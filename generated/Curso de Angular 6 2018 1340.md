[Curso de Angular 6 2018 1340](https://platzi.com/cursos/angular-avanzado)

# Introducción [2345]

## 0010. Introducción al Curso [12744](https://platzi.com/clases/1340-angular-avanzado/12744-introduccion-al-curso4105/)

### Descripción:


En este curso veremos aspectos avanzados de Angular. Crearemos un proyecto completo llamado Platzinger.

Consideraciones previas:

* Usaremos Github
* Ocurrirán errores (intencionales o no intencionales)
* Iremos rápido en aspectos básicos.



Es recomendable que hayas tomado antes el [Curso de Angular 4](https://platzi.com/cursos/angular/) también disponible en Platzi.

Contenidos de este curso:

* Introducción
* Estructura del proyecto Platzinger
* Angular y Typescript
* Estilos
* Acceso a Datos
* Edición y subida de imágenes
* Conversaciones
* Amigos
* Deploy



### Comentarios:

* **Paulina Zoffoli** (6) [402476](https://platzi.com/comentario/402476/) 

	por qué es recomendable hacer el Curso de Angular 4 ? en este curso de angular 6 no parten desde 0?

	* **hansfpc** [402476] (1)

		tengo la misma duda!

	* **Jecsham Castillo** [402476] (1)

		Este curso se considera el Avanzado de Angular

	* **Didier Axel Gulden** [402476] (4)

		Debería de ser Angular 6 Avanzado el titulo

* **Jhonnatan Duque Ramos** (4) [379275](https://platzi.com/comentario/379275/) 

	Me certifique en Angular 4, no me puedo perder este curso!!

* **Ariel Virgilio Solano Gonzalez** (3) [594970](https://platzi.com/comentario/594970/) 

	Hola, actualmente la version de Angular es la 7, se llevan de la mano o son diferentes?

	* **Jean Carlos Nuñez Hernandez** [594970] (2)

		Si te refieres a que si es compatible hacia las versiones anteriores, si es muy compatible, pero mas que todo ng7 requieres es una version suoperior de node y de npm para funcionar adecuadamente

	* **Diego Alexander Forero Higuera (Platzi)** [594970] (1)

		Angular siempre mantiene compatibilidad con la versión anterior, por ejemplo la versión 5 era compatible con la 4, la versión 6 con la 5 pero no tanto con la 4 (muchos cambios) la versión 7 compatible con la 6 pero poco con la 5 y menos con la 4, es el ciclo de desarrollo de angular, ademas que sacan versiones muy seguido cada 6 meses.

	* **Ariel Virgilio Solano Gonzalez** [594970] (1)

		Bien, osea que puedo tomar el curso de Angular6 teniendo instalado Angular 7, sera lo mismo?

	* **Diego Alexander Forero Higuera (Platzi)** [594970] (2)

		@Arisolgo Si, teniendo angular 7 puedes seguir este curso.

	* **Luis Vides** [594970] (1)

		Te recomiendo instalar Angular 6 y luego ver las diferencias con la versión 7… te podría dar error en algunas cosas.  
		Para instalar angular 6 te recomiendo este comando:
		``` 
		    npm install -g @angular/cli@6.1.*
		    
		```

* **Gianfranco  Verrocchi** (3) [545042](https://platzi.com/comentario/545042/) 

	Si utilizan el editor visual studio code, les recomiendo este video:  
	[https://www.youtube.com/watch?v=xBVGxIuAATs](url)  
	El autor recomienda varias extensiones muy utiles para desarrollar en angular.

* **WilliWonk** (3) [505783](https://platzi.com/comentario/505783/) 

	Pero este es el avanzado? ¿donde encuentro el curso mas basico?

* **tono2** (3) [406645](https://platzi.com/comentario/406645/) 

	Hola es necesario hacer el curso de Angular 4 para hacer este curso??
	
	gracias

	* **Poseidonihp** [406645] (21)

		No es necesario porque se ven conceptos basicos igual que en el de Angular 4 sino sabes nada de Angular vas a aprender lo mismo solo que mas Actualizado.

* **edg_colon** (2) [366890](https://platzi.com/comentario/366890/) 

	Muy bien, el anterior curso de angular me servio de mucho para complementar una app que estoy desarrollando con ionic-angular.!  
	Saludos platzi

* **Carla Patricia Arauz Gonzales** (1) [1020790](https://platzi.com/comentario/1020790/) 

	¿Qué es mejor, Angular 9 o Flutter(Dart) para programar PWAs?

* **ehnbytes** (1) [1015143](https://platzi.com/comentario/1015143/) 

	Iniciando el curso!!

* **Emanuel Marcelo Acuña Gimenez** (1) [853319](https://platzi.com/comentario/853319/) 

	Hola, que requisitos previos necesito para tomar el curso?

	* **Gabriel De Andrade (Platzi)** [853319] (6)

		Hola! Te recomiendo:
		
		* [Curso de Programación Básica](https://platzi.com/clases/programacion-basica/)
		* [Curso de Prework (opcional)](https://platzi.com/clases/prework/)
		* [Curso de Fundamentos de JavaScript](https://platzi.com/clases/fundamentos-javascript/)
		* [Curso de jQuery a JavaScript (opcional)](https://platzi.com/clases/jquery-js/)
		* [Curso de TypeScript con Angular.](https://platzi.com/clases/typescript-angular/)
		
		
		
		Por otra parte si esta es tu primera vez aprendiendo sobre un framework y no necesitas justo Angular 6 te recomiendo el [Curso de Angular](https://platzi.com/clases/angular/) sobre este. También recuerda que siempre puedes pedir tu ruta de aprendizaje escribiendo un correo a [team@platzi.com](mailto:team@platzi.com)

* **kevinenriquearciniegaschacon** (1) [642139](https://platzi.com/comentario/642139/) 

	Hola

* **juanbarcinilla** (1) [635864](https://platzi.com/comentario/635864/) 

	Muy buenas amigos, estoy tratando de cambiar la libreria import { Http} from ‘@angular/http’; por import { HttpClient } from ‘@angular/common/http’; en mi proyecto, pero me sale el siguiente error.
	``` 
	    import { Injectable } from '@angular/core';
	    import { Headers, ResponseContentType, RequestMethod } from '@angular/http';
	    import { environment } from '../../environments/environment';
	    import { map } from 'rxjs/operators';
	    import { HttpClient } from '@angular/common/http';
	    @Injectable({
	      providedIn: 'root'
	    })
	    export class HomeService {
	      constructor(private _http: HttpClient) {
	        
	      }
	    
	    
	      descargarEXE(arquitectura: Number) {
	        returnthis._http.post(environment.url + "descargarexe", arquitectura, {
	          method: RequestMethod.Post,
	          responseType: ResponseContentType.Blob,
	          headers: new Headers({ 'Content-Type': 'text/plain' })
	        }).pipe(map(res => res.blob()));
	      }
	    }
	    
	    
	```
	
	Error  
	Type ‘ResponseContentType.Blob’ is not assignable to type ‘“json”’.ts(2322)  
	client.d.ts(1854, 9): The expected type comes from property ‘responseType’ which is declared here on type ‘{ headers?: HttpHeaders | { [header: string]: string | string[]; }; observe?: “body”; params?: HttpParams | { [param: string]: string | string[]; }; reportProgress?: boolean; responseType?: “json”; withCredentials?: boolean; }’
	
	Si alguien me pude colaborar le agradeciere.

* **Ruben Garcia** (1) [555977](https://platzi.com/comentario/555977/) 

	Sigamos con Angular

* **Brayan Mamani** (1) [555124](https://platzi.com/comentario/555124/) 

	Me gusto mucho el curso de Angular 4, espero que este curso sea igual de bueno.

* **Alex Eugenio Gavidia Donayre** (1) [535066](https://platzi.com/comentario/535066/) 
Deploy

* **Alex Eugenio Gavidia Donayre** (1) [535065](https://platzi.com/comentario/535065/) 
A darle con todo. 😎

* **Camilo Medina** (1) [521485](https://platzi.com/comentario/521485/) 

	Estoy usando el componente de mapas del API de javascrpt para Arcgis, funciona para angular 6 muy bien pero para angular 7 tiene dificultades, para llamar algunos métodos de las clase. Saben algo que me pueda ayudar?

* **lmarinb** (1) [518274](https://platzi.com/comentario/518274/) 

	Estara Bueno el Curso.!!

* **Jhon Carlos   Romo Ramirez** (1) [514035](https://platzi.com/comentario/514035/) 

	Tengo problemas para descargar los archivos.

* **ArianaX13** (1) [503254](https://platzi.com/comentario/503254/) 

	Una consulta , yo tengo una empresa de desarrollo de erps y post queremos migrar al la web  
	me recomiendas angular? trabajamos con .net AWS y q componentes de terceros recomiendas para angular  
	gracias.

* **Spyderp** (1) [440857](https://platzi.com/comentario/440857/) 

	me encanta el punto vamos a ir rápido

* **Cristian David Franco Garcia** (1) [430241](https://platzi.com/comentario/430241/) 

	Buenas noches, para el despliegue de la aplicación explican como hacerlo haciendo uso de certificados https?

	* **Henderson Said Franco Cruz** [430241] (1)
Aún tienes está duda?

	* **Cristian David Franco Garcia** [430241] (1)

		Si

* **Carlos Uriel de Jesus Sánchez González** (1) [395581](https://platzi.com/comentario/395581/) 

	Ahh empezar después del curso de Angular 4

* **CesarVilo** (1) [392083](https://platzi.com/comentario/392083/) 

	jajaja, que onda, es el mismo profe del curso de angular 4, Super!!!

	* **ricardocelis (Platzi)** [392083] (1)

		siiii, es genial! Bienvenido

* **Diego Burlando** (1) [364919](https://platzi.com/comentario/364919/) 

	Un paso mas para convertirme en todo un experto en Angular, deseo que este curso sea de mucha utilidad para mi vida de programador.

* **Ariel Virgilio Solano Gonzalez** (1) [59716](https://platzi.com/comentario/594970/) 
Hola, actualmente la version de Angular es la 7, se llevan de la mano o son diferentes?

	* **Jean Carlos Nuñez Hernandez** [59716] (2)

		Si te refieres a que si es compatible hacia las versiones anteriores, si es muy compatible, pero mas que todo ng7 requieres es una version suoperior de node y de npm para funcionar adecuadamente

* **Camilo Medina** (1) [53753](https://platzi.com/comentario/521485/) 
Estoy usando el componente de mapas del API de javascrpt para Arcgis, funciona para angular 6 muy bien pero para angular 7 tiene dificul...

* **tono2** (1) [44302](https://platzi.com/comentario/406645/) 
Hola es necesario hacer el curso de Angular 4 para hacer este curso?? gracias

	* **Poseidonihp** [44302] (21)

		No es necesario porque se ven conceptos basicos igual que en el de Angular 4 sino sabes nada de Angular vas a aprender lo mismo solo que mas Actualizado.

## 0020. Introducción a Angular [12745](https://platzi.com/clases/1340-angular-avanzado/12745-intro-a-angular/)

### Descripción:


Angular es un framework basado en Typescript con el que se pueden crear Single Page Applications (SPAs) o aplicaciones web de una sola página. Está basado en Yypescript que es un superset de Javascript, que incorpora elementos adicionales al lenguaje como: Tipos, Clases e Interfaces.

Angular CLI es set de herramientas de línea de comandos que permiten agilizar tareas de: transpilación del código, creación de servidor local, generación automática de recursos para la app, entre otras.

Angular ha pasado por las versiones 1, 2, 4, 5 y 6 con diversas actualizaciones regulares cada 6 meses. El salto de la versión 3 a la 4 se debió a una decisión del equipo de desarrollo del framework para alinear todos los componentes y dependecias a una misma versión, ya que, por ejemplo Angular Router ya estaba en 3.x

### Comentarios:

* **Carlos Uriel de Jesus Sánchez González** (9) [395595](https://platzi.com/comentario/395595/) 

	 **Angular** es un framework basado en Typescript con el que se pueden crear Single Page Applications (SPAs) o aplicaciones web de una sola página.  
	**SPA** es una aplicación completa que corre en una sola página (index.html comúnmente).  
	**Typescript** es un superset de Javascript, es un agregado a javaScript, no lo reemplaza, que incorpora elementos adicionales al lenguaje como: Tipos, Clases e Interfaces.  
	**Angular CLI** es set de herramientas de línea de comandos que permiten agilizar tareas de: transpilar el código, creación de servidor local, generación automática de recursos para la app, entre otras.
	
	Angular ha pasado por las versiones 1, 2, 4, 5 y 6 con diversas actualizaciones regulares cada 6 meses. El salto de la versión 3 a la 4 se debió a una decisión del equipo de desarrollo del framework para alinear todos los componentes y dependencias a una misma versión, ya que, por ejemplo Angular Router ya estaba en 3.x

* **Neider Rafael Tapia Avila** (4) [392618](https://platzi.com/comentario/392618/) 
Hola @eduardoIbarra como haz hecho en tu empresa de desarrollo con el tema de las versiones. Es decir si tienes una app web con angular 4 tienes que morir con esa versión?

	* **omar1893** [392618] (1)

		Pues con angular 2+ no sucede mucho esto, yo hace poco acabo de saltar de la version 5 a la 6, sin muchas complicaciones. Si bien no es un proceso indoloro, no es tan tedioso como uno pensaria.

* **Jeffry Davila** (4) [384463](https://platzi.com/comentario/384463/) 

	para ver este curso tengo que tener conocimiento previos de angular?

	* **ricardocelis (Platzi)** [384463] (6)

		ayuda mucho que te hayas pasado el curso de Angular 4 pero si prefieres tmbn puedes arrancar con este =)

	* **Jeffry Davila** [384463] (1)

		Muchas gracias.

	* **Teofilo Rosales Gama** [384463] (2)

		yo estoy empezando defrente con este no me gusta el angular 4 demasiado desactualizado(conocimiento basico angular by youtube)

	* **Brayan Mamani** [384463] (1)

		El profesor explica las clases muy bien.

* **Alex Eugenio Gavidia Donayre** (3) [535068](https://platzi.com/comentario/535068/) 
Typescript

* **franciscolesm22226d48ae644859** (2) [659234](https://platzi.com/comentario/659234/) 

	Muy Buena Temática

* **MauroIvan** (2) [618268](https://platzi.com/comentario/618268/) 

	en la universidad a la que asisto nos enseñaron a usar angular en la versión 2 😦

	* **Andres Rodriguez (Platzi)** [618268] (1)

		No es del todo malo, de hecho tiene mérito que una Universidad enseñe por lo menos un stack de tecnología web completo. Y entre Angular 1.x a Angular 2.x+ hay un mundo de diferencia, en este último la gran mayoría de conceptos se mantienen hasta la versión 6.

* **Alex Eugenio Gavidia Donayre** (2) [535067](https://platzi.com/comentario/535067/) 
SPA( Single Page Application)

* **Juan Carlos Felizzola Vega** (2) [383686](https://platzi.com/comentario/383686/) 

	 **TypeScript:**<https://www.typescriptlang.org/>  
	**Angular CLI:**<https://cli.angular.io/>

* **Diego Vicencio** (1) [792849](https://platzi.com/comentario/792849/) 

	Ya esta terminando el soporte para angular 6

	* **Demian Arenas (Platzi)** [792849] (3)

		Hola Diego, lo sabemos y por eso hace poco lanzamos un [curso de Angular 8](https://platzi.com/clases/angular)

	* **eliasmmata** [792849] (1)

		qué es mejor entonces empezar por este o ir directamente al curso de Angular 8??

* **juanbarcinilla** (1) [637232](https://platzi.com/comentario/637232/) 

	Muy buena introducción.

* **diegocruz** (1) [481603](https://platzi.com/comentario/481603/) 

	Hay forma de tener varias versiones corriendo en una sola maquina? o necesariamente cada que sube de version angular debo hacer un update de mis proyectos?

	* **Andres Rodriguez (Platzi)** [481603] (2)

		Puedes tener varias versiones corriendo sin problema, sin embargo te recomiendo usar **nvm** que permite manejar varias versiones de node en la misma maquina, para mayor seguridad de no cruzarte con otros paquetes.

* **Raul Villca** (1) [458795](https://platzi.com/comentario/458795/) 

	Una pregunta… se que podría googlearlo pero me gustaría saber si me podrían ayudar…  
	Hay algún link en este curso para saber como agregar un componente en otro componente?  
	Lo que pasa es que no me gustaría tener un popup en mi componente dashboard… preferiría tenerlo modular… Aunque claro el login es estatico… pero es solo para probar esta idea. Gracias!

* **kikekeys** (1) [69648](https://platzi.com/comentario/760690/) 
Desde el segundo 30 que empieza definir una SPA entiendo entonces que un framework/librería orientado a componentes(...

	* **Juan David Castro (Platzi)** [69648] (1)

		Nope. Angular, Vue, React y muchas otras herramientas nos permiten construir diferentes tipos de aplicaciones. No solo Single Page Applications.
		
		Inicialmente, podemos comenzar con SPAs, es lo más sencillo y muchas veces lo más funcional. Pero en caso de que necesitemos otros tipos de renderizado/arquitectura, claro que podemos usarlos.
		
		👉 [Server Side Rendering con Angular Universal](https://angular.io/guide/universal)  
		👉 [Single Page Applications vs. Server Side Rendering vs. Generadores de Sitios Estáticos](https://platzi.com/blog/spa-vs-ssr-vs-static-site-generators/)

* **diegocruz** (1) [50603](https://platzi.com/comentario/481603/) 
Hay forma de tener varias versiones corriendo en una sola maquina? o necesariamente cada que sube de version angular debo hacer un updat...

	* **Andres Rodriguez (Platzi)** [50603] (2)

		Puedes tener varias versiones corriendo sin problema, sin embargo te recomiendo usar **nvm** que permite manejar varias versiones de node en la misma maquina, para mayor seguridad de no cruzarte con otros paquetes.

## 0030. Configurando nuestro proyecto en Git y Github [12746](https://platzi.com/clases/1340-angular-avanzado/12746-configurando-nuestro-proyecto-en-git-y-github/)

### Descripción:


Git es un sistema de control de versiones. Github, por su parte, es una comunidad online para crear, organizar y compartir repositorios de proyectos que usan Git.

Para usar Git se debe descargar e instalar la aplicación base de Git (el procedimiento de instalación difiere un poco en Windows, en comparación con Linux y Mac). Una vez instalado Git, tendremos acceso a la ejecución de los comandos desde la consola del sistema. Si no estás familiarizado con esta herramienta puedes completar el [Curso profesional de Git y Github](https://platzi.com/cursos/git-github) también disponible en Platzi.

### Links:

* [Git - Downloads](https://git-scm.com/download)

### Comentarios:

* **JDiaz0017** (9) [363094](https://platzi.com/comentario/363094/) 

	Hola, en este punto quienes utilizamos windows, les recomiendo mucho la consola de GitBash, no me ha dado problemas y me reconoce casi todos los comandos (basados en UNIX) sin problemas, al momento de instalar dependencias, configurar variables de entorno entre muchos otros comandos útiles.

	* **Diego Burlando** [363094] (3)

		Siempre utilizo gitbash, es muy útil, gracias por el aporte.

	* **Hebert  lughi villafuerte ccacala** [363094] (1)

		la powershell soporta comandos de unix en windows 😃

* **Juan Carlos Pinzón** (4) [414229](https://platzi.com/comentario/414229/) 

	Sino te gusta la consola de Git un muy buen cliente es [SourceTree](https://www.sourcetreeapp.com/)

* **Teofilo Rosales Gama** (4) [387500](https://platzi.com/comentario/387500/) 

	Otra opcion puede ser VScode con su integracion con git(usuarios windows)

	* **ramefx** [387500] (1)

		Excelente opción, personalmente es la que utilizo

* **Joss** (3) [489223](https://platzi.com/comentario/489223/) 

	Aca les dejo el curso de git, Leonidas es fenomenal.  
	<https://platzi.com/clases/git-github/>

	* **Brayan Mamani** [489223] (1)

		Es un excelente curso.

* **kevinenriquearciniegaschacon** (2) [642159](https://platzi.com/comentario/642159/) 

	Saludos recoiendo para los que no saben manejar comandos utilicen source tree <https://www.sourcetreeapp.com/>

	* **Andres Rodriguez (Platzi)** [642159] (2)

		O este <https://www.gitkraken.com/>, sin embargo saber usar GIT por línea de comandos siempre es más recomendable y apoyarse en un GUI como complemento.

* **orivasm44** (2) [450472](https://platzi.com/comentario/450472/) 

	Hola Les recomiendo un complemento para VSCode llamado** GitLens **es de mucha ayuda, sirve para ver quién realizo la ultima modificación y algunas otras cosa.

* **jeisonsrz** (2) [414762](https://platzi.com/comentario/414762/) 

	Saludos, una alternativa para equipos de desarrollo profesional es Bitbucket.

* **omar1893** (2) [403844](https://platzi.com/comentario/403844/) 

	Tambien recomiendo Gitkraken es muy bueno

* **javieralbadan** (1) [671318](https://platzi.com/comentario/671318/) 

	Yo use durante un buen tiempo SourceTree, me cambié a GitKraken pero hace poco me enteré que después de un update en 19 de junio de 2019, ya no permite trabajar con repositorios privados para las cuentas gratuitas. Punto a tener en cuenta al momento de decidir!

	* **aerama** [671318] (3)

		lo mejor que puedes hacer es usar la consola.

* **Alex Eugenio Gavidia Donayre** (1) [535071](https://platzi.com/comentario/535071/) 
Source tree

	* **yastilleros** [535071] (1)

		Si, también pienso que SourceTree es una de las mejores herramientas

* **jhonnyzapata** (1) [524319](https://platzi.com/comentario/524319/) 

	Hola yo uso mucho GitKraken como cliente para Git y me ha gustando bastante la interface gráfica que maneja en cuanto a como se ven las ramas y todo lo referente, cabe resaltar que algunas veces falla pero no es nada que no se pueda solucionar con un par de lineas en la terminal.

* **Wilson Marino Pablo Mendez** (1) [515906](https://platzi.com/comentario/515906/) 

	Interesante el proyecto!!!

* **ramefx** (1) [479099](https://platzi.com/comentario/479099/) 

	Genial en lo presonal utilizo la creacion de commits, branchs, etc desde la herramineta git que viene integrado en visual studio code

* **Alfonso Adame Rueda** (1) [443205](https://platzi.com/comentario/443205/) 

	yo siempre he usado gitbash y me ha ido muy bien, ademas desde ahí controlo las versiones de mi proyecto, reutilizo código, y me permite volver a la versión anterior en caso de errores

* **alejandrarock** (1) [403783](https://platzi.com/comentario/403783/) 

	Yo utilizo cmder console: <http://cmder.net/>  
	En esta consola puedes usar varios comandos de UNIX y tener divisiones del terminal a tu gusto, lo recomiendo totalmente.  
	![](https://drive.google.com/file/d/1FomAWCCj86L6Blqgi8JzNNDvkIrTSgaL/view?usp=sharing)

* **Carlos Uriel de Jesus Sánchez González** (1) [396037](https://platzi.com/comentario/396037/) 

	es mejor usar la consola gitbash

* **Juan Carlos Felizzola Vega** (1) [383814](https://platzi.com/comentario/383814/) 

	Otra opción para los que les gusta más con interfaces es **GitHub Desktop** :  
	<https://desktop.github.com/>

## 0040. Introducción a Angular CLI y al proyecto de Platzinger [12747](https://platzi.com/clases/1340-angular-avanzado/12747-intro-a-angular-cli-y-al-proyecto-de-platzinger/)

### Descripción:


**Platzinger** es una app de mensajería instantánea inspirada en _MSNmessenger_ , y con la cual podremos explotar mucho del potencial de lo que podemos hacer con Angular. Algunas de las características que tendrá esta app son:

* Registrarnos y hacer login
* Se podrán agregar amigos
* La comunicación será en tiempo real
* Subir fotos
* Se podrán enviar zumbidos
* y mucho más.



### Comentarios:

* **Jecsham Castillo** (12) [448807](https://platzi.com/comentario/448807/) 
	
	![14817385.jpg](https://static.platzi.com/media/user_upload/14817385-3df0cbbe-008c-47f6-aa71-8eb45d0a0faf.jpg)

* **edg_colon** (6) [366892](https://platzi.com/comentario/366892/) 

	Genial

* **bryanmedina** (4) [664489](https://platzi.com/comentario/664489/) 

	sin llorar :’)

* **Carlos Uriel de Jesus Sánchez González** (3) [396039](https://platzi.com/comentario/396039/) 

	proyecto de nostalgia!!!

* **Gerardo Manuel Reyes Fernández** (3) [364346](https://platzi.com/comentario/364346/) 
	
	![](https://media.aweita.larepublica.pe/678x508/aweita/imagen/2018/05/13/noticia-portadacoco.png)

	* **Jhon Castrillon** [364346] (1)

		bn

* **YojanPardo** (1) [1003369](https://platzi.com/comentario/1003369/) 

	aqui no vimos nada de Angular CLI, hay que corregir el título

* **basanchez** (1) [1000449](https://platzi.com/comentario/1000449/) 

	Espero poder conectarlo con Windows Media Player jajajaj

* **EstebanBoada** (1) [823987](https://platzi.com/comentario/823987/) 

	Que Triste pero a la vez … que motivación!

* **christian-magro-perez** (1) [818925](https://platzi.com/comentario/818925/) 

	¡Emocionante, que recuerdos!

* **kevinenriquearciniegaschacon** (1) [642163](https://platzi.com/comentario/642163/) 

	justo en mi infancia 😦

* **Manuel Ojeda** (1) [636575](https://platzi.com/comentario/636575/) 

	Justo en la nostalgia 😥

* **MauroIvan** (1) [618271](https://platzi.com/comentario/618271/) 

	que triste

* **Luis Sebastián Cubillos Carrasco** (1) [617196](https://platzi.com/comentario/617196/) 

	Directo en el corazón :C

* **Brayan Mamani** (1) [555138](https://platzi.com/comentario/555138/) 

	Un proyecto para recordar a una de las primeras redes sociales. 😃

* **Alex Eugenio Gavidia Donayre** (1) [535075](https://platzi.com/comentario/535075/) 
Nick

* **Alex Eugenio Gavidia Donayre** (1) [535074](https://platzi.com/comentario/535074/) 
Vamossssss

* **Alex Eugenio Gavidia Donayre** (1) [535073](https://platzi.com/comentario/535073/) 
Nostalgia 😢😝

* **Jhon Castrillon** (1) [530278](https://platzi.com/comentario/530278/) 

	SuperMSN

* **Meliza villafuerte rayme** (1) [516438](https://platzi.com/comentario/516438/) 

	Si es que ejecuto “ng serve --open”, se abre la aplicación en el navegador. Si es que cierro esta terminal, entonces ¿Como puedo terminar la ejecución del servidor virtual (localhost:4200)?

	* **aragonesteban (Platzi)** [516438] (1)

		En la terminal con `Ctrl + C` o `Command + C` puedes cancelar los procesos que se están ejecutando, si cierras la terminal donde se esta ejecutando el proceso por defecto se cancela los procesos.

* **Alfonso Adame Rueda** (1) [511845](https://platzi.com/comentario/511845/) 

	angular es un framework del paradigma de programación asíncrona,lo cual lo vuelve mas reactivo, una característica , entre muchas otra son los observables, el cual es un estándar para administrar datos en un canal de comunicación ,donde las valores se pueden incluir en cualquier momento.

* **Alfonso Adame Rueda** (1) [511844](https://platzi.com/comentario/511844/) 

	la ventaja de estudiar en platzi es que los cursos se complementan, no solo en la misma linea de estudio u otras ,los cursos en platzi apuntan a un todo, que es el conocimiento, desde el cual podemos construir un mejor mañana para cada uno de nosotros.

* **Miguel Angel Sirlopu Cumpa** (1) [466073](https://platzi.com/comentario/466073/) 

	Que nostalgia!!

* **programanime** (1) [441719](https://platzi.com/comentario/441719/) 

	Excelente!!

* **Spyderp** (1) [440867](https://platzi.com/comentario/440867/) 

	😄 😄 😄

* **mario-salinas** (1) [424372](https://platzi.com/comentario/424372/) 

	Con toda la actitud para hacer este curso!

* **Juan Pena Verdú** (1) [417736](https://platzi.com/comentario/417736/) 

	Tremendo!

* **alejandrarock** (1) [403784](https://platzi.com/comentario/403784/) 

	😄

* **Felipe Cardona** (1) [389973](https://platzi.com/comentario/389973/) 

	hace cuanto se lanzo este curso ?

* **Juan Diego Lopez Triana** (1) [370909](https://platzi.com/comentario/370909/) 

	Que buen proyecto.

* **Anthony Gonzalez** (1) [365160](https://platzi.com/comentario/365160/) 

	Justo en el cocoro

* **Diego Burlando** (1) [364928](https://platzi.com/comentario/364928/) 

	Esta genial este proyecto

* **jeison0712Ramirez** (1) [364352](https://platzi.com/comentario/364352/) 

	Se ve muy bien QUE EMOCIÓN

* **Juan Antonio Baracat** (1) [363641](https://platzi.com/comentario/363641/) 

	wow! esto se está poniendo muy interesante!

* **eddyarellanes** (1) [363581](https://platzi.com/comentario/363581/) 

	Ohhh MSN que tiempos :’)

* **Victor Alejandro Alvarez Tallada** (1) [363340](https://platzi.com/comentario/363340/) 

	Se ve muy bien.  
	Pega en la nostalgia. 😢+😁

* **Meliza villafuerte rayme** (1) [53331](https://platzi.com/comentario/516438/) 
Si es que ejecuto “ng serve --open”, se abre la aplicación en el navegador. Si es que cierro esta terminal, entonces ¿Como puedo terminar...

	* **aragonesteban (Platzi)** [53331] (1)

		En la terminal con `Ctrl + C` o `Command + C` puedes cancelar los procesos que se están ejecutando, si cierras la terminal donde se esta ejecutando el proceso por defecto se cancela los procesos.

## 0050. Instalación del entorno de desarrollo en Mac OS [12748](https://platzi.com/clases/1340-angular-avanzado/12748-instalacion-del-entorno-de-desarrollo-en-mac-os398/)

### Descripción:


Usando el procedimiento estándar para la instalación de paquetes de MacOS, necesitaremos instalar:

* Node JS: necesario para instalar NPM, correr código de Javascript en la consola, transpilar código, entre otros. Para verificar que esté instalado ejecutamos el comando _node_ en la terminal.
* NPM: que es el instalador de paquetes que viene con Nodejs. Para verificar que esté instalado ejecutamos en la terminal el comando _npm_.
* Angular CLI: es el set de herramientas que permite correr un servidor local, generar recursos que usa la aplicación, entre otros. Para comprobar que está correctamente instalado corremos _ng_ en la consola.
* Navegador web: usaremos Chrome ya que tiene herramientas de desarrollador muy útiles para facilitar el desarrollo.
* Editor de código (IDE): usaremos Webstorm, pero puedes usar VSCode, Atom, SublimeText o cualquier otro que ya conozcas.



### Links:

* [Download WebStorm: The Smartest JavaScript IDE by JetBrains](https://www.jetbrains.com/webstorm/download)

* [Visual Studio Code - Code Editing. Redefined](https://code.visualstudio.com)

* [Angular CLI](https://cli.angular.io)

* [Node.js](https://nodejs.org/en)

### Comentarios:

* **Carlos Uriel de Jesus Sánchez González** (8) [396980](https://platzi.com/comentario/396980/) 

	  1. Instalar node desde [nodejs.org](http://nodejs.org) la versión current mas actual
	  2. En terminal verificar que esta instalado node -v
	  3. Verificar que este instalado npm con npm -v
	  4. Instalar angular cli en terminal npm install -g @angular/cli
	  5. Verificar la instalación de angular en terminal con ng -v
	  6. Tener visual studio code o webstorm
	
	

* **Alejandro Salazar** (5) [366822](https://platzi.com/comentario/366822/) 

	me ha ido muy bien con PhpStorm

	* **Juan Carlos Felizzola Vega** [366822] (1)

		Pero como vas a trabajar con **Angular** y **TypeScript** te irá mejor con WebStorm

* **Mauricio Quiñones** (2) [876212](https://platzi.com/comentario/876212/) 

	Me gusta visual Studio, tiene snipes muy practicos que ayudan al desarrollo.

* **EstebanBoada** (2) [824002](https://platzi.com/comentario/824002/) 

	Recomiendo Visual Studio

* **kevinenriquearciniegaschacon** (2) [642164](https://platzi.com/comentario/642164/) 

	Node.Js  
	<https://nodejs.org/es/>

* **jeisonsrz** (2) [414778](https://platzi.com/comentario/414778/) 

	con Webstorm si te registras con una cuenta de correo .edu te dan la licencia gratuita por un año.

	* **Brayan Mamani** [414778] (1)

		Si es una de las mejores alternativas.

	* **JESUS IVAN MENDOZA CONTRERAS** [414778] (1)

		una pregunta en que apartado me puedo registrar para obtener la prueba de un año .edu

* **israellomba** (2) [391333](https://platzi.com/comentario/391333/) 

	Para los que buscan empezar rápidamente recomiendo usar <https://stackblitz.com/> que es un editor en línea basado en VIsual Studio Code.

* **carlosextra1** (2) [362896](https://platzi.com/comentario/362896/) 

	prefiero usar sublime text!!!

	* **undefined** [362896] (1)


	* **leotangram** [362896] (7)

		Yo prefiero usar Visual Studio Code

	* **Juan Carlos Felizzola Vega** [362896] (1)

		Igual, Visual Studio Code me ha quedado muy bien con Angular o Ionic

	* **Juan Antonio Baracat** [362896] (3)

		Me pasó lo mismo! para Angular va mejor VSCode

	* **Gerardo Manuel Reyes Fernández** [362896] (2)

		Yo usaba atom hasta que un proyecto en angular requerí usar VSCode y de ahí se volvió mi principal editor.

	* **Diego Burlando** [362896] (3)

		Soy muy fan de sublime text, pero probare con VsCode a ver que tal.

	* **Juan S Jiménez Galindo** [362896] (1)

		Yo igual soy muy fan de Sublime Text, pero VSCode está muy muy completo.

	* **danieldalac** [362896] (1)

		Yo he probado Brackets IO y me parecía muy buena opción, luego migré a Sublime y me pareció excelente. Desde hace un tiempo he venido trabajando con Visual Code y creo que es una excelente alternativa también. Es muy completo y lo recomiendo.

	* **Wilson Marino Pablo Mendez** [362896] (1)

		VSCode me ha parecido completo y liviano

	* **Brayan Mamani** [362896] (1)

		Mi IDEs favoritos son de la familia de JetBrains en este caso para Angular es WebStorm.

* **javieralbadan** (1) [671449](https://platzi.com/comentario/671449/) 

	Me parece muy buena forma de abordar el curso, por parte del profe Eduardo. Pues hay cosas que no esta mal repasar o hay tips que uno no conocía.

* **Alex Eugenio Gavidia Donayre** (1) [535154](https://platzi.com/comentario/535154/) 
Node.Js

* **Spyderp** (1) [440901](https://platzi.com/comentario/440901/) 

	Si eres novato recomiendo usar un IDE como los recomendados por el profesor.  
	Los motivo nuevamente los menciono te facilita buscar errores y autocompletar código.
	
	Para usuarios más avanzados pueden usar su editor de preferencia pero preparado para usar typescript y angular. En mi caso uso SublimeText y ya lo tengo listo para autocompletar en angular.

* **Calebisma** (1) [432194](https://platzi.com/comentario/432194/) 

	Es mucho mejor VSC , sencillo y tiene mucha extensiones

* **steven zuluaga cortes** (1) [428200](https://platzi.com/comentario/428200/) 

	prefiero visual studio

* **José Luis García Peceros** (1) [422617](https://platzi.com/comentario/422617/) 

	¿Y con la versión LTS seria igual?

	* **Ildebrando Mora Valdes** [422617] (1)

		LTS significa estable y que tendrá mas soporte

* **jeisonsrz** (1) [414777](https://platzi.com/comentario/414777/) 

	Visual Studio Code (Y) y Webstorm.

## 0060. Instalación del entorno de desarrollo en Windows e información acerca del editor que usaré (WebStorm) y alternativas [12749](https://platzi.com/clases/1340-angular-avanzado/12749-instalacion-del-entorno-de-desarrollo-en-windows-e/)

### Descripción:


Usando el procedimiento estándar de instalación en Windows, instalaremos:

* Node JS: necesario para instalar NPM, correr código de Javascript en la consola, transpilar código, entre otros. Para verificar que esté instalado ejecutamos el comando _node_ en la terminal.
* NPM: que es el instalador de paquetes que viene con Nodejs. Para verificar que esté instalado ejecutamos en la terminal el comando _npm_.
* Angular CLI: es el set de herramientas que permite correr un servidor local, generar recursos que usa la aplicación, entre otros. Para comprobar que está correctamente instalado corremos _ng_ en la consola.
* Navegador web: usaremos Chrome ya que tiene herramientas de desarrollador muy útiles para facilitar el desarrollo.
* Editor de código (IDE): usaremos Webstorm, pero puedes usar VSCode, Atom, SublimeText o cualquier otro que ya conozcas.



### Links:

* [Download WebStorm: The Smartest JavaScript IDE by JetBrains](https://www.jetbrains.com/webstorm/download)

* [Visual Studio Code - Code Editing. Redefined](https://code.visualstudio.com)

* [Angular CLI](https://cli.angular.io)

* [Node.js](https://nodejs.org/en)

### Comentarios:

* **Carlos Uriel de Jesus Sánchez González** (5) [396981](https://platzi.com/comentario/396981/) 

	  1. Instalar node
	  2. instalar angular ci
	  3. Tener visual studio code o webstorm
	
	

* **Matias Cabido** (4) [420334](https://platzi.com/comentario/420334/) 

	Visual Studio tiene el auto-completado que tiene WebStorm?

	* **CaroB (Platzi)** [420334] (3)

		Sí, visual studio code tiene una lista muy grande de extensiones de auto-completado para diferentes lenguajes; solo es de ir a la sección de extensiones y buscar lo que más se adecue a la necesidad.

	* **Matias Cabido** [420334] (2)

		Genial muchas gracias por la info

	* **Alex Eugenio Gavidia Donayre** [420334] (1)
Prefiero visual studio C

	* **Brayan Mamani** [420334] (1)

		El editor de WebStorm es mejor que el de Visual Studio Code.

* **tiu80** (3) [694374](https://platzi.com/comentario/694374/) 

	el mejor editor que he probado es Visual Studio Code… superior a cualquier otro

* **Calebisma** (3) [432229](https://platzi.com/comentario/432229/) 

	Yo Prefiero VSC , es muy sencillo , gratis y tiene una cantidad de extensiones

* **Hector Daniel Hernandez Castillo** (2) [990027](https://platzi.com/comentario/990027/) 

	Aguante Atom :u

* **kevinenriquearciniegaschacon** (2) [642182](https://platzi.com/comentario/642182/) 

	Fiel a Visual Studio Code

* **herbertpro** (2) [554433](https://platzi.com/comentario/554433/) 

	Les comento que curioseando en la web de webstorm. encontre que tienen una politica de licencias free para estudiantes universitarios, solo tienen que disponer de un correo del estilo @universidad.edu.pe por ejemplo. aplique, y en menos de 5 minutos me dieron la licencia y pude descargar webstorm gratis.

* **Teofilo Rosales Gama** (2) [387530](https://platzi.com/comentario/387530/) 

	Primer comentario8-)

* **juanbarcinilla** (2) [62279](https://platzi.com/comentario/637252/) 
Como especificar la versión a instalar del angular global?

	* **Manuel Ojeda** [62279] (1)

		Si haz descargado CLI bajas la versión más reciente, por lo que puedes hacer lo siguiente:
		
		  1. Ejecuta dependiendo de la versión que necesites, en este caso siendo Angular 6:
		
		
		``` 
		    npm install -g @angular/cli@6
		    
		```
		
		  1. Ve y parate sobre el la carpeta que vas a trabajar
		
		  2. Creas el proyecto, por ejemplo
		
		
		
		``` 
		    ng new my-ng6-app
		    
		```
		
		Y listo, así tienes tu proyecto en Angular 6, saludos.

* **marioamaciasortiz** (1) [825133](https://platzi.com/comentario/825133/) 

	pues el sublime 3 estaba con ganas y el VS Code tambien esta muy bien

* **formacionadv3** (1) [755081](https://platzi.com/comentario/755081/) 

	WebStorm es de pago

	* **robertarnaldo99** [755081] (1)

		Es bueno pero caro es. No me convence.

* **Brayan Mamani** (1) [555145](https://platzi.com/comentario/555145/) 

	Utilizo Web Storm para Angular.

* **cesarcadavid** (1) [550275](https://platzi.com/comentario/550275/) 

	Hola compañeros quiisera saber que extensiones de VSC son las que usan y cual es su utilidad gracias 😄

	* **Angel Hernandez** [550275] (1)

		Visual Studio Code? Si es asi, yo utilizo:
		
		* [PHP Intellisense](https://marketplace.visualstudio.com/items?itemName=felixfbecker.php-intellisense)
		* [Prettier](https://prettier.io/)
		* [Bracket pair colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
		* [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
		
		

	* **Carlos Flores** [550275] (1)

		  1. TypeScript Importer.  
		2.JavaScript (ES6) code snippets
		  2. Material Icon Theme.
		  3. JS-CSS-HTML Formatter
		  4. Bracket Pair Colorizer
		
		

* **Alex Eugenio Gavidia Donayre** (1) [535168](https://platzi.com/comentario/535168/) 
npn para instalar paquetes y dependencias

* **Alex Eugenio Gavidia Donayre** (1) [535164](https://platzi.com/comentario/535164/) 
Node.js npn para instalar librerías

* **lmarinb** (1) [526614](https://platzi.com/comentario/526614/) 

	Me voy con WebStorm 👌

* **jhonnyzapata** (1) [524327](https://platzi.com/comentario/524327/) 

	WebStorm permite descargar el id licenciado por un año mediante el uso de una cuenta institucional como por ejemplo la de una universidad, para los que les interese probar el editor esta es una de las mejores formas de tenerlo por un año para disfrutarlo de forma gratuita.

* **waldoaraque** (1) [522748](https://platzi.com/comentario/522748/) 

	Soy fiel a Atom

* **cesarcadavid** (1) [56251](https://platzi.com/comentario/550275/) 
Hola compañeros quiisera saber que extensiones de VSC son las que usan y cual es su utilidad gracias 😄

	* **Angel Hernandez** [56251] (1)

		Visual Studio Code? Si es asi, yo utilizo:
		
		* [PHP Intellisense](https://marketplace.visualstudio.com/items?itemName=felixfbecker.php-intellisense)
		* [Prettier](https://prettier.io/)
		* [Bracket pair colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
		* [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
		
		

* **Matias Cabido** (1) [45483](https://platzi.com/comentario/420334/) 
Visual Studio tiene el auto-completado que tiene WebStorm?

	* **CaroB (Platzi)** [45483] (3)

		Sí, visual studio code tiene una lista muy grande de extensiones de auto-completado para diferentes lenguajes; solo es de ir a la sección de extensiones y buscar lo que más se adecue a la necesidad.

## 0070. Corriendo nuestra app en el navegador [12750](https://platzi.com/clases/1340-angular-avanzado/12750-corriendo-nuestra-app-en-el-navegador/)

### Descripción:


Para generar un proyecto nuevo ejecutamos el comando de angular CLI: `ng new` con el nombre del proyecto.  
Este comando va a descargar todas las dependencias que necesita la app para correr y va a generar todo el sistema de archivos del proyecto. Puede tardar más o menos tiempo dependiendo de las características del equipo y la conexión a internet.

Una vez completado el proceso anterior navegamos a la carpeta de la aplicación y ejecutamos allí el comando `ng serve --open`, con el que se ejecutará un servidor web local para poder correr nuestra app. La bandera `--open` le indica al comando que una vez iniciado el servidor http, abrá una ventana del navegador en la url de la app en `http://localhost:4000`.

### Comentarios:

* **Luis Vides** (11) [390798](https://platzi.com/comentario/390798/) 

	si no tienen acceso a internet pueden crear el proyecto con los comandos:
	``` 
	    $ ng new platzinger --skip-install
	    $ cd platzinger
	    $ npm install
	    
	```
	
	(Probado en Debian)

	* **Alex Eugenio Gavidia Donayre** [390798] (1)

		Buen dato.

* **salocho** (5) [426721](https://platzi.com/comentario/426721/) 

	Para instalar librerías no hay necesidad de parar el server, en mi caso uso Visual estudio code y en el menu ver -> “terminal integrado” puedo abrir muchas terminales, donde puedo tener en una terminal corriendo el server y en otra instalando librerías, ver imagen: ![VisualStudioCode.png](https://static.platzi.com/media/user_upload/VisualStudioCode-27da591d-57f8-473e-b063-86e50a8c6de8.jpg)

	* **Alex Eugenio Gavidia Donayre** [426721] (1)

		**Buen dato.**

* **Mauricio Peña** (3) [749764](https://platzi.com/comentario/749764/) 

	Que formato de estilos debemos usar:
	
	css  
	SCSS  
	Sass  
	Less  
	Stylus?

	* **kikekeys** [749764] (2)

		Es una cuestión personal, personalmente empecé usando stylus y ahora uso scss, cuando creas un proyecto con angular cli te da a elegir si quieres usar un preprocesador o no, es decir css pelón.

* **David Flores** (3) [694936](https://platzi.com/comentario/694936/) 

	Una abreviación para correr el proyecto sería:
	``` 
	    ng serve -o
	    
	```

	* **william andres rodriguez borja** [694936] (4)

		```
		    ng s
		    
		```
		
		Esta el la version mas corta.

* **Jose Minaya Castañeda** (3) [511766](https://platzi.com/comentario/511766/) 

	A mi me salio would yo like to add angular routing?

	* **WilliWonk** [511766] (1)

		A mi tambien y no se para que se usa

	* **Wilson Marino Pablo Mendez** [511766] (1)

		Para trabajar con rutas…

	* **Alex Eugenio Gavidia Donayre** [511766] (1)

		Es para trabajar con rutas, en caso decidas colocar “N” te creará en la ruta **C:Windows\Users[Usuarios]** nombre de usuario.

* **Diego Burlando** (3) [364945](https://platzi.com/comentario/364945/) 

	ng serve -o tambien sirve.

	* **Godwiki1005** [364945] (2)

		lo que hace ng serve es correr el server y el flag de -o nos el proyecto directamente en nuestro navegador, tambien puedes cambiar el puerto por donde correcon el flag --port=(el puerto de tu eleccion)

* **sergio-medina93** (2) [648789](https://platzi.com/comentario/648789/) 

	Mientras en el compu del profe se instala todo en segundos…el mio toma minutos 😦

* **WilliWonk** (2) [513054](https://platzi.com/comentario/513054/) 

	a mi me pide unas validaciones al momento de crear el proyecto ¿que es lo mas recomendable? ¿y por que?
	
	![](https://scontent.feoh3-1.fna.fbcdn.net/v/t1.0-9/52387426_2269163146462222_8910495519155945472_n.jpg?_nc_cat=101&_nc_ht=scontent.feoh3-1.fna&oh=21c9a3fd1e456523fe8cf283acf9643d&oe=5CF59A07)

	* **Wilson Marino Pablo Mendez** [513054] (1)

		Al parecer esta pidiendo que si quieres integrar los pre procesadores en tu proyecto.

	* **cesrafa** [513054] (1)

		WilliWonk, esta es una característica del comando `ng new`, la cual te permite configurar tu proyecto rápidamente.  
		Angular routing te configura el manejo de las URL y las direcciones dentro de tu proyecto, y el formato de estilo (stylesheet format) tiene que ver con pre-procesadores de CSS.

* **Hebert  lughi villafuerte ccacala** (2) [461333](https://platzi.com/comentario/461333/) 

	como puedo juntar django con angular 😃

	* **ElizabethLopezSanchez** [461333] (1)

		Has una api rest con django y luego con angular has el frontend que consuma el api mediante axios quizá.
		
		Como consejo: No trates de hacer una aplicación monolótica incluyendo angular en la misma aplicación de django, normalmente eso te obliga a quitarle funcionalidades que le dan su razón de ser a django.

* **Neider Rafael Tapia Avila** (2) [421880](https://platzi.com/comentario/421880/) 

	Saludos, por alguna razon mi terminal se congela, la pregunta es si con ng serve subo el servidor con que comando lo “mato”

	* **Alexander Sandoval** [421880] (1)

		En Windows cancelas la ejecución del servidor con `CTRL + c`

	* **alejandrarock** [421880] (1)

		Con `Ctrl+c` o `Ctrl+z`

	* **kikekeys** [421880] (1)

		Y si estás en sistemas UNIX, ejecuta `comand + c`

	* **Joiss Ventura Rivera** [421880] (1)

		`Ctrl+z` detiene el servicio pero lo puedes reanudar, en cambio,`ctrl+c` mata el servicio.

* **ariel Silva** (1) [673857](https://platzi.com/comentario/673857/) 

	al crear el proyecto . instalo angular routing?

	* **aragonesteban (Platzi)** [673857] (1)

		Hola Ariel!  
		No, Angular Router ya viene integrado automáticamente como dependencia en el proyecto.

	* **kikekeys** [673857] (1)

		Creo que su pregunta va más enfocada a si en el step-installation debería instalar angular routing, yo digo que si, ya solo cuando le muevas más al módulo del router ya puedes modificar/agregar tus rutas, incluso para empezar y analizar el código está bien, ¡sí instalalo!

* **kevinenriquearciniegaschacon** (1) [642193](https://platzi.com/comentario/642193/) 

	Super muy bien explicado

* **Edgar Moisés Chávez Macario** (1) [614920](https://platzi.com/comentario/614920/) 
	
	![error angular.PNG](https://static.platzi.com/media/user_upload/error%20angular-ade8fedb-e668-48a9-b832-de00e2c26f38.jpg)
	
	Ayuda tengo problemas con estos errores

	* **eduquey** [614920] (1)

		probablemente esta detras de un proxy

* **Hazel** (1) [572277](https://platzi.com/comentario/572277/) 

	Hola , tengo este error al momento de ejecutar ng serve, ya busqeue mi soluciones y nada, solamente estoy instalando ANGULAR CLI y despues ng serve y me manda este error.
	
	Agradezco sus comentarios
	
	** Angular Live Development Server is listening on localhost:4200, open your browser on <http://localhost:4200/> **  
	**Invalid configuration object. Webpack has been initialised using a configuration object that does not match the API schema.
	
	* configuration.context: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.  
	-> The base directory (absolute path!) for resolving the `entry` option. If `output.pathinfo` is set, the included pathinfo is shortened to this directory.
	* configuration.module.rules[12].include should be one of these:  
	RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? } | [RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]  
	-> One or multiple rule conditions  
	Details: 
	  * configuration.module.rules[5].exclude should be an instance of RegExp
	  * configuration.module.rules[5].exclude should be a string.
	  * configuration.module.rules[5].exclude should be an instance of function
	  * configuration.module.rules[5].exclude[0] should be an instance of RegExp
	  * configuration.module.rules[5].exclude[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[5].exclude[0] should be an instance of function
	  * configuration.module.rules[5].exclude[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[5].exclude[0] should be an object.
	  * configuration.module.rules[5].exclude should be an object.
	  * configuration.module.rules[5].exclude[0] should be an instance of RegExp
	  * configuration.module.rules[5].exclude[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[5].exclude[0] should be an instance of function
	  * configuration.module.rules[5].exclude[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[5].exclude[0] should be an object.
	  * configuration.module.rules[6].exclude should be an instance of RegExp
	  * configuration.module.rules[6].exclude should be a string.
	  * configuration.module.rules[6].exclude should be an instance of function
	  * configuration.module.rules[6].exclude[0] should be an instance of RegExp
	  * configuration.module.rules[6].exclude[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[6].exclude[0] should be an instance of function
	  * configuration.module.rules[6].exclude[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[6].exclude[0] should be an object.
	  * configuration.module.rules[6].exclude should be an object.
	  * configuration.module.rules[6].exclude[0] should be an instance of RegExp
	  * configuration.module.rules[6].exclude[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[6].exclude[0] should be an instance of function
	  * configuration.module.rules[6].exclude[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[6].exclude[0] should be an object.
	  * configuration.module.rules[7].exclude should be an instance of RegExp
	  * configuration.module.rules[7].exclude should be a string.
	  * configuration.module.rules[7].exclude should be an instance of function
	  * configuration.module.rules[7].exclude[0] should be an instance of RegExp
	  * configuration.module.rules[7].exclude[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[7].exclude[0] should be an instance of function
	  * configuration.module.rules[7].exclude[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[7].exclude[0] should be an object.
	  * configuration.module.rules[7].exclude should be an object.
	  * configuration.module.rules[7].exclude[0] should be an instance of RegExp
	  * configuration.module.rules[7].exclude[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[7].exclude[0] should be an instance of function
	  * configuration.module.rules[7].exclude[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[7].exclude[0] should be an object.
	  * configuration.module.rules[8].exclude should be an instance of RegExp
	  * configuration.module.rules[8].exclude should be a string.
	  * configuration.module.rules[8].exclude should be an instance of function
	  * configuration.module.rules[8].exclude[0] should be an instance of RegExp
	  * configuration.module.rules[8].exclude[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[8].exclude[0] should be an instance of function
	  * configuration.module.rules[8].exclude[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[8].exclude[0] should be an object.
	  * configuration.module.rules[8].exclude should be an object.
	  * configuration.module.rules[8].exclude[0] should be an instance of RegExp
	  * configuration.module.rules[8].exclude[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[8].exclude[0] should be an instance of function
	  * configuration.module.rules[8].exclude[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[8].exclude[0] should be an object.
	  * configuration.module.rules[9].include should be an instance of RegExp
	  * configuration.module.rules[9].include should be a string.
	  * configuration.module.rules[9].include should be an instance of function
	  * configuration.module.rules[9].include[0] should be an instance of RegExp
	  * configuration.module.rules[9].include[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[9].include[0] should be an instance of function
	  * configuration.module.rules[9].include[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[9].include[0] should be an object.
	  * configuration.module.rules[9].include should be an object.
	  * configuration.module.rules[9].include[0] should be an instance of RegExp
	  * configuration.module.rules[9].include[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[9].include[0] should be an instance of function
	  * configuration.module.rules[9].include[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[9].include[0] should be an object.
	  * configuration.module.rules[10].include should be an instance of RegExp
	  * configuration.module.rules[10].include should be a string.
	  * configuration.module.rules[10].include should be an instance of function
	  * configuration.module.rules[10].include[0] should be an instance of RegExp
	  * configuration.module.rules[10].include[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[10].include[0] should be an instance of function
	  * configuration.module.rules[10].include[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[10].include[0] should be an object.
	  * configuration.module.rules[10].include should be an object.
	  * configuration.module.rules[10].include[0] should be an instance of RegExp
	  * configuration.module.rules[10].include[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[10].include[0] should be an instance of function
	  * configuration.module.rules[10].include[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[10].include[0] should be an object.
	  * configuration.module.rules[11].include should be an instance of RegExp
	  * configuration.module.rules[11].include should be a string.
	  * configuration.module.rules[11].include should be an instance of function
	  * configuration.module.rules[11].include[0] should be an instance of RegExp
	  * configuration.module.rules[11].include[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[11].include[0] should be an instance of function
	  * configuration.module.rules[11].include[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[11].include[0] should be an object.
	  * configuration.module.rules[11].include should be an object.
	  * configuration.module.rules[11].include[0] should be an instance of RegExp
	  * configuration.module.rules[11].include[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[11].include[0] should be an instance of function
	  * configuration.module.rules[11].include[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[11].include[0] should be an object.
	  * configuration.module.rules[12].include should be an instance of RegExp
	  * configuration.module.rules[12].include should be a string.
	  * configuration.module.rules[12].include should be an instance of function
	  * configuration.module.rules[12].include[0] should be an instance of RegExp
	  * configuration.module.rules[12].include[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[12].include[0] should be an instance of function
	  * configuration.module.rules[12].include[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[12].include[0] should be an object.
	  * configuration.module.rules[12].include should be an object.
	  * configuration.module.rules[12].include[0] should be an instance of RegExp
	  * configuration.module.rules[12].include[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[12].include[0] should be an instance of function
	  * configuration.module.rules[12].include[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[12].include[0] should be an object.
	* configuration.output.path: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\dist\appdocitalia” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.  
	-> The output directory as **absolute path** (required).  
	WebpackOptionsValidationError: Invalid configuration object. Webpack has been initialised using a configuration object that does not match the API schema.
	* configuration.context: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.  
	-> The base directory (absolute path!) for resolving the `entry` option. If `output.pathinfo` is set, the included pathinfo is shortened to this directory.
	* configuration.module.rules[12].include should be one of these:  
	RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? } | [RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]  
	-> One or multiple rule conditions  
	Details: 
	  * configuration.module.rules[5].exclude should be an instance of RegExp
	  * configuration.module.rules[5].exclude should be a string.
	  * configuration.module.rules[5].exclude should be an instance of function
	  * configuration.module.rules[5].exclude[0] should be an instance of RegExp
	  * configuration.module.rules[5].exclude[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[5].exclude[0] should be an instance of function
	  * configuration.module.rules[5].exclude[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[5].exclude[0] should be an object.
	  * configuration.module.rules[5].exclude should be an object.
	  * configuration.module.rules[5].exclude[0] should be an instance of RegExp
	  * configuration.module.rules[5].exclude[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[5].exclude[0] should be an instance of function
	  * configuration.module.rules[5].exclude[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[5].exclude[0] should be an object.
	  * configuration.module.rules[6].exclude should be an instance of RegExp
	  * configuration.module.rules[6].exclude should be a string.
	  * configuration.module.rules[6].exclude should be an instance of function
	  * configuration.module.rules[6].exclude[0] should be an instance of RegExp
	  * configuration.module.rules[6].exclude[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[6].exclude[0] should be an instance of function
	  * configuration.module.rules[6].exclude[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[6].exclude[0] should be an object.
	  * configuration.module.rules[6].exclude should be an object.
	  * configuration.module.rules[6].exclude[0] should be an instance of RegExp
	  * configuration.module.rules[6].exclude[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[6].exclude[0] should be an instance of function
	  * configuration.module.rules[6].exclude[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[6].exclude[0] should be an object.
	  * configuration.module.rules[7].exclude should be an instance of RegExp
	  * configuration.module.rules[7].exclude should be a string.
	  * configuration.module.rules[7].exclude should be an instance of function
	  * configuration.module.rules[7].exclude[0] should be an instance of RegExp
	  * configuration.module.rules[7].exclude[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[7].exclude[0] should be an instance of function
	  * configuration.module.rules[7].exclude[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[7].exclude[0] should be an object.
	  * configuration.module.rules[7].exclude should be an object.
	  * configuration.module.rules[7].exclude[0] should be an instance of RegExp
	  * configuration.module.rules[7].exclude[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[7].exclude[0] should be an instance of function
	  * configuration.module.rules[7].exclude[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[7].exclude[0] should be an object.
	  * configuration.module.rules[8].exclude should be an instance of RegExp
	  * configuration.module.rules[8].exclude should be a string.
	  * configuration.module.rules[8].exclude should be an instance of function
	  * configuration.module.rules[8].exclude[0] should be an instance of RegExp
	  * configuration.module.rules[8].exclude[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[8].exclude[0] should be an instance of function
	  * configuration.module.rules[8].exclude[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[8].exclude[0] should be an object.
	  * configuration.module.rules[8].exclude should be an object.
	  * configuration.module.rules[8].exclude[0] should be an instance of RegExp
	  * configuration.module.rules[8].exclude[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[8].exclude[0] should be an instance of function
	  * configuration.module.rules[8].exclude[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[8].exclude[0] should be an object.
	  * configuration.module.rules[9].include should be an instance of RegExp
	  * configuration.module.rules[9].include should be a string.
	  * configuration.module.rules[9].include should be an instance of function
	  * configuration.module.rules[9].include[0] should be an instance of RegExp
	  * configuration.module.rules[9].include[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[9].include[0] should be an instance of function
	  * configuration.module.rules[9].include[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[9].include[0] should be an object.
	  * configuration.module.rules[9].include should be an object.
	  * configuration.module.rules[9].include[0] should be an instance of RegExp
	  * configuration.module.rules[9].include[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[9].include[0] should be an instance of function
	  * configuration.module.rules[9].include[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[9].include[0] should be an object.
	  * configuration.module.rules[10].include should be an instance of RegExp
	  * configuration.module.rules[10].include should be a string.
	  * configuration.module.rules[10].include should be an instance of function
	  * configuration.module.rules[10].include[0] should be an instance of RegExp
	  * configuration.module.rules[10].include[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[10].include[0] should be an instance of function
	  * configuration.module.rules[10].include[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[10].include[0] should be an object.
	  * configuration.module.rules[10].include should be an object.
	  * configuration.module.rules[10].include[0] should be an instance of RegExp
	  * configuration.module.rules[10].include[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[10].include[0] should be an instance of function
	  * configuration.module.rules[10].include[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[10].include[0] should be an object.
	  * configuration.module.rules[11].include should be an instance of RegExp
	  * configuration.module.rules[11].include should be a string.
	  * configuration.module.rules[11].include should be an instance of function
	  * configuration.module.rules[11].include[0] should be an instance of RegExp
	  * configuration.module.rules[11].include[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[11].include[0] should be an instance of function
	  * configuration.module.rules[11].include[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[11].include[0] should be an object.
	  * configuration.module.rules[11].include should be an object.
	  * configuration.module.rules[11].include[0] should be an instance of RegExp
	  * configuration.module.rules[11].include[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[11].include[0] should be an instance of function
	  * configuration.module.rules[11].include[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[11].include[0] should be an object.
	  * configuration.module.rules[12].include should be an instance of RegExp
	  * configuration.module.rules[12].include should be a string.
	  * configuration.module.rules[12].include should be an instance of function
	  * configuration.module.rules[12].include[0] should be an instance of RegExp
	  * configuration.module.rules[12].include[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[12].include[0] should be an instance of function
	  * configuration.module.rules[12].include[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[12].include[0] should be an object.
	  * configuration.module.rules[12].include should be an object.
	  * configuration.module.rules[12].include[0] should be an instance of RegExp
	  * configuration.module.rules[12].include[0]: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\src\styles.css” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
	  * configuration.module.rules[12].include[0] should be an instance of function
	  * configuration.module.rules[12].include[0] should be an array:  
	[RegExp | string | function | [(recursive)] | object { and?, exclude?, include?, not?, or?, test? }]
	  * configuration.module.rules[12].include[0] should be an object.
	* configuration.output.path: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\dist\appdocitalia” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.  
	-> The output directory as **absolute path** (required).  
	at webpack (C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\node_modules\webpack\lib\webpack.js:31:9)  
	at Observable.rxjs_1.Observable.obs [as _subscribe] (C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\node_modules@angular-devkit\build-webpack\src\webpack-dev-server\index.js:39:37)  
	at Observable._trySubscribe (C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\node_modules\rxjs\internal\Observable.js:44:25)  
	at Observable.subscribe (C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\node_modules\rxjs\internal\Observable.js:30:22)  
	at C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\node_modules\rxjs\internal\util\subscribeTo.js:22:31  
	at Object.subscribeToResult (C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\node_modules\rxjs\internal\util\subscribeToResult.js:10:45)  
	at MergeMapSubscriber._innerSub (C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\node_modules\rxjs\internal\operators\mergeMap.js:82:29)  
	at MergeMapSubscriber._tryNext (C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\node_modules\rxjs\internal\operators\mergeMap.js:76:14)  
	at MergeMapSubscriber._next (C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\node_modules\rxjs\internal\operators\mergeMap.js:59:18)  
	at MergeMapSubscriber.Subscriber.next (C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\node_modules\rxjs\internal\Subscriber.js:67:18)  
	at TapSubscriber._next (C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\node_modules\rxjs\internal\operators\tap.js:65:26)  
	at TapSubscriber.Subscriber.next (C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\node_modules\rxjs\internal\Subscriber.js:67:18)  
	at MergeMapSubscriber.notifyNext (C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\node_modules\rxjs\internal\operators\mergeMap.js:92:26)  
	at InnerSubscriber._next (C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\node_modules\rxjs\internal\InnerSubscriber.js:28:21)  
	at InnerSubscriber.Subscriber.next (C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\node_modules\rxjs\internal\Subscriber.js:67:18)  
	at MergeMapSubscriber.notifyNext (C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\node_modules\rxjs\internal\operators\mergeMap.js:92:26)**
	
	

	* **aragonesteban (Platzi)** [572277] (2)

		Hola, puedas decirme qué versión de angular tienes?  
		Puedes obtenerla ejecutando en la consola el siguiente comando `ng -v`.

	* **Hazel** [572277] (1)

		Hola muchas gracias:
		
		Angular CLI: 7.3.8  
		Node: 10.15.3  
		OS: win32 x64  
		Angular:  
		…
		
		## Package Version
		
		@angular-devkit/architect 0.13.8  
		@angular-devkit/core 7.3.8  
		@angular-devkit/schematics 7.3.8  
		@schematics/angular 7.3.8  
		@schematics/update 0.13.8  
		rxjs 6.3.3  
		typescript 3.2.4

	* **aragonesteban (Platzi)** [572277] (1)

		Vale, puedes probar actualizando el **_angular cli_** de la siguiente manera…  
		Vas a a una terminal y ejecutas lo siguiente en pasos:  
		`npm uninstall -g angular-cli`  
		`npm cache clean or npm cache verify (si npm > 5)`  
		`npm install -g @angular/cli@latest`
		
		Luego intentas nuevamente `ng serve` dentro del proyecto, si aún no te sirve, crea el proyecto nuevamente ya con la ultima versión de **_angular cli_** con `ng init myapp` y prueba nuevamente el `ng serve`, espero esto pueda solucionar el problema.

	* **Hazel** [572277] (1)

		Que tal muchas gracias, ya realice los pasos de hecho ng init me marca error, asi que realice con ng new my app… sin embargo sigue saliendo el mismo error 😐

	* **Dahaku** [572277] (1)

		Buenas.
		
		Creo que el problema lo encontramos en esta linea, que se repite bastante en todo el log:
		
		configuration.output.path: The provided value “C:\Users\Hazel!!!\Documents\proyectos\appdocitalia\dist\appdocitalia” contains exclamation mark (!) which is not allowed because it’s reserved for loader syntax.
		
		parece ser que tu usuario de windows se llama “Hazel!!!” en la creación del proyecto, trabaja con unas carpetas dentro de la carpeta de tu usuario por lo que da error ya que es un Char reservado.
		
		No se si cambiando el nombre de tu usuario de windows puedes solucionar el problema. Como solución rápida, crea otro usuario windows en tu máquina y trabaja desde allí

* **Brayan Mamani** (1) [555148](https://platzi.com/comentario/555148/) 

	Crear e iniciar el proyecto:
	``` 
	    ng new platzinger
	    ng serve --open
	    
	```

* **Alex Eugenio Gavidia Donayre** (1) [535718](https://platzi.com/comentario/535718/) 
Easy

* **Alex Eugenio Gavidia Donayre** (1) [535717](https://platzi.com/comentario/535717/) 
ng server - -open

* **Alex Eugenio Gavidia Donayre** (1) [535713](https://platzi.com/comentario/535713/) 
ng new SAPCloud

* **Alex Eugenio Gavidia Donayre** (1) [535711](https://platzi.com/comentario/535711/) 
ng new platzinger

* **Adrian Camilo Caminos** (1) [480732](https://platzi.com/comentario/480732/) 

	Hola si quieren hay varias maneras de correr nuestra app por CLI les dejo unos para que prueben
	
	  1. `ng serve --open` abre en el browser la app con nuestro localhost
	  2. `ng serve --port 4300` esto hace que si ya tenemos el puerto 4200 usado podemos asignar otro puerto para trabajar con nuestra app
	  3. `ng serve --host=192.168.0.0` esto es para abrir mediante el puerto de nuestra ip lo pueden ver solo los que esten conectados en esta red
	
	

	* **Adrian Camilo Caminos** [480732] (1)

		para saber la ip por windows es con `ipconfig` y con mac, linux `ifconfig`

* **Anderson Steve Santamaría Ballesteros** (1) [441100](https://platzi.com/comentario/441100/) 

	a mi me aparece este error:
	
	Could not find module “@angular-devkit/build-angular” from “D:\Estudio\Cursos\Platzi\Angular6\platzinger”.  
	Error: Could not find module “@angular-devkit/build-angular” from “D:\Estudio\Cursos\Platzi\Angular6\platzinger”.  
	at Object.resolve (C:\Users\anderson.santamaria\AppData\Roaming\npm\node_modules@angular\cli\node_modules@angular-devkit\core\node\resolve.js:141:11)
	
	at Observable.rxjs_1.Observable [as _subscribe] (C:\Users\anderson.santamaria\AppData\Roaming\npm\node_modules@angular\cli\node_modules@angular-devkit\architect  
	src\architect.js:132:40)  
	at Observable._trySubscribe (C:\Users\anderson.santamaria\AppData\Roaming\npm\node_modules@angular\cli\node_modules\rxjs\internal\Observable.js:44:25)  
	at Observable.subscribe (C:\Users\anderson.santamaria\AppData\Roaming\npm\node_modules@angular\cli\node_modules\rxjs\internal\Observable.js:30:22)  
	at C:\Users\anderson.santamaria\AppData\Roaming\npm\node_modules@angular\cli\node_modules\rxjs\internal\Observable.js:99:19  
	at new Promise (<anonymous>)  
	at Observable.toPromise (C:\Users\anderson.santamaria\AppData\Roaming\npm\node_modules@angular\cli\node_modules\rxjs\internal\Observable.js:97:16)  
	at ServeCommand.initialize (C:\Users\anderson.santamaria\AppData\Roaming\npm\node_modules@angular\cli\models\architect-command.js:91:94)  
	at process._tickCallback (internal/process/next_tick.js:68:7)  
	at Function.Module.runMain (internal/modules/cjs/loader.js:744:11)
	
	creo que es el mismo que comentaron abajo, sin embargo, ya hice los pasos, pero no me funciona, tambien borré el proyecto, la carpeta node_modules, pero no me funciona nada.
	
	Estoy bloqueado, no se que hacer.

	* **Anderson Steve Santamaría Ballesteros** [441100] (2)

		En angular 7 se soluciona con el siguiente comando:
		
		npm i @angular-devkit/build-angular --only=dev
		
		ya me funcionó.

* **ivan_acg** (1) [432915](https://platzi.com/comentario/432915/) 

	Muy buena la explicación , excepto por la parte en que abre internet explorer >:v

* **Matias Cabido** (1) [420338](https://platzi.com/comentario/420338/) 

	Which stylesheet format would you like to use?  
	En ese caso es CSS verdad??

	* **moises mannarino** [420338] (2)

		ahi pregunta q mmanera de darle estilos a lso componentes vas a usar, podes elegir entre codificar en scss, sass, y css, elegi la manera de codificar lso estilos q vas a usar vos

	* **Matias Cabido** [420338] (1)

		Si pero yo quiero seguir los que hacen en el curso, porque sino después empiezo a tener errores y nose por que se dan.  
		Para ello sigo al pie lo que hace el profe aunque sea la primera vez que practico o sigo el curso.
		
		Muchas Gracias MoisesMannario

* **alejandrarock** (1) [403787](https://platzi.com/comentario/403787/) 

	[](https://drive.google.com/open?id=1FomAWCCj86L6Blqgi8JzNNDvkIrTSgaL)

* **Carlos Uriel de Jesus Sánchez González** (1) [397022](https://platzi.com/comentario/397022/) 

	```
	    ng new platzinger
	    cd platzinger
	    ng serve --open
	    
	```

* **Johan Fernando Garnica Rodriguez** (1) [393351](https://platzi.com/comentario/393351/) 

	buenas noches alguien me puede ayudar con el siguiente error no puedo ![Captura de pantalla \(2\).png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%282%29-14c3d5d9-613f-4c65-ab70-217d306098ca.jpg)

	* **Abelardo Asensio Callol** [393351] (1)

		Trata de ejecutar la instalación con la palabra sudo delante, me parece que lo que tienes es error de permisos…

	* **Alfonso Adame Rueda** [393351] (1)

		hola buenas noches  
		en lo que veo lo hiciste en el símbolo del sistema ,para lo cual debes ejecutar el cmd o símbolo del sistema como administrador.

	* **kikekeys** [393351] (1)

		En windows ejecuta como administrador una consola, eso lo haces dandole click derecho a la consola y `ejecutar como admistrador`

* **Alexander  Silvera** (1) [391242](https://platzi.com/comentario/391242/) 

	hola me salta todo este error cuando quiero hacer el serve:
	
	Could not find module “@angular-devkit/build-angular” from “C:\ProyectAngular\poyect-mensage”.  
	Error: Could not find module “@angular-devkit/build-angular” from “C:\ProyectAngular\poyect-mensage”.  
	at Object.resolve (C:\Users\Acer\AppData\Roaming\npm\node_modules@angular\cli\node_modules@angular-devkit\core\node\resolve.js:141:11)  
	at Observable.rxjs_1.Observable [as _subscribe] (C:\Users\Acer\AppData\Roaming\npm\node_modules@angular\cli\node_modules@angular-devkit\architect\src\architect.js:132:40)  
	at Observable._trySubscribe (C:\Users\Acer\AppData\Roaming\npm\node_modules@angular\cli\node_modules\rxjs\internal\Observable.js:43:25)  
	at Observable.subscribe (C:\Users\Acer\AppData\Roaming\npm\node_modules@angular\cli\node_modules\rxjs\internal\Observable.js:29:22)  
	at DoOperator.call (C:\Users\Acer\AppData\Roaming\npm\node_modules@angular\cli\node_modules\rxjs\internal\operators\tap.js:29:23)  
	at Observable.subscribe (C:\Users\Acer\AppData\Roaming\npm\node_modules@angular\cli\node_modules\rxjs\internal\Observable.js:24:22)  
	at C:\Users\Acer\AppData\Roaming\npm\node_modules@angular\cli\node_modules\rxjs\internal\util\subscribeTo.js:22:31  
	at Object.subscribeToResult (C:\Users\Acer\AppData\Roaming\npm\node_modules@angular\cli\node_modules\rxjs\internal\util\subscribeToResult.js:7:45)  
	at MergeMapSubscriber._innerSub (C:\Users\Acer\AppData\Roaming\npm\node_modules@angular\cli\node_modules\rxjs\internal\operators\mergeMap.js:75:38)  
	at MergeMapSubscriber._tryNext (C:\Users\Acer\AppData\Roaming\npm\node_modules@angular\cli\node_modules\rxjs\internal\operators\mergeMap.js:72:14)

	* **dddenis** [391242] (2)

		Hola, este error es debido a que no se te han bajado todas las dependencias del projecto.  
		Para ello ejecuta:
		``` 
		    npm install
		    
		```
		
		PD: en caso de que no te funcione el comando anterior, borra la carpeta node_modules y vuélvelo a ejecutar.
		
		Aunque si solo quieres instalar únicamente esa dependencia usa:
		``` 
		    npm install--save-dev @angular-devkit/build-angular
		    O
		    yarn add @angular-devkit/build-angular --dev
		    
		```

	* **Anderson Steve Santamaría Ballesteros** [391242] (1)

		a mi me aparece este error:
		
		Could not find module “@angular-devkit/build-angular” from “D:\Estudio\Cursos\Platzi\Angular6\platzinger”.  
		Error: Could not find module “@angular-devkit/build-angular” from “D:\Estudio\Cursos\Platzi\Angular6\platzinger”.  
		at Object.resolve (C:\Users\anderson.santamaria\AppData\Roaming\npm\node_modules@angular\cli\node_modules@angular-devkit\core\node\resolve.js:141:11)
		``` 
		    at Observable.rxjs_1.Observable [as _subscribe] (C:\Users\anderson.santamaria\AppData\Roaming\npm\node_modules\@angular\cli\node_modules\@angular-devkit\architect\
		    
		```
		
		src\architect.js:132:40)  
		at Observable._trySubscribe (C:\Users\anderson.santamaria\AppData\Roaming\npm\node_modules@angular\cli\node_modules\rxjs\internal\Observable.js:44:25)  
		at Observable.subscribe (C:\Users\anderson.santamaria\AppData\Roaming\npm\node_modules@angular\cli\node_modules\rxjs\internal\Observable.js:30:22)  
		at C:\Users\anderson.santamaria\AppData\Roaming\npm\node_modules@angular\cli\node_modules\rxjs\internal\Observable.js:99:19  
		at new Promise (<anonymous>)  
		at Observable.toPromise (C:\Users\anderson.santamaria\AppData\Roaming\npm\node_modules@angular\cli\node_modules\rxjs\internal\Observable.js:97:16)  
		at ServeCommand.initialize (C:\Users\anderson.santamaria\AppData\Roaming\npm\node_modules@angular\cli\models\architect-command.js:91:94)  
		at process._tickCallback (internal/process/next_tick.js:68:7)  
		at Function.Module.runMain (internal/modules/cjs/loader.js:744:11)
		
		creo que es el mismo, ya hice los pasos, pero no me funciona, tambien borré el proyecto, la carpeta node_modules, pero no me funciona nada.
		
		Estoy bloqueado, no se que hacer.

* **Jeisson Francois Rosas Céspedes** (1) [72598](https://platzi.com/comentario/819081/) 
Buenas tardes, Ya instalé angular cli pero cuando ejecuto ng en mi consola me sale el error ng: command not found. Estoy trabajando en ...

	* **Gabriel De Andrade (Platzi)** [72598] (2)

		Hola! En ocasiones la terminal no detecta bien los cambios en los comandos así que puedes intentar cerrar y abrir de nuevo la terminal, y si eso no funciona intenta instalarlo nuevamente

* **sergio-hurtado** (1) [62662](https://platzi.com/comentario/644051/) 
cuando copio http://localhost:4200 en google chrome no sale el logo de angular pero en opera y mozill...

	* **Diego Alexander Forero Higuera (Platzi)** [62662] (2)

		Revisa la consola de google chrome para ver si lanza algún error y lo compartes para poder ayudarte.

* **Edgar Moisés Chávez Macario** (1) [61031](https://platzi.com/comentario/614917/) 
ayuda yo tengo este error

	* **Diego Alexander Forero Higuera (Platzi)** [61031] (2)

		Es un problema de conexión a internet, probablemente estas detrás de un proxy o si estas en la red de tu oficina probablemente están bloqueando el acceso a esa url.

* **Neider Rafael Tapia Avila** (1) [45609](https://platzi.com/comentario/421880/) 
Saludos, por alguna razon mi terminal se congela, la pregunta es si con ng serve subo el servidor con que comando lo “mato”

	* **Alexander Sandoval** [45609] (1)

		En Windows cancelas la ejecución del servidor con `CTRL + c`

* **Matias Cabido** (1) [45484](https://platzi.com/comentario/420338/) 
Which stylesheet format would you like to use? En ese caso es CSS verdad??

	* **moises mannarino** [45484] (2)

		ahi pregunta q mmanera de darle estilos a lso componentes vas a usar, podes elegir entre codificar en scss, sass, y css, elegi la manera de codificar lso estilos q vas a usar vos

* **Johan Fernando Garnica Rodriguez** (1) [43082](https://platzi.com/comentario/393351/) 
buenas noches alguien me puede ayudar con el siguiente error no puedo

	* **Abelardo Asensio Callol** [43082] (1)

		Trata de ejecutar la instalación con la palabra sudo delante, me parece que lo que tienes es error de permisos…

* **Alexander  Silvera** (1) [42877](https://platzi.com/comentario/391242/) 
hola me salta todo este error cuando quiero hacer el serve: Could not find module “@angular-devkit/build-angular” from “C:\ProyectAngular...

	* **dddenis** [42877] (2)

		Hola, este error es debido a que no se te han bajado todas las dependencias del projecto.  
		Para ello ejecuta:
		``` 
		    npm install
		    
		```
		
		PD: en caso de que no te funcione el comando anterior, borra la carpeta node_modules y vuélvelo a ejecutar.
		
		Aunque si solo quieres instalar únicamente esa dependencia usa:
		``` 
		    npm install--save-dev @angular-devkit/build-angular
		    O
		    yarn add @angular-devkit/build-angular --dev
		    
		```

* **Hazel** (0) [58042](https://platzi.com/comentario/572277/) 
Hola , tengo este error al momento de ejecutar ng serve, ya busqeue mi soluciones y nada, solamente estoy instalando ANGULAR CLI y despue...

	* **aragonesteban (Platzi)** [58042] (2)

		Hola, puedas decirme qué versión de angular tienes?  
		Puedes obtenerla ejecutando en la consola el siguiente comando `ng -v`.

## 0080. Reto Desarrolla un tutorial escrito comparando Angular con otro Framework (Vue, React) [12751](https://platzi.com/clases/1340-angular-avanzado/12751-reto-desarrolla-un-tutorial-escrito-comparando-ang/)

### Descripción:


### Comentarios:

* **JDiaz0017** (21) [368118](https://platzi.com/comentario/368118/) 

	¡Reto cumplido! Los invito a mi Tutorial, midiendo a Angular con React, a que no adivinan quien ganó esta batalla 😃  
	Espero que les guste, me inspiré de varias fuentes así que intenté ser lo más imparcial posible. Si creen que pueden complementar, corregir o brindar alguna sugerencia, ¡venga! bienvenido sea.  
	No olviden dar su manito arriba y así contribuir emocionalmente a esta causa para seguir escribiendo Tutoriales. Un saludo y les dejo el Link:  
	[quiero leer el Tutorial](https://platzi.com/angular-avanzado/tutoriales/angular-y-react-js-dos-pesos-pesados-del-frontend/)

	* **mario-salinas** [368118] (1)

		Increíble tutorial! Super preciso, todos los estudiantes del curso deberían darle un repaso

	* **Spyderp** [368118] (1)

		Creo es un articulo muy completo con respecto al tema React. Solo incluiría que angular no usa MVC Sino que usa arquitectura MVVM - Model View Viewmodel.
		
		El MVC es más de framework de Backend.

	* **Brayan Mamani** [368118] (1)

		Muy buen aporte sobre Angular y React.

	* **Juan Camilo Rico Orjuela** [368118] (1)

		Muy buen aporte!

* **caprilespe** (16) [781821](https://platzi.com/comentario/781821/) 

	* ## **¿Qué tienen Angular, React y Vue en común?**
	
	* Todos están orientados al desarrollo del frontend.
	
	* Todos están orientados al desarrollo de aplicaciones de tipo SPA (Single Page Application).
	
	* Una vez se aprenda uno ya cualquiera de los otros dos se hará fácil.
	
	* Pueden ser utilizadas para el desarrollo de aplicaciones mobiles.
	
	* ## **Curva de Aprendizaje**
	
	* **Angular** : Curva de aprendizaje más alta.
	
	* **React** : Es mucho más fácil de aprender que Angular.
	
	* **Vue** : Es aun más fácil debido a que sus librerías son muy parecidas.
	
	* ## **Proyectos de gran escala**
	
	* **Angular** : Tiene mucha más ventaja por la cantidad de componentes que tiene que pueden manejar y fue concebido para el desarrollo de aplicaciones de alta escala.  
	- **React** : react al igual que angular es usado para el desarrollo de aplicaciones grandes.  
	- **Vue** : No es tan robusto, sin embargo es recomendable usarlo para aplicaciones en despliegue legacy que ya tengan mucho desarrollo y requieren actualizarse a aplicaciones tipo SPA o hacer algún tipo de integración.
	
	* ## **Herramientas de desarrollo**
	
	* **Angular** : Typescript le da mucha ventaja por el uso de reglas de alto tipado, de igual forma vue y react pueden integrarse a TypeScript sin embargo no es obligatorio, esto de alguna forma obliga al desarrollador a tener un código mejor estructurado y limpio.
	
	* **React** : Tiene herramientas para el debug de codigo que son extensiones del navegador (Chrome y Firefox) React Developer Tools.
	
	* ## **Mantenimiento de código**
	
	* **Angular** : Es mucho más complejo en detección de bugs causados por sus mismos componentes.  
	- **React y Vue** : Son mucho más facil y flexible en la detección de errores.
	
	* ## **Flexibilidad**
	
	* **Angular** : por la cantidad de componentes que posee angular a veces se descargan una cantidad amplia de elementos que no necesariamente serán usados, esto lo hace poco flexible si se desea desarrollar aplicaciones pequeñas.
	
	* **React y Vue** : tienen pocas librerias y se adaptan a aplicaciones pequeñas y grandes.
	
	* ## **Desarrollo mobile**
	
	* **Angular** : Tiene framework de desarrollo híbrido como Ionic, que igualmente pueden integrarse a React y Vue en su ultima versión. La ventaja que tiene este framework basado en angular es que no genera aplicaciones nativas.
	
	* **React** : React usa react native y es un desarrollo no 100% nativo pero se acerca a dicho desarrollo y lo hace mucho más optimo.  
	- **Vue** : Usa NativeScript -. Vue permite la creación de aplicaciones nativas con NativeScript y Vue.
	
	
	

	* **DiegoFGuty** [781821] (1)

		Valioso aporte, gracias bro

	* **Juan Antonio Campoy Lira** [781821] (1)

		Excelente aporte bro Gracias

* **Wilson Fabian Pérez Sucuzhañay** (8) [366209](https://platzi.com/comentario/366209/) 

	Listo algo corto espero me digan que mas adjuntar.
	
	<https://platzi.com/angular-avanzado/tutoriales/comparacion-de-angular-vs-react-vs-vue/>

* **eddyarellanes** (4) [363719](https://platzi.com/comentario/363719/) 

	Lo compararé con el señor Vue ❤️

	* **JDiaz0017** [363719] (2)

		No es por presionar, pero hasta la fecha no veo el Tutorial amigo, ¡Vamos! con toda que estoy que leo al señor Vue, otro gran competidor 😃

* **edwintrumpet** (2) [713399](https://platzi.com/comentario/713399/) 

	Vengo de React es mi fuerte, aunque ya había trabajado un poco antes con Angular.  
	Angular fue el framework con el que me inicié en esto de las SPAs.  
	Angular me parece que proporciona las herramientas para un desarrollo rápido de una SPA, todo está preparado y listo para usar, en React en cambio el lienzo está más limpio, se pueden elegir muchas cosas como la estructura de archivos, las herramientas y dependencias a usar lo que lo hace un poco más flexible y configurable a mi parecer pero hace el desarrollo un poco más lento por esas mismas causas.
	
	También con respecto a la línea de aprendizaje veo una diferencia, ya que React es muy fácil de entender para alguien que conoce bien Javascript, en cambio Angular requiere una aproximación a Typescript además de el conocimiento de varios aspectos del framework que son más complejos que el uso de React.  
	Con respecto a la organización de los archivos y el código me gustó mucho Angular cuando lo conocí porque es semejante a lo que venía manejando en la estructura de archivos que era separar maquetación, funcionalidad y estilo. En React se tiende a trabajar todo junto lo que al comienzo para mí fue un dolor de cabeza pero que después adopté y vi sus beneficios.

* **Mauricio Peña** (1) [1087075](https://platzi.com/comentario/1087075/) 
	
	![comparaciones.png](https://static.platzi.com/media/user_upload/comparaciones-884a9628-a4fe-41a8-b6cc-59035c118fdb.jpg)

* **Cristopher Hernández** (1) [766231](https://platzi.com/comentario/766231/) 

	Realmente, sólo había usado angular en su versión como Angular JS, no podría compararlos pues tampoco conozco a fondo todo lo que esta framework representa, sin embargo, es un paso gigantesco el que se hace notar desde el punto en que no se trata sólo de agregar un archivo .js a nuestro proyecto.

* **Spyderp** (1) [440976](https://platzi.com/comentario/440976/) 

	Listo me disculpo por no salir la imagen. La verdad estoy novato usando la herramienta de insertar imagenes.  
	<https://platzi.com/tutoriales/1340-angular-avanzado/3250-angular-vs-vuejs-comparativa-3/>

* **jeisonsrz** (1) [414970](https://platzi.com/comentario/414970/) 

	Comparto este link donde describen algunas ventajas y desventajas de estos framework [](https://blog.webtraining.zone/angular-vs-vue-js-que-framework-me-conviene-aprender/)

	* **jeisonsrz** [414970] (1)

		[](https://blog.webtraining.zone/angular-vs-vue-js-que-framework-me-conviene-aprender/)

	* **jeisonsrz** [414970] (1)

		<https://blog.webtraining.zone/angular-vs-vue-js-que-framework-me-conviene-aprender/>

* **Carlos Uriel de Jesus Sánchez González** (1) [397024](https://platzi.com/comentario/397024/) 

	Buen reto

* **JDiaz0017** (1) [363163](https://platzi.com/comentario/363163/) 

	¡Excelente reto! Me gustaría compararlo con don React JS 😃

# Definición de la estructura del App [2346]

## 0090. ¿Qué hará nuestra app ¿Cuál es su arquitectura ¿De qué pantallas se compondrá ¿Cuál será su look [12752](https://platzi.com/clases/1340-angular-avanzado/12752-que-hara-nuestra-app-cual-es-su-arquitectura-de-qu/)

### Descripción:


Características que tendrá nuestra app:

En el frontend (Angular):

* Pantalla Login
* Pantalla Home / Dashboard 
  * Lista de Amigos del usuario
* Buscador de amigos 
  * Botón de agregar amigos
* Pantalla de conversación 
  * Mandar mensajes, fotos, zumbidos
  * Mostrar los usuarios que chatean
* Pantalla de Perfil



En el backend (Firebase):

* Servidor centralizado
* Acceso a datos
* Envío de mensajes de manera bidireccional
* Comunicación en tiempo real
* Uso de sockets



Para profundizar en los conocimientos de Firebase puedes acceder al [Curso de Firebase para Web](https://platzi.com/cursos/firebase-web/) disponible en Platzi.

### Comentarios:

* **Miguel Matos** (5) [369136](https://platzi.com/comentario/369136/) 

	Para saber más sobre cómo funciona y cómo usar firebase, pueden ir a este enlace <https://platzi.com/cursos/firebase-web/>, disponible en Platzi.

	* **Dany Ladino** [369136] (2)

		Hola, sabes si hay mucho cambio de angular 6 a angular 7

	* **Miguel Matos** [369136] (4)

		Me dicen que los cambios son basante sutiles, apenas una ligera modificación. [En este enlace](https://blog.angular.io/version-7-of-angular-cli-prompts-virtual-scroll-drag-and-drop-and-more-c594e22e7b8c) mencionan las nuevas características que se traerán.

	* **Dany Ladino** [369136] (2)

		Gracias por el dato

	* **srojas_dev** [369136] (1)

		excelente

	* **Madrov** [369136] (0)

		El articulo esta desactualizado. React ya es MIT

* **Andrés Gutiérrez Arcia** (3) [738609](https://platzi.com/comentario/738609/) 

	Este proyecto me gusta mucho

* **kevinenriquearciniegaschacon** (3) [642220](https://platzi.com/comentario/642220/) 

	Super me encanto y esto es un gangazo 2 en 1  
	![](https://cdn.memegenerator.es/imagenes/memes/full/26/62/26626819.jpg)

* **Dany Ladino** (3) [406550](https://platzi.com/comentario/406550/) 

	Esta excelente, esperemos que la nueva version de angular no haya cambiado mucho

	* **Gustavo Ramírez Apache** [406550] (2)

		no lo hizo

* **marioamaciasortiz** (2) [826812](https://platzi.com/comentario/826812/) 

	como mudas una app de angular 7 a otro server sin saber que modulos se instalaron / esa es una duda al aire. prosigamos

	* **JerezA** [826812] (1)

		siempre puedes saber que trae una aplicacion mirando su package.json, el unico inconveniente que vendria yo a percibir seria la version de node utilizada, esa si no hay manera de interpretarla, y toca instalar una que sea lo mas compatible con tu version de ng, por este tipo de cosas comence a amar herramientas como docker, que haces una configuracion de entorno que puedes replicar en cualquier lugar y nunca mas tendras que preocuparte por migraciones tediosas.

	* **jorgearmandoutj** [826812] (1)

		Tengo entendido que al utilizar el comando:
		``` 
		    ng install o nmp install
		    
		```
		
		no recuerdo cual de esos dos es, te instala todas las dependencias y  
		que contiene el package.json

* **Brandon Iván Quiroa Loarca** (2) [608966](https://platzi.com/comentario/608966/) 

	La nostalgia que trae este proyecto 😄

* **Brayan Mamani** (2) [558657](https://platzi.com/comentario/558657/) 

	Que bien que se use Firebase en este proyecto de Angular.

* **edu1590** (2) [405541](https://platzi.com/comentario/405541/) 

	Genial idea para aprender!

* **Carlos Uriel de Jesus Sánchez González** (2) [397138](https://platzi.com/comentario/397138/) 

	Buena forma para empezar un proyecto para aprender

* **YojanPardo** (1) [1003553](https://platzi.com/comentario/1003553/) 

	me gustan mucho este tipo de cursos que van más allá que simplemente mostrar lo específico de una tecnología!

	* **Joiss Ventura Rivera** [1003553] (1)

		Sii, es lo de bueno y emocionante. Pero por otro lado es un poco de publicidad para sus demás cursos jeje

* **alexanderfredycu** (1) [978207](https://platzi.com/comentario/978207/) 

	Vine buscando cobre y encontré oro !

* **Diego Sepulveda** (1) [916096](https://platzi.com/comentario/916096/) 

	Hola muy interesante el proyecto, me gusto. Profesor una pregunta, como se llama el programa que usa para dibujar y ese hardware?

	* **Joiss Ventura Rivera** [916096] (1)

		Él está usando Adobe Photoshop CC 2018.
		
		Pero si quieres hacer diseños en verdad deberías de usar Adobe XD.
		
		Te permite tener diferentes plantillas en el mismo archivo ( diferentes modelos, por así decirlo ) los cuales puedes trabajar sin necesidad de estar cambiando de pestaña a cada rato.

* **tiu80** (1) [694389](https://platzi.com/comentario/694389/) 

	el unico que he usado es Vue y me parecio super interesante por la facilidad y la rapida escalabilidad

* **pedromosquerat** (1) [644618](https://platzi.com/comentario/644618/) 

	Me parece una idea genial, y muy atractiva, la de crear un chat durante un curso de un Framework de Frontends. 👏👏👏

* **maoacrlearn** (1) [626385](https://platzi.com/comentario/626385/) 

	2 cursos en 1 , Angular y Firebase ! Ok

* **herbertpro** (1) [554283](https://platzi.com/comentario/554283/) 

	Excelente idea! estoy muy emocionado con comenzar

## 0100. Explorando el sistema de archivos [12753](https://platzi.com/clases/1340-angular-avanzado/12753-explorando-el-sistema-de-archivos/)

### Descripción:


A primera vista la estructura de los archivos del proyecto pudiera ser un tanto abrumadora ya que Angular necesita una gran cantidad de elementos y dependencias para proveernos del entorno adecuado para el desarrollo, pero al generar el entorno de producción, la mayoría de estas dependencias no estarán incluidas, por lo que la estructura final será mucho más sencilla.

Como parte de la estructura del proyecto econtramos el archivo `/package.json`/ y el directorio `/npm_modules`. Este directorio contiene un numero importante de sub-carpetas con los paquetes de todas las dependencias usadas por node para generar nuestra app y sus versiones específicas. Es muy recomendable instalar los paquetes del proyecto con la bandera `npm install <nombre del paquete> --save-exact` para evitar incompatibilidades con futuras versiones de los mismos paquetes.

La carpeta `/src` contienen los archivos con el código que vamos a editar. Los más importantes son: los css, el index.html que es donde corre toda la aplicación ya que, como vimos, Angular genera una SPA (aplicación de una sóla página).  
También encontramos la carpeta `/app` donde están los archivos principales, que editaremos para crear nuestra aplicación, como es el caso de: `app.component.css`, `app.component.html`, `app.component.spec.ts`, `app.component.ts` y `app.modules.ts`.  
Tenemos también la carpeta `/assets`, que con tiene todos los recursos estáticos usados por la aplicación.

### Comentarios:

* **Carlos Uriel de Jesus Sánchez González** (4) [397154](https://platzi.com/comentario/397154/) 

	npm install <nombre del paquete> \--save -exact

* **alanfermin** (3) [889264](https://platzi.com/comentario/889264/) 

	Deseo hacer un CRM con Angular. Partiendo desde una plantilla. ¿Alguien quiere apuntarse a desarrollar este CRM partiendo de la información aprendida en este curso?

* **jesusgt712** (3) [556941](https://platzi.com/comentario/556941/) 

	Si el ^ es que va verificar la version mas nueva esto que es --> ~?

	* **David Flores** [556941] (1)

		Es equivalente

* **Cristian David Franco Garcia** (3) [430360](https://platzi.com/comentario/430360/) 

	Buenas noches,
	
	Es posible explicar el resto de archivos que componen un proyecto angular angular.json, e2e, karma, polyfills

	* **William Vega** [430360] (1)

		bump +1

* **TlalocES** (1) [492368](https://platzi.com/comentario/492368/) 

	A la hora de hacer una aplicación estilo galería, las fotografías de los usuarios donde las subirían, a la carpeta de assets?, no seria un poco ineficiente en caso de que haya bastantes usuarios y tener 1.000.000 de fotos repartidas entres 10.000 carpetas?

	* **Hector Luis Piñero** [492368] (7)

		No, esos archivos deberían estar en el backend y manejarlos desde un servidor.
		
		En la carpeta assets deberías colocar todos los archivos estáticos como fuentes, logos, fondos, iconos.

	* **Ehitel Rodríguez Castro** [492368] (2)

		Ahí sólo se suben archivos referentes al desarrollo y en tiempo de desarrollo que serán distribuidos con la app hacia producción.
		
		Todos los demás elementos que puedan subirse a un servidor utilizando la app, se guardarán a nivel de base de datos o de otros servicios de almacenaje de datos.
		
		Un abrazo

	* **Francisco Genaro Cerna Fukuzaki** [492368] (1)

		Lo más eficiente sería almacenar las imágenes en un servidor a parte como AWS S3, no en base de datos porque afectaría el performance. Y desde la aplicación hacer referencia a la URL generada por el servidor donde se encuentran las imágenes.

	* **YojanPardo** [492368] (1)

		en los assets solo pones archivos estáticos como iconos, fuentes, etc… aunque sería preferible usar un CDN para ello, por otro lado las imágenes cargadas por los usuarios deben ser manejadas por un backend que las almacene y guarde la ruta en una base de datos.

* **Stiven Piñeros** (1) [458185](https://platzi.com/comentario/458185/) 

	Como puedo mover mi proyecto a Scss, ya que lo creee con css.
	
	Gracias

	* **Nicolas Paolo Bueno Cavero** [458185] (1)

		Yo en su momento seguí la siguiente web para pasar el proyecto Scss, está muy bien (aunque está en inglés), espero que te sirva.
		
		<https://scotch.io/tutorials/using-sass-with-the-angular-cli>

	* **Brayan Mamani** [458185] (1)

		Muy útil.

* **jesusgt712** (1) [56785](https://platzi.com/comentario/556941/) 
Si el ^ es que va verificar la version mas nueva esto que es --> ~?

	* **David Flores** [56785] (1)

		Es equivalente

* **TlalocES** (1) [51497](https://platzi.com/comentario/492368/) 
A la hora de hacer una aplicación estilo galería, las fotografías de los usuarios donde las subirían, a la carpeta de assets?, no seria u...

	* **Hector Luis Piñero** [51497] (7)

		No, esos archivos deberían estar en el backend y manejarlos desde un servidor.
		
		En la carpeta assets deberías colocar todos los archivos estáticos como fuentes, logos, fondos, iconos.

## 0110. ¿Qué son y cómo generar los primeros componentes de nuestra app [12754](https://platzi.com/clases/1340-angular-avanzado/12754-que-son-y-generar-los-primeros-componentes-de-nues/)

### Descripción:


Un componente en Angular está compuesto mínimamente por un archivo html y un archivo de Typescript, siendo el .html la vista y el .ts la lógica que ésta tiene asociada. Un componente podemos verlo como cada una de las vistas de nuestra app.

Generalmente, para cada componente se usa sólo un archivo css con los estilos del componente, aunque la propiedad styleUrls permite varios css.

Para generar un componente usando el Angular CLI, ejecutamos el comando siguiente:
``` 
    ng generate component 
    
```

Una vez ejecutado el comando, veremos que se ha creado una nueva carpeta en `/app`, con el nombre del componente `/mi-componente` y los siguientes archivos:
``` 
    /app
      /mi-componente
        mi-componente.css
        mi-componente.html
        mi-componente.spec.ts
        mi-componente.ts
    
```

Otra de las cosas que hace Angular CLI por nosotros es importar los componentes que vayamos generando y los agrega a la propiedad declarations en `app.modules.ts`

Para indicar a Angular cuál será el componente inicial de la aplicación, debemos indicar el nombre de dicho componente en la propiedad `selector` del archivo `app.component.ts`

El selector, es la directiva usada en el `index.html` para insertar todo el contenido de nuestro componente.

### Comentarios:

* **Diego Burlando** (5) [365176](https://platzi.com/comentario/365176/) 

	Repasando bastantes conceptos del primer curso, me gusta que ahora entiendo muchas mas cosas.

	* **Duilio Luque** [365176] (1)
En qué circunstancias se puede o debe usar más de un component dentro del bootstrap de app.module.ts?

	* **Juan Carlos Felizzola Vega** [365176] (5)

		Puedes usarlo cuando quieras presentar por ejemplo un main que va a usar el router y un footer fijo, llamando estas en el index.html.
		
		Puedes probar podiendo:
		``` 
		    bootstrap: [AppComponent, LoginComponent]
		    
		```
		
		Y en el index llamarlas:
		``` 
		    <body>
		      <app-root></app-root>
		      <app-login></app-login>
		    </body>
		    
		```
		
		De esta manera de van a imprimir los dos componentes

* **Elberth Jair Agreda Rosero** (3) [779112](https://platzi.com/comentario/779112/) 

	Pueden usar Angular Console: <https://angularconsole.com/>

	* **David Alejandro Mosquera Moreno** [779112] (1)

		woah tremendo aporte!

* **Chelvis** (3) [608932](https://platzi.com/comentario/608932/) 

	Tambien puede ser ng g c login

* **Carlos Uriel de Jesus Sánchez González** (3) [397172](https://platzi.com/comentario/397172/) 

	Un componente en Angular está compuesto mínimamente por un archivo html y un archivo de Typescript, siendo el .html la vista y el .ts la lógica que ésta tiene asociada. Un componente podemos verlo como cada una de las vistas de nuestra app.  
	Generalmente, para cada componente se usa sólo un archivo css con los estilos del componente, aunque la propiedad styleUrls permite varios css.
	``` 
	    ng generatecomponent <nombre>
	    
	```

* **Jhoysner Corona** (3) [379148](https://platzi.com/comentario/379148/) 

	Pueden tambien usar el comando "ng g c login"  
	donde la g es el abreviado de generate y el c de component

* **David Flores** (2) [694966](https://platzi.com/comentario/694966/) 

	Para poder ver todo lo que podemos generar, se escribe el siguiente comando:
	``` 
	    ng g
	    
	```

* **tono2** (2) [413640](https://platzi.com/comentario/413640/) 

	Hola tengo un problema cuando creo todos los archivos en el la barra de tareas donde esta login por ejemplo  
	dentro de esa carpeta me aparecen todos los archivos en color rojo estoy utilizando webStorm  
	eso es normal

	* **alejandrarock** [413640] (1)

		Checa la consola de errors esta usualmente en la parte de abajo del IDE, ahi se mostrara el detalle o con cursor sobre las carpetas rojas.

* **edu1590** (2) [405549](https://platzi.com/comentario/405549/) 

	Hasta ahora este curso esta mucho mejor explicado y comentado que el anterior.

	* **Kevin Lozoya Giner** [405549] (4)

		o puede que ahora sepas más y todo le encuentras más sentido 😉

	* **Brayan Mamani** [405549] (1)

		Ambos son excelentes cursos.

* **Anthony Gonzalez** (2) [366575](https://platzi.com/comentario/366575/) 

	Excelente repaso, muy util para refrescar los fundamentos de angular

* **ehnbytes** (1) [1015358](https://platzi.com/comentario/1015358/) 

	Buena clase!

* **Jose Laya** (1) [860483](https://platzi.com/comentario/860483/) 

	Que configuración debe hacerse para usar sass en lugar de css?

	* **basanchez** [860483] (1)

		Al momento de crear el proyecto lo puedes especificar:
		``` 
		    ng new app --style=scss
		    
		```
		
		Tienes mas opciones a su vez
		``` 
		    --style=scss
		    --style=sass
		    --style=less
		    
		```

* **David Alejandro Mosquera Moreno** (1) [849099](https://platzi.com/comentario/849099/) 
🅰️ Repasando un poco Para abrir la app y ponerla a correr: ng serve - -open Para crear un componente: ng generate component <nombre del componente> O también puede ser: ng g c <nombre del componente>

* **stiag0** (1) [650976](https://platzi.com/comentario/650976/) 

	¿puedo no parar la ejecucion para crear un componente,service…, usando otra terminal, puedo corromper algo?

	* **Diego Alexander Forero Higuera (Platzi)** [650976] (1)

		Puedes usar otra terminal sin problema, lo que no estoy seguro es si el servidor va a detectar el cambio y reiniciarse, si no es así debes parar la ejecución y volverla a iniciar para que tome los cambios de tu componente. Prueba y nos cuentas como te va.

	* **Juan Camilo Rico Orjuela** [650976] (1)

		No hay ningún problema. Al agregar un componente nuevo o guardar una modificación a alguno de los ficheros de la aplicación, esta se compila automáticamente si se encuentra en ejecución.

	* **Arturo Mojica Guerrero** [650976] (1)

		Esa es una de las magias de angular con ng serve que el internamente detecta todos los cambios para compilar y ejecutar. En conclusión puedes crear diferentes recursos sin parar el servidor y este de forma sutil los pondrá a funcionar.

* **Brayan Mamani** (1) [560749](https://platzi.com/comentario/560749/) 

	Crear componentes:
	``` 
	    ng generatecomponent
	    
	```

	* **ITEMPRESARIAL LIC 2** [560749] (2)
Crear componentes: ng g c "componente"

	* **kelvin diego** [560749] (1)
O ng g component

* **JhonAmber** (1) [558961](https://platzi.com/comentario/558961/) 

	Exelente!!!

* **Alex Eugenio Gavidia Donayre** (1) [535739](https://platzi.com/comentario/535739/) 
Es bien pro. Respect Angular

* **Alex Eugenio Gavidia Donayre** (1) [535737](https://platzi.com/comentario/535737/) 
Estoy emocionado con el curso

* **Alex Eugenio Gavidia Donayre** (1) [535736](https://platzi.com/comentario/535736/) 
Amazing

* **Alex Eugenio Gavidia Donayre** (1) [535728](https://platzi.com/comentario/535728/) 
Excelente curso

* **CristianAlfonso** (1) [513542](https://platzi.com/comentario/513542/) 

	Aunque use el routerLink cada vez que navego en mi menu se vuelve a cargar el favicon.ico. Alguno sabe por qué?

	* **Alfonso Adame Rueda** [513542] (1)

		hola buenos dias , para que funcione el routerLink debe estar en el app.component.html como una lista , asi:  
		<li routerLinkActive=“active”><a routerLink="/lugares">Inicio<span class=“sr-only”>(current)</span></a></li>  
		ademoas deber estar en el app.module.ts como una constante ,asi :const AppRoutes:Routes = [  
		{path:’’, component: LugaresComponent},  
		{path:‘lugares’, component: LugaresComponent}, y debe estar importado asi:import { Routes,RouterModule } from “@angular/router”;  
		espero haberte ayudado.

* **Anderson Steve Santamaría Ballesteros** (1) [448288](https://platzi.com/comentario/448288/) 

	“Para indicar a Angular cuál será el componente inicial de la aplicación, debemos indicar el nombre de dicho componente en la propiedad selector del archivo app.component.ts”, esta parte no la entiendo, no sé si quisiste decir en el app.module.ts, saludos.

* **Lito López** (1) [447842](https://platzi.com/comentario/447842/) 

	Y en el caso que escribí mal el nombre del componente al crearlo, como le hago para eliminar o renombrar?

	* **Anderson Steve Santamaría Ballesteros** [447842] (1)

		solamente te paras en la carpeta que te crea, le das click derecho, eliminar, y lo vuelves a generar bien.

	* **OCAPITALMX** [447842] (3)

		No recomendaría renombrarlo porque tienes muchas dependencias. Puedes usar simplemente angular-cli para generar otro:
		
		`ng g component nombre-del-componente`
		
		Y eliminar el folder del otro componente.
		
		P.D. No te olvides de quitar la dependencia en el array de declarations del módulo en el que esté importado tu componente.

* **César Rodolfo Vicuña Méndez** (1) [411328](https://platzi.com/comentario/411328/) 

	Saludos, hice tal cual los procedimientos y no me arrojó ningún error

* **patriciavaldebenitop** (1) [81449](https://platzi.com/comentario/981516/) 
hola me aparece ““Doctype must be declared first.”” en menu.component.html en la consola ( ver imagen adjunta) tengo DOCTYPE EN index.h...

* **Pablo Azuaje** (1) [73273](https://platzi.com/comentario/831513/) 
Se puede setear un valor de un input change ng-reflect-model value y actualizar el valor de esa directiva???

* **Lito López** (1) [47851](https://platzi.com/comentario/447842/) 
Y en el caso que escribí mal el nombre del componente al crearlo, como le hago para eliminar o renombrar?

	* **Anderson Steve Santamaría Ballesteros** [47851] (1)

		solamente te paras en la carpeta que te crea, le das click derecho, eliminar, y lo vuelves a generar bien.

* **tono2** (1) [44909](https://platzi.com/comentario/413640/) 
Hola tengo un problema cuando creo todos los archivos en el la barra de tareas donde esta login por ejemplo dentro de esa carpeta me apar...

	* **alejandrarock** [44909] (1)

		Checa la consola de errors esta usualmente en la parte de abajo del IDE, ahi se mostrara el detalle o con cursor sobre las carpetas rojas.

* **César Rodolfo Vicuña Méndez** (1) [44733](https://platzi.com/comentario/411328/) 
Saludos, hice tal cual los procedimientos y no me arrojó ningún error

## 0120. Navegación básica entre componentes [12755](https://platzi.com/clases/1340-angular-avanzado/12755-navegacion-basica-entre-componentes/)

### Descripción:


Para implementar _ruteo_ , que es la capacidad de navegar entre componentes (vistas) en Angular, es necesario importar `Routes` desde `@angular/router` en el componente base de nuestra app:
``` 
    import { Routes } from '@angular/router';
    
```

Luego se deben declarar todas las rutas que vamos a usar en una constante de tipo `Routes`:
``` 
    ...
    const appRoutes: Routes = [
      { path: '', component: HomeComponent },
      { path: 'home', component: HomeComponent },
      { path: 'login', component: LoginComponent }
    ];
    ...
    
```

Se incluyen todas las rutas definidas como elementos de un arreglo de objetos json de JS.  
La propiedad `path` va a comparar el segmento coincidente en la url, mientras que `component` indica hacia cuál componente se va a navegar.

Para hacer funcionar las rutas en nuestra app, se debe importar el módulo `RouterModule` en la sección imports del app.component.ts ya que éste no se importa de manera automática.

Finalmente para implementar la navegación en nuestra app, es necesario indicar en el contenido de `app.component.html` una directiva `<router-outlet></router-outlet>` que se utilizará para inyectar eventualmente los componentes de toda la navegación que hemos definido. Todo lo que se coloque en el html, fuera de esta directiva, quedará fijado como contenido común en todas las vistas de nuestra navegación.

Es importante tener en cuenta que al usar enlaces o anclas ( `<a> ... </a>` ) de html, tendremos que sustituir el atributo _href_ por _routerLink_ , que es parte de RouterModule, para evitar la recarga completa de la página y la latencia, ya que esto iría en contra del concepto fundamental de lo que es una SPA (single page app).

### Comentarios:

* **Alfonso Navarro** (8) [714063](https://platzi.com/comentario/714063/) 

	En Angular 8 a instalarse pregunta si queremos instalar Angular-Router y genera un archivo llamado “ **app-routing.module** ” que es donde colocariamos las rutas e igualmente funciona.

	* **Jonathan R. Zambrano** [714063] (1)

		en ese archivo yo hice esto y funciona super bien
		``` 
		    constroutes: Routes = [
		      {path: 'home', component: HomeComponent },
		      {path: 'login', component: LoginComponent},
		      {path: 'conversation', component: ConversationComponent},
		      {path: 'profile', component: ProfileComponent},
		      {path: '', component: HomeComponent}
		    ];
		    
		    @NgModule({
		      imports: [RouterModule.forRoot(routes)],
		      exports: [RouterModule]
		    })
		    export class AppRoutingModule { }
		    
		```

* **waldoaraque** (7) [524394](https://platzi.com/comentario/524394/) 

	En la platilla de Angular que generan a partir de Angular CLI, ya viene incluido el **app-routing.module.ts ** en este archivo sólo deben crear el objeto para llamar a los componentes e importar los mismos. 😉

	* **Cristian Florez** [524394] (1)

		Por favor explicame  
		No entiendo, osea que puedo poner el array de rutas en el archivo app-routing.modele.ts y en el archivo de app.module.ts ponerlo en el imports??  
		Puedes dar un ejemplo

	* **David Flores** [524394] (1)

		Eso te la crea por que al crear el proyecto le indicaste que te generara las rutas.

* **carlosextra1** (7) [362944](https://platzi.com/comentario/362944/) 

	vamos super con el curso, desde basico y creo que hasta avanzado!

	* **Diego Burlando** [362944] (4)

		este curso promete!

* **Maximino Castillo García** (5) [409658](https://platzi.com/comentario/409658/) 

	Existe un archivo llamado **app-routing.module.ts** que es generado automaticamente para eso, solo se agregan los paths.

	* **moises mannarino** [409658] (6)

		eso es en angular 7

	* **Maximino Castillo García** [409658] (2)

		Es verdad, no me había percatado de que era la version 7

	* **Cristian David Franco Garcia** [409658] (1)

		Sin embargo, por buena practica es necesario crear el archivo app-routing.module.ts para crear las rutas e importarlo en app.module.ts.

* **Damaris Quiroz** (5) [381857](https://platzi.com/comentario/381857/) 

	A tener en cuenta cuando empiezas con RouterLink. Hace la recomendacion de usar las rutas con el **“/”**
	``` 
	    <arouterLink="/home"> Home </a>
	    
	```

* **Javi Felices** (4) [731664](https://platzi.com/comentario/731664/) 

	Solo quería resaltar la asombrosa explicación que te has marcado Eduardo sobre las rutas, de una forma sencilla a más no poder, gracias 😃

* **Gian Pumayalla** (3) [551691](https://platzi.com/comentario/551691/) 

	¿El mejor plugin de visual studio code para que haga el auto import?

	* **Brayan Mamani** [551691] (2)

		Esta es muy buena: <https://marketplace.visualstudio.com/items?itemName=steoates.autoimport>

	* **Carlos Flores** [551691] (2)

		TypeScript Importer.

* **YojanPardo** (2) [1003604](https://platzi.com/comentario/1003604/) 

	importante tener en cuenta que si instalaron la última versión de angular, a la hora de crear el proyecto él les va a preguntar si desean instalar un enrutador (app-routing.module.ts), en ese caso es allí donde deben instanciar las rutas de los nuevos componentes

* **Damian Spizzirri** (2) [633125](https://platzi.com/comentario/633125/) 

	Lo que esta sucediendo aca es que Angular solamente esta actualizando el DOM verdad? No esta recargando todo. Me equivoco?

	* **eric-alejandro-asce** [633125] (1)

		Al utilizar el routerLink si es lo que hace, al utilizar el href recarga toda la pagina

* **eliponce** (2) [541746](https://platzi.com/comentario/541746/) 

	para los que usan angular 7 y les aparece
	``` 
	    import { AppRoutingModule } from'./app-routing.module';
	    
	```
	
	abrir app-routing.module (ctrl+click) y va este codigo
	``` 
	    import { NgModule } from '@angular/core';
	    import { Routes, RouterModule } from '@angular/router';
	    import { HomeComponent } from './home/home.component';
	    import { LoginComponent } from './login/login.component';
	    import { ConversationComponent } from './conversation/conversation.component';
	    import { ProfileComponent } from './profile/profile.component';
	    
	    constroutes: Routes = [
	      {
	        path: '',
	        component:HomeComponent
	      },
	      {
	        path: 'home',
	        component:HomeComponent
	      },
	      {
	        path:'login',
	        component: LoginComponent
	      },
	      {
	        path:'conversation',
	        component:ConversationComponent
	      },
	      {
	        path:'profile',
	        component: ProfileComponent
	      }
	    ];
	    
	    @NgModule({
	      imports: [RouterModule.forRoot(routes)],
	      exports: [RouterModule]
	    })
	    export class AppRoutingModule { }
	    
	```

* **marioamaciasortiz** (1) [828355](https://platzi.com/comentario/828355/) 

	esta muy interesante lo del routeo

* **laurest** (1) [737023](https://platzi.com/comentario/737023/) 

	Hola buenas, no entendí por que se pone el {path:’ ', component:HomeComponent} alguien me podría por favor aclararme ?

	* **carlos ruales** [737023] (5)

		Cuando lo dejas vacío, es decir, sin una ruta especifica dentro de tu navegador (en palabras coloquiales, sin la barrita y algo (/algo)) lo que hará es que te llevará al componente HomeComponent, por eso ves que si entras a home, es decir: localhost:4000/Home o entras a localhost:4000 te mostrará lo mismo, ya que los dos apuntan a él.

	* **marioamaciasortiz** [737023] (1)

		Esto es para cuando solo te diriges a la raiz del sitio es decir no estas entrando a ninguna ruta mas, el path te redirige automaticamente a Home, lo que comenta el instructior es que despues por un mecanismo revisaremos si esta logueado el usuario y de no ser asi, lo redirigira a login.

	* **eric-alejandro-asce** [737023] (1)

		Es un catalogo de posibles entradas en la URL que el usuario puede ingresar y de ahí la app decidir que modulo mostrar

* **Gian Pumayalla** (1) [551682](https://platzi.com/comentario/551682/) 

	¿Que hace router-outlet ?

	* **hector_pulido_** [551682] (3)

		Es una especie de place holder, es decir, un espacio que luego será utilizado por una ruta

	* **David Flores** [551682] (1)

		Te recomiendo siempre buscar en la documentación, esta muy completa, ademas aporta mucho al conocimiento leer la documentación  
		[Quiero leer la documentación](https://angular.io/api/router/RouterOutlet)

	* **David Alejandro Mosquera Moreno** [551682] (1)

		En el **_< router-outlet>_** se inyectan los componentes que hayamos pasado como **rutas de navegación** anteriormente.

* **Alex Eugenio Gavidia Donayre** (1) [549053](https://platzi.com/comentario/549053/) 

	```
	    import { BrowserModule } from '@angular/platform-browser';
	    import { NgModule } from '@angular/core';
	    
	    import { AppComponent } from './app.component';
	    import { HomeComponent } from './home/home.component';
	    import { LoginComponent } from './login/login.component';
	    import { SchedulesComponent } from './schedules/schedules.component';
	    import { MenuComponent } from './menu/menu.component';
	    import { RouterModule, Routes } from '@angular/router';
	    
	    
	    // __1. Declaramos una constante para las rutas
	    constappRoutes: Routes = [
	      {path: '', component: HomeComponent},
	      {path: 'home', component: HomeComponent},
	      {path: 'login', component: LoginComponent},
	      {path: 'schedules', component: SchedulesComponent}
	    ];
	    
	    @NgModule({
	      declarations: [
	        AppComponent,
	        HomeComponent,
	        SchedulesComponent,
	        MenuComponent,
	        LoginComponent
	      ],
	      imports: [
	        BrowserModule,
	        RouterModule.forRoot(appRoutes)// __2. Agregar la constante declarada.
	      ],
	      providers: [],
	      bootstrap: [AppComponent] // __3.Definir Cual será el componente que inicie.
	    })
	    export class AppModule { }
	    
	    
	```

* **Alex Eugenio Gavidia Donayre** (1) [549052](https://platzi.com/comentario/549052/) 

	```
	    <nav>
	      <!-- routerLink es una directiva de typeScript para simular la navegación de Single Page Application -->
	    <arouterLink="/login">Login</a> |
	    <arouterLink="/home">Inicio</a> |
	    <arouterLink="/schedules">Horarios</a> |
	    </nav>
	    
	    
	```

* **Alex Eugenio Gavidia Donayre** (1) [536052](https://platzi.com/comentario/536052/) 
Increíble

* **Ernesto Vizcaíno Alvarado** (1) [499619](https://platzi.com/comentario/499619/) 

	No entiendo como aparece el menu que es lo que lo llama y que es una ruta

	* **Alfonso Adame Rueda** [499619] (1)

		hola buenas tardes, lo que da la navegación entre componentes, es el app.routing ,dinos , si te refieres a una barra de navegación, la cual se incluye desde el app.component.html  
		te recomiendo también hacer el curso de angular 4 donde se explican en detalle estos temas,

* **dcortesnet** (1) [446155](https://platzi.com/comentario/446155/) 

	Angular a mi parecer es mucho más rápido de crear apps que con react

	* **Brayan Mamani** [446155] (1)

		Si es mucho mas rápido y sencillo.

* **Jhonmarioh** (1) [439459](https://platzi.com/comentario/439459/) 

	buenas noches Eduardo.  
	tengo una duda, porque cuando creo la constante en no me crea automáticamente el import ? usando el mismo editor Webstorm ?  
	porque cuando lo hago manualmente me queda como inactivo ?

	* **Sergio Danilo García Ruíz** [439459] (1)

		Verifique que tiene instalado el plugin para que reconozca e importe a la hora de invocar y si esta inactivo es porque solo lo importo pero no lo esta usando en ninguna parte del código

* **Santiago Patiño** (1) [419547](https://platzi.com/comentario/419547/) 

	Que maravilla de clase.

* **jeisonsrz** (1) [415007](https://platzi.com/comentario/415007/) 

	código agregado en app.modules.ts —>
	``` 
	    constappRoutes: Routes = [
	      {path: '', component: HomeComponent},
	      {path: 'home', component: HomeComponent},
	      {path: 'login', component: LoginComponent},
	      {path: 'conversation', component: ConversationComponent},
	      {path: 'profile', component: ProfileComponent},
	    ];
	    
	    @NgModule({
	      declarations: [
	        AppComponent,
	        LoginComponent,
	        HomeComponent,
	        ConversationComponent,
	        ProfileComponent
	      ],
	      imports: [
	        BrowserModule,
	        RouterModule.forRoot(appRoutes)
	      ],
	      providers: [],
	      bootstrap: [AppComponent]
	    })
	    
	```
	
	código agregado en app.component.html —>
	``` 
	    <arouterLink="/home">home</a> -
	    <arouterLink="/login">Login</a> -
	    <arouterLink="/profile">Profile</a>
	    <router-outlet></router-outlet>
	    
	    
	```

* **César Rodolfo Vicuña Méndez** (1) [411371](https://platzi.com/comentario/411371/) 

	Tengo un problema, en consola me dice webpack required: Bootstrap

* **miguelpayano** (1) [403925](https://platzi.com/comentario/403925/) 

	```
	    import { BrowserModule } from "@angular/platform-browser";
	    import { NgModule } from "@angular/core";
	    
	    import { AppComponent } from "./app.component";
	    import { LoginComponent } from "./pages/login/login.component";
	    import { HomeComponent } from "./pages/home/home.component";
	    
	    import { Routes } from "@angular/router";
	    
	    constappRoutes: Routes = [{ path: "home", component: HomeComponent }];
	    
	    @NgModule({
	      declarations: [AppComponent, LoginComponent, HomeComponent],
	      imports: [BrowserModule],
	      providers: [],
	      bootstrap: [AppComponent]
	    })
	    export class AppModule {}
	    
	    
	```
	
	se estan marcando todas las importaciones me sale un error tslist que esta mal algo asi como lo soluciono si solo he creado el proyeccto tal como dijo

* **miguelpayano** (1) [403885](https://platzi.com/comentario/403885/) 

	error al generar la creacion de componente
	
	Schematic “componet” not found in collection “@schematics/angular”.  
	Error: Schematic “componet” not found in collection “@schematics/angular”.

* **Carlos Uriel de Jesus Sánchez González** (1) [397198](https://platzi.com/comentario/397198/) 

	```
	    import { Routes } from '@angular/router';
	    
	    constappRoutes: Routes = [
	      { path: '', component: HomeComponent },
	      { path: 'home', component: HomeComponent },
	      { path: 'login', component: LoginComponent }
	    ];
	    
	```

* **Diego Alberto González González** (1) [396669](https://platzi.com/comentario/396669/) 

	Hola. Tengo problemas con RouterModule.forRoot(appRoutes), no puedo cargar las otras vistas si tnego esta línea de código. ¿Alguno de ustedes les sucedió lo mismo? Les agradecería su apoyo

	* **Diego Alberto González González** [396669] (3)

		Tras investigar encontré la solución. Se debe agregar en el import { Routes } from ‘@angular/router’;, import { Routes, RouterModule } from ‘@angular/router’;

	* **marczg21** [396669] (1)

		Gracias me paso lo mismo (y)

	* **Brayan Mamani** [396669] (1)

		Genial gracias por la sugerencia.

* **carlos Alberto Bedoya Ramirez** (1) [394352](https://platzi.com/comentario/394352/) 

	Se puede crear el archivo de rutas aparte, y que no quede en el archivo app.component.ts

	* **waldoaraque** [394352] (1)

		si, de hecho el mismo Angular CLI lo genera, sólo debes crear las  
		`routes` e importar los componentes

* **jdgarcia6** (1) [394151](https://platzi.com/comentario/394151/) 

	Este curso es cada vez más interesante. voy con toda!!

* **Mauricio Peña** (1) [86125](https://platzi.com/comentario/1088760/) 
Hola a todos me aparece este error:

	* **Juan David Castro (Platzi)** [86125] (1)

		Mauricio, ¿podrías mostrarnos tu archivo **`app.module.ts`**? Más exactamente las 10 primeras líneas. Tal vez nos puedan indicar el problema. 🙏

* **Edwin De Jesus Chiyopa Garcia** (1) [61226](https://platzi.com/comentario/618382/) 
El las herramientas para desarrolladores en el apartado de console, me aparece el siguiente error Unchecked runtime.lastError: The messag...

* **Gian Pumayalla** (1) [56362](https://platzi.com/comentario/551691/) 
¿El mejor plugin de visual studio code para que haga el auto import?

	* **Brayan Mamani** [56362] (2)

		Esta es muy buena: <https://marketplace.visualstudio.com/items?itemName=steoates.autoimport>

* **Gian Pumayalla** (1) [56361](https://platzi.com/comentario/551682/) 
¿Que hace router-outlet ?

	* **hector_pulido_** [56361] (3)

		Es una especie de place holder, es decir, un espacio que luego será utilizado por una ruta

* **Ernesto Vizcaíno Alvarado** (1) [52028](https://platzi.com/comentario/499619/) 
No entiendo como aparece el menu que es lo que lo llama y que es una ruta

	* **Alfonso Adame Rueda** [52028] (1)

		hola buenas tardes, lo que da la navegación entre componentes, es el app.routing ,dinos , si te refieres a una barra de navegación, la cual se incluye desde el app.component.html  
		te recomiendo también hacer el curso de angular 4 donde se explican en detalle estos temas,

* **Jhonmarioh** (1) [47144](https://platzi.com/comentario/439459/) 
buenas noches Eduardo. tengo una duda, porque cuando creo la constante en no me crea automáticamente el import ? usando el mismo editor W...

	* **Sergio Danilo García Ruíz** [47144] (1)

		Verifique que tiene instalado el plugin para que reconozca e importe a la hora de invocar y si esta inactivo es porque solo lo importo pero no lo esta usando en ninguna parte del código

## 0130. Componentes anidados Creando un componente con nuestras rutas de navegación que funcione como menú [12756](https://platzi.com/clases/1340-angular-avanzado/12756-componentes-anidados-creando-un-componente-con-nue/)

### Descripción:


Angular permite anidar componentes o colocarlos como hermanos, al mismo nivel.

Esto significa que si tenemos código de HTML que puede ser extraído hacia un nuevo componente para ser reutilizado de manera más óptima en nuestro código, podemos hacerlo usando el mismo procedimiento con el que creamos los componentes de cada pantalla de nuestra app, e incluirlos luego como parte del contenido de dichas pantallas, o en el `app.component.html`, fuera de la directiva de enrutamiento, para que sea accesible en todas las páginas, como es el caso del menú de navegación.

### Comentarios:

* **edgon85** (9) [402138](https://platzi.com/comentario/402138/) 

	Una forma corta de generar el componente
	``` 
	    ng g c menu
	    
	```
	
	g de generate  
	c de component

	* **WilliWonk** [402138] (1)

		ufff gracias men!!!

	* **Brayan Mamani** [402138] (1)

		Muy buen truco. 😃

* **jeisonsrz** (4) [415023](https://platzi.com/comentario/415023/) 

	```
	    ng generate component menu 
	    
	```
	
	app.compnent.html —>
	``` 
	    <app-menu></app-menu>
	    <router-outlet></router-outlet>
	    
	    
	```
	
	menu.component.html
	``` 
	    <arouterLink="/home">home</a> -
	    <arouterLink="/login">Login</a> -
	    <arouterLink="/profile">Profile</a>
	    
	    
	```

* **rubianllanos** (3) [682568](https://platzi.com/comentario/682568/) 

	Me está gustando mucho angular, brutal este curso.

* **carlosextra1** (3) [362947](https://platzi.com/comentario/362947/) 

	Esto es muy importante, ya que se genera el componen menu, como si fuera un layout que se usa en laravel

* **David Alejandro Mosquera Moreno** (2) [849157](https://platzi.com/comentario/849157/) 

	Para no parar la app podemos abrir otra terminal y allí crear el componente. Aún haciéndolo así los cambios quedarán guardados…

* **renevillegasramirez** (2) [634098](https://platzi.com/comentario/634098/) 

	Hasta este punto el curso me ha parecido Súper!!

* **ehnbytes** (1) [1015545](https://platzi.com/comentario/1015545/) 

	Continuando con el curso!!

* **Cristian Florez** (1) [670090](https://platzi.com/comentario/670090/) 

	Se puede combinar Angular para el front y Laravel para el Back ?? en un mismo proyecto como se hace eso ?

	* **william andres rodriguez borja** [670090] (1)

		cuando separas el front del back puedes usar el lenguaje que desees por que los datos viajaran por api Rest

	* **Arturo Mojica Guerrero** [670090] (1)

		Pues, esa solución que tu propones la forma de combinarlo seria hacer dos proyectos independientes y a traves de API REST, es decir de conexión via http o socket puedes mandar y recibir información de ANGULAR a LARAVEL y viseversa

* **Brayan Mamani** (1) [560880](https://platzi.com/comentario/560880/) 

	Excelente la parte de modularizar componentes de nuestra aplicación y que sean independientes.

* **Carlos Uriel de Jesus Sánchez González** (1) [397226](https://platzi.com/comentario/397226/) 

	Muy buena explicacion

* **Alejandro Salazar** (1) [366826](https://platzi.com/comentario/366826/) 

	si quiero que el menu se muestre luego del login, es decir en /login no se debe mostrar y en /home y en las otras paginas si, como se maneja este caso?

	* **Julio J Yépez** [366826] (4)

		Puedes usar la directiva estructural *NgIF que se ve más adelante en el curso.

## 0140. Reto Varias conversaciones a la vez [13002](https://platzi.com/clases/1340-angular-avanzado/13002-reto-varias-conversaciones-a-la-vez/)

### Descripción:


En Platzinger, sólo es posible tener abierta una conversación a la vez, pero sería muy bueno poder tener abiertas varias.

Así que propón una manera de tener más de una conversación abierta al mismo tiempo (a través de tabs, por ejemplo), y después de terminar el curso, impleméntala.

### Comentarios:

* **Marcelino Hernández López** (6) [365089](https://platzi.com/comentario/365089/) 

	Un componente que contenga las conversaciones
	``` 
	    <app-conversations></app-conversations>
	    
	```
	
	donde este se encargue de contener las conversaciones activas y proporcionar un estilo visual más intuitivo como usar **tabs**
	``` 
	    <app-conversations>
	    	<app-conversation *ngFor="let chat of chats">
	    	<app-conversation>
	    </app-conversations>
	    
	```

* **asfo** (5) [384198](https://platzi.com/comentario/384198/) 

	Es muy simple.
	
	Lo primero es que cada conversación se considere un array, se debe generar un componente que en este, maneje/administre las conversaciones.
	
	Una vez teniendo esto, por ejemplo…si se abre una conversación hace un .push() al arreglo con los datos del identificador de la conversación y de esta forma dar de alta las tabs.
	
	Algo que dijeron en el comentario del *ngFor está en lo correcto, en teoría así se debería de dar de alta, pero, el class=“active” no debería funcionar tanto así…ya que ahí debería usarse la directiva [ngClass] para que entonces, se asigne la clase únicamente al chat activo.
	
	Asimismo, debajo de cada tab únicamente debe mostrarse la conversación relacionada al tab y esto se maneja de la misma forma que la clase activa pero haciendo un *ngIf="".

* **Samack77** (5) [366872](https://platzi.com/comentario/366872/) 

	Através de Bootstrap podemos utilizar nav pills
	``` 
	    <ulclass="nav nav-tabs">
	      <liclass="active" *ngFor="let chat of chats"><ahref="#"></a>{{chat.nombre}}</li>
	    </ul>
	    
	```

* **jeisonsrz** (3) [415027](https://platzi.com/comentario/415027/) 

	Ola Ke Ace…tengo que ver más el curso para poder tener una idea :’(

* **e.rodriguez** (2) [832728](https://platzi.com/comentario/832728/) 

	iterando por los diferentes componentes ‘conversation’ , los visualizamos plegados en un acordeón y en función de nuestra necesidad o de la notificación los vamos desplegando.

* **JesusVarela** (2) [769634](https://platzi.com/comentario/769634/) 

	que se creen nuevas ventanas al clikear un usuario diferente.

* **JorgeMontesinos** (2) [757274](https://platzi.com/comentario/757274/) 

	Un ngFor en tabs podria ser

* **Alfonso Navarro** (2) [714071](https://platzi.com/comentario/714071/) 

	Una clasica e intutiva me parece es tener tabs en la parte superior con las multiples conversaciones.

* **ariel Silva** (2) [674388](https://platzi.com/comentario/674388/) 

	como e l chat de hangoust…todas abajo

* **Briggs** (2) [637331](https://platzi.com/comentario/637331/) 

	El componente “chat” sería una sola conversación y al entrar al componente “home”, si hay alguna conversación abierta con algún timer (?) se indexaría abajo a la izquierda… con un componente llamada “mini-chat”. Se podría minimizar o cerrar dependiendo del usuario. Algo como lo que tiene care-libro jaja

* **renevillegasramirez** (2) [634113](https://platzi.com/comentario/634113/) 

	Pienso que debería existir un panel con las conversaciones activas, y tener ese componente visible como parte del **conversation.component** para poder “brincar” de una conversación a otra. El uso de tabs podría ser complicado cuando sean demasiadas conversaciones activas, quizás una lista sea más fácil de controlar.

* **Brandon Iván Quiroa Loarca** (2) [609761](https://platzi.com/comentario/609761/) 

	Yo implementaria en la vista conversation, un “menu” de las conversaciones como cuando usamos routerlink para navegar entre las vistas, solo que ahora seria para navegar entre conversaciones.

* **Steven18** (2) [602440](https://platzi.com/comentario/602440/) 

	Se crea un componente que reciba como un Input el objeto chat del arreglo. Con el ngClass se le da estilo al componente para simular la apariencia de un tab
	``` 
	    <div *ngFor="let chat of chats">
	    	<div [ngClass]="tab-chat">
	    		<app-chats [chatActive]="chat"></app-chats>
	    	</div>
	    </div>
	    
	```

* **eduardo-moora** (2) [561111](https://platzi.com/comentario/561111/) 

	no tengo idea jajaj

* **Sigaweb** (2) [496222](https://platzi.com/comentario/496222/) 

	suena interesante, veo que esta caja de texto tiene algunas características que la hacen llamativa, esto es propio de angular o es una librería?

* **Diego Mauricio Mejía Ospina** (2) [441595](https://platzi.com/comentario/441595/) 

	Lo que yo propongo es crear un array que administre los mensajes entrantes, pero que no se abran… haya un limite de mensajes abierto .  
	Creo que con un componente ngFor

* **Danie contreras** (1) [1103174](https://platzi.com/comentario/1103174/) 

	pienso que seria bueno que por cada conversación activa, el layout de el chat se divida equitativamente para cada conversación

* **Erik Ricardo Sánchez Pérez** (1) [1024945](https://platzi.com/comentario/1024945/) 

	bueno se me ocurre que las ventanas de chat sean cards y que uno pueda moverlas con drag
	
	<https://developer.mozilla.org/en-US/docs/Web/API/HTML_Drag_and_Drop_API/Drag_operations>
	
	<https://www.w3schools.com/howto/howto_js_draggable.asp>

* **Fernando Vallejo** (1) [1000222](https://platzi.com/comentario/1000222/) 

	Utilizando Sockets

* **monica0115** (1) [958600](https://platzi.com/comentario/958600/) 

	Tener en una ventana separado por tabs las conversaciones

* **Edgar Damian Morales Aguirre** (1) [954106](https://platzi.com/comentario/954106/) 

	Se pudiera generar una pestaña por cada conversación abierta

* **Jpenavar** (1) [942810](https://platzi.com/comentario/942810/) 

	seria muy bueno implementarla cuando culmine el curso que esta interesantisimo

* **Francisco Genaro Cerna Fukuzaki** (1) [900009](https://platzi.com/comentario/900009/) 

	Se podría utilizar web socket para que en cada pestaña se tenga una conversación diferente.

* **Mauricio Quiñones** (1) [876431](https://platzi.com/comentario/876431/) 

	Implementar en el componente unos subcomponentes y navegar entre ellos con el routerLink

* **Juan Antonio Campoy Lira** (1) [863226](https://platzi.com/comentario/863226/) 

	mantener en escucha diferentes accesos a mano izquierda sobre los cambios que haya en base de datos en el componente de chat

* **David Alejandro Mosquera Moreno** (1) [849164](https://platzi.com/comentario/849164/) 

	Lo primero que se me vino a la mente: De alguna manera dejar registrado las personas con las que estamos hablando y que dependiendo de esto, los tabs queden fijos en alguna parte de la pantalla así como lo hicimos con el menú : **_< app-menu></app-menu>_**

* **Zolider** (1) [814087](https://platzi.com/comentario/814087/) 

	Implementando un componente con código que cada vez que seleccione agregar un conversación, sume y lo agregue de acuerdo al usuario con el que deseo platicar.

* **caprilespe** (1) [790974](https://platzi.com/comentario/790974/) 

	Que se utilice componentes de tipo modal donde se envié por parámetro los datos de ese usuario.

* **carlos ruales** (1) [744781](https://platzi.com/comentario/744781/) 

	En 2 partes, un left side bar para la lista de conversaciones o chats y al lado derecho o central que tengan las conversaciones. Un whatsapp

* **joelpadilla** (1) [723463](https://platzi.com/comentario/723463/) 

	Algo así como la de WhatsApp con el listado de últimas conversaciones en el lateral izquierdo con opción a configurar si se quiere dejar ver el comienzo del último mensaje de cada conversación

* **angelfelipesalazarsuarez** (1) [720555](https://platzi.com/comentario/720555/) 

	Un buena forma es la que utiliza hangouts al ofrecernos multiples pestañas y no tabs superiores

* **ludwing_ra** (1) [701113](https://platzi.com/comentario/701113/) 

	Me gusta mucho el diseño que implementa Slack, en donde tenemos un menu lateral izquierdo que ocupe el 20% de la pantalla y el resto de la pantalla sea la conversación o el chat.

* **ma74ny** (1) [696036](https://platzi.com/comentario/696036/) 

	Tipo verticals-slides en la parte derecha de la pantalla, en forma de burbujas

* **Hans Vogt** (1) [668696](https://platzi.com/comentario/668696/) 

	Nuevas Ventanas tipo Tabs

* **Camiloalex1643** (1) [667374](https://platzi.com/comentario/667374/) 

	Podemos usarla simiar a Whatsapp. Una lista de contactos y cada contacto con un estilo especial para cuando haya menajes nuevos

* **juandelghans** (1) [647201](https://platzi.com/comentario/647201/) 

	Podemos tener una lista de conversaciones ordenadas por la fecha mas reciente de un mensaje con banderas que indiquen si tenemos mensajes pendientes por leer de una conversación.

* **yuyuman** (1) [624047](https://platzi.com/comentario/624047/) 

	creo que anidar en appconversations y routerlink para redirigir las ventanas de chat

* **Juan Gabriel Castro Bustos** (1) [613057](https://platzi.com/comentario/613057/) 

	agregar una nueva pestaña en el div principal que pueda ir cambiando entre conversación

* **franklin barco** (1) [611140](https://platzi.com/comentario/611140/) 

	a traves de pestañas al estilo de un navegador web

* **Chelvis** (1) [609620](https://platzi.com/comentario/609620/) 

	Que el componentes conversaions sea una carpeta donde tenga mas de un moduoloo?

* **rendona17** (1) [606904](https://platzi.com/comentario/606904/) 


* **Luis Angel Ramos Bañuelos** (1) [604173](https://platzi.com/comentario/604173/) 

	Utilizar componentes como el del ejemplo del video y cada vez que se llame a la fucion de chat, poder ir llamando a esos componentes

* **alvarodiazcastro** (1) [600235](https://platzi.com/comentario/600235/) 

	creo que se puede hacer duplicando de alguna manera toda la funcionalidad del componente conversation, cómo generando una nueva instancia por cada conversación

* **ozkartx** (1) [599452](https://platzi.com/comentario/599452/) 

	Aun no se como hacerlo, pero creo lo voy a intenta usando con lo que se acaba de ver en la clase anterior, usando router link y en el componente de conversation tener algunas vistas anidadas.

* **garbull** (1) [591153](https://platzi.com/comentario/591153/) 

	Al igual que el menú, podríamos tener un componente de conversación y vamos sumando bien sea a un panel o menú lateral cada una de las conversaciones que se vayan creando y así poder navegar entre ellas.

* **Ruben Garcia** (1) [582800](https://platzi.com/comentario/582800/) 

	Usando routerLink, las conversaciones pueden estar en un componente especifico, que funcionaria como contactos.

* **hectorchec** (1) [578324](https://platzi.com/comentario/578324/) 

	Podríamos utilizar un array de conversaciones y mostrar cada una como un tab, dependiendo del número de conversaciones activas, tendríamos que configurar cuántas se mostrarían a la vez, pues podría haber demasiadas conversaciones activas para el espacio disponible en pantalla.

* **Daniel González Morales** (1) [572414](https://platzi.com/comentario/572414/) 

	una lista de fotos en miniatura de las personas con conversaciones abiertas.
	
	Al mover el mouse sobre la lista se despliega.

* **Brayan Mamani** (1) [560887](https://platzi.com/comentario/560887/) 

	Una buena alternativa seria usar burbujas como las de facebook messenger cuando las toques usar tabs para abrir los chats y se van mostrando en pantalla.

* **Jesica Noelia Torres** (1) [558150](https://platzi.com/comentario/558150/) 

	No vi tanto codigo hasta el momento como para mencionar palabras claves que usa Angular pero a nivel estructura podemos pensar en un componente que contega una array o coleccion del componente conversation y luego se referenciara cada una donde sea necesario.

* **CristianAlfonso** (1) [555118](https://platzi.com/comentario/555118/) 

	Así como tenemos nuestro menú lo que propongo es tener un panel dinámico a la izquierda que se vaya anidando las conversaciones abiertas.

* **cesarcadavid** (1) [552930](https://platzi.com/comentario/552930/) 

	Hola… me gustaria tener un menú vertical al lado izquierdo con todos mis contactos pero dividida en tres secciones, una con los contactos que estoy chateando actualmente, otra con los contactos que se encuentren activos pero que no estoy chateando con ellos, y el ultimo con contactos inactivos, y por ultimo tener un buscador de contactos en ese mismo menú.

* **isclaem** (1) [552916](https://platzi.com/comentario/552916/) 

	Se podría generar una conexión mediante Sockets, la cual pueda administrar dichas conversaciones y esté actualizando el contenido del componente.

* **Miguel Castillo Cortes** (1) [548887](https://platzi.com/comentario/548887/) 

	pondré en mi lista de amigos junto al nombre de cada amigo una etiqueta que me indique si me ha enviado algún mensaje

* **Jhon Castrillon** (1) [535796](https://platzi.com/comentario/535796/) 

	Yo propongo que que esperemos hasta el final

* **Gabriel Solorzano** (1) [528789](https://platzi.com/comentario/528789/) 

	Creo que la mejor manera es con los elementos <ul><li>, dandoles por supuesto estilo CSS para que se vean mas bonitos y con una propiedad (onclick) para que llame a la conversacion correspondiente

* **jeisonsolarte** (1) [526543](https://platzi.com/comentario/526543/) 

	¿Existen las listas de componentes?
	
	Se me ocurre crear una lista que incremente cada vez que se selecciona una conversación y se gestione en el home, de esta manera se podrán visualizar en un solo componente.  
	Gracias, esta bueno el curso pa empezar desde cero.

* **__camilosanchez** (1) [517089](https://platzi.com/comentario/517089/) 

	Con un componente ( panel ) que siempre este visible, mostrando las conversaciones recientes y al darle click a cada una de ellas nos muestre el historial de conversación.

* **CristianAlfonso** (1) [513548](https://platzi.com/comentario/513548/) 

	Lo que propongo es tener un arreglo de la clase conversation que nos permita tener más de una a la vez

* **dev.team** (1) [490569](https://platzi.com/comentario/490569/) 

	La idea de los tabs esta muy bien, es cuestión de visibilidad que funcionalidad, en esa parte es donde se trabajara bastante, saludos

* **Adrian Camilo Caminos** (1) [483453](https://platzi.com/comentario/483453/) 

	lo haria con angular material con tabs o con un sidebar

* **Ricardo Anchaluisa Caza** (1) [480378](https://platzi.com/comentario/480378/) 

	Talvez se deberia crear un componente generico y manejarlo como array para cada conversación

* **Erick Suarez Zavala** (1) [472048](https://platzi.com/comentario/472048/) 

	una idea sería con tabs y css

* **Edison Jhon Moya Arias** (1) [468287](https://platzi.com/comentario/468287/) 

	Crear dos componentes, uno general que contenga todas las conversaciones actuales y el otro a manera de una burbuja de conversación.

* **Rubén Palavecino** (1) [465511](https://platzi.com/comentario/465511/) 

	Muy buen curso

* **Ezequiel-Fabbroni** (1) [465217](https://platzi.com/comentario/465217/) 

	Creo que lo mas viable y mas estándar es usar tabs, donde cada tab representa una iteración del mismo componente instanciado con una determinada conversación. Otra solución un poco mas avanzada podría ser la de tener imágenes miniaturas con la foto de perfil de cada amigo por cada conversación abierta.

* **Sigaweb** (1) [458600](https://platzi.com/comentario/458600/) 

	Habría que realizar un array de conversaciones

* **Ricardo José Galarza Palacios** (1) [456969](https://platzi.com/comentario/456969/) 

	Propongo usar burbujas como las de facebook messenger cuando las toques usar tabs para abrir los chats.

* **Anderson Steve Santamaría Ballesteros** (1) [449874](https://platzi.com/comentario/449874/) 

	Tener una barra lateral en la que estén las conversaciones.

* **Spyderp** (1) [441391](https://platzi.com/comentario/441391/) 

	En vez de tab agregaría una menu de miniaturas que indique que ventana de conversación se ve y cuando alguien me escribe aparezca una burbuja y poder navegar entre converzaciones

* **RENE HERRERA** (1) [440770](https://platzi.com/comentario/440770/) 

	se crea un componente conversación asociado a un tab, lo que seria una lista de componentes de conversación!

* **Calebisma** (1) [434429](https://platzi.com/comentario/434429/) 

	Estaría bueno que cada conversación sea un objeto de la clase o componente conversation

* **developerresol1** (1) [428175](https://platzi.com/comentario/428175/) 

	Para la implementación de varias conversaciones se podrían hacer con una etiqueta con el nombre del selector, cada conversación debe tener sus parámetros como el nombre del amigo, se podría utilizar el nombre del amigo para el tab.

* **Emerson-Lirmi** (1) [422309](https://platzi.com/comentario/422309/) 

	Se puede realizar por medio de la implementación de sockets, creando un objeto de tipo Conversación, crear el ServerSocket donde escuchar posibles nuevas conexiones y aceptar nuevos clientes
	``` 
	    publicclassServChat {
	    	publicstaticvoidmain (String [] arg) {
	    int port = (arg.length>0)?Integer.parseInt(arg[0]): 29029;
	    Conversacion conv = new Conversacion();
	    System.out.println("Servidor activado en port:" +port);
	    Try{ ServerSocket ss= new ServerSocket(port);
	    	System.out.println("Esperando conexion...");
	    	while(true) conv.altaCliente(ss.accept());
	    } catch (IOException e){ System.exit(-1);}
	    }
	    }
	    
	```
	
	Para nuevas conversaciones se itera un bucle infinito y en cada iteración se acepta una nueva conexión:
	``` 
	    while (true) conv.altaCliente(ss.accept());
	    
	```

* **jrapineda** (1) [410945](https://platzi.com/comentario/410945/) 

	Tener una sidebar en el area de conversaciones que nos indique las conversaciones activas.

* **henrymm** (1) [401507](https://platzi.com/comentario/401507/) 

	Se podría generar un *ngFor con las conversaciones actuales/activas

* **Juan Ahumada** (1) [399293](https://platzi.com/comentario/399293/) 

	¿se podria utilizar ngBootstrap, en especifico ngTab y con el routerlink cambiar el componente que se utiliza en el template?

* **Carlos Uriel de Jesus Sánchez González** (1) [397230](https://platzi.com/comentario/397230/) 

	Seria con la componente de conversation generar un ngFor con las convesaciones actuales y con ngClass atraves del click ponerla como activa.

* **leotangram** (1) [363113](https://platzi.com/comentario/363113/) 

	Podríamos implementar un componente anidado que contenga un “ngFor” con las conversasiones de los usuarios activos, esto con el fin de que sea más dinámico y no haya contaminación visual con los usuario no activos.

* **undefined** (1) [362958](https://platzi.com/comentario/362958/) 


	* **josearturoperezenriquez** [362958] (1)

		Usar un tab entre cada conversación

* **Juan Ahumada** (1) [43674](https://platzi.com/comentario/399293/) 
¿se podria utilizar ngBootstrap, en especifico ngTab y con el routerlink cambiar el componente que se utiliza en el template?

* **alanfermin** (0) [897540](https://platzi.com/comentario/897540/) 

	Agregar un atributo target="_blank" de forma automática a todos los link de las conversaciones, de esa forma abre una ventana nueva la hacer click

# Basics de Angular y TypeScript [2347]

## 0150. ¿Cómo usar tipos de datos con TypeScript [12757](https://platzi.com/clases/1340-angular-avanzado/12757-como-usar-tipos-de-datos-con-typescript7577/)

### Descripción:


TypeScript debe su nombre a los tipos de datos ( _types_ en inglés). JavaScript no es un lenguaje de programación tipado, por lo que es requerida en su sintaxis la definición de un tipo de dato al momento de instanciar las clases o variables en general. El uso de tipos explícitos en la programación permite a fin de cuentas un mejor aprovechamiento del recurso de memoria, entre muchos otros beneficios.

Los tipos básicos (built-in y definidos por el usuario) admitidos por TypeScript son: Boolean, Number, String, Array, Tuple, Enum, Void, Null y Undefined, y el tipo que es la base de todos los anteriores: Any, que básicamente representa cualquier cosa.

Los tipos de datos avanzados de Type  
Script incluyen: Function, Object, Interface, Guard, Union, entre otros.

### Comentarios:

* **Steven18** (6) [602458](https://platzi.com/comentario/602458/) 

	Con esta herramienta se puede escribir código en Typescript y poder ver su equivalencia en Javascript, también se encuentran diferentes ejemplos de como declarar clases, interfaces, tipos de datos, bucles, funciones asíncronas,etc.
	
	<https://typescript-play.js.org/>

* **Joss** (6) [504941](https://platzi.com/comentario/504941/) 

	para conocer un poco mas typescript:  
	<https://www.typescriptlang.org/docs/handbook/basic-types.html>

* **Diego Burlando** (4) [365242](https://platzi.com/comentario/365242/) 

	Esta clase le he estado esperando hace mucho, ya había investigado como funcionaban las variables de typescript pero con esta explicación me queda mucho mas claro.

* **Juan Carlos Pinzón** (3) [415220](https://platzi.com/comentario/415220/) 

	Estos tipos de datos existen y se usan en TypeScript para que a la hora del desarrollo evitemos lo más posible los errores que pueden salir en tiempo de ejecución y que quizás con JS normal puede que se nos pasen. Ahora bien estos tipos no afectan directamente a la hora de hacer la traspilación a JS puro.

* **jeisonsrz** (3) [415040](https://platzi.com/comentario/415040/) 

	código home.component.ts
	``` 
	    import { Component, OnInit } from '@angular/core';
	    
	    @Component({
	      selector: 'app-home',
	      templateUrl: './home.component.html',
	      styleUrls: ['./home.component.css']
	    })
	    export class HomeComponent implements OnInit {
	    
	      constructor() { 
	    
	        letc: number= 1 ;
	        letb: number =2;
	        lete: string='1';
	        letf: string = '2';
	        console.log(c+b);
	        console.log(e+f);
	    
	        letg: boolean= true;
	        leth: object = {};
	        console.log(g);
	        console.log(h);
	    
	        let i =[c,b,e,f,g,h];
	        console.log(i);
	    
	        letj: boolean []=[true,g]
	        console.log(j);
	    
	        letk: object[] = [{},h];
	        console.log(k);
	    
	        letl: any[]=[1,'string',h];
	        console.log(l);
	      }
	    
	      ngOnInit() {
	      }
	    
	    }
	    
	    
	```

* **Adrian Alberto Casas Lopez** (2) [962767](https://platzi.com/comentario/962767/) 

	let permite declarar variables limitando su alcance al bloque, declaración, o expresión donde se está usando y var define una variable global o local en una función sin importar el ámbito del bloque

* **jeduarz** (2) [707594](https://platzi.com/comentario/707594/) 

	Sería bueno que hayas aclarado antes del ejercicio que el símbolo + (más) sirve para concatenar variables del tipo string, similar a C++. Por eso Javascript da preferencia al valor “2” entre comillas ya que lo identifica como una cadena string versus cualquier valor adicional.
	
	Muy aparte de qué tan estricto sea Angular definiendo el tipado para cada variable que uno desee.

* **Nicolas Schimpf** (2) [445776](https://platzi.com/comentario/445776/) 

	aoe es por Age of Empires? ❤️

* **juanbarcinilla** (1) [638652](https://platzi.com/comentario/638652/) 

	En el caso cuando se declaro la variable
	``` 
	    let l: any [] =[1, 'aoe', {},[]] 
	    
	```
	
	seria lo mismo si le quito el tipo de dato any.

	* **Diego Ortiz** [638652] (1)

		No sería lo mismo, obtendrías un erros que dice:  
		`Type '[number, string, {}, undefined[]]' is not assignable to type '[]'.`  
		Lo que buscas se podría lograr usando los genéricos de Typescript, de cualquier forma tener el tipo `any` es algo mal visto en Angular/TS, porque no estarías haciendo nada, en tu caso lo correcto sería definir un tipo `[number, string, {}, []]` o crear una **interface **con esa estructura.

* **juanbarcinilla** (1) [638650](https://platzi.com/comentario/638650/) 

	Que diferencia hay entre var y let?

	* **Diego Alexander Forero Higuera (Platzi)** [638650] (9)

		Hola, la principal diferencia es que var no tiene un scope definido mientras que let si.
		
		Por ejemplo si defines una variable usando var dentro de una función esta variable puede ser accedida incluso fuera de la función, pero si defines la variable usando let esta variable solo se puede usar dentro de esa función.

	* **Adrian Alberto Casas Lopez** [638650] (1)

		let permite declarar variables limitando su alcance al bloque, declaración, o expresión donde se está usando y var define una variable global o local en una función sin importar el ámbito del bloque

* **Brayan Mamani** (1) [560898](https://platzi.com/comentario/560898/) 

	Una excelente clase para conocer TypeScript y ver las ventajas que tiene con respecto a JavaScript.

* **Cristian Daniel Palta Cabezas** (1) [546453](https://platzi.com/comentario/546453/) 

	Buenas clases

* **Alex Eugenio Gavidia Donayre** (1) [536073](https://platzi.com/comentario/536073/) 
Gracias

* **Alex Eugenio Gavidia Donayre** (1) [536067](https://platzi.com/comentario/536067/) 
Excelente clase

* **Gabriel Solorzano** (1) [530161](https://platzi.com/comentario/530161/) 

	Ahí el prof. puso 2 impresiones así:  
	console.log(a);  
	console.log(a);
	
	Pero se puede poner así para aprovechar tiempo y espacio:
	``` 
	    console.log("imprimiendo varios objetos o variables", a, b);
	    
	```

	* **JoosCode** [530161] (5)

		o asi
		``` 
		    console.log(`imprimiendo varios objetos o variables${a} y ${b}`);
		    
		```
		
		mucho mas bonito

* **Norman Erick Estrada Vargas** (1) [528797](https://platzi.com/comentario/528797/) 

	buena clase !!!

* **alexjhv** (1) [479029](https://platzi.com/comentario/479029/) 

	no compila en windows 10 , si me puden ayudar

	* **David Flores** [479029] (1)

		Si tienes un error la consola donde estas corriendo el ng serve te dice cual es el error

* **Calebisma** (1) [435592](https://platzi.com/comentario/435592/) 

	muy bien detallada la clase

* **Cristian David Franco Garcia** (1) [431221](https://platzi.com/comentario/431221/) 

	Basic Types:
	
	  1. <https://www.typescriptlang.org/docs/handbook/basic-types.html>
	  2. <https://dzone.com/articles/what-are-the-basic-data-types-in-typescript>  
	2.<https://www.tutorialspoint.com/typescript/typescript_types.htm>
	
	

* **tono2** (1) [416084](https://platzi.com/comentario/416084/) 

	hola me sale en rojo las variables number o c ,  
	me dice que el comando let lo cambie por const  
	que puedo hacer??

	* **Dany Ladino** [416084] (1)

		yo las cambie a const y todo funciono bien.

	* **Kevin Lozoya Giner** [416084] (1)

		 **const** y **let** son propias de javascript.  
		Te marca esa sugerencia debido a tslint.json, que tendrá alguna regla que dice que se cambie a const las variables que no se cambian. Concretamente la regla `"prefer-const": true`

* **Carlos Uriel de Jesus Sánchez González** (1) [397242](https://platzi.com/comentario/397242/) 

	Muy buena explicación.

* **Alejandro Salazar** (1) [367826](https://platzi.com/comentario/367826/) 

	me gustaria saber, como funcionan las variables dentro de una respuestas http, que entiendo es un observable, ya que si le asigno el valor a la variable para luego usarla, este no se almacena en la variable (sin embargo si realizo console.log(variable) dentro de la respuesta si imprime el valor)

	* **Ezequiel-Fabbroni** [367826] (1)

		Al hacer una petición con los módulos http de Angular esperas que estos retornen un observable al que te puedes subscribir y obtener el valor que devuelve la petición, debes tener muy en cuenta de asignar tu variable al momento en el que el método “subscribe” se ejecuta.
		
		ejemplo :  
		// método que realiza la petición http, suelen  
		// por lo general estar dentro de un servicio
		
		configUrl = ‘assets/config.json’;  
		// la url puede ser local o una dirección a otro  
		// servidor
		
		getConfig() {  
		return this.http.get(this.configUrl);  
		}
		
		// suscripción dentro de tu componente  
		this.configService.getConfig()  
		.subscribe((data: Config) => this.config = {  
		// dentro de este método puedes realizar   
		// las asignaciones  
		heroesUrl: data[‘heroesUrl’],  
		textfile: data[‘textfile’]  
		});
		
		para mas info :  
		<https://angular.io/guide/http#httpclient>

* **VGY** (1) [49946](https://platzi.com/comentario/473834/) 
Hola, ¿Que diferencia hay entre asignarle un any a una variable y no asignarle nada?

	* **metta** [49946] (4)

		Hola, según el spec de typescript no hay diferencia:
		
		<https://github.com/Microsoft/TypeScript/blob/master/doc/spec.md#31-the-any-type>
		
		Pero creo que es buena ponerlo para legibilidad para los desarrolladores.

* **tono2** (1) [45140](https://platzi.com/comentario/416084/) 
hola me sale en rojo las variables number o c , me dice que el comando let lo cambie por const que puedo hacer??

	* **Dany Ladino** [45140] (1)

		yo las cambie a const y todo funciono bien.

* **VGY** (0) [473834](https://platzi.com/comentario/473834/) 

	Hola, ¿Que diferencia hay entre asignarle un any a una variable y no asignarle nada?

	* **metta** [473834] (4)

		Hola, según el spec de typescript no hay diferencia:
		
		<https://github.com/Microsoft/TypeScript/blob/master/doc/spec.md#31-the-any-type>
		
		Pero creo que es buena ponerlo para legibilidad para los desarrolladores.

## 0160. Qué son las interfaces de TypeScript y su implementación [12758](https://platzi.com/clases/1340-angular-avanzado/12758-que-son-e-implementando-interfaces-de-typescript16/)

### Descripción:


Los tipos de datos _Interfaces_ de TypScript, son muy parecidos a una clase, en la que se definen propiedades internas que pueden ser de cualquiera de los otros tipos. Estas propiedades internas pueden definirse como obligatorias u opcionales usando el símbolo “”?"". Las interfaces definen en cierto modo estructuras personalizadas de datos en las que lo principal es que al ser implementadas usando ciertas IDEs (como Webstorm), muestran mensajes de control y validación para asegurar el uso adecuado de dicha interface, en tiempo real durante el desarrollo.

La forma de declarar una interface se puede ver en el siguiente ejemplo:
``` 
    export interface User {
      nick: string,
      subnick?: string,
      age?: number,
      email: string,
      friend: boolean,
      uid: any
    }
    
```

### Comentarios:

* **carlosextra1** (8) [363702](https://platzi.com/comentario/363702/) 

	poder marcar un valor de un object de interface como opcional, con el signo ?
	``` 
	    //el subnick?: string; y age?:number; quedan como opcionales
	    exportinterface User{
	    	nick: string;
	    	subnick?: string;
	    	age?:number;
	    	email:string;
	    	friend:boolean;
	    	uid: any;
	    }
	    
	```

	* **Julio J Yépez** [363702] (3)

		Cuidado con esos ; al final de cada línea Carlos. Son comas ,

	* **carlosextra1** [363702] (2)

		Hola @jjyepez, en este caso si se puede usar el ; aun que sea un objeto

	* **Julio J Yépez** [363702] (1)

		… interesante.

* **juandelghans** (6) [651074](https://platzi.com/comentario/651074/) 

	Angular CLI te permite generar una interface con cualquiera de los siguientes comandos:
	``` 
	    ng generate interface interfaces/user
	    
	```
	``` 
	    ng g i interfaces/user
	    
	```
	``` 
	    ng g interface interfaces/user
	    
	```
	``` 
	    ng generate i interfaces/user
	    
	```

* **stalincaiche** (5) [503801](https://platzi.com/comentario/503801/) 

	Hola con angular cli también pueden crear las interfaces:
	``` 
	    ng generate interface interfaces/user
	    
	```
	
	Al colocar interfaces/ se crea dicho directorio dentro de app.

	* **Brayan Mamani** [503801] (1)

		Muy buen aporte para optimizar la creación de interfaces.

* **gbsojo** (4) [613042](https://platzi.com/comentario/613042/) 

	Excelente clase!!  
	también podemos hacer esto
	``` 
	    ng generate interface interfaces/user 
	    
	```

* **Jecsham Castillo** (3) [448861](https://platzi.com/comentario/448861/) 

	Curso básico de TypeScript + Curso Avanzado de Angular… tremendo pack 😎

* **alanlapierre** (3) [369762](https://platzi.com/comentario/369762/) 

	Los que venimos del mundo Java, muy frecuentemente terminamos usando clases para definir DTOs. No es mala la idea de usar interfaces y asignarle un objeto anónimo. Voy a adoptarlo en mis desarrollos 😃

* **Marcelino Hernández López** (3) [365260](https://platzi.com/comentario/365260/) 

	Me acostumbre a hacer uso de las class  
	para realizar los tipos de datos ya saben POO
	``` 
	    exportclassUser{
	    	nick: string;
	    	subnick: string = null;
	    	age: number = null;
	    	email: string;
	    	friend: boolean;
	    	uid: any;
	    }
	    
	```
	
	¿Que diferencia hay en usar interface en ts a una class?

	* **Nelson Eduardo Visbal Jensen** [365260] (7)

		Las clases se instancian, las interfaces no. Una interfaz es una plantilla de una clase, te indica que debe tener la clase que la implemente. Otra diferencia es que las clases permiten herencia, las interfaces no. EN POO (Programación orientada a objetos) las interfaces te dan la guía para crear la clase.

* **jeisonsrz** (2) [415056](https://platzi.com/comentario/415056/) 

	user.ts —>
	``` 
	    export interface User {
	        nick: string;
	        subnick?: string;
	        age?: number;
	        email: string;
	        friend: boolean;
	        uid: any;
	    }
	    
	    
	```
	
	home.component.ts
	``` 
	    import { Component, OnInit } from '@angular/core';
	    import {User} from '../interfaces/user';
	    
	    @Component({
	      selector: 'app-home',
	      templateUrl: './home.component.html',
	      styleUrls: ['./home.component.css']
	    })
	    export class HomeComponent implements OnInit {
	    
	      constructor() {
	      letmyUser: User = {
	        nick: 'Eduardo',
	        age: 22,
	        email: 'eduardo@hotmail.com',
	        friend: true,
	        uid: 1,
	      };
	      letusers: User[] = [myUser];
	      console.log(myUser);
	      }
	    
	      ngOnInit() {
	      }
	    
	    }
	    
	    
	```

* **Agencia Wihaus** (2) [371005](https://platzi.com/comentario/371005/) 

	por qué usar una interfaz y no crear una clase de tipo usuario? cuales serian los pros y contras?

	* **JDiaz0017** [371005] (7)

		Hola,  
		Si bien es cierto que ambas construcciones sirven para casos simialres, la respuesta depende más sobre cómo vayas a generar los datos.  
		Es habitual usar interfaces, desprovistas de inicialización y funcionalidad, ya que esas partes es común que sean delegadas en los servicios. A diferencia de las clases, que se tendrían que crear objetos como instancias de dichas clases con la palabra reservada “new”.  
		**IMPORTANTE:**
		
		* Una desventaja que veo de usar clases, es que los datos contenidos en los objetos no siempre se generan propiamente desde el código Frontend, ya que es habitual que dichos datos dependiendo del caso, los proporcione mediante llamadas HTTP (Ajax), en estos casos no habrá “new” o instanciación, sino que se usará Angular para solicitar al servidor algún dato (en formato JSON habitualmente), para tales casos, es necesario definir mediante interfaz el tipo dado.  
		Hay que tener en cuenta que también se puede usar una clase que implemente una interfaz dada, y esto demuestra la variedad y complejidad que pueden tener nuestros tipos (mezclar clases e interfaces).
		
		
		
		En síntesis, una clase se puede instanciar y podría contener cierta funcionalidad, una interfaz solo se definen los tipos y NO se instancia. Se implementa:
		``` 
		    export interface IUsuario {
		      nombre: String;
		      direccion: String;
		      creado: Date;
		    }
		    
		    // definición de un tipo Class que implementa una interfaz
		    export class CUsuario implements IUsuario {
		      creado: Date;
		      constructor(public nombre: string, public direccion: String) {
		        this.creado = newDate(Date.now());
		       }
		    }
		    
		```
		
		Espero haber aclarado un tanto el panorama compañero.  
		Saludos.

* **Agencia Wihaus** (2) [40961](https://platzi.com/comentario/371005/) 
por qué usar una interfaz y no crear una clase de tipo usuario? cuales serian los pros y contras?

	* **JDiaz0017** [40961] (7)

		Hola,  
		Si bien es cierto que ambas construcciones sirven para casos simialres, la respuesta depende más sobre cómo vayas a generar los datos.  
		Es habitual usar interfaces, desprovistas de inicialización y funcionalidad, ya que esas partes es común que sean delegadas en los servicios. A diferencia de las clases, que se tendrían que crear objetos como instancias de dichas clases con la palabra reservada “new”.  
		**IMPORTANTE:**
		
		* Una desventaja que veo de usar clases, es que los datos contenidos en los objetos no siempre se generan propiamente desde el código Frontend, ya que es habitual que dichos datos dependiendo del caso, los proporcione mediante llamadas HTTP (Ajax), en estos casos no habrá “new” o instanciación, sino que se usará Angular para solicitar al servidor algún dato (en formato JSON habitualmente), para tales casos, es necesario definir mediante interfaz el tipo dado.  
		Hay que tener en cuenta que también se puede usar una clase que implemente una interfaz dada, y esto demuestra la variedad y complejidad que pueden tener nuestros tipos (mezclar clases e interfaces).
		
		
		
		En síntesis, una clase se puede instanciar y podría contener cierta funcionalidad, una interfaz solo se definen los tipos y NO se instancia. Se implementa:
		``` 
		    export interface IUsuario {
		      nombre: String;
		      direccion: String;
		      creado: Date;
		    }
		    
		    // definición de un tipo Class que implementa una interfaz
		    export class CUsuario implements IUsuario {
		      creado: Date;
		      constructor(public nombre: string, public direccion: String) {
		        this.creado = newDate(Date.now());
		       }
		    }
		    
		```
		
		Espero haber aclarado un tanto el panorama compañero.  
		Saludos.

* **ehnbytes** (1) [1015590](https://platzi.com/comentario/1015590/) 

	Buena clase!

* **Ricardo.20** (1) [860514](https://platzi.com/comentario/860514/) 

	Las interfaces son como las clases que definen reglas. Cuando las interfaces se implementan en otras clases, las reglas definidas deben cumplirse. Las interfaces son muy útil cuando desarrollas librerías ya que cuando implementen los terceros obligas a que cumplan ciertas reglas.

* **ctr9120** (1) [700508](https://platzi.com/comentario/700508/) 

	por ahora, a la hora de separar las propiedades de mi interface, usé la “,” y la aplicación no me marca ningún error, estoy trabajando con la versión 8, quisiera saber si esto tiene alguna consecuencia
	``` 
	    export interface User{
	    nick: string,
	    subnick?: string,
	    age?: number,
	    email: string,
	    friend: boolean,
	    uid: any
	    }```
	    
	```

	* **Alfonso Navarro** [700508] (2)

		No te preocupes, q tanto **punto y coma** como colocar **coma** son aceptados en la declaración de la Interface.

* **rubianllanos** (1) [682811](https://platzi.com/comentario/682811/) 

	Siento como si estuviera escribiendo código en Kotlin, muy interesante el curso hasta ahora.

* **danielcarmonajaramillo** (1) [582525](https://platzi.com/comentario/582525/) 

	Qué tan recomendado es almacenar datos delicados como la contraseña?

	* **ebar0n (Platzi)** [582525] (2)

		Hola, no deberías guardar la contraseña, es muy sensible.
		
		Si necesitas mantener datos de acceso, puedes tener temporalmente un token, ya que eventualmente ese token expirará, que es como trabaja más o menos una cookie de session.

* **Cristian Daniel Palta Cabezas** (1) [546456](https://platzi.com/comentario/546456/) 

	buenas clases

* **Walter Lensinas** (1) [544797](https://platzi.com/comentario/544797/) 

	Buenas tardes, dejo el código de las clase en este repositorio <https://github.com/wlensinas/platzinger-wl.git>
	
	Para ver el código:
	
	  1. git clone <https://github.com/wlensinas/platzinger-wl.git>
	  2. git checkout 16-interfaces
	  3. npm install
	  4. ng serve --open
	
	
	
	Saludos.

* **Wilson Marino Pablo Mendez** (1) [536685](https://platzi.com/comentario/536685/) 

	Es como cuando defino mis campos en el gestor DB SQL

* **Erick Suarez Zavala** (1) [474780](https://platzi.com/comentario/474780/) 

	Solo como comentario, CLI de angular tambien te ayuda a generar interfaces, con:  
	ng generate interface nombreInterface

* **Cristian David Franco Garcia** (1) [431264](https://platzi.com/comentario/431264/) 

	ng generate interface interfaces/user 😉

* **IngWMC2018** (1) [430674](https://platzi.com/comentario/430674/) 

	He creado el archivo user.ts e implementado la interface User, pero al momento de guardar los cambios, en el terminal visualizo lo siguiente:  
	ERROR in Source file not found: ‘/Users/ingwmc/Desktop/Angular/platzinger/src/app/interfaces/user.ts’.  
	Porque no encuentra el Source?
	
	Gracias.

	* **ivandiaz** [430674] (1)

		puede ser que no encuentre el archivo o puede ser que nombraste mal la interface dentro del archivo user.ts

	* **David Flores** [430674] (1)

		Algunas veces el CLI se queda trabado y no reconoce los cambios, te recomiendo parar el servidor con Ctrl + C (en windows) y volver a ejecutar el servidor con:
		``` 
		    ng serve -o
		    
		```

* **Carlos Uriel de Jesus Sánchez González** (1) [397272](https://platzi.com/comentario/397272/) 

	export interface User {  
	nick: string;  
	subnick: string;  
	age: number;  
	email: string;  
	friend: boolean;  
	uid: any;  
	}

* **Carlos Uriel de Jesus Sánchez González** (1) [397254](https://platzi.com/comentario/397254/) 

	```
	    export interface User {
	      nick: string,
	      subnick?: string,
	      age?: number,
	      email: string,
	      friend: boolean,
	      uid: any
	    }
	    
	```

* **Gualberto Cuiza Villca** (1) [393033](https://platzi.com/comentario/393033/) 

	Al parecer se comporta y es igual que un modelo, que diferencias hay?

	* **Juan Carlos Pinzón** [393033] (2)

		De hecho en varios sitios he visto que los nombran así: **Modelos**

* **Duilio Luque** (1) [372022](https://platzi.com/comentario/372022/) 
Qué tipo de dato usa angular para archivos con Excel, PDF o txt?

	* **Juan Carlos Pinzón** [372022] (1)

		Hola compañero, Angular no maneja ese tipo de archivo. Lo que se muestra en esta clase y la anterior son los tipos de Datos, tipos de variables. A lo que te refieres son tipos de archivos creo, pero Angular no maneja archivos lo más cercano es cuando se hace un Upload, pero es algo un poco abstracto que solo nos preocupamos de mandar a un API. Claro que podemos validar que tipo es el archivo pero no manejarlo como tal.

* **carlosextra1** (1) [363700](https://platzi.com/comentario/363700/) 

	poder marcar un valor de un object de interface como opcional, con el ? //el subnick?: string; y age?:number; quedan como opcionales export interface User{ nick: string; subnick?: string; age?:number; email:string; friend:boolean; uid: any; }

* **IngWMC2018** (1) [46383](https://platzi.com/comentario/430674/) 
He creado el archivo user.ts e implementado la interface User, pero al momento de guardar los cambios, en el terminal visualizo lo siguie...

	* **ivandiaz** [46383] (1)

		puede ser que no encuentre el archivo o puede ser que nombraste mal la interface dentro del archivo user.ts

* **Marcelino Hernández López** (1) [40440](https://platzi.com/comentario/365260/) 
Me acostumbre a hacer uso de las class para realizar los tipos de datos ya saben POO export class User { nick: string; subnick: s...

	* **Nelson Eduardo Visbal Jensen** [40440] (7)

		Las clases se instancian, las interfaces no. Una interfaz es una plantilla de una clase, te indica que debe tener la clase que la implemente. Otra diferencia es que las clases permiten herencia, las interfaces no. EN POO (Programación orientada a objetos) las interfaces te dan la guía para crear la clase.

## 0170. NgFor aplicado en la lista de usuarios [12759](https://platzi.com/clases/1340-angular-avanzado/12759-ngfor-aplicado-en-la-lista-de-usuarios7514/)

### Descripción:


NgFor es una directiva estructural que afecta (agrega, modifica o elimina) un elemento HTML. Las directivas estructurales las identificamos porque llevan un * antes de la directiva, por ejemplo: *ngFor

NgFor nos permite recorrer un arreglo de datos y por cada elemento generar o imprimir en el DOM un elemento HTML nuevo, con algún valor cambiado basado en el elemento leído del arreglo.

### Comentarios:

* **Anthony Gonzalez** (31) [376421](https://platzi.com/comentario/376421/) 

	Usuarios extras:
	``` 
	    letusuario1: User = {
	          nick: 'Eduardo',
	          age: 24,
	          email: 'ed@aoe.aoe',
	          friend: true,
	          uid: 1
	        };
	        letusuario2: User = {
	          nick: 'Freddy',
	          age: 28,
	          email: 'fred@aoe.aoe',
	          friend: true,
	          uid: 1
	        };
	        letusuario3: User = {
	          nick: 'Yuliana',
	          age: 18,
	          email: 'yuli@aoe.aoe',
	          friend: true,
	          uid: 1
	        };
	        letusuario4: User = {
	          nick: 'Ricardo',
	          age: 17,
	          email: 'rick@aoe.aoe',
	          friend: false,
	          uid: 1
	        };
	        letusuario5: User = {
	          nick: 'Marcos',
	          age: 30,
	          email:'marcos@aoe.aoe',
	          friend: false,
	          uid: 1
	        };
	    
	```

	* **Mariano Villarreal** [376421] (8)

		Capa sin heroe

	* **mario-salinas** [376421] (1)

		Perfecto, pueden cambiar de una vez los uid ya que aquí solo les pone 1 y mas adelante se necesita que cada elemento tenga id’s diferentes

	* **francves17** [376421] (1)

		Denle una cerveza!

	* **Cristian Daniel Palta Cabezas** [376421] (1)

		excelente ejemplo amigo. Gracias

	* **AlejandroBenitezCorp** [376421] (1)

		Muchas gracias por el aporte!

	* **Brayan Mamani** [376421] (1)

		Genial !!

* **Jhon Castrillon** (7) [537758](https://platzi.com/comentario/537758/) 

	Id Diferentes
	
	let usuario1: User = {  
	nick: ‘Eduardo’,  
	age: 24,  
	email: ‘ed@aoe.aoe’,  
	friend: true,  
	uid: 1  
	};  
	let usuario2: User = {  
	nick: ‘Freddy’,  
	age: 28,  
	email: ‘fred@aoe.aoe’,  
	friend: true,  
	uid: 2  
	};  
	let usuario3: User = {  
	nick: ‘Yuliana’,  
	age: 18,  
	email: ‘yuli@aoe.aoe’,  
	friend: true,  
	uid: 3  
	};  
	let usuario4: User = {  
	nick: ‘Ricardo’,  
	age: 17,  
	email: ‘rick@aoe.aoe’,  
	friend: false,  
	uid: 4  
	};  
	let usuario5: User = {  
	nick: ‘Marcos’,  
	age: 30,  
	email:‘marcos@aoe.aoe’,  
	friend: false,  
	uid: 5  
	};

	* **Alfonso Navarro** [537758] (2)

		Gracias compañero por tu aporte

* **Luis Miguel Ramos Hernández** (6) [458422](https://platzi.com/comentario/458422/) 

	Para no imprimir el index podría utilizarse una lista que lo genere por defecto
	``` 
	    <ol>
	      <li *ngFor="let friend of friends">
	        {{friend.nick}} - {{friend.email}}
	      </li>
	    </ol>
	    
	```

	* **Brayan Mamani** [458422] (1)

		Muy buena recomendación.

* **jeisonsrz** (6) [415080](https://platzi.com/comentario/415080/) 

	home.component.html---->
	``` 
	    <p *ngFor="let user of friends; let i = index">
	     {{i}}. {{user.nick}} - {{user.email}}
	    </p>
	    
	    
	```
	
	home.component.ts —>
	``` 
	    import { Component, OnInit } from '@angular/core';
	    import {User} from '../interfaces/user';
	    
	    @Component({
	      selector: 'app-home',
	      templateUrl: './home.component.html',
	      styleUrls: ['./home.component.css']
	    })
	    export class HomeComponent implements OnInit {
	    
	      friends: User[];
	      constructor() {
	        letusuario1: User = {
	          nick: 'Eduardo',
	          age: 24,
	          email: 'ed@aoe.aoe',
	          friend: true,
	          uid: 1
	        };
	        letusuario2: User = {
	          nick: 'Freddy',
	          age: 28,
	          email: 'fred@aoe.aoe',
	          friend: true,
	          uid: 1
	        };
	        letusuario3: User = {
	          nick: 'Yuliana',
	          age: 18,
	          email: 'yuli@aoe.aoe',
	          friend: true,
	          uid: 1
	        };
	        letusuario4: User = {
	          nick: 'Ricardo',
	          age: 17,
	          email: 'rick@aoe.aoe',
	          friend: false,
	          uid: 1
	        };
	        letusuario5: User = {
	          nick: 'Marcos',
	          age: 30,
	          email:'marcos@aoe.aoe',
	          friend: false,
	          uid: 1
	        };
	        this.friends = [usuario1,usuario2,usuario3,usuario4,usuario5];
	      }
	    
	      ngOnInit() {
	      }
	    
	    }
	    
	    
	```

* **Diego Ortiz** (5) [707348](https://platzi.com/comentario/707348/) 

	Una sintaxis alterna para el `let i = index` es `index as i`.  
	Es un poco más corta, y me parece más fácil.

	* **Joiss Ventura Rivera** [707348] (1)

		Muy buen aporte.

* **Gonzalo Muñoz** (4) [678144](https://platzi.com/comentario/678144/) 

	No olvidar el método push para agregar campos a los arrays:
	
	`this.friends.push(user1, user2, user3, user4, user5);`

* **formacionadv3** (3) [760083](https://platzi.com/comentario/760083/) 

	todo en ingles, pero cuando hay que decir ‘array’ dice ‘arreglo’

	* **aerama** [760083] (2)

		el buen spanglish haciendose presente jajaja

* **Carlos Uriel de Jesus Sánchez González** (3) [397294](https://platzi.com/comentario/397294/) 

	home.component.ts
	``` 
	    import { Component, OnInit } from '@angular/core';
	    import { User } from '../interfaces/user';
	    
	    @Component({
	      selector: 'app-home',
	      templateUrl: './home.component.html',
	      styleUrls: ['./home.component.css']
	    })
	    export class HomeComponent implements OnInit {
	    
	      friends: User[];
	      constructor() {
	        /*let c: number = 1;
	        let b: number = 2;
	        console.log(c + b);
	        let e: string = '1';
	        let f: string = '2';
	        console.log(e + f);
	        let g: boolean = true;
	        let h: object = {};
	        console.log(g);
	        console.log(h);
	        let i = [c, b, e, f, g, h];
	        console.log(i);
	        let j: boolean [] = [true, g];
	        console.log(j);
	        let l: object [] = [{}, h];
	        console.log(l);
	        let k: any [] = [1, 'qwe', {}, [], true];
	        console.log(k);
	        let myuser: User = {
	          nick: 'Uriel',
	          // subnick: 'Uriel',
	          age: 36,
	          email: 'a@a.com',
	          friend: true,
	          uid: 1
	        };
	        console.log(myuser);
	        let users: User[] = [
	          myuser
	        ];
	        console.log(users);*/
	    
	        letusuario1: User = {
	          nick: 'Eduardo',
	          age: 24,
	          email: 'ed@aoe.aoe',
	          friend: true,
	          uid: 1
	        };
	        letusuario2: User = {
	          nick: 'Freddy',
	          age: 28,
	          email: 'fred@aoe.aoe',
	          friend: true,
	          uid: 1
	        };
	        letusuario3: User = {
	          nick: 'Yuliana',
	          age: 18,
	          email: 'yuli@aoe.aoe',
	          friend: true,
	          uid: 1
	        };
	        letusuario4: User = {
	          nick: 'Ricardo',
	          age: 17,
	          email: 'rick@aoe.aoe',
	          friend: false,
	          uid: 1
	        };
	        letusuario5: User = {
	          nick: 'Marcos',
	          age: 30,
	          email: 'marcos@aoe.aoe',
	          friend: false,
	          uid: 1
	        };
	        this.friends = [usuario1, usuario2, usuario3, usuario4, usuario5];
	    
	      }
	    
	      ngOnInit() {
	      }
	    
	    }
	    
	    
	```
	
	home.component.html
	``` 
	    <p *ngFor="let user of friends; let i = index" >
	      {{i + 1}}. {{user.nick}} - {{user.email}}
	    </p>
	    
	```

* **Jecsham Castillo** (2) [448871](https://platzi.com/comentario/448871/) 

	Pueden omitir el 0 escribiendo en la variable del template `{{i + 1}}`

* **Rafael Aguilar** (2) [66124](https://platzi.com/comentario/703313/) 
Donde descargo el interface de los usaurios?

	* **pruebadate** [66124] (0)

		No se descarga, lo haces tu manualmente, de igual manera lo puedes copiar de los archivos del proyecto en: src/app/interfaces/user.ts

* **Joiss Ventura Rivera** (1) [1014132](https://platzi.com/comentario/1014132/) 

	Les muestro otra forma de realizar lo que el profe realizó en la clase.  
	Espero sea de ayuda. Cualquier duda estaré atento consulten fast :3
	
	![imagen.png](https://static.platzi.com/media/user_upload/imagen-73052c1c-070e-4a76-90ec-df4c17287cd0.jpg)

* **franciscolesm22226d48ae644859** (1) [659666](https://platzi.com/comentario/659666/) 

	Donde Se encuentra el sistema de Archivos?

	* **Diego Alexander Forero Higuera (Platzi)** [659666] (1)

		Se encuentra en la columna derecha en la clase, en la pestaña más a la derecha.
		
		![Screenshot_20190721_195714.png](https://static.platzi.com/media/user_upload/Screenshot_20190721_195714-9699ba7c-719e-4958-8b20-9d489f6afd38.jpg)
		
		Puedes ver que hay 4 pestañas, Aportes, Preguntas, Marcadores, **Archivos y Enlaces**

	* **franciscolesm22226d48ae644859** [659666] (1)

		Muchas Gracias por la respuesta efectivamente los encontré, Gracias

* **cristiancanon** (1) [647594](https://platzi.com/comentario/647594/) 

	no me funciona!
	
	![Captura de pantalla \(189\).png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%28189%29-9253e5b0-c09d-4552-9dd9-4b28f085baf3.jpg) ![Captura de pantalla \(190\).png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%28190%29-20ca793e-71bf-4ae5-82ca-ce55d23dcf70.jpg)

	* **Daniel_731** [647594] (2)

		Debes encerrar el indice en doble llave {{ i }}

	* **diferotorres** [647594] (1)

		{{user.nick}} - {{user.email}}, el nick lo tienes como Use.nick

	* **leo-amato** [647594] (1)

		pudiste encontrar la solucion?

* **Cristian Daniel Palta Cabezas** (1) [546461](https://platzi.com/comentario/546461/) 

	buenas clases

* **Walter Lensinas** (1) [544830](https://platzi.com/comentario/544830/) 

	Buenas tardes, dejo el código de las clase en este repositorio <https://github.com/wlensinas/platzinger-wl.git>
	
	Para ver el código:
	
	  1. `git clone https://github.com/wlensinas/platzinger-wl.git`
	  2. `git checkout 17-ngfor`
	  3. `npm install`
	  4. `ng serve --open`
	
	
	
	Saludos.

* **Manuel Esteban Rodríguez Gómez** (0) [65793](https://platzi.com/comentario/697899/) 
Vscode al escribir en el home.component el codigo {{user.nick}} - {{user.age}} concretamente al escribir user. no me da ninguna posible ...

	* **David Flores** [65793] (1)

		Es por que le faltan extensiones a tu vsc, te dejo un link de unas extensiones chidas:  
		[Extensiones chidas](https://programmingwithmosh.com/angular/essential-vscode-extensions-for-angular-developers/)

## 0180. NgIf aplicado en la lista de usuarios [12760](https://platzi.com/clases/1340-angular-avanzado/12760-ngif-aplicado-en-la-lista-de-usuarios7102/)

### Descripción:


NgIF es una directiva estructural de Angular que evalúa un valor o una expresión buleana, en función de la cual se mostrará o no, un elemento HTML. El elemento se mostrará sólo cuando la condición sea verdadera (true).

### Comentarios:

* **carlosextra1** (9) [363715](https://platzi.com/comentario/363715/) 

	 **ng-container** es una etiqueta auxiliar que se usa para correr un **ngFor **con **ngIf **anidados.
	``` 
	    <ol>
	    <ng-container *ngFor="let user of usuarios">
	    <li *ngIf="true">
	    	{{user.nick}}{{user.email}}
	    </li>
	    </ng-container>
	    </ol>```
	    
	```

* **Alex Eugenio Gavidia Donayre** (3) [536454](https://platzi.com/comentario/536454/) 
El ejemplo hubiese quedado mejor si mostrabas la. Lista de conectados y no conectados. Saludos desde Perú 🤣

* **Dani Desna** (3) [471514](https://platzi.com/comentario/471514/) 

	Se supone que es un _Curso avanzado de Angular_. ¿Por que estamos repasando ng-if y ng-for? 😕

	* **Brayan Mamani** [471514] (1)

		Para que recordemos y reforcemos.

* **neiluli** (2) [474972](https://platzi.com/comentario/474972/) 

	Tambien vi que se puede utilizar ng-if-else y ng-if-then-else el primero tengo idea de como utilizarlo me gustaria saber para que es el otro y como implementarlo.  
	Saludos 😄

* **Jesús Auriol Villamarín Ortiz** (2) [453958](https://platzi.com/comentario/453958/) 

	 **Mi lista de amigos conectados y no conectados**
	
	![Imagen](https://ibb.co/0rSr2Hy)  
	**home.component.html **
	``` 
	    <ng-container *ngFor="let user of users; let i = index">
	      <li>
	        <p>
	          <strong>{{ i + 1 }}</strong> . {{ user.nick }} - {{ user.age }} -
	          <strong>{{ user.email }}</strong>
	        </p>
	        <divclass="status" [ngStyle]="{'background-color': user.status ? '#25ef4e' : '#ef2630'}"></div>
	      </li>
	    </ng-container>
	    
	    
	```
	
	**home.component.css**
	``` 
	    li{
	      list-style: none;
	      margin: 0;
	      height: 6px;;
	    }
	    
	    .status{
	      margin: 0;
	      padding: 0;
	      position: relative;
	      bottom: 30px;
	      left: 320px;
	      height: 10px;
	      width: 10px;
	      border-radius: 100%;
	    
	    }
	    
	```
	
	**home.component.ts**
	``` 
	    import { User } from './../models/user';
	    import { Component, OnInit } from '@angular/core';
	    
	    @Component({
	      selector: 'app-home',
	      templateUrl: './home.component.html',
	      styleUrls: ['./home.component.scss']
	    })
	    export class HomeComponent implements OnInit {
	      users: User[];
	    
	      constructor() {
	        letuser1: User = {
	          nick: 'Jesús',
	          subnick: 'Ragnar',
	          age: 21,
	          email: 'jvillamarin@outlook.com',
	          status: true,
	          uid: 1
	        };
	        letuser2: User = {
	          nick: 'Lali',
	          subnick: 'Rapis',
	          age: 16,
	          email: 'Lali@outlook.com',
	          status: false,
	          uid: 1
	        };
	        letuser3: User = {
	          nick: 'Sara',
	          subnick: 'Sara',
	          age: 57,
	          email: 'Sara@outlook.com',
	          status: true,
	          uid: 3
	        };
	        letuser4: User = {
	          nick: 'Humberto',
	          subnick: 'Mechas',
	          age: 32,
	          email: 'humberto@outlook.com',
	          status: true,
	          uid: 2
	        };
	    
	        this.users = [user1, user2, user3, user4];
	      }
	    
	      ngOnInit() {
	    
	      }
	    
	    }
	    
	```

	* **Jesús Auriol Villamarín Ortiz** [453958] (1)

		Aún no se como subir imagen xd ![imagen](https://i.ibb.co/jD2Dfnk/Sin-t-tulo.png)

	* **Jesús Auriol Villamarín Ortiz** [453958] (1)

		Alguien tiene otro método o alguien que lo pueda simplificar?

* **Jecsham Castillo** (2) [448878](https://platzi.com/comentario/448878/) 

	Una manera óptima sería correr el array de friends en el mismo module.ts y asignar a los trues y falses en arrays distintas

* **carlos Alberto Bedoya Ramirez** (2) [394392](https://platzi.com/comentario/394392/) 

	No entiendo por que los archivos adjuntos al curso son distintos al que muestran en el video :S

* **Anthony Gonzalez** (2) [376452](https://platzi.com/comentario/376452/) 

	No es posible utilizar dos **directivas estructurales** en un solo elemento, para estos casos Angular nos ofrece la etiqueta html **ng-container**

* **alanfermin** (1) [931718](https://platzi.com/comentario/931718/) 

	Saludos,
	
	Una consulta. Porqué usa la etiqueta <b> en vez de <p> para “amigos” y “No agregados”

	* **basanchez** [931718] (1)

		Es una etiqueta para poner en negrita el texto. La `<b>` es por bold.

* **marioamaciasortiz** (1) [831098](https://platzi.com/comentario/831098/) 

	sino utilizares ng-container podrias utilizar <p> anidados?

	* **eric-alejandro-asce** [831098] (1)

		No seria correcto ya que al compilar el html te arrojaría error

* **Marco Flores** (1) [679818](https://platzi.com/comentario/679818/) 

	Una pregunta, tengo entendido que con el ngIf ademas de eliminar unelemento del DOM este en caso de tener un tag de angular lo destruiria y volveria a construir. Mi pregunta seria como actuaria en el caso del ngSwitch este tendria el mismo comportamiento?

* **gazz9ar** (1) [671134](https://platzi.com/comentario/671134/) 

	Hola gente tengo una duda, que extension deberia instalar para que al escribir user. me salte el friends?

	* **David Flores** [671134] (3)

		[Extension para autocompletar](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)

* **cristiancanon** (1) [647632](https://platzi.com/comentario/647632/) 

	No me aparece nada, tengo un problema desde la seccion anterior  
	![Captura de pantalla \(191\).png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%28191%29-2a8777af-3c8b-47d7-8abd-eaa4f2423da1.jpg)

	* **Daniel_731** [647632] (3)

		Quita el primer *ngFor

	* **leo-amato** [647632] (1)

		pudiste solucionarlo?, me toma todo parte desde *ngFor como un string y no se como cambiar eso.

* **Brayan Mamani** (1) [560970](https://platzi.com/comentario/560970/) 

	```
	    <br/>
	    <b>Amigos</b>  
	    <ng-container *ngFor="let user of friends; let i = index">
	      <p  *ngIf="user.friend">
	            {{i}}. {{user.nick}} - {{user.email}}
	      </p>
	    </ng-container>
	    
	    <b>No agregados</b> 
	    <ng-container *ngFor="let user of friends; let i = index"> 
	        <p  *ngIf="!user.friend">
	        {{i}}. {{user.nick}} - {{user.email}}
	        </p>
	    </ng-container>
	    
	```

* **Walter Lensinas** (1) [545006](https://platzi.com/comentario/545006/) 

	Buenas tardes, dejo el código de las clase en este repositorio <https://github.com/wlensinas/platzinger-wl.git>
	
	Para ver el código:
	
	  1. `git clone https://github.com/wlensinas/platzinger-wl.git`
	  2. `git checkout 18-ngif`
	  3. `npm install`
	  4. `ng serve --open`
	
	
	
	Saludos.

* **luisangeldev** (1) [500740](https://platzi.com/comentario/500740/) 

	 **ng-container**  
	Esta directiva de angular no es visible para el usuario en el front-end y nos permite declarar más de una directiva anidadas dentro de dicho elemento. Permitiendo así combinar funcionalidades de directivas.

* **jeisonsrz** (1) [415086](https://platzi.com/comentario/415086/) 

	home.component.html ----->
	``` 
	    <br/>
	    <br/>
	    <b>Amigos</b>
	    <ng-container *ngFor="let user of friends; let i = index">
	    
	      <p *ngIf="user.friend" >
	        {{i}}. {{user.nick}} - {{user.email}}
	      </p>
	    
	    </ng-container>
	    
	    <b>No Agregadoss</b>
	    <ng-container *ngFor="let user of friends; let i = index">
	    
	      <p *ngIf="!user.friend" >
	        {{i}}. {{user.nick}} - {{user.email}}
	      </p>
	    
	    
	    </ng-container>
	    
	    
	```
	
	home.component.ts ---->
	``` 
	    import { Component, OnInit } from '@angular/core';
	    import {User} from '../interfaces/user';
	    
	    @Component({
	      selector: 'app-home',
	      templateUrl: './home.component.html',
	      styleUrls: ['./home.component.css']
	    })
	    export class HomeComponent implements OnInit {
	    
	      friends: User[];
	      constructor() {
	        letusuario1: User = {
	          nick: 'Eduardo',
	          age: 24,
	          email: 'ed@aoe.aoe',
	          friend: true,
	          uid: 1
	        };
	        letusuario2: User = {
	          nick: 'Freddy',
	          age: 28,
	          email: 'fred@aoe.aoe',
	          friend: true,
	          uid: 1
	        };
	        letusuario3: User = {
	          nick: 'Yuliana',
	          age: 18,
	          email: 'yuli@aoe.aoe',
	          friend: true,
	          uid: 1
	        };
	        letusuario4: User = {
	          nick: 'Ricardo',
	          age: 17,
	          email: 'rick@aoe.aoe',
	          friend: false,
	          uid: 1
	        };
	        letusuario5: User = {
	          nick: 'Marcos',
	          age: 30,
	          email:'marcos@aoe.aoe',
	          friend: false,
	          uid: 1
	        };
	        this.friends = [usuario1, usuario2, usuario3, usuario4, usuario5];
	      }
	    
	      ngOnInit() {
	      }
	    
	    }
	    
	    
	```

* **JuanCZ** (1) [406796](https://platzi.com/comentario/406796/) 

	```
	    <ng-container *ngFor="let user of friends; let i = index">
	          <p *ngIf="user.friend==true">
	            {{i+1}} Mi nombre es {{user.nick}} y tengo {{user.age}} años
	          </p>
	      </ng-container>
	    
	```

* **Carlos Uriel de Jesus Sánchez González** (1) [397309](https://platzi.com/comentario/397309/) 

	```
	    <br/>
	    <b>Amigos</b>
	    <ng-container *ngFor="let user of friends; let i = index">
	      <p *ngIf="user.friend">
	        {{i + 1}}. {{user.nick}} - {{user.email}}
	      </p>
	    </ng-container>
	    
	    No agregados
	    <ng-container *ngFor="let user of friends; let i = index">
	      <p *ngIf="!user.friend">
	        {{i + 1}}. {{user.nick}} - {{user.email}}
	      </p>
	    </ng-container>
	    
	```

## 0190. Navegación con parámetros [12762](https://platzi.com/clases/1340-angular-avanzado/12762-navegacion-con-parametros0729/)

### Descripción:


Al navegar entre pantallas, hay ocasiones en las que es necesario pasar datos particulares. Usando routerLink podemos incluir parámetros de manera similar a como lo hacemos con subdominios o subdirectorios. Para recibir e interpretar estos parámetros correctamente es necesario definir las rutas específicas en appRoutes y consultarlos luego en el componente con el objeto ActivatedRoute.

### Comentarios:

* **carlosextra1** (6) [365954](https://platzi.com/comentario/365954/) 

	convesation.component.ts 27/08/2018
	``` 
	    import { Component, OnInit } from '@angular/core';
	    import { ActivatedRoute } from "@angular/router";
	    
	    @Component({
	      selector: 'app-conversation',
	      templateUrl: './conversation.component.html',
	      styleUrls: ['./conversation.component.css']
	    })
	    export class ConversationComponent implements OnInit {
	    	freindId: any;
	      constructor(private activatedRoute: ActivatedRoute) {
	      	this.freindId = this.activatedRoute.snapshot.params['uid'];
	      }
	    
	      ngOnInit() {
	      }
	    
	    }```
	    
	```

* **Alex Eugenio Gavidia Donayre** (3) [536460](https://platzi.com/comentario/536460/) 
Enseña todos los detalles para poder enter el framework

* **Adrian Alberto Casas Lopez** (2) [965604](https://platzi.com/comentario/965604/) 

	En angular 8 marca un warning al querer ingresar de esta manera al parampetro:
	``` 
	    this.activatedRoute.snapshot.params['uid'];
	    
	```
	
	pero funciona, también se puede de la siguiente manera:
	``` 
	    this.activatedRoute.snapshot.params.uid;
	    
	```

* **Alex Eugenio Gavidia Donayre** (2) [536459](https://platzi.com/comentario/536459/) 
Excelente curso

* **marioamaciasortiz** (1) [832601](https://platzi.com/comentario/832601/) 

	Como traer varios parametros?

	* **basanchez** [832601] (1)

		Siguendo ese mismo escenario tu tendrías que tener una ruta mas o menos de este estilo:  
		`conversation/:uid/:param2/:param3`
		
		Para obtenerlo es lo mismo
		``` 
		    this.param2 = this.activatedRoute.snapshot.params.param2;
		    this.param3 = this.activatedRoute.snapshot.params.param3;
		    
		```

* **Ariel Virgilio Solano Gonzalez** (1) [613322](https://platzi.com/comentario/613322/) 

	No entiendo cuando dice que tenemos que recuperar el uid del url

	* **charlieg** [613322] (1)

		Proviene de la ruta de navegación. Por ejemplo
		
		localhost:4200/conversation/123
		
		En este caso, el parámetro que estás obteniendo es **123** , esto sucede por cómo se configuró la ruta en **app.module.ts**.
		``` 
		    {path: 'conversation/:uid', component: ConversationComponent}
		    
		```

* **Walter Lensinas** (1) [545043](https://platzi.com/comentario/545043/) 

	Buenas tardes, dejo el código de las clase en este repositorio <https://github.com/wlensinas/platzinger-wl.git>
	
	Para ver el código:
	
	  1. `git clone https://github.com/wlensinas/platzinger-wl.git`
	  2. `git checkout 19-navigate`
	  3. `npm install`
	  4. `ng serve --open`
	
	
	
	Saludos.

* **RomarioEstradaFlorez** (1) [507606](https://platzi.com/comentario/507606/) 

	Está como larguito coger el id pero esta muy chevere!

	* **Alex Eugenio Gavidia Donayre** [507606] (1)
Si te parece largo esas pequeñas líneas. Que sobre todo en muchos lenguajes es de una manera similar.

	* **Alex Eugenio Gavidia Donayre** [507606] (1)
Estas perdido xd

* **dcortesnet** (1) [503577](https://platzi.com/comentario/503577/) 

	muy buen curso, he entendido todo!

* **jeisonsrz** (1) [415095](https://platzi.com/comentario/415095/) 

	conversation.component.ts ---->
	``` 
	    import { Component, OnInit } from '@angular/core';
	    import {ActivatedRoute} from '@angular/router';
	    
	    @Component({
	      selector: 'app-conversation',
	      templateUrl: './conversation.component.html',
	      styleUrls: ['./conversation.component.css']
	    })
	    export class ConversationComponent implements OnInit {
	    
	      friendId: any;
	      constructor(private activatedRoute: ActivatedRoute) {
	        this.friendId = this.activatedRoute.snapshot.params['uid'];
	        console.log(this.friendId);
	      }
	    
	      ngOnInit() {
	      }
	    
	    }
	    
	    
	```
	
	app.modules.ts —>
	``` 
	    constappRoutes: Routes = [
	      {path: '', component: HomeComponent},
	      {path: 'home', component: HomeComponent},
	      {path: 'login', component: LoginComponent},
	      {path: 'conversation/:uid', component: ConversationComponent},
	      {path: 'profile', component: ProfileComponent},
	    ];
	    
	```
	
	home.component.html ---->
	``` 
	    <br/>
	    <br/>
	    <b>Amigos</b>
	    <ng-container *ngFor="let user of friends; let i = index">
	    
	      <div *ngIf="user.friend">
	        <arouterLink="/conversation/{{user.uid}}" >
	          {{i}}. {{user.nick}} - {{user.email}}
	        </a>
	    
	      </div>
	    
	    </ng-container>
	    
	    <b>No Agregadoss</b>
	    <ng-container *ngFor="let user of friends; let i = index">
	    
	      <div *ngIf="!user.friend">
	        <arouterLink="/conversation/{{user.uid}}" >
	          {{i}}. {{user.nick}} - {{user.email}}
	        </a>
	      </div>
	    
	    
	    
	    </ng-container>
	    
	    
	    
	    
	```

* **Carlos Uriel de Jesus Sánchez González** (1) [397819](https://platzi.com/comentario/397819/) 

	conversation.component.ts
	``` 
	    import { Component, OnInit } from '@angular/core';
	    import {ActivatedRoute} from '@angular/router';
	    
	    @Component({
	      selector: 'app-conversation',
	      templateUrl: './conversation.component.html',
	      styleUrls: ['./conversation.component.css']
	    })
	    export class ConversationComponent implements OnInit {
	      friendId: any;
	      constructor(private activatedRoute: ActivatedRoute) {
	        this.friendId = this.activatedRoute.snapshot.params['uid'];
	        console.log(this.friendId);
	      }
	    
	      ngOnInit() {
	      }
	    
	    }
	    
	```

* **Damaris Quiroz** (1) [383275](https://platzi.com/comentario/383275/) 

	En todo esto no me queda muy claro para qque funciona el snapshot.params

	* **Juan Carlos Felizzola Vega** [383275] (4)

		Si imprimes solo `this.activatedRoute` te darás cuenta que es un objeto que trae muchas cosas.  
		Con
		``` 
		    this.activatedRoute.snapshot.params['uid']
		    
		```
		
		Estamos trayendo el parámetro que le pasamos a la ruta que especificamos, en este caso estamos trayendo el uid del usuario que clickeemos. Todo esto para poder usar los valores de ese usuario en la otra ruta.

	* **Brayan Mamani** [383275] (1)

		Gracias me sirvió para entender la función de un snapshot.

* **ecastelor** (1) [368929](https://platzi.com/comentario/368929/) 

	¿Cual es la diferencia de utilizar **routerLink** con o sin corchetes?
	``` 
	    <a [routerLink]="['/conversation', user.uid]">
	    
	    <a routerLink="/conversation/{{user.uid}}">
	    
	```

	* **Juan Diego Lopez Triana** [368929] (4)

		Cuando usas corchetes puedes pasar una bind property (una variable) que puedes definir en la clase, y cuando no los usas pasas la ruta como tal.

	* **francves17** [368929] (2)

		Acá un poco más de info: <https://angular.io/guide/template-syntax>

	* **Brayan Mamani** [368929] (1)

		Excelente información me sirvió mucho.

* **Damaris Quiroz** (1) [42102](https://platzi.com/comentario/383275/) 
En todo esto no me queda muy claro para qque funciona el snapshot.params

	* **Juan Carlos Felizzola Vega** [42102] (4)

		Si imprimes solo `this.activatedRoute` te darás cuenta que es un objeto que trae muchas cosas.  
		Con
		``` 
		    this.activatedRoute.snapshot.params['uid']
		    
		```
		
		Estamos trayendo el parámetro que le pasamos a la ruta que especificamos, en este caso estamos trayendo el uid del usuario que clickeemos. Todo esto para poder usar los valores de ese usuario en la otra ruta.

* **ecastelor** (1) [40786](https://platzi.com/comentario/368929/) 
¿Cual es la diferencia de utilizar routerLink con o sin corchetes? <a [routerLink]="['/conversation', user.uid]...

	* **Juan Diego Lopez Triana** [40786] (4)

		Cuando usas corchetes puedes pasar una bind property (una variable) que puedes definir en la clase, y cuando no los usas pasas la ruta como tal.

## 0200. Accediendo a nuestros usuarios desde Conversation.ts [12765](https://platzi.com/clases/1340-angular-avanzado/12765-accediendo-a-nuestros-usuarios-desde-conversationt/)

### Descripción:


Para tener acceso al detalle de los usuarios en diferentes componentes podemos implementar una de dos soluciones:

* Duplicar la fuente de datos en los dos (o más) componentes (no recomendada)
* Tener una sola fuente de datos a la que pueden acceder varios componentes (recomendada)



### Comentarios:

* **arnold025** (6) [585140](https://platzi.com/comentario/585140/) 

	Con la función filter de JavaScript se puede conseguir lo mismo de forma más simplificada.
	``` 
	    getFriendById(friendId) {
	        returnthis.friends.filter(friend => friend.uid === friendId);
	    }
	    
	```

	* **Gonzalo Muñoz** [585140] (1)

		Ojo que filter retorna un arreglo y no un sólo objeto.

	* **jinvernon** [585140] (1)

		Si utilizas .find( friend => friend.uid === friendUid) obtienes el objeto de una vez.

* **luis-batalla** (6) [368271](https://platzi.com/comentario/368271/) 

	Hola!  
	Con el predicate no me funcionaba, lo saquè y funciona. por?
	``` 
	    this.friend=this.friends.find( (record) => {
	          return record.uid == this.friendId;
	        });
	        console.log(this.friend);
	      }
	    
	```

	* **Carlos Federico Rubio Prias** [368271] (4)

		Esa palabra predicate la coloca el editor de manera descriptiva, pero no hace parte real del código, por eso no te funcionaba.

	* **Juan Carlos Felizzola Vega** [368271] (5)

		Te recomiendo tomar el curso de JQuery a Javascript: <https://platzi.com/clases/jquery-js/>
		
		O el de fundamentos de Javascript: <https://platzi.com/clases/fundamentos-javascript/>
		
		O si puedes, toma los dos. Te serán muy útiles.

	* **Sigaweb** [368271] (1)

		ese predicade es un descripción de webstorm, que nos dice como se llama el parámetro de la función mencionada “find”, por eso esta en un toco opaco, es una de las cosas que nos facilita webstorm

	* **Brayan Mamani** [368271] (1)

		Si Webstorrm es de lo mejor.

	* **Claudio Pedalino** [368271] (1)

		Muuuchas gracias, 😃 Tuve el mismo problema

* **sebas-hondarza-gonzalez** (4) [611884](https://platzi.com/comentario/611884/) 

	this.friend = this.friends.find((record) => record.uid === this.friendId);
	
	es bueno parsear **parseInt()** el this.friendId.  
	Algunos IDE’s mencionan el radix como segundo argumento del parseInt quedando:  
	this.friendId = parseInt(this.activatedRoute.snapshot.params.uid, 10);  
	de esta forma se puede usar igualación estricta.

* **Walter Lensinas** (3) [545052](https://platzi.com/comentario/545052/) 

	Buenas tardes, dejo el código de las clase en este repositorio <https://github.com/wlensinas/platzinger-wl.git>
	
	Para ver el código:
	
	  1. `git clone https://github.com/wlensinas/platzinger-wl.git`
	  2. `git checkout 20-access-users`
	  3. `npm install`
	  4. `ng serve --open`
	
	
	
	Saludos.

	* **nicolas-morillo** [545052] (1)

		Me salvaste de un error, gracias

* **ivan_acg** (3) [434249](https://platzi.com/comentario/434249/) 

	Como puedo hacer yo para aprender a pensar este tipo de cosas en Angular?  
	Donde puedo ver un manual o una lista de pasos a seguir para hacer esto?  
	Como hacen normalmente los programadores para aprender estas cosas?  
	Porque solo viendo el código no aprendo nada.

	* **sandovalgus** [434249] (1)

		Cuestión de practicar mucho

	* **ivan_acg** [434249] (3)

		Ya investigue en internet , no es practicar , es aprender a dominar la documentación . Yo viendo el video pensaba que el profesor escribía cosas que se le vienen a la cabeza , y no , saca todo de la documentación .

	* **ferchop2002** [434249] (2)

		Amigo … no es viendo … tienes que ver pausar y hacer el ejercicio en tu casa … de esta forma aprendemos cualquier lenguaje … tal vez algunos se les hará más fácil a otros más difícil por asemejar algún lenguaje pero solo es eso … si solo vez el código no aprendes nada.

	* **Alex Eugenio Gavidia Donayre** [434249] (2)
Yo proyecto en la TV y programo como loco en mi laptop. El tiempo es dinero hermano

	* **Walter Lensinas** [434249] (2)

		Pensa en forma abstracta lo que quieras hacer, luego se busca en el lenguaje como poder realizarlo.

	* **Omar Enrique Crespo Merchan** [434249] (1)

		Eso se le llama arquitectura de software, tienes una carrera en Platzi, la mayoria de los programadores aprendes esto por la fuerza de forma empirica a base de muchos años de código, si quieres optimizar tu aprendizaje aprende Arquitectura de Software, aqui en platzi hay un par de cursos muy buenos 😃

* **Octavio Gomez Romo** (2) [447040](https://platzi.com/comentario/447040/) 

	y cual es la solución mas optima?

	* **jobcoronadoduran** [447040] (1)

		La de servicios.

	* **Alex Eugenio Gavidia Donayre** [447040] (1)
Que formules buenas preguntas

	* **Brayan Mamani** [447040] (1)

		Utilizar servicios.

* **jeisonsrz** (2) [415110](https://platzi.com/comentario/415110/) 

	conversation.component.ts ---->
	``` 
	    import { Component, OnInit } from '@angular/core';
	    import {ActivatedRoute} from '@angular/router';
	    import {User} from '../interfaces/user';
	    
	    @Component({
	      selector: 'app-conversation',
	      templateUrl: './conversation.component.html',
	      styleUrls: ['./conversation.component.css']
	    })
	    export class ConversationComponent implements OnInit {
	    
	      friendId: any;
	      friends: User[];
	      friend: User;
	      constructor(private activatedRoute: ActivatedRoute) {
	        this.friendId = this.activatedRoute.snapshot.params['uid'];
	        console.log(this.friendId);
	    
	        letusuario1: User = {
	          nick: 'Eduardo',
	          age: 24,
	          email: 'ed@aoe.aoe',
	          friend: true,
	          uid: 1
	        };
	        letusuario2: User = {
	          nick: 'Freddy',
	          age: 28,
	          email: 'fred@aoe.aoe',
	          friend: true,
	          uid: 2
	        };
	        letusuario3: User = {
	          nick: 'Yuliana',
	          age: 18,
	          email: 'yuli@aoe.aoe',
	          friend: true,
	          uid: 3
	        };
	        letusuario4: User = {
	          nick: 'Ricardo',
	          age: 17,
	          email: 'rick@aoe.aoe',
	          friend: false,
	          uid: 4
	        };
	        letusuario5: User = {
	          nick: 'Marcos',
	          age: 30,
	          email: 'marcos@aoe.aoe',
	          friend: false,
	          uid: 5
	        };
	        this.friends = [usuario1, usuario2, usuario3, usuario4, usuario5];
	    
	        this.friend = this.friends.find((record) =>{
	          return record.uid == this.friendId;
	        });
	        console.log(this.friend);
	      }
	    
	      ngOnInit() {
	      }
	    
	    }
	    
	```

* **Briggs** (2) [62292](https://platzi.com/comentario/637438/) 
Más adelante en el curso tendremos server-side para acceder a bases de datos como MongoDB, etc?

* **Alex Eugenio Gavidia Donayre** (1) [540750](https://platzi.com/comentario/540750/) 
Find

* **Alex Eugenio Gavidia Donayre** (1) [540749](https://platzi.com/comentario/540749/) 
Gracias

* **Carlos Uriel de Jesus Sánchez González** (1) [397832](https://platzi.com/comentario/397832/) 

	```
	    this.friend = this.friends.find( (record) => {
	          return record.uid == this.friendId;
	        });
	        console.log(this.friend);
	      }
	    
	```

* **Sergio Eduardo Velandia Obando** (1) [80705](https://platzi.com/comentario/964914/) 
Una ayuda por favor: tengo el siguiente problema, al escribir la sentencia con predicate dice: cannot find name ‘predicate’ porque se gen...

	* **saidmlx** [80705] (2)

		Omite la palabra, esto sale porque el instructor esta utilizando webstorm

* **ITEMPRESARIAL LIC 1** (1) [64359](https://platzi.com/comentario/674669/) 
Sería una buena opción enviar todo el objeto del usuario como parámetro…??

	* **Cristian Camilo Beltrán Sarta** [64359] (1)

		Considero que no sería una buena práctica

* **Octavio Gomez Romo** (1) [47774](https://platzi.com/comentario/447040/) 
y cual es la solución mas optima?

	* **Alex Eugenio Gavidia Donayre** [47774] (1)
Que formules buenas preguntas

## 0210. Creando un servicio de usuarios e Inyectando el servicio en nuestros componentes [12766](https://platzi.com/clases/1340-angular-avanzado/12766-creando-un-servicio-de-usuarios-e-inyectando-el-se/)

### Descripción:


Un servicio es una clase que puede ser inyectada en uno o varios componentes y que es muy útil para compartir datos o funciones entre éstos, evitando la duplicidad de código.

Se crean a través del Angular CLI con el siguiente comando:
``` 
    ng generate service <directorio>/<nombre del servicio>
    
```

Al ejecutar este comando se generan en nuestro proyecto los siguientes archivos:
``` 
    /<directorio>
      <nombre del servicio>.service.spec.ts
      <nombre del servicio>.service.ts
    
```

Luego en el componente, inyectamos el Servicio de manera similar a cómo inyectamos el ActivatedRoute.

### Comentarios:

* **Enzo Aliatis** (7) [682368](https://platzi.com/comentario/682368/) 

	Talvez quedaría mejor si en el mismo servicio creo una función que me devuelva el friend que necesito
	
	En el servicio:
	``` 
	    getAFriend(uuid) {
	        return this.friends.find(item => item.uuid == uuid);}
	    
	```
	
	En conversation component
	``` 
	    export classConversationComponentimplementsOnInit {
	      friendId: any;
	      friend: User;
	    
	      constructor(
	        privateactivatedRoute: ActivatedRoute,
	        privateuserServices: UserService
	      ) {
	        this.friendId = this.activatedRoute.snapshot.params["uuid"];
	        this.friend = this.userServices.getAFriend(this.friendId);
	      }
	    
	      ngOnInit() {}
	    }
	    
	```

* **Leonel Rojas** (6) [370856](https://platzi.com/comentario/370856/) 

	Les dejo una versión mas corta de realizar esta búsqueda, aprovechando los arrow funtions, ya que cuando se recibe 1 solo parámetro nos podemos evitar los parentesis, y si es una sola línea de código nos ahorramos el “return”
	``` 
	    this.friend = this.friends.find(record => record.uid == this.friendId);
	    
	```

	* **Juan Roberto Paz Ramos** [370856] (1)

		Buen aporte, gracias

* **carlosextra1** (6) [365983](https://platzi.com/comentario/365983/) 

	La palabra **Predicate ** me dio error y tuve que quitarla para que corriera sin errores.
	``` 
	    this.friend =  this.friends.find((record)=>{
	          return record.uid ==  this.friendId;
	        })```
	    
	```

	* **Daniel García** [365983] (6)

		realmente fue el IDE de Eduardo quien puso ese placeholder “predicate” como un tipo de ayuda visual, la palabra no forma parte del código.

	* **luis-batalla** [365983] (2)

		gracias! me pasò lo mismo y ahora veo tu mensaje, yo uso visual code debe ser x eso.  
		Slds,

	* **Juan Carlos Felizzola Vega** [365983] (3)

		De nuevo, recomiendo tomar estos cursos antes de este:
		
		JQuery a Javascript: <https://platzi.com/clases/jquery-js/>  
		Fundamentos de Javascript: <https://platzi.com/clases/fundamentos-javascript/>
		
		O si pueden, tomen los dos. Les serán muy útiles.

	* **Gianfranco Correa** [365983] (4)

		me rompi mucho la cabheza buscando el error y en google, despues saque el pantalla completa del video y vi el primer comentario jajaja

	* **Jecsham Castillo** [365983] (1)

		xD

	* **Gabriel Solorzano** [365983] (2)

		Esto mismo pasó en el video anterior. Creo que el prof. ha usado tantas veces ese IDE que ya no le presta atención a esos HINTS o ayudas que salen, y por eso no se molestó en aclararlo en los videos. Cosas q pasan

	* **Brayan Mamani** [365983] (2)

		Si es una de las características de WebStorm. Usen WebStorm.

* **Emilio Ian Camacho Mejia** (3) [606094](https://platzi.com/comentario/606094/) 

	ng g s service/user

* **jeisonsrz** (3) [415204](https://platzi.com/comentario/415204/) 

	conversation.component.ts ---->
	``` 
	    import { Component, OnInit } from '@angular/core';
	    import {ActivatedRoute} from '@angular/router';
	    import {User} from '../interfaces/user';
	    import {UserService} from '../services/user.service';
	    
	    @Component({
	      selector: 'app-conversation',
	      templateUrl: './conversation.component.html',
	      styleUrls: ['./conversation.component.css']
	    })
	    export class ConversationComponent implements OnInit {
	    
	      friendId: any;
	      friends: User[];
	      friend: User;
	      constructor(private activatedRoute: ActivatedRoute, private userService: UserService) {
	        this.friendId = this.activatedRoute.snapshot.params['uid'];
	        console.log(this.friendId);
	    
	        this.friends = this.userService.getFriends();
	    
	        this.friend = this.friends.find((record) =>{
	          return record.uid == this.friendId;
	        });
	        console.log(this.friend);
	      }
	    
	      ngOnInit() {
	      }
	    
	    }
	    
	    
	```
	
	user.service.ts ----->
	``` 
	    import { Injectable } from '@angular/core';
	    import {User} from '../interfaces/user';
	    
	    @Injectable({
	      providedIn: 'root'
	    })
	    export class UserService {
	      friends: User[];
	      constructor() {
	        letusuario1: User = {
	          nick: 'Eduardo',
	          age: 24,
	          email: 'ed@aoe.aoe',
	          friend: true,
	          uid: 1
	        };
	        letusuario2: User = {
	          nick: 'Freddy',
	          age: 28,
	          email: 'fred@aoe.aoe',
	          friend: true,
	          uid: 2
	        };
	        letusuario3: User = {
	          nick: 'Yuliana',
	          age: 18,
	          email: 'yuli@aoe.aoe',
	          friend: true,
	          uid: 3
	        };
	        letusuario4: User = {
	          nick: 'Ricardo',
	          age: 17,
	          email: 'rick@aoe.aoe',
	          friend: false,
	          uid: 4
	        };
	        letusuario5: User = {
	          nick: 'Marcos',
	          age: 30,
	          email: 'marcos@aoe.aoe',
	          friend: false,
	          uid: 5
	        };
	        this.friends = [usuario1, usuario2, usuario3, usuario4, usuario5];
	    
	      }
	    
	      getFriends() {
	        returnthis.friends;
	      }
	    }
	    
	    
	```
	
	home.component.ts ---->
	``` 
	    import { Component, OnInit } from '@angular/core';
	    import {User} from '../interfaces/user';
	    import {UserService} from '../services/user.service';
	    
	    @Component({
	      selector: 'app-home',
	      templateUrl: './home.component.html',
	      styleUrls: ['./home.component.css']
	    })
	    export class HomeComponent implements OnInit {
	    
	      friends: User[];
	      constructor(private userService: UserService) {
	        this.friends = userService.getFriends();
	    
	      }
	    
	      ngOnInit() {
	      }
	    
	    }
	    
	    
	```

* **Carlos Castro** (2) [915480](https://platzi.com/comentario/915480/) 

	Esperaba que hubiera otra forma aparte de _servicios _y _clonar _datos entre componentes. Me refiero al uso de algún manejador del “estado” de la app, estilo Redux. Seguiré viendo el curso esperando ver una explicación sobre esta área, que es uno de los mayores retos que me enfrento al usar angular en aplicaciones grandes/complejas 😄

	* **MauricioF** [915480] (1)
Redux we puede usar en angular

* **marioamaciasortiz** (2) [833896](https://platzi.com/comentario/833896/) 

	Enzo dijo lo que yo pense jajaja  
	se tenia que decir y se dijo

* **Alex Eugenio Gavidia Donayre** (2) [543849](https://platzi.com/comentario/543849/) 
ng generate service services/user

* **Alfonso Adame Rueda** (2) [529404](https://platzi.com/comentario/529404/) 

	hola compañeros lo volví a ejecutar y ya me dio, aunque no se por que pasa esto.

	* **Diego Alexander Forero Higuera (Platzi)** [529404] (1)

		Es probable que tuvieras cache en el navegador y por esto fallaba.

	* **Alfonso Adame Rueda** [529404] (1)

		gracias a todos por responder

	* **Brayan Mamani** [529404] (1)

		Aveces hay que limpiar el cache del navegador.

* **mario-salinas** (2) [424762](https://platzi.com/comentario/424762/) 

	Durante el curso de angular 4 ademas de importar el servicio en el component donde se va a usar este se agregaba a app.module.ts en la sección de providers ¿Que ventaja nos brinda eso?  
	Ya que como se ve en esta clase podemos hacer uso sin hacer la declaración en app.module.ts

	* **moises mannarino** [424762] (3)

		si se agrega automaticamente en providers, l oque pasa que como crea el servicio con angular cli no se muestra q se agrega automaticamente ahi, pero se agrega

	* **mario-salinas** [424762] (1)

		Woow muchas gracias

	* **Brayan Mamani** [424762] (1)

		Angular CLI ayuda mucho.

* **sukomost** (2) [409797](https://platzi.com/comentario/409797/) 

	Alguien sabe porque al inyectar el servicio en el componente dentro del constructor se define como privado. ¿Siempre es asi?

	* **Poseidonihp** [409797] (1)

		Se define privado porque es dentro del contexto del componente, es mas que todo seguridad,Si es publico donde tenga inyectado(referenciado) el componente se puede llamar.

	* **Brayan Mamani** [409797] (1)

		Si para que otros no puedan alterarlo. Reglas de seguridad.

* **JOSE ANDRES GOMEZ MORANTES** (1) [1070135](https://platzi.com/comentario/1070135/) 

	Hola, alguno sabe de que manera puedo captar el id cuando la el array es de tipo Observable? es que .find no sirve para ese caso, alguna otra funcion?!
	``` 
	    export class ListDetailsComponent implements OnInit {
	      resultId: any;
	      results: Observable<Result[]>;
	      result: Result;
	      @Input() listDetail: any;
	    
	      constructor(private activatedRoute: ActivatedRoute,
	                  private backendService: BackendService) {
	        this.resultId = this.activatedRoute.snapshot.params.rid;
	        console.log(this.resultId);
	        this.results = this.backendService.getUrl();
	        this.result = this.results.find((record) => {
	          return record.rid = this.resultId;
	        })
	       }
	    
	      ngOnInit() {
	      }
	    
	    }```
	    
	```

* **FelipeVpz** (1) [597971](https://platzi.com/comentario/597971/) 

	A mi no me retorno el objeto :C … me aparece como undefined … alguien sabe como arreglarlo ?

	* **aragonesteban (Platzi)** [597971] (1)

		Hola Felipe, podrías compartir tu código para poder ayudarte mejor, gracias!

	* **FelipeVpz** [597971] (1)

		User.ts
		``` 
		    
		    export type status = 'online' | 'offline' | 'busy' | 'away';
		    
		    export interface User {
		      // Es similar a una clase, deben agregarse los atributos que obtendra,además permite manejar errores
		    
		      nick: string;
		      subnick?: string;
		      age?: number;
		      email: string;
		      friend: boolean;
		      uid: any;
		      status: status;
		    
		    }
		    
		    
		    
		```
		
		Conversation.ts
		``` 
		    import { Component, OnInit } from '@angular/core';
		    import {ActivatedRoute} from '@angular/router';
		    import {UserService} from '../services/user.service';
		    import {User} from '../interfaces/user';
		    
		    @Component({
		      selector: 'app-conversation',
		      templateUrl: './conversation.component.html',
		      styleUrls: ['./conversation.component.css']
		    })
		    export class ConversationComponent implements OnInit {
		    
		      friendId: any;
		      friends: User[];
		      friend: User;
		      constructor(private activatedRoute: ActivatedRoute , private userService: UserService) {
		        this.friendId = this.activatedRoute.snapshot.params.uid;
		        console.log('id:' + this.friendId);
		    
		        this.friends = this.userService.getFriends();
		    
		        this.friend = this.friends.find((record) => {
		          return record.uid === this.friendId;
		          console.log(this.friend);
		        });
		        console.log(this.friend);
		      }
		    
		      ngOnInit() {
		      }
		    
		    }
		    
		```
		
		conversation.html
		``` 
		    <p>
		     {{friendId}} - {{friend.nick}}
		    </p>
		    
		    
		```

	* **FelipeVpz** [597971] (1)

		user.service.ts
		``` 
		    import { Injectable } from '@angular/core';
		    import {User} from '../interfaces/user';
		    // Servicio puede ser injectado en cualquier componente o clase
		    @Injectable({
		      // esta disponible a nivel de root es decir t0do
		      providedIn: 'root'
		    })
		    export class UserService {
		      friends: User[];
		      constructor() {
		        constusuario1: User = {
		          nick: 'Eduardo',
		          age: 24,
		          email: 'ed@aoe.aoe',
		          friend: true,
		          uid: 1,
		          status: 'online'
		        };
		        constusuario2: User = {
		          nick: 'Freddy',
		          age: 28,
		          email: 'fred@aoe.aoe',
		          friend: true,
		          uid: 2,
		          status: 'offline'
		        };
		        constusuario3: User = {
		          nick: 'Yuliana',
		          age: 18,
		          email: 'yuli@aoe.aoe',
		          friend: true,
		          uid: 3,
		          status: 'offline'
		        };
		        constusuario4: User = {
		          nick: 'Ricardo',
		          age: 17,
		          email: 'rick@aoe.aoe',
		          friend: false,
		          uid: 4,
		          status: 'away'
		        };
		        constusuario5: User = {
		          nick: 'Marcos',
		          age: 30,
		          email: 'marcos@aoe.aoe',
		          friend: false,
		          uid: 5,
		          status: 'busy'
		        };
		        this.friends = [usuario1, usuario2, usuario3, usuario4, usuario5];
		      }
		      getFriends() {
		        returnthis.friends;
		      }
		    }
		    
		```

	* **ManuFerrer** [597971] (1)

		Me ha pasado lo mismo.
		
		He hecho lo siguiente y ha funcionado.  
		He cambiado return record.user_id == this.friend.user_id; y en su lugar he puesto simplemente return record.user_id;

	* **jehisonorostegui** [597971] (1)

		Creo que la solución anterior no es la adecuada, pues no valida el id del usuario que tiene que retornar.

	* **Alfonso Navarro** [597971] (2)

		Felipe tu problema es q en la linea **record.uid === this.friendId** te esta retornando **false** porq utilizas tripe igual ( **===** )
		``` 
		    this.friend = this.friends.find((record) => {
		          return record.uid === this.friendId;
		          console.log(this.friend);
		        });
		    
		```
		
		Para q’ te funcione tendrías q parsear el **id** q estas recibiendo quedando de esta manera
		``` 
		    this.friendId = parseInt(this.activatedRoute.snapshot.params['uid'])
		    
		```
		
		De esta manera ya te funcionaria.
		
		Tres meses después pero a alguien le podría servir.

* **Gian Pumayalla** (1) [555257](https://platzi.com/comentario/555257/) 

	¿Que es **service**?

	* **aragonesteban (Platzi)** [555257] (2)

		Los **services** en Angular son para que en ellos puedas hacer peticiones a una API, puedas hacer cualquier tipo de petición ya sea GET, POST, PUT o DELETE.

* **Walter Lensinas** (1) [545675](https://platzi.com/comentario/545675/) 

	Buenas tardes, dejo el código de las clase en este repositorio <https://github.com/wlensinas/platzinger-wl.git>
	
	Para ver el [código](https://github.com/wlensinas/platzinger-wl/tree/21-create-service):
	
	  1. `git clone https://github.com/wlensinas/platzinger-wl.git`
	  2. `git checkout 21-create-service`
	  3. `npm install`
	  4. `ng serve --open`
	
	
	
	Saludos.

* **Alex Eugenio Gavidia Donayre** (1) [540751](https://platzi.com/comentario/540751/) 
Excelente

* **Alfonso Adame Rueda** (1) [529391](https://platzi.com/comentario/529391/) 

	quien me ayuda por fa?

	* **jobcoronadoduran** [529391] (1)

		En que podria ayudarte?

	* **Mateo Santiago Zapata Maldonado** [529391] (1)

		¿Que necesitas?

* **Alfonso Adame Rueda** (1) [529385](https://platzi.com/comentario/529385/) 

	hola buenas noches me sale este error:  
	ERROR in src/app/home/home.component.ts(12,30): error TS2339: Property ‘getFriends’ does not exist on type ‘UserService’.

	* **Alfonso Adame Rueda** [529385] (1)
![GET.PNG](https://static.platzi.com/media/user_upload/GET-372f8afc-87b4-4583-b90e-b9c8e3dc73b8.jpg)

	* **LuisHG** [529385] (1)

		podrías mandar una imagen del código del servicio para saber bien por que marca el error. Lo que veo es que en la pestaña de servio no habías guardado cambios y no esta tomando el método de getFriends si lo creaste y no guardaste el archivo.

	* **Alfonso Adame Rueda** [529385] (1)

		gracias por responder

	* **eric-alejandro-asce** [529385] (1)

		guarda los cambios en user.service.ts, el punto a la derecha de la pestaña indica que no has guardado los últimos cambios.

* **Alfonso Adame Rueda** (1) [529374](https://platzi.com/comentario/529374/) 

	![](![GET.PNG](https://static.platzi.com/media/user_upload/GET-7d383dff-a194-41a2-b695-23fb0993f713.jpg)

* **Alfonso Adame Rueda** (1) [528985](https://platzi.com/comentario/528985/) 
	
	![GET.PNG](https://static.platzi.com/media/user_upload/GET-0f07a42d-5d64-49b1-a667-c9cd15e9627c.jpg)

* **Alfonso Adame Rueda** (1) [528983](https://platzi.com/comentario/528983/) 
	
	![GET.PNG](https://static.platzi.com/media/user_upload/GET-d91f34c3-930c-4f4e-adad-689e73c0406f.jpg)

* **Alfonso Adame Rueda** (1) [524703](https://platzi.com/comentario/524703/) 

	import { Component, OnInit } from ‘@angular/core’;  
	import { ActivatedRoute} from ‘@angular/router’;  
	import { User } from ‘…/interfaces/user’;
	
	@Component({  
	selector: ‘app-conversation’,  
	templateUrl: ‘./conversation.component.html’,  
	styleUrls: [’./conversation.component.css’]  
	})  
	export class ConversationComponent implements OnInit {  
	friendId:any;  
	friends : User[];  
	friend: User;
	
	constructor(private activatedRoute : ActivatedRoute ) {  
	this.friendId = this.activatedRoute.snapshot.params[‘uid’];  
	console.log(this.friendId);  
	let usuario1: User = {  
	nick: ‘Eduardo’,  
	age: 24,  
	email: ‘ed@aoe.aoe’,  
	friend: true,  
	uid: 1  
	};  
	let usuario2: User = {  
	nick: ‘Freddy’,  
	age: 28,  
	email: ‘fred@aoe.aoe’,  
	friend: true,  
	uid: 2  
	};  
	let usuario3: User = {  
	nick: ‘Yuliana’,  
	age: 18,  
	email: ‘yuli@aoe.aoe’,  
	friend: true,  
	uid: 3  
	};  
	let usuario4: User = {  
	nick: ‘Ricardo’,  
	age: 17,  
	email: ‘rick@aoe.aoe’,  
	friend: false,  
	uid: 4  
	};  
	let usuario5: User = {  
	nick: ‘Marcos’,  
	age: 30,  
	email:‘marcos@aoe.aoe’,  
	friend: false,  
	uid: 5  
	};  
	this.friends = [usuario1,usuario2,usuario3,usuario4,usuario5];  
	this.friend = this.friends.find((record) => {  
	return record.uid == this.friendId;   
	});  
	Console.log(this.friend);
	
	}  
	ngOnInit() {  
	}
	
	}
	``` 
	    <code>
	    
	```

* **Alfonso Adame Rueda** (1) [524702](https://platzi.com/comentario/524702/) 

	hola buenas tardes me sale este error en el console.log  
	ERROR in src/app/conversation/conversation.component.ts(58,13): error TS2339: Property ‘log’ does not exist on type ‘{ new (): Console; prototype: Console; }’.

	* **Diego Alexander Forero Higuera (Platzi)** [524702] (1)

		es `console.log(this.friend)` estas escribiendo Console.log

	* **Alfonso Adame Rueda** [524702] (1)

		muchas gracias GOLLUM23 por responder ,es un error de novato,me gusta esto de platzi, que te responden tus dudas, me hacen sentir que no estoy estudiando solo ,  
		muchas gracias.

* **Meliza villafuerte rayme** (1) [517217](https://platzi.com/comentario/517217/) 

	¿Como crear una “ventana modal” o “cuadro de dialogo” en Angular 6?

	* **aragonesteban (Platzi)** [517217] (1)

		Hola, puedes ver este tutorial de Angular Material para que puedas crear un Dialog o Modal en tu Web App <https://medium.com/codingthesmartway-com-blog/angular-material-part-2-popups-modals-1ed0c2405f18>

* **TlalocES** (1) [491682](https://platzi.com/comentario/491682/) 

	Con el mismo codigo me funciona correcto, pero me aparece en conversations WDS Disconnected! alguna idea?

* **Germain Rafael Bueno Taguariparo** (1) [462943](https://platzi.com/comentario/462943/) 

	yo lo que hice fue en el servicio cree el método que me permite seleccionar el unico friend
	``` 
	      getFriend(id: any) {
	        returnthis.friends.find( record => {
	          return record.uid === id;
	        });
	      }
	    
	```

* **Víctor Alejandro Rueda Gómez** (1) [455761](https://platzi.com/comentario/455761/) 

	Faltaría importar la interfaz de `User` en el user.service.ts para que sea válida la declaración de `friends: User[];`

* **Carlos Uriel de Jesus Sánchez González** (1) [397868](https://platzi.com/comentario/397868/) 

	conversation.component.ts
	``` 
	    import { Component, OnInit } from '@angular/core';
	    import {ActivatedRoute} from '@angular/router';
	    import {UserService} from '../services/user.service';
	    import {User} from '../interfaces/user';
	    
	    @Component({
	      selector: 'app-conversation',
	      templateUrl: './conversation.component.html',
	      styleUrls: ['./conversation.component.css']
	    })
	    export class ConversationComponent implements OnInit {
	      friendId: number;
	      friends: User[];
	      friend: User;
	      constructor(private activatedRoute: ActivatedRoute, private userService: UserService) {
	        this.friendId = parseInt(this.activatedRoute.snapshot.params['uid'], 10);
	        console.log(this.friendId);
	        this.friends = userService.getFriends();
	        this.friend = this.friends.find( record => record.uid === this.friendId);
	        console.log(this.friend);
	      }
	    
	      ngOnInit() {
	      }
	    
	    }
	    
	```

* **Bian** (1) [388482](https://platzi.com/comentario/388482/) 

	tengo este error ayuda porfavor…
	``` 
	    core.js:1673 ERROR Error: Uncaught (in promise): TypeError: Cannot read property 'find'ofundefined
	    TypeError: Cannot read property 'find'ofundefined```
	    
	```

* **Juan Carlos Felizzola Vega** (1) [384244](https://platzi.com/comentario/384244/) 

	Para crear el primer servicio no hay necesidad de crear la carpeta antes.  
	Con solo:
	``` 
	    ng g s services/user
	    
	```
	
	Generamos tanto la carpeta, como el servicio.

* **FelipeVpz** (1) [59926](https://platzi.com/comentario/597971/) 
A mi no me retorno el objeto :C … me aparece como undefined … alguien sabe como arreglarlo ?

	* **aragonesteban (Platzi)** [59926] (1)

		Hola Felipe, podrías compartir tu código para poder ayudarte mejor, gracias!

* **Gian Pumayalla** (1) [56646](https://platzi.com/comentario/555257/) 
¿Que es service?

	* **aragonesteban (Platzi)** [56646] (2)

		Los **services** en Angular son para que en ellos puedas hacer peticiones a una API, puedas hacer cualquier tipo de petición ya sea GET, POST, PUT o DELETE.

* **Alfonso Adame Rueda** (1) [54398](https://platzi.com/comentario/529391/) 
quien me ayuda por fa?

	* **jobcoronadoduran** [54398] (1)

		En que podria ayudarte?

* **Alfonso Adame Rueda** (1) [54397](https://platzi.com/comentario/529385/) 
hola buenas noches me sale este error: ERROR in src/app/home/home.component.ts(12,30): error TS2339: Property ‘getFriends’ does not exi...

	* **Alfonso Adame Rueda** [54397] (1)
![GET.PNG](https://static.platzi.com/media/user_upload/GET-372f8afc-87b4-4583-b90e-b9c8e3dc73b8.jpg)

* **Meliza villafuerte rayme** (1) [53404](https://platzi.com/comentario/517217/) 
¿Como crear una “ventana modal” o “cuadro de dialogo” en Angular 6?

	* **aragonesteban (Platzi)** [53404] (1)

		Hola, puedes ver este tutorial de Angular Material para que puedas crear un Dialog o Modal en tu Web App <https://medium.com/codingthesmartway-com-blog/angular-material-part-2-popups-modals-1ed0c2405f18>

* **mario-salinas** (1) [45842](https://platzi.com/comentario/424762/) 
Durante el curso de angular 4 ademas de importar el servicio en el component donde se va a usar este se agregaba a app.module.ts en la se...

	* **moises mannarino** [45842] (3)

		si se agrega automaticamente en providers, l oque pasa que como crea el servicio con angular cli no se muestra q se agrega automaticamente ahi, pero se agrega

* **sukomost** (1) [44610](https://platzi.com/comentario/409797/) 
Alguien sabe porque al inyectar el servicio en el componente dentro del constructor se define como privado. ¿Siempre es asi?

	* **Poseidonihp** [44610] (1)

		Se define privado porque es dentro del contexto del componente, es mas que todo seguridad,Si es publico donde tenga inyectado(referenciado) el componente se puede llamar.

* **JesusVarela** (0) [70204](https://platzi.com/comentario/770807/) 
no se como colocar una imagen aqui. la palaba predicate me da error. este es el codigo y no se que de malo tie...

	* **Juan David Castro (Platzi)** [70204] (1)

		Contesto tu primera pregunta.
		
		Hay dos formas de subir imágenes:
		
		1️⃣ Abre el editor de comentarios y arrastra tu imagen desde la computadora hasta el editor.
		
		2️⃣ Escribe **`![](URL)`** y cambia `URL` por la url de tu imagen.
		
		Para las otras preguntas: ¿Qué error te sale al usar **`predicate`**?

## 0220. Pipes en Angular (date, number, json) [12767](https://platzi.com/clases/1340-angular-avanzado/12767-pipes-en-typescript-date-number-json9984/)

### Descripción:


Los pipes en angular, son elementos que se pueden incluir en el HTML y nos permiten aplicar transformaciones a los datos antes de mostrarlos.

Algunos de los pipes más usados son:

* json
* number: ‘<formato-decimal>’
* date: ‘<formato de fecha>’



Puedes consultar más formatos en la documentación oficial de [Angular - Pipes](https://angular.io/guide/pipes).

### Links:

* [Angular Docs](https://angular.io/api/common/DatePipe)

### Comentarios:

* **greivinfonseca** (4) [676939](https://platzi.com/comentario/676939/) 

	ya para esta version en el caso de **predicate** este ya viene implicito por lo que no hay que agregarlo
	``` 
	    <this.friend = this.friends.find((record)=>{
	          return record.uid == this.friendId;
	        });>
	    
	```

	* **Juan Guerra** [676939] (1)

		Gracias!!!

* **marioamaciasortiz** (2) [833907](https://platzi.com/comentario/833907/) 

	el formato de decimales formatea o redondea es decir trunca o redondea???

	* **daniel-zurita** [833907] (1)

		si pones cuantos decimales quieres, trunca. Si quieres redondear en decimales pones x.0-0 , esto te redondeara de 5 hacia arriba como siguiente número.

* **Walter Lensinas** (2) [545711](https://platzi.com/comentario/545711/) 

	Buenas tardes, dejo el código de las clase en este repositorio <https://github.com/wlensinas/platzinger-wl.git>
	
	Para ver el [código](https://github.com/wlensinas/platzinger-wl/tree/22-pipes):
	
	  1. `git clone https://github.com/wlensinas/platzinger-wl.git`
	  2. `git checkout 22-pipes`
	  3. `npm install`
	  4. `ng serve --open`
	
	
	
	Saludos.

* **jeisonsrz** (2) [415214](https://platzi.com/comentario/415214/) 

	conversation.component.html ---->
	``` 
	    <p>
	     {{friend |  json }};
	    </p>
	    <p>
	      {{price | number: '1.2-2' }};
	    </p>
	    <p>
	      {{today | date:'medium'}};
	    </p>
	    
	    
	```
	
	conversation.component.ts ---->
	``` 
	    import { Component, OnInit } from '@angular/core';
	    import {ActivatedRoute} from '@angular/router';
	    import {User} from '../interfaces/user';
	    import {UserService} from '../services/user.service';
	    
	    @Component({
	      selector: 'app-conversation',
	      templateUrl: './conversation.component.html',
	      styleUrls: ['./conversation.component.css']
	    })
	    export class ConversationComponent implements OnInit {
	    
	      friendId: any;
	      friends: User[];
	      friend: User;
	      price: number = 78.3534533636;
	      today: any = Date.now();
	      constructor(private activatedRoute: ActivatedRoute, private userService: UserService) {
	        this.friendId = this.activatedRoute.snapshot.params['uid'];
	        console.log(this.friendId);
	    
	        this.friends = this.userService.getFriends();
	    
	        this.friend = this.friends.find((record) =>{
	          return record.uid == this.friendId;
	        });
	        console.log(this.friend);
	      }
	    
	      ngOnInit() {
	      }
	    
	    }
	    
	    
	```

	* **Brayan Mamani** [415214] (1)

		Les servirá de ayuda a los que por alguna razón no les funciona.

* **Alex Eugenio Gavidia Donayre** (1) [543855](https://platzi.com/comentario/543855/) 
Amazing

* **Carlos Uriel de Jesus Sánchez González** (1) [397884](https://platzi.com/comentario/397884/) 

	conversation.component.ts
	``` 
	    import {Component, OnInit} from '@angular/core';
	    import {ActivatedRoute} from '@angular/router';
	    import {UserService} from '../services/user.service';
	    import {User} from '../interfaces/user';
	    
	    @Component({
	      selector: 'app-conversation',
	      templateUrl: './conversation.component.html',
	      styleUrls: ['./conversation.component.css']
	    })
	    export class ConversationComponent implements OnInit {
	      friendId: number;
	      friends: User[];
	      friend: User;
	      price: number;
	      today: any;
	    
	      constructor(private activatedRoute: ActivatedRoute, private userService: UserService) {
	        this.friendId = parseInt(this.activatedRoute.snapshot.params['uid'], 10);
	        console.log(this.friendId);
	        this.friends = userService.getFriends();
	        this.friend = this.friends.find(record => record.uid === this.friendId);
	        console.log(this.friend);
	        this.price = 78.3454;
	        this.today = Date.now();
	      }
	    
	      ngOnInit() {
	      }
	    
	    }
	    
	```
	
	conversation.component.html
	``` 
	    <p>
	      {{friend | json}}
	    </p>
	    <p>
	      {{price | number: '1.5-5'}}
	    </p>
	    <p>
	      {{today | date:'fullDate'}}
	    </p>
	    
	    
	```

* **GABRIEL OMAR TARAPUES RODRIGUEZ** (1) [75614](https://platzi.com/comentario/872723/) 
Porque en TS no puedo comparar con 3 iguales (=) y solo funciona con ()???

* **Alberth Andrés Velásquez mejia** (1) [65176](https://platzi.com/comentario/687076/) 
buenas tardes tengo un problema con this.friends.find(predicate: src/app/convesation/convesation.component.ts:24:47 - error TS1005: ‘,’ e...

	* **Javi Felices** [65176] (1)

		Buenas.  
		No se ve el código, parece ser que falta una “,” según el mensaje.  
		Un saludo.

## 0230. Creando nuestro propio pipe para buscar entre nuestros contactos [12768](https://platzi.com/clases/1340-angular-avanzado/12768-creando-nuestro-propio-pipe-para-buscar-entre-nues/)

### Descripción:


Para crear un pipe personalizado debemos crear un archivo de TypeScript e importar las clases Pipe y PipeTransform desde @angular/core.
``` 
    import {Pipe, PipeTransform} from '@angular/core';
    
    @Pipe ({
      name: 'nombre-del-pipe' // --- este es el nombre con que se implementa en el html
    })
    export class MiCustomPipe implements PipeTransform {
      public transform ( value, args: string ) {
         return <valor transformado>
      }
    }
    
```

### Comentarios:

* **Andrés Ariza** (31) [364906](https://platzi.com/comentario/364906/) 

	Para agilizar la creación del pipe les recomiendo usar el angular cli
	``` 
	    ng g p pipes/search
	    
	```
	
	g = Shorthand de generate  
	P = Shorthand de pipe  
	Seguido del directorio/nombre

	* **Jhoysner Corona** [364906] (5)

		Nota : y si creas el pipe con Angular Cli automáticamente se importa en el app.module.ts

	* **Santiago Patiño** [364906] (1)

		que maravilla

	* **Jecsham Castillo** [364906] (1)

		Y también genera el código base automáticamente

	* **Brayan Mamani** [364906] (1)

		Angular Cli la mejor herramienta de Angular.

	* **AlejandroBenitezCorp** [364906] (1)

		Excelente aporte!

* **carlosagudelov** (10) [401064](https://platzi.com/comentario/401064/) 

	La consola me daba este error
	``` 
	    <ReferenceError: FormsModule isnot defined>
	    
	```
	
	Lo solucioné añadiendo esta línea en app.module.ts:
	``` 
	    <import { FormsModule } from'@angular/forms';>
	    
	```

	* **alejandro-villaseca** [401064] (1)

		buena, lo raro es que VSC no me realizó el import automáticamente

	* **Brayan Mamani** [401064] (1)

		Si VSC tiene algunos percances.

	* **AlejandroBenitezCorp** [401064] (1)

		Gracias! Me estaba pasando lo mismo y no encontraba de donde tenia que importar el FormsModule

* **Diego Ortiz** (8) [746799](https://platzi.com/comentario/746799/) 

	No dejen sus parámetros como `any` “nunca”. Aprovechen typescript usando algo como esto:  
	`transform(friends: User[], searchString: string): User[] {...}`

	* **Elberth Jair Agreda Rosero** [746799] (5)

		Sí es verdad, sin embargo este buscador lo podrías reutilizar al declararlo como any.

* **Gonzalo Muñoz** (7) [679561](https://platzi.com/comentario/679561/) 

	generar pipes por CLI
	``` 
	    ng g p pipes/search
	    
	```

	* **Adrian Alberto Casas Lopez** [679561] (1)

		Lo genial de generar los componentes, servicios pipes etc con angular cli es que ademas de generarlos con la estructura los importa en el app.module.ts.  
		Me encanta este curso!..

* **MauricioF** (4) [568739](https://platzi.com/comentario/568739/) 

	Angular v7 ya arroja toda la estructura para escribir en search,ts.
	``` 
	    import {import { Pipe, PipeTransform } from '@angular/core';
	    
	    @Pipe({
	        name:'search'
	    })
	    
	    export classNamePipeimplementsPipeTransform {
	        transform(value: any, ...args: any[]): any {
	            
	        }
	    }}```
	    
	```

* **Diego Burlando** (2) [366097](https://platzi.com/comentario/366097/) 

	Muy útil este video, pero sera la mejor forma de hacer un search input?

* **carlosextra1** (2) [365998](https://platzi.com/comentario/365998/) 

	esta chingon este pipe de search.ts
	
	**JSON.stringify(item)** : convierte el item del json en string  
	**.toLowerCase()** : para a minúsculas el string  
	**includes(args)** : incluye los argumentos que se le enviaron por la variable args para hacer la busqueda
	``` 
	    import {Pipe, PipeTransform} from"@angular/core";
	    
	    @Pipe({
	    	name: 'search'
	    })
	    export classSearchPipeimplementsPipeTransform{
	    	publictransform(value, args: string){
	    		if(!value){
	    			return;
	    		}
	    		if(!args){
	    			returnvalue;
	    		}
	    		args = args.toLowerCase();
	    		returnvalue.filter((item)=>{
	    			return JSON.stringify(item).toLowerCase().includes(args)
	    		});
	    	}
	    }```
	    
	```

	* **Ricardo Etcheto** [365998] (3)

		Includes(arg) no “incluye” includes te devuelve true o false si el string contiene ese args.  
		“Palabra”.includes(“bra”) => true  
		"Palabra".includes(“str”) => false

	* **Manuel Angel Garcia Manzano** [365998] (1)

		Gracias a los dos. No entendia bien que hacia esa linea pero ahora lo entiendo gracias

* **Diego Burlando** (2) [40507](https://platzi.com/comentario/366097/) 
Muy útil este video, pero sera la mejor forma de hacer un search input?

* **Carla Patricia Arauz Gonzales** (1) [1023621](https://platzi.com/comentario/1023621/) 

	Me falla la proiedad Filter, en la terminal me sale que no existe on type ‘typeof ValueConvertor’

* **YojanPardo** (1) [1005486](https://platzi.com/comentario/1005486/) 

	recuerden que FormsModule se import de @angular/forms
	``` 
	    import { FormsModule } from '@angular/forms';
	    
	```

* **patriciavaldebenitop** (1) [980911](https://platzi.com/comentario/980911/) 

	genial !!!

* **Kingsman7** (1) [850224](https://platzi.com/comentario/850224/) 

	Wow

* **juan-pablo-castro** (1) [617380](https://platzi.com/comentario/617380/) 

	No me queda claro,  
	¿Me lo pueden explicar?
	
	La función transform de search.ts **espera recibir dos parámetos**
	``` 
	    publictransform (value, args:string)
	    
	```
	
	Sin embargo cuando hacemos la llamada **solamente le estamos pasando el parámetro: query** , correspondiente a args:string
	``` 
	    let userof friends | search: query ;
	    
	```
	
	**¿En qué momento se le pasó el array de usuarios?**

	* **Miguel Fernando Urquijo Gómez** [617380] (1)

		No mira que al arreglo de friends se le esta aplicando el pipe… y adicional se le esta pasando el query para que lo filtre.
		
		Saludos

	* **Diego Ortiz** [617380] (4)

		El lio está en usar los nombres default de un pipe (`value` y `args`) que para fines educativos no son muy dicientes.  
		Yo al value le llamaría **friendsArray **y al args le llamaría **searchString**. Así sería mucho más fácil de leer y entender el código.  
		Y sí, por defecto el array al que le aplicas el pipe, es el primer parámetro de transform, así es la sintaxis.

	* **David Alejandro Mosquera Moreno** [617380] (1)

		Si me parece que así se puede comprender un poco mejor
		``` 
		    public transform(friendsArray, searchString: string)
		    
		```

* **Emilio Ian Camacho Mejia** (1) [606607](https://platzi.com/comentario/606607/) 

	Tengo un problema… ¿A que se debe que no me reconoce **FormsModule**?
	
	Me podrían ayudar…
	
	![angular.png](https://static.platzi.com/media/user_upload/angular-87b54239-3805-45c6-9656-3db428429b9a.jpg)

	* **aenriquer** [606607] (19)

		Eso pasa porque no estas importando FormsModule. Tienes que escribir también
		``` 
		    import { FormsModule } from '@angular/forms'
		    
		```

	* **Arturo Mojica Guerrero** [606607] (3)

		Normalmente, al escribir el modulo, mi editor me lo reconoce; pero en este caso puntual nunca me lo quizo reconocer, me toco escribir el import primero y luego si colocarlo.

* **oneri** (1) [548288](https://platzi.com/comentario/548288/) 

	Me puede ayudar ya que mi pipe si funciona pero cuando se carga la pagina la lista esta en blanco y el placeholder=“Buscar Amigo” se encuentra vació. Hasta que se tecle algo en el input se muestra de acuerdo a los caracteres tecleados y si borro lo que escribe ahora si me muestra la lista completa y el placeholder=“Buscar Amigo”
	
	home.component.html
	``` 
	    <<inputtype="text"placeholder="Buscar Amigo" [(ngModel)]="query" />
	    <br />
	    <b>Amigos</b>
	    
	    <ng-container *ngFor="let user of friends | search: query; let i = index">
	    <div>
	    <arouterLink = "/conversation/{{user.uid}}">
	     {{i}}. {{user.nick}} - {{user.email}}
	    </a>
	    </div>
	    </ng-container>
	    >
	    
	```
	
	search.ts
	``` 
	    <import {Pipe, PipeTransform} from'@angular/core';
	    @Pipe({
	    name: 'search'
	    
	    })
	    
	    export classSearchPipeimplementsPipeTransform{
	    
	      publictransform(value, args: string){
	        if(!value){
	          return;
	        }
	        
	        if(!args){
	          returnvalue;
	        }
	        args = args.toLowerCase();
	        returnvalue.filter( (item) => {
	          return JSON.stringify(item).toLowerCase().includes(args);
	        });
	      }
	    }>
	    
	```

	* **Alex Eugenio Gavidia Donayre** [548288] (2)
![](https://drive.google.com/open?id=1T1yCt5Tn2glunQH0gaJQuk0YdUUiUU-k)

	* **Alex Eugenio Gavidia Donayre** [548288] (1)

		En tu html al empezar "<<"  
		Revisa el input se te ha pasado “<”

	* **Alex Eugenio Gavidia Donayre** [548288] (1)

		```
		    <img src=https://drive.google.com/open?id=1T1yCt5Tn2glunQH0gaJQuk0YdUUiUU-k" />
		    
		```

	* **Alex Eugenio Gavidia Donayre** [548288] (1)

		Revisa esta imagen: <https://drive.google.com/open?id=1T1yCt5Tn2glunQH0gaJQuk0YdUUiUU-k>

* **Walter Lensinas** (1) [545730](https://platzi.com/comentario/545730/) 

	Buenas tardes, dejo el código de las clase en este repositorio <https://github.com/wlensinas/platzinger-wl.git>
	
	Para ver el [código](https://github.com/wlensinas/platzinger-wl/tree/23-pipes-custom):
	
	  1. `git clone https://github.com/wlensinas/platzinger-wl.git`
	  2. `git checkout 23-pipes-custom`
	  3. `npm install`
	  4. `ng serve --open`
	
	
	
	Saludos.

* **Gabriel Solorzano** (1) [533661](https://platzi.com/comentario/533661/) 

	Soy solo yo o la función .filter() solo filtra cuando uno escribe 3 letras o más? No filtra 1 o 2 letras

	* **Alex Eugenio Gavidia Donayre** [533661] (1)

		Revisa la lógica.  
		Eso lo puedes personalizar tu mismo.

	* **Diego Alexander Forero Higuera (Platzi)** [533661] (1)

		Se configura por lo general cuando tienes más de 3 caracteres para que la búsqueda no consuma tantos recursos, si tienes palabras con solo 2 caracteres debes entonces configurarlo con 2 caracteres en adelante.

* **Alfonso Adame Rueda** (1) [529809](https://platzi.com/comentario/529809/) 

	me gusto mucho este vídeo, por que se explica el código.

* **IngWMC2018** (1) [431033](https://platzi.com/comentario/431033/) 

	El SearchPipe me marca de rojo y me muestra el siguiente mensaje:  
	La compatibilidad experimental con decoradores es una característica que está sujeta a cambios en una próxima versión. Establezca la opción ‘experimentalDecorators’ para quitar esta advertencia.
	
	Por favor, alguien me puede ayudar?

	* **José Miguel Paredes Chanquin** [431033] (3)

		Me pasó lo mismo en VScode y lo solucioné entrando a:
		
		File > Preferences > Settings
		
		Y ahí en el buscador pon esto:
		
		Javascript › Implicit Project Config: Experimental Decorators
		
		Habilita el checbox y listo.

* **jeisonsrz** (1) [415238](https://platzi.com/comentario/415238/) 

	home.component.html ---->
	``` 
	    <inputtype="text"placeholder="Buscar amigo" [(ngModel)]="query" />
	    <br/>
	    <br/>
	    <b>Amigos</b>
	    <ng-container *ngFor="let user of friends | search: query; let i = index">
	    
	      <div >
	        <arouterLink="/conversation/{{user.uid}}" >
	          {{i}}. {{user.nick}} - {{user.email}}
	        </a>
	    
	      </div>
	    
	    </ng-container>
	    
	    
	```
	
	home.component.ts ---->
	``` 
	    import { Component, OnInit } from '@angular/core';
	    import {User} from '../interfaces/user';
	    import {UserService} from '../services/user.service';
	    
	    @Component({
	      selector: 'app-home',
	      templateUrl: './home.component.html',
	      styleUrls: ['./home.component.css']
	    })
	    export class HomeComponent implements OnInit {
	    
	      friends: User[];
	      query: string = '';
	      constructor(private userService: UserService) {
	        this.friends = userService.getFriends();
	    
	      }
	    
	      ngOnInit() {
	      }
	    
	    }
	    
	    
	```
	
	app.module.ts —>
	``` 
	    import { BrowserModule } from '@angular/platform-browser';
	    import { NgModule } from '@angular/core';
	    
	    import { AppComponent } from './app.component';
	    import { LoginComponent } from './login/login.component';
	    import { HomeComponent } from './home/home.component';
	    import { ConversationComponent } from './conversation/conversation.component';
	    import { ProfileComponent } from './profile/profile.component';
	    import {RouterModule, Routes} from '@angular/router';
	    import { MenuComponent } from './menu/menu.component';
	    import {SearchPipe} from './pipes/search';
	    import {FormsModule} from '@angular/forms';
	    
	    
	    constappRoutes: Routes = [
	      {path: '', component: HomeComponent},
	      {path: 'home', component: HomeComponent},
	      {path: 'login', component: LoginComponent},
	      {path: 'conversation/:uid', component: ConversationComponent},
	      {path: 'profile', component: ProfileComponent},
	    ];
	    
	    @NgModule({
	      declarations: [
	        AppComponent,
	        LoginComponent,
	        HomeComponent,
	        ConversationComponent,
	        ProfileComponent,
	        MenuComponent,
	        SearchPipe,
	      ],
	      imports: [
	        BrowserModule,
	        RouterModule.forRoot(appRoutes),
	       FormsModule
	      ],
	      providers: [],
	      bootstrap: [AppComponent]
	    })
	    export class AppModule { }
	    
	    
	```

	* **jeisonsrz** [415238] (1)

		PIPE—  
		search.ts —>
		``` 
		    import {Pipe, PipeTransform} from'@angular/core';
		    
		    @Pipe(
		      {
		        name: 'search'
		      }
		    )
		    
		    export  classSearchPipeimplementsPipeTransform{
		      publictransform(value, args: string){
		        if (!value) {
		          return;
		        }
		        if (!args) {
		          returnvalue;
		        }
		    
		        args = args.toLowerCase();
		        returnvalue.filter( (item) => {
		          return JSON.stringify(item).toLocaleLowerCase().includes(args);
		        });
		      }
		    }
		    
		    
		```

* **sukomost** (1) [414128](https://platzi.com/comentario/414128/) 

	ngModel: Te permite hacer bind a una variable y detecta los cambios que se hagan sobre ella, tanto desde el lado del front como desde el lado del back.  
	Por defecto angular no impora todos los modelos. Para poder utilizar ngModel, hay que incluir un modulo en appModule.ts. El módulo es FormsModule

* **edu1590** (1) [406221](https://platzi.com/comentario/406221/) 

	Recordatorio:
	
	Para utilizar two way data binding en un input es necesario importar formsModule

* **edu1590** (1) [406219](https://platzi.com/comentario/406219/) 

	UFF! Genial Pipe!!

* **Carlos Uriel de Jesus Sánchez González** (1) [397911](https://platzi.com/comentario/397911/) 

	search.ts
	``` 
	    import {Pipe, PipeTransform} from'@angular/core';
	    
	    @Pipe({
	      name: 'search'
	    })
	    
	    export classSearchPipeimplementsPipeTransform {
	      publictransform(value, args: string) {
	        if (!value) {
	          return;
	        }
	        if (!args) {
	          returnvalue;
	        }
	        args = args.toLowerCase();
	        returnvalue.filter(item => {
	          return JSON.stringify(item).toLowerCase().includes(args);
	        });
	      }
	    }
	    
	    
	```

* **Alejandro Salazar** (1) [367845](https://platzi.com/comentario/367845/) 

	brutal este pipe!

* **Diego Burlando** (1) [366096](https://platzi.com/comentario/366096/) 

	Muy útil este video, pero sera la mejor forma de hacer un seach input?

* **oneri** (1) [56065](https://platzi.com/comentario/548288/) 
Me puede ayudar ya que mi pipe si funciona pero cuando se carga la pagina la lista esta en blanco y el placeholder=“Buscar Amigo” se encu...

	* **Alex Eugenio Gavidia Donayre** [56065] (2)
![](https://drive.google.com/open?id=1T1yCt5Tn2glunQH0gaJQuk0YdUUiUU-k)

* **Gabriel Solorzano** (1) [54754](https://platzi.com/comentario/533661/) 
Soy solo yo o la función .filter() solo filtra cuando uno escribe 3 letras o más? No filtra 1 o 2 letras

	* **Alex Eugenio Gavidia Donayre** [54754] (1)

		Revisa la lógica.  
		Eso lo puedes personalizar tu mismo.

* **IngWMC2018** (1) [46407](https://platzi.com/comentario/431033/) 
El SearchPipe me marca de rojo y me muestra el siguiente mensaje: La compatibilidad experimental con decoradores es una característica qu...

	* **José Miguel Paredes Chanquin** [46407] (3)

		Me pasó lo mismo en VScode y lo solucioné entrando a:
		
		File > Preferences > Settings
		
		Y ahí en el buscador pon esto:
		
		Javascript › Implicit Project Config: Experimental Decorators
		
		Habilita el checbox y listo.

* **Diego Burlando** (1) [40506](https://platzi.com/comentario/366096/) 
Muy útil este video, pero sera la mejor forma de hacer un seach input?

# Estilos [2350]

## 0240. ¿Cómo usar estilos CSS y referenciar recursos [12769](https://platzi.com/clases/1340-angular-avanzado/12769-como-usar-estilos-css-y-referenciar-recursos3109/)

### Descripción:


Para ir definiendo los estilos CSS que vas a aplicar en tu componente, puedes ir probando primero en el inspector del navegador e ir viendo los resultados en tiempo real, y cuando ya tengas todos los estilos definidos, puedes cortarlos y pegarlos en los archvos CSS del proyecto.

### Comentarios:

* **carlos ruales** (5) [756133](https://platzi.com/comentario/756133/) 

	A alguno, como a mi, ¿le dio nostalgia escuchar los sonidos que estàn en los assets? 😅

* **eddyarellanes** (4) [365402](https://platzi.com/comentario/365402/) 

	Where is the repo x(?

	* **ricardocelis (Platzi)** [365402] (4)

		te paso el repo: <https://github.com/EduardoIbarra/platzinger/tree/2_EstilosLogin2>

* **ctr9120** (3) [701487](https://platzi.com/comentario/701487/) 

	Como dato, si apenas estás aprendiendo CSS y HTML Javascript, lo ideal es ponerle clases a los elementos para usarlos en CSS, para Javascript es mejor poner id

	* **Diego Ortiz** [701487] (1)

		No entiendo por qué dices que para JS es mejor poner id. A mi me parece que es mala práctica poner “ids” porque generalmente tienen otros objetivos dentro del template. En las empresa dónde he trabajado, siempre usamos clases.

	* **Usuario ESolutions** [701487] (1)

		Son atributos que se emplean para diferentes propósitos, Difference Between Class and ID  
		An HTML element can only have one unique id that belongs to that single element, while a class name can be used by multiple elements:  
		<https://www.w3schools.com/hTML/html_id.asp>

* **DESTRUN** (2) [421882](https://platzi.com/comentario/421882/) 

	la ruta de la imagen me sale invalida, ya he puesto “assets/img/logo_live.png” y “…/assets/img/logo_live.png”

	* **LegaCode** [421882] (1)

		 _Dependiendo el lugar en el que quieras traer el recurso se usan las rutas relativas y absolutas. Y un error muy común es como en tu segundo ejemplo el cual usaste 3 puntos_

	* **alejandrarock** [421882] (1)

		Te recomiendo que uses el IDE visual studio code, es muy practico cuando cargas imagenes desde un path.

	* **Arturo Mojica Guerrero** [421882] (1)

		…/…/assets/img/logo_live.png a mi me funciono asi, nose si quieres intentar

* **José Valentin Salina Peña** (2) [366659](https://platzi.com/comentario/366659/) 

	Y los assets??

	* **Diego Alexander Forero Higuera (Platzi)** [366659] (2)

		Vamos a revisar para publicarlos.

	* **ricardocelis (Platzi)** [366659] (2)

		ya están listos =)

	* **Gabriel Solorzano** [366659] (1)

		Están geniales, tantos recuerdos

	* **Brayan Mamani** [366659] (1)

		Genial ya están!!

* **Elberth Jair Agreda Rosero** (1) [780399](https://platzi.com/comentario/780399/) 

	Buen video profe Eduardo, por especifidad es mejor usar class y trabajar con BEM para darle un mejor orden a nuestro css.

* **amasfs** (1) [628624](https://platzi.com/comentario/628624/) 

	buenas, tengo una duda, al poner la imagen con el img me funciona bien y el codigo parece estar bien, pero voy al devTools ( uso Mozilla Firefox ) y me paro sobre el <img src="…/…/assets/img/logo_live.png" alt=“Logo Platzinger”>  
	me dice No se puede cargar la imagen.  
	La verdad no tengo idea porque me pasa, es un problema simple seguramente, pero me molesta no saber porque pasa…

	* **amasfs** [628624] (0)
Osea, la imagen no se muestra, me muestra solo el Alt, si alguien sabe que puede ser por favor ayúdeme.

	* **Carla Patricia Arauz Gonzales** [628624] (1)

		Usa sólo dos puntos ‘…’ no tres ‘…’

* **miguelangelloor96** (1) [588585](https://platzi.com/comentario/588585/) 

	Una pregunta, cual es el plugin de VS Code que me da las sugerencias al momento que estoy escribiendo

* **Alex Eugenio Gavidia Donayre** (1) [546584](https://platzi.com/comentario/546584/) 
Me ha servido de mucho hasta ahora

* **Alex Eugenio Gavidia Donayre** (1) [546583](https://platzi.com/comentario/546583/) 
Graciaz

* **Walter Lensinas** (1) [545860](https://platzi.com/comentario/545860/) 

	Buenas tardes, dejo el código de las clase en este repositorio <https://github.com/wlensinas/platzinger-wl.git>
	
	Para ver el [código](https://github.com/wlensinas/platzinger-wl/tree/24-css):
	
	  1. `git clone https://github.com/wlensinas/platzinger-wl.git`
	  2. `git checkout 24-css`
	  3. `npm install`
	  4. `ng serve --open`
	
	
	
	Saludos.

* **jeisonsrz** (1) [415246](https://platzi.com/comentario/415246/) 

	menu.component.html---->
	``` 
	    <img id="main-logo" src="assets/img/logo_live.png" alt="Logo de Platzinger">
	    <arouterLink="/home">home</a> -
	    <arouterLink="/login">Login</a> -
	    <arouterLink="/profile">Profile</a>
	    
	    
	```
	
	menu.component.css ---->
	``` 
	    #main-logo{
	      width: 60px;
	    }
	    
	    
	```

* **Carlos Uriel de Jesus Sánchez González** (1) [397921](https://platzi.com/comentario/397921/) 

	menu.component.html
	``` 
	    <img id="main-logo" src="assets/img/logo_live.png" alt="Logo de Platzinger"/>
	    <arouterLink="/home">Home</a>  |
	    <arouterLink="/login">Login</a>  |
	    <arouterLink="/profile">Profile</a>  |
	    
	```
	
	menu.component.css
	``` 
	    #main-logo{
	      width: 60px;
	    }
	    
	```

* **DESTRUN** (1) [45610](https://platzi.com/comentario/421882/) 
la ruta de la imagen me sale invalida, ya he puesto “assets/img/logo_live.png” y “…/assets/img/logo_live.png”

	* **LegaCode** [45610] (1)

		 _Dependiendo el lugar en el que quieras traer el recurso se usan las rutas relativas y absolutas. Y un error muy común es como en tu segundo ejemplo el cual usaste 3 puntos_

* **José Valentin Salina Peña** (1) [40570](https://platzi.com/comentario/366659/) 
Y los assets??

	* **Diego Alexander Forero Higuera (Platzi)** [40570] (2)

		Vamos a revisar para publicarlos.

## 0250. Instalando librerías usando npm (bootstrap y font-awesome) y Referenciando CSS en el angular.json [12770](https://platzi.com/clases/1340-angular-avanzado/12770-instalando-librerias-usando-npm-bootstrap-y-font-a/)

### Descripción:


Se recomienda instalar los paquetes con versiones exactas para evitar incompatibilidades con versiones futuras de las librerías.
``` 
    npm install bootstrap --save-exact
    npm install @fortawesome/fontawesome-free --save-exact
    
```

Luego de instalados los paquetes con npm, la implementación se hace importando las librerías en la sección styles del archivo angular.json
``` 
    ...
      ""styles"": [
        ""node_modules/bootstrap/dist/css/bootstrap.css"",
        ""node_modules/@fortawesome/fontawesome-free/css/all.css"",
        ""src/styles.css""
      ]
    ...
    
```

### Links:

* [Font Awesome](https://fontawesome.com)

* [Bootstrap · The most popular HTML, CSS, and JS library in the world.](https://getbootstrap.com)

### Comentarios:

* **Víctor Manuel Servín Carrillo** (11) [473207](https://platzi.com/comentario/473207/) 

	Hola a todos!
	
	Trabajé mucho tiempo con Bootstrap y si se meten mucho, podrán observar que algunas funcionalidades como los popovers **requieren la importación de algunos JS** ; bundle.js y jquery.js lo cual se me hace un costo/beneficio perjudicial (en mi opinión) a nuestra aplicación. Esto sucede porque Bootstrap surgió en la cumbre de JQuery, por lo que se preparó para ser integrado a ésta librería, pero hoy en día ya no se utiliza.
	
	Si quieren evitar esto, tener funcionalidades más rápidas les recomiendo que prueben con [bulma.io](https://bulma.io/) que es mucho más ligero y está perfectamente preparado para ser trabajado con cualquier ambiente JS (Angular, React, Vue, etc.) con la mayoría de funcionalidad de Bootstrap pero **sólo depende de su CSS** o SCSS, las funcionalidades que antiguamente se hacían con JQuery, funcionan simplemente agregando y quitando clases.
	
	Una simple recomendación que espero les sirva, saludos a todos!

	* **Alex Eugenio Gavidia Donayre** [473207] (1)
Buen dato gracias

	* **Brayan Mamani** [473207] (1)

		Genial lo estuve revisando y promete.

	* **MauricioF** [473207] (1)

		Que bien, casual estaba pensando en lo mismo jQuery esta quedando de lado y es bueno encontrar un reemplazo. ¿Conocen otros?

	* **FelipeVpz** [473207] (1)

		Yo generalmente uso materialize 😃

	* **Mateo Loaiza Rios** [473207] (1)

		Que buen dato amigo. Gracias!

* **formacionadv3** (10) [761552](https://platzi.com/comentario/761552/) 

	Cuidado al añadir las rutas en el angular.json, hay dos “styles” el de “build” y el de “test”, hay que añadirlo en el “build”.

* **JDiaz0017** (6) [364257](https://platzi.com/comentario/364257/) 

	agregando un elemento al array correspondiente a los estilos a minificar por parte del fichero de configuración principal de Angular. Al ingresar correctamente la path ubicada en node_modules y tras haber descargado previamente bootstrap, se requiere iniciar el servidor.

* **jeisonsrz** (4) [415266](https://platzi.com/comentario/415266/) 

	instalación de librerías con npm —>
	``` 
	    npm install bootstrap --save-exact
	    npm install @fortawesome/fontawesome-free --save-exact
	    
	```
	
	angular.json ---->
	``` 
	    "styles": [
	                  "node_modules/bootstrap/dist/css/bootstrap.css",
	                  "node_modules/@fortawesome/fontawesome-free/css/all.css",
	                  "src/styles.css"
	                ],
	    
	```
	
	menu.component.html —>
	``` 
	    <img id="main-logo" src="assets/img/logo_live.png" alt="Logo de Platzinger">
	    <i class="fas fa-american-sign-language-interpreting"></i>
	    <a routerLink="/home">home</a> -
	    <a routerLink="/login">Login</a> -
	    <a routerLink="/profile">Profile</a>
	    
	    
	```

	* **Alex Eugenio Gavidia Donayre** [415266] (1)

		Gracias  
		buen aporte.

* **Elberth Jair Agreda Rosero** (3) [780410](https://platzi.com/comentario/780410/) 

	Alternativa para la UI:  
	<https://material.angular.io/>  
	<https://material.io/>

* **carlos ruales** (3) [759787](https://platzi.com/comentario/759787/) 

	Otro _flag_ importante es colocarle -D para que la dependencia sea guardada como dependencia de desarrollo y no como dependencia del proyecto como tal
	``` 
	    npm install bootstrap -D --save
	    
	```

	* **Diego Ortiz** [759787] (2)

		En este caso es una dependencia de producción también, por eso no sería necesaria la bandera -D  
		Las dependencias de desarrollo son librerías que unicamente vas a usar en tu ambiente local para desarrollar, como por ejemplo las de estilos como eslint.

* **MauricioF** (3) [568794](https://platzi.com/comentario/568794/) 

	Alternativas a bootstrap:
	
	* Componentes prediseñados para Angular:[Link oficial](https://material.angular.io/components/categories)
	
	* Iconos Material Design[Link oficial](https://material.io/tools/icons/?style=baseline)
	
	
	

* **asfo** (3) [557948](https://platzi.com/comentario/557948/) 

	Un detalle:
	
	FontAwesome NO se usa ya así en Angular, tiene una dependencia que permite instalarse y llamarse a forma de componente, como:  
	<fa-icon [icon]="[‘fas’, ‘heart’]"></fa-icon>
	
	Ya no se implementa de esta forma.
	
	Otro dato es que al instalar FontAwesome como módulo directo de Angular o dependencia o como quieran decirle es que se deben instalar los paquetes como fas, far y fab por separado y cargarse en el módulo requerido, si no se usa en un módulo principal y se es´tan usando lazy modules o modules regulares y ahí se usará entonces ahí se puede cargar.
	
	Por último se cargan por separado como menciono al hacer instalaciones varias 😃.
	
	Para que no metan el all.css ahí y mejor aprovechen la bondad de <fa-icon> que viene con los SVGs.

	* **Brayan Mamani** [557948] (1)

		Buena detalle la verdad.

* **carlosextra1** (3) [366128](https://platzi.com/comentario/366128/) 

	en terminal
	``` 
	    npm i bootstrap --save-exact
	    
	```
	
	**–save** guarda el paquete en package.json y pueda ser instalado posteriormente al ejecutar npm i  
	**-exact** se instala la versión exacta del paquete que se intalo la primer vez que usamos el comando en el proyecto

* **laurest** (2) [738465](https://platzi.com/comentario/738465/) 

	Alguien me puede ayudar? añadí la ruta en el angular.json (esta bien la ruta) pero no se me muestran los estilos hice los pasos al pie de la letra y tampoco me salen errores

	* **formacionadv3** [738465] (1)

		Me pasa lo mismo. Alguien puede ayudar.

	* **diferotorres** [738465] (1)

		debes parar y reiniciar la aplicación

* **MauricioF** (2) [569912](https://platzi.com/comentario/569912/) 

	¿Por qué aparecen 13 vulnerabilidades al instalar bootstrap, de las cuales 4 son de prioridad alta?

	* **Diego Alexander Forero Higuera (Platzi)** [569912] (1)

		Es probable que tenga dependencias con vulnerabilidades detectadas y no han actualizado dichas dependencias.

* **Walter Lensinas** (2) [545887](https://platzi.com/comentario/545887/) 

	Buenas tardes, dejo el código de las clase en este repositorio <https://github.com/wlensinas/platzinger-wl.git>
	
	Para ver el [código](https://github.com/wlensinas/platzinger-wl/tree/25-css-frameworks):
	
	  1. `git clone https://github.com/wlensinas/platzinger-wl.git`
	  2. `git checkout 25-css-frameworks`
	  3. `npm install`
	  4. `ng serve --open`
	
	
	
	Saludos.

* **edu1590** (2) [406237](https://platzi.com/comentario/406237/) 

	Muy bien explicado

* **Anthony Gonzalez** (2) [378752](https://platzi.com/comentario/378752/) 

	¿Se hace los mismo con los archivos Javascript externos? como los de bootstrap?

	* **Diego Alexander Forero Higuera (Platzi)** [378752] (4)

		Si, solo que no es en la etiqueta styles si no en la de scripts
		``` 
		    "scripts": [
		      "../node_modules/jquery/dist/jquery.js"
		    ]
		    
		```

* **patriciavaldebenitop** (2) [81448](https://platzi.com/comentario/981512/) 
hola me aparece "“Doctype must be declared first.”" en la consola tengo DOCTYPE EN index.html porque sucede ? alguien me puede...

* **ehnbytes** (1) [1015987](https://platzi.com/comentario/1015987/) 

	Buena clase!

* **GABRIEL OMAR TARAPUES RODRIGUEZ** (1) [874819](https://platzi.com/comentario/874819/) 

	excelente…

* **tecnox** (1) [754814](https://platzi.com/comentario/754814/) 

	Aqui una pregunta que no es totalmente relacionada al contenido de este tema, aunque si tiene algo que ver.  
	Es una buena practica empaquetar los svg en uno solo?  
	El usar por ejemplo [svgstore](https://github.com/svgstore/svgstore)  
	Alguna herramienta similar o mejor?  
	Alguna sugerencia?

* **Wilson Marino Pablo Mendez** (1) [712454](https://platzi.com/comentario/712454/) 

	Se recomienda usar los archivos minificados example “bootstrap.min.css”

	* **Javi Felices** [712454] (1)

		Según comentaba Eduardo, el propio angular.json ya se encarga de eso, aun así yo he indicando los .min y ha funcionando sin problemas.

* **Alex Eugenio Gavidia Donayre** (1) [547081](https://platzi.com/comentario/547081/) 
Interesante

* **Alex Eugenio Gavidia Donayre** (1) [547068](https://platzi.com/comentario/547068/) 
Buena

* **Norman Erick Estrada Vargas** (1) [529839](https://platzi.com/comentario/529839/) 

	excelente explicación!!!

* **Cristian David Franco Garcia** (1) [432202](https://platzi.com/comentario/432202/) 

	ng add bootstrap @fortawesome/fontawesome-free
	
	**Nota:** Debemos borrar el ^ en el archivo package para cada paquete.

* **Carlos  Rubiano** (1) [419880](https://platzi.com/comentario/419880/) 

	En el caso de utilizar scss, cada componente me pide agregar el archivo de variables.scss de bootstrap. Cómo la defino de manera global para no tener que agregarla a cada componente?  
	Otro problema con el que me encontré es que los componente *.ts, no reconocía los estilos de cada componente independiente y resolvi momentaneamente agregando encapsulation: ViewEncapsulation.None a @Component pero esto duplicaba los estilos…

* **Carlos Uriel de Jesus Sánchez González** (1) [397956](https://platzi.com/comentario/397956/) 

	```
	    "styles": [
	                  "node_modules/bootstrap/dist/css/bootstrap.css",
	                  "node_modules/@fortawesome/fontawesome-free/css/all.css",
	                  "src/styles.css"
	                ],
	    
	```

* **MauricioF** (1) [57875](https://platzi.com/comentario/569912/) 
¿Por qué aparecen 13 vulnerabilidades al instalar bootstrap, de las cuales 4 son de prioridad alta?

	* **Diego Alexander Forero Higuera (Platzi)** [57875] (1)

		Es probable que tenga dependencias con vulnerabilidades detectadas y no han actualizado dichas dependencias.

* **Carlos  Rubiano** (1) [45455](https://platzi.com/comentario/419880/) 
En el caso de utilizar scss, cada componente me pide agregar el archivo de variables.scss de bootstrap. Cómo la defino de manera global p...

* **Anthony Gonzalez** (1) [41702](https://platzi.com/comentario/378752/) 
¿Se hace los mismo con los archivos Javascript externos? como los de bootstrap?

	* **Diego Alexander Forero Higuera (Platzi)** [41702] (4)

		Si, solo que no es en la etiqueta styles si no en la de scripts
		``` 
		    "scripts": [
		      "../node_modules/jquery/dist/jquery.js"
		    ]
		    
		```

## 0260. Reto Cambiar ícono según estatus [13003](https://platzi.com/clases/1340-angular-avanzado/13003-reto-cambiar-icono-segun-estatus/)

### Descripción:


Dentro de la carpeta de assets que les compartí, se encuentran íconos para representar cada status (online, offline, busy, away).

Usando lo que has aprendido, muestra el ícono correspondiente a un lado del nickname de cada usuario.

### Comentarios:

* **Juan Diego Lopez Triana** (24) [371883](https://platzi.com/comentario/371883/) 

	Así lo solucione yo:
	``` 
	    <img class="user-status" src="assets/img/logo_live_{{user.status}}.png" alt="Estatus"/>
	    
	```

	* **moises mannarino** [371883] (2)

		that is good, you solved it in one line of code

* **Daniel Pereira** (11) [401374](https://platzi.com/comentario/401374/) 

	Para mi solución primero cree una variable de tipo type para los estados dentro de la interface de user y esta se la aplique como tipo de variable a la propiedad state de la siguiente manera  
	![](https://i.imgur.com/BbuKmEM.png)
	
	Esta solución permite a Visual Studio agregar ayudas a la hora de programar y evita que ocurran typos en tu código  
	![](https://i.imgur.com/arXxh0s.png)
	
	Finalmente en el html solo agregue la imagen utilizando el binding de angular con la direccion de las imagenes
	``` 
	    <h3> 
	              <p>
	                  <imgid="status"src="assets/img/logo_live_{{user.status}}.png"alt="user status">
	                  Name {{user.nick}} {{i}}
	              </p>
	            </h3>
	    
	```
	
	Aqui el resultado  
	![](https://i.imgur.com/9UfxQlN.png)

	* **svaldebenitog** [401374] (1)

		Me parece una buena solución, lo único que puede mejorarse es pasarle una class status en vez del ID ya que se repite varias veces. Con eso ponemos en la css el tamaño de la imagen

	* **Brayan Mamani** [401374] (1)

		Muy buena propuesta de solución al reto.

* **alcastagar** (6) [405508](https://platzi.com/comentario/405508/) 

	Agregamos un nuevo campo de status a la inerface
	``` 
	    export interface User{
	        //"?" indica si es opcional
	        nick:       string;
	        subnick?:    string;
	        age?:        number;
	        email: string;
	        friend: boolean;
	        uid: any;
	        status: string;
	    }
	    
	    
	```
	
	Luego a cada usuario le asignamos su corespondiente status:
	``` 
	    letusuario5: User = {
	          nick: 'Marcos',
	          age: 30,
	          email:'marcos@aoe.aoe',
	          friend: false,
	          uid: 5,
	          status: 'online'
	        };
	    
	```
	
	y en el html agregamos una etiqueta de imagen con un string interpolation del campo status en el nombre del icono:
	``` 
	    <img src="assets/img/logo_live_{{user.status}}.png" alt="Logo de mezzinger"width="15px">
	    
	```

	* **Mad Manuva** [405508] (1)

		Esta solución me pareció la más práctica y limpia!

	* **Jenniffer Helena Alvarez Puello** [405508] (1)

		me parece una excelente solución

	* **Brayan Mamani** [405508] (1)

		Sin duda la mejor solución del reto.

* **Ruben Garcia** (5) [587765](https://platzi.com/comentario/587765/) 

	Saludos, para el proyecto que esto elaborando con el curso decidí utilizar materializecss y lo realice de la siguiente forma:
	
	Paso 1. Agregar un nuevo campo status a la infertace User, y agregar a cada objeto en el servicio el nuevo campo.
	``` 
	    export interface User {
	        nick: string;
	        subnick?: string;
	        age?: number;
	        email: string;
	        friend: boolean;
	        uid: any;
	        status: any;
	    }
	    
	```
	
	Paso 2. Construir Pipe para convertir el estatus en una ruta de imagen
	``` 
	    import { Pipe, PipeTransform } from '@angular/core';
	    
	    @Pipe({
	      name:'userStatus'
	    })
	    export classUserStatusPipeimplementsPipeTransform {
	      public status;
	      transform(value: any) {
	        switch (value) {
	          case1:
	            this.status = 'assets/img/status_live.png';
	          break;
	          case2:
	            this.status = 'assets/img/status_oc.png';
	          break;
	          case3:
	            this.status = 'assets/img/status_offline.png';
	          break;
	        }
	        returnthis.status;
	      }
	    
	    }
	    
	```
	
	Paso 3. Modificar el html para mostrar la imagen.
	``` 
	    <ng-container *ngFor="let friend of friends | search: query; let i = index;">
	                  <liclass="collection-item avatar" *ngIf="friend.friend == true">
	                    <imgsrc="assets/sidenav-demo-avatar.png"alt=""class="circle">
	                    <spanclass="title">{{ friend.nick }}</span><br>
	                    <arouterLink="/conversation/{{ friend.uid }}" >
	                      {{ friend.email }}
	                    </a>
	                    <ahref="#!"class="secondary-content">
	                      <img [src]="friend.status | userStatus"class="right"style="width: 10%;height: 10%;">
	                    </a>
	                  </li>
	                </ng-container>
	    
	```
	
	Resultado:  
	![image1](https://rubengarcia.com.ve/wp-content/uploads/2019/05/Captura-de-pantalla-de-2019-05-14-23-59-12.png)

	* **FelipeVpz** [587765] (1)

		te quedo buenisimo !

* **caprilespe** (4) [793112](https://platzi.com/comentario/793112/) 

	Se agrega un enum con los posibles estatus
	``` 
	    export enumStatus{
	        Online = 'online',
	        Offline = 'offline',
	        Busy = 'busy',
	        Away = 'away'
	    }
	    
	```
	
	Se modifica la interface de usuario con un nuevo atributo llamado “Status”
	``` 
	    import {Status} from '../enum/statusEnum'
	    export interface IUser {
	        nick:string;
	        subnick:string;
	        age:number;
	        email:string;
	        friend:boolean;
	        uid:any;
	        status?:Status
	    }
	    
	    
	```
	
	Finalmente se integra a la vista en el home.componen.html
	``` 
	    <br />
	    <inputtype="text"placeholder="Buscar Amigo" [(ngModel)]="query">
	    <br />
	    <b>Amigos</b>
	    <ng-container *ngFor="let user of friends | search:query; let i = index">
	        <div>
	            <imgclass="icon-status"src="../../assets/img/logo_live_{{user.status}}.png" />
	            <arouterLink="/conversation/{{user.uid}}">
	                {{i}}.{{user.nick}} - {{user.email}}
	            </a>
	        </div>
	    
	    </ng-container>
	    
	    
	```
	
	Resultado
	
	![resultado.PNG](https://static.platzi.com/media/user_upload/resultado-696f1fbb-1e85-4039-b0f1-d8b2b803aed7.jpg)

	* **Arturo Mojica Guerrero** [793112] (1)

		La verdad, nunca habia trabajado con enum tengo problemas con el enum en la clase donde se encuentra interface user con el atributo de status, ya que coloco “online”, Online y nada me coge. ¿Como lo resuelvo compañero.?

* **Jeffry Davila** (3) [389706](https://platzi.com/comentario/389706/) 

	Realice los status con números ,lo mas sencillo posible  
	![Segunda.PNG](https://static.platzi.com/media/user_upload/Segunda-e147f586-8fbb-41d9-9e3c-5b1b35d0bde7.jpg)
	
	<ng-container *ngIf=“user.status==1”>
	
	<a routerLink="/conversation/{{user.uid}}">  
	<img id=“main-logo” src=“assets/img/logo_live_online.png” alt=“Logo de platzinger” width=“20px” height=“20px”>  
	{{i}}. {{user.nick}} - {{user.email}}  
	</a>  
	</ng-container>
	
	<ng-container *ngIf=“user.status==2”>
	``` 
	        <a routerLink="/conversation/{{user.uid}}">
	            <img id="main-logo" src="assets/img/logo_live_offline.png" alt="Logo de platzinger" width="20px" height="20px">
	            {{i}}. {{user.nick}} - {{user.email}}
	        </a>
	    
	```
	
	</ng-container>
	
	<ng-container *ngIf=“user.status==3”>
	``` 
	        <a routerLink="/conversation/{{user.uid}}">
	            <img id="main-logo" src="assets/img/logo_live_busy.png" alt="Logo de platzinger" width="20px" height="20px">
	            {{i}}. {{user.nick}} - {{user.email}}
	        </a>
	    
	```
	
	</ng-container>
	
	<ng-container *ngIf=“user.status==4”>
	``` 
	        <a routerLink="/conversation/{{user.uid}}">
	            <img id="main-logo" src="assets/img/logo_live_away.png" alt="Logo de platzinger" width="20px" height="20px">
	            {{i}}. {{user.nick}} - {{user.email}}
	        </a>
	    
	```
	
	</ng-container>

* **Erik Ricardo Sánchez Pérez** (2) [1025126](https://platzi.com/comentario/1025126/) 

	En mi caso tengo la interface de esta forma
	``` 
	    export interface User {
	      $key?: string;
	      name: string;
	      email: string;
	      state: States;
	      status?: string;
	      friend: boolean;
	    }
	    
	    export enum States {
	      online, offline, busy, away
	    }
	    
	    
	```
	
	y mi vista de esta otra forma
	``` 
	    <p>Amigos</p>
	      <ul *ngFor="let user of users | search: query">
	        <li *ngIf="user.friend">
	          <arouterLink="/conversation/{{user.$key}}" [ngSwitch]="user.state">
	            <img *ngSwitchCase="0"src="assets/img/logo_live_online.png">
	            <img *ngSwitchCase="1"src="assets/img/logo_live_offline.png">
	            <img *ngSwitchCase="2"src="assets/img/logo_live_busy.png">
	            <img *ngSwitchCase="3"src="assets/img/logo_live_away.png">
	            {{user.name}}
	          </a>
	        </li>
	      </ul>
	    
	```
	
	ha sido un buen ejercicio 😄

* **Usuario ESolutions** (2) [786963](https://platzi.com/comentario/786963/) 

	Se propone crear un Enum con los estados del usuario, agregar este atributo al usuario, luego en el controlador de la vista crear un map para cada estado con su url y un método para facilitar a la vista la búsqueda del recurso.  
	Model  
	export enum UserState {  
	ONLINE=‘online’,  
	OFFLINE=‘offline’,  
	BUSY=‘busy’,  
	AWAY=‘away’  
	}  
	export interface User {  
	nick: string;  
	subnick?: string;  
	age?: number;  
	email: string;  
	friend: boolean;  
	uid: any;  
	state:UserState;  
	}
	
	Controller:  
	export class HomeComponent implements OnInit {  
	//otras lineas  
	private mapIconByUserState:Map<UserState,String>;
	
	constructor(private userService:UserService) {  
	//otras lineas  
	this.mapIconByUserState= new Map<UserState,String>();  
	this.mapIconByUserState.set(UserState.ONLINE,‘assets/img/logo_live_online.png’);  
	this.mapIconByUserState.set(UserState.OFFLINE,‘assets/img/logo_live_offline.png’);  
	this.mapIconByUserState.set(UserState.BUSY,‘assets/img/logo_live_busy.png’);  
	this.mapIconByUserState.set(UserState.AWAY,‘assets/img/logo_live_away.png’);  
	}  
	public getUrlOfIconByUserState(userState:UserState ):String{  
	return this.mapIconByUserState.get(userState);  
	}  
	}  
	Vista:  
	home.component.html  
	<!-- otras lineas–>  
	<input type=“text” placeholder=“Buscar” [(ngModel)]=“query”/>  
	<div *ngFor=‘let user of friends | search:query; let i=index;’>  
	<a routerLink="/conversation/{{user.uid}}">{{i}}. {{user.nick}} - {{user.email}}</a>  
	<img id="{{‘logo-live-’+user.state}}" class= ‘logo-live-user-state’ src=’{{getUrlOfIconByUserState(user.state)}}’ />  
	</div>  
	<!-- otras lineas–>  
	Estilo:  
	home.component.css  
	.logo-live-user-state{  
	width: 24px;  
	}

	* **Diego Ortiz** [786963] (1)

		La idea del enum está muy buena 👍  
		Y sacar la url con un método también me parece que deja todo más limpio, solo ajustaría el nombre del método de getUrlOfIconByUserState a getIconUrlByUserState  
		El único detalle es que llamarle “controlador” al componente sí suena un poco anticuado 🤔

* **Luis Angel Ramos Bañuelos** (2) [611015](https://platzi.com/comentario/611015/) 

	poner un id en cada usuario para saber su status y dependiendo a cada id, mostrar el icono correspondiente

* **Anderson Steve Santamaría Ballesteros** (2) [453225](https://platzi.com/comentario/453225/) 

	Poner un estado al usuario e interpolarlo en la ruta de la imagen <img id=“status” src=“assets/img/logo_live_{{user.state}}.png” alt=“status”>

* **Danie contreras** (1) [1111881](https://platzi.com/comentario/1111881/) 

	Bueno aproveche que el nombre de las imágenes solo cambia en el estado y la extensión de las imágenes es la misma para todas y deje que el status modifique el atributo src de mi etiqueta <img> asi:  
	<img class=“statusIcon” src="./assets/img/logo_live_{{usr.status}}.png" alt="">  
	y tengo este resultado  
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-a64dbf4c-9354-4b46-be4d-ca2532acaa51.jpg)  
	![html.PNG](https://static.platzi.com/media/user_upload/html-17fedbd8-43cd-42cd-90f1-bfee9a54394d.jpg)

* **ArmandoZenil** (1) [969091](https://platzi.com/comentario/969091/) 

	**Se agrega la propiedad status a la interface:**
	``` 
	    export interface User {
	        nick: string;
	        subnick?: string;
	        age?: number;
	        status: string;
	        email: string;
	        friend: boolean;
	        uid: string;
	    }
	    
	```
	
	**Y en el .html se implementa la directiva [ngSwitch](https://angular.io/api/common/NgSwitch): **
	``` 
	    <inputtype="text"placeholder="Buscar amigo" [(ngModel)]="query">
	    <h3>Amigos</h3>
	    <ng-container *ngFor="let user of friends | search: query;let i = index">
	        <div [ngSwitch]="user.status">
	            <strong>{{i + 1}}. </strong><arouterLink="/conversation/{{user.uid}}">{{user.nick}} - {{user.email}}</a>
	            <img *ngSwitchCase="'online'"src="assets/img/logo_live_online.png"class="img-fluid status">
	            <img *ngSwitchCase="'offline'"src="assets/img/logo_live_offline.png"class="img-fluid status">
	            <img *ngSwitchCase="'busy'"src="assets/img/logo_live_busy.png"class="img-fluid status">
	            <img *ngSwitchCase="'away'"src="assets/img/logo_live_away.png"class="img-fluid status">
	        </div>
	    </ng-container>
	    
	```
	
	**Para el tamaño de la imagen agregé la clase _status _en el archivo .css:**
	``` 
	    .status{
	        width: 20px;
	    }
	    
	```

* **GABRIEL OMAR TARAPUES RODRIGUEZ** (1) [874870](https://platzi.com/comentario/874870/) 

	Adicionar status en la interface.  
	Ajustar tamano icono en el css del home.  
	Usar {{user.status}} para referenciar el nombre del icono siempr y cuando el los estados tengan el mismo nombre de la imagen, caso contrario se deberia realizar un enumerador como lo menciona @caprilespe.

* **Kingsman7** (1) [850385](https://platzi.com/comentario/850385/) 

	NOTA: usando solo lo aprendido
	
	  1. en la interface agrege un nuevo campo llamado “status”
	
	
	``` 
	    exportinterface user{
	      nick:string;
	      subnick?: string;
	      age?:number;
	      email:string;
	      friend:boolean;
	      uid:any;
	      status:string;
	    }
	    
	```
	
	2 . en el servicio agrege ese mismo campo y uno de los 4 valores ejemplo
	``` 
	    letuser0: user ={
	          nick:'Angel',
	          age: 34,
	          email:'ae.barrios@hotmail.com',
	          friend:true,
	          uid:"0",
	          status:"online"
	        }
	    
	```
	
	y por ultimo en el home.component.html agrege una etiqueta img y dependiendo del estatus llamara a la imagen en el source
	``` 
	    <inputtype="text"placeholder='search' [(ngModel)]="query"/>
	    <h2>Friend</h2>
	    <ng-container *ngFor="let user of friends | search:query; let i = index">
	      <divclass="container">
	        <imgsrc="../../assets/img/logo_live_{{user.status}}.png"alt="icon"id="status">
	        <arouterLink="/chat/{{user.uid}}">
	          {{user.nick}} - {{user.email}}
	        </a>
	      </div>
	    </ng-container>
	    <br>
	    
	```

* **Diego Ortiz** (1) [791971](https://platzi.com/comentario/791971/) 

	Agregué un método publico en el componente
	``` 
	    	public getStatusImg(status: string): string {
	        return`../../assets/img/logo_live_${status}.png`;
	      }
	    
	```
	
	Y lo consumí desde el template
	``` 
	    <imgclass="status-img" [src]="getStatusImg(friend.status)" />
	    
	```
	
	En el css le di un ancho de `16px (1em/1rem)` y listo el pollo

* **fernandojavierespanacordoba** (1) [745910](https://platzi.com/comentario/745910/) 
	
	![2019-09-19_231332.png](https://static.platzi.com/media/user_upload/2019-09-19_231332-68a66988-d244-4ff1-96dd-838c39aab585.jpg)
	``` 
	    <<input type="text" placeholder="Buscar Amigo" [(ngModel)]="query">
	      <div>
	        <ng-container *ngFor="let user of friends | search : query">
	          <div>
	            <a routerLink = "/conversation/{{user.uid}}">
	                {{user.uid}}. {{user.nick}}-{{user.email}}
	                <!-- Se hace string interpolation, además se otorga un id para modificar
	                atributo de ancho(width) en home.component.css -->
	                <img id="statusIcon" src="assets\img\{{user.status}}.png" alt="status de usuario">
	            </a>
	          </div>
	        </ng-container>
	      </div>>
	    
	```

	* **Diego Ortiz** [745910] (1)

		Tuviste que renombrar las imágenes, pero se ve limpio 👍  
		Me queda la duda de si es buena práctica interpolar en un atributo, tenía entendido que eso se debía evitar. ¿Alguien sabe si es mala práctica?

* **WALTER RAUL CANCHAN HERMOZA** (1) [735195](https://platzi.com/comentario/735195/) 

	se creo uncampo el Object User: statusIcono?: string;  
	se agrego en el servicio el nuevo campo y se implemento el html la siguiente linea: <img class=‘img_icono’ src=‘assets/img/logo_live_{{user.statusIcono}}.png’>

* **Hans Vogt** (1) [672221](https://platzi.com/comentario/672221/) 

	  1. En user.ts cree la variable status tipo String
	  2. Dentro de la interfaz la clase user.service.ts a cada registro le agregue la variable y un status diferente entre online, offline, busy y away,  
	3.Home.component.html al div primero le puse un id para ponerle un nombre y luego agregarle en el home.component.css un estilo y agregue antes del registro esto  
	<div id=“User”>  
	<a routerLink="/conversation/{{user.uid}}">  
	<img id=“user-status"src=“assets/img/logo_live_{{user.status}}.png"alt=”${{user.status}}”>{{i}}. {{user.nick}} - {{user.email}}  
	</a>  
	</div>  
	asi deje el css
	
	
	
	#user-status{  
	width: 40px;  
	}  
	#User{  
	height: 50px;  
	vertical-align: middle;  
	}  
	para agregar la imagen segund el status y el correspondiente al nombre  
	4\. Le agregue al menu un icono de fontawesome a cada opcion
	
	<a routerLink="/home"><img id=“main-logo” src=“assets/img/logo_live.png” alt=“Logo de Platzinger”></a>  
	<a routerLink="/home"><i class=“fas fa-home”></i> home</a> |  
	<a routerLink="/login"><i class=“fas fa-sign-in-alt”></i> login</a> |  
	<a routerLink="/profile"><i class=“fas fa-user”></i> profile</a>

* **Dariel0511** (1) [668936](https://platzi.com/comentario/668936/) 

	  1. Agregue el campo del status en los arreglos de usr.service.ts
	
	  2. Luego llame el campo en el home.component.html
	
	  3. Agregue un tamaño al css
	
	
	

* **Camiloalex1643** (1) [668276](https://platzi.com/comentario/668276/) 

	Los pasos que efectue fueron:
	
	HOME COMPONENT
	``` 
	    <h1>Contactos</h1>
	    <inputtype="text"placeholder="Buscar amigo" [(ngModel)]="buscarAmigo" />
	    <br />
	    <h1>Amigos</h1>
	    <!-- Variables estructurables. Solo cambian la estructura del HTML y empiezan con *-->
	    <ulclass="list-group"style="width:20%">
	        <ng-container *ngFor="let user of friends | search:buscarAmigo; let i = index">
	            <div *ngIf="user.friend">
	                <arouterLink="/conversation/{{user.uid}}"title="{{user.status}}">
	                    <liclass="list-group-item d-flex justify-content-between align-items-center">
	    
	                        {{user.nick}}<br />{{user.email}}
	                        <spanclass="badge badge-pill"><imgsrc="assets/img/logo_live_{{user.status}}.png"
	                                class="img-status" /></span>
	    
	                    </li>
	                </a>
	            </div>
	        </ng-container>
	    </ul>
	    
	```
	
	ADICIONAR STRING DE STATUS
	``` 
	    status: string
	    
	```

* **eduquey** (1) [649268](https://platzi.com/comentario/649268/) 

	Los pasos que realicé fueron los siguientes:
	
	  1. Agregar la propiedad status a la interface.  
	status: string;
	  2. Agregar los valores a los datos del servicio:  
	status:“away”
	  3. Modificar el html del home  
	<img src="…/…/assets/img/logo_live_{{friend.status}}.png" class=“status”/> {{friend.nick}} - {{friend.email}}
	  4. Modificar el css de home para darle tamaño a la imagen  
	.status{  
	width: 20px;  
	}
	
	

* **Briggs** (1) [637568](https://platzi.com/comentario/637568/) 

	Pues lo hice como la mayoria lo hizo… Pero agregue algunos cambios al css y html del menu y home.
	
	home.css
	``` 
	    #user-status {
	        width: 30px;
	    }
	    
	```
	
	home.html
	``` 
	    <div>
	        <h1>Contactos</h1>
	        <inputtype="text"placeholder="Buscar" [(ngModel)]="query">
	        <h4>Amigos</h4>
	        <ng-container *ngFor="let user of users | search: query;">
	            <div>
	                <arouterLink="/chat/{{user.uid}}">
	                    <imgid="user-status"src="assets/img/logo_live_{{user.status}}.png"alt="${{user.status}}">{{user.nick}} - {{user.email}}
	                </a>
	            </div>
	        </ng-container>
	    </div>
	    
	```
	
	menu.html, El logo ahora te redirecciona al home.
	``` 
	    <a routerLink="/home"><imgid="main-logo"src="assets/img/logo_live.png"alt="Logo de Platzinger"></a>
	    <a class="menu-item" routerLink="/home"><iclass="fas fa-home">Home</i></a> |
	    <aclass="menu-item"routerLink="/login"><iclass="fas fa-sign-in-alt">Login</i></a> |
	    <aclass="menu-item"routerLink="/profile"><iclass="fas fa-user-alt">Profile</i></a> |
	    
	```
	
	![](https://cdn.discordapp.com/attachments/451359497546498051/596394714362806293/unknown.png)

* **jehisonorostegui** (1) [632477](https://platzi.com/comentario/632477/) 

	Lo hice de una forma muy sencilla. Agregué un nueva propiedad a la interface User llamada status de tipo string:
	``` 
	    export interface User {
	      nick: string;
	      subnick: string;
	      status: string;
	      age: number;
	      email: string;
	      friend: boolean;
	      id: any;
	    }
	    
	```
	
	Luego le coloqué un status a cada usuario que varia entre, busy, online, offline.
	
	En home.component.html agregué una imagen a cada usuario que se va a mostrar en la lista, utilizando un parámetro en su atributo src. Así cuando se recupera el status del usuario, se muestra la imagen que corresponde.
	``` 
	    <ng-container *ngFor="let user of users | search: query">
	    	<div>
	    		<a routerLink="/conversation/{{user.id}}">
	    			<img id="user-status" src="../assets/img/logo_live_{{user.status}}.png"> {{user.nick}} - {{user.email}}
	    		</a>
	    	</div>
	    </ng-container>
	    
	```

* **Edwin De Jesus Chiyopa Garcia** (1) [619955](https://platzi.com/comentario/619955/) 
	
	![Sin título.png](https://static.platzi.com/media/user_upload/Sin%20t%C3%ADtulo-3a70c692-cfd4-4df2-9665-63d11bfcb89d.jpg)

* **Brandon Iván Quiroa Loarca** (1) [615492](https://platzi.com/comentario/615492/) 

	* Se crea una propiedad en la interfase User: status: string;
	* Se añade <img class=“status-icon” src=“assets/img/logo_live_{{user.status}}.png” alt="{{user.status}}">, en el html para buscar la imagen segun el estado de cada usuario
	* Se agrega el status a cada usuarios en el servicio user.service.ts
	
	

* **egarciab2018** (1) [610622](https://platzi.com/comentario/610622/) 


* **hectorchec** (1) [584652](https://platzi.com/comentario/584652/) 

	Primero agregaría el nuevo campo **_status_** a la interfaz **_User_**
	``` 
	    export interface User{
	    	nick: string;
	    	subnick?: string;
	    	age?: number;
	    	email: string;
	    	friend: boolean;
	    	uid: any;
	    	status: string
	    }
	    
	```
	
	Después agregaría la propiedad a cada objeto del arreglo en _**usersService**_ :
	``` 
	    {
	    	nick: 'Eduardo',
	    	age: 24,
	    	email: 'ed@aoe.aoe',
	    	friend: true,
	    	uid: 1,
	    	status: 'online'
	    },
	    ...
	    
	```
	
	posteriormente, modificaría la ****home.component.html**** tal que:
	``` 
	    <arouterLink="/conversation/{{user.uid}}">
	    	<imgclass="status-icon"src="assets/img/logo_live_{{user.status}}.png"alt="{{user.status}}" /> 
	    	{{user.nick}} - {{ user.email }}
	    </a>
	    
	```
	
	y finalmente en **home.component.css** :
	``` 
	    .status-icon {
	        width: 35px;
	    }```
	    
	```

* **JorgeLopez88** (1) [577531](https://platzi.com/comentario/577531/) 

	Esta es la solución que plantee;
	
	  1. En la interface cree un atributo nuevo llamado status el cual puede tomar alguno de los estados mencionados en la linea 1, estos estados no son aleatorios se toman del nombre de las imagenes que estan en la carpeta Asset.  
	![Interface.PNG](https://static.platzi.com/media/user_upload/Interface-f670acd9-0168-49a8-ad4f-7d53722ad801.jpg)  
	![](url)
	
	  2. En el servicio a cada usuario se le agrega su respectivo status.
	
	
	
	
	![](![Servicio.PNG](https://static.platzi.com/media/user_upload/Servicio-c4e7712c-42d9-4d22-9e34-27288e2ef77c.jpg)
	
	  1. En el home.component.html se crea una etiquta img con el src respectivo, ademas se crea un id para darle estilos.  
	![](![home.PNG](https://static.platzi.com/media/user_upload/home-7da62b5b-e58f-4b1e-aaed-2884c9a6b8c6.jpg)
	
	  2. Se le aplica estilos en el home.component.css  
	![](![home-css.PNG](https://static.platzi.com/media/user_upload/home-css-55e3e42c-cfaf-475b-b91c-25a18704c40e.jpg)
	
	  3. Se obtiene el siguiente resultado.  
	![](![resultado.PNG](https://static.platzi.com/media/user_upload/resultado-d0e347a8-ce41-4a7f-aa6f-542bae93c423.jpg)
	
	
	

* **Daniel González Morales** (1) [574697](https://platzi.com/comentario/574697/) 

	buena solución “alcastagar”

* **MauricioF** (1) [570001](https://platzi.com/comentario/570001/) 

	```
	    <!--1) En user.ts se debe añadir la propiedad 'status' de tipo string:-->
	    export interface User{
	    ...
	    status: string;
	    }
	    <!--2) En user.service.ts se debe añadir la propiedad 'status' a cada usuario:-->
	    let usuario5: User = {
	          ...
	          status: 'online'
	        };
	    <!--3) En home.component.html se debe añadir la etiqueta img (dentro de la etiqueta a) incluyendo el nombre de la variable {{user.status}} para que se complete el nombre de la imagen que corresponda:-->
	    <imgsrc="../assets/img/logo_live_{{user.status}}.png"alt="">
	    
	```

	* **MauricioF** [570001] (1)

		home.component.css se debe editar para ajustar el tamaño del icono:
		``` 
		    #status{
		        width: 20px;
		    }
		    
		```
		
		Para mejorar el desempeño de la página, es mejor trabajar con una imagen que tenga exactamente el tamaño final (así evitamos que el sistema tarde más tiempo leyendo mas información de la que se necesita para representar el icono)

* **Mathías Donoso** (1) [567812](https://platzi.com/comentario/567812/) 

	home.component.html
	``` 
	    <img class="status-logo" src="assets/img/logo_live_{{ user.status }}.png" />
	    
	```
	
	En user.ts:
	``` 
	    export type Status = 'online' | 'offline' | 'busy' | 'away';
	    
	    export interface User {
	      nick: string;
	      subnick?: string;
	      age?: number;
	      email: string;
	      friend: boolean;
	      uid: any;
	      status: Status;
	    };
	    
	```

* **CristianAlfonso** (1) [565515](https://platzi.com/comentario/565515/) 

	Los pasos que seguí:
	
	  1. En el interface adicionar el estado:
	
	
	``` 
	    exportinterface User
	    {
	      nick: string;
	      subnick?: string;
	      age?: number;
	      email?: string;
	      friend?: boolean;
	      uid?: any;
	      status?: string;
	    }
	    
	```
	
	2.Servicio adicionar el estado
	``` 
	    export class UserService {
	      friends: User[];
	      constructor() {
	        letusuario1: User = {
	          nick: 'Eduardo',
	          age: 24,
	          email: 'ed@aoe.aoe',
	          friend: true,
	          uid: 1,
	          status: 'online'
	        };
	    
	```
	
	  1. En el html llamar la imagen
	
	
	``` 
	    <br />
	    <inputtype="text"placeholder="Buscar Amigo" [(ngModel)]="query">
	    <br />
	    <b>Amigos</b>
	    <ng-container *ngFor="let user of friends | search: query; let i = index">
	      <div>
	        <imgsrc="assets/img/logo_live_{{user.status}}.png">
	        <arouterLink="/conversation/{{user.uid}}">
	          {{user.nick}} - {{user.email}}
	        </a>
	      </div>
	    </ng-container>
	    <br />
	    
	```
	
	  1. En el CSS definir el tamaño
	
	
	``` 
	    img{
	      height: 30px;
	    }
	    
	```
	
	Listo queda así  
	![Captura de pantalla 2019-04-19 a la\(s\) 1.35.23 p. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-04-19%20a%20la%28s%29%201.35.23%20p.%20m.-b4a09959-071c-47dc-baa6-df849b8ddb4d.jpg)

* **veronica oviedo** (1) [564535](https://platzi.com/comentario/564535/) 

	Yo utilice la directiva estructural *ngIf para decidir que imagen mostrar.
	``` 
	    <p id="link-user" routerLink="/conversation/{{user.uid}}">
	          <img title="online" id="status_logo" *ngIf="user.status === 'online'" src="assets/img/logo_live_online.png" />
	          <img title="offline" id="status_logo" *ngIf="user.status === 'offline'" src="assets/img/logo_live_offline.png" />
	          <img title="away" id="status_logo" *ngIf="user.status === 'away'" src="assets/img/logo_live_away.png" />
	          <img title="busy" id="status_logo" *ngIf="user.status === 'busy'" src="assets/img/logo_live_busy.png" />
	          <img title="appear_offline" id="status_logo" *ngIf="user.status === 'appear_offline'" src="assets/img/logo_live_appear_offline.png" />
	          {{i}} {{user.nick}} - {{user.email}}
	    </p>
	    
	    
	```

* **cesarcadavid** (1) [557953](https://platzi.com/comentario/557953/) 

	```
	    <br />
	    <br />
	    <input type="text" placeholder="Buscar Amigo" [(ngModel)]="query" />
	    <br />
	    <h3>Amigos</h3>
	    <ng-container *ngFor="let friend of friends | search: query; let i = index">
	        <div>
	            <img id="logo-online" src="assets/img/logo_live_{{friend.status}}.png" alt="Logo online"/>
	            <a routerLink="/conversation/{{friend.uid}}">
	                {{i + 1}}. {{friend.nick}} - {{friend.age}} - {{friend.email}}
	            </a>
	        </div>
	    </ng-container>
	    
	```

* **Miguel Castillo Cortes** (1) [549109](https://platzi.com/comentario/549109/) 

	Solo he agregado la propiedad status a la interface User y dentro del home.component.html llame a la imagen interpolando el atributo user.status

* **Walter Lensinas** (1) [545898](https://platzi.com/comentario/545898/) 

	```
	    <ng-container *ngFor="let user of friends | search: query; let i = index">
	      <div>
	        <img id="status-friend" src="./assets/img/logo_live_{{user.status}}.png" alt="{{user.status}}" />
	        <a routerLink="/conversation/{{user.uid}}">
	           {{ i }}. {{ user.nick }} - {{ user.email }} 
	        </a>
	      </div>
	    </ng-container>
	    
	```

	* **Walter Lensinas** [545898] (1)

		repositorio: <https://github.com/wlensinas/platzinger-wl/tree/26-reto-iconos>

* **Francisco Samuel Hernandez Rodríguez** (1) [533730](https://platzi.com/comentario/533730/) 

	Así lo resolví, no se si sea lo óptimo, pero funcionó!
	``` 
	    <ng-container *ngFor="let user of friends | search: query; let i = index">
	    	<div>
	    		<img *ngIf="user.status == 'online'" class="user-status-icon" src="assets/img/logo_live_online.png" alt="">
	    		<img *ngIf="user.status == 'offline'" class="user-status-icon" src="assets/img/logo_live_offline.png" alt="">
	    		<img *ngIf="user.status == 'busy'" class="user-status-icon" src="assets/img/logo_live_busy.png" alt="">
	    		<img *ngIf="user.status == 'away'" class="user-status-icon" src="assets/img/logo_live_away.png" alt="">
	    		<a routerLink="conversation/user.nick">	
	    			{{ i+1 }} {{ user.nick }} - {{ user.email }}
	    		</a>
	    	</div>
	    </ng-container>
	    
	```

* **jeisonsolarte** (1) [527300](https://platzi.com/comentario/527300/) 

	Siempre es bueno hacer los retos y gastar un poco de tiempo pensando antes de mirar los comentarios para optimizar tu código 😉 😄 😃

* **Diego Mauricio Mejía Ospina** (1) [514645](https://platzi.com/comentario/514645/) 

	Defino para la primera parte un String con las variables.  
	export type status = ‘online’ | ‘offline’ | ‘busy’ | ‘away’;
	``` 
	    export type status = 'online' | 'offline' | 'busy' | 'away';
	    
	    export interface User {
	        nick: string;
	        subnick?: string;
	        age?: number;
	        email: string;
	        friend: boolean;
	        uid: any;
	        status: status
	    }
	    
	```
	
	luego en el User.services la agrego un nuevo campo
	``` 
	    letusuario1: User = {
	          nick: 'Eduardo',
	          age: 24,
	          email: 'ed@aoe.aoe',
	          friend: true,
	          uid: 1,
	          status: 'online'
	    
	```
	
	por ultimo en el home component.html le agrego la fuente de la imagen invocando el user.status.
	``` 
	    <ng-container *ngFor = "let user of friends | search: query; let i = index">
	      <div>    
	        <p>
	          <img id="status" src="assets/img/logo_live_{{user.status}}.png" alt="Logo Platzinger" width="20px">        
	          <a routerLink = "/conversation/{{user.uid}}">
	            {{i}} . {{user.nick}} - {{user.email}}
	          </a>
	        </p>      
	      </div>
	    </ng-container>```
	    
	    
	    
	```

* **DyegoVallejo** (1) [497797](https://platzi.com/comentario/497797/) 

	```
	    <ng-container *ngFor="let amigo of amigos | buscador: query; let i=index">
	      <div >  
	        <a routerLink="/conversation/{{amigo.uid}}">
	          {{i}}{{amigo.nick}}--{{amigo.email}}
	        </a>
	        <img *ngIf="amigo.status=='online'" class="imgLogo" src="assets/img/logo_live_online.png" alt="">
	        <img *ngIf="amigo.status=='busy'" class="imgLogo" src="assets/img/logo_live_busy.png" alt="">
	        <img *ngIf="amigo.status=='away'" class="imgLogo" src="assets/img/logo_live_offline.png" alt="">
	      </div>  
	    </ng-container>```
	    
	```

* **Freddy Santacruz** (1) [488929](https://platzi.com/comentario/488929/) 

	Hola mi solucion fue con un ngSwitch para cada uno de los datos
	``` 
	    <<br />
	    <inputtype="text"placeholder="Buscar Amigo" [(ngModel)]="query" />
	    <br />
	    <b>Amigos</b>
	    <ng-container *ngFor="let user of friends | search:query; let i=index">
	      <div [ngSwitch]="user.estado">
	        <p *ngSwitchCase="'C'"><imgid="logo-online"src="assets/img/logo_live_online.png"alt="Logo Conectado"><arouterLink="/conversation/{{user.uid}}">
	          {{i}}. {{user.nick}} - {{user.email}}
	        </a></p>
	        <p *ngSwitchCase="'N'"><imgid="logo-offline"src="assets/img/logo_live_offline.png"alt="Logo No Conectado"><arouterLink="/conversation/{{user.uid}}">
	          {{i}}. {{user.nick}} - {{user.email}}
	        </a></p>
	        <p *ngSwitchCase="'O'"><imgid="logo-busy"src="assets/img/logo_live_busy.png"alt="Logo Ocupado"><arouterLink="/conversation/{{user.uid}}">
	          {{i}}. {{user.nick}} - {{user.email}}
	        </a></p>
	        <p *ngSwitchCase="'I'"><imgid="logo-away"src="assets/img/logo_live_away.png"alt="Logo Espera"><arouterLink="/conversation/{{user.uid}}">
	          {{i}}. {{user.nick}} - {{user.email}}
	        </a></p>
	      </div>  
	    </ng-container>>
	    
	```
	
	cada user tiene un estado con valores
	
	* C-> conectado
	* N-> desconectado
	* O-> Ocupado
	* I-> en espera (Inactivo)
	
	

* **jsballesteros** (1) [484824](https://platzi.com/comentario/484824/) 

	<input type=“text"placeholder=“Buscar amigo” [(ngModel)]=“query” />  
	<br/>  
	<b>Amigos</b>  
	<ng-container *ngFor=“let user of friends | search: query; let i = index”>  
	<div>  
	<a routerLink=”/conversation/{{user.uid}}">  
	<img class=“user-status” src=“assets/img/logo_live_{{user.status}}.png” alt=“Estatus”/>  
	{{i}}. {{user.nick}} - {{user.email}}  
	</a>  
	</div>  
	</ng-container>

* **ferchop2002** (1) [482297](https://platzi.com/comentario/482297/) 

	  1. Añadir status a interface user
	  2. Poner datos en status
	  3. cambiar en html al frente  
	<img src=“assets/img/logo_live_{{user.status}}.png” class=“icon_status” />
	  4. puse css en home.css
	
	

* **Mikel Goig** (1) [480448](https://platzi.com/comentario/480448/) 

	export interface User {  
	nick: string;  
	subnick?: string;  
	age?: number;  
	email: string;  
	friend: boolean;  
	status: Status;  
	uid: any;  
	}
	
	export enum Status {  
	online = ‘online’,  
	offline = ‘offline’,  
	away = ‘away’,  
	busy = ‘busy’,  
	}

* **Sigaweb** (1) [459511](https://platzi.com/comentario/459511/) 

	Añadiendo un estado a la clase y con un if verificando qué estado tiene el usuario

* **Luis Miguel Ramos Hernández** (1) [459396](https://platzi.com/comentario/459396/) 

	```
	    <ng-container [ngSwitch]="user.status">
	    	<img class="status-logo" *ngSwitchCase="0"id="main-logo" src="assets/img/logo_live_offline.png" alt="logo platzinger">                
	      <img class="status-logo" *ngSwitchCase="1"id="main-logo" src="assets/img/logo_live_online.png" alt="logo platzinger">                
	      <img class="status-logo" *ngSwitchCase="2"id="main-logo" src="assets/img/logo_live_away.png" alt="logo platzinger">                
	      <img class="status-logo" *ngSwitchCase="3"id="main-logo" src="assets/img/logo_live_busy.png" alt="logo platzinger">                        
	    </ng-container> 
	    
	```

* **sandovalgus** (1) [457792](https://platzi.com/comentario/457792/) 

	menu.component.htmt
	``` 
	    <divclass= "listado">
	        <arouterLink="/conversation/{{user.uid}}" >
	          <imgclass="userStatus"src="assets/img/logo_live_{{user.status}}.png" />
	          {{i}}. {{user.nick}} - {{user.email}}
	        </a>
	    
	      </div>
	    
	```
	
	interfaces/user.ts
	``` 
	    export interface User {
	        nick:string;
	        subnick?:string;
	        age:number;
	        email: string;
	        friend:boolean;
	        uid:any;
	        status: status;
	    }
	    
	    export type status = 'online' | 'offline' | 'busy' | 'away';
	    
	```
	
	styles.css
	``` 
	    .userStatus{
	        width: 18px;
	    }
	    .listado{
	        margin-left: 16px;
	    }
	    
	```

* **Jecsham Castillo** (1) [448935](https://platzi.com/comentario/448935/) 
	
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-604dce30-0876-4bf3-8863-6cf69508cbc6.jpg)

* **Octavio Gomez Romo** (1) [447072](https://platzi.com/comentario/447072/) 

	<img class=“user-status” src=“assets/img/logo_live_{{user.status}}.png” alt=“Estatus”/>

* **Spyderp** (1) [442885](https://platzi.com/comentario/442885/) 

	El resultado.  
	![platzinger_status_user.PNG](https://static.platzi.com/media/user_upload/platzinger_status_user-65f763db-5584-4b86-8341-b1a5d89d2cfe.jpg)
	
	luego verifique como lo hicieron lo demás usuario y fue idéntico

* **developerresol1** (1) [432632](https://platzi.com/comentario/432632/) 

	Agregue un nuevo atributo en la interfaz User llamado status tipo String y la imagen cambian según su estado: (online, offline, busy, away)
	``` 
	    <b>Amigos</b>
	    <ng-container *ngFor="let user of friends | search: query; let i = index">
	      <div>
	        <arouterLink="/conversation/{{user.uid}}">
	          <imgclass="status-icon"src="../../assets/img/logo_live_{{user.status}}.png">{{i+1}}) {{user.nick}} - {{user.email}}
	        </a>
	      </div>
	    </ng-container>
	    
	```

* **Emerson-Lirmi** (1) [422656](https://platzi.com/comentario/422656/) 

	En la clase home.component.html agregue esto:
	``` 
	    <inputtype="text"placeholder="Buscar amigo" [(ngModel)]="query">
	    <br />
	    <b>Amigos conectados y  desconectados:</b>
	    <ng-container *ngFor="let user of amigos | Search: query; let i = index">
	    	<div>
	    		<imgid="status-icon"src="assets/img/logo_live_{{user.status}}.png"alt="">
	    		<arouterLink="/conversation/{{user.uid}}">
	    		  {{i}}. {{user.nick}} - {{user.email}}
	    		</a>
	    	</div>
	    </ng-container>
	    
	```

* **adrianaanacona** (1) [415291](https://platzi.com/comentario/415291/) 

	Yo lo realice asi , me comentan como podria ser mejorado
	``` 
	    <p>
	      home works!
	    </p>
	    <input type="text" placeholder="buscar amigo" [(ngModel)]="query">
	    <br>
	    <p>Amigos</p>
	    <ng-container *ngFor='let user of friends | search : query ; let i = index'>
	      <div>
	        <img id='logo_status' src="assets/img/logo_live_{{user.status}}.png" alt="estado">
	    
	        <a routerLink='/conversation/{{user.uid}}'>
	          {{i}}
	          {{user.nick}} |
	          {{user.email}}
	        </a>
	      </div>
	    
	    </ng-container>
	    
	```
	
	![]()

* **jeisonsrz** (1) [415279](https://platzi.com/comentario/415279/) 

	home.component.css —>
	``` 
	    #imgStatus{
	      width: 50px;
	    }
	    
	    
	```
	
	home.component.html ---->
	``` 
	    <inputtype="text"placeholder="Buscar amigo" [(ngModel)]="query" />
	    <br/>
	    <br/>
	    <b>Amigos</b>
	    <ng-container *ngFor="let user of friends | search: query; let i = index">
	    
	      <div >
	        <arouterLink="/conversation/{{user.uid}}" >
	         <imgid="imgStatus"src="../../assets/img/logo_live_{{user.status}}.png">{{i}}. {{user.nick}} - {{user.email}}
	        </a>
	    
	      </div>
	    
	    </ng-container>
	    
	    
	```
	
	interfaces ---- user.ts —>
	``` 
	    export interface User {
	        nick: string;
	        subnick?: string;
	        age?: number;
	        email: string;
	        friend: boolean;
	        uid: any;
	        status: string;
	    }
	    
	    
	```
	
	user.service.ts ---->
	``` 
	    import { Injectable } from '@angular/core';
	    import {User} from '../interfaces/user';
	    
	    @Injectable({
	      providedIn: 'root'
	    })
	    export class UserService {
	      friends: User[];
	      constructor() {
	        letusuario1: User = {
	          nick: 'Eduardo',
	          age: 24,
	          email: 'ed@aoe.aoe',
	          friend: true,
	          uid: 1,
	          status: 'busy',
	        };
	        letusuario2: User = {
	          nick: 'Freddy',
	          age: 28,
	          email: 'fred@aoe.aoe',
	          friend: true,
	          uid: 2,
	          status: 'offline',
	        };
	        letusuario3: User = {
	          nick: 'Yuliana',
	          age: 18,
	          email: 'yuli@aoe.aoe',
	          friend: true,
	          uid: 3,
	          status: 'online',
	        };
	        letusuario4: User = {
	          nick: 'Ricardo',
	          age: 17,
	          email: 'rick@aoe.aoe',
	          friend: false,
	          uid: 4,
	          status: 'away',
	        };
	        letusuario5: User = {
	          nick: 'Marcos',
	          age: 30,
	          email: 'marcos@aoe.aoe',
	          friend: false,
	          uid: 5,
	          status: 'offline',
	        };
	        this.friends = [usuario1, usuario2, usuario3, usuario4, usuario5];
	    
	      }
	    
	      getFriends() {
	        returnthis.friends;
	      }
	    }
	    
	    
	```

* **Dany Ladino** (1) [413166](https://platzi.com/comentario/413166/) 

	Mi solución es algo así.
	``` 
	    <inputtype="text"placeholder="Buscar Amigo" [(ngModel)]="query" />
	    <br />
	    <b>Amigos</b>
	    <ng-container *ngFor="let user of friends | search: query; let i = index"> 
	    <div>
	    <arouterLink="/conversation/{{user.uid}}">
	      <imgid="main-logo"src="assets/img/logo_live_busy.png"alt="busy" *ngIf="i===0">
	      <imgid="main-logo"src="assets/img/logo_live_away.png"alt="away" *ngIf="i===1">
	      <imgid="main-logo"src="assets/img/logo_live_offline.png"alt="busy" *ngIf="i===2">
	      <imgid="main-logo"src="assets/img/logo_live_online.png"alt="busy" *ngIf="i===3">
	      <imgid="main-logo"src="assets/img/logo_live_online.png"alt="busy" *ngIf="i===4">
	        {{i}}. {{user.nick}} - {{user.email}}
	    </a>
	    </div>
	    </ng-container>
	    
	```

* **JuanCZ** (1) [408171](https://platzi.com/comentario/408171/) 

	En User.service.ts agregue un atributo a los usuarios llamado “Status”:
	``` 
	    letusuario1: User = {
	          nick: 'Eduardo',
	          age: 24,
	          email: 'ed@aoe.aoe',
	          status:3,     
	          friend: true,
	          uid: 2
	        };
	    
	```
	
	En home.component.html utilice un NgSwitch
	``` 
	    <ng-container *ngFor="let user of friends | search: query; let i = index">
	        <span [ngSwitch]="user.status">
	        <div  *ngSwitchCase = 1>
	          <imgclass="imgStatus"src="../../assets/img/logo_live_online.png"alt="Online">
	          <arouterLink = "/conversation/{{user.uid}}">
	          {{i+1}}.{{user.nick}}
	          </a>
	        </div>
	          <div *ngSwitchCase = 2>
	              <imgclass="imgStatus"src="../../assets/img/logo_live_offline.png"alt="">
	              <arouterLink = "/conversation/{{user.uid}}">
	              {{i+1}}.{{user.nick}}
	              </a>
	          </div>
	            <div *ngSwitchCase = 3>
	               <imgclass="imgStatus"src="../../assets/img/logo_live_busy.png"alt="">
	                <arouterLink = "/conversation/{{user.uid}}">
	                {{i+1}}.{{user.nick}}
	                </a>
	            </div>
	          <div *ngSwitchCase = 4>
	              <imgclass="imgStatus"src="../../assets/img/logo_live_away.png"alt="">
	                  <arouterLink = "/conversation/{{user.uid}}">
	                  {{i+1}}.{{user.nick}}
	                  </a>
	          </div>
	        </span>
	      </ng-container>
	    
	```

* **JuanCZ** (1) [408165](https://platzi.com/comentario/408165/) 

	En home.component.html utilice un NgSwitch  
	![](https://lh3.googleusercontent.com/CqvxYIzqddw2XUbE0kQ4AgP1dqaqshwKV4aj7KlX8o7yjR1U1hobXtkYsxC4K5o5AxIdjuA=s108)

* **JuanCZ** (1) [408163](https://platzi.com/comentario/408163/) 
	
	![https://lh3.googleusercontent.com/CqvxYIzqddw2XUbE0kQ4AgP1dqaqshwKV4aj7KlX8o7yjR1U1hobXtkYsxC4K5o5AxIdjuA=s108]()

* **JuanCZ** (1) [408156](https://platzi.com/comentario/408156/) 

	En (user.service.ts a todos agregue un campo “STATUS”
	``` 
	    letusuario: User = {
	        nick:'Camilo',
	        age:18,
	        email:'Juanc@gmail.com',
	        status: 1,
	        friend:true,
	        uid:1
	        } 
	    
	```
	
	En home.component.html utilice un NgSwitch:  
	![https://drive.google.com/file/d/1cJQReA8dSLLK7zDPSv7nLRBSC_e6o_3V/view](https://drive.google.com/file/d/1cJQReA8dSLLK7zDPSv7nLRBSC_e6o_3V/view)

* **JuanCZ** (1) [408153](https://platzi.com/comentario/408153/) 

	En (user.service.ts a todos agregue un campo “STATUS”
	``` 
	    letusuario: User = {
	        nick:'Camilo',
	        age:18,
	        email:'Juanc@gmail.com',
	        status: 1,
	        friend:true,
	        uid:1
	        } 
	    
	```
	
	En home.component.html utilice un NgSwitch:  
	![](https://drive.google.com/open?id=1cJQReA8dSLLK7zDPSv7nLRBSC_e6o_3V)

* **marczg21** (1) [401461](https://platzi.com/comentario/401461/) 
Hi

* **Poseidonihp** (1) [399216](https://platzi.com/comentario/399216/) 

	Mi solución no es la mas optima porque se puede cambiar de string a number, pero asi lo realice.Agregue la propiedad status a User en string
	``` 
	    export interface User {
	        nick : string ;
	        subnick? : string ;
	        age? : number ;
	        email : string ;
	        friend : boolean;
	        status : string ;
	        uid : any ;
	    
	    }
	    
	```
	
	agregue un image y en el src realizo la concatenación con la propiedad status.
	``` 
	      <div>
	      <img  id="home-status" src="assets/img/logo_live_{{user.status}}.png" alt="logo platzinger">
	      <a routerLink="/conversation/{{user.uid}}">
	       {{i}}-{{user.nick}} - {{user.email}}
	      </a> 
	    </div>
	    ```
	    
	```

* **Carlos Uriel de Jesus Sánchez González** (1) [397967](https://platzi.com/comentario/397967/) 

	user.service.ts
	``` 
	    import {Injectable} from '@angular/core';
	    import {User} from '../interfaces/user';
	    
	    @Injectable({
	      providedIn: 'root'
	    })
	    export class UserService {
	    
	      friends: User[];
	    
	      constructor() {
	        letusuario1: User = {
	          nick: 'Eduardo',
	          age: 24,
	          email: 'ed@aoe.aoe',
	          friend: true,
	          uid: 1,
	          status: 'online'
	        };
	        letusuario2: User = {
	          nick: 'Freddy',
	          age: 28,
	          email: 'fred@aoe.aoe',
	          friend: true,
	          uid: 2,
	          status: 'offline'
	        };
	        letusuario3: User = {
	          nick: 'Yuliana',
	          age: 18,
	          email: 'yuli@aoe.aoe',
	          friend: true,
	          uid: 3,
	          status: 'busy'
	        };
	        letusuario4: User = {
	          nick: 'Ricardo',
	          age: 17,
	          email: 'rick@aoe.aoe',
	          friend: false,
	          uid: 4,
	          status: 'away'
	        };
	        letusuario5: User = {
	          nick: 'Marcos',
	          age: 30,
	          email: 'marcos@aoe.aoe',
	          friend: false,
	          uid: 5,
	          status: 'online'
	        };
	        this.friends = [usuario1, usuario2, usuario3, usuario4, usuario5];
	      }
	    
	      getFriends() {
	        returnthis.friends;
	      }
	    
	    }
	    
	```
	
	home.component.css
	``` 
	    .ico-estatus{
	      width: 20px;
	      height: 20px;
	    }
	    
	```
	
	home.component.html
	``` 
	    <input type="text" placeholder="Buscar Amigo" [(ngModel)]="query"/>
	    <br/>
	    <b>Amigos</b>
	    <ng-container *ngFor="let user of friends | search: query; let i = index">
	      <div>
	        <img class="ico-estatus" src="assets/img/logo_live_{{user.status}}.png" alt="Estatus de Contacto"/>
	        <a routerLink="/conversation/{{user.uid}}">
	          {{i + 1}}. {{user.nick}} - {{user.email}}
	        </a>
	      </div>
	    </ng-container>
	    
	```
	
	user.ts
	``` 
	    export interface User {
	        nick: string;
	        subnick?: string;
	        age?: number;
	        email: string;
	        friend: boolean;
	        uid: any;
	        status: string;
	    }
	    
	```
	
	![Captura de pantalla 2018-10-09 a la\(s\) 14.35.13.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-10-09%20a%20la%28s%29%2014.35.13-186c6afb-936b-4940-aa28-ccf1df76aa70.jpg)

* **Abelardo Asensio Callol** (1) [397287](https://platzi.com/comentario/397287/) 

	Buena solución la de JuandDiegoLopez mas limpia y efectiva.

* **Duvan Carvajal** (1) [396441](https://platzi.com/comentario/396441/) 

	 **Lista de conectados y desconectados**
	``` 
	    <b>Conectados</b>
	    
	    <ng-container *ngFor=" let users of friends | search: query; let i = index; ">
	    
	      <div *ngIf="users.status">
	      <arouterLink="/chat/{{users.uid}}">
	    
	     {{i}}).  {{users.nick}} - {{users.email}}
	    
	        <imgid="status-icon"src="assets/img/logo_live_online.png">
	    
	      </a>
	      </div>
	    
	    </ng-container>
	    
	    <b>Desconectados</b>
	    <ng-container *ngFor=" let users of friends | search: query; let i = index; ">
	    
	      <div *ngIf="!users.status">
	        <arouterLink="/chat/{{users.uid}}">
	    
	          {{i}}).  {{users.nick}} - {{users.email}}
	    
	          <imgid="status-icon"src="assets/img/logo_live_offline.png">
	    
	        </a>
	      </div>
	    
	    </ng-container>
	    
	```

* **luis-batalla** (1) [369800](https://platzi.com/comentario/369800/) 

	No pude aplicar el NgIf por estado, agregue al interface una variable online : boolean.  
	Con ese parámetro intenté obtener los online/offline desde el formulario pero da error:
	``` 
	    <ng-container *ngIf="user.online=='true'">
	    
	```
	
	Ahora tengo dudas en que caso utilizar NgIf o un pipe… Me ayudan ?.

	* **luis-batalla** [369800] (2)

		solucione lo del online/offline usando dos container ngIf user.online y otro negado ngIf !user.online  
		Ahi obtuve los online y Offline, ahora no se como comparar Strings existe NgIf=“user.status==’'away” o debo recurrir unicamente a un pipe?

	* **luis-batalla** [369800] (2)

		solucionado!!!

	* **Julio J Yépez** [369800] (2)

		¡Bien hecho Luis!  
		Gracias por compartir la solución …

* **luis-batalla** (1) [40866](https://platzi.com/comentario/369800/) 
No pude aplicar el NgIf por estado, agregue al interface una variable online : boolean. Con ese parámetro intenté obtener los online/off...

	* **luis-batalla** [40866] (2)

		solucione lo del online/offline usando dos container ngIf user.online y otro negado ngIf !user.online  
		Ahi obtuve los online y Offline, ahora no se como comparar Strings existe NgIf=“user.status==’'away” o debo recurrir unicamente a un pipe?

## 0270. Implementando estilos en la pantalla de login [12772](https://platzi.com/clases/1340-angular-avanzado/12772-implementando-estilos-en-la-pantalla-de-login4846/)

### Descripción:


En el archivo html del componente podemos usar el atributo class como se hace normalmente para aplicar estilos a los elementos de un html estándar.  
Bootstrap tiene clases particulares para el manejo de layouts basados en un grid de 12 columnas además de una implementación sencilla pero completa de características de responsividad.

### Links:

* [CSS Gradient](https://cssgradient.io)

* [The ultimate CSS tools for web designers | CSSmatic](https://www.cssmatic.com)

### Comentarios:

* **Juan Diego Lopez Triana** (8) [371889](https://platzi.com/comentario/371889/) 

	Este es el degradado que se usó:
	``` 
	    background: rgba(235,233,249,1);
	    background: -moz-linear-gradient(left, rgba(235,233,249,1) 0%, rgba(216,208,239,1) 50%, rgba(206,199,236,1) 51%, rgba(193,191,234,1) 100%);
	    background: -webkit-gradient(left top, right top, color-stop(0%, rgba(235,233,249,1)), color-stop(50%, rgba(216,208,239,1)), color-stop(51%, rgba(206,199,236,1)), color-stop(100%, rgba(193,191,234,1)));
	    background: -webkit-linear-gradient(left, rgba(235,233,249,1) 0%, rgba(216,208,239,1) 50%, rgba(206,199,236,1) 51%, rgba(193,191,234,1) 100%);
	    background: -o-linear-gradient(left, rgba(235,233,249,1) 0%, rgba(216,208,239,1) 50%, rgba(206,199,236,1) 51%, rgba(193,191,234,1) 100%);
	    background: -ms-linear-gradient(left, rgba(235,233,249,1) 0%, rgba(216,208,239,1) 50%, rgba(206,199,236,1) 51%, rgba(193,191,234,1) 100%);
	    background: linear-gradient(to right, rgba(235,233,249,1) 0%, rgba(216,208,239,1) 50%, rgba(206,199,236,1) 51%, rgba(193,191,234,1) 100%);
	    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#ebe9f9', endColorstr='#c1bfea', GradientType=1 );
	    
	```

* **jeisonsrz** (5) [415288](https://platzi.com/comentario/415288/) 

	styles.css ---->
	``` 
	    /* You can add global styles to this file, and also import other style files */
	    
	    .avatarFrameOffline{
	      background: rgba(242,246,248,1);
	      background: -moz-linear-gradient(left, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
	      background: -webkit-gradient(left top, right top, color-stop(0%, rgba(242,246,248,1)), color-stop(50%, rgba(216,225,231,1)), color-stop(51%, rgba(181,198,208,1)), color-stop(100%, rgba(224,239,249,1)));
	      background: -webkit-linear-gradient(left, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
	      background: -o-linear-gradient(left, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
	      background: -ms-linear-gradient(left, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
	      background: linear-gradient(to right, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
	      filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f2f6f8', endColorstr='#e0eff9', GradientType=1 );
	      text-align: center;
	      padding: 5%;
	      border-radius: 10px;
	      border: 1px solid white;
	      display: inline-block;
	    
	    }
	    
	    
	    
	```
	
	login.component.html ----->
	``` 
	    <divclass="loginContainer">
	      
	      <divclass="container">
	       
	        <divclass="row justify-content-md-center">
	          
	          <divclass="col-md-3">
	          
	            <divclass="avatarFrameOffline">
	            
	              <img src="assets/img/generic_avatar.png"class="avatarImage img-fluid" />
	           
	            </div>
	         
	          </div>
	       
	        </div>
	     
	      </div>
	      
	    </div>
	    
	    
	```
	
	login.component.css —>
	``` 
	    .loginContainer{
	        background-image: url('/assets/img/msnbg.jpg');
	        background-size: contain;
	        background-repeat: no-repeat;
	    
	    }
	    
	    
	    
	    
	```

* **luisangeldev** (2) [502042](https://platzi.com/comentario/502042/) 

	Le puse este estilo y el background del login queda bien ajustado 😄
	``` 
	    .loginContainer{
	        background-image: url('/assets/img/msnbg.jpg');
	        background-size: cover;
	        background-repeat: no-repeat;
	    }
	    
	```

	* **isdaimonos** [502042] (1)

		Es también me funciono y el otro no, alguien nos explique

* **bryanmedina** (1) [671274](https://platzi.com/comentario/671274/) 

	Cuando coloco el img-fluid  
	<img src=“assets/img/generic_avatar.png” class=“avatarImage img-fluid”>  
	la imagen no cambia se mantiene igual

* **miguelangelloor96** (1) [588613](https://platzi.com/comentario/588613/) 

	disculpa cual es el plugin de VS Code que nos da la sugerencias de las clases de bootstrap, se ve muy útil

	* **Miguel Angel Flores** [588613] (3)
![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-90d760fa-a728-4138-a87e-988c9fdc4ea7.jpg)
		
		Yo ocupe esta y funciona bien 😄

* **mariolyvarela_** (1) [584691](https://platzi.com/comentario/584691/) 

	Buenas tardes, cada vez que voy a agregar un estilo css simplemente como este:  
	.loginContainer{  
	background-image: url(’/assets/img/msnbg.jpg’);  
	}
	
	me sale este error y no he podido solucionarlo
	
	ERROR in ./src/app/login/login.component.sass  
	Module build failed (from ./node_modules/sass-loader/lib/loader.js):
	
	Tiene que ver que al principio elegí usar sass en vez de css?

	* **Diego Alexander Forero Higuera (Platzi)** [584691] (1)

		Si, estas usando sass, por eso trata de hacer el build para convertir sass a css, pero el error puede ser porque hay algo mal en la sintaxis del archivo sass, puedes compartir el stack trace completo del error.

* **JorgeLopez88** (1) [577662](https://platzi.com/comentario/577662/) 

	El **img-fluid** no me funciona, no da ninguna clase de error ni nada, alguna idea de por que puede ser.

	* **bryanmedina** [577662] (1)

		me pasa igual

* **Diego Mauricio Mejía Ospina** (1) [515774](https://platzi.com/comentario/515774/) 

	```
	    .btn-primary {
	        background: rgba(179,220,237,1);
	        background: -moz-radial-gradient(center, ellipse cover, rgba(179,220,237,1) 0%, rgba(41,184,229,1) 50%, rgba(188,224,238,1) 100%);
	        background: -webkit-gradient(radial, center center, 0px, center center, 100%, color-stop(0%, rgba(179,220,237,1)), color-stop(50%, rgba(41,184,229,1)), color-stop(100%, rgba(188,224,238,1)));
	        background: -webkit-radial-gradient(center, ellipse cover, rgba(179,220,237,1) 0%, rgba(41,184,229,1) 50%, rgba(188,224,238,1) 100%);
	        background: -o-radial-gradient(center, ellipse cover, rgba(179,220,237,1) 0%, rgba(41,184,229,1) 50%, rgba(188,224,238,1) 100%);
	        background: -ms-radial-gradient(center, ellipse cover, rgba(179,220,237,1) 0%, rgba(41,184,229,1) 50%, rgba(188,224,238,1) 100%);
	        background: radial-gradient(ellipse at center, rgba(179,220,237,1) 0%, rgba(41,184,229,1) 50%, rgba(188,224,238,1) 100%);
	        filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#b3dced', endColorstr='#bce0ee', GradientType=1 );
	    }```
	    
	    
	    
	```

* **Jenniffer Helena Alvarez Puello** (1) [510912](https://platzi.com/comentario/510912/) 

	excelente reto

* **Fredy Abel Huanca Torres** (1) [438662](https://platzi.com/comentario/438662/) 

	 **login.component.css**
	
	`.loginContainer{ background-image: url('/assets/img/msnbg.jpg'); background-size: contain; background-repeat: no-repeat; }`

* **Carlos Uriel de Jesus Sánchez González** (1) [398046](https://platzi.com/comentario/398046/) 

	login.component.html
	``` 
	    <divclass="loginContainer">
	      <divclass="container">
	        <divclass="row justify-content-md-center">
	          <divclass="col-md-3">
	            <divclass="avatarFrameOffline">
	              <img src="assets/img/generic_avatar.png"class="avatarImage img-fluid" />
	            </div>
	          </div>
	        </div>
	      </div>
	    </div>
	    
	```
	
	login.component.css
	``` 
	    .loginContainer{
	      background-image: url('/assets/img/msnbg.jpg');
	      -webkit-background-size: cover;
	      background-size: cover;
	      background-repeat: no-repeat;
	    }
	    
	```
	
	styles.css
	``` 
	    /* You can add global styles to this file, and also import other style files */
	    .avatarFrameOffline{
	      background: rgba(235,233,249,1);
	      background: -moz-linear-gradient(left, rgba(235,233,249,1) 0%, rgba(216,208,239,1) 50%, rgba(206,199,236,1) 51%, rgba(193,191,234,1) 100%);
	      background: -webkit-gradient(left top, right top, color-stop(0%, rgba(235,233,249,1)), color-stop(50%, rgba(216,208,239,1)), color-stop(51%, rgba(206,199,236,1)), color-stop(100%, rgba(193,191,234,1)));
	      background: -webkit-linear-gradient(left, rgba(235,233,249,1) 0%, rgba(216,208,239,1) 50%, rgba(206,199,236,1) 51%, rgba(193,191,234,1) 100%);
	      background: -o-linear-gradient(left, rgba(235,233,249,1) 0%, rgba(216,208,239,1) 50%, rgba(206,199,236,1) 51%, rgba(193,191,234,1) 100%);
	      background: -ms-linear-gradient(left, rgba(235,233,249,1) 0%, rgba(216,208,239,1) 50%, rgba(206,199,236,1) 51%, rgba(193,191,234,1) 100%);
	      background: linear-gradient(to right, rgba(235,233,249,1) 0%, rgba(216,208,239,1) 50%, rgba(206,199,236,1) 51%, rgba(193,191,234,1) 100%);
	      filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#ebe9f9', endColorstr='#c1bfea', GradientType=1 );
	      text-align: center;
	      padding: 5%;
	      border-radius: 10px;
	      -webkit-border-radius: 10px;
	      border: 1px solid white;
	      display: inline-block;
	    }
	    
	```

* **mariolyvarela_** (1) [58966](https://platzi.com/comentario/584691/) 
Buenas tardes, cada vez que voy a agregar un estilo css simplemente como este: .loginContainer{ background-image: url(’/assets/img/msnbg....

	* **Diego Alexander Forero Higuera (Platzi)** [58966] (1)

		Si, estas usando sass, por eso trata de hacer el build para convertir sass a css, pero el error puede ser porque hay algo mal en la sintaxis del archivo sass, puedes compartir el stack trace completo del error.

## 0280. Terminando de implementar los estilos de nuestra pantalla de login [12773](https://platzi.com/clases/1340-angular-avanzado/12773-terminando-de-implementar-los-estilos-de-nuestra-p/)

### Descripción:


Cuando queremos que las clases que estamos definiendo estén disponibles en todo el proyecto y no sólo en la pantalla del componente actual, tendremos que definirlas en el archivo styles.css en la raíz del proyecto y no sólo en el css del componente.

### Comentarios:

* **Jesús Auriol Villamarín Ortiz** (10) [465535](https://platzi.com/comentario/465535/) 

	Bueno veo innecesario crear .marto15 y .marbo15. Ya que si estaremos usando bootstrap podemos usar clases que ya están definidas tales como:
	
	* mt = margin top
	* mb = margin bottom
	* ml = margin left
	* mr = margin right
	* my = es margen para top y bottom
	* mx = es margen para left y right
	
	
	
	En mi caso hice uso de my-3
	
	Pueden encontrar mas en esta liga [Bootstrap](https://getbootstrap.com/docs/4.0/utilities/spacing/)

	* **Jenniffer Helena Alvarez Puello** [465535] (1)

		gracias

* **Christian Michelle Torres Martínez** (9) [615926](https://platzi.com/comentario/615926/) 
	
	![platzinger login.png](https://static.platzi.com/media/user_upload/platzinger%20login-2018b05a-27af-407b-a1bf-ce1211c11eaa.jpg)

* **Wilson Fabian Pérez Sucuzhañay** (7) [367398](https://platzi.com/comentario/367398/) 

	Algo así de verde era el de msn jaja no lo recuerdo bien.
	
	![Captura de pantalla 2018-08-29 a la\(s\) 17.09.07.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-08-29%20a%20la%28s%29%2017.09.07-8b9993b9-0806-4f33-a966-4d4835151188.jpg)

	* **ricardocelis (Platzi)** [367398] (3)

		Excelente!

* **Gonzalo Muñoz** (4) [680927](https://platzi.com/comentario/680927/) 

	Bootstrap ya trae clases como esas auxiliares:
	
	center-text
	
	Y la de los márgenes  
	mt-x : margin top de 1 a 5  
	mb-x: margin bottom de 1 a 5  
	ml-x: margin left  
	mr-x margin right

	* **Carlos Alfonso Montoya Cruz** [680927] (1)

		Si, las clases que están implementadas por bootstrap son:
		
		* text-center (text-left, text-justify, text-right)
		* Margin: m-x (mt-x, mb-x, mr-x, ml-x)
		* Padding: p-x (pt-x, pb-x, pr-x, pl-x)
		
		

	* **YojanPardo** [680927] (1)

		mx-x: margen en el eje x (horizontal)  
		my-x: margen en el eje y (vertical)  
		tambien van de 1-5

* **Juan Carlos Felizzola Vega** (4) [384631](https://platzi.com/comentario/384631/) 

	 **Nos faltó cambiar el título:**
	``` 
	    <divclass="text-center">
	    	<h3 *ngIf="operation == 'login'">Iniciar sesión</h3>
	    	<h3 *ngIf="operation == 'register'">Registrarte</h3>
	    </div>
	    
	```
	
	Y en vez de usar la clase center que estamos creando, podemos usar la clase `text-center` de **Bootstrap**.  
	También en vez de usar `marto15` y `marbo15`, podemos usar las clases `mt-3` y `mb-3` que sería iguall a `margin-top: 16px` y `margin-bottom: 16px`

* **carlosextra1** (3) [368024](https://platzi.com/comentario/368024/) 

	he aquí el resultado!!!  
	![](http://www.extrasistemas.com/Platzi/Angular/login.PNG)

* **jehisonorostegui** (2) [632505](https://platzi.com/comentario/632505/) 
	
	![Captura de Pantalla 2019-06-30 a la\(s\) 1.28.03 a. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202019-06-30%20a%20la%28s%29%201.28.03%20a.%20m.-77105535-6183-42cd-89f8-f7d111e99b54.jpg)

	* **Briggs** [632505] (1)

		Amigo me gusto el estilo que le pusiste al boton, podrias compartir el css?

	* **Juan Manuel Martínez Ortiz** [632505] (1)

		```
		    .btn {
		        background: rgb(207,207,207);
		        background: linear-gradient(0deg, rgba(207,207,207,1) 0%, rgba(255,255,255,1) 100%);
		        text-align: center;
		        border: 1px solid gray;
		        display: inline-block;
		    }
		    
		```

* **Miguel Castillo Cortes** (2) [549186](https://platzi.com/comentario/549186/) 
	
	![login.PNG](https://static.platzi.com/media/user_upload/login-15adb229-b1b2-454f-8c20-f44e0acbc3e0.jpg)

* **Adrian Camilo Caminos** (2) [483752](https://platzi.com/comentario/483752/) 

	la hice mientras ya la volvemos de nosotros![Screen Shot 2019-01-18 at 11.55.36 PM.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202019-01-18%20at%2011.55.36%20PM-3dcb1ad6-2903-467a-be01-42c744a0b008.jpg)

* **Luis Miguel Ramos Hernández** (2) [459491](https://platzi.com/comentario/459491/) 
	
	![Sin título.png](https://static.platzi.com/media/user_upload/Sin%20t%C3%ADtulo-5f09bdf9-16a5-46ef-9533-bfb88cd43159.jpg)

* **Spyderp** (2) [442939](https://platzi.com/comentario/442939/) 
	
	![login.PNG](https://static.platzi.com/media/user_upload/login-5e14888c-c8b5-4c77-bdb1-e53d441428aa.jpg)
	
	Más que agregar nuevo código css hice ajustes al nivel html  
	![codigo.PNG](https://static.platzi.com/media/user_upload/codigo-a486bbc2-1060-4147-9ea1-62330cb2ec9e.jpg)

* **jeisonsrz** (2) [415292](https://platzi.com/comentario/415292/) 

	styles.css ---->
	``` 
	    /* You can add global styles to this file, and also import other style files */
	    
	    .avatarFrameOffline{
	      background: rgba(242,246,248,1);
	      background: -moz-linear-gradient(left, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
	      background: -webkit-gradient(left top, right top, color-stop(0%, rgba(242,246,248,1)), color-stop(50%, rgba(216,225,231,1)), color-stop(51%, rgba(181,198,208,1)), color-stop(100%, rgba(224,239,249,1)));
	      background: -webkit-linear-gradient(left, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
	      background: -o-linear-gradient(left, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
	      background: -ms-linear-gradient(left, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
	      background: linear-gradient(to right, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
	      filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f2f6f8', endColorstr='#e0eff9', GradientType=1 );
	      text-align: center;
	      padding: 5%;
	      border-radius: 10px;
	      border: 1px solid white;
	      display: inline-block;
	    
	    }
	    
	    .center{
	      text-align: center !important;
	    
	    }
	    
	    .marto15{
	      margin-top: 15px;
	    }
	    
	    .marbo15{
	      margin-bottom: 5px;
	    }
	    
	    .btn-primary{
	      background-color: limegreen;
	    }
	    
	    
	```
	
	login.component.ts ----->
	``` 
	    import { Component, OnInit } from '@angular/core';
	    
	    @Component({
	      selector: 'app-login',
	      templateUrl: './login.component.html',
	      styleUrls: ['./login.component.css']
	    })
	    export class LoginComponent implements OnInit {
	    
	      operation: string = 'login';
	      constructor() { }
	    
	      ngOnInit() {
	      }
	    
	    }
	    
	```
	
	login.component.html —>
	``` 
	    <divclass="loginContainer">
	    
	      <divclass="container">
	    
	        <divclass="row justify-content-md-center">
	    
	          <divclass="col-md-3">
	    
	            <divclass="avatarFrameOffline marto15 marbo15">
	    
	              <imgsrc="assets/img/generic_avatar.png"class="avatarImageimg-fluid" />
	    
	            </div>
	    
	          </div>
	    
	        </div>
	    
	        <divclass="row justify-content-md-center">
	    
	          <divclass="col-md-6">
	            <divclass="center">
	    
	              <h3>Iniciar Sesión</h3>
	    
	            </div>
	            <p *ngIf="operation == 'register'">Ya tienes cuenta? Has <a (click)="operation = 'login'" >Login</a></p>
	            <p *ngIf="operation == 'login'"> No tienes cuenta? <a (click)="operation = 'register'" >Registrate</a></p>
	    
	            <divclass="borderedContainer">
	    
	              <inputclass="form-control marbo15"type="email"placeholder="Ingrese su Email">
	              <inputclass="form-control marbo15"type="password"placeholder="Ingrese su contraseña">
	              <input *ngIf="operation == 'register'"class="form-control marbo15"type="text"placeholder="Ingrese su Nick">
	    
	            </div>
	    
	            <divclass="center marto15">
	    
	              <a *ngIf="operation == 'login'"class="btn btn-primary">Iniciar Sesión</a>
	              <a *ngIf="operation == 'register'"class="btn btn-primary">Registrarme</a>
	    
	            </div>
	    
	          </div>
	    
	        </div>
	    
	      </div>
	    
	    </div>
	    
	    
	```

* **Jeffry Davila** (2) [389852](https://platzi.com/comentario/389852/) 

	El azul se ve bien.  
	![Segunda.PNG](https://static.platzi.com/media/user_upload/Segunda-193498eb-8b30-47f1-a303-0d04db493ec7.jpg)

* **rodspek** (2) [381675](https://platzi.com/comentario/381675/) 
	
	![Reto1AAdv.JPG](https://static.platzi.com/media/user_upload/Reto1AAdv-8e391493-e126-456e-ab6e-fb8a25789ba2.jpg)

* **Erik Ricardo Sánchez Pérez** (1) [1027135](https://platzi.com/comentario/1027135/) 

	Mi aporte 😄  
	![Screen Shot 2020-03-09 at 12.42.11.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202020-03-09%20at%2012.42.11-4ac2168a-3544-4779-93be-76f490767cef.jpg)

* **Adrian Alberto Casas Lopez** (1) [966195](https://platzi.com/comentario/966195/) 

	Va mi aporte:
	
	Login:  
	![IniciarSesión.jpg](https://static.platzi.com/media/user_upload/IniciarSesi%C3%B3n-21909098-a5e7-41f0-9c85-d2b9f9c8f78e.jpg)
	
	Registro:  
	![Registro.jpg](https://static.platzi.com/media/user_upload/Registro-df660d24-642f-42f4-bd8e-3cd55700d073.jpg)

* **David Alejandro Mosquera Moreno** (1) [856010](https://platzi.com/comentario/856010/) 
	
	![msn.png](https://static.platzi.com/media/user_upload/msn-8b34c2b0-fac4-4b3e-b4b1-05b062f947ec.jpg)

* **caprilespe** (1) [793735](https://platzi.com/comentario/793735/) 
	
	![botonLogin.PNG](https://static.platzi.com/media/user_upload/botonLogin-56f434b7-237e-4ec6-b758-de96d85da016.jpg)

* **fernandojavierespanacordoba** (1) [754630](https://platzi.com/comentario/754630/) 
	
	![2019-09-25_230739.png](https://static.platzi.com/media/user_upload/2019-09-25_230739-b3a1dd80-42be-44ff-9f89-278fb1d1e4e3.jpg)

* **Briggs** (1) [637690](https://platzi.com/comentario/637690/) 

	He aprendido muchas cosas sobre angular en este curso, gracias!  
	![](https://cdn.discordapp.com/attachments/451359497546498051/596414904865521746/unknown.png)  
	![](https://cdn.discordapp.com/attachments/451359497546498051/596415069147889677/unknown.png)

* **Emilio Ian Camacho Mejia** (1) [607761](https://platzi.com/comentario/607761/) 
	
	![messenger.png](https://static.platzi.com/media/user_upload/messenger-14cf7778-ae5c-4663-8d97-01c00876e9d8.jpg)

* **citux** (1) [542157](https://platzi.com/comentario/542157/) 

	interesante me parecio mas facil aplicar los css que ya tenemos de bootstrap

* **RomarioEstradaFlorez** (1) [509757](https://platzi.com/comentario/509757/) 

	El **important!** es para que las propiedades de las clases tengan relevancia entre las propiedades de otras clases, pero hay que saberlo usar por que o si no se vuelve cuchillo de doble filo, tambien se puede usar para sobreescribir clases propias de un framework.

* **Sigaweb** (1) [498093](https://platzi.com/comentario/498093/) 

	Esta clase es solo css

* **ferchop2002** (1) [483929](https://platzi.com/comentario/483929/) 

	Me acuerdo que tiene algo de verde por ahi.  
	![Screen Shot 2019-01-19 at 09.50.30.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202019-01-19%20at%2009.50.30-78f692f3-07ae-448c-bb83-feeec6701c3f.jpg)

* **Adrian Camilo Caminos** (1) [483749](https://platzi.com/comentario/483749/) 

	asi os he plasmado![Screen Shot 2019-01-18 at 11.52.13 PM.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202019-01-18%20at%2011.52.13%20PM-2db9779c-283f-48b0-a3ae-eafe9d060026.jpg)

* **Jecsham Castillo** (1) [448977](https://platzi.com/comentario/448977/) 

	Las clases `center`, `marto` y `marbo` en bootstrap equivalen a `text-center`, `mt-` y `mb-`, aunque para aplicar margen arriba y abajo podemos usar `my-`que aplica margen en el eje Y. Ejemplo: `my-5`

* **Dany Ladino** (1) [433626](https://platzi.com/comentario/433626/) 
	
	![Captura de pantalla 2018-11-27 a la\(s\) 9.27.51 a. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-11-27%20a%20la%28s%29%209.27.51%20a.%20m.-c347bef8-d002-44c7-811b-fd78a56847b5.jpg)

* **Poseidonihp** (1) [399820](https://platzi.com/comentario/399820/) 

	Cuando nos comunicábamos con MSN y utilizábamos emojis raros  
	![msn1.PNG](https://static.platzi.com/media/user_upload/msn1-92274668-d70c-489b-ae38-92927cc44922.jpg)

* **Carlos Uriel de Jesus Sánchez González** (1) [398078](https://platzi.com/comentario/398078/) 

	login.component.html
	``` 
	    <div class="loginContainer">
	      <div class="container">
	        <div class="row justify-content-md-center">
	          <div class="col-md-3">
	            <div class="avatarFrameOffline mt-3 mb-3">
	              <img src="assets/img/generic_avatar.png"class="avatarImage img-fluid"/>
	            </div>
	          </div>
	        </div>
	        <div class="row justify-content-md-center">
	          <div class="col-md-6">
	            <div class="text-center">
	              <h3>Iniciar sesi&oacute;n</h3>
	            </div>
	            <p *ngIf="operation == 'register'">Ya tienes cuenta? Has <a class="text-primary" (click)="operation= 'login'">Login</a>
	            </p>
	            <p *ngIf="operation == 'login'">No tienes cuenta? <a class="text-primary" (click)="operation='register'">Registrarse</a>
	            </p>
	            <div class="border">
	              <div class="mr-2 ml-2 mt-2 mb-2">
	                <input type="email" placeholder="Ingresa tu E-mail"class="form-control"/>
	                <br/>
	                <input type="password" placeholder="Ingresa tu Contrase&ntilde;a"class="form-control"/>
	                <br/>
	                <input *ngIf="operation == 'register'"type="text" placeholder="Ingresa tu Nick"class="form-control"/>
	              </div>
	            </div>
	            <div class="text-center mt-2">
	              <a *ngIf="operation == 'login'"class="btn btn-success">IniciarSesi&oacute;n</a>
	              <a *ngIf="operation == 'register'"class="btn btn-success">Registrarme</a>
	            </div>
	          </div>
	        </div>
	      </div>
	    </div>
	    
	```
	
	login.component.ts
	``` 
	    import {Component, OnInit} from '@angular/core';
	    
	    @Component({
	      selector: 'app-login',
	      templateUrl: './login.component.html',
	      styleUrls: ['./login.component.css']
	    })
	    export class LoginComponent implements OnInit {
	      operation: string;
	    
	      constructor() {
	        this.operation = 'login';
	      }
	    
	      ngOnInit() {
	      }
	    
	    }
	    
	```
	
	login.component.css
	``` 
	    .loginContainer{
	      background-image: url('/assets/img/msnbg.jpg');
	      -webkit-background-size: cover;
	      background-size: cover;
	      background-repeat: no-repeat;
	    }
	    
	```
	
	styless.css
	``` 
	    /* You can add global styles to this file, and also import other style files */
	    .avatarFrameOffline{
	      background: rgba(235,233,249,1);
	      background: -moz-linear-gradient(left, rgba(235,233,249,1) 0%, rgba(216,208,239,1) 50%, rgba(206,199,236,1) 51%, rgba(193,191,234,1) 100%);
	      background: -webkit-gradient(left top, right top, color-stop(0%, rgba(235,233,249,1)), color-stop(50%, rgba(216,208,239,1)), color-stop(51%, rgba(206,199,236,1)), color-stop(100%, rgba(193,191,234,1)));
	      background: -webkit-linear-gradient(left, rgba(235,233,249,1) 0%, rgba(216,208,239,1) 50%, rgba(206,199,236,1) 51%, rgba(193,191,234,1) 100%);
	      background: -o-linear-gradient(left, rgba(235,233,249,1) 0%, rgba(216,208,239,1) 50%, rgba(206,199,236,1) 51%, rgba(193,191,234,1) 100%);
	      background: -ms-linear-gradient(left, rgba(235,233,249,1) 0%, rgba(216,208,239,1) 50%, rgba(206,199,236,1) 51%, rgba(193,191,234,1) 100%);
	      background: linear-gradient(to right, rgba(235,233,249,1) 0%, rgba(216,208,239,1) 50%, rgba(206,199,236,1) 51%, rgba(193,191,234,1) 100%);
	      filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#ebe9f9', endColorstr='#c1bfea', GradientType=1 );
	      text-align: center;
	      padding: 5%;
	      border-radius: 10px;
	      -webkit-border-radius: 10px;
	      border: 1px solid white;
	      display: inline-block;
	    }
	    
	```
	
	![Captura de pantalla 2018-10-09 a la\(s\) 17.30.53.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-10-09%20a%20la%28s%29%2017.30.53-f3d52581-ab41-489f-b4d7-cba50a6423c6.jpg)  
	![Captura de pantalla 2018-10-09 a la\(s\) 17.31.09.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-10-09%20a%20la%28s%29%2017.31.09-d614bb3e-e78a-4bd9-b08d-6355261b28cc.jpg)

	* **Carlos Alberto García Rosales** [398078] (1)

		tu si que lo quieres replicar exacto esta muy bueno!!! 😮

* **Duvan Carvajal** (1) [396587](https://platzi.com/comentario/396587/) 

	cuanta nostalgia con este curso…  
	![2018-10-07 \(1\).png](https://static.platzi.com/media/user_upload/2018-10-07%20%281%29-a5ce4ff8-fe9d-423d-af13-8d04bd23be9c.jpg)

* **Anthony Gonzalez** (1) [378880](https://platzi.com/comentario/378880/) 

	**Bootstrap 4** trae consigo **clases auxiliares** para ayudarnos, la utilidades de [Espaciado](https://getbootstrap.com/docs/4.1/utilities/spacing/) que nos permiten manipular fácilmente margin y padding , y la utilidades de [texto](https://getbootstrap.com/docs/4.1/utilities/text/)

* **Julio J Yépez** (1) [370364](https://platzi.com/comentario/370364/) 

	Llegaron a haber varias versiones en la apariencia del MSN messenger, incluso luego pasó a llamarse Windows Live Messanger.
	
	![image.jpg](https://static.platzi.com/media/user_upload/image-315b183b-ba7f-4c34-b6d8-370856a89e57.jpg) ![Msnmessenger-logonscreen-xp.png](https://static.platzi.com/media/user_upload/Msnmessenger-logonscreen-xp-a773c3c0-42e7-4447-ac39-fdc52829d8e8.jpg)

## 0290. Implementando estilos en el navbar [12774](https://platzi.com/clases/1340-angular-avanzado/12774-implementando-estilos-en-el-navbar/)

### Descripción:


Con respecto a la navegación, particularmente el navbar, el patrón más común es que use un estilo `display: fixed` con el fin de que, tanto el logo de la aplicación como los enlaces a las diferentes pantallas, siempre estén visibles aunque el usuario haga scroll en el contenido.

### Comentarios:

* **Carlos Uriel de Jesus Sánchez González** (8) [398492](https://platzi.com/comentario/398492/) 

	menu.component.html
	``` 
	    <divid="menuConteiner">
	      <divclass="item branding" routerLink="/home">
	        <img id="main-logo" src="assets/img/logo_live.png" alt="Logo de Platzinger"/>
	        Platzinger
	      </div>
	      <divclass="item" routerLink="/profile">
	        Profile
	      </div>
	    </div>
	    
	```
	
	menu.component.css
	``` 
	    #main-logo {
	      width: 40px;
	    }
	    
	    #menuConteiner {
	      background: #8dd2f3;
	      background: -moz-linear-gradient(top, #8dd2f3 0%, #43b5eb 50%, #39abe1 51%, #3cb2ea 100%);
	      background: -webkit-linear-gradient(top, #add2f3 0%, #43b5eb 50%, #39abe1 51%, #3cb2ea 100%);
	      background: linear-gradient(to bottom, #8dd2f3 0%, #43b5eb 50%, #39abe1 51%, #3cb2ea 100%);
	      -ms-filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#8dd2f3', endColorstr='#3cb2ea', GradientType=0);
	      filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#8dd2f3', endColorstr='#3cb2ea', GradientType=0);
	      -webkit-box-shadow: 0px15px15px -4pxrgba(0, 0, 0, 0.24);
	      -moz-box-shadow: 0px15px15px -4pxrgba(0, 0, 0, 0.24);
	      box-shadow: 0px15px15px -4pxrgba(0, 0, 0, 0.24);
	      position: fixed;
	      width: 100%;
	      z-index: 9;
	      height: 56px;
	      top: 0px;
	    }
	    
	    .branding {
	      padding: 5px!important;
	      border-top: none !important;
	      border-right: none !important;
	    }
	    
	    #menuConteiner > .item {
	      padding: 15px;
	      color: white;
	      cursor: pointer;
	      display: inline-block;
	    }
	    
	```
	
	styles.css
	``` 
	    /* You can add global styles to this file, and also import other style files */
	    .avatarFrameOffline {
	      background: rgba(235, 233, 249, 1);
	      background: -moz-linear-gradient(left, rgba(235, 233, 249, 1) 0%, rgba(216, 208, 239, 1) 50%, rgba(206, 199, 236, 1) 51%, rgba(193, 191, 234, 1) 100%);
	      background: -webkit-gradient(left top right top, color-stop(0%, rgba(235, 233, 249, 1)), color-stop(50%, rgba(216, 208, 239, 1)), color-stop(51%, rgba(206, 199, 236, 1)), color-stop(100%, rgba(193, 191, 234, 1)));
	      background: -webkit-linear-gradient(left, rgba(235, 233, 249, 1) 0%, rgba(216, 208, 239, 1) 50%, rgba(206, 199, 236, 1) 51%, rgba(193, 191, 234, 1) 100%);
	      background: -o-linear-gradient(left, rgba(235, 233, 249, 1) 0%, rgba(216, 208, 239, 1) 50%, rgba(206, 199, 236, 1) 51%, rgba(193, 191, 234, 1) 100%);
	      background: -ms-linear-gradient(left, rgba(235, 233, 249, 1) 0%, rgba(216, 208, 239, 1) 50%, rgba(206, 199, 236, 1) 51%, rgba(193, 191, 234, 1) 100%);
	      background: linear-gradient(to right, rgba(235, 233, 249, 1) 0%, rgba(216, 208, 239, 1) 50%, rgba(206, 199, 236, 1) 51%, rgba(193, 191, 234, 1) 100%);
	      filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ebe9f9', endColorstr='#c1bfea', GradientType=1);
	      text-align: center;
	      padding: 5%;
	      border-radius: 10px;
	      -webkit-border-radius: 10px;
	      border: 1px solid white;
	      display: inline-block;
	    }
	    
	    .generalContent {
	      margin-top: 56px;
	    }
	    
	```
	
	app.component.html
	``` 
	    <app-menu></app-menu>
	    <divclass="generalContent">
	      <router-outlet></router-outlet>
	    </div>
	    
	```
	
	![Captura de pantalla 2018-10-10 a la\(s\) 10.57.41.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-10-10%20a%20la%28s%29%2010.57.41-8daf26ce-93bb-43d2-9348-513a3afb79d1.jpg)

	* **Matias Cabido** [398492] (1)

		background: -webkit-gradient(left top right top, color-stop(0%, rgba(235, 233, 249, 1)), color-stop(50%, rgba(216, 208, 239, 1)), color-stop(51%, rgba(206, 199, 236, 1)), color-stop(100%, rgba(193, 191, 234, 1)));
		
		No funciona!!

* **carlos Alberto Bedoya Ramirez** (4) [394723](https://platzi.com/comentario/394723/) 

	De nuevo, EL CODIGO QUE SUBEN NO CONTIENE NADA DE LO MUESTRAN EN EL VIDEO…

* **luis-batalla** (2) [396461](https://platzi.com/comentario/396461/) 

	@Eduardo, depues de implementar bootstrap funciona OK, el problema es cuando intento utilizar dropdown, no da error en la consola. Pero no funciona cuando hago click para que despliegue el menu, alguna idea ?

	* **luis-batalla** [396461] (1)

		solucionado, problema de orden de carga de jquery

* **Ezequiel-Fabbroni** (2) [49969](https://platzi.com/comentario/474061/) 
¿No seria mas conveniente incluir la clase **generalContent ** dentro de el css de app antes que en styles.css ?

* **Juan Antonio Campoy Lira** (1) [910225](https://platzi.com/comentario/910225/) 
	
	![boton.jpg.png](https://static.platzi.com/media/user_upload/boton.jpg-fdf657ad-3bd0-4fa1-84fa-67948502809c.jpg)
	
	Mi Aporte

* **David Alejandro Mosquera Moreno** (1) [856707](https://platzi.com/comentario/856707/) 
	
	![msn.png](https://static.platzi.com/media/user_upload/msn-6941034e-3219-42bf-b0f8-f02e3d6da23c.jpg)

* **Damian Spizzirri** (1) [638101](https://platzi.com/comentario/638101/) 

	Esta bien poner las medidas en pixeles? Me hace ruido eso, se podria hacer lo mismo usando porcentajes o em? Tiene sentido lo que planteo o por alguna razon esta bien asi? Que opinan?

	* **Diego Alexander Forero Higuera (Platzi)** [638101] (1)

		Puedes usar las medidas en pixeles sin problemas, la verdad todo depende mucho del diseño, lo que si es recomendable es que uses una sola fuente de medida, por ejemplo si vas a usar em, siempre usar em, si vas a usar px siempre usar px o si usas porcentajes siempre usa porcentajes.

	* **Diego Ortiz** [638101] (1)

		Para aprender Angular está bien.  
		Para un proyecto profesional no está muy bien, profesionalmente lo ideal es:
		
		* Usar solo `rem` para todo, ojala con un `:root` que nos de 1rem = 10px
		* Usar `em`y `rem` si tu equipo tiene claro dónde es ideal uno o el otro.
		
		
		
		Los porcentajes sí está bien usarlos si tu diseño responsive es congruente con esa solución.

* **JorgeLopez88** (1) [577869](https://platzi.com/comentario/577869/) 

	No se si les paso lo mismo, pero el tamaño de la imagen no me dejaba cuadrar el navbar me toco bajarle al tamaño.

	* **Edwin De Jesus Chiyopa Garcia** [577869] (1)

		también me paso lo tuve que bajar a 20px

* **isclaem** (1) [569761](https://platzi.com/comentario/569761/) 

	menu.component.html
	``` 
	    <nav class="navbar navbar-expand-lg navbar-light bg-light navarFrame">
	        <aclass="navbar-brand"href="#">
	                <imgid="main-logo"src="assets/img/logo_live.png"alt="logo de platzinger">
	                Platzinger
	        </a>
	    
	        <divclass="collapse navbar-collapse"id="navbarSupportedContent">
	                <ulclass="navbar-nav mr-auto">
	                  <liclass="nav-item">
	                    <aclass="nav-link"routerLink="/home">Home <spanclass="sr-only">(current)</span></a>
	                  </li>
	                  <liclass="nav-item">
	                    <aclass="nav-link"routerLink="/login">Login</a>
	                  </li>
	                  <liclass="nav-item">
	                    <aclass="nav-link "routerLink="/profile">Profile</a>
	                  </li>
	                </ul>
	        </div>
	    </nav>
	    
	```
	
	styles.css
	``` 
	    .navarFrame {
	        background: rgba(0,177,247,1);
	        background: -moz-linear-gradient(45deg, rgba(0,177,247,1) 0%, rgba(89,164,189,0.28) 100%);
	        background: -webkit-gradient(left bottom, right top, color-stop(0%, rgba(0,177,247,1)), color-stop(100%, rgba(89,164,189,0.28)));
	        background: -webkit-linear-gradient(45deg, rgba(0,177,247,1) 0%, rgba(89,164,189,0.28) 100%);
	        background: -o-linear-gradient(45deg, rgba(0,177,247,1) 0%, rgba(89,164,189,0.28) 100%);
	        background: -ms-linear-gradient(45deg, rgba(0,177,247,1) 0%, rgba(89,164,189,0.28) 100%);
	        background: linear-gradient(45deg, rgba(0,177,247,1) 0%, rgba(89,164,189,0.28) 100%);
	        filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#00b1f7', endColorstr='#59a4bd', GradientType=1 );
	    }
	    
	```
	
	![Captura de Pantalla 2019-04-23 a la\(s\) 16.26.45.png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202019-04-23%20a%20la%28s%29%2016.26.45-99f922dc-85d3-495d-991a-3e2a7b26df2d.jpg)

* **Sigaweb** (1) [498124](https://platzi.com/comentario/498124/) 

	Puro css 😄

* **Ezequiel-Fabbroni** (1) [474061](https://platzi.com/comentario/474061/) 

	¿No seria mas conveniente incluir la clase **generalContent ** dentro de el css de app antes que en styles.css ?

* **Luis Miguel Ramos Hernández** (1) [459512](https://platzi.com/comentario/459512/) 

	Para los que copian y pegan(no esta mal) sin revisar el código y que no vieron que tenia algunos errores…
	``` 
	    #menuContainer{
	        background: #8dd2f3;
	        background: -moz-linear-gradient(top, #8dd2f3 0%, #43b5eb 50%, #39abe1 51%, #3cb2ea 100%);
	        background: -webkit-linear-gradient(top, #add2f3 0%, #43b5eb 50%, #39abe1 51%, #3cb2ea 100%);
	        background: linear-gradient(to bottom, #8dd2f3 0%, #43b5eb 50%, #39abe1 51%, #3cb2ea 100%);
	        -ms-filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#8dd2f3', endColorstr='#3cb2ea', GradientType=0);
	        filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#8dd2f3', endColorstr='#3cb2ea', GradientType=0);
	        -webkit-box-shadow: 0px15px15px -4pxrgba(0, 0, 0, 0.24);
	        -moz-box-shadow: 0px15px15px -4pxrgba(0, 0, 0, 0.24);
	        box-shadow: 0px15px15px -4pxrgba(0, 0, 0, 0.24);
	        position: fixed;
	        width: 100%;
	        z-index: 9;
	        height: 56px;
	        top: 0px;
	        border-top: 1px solid white;
	    }```
	    
	```

* **Miguel Angel Ramos Rodríguez** (1) [386206](https://platzi.com/comentario/386206/) 

	El codigo del degradado no aparece en el sistema de archivo el menu.component.css esta vacio.

	* **Jeffry Davila** [386206] (3)

		Hola este codigo es muy similar al del video
		``` 
		    background: rgba(50,187,255,1);
		    background: -moz-linear-gradient(top, rgba(50,187,255,1) 0%, rgba(74,198,255,1) 51%, rgba(50,187,255,1) 52%, rgba(50,187,255,1) 100%);
		    background: -webkit-gradient(left top, left bottom, color-stop(0%, rgba(50,187,255,1)), color-stop(51%, rgba(74,198,255,1)), color-stop(52%, rgba(50,187,255,1)), color-stop(100%, rgba(50,187,255,1)));
		    background: -webkit-linear-gradient(top, rgba(50,187,255,1) 0%, rgba(74,198,255,1) 51%, rgba(50,187,255,1) 52%, rgba(50,187,255,1) 100%);
		    background: -o-linear-gradient(top, rgba(50,187,255,1) 0%, rgba(74,198,255,1) 51%, rgba(50,187,255,1) 52%, rgba(50,187,255,1) 100%);
		    background: -ms-linear-gradient(top, rgba(50,187,255,1) 0%, rgba(74,198,255,1) 51%, rgba(50,187,255,1) 52%, rgba(50,187,255,1) 100%);
		    background: linear-gradient(to bottom, rgba(50,187,255,1) 0%, rgba(74,198,255,1) 51%, rgba(50,187,255,1) 52%, rgba(50,187,255,1) 100%);
		    
		```

* **vlvidal** (1) [368657](https://platzi.com/comentario/368657/) 

	Aquí no hay nada de css como se muestra en el video

	* **inquiridor** [368657] (3)

		Menos quejas, más proyectos

	* **carlos Alberto Bedoya Ramirez** [368657] (2)

		No son quejas, se supone que uno paga por que los recursos del proyecto estén arriba en Git

	* **carlos alberto romero díaz** [368657] (0)

		codeale mijo

* **luis-batalla** (1) [43369](https://platzi.com/comentario/396461/) 
@Eduardo, depues de implementar bootstrap funciona OK, el problema es cuando intento utilizar dropdown, no da error en la consola. Pero n...

	* **luis-batalla** [43369] (1)

		solucionado, problema de orden de carga de jquery

## 0300. Implementando estilos en la pantalla de home [12775](https://platzi.com/clases/1340-angular-avanzado/12775-implementando-estilos-en-la-pantalla-de-home9973/)

### Descripción:


En el directorio assets/ del proyecto se encuentran los archivos de imágenes que se usan para los backgrounds en los diferentes contenedores de la UI, así como otras imágenes del proyecto.

### Comentarios:

* **Carlos Uriel de Jesus Sánchez González** (4) [398657](https://platzi.com/comentario/398657/) 

	styless.css
	``` 
	    /* You can add global styles to this file, and also import other style files */
	    .avatarFrameOffline {
	      background: #ffffff;
	      background: -moz-linear-gradient(top, #ffffff 0%, #eae5e5 45%, #c1bdbd 47%, #bab6b6 100%);
	      background: -webkit-linear-gradient(top, #ffffff 0%, #eae5e5 45%, #c1bdbd 47%, #bab6b6 100%);
	      background: linear-gradient(to bottom, #ffffff 0%, #eae5e5 45%, #c1bdbd 47%, #bab6b6 100%);
	      filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffffff', endColorstr='#bab6b6', GradientType=0);
	      text-align: center;
	      padding: 5%;
	      border-radius: 10px;
	      border: 1px solid rgba(255, 255, 255, 0.36);
	      -webkit-box-shadow: 3px3px21px1pxrgba(0, 0, 0, 0.75);
	      -moz-box-shadow: 3px3px21px1pxrgba(0, 0, 0, 0.75);
	      box-shadow: 3px3px21px1pxrgba(0, 0, 0, 0.75);
	      display: inline-block;
	    }
	    
	    .avatarFrameOnLine {
	      background: #d2ff6b;
	      background: -moz-linear-gradient(top, #d2ff6b 0%, #81ff3d 50%, #0cff00 51%, #0dbc03 100%);
	      background: -webkit-linear-gradient(top, #d2ff6b 0%, #81ff3d 50%, #0cff00 51%, #0dbc03 100%);
	      background: linear-gradient(to bottom, #d2ff6b 0%, #81ff3d 50%, #0cff00 51%, #0dbc03 100%);
	      filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#d2ff6b', endColorstr='#0dbc03', GradientType=0);
	      text-align: center;
	      padding: 5%;
	      border-radius: 10px;
	      border: 1px solid rgba(255, 255, 255, 0.36);
	      -webkit-box-shadow: 3px3px21px1pxrgba(0, 0, 0, 0.75);
	      -moz-box-shadow: 3px3px21px1pxrgba(0, 0, 0, 0.75);
	      box-shadow: 3px3px21px1pxrgba(0, 0, 0, 0.75);
	      display: inline-block;
	    }
	    
	    .generalContent {
	      margin-top: 56px;
	    }
	    
	```
	
	home.component.css
	``` 
	    .ico-estatus {
	      width: 15px;
	      height: 15px;
	    }
	    
	    #homeContainer {
	      background-image: url("/assets/img/msnbg.jpg");
	      background-size: 100%;
	      background-repeat: no-repeat;
	    }
	    
	    #whiteBorderGlassBox {
	      border: 2px solid rgba(255, 255, 255, .75);
	      padding: 8px;
	    }
	    
	    .homeHeadContainer {
	      background-color: rgba(255, 255, 255, .50);
	    }
	    
	    #homeAvatarPicture {
	      max-width: 100px;
	    }
	    
	```
	
	home.component.html
	``` 
	    <divid="homeContainer">
	      <divclass="whiteBorderGlassBox">
	        <divclass="homeHeadContainer">
	          <divclass="row">
	            <divclass="col-md-auto">
	              <divclass="avatarFrameOnLine">
	                <imgsrc="assets/img/generic_avatar.png"id="homeAvatarPicture"/>
	              </div>
	            </div>
	            <divclass="col">
	              <b>Uriel</b>
	              <div>
	                <span>Online</span>
	                <br/>
	                <span>< EscribeunMensajePersonal ></span>
	              </div>
	            </div>
	          </div>
	        </div>
	      </div>
	      <inputtype="text"placeholder="Buscar Amigo" [(ngModel)]="query"/>
	      <br/>
	      <b>Amigos</b>
	      <ng-container *ngFor="let user of friends | search: query; let i = index">
	        <div>
	          <imgclass="ico-estatus"src="assets/img/logo_live_{{user.status}}.png"alt="Estatus de Contacto"/>
	          <arouterLink="/conversation/{{user.uid}}">
	            {{i + 1}}. {{user.nick}} - {{user.email}}
	          </a>
	        </div>
	      </ng-container>
	    </div>
	    
	```
	
	![Captura de pantalla 2018-10-10 a la\(s\) 14.02.35.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-10-10%20a%20la%28s%29%2014.02.35-c019e898-f081-4984-893c-ec78ca26de40.jpg)

	* **Gustavo Ramírez Apache** [398657] (2)

		Evite usar ids para agregar estios, es una mala practica.

	* **Angel Javier Puc Yamá** [398657] (1)

		@Gustavo Ramírez Apache como debía ser?

	* **dvvergara09** [398657] (1)

		Se deberia usar clases para implementar estilos, los id se usan más para trabajar con JS

* **empresamanuel** (3) [391898](https://platzi.com/comentario/391898/) 

	Estimado Eduardo es recomendable usar archivos javascript para animaciones y otros fines (por ejemplo, librerias de graficos, terceros, otros) en Angular 6. Si fuera recomendable, cual seria la manera correcta de incluir los archivos?

	* **johangel leon** [391898] (3)

		Para cualquier persona del futuro que tenga esta misma duda, hace unos capitulos nos enseñaron como importar estilos en nuestra app usando el archivos angular.json, así mismo existe una arreglo llamado scripts, en el cual podremos enseñarle a angular que librerarias terceras queremos tener en nuestra aplicacion, por ejemplo si quisiera utilizar jquery harias:
		
		  1. instalarlo usando npm
		  2. referenciarlo dentro de angular.json en el arreglo scripts (receurda que se instalara en node_modules)
		  3. vuelve a compilar la app usango ng serve y ya asi estarias importando scripts terceros en tu app.
		
		

* **jcarranzac** (2) [746379](https://platzi.com/comentario/746379/) 

	buen curso

	* **Juan Guerra** [746379] (1)

		Asi es Excelente Curso…

* **Walter Lensinas** (2) [547552](https://platzi.com/comentario/547552/) 

	Buenas tardes, dejo el código de las clase en este repositorio <https://github.com/wlensinas/platzinger-wl.git>
	
	Para ver el [código](https://github.com/wlensinas/platzinger-wl/tree/30-home-css):
	
	  1. `git clone https://github.com/wlensinas/platzinger-wl.git`
	  2. `git checkout 21-create-service`
	  3. `npm install`
	  4. `ng serve --open`
	
	
	
	Saludos.

* **Luis Miguel Ramos Hernández** (2) [462290](https://platzi.com/comentario/462290/) 

	Hay un error ya que en el html whiteBorderGlassBox lo asignas como clase y en el css lo asignas como id

* **Juan Guerra** (1) [848474](https://platzi.com/comentario/848474/) 

	Tengo una duda porque algunas veces se utiliza CSS el ‘#’ y otras ‘.’?  
	Ejemplo  
	.HomeContainer{}  
	#HomeContainer{}  
	Lo digo porque nome estaba funcionando con # y con . si.

	* **DoappsTeam** [848474] (3)

		Se usa :
		
		* “.” : cuando el selector es un “class”
		* “#” : cuando el selector es un “id”.
		
		

	* **daniel-zurita** [848474] (1)

		son selectores, uno es para clases ‘.’ y el otro para id ‘#’.

* **juan-pablo-castro** (1) [653655](https://platzi.com/comentario/653655/) 

	En qué momento la página se volvió entera responsive?

	* **capacitacionicesi** [653655] (1)

		El boostrap y las buenas prácticas te proporcionan eso. Cuando una página es modular Booststrap es muy útil porque te proporciona el responsive con sus atributos.

* **Damian Spizzirri** (1) [638111](https://platzi.com/comentario/638111/) 

	Me gusta mucho que lo estes haciendo mientras lo explicas y muestres paso a paso como va cambiando.

* **Alex Eugenio Gavidia Donayre** (1) [552228](https://platzi.com/comentario/552228/) 
Gracias

* **DESTRUN** (1) [421970](https://platzi.com/comentario/421970/) 

	y la intro del video xd?

	* **dvvergara09** [421970] (1)

		x2 jejejejej

* **jeisonsrz** (1) [415294](https://platzi.com/comentario/415294/) 

	style.css ---- >
	``` 
	    /* You can add global styles to this file, and also import other style files */
	    
	    .avatarFrameOffline{
	      background: rgba(242,246,248,1);
	      background: -moz-linear-gradient(left, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
	      background: -webkit-gradient(left top, right top, color-stop(0%, rgba(242,246,248,1)), color-stop(50%, rgba(216,225,231,1)), color-stop(51%, rgba(181,198,208,1)), color-stop(100%, rgba(224,239,249,1)));
	      background: -webkit-linear-gradient(left, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
	      background: -o-linear-gradient(left, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
	      background: -ms-linear-gradient(left, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
	      background: linear-gradient(to right, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
	      filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f2f6f8', endColorstr='#e0eff9', GradientType=1 );
	      text-align: center;
	      padding: 5%;
	      border-radius: 10px;
	      border: 1px solid white;
	      display: inline-block;
	    
	    }
	    .avatarFrameonline{
	      background: rgba(210,255,82,1);
	      background: -moz-linear-gradient(left, rgba(210,255,82,1) 0%, rgba(145,232,66,1) 100%);
	      background: -webkit-gradient(left top, right top, color-stop(0%, rgba(210,255,82,1)), color-stop(100%, rgba(145,232,66,1)));
	      background: -webkit-linear-gradient(left, rgba(210,255,82,1) 0%, rgba(145,232,66,1) 100%);
	      background: -o-linear-gradient(left, rgba(210,255,82,1) 0%, rgba(145,232,66,1) 100%);
	      background: -ms-linear-gradient(left, rgba(210,255,82,1) 0%, rgba(145,232,66,1) 100%);
	      background: linear-gradient(to right, rgba(210,255,82,1) 0%, rgba(145,232,66,1) 100%);
	      filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#d2ff52', endColorstr='#91e842', GradientType=1 );
	      text-align: center;
	      padding: 5%;
	      border-radius: 10px;
	      border: 1px solid lime;
	      display: inline-block;
	    }
	    
	    .center{
	      text-align: center !important;
	    
	    }
	    
	    .marto15{
	      margin-top: 15px;
	    }
	    
	    .marbo15{
	      margin-bottom: 5px;
	    }
	    
	    .btn-primary{
	      background-color: limegreen;
	    
	    }
	    
	    .generalContent{
	      margin-top: 56px;
	    }
	    
	    
	```
	
	home.component.html ----->
	``` 
	    <divid="homeContainer">
	    
	      <divclass="whiteBorderClassBox">
	        <divclass="homeHeadContainer">
	            <divclass="row">
	              <divclass="col-md-auto">
	                <divclass="avatarFrameonline">
	                  <imgsrc="assets/img/generic_avatar.png"id="homeAvatarPicture" />
	    
	                </div>
	              </div>
	              <divclass="col">
	                <b>Jeison Ruiz</b>
	                <div>
	                  <span>Online</span>
	                  <br/>
	                  <span>Escribe un mensaje personal</span>
	                </div>
	              </div>
	            </div>
	        </div>
	      </div>
	      <inputtype="text"placeholder="Buscar amigo" [(ngModel)]="query" />
	      <br/>
	      <br/>
	      <b>Amigos</b>
	      <ng-container *ngFor="let user of friends | search: query; let i = index">
	    
	        <div >
	          <arouterLink="/conversation/{{user.uid}}" >
	            <imgid="imgStatus"src="../../assets/img/logo_live_{{user.status}}.png">{{i}}. {{user.nick}} - {{user.email}}
	          </a>
	    
	        </div>
	    
	      </ng-container>
	    
	    </div>
	    
	    
	    
	```
	
	home.component.css ---->
	``` 
	    #imgStatus{
	      width: 50px;
	    }
	    
	    #homeContainer {
	      background-image: url(/assets/img/msnbg.jpg);
	      background-size: 100%;
	      background-repeat: no-repeat;
	    }
	    
	    #whiteBorderClassBox{
	      border: 2px solid rgba(255,255,255, .75);
	      padding: 8px;
	    }
	    
	    .homeHeadContainer{
	      background-color: rgba(255,255,255, .50);
	    
	    }
	    
	    #homeAvatarPicture{
	      max-width: 100px;
	    }
	    
	    
	```

* **edu1590** (1) [406847](https://platzi.com/comentario/406847/) 

	Por que algunos estilos los agregaste por intermedio de una clase y otros por el Id?

	* **albertodsosa** [406847] (1)

		La respuesta más sencilla para eso es que algunos estilos se crean para ser reutilizables en muchos elementos como por ejemplo las clases y otros particulares o únicos para un elemento como por ejemplo el id.

	* **Gustavo Ramírez Apache** [406847] (3)

		De todas formas así sean unicos debe evitar usarse id, esto se da por algo llamado especificidad.

* **empresamanuel** (1) [42932](https://platzi.com/comentario/391898/) 
Estimado Eduardo es recomendable usar archivos javascript para animaciones y otros fines (por ejemplo, librerias de graficos, terceros, o...

	* **johangel leon** [42932] (3)

		Para cualquier persona del futuro que tenga esta misma duda, hace unos capitulos nos enseñaron como importar estilos en nuestra app usando el archivos angular.json, así mismo existe una arreglo llamado scripts, en el cual podremos enseñarle a angular que librerarias terceras queremos tener en nuestra aplicacion, por ejemplo si quisiera utilizar jquery harias:
		
		  1. instalarlo usando npm
		  2. referenciarlo dentro de angular.json en el arreglo scripts (receurda que se instalara en node_modules)
		  3. vuelve a compilar la app usango ng serve y ya asi estarias importando scripts terceros en tu app.
		
		

## 0310. Implementando estilos en home, lista de contactos [12776](https://platzi.com/clases/1340-angular-avanzado/12776-implementando-estilos-en-home-lista-de-contactos/)

### Descripción:


Las clases row y col de Bootstrap permiten distribuir los anchos de los divs de una manera automatizada. En ciertos casos se suelen usar etiquetdas de html en lugar de estilos, como es el caso de las etiquetas `<b>` o `<i>`.

### Comentarios:

* **Juan Carlos Felizzola Vega** (6) [385024](https://platzi.com/comentario/385024/) 

	Podemos usar las clases de **Bootstrap** para agregarle el `display block` y el `margin-bottom`
	
	* d-block
	* mb-1 = margin-bottom: 4px
	
	
	``` 
	    <spanrouterLink="/conversation/{{user.uid}}"class=“d-blockmb-1”>
	    
	```

	* **cirovladimir** [385024] (1)

		importante añadir que esto lo encuentras en la documentación de bootstrap en la sección de utilities
		
		<https://getbootstrap.com/docs/4.3/utilities/>
		
		en específico en la sección display y spacing.

* **jeisonsrz** (4) [415297](https://platzi.com/comentario/415297/) 

	home.component.css ---->
	``` 
	    #imgStatus{
	      width: 50px;
	    }
	    
	    #homeContainer {
	      background-image: url(/assets/img/msnbg.jpg);
	      background-size: 100%;
	      background-repeat: no-repeat;
	    }
	    
	    #whiteBorderClassBox{
	      border: 2px solid rgba(255,255,255, .75);
	      padding: 8px;
	    }
	    
	    .homeHeadContainer{
	      background-color: rgba(255,255,255, .50);
	    
	    }
	    
	    #homeAvatarPicture{
	      max-width: 100px;
	    }
	    
	    .whiteContainerPadded{
	      padding: 15px;
	      background-color: #feffff;
	    }
	    
	    img.icon{
	      width: 30px;
	    }
	    
	    .disblo{
	      display: block !important;
	    }
	    
	    .marbo5{
	      margin-bottom: 5px;
	    }
	    
	    
	```
	
	home.component.html ----->
	``` 
	    <divid="homeContainer">
	    
	      <divclass="whiteBorderClassBox">
	        <divclass="homeHeadContainer">
	            <divclass="row">
	              <divclass="col-md-auto">
	                <divclass="avatarFrameonline">
	                  <imgsrc="assets/img/generic_avatar.png"id="homeAvatarPicture" />
	    
	                </div>
	              </div>
	              <divclass="col">
	                <b>Jeison Ruiz</b>
	                <div>
	                  <span>Online</span>
	                  <br/>
	                  <span>Escribe un mensaje personal</span>
	                </div>
	              </div>
	            </div>
	        </div>
	      </div>
	      <divclass="whiteContainerPadded marto15">
	    
	        <divclass="row">
	    
	          <divclass="col">
	    
	            <inputtype="text"class="form-control"placeholder="Buscar amigo" [(ngModel)]="query" />
	    
	    
	          </div>
	    
	          <divclass="col-md-auto">
	            <imgsrc="assets/img/logo_live_add.png"class="icon"alt="">
	          </div>
	    
	        </div>
	    
	        <br/>
	        <hr/>
	        <b>Amigos ({{friends.length}} / {{friends.length}})</b>
	        <divclass="disblo marbo5" *ngFor="let user of friends | search: query; let i = index">
	    
	    
	            <spanrouterLink="/conversation/{{user.uid}}" >
	              <imgclass="icon"id="imgStatus"src="../../assets/img/logo_live_{{user.status}}.png">
	              <b>{{user.nick}}</b> - {{user.subnick || 'No hay subnick'}}
	              <small>{{user.email}}</small>
	            </span>
	    
	    
	    
	        </div>
	    
	      </div>
	    
	    
	    </div>
	    
	    
	    
	    
	```

	* **jeisonsrz** [415297] (1)

		style.css ---->
		``` 
		    /* You can add global styles to this file, and also import other style files */
		    
		    .avatarFrameOffline{
		      background: rgba(242,246,248,1);
		      background: -moz-linear-gradient(left, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
		      background: -webkit-gradient(left top, right top, color-stop(0%, rgba(242,246,248,1)), color-stop(50%, rgba(216,225,231,1)), color-stop(51%, rgba(181,198,208,1)), color-stop(100%, rgba(224,239,249,1)));
		      background: -webkit-linear-gradient(left, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
		      background: -o-linear-gradient(left, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
		      background: -ms-linear-gradient(left, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
		      background: linear-gradient(to right, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
		      filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f2f6f8', endColorstr='#e0eff9', GradientType=1 );
		      text-align: center;
		      padding: 5%;
		      border-radius: 10px;
		      border: 1px solid white;
		      display: inline-block;
		    
		    }
		    .avatarFrameonline{
		      background: rgba(210,255,82,1);
		      background: -moz-linear-gradient(left, rgba(210,255,82,1) 0%, rgba(145,232,66,1) 100%);
		      background: -webkit-gradient(left top, right top, color-stop(0%, rgba(210,255,82,1)), color-stop(100%, rgba(145,232,66,1)));
		      background: -webkit-linear-gradient(left, rgba(210,255,82,1) 0%, rgba(145,232,66,1) 100%);
		      background: -o-linear-gradient(left, rgba(210,255,82,1) 0%, rgba(145,232,66,1) 100%);
		      background: -ms-linear-gradient(left, rgba(210,255,82,1) 0%, rgba(145,232,66,1) 100%);
		      background: linear-gradient(to right, rgba(210,255,82,1) 0%, rgba(145,232,66,1) 100%);
		      filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#d2ff52', endColorstr='#91e842', GradientType=1 );
		      text-align: center;
		      padding: 5%;
		      border-radius: 10px;
		      border: 1px solid lime;
		      display: inline-block;
		    }
		    
		    .center{
		      text-align: center !important;
		    
		    }
		    
		    .marto15{
		      margin-top: 15px;
		    }
		    
		    .marbo15{
		      margin-bottom: 5px;
		    }
		    
		    .btn-primary{
		      background-color: limegreen;
		    
		    }
		    
		    .generalContent{
		      margin-top: 56px;
		    }
		    
		    
		```

* **Carlos Uriel de Jesus Sánchez González** (2) [398723](https://platzi.com/comentario/398723/) 

	styless.css
	``` 
	    /* You can add global styles to this file, and also import other style files */
	    .avatarFrameOffline {
	      background: #ffffff;
	      background: -moz-linear-gradient(top, #ffffff 0%, #eae5e5 45%, #c1bdbd 47%, #bab6b6 100%);
	      background: -webkit-linear-gradient(top, #ffffff 0%, #eae5e5 45%, #c1bdbd 47%, #bab6b6 100%);
	      background: linear-gradient(to bottom, #ffffff 0%, #eae5e5 45%, #c1bdbd 47%, #bab6b6 100%);
	      filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffffff', endColorstr='#bab6b6', GradientType=0);
	      text-align: center;
	      padding: 5%;
	      border-radius: 10px;
	      border: 1px solid rgba(255, 255, 255, 0.36);
	      -webkit-box-shadow: 3px3px21px1pxrgba(0, 0, 0, 0.75);
	      -moz-box-shadow: 3px3px21px1pxrgba(0, 0, 0, 0.75);
	      box-shadow: 3px3px21px1pxrgba(0, 0, 0, 0.75);
	      display: inline-block;
	    }
	    
	    .avatarFrameOnLine {
	      background: #d2ff6b;
	      background: -moz-linear-gradient(top, #d2ff6b 0%, #81ff3d 50%, #0cff00 51%, #0dbc03 100%);
	      background: -webkit-linear-gradient(top, #d2ff6b 0%, #81ff3d 50%, #0cff00 51%, #0dbc03 100%);
	      background: linear-gradient(to bottom, #d2ff6b 0%, #81ff3d 50%, #0cff00 51%, #0dbc03 100%);
	      filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#d2ff6b', endColorstr='#0dbc03', GradientType=0);
	      text-align: center;
	      padding: 5%;
	      border-radius: 10px;
	      border: 1px solid rgba(255, 255, 255, 0.36);
	      -webkit-box-shadow: 3px3px21px1pxrgba(0, 0, 0, 0.75);
	      -moz-box-shadow: 3px3px21px1pxrgba(0, 0, 0, 0.75);
	      box-shadow: 3px3px21px1pxrgba(0, 0, 0, 0.75);
	      display: inline-block;
	    }
	    
	    .generalContent {
	      margin-top: 56px;
	    }
	    
	```
	
	home.component.css
	``` 
	    .ico-estatus {
	      width: 15px;
	      height: 15px;
	    }
	    
	    #homeContainer {
	      background-image: url("/assets/img/msnbg.jpg");
	      background-size: 100%;
	      background-repeat: no-repeat;
	    }
	    
	    #whiteBorderGlassBox {
	      border: 2px solid rgba(255, 255, 255, .75);
	      padding: 8px;
	    }
	    
	    .homeHeadContainer {
	      background-color: rgba(255, 255, 255, .50);
	    }
	    
	    #homeAvatarPicture {
	      max-width: 100px;
	    }
	    
	    .whiteContainerPadded {
	      padding: 15px;
	      background-color: #feffff;
	    }
	    
	    img.icon {
	      width: 30px;
	    }
	    
	```
	
	home.component.html
	``` 
	    <divid="homeContainer">
	      <divclass="whiteBorderGlassBox">
	        <divclass="homeHeadContainer">
	          <divclass="row">
	            <divclass="col-md-auto">
	              <divclass="avatarFrameOnLine">
	                <imgsrc="assets/img/generic_avatar.png"id="homeAvatarPicture"/>
	              </div>
	            </div>
	            <divclass="col">
	              <b>Uriel</b>
	              <div>
	                <span>Online</span>
	                <br/>
	                <span>< EscribeunMensajePersonal ></span>
	              </div>
	            </div>
	          </div>
	        </div>
	      </div>
	      <divclass="whiteContainerPadded mt-3">
	        <divclass="row">
	          <divclass="col">
	            <inputtype="text"class="form-control"placeholder="Buscar Amigo" [(ngModel)]="query"/>
	          </div>
	          <divclass="col-md-auto">
	            <imgsrc="assets/img/logo_live_add.png"class="icon"alt=""/>
	          </div>
	        </div>
	        <hr/>
	        <b>Amigos ({{friends.length}} / {{friends.length}})</b>
	        <div *ngFor="let user of friends | search: query"class="d-block m-1">
	            <spanrouterLink="/conversation/{{user.uid}}">
	              <imgclass="ico-estatus"src="assets/img/logo_live_{{user.status}}.png"alt="Estatus de Contacto"/>
	              <b>{{user.nick}}</b> - {{user.subnick || 'No subnick'}}
	              <small>{{user.email}}</small>
	            </span>
	        </div>
	      </div>
	    </div>
	    
	```
	
	![Captura de pantalla 2018-10-10 a la\(s\) 16.19.54.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-10-10%20a%20la%28s%29%2016.19.54-d790f4ee-b45b-4b36-afb4-706fd4cb2814.jpg)

* **Gonzalo Muñoz** (1) [682205](https://platzi.com/comentario/682205/) 

	Bootstrap ya tiene una class para hacer un display block.  
	Pueden agregarla como
	``` 
	    class="d-block"
	    
	```

* **Walter Lensinas** (1) [547604](https://platzi.com/comentario/547604/) 

	Buenas tardes, dejo el código de las clase en este repositorio <https://github.com/wlensinas/platzinger-wl.git>
	
	Para ver el [código](https://github.com/wlensinas/platzinger-wl/tree/31-contactos-css):
	
	  1. `git clone https://github.com/wlensinas/platzinger-wl.git`
	  2. `git checkout 31-contactos-css`
	  3. `npm install`
	  4. `ng serve --open`
	
	
	
	Saludos.

* **Diego Mauricio Mejía Ospina** (1) [525940](https://platzi.com/comentario/525940/) 

	Asi vamos…
	``` 
	    <divid="homeContainer">
	      <divclass="whiteBorderGlassBox">
	        <divclass="homeHeadContainer">
	          <divclass="row"> 
	            <divclass="col-md-auto">
	              <divclass="avatarFrameonline">
	                  <imgsrc="assets/img/generic_avatar.png"id="homeAvatarPicture">
	              </div>
	            </div>
	            <divclass="col">
	              <b>Diego</b>
	              <div>
	                <span>Online</span>
	                <br />
	                <span>< EscribaunMensajePersonal ></span>
	              </div>
	            </div>
	          </div>
	        </div>
	      </div>
	      <inputtype="text"placeholder="Buscar Amigo" [(ngModel)]="query" />
	      <br />
	      <b>Amigos</b>
	    
	      <ng-container *ngFor = "letuseroffriends | search:query; leti = index">
	        <div>    
	          <p>
	            <imgid="status"src="assets/img/logo_live_{{user.status}}.png"alt="Logo Platzinger"width="20px">        
	            <arouterLink = "/conversation/{{user.uid}}">
	              {{i}} . {{user.nick}} - {{user.email}}
	            </a>
	          </p>      
	        </div>
	      </ng-container>
	    </div>```
	    
	```

## 0320. Implementando estilos en profile [12777](https://platzi.com/clases/1340-angular-avanzado/12777-implementando-estilos-en-profile/)

### Descripción:


Cuando usamos inputs de tipo file, normalmente no podemos controlar de manera directa la apariencia en el navegador; incluso, la apariencia de este elemento es muy diferente para los diferentes navegadores. Para evitar esta inconsistencia visual podemos colocar el input dentro de una etiqueta `<label>` y ocultarlo con `display: none`, y aplicar al label una clase para que se ajuste mejor a la apariencia de los botones de nuestra UI.

### Comentarios:

* **Juan Carlos Felizzola Vega** (7) [385033](https://platzi.com/comentario/385033/) 

	Podemos usar las clases de **Bootstrap** para agregarle el `padding-top`
	
	* pt-5 = padding-top: 48px
	
	

* **Carlos Uriel de Jesus Sánchez González** (6) [398752](https://platzi.com/comentario/398752/) 

	styless.css
	``` 
	    /* You can add global styles to this file, and also import other style files */
	    .avatarFrameOffline {
	      background: #ffffff;
	      background: -moz-linear-gradient(top, #ffffff 0%, #eae5e5 45%, #c1bdbd 47%, #bab6b6 100%);
	      background: -webkit-linear-gradient(top, #ffffff 0%, #eae5e5 45%, #c1bdbd 47%, #bab6b6 100%);
	      background: linear-gradient(to bottom, #ffffff 0%, #eae5e5 45%, #c1bdbd 47%, #bab6b6 100%);
	      filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffffff', endColorstr='#bab6b6', GradientType=0);
	      text-align: center;
	      padding: 5%;
	      border-radius: 10px;
	      border: 1px solid rgba(255, 255, 255, 0.36);
	      -webkit-box-shadow: 3px3px21px1pxrgba(0, 0, 0, 0.75);
	      -moz-box-shadow: 3px3px21px1pxrgba(0, 0, 0, 0.75);
	      box-shadow: 3px3px21px1pxrgba(0, 0, 0, 0.75);
	      display: inline-block;
	    }
	    
	    .avatarFrameOnLine {
	      background: #d2ff6b;
	      background: -moz-linear-gradient(top, #d2ff6b 0%, #81ff3d 50%, #0cff00 51%, #0dbc03 100%);
	      background: -webkit-linear-gradient(top, #d2ff6b 0%, #81ff3d 50%, #0cff00 51%, #0dbc03 100%);
	      background: linear-gradient(to bottom, #d2ff6b 0%, #81ff3d 50%, #0cff00 51%, #0dbc03 100%);
	      filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#d2ff6b', endColorstr='#0dbc03', GradientType=0);
	      text-align: center;
	      padding: 5%;
	      border-radius: 10px;
	      border: 1px solid rgba(255, 255, 255, 0.36);
	      -webkit-box-shadow: 3px3px21px1pxrgba(0, 0, 0, 0.75);
	      -moz-box-shadow: 3px3px21px1pxrgba(0, 0, 0, 0.75);
	      box-shadow: 3px3px21px1pxrgba(0, 0, 0, 0.75);
	      display: inline-block;
	    }
	    
	    .generalContent {
	      margin-top: 56px;
	    }
	    
	    input[type='file'] {
	      display: none;
	    }
	    
	    .custom-file-upload {
	      background: #f2f6f8;
	      background: -moz-linear-gradient(top, #f2f6f8 0%, #d8e1e7 50%, #b5c6d0 51%, #e0eff9 100%);
	      background: -webkit-linear-gradient(top, #f2f6f8 0%, #d8e1e7 50%, #b5c6d0 51%, #e0eff9 100%);
	      background: linear-gradient(to bottom, #f2f6f8 0%, #d8e1e7 50%, #b5c6d0 51%, #e0eff9 100%);
	      filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#f2f6f8', endColorstr='#e0eff9', GradientType=0);
	      display: inline-block;
	      padding: 6px12px;
	      cursor: pointer;
	      border: 1px solid #8dd2f3;
	    }
	    
	```
	
	profile.component.css
	``` 
	    #profileContainer {
	      background-image: url("/assets/img/msnbg.jpg");
	      background-size: 100%;
	      background-repeat: no-repeat;
	    }
	    
	```
	
	profile.component.html
	``` 
	    <divid="profileContainer">
	      <divclass="container pt-5">
	        <divclass="row">
	          <divclass="col-md-3">
	            <divclass="avatarFrameOnLine">
	              <imgsrc="assets/img/generic_avatar.png"alt=""class="avatarImage img-fluid">
	            </div>
	            <hr/>
	            <div>
	              <span>Cambiar Foto</span>
	              <br/>
	              <labelclass="custom-file-upload">
	                <inputtype="file"/>
	                Subir Avatar
	              </label>
	            </div>
	          </div>
	          <divclass="col-md-9">
	            <div>
	              <labelfixed>Nick</label>
	              <inputtype="text"class="form-control"/>
	            </div>
	            <div>
	              <labelfixed>Subnick</label>
	              <inputtype="text"class="form-control"/>
	            </div>
	            <div>
	              <labelfixed>Email</label>
	              <inputtype="email"disabledclass="form-control"/>
	            </div>
	            <div>
	              <labelfixed>Estatus</label>
	              <selectclass="form-control">
	                <optionvalue="online">Conectado</option>
	                <optionvalue="away">Ausente</option>
	                <optionvalue="busy">Ocupado</option>
	                <optionvalue="appear_offline">Desconectado</option>
	              </select>
	            </div>
	            <hr/>
	            <aclass="btn btn-primary btn-block">Guardar</a>
	          </div>
	        </div>
	      </div>
	    </div>
	    
	```
	
	![Captura de pantalla 2018-10-10 a la\(s\) 17.18.31.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-10-10%20a%20la%28s%29%2017.18.31-04652e11-fcd3-46a9-9761-214fa2ca4cd9.jpg)

* **jeisonsrz** (3) [415300](https://platzi.com/comentario/415300/) 

	profile.component.html ----->
	``` 
	    <divid="profileContainer">
	      <divclass="container pato45">
	        <divclass="row">
	          <divclass="col-md-3">
	            <divclass="avatarFrameonline">
	              <imgsrc="assets/img/generic_avatar.png"class="avatarImage img-fluid">
	            </div>
	            <hr/>
	            <div>
	              <span>Cambiar Foto</span><br />
	              <labelclass="custom-file-upload">
	                <inputtype="file">
	                Subir Avatar wey
	              </label>
	            </div>
	          </div>
	          <divclass="col-md-9">
	            <div>
	              <labelfixed >Nick</label>
	              <inputtype="text"class="form-control" />
	            </div>
	            <div>
	              <labelfixed >Subnick</label>
	              <inputtype="text"class="form-control" />
	            </div>
	            <div>
	              <labelfixed >Email</label>
	              <inputtype="email"disabledclass="form-control" />
	            </div>
	            <div>
	              <labelfixed >Status</label>
	              <selectclass="form-control">
	                <optionvalue="online">Conectado</option>
	                <optionvalue="awaye">Ausente</option>
	                <optionvalue="busy">Ocupado</option>
	                <optionvalue="appear_offline">Desconectado</option>
	    
	              </select>
	            </div>
	            <hr />
	            <aclass="btn btn-primary btn-block">Guardar</a>
	          </div>
	        </div>
	      </div>
	    </div>
	    
	    
	```
	
	styles.css —>
	``` 
	    /* You can add global styles to this file, and also import other style files */
	    
	    .avatarFrameOffline{
	      background: rgba(242,246,248,1);
	      background: -moz-linear-gradient(left, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
	      background: -webkit-gradient(left top, right top, color-stop(0%, rgba(242,246,248,1)), color-stop(50%, rgba(216,225,231,1)), color-stop(51%, rgba(181,198,208,1)), color-stop(100%, rgba(224,239,249,1)));
	      background: -webkit-linear-gradient(left, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
	      background: -o-linear-gradient(left, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
	      background: -ms-linear-gradient(left, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
	      background: linear-gradient(to right, rgba(242,246,248,1) 0%, rgba(216,225,231,1) 50%, rgba(181,198,208,1) 51%, rgba(224,239,249,1) 100%);
	      filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f2f6f8', endColorstr='#e0eff9', GradientType=1 );
	      text-align: center;
	      padding: 5%;
	      border-radius: 10px;
	      border: 1px solid white;
	      display: inline-block;
	    
	    }
	    .avatarFrameonline{
	      background: rgba(210,255,82,1);
	      background: -moz-linear-gradient(left, rgba(210,255,82,1) 0%, rgba(145,232,66,1) 100%);
	      background: -webkit-gradient(left top, right top, color-stop(0%, rgba(210,255,82,1)), color-stop(100%, rgba(145,232,66,1)));
	      background: -webkit-linear-gradient(left, rgba(210,255,82,1) 0%, rgba(145,232,66,1) 100%);
	      background: -o-linear-gradient(left, rgba(210,255,82,1) 0%, rgba(145,232,66,1) 100%);
	      background: -ms-linear-gradient(left, rgba(210,255,82,1) 0%, rgba(145,232,66,1) 100%);
	      background: linear-gradient(to right, rgba(210,255,82,1) 0%, rgba(145,232,66,1) 100%);
	      filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#d2ff52', endColorstr='#91e842', GradientType=1 );
	      text-align: center;
	      padding: 5%;
	      border-radius: 10px;
	      border: 1px solid lime;
	      display: inline-block;
	    }
	    
	    .center{
	      text-align: center !important;
	    
	    }
	    
	    .marto15{
	      margin-top: 15px;
	    }
	    
	    .marbo15{
	      margin-bottom: 5px;
	    }
	    
	    .btn-primary{
	      background-color: limegreen;
	    
	    }
	    
	    .generalContent{
	      margin-top: 56px;
	    }
	    
	    #homeAvatarPicture{
	      max-width: 100px;
	    }
	    
	    .disblo{
	      display: block !important;
	    }
	    
	    .marbo5{
	      margin-bottom: 5px;
	    }
	    
	    .pato45{
	      padding-top: 45px;
	    }
	    
	    input[type ="file"]{
	      display: none;
	    }
	    
	    .custom-file-upload{
	      background: #f2f6f8;
	      background: -moz-linear-gradient(top, #f2f6f8 0%, #d8e1e7 50%, #b5c6d0 51%, #e0eff9 100%);
	      background: -webkit-linear-gradient(top, #f2f6f8 0%, #d8e1e7 50%, #b5c6d0 51%, #e0eff9 100%);
	      background: linear-gradient(to bottom, #f2f6f8 0%, #d8e1e7 50%, #b5c6d0 51%, #e0eff9 100%);
	      filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#f2f6f8', endColorstr='#e0eff9', GradientType=0);
	      display: inline-block;
	      padding: 6px12px;
	      cursor: pointer;
	      border: 1px solid #8dd2f3;
	    }
	    
	    
	```
	
	profile.component.css ---->
	``` 
	    #profileContainer {
	      background-image: url(/assets/img/msnbg.jpg);
	      background-size: 100%;
	      background-repeat: no-repeat;
	    }
	    
	    
	```

* **ehnbytes** (1) [1016161](https://platzi.com/comentario/1016161/) 

	Buena clase!

* **Damian Spizzirri** (1) [658575](https://platzi.com/comentario/658575/) 

	Que es ese fixed que le puso a la etiqueta label? No entendi.

	* **Diego Alexander Forero Higuera (Platzi)** [658575] (2)

		He investigado y no he encontrado nada al respecto, lo que si comprobé es que no cambia nada el tenerlo o no tenerlo a nivel visual.

* **juan-pablo-castro** (1) [653782](https://platzi.com/comentario/653782/) 

	 **La clase avatatarImage no existe**  
	Esto no da problema, pero tampoco añade valor. La puedes quitar

* **Alex Eugenio Gavidia Donayre** (1) [552230](https://platzi.com/comentario/552230/) 
Gracias

## 0330. Reto Estilos en la pantalla de conversación [13004](https://platzi.com/clases/1340-angular-avanzado/13004-reto-estilos-en-la-pantalla-de-conversacion/)

### Descripción:


Ya que tenemos el resto del app con estilos, lo más parecido posible al legendario Msn Messenger, toma la pantalla de conversación y dale estilo.

### Comentarios:

* **Ezequiel Freire** (10) [447951](https://platzi.com/comentario/447951/) 

	Hola, asi me quedo. ![Captura de pantalla 2018-12-13 a la\(s\) 21.18.39.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-12-13%20a%20la%28s%29%2021.18.39-c815340b-6e09-401b-93ee-1375a7f33602.jpg)

	* **RomarioEstradaFlorez** [447951] (2)

		jajajajaja

* **Juan Diego Lopez Triana** (8) [372629](https://platzi.com/comentario/372629/) 

	Así me quedo:  
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-fc3ea960-5454-4a3f-8ac0-03dc7221bc42.jpg)

	* **Sigaweb** [372629] (1)

		Esa carita, la da estil, se ve muy bn

* **jehisonorostegui** (4) [632718](https://platzi.com/comentario/632718/) 

	Intento hacerlo lo mas parecido a MSN
	
	![Captura de Pantalla 2019-06-30 a la\(s\) 11.54.37 a. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202019-06-30%20a%20la%28s%29%2011.54.37%20a.%20m.-7b2c0168-71fa-4cc2-9c05-f9b2883b9347.jpg)

* **Carlos Garrido Marin** (4) [591350](https://platzi.com/comentario/591350/) 

	Así quedo el mío:  
	![](url)![Platzinger.jpg](https://static.platzi.com/media/user_upload/Platzinger-b543d449-55e8-4bc9-9a1e-23ba2eaa97f2.jpg)

* **Wilson Fabian Pérez Sucuzhañay** (3) [367959](https://platzi.com/comentario/367959/) 

	listo  
	![Captura de pantalla 2018-08-30 a la\(s\) 11.21.13.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-08-30%20a%20la%28s%29%2011.21.13-4521ead9-86e4-4ac5-a097-3a96d8838eae.jpg)

* **Gianfranco  Verrocchi** (2) [546261](https://platzi.com/comentario/546261/) 
	
	![msn.jpg](https://static.platzi.com/media/user_upload/msn-abe82049-7c99-4faf-b856-288fb54b570f.jpg)

* **Luis Miguel Ramos Hernández** (2) [464333](https://platzi.com/comentario/464333/) 
	
	![123.png](https://static.platzi.com/media/user_upload/123-8d9f2c7d-edfc-4452-a270-38b08898825b.jpg)

* **salocho** (2) [420851](https://platzi.com/comentario/420851/) 
	
	![conversation.png](https://static.platzi.com/media/user_upload/conversation-1236839a-e850-4e46-8148-a894f1a9d94f.jpg)

* **Alexander Sandoval** (2) [418567](https://platzi.com/comentario/418567/) 

	Así quedó el mío:  
	![conversation.png](https://static.platzi.com/media/user_upload/conversation-e90353e4-9123-4a47-9fd1-4bfa3e4b064e.jpg)

* **Jeffry Davila** (2) [393874](https://platzi.com/comentario/393874/) 

	Al final así me quedo:  
	![primero.JPG](https://static.platzi.com/media/user_upload/primero-937eef14-5cec-428c-bdd0-dd90d7db5ede.jpg)

* **rodspek** (2) [381851](https://platzi.com/comentario/381851/) 
	
	![Reto2AAdv.JPG](https://static.platzi.com/media/user_upload/Reto2AAdv-dfa62a0a-baa9-4711-bc4e-be2d25bb77be.jpg)

* **Fernando Vallejo** (1) [1045243](https://platzi.com/comentario/1045243/) 
	
	![Captura de Pantalla 2020-03-18 a la\(s\) 02.58.02.png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202020-03-18%20a%20la%28s%29%2002.58.02-e30c7b54-45ba-41d4-8e37-5eed8187529a.jpg)

* **David Alejandro Mosquera Moreno** (1) [862341](https://platzi.com/comentario/862341/) 
	
	![convo.png](https://static.platzi.com/media/user_upload/convo-62855c45-f354-4afb-8203-4246ce0b87be.jpg)

* **caprilespe** (1) [795297](https://platzi.com/comentario/795297/) 
	
	![conversation.PNG](https://static.platzi.com/media/user_upload/conversation-10a7a235-bf7d-4b82-8e67-ea8a26cebe53.jpg)

* **fernandojavierespanacordoba** (1) [794505](https://platzi.com/comentario/794505/) 
	
	![2019-10-23_112516.png](https://static.platzi.com/media/user_upload/2019-10-23_112516-110ffa85-3617-4319-8dbf-30dc3e16aa33.jpg)

* **Hans Vogt** (1) [673129](https://platzi.com/comentario/673129/) 
	
	![dfad.png](https://static.platzi.com/media/user_upload/dfad-7740629b-6007-4c23-87e7-622074814cd3.jpg) ![imagen2.png](https://static.platzi.com/media/user_upload/imagen2-c45b72e3-8f0d-425c-a67e-1814af64b71b.jpg)

* **Christian Michelle Torres Martínez** (1) [626059](https://platzi.com/comentario/626059/) 

	![Screenshot Conversation.png](https://static.platzi.com/media/user_upload/Screenshot%20Conversation-c6eb0aac-68fe-4663-81b8-51800ac8ffbb.jpg)!

* **Edwin De Jesus Chiyopa Garcia** (1) [625889](https://platzi.com/comentario/625889/) 

	![](https://drive.google.com/file/d/16BhZhxVkV8bhNEoOhuOMEAf6qbvgxhhk/view?usp=sharing)  
	<https://drive.google.com/file/d/16BhZhxVkV8bhNEoOhuOMEAf6qbvgxhhk/view?usp=sharing>

* **JorgeLopez88** (1) [580212](https://platzi.com/comentario/580212/) 

	El mio quedo asi, falta mejorarlo mucho.![](![Conversation.PNG](https://static.platzi.com/media/user_upload/Conversation-2c2b748d-addf-4b50-914d-6e7c587e602e.jpg)
	``` 
	    <divclass="conversationContainer">
	        <divclass="container margenSuperior45">
	            <divclass="row">
	                <divclass="col-md-3 margenIzquierda">
	                    <divclass="avatarFrameOnline">
	                        <imgsrc="assets/img/generic_avatar.png"class="avatarImage img-fluid" />
	                    </div>
	                    <divclass="avatarFrameOnline margenSuperior200">
	                        <imgsrc="assets/img/generic_avatar.png"class="avatarImage img-fluid" />
	                    </div>
	                </div>
	                <divclass="col">
	                    <span><b>{{friend.nick}} - ({{friend.status}})</b></span>
	                    <divclass="container">
	                        <divclas="espacioChat margenSuperior">
	                            <divclass="msjChat">
	                                <span><b>{{friend.nick}} dice:</b></span>
	                                <p>Hola, como estas?</p>
	                            </div>
	                            <divclass="msjChat">
	                                <span><b>Jorge dice:</b></span>
	                                <p>Muy bien y tu?</p>
	                            </div>
	                        </div>
	                        <divclass="posicionCuadroTexto">
	                            <inputtype="text"class="form-control tamañoCuadroTexto"placeholder="Ingresa tu mensaje">
	                            <divclass="margenSuperior">
	                                <imgsrc="assets/img/zumbido.png"class="iconImage img-fluid">
	                                <labelclass="custom-file-upload">
	                                    <inputtype="file">
	                                    <iclass="far fa-images"></i>
	                                    Seleccionar Imagen
	                                </label>
	                                <buttontype="button"class="btn btn-primary posicionBotonEnviar">Enviar</button>
	                            </div>
	                        </div>
	                    </div>
	                </div>
	            </div>
	        </div>
	    </div>
	    
	```

* **ing-michaelvillanueva** (1) [575844](https://platzi.com/comentario/575844/) 

	Asi me quedo el diseño de la pantalla de conversación![Screenshot_2019-05-01 Chatangular.png](https://static.platzi.com/media/user_upload/Screenshot_2019-05-01%20Chatangular-54939d1a-7e7e-476e-ba73-061c9a0f50da.jpg)

* **JESUS IVAN MENDOZA CONTRERAS** (1) [574969](https://platzi.com/comentario/574969/) 
	
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-be26b57f-bf09-455f-a0c3-88793b600d6f.jpg)

* **isclaem** (1) [570118](https://platzi.com/comentario/570118/) 

	Así me quedo :  
	![Captura de Pantalla 2019-04-23 a la\(s\) 20.16.18.png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202019-04-23%20a%20la%28s%29%2020.16.18-11726254-9791-4fb4-89fd-322255f24e8d.jpg)

* **Walter Lensinas** (1) [549771](https://platzi.com/comentario/549771/) 

	Buenas tardes, dejo el código del reto en este repositorio <https://github.com/wlensinas/platzinger-wl.git>
	
	Para ver el código del reto ver el branch [33-conversacion-css-reto](https://github.com/wlensinas/platzinger-wl/tree/33-conversacion-css-reto)
	
	  1. `git clone https://github.com/wlensinas/platzinger-wl.git`
	  2. `git checkout 33-conversacion-css-reto`
	  3. `npm install`
	  4. `ng serve --open`
	
	
	
	Saludos.
	
	![chat.JPG](https://static.platzi.com/media/user_upload/chat-90d85787-9bf6-4788-824c-db90febd70c0.jpg)

* **Adrian Camilo Caminos** (1) [537620](https://platzi.com/comentario/537620/) 

	asi os quedo  
	![Screen Shot 2019-03-17 at 4.43.38 PM.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202019-03-17%20at%204.43.38%20PM-c6d9c6b8-5ff4-4032-8f3b-950014ea2d45.jpg)

* **Alfonso Adame Rueda** (1) [535545](https://platzi.com/comentario/535545/) 

	hola buenas tardes, a mi me quedo asi.

* **Alfonso Adame Rueda** (1) [535543](https://platzi.com/comentario/535543/) 

	![](![CONVERSATION.PNG](https://static.platzi.com/media/user_upload/CONVERSATION-3bd06ec3-472f-4dc6-9649-74b082d8e8e3.jpg)

* **Diego Mauricio Mejía Ospina** (1) [527178](https://platzi.com/comentario/527178/) 
	
	![](http://www.subirimagenes.com/imagen-captura-9888711.html)

* **Diego Mauricio Mejía Ospina** (1) [527172](https://platzi.com/comentario/527172/) 

	[](http://www.subirimagenes.com/privadas-captura-2443513.html)

* **Ezequiel-Fabbroni** (1) [477424](https://platzi.com/comentario/477424/) 

	Asi me salio:
	
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-a4c70243-e435-4861-9b92-39d5498c28ba.jpg)
	
	Saludos
	``` 
	    <divid="conversationContainer">
	    	<divclass="contPrinc pato45">
	    		<divclass="row">
	    			<divclass="col-xs-3 bg-grey marle-25">
	    				<divclass="avatarFrameOnLine ">
	    					<imgsrc="assets/img/generic_avatar.png"class=" homeAvatarPicture img-fluid">
	    				</div>
	    
	    				<divclass="avatarFrameOnLine  marto250">
	    					<imgsrc="assets/img/generic_avatar.png"class=" homeAvatarPicture img-fluid">
	    				</div>
	    
	    			</div>
	    			<divclass="col">
	    				<span><b>Persona (Online)</b></span>
	    				<divclass="container">
	    					<divclass="chatContainer marto15">
	    						<divclass="exampleChat">
	    							<span><b>Persona dice:</b></span>
	    							<pclass="marle-25">Hola, ¿como estas?</p>
	    						</div>
	    						<divclass="exampleChat">
	    							<span><b>Persona2 dice:</b></span>
	    							<pclass="marle-25">Bien, aquí esforzandome por diseñar el chat :C <br> ¿y tu?</p>
	    						</div>
	    						
	    
	    					</div>
	    					<divclass="bottomChat">
	    						<inputtype="area"class="form-control areaChat"placeholder="Escribe un mensaje"name="">
	    						
	    						<divclass="marto15">
	    
	    							<imgsrc="assets/img/zumbido.png"class="iconImage img-fluid">
	    							<imgsrc="assets/img/zumbido.png"class="iconImage img-fluid">
	    							<imgsrc="assets/img/zumbido.png"class="iconImage img-fluid">
	    							
	    							<labelclass="customFileUpload">
	    								<inputtype="file">
	    								<iclass="far fa-images"></i>
	    								Seleccionar Imagen
	    							</label>
	    						</div>
	    					</div>
	    					
	    				</div>
	    			</div>
	    		</div>
	    	</div>
	    </div>
	    
	    // css
	    .contPrinc{
	    	padding: 15px;
	    }
	    .margin-left{
	    	margin-left: 0px;
	    }
	    .chatContainer{
	    	width: 100%;
	    	height: 350px;
	    }
	    .bottomChat{
	    	width: 100%;
	    	bottom: 0px;
	    }
	    #conversationContainer{
	      background-image: url("/assets/img/msnbg.jpg");
	      background-size: 100%;
	      background-repeat: no-repeat;
	    
	    }
	    .homeAvatarPicture {
	      max-width: 100px;
	    }
	    .marto100 {
	    	margin-top: 100px;
	    }
	    .marle-25{
	    	margin-left: 25px;
	    }
	    .marto250{
	      margin-top: 250px;
	    }
	    .areaChat{
	    	height:100px;
	    }
	    
	    .exampleChat {
	    	font-family: 'San-serif'
	    }
	    
	    .iconImage{
	    	width: 30px;
	    	margin-right: 10px;
	    }
	    
	    img .logoPers {
	    	width: 65px;
	    }
	    .icon{
	    	margin-right:  10px;
	    }
	    
	```

* **Luis Miguel Ramos Hernández** (1) [464329](https://platzi.com/comentario/464329/) 
	
	![123.png](https://static.platzi.com/media/user_upload/123-bbb7f200-34cb-4e67-b8e8-ec4aae6f910d.jpg)

* **Spyderp** (1) [445119](https://platzi.com/comentario/445119/) 

	lo que hice en un rato. Como se que lo voy a corregir con el código no quise arreglar hasta el detalle.  
	![reto.PNG](https://static.platzi.com/media/user_upload/reto-64482713-ec11-4e7a-a461-62eb27a62591.jpg)

* **elmerrodriguez** (1) [441379](https://platzi.com/comentario/441379/) 
	
	![platzinger.png](https://static.platzi.com/media/user_upload/platzinger-f050c0c0-261a-4284-be94-4d52bf52eb7c.jpg)

* **Dany Ladino** (1) [433941](https://platzi.com/comentario/433941/) 

	Hola, este es la pantalla de conversation: ![Captura de pantalla 2018-11-27 a la\(s\) 3.04.07 p. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-11-27%20a%20la%28s%29%203.04.07%20p.%20m.-be1290f2-a512-484d-8000-ec096b3b4ffd.jpg)

* **mario-salinas** (1) [425051](https://platzi.com/comentario/425051/) 
	
	![Captura de pantalla 2018-11-17 a la\(s\) 6.15.53 p. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-11-17%20a%20la%28s%29%206.15.53%20p.%20m.-7c8f5e98-2557-443f-a591-5b60e84654d7.jpg)
	
	Asi me quedó

* **Emerson-Lirmi** (1) [423452](https://platzi.com/comentario/423452/) 
	
	![Chat.jpg](https://static.platzi.com/media/user_upload/Sin%20t%C3%ADtulo-bb72859a-728b-4dfb-a6fc-37b4ba671421.jpg)

* **Jeffry Davila** (1) [393875](https://platzi.com/comentario/393875/) 

	Lo otro que agregue fue que cuando no sean amigos no aparezca la opción de enviar mensaje:  
	![segundo.JPG](https://static.platzi.com/media/user_upload/segundo-33ec7db3-3c68-4b11-b563-abfe10675976.jpg)

## 0340. Usando ngClass para añadir estilos dinámicos [12778](https://platzi.com/clases/1340-angular-avanzado/12778-usando-ngclass-para-anadir-estilos-dinamicos/)

### Descripción:


NgClass es una directiva que te permite aplicar una u otra clase a un elemento de html, dependiendo de una condición o expresión buleana.  
La forma de implementar NgClass es la siguiente:
``` 
      <div [ngClass] = ""{ '<nombre-de-la-clase': <expresión buleana> }"">
        <!-- -->
      </div>
    
```

La clase indicada se aplicará al elemento cuando la expresión buleana sea verdadera.

### Comentarios:

* **Carlos Uriel de Jesus Sánchez González** (3) [398760](https://platzi.com/comentario/398760/) 

	app.component.ts
	``` 
	    import {Component} from '@angular/core';
	    import {Router} from '@angular/router';
	    
	    @Component({
	      selector: 'app-root',
	      templateUrl: './app.component.html',
	      styleUrls: ['./app.component.css']
	    })
	    export class AppComponent {
	      constructor(public router: Router) {
	      }
	    }
	    
	```
	
	app.component.html
	``` 
	    <app-menu *ngIf="router.url != '/login'"></app-menu>
	    <div [ngClass]="{'generalContent': router.url != '/login'}">
	      <router-outlet></router-outlet>
	    </div>
	    
	```
	
	![Captura de pantalla 2018-10-10 a la\(s\) 17.31.57.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-10-10%20a%20la%28s%29%2017.31.57-fcbc65fa-009e-43be-96a4-0d8a7a2ec098.jpg)

* **Erik Ricardo Sánchez Pérez** (2) [1027499](https://platzi.com/comentario/1027499/) 

	Para los que tengan problemas con el `router.url` con angular 9 les comento que pueden usar el modulo `import {Location} from '@angular/common';`
	``` 
	    import { Component } from'@angular/core';
	    import {Location} from'@angular/common';
	    
	    @Component({
	      selector: 'app-root',
	      templateUrl: './app.component.html',
	      styleUrls: ['./app.component.css']
	    })
	    exportclassAppComponent{
	      title = 'platzinger';
	      constructor(public location: Location) {}
	    }
	    
	    
	```
	
	y pueden acceder a `location.path()` para obtener la ruta

* **TlalocES** (2) [492364](https://platzi.com/comentario/492364/) 

	¿Es esta en producción la mejor forma de ocultar paginas?, ¿no es fácilmente hackeable?

	* **JerezA** [492364] (1)

		me gustaria saber lo mismo…

* **mcamelo** (2) [417171](https://platzi.com/comentario/417171/) 
Hola Eduardo, queria saber si tenias alguna forma de hacer validaciones personalizadas en Angular 6, tipo "El campo es requerido" pero con componentes de NgPrime

* **Adrian Alberto Casas Lopez** (1) [970073](https://platzi.com/comentario/970073/) 

	Implemente un navbar para la parte de la navegación y agregue una opción de logout pero no me funciona del todo ya que al logearme me manda a home pero no me muesra la opción de Logout solo cuando doy F5 aparece, ¿alguien sabra porque?  
	Esto esta implementado en el app.comoponent.ts
	``` 
	    export class AppComponent {
	      title = 'platzinger';
	      loggedIn = false;
	      constructor(public router: Router, private authenticationService: AuthenticationService) {
	        this.authenticationService.getStatus()
	        .subscribe((result) => {
	          if ( result && result.uid) {
	            this.loggedIn = true;
	          } else {
	            this.loggedIn = false;
	          }
	        }, (error) => {
	          this.loggedIn = false;
	        });
	      }
	    
	      logout() {
	        this.authenticationService.logout().then(() => {
	          alert('Sesión cerrada!');
	          this.route.navigate(['login']);
	        }, (error) => {
	          console.log(error);
	        });
	      }
	    }```
	    
	    
	```

* **Kingsman7** (1) [851983](https://platzi.com/comentario/851983/) 

	wow angular wow

* **Wilson Marino Pablo Mendez** (1) [713203](https://platzi.com/comentario/713203/) 

	Que interesante 👌

* **asfo** (1) [557976](https://platzi.com/comentario/557976/) 

	Yo diría que es una mala práctica usar el *ngIf aquí.
	
	Aunque no he visto todo el curso, espero que se haga el cambio pero, en este caso en el componente de <app-menu> debería pasarse como parámetro a través de una directiva ya sea la ruta si así se busca hacer (que, en lo personal considero que este <app-menu> no debería estar si quiera en este punto en el app.component si no dentro del component login y no usar las rutas) o un parámetro estilo `[show]="true"` que permita mostrar o no el menú ya que de esta forma no requieres ni si quiera el router y el código es más básico y simple.

* **Alex Eugenio Gavidia Donayre** (1) [547462](https://platzi.com/comentario/547462/) 
Great

* **Yonathan Gutierrez** (1) [436508](https://platzi.com/comentario/436508/) 

	Se me ocurrió que, si yo pongo que por defecto la primera vista fuera el login, como manejarlo? aplique algo que se mostró anteriormente (etiqueta auxiliar) para aplicarlo tambien al link limpio es decir sin nada después del dominio quedando así:
	``` 
	    <div *ngIf="router.url != '/'">
	      <app-navbar *ngIf="router.url != '/login'"></app-navbar>
	    </div>
	    
	```

* **Arturo Mojica Guerrero** (1) [72247](https://platzi.com/comentario/813015/) 
Nose, porque en todas las paginas el router.url solo me lanza el “/” no me da el complemento de ese caracter por ejemplo /login.

	* **Juan David Castro (Platzi)** [72247] (1)

		¿Tienes tu código publicado en alguna parte? Así podemos descargarlo o algo para buscar el error y su solución. 😉

* **TlalocES** (1) [51496](https://platzi.com/comentario/492364/) 
¿Es esta en producción la mejor forma de ocultar paginas?, ¿no es fácilmente hackeable?

	* **JerezA** [51496] (1)

		me gustaria saber lo mismo…

## 0350. Reto Mejorar estilos en la pantalla de conversación [13005](https://platzi.com/clases/1340-angular-avanzado/13005-reto-mejorar-estilos-en-la-pantalla-de-conversacio/)

### Descripción:


Ahora, llevemos el estilo de la pantalla de conversación un paso más allá.

Agrega cada mensaje de texto en una “burbuja” como las que encontrarías en las apps más populares de mensajería instantánea.

También, agrega el avatar de los participantes a un lado de cada mensaje enviado.

### Comentarios:

* **Juan Diego Lopez Triana** (6) [372645](https://platzi.com/comentario/372645/) 

	No sé si a esto era a lo que se refería:  
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-3ee952d0-697c-4466-bbdb-ef3a55d905ac.jpg)

* **Elberth Jair Agreda Rosero** (5) [780577](https://platzi.com/comentario/780577/) 

	Inspiración:  
	![Captura de Pantalla 2019-10-14 a la\(s\) 11.09.13 a. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202019-10-14%20a%20la%28s%29%2011.09.13%20a.%20m.-3c28b0b9-6d63-4e06-9b10-9efbfa2f4147.jpg)

* **Teofilo Rosales Gama** (5) [390689](https://platzi.com/comentario/390689/) 

	Perdonen es algo como esto:  
	![chat.png](https://static.platzi.com/media/user_upload/chat-6d728355-2012-4b27-9ee7-b39b1a87d265.jpg)  
	aqui les mando el codigo no soy egoista
	``` 
	    <divid="conversationContainer">
	      <divclass="whiteBorderGlassBox">
	          <divclass="homeHeadContainer">
	            <divclass="row">
	              <divclass="col-md-auto">
	                <divclass="avatarFrameonline">
	                    <imgsrc="assets/img/generic_avatar.png"id="homeAvatarPicture">
	                </div>
	              </div>
	              <divclass="col">
	                <h1>Eduardo</h1>
	                <div>
	                  <span>Online</span>
	                  <br />
	                  <span>Escribe un mensaje Personal </span>
	                  <hr/>
	                </div>
	                <form >
	                  <divclass="form-group">
	                    <divclass="card">
	                      <divclass="card-body">
	                        <divclass="col">
	                          <i>
	                            <imgsrc="assets/img/generic_avatar.png"alt=""class="icon-chat">
	                          </i>
	                          <spanclass="badge badge-primary">Hola como estas?</span>
	                        </div>
	                        <divclass="col text-right">
	                            <i>
	                              <spanclass="badge badge-primary">Yo bien y tu?</span>
	                              <imgsrc="assets/img/generic_avatar.png"alt=""class="icon-chat">
	                            </i>
	                          </div>
	                      </div>
	                    </div>
	                  </div>
	                </form>
	              </div>
	            </div>
	          </div>
	        </div>
	        <divclass="whiteBorderGlassBox">
	            <divclass="homeHeadContainer">
	              <divclass="row">
	                <divclass="col-md-auto">
	                  <divclass="avatarFrameonline">
	                      <imgsrc="assets/img/generic_avatar.png"id="homeAvatarPicture">
	                  </div>
	                </div>
	                <divclass="col">
	                  <b>Yo</b>
	                  <div>
	                    <form >
	                      <divclass="form-group">
	                        <textareaclass="form-control"id="Area-de-Chat"rows="3"placeholder="Escribe menos de 140 caracteres"></textarea>
	                        <divclass="col text-right">
	                          <iclass="img mr-1">
	                            <imgsrc="assets/img/icons/regular_smile.gif"alt="">
	                          </i>
	                          <iclass="img mr-1">
	                            <imgsrc="assets/img/icons/tongue_smile.gif"alt="">
	                          </i>
	                          <iclass="img mr-1">
	                            <imgsrc="assets/img/icons/angry_smile.gif"alt="">
	                          </i>
	                          <buttontype="button"class="btn btn-primary btn-sm mr-1">
	                            Enviar
	                          </button>
	                          <labelclass="custom-file-upload mr-1">
	                            <inputtype="file">
	                            Selecciona Imagen
	                          </label>
	                        </div>
	                      </div>
	                    </form>
	                  </div>
	                </div>
	              </div>
	            </div>
	          </div>
	      </div>
	    
	```
	
	conversation.component.css:
	``` 
	    #conversationContainer {
	      background-image: url(/assets/img/msnbg.jpg);
	      background-size: 100%;
	      background-repeat: no-repeat;
	    }
	    img.avatarImage{
	      height: 100px;
	      width: 100px;
	    }
	    .icon-chat{
	      height: 40px;
	      width: 40px;
	    }
	    
	```

* **ing-michaelvillanueva** (4) [576153](https://platzi.com/comentario/576153/) 

	Así me quedo el diseño ![Screenshot_2019-05-01 Chatangular\(1\).png](https://static.platzi.com/media/user_upload/Screenshot_2019-05-01%20Chatangular%281%29-7385eb06-ab82-4b38-befe-5deb2a99b73e.jpg)

* **David Alejandro Mosquera Moreno** (3) [862481](https://platzi.com/comentario/862481/) 
	
	![bubbleMsg.png](https://static.platzi.com/media/user_upload/bubbleMsg-7c6c4c4e-e97d-46d6-9a32-89e369c4474b.jpg)

* **jehisonorostegui** (3) [632772](https://platzi.com/comentario/632772/) 

	Hi! My doggy
	
	![Captura de Pantalla 2019-06-30 a la\(s\) 12.46.25 p. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202019-06-30%20a%20la%28s%29%2012.46.25%20p.%20m.-45a16a96-e2dd-49db-ac70-813de81f68bd.jpg)

* **isclaem** (2) [570703](https://platzi.com/comentario/570703/) 

	Asi me quedo:
	
	![Captura de Pantalla 2019-04-24 a la\(s\) 11.35.53.png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202019-04-24%20a%20la%28s%29%2011.35.53-4ec6ee2f-2280-41b6-afad-625b0c9d6751.jpg)

* **Wilson Fabian Pérez Sucuzhañay** (2) [367958](https://platzi.com/comentario/367958/) 

	pues no se si quedo igual pero ya va cogiendo forma jaja  
	![Captura de pantalla 2018-08-30 a la\(s\) 11.21.13.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-08-30%20a%20la%28s%29%2011.21.13-5f9e0fa8-6065-4b0d-87e0-1426839f9faa.jpg)

* **Andrés Felipe Giraldo Agudelo** (1) [926340](https://platzi.com/comentario/926340/) 
	
	![Selección_029.png](https://static.platzi.com/media/user_upload/Selecci%C3%B3n_029-625574ee-a347-429d-8639-12042a9251f9.jpg)

* **caprilespe** (1) [798495](https://platzi.com/comentario/798495/) 
	
	![bubblechat.PNG](https://static.platzi.com/media/user_upload/bubblechat-b5124f03-d439-45f8-9c3f-e69bd4afadb7.jpg)

* **Edwin De Jesus Chiyopa Garcia** (1) [625913](https://platzi.com/comentario/625913/) 

	<https://drive.google.com/file/d/1D6p_dztyaTYmKGWCZu-cLM-DC6Qijrrx/view?usp=sharing>  
	![](https://drive.google.com/file/d/1D6p_dztyaTYmKGWCZu-cLM-DC6Qijrrx/view?usp=sharing)

* **egarciab2018** (1) [610677](https://platzi.com/comentario/610677/) 


* **Ruben Garcia** (1) [587980](https://platzi.com/comentario/587980/) 

	Saludos mi proyecto lo estoy trabajando con materialize css, y va quedando de esta manera:
	
	![](https://rubengarcia.com.ve/wp-content/uploads/2019/05/platzi-angular-2.png)

* **JESUS IVAN MENDOZA CONTRERAS** (1) [575002](https://platzi.com/comentario/575002/) 
	
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-aa0a7d55-8cd6-4718-a84f-a839decad4a1.jpg)

* **Ana Lorena Bojorquez Acuña** (1) [557773](https://platzi.com/comentario/557773/) 

	Algo asi (8  
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-6607ebed-c70a-4aca-9c5a-b3f736aafa22.jpg)

	* **FelipeVpz** [557773] (1)

		Me compartes tu codigo? :3

* **Walter Lensinas** (1) [549935](https://platzi.com/comentario/549935/) 

	Buenas tardes, dejo el código de las clase en este repositorio <https://github.com/wlensinas/platzinger-wl.git>
	
	Para ver el [código](https://github.com/wlensinas/platzinger-wl/tree/35-reto):
	
	  1. `git clone https://github.com/wlensinas/platzinger-wl.git`
	  2. `git checkout 21-create-service`
	  3. `npm install`
	  4. `ng serve --open`
	
	
	
	Saludos.
	
	![localhost_4200_conversation_1 \(1\).png](https://static.platzi.com/media/user_upload/localhost_4200_conversation_1%20%281%29-93ca9d5b-84b8-4311-a22a-9b73caa37a58.jpg)

* **Adrian Camilo Caminos** (1) [537642](https://platzi.com/comentario/537642/) 

	algo asi  
	![Screen Shot 2019-03-17 at 5.17.20 PM.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202019-03-17%20at%205.17.20%20PM-93b1b005-04db-48f3-a38d-f962bbfd6ae9.jpg)

* **irodriguezmx** (1) [524072](https://platzi.com/comentario/524072/) 
	
	![platzinger.png](https://static.platzi.com/media/user_upload/platzinger-d8e2d1ef-20cf-4c1e-97e1-28fb7dff8847.jpg)

* **William Vega** (1) [517821](https://platzi.com/comentario/517821/) 

	Tengo curiosidad, una pregunta a todos, cuanto tiempo les llevó hacer este reto? Cual es el tiempo en su opinion que un pro se debería de llevar en hacer algo como esto? Dos horas? toda una mañana? Realmente apreciaría saber su opinión.

* **Ezequiel-Fabbroni** (1) [477719](https://platzi.com/comentario/477719/) 

	Me imagino algo así, saludos  
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-6045efe9-f101-43d2-b00e-e5436098b3c4.jpg)

* **Luis Miguel Ramos Hernández** (1) [464373](https://platzi.com/comentario/464373/) 
	
	![123.png](https://static.platzi.com/media/user_upload/123-0b6a40e0-9060-4ec4-b41e-8bc718493bc2.jpg)

* **Spyderp** (1) [445979](https://platzi.com/comentario/445979/) 
	
	![nuevo_reto.PNG](https://static.platzi.com/media/user_upload/nuevo_reto-7c995d93-26e6-4311-9958-2400762ace3f.jpg)
	
	HTML
	``` 
	    <divid="conversationContainer">
	    <divclass="container-fluid pt-3 sendMsn">
	      <divclass="row align-items-start">
	        <divclass="col-3  col-md-2 col-lg-1 ">
	          <divclass="avatarFrameonline">
	            <img class="avatarImage img-fluid" src="assets/img/generic_avatar.png" alt="Avatar generico">
	          </div>
	        </div>
	        <divclass="col">
	          <h1><b>Amigo</b> (Online)</h1>
	          <b>Mensaje Personal</b>
	          <hr>
	          <divclass="msg">
	            <divclass="msgMe"> <img class="img-fluid" src="assets/img/generic_avatar.png" alt="Avatar generico"><span>Hola</span></div>
	            <divclass="msgYou"> <span>Hola</span><img class="img-fluid" src="assets/img/generic_avatar.png" alt="Avatar generico"></div>
	            <divclass="msgMe"> <img class="img-fluid" src="assets/img/generic_avatar.png" alt="Avatar generico"><span>Como tas</span></div>
	            <divclass="msgYou"> <span>bien tú</span><img class="img-fluid" src="assets/img/generic_avatar.png" alt="Avatar generico"></div>
	          </div>
	        </div>
	      </div>
	      <divclass="row lign-items-end">
	        <divclass="col-3  col-md-2 col-lg-1">
	            <divclass="avatarFrameonline">
	              <img class="avatarImage img-fluid" src="assets/img/generic_avatar.png" alt="Avatar generico">
	            </div>
	        </div>
	        <divclass="col">
	          <divclass="msgArea">
	          <textarea></textarea>
	          <divclass="row">
	            <divclass="col">
	              <img src="assets/img/zumbido.png"class="icon">
	            </div>
	            <divclass="col-3 col-md-1">
	              <button class="btn btn-primary">Enviar</button>
	            </div>
	          </div>
	          </div>
	        </div>
	      </div>
	    </div>
	    </div>
	    
	```
	
	Código en SASS ( estoy trabajando el curso así)
	``` 
	    #conversationContainer
	      background-image: url(/assets/img/msnbg.jpg)
	      background-size:100%
	      background-repeat:no-repeat
	    
	    .msg
	      height:350px
	      overflow-y: auto
	      .msgMe, .msgYou
	        img
	          width:32px
	          border-radius:15px
	        span
	          border-radius:10px
	          padding:3px 5px
	      .msgMe
	        span
	          margin-left:5px
	          background-color:#EAECEB
	      .msgYou
	        text-align: right
	        span
	          margin-right:5px
	          background-color:#B8E5F9
	    .msgArea
	      background:#ffffff
	      border:1px solid #cccccc
	      textarea
	        width:100%
	        height:86px
	        border:1px solid #cccccc
	    
	    img.icon
	      width:30px```
	    
	    
	```

* **Emerson-Lirmi** (1) [424009](https://platzi.com/comentario/424009/) 

	![Sin título.jpg](https://static.platzi.com/media/user_upload/Sin%20t%C3%ADtulo-e6788bf4-16d2-4fb6-a15a-672ce50590e9.jpg)![](url)

* **Alexander Sandoval** (1) [418609](https://platzi.com/comentario/418609/) 

	Va quedando así:  
	![conversation.png](https://static.platzi.com/media/user_upload/conversation-156753d2-63b1-4c27-8f77-d36120df4a42.jpg)
	
	Pueden obtener algunos efectos burbujas:
	
	* Acá:  
	<https://leaverou.github.io/bubbly/>
	* Y aquí también:  
	<https://codepen.io/Founts/pen/gmhcl>
	
	

* **Jeffry Davila** (1) [398943](https://platzi.com/comentario/398943/) 

	Asi me quedo…  
	![enviar_platzi.JPG](https://static.platzi.com/media/user_upload/enviar_platzi-4665a90e-c7b6-449f-94d1-a434dffd0949.jpg)

* **rodspek** (1) [381998](https://platzi.com/comentario/381998/) 

	Me quedo de la siguiente forma:  
	![Reto3AAdv.JPG](https://static.platzi.com/media/user_upload/Reto3AAdv-54325197-33cd-4cef-a0ce-591cff71e781.jpg)

* **Ana Lorena Bojorquez Acuña** (1) [56849](https://platzi.com/comentario/557773/) 
Algo asi (8

	* **FelipeVpz** [56849] (1)

		Me compartes tu codigo? :3

# Acceso a datos remotos y login [2351]

## 0360. ¿Qué es Firebase Creando nuestro proyecto [12779](https://platzi.com/clases/1340-angular-avanzado/12779-que-es-firebase-creando-nuestro-proyecto/)

### Descripción:


Firebase es un servicio de backend ofrecido por Google de manera gratuita. Provee entre sus utilidades, una base de datos remota más parecida a Mongo que SQL ya que es del tipo no-relacional.

Para implementar este servicio es necesario acceder a la consola de Firebase con una cuenta Google, y seguir las instrucciones de implementación en la sección Base de Datos en Tiempo Real.

### Links:

* [Firebase](https://firebase.google.com)

### Comentarios:

* **makitocode** (7) [416859](https://platzi.com/comentario/416859/) 

	Deberían darse una vuelta por firebase, es muy poderoso y tienen una gran capa free.  
	Te ahorra mucho tiempo y $$. y aún pagando, los costos son muy bajos para tener todo lo ofrecen.  
	Actualmente trabajo con Firebase y me ha parecido una maravilla.

	* **Jecsham Castillo** [416859] (3)

		Firebase es ideal para iniciar startups

	* **Víctor Alejandro Rueda Gómez** [416859] (2)

		Recomiendo los meetup de firebase <https://www.meetup.com/es/GDG-Firebase-Mexico/> (dan cheve y pizza), ahí es donde yo los conocí, y en donde trabajo ya lo he usado para producción a un costo muy bajo.

* **TlalocES** (4) [492370](https://platzi.com/comentario/492370/) 

	Yo creo que firebase puede estar bien para empezar pero desde luego te ata dado que no es un sql tradicional es algo diferente y estas arrastrado a que si te suben el precio algo que ya hicieron <https://startupsventurecapital.com/firebase-costs-increased-by-7-000-81dc0a27271d> el hecho de ir a otro lado hace que tengas que rehacer todo tu back dado que el diseño de sus herramientas no son tan standard, quizá esta bien para según que cosas pero en mi opinión es como usar wix en vez de aprender diseño.

	* **William Vega** [492370] (1)

		Auna a esto que toda la información confidencial de tus clientes pasa por el devorador de información que es Google y la ecuación no es del todo favorable, en especial para guardar información de temas sensibles como tarjetas de crédito y expedientes médicos. No lo sé, ustedes que opinan?

* **Adrian Camilo Caminos** (2) [537643](https://platzi.com/comentario/537643/) 

	es muy bueno para ciertas cosas pero si tu aplicacion comienza a crecer el costo va incrementar bastante

* **Sigaweb** (2) [498130](https://platzi.com/comentario/498130/) 

	Esto es lo que he necesitado hacer, para aprender a consumir una api,

* **Gonzalo Muñoz** (1) [685323](https://platzi.com/comentario/685323/) 

	Consulta, siempre veo que en cursos de Angular u otros ocupan Firebase. Entiendo que es porque es rápido tener implementada la base de datos y backend, mi pregunta, es utilizada esta solución a nivel empresarial? Quizás es más rápido de implementar, pero trae mayores costos asociados a la larga.  
	Alguien sabe qué tanto se usa Firebase a nivel de empresas?

	* **tecnox** [685323] (1)

		Lo que puedo afirmar es que Firebase es usado como una herramienta para Startups, lo cual no necesariamente la aleja de empresas consolidadas, sin embargo se de muy pocas que lo usen mas alla de prototyping.
		
		Saludos

## 0370. Diferencia entre conexión por sockets y HTTP [12780](https://platzi.com/clases/1340-angular-avanzado/12780-diferencia-entre-conexion-por-sockets-y-http/)

### Descripción:


Conexión HTTP:

* Se establece la comunicación al servidor
* Se solicitan los recursos
* Se reciben los recursos
* Se confirman recibidos los recursos
* Se cierra la conexión



Esto se repite por cada requerimiento de recursos que sean necesarios.

Conexión con sockets:

* Se establece la comunicación al servidor
* Se solicitan los recursos
* Se reciben los recursos
* Se confirman recibidos los recursos
* La comunicación queda abierta y escuchando posibles cambios en los recursos



Al suceder algún cambio en el recurso, el servidor notifica al navegador sin volver abrir nuevas conexiones.

### Comentarios:

* **Erik Fernando Ajú Mota** (6) [403540](https://platzi.com/comentario/403540/) 

	<https://hackernoon.com/how-we-spent-30k-usd-in-firebase-in-less-than-72-hours-307490bd24d>

	* **danielcarmonajaramillo** [403540] (1)

		Esa fue la introducción que me dieron en mi clase de base de datos Oracle… Es impactante, luego de eso mi vida cambió, buen articulo para entender qué es Firebase hahaha

* **Alex Eugenio Gavidia Donayre** (3) [552232](https://platzi.com/comentario/552232/) 
El costo es muy caro? Dependiendo, porque si. Tu aplicación crece, tus ingresos crece. Y deberías invertir más

* **Alex Eugenio Gavidia Donayre** (2) [552233](https://platzi.com/comentario/552233/) 
Quiten esa idea arcaica de que es muy caro.

* **makitocode** (2) [416880](https://platzi.com/comentario/416880/) 

	Cabe mencionar que Firebase funciona a través de http (Api) o a través de sockest con librerías como AngularFire (<https://github.com/angular/angularfire2>).
	
	Cómo funciona a través de http ?, el link que aparece en cada referencia de la bd (colección - like- Tabla) es la referencia a los datos de esa colección. Usando por ejemplo get, podemos obtener todos los datos de ese nodo o colección.
	
	Para RealTime Database  
	Vamos a suponer que nuestro proyecto tiene la colección **Users**  
	el link que aparece sobre la colección Users es <https://testingfirebase-74175.firebaseio.com/Users>  
	Lo único que tenemos q hacer es adicionar a la url '.json’  
	Es decir, la url  
	<https://testingfirebase-74175.firebaseio.com/Users.json> te da acceso a la colección usuarios.
	
	Así mismo, si queremos acceder a un solo recurso (un solo usuario) o una colección dentro de users usamos la misma estructura, es decir  
	Con la url <https://testingfirebase-74175.firebaseio.com/Users/1/network.json> se puede acceder a la colección network dentro del usuario con el id = 1.

* **Carlos Uriel de Jesus Sánchez González** (1) [399134](https://platzi.com/comentario/399134/) 

	Conexión HTTP:
	
	Se establece la comunicación al servidor  
	Se solicitan los recursos  
	Se reciben los recursos  
	Se confirman recibidos los recursos  
	Se cierra la conexión  
	Esto se repite por cada requerimiento de recursos que sean necesarios.
	
	Conexión con sockets:
	
	Se establece la comunicación al servidor  
	Se solicitan los recursos  
	Se reciben los recursos  
	Se confirman recibidos los recursos  
	La comunicación queda abierta y escuchando posibles cambios en los recursos

## 0380. Instalación y setup de la librería AngularFire a través de npm [12781](https://platzi.com/clases/1340-angular-avanzado/12781-instalacion-y-setup-de-la-libreria-angularfire-a-t/)

### Descripción:


Para conectar nuestro proyecto a los servicios de Firebase, usamos AngularFire, disponible en los repositorios de paquetes de npm. Al crear un proyecto en Firebase se nos muestran varias opciones de configuración. La opción de configuración web es la que vamos a utilizar, al obtener los datos y credenciales de autenticación las copiamos en el archivo `environment.ts` y en `environment.prod.ts` para que estén disponibles tanto en el ambiente de desarrollo como en producción.

Una vez creadas las variables de configuración será necesario importar los módulos AngularFireModule y environment en `app.modules.ts`. Finalmente incluímos las clases de Firebase que usaremos en nuestro proyecto en la sección imports: AngularFireAuthModule, AngularFireStorageModule y AngularFireDatabaseModule.

### Links:

* [GitHub - angular/angularfire2: The official Angular library for Firebase.](https://github.com/angular/angularfire2)

### Comentarios:

* **Poseidonihp** (24) [403819](https://platzi.com/comentario/403819/) 

	La Documentación cambio para realizarla como esta en Octubre de 2018 se realiza los imports de los módulos asi.
	``` 
	    npm install @angular/fire firebase --save
	    
	```
	``` 
	    import {AngularFireModule} from '@angular/fire';
	    import { AngularFirestoreModule } from '@angular/fire/firestore';
	    import { AngularFireStorageModule } from '@angular/fire/storage';
	    import { AngularFireAuthModule } from '@angular/fire/auth';
	    import { AngularFireDatabaseModule } from '@angular/fire/database';
	    
	    imports: [
	        BrowserModule,
	        RouterModule.forRoot(appRoutes),
	        FormsModule,
	        AngularFireModule.initializeApp(environment.firebase),
	        AngularFirestoreModule, // imports firebase/firestore, only needed for database features
	        AngularFireAuthModule, // imports firebase/auth, only needed for auth features,
	        AngularFireStorageModule ,
	        AngularFireDatabaseModule
	    
	      ]
	    
	```

	* **Ricardo Asin** [403819] (1)

		Gracias!

	* **Gabriel Solorzano** [403819] (3)

		import { AngularFireDatabaseModule } from ‘@angular/fire/database’;
		
		Gracias

	* **Miguel Castillo Cortes** [403819] (1)

		súper !!! gracias =)

	* **elkinidarg** [403819] (1)

		Gracias

	* **Kevin Brayan Luna Figueroa** [403819] (1)

		Gracias!!

* **makitocode** (6) [416884](https://platzi.com/comentario/416884/) 

	Sin importar cuándo estén viendo este video, Junio, Diciembre, Enero… y como todas las versiones cambian seguido (angular, firebase), guiénse siempre por la documentación oficial de [AngularFire2](https://github.com/angular/angularfire2).
	
	Instalación y setup  
	<https://github.com/angular/angularfire2/blob/master/docs/install-and-setup.md>
	
	Siguen los pasos y listo!, siempre estarán actualizados.

* **Arturo Mojica Guerrero** (2) [814547](https://platzi.com/comentario/814547/) 

	Nueva url de firebase para continuar con el proyecto, aunque entre versiones el proceso es el mismo. <https://github.com/angular/angularfire/blob/master/docs/install-and-setup.md>

* **Elberth Jair Agreda Rosero** (2) [780594](https://platzi.com/comentario/780594/) 

	Solo tengan cuidado con subir credenciales de accesos a repositorios públicos.

* **Adrián San Martín** (2) [521180](https://platzi.com/comentario/521180/) 

	Hola, yo corrí el comando
	``` 
	    npm install @angular/fire firebase --save
	    
	```
	
	y digamos que se me olvido anexar la otra bandera “-exact” , ¿Se puede agregar después?

	* **Gabriel Solorzano** [521180] (1)

		Creo que lo que tendrías que hacer es quitar el “gorrito” como lo llama el profesor en el archivo package.json
		
		Ya que cuando se instala la librería allí, si no pones el -exact el pondría el caracter ^ para indicar que se puede instalar una versión más actualizada.
		
		Si tienes algo como esto:
		``` 
		    "bootstrap": "^4.3.1",
		    
		```
		
		Con quitarle el ^ bastaría

* **Jose Adan Ardila Sanchez** (2) [398821](https://platzi.com/comentario/398821/) 

	En la documentación hablan de que la interacción con la base de datos se hace con AngularFirestore que que fue uno de los módulos importados, recomendarían ustedes empezar a trabajar con esta base de datos desde ahora, saben si hay alguna fecha en la que salga el primer release?

	* **makitocode** [398821] (1)

		Es lo mejor. En firebase existen 2 tipos de bases de datos.
		
		* RealTime
		* FireStore
		
		
		
		RealTime fue la primera base de datos que tuvo firebase y como todo, la evolución de ese producto es FireStore. Promete y tiene muchas opciones adicionales y es más sencillo de gestionar y toda su documentación y tutoriales están inclinados hacia esta base de datos.
		
		Para tomar una buena desición, pueden ver este link  
		<https://firebase.google.com/docs/database/rtdb-vs-firestore>

* **Jhon Castrillon** (1) [558833](https://platzi.com/comentario/558833/) 

	npm install @angular/fire firebase --save

* **Rarvac** (1) [430464](https://platzi.com/comentario/430464/) 

	Como puedo solucionar el siguiente error:?
	``` 
	    <$ ng serve -o
	    Could not find module "@angular-devkit/build-angular" from "R:\\Angular\\Platzi\\platzinger".
	    Error: Could not find module "@angular-devkit/build-angular" from "R:\\Angular\\Platzi\\platzinger".
	        at Object.resolve (C:\Users\Raul\AppData\Roaming\npm\node_modules\@angular\cli\node_modules\@angular-devkit\core\node\resolve.js:141:11)
	        at Observable.rxjs_1.Observable [as _subscribe] (C:\Users\Raul\AppData\Roaming\npm\node_modules\@angular\cli\node_modules\@angular-devkit\architect\src\architect.js:132:40)
	        at Observable._trySubscribe (C:\Users\Raul\AppData\Roaming\npm\node_modules\@angular\cli\node_modules\rxjs\internal\Observable.js:44:25)
	        at Observable.subscribe (C:\Users\Raul\AppData\Roaming\npm\node_modules\@angular\cli\node_modules\rxjs\internal\Observable.js:30:22)
	        at C:\Users\Raul\AppData\Roaming\npm\node_modules\@angular\cli\node_modules\rxjs\internal\Observable.js:99:19
	        at new Promise (<anonymous>)
	        at Observable.toPromise (C:\Users\Raul\AppData\Roaming\npm\node_modules\@angular\cli\node_modules\rxjs\internal\Observable.js:97:16)
	        at ServeCommand.initialize (C:\Users\Raul\AppData\Roaming\npm\node_modules\@angular\cli\models\architect-command.js:91:94)
	        at process._tickCallback (internal/process/next_tick.js:68:7)
	        at Function.Module.runMain (internal/modules/cjs/loader.js:744:11)>
	    
	```

	* **Cristian David Franco Garcia** [430464] (1)

		npm install --save-dev @angular-devkit/build-angular

* **Juan Diego Lopez Triana** (1) [373122](https://platzi.com/comentario/373122/) 

	Ahora AngularFire se instala con el siguiente comando:
	``` 
	    npm install firebase angularfire2 --save
	    
	```

	* **Juan Carlos Felizzola Vega** [373122] (4)

		Acabo de mirar la documentación y me aparece:
		``` 
		    npm install @angular/fire firebase --save
		    
		```
		
		Aunque para que funcionara tuve que hacer algunos ajustes.

	* **makitocode** [373122] (1)

		por eso lo mejor es ir a la documentación, sin importar cuándo vean este video.
		
		Instalación y setup  
		<https://github.com/angular/angularfire2/blob/master/docs/install-and-setup.md>

	* **makitocode** [373122] (1)

		Angular 7 ya trae integrado la librería de AngularFire2 hahaha!

* **Yulissa Terán Cerquín** (1) [64935](https://platzi.com/comentario/683884/) 
¿En qué curso puedo obtener más información sobre conexión por sockets?

* **Rarvac** (1) [46364](https://platzi.com/comentario/430464/) 
Como puedo solucionar el siguiente error:? <$ ng serve -o Could not find module "@angular-devkit/build-angular" from "R:\\\Angula...

	* **Cristian David Franco Garcia** [46364] (1)

		npm install --save-dev @angular-devkit/build-angular

## 0390. LoginRegistro de usuarios con email y password [12782](https://platzi.com/clases/1340-angular-avanzado/12782-loginregistro-de-usuarios-con-email-y-password6583/)

### Descripción:


Para implementar el servicio de Firebase Authentication con email y password crearemos un nuevo servicio con AngularCLI. Al usar un servicio, esta funcionalidad estará disponible en todos los componentes del proyecto en los que lo inyectemos.

Creamos los métodos relaciones con la funcionalidad de autenticación: loginWithEmail, registerWithEmail, getStatus y logOut utilizando las funciones provistas por la API de Firebase. Para hacer uso de este servicio debemos inyectarlo en los componentes de las pantallas de nuestra app.

Para hacer uso de este servicio importamos el módulo AngularFireAuth y lo pasamos al constructor. Luego en el componente tendremos que inyectar el servicio authenticationService, también en el constructor del componente.

Es necesario habilitar en Firebase el modo de autenticación de Email y Password para poder usar esta funcionalidad, y como queremos incluir el nickname y otros atributos del usuario, además de estos dos, nos apoyaremos luego en la base de datos de Firebase.

### Comentarios:

* **Teofilo Rosales Gama** (10) [392174](https://platzi.com/comentario/392174/) 

	Para que el codigo funcione igual que en el video la importacion debe ser asi:
	``` 
	    import { AngularFireAuth } from '@angular/fire/auth';
	    
	```

	* **moises mannarino** [392174] (1)

		en que documentacion revisaste para descubrir que los imports iban asi

	* **Ricardo Asin** [392174] (2)

		@Moises en la documentacion oficial

	* **Gerardo Manuel Reyes Fernández** [392174] (2)

		Documentación oficial  
		<https://github.com/angular/angularfire2/blob/master/docs/auth/getting-started.md>

	* **Miguel Castillo Cortes** [392174] (1)

		super !!!

	* **Rarvac** [392174] (1)

		en la pagina de GitHub… dice:
		
		**import { AngularFireAuthModule } from ‘@angular/fire/auth’;**

* **Elberth Jair Agreda Rosero** (5) [780638](https://platzi.com/comentario/780638/) 

	Si trabajan con versiones recientes al día de hoy, el cambio en el import es:  
	import { AngularFireAuth } from ‘@angular/fire/auth’;

* **Alexander Sandoval** (5) [419312](https://platzi.com/comentario/419312/) 

	Para resolver el reto necesitamos **habilitar el proceso de autenticación con Facebook** :
	
	  1. Lo primero que debemos hacer es ir, en la consola de nuestro proyecto en Firebase, a la sección de _Authentication_ , en la pestaña de Método de inicio de sesión o _SignIn Method_ y habilitar el método Facebook donde debemos colocar el _App ID_ y el _App Secret_. Para obtenerlos vamos a [Facebook for Developers](https://developers.facebook.com/) (previo inicio de sesión en Facebook) y **agregamos nuestra aplicación** (en la parte superior derecha), luego en la sección **Configuración > Básica** obtenemos nuestros _App ID_ y el _App Secret_.
	
	  2. Una vez de vuelta en la consola de Firebase copia la URI de redireccionamiento (justo antes de guardar en la pestaña para habilitar el inicio de sesión con Facebook) y la agregamos en el producto de inicio de sesión con Facebook de nuestra aplicación en la consola de Facebook. Para ello vamos, en la parte derecha, a **Productos > Inicio de sesión con Facebook > Configuración** a la sección URI de redireccionamiento de OAuth válidos, agregamos la URI que nos provee Firebase y guardamos los cambios.
	
	
	
	
	En este punto ya configuramos el proceso de autenticación con Facebook en nuestro proyecto de Firebase y estamos listos para implementar el inicio de sesión con Facebook en nuestra aplicación.
	
	**Nota:** justo antes de guardar el proceso de autenticación de Facebook en Firebase hay un enlace [Más información](https://firebase.google.com/docs/auth/), sección Integración con proveedores de identidad federada > Facebook > Web, donde se detalla el proceso.
	
	**Implementación de método de autenticación con Facebook en nuestra aplicación Angular6:**
	
	  1. En nuestro servicio `authentication.service.ts` agregamos el método `logInWithFacebook()` e importamos las funcionalidad de firebase/app:
	
	
	``` 
	    import * as firebase  from'firebase/app'
	    
	    ...
	    
	    logInWithFacebook() {
	        let provider = new firebase.auth.FacebookAuthProvider();
	        returnthis.angularFireAuth.auth.signInWithPopup(provider);
	      }
	    
	```
	
	  1. En nuestro componente `login.component.ts` agregamos la llamada al método que acabamos de crear en nuestro servicio:
	
	
	``` 
	    loginWithFacebook() {
	        this.autheticationService.loginWithFacebook()
	          .then( data => {
	            alert('Logeado con Facebook correctamente')
	            console.log(data)
	          })
	          .catch( error => {
	            alert('Ocurrió un error')
	            console.log(error)
	          })
	      }
	    
	```
	
	  1. Y finalmente agregamos un botón en la plantilla del componente que ejecute la llamada del proceso de autenticación:
	
	
	``` 
	    <a (click)="loginWithFacebook()" *ngIf="operation == 'login'"class="btn btn-primary facebook">Logear con facebook</a>
	    
	```

	* **rprado** [419312] (1)

		Super bien explicado, siempre es un problema que facebook cambia la interfaz de las opciones de developer pero basta con una pequeña busqueda y listo.

	* **Angel Javier Puc Yamá** [419312] (1)

		Gracias !

* **Juan Diego Lopez Triana** (4) [373174](https://platzi.com/comentario/373174/) 

	Así resolví el reto:
	
	**auth.service.ts**
	``` 
	    import { Injectable } from'@angular/core';
	    import * as firebase  from'firebase/app'
	    import { AngularFireAuth } from'angularfire2/auth'
	    
	    @Injectable({
	      providedIn: 'root'
	    })
	    exportclassAuthService{
	    	constructor(private angularFireAuth: AngularFireAuth) { }
	      	loginWithFacebook() {
	        		const provider = new firebase.auth.FacebookAuthProvider()
	        		provider.setCustomParameters({
	          		'display': 'popup'
	        		})
	    
	        		returnthis.angularFireAuth.auth.signInWithPopup(provider)
	      	}	
	    }
	    
	```
	
	**login.component.ts**
	``` 
	    asyncloginWithFacebook () {
	        try {
	          const data = awaitthis.authService.loginWithFacebook()
	          alert('Logged with facebook successful!')
	        } catch (err) {
	          this.authService.handleFatalError(err)
	        }
	      }
	    
	```

* **Adrian Camilo Caminos** (3) [542843](https://platzi.com/comentario/542843/) 

	aqui esta la nueva documentacion
	
	<https://github.com/angular/angularfire2/blob/master/docs/auth/getting-started.md>

* **charlieg** (2) [637928](https://platzi.com/comentario/637928/) 

	Tengo todas las instrucciones como los dio el instructor, pero al presionar iniciar sesion, este siempre me dirije al home.

	* **Marival** [637928] (1)

		a mi me pasa lo mismo, entontraste la solución?

	* **Marival** [637928] (1)

		Mi solución fue cambiar las etiquetas <a> por botones, así…  
		<div class=“center marto15”>  
		<button (click)=“login()” *ngIf=“operation == ‘login’” class=“btn btn-primary” href="">Iniciar Sesión</button>  
		<button (click)=“register()” *ngIf=“operation == ‘register’” class=“btn btn-primary” href="">Registrarme</button>  
		</div>

	* **eric-alejandro-asce** [637928] (1)

		asegúrate que no tengas el “href” definido dentro de la etiqueta <a>

* **Diego Mauricio Mejía Ospina** (2) [531980](https://platzi.com/comentario/531980/) 

	El código funciona con:
	``` 
	    import { AngularFireAuthModule } from '@angular/fire/auth';
	    
	```

* **luisangeldev** (2) [514965](https://platzi.com/comentario/514965/) 

	Así resolví la parte de login  
	**authentication.service.ts**
	``` 
	    import { Injectable } from '@angular/core';
	    import { AngularFireAuth } from '@angular/fire/auth';
	    import * as firebase from 'firebase/app';
	    
	    @Injectable({
	      providedIn: 'root'
	    })
	    export class AuthenticationService {
	    
	      constructor(
	        private angularFireAuth: AngularFireAuth
	      ) { }
	    
	      loginSocial() {
	        returnthis.angularFireAuth.auth.signInWithPopup(new firebase.auth.FacebookAuthProvider());
	      }
	    
	      loginWithEmail(email: string, password: string) {
	        returnthis.angularFireAuth.auth.signInWithEmailAndPassword(email, password);
	      }
	    
	      registerWithEmail(email: string, password: string) {
	        returnthis.angularFireAuth.auth.createUserWithEmailAndPassword(email, password);
	      }
	    
	      getStatus() {
	        returnthis.angularFireAuth.authState;
	      }
	    
	      logOut() {
	        returnthis.angularFireAuth.auth.signOut();
	      }
	    }
	    
	```
	
	**login.component.ts**
	``` 
	    import { Component, OnInit } from '@angular/core';
	    import { AuthenticationService } from 'src/app/services/authentication.service';
	    
	    @Component({
	      selector: 'app-login',
	      templateUrl: './login.component.html',
	      styleUrls: ['./login.component.scss']
	    })
	    export classLoginComponentimplementsOnInit {
	      public operation: string;
	      public email: string = null;
	      public password: string = null;
	    
	      constructor(
	        private authenticationService: AuthenticationService
	      ) {
	          this.operation = 'login';
	      }
	    
	      ngOnInit() {
	      }
	      loginSocial() {
	        this.authenticationService.loginSocial().then(
	          (data) => {
	            alert('Social Login Correcto');
	            console.log(data);
	          }
	        ).catch(
	          (error) => {
	            alert('Login Social Falló');
	            console.log(error);
	          }
	        );
	      }
	    
	      login() {
	        this.authenticationService.loginWithEmail(this.email, this.password).then(
	          (data) => {
	            alert('Loggeado correctamente');
	            console.log(data);
	          }
	        ).catch(
	          (error) => {
	            alert('Ocurrió un error');
	            console.log(error);
	          }
	        );
	      }
	      register() {
	        this.authenticationService.registerWithEmail(this.email, this.password)
	        .then(
	          (data) => {
	            alert('Registrado correctamente');
	            console.log(data);
	          }).catch(
	            (error) => {
	            alert('Ocurrió un error en el registro');
	            console.log(error);
	          });
	      }
	    }
	    
	    
	```

* **Jose Aladino Ospina Lopez** (2) [391009](https://platzi.com/comentario/391009/) 

	Los imports de la versión que acabo de bajar no van con ‘angularfire2’ sino con ‘@angular/fire’ así:
	``` 
	    import { AngularFirestoreModule } from '@angular/fire/firestore';
	    import { AngularFireStorageModule } from '@angular/fire/storage';
	    import { AngularFireAuthModule } from '@angular/fire/auth';
	    import { AngularFireDatabaseModule } from '@angular/fire/database'
	    
	```

	* **moises mannarino** [391009] (1)

		en que documentacion revisaste para descubrir que los importanos iban asi?

	* **moises mannarino** [391009] (1)

		en que documentacion revisaste para descubrir que los imports iban asi

	* **Gerardo Manuel Reyes Fernández** [391009] (1)

		<https://github.com/angular/angularfire2/blob/master/docs/auth/getting-started.md>

* **Juan Antonio Campoy Lira** (1) [977994](https://platzi.com/comentario/977994/) 
	
	![boton.jpg.png](https://static.platzi.com/media/user_upload/boton.jpg-7aff7bee-5cec-48fa-9335-8a6cea8efe05.jpg)
	
	Vamos

* **caprilespe** (1) [799349](https://platzi.com/comentario/799349/) 

	authentication.service.ts
	
	import
	``` 
	    import * as firebase from'firebase/app';
	    
	```
	``` 
	      loginWithFacebook(){
	        const provider = new firebase.auth.FacebookAuthProvider();
	        returnthis.angularFireAuth.auth.signInWithPopup(provider);
	      }
	    
	```
	
	login.component.ts
	``` 
	      loginWithFacebook() {
	        this.authenticationService.loginWithFacebook().then((data)=>{
	          alert("Loggeado correctamente");
	          console.log(data);
	        }).catch((error)=>{
	          alert("Ocurrio un error");
	          console.log(error);
	        });
	      }
	    
	```
	
	Resultado:
	
	![loginWithFacebook.PNG](https://static.platzi.com/media/user_upload/loginWithFacebook-eec2f752-bfa4-48a0-b3bb-087713e62981.jpg)

* **Samuel Gonzalez Alvarez** (1) [749506](https://platzi.com/comentario/749506/) 

	El código me marca error Cannot find name en “onrejected” y en “onfulfilled”. He buscado en la documentación pero no consigo resolverlo, a alguien le ha sucedido?

* **JorgeLopez88** (1) [581058](https://platzi.com/comentario/581058/) 

	Tengo el siguiente error al momento de importar desde Firebase y no he logrado solucionarlo, alguien que me ayude, hice exactamente los pasos del vídeo.  
	![](!%5BErrorFireBase.PNG%5D\(https://static.platzi.com/media/user_upload/ErrorFireBase-7aded385-39fc-4131-a75f-4815c09522d0.jpg\))

* **JESUS IVAN MENDOZA CONTRERAS** (1) [578147](https://platzi.com/comentario/578147/) 

	saludos. alguien sabe porque da este error.
	
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-ef5d4c78-ca32-4e02-8e56-ecaaf36dee2a.jpg)

	* **Diego Alexander Forero Higuera (Platzi)** [578147] (1)

		Hola tienes que incluir la url de tu servidor en la app de facebook que creaste para el login, si usas localhost debes tener un servidor que corra por https ya que facebook ya no recibe urls con protocolo http.

* **Víctor Julio Molano Bolívar** (1) [576072](https://platzi.com/comentario/576072/) 

	Tengo este error, alguna sugerencia ?
	
	ERROR in node_modules/@angular/fire/firebase.app.module.d.ts(17,22): error TS2420: Class ‘FirebaseApp’ incorrectly implements interface ‘App’.  
	Property ‘performance’ is missing in type ‘FirebaseApp’ but required in type ‘App’.

	* **ing-michaelvillanueva** [576072] (1)

		ya lograste solucionarlo ?? tengo el mismo error

	* **Diego Alexander Forero Higuera (Platzi)** [576072] (1)

		Por lo que leo en el error es que App es una interface que tiene la propiedad performance pero no esta implementada en FirebaseApp, están usando las mismas versiones de las librerías que se usan en el curso?, es probable que algo haya cambiado en una nueva versión y se tenga que implementar de forma diferente.

	* **Walter Lensinas** [576072] (1)

		Por las dudas @victormolano, subí el código a github y compartí el repositorio así lo vemos.

* **veronica oviedo** (1) [570055](https://platzi.com/comentario/570055/) 

	Este es mi reto, autenticacion por medio de Facebook y Google.
	``` 
	     loginWithEmail(email: string, password: string) {
	        returnthis.afAuth.auth.signInWithEmailAndPassword(email, password);
	      }
	      loginWithFacebook() {
	        const provider = new firebase.auth.FacebookAuthProvider();
	        returnthis.afAuth.auth.signInWithPopup(provider);
	      }
	      loginWithGoogle() {
	        const provider = new firebase.auth.FacebookAuthProvider();
	        provider.addScope('profile');
	        provider.addScope('email');
	        returnthis.afAuth.auth.signInWithPopup(provider);
	      }
	    
	```

* **Luis Rodriguez** (1) [556939](https://platzi.com/comentario/556939/) 

	a mi me funcionó quitando el “onfulfilled” y el “onrejected”,
	
	login.component.ts
	``` 
	    import { Component, OnInit } from '@angular/core';
	    import { AuthenticationService } from '../services/authentication.service';
	    
	    @Component({
	      selector: 'app-login',
	      templateUrl: './login.component.html',
	      styleUrls: ['./login.component.css']
	    })
	    export classLoginComponentimplementsOnInit {
	    operation: string = 'login';
	    email: string = null;
	    password: string = null;
	      constructor(private authenticateService: AuthenticationService) { }
	    
	      ngOnInit() {
	      }
	      
	      login() {
	        this.authenticateService.loginWithEmail(this.email, this.password).then( 
	          (data) => {
	            alert('Loggeado correctamente');
	          }).catch( (error) => {
	            alert('Ocurrio un error');
	            console.log(error);
	          });
	      }
	    
	      register() {
	        this.authenticateService.registerWithEmail(this.email, this.password).then( 
	          (data) => {
	            alert('Registrado correctamente');
	          }).catch( (error) => {
	            alert('Ocurrio un error');
	            console.log(error);
	          });
	      }
	    
	    }
	    
	```

* **Rarvac** (1) [550687](https://platzi.com/comentario/550687/) 

	_Estimada comunidad, tengo un problema._
	
	no me devuelve los datos en consola al momento de hacer login o register.  
	en Firebase esta todo bien, si registra y si logea pero cada ves que se ejecuta una de esas ordenes (login o register) en **4200/platzinger/login** => me envia a **4200/platzinger/home** y el
	``` 
	    console.log ()  ``` nose muestra enla consola del Chrome
	    
	```

	* **Luis Rodriguez** [550687] (1)

		hola! cómo vas, hermano?
		
		tienes el siguiente código en tu archivo de login.component.ts ?
		``` 
		    alert('Loggeado correctamente');
		          }).catch( (error) => {
		            alert('Ocurrio un error');
		            console.log(error);
		          });```
		```

* **Alfonso Adame Rueda** (1) [538332](https://platzi.com/comentario/538332/) 

	![](![angular2.PNG](https://static.platzi.com/media/user_upload/angular2-c95f308b-a077-460d-aafc-a958fea90d97.jpg)

* **Alfonso Adame Rueda** (1) [538329](https://platzi.com/comentario/538329/) 

	![](![angular.PNG](https://static.platzi.com/media/user_upload/angular-3dda344e-71fd-405a-a28c-6d14828b3377.jpg)

* **Alfonso Adame Rueda** (1) [538310](https://platzi.com/comentario/538310/) 

	hola buenas tardes, me sale este error:compiler.js:1021 Uncaught Error: Unexpected value ‘AngularFireAuth’ imported by the module ‘AppModule’. Please add a @NgModule annotation,  
	quien me ayuda por favor?

	* **Diego Alexander Forero Higuera (Platzi)** [538310] (1)

		Por lo que veo en las capturas que compartiste AngularFireAuth no esta agregado en el array de declarations en el NgModules, prueba agregarlo y esto debe solucionar el problema.

* **Alfonso Adame Rueda** (1) [538305](https://platzi.com/comentario/538305/) 
	
	![angular3.PNG](https://static.platzi.com/media/user_upload/angular3-9a19fe1f-d800-4fab-ac23-d9949118fbcd.jpg)

	* **Jenny Katherine Aguilera Morales** [538305] (1)

		Importalo así:
		
		`import { AngularFireAuthModule } from '@angular/fire/auth';`
		
		<https://github.com/angular/angularfire2/blob/master/docs/install-and-setup.md>

* **Spyderp** (1) [446475](https://platzi.com/comentario/446475/) 

	Mi forma de Solucionarlo  
	authentication.service.ts
	``` 
	    import { Injectable } from '@angular/core';
	    import { AngularFireAuth } from '@angular/fire/auth';
	    import * as firebase from 'firebase/app';
	    
	    @Injectable({
	      providedIn: 'root'
	    })
	    export class AuthenticationService {
	    
	      constructor(private angularFireAuth:AngularFireAuth) { }
	      loginWithEmail(email: string, password: string) {
	        returnthis.angularFireAuth.auth.signInWithEmailAndPassword(email, password);
	      }
	      loginWithFacebook(){
	        returnthis.angularFireAuth.auth.signInWithPopup(new firebase.auth.FacebookAuthProvider());
	      }
	      registerWithEmail(email: string, password: string) {
	        returnthis.angularFireAuth.auth.createUserWithEmailAndPassword(email, password);
	      }
	      getStatus() {
	        returnthis.angularFireAuth.authState;
	      }
	      logout(){
	        returnthis.angularFireAuth.auth.signOut();
	      }
	    }
	    
	```
	
	login.component.ts
	``` 
	     loginWithFacebook(){
	        this.authenticationService.loginWithFacebook()
	         .then((data) => {
	            alert('Logeado correctamente');
	          }).catch((err) =>console.log(err));
	    
	      }```
	    login.component.html (agregar este código)
	    
	```
	``` 
	     <button *ngIf="operation=='login'"  type="buton" class="btn btn-primary btn-block" (click)="loginWithFacebook()">
	              <i class="fab fa-facebook" aria-hidden="true"></i>
	              Login with Facebook
	            </button>```
	    
	```

* **stiag0** (1) [81051](https://platzi.com/comentario/972330/) 
yo instale el angularFire, intente importarlo desde los módulos, que ya verifique estuviesen en los node_modules, aun así dice: “Property...

* **Samuel Gonzalez Alvarez** (1) [68989](https://platzi.com/comentario/749452/) 
Al intentar abrir la página de login sólo me carga el navbar, todo corre bien pero esa sitio en especial no funciona import { Injec...

* **Víctor Julio Molano Bolívar** (1) [58365](https://platzi.com/comentario/576072/) 
Tengo este error, alguna sugerencia ? ERROR in node_modules/@angular/fire/firebase.app.module.d.ts(17,22): error TS2420: Class ‘FirebaseA...

	* **ing-michaelvillanueva** [58365] (1)

		ya lograste solucionarlo ?? tengo el mismo error

* **Rarvac** (1) [56275](https://platzi.com/comentario/550687/) 
Estimada comunidad, tengo un problema. no me devuelve los datos en consola al momento de hacer login o register. en Firebase est...

	* **Luis Rodriguez** [56275] (1)

		hola! cómo vas, hermano?
		
		tienes el siguiente código en tu archivo de login.component.ts ?
		``` 
		    alert('Loggeado correctamente');
		          }).catch( (error) => {
		            alert('Ocurrio un error');
		            console.log(error);
		          });```
		```

* **Alfonso Adame Rueda** (1) [55167](https://platzi.com/comentario/538310/) 
hola buenas tardes, me sale este error:compiler.js:1021 Uncaught Error: Unexpected value ‘AngularFireAuth’ imported by the module ‘AppMod...

	* **Diego Alexander Forero Higuera (Platzi)** [55167] (1)

		Por lo que veo en las capturas que compartiste AngularFireAuth no esta agregado en el array de declarations en el NgModules, prueba agregarlo y esto debe solucionar el problema.

* **AndreCoDev** (0) [753824](https://platzi.com/comentario/753824/) 
	
	![captura 1.png](https://static.platzi.com/media/user_upload/captura%201-71870d2e-23f5-4b69-97dd-3c47c90ac6d2.jpg)
	
	Alguien me podria ayudar con este error, gracia

* **Alex Eugenio Gavidia Donayre** (0) [550121](https://platzi.com/comentario/550121/) 
Easy

* **Alex Eugenio Gavidia Donayre** (0) [550122](https://platzi.com/comentario/550122/) 
Thanks

## 0400. Reemplazo del servicio de usuarios por un servicio dinámico con conexión a Firebase [12784](https://platzi.com/clases/1340-angular-avanzado/12784-reemplazo-del-servicio-de-usuarios-por-un-servicio/)

### Descripción:


La autenticación de usuarios con la API de Firebase sólo contempla el mínimo de datos requeridos, luego devuelve un identificador único de usuario (uid) y los datos convenidos con el proveedor. Para incorporar datos adicionales y tener control sobre éstos, es necesario apoyarnos en el servicio de base de datos de Firebase, con el fin de almacenar todos los demás datos que queramos.

El manejo de datos con Firebase se hace sobre una estructura de nodos más parecida a las bases de datos de MongoDB que a las de SQL. Para esto, AngularFire pone a disposición el objeto AngularFireDatabase.

Al momento de actualizar un registro en la base de datos se creará automáticamente, si es que aún no existe. Lo recomendable es asociar los datos guardados en la base de datos, con los datos suministrados por el proveedor de autenticación a través del user.uid

### Comentarios:

* **Carlos Federico Rubio Prias** (16) [375053](https://platzi.com/comentario/375053/) 

	En el método de editUsers es mejor user update y no set, pues con el método set se esta sobre escribiendo todo el objeto, si usamos update solo va a actualizar los datos que tendrán un cambio.
	``` 
	    editUser(user){
	    	returnthis.angularFireDatabase.object('/users' + user.uid).update(user);
	    }```
	    
	```

* **jorgejunior1211** (4) [715775](https://platzi.com/comentario/715775/) 

	Faltó indicar que se debe importar en app.module.ts :
	
	AngularFireDatabaseModule
	
	Mi solucion no compilaba por esa bendita linea.

	* **Oscar Martinez** [715775] (1)

		Gracias

* **Pablo Pérez Chueca** (3) [400890](https://platzi.com/comentario/400890/) 

	Según el orden cronológico esta clase debería ir antes de la de “Login con Facebook”  
	.

* **Alex Eugenio Gavidia Donayre** (2) [550148](https://platzi.com/comentario/550148/) 
Interesante

* **Cristian David Franco Garcia** (2) [449886](https://platzi.com/comentario/449886/) 

	Con interpolación:
	``` 
	     getUserByUid(uid: string) {
	        returnthis.angularFireDatabase.object(`/users/${uid}`);
	      }
	    
	```

* **ehnbytes** (1) [1017135](https://platzi.com/comentario/1017135/) 

	Buena clase!!

* **Julian Leonel Lopez** (1) [1003414](https://platzi.com/comentario/1003414/) 

	Hay unos detalles que se deben aclarar, por lo menos en la versión actual.
	
	  1. En el app.modules se debe agregar AngularFireDatabaseModule  
	2.A las funciones del userService se les deben agregar el **public** , por delante.
	
	
	``` 
	    imports: [
	        AppRoutes,
	        BrowserModule,
	    BrowserAnimationsModule,
	        MatSliderModule,
	        NgbModule,
	        MatFormFieldModule,
	        ReactiveFormsModule,
	        NgSelectModule,
	        AngularFireModule.initializeApp(environment.firebase),
	    
	        
	        AngularFireAnalyticsModule,
	        AngularFirestoreModule,
	        AngularFireAuthModule,    
	        AngularFireDatabaseModule
	      
	      ],
	      providers: [AngularFireDatabaseModule],
	    
	```

* **monica0115** (1) [967273](https://platzi.com/comentario/967273/) 

	Hola me está generando el siguiente error con CloudFirestore:
	
	index.esm.js:99 [2020-02-05T12:20:18.776Z] @firebase/database: FIREBASE WARNING: set at /users/cW73UhK8dXhYOytu1MJgv5My3Ag2 failed: permission_denied
	
	y con RealTime database, no me permite modificar las reglas y genera tambien error:
	
	index.esm.js:99 [2020-02-05T12:30:50.107Z] @firebase/database: FIREBASE WARNING: set at /users/F19pEhH3MbTUdczl2EoscKgoBVi1 failed: permission_denied

* **Wilson Marino Pablo Mendez** (1) [722932](https://platzi.com/comentario/722932/) 

	Al principio utilice el tipo de base de datos “cloud Firebase” ya que, ya no esta en beta. pero no me funciono así que utilice el “Realtime Database”.

* **Damian Spizzirri** (1) [658887](https://platzi.com/comentario/658887/) 

	Se puede evitar tener las promesas una dentro de otra? No me termina de convencer como quedo.

	* **Diego Alexander Forero Higuera (Platzi)** [658887] (2)

		Podrías refactorizar creando funciones y que estas se llaman en la resolución de la primera promesa, y en la función tienes la segunda promesa, seguirán anidadas pero con un código probablemente más sencillo de leer.

	* **Damian Spizzirri** [658887] (1)

		Gracias, si, algo asi va a quedar mejor.

* **freddy0fh** (1) [592816](https://platzi.com/comentario/592816/) 

	¿Como debería ser implementado los servicios para poder trabajar en modo offline con AngularFirestore?

	* **Walter Lensinas** [592816] (1)

		Implementando PWA creo que manejas serviceworkers y ahí tenes la gestión de los datos de manera offline.

* **Alfonso Adame Rueda** (1) [540495](https://platzi.com/comentario/540495/) 

	AppComponent.html:2 ERROR TypeError: Cannot read property ‘url’ of undefined  
	at Object.eval [as updateDirectives] (AppComponent.html:2)  
	at Object.debugUpdateDirectives [as updateDirectives] (core.js:11054)  
	at checkAndUpdateView (core.js:10451)  
	at callViewAction (core.js:10692)  
	at execComponentViewsAction (core.js:10634)  
	at checkAndUpdateView (core.js:10457)  
	at callWithDebugContext (core.js:11344)  
	at Object.debugCheckAndUpdateView [as checkAndUpdateView] (core.js:11022)  
	at ViewRef_.push…/node_modules/@angular/core/fesm5/core.js.ViewRef_.detectChanges (core.js:8838)  
	at core.js:4571 me salio este error que marca el codigo que esta abajo, me ayudan por favor

	* **LuisHG** [540495] (1)

		Podrías poner la captura del código para saber mejor por que ocurre el error?

	* **Diego Alexander Forero Higuera (Platzi)** [540495] (1)

		El error lo que menciona es que router no esta definido por lo tanto es null y no tiene el atributo o propiedad url, revisa que este correctamente definido router.

	* **Alfonso Adame Rueda** [540495] (1)

		gracias a los dos por responder , efectivamente ese es el problema ,muchas gracias por responder.

	* **David Alejandro Mosquera Moreno** [540495] (1)

		¿Cómo lograste solucionar este problema Alfonso?

* **Alfonso Adame Rueda** (1) [540492](https://platzi.com/comentario/540492/) 

	hola buenas noches me ayudan por favor con este error:  
	<app-menu *ngIf=“router.url != ‘/login’”></app-menu>  
	<div [ngClass]="{‘generalContent’: router.url !=’/login’}">  
	<router-outlet></router-outlet>

	* **Diego Alexander Forero Higuera (Platzi)** [540492] (1)

		Hola puedes compartir el error completo, aquí estas poniendo tu código pero no el error.

	* **vidalmix** [540492] (1)

		Te falta el cierre de la etiqueta </div>

* **Adrián San Martín** (1) [521672](https://platzi.com/comentario/521672/) 

	Dentro de ‘home’ no me aparece la lista de amigos, ¿alguien me ayuda?. este seria mi código:  
	<home.component.ts>
	``` 
	    import { Component, OnInit } from '@angular/core';
	    import { User } from '../interfaces/user';
	    import { UserService } from '../services/user.service';
	    
	    @Component({
	      selector: 'app-home',
	      templateUrl: './home.component.html',
	      styleUrls: ['./home.component.css']
	    })
	    export class HomeComponent implements OnInit {
	    
	      friends: User[];
	      query: string = '';
	      
	      constructor(private userServices: UserService) { 
	    
	        this.userServices.getUsers().valueChanges().subscribe( 
	          (data: User[]) => {
	            this.friends = data;
	            console.log('components.ts', data);
	          }, (err) => {
	            console.log(err)
	          });
	      }
	        
	      ngOnInit() {
	      }
	    
	    }
	    
	```
	
	<home.component.html> (solo la parte de los amigos)
	``` 
	    <h1>friends:{{friends}}</h1>
	        <p *ngIf="friends">Amigos ({{friends.length}} /{{friends.length}})</p>
	        
	        <ng-container *ngFor="let user of friends | search: query; let i = index" class="disblo marbo5">
	    
	          <div>
	            <span routerLink="/conversation/{{user.uid}}">
	              <img id="user-status" src="assets/img/logo_live_{{user.status}}.png" alt="Estatus" class="icon"/> 
	              <b>{{user.nick}}</b> - {{user.subnick || 'no subnick'}}
	              <small>{{user.email}}</small>
	            </span>
	          </div>
	        </ng-container>
	    
	```
	
	Gracias.

	* **Adrián San Martín** [521672] (1)

		😛 ya encontré mi error, estaba apuntando al nodo equivocado de firebase … por ejemplo en  
		user.services.ts
		``` 
		    ...
		    getUsers() {
		          return this.angularFireDatabase.list('/users');
		      }
		    ...
		    
		```
		
		me conecto con el nodo “/users” … y lo que tenia en firebase era el nodo “/user” (probando cosas) … así que basto con volver a crear un usuario dentro de ese nodo.

	* **Luis Ospina** [521672] (1)

		Yo sigo solucionar mi error, es el mismo.

* **Luis Caiza** (1) [509666](https://platzi.com/comentario/509666/) 

	El vídeo no corresponde al titulo Creando un CRUD implementando un API REST HTTP (con diversos backends), esta mostrando un curso de excel, solucionen por favor.

* **Francisco Ayala** (1) [474475](https://platzi.com/comentario/474475/) 

	¿Cual es la diferencia en usar then - catch y cuando subscribe?

	* **alesanabriav** [474475] (3)

		then - catch es para recibir los datos de una promesa y subscribe es para recibir los datos de un socket @larox90

	* **OCAPITALMX** [474475] (1)

		Como menciona @alesanabriav, then y catch son método que se ejecutan dentro de una promesa en JS.
		
		Por otro lado, el subscribe se utiliza cuando necesitas obtener el valor de una observable.

* **ivan_acg** (1) [436464](https://platzi.com/comentario/436464/) 

	Necesito ayuda con esta parte , he buscado en todas partes y la verdad que no doy con el problema .
	
	La consola me dice :
	``` 
	    ERROR in src/app/login/login.component.ts(22,74): error TS2339: Property'then' does not exist ontype'void'.
	    
	```
	
	y mi codigo es :
	``` 
	    import { Component, OnInit } from '@angular/core';
	    import {AuthenticationService} from '../services/authentication.service';
	    import {UserService} from '../services/user.service';
	    import {Router} from '@angular/router';
	    
	    @Component({
	      selector: 'app-login',
	      templateUrl: './login.component.html',
	      styleUrls: ['./login.component.css']
	    })
	    export class LoginComponent implements OnInit {
	      operation: string = 'login';
	      email: string = null;
	      password: string = null;
	      nick: string = null;
	      constructor(private authenticationService: AuthenticationService, private userService: UserService, private router: Router) { }
	    
	      ngOnInit() {
	      }
	    
	      login() {
	        this.authenticationService.loginWithEmail(this.email, this.password).then( (data) => {
	          alert('Loggeado correctamente');
	          console.log(data);
	          this.router.navigate(['home']);
	    
	        }).catch((error) => {
	          alert('Ocurrioo un error');
	          console.log(error);
	        });
	      }
	    
	      register() {
	        this.authenticationService.registerWithEmail(this.email, this.password).then( (data) => {
	          const user = {
	            uid: data.user.uid,
	            email: this.email,
	            nick: this.nick
	          };
	          this.userService.createUser(user).then((data2) => {
	            alert('Registrado correctamente');
	            console.log(data2);
	          }).catch((error) => {
	            alert('Ocurrioo un error');
	            console.log(error);
	          });
	        }).catch((error) => {
	          alert('Ocurrioo un error');
	          console.log(error);
	        });
	      }
	    }
	    
	    
	    
	```

	* **Yonathan Gutierrez** [436464] (1)

		hazlo de esta forma… saludos… me cuentas como te fue…
		``` 
		    login() {
		        this.authenticationService.loginWithEmail(this.email, this.password).then( data => {...
		    
		```

	* **Yonathan Gutierrez** [436464] (1)

		igual en el caso del register…

	* **ivan_acg** [436464] (1)

		Ya resolví el problema , el problema era que en el folder **login.component.ts** no se estaba retornando ningún valor .
		
		Es decir :
		``` 
		    this.authenticationService.loginWithEmail(this.email, this.password).then( (data) => {
		    
		```
		
		no recibía nada ; y el problema provenía de la carpeta de autenficacion de usuarios que no retornaba nada en la función ‘loginWithEmail’
		``` 
		    constructor(private angularFireAuth: AngularFireAuth ){ }
		        loginWithEmail(email: string , password: string){
		         this.angularFireAuth.auth.signInWithEmailAndPassword(email ,password);
		    
		        }
		        registerWithEmail(email: string, password: string){
		          return this.angularFireAuth.auth.createUserWithEmailAndPassword(email ,password);
		        }
		        getStatus(){
		          return this.angularFireAuth.authState;
		        }
		        logOut(){
		          return this.angularFireAuth.auth.signOut();
		        }
		       }
		    
		```
		
		y lo resolví agregando “return” antes del this.angularFireAuth
		``` 
		    loginWithEmail(email: string , password: string){
		          returnthis.angularFireAuth.auth.signInWithEmailAndPassword(email ,password);
		    
		        }
		        registerWithEmail(email: string, password: string){
		          returnthis.angularFireAuth.auth.createUserWithEmailAndPassword(email ,password);
		        }
		    
		```

	* **ivan_acg** [436464] (2)

		Gracias igual por intentar ayudar !!

	* **Yonathan Gutierrez** [436464] (2)

		ok por nada, aunque tu consola señalaba lo que te mostré que era un paréntesis de mas, en el caso de la clase, al instructor le aparece por una especie de helper del IDE, saludos.

* **Mauricio Quiñones** (1) [75952](https://platzi.com/comentario/878563/) 
Hola buena noche, a hoy podemos trabajar con Cloud en ves de Realtime DB?

* **Arturo Mojica Guerrero** (1) [72546](https://platzi.com/comentario/818117/) 
Disculpen compañeros he visto en varias partes que para algunas cosas de recibir información lo reciben con metodos THEN y otros con SUSC...

	* **tecnox** [72546] (2)

		Son dos paradigmas diferentes del manejo de procesos asincronos
		
		  1. Por un lado las promesas, con el ‘then’ que en escencia es un mecanismo de pull, es decir trae la respuesta asincronicamente y espera su respuesta en el then, o en el catch segun sea el caso
		  2. Por otro lado la programacion reactiva, usando observables donde el paradigma es sutilmente diferente, la idea es la suscripcion a publicaciones/eventos a los que se llaman los observables, de ahi que ves el .subscribe, la idea es que el programador se suscribe a una potencial fuente de datos y recibira asincronicamente la respuesta en el subscribe o en su contraparte error  
		<https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Promise>  
		<https://www.learnrxjs.io/>
		
		

* **Elberth Jair Agreda Rosero** (1) [70711](https://platzi.com/comentario/780821/) 
¿Profe, por qué siempre usas promesas y no observables?

* **freddy0fh** (1) [59555](https://platzi.com/comentario/592816/) 
¿Como debería ser implementado los servicios para poder trabajar en modo offline con AngularFirestore?

	* **Walter Lensinas** [59555] (1)

		Implementando PWA creo que manejas serviceworkers y ahí tenes la gestión de los datos de manera offline.

* **Alfonso Adame Rueda** (1) [55364](https://platzi.com/comentario/540495/) 
AppComponent.html:2 ERROR TypeError: Cannot read property ‘url’ of undefined at Object.eval [as updateDirectives] (AppComponent.html:2) a...

	* **LuisHG** [55364] (1)

		Podrías poner la captura del código para saber mejor por que ocurre el error?

* **Alfonso Adame Rueda** (1) [55363](https://platzi.com/comentario/540492/) 
hola buenas noches me ayudan por favor con este error: <app-menu *ngIf=“router.url != ‘/login’”></app-menu> <div [ngClass]...

	* **Diego Alexander Forero Higuera (Platzi)** [55363] (1)

		Hola puedes compartir el error completo, aquí estas poniendo tu código pero no el error.

* **Adrián San Martín** (1) [53767](https://platzi.com/comentario/521672/) 
Dentro de ‘home’ no me aparece la lista de amigos, ¿alguien me ayuda?. este seria mi código: <home.component.ts> import { Com...

	* **Adrián San Martín** [53767] (1)

		😛 ya encontré mi error, estaba apuntando al nodo equivocado de firebase … por ejemplo en  
		user.services.ts
		``` 
		    ...
		    getUsers() {
		          return this.angularFireDatabase.list('/users');
		      }
		    ...
		    
		```
		
		me conecto con el nodo “/users” … y lo que tenia en firebase era el nodo “/user” (probando cosas) … así que basto con volver a crear un usuario dentro de ese nodo.

* **Francisco Ayala** (1) [50001](https://platzi.com/comentario/474475/) 
¿Cual es la diferencia en usar then - catch y cuando subscribe?

	* **alesanabriav** [50001] (3)

		then - catch es para recibir los datos de una promesa y subscribe es para recibir los datos de un socket @larox90

## 0410. Guards para verificar Firebase auth [12785](https://platzi.com/clases/1340-angular-avanzado/12785-guards-para-checar-firebase-auth/)

### Descripción:


Los guards son scripts que implementan una estrategia de seguridad para accesos no autorizados a las deferentes rutas de nuestra aplicación. Se crean de manera similar a los servicios y componentes, con el siguiente comando de AngularCLI:
``` 
    ng generate guard <directorio>/<nombre-del-guard>
    
```

Resultando en la creación de los archivos: `<nombre-del-guard>.specs.guard.ts` y `<nombre-del-guard>.guard.ts`

El guard se basa en un atributo llamado canActivate que, dependiendo de una condición o expresión buleana, retornará verdadero o falso al constructor del componente en el que se haya inyectado para indicarle cuando deberá mostrar o no el contenido de dicho componente.

### Comentarios:

* **Wilson Fabian Pérez Sucuzhañay** (5) [368151](https://platzi.com/comentario/368151/) 

	Por unos segundos se ve el menu y luego manda al login donde seria la mejor manera de hacerlo sin que acceda al sistema¿?

	* **Jhoysner Corona** [368151] (3)

		Quisiera tambien saber como evitar que se vea por ese segundo la navegacion

	* **Wilson Fabian Pérez Sucuzhañay** [368151] (2)

		lo que me comentan y lo que he visto hasta ahora es poner un if al contenedor de toda la pagina y mientras no este en tru no se mostrara pero mmm no me cuadra deberiamos tner un como main donde consulte todo antes de ingresar no creen?, alguien mas tiene otra idea¡?

	* **Juan Carlos Felizzola Vega** [368151] (2)

		Este problema lo tenemos es porque estamos llamando el `app-menu` en el `app.component.html`.
		
		La manera en que se podría hacer es: Llamar el menú directamente en el `home.component.html` y en los demás donde lo queremos, así evitamos que se vea cuando ingresamos directamente la url

	* **marczg21** [368151] (2)

		Claro deberíamos de tener un master page que nos cargue luego del login, en este master page tendríamos el menú así como también podríamos poner un footer y solo ir actualizando el contenido al navegar a otra opción del menú.  
		Alguien sabe como podríamos hacer esto en angular ???

* **gazz9ar** (2) [682262](https://platzi.com/comentario/682262/) 

	Hola segui todos los pasos del profe y compila correctamente pero al probar la pagina ahora no me muestra nada, ni siquiera el menu.
	
	Si a alguien le ha pasado me ayudaria porfavor.

	* **Juan Antonio Campoy Lira** [682262] (1)

		import { Injectable } from ‘@angular/core’;  
		import { Http,  
		Response,  
		Headers,  
		RequestOptions } from ‘@angular/http’;  
		import { Observable } from ‘rxjs’;
		
		import { mainUrl } from ‘…/…/Shared/Urls/mainUrl’;
		
		import ‘rxjs/add/operator/map’;
		
		@Injectable()  
		export class AuthService {  
		private _authUrl = mainUrl + “oauth/token”;  
		private _getUserUrl = mainUrl + “user/”;  
		private _headers = new Headers({“Content-Type”:“application/x-www-form-urlencoded”});
		``` 
		    //private _myheader = new Headers({'Authorization':`bearer ${localStorage.getItem('token')}`})
		    
		    constructor(private _http: Http) { }
		    
		    postAuth(username,password){
		        let body = `username=${username}&password=${password}&grant_type=password`;
		        let options = new RequestOptions({headers: this._headers});
		        return this._http
		                    .post(this._authUrl,body,options)
		                    .map(res => {
		                        let user = res.json();
		                        if(user && user.access_token){
		                            localStorage.setItem('token', user.access_token);
		                        }
		                        return user;
		                    });
		    }
		    
		    postConfirm(username,password){
		        let body = `username=${username}&password=${password}&grant_type=password`;
		        let options = new RequestOptions({headers: this._headers});
		        return this._http
		                    .post(this._authUrl,body,options)
		                    .map(res => res.json());
		    }
		    
		    //TODO: mandar la request por authHttp para no tener que enviar los headers a mano cada vez
		    getUserDetails(username,token){
		        
		        let _myheader = new Headers({'Authorization':`bearer ${token}`})
		        let options = new RequestOptions({headers: _myheader});
		        return this._http
		                .get(this._getUserUrl + username, options)
		                .map(res => {
		                    let user = res.json();
		                    if(user)
		                    {
		                        localStorage.setItem('fullName', user.fullName);
		                        localStorage.setItem('userName', user.userName);
		                        localStorage.setItem('email', user.email);
		                        localStorage.setItem('level', user.level);
		                        localStorage.setItem('roles', user.roles);    
		                        localStorage.setItem('departamento', user.departamento);    
		                        localStorage.setItem('puesto', user.puesto);    
		                    }
		                    return user;
		                });
		    }
		    
		```
		
		}

* **Angel Javier Puc Yamá** (1) [615899](https://platzi.com/comentario/615899/) 

	En authentication.service.ts mi metodo
	
	logOut(){  
	return this.angularFireAuth.auth.signOut;  
	}
	
	En home.component.ts tengo el metodo
	
	logout(){  
	this.authenticationService.logOut();  
	}
	
	El .then no funciona de la misma forma ya que me dice que la Promise<void> como se debería de hacer en Angular 8? Creo que cuando le doy click a logout() no me cierra la sesión ya que si escribo localhost:4200/home me aparece la pantalla de home y el boton Logout tambien, no se si sea problema de mi metodo logout() en home.component.ts que no puedo ponerle el .then o si sea problema de mi authentication.guard.ts que no esta funcionando.
	
	Intente tambien ponerlo de esta forma
	``` 
	    logout(){
	        this.authenticationService.logOut();
	        return Promise.resolve().then(
	          () => {
	            alert('Sesion Finalizada');
	            this.router.navigate(['login']);
	          }
	        ).catch(
	          (error) => {
	            console.log(error);
	          }
	        );
	      }
	    
	```

	* **Felipe Concha Almeida** [615899] (1)

		En authentication.service.ts tienes esto:
		``` 
		    logOut(){
		        returnthis.angularFireAuth.auth.signOut;
		    }
		    
		```
		
		Pero deberias tener esto:
		``` 
		    logOut(){
		        returnthis.angularFireAuth.auth.signOut();
		    }
		    
		```
		
		Por eso es tu problema, lo demás esta todo bien!

	* **Fernando Vallejo** [615899] (1)

		Quizo decir home.component.ts

* **Angel Javier Puc Yamá** (1) [615684](https://platzi.com/comentario/615684/) 

	Al escribir la instruccion ng g g services/authentication si me crea los dos archivos pero vienen sin el implements y el metodo canActivate, que parámetro necesito pesarle al CLI o de que forma me crea los métodos? Probé con el espacio pero no me sale ninguna opción.

	* **JerezA** [615684] (1)

		se debe a que escribres ng g g, la sigla sola de G es para el generate, no para el guard, por lo que el considera que debe crear un servicio normal

* **Codehero** (1) [564810](https://platzi.com/comentario/564810/) 

	Tengo este error al utilizar map, alguien sabe porque?
	``` 
	    ERROR in src/app/services/authentication.guard.ts(25,7): error TS2552: Cannot find name 'map'. Did you mean 'Map'?
	    
	```

	* **Codehero** [564810] (1)

		Este es mi codigo del metodo
		``` 
		    return this.authenticationService.getStatus().pipe(
		          map(status => {
		            if(status) {
		              returntrue;
		            }else{
		              returnfalse;
		            }
		          });
		        )
		    
		```

	* **Diego Alexander Forero Higuera (Platzi)** [564810] (3)

		Estas importando esto
		``` 
		    import {map} from 'rxjs/operators';
		    
		```

* **Alex Eugenio Gavidia Donayre** (1) [550918](https://platzi.com/comentario/550918/) 
Great

* **Diego Mauricio Mejía Ospina** (1) [537442](https://platzi.com/comentario/537442/) 

	se Impota el Router desde:
	``` 
	    import {Router} from'@angular/router';```
	    
	```

* **Jecsham Castillo** (1) [449550](https://platzi.com/comentario/449550/) 

	`ng g g services/authentication`

	* **iluna** [449550] (1)

		Al crear correr (ng g g services/authnetication)  
		se me agregar algo como esto (UrlTree) , que funcionalidad tiene ?
		``` 
		    state: RouterStateSnapshot): Observable<boolean | UrlTree> | Promise<boolean | UrlTree> | boolean | UrlTree
		    
		```

* **ma74ny** (1) [66135](https://platzi.com/comentario/703409/) 
¿cómo evito que ingresen al login una vez que ya iniciaron sesión?

	* **octaviodiaz_cg** [66135] (1)

		Yo generé un AuthGuard con un canActivate de esta forma:
		``` 
		    import { Injectable } from'@angular/core';
		    import { CanActivate, ActivatedRouteSnapshot } from'@angular/router';
		    import { AuthService } from'../services/auth.service';
		    
		    @Injectable({
		      providedIn: 'root'
		    })
		    exportclassAuthGuardServiceimplementsCanActivate{
		    
		      constructor(private _authService: AuthService) { }
		    
		      canActivate(route: ActivatedRouteSnapshot) {    
		        	let noAuth = route.data.noAuth;
		        	returnthis._authService.isAuth(noAuth);
		    		}
		    	}
		    
		    }
		    
		```
		
		y en el auth.service tengola función isAuth
		``` 
		    isAuth(noAuth = false) {
		        returnthis._store.select('auth').pipe(
		          map(auth => {
		            let today = newDate();
		            let authData = auth.authData ? auth.authData : {};
		            const userData = authData.user ? authData.user.Role.name : {};
		            let expDate = authData.exp ? newDate(authData.exp) : newDate();
		            let isAuth = authData.token && today < expDate;
		    
		            if (noAuth) { // si el usuario no esta autenticado le permite ver la vista del login
		              isAuth = !isAuth;
		            }
		            if (!isAuth && !noAuth) { // si el token expiró cierra la sesion del usuario
		              this.logout();
		            } elseif (!isAuth && noAuth) { // si el usuario esta autenticado y quiere acceder a login lo manda al home
		              this._router.navigate(['/' + userData.toLowerCase()]);
		            }
		            return isAuth;
		          })
		        );
		      }
		    
		```

## 0420. Creando un CRUD implementando un API REST HTTP (con diversos backends) [13000](https://platzi.com/clases/1340-angular-avanzado/13000-creando-un-crud-implementando-un-api-rest-http-con/)

### Descripción:


Las apps que construimos en Ionic, son meramente de frontend, esto quiere decir, que los archivos de la aplicación en sí, sólo son ejecutados en el browser cliente.  
Dado esto, nuestras apps deben usar ciertos mecanismos para conectarse con el backend, como comunicación a través de sockets puros o llamados HTTP.  
Nuestra app se comunica con Firebase usando la librería AngularFire, la cual establece comunicación con nuestra base de datos usando sockets, sin embargo, fácilmente puedes reemplazar esta librería (y firebase) por cualquier backend que exponga un API que el app pueda consumir.

Por ejemplo, puedes usar un backend de PHP, usando Laravel. Puedes usar este repositorio para montar tu propio servidor de Laravel: <https://github.com/EduardoIbarra/laravelcrud> (debes de hacer configuraciones de base de datos e instalación de dependencias usando composer, puedes encontrar cómo crear este backend y como ejecutarlo aquí: [https://www.youtube.com/watch?v=2RNZ1TcK_kI&list=PLYPjmy5IVxT_EXZQK-Getu3xKAJ4bPOa6](https://www.youtube.com/watch?v=2RNZ1TcK_kI&list=PLYPjmy5IVxT_EXZQK-Getu3xKAJ4bPOa6)

Las funciones de un CRUD son las siguientes:

* **Create,** usando un verbo HTTP llamado POST
* **Read,** usando un verbo HTTP llamado GET
* **Update,** usando un verbo HTTP llamado PUT
* **Delete,** usando un verbo HTTP llamado DELETE



Te recomiendo crear un nuevo app de Ionic para consumir este CRUD de Laravel. Además, agregar un servicio como los que creamos para acceder a los datos de Firebase y de esta manera acceder al CRUD.

Para lograr acceder a métodos HTTP, necesitamos el Módulo de HttpClient de Angular. Lo que hay que hacer para tenerlo disponible en nuestra app es dirigirnos a nuestro app.module.ts, y en la sección de imports, colocar: HttpClientModule.

Luego, en el servicio que agregaste para el acceso al CRUD, en su constructor, agregar una propiedad del tipo HttpClient, de esta manera: private httpClient: HttpClient.

Aquí te muestro los métodos de acceso para este CRUD en particular:
``` 
     get() {
        return this.httpClient.get(this.API_ENDPOINT + '/movies');
      }
    
      save(movie: Movie) {
        const headers = new HttpHeaders({'Content-Type': 'application/json'});
        return this.httpClient.post(this.API_ENDPOINT + '/movies', movie, {headers: headers});
      }
    
      put(movie) {
        const headers = new HttpHeaders({'Content-Type': 'application/json'});
        return this.httpClient.put(this.API_ENDPOINT + '/movies/' + movie.id, movie, {headers: headers});
      }
    
      delete(id) {
        return this.httpClient.delete(this.API_ENDPOINT + '/movies/' + id);
      }
    
```

Y a partir de este punto, lo demás es casi exactamente igual que acceder a método de Firebase, simplemente, inyectas el servicio en tu Page o Componente y llamas a sus métodos, los cuáles regresan Observables a los que puedes suscribirte (.subscribe())

Si deseas el resultado final de este crud para Angular, puedes obtenerlo aquí: <https://github.com/EduardoIbarra/angularcrud/tree/2_RoutingInterfaces>

## CRUD con Django

Para hacer el CRUD con Django, realmente el cambio es poco, puedes tomar el CRUD de Django que cree desde este repositorio de Github: <https://github.com/EduardoIbarra/djangocrud>

Este CRUD se desarrolló basándome en esta guía y adaptando el código al mismo caso del CRUD de Laravel: <https://codeburst.io/create-a-django-api-in-under-20-minutes-2a082a60f6f3>

Aquí está una versión del CRUD de Angular adaptado a nuestro nuevo CRUD de Django: <https://github.com/EduardoIbarra/angularcrud/tree/django>, si te ocurre algún error relacionado con Access-Control-Allow-Origin, checa este url: <https://gist.github.com/miraculixx/6536381>

### Comentarios:

* **Juan Antonio Campoy Lira** (3) [979512](https://platzi.com/comentario/979512/) 

	Crud con C# API rest?

	* **Emilio Ian Camacho Mejia** [979512] (1)

		Con NetCore, creas una webapi

* **carlosextra1** (3) [391395](https://platzi.com/comentario/391395/) 

	Agregue un metodo mas. para cuando van a editar una peli.  
	**getById**
	``` 
	    import { Injectable } from'@angular/core';
	    import { HttpClient, HttpHeaders } from"@angular/common/http";
	    import { Movie } from"../interfaces/movie";
	    @Injectable({
	      providedIn: 'root'
	    })
	    exportclassMoviesService{
	    	API_ENDPOINT = 'http://localhost:8055/api';
	    	constructor(private http:HttpClient) {
	    	}
	    	get(){
	    		returnthis.http.get(this.API_ENDPOINT + "/movies")
	    	}
	    	getById(id){
	    		if(id){
	    			returnthis.http.get(this.API_ENDPOINT + "/movies/id/"+id);
	    		}
	    	}
	    	save(movie: Movie){
	    		const headers = new HttpHeaders({'Content-Type': 'application/json'});
	    		returnthis.http.post(this.API_ENDPOINT + '/movies',movie, {headers: headers});
	    	}
	    	put(movie){
	    		const headers = new HttpHeaders({'Content-Type':'application/json'});
	    		returnthis.http.put(this.API_ENDPOINT + '/movies/' + movie.id, movie, {headers: headers});
	    	}
	    	delete(id){
	    		returnthis.http.delete(this.API_ENDPOINT + '/movies/' + id);
	    	}
	    }```
	    
	    
	    lo mando llamar desde aqui.
	    
	    
	    
	```
	
	import { Component, OnInit } from ‘@angular/core’;  
	import { MoviesService } from “…/services/movies.service”;  
	import { Movie } from “…/interfaces/movie”;  
	import { Router, ActivatedRoute } from “@angular/router”;
	
	@Component({  
	selector: ‘app-form’,  
	templateUrl: ‘./form.component.html’,  
	styleUrls: [’./form.component.css’]  
	})  
	export class FormComponent implements OnInit {  
	movie: Movie = {  
	name :null,  
	genre :null,  
	year :null,  
	duration :null,  
	description :null  
	}  
	id:number;  
	editing:boolean;  
	constructor(private moviesService:MoviesService,  
	private router: Router,  
	private activatedRoute:ActivatedRoute) {  
	[this.id](http://this.id) = this.activatedRoute.snapshot.params[‘id’];  
	if([this.id](http://this.id)){  
	this.editing= true;  
	this.moviesService.getById([this.id](http://this.id))  
	.subscribe((result:Movie)=>{  
	this.movie = result;  
	},(e)=>{  
	console.log(e);  
	});  
	}else{  
	this.editing= false;  
	}  
	}
	``` 
	    ngOnInit() {
	    }
	    save(){
	    	if(this.id && this.editing){
	    		this.moviesService.put(this.movie)
	    			.subscribe(
	    				(res)=>{
	    					this.router.navigate(['home']);
	    				},(e)=>{
	    
	    				});
	    	}else{
	    		this.moviesService.save(this.movie)
	    			.subscribe(
	    				(dat)=>{
	    					this.router.navigate(['home']);
	    				},(e)=>{
	    					console.log(e);
	    				})
	    	}
	    }
	    
	```
	
	}```

* **Davidvhub** (2) [569015](https://platzi.com/comentario/569015/) 

	Otra opción que se puede tener para este tipo de CRUD es centralizar los servicios, cosa que puedas inyectar las dependencias desde diferentes componentes y realizar tu llamada desde éstos…
	``` 
	    import { Injectable } from'@angular/core';
	    import { Http , Headers, RequestOptions } from'@angular/http';
	    
	    @Injectable({
	      providedIn: 'root'
	    })
	    export classApirestService {
	    
	    	public apiUrl: string = Url_api
	    	constructor(private http: Http)
	        {
	            this.http = http;
	        }
	    
	        Post(route:string, body)
	        {    
	            let repos = this.http.post(this.apiUrl.concat(route), body);
	            return repos;
	        }
	    
	        Get(route:string)
	        {
	           let repos = this.http.get(this.apiUrl.concat(route), options);
	            return repos;
	        }
	    
	        queryDelete(route:string)
	        {
	            let repos = this.http.delete(this.apiUrl.concat(route), options);
	            return repos;
	        }
	    }
	    
	    
	```
	
	Ejemplo de solicitud:
	``` 
	    let url '/getData'
	    this.service.Get(url).subscribe(
	                response=>
	                {      
	                    letresult = response.json();  # obtenemos la respuesta en formato json
	                },
	                err => 
	                {
	                    console.log(err);
	                }
	            );
	    
	```

* **carlosextra1** (2) [391396](https://platzi.com/comentario/391396/) 

	```
	    import { Component, OnInit } from '@angular/core';
	    import { MoviesService } from "../services/movies.service";
	    import { Movie } from "../interfaces/movie";
	    import { Router, ActivatedRoute } from "@angular/router";
	    
	    @Component({
	      selector: 'app-form',
	      templateUrl: './form.component.html',
	      styleUrls: ['./form.component.css']
	    })
	    export classFormComponentimplementsOnInit {
	    	movie: Movie = {
	    		name        :null,
	    		genre       :null,
	    		year        :null,
	    		duration    :null,
	    		description :null
	    	}
	    	id:number;
	    	editing:boolean;
	    	constructor(private moviesService:MoviesService,
	    				private router: Router,
	    				private activatedRoute:ActivatedRoute) {
	    		this.id = this.activatedRoute.snapshot.params['id'];
	    		if(this.id){
	    			this.editing= true;
	    			this.moviesService.getById(this.id)
	    				.subscribe((result:Movie)=>{
	    					this.movie = result;
	    				},(e)=>{
	    					console.log(e);
	    				});
	    		}else{
	    			this.editing= false;
	    		}
	    	}
	    
	    	ngOnInit() {
	    	}
	    	save(){
	    		if(this.id && this.editing){
	    			this.moviesService.put(this.movie)
	    				.subscribe(
	    					(res)=>{
	    						this.router.navigate(['home']);
	    					},(e)=>{
	    
	    					});
	    		}else{
	    			this.moviesService.save(this.movie)
	    				.subscribe(
	    					(dat)=>{
	    						this.router.navigate(['home']);
	    					},(e)=>{
	    						console.log(e);
	    					})
	    		}
	    	}
	    
	    }
	    
	```

* **Erik Ricardo Sánchez Pérez** (1) [1028123](https://platzi.com/comentario/1028123/) 

	Igual recuerden que saber docker nos da un gran super poder para integrar todo nuestro ambiente de desarrollo 😉

* **Rubén Jiménez Torres** (1) [673653](https://platzi.com/comentario/673653/) 

	Como implementar todo esto con un backend escrito con Java.

* **Ale17273has** (1) [603440](https://platzi.com/comentario/603440/) 

	Un pequeño ejemplo, en este caso la realize con esta api  
	<https://rickandmortyapi.com/documentation/>
	
	Servicio
	``` 
	    <import {Injectable} from'@angular/core';
	    import {HttpClient} from'@angular/common/http';
	    
	    @Injectable({
	      providedIn: 'root'
	    })
	    exportclassBackendService{
	    
	      API_ENDPOINT = 'https://rickandmortyapi.com/api/';
	    
	      constructor(private httpClient: HttpClient) {
	      }
	    
	      get() {
	        returnthis.httpClient.get(this.API_ENDPOINT + '/character/');
	      }
	    }
	    >
	    
	```
	
	Implementacion de home
	``` 
	    <import {Component, OnInit} from '@angular/core';
	    import {AuthenticationService} from '../services/authentication.service';
	    import {UserService} from '../services/user.service';
	    import {Router} from '@angular/router';
	    import {BackendService} from '../services/backend.service';
	    import {Ricky} from '../interfaces/ricky';
	    
	    @Component({
	      selector: 'app-login',
	      templateUrl: './login.component.html',
	      styleUrls: ['./login.component.css']
	    })
	    
	    export class LoginComponent implements OnInit {
	      operation: string = 'login';
	      email: string = null;
	      password: string = null;
	      nick: string = null;
	    
	      constructor(private authenticationService: AuthenticationService,
	                  private userService: UserService, private router: Router, private backend: BackendService) {
	      }
	    
	      ngOnInit() {
	      }
	    
	      login() {
	        this.backend.get().subscribe((data: Ricky) => {
	          console.log(data);
	        }, (error) => {
	          console.log(error);
	          alert('Ocurrió un error');
	        });
	      }
	    
	      register() {
	        this.authenticationService.registerWithEmail(this.email, this.password)
	          .then((data) => {
	            const user = {
	              uid: data.user.uid,
	              email: this.email,
	              nick: this.nick
	            };
	            this.userService.createUser(user).then((data2) => {
	    
	            }).catch((error) => {
	              console.log('Se presento problemas para create user');
	            });
	          }).catch((error) => {
	          console.log(error);
	        });
	      }
	    }
	    >
	    
	```
	
	Interfaz
	``` 
	    <exportinterface Ricky {
	      'info': {
	        'count': number,
	        'pages': number,
	        'next': string,
	        'prev': string
	      };
	      'results': [
	        {
	          'id': number,
	          'name': string,
	          'status': string,
	          'species': string,
	          'type': string,
	          'gender': string,
	          'origin': {
	            'name': string,
	            'url': string
	          },
	          'location': {
	            'name': string,
	            'url': string
	          },
	          'image': string,
	          'episode': [],
	          'url': string,
	          'created': string
	        }
	        ];
	    }
	    >
	    
	```

* **alexgv04** (1) [570816](https://platzi.com/comentario/570816/) 

	buenas tardes, tengo un error al realizar el servicio no me esta registrado la respuesta que me envía el backend, si en el servicio adiciono un .map puedo tener la respuesta pero al tratar de retornarla al componente siempre me llega null
	
	ejem  
	-servicio  
	saveImage(formData:FormData) : Observable<Object>{  
	return this.httpClient.post<Object>(GLOBALURLS().urlFile , formData)  
	}
	
	-componente  
	saveImageEmpresa(imageInput: any){  
	var formData = new FormData();  
	this.file = imageInput.files[0];  
	formData.append(‘form’, this.file);  
	this.empresaService.saveImage(formData).subscribe((result) => {  
	console.log(result);  
	alert(‘Película actualizada’+result);  
	}, (error) => {  
	console.log(error);  
	alert(‘Ocurrió un error’);  
	});  
	}

* **alexgv04** (1) [57926](https://platzi.com/comentario/570816/) 
buenas tardes, tengo un error al realizar el servicio no me esta registrado la respuesta que me envía el backend, si en el servicio adici...

## 0430. Reto Implementar API HTTP [13006](https://platzi.com/clases/1340-angular-avanzado/13006-reto-implementar-api-http/)

### Descripción:


Hasta ahora, los datos que hemos consumido han sido a través de la librería angularfire2, la cual establece comunicaciones con el backend usando sockets.

Sin embargo, es muy común establecer comunicaciones a través de llamados HTTP hacia APIs. Así que, busca una API REST que puedas consumir usando el HttpClientModule en Angular, como las APIs de Reddit, weather, etc.

### Comentarios:

* **rprado** (5) [575830](https://platzi.com/comentario/575830/) 

	Yo implementé la funcionalidad de obtener el clima de nuestras coordenadas, para ello cree 2 servicios:
	
	1.- Servicio para consultar las coordenadas del navegador:
	``` 
	      getGeoLocation(): Observable<any>{
	        return new Observable( (observer) => {
	          navigator.geolocation.getCurrentPosition(resp => {
	            //console.log({lat: resp.coords.latitude, lng: resp.coords.longitude});
	            observer.next(resp)
	          },
	          err => {
	            observer.error( err )
	          });
	        });
	      }
	    
	```
	
	2.- Servicio para obtener los datos del clima en base a las coordenadas enviadas por parametros (obtenidas en el servicio anterior) mediante la API de [openweathermap.org](http://openweathermap.org):
	``` 
	      endpoint = 'https://api.openweathermap.org/data/2.5/';
	      httpOptions = {
	        headers: new HttpHeaders({
	          'Content-Type':  'application/json'
	        })
	      };
	    
	      getWeatherByCoord(lat:string, lon:string){
	        returnthis.httpClient.get(this.endpoint + 'weather?lat='+lat+'&lon='+lon+'&units=metric&appid=AQUÍ_VA_SU_API_KEY')
	        .pipe( map( (data:any) =>{
	          let city = data.name;
	          let country = data.sys.country;
	          let weather = data.weather[0].main;
	          let description = data.weather[0].description;
	          let icon = data.weather[0].icon;
	          let temp = parseInt(data.main.temp);
	          let humidity = data.main.humidity;
	          let x:Weather = { city, country, weather, description, icon, temp, humidity };
	          return x;
	        }
	        ), //Map
	        ); //Pipe
	      }
	    
	```
	
	Luego solamente use algunas funciones de rxjs para suscribirme en cola a los Observables creados anteriormente y así poder obtener la data del clima 😉
	``` 
	    //Pipe se encarga de encolar las suscripciones por si se necesitan ejecutar en estricto orden
	          //En este caso es así, pues primero necesitamos las coordenadas del servicio de Geolocation
	          //Y despues consultar el servicio de Weather para traer el clima por medio de la API
	          this.geoLocationService.getGeoLocation().pipe(
	            flatMap( 
	              (resp) =>this.weatherService.getWeatherByCoord(resp.coords.latitude, resp.coords.longitude),
	            )
	          ).subscribe( //Solo se necesita suscribirse al servicio final para completar el proceso
	            (data: Weather) => {
	              this.weatherData = data;
	              console.log(data);
	            },
	            (err) => {
	              this.error = "No es posible consultar el servicio del clima en estos momentos.";
	              console.log(err);
	            }
	          );
	    
	```
	
	El resultado:  
	![](https://i.imgur.com/4G2u2v8.png)
	
	Tarde un poco mas de lo esperado pues soy un poco nuevo con los Observables de rxjs pero creo que fue un buen resultado a pesar de lo mencionado.

* **carlosextra1** (4) [391631](https://platzi.com/comentario/391631/) 

	aqui el el link del repo en angular <https://github.com/linuxcarl/angular6-laravel5>  
	y aqui en de laravel  
	<https://github.com/linuxcarl/crud-laravel-angular-6>

* **carlosextra1** (3) [391632](https://platzi.com/comentario/391632/) 

	Index![](http://www.extrasistemas.com/Platzi/Angular/http_php_index.PNG)  
	nuevo  
	![](http://www.extrasistemas.com/Platzi/Angular/http_php_nuevo.PNG)  
	editar![](http://www.extrasistemas.com/Platzi/Angular/http_php_edit.PNG)  
	Eliminar  
	![](http://www.extrasistemas.com/Platzi/Angular/http_php_del.PNG)

* **Wilson Fabian Pérez Sucuzhañay** (3) [368153](https://platzi.com/comentario/368153/) 

	Estoy creando un graphql y sockets en php POR DIOS NO LARAVEL jaja por eso me estoy tardando pero estoy en el reto al terminarlo subo demo.

	* **carlosextra1** [368153] (1)

		wey sube los links de los repositorios para ver como lo hiciste con esas tecnologias.

* **Ale17273has** (2) [603445](https://platzi.com/comentario/603445/) 

	Api llamada API_ENDPOINT = ‘<https://rickandmortyapi.com/api/>’;
	
	e implementacion de llamada
	``` 
	    <import {Injectable} from'@angular/core';
	    import {HttpClient} from'@angular/common/http';
	    
	    @Injectable({
	      providedIn: 'root'
	    })
	    exportclassBackendService{
	    
	      API_ENDPOINT = 'https://rickandmortyapi.com/api/';
	    
	      constructor(private httpClient: HttpClient) {
	      }
	    
	      get() {
	        returnthis.httpClient.get(this.API_ENDPOINT + '/character/');
	      }
	    }
	    >
	    
	```

* **Sigaweb** (2) [460916](https://platzi.com/comentario/460916/) 

	Aquí está el código de una clase para el backend que realicé utilizando Spring y java. Muy sencillo y sin autenticación.
	``` 
	    @CrossOrigin(origins = {"http://localhost:4200"})
	    @RestController
	    @RequestMapping("api")
	    public classClienteRestController{
	    
	        @Autowired
	        private ClienteService clienteService;
	    
	        @GetMapping("clientes")
	        public List<Cliente> index() {
	            return clienteService.findAll();
	        }
	    
	    
	        @GetMapping("clientes/{id}")
	        public ResponseEntity<?> getCliente(@PathVariable("id") Long id) {
	            Cliente cliente = null;
	            Map<String, Object> response = new HashMap<>();
	    
	            try {
	                cliente = clienteService.findById(id);
	            } catch (DataAccessException e) {
	                response.put("mensaje", "Error al realizar la consulta. Por favor intenta de nuevo más tarde.");
	                response.put("error", e.getMessage().concat(": ").concat(e.getMostSpecificCause().getMessage()));
	                returnnew ResponseEntity<Map<String, Object>>(response, HttpStatus.INTERNAL_SERVER_ERROR);
	            }
	    
	            if (cliente == null) {
	                response.put("mensaje", "El cliente con el id: ".concat(id.toString()).concat(" no existe, verifica la información"));
	                returnnew ResponseEntity<Map<String, Object>>(response, HttpStatus.NOT_FOUND);
	            }
	            returnnew ResponseEntity<Cliente>(cliente, HttpStatus.OK);
	        }
	    
	        @PostMapping("clientes")
	        public ResponseEntity<?> createCliente(@RequestBody Cliente cliente) {
	            Cliente clienteNew = null;
	            Map<String, Object> response = new HashMap<>();
	            try {
	                clienteNew = clienteService.save(cliente);
	            } catch (DataAccessException e) {
	                response.put("mensaje", "No se pudo crear el cliente. Por favor intenta de nuevo más tarde.");
	                response.put("error", e.getMessage().concat(": ").concat(e.getMostSpecificCause().getMessage()));
	                returnnew ResponseEntity<Map<String, Object>>(response, HttpStatus.INTERNAL_SERVER_ERROR);
	            }
	    
	            response.put("mensaje", "Cliente creado con éxito");
	            response.put("cliente", clienteNew);
	            returnnew ResponseEntity<Map<String, Object>>(response, HttpStatus.CREATED);
	        }
	    
	        @PutMapping("clientes/{id}")
	        public ResponseEntity<?> updateCliente(@RequestBody Cliente cliente, @PathVariable("id") Long id) {
	    
	            Cliente clienteActual = null;
	            Cliente clienteUpdated = null;
	            Map<String, Object> response = new HashMap<>();
	    
	            try {
	                clienteActual = clienteService.findById(id);
	            } catch (DataAccessException e) {
	                response.put("mensaje", "Ha ocurrido un error al buscar el cliente");
	                response.put("error", e.getMessage().concat(": ").concat(e.getMostSpecificCause().getMessage()));
	                returnnew ResponseEntity<>(response, HttpStatus.INTERNAL_SERVER_ERROR);
	            }
	    
	            if (clienteActual != null) {
	                clienteActual.setNombre(cliente.getNombre());
	                clienteActual.setApellido(cliente.getApellido());
	                clienteActual.setEmail(cliente.getEmail());
	    
	                try {
	                    clienteUpdated = clienteService.save(clienteActual);
	                    response.put("mensaje", "El cliente ha sido actualizado con éxito");
	                    response.put("cliente", clienteUpdated);
	                    returnnew ResponseEntity<Map<String, Object>>(response, HttpStatus.CREATED);
	                } catch (DataAccessException e) {
	                    response.put("mensaje", "Ha ocurrido un error al actualizar el cliente");
	                    response.put("error", e.getMessage().concat(": ").concat(e.getMostSpecificCause().getMessage()));
	                    returnnew ResponseEntity<>(response, HttpStatus.INTERNAL_SERVER_ERROR);
	                }
	            } else {
	                response.put("mensaje", "No se ha encontrado un cliente con ese id");
	                returnnew ResponseEntity<>(response, HttpStatus.NOT_FOUND);
	            }
	    
	        }
	    
	        @DeleteMapping("clientes/{id}")
	        public ResponseEntity<?> deleteCliente(@PathVariable("id") Long id) {
	            Map<String, Object> response = new HashMap<>();
	            try {
	                clienteService.delete(id);
	                response.put("mensaje", "El cliente ha sido eliminado con éxito");
	                returnnew ResponseEntity<>(response, HttpStatus.OK);
	            } catch (DataAccessException e) {
	                response.put("mensaje", "Ha ocurrido un error al intentar eliminar el cliente");
	                response.put("error", e.getMessage().concat(": ").concat(e.getMostSpecificCause().getMessage()));
	                returnnew ResponseEntity<>(response, HttpStatus.INTERNAL_SERVER_ERROR);
	            }
	    
	        }
	    
	    
	    }```
	    
	```

* **caprilespe** (1) [805980](https://platzi.com/comentario/805980/) 

	Realice el ejemplo de uso de HttpClient con el servicio api rest de GitHub
	
	GithubService
	``` 
	    import { Injectable } from'@angular/core';
	    import { IGithubService } from'../interfaces/IGithubService';
	    import { HttpClient, HttpHeaders } from'@angular/common/http';
	    import { environment } from'src/environments/environment.prod';
	    
	    @Injectable({
	      providedIn: 'root'
	    })
	    exportclassGithubServiceimplementsIGithubService{
	    
	      constructor(private httpClient:HttpClient) { }
	    
	      GetUser(username:string):any {
	        const url = environment.gitHub.endpoint +"users/"+username;
	        const httpHeader:HttpHeaders = new HttpHeaders();
	        httpHeader.append("x-github-otp","OTP");
	        httpHeader.append("Content-Type","application/json");
	        returnthis.httpClient.get(url,{headers: httpHeader})
	      }
	    }
	    
	    
	```
	
	Llamado del servicio
	``` 
	    this.githubService.GetUser(this.model.username).subscribe((data)=>{
	          console.log(data);
	        },(error)=>{
	          console.log(error);
	        });
	    
	    
	```

# Opciones y subida de imágenes [2352]

## 0440. Perfil de usuario [12786](https://platzi.com/clases/1340-angular-avanzado/12786-perfil-de-usuario/)

### Descripción:


Para mostrar la información del usuario en la pantalla de Perfil, necesitamos obtener su **uid** desde el servicio _autenthicationService_ que creamos antes y usar este uid para extraer los detalles desde la base de datos a través del método _getUserById_ en el servicio de usuario.

Una vez obtenidos los datos adicionales del usuario, los enlazamos a los elementos html del formulario usando NgModel.

### Comentarios:

* **Juan Carlos Felizzola Vega** (5) [385801](https://platzi.com/comentario/385801/) 

	 **Rero cumplido.**
	
	Solo es aplicar lo mismo que hicimos en profile y reemplazar las variables estaticas que tenemos en home

	* **Teofilo Rosales Gama** [385801] (2)

		no entiendo serias mas especifico para todos

	* **Juan Carlos Felizzola Vega** [385801] (1)

		¿Recuerdas que en profile obtuvimos el status para luego traer el usuario? _Si no recuerdas repasa esa clase._  
		Ahora sólo es hacer lo mismo en home.component.ts y traer esa variable en home.component.html

	* **Teofilo Rosales Gama** [385801] (2)

		sigo sin entender necesito el codigo lo e intentado y me sige saliendo montones de errores

	* **Juan Carlos Felizzola Vega** [385801] (1)

		Puedes publicar acá los errores o escribirme por mensaje para ayudarte.

* **emanuel-gordillo** (3) [624550](https://platzi.com/comentario/624550/) 

	Que tanta practico seria si lo guardamos en local storge ?

* **Teofilo Rosales Gama** (2) [394664](https://platzi.com/comentario/394664/) 

	Lo logre!!!
	
	![fda.png](https://static.platzi.com/media/user_upload/fda-f47d88d6-0dce-418f-bb19-e42faec327b7.jpg)
	
	home.component.ts
	``` 
	    import { Component, OnInit } from '@angular/core';
	    import { User } from '../interfaces/user';
	    import { UserService } from './../services/user.service';
	    import { AuthenticationService } from './../services/authentication.service';
	    import { Router } from '@angular/router';
	    
	    @Component({
	      selector: 'app-home',
	      templateUrl: './home.component.html',
	      styleUrls: ['./home.component.css']
	    })
	    export classHomeComponentimplementsOnInit {
	    friends: User[];
	    user: User;
	    query: string = '';
	      constructor( private userService: UserService,
	        private authenticationService: AuthenticationService,
	        private router: Router) {
	        this.userService.getUsers().valueChanges().subscribe(
	          (data: User[] ) => {
	            this.friends = data;
	          }, (error) => {
	            console.log(error);
	          }
	          );
	          this.authenticationService.getStatus().subscribe(
	            (status) => {
	              this.userService.getUserById(status.uid).valueChanges().subscribe(
	                (data: User) => {
	                  this.user = data;
	                  console.log(this.user);
	                }, (error) => {
	                  console.log(error);
	                });
	            }, (error) => {
	              console.log(error);
	            });
	      }
	      ngOnInit() {
	      }
	      logout () {
	        this.authenticationService.logOut().then(() => {
	          alert('sesion Cerrada');
	          this.router.navigate(['login']);
	        }).catch ((error) => {
	          console.log (error);
	        });
	      }
	    }
	    
	```
	
	home.component.html
	``` 
	    <divid="homeContainer">
	      <divclass="whiteBorderGlassBox">
	        <divclass="homeHeadContainer">
	          <divclass="row">
	            <divclass="col-md-auto">
	              <divclass="avatarFrameonline" *ngIf="user">
	                  <img [src]="user.avatar || 'assets/img/generic_avatar.png'"id="homeAvatarPicture">
	              </div>
	            </div>
	            <divclass="col" *ngIf="user">
	    
	              <b>{{ user.nick }}</b>
	              <div>
	                <span>{{ user.status }}</span><br/>
	                <b>{{ user.subnick }}</b><br/>
	                <b>{{ user.email }}</b>
	                <br />
	                <span>< EscribeunmensajePersonal ></span><br/>
	                <a (click)="logout()">Logout</a>
	              </div>
	            </div>
	          </div>
	        </div>
	      </div>
	      <divclass="whiteContainerPadded marto15">
	        <divclass="row">
	          <divclass="col">
	            <inputtype="text"class="form-control"placeholder="Buscar Amigo" [(ngModel)]="query"/>
	          </div>
	          <divclass="col-md-auto">
	            <imgsrc="assets/img/logo_live_add.png"class="icon"alt="">
	          </div>
	        </div>
	        <hr/>
	        <b *ngIf="friends">Amigos ({{ friends.length }}) / ({{ friends.length }})</b>
	        <div *ngFor="let user of friends | search: query; let i = index"class="disblo marbo5">
	    
	            <spanrouterLink="/conversation/{{ user.uid }}">
	              <imgsrc="assets/img/logo_live_online.png"class="icon"alt="">
	               <b>{{ user.nick }}</b> - {{ user.subnick || 'No subnick' }}
	               <small>
	                {{ user.email }}
	               </small>
	            </span>
	    
	        </div>
	      </div>
	    
	    </div>
	    
	```

* **ehnbytes** (1) [1017215](https://platzi.com/comentario/1017215/) 

	Continuando con el curso!

* **Adrian Alberto Casas Lopez** (1) [970619](https://platzi.com/comentario/970619/) 

	Cuando pongo *ngIF=“user” para validar si la variable user tiene valor, y regreso al home y vulevo a ir al Profile ya no me carga los datos y tengo que darle F5, ¿alguien sabe el por que?

* **Adrian Alberto Casas Lopez** (1) [970209](https://platzi.com/comentario/970209/) 

	No se si le suceda ha alguien mas pero a mi despúes de cierto tiempo ya no me responde el menú correctamente alguien sabe a que se deba ?

* **Alex Eugenio Gavidia Donayre** (1) [550931](https://platzi.com/comentario/550931/) 
Gracias

* **Gianfranco  Verrocchi** (1) [547031](https://platzi.com/comentario/547031/) 

	Logre completar el codigo, pero hay un error que me aparece y no logro entender porque sale. Sin embargo todo funciona bien.
	
	El error:  
	![Screenshot from 2019-03-28 18-55-23.png](https://static.platzi.com/media/user_upload/Screenshot%20from%202019-03-28%2018-55-23-3df99655-fb7b-4db7-a136-ff11ed2cec52.jpg)
	
	El constructor que trae los datos de firebase:
	``` 
	    <  constructor(private router: Router, private userservice: UserService, private authenticationService: AuthenticationService) {
	        this.userservice.getUsers().valueChanges().subscribe((data: User[]) => {
	          this.friends = data;
	        }, (error) => {
	          console.log('error obteniendo lista de usuarios:', error);
	        });
	    
	        this.authenticationService.getStatus().subscribe((status) => {
	          //if (status) {
	            this.userservice.getUserByID(status.uid).valueChanges().subscribe((data: User) => {
	              this.currentUser = data;
	              console.log(this.currentUser);
	            },
	             (error2) => {
	              console.log(error2);
	             });
	          // }
	        }, (error) => {
	          console.log(error);
	        });
	    
	      }  constructor(private router: Router, private userservice: UserService, private authenticationService: AuthenticationService) {
	        this.userservice.getUsers().valueChanges().subscribe((data: User[]) => {
	          this.friends = data;
	        }, (error) => {
	          console.log('error obteniendo lista de usuarios:', error);
	        });
	    
	        this.authenticationService.getStatus().subscribe((status) => {
	            this.userservice.getUserByID(status.uid).valueChanges().subscribe((data: User) => {
	              this.currentUser = data;
	              console.log(this.currentUser);
	            },
	             (error2) => {
	              console.log(error2);
	             });
	        }, (error) => {
	          console.log(error);
	        });
	    
	      }
	    
	```
	
	Logre eliminar el error verificando si status no es null…
	``` 
	      constructor(private router: Router, private userservice: UserService, private authenticationService: AuthenticationService) {
	        this.userservice.getUsers().valueChanges().subscribe((data: User[]) => {
	          this.friends = data;
	        }, (error) => {
	          console.log('error obteniendo lista de usuarios:', error);
	        });
	    
	        this.authenticationService.getStatus().subscribe((status) => {
	           if (status) {
	            this.userservice.getUserByID(status.uid).valueChanges().subscribe((data: User) => {
	              this.currentUser = data;
	              console.log(this.currentUser);
	            },
	             (error2) => {
	              console.log(error2);
	             });
	           }
	        }, (error) => {
	          console.log(error);
	        });
	    
	      }
	    
	```
	
	Pero no entiendo porque pasa esto…

	* **Walter Lensinas** [547031] (1)

		¿En el primer código tenes dos constructores? Estimo que es un error de copy-past.

	* **Edwin De Jesus Chiyopa Garcia** [547031] (2)

		Porque cuando inicia hay un retardo para que pueda traer los datos, y en ese momentos los datos son null, agrégale en el div un *ngIf=“user”, eso hará que hasta que tenga los datos desde firebase ejecute lo demás, espero haberme hecho entender…

* **Jecsham Castillo** (1) [449589](https://platzi.com/comentario/449589/) 

	`src="/assets/img/logo_live_{{user.status || 'offline'}}.png"`

* **Jeffry Davila** (1) [398501](https://platzi.com/comentario/398501/) 

	Terminado…  
	![primero.JPG](https://static.platzi.com/media/user_upload/primero-52537a62-5cf5-4812-9771-b18492e2560d.jpg)

	* **Jeffry Davila** [398501] (1)
![segundo.JPG](https://static.platzi.com/media/user_upload/segundo-2a227344-b83c-4673-968a-0b22b8e7c75e.jpg)

* **carlosextra1** (1) [391879](https://platzi.com/comentario/391879/) 

	home con foto y datos del user logeado  
	![](http://www.extrasistemas.com/Platzi/Angular/angular_home.PNG)
	
	profile  
	![](http://www.extrasistemas.com/Platzi/Angular/angular_profile.PNG)

* **Gianfranco  Verrocchi** (1) [55940](https://platzi.com/comentario/547031/) 
Logre completar el codigo, pero hay un error que me aparece y no logro entender porque sale. Sin embargo todo funciona bien. El error: E...

	* **Walter Lensinas** [55940] (1)

		¿En el primer código tenes dos constructores? Estimo que es un error de copy-past.

## 0450. Seleccionar fotos usando una librería para image cropping [12787](https://platzi.com/clases/1340-angular-avanzado/12787-seleccionar-fotos-usando-una-libreria-para-image-c/)

### Descripción:


Para seleccionar y preparar la foto que usaremos en el perfil de usuario, haremos uso de la librería imageCropper, que nos permite recortar la imagen seleccionada a un formato cuadrado, entre otras opciones.

### Links:

* [ngx-image-cropper  -  npm](https://npmjs.com/package/ngx-image-cropper)

### Comentarios:

* **Juan Carlos Felizzola Vega** (6) [386739](https://platzi.com/comentario/386739/) 

	 **Si no les llega a funcionar el botón de subir imagen** (como me pasó a mi).  
	Recuerden que le agregamos un estilo a los `input['file']` de `display: none`.  
	A mi me tocó dejar el valor por defecto del `input` para que funcionara, luego podrán agregarle estilos.

	* **Spyderp** [386739] (1)

		Yo use esta guía de css para arreglarlo luego de tu sugerencia y funciona perfectamente para que la pruebes.  
		[](https://blog.benestudio.co/custom-file-upload-button-with-pure-css-5aacf39aa0a)

	* **Spyderp** [386739] (4)

		<https://blog.benestudio.co/custom-file-upload-button-with-pure-css-5aacf39aa0a>

* **Daniel Pereira** (3) [402228](https://platzi.com/comentario/402228/) 

	image cropper se actualizo y el método imageCropped ahora recibe un objeto de tipo ImageCroppedEvent en lugar de un string, para utilizar esta interfaz hay que importarlo dentro del **profile.component.ts** desde
	``` 
	    import { ImageCroppedEvent } from'ngx-image-cropper/src/image-cropper.component';
	    
	```

	* **Jecsham Castillo** [402228] (1)

		Pero sucede que vamos es a guardar la URL del archivo en la database, que viene siendo string

	* **Gustavo Ramírez Apache** [402228] (2)

		```
		    import { ImageCroppedEvent } from 'ngx-image-cropper/src/interfaces/image-cropped-event.interface';
		    
		```

* **Zolider** (2) [81387](https://platzi.com/comentario/980322/) 
Tengo esta duda… ¿Qué librería conocen en VSC que importe en automático los modulos? Por ejempo este que acabamos de instalar, el pequeño...

* **Cristian David Franco Garcia** (1) [451070](https://platzi.com/comentario/451070/) 

	Con interpolación:
	``` 
	    setUserAvatar(uid: any, avatar: string) {
	        returnthis.angularFireDatabase.object(`/users/${uid}/avatar`).set(avatar);
	      }
	    
	```

	* **Edwin De Jesus Chiyopa Garcia** [451070] (1)

		Cual es la ventaja de usar lo que mencionas?

* **Mauricio Quiñones** (1) [75955](https://platzi.com/comentario/878594/) 
Buena noche, esta libreria la puedo utilizar en ionic 4 y en caso de que no cual puedo utilizar?

## 0460. Guardando las imágenes de perfil en nuestra base de datos de firebase [12788](https://platzi.com/clases/1340-angular-avanzado/12788-guardando-las-imagenes-de-perfil-en-nuestra-base-d/)

### Descripción:


Para incluir la funcionalidad de agregar foto a nuestro perfil, usaremos el servicio Firebase Storage de Firebase, con AngularFireStorage.

El servicio FirebaseStorage funciona como un repositorio de recursos estáticos (organizado en carpetas) y se implementa en Angular a través del módulo AngularFireStorageModule, que debemos incluir en app.modules.ts

Finalmente, subiremos la imagen recortada a FirebaseStorage en formato base64, que será convertida por el storage a formato binario. Guardaremos luego en la base de datos, la referencia a la url de esa imagen que obtenemos mediante el método `getDownloadURL()`.

### Comentarios:

* **crarrivillaga** (7) [390987](https://platzi.com/comentario/390987/) 

	Para los que obtengan un error en la consola de: **Error: No Storage Bucket defined in Firebase Options…**
	
	Deben ir a la configuracion del proyecto en la consola de Firebase y buscar el valor que tiene **storageBucket**. Por defecto, este valor viene vacio al crear el proyecto, pero al configurar el **storage** , éste valor cambia en la configuracion, por tanto hay que cambiarlo en la configuracion en **envionment.ts**.

* **Alfonso Adame Rueda** (3) [543968](https://platzi.com/comentario/543968/) 

	a mi me funciono con este release:  
	import { AngularFireStorage } from ‘@angular/fire/storage’;//antes era import { AngularFireStorage } from ‘angularfire2/storage’;

	* **Josue Anthony Facundo Chumacero** [543968] (2)

		claro es la nueva actualización junto con angular 8

* **mayratarazona** (3) [540202](https://platzi.com/comentario/540202/) 

	En mi caso llene el campo de storageBucket en enviroment.ts con “[platzinger-dd5bc.appspot.com](http://platzinger-dd5bc.appspot.com)”. Para solucionar el error de No Storage Bucket defined in Firebase Option.  
	Solo es el nombre de mi proyecto seguido de **.appspot.com**

	* **Ale17273has** [540202] (1)

		No es necesario solo debes haber creado el firebase storage primero a traves de la consola

	* **Wilson Marino Pablo Mendez** [540202] (1)

		Graciar por el aporte.  
		Esta vacio el apartado de la url del Storage.

* **eric-alejandro-asce** (2) [923312](https://platzi.com/comentario/923312/) 

	firebaseStorage Deberá ser AngularFireStorage el import a Enero 2020 es import { AngularFireStorage } from '@angular/fire/storage';

* **Andrs** (2) [396380](https://platzi.com/comentario/396380/) 

	```
	        async guardar(){
	    
	            var user = {
	              username:this.user.username,
	              phone:this.user.phone,
	              email:this.user.email,
	              country:this.user.country,
	              name:this.user.name,
	              lastName:this.user.lastName,
	              uid: this.user.uid,
	              cover: this.user.cover || '../../../assets/img/profilePic.jpg'
	            }
	    
	            if(this.croppedImage){
	              let picture = await this.crudService.savePicProfile(this.croppedImage)
	                  user.cover = picture;
	            }
	    
	              this.authService.editUser(user)
	                .then((data)=>{
	                  returnthis.apisService.openSnackBar('Usuario Actualizado', 'SUCCESS')
	                })
	          }
	    
	    
	    
	    //service.ts
	    
	    
	    
	      savePicProfile(croppedImage){
	    
	          const currentCoverId =  UUID.UUID();
	    
	          returnthis.firebaseStorage.ref(`pictures/${currentCoverId}.jpg`).putString(croppedImage, 'data_url')
	                  .then((res)=>{
	                      returnnew Promise((resolve, reject)=>{
	                        let picture =  this.firebaseStorage.ref(`pictures/${currentCoverId}.jpg`).getDownloadURL();
	                        picture.subscribe((p)=>{
	                              return resolve(p)
	                          })
	                      })
	                  })
	      }
	    
	    
	```

* **Kalin** (1) [857627](https://platzi.com/comentario/857627/) 

	alguien sabe como cerrar la vista previa de la imagen del npx image cropper?

* **Alex Eugenio Gavidia Donayre** (1) [551352](https://platzi.com/comentario/551352/) 
Gracias

* **Patricio Jacho** (1) [484845](https://platzi.com/comentario/484845/) 

	Genial, creo que faltó que al momento de modificar la imagen, también se actuaicen los demás campos, en caso de ser modificados.

* **carlosextra1** (1) [391920](https://platzi.com/comentario/391920/) 

	ahi va la cosa!  
	![](http://www.extrasistemas.com/Platzi/Angular/angular-imgs.PNG)

# Conversación [2353]

## 0470. ¿Cómo resolver el problema de comunicación en tiempo real [12789](https://platzi.com/clases/1340-angular-avanzado/12789-como-resolver-el-problema-de-comunicacion-en-tiemp/)

### Descripción:


Generalmente, en sistemas tradicionales, un cliente envía la información al servidor, donde va a quedar almacenada hasta que otro cliente haga una petición y descargue los datos actualizados a su entorno local. Esto debe hacerlo el cliente dos en intervalos frecuentes que pueden ir desde algunos minutos hasta un segundo o menos, lo que pudiera significar una sobre carga del servidor. Esto va a depender de la cantidad de clientes que realicen peticiones en simultáneo.

Firebase por su parte, usa una estrategia de sockets para manejar las actualizaciones que suceden en su servicio de base de datos en tiempo real. Esto significa que una vez realizada la primera conexión entre la app y el servidor, queda abierto un canal de comunicación permanente entre el servidor y el cliente, y al haber alguna actualización en la base de datos, ésta es notificada al navegador en cuestión de milisegundos, sin necesidad de que éste haya hecho una petición explícitamente, ni sometiendo al servidor a atender peticiones recurrentes en intervalos específicos.

En nuestra app sólo deberemos tener un método que esté subscrito a los cambios notificados por el servicio de base de datos de firebase a través de un Observable, para actualizar la información de nuestro componente.

### Comentarios:

* **DESTRUN** (4) [424174](https://platzi.com/comentario/424174/) 

	Eso de abajo no es KMS xd?

* **Jecsham Castillo** (3) [449641](https://platzi.com/comentario/449641/) 

	Socket y Observables 😎

* **ehnbytes** (1) [1017458](https://platzi.com/comentario/1017458/) 

	Genial!

* **Adrian Alberto Casas Lopez** (1) [971098](https://platzi.com/comentario/971098/) 

	WOW!!!

* **Alex Eugenio Gavidia Donayre** (0) [551354](https://platzi.com/comentario/551354/) 
Interested

## 0480. Enviando un mensaje (con reproducción de sonido) [12790](https://platzi.com/clases/1340-angular-avanzado/12790-enviando-un-mensaje-con-reproduccion-de-sonido/)

### Descripción:


Para el manejo de la conversación en nuestra app, crearemos un servicio llamado conversation, usando el Angular CLI. Usaremos el servicio de base de datos en tiempo real de Firebase a través del objeto AngularFireDatabase inyectado a nuestro servicio en el constructor.

Cada mensaje estará identificado con un _timestamp_ del momento en que se generó y una clave única formada por el _user.uid_ de los dos usuarios que intervienen en la conversación, ordenados con sort() y concatenados con join().

### Comentarios:

* **ivan_acg** (2) [437592](https://platzi.com/comentario/437592/) 

	Esta clase estuvo muy buena pero muy compleja , sería de ayuda que hagan un grafico de lo que se está haciendo con el codigo , ya que con ver el codigo y escuchar lo que el profesor dice no basta.

* **Jessie Buckland Pérez** (1) [916500](https://platzi.com/comentario/916500/) 

	Muy interesante el mecanismo de comunicación para los mensajes con la lógica de los ids, voy a tratar de implementarlo con una api graphql propia agregándole un servidor de ws para las suscripciones. ¿Alguien me recomienda un sistema de buenas prácticas para poder realizar esto empleando además un sistema de almacenamiento de tipo mysql y mongodb de manera que tenga una redundancia de las conversaciones en ambas bases de datos? 😃

* **jinvernon** (1) [841203](https://platzi.com/comentario/841203/) 

	Una forma interesante y alternativa de hacer la misma funcionalidad sería aplicar un .include() sobre los 2 uid concatenados. Así si esta de primero o de segundo, solo verificarias si existen los 2.  
	Saludos!

* **Ruben Garcia** (1) [593067](https://platzi.com/comentario/593067/) 

	Muy bien explicado.

* **Alfonso Adame Rueda** (1) [544618](https://platzi.com/comentario/544618/) 

	hola buenos dias, me sale este error en este componente.  
	core.js:1673 ERROR TypeError: Cannot read property ‘uid’ of null

	* **Angel Hernandez** [544618] (1)

		Hola 😄 verifica tu variable de la cual estas intentando obtener la propiedad uid ya que esta llegando nula

	* **Alfonso Adame Rueda** [544618] (1)

		hola mira este es el codigo de mi componente:
		``` 
		    import { Component, OnInit } from '@angular/core';
		    import { ActivatedRoute} from '@angular/router';
		    import { User } from '../interfaces/user';
		    import { UserService } from "../services/user.service";
		    import { ConversationService } from "../services/conversation.service";
		    import { AuthenticationService } from "../services/authentication.service";
		    import { AngularFireAuthModule } from '@angular/fire/auth';
		    
		    
		    
		    
		    @Component({
		      selector: 'app-conversation',
		      templateUrl: './conversation.component.html',
		      styleUrls: ['./conversation.component.css']
		    })
		    export class ConversationComponent implements OnInit {
		    friendId:any;
		    friend: User;
		    today: any = Date.now();
		    user:User;
		    textMessage:string;
		    conversation_id:string;
		    ids:string;
		    uid:string;
		    
		      constructor(private activatedRoute : ActivatedRoute,
		                private userService: UserService,
		                private conversationService:ConversationService,private AuthenticationService:AuthenticationService) { 
		      this.friendId = this.activatedRoute.snapshot.params['uid'];
		      console.log(this.friendId);
		      
		              this.AuthenticationService.getStatus().subscribe((session)=>{
		              this.userService.getUserById(session.uid).valueChanges().subscribe((user:User)=>{
		              this.user = user;
		              this.userService.getUserById(this.friendId).valueChanges().subscribe((data: User) => {
		              this.friend = data;
		              const ids =[this.user.uid,this.friend.uid].sort();//ordena el arreglo para obtener los ids en el mismo orden del arreglo
		               this.conversation_id = ids.join('|');    
		        }, (error) => {
		          console.log(error);
		        });
		             })
		          })
		        
		    }
		    
		    
		    
		      ngOnInit() {
		      }
		      sendMessage() {
		        const message = {
		          uid: this.conversation_id ,
		          timestamp :  Date.now(),
		          text: this.textMessage,
		          sender: this.user.uid,
		          receiver: this.friend.uid
		        };
		        this.conversationService.createConversation(message).then(()=>{
		           this.textMessage = '';
		           
		        });
		      }
		    
		    }
		    
		    
		```

	* **Walter Lensinas** [544618] (1)

		¿Lo pudiste solucionar? ¿Subiste el código a un repo?

	* **Alfonso Adame Rueda** [544618] (1)

		no nada , si lo subí, mi repo se llama aitageo/angular6

	* **Alfonso Adame Rueda** [544618] (1)

		el error esta en el uid de el friend en el array,donde se obtienen los uids de los dos.

	* **Walter Lensinas** [544618] (2)

		Recién lo clone, instale las dependencias y al iniciar, todo funciona. En Consola todo OK.
		
		<https://github.com/aitageo/angular6>
		
		Consejo: no subas los datos de environment al repositorio.

	* **Walter Lensinas** [544618] (1)

		Encontré el siguiente bug en profile. No te toma el preview de la imagen y no se sube a firebase.
		
		![bug-avatar.jpg](https://static.platzi.com/media/user_upload/bug-avatar-4516f9b0-987d-4d8d-8b4e-ce3fb7a33e1a.jpg)

	* **Alfonso Adame Rueda** [544618] (1)

		hola buenas tardes , ya arregle eso que dices pero sigue apareciendo el mismo error del uid  
		core.js:1673 ERROR TypeError: Cannot read property ‘uid’ of null  
		at SafeSubscriber._next (conversation.component.ts:36)  
		at SafeSubscriber.push…/node_modules/rxjs/_esm5/internal/Subscriber.js.SafeSubscriber.__tryOrUnsub (Subscriber.js:195)  
		at SafeSubscriber.push…/node_modules/rxjs/_esm5/internal/Subscriber.js.SafeSubscriber.next (Subscriber.js:133)  
		at Subscriber.push…/node_modules/rxjs/_esm5/internal/Subscriber.js.Subscriber._next (Subscriber.js:77)  
		at Subscriber.push…/node_modules/rxjs/_esm5/internal/Subscriber.js.Subscriber.next (Subscriber.js:54)  
		at MapSubscriber.push…/node_modules/rxjs/_esm5/internal/operators/map.js.MapSubscriber._next (map.js:41)  
		at MapSubscriber.push…/node_modules/rxjs/_esm5/internal/Subscriber.js.Subscriber.next (Subscriber.js:54)  
		at angularfire2.js:49  
		at ZoneDelegate.push…/node_modules/zone.js/dist/zone.js.ZoneDelegate.invoke (zone.js:391)  
		at Object.onInvoke (core.js:3820)

	* **David Alejandro Mosquera Moreno** [544618] (1)

		Prueba iniciando sesión de nuevo.
		
		Puede ser que el constructor esté tratando de traer al usuario antes de que este esté listo, y por lo tanto la propiedad de **_uid_** no está ahí todavía.

	* **Mauricio Quiñones** [544618] (1)

		Hola Alfonso, pudiste solucioar el error?

* **Alfonso Adame Rueda** (1) [544117](https://platzi.com/comentario/544117/) 

	hola buenas tardes , me gustaría saber que plugin le puedo poner a sublime text para que haga los imports automáticamente.

	* **Adrian Camilo Caminos** [544117] (1)

		Hola te puedes guiar en este enlace te explican como serial el proceso quedo atento saludes [](https://www.sitepoint.com/top-angular-plugins-sublime-text/)

	* **Adrian Camilo Caminos** [544117] (1)

		<https://www.sitepoint.com/top-angular-plugins-sublime-text/>

	* **Alfonso Adame Rueda** [544117] (1)

		gracias por responder fue de mucha ayuda.

* **Gabriel Solorzano** (1) [536368](https://platzi.com/comentario/536368/) 

	Recordar que  
	$ ng generate service services/conversation
	
	se puede resumir así:  
	$ ng g s services/conversation

* **dcortesnet** (1) [517344](https://platzi.com/comentario/517344/) 

	en sí que significa valueChanges() a nivel de código que es?

	* **Mateo Santiago Zapata Maldonado** [517344] (1)

		Hola dCortesNet.
		
		El Metodo valueChanges() lo que hace es estar esperando cambios en la lista en especifico, digamos que tienes ‘/usuarios’ entonces este metodo retorna una promesa y se activara siempre que haya algun update, create o delete dentro de ella para que tu generes el evento en la web como desees.
		
		¿Te explique bien?

* **ivan_acg** (1) [437600](https://platzi.com/comentario/437600/) 

	```
	    sendMessage() {
	        const message = {
	          uid: this.conversation_id ,
	          timestamp :  Date.now(),
	          text: this.textMessage,
	          sender: this.user.uid,
	          receiver: this.friend.uid
	        };
	        this.conversationService.createConversation(message);
	      }
	    
	    
	```
	
	Este es el resumen de la clase , con esto es que funciona el mundo prácticamente , impresionante ; no puedo esperar a construir mi propio chat.

* **Mauricio Quiñones** (1) [75980](https://platzi.com/comentario/879282/) 
Hola, estoy implementando este mismo sistema para una app en Ionic. Lo que quiero saber es como enviar la notificacion de mensaje nuevo a...

	* **aragonesteban (Platzi)** [75980] (2)

		Hola Mauricio, Ionic tiene una integración con OneSignal que es un proveedor de push notification, puedes seguir la documentación de Ionic y ver como lo puedes usar en tu proyecto  
		<https://ionicframework.com/docs/native/onesignal>

* **Arturo Mojica Guerrero** (1) [72827](https://platzi.com/comentario/823688/) 
Disculpen una pregunta, desde que estamos trabajando con socket con firebase siempre me toca hacer un setimeout para esperar los valores ...

	* **Poseidonihp** [72827] (2)

		Si es normal cuando ya se empieza a trabajar en proyectos que requieren un nivel mayor de profesionalismo, se empiezan a utilizar mas las promesas y los observables para hacer y mantener todo Asíncrono.

* **Alfonso Adame Rueda** (1) [55746](https://platzi.com/comentario/544618/) 
hola buenos dias, me sale este error en este componente. core.js:1673 ERROR TypeError: Cannot read property ‘uid’ of null

	* **Angel Hernandez** [55746] (1)

		Hola 😄 verifica tu variable de la cual estas intentando obtener la propiedad uid ya que esta llegando nula

* **Alfonso Adame Rueda** (1) [55703](https://platzi.com/comentario/544117/) 
hola buenas tardes , me gustaría saber que plugin le puedo poner a sublime text para que haga los imports automáticamente.

	* **Adrian Camilo Caminos** [55703] (1)

		Hola te puedes guiar en este enlace te explican como serial el proceso quedo atento saludes [](https://www.sitepoint.com/top-angular-plugins-sublime-text/)

## 0490. Mostrando conversación [12791](https://platzi.com/clases/1340-angular-avanzado/12791-mostrando-conversacion/)

### Descripción:


Para mostrar la conversación creamos el método getConversation en nuestro servicio conversation. Este método usará los uids de los dos usuarios que participan en la conversación para obtener los registros desde la base de datos.

El resultado de la consulta a la base de datos es devuelto en un arreglo de objetos json con los detalles que definimos para cada mensaje de la conversación, los cuales mostraremos en el componente html utilizando la directiva *ngFor para recorrerlo y mostrar un elemento div para cada uno de los mensajes recibidos.

A cada elemento message del arreglo, le asignaremos un atributo buleano llamado _seen_ para indicar que el mensaje ya ha sido mostrado. Adicionalmente reproduciremos un audio cada vez que se muestre un nuevo mensaje. Esto lo haremos creando un objeto **Audio** de html5 al que le asignaremos el src con la url del archivo de audio seleccionado y ejecutando luego el método _play()_

### Comentarios:

* **Teofilo Rosales Gama** (6) [394789](https://platzi.com/comentario/394789/) 

	Soy el unico que sintio nostalgia?

	* **mario-salinas** [394789] (1)

		Presente… jeje

	* **Gabriel Solorzano** [394789] (1)

		Claro que no sniff sniff

* **Felipe Concha Almeida** (3) [638174](https://platzi.com/comentario/638174/) 

	Es una mala practica de programación darle nombre “m” a la variable del *ngFor ya que no es un nombre significativo y le quita legibilidad al código.

* **Damian Spizzirri** (2) [660986](https://platzi.com/comentario/660986/) 

	Se me cayo una lagrima al recordarlo cuando lo hiciste sonar.

* **David Alejandro Mosquera Moreno** (1) [872881](https://platzi.com/comentario/872881/) 

	Otros nombres más descriptivos para la directiva *ngFor pueden ser:  
	.  
	![mensaje.png](https://static.platzi.com/media/user_upload/mensaje-317db449-dbd7-4037-bb09-eb8b1c9bc929.jpg)

* **Usuario ESolutions** (1) [817044](https://platzi.com/comentario/817044/) 

	El servicio recarga nuevamente todos los mensajes por cada mensaje que se envia, deberia mejorarse eso.

* **Alfonso Adame Rueda** (1) [546943](https://platzi.com/comentario/546943/) 

	me sigue saliendo este error:  
	core.js:1673 ERROR TypeError: Cannot read property ‘uid’ of null

* **Alfonso Adame Rueda** (1) [546942](https://platzi.com/comentario/546942/) 

	este es mi conversation.service.ts
	``` 
	    <import { Injectable } from'@angular/core';
	    import { AngularFireDatabase } from'@angular/fire/database';
	    
	    @Injectable({
	      providedIn: 'root'
	    })
	    exportclassConversationService{
	    
	      constructor(private angularFireDatabase:AngularFireDatabase) {} 
	       createConversation(conversation){
	       	returnthis.angularFireDatabase.object('conversations/' + conversation.uid + '/' + conversation.timestamp).set(conversation);
	    }
	    getConversation(uid){
	    	returnthis.angularFireDatabase.list('conversations/' + uid );
	    
	    }
	        
	        
	     }>
	    
	```

* **Alfonso Adame Rueda** (1) [546940](https://platzi.com/comentario/546940/) 

	este es mi conversation.component.ts
	``` 
	    <import { Component, OnInit } from '@angular/core';
	    import { ActivatedRoute} from '@angular/router';
	    import { User } from '../interfaces/user';
	    import { UserService } from "../services/user.service";
	    import { ConversationService } from "../services/conversation.service";
	    import { AuthenticationService } from "../services/authentication.service";
	    import { AngularFireAuthModule } from '@angular/fire/auth';
	    
	    
	    
	    
	    @Component({
	      selector: 'app-conversation',
	      templateUrl: './conversation.component.html',
	      styleUrls: ['./conversation.component.css']
	    })
	    export class ConversationComponent implements OnInit {
	    friendId:any;
	    friend: User;
	    today: any = Date.now();
	    user:User;
	    textMessage:string;
	    conversation_id:string;
	    ids:any;
	    uid:any;
	    
	      constructor(private activatedRoute : ActivatedRoute,
	                private userService: UserService,
	                private conversationService:ConversationService,private AuthenticationService:AuthenticationService) { 
	      this.friendId = this.activatedRoute.snapshot.params['uid'];
	      console.log(this.friendId);
	      
	              this.AuthenticationService.getStatus().subscribe((session)=>{
	              this.userService.getUserById(session.uid).valueChanges().subscribe((user:User)=>{
	              this.user = user;
	              this.userService.getUserById(this.friendId).valueChanges().subscribe((data: User) => {
	              this.friend = data;
	              this.uid = data;
	              const ids = [this.user.uid, this.friend.uid].sort();//ordena el arreglo para obtener los ids en el mismo orden del arreglo
	               this.conversation_id = ids.join('|');    
	        }, (error) => {
	          console.log(error);
	        });
	             });
	          });
	        
	    }
	    
	    
	    
	      ngOnInit() {
	      }
	      sendMessage() {
	        const message = {
	          uid: this.conversation_id ,
	          timestamp :  Date.now(),
	          text: this.textMessage,
	          sender: this.user.uid,
	          receiver: this.friend.uid
	        };
	        this.conversationService.createConversation(message).then(()=>{
	           this.textMessage = '';
	           
	        });
	      }
	    
	    }
	    >
	    
	```

* **Alfonso Adame Rueda** (1) [546937](https://platzi.com/comentario/546937/) 

	hola buenas tardes quien me ayuda por favoooor con este error que me sale :core.js:1673 ERROR TypeError: Cannot read property ‘uid’ of null

* **Alfonso Adame Rueda** (1) [545706](https://platzi.com/comentario/545706/) 

	me sale este error:  
	core.js:1673 ERROR TypeError: Cannot read property ‘uid’ of null

	* **Ale17273has** [545706] (1)

		se debe que en el router no estas pasando el parametro, si lo tienes configurado en el route?

* **Teofilo Rosales Gama** (1) [394790](https://platzi.com/comentario/394790/) 

	12:22 Soy el unico que sintio nostalgia?

* **Alfonso Adame Rueda** (1) [55934](https://platzi.com/comentario/546943/) 
me sigue saliendo este error: core.js:1673 ERROR TypeError: Cannot read property ‘uid’ of null

* **Alfonso Adame Rueda** (1) [55933](https://platzi.com/comentario/546940/) 
este es mi conversation.component.ts <import { Component, OnInit } from '@angular/core'; import { ActivatedRoute} from '@angular...

* **Alfonso Adame Rueda** (1) [55834](https://platzi.com/comentario/545706/) 
me sale este error: core.js:1673 ERROR TypeError: Cannot read property ‘uid’ of null

	* **Ale17273has** [55834] (1)

		se debe que en el router no estas pasando el parametro, si lo tienes configurado en el route?

## 0500. Enviando un zumbido (con reproducción de sonido y animación) [12792](https://platzi.com/clases/1340-angular-avanzado/12792-enviando-un-zumbido-con-reproduccion-de-sonido-y-a/)

### Descripción:


El envío de zumbidos está compuesto de varios aspectos: un mensaje informando que alguien envió un zumbido, la reproducción de un sonido particular y la animación de la pantalla.  
Para esto crearemos un par de métodos nuevos en nuestro servicio conversation, llamados: sendZumbido() y doZumbido().

La animación será aplicada al elemento del html con la directiva [ngClass] y una clase .shaker que implementa animcaiones de CSS. Esta clase será aplicada al html sólo cuando se cumpla la expresión buleana que indica que el tipo de mensaje es un zumbido.

### Comentarios:

* **Daniel Pereira** (13) [402867](https://platzi.com/comentario/402867/) 

	el código de la animación
	``` 
	    .shaker {
	      animation: shake .5s;
	      animation-iteration-count: infinite;
	    }
	    @keyframes shake {
	      0% { transform: translate(1px, 1px) rotate(0deg); }
	      10% { transform: translate(-1px, -2px) rotate(-1deg); }
	      20% { transform: translate(-3px, 0px) rotate(1deg); }
	      30% { transform: translate(3px, 2px) rotate(0deg); }
	      40% { transform: translate(1px, -1px) rotate(1deg); }
	      50% { transform: translate(-1px, 2px) rotate(-1deg); }
	      60% { transform: translate(-3px, 1px) rotate(0deg); }
	      70% { transform: translate(3px, 1px) rotate(-1deg); }
	      80% { transform: translate(-1px, -1px) rotate(1deg); }
	      90% { transform: translate(1px, 2px) rotate(0deg); }
	      100% { transform: translate(1px, -2px) rotate(-1deg); }
	    }
	    
	```

	* **Jecsham Castillo** [402867] (3)

		Gracias!

* **Juan Carlos Felizzola Vega** (2) [386927](https://platzi.com/comentario/386927/) 

	 **Curso de Animación para la web:**  
	<https://platzi.com/clases/animaciones-web/>

	* **David Alejandro Mosquera Moreno** [386927] (1)

		De los mejores que hay en Platzi

* **Juan Antonio Campoy Lira** (1) [985626](https://platzi.com/comentario/985626/) 

	De esta manera se ejecuta a quien lo reciba y también no se ejecutan el sonido ni el zumbido cada ves que se entra a la conversación
	``` 
	      doZumbido(){
	        const audio = new Audio('assets/sound/zumbido.m4a');
	        audio.play();
	        this.shake = true;
	        window.setTimeout(()=>{
	          this.shake =  false;
	        },1000  );
	      }
	    
	    
	      getConversation(){
	        console.log(this.conversartion_Id);
	      this.conversationService.getConversation(this.conversartion_Id).valueChanges().subscribe((data)=>{
	        console.log(data,"conversacion");
	        this.conversation = data;
	        this.conversation.forEach((message)=>{
	          if(!message.seen){
	            message.seen = true;
	            this.conversationService.editConversation(message);
	            const audio = new Audio ('assets/sound/new_message.m4a');
	            audio.play();
	          }if(message.type == 'zumbido' && message.seen == false){
	            this.doZumbido();
	          }
	        });
	      },
	      (error)=>{console.log(error);})
	      }
	    
	```

* **eric-alejandro-asce** (1) [925739](https://platzi.com/comentario/925739/) 

	En el ejemplo de la clase el zumbido solo se efectúa en la pantalla de quien lo envía, para que se ejecute en el que lo envía y el que lo recibe debería de ser así:
	
	doZumbido(){  
	const audio = new Audio(‘assets/sound/zumbido.m4a’);  
	audio.play();  
	this.shake = true;  
	window.setTimeout( () => {  
	this.shake = false;  
	}, 1000);  
	}
	
	y llamar doZumbido() en el:
	
	if (message.type == ‘zumbido’) {  
	this.doZumbido();  
	}

	* **Juan Antonio Campoy Lira** [925739] (1)

		pero tienes el PROBLEMA DE QUE SIEMPRE QUE ENTRES SE EJECUTARA
		``` 
		    <  doZumbido(){
		        const audio = new Audio('assets/sound/zumbido.m4a');
		        audio.play();
		        this.shake = true;
		        window.setTimeout(()=>{
		          this.shake =  false;
		        },1000  );
		      }
		    
		    
		      getConversation(){
		        console.log(this.conversartion_Id);
		      this.conversationService.getConversation(this.conversartion_Id).valueChanges().subscribe((data)=>{
		        console.log(data,"conversacion");
		        this.conversation = data;
		        this.conversation.forEach((message)=>{
		          if(!message.seen){
		            message.seen = true;
		            this.conversationService.editConversation(message);
		            const audio = new Audio ('assets/sound/new_message.m4a');
		            audio.play();
		          }if(message.type == 'zumbido' && message.seen == false){
		            this.doZumbido();
		          }
		        });
		      },
		      (error)=>{console.log(error);})
		      }>
		    
		```

	* **Juan Antonio Campoy Lira** [925739] (1)

		y asi ya no compa

* **Brandon Iván Quiroa Loarca** (1) [625276](https://platzi.com/comentario/625276/) 

	Me encanta como esta quedando el Messenger 😄

* **Angel Javier Puc Yamá** (1) [622122](https://platzi.com/comentario/622122/) 

	Alguien hizo el reto?

* **Gabriel Solorzano** (1) [536397](https://platzi.com/comentario/536397/) 

	Ese zumbido me remota a mi niñez

## 0510. Reto Envía una foto [13007](https://platzi.com/clases/1340-angular-avanzado/13007-reto-envia-una-foto/)

### Descripción:


Actualmente, en la pantalla de conversación se pueden enviar mensajes de texto y también zumbidos. Ahora, usando los conocimiento adquiridos para subir imágenes y usarla como avatar, sube imágenes que puedas enviar como un mensaje en la pantalla de conversación.

### Comentarios:

* **Juan Diego Lopez Triana** (4) [374426](https://platzi.com/comentario/374426/) 

	**Me demore un poquito pero lo logre: **  
	![Captura1.PNG](https://static.platzi.com/media/user_upload/Captura1-6cb74f61-af82-4485-8eeb-e30801472547.jpg)  
	![Captura2.PNG](https://static.platzi.com/media/user_upload/Captura2-de2ae48b-c947-4faf-bb1d-3a564623827b.jpg)  
	![Captura3.PNG](https://static.platzi.com/media/user_upload/Captura3-9a12d2ea-4298-4970-986d-0c465905685c.jpg)

	* **ziker** [374426] (2)

		Podrias compartir como hiciste el modal?

	* **William Vega** [374426] (2)

		Que buen código, excelente tu uso de async - await.

* **Ana Lorena Bojorquez Acuña** (3) [561819](https://platzi.com/comentario/561819/) 
	
	![Captura2.PNG](https://static.platzi.com/media/user_upload/Captura2-e7561914-235f-43c2-bcf3-0acd675774ab.jpg)

* **Ruben Garcia** (2) [594247](https://platzi.com/comentario/594247/) 

	Reto completado:
	
	![](https://rubengarcia.com.ve/wp-content/uploads/2019/05/Captura-de-pantalla-de-2019-05-22-13-29-42.png)

* **Spyderp** (2) [450447](https://platzi.com/comentario/450447/) 

	Este reto fue más fácil de lo que creía  
	Código en conversation.component.ts
	``` 
	      sendImage() {
	        const currentPictureId = Date.now();
	        const pictures = this.firebaseStorage.ref('pictures/' + currentPictureId + '.jpg').putString(this.croppedImage, 'data_url');
	        pictures.then((result) => {
	          this.picture = this.firebaseStorage.ref('pictures/' + currentPictureId + '.jpg').getDownloadURL();
	          this.picture.subscribe((p) => {
	            const message = {
	              uid: this.conversation_id,
	              timestamp: Date.now(),
	              text: p,
	              sender: this.user.uid,
	              receiver: this.friend.uid,
	              type: 'image'
	            }
	            this.conversationService.createConversation(message).then(() => { });
	            this.croppedImage = ''
	          });
	        }).catch((error) => {
	          console.log(error)
	        });
	    doNewMessage(){
	        const audio = new Audio('assets/sound/new_message.m4a');
	        audio.play();
	      }
	      doZumbido(){
	        const audio = new Audio('assets/sound/zumbido.m4a');
	        audio.play();
	        this.shake = true;
	        window.setTimeout(()=>{
	          this.shake = false;
	        }, 1000);
	      }
	      getConversation(){
	        this.conversationService.getConversation(this.conversation_id).valueChanges().subscribe((data) => {
	          this.conversation = data;
	          this.conversation.forEach((message) => {
	            if( !message.seen){
	              message.seen = true;
	              this.conversationService.editConversation(message);
	              if(message.type == 'text'){
	                this.doNewMessage();
	              } elseif (message.type == 'image') {
	                this.doNewMessage();
	              } elseif (message.type == 'zumbido') {
	                this.doZumbido();
	              }
	             
	            }
	          });
	          console.log(data)
	        }, (error)=>{ console.log(error)});
	      }
	    
	```
	
	![mario_send.PNG](https://static.platzi.com/media/user_upload/mario_send-4717db74-c0c6-4705-a87f-b3ccacb2d127.jpg)

* **Juan Antonio Campoy Lira** (1) [990453](https://platzi.com/comentario/990453/) 

	Pueden ver mi código en []<https://github.com/CampoyLira1994/platzinger>

* **Juan Antonio Campoy Lira** (1) [990445](https://platzi.com/comentario/990445/) 
	
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-6078e165-b43e-4dfb-96fc-bece4ace02d7.jpg)

* **e.rodriguez** (1) [849622](https://platzi.com/comentario/849622/) 

	```
	    <divclass="conversationContainer bluewhitebg" [ngClass]="{'shaker' : shake}">
	      <divclass="row">
	        <divclass="col-sm-3 maxwi300">
	          <divid="conversationSidebar">
	            <divclass="vh30">
	              <divclass="avatarFrameonline">
	                <imgsrc="{{'assets/img/generic_avatar.png'}}"class="avatarImage img-fluid">
	              </div>
	            </div>
	            <divclass="vh30"></div>
	            <divclass="vh25">
	              <divclass="avatarFrameonline">
	                <imgsrc="{{'assets/img/generic_avatar.png'}}"class="avatarImage img-fluid">
	              </div>
	            </div>
	          </div>
	        </div>
	        <divclass="col-sm-9">
	          <br/>
	          <spanclass="friendName">Amigo 1</span> (online)
	          <hr/>
	          <divclass="vh55 overscroll pabo10"id="messageArea">
	            <divclass="messageGroup" *ngFor="let message of conversation">
	              <div *ngIf="!message.type || message.type=='text'">
	                <b>{{geUserNickById(message.uid)}}</b> dice : <br/>
	                <span>{{message.text}}</span>
	              </div>
	    
	              <div *ngIf="message.type=='buzz'">
	                <b>{{geUserNickById(message.uid)}}</b> ha enviado un zumbido<br/>
	              </div>
	    
	              <div *ngIf="message.type=='image'">
	                <b>{{geUserNickById(message.uid)}}</b> dice : <br/>
	                <img [src]="message.url"alt="imagen"class="img-fluid">
	              </div>
	    
	            </div>
	          </div>
	          <divclass="messageControlsContainer">
	            <textarea [(ngModel)]="textMessage" (keyup.enter)="sendMessage()"class="form-control"cols="30"
	                      rows="5"></textarea>
	            <divid="messageToolBar">
	              <divclass="item">
	                <imgsrc="assets/img/icons/regular_smile.gif"class="tool">
	                <iname="caret-down"></i>
	              </div>
	              <divclass="item">
	                <imgsrc="assets/img/icons/wink_smile.gif"class="tool">
	                <iname="caret-down"></i>
	              </div>
	              <divclass="item" (click)="sendBuzz()">
	                <imgsrc="assets/img/zumbido.png"class="tool">
	              </div>
	    
	              <aclass="btn btn-primary btn-sm marri10"accept="image/*">Enviar</a>
	              <labelclass="custom-file-upload">
	                <inputtype="file" (change)="handleInputChange($event)">
	                <iname="image"></i> Seleccionar Imagen
	              </label>
	            </div>
	          </div>
	        </div>
	      </div>
	    </div>
	    
	    
	```
	``` 
	    import {Component, OnInit} from '@angular/core';
	    import {ActivatedRoute} from "@angular/router";
	    import {User} from "../../interfaces/user";
	    import {UserService} from "../../services/user.service";
	    import {ConversationsService} from "../../services/conversations.service";
	    import {AuthenticationService} from "../../services/authentication.service";
	    import {extractMessages} from "@angular/compiler/src/i18n/extractor_merger";
	    import {AngularFireStorage} from "@angular/fire/storage";
	    
	    @Component({
	      selector: 'app-conversation',
	      templateUrl: './conversation.component.html',
	      styleUrls: ['./conversation.component.scss']
	    })
	    export class ConversationComponent implements OnInit {
	    
	      friendId: any;
	      friendUser: User;
	      user: User;
	      conversationId: string;
	      private textMessage: string;
	      private conversation: any[];
	      shake: boolean = false;
	      private imgSrc: any = '';
	      picture: any;
	    
	    
	      constructor(private userService: UserService, private activatedRoot: ActivatedRoute, private conversationService: ConversationsService, private authenticationService: AuthenticationService, private firebaseStorage: AngularFireStorage) {
	        this.friendId = this.activatedRoot.snapshot.params['uid'];
	    
	        this.userService.getUserById(this.friendId).valueChanges().subscribe((data: User) => {
	            this.friendUser = data;
	          }, (error) => {
	            console.log(error);
	          }
	        );
	    
	        this.authenticationService.getStatus().subscribe((session) =>
	          this.userService.getUserById(session.uid).valueChanges().subscribe(
	            (user: User) => {
	              this.user = user;
	              const ids = [this.user.uid, this.friendUser.uid].sort();
	    
	              this.conversationId = ids.join('|');
	    
	              this.getConversation();
	            }
	          ));
	      }
	    
	      ngOnInit() {
	      }
	    
	      sendMessage() {
	        const message = {
	          uid: this.conversationId,
	          timestamp: Date.now(),
	          text: this.textMessage,
	          sender: this.user.uid,
	          receiver: this.friendUser.uid,
	          type: 'text'
	        }
	        this.conversationService.createConversation(message).then(() => this.textMessage = '');
	      }
	    
	    
	      sendBuzz() {
	        const message = {
	          uid: this.conversationId,
	          timestamp: Date.now(),
	          text: null,
	          sender: this.user.uid,
	          receiver: this.friendUser.uid,
	          type: 'buzz'
	        }
	        this.conversationService.createConversation(message).then(() => this.textMessage = '');
	      }
	    
	    
	      private getConversation() {
	        this.conversationService.getConversation(this.conversationId).valueChanges().subscribe((data) => {
	          console.log(data);
	          this.conversation = data;
	          this.conversation.forEach((message) => {
	    
	    
	            if (!message.seen) {
	              message.seen = true;
	              this.conversationService.editConversation(message);
	              if (message.type == 'text') {
	                const audio = new Audio('assets/sound/new_message.m4a');
	                audio.play();
	              } elseif (message.type == 'buzz') {
	                this.doBuzz();
	              }
	            }
	          })
	        }, (error) => console.log(error));
	      }
	    
	      private geUserNickById(uid) {
	        if (this.friendUser.uid === uid) {
	          returnthis.friendUser.nick;
	        } else {
	          returnthis.user.nick;
	        }
	      }
	    
	      private doBuzz() {
	        const audio = new Audio('assets/sound/zumbido.m4a');
	        audio.play();
	        this.shake = true;
	        window.setTimeout(() => {
	          this.shake = false
	        }, 1000);
	      }
	    
	      handleInputChange(event: any) {
	        var file = event.dataTransfer ? event.dataTransfer.files[0] : event.target.files[0];
	        var pattern = /image-*/;
	        var reader = new FileReader();
	        if (!file.type.match(pattern)) {
	          alert('invalid format');
	          return;
	        }
	        reader.onload = this._handleReaderLoaded.bind(this);
	        reader.readAsDataURL(file);
	      }
	    
	      _handleReaderLoaded(e) {
	        let reader = e.target;
	        this.imgSrc = reader.result;
	        console.log(this.imgSrc)
	    
	        this.sendImage();
	      }
	    
	      private sendImage() {
	        if (this.imgSrc) {
	          const currentPictureId = Date.now();
	          const pictures = this.firebaseStorage.ref('pictures/' + currentPictureId + '.jpg').putString(this.imgSrc, 'data_url');
	    
	          pictures.then(() => {
	            this.picture = this.firebaseStorage.ref('pictures/' + currentPictureId + '.jpg').getDownloadURL();
	    
	            this.picture.subscribe((pictureUrl) => {
	              console.log(pictureUrl);
	    
	              const message = {
	                uid: this.conversationId,
	                timestamp: Date.now(),
	                text: null,
	                sender: this.user.uid,
	                receiver: this.friendUser.uid,
	                url: pictureUrl,
	                type: 'image'
	              };
	    
	              this.conversationService.createConversation(message).then(() => this.textMessage = '')
	                .then(() => console.log('conversacion creada correctamente'))
	                .catch(() => console.log('error creando conversaciom'));
	    
	            }).then(() => console.log('foto en conversacion enviada correctamente')).catch(() => console.log('error subiendo foto'));
	    
	          }).catch(()=>{
	            console.log('error obteniendo url. ');
	          });
	    
	        }
	      }
	    }
	    
	    
	```

* **caprilespe** (1) [809280](https://platzi.com/comentario/809280/) 

	Envió resultado del reto
	
	conversation.service.ts
	``` 
	      sendImage(image:string,conversationId:string){
	        returnthis.angularFireDatabase.object('/conversations/'+conversationId+'/image').set(image);
	      }
	    
	    
	```
	
	conversation.component.ts
	``` 
	    import { Component, OnInit } from '@angular/core';
	    import { ActivatedRoute } from '@angular/router';
	    import { IUser } from '../interfaces/IUser';
	    import { UserService } from '../services/user.service';
	    import { ConversationService } from '../services/conversation.service';
	    import { AuthenticationService } from '../services/authentication.service';
	    import { MessageType } from '../enum/messageTypeEnum';
	    import { ImageCroppedEvent } from 'ngx-image-cropper';
	    import { AngularFireStorage } from '@angular/fire/storage';
	    
	    @Component({
	      selector: 'app-conversation',
	      templateUrl: './conversation.component.html',
	      styleUrls: ['./conversation.component.scss']
	    })
	    export class ConversationComponent implements OnInit {
	      public friendId: any;
	    
	      public friend: IUser;
	    
	      public user:IUser;
	    
	      public conversationId:string;
	    
	      public textMessage:string;
	    
	      public conversations:any = [];
	    
	      public shake:boolean = false;
	    
	      public imageChangedEvent: any = '';
	      public croppedImage: any = '';
	      public picture:any;
	      public showCropper:boolean = true;
	      public showSendImage:boolean = false;
	    
	      constructor(private activatedRoute: ActivatedRoute, private userService: UserService, private conversationService:ConversationService, private authenticationService:AuthenticationService, private firebaseStorage: AngularFireStorage) {
	        this.friendId = this.activatedRoute.snapshot.params['uid'];
	        console.log(this.friendId);
	    
	        this.authenticationService.getStatus().subscribe((session)=>{
	          this.userService.getUserById(session.uid).valueChanges().subscribe((user:IUser)=>{
	            this.user = user;
	            this.userService.getUserById(this.friendId).valueChanges().subscribe((data: IUser) => {
	              console.log(data);
	              this.friend = data;
	              const ids = [this.user.uid,this.friend.uid].sort();
	              this.conversationId = ids.join('|');
	              this.getConversations();
	            }, (error) => {
	              console.log(error);
	            });
	          },(error)=>{
	            console.log(error);
	          });
	        });
	      }
	    
	      ngOnInit() {
	      }
	    
	      sendMessage(){
	        const message = {
	          uid:this.conversationId,
	          timestamp: Date.now(),
	          text: this.textMessage,
	          sender: this.user.uid,
	          receiver: this.friend.uid,
	          type: MessageType.Text
	        };
	        this.conversationService.createConversation(message).then(()=>{
	          this.textMessage = '';
	        });
	      }
	    
	      sendImage(p, conversationId){
	        this.showCropper = true;
	        this.showSendImage = false;
	        const message = {
	          uid:conversationId,
	          timestamp: Date.now(),
	          text: null,
	          urlImage:p,
	          sender: this.user.uid,
	          receiver: this.friend.uid,
	          type: MessageType.Image
	        };
	        this.conversationService.sendImage(p, conversationId).then(()=>{
	              this.conversationService.createConversation(message).then(()=>{
	              });
	        }).catch((error)=>{
	          alert("Hubo un error al tratar de subir la imagen.");
	          console.log(error);
	        });
	      }
	    
	      sendZumbido(){
	        const message = {
	          uid:this.conversationId,
	          timestamp: Date.now(),
	          text: null,
	          sender: this.user.uid,
	          receiver: this.friend.uid,
	          type: MessageType.Zumbido
	        };
	        this.conversationService.createConversation(message).then(()=>{
	        });
	    
	        this.doZumbido();
	      }
	    
	      doZumbido(){
	        const audio = new Audio('assets/sound/zumbido.m4a');
	        audio.play();
	        this.shake = true;
	    
	        window.setTimeout(()=>{
	          this.shake = false;
	        }, 1000);
	      }
	    
	      saveSettings() {
	        if (this.croppedImage) {
	          const currentPictureId = Date.now();
	          const pictures = this.firebaseStorage.ref('pictures/'+currentPictureId+'.jpg').putString(this.croppedImage,'data_url');
	    
	          pictures.then((data)=>{
	            this.picture = this.firebaseStorage.ref("pictures/"+currentPictureId+'.jpg').getDownloadURL();
	            this.picture.subscribe((p)=>{
	             this.sendImage(p,this.conversationId);
	            });
	          }).catch((error)=>{
	            console.log(error);
	          });
	        }
	        else {
	          this.userService.editUser(this.user).then(() => {
	            alert("Cambios Guardados");
	          }).catch((error) => {
	            alert("Hubo un error");
	            console.log(error);
	          });
	        }
	    
	      }
	    
	    
	    
	      getConversations(){
	        this.conversationService.getConversation(this.conversationId).valueChanges().subscribe((data)=>{
	          this.conversations = data;
	          this.conversations.forEach((message) => {
	            if(!message.seen){
	              message.seen = true;
	              this.conversationService.editConversation(message);
	              if(message.type == MessageType.Text){
	                const audio = new Audio('assets/sound/new_message.m4a');
	                audio.play();
	              }
	              elseif(message.type == MessageType.Zumbido){
	                this.doZumbido();
	              }
	    
	            }
	          });
	          console.log(data);
	        },(error)=>{
	          console.log(error);
	        });
	      }
	    
	      getUserNickById(id){
	        if(id == this.friend.uid){
	          returnthis.friend.nick;
	        }
	        else{
	          returnthis.user.nick;
	        }
	      }
	    
	      fileChangeEvent(event: any): void {
	        this.imageChangedEvent = event;
	      }
	      imageCropped(event: ImageCroppedEvent) {
	        console.log("Cup");
	        this.showCropper = true;
	        this.showSendImage = true;
	        this.croppedImage = event.base64;
	      }
	      imageLoaded() {
	        // show cropper
	      }
	      cropperReady() {
	    
	      }
	      loadImageFailed() {
	        // show message
	      }
	    
	    
	      
	    
	    }
	    
	    
	```
	
	Resultado:
	
	![EnvioDeImagen.PNG](https://static.platzi.com/media/user_upload/EnvioDeImagen-952c2613-5535-46c4-b81a-880a8b186ffd.jpg)

* **WALTER RAUL CANCHAN HERMOZA** (1) [760014](https://platzi.com/comentario/760014/) 

	Reto logrado  
	![platziconversacionimagen.png](https://static.platzi.com/media/user_upload/platziconversacionimagen-71d042f3-169c-4aca-901a-af70c238d3d4.jpg)

* **ma74ny** (1) [703449](https://platzi.com/comentario/703449/) 

	<https://lh3.googleusercontent.com/-QL_716nMins/XWAEADy3aYI/AAAAAAABIvM/AJDVSnuFodEqaZIZdQEDzeaEqbcBUjNJACK8BGAs/s0/2019-08-23.png>

* **cesarcadavid** (1) [582318](https://platzi.com/comentario/582318/) 
	
	![](https://drive.google.com/open?id=1JeJN1lVhJhgc7eO9Uzv9BuURlOdbKKbO)
	
	Ts
	``` 
	      saveImageMenssage() {
	        if (this.croppedImage) {
	          const idImage = Date.now();
	          const savePicture = this.firebaseStore.ref('/picturesConversation/' + idImage + '.jpg').putString(this.croppedImage, 'data_url');
	          savePicture.then(() => {
	            const urlPicture = this.firebaseStore.ref('/picturesConversation/' + idImage + '.jpg').getDownloadURL();
	            urlPicture.subscribe((url) => {
	              this.sendImageConversation(url);
	            });
	          });
	        }
	      }
	    
	      sendImageConversation(url: string) {
	        const message = {
	          uid: this.conversationId,
	          timestamp: Date.now(),
	          text: url,
	          sender: this.user.uid,
	          receiver: this.friend.uid,
	          type: 'image'
	        };
	    
	        this.conversationService.createConversation(message).then(() => {
	          this.croppedImage = null;
	        });
	      }
	    
	    
	```
	
	Modal
	``` 
	    <a (click)="open(content)"class="fas fa-images"></a>
	    
	    <ng-template #contentlet-modal>
	      <divclass="modal-header">
	        <h4class="modal-title"id="modal-basic-title">Subir Imagen</h4>
	        <buttontype="button"class="close"aria-label="Close" (click)="modal.dismiss('Cross click')">
	          <spanaria-hidden="true">&times;</span>
	        </button>
	      </div>
	      <divclass="modal-body">
	        <divclass="row">
	          <divclass="col-md-auto">
	            <labelclass="custom-file-upload mr-5">
	              <inputtype="file" (change)="fileChangeEvent($event)" />
	              Seleccionar Imagen
	            </label>
	    
	            <img [src]="croppedImageTwo || 'assets/img/generic_avatar.png' "class="avatarImage img-fluid" />
	          </div>
	        </div>
	        <divclass="row justify-content-md-center">
	          <divclass="col-md-12">
	            <image-cropper [imageChangedEvent]="imageChangedEvent" [maintainAspectRatio]="true" [aspectRatio]="1 / 1"
	              [resizeToWidth]="128"format="png" (imageCropped)="imageCropped($event)" (imageLoaded)="imageLoaded()"
	              (cropperReady)="cropperReady()" (loadImageFailed)="loadImageFailed()" ></image-cropper>
	          </div>
	        </div>
	      </div>
	      <divclass="modal-footer">
	        <buttontype="button"class="btn btn-primary" (click)="saveImageMenssage(); modal.close('Save click') ">Enviar Imagen</button>
	      </div>
	    </ng-template>
	    
	```

* **veronica oviedo** (1) [577061](https://platzi.com/comentario/577061/) 

	Oigan nose como subir la imagen? me pide la url

	* **aragonesteban (Platzi)** [577061] (1)

		Hola!  
		Puedes arrastrar la imagen hacia el editor para que se cargue y así mismo puedas publicarla 😃

* **dani_valencia** (1) [527430](https://platzi.com/comentario/527430/) 
	
	![Screenshot from 2019-03-05 06-49-27.png](https://static.platzi.com/media/user_upload/Screenshot%20from%202019-03-05%2006-49-27-bc443b28-af8d-4767-8de4-757e67cb01f6.jpg)

* **Ezequiel-Fabbroni** (1) [500609](https://platzi.com/comentario/500609/) 

	Le falta un poco de estilo pero funciona!!!
	
	![Captura de pantalla de 2019-02-04 12:13:38.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20de%202019-02-04%2012%3A13%3A38-826a2181-6c8a-4015-a114-0c7c48135176.jpg)

* **ziker** (1) [469285](https://platzi.com/comentario/469285/) 

	```
	    sendImage(){
	        const currentPictureId = Date.now();
	        const pictures = this.angularFireStorage.ref('pictures/' + currentPictureId + '.jpg').putString(this.croppedImage, 'data_url');
	        pictures.then((result) => {
	          this.picture = this.angularFireStorage.ref('pictures/' + currentPictureId + '.jpg').getDownloadURL();
	          this.picture.subscribe((p) => {
	            const message = {
	              uid: this.conversation_id,
	              timestamp: Date.now(),
	              text: p,
	              sender: this.user.uid,
	              receiver: this.friend.uid,
	              type: 'img'
	            };
	            this.conversationService.createConversation(message).then(() => { });
	            this.croppedImage = '';
	            this.imageChangedEvent = '';
	          });
	        }).catch((error) => {
	          console.log(error);
	        });
	      }
	    
	```

* **ziker** (1) [469282](https://platzi.com/comentario/469282/) 
	
	![Captura de pantalla 2019-01-06 a la\(s\) 21.32.36.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-06%20a%20la%28s%29%2021.32.36-204088da-15f3-4ccc-97a5-c4fe962d3e31.jpg)

* **developerresol1** (1) [454222](https://platzi.com/comentario/454222/) 

	Así me quedo el envio de la imagen.  
	![Screenshot_3.png](https://static.platzi.com/media/user_upload/Screenshot_3-91e3ffab-da2f-48e7-b264-2acd09d685f2.jpg)

* **elmerrodriguez** (1) [443279](https://platzi.com/comentario/443279/) 

	no se si sera la manera correcta pero funciona
	
	![chatimagen.png](https://static.platzi.com/media/user_upload/chatimagen-2b698ade-78ab-4070-978f-639917e9cd84.jpg)
	
	conversation.component.ts
	``` 
	    croppedImage: any = '';
	    picture: any = '';
	    imageChangedEvent: any = '';
	    
	    
	    sendImagen(){
	        if(this.croppedImage){
	          const currentPictureId = Date.now();
	          const picture = this.firebaseStorage.ref('conversation/pictures/' +this.conversation_id+'/'+currentPictureId+'.jpg').putString(this.croppedImage, 'data_url');
	          picture.then( (result) => {
	            this.picture = this.firebaseStorage.ref('conversation/pictures/'+this.conversation_id+'/'+currentPictureId+'.jpg').getDownloadURL();
	            this.picture.subscribe((p) => {
	              const message = {
	                uid: this.conversation_id,
	                timestamp: Date.now(),
	                text: p,
	                sender: this.user.uid,
	                receiver: this.friend.uid,
	                type: 'image'
	              }
	              this.conversationService.createConversation(message).then( () => {});
	            });
	          }).catch( (error) => {
	            console.log(error);
	          });
	        }
	       
	      }
	    
	```
	
	conversation.component.html
	``` 
	    <span *ngIf="m.type=='text'">{{m.text}}</span>
	    <img *ngIf="m.type=='image'" src="{{m.text}}" />
	    
	```

* **Jeffry Davila** (1) [407628](https://platzi.com/comentario/407628/) 
	
	![Captura de pantalla \(52\).png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%2852%29-47f5a5b0-bc90-4b9d-afa9-fcd1ec3b8560.jpg)

* **Jeffry Davila** (1) [407626](https://platzi.com/comentario/407626/) 

	Le agregue un Modal ahora se ve mejor:  
	![Captura de pantalla \(51\).png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%2851%29-99d00ccb-55f8-4491-a88e-63c890fcf0c4.jpg)

* **Jeffry Davila** (1) [404508](https://platzi.com/comentario/404508/) 

	La función getConversation() solo le agregue mas código.
	``` 
	    getConversation() {  this.conversationService.getConversation(this.conversation_id).valueChanges().subscribe((data)=>{
	    this.conversation=data;
	    this.conversation.forEach((message)=>
	    {
	    if(!message.seen)
	    {
	    message.seen=true;
	    this.conversationService.editConversation(message);
	    if(message.type=='text')
	    {
	    const audio=new Audio('assets/sound/new_message.m4a');
	    audio.play();
	    }
	     elseif(message.type=='zumbido')
	    {
	        this.doZumbido();
	    } 
	    elseif(message.type=='imagen')
	    {
	    this.doImagen(message)const audio=new Audio('assets/sound/new_message.m4a');
	    audio.play();
	    this.envio_imagen=false;
	    console.log(this.envio_imagen)
	    }
	    }
	    });
	    console.log(data);
	    },(error)=>{
	    console.log(error);
	    });
	    }
	    
	```

* **Jeffry Davila** (1) [404503](https://platzi.com/comentario/404503/) 

	conversation.component.html
	``` 
	    <divclass="messageGroup" *ngFor="let m of conversation">
	    <b>{{getUserNickById(m.sender)}}</b> dice: <br />
	    <span>{{m.text}}</span>
	    <divclass="imagen_enviada" *ngIf="m.url">
	    <img  [src]="m.url "class="avatarImage img-fluid"alt="">
	    </div>
	    </div> 
	    
	```

* **Jeffry Davila** (1) [404501](https://platzi.com/comentario/404501/) 

	conversartion.service.ts
	``` 
	      setImagen(conversation,imagen)
	      {
	          returnthis.angularFireDatabase.object('conversation/'+conversation.uid+'/'+conversation.timestamp+'/url').set(imagen);
	      }
	    
	```

* **Jeffry Davila** (1) [404497](https://platzi.com/comentario/404497/) 

	conversation.component.ts
	``` 
	     sendImagen()
	      {
	        const message={
	            uid:this.conversation_id,
	            timestamp: Date.now(),
	            text: null,
	            url:null,
	            sender:this.user.uid,
	            receiver:this.friend.uid,
	            type: 'imagen'
	        };
	        this.conversationService.createConversation(message).then(()=>{}); 
	      }
	    
	      doImagen(mensaje)
	      {
	        if(this.croppedImage)
	        {
	               const currentPictureId = Date.now();
	               const picture = this.firebaseStorage.ref('imagenes/'+ currentPictureId + '.jpg').putString(this.croppedImage,'data_url');
	               picture.then((result)=>{
	               this.img_env=this.firebaseStorage.ref('imagenes/'+ currentPictureId + '.jpg').getDownloadURL();
	               this.img_env.subscribe((p)=>{
	               this.conversationService.setImagen(mensaje,p).then(()=>{
	               }).catch((error)=>
	               {
	               console.log(error);
	               });
	               });
	         }).catch((error)=>{
	      console.log(error);
	         });
	      } 
	      }```
	    
	```

	* **ivan_acg** [404497] (1)

		Tengo la consola prendida fuego por tu codigo .

* **Jeffry Davila** (1) [404493](https://platzi.com/comentario/404493/) 
	
	![Captura de pantalla \(40\).png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%2840%29-d3ae5c82-18c4-44b8-9ba8-fa8277203769.jpg)

* **Jeffry Davila** (1) [404492](https://platzi.com/comentario/404492/) 

	Me costo mucho hacerlo pero lo logre…  
	![Captura de pantalla \(39\).png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%2839%29-22918350-ba11-466c-b9b7-e24f599c5214.jpg)

	* **Carlos Alberto García Rosales** [404492] (2)

		lograste ocultar la preview del cortado luego de mandar?

	* **Jeffry Davila** [404492] (1)

		Hola , pues en esa foto que comentaste no se oculta, solo se oculta cuando presionas el seleccionar imagen después que lo hayas mandado, te recomiendo que lo hagas con un modal como el que hice mas abajo, por que una vez que presionas enviar el modal y el preview del cortador se oculta.

# Amigos [2354]

## 0520. Planeación previa para la característica, ¿cómo generaremos las solicitudes [12793](https://platzi.com/clases/1340-angular-avanzado/12793-planeacion-previa-para-la-caracteristica-como-gene/)

### Descripción:


Para implementar la característica de solicitudes de amistad usaremos un par de nodos adicionales en la base de datos de Firebase: friends y requests. El nodo friends formará parte de los atributos propios de cada usuario.

Los usuarios sólo podrán comunicarse entre sí sólo cuando se encuentren relacionados como amigos.

### Comentarios:

* **Alex Eugenio Gavidia Donayre** (1) [553155](https://platzi.com/comentario/553155/) 
Interesante

## 0530. Enviando una solicitud de amistad [12794](https://platzi.com/clases/1340-angular-avanzado/12794-enviando-una-solicitud-de-amistad3345/)

### Descripción:


Esta característica nueva en nuestra app la crearemos a partir de un nuevo servicio que llamaremos requests. Debido a que almacenaremos la dirección de correo de usuarios, y ésta lleva puntos, tendremos que aplicar una transformación del string antes de guardarlo en la base de datos ya que Firebase no tolera el uso de puntos en los valores almacenados, esto es para evitar conflictos con el uso de puntos para indicar propiedades o atributos de objetos.

Cada request tendrá, además de la dirección de correo, un atributo status que podrá tomar los valores de: aceptado, rechazado o pendiente.

Implementaremos Bootstrap (a través de la librería ng-bootstrap) para el manejo de un diálogo de tipo modal para realizar la solicitud de amistades a otros usuarios.

### Links:

* [Angular powered Bootstrap](https://ng-bootstrap.github.io)

### Comentarios:

* **ziker** (3) [469362](https://platzi.com/comentario/469362/) 

	Por si ocupan correos con como “.com.mx”
	``` 
	    const cleanEmail = request.receiver_email.replace(/\./g, ',');
	    
	```

* **Pablo David Sánchez Aguilera** (2) [799602](https://platzi.com/comentario/799602/) 

	Tengo problema en en el NgbModule.forRoot() me marca error y no entiendo porque me pueden ayudar?
	``` 
	    import { BrowserModule } from '@angular/platform-browser';
	    import { NgModule } from '@angular/core';
	    import { FormsModule } from '@angular/forms'
	    import { AppComponent } from './app.component';
	    import { LoginComponent } from './login/login.component';
	    import { HomeComponent } from './home/home.component';
	    import { ConversationComponent } from './conversation/conversation.component';
	    import { ProfileComponent } from './profile/profile.component';
	    import { Routes, RouterModule} from '@angular/router';
	    import { MenuComponent } from './menu/menu.component';
	    import { SearchPipe } from './pipes/search';
	    import { AngularFireModule} from '@angular/fire';
	    import { AngularFirestoreModule } from '@angular/fire/firestore';
	    import { AngularFireStorageModule } from '@angular/fire/storage';
	    import { AngularFireAuthModule } from '@angular/fire/auth';
	    import { AngularFireDatabaseModule } from '@angular/fire/database';
	    import { environment } from 'src/environments/environment';
	    import { AuthenticationGuard } from './services/authentication.guard';
	    import { ImageCropperModule} from 'ngx-image-cropper';
	    import {NgbModule} from '@ng-bootstrap/ng-bootstrap';
	    constappRoutes: Routes = [
	      {path: '', component: HomeComponent},
	      {path: 'home', component: HomeComponent, canActivate: [AuthenticationGuard]},
	      {path: 'login', component: LoginComponent},
	      {path: 'conversation/:uid', component: ConversationComponent},
	      {path: 'profile', component: ProfileComponent, canActivate: [AuthenticationGuard]}
	    ];
	    @NgModule({
	      declarations: [
	        AppComponent,
	        LoginComponent,
	        HomeComponent,
	        ConversationComponent,
	        ProfileComponent,
	        MenuComponent,
	        SearchPipe
	      ],
	      imports: [
	        BrowserModule,
	        RouterModule.forRoot(appRoutes),
	        FormsModule,
	        AngularFireModule.initializeApp(environment.firebase),
	        AngularFirestoreModule,
	        AngularFireAuthModule,
	        AngularFireStorageModule,
	        AngularFireDatabaseModule,
	        ImageCropperModule,
	        NgbModule.forRoot()
	      ],
	      providers: [],
	      bootstrap: [AppComponent]
	    })
	    export class AppModule { }
	    
	```

	* **cristian.arias** [799602] (4)

		Hola, Pablo.
		
		Esto puede deberse a la versión de Angular que esté utilizando, en mi caso, estoy utilizando la versión 8, y para ellos no es necesario adicionar “.forRoot()” en el módulo, solo se adiciona el nombre del módulo en el import:
		
		imports: [  
		BrowserModule,  
		AppRoutingModule,  
		FormsModule,  
		AngularFireModule.initializeApp(environment.firebase),  
		AngularFirestoreModule,  
		AngularFireAuthModule,  
		AngularFireStorageModule,  
		AngularFireDatabaseModule,  
		ImageCropperModule,  
		NgbModule  
		],

	* **Fernando Vallejo** [799602] (1)

		Hola!
		
		Estas utilizando Angular superior o igual a 9.00, instala @angular/localize con el siguiente comando :
		``` 
		    ng add@angular/localize
		    
		```
		
		Si deseas mas detalle, puedes ir a la documentación (<https://angular.io/guide/i18n>)
		
		😃

* **Walter Jaramillo 2019** (2) [647789](https://platzi.com/comentario/647789/) 

	WARNING in ./node_modules/@ng-bootstrap/ng-bootstrap/fesm5/ng-bootstrap.js 10672:163-171  
	"export ‘ɵɵinject’ was not found in ‘@angular/core’
	
	Alguien ha tenido este error, help me!!!  
	Gracias.

	* **Marival** [647789] (1)

		Tengo el mismo problema, ¿pudiste resolver ?

	* **Walter Jaramillo 2019** [647789] (0)

		Si debes cambiar la versión de boostrap, ese problema es de estilos

	* **Wilson Marino Pablo Mendez** [647789] (2)

		Para solocionar el problema se utiliza esta version de boostrap:  
		`npm install --save @ng-bootstrap/ng-bootstrap@3.3.1`

* **Angel Javier Puc Yamá** (2) [625905](https://platzi.com/comentario/625905/) 

	Por que para el request no se creo una interfaz?
	
	Cuando debo crear una interface y cuando debo usar solo una constante?

* **Walter Lensinas** (2) [572935](https://platzi.com/comentario/572935/) 

	Buenas noches, dejo el código de las clase en este branch: 53-solicitud
	
	Para ver el [código](https://github.com/wlensinas/platzinger-wl/tree/53-solicitud).
	
	Para probar el código de esta clase:
	
	  1. `git clone https://github.com/wlensinas/platzinger-wl.git`
	  2. `git checkout 53-solicitud`
	  3. `npm install`
	  4. Agregar el objeto firebase en environment con tu config:
	
	
	``` 
	    exportconst environment = {
	      production: false,
	      firebase: {
	      	apiKey: "",
	        authDomain: "",
	        databaseURL: "",
	        projectId: "",
	        storageBucket: "",
	        messagingSenderId: ""
	      }
	    };
	    
	```
	
	  1. `ng serve --open`
	
	
	
	Saludos.

* **JerezA** (1) [923123](https://platzi.com/comentario/923123/) 

	Por si alguien tiene un error con los providers, me toco agregar 3 para poder hacer correr el modal y bueno, una funcion de scrollbar que utilice para el autoscroll de la conversacion. Ahi se las dejo
	``` 
	    import { NgbModule, NgbModal } from '@ng-bootstrap/ng-bootstrap';
	    import { NgbModalStack } from '@ng-bootstrap/ng-bootstrap/modal/modal-stack';
	    import { ScrollBar } from '@ng-bootstrap/ng-bootstrap/util/scrollbar';
	    ...
	    
	    providers: [NgbModal, NgbModalStack, ScrollBar],
	    
	```

* **Jose Alejandro  Gonzalez Rondon** (1) [652781](https://platzi.com/comentario/652781/) 

	Como se puede enviar un email automatico al usuariio al cual se esta agragando para notificarle que se le a enviado una notificacion?

	* **Manuel Angel Garcia Manzano** [652781] (1)

		Node tiene un modulo para enviar correos por medio de firebase pero la verdad no sé mucho de como hacerlo acá te dejo el github <https://github.com/nodemailer/nodemailer>

* **Luis Angel Ramos Bañuelos** (1) [642179](https://platzi.com/comentario/642179/) 

	si olvide poner las banderas de --save y -exact como las activo despues?

	* **juanbarcinilla** [642179] (1)

		hay que reinstalar la librería y le colocas las banderas. O vas a la carpeta node_module identifica la librerías la eliminas y la vuelves a instalar con las banderas.

* **eemartinez97** (1) [594140](https://platzi.com/comentario/594140/) 

	Cual es el objetivo de la ‘,’ en el correo electrónico?

* **Alfonso Adame Rueda** (1) [552661](https://platzi.com/comentario/552661/) 

	hola buenas tardes  
	nada que me responde nadie al error que me sale :  
	TypeError: Cannot read property ‘uid’ of null

	* **Alex Eugenio Gavidia Donayre** [552661] (1)
No existe el uid o bien Le estás enviando sin valor, verifica, eso compa

	* **Alfonso Adame Rueda** [552661] (2)

		hola buenos días ya lo hice ,por favor mira en el vídeo anterior a este que en este muestro mi código, muchas gracias por responder.

	* **Alex Eugenio Gavidia Donayre** [552661] (1)

		De nada.

* **ivan_acg** (1) [440258](https://platzi.com/comentario/440258/) 

	Consejo para que no le pase lo que me paso ; se que suena tonto pero asegurense que cuando manden una solicitud , si lo quieren testear , mandeselos uds mismos :v . Duré 3 dias enviando mails esperando que me saltara el Modal y resulta que no se me paso por la cabeza enviarmelo a mi mismo :v

	* **Jecsham Castillo** [440258] (1)

		Jajaja

	* **Alex Eugenio Gavidia Donayre** [440258] (1)
Suele pasar

* **Mauricio Quiñones** (1) [76247](https://platzi.com/comentario/883722/) 
Buena tarde, como puedo integrar payU con angular?

	* **MauricioF** [76247] (1)

		Hola Mauricio, [aquí ](http://developers.payulatam.com/en/web_checkout/integration.html)puedes ver mas información sobre como hacer la integración. Esencialmente es a través de un formulario.

* **eemartinez97** (1) [59662](https://platzi.com/comentario/594140/) 
Cual es el objetivo de la ‘,’ en el correo electrónico?

* **Alfonso Adame Rueda** (1) [56440](https://platzi.com/comentario/552661/) 
hola buenas tardes nada que me responde nadie al error que me sale : TypeError: Cannot read property ‘uid’ of null

	* **Alex Eugenio Gavidia Donayre** [56440] (1)
No existe el uid o bien Le estás enviando sin valor, verifica, eso compa

* **DanielCM** (0) [785960](https://platzi.com/comentario/785960/) 

	cuando utiizas ngmodel, es con la finalidad de hacer un selector a nivel global del proyecto??

## 0540. Generando el modal de solicitud de amistad [12795](https://platzi.com/clases/1340-angular-avanzado/12795-generando-el-modal-de-solicitud-de-amistad/)

### Descripción:


Para implementar el modal de solicitud de amistad, usaremos una nueva librería llamada ng2-boostrap-modal.

Importaremos el módulo BoostrapModalModule en el app.component.ts con forRoot() y no en el componente específico de conversation para que el modal pueda ser mostrado en cualquier pantalla de la app en la que estemos y no sólo durante una conversación.

Crearemos un nuevo componente para esta ventana modal utilizando el Angular CLI: `ng generate component modals/request`, este componente extiende funcionalidades de DialogComponent e implementa PromptModel, que es una _interface_ que tendremos que definir.

Finalmente creamos un nuevo método en el userService llamado _addFriend()_ que insertará en el registro de cada usuario, el user.uid de cada cual, para establecer la relación de amistad entre ellos.

### Links:

* [https://npmjs.com/package/ng2-bootstrap-modal](https://npmjs.com/package/ng2-bootstrap-modal)

### Comentarios:

* **Víctor Manuel Servín Carrillo** (4) [478818](https://platzi.com/comentario/478818/) 

	Si alguien tomó como reto personal hacer su propio estilo y no tanto el de MSN messenger, también es buena idea realizar una especie de notificaciones en la barra de navegación, les paso el código del mío. (Usando [bulma.io](https://bulma.io).
	
	Diseño
	
	![Imagen](https://i.gyazo.com/1a6703ff7a513e6d48d6bc41866d5222.png)
	
	menu.component.ts
	``` 
	    getFriendRequests(){
	    		this.requestsService.getRequestsForEmail(this.currentUser.email).valueChanges()
	    		.subscribe( (requests: Request[]) => {
	    			// Ordenar por status
	    			this.requests = requests
	    			.sort( (requestA, requestB) => requestA.status == 'accepted' ? -1 : 1)
	    			.sort( (requestA, requestB) => requestA.status == 'rejected' ? -1 : 1)
	    			.sort( (requestA, requestB) => requestA.status == 'seen' ? -1 : 1)
	    			.sort( (requestA, requestB) => requestA.status == 'pending' ? -1 : 1);
	    			// Arreglo de únicamente las solicitudes nuevas
	    			this.newRequests = this.requests.filter( request => request.status == 'pending');
	    			this.requests.forEach( (request:Request) => {
	    				this.userService.getUserById(request.sender_uid).valueChanges()
	    				.subscribe( (user:User) => {
	    					request.sender = user;
	    				}, error => {
	    					console.log("Error while getting requests");
	    				});
	    			})
	    		});
	    	}
	    	statusChange(status: requestStatus, request: Request = null){
	    		this.requestsService.setRequestStatus(status, request);
	    	}
	    
	```
	
	menu.component.html
	``` 
	    <navclass="navbar is-dark"role="navigation"aria-label="main navigation">
	    	<divclass="navbar-brand">
	    		<aclass="navbar-item"routerLink="/">
	    			<imgsrc="assets/img/logo_live.png"alt="Logo de Platzinger">
	    			<h1class="is-size-5"> Platzinger</h1>
	    		</a>
	    		<arole="button" [ngClass]="{'is-active': mobileNavFlag}"class="navbar-burger burger"aria-label="menu"aria-expanded="false"data-target="navbarElement" (click)="mobileNavFlag = !mobileNavFlag">
	    			<spanaria-hidden="true"></span>
	    			<spanaria-hidden="true"></span>
	    			<spanaria-hidden="true"></span>
	    		</a>
	    	</div>
	    	
	    	<divid="navbarElement" [ngClass]="{'is-active': mobileNavFlag}"class="navbar-menu">
	    		
	    		<divclass="navbar-start">
	    			<aclass="navbar-item"routerLink="/home"routerLinkActive="is-active">Home</a>
	    			<aclass="navbar-item"routerLink="/profile"routerLinkActive="is-active">My Profile</a>
	    		</div>
	    		
	    		<divclass="navbar-end">
	    			
	    			<divclass="navbar-item has-dropdown" [ngClass]="{'is-active': requestsFlag}">
	    				<aclass="navbar-link" (click)="requestsFlag = !requestsFlag">
	    					<spanclass="icon"><iclass="fas fa-user-friends"></i></span><span>New requests</span>
	    					<spanclass="ml-1 tag is-danger is-normal" *ngIf="newRequests && newRequests.length > 0">{{newRequests.length}}</span>
	    				</a>
	    				<divclass="navbar-dropdown is-right">
	    					<ng-container *ngFor="let request of requests">
	    						<aclass="navbar-item" *ngIf="request.sender">
	    							<figureclass="image is-inline-block is-24x24"><imgclass="user-status is-rounded" [src]="request.sender.avatar || 'assets/img/generic_avatar.png'"alt="Avatar"/></figure>
	    							<spanclass="subtitle is-5 mb-0 ml-2 mr-4" [ngClass]="{'has-text-primary': request.status == 'pending'}">{{request.sender.nick | lowercase | titlecase}}</span>
	    							<divclass="buttons has-addons"style="flex-wrap: nowrap;" *ngIf="['pending', 'seen'].includes(request.status) ">
	    								<spanclass="button is-primary" (click)="statusChange('seen', request)" *ngIf="request.status == 'pending'">Seen</span>
	    								<spanclass="button is-success" (click)="statusChange('accepted', request)">Accept</span>
	    								<spanclass="button is-danger" (click)="statusChange('rejected', request)">Reject</span>
	    							</div>
	    							<divclass="notification is-success px-3 py-1" *ngIf="request.status == 'accepted'">Accepted</div>
	    							<divclass="notification is-danger px-3 py-1" *ngIf="request.status == 'rejected'">Rejected</div>
	    						</a>
	    						<divclass="has-text-centered has-text-grey" *ngIf="request.message">{{request.message}}</div>
	    						<hrclass="navbar-divider my-4">
	    					</ng-container>
	    					<aclass="navbar-item" *ngIf="requests && requests.length == 0">
	    						<divclass="notification is-info px-3 py-1">No requests yet, try to socialize more :)</div>
	    					</a>
	    					<ng-container *ngIf="(newRequests && newRequests.length > 0)">
	    						<divclass="buttons has-addons is-centered mb-4"style="flex-wrap: nowrap;">
	    							<spanclass="button is-primary" (click)="statusChange('seen')">See all</span>
	    							<spanclass="button is-success" (click)="statusChange('accepted')">Accept all</span>
	    							<spanclass="button is-danger" (click)="statusChange('rejected')">Reject all</span>
	    						</div>
	    					</ng-container>
	    				</div>			
	    			</div>
	    			<divclass="navbar-item">
	    				<divclass="buttons">
	    					<aclass="button is-primary" (click)="logout()">Logout</a>
	    				</div>
	    			</div>
	    		</div>
	    		
	    	</div>
	    </nav>
	    
	```
	
	requests.service.ts
	``` 
	    // Si el request es nulo, se asume que se intenta cambiar el status de todos los requests
	    	setRequestStatus(status: requestStatus, request: Request = null){
	    		if(request){
	    			const cleanEmail = request.receiver_email.replace(/\./g, ',');
	    			request.status = status;
	    			returnthis.angularFireDB.object('requests/'+cleanEmail+'/'+request.sender_uid).set(request);
	    		}	else {
	    			this.authService.getStatus().subscribe( authStatus => {
	    				this.userService.getUserById(authStatus.uid).valueChanges().subscribe( (user:User) => {
	    					this.getRequestsForEmail(user.email).valueChanges().subscribe( (requests: Request[]) => {
	    						requests.filter( (request: Request) => ['pending', 'seen'].includes(request.status)).forEach( (request: Request) => {
	    							// Recursive con c/u de los requests
	    							returnthis.setRequestStatus(status, request);
	    						});
	    					}, error => {
	    						console.log("Error while getting given requests", error);
	    					});
	    				}, error => {
	    					console.log("Error while getting user", error);
	    				});
	    			});
	    		}
	    	}```
	    
	    
	```

* **sandovalgus** (2) [485469](https://platzi.com/comentario/485469/) 

	Buenas, en el curso de Angular explica mas detallado cuando usar subscribe y then?

	* **waldoaraque** [485469] (1)

		En Angular (actualmente en Angular-6) .subscribe () es un método en el tipo Observable. El tipo Observable es una utilidad que transmite datos de forma asíncrona o síncrona a una variedad de componentes o servicios que se han suscrito al observable.
		
		Lo observable es una implementación / abstracción a lo largo de la cadena de promesas y formará parte de ES7 como una característica propuesta y muy compatible. En Angular se usa internamente debido a que rxjs es una dependencia del desarrollo.
		
		Un observable en sí mismo puede considerarse como un flujo de datos provenientes de una fuente. En Angular, esta fuente es un punto final de API, un servicio, una base de datos u otro observable. Pero el poder que tiene es que no está esperando una respuesta única. Puede tener uno o varios valores que se devuelven.

	* **waldoaraque** [485469] (1)

		<https://blog.fullstacktraining.com/angular-promise-vs-observable/>

	* **waldoaraque** [485469] (1)

		then() lo puedes usar para resolver Promisas y subscribe() para ejecutar acciones en un Observable… De igual forma tienen sus casos de uso…

* **Daniel Perez Nuñez** (1) [1071298](https://platzi.com/comentario/1071298/) 
	
	![error.PNG](https://static.platzi.com/media/user_upload/error-e79d0dbd-c0d7-4952-807a-716fa2245ca8.jpg)
	
	Alguien me puede ayudar con este error?, actualmente estoy trabajando con la versión 9.0.7 de angular

* **Jessie Buckland Pérez** (1) [916541](https://platzi.com/comentario/916541/) 

	Interesante el método .forRoot, vestigando un poco mas sobre el tema me fije que existe tambien en código relativo a rutas, en el modulo de routes.d.ts:
	``` 
	    export declareclassRouterModule{
	        constructor(guard: any, router: Router);
	        /**
	       * Creates and configures a module with all the router providers and directives.
	       * Optionally sets up an application listener to perform an initial navigation.
	         *
	       * @param routes An array of `Route` objects that define the navigation paths for the application.
	       * @param config An `ExtraOptions` configuration object that controls how navigation is performed.
	       * @return The new router module.
	        */
	        static forRoot(routes: Routes, config?: ExtraOptions): ModuleWithProviders<RouterModule>;
	        /**
	       * Creates a module with all the router directives and a provider registering routes.
	         */
	        static forChild(routes: Routes): ModuleWithProviders<RouterModule>;
	    }```
	    
	```

* **Walter Lensinas** (1) [578833](https://platzi.com/comentario/578833/) 

	Buenas, dejo el repo donde voy subiendo las clases: [código](https://github.com/wlensinas/platzinger-wl/tree/54-solicitud-amistad).
	
	Para probar el código de esta clase:
	
	  1. `git clone https://github.com/wlensinas/platzinger-wl.git`
	  2. `git checkout 54-solicitud-amistad`
	  3. `npm install`
	  4. Agregar el objeto firebase en environment con tu config:
	
	
	``` 
	    exportconst environment = {
	      production: false,
	      firebase: {
	      	apiKey: "",
	        authDomain: "",
	        databaseURL: "",
	        projectId: "",
	        storageBucket: "",
	        messagingSenderId: ""
	      }
	    };
	    
	```
	
	  1. `ng serve --open`
	
	
	
	Saludos.

* **Alex Eugenio Gavidia Donayre** (1) [553291](https://platzi.com/comentario/553291/) 
En cada video enseña algo nuevo. Aunque parezca repetitivo

* **Alex Eugenio Gavidia Donayre** (1) [553289](https://platzi.com/comentario/553289/) 
Gracias

* **Cristian David Franco Garcia** (1) [468282](https://platzi.com/comentario/468282/) 

	ng generate component modals/request

* **manuelpucci** (1) [449867](https://platzi.com/comentario/449867/) 

	Como puedo acceder al dom desde angular es buena practica utilizar document.getElementById de toda la vida???.

	* **Jecsham Castillo** [449867] (1)

		En el .html  
		`<button #elemento (click)="domElement(elemento)" class="btn btn-succes btn-sm">Click</button>`  
		En el .ts  
		`domElement(element){ console.log(element) }`

	* **manuelpucci** [449867] (1)

		Muchas gracias Jecsham y para referenciar una variable en en .TS al elemento HTML.

* **DESTRUN** (1) [424468](https://platzi.com/comentario/424468/) 

	Al parecer soy el unico que ha llegado hasta acá

	* **Alexander Sandoval** [424468] (1)

		No.

	* **ivan_acg** [424468] (1)

		Nopiti nop :v

* **manuelpucci** (1) [48003](https://platzi.com/comentario/449867/) 
Como puedo acceder al dom desde angular es buena practica utilizar document.getElementById de toda la vida???.

	* **Jecsham Castillo** [48003] (1)

		En el .html  
		`<button #elemento (click)="domElement(elemento)" class="btn btn-succes btn-sm">Click</button>`  
		En el .ts  
		`domElement(element){ console.log(element) }`

## 0550. Aceptando solicitudes de amistad [12796](https://platzi.com/clases/1340-angular-avanzado/12796-aceptando-solicitudes-de-amistad7768/)

### Descripción:


Las solicitudes de amistad que ha recibido el usuario se obtendrán de la base de datos usando la dirección de correo del usuario actual. Se extraerán los registros del nodo requests y serán guardados localmente en un arreglo; luego, recorriendo este arreglo, se mostrará en el modal la lista de solicitudes pendientes, así el usuario pueda tomar la decisión de aceptarlas, rechazarlas o postergarlas. Para ello usaremos el componente que creamos en la clase anterior: requestsComponent.

El estatus actualizado se guardará de nuevo en la base de datos.

### Comentarios:

* **Juan Diego Lopez Triana** (4) [376199](https://platzi.com/comentario/376199/) 

	Para solucionar el reto primero hice que la clase del request.component.ts volviera a implementar OnInit y luego en el metodo ngOnInit() recuperar los datos del usuario que envió la solicitud: ![1.PNG](https://static.platzi.com/media/user_upload/1-8fa6ba3c-f288-4b1b-b6ab-336ec83322d9.jpg)
	
	![2.PNG](https://static.platzi.com/media/user_upload/2-55c733be-edd8-4663-8252-08a93fd5d2a1.jpg)

	* **Juan Carlos Felizzola Vega** [376199] (1)

		¡Muy bien!

	* **ivan_acg** [376199] (0)

		Intenté usar tu codigo pero no me sirvió .

	* **Rafael Andrés Cisneros Corro** [376199] (1)

		Buena solucion. Yo intente hacer lo mismo en el constructor pero me encontraba con currentRequest = undefined

* **David Alejandro Mosquera Moreno** (1) [879006](https://platzi.com/comentario/879006/) 

	El modal de nueva solicitud no se me activa y no entiendo por qué  
	.  
	Y veo que el campo de receiver_email está vacío  
	.  
	![](![requests.png](https://static.platzi.com/media/user_upload/requests-f49b54dd-4de7-4197-ad19-c6dfe9d78c52.jpg)  
	.  
	Dejo mi código por si alguien me puede ayudar con este error.  
	.  
	home.component.ts  
	.
	``` 
	    import { Component, OnInit } from "@angular/core";
	    import { User } from "../interfaces/user";
	    import { UserService } from "../services/user.service";
	    import { AuthenticationService } from "../services/authentication.service";
	    import { Router } from "@angular/router";
	    import { NgbModal } from "@ng-bootstrap/ng-bootstrap";
	    import { RequestService } from "../services/request.service";
	    
	    @Component({
	      selector: "app-home",
	      templateUrl: "./home.component.html",
	      styleUrls: ["./home.component.css"]
	    })
	    export class HomeComponent implements OnInit {
	      friends: User[];
	      query: string = "";
	      friendEmail: string = "";
	      user: User;
	    
	      constructor(
	        private userService: UserService,
	        private authenticactionService: AuthenticationService,
	        private router: Router,
	        private modalService: NgbModal,
	        private requestService: RequestService
	      ) {
	        this.userService
	          .getUsers()
	          .valueChanges()
	          .subscribe(
	            (data: User[]) => {
	              this.friends = data;
	            },
	            error => {
	              console.log(error);
	            }
	          );
	        this.authenticactionService.getStatus().subscribe(status => {
	          this.userService
	            .getUserById(status.uid)
	            .valueChanges()
	            .subscribe((data: User) => {
	              this.user = data;
	              console.log(data);
	              console.log(data.email);
	            });
	        });
	      }
	    
	      ngOnInit() {}
	    
	      logout() {
	        this.authenticactionService
	          .logOut()
	          .then(() => {
	            alert("Successfully logged out");
	            this.router.navigate(["login"]);
	          })
	          .catch(error => {
	            console.log(error);
	          });
	      }
	    
	      open(content: any) {
	        this.modalService
	          .open(content, { ariaLabelledBy: "modal-basic-title" })
	          .result.then(
	            result => {},
	            reason => {}
	          );
	      }
	    
	      sendRequest() {
	        const request = {
	          timestap: Date.now(),
	          receiver_email: this.friendEmail,
	          sender: this.user.uid,
	          status: "pending"
	        };
	    
	        this.requestService
	          .createRequest(request)
	          .then(() => {
	            alert("Request Sent");
	          })
	          .catch(error => {
	            alert("Something bad happened");
	            console.log(error);
	          });
	      }
	    }
	    
	    
	```
	
	user.service.ts
	``` 
	    import { Injectable } from"@angular/core";
	    import { AngularFireDatabase } from"@angular/fire/database";
	    
	    @Injectable({
	      providedIn: "root"
	    })
	    export classUserService {
	      // friends: User[];
	    
	      constructor(private angularFireDatabase: AngularFireDatabase) {}
	      
	      getUsers() {
	        returnthis.angularFireDatabase.list("/users");
	      }
	    
	      getUserById(uid) {
	        returnthis.angularFireDatabase.object("/users/" + uid);
	      }
	    
	      createUser(user) {
	        returnthis.angularFireDatabase.object("/users/" + user.uid).set(user);
	      }
	    
	      editUser(user) {
	        returnthis.angularFireDatabase.object("/users/" + user.uid).set(user);
	      }
	    
	      setAvatar(avatar, uid) {
	        returnthis.angularFireDatabase
	          .object("/users/" + uid + "/avatar")
	          .set(avatar);
	      }
	    
	      addFriend(userId: unknown, friendId: unknown) {
	        this.angularFireDatabase
	          .object("users/" + userId + "/friends/" + friendId)
	          .set(friendId);
	        returnthis.angularFireDatabase
	          .object("users/" + friendId + "/friends/" + userId)
	          .set(userId);
	      }```
	    
	    request.component.ts
	    
	    
	```
	
	import { Component } from “@angular/core”;  
	import { DialogComponent, DialogService } from “ng2-bootstrap-modal”;  
	import { UserService } from “src/app/services/user.service”;  
	import { RequestService } from “src/app/services/request.service”;
	
	export interface PromptModel {  
	scope: any;  
	currentRequest: any;  
	}
	
	@Component({  
	selector: “app-request”,  
	templateUrl: “./request.component.html”,  
	styleUrls: ["./request.component.css"]  
	})  
	export class RequestComponent extends DialogComponent<PromptModel, any>  
	implements PromptModel {  
	scope: any;  
	shouldAdd: string = “yes”;  
	currentRequest: any;
	
	constructor(  
	public dialogService: DialogService,  
	private userService: UserService,  
	private resquestService: RequestService  
	) {  
	super(dialogService);  
	}
	
	accept() {  
	if (this.shouldAdd == “yes”) {  
	this.resquestService  
	.setRequestStatus(this.currentRequest, “accepted”)  
	.then(data => {  
	console.log(data);  
	this.userService  
	.addFriend(this.scope.user.uid, this.currentRequest.sender)  
	.then(() => {  
	alert(“Request successfully accepted!”);  
	});  
	})  
	.catch(error => {  
	console.log(error);  
	});  
	} else if (this.shouldAdd == “no”) {  
	this.resquestService  
	.setRequestStatus(this.currentRequest, “rejected”)  
	.then(data => {  
	console.log(data);  
	})  
	.catch(error => {  
	console.log(error);  
	});  
	} else if (this.shouldAdd == “later”) {  
	this.resquestService  
	.setRequestStatus(this.currentRequest, “pending”)  
	.then(data => {  
	console.log(data);  
	})  
	.catch(error => {  
	console.log(error);  
	});  
	}  
	}  
	}
	``` 
	    request.service.ts
	    
	    
	    
	```
	
	import { Injectable } from “@angular/core”;  
	import { AngularFireDatabase } from “@angular/fire/database”;
	
	@Injectable({  
	providedIn: “root”  
	})  
	export class RequestService {  
	constructor(private angularFireDatabase: AngularFireDatabase) {}
	
	createRequest(request) {  
	const cleanEmail = request.receiver_email.replace(".", “,”);  
	return this.angularFireDatabase  
	.object(“requests/” + cleanEmail + “/” + request.sender)  
	.set(request);  
	}
	
	setRequestStatus(request, status) {  
	const cleanEmail = request.receiver_email.replace(".", “,”);  
	return this.angularFireDatabase  
	.object(“requests/” + cleanEmail + “/” + request.sender + “/status”)  
	.set(status);  
	}
	
	getResquestForEmail(email: string) {  
	const cleanEmail = email.replace(".", “,”);  
	return this.angularFireDatabase.list(“requests/” + cleanEmail);  
	}  
	}
	```
	```
	

	* **Jessie Buckland Pérez** [879006] (1)

		Podrias publicar tu app.modules.ts?

	* **David Alejandro Mosquera Moreno** [879006] (1)

		Mira  
		.
		``` 
		    import { BrowserModule } from "@angular/platform-browser";
		    import { NgModule } from "@angular/core";
		    
		    import { AppComponent } from "./app.component";
		    import { LoginComponent } from "./login/login.component";
		    import { HomeComponent } from "./home/home.component";
		    import { ConversationComponent } from "./conversation/conversation.component";
		    import { ProfileComponent } from "./profile/profile.component";
		    import { Routes, RouterModule } from "@angular/router";
		    import { MenuComponent } from "./menu/menu.component";
		    import { SearchPipe } from "./pipes/search";
		    import { FormsModule } from "@angular/forms";
		    import { AngularFireModule } from "@angular/fire";
		    import { AngularFireStorageModule } from "@angular/fire/storage";
		    import { AngularFirestoreModule } from "@angular/fire/firestore";
		    import { AngularFireAuthModule } from "@angular/fire/auth";
		    import { AngularFireDatabaseModule } from "@angular/fire/database";
		    import { environment } from "../environments/environment";
		    import { AuthenticationGuard } from "./services/authentication.guard";
		    import { ImageCropperModule } from "ngx-image-cropper";
		    import { NgbModule } from "@ng-bootstrap/ng-bootstrap";
		    import { BootstrapModalModule } from "ng2-bootstrap-modal";
		    import { RequestComponent } from './modals/request/request.component';
		    import { ContactComponent } from './contact/contact.component';
		    
		    constappRoutes: Routes = [
		      { path: "", component: HomeComponent },
		      {
		        path: "home",
		        component: HomeComponent,
		        canActivate: [AuthenticationGuard]
		      },
		      { path: "login", component: LoginComponent },
		      { path: "conversation/:uid", component: ConversationComponent },
		      {
		        path: "profile",
		        component: ProfileComponent,
		        canActivate: [AuthenticationGuard]
		      }
		    ];
		    
		    @NgModule({
		      declarations: [
		        AppComponent,
		        LoginComponent,
		        HomeComponent,
		        ConversationComponent,
		        ProfileComponent,
		        MenuComponent,
		        SearchPipe,
		        RequestComponent,
		        ContactComponent
		      ],
		      imports: [
		        BrowserModule,
		        RouterModule.forRoot(appRoutes),
		        FormsModule,
		        AngularFireModule.initializeApp(environment.firebase),
		        AngularFirestoreModule, // imports firebase/firestore, only needed for database features
		        AngularFireAuthModule, // imports firebase/auth, only needed for auth features,
		        AngularFireStorageModule,
		        AngularFireDatabaseModule,
		        ImageCropperModule,
		        NgbModule,
		        BootstrapModalModule.forRoot({container: document.body})
		      ],
		      providers: [],
		      bootstrap: [AppComponent],
		      entryComponents: [RequestComponent]
		    })
		    export class AppModule {}
		    
		```

	* **Jessie Buckland Pérez** [879006] (1)

		que raro, pensé que seria algún módulo no importado del modal o algo así, has probado a hacer debug de todo el proceso de llamada a la función que muestra el modal y si has incluido esa accion en el html?? Lo revisaré bien y si veo algo te contesto ok?? Un saludo y ánimo, el curso esta genial verdad??

	* **David Alejandro Mosquera Moreno** [879006] (1)

		Si he hecho algunas pruebas de esa función del modal pero no sé que puede ser… porque sí la incluí en el HTML.
		
		Muchas gracias. Si logras encontrar el error me ayudarías demasiado… igual seguiré buscando jaja
		
		Y es cierto, este curso es uno de los mejores que hay por aquí

* **caprilespe** (1) [823347](https://platzi.com/comentario/823347/) 

	Reto
	
	request.component.html
	``` 
	    <divclass="modal-dialog modal-lg">
	        <divclass="modal-content">
	            <divclass="modal-header">
	                Nueva Solicitud
	                <ahref=""class="closeButton" (click)="close()">x</a>
	            </div>
	            <divclass="modal-body"style="height:auto;" *ngIf="friendRequest">
	                <divclass="row">
	                    <divclass="col-md-3">
	                        <img [src]="friendRequest.avatar || 'assets/img/generic_avatar.png'"alt=""class="img-fluid" />
	                    </div>
	                    <divclass="col-md-9">
	                        <b>{{friendRequest.nick}}</b>
	                        <small>Te ha enviado esta solicitud</small>
	                    </div>
	                    <hr />
	                    <divclass="col-md-12">
	                        <h4>Deseas agregar a esta persona?</h4>
	                        <br />
	                        <inputtype="radio"name="addToMsn" [(ngModel)]="shouldAdd"value="yes"id="add-yes">
	                        <labelfor="add-yes">Si quiero agregarlo</label><br />
	                        <inputtype="radio"name="addToMsn" [(ngModel)]="shouldAdd"value="no"id="add-no">
	                        <labelfor="add-no">No quiero agregarlo</label><br />
	                        <inputtype="radio"name="addToMsn" [(ngModel)]="shouldAdd"value="later"id="add-later">
	                        <labelfor="add-later">Quiero agregar más tarde</label><br />
	                    </div>
	                    
	                </div>
	            </div>
	            <footerclass="modal-footer">
	                <buttonclass="btn btn-primary" (click)="accept()">Ok</button>
	                <buttonclass="btn btn-default" (click)="close()">Cerrar</button>
	            </footer>
	        </div>
	    </div>
	    
	```
	
	request.component.ts
	``` 
	    import { Component, OnInit } from '@angular/core';
	    import { DialogService, DialogComponent } from 'ng2-bootstrap-modal';
	    import { UserService } from 'src/app/services/user.service';
	    import { PromptModel } from 'src/app/interfaces/IPromptModel';
	    import { RequestsService } from 'src/app/services/requests.service';
	    import { RequestStatus } from 'src/app/enum/requestStatusEnum';
	    @Component({
	      selector: 'app-request',
	      templateUrl: './request.component.html',
	      styleUrls: ['./request.component.sass']
	    })
	    export classRequestComponentextendsDialogComponent<PromptModel, any> implementsPromptModel {
	      scope: any;
	      shouldAdd: string = 'yes';
	      currentRequest: any;
	      friendRequest: any;
	    
	      constructor(public dialogService: DialogService, private userService: UserService, private requestsService: RequestsService) {
	        super(dialogService);
	    
	      }
	      ngOnInit(){
	        this.userService.getUserById(this.currentRequest.sender).valueChanges().subscribe((data)=>{
	          console.log(data);
	          this.friendRequest = data;
	        },(error)=>{
	          console.log(error);
	        });
	      }
	    
	      accept() {
	        if (this.shouldAdd == 'yes') {
	          this.requestsService.setRequestStatus(this.currentRequest, RequestStatus.Accepted).then((data) => {
	            this.userService.addFriend(this.scope.user.uid,this.currentRequest.sender).then((data)=>{
	              alert('Solicitud Aceptada con éxito.');
	            });
	          }).catch((error) => {
	            console.log(error);
	          });
	        }
	        elseif(this.shouldAdd == 'no'){
	          this.requestsService.setRequestStatus(this.currentRequest, RequestStatus.Rejected).then((data) => {
	            console.log(data);
	          }).catch((error) => {
	            console.log(error);
	          });
	        }
	        elseif (this.shouldAdd == 'later') {
	          this.requestsService.setRequestStatus(this.currentRequest, RequestStatus.Later).then((data) => {
	            console.log(data);
	          }).catch((error) => {
	            console.log(error);
	          });
	        }
	      }
	    
	    }
	    
	    
	```
	
	Resultado:
	
	![SolicitudDeAmistad.PNG](https://static.platzi.com/media/user_upload/SolicitudDeAmistad-9c42d10a-6adb-47ad-aeaf-5e982a4978d1.jpg)

	* **Pablo David Sánchez Aguilera** [823347] (1)

		Que version de angular estas usando ya qye y estoy usando el 8 y no me deja avancar esa seccion

* **Pablo David Sánchez Aguilera** (1) [815964](https://platzi.com/comentario/815964/) 

	Abra alguna excepción en app.component.ts con angular 8 ya que en el cosntructor en private dialogService: DialogService me genera error en la consola. Sera por la version de Angular?
	
	el error que me da es el siguiente: core.js:6014 ERROR NullInjectorError: StaticInjectorError(AppModule)[AppComponent -> DialogService]:  
	StaticInjectorError(Platform: core)[AppComponent -> DialogService]:  
	NullInjectorError: No provider for DialogService!

	* **JerezA** [815964] (2)

		pues lo que me dice de entrada tu stacktrace es que le hahce falta el provider de DialogService, en angular6 no se necesitaba provider, pero puede ser que para angular8 Cambiaran eso, por eso mi recomendacion es hacerlo con la version del framework del curso, ya hay un curso independiente de angular8 en el que podrias practicarlo

* **greivinfonseca** (1) [728303](https://platzi.com/comentario/728303/) 

	Si les da un error como este :
	
	ERROR Error: No component factory found for RequestComponent. Did you add it to @NgModule.entryComponents?  
	at noComponentFactoryError
	
	Lo que tienen que hacer es en el app.module.ts agreguen:
	
	**entryComponents:[RequestComponent]**
	
	Con eso lo pude resolver, ya que no podía avanzar

* **ma74ny** (1) [708535](https://platzi.com/comentario/708535/) 
	
	![](https://lh3.googleusercontent.com/-Enh-PUD6npY/XWRYpRhLxmI/AAAAAAABIyQ/7PED656asTg4DN9cNA-u-GDZjaaZeP-3QCK8BGAs/s0/2019-08-26.png)

* **Walter Jaramillo 2019** (1) [685533](https://platzi.com/comentario/685533/) 

	![solicitud.png](https://static.platzi.com/media/user_upload/solicitud-64132825-733c-49ad-b46a-d3cbe70d4654.jpg)![](url)

* **Rafael Andrés Cisneros Corro** (1) [660527](https://platzi.com/comentario/660527/) 

	tengo un problema, cuando recien se lanza la aplicacion no tienes usuario conectado y falla el servicio de Authentication getStatus, cuando me conecto tengo que recargar la pagina para que me cargue las solicitudes ya que ahora el getStatus si retorna un usuario. Algun solucion para esto?

	* **Manuel Angel Garcia Manzano** [660527] (1)

		No entiendo bien la pregunta podrias explicarte mejor? si es al momento de que se va a cargar el html entonces solo agrega un *ngIf = “user” a todo el contenido para que así se cargue solo si objeto user tiene algun valor. Por lo que entendí era eso pero mejor explica mejor para que te pueda ayudar.

* **Walter Lensinas** (1) [584588](https://platzi.com/comentario/584588/) 

	Buenas tardes, dejo el código de las clase en este branch: 55-solicitud-aceptar
	
	En el mismo esta el reto resuelto.
	
	Para ver el [código](https://github.com/wlensinas/platzinger-wl/tree/55-solicitud-aceptar).
	
	Para probar el código de esta clase:
	
	  1. `git clone https://github.com/wlensinas/platzinger-wl.git`
	  2. `git checkout 55-solicitud-aceptar`
	  3. `npm install`
	  4. Agregar el objeto firebase en environment con tu config:
	
	
	``` 
	    exportconst environment = {
	      production: false,
	      firebase: {
	      	apiKey: "",
	        authDomain: "",
	        databaseURL: "",
	        projectId: "",
	        storageBucket: "",
	        messagingSenderId: ""
	      }
	    };
	    
	```
	
	  1. `ng serve --open`
	
	
	
	Por favor, cualquier comentario, por github, por aquí o por twitter: @wlensinas
	
	Saludos.

* **Alex Eugenio Gavidia Donayre** (1) [553611](https://platzi.com/comentario/553611/) 
Gracias

* **sandovalgus** (1) [486800](https://platzi.com/comentario/486800/) 

	Buenas, tengo un problema, al “aceptar” la solicitud, me cambia el status a accepted en firebase, pero no me agrega la relacion en users/friends.  
	Es mas, antes de ejecutar this.userService.addFriend(…) me refresca la pagina. y me fije en Archivos el codigo y lo tengo igual.

	* **sandovalgus** [486800] (1)

		Sorry, ya encontré mi error, en **request.component.html** en la etiqueta **< a>** tenia ** href=""** por eso me refrescaba la pagina. Saludos.

* **elmerrodriguez** (1) [444939](https://platzi.com/comentario/444939/) 
	
	![modal.png](https://static.platzi.com/media/user_upload/modal-6d221027-aed7-489f-bde5-044fbb900f3c.jpg)
	``` 
	    userSend: User;
	    
	    constructor(public dialogService: DialogService,private authenticationService: AuthenticationService,private userService: UserService, private requestsService: RequestsService) { 
	        
	        super(dialogService);
	    
	        this.authenticationService.getStatus().subscribe( (status) => {
	          this.userService.getUserById(status.uid).valueChanges().subscribe( (data:User) => {
	            this.userSend = data;
	            console.log(this.userSend);
	          },(error) => {
	            console.log(error);
	          });
	        },(error) => {
	          console.log(error);
	        });
	      }
	    
	```
	``` 
	    <b>{{userSend.nick}}</b>
	    
	```

* **ivan_acg** (1) [440406](https://platzi.com/comentario/440406/) 

	No tuve que agregar código , lo único que había que hacer era un poco de css y de modificar el html del modal ,cambié en request.component.html:
	``` 
	    <b>{{currentRequest.sender}}</b>
	    
	    
	```
	
	por
	``` 
	    <b>{{currentRequest.receiver_email}}</b>
	    
	    
	```
	
	![as.png](https://static.platzi.com/media/user_upload/as-882d776d-f429-40a6-9534-bd0cd59191f4.jpg)

	* **ivan_acg** [440406] (1)

		request.component.css
		``` 
		     div.col-md-9 > b{
		       font-size: 40px;
		     }
		    div.col-md-9 > small{
		      font-size: 28px;
		    }
		    
		```

* **Jeffry Davila** (1) [411590](https://platzi.com/comentario/411590/) 

	No estuvo difícil.  
	![segundo.JPG](https://static.platzi.com/media/user_upload/segundo-1216d91e-46ba-4cb2-a0ed-f0018e707b65.jpg)

	* **Jeffry Davila** [411590] (1)

		request.component.ts
		``` 
		    ObtenerDatos()
		    {
		    this.authentificationService.getStatus().subscribe((session)=>
		    {
		     this.userService.getUserById(this.currentRequest.sender).valueChanges().subscribe((data:User)=>
		    {
		          this.user=data;
		          console.log(this.user);
		        },(error)=>{
		          console.log(error);
		        });
		    
		        });
		    
		     }
		    
		```

	* **Jeffry Davila** [411590] (1)

		```
		    constructor(public dialogService:DialogService,private userService:UserService,private requestsService:RequestsService,private authentificationService: AuthentificationService) 
		    { 
		        super(dialogService);
		        this.ObtenerDatos();
		      }
		    
		```

## 0560. Mostrando sólo contactos que son amigos [12797](https://platzi.com/clases/1340-angular-avanzado/12797-mostrando-solo-aquellos-contactos-que-son-amigos/)

### Descripción:


Agregamos el atributo _friends_ al _interface_ de User en el que almacenaremos los uids de sólo aquellos usuarios que efectivamente hemos aceptado y a partir de este arreglo vamos a mostrar los elementos en el html, para lo cual debemos actualizar la manera en que se aplican las directivas *ngIf y *ngFor en el componente home.

### Comentarios:

## 0570. Componentes anidados (con paso de parámetros) [12798](https://platzi.com/clases/1340-angular-avanzado/12798-componentes-anidados-con-paso-de-parametros6613/)

### Descripción:


Como ya vimos en las primeras clases del curso, los componentes en Angular, pueden contener internamente a otros componentes. A éstos se les denomina componentes anidados.

Para poder utilizar información proveniente de un componente externo en uno anidado, es necesario incluir en este último el decorador @Input. Al incluir el nuevo componente en el html del componente padre, deberá pasarse, a través de un atributo colocado entre corchetes “”[ ]"", el valor indicado en el decorador @Input.

### Comentarios:

* **Juan Diego Lopez Triana** (8) [381426](https://platzi.com/comentario/381426/) 

	Algo que tuve que aclarar fue la diferencia de inicializar una clase directamente desde el constructor o en el método ngOnInit(), la conclusión a la que llegué, es que como buena practica se debería mantener el constructor lo más simple posible y sin lógica compleja, solo inicializando los servicios que la clase va a utilizar y en el metodo ngOnInit sí utilizar estos servicios e implementar toda su lógica. En este vídeo, a diferencia de los anteriores del curso, se utilizo el servicio UserService en el método ngOnInit porque es en este método donde puedo acceder a la variable de tipo Input, de lo contrario marcaría error.

	* **Jhoysner Corona** [381426] (1)

		gracias por el aporte compañero

	* **Alexander Sandoval** [381426] (1)

		La documentación oficial de [Angular](https://angular.io/) recomienda hacer eso: utilizar el constructor sólo para definir las variables que se van a usar y usar el `ngOnInit()` para funcionalidad de inicio.

	* **Jecsham Castillo** [381426] (1)

		Gracias por el aporte. Yo estaba haciendo lógicas en el constructor… 😪

	* **Spyderp** [381426] (1)

		El ngOnInit() es un call back que ocurre antes que inicie el componente. Es recomendable usarlo ya que este permite la carga previa de algunos parametros propios del componente los cuales no se pueden acceder desde el constructor .

	* **JerezA** [381426] (1)

		Si, tienes razon, inclusive en casos en donde el componente sea complejo, y hay cuestiones de lentitud en red u otros, hacer logica en el OnInit permitira darle tiempo al componente de estar un paso mas adelante y poder jugar ya con objetos que requerian cargar informacion previa para poder operar

* **Adrian Alberto Casas Lopez** (1) [980116](https://platzi.com/comentario/980116/) 

	Cabe aclarar que al momento de implementar lo enseñado en la clase el buscador deja de funcionar ya que lo unico que tenemos del usuario es el uid. Antes de esto contabamos con todos los datos tales como: uid, nombre, nick, correo etc. Por lo que el pipe hace el filtro con todos los datos después de implementar el <app-contact> solo filtrara por el uid

## 0580. Reto Mensaje personal en Solicitud de Amistad [13008](https://platzi.com/clases/1340-angular-avanzado/13008-reto-mensaje-personal-en-solicitud-de-amistad/)

### Descripción:


Actualmente ya podemos agregar amigos y aceptar solicitudes de amistad. Pero hasta ahora, solo podemos introducir el correo del amigo que deseamos agregar, sin embargo sería bueno poder agregar un mensaje personal para que el contacto que lo reciba, pueda identificarte.

Entonces, hay que agregar ese nuevo input junto con el del email. Además, en el modal que se muestra al recibir la solicitud, desplegar el mensaje personal.

### Comentarios:

* **ziker** (3) [472069](https://platzi.com/comentario/472069/) 

	![Captura de pantalla 2019-01-08 a la\(s\) 21.06.40.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-08%20a%20la%28s%29%2021.06.40-d775eb4b-02fd-4423-be84-981a923288c8.jpg)  
	Asi quedo!

* **Jeffry Davila** (2) [413047](https://platzi.com/comentario/413047/) 

	Terminado.  
	![primero.JPG](https://static.platzi.com/media/user_upload/primero-325c5e16-b21c-4663-b64f-b2abf2a039c4.jpg)

* **Juan Diego Lopez Triana** (2) [381430](https://platzi.com/comentario/381430/) 

	Solo puse un campo en el objeto que se envia al hacer la solicitud, y en el html poner un etiqueta para mostrar dicho mensaje.
	``` 
	    const request = {
	          timestamp: Date.now(),
	          receiver_email: this.friendEmail,
	          message: this.friendMessage,
	          sender: this.user.uid,
	          status: 'pending'
	        }
	    
	```

	* **Juan Carlos Felizzola Vega** [381430] (1)

		¡Muy bien!

* **e.rodriguez** (1) [858545](https://platzi.com/comentario/858545/) 

	```
	    <divid="homeContainer">
	      <divclass="whiteBorderGlassBox">
	        <divclass="homeHeadContainer">
	          <divclass="row">
	            <divclass="col-md-auto">
	              <divclass="avatarFrameonline">
	                <imgsrc="assets/img/generic_avatar.png"id="homeAvatarPicture">
	              </div>
	            </div>
	            <divclass="col">
	              <b>{{user.nick}}</b>
	              <div>
	                <span>{{user.status}}</span>
	                <br/>
	                <span>< EscribeunmensajePersonal ></span>
	                <br/>
	                <a (click)="logout()">Logout</a>
	              </div>
	            </div>
	          </div>
	        </div>
	      </div>
	    
	      <divclass="whiteContainerPadded marto15">
	    
	        <divclass="row">
	          <divclass="col">
	            <inputtype="text"class="form-control"placeholder="Buscar Amigo" [(ngModel)]="query"/>
	          </div>
	          <divclass="col-md-auto">
	            <img (click)="open(content)"src="assets/img/logo_live_add.png"class="icon"alt="">
	          </div>
	        </div>
	        <hr/>
	        <b *ngIf="user && user.friends">Amigos ({{user.friends.length}} / {{user.friends.length}})</b>
	        <div *ngIf="user&& user.friends">
	          <divclass="disblo marbo5">
	            <app-contactclass="col-md-12" *ngFor="let user of user.friends" [uid]="user"></app-contact>
	          </div>
	        </div>
	      </div>
	    </div>
	    
	    
	    <ng-template #contentlet-modal>contac
	      <divclass="modal-header">
	        <h4class="modal-title"id="modal-basic-title">Agregar amigo</h4>
	        <buttontype="button"class="close"aria-label="Close" (click)="modal.dismiss('Cross click')">
	          <spanaria-hidden="true">&times;</span>
	        </button>
	      </div>
	      <divclass="modal-body">
	        <div>
	          <b>Ingresa Email de tu amigo</b>
	          <inputtype="email"class="form-control"placeholder="email" [(ngModel)]="friendEmail">
	          <textareaclass="form-control marto15" [(ngModel)]="friendMessage"rows="3"></textarea>
	        </div>
	      </div>
	      <divclass="modal-footer">
	        <buttontype="button"class="btn btn-outline-dark" (click)="sendRequest()">Guardar</button>
	      </div>
	    </ng-template>
	    
	    
	    
	```
	``` 
	    import {Component, OnInit} from '@angular/core';
	    import {User} from "../../interfaces/user";
	    import {UserService} from "../../services/user.service";
	    import {AuthenticationService} from "../../services/authentication.service";
	    import {Router} from "@angular/router";
	    import {NgbModal} from "@ng-bootstrap/ng-bootstrap";
	    import {RequestsService} from "../../services/requests.service";
	    
	    @Component({
	      selector: 'app-home',
	      templateUrl: './home.component.html',
	      styleUrls: ['./home.component.scss']
	    })
	    export class HomeComponent implements OnInit {
	    
	      friends: User[];
	      query: string;
	      private user: User;
	      closeResult: string;
	      friendEmail: string;
	      friendMessage: string;
	    
	    
	      constructor(private userService: UserService, private authenticationService: AuthenticationService, private router: Router, private modalService: NgbModal, private requestService: RequestsService) {
	        this.getUsers();
	        this.getUserSession();
	      }
	    
	      private getUsers() {
	        this.userService.getUsers().valueChanges().subscribe((data: User[]) => {
	          this.friends = data;
	        }, (error) => {
	          console.log(error);
	        });
	      }
	    
	      logout() {
	        this.authenticationService.logout().then((data) => {
	          alert('sesion cerrada');
	          this.router.navigate(['login']);
	        }).catch((error) => console.log());
	      }
	    
	      ngOnInit() {
	      }
	    
	      private getUserSession() {
	        this.authenticationService.getStatus().subscribe((status) => {
	          this.userService.getUserById(status.uid).valueChanges().subscribe(
	            (user: User) => {
	              this.user = user;
	              if (this.user.friends) {
	                this.user.friends = Object.values(this.user.friends);
	                console.log(this.user);
	              }
	            },
	            (error) => {
	              console.log(error);
	            })
	        }, (error) => {
	          console.log(error);
	        })
	      }
	    
	    
	      open(content) {
	        this.modalService.open(content, {ariaLabelledBy: 'modal-basic-title'}).result.then((result) => {
	        }, (reason) => {
	        });
	      }
	    
	      private sendRequest() {
	        const request = {
	          timestamp: Date.now(),
	          receiver_email: this.friendEmail,
	          sender: this.user.uid,
	          friend_message: this.friendMessage,
	          status: 'pending'
	        }
	    
	        this.requestService.createRequest(request).then(() => alert('solicitud enviada')).catch(() => console.log('error'));
	    
	      }
	    }
	    
	    
	```
	``` 
	    <divclass="modal-dialog modal-lg">
	      <divclass="modal-content">
	        <divclass="modal-header">
	          Nueva Solicitud
	          <aclass="closeButton" (click)="close()">x</a>
	        </div>
	        <divclass="modal-body"style="height: auto">
	          <divclass="row">
	            <divclass="col-md-3">
	              <imgsrc="assets/img/generic_avatar.png"class="img-fluid" />
	            </div>
	            <divclass="col-md-9">
	              <b>{{currentRequest.sender}}</b>
	              <small>Te ha enviado esta solicitud</small>
	              <textareareadonlyclass="form-control"id="exampleFormControlTextarea1"rows="3">{{currentRequest.friend_message}}</textarea>
	            </div>
	            <hr />
	            <divclass="col-md-12">
	              <h4>Deseas agregar a esta persona?</h4>
	              <br />
	              <inputtype="radio"name="addToMsn" [(ngModel)]="shouldAdd"value="yes"id="add-yes"><labelfor="add-yes">Si quiero agregarlo</label><br />
	    
	              <inputtype="radio"name="addToMsn" [(ngModel)]="shouldAdd"value="no"id="add-no"><labelfor="add-no">No quiero agregarlo</label><br />
	    
	              <inputtype="radio"name="addToMsn" [(ngModel)]="shouldAdd"value="later"id="add-later"><labelfor="add-later">Decido despuees</label><br />
	            </div>
	          </div>
	        </div>
	        <divclass="modal-footer">
	          <aclass="btn btn-primary" (click)="accept()">Ok</a>
	          <aclass="btn btn-default" (click)="close()">Cerrar</a>
	        </div>
	      </div>
	    </div>
	    
	    
	```

* **caprilespe** (1) [825986](https://platzi.com/comentario/825986/) 

	Cumpliendo con el reto
	
	home.component.html
	``` 
	    <divid="homeContainer">
	        <divclass="whiteBorderGlassBox">
	            <divclass="homeHeadContainer">
	                <divclass="row">
	                    <divclass="col-md-auto">
	                        <divclass="avatarFrameOnline">
	                            <imgsrc="assets/img/generic_avatar.png"id="homeAvatarPicture"alt="Imagen de Perfil">
	                        </div>
	                    </div>
	                    <divclass="col">
	                        <b>{{user.nick}}</b>
	                        <div>
	                            <span>{{user.status}}</span>
	                            <br />
	                            <span>
	                                {{user.subnick}}
	                            </span><br />
	                            <a (click)="logOut()">Logout</a>
	                        </div>
	                    </div>
	                </div>
	            </div>
	        </div>
	        <divclass="whiteContainerPadded margin-top-15">
	            <divclass="row">
	                <divclass="col">
	                    <inputtype="text"class="form-control"placeholder="Buscar Amigo" [(ngModel)]="query">
	                </div>
	                <divclass="col-md-auto">
	                    <imgsrc="assets/img/logo_live_add.png"alt=""class="icon" (click)="open(content)">
	                </div>
	            </div>
	            <hr />
	            <b *ngIf="user && user.friends">Amigos ({{user.friends.length}} / {{user.friends.length}})</b>
	            <div *ngIf="user && user.friends">
	                <divclass="display-block margin-bottom-5">
	                    <app-contactclass="col-md-12" *ngFor="let user of user.friends | search:query; let i = index"
	                        [uid]="user"></app-contact>
	                </div>
	            </div>
	        </div>
	        <ng-template #contentlet-modal>
	            <divclass="modal-header">
	                <h4class="modal-title"id="modal-basic-title">Tienes una Solicitud</h4>
	                <buttontype="button"class="close"aria-label="Close" (click)="modal.dismiss('Cross click')">
	                    <spanaria-hidden="true">&times;</span>
	                </button>
	            </div>
	            <divclass="modal-body">
	                <divclass="container">
	                    <divclass="row">
	                        <h4>Mensaje</h4>
	                        <textareaclass="form-control editor" [(ngModel)]="friendMessage"></textarea>
	                    </div>
	                    <divclass="row">
	                        <b>Ingresa el email de tu amigo</b>
	                        <inputtype="email"class="form-control"placeholder="Email" [(ngModel)]="friendEmail"
	                            (keyup.enter)="sendRequest()" />
	                    </div>
	                </div>
	            </div>
	            <divclass="modal-footer">
	                <buttontype="button"class="btn btn-outline-dark" (click)="sendRequest()">Guardar</button>
	            </div>
	        </ng-template>
	    </div>
	    
	```
	
	home.component.ts en el metodo sendRequest()
	``` 
	      sendRequest() {
	        const request = {
	          timestamp: Date.now(),
	          receiver_email: this.friendEmail,
	          receiver_message:this.friendMessage,
	          sender: this.user.uid,
	          status: RequestStatus.Pending
	        }
	    
	        this.requestService.createRequest(request).then(() => {
	          alert("Solicitud Enviada");
	        }).catch((error) => {
	          alert("Hubo un error");
	          console.log(error);
	        });
	      }
	    
	```
	
	![envioDeSolicitud.PNG](https://static.platzi.com/media/user_upload/envioDeSolicitud-186c9be1-ff65-4e64-8fe9-b58b04f94369.jpg)
	
	request.component.html
	``` 
	    <divclass="modal-dialog modal-lg">
	        <divclass="modal-content">
	            <divclass="modal-header">
	                Nueva Solicitud
	                <ahref=""class="closeButton" (click)="close()">x</a>
	            </div>
	            <divclass="modal-body"style="height:auto;" *ngIf="friendRequest">
	                <divclass="row">
	                    <divclass="col-md-3">
	                        <img [src]="friendRequest.avatar || 'assets/img/generic_avatar.png'"alt=""class="img-fluid" />
	                    </div>
	                    <divclass="col-md-9">
	                        <b>{{friendRequest.nick}}</b>
	                        <small>Te ha enviado esta solicitud</small>
	                        <div *ngIf="currentRequest.receiver_message">
	                            <h6>Mensaje en solicitud</h6>
	                            <p>{{currentRequest.receiver_message}}</p>
	                        </div>
	    
	                    </div>
	                    <div *ngIf="currentRequest.receiver_message"class="col-md-12">
	    
	                    </div>
	                    <hr />
	                    <divclass="col-md-12">
	                        <h4>Deseas agregar a esta persona?</h4>
	                        <br />
	                        <inputtype="radio"name="addToMsn" [(ngModel)]="shouldAdd"value="yes"id="add-yes">
	                        <labelfor="add-yes">Si quiero agregarlo</label><br />
	                        <inputtype="radio"name="addToMsn" [(ngModel)]="shouldAdd"value="no"id="add-no">
	                        <labelfor="add-no">No quiero agregarlo</label><br />
	                        <inputtype="radio"name="addToMsn" [(ngModel)]="shouldAdd"value="later"id="add-later">
	                        <labelfor="add-later">Quiero agregar más tarde</label><br />
	                    </div>
	    
	                </div>
	            </div>
	            <footerclass="modal-footer">
	                <buttonclass="btn btn-primary" (click)="accept()">Ok</button>
	                <buttonclass="btn btn-default" (click)="close()">Cerrar</button>
	            </footer>
	        </div>
	    </div>
	    
	```
	
	![mensajeEnSolicitud.PNG](https://static.platzi.com/media/user_upload/mensajeEnSolicitud-8d3930c7-3747-43b2-ad09-86807c019125.jpg)

* **WALTER RAUL CANCHAN HERMOZA** (1) [775089](https://platzi.com/comentario/775089/) 

	![](![2019-10-09 23_05_06-Window.png](https://static.platzi.com/media/user_upload/2019-10-09%2023_05_06-Window-ba7fb81e-ba54-4712-88d6-0131ea8b433c.jpg)

* **ma74ny** (1) [709971](https://platzi.com/comentario/709971/) 
	
	![](https://lh3.googleusercontent.com/-DG8WvXOsLlY/XWWD1isO35I/AAAAAAABIzg/IfJRFSU-jD4qT1LIM0SKHrJJ38hB02-NgCK8BGAs/s0/2019-08-27.png) ![](https://lh3.googleusercontent.com/-8HofSNmox-0/XWWENoy9cEI/AAAAAAABIzo/qXPl8fgDC_EQW_AwGMGmRZkaYRXZlEwtwCK8BGAs/s0/2019-08-27.png)

* **cesarcadavid** (1) [587655](https://platzi.com/comentario/587655/) 

	Home Component Html
	``` 
	    <divclass="col-md-12">
	    	<b>Enviale un saludo a tu amigo</b>
	    	<textarea [(ngModel)]="greetingRequest"class="form-control"></textarea>
	    </div>
	    
	```
	
	Home Component ts
	``` 
	    greetingRequest: string;
	    
	    const request = {
	      timestamp: Date.now(),
	      receiver_email: this.friendEmail,
	      sender: this.user.uid,
	      status: 'pending',
	      greeting: this.greetingRequest
	    };
	    
	```
	
	Request Component Html
	``` 
	    <divclass="col-md-10">
	      <divclass="mb-3">
	    	<div><b>{{userRequestFriendship.nick}}</b></div>
	    	<div><small>{{userRequestFriendship.email}}</small></div>
	    	<div><small>Te ha enviado esta solicitud</small></div>
	      </div>
	      <divclass="alert alert-primary"role="alert">
	    	<b>Te ha enviado este saludo</b>
	    	<p>{{currentRequest.greeting}}</p>
	      </div>
	    </div>
	    
	```

* **Walter Lensinas** (1) [585841](https://platzi.com/comentario/585841/) 
	
	![reto.jpg](https://static.platzi.com/media/user_upload/reto-f87b7fcc-77b4-4d57-a847-918975526bce.jpg)
	
	Listo!
	
	codigo: <https://github.com/wlensinas/platzinger-wl/tree/58-reto>

* **Ezequiel-Fabbroni** (1) [505194](https://platzi.com/comentario/505194/) 
	
	![Captura de pantalla de 2019-02-08 13:23:11.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20de%202019-02-08%2013%3A23%3A11-39957e24-b7ec-4d71-886c-484051262cf0.jpg)

* **developerresol1** (1) [458368](https://platzi.com/comentario/458368/) 

	Le agrege como atributo “message?: string” y cree el componente anidado en el modal. Así me quedo:  
	![Screenshot_1.png](https://static.platzi.com/media/user_upload/Screenshot_1-8f7fa6c1-6ee9-4e31-8cf8-c442b90d0312.jpg)

* **Emerson-Lirmi** (1) [427250](https://platzi.com/comentario/427250/) 

	Me confundo en algunas partes!

* **Emerson-Lirmi** (1) [46077](https://platzi.com/comentario/427250/) 
Me confundo en algunas partes!

# Deploy [2355]

## 0590. Creando un wrapper para desktop, usando Electron [12799](https://platzi.com/clases/1340-angular-avanzado/12799-creando-un-wrapper-para-desktop-usando-electron/)

### Descripción:


 **Electron** es un framework muy potente que nos permite encapsular nuestras aplicaciones de Angular en wrappers nativos para sistemas operativos de escritorio como _Windows, MacOS_ o _Linux_. Incluso podremos generar los paquetes de instalación, también nativos, para cada sistema operativo con otra herramienta llamada `electron-packager`.

Electron debe ser instalado mediante npm:
``` 
    npm install electron --save-exact
    
```

Una vez instalado el paquete, tendremos que crear un archivo llamado `main.js` en el directorio raíz de nuestra aplicación y referenciarlo en el archivo package.json de nuestra app con el atributo ““main””. En este archivo debemos importar los objetos app y BrowserWindow, además de crear los valores de configuración y la función createWindow(), necesarios para generar la aplicación.

Definimos los manejadores de los eventos ‘ready’, ‘window-close-all’ y ‘activate’ que enlazarán a la función createWindow() y a las instrucciones necesarias para liberar la memoria de los recursos reservados por la aplicación cuando ésta haya sido cerrada o reactivar si se ha minimizado, respectivamente.

En el sistema operativo MacOS hay una particularidad, y es que al cerrar la ventana de una aplicación, ésta continúa ejecutándose en segundo plano, por lo que es necesario tener en cuenta esta salvedad en nuestro código para que la aplicación tenga un comportamiento esperado en cada uno de los sistemas operativos.

Finalmente generamos el paquete de producción de nuestra aplicación con el comando de Angular CLI: `ng build --prod`, generando la carpeta `dist/` con los archivos y recursos optimizados y comprimidos para el ambiente de producción y por último el comando `electron .`

Para generar el paquete de instalación debemos ejecutar:
``` 
    electron-packager ./ <nombre-de-la-app> --platform=<plataforma> --icon <ubicacion-icono>
    
```

El parámetro `<plataforma>` puede tomar los valores: win32 (para SO Windows) o darwin (para MacOS)

### Links:

* [GitHub - electron-userland/electron-packager: Customize and package your Electron app with OS-specific bundles (.app, .exe, etc.) via JS or CLI](https://github.com/electron-userland/electron-packager)

* [Angular 5 Electron Tutorial](https://coursetro.com/posts/code/125/Angular-5-Electron-Tutorial)

### Comentarios:

* **ivan_acg** (4) [441350](https://platzi.com/comentario/441350/) 

	Para los que usan Windows , cambien en vez de darwin por:
	``` 
	    if(process.platform !== 'win32')
	    
	```

* **Gonzalo Muñoz** (3) [699441](https://platzi.com/comentario/699441/) 

	Si les sale la pantalla en blanco y la solución de cambiar el target a es5 no les funciona, lo que me sirvió a mi fue cambiar en el package.json el “electron” por:
	
	“electron”: “ng build --base-href ./ && electron .”,

* **Ale17273has** (3) [603895](https://platzi.com/comentario/603895/) 

	Alguien sabe porque se queda en blanco la pantalla de electron, se ejecuta el comando pero sale la siguiente pantalla
	
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-2a7b8ca8-92f3-492b-bbcb-06f1932c9125.jpg)

	* **ManuFerrer** [603895] (1)

		Me ocurre exactamente lo mismo 😕

	* **ManuFerrer** [603895] (1)

		¿Conseguiste solucionarlo?

	* **Ale17273has** [603895] (1)

		nada pero con windows 7 funciona

	* **Andres Rodriguez (Platzi)** [603895] (1)

		El `pathname` apunta a la carpeta build, en desarrollo esta no se construye sola, deben construirla con:  
		`ng build`  
		o  
		`ng build --prod`  
		si quieren transpilarlos para producción.

	* **Angel Javier Puc Yamá** [603895] (1)

		Alguien por amor de yisus consiguió solucionar este problema?

	* **charlieg** [603895] (1)

		A mi me sucedio lo mismo.
		
		Se puede colocar esta linea en **main.js** , en el método **createWindow** , para poder observar cuales son los problemas en la consola.
		``` 
		    win.webContents.openDevTools();
		    
		```

	* **charlieg** [603895] (4)

		Logré solucionar este problema de este modo. Dentro del archivo **tsconfig.json** , se encuentra :
		``` 
		    "target": "es2015",
		    
		```
		
		lo cambie por:
		``` 
		    "target": "es5",
		    
		```
		
		y ya me mostró la aplicación. Referencia: <https://malcoded.com/posts/angular-desktop-electron/>

	* **Rafael Andrés Cisneros Corro** [603895] (1)

		Me funciono la respuesta de charlieg

	* **AhorraSegurosMX** [603895] (1)

		Actualicen su main.js  
		Actualmente la ruta es:
		
		pathname: path.join(__dirname, ‘dist/myAppName/index.html’),
		
		en su main.js, busquen esa linea, ya que la ruta no solo es dist.

* **Brandon Iván Quiroa Loarca** (2) [628879](https://platzi.com/comentario/628879/) 

	No crei que estuviera tan completo el curso, pero me sorprendio todos los usos que le dio Eduardo. Buenisimo los cursos que imparte.

* **Angel Javier Puc Yamá** (2) [628832](https://platzi.com/comentario/628832/) 

	Alguien que me ayude a resolver por que el resultado de electron solo aparece una pantalla blanca y con CTRL + SHIFT + i el error que dice es:
	
	Failed to load module script: The server responded with a non-JavaScript MIME type of “”. Strict MIME type checking is enforced for module scripts per HTML spec.
	
	![](https://drive.google.com/file/d/1CXef-vAFPpVSZwSilSoE-GvV11nQE9Xk/view?usp=sharing)

	* **Angel Javier Puc Yamá** [628832] (1)
![](%5Bhttps://ibb.co/rQ6g4fS%5D\(https://ibb.co/rQ6g4fS\))

	* **Angel Javier Puc Yamá** [628832] (1)
![](https://i.ibb.co/j8MdgZ2/1.png)

	* **Katherine Cortés** [628832] (2)

		El pathname apunta a la carpeta build, en desarrollo esta no se construye sola, deben construirla con:  
		ng build  
		o  
		ng build --prod  
		si quieren transpilarlos para producción.

	* **Andres Rodriguez (Platzi)** [628832] (2)

		El `pathname` apunta a la carpeta build, en desarrollo esta no se construye sola, deben construirla con:  
		`ng build`  
		o  
		`ng build --prod`  
		si quieren transpilarlos para producción.

	* **Angel Javier Puc Yamá** [628832] (1)

		Disculpa @andresmaro si puse ng build y sigue quedando la pantalla blanca, de igual forma intente con ng build --prod y el resultado es el mismo.
		
		Que otra opción podría intentar?

	* **Angel Javier Puc Yamá** [628832] (1)

		?

* **Jeffry Davila** (2) [413559](https://platzi.com/comentario/413559/) 

	Un pregunta: ¿porque en el ejecutable de electrón no aparece la imagen  
	azul de fondo?![tercero.JPG](https://static.platzi.com/media/user_upload/tercero-7755d8ed-6970-4542-bb6b-7631999d73b9.jpg)

	* **Alexander Sandoval** [413559] (1)

		En la ventana que abre electron puedes ver la consola igual que en el browser sólo tienes que hacer `Ctrl + Shift + i`. Uno de los errores que yo leo es: **Failed to load resource: net::ERR_FILE_NOT_FOUND**. Esa puede ser la explicación, aún no he intentado resolverlo.

* **Miguel Angel Ramos Rodríguez** (2) [388688](https://platzi.com/comentario/388688/) 

	Excelente no conocia electron ahora me esta gustando mucho las tecnologias javascript, por cierto se perdieron los fondos. en la app de escritorio.

* **ehnbytes** (1) [1018256](https://platzi.com/comentario/1018256/) 

	Excelente clase!

* **Rafael Andrés Cisneros Corro** (1) [661873](https://platzi.com/comentario/661873/) 

	No puedo compilar con --prod me sale el siguiente error:  
	ERROR in src/app/home/home.component.html(6,40): : Property ‘croppedImage’ does not exist on type ‘HomeComponent’.

	* **jinvernon** [661873] (1)

		Esto es porque no la tienes definida en tu Ts. Chequea si esta bien definida

* **Rafael Andrés Cisneros Corro** (1) [661865](https://platzi.com/comentario/661865/) 

	Si les sale la pantalla en blanco, esta solucion me sirvio, cortesia de charlieg unos comentarios mas abajo:
	
	Logré solucionar este problema de este modo. Dentro del archivo tsconfig.json, se encuentra :
	``` 
	    "target": "es2015",
	    
	```
	
	lo cambie por:
	``` 
	    "target": "es5",
	    
	```
	
	y ya me mostró la aplicación. Referencia: <https://malcoded.com/posts/angular-desktop-electron/>

* **juanbarcinilla** (1) [648395](https://platzi.com/comentario/648395/) 

	Excelente muy buena explicación sobre la empaquetacion de los archivos.

* **Steven18** (1) [622751](https://platzi.com/comentario/622751/) 
Muy interesante conocer ELECTRON, este poderoso framework nos ayuda a que nuestra aplicacion web desarrollada con Angular pueda ejecutarse de forma "nativa" en aplicaciones Desktop multiplataforma. Al igual que Ionic orientado en moviles

* **franklin barco** (1) [588639](https://platzi.com/comentario/588639/) 

	 **Me sale este error al ejecutar npm install electron --save-exact**
	``` 
	    C:\Users\zankeii\Documents\PLATZI\ANGULAR6\messenger>npm install electron --save-exact
	    
	    > electron@5.0.1 postinstall C:\Users\zankeii\Documents\PLATZI\ANGULAR6\messenger\node_modules\electron
	    > node install.js
	    
	    Downloading tmp-12604-0-electron-v5.0.1-win32-x64.zip
	    Error: read ECONNRESET
	    C:\Users\zankeii\Documents\PLATZI\ANGULAR6\messenger\node_modules\electron\install.js:49
	      throw err
	      ^
	    
	    Error: read ECONNRESET
	        at TLSWrap.onStreamRead (internal/stream_base_commons.js:167:27)
	    npm WARN bootstrap@4.3.1 requires a peer of jquery@1.9.1 - 3 but none is installed. You must install peer dependencies yourself.
	    npm WARN bootstrap@4.3.1 requires a peer of popper.js@^1.14.7 but none is installed. You must install peer dependencies yourself.
	    npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.8 (node_modules\fsevents):
	    npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.8: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})
	    
	    npm ERR! code ELIFECYCLE
	    npm ERR! errno 1
	    npm ERR! electron@5.0.1 postinstall: `node install.js`
	    npm ERR! Exit status 1
	    npm ERR!
	    npm ERR! Failed at the electron@5.0.1 postinstall script.
	    npm ERR! This is probably not a problem withnpm. There is likely additional logging output above.
	    
	    npm ERR! A complete log ofthis run can be found in:
	    npm ERR!     C:\Users\zankeii\AppData\Roaming\npm-cache\_logs\2019-05-15T23_55_02_152Z-debug.log
	    
	```

* **Walter Lensinas** (1) [586052](https://platzi.com/comentario/586052/) 

	Me encanta esta solución para hacer el delivery de la app!! GENIO EDUARDOOOO!!!

	* **Walter Lensinas** [586052] (1)

		Código aqui: <https://github.com/wlensinas/platzinger-wl/tree/59-electron>

* **Juan Camilo Bula** (1) [567818](https://platzi.com/comentario/567818/) 

	Que ruta de aprendizaje recomiendan para crear aplicaciones de escritorio o software de escritorio multiplataforma como este, me gustaria aprender desde 0 hasta llegar a este curso. les agradeceria mucho si me dijeran

	* **aragonesteban (Platzi)** [567818] (1)

		Hola Juan, puedes comenzar haciendo el curso de [Electron](https://platzi.com/clases/electron/) para profundizar estos conocimientos, luego puedes pasar a hacer el curso de [PWA con Angular](https://platzi.com/clases/pwa-angular/), ya teniendo estos conceptos puedes pasar a hacer aplicaciones móviles tomando el curso de [Ionic](https://platzi.com/clases/ionic/), con estos cursos crearás aplicaciones multiplataforma.

* **Alex Eugenio Gavidia Donayre** (1) [553796](https://platzi.com/comentario/553796/) 

	Interesante

* **Milciades** (1) [494121](https://platzi.com/comentario/494121/) 

	me esta saliendo este error al correr el comando npm run electron
	``` 
	    Date:2019-01-29T16:29:28.223Z
	    Hash:89e431da156078dfc4b0
	    Time:13008ms
	    chunk {main} main.js, main.js.map (main) 82.3 kB [initial] [rendered]
	    chunk {polyfills} polyfills.js, polyfills.js.map (polyfills) 227 kB [initial] [rendered]
	    chunk {runtime} runtime.js, runtime.js.map (runtime) 5.22 kB [entry] [rendered]
	    chunk {styles} styles.js, styles.js.map (styles) 260 kB [initial] [rendered]
	    chunk {vendor} vendor.js, vendor.js.map (vendor) 6.86 MB [initial] [rendered]
	    C:\Users\milciades.vargas\Downloads\messagelive\main.js:25
	    app.on("ready", createWindow);
	        ^
	    
	    TypeError: Cannot read property 'on' of undefined
	    
	        at Object.<anonymous> (C:\Users\milciades.vargas\Downloads\messagelive\main.js:25:5)
	        at Object.<anonymous> (C:\Users\milciades.vargas\Downloads\messagelive\main.js:41:3)
	        at Module._compile (internal/modules/cjs/loader.js:693:30)
	        at Object.Module._extensions..js (internal/modules/cjs/loader.js:704:10)
	        at Module.load (internal/modules/cjs/loader.js:602:32)
	        at tryModuleLoad (internal/modules/cjs/loader.js:541:12)
	        at Function.Module._load (internal/modules/cjs/loader.js:533:3)
	        at Function.Module.runMain (internal/modules/cjs/loader.js:746:12)
	        at startup (internal/bootstrap/node.js:282:19)
	        at bootstrapNodeJSCore (internal/bootstrap/node.js:759:3)
	    npm ERR! code ELIFECYCLE
	    npm ERR! errno 1
	    npm ERR! messagelive@0.0.0electron: `ng build && electron .`
	    npm ERR! Exit status 1
	    npm ERR!
	    npm ERR! Failed at the messagelive@0.0.0 electron script.
	    npm ERR! This is probably not a problem with npm. There is likely additional logging output above.
	    
	    npm ERR! A complete log of this run can be found in:
	    npm ERR!     C:\Users\milciades.vargas\AppData\Roaming\npm-cache\_logs\2019-01-29T16_29_29_102Z-debug.log
	    
	```

	* **Pablo Sozko** [494121] (1)

		Trata de cambiar a otro directorio y probar tuve el mismo problema y se debia al . en el nombre de una de las carpetas en tu caso creo que se debe a milciades.vargas

* **Germain Rafael Bueno Taguariparo** (1) [467631](https://platzi.com/comentario/467631/) 

	excelente aporte. Un curso más que hacer en platzi…

* **ivan_acg** (1) [441365](https://platzi.com/comentario/441365/) 

	ng build --prod para usar la carpeta dist si no les aparece.

* **Juan Carlos Felizzola Vega** (1) [389955](https://platzi.com/comentario/389955/) 

	 **Electron** en este caso se recomienda instalar como dependencia de desarrollo dentro del proyecto.
	
	**Curso de Electron:**  
	<https://platzi.com/clases/electron/>

* **José Francisco Ojeda Vera** (1) [388385](https://platzi.com/comentario/388385/) 

	Excelente la explicación, un gran aporte

* **Ale17273has** (1) [60321](https://platzi.com/comentario/603895/) 
Alguien sabe porque se queda en blanco la pantalla de electron, se ejecuta el comando pero sale la siguiente pantalla

	* **ManuFerrer** [60321] (1)

		Me ocurre exactamente lo mismo 😕

* **Cristian David Franco Garcia** (0) [472060](https://platzi.com/comentario/472060/) 

	ng build --base-href ./

## 0600. Reto Dándole Características PWA a nuestra App [13009](https://platzi.com/clases/1340-angular-avanzado/13009-reto-dandole-caracteristicas-pwa-a-nuestra-app/)

### Descripción:


Nuestra app está ya lista para ser publicada en producción usando Firebase Hosting, también para distribuirse de manera nativa en Windows y Mac usando el wrapper de Electron.

Sin embargo, aún no hemos cubierto una opción importantísima para Platzinger que es la de PWA; un PWA básicamente es una aplicación web que trata de parecerse lo más posible a un app móvil y te permite obtener lo mejor de ambos mundos (móvil y web).

Entonces, ahora implementarás características de un PWA en Platzinger, basándote en el curso de [Angular PWA](https://platzi.com/cursos/pwa-angular/) que tenemos publicado aquí en Platzi.

### Comentarios:

* **Alex Eugenio Gavidia Donayre** (3) [553800](https://platzi.com/comentario/553800/) 

	Esto se ve fascinante !!! Gracias platzi!

## 0610. Exportando app para web, complementando con Firebase Hosting [12800](https://platzi.com/clases/1340-angular-avanzado/12800-exportando-app-para-web-complementando-con-firebas/)

### Descripción:


Para hacer el deploy de nuestra app hacia la web, usaremos el servicio de hosting gratuito de Firebase, para lo cual sólo es necesario seguir los siguientes pasos:

* Instalar las Firebase tools con `npm install -g firebase-tools`
* Hacer login desde la terminal con `firebase login`
* Inicializar el directorio del proyecto con `firebase init`
* y realizar el despliege con `firebase deploy`



Al finalizar el proceso de deploy, Firebase nos indicará la url en la que se ha hecho la publicación. Esta url será servida de manera segura a través de https por Firebase.

### Comentarios:

* **ManuFerrer** (3) [439647](https://platzi.com/comentario/439647/) 

	Genial !, tuve que venir desde el curso de angular 4 pero ha valido la pena.

	* **Jecsham Castillo** [439647] (2)

		Lo mismo digo! 😎

	* **Germain Rafael Bueno Taguariparo** [439647] (1)

		tal cual. La mega maraton jajaja

	* **Alex Eugenio Gavidia Donayre** [439647] (1)

		Exacto!

* **ivan_acg** (2) [441689](https://platzi.com/comentario/441689/) 

	Para que no hagan deploy sobre un proyecto anterior tienen que ingresar :
	``` 
	    firebase use <project-id >
	    
	```

	* **ivan_acg** [441689] (0)

		Y ahi ponen el nombre del proyecto anterior

* **robertojosuemendozanieto** (1) [996771](https://platzi.com/comentario/996771/) 

	Y si lo quiero subir a cpanel cómo puedo ocupar más de 96 dist que me salieron

* **emanuel-gordillo** (1) [640959](https://platzi.com/comentario/640959/) 
Como seria si utilizamos express y MySQL ? Es decir estos dos sean nuestro servidor, como cambiaríamos el localhost y como estaria Express en deploy?

* **anahipresas** (1) [593602](https://platzi.com/comentario/593602/) 

	Buenas Tardes ! Porque Firebase No Me Muestra El Menú Con Todos Mis Proyectos.  
	Before we get started, keep in mind:
	
	* You are initializing in an existing Firebase project directory
	
	
	
	? Are you ready to proceed? Yes  
	? Which Firebase CLI features do you want to set up for this folder? Press Space to select features, then Enter to conf  
	irm your choices. Database: Deploy Firebase Realtime Database Rules, Hosting: Configure and deploy Firebase Hosting sit  
	es
	
	=== Project Setup
	
	First, let’s associate this project directory with a Firebase project.  
	You can create multiple project aliases by running firebase use --add,  
	but for now we’ll just set up a default project.
	
	i .firebaserc already has a default project, skipping
	
	=== Database Setup
	
	Firebase Realtime Database Rules allow you to define how your data should be  
	structured and when your data can be read from and written to.
	
	? What file should be used for Database Rules? (database.rules.json)

* **Alex Eugenio Gavidia Donayre** (1) [561892](https://platzi.com/comentario/561892/) 

	Tuve que regresar al curso, para recordar que el public directory es:  
	dist/NOMBRE DE TU PROYECTO!!!

* **Gabriel Solorzano** (1) [538429](https://platzi.com/comentario/538429/) 

	En el curso Angular 4 se dió esta misma clase pero en las opciones de $ **firebase init** SOLO SE ELIGIÓ HOSTING. Ahora el profesor eligió 2: HOSTING y DATABASE
	
	Cuál será la diferencia?

	* **Alex Eugenio Gavidia Donayre** [538429] (1)

		La diferencia es utilizar lo que necesitas. Simple.

* **Jenniffer Helena Alvarez Puello** (1) [513748](https://platzi.com/comentario/513748/) 

	Excelente curso

* **Alan Nava Torres** (1) [512536](https://platzi.com/comentario/512536/) 

	excelente curso Eduardo! felicitaciones

* **Mauricio Quiñones** (1) [77786](https://platzi.com/comentario/909686/) 
Buena tarde, al correr ng buid obtengo el siguiente error: “An unhandled exception occurred: Call retries were exceeded See “C:\Users\and...

* **HatsuDopple** (1) [64323](https://platzi.com/comentario/674201/) 
y si yo tengo un dominio ya comprado en godaddy o en otro servidor, Como se puede relacionar ese dominio a mi proyecto front end?

* **Gabriel Solorzano** (1) [55178](https://platzi.com/comentario/538429/) 
En el curso Angular 4 se dió esta misma clase pero en las opciones de $ firebase init SOLO SE ELIGIÓ HOSTING. Ahora el p...

	* **Alex Eugenio Gavidia Donayre** [55178] (1)

		La diferencia es utilizar lo que necesitas. Simple.

# Conclusión [2356]

## 0620. Conclusión [12801](https://platzi.com/clases/1340-angular-avanzado/12801-conclusion2513/)

### Descripción:


Hemos concluido el Curso de Angular Avanzado. Ya sabes como crear una aplicación funcional completa y empaquetarla para ser instalada en Windows, Mac o Linux con Electron, o publicarla en el hosting de Firebase para que todos la vean.

¡Felicitaciones!

### Comentarios:

* **Spyderp** (4) [466782](https://platzi.com/comentario/466782/) 

	es de los mejores profesores de platzinger

* **Steven18** (3) [622764](https://platzi.com/comentario/622764/) 
Muy buen curso 👌

* **lcollazos** (1) [1020945](https://platzi.com/comentario/1020945/) 

	Excelente!  
	Buen curso y excelente profesor. Gracias!!

* **ehnbytes** (1) [1018259](https://platzi.com/comentario/1018259/) 

	Excelente curso!!

* **TeddySipraM** (1) [997781](https://platzi.com/comentario/997781/) 

	<https://platzisquare-1571801316942.firebaseapp.com/login>  
	Excelente curso

* **Manuel Andrade** (1) [805872](https://platzi.com/comentario/805872/) 

	Excelente curso!

* **Elberth Jair Agreda Rosero** (1) [780995](https://platzi.com/comentario/780995/) 

	Muy buen curso, muy completo

* **Wilson Marino Pablo Mendez** (1) [742253](https://platzi.com/comentario/742253/) 

	Excelente curso…

* **Gabriel Uviedo** (1) [720394](https://platzi.com/comentario/720394/) 

	<https://platzinger-324fc.firebaseapp.com/> 😄

* **Gabriel Uviedo** (1) [720392](https://platzi.com/comentario/720392/) 

	Excelente curso!

* **carlos mauricio severiche** (1) [672014](https://platzi.com/comentario/672014/) 

	Muy buen curso y bien explicado.

* **juanbarcinilla** (1) [648403](https://platzi.com/comentario/648403/) 

	Excelente curso.

* **Alex Eugenio Gavidia Donayre** (1) [553801](https://platzi.com/comentario/553801/) 

	Excelente profesor, muchas gracias!!!  
	Con tan sólo 3 meses en platzi, pude aumentar mis ingresos !!  
	GRACIAS!!

* **Luis Javier Quijije Parrales** (1) [539071](https://platzi.com/comentario/539071/) 

	Super largo, pero bien explicado.!!

* **Jose David Ocaña Ballester** (1) [468032](https://platzi.com/comentario/468032/) 

	El curso esta muy bien explicado, Eduardo es un excelente profesor 😃

* **Jecsham Castillo** (1) [450312](https://platzi.com/comentario/450312/) 

	Finalmente!

* **Jeffry Davila** (1) [413609](https://platzi.com/comentario/413609/) 

	Me encanto este curso.

* **edu1590** (1) [411780](https://platzi.com/comentario/411780/) 

	Genial curso, el temario esta excelente y el modo de llevarlo aun mas. Hacer un ejemplo practico e interesante asi como disponer del repositorio lo hace una grata experiencia de aprendizaje.

* **Ray L. Rojas Enciso** (1) [406887](https://platzi.com/comentario/406887/) 

	Disculpa en conclución una Single Page Application es una aplicación que puede ser descargada con un un simple wget?

	* **Miguel Gil Rosas** [406887] (1)

		Hola.  
		Generalizando mucho, una Single Web Application es aquella aplicación Web con páginas cuyo contenido se define en el cliente (el navegador) por un programa que normalmente va incluido o se referencia en la propia página en Javascript. En contraposición a la aplicación Web clásica cuyas páginas se definen en el servidor y en el cliente sólo se muestran sin modificarse.  
		Espero te sirva, saludos.

	* **Miguel Gil Rosas** [406887] (1)

		Perdona, al final no contesté claramente. Si la SPA va toda incluida en un sólo fichero (HTML, CSS y/o Javascript) sin referencias a ficheros externos, sí te la puedes bajar con un simple wget, después la corres en el navegador y listo.  
		Saludos.

* **juan camilo castillo saucedo** (1) [401862](https://platzi.com/comentario/401862/) 

	Excelente este curso 🤘

* **Carlos Uriel de Jesus Sánchez González** (1) [399844](https://platzi.com/comentario/399844/) 

	Muchas Gracias, muy buen curso.

* **carlosextra1** (1) [394477](https://platzi.com/comentario/394477/) 

	Gracias excelente curso!!!

* **OSCAR ALFREDO CHAFLOQUE TAMPECK** (1) [68481](https://platzi.com/comentario/741200/) 
si quiero actualizar el deploy repito todos los pasos o basta con un ng-build y un deploy

* **Ray L. Rojas Enciso** (1) [44327](https://platzi.com/comentario/406887/) 
Disculpa en conclución una Single Page Application es una aplicación que puede ser descargada con un un simple wget?

	* **Miguel Gil Rosas** [44327] (1)

		Hola.  
		Generalizando mucho, una Single Web Application es aquella aplicación Web con páginas cuyo contenido se define en el cliente (el navegador) por un programa que normalmente va incluido o se referencia en la propia página en Javascript. En contraposición a la aplicación Web clásica cuyas páginas se definen en el servidor y en el cliente sólo se muestran sin modificarse.  
		Espero te sirva, saludos.

* **Juan** (0) [777204](https://platzi.com/comentario/777204/) 

	Excelente Profe!!! muy buen curso justo lo que estaba buscando!!

## 0630. Cuéntanos [12803](https://platzi.com/clases/1340-angular-avanzado/12803-cuentanos/)

### Descripción:


Has llegado al final de este curso y nos encantaría saber qué piensas:

¿Qué ventajas le ves a Angular?  
¿Qué desventajas?  
¿Cómo lo implementarías en un app que tengas pensado desarrollar?

Escríbenos en Twitter a [@platzi](https://twitter.com/platzi) y [@iBar_Ed](https://twitter.com/ibar_ed) tus respuestas, estaremos pendientes.

### Comentarios:

* **Juan Antonio Baracat** (2) [366660](https://platzi.com/comentario/366660/) 

	¿Qué ventajas le ves a Angular?  
	Las ventajas que veo en Angular es que es un Framework muy maduro y estable, nos propone una arquitectura muy bien pensada y nos brinda las funcionalidades que casi todos los proyectos lo quieren.  
	¿Qué desventajas?  
	Como todo Framework tiene su curva de aprendizaje, no lo recomiendo para proyectos pequeños…  
	¿Cómo lo implementarías en un app que tengas pensado desarrollar?  
	Tengo pensando usar Angular en proyectos medianos y grandes.

* **williamleonardogarciarueda** (1) [1005384](https://platzi.com/comentario/1005384/) 

	Angular me parece una excelente tecnología para desarrollo de aplicaciones. Nos preocupa un poco en mi empresa que la actualización tan frecuente de versiones traiga algunas dificultades con nuestros clientes.

* **TeddySipraM** (1) [997786](https://platzi.com/comentario/997786/) 

	Actualmente lo utilizamos en la empresa que laboro, con un sistema ERP en perú con facturación electronica  
	app.sauri.app, hasta el momento la unica desventaja que veo a angular es el tiempo de carga de la aplicación ya que por la cantidad de componentes y modulos que tenemos es muy pesado, pero gracias a los cursos ya estamos haciendo mejoras en la aplicacióin

* **kmancera** (1) [869640](https://platzi.com/comentario/869640/) 

	Ventajas
	
	* es que tiene muchas herramientas para agilizar el desarrollo
	* Una gran comunidad para encontrar información
	* Framework robusto y confiable por su gran constructor Google  
	Desventajas
	* Es pesado porque carga todo un las herramientas de angular asi no las usemos
	* Al tener tantas herramientas, ya se vuelve muy template, toca seguir todo paso a paso.
	
	
	
	Usuaria angular con bootstap y adicional usaria rxjs para manejar el estado de la aplicacion

* **Kalin** (1) [859334](https://platzi.com/comentario/859334/) 

	A lo mejor no tengo mucha experiencia pero no le veo ningun desventaja.  
	lo aplicaría para un sistema de entregas que actualmente lo llevo manual.

* **caprilespe** (1) [827783](https://platzi.com/comentario/827783/) 

	¿Qué ventajas le ves a Angular?  
	Es un framework bastante versátil, fácil de usar, con distintas funcionalidades y que permite el desarrollo de aplicaciones móviles y aplicaciones desktop con electron
	
	¿Qué desventajas?  
	Una de las desventajas que le veo es su curva de aprendizaje que es algo difícil y sus distintas versiones que han causado muchos cambios y a veces crea problemas de compatibilidades.
	
	¿Cómo lo implementarías en una app que tengas pensado desarrollar?
	
	Seria interesante desarrollar una aplicación crossplatform del lado web con angular y crear aplicaciones móviles con ionic.

* **WALTER RAUL CANCHAN HERMOZA** (1) [813105](https://platzi.com/comentario/813105/) 

	Me encanto el curso, excelente profesor, este el resultado del curso: <https://platzinger-b8062.firebaseapp.com/> Gracias por compartir estos conocimientos…

* **Elwyn Cumpa** (1) [786411](https://platzi.com/comentario/786411/) 

	Excelente curso, abarcando los puntos principales en este lenguaje.

* **Gabriel Uviedo** (1) [720395](https://platzi.com/comentario/720395/) 

	Me gustó mucho el curso, cubrio varios temas y se salió de Angular para dar inicio a otros conocimientos. Excelente!

* **ma74ny** (1) [709980](https://platzi.com/comentario/709980/) 

	Excelente curso, muy bien explicado. Cubrió varios aspectos y despejó muchas dudas!

* **carlos mauricio severiche** (1) [672016](https://platzi.com/comentario/672016/) 

	Muy buen curso y bien explicado, seguiré profundizando más para seguir aprendiendo.

* **Christian Michelle Torres Martínez** (1) [646413](https://platzi.com/comentario/646413/) 

	Excelente curso, no sabía lo interesante que puede llegar a ser angular y la manera de explicar Eduardo, magnifico

* **Brandon Iván Quiroa Loarca** (1) [628890](https://platzi.com/comentario/628890/) 

	No sabia que tan poderoso podia ser angular, hasta que decidi tomar los cursos de Eduardo. Buenisimos por cierto!

* **Ruben Garcia** (1) [598624](https://platzi.com/comentario/598624/) 

	Angular es un framework bastante completo y ademas su estructura permite tener el código organizado.
	
	Creo que su curva de aprendizaje es mayor a otros framework de js.

* **cesarcadavid** (1) [591304](https://platzi.com/comentario/591304/) 

	Angular nos permite de forma organizada poder desarrollar nuestro front, mantener un estándar y todo mucho mas organizado, me gustaría desde ahora implementarlo en todos mis desarrollos personales, es un framework muy poderoso y con mucho futuro, gracias

* **Brayan Andres Gallego Cardona** (1) [571680](https://platzi.com/comentario/571680/) 

	¿Qué ventajas le ves a Angular?
	
	* Es un framework muy potente y se pueden hacer muchas cosas con el.
	* Se puede ajustar a las necesidades que tengamos.  
	¿Qué desventajas?
	* Es algo complejo de usar si eres muy nuevo en programación.  
	¿Cómo lo implementarías en un app que tengas pensado desarrollar?
	* lo pienso utilizar en un aplicativo web para mi negocio.
	
	

* **Fernando Rocha Olivera** (1) [561977](https://platzi.com/comentario/561977/) 

	¿Qué ventajas le ves a Angular?  
	arquitectura muy simple de utilizar.  
	¿Qué desventajas?  
	el versionamiento de librerias  
	¿Cómo lo implementarías en un app que tengas pensado desarrollar?  
	actualmente estoy haciendo mi tesis con angular y con un web service en .netCore

* **Luis Javier Quijije Parrales** (1) [539076](https://platzi.com/comentario/539076/) 

	¿Qué ventajas le ves a Angular?
	
	* Puedo crear SPA de una manera mas intuitiva.
	* Al combinar con firebase el realtime es sorprendente para dejar de usar [socket.io](http://socket.io) de node.
	* Permiter usar gran cantidad de controles de terceros.
	* El ngserve es increible, ya no tengo q hacer refresh.  
	¿Qué desventajas?
	* Definitivamente es para developers pro.  
	¿Cómo lo implementarías en un app que tengas pensado desarrollar?
	* Actualmente estoy creando una SPA para un cliente de trade-marketing y como bckend uso firebase firestore.
	
	

* **Gabriel Solorzano** (1) [538424](https://platzi.com/comentario/538424/) 

	Muy bueno el curso Eduardo, congrats!!!
	
	Me trae tantos recuerdos mi viejo Messenger, y poder replicarlo ha sido un gran aprendizaje.
	
	Ventajas a Angular le veo muchísimas, tiene una gran comunidad, una gran empresa que le da soporte, y esto me ha ayudado a definirme entre tanto mar de frameworks JS.
	
	Desventajas, pues como todo, nada es eterno en el mundo pero definitivamente es un gran framework. Quién sabe que estaremos viendo por ahì en el el 2029.
	
	De implementarlo, por supuesto, como front-end para la web, y eso de Electron abre un mundo de posibilidades para crear “programas ejecutables windows”.

* **Edison Jhon Moya Arias** (1) [477578](https://platzi.com/comentario/477578/) 

	La mayor ventaja es la estructura que se sigue al programar con este framework, debido a que establece la forma en la que deben organizarse sus elementos (componentes, service, modules, etc).  
	La desventaja es que te ves obligado a usar typescript para su desarrollo.  
	Como punto final quisiera recomendar algo para futuros cursos de angular:
	
	* Usar modules para crear agrupaciones de componentes dentro de estos y llevar de mejor manera el codigo.
	* Implementar el desarrollo por ambientes (desarrollo, produccion, etc).
	
	

* **developerresol1** (1) [458551](https://platzi.com/comentario/458551/) 

	¿Qué ventajas le ves a Angular?  
	Es un framework que permite crear single page application, tiene un set de herramientas para generar componentes, servicios, guards y también ejecutar la aplicación en un ambiente local. Evita el código espagueti  
	¿Qué desventajas?  
	En lo personal no le encuentro desventajas es muy útil en verdad.
	
	¿Cómo lo implementarías en un app que tengas pensado desarrollar?  
	Para crear un sistema de calificaciones cómodo para las universidades o para trabajar con Big Data con una app de analisis.

* **Jeffry Davila** (1) [413622](https://platzi.com/comentario/413622/) 

	¿ventaja le ves a angular?  
	Es un Framework ,se pueden desarrollar proyectos grandes,tiene buena estética y la manera en como trabaja es decir que trabaja por componentes.
	
	¿Desventajas?  
	Veo que es mas adecuado usarlo para el lado del cliente, también su documentación, es muy confusa, me tomo días resolver uno de los retos.
	
	¿Lo implementaría en un app que tengas pensado desarrollar?  
	-En un portal de notas para una escuela.

* **edu1590** (1) [411783](https://platzi.com/comentario/411783/) 

	¿Qué ventajas le ves a Angular?  
	A mi parecer la curva de aprendizaje no es tan elevada como la de otros frameworks de JS. El uso de Typescript simplifica mucho las cosas para los que venimos de la POO y lenguajes como JAVA.
	
	¿Qué desventajas?  
	La velocidad con la que salen las nuevas versiones hacen que se tenga que estar excesivamente atento a los cambios.
	
	¿Cómo lo implementarías en un app que tengas pensado desarrollar?  
	Ya tengo 3 en mente y una de ellas va con Electron tambien

* **Carlos Uriel de Jesus Sánchez González** (1) [399846](https://platzi.com/comentario/399846/) 

	¿Qué ventajas le ves a Angular?  
	framework muy completo  
	¿Qué desventajas?  
	curva de aprendizaje alta  
	¿Cómo lo implementarías en un app que tengas pensado desarrollar?  
	Muchos proyectos en mi trabajo

