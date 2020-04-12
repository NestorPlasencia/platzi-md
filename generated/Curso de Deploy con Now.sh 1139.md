[Curso de Deploy con Now.sh 1139](https://platzi.com/cursos/deploy-now)

# Introducción al Cursos de Deploy con Now.sh [1481]

## 0010. Componentes de una aplicación [8403](https://platzi.com/clases/1139-deploy-now/8403-componentes-de-una-aplicacion/)

### Descripción:


Una aplicación web moderna se divide en varias partes, algunas aplicaciones tienen más que otras, en este curso vamos a ver alguna:

* Archivos estáticos o Frontend. Estos archivos son enviados al usuario a través de un CDN.
* Backend for Frontend. Este es el servidor que pide datos al API y responde HTML al usuario.
* Backend API. Puede estar hecho en cualquier tecnología e incluso puede estar dividido en múltiples aplicaciones pequeñas encargadas de distintas responsabilidades cada una.
* Bases de Datos. Puede estar hecha en lo tecnología de BD que sea y pueden existir diferentes bases de datos creadas en distintas tecnologías.



## Definiciones importantes:

* CDN = Content Delivering Network. Muchos servidores distribuidos por todo el mundo proveer de estos archivos comunes y que no están generados dinámicamente a nuestros usuarios y que puedan acceder rápidamente a ellos.
* API = Aplication Programming Interface. Representa la capacidad de comunicación entre componentes de software.



### Comentarios:

* **Joaquin Araujo** (19) [205172](https://platzi.com/comentario/205172/) 

	Actualmente una aplicación “moderna” esta compuesta por varias partes (algunas aplicaciones tienen más que otras), las cuales son:
	
	* **Archivos estáticos o Front-end:** Estos archivos no cambian y son enviados al usuario por medio de un **CDN (Content Delivering Network)** , es decir, por medio de uno de tantos servidores distribuidos por todo el mundo que se dedican a proveer esta clase de archivos con el fin de ayudar con la carga de la página y una mejor **UX**.
	* **Backend for Frontend:** Es el servidor que tiene como tarea pedir datos al **API** y al obtenerlos enviarlos al usuario como **HTML**.
	* **Backend API (Aplication Programming Interface):** Es el núcleo de la aplicación, este puede estar hecho en cualquier lenguaje de programación e incluso puede estar distribuido en microservicios y cada uno encargarse de una tarea en especial.
	* **Bases de datos (DB):** Es donde se almacena los datos de la aplicación, puede ser cualquier base de datos e incluso puede ser más de una.
	
	![](http://www.paginaswebs.com/wp-content/uploads/2017/02/desarrollo-aplicaciones-web.png)
	
	Si necesitas una guía y resumen del curso [aquí](https://joaquinaraujo.github.io/deploy-now) la tienes.

* **ivanguerra10** (5) [194272](https://platzi.com/comentario/194272/) 

	Muy clara explicacion!! Iniciando este excelente curso

* **Sergio Minei** (4) [349116](https://platzi.com/comentario/349116/) 

	## Flujo de una Aplicación Web
	
	![Flujo de una app web](https://raw.githubusercontent.com/MineiToshio/CursosPlatzi/master/Curso%20de%20Deploy%20con%20Now.sh/img/flujo-app-web.png)
	
	¿Cómo es el flujo de un usuario en una aplicación?
	
	  1. El usuario accede al backend for frontend.
	  2. El backend for frontend le pide los datos al backend API.
	  3. el backend API va a leer los datos de la base de datos.
	  4. La base de datos le va a dar la respuesta de su query.
	  5. El backend API va a parsear los datos en un json.
	  6. El backend API envía el json al frontend.
	  7. El frontend genera con el json el HTML.
	  8. El frontend envía el HTML al usuario.
	  9. El usuario va a descargar los estáticos de frontend.
	  10. El usuario recibe el css, js, imágenes, etc.
	  11. Con el js descargado, el usuario puede iniciar una aplicación del lado de cliente.
	  12. El js se puede conectar directamente con el backend API e interactuar directamente sin pasar por el backend for frontend.
	
	
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Deploy%20con%20Now.sh)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.

* **Jesús Israel Contreras Urquiola** (4) [194704](https://platzi.com/comentario/194704/) 

	Excelente muy buen comienzo.

* **Favio Náquira** (3) [555753](https://platzi.com/comentario/555753/) 

	No me gusta el inicio del curso, porque no se explica que se va a realizar…

* **Oswaldo Peralta** (2) [73394](https://platzi.com/comentario/834215/) 
Estimados, este curso de Now.sh està bastante desactualizado por lo que me ha resultado dificil hacer el depl...

	* **Erik Ochoa (Platzi)** [73394] (2)

		Tienes razón en que hay cosas de este curso que ya no aplican. Mira hay una [clase](https://platzi.com/clases/1646-backend-nodejs/22258-despliegue-en-now/) en el **Curso de Backend con Node.js** en la que se hace deploy con [Now.sh](http://Now.sh), tal vez eso te pueda servir.
		
		Mi otra sugerencia es que vayas paso por paso tratando de hacer el proceso y nos comentes con qué error te vas encontrando, así te podemos ayudar paso a paso.
		
		No olvides adjuntar código y se se puede una captura de pantallas.

* **Wilson Marino Pablo Mendez** (1) [780718](https://platzi.com/comentario/780718/) 

	Excelente!!

* **Alejandro Robleto** (1) [765634](https://platzi.com/comentario/765634/) 
	
	![Captura de pantalla 2019-10-03 a la\(s\) 15.48.53.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-10-03%20a%20la%28s%29%2015.48.53-ade34d4d-e2ea-4e36-bf2e-ad7d8a7665c4.jpg)

* **j2rojasr** (1) [674806](https://platzi.com/comentario/674806/) 

	Lo de Backend for Frontend no me quedó muy claro. ¿Alguien me podría dar un ejemplo práctico y en qué casos es conveniente usarlo? 😅

	* **CrifQui** [674806] (1)

		Simplemente son aplicaciones que solicitan datos a un Api y solo te devuelve las vistas correspondientes a los datos que pudes, ejemplo una aplicación de clima que se conecta con api que le envía los datos necesarios para que el usuario pueda verlos reflejados en su navegador por medio de html, csss y lo que tenga.

	* **CrifQui** [674806] (1)

		Simplemente son aplicaciones que solicitan datos a un Api y solo te devuelve las vistas correspondientes a los datos que pudes, ejemplo una aplicación de clima que se conecta con api que le envía los datos necesarios para que el usuario pueda verlos reflejados en su navegador por medio de html, css y lo que tenga.

* **Jhon Alexander Perez Valencia** (1) [599268](https://platzi.com/comentario/599268/) 

	## 💪😎🤳
	
	## 🦵💈🌂

* **Jhon Alexander Perez Valencia** (1) [599266](https://platzi.com/comentario/599266/) 

	Muy buena explicación 💪😎🤳

* **Sebastian Medina** (1) [598162](https://platzi.com/comentario/598162/) 

	Pueden haber aplicaciones donde no exista el backend for frontend? x ejemplo cuando desarrollo en angular o React cual es el backedn for frontend ??? muchas gracias

* **Hector Daniel Hernandez Castillo** (1) [544835](https://platzi.com/comentario/544835/) 

	Esto es lo que estaba buscando :3

* **Andres Rodriguez Escudero** (1) [436044](https://platzi.com/comentario/436044/) 

	Hola… donde puedo leer sobre el termino de Backend for frontend, nunca lo había escuchado y me interesaría saber mas acerca de el

	* **kaia_6** [436044] (1)

		Hola, este articulo me pareció interesante: <https://docs.microsoft.com/en-us/azure/architecture/patterns/backends-for-frontends>

* **Felipe Acosta** (1) [280173](https://platzi.com/comentario/280173/) 

	HEEE que bueno ver de nuevo a Colo dando cursos !!

* **Jonhatan Fajardo** (1) [194985](https://platzi.com/comentario/194985/) 

	Excelente curso… Tengo una aplicación desarrollada en React JS y el Backend en Django, mi duda es como hago para actualizar el cliente cada vez que subo un cambio al servidor sin necesidad de refrescar el browser?  
	Muchas gracias

	* **sergiodxa** [194985] (4)

		Si tenés bien separados tu backend de tu frontend es fácil, si tu frontend está en su propio deployment y tu backend en otro y se comunican por un API entonces simplemente haces deploy del nuevo backend o del nuevo frontend sin tocar el otro. Por cierto es lo que vamos a hacer en el proyecto.

	* **Jonhatan Fajardo** [194985] (0)

		Muchas gracias

* **Navarrock33** (0) [246349](https://platzi.com/comentario/246349/) 

	Base de datos

* **Navarrock33** (0) [246347](https://platzi.com/comentario/246347/) 

	Backend API

* **Navarrock33** (0) [246343](https://platzi.com/comentario/246343/) 

	El Back-end for Front-end

* **Navarrock33** (0) [246338](https://platzi.com/comentario/246338/) 

	Los archivos estáticos el Front-end 

* **Isaac Aranda Maldonado** (0) [238483](https://platzi.com/comentario/238483/) 

	Hola, genial el curso, pero aun no entiendo bien los conceptos o a que hacen referencia en nuestro aplicativo web :
	
	* Archivos estáticos o Frontend
	* Backend for Frontend
	* Backend API
	* Bases de Datos (Este punto lo entiendo)
	
	
	
	Muchas Gracias de antemano!

	* **Diego Alexander Forero Higuera (Platzi)** [238483] (5)

		Archivos estáticos => Son los archivos que pertenecen a tu aplicación como las hojas de estilo, fuentes, imágenes y código JavaScript.
		
		Backend for Frontend => Se encarga de entregar un html listo para ser mostrado al usuario con base en la petición al servidor, es útil por ejemplo cuando se tiene desactivado JavaScript en el navegador para que todo se vea de la manera correcta.
		
		Backend API => Es el servidor al cual se le hacen las peticiones de información, tiene endpoints o rutas, por ejemplo cuando haces peticiones a un servicio API REST como <https://swapi.co/>

	* **Isaac Aranda Maldonado** [238483] (0)

		Muchas Gracias colega!!

* **Danilo Josué Huacón Aguirre** (0) [197018](https://platzi.com/comentario/197018/) 

	No puede ser que haya pagado 29$ por un profesor así…

	* **Omar Enrique Crespo Merchan** [197018] (15)

		tu pagaste menos de 0.29$ por este curso, Platzi te ofrece mas de 150 cursos que podras ver, si sientes que este plataforma no te gusta:  
		1- Mal hecho por pagar sin verte uno de los cursos gratis!  
		2- Si tu suscripción lleva poco tiempo y no planeas usarla mas contacta al #TeamPlatzi y comenta tu inconveniente a ver si te cancelan la suscripción y hacen un reembolso
		
		PD: Un poco de respeto hacia el profe, que el es una persona como tu y yo, y merece respeto!

* **Omar Enrique Crespo Merchan** (0) [194282](https://platzi.com/comentario/194282/) 

	a ver que tal ^-^

* **fersot7** (0) [194234](https://platzi.com/comentario/194234/) 

	Iniciando a ver el contenido del curso…

## 0020. Opciones para hacer Deploy [8404](https://platzi.com/clases/1139-deploy-now/8404-opciones-para-hacer-deploy/)

### Descripción:


Estas son algunas de las opciones para llevar una aplicación a producción:

**- Amazon Web Services **(Control en la infraestructura)  
**\- Microsoft Azure** (Control en la infraestructura)  
**\- Google Cloud Platform** (Control en la infraestructura)  
**\- Heroku** (Sin control en la infraestructura)  
**\- Digital Ocean** (Control en la infraestructura)  
**\- GitHub Pages** (Para sitios estáticos)  
**-[Surge.sh](http://Surge.sh)** (Para sitios estáticos)  
**\- Zeit Now** (Sin control en la infraestructura)

### Links:

* [AWS | Cloud Computing - Servicios de informática en la nube](https://aws.amazon.com/es/)

* [Microsoft Azure: plataforma y servicios de informática en la nube](https://azure.microsoft.com/es-mx/)

* [Cloud Computing Services  |  Google Cloud](https://cloud.google.com/)

* [Cloud Application Platform | Heroku](https://www.heroku.com/)

* [DigitalOcean â?? The developer cloud](https://www.digitalocean.com/)

* [GitHub Pages | Websites for you and your projects, hosted directly from your GitHub repository. Just edit, push, and your changes are live.](https://pages.github.com/)

* [Surge](https://surge.sh/)

* [Now - ZEIT](https://zeit.co/now)

### Comentarios:

* **Joaquin Araujo** (24) [205179](https://platzi.com/comentario/205179/) 

	Actualmente existen muchas empresas que se dedican a venderte _“un lugar en Internet estable, escalable y seguro”_ , las más famosas por su buena calidad de servicio son:
	
	* **Amazon Web Services (AWS):** Se tiene control de la infraestructura (IaaS).
	* **Microsoft Azure (Azure):** Se tiene control de la infraestructura (IaaS).  
	Google Cloud Platform (Google Cloud): Se tiene control de la infraestructura (IaaS).
	* **Digital Ocean (Digital Ocean):** Se tiene control de la infraestructura (IaaS).
	* **GitHub Pages (gh-pages):** Funciona solo para hostear archivos estáticos, es decir el Frontend de una aplicación.
	* **Google Firebase (Firebaseapp)**Tiene varios servicios pero entre ellos un hosting. Funciona solo para hostear archivos estáticos, es decir el Frontend de una aplicación.
	* **Heroku (Heroku):** No se tiene control de la infraestructura (PaaS).
	* **Zeit Now ([Now.sh](http://Now.sh)):** No se tiene control de la infraestructura (PaaS).  
	**¿Por que elegir[Now.sh](http://Now.sh) por encima de otros?** Zeit Now funciona con Nodejs, puede contener archivos estáticos y **soporta Docker**. Algunas de sus características son:
	* Es fácil (sólo un comando basta).
	* Escala automáticamente.
	* Deploy inmutable.
	* Deploy sin caída.
	* Deploy ilimitados.
	* HTTP2 automáticamente.
	* Certificado SSL gratis.
	* Logs por deploy.
	* DNS (zeit.world).
	* Permite comprar dominios por CLI.
	
	
	
	Si necesitas una guía y resumen del curso [aquí](https://joaquinaraujo.github.io/deploy-now) la tienes.

	* **Luis Enrique Galindo Arenas** [205179] (0)

		Excelente aporte, gracias por la iniciativa, saludos desde Maturín!

	* **Joaquin Araujo** [205179] (1)

		Epale, saludos desde Maracaibo!

	* **Jesus Sandrea** [205179] (0)

		Saludos desde Maracaibo! 😃

	* **Nelson Meza** [205179] (0)

		Zeit Now ([Now.sh](http://Now.sh)): No se tiene control de la infraestructura (PaaS).  
		¿Por que elegir [Now.sh](http://Now.sh) por encima de otros? Zeit Now funciona con Nodejs, puede contener archivos estáticos y soporta Docker. Algunas de sus características son:  
		Es fácil (sólo un comando basta).  
		Escala automáticamente.  
		Deploy inmutable.  
		Deploy sin caída.  
		Deploy ilimitados.  
		HTTP2 automáticamente.  
		Certificado SSL gratis.  
		Logs por deploy.  
		DNS (zeit.world).  
		Permite comprar dominios por CLI.

* **Sergio Minei** (5) [349125](https://platzi.com/comentario/349125/) 

	## Opciones para hacer deploy
	
	* **[Amazon Web Services](https://aws.amazon.com/es/)** : Es el más grande de todas las opciones para hacer deploy.
	* **[Microsoft Azure](https://azure.microsoft.com/)** : Es muy buenas para deploys con MS SQL y C#.
	* **[Google Cloud Platform](https://cloud.google.com/)** : Tiene un montón de servicios. Una ventaja es que tiene varias API propias de Google que se pueden integrar en la aplicación.
	* **[Heroku](https://www.heroku.com/)** : permite hacer deploy sin tener que pensar en cómo va a funcionar al app por debajo ni la infraestructura de esta.
	* **[Digital Ocean](https://www.digitalocean.com/)** : permite tener un servidor privado y empezar a encontrar todo lo que se quiere ahí.
	* **[GitHub Pages](https://pages.github.com/)** : Permite hacer el deploy de archivos estáticos. Es completamente gratis pero el código es open source.
	* **[Surge.sh](https://surge.sh/)** : Permite hacer deploys estáticos muy fácilmente por medio de un CLI.
	* **[Zeit Now](https://zeit.co/now)** : Es una plataforma para hacer deploy de todo tipo de aplicaciones. No permite hacer deploy de base de datos.
	
	![Opciones de Deploy](https://raw.githubusercontent.com/MineiToshio/CursosPlatzi/master/Curso%20de%20Deploy%20con%20Now.sh/img/plataforma-deploy.png)
	
	Control de la infraestructura se referiere a poder controlar cómo funciona la aplicación por debajo:
	
	* ¿Cuántos servidores hay?
	* ¿Qué tipo de servidores son?
	* ¿Qué hardware tienen?
	
	
	
	## ¿Por qué Zeit Now?
	
	**Tipos de deploy** :
	
	* Aplicación de Node.js
	* Sitios estáticos
	* Contenedores de Docker
	
	
	
	**Deploy fáciles** :
	
	* Con un comando: `now`
	* con un drag & drop con el cliente.
	
	
	
	**Características** :
	
	* Es fácil. Todo se hace con un solo comando.
	* Escala automáticamente. Se crean instancias dependiendo del tráfico de la aplicación.
	* Deploy inmutable. Cada deploy genera una url única.
	* Deploy sin caída. Al escalar automáticamente y generar una nueva url en cada deploy, se puede asegurar la continuidad de la aplicación.
	* Deploy ilimitados.
	* HTTP2 automáticamente.
	* Certificado SSL gratis.
	* Logs por deploy.
	* DNS (zeit.world).
	* Permite comprar dominios por CLI.
	
	
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Deploy%20con%20Now.sh)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.

* **Jemd** (2) [817121](https://platzi.com/comentario/817121/) 

	No se hacer deploys asi que estoy acá, a darle al curso!

* **Andres Roberto Coello Goyes** (2) [791378](https://platzi.com/comentario/791378/) 

	yo casi siempre utilizo now pero concentado a un repositorio de github asi cada vez que yo realice un PUSH automaticamente now empieza hacer el deploy…

* **MauricioF** (2) [676933](https://platzi.com/comentario/676933/) 

	Netlify es otro servicio para hacer deploy de sitios estáticos. Puede conectarse a la cuenta de Github, de tal manera que puede ser actualizada aprovechando las ventajas de Git.

* **platzerito02112019 platzerito02112019** (2) [607970](https://platzi.com/comentario/607970/) 

	Bueno parece que por fin voy a poder hacer Deploy de mi Platzigram en curso de Django que allá no pude…

* **Damian Spizzirri** (2) [373939](https://platzi.com/comentario/373939/) 
Zeit now es gratis?? Y si es gratis, porque te dan todo eso?? Cual es el negocio??. 🤔

	* **Eduardo Hidalgo Díaz Rugama** [373939] (3)

		no te sirve para montar app pesadas. para eso ya tendrías que acudir a sus servicios con costo. si tienes una pagina simple, pequeña y ligera, entonces no te costará nada
		
		te cobran por el peso de tu app, el consumo de logs, el consumo de ancho de banda, el tamaño máximo por archivo, etc. si excedes eso, vas a pago.

	* **venusarcana** [373939] (1)

		nunca, jamas, nada es gratis

	* **Eduardo Hidalgo Díaz Rugama** [373939] (1)

		tu sigue con tu forma de pensar bro. No dije “todo es gratis”, y hablamos de un servicio muy puntual con modelos de negocio muy puntuales. Si hay cosas gratuitas, tal ves no lo que uno quiere es gratis, pero servicios tecnológicos por lo usual ofrecen pruebas gratuitas de sus servicios o consumo gratuito bajo cierto rango de uso. Relajate dude (:

* **Juan Teixeira** (1) [1100806](https://platzi.com/comentario/1100806/) 

	De momento estoy haciendo app web estáticas (HTML,CSS,JS) asi que uso GitHub pages.

* **Enrique Devars (Platzi)** (1) [1011698](https://platzi.com/comentario/1011698/) 

	Les recomiendo muchisimo tambien netlify para el deploy de sus aplicaciones

* **Camilo Andrés Santana Lizcano** (1) [894811](https://platzi.com/comentario/894811/) 

	Es muy emocionante estar a punto de dar el salto de tener aplicaciones estáticas ( de juguete) a tener un despliegue de este nivel 😄

* **cjimd90** (1) [841810](https://platzi.com/comentario/841810/) 

	He utilizado por el momento GitHub pages

* **edwintrumpet** (1) [666796](https://platzi.com/comentario/666796/) 

	Yo siempre he usado AWS, S3 para sitios y archivos estáticos y para aplicaciones puede ser un Lightsail, un EC2 o un Elastic Beanstalk.

* **Jhon Alexander Perez Valencia** (1) [599277](https://platzi.com/comentario/599277/) 

	## Opciones para hacer deploy:
	
	* * *
	
	> Con control de la infraestructura
	
	* [Amazon Web Services](https://aws.amazon.com/)
	* [Microsoft Azure](https://azure.microsoft.com/en-us/)
	* [Google Cloud Plaform](https://cloud.google.com/)
	* [Digital Ocean](https://www.digitalocean.com/)
	
	
	
	> Sin control de la infraestructura
	
	* [Zeit](https://zeit.co)
	* [Heroku](https://www.heroku.com/)
	
	
	
	> Sitios Estáticos
	
	* [GitHub Pages](https://pages.github.com/)
	* [Gitlab Pages](https://about.gitlab.com/product/pages/)
	* [Surge](https://surge.sh/)
	
	

* **Jhon Alexander Perez Valencia** (1) [599272](https://platzi.com/comentario/599272/) 

	> vaya vaya es una gran variedad de opciones para hacer el deploy de nuestras aplicaciones.

* **José Gabriel Guzmán Lopéz** (1) [310981](https://platzi.com/comentario/310981/) 

	github se puede trabajar con jekyll

	* **Oscar Barajas Tavares (Platzi)** [310981] (0)

		Si, hay documentación que te permite hacerlo sin ningún problema.
		
		<https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/>

* **José Gabriel Guzmán Lopéz** (1) [310980](https://platzi.com/comentario/310980/) 

	amo heroku :3

* **josé gabriel guzman lopez** (1) [215222](https://platzi.com/comentario/215222/) 

	excelente curso

* **jesusmurf** (1) [209742](https://platzi.com/comentario/209742/) 

	Muy buena explicación, yo tengo poca experiencia en deploy y pensaba hasta ahora que todos estos servicios eran prácticamente iguales.

* **Jazcar Josué  Bravo Rivas** (0) [286021](https://platzi.com/comentario/286021/) 

	Excelente curso y la explicación del maestro es fácilmente comprensible.
	
	Aunque tengo una duda, ¿Cuál es la alternativa que tiene AWS en la que ofrece lo mismo que DigitalOcean por el mismo precio?

	* **Diego Alexander Forero Higuera (Platzi)** [286021] (1)

		Hola es este <https://aws.amazon.com/lightsail/>

* **Eday Alix Gonzalez M** (0) [237234](https://platzi.com/comentario/237234/) 

	Platzi utiliza [Now.sh](http://Now.sh) ?

	* **sergiodxa** [237234] (1)

		Usan AWS y Azure.

* **Marco Lopez** (0) [217088](https://platzi.com/comentario/217088/) 

	Y hay alguna forma de hacer un deploy a un hosting compartido?

	* **davidtoca (Platzi)** [217088] (1)

		Si, la forma depende del servicio en el servicio que contrates, usualmente solo te dan acceso via ftp y el deploy consiste en enviar los archivos, pero algunos servicios tambien te dan acceso a ssh.

	* **Diego Alexander Forero Higuera (Platzi)** [217088] (2)

		Ten en cuenta que en los hosting compartidos por lo general solo te ofrecen PHP, algunos Ruby y Python, muy pocos por no decir ninguno te ofrecen Node, hay uno que es webfaction pero por el costo que pagas hay puedes pagar un vps en digital ocean y administrar todo.

* **ThisQtso** (0) [197463](https://platzi.com/comentario/197463/) 

	Si quiero hacer un e-commerce que servicio seria el mejor?

	* **Joaquin Araujo** [197463] (0)

		Hola, mira te comparto este [curso](https://platzi.com/clases/e-commerce/) de Platzi, seguro que será la mejor respuesta a tu pregunta 😃

* **jsteven** (0) [197019](https://platzi.com/comentario/197019/) 

	Tengo continuos deployment de mi sitio web con Netlify, una opción a qtener en cuenta para autmatizar despliegues de tu app.

* **David Chan** (0) [194247](https://platzi.com/comentario/194247/) 

	Yo tengo una duda sobre el servicio de Zeit Now, yo compro un dominio en X provedor de dominios, y los apunto e Zeit Now, en el panel de Zeit Now tengo tambien servidor de correo?

	* **sergiodxa** [194247] (3)

		Now no da email, pero si apuntas los nameservers a Now o si compras el dominio con Now podés apuntar registros MX a cualquier servicio de email (como gmail).

## 0030. Aplicaciones monolíticas vs microservicios [8408](https://platzi.com/clases/1139-deploy-now/8408-aplicaciones-monoliticas-vs-microservicios/)

### Descripción:


¿Qué son las **aplicaciones monolíticas**?  
Todo el código está en una sola aplicación.

## Ventajas de las aplicaciones monolíticas:

* Buena para aplicaciones pequeñas.
* Fácil de desarrollar.
* Fácil de hacer deploy.
* Fácil para trabajar individual o en equipos pequeños.



## Desventajas de las aplicaciones monolíticas:

* Difícil de mantener a largo plazo.
* Costosa para escalar.
* En caso de un error se puede caer toda la aplicación.
* Más difícil testear.  
-Más difícil de depurar.



¿Qué es un **microservicio**?  
El código dividido en varias aplicaciones.

## Ventajas de los microservicios:

* Fácil de hacer deploy.
* Fácil de escalar.
* Fácil de testear.
* Fácil de depurar.
* En caso de error solo se cae un servicio.
* Se pueden utilizar diferentes tecnologías.



## Desventajas de los microservicios:

* Difícil de orquestar.
* Puede ser lenta la comunicación entre servicios.
* Difícil saber cómo dividir nuestra aplicación.
* Es más costoso de mantener.



## Importante:

**Orquestación y Coreografía de Servicios** = Ambos conceptos se basan en cómo hacer para comunicar nuestros servicios y que todo funcione como si fuera una sola aplicación.

### Comentarios:

* **Joaquin Araujo** (15) [205210](https://platzi.com/comentario/205210/) 

	En las aplicaciones monolíticas todo el código esta en una solo aplicación mientas que una aplicación basada en microservicios divide su código en varias aplicaciones.
	
	![](http://4.bp.blogspot.com/-pFL-IiCushg/VeiQQc7igjI/AAAAAAAABBM/rhaWcQKY9HM/s1600/micro-service-architecture.png)
	
	Si necesitas una guía y resumen del curso [aquí](https://joaquinaraujo.github.io/deploy-now) la tienes.

* **AndresFdelgado** (6) [216233](https://platzi.com/comentario/216233/) 

	En el curso definitivo de JavaScript se construlle una aplicación usando microservicios. De verdad es genial!! super recomentado.

	* **Ronnie Moncayo** [216233] (1)

		Disculpa, tienes el enlace al curso? el buscador no lo encuentra, muchas gracias.

	* **kaia_6** [216233] (1)

		Hola Ronniemh, el curso que menciona es <https://platzi.com/clases/javascript-pro-2016/>

* **Omar Flores Grimontt** (4) [252438](https://platzi.com/comentario/252438/) 

	**Orquestación y Coreografía** : Comunicación entre servicios.
	
	**Orquestación** : El servicio ‘A’ manda peticiones HTTP avisando que ya terminó su tarea. El código de peticiones del servicio ‘A’ depende de la cantidad de servicios a los que deba avisar que terminó su tarea.
	
	**Coreografía** : Servicio general de suscripciones a canales. Los servicios ajenos al servicio ‘A’ van a estar (o no) a la escucha de la finalización de la tarea del servicio ‘A’. No hace falta modificar el código del servicio ‘A’, ya que al agregar un nuevo servicio se pondría éste a la escucha de la finalización de la tarea del servicio ‘A’.

	* **Nelson Meza** [252438] (0)

		Microservicios:
		
		* El codigo separado en multiples aplicaciones.
		
		
		
		Ventajas:
		
		* Facil de deploy.
		* Facil de escalar.
		* Facil de depurar (se revisa el componente correspondiente)
		* En caso de error solo se cae el servicio que tiene el error.
		* Se pueden usar diferentes tecnologias.
		
		
		
		Desventajas:
		
		* Dificil de orquestar.
		* Lenta comunicacion entre servicios.
		* Dificil de dividir nuestra aplicación.
		* Mas costo de mantener.
		
		

* **j2rojasr** (2) [670142](https://platzi.com/comentario/670142/) 

	Desde el minuto 7:35 todo se volvió confuso. Un mejor slide hubiera ayudado mucho. 😑

* **oobie92** (2) [630467](https://platzi.com/comentario/630467/) 

	Otro dato util para el tema de Microservicios es que “Es recomendable que cada microservicio, tenga su propia base de datos”
	
	Saludos

	* **j2rojasr** [630467] (2)

		¿Cual sería el inconveniente si varios microservicios apuntan a una sola BD? Yo he trabajado de esta forma y no he tenido problemas hasta ahora. Y hablo de miles de visitas diarias. 😲

	* **william andres rodriguez borja** [630467] (1)

		Es correcto en el modelo de microservicios cada servicio debe ser modular he independiente.

	* **oobie92** [630467] (1)

		Uno de los inconvenientes de que compartan recursos, que si por X o Y razon un microservicios necesita editas alguna tabla o campo, pueda que esa tabla tambien sea utilizada por otro servicio, ademas que tendrias que involucrar a varios equipos al momento de realizar los cambios

* **jsteven** (2) [197021](https://platzi.com/comentario/197021/) 

	En mi trabajo tenemos una plataforma de 11 microservicios y realizar la orquestación de estos al principio fue todo un reto.

* **Enmanuel Jarquin** (2) [194697](https://platzi.com/comentario/194697/) 

	Mi interpretación de Coreografía es la asignación de eventos a microservicios, en la que el microservicio X tiene asociado un evento que se lanzará cuando el microservicio Y ejecute determinada acción que proboque la descadenación del evento asignado al microservicio X.

* **Luis Fernando Valderrama Gastiaburu** (1) [1078158](https://platzi.com/comentario/1078158/) 

	He trabajado en un proyecto integrando 2 micro-servicios, 1 micro-servicio de autentificación y otro con la lógica de negocio, el usuario final(frontend) accedía a la información por medio de un gateway (grapql) y el principal problema con el que me tope fue: la comunicación.  
	El hecho de que al trabajar con micro-servicios, las partes de cada uno deben estar separadas lo mas que se pueda, porque de no ser el caso, se crean restricciones a nivel de acceso de información y la solución se puede volver dependiente.

* **Wilson Marino Pablo Mendez** (1) [780815](https://platzi.com/comentario/780815/) 

	Justamente quería crear una aplicación basado en microservicios haciendo uso de bases de datos SQL Y NoSQL… El problema que me enfrentaba era unir esos servicios en una sola aplicación.

* **Fernando Azuaje** (1) [672818](https://platzi.com/comentario/672818/) 

	Por lo que entendi la corogrefia es parecido a como funcionan los eventos de js, o en [socket.io](http://socket.io)

* **j2rojasr** (1) [670144](https://platzi.com/comentario/670144/) 

	¿Algún ejemplo práctico sobre “Orquestación y Coreografía de servicios”? 😨

* **Jhon Alexander Perez Valencia** (1) [599283](https://platzi.com/comentario/599283/) 

	## Aplicaciones monolíticas
	
	Todo el código en una sola aplicación.
	
	> Ventajas
	
	* Bueno para aplicaciones pequeñas.
	* Fácil de desarrollar.
	* Fácil de hacerle **deploy**.
	* Fácil trabajar solo o en equipos pequeños.
	
	
	
	> Desventajas
	
	* Difícil de mantener.
	* Costoso de mantener.
	* En caso de un error se puede caer toda la aplicación.
	* Mas difícil de testear.
	* Mas difícil de depurar.
	
	
	
	## Micro servicios
	
	El código dividido en múltiples aplicaciones.
	
	> Ventajas
	
	* Fácil de hacer **deploy**.
	* Fácil escalar.
	* Fácil testear.
	* Fácil de depurar.
	* En caso de error, solo se cae un servicio.
	* Se pueden usar diferentes tecnologías.
	
	
	
	> Desventajas
	
	* Difícil de orquestar.
	* Puede ser lenta la comunicación entre servicios.
	* Difícil saber como dividir nuestra aplicación.
	* Mas costoso de mantener.
	
	

* **Neira Steven** (1) [591293](https://platzi.com/comentario/591293/) 

	Empecé una app en next js pero tiene typescript, voy a intentar subirla a now

* **Julio Cesar Jaramillo Palacios** (1) [204092](https://platzi.com/comentario/204092/) 

	 **Aplicaciones monoliticas y microservicios.**
	
	**Monoliticas: **  
	Todo el codigo esta en un solo servicio.  
	**Ventajas: **  
	\- Aplicacion pequeña.  
	\- Facil de desarrollar.  
	\- Facil de ser deploy.  
	\- Facil de trabajo (Equipo pequeño).  
	**Desventajas:**  
	\- Dificil de mantener.  
	\- Costoso de escalar (separar el codigo).  
	\- En caso de errores la aplicacion se cae.  
	\- Dificil de testear.  
	\- Dificil de depurar (debug).
	
	**Microservicios:**  
	\- El codigo separado en multiples aplicaciones.
	
	**Ventajas:**  
	\- Facil de deploy.  
	\- Facil de escalar.  
	\- Facil de depurar (se revisa el componente correspondiente)  
	\- En caso de error solo se cae el servicio que tiene el error.  
	\- Se pueden usar diferentes tecnologias.
	
	**Desventajas:**  
	\- Dificil de orquestar.  
	\- Lenta comunicacion entre servicios.  
	\- Dificil de dividir nuestra aplicación.  
	\- Mas costo de mantener.
	
	**Uso de servicios de terceros.**
	
	**Orquestación y coreografía de servicios:**  
	\- Cuando termine un proceso se informa que este ya acabo para pasar el siguiente paso.

## 0040. Instalación de Now.sh [8409](https://platzi.com/clases/1139-deploy-now/8409-instalacion-de-nowsh/)

### Descripción:


### Links:

* [Now – Realtime global deployments](https://zeit.co/now)

* [Curso de Desarrollo Web Online | Materiales](https://platzi.com/clases/html5-css3/)

### Comentarios:

* **Daniel Romero** (3) [254336](https://platzi.com/comentario/254336/) 

	Si tienen error en Ubuntu posiblemente sea el SO desactualizado lo prove en versiones anteriores y no deja. en la actual solo deben poner
	
	sudo apt-get install nodejs-legacy  
	sudo apt-get update  
	sudo apt-get upgrade  
	sudo apt-get install npm  
	sudo npm install -g now
	
	En el caso de Windows deben descargar nodejs de la pagina oficial [https://nodejs.org/es/](url) lo ejecutan y con unos cuantos next ya lo tendran listo.  
	Luego abran la terminal de node pueden escribir en inicio “command” y aparecera la terminal de nodejs y ahy ejecutas el comando
	
	npm install -g now

	* **Daniel Romero** [254336] (0)
![Captura.JPG](https://static.platzi.com/media/user_upload/Captura-ba29d177-e15f-471c-b491-8f481f44f41e.jpg)

	* **gersonguillensolano** [254336] (1)

		Entonces se puede usar Now para hacer deploy en una red interna? Es que estoy tratando de hacer un deploy de una app node.js en un servidor del lugar donde trabajo, pero ha sido un dolor de cabeza hasta ahora

* **Alejandro Robleto** (2) [766933](https://platzi.com/comentario/766933/) 
	
	![Captura de pantalla 2019-10-04 a la\(s\) 11.56.20.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-10-04%20a%20la%28s%29%2011.56.20-cd2bb716-ff14-4064-8524-8ccb663e9409.jpg)

* **Alejandro Robleto** (2) [766919](https://platzi.com/comentario/766919/) 
	
	![Captura de pantalla 2019-10-04 a la\(s\) 11.56.00.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-10-04%20a%20la%28s%29%2011.56.00-be15c4e9-2cf4-4870-aced-a0d47f7c658e.jpg)

* **Daniel Garrido** (2) [343485](https://platzi.com/comentario/343485/) 

	Una pregunta [Now.sh](http://Now.sh) tambien puede servir para una app de php laravel?

	* **sergiodxa** [343485] (2)

		Sí claro, sólo necesitas crear un Dockerfile que instale las dependencias de tu app (como laravel) y la inicie exponiendo un puerto.

	* **Daniel Garrido** [343485] (1)

		Ohhh que genial, muchisimas gracias

	* **Cristian Caballero** [343485] (1)

		Pero no tendrias BD en now

* **Jhon Alexander Perez Valencia** (1) [599336](https://platzi.com/comentario/599336/) 

	## instalar now
	
	`$ npm install -g now`

* **Sergio Minei** (1) [349126](https://platzi.com/comentario/349126/) 

	```
	    $ npm install -g now
	    
	```
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Deploy%20con%20Now.sh)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.

* **David Granados** (1) [238576](https://platzi.com/comentario/238576/) 

	me pidio correr el comando asi:
	
	“sudo npm install -g --unsafe-perm now”
	
	porque?

	* **Aaron Delgado** [238576] (2)

		Creo que es un permiso para evitar que los usuarios que no son root instalen paquetes. Algo así como la clasica ventana de windows o mac que dice “Confias en este programa para ejecutarse…”

* **Joaquin Araujo** (1) [205214](https://platzi.com/comentario/205214/) 

	Se utiliza sudo para ejecutar el comando como root, ya que [Now.sh](http://Now.sh) se instala de manera global (-g).

* **Alejandro Robleto** (1) [69998](https://platzi.com/comentario/767338/) 
no puedo entender porque me da este error Error! The content of “~/Library/Application Support/now/auth.json” is invalid. No...

	* **Erik Ochoa (Platzi)** [69998] (1)

		Parece se un problema con tus credenciales, prueba lo siguiente:
		
		  1. borra el archivo `~/Library/Application Support/now/auth.json`.
		  2. Asegurate de tener la última version del CLI de now con `npm install -g now@latest`
		  3. Vuelve a hacer login con el comando `now login`
		
		
		
		Nos cuentas si eso te sirve.

* **Daniel Garrido** (1) [38367](https://platzi.com/comentario/343485/) 
Una pregunta Now.sh tambien puede servir para una app de php laravel?

	* **sergiodxa** [38367] (2)

		Sí claro, sólo necesitas crear un Dockerfile que instale las dependencias de tu app (como laravel) y la inicie exponiendo un puerto.

* **justinmark** (0) [243351](https://platzi.com/comentario/243351/) 

	Hice un pequeño [tutorial](https://medium.com/@markcolling/deploy-was-never-more-fun-with-now-371c89eaf41c) que complementa el video, en el explico como descargar Now Desktop. Se lo recomiendo chicos 😃

* **Carlos Eduardo Diaz Polanco** (0) [212699](https://platzi.com/comentario/212699/) 

	No logro instalar [Now.sh](http://Now.sh) en mi mac.  
	ejecuto:  
	➜ ~ sudo npm install -g now  
	sudo: npm: command not found
	
	tambien sonda  
	➜ ~ sudo npm install i -g now  
	sudo: npm: command not "found

	* **Diego Alexander Forero Higuera (Platzi)** [212699] (2)

		Ya te había respondido y borraste la pregunta.
		
		No tienes instalado npm, revisa que tienes instalado Node el cual instala automáticamente npm

	* **Carlos Eduardo Diaz Polanco** [212699] (1)

		Esa fue la solución, instale Node.js desde la pagina oficial [link ](https://nodejs.org/en/download/)  
		y se activo el gestor de paquetes npm… muchas gracias!!!

* **Oscar Rodrigo Chavez Calderón** (0) [211546](https://platzi.com/comentario/211546/) 

	Alguien ha podido instalar Now en ubuntu? Llevo dias intentandolo. Podrian ayudarme!
	
	root@Rodrigo-PC:/home/rodrigo# npm install -g now  
	/usr/local/bin/now -> /usr/local/lib/node_modules/now/download/dist/now
	
	> now@8.4.0 postinstall /usr/local/lib/node_modules/now  
	>  node download/install.js
	
	sh: 1: node: not found  
	npm ERR! Linux 4.4.0-43-Microsoft  
	npm ERR! argv “/usr/bin/nodejs” “/usr/bin/npm” “install” “-g” "now"  
	npm ERR! node v4.2.6  
	npm ERR! npm v3.5.2  
	npm ERR! file sh  
	npm ERR! code ELIFECYCLE  
	npm ERR! errno ENOENT  
	npm ERR! syscall spawn
	
	npm ERR! now@8.4.0 postinstall: `node download/install.js`  
	npm ERR! spawn ENOENT  
	npm ERR!  
	npm ERR! Failed at the now@8.4.0 postinstall script ‘node download/install.js’.  
	npm ERR! Make sure you have the latest version of node.js and npm installed.  
	npm ERR! If you do, this is most likely a problem with the now package,  
	npm ERR! not with npm itself.  
	npm ERR! Tell the author that this fails on your system:  
	npm ERR! node download/install.js  
	npm ERR! You can get information on how to open an issue for this project with:  
	npm ERR! npm bugs now  
	npm ERR! Or if that isn’t available, you can get their info via:  
	npm ERR! npm owner ls now  
	npm ERR! There is likely additional logging output above.
	
	npm ERR! Please include the following file with any support request:  
	npm ERR! /home/rodrigo/npm-debug.log```

	* **sergiodxa** [211546] (2)

		Intentá agregar `sudo` al instalar.
		
		Otra cosa es que dice qeu no tenés Node, si instalaste Node.js desde `apt-get` entonces se instaló como nodejs, tenés que crear un alias en tu sistema para que `node` ejecuta `nodejs` porque todo el mundo usa `node` y nadie usa `nodejs`.

	* **Oscar Rodrigo Chavez Calderón** [211546] (1)

		Listo ya quedo, instale primero  
		-sudo apt-get install nodejs-legacy  
		-sudo apt-get update  
		-sudo apt-get upgrade  
		-sudo npm install -g now

* **carlinius PD** (0) [199143](https://platzi.com/comentario/199143/) 

	¿Alguien instalo [Now.sh](http://Now.sh) para ubuntu? Si es asi… alguna pista please¡¡¡

	* **Diego Alexander Forero Higuera (Platzi)** [199143] (5)

		Primero tienes que tener instalado node, npm o yarn, luego de eso solo tienes que instalar usando npm
		``` 
		    sudo npm install -g now
		    
		```
		
		o usando yarn
		``` 
		    sudo yarn globaladd now
		    
		```

# Aplicaciones Estáticas [1482]

## 0050. Deploy con GitHub Pages [8410](https://platzi.com/clases/1139-deploy-now/8410-github-pages2811/)

### Descripción:


## Cosas importantes:

* Cuando la barrita está en verde significa que está hecho el deploy. Si la barra está en un color rojo tenue, significa que aún está en proceso.
* Se puede customizar para aparentar ser mucho más poderoso.
* Lo más común es utilizarlo para documentación de librerías.



### Links:

* [GitHub - platzi/invie-responsive: Las guitarras más locas](https://github.com/platzi/invie-responsive)

* [Curso de Desarrollo Web Online | Materiales](https://platzi.com/clases/html5-css3/)

* [Curso de Responsive Design | Materiales](https://platzi.com/clases/responsive-design/)

### Comentarios:

* **Joaquin Araujo** (10) [205216](https://platzi.com/comentario/205216/) 

	Para configurar un dominio en GitHub Pages solo basta crear un archivo con el nombre CNAME el cual debe estar en la raíz del repositorio y en el [[tudominio.com](http://tudominio.com)] y luego en las configuraciones de DNS de tu dominio agregar un CNAME que apunte a la URL [username].github.io.
	
	Si necesitas más información puedes ver este pequeño [tutorial](http://blog.hostdime.com.co/configurar-un-dominio-personalizado-para-github-pages/).

	* **Alejandro Robleto** [205216] (1)

		muy bueno este aporte muchas gracias, mas para lo nuevos como yo que iniciamos con poco gracias joaquin

* **Daniel Portugal Revilla** (6) [228287](https://platzi.com/comentario/228287/) 

	cada clase que avanzo, se vuelve mas adictivo e interesante el curso. vide buscando cobre pero encontré oro! con ganas de aprender GIT y WEB!

	* **Fernando Vallejo** [228287] (1)

		Jajaja me pasa los mismo.

* **Sergio Minei** (2) [349129](https://platzi.com/comentario/349129/) 

	Github Pages se usa mucho para documentar librerías.
	
	  1. Settings
	  2. Ir a la sección Github Pages.
	  3. En source marcar master branch.
	  4. Clic a save.
	  5. Si la barra está en un color rojo tenue, significa que aún está en proceso.
	  6. Cuando la barrita está en verde significa que está hecho el deploy.
	
	
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Deploy%20con%20Now.sh)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.

* **Jhon Alexander Perez Valencia** (1) [599338](https://platzi.com/comentario/599338/) 

	> Una alternativa para **github pages** puede ser **gitlab pages**

* **Alejandro López** (1) [310941](https://platzi.com/comentario/310941/) 

	Puedes utilizar github pages no solo para hacer paginas estaticas puedes hacer poderosas aplicaciones usando Vuejs React o Angular junto con servicios en la nube como Firebase AWS o Azure y funcionan estupendamente bien!!

* **ivanguerra10** (1) [247032](https://platzi.com/comentario/247032/) 

	* El deploy a Github Pages es muy util para archivos estaticos (Frontend: html, css, js, imagenes).
	* Tambien es util para hacer deploy de documentacion de librerias.
	
	

## 0060. Deploy con Surge.sh [8411](https://platzi.com/clases/1139-deploy-now/8411-surge/)

### Descripción:


### Links:

* [Surge](http://surge.sh/)

* [GitHub - platzi/invie-responsive: Las guitarras más locas](https://github.com/platzi/invie-responsive)

### Comentarios:

* **Adrian Garcia Saaib** (1) [664599](https://platzi.com/comentario/664599/) 

	es recomendable hacer esto con proyecto de react, que otros pasos lleva?

* **Sergio Minei** (1) [349130](https://platzi.com/comentario/349130/) 

	Para usar Surge, primero se debe de instalar:
	``` 
	    npm install -g surge
	    
	```
	
	Luego vas a la carpeta del proyecto con la consola.
	
	Escribes el comando `surge`.
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Deploy%20con%20Now.sh)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.

* **fredy bustos** (1) [203084](https://platzi.com/comentario/203084/) 

	Deploy del proyecto de Vue.js básico.  
	[Vue-music](http://vue-music.surge.sh/)

	* **Joaquin Araujo** [203084] (0)

		Aún no he realizado ese curso de Vue.js, ¿ese proyecto es solo Frontend o Backend for Frontend?

	* **fredy bustos** [203084] (1)

		Solo se consume los datos de la API de last-Fm y se muestran con vue.

	* **Joaquin Araujo** [203084] (1)

		Excelnete, muchas gracias 😄

* **Joaquin Araujo** (0) [205226](https://platzi.com/comentario/205226/) 

	Alguien me podría exlicar ¿Que tiene de interesante [Surge.sh](http://Surge.sh)?

	* **fredy bustos** [205226] (0)

		Pues no lo he usado, pero se ve muy interesante para hacer deploy de staticos.

	* **Joaquin Araujo** [205226] (0)

		Pero GitHub Pages también ofrece eso y te deja configurar tu propio dominio, en cambio [Now.sh](http://Now.sh) no, tienes que comprar un plan y el más básico cuesta 15 al mes.

	* **fredy bustos** [205226] (0)

		en now también puedes configurar tu propio dominio.  
		No se si ya terminaste el curso, pero hay una clase donde se muestra como hacerlo. Saludos.  
		[dominioPersonalizado](https://platzi.com/clases/deploy-now/concepto/configuraciones/usar-un-dominio-personalizado/material/)

	* **Joaquin Araujo** [205226] (0)

		Si pero no es gratis a diferencia de GitHub Pages

* **david** (0) [201631](https://platzi.com/comentario/201631/) 

	Me podrían ayudar en como solucionar este error ???![Screen Shot 2017-10-09 at 12.16.40 AM.png](https://static.platzi.com/media/user_upload/Screen%20Shot%202017-10-09%20at%2012.16.40%20AM-aa64a6d4-efcd-4355-b934-8c8f7ab871f6.jpg)

	* **Diego Alexander Forero Higuera (Platzi)** [201631] (1)

		Quita los espacios en el nombre de la carpeta y vuelve a intentarlo.

	* **david** [201631] (0)

		hola, si de echo vi el comentario que contestaste antes a otra persona y hice eso pero aun así sigue sin funcionarme

	* **Kevin Kleber Rivamontan Alvarado** [201631] (2)

		El problema es que estás usando un dominio que está usando alguien más, cambialo, intenta con “invie444” por ejemplo

* **Alexander  Silvera** (0) [194334](https://platzi.com/comentario/194334/) 

	Este es el error:
	
	Surge - [surge.sh](http://surge.sh)
	``` 
	              email: alexandersilvera@hotmail.com
	              token: *****************
	       project path: C:\Users\Acer\Desktop\Curso Responsive Desinge\invie-responsive-master\
	               size: 63 files, 59.8 MB
	             domain: hurt-engine.surge.sh
	    
	    Aborted - you do not have permission to publish to hurt-engine.surge.sh
	    
	```

	* **Diego Alexander Forero Higuera (Platzi)** [194334] (2)

		Prueba cambiando la ruta de tu carpeta, no se pero puede que los espacios en el nombre de la carpeta den problemas, yo como buena costumbre uso `-` o `_` en lugar de espacios, uso Linux y con esto no tengo ningún problema.

	* **Carlos Eduardo Diaz Polanco** [194334] (0)

		a mi tambien me salio el mismo error, y supuse que si todos seguíamos el tuto al pie de la letra, habria un montón de personas con el mismo dominio, por lo que ya estaría ocupado, cambie el nombre del dominio a uno personalizado y funciono… espero que les sirva!

* **Alexander  Silvera** (0) [194333](https://platzi.com/comentario/194333/) 

	cual es el problema que no me reconoce el dominio que coloco en surge desde la terminal?  
	Pongo distintos nombres de dominios y no me los reconoce, los pone como inválidos

	* **Joaquin Araujo** [194333] (0)

		¿Será que ya están en uso?

## 0070. Deploy con Now.sh [8412](https://platzi.com/clases/1139-deploy-now/8412-deploy-con-nowsh/)

### Descripción:


 **Para considerar:**

* Podemos cambiar el nombre de la url que vamos a dar a nuestros usuarios utilizando `now alias`



### Links:

* [Now - ZEIT](https://zeit.co/now)

### Comentarios:

* **Joaquin Araujo** (11) [205454](https://platzi.com/comentario/205454/) 

	Hacer deploy con [Now.sh](http://Now.sh) es algo muy sencillo.
	
	* `now` Ejecuta el deploy (de todos los archivos de la carpeta donde se encuentra posicionado).
	* `now [directorio del proyecto]` Ejecuta el deploy de todos los archivos de la carpeta indicada.
	* `now [user]/[repositorio]` Ejecuta un deploy partiendo de un repositorio en GitHub.
	* `now -e NODE_ENV=production -e MONGODB_PASSWORD=@password` Ejecuta un deploy con variables de entorno.
	* `now alias [URL generada por Now.sh] [URL personalizada].now.sh` Permite crear un alias de la dirección URL.
	
	
	
	Si necesitas una guía y resumen del curso [aquí](https://joaquinaraujo.github.io/deploy-now) la tienes.

	* **Oswaldo Peralta** [205454] (1)

		Excelente guìa. gracias

* **Efrén Sánchez** (3) [434952](https://platzi.com/comentario/434952/) 

	Siempre que hago deploy, lo que me aparece en el browser es lo siguiente:
	
	![Capture.png](https://static.platzi.com/media/user_upload/Capture-92c102c0-6216-4b8c-9d0c-2b53278bc7ae.jpg)
	
	Por qué!!!

	* **Gianfranco Correa** [434952] (2)

		tengo entendido que es por la version de now, hay que especificar algo en now.json creo

	* **Gianfranco Correa** [434952] (2)

		La solución que encontré es crear el archivo ‘now.json’ en el directorio raíz del proyecto. y que contenga esto:
		``` 
		    {
		      "version": 1
		    }
		    
		```
		
		esperemos que actualicen en curso para poder deployar con la versión 2.  
		Un saludo

	* **Efrén Sánchez** [434952] (1)

		Gracias por la respuesta @GianC13. Pero ya hice el archivo now,json y especifiqué la versión:1. Pero nada…

	* **David Isaac Flores Medrano** [434952] (1)

		Yo actualice a la versión 2 y ya sin ningún problema!

	* **jas486** [434952] (1)

		Es debido a que now require una carpeta llamada public

* **Sergio Minei** (2) [349132](https://platzi.com/comentario/349132/) 

	  1. Ir a la capeta del proyecto
	  2. Escribir el comando `now`.
	
	
	
	Si se desea cambiar la url generada se puede hacer de la siguiente manera:
	``` 
	    now alias URL_AUTOGENERADA alias.now.sh
	    
	```
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Deploy%20con%20Now.sh)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.

* **Diego Osorio** (1) [402452](https://platzi.com/comentario/402452/) 

	Como le asigno un dominio a un sitio web estático, tengo algo similar a invie, pero quiero tener un nombre de dominio personalizado?

	* **kaia_6** [402452] (1)

		Hola @Diegoosorio hablan de este tema en la clase: <https://platzi.com/clases/1139-deploy-now/8419-usar-un-dominio-personalizado/>

* **Josué Huancapaza Córdova** (1) [245178](https://platzi.com/comentario/245178/) 

	Cómo puedo eliminar la instancia creada?

	* **sergiodxa** [245178] (2)

		Con `now rm [url]`

* **CARLOS ROMERO** (1) [217686](https://platzi.com/comentario/217686/) 

	En donde hace el deploy now?

	* **sergiodxa** [217686] (4)

		En su propia nube llamada [Now.sh](http://Now.sh). Si te referís a que lugar físico la única región por ahora es [SFO](https://sfo.now.sh) y pronto [BRU](https://bru.now.sh).

* **Jose Francisco Alvarez Valdez** (1) [67397](https://platzi.com/comentario/722430/) 
Alguien me puede ayudar con este error cuando ejecuto el comando now Error! An unexpected error occurred! TypeError: e.ref is not a funct...

	* **osmandi (Platzi)** [67397] (1)

		Parece ser un error de la librería, intenta actuarlo a la última versión.

* **Navarrock33** (0) [246376](https://platzi.com/comentario/246376/) 

	Alias en Now

* **José Rodríguez** (0) [224449](https://platzi.com/comentario/224449/) 

	Saludos, si es la primera vez que ejecutas el comando now, te pedirá que ingreses tu email y luego lo verifiques por medio de un correo eléctronico que ellos estarán enviando.

* **Joaquin Araujo** (0) [205252](https://platzi.com/comentario/205252/) 

	Ya instalé **npm install -g now** pero me ubico en la carpeta del proyecto al cual le quiero hacer deploy y al ejecutar el comando **now** me regresa un error que dice:
	``` 
	    zsh: execformaterror: now
	    
	```
	
	Intento ejecutarlo en bash y es lo mismo, error.

	* **davidtoca (Platzi)** [205252] (0)

		Intenta usar otra terminal, puede que no se halla actualizado tu terminal actual. Corriste npm con sudo ??

	* **Joaquin Araujo** [205252] (2)

		[Solución] El problema es que now no funciona en una arquitectura de 32 bits, en un sisitemas de 64 bits me funcionó perfectamente.

# Tipos de Deploy [1483]

## 0080. Estructura del proyecto [8413](https://platzi.com/clases/1139-deploy-now/8413-estructura-del-proyecto8978/)

### Descripción:


### Links:

* [GitHub - platzi/now-course: Proyecto para el curso de Now.sh en Platzi](https://github.com/platzi/now-course)

* [https://platzi-now.now.sh/](https://platzi-now.now.sh/)

### Comentarios:

* **sergiodxa** (10) [193225](https://platzi.com/comentario/193225/) 

	Link del proyecto: <https://platzi-now.now.sh/>  
	Repositorio: <https://github.com/platzi/now-course>

* **Ronnie Moncayo** (1) [660194](https://platzi.com/comentario/660194/) 

	Que pasó con el repo de GitHub? ya no me vale

	* **Diego Alexander Forero Higuera (Platzi)** [660194] (1)

		El repo del curso esta funcionando sin problemas <https://github.com/platzi/now-course/>, ayer Github tuvo algunos problemas, es probable que por eso no podías entrar al repo.

* **José Gabriel Guzmán Lopéz** (0) [311097](https://platzi.com/comentario/311097/) 

	Hola quien me ayuda ? me sale esto  
	Missing `start` (or `now-start`) script in `package.json`. See: <https://docs.npmjs.com/cli/start>

	* **Oscar Barajas Tavares (Platzi)** [311097] (0)

		Esto es por que no encuentra el comando “start” en tu package.json, ¿lo has asignado correctamente?

## 0090. Deploy de aplicaciones Node.js [8414](https://platzi.com/clases/1139-deploy-now/8414-deploy-de-aplicaciones-nodejs/)

### Descripción:


* Con now.json se puede personalizar el deploy de nuestro proyecto.
* Podemos omitir decirle a now qué tipo de deploy estamos trabajando ya que identifica según el tipo de archivo lo que estamos haciendo, sin embargo, el decirle nos garantiza que no haya ningún error.



### Links:

* [Atom](https://atom.io)

### Comentarios:

* **Joaquin Araujo** (5) [205530](https://platzi.com/comentario/205530/) 

	Una forma de personalizar el deploy a [Now.sh](http://Now.sh) es usando un archivo JSON, dicho archivo debe tener por nombre now.json y su estructura es:
	``` 
	        {
	            "name": "nombre-de-la-aplicacion",
	            "alias": "[alias-personalizado].now.sh",
	            "env": {
	                "NODE_ENV": "production"
	                "PORT": "3000"
	                "HOST": "0.0.0.0",
	                "DB_USER": "@[db_user]",
	                "DB_PASS": "@[db_pass]",
	                "DB_HOST": "@[db_host]",
	                "DB_NAME": "@[db_name]",
	                "DB_PORT": "27017"
	            },
	            "type": "[npm]/[docker]/[static]"
	        }
	    
	```
	
	Si necesitas una guía y resumen del curso [aquí](https://joaquinaraujo.github.io/deploy-now) la tienes.

	* **José Rodríguez** [205530] (4)

		```
		    {
		        "name": "nombre-de-la-aplicacion",
		        "alias": "[alias-personalizado].now.sh",
		        "env": {
		            "NODE_ENV": "production",
		            "PORT": "3000",
		            "HOST": "0.0.0.0",
		            "DB_USER": "@[db_user]",
		            "DB_PASS": "@[db_pass]",
		            "DB_HOST": "@[db_host]",
		            "DB_NAME": "@[db_name]",
		            "DB_PORT": "27017"
		        },
		        "type": "[npm]/[docker]/[static]"
		    }
		    
		```

	* **Joaquin Araujo** [205530] (0)

		¡Gracias! No me di cuenta el error 😃

* **Oswaldo Peralta** (3) [831760](https://platzi.com/comentario/831760/) 

	Parece que en el video usan la versiòn 1.0 de Now – asi que seguramente cuando intenten hacer el deployment les salga este mensaje
	``` 
	    The property `type` isnot allowed in now.json when using Now 2.0 – please remove it.
	    
	```
	
	Para solucionarlo simplemente eliminen la linea “type”: “npm” del now.json y todo funcionarà correctamente.

* **Juan Enrique García Costas** (2) [617603](https://platzi.com/comentario/617603/) 

	Me da un error al usar el comando now. Me dice que el type del json ya no es necesario y que lo elimine. Después me sugiere que diga la versión, si 1 o 2 de Now. ¿Este curso se realizó según la primera versión de Now?
	
	Por último me están apareciendo los archivos del projecto como a David Isaac pero no el proceso ni los logs como a ti.

* **David Isaac Flores Medrano** (2) [600538](https://platzi.com/comentario/600538/) 

	Por qué al momento de hacer deploy se muestran los archivos y no corrio npm start?  
	![](![Screenshot 2019-05-29 10.42.45.png](https://static.platzi.com/media/user_upload/Screenshot%202019-05-29%2010.42.45-c9e098bb-3d87-4604-a410-5c382df0872d.jpg)
	
	P.D: previamente en local, habia corrido npm start… pero que puede faltar?

	* **Juan Enrique García Costas** [600538] (2)

		Me pasa lo mismo…

	* **Juan Enrique García Costas** [600538] (3)

		He conseguido algún avance añadiendo ese array en builds…aunque no entiendo que estoy haciendo.
		``` 
		    {
		      "version": 2,
		      "name": "platzi-now-bff",
		      "builds": [
		        {
		          "src": "package.json",
		          "use": "@now/node"
		        }
		      ]
		    }```
		    
		```

	* **David Alejandro Mosquera Moreno** [600538] (1)

		Muchas gracias **@jentp** por esta solución. Estaba estancado en este error: ![build.png](https://static.platzi.com/media/user_upload/build-0840c401-7baa-41f3-b481-94a97be3325b.jpg)

* **Fernando Azuaje** (1) [673323](https://platzi.com/comentario/673323/) 

	Buenas no me funcionan los deploys, me aparecen solo las carpetas, alguien con alguna solucion?

* **Jhon Alexander Perez Valencia** (1) [599387](https://platzi.com/comentario/599387/) 

	```
	    {
	      "name": "project_name",
	      "type": "npm"
	    }
	    
	```

* **Jhon Alexander Perez Valencia** (1) [599386](https://platzi.com/comentario/599386/) 

	```
	    {json
	      "name": "project_name",
	      "type": "npm"
	    }
	    
	```

* **Sergio Minei** (1) [349133](https://platzi.com/comentario/349133/) 

	Para hacer deploy a una aplicación en node.js, hay que crear un archivo now.json.
	
	En ese eschivo, escribir lo siguiente:
	``` 
	    {
	      "name": "platzi-now-bff",
	      "type": "npm"
	    }
	    
	```
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Deploy%20con%20Now.sh)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.

* **Luis Fernando Valderrama Gastiaburu** (1) [85765](https://platzi.com/comentario/1081418/) 
Hola, acabo de ejecutar comando now desde la terminal, pero hay un problema, en la parte de sources, si me muestra la in...

* **David Isaac Flores Medrano** (1) [60088](https://platzi.com/comentario/600538/) 
Por qué al momento de hacer deploy se muestran los archivos y no corrio npm start? ![]( P.D: previamente en local, habia corrido npm star...

	* **Juan Enrique García Costas** [60088] (2)

		Me pasa lo mismo…

* **Gonzalo Vazquez** (0) [279473](https://platzi.com/comentario/279473/) 

	Buenas! que es un backend for frontend? (BFF)

	* **Diego Alexander Forero Higuera (Platzi)** [279473] (2)

		Es el backend que puede servir datos a aplicaciones frontends especificos. Por ejemplo tienes un backend que sirve datos para una aplicación de escritorio y otro backend que sirve la misma aplicación en móviles.

* **viciotec** (0) [267173](https://platzi.com/comentario/267173/) 

	Duda, se puede hacer deploy de laravel?

	* **sergiodxa** [267173] (1)

		Sí, usando contenedores de Docker se puede hacer deploy de lo que sea.

* **Josué Huancapaza Córdova** (0) [245223](https://platzi.com/comentario/245223/) 

	En la consola como hiciste para que te aparezca el branch del repositorio Sergio?

	* **sergiodxa** [245223] (1)

		Lo hace oh-my-zsh solo.

	* **Diego Alexander Forero Higuera (Platzi)** [245223] (1)

		Tienes que tener instalado zsh como shell de tu terminal y luego instalar <http://ohmyz.sh>

* **Carlos Eduardo Diaz Polanco** (0) [212778](https://platzi.com/comentario/212778/) 

	Que editor de texto utiliza Sergio ?

	* **Diego Alexander Forero Higuera (Platzi)** [212778] (2)

		Atom, <https://atom.io>

## 0100. Deploy de contenedores de Docker [8415](https://platzi.com/clases/1139-deploy-now/8415-deploy-de-contenedores-de-docker/)

### Descripción:


## Notas:

* pubsub = Nos sirve para tener una forma de comunicarnos cuando hacemos la parte de las suscripciones en real time.
* resolvers = Nos sirven para saber qué hacer en cada query o cada cambio que el navegador envía al API.
* squema = Le escribimos todo el esquema de datos que tiene nuestra aplicación, los datos que existen.
* server = Donde inicializamos el servidor, sincronizamos el modelo con la base de datos, creamos el servidor express y creamos todo lo que necesitamos para correr en producción.



### Comentarios:

* **Daniel Garrido** (3) [345837](https://platzi.com/comentario/345837/) 

	Como podria yo hacer un deploy con un docker-compose, creo que se maneja distinto. pero ya he buscando bastante y no he podido hacer un deploy

	* **Diego Alexander Forero Higuera (Platzi)** [345837] (4)

		De momento [now.sh](http://now.sh) no tiene soporte nativo para docker-compose.yml, pero encontré esto que puede servirte para lo que necesitas <https://github.com/dannav/now-compose>

* **Jair Sebastian Lozano Moron** (3) [67421](https://platzi.com/comentario/722852/) 
Podrías especificar como hacerlo ahora con la version 2.0 de now? Ya que no acepta la propiedad type

	* **Oswaldo Peralta** [67421] (1)

		solo debe quitar esa lìnea del now.json y todo funcionarà ok

* **Alejandro Robleto** (2) [774239](https://platzi.com/comentario/774239/) 

	realmente la version 2.0 de now no te deja aplicarle el deploy debemos estar muy atentos a las actualizaciones del comando??

* **Daniela Gonzales** (1) [610699](https://platzi.com/comentario/610699/) 
Genial

* **Luis Fernando Valderrama Gastiaburu** (1) [85766](https://platzi.com/comentario/1081435/) 
Hola, podrias explicar como es posible ahora, hacer despliegue con docker, en la version actual de now no es posible esp...

* **Daniel Garrido** (1) [38601](https://platzi.com/comentario/345837/) 
Como podria yo hacer un deploy con un docker-compose, creo que se maneja distinto. pero ya he buscando bastante y no he podido hacer un d...

	* **Diego Alexander Forero Higuera (Platzi)** [38601] (4)

		De momento [now.sh](http://now.sh) no tiene soporte nativo para docker-compose.yml, pero encontré esto que puede servirte para lo que necesitas <https://github.com/dannav/now-compose>

# Configuraciones [1484]

## 0110. Configuración de secrets y variables de entorno [8416](https://platzi.com/clases/1139-deploy-now/8416-configuracion-de-secrets-y-variables-de-entorno/)

### Descripción:


### Links:

* [ElephantSQL - PostgreSQL as a Service](https://www.elephantsql.com/)

### Comentarios:

* **Joaquin Araujo** (13) [205519](https://platzi.com/comentario/205519/) 

	En ocasiones, se necesita almacenar información confidencial del proyecto que solo debe ser accedida con el código en ejecución. Esto puede lograrse utilizando los screts de [Now.sh](http://Now.sh) asi de esta forma almacenar los datos necesarios (como tokens de API o contraseñas) para que la aplicación funcionen de una manera segura.
	
	Una vez que almacena un secreto, sus contenidos ya no son accesibles directamente por nadie. Solo pueden estar expuestos a implementaciones como variables de entorno.
	
	* `now secret add [secret-id] [secret-valor]` Permite agregar un nuevo secrets.
	* `now secret rename [secret-id] [secret-valor]` Permite renombrar un secrets.
	* `now secret rm [secret-id] [secret-valor]` Permite eliminar un secrets.
	* `now secret ls` Permite listar todos los secrets.
	
	
	
	Si necesitas una guía y resumen del curso [aquí](https://joaquinaraujo.github.io/deploy-now) la tienes.

	* **Edgar Valdez Moises** [205519] (1)

		Excelente aporte. Gracias

* **Juan Carlos Mendoza Rodríguez** (4) [220655](https://platzi.com/comentario/220655/) 

	Un comentario sobre el HOST: 0.0.0.0 como complemto
	
	Un servidor, o PC puede tener una o varias direcciones IPs y están asociadas a una o más interfaces de red (Tarjeta de red o WiFI).
	
	NOTA: no pueden existir direciones IP repetidas en la misma red ya que causaría lo que se denomina conflicto de IP y deshabilitarían dichas IPs
	
	localhost es el equivalente a colocar la ip 127.0.0.1 o lo que es lo mismo interface local (lo) y hace referencia al mismo equipo en si. Al colocar éste valor en 0.0.0.0, se le indica a un componente de software que se va a ejecutar para que acepte peticiones desde cualquiera de las direcciones IPs asociadas a todas las interfaces de red que posea el equipo o servidor.
	
	Si se coloca solo una, entonces la aplicación solo permitirá conexiones por esa dirección IP. En algunas aplicaciones es posible colocar más de una IPs separadas por “,”
	
	El puerto se refiere a un número de socket que se abrirá para que la aplicación secomunique, para este caso es el 3000.
	
	Existen 65535 puertos disponibles de los cuales los primeros 1024 están reservados para servicios conocidos.
	
	Estos son algunos:  
	http: 80  
	https: 443  
	ssh: 22  
	cups: 631

* **Sergio Minei** (2) [349136](https://platzi.com/comentario/349136/) 

	## Variables de Entorno
	
	Para crear variables de enterno, se añade un key **env** en el archivo now.json.
	``` 
	    {
	      "name": "platzi-now-bff",
	      "env": {
	        "NODE_ENV": "production",
	        "PORT": "3000",
	        "HOST": "0.0.0.0",
	        "DB_USER": "cobliwpv",
	        "DB_PASS": "",
	        "DB_HOST": "stampy.db.elephantsql.com",
	        "DB_NAME": "cobliwpv",
	        "DB_PORT": "5432"
	      },
	      "type": "docker"
	    }
	    
	    
	```
	
	## Secrets
	
	Hay veces en la que se necesita almacenar información confidencial del proyecto que solo debe ser accedida con el código en ejecución. Esto puede lograrse usando **secrets**.
	
	Una vez que almacena un secreto, sus contenidos ya no son accesibles directamente por nadie. Solo pueden estar expuestos a implementaciones como variables de entorno.
	
	* `now secret add [key] [valor]` Permite agregar un nuevo secrets.
	* `now secret ls` Permite listar todos los secrets.
	
	
	
	Para usar los secrets en el archivo now.json, se hace de la siguiente manera:
	``` 
	    {
	      "env": {
	        "DB_USER": "@platzi_now_db_user",
	        "DB_PASS": "@platzi_now_db_pass"
	      }
	    }
	    
	```
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Deploy%20con%20Now.sh)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.

* **Cesar Galindo** (1) [1050953](https://platzi.com/comentario/1050953/) 

	Me esta apareciendo el siguiente error
	``` 
	    `Now CLI 17.0.4
	    ❗️  The `name` property innow.json is deprecated (https://zeit.ink/5F)
	    🔍  Inspect: https://zeit.co/chestergalindo/platzi-bbf-now/2q1m3rn8u [2s]
	    Error! Build failed
	    Error! Check your logs at https://platzi-bbf-now-2q1m3rn8u.now.sh/_logs orrun `now logs https://platzi-bbf-now-2q1m3rn8u.now.sh`````
	    
	    mi repo es [](https://github.com/chestergalindo/now-course)
	```

* **fabiangzvo** (1) [1011446](https://platzi.com/comentario/1011446/) 

	Alguien me puede ayudar, por lo menos darme un indicio
	``` 
	    Downloading 12 deployment files...
	    Installing build runtime...
	    Build runtime installed:465.970ms
	    Looking up build cache...
	    Build cache not found
	    WARNING: your application is being deployed in @now/next's legacy mode. http://err.sh/zeit/now/now-next-legacy-mode
	    Installing dependencies...
	    yarn install v1.22.0
	    info No lockfile found.
	    [1/4] Resolving packages...
	    warning react > fbjs > core-js@1.2.7: core-js@<3 is no longer maintained and not recommended for usage due to the number of issues. Please, upgrade your dependencies to the actual version of core-js@3.
	    warning next > @babel/runtime-corejs2 > core-js@2.6.11: core-js@<3 is no longer maintained and not recommended for usage due to the number of issues. Please, upgrade your dependencies to the actual version of core-js@3.
	    warning next > styled-jsx > babel-types > babel-runtime > core-js@2.6.11: core-js@<3 is no longer maintained and not recommended for usage due to the number of issues. Please, upgrade your dependencies to the actual version of core-js@3.
	    [2/4] Fetching packages...
	    warning terser-webpack-plugin@1.1.0: Invalid bin field for "terser-webpack-plugin".
	    info fsevents@1.2.11: The platform "linux" is incompatible with this module.
	    info "fsevents@1.2.11" is an optional dependency and failed compatibility check. Excluding it from installation.
	    [3/4] Linking dependencies...
	    warning " > next-server@7.0.2-canary.49" has incorrect peer dependency "react@^16.0.0".
	    warning " > next-server@7.0.2-canary.49" has incorrect peer dependency "react-dom@^16.0.0".
	    warning " > next@7.0.2-canary.49" has incorrect peer dependency "react@^16.0.0".
	    warning " > next@7.0.2-canary.49" has incorrect peer dependency "react-dom@^16.0.0".
	    warning "next > next-server@7.0.2-canary.50" has incorrect peer dependency "react@^16.0.0".
	    warning "next > next-server@7.0.2-canary.50" has incorrect peer dependency "react-dom@^16.0.0".
	    warning " > react-apollo@1.1.2" has unmet peer dependency "redux@^2.0.0 || ^3.0.0".
	    warning "react-apollo > react-dom@16.13.0" has incorrect peer dependency "react@^16.0.0".
	    [4/4] Building fresh packages...
	    success Saved lockfile.
	    Done in 11.94s.
	    Running "yarn run now-build"
	    yarn run v1.22.0
	    $ NODE_OPTIONS=--max_old_space_size=3000 next build --lambdas
	    [10:49:59 PM] Compiling client
	    [10:50:04 PM] Compiled client in 6s
	    [10:50:04 PM] Compiling server
	    [10:50:07 PM] Compiled server in 2s
	    ModuleBuildError: Module build failed (from ./node_modules/next/dist/build/webpack/loaders/next-babel-loader.js):
	    Error: .plugins[0][1] must be an object, false, or undefined
	        at assertPluginItem (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/option-assertions.js:244:15)
	        at /zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/option-assertions.js:222:30
	        at Array.forEach (<anonymous>)
	        at assertPluginList (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/option-assertions.js:222:9)
	        at /zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/options.js:107:5
	        at Array.forEach (<anonymous>)
	        at validateNested (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/options.js:83:21)
	        at validate (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/options.js:74:10)
	        at /zeit/30cd8a69/node_modules/@babel/core/lib/config/config-chain.js:169:34
	        at cachedFunction (/zeit/30cd8a69/node_modules/@babel/core/lib/config/caching.js:33:19)
	        at buildRootChain (/zeit/30cd8a69/node_modules/@babel/core/lib/config/config-chain.js:118:36)
	        at loadPrivatePartialConfig (/zeit/30cd8a69/node_modules/@babel/core/lib/config/partial.js:85:55)
	        at Object.loadPartialConfig (/zeit/30cd8a69/node_modules/@babel/core/lib/config/partial.js:110:18)
	        at Object.<anonymous> (/zeit/30cd8a69/node_modules/babel-loader/lib/index.js:105:26)
	        at Generator.next (<anonymous>)
	        at step (/zeit/30cd8a69/node_modules/babel-loader/lib/index.js:3:221)
	        at /zeit/30cd8a69/node_modules/webpack/lib/NormalModule.js:286:20
	        at /zeit/30cd8a69/node_modules/loader-runner/lib/LoaderRunner.js:367:11
	        at /zeit/30cd8a69/node_modules/loader-runner/lib/LoaderRunner.js:233:18
	        at context.callback (/zeit/30cd8a69/node_modules/loader-runner/lib/LoaderRunner.js:111:13)
	        at /zeit/30cd8a69/node_modules/babel-loader/lib/index.js:45:103 {
	      details: undefined,
	      missing: undefined,
	      origin: MultiModule {
	        dependencies: [ [SingleEntryDependency] ],
	        blocks: [],
	        variables: [],
	        type: 'javascript/dynamic',
	        context: '/zeit/30cd8a69',
	        debugId: 1001,
	        hash: '7a33a20d8672d01b741f0330250c9502',
	        renderedHash: '7a33a20d8672d01b741f',
	        resolveOptions: {},
	        factoryMeta: {},
	        warnings: [],
	        errors: [],
	        buildMeta: { providedExports: true },
	        buildInfo: {},
	        reasons: [ [ModuleReason] ],
	        _chunks: SortableSet [Set] {
	          [Chunk],
	          _sortFn: [Function: sortById],
	          _lastActiveSortFn: null,
	          _cache: undefined,
	          _cacheOrderIndependent: undefined
	        },
	        id: 1,
	        index: 364,
	        index2: 365,
	        depth: 0,
	        issuer: null,
	        profile: undefined,
	        prefetched: false,
	        built: true,
	        used: true,
	        usedExports: true,
	        optimizationBailout: [
	          'ModuleConcatenation bailout: Module is not an ECMAScript module'
	        ],
	        _rewriteChunkInReasons: undefined,
	        useSourceMap:false,
	        _source: null,
	        name:'static/P~qgTFiFlIL8HygngYQaV/pages/index.js',
	        _identifier:'multi ./pages/index.js'
	      },
	      dependencies: [
	        SingleEntryDependency {
	          module: [NormalModule],
	          weak:false,
	          optional:false,
	          loc: [Object],
	          request:'./pages/index.js',
	          userRequest:'./pages/index.js'
	        }
	      ],
	      module: NormalModule {
	        dependencies: [],
	        blocks: [],
	        variables: [],
	        type:'javascript/auto',
	        context:'/zeit/30cd8a69/pages',
	        debugId:1004,
	        hash:'8f3dd13ed331f9e43c629b5936d75c0a',
	        renderedHash:'8f3dd13ed331f9e43c62',
	        resolveOptions: {},
	        factoryMeta: {},
	        warnings: [],
	        errors: [ [Circular] ],
	        buildMeta: { providedExports:true },
	        buildInfo: {
	          cacheable:true,
	          fileDependencies: [Set],
	          contextDependencies: Set {}
	        },
	        reasons: [ [ModuleReason] ],
	        _chunks: SortableSet [Set] {
	          [Chunk],
	          _sortFn: [Function: sortById],
	          _lastActiveSortFn: null,
	          _cache: undefined,
	          _cacheOrderIndependent: undefined
	        },
	        id:'RNiq',
	        index:365,
	        index2:364,
	        depth:1,
	        issuer: MultiModule {
	          dependencies: [Array],
	          blocks: [],
	          variables: [],
	          type:'javascript/dynamic',
	          context:'/zeit/30cd8a69',
	          debugId:1001,
	          hash:'7a33a20d8672d01b741f0330250c9502',
	          renderedHash:'7a33a20d8672d01b741f',
	          resolveOptions: {},
	          factoryMeta: {},
	          warnings: [],
	          errors: [],
	          buildMeta: [Object],
	          buildInfo: {},
	          reasons: [Array],
	          _chunks: [SortableSet [Set]],
	          id:1,
	          index:364,
	          index2:365,
	          depth:0,
	          issuer: null,
	          profile: undefined,
	          prefetched:false,
	          built:true,
	          used:true,
	          usedExports:true,
	          optimizationBailout: [Array],
	          _rewriteChunkInReasons: undefined,
	          useSourceMap:false,
	          _source: null,
	          name:'static/P~qgTFiFlIL8HygngYQaV/pages/index.js',
	          _identifier:'multi ./pages/index.js'
	        },
	        profile: undefined,
	        prefetched:false,
	        built:true,
	        used:true,
	        usedExports:true,
	        optimizationBailout: [
	          'ModuleConcatenation bailout: Module is not an ECMAScript module'
	        ],
	        _rewriteChunkInReasons: undefined,
	        useSourceMap:false,
	        _source: RawSource {
	          _value:'throw new Error("Module build failed (from ./node_modules/next/dist/build/webpack/loaders/next-babel-loader.js):\\nError: .plugins[0][1] must be an object, false, or undefined\\n    at assertPluginItem (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/option-assertions.js:244:15)\\n    at /zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/option-assertions.js:222:30\\n    at Array.forEach (<anonymous>)\\n    at assertPluginList (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/option-assertions.js:222:9)\\n    at /zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/options.js:107:5\\n    at Array.forEach (<anonymous>)\\n    at validateNested (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/options.js:83:21)\\n    at validate (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/options.js:74:10)\\n    at /zeit/30cd8a69/node_modules/@babel/core/lib/config/config-chain.js:169:34\\n    at cachedFunction (/zeit/30cd8a69/node_modules/@babel/core/lib/config/caching.js:33:19)\\n    at buildRootChain (/zeit/30cd8a69/node_modules/@babel/core/lib/config/config-chain.js:118:36)\\n    at loadPrivatePartialConfig (/zeit/30cd8a69/node_modules/@babel/core/lib/config/partial.js:85:55)\\n    at Object.loadPartialConfig (/zeit/30cd8a69/node_modules/@babel/core/lib/config/partial.js:110:18)\\n    at Object.<anonymous> (/zeit/30cd8a69/node_modules/babel-loader/lib/index.js:105:26)\\n    at Generator.next (<anonymous>)\\n    at step (/zeit/30cd8a69/node_modules/babel-loader/lib/index.js:3:221)");'
	        },
	        request:'/zeit/30cd8a69/node_modules/next/dist/build/webpack/loaders/next-babel-loader.js??ref--4!/zeit/30cd8a69/pages/index.js',
	        userRequest:'/zeit/30cd8a69/pages/index.js',
	        rawRequest:'./pages/index.js',
	        binary:false,
	        parser: Parser {
	          _pluginCompat: [SyncBailHook],
	          hooks: [Object],
	          options: {},
	          sourceType:'auto',
	          scope: undefined,
	          state: undefined,
	          comments: undefined
	        },
	        generator: JavascriptGenerator {},
	        resource:'/zeit/30cd8a69/pages/index.js',
	        matchResource: undefined,
	        loaders: [ [Object] ],
	        error: [Circular],
	        _buildHash:'26e93971229cae3bdb6b342df05ccc42',
	        buildTimestamp:1582930199347,
	        _cachedSources: Map { 'javascript' => [Object] },
	        lineToLine:false,
	        _lastSuccessfulBuildMeta: {},
	        _ast: null
	      },
	      name:'ModuleBuildError',
	      error:Error: .plugins[0][1] must be an object, false, or undefined
	          at assertPluginItem (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/option-assertions.js:244:15)
	          at /zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/option-assertions.js:222:30
	          at Array.forEach (<anonymous>)
	          at assertPluginList (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/option-assertions.js:222:9)
	          at /zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/options.js:107:5
	          at Array.forEach (<anonymous>)
	          at validateNested (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/options.js:83:21)
	          at validate (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/options.js:74:10)
	          at /zeit/30cd8a69/node_modules/@babel/core/lib/config/config-chain.js:169:34
	          at cachedFunction (/zeit/30cd8a69/node_modules/@babel/core/lib/config/caching.js:33:19)
	          at buildRootChain (/zeit/30cd8a69/node_modules/@babel/core/lib/config/config-chain.js:118:36)
	          at loadPrivatePartialConfig (/zeit/30cd8a69/node_modules/@babel/core/lib/config/partial.js:85:55)
	          at Object.loadPartialConfig (/zeit/30cd8a69/node_modules/@babel/core/lib/config/partial.js:110:18)
	          at Object.<anonymous> (/zeit/30cd8a69/node_modules/babel-loader/lib/index.js:105:26)
	          at Generator.next (<anonymous>)
	          at step (/zeit/30cd8a69/node_modules/babel-loader/lib/index.js:3:221)
	    } ModuleBuildError: Module build failed (from ./node_modules/next/dist/build/webpack/loaders/next-babel-loader.js):
	    Error: .plugins[0][1] must be an object, false, or undefined
	        at assertPluginItem (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/option-assertions.js:244:15)
	        at /zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/option-assertions.js:222:30
	        at Array.forEach (<anonymous>)
	        at assertPluginList (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/option-assertions.js:222:9)
	        at /zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/options.js:107:5
	        at Array.forEach (<anonymous>)
	        at validateNested (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/options.js:83:21)
	        at validate (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/options.js:74:10)
	        at /zeit/30cd8a69/node_modules/@babel/core/lib/config/config-chain.js:169:34
	        at cachedFunction (/zeit/30cd8a69/node_modules/@babel/core/lib/config/caching.js:33:19)
	        at buildRootChain (/zeit/30cd8a69/node_modules/@babel/core/lib/config/config-chain.js:118:36)
	        at loadPrivatePartialConfig (/zeit/30cd8a69/node_modules/@babel/core/lib/config/partial.js:85:55)
	        at Object.loadPartialConfig (/zeit/30cd8a69/node_modules/@babel/core/lib/config/partial.js:110:18)
	        at Object.<anonymous> (/zeit/30cd8a69/node_modules/babel-loader/lib/index.js:105:26)
	        at Generator.next (<anonymous>)
	        at step (/zeit/30cd8a69/node_modules/babel-loader/lib/index.js:3:221)
	        at /zeit/30cd8a69/node_modules/webpack/lib/NormalModule.js:286:20
	        at /zeit/30cd8a69/node_modules/loader-runner/lib/LoaderRunner.js:367:11
	        at /zeit/30cd8a69/node_modules/loader-runner/lib/LoaderRunner.js:233:18
	        at context.callback (/zeit/30cd8a69/node_modules/loader-runner/lib/LoaderRunner.js:111:13)
	        at /zeit/30cd8a69/node_modules/babel-loader/lib/index.js:45:103 {
	      details: undefined,
	      missing: undefined,
	      origin: MultiModule {
	        dependencies: [ [SingleEntryDependency] ],
	        blocks: [],
	        variables: [],
	        type:'javascript/dynamic',
	        context:'/zeit/30cd8a69',
	        debugId:2092,
	        hash:'166722774d26ebeabf250cffd337e080',
	        renderedHash:'166722774d26ebeabf25',
	        resolveOptions: {},
	        factoryMeta: {},
	        warnings: [],
	        errors: [],
	        buildMeta: { providedExports:true },
	        buildInfo: {},
	        reasons: [ [ModuleReason] ],
	        _chunks: SortableSet [Set] {
	          [Chunk],
	          _sortFn: [Function: sortById],
	          _lastActiveSortFn: null,
	          _cache: undefined,
	          _cacheOrderIndependent: undefined
	        },
	        id:0,
	        index:0,
	        index2:1,
	        depth:0,
	        issuer: null,
	        profile: undefined,
	        prefetched:false,
	        built:true,
	        used:true,
	        usedExports:true,
	        optimizationBailout: [
	          'ModuleConcatenation bailout: Module is not an ECMAScript module'
	        ],
	        _rewriteChunkInReasons: undefined,
	        useSourceMap:false,
	        _source: null,
	        name:'static/P~qgTFiFlIL8HygngYQaV/pages/index.js',
	        _identifier:'multi ./pages/index.js'
	      },
	      dependencies: [
	        SingleEntryDependency {
	          module: [NormalModule],
	          weak:false,
	          optional:false,
	          loc: [Object],
	          request:'./pages/index.js',
	          userRequest:'./pages/index.js'
	        }
	      ],
	      module: NormalModule {
	        dependencies: [],
	        blocks: [],
	        variables: [],
	        type:'javascript/auto',
	        context:'/zeit/30cd8a69/pages',
	        debugId:2096,
	        hash:'8f3dd13ed331f9e43c629b5936d75c0a',
	        renderedHash:'8f3dd13ed331f9e43c62',
	        resolveOptions: {},
	        factoryMeta: {},
	        warnings: [],
	        errors: [ [Circular] ],
	        buildMeta: { providedExports:true },
	        buildInfo: {
	          cacheable:true,
	          fileDependencies: [Set],
	          contextDependencies: Set {}
	        },
	        reasons: [ [ModuleReason] ],
	        _chunks: SortableSet [Set] {
	          [Chunk],
	          _sortFn: [Function: sortById],
	          _lastActiveSortFn: null,
	          _cache: undefined,
	          _cacheOrderIndependent: undefined
	        },
	        id:'RNiq',
	        index:1,
	        index2:0,
	        depth:1,
	        issuer: MultiModule {
	          dependencies: [Array],
	          blocks: [],
	          variables: [],
	          type:'javascript/dynamic',
	          context:'/zeit/30cd8a69',
	          debugId:2092,
	          hash:'166722774d26ebeabf250cffd337e080',
	          renderedHash:'166722774d26ebeabf25',
	          resolveOptions: {},
	          factoryMeta: {},
	          warnings: [],
	          errors: [],
	          buildMeta: [Object],
	          buildInfo: {},
	          reasons: [Array],
	          _chunks: [SortableSet [Set]],
	          id:0,
	          index:0,
	          index2:1,
	          depth:0,
	          issuer: null,
	          profile: undefined,
	          prefetched:false,
	          built:true,
	          used:true,
	          usedExports:true,
	          optimizationBailout: [Array],
	          _rewriteChunkInReasons: undefined,
	          useSourceMap:false,
	          _source: null,
	          name:'static/P~qgTFiFlIL8HygngYQaV/pages/index.js',
	          _identifier:'multi ./pages/index.js'
	        },
	        profile: undefined,
	        prefetched:false,
	        built:true,
	        used:true,
	        usedExports:true,
	        optimizationBailout: [
	          'ModuleConcatenation bailout: Module is not an ECMAScript module'
	        ],
	        _rewriteChunkInReasons: undefined,
	        useSourceMap:false,
	        _source: RawSource {
	          _value:'throw new Error("Module build failed (from ./node_modules/next/dist/build/webpack/loaders/next-babel-loader.js):\\nError: .plugins[0][1] must be an object, false, or undefined\\n    at assertPluginItem (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/option-assertions.js:244:15)\\n    at /zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/option-assertions.js:222:30\\n    at Array.forEach (<anonymous>)\\n    at assertPluginList (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/option-assertions.js:222:9)\\n    at /zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/options.js:107:5\\n    at Array.forEach (<anonymous>)\\n    at validateNested (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/options.js:83:21)\\n    at validate (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/options.js:74:10)\\n    at /zeit/30cd8a69/node_modules/@babel/core/lib/config/config-chain.js:169:34\\n    at cachedFunction (/zeit/30cd8a69/node_modules/@babel/core/lib/config/caching.js:33:19)\\n    at buildRootChain (/zeit/30cd8a69/node_modules/@babel/core/lib/config/config-chain.js:118:36)\\n    at loadPrivatePartialConfig (/zeit/30cd8a69/node_modules/@babel/core/lib/config/partial.js:85:55)\\n    at Object.loadPartialConfig (/zeit/30cd8a69/node_modules/@babel/core/lib/config/partial.js:110:18)\\n    at Object.<anonymous> (/zeit/30cd8a69/node_modules/babel-loader/lib/index.js:105:26)\\n    at Generator.next (<anonymous>)\\n    at step (/zeit/30cd8a69/node_modules/babel-loader/lib/index.js:3:221)");'
	        },
	        request:'/zeit/30cd8a69/node_modules/next/dist/build/webpack/loaders/next-babel-loader.js??ref--4!/zeit/30cd8a69/pages/index.js',
	        userRequest:'/zeit/30cd8a69/pages/index.js',
	        rawRequest:'./pages/index.js',
	        binary:false,
	        parser: Parser {
	          _pluginCompat: [SyncBailHook],
	          hooks: [Object],
	          options: {},
	          sourceType:'auto',
	          scope: undefined,
	          state: undefined,
	          comments: undefined
	        },
	        generator: JavascriptGenerator {},
	        resource:'/zeit/30cd8a69/pages/index.js',
	        matchResource: undefined,
	        loaders: [ [Object] ],
	        error: [Circular],
	        _buildHash:'26e93971229cae3bdb6b342df05ccc42',
	        buildTimestamp:1582930204951,
	        _cachedSources: Map { 'javascript' => [Object] },
	        lineToLine:false,
	        _lastSuccessfulBuildMeta: {},
	        _ast: null
	      },
	      name:'ModuleBuildError',
	      error:Error: .plugins[0][1] must be an object, false, or undefined
	          at assertPluginItem (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/option-assertions.js:244:15)
	          at /zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/option-assertions.js:222:30
	          at Array.forEach (<anonymous>)
	          at assertPluginList (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/option-assertions.js:222:9)
	          at /zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/options.js:107:5
	          at Array.forEach (<anonymous>)
	          at validateNested (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/options.js:83:21)
	          at validate (/zeit/30cd8a69/node_modules/@babel/core/lib/config/validation/options.js:74:10)
	          at /zeit/30cd8a69/node_modules/@babel/core/lib/config/config-chain.js:169:34
	          at cachedFunction (/zeit/30cd8a69/node_modules/@babel/core/lib/config/caching.js:33:19)
	          at buildRootChain (/zeit/30cd8a69/node_modules/@babel/core/lib/config/config-chain.js:118:36)
	          at loadPrivatePartialConfig (/zeit/30cd8a69/node_modules/@babel/core/lib/config/partial.js:85:55)
	          at Object.loadPartialConfig (/zeit/30cd8a69/node_modules/@babel/core/lib/config/partial.js:110:18)
	          at Object.<anonymous> (/zeit/30cd8a69/node_modules/babel-loader/lib/index.js:105:26)
	          at Generator.next (<anonymous>)
	          at step (/zeit/30cd8a69/node_modules/babel-loader/lib/index.js:3:221)
	    }
	    > Build error occured
	    Error: > Build failed because of webpack errors
	        at Object.build [as default] (/zeit/30cd8a69/node_modules/next/dist/build/index.js:42:15)
	        at runMicrotasks (<anonymous>)
	        at processTicksAndRejections (internal/process/task_queues.js:94:5)
	    error Command failed with exit code 1.
	    info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
	    Error: Exited with 1
	        at ChildProcess.<anonymous> (/zeit/7665ffb244d2ecd4/.build-utils/node_modules/@now/build-utils/dist/index.js:31347:24)
	        at ChildProcess.emit (events.js:223:5)
	        at ChildProcess.EventEmitter.emit (domain.js:475:20)
	        at maybeClose (internal/child_process.js:1021:16)
	        at Process.ChildProcess._handle.onexit (internal/child_process.js:283:5)
	    worker exited with code 20 and signal null
	    Done with"package.json"
	    
	```

* **eddyarellanes** (1) [395712](https://platzi.com/comentario/395712/) 

	Me confundí un poco, pero al final funcionó el tema de los secrets, dejo un pedazo de código por si a alguien más le pasa:  
	Añadiendo el secret:  
	now secret add access_token 0101010  
	en el archivo [now.sh](http://now.sh)
	``` 
	    {
	      "name": "Test",
	      "alias": "test121.now.sh",
	      "type": "npm",
	      "env": {
	        "access_token": "@access_token"
	      }
	    }
	    
	```
	
	Y en un archivo de config que uso:
	``` 
	    const ACCESS_TOKEN = process.env.access_token//Now Secret Variable
	    const TOKEN_NAME = 'dummy_token'
	    const URL_CALLBACK = 'test121.now.sh'
	    module.exports = {
	        ACCESS_TOKEN,
	        TOKEN_NAME,
	        URL_CALLBACK
	    }
	    
	```
	
	Y así ya puedo usar mi secret y tantan (Y)

* **LUIGGI ALEXIS RODRIGUEZ RUIZ** (1) [382955](https://platzi.com/comentario/382955/) 

	Hola, tengo un error en el bff: luego de hacer deploy y probar el enlace, obtengo Internal server error : 500  
	Este es el log de mi ultimo deployment de bff, veo que hay un Error: **Network request failed with status 404 - “Not Found”**
	
	![Capture.PNG](https://static.platzi.com/media/user_upload/Capture-5515f182-8a74-42ea-855b-6331ccc87e5c.jpg)
	
	Alquien me brindaría una pista? gracias!

	* **walis85300 (Platzi)** [382955] (1)

		Podría decir que tal vez exista un error en la escritura de la URL, por el código que retorna, 404.

* **Pablo Elias   Mercado Moreno** (1) [358723](https://platzi.com/comentario/358723/) 

	Primero colocó now secrets y luego now secret, no hay problema en esto? a mi me funciono tambien, pero me gustaría saber si hay alguna diferencia o si ocurre algo en otros SO que se deba usar estrictamente de alguna forma.

	* **Diego Alexander Forero Higuera (Platzi)** [358723] (1)

		Es un alias, funcionan igual.

	* **Pablo Elias   Mercado Moreno** [358723] (1)

		@GOLLUM23 Pero alias definidas previamente por now cierto? algo así como palabras reservadas? porque yo probé y me sirvió pero no hice ningún alias.

	* **Diego Alexander Forero Higuera (Platzi)** [358723] (2)

		Si son definidas por now.

	* **Pablo Elias   Mercado Moreno** [358723] (1)

		Muchas gracias @GOLLUM23

* **Edgar Valdez Moises** (1) [340130](https://platzi.com/comentario/340130/) 

	Hola. Necesito ayuda. Tengo un error al deployar el proyecto y pienso que se debe a los Puertos.  
	Al ejecutar `npm run dev` con el puerto 3000  
	Esto se muestra en el navegador
	``` 
	    500
	    Internal Server Error.
	    Network error: request to http://localhost:4000/graphql failed, reason: connect ECONNREFUSED 127.0.0.1:4000
	    Error: Network error: request to http://localhost:4000/graphql failed, reason: connect ECONNREFUSED 127.0.0.1:4000
	        at new ApolloError (/home/evaldez/platzi/now-course/bff/node_modules/apollo-client/src/errors/ApolloError.js:32:28)
	        at /home/evaldez/platzi/now-course/bff/node_modules/apollo-client/src/core/QueryManager.js:260:41
	        at /home/evaldez/platzi/now-course/bff/node_modules/apollo-client/src/core/QueryManager.js:692:25
	        at Array.forEach (<anonymous>)
	        at /home/evaldez/platzi/now-course/bff/node_modules/apollo-client/src/core/QueryManager.js:689:27
	        at Array.forEach (<anonymous>)
	        at QueryManager.broadcastQueries (/home/evaldez/platzi/now-course/bff/node_modules/apollo-client/src/core/QueryManager.js:686:42)
	        at Array.<anonymous> (/home/evaldez/platzi/now-course/bff/node_modules/apollo-client/src/core/QueryManager.js:63:23)
	        at dispatch (/home/evaldez/platzi/now-course/bff/node_modules/redux/lib/createStore.js:186:19)
	        at /home/evaldez/platzi/now-course/bff/node_modules/apollo-client/src/ApolloClient.js:172:30
	    
	```
	
	Y esto en la consola del api
	``` 
	    [nodemon] 1.11.0
	    [nodemon] to restart at any time, enter `rs`
	    [nodemon] watching: *.*
	    [nodemon] starting `node .`
	    Executing (default): DROP TABLE IF EXISTS "todos" CASCADE;
	    Executing (default): DROP TYPE IF EXISTS "public"."enum_todos_status";
	    Executing (default): SELECT t.typname enum_name, array_agg(e.enumlabel ORDER BY enumsortorder) enum_value FROM pg_type t JOIN pg_enum e ON t.oid = e.enumtypid JOIN pg_catalog.pg_namespace n ON n.oid = t.typnamespace WHERE n.nspname = 'public' AND t.typname='enum_todos_status' GROUP BY 1
	    Executing (default): DROP TYPE IF EXISTS "public"."enum_todos_status"; CREATE TYPE "public"."enum_todos_status" AS ENUM('active', 'completed', 'deleted');
	    Executing (default): CREATE TABLE IF NOT EXISTS "todos" ("id" UUID UNIQUE , "content" VARCHAR(255), "status""public"."enum_todos_status", "createdAt" TIMESTAMP WITH TIME ZONE NOT NULL, "updatedAt" TIMESTAMP WITH TIME ZONE NOT NULL, UNIQUE ("id"), PRIMARY KEY ("id"));
	    Executing (default): SELECT i.relname AS name, ix.indisprimary AS primary, ix.indisunique AS unique, ix.indkey AS indkey, array_agg(a.attnum) as column_indexes, array_agg(a.attname) AS column_names, pg_get_indexdef(ix.indexrelid) AS definition FROM pg_class t, pg_class i, pg_index ix, pg_attribute a WHERE t.oid = ix.indrelid AND i.oid = ix.indexrelid AND a.attrelid = t.oid AND t.relkind = 'r' and t.relname = 'todos' GROUP BY i.relname, ix.indexrelid, ix.indisprimary, ix.indisunique, ix.indkey ORDER BY i.relname;
	    Executing (default): CREATE UNIQUE INDEX "todos_id" ON "todos" ("id")
	    events.js:167
	          throw er; // Unhandled 'error' event
	          ^
	    
	    Error: listen EADDRINUSE 127.0.0.1:3000
	        at Server.setupListenHandle [as _listen2] (net.js:1336:14)
	        at listenInCluster (net.js:1384:12)
	        at GetAddrInfoReqWrap.doListen [as callback] (net.js:1510:7)
	        at GetAddrInfoReqWrap.onlookup [as oncomplete] (dns.js:61:10)
	    Emitted 'error' event at:
	        at emitErrorNT (net.js:1363:8)
	        at process._tickCallback (internal/process/next_tick.js:63:19)
	    [nodemon] app crashed - waiting for file changes before starting...
	    
	```
	
	Estoy usando [api.elephantsql](https://api.elephantsql.com/) para la base de datos.  
	Al deployar con now se muestra error 500 pienso que es el mismo error.  
	En desarrollo el problema se soluciona cuando uso el Puerto 4000 para el api. Pero al deployar persite el error.
	
	Esta es la conf de now.json para el api
	``` 
	    {
	        "name": "now_curso_api",
	        "alias": "now_curso_api.now.sh",
	        "type": "docker",
	        "env": {
	            "NODE_ENV": "production",
	            "HOST": "0.0.0.0",
	            "PORT": "3000",
	            "DB_HOST": "@now_curso_platzi_db_host",
	            "DB_PORT": "5432",
	            "DB_USER": "@now_curso_platzi_db_user",
	            "DB_PASS": "@now_curso_platzi_db_pass",
	            "DB_NAME": "@now_curso_platzi_db_name"
	        }
	    }
	    
	```
	
	Y este el de bff
	``` 
	    {
	        "name": "now_curso_bff",
	        "type": "npm",
	        "env": {
	            "NODE_ENV": "production",
	            "BACKEND_API_ENDPOINT": "https://now_curso_api.now.sh/graphql",
	            "BACKEND_WS_ENDPOINT": "wss://now_curso_api.now.sh/subscriptions"
	        }
	    }
	    
	```
	
	Si alguien tiene alguna idea del problema. Se agradece la ayuda
	
	Saludos.

	* **Edgar Valdez Moises** [340130] (1)

		El error de debía a que mis endpoint estaban mal apuntados.

* **Fernando Eladio Alvarez Noya** (1) [84513](https://platzi.com/comentario/1052279/) 
Hola luego de ejecutar now en el directorio api al ir a la url solo me muestra los archivos pero nada ejecutandose! Que me falto hacer o ...

* **Alejandro Robleto** (1) [70527](https://platzi.com/comentario/776948/) 
me arroja este error The property type is not allowed in now.json when using Now 2.0 – please remove it.

* **LUIGGI ALEXIS RODRIGUEZ RUIZ** (1) [42065](https://platzi.com/comentario/382955/) 
Hola, tengo un error en el bff: luego de hacer deploy y probar el enlace, obtengo Internal server error : 500 Este es el log de mi ultimo...

	* **walis85300 (Platzi)** [42065] (1)

		Podría decir que tal vez exista un error en la escritura de la URL, por el código que retorna, 404.

* **carlinius PD** (0) [199204](https://platzi.com/comentario/199204/) 

	hola, los datos de la conexión a la bbdd todavía funcionan? lo digo por que a mi me da un error de login  
	gracias, un saludo

	* **davidtoca (Platzi)** [199204] (1)

		No debes usar los datos de conexion del video, estos son los del profesor, tu debes tener unos propios de tu aplicacion, para ello puedes usar elephantsql, para usarlo, debes crear una cuenta en <https://www.elephantsql.com/> y una vez estes logeado creas tu propia base de datos y a continuacion ver los datos de conexion de esa base de datos en la seccion de details, esos datos de conexion son los que debes usar.

* **pedri77** (0) [194437](https://platzi.com/comentario/194437/) 

	Ayuda!  
	Me da este error:
	
	> Error! An unexpected error occurred!  
	>  SyntaxError: Unexpected string in JSON at position 207  
	>  at JSON.parse (<anonymous>)  
	>  at readJSON (/snapshot/now-cli/dist/now.js:4503:17) SyntaxError: Unexpected string in JSON at position 207  
	>  at JSON.parse (<anonymous>)  
	>  at readJSON (/snapshot/now-cli/dist/now.js:4503:17)

	* **Diego Alexander Forero Higuera (Platzi)** [194437] (1)

		Comparte tu archivo de configuración, al parecer hay un problema, esta llegando un string donde no los espera.

	* **pedri77** [194437] (0)

		Me faltaban unas " " 😉 Gracias.

* **Francisco Martin Nacimiento** (0) [78774](https://platzi.com/comentario/927342/) 
Mi pregunta es la siguiente, con esas variables de entorno de que definen en el now.json, lo que hacen es mapear esas variables al comand...

* **Alejandro Robleto** (0) [70526](https://platzi.com/comentario/776946/) 
alguien me podria ayudar a resover el punto de la version 2,0 de now cuando trato de hacer el deploy no me deja porque me indica que el T...

	* **Oswaldo Peralta** [70526] (1)

		Estimado, en el video utilizan Now 1.0, por lo tanto la lìnea “type”: “npm” era necesaria.
		
		Al estar en versiòn 2.0, lo que debe hacer es quitar esa lìnea del now.json y todo funcionarà implecable.

## 0120. Ver el código fuente de tu aplicación [8417](https://platzi.com/clases/1139-deploy-now/8417-ver-el-codigo-fuente-de-tu-aplicacion/)

### Descripción:


### Comentarios:

* **ivanguerra10** (8) [249228](https://platzi.com/comentario/249228/) 

	* En la pestaña **Source** de cada deploy podemos ver todo el codigo del mismo.
	
	* En el plan **“Free”** de [now.sh](http://now.sh), el Codigo fuente es accesible Open Source, es decir, cualquiera que tenga la url del deploy: url-deploy/_src puede ver el codigo fuente.
	
	* En el plan **“Premium”** , hay que estar logueado para poder ver el codigo fuente de un deploy.
	
	* De esta manera, podemos tener la lista de deploys que fuimos haciendo y el codigo fuente de cada uno, una especie de **“versionamiento”** de cada deploy.
	
	
	

* **Sergio Minei** (3) [349137](https://platzi.com/comentario/349137/) 

	Para ver el código fuente del proyecto, solo hay que poner **/_src** al final de la url de now.
	``` 
	    https://podcast-dadzjorpfe.now.sh/_src
	    
	```
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Deploy%20con%20Now.sh)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.

## 0130. Definir aliases para tus deploy [8418](https://platzi.com/clases/1139-deploy-now/8418-definir-aliases-para-tus-deploy/)

### Descripción:


 **Nota:**

* Cuando utilizamos `now alias` va a tomar el último deploy que se hizo y va a conectarlo al alias que hayamos creado.



### Comentarios:

* **sergiodxa** (6) [193232](https://platzi.com/comentario/193232/) 

	La propiedad `alias` en nuestro `now.json` también puede ser un array de strings lo que permite que al ejecutar `now alias` se asignen múltiples aliases al mismo tiempo.

	* **Carlos Eduardo Diaz Polanco** [193232] (0)

		tengo un herron en mi deploy.!  
		segun el deply se hizo correctamente, incluso se carga la pagina, pero en el cuerpo medio de la pagina sale el siguiente mensaje de error
		
		“An unexpected error has occurred.”
		
		y cuando introduzco datos no los carga en la base de datos y por ende no devuelve resultados

	* **Jose Reyes Garcia Delgado** [193232] (0)

		Me sucede lo mismo, me sale “An unexpected error has occurred”

* **Jose Reyes Garcia Delgado** (3) [217917](https://platzi.com/comentario/217917/) 

	Logré arreglar el mensaje de “unexpected error”, a mi me sucedió por que el backend_ws_endpoint lo definí con https en lugar de wss. Espero le sirva a alguien que tenga el mismo problema

* **David Alejandro Mosquera Moreno** (1) [860541](https://platzi.com/comentario/860541/) 

	⚠️ ADVERTENCIA! El comando **_`now alias`_** (sin argumentos) fue desaprobado a favor de _**`now --prod`**_

* **Jhon Alexander Perez Valencia** (1) [599529](https://platzi.com/comentario/599529/) 

	Para agregar un alias en el archivo `now.json` agregar.
	``` 
	    {
	      ...
	      "alias": "your-alias.now.sh"
	    }
	    
	```

* **Sergio Minei** (1) [349138](https://platzi.com/comentario/349138/) 

	## Definir Aliases
	
	Para definir un alias dentro de nuestro pyoyecto, lo podemos hacer desde nuestro archivo now.json:
	``` 
	    {
	      "alias": "platzi-now-api.now.sh"
	    }
	    
	```
	
	Para ejecutar el alias, se debe ir a la carpeta del proyecto y escribir `now alias`.
	
	Cuando utilizamos `now alias`, se va a tomar el último deploy que se hizo y va a conectarlo al alias que hayamos creado.
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Deploy%20con%20Now.sh)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.

* **David Granados** (0) [238657](https://platzi.com/comentario/238657/) 

	como hago para apuntar una url principal a un alias?

	* **Diego Alexander Forero Higuera (Platzi)** [238657] (1)

		En el siguiente video lo enseña, básicamente tienes que configurar los dns de tu dominio para que usen los dns de zeit.

## 0140. Usar un dominio personalizado [8419](https://platzi.com/clases/1139-deploy-now/8419-usar-un-dominio-personalizado/)

### Descripción:


### Links:

* [ZEIT – zeit.world: free global DNS](https://zeit.co/world)

### Comentarios:

* **Sergio Minei** (5) [349139](https://platzi.com/comentario/349139/) 

	## Dominio Personalizado
	
	Zeit.world es un DNS gratiuto global que Zeit nos da para manejar los dominios.
	
	**Si ya se tiene un dominio** :
	
	  1. Ir a la configuración de Nameservers del dominio.
	  2. Escoger Custom DNS
	  3. Agregar unos de los hostnames que aparecen en la página de [Zeit World](https://zeit.co/world). Se pueden agregar hasta 4.
	
	
	``` 
	    Host	IP	IPV6
	    a.zeit.world	96.45.80.1	2600:180a:1001::1
	    b.zeit.world	46.31.236.1	2600:180b:2001::1
	    c.zeit.world	43.247.170.1	2600:180c:3001::1
	    d.zeit.world	96.45.81.1	2600:180a:4001::1
	    e.zeit.world	46.31.237.1	2600:180b:5001::1
	    f.zeit.world	43.247.171.1	2600:180c:6001::1
	    
	```
	
	**Comprar dominio desde Zeit Domains** :
	
	Zeit te permite comprar dominios directamente desde su servicio.
	``` 
	    $ now domain buy pagina.com
	    
	```
	
	**Asignar un dominio como alias** :
	
	También se puede asignar un dominio como el alias de un deploy.
	``` 
	    $ now alias my-app-fdhdsd45.now.sh pagina.com
	    
	```
	
	Otra forma de hacerlo es agregando el key alias en now.json.
	``` 
	    {
	      "alias": "pagina.com"
	    }
	    
	```
	
	Nota: Para que el alias funcione, primero se debe de hacer configurado el hostname o haber comprado el dominio directamente desde now domains.
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Deploy%20con%20Now.sh)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.

	* **eddyarellanes** [349139] (2)

		Muy buenos tus resúmenes man muchas gracias 😃

	* **Sergio Minei** [349139] (1)

		gracias @eddyarellanes

* **sergiodxa** (4) [193230](https://platzi.com/comentario/193230/) 

	La actualización de DNS al apuntar los `nameservers` puede tomar unos minutos o hasta 2~3 días. Si no funciona inmediatamente lo mejor es esperar unas horas y volver a intentar.

	* **Carlos Eduardo Diaz Polanco** [193230] (0)

		Cual es el editor de texto que ud utiliza?

	* **sergiodxa** [193230] (1)

		Atom

* **Diego Osorio** (1) [402448](https://platzi.com/comentario/402448/) 

	Como asigno un dominio a un sitio web estático, con solo html5, css3 y js. ?

* **viciotec** (1) [269447](https://platzi.com/comentario/269447/) 

	duda, platzi.xalambri.xyz lo compraste? o como funciono, la verdad no entendi.

	* **sergiodxa** [269447] (2)

		`xalambri.xyz` es un dominio mío  
		`platzi.xalambri.xyz` es un subdomino, al ser mio el dominio puede crear todos los subdominios que quiera.

	* **ferontv_** [269447] (1)

		Una pregunta, ¿cómo se configura un subdominio? (Tomando como lo haces en el curso Namecheap como referencia).

* **Jose Pirela** (1) [253545](https://platzi.com/comentario/253545/) 

	hola que tal, he cambiado los DNS en mi servidor(GoDaddy) tengo la cuenta premiun, pero al asignar el dominio, me dice lo siguiente: DNS Configured! Verifying propagation… luego me dice, Error! > We configured the DNS settings for your alias, but we were unable to verify that they’ve propagated. Please try the alias again later… cabe acotar que fue hace un par de horas que hice el cambio de los DNS, (hace mas de 3 horas) tendré yo algún problema ? o es que debo esperar el lapso sergio comenta, muchas gracias =)

	* **Jose Pirela** [253545] (0)

		Por si alguien le pasa lo mismo, si efectivamente, solo espere un par de horas y se soluciono el problema, es solo esperar el cambio del DNS

	* **Diego Alexander Forero Higuera (Platzi)** [253545] (2)

		Siempre debes esperar, por lo general la propagación de dns toma hasta 48 horas para estar en todos los servidores DNS del mundo.

* **Luis Garcia Meneses** (1) [205922](https://platzi.com/comentario/205922/) 

	que diferencia hace lo que estamos viendo frente a contratar un hosting como HostGator o webempresa o hostiger, no es esto mas complicado, claro mi pregunta va porque lo que veo es cargar mi proyecto a un servidor que me hace "creo que lo mismo que un hosting disculpen mi ignorancia y si pueden remitirme a una guia conceptual mas intuitiva o clara

	* **Diego Alexander Forero Higuera (Platzi)** [205922] (3)

		La ventaja es que lo haces todo desde consola, no tienes que entrar a panels como `cpanel` a configurar cosas y luego ir a donde compraste el dominio y llenar otras, aquí casi puedes hacer casi todo desde un solo sitio, la terminal.

	* **Luis Garcia Meneses** [205922] (0)

		Gracias respondida la pregunta

	* **sergiodxa** [205922] (3)

		Otra cosa es que los hostings compartidos normalmente solo te permiten usar el stack LAMP, y si te dan un VPS tenés que configurar **todo** , con Now solo ejecutas un comando y ya está todo listo, sea el stack que sea.

* **Joaquin Araujo** (1) [205518](https://platzi.com/comentario/205518/) 

	¿Para el uso de dominios es necesario tener una cuenta pagada?

	* **sergiodxa** [205518] (4)

		Sí, necesitas tener una cuenta con una suscripción activa, la cuenta gratis no te permite comprar o usar dominios.

* **fersot7** (0) [198775](https://platzi.com/comentario/198775/) 

	Saludos, como eliminar un deploy, por otro lado con esto de los dominios personalizados, lo que quiere decir es que teniendo un dominio, por ejemplo [mipagina.com](http://mipagina.com) (pago), fácilmente lo puedo asociar a mi deploy en now?

	* **Diego Alexander Forero Higuera (Platzi)** [198775] (2)

		Siempre se va a vincular a tu dominio el último deploy que hagas en now.

	* **fersot7** [198775] (0)

		Bueno a lo que me refiero es a los deploy que van quedando en la **dashboard** de Zeit, por otro lado veo que se debe adquirir PremiumDNS para poder usar los custom nameservers…

	* **sergiodxa** [198775] (2)

		@fersot7 se eliminan usando `now rm [deployment]` donde `[deployment]` es la URL única. Aunque normalmente no es necesario ya que los deployments viejos quedan congelados.

## 0150. Componer microservicios [8420](https://platzi.com/clases/1139-deploy-now/8420-componer-microservicios/)

### Descripción:


### Comentarios:

* **Joaquin Araujo** (3) [205529](https://platzi.com/comentario/205529/) 

	La forma de gestionar una aplicación basada en microservicios en **[Now.sh](http://Now.sh)** es por medio de un archivo llamada rules.json
	``` 
	        {
	            "rules": [
	                {
	                    "pathname": "/graphql",
	                    "dest": "[aplicacion].now.sh"
	                },
	                {
	                    "pathname": "/[ruta]",
	                    "dest": "[aplicacion].now.sh"
	                },
	                {
	                    "dest": "[aplicacion].now.sh"
	                }
	            ]
	        }
	    
	```
	
	La forma de establecer esta configuración en [Now.sh](http://Now.sh) es por medio de el comando:
	
	* `now alias [aplicacion].now.sh -r rules.json` Permite establecer las configuraciones de rules.json en un deploy de **[Now.sh](http://Now.sh)**.
	
	
	
	Si necesitas una guía y resumen del curso [aquí](https://joaquinaraujo.github.io/deploy-now) la tienes.

* **nicolas ricardo restrepo Restr Restrepo** (1) [195654](https://platzi.com/comentario/195654/) 

	que otra alternativa tengo para orquestar microservicios, si uso docker-compose, algo como kubernetes ?

	* **Diego Alexander Forero Higuera (Platzi)** [195654] (2)

		La opción nativa de docker es docker swarm <https://docs.docker.com/engine/swarm/>

	* **nicolas ricardo restrepo Restr Restrepo** [195654] (0)

		pero puedo usarla, haciendo el deploy con now? o tengo que usar rules

	* **sergiodxa** [195654] (2)

		Now no soporta Kubernetes ni Swarm. Solo soportamos rules.json.

# Conclusiones  [1485]

## 0160. Conclusión del proyecto [8421](https://platzi.com/clases/1139-deploy-now/8421-conclusion-del-proyecto/)

### Descripción:


 **Repaso del proyecto:**

* Creamos las reglas de cómo se van a combinar nuestros microservicios para trabajar como si fuesen una sola aplicación monolítica.
* En el backend for frontend definimos un now json donde tenemos el nombre del proyecto, el alias, las variables de entornos y el tipo de deploy.
* En el API tenemos el now json, el nombre, el alias, las variables de entorno para las bases de datos y el tipo de deploy. Igual que en el bff.



### Comentarios:

* **Joaquin Araujo** (6) [205531](https://platzi.com/comentario/205531/) 

	Muy interesante esta plataforma y muy fácil de usar.

	* **Carlos Enrique Gonzalez Peña** [205531] (1)

		Muy facil de usar Pana, pense que ese curso seria mas complicado pero me equivoque

* **Pablo Elias   Mercado Moreno** (3) [358760](https://platzi.com/comentario/358760/) 

	Excelente curso, lo acabe en un par de horas y muy cómodo de seguir, una ultima consulta, como hago para ver la capacidad y demás features si yo pago por un servicio premium? Es decir, en el servidor que ya compre como vería y gestionaría eso? Desde la consola o desde la misma pagina (interfaz grafica).

	* **sergiodxa** [358760] (3)

		Todos los deployments tienen el mismo hardware, 0.125 CPU y 512MB de RAM. En el futuro va a ser configurable, actualmente no es posible de cambiar.

	* **Pablo Elias   Mercado Moreno** [358760] (2)

		Muchas gracias @sergiodxa

## 0170. Conclusiones del curso [8422](https://platzi.com/clases/1139-deploy-now/8422-conclusiones-del-curso/)

### Descripción:


### Links:

* [Five Minute Guide - ZEIT Documentation](https://zeit.co/docs)

* [Now Examples · GitHub](https://github.com/now-examples)

* [ZEIT Chat - Join us on Slack](https://zeit.chat/)

* [GitHub - zeit/awesome-zeit: The best resources related to ZEIT](https://github.com/zeit/awesome-zeit)

### Comentarios:

* **Martin Cortes** (6) [227884](https://platzi.com/comentario/227884/) 

	Siendo sincero no me gusto para nada el curso, da la impresion que se hizo todo de afán y con poca profundizacion en cada tema. Parece mas un tutorial dividido en varios videos.

	* **Damianenko Max Zeballos Torres** [227884] (1)

		A mi parecerer este es un curso corto, la herramienta no es nada compleja y se muetra lo necesario de una manera facil.

	* **edesalla17** [227884] (1)

		lo suficiente para conocer la herramienta

	* **Pablo Elias   Mercado Moreno** [227884] (1)

		La herramienta es sencilla, por eso es corto, no fue de afán, hay unos que si no se entiende nada por el afán, este curso vale la pena.

	* **Ronnie Moncayo** [227884] (1)

		El curso fue muy bueno, no se porqué quieren complejidad en algo que no hay.

* **Carlos Enrique Gonzalez Peña** (5) [331079](https://platzi.com/comentario/331079/) 

	La herramienta de Zeit no es complicada, al principio pense que este curso seria mas complejo, una ves viéndolo si se mira todo como muy poca cosa, pero aprendes todo lo esencial para hacer un deploy completo.  
	Eso si, habría estado viendo ver mas ejemplos de diferentes tipos de deploy como los que salen en los docs como un deploy de next o de websockets

* **Byron EQ** (1) [773439](https://platzi.com/comentario/773439/) 
Tenia muchas expectativas sobre este curso. Pensé que era un curso para saber de now, osea un curso básico de now pro no fue así.

# Contenido Bonus [1486]

## 0180. Deploy en Now.sh desde GitHub [8423](https://platzi.com/clases/1139-deploy-now/8423-deploy-en-nowsh-desde-github/)

### Descripción:


### Links:

* [GitHub - platzi/invie-responsive: Las guitarras más locas](https://github.com/platzi/invie-responsive)

### Comentarios:

* **Carlos Enrique Gonzalez Peña** (3) [331097](https://platzi.com/comentario/331097/) 

	Existe otra manera igual de sencilla, solo tal vez con mas clicks pero esto es directo desde GitHub.  
	Solo tienes irte a tu cuenta en Zeit y buscar el apartado de integración con GitHub.  
	Te va a pedir que inices sesión con ti GitHub y listo.  
	Una ves que tengas esto, solamente te vas al repositorio al que le quieras hacer deploy y le das click en agregar un nuevo archivo, pero, no lo agregues directamente en ese commit, si no que le das crear un nuevo branch e iniciar un pull request.  
	El archivo que vas a agregar se debe llamar `now.json` y aqui puedes poner el nombre y el alias de tu proyecto o un objeto de JS vacio `{}`  
	Y listo, con esto solo debes esperar a que now publique, en el pull request te saldra que se abra creado satisfactoriamente con un bot de now.
	
	Si alguien ocupa que cree un tutorial sobre esto con gusto lo creo.  
	Aquí esta la documentación  
	<https://zeit.co/blog/now-for-github>

* **Sergio Minei** (2) [349142](https://platzi.com/comentario/349142/) 

	## Deploy desde Github
	
	Se puede hacer deploy directamente a un repositorio de Github
	``` 
	    now [usuario]/[repositorio]
	    
	```
	
	Pueden ver el resumen completo del curso **[aquí](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20Deploy%20con%20Now.sh)**.  
	Pueden ver mi lista de resúmenes **[aquí](https://github.com/MineiToshio/CursosPlatzi)**.

	* **Oswaldo Peralta** [349142] (2)

		Buen trabajo! muchas gracias por compartir!

* **Leonardo Araoz** (2) [214415](https://platzi.com/comentario/214415/) 

	Wow!! Esto me encanto!!! Espectacular

# Retos y Desafíos  [1487]

## 0190. Combinar muchos servicios [8424](https://platzi.com/clases/1139-deploy-now/8424-combinar-muchos-servicios/)

### Descripción:


### Comentarios:

* **Felipe Acosta** (3) [665009](https://platzi.com/comentario/665009/) 

	Este curso tendra actualizacion ?, he visto que Zeit ha agregado muchas funcionalidades nuevas incluso deploys cero configuracion.

* **Kerohuixco** (1) [650198](https://platzi.com/comentario/650198/) 

	Esta difícil el reto pero lo acepto. Lo haré y cuando lo tenga lo compartiré.

* **Carlos Eduardo Diaz Polanco** (0) [213194](https://platzi.com/comentario/213194/) 

	Estoy empezando en el mundo de la programación, despues del curso de Intruduccion a la terminal, viene este curso de Now, lo tome imaginando que en grado de dificultad le seguia, sin embargo no es asi…  
	Llevar acabo este ejercicio, seria casi imposible para mi, imagino que me quedara pendiente para mas adelante…  
	No es que no haya entendido nada, realmente entendí todo el proceso y los alcances de hacer deploy con [Now.sh](http://Now.sh), sin embargo creo que debería manejar varios de los lenguajes y tecnologias allí planteadas para poder entender a totalidad lo que Sergio hizo…
	
	No pierdo mi fe, en seguir aprendiendo, seguire avanzando.  
	me gustaria que me aconsejaran sobre la forma en que debo seguir la secuencia de los cursos, yo deseo especializarme en backend.

	* **sergiodxa** [213194] (6)

		Hay muchas opciones para ser backend, depende en realidad del lenguaje.
		
		Empezá por el curso de programación básica, luego elegí entre:
		
		* Desarrollador JavaScript
		* Desarrollo backend con Go
		* Desarrollo backend con Python
		* Desarrollo backend con Ruby
		* Desarrollo backend con PHP
		* Desarrollo de aplicaciones con [ASP.NET](http://ASP.NET)
		
		
		
		Y luego el curso de Docker.
		
		Cuando termines vas a poder volver acá para repasar como llevar tus proyectos a producción con Now.

## 0200. Usar un servicio diferente [8425](https://platzi.com/clases/1139-deploy-now/8425-usar-un-servicio-diferente/)

### Descripción:


### Comentarios:

* **Ronnie Moncayo** (2) [660304](https://platzi.com/comentario/660304/) 

	Una pregunta, docker admite muchas cosas, puedo correr una app dockerizada con Spring? o el docker igual debe ser de Node?

	* **Diego Alexander Forero Higuera (Platzi)** [660304] (4)

		Con docker puedes correr cualquier lenguaje dentro de [now.sh](http://now.sh), si no usas docker solo puedes correr aplicaciones hechas con JavaScript.

	* **Ronnie Moncayo** [660304] (1)

		Muchas gracias!

