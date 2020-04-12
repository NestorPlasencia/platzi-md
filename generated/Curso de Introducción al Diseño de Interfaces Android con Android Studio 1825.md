[Curso de Introducción al Diseño de Interfaces Android con Android Studio 1825](https://platzi.com/cursos/interfaces-android)

# Introduccion [5313]

## 0010. UI en Android ¿Por qué ¿Cómo [26254](https://platzi.com/clases/1825-interfaces-android/26254-ui-en-android-por-que-como/)

### Descripción:


### Comentarios:

* **Nolbert Juarez** (4) [1009085](https://platzi.com/comentario/1009085/) 

	En reasumen:
	
	**XML** (eXtensible Markup Language):  
	es un lenguaje de etiquetas, es decir, cada paquete de información está delimitado por dos **_etiquetas/tags_**  
	como se hace también en el lenguaje HTML, pero XML separa el contenido de la presentación.
	``` 
	    <H1>Mateo</H1><---HTML
	    <Nombre>Mateo</Nombre><---XML
	    
	```
	
	`<H1`> y `<Nombre>` son etiquetas/tags. Ambas encierran el texto o paquete de información _Mateo_. <br>  
	La etiqueta `<H1>` es de HTML, y se encarga de mostrar visualmente el texto _Mateo_ en la página web en un tamaño  
	determinado pero no dice nada del significado de _Mateo_ : si es una ciudad o un nombre, por ejemplo. <br>  
	En cambio la etiqueta `<Nombre>` es de XML y nos dice que _Mateo_ es un nombre de persona,  
	por lo tanto XML se preocupa del significado del texto que encierra y no de la apariencia de cómo se muestre el texto en la página web.  
	Por eso se dice que XML es un lenguaje de etiquetas, que como hemos dicho anteriormente, separa el contenido de la presentación.<br><br>  
	Los **tags** ( _etiquetas_ ) pueden tener **atributos** , que son una manera de incorporar características o propiedades a las etiquetas de un documento.  
	El atributo **consta de dos partes** : La **propiedad** del elemento y el **valor** de la propiedad,  
	que siempre va entre comillas doble (“) o simple (‘).
	``` 
	    <TAGatributo="valor">
	        Contenido
	    </TAG>
	    
	    <TAG-2atributo="valor"/>
	    
	```
	
	Ejemplo practico:
	``` 
	    <Datos-Nacimiento>
	        <Persona>
	           <Nombre>Mateo</Nombre>
	           <Fecha>15.10.2012</Fecha>
	           <Ciudad>Madrid</Ciudad>
	           <Peso>3.1Kg</Peso>
	           <Estatura>45cm</Estatura>
	        </Persona>
	        <Persona>
	           <Nombre>Maribel</Nombre>
	           <Fecha>11.09.2012</Fecha>
	           <Ciudad>Sevilla</Ciudad>
	           <Peso>3Kg</Peso>
	           <Estatura>40cm</Estatura>
	        </Persona>
	    </Datos-Nacimiento>
	    
	```
	
	* **namespaces** : es una forma de dar un _contexto_ (scope), a un tag.  
	Es definir donde un elemento tiene un valor definido.
	```    <NAMESPACE:TAGatr="val">
	        Contenido
	    </NAMESPACE:TAG>
	    
	```
	
	En otras palabras, es un medio para organizar clases dentro de un entorno,  
	agrupándolas de un modo más lógico y jerárquico. <br>  
	Ejemplo:
	```    <Profesor:Luis 
	        trabajo:horario="9-11"
	        trabajo:email="luisprof@uni.com"
	        persona:id="@user9283">
	    </Profesor:Luis>
	    
	```
	
	<br>  
	En Android veremos mucho el **_namespace_** de Androdid en la siguiente forma:
	
	
	``` 
	    <TextViewandroid:text="Hola mundo" />
	    
	```
	
	_¿Pero como saber de donde proviene un namespace?_ <br>  
	Con la palabra reservada `xmlns` y con un URI/dirección que harà a entender de donde  
	un xml tiene su procedencia, de esa manera xml va a poder entender cuando un valor tiene  
	o no tiene un contexto y cuando puede darle o asignarle un comportamiento.<br>  
	Siguiendo el ejemplo anterior:
	``` 
	    <...xmlns:android="http://schemas.android.com/apk/res/android"/>
	    
	```
	
	`android` es un alias asignado por nosotros. Podemos ver esto como una forma de encapsular otra etiqueta dentro una clase _Android_.

* **Miguel Angel Fuentes Garcia** (3) [1018831](https://platzi.com/comentario/1018831/) 

	* Un xml no es más que un lenguaje de marcado en cual se estructuran datos a través de tags.
	* Un tag es una forma de señalar datos.
	* Cuando un tag no tiene contenido como tal se conocen como inlinetag y se cierran directamente cuando se declaran.
	* Un namespace es una forma de darle contexto a un tag. Nos ayuda a entender dónde un tag tiene valor.
	* Los namespace provienen xmlns (xml namespace) donde vamos a darle una url de dónde un xml tiene su procedencia. De esta manera xml va a poder entender cuando tiene o no tiene un contexto y cuando puede darle o asignarle un comportamiento.
	
	

* **mariorm1106** (3) [1016977](https://platzi.com/comentario/1016977/) 

	Muy buena explicación de XML y NAMESPACE
	
	* xml Lenguaje de margado en TAG
	* NameSpace forma de conceptualista un xml
	
	

* **Brayan Mamani** (3) [1012719](https://platzi.com/comentario/1012719/) 

	❗ Excelente introducción ❗  
	✔️ XML  
	✔️ NameSpaces

* **miguelangelpglez** (3) [1011338](https://platzi.com/comentario/1011338/) 

	<hogar: laptop servicio=“8-2” usuario=“user”>  
	</hogar: laptop>

* **Diana Cañón** (3) [1008953](https://platzi.com/comentario/1008953/) 

	Excelente profesor, muy interesante.

* **Omar Mejia** (2) [1047522](https://platzi.com/comentario/1047522/) 

	la ruta de Desarrollo de Android no esta actualizada, no incluye este curso!

	* **Gabriel De Andrade** [1047522] (2)

		Hola! Ya la actualizamos, gracias por el reporte 😄 <https://platzi.com/desarrollo-android/>

	* **Valeria Calcina Cisneros** [1047522] (1)

		Hola Gabriel, una pregunta, ¿por que no incluyen el curso de Patrones de Diseño a esta ruta?

	* **Gabriel De Andrade** [1047522] (2)

		Hola Valeria! Gracias por el reporte, ya añadimos el Curso a la ruta y ya estamos revisando todo el contenido de la misma para asegurarnos de que no falten más cursos. 😄

* **Valeria Calcina Cisneros** (2) [1011993](https://platzi.com/comentario/1011993/) 

	 **UI en Android: ¿Por qué? ¿Cómo? (Clase 1)**  
	.  
	Introducción:  
	 **XML** ; es un lenguaje de marcado, que será estructurado en mediante tags (Atributos).  
	 **NameSpaces** ; es una forma de dar una categoría o contexto a un tag (No solo se usan en los tags) Un namespace puede provenir de **xmlns**.

* **Luis Enrique Lemus Hernandez** (2) [1010685](https://platzi.com/comentario/1010685/) 

	Nuevo material!!!

* **Jean Carlos Nuñez Hernandez** (1) [1052721](https://platzi.com/comentario/1052721/) 

	Los namespace se le pueden agregar atributos para darle mas sentido al tag en android

* **Giovani Fernandez** (1) [1008260](https://platzi.com/comentario/1008260/) 

	**Namespace: **  
	Es un contexto. Es definir donde un elemento tiene un valor definido.

* **Omar Mejia** (1) [84282](https://platzi.com/comentario/1047524/) 
¿Que curso debería tomar antes para familiarizarme con la terminologia?

	* **Valeria Calcina Cisneros** [84282] (1)

		Hola! Te recomendaria el curso de [Arquitectura Android](https://platzi.com/clases/arquitectura-android/), ya que es un curso muy completo que te ayudara a trabajar correctamente con el ciclo de vida de una actividad, que es necesario para el diseño e interfaces.  
		Saludos!

# Revisando los archivos para una UI [5314]

## 0020. Instalando Android Studio [26272](https://platzi.com/clases/1825-interfaces-android/26272-instalando-android-studio/)

### Descripción:


### Links:

* [https://developer.android.com/studio/](https://developer.android.com/studio/)

### Comentarios:

* **Brayan Mamani** (3) [1012728](https://platzi.com/comentario/1012728/) 

	❗ Guía de Instalación de Android Studio ❗  
	Disponible para Windows, Mac, Linux y Chrome OS.  
	➡️ <https://developer.android.com/studio/install>

* **ricardocelis (Platzi)** (3) [1008129](https://platzi.com/comentario/1008129/) 

	<https://developer.android.com/studio/>

* **Miguel Angel Fuentes Garcia** (2) [1018841](https://platzi.com/comentario/1018841/) 

	Recuerdo cuando teníamos que instalar eclipse con ADT, todo un dolor de cabeza, que bueno que ahora todo es más fácil.

* **ChristianEspino** (1) [1071333](https://platzi.com/comentario/1071333/) 

	Excelente explicación. ¡Todo listo!

* **alafourcadedespaigne** (1) [1054368](https://platzi.com/comentario/1054368/) 

	El titulo dice Instalando Android Studio e introducción a las carpetas de recursos y layouts  
	y lo unico que se hace es instalar el Android Studio, es decir , la introducci;on a las carpetas de recursos y layouts no est;a en este video

* **Jean Carlos Nuñez Hernandez** (1) [1052726](https://platzi.com/comentario/1052726/) 

	vamos a decargar android studio!

* **alonsohernandezsastre** (1) [1048757](https://platzi.com/comentario/1048757/) 

	Todo listo para continuar!

* **DidierMatos** (1) [1014402](https://platzi.com/comentario/1014402/) 

	Excelente por suerte ya lo tenía instalado, vamos ha por aprender más

* **Valeria Calcina Cisneros** (1) [1012002](https://platzi.com/comentario/1012002/) 

	Una instalacion muy facil 😄  
	[Android Studio](https://developer.android.com/studio/)  
	Aqui vamos!

* **Carlos Héctor Méndez Sánchez** (1) [1010513](https://platzi.com/comentario/1010513/) 

	muy bien empecemos

* **Moises Santos Andrade** (1) [82876](https://platzi.com/comentario/1014412/) 
No carga en mi i3 window 10 es muy lento, que hadware necesita androide studio

	* **Carlos José González Juan** [82876] (1)

		Una pregunta. ¿Cuanta memoria tienes?

## 0030. Enlazando nuestro layout con el código [26255](https://platzi.com/clases/1825-interfaces-android/26255-enlazando-nuestro-layout-con-el-codigo/)

### Descripción:


### Comentarios:

* **Miguel Angel Fuentes Garcia** (6) [1018879](https://platzi.com/comentario/1018879/) 

	 **Estructura de res:**
	
	* drawable: Representa gráficos (Todo aquello que pueda ser dibujado en una pantalla).
	* layout: Representa todas las estructuras de pantallas que creemos.
	* mipmap: Aquí guardaremos iconos.
	* values: Aquí administraremos los recursos (Colores, cadenas, dimensiones o arreglos).
	
	
	
	**Recursos más complejos:**
	
	* font: Aquí guardaremos las fuentes de la aplicación.
	* anim: Contendrá xml para animaciones.
	* xml: Contendrá preferencias de usuario y datos más complejos.
	* raw: Contendrá archivos como vídeos o audios.
	
	

* **Valeria Calcina Cisneros** (4) [1012019](https://platzi.com/comentario/1012019/) 

	jaja la emocion que tuve al ver mi pantalla no se compara con nada 😊

* **Sergio Romo Medina** (2) [1031800](https://platzi.com/comentario/1031800/) 

	Se ve muy completo

* **Brayan Mamani** (2) [1017113](https://platzi.com/comentario/1017113/) 

	❗ Estructura de res: Recursos ❗
	
	📁 drawable: Images  
	📁 layout: Diseños  
	📁 mipmap: Logos  
	📁 values  
	📄 colors.xml: Colores  
	📄 strings.xml: Textos  
	📄 styles.xml: Temas  
	📄 dimens.xml: Dimensiones

* **Carlos Héctor Méndez Sánchez** (2) [1014979](https://platzi.com/comentario/1014979/) 

	Excelente se ve que el curso va a tener un poco de código

* **Jean Carlos Nuñez Hernandez** (1) [1052731](https://platzi.com/comentario/1052731/) 

	Package Name identificador unico en play store

* **Jorge Ronald Vargas Portillo** (1) [1018739](https://platzi.com/comentario/1018739/) 

	buen comienzo

* **Manuel Pinzón** (1) [1018399](https://platzi.com/comentario/1018399/) 

	Esta genial…😃

* **miguelangelpglez** (1) [82727](https://platzi.com/comentario/1011397/) 
Mi proecto se queda procesando al tratar de abrir esta laout, que ocurre?

	* **Valeria Calcina Cisneros** [82727] (2)

		Hola! a mi me paso lo mismo al iniciar, pero decidi esprerar y cargo, solo ten paciencia 😉

# Creando una UI [5315]

## 0040. La vista de diseño en Android Studio [26256](https://platzi.com/clases/1825-interfaces-android/26256-la-vista-de-diseno-en-android-studio/)

### Descripción:


### Comentarios:

* **Valeria Calcina Cisneros** (4) [1012028](https://platzi.com/comentario/1012028/) 

	Les recomiendo primero tomar el [Curso de Bases Técnicas de Android](https://platzi.com/clases/tecnico-android/) ya que ahi les enseñara la teoría de Android, como el ciclo de vida de una **Activity** y demás…  
	Saludos!

* **Miguel Angel Fuentes Garcia** (3) [1018893](https://platzi.com/comentario/1018893/) 

	* La clase R es auto generada y a través de ella podemos enlazar nuestros recursos (layout, drawable, color, string etc.) con nuestras clases.
	
	

* **Nolbert Juarez** (3) [1009317](https://platzi.com/comentario/1009317/) 

	En reasumen:  
	Cuando compilas tu aplicación, cada archivo de diseño XML se compila en un recurso `View`.  
	Debes cargar el recurso de diseño desde el código de tu aplicación, en la implementación de devolución de llamada `Activity.onCreate()`.  
	Para eso, llama a `setContentView()` pasando la referencia a tu recurso de diseño en forma de `R.layout.layout_file_name.`
	
	Por ejemplo, mirando el diseño XML _activity_main.xml_ que nos crea Android Studio al crear un _empty project_ ,  
	para poder cargarlo en nuestra actividad lo hariamos de la siguiente manera:
	``` 
	    overridefunonCreate(savedInstanceState: Bundle?) {
	        super.onCreate(savedInstanceState)
	        setContentView(R.layout.activity_main)
	    }
	    
	```
	
	La clase **R** es una clase que **tiene referencia directa a los recursos dentro del package _res_**.  
	Por ejemplo podriamos acceder al valor _app_name_ dentro del recurso _strings.xml_ asi:
	``` 
	    println(R.string.app_name)
	    
	```

* **Jean Carlos Nuñez Hernandez** (1) [1053515](https://platzi.com/comentario/1053515/) 

	la clase R es autogenerada

* **Jean Carlos Nuñez Hernandez** (1) [1053487](https://platzi.com/comentario/1053487/) 

	La clase R tiene referencia a cada uno de los layout

* **Jorge Ronald Vargas Portillo** (1) [1018799](https://platzi.com/comentario/1018799/) 

	muy buena explicación

* **Brayan Mamani** (1) [1017309](https://platzi.com/comentario/1017309/) 

	❗ Referencia de XML ❗  
	✔️ Java  
	✔️ Kotlin

* **Carlos Héctor Méndez Sánchez** (1) [1014988](https://platzi.com/comentario/1014988/) 

	es una excelente explicación para hacer referencia nuestras pantallas y propiedades

* **Valeria Calcina Cisneros** (1) [1012035](https://platzi.com/comentario/1012035/) 

	(Una pequeña informacion que encontre sobre Layout Main)  
	.  
	En Android, el diseño visual se almacena en archivos XML y cada actividad está asociada a un diseño.  
	.  
	setContentView(R.layout.main)  
	.  
	**R** significa recurso
	
	**layout** significa diseño
	
	**main** es el xml que has creado bajo res->layout->main.xml
	
	Siempre que desee cambiar el aspecto actual de una Actividad o cuando pase de una Actividad a otra, la nueva Actividad debe tener un diseño para mostrar. Llamamos setContentView onCreate con el diseño deseado como argumento.  
	.  
	(onCreate es la primera fase del ciclo de vida de un Activity)

## 0050. La vista de texto en Android Studio [26257](https://platzi.com/clases/1825-interfaces-android/26257-la-vista-de-texto-en-android-studio/)

### Descripción:


### Comentarios:

* **David Luna** (5) [1009799](https://platzi.com/comentario/1009799/) 

	A partir del minuto 3:12 deberían haber cambiado a la pantalla del profesor. Se le ve explicando algo pero no lo vemos en la pantalla.

* **Miguel Gutiérrez Rodríguez** (3) [1021742](https://platzi.com/comentario/1021742/) 

	En inglés a esta **“vista de diseño”** , se le conoce como **“layout editor”**. (Para que no se confundan si algún día están leyendo la documentación y no saben lo que es el layout editor).

* **Luis David Campos Solorio** (3) [1008734](https://platzi.com/comentario/1008734/) 

	Nota: En la versión 3.6 de AS el menú para ver el diseño y el código al mismo tiempo ahora esta arriba a la derecha.

* **Brayan Mamani** (2) [1017324](https://platzi.com/comentario/1017324/) 

	 **Android Studio** nos ofrece dos tipos de vistas para trabajar en nuestro proyecto:  
	✔️ Design: Diseño  
	✔️ Text: Texto

* **Carlos Héctor Méndez Sánchez** (2) [1015001](https://platzi.com/comentario/1015001/) 

	a mi siempre me aparece la ventana de diseño pero siempre si bueno conocer ambos casos, los xml y la ventana de gráfica para crear interfaces

* **Miguel Gutiérrez Rodríguez** (1) [83205](https://platzi.com/comentario/1021743/) 
¿Alguien sabe de algún estándar tipo coding style para los xml en Android?

# Widgets y Vistas [5316]

## 0060. ViewGroup y View Diferencias básicas [26258](https://platzi.com/clases/1825-interfaces-android/26258-viewgroup-y-view-diferencias-basicas/)

### Descripción:


### Comentarios:

* **Nolbert Juarez** (3) [1009349](https://platzi.com/comentario/1009349/) 

	En reasumen:
	
	* **View** : es un elemento que se va a mostrar por pantalla así como tal. 
	  * TextView
	  * ImageView
	  * EditText
	* **ViewGroup** : es un elemento que sirve para agrupar elementos. Nota: cuando tenemos un grupo de elementos dentro de un ViewGroup, los cambios que hagamos sobre este afectaran los elementos dentro de el.  
	Ejemplo:
	```    <LinearLayout android:gravity="start"
	    	<TextView />
	    	<ImageView />
	    	<EditText />
	    </LinearLayout>
	    
	```
	
	Si cambiamos el **atributo**`gravity="center"`, todos los elementos se moverán al centro de la pantalla.
	
	

* **Valeria Calcina Cisneros** (2) [1053008](https://platzi.com/comentario/1053008/) 

	Sin duda, este curso sera fácil de adaptarse 😉

* **Brayan Mamani** (2) [1017343](https://platzi.com/comentario/1017343/) 

	En nuestro proyecto **Android** podemos encontrarnos con:  
	✔️ View Group: Almacena un grupo de view.  
	✔️ View: Vista de diseño.

* **Carlos Héctor Méndez Sánchez** (2) [1015020](https://platzi.com/comentario/1015020/) 

	me recuerda cuando empezaba en visual basic o java de alinear u ordenar por código

* **Jean Carlos Nuñez Hernandez** (1) [1053557](https://platzi.com/comentario/1053557/) 

	ViewGroup -> Contiene un conjunto de view y las propiedades que agregue los objetos dentro se veran afectado.
	
	View -> Vista de diseño

## 0070. Atributos importantes alto, ancho y id [26259](https://platzi.com/clases/1825-interfaces-android/26259-atributos-importantes-alto-ancho-y-id/)

### Descripción:


### Comentarios:

* **Nolbert Juarez** (5) [1009365](https://platzi.com/comentario/1009365/) 

	En reasumen:  
	`android:layout_width`,`android:layout_height`: nos permiten especificar el ancho y la altura con medidas exactas,  
	aunque probablemente no quieras hacerlo con mucha frecuencia.
	
	Generalmente, usarás una de estas constantes para establecer el ancho o la altura:
	
	* **wrap_content** : indica a tu vista que modifique su tamaño conforme a los requisitos de este contenido.
	* **match_parent** indica a tu vista que se agrande tanto como lo permita su grupo de vistas principal.
	
	
	
	En general, no se recomienda especificar el ancho ni la altura de un diseño con unidades absolutas como píxeles. En cambio, el uso de medidas relativas como unidades de píxeles independientes de densidad ( **dp** ), **wrap_content**  
	o **match_parent** es un mejor enfoque, ya que ayuda a garantizar que tu aplicación se muestre correctamente en dispositivos con pantallas de diferentes tamaños.

* **Valeria Calcina Cisneros** (2) [1053026](https://platzi.com/comentario/1053026/) 

	Este curso esta realmente completo :0

* **Carlos Héctor Méndez Sánchez** (2) [1015069](https://platzi.com/comentario/1015069/) 

	es como css que le das propiedades a los archivos

* **Jean Carlos Nuñez Hernandez** (1) [1053571](https://platzi.com/comentario/1053571/) 

	"color/red podemos referencial el color que creamos y usarlo en nuestro objeto

* **Jean Carlos Nuñez Hernandez** (1) [1053564](https://platzi.com/comentario/1053564/) 

	Al cambiar la propiedad layout_height va a empujar hasta el final al siguiente objeto

## 0080. Otros atributos y el namespace tools [26260](https://platzi.com/clases/1825-interfaces-android/26260-otros-atributos-y-el-namespace-tools/)

### Descripción:


### Comentarios:

* **Nolbert Juarez** (6) [1009435](https://platzi.com/comentario/1009435/) 
<h1>En reasumen:</h1>
	
	## `android:id`
	
	Cualquier objeto **View** puede tener un **ID** entero asociado para identificarse de forma única dentro del árbol.  
	Cuando se compila la aplicación, se hace referencia a este ID como un número entero, pero el ID se asigna normalmente en el archivo XML de diseño como una _string_ del atributo id.  
	Este es un atributo XML común para todos los objetos View (definido por la clase View) y lo utilizarás muy a menudo.  
	La sintaxis de un ID dentro de una etiqueta XML es la siguiente: `android:id="@+id/my_button"`
	
	## Atributos específicos y atributos compartidos
	
	Existen atributos compartidos y otros específicos para cada elemento.  
	Por ejemplo, el atributo `android:background`, que nos permite establecer un color, es un atributo que existe para todos los elementos de `android`; el atributo `android:hint="Enter password"` es un atributo especifico de la View `EditText`
	
	## Namespace tools
	
	Si en algún momento no quieres utilizar un atributo especifico y quieres solamente utilizarlo en tiempo de diseño para poder ver como se vería, existe un namespace denominado tools.  
	Es un namespace que nos permite ver en tiempo de diseño como se verá nuestra aplicación sin generar una versione final de la aplicación con esos valores.
	
	Por ejemplo, si se establece el valor del atributo `android:text` durante el tiempo de ejecución o si quieres ver el diseño con un valor diferente del valor predeterminado, puedes agregar `tools:text` para especificar texto solo para la vista previa de diseño.  
	![img](https://developer.android.com/studio/images/write/tools-attribute-text_2x.png)

* **kikeRC** (4) [1016244](https://platzi.com/comentario/1016244/) 

	El namespace tools, nos brinda la posibilidad de poder modelar de manera segura nuestra aplicación, ya que a un TexView le podemos colocar el texto en tiempo de diseño y este no se vera reflejado cuando la app se este ejecutando.
	``` 
	       <TextView
	            android:id="@+id/tvMainTitle"
	            android:layout_width="match_parent"
	            android:layout_height="wrap_content"
	            android:background="@color/colorAccent"
	            tools:text="Hello Kike!"
	             />
	    
	```

* **Valeria Calcina Cisneros** (2) [1053424](https://platzi.com/comentario/1053424/) 

	Namespace juega un gran papel en el Diseño de Interfaces 😄

* **Manuel Pinzón** (2) [1020831](https://platzi.com/comentario/1020831/) 

	Super bien explicado…

* **Jean Carlos Nuñez Hernandez** (1) [1053623](https://platzi.com/comentario/1053623/) 

	sP para el tamaño del texto, ejemplo tools:textSize=“70sP”

* **Jean Carlos Nuñez Hernandez** (1) [1053592](https://platzi.com/comentario/1053592/) 

	@mipmap -@drawable para colocar imagenes

* **Jean Carlos Nuñez Hernandez** (1) [1053584](https://platzi.com/comentario/1053584/) 

	elemento id utiliza este formato “@+id/tvMainTitle”

# Layouts base [5317]

## 0090. LinearLayout Organizacion lineal [26261](https://platzi.com/clases/1825-interfaces-android/26261-linearlayout-organizacion-lineal/)

### Descripción:


### Links:

* [GitHub - sierisimo/Android-Interfaces-PlatziMusic at 01-linear-layout](https://github.com/sierisimo/Android-Interfaces-PlatziMusic/tree/01-linear-layout)

### Comentarios:

* **ricardocelis (Platzi)** (4) [1008133](https://platzi.com/comentario/1008133/) 

	<https://github.com/sierisimo/Android-Interfaces-PlatziMusic/tree/01-linear-layout>

* **ricindigus** (3) [1014424](https://platzi.com/comentario/1014424/) 

	LinearLayout distribuye los objetos de manera lineal ya sea vertical (uno debajo de otro) u horizontal (uno a continuacion del otro)  
	Y es cierto que podemos combinar y tener un linear layout vertical que tenga otros linearlayouts horizontales con lo cual tendriamos cuadriculas. Pero esto resulta poco optimo en una app, sobrecargas el arbol ,recuerden que cuando android lee el xml genera un arbol, y mientras mas anidado, mas complejo se vuelve el arbol y mientras mas viewgroups mas pesado es, con lo cual se hace menos optimo, por lo cual es un layout que debe usarse con cuidado y evitar anidar, es importante saberlo por que con linearlayout tecnicamente puedes diseñar lo que sea y eso hace que la mayoria de los programadores cuando inician lo usen para todo sin notar lo poco optimo que estan haciendolo. de preferencia es aprender a usar los otros como relative layout, que nos permite hacer mas anidando menos y teniendo menos viewgroups, y mejor aun , aprender ConstraintLayout (el papá de los layouts XD) con el cual puedes generar interfaces mucho mas rapido y de una manera mucho mas optima, pero para empezar y solo para empezar esta bien linearlayout, pero deben ser conscientes de sus pros y CONTRAS.

	* **sierisimo** [1014424] (2)

		Sin duda es bueno entender las diferencias, es por ello que incluimos las siguientes 5 clases para explicar como la misma vista se puede hacer con los otros layouts que mencionas.
		
		Tambien por ello dejamos al ultimo `ConstraintLayout`, para poder ver la diferencia mas notable entre usar `LinearLayout` anidado y usar un `ConstraintLayout` que ya no requiere de anidaciones.

* **alonsohernandezsastre** (2) [1049889](https://platzi.com/comentario/1049889/) 

	Genial uso del linear Layout

* **Miguel Angel Fuentes Garcia** (2) [1019211](https://platzi.com/comentario/1019211/) 

	* La diferencia entre android:layout_gravity=“center” y android:gravity=“center” es que el primero solo afecta al elemento como tal y el segundo afecta a todos los elementos hijos.
	
	

* **Eduardo P. Rivero** (2) [1016865](https://platzi.com/comentario/1016865/) 

	Documentación y Referencia de LinearLayout
	
	<https://developer.android.com/guide/topics/ui/layout/linear>
	
	<https://developer.android.com/reference/kotlin/android/widget/LinearLayout?hl=en>

	* **Manuel Pinzón** [1016865] (2)

		Excelente información…

* **Valeria Calcina Cisneros** (1) [1054978](https://platzi.com/comentario/1054978/) 

	Esta clase me fascino! Jamas pensé que podría diseñar una interfaz (":

* **Valeria Calcina Cisneros** (1) [1054757](https://platzi.com/comentario/1054757/) 

	En [esta pagina](https://html-color-codes.info/codigos-de-colores-hexadecimales/) pueden escoger colores HTML

* **Jean Carlos Nuñez Hernandez** (1) [1053679](https://platzi.com/comentario/1053679/) 

	weight para darle peso y el componente lo pasa para abajo

* **Jean Carlos Nuñez Hernandez** (1) [1053677](https://platzi.com/comentario/1053677/) 

	Space es un espacio vacio

* **Jean Carlos Nuñez Hernandez** (1) [1053651](https://platzi.com/comentario/1053651/) 

	layout_gravity solo afecta al elemento

* **Jean Carlos Nuñez Hernandez** (1) [1053641](https://platzi.com/comentario/1053641/) 

	dp density point

* **DNAvacio** (1) [83266](https://platzi.com/comentario/1023306/) 
Lo de las imagenes no me queda muy claro, se que las direcciones mostradas son que de ahi va a sacar las imagenes dependiendo de la panta...

	* **sierisimo** [83266] (1)

		Si es asi de “automatico”. Android va a determinar la resolución de tu pantalla y buscar la imagen que mejor se adapte para ella, lo ideal en todo caso es que tu agregues cada una de las diferentes dimensiones para evitar que quien use tu app note pixeleado o que la imagen se estira.
		
		Puedes ver mas información (en ingles) en este link: <https://developer.android.com/training/multiscreen/screendensities>

* **Manuel Pinzón** (1) [83167](https://platzi.com/comentario/1020952/) 
Como hago para cargar el logo de Platzi…? Gracias.

## 0100. RelativeLayout organizando con referencias [26262](https://platzi.com/clases/1825-interfaces-android/26262-relativelayout-organizando-con-referencias/)

### Descripción:


### Links:

* [GitHub - sierisimo/Android-Interfaces-PlatziMusic at 02-relativelayout](https://github.com/sierisimo/Android-Interfaces-PlatziMusic/tree/02-relativelayout)

### Comentarios:

* **Zorayda Gutiérrez Montes** (2) [1043525](https://platzi.com/comentario/1043525/) 

	Quiero una camiseta como la suya profe. Está muy way

* **Eduardo P. Rivero** (2) [1016868](https://platzi.com/comentario/1016868/) 

	Documentación y Referencia de RelativeLayout
	
	<https://developer.android.com/guide/topics/ui/layout/relative>
	
	<https://developer.android.com/reference/kotlin/android/widget/RelativeLayout?hl=en>

* **Valeria Calcina Cisneros** (1) [1054991](https://platzi.com/comentario/1054991/) 

	Al parecer Android venia todo preparado para los desarrolladores 😄

## 0110. RelativeLayout Uso práctico [26273](https://platzi.com/clases/1825-interfaces-android/26273-relativelayout-uso-practico/)

### Descripción:


### Links:

* [GitHub - sierisimo/Android-Interfaces-PlatziMusic at 02-relativelayout](https://github.com/sierisimo/Android-Interfaces-PlatziMusic/tree/02-relativelayout)

### Comentarios:

* **ricindigus** (3) [1014435](https://platzi.com/comentario/1014435/) 

	RelativeLayout tiene la ventaja que te permite generar vistas usando menos viewgroups para estructurarlas. haciendo el arbol jerarquico menos pesado.

* **Miguel Angel Fuentes Garcia** (2) [1019244](https://platzi.com/comentario/1019244/) 

	¿Cómo sabemos que layout nos conviene más?, ¿El que utilice menos código?

	* **sierisimo** [1019244] (3)

		No hay como tal una respuesta directa a cual layout es mejor.
		
		La realidad es que bajo diferentes tipos de vistas, vas a tener diferentes tipos de layouts involucrados. Por ejemplo, si lo que estas haciendo es una aplicacion que tiene una lista de contactos… tal vez `RelativeLayout` sea demasiado complejo comparado con un simple `LinearLayout`. Pero si estas haciendo un parte donde vez la foto de un contacto… tal vez `RelativeLayout` o `ConstraintLayout` se ajuste mejor.

	* **Miguel Gutiérrez Rodríguez** [1019244] (3)

		En realidad si lo que vas a mostrar es una lista de contactos, hacerlo con LinearLayout, no sería una buena práctica. En Android existen Views con la función de listar elementos, el más recomendado es RecyclerView, pero también tienes ListView.
		
		Y hablando acerca de cuál es el layout que deberías usar. Google ha sido claro desde los Google IO del 2017 que ConstraintLayout es un RelativeLayout que funciona. ConstraintLayout es el ViewGroup más poderoso que tiene Android hasta la fecha. No significa que LinearLayout ya no se use, pero al menos de manera personal yo sólo puedo recomendar usar ConstraintLayout como el ViewGroup principal de todos nuestros layouts.

	* **sierisimo** [1019244] (2)

		Puntos interesantes son mencionados por Migue_Nightcore, me gustaria aclarar algunos puntos:
		
		  1. Cuando tienes una vista donde los elementos van “alineados” uno despues de otro, `LinearLayout` es simple y util. Sin embargo si tus elementos son varios y no caben bien en pantalla, puedes utilizar un simple `ScrollView` con un `LinearLayout` interno.
		  2. Si tus elementos son mas complejos que simples `TextView` o por ejemplo, son cargados “dinamicamente”, donde no puedes definir el id para cada uno, o simpelmente tienes muchisimos, es mejor utilizar un `RecyclerView`, que es una libreria adicional que debes incluir en tu proyecto, el uso de `ListView` ya no es tan recomendado.
		  3. `ConstraintLayout` tiene muchisimas ventajas, sobre muchos otros tipos de `ViewGroup`, la principal es que como cada elemento dentro del layout esta alineado con respecto a otro elemento, si un elemento llega a cambiar de posicion, todos aquellos que esten alineados tambien haran ajustes para mantener su alineación. Adicional a esto hay algunos elementos no visuales que te pueden ayudar a alinear tus elementos, como `Guideline` o `Barrier`.
		
		
		
		La cuestión al final es que tomes la mejor decisión con respecto a la vista de tu apliación. Cada layout tiene sus ventajas sobre los otros, aunque `ConstraintLayout` es muy poderoso, puede que sea un poco exagerado para algunos casos donde un `LinearLayout` o un `GridLayout` habrian sido mas simples de usar.

	* **Jean Carlos Nuñez Hernandez** [1019244] (1)

		Pienso que si, pero segun lo que dice sierisimo este tipo de layout da la ventaja que es adaptable a cualquier pantalla ya que su aliniacion es por bellow reference

* **Jean Carlos Nuñez Hernandez** (1) [1053733](https://platzi.com/comentario/1053733/) 

	Es mas productivo trabajar con este tipo layout

	* **Valeria Calcina Cisneros** [1053733] (1)

		al parecer si

## 0120. FrameLayout Alineación por region [26263](https://platzi.com/clases/1825-interfaces-android/26263-framelayout-alineacion-por-region/)

### Descripción:


### Comentarios:

* **Miguel Angel Fuentes Garcia** (3) [1019286](https://platzi.com/comentario/1019286/) 

	* Con FrameLayout podemos organizar vistas unas sobre otras como si fueran capas y ajustar sus atributos layout_gravity para que tomen la posición que indique nuestro diseño. También podemos agregar vistas dinámicas.
	
	

* **Jean Carlos Nuñez Hernandez** (1) [1053744](https://platzi.com/comentario/1053744/) 

	Framelayout recomienda tene un solo hijo o vista interno para el performace de la aplicacion

* **Jean Carlos Nuñez Hernandez** (1) [1053737](https://platzi.com/comentario/1053737/) 

	Framelayout crece tanto como lo necesitemos

## 0130. FrameLayout Uso práctico [26264](https://platzi.com/clases/1825-interfaces-android/26264-framelayout-uso-practico/)

### Descripción:


### Links:

* [GitHub - sierisimo/Android-Interfaces-PlatziMusic at 03-FrameLayout](https://github.com/sierisimo/Android-Interfaces-PlatziMusic/tree/03-FrameLayout)

### Comentarios:

* **ricindigus** (5) [1014477](https://platzi.com/comentario/1014477/) 

	El framelayout normalmente se utiliza para tener solo un elemento el cual podras sustituir como una imagen, si pones mas vistas estan se iran superponiendo como una pila de capas,donde la mas reciente agregada se vera primero , asi que algunos lo usan para sus placeholder. otros para mostrar un elemento encima de otro, por las capas. pero no es usado para diseñar toda una interfaz, como el login, imaginate poner margin o gravity a todo.

	* **sierisimo** [1014477] (4)

		Exacto! Justo eso es lo que tratamos de demostrar al hacer la misma pantalla con diferentes layouts, para dar ejemplos de como algunos layouts pueden aplicar mejor que otros segun el diseño de tu pantalla

* **ricindigus** (5) [1014449](https://platzi.com/comentario/1014449/) 

	Un dato: Si es cierto q los dp es una unidad de medida que usa android para lo que es el espacio en pantalla. Fue creada para estandarizar una forma de medida, ya que Android tiene una gran cantidad de pantallas con densidades de pixeles muy variadas.  
	Bueno pero **android teniendo esta medida de DPs, divide cualquier pantalla en una cuadricula (como un cuaderno cuadriculado) donde cada cuadradito es de 8dp x 8dp,** por esa razon es bueno intentar diseñar teniendo esa regla para las medidas de los views, paddings, margenes, imagenes,iconos,etc. : multiplos de 8 (8dp.16dp, 24 dp), por ejemplo si vas a poner altura a un appBar, no pongas 60, ponle 64, o si pones una altura para esa imageview y quieres poner 20 no pongas 20, ponle 16 o 24, osea siempre intenta llevar tus medidas a multiplos de 8 , es una recomendacion que hacen en la documentacion oficial. esto explica algo que veran constantemente en Android Studio, cuando el IDE autogenera alguna medida normalmente pone 8dp, 16dp, 24dp, etc . por ejemplo cuando estas usando los constraint layout y quieres poner margenes ,android studio te sugiere 8,16,24,etc…esto es por** la famosa regla de 8** anteriormente mencionada.

* **Eduardo P. Rivero** (3) [1016906](https://platzi.com/comentario/1016906/) 

	Referencia a FrameLayout
	
	<https://developer.android.com/reference/kotlin/android/widget/FrameLayout?hl=en>

* **ricardocelis (Platzi)** (3) [1008144](https://platzi.com/comentario/1008144/) 

	<https://github.com/sierisimo/Android-Interfaces-PlatziMusic/tree/03-FrameLayout>

* **Valeria Calcina Cisneros** (1) [1055681](https://platzi.com/comentario/1055681/) 

	Hasta ahora hay muchos Layouts y todos son muy buenos :0

## 0140. Layouts externos ConstraintLayout [26265](https://platzi.com/clases/1825-interfaces-android/26265-layouts-externos-constraintlayout/)

### Descripción:


### Links:

* [GitHub - sierisimo/Android-Interfaces-PlatziMusic at 04-constraintlayout](https://github.com/sierisimo/Android-Interfaces-PlatziMusic/tree/04-constraintlayout)

### Comentarios:

* **ricardocelis (Platzi)** (4) [1008159](https://platzi.com/comentario/1008159/) 

	<https://github.com/sierisimo/Android-Interfaces-PlatziMusic/tree/04-constraintlayout>

* **ricindigus** (3) [1014481](https://platzi.com/comentario/1014481/) 

	El papa de los layout, con este layout haces de todo.

* **Jorge Ronald Vargas Portillo** (2) [1018923](https://platzi.com/comentario/1018923/) 

	este es el que creo que mejor ordena

	* **sierisimo** [1018923] (1)

		Nota un detalle: El `ConstraintLayout` no hace el ordenamiento por si mismo. Por cada elemento que agreguemos, debemos decirle como alinearlo con respecto a otros elementos de la pantalla. Aunque si, podemos hacer cosas mas atractivas con este layout, tenemos que recordar que el como se organizan las cosas depende totalmente de nosotros.

* **mariorm1106** (2) [1018810](https://platzi.com/comentario/1018810/) 

	Mejora mucho al forma de ordenar con respecto a los demás elementos

* **Jean Carlos Nuñez Hernandez** (1) [1053772](https://platzi.com/comentario/1053772/) 

	ConstraintLayout es como RelativeLayout pero la diferencia es que los elementos reacciona dependiendo de como se acomodan

# Estilos y temas [5318]

## 0150. ¿Qué es un estilo [26266](https://platzi.com/clases/1825-interfaces-android/26266-que-es-un-estilo/)

### Descripción:


### Links:

* [GitHub - sierisimo/Android-Interfaces-PlatziMusic at 05-styles](https://github.com/sierisimo/Android-Interfaces-PlatziMusic/tree/05-styles)

### Comentarios:

* **ricindigus** (4) [1014483](https://platzi.com/comentario/1014483/) 

	un buen post para diferenciar un estilo y un tema.  
	<https://medium.com/androiddevelopers/android-styling-themes-vs-styles-ebe05f917578>

* **ricardocelis (Platzi)** (3) [1008160](https://platzi.com/comentario/1008160/) 

	<https://github.com/sierisimo/Android-Interfaces-PlatziMusic/tree/05-styles>

* **Valeria Calcina Cisneros** (1) [1055932](https://platzi.com/comentario/1055932/) 

	Nota: una etiqueta style es muy similar a la herencia

* **Jean Carlos Nuñez Hernandez** (1) [1053787](https://platzi.com/comentario/1053787/) 

	estilo es la forma como nuestra aplicacion muestra su imagen o su apariencia

## 0160. ¿Qué es un tema [26267](https://platzi.com/clases/1825-interfaces-android/26267-que-es-un-tema/)

### Descripción:


### Links:

* [GitHub - sierisimo/Android-Interfaces-PlatziMusic at 06-temas](https://github.com/sierisimo/Android-Interfaces-PlatziMusic/tree/06-temas)

### Comentarios:

* **Eduardo P. Rivero** (4) [1017380](https://platzi.com/comentario/1017380/) 

	Documentación oficial de temas y estilos.
	
	<https://developer.android.com/guide/topics/ui/look-and-feel/themes>

* **ricardocelis (Platzi)** (4) [1008161](https://platzi.com/comentario/1008161/) 

	<https://github.com/sierisimo/Android-Interfaces-PlatziMusic/tree/06-temas>

* **Jean Carlos Nuñez Hernandez** (2) [1053801](https://platzi.com/comentario/1053801/) 

	Un tema es un estilo aplicado globalmente

* **Laura Perez Toledo** (1) [1018793](https://platzi.com/comentario/1018793/) 

	Vi que para el color rojo del background quedo sin querer una “f” minúscula, tiene algo que ver que eso haya afectado la imagen y no al botón o da lo mismo escribir los hexadesimales con mayúsculas que con minúsculas?

	* **sierisimo** [1018793] (4)

		El uso de mayusculas vs minusculas (o incluso combinaciones de ellas) no afecta el valor del color. En proyectos del mundo real es mas un acuerdo entre la gente del proyecto que un una regla de oro.

## 0170. Distribuyendo nuestros valores [26268](https://platzi.com/clases/1825-interfaces-android/26268-distribuyendo-nuestros-valores/)

### Descripción:


### Comentarios:

* **Manuel Pinzón** (3) [1033635](https://platzi.com/comentario/1033635/) 

	<https://developer.android.com/training/multiscreen/screendensities?hl=es>

* **Jean Carlos Nuñez Hernandez** (1) [1053845](https://platzi.com/comentario/1053845/) 

	Primero se resuelve el elemento despues el estilo y al final se tomara el tema

# Extendiendo los widgets [5319]

## 0180. Agregando widgets externos [26269](https://platzi.com/clases/1825-interfaces-android/26269-agregando-widgets-externos/)

### Descripción:


### Links:

* [GitHub - sierisimo/Android-Interfaces-PlatziMusic at 08-elementos-externos](https://github.com/sierisimo/Android-Interfaces-PlatziMusic/tree/08-elementos-externos)

### Comentarios:

* **ricardocelis (Platzi)** (6) [1008164](https://platzi.com/comentario/1008164/) 

	<https://github.com/sierisimo/Android-Interfaces-PlatziMusic/tree/08-elementos-externos>

* **Luis Arturo Lira Cerda** (3) [1022923](https://platzi.com/comentario/1022923/) 

	Les dejo el link al repo de [Circle View Image](https://github.com/hdodenhof/CircleImageView)

* **Valeria Calcina Cisneros** (1) [1057366](https://platzi.com/comentario/1057366/) 

	Me pareció muy interesante el tema de los widgets, aquí les dejare un link donde explican como crear un widget desde la app : <https://developer.android.com/guide/topics/appwidgets?hl=es-419>

* **adriancastilloTI** (1) [1053836](https://platzi.com/comentario/1053836/) 

	Buenas tardes!! en el video menciona que con ConstraintLayout no es posible estirar elementos, pero he visto que si es posible añadiendo 0dp en width y utilizando constraintStart y constraintEnd, y 0dp en height y usando constraintTop y Bottom…
	
	Saludos!!

## 0190. Reutilizando elementos [26270](https://platzi.com/clases/1825-interfaces-android/26270-reutilizando-elementos/)

### Descripción:


### Links:

* [GitHub - sierisimo/Android-Interfaces-PlatziMusic at 09-includes-merge](https://github.com/sierisimo/Android-Interfaces-PlatziMusic/tree/09-includes-merge)

### Comentarios:

* **Luis Arturo Lira Cerda** (2) [1022986](https://platzi.com/comentario/1022986/) 

	Y cómo haríamos para centrar de nuevo el logo?  
	O sea, yo lo centré usando un RelativeLayout, poniendo los constraints y en su contenido puse el include, pero no sé si eso también es un anidamiento innecesario.
	
	¿Cuál sería la manera correcta?  
	Así es como lo puse:
	``` 
	        <RelativeLayout
	            android:id="@+id/logoContainer"
	            android:layout_width="wrap_content"
	            android:layout_height="wrap_content"
	            app:layout_constraintEnd_toEndOf="parent"
	            app:layout_constraintStart_toStartOf="parent"
	            app:layout_constraintTop_toTopOf="parent">
	    
	            <include layout="@layout/merge_logo" />
	        </RelativeLayout>
	    
	```
	
	![Screenshot_6.png](https://static.platzi.com/media/user_upload/Screenshot_6-ea0399b2-4a5a-4ca8-a2e4-8200ccfdcf16.jpg)

* **ricardocelis (Platzi)** (2) [1008165](https://platzi.com/comentario/1008165/) 

	<https://github.com/sierisimo/Android-Interfaces-PlatziMusic/tree/09-includes-merge>

# Cierre [5320]

## 0200. Recapitulación y cierre del curso [26271](https://platzi.com/clases/1825-interfaces-android/26271-recapitulacion-y-cierre-del-curso/)

### Descripción:


### Links:

* [https://twitter.com/sierisimo](https://twitter.com/sierisimo)

### Comentarios:

* **calderón montes de  oca victor eduardo** (3) [1050343](https://platzi.com/comentario/1050343/) 

	Para cuando el curso avanzado de diseño de interfaces Android?

	* **Valeria Calcina Cisneros** [1050343] (1)

		Digo lo mismo 😄

* **Alejandro_R_R** (3) [1019527](https://platzi.com/comentario/1019527/) 

	Muchísimas gracias por todo, me servio de mucho para saber mas de android.

* **ricardocelis (Platzi)** (3) [1008166](https://platzi.com/comentario/1008166/) 

	<https://twitter.com/sierisimo>

* **alonsohernandezsastre** (1) [1054921](https://platzi.com/comentario/1054921/) 

	Conceptos muy claros después de estas clases 😃

