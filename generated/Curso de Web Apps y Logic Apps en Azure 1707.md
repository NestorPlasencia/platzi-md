[Curso de Web Apps y Logic Apps en Azure 1707](https://platzi.com/cursos/web-apps)

# Introducción al curso [4633]

## 0010. Introducción a Web Apps en Azure [23126](https://platzi.com/clases/1707-web-apps/23126-introduccion-a-web-apps-en-azure/)

### Descripción:


### Comentarios:

* **carlosbazanhuaman** (1) [914223](https://platzi.com/comentario/914223/) 
docker esta en todo....

* **Jaime  Espinoza** (1) [780308](https://platzi.com/comentario/780308/) 
Empeze un curso de containers...alli se ve docker......gracias platzi por estar siempre adelante...

* **Uayeb Caballero Rodríguez** (1) [762830](https://platzi.com/comentario/762830/) 

	Azure ultimamente lo orilla mas a uno trabajar con docker!

# Web Apps [4632]

## 0020. Crear mi sitio web local en VS Code [23127](https://platzi.com/clases/1707-web-apps/23127-crear-mi-sitio-web-local-en-vs-code/)

### Descripción:


### Comentarios:

* **Alexander-Ponce-Castillo** (1) [963127](https://platzi.com/comentario/963127/) 

	visual studio code tengo que descargar?

	* **daniel alonso** [963127] (1)

		No necesariamente, lo que si debes tener es .Net Core <https://docs.microsoft.com/en-us/dotnet/core/>
		
		Pero para que sigas los ejercicios con mayor facilidad yo si te lo recomiendo.

* **OSCAR RODRIGUEZ** (1) [789826](https://platzi.com/comentario/789826/) 

	Muy buena introducción!

## 0030. Subiendo mi código a Github [23125](https://platzi.com/clases/1707-web-apps/23125-subiendo-mi-codigo-a-github/)

### Descripción:


### Comentarios:

* **Alexander-Ponce-Castillo** (1) [963134](https://platzi.com/comentario/963134/) 

	debería ser mas detallado supone que todos sabemos , que mal!! :c

	* **daniel alonso** [963134] (1)

		Si no haz tomado el curso de git y github, te recomiendo hacerlo. En caso contrario, ¿Cuál es tu duda?

## 0040. Estableciendo una integración continua con GitHub [23137](https://platzi.com/clases/1707-web-apps/23137-estableciendo-una-integracion-continua-con-github/)

### Descripción:


### Comentarios:

## 0050. Integración continua de mi aplicación [23138](https://platzi.com/clases/1707-web-apps/23138-integracion-continua-de-mi-aplicacion/)

### Descripción:


### Comentarios:

## 0060. Monitoreo de aplicaciones Web [23139](https://platzi.com/clases/1707-web-apps/23139-monitoreo-de-aplicaciones-web/)

### Descripción:


### Comentarios:

* **karolrojas** (1) [761823](https://platzi.com/comentario/761823/) 

	La clase se llama Monitoreo de aplicaciones Web y están presentando es una clase de Bases de Datos, creo que se equivocaron de clase

	* **Kevin Javier Morales** [761823] (1)

		Ya quedó la clase correcta. Gracias por reportarlo 😃

## 0070. Ajustes adicionales a mi sitio web [23140](https://platzi.com/clases/1707-web-apps/23140-ajustes-adicionales-a-mi-sitio-web/)

### Descripción:


### Comentarios:

* **karolrojas** (1) [761824](https://platzi.com/comentario/761824/) 

	En la clase anterior no se vieron gráficos, la clase anterior fue sobre Bases de Datos

	* **Kevin Javier Morales** [761824] (1)

		La clase anterior ya fue corregida 😃

## 0080. Instalar Wordpress con mi WebApp [23672](https://platzi.com/clases/1707-web-apps/23672-instalar-wordpress-con-mi-webapp/)

### Descripción:


Después de las clases en donde viste como trabajar con la integración continua de un sitio nos vamos a detener a ver una de las opciones más populares y recurrentes de las aplicaciones web. Me refiero, por supuesto al gestor de contenidos por excelencia. Wordpress. ¿Quieres comenzar?

Comienza por ir al portal de Azure y buscar **Wordpress** en la opción de nuevos recursos. Al hacerlo, aparecerá algo como esto.  
![tin1.png](https://static.platzi.com/media/user_upload/tin1-b9023f22-0cf9-42ec-9bd8-cafeaf2d9d43.jpg)  
Al seleccionar la opción de **Crear** verás un formulario muy parecido al de las Web Apps.  
![tin2.png](https://static.platzi.com/media/user_upload/tin2-6fe30d9e-7d49-4c34-9956-9fcc05e3e906.jpg)  
**Nombre de la aplicación:** Se trata de un nombre único debico a que será la URL del sitio.  
**Suscripción:** Tu suscripción de Azure  
**Grupo de recursos:** Puedes crear uno nuevo si eso te acomoda o asignar la solución a uno existente.  
**Proveedor de bases de datos:** Considerando que Wordpress trabaja con MySQL no hay mucho por hacer aquí, puedes ver que la opción está ya lista para continuar sin hacer nada. La segunda opción si expandes el control es la de **MySQL In App** , esto solo hace que la base de datos simule ser MySQL pero trabaje de una manera diferente.  
**Plan de servicio:** Si ya has creado algún sitio web entonces tendrás uno, de lo contrario deberás crearlo. Este plan es el plan que se encarga de los límites de hardware de tu sitio, te recomendaría crear uno para que veas todas las opciones que hay, escoge pensando en los fines para lo que usarás el sitio, recuerda que puedes cambiar en cualquier momento estos niveles.  
**Base de datos:** Como escogiste la opción de base de datos, entonces aquí debes abrir una nueva ventana para poder poner el nombre de la base de datos así como sus directivas de seguridad, en la siguiente imagen podrás ver cómo configuré mi base de datos (no olvides usar una contraseña muy segura).  
![tin3.png](https://static.platzi.com/media/user_upload/tin3-ef15e728-c2f3-42a7-aa02-8a31049b652b.jpg)  
Para la cuestión en el plan de tarifa primero selecciona la opción de **Básico** , ya sabes, estamos aprendiendo así que la opción menos costosa es buena idea por ahora. Puedes también reducir a un núcleo tu base de datos para disminuir el costo.  
![tin4.png](https://static.platzi.com/media/user_upload/tin4-37de8e7f-c760-459b-97e5-1d93c9cd7e0e.jpg)  
Si aceptas los parámetros que más te interesen y lo haces de nuevo en la segunda ventana (la de la configuración de la base de datos) el resultado final de tu ventana de configuración será el siguiente.  
![tin5.png](https://static.platzi.com/media/user_upload/tin5-2c498663-a0f9-4af0-9856-99f028bdf229.jpg)  
Si todo empata selecciona la opción de **Crear** y espera unos segundos a que la nueva instancia sea creada. Después de este tiempo viene entonces el mensaje de confirmación de que ya todo está listo.  
![tin6.png](https://static.platzi.com/media/user_upload/tin6-9ed279fb-3f3c-4bf9-92bc-440f8eefd858.jpg)  
Y si vas a tu nuevo recurso creado verás ya ahí tu nuevo sitio web, tu aplicación de telemetría y la base de datos de mysql que necesitamos.  
![tin7.png](https://static.platzi.com/media/user_upload/tin7-a9c54059-4926-4e21-bded-37d7363f789f.jpg)  
Selecciona tu aplicación web y en su menú principal podrás ver la dirección de la misma. Abre tu nuevo enlace y celebra si todo está hasta ahora en una pantalla de configuración de Wordpress. Escribe en este formulario tus datos. Si piensas hacer un sitio web privado, ten mucho cuidado con deshabilitar la última casilla, te permitirá ocultar al sitio de los motores de búsqueda.  
![tin8.png](https://static.platzi.com/media/user_upload/tin8-f6f5b12d-27cc-4499-9aa5-b26042be7b9d.jpg)  
Ahora si. ¡Festeja totalmente! Puedes empezar a utilizar tu escritorio de Wordpress sin problemas.  
![tin9.png](https://static.platzi.com/media/user_upload/tin9-da7b1108-9237-4602-9fbb-a9c5f986a37b.jpg)

### Comentarios:

# Logic Apps [4635]

## 0090. ¿Qué son las Logic Apps [23141](https://platzi.com/clases/1707-web-apps/23141-que-son-las-logic-apps/)

### Descripción:


### Links:

* [Logic App Service | Microsoft Azure](https://azure.microsoft.com/en-us/services/logic-apps/)

### Comentarios:

* **karolrojas** (3) [761858](https://platzi.com/comentario/761858/) 

	*Loggic Apps nos permite automatizar procesos simplemente realizando los pasos de arrastrar y pegar  
	*Loggic apps se divide en tres etapas, entrada, proceso y salida, ejm para las entradas (petición HTTP, Cola, Registro en Azure ), estas etapas pueden llevar condiciones y se configuran con lo pasos mencionados anteriormente (arrastrar y pegar)
	
	**no hay una cantidad de pasos definidos, los que se requieran** *

## 0100. Crear una Logic App y analizar un proceso [23142](https://platzi.com/clases/1707-web-apps/23142-crear-una-logic-app-y-analizar-un-proceso/)

### Descripción:


### Comentarios:

* **karolrojas** (2) [761869](https://platzi.com/comentario/761869/) 

	el proyecto que esta utilizando el profesor en la clase: <https://github.com/aminespinoza/ContenidoSQLAzure/tree/master/Proyectos>

* **carlosbazanhuaman** (1) [943975](https://platzi.com/comentario/943975/) 
esto se puede aplicar a métricas

## 0110. Recibir correos con noticias [23143](https://platzi.com/clases/1707-web-apps/23143-recibir-correos-con-noticias/)

### Descripción:


### Comentarios:

* **gal16v8d** (1) [1057576](https://platzi.com/comentario/1057576/) 

	Buenos Días,
	
	El navegador Chrome sera que tiene problemas con la creación de Logic Apps?  
	Me sale este error.  
	![error_gmail.PNG](https://static.platzi.com/media/user_upload/error_gmail-683b4e14-8765-4a74-a3d6-49a8f0cdaef4.jpg)

## 0120. Recordatorios a tu correo [23144](https://platzi.com/clases/1707-web-apps/23144-recordatorios-a-tu-correo/)

### Descripción:


### Comentarios:

## 0130. Compartir un tweet a correo electrónico [23145](https://platzi.com/clases/1707-web-apps/23145-compartir-un-tweet-a-correo-electronico/)

### Descripción:


### Comentarios:

## 0140. Enviar correos automáticos usando HTTP [23146](https://platzi.com/clases/1707-web-apps/23146-enviar-correos-automaticos-usando-http/)

### Descripción:


### Comentarios:

* **karolrojas** (1) [762181](https://platzi.com/comentario/762181/) 

	La clase no concuerda con el titulo

	* **Kevin Javier Morales** [762181] (1)

		Ya esta corregida 😃

# Cierre [4636]

## 0150. Cierre [23147](https://platzi.com/clases/1707-web-apps/23147-cierre/)

### Descripción:


### Links:

* [Curso de Git y GitHub Profesional 🔋 | Platzi](https://platzi.com/clases/git-github/)

* [Curso de Almacenamiento en Azure](https://platzi.com/clases/almacenamiento-azure/)

* [Curso de SQL en Azure](https://platzi.com/clases/sql-azure/)

### Comentarios:

* **Jorge Fernandez Conejeros** (1) [832018](https://platzi.com/comentario/832018/) 

	buen curso

* **Ronnie Moncayo** (1) [769486](https://platzi.com/comentario/769486/) 

	Un curso muy interesante, muchas gracias!

