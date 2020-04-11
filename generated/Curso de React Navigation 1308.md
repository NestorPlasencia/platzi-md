# Introducción a React Navigation

## 0010. Bienvenidos el curso de React Navigation

### Descripción:


Bienvenidos al curso de React Navigation. Vamos a ampliar mas nuestros conocimientos haciendo aplicaciones móviles usando JS.

**React Navigation** es una librería que nos ayuda a hacer navegación en nuestras aplicaciones móviles.

Recuerda que en cada clase encontrarás en la sección de archivos el repositorio con el commit correspondiente a la clase. Sin embargo, aquí te dejo los dos repositorios completos.

Repositorio de las clases correspondientes a los conceptos básicos: <https://github.com/LeonidasEsteban/react-navigation-bases/commits/master>

Repositorio de las clases correspondientes al desarrollo del proyecto: <https://github.com/LeonidasEsteban/platzi-video-react-navigation/commits/master>

### Comentarios:

* **Yeraldine Martinez** (22)

	
	¡Ya por aqui! 😄 a reforzar lo que he venido aprendiendo \o/

	* **WilliamVelazquez** (3)

		
		😄 Ya somos dos!

	* **gabino18** (3)

		
		somos 3 😆

	* **Juan David Castro (Platzi)** (3)

		
		somos todos 😄

	* **asx_mx** (2)

		
		Ya somos más

	* **JaySan** (3)

		
		vamos!

	* **Yerson Arce Arbildo** (3)

		
		somos 7

	* **Oscar Barajas Tavares (Platzi)** (3)

		
		somos 8 😃

	* **Ricardo Medina** (2)

		
		Hola! vengo llegando. Otro más!

	* **Ivan Robles** (4)

		
		Ya somos 10!! y tienes 9 pulgares arriba porque faltas tu de ponerte un punto!! 😃  
		Si no faltas tu, entonces alguien no te dio pulgar arriba ò_ó

	* **David Isaac Flores Medrano** (1)

		
		11 😉

	* **darwin1111** (1)

		
		Ahora 12 😄

	* **Santiago Nicolas Maggione** (1)

		
		13 😄

	* **JuanM04** (1)

		
		14 c:

	* **Milton1792** (1)

		
		Somos 15, #JA

	* **leotangram** (1)

		
		16 😄

	* **david-villegas** (1)

		
		17 😛

* **Gerardo Nava Pereda** (4)

	
	😮 ¿Por qué “React Navigation” en lugar de “React Router”? Cuál es mejor y por qué? Son muy similares o muy diferentes? Es cuestion de gustos?

	* **Juan David Castro (Platzi)** (8)

		
		React Router es más recomendado para Web, React Navigation esta más optimizado (con más soporte y opciones en el código) para react-native.

* **Gerardo Nava Pereda** (3)
😮 ¿Por qué “React Navigation” en lugar de “React Router”? Cuál es mejor y por qué? Son muy similares o muy diferentes? Es cuestion de gu...

	* **Juan David Castro (Platzi)** (8)

		
		React Router es más recomendado para Web, React Navigation esta más optimizado (con más soporte y opciones en el código) para react-native.

* **Edgar de Jesus Mendoza Ortegon** (2)

	
	Yo uso este react-native-router-flux y me va muy bien espero aprender algo nuevo en este curso. Gracias LEO !!!

* **Manuel Rivera** (1)

	
	Vamos a ver que tal 🐱‍🏍

* **Gerardo Cetzal Balam** (1)

	
	les comparto mi repositorio, por si tienes dudas como usar las nuevas versiones de react navigation o como implementar ciertas cosas [platzivideo](https://github.com/geceba/platzivideo) noviembre 2019
	
	en android nunca lo probé, pero es cuestión de agregar las configuraciones siguiendo la documentación, me dio pereza y decidí seguir con el curso, igual pienso agregarlo

	* **Gerardo Cetzal Balam** (1)

		
		Hace unas horas actualice para android, ya funciona

* **Izael Ruelas Garcia** (1)

	
	Largo el video pero que bien que podamos ver realmente lo que se tarda react-native en hacer el build y ver los diferentes errores que pueden aparecer para que no crean que trabajar con este entorno es todo bonito con castillos con vista al mar

* **nachoogoomez** (1)

	
	React Navigation acaba de sacar su versión 3 la cual es incompatible con la versión 2 sin adaptar los cambios!

	* **Wilson Marino Pablo Mendez** (1)

		
		Ahora ya con la version 4 😨

* **DMT Technology** (1)

	
	Se viene lo chido xd…

## 0020. Proyecto del curso

### Descripción:


En el curso de React Native hicimos la app PlatziVideo, en este curso vamos a agregar algunas caraterísticas que van a darnos una app super poderosa.

  1. Vamos a agregar navegación en las categorías de las películas.
  2. Drawable Navigation.



### Comentarios:

* **Jesús Angel González Nuñez** (1)

	
	React Native tiene Responsive Design?  
	Si es así, Platzi tiene un curso sobre eso?  
	Mi app no se ve bien en teléfonos pequeños.

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Todo se ajusta igual como se haría en web para hacer responsive, solo que se escribe de manera diferente ya que se hace desde JavaScript <https://facebook.github.io/react-native/docs/style>

	* **George_18** (2)

		
		Hola **angelpiwa** react-native maneja un componente interno llamado **Dimensions** el cual te permite ajustar tu contenido a diferentes dispositivos, por ejemplo ;
		
		Importamos los componentes necesarios.
		``` 
		    import React, { Component } from 'react'
		    import {
		    	View, 
		    	Dimensions, 
		    	StlyleSheet
		     } from 'react-native'
		    
		```
		
		Usamos el componente Dimensions y lo asignamos a las variables de **ancho** y **alto**
		``` 
		    let { height, width } = Dimensions.get('screen')
		    
		```
		
		Y aplicamos estos cambios sobre nuestros estilos
		``` 
		    classIndexScreenextendsComponent{
		    
		        render(){
		            return(
		                <Viewstyle={styles.container}>
		    		<Viewstyle={subContainer}></View>
		                </View>
		            )
		        }
		    }
		    const styles = StyleSheet.create({
		        container:{
		            flex:1,
		            backgroundColor:'#0D5F99',
		            alignItems: 'flex-start',
		            justifyContent:'flex-start',
		       	 },
		    			subContainer:{
		    				height:height,
		    				width:width,
		    				backgroundColor:'deeppink'
		    		 }
		    })
		    exportdefault IndexScreen
		    
		```
		
		de esta forma puedes garantizar que el objeto que vas a renderizar sea una image, view, text se ajuste a las pantallas de los dispositivos.

* **Daniee** (1)

	
	Hola Leo, qué programa utilizas para enviar la pantalla del teléfono enchufado por el cable ? Me dejarías un pequeño tutorial de cómo hacerlo ? Gracias ! 😊

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Esto funciona para mac y es conectas el teléfono usando el cable, luego abres QuickTime y en el menu file o archivo le dices new recording o nueva grabación, luego te va a salir un menu donde seleccionas que queires grabar y sale el iphone que tienes conectado.

	* **Daniee** (1)

		
		y si fuera un teléfono Android (mi caso) ? Mil gracias Diego !

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		No se si con android sea posible.

	* **Daniee** (2)

		
		ohh bueno gracias de todas formas 😉

	* **victorAguilera** (1)

		
		Es uno de los últimos videos del curso de React Native

	* **Miguel Angel Monje Allende** (3)

		
		si es posible:  
		1.- tener conectado tu móvil  
		2.- en el cmd dirigirte a la carpeta de tu proyecto  
		3.-ejecuta el siguiente comando: react-native run-android  
		y eso es todo
		
		en mi caso me da error asi que lo que hago es siempre ejecutar antes el siguiente comando:  
		(con tu móvil conectado)  
		adb reverse tcp:8081 tcp:8081
		
		si no tienes el adb instalado de forma global  
		te dará error así que lo que tendrás que hacer es dirigirte manualmente a el, la ruta es:
		
		C:\Users\tuUsuario\AppData\Local\Android\Sdk\platform-tools
		
		y ahi ejecutas el comando
		
		espero que te sirva 😃

	* **DMT Technology** (4)

		
		Yo uso Vysor, te dejo el link.  
		<https://www.vysor.io/>

	* **Daniee** (1)

		
		@dtowong muchas gracias !

	* **Yubeli Martinez Sanchez** (1)

		
		Igual mente.

* **Ivan Robles** (1)

	
	Nice!! 😃

* **WilliamVelazquez** (1)

	
	En la navegación del lado izquierdo ¿Es normal que desaparezcan las tabs de abajo al realizar el desplazamiento a alguna de ellas?

	* **Leonidas Esteban Gonzalez** (2)

		
		Si, en la demo usé las mismas pantallas para el Drawer. Es decir que aunque tengan el mismo contenido para mi Drawer son totalmente diferentes, pero esto es totalmente intencional, ya lo verás en el curso.

	* **Izael Ruelas Garcia** (2)

		
		Que bien que se verá esa parte porque hay ocasiones que necesitas Vistas que tengan tabs y otras vistas que no tengan, incluso intercambiar la información que aparece en las tabs

	* **WilliamVelazquez** (1)

		
		Justo como dices Izael, en muchas ocasiones necesitamos otro tipos de vista con información distinta! 😃

* **Jesús Angel González Nuñez** (1)
React Native tiene Responsive Design? Si es así, Platzi tiene un curso sobre eso? Mi app no se ve bien en teléfonos pequeños.

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Todo se ajusta igual como se haría en web para hacer responsive, solo que se escribe de manera diferente ya que se hace desde JavaScript <https://facebook.github.io/react-native/docs/style>

* **WilliamVelazquez** (0)
En la navegación del lado izquierdo ¿Es normal que desaparezcan las tabs de abajo al realizar el desplazamiento a alguna de ellas?

	* **Leonidas Esteban Gonzalez** (2)

		
		Si, en la demo usé las mismas pantallas para el Drawer. Es decir que aunque tengan el mismo contenido para mi Drawer son totalmente diferentes, pero esto es totalmente intencional, ya lo verás en el curso.

## 0030. Hola mundo con react-navigation

### Descripción:


Vamos a crear una aplicación muy sencilla en la que vamos a aprender a usar react-navigation de la manera mas sencilla posible.

Luego estaremos trabajando con nuestra app PlatziVideo.

Para crear la aplicación, úbicate en la carpeta donde vas a tener los proyectos del curso.

`react-native init reactNavigationBasic`

### Links:

* [React Navigation (v2) · Routing and navigation for your React Native apps](https://reactnavigation.org/)

### Comentarios:

* **Christian Omar López Macías** (13)

	
	Para limpiar la cache escribir el siguiente comando “npm start --reset-cache”

	* **Juan Roa** (7)

		
		o con la CLI de react native: `react-native start --reset-cache`

	* **Christian Omar López Macías** (0)

		
		Buen aporte @roadev

	* **Melina Jacqueline onoriaga** (1)

		
		Muchas gracias!! siempre tengo problemas con el cache!!

* **Edgar de Jesus Mendoza Ortegon** (12)

	
	Revisen la nueva documentación hay que agregar 2 cosas para que funcione
	
	npm install --save react-native-gesture-handler  
	react-native link
	
	import { createStackNavigator, createAppContainer } from “react-navigation”;
	
	const AppNavigator = createStackNavigator({  
	Home: {  
	screen: HomeScreen  
	}  
	});
	
	export default createAppContainer(AppNavigator);

	* **Danvasem** (3)

		
		me salvaste el día!! excelente aporte.

	* **DTI** (3)

		
		Que tal buen día, instale  
		npm install --save react-native-gesture-handler  
		react-native link  
		pero sigo teniendo el mismo error alguna otra sugerencia?

	* **Nearshore Code** (2)

		
		Prueba esto
		``` 
		    $ npm install--save react-navigation
		    $ npm install--save react-native-gesture-handler
		    $ react-nativelink react-native-gesture-handler
		    $ react-native run-android
		    
		```

	* **Jose Balcazar** (1)

		
		adicional para android hay que modificar el archivo MainActivity.java talcual indica en la documentacion para que se pueda ver igual al ios  
		<https://reactnavigation.org/docs/en/getting-started.html>

* **Wilson Marino Pablo Mendez** (10)

	
	Este curso require una update ‼

	* **esdraspavon** (1)

		
		rt

	* **Jesus Camacaro** (1)

		
		rt

* **Lisandro Gómez Ortiz** (10)

	
	 _ _En caso que se quiera utilizar la version 4._ de React Navigation …_*
	
	* * *
	
	Ahora createStackNavigator pertenece a react-navigation-stack, por lo que se debe instalar primero react-native-gesture-handler y react-navigation-stack
	``` 
	    yarn add react-native-gesture-handler
	    #  o con npm 
	    # npm install --save react-native-gesture-handler
	    
	    yarn add react-navigation-stack
	    # o con npm
	    # npm install --save react-navigation-stack
	    
	```
	
	En vez de importar createStackNavigator de react-navigation se debe hacer desde react-navigation-stack Y de react-navigation se debe importar el createAppContainer
	``` 
	    import {createStackNavigator} from'react-navigation-stack';
	    import {createAppContainer} from'react-navigation';
	    
	```
	
	Luego, en vez de exportar por defecto AppNavigator se crea una constante AppContainer la cual se crea con createAppContainer recibiendo AppNavigator como parámetro y se hace el export de esta:
	``` 
	    const AppContainer = createAppContainer(AppNavigator)
	    
	    exportdefault AppContainer
	    
	```
	
	Asi se crea el Hola Mundo React Navigation, se debería actualizar este curso ya que cuando se hizo estaba en la versión 2, pero mientras tanto para los que queremos continuar con el curso espero que les sea de utilidad y no se frustren 😉

	* **Daniel Fernando Murcia Perdomo** (1)

		
		muchisimas gracias

* **Ivan  Alvarez Malo L** (7)

	
	Lamentablemente (o afortunadamente, como quieran verlo) justo alrededor fechas en que se lanzo este curso, a los creadores de “React Navigation” se les ocurrió lanzar un nuevo release de la dependencia (3.X) y obviamente conlleva grandes cambios, por lo que algunos de los conocimientos de este curso no aplican para esta nueva versión. Para instalar la versión de “React Navigation” usada en este curso, no uses este comando, ya que te instalará la versión más reciente:
	``` 
	    npm install react-navigation --save
	    
	```
	
	Usa este de acá:
	``` 
	    npm i --save react-navigation@2.3.1
	    
	```
	
	No recomiendo continuar el curso usando la nueva versión e ir arreglando los pequeños o grandes detalles que vayan saliendo a lo largo de las clases, solo te frustrarás y no aprenderás ni una u otra versión. Además, la versión anterior (2.X) es bastante útil, yo en lo personal la sigo usando para mis proyectos de React Native y no me ha dado problemas, así que lo que aprendas aquí igual te va a ser de mucha utilidad.

	* **pedro-daniel-rojas-corona** (1)

		
		Gracias por tu aporte, me fue de mucha ayuda!!

	* **Jonattan_Infante** (1)

		
		Gracias, Intente user la nueva versión pero la verdad todo fue caos.

	* **xpertgroup** (1)

		
		Muchas Gracias

* **Omar Guerrero** (4)

	
	Si les sale este error: ‘Invariant Violation: The navigation prop is missing for this navigator’ usando la versión 3 de react-navigation, es debido a que react-navigation requiere un contenedor para manejar el estado de la navegación. En las versiones anteriores este contenedor se aplicaba automaticamente cuando usabas ‘createStackNavigator’ pero en la versión 3 es necesario hacerlo nosotros mismos usando ‘createNavigationContainer’.
	``` 
	    import {
	      createStackNavigator,
	      createNavigationContainer
	    } from "react-navigation";
	    
	    const AppNavigator = createStackNavigator({
	      Home: App
	    });
	    
	    exportdefault createNavigationContainer(AppNavigator);
	    
	```

* **Yerson Arce Arbildo** (4)

	
	Eso de estar bajando las versiones para que funcione, NO me gustar para nada, espero que esto cambie pronto

	* **SAVelasco** (1)

		
		Es imposible que un curso salga con las dependencias actuales, ya que en el tiempo en que se graba y edita van saliendo mas y mas versiones de las distintas dependencias que existen, mucho del trabajo de los programadores es adaptar los sistemas a estas nuevas versiones

* **Francisco Maneiro** (3)

	
	A partir de la version 3.0 se incluye el `createAppContainer` quedando la app de esta manera
	``` 
	    import {  createStackNavigator, createAppContainer } from 'react-navigation'
	    
	    {...}
	    
	    constAppNavigator = createStackNavigator({
	      Home: App
	    })
	    
	    constApp = createAppContainer(AppNavigator);
	    
	    export default App;
	    
	    
	```

* **Carlos Alberto Petit Quintero** (3)

	
	Por que no usar Yarn en lugar de npm ?

* **freddy0fh** (3)

	
	Con la versión 3.0.9 se me presento el sigueinte error:
	``` 
	    The navigation prop is missing forthis navigator. In react-navigation 3 you
	    
	```
	
	Solución:
	``` 
	    /**
	     * Sample React Native App
	     * https://github.com/facebook/react-native
	     *
	     * @format
	     * @flow
	     */
	    
	    import React, { Component } from'react';
	    import { Platform, StyleSheet, Text, View } from'react-native';
	    import { createStackNavigator, createAppContainer } from"react-navigation";
	    
	    const instructions = Platform.select({
	      ios: 'Press Cmd+R to reload,\n' + 'Cmd+D or shake for dev menu',
	      android:
	        'Double tap R on your keyboard to reload,\n' +
	        'Shake or press menu button for dev menu',
	    });
	    
	    type Props = {};
	    classAppextendsComponent<Props> {
	      render() {
	        return (
	          <Viewstyle={styles.container}>
	            <Textstyle={styles.welcome}>Welcome to React Native!</Text>
	            <Textstyle={styles.instructions}>To get started, edit App.js</Text>
	            <Textstyle={styles.instructions}>{instructions}</Text>
	          </View>
	        );
	      }
	    }
	    
	    const styles = StyleSheet.create({
	      container: {
	        flex: 1,
	        justifyContent: 'center',
	        alignItems: 'center',
	        backgroundColor: '#F5FCFF',
	      },
	      welcome: {
	        fontSize: 20,
	        textAlign: 'center',
	        margin: 10,
	      },
	      instructions: {
	        textAlign: 'center',
	        color: '#333333',
	        marginBottom: 5,
	      },
	    });
	    const AppNavigator = createStackNavigator({
	      Home: App
	    });
	    const AppContainer = createAppContainer(AppNavigator);
	    exportdefault AppContainer;
	    
	```

* **Ruben Garcia** (2)

	
	React- Navigation 5
	``` 
	    import React, { Component } from'react';
	    import { StyleSheet, Button, View, Text } from'react-native';
	    import { NavigationContainer } from'@react-navigation/native';
	    import { createStackNavigator } from'@react-navigation/stack';
	    
	    classHomeextendsComponent {
	        render() {
	            return (
	                <View style={styles.container}>
	                  <Text>Open up App.js to start working on your app!</Text>
	                  <Button
	                    title="Go to Details"
	                    onPress={() => navigation.navigate('Details')}
	                  />
	                </View>
	            );
	        }
	    }
	    
	    const styles = StyleSheet.create({
	        container: {
	            flex: 1,
	            backgroundColor: '#fff',
	            alignItems: 'center',
	            justifyContent: 'center',
	        },
	    });
	    
	    const Stack = createStackNavigator();
	    
	    function App() {
	      return (
	        <NavigationContainer>
	          <Stack.Navigator>
	            <Stack.Screen
	              name="Home"
	              component={Home}
	            />
	          </Stack.Navigator>
	        </NavigationContainer>
	      );
	    }
	    
	    exportdefault App;```
	    
	```

* **victormanuelmurillocamayo** (2)

	
	Yo me frustré hasta que decidi seguir los comentarios y usar  
	npm i --save react-navigation@2.3.1 y todo salio bien!!!

* **Pedro Perafán Carrasco** (2)

	
	Si estan usando react navigation v3 puede salir este error.
	
	`undefined is not an object (evaluating 'RNGestureHandlerModule.State')`
	
	Deben de instalar react-native-gesture-handler.
	``` 
	    npm install--save react-native-gesture-handler
	    react-nativelink react-native-gesture-handler
	    
	```
	
	y en el código
	``` 
	    import {
	      createStackNavigator,
	      createAppContainer
	    } from 'react-navigation'
	    
	    const AppNavigator = createStackNavigator({
	      Home: App
	    })
	    
	    exportdefault createAppContainer(AppNavigator)
	    
	```

* **Yeraldine Martinez** (2)

	
	Jajajajajaaj hay días que me toca hacer run-android como 5 veces antes de que la aplicación arranque (/.) Si, ¡es el día a día!

	* **WilliamVelazquez** (0)

		
		Suele pasar! jeje

	* **Juan Roa** (2)

		
		Basta con correr la app en el emulador / device y correr solo el server de desarrollo de node con `react-native start`

* **Alexander Miguel Ferreras Concepción** (2)
Leonidas, puedo usar expo para este este curso?

	* **jenapi** (1)

		
		Si si puedes, yo lo hice con expo, de hecho expo fue el desarrollador de react navigation.  
		Solo recuerda que para instalar las librerías debes hacer
		``` 
		    expo install <NombreDeLaLibrería>
		    
		```

* **Manuel Rivera** (1)

	
	Actualmente estamos en la Versión 5 😕

* **Alirio Alejandro Angel Arenas** (1)

	
	cabe acotar que con Yarn muchos problemas de NPM no suceden

* **Jordi Santamaría Portolés** (1)

	
	Cuando vas a ver el curso de platzi xk te da pereza hacer el tutorial de la web oficial… no funciona lo k se dice en platzi y tienes que volver igualmente a hacer el tuto de la web oficial para conseguir arrancar kappa.

* **Jordi Santamaría Portolés** (1)

	
	lul, npm 13 segundos, yarn 3 segundos

* **luisferbedon** (1)

	
	en la nueva version al exportar hay que generar un container  
	createAppContainer(AppNavigator);

* **leotangram** (1)

	
	Lo mejor que ha servido para mi cuando la app se totea es escribir en la terminal lo siguiente:  
	“killall node”

* **Manuel Calle Pérez** (1)

	
	No logre hacer que me funcione, siempre que corro el programa me sale error 500, esto ocurre cuando coloco el **import { createStackNavigator } from ‘react-navigation’;**![](https://photos.app.goo.gl/5LHyebyy8WQb8uBr7)

	* **Miguel Cobas** (1)

		
		intenta primero instalar react-native-gesture-handler, luego react-native link, segundo hay que importar tambien createAppContainer de react-navigation y al final exportarlo export default createAppContainer(AppNavigator);

* **Jesús Pernía** (1)

	
	En mi caso tuve problemas al empezar un nuevo proyecto con react-native… Luego de intentar las soluciones que propone el mismo cli y las descritas aquí el problema persistió.
	
	El error era:
	``` 
	    Error: Cannot findmodule '@babel/runtime/helpers/builtin/interopRequireDefault'
	    
	```
	
	Este problema al parecer surge porque babel cambió la estructura de sus carpetas. Para solucionar agregué lo siguiente a mis dependencias del **package.json** , y luego hice un **npm install** :
	``` 
	    "@babel/runtime": "7.0.0-beta.55"
	    
	```
	
	Más información al respecto en [este issue de github](https://github.com/meteor/meteor/issues/10128).

* **Hummingbird It** (1)

	
	Hasta ahora lo veo muy interesante 😄

* **Ivan Robles** (1)

	
	 **StackNavigator** es la forma mas elemental para crear navegación con **react-navigation**.
	
	El método **createStackNavigator()** recibe **rutas** y una **configuración** (que es opcional):
	``` 
	    const AppNavigator = createStackNavigator({
	      Home: App
	    });
	    
	```
	
	En este caso solo le pasamos la ruta de **Home** , a la cual le asignamos el componente **App**.

* **raulaallendep** (1)

	
	Para cerrar el emulador le das click y luego presionas command+w o vas a File/Close Window

* **Javier Rocha** (1)

	
	Leonidas el mejor profe

* **jesusmurf** (1)

	
	Si queremos usar un header personalizado sin tener que usar el que nos provee React Navigation?

	* **Joshua Camilo Medina** (2)

		
		Puedes crear tu propio header, Leonidas explica como realizarlo en el curso de react native y en este curso te muestra como cambiarlo en el navigationOptions de tu app-navigator.js, te dejo un ejemplo:
		``` 
		    import Header from '../custom-header'
		    const Init = createStackNavigator(
		     {
		        Home: {
		          screen: Welcome,
		        },
		        {
		          navigationOptions: {
		            header: Header,
		        }
		    }
		    
		```

	* **José Antonio Torres** (2)

		
		Adicionalmente, puedes usar un haeder en todo el stack o solo poner header a una pantalla del stack.
		``` 
		    const stack = createStackNavigator({
		    	screen1: Welcome,
		    	navigationOptions: {
		    		header: null
		    	}
		    })
		    
		```

* **Jose R. Torrens Acosta** (1)

	
	Me ocurrió lo mismo. vengo del curso de React native y sin descanso seguí con este, luego de crear la app y darle “react-native run-android” me decía esto “react native application has not been registered”. Y luego de tanto probar tuve que reiniciar la PC y todo bien. Si alguien paso por lo mismo y resolvió de otra forma. Bienvenido sea su comentario.
	
	BTW: Estoy usando Ubuntu

* **nachoogoomez** (1)

	
	Puedes cerrar uno de los simuladores con command+w. Con command+q como ya sabrás cierras todos.

* **Daniel Pereira** (1)

	
	para cerrar el emulador solo selecciona el que quieres cerrar y presiona Command+W o en la barra superior quita la opción de window / show Device bezels para quitar la interfaz del iPhone y se vea solo la pantalla y los botones de minimizar y cerrar

* **Juan Roa** (1)

	
	Usa `yarn` mejor 😄

	* **Oscar Barajas Tavares (Platzi)** (2)

		
		Cuales son las ventajas de yarn sobre npm?

	* **Juan Roa** (2)

		
		Yarn llega a ser hasta 10 veces más rápido instalando dependencias a comparación de npm. Ahorras una cantidad de tiempo considerable cuando trabajas con cualquier proyecto front / node.

* **Christian Omar López Macías** (1)

	
	Cada proyecto nuevo que comienzo tengo que compilarlo primero en el Android Studio para que hace se actualice 😕

* **jesusmurf** (1)
Si queremos usar un header personalizado sin tener que usar el que nos provee React Navigation?

	* **Joshua Camilo Medina** (2)

		
		Puedes crear tu propio header, Leonidas explica como realizarlo en el curso de react native y en este curso te muestra como cambiarlo en el navigationOptions de tu app-navigator.js, te dejo un ejemplo:
		``` 
		    import Header from '../custom-header'
		    const Init = createStackNavigator(
		     {
		        Home: {
		          screen: Welcome,
		        },
		        {
		          navigationOptions: {
		            header: Header,
		        }
		    }
		    
		```

* **Carlos Enrique Gonzalez Peña** (0)

	
	Yo tuve un monton de problemas.  
	Me salia principalmente un error donde no encontraba un Modulo llamado AccessibilityInfo.
	``` 
	    error: bundling failed: Error: Unable to resolve module`AccessibilityInfo`
	    
	```
	
	Lo que tuve que hacer es crear un nuevo proyecto pero con una versión menor de react-native en este caso la 0.55.4.  
	Si tiene este problema y por mas que borren cache y borren los modules de node `node_modules`  
	Borren todo y creen un nuevo proyecto de la siguiente forma `react-native init --version="0.55.4" MyNewApp`  
	Por ultimo no olviden eliminar la app de su navegador por si le pusieron el mismo nombre

* **Juan Roa** (0)

	
	Cuando aún no les funcione borrando el caché, deben de ejecutar este comando de watchman: `watchman watch-del-all`

## 0040. Creando múltiples pantallas

### Descripción:


Estamos yendo paso a paso en la creación de la aplicación en la que estaremos aprendiendo los conceptos básicos de React Navigation.

Vamos a implementar 4 pantallas en esta clase:

  1. Pantalla de home.
  2. Pantalla de blog.
  3. Pantalla de about.
  4. Pantalla para el perfil.



### Comentarios:

* **leotangram** (11)

	
	Para que ahora funcione React Nativation 3, se debe importar aparte de createStackNavigator, createAppContainer
	
	Y debe quedar el código algo así:
	``` 
	    /**
	     * Sample React Native App
	     * https://github.com/facebook/react-native
	     *
	     * @format
	     * @flow
	     */
	    
	    import React, { Component } from'react';
	    import { Platform, StyleSheet, Text, View } from'react-native';
	    import { createStackNavigator, createAppContainer } from'react-navigation'
	    import Home from'./src/screens/home'
	    
	    const instructions = Platform.select({
	      ios: 'Press Cmd+R to reload,\n' + 'Cmd+D or shake for dev menu',
	      android:
	        'Double tap R on your keyboard to reload,\n' +
	        'Shake or press menu button for dev menu',
	    });
	    
	    type Props = {};
	    classAppextendsComponent<Props> {
	      render() {
	        return (
	          <Viewstyle={styles.container}>
	            <Textstyle={styles.welcome}>Welcome to React Native!</Text>
	            <Textstyle={styles.instructions}>To get started, edit App.js</Text>
	            <Textstyle={styles.instructions}>{instructions}</Text>
	          </View>
	        );
	      }
	    }
	    
	    const styles = StyleSheet.create({
	      container: {
	        flex: 1,
	        justifyContent: 'center',
	        alignItems: 'center',
	        backgroundColor: '#F5FCFF',
	      },
	      welcome: {
	        fontSize: 20,
	        textAlign: 'center',
	        margin: 10,
	      },
	      instructions: {
	        textAlign: 'center',
	        color: '#333333',
	        marginBottom: 5,
	      },
	    });
	    
	    const MainNavigator = createStackNavigator({
	      Home: App
	    })
	    
	    const AppNavigator = createAppContainer(MainNavigator)
	    
	    exportdefault AppNavigator
	    
	```

	* **José Miguel Soltero** (2)

		
		Muchas gracias.

	* **Mario Gonzalezrubio** (1)

		
		Gracias, estuve atascado con este tema del declarar el container

* **Wilson Marino Pablo Mendez** (4)

	
	React Navegation v.4 con Expo
	``` 
	    import React from 'react';
	    import { View, Text } from 'react-native';
	    import { createAppContainer } from 'react-navigation';
	    import { createStackNavigator } from 'react-navigation-stack';
	    import Home from './src/screens/Home';
	    import Login from './src/screens/Login';
	    import Register from './src/screens/Register';
	    import Perfil from './src/screens/Perfil';
	    import Blog from './src/screens/Blog';
	    
	    
	    const AppNavigator = createStackNavigator({
	      Home: {
	        screen: Home,
	      },
	      Login: {
	        screen: Login,
	      },
	      Perfil: {
	        screen: Perfil,
	      },
	      Blog: {
	        screen: Blog,
	      },
	      Register: {
	        screen: Register,
	      }
	    });
	    
	    exportdefault createAppContainer(AppNavigator);
	    
	```

* **leotangram** (3)

	
	Para que Button funcione:
	
	yarn add react-native-gesture-handler  
	<h1>or with npm</h1> <h1>npm install --save react-native-gesture-handler</h1>  
	react-native link  
	Mas info: <https://reactnavigation.org/docs/en/getting-started.html>

* **José Tuzinkievicz** (2)

	
	Alguien sabe qué extensión se usa en VSCode para autocompletar el código como lo hace Leonidas? Gracias.

* **Jorge Daniel Pat Navarro** (2)

	
	Ahora el createStackNavigation viene aparte, lo instalas con
	``` 
	    npm install react-navigation-stack
	    
	```

* **Marvin Baptista** (1)

	
	Realizando estos pasos en terminal, logre hacer la instalación de todo para EXPO, puede que sobre algo, pero seguro no falta nada…
	``` 
	    expo init reactNavigationBasic2 
	    cd reactNavigationBasic2  
	    npm install--save react-navigation 
	    npm install--save react-native-gesture-handler 
	    npm install--save react-navigation-stack 
	    expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view 
	    npm install 
	    yarn start 
	    
	```

* **jcardozo** (1)

	
	valdria la pena una actualizacion de esta parte

* **Karl Heitmann** (1)

	
	Aqui renderiza el Home dentro de un createStackNavigator

* **Karl Heitmann** (1)

	
	En esta clase crea la estructura del proyecto, que circula por las páginas home, login, profile, about, home, etc.

* **Victor Parra** (1)

	
	Atentos a la versión de React Native que estéis usando, en la versión **0.57.3** el componente _Button_ no funcionará correctamente, podéis usar la misma versión de nuestro amigo Leonidas o crear otro tipo de botón, por ejemplo:
	``` 
	    <TouchableOpacity>
	    	<Text>Ir a Login</Text>
	    </TouchableOpacity>```
	    
	```

	* **Damian Perez** (2)

		
		Gracias por el tip.

* **cafeagenceweb** (1)
Hola, tengo dudas en como crear el typeProps , podrian alguien ayudarme , sin esto no me funciona

## 0050. Navegando entre pantallas

### Descripción:


En esta clase vamos a aprender a usar un botón para navegar entre pantallas. Luego veremos la configuración y personalización de los stacks y la navegación en el framework.

### Comentarios:

* **Ivan Robles** (3)

	
	El método **navigate()** de navigation nos lleva a otra pantalla dada la ruta que le especificamos.
	``` 
	    handlePress = () => {
	        this.props.navigation.navigate('Home');
	      }
	    
	```
	
	La prop **navigation** se manda a cada ruta/componente/pantalla que definimos en el **StackNavigator**.

* **Karl Heitmann** (2)

	
	Gracias a que hemos utilizado createStackNavigator, el Home hereda una propiedad que es navigation, a la que se puede acceder desde el botón

	* **Yusnier Matos Arias** (1)

		
		Me salvaste la vida hermano. Estoy trabajando con la versión actual de React Navigation y tratando de alinearme con este curso. Ese comentario tuyo me salvó.  
		Gracias.

* **Carlos Alberto Petit Quintero** (2)

	
	yisussss, hace tiempo intente utlizar React Navigation, y no sabia que se podian ver las propiedades del stack haciendo un console.log.!!!

	* **José Antonio Torres** (2)

		
		hahaha suele pasar. La clave esta en que always console.log everything

* **juand_silva** (2)

	
	Si están emulando en un dispositivo físico y presionan el ‘GO BACK’ en Android y notan que no les funciona o se tarda una eternidad en regresar a la pantalla previa, Apaguen el modo “DEBUG”

	* **José Tuzinkievicz** (1)

		
		Gracias por el comentario salvador 😄

* **Felipe Ruiz** (2)

	
	Que lindo es react-navigation 😍

* **Karl Heitmann** (1)

	
	muestra como se navega llamando al metodo adecuado de props.navigation.

* **Karl Heitmann** (1)

	
	muestra la props navigation en consola del navegador.

* **Edgar de Jesus Mendoza Ortegon** (1)

	
	Creando un stack en la nueva version
	``` 
	    import React, { Component } from "react";
	    import { createStackNavigator, createAppContainer } from "react-navigation";
	    
	    import Login from "./containers/Login/Login";
	    import Home from "./containers/Home/Home";
	    
	    const AppNavigator = createStackNavigator({
	      Login: { screen: Login },
	      Home: { screen: Home }
	    });
	    
	    const AppContainer = createAppContainer(AppNavigator);
	    
	    exportdefault AppContainer;
	    
	    
	    
	    
	```
	
	import React, { Component } from “react”;  
	import Router from “./src/Router”;
	
	class App extends Component<Props> {  
	render() {  
	return <Router />;  
	}  
	}
	
	export default App;```
	```
	```
	

* **juand_silva** (1)

	
	Documentación del prop navigation:  
	<https://reactnavigation.org/docs/en/navigation-prop.html>  
	Tiene demasiadas funcionalidades.

* **sebastian-cipolat** (1)

	
	En mi caso en Android la navegacion no me funcionaba,  
	descubri que el problema estaba cuando se definia AppNavigator
	
	`const AppNavigator=createStackNavigator({ Home, Login, Profile, About, })`
	
	Lo cambie a:
	
	`const AppNavigator=createStackNavigator({ Home:Home, Login:Login, Profile:Profile, About:About, })`
	
	y funciona sin problemas, no se por que pero anduvo.  
	Comparto por si alguno le paso tmb

	* **Carlos Enrique Gonzalez Peña** (1)

		
		Gracias por compartir

	* **Carlos Enrique Gonzalez Peña** (2)

		
		sebastian  
		Que versión de Node tienes instalada?  
		Te comento que esto de que Home = Home: Home es una opción de ES6 o ES2015 llamado Destructure  
		Este en este caso nos ayuda al momento de asignar un valor a una key de un objeto.  
		Si nosotros nombramos de la misma forma el valor que la llave y no le pasamos ningún valor a la llave, JS asume que ese es el valor. ejemplo:
		``` 
		    const name = 'Carlos'
		    
		    const JSObject = {
		    	name
		    }
		    console,log(JSObject.name)
		    //output Carlos
		    
		```

# React Navigation API

## 0060. Configurando un Stack Navigator

### Descripción:


Importamos desde React Navigation el Stack navigator y logramos implementar navegación entre pantallas.

Vamos a conocer el API completo para conocer todas las funciones que nos ofrece.

### Comentarios:

* **Danvasem** (12)

	
	Si no les aparece el titulo por defecto, que se configura en el segundo parámetro de “createAppContainer” deben cambiar “navigationOptions” por “defaultNavigationOptions”.

	* **Jesús Angel González Nuñez** (1)

		
		Gracias. Muchas Gracias.

* **Ivan Robles** (9)

	
	Un **StackNavigator** es como un “array”, donde podemos añadir y quitar elementos (Push y Pop) entre otras cosas.
	
	El método **createStackNavigator()** recibe:
	
	  * **Configuración de Ruta** : Lista de las rutas, cada ruta puede en un objeto con configuraciones especificas.
	  * **Configuración del StackNavigator** : Configuración global donde podemos definir como va a funcionar nuestra navegación (cards, modals, configuraciones visuales).
	
	
	
	Párametros para la configuración de **Ruta** :
	
	  * **screen** : Componente.
	  * **path** : Deep Linking.
	  * **navigationOptions** : Personalización particular de la pantalla (Titulo en el navigator).
	
	
	
	Parámetros para la configuración del **StackNavigator** :
	
	  * **initialRouteName** : Desde que ruta queremos arrancar.
	  * **initialRouteParams** : Parametros a la pantalla inicial de la aplicación.
	  * **initialRouteKey** : Navegación por keys.
	  * **navigationOptions** : Similar a los parámetros de navegación de rutas, pero en este caso son globales.
	  * **paths** : configuraciones para Deep Linking.
	
	

* **ma_angelica_romero** (3)

	
	En la versión de react-navigation@2.18.2 el titulo el titulo se pon de esta forma
	``` 
	        navigationOptions: ({ navigation }) => ({
	          title: 'Esta es la home',
	        }),
	    
	    
	```

* **jesusmurf** (3)

	
	Si no existe initialRouteName en el routerConfig la ruta inicial será la primera ruta del objeto de rutas.

* **Karl Heitmann** (1)

	
	tiene practicamente listo la configuración de ejemplo de ruta y de parametros de StackNavigator.

* **Karl Heitmann** (1)

	
	detalla stackNavigatorConfig

* **Karl Heitmann** (1)

	
	detalla argumento RouteConfig

* **Karl Heitmann** (1)

	
	habla de los argumentos de createStackNavigator: routeConfig,stackNavigatorConfig

* **Fernando Bayley** (1)

	
	Hola a todos, les consulto a ver si me pueden ayudar, no tengo forma que me aparezca el titulo en las vistas, veo más abajo en comentarios de otros compañeros que indican algún tipo de solución pero la verdad no logro hacer la configuración desde el archivo App.js, si me pueden ayudar se los agradecería, saludos y muchas gracias a todos!!!

	* **Miguel Cobas** (5)

		
		en la parte general se cambio la propiedad para poner el titulo para todas, en lugar de navigationOptions cambialo por defaultNavigationOptions pero solo de manera general, cuando es individual queda igual

	* **romeomunoz** (1)

		
		Buen aporte:  
		defaultNavigationOptions: {  
		title: ‘titulo generico’,  
		},

* **Enzo Aliatis** (1)

	
	Es posible que no pueda correr la app sin wifi?
	
	lo que pasa es que en casa la app corre excelente pero al intentar abrirla sin wifi o en otro lado no abre, es alguna restricción ?

	* **Leonidas Esteban Gonzalez** (3)

		
		Cuando corres la App fuera de casa estás usando el modo de producción? De otra manera el problema es que nunca va a conectar con el server de desarrollo

	* **Enzo Aliatis** (0)

		
		Veremos como hacer esto en el curso?

	* **Enzo Aliatis** (3)

		
		Era exactamente eso gracias por la respuesta  
		![Captura de pantalla 2018-06-29 a la\(s\) 11.07.19.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-06-29%20a%20la%28s%29%2011.07.19-621b7da1-040a-446b-bd1a-6024308b4f1c.jpg)

	* **WilliamVelazquez** (1)

		
		Para la generación de la app en modo de producción se ve más a detalle en el curso de React Native 😃 Si no lo has tomado, te recomiendo primero lo curses y continues con este debido a que se continuará con el proyecto que se desarrolló en ese curso. Saludos! 😃

## 0070. Navigation Options

### Descripción:


Veamos algunas opciones mas avanzadas de configuración que nos ofrece React Navigation.

### Comentarios:

* **Christian Omar López Macías** (32)

	
	Stack Navigator Config - Navigation Options  
	* title: Titulo en la parte de encima  
	* header: Componente personalizado  
	* headerTitle: Similar a title  
	* headerAllowFontScaling: El font size se escala dependiendo el dispositivo  
	* headerBackImage: La imagen para el botón de regresar, por default está una flecha  
	* headerBackTitle: Texto que acompaña al botón de regresar  
	* headerTruncateBackTitle: Un texto más corto en dado caso que el headerTitle no alcance el espacio  
	* headerRight: Componente personalizado orientado a la derecha  
	* headerLeft: Componente personalizado orientado a la izquierda  
	* headerStyle: Estilos para el header  
	* headerForceInset: Mover el header para arriba, abajo, izquierda  
	* headerTitleStyle: Estilos al titulo  
	* headerTintColor: Color del background del header  
	* headerPressColorAndroid: Color del background del header al presionarlo  
	* headerTransparent: Por si se necesita que el header sea transparente  
	* headerBackground: Por si se necesita una imagen de fondo en el header  
	* gesturesEnableb: Por si quieres que los gestos esten activados (por default iOS los tiene Android no)  
	* gesturesResponseDistance: Para la sensibilidad al momento de arrastrar a otra pantalla  
	* gesturesDirection: Por si se necesita invertir el cambio de dirección al cambiar de pantalla

	* **jhurtadojerves** (3)

		
		Héroe sin capa 😄

	* **Carlos Enrique Gonzalez Peña** (2)

		
		Esta mal escrito el headerLeft.  
		Según Leo se escribe heraderLeft 😂  
		Perdon Leo, es juego 😀

	* **Ivan Robles** (3)

		
		Buen apunte, de mucha utilidad, sin embargo no olvides que en el editor de Platzi pudiste darle formato a la lista de esta manera:
		
		  * title
		  * header
		  * headerTitle
		
		
		
		Y así queda mas legible 😉

* **Jose R. Torrens Acosta** (8)

	
	Algo que se olvido decir es que **headerBackTitle** solo esta soportado para iOS

* **nixon-gamboa** (6)

	
	El **headerBackTitle** : _Texto que acompaña al botón de regresar_ Solo funciona en iOS, me rompi 1 hora intentndo hacer que funcione en android hasta que descubri que solo funciona en iOS

	* **Kingsman7** (4)

		
		gracias. ya iba por el mismo camino

	* **Jemd** (1)

		
		Ufff Ya casi eramos 3 menos mal y tengo la costumbre de bajar a los comentarios xd

* **Sebastian Wilde Alarcón Arenas** (2)

	
	react-navigation": “^4.0.10” se tiene que ser defaultNavigationOptions

* **WilliamVelazquez** (2)

	
	¿Con qué combinación de teclas se pueden poner los emojis? 😃

	* **Daniel Pereira** (4)

		
		en mac es con la combinación de Control+Commnad+Espacio

	* **WilliamVelazquez** (1)

		
		Muchas gracias 😃, ¿sabes cuál será en Windows? o si debo instalar algo extra?

	* **Daniel Pereira** (2)

		
		estuve viendo y hay 2 opciones  
		con el teclado virtual [aquí](https://omicrono.elespanol.com/2015/08/como-usar-emoji-en-windows-10/) te explican como ponerlo  
		o abre [esta pagina](https://getemoji.com) donde están todos los emojis y solo copia y pega, creo que también puedes descargar la pagina en formato web completo para verla sin necesidad de internet

	* **WilliamVelazquez** (1)

		
		De nuevo gracias 😃

	* **Carlos Enrique Gonzalez Peña** (2)

		
		Yo uso esta [Emojipedia](https://emojipedia.org/)[]  
		Es muy similar a la que pone Daniel

	* **WilliamVelazquez** (2)

		
		Muchas gracias @cgonzalez91 😃

	* **Ivan Robles** (2)

		
		El comando para los emojis ha sido de lo mejor!! gracias @danielpp95

	* **Alberto González** (1)

		
		¡Hola!  
		Puedes abrir el menú de los emojis en windows con el siguiente shortcut: ’ Windows + . ’ (Tecla windows más la tecla punto)

* **Ezequiel Alejandro Barrales** (1)

	
	Haciendo ésto con React Navigation 4 me salió un Warning sobre el parámetro ‘header’ de defaultNavigationOptions.
	
	Lo que hizo como:
	``` 
	    navigationOptions: {
	    	header: <Text>Esto es un header</Text>
	    }
	    
	```
	
	Ahora debe ser una función que retorne ese componente (ya sabrán como sacarle provecho siendo una función):
	``` 
	    defaultNavigationOptions: {
	    	header: () => <Text>Esto es un header</Text>
	    }
	    
	```

* **José Tuzinkievicz** (1)

	
	La opción  
	`gesturesEnabled: true,`  
	no me funciona en Android y estoy usando la misma versión de React Navigation que Leonidas…

* **Karl Heitmann** (1)

	
	personaliza la parte de header "back"

* **Karl Heitmann** (1)

	
	ejemplo de personalizacion del header: headerTitleAllowFontScaling: true

* **Christian Michelle Torres Martínez** (1)

	
	no me funciona el navigationOptions fuera de los screens 😦

	* **Danvasem** (4)

		
		En la última versión de ‘react-navigation’ cambió y ahora debes colocar la propiedad ‘defaultNavigationOptions’.

	* **Alexis Silva** (1)

		
		Gracias danvasem es la respuesta correcta

* **brunosendras** (1)

	
	Que hace exactamente cada propiedad? Este es el link de la documentación de React Navigation [Navigation Options](https://reactnavigation.org/docs/en/stack-navigator.html#navigationoptions-for-screens-inside-of-the-navigator)

* **Luis Alberto Sandoval Monestel** (1)
Buenos Días, donde se encuentran la diapositivas?

	* **Juan David Castro (Platzi)** (1)

		
		¡Hola!
		
		Ya los encuentras en la primera clase:
		
		  * <https://platzi.com/clases/1308-react-navigation/11973-bienvenidos-el-curso-de-react-navigation/>
		  * <https://static.platzi.com/media/public/uploads/react-navigation_09901d65-e8cd-4275-a858-43870346c0d9.pdf>
		
		

* **WilliamVelazquez** (0)
¿Con qué combinación de teclas se pueden poner los emojis? 😃

	* **Daniel Pereira** (4)

		
		en mac es con la combinación de Control+Commnad+Espacio

## 0080. Configuraciones visuales al Stack Navigator

### Descripción:


Ahora hablemos del Stack de configuraciones visuales que tenemos en React Navigation.

-mode: nos permite saber si estamos en una pantalla o en un modal.  
-headerMode: Para ver si esta flotando o en la pantalla.  
-heaserTransitionPreset: Cual es la transición del header en el momento de la navegación.  
-cardStyle: Estilos del componente.  
-transitionConfig: Configuras cómo ocurren las transiciones.

### Comentarios:

* **Ivan Robles** (15)

	
	Parámetros de las configuraciones visuales de **StackNavigator** :
	
	  * **mode** : 
	    * **modal** al cambiar de pantalla esta entra de abajo hacia arriba (por default en android)
	    * **card** al cambiar de pantalla esta entra desde el costado(por default en iOS)
	  * **headerMode** : 
	    * **none** , sin un header.
	    * **screen** el header se mueve (default android).
	    * **float** el header se queda fijo (default iOS).
	  * **headerTransitionPreset** : animación en el header. 
	    * **fade-in-place** (alfa de 0 a 1).
	    * **uikit** (el header se mueve y también cambia el alfa de 0 a 1).
	  * **cardStyle** : Estilos para el componente que envuelve nuestra screen (backgroundColor, borders, etc).
	
	

* **George_18** (2)

	
	Hola 😄 como puedo hacer para para que una vez el usuario vea mi onboarding no lo muestre mas y cuando abra al app en otras ocaciones llegue directo al home ?

	* **Rodman M. Swanston C.** (2)

		
		Podrías crear una variable en `AsyncStorage` y si es la primera vez del usuario en la app muestras el onboarding y cambias la variable.

	* **Diego Alexander Forero Higuera (Platzi)** (5)

		
		Puedes guardar en la base de datos el estado de la visualización del onboarding, lo consultas cuando el usuario entre, recuerda que si un cambia de dispositivo si usas el storage del dispositivo entonces le vas a volver a mostrar el onboarding si lo almacenas en la base de datos no vas a tener este problema.

	* **George_18** (1)

		
		como estoy trabajando el auth con firebase podria usar el database ?

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		Si, sin problema, solo creas el campo y validas en cada login

* **esdraspavon** (1)

	
	En la version 4 de React navigation, el cardStyle, debe estar dentro de la configuración de navigationOption, o defaultNavigationOption.
	``` 
	    defaultNavigationOptions: {
	        ....
	          cardStyle:{
	            borderWidth: 2,
	          },
	    },
	    
	```

* **Karl Heitmann** (1)

	
	Comienza el ejemplo de como hacer las configuraciones visuales vistas en las diapositivas anteriores

* **Melina Jacqueline onoriaga** (1)

	
	“A android le vale” jajjajaja

	* **Javier Asencio** (1)

		
		pareciera q no accioana los efectos la verdad

* **Sergio David Serrano Garcés** (1)

	
	Una pregunta puedo usar el headerMode en una pantalla especifica unicamente?

	* **Miguel Cobas** (1)

		
		intenta poniendo esto dentro de la pantalla
		``` 
		    classHomeextendsComponent{
		        static navigationOptions = {
		            title:'Pantalla',
		            headerMode: 'none',
		          };
		        ```
		    
		    Espero te sirva 
		    
		```

* **George_18** (1)
Hola 😄 como puedo hacer para para que una vez el usuario vea mi onboarding no lo muestre mas y cuando abra al app en otras ocaciones lleg...

	* **Rodman M. Swanston C.** (2)

		
		Podrías crear una variable en `AsyncStorage` y si es la primera vez del usuario en la app muestras el onboarding y cambias la variable.

## 0090. Pasando parámetros entre pantallas

### Descripción:


En esta clase vamos a aprender dos cosas, en primer lugar veremos cómo se pasan parámetros entre pantallas y luego veremos como sacarle mas provecho al navigation option.

### Comentarios:

* **Ivan Robles** (9)

	
	En cualquier componente que sea una pantalla, recibimos un método estático **navigationOptions** donde vamos a retornar las opciones que podemos configurar.
	``` 
	    static navigationOptions = ({ navigation }) => {
	        return {
	            title: navigation.getParam('name')
	        }
	    }
	    
	```
	
	Con el método **navigate()** ademas de “movemos” hacia otra pantalla, también le podemos enviarle parámetros como segundo parámetro:
	``` 
	    handlePress = () => {
	        this.props.navigation.navigate('Profile', {
	            name: 'Ivan Robles'
	        });
	    }
	    
	```
	
	Podemos obtener parámetros con el método de navigation **getParam()** , el cual recibe 2 cosas, el parámetro que queremos obtener y un valor por defecto para ese parámetro en caso de no encontrarlo:
	``` 
	    navigation.getParam('age', 30);
	    
	```

	* **ordep96** (1)

		
		capo

* **esdraspavon** (1)

	
	Para los que estan probando con componentes funcionales, para usar navigation options, hay que declarar el componente, y luego declarar navigationOptions:
	``` 
	    const Home = (props) => {
	     ...
	    
	      const setParams = () => {
	        props.navigation.setParams({name: 'Pedro Suarez'});
	      };
	    
	      ...
	    };
	    
	    Home.navigationOptions = ({navigation}) => {
	      return {
	        title: `${navigation.getParam('name')} ${navigation.getParam('age', 24)}`,
	      };
	    };
	    
	    
	    export default Home;
	    
	```

* **Karl Heitmann** (1)

	
	Con la ayuda de un evento asociado a un botón, logra cambiar el parámetro recibido por la pantalla anterior. Esto modifica el título del header también.

* **Karl Heitmann** (1)

	
	Ocupa navigation.getParams para dentro del método estático acceder a los parámetros enviados desde navigate en la pantalla anterior.

* **Karl Heitmann** (1)

	
	El segundo parámetro que recibe this.props.navigation.navigate() corresponde a los parámetros que se enviarán a la pantalla a la cuál se quiere navegar.

* **Karl Heitmann** (1)

	
	Cualquier componente ==QUE SEA UNA PANTALLA== va a tener un método estático que me permitirá cambiar el título de esa página en el header de navegación.

* **jenapi** (1)

	
	Como aporte quiero decir que si tratan de usar navigation con redux, tienen que hacer algo diferente, pero está todo en la documentación

## 0100. Pasando navigation prop a cualquier componente

### Descripción:


### Comentarios:

* **Juan David Castro (Platzi)** (11)

	
	Damn. Haber visto esta clase antes 😭… En mi ignorancia escribí un **HOC** para pasar `navigation` a cualquier componente, no sabia que ya había uno 😅 😛.
	
	<https://github.com/juandc/PlatziMusic/blob/master/utils/navigation.js>
	``` 
	    import React from"react";
	    
	    const { Provider, Consumer } = React.createContext();
	    
	    exportclassNavigationProviderextendsReact.Component{
	      render() {
	        const { render, children, navigation } = this.props;
	    
	        return<Providervalue={navigation}>{render || children}</Provider>;
	      }
	    }
	    
	    exportconst NavigationConsumer = ({ render, children, ...props }) => (
	      <Consumer {...props}>{render || children}</Consumer>
	    );
	    
	    exportfunctionwithNavigation(WrappedComponent) {
	      returnfunctionwithInheritProps(props) {
	        return (
	          <NavigationConsumer
	            render={navigation => (
	              <WrappedComponent {...props} navigation={navigation} />
	            )}
	          />
	        );
	      };
	    }
	    
	```

	* **Ivan Robles** (4)

		
		Tan bonito que te había quedado tu **HOC** con el **Context API** @juandc 😭
		
		…pulgar arriba para sentirse mejor!! 😃

	* **Juan David Castro (Platzi)** (1)

		
		Thank u @elSharmaz 😃

* **Kingsman7** (2)

	
	y esto como lo ligo con redux? o eligo entre uno y el otro?

* **Enzo Aliatis** (2)

	
	Cual vendría a ser la diferencia de withNavigation con NavigationActions ?

	* **alesanabriav** (2)

		
		La única es que withNavigation te inserta el prop de navigation con un high order function y NavigationActions tienes directo la navegación

* **Karl Heitmann** (1)

	
	Decora exitosamente la funcion Name(props) para que tenga aceso a props.navigation.

* **Karl Heitmann** (1)

	
	Es importante considerar la diferencia entre clase y función.
	
	En el caso de las clases, estas al entrar en la configRoute de createNavigationStack, adquieren automáticamente la propiedad de navigation que les permite dentro de cualesquiera de sus métodos navegar a otra página, enviar parámetros, etc.
	
	En cambio en las funciones, estas no deberían entrar en el createNavigationStack, por eso es que se decoran utilizando **wwithNavigation**

	* **Manuel Rivera** (1)

		
		excelente aporte bro, muchas gracias

* **Sofía Lisset Chuquín De la Cruz** (1)

	
	Wow!, con **withNavigation** hubiera ahorrado mucho código.

* **Enzo Aliatis** (1)
Cual vendría a ser la diferencia de withNavigation con NavigationActions ?

	* **alesanabriav** (2)

		
		La única es que withNavigation te inserta el prop de navigation con un high order function y NavigationActions tienes directo la navegación

## 0110. Combinando navigators - modal

### Descripción:


### Comentarios:

* **Kingsman7** (2)

	
	¿en android no funciona el mode:‘modal’?

* **mayraaceves** (2)

	
	Si les aparece el error _React Navigation Error: The navigation prop is missing for this navigator_ deben de usar _createAppContainer_
	``` 
	    const Main = createAppContainer(
	      createStackNavigator(
	        {
	          Main: {
	            screen: AppNavigator
	          },
	          Login: {
	            screen: Login
	          }
	        },
	        {
	          mode: "modal",
	          headerMode: "none"
	        }
	      )
	    );
	    
	    exportdefault Main;
	    
	```

* **Karl Heitmann** (1)

	
	Muestra un ejemplo funcionando de la combinación de dos stackNavigators... pero hay algo raro en el header: en breve mostrará como solucionarlo.

* **Karl Heitmann** (1)

	
	Explica como se pueden sobreescribir en el otro stackNavigator las propiedades del header.

* **Karl Heitmann** (1)

	
	Combinará un StackNavigator con una vista.

* **Karl Heitmann** (1)

	
	En un ejemplo hipotético, explica las circunstancias bajo las cuáles se justifica crear dos o más StackNavigator que cumplan distintos roles.

* **Roberto Urita Jiménez** (1)

	
	Como podríamos desactivar el back, en los teléfonos android en la pantalla de login. Es decir, que después de hacer login, no puedan regresar a esta pantalla con el botón físico de los teléfonos android. Gracias.

	* **Daniel Alberto Esquinazi** (5)

		
		Tal vez esto te ayude: <https://reactnavigation.org/docs/en/auth-flow.html>

	* **Roberto Urita Jiménez** (1)

		
		Muchas gracias, ya lo había solucionado. Exactamente con esta liga que me proporcionas. Muchas gracias.

	* **Edgar de Jesus Mendoza Ortegon** (2)

		
		Te comparto mi código por si te sirve de algo.
		``` 
		    import { createStackNavigator } from "react-navigation";
		    import Intro from "./components/Intro/Intro";
		    import Login from "./containers/Login/login";
		    import Home from "./containers/Home/Home";
		    
		    const LoginStack = createStackNavigator(
		      {
		        Intro: Intro,
		        Login: Login
		      },
		      {
		        headerMode: "none"
		      }
		    );
		    
		    const AppStack = createStackNavigator({
		      Home: Home
		    });
		    
		    const AppNavigator = createStackNavigator(
		      {
		        LoginStack: {
		          screen: LoginStack,
		          navigationOptions: {
		            header: null
		          }
		        },
		        AppStack: {
		          screen: AppStack,
		          navigationOptions: {
		            header: null
		          }
		        }
		      },
		      {
		        headerMode: "screen",
		        initialRouteName: "AppStack"
		      }
		    );
		    
		    exportdefault AppNavigator;
		    
		```

* **Jose R. Torrens Acosta** (1)

	
	Según entiendo, esto sirve cuando tenemos una app que tiene varios modulos, por ejemplo. Account (Login, register recovery) y otro que muestre por ejemplo listados. Y entonces podría tener uno por cada modulo, y un main que los englobe.
	
	De esta forma hasta podrían estar en folders distintos.

## 0120. Stack Actions

### Descripción:


Algo que hemos venido usando es el navigation prop, que es la funcion que nos permite navegar. Veamos que otras opciones nos ofrece esta opción.

  * **.navigate():** Sirve para ir a otra pantalla de las rutas definidas.
  * **.goBack():** Es para movernos hacia atrás en la ruta.
  * **.addListener():** Para que puedas escuchar eventos dentro de la pantalla a la que estas llegando.
  * **.isFocused():** Retorna Verdadero o falso si estas o no en una pantalla.
  * **.state:** retorna el key, la ruta, parametros.
  * **.setParams():** setear parametros.
  * **.dispatch() documentacion:** <https://reactnavigation.org/docs/en/stack-actions.html#push>



### Comentarios:

* **Ivan Robles** (6)

	
	**StackActions** :
	
	  * **.push()** Agrega una pantalla al Stack sin importar si ya estaba el Stack.
	  * **.pop()** Va a quitar el ultimo elemento del Stack.
	  * **.popToTop()** Va a quitar todos hasta quedar al primer elemento del Stack.
	  * **.replace()** Reemplaza los datos de un elemento del Stack.
	  * **.reset()** Reemplaza el estado actual con un nuevo estado (todo el Stack).
	
	

* **WilliamVelazquez** (4)

	
	@LeonidasEsteban Entonces cuáles serían las ventajas de navegar mediante dispatch y no con navigate?

	* **Diego Alexander Forero Higuera (Platzi)** (4)

		
		navigate usa de forma interna dispatch.

	* **WilliamVelazquez** (1)

		
		Gracias GOLLUM 😃

* **Kingsman7** (2)

	
	wow nunca pensé decir esto pero, no me gusto esta clase. Esto porque vi la super utilidad que tiene el .replace() en el ejemplo que nos dio Leonidas con la app de platzi que me pareció super brutal. y solo SOLO ponen en practica el .push() fue una decepción

* **Karl Heitmann** (1)

	
	Ejemplo listo de como despachar hacia redux de la forma "carretera", escribiendo todo a mano. Está ahora a punto de mostrar como se despacha un evento a Redux utilizando métodos proporcionados por StackActions.

* **Karl Heitmann** (1)

	
	Explicación de StackActions: .push, pop, etc.

* **Karl Heitmann** (1)

	
	Aqui explica como this.props.navigation tiene el metodo .dispatch(), que sirve para conectarse con redux y así persistir data.

* **Karl Heitmann** (1)

	
	Explica todos los métodos que tiene props.navigation, no solo el .navigate() que era lo que habíamos estado ocupando.

* **Felipe Ruiz** (1)

	
	Como alternativa al array, pienso que seria mejor visualizarlo como una pila, tal como lo indica su nombre.  
	En fin, excelente explicación!

* **Eduardo Serrano Jaime** (1)
Como seria para navegar a otra pantalla pero desmontando la pantalla anterior?

* **WilliamVelazquez** (0)
@LeonidasEsteban Entonces cuáles serían las ventajas de navegar mediante dispatch y no con navigate?

	* **Diego Alexander Forero Higuera (Platzi)** (4)

		
		navigate usa de forma interna dispatch.

## 0130. Navigator Actions

### Descripción:


Otro gurpo de acciones comunes que son importantes en el momento de agregar navegación a nuestras aplicaciones.

**.navigate()**  
**.back()**  
**.setParams()**  
**.init()**

Cuando trabajemos con Redux no va a hacer falta que usemos navigation.

### Comentarios:

* **Felipe Ruiz** (10)

	
	 **Navigation Actions**
	
	**.navigate()** \- Navegar a otra ruta  
	**.back()** \- Volver a un estado previo  
	**.setParams()** \- Establecer parámetros para la ruta dada  
	**.init()** \- Se usa para inicializar el primer estado si el estado no está definido

* **Karl Heitmann** (1)

	
	Muestra el demo de como funciona navigation.dispatch con un NavigationActions.navigate enviado como parametro.

# Integrando Platzi Video con React Navigation

## 0140. Configurando react navigation con Redux

### Descripción:


Y conoces el API de React Navigation y como usar sus diferentes funciones.

Ahora vamos a trabajar con un proyecto real, para esto vamos a tomar como base el proyecto que hicimos en el curso de React Native en [Platzi.com/native](http://Platzi.com/native).

### Comentarios:

* **Christian Omar López Macías** (10)

	
	Configurando React Navigation con Redux
	
	  1. app-navigator.js: Tener un solo archivo con el componente que crea el navigator.
	  2. Installar react-navigation-redux-helpers: Middlewares y utilidades para integrar react navigation a un proyecto con redux.
	  3. navigation.js: 
	    * createNavigationReducer helper pasando por parametro el componente de navegación (app-navigator)
	    * Combinar reducers
	  4. store.js: 
	    * Traer el reducer principal
	    * Usar createReactNavigationReduxMiddleware para que nuestro store pueda escuchar las acciones de react navigation
	  5. app-navigator-with-state.js 
	    * Conectar el componente a redux
	    * Utilizar createReduxBoundAddListener, createDidUpdateCallBack y initiaizeListeners
	    * Personalizar el componente de app-navigator
	
	

	* **Ivan Robles** (2)

		
		Gracias por el apunte amigo!! 😄

* **Tobías Schwarz** (3)

	
	Para los que estén trabajando con ReactNative V0.6+ hay que instalar el AsyncStorage para que funciones redux-persists, ya que lo separaron del core y asimismo el webview hay que instalarlo aparte con react-native-webview

* **Alexander Miguel Ferreras Concepción** (2)

	
	Saludos, si alguien desea tener la app de platzi video con EXPO, aqui les comparto el repositorio para que no tengan que usar emulador.
	
	Solo tienen que hacer., yarn install y npm start
	
	<https://github.com/alexander0205/Platzi-Video-Con-Expo>

* **nixon-gamboa** (1)

	
	Aun no logro entender especificamente para que utilizan redux-helpers aplicados a esta app?

* **deveeup** (1)

	
	<https://github.com/LeonidasEsteban/platzi-video-react-native>

* **Ronald Cuello** (1)

	
	Que podemos hacer respecto a esto:  
	Warning: in the next major version of React Navigation, to be released in Fall 2018, we will no longer provide any information about how to integrate with Redux and it may cease to work. Issues related to Redux that are posted on the React Navigation issue tracker will be immediately closed. Redux integration may continue to work but it will not be tested against or considered when making any design decisions for the library.****  
	<https://reactnavigation.org/docs/en/redux-integration.html>

	* **Miguel Cobas** (1)

		
		de hecho en la misma documentación te dice que es lo que podrías hacer al respecto, dale una leida 😄.
		
		Creo que es como lo haremos en este curso

* **George_18** (0)

	
	que diferencia hay entre un StackNavigator y un switch Navigator ?

	* **Diego Alexander Forero Higuera (Platzi)** (4)

		
		StackNavigator permite hacer transición entre pantallas o screens de tu aplicación, cada nueva pantalla se va poniendo en una pila. SwitchNavigator solo permite manejar o mostrar una pantalla al tiempo, el caso de uso común es en el flujo de autenticación, donde la pantalla de login desaparece y se muestra otra una vez el login es existoso y no puede hacer atras para volver al login, tiene que desloguearse para ver nuevamente esa pantalla.

	* **George_18** (1)

		
		Hola Gollum 😄, Ok ahora en mi aplicación estoy utilizando StackNavigator y SwitchNavigator y funciona bien pero el problema es cuando se cierra la aplicación y la abro de nuevo tiene que hacer el login de nuevo 😕, si hago uso del asyncstorage como puedo hacer que persista la sesion iniciada. el auth lo tengo funcionado con (email & password) y facebook con firebase ?

	* **Diego Alexander Forero Higuera (Platzi)** (4)

		
		No he trabajado mucho con react, pero en un sistema web normal se debe guardar la sesión para que mantenga la autenticación, puedes usar algo como esto
		``` 
		    import { AsyncStorage } from "react-native";
		    
		    exportconst USER_KEY = "auth-demo-key";
		    
		    exportconst onSignIn = () => AsyncStorage.setItem(USER_KEY, "true");
		    
		    exportconst onSignOut = () => AsyncStorage.removeItem(USER_KEY);
		    
		    exportconst isSignedIn = () => {
		      returnnew Promise((resolve, reject) => {
		        AsyncStorage.getItem(USER_KEY)
		          .then(res => {
		            if (res !== null) {
		              resolve(true);
		            } else {
		              resolve(false);
		            }
		          })
		          .catch(err => reject(err));
		      });
		    };
		    
		```

	* **George_18** (1)

		
		Gracias lo voy a revisar

* **George_18** (0)
que diferencia hay entre un StackNavigator y un switch Navigator ?

	* **Diego Alexander Forero Higuera (Platzi)** (4)

		
		StackNavigator permite hacer transición entre pantallas o screens de tu aplicación, cada nueva pantalla se va poniendo en una pila. SwitchNavigator solo permite manejar o mostrar una pantalla al tiempo, el caso de uso común es en el flujo de autenticación, donde la pantalla de login desaparece y se muestra otra una vez el login es existoso y no puede hacer atras para volver al login, tiene que desloguearse para ver nuevamente esa pantalla.

## 0150. Añadiendo react navigation a Platzi Video

### Descripción:


### Comentarios:

* **luisferbedon** (9)

	
	en versiones actuales no me funciona la integración, me gustaría que actualicen los videos. Gracias

* **Rafael Enrique Gonzalez** (9)

	
	Este curso tienen que actualizarlo, hoy en día es imposible seguir el curso sin perder tiempo modificando cosas.

* **Kingsman7** (6)

	
	en esta parte muchas cosas cambiarón con la versión del “react-navigation-redux-helpers”: “^3.0.2”,
	
	el Middleware es igual solo que la key ‘root’ es opcional, aplica si se tiene mas de un store.Así que em Middleware queda así
	``` 
	    const navigationMiddleware =createReactNavigationReduxMiddleware(
	        state => state.navigationReducer )
	    
	```
	
	ahora lo que mas cambio tubo es el AppNavigatorWithState. ya que las funciones initializeListeners, createReduxBoundAddListener, createNavigationPropConstructor, createDidUpdateCallback, reduxifyNavigator, DEPRECARON y ahora todo se resume a usar la función createReduxContainer
	
	para este caso se utiliza de la siguiente manera
	``` 
	    import { 
	        createReduxContainer
	     } from 'react-navigation-redux-helpers';
	    import { connect } from 'react-redux';
	    import AppNavigator from './appNavigator';
	    
	    const AppNavigatorWithState = createReduxContainer(AppNavigator) 
	    
	    const mapStateToProps=(state)=>{
	      return{
	        navigation : state.navigationReducer
	      }
	    }
	    
	    exportdefault connect(mapStateToProps)(AppNavigatorWithState)```
	    
	    donde solo esta linea const AppNavigatorWithState = createReduxContainer(AppNavigator)  reemplaza la toda la clase que el gran Leonidas nos explico.
	    
	    de momento me funciona igual, hace su middleware y me envia los listener quizas hace falta algo más pero hasta ahora me funciona
	    
	```

	* **jenapi** (3)

		
		Saludos, Estoy con este error, seguí el video hasta la parte de app-navigator-with-state y al createReduxMiddleware le quité el ‘root’
		``` 
		    typeError: Undefined is not an object (evaluating state.routes)
		    
		```

* **Christian Omar López Macías** (6)

	
	Me gustaría agregar algo más. Quizás a estas alturas lo más conveniente será utilizar react navigation sin redux ya que torna más complejo el código, además en el sitio oficial ya no darán soporte para los que tengan integrado react navigation con redux e incluso ya no tomarán en cuenta redux en las futuras mejoras de react navigation.

	* **Brayam Ruiz** (3)

		
		Alguna alternativa, efectivamente en el site de react navigation aclaran que no van a dar mas soporte a redux 😕

	* **ferontv_** (1)

		
		Ésta es la alternativa que ellos mismos mencionan en la documentación: [Navigating without the navigation prop](https://reactnavigation.org/docs/en/navigating-without-navigation-prop.html)

	* **Edgar de Jesus Mendoza Ortegon** (2)

		
		puedes usar este paquete <https://github.com/aksonov/react-native-router-flux> es parecido a react navigation y facil integracion con redux

	* **linampatino** (1)

		
		Hola, tengo una pregunta… Entonces debería quitar redux por completo de mi proyecto?

	* **SAVelasco** (1)

		
		@linampatino No, en este caso estaban integrando el redux para centralizar la forma de la navegación y todo lo usemos con el dispatch, sin embargo, redux se usa normalmente para el control del flujo de la información, asi que redux se queda para que puedas ‘orquestar’ tu información, pero el redireccionamiento pues se tendrá que manejar aparte.

* **Saulo_Puma** (5)

	
	es hora de actualizar el curso 😄

* **Javier Asencio** (5)

	
	por favor seria bueno q actualicen el curso de reacnavigation, se torna un poco dificil ayudarse con las clases

* **brunosendras** (5)

	
	app-navigator-with-state.js  
	Deberia quedar asi con la nueva version de navigator.
	``` 
	    import React, { Component } from'react';
	    import { connect } from'react-redux';
	    import { reduxifyNavigator } from'react-navigation-redux-helpers';
	    
	    
	    import AppNavigator from'./app-navigator';
	    
	    const AppNavigatorWithState = reduxifyNavigator(AppNavigator, 'root');
	    
	    const mapStateToProps = state => ({
	        state: state.navigation
	    })
	    
	    exportdefault connect(mapStateToProps)(AppNavigatorWithState);
	    
	```

	* **Danvasem** (1)

		
		Funcionó correctamente, y es mucho más sencillo en la nueva versión que en la que usa Leonidas.

	* **Miguel Cobas** (4)

		
		En la versión 3 hay que cambiar reduxifyNavigator por createReduxContainer
		``` 
		    import { connect } from'react-redux';
		    import { createReduxContainer } from'react-navigation-redux-helpers';
		    
		    
		    import AppNavigator from'./app-navigator';
		    
		    const AppNavigatorWithState = createReduxContainer(AppNavigator, 'root');
		    
		    const mapStateToProps = state => ({
		        state: state.navigation
		    })
		    
		    export default connect(mapStateToProps)(AppNavigatorWithState);
		    
		```

* **JuanM04** (5)

	
	A fines de 2018, React Navigation **dejará** (o dejó, depende de cuando lo leas) de darle soporte a la integración Redux-React Navigation. Por ende, he aquí mi aporte traido directamente de la [documentación oficial](https://reactnavigation.org/docs/en/navigating-without-navigation-prop.html) de cómo hacer lo que Leonidas explica en el vídeo de la “nueva forma”.
	
	_**Nota** : Todo a continuación se aplica al proyecto de PlatziVideo antes de esta clase, por ende si ya hiciste cambios en el proyecto de PlatziVideo desde que tomaste este curso, deshacelos._
	
	_**Nota** : Todos los nombres de archivos y de funciones, además de las rutas, pueden ser cambiadas._
	
	  1. Instalar React Navigation
	
	
	``` 
	    npm install--save react-navigation
	    
	    yarn add react-navigation
	    
	```
	
	  1. Crear, en algún lugar de tu proyecto, el archivo **NavigationService**.js
	
	
	``` 
	    // Importamos NavigationActions
	    import { NavigationActions } from 'react-navigation';
	    
	    // Creamos un Navigator. Más adelante se explica qué es
	    let _navigator;
	    
	    // Declaramos la función para decirle a ReactNavigation cuál es nuestro Navigator. Lo mismo de antes, luego se explica qué es
	    functionsetTopLevelNavigator(navigatorRef) {
	      _navigator = navigatorRef;
	    }
	    
	    // Creamos las funciones que nos parezcan necesarias (navigate, back, etc.)
	    functionnavigate(routeName, params) {
	      // Usamos el método dispatch del Navigator
	      _navigator.dispatch(
	        // Lo que ya sabemos de navigate
	        NavigationActions.navigate({
	          routeName,
	          params,
	        })
	      );
	    }
	    
	    
	    // Exportamos las funciones (de crear otra función, mencionarla aquí)
	    exportdefault {
	      navigate,
	      setTopLevelNavigator,
	    };
	    
	```
	
	  1. Ahora en nuestro App.js
	
	
	``` 
	    // Importamos nuestro archivo posteriormente creado
	    importNavigationServicefrom './NavigationService';
	    
	    // Creamos un StackNavigator, el Navigator anteriormente mencionado (_navigator).
	    constTopLevelNavigator = createStackNavigator({ 
	      // Recordatorio: AppLayout es nuestro componente principal y debe estar importado
	      Home: AppLayout
	    })
	    
	    
	    
	    class App extends Component<Props> {
	      render() {
	        return (
	          <Provider
	            store={store}
	          >
	            <PersistGate
	              loading={<Loading/>}
	              persistor={persistor}
	            >
	              // Llamamos a nustro StackNavigator (si, el Navigator retorna un componente) reemplazando nuestro AppLayout
	              <TopLevelNavigator
	                // Le hacemos una referencia y se la mandamos a nuestro NavigationService 
	                ref={ref => {
	                  NavigationService.setTopLevelNavigator(ref);
	                }}
	              />
	            </PersistGate>
	          </Provider>
	        )
	      }
	    }
	    
	```
	
	  1. Ahora, en cualquier componente que lo necesitemos
	
	
	``` 
	    // componente.js
	    
	    // Importamos nuestro NavigationService (reemplazar 'path' por la ruta)
	    import NavigationService from '(path)/NavigationService.js';
	    
	    // ...
	    
	    // Y usamos el método navigate
	    NavigationService.navigate('Login', { name: 'Leonidas Esteban' });
	    
	```

	* **mauroalejandro** (1)

		
		Esto igualmente con ya la integracion de Redux realizada? estoy siguiendo apenas el curso con un proyecto personal y quiero llevarlo de la mano… pero entonces no integro redux o si tal cual y hago esto que indicas?

	* **JuanM04** (1)

		
		@mauroalejandro  
		No sé con exactidud como funcionará con la integración de Redux hecha. Sin embargo, te recomiendo que en los próximos proyectos que hagas, uses este método, ya que es el actual.
		
		PD: Por si algo de mi explicación no quedó claro, en la página de la documentación (mencionada anteriormente) hay más información

* **Alexis Silva** (4)

	
	Muchas experiencias sobre la actual versión y que hacer… Compartiré los únicos cambios que me sirvieron para arrancar la app siguiendo el código de este vídeo:
	
	  1. En la actual versión además de createStackNavigator se debe agregar un segundo componente llamado createAppContainer  
	app-navigator.js:
	
	
	``` 
	    import {createStackNavigator, createAppContainer} from 'react-navigation'
	    import Loading from './sections/components/loading'
	    
	    const Main = createStackNavigator(
	        {
	            Home: Loading
	        }
	    )
	    
	    exportdefault createAppContainer(Main)
	    
	```
	
	  1. Leonidas explica **en el siguiente vídeo** el cual es un artículo no un vídeo, **como debe ser** el código del archivo **app-navigator-with-state-js** , faltó que en la actual versión **se reemplaza reduxifyNavigator por createReduxContainer**
	
	  2. Me arrojaba un error que decía **navStateSelector is not a function** y lo solucioné comentando la key en el store.js:
	
	
	
	``` 
	    const navigationMiddleware = createReactNavigationReduxMiddleware(
	      //'root',
	      state => state.navigation
	    )
	    
	```
	
	El resto lo tengo igual que en el vídeo del curso. Uso expo para tomar este curso y el de ReactNative. Hasta ahora, todo bien (Y)

	* **romeomunoz** (1)

		
		Sigo sin lograrlo, comparte tu repo. saludos

* **Miguel Cobas** (4)

	
	Recuerden que con react-navigation 3 hay que instalar react-native-gesture-handler al proyecto.
	``` 
	    npm install--save react-navigation react-native-gesture-handler react-navigation-redux-helpers
	    
	    react-nativelink para vincular los gestures
	    
	```
	
	Adicional hay que importar en el archivo app-navigator.js “createAppContainer” ya que la ultima versión de react navigation el StackNavigation debe de estar dentro de un contenedor
	``` 
	    import { createStackNavigator, createAppContainer } from 'react-navigation'
	    import Loading from './screens/components/loading'
	    
	    const Main = createStackNavigator(
	        {
	            Home: Loading
	        }
	    )
	    
	    exportdefault createAppContainer(Main);```
	    
	    
	    
	```

* **Jesus Camacaro** (3)

	
	actualicen el curso

* **Gerardo Cetzal Balam** (3)

	
	Spolier: si te da error con el app navigator with state Leonidas te da una explicación de lo que paso, para que no sufras tanto, básicamente es esto
	``` 
	    import React, { Component } from'react';
	    import { connect } from'react-redux';
	    import AppNavigator from'./app-navigator';
	    import {
	      createReduxContainer,
	    } from'react-navigation-redux-helpers';
	    
	    const reduxContainer = createReduxContainer(AppNavigator, 'root');
	    
	    classAppNavigatorWithStateextendsreduxContainer{
	    
	    }
	    
	    functionmapStateToProps(state) {
	      return {
	        state: state.navigation
	      }
	    }
	    
	    exportdefault connect(mapStateToProps)(AppNavigatorWithState)
	    
	```

	* **Sebastian Wilde Alarcón Arenas** (1)

		
		Buena solución, gracias

* **Alexander Miguel Ferreras Concepción** (3)

	
	La sinceridad de leonidas no tiene madre. es igualito a @freddy

* **Juan David Castro (Platzi)** (3)

	
	Solo dire una cosa: Esta clase ha sido la más terriblemente traumática que ha dado Leo en mucho mucho tiempo… 😅 😄
	
	Que cursooooo!! 🎉

	* **Joel Alejandro Morales García** (1)

		
		Pensé lo mismo cuando vi que el video duraba 28.33 min 😅

* **jegoxme** (2)

	
	Compañeros a todos les recomiendo instalar las dependencias que estan en el repo de github [https://github.com/LeonidasEsteban/platzi-video-react-navigation/blob/master/package.json](url)

* **Melina Jacqueline onoriaga** (2)

	
	Creo que esta clase ya quedo muy desactualizada, porque no encuentro como hacerlo funcionar con todo lo nuevo de react native y tampoco me sirve usar una versión mas vieja de react navigation, porque no machea con lo nuevo de native asi que booom! yo creo que lo mejor es seguir la documentacion y ya … <https://reactnavigation.org/docs/en/redux-integration.html>

	* **Alexis Silva** (2)

		
		que has cambiado? puedes pegar acá el código de lo que has cambiado xfavor?

	* **Melina Jacqueline onoriaga** (1)

		
		Alex_Sil dale! es mucho mas simple ahora! luego te pego el código de como lo logre 😃

* **Christian Núñez** (2)

	
	creanme es mejor con Redux, te sirve de base y la siguiente vez es mas fácil, solo no desesperen!

* **Oscar Estuardo de la Mora** (1)

	
	Segun entiendo en la documentacion de React Navigation 5.x (que es la mas actualizada por que hasta este momento tomo este curso), todo esto ya no se hace cierto?

	* **Manuel Rivera** (1)

		
		La verdad no la he leido bro, estaba realizando el curso con las ultimas versiones pero han cambiado muchas cosas, así que decidí realizar el curso con las versiones de este para aprender lo básico , después actualizarme.

* **Luis Alberto Sandoval Monestel** (1)

	
	Actualicen el curso, por favor.

* **Karl Heitmann** (1)

	
	Habla de los archivos que va a crear para poner la logica de navegacion

* **Karl Heitmann** (1)

	
	instalación de dependencias

* **Jesús Angel González Nuñez** (1)

	
	La nueva versión de React Navigation necesita otras dependencias.  
	Si les marca el error de:  
	`rn gesture handler module.state`
	
	Puedes hacer lo siguiente para resolverlo.  
	remover node_modules and package-lock.json  
	`npm install`  
	`npm install --save react-navigation ``npm install --save react-native-gesture-handler ``react-native link`

* **david-villegas** (1)

	
	Bastante complicado todo este contenido…

* **David Isaac Flores Medrano** (1)

	
	Ahora si me mareé … tendré que ver unas dos veces mas esta clase

	* **Melina Jacqueline onoriaga** (1)

		
		yo lo vengo viendo tres veces y trato de traducirlo a las nuevas versiones!! esta terrible jajja

* **Eliezertavarez** (1)

	
	Me lanza este error createReduxBoundAddListener is deprecated in 2.0.2. What is the recommendation to get around this problem?
	
	Puse las mismas versiones del curso y me lanza otro error diferente.

	* **Ivan Robles** (4)

		
		Yo también estaba batallando con esto leyendo la documentación de [react-navigation-redux-helpers](https://github.com/react-navigation/react-navigation-redux-helpers) y la solución ya estaba en [Actualizando Integración con Redux](https://platzi.com/clases/react-navigation/concepto/integrando-platzi-video-con-react-navigation/actualizando-la-integracion-con-redux/material/)  
		😃

* **Juan Victor Rivera Carrillo** (1)

	
	¿Que es mas viable utilizar la navegación con Redux o sin Redux?

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Creo que depende mucho del tamaño de tu aplicación, la ventaja de redux es que puedes compartir el estado de las variables entre multiples componentes, pero si tu aplicación es pequeña y es más complejo trabajar con redux entonces puedes no usarlo.

* **Christian Omar López Macías** (1)

	
	Ajustar a la versión en que se muestra en el tutorial, Leonidas posteriormente nos publicara un articulo para integrar la actualización.
	
	“dependencies”: {  
	“react”: “16.3.1”,  
	“react-native”: “0.55.4”,  
	“react-native-router-flux”: “4.0.0-beta.31”,  
	“react-native-vector-icons”: “4.6.0”,  
	“react-native-video”: “2.2.0”,  
	“react-navigation”: “2.2.0”,  
	“react-navigation-redux-helpers”: “1.1.2”,  
	“react-redux”: “^5.0.7”,  
	“redux”: “^4.0.0”,  
	“redux-persist”: “5.9.1”  
	},

* **frankromero** (0)

	
	Para los que tengan problemas al instalar react-navigation, ahora además de instalar react navigation seguir estos pasos.  
	1.Instalar react-native-gesture-handler y react-native-reanimated (es necesario hacer el link para android):  
	npm install react-native-gesture-handler react-native-reanimated
	``` 
	    2. posteriormente modificar el archivo app >java >com.(nombredetuapp) >MainActivity  debe quedar así:
	    
	```
	``` 
	    package com.nombredetuapp;
	    
	    import com.facebook.react.ReactActivity;
	    import com.facebook.react.ReactActivityDelegate;
	    import com.facebook.react.ReactRootView;
	    import com.swmansion.gesturehandler.react.RNGestureHandlerEnabledRootView;
	    
	    public classMainActivityextendsReactActivity{
	    
	        /**
	         * Returns the name of the main component registered from JavaScript.
	         * This is used to schedule rendering of the component.
	         */
	        @Override
	        protectedString getMainComponentName() {
	            return"nombredeapp";
	        }
	    
	        @Override
	        protectedReactActivityDelegate createReactActivityDelegate() {
	            returnnewReactActivityDelegate(this, getMainComponentName()) {
	                @Override
	                protectedReactRootView createRootView() {
	                    returnnewRNGestureHandlerEnabledRootView(MainActivity.this);
	                }
	            };
	        }
	    }
	    
	```
	
	y listo volver a correr react-native run-android.
	
	Espero les sirva!!

## 0160. Actualizando la integración con Redux

### Descripción:


En la clase anterior aprendiste a integrar Redux a React Navigation para la versión. 2.2.0. Porque `react-navigation-redux-helpers` aun no tenía una versión compatible con una versión superior (Estos updates ocurrieron en plena grabación del curso).

Pero aquí te traigo el update lanzado días después que es compatible con versiones de React Navigation 2.3 o superiores.

> Vamos a partir de la configuración para Redux de la clase anterior, así que te recomiendo que la tenga tal cual.

## Paso 1 - Actualizar dependencias

![Captura de pantalla 2018-06-26 a la\(s\) 7.43.11 p. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-06-26%20a%20la%28s%29%207.43.11%20p.%20m.-3198c166-7c51-4f48-8dfd-f7de520b7a93.jpg)

Pasamos a la versión 2.5.3 de React Navigation (la última hasta el momento de realizar este tutorial) aunque una versión superior no debería tener problemas

Pasamos a la versión 2.0.2 de React Navigation Redux Helpers (la última hasta el momento de realizar este tutorial) versiones superiores de ambas librerías quizá funcionen de la misma manera pero ya sabes como es el mundo de la programación, si algo se actualiza otra vez ayúdame a reportarlo desde los comentarios y haré mi mejor esfuerzo por actualizar esta guía.

## Paso 2 - Buenas noticias, ahora la configuración es más fácil

Solo debemos actualizar un par de cosas en nuestro archivo `app-navigator-with-state.js`
``` 
    import {
      reduxifyNavigator,
    } from 'react-navigation-redux-helpers';
    
```

Solo hace falta importar la función `reduxifyNavigator` de los helpers _Win #1_
``` 
    import React, { Component } from 'react';
    import { connect } from 'react-redux';
    import AppNavigator from './app-navigator';
    import {
      reduxifyNavigator,
    } from 'react-navigation-redux-helpers';
    
    const ReduxifyApp = reduxifyNavigator(AppNavigator, 'root');
    
    class AppNavigatorWithState extends ReduxifyApp {
    
    }
    
    function mapStateToProps(state) {
      return {
        state: state.navigation
      }
    }
    
    export default connect(mapStateToProps)(AppNavigatorWithState)
    
```

### Opción A - copy/paste y todo bonito.

### Opción B - te cuento que está pasando de nuevo

## Buenas noticias, hay menos código

![Captura de pantalla 2018-06-26 a la\(s\) 8.08.08 p. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-06-26%20a%20la%28s%29%208.08.08%20p.%20m.-c4643daa-a0d4-4391-a9b4-de3494c3ad57.jpg)

Ya no necesitamos ni createReduxBoundAddListener, initializeListeners ni ningún otro helper futuro [en este archivo]. **Spoiler Alert** en la clase de **Personalizando el StatusBar** importo otro helper (este tampoco hace falta si sigues esta guía)

  * El único helper útil será **reduxifyNavigator** que de hecho es nuevo
  * Con él vamos a crear un Higher Order Component que se encargará de hacer tooodo lo que hacían los otros helpers


``` 
    const ReduxifyApp = reduxifyNavigator(AppNavigator, 'root');
    
```

  * ReduxifyApp es un HOC así que podemos extenderlo fácilmente para que en el futuro podamos usar su ciclo de vida, por eso vamos a dejar esto así.


``` 
    class AppNavigatorWithState extends ReduxifyApp {
    
    }
    
```

  * Para finalizar ahora conectamos AppNavigatorWithState con el estado de redux y exportamos ese componente


``` 
    function mapStateToProps(state) {
      return {
        state: state.navigation
      }
    }
    
    export default connect(mapStateToProps)(AppNavigatorWithState)
    
```

> aquí es súper importante que el key del `mapStateToProps` que lleva nuestro router se llame `state`

Listo, nuestra app sigue en el mismo estado y puedes seguir con normalidad el resto de clases porque no tendrás que lidiar con la integración de redux nunca más (por lo menos en esta app)

![Captura de pantalla 2018-06-26 a la\(s\) 8.17.00 p. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-06-26%20a%20la%28s%29%208.17.00%20p.%20m.-d480354c-7b95-4c9a-8f2b-4baef348bf3a.jpg)

## Te veo en la próxima clase!!!

Aquí te dejo un commit con todas estas mejoras por si eres mejor leyendo código en github  
<https://github.com/LeonidasEsteban/platzi-video-react-navigation/commit/816524c55cee6298079dfa57440b3f87a7e278ef>

### Comentarios:

* **Enzo Aliatis** (6)
![meme.jpg](https://static.platzi.com/media/user_upload/meme-af986d10-27e4-4348-aa14-cedf2fff6048.jpg)

* **brunosendras** (5)

	
	Creo que debería quedar de esta forma, evitando declarar la clase:
	``` 
	    import React, { Component } from'react';
	    import { connect } from'react-redux';
	    import { reduxifyNavigator } from'react-navigation-redux-helpers';
	    
	    import AppNavigator from'./app-navigator';
	    
	    const AppNavigatorWithState = reduxifyNavigator(AppNavigator, 'root');
	    
	    const mapStateToProps = state => ({
	        state: state.navigation
	    })
	    
	    exportdefault connect(mapStateToProps)(AppNavigatorWithState);
	    
	```
	
	**Por varios motivos:**
	
	  1. Lo que devuelve reduxifyNavigator() ya ES un Componente React. Es por esto que podemos conectarlo al store directamente.
	
	  2. Ademas, React es claro en su documentación cuando explica que no hay casos de uso (salvo el de extender de Component) que ameriten usar herencia. Deberíamos Siempre intentar componer clases en lugar de heredar con “extends”.
	
	  3. El tercer motivo hace que el anterior sea aún mas evidente… y es… Para qué heredar de una clase si no vamos a extender sus propiedades ni a añadir comportamiento? Escribiendo una clase “vacía”? … En javascript subyacente esto se traduce en una función que no hace nada y se le asigna el prototype de otra.
	
	
	

	* **Luis Antonio Schmiel Paredes** (2)

		
		Me convenciste

	* **Melina Jacqueline onoriaga** (1)

		
		muy bien justificado!

* **ma_angelica_romero** (3)

	
	. Gracias. Casi me suicido con la clase anterior.

	* **Melina Jacqueline onoriaga** (1)

		
		jajaj yo tambien

* **David Ruiz** (2)

	
	reduxifyNavigator para la versión ^3.0.2 se ha removido y se reemplazó por createReduxContainer. Así que solamente toca cambiar reduxifyNavigator por createReduxContainer y funciona como está en el articulo.

* **Daniel Pereira** (1)

	
	aplicando estos cambios aparece un error "Before calling `reduxifyNavigator`, please call `createReactNavigationReducMiddleware` so that we know when to trigger your listener
	
	para solucionarlo el código completo debe quedar así
	``` 
	    import React, { Component } from 'react';
	    import { connect } from 'react-redux';
	    import AppNavigator from './app-navigator';
	    import {
	      createReactNavigationReduxMiddleware,
	      reduxifyNavigator,
	    } from 'react-navigation-redux-helpers';
	    
	    const navigationMiddleware = createReactNavigationReduxMiddleware(
	      'root',
	      state => state.navigation
	    )
	    
	    const ReduxifyApp = reduxifyNavigator(AppNavigator, 'root');
	    
	    class AppNavigatorWithState extends ReduxifyApp {
	    
	    }
	    
	    function mapStateToProps(state) {
	      return {
	        state: state.navigation
	      }
	    }
	    
	    export default connect(mapStateToProps)(AppNavigatorWithState)
	    
	```

	* **Daniel Pereira** (1)

		
		Este era el error  
		![Este era el error](https://i.imgur.com/dayXZBk.png)

	* **3dmit** (2)

		
		cambiar reduxifyNavigator por createReduxContainer
		``` 
		    import React, { Component } from 'react';
		    import { connect } from 'react-redux';
		    import AppNavigator from './app-navigator';
		    import {
		      createReactNavigationReduxMiddleware,
		      createReduxContainer,
		    } from 'react-navigation-redux-helpers';
		    
		    const navigationMiddleware = createReactNavigationReduxMiddleware(
		      'root',
		      state => state.navigation
		    )
		    
		    const ReduxifyApp = createReduxContainer(AppNavigator, 'root');
		    
		    class AppNavigatorWithState extends ReduxifyApp {
		    
		    }
		    
		    function mapStateToProps(state) {
		      return {
		        state: state.navigation
		      }
		    }
		    
		    export default connect(mapStateToProps)(AppNavigatorWithState)```
		    
		```

* **deveeup** (0)

	
	Excelente guía 😃

## 0170. Configurando la navegación de pantallas

### Descripción:


### Comentarios:

* **Oscar Estuardo de la Mora** (2)

	
	Que complicado era con la version 2.x, ahora con la 5.x es mucho mas sencillo, espero que actualizen pronto este curso, aunque pueden usar facilmente la documentacion de React Navigation para completar esta app 😃

* **Kingsman7** (2)

	
	ya lo rompi todo. actualizando hasta el Android estudio. me volví loco

* **JuanM04** (2)

	
	Para los que usaron el “nuevo método” que mencioné en la clase anterior, ahora pueden hacer simplemente lo siguiente.
	
	**NavigationOptions**
	``` 
	    // ...
	    
	    // Creamos la función para volver
	    // (El parámetro de key es opcional, lo puse por si lo necesitásemos en un futuro)
	    functionback(key = {}) {
	      _navigator.dispatch(
	        NavigationActions.back(key)
	      )
	    }
	    
	    // ...
	    
	    
	    // Exportamos 'back'
	    exportdefault {
	      // ...
	      back
	    }
	    
	```
	
	**app.js** (Con “a” minúscula)
	``` 
	    classAppLayoutextendsComponent{
	      // ...
	      // Cambiamos el header por el que ya creamos nosotros
	      static navigationOptions = ({ nav }) => {
	        return {
	          // Los paréntesis estan porque así podemos poner todo en más de una línea
	          header: (
	            <Header>
	              <Search />
	            </Header>
	          )
	        }
	      }
	      render() {
	        // BORRAMOS el if para ver si mostrar Movies o Home
	        return (
	          <Home>
	            <CategoryList/>
	            <SuggestionList/>
	          </Home>
	        )
	      }
	    }
	    
	```
	
	**movie.js**
	``` 
	    // Importamos nuestro NavigationService (reemplazar 'path' por la ruta)
	    importNavigationService from '(path)/NavigationService.js';
	    
	    // ...
	    
	    classMovieextendsComponent{
	      // Eliminamos, porque ya no sirve, el método para borrar la película seleccionada
	      // ...
	      // Cambiamos el header de igual forma que en 'app.js'
	      static navigationOptions = ({ nav }) => {
	        return {
	          header: (
	            <Header>
	              <Back
	                // Cambiamos el llamado a la función de volver antigua por la del NavigationService
	                onPress={NavigationService.back}
	              />
	            </Header>
	          )
	        }
	      }
	      render() {
	        return(
	          <Animated.View
	            style={{
	              flex: 1,
	              opacity: this.state.opacity
	            }}
	          >
	            <Layout>
	              <Player/>
	              <Details {...this.props.selectedMovie}/>
	            </Layout>
	          </Animated.View>
	        )
	      }
	    }
	    
	```
	
	**suggestion-list.js**
	``` 
	    // Importamos nuestro NavigationService (reemplazar 'path' por la ruta)
	    importNavigationService from '(path)/NavigationService.js';
	    
	    // ...
	    
	    classSuggestionListextendsComponent{
	      // ...
	      viewMovie = (item) => {
	        this.props.dispatch({
	          type: 'SET_SELECTED_MOVIE',
	          payload: {
	            movie: item
	          }
	        })
	        // Agregamos la función para ir a Movie
	        NavigationService.navigate('Movie')
	      }
	      render() {
	        // ...
	      }
	    }
	    
	```

* **Christian Omar López Macías** (2)

	
	Me estaba dando el siguiente error "TypeError: Cannot read property ‘routes’ of undefined.
	
	Tuve que reiniciar la aplicación unas 3 veces y cerrar y abrir el emulador.
	
	“react-native run-android”

	* **Leonidas Esteban Gonzalez** (3)

		
		Déjame adivinar, acrualizaste las dependencias verdad? Para esto es mejor correr el server de la con npm start —reset-cache

	* **Christian Omar López Macías** (2)

		
		Si, inicie la aplicación con las dependencias más actualizadas, luego baje la versión y después las volví a aumentar, muchas gracias por el consejo del cache.
		
		Saludos!

	* **darwin1111** (2)

		
		Tengo un error parecido! actualice las dependencias!
		
		TypeError: TypeError: undefined is not an object (evaluating state.routes)

	* **darwin1111** (3)

		
		Lo resolví, estaba enviando mal el nombre del reducer navigation al crear el middleware

* **Víctor Varas** (1)

	
	lo unico que no me funciono fue el tema del balcklist. Al recargar me vuelve a colocar en la pantalla del video, y copie el mismo código que Leonidas.
	
	import {createStore, applyMiddleware} from ‘redux’;  
	import {persistStore, persistReducer} from ‘redux-persist’;  
	import reducer from ‘./reducers/index’;  
	// import storage from ‘redux-persist/lib/storage’;  
	// import AsyncStorage from ‘@react-native-community/async-storage’;  
	// import {AsyncStorage} from ‘react-native’;  
	import storage from ‘redux-persist/lib/storage’;  
	import {createReactNavigationReduxMiddleware} from ‘react-navigation-redux-helpers’;
	
	// const store = createStore(reducer, {  
	// suggestionList: [],  
	// categoryList: [],  
	// })
	
	const persistConfig = {  
	//…  
	key: ‘root’,  
	storage,  
	blackList: [‘navigation’],  
	};
	
	const persistedReducer = persistReducer(persistConfig, reducer);  
	const navigationMiddleware = createReactNavigationReduxMiddleware(  
	‘root’,  
	state => state.navigation,  
	);
	
	const store = createStore(  
	persistedReducer,  
	applyMiddleware(navigationMiddleware),  
	);  
	const persistor = persistStore(store);
	
	export {store, persistor};

* **Alfred Manriquez Fuentes** (1)

	
	Con las versiones indicadas funciona perfect !

* **freddy0fh** (1)

	
	Tambien podemos realizar de la siguiente manera la navegación
	``` 
	    importReact, { Component } from "react";
	    import { FlatList, Text } from "react-native";
	    importEmpty from "../components/empty"
	    importVerticalSeparator from "../../sections/components/vertical-separator"
	    importLayout from "../components/suggestion-list-layout";
	    importSuggest from "../components/suggestion";
	    import { connect } from "react-redux";
	    import {withNavigation} from "react-navigation"
	    function mapStateToProps(state) {
	        return {
	            list:state.videos.suggestionList
	        };
	    }
	    classSuggestionListextendsComponent{
	        viewMovie=(item)=>{
	            this.props.dispatch({
	                type:"SET_SELECTED_MOVIE",
	                payload:{
	                    movie:item
	                }
	            })
	            this.props.navigation.navigate('Movie')
	            //this.props.dispatch(NavigationAction.navigate({routeName:"Movie"}));
	        }
	        renderEmpty = () => <Empty text="No hay ninguna sugerencias. :(" />;
	        itemSeparator = () => <VerticalSeparator />;
	        renderItem = ({ item }) => { return (<Suggest onPress={()=>{this.viewMovie(item)}} {...item} />) }
	        keyExtractor = ({ item }) => {
	            return (item ? item.id.toString() : "-1")
	        };
	        _keyExtractor = (item, index) => item ? item.id.toString() : index;
	        render() {
	            return (
	                <Layout title="Recomendado para tí..">
	                    <FlatList keyExtractor={this._keyExtractor} ItemSeparatorComponent={this.itemSeparator} ListEmptyComponent={this.renderEmpty} data={this.props.list} renderItem={this.renderItem} />
	                </Layout>
	            )
	        }
	    }
	    export default withNavigation(connect(mapStateToProps)(SuggestionList));
	    
	```

* **Manuel Calle Pérez** (1)

	
	npm start —reset-cache && react-native run-ios se queda pensando y no ejecuta “react-native run-ios” porque puede suceder esto o es normal?

	* **aragonesteban (Platzi)** (1)

		
		Hola, esto es porque ambos comandos están ejecutando `npm start` para inciar el Metro Bundle, puedes primero ejecutar `npm start —reset-cache` y luego `react-native run-ios` para que te abra el emulador de iOS con la aplicación.

* **Manuel Calle Pérez** (1)
npm start —reset-cache && react-native run-ios se queda pensando y no ejecuta “react-native run-ios” porque puede suceder esto o ...

	* **aragonesteban (Platzi)** (1)

		
		Hola, esto es porque ambos comandos están ejecutando `npm start` para inciar el Metro Bundle, puedes primero ejecutar `npm start —reset-cache` y luego `react-native run-ios` para que te abra el emulador de iOS con la aplicación.

## 0180. Creando una nueva pantalla para categorías

### Descripción:


### Comentarios:

* **AndresArdilaB** (5)

	
	En la ultima version de react navigation las opciones se envían con **defaultNavigationOptions** en lugar de **NavigationOptions**

	* **Luis Manuel  Sanchez Torres** (1)

		
		justamente estaba batallando porque no me funcionaba el header y era por eso. gracias

* **Carlos Alberto Petit Quintero** (2)

	
	esta clase estuvo muy enredada, a veces leonidas cambia mucho de pantallas y con tranquilidad se pierde el hilo de lo que se esta haciendo, podría reducir la velocidad al hablar, ayudaría mucho a entender algunos conceptos, no es hacer un curso corto, es hacer un curso bueno.!

	* **Miguel Cobas** (3)

		
		Recuerda que tienes la opción de repetir el video las veces que quieras, o puedes aprovechar los marcadores para ponerlos donde tengas dudas y volver a repasar solamente eso

* **Matias Niz** (2)

	
	Hice lo del header antes de llegar a este video, y me di cuenta que nos quita el boton de back. Porque esta “pisando” el header completamente.
	
	Asi que opte por personalizar el header en cada uno de los screen, agregandole el back button como un children de <Header>
	
	Pimero importo:
	``` 
	    import { HeaderBackButton } from'react-navigation'
	    
	```
	
	Y en el static navigationOption:
	``` 
	    static navigationOptions = ({navigation}) => {
	        return {
	          header: <Header>
	                    <HeaderBackButtononPress={() => navigation.goBack(null)} />
	                  </Header>
	        }
	      }
	    
	```
	
	No logre incluir el HeaderBackButton en el archivo de app-navigator.js. Hay alguna manera de hacerlo para no tener que estar personalizando el header en todos los archivos?

	* **Miguel Cobas** (1)

		
		Intentaste usando este parametro **defaultNavigationOptions** ?

* **Wilson Marino Pablo Mendez** (1)

	
	Dejar el **Header** sin ninguna opción de **regresar,** mala experiencia de usuario

* **Melina Jacqueline onoriaga** (1)

	
	En mi caso cree la navegación con createSwitchNavigator y este no usa el header por defecto de react navigation, así que podes usar uno personalizado… entonces lo pones los botones, iconos y títulos que quieras, no hace falta que re-configures nada…

* **inquiridor** (1)

	
	¿Por qué no puedo ver este video en el Servidor C?

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Lo estoy viendo en este momento y lo veo de manera correcta.

	* **inquiridor** (1)

		
		Emm sí, pero la pregunta fue antes de que lo arreglaran jeje

* **David Isaac Flores Medrano** (1)

	
	¿Porque me marca este error?  
	![](![Captura de pantalla 2018-08-30 a la\(s\) 10.34.06.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-08-30%20a%20la%28s%29%2010.34.06-b8582fbc-edaa-403c-9f0c-64d607234206.jpg)
	
	Pero si elimino esta parte del …/videos/components/suggestion funciona …  
	![](![Captura de pantalla 2018-08-30 a la\(s\) 10.34.24.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202018-08-30%20a%20la%28s%29%2010.34.24-2fa35ad8-3dda-4879-bf8a-79cd7855b099.jpg)

	* **Diego Alexander Forero Higuera (Platzi)** (4)

		
		Es probable que una de las películas que esta llegando no tenga genres y es por eso que se rompe, debes validar si tiene o no genres, si existe entonces si traer el primero si no entonces poner un valor por defecto.

	* **David Isaac Flores Medrano** (1)

		
		Entiendo… ya lo probaré… gracias!!

	* **Ivan Robles** (1)

		
		Tienes que dejar un dato por default en caso de que el genero de la película (genres) no exista (el cual a veces sucede).
		
		Puedes usar la validación con el operador ternario ( ?: ) para evaluar si existe la data o setear tus [defaultProps](https://reactjs.org/docs/react-without-es6.html#declaring-default-props).

	* **Nacho Ávila** (1)

		
		Puedes simplemente comprobar si hay generos. Si no los hay pones ‘Categoría’ o null.
		``` 
		    item.genres ? item.genres[0] : 'Categoria'
		    
		```

* **Matias Niz** (1)
Hice lo del header antes de llegar a este video, y me di cuenta que nos quita el boton de back. Porque esta “pisando” el header completa...

* **inquiridor** (1)
¿Por qué no puedo ver este video en el Servidor C?

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Lo estoy viendo en este momento y lo veo de manera correcta.

* **David Isaac Flores Medrano** (1)
¿Porque me marca este error? ![]( Pero si elimino esta parte del …/videos/components/suggestion funciona … ![](

	* **Diego Alexander Forero Higuera (Platzi)** (4)

		
		Es probable que una de las películas que esta llegando no tenga genres y es por eso que se rompe, debes validar si tiene o no genres, si existe entonces si traer el primero si no entonces poner un valor por defecto.

* **Javier Rodríguez Ruiz** (0)

	
	Podrían destacar lo desactualizado de la versión. Ahorrariamos tiempo.

## 0190. Tab Navigator

### Descripción:


### Comentarios:

* **Christian Omar López Macías** (9)

	
	createBottomTabNavigator(routeConfig, bottomTabNavigatorConfig)
	
	Configuración del bottomTabNavigatorConfig
	
	  * tabBarComponent
	  * tabBarPosition - top | bottom
	  * swipeEnabled
	  * animationsEnabled
	  * lazy
	  * removeClippedSubviews
	  * initialLayout
	  * tabBarOptions
	  * activeTintColor
	  * activeBackgroundColor
	  * inactiveTintColor
	  * inactiveBackgroundColor
	  * showLabel
	  * style
	  * labelStyle
	  * allowFontScaling
	
	
	
	navigationOptions en Tab Navigator
	
	  * Title
	  * tabBarIcon
	  * tabBarColor
	  * tabBarLavel
	  * tabBarAccessibilityLabel
	  * tabBarTestID
	  * tabBarOnPress
	
	

## 0200. Personalizando Tab Navigator

### Descripción:


### Comentarios:

* **Wilson Marino Pablo Mendez** (1)

	
	En mi caso use **react-native-vector-icons**

* **jenapi** (1)

	
	Si a alguien que esté usando Las versiones actuales le sirve esto, Hice todo tal cual dicen en esta clase y también me guié de los docs, pero nada funcionaba. De todas las formas que dicen en la documentación mi app dejaba o de verse o no podía acceder a las screens de mi stack navigator. Lo que hice fue quitar el persistGate y todo lo que tuviese que ver con la persistencia de datos, luego de eso funcionó. Dejo aca abajo mi codigo de store.js
	``` 
	    import { createStore, /*applyMiddleware */} from 'redux';
	    // import { persistStore, persistReducer } from 'redux-persist';
	    // import { AsyncStorage } from 'react-native';
	    // import { createReactNavigationReduxMiddleware } from 'react-navigation-redux-helpers';
	    
	    import Reducer from './reducers/index';
	    
	    // const persistConfig = {
	    // 	key: 'root',
	    // 	storage: AsyncStorage,
	    // 	blackList: ['selectedMovie', 'navigation'],
	    // };
	    
	    // const AppReducer = persistReducer(persistConfig, Reducer);
	    
	    // const middleware = createReactNavigationReduxMiddleware(
	    // 	(state) => state.navigation,
	    // );
	    
	    const store = createStore(Reducer);
	    // const persistor = persistStore(store);
	    
	    // const AppStore = { store, persistor };
	    
	    exportdefault store;
	    
	```

* **José Daniel Gómez Larin** (1)

	
	Si estas utilizando las ultimas versiones debes importar createBottomTabNavigator de react-navigation-tabs, aquí te dejo la documentación para que te puedas guiar mejor. <https://reactnavigation.org/docs/en/bottom-tab-navigator.html>

	* **Hugo Sebastian Martínez Hernández** (1)

		
		Buenísimo aporte!!

	* **jenapi** (1)

		
		Puedes compartir tu código? es que Me lanza un error que dice
		``` 
		    TypeError: No "routes" found in navigation state
		    
		```

* **Jose Balcazar** (1)

	
	La carpeta src no esta en los recursos, como obtengo los archivos, about, lucky, profile?

	* **Jose Balcazar** (1)

		
		en los recursos de este capitulo no estan los archivos que indican leonidas, pero si los puedes conseguir en el github de leonidas  
		<https://github.com/LeonidasEsteban/platzi-video-react-navigation/tree/master/src/screens/containers>

* **rulobars** (1)

	
	¡Hola! A ustedes no les marcó algún error después de exportar el TagNavigator ?
	
	A mi me sale esto:
	
	TypeError: undefined is not an object (evaluating ‘routes.forEach’)
	
	This error is located at:  
	in Navigator (at createKeyboardAwareNavigator.js:11)  
	in KeyboardAwareNavigator (at createNavigationContainer.js:393)  
	in NavigationContainer (at SceneView.js:10)  
	in SceneView (at createTabNavigator.js:10)  
	in RCTView (at View.js:60)  
	in View (at ResourceSavingScene.js:14)  
	in RCTView (at View.js:60)  
	in View (at ResourceSavingScene.js:10)  
	in ResourceSavingScene (at createBottomTabNavigator.js:86)  
	in RCTView (at View.js:60)  
	in View (at createBottomTabNavigator.js:77)  
	in RCTView (at View.js:60)  
	in View (at createBottomTabNavigator.js:76)  
	in TabNavigationView (at createTabNavigator.js:127)  
	in NavigationView (at createNavigator.js:123)  
	in Navigator (at createNavigationContainer.js:393)  
	in NavigationContainer (at app-navigator-with-state.js:24)  
	in AppNavigatorWithState (created by Connect(AppNavigatorWithState))  
	in Connect(AppNavigatorWithState) (at App.js:29)  
	in PersistGate (at App.js:25)  
	in Provider (at App.js:22)  
	in App (at renderApplication.js:33)  
	in RCTView (at View.js:60)  
	in View (at AppContainer.js:102)  
	in RCTView (at View.js:60)  
	in View (at AppContainer.js:122)  
	in AppContainer (at renderApplication.js:32)  
	getDerivedStateFromProps

	* **Miguel Cobas** (1)

		
		Puedes agregar tu código para ver por que el error? o ya lo solucionaste?

	* **Miguel Cobas** (1)

		
		Yo acabo de terminar el video y lo pude importar perfecto, si puedes pasa me como lo estas importando para ver el error ojala pueda ayudarte 😄

* **Julio Vargas Bautista** (1)

	
	Hola, hay alguna forma de conservar el header con el tabNavigator?

	* **Miguel Cobas** (1)

		
		Si lo tienes que agregar de la siguiente forma
		``` 
		    StackNavigator({
		       MyTab: {
		         screen: TabNavigator({ }),
		         navigationOptions: { title: 'Header title' }
		      }
		    })
		    
		```

* **Manuel Calle Pérez** (1)

	
	¿Como se pueden agregar los iconos emogy desde sublime? gracias

	* **Miguel Cobas** (1)

		
		Instala el siguiente paquete [Emoji Packages](https://packagecontrol.io/packages/Emoji) con eso los podrás usar en Sublime

* **Jose Balcazar** (1)
La carpeta src no esta en los recursos, como obtengo los archivos, about, lucky, profile?

	* **Jose Balcazar** (1)

		
		en los recursos de este capitulo no estan los archivos que indican leonidas, pero si los puedes conseguir en el github de leonidas  
		<https://github.com/LeonidasEsteban/platzi-video-react-navigation/tree/master/src/screens/containers>

* **WilliamVelazquez** (0)

	
	@LeonidasEsteban ¿Hay forma de agregar un gesto que al deslizar a la derecha o izquierda cambie entre los diferentes tabs?
	
	Gracias de antemano.
	
	Saludos! 😃

	* **deveeup** (1)

		
		DrawerNavigator… [acá](https://reactnavigation.org/docs/en/drawer-navigator.html)

	* **WilliamVelazquez** (0)

		
		Ese es otro navigator, ¿no? 👀  
		Lo que decía yo era dentro del mismo Tab Navigator como intercambiar entre tabs con algún gesto (desilzando a izquierda o derecha).

	* **deveeup** (1)

		
		Si, es cómo crear otro stack con screens… Lo que tu dices es cómo agregar un gesto similar al del histories de facebook, el cuál se activa deslizando a la derecha?

	* **WilliamVelazquez** (1)

		
		Justo así agregando el gesto, o como en instagram que navegas diferente deslizando a la izquierda o derecha!

	* **Miguel Cobas** (2)

		
		en la parte de tabNavigatorConfig tienes que agregar swipeEnabled y eso permitira moverte entre tabs haciendo swipe

	* **WilliamVelazquez** (1)

		
		Gracias Mike, revisaré y te comento si me funciona!  
		Un saludo! 😃

* **WilliamVelazquez** (0)
@LeonidasEsteban ¿Hay forma de agregar un gesto que al deslizar a la derecha o izquierda cambie entre los diferentes tabs? Gracias de ant...

	* **deveeup** (1)

		
		DrawerNavigator… [acá](https://reactnavigation.org/docs/en/drawer-navigator.html)

## 0210. Personalizando el Status Bar

### Descripción:


 _DISCLAIRMER_  
Si actualizaste react-navigation y react-navigation-redux-helpers no hace falta hacer ninguna configuración extra con createDidUpdateCallback, si es tu caso solo omite esa parte ????

### Comentarios:

* **Christian Omar López Macías** (8)

	
	Con la nueva versión va a marcar error en la función "createDidUpdateCallback que usan en app-navigator-with-state.js.
	
	Usando el reduxifyNavigator ya no es necesario hacer nada en esta parte.

* **José Daniel Gómez Larin** (2)

	
	Si estas utilizando createReduxContainer (esto se utiliza en las ultimas versiones) ya no es necesario configurar el createDidUpdateCallback.

* **WilliamVelazquez** (2)

	
	Me parece que para mejorar aún la parte de la Status Bar, se debería agregar la parte del
	``` 
	    componentDidMoun
	    
	```
	
	y la parte del
	``` 
	    componentWillUnmount
	    
	```
	
	dentro de las screens de movie y de category, ya que al cambiar de About y en el Main dejamos abierta alguna otra screen no se realiza el montado del componente Home y por tanto no se cambia la configuración de la Status Bar.
	
	Sin embargo en ocasiones me marca un error al usar el back en la pantalla de **Movie** (me marca como **indefinido** a **this.focus** , ¿tendría que inicializarse en otro lado?), por otra parte al agregarlo en ocasiones no me funciona (sólo tengo el problema en estas dos pantallas debido a que están dentro de **Main** )
	
	¿Cuál es la forma correcta de solucionar el asunto?
	
	Saludos! 😃

	* **Miguel Cobas** (1)

		
		Creo que podrías agregar el componentDidMount en esas dos screens o en su caso, hacer una función que si no esta onFocus se cierre

* **Víctor Varas** (1)

	
	Sólo me respeta las configuraciones del SatusBar que defino en Home. Los demás StatusBar no los puedo configurar de manera independiente:
	
	about.js
	
	import React, {Component} from ‘react’;  
	import {View, Text, StyleSheet, Image, StatusBar} from ‘react-native’;  
	import Icon from ‘…/…/sections/components/icon’;
	
	class About extends Component {  
	static navigationOptions = () => {  
	return {  
	title: ‘Acerca de’,  
	tabBarIcon: <Icon icon=“😁” />,  
	};  
	};
	
	componentDidMount() {  
	this.focus = this.props.navigation.addListener(‘didFocus’, () => {  
	StatusBar.setBarStyle(‘dark-content’);  
	StatusBar.setBackgroundColor(‘pink’);  
	});  
	}
	
	componentWillUnmount() {  
	this.focus.remove();  
	}
	
	render() {  
	return (  
	<View style={styles.container}>  
	<Image  
	source={{  
	uri:  
	‘<https://static.platzi.com/media/achievements/badge-reactnative-9c23a814-e9c3-4041-afbd-ff8083fbf32f.png>’,  
	}}  
	style={styles.logo}  
	/>  
	<Text style={styles.text}>  
	Platzi Video es construido como una aplicaciÃ³n educativa para  
	enseÃ±ar React Native y React Navigation  
	</Text>  
	<Text style={styles.text}>@LeonidasEsteban</Text>  
	<Text style={styles.text}>2019</Text>  
	</View>  
	);  
	}  
	}
	
	const styles = StyleSheet.create({  
	container: {  
	flex: 1,  
	padding: 10,  
	justifyContent: ‘center’,  
	alignItems: ‘center’,  
	backgroundColor: ‘#022c43’,  
	},  
	text: {  
	textAlign: ‘center’,  
	marginBottom: 5,  
	color: ‘white’,  
	},  
	logo: {  
	width: 80,  
	height: 80,  
	marginBottom: 20,  
	},  
	});
	
	export default About;

	* **Víctor Varas** (1)

		
		Ya me funciono mi problema era: que en el app-navigator-with-state.js, había escrito mal el didUpdate:
		
		Tenía:  
		return didUpdate;
		
		Cambio:  
		return didUpdate();

* **Manuel Rivera** (1)

	
	Sería aun mas genial si actualizaran el curso junto con el de react Native  
	😕

* **Matias Andres Morales** (1)

	
	Alguien soluciono este problema con la nueva version de React-Navigation? no puedo solucionarlo

	* **aragonesteban (Platzi)** (2)

		
		Hola Matias, ¿Qué problema tienes con la nueva versión?

	* **Matias Andres Morales** (1)

		
		Hola Esteban , sigo la documentacion de React Navigation y persiste el Status Bar al que lo agregue como un componente y olvida al otro. Te dejo mi codigo

	* **Matias Andres Morales** (1)

		
		import React, { Component, Fragment } from ‘react’;  
		import { StatusBar } from 'react-native’  
		import { connect } from ‘react-redux’;
		
		import Header from '…/…/sections/components/Header’  
		import SuggestionList from '…/…/videos/container/SuggestionList’  
		import CategoryList from ‘…/…/videos/container/CategoryList’;  
		import API from ‘…/…/…/utils/Api’;  
		import Movie from ‘…/…/screens/container/Movie’;  
		import Search from ‘…/…/sections/container/Search’;
		
		class Home extends Component {  
		static navigationOptions = () => {  
		return {  
		header: Header,  
		}  
		}
		
		async componentDidMount() {  
		this.navListener = this.props.navigation.addListener(‘didFocus’, () => {  
		StatusBar.setBarStyle(‘dark-content’);  
		});
		``` 
		    const categoryList = await API.getMovies();
		    console.log(categoryList);
		    this.props.dispatch({
		      type: 'SET_CATEGORIES_LIST',
		      payload: {
		        categoryList
		      }
		    })
		    
		    const suggestionList = await API.getSuggestion(10);
		    console.log(suggestionList)
		    this.props.dispatch({
		      type: 'SET_SUGGESTION_LIST',
		      payload: {
		        suggestionList
		      }
		    })
		    
		```
		
		}
		
		componentWillUnmount() {  
		this.navListener.remove();  
		}
		
		render() {  
		return (  
		<Fragment>  
		<StatusBar barStyle=“dark-content” />  
		<Search />  
		<CategoryList />  
		<SuggestionList />  
		</Fragment>  
		)  
		}  
		}
		
		export default connect(null)(Home);
		
		Esa es la Home , la vista principal , la que tiene que tener un statusbar negro

	* **Matias Andres Morales** (1)

		
		import React, { Component } from ‘react’;  
		import {  
		View,  
		Text,  
		StyleSheet,  
		Image,  
		StatusBar  
		} from ‘react-native’;
		
		class About extends Component {  
		componentDidMount() {  
		this.navListener = this.props.navigation.addListener(‘didFocus’, () => {  
		StatusBar.setBarStyle(‘light-content’);  
		});  
		}
		
		componentWillUnmount() {  
		this.navListener.remove();  
		}
		
		render() {  
		return (  
		<View style={styles.container}>  
		<Image  
		source={{uri: ‘<https://static.platzi.com/media/achievements/badge-reactnative-9c23a814-e9c3-4041-afbd-ff8083fbf32f.png>’}}  
		style={styles.logo}  
		/>  
		<Text style={styles.text}>Esta App fue realizada por Matias Morales</Text>  
		<Text style={styles.text}>@matiasmorales.11</Text>  
		<Text style={styles.text}>2019</Text>  
		</View>  
		)  
		}  
		}
		
		const styles = StyleSheet.create({  
		container: {  
		flex: 1,  
		padding: 10,  
		justifyContent: ‘center’,  
		alignItems: ‘center’,  
		backgroundColor: ‘#022c43’,  
		},  
		text: {  
		textAlign: ‘center’,  
		marginBottom: 5,  
		color: ‘white’,  
		},  
		logo: {  
		width: 80,  
		height: 80,  
		marginBottom: 20,  
		}  
		})
		
		export default About
		
		y en el about , tiene que estar el StatusBar blanco , pero cuando reenderizo la app aparece el StatusBar negro

* **Favio Náquira** (1)

	
	¿Y qué opinas de usar react-native log-android en vez del debugger-ui que utilizas? ¿Cuál es la diferencia?

	* **alesanabriav** (2)

		
		react-native log-android para hacer debug de código nativo ejemplo Log.e(“MainActivity”, “err”) y debugger-ui código de javascript consolel.log(“Hola react”)

* **Judiel Reyes** (1)

	
	Ya con el helper de reduxifyNavigator que esta en react-navigation-redux-helpers se escuchan todos los eventos cuando se lanzan la primera vez

* **Christian Omar López Macías** (1)

	
	He intentado cambiar el statusBar del screen de Login pero no me ha dejado, no se si el código para la validación del screen esté interfiriendo en el scope.
	
	if(this.props.user) {  
	this.props.navigation.navigate(‘App’);  
	} else {  
	this.props.navigation.navigate(‘Login’);  
	}
	
	Saludos!

	* **Miguel Cobas** (1)

		
		Crees que puedas poner tu código completo?

* **Favio Náquira** (1)
¿Y qué opinas de usar react-native log-android en vez del debugger-ui que utilizas? ¿Cuál es la diferencia?

	* **alesanabriav** (2)

		
		react-native log-android para hacer debug de código nativo ejemplo Log.e(“MainActivity”, “err”) y debugger-ui código de javascript consolel.log(“Hola react”)

* **WilliamVelazquez** (0)

	
	@LeonidasEsteban ¿Cómo debería afrontar ese detallito?

* **WilliamVelazquez** (0)
@LeonidasEsteban ¿Cómo debería afrontar ese detallito?

## 0220. Switch Navigator

### Descripción:


### Comentarios:

* **Christian Omar López Macías** (10)

	
	El link para el login.
	
	<https://github.com/LeonidasEsteban/platzi-video-react-navigation/blob/master/src/screens/containers/login.js>

	* **darwin1111** (1)

		
		Gracias

* **Miguel Angel Monje Allende** (3)

	
	Este es el Login
	``` 
	    import React, { Component } from 'react';
	    import {
	      View,
	      Text,
	      TextInput,
	      Button,
	      StyleSheet,
	      SafeAreaView,
	      Image,
	      TouchableOpacity
	    } from 'react-native';
	    import { connect } from 'react-redux';
	    
	    class Login extends Component {
	      handleLogin = () => {
	        const token = 'ABCDEFGHIJK';
	        this.props.dispatch({
	          type: 'SET_USER',
	          payload: {
	            token,
	            username: 'LeonidasEsteban'
	          }
	        })
	        this.props.navigation.navigate('Loading');
	      }
	      render() {
	        return (
	          <SafeAreaViewstyle={styles.container}>
	            <View>
	              <Image
	                source={require('../../../assets/logo.png')}
	                style={styles.logo}
	              />
	              <TextInput
	                style={styles.input}
	                placeholder="Nombre de usuario"
	                placeholderTextColor="white"
	              />
	              <TextInput
	                style={styles.input}
	                placeholder="Contraseña"
	                placeholderTextColor="white"
	                secureTextEntry={true}
	              />
	              <TouchableOpacity
	                onPress={this.handleLogin}
	                style={styles.button}
	              >
	                <Textstyle={styles.buttonLabel}>Iniciar Sesión</Text>
	              </TouchableOpacity>
	            </View>
	          </SafeAreaView>
	        )
	      }
	    }
	    
	    const styles = StyleSheet.create({
	      container: {
	        flex: 1,
	        alignItems: 'center',
	        justifyContent: 'center',
	        backgroundColor: 'white',
	      },
	      logo: {
	        width: 200,
	        height: 80,
	        resizeMode: 'contain',
	        marginBottom: 10,
	      },
	      input: {
	        marginBottom: 10,
	        width: 250,
	        height: 50,
	        paddingHorizontal: 10,
	        borderRadius: 5,
	        backgroundColor: '#838383',
	        color: 'white',
	      },
	      button: {
	        backgroundColor: '#99c84a',
	        borderRadius: 5,
	      },
	      buttonLabel: {
	        color: 'white',
	        padding: 10,
	        fontSize: 18,
	        fontWeight: 'bold',
	        textAlign: 'center'
	      }
	    })
	    
	    exportdefault connect(null)(Login)
	    
	```

	* **Carlos Alberto Petit Quintero** (1)

		
		Tienes un pequeño error de sintaxis 🧐

	* **Karl Heitmann** (1)

		
		Gracias, muy amable.

* **elias.dominguezpires** (2)

	
	Abrir sesión con Facebook ??? Eso seria bueno

## 0230. Login con Switch Navigator

### Descripción:


### Comentarios:

* **Melina Jacqueline onoriaga** (2)

	
	con jwt la mejor opción! 😄

* **Karl Heitmann** (1)

	
	Muestra como consumir el dato de username desde el estado proporcionado por redux.

## 0240. Añadiendo la pantalla Movie a un modal

### Descripción:


### Comentarios:

* **Javier Cestau** (4)

	
	Según la documentación **mode: ‘modal’** es solo para IOS, en android no funciona

* **WilliamVelazquez** (2)

	
	@LeonidasEsteban al realizar el ejercicio me percaté de que al poner en **headerMode** en **none** no afecta solamente a la Screen de **home** si no también a la de **movie** y por ende **se pierde el header** personalizado que teníamos con el botón para cerrar (sé que de igual forma funciona la navegación con los gestos pero me parece que no era la idea).
	
	Para cambiar dicho funcionamiento lo que realicé fue en el archivo **app-navigator** cambiar algunas cosas al **StackNavigator Main** le **agregué** nuevamente la Screen de **Movie** y **quité** la de** Category**, la cual coloqué dentro del **StackNavigator WithModal** donde **quité** la Screen de **Movie**.
	
	Después de lo anterior cambie **WithModal** el modo que definimos como **modal por card** y dentro de **Main agregué el modo modal** (de igual forma **activé los gestos** ).
	
	Adjunto como quedaría ambos **StackNavigators** por si a alguien le sirve 😃
	``` 
	    const Main = createStackNavigator(
	      {
	        Home,
	        Movie,
	      },
	      {
	        navigationOptions: {
	          header: Header,
	          gesturesEnabled: true
	        },
	        mode: 'modal',
	        cardStyle: {
	          backgroundColor: 'white'
	        }
	      }
	    );
	    
	```
	``` 
	    const WithModal = createStackNavigator(
	      {
	        Main: {
	          screen: TabNavigator
	        },
	        Category
	      },
	      {
	        mode: 'card',
	        headerMode: 'none',
	        cardStyle: {
	          backgroundColor: 'white'
	        },
	        navigationOptions: {
	          gesturesEnabled: true
	        }
	      }
	    );
	    
	```

	* **WilliamVelazquez** (1)

		
		Cabe señalar que con el cambio anterior ahora la Screen de **Category** se queda **sin** el **header** , por lo que me parece que para devolvérselo deberíamos agregar otro StackNavigator. 😮

	* **WilliamVelazquez** (1)

		
		Ahora que avancé más el curso al agregar el **DrawerNavigator** al funcionar al realizar el gesto de izquierda a derecha de acuerdo a lo que mencioné antes dejaría la screen **Category** junto con **Movie** en **Main** ya que de lo contrario nos quedaríamos sin la navegación por el gesto dentro de ese screen ya que esta en modo card y se empalmaría con el **DrawerNavigator** (a menos que se ocupe desde derecha a izquierda).

	* **gmocmm** (1)

		
		Con tu cambio también, hace que el home pase a ser modal. Creo que en este caso el componente Video al ser un “modal” lo más recomendable seria poner el componente Header dentro de los elementos que renderizará, asi mantener la opcion “none” en el “headerMode”.

	* **WilliamVelazquez** (1)

		
		@guillermocamarenamiramontes Como dices me dí cuenta después y agregué que se debía hacer como respuesta 😉

## 0250. Añadiendo un Drawer Navigator

### Descripción:


### Comentarios:

* **juand_silva** (6)

	
	No me estaba funcionando el los gestos en el dispositivo de Android con React-navigatio 3.X y aquí está la solución. Por si alguien le pasa lo mismo:  
	<https://stackoverflow.com/questions/53394982/react-navigation-swipe-on-drawer-does-not-work-in-android>

	* **Danvasem** (1)

		
		Perfecto, justo estaba sufriendo porque no me funcionaban los gestos. Excelente aporte!.

	* **Melina Jacqueline onoriaga** (2)

		
		Muchas gracias por el aporte!

* **diego1827** (2)

	
	Leonidas buenas tardes, he seguido tus cursos y te agradezco por ser un gran educador pero tengo un problema y quisiera que me ayudaras, estoy desarrollando una ecommerce y quiero agregar en mi drawer una sección de MIS COMPRAS donde podré ver todos los artículos que he agregado a mi carrito, el problema surge cuando quiero hacer algo parecido a lo que hace hotmail o gmail, que tienen un icono, el nombre y un numero que va cambiando dinamicamente según la cantidad de correos que tenga, quiero hacer algo parecido que el numero vaya cambiando según la cantidad de productos añadidos, agradecería tu asesoría

	* **Miguel Cobas** (1)

		
		Hola, has intentado usar la persistencia de datos, con una función sumerle a tu dato local. Asi tu contador en el carrito puede ir sumando cada touch que le den

* **José Daniel Gómez Larin** (1)

	
	Si estas utilizando las ultimas versiones, debes utilizar createDrawerNavigator de react-navigation-drawer, miralo aquí <https://reactnavigation.org/docs/en/drawer-navigator.html>

## 0260. Personalizando un Drawer Component

### Descripción:


### Comentarios:

* **Christian Omar López Macías** (3)

	
	¿Como podemos hacer para que el drawerNavigator se accione también con un icono? como el que se usa habitualmente el de hamburguesa

	* **Leonidas Esteban Gonzalez** (10)

		
		te doy varias opciones
		``` 
		    this.props.navigation.openDrawer();
		    this.props.navigation.closeDrawer();
		    
		```
		``` 
		    this.props.navigation.toggleDrawer();
		    
		```
		
		o importando DrawerActions
		``` 
		    this.props.navigation.dispatch(DrawerActions.openDrawer());
		    this.props.navigation.dispatch(DrawerActions.closeDrawer());
		    this.props.navigation.dispatch(DrawerActions.toggleDrawer());
		    
		```

	* **Christian Omar López Macías** (1)

		
		Me funciono perfecto @LeonidasEsteban, gracias!

* **Yeraldine Martinez** (2)
Quiero saber si el drawer esta abierto o cerrado, como puedo acceder a ese valor si tengo React Navigation con Redux?

	* **ferontv_** (2)

		
		Creo que se puede manejar como un boolean tomando en cuenta que por defecto el drawer está en false y manejarlo como un estado cualquiera en redux. Se cambiaría a true (o false) en el caso que se accione:
		
		this.props.navigation.openDrawer();  
		this.props.navigation.closeDrawer();
		
		ó
		
		this.props.navigation.toggleDrawer();

* **Sebastian Wilde Alarcón Arenas** (1)

	
	Para la versión 4.0.10
	``` 
	    import { DrawerItems } from'react-navigation-drawer';
	    
	```

* **Alimoralesmio** (1)

	
	El DrawerNavigator presenta un ligero Lag al momento de realizar el gesto para abrir, a que se debe esto ?

* **Damian Perez** (1)

	
	por si alguien necesita como yo ocultar un elemento del Drawer:
	``` 
	    navigationOptions: {
	            drawerLabel: () =>null
	    }```
	    
	```

* **Yeraldine Martinez** (1)

	
	Quiero saber si el drawer esta abierto o cerrado, como puedo acceder a ese valor si tengo React Navigation con Redux?

	* **ferontv_** (2)

		
		Creo que se puede manejar como un boolean tomando en cuenta que por defecto el drawer está en false y manejarlo como un estado cualquiera en redux. Se cambiaría a true (o false) en el caso que se accione:
		
		this.props.navigation.openDrawer();  
		this.props.navigation.closeDrawer();
		
		ó
		
		this.props.navigation.toggleDrawer();

* **Alejandro Ortegano** (0)

	
	Como podemos realizar la implementavion de un TabNavigator y un DrawerNavigator?

	* **Miguel Cobas** (1)

		
		en el drawer debes de contener el TabNavigation
		``` 
		     {
		            Main: {
		                screen: TabNavigation, <----- aqui iria tu tab
		                navigationOptions:{
		                    title:'Inicio',
		                    drawerIcon: <Icon name="home" size={16} />, 
		                }
		            },
		            Sobre: {
		                screen: About
		            },
		            Suerte:{
		                screen: Lucky
		            }   
		        },```
		    
		    
		    
		```

* **Christian Omar López Macías** (0)
¿Como podemos hacer para que el drawerNavigator se accione también con un icono? como el que se usa habitualmente el de hamburguesa

	* **Leonidas Esteban Gonzalez** (10)

		
		te doy varias opciones
		``` 
		    this.props.navigation.openDrawer();
		    this.props.navigation.closeDrawer();
		    
		```
		``` 
		    this.props.navigation.toggleDrawer();
		    
		```
		
		o importando DrawerActions
		``` 
		    this.props.navigation.dispatch(DrawerActions.openDrawer());
		    this.props.navigation.dispatch(DrawerActions.closeDrawer());
		    this.props.navigation.dispatch(DrawerActions.toggleDrawer());
		    
		```

## 0270. Back button en Android

### Descripción:


### Comentarios:

* **Matias Sebastian Perez** (5)

	
	Para aquellos que utilizan reduxifyNavigator y no tienen la clase creada de appNavigationWithState, sino que la resiven del reduxifyNavigator… tienen que hacer esta clase de esta forma. Extendiendo de eso que resiven del reduxify y agregando el listener en esta nueva clase
	``` 
	    import React, {Component} from'react-native';
	    import { BackHandler } from'react-native';
	    import { connect } from'react-redux';
	    import AppNavigator from'./app-navigation';
	    import {
	      reduxifyNavigator,
	    } from'react-navigation-redux-helpers';
	    import { NavigationActions } from'react-navigation';
	    
	    const AppNavigatorWithState = reduxifyNavigator(AppNavigator, 'root');
	    
	    classAppNavigatorWithStateWithBackButtonextendsAppNavigatorWithState{
	      onBackPress = () => {
	        this.props.dispatch(NavigationActions.back({
	          key: null
	        }));
	    
	        returntrue//Tengo que poner esto para que se termine de mandar el evento
	      }
	    
	      componentDidMount(){
	        BackHandler.addEventListener('hardwareBackPress', this.onBackPress)
	      }
	      componentWillUnMount(){
	        BackHandler.removeEventListener('hardwareBackPress', this.onBackPress)
	      }
	    }
	    
	    const mapStateToProps = (state) => {
	      return {
	        state: state.navigationReducer
	      }
	    }
	    
	    exportdefault connect(mapStateToProps)(AppNavigatorWithStateWithBackButton);
	    
	```

	* **Wilson Marino Pablo Mendez** (1)

		
		En la nueva version en lugar de **reduxifyNavigator** se pone **createReduxContainer**

* **Sebastian Wilde Alarcón Arenas** (2)

	
	Para los que usen ReduxContainer
	``` 
	    import { 
	        createReduxContainer
	     } from 'react-navigation-redux-helpers';
	    import { connect } from 'react-redux';
	    import AppNavigator from './app-navigator';
	    import { BackHandler } from "react-native";
	    import { NavigationActions } from "react-navigation";
	    
	    class AppNavigatorWithState extends createReduxContainer(AppNavigator, 'root') {
	      componentDidMount() {
	        super.componentDidMount && super.componentDidMount();
	        BackHandler.addEventListener('hardwareBackPress', this.onBackButtonPressAndroid);
	    }
	    
	    componentWillUnmount() {
	        BackHandler.removeEventListener('hardwareBackPress', this.onBackButtonPressAndroid);
	        super.componentWillUnmount && super.componentWillUnmount();
	    }
	    
	    onBackButtonPressAndroid = () => {
	        const { dispatch } = this.props;
	        const { state } = this.getCurrentNavigation();
	        // ... do something with state
	        dispatch(NavigationActions.back());
	        returntrue;
	    };
	    }
	    
	    const mapStateToProps = (state) => {
	      return {
	        state : state.navigation
	      }
	    }
	    exportdefault connect(mapStateToProps)(AppNavigatorWithState);
	    
	```

* **nixon-gamboa** (2)

	
	Esto ya lo soluciono react navigation? por defecto me funciona en el emulador, mis versiones son:
	``` 
	    "react": "16.8.3",
	        "react-native": "0.59.8",
	        "react-native-datepicker": "^1.7.2",
	        "react-native-gesture-handler": "1.2.2",
	        "react-native-snap-carousel": "^3.8.0",
	        "react-native-vector-icons": "^6.5.0",
	        "react-navigation": "3.11.0",```
	    
	    Lo queno me funciono fue el efecto modal y cerrar la pestaña con un gesto hacia abajo. funciona hacia el lado 
	```

* **jmframil** (1)

	
	¿¿ Por que a lo ultimo Leo este tema??

	* **elias.dominguezpires** (1)

		
		desapareció

## 0280. Conclusiones del curso

### Descripción:


### Comentarios:

* **Luis Enrique Sanchez Piñerua** (4)

	
	Felicidades a todos los que completaron el curso 😄. Dejemos reviews de este curso y el de react-native para que Leonidas se anime a hacer el curso de Animaciones con React-Native

* **Felipe Acosta** (2)

	
	Styled Components para React Native seria muy bueno.

	* **Juan David Castro (Platzi)** (2)

		
		Lo he intentado, pero me salen mucho errores todo el tiempo. Ademas he leído que no es tan bueno en performance comparado con los estilos en linea normalitos…

	* **Nestor  de Valais** (7)

		
		Una opcion es declarar variables.
		
		Archivo styles.js
		``` 
		    exportdefault {
		      COLOR_PRIMARY: 'green',
		      COLOR_SECONDARY: '#111',
		      FONT_NORMAL: 'OpenSans-Regular',
		      FONT_BOLD: 'OpenSans-Bold',
		      BORDER_RADIUS: 5
		    }
		    
		```
		
		Luego haces el import y utilizas las variables
		``` 
		    import { StyleSheet } from ‘react-native’;
		    import theme from ‘./styles’;
		    .
		    .
		    
		    exportdefault StyleSheet.create({
		    largeButtonText: {
		    color: theme.COLOR_PRIMARY
		    }
		    });
		    
		    
		```

	* **camilomunozg** (1)

		
		Excelente opción.

* **David Behar** (1)

	
	El curso es bueno, pero ya está utilizando una versión demasiado antigua de todas las librerías, recomiendo este video para actualizarnos después de tomar este curso  
	[[VideoReactNavigation2020.png](https://static.platzi.com/media/user_upload/VideoReactNavigation2020-e26bcd8e-9fb5-4354-ab14-4a64de8042d6.jpg)](<https://www.youtube.com/watch?v=nQVCkqvU1uE!)>

* **Roy Hodson** (1)

	
	Alguno tiene el repositorio del curso?

* **Nestor  de Valais** (1)

	
	Que librería se puede usar para el multi-lenguaje y para la utilización de mapas ?

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		Para multilenguaje creo que react-intl-v2 <https://www.npmjs.com/package/react-intl-v2>

	* **Nestor  de Valais** (2)

		
		Gracias @GOLLUM23 Encontre esta tambien [https://github.com/AlexanderZaytsev/react-native-i18n](url)

	* **George_18** (1)

		
		Para mapas la mejor es : <https://github.com/react-native-community/react-native-maps>

* **andresdcl7** (1)
Hola compañeros, quería saber si de pronto ustedes me podrían indicar como hacer un tabs que me permita cargar otras views pero sin tener...

	* **aragonesteban (Platzi)** (1)

		
		Hola Andres, esto lo podrías hacer mediante un [ScrollView](https://facebook.github.io/react-native/docs/scrollview#docsNav) agregando el atributo `pagingEnabled` el cual te permite tener una paginación en el scroll, el cual puedes convertir a Tabs, cada que le das click a un Tab haces scroll a la pagina que deseas navegar, de esta manera no se actualizara todo el tab un nuevo `View`, un ejemplo que puedes ver es en la app de **Platzi** versión 30.8.

* **Nestor  de Valais** (1)
Que librería se puede usar para el multi-lenguaje y para la utilización de mapas ?

	* **Diego Alexander Forero Higuera (Platzi)** (3)

		
		Para multilenguaje creo que react-intl-v2 <https://www.npmjs.com/package/react-intl-v2>

* **Gerardo Cetzal Balam** (0)

	
	Me gusto mucho el curso, muy entretenido, no seguí con las versiones que uso Leonidas, fui directo a las nuevas, con la documentación me sirvió para seguir el ritmo del curso.

