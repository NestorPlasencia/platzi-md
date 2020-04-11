# Introducción a JavaScript

## 0010. ¿Qué es JavaScript

### Descripción:


### Links:

* [Curso de JavaScript Engine (V8) y el Navegador](https://platzi.com/clases/javascript-navegador/)

### Comentarios:

* **Sneyder Alfonso Barreto Buitrago** (22)

	
	Los invito a leer la serie de libros de **_You Don’t Know JS Yet_** por Kyle Simpson. En el primer libro llamado “ _Get Started_ ”, habla a fondo sobre estos temas. En su [repositorio en GitHub](https://github.com/getify/You-Dont-Know-JS) lo pueden leer de manera gratuita.  
	**Al que le interese:** Hago parte de una comunidad llamada _CodeBookClub_ , actualmente estamos leyendo el primer libro y discutimos semanalmente acerca de un capitulo leído, entre otras cosas.  
	Les dejo un enlace a mi [repositorio en GitHub](https://github.com/sneyderdev/codebookclub-resources) en donde podrán encontrar algunos recursos que compartimos dentro de la comunidad, así como también información por si quieren unirse.  
	Espero esto les sea de ayuda, un saludo.

	* **adersonrangel** (1)

		
		Excelente aporte.

	* **lmoran** (1)

		
		Muy buen aporte, me está sirviendo para profundizar conceptos.

	* **Christian Erik Velázquez Morales** (1)

		
		Muchas Gracias.

* **Karla Agraz** (10)

	
	  * Orientado a objetos: Se genera un objeto llamado usuarios y cada una de las personas que se registren en la aplicación va a ser usuario de este objeto de esta base de datos. Cada usuario va a tener ciertas particularidades como nombre, apellido, sexo, ciudad, etc; todos estos datos quedaran guardados en el usuario.
	
	  * Débilmente tipado: JavaScript puede asumir operaciones matemáticas con strings y booleanos, te regresará un número. En otros lenguajes de programación fuertemente tipados puede aparecer un error en este tipo de operaciones raras.
	
	
	
	
	Compilación: Cuando trabajamos en nuestro programa debemos mandarlo a una etapa de compilación para saber si funciona o no, en donde se traduce lo que estas haciendo en un lenguaje que entiendas como humano a un lenguaje que la máquina pueda entender (código binario).
	
	  * Dinámico: Solo lo abres en el navegador. No tienes que compilarlo para saber si funciona o no.
	
	

* **lmoran** (9)

	
	**BACKWARDS & FORWARDS**
	
	**FORWARDS:** Ser compatible con versiones futuras significa que incluir una adición al lenguaje en un programa no causaría que se rompa si se ejecuta en un motor JS anterior. JavaScript no es compatible con versiones futuras.
	
	**BACKWARDS COMPATIBLE: **La compatibilidad con versiones anteriores significa que cuando se acepta como JS valido, no habrá un cambio futuro que haga que el código deje de funcionar. JavaScript es un backwards compatible.  
	El código escrito en 1995, por primitivo o limitado que haya sido, todavía debería funcionar hoy. Como a menudo proclaman los miembros de TC39, “¡no rompemos la red!”.  
	La idea es que los desarrolladores de JS puedan escribir código con la confianza de que su código no dejará de funcionar de manera impredecible porque se lanza una actualización del navegador. Esto hace que la decisión de elegir JS para un programa sea una inversión más sabia y segura, por años en el futuro.  
	Hay algunas pequeñas excepciones a esta regla. JS ha tenido algunos cambios incompatibles con versiones anteriores, pero TC39 es extremadamente cauteloso al hacerlo. Estudian el código existente en la web (a través de la recopilación de datos del navegador) para estimar el impacto de dicha rotura, y los navegadores finalmente deciden y votan si están dispuestos a tomar el calor de los usuarios por una rotura a muy pequeña escala contra los beneficios de arreglar o mejorar algún aspecto del lenguaje para muchos más sitios (y usuarios).  
	Por lo general, los problemas de compatibilidad hacia adelante relacionados con la sintaxis se resuelven utilizando un COMPILADOR (el más común es **Babel** ( <https://babeljs.io> )) para convertir de esa nueva versión de sintaxis JS a una sintaxis más antigua equivalente.  
	**BABEL:** traduce esas nuevas versiones de JavaScript a versiones anteriores.

* **Carlos Eduardo Diaz Polanco** (7)

	
	En resumen, JavaScript es un lenguaje Interpretado, Orientado a Objetos, debilmente Tipado, Dinamico y compilado.

	* **urieelmm** (2)

		
		Agregaría que es case Sensitive (diferencia minúsculas de mayúsculas)

* **picojohn** (5)

	
	a aprender javascript aprovechando la cuarentena 😃

	* **luisP** (3)

		
		No te imaginas cuantos más estamos en la misma 😉

	* **Ralph** (2)

		
		100% cierto

	* **luisP** (2)

		
		ya voy por la clase 8 😃

	* **Juan José Vega Quintero** (3)

		
		X5

* **iridian** (5)

	
	WOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOW excelente explicación pude entender mejor que es:  
	**orientado a objetos, **  
	**lenguaje débilmente tipado y dinámico **  
	así como que **babel **es un compilador de javascript que nos ayuda a usar las nuevas versiones de JS y convertirlas a código que puedan entender los navegadores con versiones anteriores o:  
	también sobre la diferencia entre el **runtime **y** compile time.**
	
	Gracias. 😄

* **Jose Hidalgo** (5)

	
	Veo q este curso habla de alguna cosas que no están en el curso de Fundamentos de JavaScript.  
	Que bueno que se complementen

	* **Japheth Calzada López** (1)

		
		El de fundamentos de Sasha lo sentí algo extenso, o bueno en lo personal me perdia un poco

* **Juan Esteban Galvis** (4)
Empecé este curso para reforzar mis conocimientos, y en una clase me cambio muchas cosas jaja No sabía que JavaScript es considerado orientado a objetos como Java. Les recomiendo de curso de orientada a objetos de @anncode Y lo de compilado, porque aunque el programador no es el encargado de compilar si se realiza todo ese proceso. Se ve que será un gran curso!

	* **Aaron Gonzalez (Platzi)** (2)

		
		Y espera a que vayas por los demás cursos como EcmaScript o Asincronismo, son muy precisos y te dan un contexto muy avanzado de JS 😄

* **TecnoDesign Paraguay** (4)

	
	 **Backwards y Forwards**  
	**Forwards:** Ser compatible con versiones futuras significa que incluir una adición al lenguaje en un programa no causaría que se rompa si se ejecuta en un motor JS anterior. JS no es compatible con versiones futuras.
	
	**JS es Backwards Compatible:** La compatibilidad con versiones anteriores significa que cuando se acepta como JS valido, no habrá un cambio futuro que haga que el código deje de funcionar.
	
	**¿Como puedo utilizar las nuevas versiones de JS?**  
	Babel: Compilador de JS que te permite utilizar todas las funciones o módulos de JS en tu entorno de trabajo para que puedas utilizarlas. Es una buena practica cuando, si van saliendo nuevas versiones de JS, ya empieces a usarlas porque trae muchas mejoras y BABEL te ayuda, lo que hace es que traduce esa nueva versión de JS a una versión vieja “estándar” que el navegador entiende y así puedas implementarlas en tu entorno de trabajo.

* **vickiavola** (4)

	
	Me fascino ésta clase

* **Kendy Valladolid** (3)

	
	uno más para la carrera de FrontEnd combinado con Diseño UI/UX 🙈❤👩‍💻

	* **Juan Felipe Peralta Zapata (Platzi)** (1)

		
		¡Genial! ¿Ya terminaste el curso? ¿Qué tal te ha parecido? 😄

	* **Juan José Vega Quintero** (1)

		
		Qué tal los de UI/UX?

* **Javier Andres Gamboa Duarte** (3)

	
	Iba comenzar el curso profesional de JS, pero vi que adicionaron este curso a la ruta de JS, muy bien explicado…

	* **Manuel Mosquera** (1)

		
		igual yo !!!

* **Cesar Octavio de Jesús Meza Carrillo** (3)

	
	Me parece muy bien este curso para empezar! Saludos!!

* **Oscar Galicia** (3)

	
	Parece que es un excelente complemento al curso de Fundamentos de Javascript con Sacha, estoy contento de hacer este curso.

* **Merlyn Rodriguez** (3)

	
	dos puntos por terminar de ver el video :v

* **Camilo Alexander Velandia Velandia** (3)

	
	vamos, llevaba dias esperando que estuviera disponible este curso

* **matias-alexander-ibarra-trujil** (3)

	
	lo estaba esperando profe

* **Ignacio_Damanes** (3)
Alguien me puede explicar que hace este curso casi al final de la carrera de Javascript por favor? Enserio necesito aclarar esa duda, por...

	* **mbautista95** (1)

		
		Pregunta al soporte de Platzi en “Contáctanos”, probablemente es un error, ya que si te van a dar las bases, debería estar al principio.  
		Lo mismo pasaba con el curso antiguo de Wordpress de la carrera de desarrollo web con Wordpress, uno de los cursos finales, que se llamaba creación y optimización de sitios web con Wordpress, no requería que escribieras ni una sola línea de código, los primeros cursos te enseñaban html, css, php, bases de datos, creación de plugins.  
		Ese curso debía estar al principio en términos de dificultad de aprendizaje.

* **John Steven Bernal Gonzalez** (2)

	
	Alguna información sobre Backwars & Forwards ?

* **Brais Oliveira Sanjurjo** (2)

	
	Hasta donde yo sé [bytecode](https://es.wikipedia.org/wiki/Bytecode) es un código intermedio entre el lenguaje de alto nivel y de [código binario](https://es.wikipedia.org/wiki/C%C3%B3digo_binario) (también llamado código máquina). No sé si JavaScript utiliza bytecode como Java, pero bytecode no es código binario.  
	Ruego se me corrija si me equivoco en algo, gracias!

	* **Rabi Leonel Leon Chan** (2)

		
		Hola Hermano, me encontré esta fuente de [bytecode](https://www.ecured.cu/Bytecode), donde explica lo siguiente :  
		_Código intermedio más abstracto que el código máquina. Habitualmente es tratado como un archivo binario que contiene un programa ejecutable similar a un módulo objeto, que es un archivo binario producido por el compilador cuyo contenido es el código objeto o código máquina._

	* **Milton Enríquez Torres** (2)

		
		Tengo entendido que no, el bytecode únicamente es usado por los lenguajes que requieren maquina virtual como Java o Kotlin.

	* **Brais Oliveira Sanjurjo** (1)

		
		Gracias por el esfuerzo, me apunto esta frase de la documentación que aportada “muchos lenguajes interpretados, de hecho, se compilan para convertirlos en bytecode y después son ejecutados por un intérprete de bytecode” porque ahora tengo dos referencias que afirman eso y puedo tirar del hilo a ver a donde lleva. De otro modo podía ser un simple despiste del profesor.

* **Alexander Nova Arevalo** (2)

	
	Pense Omitir esl curso pero, desaprende lo aprendido y aprenderas mejor 😄

	* **Héctor Daniel Vega Quiñones (Platzi)** (1)

		
		Siempre es una buena idea repasar las bases, son los cimientos de todo lo que hagamos después 😉

* **SebastianMelo7** (2)

	
	Me gustan los nuevos cursos.

* **Juanes Sánchez** (2)

	
	Excelente. Decidí verme este curso básico antes de entrar a la escuela de javascript con el curso de fundamentos. Después de este curso, arranco con toda la ruta de aprendizaje.

	* **bamartinezd** (1)

		
		Tienes razón…

	* **Aaron Gonzalez (Platzi)** (1)

		
		¡Excelentes noticias, **@JuanesSabe**! 😄  
		La Escuela de JS está diseñada para llevarte de 0 a Experto en JS. Te recomiendo mucho realizar todos los proyectos y crear los tuyos 😉

* **Christian Erik Velázquez Morales** (2)

	
	Gracias, Platzi. Me agrada que, tengan cursos en específico para resolver todo tipo de dudas sobre javascript.

* **mbautista95** (2)

	
	Javascript es un lenguaje de programación básico, que nos permite ampliar la interactividad de nuestro sitio web con el usuario.
	
	Es un lenguaje de programación que puede integrar tanto números y textos de distintas variables en un diferentes resultados, interpretando las comillas de un número en una suma como si fuera un texto, y en el caso de multiplicación realizando la operación asumiendo la variable de texto como un número.
	
	Es un programa que no requiere de una compilación para que puedas comprobar la funcionalidad de tu código, sino que es leido en tiempo real por tus dispositivos, software y demás.
	
	En caso de que queramos probar las funcionalidades de mayor actualidad en Javascript, es necesario que utilicemos el compilador Babel.

* **Miguel Ángel Torres Vargas** (2)

	
	Javascript es **Dinamico** más no estatico pues “ejecuta de una vez” en Runtime y no ha de ser compilado (lo cual lo haria estatico).

* **John W. Martínez** (2)

	
	Excelente, vamos a las bases para poder ir por grandes desarrollos.

* **luisrovez** (2)

	
	En JavaScript para concatenar cadenas de caracteres usamos el operador +, en el primer ejemplo 4 + “7”, creo que manera interna 🤔, al toparse con un string, lo concatena con el numero ya que encuentra el signo +, por eso devuelve un string de “47”, interpreta que el numero entero debió ser un string también. En la multiplicación es al revés, ya que, con este operador solamente podemos manipular números, por lo tanto de manera interna, el string, lo convierte o interpreta como un entero.

* **Daniel Idarraga** (2)

	
	Vamo a darle

* **Lorenzo David Lezcano** (2)

	
	Mucho hype con este curso!

* **Cesar Andres Urrea Gutierrez** (1)

	
	Estoy contento de comenzar este curso ¡vamos a darle!

* **Ariel Alejandro Ureña Morales** (1)

	
	Excelente, vamos a empezar con lo basico.

* **Carlos Garcia** (1)

	
	 **¿A qué se debe un bajo entendimiento en programar?**

	* **IanVass** (1)

		
		Intenta estudiar con un motivo, y con una metodología de aprendizaje (Un ejemplo, sería usando la técnica comodoro, 15 o 25 min de estudio, 5 min de descanso, se repite 4 veces y tienes un descanso de 15 minutos o 20 o 30 min y después vuelves) .
		
		En sí aprende a aprender. Espero que sea lo que buscas, si no pues no comprendí tu pregunta jaja

* **Carlos Garcia** (1)

	
	¿Cuándo crear un programa debo basarme en un existente?  
	¿A qué se debe un bajo entendimiento en programar?

* **andresargote** (1)

	
	muy interesante este curso

* **Pablo Rocha** (1)

	
	Interesante lo del motor V8, después de este curso me lo veré para entender mejor como funciona 😄

* **carlosextra1** (1)

	
	Que otro compilador de ECMAScript aparte de babel recomiendan?

* **carlosextra1** (1)

	
	Backwards & Forwards

* **carlosextra1** (1)

	
	Explicación de dinamico

* **JheysonEGalvis** (1)

	
	¿Qué significa la palabra perse?  
	La locución latina per se, que significa ‘por sí’ o ‘por sí mismo’, se escribe en dos palabras, en cursiva y sin acento (no per sé, perse o persé).

* **Jharell Alejandra Hidalgo Loya** (1)

	
	entonces un lenguaje debilmente tipado es cuando no necesitan ser del mismo tipo para poder interactuar entre estas?

	* **snowy** (2)

		
		débilmente tipado significa que no controlan el tipo de variable que declaras y es posible usar variables de cualquier tipo una misma función, por ejemplo: una función puede recibir como parámetro un valor entero, flotante, etc.

	* **Alejandro Lopez Ramírez** (1)

		
		También que una declaración como const, Var o let puede ser cualquier tipo de dato en cualquier momento es decir:
		``` 
		    const x; // solo declaro pero no tiene un valor asignado es decir que en cualquier momento puedo asignarle un valor
		    
		    x = 1 // al ser una constante no cambia después de su declaración pero podría haber dicho que no es un número si no un stringo un array o un objeto.
		    
		    var y;
		    
		    y = 'a' // ahora "y" es un string
		    
		    y = 1 // ahora "y" es un numero
		    
		    y = [] // ahorra "y" es un array
		    
		    ``
		    Let se comporta igual que var enel tipo de dato puede cambiar en cualquier momento. la diferencia es enel alcance de su utilización enel bloque de código. 
		    
		    teen cuenta que al hacer la igualdad reemplazas el valor existente enla variable 
		    
		    En lenguajes fuertemente tipados como java cuando asignas una variable le decimos el tipo de dato que va a manejar y este si no puede cambiar siempre debe ser el mismo tipo de dato.
		```

* **Ezequiel Garcia Camarena** (1)

	
	El arbol que dices, seria como un diagrama se secuencia, dependiendo del nodo del árbol que estemos se espera algo para realizar una acción. Ese algo pueden ser palabras reservadas o símbolos.

* **Alexander Montalvo** (1)

	
	Por lo tanto, por lo pasos 3 y 4 JavaScript es un lenguaje COMPILADO!!!

* **Jeisson Santiago Cortes Ortiz** (1)

	
	…

* **davidhdez8** (1)

	
	Wow, no conocía Babel.

* **33andres33** (1)

	
	otro mas para la carrera de fronted, y despues la escuela de js

* **marlonhmp** (1)

	
	Genial

* **Christian David Sánchez** (1)

	
	JavaScript el lenguaje más importante y potente en la web.  
	JavaScript, es uno de los más potentes e importantes lenguajes de programación en la actualidad, por tres enfoques claros: es útil, práctico y está disponible en cualquier navegador web.
	
	JavaScript fue creado por Brendan Eich y vio la luz en el año 1995 con el nombre de LiveScript, que luego fue nombrado JavaScript, nace como un lenguaje sencillo destinado a añadir algunas características interactivas a las páginas web. Sin embargo, hoy en día ha crecido de manera acelerada y es el lenguaje de programación que se utiliza en casi todos los sitios web en el mundo.

* **Danelia Sanchez Sanchez** (1)

	
	Sobre [Babel](https://babeljs.io/docs/en/)

* **Roberto Villate Morales** (1)

	
	Interesante explicacion, al parecer Degranda entiende bastante bien del tema y sabe explicarlo.

* **Wandy Rafael Santana Evangelista** (1)

	
	Vamos a comenzar. 😃

* **John Botero** (1)

	
	Perfecto para seguir reforzando los fundamentos en JS, Degranda explica muy bien todo.

* **Adán Dueñas Escobar** (1)

	
	Excelente para reforzar todo lo aprendido, acabo de terminar el curso profesional de javascript sin embargo hay que probar nuevas maneras de enseñar

	* **Gabriel De Andrade (Platzi)** (1)

		
		Igual ten en cuenta que este curso es complementario a los que ya hay de JavaScript y contiene diferentes puntos de vista y algunas cosas que pueden no ser tan obvias 😄

* **ASSACOLOMBIA** (1)

	
	Iniciando ahora este nuevo curso, vengo del Fronde Developer que es de 43 clases, veamos que tal el profe Diego.

* **Laurapregonero** (1)

	
	JavaScript es un lenguaje interpretado orientado a objetos tipados y dinámicos!!! que sirve para que las personas puedan interactuar en las paginas web y aplicaciones.

* **Jhon Alexander Romero Gonzaga** (1)

	
	Recién Termine el curso Fundamentos de JavaScript y salio este curso para actualizar mi información. 😉

* **Juan Zavala** (1)

	
	Excelente explicación

* **Alejandro Beltran** (1)

	
	preparado para aprender JavaScript

* **JheysonEGalvis** (1)

	
	Vengo del curso práctico de Maquetación en CSS con el mismo profesor y explica muy bien. 😃

* **Carlos Bueno Tavares** (1)

	
	Jabascript es un lenguaje que revoluciono las paginas estaticas a dinamicas es 6un len6g6uaje compilado, orientado a objeto, bebilmente tipado y dinamico, javascript es backward compile lo que significa que sus nuevas actualizaciones no tendran efecto en tu codigo antiguo si deseas utilizar codigo de nuevas versiones debes utilizar el framework babel que lee tu codigo de js nuevo y lo interpreta a una forma mas standar.

	* **Clair** (3)

		
		JavaScript*

* **Andres Giraldo** (1)

	
	resolví muchas dudas, espero aprender lo maximo

* **jose-morales-varon** (1)

	
	Empezamos bien con esta introducción.

* **Germán Moreno** (1)

	
	Excelente introducción.

* **Juan Torrealba** (1)

	
	Excelente la explicación, tiene una manera de enseñar muy buena!

* **sofia.condori** (1)

	
	Ayuda a crear paginas dinámicas  
	Lenguaje interpretado  
	Orientado a objetos  
	Débilmente tipado, puede interpretar algunos errores, ejem 4+”7”; //47  
	Dinamico: compilación() lo abres en el navegador y vez si funciona o no
	
	Forwards, con nuevas versiones,  
	Js es Backward compile, lo nuevo no se puede usar, para usar trabajar por ejemplo con compiladores como BABEL

* **Alfonso Luis Arrieta Hernández** (1)

	
	Entonces, javascript es en sí es un lenguaje compilado que interpretado.

* **Bervive** (1)

	
	Este curso me va a servir de complemento a lo que estoy aprendiendo en el curso de programación básica

* **HumanEligreg** (1)

	
	No creo que este sea el primer curso en el que lo aplican, pero esto de usar las diapositivas en transparencias me agrada mucho. Claro, cuando se debe usar.

* **Manuel Rivera** (1)

	
	Entonces JS es un lenguaje debilmente tipado, dinámico, no es interpretado, es compilado

* **Francisco de Jesus** (1)

	
	Buena y buen curso para iniciarme en JS!!

* **Martin L.** (1)

	
	que es ecmascript?

	* **Cristobal Vega** (4)

		
		Es la especificación de JavaScript, al ser este un lenguaje que corre en todos los navegadores una organización de estándares (en este caso ECMA International) tiene un documento que nos dice como se debe hacer JavaScript 🤓

	* **Juan Felipe Peralta Zapata (Platzi)** (2)

		
		Aquí en Platzi tenemos un curso por si quieres echarle un ojo: <https://platzi.com/clases/ecmascript-6/>. 😄

* **hugoorlandogonzalez** (1)

	
	No me llevo muy bien con Js hasta el momento pero creo que este curso va a darme una mano jaja

* **Jean Carlos Nuñez Hernandez** (1)

	
	vamos again

* **Aby Leyva** (1)

	
	Pinta bien este curso, se ve muy digerible el contenido…veremos la tendencia en los próximos videos…

* **Cristian Emanuel Ortega Camarena** (1)

	
	Muy buen contenido, y me agrada que quien lo imparte va al grano con todos sus puntos

* **alejandrozapata73** (1)

	
	Excelente explicacion

* **JhonColorado07** (1)

	
	Excelente explicación.

* **Pablo Domínguez Durán** (1)

	
	Genial tener las bases de JavaScript tan bien explicado 👌
	
	Diego todo un crack que sabe cómo funcionan las cosas por dentro 👊

* **Lucas Ramirez** (1)

	
	Lo espere con ganas este Curso, explica muy el Profe !!

* **Daniel Carmona** (1)

	
	Me gusta mucho JavaScript, reforzare mis conocimientos con este curso.

* **Ramón Ruiz** (1)

	
	A empezar

* **Karla Agraz** (1)

	
	Estaba esperando este curso, a darle 👌

* **matias-alexander-ibarra-trujil** (1)

	
	JavaScript cae dentro de la categoría general de lenguajes dinámicos o interpretados, es de hecho un lenguaje compilado. No se compila con suficiente antelación, al igual que muchos lenguajes compilados tradicionalmente, ni tampoco son los resultados de la compilación portátiles entre varios sistemas distribuidos.
	
	Pero, sin embargo, el motor JavaScript realiza muchos de los mismos pasos, aunque en formas más sofisticadas de las que comúnmente conocemos, de cualquier compilador de lenguaje tradicional.

* **juanlondono** (1)

	
	2do en escribir

* **gonzaloPzl** (1)
Alguien me podria explicar bien la parte de Forwards y Backwards?

	* **Juan Camilo Alvarez Jurado** (1)

		
		Backwards-Compatible o Retrocompatible, quiere decir que puedes escribir código en versiones viejas e igual va a seguir corriendo en versiones nuevas. Ya Forwards-Compatible o Compatible Hacia Adelante quiere decir que un código para una versión vieja acepta y permite cosas que están pensadas para una versión nueva, y aún así funciona

## 0020. ¿Por qué JavaScript

### Descripción:


### Links:

* [Curso de Introducción a IoT](https://platzi.com/clases/iot/)

* [Ruta de aprendizaje Backend con JavaScript](https://platzi.com/clases/learning-path/backend-javascript/)

* [Ruta de aprendizaje Frontend con React.JS](https://platzi.com/clases/learning-path/desarrollo-react/)

* [Ruta de aprendizaje Vue.js](https://platzi.com/clases/learning-path/vue/)

* [Ruta de aprendizaje Desarrollo con Angular](https://platzi.com/clases/learning-path/desarrollo-angular/)

### Comentarios:

* **axlina90** (6)

	
	Excelente curso, me encanta, quiero aprender JavaScript.
	
	  * WebAssembly: es un nuevo tipo de código que puede ser ejecutado en navegadores modernos es un lenguaje de bajo nivel, similar al lenguaje ensamblador, con un formato binario compacto que se ejecuta con rendimiento casi nativo y provee un objetivo de compilación para lenguajes como C/C++ y Rust que les permite correr en la web. También está diseñado para correr a la par de JavaScript, permitiendo que ambos trabajen juntos.
	
	

* **Camilo Ernesto Hurtado Cataño** (5)

	
	Url donde hablan mas acerca de webAssembly <https://developer.mozilla.org/es/docs/WebAssembly>

	* **Christian Erik Velázquez Morales** (1)

		
		GRacias.

* **JULIO RAUL CARRANZA RUIZ** (4)

	
	Verdaderamente aplaudo a este profesor te dar un vision 360 del por aprender javascript y donde usarlo

	* **Aaron Gonzalez (Platzi)** (1)

		
		En Platzi nos esforzamos siempre porque todos nuestros alumnos tengan profesores tops de la industria. Por ejemplo, en el área de Frontend todos nuestros profesores son Google Developer Experts 😉

* **Christian David Sánchez** (3)

	
	JavaScript es uno de los 3 lenguajes que todos los desarrolladores web deben aprender:
	
	  1. HTML para definir el contenido de las páginas web
	
	  2. CSS para especificar el diseño de las páginas web
	
	  3. JavaScript para programar el comportamiento de las páginas web
	
	
	
	
	Las páginas web no son el único lugar donde se usa JavaScript. Muchos programas de escritorio y servidor usan JavaScript. Node.js es el más conocido. Algunas bases de datos, como MongoDB y CouchDB, también usan JavaScript como su lenguaje de programación.
	
	**¿Sabías?**  
	JavaScript y Java son lenguajes completamente diferentes, tanto en concepto como en diseño.

* **Pablo Rocha** (2)

	
	Muchas posibilidades de desarrollo con un solo lenguaje, hay que aprender bien todas las opciones que nos de JavaScript.

* **33andres33** (2)

	
	Web Assembly no me gustaría por costumbre, le cojes amor a html CSS Y JS

* **Wandy Rafael Santana Evangelista** (2)

	
	Siempre me ha encatado que al inicio de los cursos un poco de teoria, ayuda mucho a entender muchas cosas antes de comenzar a picar codigo. 😃

* **Jhon Alexander Romero Gonzaga** (2)

	
	Eso de WebAssembly no me lo sabia y esta interesante lo que estaba leyendo acerca de esto.

* **Javier Andres Gamboa Duarte** (2)

	
	No sabia lo de la framework ELECTRON 😮

* **Oveja_Gt** (2)

	
	por qué aprender JS?  
	* Tiene una comunidad enorme  
	* Muchos frameworks y librerias  
	* Se puede construir apps nativas para móviles usando JS  
	* Podemos trabajar con Backend e IOT

* **Carlos Bueno Tavares** (2)

	
	Por que javascript?
	
	javascript tiene muchas tecnologia que te permitiran trabajar en cualquier area que desees digase para aplicaciones web, moviles y de escritorio

* **Andres Giraldo** (2)

	
	es chistoso con el paso del tiempo a tomado muchísima seriedad este lenguaje y tanto que lo criticaban, me sorprende lo versatil

* **Manuel Rivera** (2)

	
	Legoo

* **Aby Leyva** (2)

	
	Vaya…entonces todo tiene cubierto JavaScript con la ayuda de los respectivos Frameworks…Great

* **Merlyn Rodriguez** (2)

	
	dos puntos por terminar de ver el video :v

* **Brayhan Andres Jaramillo Castaño** (1)

	
	excelente explicación

* **Ariel Alejandro Ureña Morales** (1)

	
	Muy interesante conocer el por qué de las cosas

* **andresargote** (1)

	
	Muy muy interesante!!

* **carlosextra1** (1)

	
	WebAssembly!!! que sera de nosotros!!!

	* **durbonca** (3)

		
		yo no veo a platzi sacando cursos de WASM…

* **carlosextra1** (1)

	
	WebAssembly

* **Orlando0302** (1)

	
	excelente

* **Jharell Alejandra Hidalgo Loya** (1)

	
	node tambien es un framework?

	* **Gabriel De Andrade (Platzi)** (1)

		
		No.  
		Node, es un entorno de ejecución que te permite correr JavaScript en tu computadora o servidor. Express por otra parte si es un framework para Node.js.  
		De todas maneras si quieres profundizar en estos conocimientos te recomiendo el [Curso de Fundamentos de Node.js](https://platzi.com/clases/fundamentos-node/) y el [Curso de JavaScript Engine (V8) y el Navegador](https://platzi.com/clases/javascript-navegador/) 😄

* **Ezequiel Garcia Camarena** (1)

	
	mis nota:  
	JS era parte de 3 lenguajes de programación para crear productos web, que son HTML(empaquetar información en la pagina, texto, gif, videos, etc.), CSS (leguaje de estilos) Y JS.  
	JS tiene a ser Desarrollo web, ya que tiene muchas framework que te ayudaran a desarrollar la aplicación web que deseas, pero también te sirve para desarrollar aplicaciones con React Native para android y ios, y electron para aplicaciones de escritorio para Windows y mac.

* **Alexander Montalvo** (1)

	
	WebAssembly: Nuevo lenguaje de programación para construir productos web es muy diferente a JS y con este ya no vamos a tener que utilizar html, css ni JS para poder hacer productos WEB.

* **Jeisson Santiago Cortes Ortiz** (1)

	
	…

* **picojohn** (1)

	
	no sabia que con javascript se podia manejar iot, interesante

* **marlonhmp** (1)

	
	Muy interesante lo de Web Asembly

* **Danelia Sanchez Sanchez** (1)

	
	WebAsembly

* **Roberto Villate Morales** (1)

	
	Estoy muy interesado en la escuela de JavaScript por la gran variedad de recursos que existen y las posibilidades que te abre. Espero en unos meses poder dominar bastante bien el lenguaje y las librerias,

* **ASSACOLOMBIA** (1)

	
	Interesante el gran uso que se le puede dar a JS, espero algun dia poder elaborar un proyecto completo con este lenguaje.

* **Laurapregonero** (1)

	
	Por que JavaScript? porque tenemos gran variedad de librerías para programadores, aparte me parece muy interesante todo el tema de IOT (Internet de las cosas) por lo que hace inteligente cada cosa conectada a Internet.  
	Node.js es un entorno de ejecución de JavaScript.

* **Randy José Agustín Montenegro Socha** (1)

	
	no tenia ni idea lo de WebAssembly, que bueno poder acceder a contenidos actualizados.

* **juancruzbidegain** (1)

	
	Excelente clase!

* **Juan Zavala** (1)

	
	Excelente aporte

* **Germán Moreno** (1)

	
	Genial!

* **Juanes Sánchez** (1)

	
	Muy poderoso JavaScript. Suficientes razones para aprenderlo y verse todos los cursos de la escuela de JavaScript y sus derivados.

* **Bervive** (1)

	
	sera que de a poco este nuevo lenguaje webassembly va a desplazar el uso de javascript, html y css ? en teoria un solo lenguaje que reuna las funciones de los 3 suena muy bien… que piensan ustedes?

	* **adersonrangel** (2)

		
		Yo creería que si… lo bueno es que puedo reutilizar lo que ya se de otros lenguajes.

	* **Eduardo Zamarron Muñoz** (2)

		
		Según lo que he escuchado Web Assembly lo que se prevé que haga es reducir el uso de JS para funciones que se podrían hacer de manera más rápida en c# por ejemplo. Pues se está cayendo en un vicio de que todo se quiere hacer en JS y lo que genera como resultado son páginas súper pesadas.  
		Lo que haría WA es reducir esa carga.

	* **Aaron Gonzalez (Platzi)** (1)

		
		Se prevé que eso podría suceder en un futuro no muy lejano 👀  
		Sin embargo, nada está dicho y es muy válido adquirir maestría en HTML, CSS y JS 😉

* **Francisco de Jesus** (1)

	
	JS tiene muchas aplicaciones no sabia que pudiera ser tan ampliamente usado.

	* **Aaron Gonzalez (Platzi)** (1)

		
		JS ha avanzado tanto que lo puedes usar en:
		
		  * Web
		  * Apps
		  * … y hasta en su cepillo de diente 😉
		
		
		
		<https://iotjs.net/> 😄

* **cether** (1)

	
	It was great!  
	Realmente javascript es muy versátil o no se si es la palabra, pero tiene cubierto gran campo de las aplicaciones, y yo que pensé que sólo era para web.

* **cesar-riveros-baeza** (1)

	
	muy buena clase

* **Cristian Emanuel Ortega Camarena** (1)

	
	Muy buena clase

* **Pablo Domínguez Durán** (1)

	
	No mencionó Polymer 💔

	* **luisrovez** (1)

		
		El único sitio que se que usa Polymer es Youtube 😅

* **Lucas Ramirez** (1)

	
	muy buena clase

* **Daniel Carmona** (1)

	
	Muchos framworks de JavaScript

* **Jose Hidalgo** (1)

	
	Me dejo hypeado todo lo que se puede hacer con JS

	* **JhonColorado07** (1)

		
		Si es mucho lo que se puede hacer con JS, así que a aprender.

* **Carlos Roa** (1)

	
	Muy bien explicado

* **Lorenzo David Lezcano** (1)

	
	Genial!

* **wlm.morant** (1)
Te enseño el curso de javascript pero dentro del curso te digo que ya no vas usar html ni css ni Js para web sino web assembly, decidanse...

	* **Erik Ochoa (Platzi)** (1)

		
		Tranquilo 😅es sólo un decir, lo que pasa es que se le ve muy buen futuro a Web Assembly pero nada está decidido, aprender html/css y js es aún muy válido.

## 0030. Elementos de un Lenguaje de Programación Variables, Funciones y Sintaxis

### Descripción:


### Links:

* [Atom](https://atom.io)

* [Visual Studio Code - Code Editing. Redefined](https://code.visualstudio.com)

* [Sublime Text - A sophisticated text editor for code, markup and prose](https://www.sublimetext.com/)

### Comentarios:

* **Carlos Bueno Tavares** (8)

	
	Valores primitivos:
	
	number = valor tipo entero,  
	string =valor de cadena o texto,  
	boolean = True or false,  
	null, undefined = valores nulos
	
	valores no primitivos
	
	{} or [] = valores tipo objeto

* **Gerardo Nava Pereda** (8)

	
	[The history of “typeof null”](https://2ality.com/2013/10/typeof-null.html)
	
	**null** es un valor primitivo y es **null** NO es un **“object”**
	``` 
	    typeofnull// = "object"
	    
	```
	
	es un error que no pueden corregir por que dejarían de funcionar las aplicaciones actuales.

* **pablod574** (5)

	
	min 5:43 : una aclaración, quien inventó los booleanos no se llamaba “George Boolean”, se llamaba “George Boole”

* **lmoran** (5)

	```
	    /Valores numericos
	    40;
	    //valores de tipo string
	    ("Luis");
	    //valores de tipo Boolean
	    true;
	    false;
	    //valores de tipo vacio:
	    null;
	    undefined; //tener cuidado con el undefine
	    //valores de tipo objeto:
	    //arrays
	    [1, 2, 3];
	    {
	      nombre: "Luis";
	    }
	    
	    //nota: en el navegador para ver que tipo de valor es colocas typeof ejemplo:
	    //typeof true
	    //y te va decir boleaan
	    
	```

* **miguelangelpglez** (4)

	
	Biografia de George Boole:
	
	<https://es.wikipedia.org/wiki/George_Boole>

* **yeseniamosqueragil** (4)

	
	Si quieren ver cuanto tiempo codean al dia o la semana, registrense en esta pagina e instalen la extension para su editor de texto preferido, <https://wakatime.com>, es gratis y ayuda a motivarse.

	* **Aaron Gonzalez (Platzi)** (2)

		
		¡Hey! muchas gracias por tu aporte, Yesenia 😄  
		En este blog hay otros plugins de VSCode que están buenísimos
		
		<https://platzi.com/blog/10-plugins-esenciales-para-vscode/>
		
		Te lo recomiendo mucho 😄

* **Cristian Emanuel Ortega Camarena** (4)

	
	denme mis dos puntitos :V

	* **luisrovez** (1)

		
		Tome sus dos punto
		
		  *   *   * 
		

* **ASSACOLOMBIA** (3)

	
	El valor de undefined, es undefined HAHAHAHAHA

* **Jhon Alexander Romero Gonzaga** (3)

	
	typeof (valor), me parece muy útil esto.

* **Andres Giraldo** (3)

	
	Aqui algunos tipos de datos
	
	![tipos de datos.jpg](https://static.platzi.com/media/user_upload/tipos%20de%20datos-9b93872a-d920-4783-ade1-a0afbc7df95a.jpg)

	* **Luis Corado** (1)

		
		Este diagrama de las clases del profe Juan Diaz

* **AlexanderAReyes** (3)

	
	Solo quería dejar esto por aquí, me pareció curioso.
	
	De hecho es **George Boole** , no George Boolean.
	
	😉🤷‍♀️

* **John Steven Bernal Gonzalez** (2)

	
	 **Dos Componentes principales**
	
	Data que guardamos en la memoria : Numeros, string, objetos etc  
	Tareas(funciones) que haremos con los datos: Hacer osas con los datos  
	Tipos de datos o valores primitivos
	
	Numero = 40  
	String = “John Conor”  
	Booleanos = true o false - toma de decisiones  
	valores vacíos = null o undefined -evitar este tipo de valores -valor faltante
	
	los valores se guardan en memoria
	
	**Valores primitivos o tipo objeto**
	
	Tipo array  
	[1,2,3,4] > tipo objeto internamente tiene valores primitivos
	
	Tipo objeto  
	{nombre: “john”}
	
	para saber que tipo de valor usamos
	
	typeof valor
	
	este nos dira si es tipo numero, string, booleano, objeto

* **Ezequiel Garcia Camarena** (2)

	
	mis notas:  
	Dos componentes principales del lenguaje de programación:  
	1- Data que guardaremos en memoria ( tipos de datos, int, string, objetos, etc)  
	2- Tareas que haremos con esa data (las funciones que crearemos en el lenguaje)  
	Valores y tipos de valores
	
	Valores Primitivos:  
	• Valores de numero : 40  
	• Valores de texto : “cadenas de texto string”  
	• Valor booleano : true o false  
	• Valores vacios : null undefined, valores reservados, valores faltantes  
	Valores no primitivos  
	• Array [1,2,3]  
	Valor objeto  
	• {nombre : “Diego”, edad : 14}

* **davidhdez8** (2)

	
	Vengo de Java, y entiendo que JavaScript no es necesario las ;, pero me rompe la cabeza no verlas en las clases 😦

	* **Germán González** (1)

		
		Pronto las veras, si se usan.

* **JheysonEGalvis** (2)

	
	Es increíble como ha crecido JavaScript.

* **Wilson Arias Ruiz** (2)

	
	aprendiendo desde cero pero muy interesante

* **Martin L.** (2)

	
	que diferencia hay entre un string “” y ‘’?

	* **Cristobal Vega** (6)

		
		En JavaScript, ninguna. Pero en otros lenguajes como C o C++ o Java el colocar ‘’ simboliza a un solo caracter ‘H’, ‘o’ y el colocar “” da indicar que es un texto “Hola”.

	* **Valente IA** (1)

		
		Las comillas simples ’ ’ se utilizan para los tipo de dato char

	* **Juanes Sánchez** (1)

		
		En PHP el tipo de comillas genera diferencia en el contenido. En JS, hasta donde tengo entendido, no.

	* **Aaron Gonzalez (Platzi)** (2)

		
		En JS no hay diferencia alguna. En otros lenguajes como PHP o C estos sí indican otras cosas según cual sea.

* **Aby Leyva** (2)

	
	Yo en lo personal estoy trabajando con Visual Studio Code…Por cierto es excelente la funcionalidad del **typeof**

* **Mirna Mabel Veras Carvajal** (2)

	```
	     //Valor tipo número:
	    40
	    
	    //Cadenas de texto:
	    "Diego De Granda"
	    
	    //Booleanos:
	    true
	    false
	    
	    //Valores vacíos:
	    null
	    undefined
	    
	    //Valores tipo objeto:
	    [1,2,3]
	    { nombre: "Diego" }
	    
	```

* **Héctor Yaniel Remedios Fernández** (2)

	
	Hola, me descargué “Visual Estudio Code” desde el enlace de la clase pero mi Mac me lanza el siguiente mensaje:  
	![Captura de Pantalla 2020-02-20 a la\(s\) 19.49.28.png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202020-02-20%20a%20la%28s%29%2019.49.28-51d6bdae-dac7-4903-b83d-b9e8b7ac7b8b.jpg)
	
	Estoy usando MacOS Catalina. Si alguien sabe como solucionarlo!!!  
	gracias de antemano.

	* **Pablo Domínguez Durán** (2)

		
		Es un enlace seguro. Me parece que dándole click derecho al archivo, y en abrir, lo puedes instalar sin problemas. Es por eso que te dice Mostrar en Finder 😃

	* **Héctor Yaniel Remedios Fernández** (1)

		
		Gracias, Sí funcionó abriéndolo con click derecho / abrir.

	* **Aaron Gonzalez (Platzi)** (2)

		
		¡Hola, **@keepoutofart**!  
		Es un detalle que viene en muchos en Catalina, todo programa que instales te recomiendo que lo hagas con
		
		> click derecho > Abrir 😄

* **Brayhan Andres Jaramillo Castaño** (1)

	
	Una muy buena introducción a los tipos de datos.

* **Gastón Gentile** (1)

	
	Hola!
	
	Para probar su código JavaScript, en lugar de hacer: click derecho -> inspeccionar, dentro de cualquier página, pueden abrir una página en blanco escribiendo en la barra de direcciones:
	
	`about:blank`
	
	Le dan `Enter` y el navegador mostrara una página en blanco.  
	Ahora `apretan F12` y les va a aparecer la consola para que hagan sus pruebas.  
	(funciona en Firefox y Chrome)
	
	Saludos,

* **andresargote** (1)

	
	typeof() es una palabra reservada que nos permite saber el tipo de dato

* **andresargote** (1)

	
	Elementos de un lenguaje de programación: Variables, Funciones y Sintaxis.
	
	1.-Data que guardamos en memoria, tipos de datos como strings, números, booleanos, nulos.
	
	2.-Tareas (funciones) que haremos con esa data.
	
	Existen diferentes tipos de datos, los primitivos y los no primitivos.
	
	Primitivos:  
	-Numeros  
	-Strings  
	-Boleanos  
	-Vacios
	
	Y los no primitivos:  
	-Arrays  
	-Objetos

* **Ulises Antonio Sámano Galván** (1)

	```
	    Existen 2 tipos de elementos en JavaScript:
	    
	```
	
	*Valores o datos: almacenan información  
	*Funciones: realizan acciones con la información
	
	Los datos pueden ser primitivos o no primitivos
	``` 
	    Los primitivos son:
	    
	```
	
	*Números  
	*Strings (Texto que podemos escribir de forma libre)  
	*Booleanos, pueden ser “true” o “false” y sirven para confirmar acciones  
	*Vacíos: Son como una caja vacía, están ahí para guardar cosas cuando lo necesitemos, pueden ser “null” o “undefinide”
	``` 
	    Los no primitivos llevan dentro valores primitivos y son:
	    
	```
	
	*Arrays: Utilizan []  
	*Objetos: Utilizan {}
	
	Podemos conocer que tipo de valores estamos usando con “typeof”

* **John Steven Bernal Gonzalez** (1)

	
	Podría ser buena opción utilizar Vim que piensan ustedes ?

* **garciafran** (1)

	
	Visual Studi Code, es de los mejores editores

* **Pablo Rocha** (1)

	
	Explicación clara y concisa de los tipos de datos que podemos tener y usar en JavaScript!

* **carlosextra1** (1)

	
	Gracias, bastante básico !

* **Orlando0302** (1)

	
	genial

* **Naylin15** (1)

	
	Qué características debería tener una laptop para programar? Memoria RAM de cuánto? SSD?

	* **Gabriel De Andrade (Platzi)** (2)

		
		Para empezar, yo logré empezar con 4GB en Linux, lo recomendable es 8GB pero tener 16GB es increíble. Con respecto al SSD no es algo fundamental en el desarrollo. Yo empecé con un Desktop de 2008 y poco a poco fui mejorando según fuí necesitando 😄

	* **ernestojv** (2)

		
		Si estás iniciando desde ya te recomiendo GNU/Linux o MacOS, por ejemplo para Linux no necesitas muchos recursos, la mayoría de distribuciones te irán bien con unos 4GB de ram y un HDD, pero claro, todo va de acuerdo a tus necesidades, pero con JS no creo que necesites mas que eso.

* **victor-castaneda-rivera** (1)

	
	cuando queda un valor faltante tenemos que guardar algún tipo de valor en memoria. ( null , undefined)

* **Jeisson Santiago Cortes Ortiz** (1)

	
	…

* **Ronal Aguirre** (1)

	
	muy claro!

* **Brais Oliveira Sanjurjo** (1)

	
	 _Las interpretaciones respectivas de los símbolos 0 y 1 en el sistema de lógica son Nada y Universo._  
	George Boole

* **Bryan Javier Calero Robleto** (1)

	```
	    typeof40
	    //Nos devolveria que es un number
	    
	    var x = "calero"
	    typeof x
	     //este no devoleria que es un string
	    
	    var y = true
	    typeof y
	    //Es un boolean
	    
	    var z = null
	    typeof z
	    //es un object
	    
	    var a = undefined
	    typeof a
	    //Es "undefined"```
	    
	```

* **picojohn** (1)

	
	aprendiendo mas, Buena clase

* **Luis Diego Maroto Segura** (1)

	
	Un ejemplo de código JS
	``` 
	    /* 
	    VALORES:
	    
	    Valor <40> es de tipo "number"
	    Valor <"Diego de la Vega"> es de tipo "string"
	    Valor primitivo <true> es de tipo "boolean"
	    Valor primitivo <false> es de tipo "boolean"
	    Valor primitivo <NULL> es de tipo "null"
	    Valor primitivo <> es de tipo "undefined"
	    Valor <[1,2,3]> es de tipo "object"
	    Valor <{nombre: "Diego"}> es de tipo "object"
	    
	    TYPEOF:
	    "Typeof" es un comando para obtener el tipo de variable de un determinado valor.
	    */
	    
	    var numero1 = 40;
	    var cadena1 = "Hola Mundo"
	    var boleano1 = true;
	    var boleano2 = false;
	    var indefinido1;
	    var arreglo1 = [1,2,3];
	    var objeto1 = { nombre: "Diego"};
	    
	    presentar(numero1);
	    presentar(cadena1);
	    presentar(boleano1);
	    presentar(boleano2);
	    presentar(indefinido1);
	    presentar(arreglo1);
	    presentar(objeto1);
	    
	    function presentar(i){
	        console.log("Valor: " + i + " | Tipo: " + typeof(i))
	    }
	    
	```

* **Christian David Sánchez** (1)

	
	**Elementos de un lenguaje de programacion:**
	
	  * Data que guardamos en memoria.
	
	  * Tareas(funciones) que haremos con esa data.
	
	
	
	
	Valores Placeholders: null y undefined.  
	Valores Tipo Objetos: { nombre: “Christian”}
	
	**typeof** : sirve para obtener el tipo de la variable.

* **marlonhmp** (1)

	
	Interesante lo de los booleans en el navegador

* **Juan Zavala** (1)

	
	Interesante

* **MartinMB** (1)

	
	Tremendo

* **horacio-garcia** (1)

	
	genial explicacion

* **Germán Moreno** (1)

	
	Excelente clase.

* **Kevin Vega** (1)

	
	Valores enteros: numeros  
	Valores cadena o String: Texto  
	Valores Boolean: True o False  
	Valor tipo Objeto: Array  
	Valores Vacios: null y undefined

* **Jose guillermo Vazquez Huerta** (1)

	
	para js, ¿que tipo de atributos son los mas comunes o los mas tulizados?

	* **Sammuel** (1)

		
		Eso dependería de la necesidad que tengas con tu código, para cada necesidad podrías usar el atributo que más te convenga

* **Guillermo Vega Diaz** (1)

	
	Excelente el curso para reafirmar los conocimientos

* **Bervive** (1)

	
	El curso esta excelente como complemento y para reforzar todo lo que hemos visto en el curso de programación basica, me gusta que vayamos a trabajar con el visual studio, porque hasta ahora venia solo trabajando con sublime, y a pesar de haberlo descargado no lo habia usado, visual studio parece que tiene mas funcionalidades, ya veremos cual esta mejor.

* **Francisco de Jesus** (1)

	
	Interesante los diferentes tipos de valores primitivos!!

* **luisrovez** (1)

	
	en la barra de direcciones pueden acceder a about:blank y les abrirá una pestaña en blanco, ahí pueden usar la consola y manipular el DOM sin que salgan warnings

* **alejandrozapata73** (1)

	
	Excelente tipo el de typeof… me vino genial, muy buen curso

* **Lucas Ramirez** (1)

	
	Atom es bueno pero Vs code tiene más cosas

* **Cristian Rivera Herrera** (1)

	
	Personalmente yo utilizo Visual Studio Code y Notepad++ como extra

* **Javier Téllez** (1)

	
	con **typeof ** la consola de tu navegador te puede decir el tipo de variable.

* **Daniel Carmona** (1)

	
	Editores de texto:  
	1.- Visual Studio Code  
	2.-Brackets  
	3.-Sublime Text  
	4.- Atom  
	5.-Notepad ++
	
	etc… utiliza el que mas te acomodes

* **Merlyn Rodriguez** (1)

	
	dos puntos por terminar de ver el video :v

	* **Cristian Rivera Herrera** (4)

		
		No se si recuerdas, pero los comentarios en los cursos son para dar puntos de vista sobre los mismos, experiencias y/o aportes.

	* **William Camilo Guzmán Espitia** (4)

		
		Lástima que no hay una opción para reportar ciertos comentarios como “spam”. Este tipo en todos los videos es con lo mismo.

* **Lorenzo David Lezcano** (1)

	
	Excelente herramienta el typeof

	* **arturoperezfigueroa** (1)

		
		No es una herramienta, es un operador.

* **Aaron Gonzalez (Platzi)** (1)

	
	Para iniciar yo recomiendo usar <https://www.atom.io> 😄

	* **Reny Severiche** (6)

		
		Ante lo utilizaba, pero agregando extensiones se volvio bastante lento cosa que con VSC no pasa.

	* **Cristian Andrés Córdova Valencia** (4)

		
		VS Code is love.

	* **AlexanderAReyes** (2)

		
		Exacto, para iniciar esta muy bien.  
		Recordemos que manejar otras opciones para editar nuestros programas, será un plus para nosotros, no nos encerremos solo con una opción.
		
		Yo, uso VS Code como editor principal, pero Atom es una muy buena opción.

	* **Aaron Gonzalez (Platzi)** (1)

		
		Totalmente de acuerdo **@AlexanderAReyes** 😄  
		Yo comencé con Atom y luego pasé a VSCode. Actualmente uso ambos según sea el caso 😄

* **ROGELIO TREJO SANCHEZ** (0)

	
	Una clase muy bien explicada así si da gusto aprender, saludos

	* **Aaron Gonzalez (Platzi)** (1)

		
		¡Hola, Rogelio! 😄  
		Todos nuestros profesores son el top de la industria y su área 😄. Por ejemplo, en el área de Frontend todos nuestros profesores son Google Developer Experts 😉

* **Cesar Alberto Flores Herrera** (0)

	
	Hola, tengo un problema, no me deja abrir el archivo en google chrome, ya lo busque en abrir con… y no aparece la opcion de google. Que puedo hacer?

	* **Gabriel De Andrade (Platzi)** (1)

		
		Intenta arrastrando el archivo a una nueva pestaña de Chrome 😄

	* **Aaron Gonzalez (Platzi)** (1)

		
		🤔 Un error poco raro, César.  
		Te recomiendo lo siguiente:
		
		  * Revisa que la extensión del archivo esté escrita correctamente.
		  * Arrastra el archivo a la venta de Chrome una vez hayas verificado esto.
		
		

## 0040. Variables

### Descripción:


### Comentarios:

* **lmoran** (10)

	
	Dentro de JavaScript tenemos tres formas de declarar una variable las cuales son: **var** , **const** y **let.**
	
	  1. **Var:** Era la forma en que se declaraban las variables hasta ECMAScript 5. Casi ya no se usa porque es de forma global y tiene las siguientes características:
	
	**o Se puede reinicializar:** osea todas las variables se inicializan, por ejemplo:  
	Var pokemonType = ‘electric’ entonces reinicializar es:  
	Var pokemonType = ‘grass’ osea la misma variable con diferentes datos el último dato predomina.  
	**o Se puede reasignar:** osea la variable ya inicializada le reasignamos otro valor por ejemplo: inicializamos la variable: Var pokemonType = ‘electric’ ahora la reasignamos pokemonType = ‘grass’ ya no va var  
	**o Su alcance es función global:** osea inicializamos la variable, pero la podemos llamar desde cualquier bloque (una llave abierta y una cerrada {}) pero hay que tener mucho cuidado con ello ya que puede haber peligro, no es recomendable usar VAR.
	
	**const y let es la forma en que se declaran las variables a partir de ECMAScript 6,**
	
	  2. **const:** sirve para declarar variables que nunca van a ser modificadas:  
	**o No se puede reinicilizar:** es una const única no puede haber otra inicializada con el mismo nombre. const pokemonType = ‘electric’ no puede haber:  
	const pokemonType = ‘grass’  
	o **No se pude re asignar:** una vez que la hayamos inicializado no la podemos reasignar solo con su nombre: const pokemonType = ‘electric’ no puede ejecutarse:  
	pokemonType = ‘grass’  
	o **No es inmutable:** osea no puede cambiar con objetos:
	
	  3. **Let:** Son variables que pueden ser modificadas, se pueden cambiar:  
	**o No se puede reinicilizar:** es una const única no puede haber otra inicializada con el mismo nombre. let pokemonType = ‘electric’ no puede haber:  
	let pokemonType = ‘grass’  
	o **Se puede reasignar:** Osea la variable ya inicializada le reasignamos otro valor por ejemplo: inicializamos la variable: let pokemonType = ‘electric’ ahora la reasignamos pokemonType = ‘grass’  
	o **Su contexto de es bloque:** Solo funciona dentro de un bloque {}, fuera de ello no.
	
	
	

* **hidalgolopezdaniel** (7)

	
	Creo que deberían de enriquecer este video con las diferencias y buenas prácticas de “let” “const” y “var”.

	* **JhonColorado07** (1)

		
		Exacto por muy básico que sea deberían haber explicado la diferencias de éstas.

	* **Gabriel De Andrade (Platzi)** (3)

		
		Eso está en el [Curso de Fundamentos de JavaScript](https://platzi.com/clases/fundamentos-javascript/), que deberías tomar antes de este. Acá la clase [var, let y const: las diferencias entre ellos](https://platzi.com/clases/1339-fundamentos-javascript/12974-var-let-y-const-las-diferencias-entre-ellos/) 😄

	* **luisrovez** (1)

		
		También creo que ese tema debería estar en este curso, ya que, como su nombre lo dice, es un Curso Básico de JavaScript.

	* **adersonrangel** (1)

		
		Ese es el problema de los paths no sabemos cual curso tomar primero… Aunque la explicación está muy bien, profundizare en el concepto. Thanks

	* **Eduardo Zamarron Muñoz** (1)

		
		Gabriel, a mi me parece que este curso es mucho más básico que el de Fundamentos. El de fundamentos tiene más contenido en su temario.

	* **Andres Giraldo** (1)

		
		debo admitir que si esperaba que lo incluyera ya que hablo del ES6 y estándares, una lastima la verdad, terminare este y me iré para el de fundamentos

* **Jhon Alexander Romero Gonzaga** (5)

	
	Importante saber que los tipos de variables son:
	``` 
	    var persona;
	    let persona;
	    const person;
	    
	```
	
	y ya no se utiliza `var` para declararlas, es preferible let para no tener Bugs.  
	sigan el [Curso de ECMAScript 6+](https://platzi.com/clases/ecmascript-6/) para aprender sobre las nuevas integraciones de JavaScript, y esta [clase en especifico explica porque debemos utiliza let antes que var](https://platzi.com/clases/1815-ecmascript-6/26122-let-y-const-multilinea-spread-operator-y-desestruc/)

* **Darwin_Saenz** (5)
![Captura de pantalla 2020-03-20 a las 9.25.08 a. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202020-03-20%20a%20las%209.25.08%20a.%C2%A0m.-59b790fb-e770-40c9-bd5d-e55784b7515e.jpg)

* **Steven Angel Coaila Zaa** (4)

	
	Un pequeño resumen 😊👌
	``` 
	    ////////////////////////
	    // Variables
	    var nombre = 'Steven';
	    var elementos = ['java', 'c++', 'python'];
	    var persona = {
	      nombre: 'Steven',
	      edad: 17
	    }
	    
	    // Declarando variable
	    var edad;
	    
	    // Inicializando variable
	    edad = 17;
	    
	```

* **Manuel Rivera** (3)

	
	Quisiera haber realizado este curso recien empece a aprender a programar , explica de una manera muy explicita cada detalle, excelente 😄

* **Javier Téllez** (3)

	
	Para guardar un valor en memoria, se hace a través de variables, es decir, apartar un espacio en memoria para almacenar un valor.
	
	Para ello declaramos la variable con la siguiente sintaxis:
	
	Var nombre=“Javier”;
	
	Lo que estoy diciendo es que la variable llamada nombre, almacena el valor “Javier”, por estar entre comillas (y por ser de tipado débil), la variable es de tipo char/string.
	
	Cuando no inicializamos la variable, es decir, que no igualamos el nombre de variable con algún valor, lo único que estamos haciendo es reservar un espacio en memoria, y en cualquier momento el programa le va a asignar el valor. Ejemplo:
	
	Var=edad;  
	edad=30;
	
	Otro tipo de variable es el array/arreglo que nos servirá para almacenar diferentes valores a una misma variable, lo identificamos porque dichos valores se encierran entre corchetes. Ejemplo:
	
	var elementos = [“Computadora”,“Celular”];
	
	Con esta variable, podemos llamar uno o varios valores con el mismo nombre, lo unico que cambia es la posición del arreglo, Computadora está en la posición 0 y Celular está en la posición 1.
	
	Cuando queremos definir una variable como objeto, los valores que igualan a la variable se encierra entre llaves. Al igual que el array, almacena mas de 1 valor, solo que es mas complejo porque aqui se le conoce como atributos, todos los objetos tienen atributos. Ejemplo:
	
	Var persona = {  
	nombre:“DIego”,  
	edad:30
	
	Dos atributos de la persona es que su nombre es Diego y su edad es 30.

* **Ariel Alejandro Ureña Morales** (2)

	
	Me encanta esta clase, todo está muy bien explicado.

* **Pablo Rocha** (2)

	
	Eché de menos en esta clase la explicación de las diferentes formas de declarar una variable, entiendo que se dará en una clase futura de Scope, pero se podría haber mencionado, el esto genial 😃

* **Jharell Alejandra Hidalgo Loya** (2)

	
	las posiciones en los arreglos comienzan desde 0 por eso trae “celular”. La posición 0 del array es “computadora”

* **Alejandro Jimenez** (2)

	
	Es mejor usar
	``` 
	    let
	    
	```

	* **33andres33** (2)

		
		realmente no me parece yo utilizaria let en algunos casos mas especificos

* **Pablo Victor Vargas** (2)

	```
	     	    inicializa	    declarar
	    var		nombre	  =    "Pablo"; 			
	```

* **Valente IA** (2)
![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-c38b0ad0-e829-47d6-a543-fd1adbe1127b.jpg)

* **andresargote** (2)
Alguién conoce alguna web para hacer ejercicios de Js?

	* **Juan David Castro (Platzi)** (2)

		
		Yo soy fan de [codewars.com](http://codewars.com). 😎

* **OmarGbet** (1)

	
	“El término «variable» se utiliza aun fuera del ámbito matemático para designar una cantidad susceptible de tomar distintos valores numéricos dentro de un conjunto de números especificado.​” Según Wikipedia.

* **John Steven Bernal Gonzalez** (1)

	
	Que buena explicación

* **durbonca** (1)

	
	ya, y si no quiero poner el ; por que yo soy de EMAC script 2016 y soy flojo para escribir…

* **garciafran** (1)

	
	Resumen:
	``` 
	    var nombre = "Francisco";
	    
	    //declaracion de variables
	    //con dos barras inclinadas genero un comentario
	    
	    var edad;
	    
	    edad = 30;
	    
	    //declaracion de array
	    
	    var elmentos = ["computadora", "ceular"];
	    
	    var persona = {
	        nombre: "francisco",
	        edad: 52
	    }```
	    
	```

* **carlosextra1** (1)

	
	muy bien explicado

* **Ezequiel Garcia Camarena** (1)

	
	Mi nota:  
	Que son las variables y como se utilizan.  
	Que es una variable: como representación de un lugar en memoria que se reserva para guardar un valor. Sintaxis var nombre = “Ezequiel”;
	
	Estados de una variable:  
	Declarar -> Cuando se declara una variable, se reserva un espacio en memoria.  
	Var edad;  
	Inicializar -> se le asigna un valor a la variable, el cual se guarda en el espacio de memoria reservado.  
	Edad = 30;  
	Declaración y asignación de una variable.  
	Var elementos = [“computadora”,”celular”]

* **Jeisson Santiago Cortes Ortiz** (1)

	
	…

* **fabio-hernan-mosquera-obando** (1)

	
	vamos con calma…

* **33andres33** (1)

	
	el ; no es muy utilizado en la actualidad yo no lo utilizo no se si todavia sea buenas practicas utilizarlo

	* **Germán González** (1)

		
		Es una buena practica usarlo, te va a ahorrar problemas luego.

* **picojohn** (1)

	
	muy buena clase

* **Germán Moreno** (1)

	
	Buena explicación.

* **Luis Diego Maroto Segura** (1)

	```
	    /*
	    var es una palabra reservada en JS para poder guardar un valor en memoria.
	    El ";" nos permite indicar que termina una sentencia.
	    
	    Las variales tienen dos estados: declarado e inicializado.
	    */
	    
	    var nombre = "Diego"; //valor declarado e iniciado.
	    var apellido; //valor declarado.
	    apellido = "Perez"; //valor iniciado.
	    
	    var persona = {
	        nombre: "Diego",
	        edad: 30
	    }```
	    
	```

* **Christian David Sánchez** (1)

	
	**Var** es la palabra reservada por javascript que representa el espacio de memoria donde se guarda la variable.
	
	**//Declarando una variable**  
	var edad;  
	**//Inicializando una variable**  
	edad = 23;
	
	**//Array**  
	var lenguajes = [“Javascript”, “C#”]

* **marlonhmp** (1)

	
	Excelente

* **Danelia Sanchez Sanchez** (1)

	
	Sobre qué es una variable

* **ASSACOLOMBIA** (1)
![1.jpg](https://static.platzi.com/media/user_upload/1-0695f3b9-8841-4822-ad4a-e0c5a9123262.jpg)

* **gonzaloPzl** (1)

	
	Una _variable_ es la representación de algún lugar en memoria que nosotros vamos a reservar para guardar un valor.

* **Raundy Ibarras** (1)

	
	Good class!

* **cambel24** (1)

	
	con cada vídeo quiero mas.
	
	****_// declaracion e inicializacion de un arreglo_****  
	var elemento = [‘pepito’, ‘ramiro’]
	
	**// declaracion e inicializacion de un objeto**  
	var persona = {  
	nombre : ‘pepito’,  
	apellido : ‘suarez’,  
	edad : 30  
	}

* **Juan Zavala** (1)

	
	Excelente !

* **jose-morales-varon** (1)

	
	¿editor de texto? ú ¿editor de código?

	* **Gabriel De Andrade (Platzi)** (1)

		
		Los editores como VSCode, Sublime o Atom, son editores de texto plano que pueden editar código de manera eficiente incluso llegando a poder ser un IDE a través de extensiones. La línea ya no está tan clara hoy en día 😛

* **roberto vargas castro** (1)

	```
	    <var nombre = "Roberto";
	    undefined
	    nombre
	    "Roberto"
	    elementos = ["Computadora", "Celular"];
	    (2) ["Computadora", "Celular"]
	    elementos[1]
	    "Celular"
	    elementos[0]
	    "Computadora">
	    
	```

* **Andres Giraldo** (1)

	
	variable es un espacio en memoria reservado para almacenar un valor

* **sofia.condori** (1)

	
	40
	
	“Sofia Condori”
	
	true  
	false
	
	null  
	undefined
	
	[1,2,3]  
	{nombre: “Sofia”}

* **Gerardo Nava Pereda** (1)

	
	## var
	``` 
	    console.log(edad) // undefined
	    
	    // declarar variable
	    var edad;
	    
	    // inicializar variable
	    edad = 18;
	    
	    console.log(edad) // 18
	    
	```

* **Valente IA** (1)

	
	tema básico pero bien explicado

* **Bervive** (1)

	
	Ya estaba un poco familiarizado con los términos gracias al curso de programación básica, aun así, esta muy bien repasar para agarrar solvencia

* **wAguilar** (1)

	
	“Variable es la representación de un espacio en memoria que se va a reservar para guardar un valor”

* **Guillermo Vega Diaz** (1)

	
	Me encantaria que todas las clas las explicaran de esta forma tan clara con el trasfondo de porque son las cosas.

* **Francisco de Jesus** (1)

	
	Me gusta este tipo de clases son muy dinamicas, explica teorias y luego hace ejemplos!!

* **Julián David Palacios Cárdenas** (1)
Diego explica de forma muy clara y concreta los tipos de variables en JS.

* **Gilmar Natanael Morán Aquino** (1)

	
	Variable: representación de algún espacio en memoria que vamos a reservar para almacenar valores, y esos valores pueden ser de varios tipos.

* **Aby Leyva** (1)

	
	Variables: para guardar el valor en memoria y poder utilizarlo posteriormente…  
	Importante no perder en cuenta la cuestión de que es **débilmente tipado** ( _Visto en la primera clase_ ) el cual implica que una variable puede cambiar de tipo de dato a traves de una re-asignación por ejemplo:
	``` 
	    var a=4 + "7";
	    // Ahora a vale "47"  is es  un string
	    typeof a; //devuelve string
	    //Reasignando otro valor como
	    a=23;
	    typeof a; //Ahora a es un numerico
	    
	```
	
	**Byegon**

* **Mirna Mabel Veras Carvajal** (1)

	```
	     //Ejemplo de variable:
	    var nombre = "Oscar";
	    
	    //Declarar una variable:
	    var edad;
	    
	    //Inicializar la variable:
	    edad = 30;
	    
	    //Declarando e Inicializando una variable:
	    var elementos = ["Computadora", "Celular"];
	    
	    //Ejemplo de una variable que guarda un objeto:
	    var persona = {
	        nombre: "Diego",
	        edad: 30
	    }
	    
	```

* **Daniel Carmona** (1)

	
	Me gusta mucho la explicación de las variables de JavaScript

* **Merlyn Rodriguez** (1)

	
	dos puntos por terminar de ver el video :v

* **Merlyn Rodriguez** (1)

	
	primer comentario

* **JuanFe98** (1)
¿Cuál es la diferencia entre “var” y “let” a la hora de crear variables? ¿Cuándo uso cada una?

	* **Juan Felipe Peralta Zapata (Platzi)** (1)

		
		La diferencia principal es el alcance que va a tener esa variable dentro del código. Si se usa **var** , esta tendrá un alcance global. Si se usa **let** , el alcance se limitará a la función o bloque donde fue declarada.
		
		Eso se explica en profundidad en este curso: [Curso de Closures y Scope en JavaScript](https://platzi.com/clases/scope/). 😄

* **ArielScc** (1)
Perdón. ¿El objeto nullocupa espacio de memoria cuando se lo utiliza en una variable?

	* **Gabriel De Andrade (Platzi)** (2)

		
		Sip, sin embargo es sólo el espacio que tomaría la palabra “NULL” en el interpreter. Si quieres aprender quién es el interpreter, te recomiendo tomar en un futuro el [Curso de JavaScript Engine(V8) y el Navegador](https://platzi.com/clases/javascript-navegador/) 😄

* **savier687** (0)

	
	El punto y coma dependera del consenso en el que llegue el equipo de trabajo en el cual estas desarrollando, hay algunos casos en Js donde el punto y coma es estrictamente necesario, por lo tanto es recomendable usarlo,xD

## 0050. Funciones

### Descripción:


### Comentarios:

* **rmmartinez** (7)

	
	Para pasar a la siguiente línea en la consola, sin ejecutar el código, presiona Shift + Enter

	* **luisrovez** (1)

		
		gracias por el tip

* **arturoperezfigueroa** (6)

	
	Lista de palabras reservadas de JS
	
	<https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Palabras_Reservadas>

* **garciafran** (4)

	
	Super la expliacion, aqui el resumen
	``` 
	    //hay dos tipos de funciones
	    // funciones declarativas
	    
	    functionmiFuncion(){
	        return3;
	    }
	    
	    //asi hago el llamado
	    miFuncion();
	    
	    // funciones de expresion
	    //declaramos una variable que guarda una funcion
	    // los parametros van dentro de los parentesis cuando declaro la funcion
	    var miXFuncion = function(a, b){
	        return a + b;
	    }
	    
	    //asi hago el llamado
	    miXFuncion(2, 3);
	    
	    functionsaludarEstudiantes(estudiante) { 
	        console.log(`hola ${estudiante}`); 
	    }
	    
	    functionsumar(a, b){ 
	        var resultado = a + b; 
	        return resultado;
	    }```
	    
	```

* **dacarr** (4)

	
	entonces las arrow function son la evolución de las funciones expresivas, en donde el nombre de la función pasa a ser el nombre de la variable y los parametros con el bloque de codigo su valor
	``` 
	    var saludo = (nombre) => { console.log("hola " + nombre); }```
	    
	```

	* **Angel Joaquín Velasco Gómez** (2)

		
		Las arrow function son diferentes, debes de saber cuando usarlas porque ellas manejan de otra forma el this.

* **matias-alexander-ibarra-trujil** (4)

	
	Hay un tipo de funcion que se llama IIFE, que significa Expresión de Función Invocada Inmediatamente.
	
	Por supuesto, los IIFE no necesitan nombres, necesariamente — la forma más común de IIFE es usar una expresión de función anónima. Aunque ciertamente es menos común, nombrar un IIFE tiene beneficios sobre las expresiones de función anónimas, por lo que es una buena práctica.
	
	la ventaja es que optimiza el codigo ya que no debo nombrar y llamar la función  
	.

	* **Cristian Camilo Cucunubá** (1)

		
		Para convertir la funcion expresiva/anonima de la clase en una IIFE seria algo asi
		``` 
		    (function() {
		      return 3
		    })()
		    
		    
		```
		
		Asi la funcion se declara y ejecuta automaticamente

* **Ulises Antonio Sámano Galván** (3)

	```
	    Funciones
	    
	```
	
	Las funciones son las tareas que va a llevar a cabo el navegador. Existen 2 tipos de funciones  
	1) Declarativas  
	2) De expresión  
	Ambas pueden llevar parámetros, que son los datos que necesitan para ejecutarse.  
	Cada parámetro va separado por una coma.  
	Cada instrucción que tenga la función debe terminar con ; .  
	Si queremos que una función nos dé un numero o dato tenemos que usar la siguiente sintaxis:
	
	_return El dato que queremos que nos dé;_
	``` 
	    Las funciones declarativas tienen la siguiente sintaxis:
	    
	```
	
	_function Nombre de la función (Parámetros de la función) {Instrucciones}_
	``` 
	    Un ejemplo de una función puede ser una suma:
	    
	```
	
	_  
	function suma (a,b) {return a+b;}_
	``` 
	    Las funciones de expresión son aquellas que guardamos en una variable, por lo tanto, no es necesario nombrarlas y tienen la siguiente sintaxis:
	    
	```
	
	_var Nombre de la variable = function(Parametros){Instrucciones}.  
	_
	
	Un ejemplo de una función de expresión sería:
	
	_var suma = function(a,b){return a+b;}_
	``` 
	    Para ejecutar las funciones debemos usar la siguiente sintaxis:
	    
	```
	
	_Nombre de la funcion(Parametros función); _
	
	Si la función no tiene ningún parámetro, únicamente se escribe:
	
	_Nombre de la función(); _

* **Jhon Alexander Romero Gonzaga** (3)

	
	al declara una función expresiva o también una arrow function, es mejor utilizar `const` ya que no se la volverá a reasignar un valor a futuro. No utilicen `var`.
	``` 
	    const miFuncion = function(a, b){
	    	return a + b;
	    }
	    
	```

* **EmiGarello** (3)

	
	tenia pensado saltarme el curso para arrancar Profesional, pero la verdad que esto aclara muchisimo el panorama para los que recien estamos empezando, gracias.

* **Juan Diego Luque Linares** (3)

	
	La Comilla que utiliza en consola ` es Alt+96  
	😄

* **Javier Téllez** (3)

	
	Hay dos tipos de funciones, declarativas y de Expresión.  
	Las funciones declarativas se llaman así porque les declaramos un nombre a la función.  
	Las funciones expresivas, también son conocidas como anónimas porque no les ponemos un nombre a la función, simplemente almacenamos la función dentro de una variable.

* **Ariel Alejandro Ureña Morales** (2)

	
	Intento de una funcion para darte las gracias c:
	``` 
	    functionagradecer(profesor){
	        return"Gracias por la leccion " + profesor;
	    }
	    
	```

* **durbonca** (2)

	
	Diferencias prácticas?

	* **Ulises Antonio Sámano Galván** (1)

		
		Las funciones de expresión solo deben usarse cuando van a ser utilizadas en una o pocas ocasiones, ya que solo pueden ser ejecutadas cuando el navegador lea esa parte del código. En cambio, las funciones declarativas están disponibles siempre.

* **ASSACOLOMBIA** (2)

	
	Me cuesta entender los de las funciones, esperemos como nos va en el camino .

	* **Germán González** (1)

		
		Que no entiendes de las funciones a ver como te ayudamos.

	* **rsalamanca** (1)

		
		Todo es cuestión de que practiques mucho sin embargo déjanos saber q no entiendes tal vez te podamos ayudar

* **gonzaloPzl** (2)

	
	Las **Funciones** son un conjunto de sentencias que podemos utilizar para generar ciertas acciones con los valores que guardamos en las variables.

* **Oveja_Gt** (2)

	
	Para los que tengan configurado el teclado para latinoamérica, puede sacar las comillas utilizadas en el ejemplo con **ctrl + alt + `** y luego presionar la tecla espaciadora.

* **Andres Giraldo** (2)

	
	es de practicar mucho, el tema de las funciones esta bastante amplio pero con estos ejemplos quedo muy claro, ahora la misión es practicar

* **Brandon Iván Quiroa Loarca** (2)

	
	Estoy aprendiendo bastante con el.

* **Francisco de Jesus** (2)

	
	Nunca aprendi tanto en una sola clase!!

* **andresargote** (1)

	
	 **Entonces** los parametros son como variables?

	* **Eduardo Hernand** (1)

		
		Si ahi estas declarando variables que solo viviran en la función(por algo llamdo Scope local)

* **David Rodriguez** (1)

	
	Muy bien explicado!!!  
	mas claro imposible

* **Ariel Alejandro Ureña Morales** (1)

	
	Excelente explicacion. c:

* **John Steven Bernal Gonzalez** (1)

	
	 **Función Expresiva**
	
	Denominamos una función expresiva a una variable que guarda una función a esta función se le llama también función anónima y por lo tanto propiamente la función no tiene nombre
	
	`var miFuncion = function(){  
	return 3  
	}
	
	miFuncion(); // llamar funcion`
	
	**Función Declarativa**
	
	Se declara con la palabra reservada función y le damos un nombre y toda función viene con su parámetro
	
	`function miFuncion() {  
	return 3 // palabra reservada de JS para regresar un valor  
	}
	
	miFuncion() // Para llamar mi función`

* **Pablo Rocha** (1)

	
	Buena explicación!

* **carlosextra1** (1)

	
	Igual bien explicado!!

* **Ginnio Sarabia** (1)

	
	  * **FUNCIÓN DECLARATIVA**
	
	
	``` 
	    functionmiFuncion()
	    {
	    	return0;
	    }
	    
	```
	
	  * **FUNCIÓN EXPRESIVA**
	
	
	``` 
	    var miFuncion = function()
	    { 
	    	return0;
	    }
	    
	```

* **Robinson Matias Aguilar Bascuñan** (1)

	
	como hago ese tipo de comillas para colocar la variable en un string ?  
	“hola ${estudiante}”

	* **Jorge Mendez Ortega** (1)

		
		para eso tienes que utilizar ` (no es una comilla simple se conocse como apostrofo) y tu ejemplo queda asi
		``` 
		    console.log(`Hola ${estudiante}`);
		    
		```

	* **Jorge Andrés Grey Cornejo** (1)

		
		Depende de la configuración de idioma de tu pc y el teclado que tengas. Busca en que botón de tu teclado está ese símbolo y oprímela, sí no te sirve prueba con AltGr + esa tecla o sino prueba con Alt+96.

* **oscar-abraham-carrillo** (1)

	
	Otra forma de hacer la suma con arrow functions un concepto que despues lo vemos en fundamentos pero es practiacemnte una abrevación de la palabra function con una flechita =>
	``` 
	    var suma = (a,b)=>console.log(`${a+b}`)
	    
	```

* **Orlando0302** (1)

	
	muy interesante

* **Alexander Montalvo** (1)

	
	Entiendo todo pero me gustaria mejor hacer mas ejecicios 😃

* **Ezequiel Garcia Camarena** (1)

	
	Clase 5. Funciones  
	Que son las funciones -> son un conjunto de sentencias que nosotros utilizamos para generar ciertas acciones con las variables, y regresar algo.  
	Tenemos 2 tipos de Funciones: Declarativas y de Expresión
	
	Declarativa, Sintaxis:  
	function sumar(a,b){  
	var resultado = a + b;  
	return resultado;  
	}
	
	Sumar(1,2);
	
	Expresión, Sintaxis:  
	Var mifunction = function(a,b){  
	return a + b;  
	}  
	Mifuncion(1,2);

* **Angelo Zambrano** (1)

	
	No entendí muy bien la diferencia lógica entre una función declarativa y de expresión. ?

	* **Jharell Alejandra Hidalgo Loya** (2)

		
		en la de expresión el resultado final sera el que se guarde en la variable que declaraste

* **Jeisson Santiago Cortes Ortiz** (1)

	
	:0

* **vanesora** (1)

	
	haciendolo tal cual me sale hola ${estudiante}

	* **Moises19** (1)

		
		De seguro te falto poner las comillas invertidas:
		``` 
		    ``
		    
		```
		``` 
		    console.log(`Hola ${estudiante}`)
		    
		```

* **Germán Moreno** (1)

	
	Excelente.

	* **Germán González** (1)

		
		Hey Tocayo.

* **picojohn** (1)

	
	huy, muy bueno, habia utilizado funciones antes, en otro lenguaje, me perdi algo en las expresivas y declarativas, buscare mas, a seguir aprendiendo

* **Luis Diego Maroto Segura** (1)

	
	Notas de esta lección:
	``` 
	    /*
	    Las funciones son un conjunto de sentencias, que utilizamos para realizar acciones con valores que guardamos en las variables.
	    Funciones son como procedimientos o tares.
	    
	    Para llamar una función, se coloca el bombre de la función, seguido de "()". El "()" le dice a JS que hay mismo se llama la función.
	    Dentro de "()", se indican los parámetros.
	    
	    function() es una función anónima porque no tiene nombre.
	    */
	    
	    //Declatativas
	    functionmiFuncion1(){
	        return;
	    }
	    
	    //De expresion
	    var miFuncion2 = function(){
	        return;
	    }
	    
	    //De expresión con parámetros
	    var miFuncion3 = function(a,b){
	        return a + b;
	    }
	    
	    //Llamando una función.
	    miFuncion1();
	    miFuncion2();
	    miFuncion3(1,2);
	    
	    
	    //Uso de parámetros de una función.
	    var estudiante = "Diego"
	    
	    holaEstudiante1(estudiante);
	    holaEstudiante2(estudiante);
	    
	    functionholaEstudiante1(estudiante){
	        console.log(`Hola ${estudiante}`);
	    }
	    
	    functionholaEstudiante2(estudiante){
	        console.log("Hola " + estudiante);
	    }
	    
	    //Uso de parámetro de una función con return
	    
	    var num1 = 10;
	    var num2 = 25;
	    
	    console.log("Resultado: " + calcular(num1,num2));
	    
	    functioncalcular(x,y){
	        var resultado = x + y;
	        return resultado;
	    }```
	    
	```

* **Danelia Sanchez Sanchez** (1)

	
	Template Strings (Plantilla de Cadena de Texto)

* **Christian David Sánchez** (1)

	
	Sintaxis de la función de JavaScript  
	Una función de JavaScript se define con la functionpalabra clave, seguida de un nombre , seguido de paréntesis () .
	
	Los nombres de funciones pueden contener letras, dígitos, subrayados y signos de dólar (las mismas reglas que las variables).
	
	**// Función Declarativa**  
	function myFunction() {  
	return “Mi nombre es Christian”;  
	}
	
	**// Función Expresiva o Función Anónima**  
	var myFunction = function () {  
	return “Mi nombre es Christian”;  
	}
	
	**//Parámetros: son valores que la función recibe.**  
	function myFunctionParameter(a, b) {  
	return a + b;  
	}
	
	**//Ejemplo:**  
	function saludoEstudiantes(estudiante){  
	console.log(`Hola! Soy ${estudiante}`);  
	}
	
	**//Interpolación de Cadenas**  
	console.log(`Hola! Soy ${estudiante}`);

* **marlonhmp** (1)

	
	Funciones declarativas y de expresion.

* **gustavoadolfocastaedalondo** (1)

	
	Las funciones sirve para empaquetar pedazos de código, reducir la repetición de código y asociarle nombre a varios subprogramas.

* **Juan Zavala** (1)

	
	Wow, todos los días se aprende algo, por pequeña que sea

* **lmoran** (1)

	
	Utilizó lo que son template literal: esas comilla en windows se sacan con Alt + 96.

* **Kevin Vega** (1)

	
	bloque de código que define la función:
	
	La palabra clave ‘function‘  
	El nombre que queremos darle a dicha función, en este caso: miFuncion  
	Unos paréntesis que añadimos al nombre para identificarla como función: miFuncion()  
	Un bloque de instrucciones que queda encerrado entre llaves { } . En este caso solo hemos incluido una (return), pero podrían ser varias. Las instrucciones deben llevar al final el correspondiente punto y coma (😉

* **Carlos Eduardo Diaz Polanco** (1)

	
	Excelente contenido!

* **Frank Carmona** (1)

	
	muy bueno

* **Bervive** (1)

	
	Ojala pronto empecemos a hacer proyectos, creo que así aprendo mejor que solo con ejemplos o definiciones.

* **Guillermo Vega Diaz** (1)

	
	Excelente funciones Declarativas y Expresivas o Anonimas

* **Lucila Belen Pésaro** (1)

	
	Explica muy bien =)

* **Manuel Rivera** (1)

	
	y las arrows functions ? No se consideran funciones ?

* **hidalgolopezdaniel** (1)

	
	¿cuándo o en que casos debo usar una función expresiva y una anónima?

	* **Cristian Camilo Cucunubá** (1)

		
		Hola, una funcion expresiva y anonima son la misma cosa, depronto quisites decir cuando usar una declarativa y una expresiva/anonima. Te comparto este [post](https://dev.to/designpuddle/coding-concepts---anonymous-methods-a9o) donde puedes ver cuando usar una funcion anonima.

	* **luisrovez** (2)

		
		Lo que hago usualmente es usar las funciones expresivas para almacenar cierto resultado, por ejemplo, detectar un evento y almacenarlo en la variable para posteriormente compararlo. Las anónimas las uso para ejecutar un bloque de código en ese momento, por ejemplo, el click en un botón y mandar un saludo justo después del click.

* **Aby Leyva** (1)

	
	Las funciones tienen una gran funcionalidad y es que nos **permite reutilizar código** al permitir ejecutar una acción o serie de acciones y tan solo se manda a llamar cada vez que sea requerido y solo pasando parámetros si es que se requieren.

* **Mirna Mabel Veras Carvajal** (1)

	```
	    //Declarativas
	    
	    functionmiFuncion(){
	        return 3;
	    }
	    
	    miFuncion();
	    
	    
	    //De Expresión:
	    
	    var miFuncion2 = function(a,b){
	        return a + b;
	    }
	    
	    miFuncion2(a,b);
	    
	```

* **Daniel Carmona** (1)

	
	Las conocía solo como anónimas

* **savier687** (1)

	```
	    // Tipos de funciones
	    // Funciones declarativas
	    
	    functionmiFuncion() {
	        return3;
	    }
	    
	    miFuncion();
	    
	    // Funciones Expresivas -- Tambien llamadas anonimas
	    
	    var miFuncion = function(a,b){
	        
	        return a + b;
	    }
	    
	    miFuncion(12,10)```
	    
	```

* **Merlyn Rodriguez** (1)

	
	dos puntos por terminar de ver el video :V

	* **savier687** (2)

		
		De verdad haras esto en todos los videos?

* **juanlondono** (1)

	```
	    // Funciones declarativas
	    functionnombre_funcion(){
	    	instrucciones ;
	    	}
	    
	    // Funciones Expresivas
	    var nombre_funcion =  function( parametros ){
	    	instrucciones ;
	    	}
	    
	    // para llamar a las funciones
	    nombre_funcion();
	    
	    nombre_funcion(parametros);	
	    
	    
	```

* **Lorenzo David Lezcano** (1)

	
	Muy buena explicación sobre las funciones

* **ironcap** (1)
Entonces, y vieendo la lección anterior; una expresión es: // ¿Todo ésto es una expresión? (la delcaración y asignación de variables en c...

	* **Marco Aurelio Elizalde Torres** (1)

		
		así es, estas declarando y asignado la variable.

* **Añaqui Apolinar Morales** (1)
Como declaro en mi funcion si la variable que recibe es obligatoria ???

	* **Luis Arturo Lira Cerda** (3)

		
		Actualmente con JavaScript vanilla no existe algo así como en otros lenguajes como C#, Java, etc.
		
		Existe TypeScript, que cuenta con esa posibilidad de tipado de datos y POO, extiende todas la capacidades de JS. Además de que existen otras librerías que seguramente dan esta posibilidad.
		
		Con Javascript vanilla (Javascript puro) lo que podrías hacer es que dentro la función tengas un if para comprobar que el valor que necesitas no sea undefined o empty.
		
		Algo así como:
		``` 
		    functionSuma(a, b) {
		      if (isNaN(a) || isNaN(b)) {
		        console.log("Los valores deben ser números")
		        return
		      }
		      console.log(a + b)
		      return a + b
		    }
		    
		    let x = Suma(3) // Regresa el undefined y muestra el log
		    let y = Suma(3, "a") // Regresa el undefined y muestra el log
		    let z = Suma(3, 1) // Regresa el valor y hace el log de la suma
		    
		```

## 0060. ¿Cuándo utilizar una función declarativa y una expresiva

### Descripción:


Cuando hablamos de funciones en JavaScript, tenemos dos tipos de funciones: Funciones Declarativas (function declaration / function statement) y Expresiones de función (function expression / funciones anónimas).

### Funciones Declarativas:

En las funciones declarativas, utilizamos la palabra reservada function al inicio para poder declarar la función:
``` 
    function saludar(nombre) {
    	console.log(`Hola ${nombre}`);
    }
    
    saludar('Diego');
    
    
```

#### Expresión de función:

En la expresión de función, la declaración se inicia con la palabra reservada var, donde se generará una variable que guardará un función anónima.
``` 
    var nombre = function(nombre){
        console.log(`Hola ${nombre}`)
    }
    
    nombre(‘Diego’);
    
    
```

En la expresión de función, la función podría o no llevar nombre, aunque es más común que se hagan anónimas.

### Diferencias:

A las funciones declarativas se les aplica hoisting, y a la expresión de función, no. Ya que el hoisting solo se aplica en las palabras reservadas var y function.

Lo que quiere decir que con las funciones declarativas, podemos mandar llamar la función antes de que ésta sea declarada, y con la expresión de función, no, tendríamos que declararla primero, y después mandarla llamar.

### Comentarios:

* **Fernando Alejandro Yerena Ramos** (21)

	
	El profesor Sacha Lifzyc, del Curso de Fundamentos de JavaScript tiene un video en Youtube explicando que es el _Hoisting_. Un recurso imperdible: [¿QUÉ ES EL HOISTING en JAVASCRIPT? | JS en ESPAÑOL](https://www.youtube.com/watch?v=uI6o97A4IrI)

	* **Alexander Nova Arevalo** (2)

		
		Me gusta el video, me dejo claro todo con el GLOBO 😄:D

	* **Javier Andres Gamboa Duarte** (1)

		
		woow gracias!

	* **Andres Burbano** (2)

		
		Wow muy bueno. Muchas gracias.

	* **ELITA CAMPOJO GUEVARA** (1)

		
		Veré el video para entender lo del Hoisting. Gracias.

* **Eleazar Carreón Álvarez** (14)

	
	Aquí estoy llamando la función antes de que sea declarada;
	``` 
	    mostrarMensaje();
	    
	    functionmostrarMensaje() {
	      console.log('Hello world!');
	    }
	    
	```
	
	El código si lo ejecuta.
	
	En cambio si usamos:
	``` 
	    mostrarMensaje();
	    var mostrarMensaje() = function (){
	    console.log('Hello World!');
	    };
	    
	```
	
	Mostrara un error de que no es una función, pues no ha surtido efecto el hoisting.

	* **ferchodleon** (2)

		
		Que buen ejemplo, me quedo mucho mas claro, gracias!!!

	* **Chrystian Fabian Lozano Ramirez** (1)

		
		tan claro como curso de udemy

	* **davidhdez8** (1)

		
		Muy buen ejemplo, excelente.

* **eduvra** (10)

	
	Buena explicación, solo que puede ser un poco confuso al final tan solo por la palabra “Hoisting”, [pero acá puedes aprender más sobre ella.](https://developer.mozilla.org/es/docs/Glossary/Hoisting)

	* **Eric Perez** (2)

		
		Excelente aporte compañero.

	* **carlosextra1** (1)

		
		gracias

* **Miguel Ángel Torres Vargas** (7)

	
	 **Hoisting:** Es aquel que declara las variables y las funciones antes de que inicie cualquier otro código. En cortas palabras el _Inicializador_ de variables y funciones nativas de JS. _ (Las palabras var y function)_

	* **Juan José Vega Quintero** (1)

		
		Corto y preciso.

* **AITeam** (5)

	
	Lo que pude buscar en internet es esto:  
	Se llama hoisting al proceso de “elevar” las declaraciones de variables al inicio , es decir, que si declaramos un var y nos ponemos a llamar a esa variable por encima de su declaración podríamos ya tenerla en memoria , pero con valor UNDEFINED
	
	Esto sucede con los siguientes:  
	HOISTING  
	var se afecta solo a la declaración  
	function se afecta por completo ( todo dentro de la función)  
	import se afecta por completo  
	class no es afectada por el hoisting

	* **picojohn** (1)

		
		muy bueno, seguire investigando mas para poder comprender el tema 😃

* **williamlopez123** (5)

	
	En pocas palabras la función declarativa, javascript la lee y la guarda en memoria y no importa donde se halla escrito (si se llama la función declarativa antes de ser creada no hay problema puesta que js las lee y las almacena pero con una función de expresión primero se crea y luego se llama)

	* **andrés eduardo betancourt bescanza** (1)

		
		genio

* **arturoperezfigueroa** (5)

	
	Entiendo la diferencia entre una y otra, pero creo que no explica lo que el título del artículo dice “Cuándo utilizar una u otra”, me refiero a que, ¿en qué casos me conviene mandar llamar la función antes de que sea declarada o viceversa?

	* **matias-alexander-ibarra-trujil** (5)

		
		yo creo que es un tema avanzado, pero basicamente es un tema de optimizar el codigo, osea es necesario que declares una funcion? la usaras mas de una vez? es probable que haya una colision de nombres en el alcance global de la funcion ?
		
		Hay algunos problemas que introduce. La primera es que tenemos que declarar una función, lo que significa que el propio nombre identificador «contamina» el ámbito de aplicación adjunto (global como ejemplo). También tenemos que llamar explícitamente a la función por su nombre para que el código envuelto realmente se ejecute.  
		Sería más ideal si la función no necesitara un nombre (o, más bien, el nombre no contaminara el ámbito circundante), y si la función pudiera ejecutarse automáticamente.

	* **hidalgolopezdaniel** (2)

		
		Arriba puse un ejemplo y otra explicación, ojalá te sirva.  
		La explicación de Matías-Alexander es acertada

* **juanchaparro9** (4)

	
	Para que al igual que yo quedaba con la duda de que es Hoisting, comparto un buen ejemplo claro para complementar:  
	<https://developer.mozilla.org/es/docs/Glossary/Hoisting>

* **dayell** (4)

	
	se aclarea un poco más en como se diferencia una de otra pero no dice en que situacionese usa una delcarativa o una empresiva???

	* **Cristobal Vega** (2)

		
		No hay como tal un caso de uso para una u otra. Como siempre dependerá de los programadores y de el producto que se esté desarrollando. Lo importante aquí es entender que V8 les da un tratamiento diferente si la función es declarativa o expresiva.

	* **hidalgolopezdaniel** (2)

		
		Si tu pones una función declarativa y antes de llamarla pones una variable “var, let, const” con el mismo nombre de la función corres el riesgo de cambiar hacia donde apunta… ejemplo:
		``` 
		    functionsaludar(nombre) {
		    	console.log(`Hola ${nombre}`);
		    }
		    
		    //Esto hace que "saludar" apunte a la variable y deje de pertenecer a la función misma
		    var saludar = 123;
		    
		    saludar('Diego');```
		     
		    **¿QUÉ ES MEJOR? --- Las Expresivas o Anónimas** (Como medida de seguridad), ya que el nombre utilizado no puede ser reutilizado dentro del código.
		```

* **matias-alexander-ibarra-trujil** (3)

	
	Nota: La manera más fácil de distinguir entre declaración y expresión es la posición de la palabra «function» en la declaración (no sólo una línea, sino una declaración distinta). Si «function» es lo primero en la sentencia, entonces es una declaración de función. De lo contrario, es una expresión de función.

* **garciafran** (2)

	
	En caso de las funciones declarativas, podemos hacerlas al final de todo el codigo de manera que al final del mismo tengamos todas las funciones, para de esta forma tener el codigo mas ordenado, miesntras que las funciones de expresión las asignamos a la variable al momento de usar, es posible que estas ultimas se usen para un momento especifico o una sola vez. Las declarativas estaran en el programa disponibles en cualquier momento

* **Christian David Sánchez** (2)

	
	 **function name(parameter1, parameter2, parameter3) {  
	// code to be executed  
	}**
	
	Los parámetros de la función se enumeran entre paréntesis () en la definición de la función.  
	Los argumentos de función son los valores recibidos por la función cuando se invoca.

* **Andres Burbano** (2)

	
	Me queda muy claro cual es la diferencia entre ambas. lo de hoisting no lo entendí pero lo investigare.

* **Kevin Vega** (2)

	
	Hoisting manera general de referirse a cómo funcionan los contextos de ejecución en JavaScript (específicamente las fases de creación y ejecución)

* **Eleazar Carreón Álvarez** (2)

	
	Creo que se refiere a esto. Podemos llamar la función con el hecho de solo ponerlo entre paréntesis la función declarativa y se ejecutará. Ya no tendríamos que llamarla como la expresiva. Esto lo puedes checar en el curso de jQuery a Javascript.  
	![platzi.jpg](https://static.platzi.com/media/user_upload/platzi-254278fd-519f-48c5-8de5-a6164ce0bf74.jpg)

* **Lorenzo David Lezcano** (2)

	
	Muy útil!

* **ZusMexSide** (1)

	
	Aquí se explica con código un poco más sobre las diferencias  
	[Enlace](https://www.desarrollolibre.net/blog/javascript/funciones-declarativas-vs-funciones-de-expresiones-en-javascript#.Xo-INMhKhEZ)

* **ZusMexSide** (1)

	
	Realmente las diferencias no fueron muy claras, ojalá alguien las pueda explicar mejor

* **Ariel Alejandro Ureña Morales** (1)

	
	Entendido, tuve que buscar que es hoisting, pero entendido. c:

* **durbonca** (1)

	
	Que es hoistin?

	* **John Steven Bernal Gonzalez** (2)

		
		Mira lo que encontré <https://developer.mozilla.org/es/docs/Glossary/Hoisting>

	* **Ariel Alejandro Ureña Morales** (1)

		
		Recuerdas que en las lecciones mencionaban que al declarar una variable o funcion se guardan en memoria hasta que sean invocadas, eso es hoisting.  
		Saludos c:

	* **ZusMexSide** (1)

		
		En el temario lo incluye bro 😉

* **kikega** (1)

	
	Ya, pero que ventajas y desventajas del uso de una u otra en el código

	* **Juan Felipe Peralta Zapata (Platzi)** (3)

		
		¡Hola! Eso se explica en las clases siguientes, o en este curso también: <https://platzi.com/clases/scope/>. 😄

	* **Ulises Antonio Sámano Galván** (2)

		
		Las funciones de expresión solo deben usarse cuando van a ser utilizadas en una o pocas ocasiones, ya que solo pueden ser ejecutadas cuando el navegador lea esa parte del código. En cambio, las funciones declarativas están disponibles siempre.

* **Pablo Rocha** (1)

	
	Gran diferencia para saber que debemos usar en cada caso de uso.

* **carlosextra1** (1)

	
	Por estos temas vale la pena tomar cursos básicos!

* **Orlando0302** (1)

	
	muy buena explicación

* **Diego Alfonso Najera Ortiz** (1)

	
	Simple pero buena explicación!

* **Alexander Montalvo** (1)

	
	Hoisting no habia escuchado esa plabra pero ahora ya la comprendo 😃

* **cristhiandelacruzperu** (1)

	
	Gracias todo muy claro por el momento.

* **John Benvin** (1)

	
	Por el momento voy entendiendo todo.  
	El curso explica todo muy bien, muchas gracias.

* **cesaraguilareduardoromero** (1)

	
	muy claro

* **johnaagudelo** (1)

	
	Super bien

* **fabio-hernan-mosquera-obando** (1)

	
	super

* **Rabi Leonel Leon Chan** (1)

	
	Entendido, tenia el concepto pero no la había entendido correctamente, es un buen articulo.

* **Germán González** (1)

	
	Excelente

* **Germán Moreno** (1)

	
	Excelente detalle.

* **marlonhmp** (1)

	
	Excelente explicacion.

* **Nestor Ruben Rodriguez Caro** (1)

	
	Muy buen aporte amigo gracias!

* **cambel24** (1)

	
	he visto el curso de fundamentos de js, y al empezar este no creí encontrar cosas nuevas, pero ya vez, este es un porque que desconocía totalmente.

	* **Javier Andres Gamboa Duarte** (1)

		
		ya somos dos

* **Jonás Onofre Durán** (1)

	
	En el curso de Fundamentos de JavaScript no se explicó a detalle este concepto sobre las diferencias de cada tipo de función, ahora ya sé las diferencias entre ellas y como usarlas mejor sabiendo su funcionamiento, excelente resumen.

* **Oveja_Gt** (1)

	
	Excelente…

* **Juan Zavala** (1)

	
	Excelente

* **Andres Giraldo** (1)

	
	ya me queda un poco mas claro el conpcepto, no se exactamente en que casos aplicarlas asi que investigare mas

	* **Aaron Gonzalez (Platzi)** (1)

		
		A medida que avances en tu carrera en JavaScript verás la aplicación precisa de cada uno. En React por ejemplo te encontrarás mucho con Funciones tipo `const name = Function();`

* **jameskristof** (1)

	
	No entiendo, las funciones de expresión tienen la palabra var, entonces se le debería aplicar hoisting ¿no?

	* **yeseniamosqueragil** (5)

		
		No, con hoisting se refiere a que el navegador va a leer la función declarativa y la va a almacenar en memoria, para de esta forma cuando tu la mandes a llamar siempre estará disponible.  
		Las funciones de expresión no son almacenadas por el navegador sino solo cuando el navegador la lee en el bloque de código que la hayas declarado como variable, por lo que si no la ha leído no podrás mandar a llamarla.

* **Bervive** (1)

	
	Un articulo para complementar lo explicado en la clase anterior

* **Lucas Ramirez** (1)

	
	voy a entender mejor el concepto en las próximas clases seguro

* **Aby Leyva** (1)

	
	Excelente resumen para diferenciarlas

* **Oscar Galicia** (1)

	
	Ya va, que es hoisting?

	* **Absalon** (4)

		
		Te comparto este enlace:  
		<https://www.w3schools.com/js/js_hoisting.asp>

	* **Gabriel De Andrade (Platzi)** (4)

		
		En esta clase lo aprendemos: [Hoisting](https://platzi.com/clases/1814-basico-javascript/26297-hoisting/) 😄

* **snowy** (1)

	
	muy bien explicado

* **Daniel Carmona** (1)

	
	Quedo más claro

* **Merlyn Rodriguez** (1)

	
	dos puntos por terminar de leer :v

# Bases de JavaScript

## 0070. Scope

### Descripción:


### Comentarios:

* **cambel24** (6)

	
	 _**variables globales: **_ Pueden ser accedidas desde un scope local o global. las variables globales son definidas fuera de las funciones (Scope global)
	
	_**Scope local: **_Son aquellas variables definidas dentro del cuerpo de la función, estas son solo accedidas desde dentro de la misma función.
	
	**_Scope Global:_** variables que pueden ser accedidas y procesadas por cualquier función dentro del código.

* **Diego Andres Cabrera Rojas** (6)

	
	Global -> Universo , seria como el todo , las variables son accesibles desde cualquier parte del código.  
	Local -> Cada Planeta , un mundo distinto , las variables son accesibles en ese mundo , no es visible para los demás mundos.
	
	Resumen : lo que es global se puede acceder desde cualquier parte de tu código , y lo pueden acceder cada mundo , lo que es local solo lo puede acceder cada mundo.😁

* **Carlos Roberto Villatoro Barrios** (5)

	
	Super fácil de entender y mas con esos ejemplos, el scope global es todo el conjunto universo, mientras que el scope local es un conjunto dentro de este universo, el cual puede tener acceso a los elementos del conjunto universo, pero el universo no puede tener acceso a los elementos del conjunto (Scope local).

* **Aldo-Salas** (5)

	
	Scope: Alcance que tienen las variables en el codigo.
	
	Existen 2 tipos de scopes.
	
	Global: Puede ser llamada a lo largo de nuestro programa.
	
	Local: Solo puede ser llamada dentro del bloque de codigo en el que se declaro.

* **Juan Carlos Valencia López** (4)

	
	Un buen desarrollador en JS sabe que es el scope y como funciona 😃

* **Orlando0302** (3)

	
	si sabia como funciona pero no sabia que se llamaba asi.

* **Christian Erik Velázquez Morales** (3)

	
	En lo personal, para no confundirme utilizo: “Var”, “CONST”, y “let”.  
	Esto, me permite diferenciarlas entre tanto código (más cuando eres principiante).  
	var: global.  
	let: Sólo vive dentro del bloque donde fue declarada.  
	CONST: Es una constante. No cambiará su valor.  
	Les comparte respuestas de la comunidad:  
	<https://platzi.com/discusiones/1099-fundamentos-javascript-2017/32001-cual-es-la-diferencia-entre-var-let-y-const/>

* **Joseph Paucar** (2)

	
	No pudo estar mejor explicado.

* **Manuel Rivera** (2)

	
	He ahí donde se genera también las diferencias en la manera de declarar una variable, ya sea con var, const o let

* **Rigo Antonio Galicia Barrera** (2)

	
	Muy buena explicación, con esto queda bien claro el tema del scope de las variables.

* **Añaqui Apolinar Morales** (2)

	
	En resumen el scope es el alcance que tienen las variables, hay 2 tipos de variables, variables locales y globales.  
	Las variables locales son las que se encuentran declaradas dentro de las funciones y solo seran usadas dentro de las funciones.  
	Las variables globales son las que se declararon fuera de las funciones pero si pueden ser usadas dentro de las funciones ya que existen de manera global en todo el codigo

* **Karla Agraz** (2)

	
	Muy buena la explicación 😁

* **vickiavola** (2)

	
	Excelente el ejemplo de las hormigas

* **matias-alexander-ibarra-trujil** (2)

	
	Recomiendo hacer este ejercicio
	
	* * *
	``` 
	    functionfoo(){
	    	console.log(a)
	        a=5
	    }
	    foo()
	    console.log(a)````
	    ***
	    `var a = 4
	    functionfoo(a){
	    	console.log(a)
	        a=5
	    }
	    foo(a)
	    console.log(a)`
	```

* **Mirna Mabel Veras Carvajal** (2)

	```
	    //El alcance (scope) de una variable puede ser:
	    //1- Global:
	    var miNombre = "Diego";
	    
	    //2- Local:
	    functionnombre(){
	        var miApellido = "De Granda";
	        console.log(miNombre + " " + miApellido);
	    }
	    
	    nombre(); //Devuelve "Diego De Granda"
	    
	    //En todo el código podemos utilizar la variable global.
	    //Las variables locales sólo pueden ser accedidas 
	    //dentro de la función en la que fueron declaradas.
	    
	```

* **Cristian Rivera Herrera** (2)
Me encantó la explicación, sabía lo práctico, pero no sabía el nombre por el cual se le llamaba... Scope. Progresando en Javascript. PD: AntMan si puede.

	* **Gabriel De Andrade (Platzi)** (3)

		
		Si quieres profundizar en este tema tenemos el [Curso de Closures y Scope en JavaScript](https://platzi.com/clases/scope/) 😄

	* **Cristian Rivera Herrera** (1)

		
		Excelente, gracias @GabrielElpidio, estaré tomando el curso en cuanto termine este y el de ECMAScript 6+

* **Merlyn Rodriguez** (2)

	
	dos puntos por terminar de ver el video :v

* **ignacioaredez** (1)

	
	Por un momento pensé que estaba en el national geographic

* **diegopagini** (1)

	
	Muy buen profe, muy claro

* **Brayhan Andres Jaramillo Castaño** (1)

	
	Es un concepto muy importante a tener en cuenta cuando se esta desarrollando, como tambien de mucho cuidado pues en ocasiones se suele alterar ese valor global sin querer, y generar confusiones.

* **ZusMexSide** (1)

	
	Espero no confundirlos, aclaro que scope = ámbito.  
	Cuando tenemos **var** en el **ámbito de bloque** (dentro de un if o for), éste expande su alcance al **ambito local** ( dentro de la misma función pero fuera del if). Cuando usamos **let** bloqueamos el alcance en donde se este declarando, en este caso dentro del if. ![Anotación 2020-04-09 154938.jpg](https://static.platzi.com/media/user_upload/Anotaci%C3%B3n%202020-04-09%20154938-1e7dca17-e43f-4e5d-b6ad-c917b42fe1d8.jpg)

* **Ulises Antonio Sámano Galván** (1)

	
	Scope es como una ciudad, todo mundo puede caminar libremente, sin embargo nadie mas puede entrar a tu casa o saber lo que ocurre en ella.

* **Ariel Alejandro Ureña Morales** (1)

	
	Gracias por las expicaciones y las analogías, me ha quedado claro con el ejemplo de los humanos y las hormigas.

* **John Steven Bernal Gonzalez** (1)

	
	Que buena explicación me gusto mucho esta clase!

* **garciafran** (1)

	
	Excelente explicacion.  
	En resumen el scope local tiene acceso a si mismo y al global.  
	El scope global solo tiene acceso a si mismo.

* **Pablo Rocha** (1)

	
	Como se dice en España, lo bueno y breve dos veces bueno 😃 buena explicación

* **carlosextra1** (1)

	
	Excelente explicación!

* **eduvra** (1)

	
	Wow, super bien explicado en 7 minutos.

* **Sthepha04** (1)

	
	Super!! 😄

* **Ginnio Sarabia** (1)

	
	Está bien explicado.
	
	Ya los conceptos ya los tengo conmigo con anterioridad.

* **Jeisson Santiago Cortes Ortiz** (1)

	
	…

* **cesaraguilareduardoromero** (1)

	
	//el scope local puede acceder a lo que tengo en scope global  
	// el scope global no puede acceder a lo que esta en scope local

* **picojohn** (1)

	
	lo que entiendo es que depede como necesitemos una variable, si la quero para todo el aplicativo la hago global, si la necesitamos para algo mas puntual la hago local 😃

	* **arturomauricio** (1)

		
		Perfecto!! y ten en cuenta el alcance de esas dos variables, eso es el scope

* **Matías Criado** (1)

	
	Tomar el curso de [Fundamentos de JS](https://platzi.com/clases/fundamentos-javascript/) y luego este ha sido de gran ayuda para comprender de mejor manera el lenguaje. Recomiendo mucho tomar ambos, para luego prácticar con mayor seguridad.

* **victor-castaneda-rivera** (1)

	
	cuando genero una función, genero un scope local?

	* **Marco Antonio Ortega** (1)

		
		Así es, lo que se enmarca en la función es scope local, pero podes tomar variables globales y esas entran como scope global (:

* **Germán Moreno** (1)

	
	Entendido.

* **marlonhmp** (1)

	
	Entendido lo de Scope

* **Christian David Sánchez** (1)

	
	 **Scope en JavaScript**  
	En JavaScript hay dos tipos de alcance:
	
	  * Alcance local
	
	  * Alcance global  
	JavaScript tiene un alcance de función: cada función crea un nuevo alcance.
	
	
	
	
	El alcance determina la accesibilidad (visibilidad) de estas variables.
	
	Las variables definidas dentro de una función no son accesibles (visibles) desde fuera de la función.

* **andrés eduardo betancourt bescanza** (1)

	
	Como hacer para que la consola, se vea como el editor de codigo?

	* **Gabriel De Andrade (Platzi)** (3)

		
		Lo que tienes es que buscar temas parecidos para la consola y el editor de código, va a variar mucho dependiendo de los programas que utilices para estos dos 😛

	* **sotecnar** (4)

		
		En los 3 puntos que aparecen en las herramientas de desarrollador, settings, theme: dark theme.

	* **Laurapregonero** (1)

		
		instala Run code desde la Terminal , después de ya a ver hecho eso , abre Visual Studio Code , le das click derecho y de primeras te va aparecer algo que dice Run Code y allí ya te va a parecer la consola. aparte te ayudara a correr de una vez el codigo.

	* **FredyColorado** (2)
![Captura16.PNG](https://static.platzi.com/media/user_upload/Captura16-723dc1ac-1638-4efc-aeef-3e34f6e035bc.jpg)

* **Jhon Alexander Romero Gonzaga** (1)

	
	Muy fácil y rápido de entender!

* **Raundy Ibarras** (1)

	
	Súper buena la explicación!

* **Juan Zavala** (1)

	
	Interesante

* **JheysonEGalvis** (1)

	
	“En el scope local podemos tener acceso a las variables que están en el scope globlal”.

* **Carlos Bueno Tavares** (1)

	
	Scope es el alcanze de una variales hay dos tipos de scope:  
	Scope global = todo el archivo tendra acceso a estas variables.  
	Scope local = son variables internas de funciones.

* **Andres Giraldo** (1)

	
	me quedo claro, una variable tiene un cierto alcance o ámbito.  
	global: donde están todas la variables en general.  
	local: donde hacen parte de una función.  
	desde la función las variables locales (las que estan dentro de la función) pueden acceder a las globales, pero las variables globales no pueden acceder a las variables locales

* **Carlos Sanchez** (1)

	
	Excelente ejemplo el de las hormigas, esta buenísimo el curso.

* **estefaniajmedina** (1)

	
	Excelente ejemplo con las hormigas

* **Steven Angel Coaila Zaa** (1)

	```
	    //////////////////////////
	    // Scope
	    
	    var miNombre = 'Steven';
	    
	    functionnombre() {
	      var miApellido = 'Coaila';
	      console.log(`${miNombre}${miApellido}`);
	    }
	    
	    nombre(); // Steven Coaila;
	    
	    console.log(miNombre); // Steven 
	    console.log(typeof miApellido); // Error & undefined```
	    
	```

* **lmoran** (1)

	
	Explica muy bien, con ejemplos que todos entendemos.

* **Kevin Vega** (1)

	
	Los Scope se pueden superponer en una jerarquía, de modo que los Scope secundarios tengan acceso a los ámbitos primarios, pero no al revés.

* **ferchodleon** (1)

	
	Que buena clase!!

* **Bervive** (1)

	
	Scope, global y local, mientras que el scope local puede acceder al scope global, no sucede lo mismo al contrario. Got it!

* **Francisco de Jesus** (1)

	
	Muy bien explicado!!

* **Daniel Carmona** (1)

	
	Me faltaba definir bien que era scope

* **savier687** (1)

	```
	    //Scope Global
	    var nombre = "Saviel";
	    
	    //Scope Local
	    function fun() {
	        var apellido = "Martinez";
	        return nombre + " "+apellido
	    }
	    
	    fun();
	    
	    
	    //El Resultado sera "Saviel Martinez"
	    // Podemos acceder al Scope Global desde cualquier parte
	    // Solo podemos acceder al Scope Local desde dentro de la funcion donde se declaro ```
	    
	```

* **Marlon Fabian Pineda Jaimes** (1)

	
	Excelente explicación.

* **victor-castaneda-rivera** (1)
Puedo tener un scope local dentro de otro scope local?

	* **Manuel Rivera** (2)

		
		Claro, pero no necesariamente sería scope local dentro de scope local, el scope local es el scope donde esta lo que tu declaraste y recuerda, podemos acceder del scope local al scope global pero nunca al reves. Saludos 🚀…

* **Nicolas David Pastran Zamora** (1)
Las variables o funciones que están en scope global pueden ser accedidas desde otro archivo javascript diferente del que se declaran ?

	* **Ruben Padilla** (2)

		
		Si pueden ser accedidas desde un archivo diferente, para realizar esto debes entender el concepto de modularización. Te comparto el enlace a la documentación:
		
		<https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules>

## 0080. Hoisting

### Descripción:


### Links:

* [Curso de ECMAScript 6+](https://platzi.com/clases/ecmascript-6/)

* [Hoisting - Glosario | MDN](https://developer.mozilla.org/es/docs/Glossary/Hoisting)

* [¿Qué es el hoisting? - Ana Martínez Aguilar - Medium](https://medium.com/@anamartinezaguilar/qu%C3%A9-es-el-hoisting-327870f67b36)

### Comentarios:

* **Jhon Alexander Romero Gonzaga** (14)

	
	Profe Sacha Lyfszic: <https://www.youtube.com/watch?v=uI6o97A4IrI>

* **Oveja_Gt** (9)

	
	¿Qué es Hoisting?  
	En JavaScript, las declaraciones (por ejemplo, de variables o funciones) se mueven al principio de su scope o ámbito. Este comportamiento se conoce como hoisting y es muy importante tenerlo en cuenta a la hora de programar para prevenir posibles errores.
	
	  * Las funciones siempre se mueven arriba del scope. Por lo tanto, podemos elegir donde declararlas y usarlas.
	  * La declaración de las variables se mueven arriba del scope, pero no la asignación. Antes de usar una variable, habrá que crearla y asignarla.
	
	

* **Cristobal Vega** (7)

	
	FUN FACT: El concepto de Hoisting en inglés se refiere a “izar”, es decir elevar un objeto. Como una bandera o con estas cosas:
	
	![](https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.birdladder.com%2Fecomimages%2F1406046931.jpg&f=1&nofb=1)

* **Karla Agraz** (5)

	
	Hoisting es cuando las variables y las funciones se declaran antes de que se procese cualquier tipo de código. El Hoisting funciona de ECMAScript 5 para abajo, de ECMAScript 6 en adelante no sucede porque el Hoisting sucede con var y function. En las versiones de ECMAScript 6 en adelante aparece const y let.

* **garciafran** (3)

	
	interesante el concepto de hoisting.  
	en resumen.
	``` 
	    //aqui se da el hoisting en las variables
	    //donde la variable es usada antes de ser declarada
	    //
	    console.log(miNombre);
	    var miNombre = "Francisco";
	    
	    hey();
	    
	    functionhey() {
	        console.log("hola " + miNombre);
	    }
	    
	    var miNombre = "Francisco";
	    
	    //Lo ideal es que se declaren la funcines al inicio
	    
	```

* **juanlondono** (3)

	
	2 puntos por ser el primero en escribir

* **JheysonEGalvis** (2)

	
	“Las funciones se declaran antes que las variables”

* **Matias Alejandro Lopez Heredia** (2)

	
	En resumen:
	
	  1. 
	
	
	Mostrar en pantalla una variable no definida, provocará un error:
	``` 
	    console.log(nombre);
	    
	```
	
	La consola muestra: ReferenceError: nombre is not defined  
	Este error corta la ejecución del programa.
	
	  1. 
	
	
	Declararla después de utilizarla, provocará que el valor en ese momento de la variable sea undefined
	``` 
	    console.log(nombre);
	    var nombre = "Matias";
	    
	```
	
	La consola muestra: undefined, esto no corta la ejecución del programa.  
	Nota: Esto solo ocurre con la palabra reservada var, si utilizan let o const obtendrán un error: Cannot access ‘nombre’ before initialization, y la ejecución del programa se vera interrumpida.
	
	Espero les sirva.

* **David Emanuel Espinoza Romero** (2)

	
	por si a alguien le queda alguna duda lea este post, espero le sirva igual que a mi o mas <https://www.jasoft.org/Blog/post/Elevacion-de-variables-(hoisting)-en-JavaScript.aspx>

* **Orlando0302** (2)

	
	jejjeje super entendido.

* **Ronal Aguirre** (2)

	
	no podria ejecutarse, saldria “undefined”

* **davidhdez8** (2)

	
	Undefined.

* **cambel24** (2)

	
	9:57 ERROR… aun no concatenas el “hola” con la variable

* **Israel Castro Urieta** (2)

	
	Perdí la cuenta de las veces que tuve que regresar y repasar los ejemplos y las definiciones de este vídeo hasta que me quedara completamente claro. ¡Excelente clase!

	* **pabloverduzcos** (1)

		
		Te dejo el vídeo de otro profesor de Platzi que explica el tema de una manera muy simple: <https://youtu.be/uI6o97A4IrI>

	* **Israel Castro Urieta** (1)

		
		Muchas gracias por el aporte @pabloverduzcos fue simple por la parte en la que vimos en esta clase (sobretodo por los gráficos), además se incluyeron mas conceptos y casos.

* **Kevin Vega** (2)

	
	Hoisting: Cuando las Variables y funciones se declaran antes de la ejecución del código  
	Creo que para el ejercicio saldrá undefined, ya que está imprimiento una variable que no declaro o bueno no ha tomado valor…creo

* **Isam David Espinosa Flores** (2)

	
	Esta información podría complementar lo explicado en el vídeo por si quieren ver otros ejemplos <https://developer.mozilla.org/es/docs/Glossary/Hoisting>

* **AlexanderAReyes** (2)

	
	Por cierto, como mi pc tenia mala la fecha y hora, ya envié el comentario de mis respuestas pero parece que estoy en el futuro. 🤣😎
	
	_Solo es para agregarle humor al curso_
	
	![raroFuturo.png](https://static.platzi.com/media/user_upload/raroFuturo-fff9289c-70b0-4a54-b179-1909f2af118d.jpg)

* **Manuel Rivera** (2)

	
	En el caso de la función, el output es que la función si se va a ejecutar, pues lo que he aprendido en otros cursos es que siempre las funciones se leen primero ya que al leerlas se les reserva un espacio en memoría, después se vuelve al inicio y hay si se lee el resto del codigo, siempre en el orden de arriba hacia abajo, pero por buena práctica o me parece que se mira mejor, declarar e inicializar primero antes de llamar, tanto para variables como para funciones.

* **Enrique Alexis Lopez Araujo** (2)

	
	Hola @degranda no vi en la parte de enlances la lectura acerca de hosting, saludos!

* **Oscar Galicia** (2)

	
	Antes de que corra el video: Pienso que a la hora de correr el codigo primero se van a buscar las funciones y luego se van a procesar donde se hayan declarado… A ver si tengo razon.

* **Marlon Fabian Pineda Jaimes** (2)

	
	Si se intenta llamar una variable antes de poderla definir, simplemente va a arrojar un error diciendo que la variable no esta definida.

	* **Camilo Alexander Velandia Velandia** (2)

		
		de hecho no da un error, esto crea la variable y la declara como undefined

* **ZusMexSide** (1)

	
	error

* **Brayhan Andres Jaramillo Castaño** (1)

	
	undefined

* **DanielCu** (1)

	
	Hola undefined

* **Ulises Antonio Sámano Galván** (1)

	
	  1. Undefined.
	  2. Undefined
	
	

* **Jesús David Cuéllar Ortiz** (1)

	
	1- undefined  
	2-Un error primero porque se te olvido el + ¿No? y luego undefined tambien

* **crimiro** (1)

	
	  1. Undefined
	  2. Hola undefined  
	Ya conocía el tema pero no sabía que tenía nombre (Hoisting)
	
	

* **RemyLebeau** (1)

	
	Las declaraciones de variables o funciones se mueven al principio de su scope o ámbito. Es muy importante tenerlo en cuenta a la hora de programar para prevenir posibles errores.
	
	Teniendo en cuenta cómo funciona el hoisting, podemos llamar a una función y definirla más abajo, porque automáticamente JS la “subirá”.

* **edwin-rafael-pimienta-calderon** (1)

	
	Escribe ****Hola Diego ****porque el buscara el nombre de la función en cualquier lugar donde este declarada

* **Pablo Rocha** (1)

	
	undefined

* **carlosextra1** (1)

	
	Excelente explicación profesor!! Felicidades!

* **carlosextra1** (1)

	
	Porque js manda undefined!

* **eduvra** (1)

	
	Woo, pensé que iba a ser mucho más complejo de entender.

* **miguelgz18** (1)

	
	undefined

* **MATTHEUV OSORIO** (1)

	
	undefined

* **Jharell Alejandra Hidalgo Loya** (1)

	
	undefined

* **Ginnio Sarabia** (1)

	
	hey();
	
	pienso que va a decir que la función hey() no esta definida.
	
	Luego si la define.

* **rsalamanca** (1)

	
	Es muy interesante este tema del hoisting la verdad no tenia ni idea q existia

* **Jeisson Santiago Cortes Ortiz** (1)

	
	😦

* **Migrant** (1)

	
	Lo siento, pero debo decirlo. Me tiembla el ojo izquierdo cada que dices “mandar llamar” Diego

* **Ronal Aguirre** (1)

	
	también seria undefined, porque se lee primero la función antes de que se realice el proceso de que esta en la función

* **Germán González** (1)

	
	Genial.

* **picojohn** (1)

	
	muy buena clase

* **victor-castaneda-rivera** (1)

	
	Pasos para usar una variable:
	
	  1. se declara una variable
	  2. se inicializa una variable
	
	

* **Germán Moreno** (1)

	
	Genial.

* **marlonhmp** (1)

	
	Ahora si entendi lo de hoisting

* **jaguarjs** (1)

	
	Las variables y las funciones se procesan antes de ejecutar cualquier código, pero las funciones se declaran antes que las variables

* **Danelia Sanchez Sanchez** (1)

	
	Sale undefined

* **Christian David Sánchez** (1)

	
	 **Hoisting** es el comportamiento predeterminado de JavaScript de mover las declaraciones a la parte superior.
	
	En JavaScript, una variable se puede declarar después de que se haya utilizado. En otras palabras; una variable se puede usar antes de que se haya declarado.
	
	**Ejemplo:**
	``` 
	    x = 5; // Assign 5 to x
	    
	    elem = document.getElementById("demo"); // Find an element
	    elem.innerHTML = x;                     // Display x in the element
	    
	    var x; // Declare x
	    
	```

* **Ines Patricia Contreras Espiritu** (1)

	
	undefined

* **Wandy Rafael Santana Evangelista** (1)

	
	Aprendi mucho sobre esto del hoisting, y de lo importante de conocer las buenas practicas.

* **Gustavo Adolfo Paz Solorzano** (1)

	
	Excelente clase!

* **Mayco Busto** (1)

	
	4:08 primero lo primero!!  
	Declarar  
	Inicializar  
	Llamar

* **cambel24** (1)

	
	4:50 Creo sera undefined, recordando la forma en como javascript ejecuta el código, linea tras linea. _“creo primero reconocerá una variable sin inicializar y luego asignara el valor a esta.”_

* **Juan Zavala** (1)

	
	No entendí que paso en el minuto 8:35, como imprime el nombre “Diego” si esta inicializado la variable después del console.log ??

	* **Gabriel De Andrade (Platzi)** (1)

		
		En el min 08:35 lo que pasa es que se define la variable `miNombre` pero se le asigna el valor `undefined`, cuando se ejecuta el `console.log()` imprime`"undefinedSoy ese hoisting"` porque la variable se declaró pero se le asignó el valor undefined. Luego aparece “Diego” porque es lo que devuelve la consola de Chrome cuando le asignas un valor a una variable. 😄

	* **cambel24** (1)

		
		El ‘Diego’ que vez debajo del undefined, es el retorno del dato que acabas de poner en la variable miNombre.

* **David Vargas Domínguez** (1)

	
	Lo que hace el hoisting es ejecutar nuestras declaraciones de variables y funciones antes que lo demás.
	``` 
	    // lo que pones
	    var foo = 'bar';
	    
	    
	    // lo que javascript interpreta
	    var foo = undefined;
	    foo = 'bar';
	    
	```

* **Juan Camargo** (1)

	
	sale undefined

* **SEBASTIAN PADUANO** (1)

	
	sale un error en la función

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Puedes dar mas información para poder ayudarte.

* **Bárbara de los Ángeles Morantes Carvajal** (1)

	
	Si colocas el console.log(miNombre); antes de declarar la variable saldría undifined, porque miNombre no esta definida aún.

	* **Bárbara de los Ángeles Morantes Carvajal** (1)

		
		Si se va a ejecutar la función porque JS, lee primero todo el código y almacena las funciones en memoria y luego enecuta el código linea a linea y al llegar al llamado de la función ya va estar cargada.

* **Renato Maximiliano Rivera Abad** (1)

	
	Saldría null ¡?

* **estefaniajmedina** (1)

	
	Aparece undefined

* **pablohugomontenegro** (1)

	
	5:02 --> a mi me apareció Diego y abajo undefined

* **Leonardo Bravo Kunkel** (1)

	
	En la segunda pregunta, me imagino que lanzaría un “undefined” porque lee una función vacía y luego lanzaría “Hola Diego” porque leería la segunda función.

* **Leonardo Bravo Kunkel** (1)

	
	De acuerdo a la primera pregunta que realizaste, supongo que se desplegaría un “undefined”, porque se estaría leyendo el log y luego se declara la variable.  
	Saludos.

* **Eduardo Zamarron Muñoz** (1)

	
	Hola, a la fecha de este comentario falta el artículo en la sección de enlaces (:

	* **Gabriel De Andrade (Platzi)** (2)

		
		Hola! Ya lo reporté con el equipo y ya puedes encontrarlos en la sección de enlaces, gracias por el reporte 😄

* **Aldo Miguel García Barrios** (1)

	
	Tomando como base le primer ejemplo creo que saldrá undefined

* **chavwilh_platzi** (1)

	
	Yo lo que entendí es que se debe declarar o inicializar primero las variables antes de ejecutar la función. Si no lo hacemos así se genera el Hoisting el cual le asigna un “undefined” a la función que estemos ejecutando y se evita que se genere un error por ejecutar funciones si la declaración de sus variables previamente, sin embargo este resultado nos puede confundir sobre lo que esta sucediendo, por tal razón debemos mantener un orden en la programación de nuestras funciones

* **hidalgolopezdaniel** (1)

	
	"SIEMPRE" Declarar al inicio del código las funciones y mandarlas llamar en donde las necesitemos. Esto para evitar Hoisting. \--BUENAS PRÁCTICAS

* **Bervive** (1)

	
	El tema no es fácil de explicar pero con ejemplos todo se vuelve cada vez mas claro, gracias.

* **Francisco de Jesus** (1)

	
	Muy bien explicado rapido y con ejemplos claros!!

* **Pablo Domínguez Durán** (1)

	
	 **Hoisting** es el comportamiento por defecto de JS de mover declaraciones al prinicipio.
	
	<https://www.w3schools.com/js/js_hoisting.asp>

* **hidalgolopezdaniel** (1)

	
	¿Es como cuando ordenas un archivo de estilos CSS … primero Body, IDs, Clases etc?

* **AlexanderAReyes** (1)

	
	Para evitar el hoisting debemos **declarar las funciones al inicio de nuestro archivo** y **las variables después de todas las funciones a usar**.

* **AlexanderAReyes** (1)

	
	Al escribir en la consola
	``` 
	    hey();
	    
	    functionhey(){
	    	console.log("Hola " + nombre);
	    }
	    
	    var nombre ="Diego";
	    
	```
	
	va a ejecutar la función normalmente pero el valor de la variable será `undefined`, así que mostrará:
	
	`Hola undefined`

* **AlexanderAReyes** (1)

	
	Al escribir en la consola
	``` 
	    console.log(miNombre);
	    
	    var miNombre = "Diego";
	    
	```
	
	devolverá `undefined` ya que al momento de leer esta variable no tendrá un valor asignado

* **Manuel Rivera** (1)

	
	El output va a ser un error, ya que el archivo se va a leer de arriba hacía abajo y de derecha a izquierda, por ende estamos queriendo mostrar una variable que aún no existe, pienso yo

* **Ramón Ruiz** (1)

	
	Yo creo que se va a ejecutar la función de todas formas.

* **Almu_timkerbell** (1)

	
	Entiendo el concepto, pero al igual que hay que declarar las variables al principio, ¿no es también considerado “buena práctica” declarar primero la función y después llamarla? Ahora me queda la duda…

* **Javier Armando Vargas Vega** (1)

	
	Cuando se llama primero la función, antes de ser declarada, esta se ejecuta de manera normal.

* **Lucas Ramirez** (1)

	
	Una clase muy productiva , es un tema que no sabía

* **fjaraujo** (1)

	
	Si no esta definida la variable antes de llamarla creo que arroja UNDEFINED

	* **Gabriel De Andrade (Platzi)** (2)

		
		Si no está declarada te arrojará un error, si no le asignaste ningún valor te arrojará undenfined 😄

* **Mirna Mabel Veras Carvajal** (1)

	```
	    //Ejemplo 1: Llamando la variable antes de declararla
	    console.log(miNombre);
	    var miNombre = "Diego"; //Esto genera undefined
	    
	    //Ejemplo 2: Llamando la función y la variable antes de declararlas
	    hey();
	    functionhey() {
	        console.log("Hola " + miNombre2);
	    }
	    
	    var miNombre2 = "Diego"; //Aquí la función se ejecuta, pero genera undefined en el caso de la variable
	    
	```

* **Merlyn Rodriguez** (1)

	
	dos puntos por terminar de ver el video :v

* **snowy** (1)

	
	al ejecutarlo enviara el mensaje que miNombre no esta declarado ya que en js se lee linea por linea

* **savier687** (1)

	
	Al ejecutar el el console.log sin estar definida la variable antes nos arrojara UNDEFINED ya que Js es un lenguaje interpretado por ende lee linea por linea, el explorador ejecuta el codigo de arriba hacia abajo

* **Daniel Carmona** (1)

	
	Esto si no lo había visto

* **Jonathan Vacas** (0)

	
	  1. Undefined
	  2. Undefined
	
	

* **Eduardo Neptali Benso Pasquel** (0)

	
	undefined

## 0090. Coerción

### Descripción:


### Comentarios:

* **Carlos Bueno Tavares** (8)

	
	Coerción es la forma en la que podemos cambiar un tipo de valor a otro, existen dos tipos de coerción:  
	Coerción implícita = es cuando el lenguaje nos ayuda a cambiar el tipo de valor.  
	Coerción explicita = es cuando obligamos a que cambie el tipo de valor.

* **Cristobal Vega** (8)

	
	Como dato extra, en JavaScript tenemos 8 tipos de datos únicamente en 2020:
	``` 
	        Boolean
	        Null
	        Undefined
	        Number
	        BigInt
	        String
	        Symbol
	    
	```
	
	y el valor Object.
	
	Si quieren aprender más de los tipos de dato les recomiendo el libro gratuito no 3 del autor Kyle Simpson.
	
	👇  
	<https://github.com/getify/You-Dont-Know-JS/tree/2nd-ed/types-grammar>

	* **Pablo Domínguez Durán** (2)

		
		Súper dato!

* **Karla Agraz** (8)

	
	  * Coerción implícita: Es cuando el lenguaje nos ayuda y cambia de un tipo de valor a otro tipo de valor.
	
	
	
	-Coerción explícita : Es cuando nosotros obligamos a un valor de un tipo a cambiar a otro tipo.

* **Carlos Roberto Villatoro Barrios** (6)

	
	ParseInt vs Number
	
	ParseInt: Analiza la cadena desde el primer dígito, hasta que encuentre algo que no sea dígito y devuelve lo que haya analizado.  
	Ejemplo:  
	parseInt(“123hui”) //123  
	Number: Busca convertir toda la cadena en un número, por lo que al encontrarse con un elemento que no sea diginto nos dara como resultado NAN.  
	Ejemplo:  
	Number(“123hui”) //NaN
	
	Cada día se aprende algo nuevo, no pierdas esa oportunidad y no pares de aprender.

* **Juan Zavala** (4)

	
	Todos los días se aprende algo nuevo, por muy pequeño que sea. Excelente !

* **Mirna Mabel Veras Carvajal** (4)

	```
	    //Ejemplos de Coerción:
	    
	    var a = 4 + "7"; //Convierte a 4 en un string y lo concatena con el "7", por esto regresa un string de valor "47"
	    
	    4 * "7"; //Convierte al "7" en un número y realiza la operación, por esto devuelve 28
	    
	    var a = 20;
	    var b = a + ""; //Aquí concatenamos para convertir la variable a string (coerción implícita)
	    console.log(b); 
	    
	    var c = String(a); //Aquí obligamos a la variable a convertirse en string (coerción explícita)
	    console.log(c);
	    
	    vard = Number(c); //Aquí obligamos a la variable a convertirse en número (coerción explícita)
	    console.log(d);
	    
	```

* **JheysonEGalvis** (2)

	
	Hay dos tipos de coerciones  
	**Coerciones implícitas**  
	Cuando el lenguaje nos ayuda y cambia de un tipo de valor a otro tipo de valor.  
	**Coerciones explísitas**  
	Es la forma en que nosotros obligamos a que un valor de un tipo cambie a un valor de otro tipo.

* **Jeisson Santiago Cortes Ortiz** (2)

	
	Es muy similar o practicamente igual al casteo de java, por ejemplo:
	
	Double numero = 0;  
	String cadena="";  
	cadena = (String) numero;

* **Luis Diego Maroto Segura** (2)

	```
	    /*
	    Hay dos tipos de coerciones: implicitas y explicitas.
	    */
	    
	    // Ejemplo de coerción Implicita
	    var a = 4 + "7"
	    console.log(a + " --> " + typeof(a)); // Lo que ocurre es una concatenación.
	    
	    var b = 4 * "7"
	    console.log(b + " --> " + typeof(b)); // Lo que ocurre es una multiplicación.
	     
	    // Ejemplo de coerción Explicita
	    var n1 = 20; // numero
	    var s1 = n1 + ""// cadena
	    
	    var s2 = String(n1); // cadena
	    console.log(s2 + " --> " + typeof(s2)); // Coerción explicita.
	    
	    var n2 = Number(s1); // numero
	    console.log(n2 + " --> " + typeof(n2)); // Coerción explicita.
	    
	```

	* **eduvra** (1)

		
		Buen resumen compañero!

* **Christian David Sánchez** (2)

	
	 **¿Que es coerción?**  
	Se podría decir que coerción es la acción de forzar a que un objeto se comporte como si fuera de otro tipo.

* **gonzaloPzl** (2)

	
	La coerción se da cuando se cambie de un tipo de valor a otro, hay 2 tipos de coerciones las **Implicitas** y las **Explicitas** , las primeras ocurren cuando este cambio es sin que intervengamos y la segunda es cuando forzamos ese cambio.

* **Francisco de Jesus** (2)

	
	Muy interesante lo de la coerción implicita

* **Manuel Rivera** (2)

	
	2 tipos de scope: Global y local  
	2 tipos de funciones  
	2 tipos de coerción: implcita y explicita

* **Javier Téllez** (2)

	
	Coerción implicita es cuando JS nos ayuda a definir el tipo de variable, y la coerción explicita es cuando nosotros le decimos a JS en que tipo de variable almacenaremos nuestros valores.

* **Daniel Carmona** (2)

	
	Me gusto

* **Ulises Antonio Sámano Galván** (1)

	```
	    La coerción es la acción de cambiar un tipo de valor a otro, por ejemplo, un string a un número y viceversa.
	    
	    Existen 2 tipos de coerción:
	    
	```
	
	  1. Implícita: Es cuando el mismo lenguaje realiza la coerción.
	  2. Explicita: Ocurre cuando nosotros le indicamos al lenguaje que cambie el tipo de valor.
	
	

* **Ulises Antonio Sámano Galván** (1)

	
	Si quieren profundizar más en el tema de coerción [Vean este enlace](http://www.etnassoft.com/2011/04/06/coercion-de-datos-en-javascript/)

* **John Steven Bernal Gonzalez** (1)

	
	Con coercion explicita obligamos a cambiar de un tipo de valor de numero a un string usamos el metodo String() dentro de los paréntesis ubicamos la variable.

* **Ariel Alejandro Ureña Morales** (1)

	
	Excelente clase.

* **jameskristof** (1)

	
	¿Es como el parseInt?

* **durbonca** (1)

	
	Para eso no están los atributos de HTML5 de type en los inputs?

	* **Jesús David Cuéllar Ortiz** (1)

		
		Sí, pero solo toman los datos y JS generalmente los vuelve string.

* **carlosextra1** (1)

	
	Muy bien explicado!!

* **David Flores** (1)

	
	a ese tipo de coerción explícita yo la conocía como casteo (cast de datos)

* **picojohn** (1)

	
	tiene buenos trucos javascript

* **Juan Esteban Galvis** (1)

	
	El profesor pasaba de String a numero o viceversa con otra variable, pero también se puede en la misma variable:
	
	var a = 3 -> Número  
	a = String(a) -> Convierto “a” en String  
	a = Number(a) -> Vuelvo a convertir “a” en número
	
	Por cierto, Javascript si realiza las operaciones básicas entre numero y string (resta, multiplicación, división y otras más) pero el + lo toma como concatenar. Obviamente al operar 3 * “A” saca NnN (Not a Number).

* **Germán Moreno** (1)

	
	Genial.

* **marlonhmp** (1)

	
	Muy util saber esto.

* **Jair Israel Avilés Eusebio** (1)

	
	Una duda, cuando se cambio el valor de un number a un string ¿por que al imprimirlo en el navegador este no muestra las comillas? Es solo curiosidad
	``` 
	    var a = 20;
	    var b = String(a);
	    
	    console.log(b) // ¿Por que se imprime como 20 y no "20" ? 
	    
	```

	* **Juan Camilo Alvarez Jurado** (2)

		
		Cuando lo imprimes con console.log simplemente muestras texto en consola. No mostrarás comillas a menos que éstas hagan parte explícitamente del contenido de la cadena de caracteres.
		
		Por ello, si haces **console.log(“hola”)** te muestra hola sin comillas.
		
		Para incluir las comillas como parte de una cadena de caracteres tienes dos opciones:
		
		escapar el caracter comilla doble con contraslash (\\)  
		var cadena = “\“ejemplo\””
		
		usar comilla simple (puse espacios en medio para que se viera, estos no se necesitan)  
		var cadena = ’ “ejemplo” ’
		
		Vemos comillas de una variable de cadena de caracteres cuando simplemente la ponemos en la consola sin **console.log** (por ejemplo, escribes cadena y le das Enter), con lo que identificamos rápidamente de si se trata o no de una cadena (en ese caso sí pone comillas)

* **Jhon Alexander Romero Gonzaga** (1)

	
	me sabia que con parseInt() se podia cambiar a entero, y con toString() a un string, pero esta clase me deja claro mas cosas.

* **Leonardo Bravo Kunkel** (1)

	
	Muy útil la información. Gracias.

* **Eduardo Zamarron Muñoz** (1)

	
	¿Es decir que la coerción y el casting son lo mismo?

	* **Diego Alexander Forero Higuera (Platzi)** (4)

		
		Si, coerción y casteo de datos es lo mismo.

* **Valente IA** (1)

	
	Coerción: sería lo que en otros lenguajes de programación es la conversión (implícita, explícita)

* **lmoran** (1)

	
	Entendible.

* **Kevin Vega** (1)

	
	Coerción: Forma en qué podemos cambiar un tipo de valor  
	Coerción Explicíta: Es cuando obligamos a que cambié el valor

* **hidalgolopezdaniel** (1)

	
	Ejemplo de coerción explicita: var a = 1 + "2" var b = Number(a) var c = 1 * 2 var d = String(c)

* **Bervive** (1)

	
	Me quedaron claro los 2 tipos de coerciones, Aunque siento que a este curso le falta hacer mas actividad practica escribiendo código, menos como ejemplos y mas en sentido de proyectos.

	* **Eduardo Zamarron Muñoz** (4)

		
		Pásate por el curso de Fundamentos de JavaScript, ahí ya hay un proyecto (:

* **Rigo Antonio Galicia Barrera** (1)

	
	Tambien puedes convertir a un timpo mas especifico como un entero con la funcion parseInt()

* **diego rodriguez** (1)

	
	buena explicacion

* **Merlyn Rodriguez** (1)

	
	dos puntos por terminar de ver el video :v

## 0100. Valores Truthy y Falsy

### Descripción:


### Comentarios:

* **Mirna Mabel Veras Carvajal** (15)

	```
	    //Ejemplos en los que Boolean devuelve Falso:
	    Boolean(0); //false
	    Boolean(null); //false
	    Boolean(NaN); //false
	    Boolean(undefined); //false
	    Boolean(false); //false
	    Boolean(""); //false
	    
	    //Ejemplos en los que Boolean devuelve verdadero:
	    Boolean(1); //true para 1 o cualquier número diferente de cero (0)
	    Boolean("a"); //true para cualquier caracter o espacio en blanco en el string
	    Boolean([]); //true aunque el array esté vacío
	    Boolean({}); //true aunque el objeto esté vacío
	    Boolean(function(){}); //Cualquier función es verdadera también
	    
	```

	* **Gerardo Nava Pereda** (3)

		
		Faltaría tener cuidado con los números negativos.  
		Sólo el **0 es false**.  
		Cualquier otro número incluso los negativos es **true**
		``` 
		    Boolean(-1); //true
		    
		```

	* **Esau Guerra** (2)

		
		agregaria Boolean(true); //true

* **Carlos Andres Castañeda Osorio** (6)

	
	En el MDN se pueden encontrar los valores, dejo los enlaces:
	
	  * [Falsy](https://developer.mozilla.org/es/docs/Glossary/Falsy)
	  * [Truthy](https://developer.mozilla.org/es/docs/Glossary/Truthy)
	
	

* **Manuel Rivera** (6)

	
	Lo utilizamos bastabte en el curso de React js

* **israelhuaman** (5)

	
	creo que esta es una de las clases que evita muchos errores

	* **SEBASTIAN PADUANO** (1)

		
		totalmente de acuerdo

* **John Steven Bernal Gonzalez** (4)

	
	 **Que tipo de valor es verdadero y faso?**
	
	Que tipos por default son verdaderos y falsos
	
	La siguiente lista daremos ejemplos
	
	usamos la funcion de JS que es Boolean() dentro del pàrentesis ponemos el valor
	
	Boolean() —> sin ningun valor es false  
	Boolean(0) —> false  
	Boolean(null) —> false  
	Boolean(NaN) —> false // NaN es Not and Number  
	Boolean(Undefined) —> false  
	Boolean(false) —> false  
	Boolean(“") —> false
	
	Boolean(1) —> true //cualquier numero que no sea igual a cero es true  
	Boolean(“a") —> true  
	Boolean(“ ") —> true // siendo un espacio el valor es true  
	Boolean([]) —> true // un array nos da un true  
	Boolean({}) —> true // un objeto nos da el valor de true  
	Boolean(function() {}) —> true //una funcion tambien es true  
	Boolean(true) —> true
	
	Todo esto lo vamos a ucupar en condiciones esto valida si es verdadero o falso para ejecutar cierta acción
	
	<https://developer.mozilla.org/es/docs/Glossary/Falsy>  
	<https://developer.mozilla.org/es/docs/Glossary/Truthy>

* **Christian David Sánchez** (4)

	
	Hay un total de 6 valores / expresiones falsas en javascript.
	
	  * boolean ‘false’
	
	  * Cadena vacía es decir ‘’"
	
	  * undefined Cualquier variable undefined será igual a false.
	
	  * null Cualquier variable null será igual a false.
	
	  * NaN Cualquier expresión numérica con resultado en NaN(no un número) será igual a false.
	
	  * Número cero 0: Cualquier expresión numérica con resultado en cero será igual a false.
	
	
	

* **gonzaloPzl** (3)

	
	Valores que dan **False**  
	0  
	null  
	undefined  
	NaN  
	false  
	String vacio  
	Valores que dan **True**  
	Funciones  
	Strings  
	1 o mas  
	Arrays  
	Objetos  
	true

* **Francisco de Jesus** (3)

	
	NO olvidar NaN = not a number

* **Andres Roberto Coello Goyes** (3)

	
	En el caso de hacer una consulta en MySQL con node y no trae nada mysql retorna NULL, esto se interpreta como FALSE

* **Ulises Antonio Sámano Galván** (2)

	```
	    En JS todos los valores son verdaderos por defecto, a menos que los definamos como falsos con alguno de los siguientes valores:
	    
	```
	
	  * false.
	  * “” Un string vacio
	  * null
	  * NaN
	  * undefined
	
	
	
	Si quieres saber si un valor es verdadero o falso utiliza la función Boolean( _El valor que vas a evaluar_ );

* **carlosextra1** (2)

	
	Excelente clase, siempre es bueno ver cursos básicos. Esta clase me fue muy util!

* **renso-bc** (2)

	
	En JavaScript, un valor verdadero es un valor que se considera true/verdadero cuando es evaluado en un contexto Booleano. Todos los valores son verdaderos (true, {}, [], 42, “foo”, new(), -42, 3.14, -3.14, Infinity, -Infinity) a menos que se definan como falso (es decir, excepto false, 0, “”, null, undefined, y NaN).

* **Juan Esteban Galvis** (2)

	
	0, false, null, undefine, NaN o vacio = **Falso**  
	1, true, valor cualquiera, array, función u objeto = **True**
	
	Esto es muy importante para condicionales, y luego con esos true o false las tablas de valores son lo siguiente a aprender para dominar los condicionales-

* **Miguel Sequeiros Arapa** (2)

	
	muy útil tambien el concepto de nullish  
	<https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Nullish_coalescing_operator>

* **urieelmm** (2)

	
	Si tenemos una variable, también es verdadera o falso?

	* **dariusv** (1)

		
		Hice la prueba y si solo esta declarada la variable es falsa, si la inicializas con 0 sigue siendo falso ya que cero es igual a falso, si la inicializas con algún valor que sea verdadero como el 3, la variable pasaría a ser verdadera, recuerda que la variable equivale a el valor que le asignes, por eso será verdadera o falsa dependiendo del valor que le asignes a dicha variable

	* **rsalamanca** (1)

		
		Si claro si solo esta declarada pues seria undefined por ende seria false igual que si fuera inicializada en 0 o en ‘’’’

* **Kevin Vega** (2)

	
	En JavaScript, un valor verdadero es un valor que se considera true/verdadero cuando es evaluado en un contexto Booleano. Todos los valores son verdaderos a menos que se definan como falso (es decir, excepto false, 0, “”, null, undefined, y NaN).

* **Alejandro Arellano Alemán** (2)

	```
	    NaN// Not a Number
	    
	```

* **Javier Téllez** (2)

	
	Valor Booleano, solo almacena dos posibles valores, verdadero o falso, 0 y 1, prendido apagado, es para hacer las famosas banderas.

* **Ariel Alejandro Ureña Morales** (1)

	
	Excelente clase c:

* **garciafran** (1)

	
	Interesante el valor por default, bastante ultil

* **Diego Alfonso Najera Ortiz** (1)

	
	muy buena explicación!

* **Laurapregonero** (1)

	
	Vamos a utilizar (TRUTHY y FALSE) Cuándo generemos condiciones, funciones que tengamos que validar.
	
	False, Null, Undefined,NaN, vacio = False  
	True, Valor Array, Functions, objetos = True

* **picojohn** (1)

	
	buena clase

* **Germán Moreno** (1)

	
	Genial.

* **marlonhmp** (1)

	
	No sabia que una funcion tambien daba verdadero.

* **Sebastian Lomas** (1)

	
	Los objetos también son true.

* **Juan Zavala** (1)

	
	Excelente dato

* **Leonardo Bravo Kunkel** (1)

	
	Boolean (-1);  
	//true
	
	Pensé que sería falso, pero no.

	* **Israel Castro Urieta** (2)

		
		Cuando bien lo dice el profesor “valores distintos de cero” justo eso iba a comentar, que valores negativos también son valores true.

* **Bervive** (1)

	
	Los valores verdadero, falso

* **Merlyn Rodriguez** (1)

	
	dos puntos por terminar de ver el video :v

* **snowy** (1)

	
	ahora si viene lo chido !!!

* **Daniel Carmona** (1)

	
	Ya se vienen las evaluaciones 😄

* **Cristian Florez** (1)
Si cual es la diferencia entre NaN y por ejemplo Null???

	* **Jose Daniel Paiva** (2)

		
		`NaN` (Not a Number), como su nombre lo dice, nos indica que no es un número. Una de las formas de obtener este valor es dividiendo 0/0.
		
		`Null` quiere decir que el objeto está vacío y no apunta a ninguna dirección de memoria.
		
		[Aquí puedes leer sobre null, NaN y undefined](https://www.todojs.com/casos-especiales-undefined-null-y-nan/), espero que te ayude 😉

## 0110. Operadores Asignación, Comparación y Aritméticos.

### Descripción:


### Links:

* [Expressions and operators - JavaScript | MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

### Comentarios:

* **Cristobal Vega** (20)

	
	Bien, después de esta clase ya puedo agregar un meme que explica más sobre operadores 🤓
	
	![](https://i.redd.it/4skcofasa1p01.png)

* **Javier Téllez** (17)

	
	Por accidente descubrí que si aprietas algún número mientras ves el video, te posiciona en el porcentaje del número que hayas apretado.
	
	Ejemplo:  
	2 te lleva al 20%  
	3 te lleva al 30%  
	.  
	.  
	.  
	9 te lleva al 90%.

	* **Emmanuel García** (2)

		
		Pero al mismo tiempo es incomodo cuando te mueves entre pestañas con shortcuts 😕

	* **Cristobal Vega** (5)

		
		Más de medio año en la plataforma y apenas me acabo de dar cuenta también. 🤯

	* **Christian Erik Velázquez Morales** (1)

		
		Gracias, por el dato!

* **Mirna Mabel Veras Carvajal** (10)

	```
	    //Operadores binarios:
	    3 + 2//Suma
	    50 - 10// Resta
	    10 * 20//Multiplicación
	    20 / 2//División
	    
	    "Diego " + "De Granda"//concatenación de strings
	    
	    //Operadores unitarios:
	    !false//negación de la negación = true
	    
	    //Operadores de asignación:
	    var a = 1; //Asignamos un valor a la variable
	    
	    //Operadores para comparar:
	    3 == "3"; //Compara los valores y devuelve "true" en este caso
	    
	    3 === "3"; //Compara y valida los tipos y valores. Devuelve "falso" en este caso
	    
	    5 < 3//Compara y valida si el 5 es menor a 3
	    5 > 3//Compara y valida si el 5 es mayor a 3
	    5 <= 6//Compara y valida si el 5 es menor o igual al 6
	    5 >= 6//Compara y valida si el 5 es mayor o igual al 6
	    
	    a && b //Valida si ambas variables son verdaderas para que se cumpla la condición
	    a || b //Aquí se cumple la condición si alguna de las dos variables es verdadera
	    
	    var edad = 40
	    edad++ //Incrementa el valor en 1
	    
	    edad += 2//Incrementa el valor por 2
	    
	```

* **lmoran** (8)

	```
	    //OPERADORES
	    //Operadores Binarios:
	    3 + 2;
	    50 - 10;
	    10 * 20;
	    20 / 2;
	    //Tambien sirve para concatenar String:
	    "Diego " + "De Granda";
	    //Operador de negación:
	    !true; //devolverá false
	    !false; //devolverá true
	    //Operador de asignación:
	    var a = 3;
	    //operador de comparación:
	    3 == "3"; // va comparar el valor mas no el tipo
	    3 === "3"; // compara que el valor y el tipo sean iguales
	    5 > 3; //5 es mayor que 3 es true
	    5 < 3; // 5 es menor que 3 es false
	    5 >= 6; // 5 es mayor o igual 6 es false
	    5 <= 6; // 5 es menor o igual que 6 es true
	    5 <> 6; //5 no es igual que 6
	    
	    a && b; // va validar que a y b son verdad se cumple esa condición
	    a || b; // va validar que solo a o b sea verdad para que se cumpla esa condición
	    //operadores de incremento:
	    var edad = 40;
	    edad++; //el valor de edad se va incrementar en uno.
	    edad += 2; // el valor de edad va incrementar en dos.
	    
	```

	* **Rimak Castañeda Mejia** (1)

		
		Gracias!

* **Andres Burbano** (6)
<h1>OPERADORES: ASIGNACION, LOGICOS Y ARITMETICOS</h1>
	
	## Operador de asignacion
	
	Simbolo | Descripcion  
	---|---  
	= | operador de asignacion  
	  
	## Operadores de comparacion
	
	Simbolo | Descripcion  
	---|---  
	== | igual que  
	=== | estrictamente igual que  
	> or >= or >== | mayor o mayor igual que  
	< or <= or <== | menor o menor igual que  
	!= or !== | diferente que  
	  
	## Operadores aritmeticos
	
	Simbolo | Descripcion  
	---|---  
	+ | operador suma este se utiliza para concatener dos cadenas de texto.  
	- | operador resta  
	* | operador de multicacion  
	/ | operador de division  
	% | operador de modulo  
	** | operador de potenciacion  
	  
	tambien se les conoce como operadores binarios. por que toman dos valores y generan un resultado.
	
	## Operadores logicos
	
	Simbolo | Descripcion  
	---|---  
	! | NOT niega un valor  
	&& | AND  
	|| | OR

	* **Orlando0302** (1)
  
		  
		excelente amigo

* **Lorenzo David Lezcano** (5)

	
	Lo del triple igual === es bárbaro

* **lmgaero** (4)

	
	Perfecta clase, solo hizo falta un operador binario o aritmético, llamado módulo que es escrito con el símbolo de porcentaje (%). Este operador nos devuelve el resto o el sobrante de la división aritmética.
	
	Ejemplo:  
	`6 % 2; // Devuelve 0, porque es una división perfecta. 8 % 3; // Devuelve 2, porque no es una división exacta, 2 * 3 = 6, y el restante es 2`

* **Christian David Sánchez** (4)
![operadores-javascript3-l.jpg](https://static.platzi.com/media/user_upload/operadores-javascript3-l-c8941201-4375-424b-a45c-aa80688f2cf3.jpg)

* **Juan Camilo Alvarez Jurado** (4)

	
	Todo el mundo deja de lado a la disyunción exclusiva :c  
	  
	El operador ^ (acento circunflejo) sirve para la operación de disyunción exclusiva entre dos booleanos. Esta operación, también conocida como XOR, es básicamente: o es A, o es B, pero no pueden ser A y B a la vez  
	  
	Tabla de verdad de a ^ b:  
	  
	![](![xor.png](https://static.platzi.com/media/user_upload/xor-944d9bd3-ca04-4053-9d3e-2f8f4408c9df.jpg)

* **dariusv** (4)

	
	¿En los operadores no entraría también el “MOD” (%)?

	* **Danelia Sanchez Sanchez** (1)

		
		Sí, al igual que los operadores de exponenciación, incremento y decremento.  
		[https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Operadores/Aritméticos](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Operadores/Aritm%C3%A9ticos)

* **Mauricio Jofre Heimerl** (3)

	
	Codigo desafio juego - piedra, papel o tijera
	``` 
	    /*=============================================
	        Juego - Piedra, Tijera o Papel
	    =============================================*/
	    
	    // Esatructura de datos
	    const opciones = ["piedra", "tijera", "papel"];
	    
	    functionjugadorMaquina() {
	      // Retorna un valor aleatorio entre 0 y 3
	      var indice = Math.floor(Math.random() * 3);
	      document.getElementById(
	        "maquina"
	      ).innerHTML = `<strong>Máquina:</strong> ${opciones[indice]}`;
	      return opciones[indice];
	    }
	    
	    /*=============================================
	    =  Obtiene seleccion del Jugador del HTML     =
	    =============================================*/
	    functiongetRadioButtonSelectedValue() {
	      var elementos = document.getElementsByName("opcionesjugador");
	      for (i = 0; i < elementos.length; i++) {
	        if (elementos[i].checked) {
	          var seleccionJugador = elementos[i].value;
	          var seleccionMaquina = jugadorMaquina();
	          /*=============================================
	          =            Jugador = Maquina                =
	          =============================================*/
	          if (seleccionJugador === seleccionMaquina) {
	            mostrarResultado("EMPATE");
	          /*=============================================
	          =   Combinaciones de Piedra, Papel y Tijera   =
	          =============================================*/
	          } else {
	            seleccionJugador === "piedra" && seleccionMaquina === "papel"
	              ? mostrarResultado("PERDISTE")
	              : null;
	            seleccionJugador === "piedra" && seleccionMaquina === "tijera"
	              ? mostrarResultado("GANASTE")
	              : null;
	            seleccionJugador === "papel" && seleccionMaquina === "piedra"
	              ? mostrarResultado("GANASTE")
	              : null;
	            seleccionJugador === "papel" && seleccionMaquina === "tijera"
	              ? mostrarResultado("PERDISTE")
	              : null;
	            seleccionJugador === "tijera" && seleccionMaquina === "piedra"
	              ? mostrarResultado("PERDISTE")
	              : null;
	            seleccionJugador === "tijera" && seleccionMaquina === "papel"
	              ? mostrarResultado("GANASTE")
	              : null;
	          }
	        }
	      }
	    }
	    
	    // Muestra el resultado en HTML
	    functionmostrarResultado(resultado) {
	      return (document.getElementById(
	        "resultado"
	      ).innerHTML = `<strong>¡${resultado}!</strong>`);
	    }
	    
	```

	* **RemyLebeau** (1)

		
		Super, esta muy bueno, espero al terminar los cursos básicos de javascript poder implementarlo con html como lo haces, ya que hay partes que aun desconozco.

* **Carlos Eduardo Diaz Polanco** (3)

	```
	    == // Es igual
	    === // Es identico
	    
	```

* **Ariel Alejandro Ureña Morales** (2)

	
	Qué util, no sabía la diferencia entre == y ===.

* **Bryan Javier Calero Robleto** (2)
<h1>Operadores: Asignación, Comparación y Aritméticos</h1>
	
	## Operadores de Operación
	
	  *     * : este tambien sirve para concatenar texto
	  *     *   *     *   * /
	
	3 + 2  
	50 - 10  
	10 * 20  
	20 / 20  
	"Bryan" \+ “Calero” //concatenar
	
	
	
	
	## Unity Operator
	
	  * ! : Sirve para negar
	
	!false //no devuelve que es true ya que lo estaria negando
	
	
	
	
	## Operadores de Asignación y comparación
	
	  * = : Asigna valor
	
	  * == : hace una comparación no estricta (no importa tipos de variables)
	
	  * === : Hace una comparación estricta (Importas los tipos de variables)
	
	var a = 1; //asigna uno a la variable x  
	3 == “3”; //TRUE compara dos variables y no toma en cuenta el tipo de variable  
	3 === “3”;//FALSE Compara dos variable y toma en cuenta el tipo de variable
	
	
	

* **Juan Esteban Galvis** (2)

	
	El tema de que se cumpla uno y/o la otra se aprendé con las **Tablas de Verdad** en matemáticas discretas, dejo la tabla:
	
	**( && = Y ; || = O ; ! = Negación)**
	
	![tablas-de-verdad.jpg](https://static.platzi.com/media/user_upload/tablas-de-verdad-40efb332-c0c5-42c0-95d4-49d66f5265dc.jpg)

* **Sebastián Mera** (2)

	
	¿Alguien sabe como sacar el simbolo de “o”? Las dos lineas verticales.

	* **Gabriel De Andrade (Platzi)** (5)

		
		Este: | ? Generalmente está en la parte superior izquierda de tu teclado, si está en español 😛

	* **RemyLebeau** (2)

		
		Si no se visibiliza en tu teclado lo puedes sacar por codigo ASCii
		
		ALT 124
		
		| |

* **pablod574** (2)

	
	comparar un numero con un string con == no importa el tipo de dato, sino el valor ej: 3 == "3" true

* **pablod574** (2)

	
	Al usar === sí importa el tipo de dato ej: 3 === "3" false

* **Kevin Vega** (2)

	
	 **Operadores de Comparación**  
	= (Es igual a) Igual a
	
	> (Mayor que) Mayor que  
	>  < (Menor que) Menor que  
	>  = (Mayor o igual a) Mayor o igual que  
	>  <= (Menor o igual a) Menor o igual que  
	>  <> (No es igual a) No es igual a  
	>  != (No es igual a) No es igual a  
	>  !< (No menor que) No es menor que  
	>  !> (no mayor que) No es mayor que
	
	**Operadores de Asignación en JavaScript**  
	<https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Operadores/Assignment_Operators>

* **Sneyder Alfonso Barreto Buitrago** (2)

	
	Existe un término _‘fancy’_ en programación llamado **overloading** , que se refiere a que un operador (en este caso) cuenta con _más de un comportamiento_ dependiendo de los tipos de valores usados en la operacion.  
	Un ejemplo de esto sería el operador **+**.
	``` 
	    3 + 4// Output: 7 (En este caso sería una simple suma aritmética)
	    'Hola ' + 'compañeros'// Output: Hola compañeros (En este caso sería una string concatenation)
	    
	```
	
	Algo más a tener en cuenta, es que los operadores como **+=** , **-=** , etc., son operadores que se pueden usar **únicamente con variables**. Como por ejemplo, la variable _edad_ que utilizó el profesor en esta clase.  
	Un saludo.

* **Daniel Carmona** (2)

	
	Tambien el decremento con – o -=

* **juanlondono** (2)

	
	<https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Expressions_and_Operators>

* **carlosextra1** (1)

	
	esta clase es esencial porque las comparaciones aplican a cualquier lenguaje de programación

* **Jharell Alejandra Hidalgo Loya** (1)

	
	operadores lógicos son && y || ??

	* **ag94e** (2)

		
		Así es, && (AND) || (OR)

	* **Robinson Matias Aguilar Bascuñan** (1)

		
		el OR no es solo con 1 | ?

* **Jeisson Santiago Cortes Ortiz** (1)

	
	…

* **Andres Burbano** (1)

	
	Cuales son las reglas de markdown utilizadas en esta sección ?

* **Danelia Sanchez Sanchez** (1)

	
	Igualdad estricta.

* **Germán Moreno** (1)

	
	Excelente clase.

* **Miguel Sequeiros Arapa** (1)

	
	se viene el operador Nullish coalescing , ya está en Stage 4 !!!
	
	<https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Nullish_coalescing_operator>

* **Juan Zavala** (1)

	
	Excelente

* **Valente IA** (1)

	
	son los mismos operadores que se utilizan en algún otro lenguaje

* **Francisco de Jesus** (1)

	
	Buena clase rapida y concisa

* **Bervive** (1)

	
	Estoy familiarizado con estos operadores porque los hemos trabajado bastante en el curso de programación básica.

* **CarlosAlba** (1)

	
	Algo importante es repasar las “[tablas de verdad](https://es.wikipedia.org/wiki/Tabla_de_verdad)” para entender mejor acerca de los operadores.

* **Manuel Rivera** (1)

	
	Documentación
	
	<https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Expressions_and_Operators>

* **Merlyn Rodriguez** (1)

	
	dos puntos por terminar de ver el video :v

	* **DiegoPV** (9)

		
		Loco, hay varias formas de que te ganes puntos, y si es por comentarios, pues que sea algo que aporte!

	* **Oscar Galicia** (3)

		
		No seas pesado.

	* **matias-alexander-ibarra-trujil** (2)

		
		dejen que gane sus puntos, dos puntos por apoyar al compañero

	* **Gerardo Nava Pereda** (5)

		
		Se engaña a si mismo xD, los puntos no valen, realmente ganaría si investigara y aportara algo de valor ganaría conocimiento para él y para otros… además en la vida real hacer algo funcional es lo que vale. Los puntos son meramente un efecto de recompensa que te motiva a compartir pero quiere sentir un efecto inmediato, es natural, así empieza la mayoría queriendo correr …

	* **matias-alexander-ibarra-trujil** (2)

		
		mhhh nop, los puntos te sirven para platzi master, 2 puntos por refutar

# Condicionales

## 0120. Condicionales If, Else, else if

### Descripción:


### Links:

* [Operador condicional (ternario) - JavaScript | MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Operadores/Conditional_Operator)

### Comentarios:

* **JEB10** (4)
![Captura de pantalla 2020-04-06 a las 1.10.13 p. m..png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202020-04-06%20a%20las%201.10.13%20p.%C2%A0m.-375c1281-faae-43ac-a7dd-f1d469228595.jpg)
	``` 
	    /* Función para generar un número random y asignarle un valor:
	    ('Rock ✊🏼', 'Paper 🖐🏼' o 'Scissors ✌🏼) a través de los condicionales: if, else, else if */
	    
	    functionrandomMachine(){
	        electionMachine = Math.round(Math.random()*2)
	        if(electionMachine === 0){
	            electionMachine = 'Rock ✊🏼'
	            console.log('🤖Machine Choice: ' + electionMachine)
	        } elseif(electionMachine === 1){
	            electionMachine = 'Paper 🖐🏼'
	            console.log('🤖Machine Choice: ' + electionMachine)
	        } elseif(electionMachine === 2){
	            electionMachine = 'Scissors ✌🏼'
	            console.log('🤖Machine Choice: ' + electionMachine)
	        } else{
	            console.log('Are You Ready? 🎮')
	        }
	        }
	    
	    /* Función que contiene la lógica del programa a través de los condicionales: if, else, else if donde pasamos como
	    parámetro(playerElection) y generamos la comparación con la variable(ElectionMachine) de la función randomMachine*/
	    
	        functionplayRoshambo(playerElection){
	        console.log('👾Player Choice: : ' + playerElection)
	        if(playerElection === electionMachine){
	            console.log('Try Again ✊🏼🖐🏼✌🏼')
	        } elseif(playerElection === 'Rock ✊🏼' && electionMachine === 'Paper 🖐🏼'){
	            console.log('LOSER 💩!')
	        } elseif(playerElection === 'Rock ✊🏼' && electionMachine === 'Scissors ✌🏼'){
	            console.log('WINNER 🎉!!')
	        } elseif(playerElection === 'Scissors ✌🏼' && electionMachine === 'Rock ✊🏼'){
	            console.log('LOSER 💩!')
	        } elseif(playerElection === 'Scissors ✌🏼' && electionMachine === 'Paper 🖐🏼'){
	            console.log('WINNER 🎉!')
	        } elseif(playerElection === 'Paper 🖐🏼' && electionMachine === 'Scissors ✌🏼'){
	            console.log('LOSER 💩!')
	        } elseif(playerElection === 'Paper 🖐🏼' && electionMachine === 'Rock ✊🏼'){
	            console.log('WINNER 🎉!')
	        }
	        }
	    
	        console.log('Choice: Rock ✊🏼 / Paper 🖐🏼 / Scissors ✌🏼');
	    
	    /* No olvides llamar ambas funciones para inicializar el juego:
	    randomMachine()
	    playRoshambo('Scissors ✌🏼') --> Aquí va la elección del jugador como String.
	    Anímate a mejorar este código para que hagamos un juego más divertido 🦾👨🏼‍💻
	    */```
	    
	```

	* **RemyLebeau** (1)

		
		Hey amigo super, quedo bacanisimo, como hiciste para sacar los emoticones o iconos?

	* **JEB10** (1)

		
		Hola **@RemyLebeau**  
		Es fácil, si tienes un mac, presiona: **(ctrl + cmd + barra espaciadora).**  
		Si trabajas con otro sistema operativo, puedes buscarlo en este link, y solo haces **copy/paste**  
		<https://emojikeyboard.top/es/>
		
		Un abrazo de gol! 🦾👨🏼‍💻

* **Yiy0** (4)

	
	Dos cosas: la primera es la interactividad que puede ser mejorada con botones para que se registre correctamente la elección y segundo no se como colocar como parámetro un array sin romper el código, cualquier sugerencia en especial en lo ultimo siempre es bienvenida, peace 😃
	``` 
	    alert("You must give 0 (scissor) or 1 (rock) or 2 (paper) to the parameter of the game function")
	    
	    let options = [0, 1, 2];
	    
	        functiongame(input_player){
	            //Machine choice      
	            machine_choice = options[Math.floor(Math.random() * options.length)]
	            
	            //Logic
	            if (
	                input_player === 0 && machine_choice === 2 || 
	                input_player === 1 && machine_choice === 0 ||
	                input_player === 2 && machine_choice === 1 
	                ){
	                console.log("Player wins!");
	            }elseif (input_player === machine_choice ){
	                console.log("Draw");
	    
	            }else{
	                console.log("Player lose ;(")
	            }
	        }
	    
	```

* **juancamiloosoriobedoya5** (4)

	
	Este codigo es el mas sencillo, se debe ingresar en strings lo que escogería el jugador o el computador y ahí te arroja el resultado.  
	Esta de acuerdo a lo que nos han enseñado hasta hoy, para que no se desanimen si ven que los compañeros usan cosas que no hemos visto en lo que va de la escuela de JS (Math.random, Math.Floor, let etc etc…)
	``` 
	    var jugador;
	    var computador;
	    
	    if (jugador == "tijeras"  && computador == "papel") 
	    {
	        console.log("Ganaste");
	    }
	    elseif (jugador == "Piedra"  && computador == "tijeras") 
	    {
	        console.log("Ganaste");
	    }
	    elseif (jugador == "papel"  && computador == "piedra") 
	    {
	        console.log("Ganaste");
	    }
	    elseif (jugador == computador ) 
	    {
	        console.log("empate");
	    }
	    else {
	        console.log("Perdiste")
	    }
	    
	```

* **julio1985** (3)
saludos compañeros donde puedo encontrar ejercicios con If y else, para practicar!!!

	* **diego rodriguez** (6)

		
		esta pagina sirve para pracitcar js con diferentes retos  
		<https://javascript30.com/>

* **RemyLebeau** (2)

	
	Algo sencillo y simple al principio se me dificulto la lógica pero ya después que fui probando y aclarando resolví dudas y practique la teoría.
	``` 
	    /*****PIEDRA, PAPEL O TIJERA********/
	    
	    var persona; // declaro las variables
	    var maquina ;
	    
	    /***Funcion Juego**** */
	    
	    functionJuego ( persona, maquina){
	        
	        const piedra = "piedra";// declaro las constantes del juego
	        const papel = "papel";
	        const tijera = "tijera";
	    
	        /**Validar que la variable a jugar sea valida para el juego ****/
	        if(persona != "piedra" || persona != "papel" || persona !="tijera"){
	            console.log("Jugada No Valida")
	        }
	    
	        /**Declara empate en el juego ****/
	        if(persona === maquina){
	            console.log(" empate ");
	    
	        /*** Condiciones que declaro campeon al jugador***/    
	        }elseif(persona === piedra && maquina === tijera){
	                console.log("Tu haz ganado");
	            }elseif(persona === papel && maquina === piedra){
	                console.log("Tu haz ganado");
	            }elseif(persona === tijera && maquina === papel){
	                console.log("Tu haz ganado"); 
	        /** Condiciones que declaran ganador a la Maquina**/        
	            }elseif(maquina === papel && persona === piedra){
	                console.log("Haz perdido");
	            }elseif(maquina === tijera && persona === papel){
	                console.log("Haz perdido"); 
	            }elseif(maquina === piedra && persona === tijera){
	                console.log("Haz perdido");
	            }    
	    
	    
	    }
	    
	    Juego("piedra", "tijera") // Llamo a la funcion Juego```
	    
	```

* **geovanygomez** (2)

	
	Se que es muuuy básico pero de verdad no saben lo feliz que me pone haberlo hecho yo solo, estoy aprendiendo desde cero
	
	var computadoraElije = "papel"  
	var yoElijo = "piedra"  
	if (computadoraElije == yoElijo) {  
	console.log(“Empate”)  
	}  
	else if (computadoraElije == “piedra” && yoElijo == “papel” ) {  
	console.log(“Gana humano”)  
	}  
	else if (computadoraElije == “piedra” && yoElijo == “tijera” ) {  
	console.log(“Gana computadora”)  
	}  
	else if (computadoraElije == “papel” && yoElijo == “piedra” ) {  
	console.log(“Gana computadora”)  
	}  
	else if (computadoraElije == “papel” && yoElijo == “tijera” ) {  
	console.log(“Gana humano”)  
	}  
	else if (computadoraElije == “tijera” && yoElijo == “papel” ) {  
	console.log(“Gana computadora”)  
	}  
	else if (computadoraElije == “tijera” && yoElijo == “piedra” ) {  
	console.log(“Gana humano”)  
	}  
	else {  
	console.log(“Algo salio mal y no se que pudo haber sido”)  
	}

* **Mackial Houng** (2)

	```
	    const option = {
	       "one" : "rock",
	       "two" : "paper",
	       "tree" : "scissors" 
	    }
	    
	    functionplayPC() {
	       // Obtendrá un número aleatorio del 0 al 2
	       var pc = Math.floor(Math.random()*3);
	       var chosenOption = "";
	       if (pc === 0) {
	          chosenOption = option["one"];
	       } elseif (pc === 1) {
	          chosenOption = option["two"];
	       } elseif (pc === 2) {
	          chosenOption = option["tree"];
	       }
	       return chosenOption;
	    }
	    
	    functioncheck(player) {
	       // eleccion del computador
	       var pc = playPC();
	       console.log(pc);
	       if (player === pc) {
	          console.log("Draws");
	       } elseif (player === 'rock' && pc === 'paper') {
	          console.log('You lost');
	       } elseif (player === 'rock' && pc === 'scissors') {
	          console.log('You win');
	       } elseif (player === 'paper' && pc === 'rock') {
	          console.log('You win');
	       } elseif (player === 'paper' && pc === 'scissors') {
	          console.log('You lost');
	       } elseif (player === 'scissors' && pc === 'rock') {
	          console.log('You lost');
	       } elseif (player === 'scissors' && pc === 'paper') {
	          console.log('You win');
	       }
	    }
	    
	    var yourChoice = prompt("rock | paper | scissors \n\nWrite one: ");
	    
	    check(yourChoice);```
	    
	```

* **Daniel Esteban Santos Mendez** (2)

	```
	    const piedra = 0;
	    const papel = 1;
	    const tijera = 2;
	    var machine = Math.floor(Math.random() * 3); 
	    
	    
	    functionpiedraPapelOTijera(element) {
	        
	    
	        if(machine === element){
	            console.log('Empatan');
	            
	         } elseif(machine === 0 && element === 1){
	            console.log('Papel gana a piedra');
	        }elseif (machine === 0 && element === 2){
	            console.log('Piedra gana a tijera');
	        }elseif (machine === 1 && element === 0) {
	            console.log('Papel gana a piedra');
	        }elseif (machine === 1 && element === 2){
	            console.log('Tijera gana a Papel');
	        }elseif (machine === 2 && element === 0){
	            console.log('Piedra gana a tijera');
	        }elseif (machine === 2 && element === 1){
	            console.log('Tijera gana a papel');
	        }
	    }
	    
	    
	```

	* **Orlando0302** (1)

		
		excelente amigo

	* **eduardovinagre** (1)

		
		Un consejo … si ya declaraste las constantes, entonces úsalas así facilitas la lectura de tu código.

* **Lorena Pinzón** (2)

	```
	    var maquina = ["piedra","papel","tijera"];
	    
	    functionjugadas( jugador ){
	        var i = Math.floor(Math.random() * 3);
	        if(jugador != "piedra" || jugador != "papel" || jugador != "tijera"){
	            console.log("jugada no válida");
	        }
	        else{
	            if(jugador === maquina[i]){
	                console.log("empate");
	            }
	            else{
	                if(jugador === "piedra" && maquina[i] === "papel" || jugador === "tijera" && maquina[i] === "piedra" || jugador === "papel" && maquina[i] === "tijera"){
	                    console.log("perdiste contra la máquina "+maquina[i]);
	                }
	                else{
	                    console.log("ganaste contra la máquina "+maquina[i]);
	                } 
	            }
	        }
	    }
	    
	    jugadas("piedra");
	    
	```

* **Ender José Urdaneta Ocando** (2)

	```
	    function jugar(p1,p2){
	        if(p1===p2){
	            console.log("hay empate");
	        }elseif(p1==="piedra" && p2 ==="tijera"){
	            console.log("gana jugador 1");
	        }elseif(p1==="piedra" && p2 ==="papel"){
	            console.log("gana jugador 2");
	        }elseif(p1==="papel" && p2 ==="tijera"){
	            console.log("gana jugador 2");
	        }elseif(p1==="papel" && p2 ==="piedra"){
	            console.log("gana jugador 1");
	        }elseif(p1==="tijera" && p2 ==="piedra"){
	            console.log("gana jugador 2");
	        }elseif(p1==="tijera" && p2 ==="papel"){
	            console.log("gana jugador 1");
	        }
	    }```
	    
	```

	* **ASSACOLOMBIA** (1)

		
		Tu respuesta me agrada pues uso conocimientos vistos hasta el momento, algunas soluciones que vi meten otras cosas que hasta el momento no conozco.

* **Bryan Gallo** (2)

	
	Este código que utilice yo para el reto 😛 , se me hizo un poco complicado pero me guié en varios códigos que publicaron en la comunidad aunque algunos no entendía 😦 pero en lo de Math.random logre entender 😛 espero este bien para haber comenzado,el curso me gusta mucho 😄  
	![Captura de pantalla \(387\).png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%28387%29-cc706d2e-507a-40af-8392-3e053b1264e4.jpg)

	* **Messorid** (2)

		
		Gracias amigo tu codigo me fue muy util

* **DevNaftan** (2)

	
	 **Reto cumplido**
	``` 
	    /* El juego tiene 3 rondas y acaba cuando uno de los participantes gana 3 veces */
	    
	    // Declaración de variables
	    var piedra = "Piedra";
	    var papel = "Papel";
	    var tijera = "Tijera";
	    var round_count = 0;
	    var yo_count = 0;
	    var maquina_count = 0;
	    var maquina;
	    
	    // Generación aleatoria de una opción para la máquina
	    var maquinaOpcion = function() {
	      return Math.round(Math.random()*(3-1)+parseInt(1));
	    }
	    
	    // Algoritmo del juego
	    function juego(yo) {
	      // Escoge una opción para la máquina
	      maquina = maquinaOpcion();
	    
	      // Convierte la opción escogida a texto
	      if(maquina === 1){
	        maquina = "Piedra";
	      } elseif (maquina === 2) {
	        maquina = "Papel";
	      } elseif (maquina === 3) {
	        maquina = "Tijera";
	      }
	    
	      // Compara las opciones escogidas y muestra el resultado de la ronda
	      if (yo === maquina) {
	        round_count++
	        console.log("Ronda: " + round_count + ". Tú: " + yo + " - Máquina: " + maquina + ". Resultado: Empate");
	      } elseif (yo === "Piedra" && maquina === "Papel") {
	        maquina_count++;
	        round_count++
	        console.log("Ronda: " + round_count + ". Tú: " + yo + " - Máquina: " + maquina + ". Resultado: Perdiste");
	      } elseif (yo === "Piedra" && maquina === "Tijera") {
	        yo_count++;
	        round_count++
	        console.log("Ronda: " + round_count + ". Tú: " + yo + " - Máquina: " + maquina + ". Resultado: Ganaste");
	      } elseif (yo === "Papel" && maquina === "Piedra") {
	        yo_count++;
	        round_count++
	        console.log("Ronda: " + round_count + ". Tú: " + yo + " - Máquina: " + maquina + ". Resultado: Ganaste");
	      } elseif (yo === "Papel" && maquina === "Tijera") {
	        maquina_count++;
	        round_count++
	        console.log("Ronda: " + round_count + ". Tú: " + yo + " - Máquina: " + maquina + ". Resultado: Perdiste");
	      } elseif (yo === "Tijera" && maquina === "Piedra") {
	        maquina_count++;
	        round_count++
	        console.log("Ronda: " + round_count + ". Tú: " + yo + " - Máquina: " + maquina + ". Resultado: Perdiste");
	      } elseif (yo === "Tijera" && maquina === "Papel") {
	        yo_count++;
	        round_count++
	        console.log("Ronda: " + round_count + ". Tú: " + yo + " - Máquina: " + maquina + ". Resultado: Ganaste");
	      }
	    
	      // Verifíca el número de rondas
	      if ((yo_count === 3) || (maquina_count === 3)) {
	        // Muestra el resultado final si alquien ya ha ganado 3 veces
	        if (yo_count === 3) {
	          alert("Ganaste. Puntaje final: " + yo_count + " - " + maquina_count);
	        } elseif (maquina_count === 3){
	          alert("Perdiste. Puntaje final: " + yo_count + " - " + maquina_count);
	        }
	        //Reinicia las variables para poder jugar nuevamente
	        round_count = 0;
	        yo_count = 0;
	        maquina_count = 0;
	      }
	    }```
	    
	```

* **Juan Enrique Rodriguez Garcia** (2)

	
	Juego reto
	
	![Captura de pantalla de 2020-03-23 08-58-25.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20de%202020-03-23%2008-58-25-51a569b2-7cdd-49e0-8a3a-eadb53412a87.jpg)
	
	codigo html
	``` 
	    <!DOCTYPE html>
	    <htmllang="en">
	    <head>
	        <metacharset="UTF-8">
	        <metaname="viewport"content="width=device-width, initial-scale=1.0">
	        <linkrel="stylesheet"href="css/style.css">
	        <title>Piedra, papel y tijeras</title>
	    </head>
	    <body>
	        <headerclass="header">
	            <h1class="header-title">Piedra, papel y tijeras</h1>
	        </header>
	    
	    
	        <sectionid="empezar"class="start">
	            <divclass="start__container">
	                <inputtype="button"value="Empezar a jugar"onclick="empezar()">
	            </div>
	        </section>
	    
	    
	        <sectionid="opciones"class="options hidden">
	            <navclass="options__container">
	                <inputid="elegirPiedra"class="options__container--input"type="button"onclick="eleccion()"value="Piedra">
	                <inputid="elegirPapel"class="options__container--input"type="button"onclick="eleccion()"value="Papel">
	                <inputid="elegirTijeras"class="options__container--input"type="button"onclick="eleccion()"value="Tijeras">
	            </nav>
	        </section>
	    
	        <sectionid="cartelFinal"class="final hidden">
	            <divclass="final__container">
	                <pid="final"class="final__container--title"></p>
	                <inputclass="final__container--input"type="button"value="Dale de nuevo!!"onclick="empezar()">
	            </div>
	        </section>
	    
	        <sectionclass="container">
	            <figureclass="container-figure">
	                <divid="piedraPlayer1"class="container-figure--img hidden">
	                    <p>Tú</p>
	                    <imgsrc="imagenes/piedra.png"alt="piedra">
	                    <p>Piedra</p>
	                </div>
	                <divid="papelPlayer1"class="container-figure--img hidden">
	                    <p>Tú</p>
	                    <imgsrc="imagenes/papel.png"alt="papel">
	                    <p>Papel</p>
	                </div>
	                <divid="tijerasPlayer1"class="container-figure--img hidden">
	                    <p>Tú</p>
	                    <imgsrc="imagenes/tijera.png"alt="tijeras">
	                    <p>Tijera</p>
	                </div>
	            </figure>      
	            <figureclass="container-figure">
	                <divid="piedraPlayer2"class="container-figure--img hidden">
	                    <p>Rival</p>
	                    <imgsrc="imagenes/piedra.png"alt="piedra">
	                    <p>Piedra</p>
	                </div>
	                <divid="papelPlayer2"class="container-figure--img hidden">
	                    <p>Rival</p>
	                    <imgsrc="imagenes/papel.png"alt="papel">
	                    <p>Papel</p>
	                </div>
	                <divid="tijerasPlayer2"class="container-figure--img hidden">
	                    <p>Rival</p>
	                    <imgsrc="imagenes/tijera.png"alt="tijera">
	                    <p>Tijera</p>
	                </div>
	            </figure>   
	        </section>
	    
	    
	        <footerclass="footer">
	            <pid="footer__counter"class="footer__counter">Contador</p>
	        </footer>
	        <scriptsrc="index.js"></script>
	    </body>
	    </html>
	    
	```
	
	Codigo CSS
	``` 
	    .footer, .container-figure--img, .final__container, .options__container, .start__container, .header, .final, .options, .start {
	      display: flex;
	      justify-content: center;
	      align-items: center;
	    }
	    
	    .final, .options, .start {
	      position: absolute;
	      top: 0;
	      right: 0;
	      bottom: 0;
	      left: 0;
	    }
	    
	    .final__container, .options__container, .start__container {
	      width: 45vw;
	      height: 20vh;
	      flex-direction: column;
	      justify-content: space-around;
	      border-radius: 20px;
	      box-shadow: 10px10pxrgba(0, 0, 0, 0.2);
	      background: linear-gradient(#fe346e, #ffbd69);
	    }
	    
	    .hidden {
	      display: none;
	    }
	    
	    * {
	      margin: 0;
	      padding: 0;
	      box-sizing: 0;
	    }
	    
	    bodyinput {
	      width: 80%;
	      height: 20%;
	      border-radius: 25px;
	      background: linear-gradient(#ffbd69, #fe346e);
	      border: none;
	      outline: none;
	      cursor: pointer;
	    }
	    
	    input:active {
	      filter: opacity(0.3);
	    }
	    
	    .header {
	      width: 100vw;
	      height: 10vh;
	      background-color: #fe346e;
	    }
	    
	    .header-title {
	      color: white;
	    }
	    
	    .start__container {
	      background: transparent;
	      box-shadow: none;
	    }
	    
	    .start__containerinput {
	      height: 70%;
	    }
	    
	    .final__container--title {
	      font-size: 20px;
	    }
	    
	    .container {
	      width: 100vw;
	      height: 80vh;
	      background: linear-gradient(#fe346e, #ffbd69);
	      display: grid;
	      grid-template-columns: 50%50%;
	    }
	    
	    .container-figure {
	      margin: 0;
	    }
	    
	    .container-figure--img {
	      width: 50vw;
	      height: 100%;
	      flex-direction: column;
	      font-size: 30px;
	      color: white;
	    }
	    
	    .container-figure--imgimg {
	      width: 60%;
	      height: 60%;
	      object-fit: contain;
	    }
	    
	    .footer {
	      width: 100vw;
	      height: 10vh;
	      background: #ffbd69;
	      font-size: 50px;
	    }
	    
	```
	
	Codigo Javascript
	``` 
	    const start = document.getElementById("empezar");
	    const options = document.getElementById("opciones");
	    const cartelFinal = document.getElementById("cartelFinal");
	    
	    const piedra1 = document.getElementById("piedraPlayer1");
	    const papel1 = document.getElementById("papelPlayer1");
	    const tijeras1 = document.getElementById("tijerasPlayer1");
	    const piedra2 = document.getElementById("piedraPlayer2");
	    const papel2 = document.getElementById("papelPlayer2");
	    const tijeras2 = document.getElementById("tijerasPlayer2");
	    
	    const elegirPiedra =  document.getElementById("elegirPiedra");
	    const elegirPapel = document.getElementById("elegirPapel");
	    const elegirTijeras = document.getElementById("elegirTijeras");
	    
	    const tituloFinal = document.getElementById("final");
	    const contador = document.getElementById("footer__counter");
	    
	    var jugador = null;
	    var maquina = null;
	    var contadorJugador = 0;
	    var contadorMaquina = 0;
	    
	    var empezar = () => {
	        start.classList.add("hidden");     
	        options.classList.remove("hidden");
	        cartelFinal.classList.add("hidden");
	        piedra1.classList.add("hidden");   
	        piedra2.classList.add("hidden");   
	        papel1.classList.add("hidden");   
	        papel2.classList.add("hidden");   
	        tijeras1.classList.add("hidden");   
	        tijeras2.classList.add("hidden");   
	    }
	    
	    var eleccion = () => {
	        if(event.srcElement === elegirPiedra){
	            options.classList.add("hidden");
	            piedra1.classList.remove("hidden");
	            jugador = 1;
	        }
	        if(event.srcElement === elegirPapel){
	            options.classList.add("hidden");
	            papel1.classList.remove("hidden");
	            jugador = 2;
	        }
	        if(event.srcElement === elegirTijeras){
	            options.classList.add("hidden");
	            tijeras1.classList.remove("hidden");
	            jugador = 3;  
	        }
	        machine();
	    }
	    
	    var machine = () => {
	        let random = Math.random();
	        if(random <= 0.33){
	            piedra2.classList.remove("hidden");
	            maquina = 1;
	        }
	        if(random >= 0.34 && random <= 0.66){
	            papel2.classList.remove("hidden");
	            maquina = 2;
	        }
	        if(random >= 0.67) {
	            tijeras2.classList.remove("hidden");
	            maquina = 3;
	        }
	        console.log(random)
	        final();
	    }
	    
	    var final = () => {
	        cartelFinal.classList.remove("hidden");
	        if(jugador - maquina === 0){
	            tituloFinal.innerHTML = "Empate";
	            contador.innerHTML = `${contadorJugador} - ${contadorMaquina}`;
	        }
	        if(jugador === 1 && maquina === 2){
	            tituloFinal.innerHTML = "Perdiste...";
	            contadorMaquina++;
	            contador.innerHTML = `${contadorJugador} - ${contadorMaquina}`;
	        }
	        if(jugador === 1 && maquina === 3){
	            tituloFinal.innerHTML = "Ganaste!!!";
	            contadorJugador++;
	            contador.innerHTML = `${contadorJugador} - ${contadorMaquina}`;
	        }
	        if(jugador === 2 && maquina === 1){
	            tituloFinal.innerHTML = "Ganaste!!!";
	            contadorJugador++;
	            contador.innerHTML = `${contadorJugador} - ${contadorMaquina}`;
	        }
	        if(jugador === 2 && maquina === 3){
	            tituloFinal.innerHTML = "Perdiste...";
	            contadorMaquina++
	            contador.innerHTML = `${contadorJugador} - ${contadorMaquina}`;
	        }
	        if(jugador === 3 && maquina === 1){
	            tituloFinal.innerHTML = "Perdiste...";
	            contadorMaquina++;
	            contador.innerHTML = `${contadorJugador} - ${contadorMaquina}`;
	        }
	        if(jugador === 3 && maquina === 2){
	            tituloFinal.innerHTML = "Ganaste!!!";
	            contadorJugador++;
	            contador.innerHTML = `${contadorJugador} - ${contadorMaquina}`;
	        }
	    }
	    
	```

* **EmiGarello** (2)

	
	muy bueno

* **Jhon Alexander Romero Gonzaga** (2)
![](https://i.ibb.co/zmbSKyv/5fd09e93-81e3-4d50-88ea-403731d9b191.jpg)

* **Ulises Antonio Sámano Galván** (1)

	```
	    Si necesitas validar una sentencia utiliza:
	    
	```
	
	if(){}
	``` 
	    Si necesitas que ocurra algo en caso de que una sentencia sea falsa utiliza:
	    
	```
	
	if(){}  
	else{}
	``` 
	    Si necesitas validar múltiples sentencias, utiliza:
	    
	```
	
	if(){}  
	else if(){}
	``` 
	    O puedes hacer un if(){} else{} con otra sintaxis:
	    
	```
	
	_La condición_ ? _Lo que ocurrirá si es verdadera_ : _Lo que ocurrirá si es falsa_

* **Ulises Antonio Sámano Galván** (1)

	```
	     functionjuego (maquina,usuario)
	    {
	        if(maquina === usuario)
	        {
	            document.write(empate);
	        }
	        //Inicia piedra
	        elseif(usuario === "piedra" && maquina=== "papel")
	        {
	            document.write(g_maquina);
	        }
	        elseif(usuario === "piedra" && maquina=== "tijera")
	        {
	            document.write(g_usuario);
	        }
	        //Acaba piedra
	        //Inicia papel
	        elseif(usuario === "papel" && maquina=== "piedra")
	        {
	            document.write(g_usuario);
	        }
	        elseif(usuario === "papel" && maquina=== "tijera")
	        {
	            document.write(g_maquina);
	        }
	        //Acaba papel por compras de pánico :(
	        //Inicia tijeras
	        elseif(usuario === "tijera" && maquina=== "papel")
	        {
	            document.write(g_usuario);
	        }
	        elseif(usuario === "tijera" && maquina=== "piedra")
	        {
	            document.write(g_maquina);
	        }
	    }
	    
	    var maquina; 
	    var usuario;
	    var empate = "Empate";
	    var g_maquina = "Gana la máquina :(";
	    var g_usuario = "Ganaste :)";```
	    
	```

* **nicolasagreda** (1)

	
	var player1 = "piedra"  
	var maquina = “piedra”
	
	function juego(player1,maquina){  
	if(player1===“piedra” && maquina===“piedra”){  
	console.log(“nadie gana 😕”);  
	}else if(player1===“piedra” && maquina===“papel”){  
	console.log(“Gana la maquina 😦”);  
	}else if(player1===“piedra” && maquina===“tijera”){  
	console.log(“Ganaste 😃”);  
	}else if(player1===“papel” && maquina===“piedra”){  
	console.log(“Ganaste 😃”);  
	}else if(player1===“papel” && maquina===“papel”){  
	console.log(“nadie gana 😕”)  
	}else if(player1===“papel” && maquina===“tijera”){  
	console.log(“Gana la maquina 😦”);  
	}else if(player1===“tijera” && maquina===“piedra”){  
	console.log(“Gana la maquina 😦”);  
	}else if(player1===“tijera” && maquina===“papel”){  
	console.log(“Ganaste 😃”);  
	}else if(player1===“tijera” && maquina===“tijera”){  
	console.log(“nadie gana 😕”)  
	}else{  
	console.log(“selecciona una jugada valida”);  
	}  
	}  
	juego(player1,maquina);

* **Jonathan Vacas** (1)

	```
	    var jugador1 = "piedra"; //establecemos una variable al jugador 1
	    var jugador2 = "papel"; //establecemos una variable al jugador 2
	    if (jugador1 === "piedra" && jugador2 === "piedra") {
	         console.log("empate");} //comprueba si esa variable es correcta 
	    //al no ser correcta la anterior comprueba si esta es correcta
	         elseif(jugador1 === "piedra" && jugador2 === "papel") {console.log("Gana Jugador2");}
	    //al no ser correcta la anterior comprueba si esta es correcta 
	         elseif(jugador1 === "piedra" && jugador2 === "tijera"){console.log("Gana Jugador1");}
	    //al no ser correcta la anterior comprueba si esta es correcta
	         elseif(jugador1 === "papel" && jugador2 === "piedra"){console.log("Gana Jugador1");}
	    //al no ser correcta la anterior comprueba si esta es correcta
	         elseif(jugador1 === "papel" && jugador2 === "papel"){console.log("Empate");}
	    //al no ser correcta la anterior comprueba si esta es correcta
	         elseif(jugador1 === "papel" && jugador2 === "tijera"){console.log("Gana Jugador2");}
	    //al no ser correcta la anterior comprueba si esta es correcta
	         elseif(jugador1 === "tijera" && jugador2 === "piedra"){console.log("Gana Jugador2");}
	    //al no ser correcta la anterior comprueba si esta es correcta
	         elseif(jugador1 === "tijera" && jugador2 === "papel"){console.log("Gana Jugador1");}
	    //al no ser correcta la anterior comprueba si esta es correcta
	         elseif(jugador1 === "tijera" && jugador2 === "tijera"){console.log("Empate");}
	    //al no ser correcta ninguna devuelve "No esta Bien establecidos los valores de los jugadores
	         else {console.log("No esta bien establecidos los valores de los jugadores");}
	    
	```

* **FredySarmiento** (1)

	```
	    var opcJ1=prompt("Seleccione el valor 1. piedra 2. papel 3.Tijrea");
	    
	    var opcJ2=prompt("Seleccione el valor 1. piedra 2. papel 3.Tijrea");
	    
	    
	    if (opcJ1 === opcJ2 )
	    {
	        console.log ("Empate");
	    }elseif (opcJ1 ==1 && opcJ2 ==2)
	    {
	        console-log("Gana jugador 2 usaste papel");
	    }elseif (opcJ1 ==2 && opcJ2 ==3){
	        console.log("Gana jugador 2 usaste Tijera");
	    }elseif (opcJ1 ==3 && opcJ2 ==1){
	        console.log("Gana jugador 2 usaste piedra");
	    }elseif (opcJ2 ==1 && opcJ1 ==2)
	    {
	        console.log("Gana jugador 1 usaste papel");
	    }elseif (opcJ2 ==2 && opcJ1 ==3){
	        console.log("Gana jugador 1 usaste Tijera");
	    }elseif (opcJ2 ==3 && opcJ1 ==1){
	        console.log("Gana jugador 1 usaste piedra");
	    }
	    
	```

* **jameskristof** (1)

	```
	    function piedraPapeloTijera()
	    {
	        var respuesta_jugador1 = prompt("Elige piedra, papel, tijera");
	        var respuesta_jugador2 = prompt("Elige piedra, papel, tijera");
	        if (respuesta_jugador1 === "piedra" && respuesta_jugador2 === "tijera")
	        {
	            console.log("ganó jugador 1");
	        }
	        elseif (respuesta_jugador1 === "piedra" && respuesta_jugador2 === "papel")
	        {
	            console.log("ganó jugador 2");
	        }
	        elseif (respuesta_jugador1 === "tijera" && respuesta_jugador2 === "piedra")
	        {
	            console.log("ganó jugador 2");
	        }
	        elseif (respuesta_jugador1 === "tijera" && respuesta_jugador2 === "papel")
	        {
	            console.log("ganó jugador 1");
	        }
	        elseif (respuesta_jugador1 === "papel" && respuesta_jugador2 === "tijera")
	        {
	            console.log("ganó jugador 2");
	        }
	        elseif (respuesta_jugador1 === "papel" && respuesta_jugador2 === "piedra")
	        {
	            console.log("ganó jugador 1");
	        }
	        else
	        {
	            console.log("comiencen otra vez");
	        }
	    }```
	    
	```

* **max23esau** (1)

	
	Les dejo mi aporte:  
	<https://max23esau.github.io/Game/>  
	[Repositorio](https://github.com/Max23Esau/Game)

* **Daniel Acevedo Rodriguez** (1)

	```
	    function PPT(usuario1 , usuario2) {
	    var usuario1 = prompt ("jugador 1 escribe piedra, papel o tijera");
	    var usuario2 =  prompt ("jugador 2 escribe piedra, papel o tijera");
	    
	        if(usuario1 === "piedra" && usuario2 === "papel"){
	         console.log("Gana jugador 2");
	        } elseif (usuario1 === "papel" && usuario2 === "tijera"){
	            Console.log("Gana jugador 2");
	        } elseif (usuario1 === "tijera" && usuario2 === "piedra"){
	            Console.log("Gana jugador 2");
	        }
	          elseif (usuario1 === "tijera" && usuario2 === "papel"){
	            Console.log("Gana jugador 1");
	        }
	          elseif (usuario1 === "papel" && usuario2 === "piedra"){
	            Console.log("Gana jugador 1");
	        }
	          elseif (usuario1 === "piedra" && usuario2 === "tijera"){
	            Console.log("Gana jugador 1");
	        } else {
	            console.log ("elija de nuevo");
	        }
	    }```
	    
	```

* **Ariel Alejandro Ureña Morales** (1)

	
	Yo hice uno de jugador 1 contra jugador 2.
	``` 
	    var usuario1 = prompt("Jugador 1, escribe tu nombre.");
	    var usuario2 = prompt("Jugador 2, escribe tu nombre.");
	    
	    var eleccion1 = prompt("Jugador 1, elige escribiendo piedra, papel o tijera.");
	    var eleccion2 = prompt("Jugador 2, elige escribiendo piedra, papel o tijera.");
	    
	    var papel = "papel";
	    var piedra = "piedra";
	    var tijera = "tijera";
	    
	    if(eleccion1 === papel && eleccion2 === piedra){
	        alert("Jugador 1 gana, papel le gana a piedra");
	    }elseif(eleccion1 === papel && eleccion2 === tijera){
	        alert("Jugador 2 gana, tijera  le gana a papel");
	    }elseif(eleccion1 === piedra && eleccion2 === papel){
	        alert("Jugador 2 gana, papel  le gana a piedra");
	    }elseif(eleccion1 === piedra && eleccion2 === tijera){
	        alert("Jugador 1 gana, piedra  le gana a tijera");
	    }elseif(eleccion1 === tijera && eleccion2 === papel){
	        alert("Jugador 1 gana, tijera  le gana a papel");
	    }elseif(eleccion1 === tijera && eleccion2 === piedra){
	        alert("Jugador 2 gana, tijera  le gana a papel");
	    }
	    elseif(eleccion1 = eleccion2){
	        alert("Es un empate");
	    }
	    
	```

* **Ariel Alejandro Ureña Morales** (1)

	
	Excelente clase, todo bien explicado c:

* **Carlos Luis García** (1)

	
	var usuario1 = "Carlos"  
	var usuario2 = "Pedro"  
	var piedra = "piedra"  
	var papel = "papel"  
	var tijera = "tijera"  
	var manoUsuario1 = piedra  
	var manoUsuario2 = papel
	
	resultado(manoUsuario1, manoUsuario2)
	
	function resultado(mU1, mU2) {  
	var ganador  
	if ((manoUsuario1 == piedra) && (manoUsuario2 == tijera)) {  
	ganador = "El ganador es: " \+ usuario1  
	} else if ((mU1 == piedra) && (mU2 == papel)) {  
	ganador = "El ganador es: " \+ usuario2  
	} else if ((mU1 == papel) && (mU2 == piedra)) {  
	ganador = "El ganador es: " \+ usuario1  
	} else if ((mU1 == papel) && (mU2 == tijera)) {  
	ganador = "El ganador es: " \+ usuario2  
	} else if ((mU1 == tijera) && (mU2 == papel)) {  
	ganador = "El ganador es: " \+ usuario1  
	} else if ((mU1 == tijera) && (mU2 == piedra)) {  
	ganador = "El ganador es: " \+ usuario2  
	} else {  
	ganador = “Intentalo de nuevo”  
	}  
	return ganador  
	}

* **jmgaitan** (1)

	```
	    var jugador1
	    var opciones = ['piedra', 'papel', 'tijera']
	    
	    functionresultado() {
	        if (jugador1 === jugador2) {
	            alert('han empatado')
	            iniciarJuego()
	        } else {
	            if (((jugador1 === 'piedra') && (jugador2 === 'papel')) || ((jugador1 === 'tijera') && (jugador2 === 'piedra')) || ((jugador1 === 'papel') && (jugador2 === 'tijera'))) {
	                alert('ha ganado el jugador2 con ' + jugador2 + ' ' + 'a ' + jugador1)
	                iniciarJuego()
	    
	            } else {
	                alert('ha ganado el jugador1 con ' + jugador1 + ' ' + 'a ' + jugador2)
	    
	            }
	        }
	    }
	    
	    functioniniciarJuego() {
	        functionelegirJugada() {
	    
	            jugador1 = prompt('elija entre piedra, papel o tijera')
	            if ((jugador1 === 'piedra') || (jugador1 === 'papel') || (jugador1 === 'tijera')) {
	                jugador2 = this.opciones[Math.floor(Math.random() * opciones.length)]
	                console.log(jugador1)
	                console.log(jugador2)
	            } else {
	                elegirJugada()
	            }
	            resultado()
	        }
	        elegirJugada();
	    }
	    
	    iniciarJuego()```
	    
	```

* **Carlos Cipagauta** (1)

	```
	    <style>
	    body {
	    
	    }
	    </style>
	    
	    
	    
	    
	    <script>
	    // puedes leer?
	     
	      const PIEDRA=1
	      const PAPEL=2
	      const TIJERA=3
	      
	      const EMPATE=4
	      const GANA_U=5
	      const GANA_M=6
	      
	      var valorUsuario=parseInt(window.prompt("Digite su valor","1,2 o 3"));
	      
	      var ganador=jugar(valorUsuario)
	      
	      if(ganador===EMPATE){
	        alert("Es un empate")
	      }
	      if(ganador===GANA_U){
	        alert("GANA USUARIO")
	      }
	      
	       if(ganador===GANA_M){
	        alert("GANA MAQUINA")
	      }
	      
	      //console.log(jugar(PAPEL))
	      //console.log(jugar(TIJERA))
	      //maquina()
	     
	      functionjugar (valorUsuario){
	        console.log("u:"+valorUsuario)    
	        var valorMaquina=maquina()
	        console.log("m:"+valorMaquina)
	        
	        var resultado=-1
	        if (valorUsuario===valorMaquina){       
	            resultado=EMPATE
	        }
	        
	        if(valorUsuario===PIEDRA  && valorMaquina===PAPEL){
	            resultado=GANA_M
	        }
	        
	        if(valorUsuario===PAPEL  && valorMaquina===PIEDRA){
	            resultado=GANA_U
	        }
	        
	        if(valorUsuario===TIJERA  && valorMaquina===PIEDRA){
	            resultado=GANA_M
	        }
	           
	        if(valorUsuario===TIJERA  && valorMaquina===PAPEL){
	            resultado=GANA_U
	        }
	        
	        if(valorUsuario===PIEDRA  && valorMaquina===TIJERA ){
	            resultado=GANA_U
	        }
	        
	        if(valorUsuario===PAPEL  && valorMaquina===TIJERA ){
	            resultado=GANA_M
	        }
	        
	        
	      	return resultado
	      }
	      
	      /*generar numero aleatorio maquina*/
	      functionmaquina(){
	      	var valorMaquina
	        valorMaquina=Math.floor(Math.random() * 3) + 1   
	        return valorMaquina;
	      }
	      
	      //https://stackoverflow.com/questions/4959975/generate-random-number-between-two-numbers-in-javascript
	      
	      
	     
	    
	    </script>```
	    
	```

* **Vicente Andrés Muñoz Moller** (1)

	```
	    var localPlayer = prompt("1 for Rocks, 2 for Scissors or 3 for Paper ");
	    var localConsole = 2;
	    
	    functiontheGame() {
	        if (localPlayer == localConsole) {
	            console.log("This is a tie");
	        }
	        elseif(localPlayer == 1) {
	            console.log("You are the winner");
	        }
	        elseif(localPlayer == 3) {
	            console.log("You lost");
	        }
	        else {
	            console.log("The value " + localPlayer + " is not a valid option, please try again");
	        }
	    }
	    
	    theGame();```
	    
	```

* **david1pc** (1)

	```
	    var opcion = "tijera";
	    
	    function PiedraPapel(a){
	      
	      var b = "piedra";
	    
	      if (a == "piedra" && b == "piedra" || a == "papel" && b == "papel" || a == "tijera" && b == "tijera"){
	        console.log("Empate");
	      }elseif(a == "piedra" && b == "tijera" || a == "papel" && b == "piedra" || a == "tijera" && b == "papel"){
	        console.log("Gana el usuario");
	      }elseif(a == "tijera" && b == "piedra" || a == "piedra" && b == "papel" || a == "papel" && b == "tijera"){
	        console.log("Gana la maquina");
	      }else{
	        console.log("Digite una opcion valida");
	      }
	      
	    }
	    
	    PiedraPapel(opcion);```
	    
	```

* **ELITA CAMPOJO GUEVARA** (1)

	
	Con un poco de ayuda pero lo hice.
	
	![juego tijera-papel-piedra.png](https://static.platzi.com/media/user_upload/juego%20tijera-papel-piedra-3c4c3851-b3cc-49de-853e-b9fccfdd3975.jpg)
	
	Gracias a los compañeros por su aporte.

* **luistaurik** (1)

	
	No logré hacerlo, no me corre 😦

* **Alejandro Luján** (1)

	
	Listo!, me costo un poco de trabajo, pero lo terminé:
	``` 
	    let election1 = prompt("Que vas a querer? \n -Rock \n -Paper \n -Scissors");
	    let election = election1.toLowerCase();
	    let machineNumber = Math.ceil(Math.random() * 3);
	    
	    let machineOptions = { 1: "rock", 2: "paper", 3: "scissors" };
	    
	    let machineElection = machineOptions[machineNumber];
	    
	    console.log(machineNumber);
	    
	    console.log(machineElection);
	    
	    console.log(election);
	    
	    /*rock wins scissors
	      scissors wins paper
	      paper wins rock
	     ----------------------
	      rock lose paper
	      scissors lose rock
	      paper lose scissors
	    */
	    
	    functionGame(playerElection) {
	      if (playerElection != machineElection) {
	        if (playerElection === "paper" && machineElection === "scissors") {
	          console.log("You Lose!");
	        } else {
	          if (playerElection === "rock" && machineElection === "paper") {
	            console.log("You Lose!");
	          } else {
	            if (playerElection === "scissors" && machineElection === "rock") {
	              console.log("You Lose!");
	            } else {
	              if (playerElection === "scissors" && machineElection === "paper") {
	                console.log("You Win!");
	              } else {
	                if (playerElection === "paper" && machineElection === "rock") {
	                  console.log("You Win!");
	                } else {
	                  if (playerElection === "rock" && machineElection === "scissors") {
	                    console.log("You Win!");
	                  }
	                }
	              }
	            }
	          }
	        }
	      } else {
	        console.log("Draw!!");
	      }
	    }
	    
	    Game(election);
	    
	    
	```

* **HumbertoMLL** (1)

	
	Si metemos todo dentro de la función juego, podemos cargar el código en consola, y solo ejecutar juego(), y evitamos que se queden guardados los valores de las variables
	``` 
	    const juego = () => {
	      const electionPlayer = prompt("¿piedra, papel ó tijera?");
	      const options = ["piedra", "papel", "tijera"];
	      const electionMachine = options [Math.floor(Math.random() * options.length)];
	    
	      if ( electionMachine === "piedra") {
	        if (electionPlayer === "tijera") {
	        console.log("Perdiste");
	        } elseif(electionPlayer ==="papel") {
	          console.log("Ganaste")
	        } else {
	          console.log("Empatamos")
	        }
	      } elseif(electionMachine === "papel") {
	        if (electionPlayer === "tijera") {
	          console.log("Ganaste");
	        } elseif (electionPlayer === "piedra"){
	          console.log("Perdiste");
	        } else {
	          console.log("Empatamos")
	        }
	      } elseif (electionMachine === "tijera") {
	        if(electionPlayer ==="papel"){
	          console.log("Ganaste");
	        } elseif (electionPlayer === "piedra") {
	          console.log("Perdiste");
	        } else {
	          console.log("Empatamos");
	        }
	      }
	    }
	    
	    juego();
	    
	```

* **HumbertoMLL** (1)

	```
	    const jugador = prompt("¿piedra, papel ó tijera?");
	    const options = ["piedra", "papel", "tijera"];
	    
	    const machine = ()=>{
	    const random = options [Math.floor(Math.random() * options.length)];
	    console.log(random);
	    return random;
	    }
	    
	    
	    const juego = (a, b)=> {
	    let electionPlayer = a;
	    let electionMachine = b;
	    
	      if ( electionMachine === "piedra") {
	        if (electionPlayer === "tijera") {
	        console.log("Perdiste");
	        } elseif(electionPlayer ==="papel") {
	          console.log("Ganaste")
	        } else {
	          console.log("Empatamos")
	        }
	      } elseif(electionMachine === "papel") {
	        if (electionPlayer === "tijera") {
	          console.log("Ganaste");
	        } elseif (electionPlayer === "piedra"){
	          console.log("Perdiste");
	        } else {
	          console.log("Empatamos")
	        }
	      } elseif (electionMachine === "tijera") {
	        if(electionPlayer ==="papel"){
	          console.log("Ganaste");
	        } elseif (electionPlayer === "piedra") {
	          console.log("Perdiste");
	        } else {
	          console.log("Empatamos");
	        }
	      }
	    }
	    
	    juego(jugador, machine());
	    
	    
	```

* **platzerito080420202** (1)

	
	Sí soy un ano

* **Milton Enríquez Torres** (1)

	```
	    <!DOCTYPE html>
	    <html>
	        <head>
	           <script>
	                // Game of rock,paper,scissors
	               // si quieres cambiar el idioma, modifica estas variables
	                var option1="rock";
	                var option2="paper";
	                var option3="scissors";
	                var cpu=Math.floor(Math.random()*3)+1;
	    
	                // entrada de datos
	                var word=prompt("Escribe "+option1+", "+option2+" o "+option3);
	                if(word==option1||word==option2||word==option3)
	                    document.write(getUserFunction(word));
	                else
	                    document.write("Error, no se encuentra la palabra "+"<strong>"+word+"</strong>");
	                
	                functiongetCPUOption(){
	                    if(cpu==1)
	                      return option1; // rock
	                    elseif(cpu==2)
	                        return option2; // paper
	                    else
	                        return option3; // scissors
	                }
	    
	                functionmessage1(option,cpu){
	                   return"Ganaste, tu opcion: "+option+", opcion del CPU: "+getCPUOption();
	                }
	    
	                functionmessage2(option,cpu){
	                    return"Empate. Tu opcion: "+"<strong>"
	                    +option+"</strong>"+", la del CPU: "+"<strong>"
	                    +cpu+"</strong>";
	                }
	    
	                functiongetUserFunction(option){
	                    if(option.toLowerCase()==option1&&getCPUOption()==option3||
	                       option.toLowerCase()==option2&&getCPUOption()==option1||
	                       option.toLowerCase()==option3&&getCPUOption()==option2)
	                        return message1(option.toLowerCase(),getCPUOption());
	                    elseif(option.toLowerCase()==getCPUOption())
	                        return message2(option.toLowerCase(),getCPUOption());               
	                    else
	                         return"Perdiste, tu opcion: "+option+", opcion del CPU: "+getCPUOption();
	                       
	                }
	            
	            </script>
	        </head>
	        <body>
	        </body>
	    </html> 
	    
	```

	* **luistaurik** (1)

		
		Creo que esto es mucho más avanzado de lo del cuso.

* **Julio Cesar Cedeño Alemar** (1)

	```
	    var nombreJugador=prompt("Introduce tu nombre para comenzar");
	    
	    alert("Bienvenido: "+nombreJugador);
	    
	    jugada_jugador=prompt("Introduce 1 para jugar piedra, introduce 2 para jugar papel, introduce 3 para jugar tijeras.");
	    
	    functionjugadaMaquina(){
	    
	      var jugadaMaquina = Math.floor(Math.random() *3 +1);
	      return jugadaMaquina;
	    }
	    
	    functionjugar(jugador, maquina){
	      var jugada_jugador=jugador;
	      var jugadaMaquina= maquina;
	    
	      if(jugada_jugador==1 && jugadaMaquina==2 ){
	        console.log(nombreJugador+ ": Piedra Maquina: Papel Ganador: Maquina")
	      }
	      if(jugada_jugador==1 && jugadaMaquina==1 ){
	        console.log(nombreJugador+ ": Piedra Maquina: Piedra Ganador: Empate");
	      }
	      if(jugada_jugador==1 && jugadaMaquina==3 ){
	        console.log(nombreJugador+ ": Piedra Maquina: Tijeras Ganador: "+nombreJugador);
	      }
	    
	      if(jugada_jugador==2 && jugadaMaquina==1 ){
	        console.log(nombreJugador+ ": Papel Maquina: Piedra Ganador: "+nombreJugador)
	      }
	      if(jugada_jugador==2 && jugadaMaquina==2 ){
	        console.log(nombreJugador+ ": Papel Maquina: Papel Ganador: Empate");
	      }
	      if(jugada_jugador==2 && jugadaMaquina==3 ){
	        console.log(nombreJugador+ ": Papel Maquina: Tijeras Ganador: Maquina");
	      }
	    
	      if(jugada_jugador==3 && jugadaMaquina==1 ){
	        console.log(nombreJugador+ ": Tijeras Maquina: Piedra Ganador: Maquina")
	      }
	      if(jugada_jugador==3 && jugadaMaquina==3 ){
	        console.log(nombreJugador+ ": Tijeras Maquina: Tijera Ganador: Empate");
	      }
	      if(jugada_jugador==3 && jugadaMaquina==2 ){
	        console.log(nombreJugador+ ": Tijeras Maquina: Papel Ganador: Maquina");
	      }
	    }
	    
	    jugar(jugada_jugador,jugadaMaquina());
	    
	    
	```

* **jandresfr** (1)

	
	function ppt(){
	``` 
	    var maquina = "piedra";
	    var jugador = "piedra";
	    
	    if (maquina === "piedra" && jugador === "piedra") {
	        console.log("Empate. Piedra con piedra no hace nada");
	    } else if (maquina === "piedra" && jugador === "papel"){
	        console.log("Gana jugador porque papel envuelve a piedra");
	    } else if (maquina === "piedra" && jugador === "tijera"){
	        console.log("Gana maquina porque piedra daña a tijera");
	    } else if (maquina === "papel" && jugador === "piedra"){
	        console.log("Gana maquina porque papel envuelve a piedra");
	    } else if (maquina === "papel" && jugador === "papel"){
	        console.log("Empate. Papel con papel no hace nada");
	    } else if (maquina === "papel" && jugador === "tijera"){
	        console.log("Gana jugador porque tijera daña a papel");
	    } else if (maquina === "tijera" && jugador === "piedra"){
	        console.log("Gana jugador porque piedra daña a tijera");
	    } else if (maquina === "tijera" && jugador === "papel"){
	        console.log("Gana maquina porque tijera daña a papel");
	    } else if (maquina === "tijera" && jugador === "tijera"){
	        console.log("Empate. Tijera con tijera no hace nada");
	    } else {
	        console.log("Opción no contemplada en los elementos");
	    }
	    
	```
	
	}
	
	console.log(ppt());

* **garciafran** (1)

	
	muy interesante la instruccion del operador ternario.
	``` 
	    if (true){
	        console.log("verdadero");
	    } else {
	        console.log("falso");
	    }
	    
	    var edad = 18;
	    
	    
	    
	    if (edad === 18){
	        console.log("puede votar, su primera votacion");
	    } elseif (edad > 18) {
	        console.log("puede votar de nuevo");
	    } else {
	        console.log("aun no puedes votar")
	    }
	    
	    //operador ternario
	    
	    edad >= 18 ? "puede votar" : "no puede votar";
	    
	    var numero = 1;
	    
	    var resultado = numero === 1 ? "si soy el numero uno" : "no soy el numero uno"```
	    
	```

* **JheysonEGalvis** (1)

	
	Porqué cuando ejecuto esto sempre me sale “Aun no puedes votar” así ponga una edad mayor a 18?  
	var edad = prompt;  
	var edad = String(edad);  
	prompt("¿cuál es tu edad?");  
	if(edad === 18){  
	alert(“Puedes votar, será tu primera votación”);  
	}else if(edad > 18){  
	alert(“Puedes votar de nuevo”);  
	}else{  
	alert(“Aun no puedes votar”);  
	}

	* **lmgaero** (1)

		
		En tu segunda línea estás haciendo una coerción explícita a String, es decir, el dato que ingrese el usuario, que por defecto ya es un string, lo estás convirtiendo en string. Y luego comparando con “===” contra un valor numérico.
		
		Cambia tu método String(edad), por Number(edad), esto debería solucionar tu problema.
		
		Te sugiero ver nuevamente las clases de coerción y operadores.

* **Arturo Linares** (1)

	
	var piedra = 0  
	var papel = 0  
	var tijera = 0
	
	if(piedra === 1 && papel === 2) {  
	console.log(“Gana Papel”);  
	}else if (piedra === 1 && tijera === 3) {  
	console.log(“Gana Piedra”);  
	}else if (papel === 2 && tijera === 3) {  
	console.log(“Gana Tijera”);  
	}else{console.log(“empate”);}
	
	algo básico y rápido jajaja

* **Luis Alejandro Medina Escobar** (1)

	
	Vaya, pensé que me iba a resultar más sencillo hacer este ejercicio.
	``` 
	    var math = ((Math.floor(Math.random()*3))+1);
	    
	    
	    var px = mx.u * mx.m;
	    
	    mx.m = math;
	    
	    var machine_trans;
	    
	    
	    
	    
	    function translator() {
	    if (math == 1) {
	        machine_trans = "Piedra";
	    } else if (math == 2){
	        machine_trans = "Papel";
	    }
	        else if(math == 3){
	            machine_trans = "Tijeras";
	        }
	    return(machine_trans);
	    }
	    
	    function check(){
	        
	        if (mx.u == mx.m){
	            console.log("Es un empate!" + machine_trans);
	            result = "empate";
	        } else if ((mx.u == 1&& mx.m === 3)||(mx.u == 2&& mx.m === 1)||(mx.u == 3&& mx.m === 2)){
	            prompt("Eres el Ganador! Machine escogió:" + machine_trans);
	            result = "Usuario gana";
	        } else if ((mx.u == 1&& mx.m === 2)||(mx.u == 2&& mx.m === 3)||(mx.u == 3&& mx.m === 1)){
	            prompt("Eres el Perdedor! Machine escogió:" + machine_trans);
	            result = "Usuario pierde";
	        } else {
	            console.log("Por favor escoge una opción válida." + user_selection);
	        }
	        return(user_selection);
	    }
	    
	    translator(math);
	    
	    var user_selection = prompt("1 rock | 2 paper | 3 scissors \n\nWrite one: ");
	    
	    var mx = {u: user_selection, m: math};
	        console.log(mx);
	        console.log(math);
	    
	    check(user_selection);
	    
	    
	    
	```

* **Luis Alejandro Medina Escobar** (1)

	
	Condition. Importante muy práctico.

* **luisglopez7777** (1)

	```
	    functionrandom(){
	      n = Math.floor(Math.random()*3)
	      if(n === 0){
	        n = 'piedra'
	        console.log('La computadora elige: ' + n)
	      }elseif(n === 1){
	        n = 'papel'
	        console.log('La computadora elige: ' + n)
	      }else{
	        n = 'tijera'
	        console.log('La computadora elige: ' + n)
	      }
	    }
	    
	    functionjugar(eleccion){
	      console.log('Elegiste: ' + eleccion)
	      random()
	      if(eleccion === n){
	        console.log('Empate')
	      }elseif(eleccion === 'piedra' && n === 'papel'){
	        console.log('Perdiste')
	      }elseif(eleccion === 'piedra' && n === 'tijera'){
	        console.log('Ganaste!')
	      }elseif(eleccion === 'tijera' && n === 'piedra'){
	        console.log('Perdiste')
	      }elseif(eleccion === 'tijera' && n === 'papel'){
	        console.log('Ganaste')
	      }elseif(eleccion === 'papel' && n === 'tijera'){
	        console.log('Perdiste')
	      }elseif(eleccion === 'papel' && n === 'piedra'){
	        console.log('Ganaste')
	      }
	    }
	    
	    jugar('papel')```
	    
	```

* **miguelgz18** (1)

	```
	    var opciones = ['piedra', 'papel', 'tijera'];
	            var numeroRandom = Math.floor( Math.random() * 3 );
	            var opcionMaquina = opciones[numeroRandom];
	    
	            var valorUsuario = prompt('Escoge entre piedra, papel o tijera, a ver si ganas');
	    
	            functionjuego( valorUsuario ) {
	                if( valorUsuario === opcionMaquina ){
	                    console.log('Empate');
	                } elseif ( valorUsuario == 'piedra' && opcionMaquina == 'papel' ) {
	                    console.log('Has perdido, papel atrapa a piedra');
	                } elseif ( valorUsuario == 'piedra' && opcionMaquina == 'tijera' ){
	                    console.log('Has ganado, piedra destruye a tijera');
	                } elseif ( valorUsuario == 'papel' && opcionMaquina == 'piedra' ) {
	                    console.log('Has ganado, papel atrapa a piedra');
	                } elseif ( valorUsuario = ' papel' && opcionMaquina == 'tijera' ) {
	                    console.log('Has perdido, tijera corta papel');
	                } elseif ( valorUsuario == 'tijera' && opcionMaquina == 'piedra' ) {
	                    console.log('Has perdido, piedra destruye papel');
	                } elseif ( valorUsuario == 'tijera' && opcionMaquina == 'papel' ) {
	                    console.log('Has ganado, tijera corta papel');
	                }
	             }  
	             juego( valorUsuario );```
	    
	```

* **David Emanuel Espinoza Romero** (1)

	
	<script>  
	var max = 3;  
	var min = 1;  
	var ianumber = aleatorio(max, min);  
	var usernumber = aleatorio(max, min);
	``` 
	      if (ianumber => 1 && ianumber <= 3) {
	        if (ianumber == usernumber) {
	          console.log("Empate Vuelve a intentar");
	          console.log(`Escogiste =${usernumber} la IA=${ianumber}`);
	        }else if (ianumber != usernumber){
	          if (ianumber == 3 && usernumber == 1 || usernumber == 2 && ianumber == 1 || usernumber == 3 && ianumber == 2 ) {
	            console.log("Ganaste!! La IA quiere revancha");          
	            console.log(`Escogiste =${usernumber} la IA=${ianumber}`);
	          } else {
	            console.log("Perdiste!! la IA se rie! ¿Quieres revancha? ");
	            console.log(`Escogiste =${usernumber} la IA=${ianumber}`);          
	          }
	        }
	      }else {
	        console.log(`Eso no es un numero ${usernumber} escoge del 1 al 3 chistoso!!`);
	      }
	    
	    
	    function aleatorio (max, min) {
	      var r = Math.floor(Math.random() *(max - min + 1)) + min;
	      return r;
	    }
	    
	```
	
	</script>

* **eduardovinagre** (1)

	```
	    const PIEDRA = 1;
	    const PAPEL = 2;
	    const TIJERA = 3;
	    
	    //0-Empate, 1-Gana el usuario1, -1 Gana el usuario2
	    function determinarGanador(usuario1, usuario2) {
	      if (usuario1 === usuario2) {
	        return0; //Empate
	      }
	      //Condiciones donde el usuario1 gana
	      if (
	        (usuario1 === PIEDRA && usuario2 === TIJERA) ||
	        (usuario1 === PAPEL && usuario2 === PIEDRA) ||
	        (usuario1 === TIJERA && usuario2 == PAPEL)
	      )
	        return1;
	      elsereturn-1;
	    }
	    
	    function mostrarResultado(resultado) {
	      if (resultado === 0) console.log("Es un empate");
	      elseif (resultado > 0) {
	        console.log("Felicidades, Ganaste");
	      } else {
	        console.log("Suerte para la próxima");
	      }
	    }
	    
	    function jugar(usuario1, usuario2) {
	      let resultado = determinarGanador(usuario1, usuario2);
	      mostrarResultado(resultado);
	    }
	    
	    jugar(PIEDRA, PIEDRA);
	    jugar(PIEDRA, PAPEL);
	    jugar(PIEDRA, TIJERA);
	    jugar(PAPEL, PIEDRA);
	    jugar(PAPEL, PAPEL);
	    jugar(PAPEL, TIJERA);
	    jugar(TIJERA, PIEDRA);
	    jugar(TIJERA, PAPEL);
	    jugar(TIJERA,TIJERA);
	    
	```

* **victor-castaneda-rivera** (1)

	
	// Juego Piedra papel o tijera
	
	var piedra = 0 ;  
	var papel = 1;  
	var tijera = 2;
	
	var maquina = Math.floor(Math.random() * 3);  
	return numero;
	``` 
	          function piedraPapelOTijera(jugador1){
	    if (jugador1 === maquina){
	    console.log (" hay empate, juega de nuevo! "); 
	       }
	        else if(maquina === 0 && jugador1 === 1){
	              console.log ('Felicidades!, papel gana piedra');
	            }
	            else if(maquina === 1 && jugador1 === 0){
	                    console.log ('Felicidades, papel gana piedra');
	                 }
	                 else if(maquina === 0 && jugador1 === 2){
	                         console.log ('Felicidades, piedra gana a tijera');
	                    }
	                    else if(maquina === 2 && jugador1 === 0){
	                            console.log ('Felicidades piedra gana a tijera');
	                       }
	                       else if(maquina === 1 && jugador1 === 2){
	                               console.log ('tijera gana a papel');
	                       }
	                       else if(maquina === 2 && jugador1 === 1){
	                        console.log ('tijera gana a papel');
	                       }
	    
	```
	
	}
	
	piedraPapelOTijera();
	
	// Analisis del juego
	
	//empate un comparativo === estricatamente igual a
	
	// 0 + 0 = 0 piedra  
	// 1 + 1 = 0 papel  
	// 2 + 2 = 0 tijera
	
	// piedra gana
	
	// 0 + 0 = 0 === piedra vs piedra = empate  
	// 0 + 1 = 1 piedra vs papel = gana papel  
	// 0 + 2 = 0 piedra vs tijera= gana piedra
	
	// papel gana
	
	// 1 + 0 = 1 papel vs piedra = gana papel  
	// 1 + 1 = 1 === papel vs papel = empate  
	// 1 + 2 = 2 papel vs tijera = gana tijera
	
	// papel tijera
	
	// 2 + 0 = 1 tijera vs piedra = gana piedra  
	// 2 + 1 = 2 tijera vs papel = gana tijera  
	// 2 + 2 = 2 === tijera vs tijera = empate

	* **Robinson Matias Aguilar Bascuñan** (1)

		
		intenta hacerlo con un stwich

* **Jharell Alejandra Hidalgo Loya** (1)

	
	condition ? true : fase;  
	es igual a:  
	condición “then” valor a regresar “else” valor a regresar

* **Benjamin_Espinosa_N** (1)

	
	La version contra la máquina, hice lo que pude:
	``` 
	    var jugadorA = prompt("Jugador A, elige piedra, papel o tjera");
	    var aleatorio = Math.floor( Math.random() * 3 ) + 1;
	    
	    console.log(aleatorio);
	    
	        if (aleatorio === 1)
	        {
	            var maquina = "piedra";
	        }
	        elseif (aleatorio === 2)
	        {
	            var maquina = "papel";
	        }
	        elseif (aleatorio === 3)
	        {
	            var maquina = "tijera";
	        }
	        console.log(maquina);
	    
	    comienzaJuego()
	    
	    function comienzaJuego()
	    {
	        if(jugadorA === "piedra" && maquina === "tijera" || jugadorA === "papel" && maquina === "piedra" || jugadorA === "tijera" && maquina === "papel")
	        {
	            alert("Jugador A resulta ganador!");
	        }
	        elseif (jugadorA === "piedra" && maquina === "papel" || jugadorA === "papel" && maquina === "tijera" || jugadorA === "tijera" && maquina === "piedra")
	        {
	            alert("La máquina resulta ganador!");
	        }
	        elseif (jugadorA === "piedra" && maquina === "piedra" || jugadorA === "papel" && maquina === "papel" || jugadorA === "tijera" && maquina === "tijera")
	        {
	            alert("Empate!! El ganador se eligira con una pelea a muerte con cuchillos");
	        }
	        else 
	        {
	            alert("Jueguen bien!");
	        }
	    }
	    
	```

* **Benjamin_Espinosa_N** (1)

	
	Bueno, es la version PVP… Aún así funciona
	``` 
	    var jugadorA = prompt("Jugador A, elige piedra, papel o tjera");
	    var jugadorB = prompt("Jugador B, elige piedra, papel o tjera");
	    
	        if(jugadorA === "piedra" && jugadorB === "tijera"||jugadorA === "papel" && jugadorB === "piedra"||jugadorA === "tijera" && jugadorB === "papel")
	        {
	            alert("Jugador A resulta ganador!");
	        }
	        else if (jugadorA === "piedra" && jugadorB === "papel"||jugadorA === "papel" && jugadorB === "tijera"||jugadorA === "tijera" && jugadorB === "piedra")
	        {
	            alert("Jugador B resulta ganador!");
	        }
	        else if (jugadorA === "piedra" && jugadorB === "piedra"||jugadorA === "papel" && jugadorB === "papel"||jugadorA === "tijera" && jugadorB === "tijera")
	        {
	            alert("Empate!! El ganador se eligira con una pelea a muerte con cuchillos");
	        }
	        else 
	        {
	            alert("Jueguen bien!");
	        }
	    
	```

* **Juan Teixeira** (1)

	```
	    var herramientas = [ 'piedra', 'papel', 'tijera']
	    var jugador = prompt(`Escribe la opción que quieres usar: \n piedra \n  papel \n  tijeras`)
	    
	    
	    
	    
	    functionvalidarOpcion(){
	        console.log(`validacion ${jugador} `);
	        if(jugador === false   ){
	            alert(`Oye no escribiste ningun valor 😑` )
	        }
	        else{
	            elegirGanador()
	        }
	    }
	    
	    functionelegirGanador(){
	    var cpu =  herramientas[Math.floor(Math.random() * herramientas.length )]
	        if(jugador === "piedra"){
	            if(jugador == 'piedra' && cpu == 'piedra'){
	                alert(` 😧 Hey hay un empate \n intetalo de nuevo`)
	            }
	            elseif(jugador == 'piedra' && cpu == 'papel'){
	                alert(` 😔 perdiste \n intetalo de nuevo`)
	            }
	            else{
	                alert(` 😏 ganaste`)
	            }
	        }
	        elseif(jugador === "papel"){
	            if(jugador == 'papel' && cpu == 'papel'){
	                alert(` 😧 Hey hay un empate \n intetalo de nuevo`)
	            }
	            elseif(jugador == 'papel' && cpu == 'tijera'){
	                alert(` 😔 perdiste \n intetalo de nuevo`)
	            }
	            else{
	                alert(` 😏 ganaste`)
	            }
	        }
	        elseif(jugador === "tijera"){
	            if(jugador == 'tijera' && cpu == 'tijera'){
	                alert(` 😧 Hey hay un empate \n intetalo de nuevo`)
	            }
	            elseif(jugador == 'tijera' && cpu == 'piedra'){
	                alert(` 😔 perdiste \n intetalo de nuevo`)
	            }
	            else {
	                alert(` 😏 ganaste`)
	            }
	        }
	        else{
	            alert(`Debe escribir unas de las las tres opciones 😓` )
	        }
	        console.log(`elegistes ${jugador}`);
	        console.log(`la compu eligio ${cpu}`);
	    }
	    
	    
	    functionjugar(){
	        validarOpcion()
	    
	    }
	    
	    jugar()
	    
	    
	```

* **Angelo Zambrano** (1)

	
	Reto: Piedra, Papel o Tijera:  
	![reto4.PNG](https://static.platzi.com/media/user_upload/reto4-9324be36-1d76-4acd-a53c-14c7be44f31d.jpg)

* **Jeisson Santiago Cortes Ortiz** (1)

	
	var edad = 18;  
	var a = parseInt(prompt("Ingresa tu edad: "));  
	if (a===18) {  
	console.log(“Puedes votar, serà tu 1ra votacion”);  
	}else if(a> 18){  
	console.log(“Puedas votar de nuevo”);  
	}else{  
	console.log(“Aun no puedes votar”);  
	}

* **Juan Pedraza** (1)

	
	Es bastante básico, pero es funcional…
	``` 
	    functionjugar(player1, player2) {
	    
	        if (player1 === "piedra" && player2 === "piedra") {
	            console.log(`Jugador uno juega ${player1} y jugador 2 juega ${player2} hay empate`);
	        } elseif (player1 === "piedra" && player2 === "papel") {
	            console.log(`Jugador uno juega ${player1} y jugador 2 juega ${player2} gana jugador 2`);
	        } elseif (player1 === "piedra" && player2 === "tijera") {
	            console.log(`Jugador uno juega ${player1} y jugador 2 juega ${player2} gana jugador 1`);
	        } elseif (player1 === "papel" && player2 === "piedra") {
	            console.log(`Jugador uno juega ${player1} y jugador 2 juega ${player2} gana jugador 1`);
	        } elseif (player1 === "papel" && player2 === "papel") {
	            console.log(`Jugador uno juega ${player1} y jugador 2 juega ${player2} hay empate`);
	        } elseif (player1 === "papel" && player2 === "tijera") {
	            console.log(`Jugador uno juega ${player1} y jugador 2 juega ${player2} gana jugador 2`);
	        } elseif (player1 === "tijera" && player2 === "piedra") {
	            console.log(`Jugador uno juega ${player1} y jugador 2 juega ${player2} gana jugador 2`);
	        } elseif (player1 === "tijera" && player2 === "papel") {
	            console.log(`Jugador uno juega ${player1} y jugador 2 juega ${player2} gana jugador 1`);
	        } elseif (player1 === "tijera" && player2 === "tijera") {
	            console.log(`Jugador uno juega ${player1} y jugador 2 juega ${player2} hay empate`);
	        }
	    
	    }
	    
	    jugar();```
	    
	```

* **Freddy-Cabrera** (1)

	```
	    <var jugador= ["piedra", "papel", "tijera"];
	    var maquina= jugador[Math.floor(Math.random() *3)];
	    
	    functioncomienzaJuego(jugador){
	        if (jugador===maquina){
	            console.log("Empate");
	        }
	        elseif (jugador !=maquina)
	        {
	            if ((jugador==="piedra")&& (maquina==="tijera")){
	                console.log("Gana jugador");
	            }
	            elseif ((jugador==="tijera") && (maquina==="papel")){
	                console.log("Gana jugador");
	            }
	            elseif ((jugador==="papel") && (maquina==="piedra")){
	                console.log("Gana jugador");
	            }
	        
	            elseif ((jugador==="tijera") && (maquina==="piedra")){
	            console.log("Gana maquina");
	            }
	        
	            elseif ((jugador==="papel") && (maquina==="tijera")){
	                console.log("Gana maquina");
	            }
	            elseif ((jugador==="piedra") && (maquina==="papel")){
	                console.log("Gana maquina");
	            }
	        }
	        }
	     
	    
	    comienzaJuego("piedra");
	    >
	    
	```

* **Migrant** (1)

	```
	    var opciones =["tijera", "papel", "piedra"]
	    var opcionMaquina = opciones[Math.floor(Math.random() * 3)]
	    functionseleccionUsuario (opcionEscogida){ 
	    if((opcionEscogida==="tijera" && opcionMaquina ==="papel")||(opcionEscogida==="papel" && opcionMaquina === "piedra")||(opcionEscogida==="piedra" && opcionMaquina === "tijera")){
	        console.log ("Felicitaciones, Ganaste!!!")
	    } elseif((opcionEscogida==="tijera"&& opcionMaquina === "tijera")||(opcionEscogida==="piedra"&& opcionMaquina === "piedra")||(opcionEscogida==="papel"&& opcionMaquina === "papel")) {
	        console.log ("Quedaste empatadx con la maquina")
	    } else {
	        console.log("Perdiste loser")
	    }
	                                              }
	    seleccionUsuario("piedra")```
	    
	```

* **AxlRubio** (1)
![Image 1.png](https://static.platzi.com/media/user_upload/Image%201-5c1f979d-c78d-4f0a-bb18-5c2cdb613719.jpg)

* **mBaez** (1)

	
	Aquí está mi ejercicio, espero no esté tan confuso
	``` 
	    <!DOCTYPE html>
	    <htmllang="en">
	      <head>
	        <link
	          href="https://fonts.googleapis.com/css2?family=Exo+2:wght@300&display=swap"
	          rel="stylesheet"
	        />
	        <metacharset="UTF-8" />
	        <metaname="viewport"content="width=device-width, initial-scale=1.0" />
	        <title>Piedra, papel o tijera</title>
	        <style>
	          * {
	            font-family: "Exo 2", sans-serif;
	          }
	          .body {
	            display: flex;
	            flex-direction: column;
	            align-items: center;
	            padding: 20px;
	          }
	          .bodyh2 {
	            text-align: center;
	          }
	          .bodyp {
	            font-size: 20px;
	          }
	          button {
	            font-size: 16px;
	          }
	          .respuesta {
	            margin: 25px;
	            text-align: center;
	          }
	          .respuestap {
	            font-size: 15px;
	            margin: 0;
	            padding: 10px;
	          }
	        </style>
	      </head>
	      <body>
	        <sectionclass="body">
	          <h2>Este es el juego de piedra, papel o tijera</h2>
	          <p>Elige con cual jugarás</p>
	          <formid="formulario">
	            <selectid="elementos">
	              <option>Piedra</option>
	              <option>Papel</option>
	              <option>Tijera</option>
	            </select>
	            <buttontype="submit">Vamoh a darle</button>
	          </form>
	          <divclass="respuesta">
	            <pid="respuesta"></p>
	            <pid="low"></p>
	          </div>
	        </section>
	      </body>
	      <script>
	        const form = document.getElementById("formulario");
	        const miEleccion = document.getElementById("elementos");
	        let opciones = ["Piedra", "Papel", "Tijera"];
	        let respuesta = document.getElementById("respuesta");
	        let low = document.getElementById("low");
	    
	        form.addEventListener("submit", event => {
	          event.preventDefault();
	          let eleccionMaquina = parseInt(Math.random() * opciones.length);
	          let selectMachine = opciones[eleccionMaquina];
	    
	          respuesta.innerHTML =
	            "Tú elegiste: " +
	            miEleccion.value +
	            "<br/>La máquina eligió: " +
	            opciones[eleccionMaquina];
	    
	          if (miEleccion.value === selectMachine) {
	            low.innerHTML = "Empataron, sigue jugando!!!!";
	          } elseif (
	            (miEleccion.value === "Piedra" && selectMachine === "Tijera") ||
	            (miEleccion.value === "Papel" && selectMachine === "Piedra") ||
	            (miEleccion.value === "Tijera" && selectMachine === "Papel")
	          ) {
	            low.innerHTML = "Felicidades, ganaste!!!";
	          } else {
	            low.innerHTML = "Lo siento, perdiste!!!! :(";
	          }
	        });
	      </script>
	    </html>
	    
	    
	```

* **samy fabian villanueva gutierrez** (1)

	
	var valor1 = Math.floor(Math.random()*3+1); // maquina  
	var valor2 = Math.floor(Math.random()*3+1); // yo
	
	if(valor1==valor2){  
	empate();  
	}else if(valor1>valor2){  
	desempate1();  
	}else{  
	desempate2();  
	}
	
	function empate(){  
	document.write(“Hay un empate”);  
	}  
	function desempate1(){  
	if(valor12 && valor21){  
	document.write(“Ganaste”);  
	}else if(valor13 && valor21) {  
	document.write(“Perdiste”);  
	}else {  
	document.write(“Ganaste”);  
	}  
	}  
	function desempate2(){  
	if(valor11 && valor22){  
	document.write(“Perdiste”);  
	}else if(valor11 && valor23){  
	document.write(“Ganaste”);  
	}else{  
	document.write(“Perdiste”);  
	}  
	}

* **Danelia Sanchez Sanchez** (1)

	```
	    var opciones = ["piedra", "papel", "tijera"];
	    var index = Math.floor((Math.random() * 3));
	    var jugador1 = prompt("Selecciona piedra 👊, papel ✋ o tijera ✌: ");
	    var jugador2 = opciones[index];
	    
	    
	    function juego(j1, j2) {
	        if(j1 === "piedra" && j2 === "papel") {
	            console.log(`Jugador 2 gana! J1 = ${j1}, J2 = ${j2}`);
	        } else if(j1 ==="piedra" && j2 === "tijera") {
	            console.log(`Jugador 1 gana! J1 = ${j1}, J2 = ${j2}`);
	        } else if(j1 === "papel" && j2 === "piedra") {
	            console.log(`Jugador 1 gana! J1 = ${j1}, J2 = ${j2}`);
	        } else if(j1 === "papel" && j2 === "tijera") {
	            console.log(`Jugador 2 gana! J1 = ${j1}, J2 = ${j2}`);
	        } else if(j1 === "tijera" && j2 === "piedra") {
	            console.log(`Jugador 2 gana! J1 = ${j1}, J2 = ${j2}`);
	        } else if(j1 === "tijera" && j2 === "papel") {
	            console.log(`Jugador 1 gana! J1 = ${j1}, J2 = ${j2}`);
	        } else {
	            console.log(`Empate! J1 = ${j1}, J2 = ${j2}`);
	        }
	    
	    }
	    
	    juego(jugador1, jugador2);
	    
	```

* **ALBERTO JOSE MORALES BOSCAN** (1)

	
	Mi primer intento fue:
	``` 
	    var player1 = "piedra";
	    var player2 = "ppel";
	    
	    function chose(player1, player2){
	    	if(player1 === player2){
	    		alert("Es un empate");
	    	}elseif(player1 === 'piedra' && player2 === 'tijera' || player2 === 'piedra' && player1 === 'tijera'){
	    		alert("Piedra rompe tijera. " + "Tu ganas!!!");
	    	}elseif(player1 === 'papel' && player2 === 'tijera' || player2 === 'papel' && player1 === 'tijera'){
	    		console.log("Tijera rompe papel. " + "Tu ganas!!!");
	    	}else{
	    		alert("Papel envuelve a piedra. " + "Tu ganas!!!");
	    	}
	    }
	    
	    if(player1 && player2 == opcion[0] || player1 && player2 == opcion[1] || player1 && player2 == opcion[2]){
	        // console.log(player1, player2);
	        chose (player1, player2);
	    	}else{
	    			alert("Escoje piedra, papel o tijeras");
	    	}
	    
	```
	
	Luego investigue para que el computador escogiera al asar:
	``` 
	    function select(jugador){
	    	var resul_text = ["EMPATAS", "GANAS", "PIERDES"];
	    
	    	var nombre = ["piedra", "papel", "tijera"];
	    	
	    
	    	var jugada = [
	    					[0, 1, 2],
	    					[2, 0, 1],
	    					[1, 2, 0]
	    	];
	    
	    	var pc = Math.floor((Math.random()*3));
	    
	    	var desc_jugada = [
	    						['Iguales.', 'Papel envuelve a piedra.', 'Piedra rompe tijera.'],
	    						['Papel envuelve a piedra.', 'Iguales.', 'Tijera corta papel.'],
	    						['Piedra rompe tijera.', 'Tijera corta papel.', 'Iguales.']
	    	];
	    
	    	resultado = jugada [pc][jugador];
	    
	    	if(resultado == 0){
	    		console.log("Han quedado " + desc_jugada[pc][jugador]);
	    	}else if(resultado == 1){
	    		console.log("Resultado: " + desc_jugada[pc][jugador] + " " + resul_text[resultado]);
	    	}else if(resultado == 2){
	    		console.log("Resultado: " + desc_jugada[pc][jugador] + " " + resul_text[resultado]);
	    	}else{
	    		alert("ERROR");
	    	}
	    
	    	console.log("Jugador: " + nombre[jugador]);
	    	console.log("Maquina: " + nombre[pc]);
	    	console.log("Resultado: " + resul_text[resultado]);
	    }
	    //Jugador remplace # con un numero del 0 al 2, coloque dentro del () de select().
	    select(#);
	    
	```

* **Santiago_Mateus** (1)

	
	Dure mucho tiempo pero lo hice , también me ayude con algunos comentarios de mis compañeros.  
	Pero aquí esta !!!
	``` 
	    var jugador = prompt(" Elije entre : papel - tijeras - piedra ");
	    
	    var resultado;
	    var papel = "papel";
	    var tijeras = "tijeras";
	    var piedra = "piedra"; 
	    
	    var Computadora=[ papel,tijeras,piedra];
	    var seleccion = Computadora[Math.floor(Math.random() * Computadora.length)]; //Seleccion de variable aleatoria 
	    
	    
	    if (jugador == seleccion)
	        {
	        resultado = "Empate, vuelve a jugar de nuevo";
	        }
	    
	    elseif (jugador === "papel" && seleccion === piedra)     
	        {
	        resultado = "FELICIDADES GANASTE ";
	        }
	    
	    elseif (jugador === "piedra" && seleccion === tijeras)
	    {
	        resultado = "FELICIDADES GANASTE "
	    
	    }
	    elseif (jugador === "tijeras" && seleccion === papel)
	    {
	        resultado = "FELICIDADES GANASTE "
	    }
	    
	    else 
	        {
	        resultado = "Lo siento Perdiste,vuleve a intentarlo de nuevo"
	        }
	    
	    console.log("el jugador eligio: " + jugador);
	    console.log("la Computadora eligio: " + seleccion);
	    console.log(resultado);```
	    
	```

* **gustavoadolfocastaedalondo** (1)

	
	El reto de piedra papel o tijera lo hice así: en html puse un select, a cada opción se le asignó un número.  
	Por otro lado puse un generador de números aleatorios que correspondía a la jugada de la máquina. Los números se compararon en condicionales
	``` 
	    <!DOCTYPE html>
	    
	    <head> 
	    
	    	<title>Piedra, papel o tijera</title>
	    
	    	<style>
	    
	    body
	    {
	    
	    background-color: blue;
	    color:white
	    font family:Helvetica
	    }
	    
	    
	    	</style>
	    
	    </head>
	    	<body>
	    		<h2>Juguemos piedra papel o tijera</h2>
	    		<p>Con cual vas a jugar, seleccionala!</p>
	    		<inputtype ="button"value= "Adarleatomos!">
	    		<formonsubmit="return false">
	    
	    
	    				<selectid="elementos"onchange="getSelectValue();">
	    					<optionvalue="0">...</option>
	    					<optionvalue="1">Piedra</option>
	    					<optionvalue="2">papel</option>
	    					<optionvalue="3">tijera</option>
	    				</select>
	    			</p>
	    		</form> 
	    
	    <script>
	    
	    functiongetSelectValue()
	    
	    {
	    
	    	var selectedValue=document.getElementById("elementos").value;
	    
	    
	    functionrandomNumber(min, max)
	    {
	        returnMath.random() * (max - min) + min;
	    }
	    
	    
	    x=( randomNumber(1, 3) );
	    y=Math.round(x);
	     if (y=1){
	    	 console.log("la máquina escogió piedra");
	     }
	     elseif(y=2){
	    	 console.log("la máquina escogió papel");
	    }
	    	 elseif(y=3){
	    		 console.log("la máquina escogió tijera");
	    	 }
	    
	    
	    //console.log(selectedValue);
	    //console.log(y);
	    
	    
	    if(selectedValue==y){
	       console.log("Empataron");
	    }
	    elseif((selectedValue==1)&&(y=2)){
	    console.log("ganó la máquina");
	    }
	    
	    elseif((selectedValue==1)&(y=3))
	    {
	    	console.log("ganaste");
	    }
	    
	    elseif((selectedValue==2)&(y=1)){
	    console.log("ganaste");
	    }
	    
	    elseif((selectedValue==2)&(y=3)){
	    	console.log("ganó la máquina");
	    
	    }
	    elseif((selectedValue==3)&(y=1)){
	    	console.log("ganó la máquina");
	    }
	    
	    elseif((selectedValue==3)&(y=2))
	    {
	    	console.log("ganaste");
	    }
	    
	    }
	    
	    </script>
	    
	    	</body>
	    
	    
	    </html>
	    
	    
	```

* **Alejandro Giraldo Londoño** (1)

	
	Resuelto! 😃
	``` 
	     var op_elije = prompt ("Elije una opción")
	     var op_machine
	     var n_random = Math.round(Math.random()*2);
	    
	    if(n_random==0){
	        op_machine="Piedra";
	    }elseif(n_random==1){
	        op_machine="Tijera";
	    }elseif(n_random==2){
	        op_machine="Papel";
	    }
	    
	    PPT(op_machine,op_elije);
	    
	    function PPT(op_machine,op_usuario){
	        if  (op_usuario === op_machine ){
	            alert("Empate" + " " + "La máquina sacó " + op_machine);
	        }elseif(op_usuario ==="Tijera" && op_machine ==="Piedra"){
	            alert("Tu has perdido" + " " + "La máquina sacó " + op_machine);
	        }elseif(op_usuario==="Tijera" && op_machine==="Papel"){
	            alert("Tu has ganado" + " " + "La máquina sacó " + op_machine);  
	        }elseif(op_usuario==="Papel" && op_machine==="Tijera"){
	            alert("Tu has perdido" + " " + "La máquina sacó " + op_machine);   
	        }elseif(op_usuario==="Papel" && op_machine==="Piedra"){
	            alert("Tu has ganado" + " " + "La máquina sacó " + op_machine);
	        }elseif(op_usuario==="Piedra" && op_machine==="Tijera"){
	            alert("Tu has ganado" + " " + "La máquina sacó " + op_machine);   
	        }elseif(op_usuario==="Piedra" && op_machine==="Papel"){
	            alert("Tu has perdido" + " " + "La máquina sacó " + op_machine);
	        }else
	        alert("Parece que no sabes jugar, elije Piedra Papel o Tijera");    
	    }
	    
	    
	```

* **Luis Diego Maroto Segura** (1)

	
	Reto realizado !!!
	``` 
	    var opciones = ['Piedra', 'Papel', 'Tijera'];
	    var eleccionTuya = Math.floor(Math.random()*3);
	    
	    functionplay(i){
	        var eleccionMaquina = Math.floor(Math.random()*3);
	        console.log("Tu elección: " + i[eleccionTuya]);
	        console.log("Maquina elije: " + i[eleccionMaquina]);
	        console.log("--------------------------");
	    
	        if (eleccionMaquina === eleccionTuya) {
	            console.log("Resultado: Empate, siga intentando...");
	        } elseif ( ((eleccionTuya === 0) && (eleccionMaquina === 2)) || ((eleccionTuya === 1) && (eleccionMaquina === 0)) || ((eleccionTuya === 3) && (eleccionMaquina === 2)) ){
	            console.log("Resultado: Ganaste, felicidades !!!");
	        } else {
	            console.log("Resultado: Lo siento, perdiste :-(");
	        }
	    }
	    
	    play(opciones);
	    
	```

* **JIMMY STEVE OSMA JEREZ** (1)

	```
	    functionjuegoMaquina(){
	        var aleatorio = Math.round(Math.random()*2);
	        return aleatorio;
	    } 
	    var numeroaleatorio = juegoMaquina();
	    if(numeroaleatorio === 0){
	        maquina="piedra";
	    }
	    elseif(numeroaleatorio === 1){
	        maquina = "papel";
	    }
	    else{
	        maquina = "tijera";
	    }
	    //console.log(numeroaleatorio,maquina)
	    
	    functionjuego(usuario){
	        //console.log("la maquina tira ", maquina)
	    
	        if (maquina === usuario){
	                console.log("Hay empate" + " la maquina tenia", maquina);
	            }elseif(usuario == "piedra"){
	                if(maquina == "papel"){
	                    console.log("Perdiste" + " la maquina tenia", maquina);
	                }else{
	                    console.log("Ganaste"+ " la maquina tenia", maquina);
	                }
	            }
	            elseif(usuario== "papel"){
	                if (maquina == "piedra"){
	                    console.log("Ganaste"+ " la maquina tenia ", maquina);
	                }else{
	                    console.log("Perdiste"+ " la maquina tenia ", maquina)
	                }
	            }
	            elseif(usuario == "tijera"){
	                if (maquina == "papel"){
	                    console.log("Ganaste"+ " la maquina tenia ", maquina);
	                }else{
	                    console.log("perdiste " + " la maquina tenia ", maquina)
	                }
	            }
	    
	    }
	    juego("tijera")
	    
	```

* **ccarpio** (1)

	
	Algo sencillo, pero util para practicar la sintaxis de condicionales en js
	``` 
	    functionjuego(jugada){
	        opciones = ["PIEDRA","PAPEL","TIJERA"]
	        random = Math.ceil(Math.random()*3)
	        var jugadamaquina=opciones[random-1];
	        if((jugada=="TIJERA" & jugadamaquina=="PAPEL") || (jugada=="PAPEL" & jugadamaquina=="PIEDRA") || (jugada=="PIEDRA" & jugadamaquina=="TIJERA")){
	            //Escenarios de victoria para el jugador
	            console.log(`Has ganado este encuentro!, escogiste ${jugada} y tu adversario escogio ${jugadamaquina}`);
	        }
	        elseif((jugada == jugadamaquina)){
	            //Escenarios de empate
	            console.log(`El encuentro resulto en un empate, escogiste ${jugada} y tu adversario escogio ${jugadamaquina}`);
	        }
	        else{
	            //Escenarios de derrota para el jugador
	            console.log(`Has perdido este encuentro, escogiste ${jugada} y tu adversario escogio ${jugadamaquina}`);
	        }
	    }
	    
	    juego("PIEDRA");```
	    
	```

* **AITeam** (1)
![Screenshot_18.png](https://static.platzi.com/media/user_upload/Screenshot_18-6d9400df-2183-4483-b415-56a979004cfa.jpg)

* **luisP** (1)
![Captura de Pantalla 2020-03-28 a la\(s\) 08.37.36.png](https://static.platzi.com/media/user_upload/Captura%20de%20Pantalla%202020-03-28%20a%20la%28s%29%2008.37.36-970353dd-d689-43f8-b0ac-3b77b77d811c.jpg)

* **cesaraguilareduardoromero** (1)
![juego.PNG](https://static.platzi.com/media/user_upload/juego-87ef45fa-f87e-4589-befd-98aa8ca98080.jpg)

* **Héctor Daniel Vega Quiñones (Platzi)** (1)

	
	Este es mi ejercicio 😃
	``` 
	    var options = ["Rock", "Paper", "Scissors"]
	    // var playerChoice, computerChoice
	    
	    functionplayer() {
	        alert("Let's play Rock-Paper-Scissors!")
	        var playerChoice = prompt("Choose an option according to a number:\n[1]Rock\n[2]Paper\n[3]Scissors")
	        return playerChoice - 1
	    }
	    
	    functioncomputer() {
	        var computerChoice = Math.floor(Math.random() * 3)
	        return computerChoice
	    }
	    
	    functionwinningLogic() {
	        var computerAction = options[computer()]
	        var playerAction = options[player()]
	    
	        if (playerAction == computerAction) {
	            console.log(`You picked ${playerAction} vs ${computerAction}`)
	            console.log("IT'S A  D R A W !! !!")
	        } elseif (playerAction == "Rock" && computerAction == "Scissors") {
	            console.log(`You picked ${playerAction} vs ${computerAction}`)
	            console.log("YOU WON !! !!")
	        } elseif (playerAction == "Rock" && computerAction == "Paper") {
	            console.log(`You picked ${playerAction} vs ${computerAction}`)
	            console.log("YOU LOST !! !!")
	        } elseif (playerAction == "Paper" && computerAction == "Scissors") {
	            console.log(`You picked ${playerAction} vs ${computerAction}`)
	            console.log("YOU LOST !! !!")
	        } elseif (playerAction == "Paper" && computerAction == "Rock") {
	            console.log(`You picked ${playerAction} vs ${computerAction}`)
	            console.log("YOU WON !! !!")
	        } elseif (playerAction == "Scissors" && computerAction == "Rock") {
	            console.log(`You picked ${playerAction} vs ${computerAction}`)
	            console.log("YOU LOST !! !!")
	        } elseif (playerAction == "Scissors" && computerAction == "Paper") {
	            console.log(`You picked ${playerAction} vs ${computerAction}`)
	            console.log("YOU WON !! !!")
	        }
	    }
	    
	    winningLogic()
	    
	```

* **Ines Patricia Contreras Espiritu** (1)
![reto.PNG](https://static.platzi.com/media/user_upload/reto-9223e16c-128b-4aec-a49e-abfca125c5b1.jpg)

* **Germán Moreno** (1)
![code.png](https://static.platzi.com/media/user_upload/code-318e3287-4aa4-455a-91ee-bcb3033d7ec9.jpg)
	
	Completamente funcional y sólo con if, else y else if! No sé si pueda reducir aún más el código 😃 Si alguien puede darme algún tip para este caso estaría agradecido.

* **marlonhmp** (1)

	
	Ahora ya esta con la maquina automatica xD
	``` 
	    var piedra = 0
	    var papel = 1
	    var tijera = 2
	    
	    var numeroX = function() {
	        var aleatorio = Math.round(Math.random()*2)
	        return aleatorio
	    }
	    var player2 = numeroX()
	    
	    functionjugar (player1) {
	        if (player1 === player2) {
	            console.log(`Empate, sigue jugando`)
	        } elseif (player1 == piedra && player2 == tijera) {   //piedra
	            console.log(`Tu Ganas, piedra aplasta tijera`)
	        } elseif (player1 == piedra && player2 == papel) {
	            console.log(`Perdiste, papel cubre piedra`)
	        } elseif (player1 == papel && player2 == tijera) {   //papel
	            console.log(`Perdiste, tijera corta papel`)
	        } elseif (player1 == papel && player2 == piedra) {
	            console.log(`Tu Ganas, papel cubre piedra`)
	        } elseif (player1 == tijera && player2 == piedra) {   //tijera
	            console.log(`Perdiste, piedra aplasta tijera`)
	        } elseif (player1 == tijera && player2 == papel) {
	            console.log(`Tu Ganas, tijera corta papel`)
	        }
	    }
	    
	    console.log(`La maquina saco ${player2}`)
	    jugar(piedra)
	    
	    
	```

* **Christian David Sánchez** (1)

	
	En JavaScript tenemos las siguientes declaraciones condicionales:
	
	  * Se usa **if** para especificar un bloque de código que se ejecutará, si una condición especificada es verdadera
	
	  * Use **else** para especificar un bloque de código que se ejecutará, si la misma condición es falsa
	
	  * Use **else if** para especificar una nueva condición para probar, si la primera condición es falsa
	
	  * Se usa **switch** para especificar muchos bloques de código alternativos que se ejecutarán
	
	
	

* **marlonhmp** (1)

	```
	    var piedra = 1
	    var papel = 2
	    var tijera = 3
	    
	    functionjugar (player1, player2) {
	        if (player1 === player2) {
	            console.log(`Empate, sigue jugando`)
	        } elseif (player1 == piedra && player2 == tijera) {   //piedra
	            console.log(`player1 Gana`)
	        } elseif (player1 == piedra && player2 == papel) {
	            console.log(`player2 Gana`)
	        } elseif (player1 == papel && player2 == tijera) {   //papel
	            console.log(`player2 Gana`)
	        } elseif (player1 == papel && player2 == piedra) {
	            console.log(`player1 Gana`)
	        } elseif (player1 == tijera && player2 == piedra) {   //tijera
	            console.log(`player2 Gana`)
	        } elseif (player1 == tijera && player2 == papel) {
	            console.log(`player1 Gana`)
	        }
	    }
	    
	    jugar(piedra, papel)
	    
	```

* **Nahuel Bonader** (1)

	
	Solo se debe llamar a lfunción con el string que se desee: piedra, papel o tijera.
	``` 
	    functionjuego(eleccion) {
	      const eleccionJugador = traduccionEleccionANumero(eleccion);
	      const eleccionComputadora = Math.floor(Math.random() * 3);
	      const eleccionComputadoraPalabra = traduccionNumeroAEleccion(eleccionComputadora);
	      if (eleccionJugador === eleccionComputadora) {
	        console.log(`Has empatado. Tu rival también eligió ${eleccionComputadoraPalabra}.`);
	      } elseif (ganaste(eleccionJugador, eleccionComputadora)) {
	        console.log(`Has ganado. Tu rival eligió ${eleccionComputadoraPalabra}.`);
	      } else {
	        console.log(`Has perdido. Tu rival eligió ${eleccionComputadoraPalabra}.`);
	      }
	    }
	    
	    functiontraduccionEleccionANumero(eleccion) {
	      switch (eleccion) {
	        case'piedra':
	          return0;
	        case'papel':
	          return1;
	        case'tijera':
	          return2;
	      }
	    }
	    
	    functiontraduccionNumeroAEleccion(number) {
	      switch (number) {
	        case0:
	          return'piedra';
	        case1:
	          return'papel';
	        case2:
	          return'tijera';
	      }
	    }
	    
	    functionganaste(jugador, computadora) {
	      if (((jugador === 2) && (computadora === 1))||
	         ((jugador === 1) && (computadora === 0))||
	         ((jugador === 0) && (computadora === 2)))  {
	           returntrue;
	       }
	    }```
	    
	```

* **DosVentanillas** (1)

	```
	    var piedra = 1;
	    var papel  = 2;
	    var tijera = 3;
	    
	    functionjuega(jugador,maquina){
	    	if (jugador === 1 || 3 & maquina === 1 || 3 ){
	            if (jugador < maquina){  console.log("Perdiste");
	            }elseif (jugador > maquina){console.log("ganaste");
	            }else{console.log("empate");
	            }
	    	}elseif (jugador > maquina){console.log("Perdiste");
	    				}elseif (jugador < maquina){ console.log("ganaste");
	    				}else{console.log("empate");
	    }
	    }
	    
	```

* **Jorge Alberto Alvarez Sone** (1)

	```
	    var piedra = 0;
	    var tijera = 1;
	    var papel = 2;
	    
	    functionplay(elección) {
	      let computer = Math.floor(Math.random() * 3);
	      console.log(computer)
	      if (elección === computer) {
	        console.log("Empate");
	      } elseif ((elección === 0) && (computer === 1)) {
	        console.log("Ganaste");
	      } elseif ((elección === 1) && (computer === 2)) {
	        console.log("Ganaste");
	      } elseif ((elección === 2) && (computer === 0)) {
	        console.log("Ganaste");
	      } else {
	        console.log("Perdiste");
	      }
	    };
	    
	    play(papel);```
	    
	```

* **Luigui Mario** (1)

	
	Primero utilice un if simple para validar los datos
	
	Luego un **operador ternario** para ahorrar código, es mas complejo pero se entiende asi:
	
	Tener en cuenta que son **9 posibles casos**
	
	Primero descarto los empates comparando si son iguales las variables en general (sin importar si es A, B o C), primer **condicional del ternario 1** , si es true sera empate, sino se hará toda la operación que viene a continuación:
	
	Segundo, de los 6 posibles casos faltantes, en 3 de ellos gana la maquina y en el resto el jugador.  
	Entonces por esto solo basta detallar en que condiciones gana la maquina, es decir especificar que condiciones se da para que el resultado sea que gane la maquina y esto colocarlo en la parte true del operador **ternario 2**
	
	Tercero, los 3 casos siguientes ya no es necesario especificar por que en estos casos ganaría siempre el jugador, es decir se coloca en el false del **ternario 2,** ya que supuestamente todos los casos anteriores no se cumplieron
	
	![RetoFranz.PNG](https://static.platzi.com/media/user_upload/RetoFranz-bb8205de-0b16-4327-a93f-4ec9c4c61052.jpg)

* **joaomesa** (1)

	
	Propuesta para el reto propuesto por el profesor DIego. ¿Sugerencias?:
	``` 
	    <!DOCTYPE html>
	    <htmllang="en">
	    <head>
	      <metacharset="UTF-8">
	      <metaname="viewport"content="width=device-width, initial-scale=1.0">
	      <metahttp-equiv="X-UA-Compatible"content="ie=edge">
	      <title>Piedra - Papel - Tijera</title>
	    </head>
	    <body>
	      <script>
	        const validations = (player, machine) => {
	          if (player === "Piedra" && machine === "Tijera") {
	            alert("Ganó. La máquina escogio: " + machine);  
	          }elseif (player === "Piedra" && machine === "Papel") {
	            alert("Perdió. La máquina escogio: " + machine);
	          }elseif (player === "Papel" && machine === "Piedra") {
	            alert("Ganó. La máquina escogio: " + machine);
	          }elseif (player === "Papel" && machine === "Tijera") {
	            alert("Perdió. La máquina escogio: " + machine);
	          }elseif (player === "Tijera" && machine === "Papel") {
	            alert("Ganó. La máquina escogio: " + machine);
	          }elseif (player === "Tijera" && machine === "Piedra") {
	            alert("Perdió. La máquina escogio: " + machine);
	          }else {
	            alert("Empate. La máquina escogio: " + machine);
	          }
	        }
	    
	        const machine = () => {
	          let number = Math.floor(Math.random() * 3);
	          let option = ['Piedra', 'Papel', 'Tijera'];
	    
	          return option [number];
	        }
	    
	        const capitalize = (option) => {
	          return option.toLowerCase().replace(/\b\w/g, (m) => {
	            return m.toUpperCase();
	          });
	        }
	    
	        const gameStart = () => {
	          machine();
	          alert("Vamos a jugar Piedra - Papel - Tijera contra la computadora");
	          let player = capitalize(prompt("Ingresa Piedra, Papel o Tijera"));
	          validations(player, machine());
	        }
	    
	        gameStart();
	    
	      </script>
	    </body>
	    </html>
	```

* **Alessandri** (1)

	
	Aquí esta el desafió
	``` 
	    let options = ['Paper','Rock','Scissors']
	    let player = 1;
	    
	    functionwhoIsTheWinner(option1, option2){
	        let winnerResult;
	        if(option1 === option2)
	        {
	            winnerResult = "Draw"
	        }elseif(option1=="Paper"){
	           if(option2 == 'Rock') winnerResult = option1; 
	           elseif (option2 == 'Scissors') winnerResult = option2;
	        }elseif(option1=="Scissors"){
	            if (option2 == 'Rock') winnerResult = option2; 
	            elseif(option2 == 'Paper') winnerResult = option1;
	        }elseif(option1=="Rock"){
	            if (option2 == 'Scissors') winnerResult = option1; 
	            elseif(option2 == 'Paper') winnerResult = option2;
	        }
	        return winnerResult;
	    }
	    
	    functionmakeChoice(num){
	        return options[num]
	    }
	    
	    functiongameStart(){
	     const cpu = makeChoice(Math.floor(Math.random() * 3))
	     player = makeChoice(player)
	     console.log('the winner is '+whoIsTheWinner(player,cpu))
	    }
	    
	    gameStart();```
	    
	```

* **Wandy Rafael Santana Evangelista** (1)

	
	Bueno, hice un **Mini Juego** utilizando **Recursidad** , aqui el codigo:
	``` 
	    let options = ['paper', 'rock', 'scissors'];
	    let cpuOption;
	    let meOption;
	    
	    const cpuChooseOption = () => {
	        let optionChoosed = Math.random();
	    
	        if(optionChoosed <= 0.3){
	            return cpuOption = options[0]
	        } elseif (optionChoosed > 0.3 && optionChoosed <= 0.6){
	            return cpuOption = options[1]
	        } else {
	            return cpuOption = options[2]
	        }
	    }
	    
	    functionstartGame(){
	        cpuChooseOption()
	    
	        if (cpuOption){
	            meOption = prompt('Write Rock, Paper or Scissors:')
	            if(meOption) {
	                if(meOption === cpuOption){
	                    console.log(`THE SAME OPTION: CPU ${cpuOption} ME ${meOption}`)
	                } else {
	                    console.log(`You choosed: ${meOption} and CPU choosed: ${cpuOption}`)
	                    meOption = undefined
	                    cpuOption = undefined
	                    startGame()
	                }
	            }
	        }
	    }```
	    
	```

* **Ignacio** (1)

	
	Queda dar algunos retoques. No he podido subir la imagen de cómo me quedó el frontend pero el código JS es este
	``` 
	    functionplay(index){
	        CPU = buttons[getRandomArbitrary(0,3)]
	        userPlay[0].setAttribute("src", buttons[index].getAttribute("src"))
	        CPUPlay[0].setAttribute("src", CPU.getAttribute("src"))
	        whoWin(buttons[index].nameInGame, CPU.nameInGame)
	    }
	    
	    functiongetRandomArbitrary(min, max) {
	        returnMath.floor(Math.random() * (max - min)) + min;
	    }
	    
	    functionwhoWin(user, cpu){
	        if(user == cpu) paragraphResult[0].appendChild(tieString)
	        elseif(user == "rock" && cpu == "scissors") paragraphResult[0].appendChild(winString)
	        elseif(user == "scissors" && cpu == "rock") paragraphResult[0].appendChild(loseString)
	        elseif(user == "rock" && cpu =="paper") paragraphResult[0].appendChild(loseString)
	        elseif(user == "paper" && cpu == "rock") paragraphResult[0].appendChild(winString)
	        elseif(user == "paper" && cpu == "scissors") paragraphResult[0].appendChild(loseString)
	        elseif(user == "scissors" && cpu == "paper") paragraphResult[0].appendChild(winString)
	    }
	    
	    var buttons = document.getElementsByClassName("button__img")
	    var userPlay = document.getElementsByClassName("main__play")
	    var CPUPlay = document.getElementsByClassName("main__CPU")
	    var paragraphResult = document.getElementsByClassName("main__userPlays--finishTxt")
	    
	    buttons[0].addEventListener("click", function(){play(0)})
	    buttons[1].addEventListener("click", function(){play(1)})
	    buttons[2].addEventListener("click", function(){play(2)})
	    
	    buttons[0].nameInGame = "rock"
	    buttons[1].nameInGame = "paper"
	    buttons[2].nameInGame = "scissors"
	    
	    var loseString = document.createTextNode("Has perdido")
	    var winString = document.createTextNode("¡Tú ganas!")
	    var tieString = document.createTextNode("Han empatado")```
	    
	```

* **edgar limones lozano** (1)

	```
	    functionpartidaMaquinaMano(){
	        var mano = ["Piedra", "Papel", "Tijera"];
	        var i = Math.floor(Math.random() * 3);  //genera random entre 0 y 2 (enteros sin decimal: 0, 1 o 2)
	        return mano[i];
	    }
	    
	    functionjugarPiedraPapelTijeras(mano){
	        var partidaMaquina = partidaMaquinaMano();
	        console.log("Maquina dice: " + partidaMaquina);
	    
	        if(mano == partidaMaquina){
	            console.log("Empate");
	    
	        }elseif(mano == "Piedra" && partidaMaquina == "Tijera"){
	            console.log("Ganas");
	        }elseif(mano == "Papel" && partidaMaquina == "Piedra"){
	            console.log("Ganas");
	        }elseif(mano == "Tijera" && partidaMaquina == "Papel"){
	            console.log("Ganas");
	    
	        }elseif(mano == "Piedra" && partidaMaquina == "Papel"){
	            console.log("Pierdes");
	        }elseif(mano == "Papel" && partidaMaquina == "Tijera"){
	                console.log("Pierdes");    
	        }elseif(mano == "Tijera" && partidaMaquina == "Piedra"){
	            console.log("Pierdes");    
	        }else{
	            console.log("¿A qué juegas?");
	        }
	    }
	    
	```

* **Alejandro Cruzado Rosas** (1)

	```
	    var jugada;
	    var maquina;
	    jugada = prompt("Por favor selcciona una opcion, ¿Qué eliges? \nPiedra \nPapel \nTijera");
	    
	    maquina = jugadaMaquina();
	    alert("La maquina seleccionó: "+maquina);
	    alert(juego(jugada,maquina));
	    
	    function jugadaMaquina() {
	        var tiroJugador = ["Piedra", "Papel", "Tijera"];
	        var random = Math.floor(Math.random() * 3);
	        var seleccionMaquina = parseInt(random);
	        return tiroJugador[seleccionMaquina];
	    }
	    
	    function juego(tiroJugador, tiroMaquina) {
	        //Jugador selecciona piedra 
	        if (tiroJugador == "Piedra" && tiroMaquina == "Papel") {
	            return"ganaste";
	        }elseif (tiroJugador == "Piedra" && tiroMaquina == "Tijera") {
	            return"perdiste";
	        }elseif (tiroJugador == "Piedra" && tiroMaquina == "Piedra") {
	            return"empate";
	        }
	        //Jugador selecciona papel
	        if (tiroJugador == "Papel" && tiroMaquina == "Piedra") {
	            return"perdiste";
	        }elseif (tiroJugador == "Papel" && tiroMaquina == "Tijera") {
	            return"ganaste";
	        }elseif (tiroJugador == "Papel" && tiroMaquina == "Papel") {
	            return"empate";
	        }
	        //Jugador selecciona tijera
	        if (tiroJugador == "Tijera" && tiroMaquina == "Piedra") {
	            return"ganaste";
	        }elseif (tiroJugador == "Tijera" && tiroMaquina == "Papel") {
	            return"perdiste";
	        }elseif (tiroJugador == "Tijera" && tiroMaquina == "Tijera") {
	            return"empate";
	        }
	    }```
	    
	    
	```

* **sergiiolperez** (1)

	```
	    var Player1;
	    
	    functionValor_computadora() {
	        returnMath.random();
	    }
	    
	    var Computadora = Valor_computadora();
	    
	    if(Computadora < 0.3333 ){
	        Computadora = 'Papel'
	    }elseif (Computadora > 0.333 && Computadora < 0.6666) {
	        Computadora = 'Piedra'
	    }else {
	        Computadora = 'Tijeras'
	    }
	    
	    functionplay(Player1, Computadora) {
	      if (Player1 == "Tijeras" && Computadora == 'Papel') {
	        console.log(`Ganaste! con ${Player1}, La maquina Saco ${Computadora}`);
	      } elseif (Player1 == "Papel" && Computadora == 'Piedra') {
	        console.log(`Ganaste! con ${Player1}, La maquina Saco ${Computadora}`);
	      } elseif (Player1 == "Piedra" && Computadora == 'Tijeras') {
	        console.log(`Ganaste! con ${Player1}, La maquina Saco ${Computadora}`);
	      } elseif (Player1 === Computadora){
	          console.log(`Empataron, Ambos sacaron ${Player1}. Prueben denuevo!`)
	      }else {
	        console.log(`Perdiste, Sacaste ${Player1}, La maquina saco ${Computadora}`);
	      }
	    }
	    
	    play('Piedra',Computadora);
	    
	    
	```

* **Derek Samuel Paúl Peña** (1)

	
	Hice que el juego tuviera respuestas random, por si desean checkearlo en el siguiente link los invito a revisar la siguiente página con el fin de que su aprendizaje se incremente 😁: <https://dereksamuel.github.io/Piedra-Papel-o-Tijera/Juego/>

* **bamartinezd** (1)

	```
	    'use strict'
	    
	    functionupdate() {
	        location.reload();
	    }
	    
	    functionplay(elem){
	        var userSelected = elem.id;
	        elem.style.backgroundColor = "#2D8636";
	        var pcSelected = Math.floor(Math.random() * (3 - 0)) + 0;
	        document.getElementById(pcSelected).style.backgroundColor = "#1F3D5C";
	    
	        if (userSelected == pcSelected) {
	            document.getElementById("result").innerHTML = "Elegiste igual que la maquina 🙄";
	        } else {
	            if (userSelected == 0 && pcSelected == 1) {
	                document.getElementById("result").innerHTML = "Perdiste esta vez!!! 😥";
	            } elseif(userSelected == 0 && pcSelected == 2) {
	                document.getElementById("result").innerHTML = "Ganaste!!! 😀";
	            }elseif(userSelected == 1 && pcSelected == 0) {
	                document.getElementById("result").innerHTML = "Ganaste!!! 😀";
	            }elseif(userSelected == 1 && pcSelected == 2) {
	                document.getElementById("result").innerHTML = "Perdiste esta vez!!! 😥";
	            }elseif(userSelected == 2 && pcSelected == 0) {
	                document.getElementById("result").innerHTML = "Perdiste esta vez!!! 😥";
	            }elseif(userSelected == 2 && pcSelected == 1) {
	                document.getElementById("result").innerHTML = "Ganaste!!! 😀";
	            }
	        }
	    
	        document.getElementById(0).disabled = true;
	        document.getElementById(1).disabled = true;
	        document.getElementById(2).disabled = true;
	    }
	    
	```

* **bamartinezd** (1)

	```
	    <!DOCTYPE html>
	    <html>
	        <head>
	            <linkhref="css/main.css"rel="stylesheet" />
	            <scriptsrc="js/main.js"type="text/javascript"></script>
	        </head>
	        <body>
	            <divid="container">
	                <buttonid="letsgo"name="letsgo"onclick="update()"style="background-image: url('img/restart.png'); background-size: cover;"></button>
	            </div>
	            <divid="container-countdown">
	                <h1id="result"></h1>
	            </div>
	            <divid="container-rockpaperscissors">
	                <buttonid="0"name="rock"onclick="play(this)"style="background-image: url('img/rock.png'); background-size: cover;"></button>
	                <buttonid="1"name="paper"onclick="play(this)"style="background-image: url('img/paper.png'); background-size: cover;"></button>
	                <buttonid="2"name="scissors"onclick="play(this)"style="background-image: url('img/scissors.png'); background-size: cover;"></button>
	            </div>
	        </body>
	    </html>
	    
	```

* **Juan Camilo Alvarez Jurado** (1)

	```
	    var machinePlay = "rock"
	    
	    function play(personPlay) {
	        if (machinePlay === personPlay)
	            console.log("TIE!")
	        else
	            if ((machinePlay === "rock" && personPlay === "scissors") ||
	                (machinePlay === "scissors" && personPlay === "paper") ||
	                (machinePlay === "paper" && personPlay === "rock"))
	                console.log("THE MACHINE WINS!")
	            else
	                if ((personPlay === "rock" && machinePlay === "scissors") ||
	                (personPlay === "scissors" && machinePlay === "paper") ||
	                (personPlay === "paper" && machinePlay === "rock"))
	                    console.log("YOU WIN!")
	                else
	                    console.log("INVALID OPTION!!! >:C")
	    }
	    
	    play('rock')
	    play('scissors')
	    play('paper')
	    
	```

* **jorge4rteaga** (1)

	
	//Juego de piedra papel o tijera  
	var jugador = “Piedra”;  
	var maquina = “Papel”
	
	if (jugador==“Piedra”&&maquina==“Piedra”){  
	console.log(“Empataron”);  
	}  
	else if (jugador==“Piedra”&&maquina==“Papel”){  
	console.log(“Gano la maquina”);  
	}  
	else if (jugador==“Piedra”&&maquina==“Tijera”){  
	console.log(“Gano el jugador”);  
	}  
	else if (jugador==“Papel”&&maquina==“Piedra”){  
	console.log(“Gano el jugador”);  
	}  
	else if (jugador==“Papel”&&maquina==“Papel”){  
	console.log(“Emoataron”);  
	}  
	else if (jugador==“Papel”&&maquina==“Tijera”){  
	console.log(“Gano la maquina”);  
	}  
	else if (jugador==“Tijera”&&maquina==“Piedra”){  
	console.log(“Gano la maquina”);  
	}  
	else if (jugador==“Tijera”&&maquina==“Papel”){  
	console.log(“Gano el jugador”);  
	}  
	else if (jugador==“Tijera”&&maquina==“Tijera”){  
	console.log(“Empataron”);  
	}  
	else{  
	console.log(“Introduciste mal tu eleccion”);  
	}

* **Carlos Roberto Villatoro Barrios** (1)

	
	Dejo mi ejercicio:
	``` 
	    <!DOCTYPE html>
	    <htmllang="en">
	    <head>
	        <metacharset="UTF-8">
	        <metaname="viewport"content="width=device-width, initial-scale=1.0">
	        <title>Piedra, papel o tijera</title>
	    </head>
	    <body>
	        <script>
	            var opcion_usuario = Number(prompt("0.Piedra / 1.Papel / 2.tijera" )) //Creamor una variable que va almacenar la opcion del ususario 
	            var opcion_sistema = ["Piedra", "Papel", "Tijera"] //Opciones existentes
	            var opcion_aleatoria = Number(Math.floor(opcion_sistema["length"] * Math.random())) //Genero una opcion aleatoria
	    
	            quien_gano(opcion_aleatoria, opcion_usuario); //Probando el hoisting de la aplicación
	    
	            functionquien_gano(o_aleatoria, o_usuario){
	                if(o_aleatoria === o_usuario){
	                    alert("Empate" + " La maquina escogio: " + o_aleatoria)
	                } elseif (o_usuario === 0 && o_aleatoria === 1){ //piedra vs papel
	                    alert("Perdiste" + " La maquina escogio: " + o_aleatoria)
	                } elseif (o_usuario === 1 && o_aleatoria === 0){ //papel vs piedra
	                    alert("Ganaste" + " La maquina escogio: " + o_aleatoria)
	                } elseif (o_usuario === 0 && o_aleatoria === 2){ //piedra vs tijera
	                    alert("Perdiste" + " La maquina escogio: " + o_aleatoria)
	                } elseif (o_usuario === 2 && o_aleatoria === 0){ //tiejra vs piedra
	                    alert("Ganaste" + " La maquina escogio: " + o_aleatoria)
	                } elseif (o_usuario === 1 && o_aleatoria === 2){ //papel vs tijera
	                    alert("Perdiste" + " La maquina escogio: " + o_aleatoria)
	                } elseif (o_usuario === 2 && o_aleatoria === 1){ //Tijera vs papel
	                    alert("Ganaste" + " La maquina escogio: " + o_aleatoria)
	                }  
	            }
	        </script>
	    </body>
	    </html>
	    
	```

* **Pablo Nicolas Fontaine Gilardi** (1)

	
	Adjunto ejercicio
	``` 
	    var numeroUsuario = Number( prompt("0. Piedra | 1. Papel | 2. Tijera") );
	    var opcionesSistema = ["Piedra", "Papel", "Tijera"];
	    var numeroAleatorio = Number( Math.floor( opcionesSistema["length"] * Math.random() ) );
	    console.log("Numero aleatorio: " + numeroAleatorio);
	    console.log("Numero usuario: " + numeroUsuario);
	    
	    quienGano(numeroAleatorio, numeroUsuario);
	    
	    functionquienGano(n_aleatorio, n_usuario)
	    {
	        if ( n_aleatorio === n_usuario ) /* Empate */
	        {
	            console.log("Empate");
	        }
	        elseif ( n_usuario === 0 && n_aleatorio === 1 ) /* Piedra vs. Papel */
	        {
	            console.log("Perdiste");
	        }
	        elseif ( n_usuario === 1 && n_aleatorio === 0 ) /* Papel vs. Piedra */
	        {
	            console.log("Ganaste");
	        }
	        elseif ( n_usuario === 0 && n_aleatorio === 2 ) /* Piedra vs. Papel */
	        {
	            console.log("Ganaste");
	        }
	        elseif ( n_usuario === 2 && n_aleatorio === 0 ) /* Tijera vs. Piedra */
	        {
	            console.log("Perdiste");
	        }
	    }```
	    
	```

* **Antonio Rafael González Ferrer** (1)

	
	Sin duda pude haber simplificado pero quise describir cada situación:
	``` 
	    functionrandomSelection()
	            {
	                returnMath.floor(Math.random() * 3) + 1
	            }
	    
	            const options = 
	            {
	                1 : "Piedra",
	                2 : "Papel",
	                3 : "Tijeras"
	            }
	    
	            functionplayGame()
	            {
	                console.log('Bienvenid@ al juego Piedra, papelo tijeras! 🎮')
	                console.log(`1. ${options[1]}`)
	                console.log(`2. ${options[2]}`)
	                console.log(`3. ${options[3]}`)
	    
	                const userVar = parseInt(prompt('Ingresa 1, 2 o 3 para decidir:'))
	    
	                if(isNaN(userVar) || userVar < 1 || userVar > 3)
	                {
	                    console.log("🛑 Ingresó un valor erróneo, por favor vuelva a iniciar el juego...")
	                }
	                else
	                {
	                    console.log(`Usted eligió: ${userVar}. ${options[userVar]}`)    
	                    console.log(`Ahora nos toca a nosotros...`)
	                    
	                    const iaVar = randomSelection()
	    
	                    console.log(`Hemos seleccionado: ${iaVar}. ${options[iaVar]}`)
	    
	                    if(userVar === iaVar) // elección del usuario === elección aleatoria
	                    {
	                        console.log(`...`)
	                        console.log('Es un empate!! 😅')
	                    }
	                    elseif(userVar === 1 && iaVar === 2) // usuario piedra, ia papel
	                    {
	                        console.log(`${options[iaVar]} cubre ${options[userVar]}... Usted pierde 😟`)
	                    }
	                    elseif(userVar === 1 && iaVar === 3) // usuario piedra, ia tijeras
	                    {
	                        console.log(`${options[userVar]} rompe ${options[iaVar]}... ¡Ha ganado! 🎆🎆🎈`)
	                    }
	                    elseif(userVar === 2 && iaVar === 1) // usuario papel, ia piedra
	                    {
	                        console.log(`${options[userVar]} cubre ${options[iaVar]}... ¡Ha ganado! 🎆🎆🎈`)
	                    }
	                    elseif(userVar === 2 && iaVar === 3) // usuario papel, ia tijeras
	                    {
	                        console.log(`${options[iaVar]} corta ${options[userVar]}... Usted pierde 😟`)
	                    }
	                    elseif(userVar === 3 && iaVar === 1) // usuario tijeras, ia piedra
	                    {
	                        console.log(`${options[iaVar]} rompe ${options[userVar]}... Usted pierde 😟`)
	                    }
	                    elseif(userVar === 3 && iaVar === 2) // usuario tijeras, ia papel
	                    {
	                        console.log(`${options[iaVar]} corta ${options[userVar]}... ¡Ha ganado! 🎆🎆🎈`)
	                    }
	                }
	            }
	    
	            playGame()
	    
	```

* **Noel Mejia** (1)

	
	Reto:
	``` 
	    functionstart(juego, jugador, maquina) {
	      if (jugador == maquina) {
	        console.log("EMPATE");
	      } elseif (jugador == juego[0]) {
	        if (maquina == juego[1]) {
	          console.log("La maquina gana");
	        } else {
	          console.log("El jugador gana");
	        }
	      } elseif (jugador == juego[1]) {
	        if (maquina == juego[2]) {
	          console.log("La maquina gana");
	        } else {
	          console.log("El jugador gana");
	        }
	      } elseif (jugador == juego[2]) {
	        if (maquina == juego[0]) {
	          console.log("La maquina gana");
	        } else {
	          console.log("El jugador gana");
	        }
	      }
	    }
	    
	    var juego = ["piedra", "papel", "tijeras"];
	    
	    var jugador = juego[Math.floor(Math.random() * 3)];
	    console.log("Jugador: " + jugador);
	    
	    var maquina = juego[Math.floor(Math.random() * 3)];
	    console.log("Maquina: " + maquina);
	    
	    start(juego, jugador, maquina);```
	    
	```

* **Alejandro Ernesto Vargas Vaca** (1)

	```
	    var opciones = ["piedra","papel","tijera"];
	    
	    functionjugar(optJugador){
	        var optPC = opciones[Math.floor(Math.random() * opciones.length)];
	    
	        console.log(`La computadora eligió ${optPC} - El jugador eligió ${optJugador}`);
	    
	        if(optPC === "piedra"){
	            if(optJugador === "piedra"){
	                console.log("Empate");
	            }elseif (optJugador === "papel"){
	                console.log("El jugador gana");
	            } else{
	                console.log("La máquina gana");
	            }
	        }
	    
	        if(optPC === "papel"){
	            if(optJugador === "papel"){
	                console.log("Empate");
	            }elseif (optJugador === "tijera"){
	                console.log("El jugador gana");
	            } else{
	                console.log("La máquina gana");
	            }
	        }
	    
	        if(optPC === "tijera"){
	            if(optJugador === "tijera"){
	                console.log("Empate");
	            }elseif (optJugador === "piedra"){
	                console.log("El jugador gana");
	            } else{
	                console.log("La máquina gana");
	            }
	        }
	    }
	    
	```

* **Joaquín Ignacio Ossandón Gómez** (1)

	
	**Juega diez veces**
	``` 
	    let opt = ["piedra", "papel", "tijeras"], computer, human = "piedra"
	    
	    const azar = () => {
	      random = Math.floor(Math.random() * opt.length)
	      if(random === 0){
	        computer = opt[0]
	      } elseif(random === 1) {
	        computer = opt[1]
	      } else {
	        computer = opt[2]
	      }
	    }
	    
	    const solution = () => {
	      if (human === computer){
	        console.log(`humano: ${human} 
	    computadora: ${computer}`)
	        console.log("empate")
	      } elseif (human === opt[0] && computer === opt[2] || human === opt[1] && computer === opt[0] || human === opt[2] && computer === opt[1]){
	        console.log(`humano: ${human} 
	    computadora: ${computer}`)
	        console.log("ganaste")
	      } else {
	        console.log(`humano: ${human} 
	    computadora: ${computer}`)
	        console.log("perdiste")
	      }
	    }
	    
	    const game = () => {
	      azar()
	      solution()
	    }
	    
	    for (let i = 0; i < 10; i++) {
	      console.log(`%cduelo ${i+1}`, 'color: #0000FF;',)
	      game()  
	    }
	    
	```
	
	Pido recomendaciones, por favor 😄

* **Raundy Ibarras** (1)

	
	Excelente clase, y reto completado!
	``` 
	    var opciones = ["Piedra", "Papel", "Tijera"];
	    
	    functionjuego(user) {
	      opcion = opciones[Math.floor(Math.random() * opciones.length)];
	      console.log(`La pc jugo ${opcion} y tu jugastes ${user}`);
	      if (opcion === user) {
	        console.log(`Es un empate, ambas jugadas, son iguales`);
	      } elseif ((opcion === "Piedra") & (user === "Papel")) {
	        console.log(`Ganaste!`);
	      } elseif ((opcion === "Piedra") & (user === "Tijera")) {
	        console.log(`Gana la pc!`);
	      } elseif ((opcion === "Papel") & (user === "Piedra")) {
	        console.log(`Gana la pc!`);
	      } elseif ((opcion === "Papel") & (user === "Tijera")) {
	        console.log(`Ganaste!`);
	      } elseif ((opcion === "Tijera") & (user === "Papel")) {
	        console.log(`Gana la pc!`);
	      } elseif ((opcion === "Tijera") & (user === "Piedra")) {
	        console.log(`Ganaste!`);
	      } else {
	        if (opcion !== user) {
	          console.log(`Para poder jugar vs la pc, debes escribir los nombres de la siguente forma
	          a: Piedra
	          b: Papel
	          c: Tijera, la primera letra en mayuscula y en singular!`);
	        }
	      }
	    }
	    
	    juego("Papel");
	    
	    
	```

## 0130. Switch

### Descripción:


### Comentarios:

* **Lorena Pinzón** (3)

	
	Este es mi resultado 😄
	``` 
	    var maquina = ["piedra","papel","tijera"];
	    
	    functionjugadas( jugador ){
	        var i = Math.floor(Math.random() * 3);
	        console.log(maquina[i])
	        switch(jugador + "|" + maquina[i]){
	            case maquina[i] + "|" + jugador:
	                console.log("empate");
	                break;
	            case"piedra" + "|" + "papel":case"papel" + "|" + "tijera":case"tijera" + "|" + "piedra":
	                console.log("perdiste contra la máquina "+maquina[i]);
	                break;
	            case"piedra" + "|" + "tijera":case"papel" + "|" + "piedra": case"tijera" + "|" + "papel":
	                console.log("le ganaste a la máquina "+maquina[i]);
	                break;
	            default:
	                console.log("jugada no válida");
	        }
	    }
	    
	```

* **max23esau** (2)

	
	[Reto terminado](https://max23esau.github.io/Game/)  
	[Repositorio](https://github.com/Max23Esau/Game)
	
	HTML
	``` 
	    <!DOCTYPE html>
	    <htmllang="es">
	    <head>
	        <metacharset="UTF-8">
	        <metaname="viewport"content="width=device-width, initial-scale=1.0">
	        <linkrel="stylesheet"href="./css/styles.css">
	        <linkhref="https://fonts.googleapis.com/css2?family=Lato&display=swap"rel="stylesheet">
	        <title>Piedra, Papel o Tijera</title>
	    </head>
	    <body>
	    
	        <mainclass="main">
	            <divclass="title">
	                <h1>Bienvenido<br>Juguemos Piedra, Papel o Tijera<br><br>Elije una opción !</h1>
	            </div>
	            <divclass="options">
	                <buttonid="piedra"><imgsrc="./images/piedra.png"alt=""></button>
	                <buttonid="papel"><imgsrc="./images/papel.png"alt=""></button>
	                <buttonid="tijera"><imgsrc="./images/tijeras.png"alt=""></button>
	            </div>
	            <pid="resultado"></p>
	            <ahref="index.html"class="recharge">Jugar de Nuevo</a>
	        </main>
	        <footerclass="footer">
	            <p>Created by <ahref="https://twitter.com/@Max23Esau"target="_blank">@Max23Esau</a></p>
	        </footer>
	        <scriptsrc="./game.js"></script>
	    </body>
	    </html>
	    
	```
	
	JS
	``` 
	    // piedra = 1
	    // papel = 2
	    // tijera = 3
	    
	    var rock = document.getElementById("piedra");
	    rock.addEventListener("click", piedra);
	    
	    var paper = document.getElementById("papel");
	    paper.addEventListener("click", papel);
	    
	    var scissors = document.getElementById("tijera");
	    scissors.addEventListener("click", tijera);
	    
	    varresult = document.getElementById("resultado");
	    constMachine = Math.floor(Math.random() * (4 - 1) + 1);
	    
	    function piedra(){
	        switch(Machine){
	            case1: result.innerHTML = "La computadora eligio Piedra, Empataron !"; break;
	            case2: result.innerHTML = "La computadora eligio Papel, Perdiste !";   break;
	            case3: result.innerHTML = "La computadora eligio Tijera, Ganaste !";   break;
	            default : result.innerHTML = "ERROR";
	        }
	    }
	    function papel(){
	        switch(Machine){
	            case1: result.innerHTML = "La computadora eligio Piedra, Ganaste !";  break;
	            case2: result.innerHTML = "La computadora eligio Papel, Empataron !"; break;
	            case3: result.innerHTML = "La computadora eligio Tijera, Perdiste !"; break;
	            default : result.innerHTML = "ERROR";
	        }
	    }
	    function tijera(){
	        switch(Machine){
	            case1: result.innerHTML = "La computadora eligio Piedra, Perdiste !";  break;
	            case2: result.innerHTML = "La computadora eligio Papel, Ganaste !";    break;
	            case3: result.innerHTML = "La computadora eligio Tijera, Empataron !"; break;
	            default : result.innerHTML = "ERROR";
	        }
	    }
	    
	```

* **jandresfr** (2)

	
	function ppt(){
	``` 
	    var maquina = "piedra";
	    var jugador = "piedra";
	    
	    switch (maquina){
	        case "piedra":
	            if (maquina === "piedra" && jugador === "piedra") {
	                console.log("Empate. Piedra con piedra no hace nada");
	            } else if (maquina === "piedra" && jugador === "papel"){
	                console.log("Gana jugador porque papel envuelve a piedra");
	            } else if (maquina === "piedra" && jugador === "tijera"){
	                console.log("Gana maquina porque piedra daña a tijera");
	            } else {
	                console.log("Opción no contemplada en los elementos");
	            }
	            break;
	        case "papel":
	            if (maquina === "papel" && jugador === "piedra"){
	                console.log("Gana maquina porque papel envuelve a piedra");
	            } else if (maquina === "papel" && jugador === "papel"){
	                console.log("Empate. Papel con papel no hace nada");
	            } else if (maquina === "papel" && jugador === "tijera"){
	                console.log("Gana jugador porque tijera daña a papel");
	            } else {
	                console.log("Opción no contemplada en los elementos");
	            }
	            break;
	        case "tijera":
	            if (maquina === "tijera" && jugador === "piedra"){
	                console.log("Gana jugador porque piedra daña a tijera");
	            } else if (maquina === "tijera" && jugador === "papel"){
	                console.log("Gana maquina porque tijera daña a papel");
	            } else if (maquina === "tijera" && jugador === "tijera"){
	                console.log("Empate. Tijera con tijera no hace nada");
	            } else {
	                console.log("Opción no contemplada en los elementos");
	            }
	            break;
	        default:
	            console.log("Opción no contemplada en los elementos");
	    }
	    
	```
	
	}
	
	console.log(ppt());

* **Benjamin_Espinosa_N** (2)

	
	Aqui está mi codigo sin usar if
	``` 
	    var jugadorA = prompt("Jugador A, elige piedra, papel o tjera");
	    var aleatorio = Math.floor( Math.random() * 3 ) + 1;
	    
	    switch (aleatorio)
	    {
	        case1:
	            var maquina = "piedra";
	            break;
	        case2:
	            var maquina = "papel";
	            break;
	        case3:
	            var maquina = "tijera";
	            break;
	    }
	    
	    comienzaJuego(jugadorA, maquina)
	    
	    function comienzaJuego( humano, computadora)
	    {
	        var ganador = humano + computadora;
	        console.log(ganador);
	    
	        switch(ganador)
	        {
	            case"piedratijera":
	                alert("Jugador A resulta ganador!");
	                break;
	            case"piedrapapel":
	                alert("La máquina resulta ganador!");
	                break;
	            case"piedrapiedra":
	                alert("Empate!! El ganador se eligira con una pelea a muerte con cuchillos");
	                break;
	    
	            case"papelpiedra":
	                alert("Jugador A resulta ganador!");
	                break;
	            case"papeltijera":
	                alert("La máquina resulta ganador!");
	                break;
	            case"papelpapel":
	                alert("Empate!! El ganador se eligira con una pelea a muerte con cuchillos");
	                break;
	    
	            case"tijerapapel":
	                alert("Jugador A resulta ganador!");
	                break;
	            case"tijerapiedra":
	                alert("La máquina resulta ganador!");
	                break;
	            case"tijeratijera":
	                alert("Empate!! El ganador se eligira con una pelea a muerte con cuchillos");
	                break;
	            default:
	                alert("Jueguen bien!");
	        }
	    }```
	    
	```

* **Laurapregonero** (2)

	
	Switch es una expresión que ejecuta declaraciones asociadas a el (case)

* **mBaez** (2)

	
	Ejercicio completado 😄
	``` 
	    const form = document.getElementById("formulario");
	    const miEleccion = document.getElementById("elementos");
	    let opciones = ["Piedra", "Papel", "Tijera"];
	    let respuesta = document.getElementById("respuesta");
	    let low = document.getElementById("low");
	    
	    form.addEventListener("submit", event => {
	      event.preventDefault();
	      let eleccionMaquina = parseInt(Math.random() * opciones.length);
	      let selectMachine = opciones[eleccionMaquina];
	    
	      console.log("Tú elegiste: " + miEleccion.value);
	      console.log("La máquina eligió: " + opciones[eleccionMaquina]);
	    
	      respuesta.innerHTML =
	        "Tú elegiste: " +
	        miEleccion.value +
	        "<br/>La máquina eligió: " +
	        opciones[eleccionMaquina];
	    
	      switch (true) {
	        case miEleccion.value === selectMachine:
	          low.innerHTML = "Empataron, sigue jugando!!!!";
	          break;
	        case (miEleccion.value === "Piedra" && selectMachine === "Tijera") ||
	          (miEleccion.value === "Papel" && selectMachine === "Piedra") ||
	          (miEleccion.value === "Tijera" && selectMachine === "Papel"):
	          low.innerHTML = "Felicidades, ganaste!!!";
	          break;
	        default:
	          low.innerHTML = "Lo siento, perdiste!!!! :c";
	      }
	    
	      console.log("---------------------------");
	    
	    });
	    
	    
	```

	* **Yiy0** (1)

		
		Amigo tu solucion es muy eficiente, si pudieras decir donde encontrar recursos o si tienes experiencia en esto, no se cuéntanos 😃

* **AITeam** (2)

	```
	    var jugador1;
	    var pc_choose;
	    
	    functionselector_random() {
	        pc_choose = Math.random();
	        return pc_choose;
	    }
	    var option_taken = selector_random();
	    if (option_taken <= 0.333) {
	        option_taken = "ROCK";
	    } elseif (pc_choose > 0.333 && pc_choose <0.666) {
	        option_taken = "PAPER";
	    } else {
	        option_taken = "SCISSORS";
	    }
	    
	    functiongame_process(jugador1, option_taken) {
	        switch (true) {
	            case jugador1 === "ROCK" && option_taken === "PAPER":
	                console.log(`I'm sorry, but you lose.I got ${option_taken} and you ,${jugador1}.`)
	                break;
	            case jugador1 === "PAPER" && option_taken === "SCISSORS":
	                console.log(`I'm sorry, but you lose.I got ${option_taken} and you ,${jugador1}.`)
	                break;
	            case jugador1 === option_taken:
	                console.log(`I'm sorry, nobody wins.I got ${option_taken} and you ,${jugador1}.`)
	                break;
	            default:
	                console.log(`What the fuck? You win!! I got ${option_taken} and you ,${jugador1}.`)
	        }
	    }
	    game_process("ROCK",option_taken);
	    
	```

* **Germán Moreno** (2)
![code1.png](https://static.platzi.com/media/user_upload/code1-8b07fae9-221c-4e29-9732-c2825f255a1e.jpg)

* **Krystian Barragán** (2)

	```
	    var movimientos = ["piedra", "papel", "tijeras"];
	    
	    function juego(eleccion) {
	        random = movimientos[Math.floor(Math.random() * movimientos.length)];
	        console.log("La PC eligió --> " + random);
	        console.log("Tú elegiste --> " + eleccion);
	    
	        switch (eleccion) {
	            case"piedra":
	                switch (random) {
	                    case"piedra":
	                        console.log("Empate");
	                        break;
	    
	                    case"papel":
	                        console.log("Perdiste");
	                        break;
	    
	                    case"tijeras":
	                        console.log("Ganaste");
	                        break;
	                }
	                break;
	    
	            case"papel":
	                switch (random) {
	                    case"piedra":
	                        console.log("Ganaste");
	                        break;
	    
	                    case"papel":
	                        console.log("Empate");
	                        break;
	    
	                    case"tijeras":
	                        console.log("Perdiste");
	                        break;
	                }
	                break;
	    
	            case"tijeras":
	                switch (random) {
	                    case"piedra":
	                        console.log("Perdiste");
	                        break;
	    
	                    case"papel":
	                        console.log("Ganaste");
	                        break;
	    
	                    case"tijeras":
	                        console.log("Empate");
	                        break;
	                }
	                break;
	    
	        }
	    }
	    
	    console.log(juego("tijeras"));```
	    
	```

* **hdgeeks** (2)

	
	Esta sería mi versión con switch 😁
	``` 
	    const choices = ["Rock 👊", "Paper 🖐", "Scissors ✌"];
	    let player = Math.floor(Math.random() * choices.length);
	    let computer = Math.floor(Math.random() * choices.length);
	    console.log('Player: ' + choices[player] + ' | Computer: ' + choices[computer]);
	    
	    functionGame(playerChoice, computerChoice){
	        switch(true) {
	            case playerChoice === 0 && computerChoice === 1 || playerChoice === 1 && computerChoice === 2 || playerChoice === 2 && computerChoice === 0:
	                return"You Lose! 😈";
	            case playerChoice === 0 && computerChoice === 2 || playerChoice === 2 && computerChoice === 1 || playerChoice === 1 && computerChoice === 0: 
	                return"You Win!!! 🎉";
	            default:
	                return"Is a Tie 😬";
	        }
	    }
	    
	    console.log('Result: ' + Game(player, computer));
	    
	```

* **Daniel Felipe Merchan Fuquen** (2)

	```
	    const boton = document.getElementById('boton')
	    const piedra = 0
	    const papel = 1
	    const tijera = 2
	    
	    functiongame () {
	      const seleccionPrograma = Math.floor(Math.random() * 3)
	      let seleccionUsuario = parseInt(prompt(`¿Cuál escojes? /n 0 es piedra, 1 es papel y 2 es tijera`))
	      switch(seleccionUsuario) {
	        casepiedra:
	          if (seleccionPrograma === papel) {
	            alert('Has perdido.')
	          } elseif (seleccionPrograma === tijera) {
	            alert('Has ganado.')
	          } elseif (seleccionUsuario === seleccionPrograma) {
	            alert('Es un empate')
	          }
	          break;
	        casepapel:
	          if (seleccionPrograma === tijera) {
	            alert('Has perdido.')
	          } elseif (seleccionPrograma === piedra) {
	            alert('Has ganado.')
	          } elseif (seleccionUsuario === seleccionPrograma) {
	            alert('Es un empate')
	          }
	          break;
	        casetijera:
	          if (seleccionPrograma === papel) {
	            alert('Has ganado.')
	          } elseif (seleccionPrograma === piedra) {
	            alert('Has perdido.')
	          } elseif (seleccionUsuario === seleccionPrograma) {
	            alert('Es un empate')
	          }
	          break;
	        default:
	          alert("No es una opción válida. intenta con 0 para piedra, 1 para papel y 2 para tijera.")
	          break;
	      }
	    }
	    
	    boton.addEventListener('click', game)```
	    
	```

* **Jonathan Vacas** (1)

	```
	    var jugador1 = "piedra"; //definimos lo que va a usar el jugador
	    var jugador2 = "papel"; //definimos lo que va a usar el jugador
	    
	    switch(true){
	         case jugador1 === "piedra" && jugador2 === "papel":
	              console.log("Gana jugador 2"); //establecemos un caso
	         break; //paramos la comprobacion en caso de que el caso sea correcto
	    
	         case jugador1 === "piedra" && jugador2 === "tijera":
	              console.log("Gana jugador 1"); //establecemos otro caso diferente
	         break;//paramos la comprobacion en caso de que el caso sea correcto
	    
	         case jugador1 === "papel" && jugador2 === "piedra":
	              console.log("Gana jugador 1");//establecemos otro caso diferente
	         break;//paramos la comprobacion en caso de que el caso sea correcto
	         
	         case jugador1 === "papel" && jugador2 === "tijera":
	              console.log("Gana jugador 2");//establecemos otro caso diferente
	         break;//paramos la comprobacion en caso de que el caso sea correcto
	                   
	         case jugador1 === "tijera" && jugador2 === "papel":
	              console.log("Gana jugador 1");//establecemos otro caso diferente
	         break;//paramos la comprobacion en caso de que el caso sea correcto
	                   
	         case jugador1 === "tijera" && jugador2 === "piedra":
	              console.log("Gana jugador 2");//establecemos otro caso diferente
	         break;//paramos la comprobacion en caso de que el caso sea correcto
	                   
	         case jugador1 === jugador2:
	              console.log("Empate");//establecemos otro caso diferente
	         break;//paramos la comprobacion en caso de que el caso sea correcto
	         
	         default:
	              console.log("Los jugadores no tienen un parametro correcto");//en caso de error en los casos anteriores se emite este caso
	    }```
	    
	```

* **Leonardo Bravo Kunkel** (1)

	
	var saca = (piedra = 0, papel = 1, tijera = 2);  
	var saca = (Math.floor(Math.random () * 3));  
	console.log(saca);
	
	var random = (Math.floor(Math.random () * 3));  
	console.log(random);
	
	switch (saca) {  
	case 0:  
	switch (random) {  
	case 0:  
	console.log(“Has escogido piedra y la PC también. EMPATE!!! El empate es peor que la derrota, destruya todo.”);  
	break;  
	case 1:  
	console.log(“Has escogido piedra y la PC papel. PERDISTE!!! Lo bueno de la derrota es que no dura para siempre.”);  
	break;  
	case 2:  
	console.log(“Has escogido piedra y la PC tijera. GANASTE!!! BIenvenido al Olimpo.”);  
	break;  
	}  
	break;  
	case 1:  
	switch (random) {  
	case 0:  
	console.log(“Has escogido papel y la PC también. EMPATE!!! El empate es peor que la derrota, destruya todo.”);  
	break;  
	case 1:  
	console.log(“Has escogido papel y la PC tijera. PERDISTE!!! Lo bueno de la derrota es que no dura para siempre.”);  
	break;  
	case 2:  
	console.log(“Has escogido papel y la PC piedra. GANASTE!!! BIenvenido al Olimpo.”);  
	break;  
	}  
	break;  
	case 2:  
	switch (random) {  
	case 0:  
	console.log(“Has escogido tijera y la PC también. EMPATE!!! El empate es peor que la derrota, destruya todo.”);  
	break;  
	case 1:  
	console.log(“Has escogido tijera y la PC piedra. PERDISTE!!! Lo bueno de la derrota es que no dura para siempre.”);  
	break;  
	case 2:  
	console.log(“Has escogido tijera y la PC papel. GANASTE!!! BIenvenido al Olimpo.”);  
	break;  
	}  
	break;  
	default:  
	}

* **FredySarmiento** (1)

	```
	    var opcJ1=prompt("Seleccione el valor piedra, papel, Tijrea");
	    var opcJ2=prompt("Seleccione el valor piedra, papel, Tijrea");
	    
	    
	    switch(opcJ1,opcJ2){
	    case"piedra","papel":
	        console-log("Gana jugador 2 usaste papel");
	        break;
	    case"papel","tijera":
	        console.log("Gana jugador 2 usaste Tijera");
	        break;
	    case"tijera","piedra":
	        console.log("Gana jugador 2 usaste piedra");
	        break;
	    case"papel","piedra":
	        console-log("Gana jugador 1 usaste papel");
	        break;
	    case"tijera","papel":
	        console.log("Gana jugador 1 usaste Tijera");
	        break;
	    case"piedra","tijera":
	        console.log("Gana jugador 1 usaste piedra");
	        break;
	        default:
	            console.log ("Empate");
	            break; 
	    }
	    
	    
	    
	```

* **jameskristof** (1)

	```
	    function piedraPapeloTijeraSwitch()
	    {
	        var resp_player1 = prompt("Elige piedra, papel o tijera");
	        var resp_player2 = prompt("Elige piedra, papel o tijera");
	        switch(resp_player1, resp_player2)
	        {
	            case"piedra", "papel":
	                console.log("Ganó jugador 2");
	                break;
	            case"piedra", "tijera":
	                console.log("Ganó jugador 1");
	                break;
	            case"papel", "piedra":
	                console.log("Ganó jugador 1");
	                break;
	            case"papel", "tijera":
	                console.log("Ganó jugador 2");
	                break;
	            case"tijera", "piedra":
	                console.log("Ganó jugador 2");
	                break;
	            case"tijera", "papel":
	                console.log("Ganó jugador 1");
	                break;
	            default:
	                console.log("comiencen otra vez");
	        }
	    }```
	    
	```

* **Ariel Alejandro Ureña Morales** (1)

	
	Yo hice un intento de hacerlo interactivo para dos jugadores.  
	Aquí está mi código c:
	``` 
	    var usuario1 = prompt("Jugador 1, escribe tu nombre.");
	    var usuario2 = prompt("Jugador 2, escribe tu nombre.");
	    
	    var eleccion1 = prompt(`${usuario1}, elige  piedra,  papel o  tijera.`);
	    var eleccion2 = prompt(`${usuario2}, elige  piedra,  papel o  tijera.`);
	    
	    switch (eleccion1,eleccion2){
	        case"piedra", "tijera":
	            console.log(`${usuario1} gana.`)
	            break;
	        case"papel", "piedra":
	            console.log(`${usuario1} gana.`)
	            break;
	        case"tijera", "papel":
	            console.log(`${usuario1} gana.`)
	            break;
	        case"tijera", "piedra":
	            console.log(`${usuario2} gana.`)
	            break;
	        case"piedra", "papel":
	            console.log(`${usuario2} gana.`)
	            break;
	        case"papel", "tijera":
	            console.log(`${usuario2} gana.`)
	            break;
	        case eleccion1=eleccion2:
	            console.log("Empate. Refresca la pagina e intenta otra vez.");
	            break;
	        default:
	            console.log(`Esto no estaba contemplado, has logrado escapar de la matrix.`);
	            break;
	    }
	    
	```

* **Daniel Acevedo Rodriguez** (1)

	```
	      var usuario1 = prompt ("jugador 1 escribe piedra, papel o tijera");
	        var usuario2 =  prompt ("jugador 2 escribe piedra, papel o tijera");
	    
	        switch (true){
	        case usuario1 === "piedra" && usuario2 === "papel":
	             console.log("Gana jugador 2");
	             break;
	        case usuario1 === "papel" && usuario2 === "tijera":
	            Console.log("Gana jugador 2");
	             break;
	        case usuario1 === "tijera" && usuario2 === "piedra":
	            Console.log("Gana jugador 2");
	            break;
	        case usuario1 === "tijera" && usuario2 === "papel":
	            Console.log("Gana jugador 1");
	            break;
	        case usuario1 === "papel" && usuario2 === "piedra":
	            Console.log("Gana jugador 1");
	            break;
	        case usuario1 === "piedra" && usuario2 === "tijera":
	            Console.log("Gana jugador 1");
	            break;
	        default:
	            console.log ("elija de nuevo");        
	        }
	    
	```

* **ELITA CAMPOJO GUEVARA** (1)

	
	Mi reto  
	![reto2.png](https://static.platzi.com/media/user_upload/reto2-be142ab4-f1e7-4105-91ec-f9eda8490a2b.jpg)

* **Carlos Luis García** (1)

	```
	    <code>
	    var usuario1 = "Carlos"
	    var usuario2 = "Pedro"
	    
	    var piedra = "piedra"
	    var papel = "papel"
	    var tijera = "tijera"
	    
	    var manoUsuario1 = piedra
	    var manoUsuario2 = papel
	    
	    resultado(manoUsuario1, manoUsuario2)
	    
	    functionresultado(mU1, mU2) {
	      var ganador
	      switch (mU1) {
	        casepiedra:
	          if (mU2 == tijera) {
	            ganador = "El ganador es: " + usuario1
	          } elseif (mU2 == papel) {
	            ganador = "El ganador es: " + usuario2
	          }
	        break
	        casepapel:
	          if (mU2 == piedra) {
	            ganador = "El ganador es: " + usuario1
	          } elseif (mU2 == tijera) {
	            ganador = "El ganador es: " + usuario2
	          }
	        break
	        casetijera:
	          if (mU2 == papel) {
	            ganador = "El ganador es: " + usuario1
	          } elseif (mU2 == piedra) {
	            ganador = "El ganador es: " + usuario2
	          }
	        break
	        default:
	          ganador = "Deben seleccionar entre Piedra, Papel o Tijera"
	      }
	      return ganador
	    }
	    
	```

* **Vicente Andrés Muñoz Moller** (1)

	```
	    var localPlayer = prompt("1 for Rock, 2 for Paper, 3 for Scissors");
	    var localCPU = 3;
	    
	    function theGame() {
	        switch (localPlayer){
	            case"1":
	                console.log("You win");
	                break;
	            case"2":
	                console.log("You lose");
	                break;
	            case"3":
	                console.log("It's a tie");
	                break;
	            default:
	                console.log(localPlayer + " is not a valid value");
	        }
	    }
	    
	    theGame();```
	    
	```

* **Milton Enríquez Torres** (1)

	```
	    <!DOCTYPE html>
	    <html>
	        <head>
	           <title>rock, paper, scissors</title>
	        </head>
	        <body>
	            <script>
	                // Game of rock,paper,scissors
	    
	                var option1="rock";
	                var option2="paper";
	                var option3="scissors";
	                var cpu=Math.floor(Math.random()*3)+1;
	    
	                // entrada de datos
	                var word=prompt("Escribe "+option1+", "+option2+" o "+option3);
	                switch(word){
	                    case option1: case option2: case option3: document.write(getUserFunction(word)); break;
	                     default: document.write("Error, no se encuentra la palabra "+"<strong>"+word+"</strong>"); 
	                }
	          
	                functiongetCPUOption(){
	                  switch(cpu){
	                      case1: return option1;
	                              break;
	                      case2: return option2;
	                              break;
	                      case3: return option3;
	                              break;
	                  }       
	                }
	    
	                functionmessage1(option,cpu){
	                   return"Ganaste, tu opcion: "+"<strong>"+option+"</strong>"+
	                    " , opcion del CPU: "+"<strong>"+getCPUOption()+"</strong>";
	                }
	    
	                functionmessage2(option,cpu){
	                    return"Empate. Tu opcion: "+"<strong>"
	                    +option+"</strong>"+", la del CPU: "+"<strong>"
	                    +cpu+"</strong>";
	                }
	    
	                functiongetUserFunction(option){
	                    switch(option.toLowerCase()){
	                        case getCPUOption(): return message2(option,getCPUOption());
	                                             break;
	                        case option1: switch(getCPUOption()){ case option3: return message1(option,getCPUOption());}
	                                      
	                        case option2: switch(getCPUOption()){case option1: return message1(option,getCPUOption());} 
	                        case option3: switch(getCPUOption()){case option2: return message1(option,getCPUOption());} 
	                        default: return"Perdiste, tu opcion: "+"<strong>"+option+"</strong>"+", opcion del CPU: "+getCPUOption();        
	                    }             
	                }    
	            </script>
	        </body>
	    </html> ```
	    
	```

* **BrandonDAst** (1)

	
	Si dejan dos case juntos, sin un brake que los separe, se entiende que cualquiera de los dos casos ejecutaría las mismas instrucciones que tengan el segundo case.
	``` 
	    var n = 2;
	    switch (n){
	    case2:
	    case4: 
	    console.log('Soy numero par');
	    break;
	    }
	    
	```

* **RemyLebeau** (1)

	
	Aquí mi reto, algo simple y sencillo mientras con el tiempo y el avanzar de los cursos aprendo a dominar JavaScript.
	``` 
	    function Juego(persona, maquina){
	    
	        switch(true){
	        case persona === maquina:
	            console.log("Empate");
	            break;
	        case persona==="piedra" && maquina ==="tijera":
	            console.log("You Win.");
	            break;
	        case persona==="tijera" && maquina ==="piedra":
	            console.log("You Lose.");
	            break;
	        case persona==="papel" && maquina ==="piedra":
	            console.log("You Win.");
	            break;
	        case persona==="piedra" && maquina ==="papel":
	            console.log("You Lose.");
	            break;
	        case persona==="tijera" && maquina ==="papel":
	            console.log("You Win.");
	            break;
	        case persona==="papel" && maquina ==="tijera":
	             console.log("You Lose.");
	            break;
	        default:
	            console.log("No valido")
	            break;
	    
	        }
	    
	    }
	        ```
	    
	```

* **Damian Stone** (1)
![screenshot swtich js.png](https://static.platzi.com/media/user_upload/screenshot%20swtich%20js-6bd94262-6702-42e4-b68a-74bdc54f9575.jpg)

* **eduardovinagre** (1)

	```
	    const PIEDRA = 1;
	    const PAPEL = 2;
	    const TIJERA = 3;
	    
	    functiondeterminarGanador(usuario1, usuario2) {
	      switch (usuario1) {
	        casePIEDRA:
	          switch (usuario2) {
	            casePAPEL: return-1
	            caseTIJERA: return1
	            default: return0;
	          }
	        casePAPEL:
	          switch (usuario2) {
	            casePIEDRA: return1;
	            caseTIJERA: return-1
	            default: return0;
	          }
	        caseTIJERA:
	          switch (usuario2) {
	            casePIEDRA: return-1;
	            casePAPEL: return1
	            default: return0;
	          }
	          break;
	      }
	    }
	    
	    functionmostrarResultado(resultado) {
	        if (resultado === 0) console.log("Es un empate");
	        elseif (resultado > 0) {
	          console.log("Felicidades, Ganaste");
	        } else {
	          console.log("Suerte para la próxima");
	        }
	      }
	      
	      functionjugar(usuario1, usuario2) {
	        let resultado = determinarGanador(usuario1, usuario2);
	        console.log(usuario1, usuario2);
	        mostrarResultado(resultado);
	      }
	      
	      jugar(PIEDRA, PIEDRA);
	      jugar(PIEDRA, PAPEL);
	      jugar(PIEDRA, TIJERA);
	      jugar(PAPEL, PIEDRA);
	      jugar(PAPEL, PAPEL);
	      jugar(PAPEL, TIJERA);
	      jugar(TIJERA, PIEDRA);
	      jugar(TIJERA, PAPEL);
	      jugar(TIJERA,TIJERA);
	    
	```

* **Mackial Houng** (1)

	```
	    const option = {
	       "one" : "rock",
	       "two" : "paper",
	       "tree" : "scissors" 
	    }
	    
	    functionchoicePC() {
	       var pc = Math.floor(Math.random()*3);
	       var chosenOption = "";
	    
	       switch (pc) {
	          case0:
	             chosenOption = option["one"];
	             break;
	          case1: 
	             chosenOption = option["two"];
	             break;
	          case2: 
	             chosenOption = option["tree"];
	             break;
	       }
	       return chosenOption;
	    }
	    
	    functionplay(playing) {
	       var pc = choicePC();
	       console.log(pc);
	    
	       if (playing != pc) {
	          console.log(playing != pc);
	       }
	    
	       switch(playing != pc) {
	          casetrue:
	             if (playing === 'rock' && pc === 'paper') { console.log("you lost"); break; }
	          casetrue:
	             if (playing === 'rock' && pc === 'scissors') { console.log("you win"); break; }
	          casetrue:
	             if (playing === 'paper' && pc === 'rock') { console.log("you win"); break; }
	          casetrue:
	             if (playing === 'paper' && pc === 'scissors') { console.log("you lost"); break; }
	          casetrue:
	             if (playing === 'scissors' && pc === 'rock') { console.log("you lost"); break; }
	          casetrue:
	             if (playing === 'scissors' && pc === 'paper') { console.log("you win"); break; }
	    
	          default: console.log("Draws");
	       }
	    
	    }
	    
	    var yourChoice = prompt("rock | paper | scissors \n\nWrite one: ");
	    
	    play(yourChoice);
	    
	```

* **luisglopez7777** (1)

	```
	    const random = () => {
	      n = Math.floor(Math.random() * 3)
	      switch(n){
	        case0:
	          console.log(`La computadora elige piedra`)
	          n = 'piedra'
	          break
	    
	        case1:
	          console.log(`La computadora elige papel`)
	          n = 'papel'
	          break
	    
	        case2:
	          console.log(`La computadora elige tijera`)
	          n = 'tijera'
	          break
	       
	        default: console.log('Hubo un error')
	      }
	    }
	    
	    const jugar = (eleccion) => {
	      random()
	        switch(eleccion){
	          case'piedra':
	            if(eleccion === n){
	              console.log('Empate')
	            }elseif(n === 'papel'){
	              console.log('Perdiste') 
	            }else {console.log('Ganaste')}
	            break
	      
	          case'papel':
	            if(eleccion === n){
	              console.log('Empate')
	            }elseif(n === 'piedra'){
	              console.log('Ganaste')
	            }else {console.log('Perdiste')}
	            break
	      
	          case'tijera':
	            if(eleccion === n){
	              console.log('Empate')
	            }elseif(n === 'piedra'){
	              console.log('Perdiste')}else{console.log('Ganaste')}
	            break
	          
	          default: console.log('Hubo un error')
	          }
	      }
	    
	    jugar('tijera')```
	    
	```

* **Jorge Alberto Martínez Cerón** (1)

	
	Listo!
	``` 
	    var herramienta = ["piedra","papel","tijeras"];
	    
	    function aleatorio(min,maxi)
	    {
	       var resultado;
	       resultado = Math.floor(Math.random() * (maxi - min + 1) ) +min;
	       return resultado;
	    }
	    
	    function iniciajuego (){
	    
	        var suerte =  aleatorio (0,2);
	        var eleccionpc = herramienta[suerte]; 
	    
	        var j = document.getElementById ("jugadahumano");
	        var  eleccionhumano= herramienta[j.value];
	    
	        switch(true){
	    
	            case eleccionhumano=="papel" && eleccionpc=="papel":
	                console.log("Escogiste:" + eleccionhumano + " y la pc escogió: " + eleccionpc );
	                console.log("empate");
	                break;
	    
	            case eleccionhumano=="piedra" && eleccionpc=="piedra":
	                console.log("Escogiste:" + eleccionhumano + " y la pc escogió: " + eleccionpc );
	                console.log("empate");
	                break;
	    
	            case eleccionhumano=="tijeras" && eleccionpc=="tijeras":
	                    console.log("Escogiste:" + eleccionhumano + " y la pc escogió: " + eleccionpc );
	                    console.log("empate");
	                    break;
	    
	            case eleccionhumano=="papel" && eleccionpc=="piedra":
	                        console.log("Escogiste:" + eleccionhumano + " y la pc escogió: " + eleccionpc );
	                        console.log("ganaste");
	                        break;
	    
	            case eleccionhumano=="papel" && eleccionpc=="tijeras":
	                        console.log("Escogiste:" + eleccionhumano + " y la pc escogió: " + eleccionpc );
	                        console.log("perdiste");
	                        break;
	    
	            case eleccionhumano=="piedra" && eleccionpc=="tijeras":
	                        console.log("Escogiste:" + eleccionhumano + " y la pc escogió: " + eleccionpc );
	                        console.log("ganaste");
	                        break;
	    
	            case eleccionhumano=="piedra" && eleccionpc=="papel":
	                        console.log("Escogiste:" + eleccionhumano + " y la pc escogió: " + eleccionpc );
	                        console.log("perdiste");
	                        break;
	            
	            case eleccionhumano=="tijeras" && eleccionpc=="papel":
	                            console.log("Escogiste:" + eleccionhumano + " y la pc escogió: " + eleccionpc );
	                            console.log("ganaste");
	                            break;
	        
	            case eleccionhumano=="tijeras" && eleccionpc=="piedra":
	                        console.log("Escogiste:" + eleccionhumano + " y la pc escogió: " + eleccionpc );
	                        console.log("perdiste");
	                        break;
	            
	            default:
	                console.log("no escogiste nada/error");
	                console.log("Escogiste:" + eleccionhumano + " y la pc escogió: " + eleccionpc );
	            
	        }
	    }
	    
	    var b = document.getElementById("jugar");
	    b.addEventListener ("click",iniciajuego);
	    
	```

* **Jharell Alejandra Hidalgo Loya** (1)

	
	el switch es como el case en RoR, great.

* **Juan Teixeira** (1)

	```
	    var herramientas = [ 'piedra', 'papel', 'tijera']
	    var jugador = prompt(`Escribe la opción que quieres usar: \n piedra \n  papel \n  tijeras`)
	    
	    
	    functionvalidarOpcion(){
	        console.log(`validacion ${jugador} `);
	        if(jugador === ""   ){
	            alert(`Oye no escribiste ningun valor 😑` )
	        }
	        else{
	            let validacion = true;
	            elegirGanador(validacion)
	        }
	    }
	    
	    functionelegirGanador(v){
	    var cpu =  herramientas[Math.floor(Math.random() * herramientas.length )]
	        switch( v == true){
	            case jugador == 'piedra' && cpu == 'piedra':
	                alert(` 😧 Hey hay un empate \n intetalo de nuevo`)
	                break
	            case jugador == 'piedra' && cpu == 'papel':
	                alert(` 😔 perdiste \n intetalo de nuevo`)
	                break
	            case jugador == 'piedra' && cpu == 'tijera':
	                alert(` 😏 ganaste`)
	                break
	                case jugador == 'papel' && cpu == 'papel':
	                    alert(` 😧 Hey hay un empate \n intetalo de nuevo`)
	                    break
	                case jugador == 'papel' && cpu == 'tijera':
	                    alert(` 😔 perdiste \n intetalo de nuevo`)
	                    break
	                case jugador == 'papel' && cpu == 'piedra':
	                    alert(` 😏 ganaste`)
	                    break
	                    case jugador == 'tijera' && cpu == 'tijera':
	                        alert(` 😧 Hey hay un empate \n intetalo de nuevo`)
	                        break
	                    case jugador == 'tijera' && cpu == 'piedra':
	                        alert(` 😔 perdiste \n intetalo de nuevo`)
	                        break
	                    case jugador == 'tijera' && cpu == 'papel':
	                        alert(` 😏 ganaste`)
	                        break
	                    default:
	                         alert(`Debe escribir unas de las las tres opciones 😓` )
	    
	        }
	        console.log(`elegistes ${jugador}`);
	        console.log(`la compu eligio ${cpu}`);
	    }
	    
	    functionjugar(){
	        validarOpcion()
	    }
	    
	    jugar()```
	    
	```

* **Migrant** (1)

	```
	    var opcUser = Math.floor(Math.random()*3)
	    var opcMchn = Math.floor(Math.random()*3)
	    var jugada = String(opcUser) + String(opcMchn)
	    switch(jugada){
	        case"01": 
	        if(opcUser === 1){ 
	            console.log("Ganaste con papel!!")
	        }else{
	            console.log("Perdiste con piedra!!")
	        }; break;
	        case"10": 
	            if(opcUser === 1){ 
	                console.log("Ganaste con papel!!")
	            }else{
	                console.log("Perdiste con piedra!!")
	            }; break;
	        case"12":
	            if(opcUser === 2){ 
	                    console.log("Ganaste con Tijera!!")
	                }else{
	                    console.log("Perdiste con Papel!!")
	                }; break;
	        case"21":
	                if(opcUser === 2){ 
	                        console.log("Ganaste con Tijera!!")
	                    }else{
	                        console.log("Perdiste con Papel!!")
	                    }; break;
	        case"20": 
	            if(opcUser === 2){ 
	                console.log("Ganaste con piedra!!")
	            }else{
	                console.log("Perdiste con Tijera!!")
	            }; break;
	        case"02": 
	                if(opcUser === 2){ 
	                    console.log("Ganaste con piedra!!")
	                }else{
	                    console.log("Perdiste con Tijera!!")
	                }; break;
	        default: console.log("empataron!!")
	    }
	    
	    
	```

* **Ender José Urdaneta Ocando** (1)

	```
	    var p1= "piedra";
	    var p2= "papel";
	    //console.log(p1+p2);
	    
	    function jugar (a,b){
	        var combinacion=a+b;
	    
	        switch(combinacion){
	            case"piedrapapel":
	                console.log("gana jugador 2");
	                break;
	            case"piedratijera":
	                console.log("gana jugador 1");
	                break;
	            case"papeltijera":
	                console.log("gana jugador 2");
	                break;
	            case"papelpiedra":
	                console.log("gana jugador 1");
	                break;
	            case"tijerapiedra":
	                console.log("gana jugador 2");
	                break;
	            case"tijerapapel":
	                console.log("gana jugador 1");
	                break;
	            default:
	                console.log("empate");
	                break;
	                                                    
	        }
	    }
	    
	    jugar(p1,p2)```
	    
	```

* **Jeisson Santiago Cortes Ortiz** (1)

	
	😃

* **Freddy-Cabrera** (1)

	```
	    var jugador= ["piedra", "papel", "tijera"];
	    var maquina= jugador[Math.floor(Math.random() *3)];
	    
	    functioncomienzaJuego(jugador){
	    
	    switch(jugador){
	    
	        case"piedra":
	           if (jugador===maquina){
	            console.log("Empate");}
	    
	            elseif (jugador !=maquina)
	            {
	            if ((jugador==="piedra")&& (maquina==="tijera")){
	                console.log("Gana jugador");
	            }
	            elseif ((jugador==="piedra") && (maquina==="papel")){
	                console.log("Gana maquina");
	            }}
	            break;
	            
	        
	        case"papel":
	            if (jugador===maquina){
	                console.log("Empate");}
	        
	            elseif ((jugador==="papel") && (maquina==="piedra")){
	                console.log("Gana jugador");
	            }
	            elseif ((jugador==="papel") && (maquina==="tijera")){
	                console.log("Gana maquina");
	            }
	            break;
	    
	        
	        case"tijera":
	            if (jugador===maquina){
	                console.log("Empate");}
	        
	            elseif ((jugador==="tijera") && (maquina==="papel")){
	                console.log("Gana jugador");
	            }
	            
	            elseif ((jugador==="tijera") && (maquina==="piedra")){
	            console.log("Gana maquina");
	            }
	            break;
	        default:
	            console.log("Incorrect");
	        
	        }
	    }
	    
	    comienzaJuego("piedra");
	    
	    
	    
	    
	```

* **Jaime Agustí** (1)

	
	var opcionesDeJuego = [“Piedra”, “Papel”, “Tijera”];  
	var eleccionPlayer;
	
	function play (eleccionPlayer) {  
	var eleccionPC = opcionesDeJuego[Math.floor(Math.random() * opcionesDeJuego.length)];  
	console.log(“Tu elección ha sido: " \+ eleccionPlayer);  
	console.log(“La elección de la máquina ha sido: " \+ eleccionPC);  
	console.log(”---------------R-E-S-U-L-T-A-D-O---------------”);  
	switch (true) {  
	case (eleccionPlayer === “Piedra” && eleccionPC === “Tijera” || eleccionPlayer === “Tijera” && eleccionPC === “Papel” || eleccionPlayer === “Papel” && eleccionPC === “Piedra”):  
	console.log("¡Ganas la partida!");  
	break;  
	case (eleccionPlayer === “Papel” && eleccionPC === “Tijera” || eleccionPlayer === “Piedra” && eleccionPC === “Papel” || eleccionPlayer === “Tijera” && eleccionPC === “Piedra”):  
	console.log(“Pierdes la partida”);  
	break;  
	default:  
	console.log(“Habés empatado la partida”);  
	}  
	}
	
	play ()

* **vrgrajeda** (1)

	```
	    var jugador1;
	    var jugador2;
	    
	    functionobtenerNombresDeJugadores () {
	        jugador1 = prompt("Nombre del primer jugador: ");
	        jugador2 = prompt("Nombre del segundo jugador: ");
	    }
	    
	    functionobtenerJugadaJugador1 () {
	        var opcion = prompt(`${jugador1}, selecciona tu jugada [piedra, papel o tijera]: `);
	        return opcion;
	    }
	    
	    functionobtenerJugadaJugador2 () {
	        var opcion = prompt(`${jugador2}, selecciona tu jugada [piedra, papel o tijera]`);
	        return opcion;
	    }
	    
	    functionobtenerGanador (opcionJugador1, opcionJugador2) {
	        switch (opcionJugador1) {
	            case"piedra":
	                if (opcionJugador2 == "papel") {
	                    alert(`${jugador2} le ganó a ${jugador1}!`);
	                } elseif (opcionJugador2 == "tijera") {
	                    alert(`${jugador1} le ganó a ${jugador2}!`);
	                } else {
	                    alert(`${jugador1} empató con ${jugador2}!`);
	                }
	                break;
	            case"papel":
	                if (opcionJugador2 == "tijera") {
	                    alert(`${jugador2} le ganó a ${jugador1}!`);
	                } elseif (opcionJugador2 == "piedra") {
	                    alert(`${jugador1} le ganó a ${jugador2}!`);
	                } else {
	                    alert(`${jugador1} empató con ${jugador2}!`);
	                }
	                break;
	            case"tijera":
	                if (opcionJugador2 == "piedra") {
	                    alert(`${jugador2} le ganó a ${jugador1}!`);
	                } elseif (opcionJugador2 == "papel") {
	                    alert(`${jugador1} le ganó a ${jugador2}!`);
	                } else {
	                    alert(`${jugador1} empató con ${jugador2}!`);
	                }
	                break;
	        }
	    }
	    
	    obtenerNombresDeJugadores();
	    var opcionJugador1 = obtenerJugadaJugador1();
	    var opcionJugador2 = obtenerJugadaJugador2();
	    obtenerGanador(opcionJugador1, opcionJugador2);
	    
	```

* **Juan Pedraza** (1)

	
	Espero mejorarlo en la medida que aprenda más cosas del curso
	``` 
	    function jugar(player1, player2) {
	    
	        switch (true) {
	            case (player1 === "piedra" && player2 === "piedra"):
	                console.log(`Jugador uno juega ${player1} y jugador 2juega ${player2} hay empate`);
	                break;
	            case (player1 === "piedra" && player2 === "papel"):
	                console.log(`Jugador uno juega ${player1} y jugador 2juega ${player2} gana jugador 2`);
	                break;
	            case (player1 === "piedra" && player2 === "tijera"):
	                console.log(`Jugador uno juega ${player1} y jugador 2juega ${player2} gana jugador 1`);
	                break;
	            case (player1 === "papel" && player2 === "piedra"):
	                console.log(`Jugador uno juega ${player1} y jugador 2juega ${player2} gana jugador 1`);
	                break;
	            case (player1 === "papel" && player2 === "papel"):
	                console.log(`Jugador uno juega ${player1} y jugador 2juega ${player2} hay empate`);
	                break;
	            case (player1 === "papel" && player2 === "tijera"):
	                console.log(`Jugador uno juega ${player1} y jugador 2juega ${player2} gana jugador 2`);
	                break;
	            case (player1 === "tijera" && player2 === "piedra"):
	                console.log(`Jugador uno juega ${player1} y jugador 2juega ${player2} gana jugador 2`);
	                break;
	            case (player1 === "tijera" && player2 === "papel"):
	                console.log(`Jugador uno juega ${player1} y jugador 2juega ${player2} gana jugador 1`);
	                break;
	            case (player1 === "tijera" && player2 === "tijera"):
	                console.log(`Jugador uno juega ${player1} y jugador 2juega ${player2} hay empate`);
	                break;
	    
	            default:
	                console.log("Se ha terminado el juego");
	                break;
	        }
	    
	    
	    }
	    
	    
	    jugar();```
	    
	```

* **gustavoadolfocastaedalondo** (1)

	```
	    <<!DOCTYPEhtml>
	    
	    <head>
	    
	    	<title>Piedra, papel o tijera</title>
	    
	    	<style>
	    
	    body
	    {
	    
	    background-color: blue;
	    color:white
	    font family:Helvetica
	    }
	    
	    
	    	</style>
	    
	    </head>
	    	<body>
	    		<h2>Juguemos piedra papel o tijera</h2>
	    		<p>Con cual vas a jugar, seleccionala!</p>
	    		<inputtype ="button"value= "Adarleatomos!">
	    		<formonsubmit="return false">
	    
	    
	    				<selectid="elementos"onchange="getSelectValue();">
	    					<optionvalue="0">...</option>
	    					<optionvalue="1">Piedra</option>
	    					<optionvalue="2">papel</option>
	    					<optionvalue="3">tijera</option>
	    				</select>
	    			</p>
	    		</form>
	    
	    <script>
	    
	    functiongetSelectValue()
	    
	    {
	    
	    	var selectedValue=document.getElementById("elementos").value;
	    
	    
	    functionrandomNumber(min, max)
	    {
	        returnMath.random() * (max - min) + min;
	    }
	    
	    
	    x=( randomNumber(1, 3) );
	    y=Math.round(x);
	    
	    switch(y) {
	     case (y=1):
	    	console.log("la máquina escogió piedra");
	      break;
	    
	     case(y=2):
	    	 console.log("la máquina escogió papel");
	      break;
	    	 case (y=3):
	    		console.log("la máquina escogió tijera");
	    		break;
	    	 }
	    
	    
	    //console.log(selectedValue);
	    //console.log(y);
	    
	    switch (selectedValue,y)
	    {
	    //case (selectedValue==y):
	      // console.log("Empataron");
	    	 //break;
	    
	    case((selectedValue==1)&&(y=2)):
	    console.log("ganó la máquina");
	    break;
	    
	    case ((selectedValue==1)&(y=3)):
	    console.log("ganaste");
	    break;
	    
	    case ((selectedValue==2)&(y=1)):
	    console.log("ganaste");
	    break;
	    
	    case ((selectedValue==2)&(y=3)):
	    console.log("ganó la máquina");
	    break;
	    
	    case ((selectedValue==3)&(y=1)):
	    console.log("ganó la máquina");
	    break;
	    
	    case ((selectedValue==3)&(y=2)):
	    console.log("ganaste");
	    break;
	    
	    default:
	    console.log("empataron");
	    
	    }
	    }
	    
	    
	    </script>
	    
	    	</body>
	    
	    
	    </html>
	    >
	    
	```

* **Yiy0** (1)

	
	YEP
	``` 
	    alert("You must give 0 (scissor) or 1 (rock) or 2 (paper) to the parameter of the game function")
	    
	    let options = [0, 1, 2];
	    
	        functiongame(input_player){
	            //Machine choice      
	            machine_choice = options[Math.floor(Math.random() * options.length)]
	    
	            switch(true){
	    
	                case input_player === 0 && machine_choice === 2 || 
	                     input_player === 1 && machine_choice === 0 ||
	                     input_player === 2 && machine_choice === 1 
	                     : console.log("Player wins!");
	                    break;
	                
	                case input_player === machine_choice : 
	                    console.log("Draw"); 
	                    break;
	    
	                default: console.log("Player lose ;(");                                    
	            }
	    
	        }
	    
	```

* **Laurapregonero** (1)

	
	Este es mi codigo, me demore un poco pero lo logre  
	var jugador1 =(" Piedra, Papel o Tijera");  
	var Piedra = “Piedra”;  
	var Papel = “Papel”;  
	var Tijera = “Tijera”;
	
	var Jugador2 = [“Piedra”, “Papel”, “Tijera”];  
	var LC = Jugador2[Math.floor(Math.random() * Jugador2.length)];  
	console.log(LC)
	
	switch (jugador1) {  
	case (LC):  
	console.log(“empate 😦 intenta de nuevo”);  
	break;  
	case (“Papel”):  
	switch (LC) {  
	case (“Piedra”):  
	console.log(“ganaste Papel tapa la Piedra”);  
	break;  
	case (“Tijera”):  
	console.log(“perdiste Tijera se rompe con la Piedra”);  
	break;  
	}  
	break;  
	case (“Piedra”):  
	switch (LC) {  
	case (“Papel”):  
	console.log(“perdiste Papel envuelve la Piedra”);  
	break;  
	case (“Tijera”):  
	console.log(“ganaste Piedra rompre la Tijera”);  
	break;
	``` 
	        }
	        break;
	    
	    case ("Tijera"):
	        switch (LC) {
	            case ("Papel"):
	                console.log("ganaste las Tijeras rompen el Papel");
	                break;
	            case ("Piedra"):
	                console.log("perdiste");
	                break;
	    
	        }
	        break;
	    
	        default:
	            console.log("Aitch nooo")
	    
	```
	
	}

* **Stiven Alejandro Manosalvas** (1)

	```
	    var piedra = "Piedra", papel = "Papel", tijeras = "Tijeras"; 
	    
	    var piedraObject = {
	        nombre: piedra,
	        Winner: tijeras,
	        Looser: papel
	    }
	    
	    var papelObject = {
	        nombre: papel,
	        Winner: piedra,
	        Looser: tijeras
	    }
	    
	    var tijerasObject = {
	        nombre: tijeras,
	        Winner: papel,
	        Looser: piedra
	    }
	    
	    
	    function getObjectOption(selection) {7
	        varresult;
	        switch (selection) {
	            case piedra:
	                result = piedraObject;
	                break;
	            case papel:
	                result = papelObject;
	                break;
	            case tijeras:
	                result = tijerasObject;
	                break;
	            default:
	                result = undefined;
	                break;
	        }
	    
	        returnresult;
	    }
	    
	    function chooseWinner(firstPlayer, secondPlayer) {
	        var optionSelected = getObjectOption(firstPlayer);
	    
	        if(optionSelected.Winner === secondPlayer){
	            console.log("Me ganaste AGRRRRR");
	        } 
	        elseif (optionSelected.Looser === secondPlayer){
	            console.log("jaja te gane");
	        } else {
	            console.log ("Empatamos... pero te ganare la proxima");
	        }
	    }
	    
	    chooseWinner(piedra, papel);
	    
	```

* **Danelia Sanchez Sanchez** (1)

	```
	    var opciones = ["piedra", "papel", "tijera"];
	    var index = Math.floor((Math.random() * 3));
	    var jugador1 = prompt("Selecciona piedra 👊, papel ✋ o tijera ✌: ");
	    var jugador2 = opciones[index];
	    
	    
	    function juego(j1, j2) {
	        switch(true) {
	            case (j1 === "piedra" && j2 === "papel"):
	                console.log(`Jugador 2 gana! J1 = ${j1}, J2 = ${j2}`);
	    break;
	            case (j1 ==="piedra" && j2 === "tijera"):
	                console.log(`Jugador 1 gana! J1 = ${j1}, J2 = ${j2}`);
	    break;
	            case (j1 === "papel" && j2 === "piedra"):
	                console.log(`Jugador 1 gana! J1 = ${j1}, J2 = ${j2}`);
	    break;
	            case (j1 === "papel" && j2 === "tijera"):
	                console.log(`Jugador 2 gana! J1 = ${j1}, J2 = ${j2}`);
	    break;
	            case (j1 === "tijera" && j2 === "piedra"):
	                console.log(`Jugador 2 gana! J1 = ${j1}, J2 = ${j2}`);
	    break;
	            case (j1 === "tijera" && j2 === "papel"):
	                console.log(`Jugador 1 gana! J1 = ${j1}, J2 = ${j2}`);
	    break;
	            default:
	                console.log(`Empate! J1 = ${j1}, J2 = ${j2}`);
	    
	        }
	    }   
	    
	    juego(jugador1, jugador2);
	    
	```

* **ALBERTO JOSE MORALES BOSCAN** (1)

	
	Mejorando el juego pasado
	``` 
	    // ****************Archivo HTML*****************
	    
	    <!DOCTYPE html>
	    <html>
	    <head>
	    	<title>Juego Piedra, papel o tijeras</title>
	    	<script src="ejercicioPiedraPapelTijera.js"></script>
	    </head>
	    <body>
	    	<h1>JUGADOR</h1>
	    	<h3>Escoje una juegada</h3>
	    	<br>
	    
	    	<button onclick="select(0)">PIEDRA</button>
	    	<button onclick="select(1)">PAPEL</button>
	    	<button onclick="select(2)">TIJERA</button>
	    </body>
	    </html>
	    
	    
	    
	    // ****************Archivo JS*****************
	    
	    function select(jugador){
	    	var resul_text = ["EMPATAS", "GANAS", "PIERDES"];
	    
	    	var nombre = ["piedra", "papel", "tijera"];
	    	
	    
	    	var jugada = [
	    					[0, 1, 2],
	    					[2, 0, 1],
	    					[1, 2, 0]
	    	];
	    
	    	var pc = Math.floor((Math.random()*3));
	    
	    	var desc_jugada = [
	    						['Iguales.', 'Papel envuelve a piedra.', 'Piedra rompe tijera.'],
	    						['Papel envuelve a piedra.', 'Iguales.', 'Tijera corta papel.'],
	    						['Piedra rompe tijera.', 'Tijera corta papel.', 'Iguales.']
	    	];
	    
	    	resultado = jugada [pc][jugador];
	    
	    	switch (resultado) {
	    		case 0: 
	    			console.log("Han quedado " + desc_jugada[pc][jugador]);
	    			break;
	    		case 1:
	    			console.log("Resultado: " + desc_jugada[pc][jugador] + " " + resul_text[resultado]);
	    			break;
	    		case 2:
	    			console.log("Resultado: " + desc_jugada[pc][jugador] + " " + resul_text[resultado]);
	    			break;
	    		default:
	    			alert("ERROR");
	    	}
	    
	    	console.log("Jugador: " + nombre[jugador]);
	    	console.log("Maquina: " + nombre[pc]);
	    	console.log("jugada: " + jugada[pc][jugador]);
	    	console.log("Resultado: " + resul_text[resultado]);
	    }
	    
	```

* **picojohn** (1)

	
	mi respuesta al reto, probada y comprobada 😃
	``` 
	    var jugador_1 = prompt("Dime piedra papel o tijera"); 
	    var piedra = "piedra";
	    var papel = "papel";
	    var tijera = "tijera";
	    var r;
	    
	    var jugador_2 = ["piedra", "papel", "tijera"];
	    var a = jugador_2[Math.floor(Math.random() * jugador_2.length)];
	    console.log(a)
	    
	    switch (jugador_1) {
	        case (a):
	            console.log("empate intenta de nuevo");
	            break;
	        case ("papel"):
	            switch (a) {
	                case ("piedra"):
	                    console.log("ganaste papel tapa piedra");
	                    break;
	                case ("tijera"):
	                    console.log("perdiste tijera tapa piedra");
	                    break;
	            }
	            break;
	        case ("piedra"):
	            switch (a) {
	                case ("papel"):
	                    console.log("perdiste papel tapa piedra");
	                    break;
	                case ("tijera"):
	                    console.log("ganaste piedra destruye tijera");
	                    break;
	    
	            }
	            break;
	    
	        case ("tijera"):
	            switch (a) {
	                case ("papel"):
	                    console.log("ganaste tijera rompe papel");
	                    break;
	                case ("piedra"):
	                    console.log("perdiste piedra destruye tijera");
	                    break;
	    
	            }
	            break;
	    
	            default:
	                console.log("te equivocaste")
	    
	    }
	    
	```

* **Luis Diego Maroto Segura** (1)

	
	Mi reto resulto.
	``` 
	    var opciones = ['Piedra', 'Papel', 'Tijera'];
	    var eleccionTuya = Math.floor(Math.random() * 3);
	    
	    function play(i) {
	        var eleccionMaquina = Math.floor(Math.random() * 3);
	        console.log("Tu elección: " + i[eleccionTuya]);
	        console.log("Maquina elije: " + i[eleccionMaquina]);
	        console.log("--------------------------");
	    
	        switch (eleccionTuya) {
	            case0:
	                switch (eleccionMaquina) {
	                    case0:
	                        console.log("Resultado: Empate, siga intentando...");
	                        break;
	                    case1:
	                        console.log("Resultado: Lo siento, perdiste :-(");
	                        break;
	                    case2:
	                        console.log("Resultado: Ganaste, felicidades !!!");
	                        break;
	                }
	                break;
	            case1:
	                switch (eleccionMaquina) {
	                    case0:
	                        console.log("Resultado: Ganaste, felicidades !!!");
	                        break;
	                    case1:
	                        console.log("Resultado: Empate, siga intentando...");
	                        break;
	                    case2:
	                        console.log("Resultado: Lo siento, perdiste :-(");
	                        break;
	                }
	                break;
	            case2:
	                switch (eleccionMaquina) {
	                    case0:
	                        console.log("Resultado: Lo siento, perdiste :-(");
	                        break;
	                    case1:
	                        console.log("Resultado: Ganaste, felicidades !!!");
	                        break;
	                    case2:
	                        console.log("Resultado: Empate, siga intentando...");
	                        break;
	                }
	                break;
	        }
	    }
	    
	    play(opciones);
	    
	```

* **Danilo Josué Huacón Aguirre** (1)

	```
	    //Valor random de la maquina
	    var  a ;
	    var n = Math.round(Math.random()*2);
	    if (n==0){
	    a= "piedra";
	    }elseif(n==1){
	    a="papel";
	    }else{
	    a="tijera";
	    }
	    
	    // Valor dado por el user
	    var b = "piedra";
	    juego(a,b)
	    functionjuego (v_machine, v_user){
	    if((v_machine === "piedra" && v_user==="piedra") || (v_machine==="papel" && v_user==="papel") || (v_machine === "tijera" && v_user==="tijera")){
	      returnconsole.log("HA SIDO UN EMPATE");
	    }
	      elseif (v_machine === "piedra" && v_user==="papel"){
	      returnconsole.log("HAS GANADO");
	    }elseif (v_machine === "piedra" && v_user==="tijera"){
	      returnconsole.log("HA GANADO LA MAQUINA");
	    }elseif (v_machine === "papel" && v_user==="piedra"){
	      returnconsole.log("HA GANADO LA MAQUINA");
	    }elseif (v_machine === "papel" && v_user==="tijera"){
	      returnconsole.log("HAS GANADO");
	    }elseif (v_machine === "tijera" && v_user==="papel"){
	      returnconsole.log("HA GANADO LA MAQUINA");
	    }elseif (v_machine === "tijera" && v_user==="piedra"){
	      returnconsole.log("HAS GANADO");
	    }else{
	      returnconsole.log("Valor no valido")
	         }
	    }
	    
	```

* **Alejandro Giraldo Londoño** (1)

	
	Solved 😃
	``` 
	    var op_usuario = prompt ("Elije una opción")
	    var op_machine
	    var n_random = Math.round(Math.random()*2);
	    
	    if(n_random==0){
	       op_machine="Piedra";
	    }elseif(n_random==1){
	       op_machine="Tijera";
	    }elseif(n_random==2){
	       op_machine="Papel";
	    }
	    
	    
	    switch(true){
	        case op_machine === op_usuario:
	            alert ("Empate");
	            break
	        case (op_usuario ==="Tijera" && op_machine ==="Piedra"):
	                alert("Tu has perdido" + " " + "La máquina sacó " + op_machine);
	            break
	        case (op_usuario==="Tijera" && op_machine==="Papel"):
	                alert("Tu has ganado" + " " + "La máquina sacó " + op_machine);
	            break
	        case(op_usuario==="Papel" && op_machine==="Tijera"):
	                alert("Tu has perdido" + " " + "La máquina sacó " + op_machine);
	            break   
	        case (op_usuario==="Papel" && op_machine==="Piedra"):
	                alert("Tu has ganado" + " " + "La máquina sacó " + op_machine);
	            break
	        case (op_usuario==="Piedra" && op_machine==="Tijera"):
	                alert("Tu has ganado" + " " + "La máquina sacó " + op_machine);
	            break
	        case  (op_usuario==="Piedra" && op_machine==="Papel"):
	                alert("Tu has perdido" + " " + "La máquina sacó " + op_machine);
	            break 
	        }```
	    
	```

* **JIMMY STEVE OSMA JEREZ** (1)

	```
	    function juegoMaquina(){
	        var aleatorio = Math.round(Math.random()*2);
	        return aleatorio;
	    } 
	    var numeroaleatorio = juegoMaquina();
	    
	    switch(numeroaleatorio){
	        case0:
	            maquina ="piedra";
	            break;
	        case1:
	            maquina = "papel";
	            break;
	        case2:
	            maquina = "tijera";
	            break;
	    }       
	    
	        //console.log(numeroaleatorio,maquina)
	    
	        function juego(usuario){
	            //console.log("la maquina tira ", maquina)
	    
	            switch(usuario){
	                case"piedra":
	                    switch(maquina){
	                        case"piedra":
	                            console.log("Empate, la maquina tiene", maquina);
	                            break;
	                        case"papel":
	                            console.log("Perdiste, la maquina tiene", maquina);
	                            break;
	                        default:
	                            console.log("Ganaste, la maquina tiene", maquina);
	                    }
	                break;
	                case"papel":
	                    switch(maquina){
	                        case"papel":
	                            console.log("Empate, la maquina tiene", maquina);
	                            break;
	                        case"tijera":
	                            console.log("Perdiste, la maquina tiene", maquina);
	                            break;
	                        default:
	                            console.log("Ganaste, la maquina tiene", maquina);
	                    }
	                break;
	                case"tijera":
	                    switch(maquina){
	                        case"tijera":
	                            console.log("Empate, la maquina tiene", maquina);
	                            break;
	                        case"piedra":
	                            console.log("Perdiste, la maquina tiene", maquina);
	                            break;
	                        default:
	                            console.log("Ganaste, la maquina tiene", maquina);
	                    }
	                    
	    
	            }
	        
	               
	        }
	        juego("piedra")```
	    
	```

* **Ines Patricia Contreras Espiritu** (1)

	
	[](![reto2.PNG](https://static.platzi.com/media/user_upload/reto2-cfc77cff-389a-45b5-b31d-ae7ea9a74fd4.jpg)

* **luisP** (1)

	```
	    var piedra = "piedra";
	    var papel = "papel";
	    var tijera = "tijera";
	    
	    var jugador1;
	    var jugador2;
	     
	    
	    
	    function juego(){
	        jugador1 = prompt("Escoge una opción entre piedra, papel o tijera");
	        jugador2 = prompt("Escoge una opción entre piedra, papel o tijera");
	        switch (jugador1){
	            case"piedra":
	                switch (jugador2) {
	                    case"piedra":
	                        text = "Empate";
	                        break;
	                    case"papel":
	                        text = "Gana jugador 2";
	                        break;
	                    case"tijera":
	                        text = "Gan jugador 1";
	                        break;
	                }
	                break;
	            case"papel":
	                switch (jugador2) {
	                    case"piedra":
	                        text = "Gana jugador 1";
	                        break;
	                    case"papel":
	                        text = "Empate";
	                        break;
	                    case"tijera":
	                        text = "Gana jugador 2";
	                        break;
	                }
	                break;
	            case"tijera":
	                switch (jugador2) {
	                    case"piedra":
	                        text = "Gana jugador 2";
	                        break;
	                    case"papel":
	                        text = "Gana jugador 1";
	                        break;
	                    case"tijera":
	                        text = "Empate";
	                        break;
	                }
	                break;
	                default:
	                    text = "Jueguen bien, recuerden usar solo minúsculas";
	        }
	    
	        document.getElementById("resultado").innerHTML = text; 
	    }
	    
	    
	```

* **ccarpio** (1)

	
	nuevamente, una representacion sencilla del juego de piedra papel o tijera haciendo uso de Switch
	``` 
	    functionjuego(jugada){
	        opciones = ["PIEDRA","PAPEL","TIJERA"]
	        random = Math.ceil(Math.random()*3)
	        var jugadamaquina=opciones[random-1];
	        switch(jugada){
	            case"TIJERA":
	                switch(jugadamaquina){
	                    case"TIJERA":
	                        console.log(`El encuentro resulto en un empate, escogiste ${jugada} y tu adversario escogio ${jugadamaquina}`);
	                        break
	                    case"PAPEL":
	                        console.log(`Has ganado este encuentro!, escogiste ${jugada} y tu adversario escogio ${jugadamaquina}`);
	                        break
	                    case"PIEDRA":
	                        console.log(`Has perdido este encuentro, escogiste ${jugada} y tu adversario escogio ${jugadamaquina}`);
	                        break
	                }
	                break
	            case"PAPEL":
	                switch(jugadamaquina){
	                    case"PAPEL":
	                        console.log(`El encuentro resulto en un empate, escogiste ${jugada} y tu adversario escogio ${jugadamaquina}`);
	                        break
	                    case"PIEDRA":
	                        console.log(`Has ganado este encuentro!, escogiste ${jugada} y tu adversario escogio ${jugadamaquina}`);
	                        break
	                    case"TIJERA":
	                        console.log(`Has perdido este encuentro, escogiste ${jugada} y tu adversario escogio ${jugadamaquina}`);
	                        break
	                }
	                break
	            case"PIEDRA":
	                switch(jugadamaquina){
	                    case"PIEDRA":
	                        console.log(`El encuentro resulto en un empate, escogiste ${jugada} y tu adversario escogio ${jugadamaquina}`);
	                        break
	                    case"TIJERA":
	                        console.log(`Has ganado este encuentro!, escogiste ${jugada} y tu adversario escogio ${jugadamaquina}`);
	                        break
	                    case"PAPEL":
	                        console.log(`Has perdido este encuentro, escogiste ${jugada} y tu adversario escogio ${jugadamaquina}`);
	                        break
	                }
	                break
	        }
	    }
	    juego("PIEDRA");
	    
	```

* **Héctor Daniel Vega Quiñones (Platzi)** (1)

	
	Mi ejercicio usando switch:
	``` 
	    var options = ["Rock", "Paper", "Scissors"]
	    // var playerChoice, computerChoice
	    
	    functionplayer() {
	        alert("Let's play Rock-Paper-Scissors!")
	        var playerChoice = prompt("Choose an option according to a number:\n[1]Rock\n[2]Paper\n[3]Scissors")
	        return playerChoice - 1
	    }
	    
	    functioncomputer() {
	        var computerChoice = Math.floor(Math.random() * 3)
	        return computerChoice
	    }
	    
	    functionwinningLogic() {
	        var computerAction = options[computer()]
	        var playerAction = options[player()]
	    
	        switch (playerAction) {
	            case"Rock":
	                switch (computerAction) {
	                    case"Rock":
	                        console.log(`You picked ${playerAction} vs ${computerAction}`)
	                        console.log("IT'S A  D R A W !! !!")
	                        break
	                    case"Paper":
	                        console.log(`You picked ${playerAction} vs ${computerAction}`)
	                        console.log("YOU LOST !! !!")
	                        break
	                    case"Scissors":
	                        console.log(`You picked ${playerAction} vs ${computerAction}`)
	                        console.log("YOU WON !! !!")
	                        break
	                }
	                break
	        }
	    
	        switch (playerAction) {
	            case"Paper":
	                switch (computerAction) {
	                    case"Rock":
	                        console.log(`You picked ${playerAction} vs ${computerAction}`)
	                        console.log("YOU WON !! !!")
	                        break
	                    case"Paper":
	                        console.log(`You picked ${playerAction} vs ${computerAction}`)
	                        console.log("IT'S A  D R A W !! !!")
	                        break
	                    case"Scissors":
	                        console.log(`You picked ${playerAction} vs ${computerAction}`)
	                        console.log("YOU LOST !! !!")
	                        break
	                }
	        }
	    
	        switch(playerAction) {
	            case"Scissors":
	                switch(computerAction) {
	                    case"Rock":
	                        console.log(`You picked ${playerAction} vs ${computerAction}`)
	                        console.log("YOU LOST !! !!")
	                        break
	                    case"Paper":
	                        console.log(`You picked ${playerAction} vs ${computerAction}`)
	                        console.log("YOU WON !! !!")
	                        break
	                    case"Scissors":
	                        console.log(`You picked ${playerAction} vs ${computerAction}`)
	                        console.log("IT'S A  D R A W !! !!")
	                        break
	                }
	        }
	    }
	    
	    winningLogic()
	    
	```

* **marlonhmp** (1)

	
	Esta bien largo pero creo que se entiende xD, estoy buscando como hacerlo mas corto jaja
	``` 
	    var papel = 0
	    var piedra = 1
	    var tijera = 2
	    
	    var numeroX = function() {
	        var aleatorio = Math.round(Math.random()*2)
	        return aleatorio
	    }
	    var player2 = numeroX()
	    
	    functionjugar (player1) {
	        switch (player1) {
	            casepapel:
	                switch (player2) {
	                    casepapel: 
	                        console.log(`Empate, vuelve a intertarlo`)
	                        break
	                    casepiedra:
	                        console.log(`Tu ganas, papel cubre piedra`)
	                        break
	                    casetijera:
	                        console.log(`Perdiste, tijera corta papel`)
	                        break
	                }
	                break
	            
	            casepiedra:
	                switch (player2) {
	                    casepapel: 
	                        console.log(`Perdiste, papel cubre piedra`)
	                        break
	                    casepiedra:
	                        console.log(`Empate, vuelve a intertarlo`)
	                        break
	                    casetijera:
	                        console.log(`Tu ganas, piedra apalsta tijera`)
	                        break
	                }
	                break
	    
	            casetijera:
	                switch (player2) {
	                    casepapel: 
	                        console.log(`Tu ganas, tijera corta papel`)
	                        break
	                    casepiedra:
	                        console.log(`Perdiste, piedra aplasta tijera`)
	                        break
	                    casetijera:
	                        console.log(`Empate, vuelve a intertarlo`)
	                        break
	                }
	                break
	    
	            default:
	                console.log(`Nel`)
	        }
	    }
	    
	    console.log(`la maquina saco ${player2}`)
	    jugar(piedra)
	    
	    
	```

* **Christian David Sánchez** (1)

	
	La declaración **switch** se utiliza para realizar diferentes acciones en función de diferentes condiciones.

* **DosVentanillas** (1)
![switch.png](https://static.platzi.com/media/user_upload/switch-a764822e-9ca3-4b51-af1e-a00ab7b9e08d.jpg)

* **Jorge Alberto Alvarez Sone** (1)

	```
	    var Jugador = Number(prompt('Elije una opción: Piedra = 0, Papel = 1 y Tijera = 2'));
	    var Computadora = Math.floor(Math.random() * 3);
	    
	    switch (Jugador) {
	      case0:
	    
	        switch (Computadora) {
	          case0:
	            console.log("Empate");
	            break;
	          case1:
	            console.log("Perdiste");
	            break;
	          case2:
	            console.log("Ganaste");
	            break;
	        }
	    
	        case1:
	    
	          switch (Computadora) {
	            case0:
	              console.log("Ganaste");
	              break;
	            case1:
	              console.log("Empate");
	              break;
	            case2:
	              console.log("Perdiste");
	              break;
	          }
	    
	          case2:
	    
	            switch (Computadora) {
	              case0:
	                console.log("Perdiste");
	                break;
	              case1:
	                console.log("Ganaste");
	                break;
	              case2:
	                console.log("Empate");
	                break;
	            }
	            break;
	          default:
	            console.log("Tienes que elegir Piedra (0), Papel (1) o Tijeras (2)");
	    }
	    
	```

* **Luigui Mario** (1)
![RetoFranz.PNG](https://static.platzi.com/media/user_upload/RetoFranz-ed3dde48-728b-4184-ba57-89728220d64e.jpg)

* **Rafael Muñoz Pérez** (1)

	```
	    var userOption = parseInt(prompt("0 -> Piedra\n1 -> Papel\n2 -> Tijeras"));
	    while(userOption < 0 || userOption > 2 || isNaN(userOption)){
	        alert('Valor no permitido, vuelve a ingresarlo');
	        var userOption = parseInt(prompt("0 -> Piedra\n1 -> Papel\n2 -> Tijeras"));
	    }
	    const OPCIONES_MAQUINA = Math.floor(Math.random()*3);
	    const mensaje = `\nOpcion jugador: ${userOption}\nOpcion Maquina: ${OPCIONES_MAQUINA}`;
	    if(OPCIONES_MAQUINA === userOption){
	        alert(`Empate + ${mensaje}`);
	    }elseif(userOption === 0 && OPCIONES_MAQUINA === 1){
	        alert(`Gana la maquina ${mensaje}`);
	    }elseif(userOption === 1 && OPCIONES_MAQUINA === 0){
	        alert(`Gana el jugador ${mensaje}`);
	    }elseif(userOption === 1 && OPCIONES_MAQUINA === 2){
	        alert(`Gana el maquina ${mensaje}`);
	    }elseif(userOption === 2 && OPCIONES_MAQUINA === 1){
	        alert(`Gana el jugador ${mensaje}`);
	    }elseif(userOption === 0 && OPCIONES_MAQUINA === 2){
	        alert(`Gana la jugador ${mensaje}`);
	    }else{
	        alert(`Gana el maquina ${mensaje}`);
	    }```
	    
	    
	```

* **joaomesa** (1)

	
	Reto propuesto por el Profesor. Espero sugerencias:
	``` 
	    <!DOCTYPE html>
	    <htmllang="en">
	    <head>
	      <metacharset="UTF-8">
	      <metaname="viewport"content="width=device-width, initial-scale=1.0">
	      <metahttp-equiv="X-UA-Compatible"content="ie=edge">
	      <title>Run File</title>
	    </head>
	    <body>
	      <script>
	        const validations = (player, machine) => {
	          if (player === machine) {
	            alert(`Empate!!!\nJugador: ${player}\nMaquina: ${machine}`);
	          }else {
	            switch (player, machine) {
	              case"Piedra", "Papel":
	                alert(`Perdió!!!\nJugador: ${player}\nMaquina: ${machine}`);
	                break;
	              case"Piedra", "Tijera":
	                alert(`Ganó!!!\nJugador: ${player}\nMaquina: ${machine}`);
	                break;
	              case"Papel", "Piedra":
	                alert(`Ganó!!!\nJugador: ${player}\nMaquina: ${machine}`);
	                break;
	              case"Papel", "Tijera":
	                alert(`Perdió!!!\nJugador: ${player}\nMaquina: ${machine}`);
	                break;
	              case"Tijera", "Piedra":
	                alert(`Perdió!!!\nJugador: ${player}\nMaquina: ${machine}`);
	                break;
	              case"Tijera", "Papel":
	                alert(`Ganó!!!\nJugador: ${player}\nMaquina: ${machine}`);
	                break;
	            }
	          }
	        }
	    
	        const machine = () => {
	          let number = Math.floor(Math.random() * 3);
	          let option = ['Piedra', 'Papel', 'Tijera'];
	    
	          return option [number];
	        }
	    
	        const capitalize = (option) => {
	          return option.toLowerCase().replace(/\b\w/g, (m) => {
	            return m.toUpperCase();
	          });
	        }
	    
	        const gameStart = () => {
	          machine();
	          alert("Vamos a jugar Piedra - Papel - Tijera contra la computadora");
	          let player = capitalize(prompt("Ingresa Piedra, Papel o Tijera"));
	          validations(player, machine());
	        }
	    
	        gameStart();
	      </script>
	    </body>
	    </html>
	    
	```

* **Julian Ignacio Carelli** (1)

	
	![Captura de pantalla \(50\).png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%2850%29-324e8681-0486-4b46-85b1-0f7a681ead96.jpg)  
	![Captura de pantalla \(51\).png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%2851%29-63d3d33c-6319-4c19-8442-e806edd20dc6.jpg)  
	Reto completadoooo 😃

* **Carlos Roberto Villatoro Barrios** (1)

	```
	    <script>
	            let opciones = ["piedra", "papel", "tijera"];
	            let opcion_usuario = prompt("piedra, papel o tijera");
	            let opcion_sistema = Math.floor(Math.random() *3);
	            let resultados = opcion_usuario + " y la del sistema fue: " + opciones[opcion_sistema];
	    
	            switch (opcion_usuario){
	                case"piedra":
	                    if(opcion_sistema === 0){
	                        alert("Empate, tu opcion fue: " + resultados)
	                    } elseif (opcion_sistema === 1){
	                        alert("Perdiste tu opcion fue: " + resultados)
	                    } elseif (opcion_sistema === 2){
	                        alert("Ganaste!! tu opcion fue: " + resultados)
	                    }
	                break;
	                case"papel":
	                    if(opcion_sistema === 0){
	                        alert("Ganaste!! tu opcion fue: " + resultados)
	                    } elseif (opcion_sistema === 1){
	                        alert("Empate tu opcion fue: " + resultados)
	                    } elseif (opcion_sistema === 2){
	                        alert("Perdiste tu opcion fue: " + resultados)
	                    }
	                break;
	                case"tijera":
	                    if(opcion_sistema === 0){
	                        alert("Perdiste tu opcion fue: " + resultados)
	                    } elseif (opcion_sistema === 1){
	                        alert("Ganaste!! tu opcion fue: " + resultados)
	                    } elseif (opcion_sistema === 2){
	                        alert("Empate tu opcion fue: " + resultados)
	                    }
	                break; 
	                default:
	                    alert("Ingresaste una opcion invalida")
	            }   
	                
	        </script>```
	    
	```

* **Edgar Ramirez** (1)

	
	Si alguien me puede ayudar, funciona pero los resultados no coinciden, cuando debería empatar pierdo , y así en varios casos!
	``` 
	    let user = ["piedra","papel","tijera"]
	            console.log(user)
	            let cpu = Math.floor(Math.random()*3);
	            console.log(cpu);
	    
	            functionposicionEnArrayDeUser(textoABuscar, user) {
	    
	        var posicionEncontrada = -1
	    
	        for(var i = 0; i < user.length; i++) {
	    
	        if(user[i] == textoABuscar ) {
	    
	            posicionEncontrada = i
	            break
	        }
	    }
	    
	    return posicionEncontrada
	    }
	    
	    var texto = prompt("Elija una opcion", "piedra,papel,tijera")
	    var posicion = posicionEnArrayDeUser(texto, user)
	    
	    
	        
	           functionplay (){
	               switch (posicion){
	                   case1: ((posicion === 0) && (cpu === 1)) 
	                   alert("perdistes")
	                   break
	    
	                   case2: ((posicion === 0) && (cpu === 2))
	                   alert("ganaste")
	                   break
	    
	                   case3: ((posicion === 1) && (cpu === 0)) 
	                   alert("ganaste")
	                   break
	    
	                   case4: ((posicion === 1) && (cpu === 2)) 
	                   alert("perdistes")
	                   break
	    
	                   case5: ((posicion === 2) && (cpu === 0)) 
	                   alert("perdistes")
	                   break
	    
	                   case6: ((posicion === 2) && (cpu === 1)) 
	                   alert("ganaste")
	                   break
	                   case7: (posicion === cpu)
	                   alert("empate")
	                   default: 
	                   alert(" empate")
	    
	               }
	               
	           }console.log(posicion)
	            play()
	    
	```

* **Wandy Rafael Santana Evangelista** (1)

	
	Aqui esta mi **Mini Juego de consola** con **Switch:**
	``` 
	    let options = ['paper', 'rock', 'scissors'];
	    let cpuOption, meOption;
	    
	    const cpuChooseOption = () => {
	        let optionChoosed = Math.floor(Math.random() * 3);
	    
	        if(optionChoosed === 0){
	            return cpuOption = options[0]
	        } elseif (optionChoosed === 1){
	            return cpuOption = options[1]
	        } else {
	            return cpuOption = options[2]
	        }
	    }
	    
	    const theSame = () => console.log(`THE SAME OPTION: CPU ${cpuOption} ME ${meOption}`)
	    
	    const NotSame = () => {
	        console.log(`You choosed: ${meOption} and CPU choosed: ${cpuOption}`)
	        cpuOption = undefined
	        meOption = undefined
	        startGame()
	    }
	    
	    const validateOption = () => cpuOption === meOption ? theSame() : NotSame()
	    
	    functionstartGame(){
	        cpuChooseOption()
	        meOption = prompt('Write Rock, Paper or Scissors:')
	        switch (meOption) {
	            case options[0]:
	                return validateOption()
	                break;
	            case options[1]:
	                return validateOption()
	                break;
	            case options[2]:
	                return validateOption()
	                break;
	            default: 
	                console.log('Some is wrong, try again');
	                startGame();
	        }
	    }```
	    
	```

* **edgar limones lozano** (1)

	```
	    functionpartidaMaquinaMano(){
	        var mano = ["Piedra", "Papel", "Tijera"];
	        var i = Math.floor(Math.random() * 3);  //genera random entre 0 y 2 (enteros sin decimal: 0, 1 o 2)
	        return mano[i];
	    }
	    
	    functionjugarPiedraPapelTijeras(mano){
	        var partidaMaquina = partidaMaquinaMano();
	        console.log("Maquina dice: " + partidaMaquina);
	    
	        switch(mano){
	            case"Piedra":
	                if(partidaMaquina == "Piedra"){
	                    console.log("Empate");
	                }elseif(partidaMaquina == "Tijera"){
	                    console.log("Ganaste a la maquina");
	                }else{
	                    console.log("Perdiste contra la máquina");
	                }
	                break;
	            case"Papel":
	                if(partidaMaquina == "Papel"){
	                    console.log("Empate");
	                }elseif(partidaMaquina == "Piedra"){
	                    console.log("Ganaste a la maquina");
	                }else{
	                    console.log("Perdiste contra la máquina");
	                }
	                break;
	            case"Tijera":
	                if(partidaMaquina == "Tijera"){
	                    console.log("Empate");
	                }elseif(partidaMaquina == "Papel"){
	                    console.log("Ganaste a la maquina");
	                }else{
	                    console.log("Perdiste contra la máquina");
	                }
	                break;
	            default:
	                console.log("¿A qué juegas?");
	        }
	    }
	    
	    
	```

* **sergiiolperez** (1)

	```
	    var Player1;
	    
	    functionValor_computadora() {
	        returnMath.random();
	    }
	    
	    var Computadora = Valor_computadora();
	    
	    switch (true) {
	        case Computadora < 0.3333:
	            Computadora = 'Papel'
	            break;
	        case Computadora > 0.333 && Computadora < 0.6666:
	            Computadora = 'Piedra'
	            break;
	        default:
	            Computadora = 'Tijeras';
	            break;
	    }
	    
	    functionplay(Player1, Computadora) {
	        switch (true) {
	            case Player1 == "Tijeras" && Computadora == 'Papel':
	                console.log(`Ganaste! con ${Player1}, La maquina Saco ${Computadora}`);
	                break;
	            case Player1 == "Papel" && Computadora == 'Piedra' :
	                console.log(`Ganaste! con ${Player1}, La maquina Saco ${Computadora}`);
	                break;
	            case Player1 == "Piedra" && Computadora == 'Tijeras' :
	                console.log(`Ganaste! con ${Player1}, La maquina Saco ${Computadora}`);
	                break;
	            case Player1 === Computadora :
	                console.log(`Empataron, Ambos sacaron ${Player1}. Prueben denuevo!`)
	                break;
	            default:
	                console.log(`Perdiste, Sacaste ${Player1}, La maquina saco ${Computadora}`);
	                break;
	        }
	    }
	    
	    play('Piedra',Computadora);```
	    
	```

* **Derek Samuel Paúl Peña** (1)

	
	SOLUCIÓN DEL RETO:
	``` 
	    <code>
	    let piedra = document.getElementById('piedra');
	    let papel = document.getElementById('papel');
	    let tijera = document.getElementById('tijera');
	    var result = Math.random();
	    let resultados = document.getElementById('resultados');
	    
	    functionclickPiedra() {
	        piedra.style = 'background-color: tomato;';
	    
	        switch(true) {
	            case result < 0.3:
	                resultados.textContent = 'Ganaste 😁';
	                piedra.style = 'background-color: greenYellow;';
	            break
	            default:
	                resultados.textContent = 'Perdiste 😵';
	            break
	        }
	    }
	    
	    functionclickPapel() {
	        papel.style = 'background-color: tomato;';
	    
	        switch(true) {
	            case result > 0.6:
	                resultados.textContent = 'Ganaste 😁';
	                papel.style = 'background-color: greenYellow;';
	            break
	            default:
	                resultados.textContent = 'Perdiste 😵';
	            break
	        }
	    }
	    
	    functionclickTijera() {
	        tijera.style = 'background-color: tomato;';
	    
	        switch(true) {
	            case result > 0.3 && result < 0.6:
	                resultados.textContent = 'Ganaste 😁';
	                tijera.style = 'background-color: greenYellow;';
	            break
	            default:
	                resultados.textContent = 'Perdiste 😵';
	            break
	        }
	    }
	    
	    
	```

* **bamartinezd** (1)
![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-113c4312-2419-4330-8c6c-f5c0a44add5f.jpg)

* **DevNaftan** (1)

	
	**Reto cumplido**
	``` 
	    /* El juego tiene 3 rondas y acaba cuando uno de los participantes gana 3 veces 
	    Opción 1: Piedra
	    Opción 2: Papel
	    Opción 3: Tijera
	    */
	    
	    // Declaración de variables
	    var round_count = 0;
	    var yo_count = 0;
	    var maquina_count = 0;
	    var maquina;
	    var yo_string;
	    var maquina_string;
	    
	    // Generación aleatoria de una opción para la máquina
	    var maquinaOpcion = function() {
	      return Math.round(Math.random()*(3-1)+parseInt(1));
	    }
	    
	    // Algoritmo del juego
	    function juego(yo) {
	      // Escoge una opción para la máquina
	      maquina = maquinaOpcion();
	    
	      //Asigna un string a la opción escogida por el usuario
	      if (yo === 1) {
	        yo_string = "Piedra"
	      } elseif (yo === 2) {
	        yo_string = "Papel"
	      }elseif (yo === 3) {
	        yo_string = "Tijera"
	      }
	    
	      //Asigna un string a la opción escogida por la maquina
	      if (maquina === 1) {
	        maquina_string = "Piedra"
	      } elseif (maquina === 2) {
	        maquina_string = "Papel"
	      }elseif (maquina === 3) {
	        maquina_string = "Tijera"
	      }
	    
	      //Realiza la comprobación
	      switch (yo) {
	        case1:
	          if (maquina === 1) {
	            round_count++;
	            console.log("Ronda: " + round_count + ". Tú: " + yo_string + " - Máquina: " + maquina_string + ". Resultado: Empate");
	          } elseif (maquina === 2) {
	            maquina_count++;
	            round_count++
	            console.log("Ronda: " + round_count + ". Tú: " + yo_string + " - Máquina: " + maquina_string + ". Resultado: Perdiste");
	          } elseif (maquina === 3) {
	            yo_count++;
	            round_count++
	            console.log("Ronda: " + round_count + ". Tú: " + yo_string + " - Máquina: " + maquina_string + ". Resultado: Ganaste");
	          }
	          break;
	        case2:
	          if (maquina === 1) {
	            yo_count++;
	            round_count++
	            console.log("Ronda: " + round_count + ". Tú: " + yo_string + " - Máquina: " + maquina_string + ". Resultado: Ganaste");
	          } elseif (maquina === 2) {
	            round_count++;
	            console.log("Ronda: " + round_count + ". Tú: " + yo_string + " - Máquina: " + maquina_string + ". Resultado: Empate");
	          } elseif (maquina === 3) {
	            maquina_count++;
	            round_count++
	            console.log("Ronda: " + round_count + ". Tú: " + yo_string + " - Máquina: " + maquina_string + ". Resultado: Perdiste");
	          }
	          break;
	        case3:
	          if (maquina === 1) {
	            maquina_count++;
	            round_count++
	            console.log("Ronda: " + round_count + ". Tú: " + yo_string + " - Máquina: " + maquina_string + ". Resultado: Perdiste");
	          } elseif (maquina === 2) {
	            yo_count++;
	            round_count++
	            console.log("Ronda: " + round_count + ". Tú: " + yo_string + " - Máquina: " + maquina_string + ". Resultado: Ganaste");
	          } elseif (maquina === 3) {
	            round_count++;
	            console.log("Ronda: " + round_count + ". Tú: " + yo_string + " - Máquina: " + maquina_string + ". Resultado: Empate");
	          }
	          break;
	      }
	    
	      // Verifíca si algún jugador ya ha ganado 3 veces
	      if ((yo_count === 3) || (maquina_count === 3)) {
	        // Asigna un ganador
	        if (yo_count === 3) {
	          alert("Ganaste. Puntaje final: " + yo_count + " - " + maquina_count);
	        } elseif (maquina_count === 3){
	          alert("Perdiste. Puntaje final: " + yo_count + " - " + maquina_count);
	        }
	        //Reinicia las variables para poder jugar nuevamente
	        round_count = 0;
	        yo_count = 0;
	        maquina_count = 0;
	      }
	    }```
	    
	```

* **Juan Camilo Alvarez Jurado** (1)

	```
	    var machinePlay = "rock"
	    
	    function playSwitch(personPlay){
	        switch (personPlay) {
	            case"rock":
	                switch (machinePlay) {
	                    case"rock":
	                        console.log("TIE!")
	                        break;
	                    case"scissors":
	                        console.log("THE MACHINE WINS!")
	                        break;
	                    case"paper":
	                        console.log("YOU WIN!")
	                        break;
	                }
	                break;
	            case"scissors":
	                switch (machinePlay) {
	                    case"rock":
	                        console.log("THE MACHINE WINS!")
	                        break;
	                    case"scissors":
	                        console.log("TIE!")
	                        break;
	                    case"paper":
	                        console.log("YOU WIN!")
	                        break;
	                }
	                break;
	            case"paper":
	                switch (machinePlay) {
	                    case"rock":                    
	                        console.log("YOU WIN!")
	                        break;
	                    case"scissors":
	                        console.log("THE MACHINE WINS!")
	                        break;
	                    case"paper":
	                        console.log("TIE!")
	                        break;
	                }
	                break;
	            default:
	                console.log("INVALID OPTION!! >:C")
	        }
	    }
	    
	    playSwitch('rock')
	    playSwitch('scissors')
	    playSwitch('paper')
	    
	```

* **Pablo Nicolas Fontaine Gilardi** (1)

	```
	    var numeroUsuario = Number( prompt("0. Piedra | 1. Papel | 2. Tijera") );
	    var opcionesSistema = ["Piedra", "Papel", "Tijera"];
	    var numeroAleatorio = Number( Math.floor( opcionesSistema["length"] * Math.random() ) );
	    console.log("Numero aleatorio: " + numeroAleatorio);
	    console.log("Numero usuario: " + numeroUsuario);
	    
	    switch (numeroAleatorio)
	    {
	        case0:
	            if ( numeroUsuario === 0 )
	            {
	                console.log("Empate");
	            }
	            elseif ( numeroUsuario === 1 )
	            {
	                console.log("Ganaste");
	            }
	            elseif ( numeroUsuario === 2 )
	            {
	                console.log("Perdiste");
	            }
	            break;
	        case1:
	            if ( numeroUsuario === 0 )
	            {
	                console.log("Perdiste");
	            }
	            elseif ( numeroUsuario === 1 )
	            {
	                console.log("Empate");
	            }
	            elseif ( numeroUsuario === 2 )
	            {
	                console.log("Ganaste");
	            }
	            break;
	        case2:
	            if ( numeroUsuario === 0 )
	            {
	                console.log("Ganaste");
	            }
	            elseif ( numeroUsuario === 1 )
	            {
	                console.log("Perdiste");
	            }
	            elseif ( numeroUsuario === 2 )
	            {
	                console.log("Empate");
	            }
	            break;
	        default: console.log("Has elegido mal.");
	    }```
	    
	```

* **Antonio Rafael González Ferrer** (1)

	
	Switches anidados 😬
	``` 
	    functionrandomSelection()
	            {
	                returnMath.floor(Math.random() * 3) + 1
	            }
	    
	            const options = 
	            {
	                1 : "Piedra",
	                2 : "Papel",
	                3 : "Tijeras"
	            }
	    
	            functionplayGame()
	            {
	                console.log('Bienvenid@ al juego Piedra, papelo tijeras! 🎮')
	                console.log(`1. ${options[1]}`)
	                console.log(`2. ${options[2]}`)
	                console.log(`3. ${options[3]}`)
	    
	                const userVar = parseInt(prompt('Ingresa 1, 2 o 3 para decidir:'))
	                console.log(`Usted eligió: ${userVar}. ${options[userVar]}`)    
	                console.log(`Ahora nos toca a nosotros...`)
	                const iaVar = randomSelection()
	                console.log(`Hemos seleccionado: ${iaVar}. ${options[iaVar]}`)
	                
	                switch(userVar)
	                {
	                    case1: // Piedra
	                        switch(iaVar)
	                        {
	                            case1: // vs Piedra
	                                console.log('Es un empate!! 😅')
	                                break;
	    
	                            case2: // vs Papel
	                                console.log('Papel cubre piedra... usted pierde 😟')
	                                break;
	                            
	                            case3: // vs Tijeras
	                                console.log('Piedra rompe tijeras... ¡Ha ganado! 🎆🎈🎆')
	                                break;
	                        }
	                        break;
	    
	                    case2: // Papel
	                        switch(iaVar)
	                        {
	                            case1: // vs Piedra
	                                console.log('Papel cubre piedra... ¡Ha ganado! 🎆🎈🎆')
	                                break;
	    
	                            case2: // vs Papel
	                                console.log(`...`)
	                                console.log('Es un empate!! 😅')
	                                break;
	                            
	                            case3: // vs Tijeras
	                                console.log('Tijeras cortan papel... usted pierde 😟')
	                                break;
	                        }
	                        break;
	    
	                    case3: // Tijeras
	                        switch(iaVar)
	                        {
	                            case1: // vs Piedra
	                                console.log('Piedra rompe tijeras... usted pierde 😟')
	                                break;
	    
	                            case2: // vs Papel
	                                console.log('Tijeras cortan papel... ¡Ha ganado! 🎆🎈🎆')
	                                break;
	                            
	                            case3: // vs Tijeras
	                                console.log(`...`)
	                                console.log('Es un empate!! 😅')
	                                break;
	                        }
	                        break;
	    
	                    default: // valor fuera de las opciones
	                        console.log("🛑 Ingresó un valor erróneo, debe volver a iniciar el juego...")
	                }
	            }
	    
	            playGame()
	    
	```

* **merzeK** (1)
![juego_switch.png](https://static.platzi.com/media/user_upload/juego_switch-4122775d-76b6-468c-94a9-7f3132d9fdea.jpg)

* **stwanga** (1)

	
	Mi código:  
	Incluí switch anidados.
	``` 
	    var num_Piedra = 3;
	    var num_Tijera = 2;
	    var num_Papel = 1;
	    
	    function randomNumber(valorMax, valorMin) {
	        
	        // Obtiene el numero aleatorio entre 1 y 3
	        var numRandon = Math.floor((Math.random() * valorMax) + valorMin);
	    
	        return numRandon;
	    }
	    
	    function valorOpcion(valorOpcion) {
	        
	        var nombreOpcion;
	        switch (valorOpcion) {
	            case1:
	                nombreOpcion = "Papel";
	                break;
	            case2:
	                nombreOpcion = "Tijera";
	                break;
	            case3:
	                nombreOpcion = "Piedra";
	                break;
	            default:
	                nombreOpcion = "Opción no considerada en el juego";
	                break;
	        }
	        return nombreOpcion;
	    
	    }
	    function quienGana (eleccionUsuario) {
	        
	        // Debemos obtener un valor aleatorio para saber que escoge la máquina
	        //  Debe ser entre el 1 y 3 por los valores declarados para cada tipo
	        var random = randomNumber (num_Piedra,num_Papel);
	        
	        // Obtengo el valor seleccionado por el usuario
	        var valorUsuario = valorOpcion (eleccionUsuario);
	    
	        // Obtengo el valor escogido por la máquina
	        var valorComputadora = valorOpcion (random);
	    
	        var mensaje;
	        
	    
	        switch (eleccionUsuario) {
	            case random:
	                mensaje = "Empate, ambos escogieron " + valorUsuario;
	                break;
	        
	            default:
	                switch (eleccionUsuario) {
	                    case num_Papel:
	                        switch (random) {
	                            case num_Piedra:
	                                mensaje = "Ganaste, tu sacaste " + valorUsuario + " y la máquina sacó " + valorComputadora;
	                                break;
	                            case num_Tijera:
	                                mensaje = "Perdiste, tu sacaste " + valorUsuario + " y la máquina sacó " + valorComputadora;
	                                break;
	                        }
	                        break;
	                    case num_Piedra:
	                        switch (random) {
	                            case num_Tijera:
	                                mensaje = "Ganaste, tu sacaste " + valorUsuario + " y la máquina sacó " + valorComputadora;
	                                break;
	                            case num_Papel:
	                                mensaje = "Perdiste, tu sacaste " + valorUsuario + " y la máquina sacó " + valorComputadora;
	                                break;
	                        }
	                        break;
	                    case num_Tijera:
	                        switch (random) {
	                            case num_Papel:
	                                mensaje = "Ganaste, tu sacaste " + valorUsuario + " y la máquina sacó " + valorComputadora;
	                                break;
	                            case num_Piedra:
	                                mensaje = "Perdiste, tu sacaste " + valorUsuario + " y la máquina sacó " + valorComputadora;
	                                break;
	                        }
	                        break;
	                    default:
	                        mensaje = valorUsuario;
	                        break;
	    
	                }
	        }
	    
	        return mensaje;
	    
	    }
	    
	    function juegaPiedraPapelTijera(valorUsuario) {
	        console.log ("La opción seleccionada fue: " + valorUsuario);
	        console.log ("*******************************");
	        var resultado = quienGana (valorUsuario);
	        console.log ("Y el resultado fue: " + resultado);
	        
	    }
	    
	    
	```

* **Raundy Ibarras** (1)

	
	Buenas aquí la repuesta al reto, la verdad es que así con el case es mucho mas legible el código.
	``` 
	    var options = ["Piedra", "Papel", "Tijera"];
	    
	    functionjuego(user) {
	      var option = options[Math.floor(Math.random() * options.length)];
	      console.log(`La pc jugó ${option} y tu jugaste ${user}`);
	    
	      if (option === user) {
	        console.log(`Es un empate, ambas jugadas son iguales!`);
	      } else {
	        switch (user) {
	          case"Piedra":
	            option === "Tijera"
	              ? console.log(`Ganaste!`)
	              : console.log(`Gana la pc!`);
	            break;
	    
	          case"Papel":
	            option === "Piedra"
	              ? console.log(`Ganaste!`)
	              : console.log(`Gana la pc`);
	            break;
	    
	          case"Tijera":
	            option === "Papel"
	              ? console.log(`Ganaste!`)
	              : console.log(`Gana la pc`);
	            break;
	    
	          default:
	            console.log(`Para poder jugar vs la pc, debes escribir los nombres de la siguente forma
	              a: Piedra
	              b: Papel
	              c: Tijera, la primera letra en mayuscula y en singular!`);
	            break;
	        }
	      }
	    }
	    
	    juego("Papel");
	    
	    
	```

* **stevenvalladares** (1)

	```
	    <h1>Piedra, Papel o Tijera</h1>
	        <p>Juega de <strong>Piedra, Papel o Tijera</strong> contra la máquina.</p>
	        <p>El código del juego se realiza utilizando la función <strong><em>Switch</em></strong>.</p>
	        <hr />
	        <h2>Resultado</h2>
	    
	        <scripttype="text/javascript">
	            var user_opt = parseInt(prompt("Elige una opción para jugar:\n 1.- Piedra. \n 2.- Papel. \n 3.- Tijera"));
	            console.log("user choice: " + user_opt + ", type: " + typeof(user_opt));
	    
	            var option = ["Piedra", "Papel", "Tijera"];
	    
	            var machine_opt = option[Math.floor(Math.random() * option.length)];
	            console.log(`selection by machine: ${machine_opt}`);
	    
	            var player = function() 
	            {
	                if (user_opt == 1) 
	                {
	                    var selection = option[0];
	                    console.log(`selection by player: ${selection}`);
	                    return selection;
	                }
	                elseif (user_opt == 2) 
	                {
	                    var selection = option[1];
	                    console.log(`selection by player: ${selection}`);
	                    return selection;
	                }
	                elseif (user_opt == 3) 
	                {
	                    var selection = option[2];
	                    console.log(`selection by player: ${selection}`);
	                    return selection;
	                } 
	                else 
	                {
	                    console.log(`selection by player: ${undefined}`);
	                    returnundefined;
	                }
	            }
	    
	            functionshowInDocument(player, machine) 
	            {
	                document.write("Jugador: <b>" + player + "</b>");
	                document.write("<br />")
	                document.write("Máquina: <b>" + machine_opt + "</b>");
	            }
	    
	            functiontoPlay() 
	            {
	                switch (player()) 
	                {
	                    case"Piedra":
	                        if (machine_opt == option[0])
	                        {
	                            alert("¡Empate!");
	                            showInDocument(player(), machine_opt);
	                        }
	                        elseif (machine_opt == option[1])
	                        {
	                            alert("¡Perdistes!");
	                            showInDocument(player(), machine_opt);
	                        } 
	                        else 
	                        {
	                            alert("¡Ganastes!");
	                            showInDocument(player(), machine_opt);
	                        }
	                    break;
	                    case"Papel":
	                        if (machine_opt == option[1])
	                        {
	                            alert("¡Empate!");
	                            showInDocument(player(), machine_opt);
	                        }
	                        elseif (machine_opt == option[2]) 
	                        {
	                            alert("¡Perdistes!");
	                            showInDocument(player(), machine_opt);
	                        } 
	                        else 
	                        {
	                            alert("¡Ganastes!");
	                            showInDocument(player(), machine_opt);
	                        }
	                    break;
	                    case"Tijera":
	                        if (machine_opt == option[2])
	                        {
	                            alert("¡Empate!");
	                            showInDocument(player(), machine_opt);
	                        }
	                        elseif (machine_opt == option[0]) 
	                        {
	                            alert("¡Perdistes!");
	                            showInDocument(player(), machine_opt);
	                        } 
	                        else 
	                        {
	                            alert("¡Ganastes!");
	                            showInDocument(player(), machine_opt);
	                        }
	                    break;            
	                }
	            }
	    
	            toPlay();
	    
	        </script>
	        
	        <br />
	        <br />
	    
	        <inputtype="button"value="Volver a jugar"onclick="location.reload()" />
	    
	```

* **Noel Mejia** (1)

	```
	    var juego = ["piedra", "papel", "tijeras"];
	    
	    var jugador = juego[Math.floor(Math.random() * 3)];
	    console.log("Jugador: " + jugador);
	    
	    var maquina = juego[Math.floor(Math.random() * 3)];
	    console.log("Maquina: " + maquina);
	    
	    switch (jugador) {
	      case"piedra":
	        if (maquina == juego[1]) {
	          console.log("La maquina gana");
	        } else {
	          console.log("El jugador gana");
	        }
	        break;
	      case"papel":
	        if (maquina == juego[2]) {
	          console.log("La maquina gana");
	        } else {
	          console.log("El jugador gana");
	        }
	        break;
	      case"tijeras":
	        if (maquina == juego[0]) {
	          console.log("La maquina gana");
	        } else {
	          console.log("El jugador gana");
	        }
	        break;
	    }
	    
	```

* **Alejandro Ernesto Vargas Vaca** (1)

	```
	    var opciones = ["piedra","papel","tijera"];
	    
	    function jugar(optJugador){
	        var optPC = opciones[Math.floor(Math.random() * opciones.length)];
	    
	        console.log(`La computadora eligió ${optPC} - El jugador eligió ${optJugador}`);
	    
	        switch(optPC){
	            case"piedra":
	                switch(optJugador){
	                    case"piedra":
	                        console.log("Empate");
	                        break;
	                    case"papel":
	                        console.log("El jugador gana");
	                        break;
	                    case"tijera":
	                        console.log("La máquina gana");
	                        break;
	                }
	                break;
	            case"papel":
	                switch(optJugador){
	                    case"papel":
	                        console.log("Empate");
	                        break;
	                    case"tijera":
	                        console.log("El jugador gana");
	                        break;
	                    case"piedra":
	                        console.log("La máquina gana");
	                        break;
	                }
	                break;
	            case"tijera":
	                switch(optJugador){
	                    case"tijera":
	                        console.log("Empate");
	                        break;
	                    case"piedra":
	                        console.log("El jugador gana");
	                        break;
	                    case"papel":
	                        console.log("La máquina gana");
	                        break;
	                }
	                break;
	            default:
	                console.log("Opción incorrecta");
	        }
	    }
	    
	```

* **mauroquinteros** (1)

	```
	    // Array
	    var players = ["paper", "rock", "scissor"];
	    // Function game
	    game(players[1],2);
	    
	    functiongame(player, index) {
	      var master = players[index];
	      console.log(`Master chose: ${master}`)
	      console.log(`You chose: ${player}`)
	      switch(master){
	        case"paper":
	          switch(player){
	            case"paper":
	              console.log("Anyone wins!")
	              break
	            case"rock":
	              console.log("Master wins!")
	              break
	            case"scissor":
	              console.log("You win!")
	              break
	          }
	          break
	        case"rock":
	          switch(player){
	            case"paper":
	              console.log("You win!")
	              break
	            case"rock":
	              console.log("Anyone wins!")
	              break
	            case"scissor":
	              console.log("Master wins!")
	              break
	          }
	          break
	        case"scissor":
	          switch(player){
	            case"paper":
	              console.log("Master wins!")
	              break
	            case"rock":
	              console.log("You win!")
	              break
	            case"scissor":
	              console.log("Anyone wins!")
	              break
	          }
	          break
	        default:
	          console.log("write a correct option!");
	      }
	    }
	    
	```

* **Juan Zavala** (1)

	
	Interesante

* **danielbandera** (1)
![PPTSWITCH.PNG](https://static.platzi.com/media/user_upload/PPTSWITCH-63daf28e-f4ee-4aeb-9672-41dc043dad88.jpg)

* **Israel Castro Urieta** (1)

	
	Después de muchos intentos por fin quedó 😱 (tomé ejemplos de varios de mis compañeros y de la [documentación de Mozilla](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Sentencias/switch)), aquí mi código:
	``` 
	    var Jugador = Number(prompt('Elije una opción: Piedra = 0, Papel = 1 y Tijera = 2'));
	    var Computadora = Math.floor((Math.random()*10)%3);
	    
	    switch (Jugador) {
	        case0:
	          switch (Computadora) {
	            case0:
	              console.log("Elegiste " + Jugador + " (Piedra) y la computadora " + Computadora + " (Piedra)");
	              console.log("Hubo empate");
	              break;
	            case1:
	              console.log("Elegiste " + Jugador + " (Piedra) y la computadora " + Computadora + " (Papel)");
	              console.log("Gana la computadora");
	              break;
	            case2:
	              console.log("Elegiste " + Jugador + " (Piedra) y la computadora " + Computadora + " (Tijeras)");
	              console.log("Gana el jugador");
	              break;
	          }
	          break;
	        case1:
	          switch (Computadora) {
	            case0:
	              console.log("Elegiste " + Jugador + " (Papel) y la computadora " + Computadora + " (Piedra)");
	              console.log("Gana el jugador");
	              break;
	            case1:
	              console.log("Elegiste " + Jugador + " (Papel) y la computadora " + Computadora + " (Papel)");
	              console.log("Hubo empate");
	              break;
	            case2:
	              console.log("Elegiste " + Jugador + " (Papel) y la computadora " + Computadora + " (Tijeras)");
	              console.log("Gana la computadora");
	              break;
	          }
	          break;
	        case2:
	          switch (Computadora) {
	            case0:
	              console.log("Elegiste " + Jugador + " (Tijeras) y la computadora " + Computadora + " (Piedra)");
	              console.log("Gana la computadora");
	              break;
	            case1:
	              console.log("Elegiste " + Jugador + " (Tijeras) y la computadora " + Computadora + " (Papel)");
	              console.log("Gana el jugador");
	              break;
	            case2:
	              console.log("Elegiste " + Jugador + " (Tijeras) y la computadora " + Computadora + " (Tijeras)");
	              console.log("Hubo empate");
	              break;
	          }
	          break;
	      break;
	        default:
	            console.log("Tienes que elegir Piedra (0), Papel (1) o Tijeras (2)");
	    }
	    
	```

* **horacio-garcia** (1)

	
	me costo entender un par de cosas pero pude!!
	``` 
	    var piedra = 0;
	    var papel = 1;
	    var tijera = 2;
	    var jugador = prompt("elije una opcion")
	    
	    functionRobot() {
	        numerx = (Math.random()*10)%3; //aleatoreo por 10 
	        numero = Math.floor(numerx); //redondeamos numero
	        return numero;
	    };
	    
	    switch (Robot()){
	        case1: (Robot === jugador) 
	                    console.log("win 1");
	                    break;
	        case2: ((Robot === 0) && (jugador ===1)) 
	                    console.log("win 2");
	                    break;
	        case3: ((Robot === 1) && (jugador ===2)) 
	                    console.log("win 2");
	                    break;
	        case4: ((Robot === 2) && (jugador ===0)) 
	                    console.log("win 3");
	                    break;
	                default:
	            console.log("WTF!!");
	    }```
	    
	```

* **Osvaldo Arzate Santiago** (1)

	```
	    var jugador1 = prompt("Elije entre: piedra | papel | tijeras")
	    var jugador2 = prompt("Elije entre: piedra | papel | tijeras")
	    
	    switch (jugador1, jugador2){
	        case"piedra", "piedra":
	            console.log("empate");
	            break;
	        case"papel", "papel":
	            console.log("empate");
	            break;
	        case"tijeras", "tijeras":
	            console.log("empate");
	            break;
	        case"piedra", "tijeras":
	            console.log("Gano jugador 1");
	            break;
	        case"tijeras", "papel":
	            console.log("Gano jugador 1");
	            break;
	        case"papel", "piedra":
	            console.log("Gano jugador 1");
	        default:
	            console.log("Gana jugador 2");
	    }
	    
	```

* **Renato Maximiliano Rivera Abad** (1)

	```
	    var piedra = 0;
	    var tijera = 1;
	    var papel = 2;
	     functionplay (eleccion) {
	            let computer = Math.floor(Math.random()*3);
	            console.log(computer);
	            switch (eleccion) {
	                case1: (eleccion === computer) 
	                    console.log("Empate");
	                    break;
	                case2: ((eleccion === 0) && (computer ===1)) 
	                    console.log("Ganaste 1");
	                    break;
	                case3: ((eleccion === 1) && (computer ===2)) 
	                    console.log("Ganaste 2");
	                    break;
	                case4: ((eleccion === 2) && (computer ===0)) 
	                    console.log("Ganaste 3");
	                    break;
	                default:
	            }
	        }```
	    
	```

* **Mauricio Jofre Heimerl** (1)

	
	Mi respuesta al desafio. Ahora con SWITCH.
	``` 
	    /*=============================================
	        Juego - Piedra, Tijera o Papel
	                    con SWITCH
	    =============================================*/
	    
	    // Esatructura de datos
	    const opciones = ["piedra", "tijera", "papel"];
	    
	    functionjugadorMaquina() {
	      // Retorna un valor aleatorio entre 0 y 3
	      var indice = Math.floor(Math.random() * 3);
	      document.getElementById(
	        "maquina"
	      ).innerHTML = `<strong>Máquina:</strong> ${opciones[indice]}`;
	      return opciones[indice];
	    }
	    
	    /*=============================================
	    =  Obtiene seleccion del Jugador del HTML     =
	    =============================================*/
	    functiongetRadioButtonSelectedValue() {
	      var elementos = document.getElementsByName("opcionesjugador");
	      for (i = 0; i < elementos.length; i++) {
	        if (elementos[i].checked) {
	          var seleccionJugador = elementos[i].value;
	          var seleccionMaquina = jugadorMaquina();
	          /*=============================================
	          =            Jugador = Maquina                =
	          =============================================*/
	          switch (seleccionJugador) {
	            // Combinaciones de Piedra, Papel y Tijera
	            caseseleccionMaquina:
	              mostrarResultado("EMPATE");
	              break;
	            case"piedra":
	              seleccionMaquina === "papel"
	                ? mostrarResultado("PERDISTE")
	                : mostrarResultado("GANASTE");
	              break;
	            case"papel":
	              seleccionMaquina === "tijera"
	                ? mostrarResultado("PERDISTE")
	                : mostrarResultado("GANASTE");
	              break;
	            case"tijera":
	              seleccionMaquina === "piedra"
	                ? mostrarResultado("PERDISTE")
	                : mostrarResultado("GANASTE");
	              break;
	          }
	        }
	      }
	    }
	    
	    // Muestra el resultado en HTML
	    functionmostrarResultado(resultado) {
	      return (document.getElementById(
	        "resultado"
	      ).innerHTML = `<strong>¡${resultado}!</strong>`);
	    }
	    
	```

* **Bárbara de los Ángeles Morantes Carvajal** (1)

	
	Anexo mi aporte, no se me ocurrió como a otros hacer un switch dentro de un switch, así que hice un if dentro de los casos para comparar la opción de la maquina.
	``` 
	    <code>
	    ```var opcion_usuario;  
	     var opcion_maquina; //almacena la opción a generar aleatoriamente 
	     
	    
	    functionaleatorio(){ /* Se encarga de generar un número del 1 al 3  y en función 
	    del resultado asigna a la variable opción_maquina la opción piedra, papel o tijera */ 
	     var aleatorio; 
	     aleatorio = Math.floor(Math.random() * (3 - 1)) + 1; 
	     switch(aleatorio){
	         case1:
	             opcion_maquina = "piedra";
	             break;
	         case2:
	             opcion_maquina = "papel";
	             break;
	         default:
	             opcion_maquina = "tijera";
	     }
	      return opcion_maquina; 
	    } 
	     
	     
	    
	    functionjuego(opcion_usuario, opcion_maquina){/* Se encarga de comparar la variable  
	     opcion_usuario con opcion_maquina para indicar si el usuario perdio, gano, empato o  
	     ingreso una opción no valida*/ 
	     switch(opcion_usuario){
	         case"piedra":
	             if (opcion_maquina === "tijera"){
	                console.log("Tu opción fue: " + opcion_usuario + " y la de la maquina fue: " + opcion_maquina + ". Felicidades, has ganado.");
	             }
	             elseif(opcion_maquina === "papel"){
	                console.log("Tu opción fue: " + opcion_usuario + " y la de la maquina fue: " + opcion_maquina + ". Lo siento, has perdido.");
	             } else {
	                console.log("Tu opción fue: " + opcion_usuario + " y la de la maquina fue: " + opcion_maquina + ". Empate.");
	             }
	            break;
	         case"papel":
	            if (opcion_maquina === "piedra"){
	                console.log("Tu opción fue: " + opcion_usuario + " y la de la maquina fue: " + opcion_maquina + ". Felicidades, has ganado.");
	             }
	             elseif(opcion_maquina === "tijera"){
	                console.log("Tu opción fue: " + opcion_usuario + " y la de la maquina fue: " + opcion_maquina + ". Lo siento, has perdido.");
	             } else {
	                console.log("Tu opción fue: " + opcion_usuario + " y la de la maquina fue: " + opcion_maquina + ". Empate.");
	             }
	            break;
	         case"tijera":
	            if (opcion_maquina === "papel"){
	                console.log("Tu opción fue: " + opcion_usuario + " y la de la maquina fue: " + opcion_maquina + ". Felicidades, has ganado.");
	             }
	             elseif(opcion_maquina === "piedra"){
	                console.log("Tu opción fue: " + opcion_usuario + " y la de la maquina fue: " + opcion_maquina + ". Lo siento, has perdido.");
	             } else {
	                console.log("Tu opción fue: " + opcion_usuario + " y la de la maquina fue: " + opcion_maquina + ". Empate.");
	             }
	            break;
	         default:
	             console.log("La opción ingresada no es valida, por favor intentelo nuevamente");
	     }
	    }
	     
	    
	    opcion_usuario = prompt("Ingresa una opción, piedra, papel o tijera: "); /*Lee el valor ingresado 
	    por el usuario*/ 
	    opcion_usuario = opcion_usuario.toLowerCase(); // Lo convierte en minúsculas para la comparación 
	     
	    
	    aleatorio(); // llamado de la función aleatorio 
	    juego(opcion_usuario,aleatorio()); /* llamado de la función juego y pasa la opcion del usuario  
	    y la generada por aleatorio() por parametro */
	    
	```

* **mexicansauce** (1)

	```
	    var piedra = 0;
	    var papel = 1;
	    var tijeras = 2;
	    var jugadaPCString;
	    
	    functionjuego(miJugada) {
	      var jugadaPCNum = Math.floor(Math.random() * 3); // random del 0 al 2
	      switch (jugadaPCNum) {
	        casepiedra:
	          jugadaPCString = 'piedra';
	          break;
	        casepapel:
	          jugadaPCString = 'papel';
	          break;
	        casetijeras:
	          jugadaPCString = 'tijeras';
	          break;
	      }
	    
	      var res = miJugada - jugadaPCNum;
	    
	      switch (res) {
	        case1:
	        case-2:
	          console.log('Ganaste, la PC escogió ' + jugadaPCString);
	          break;
	        case-1:
	        case2:
	          console.log('Perdiste, la PC escogió ' + jugadaPCString);
	          break;
	        case0:
	          console.log('Empataste, la PC escogió ' + jugadaPCString);
	          break;
	        default:
	          console.log('Valor no válido')
	      }
	    }
	    
	    juego(piedra); // Juegas escogiendo piedra, papel o tijera
	    
	```

* **Sebastián Mera** (1)

	
	Aquí mi código, usé el mismo código que ya había escrito para el reto y modifiqué el if y else if por switch:
	
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-6cc04f0c-3427-4e1d-956f-23589872470a.jpg)

* **Daniel Melchor** (1)

	```
	    var opcion = parseInt(prompt("ingresa un valor 0 -> piedra, 1 -> papel, 2 -> tijera"));
	    
	    jugar(opcion);
	    
	    function jugar(uOpcion){
	        Maquina = Math.floor(Math.random()*3);
	    
	        switch (uOpcion) {
	            case0:
	                switch (Maquina){
	                    case0:
	                        console.log("Empate !!! "+ Maquina);
	                        break;
	                    default:
	                        console.log("Lo siento perdiste !!! "+ Maquina);
	                        break;
	                }
	                break;
	            case1:
	                switch (Maquina){
	                    case0:
	                        console.log("Ganaste !!! "+ Maquina);
	                        break;
	                    case1:
	                        console.log("Empate !!! "+ Maquina);
	                        break;
	                    default:
	                        console.log("Lo siento perdiste !!! "+ Maquina);
	                        break;
	                }
	                break;
	            case2:
	                switch (Maquina){
	                    case2:
	                        console.log("Empate !!! "+ Maquina);
	                        break;
	                    default:
	                        console.log("Ganaste !!! "+ Maquina);
	                        break;
	                }
	                break;
	            default:
	                console.log("Valor ingreado no permitido !!! "+ Maquina);
	                break;
	        }
	    }```
	    
	```

* **Raúl Marfull** (1)
![PPTSwitch.jpg](https://static.platzi.com/media/user_upload/PPTSwitch-bfc6a480-5f40-4cbe-ad23-9985dee89a29.jpg)

* **estefaniajmedina** (1)

	
	Hola les comparto el reto
	
	var jugador, maquina;  
	jugador = prompt(‘Vamos a jugar piedra, papel y tijeras: /n 0.Piedra /n 1.Papel /n 2.Tijera’);  
	maquina = Math.floor(Math.random()*3);  
	function piedra(maquina){  
	switch (maquina) {  
	case 1:  
	console.log(‘Perdiste’);  
	break;  
	case 2:  
	console.log(‘Ganaste’);  
	break;  
	default:  
	console.log(‘Empate’);  
	break;  
	}  
	}
	
	function papel(maquina){  
	switch (maquina) {  
	case 2:  
	console.log(‘Perdiste’);  
	break;  
	case 1:  
	console.log(‘Ganaste’);  
	break;
	``` 
	        default:
	            console.log('Empate');
	            break;
	    }
	    
	```
	
	}
	
	function tijera(maquina){  
	switch (maquina) {  
	case 0:  
	console.log(‘Perdiste’);  
	break;  
	case 1:  
	console.log(‘Ganaste’);  
	break;  
	default:  
	console.log(‘Empate’);  
	break;  
	}  
	}
	
	switch (parseInt(jugador)) {  
	case 0:  
	piedra(maquina);  
	break;  
	case 1:  
	papel(maquina);  
	break  
	case 2:  
	tijera(maquina);  
	break;  
	default:  
	break;  
	}

* **Cristian Rivera Herrera** (1)

	
	Abordé el reto desde esta perspectiva:  
	(Al final pueden enviar las veces que se desee “Resultado();” que les estará indicando la respuesta de lo que sucedió.
	
	Ya en futuras clases doy por hecho que nos enseñará a ingresar datos por parte del usuario.
	``` 
	    // Declaramos nuestras variables y asignamos valores.
	    var Jugador, Computadora;
	    var Respuesta = ["Piedra", "Papel", "Tijera"];
	    Jugador = Math.round(Math.random() * 2);
	    Computadora = Math.round(Math.random() * 2);
	    // Probabilidades				      Valores		Resultado
	    // Piedra gana a Tijeras 		  = 0  2 		* Ganar
	    // Piedra pierde con Papel	  = 0  1
	    // Papel gana a Piedra			  = 1  0 		* Ganar	
	    // Papel pierde a Tijera		  = 1  2
	    // Tijeras ganan a papel		  = 2  1 		* Ganar
	    // Tijeras pierden con Piedra	= 2  0
	    
	    functionResultado()
	    {
	      switch(Jugador)
	      {
	        case0:
	          if (Jugador != Computadora)
	          {
	            if (Computadora == 2)
	            {
	              console.log("Has escogido: " + Respuesta[Jugador] + " y tu adversario " + Respuesta[Computadora] + " por lo tanto has ganado!");
	              break;
	            }
	            else
	            {
	              console.log("Has escogido: " + Respuesta[Jugador] + " y tu adversario " + Respuesta[Computadora] + " por lo tanto has perdido!");
	              break;
	            }
	          }
	          else
	          {
	            console.log("Has escogido: " + Respuesta[Jugador] + " y haz quedado empate");
	            break;
	          }
	        case1:
	          if (Jugador != Computadora)
	          {
	            if (Computadora == 0)
	            {
	              console.log("Has escogido: " + Respuesta[Jugador] + " y tu adversario " + Respuesta[Computadora] + " por lo tanto has ganado!");
	              break;
	            }
	            else
	            {
	              console.log("Has escogido: " + Respuesta[Jugador] + " y tu adversario " + Respuesta[Computadora] + " por lo tanto has perdido!");
	              break;
	            }
	          }
	          else
	          {
	            console.log("Has escogido: " + Respuesta[Jugador] + " y haz quedado empate");
	            break;
	          }
	        case2:
	          if (Jugador != Computadora)
	          {
	            if (Computadora == 1)
	            {
	              console.log("Has escogido: " + Respuesta[Jugador] + " y tu adversario " + Respuesta[Computadora] + " por lo tanto has ganado!");
	              break;
	            }
	            else
	            {
	              console.log("Has escogido: " + Respuesta[Jugador] + " y tu adversario " + Respuesta[Computadora] + " por lo tanto has perdido!");
	              break;
	            }
	          }
	          else
	          {
	            console.log("Has escogido: " + Respuesta[Jugador] + " y haz quedado empate");
	            break;
	          }
	      }
	      Jugador = Math.round(Math.random() * 2);
	      Computadora = Math.round(Math.random() * 2);
	    }
	    
	    Resultado();```
	    
	```

* **Diego Fernando Rojas Quintero** (1)

	
	Reto solucionado. Yo lo hice de dos formas, espero que les sirva para comprenderlo:
	
	  1. De forma anidada
	
	
	``` 
	    const Elección= () => Math.round(Math.random()*2)
	    
	    functionRun(){
	        let computadora = ['piedra','papel','tijera']
	        var EleciónDeLaPersona = prompt ('Escribe tu elecion: piedra papel o tijera')
	        let EleciónDeLaComputadora = computadora [Elección()]
	    
	        console.log('Tu elecion fue: ' + EleciónDeLaPersona);
	        console.log('La elecion de la computadora fue: ' + EleciónDeLaComputadora);
	        
	        switch(EleciónDeLaPersona){
	            case'piedra':
	            case'Piedra':
	            case'PIEDRA':
	                switch(EleciónDeLaComputadora){
	                    case'piedra':
	                        console.log('Empataste');
	                        break
	                    
	                    case'papel':
	                        console.log('perdiste');
	                        break
	    
	                    case'tijeras':
	                        console.log('Ganaste');
	                        break
	                }
	    
	                break
	            
	            case'papel':
	            case'Papel':
	            case'PAPEL':
	                switch(EleciónDeLaComputadora){
	                    case'piedra':
	                        console.log('Ganaste');
	                        break
	                    
	                    case'papel':
	                        console.log('Empataste');
	                        break
	    
	                    case'tijeras':
	                        console.log('perdiste');
	                        break
	                }
	    
	                break
	            
	            case'tijera':
	            case'Tijera':
	            case'TIJERA':
	                switch(EleciónDeLaComputadora){
	                    case'piedra':
	                        console.log('perdiste');
	                        break
	                    
	                    case'papel':
	                        console.log('Ganaste');
	                        break
	    
	                    case'tijeras':
	                        console.log('perdiste');
	                        break
	                }
	    
	                break
	        }
	    }
	    
	    functioninit(){
	        var juego = prompt ('¿Quieres jugar piedra, papel o tijera?')
	    
	        if (juego === 'si'){
	            Run()
	        }else{
	            alert('Que lastima!'); 
	        }
	    }
	    
	```
	
	  1. Utilizando operadores lógicos
	
	
	``` 
	    const Elección= () => Math.round(Math.random()*2)
	    
	    functionRun(){
	        let computadora = ['piedra','papel','tijera']
	        var EleciónDeLaPersona = prompt ('Escribe tu elecion: piedra papel o tijera')
	        let EleciónDeLaComputadora = computadora [Elección()]
	    
	        console.log('Tu elecion fue: ' + EleciónDeLaPersona);
	        console.log('La elecion de la computadora fue: ' + EleciónDeLaComputadora);
	        console.log('');
	        
	        
	        switch (true) {
	    
	        //* Este es el caso si la persona elige piedra
	        
	            case EleciónDeLaPersona==='piedra' && EleciónDeLaComputadora==='piedra':
	            case EleciónDeLaPersona==='Piedra' && EleciónDeLaComputadora==='piedra':
	            case EleciónDeLaPersona==='PIEDRA' && EleciónDeLaComputadora==='piedra':
	                console.log('Empataste');
	                
	                break;
	            case EleciónDeLaPersona==='piedra' && EleciónDeLaComputadora==='papel':
	            case EleciónDeLaPersona==='Piedra' && EleciónDeLaComputadora==='papel':
	            case EleciónDeLaPersona==='PIEDRA' && EleciónDeLaComputadora==='papel':
	                console.log('Ganaste');
	                
	                break;
	            case EleciónDeLaPersona==='piedra' && EleciónDeLaComputadora==='tijera':
	            case EleciónDeLaPersona==='Piedra' && EleciónDeLaComputadora==='tijera':
	            case EleciónDeLaPersona==='PIEDRA' && EleciónDeLaComputadora==='tijera':
	                console.log('Perdiste');
	                
	                break;
	    
	        //* Este es el caso si la persona elige papel
	    
	            case EleciónDeLaPersona==='papel' && EleciónDeLaComputadora==='piedra':
	            case EleciónDeLaPersona==='Papel' && EleciónDeLaComputadora==='piedra':
	            case EleciónDeLaPersona==='PAPEL' && EleciónDeLaComputadora==='piedra':
	                console.log('Ganaste');
	                
	                break;
	            case EleciónDeLaPersona==='papel' && EleciónDeLaComputadora==='papel':
	            case EleciónDeLaPersona==='Papel' && EleciónDeLaComputadora==='papel':
	            case EleciónDeLaPersona==='PAPEL' && EleciónDeLaComputadora==='papel':
	                console.log('Empataste');
	                
	                break;
	            case EleciónDeLaPersona==='papel' && EleciónDeLaComputadora==='tijera':
	            case EleciónDeLaPersona==='Papel' && EleciónDeLaComputadora==='tijera':
	            case EleciónDeLaPersona==='PAPEL' && EleciónDeLaComputadora==='tijera':
	                console.log('Perdiste');
	    
	                break;
	        
	        //* Este es el caso si la persona elige tijeras
	    
	            case EleciónDeLaPersona==='tijera' && EleciónDeLaComputadora==='piedra':
	            case EleciónDeLaPersona==='Tijera' && EleciónDeLaComputadora==='piedra':
	            case EleciónDeLaPersona==='TIJERA' && EleciónDeLaComputadora==='piedra':
	                console.log('Perdiste');
	                
	                break;
	            case EleciónDeLaPersona==='tijera' && EleciónDeLaComputadora==='papel':
	            case EleciónDeLaPersona==='Tijera' && EleciónDeLaComputadora==='papel':
	            case EleciónDeLaPersona==='TIJERA' && EleciónDeLaComputadora==='papel':
	                console.log('Ganaste');
	                
	                break;
	            case EleciónDeLaPersona==='tijera' && EleciónDeLaComputadora==='tijera':
	            case EleciónDeLaPersona==='Tijera' && EleciónDeLaComputadora==='tijera':
	            case EleciónDeLaPersona==='TIJERA' && EleciónDeLaComputadora==='tijera':
	                console.log('Empataste');
	    
	                break;
	        }
	    }
	    
	    functioninit(){
	        var juego = prompt ('¿Quieres jugar piedra, papel o tijera?')
	    
	        if (juego === 'si'){
	            Run()
	        }else{
	            alert('Que lastima!'); 
	        }
	    }
	    
	    init()
	    
	```

* **eocas98** (1)

	
	Solución al reto
	``` 
	    let eleccion = prompt("Escoge piedra(Pi), papel(Pa) y Tijera(T)").toUpperCase();
	    let computador = ["PI", "PA", "T"];
	    let eleccionComputador = computador[Math.floor(Math.random() * 3)];
	    
	    function PiedraPapelTijera(eleccion, eleccionComputador) {
	        debugger
	        switch (eleccion) {
	            case"PA":
	                switch (eleccionComputador) {
	                    case"PI":
	                        console.log("Ganaste!!!");
	                        break;
	                    case"PA":
	                        console.log("Empate");
	                        break;
	                    case"T":
	                        console.log("Perdiste!!!");
	                        break;
	                    default:
	                        console.log("Han sucedido cosas raras");
	                };
	                break;
	    
	            case"PI":
	                switch (eleccionComputador) {
	                    case"T":
	                        console.log("Ganaste!!!");
	                        break;
	                    case"PI":
	                        console.log("Empate");
	                        break;
	                    case"PA":
	                        console.log("Perdiste!!!");
	                        break;
	                    default:
	                        console.log("Han sucedido cosas raras");
	                };
	                break;
	    
	            case"T":
	                switch (eleccionComputador) {
	                    case"PA":
	                        console.log("Ganaste!!!");
	                        break;
	                    case"T":
	                        console.log("Empate");
	                        break;
	                    case"PI":
	                        console.log("Perdiste!!!");
	                        break;
	                    default:
	                        console.log("Han sucedido cosas raras");
	                };
	                break;
	            default:
	                console.log("Debe elegir una opción válida");
	                break;
	        }
	    }
	    
	    PiedraPapelTijera(eleccion, eleccionComputador);
	    
	```

* **mr_alex** (1)

	```
	    var opcion = ["piedra", "papel", "tijera"]
	    
	    var intro_user = prompt("Elige el numero de tu opcion: 1:Piedra, 2:Papel, 3:Tijera");
	    
	    intro_user=intro_user-1;
	    
	    var pc= Math.floor(Math.random()*3);
	    
	    if(validar_opcion(intro_user)){
	        
	        var user=intro_user;
	        console.log("User:"+opcion[user]+" Pc:"+opcion[pc]);
	        
	        jugar(user,pc)
	        
	    }else{
	        console.log("opcion incorrecta");
	    }
	    
	    
	    
	    function validar_opcion(n){
	         var valido=((n>-1 && n<3)? true: false)
	         return valido;
	    }
	    
	    
	    function jugar(a,b){
	        
	        var ganador=0; //= 0 empate, 1 gana user, 2 gana pc
	        
	            switch(a){
	                case0: //posicion 0 en el arreglo de opcion
	                    switch(b){
	                        case0:
	                            ganador=0;
	                            break;
	                        case1:
	                            ganador=2;
	                            break;
	                        case2:
	                            ganador=1;
	                            break; 
	                    }
	                    break;
	                    
	                case1:
	                    switch(b){
	                        case0:
	                            ganador=1;
	                            break;
	                        case1:
	                            ganador=0;
	                            break;
	                        case2:
	                            ganador=2;
	                            break; 
	                    }
	                    break;
	                    
	                case2:
	                    switch(b){
	                        case0:
	                            ganador=2;
	                            break;
	                        case1:
	                            ganador=1;
	                            break;
	                        case2:
	                            ganador=0;
	                            break; 
	                    }
	                    break;
	                    
	                default:
	                    console.log("Algo salio mal :c");
	                    break;
	            }
	            
	            imprime_ganador(ganador);
	    }
	    
	    
	    function imprime_ganador(g){
	        switch (g){
	            case0:
	                console.log("Empate");
	                break;
	            case1:
	                console.log("Gana user");
	                break;
	            case2:
	                console.log("Gana pc");
	                break;
	            default:
	                break;
	        }
	    }
	    
	```

* **Abraham Guadarrama Rangel** (1)

	
	Tengo un problema, cuando hago una versión corta mi función responde muy bien:
	``` 
	    var persona = ["piedra", "papel", "tijera"];
	    var compu = ["piedra", "papel", "tijera"];
	    
	    function jugar(persona, compu){
	        switch (persona, compu){
	            case ("piedra", "piedra"): 
	                console.log("Es un empate");
	                break;
	            case ("piedra", "tijera"): 
	                console.log("Ganaste humano");
	                break;
	            case ("piedra", "papel"):
	                console.log("Perdiste humano");
	                break;
	            default:
	                console.log("Que paso");
	        }
	    }
	    
	    jugar("piedra", "tijera")
	    
	```
	
	Pero al hacerla más larga deja de funcionar:
	``` 
	    var persona = ["piedra", "papel", "tijera"];
	    var compu = ["piedra", "papel", "tijera"];
	    
	    function jugar(persona, compu){
	        switch (persona, compu){
	            case ("piedra", "piedra"): 
	                console.log("Es un empate");
	                break;
	            case ("tijera", "tijera"):
	                console.log("Es un empate");
	                break;
	            case ("papel", "papel"): 
	                console.log("Es un empate");
	                break; 
	            case ("piedra", "tijera"): 
	                console.log("Ganaste humano");
	                break;
	            case ("tijera", "papel"): 
	                console.log("Ganaste humano");
	                break;
	            case ("papel", "piedra"): 
	                console.log("Ganaste humano");
	                    break;
	            case ("piedra", "papel"):
	                console.log("Perdiste humano");
	                break;
	            case ("papel", "tijera"):
	                console.log("Perdiste humano");
	                break;
	            case ("tijera", "piedra"):
	                console.log("Perdiste humano");
	                break;
	            default:
	                console.log("Que paso");
	        }
	    }
	    
	    jugar("papel", "tijera")```
	    
	    Alguien sabe a qué se debe?
	    
	    
	```

* **Valente IA** (1)

	
	Mi aporte utilizando switch:
	``` 
	    var user = prompt("Elige una opción: 'Piedra', 'Papel', 'Tijera'");
	    var x = ["Piedra", "Papel", "Tijera"];
	    var y = Math.floor(Math.random() * 3);
	    var pc = x[y].toString();
	    
	    console.log("Has elegido " + user);
	    console.log("La computadora eligio " + pc);
	    
	    var result = jugar(user, pc);
	    
	    switch (result) {
	        case0:
	            console.log("Empate!");
	            break;
	        case1:
	            console.log("Has Ganado!");
	            break;
	        case2:
	            console.log("Has Perdido!");
	            break;
	    }
	    
	    function jugar(user, pc)
	    {
	        //pieda gana a tijera, pierde con papel
	        //papel gana a piedra, pierde con tijera
	        //tijera gana a papel, pierde con piedra
	        if(user == pc)
	            return0;
	        elseif ((user == "Piedra" && pc == "Tijera") || (user == "Papel" && pc == "Piedra") || (user == "Tijera" && pc == "Papel"))
	            return1;
	        else
	            return2;
	    }
	    
	```

* **Estiventh Leonardo Neira Aldana** (1)

	```
	    var EleccionJugador = "tijeras";
	    var EleccionComputadora = "piedra";
	    
	    var validador 
	    
	    functiongame(EleccionJugador, EleccionComputadora) {
	            
	        //Si el jugador elije piedra
	    
	        if (EleccionJugador === "piedra" && EleccionComputadora === "tijeras") {
	            console.log("Gana Jugador");
	            validador = 1
	        }
	        elseif (EleccionJugador === "piedra" && EleccionComputadora === "papel") {
	            console.log("Gana Computadora");
	            validador = 2
	        }
	        elseif(EleccionJugador === "piedra" && EleccionComputadora === "piedra"){
	            console.log("Empate, elije de nuevo");        
	            validador = 3
	        }
	    
	        //Si el Jugador elije Papel
	    
	        if (EleccionJugador === "papel" && EleccionComputadora === "tijeras") {
	            console.log("Gana Computadora");
	            validador = 2
	        }
	        elseif (EleccionJugador === "papel" && EleccionComputadora === "piedra") {
	            console.log("Gana  Jugador");
	            validador = 1
	        }
	        elseif (EleccionJugador === "papel" && EleccionComputadora === "papel"){
	            console.log("Empate, elije de nuevo");     
	            validador = 3   
	        }
	    
	        if (EleccionJugador === "tijeras" && EleccionComputadora === "piedra") {
	            console.log("Gana Computadora");
	            validador = 2
	        }
	        elseif (EleccionJugador === "tijeras" && EleccionComputadora === "papel") {
	            console.log("Gana  Jugador");
	            validador = 1
	        }
	        elseif (EleccionJugador === "tijeras" && EleccionComputadora === "tijeras"){
	            console.log("Empate, elije de nuevo");        
	            validador = 3
	        }
	        
	        
	        switch (validador) {
	            case1:
	                console.log("Gana  Jugador");
	                break;
	            case2:
	                console.log("Gana  Computador");
	                break;
	            case3: 
	                console.log("Empate, elije de nuevo");
	                break;
	            default:
	                console.log("seas mamon")
	                break;
	        }
	        
	        
	        
	    
	    }
	    
	    game (EleccionJugador, EleccionComputadora)
	    
	```

* **gustavoadolfocastaedalondo** (1)
Buenas les pregunto, cómo paso los datos de un select a variable, en el html tengo un menu donde uno escoge si piedra, papel o tijera, có...

	* **Danelia Sanchez Sanchez** (1)

		
		Usa el atributo **id** en la etiqueta select (un nombre que identifique ese elemento) para seleccionarlo con la función `getElementById()`:
		``` 
		    <select id ="menu"  name = "menu">
		    	<optionvalue="opcion1">Opcion 1></option>
		    	<optionvalue="opcion2">Opcion 2></option>
		    
		```
		
		y obtener el valor seleccionado mediante la propiedad value:
		``` 
		    var miopcion = document.getElementById("menu").value;
		    
		```

* **jimmy-alexander-castiblanco-bu** (0)

	```
	    <code>
	    var opc = parseInt(prompt("Digite su opcion:"+"\n"+"1. Piedra"+"\n"+"2. Papel"+"\n"+"3. Tijera"));
	    lanzamiento= ["piedra","papel","tijera"];
	    var maquina = lanzamiento[Math.floor(Math.random() * lanzamiento.length)];
	        switch (opc){
	            case1:
	                if(opc === 1){
	                    opc = "piedra";
	                }
	                break;
	            case2:
	                if(opc === 2){
	                    opc = "papel";
	                }
	                break;
	            case3:
	                if(opc === 3){
	                    opc = "tijera";
	                }
	                break;
	        }
	        if(opc === maquina){
	            console.log("EMPATE🙆"+" "+"Usuario:"+opc+" "+"Maquina:"+" "+maquina);
	        }
	        elseif(opc === "piedra" && maquina === "tijera"){
	            console.log("WOW!😀"+" "+"Usuario gana"+"\n"+"Usuario:"+" "+opc+"  "+"Maquina:"+" "+maquina);
	        }
	        elseif(opc === "tijera" && maquina === "piedra"){
	            console.log("OH NO!🤒"+"  "+"La maquina te vencio :("+"\n"+"Usuario:"+" "+opc+"  "+"Maquina:"+" "+maquina);
	        }
	    
	        elseif(opc === "papel" && maquina === "piedra"){
	            console.log("WOW!😀"+" "+"Usuario gana"+"\n"+"Usuario:"+" "+opc+"  "+"Maquina:"+" "+maquina);
	        }
	        elseif(opc === "piedra" && maquina === "papel"){
	            console.log("OH NO!🤒"+"  "+"La maquina te vencio :("+"\n"+"Usuario:"+" "+opc+"  "+"Maquina:"+" "+maquina);
	        }
	    
	        elseif(opc === "tijera" && maquina === "papel"){
	            console.log("WOW!😀"+" "+"Usuario gana"+"\n"+"Usuario:"+" "+opc+"  "+"Maquina:"+" "+maquina);
	        }
	        elseif(opc === "papel" && maquina === "tijera"){
	            console.log("OH NO!🤒"+"  "+"La maquina te vencio :("+"\n"+"Usuario:"+" "+opc+"  "+"Maquina:"+" "+maquina);
	        }
	        elseif(opc !== " "){
	            alert("Error! Digite un valor valido");
	        }
	    
	    
	    
	```

* **isabellaahc** (0)

	
	Mi código, cambié solo la lógica de if por switch
	``` 
	    const valores = ['piedra', 'papel', 'tijera'] 
	    
	    const resultado = (user) => {
	        const maquina = Math.floor(Math.random()* valores.length);
	        const opcionMaquina = valores[maquina];
	        console.log('La maquina a lanzado: '+ opcionMaquina);
	    
	        const opcionUsuario =  parseInt(valores.indexOf(user));
	    
	        const resultado = maquina - opcionUsuario;
	    
	        switch (resultado) {
	            case0:
	                console.log('Empate, elije otra opción')
	               break;
	            case-1:
	                console.log('Ganaste');
	                break;
	            case-2:
	                console.log('perdiste')
	                break;
	            case1:
	                if (opcionMaquina === 'papel' && user === 'piedra') {
	                    console.log('Perdiste');   
	                } else {
	                    console.log('Ganaste');
	                }
	                break;
	            case2:
	                console.log('Ganaste');
	                break;
	            default:
	                console.log('Que paso aquí??')
	                break;
	        }
	        
	    } 
	    
	    resultado('piedra');
	    
	```

# Arrays

## 0140. Arrays

### Descripción:


### Comentarios:

* **medicenmon** (11)

	
	Un **Array** es un tipo de estructura de datos, objeto. Puede guardar datos distintos dentro, guarda los datos en forma de lista.  
	**.lenght** devuelve la longitud del array.  
	**.push()** agrega elementos al final de array.  
	**.pop()** elimina un elemento del array.  
	**.unshift()** agrega un elemento al array, pero lo agrega en primer lugar.  
	**.shift() **elimina el elemento que está en el inicio del array.  
	**.indexOf ** devuelve la posición de un elemento del array.

* **eriksen** (9)

	
	Para complementar un poco, ya que me parece que en los otros cursos de JavaScript tampoco lo mencionan, a los **arrays** también se les pueden asignar o añadir datos con **string keys** , es decir, pasándole un string entre corchetes en vez del índice.
	
	Algo curioso con los string keys es que no influye en la longitud de los arrays, por ejemplo:  
	![](https://i.postimg.cc/QdMBh6p8/Screenshot-1.jpg)
	
	Algunos dirán que si quiero usar string keys, ¿por qué no usar un objeto?  
	Pero la verdad es que dependiendo de lo que estés desarrollando podrías necesitar usar un array de esta forma y si quieres saber la longitud de un array tomando en cuenta las string keys, es posible hacerlo de la siguiente forma:  
	![](https://i.postimg.cc/fytN89Xh/Screenshot-1.jpg)

	* **ArielScc** (1)

		
		Muy interesante…

	* **hidalgolopezdaniel** (1)

		
		Genial tu aporte!

	* **Juan José Vega Quintero** (1)

		
		Esto es muy usado en Python

* **Manuel Rivera** (5)

	
	Por ende los métodos shift y pop no es obligatorio pasarles parametros

	* **AlexanderAReyes** (3)

		
		Es necesario pasarle indices y creo que eso es un parametro

* **Keysi Simbron Guerra** (5)

	
	el .pop() elimina el último elemento del array y el .shift() elimina el primero , no es necesario pasarles un parametro

* **jonymonroy** (4)

	```
	    // ARRAYS MÉTODOS //
	    
	    // push: Coloca un elemento al final del Array
	        //frutas.push('elemento')
	    
	    //pop: Elimina el último elemento del Array
	        // frutas.pop()
	    
	    //unshift: coloca un elemento al comienzo del Array
	        //frutas.unshift('elemento');
	    
	    
	    //shift: Elimina el primer elemento del Array   
	        // frutas.shift()
	    
	    // indexOf: indica la posición del elemento
	        //frutas.indexOf('elemento' Ej:'Cereza')
	    
	```

* **Estiventh Leonardo Neira Aldana** (4)

	
	No entiendo para qué se lo coloca entre comillas el nombre de “Manzana” o de “Cerezas” si igualmente se borrará el que esté de primero en el caso de .shift osea, qué sentido tiene ponerle eso?

	* **Valente IA** (1)

		
		También tuve esa duda, no tiene caso indicar el elemento ya que siempre borrara el primer o ultimo elemento

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Lo que quiere indicar el profesor al poner en el shift o pop el parámetro es precisamente comprobar que no importa lo que se ponga siempre va a borrar el primer o último elemento

	* **Rodrigo Josué Hernández Barrios** (1)

		
		Solo lo hizo para que fuera más explicito el ejemplo, pero solo con mandar llamar la función, suficiente, ya lo interpreta que se elimine un elemento (pop) o lo agregue (push).

* **Kevin Vega** (4)

	
	El objeto Array de JavaScript es un objeto global que es usado en la construcción de arrays, que son objetos tipo lista de alto nivel.
	
	<https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array>

* **Alfonso Luis Arrieta Hernández** (4)

	
	Esta es una buena documentación sobre javascript.  
	<https://devdocs.io/javascript/>

* **EddJoy** (4)

	```
	    //Forma sintaxica de generar un array
	    var frutas = ["Manzana", "Plátano", "Cereza", "Fresa"];
	    console.log(frutas);
	    console.log(frutas.length); //Para ver tamaño del array
	    console.log(frutas[0]); //Consultar un elemento del array en posición especifica
	    
	    //Metodos que nos ayudan a mutar un array
	    //Agregar más frutas al final de nuestro array
	    var masFrutas = frutas.push("Uvas");
	    //Eliminar ultimo elemento del array
	    var ultimo = frutas.pop("Uvas");
	    //Agregar al inicio de nuestro array
	    var nuevaLongitud = frutas.unshift("Uvas");
	    //Borrar primer elemento del array
	    var borrarFruta = frutas.shift("Manzana");
	    //Nos ayuda a saber la posición del elemento que le pasemos al array
	    var posicion = frutas.indexOf("Cereza");
	    
	    
	```

* **Jharell Alejandra Hidalgo Loya** (3)

	
	pop elimina el ultimo elemento del array  
	push agrega elementos a un array  
	unshift agrega elementos a un array pero en primera posición  
	shift elimina el primer elemento de un array  
	indexof obtienes el index del elemento

* **juanlondono** (3)

	
	un arreglo o un array, es una estructura de datos que se almacena Bajo el mismo nombre a una colección de datos. es decir, cuando nosotros declaramos un arreglo, estamos abriendo un espacio en memoria al igual que lo hacemos con las variables, pero con la diferencia de que un arreglo está seccionado o dividido en varias partes. los arreglos Se caracterizan por: en primer lugar, almacenar los elementos en posiciones contigua de memoria, es decir, los elementos están uno al lado del otro, tienen un mismo nombre de variable que representa a todos los elementos. los elementos, son asignados a una posición dentro del vector y los arreglos trabajan en conjunto con índices que especifican la posición de cada elemento dentro del arreglo.

	* **cristhiandelacruzperu** (1)

		
		Gracias.

* **Julian Andres Cajiao** (3)

	
	array.push => agrega un elemento al final del array  
	array.pop => elimina un elemento del final de un array  
	array.unshift => agrega un elemento al inicio del array  
	array.shift=> elimina un elemento del inicio de un array  
	array.indexOf => nos indica la posicion de un elemento en el array

* **Christian David Sánchez** (3)

	
	 **Arrays**
	
	var languages = [“Javascript”, “C#”, “C”]
	
	  * Para saber cuántos elementos tiene un array:  
	languages.length
	
	  * Para acceder a un elemento de un array:  
	languages[index] => languages[0]
	
	  * Para agregar un elemento al final de un array:  
	languages.push(“Javascript”)
	
	  * Para agregar un elemento al inicio de un array:  
	languages.unshift(“Javascript”)
	
	  * Para eliminar el primer elemento de un array:  
	languages.shift(“Javascript”)
	
	  * Para eliminar el último elemento de un array:  
	languages.pop(“Javascript”)
	
	  * Para obtener la posición de un elemento:  
	languages.indexOf(“C#”);
	
	
	

* **Juan Marcos Caicedo Mejía** (3)

	
	Por qué el profesor los pronuncia como Arrayls?

	* **María Gemini** (1)

		
		Supongo que se le mezcla con el español, arreglo.

* **kikega** (2)

	
	Asi queda mejor
	``` 
	    var frutas = ["Manzana", "Pera", "Naranja", "Platano"];
	        
	        // Agregar elementos a un array y devuelve el tamaño del array
	        var masFrutas = frutas.push("Cerezas");
	        
	        // Extraer un elemento del array, devuelve el elemento
	        var elemento = frutas.pop();
	        
	        // Agregar un elemento al principio del array
	        var nuevoItem = frutas.unshift("Fresa");
	        
	        // Eliminar el primer elemento del array
	        var borrarFruta = frutas.shift();
	        
	        // Devuelve la posición de un elemen to del array
	        var posicion = frutas.indexOf("Platano";) 
	    
	```

* **Germán González** (2)

	
	Array tiene los siguientes metodos:
	
	  * .push : Añade un elemento al final del array.
	  * .pop : Elimina un elemento del final del array
	  * .unshift : Añade al inicio
	  * .shift : Elemina del inicio
	  * .indexOf : posicion del elemento
	
	

* **gonzaloPzl** (2)

	
	No hace falta escribir el nombre de la fruta a la hora de eliminar ya sea con pop o shift, es decir:
	``` 
	    var frutas = ["Manzanas", "Bananas", "Cerezas", "Frutillas"];
	    var menosFinal = frutas.pop();
	    var menosInicio = frutas.shift();
	    
	    
	```

* **mexicansauce** (2)

	
	Parece ser que los métodos pop y shift no necesitan parámetros para eliminar el último y el primer elemento de un array (segun el caso). Basta con:
	``` 
	    var ultimo = frutas.pop()
	    var borrarFruta = frutas.shift()
	    
	```
	
	Fuentes:  
	<https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/pop>  
	<https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/shift>

* **Franciree Arellán** (2)

	
	Con array.pop() elimino el último elemento del array.  
	Con array.shift() elimino el primer elemento del array.
	
	¿Hay forma de eliminar un elemento en medio del array?

	* **urieelmm** (5)

		
		Puedes usar el método splice  
		array.splice(x,1)
		
		Dónde x es el índice que deseas eliminar y 1 es la cantidad de elementos que deseas eliminar.
		
		Array inicial: [“fresa”, “manzana”, “plátano”, “melón”]  
		Método splice: frutas.splice(1,1)  
		Elemento que elimina: [“manzana”]  
		Array después de usar el splice: [“fresa”, “plátano”, “melón”]

* **ag94e** (2)
¿Cómo borro un elemento del array que no está ni al principio ni al final?

	* **Alexei Alvarez** (3)

		
		Puedes utilizar el método .slice
		
		<https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array/slice>

* **Javier Andres Gamboa Duarte** (2)
Cuando se aplica un método siempre se debe asignar a una variable?

	* **Gabriel De Andrade (Platzi)** (1)

		
		No necesariamente, en este caso se muestra de esa forma porque es más didáctico, pero si aplicas un método que modifique el array original, como .push o .pop, no necesitas declarar una variable, si por otra parte usas un método que devuelve un nuevo array en vez de modificar el original como es el caso de .map en la mayoría de los casos vas a querer aplicarlo a una variable porque de otra manera no tiene mucho sentido utilizarlo 😛

* **geovanygomez** (1)

	```
	    var computadoraElije = "papel"
	    var yoElijo = "piedra"
	    
	    
	    switch(true) {
	    
	    case computadoraElije == yoElijo:  
	    console.log("Empate")
	    break
	    
	    
	    case computadoraElije == "piedra"  && yoElijo == "papel":
	        console.log("Gana humano");
	    break
	    
	    
	    case computadoraElije == "piedra"  && yoElijo == "tijera":
	        console.log("Gana computadora")
	    break
	    
	    
	    case computadoraElije == "papel"  && yoElijo == "piedra":
	        console.log("Gana computadora")
	    break
	    
	    
	    case computadoraElije == "papel"  && yoElijo == "tijera":
	        console.log("Gana Gana humano")
	    break
	    
	    
	    case computadoraElije == "tijera"  && yoElijo == "papel":
	        console.log("Gana computadora")
	    break
	    
	    
	    case computadoraElije == "tijera"  && yoElijo == "piedra":
	        console.log("Gana humano")
	    break
	    
	    
	    default:
	        console.log("Algo salio mal y no se que pudo haber sido")
	    
	    }```
	    
	```

* **Ariel Alejandro Ureña Morales** (1)

	
	Excelente clase.

* **Eduardo Neptali Benso Pasquel** (1)

	
	posición 0 = “Manzanas” , posición 1 = “Plátano” , posición 2 = “Cereza” , posición 3 = “Fresa”

* **garciafran** (1)

	
	En resumen:
	``` 
	    //como generar un array
	    
	    var frutas = ["Manzana", "Pera", "Banano", "Cereza", "Fresa"];
	    
	    console.log(frutas);
	    
	    console.log(frutas.length)
	    console.log(frutas[0]);
	    console.log(frutas[3]);
	    
	    //para agregar elementos a un array
	    var masFrutas = frutas.push("Uvas");
	    
	    //para eliminar elementos de un array
	    var ultimo = frutas.pop("Uvas");
	    var ultimo = frutas.pop(frutas.length-1);
	    
	    //para agregar un elemento al inicio del array
	    var nuevoItem = frutas.unshift("Durazno")
	    
	    //para borrar el primer elemento de un array
	    var borrarFruta = frutas.shift();
	    
	    //para averiguar la posicion de un elmento en un Array
	    var posicion = frutas.indexOf("Cereza");
	    frutas[posicion]```
	    
	```

* **carlosextra1** (1)

	
	Excelente clase!!

* **Jeisson Santiago Cortes Ortiz** (1)

	
	😃

* **picojohn** (1)

	
	buena explicacion

* **marlonhmp** (1)

	
	Genial

* **Juan Esteban Galvis** (1)

	
	Entender qué o como funciona un Array es sencillo, lo complicado es aprenderse todas las funciones que ofrece Javascript ajaja

	* **Gabriel Zapata** (2)

		
		En principio parece un problema, pero esto por intentar aprenderlo todo junto desde el principio, se trata de conocerlas, no de memorizarlas, al final del día un programador trabaja con apuntes y no con lo que memorizo a lo largo de su carrera

* **Germán Moreno** (1)

	
	Excelente.

* **Aníbal Javier Ladera Hernández** (1)

	
	Aqui comparto mi if sobre el tema y juego:
	``` 
	    functiongame(item_1, item_2)
	    {
	        if(item_1 === item_2)
	        {
	            return"Empate"
	        }
	        elseif(item_1 !== item_2)
	        {
	            if(
	                (item_1==="tijera" && item_2==="piedra")    || 
	                (item_1==="piedra" && item_2==="papel")     || 
	                (item_1==="papel" && item_2==="tijera") 
	               )
	            {
	                return"Perdiste"
	            }
	            elseif(
	                    (item_1==="tijera" && item_2==="papel")  || 
	                    (item_1==="piedra" && item_2==="tijera") ||
	                    (item_1==="papel" && item_2==="piedra") 
	                    )
	            {
	                return"Ganaste"
	            }
	        }
	    }
	    
	```

* **Edgar Ramirez** (1)

	
	Si alguien me puede ayudar, funciona pero los resultados no coinciden, cuando debería empatar pierdo , y así en varios casos!
	``` 
	    let user = ["piedra","papel","tijera"]
	            console.log(user)
	            let cpu = Math.floor(Math.random()*3);
	            console.log(cpu);
	    
	            functionposicionEnArrayDeUser(textoABuscar, user) {
	    
	        var posicionEncontrada = -1
	    
	        for(var i = 0; i < user.length; i++) {
	    
	        if(user[i] == textoABuscar ) {
	    
	            posicionEncontrada = i
	            break
	        }
	    }
	    
	    return posicionEncontrada
	    }
	    
	    var texto = prompt("Elija una opcion", "piedra,papel,tijera")
	    var posicion = posicionEnArrayDeUser(texto, user)
	    
	    
	        
	           functionplay (){
	               switch (posicion){
	                   case1: ((posicion === 0) && (cpu === 1)) 
	                   alert("perdistes")
	                   break
	    
	                   case2: ((posicion === 0) && (cpu === 2))
	                   alert("ganaste")
	                   break
	    
	                   case3: ((posicion === 1) && (cpu === 0)) 
	                   alert("ganaste")
	                   break
	    
	                   case4: ((posicion === 1) && (cpu === 2)) 
	                   alert("perdistes")
	                   break
	    
	                   case5: ((posicion === 2) && (cpu === 0)) 
	                   alert("perdistes")
	                   break
	    
	                   case6: ((posicion === 2) && (cpu === 1)) 
	                   alert("ganaste")
	                   break
	                   case7: (posicion === cpu)
	                   alert("empate")
	                   default: 
	                   alert(" empate")
	    
	               }
	               
	           }console.log(posicion)
	            play()```
	    
	```

* **Rickert Gonzales Ramires** (1)

	
	fruta(0) = manzana

* **Rafael Alvarez Cardona** (1)

	
	@drgranda tiene que especificar el tipo de **platano** ya que hay muchas culturas aqui!

* **laystiben** (1)

	
	cómo elimino un elemento de un array por su posicion o nombre?

	* **Rafael Alvarez Cardona** (2)

		```
		    let frutas = ["manzana", "uva", "pera", "cereza"]
		      frutas.splice(1,1)
		      //la consola arroja ["uva"]
		      //Donde 1 es "manzana" y 1 apartir de manzana es "uva"
		    
		```
		
		La Función **splice()** pasándole dos parámetros: el primero será el índice a partir del cual queremos borrar elementos y, el segundo, el número de elementos que queremos borrar a partir de la posición dada
		
		  * con esta funcion si se comienza a contar desde 1
		
		

	* **Gabriel De Andrade (Platzi)** (3)

		
		Y si lo que quieres es crear un array nuevo sin algunos elementos específicamente, tienes [slice()](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array/slice) 😄

* **Alex Toasa** (1)

	```
	    //declarar variable tipo arreglo
	        var frutas = ['manzana', 'platano', 'uva', 'sandia'];
	    //consultar longitud de arreglo (devuelve 4)
	        console.log(frutas.length);
	    //consulta el contenido del arreglo
	        console.log(frutas);
	        console.log(frutas[1]); //de una posicion especifica
	    //agregar un elemento al final
	        frutas.push('papaya');
	    //elimina el ultimo elemento 
	        frutas.pop();
	    //agregar un elemento al inicio
	        frutas.unshift('mango');
	    //elimina el primer elemento 
	        frutas.shift();
	    //devuelve la posicion del elemento que se igual al valor consultado
	        frutas.indexOf('uva'); //si no existiera devuelve -1
	    
	```

* **Juan Zavala** (1)

	
	Interesante

* **Bárbara de los Ángeles Morantes Carvajal** (1)

	
	Para llegar a la opción Manzana, la instrucción debera ser console.log(frutas[0]); y para Cereza, console.log(frutas[2]); Esto debido a que se empieza a contar desde 0.

* **Edwuard Ramos Garcia** (1)

	```
	    var frutas = ['manzana', 'platano', 'uva', 'sandia'];
	    console.log(frutas.length);
	    
	    var masFrutas = frutas.push('papaya');
	    console.log(frutas);
	    
	    var borrarFruta = frutas.pop();
	    console.log(frutas);
	    
	    var nuevaFruta = frutas.unshift('mango');
	    console.log(frutas);
	    
	    var eliminarNuevaFruta = frutas.shift();
	    console.log(frutas);
	    
	    var positionFruta = frutas.indexOf('platano');
	    console.log(positionFruta);
	    
	    console.log(frutas[1]);
	    
	    
	```

	* **Rafael Alvarez Cardona** (1)

		
		Bro… platano es una fruta? :0 JAJAJ pero bacano compa! lo importante es la actitud

	* **Rafael Alvarez Cardona** (1)

		
		 **corrijo, xd de donde soy al platano verde se le llama platano y al banano se le dice tal cual “banano”**

* **Valente IA** (1)

	
	Porque si el método push elimina el último elemento de un array, ¿se indico el elemento “Uvas” dentro del push?, cuando podría ir sin parámetro.  
	También para que se declara una variable para mandar a llamar a los métodos si al final no estamos utilizando esas variables, y se podría mandar a llamar solo al método
	``` 
	    var frutas = ["Manzana", "Plátano", "Cereza", "Fresa"];
	    console.log(frutas);
	    
	    //push, agrega elementos al final de un array
	    frutas.push("Uvas", "Mango", "Kiwi");
	    console.log(frutas);
	    
	    //pop, elimina el último elemento de un array
	    frutas.pop();
	    console.log(frutas);
	    
	    //unshift, agrega elemento al principio
	    frutas.unshift("Piña", "Sandía");
	    console.log(frutas);
	    VM668:2 (4) ["Manzana", "Plátano", "Cereza", "Fresa"]
	    VM668:6 (7) ["Manzana", "Plátano", "Cereza", "Fresa", "Uvas", "Mango", "Kiwi"]
	    VM668:10 (6) ["Manzana", "Plátano", "Cereza", "Fresa", "Uvas", "Mango"]
	    VM668:14 (8) ["Piña", "Sandía", "Manzana", "Plátano", "Cereza", "Fresa", "Uvas", "Mango"]```
	    
	```

	* **Jorgelisapa** (1)

		
		Hola, el método push no elimina elementos de un array, más bien los agrega y lo hace en el ultimo indice de dicho array.

* **Julián David Palacios Cárdenas** (1)

	
	No entiendo algo, ¿porqué estos métodos deben ser cargados a una variable y simplemente no ejecutados?

	* **Eduardo Antonio Rivero Rivera** (2)

		
		Según entiendo es porque el método corresponde al objeto, el método no se ejecuta con otro elemento mas que con el objeto en si. Supongo que por eso, pero si como dices tu si se puede tener otro tipo de elementos.

	* **Alfonso Luis Arrieta Hernández** (2)

		
		Tienes razón, parece “mala práctica”. Sí tienes definido el array frutas, puedes ejecutar métodos directamente sobre ese array sin esperar ningún otro tipo de resultado, ya que se ejecuta el método sobre el array. ejm.  
		Se define el array:
		``` 
		    var frutas = ['Manzana', 'Plátano', 'cereza', 'Fresa'];```
		    
		    fácilmente puedes ejecutar métodos sobre él así.
		    
		```
		
		frutas.pop();
		``` 
		    yse mostrará en pantalla el elemento eliminado....
		    
		```

* **matias-alexander-ibarra-trujil** (1)

	
	esto es muy valioso

* **Merlyn Rodriguez** (1)

	
	dos puntos por terminar de ver el video :v

* **Daniel Esteban Santos Mendez** (1)
.pop() y .shift() son metodos que eliminan el elemento primero y último por default, lo podemos llamar sin poner el nombre del elemento e...

	* **ag94e** (1)

		
		Como mencionas, .pop() y . shift() solo trabajan con lo ya predefinido por el lenguaje, por ende no es necesario que se coloquen nombres entre los paréntesis.

# Loops

## 0150. Loops For y For...of

### Descripción:


### Comentarios:

* **diego rodriguez** (7)

	
	no tenia ni idea del for of

* **Ginnio Sarabia** (5)

	
	Tengo experiencia desarrollando y olvide colocar el incremento en el for jajaja ciclo infinito.
	
	Tuve que hacer un TOP y un KILL en consola para matar el proceso por que Chrome se congelo

	* **julian orrego** (1)

		
		jajaja cosas que suelen suceder

* **Lorenzo David Lezcano** (5)

	
	La segunda manera de usar el for me gusto mucho, la había visto en códigos pero no entendida como funcionaba, gracias a este video ahora lo se! 😄

* **kikega** (3)

	```
	    var frutas = ["Manzana", "Pera", "Naranja", "Platano", "Uva"];
	    
	    for (i = 0; i < frutas.length; i++) {
	        console.log(`Indice ${i}: ${frutas[i]}`);
	    }
	    
	    for (e of frutas) {
	        console.log(`Elemento ${e}`);
	    }```
	    
	```

	* **platzerito080420202** (1)

		
		en todos los videos tus publicaciones jaja para xd

* **Abraham Caso Torres** (3)

	
	speed x2 se entiendo mejor.

* **Manuel Rivera** (3)

	
	También esta el For…in 😄

	* **Eleazar Carreón Álvarez** (1)

		
		Sí, solo que el for… in lo usemos para objetos con propiedades ya definidas por el usuario.

	* **Valente IA** (1)

		
		También esta el foreach

* **Jorge Enrique Avendaño Jara** (3)

	
	esta es la estructura de un for…of:
	``` 
	    <for (const valor of objetoIterable) {
	      console.log(valor);
	    }>
	    
	```
	
	pueden encontrar mas información sobre for…of en esta pagina:  
	[](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Sentencias/for...of)

* **Jeins1991** (2)
Muy bien explicado, me gusta la forma como enseña este profesor; todo queda muy claro rápidamente.

* **andrés eduardo betancourt bescanza** (2)

	
	Que buena la explicacion del profesor, me aclaro mucho lo de la (i) .

* **Ariel Alejandro Ureña Morales** (1)

	
	Excelente clase, gracias.

* **RemyLebeau** (1)

	
	hasta ahora me entero del FOR OF, muy simple y sencillo para recorrer arreglos.

	* **Cristhian Franco** (2)

		
		En otros lenguajes se le llama for each, util cuando no necesitas el index de cada elemento

* **eduvra** (1)

	
	Super buena explicación.

* **garciafran** (1)

	
	Excelente el uso del for of, no lo conocia.
	``` 
	    var estudiantes = ["Francisco", "Juan", "Cristian", "Liz", "Paola"];
	    
	    functionsaludarEstudiantes(estudiante){
	        console.log(`Hola, ${estudiante}`);
	    }
	    
	    //forma 1 haciendo recorrido del arry mediante el uso de variables de indice
	    for (var i = 0; i < estudiantes.length; i++){
	        saludarEstudiantes(estudiantes[i]);
	    }
	    
	    //forma 2 haciendo recorrido del array de forma implicita con el uso del for of
	    for (var estudiante of estudiantes) {
	        saludarEstudiantes(estudiante);
	    }```
	    
	```

* **carlosextra1** (1)

	
	Excelente y muy usado el for

* **Orlando0302** (1)

	
	genial

* **gustavoadolfocastaedalondo** (1)

	
	No conocía el ciclo for of, muy practico!

	* **Ginnio Sarabia** (1)

		
		Creo que es similar al for each de c#

* **picojohn** (1)

	
	buena explicacion

* **cesaraguilareduardoromero** (1)

	
	excelente explicación

* **marlonhmp** (1)

	
	Muy buena exlicacion de los ciclos repetitivos.

* **Germán Moreno** (1)

	
	Excelente explicación.

* **Christian David Sánchez** (1)

	
	Los bucles pueden ejecutar un bloque de código varias veces. JavaScript admite diferentes tipos de bucles:
	
	  * for - recorre un bloque de código varias veces
	
	  * for/in - recorre las propiedades de un objeto
	
	  * for/of - recorre los valores de un objeto iterable
	
	  * while - recorre un bloque de código mientras se cumple una condición específica
	
	  * do/while - también recorre un bloque de código mientras se cumple una condición específica
	
	
	

* **leotori** (1)

	
	Para quien no sepa como sacar este carácter (``) lo logras presionando alt + 96 en el teclado numérico.  
	Aquí les adjunto la referencia  
	<https://elcodigoascii.com.ar/codigos-ascii/acento-grave-codigo-ascii-96.html>

	* **picojohn** (1)

		
		me toco usar el mapa de caracteres de windows, pero gracias por tu aporte

* **Jair Israel Avilés Eusebio** (1)

	
	Encontre este articulo en el cual me parece interesante la explicacion y diferencia del loop `for...of` y `for...in`
	
	[for…of vs for…in Loops in JavaScript](https://alligator.io/js/for-of-for-in-loops/)

* **gonzaloPzl** (1)

	
	Excelente explicación

* **Pedro Renatto Neciosup Liza** (1)

	
	muy buen dato!  
	For in => Objects  
	For of => Arrays

* **Juan Zavala** (1)

	
	Desde cuando existe esa opción de For of ??

	* **John Alexander Diaz Astudillo** (2)

		
		Eso fue de las grandes apariciones en 2015 de ES6 ó ES2015, fueron grandes cambios porque desde el 2011 existía ES5 y los cambios eran algo pequeños entre ediciones, desde el 2015 se vienen haciendo modificaciones anuales. [wikipedia](https://es.wikipedia.org/wiki/ECMAScript)

	* **José Abdiel Ortega Vázquez** (1)

		
		Existe otro que se llama [for in](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Sentencias/for...in) solo que es para iterar objetos y recorre los keys de las propiedades no los valores.

* **Juan Zavala** (1)

	
	Como siempre lo digo, todos los días se aprende algo nuevo, por muy pequeño que sea, excelente curso

* **SoterRamirez** (1)

	
	Aprendes mucho, en serio no sabia eso de for of!!
	
	For
	``` 
	    //Nuestro Arrey tiene 4 elementos
	    var estudiantes = [ "Soter", "Maria", "Sergio"];
	    
	    //Hacer la tarea del loop, lo ejecutara de forma manual. Trabajar la función para que haga la tarea
	    functionsaludarEstudiantes (estudiante){
	    	console.log(`Hola, ${estudiante}`);
	    }
	    //Cuál sería el Loop?
	    //Este sería el Loop
	    //Mientras la variable i sea menor a menor a la longitud de estudiantes i se va a aumentar con +1 
	    for(var i = 0; i < estudiantes.length; i++){
	    	//SI se cumple la condición manda a llamar los saludos
	    	saludarEstudiantes(estudiantes[i]);
	    }
	    
	    
	```
	
	For of
	``` 
	    var estudiantes = [ "Soter", "Maria", "Sergio"];
	    functionsaludarEstudiantes (estudiante){
	    	console.log(`Hola, ${estudiante}`);
	    }
	    //Tenemos un array de estudiantes y vamos a mandar  llamar a cada estudiante del arrey de estudiantes
	    for(var estudiante of estudiantes){
	    	//Mandamos a llamar nuestra función
	    	saludarEstudiantes(estudiante);
	    }
	    
	```

* **Diego Fernando Rojas Quintero** (1)

	
	Reto de la clase: Escribe un programa que muestre los números del 1 al 50, con las siguientes excepciones:
	
	  * Para los múltiplos de 3 muestra la palabra “Fizz” en lugar del número.
	
	  * Para los múltiplos de 5 muestra la palabra “Buzz” en lugar del número.
	
	  * Para los múltiplos de 3 y 5 muestra la palabra “FizzBuzz” en lugar del número.
	
	
	
	
	NOTA: EL ALGORTITMO DEBERA ESTAR EN UNA SOLA LINEA DE CODIGO.

	* **César Oswaldo Mandamiento Salas** (1)

		```
		    for (let i = 1; i <= 50; i++) {
		        console.log((i%3 === 0 ? 'Fizz':'') + (i%5 === 0 ? 'Buzz':'') || i)
		    }
		    
		```

	* **Diego Fernando Rojas Quintero** (1)

		
		Buen hecho cmandamiento_

* **Valente IA** (1)

	
	falto explicar el foreach.
	``` 
	    var frutas = ["Manzana", "Plátano", "Cereza", "Fresa"];
	    
	    //push, agrega elementos al final de un array
	    frutas.push("Uvas", "Mango", "Kiwi");
	    
	    //pop, elimina el último elemento de un array
	    frutas.pop();
	    
	    //unshift, agrega elemento al principio
	    frutas.unshift("Pera","Piña", "Sandía");
	    
	    //shift, elimina el primer elemento del array
	    frutas.shift();
	    
	    var position = frutas.indexOf("Piña");
	    
	    //1
	    for(var i = 0; i < frutas.length; i++)
	    {
	        console.log(frutas[i]);
	    }
	    
	    //2
	    for(var fruta of frutas)
	    {
	        console.log(fruta);
	    }
	    
	    //3
	    frutas.forEach(element => {
	        console.log(element);
	    });```
	    
	```

	* **joaquin-fontela** (1)

		
		Como funcionaria? <array>.forEach(funcion) ?  
		Entonces por cada elemento del array, ejecutaria la funcion?

* **Kevin Vega** (1)

	
	Cuando un bucle for se ejecuta, ocurre lo siguiente:
	
	  1. La expresión de inicialización expresionInicial, si existe, se ejecuta. Esta expresión habitualmente inicializa uno o mas contadores del bucle, pero la sintaxis permite una expresión con cualquier grado de complejidad. Esta expresión puede también declarar variables.
	  2. Se evalúa la expresión condicion. Si el valor de condicion es true, se ejecuta la sentencia del bucle. Si el valor de condicion es false, el bucle for finaliza. Si la expresión condicion es omitida, la condición es asumida como verdadera.
	  3. Se ejecuta la sentencia. Para ejecutar múltiples sentencias, use un bloque de sentencias ({ … }) para agruparlas.
	  4. Se ejecuta la expresión expresionIncremento, si hay una, y el control vuelve al paso 2.
	
	
	
	[https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Bucles_e_iteración](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Bucles_e_iteraci%C3%B3n)

* **Carlos Eduardo Diaz Polanco** (1)

	
	Estudiante se convierte en estudiante[i]

* **hidalgolopezdaniel** (1)

	
	Cada día Amo más Javascript

* **Javier Armando Vargas Vega** (1)

	
	Me parece muy interesante el for…of para recorrer arreglos.  
	Muy práctico y fácil de implementar

* **Merlyn Rodriguez** (1)

	
	dos puntos por terminar de ver el video :v

* **Daniel Carmona** (1)

	
	También me gusto la segunda forma

* **Francisco Varela** (1)
Tengo dos preguntas: En la function saludarEstudiantes(estudiante){ Ese estudiante no debería ser estudiantes? Para que sepa qu...

	* **Ruben Padilla** (1)

		
		¡Hola!
		
		Debes usar los _template literals_ ``
		
		<https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals>
		``` 
		    var estudiantes = ["Maria", "Sergio", "Rosa", "Daniel"];
		    
		    functionsaludarEstudiantes(estudiante) {
		    	console.log(`Hola, ${estudiante}`;
		    }
		    
		    for(var i = 0; i < estudiantes.length; i++) {
		    	saludarEstudiantes(estudiantes[i]);
		    }
		    
		```

* **Oscar Galicia** (1)
var estudiantes = [“Maria”, “Sergio”, “Rosa”, “Daniel”]; function saludarEstudiantes(eraro){ console.log(Hola, ${eraro}); } for(var cualq...

	* **Luis Arturo Lira Cerda** (3)

		
		En este caso, no es que la función sepa que te refieres al Array de estudiantes, si no, en el for, lo que estás haciendo es pasar el nombre de cada estudiante a la función saludarEstudiantes().
		
		Aunque en estricta forma tu código debería lanzar error por el detalle de que Hola, debe estar entre comillas: “Hola” y eraro, debería sólo estar como eraro y no entre ${}.
		``` 
		    console.log("Hola", eraro);
		    
		```
		
		Pero fuera de eso, digamos que se vería de esta manera si pudieras leer paso a paso el código:
		``` 
		    // ------------------------------------
		    for (var cualquiera of estudiantes) {
		      saludarEstudiantes(cualquiera); // cualquiera vale "Maria"
		    }
		    
		    functionsaludarEstudiantes(eraro) { // cualquiera vale "Maria"
		      console.log("Hola", eraro); // cualquiera vale "Maria"
		    }
		    
		    // ------------------------------------
		    for (var cualquiera of estudiantes) {
		      saludarEstudiantes(cualquiera); // cualquiera vale "Sergio"
		    }
		    
		    functionsaludarEstudiantes(eraro) { // cualquiera vale "Sergio"
		      console.log("Hola", eraro); // cualquiera vale "Sergio"
		    }
		    
		    // ------------------------------------
		    for (var cualquiera of estudiantes) {
		      saludarEstudiantes(cualquiera); // cualquiera vale "Rosa"
		    }
		    
		    functionsaludarEstudiantes(eraro) { // cualquiera vale "Rosa"
		      console.log("Hola", eraro); // cualquiera vale "Rosa"
		    }
		    
		    // ------------------------------------
		    for (var cualquiera of estudiantes) {
		      saludarEstudiantes(cualquiera); // cualquiera vale "Daniel"
		    }
		    
		    functionsaludarEstudiantes(eraro) { // cualquiera vale "Daniel"
		      console.log("Hola", eraro); // cualquiera vale "Daniel"
		    }
		    
		```

* **nestor-alejandro-aguilar-munoz** (0)

	
	para que sirve el simbolo $

	* **Angel Joaquín Velasco Gómez** (1)

		
		Es la forma de imprimir variables cuando usas template literals.

	* **Diego Camino** (3)

		
		Hola, se llama ‘template literals’ y es una funcionalidad dentro de EcmaScript6, en lugar de comillas simples (’) o comillas dobles ("), usamos el carácter de _backtick _ o comilla de retroceso(`).  
		Con él vienen nuevas características que nos permiten un mayor control sobre las cadenas dinámicas en nuestros programas.
		
		Por ejemplo:  
		// antigua manera  
		var multiLinea = ‘Primera línea \n Y esta es la segunda línea!’;
		
		// nueva manera  
		var multiLinea = `Primera línea Y esta es la segunda línea!`;
		
		//También la manera de concatenar variables  
		// antigua manera  
		var nombre= ‘Diego’;  
		console.log(‘Hola mi nombre es’ + nombre);
		
		// nueva manera  
		var nombre = ‘Diego’;  
		console.log(`Hi my name is ${nombre}`);
		
		Puedes leer más aquí si te interesa: <https://css-tricks.com/template-literals/>

## 0160. Loops While

### Descripción:


### Comentarios:

* **Eleazar Carreón Álvarez** (7)

	
	Ambos ciclos se ocupan el for y el while. Con for podemos definir un fin de intentos y con el while mientras se cumpla que lo siga haciendo. Es como decir en while sería, seguir cocinando el pollo mientras siga crudo, realmente no sabemos cuando estará cocinado. Si usáramos for podría quedarnos crudo o muy quemado, a menos que fueras un super experto.

	* **AlexanderAReyes** (2)

		
		Muy buena metáfora

* **Oscar Lobo** (3)

	
	aqui el código de la clase con ejemplo tambien del do-while
	``` 
	    var estudiantes = ["Maria", "Sergio", "Rosa", "Daniel"];
	    
	    functionsaludarEstudiante(estudiante) {
	        console.log(`Hola ${estudiante}`);
	    }
	    
	    var i = 0;
	    
	    //do-while
	    do {
	        saludarEstudiante(estudiantes[i]);
	        i++;
	    } while (i < estudiantes.length)
	    
	    //while
	    while (estudiantes.length > 0) {
	        var estudiante = estudiantes.shift();
	        saludarEstudiante(estudiante);
	    }
	    
	```

* **ikertrigueros** (2)

	
	¿Por qué en mi consola, a la hora de imprimir, no me salen los 4 mensajes, y me lo manda de esta manera?
	
	![Sin título.png](https://static.platzi.com/media/user_upload/Sin%20t%C3%ADtulo-ae95e277-c269-49ab-85f5-f06480a9adf9.jpg)
	
	Gracias por el apoyo  
	saludos!

	* **Alejandro Luján** (1)

		
		Tienes que usar las “backticks” para interpolar variables, osea poner variables dentro de un string, y tu estas usando comillas simples en el console.log de la funcion, por eso te lo escribe todo como si fuera texto simple, y no te interpola la variable, saludos!

	* **Alejandro Luján** (1)

		
		Estas son las backticks: ``

* **Christian David Sánchez** (2)

	
	El bucle while recorre un bloque de código siempre que una condición especificada sea verdadera.  
	**Sintaxis**
	``` 
	    while (condition) {
	      // codeblock to be executed
	    }
	    
	```

* **Cesar Octavio de Jesús Meza Carrillo** (2)

	
	Yo creo que depende de que estemos utilizando en su momento, porque a veces sabemos cuantas veces necesitamos ejecutar una fraccion de codigo… o a veces requerimos de cierta condicion para hacer algo no importando el numero de veces,

* **José Ponceleón** (2)
Que hace “shift” para hacer que la variable “estudiante” muestre solo 1 estudiante a la vez y no todos los elementos del array?

	* **Luis Arturo Lira Cerda** (6)

		
		El método shift() sirve para sacar el primer elemento de un array y eso mismo te retorna. Es decir si tenemos:
		``` 
		    var personas = ['Ana', 'Juan', 'Pedro']
		    var persona = personas.shift()
		    
		    /* 
		    persona ahora vale 'Ana'
		    personas ya no tendrá a 'Ana' ahora sólo será ['Juan', 'Pedro']
		    */
		    
		```

* **Ariel Alejandro Ureña Morales** (1)

	
	Excelente clase.

* **garciafran** (1)

	
	muy bueno el recorrido del array, eliminando simultaneamente elementos. 😉
	``` 
	    var estudiantes = ["Francisco", "Juan", "Cristian", "Liz", "Paola"];
	    
	    
	    functionsaludarEstudiantes(estudiante){
	        console.log(`Hola, ${estudiante}`);
	    }
	    
	    while (estudiantes.length > 0) {
	        console.log(estudiantes);
	        var estudiante = estudiantes.shift();
	        saludarEstudiantes(estudiante);
	    }```
	    
	```

* **carlosextra1** (1)

	
	muy usado el ciclo while!! hay que aprenderlo bien!

* **fabio-hernan-mosquera-obando** (1)

	
	Entiendo que en el ejemplo de while(); para que el ciclo termine debe llegar a longitud de elementos cero. de lo contrario se vuelve un loop infinito. por esta razón el array debe mutar de 4 elementos, a 3, a 2, 1 y luego a cero para que el ciclo termine.

* **Laurapregonero** (1)

	
	While es un bucle que que ejecuta una sentencia especifica mientras cierta condición es evaluada si es verdadera.
	
	Muy buenos los Ejemplos!!!

* **Jeisson Santiago Cortes Ortiz** (1)

	
	…

* **picojohn** (1)

	
	buena expicacion, aprendiendo cada dia mas, solo queda practicar

* **Javier Andres Gamboa Duarte** (1)

	
	Bien explicado

* **marlonhmp** (1)

	
	Entendido los Loops, excelente clase.

* **Germán Moreno** (1)

	
	Excelente.

* **Juan Zavala** (1)

	
	Lo que no he entendido las pocas veces que lo vi es esa sintaxis de $ { } ?? alguien me puede explicar que es y para que es ??

	* **renatojobal** (2)

		
		Se llama “template string” o “plantilla de cadena de texto”, lo explica en la clase de Funciones, exactamente a partir del minuto 8:40. :3

	* **Juan Vicente Cordero** (2)

		
		Básicamente es para poder introducir una variable dentro de un string. En sustitución de concatenar la variable.  
		var nom = “Pepe”;
		``` 
		      puede ser así == console.log("Hola " + nom);
		    
		      como se muestra en el curso == console.log(`Hola ${nom}`);
		    
		```
		
		Las comillas son la de la tecla del corchete [ .

	* **GibsonR** (1)

		
		Epale mi pana… el caso de esas comillas (la invertidas o francesas) y el símbolo de pesos es que: de esa manera puede interpolar variables con una cadena de texto; es decir puede meter las dos entidades en un solo renglón o más de un renglón porque ellas permiten también el salto de linea.
		
		var nombre = "Gibson"  
		console.log(`**Hola me llamo** ${nombre}`)
		
		El String está en negrita y la variables está en dentro de las llaves que me permiten pasar el valor o la evaluación de nombre, que como ves definí con Gibson.
		
		De esta manera debe decir en consola Hola me llamo Gibson

	* **John Alexander Diaz Astudillo** (1)

		
		Es cuestión de práctica, la única forma de que te quede claro es practicando, así me ha tocado a mí cada vez que me enseñan una cosa nueva. En este caso en especial te recomiendo [practicar Template Strings en Javascript](https://www.google.com/search?q=template+strings+javascript)

* **Valente IA** (1)

	
	falto un ejemplo del do{  
	//  
	}while(condición);

* **dariusv** (1)

	
	faltaría el ciclo do-while que ejecuta el código una vez antes de validar si la condición es verdadera o falsa

* **Kevin Vega** (1)

	
	while (condicion){  
	sentencia;  
	}

* **Manuel Rivera** (1)

	
	También tenemos el do…while, qeu es un ciclo que se va a ejecutar minimo una vez 😄

* **diego rodriguez** (1)

	
	este loop junto con el do while me parece mas interesante que el for.

	* **vickiavola** (1)

		
		Hola, depende de lo que necesites hacer.

* **Javier Armando Vargas Vega** (1)

	
	Creo que el ciclo más usado es el for.

	* **havelka** (1)

		
		asi es

* **Daniel Carmona** (1)

	
	Ciclos

# Objects

## 0170. Objects

### Descripción:


### Comentarios:

* **Karla Agraz** (5)

	
	Objetos: JS es un lenguaje que está diseñado en un paradigma de objetos.
	
	Ejemplo de Objeto:
	``` 
	    var miAuto = {
	    marca: "Toyota",
	    modelo: "Corolla",
	    año: 2020
	    }
	    
	```
	
	Acceder a una propiedad del objeto:
	``` 
	    miAuto.marca 
	    // "Toyota"
	    
	```
	
	Se pueden agregar propiedades que van a ser una función, se les llama métodos de objetos.
	``` 
	    var miAuto = {
	    marca: "Toyota",
	    modelo: "Corolla",
	    año: 2020, 
	    detallesDelAuto: function () {
	    	console.log(`Auto ${this.modelo}${this.año}`);
	    }
	    
	    // miAuto.detallesDelAuto();
	    //Auto Corolla 2020
	    
	```
	
	¿Quién es this?  
	Es una variable que hace referencia al objeto. En este caso: this = miAuto.

* **Julián David Palacios Cárdenas** (3)

	
	Diego explica de forma simple y entendible estos conceptos abstractos, gracias!

* **garciafran** (2)

	
	Excelente la forma de entender this.
	``` 
	    //this hace referencia a un objeto, en este caso el objeto papa que es el objeto miAuto.
	    
	    var miAuto = {
	        marca: "Chevrolet",
	        modelo: "Spark",
	        annio: 2019,
	        detalleDelAuto: function() {
	            console.log(`Auto ${this.modelo}${this.annio}`)
	        }
	    };
	    
	    
	    
	```

	* **eduvra** (1)

		
		Jaja, yo igual pensé en un spark.

* **juanlondono** (2)

	
	la POO, es una manera de diseñar y desarrollar software que trata de imitar la realidad tomando algunos conceptos esenciales de ella.
	
	el primero de estos es, precisamente, el de objeto, cuyo rasgos son la identidad, el estado y el comportamiento.  
	la identidad es el Que distingue a un objeto de otro. posteriormente tenemos, el estado, que son las características que lo describen al objeto y finalmente tenemos el comportamiento que es lo que puede hacer nuestro objeto.
	
	en conclusión, Un identificador es el nombre del objeto, las variables son las características del objeto y, los métodos son el comportamiento de nuestro objeto

* **Christian David Sánchez** (2)

	
	 **Objetos**
	
	  * Para declarar un objeto la sintaxis es:  
	var myObject = {property : “value”}  
	Ejemplo:  
	var myCar = {  
	color: “Red”,  
	year: 2015,  
	}
	
	  * Para acceder a un objeto:  
	myCar.year;
	
	
	

* **Jose Tabango** (2)
Javascript es orientado a objetos, pero es multi paradigma (permite varios estilos de programación), soporta la programación funcional, orientada a objetos e imperativa. Fuente: https://developer.mozilla.org/es/docs/Web/JavaScript

* **Eleazar Carreón Álvarez** (2)

	```
	    var carro = {
	      marca: 'ford',
	      modelo: 'f150',
	      year: '2005',
	      encendido: false,
	      arrancar: function(encendido) {
	        this.encendido = !encendido;
	      },
	    };
	    
	    carro.arrancar(carro.encendido);
	    
	    console.log(carro);
	    
	    carro.arrancar(carro.encendido);
	    
	    console.log(carro);
	    
	```

* **ironcap** (2)
Resumiendo y no se si lo entendí bien. ¿this hace referencia al objeto que lo contiene? en el ejemplo del auto, la funci...

	* **ag94e** (1)

		
		Efectivamente, tal cual lo dices, apuntará a window.object si llamas a this con una función que no tenga un objeto padre diferente al window.object.

* **Ariel Alejandro Ureña Morales** (1)

	
	Muy buena clase

* **carlosextra1** (1)

	
	Ojo todo javascript es un objeto!!

* **Orlando0302** (1)

	
	Excelente clase

* **Juan Pedraza** (1)

	
	Antes de empezar a ver esta clase y en general el tema de objetos, reconozco que esto es una de las cosas que más lata me ha dado en cuanto aprender a programar, sin embargo tengo todas las expectativas que apartir de la fecha no lo será nunca más y al final tener sólido el conocimiento.

* **Laurapregonero** (1)

	
	Un objeto tiene características y metodos. y va de la mano con THIS que hace referencia a el objeto global.

* **Jeisson Santiago Cortes Ortiz** (1)

	
	Curioso, en java el concepto al cual se utiliza para llamar el valor de una característica, es por medio de los métodos de accesibilidad , osea los get() y set(). aclaro que aun me falta profundizar en este lenguaje.

* **picojohn** (1)

	
	empezamos con lo bueno, buena explicacion

* **cesaraguilareduardoromero** (1)

	
	que buena clase

* **Germán Moreno** (1)

	
	Perfecto.

* **marlonhmp** (1)

	
	El `.this` esta entendido hasta aqui pero despues genera algo de confucion xD

* **Juan Esteban Galvis** (1)
La verdad el concepto de **this** me dió mucha dificultad en el curso de JavaScript. Pero busque y entendí, como lo explico el profesor en esta clase está bien para empezar. This es el objeto contexto dónde corre el código

* **Juan Vicente Cordero** (1)

	
	Pero estoy un poco liado con esta explicación, y ha trastocado un pelín el concepto.  
	En esta explicación, no se está construyendo un objeto, sino la definición de una clase de objeto, la cual tiene sus atributos y métodos.  
	Realmente el objeto en sí, se construye cuando se llame al constructor de la clase, que crea una instancia de una clase, siendo esta instancia la materialización de un objeto.  
	Que imagino será explicado en la próxima clase.
	
	Por favor, aclaren.

	* **John Alexander Diaz Astudillo** (8)

		
		Si es un objeto, incluso esto {} también es un objeto, lo que pasa es que hacerlo de esa manera tan básica casi que nunca se utiliza, siempre se crea una clase y los objetos va a ser instancias de esa clase, pero esto es un curso básico y vas a seguir aprendiendo.

	* **Ignacio Bogarín Alvarez** (1)

		
		Espera la siguiente clase… 😃

* **Joseph Paucar** (1)

	
	Excelente explicación, comprimida pero fácil de entender cuando se inicia con los objetos.

* **Juan Zavala** (1)

	
	Excelente profesor, por ende, excelente curso

* **Farid Xacur Novelo** (1)

	
	La sintaxis que estan usando es ECMASCRIPT6??

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Si, hace parte de EcmaScript 6 y se llama literal strings.

* **mafevito** (1)

	
	Los objetos te permiten envolver piezas de datos relacionados y funcionalidad en un solo contenedor. Los objetos tienen:
	
	  * **Propiedades** que muestran información sobre el objeto.
	  * **Métodos** que son funciones o capacidades que tiene el objeto.
	
	

* **Estiventh Leonardo Neira Aldana** (1)

	
	para qué sirve el signo de dolar o pesos cuando estas usando una función? no me quedó claro

	* **Daniel Felipe Merchan Fuquen** (3)

		
		El signo de pesos junto con las llaves nos permiten concatenar strings. Si no lo usaramos tendríamos que concatenar de la siguiente manera:  
		“Auto” + this.modelo  
		Para que funcione debemos usar la comilla invertida (``).Dentro de las llaves podemos escribir código JavaScript dentro de un string:  
		`Auto ${this.modelo}`

* **Kevin Vega** (1)

	
	<https://www.w3schools.com/js/js_objects.asp>

* **diego rodriguez** (1)

	
	muy bueno saber que a los objetos se les puede meter funciones, genial!

* **Miguel Ángel Torres Vargas** (1)

	
	Curioso 🤔 no sabia que se podían añadir funciones a objetos, Gracias por el conocimiento.

	* **Christian David Sánchez** (1)

		
		Los objetos de JavaScript son contenedores para valores con nombre llamados propiedades o métodos.

* **Daniel Carmona** (1)

	
	Objetos y métodos 😄

* **Juan José Vega Quintero** (1)
Alguien sabe por qué no funciona con arrow function?

	* **Juan David Castro (Platzi)** (1)

		
		Puedes mostrarnos el ejemplo que no te funciona y te ayudamos a entender por qué no funciona o, en el mejor de los casos, cómo hacer que sí funcione.

* **Jeisson Santiago Cortes Ortiz** (0)

	
	Un objeto contiene caracteristicas(atributos) y comportamientos(metodos).

## 0180. Objects Función constructora

### Descripción:


### Comentarios:

* **Juan Camilo Alvarez Jurado** (4)

	```
	    var brands = ['Toyota', 'Mazda', 'Renault']
	    var cars = []
	    
	    functionCar(brand, model, year) {
	        this.brand = brand
	        this.model = model
	        this.year = year
	    }
	    
	    for (var i = 0; i < 30; i++)
	        cars.push(new Car(brands[Math.floor(i/10)], `Serie ${i % 10}`, 1999 + i % 10))
	    
	    console.log(cars)
	    
	```

	* **Israel Castro Urieta** (2)

		
		Muy elegante tu código 👏👏👏.

* **Daniel Acevedo Rodriguez** (2)

	```
	    functionauto (marca, modelo, annio){
	        this.marca = marca;
	        this.modelo = modelo;
	        this.annio = annio;
	    }
	    var marca = ["Nissan","Nissan","Nissan","Nissan","Nissan","Nissan","Nissan","Nissan","Nissan","Nissan",
	    "Ford","Ford","Ford","Ford","Ford","Ford","Ford","Ford","Ford","Ford", 
	    "Chevrolet","Chevrolet","Chevrolet","Chevrolet","Chevrolet","Chevrolet","Chevrolet","Chevrolet","Chevrolet","Chevrolet"];
	    var modelo = ["versa", "tida", "altima", "maxima", "sentra", "march","versa" , "altima", "maxima","march",
	    "mustang", "figo", "fiesta", "fusion","mustang", "figo", "fiesta", "fusion","espape", "edge",
	    "beat", "aveo", "spark", "onix", "cavalier", "camaro", "corvette", "beat", "aveo","onix"];
	    var annio = [1999,2000,2004,2020,2019,2014,2012,2006,2020,2005,
	        1999,2000,2004,2020,2019,2014,2012,2006,2020,2005,
	        1999,2000,2004,2020,2019,2014,2012,2006,2020,2005];
	    
	    
	    
	    for (var i = 0; i < marca.length; i++) {
	        var autoNuevo = new auto (marca, modelo, annio);
	        autoNuevo.marca = marca[i]
	        autoNuevo.modelo = modelo[i]
	        autoNuevo.annio = annio[i]
	        console.log(autoNuevo)
	    }```
	    
	```

* **Vicente Andrés Muñoz Moller** (2)

	```
	    var manufacturer = ["Toyota", "Toyota", "Toyota", "Nissan", "Nissan", "Nissan", "Honda", "Honda",
	    "Honda", "Mazda", "Mazda", "Mazda", "Subaru", "Subaru", "Subaru", 
	    "Mercedes-Benz", "Mercedes-Benz", "Mercedes-Benz", "Ferrari", "Ferrari", "Ferrari"];
	    var model = ["Supra", "Corolla", "Celica", "Skyline", "R390 GT1", "Silvia",
	    "NSX", "Civic", "Accord", "RX-7", "RX-8", "Rotary 787B", "Impreza", "Outback", "Legacy",
	    "SLK230", "CL600 AMG", "CLR Racecar", "Enzo", "Testarossa", "F430 F1"];
	    var year = [1994, 1986, 1999, 1989, 1996, 2001, 1991, 1994, 2012,
	    1997, 2004, 1991, 1998, 2007, 2001, 1997, 2000, 1999, 2005, 1990, 2006];
	    
	    var raceCars = [];
	        
	    
	    
	    for (var i = 0; i < 21; i++) {
	        var car = new Object();
	        car.manufacturer = manufacturer[i];
	        car.model = model[i];
	        car.year = year[i];
	        raceCars.push(car);
	    }
	    
	    console.log(raceCars)```
	    
	```

* **Lorena Pinzón** (2)

	
	Mi solución 😄
	``` 
	    functionauto (marca,modelo, anio){
	        this.anio = anio;
	        this.marca = marca;
	        this.modelo = modelo;
	        this.imprimirAutos = function(){
	            console.log(`Tu auto es de marca ${this.marca} del modelo ${this.modelo} del año ${this.anio}`);
	        };
	    }
	    
	    var marca = ["Tesla", "Toyota", "Porsche", "Chevrolet"];
	    var modelo = ["Model X", "Model Y", "Model V", "Model 3"];
	    
	    var misAutos = [];
	    for (var anio = 1990 ; anio<2020; anio++){
	        var i = Math.floor(Math.random() * 4);
	        var j = Math.floor(Math.random() * 4);
	        misAutos.push( new auto (marca[i],modelo[j],anio) );
	    }
	    
	    for (const auto of misAutos) {
	       auto.imprimirAutos();
	    }
	    
	```

* **garciafran** (2)

	
	¯\＿(ツ)＿/¯
	``` 
	    var marca = ["Toyota", "Honda", "Renault", "Volkwagen", "Chevrolet", "Ford", "Suzuki", "Mazda", "Kia", "BMW", "Nissan", "Audi", "Citroen", "Fiat", "Land Rover", "Lexus", "Jaguar", "Jeep", "Mercedes Benz", "Mitsubishi", "Maserati", "Peugeot", "Porsche", "Seat", "Skoda", "Subaru", "Tesla", "Volvo", "Cadillac", "Aston Martin"];
	    var modelo = ["Corolla", "Civic", "Megane", "Amarok", "Spark", "Raptor", "Vitara", "CX5", "Picanto", "Serie 3", "Pathfinder", "A3", "C4 Feel", "Palio Fire", "Defender 110", "GX 460 Luxury", "Xe Sport", "Grand Cherokee", "Clase A", "Montero", "Levante S", "208 Active", "Cayene", "Cordoba", "Octavia", "Forester", "Model X", "V40 Crosscountry T5", "Aston Martin Dbs", "Eldorado Coupe"];
	    var annio = [2010, 2011, 2012, 2013, 2014, 2015, 2016, 2017, 2018, 2019 ,2020, 2011, 2012, 2013, 2014, 2015, 2016, 2017, 2018, 2019 ,2020, 2011, 2012, 2013, 2014, 2015, 2016, 2017, 2018, 2019 ,2020]
	    
	    var listaCarros = [];
	    
	    for (var i = 0; i < 30; i++) {
	        var miCarrito = new Object();
	        miCarrito.marca = marca[i];
	        miCarrito.modelo = modelo[i];
	        miCarrito.annio = annio[i];
	        listaCarros.push(miCarrito);
	    }
	    
	    console.log(listaCarros)
	    
	```

	* **EfrainSanchez** (1)

		
		Compañero, primero gracias por tu aporte, me ayudaste mucho. Tengo una duda, ¿Por qué se crea el array vacío (listaCarros, en tu caso)? Y también, no sé si me podrías explicar como funciona en este caso la linea con el operador "New"  
		**Gracias por tu aporte nuevamente.**

* **Migrant** (2)

	
	Así quedó mi code, lo único que me quedó inconcluso es que quería que cada objeto tuviera el nombre de la marca que caía al azar
	``` 
	    var opcionMarca = ["Lamborghini","Tesla","Mercedes Benz","Audi","Ferrari","Aston Martin","Alfa Romeo","BMW","Porshe"]
	    
	    var annio = [2020, 2019, 2018, 2017, 2016]
	    
	    varcolor = ["Negro","Rojo","Blanco","Dorado","Plata"]
	    
	    var miGarage = []
	    
	        functionpruebaDeAuto(marca, color, annio){
	            this.marca = marca
	            this.color = color
	            this.annio = annio
	        }
	    
	    while (miGarage.length < 31) {
	    	var marcaEscogida = opcionMarca[Math.floor(Math.random()*9)]
	    	var annioEscogido = annio[Math.floor(Math.random()*5)]
	       	var colorEscogido = color[Math.floor(Math.random()*5)]
	        
	       	var autosQueCompre = new pruebaDeAuto(marcaEscogida, colorEscogido, annioEscogido)
	        	var autoNuevo = miGarage.push(autosQueCompre)
	    
	    }```
	    
	```

* **Daniel Esteban Santos Mendez** (2)

	
	Tome un poco de ayuda para saber como ingresaba los datos sin hacer HTML, no me acordaba del prompt.  
	Esta bueno este curso!!!
	``` 
	    functionpersonas(nombre, apellido, edad){
	                this.nombre = nombre;
	                this.apellido = apellido;
	                this.edad = edad;
	            }
	    
	            var personasAgrup = [];
	             
	    
	            for(let i = 0; i < 5; i++){
	                var nombre = prompt('Ingrese su nombre');
	                var apellido = prompt('Ingrese su apellido');
	                var edad = prompt('Ingrese su edad');
	    
	                personasAgrup[i] = new personas(nombre, apellido, edad);
	            }
	            console.log(personasAgrup);
	    
	```

* **Yiy0** (2)

	
	YEP
	``` 
	    var car_list = [];
	    
	    classCar{
	        constructor(brand, model, year) {
	            this.brand = brand;
	            this.model = model;
	            this.year = year
	        }
	    }
	    
	    functionmake_anew_car() {
	        cars = parseInt(prompt("How much cars do you want? type a number."))
	    
	        if (typeof cars === "number"){
	            for (var i = 0; i < cars; i++){
	                brand = prompt("Type the car brand here");
	                model = prompt("Type the car model");
	                year = parseInt(prompt("Type the year in which the car came out"));
	                car_list.push(new Car (brand, model, year));
	            }
	        }else{
	            alert("C'mon brother type a number please");
	        }
	    }
	    
	    make_anew_car();
	    console.log(car_list);
	    
	```

	* **José Bryan Aranda Figueroa** (2)

		
		Hola compañero, me gustaría saber donde o como aprendiste a crear clases en javaScript, lo que pasa es que me gusto mucho tu forma de resolverlo porque la forma que se ve en esta clase que es con la funcion construra me es menos comoda, debido a que yo vengo de estudiar java y pues la forma de crear objetos en ese lenguaje es muy similar a como tu lo hiciste

	* **Yiy0** (2)

		
		Gracias por tu pregunta. 😃 desconozco si la palabra “constructor” como nombre de la función es una palabra reservada o no pero yo la tome literalmente para hacer explícita, válgame la redundancia, la función de esta, si quieres profundizar en JS es recomendable el curso de fundamentos de JS y de ECMAs 6 de platzi, lo que sí conceptualmente puedo alcanzar es que tu puedes tener n numero funciones o constructores del objeto. Lamento no poder profundizar pero también soy nuevo aca XD

	* **José Bryan Aranda Figueroa** (2)

		
		muchas gracias por tu respuesta compañero

* **Francisco Veloz** (2)

	```
	    //Arreglos
	    var Brands = ["Tesla", "Fiat", "Nissan", "Honda"];
	    var Years = [2020, 2019, 2018, 2017];
	    
	    //Creacion de una funcion constructora
	    functionAuto(brand, year)
	    {
	        this.brand = brand;
	        this.year = year;
	    }
	    
	    //Arreglo que guardar los autos
	    var nuevosAutos = [];
	    
	    //Llenado de autos
	    for(var i = 0; i < 30; i++)
	    {
	        var random = Math.floor(Math.random() * 4);
	        nuevosAutos.push(new Auto(Brands[random], Years[random]));
	    }
	    
	    //Imprimir autos
	    for(var autos of nuevosAutos)
	    {
	        console.log(autos);
	    }
	    
	```

	* **Germán González** (1)

		
		Muy bien explicado

* **Nahuel Bonader** (2)

	```
	    functioncar(marca, modelo, annio) {
	      this.marca = marca;
	      this.modelo = modelo;
	      this.annio = annio;
	    }
	    
	    var cars =[]
	    var addCar = (newCar) => {cars.push(newCar);}
	    var marcas = ["Renault", "Fiat", "Ford", "Tesla", "BMW"]
	    var modelosRenault = ["Logan", "Duster", "Captur", "Kangoo", "Sandero"]
	    var modelosFiat = ["Argo", "Cronos", "Uno Way", "Toro", "Fiorino"]
	    var modelosFord = ["Fiesta", "Ka", "Focus", "Mondeo", "Mustang"]
	    var modelosTesla = ["Model S", "Model 3", "Model X", "Model Y", "Roadster"]
	    var modelosBMW = ["Serie 3", "Serie 4", "X4", "X6","Z4 Roadster"]
	    var annioAutos = [2016, 2017, 2018, 2019, 2020]
	    
	    for (var i = 0; i < 30; i++) {
	      let marca = marcas[Math.floor(Math.random() * 5)]
	      let modelo;
	      switch (marca) {
	        case"Renault":
	          modelo = modelosRenault[Math.floor(Math.random() * 5)]
	          break;
	        case"Fiat":
	          modelo = modelosFiat[Math.floor(Math.random() * 5)]
	          break;
	        case"Ford":
	          modelo = modelosFord[Math.floor(Math.random() * 5)]
	          break;
	        case"Tesla":
	          modelo = modelosTesla[Math.floor(Math.random() * 5)]
	          break;
	        case"BMW":
	          modelo = modelosBMW[Math.floor(Math.random() * 5)]
	          break;
	      }
	      let annio = annioAutos[Math.floor(Math.random() * 5)]
	      let newCar = new car(marca, modelo, annio)
	      console.log(newCar);
	      addCar(newCar);
	    }
	    
	    console.log(cars);
	    
	    
	```

* **Wandy Rafael Santana Evangelista** (2)

	
	Aqui muestro **mi solucion:**
	``` 
	    let cars = []
	    
	    functioncar (brand, model, year) {
	        this.brand = brand,
	        this.model = model,
	        this.year = year
	    }
	    
	    const fillCars = () => {
	        let carsNumbers = prompt('How many cars do you want to register?')
	        for(let i = 0; i < carsNumbers; i++){
	            let carBrand = prompt(`Write Car Brand ${i}`);
	            let carModel = prompt(`Write Car Model ${i}`);
	            let carYear = prompt(`Write Car Year ${i}`);
	            let newCar = new car(carBrand, carModel, carYear)
	            cars.push(newCar)
	        }
	    }```
	    
	```

* **caegomezda** (2)

	```
	    <code>functionmiAuto(marca, modelo, annio) {
	        this.marca = marca,
	        this.modelo = modelo,
	        this.annio = annio
	    }
	    const carros = []
	    const NUMERO_DE_CARROS = 30
	    
	    for (let i = 0; i < NUMERO_DE_CARROS; i++) {
	        var marca = prompt('cual es la marca')
	        var modelo = prompt('Cual es la modelo')
	        var year = prompt('Cual es el año')
	        let nuevoCarro = new miAuto(marca, modelo, year)
	        carros.push(nuevoCarro)
	        console.log(nuevoCarro)
	    }
	    for (let i = 0; i < NUMERO_DE_CARROS; i++) {
	        console.log(carros[i])
	    }
	    
	```

* **gonzaloPzl** (2)

	```
	    functioncar(brand, model, year){
	        this.brand = brand;
	        this.model = model;
	        this.year = year;
	    }
	    
	    for(var i = 0; i < 30; i++){
	        var b = prompt('the brand is: ');
	        var m = prompt('the model is: ');
	        var y = prompt('the year is: ');
	        var c = new car(b, m, y);
	        console.log(c)
	    }```
	    
	```

* **Fabián Sandobal** (2)

	```
	    var autoMarca = ["Ford", "Chevrolet", "Renault", "Toyota", "Ferrary", "Lamborgini", "Bugatti", "McClaren"];
	    var autoModelo = ["Mustang", "Camaro", "Sandero", "Hilux", "Superfast", "Murcielago", "Veyron", "P1"];
	    var autoAnnio = [1967, 1965, 2020, 1980, 1985, 2005, 2001, 2010];
	    functionauto( marca, modelo, annio) {
	        this.marca = marca;
	        this.modelo = modelo;
	        this.annio = annio;
	    }
	    for (var i = 0; i < autoMarca.length; i++){
	        var autoFinal = new auto(autoMarca[i], autoModelo[i], autoAnnio[i]);
	        console.log(autoFinal);
	    }
	    
	```
	
	Comenzando me ha costado entender la lógica, pero los ejercicios van ayudando 😄

* **horacio-garcia** (2)

	
	Reto
	``` 
	    let cars = 
	       [{ make: "audi", model: "r8", year: "2012"},
	        { make: "audi", model: "rs5", year: "2013"},
	        { make: "ford", model: "mustang", year: "2012"},
	        { make: "ford", model: "fusion", year: "2015"},
	        { make: "kia", model: "optima", year: "2012"}];
	    
	    functionauto(cars) { 
	        this.make = cars; 
	    };
	    
	    for (let i = 0; i < cars.length; i++) {
	            list = new auto(cars[i]);
	            // var newList = new auto();
	            console.log(list);
	    }```
	    
	```

* **bryanjavier** (2)

	
	Recomiendo mucho el curso de programación orientada a objetos, usa un ejemplo muy bueno durante todo el curso.

* **jonymonroy** (2)

	
	Una solución:
	``` 
	    functionauto(marca, modelo, annio){
	        var marca = ['BMW', 'Audi', 'Lexus', 'Toyota', 'Mazda'];
	        var modelo = ['Model X', 'Model Y', 'Model Z'];
	        var annio = ['2020', '2019', '2018'];
	        this.marca = marca[(Math.floor(Math.random() * 4))];
	        this.modelo = modelo[(Math.floor(Math.random() * 2))];
	        this.annio = annio[(Math.floor(Math.random() * 2))];  
	        
	    }
	    for(i = 0; i < 30; i++) {
	            
	        var nuevoAuto = new auto();
	        console.log(nuevoAuto)
	    }
	    
	```

* **Bárbara de los Ángeles Morantes Carvajal** (2)

	```
	    <code>
	    ``` var autos = []; //arreglo donde se guardan las instancias de auto
	    
	    
	    
	    
	    
	    function auto(marca,modelo,anio){ //función constructura
	    
	      this.marca = marca;
	    
	      this.modelo = modelo;
	    
	      this.anio = anio;
	    
	      
	    
	    }
	    
	    
	    
	    var cantAutos = parseInt(prompt("Indique la cantidad de autos que desea ingresar"));
	    
	    
	    
	    for(var i=0; i < cantAutos; i++){ //ciclo que se repite según la cantidad de autos a ingresar
	    
	      varma = "" ,mo = "" ,a = ""; //variables auxiliares de modelo, marca y año
	    
	      varn=1;
	    
	      ma = prompt(`Ingrese la marca del auto ${n}`); //ingreso de datos
	    
	      mo = prompt(`Ingrese el modelo del auto ${n}`);
	    
	      a = prompt(`Ingrese el año del auto ${n}`);
	    
	      
	    
	      var autoNuevo = new auto(ma,mo,a); //instancia de la clase auto
	    
	      autos[i] = autoNuevo; // se almacena en el arreglo la nueva instancia
	    
	      n++;
	    
	      
	    
	    }
	    
	    
	    
	    clear();
	    
	    console.log(`Se ingresaron ${autos.length} auto(s) \n Los autos ingresados son: `);
	    
	    
	    
	    for(a of autos){ //muestra las instancias creadas.
	    
	      console.log(`${a.marca} ${a.modelo} ${a.anio}`);
	    
	    }
	    
	```

* **mexicansauce** (2)

	```
	    var marcas = ["Ford", "Susuki", "BMW"];
	    var modelos = ["Fiesta", "One", "Bi1532"];
	    var annios = [2020, 2019, 2018];
	    var coches = [];
	    
	    functionauto(marca, modelo, annio){
	      this.marca = marca;
	      this.modelo = modelo;
	      this.annio = annio;
	    }
	    
	    for (i = 0; i < marcas.length; i++) {
	      coches[i] = new auto(marcas[i], modelos[i], annios[i]);
	    }
	    
	```

* **heortizr** (1)

	
	por convencion la funcion constructora (aka constructor) debe iniciar con mayuscula

* **Alejandro Luján** (1)

	
	Listo!! 😛
	``` 
	    let manufacturer = [
	      "Toyota",
	      "Toyota",
	      "Toyota",
	      "Nissan",
	      "Nissan",
	      "Nissan",
	      "Honda",
	      "Honda",
	      "Honda",
	      "Mazda",
	      "Mazda",
	      "Mazda",
	      "Subaru",
	      "Subaru",
	      "Subaru",
	      "Mercedes-Benz",
	      "Mercedes-Benz",
	      "Mercedes-Benz",
	      "Ferrari",
	      "Ferrari",
	      "Ferrari",
	    ];
	    
	    let model = [
	      "Supra",
	      "Corolla",
	      "Celica",
	      "Skyline",
	      "R390 GT1",
	      "Silvia",
	      "NSX",
	      "Civic",
	      "Accord",
	      "RX-7",
	      "RX-8",
	      "Rotary 787B",
	      "Impreza",
	      "Outback",
	      "Legacy",
	      "SLK230",
	      "CL600 AMG",
	      "CLR Racecar",
	      "Enzo",
	      "Testarossa",
	      "F430 F1",
	    ];
	    
	    let year = [
	      1994,
	      1986,
	      1999,
	      1989,
	      1996,
	      2001,
	      1991,
	      1994,
	      2012,
	      1997,
	      2004,
	      1991,
	      1998,
	      2007,
	      2001,
	      1997,
	      2000,
	      1999,
	      2005,
	      1990,
	      2006,
	    ];
	    
	    functionauto(brand, model, year) {
	      this.brand = brand;
	      this.model = model;
	      this.year = year;
	    }
	    
	    for (let i = 0; i < manufacturer.length; i++) {
	      let autoNuevo = [];
	    
	      autoNuevo[i] = new auto(manufacturer[i], model[i], year[i]);
	    
	      console.log(autoNuevo[i]);
	    }
	    
	    
	```

* **david1pc** (1)

	```
	    marca = ["Nissan", "Ferrari", "Toyota", "Renault"];
	    modelo = ["Juke", "F8 Spider", "Corolla", "Zoe"];
	    annio = [2016,2017,2018,2019];
	    
	    
	    function auto(carros){
	        mar = [carros];
	        model = [carros];
	        this.anni = [carros];
	    
	        for(var i=0;i<carros;i++){
	            mar = console.log(marca[i]);
	            model = console.log(modelo[i]);
	            anni = console.log(annio[i]);
	        }
	    }
	    
	    var miAuto = new auto(4);
	    
	    
	```

* **Cristhian Franco** (1)

	
	Mi solución, es un poco floja en cuanto a los datos de los carros, pero no tenia tiempo para investigar modelos y marcas:
	``` 
	    function car(brand, model, year) {
	        this.brand = brand;
	        this.model = model;
	        this.year = year;
	    }
	    
	    function randomCar(numberOfCars) {
	        var carArray = [];    
	    
	        for (let i = 0; i < numberOfCars; i++) {
	            var randomSelection = Math.floor((Math.random() * 4 )+ 1);
	    
	            switch(randomSelection){
	                case1: 
	                    carArray.push(new car("Mitsubishi", "Lancer", 2015));
	                    break;
	                case2:
	                    carArray.push( new car("Toyota", "Corola", 2020));
	                    break;
	                case3:
	                    carArray.push(new car("Kia", "Fiesta", 2018));
	                    break;
	                case4:
	                    carArray.push(new car("BMW", "BMW", 2000));
	                    break;
	                default:
	                    break;
	            }        
	        }
	        
	        console.log(carArray);
	    }
	    
	    randomCar(4);
	    
	    
	    
	    
	```

* **eduardovinagre** (1)

	```
	    functionauto(marca, modelo, anio) {
	      this.marca = marca;
	      this.modelo = modelo;
	      this.anio = anio;
	    }
	    
	    functionobtenerModeloPorMarca(marca) {
	      switch (marca) {
	        case"Chevrolet":
	          return obtenerModeloChevrolet();
	        case"Ford":
	          return obtenerModeloFord();
	        case"Nissan":
	          return obtenerModeloNissan();
	        case"Mazda":
	          return obtenerModeloMazda();
	        case"Toyota":
	          return obtenerModeloToyota();
	      }
	    }
	    
	    functionobtenerModelo(modelos) {
	      let i = Math.floor(Math.random() * modelos.length);
	      return modelos[i];
	    }
	    
	    functionobtenerModeloChevrolet() {
	      let modelos = ["Beat", "Cruze", "Malibu", "Spark", "Volt", "Aveo"];
	      return obtenerModelo(modelos);
	    }
	    
	    functionobtenerModeloFord() {
	      let modelos = ["Fusion", "Fiesta", "Focus", "Figo", "Icon"];
	      return obtenerModelo(modelos);
	    }
	    
	    functionobtenerModeloNissan() {
	      let modelos = ["Altima", "March", "Versa", "Maxima", "Note"];
	      return obtenerModelo(modelos);
	    }
	    
	    functionobtenerModeloMazda() {
	      let modelos = [
	        "Mazda 2",
	        "Mazda 3",
	        "Mazda CX-5",
	        "Mazda MX-5",
	        "Mazda CX-3",
	        "Mazda CX-5",
	        "Mazda CX-9",
	      ];
	      return obtenerModelo(modelos);
	    }
	    
	    functionobtenerModeloToyota() {
	      let modelos = ["Corolla", "Yaris", "Camry", "Supra", "RAV-4", "Prius"];
	      return obtenerModelo(modelos);
	    }
	    
	    functionobtenerMarca() {
	      let marcas = ["Chevrolet", "Ford", "Nissan", "Mazda", "Toyota"];
	      let i = Math.floor(Math.random() * marcas.length);
	      return marcas[i];
	    }
	    
	    functionobtenerAnio() {
	      let primerAnio = 2000;
	      let offset = Math.floor(Math.random() * 20);
	      return primerAnio + offset;
	    }
	    
	    let autos = [];
	    for (let i = 1; i <= 30; i++) {
	      let marca = obtenerMarca();
	      let modelo = obtenerModeloPorMarca(marca);
	      let anio = obtenerAnio();
	      let nuevoAuto = new auto(marca, modelo, anio);
	      autos.push(nuevoAuto);
	    }
	    
	    console.log(autos);```
	    
	```

* **jandresfr** (1)

	
	function constructorAuto(marca, modelo, anio){  
	this.marca = marca;  
	this.modelo = modelo;  
	this.anio = anio;  
	}
	
	var marcasAutos = [“Chevrolet”, “Kia”, “Renault”, “Mazda”];  
	var modelosAutos = [“Spark”, “Picanto”, “Capture”, “3”];  
	var anioAutos = [2020, 2021, 2019, 2018];
	
	var listadoDeAutos = [];
	
	for(var i=0; i<marcasAutos.length; i++){  
	listadoDeAutos[i] = new constructorAuto(marcasAutos[i], modelosAutos[i], anioAutos[i]);  
	}
	
	for(var j=0; j<listadoDeAutos.length; j++){  
	console.log(listadoDeAutos[j]);  
	}
	
	[//console.log](//console.log)(listadoDeAutos[0]);  
	[//console.log](//console.log)(listadoDeAutos[1]);  
	[//console.log](//console.log)(listadoDeAutos[2]);  
	[//console.log](//console.log)(listadoDeAutos[3]);

* **jandresfr** (1)

	
	function constructorAuto(marca, modelo, anio){  
	this.marca = marca;  
	this.modelo = modelo;  
	this.anio = anio;  
	}
	
	var marcasAutos = [“Chevrolet”, “Kia”, “Renault”, “Mazda”];  
	var modelosAutos = [“Spark”, “Picanto”, “Capture”, “3”];  
	var anioAutos = [2020, 2021, 2019, 2018];
	
	var listadoDeAutos = [];
	
	for(var i=0; i<marcasAutos.length; i++){  
	listadoDeAutos[i] = new constructorAuto(marcasAutos[i], modelosAutos[i], anioAutos[i]);  
	}
	
	for(var j=0; j<listadoDeAutos.length; j++){  
	console.log(listadoDeAutos[j]);  
	}

* **OscarAn** (1)

	
	function auto(marca,modelo,annio){  
	this.marca = marca;  
	this.modelo = modelo;  
	this.annio = annio;  
	};
	
	var marca = [“Honda”,“Mitsubishi”,“Tesla”,“Ford”,“Seat”];  
	var modelos = [“Civic”,“Lancer”,“Model X”,“Mustang”,“Leon”];  
	var annio = [2020,2010,2020,1968,2019];
	
	for (let index = 0; index < marca.length; index++) {  
	var autoNuevo = new auto(marca[index], modelos[index],annio[index]);  
	console.log(autoNuevo);
	
	}
	
	//No se si sea la mejor solución pero salio. De hecho tiene de seguro tiene muchos errores

* **ernestojv** (1)

	
	Bastante parecido a Java, pero un poco mas fácil.

* **vanesora** (1)

	
	me consto un chingo! para la proxima, explicar random, floor y math… gracias
	``` 
	    functiongetRandomInt(min, max) {
	        returnMath.floor(Math.random() * (max - min)) + min;
	    }
	    
	    var systema = {
	        modelos: [2019, 2020, 2015, 2017],
	        colores: ["azul", "blanco", "negro", "verde"],
	        marcas: ["subaru", "toyota", "mazda", "chevrolet"]
	    }
	    
	    
	    functionmodeloR(modelos) {
	        const index = getRandomInt(0,4);
	        return modelos[index]
	    }
	    
	    functiondameOpinion() {
	       const modelo = modeloR(systema.modelos)
	        constcolor = colorR(systema.colores)
	        const marca = marcaR(systema.marcas)
	        return`marca: ${marca} color: ${color} modelo: ${modelo}`
	    }
	    
	    functioncolorR(colores){
	        const index = getRandomInt(0,4) //
	        return colores[index]
	    }
	    
	    functionmarcaR(marcas){
	        const index = getRandomInt(0,4)
	        return marcas[index]
	    }
	    
	    
	```

* **Laurapregonero** (1)

	
	Hola, como están??? Así fue como me quedo el código!!!
	
	NEW = Va a generar una nueva instancia de nuestra función constructora.
	
	INSTANCIA = Es generar un objeto que derriba de otro objeto.
	
	…  
	function auto(Brand, model, Year, Color) {  
	this.Brand = Brand,  
	this.model = model,  
	this.Year = Year,  
	this.Color = Color  
	}
	
	let Brand = [ ‘Lamborghini’, ‘Ford’, ‘Audi’, ‘BMW’, ‘Camaro’, ‘Toyota’];  
	let model = [‘Sport’, ‘Classic’, ‘Retro’];  
	var Year = [2020, 2019, 2018, 2017, 2016,2015];  
	let Color = [“White”, “Black”];
	
	for(var i = 0; i < 30; i++) {  
	var index = Math.floor(Math.random() * 5);  
	var AutoNuevo = new auto(Brand[index], model[index], Year[index], Color[index]);  
	console.log(AutoNuevo);  
	}  
	…

* **Luis Alejandro Medina Escobar** (1)

	```
	    var modelo = [0,1,2,3,4,0,1,2,3,4,0,1,2,3,4,0,1,2,3,4,0,1,2,3,4,0,1,2,3,4];
	    var marca = [0,1,2,3,4,0,1,2,3,4,0,1,2,3,4,0,1,2,3,4,0,1,2,3,4,0,1,2,3,4];
	    var anio = [0,1,2,3,4,0,1,2,3,4,0,1,2,3,4,0,1,2,3,4,0,1,2,3,4,0,1,2,3,4];
	    
	    function constructor(marca, modelo, anio){
	        this.marca = marca;
	        this.modelo = modelo;
	        this.anio = anio;
	        
	    }
	    
	    for (var i = 0; i < 30; i++){
	    
	        Auto = new constructor(marca[i],modelo[i],anio[i]);
	        console.log(Auto);
	    
	    }
	    
	```

* **Arturo Linares** (1)

	
	var marca = [“Toyota”,“BMW”,“Lamborghini”,“Ferrari”,“Corvette”];  
	var tipo = [“sport”, “carrera”,“clasico”,“noche”,“Dia”];  
	var annio = [2020, 2018, 2019,2025,2040];
	
	function auto(marca, tipo, annio){  
	this.marca = marca;  
	this.tipo = tipo;  
	this.annio = annio;  
	}
	
	for(var i = 0; i < 30; i++) {  
	var index = Math.floor(Math.random() * 5)  
	var autoNuevo = new auto(marca[index], tipo[index], annio[index]);  
	console.log(autoNuevo);  
	}

* **luisglopez7777** (1)

	```
	    let marca = [ 'Honda', 'Chevrolet', 'Audi', 'BMW', 'Tesla', 'Toyota']
	    let modelo = ['Sport', 'Classic', 'Retro']
	    let año = 2000
	    
	    functionAuto(marca, modelo, año){
	        this.marca = marca,
	        this.modelo = modelo,
	        this.año = año
	    }
	    
	    let n = 0
	    let q = 0
	    for(let i = 0; i < 30; i++){
	        n++
	        q++
	        if(n === 6){
	            n = 0
	        }
	        if( q=== 3){
	            q = 0
	        }
	        let coche = new Auto(marca[n], modelo[q], año++)
	        console.log(coche)
	    }```
	    
	```

* **carlosextra1** (1)

	
	Aquí mi solución!
	``` 
	    function auto(auto,modelo,anio){
	        this.auto = auto;
	        this.modelo = modelo ;
	        this.anio = anio;
	    }
	    let autos = [];
	    let datos = [['Hyundai','Elantra',2020],
	                ['Nissan','Sentra',2021],
	                ['Nissan','Versa',2018],
	                ['Ford','Figo',2009],
	                ['Ford','Fiesta',2012],
	                ['Chevrolet','Aveo',2021],
	                ['Kia','Rio',2022]];
	    let i = 0;
	    datos.forEach((val) => {
	        autos[i] = new auto(val[0],val[1],val[2]);
	        i++;
	    })
	    console.log(autos);
	    
	```

* **miguelgz18** (1)

	```
	    functionauto( modelo, marca, annio ){
	                this.modelo = modelo;
	                this.marca = marca;
	                this.annio = annio;
	            }
	    
	            var listaCarros = [];
	    
	            for( var i = 1; i <= 5 ; i++ ){
	    
	                var modelo = prompt('Escoge un modelo');
	                var marca = prompt('Escoge una marca');
	                var annio = prompt('Escoge un annio del auto');
	    
	                var nuevoAuto = new auto(modelo, marca, annio);
	                listaCarros.push(nuevoAuto);
	    
	            }
	    
	            console.log(listaCarros);```
	    
	```

* **fabio-hernan-mosquera-obando** (1)

	
	en la funcion constructora this es el objeto = auto  
	entonces la marca del auto sera igual al parametro marca asi:  
	this.marca= marca; que es uno de los parametros de la funcion.
	
	asi lo entiendo. si alguien tiene alguna observacion con gusto la aceptare.

	* **rsalamanca** (1)

		
		Si asi como lo planteas efectivamente.

* **Guido Fortunato** (1)

	
	por que en la funcion constructora pone this.marca = marca? cual es el sentido?

	* **Robinson Matias Aguilar Bascuñan** (2)

		
		basicamente, lo que te intenta decir es que
		
		this.marca (es una variable creada por this dentro de la funcion, una variable local)
		
		this.marca = marca (la marca subrayada hace referencia al parametro de la  
		funcion)  
		**entonces :**  
		function auto(marca){  
		this.marca=marca;  
		//aqui estoy diciendo que la marca que se pasara por parametro, se la asignare a  
		la variable creada por this  
		}

	* **richardberna211** (1)

		
		this hace referencia a las propiedades del objeto, en el ejemplo el caso es el siguiente:  
		this.marca = marca // quiere decir que a la propiedad marca del objeto se le asigne el valor que se esta pasando al instanciar el objeto.  
		Para ser mas entendible si cambias el nombre de la variable que se esta pasando **marca** pero selelasigne a la propiedad marca igual funcionará.

	* **rsalamanca** (1)

		
		Por que cuando se instancie la función le van a tener q pasar una marca.  
		Y esa marca que se pasa como parametro directamente se asignara a la variable marca que tienes declarada dentro de la función.

* **Guido Fortunato** (1)

	
	Buenas, una consulta que no tiene que ver con la clase en si.  
	En visual studio code tengo un plugin por defecto que te remarca con un rectangulo las llaves, los parentesis, eso quisiera sacarlo pero nose como!  
	Instale el Bracket Pair Colorizer que te remarca de diferentes colores las llaves, parentesis, pero sigo teniendo ese rectangulo molesto en cada uno de ellos.  
	Gracias!

* **picojohn** (1)

	```
	    functionauto(marca, modelo, annio){
	        this.marca= marca;
	        this.modelo = modelo;
	        this.annio = annio;
	    }
	    
	    var cant = prompt("cuantos carros vas a agregar ");
	    var autos = [];
	    
	    for (var i=0; i<cant; i++){
	        var marca =prompt("ingrese la marca");
	        var modelo = prompt("ingrese el modelo");
	        var annio = prompt("ingresa el año")
	    
	    
	        window["auto_No_"+i] = new auto(marca,modelo,annio);
	        console.log(marca,modelo,annio);
	    
	    }```
	    
	```

* **Ender José Urdaneta Ocando** (1)

	```
	    functionauto(marca,modelo,year){
	        this.marca=marca;
	        this.modelo=modelo;
	        this.year=year;
	    }
	    /* 
	    var autoNuevo = new auto ("chevrolet", "captiva", 2012 );
	    autoNuevo
	    var autoNuevo2 = new auto ("mazda", "cx30", 2020);
	     */
	    var nro_carros=prompt(`Cuantos carros vas a ingresar: `);
	    var autos=[];
	    for (var i=0; i<nro_carros; i++){
	        var marca1 = prompt(`ingrese marca:`);
	        var modelo1 = prompt(`ingrese modelo:`);
	        var year1 = prompt(`ingrese año:`);
	        //creación del objeto con la función
	        var nuevoAuto = new auto(marca1, modelo1, year1);
	        autos.push(nuevoAuto);
	    }
	    autos;
	    
	```

* **Angelo Zambrano** (1)

	
	Reto:  
	![RetoObjetos.PNG](https://static.platzi.com/media/user_upload/RetoObjetos-1a13631e-62ca-4a1a-a1f3-7ee9c822e586.jpg)

	* **Juan Pedraza** (2)

		
		¿Eso ya es typescript?

	* **Angelo Zambrano** (1)

		
		@juan-pedraza Sí!

	* **Juan Pedraza** (2)

		
		aaaahhh bueno… Ya otro nivel.
		
		Gracias por compartir tus avances

	* **rsalamanca** (1)

		
		Vengo de java y es muy parecida la forma de trabajarlo. Gracias por tu aporte amigo empezare a mirar mas sobre typeScript

	* **Angelo Zambrano** (1)

		
		Vos que conoces Java sabes la importancia de tener tipado el código. Gracias por comentar. Saludos!

* **Juan Teixeira** (1)

	```
	    functionauto(marca, modelo, annio){
	        this.marca = marca;
	        this.modelo = modelo;
	        this.annio = annio;
	    }
	    
	    var detallesAutos =[['Abarth', 'Alfa Romeo', 'Aston Martin', 'Audi', 'Bentley',
	        'BMW',	'Cadillac',	'Caterham',	'Chevrolet', 'Citroen'],['Sedan', 'Camioneta', 'Deportivo'],[2018,2019,2020]]
	        
	    functionnuevoCoche(){
	        for(i=0; i< 10; i++){
	            var marca =  detallesAutos[0][Math.floor(Math.random() * detallesAutos[0].length )]
	            var modelo =  detallesAutos[1][Math.floor(Math.random() * detallesAutos[1].length )]
	            var annio =  detallesAutos[2][Math.floor(Math.random() * detallesAutos[2].length )]
	        
	            var autoNuevo = new auto(marca , modelo, annio )
	            console.log(autoNuevo);
	    
	        }
	        
	    }
	    nuevoCoche()
	    
	```

* **pablopazos** (1)

	
	function coche (marca, modelo, ano) {  
	this.marca = marca;  
	this.modelo = modelo;  
	this.ano = ano;  
	}  
	var marcas = [“Toyota”, “Mazda”, “Honda”];  
	var modelosToyota = [“Yaris”, “Corolla”, “Rav4”];  
	var modelosMazda = [“2”, “3”, “6”];  
	var modelosHonda = [“Jazz”, “Civic”, “Accord”];  
	var anos = [“2020”, “2019”, “2018”];
	
	for (let i = 0; i < 30; i++) {  
	var newMarca = marcas[Math.floor(Math.random() * marcas.length)];  
	if (newMarca === “Toyota”) {  
	var newModel = modelosToyota[Math.floor(Math.random() * modelosToyota.length)];  
	} else if (newMarca === “Mazda”) {  
	var newModel = modelosMazda[Math.floor(Math.random() * modelosMazda.length)];  
	} else {  
	var newModel = modelosHonda[Math.floor(Math.random() * modelosHonda.length)];  
	}  
	var newAno = anos[Math.floor(Math.random() * anos.length)];  
	var newCoche = new coche(newMarca, newModel, newAno);  
	console.log(newCoche);  
	}

* **Jaime Agustí** (1)

	
	function auto (marca, modelo, annio) {  
	this.marca = marca;  
	this.modelo = modelo;  
	this.annio = annio;  
	}
	
	var marcasAutos = [“Tesla”, “Seat”, “BMW”];  
	var modelosTesla = [“Model X”, “Model 3”, “Model S”];  
	var modelosSeat = [“Ibiza”, “Leon”, “Ateca”, “Arona”];  
	var modelosBMW = [“Serie 1”, “X3”, “M6”];  
	var annios = [2015, 1016, 2017, 2018, 2019, 2020];  
	var autoList = [];
	
	for (var i = 0; i < 30; i++) {  
	var NewMarca = marcasAutos[Math.floor(Math.random() * marcasAutos.length)];  
	if (NewMarca === “Tesla”) {  
	var NewModelo = modelosTesla[Math.floor(Math.random() * modelosTesla.length)];  
	} else if (NewMarca === “Seat”) {  
	var NewModelo = modelosSeat[Math.floor(Math.random() * modelosSeat.length)];  
	} else {  
	var NewModelo = modelosBMW[Math.floor(Math.random() * modelosBMW.length)];  
	}  
	var NewAnnio = annios[Math.floor(Math.random() * annios.length)];  
	autoList.push (new auto (NewMarca, NewModelo, NewModelo));  
	console.log (`Auto ${NewMarca} ${NewModelo} ${NewAnnio}`);  
	}

* **Jeisson Santiago Cortes Ortiz** (1)

	
	.

* **tito jesús yanac saldaña Yanac Saldaña** (1)

	
	var mod = [“a”,“b”,“c”,“d”];  
	var an = [2001, 2002, 2003, 2004];  
	var mar = [“toyota”, “nissan”, “pedro”, “acme”];
	
	var carrostotales=[];
	
	function auto (modelo, annio, marca){  
	this.modelo= modelo;  
	this.annio= annio;  
	this.marca= marca;  
	}
	
	for (var i=0 ; i<30;i++){  
	var x=Math.round (Math.random()*3);  
	var y=Math.round (Math.random()*3);  
	var z=Math.round (Math.random()*3);
	``` 
	    var nuevoauto = new auto (mod[x], an[y], mar[z]);
	       carrostotales[i] = nuevoauto;
	    
	```
	
	}

* **Jeisson Santiago Cortes Ortiz** (1)

	
	:0

* **José Bryan Aranda Figueroa** (1)

	
	aquí esta mi reto
	``` 
	    <code>
	    var personasArray= []
	    
	    functionpersona(nombre,edad){
	    
	        this.nombre = nombre;
	        this.edad = edad;
	    
	    }
	    
	    
	    var numeroPersonas = prompt('cuantas personas quieres hacer?')
	    if(numeroPersonas>0){
	    for(var i=0;i<numeroPersonas;i++){
	    var nombre = prompt('digite el nombre de la persona ' + i)
	    var edad = parseInt(prompt('digite la edad de la persona '+i))
	    var personita = new persona(nombre,edad)
	    personasArray.push(personita)
	    }
	    }else{alert('no digito numero de personas valido')}
	    console.log(personasArray)
	    
	    
	```

* **vrgrajeda** (1)

	```
	    var listaDeAutos = [];
	    var cantidadDeAutos;
	    var marca, modelo, año;
	    
	    classAuto {
	        constructor(marca, modelo, año) {
	            this.marca = marca;
	            this.modelo = modelo;
	            this.año = año;
	        }
	    }
	    
	    function generarAutos () {
	        cantidadDeAutos = parseInt(prompt('Cuantosautosquieres 																																																									 
	                                       generar: '));
	        for(vari = 0; i < cantidadDeAutos; i++){
	            if (cantidadDeAutos == 1) {
	                marca = prompt(`Cualeslamarcadelauto: `);
	                modelo = prompt(`Cualeselmodelodelauto: `);
	                año = prompt(`Cualeselañodelauto: `);
	                listaDeAutos.push(newAuto(marca, modelo, año));    
	            } else {
	                marca = prompt(`Cualeslamarcadelauto ${i + 1}: `);
	                modelo = prompt(`Cualeselmodelodelauto ${i + 1}: `);
	                año = prompt(`Cualeselañodelauto ${i + 1}: `);
	                listaDeAutos.push(newAuto(marca, modelo, año));
	            }
	        }
	    }
	    
	    generarAutos();
	    console.log(listaDeAutos);
	    
	```

* **Messorid** (1)

	
	const marca = [“Toyota”,“Chery”,“Mazda”,“aveo”,“fiesta”,“chevrolet”]  
	const modelo = [“Modelo 1”,“Modelo 2”, “Modelo X”]  
	const año = [2017,2018,2019]  
	let cantidad = 0;
	
	function auto(marca,modelo,año) {  
	this.marca = marca,  
	this.modelo = modelo,  
	this.año = año  
	}  
	// let auto1 = new auto(marca[0],modelo[0],año[0]);  
	// let auto2 = new auto(marca[1],modelo[1],año[1]);  
	// let auto3 = new auto(marca[2],modelo[2],año[2]);
	
	function numeroRandom(){  
	random = Math.floor(Math.random() * (3 - 0 ));  
	return random  
	}
	
	while(cantidad <= 30){  
	cantidad++  
	console.log(`Vehiculo ${marca[numeroRandom()]} ${modelo[numeroRandom()]} año ${año[numeroRandom()]}`)
	
	}

* **Daniel Cuevas** (1)

	```
	    var marcas = ["Tesla", "Toyota", "Mazda"];
	    var modelos = ["Model 1", "Model 2", "Model 3"];
	    var años = [2018, 2019, 2020];
	    var autos = [];
	    
	    functioncrearAutos(marca, modelo, año)
	    {
	     this.marca = marca;
	     this.modelo = modelo;
	     this.año = año;
	    }
	    
	    for (i = 0; i < 30; i++)
	    {
	      var resultado1 = Math.floor(Math.random() * 3);
	      var resultado2 = Math.floor(Math.random() * 3);
	      var resultado3 = Math.floor(Math.random() * 3);
	      autos.push(new crearAutos(marcas[resultado1],modelos[resultado2],años[resultado3]));
	    }
	    
	    console.log(autos);```
	    
	```

* **ALBERTO JOSE MORALES BOSCAN** (1)

	```
	    functionconcesionario(marca, modelo, annio){
	    	this.marca = marca;
	    	this.modelo = modelo;
	    	this.annio = annio;
	    }
	    //Listado
	    var listaMarcas = ['ford', 'mazda', 'chevrolet', 'voltswagen'];
	    var listaModelo = ['fiesta', 'mazda 3', 'spark', 'gol'];
	    var listaAnnio = ['2010', '2015', '2020', '2018'];
	    
	    var listaAutos = [];
	    
	    //Llenado del array
	    var cant = prompt('Cuantos vehículos deseas introducir?');
	    
	    for (var i = 0; i < cant; i++) {
	    	var random = Math.floor(Math.random() * 3);
	    	
	    	listaAutos.push(new concesionario(listaMarcas[random], listaModelo[random], listaAnnio[random]));
	      	
	    }
	    
	    //mostrar autos
	    for (var auto of listaAutos){
	    	console.log(auto);
	    }
	    
	```

* **Danelia Sanchez Sanchez** (1)

	```
	    functionauto(marca, model, annio) {
	        this.marca = marca;
	        this.model = model;
	        this.annio = annio;
	    }
	    
	    var marcas = ["Tesla", "Toyota", "Audi", "Honda", "Nissan", "Suzuki"];
	    var models = ["Model 1", "Model 2", "Model 3", "Model 4", "Model 5", "Model 6"];
	    var annios = [2015, 2016, 2017, 2018, 2019, 2020];
	    
	    for(var i = 0; i < 30; i++) {
	        var index = Math.floor(Math.random() * 6)
	        var autoNuevo = new auto(marcas[index], models[index], annios[index]);
	        console.log(autoNuevo);
	    }
	    
	```

* **cesaraguilareduardoromero** (1)
![reto2.PNG](https://static.platzi.com/media/user_upload/reto2-bc116193-b3a2-4403-861c-e81c549f3d4a.jpg)

* **Alexis Maximiliano Nieva** (1)

	```
	    functionauto(marca,modelo,annio){
	      this.marca = marca ;
	      this.modelo = modelo;
	      this.annio = annio;
	    }
	    
	    var autos =[];
	    var cantidad = prompt('ingrese la cantidad de autos:');
	    
	    for (var i = 0; i < cantidad; i++) {
	      var marca =prompt('ingrese la marca del auto:');
	      var modelo =prompt('ingrese la modelo del auto:');
	      var annio =prompt('ingrese el año del auto:');
	    
	      var nuevo = new auto(marca,modelo,annio);
	    
	       autos.push(nuevo);
	       console.log("cargado con exito");
	    }```
	    
	```

* **Danilo Josué Huacón Aguirre** (1)

	```
	    functionauto(marca, modelo, ano){
	      
	      this.marca = marca;
	      this.modelo = modelo;
	      this.ano= ano;
	    }
	    // Cuantos autos quieres crear?
	    var n  = 5;
	    var coche  =[] ;
	    for (var i = 0 ; i< n;i++){
	      var brand=""; var model=""; var year=0;
	       brand = prompt("Dime una marca");
	       model = prompt("Dime un modelo");
	       year = prompt("Dime un año");
	      coche[i] = new auto(brand, model, year);
	      
	    }
	    
	```

* **Germán Moreno** (1)
![code2.png](https://static.platzi.com/media/user_upload/code2-8c0d95df-a435-46e6-8e9c-3bc3811d2003.jpg)
	
	¡Excelente práctica!

* **Ines Patricia Contreras Espiritu** (1)
![reto 3.PNG](https://static.platzi.com/media/user_upload/reto%203-126b9418-bb58-4d7a-b5e8-edd4be64b293.jpg)

* **JIMMY STEVE OSMA JEREZ** (1)

	```
	    function auto(marca,modelo,annio){
	        this.marca = marca;
	        this.modelo = modelo;
	        this.annio = annio;
	    }
	    cantidad = prompt("cuantos autos quieres ingresa");
	    
	    for (var i = 0; i < cantidad ; i++){
	    
	        marca = prompt("Cual es la marca del carro?");
	        modelo = prompt("Cual es el modelo del carro?");
	        annio = prompt("Cual es el año del carro?");
	        window["autoNuevo"+i] = new auto(marca,modelo,annio);
	        console.log(marca,modelo,annio);
	    }```
	    
	```

* **luisP** (1)

	
	No era lo q esperaba
	``` 
	    var auto = [];
	    var company = ["Chevy", "Fiat", "Renault", "BMW"];
	    var year = ["2000", "2001", "2002", "2003"];
	    
	    for(auto = 0; auto < 30; auto++)
	    {
	        var company = company[(Math.floor(Math.random() * company.length))];
	        var year = year[(Math.floor(Math.random() * year.length))];
	            console.log("auto " + company + " " + year);
	    
	    }
	    
	```

* **marlonhmp** (1)

	
	Excelente clase.

* **Julian Ignacio Carelli** (1)
![Captura de pantalla \(52\).png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%2852%29-6c7c89b4-5c37-4489-a22e-df591cb7c230.jpg)

* **Christian David Sánchez** (1)

	
	Los objetos también pueden tener métodos .
	
	Los métodos son acciones que se pueden realizar en objetos.
	
	Los métodos se almacenan en propiedades como definiciones de funciones .  
	En una definición de función, se thisrefiere al “propietario” de la función.

* **joaomesa** (1)

	
	Comparto ejercicio propuesto:
	``` 
	    let autoNuevo = [];
	    const marca = ["Tesla", "Toyota", "BMW", "Kia", "Audi", "Suzuki", "Chevrolet", "Ford", "Ferrari", "Mitsubishi"];
	    const modelo = ["Model 3", "Corolla", "i3", "Sportage", "A3", "Vitara", "Aveo", "Mustang", "812", "Outlander"];
	    const annio = [2020, 2020, 2019, 2018, 2020, 2019, 2015, 2018, 2020, 2015];
	    
	    functionauto(marca, modelo, annio) {
	      this.marca = marca;
	      this.modelo = modelo;
	      this.annio = annio;
	    }
	    
	    for (let i = 0; i<30; i++) {
	      autoNuevo[i] = new auto (
	        marca[Math.floor(Math.random() * marca.length)], 
	        modelo[Math.floor(Math.random() * modelo.length)], 
	        annio[Math.floor(Math.random() * annio.length)]
	      );
	    }
	    
	    console.log(autoNuevo);
	    
	```

* **isabellaahc** (1)

	
	Aquí mi ejercicio 😃
	``` 
	    functioncar(brand, model, year) {
	        this.brand = brand,
	        this.model = model,
	        this.year = year
	    }
	    
	    let brands = ['Toyota', 'Nissan', 'Citroen', 'Peugeot', 'Audi', 'Suzuki']
	    let models = ['Palio', 'Suman', 'c3', '3008', 'pulento', 'jimmny']
	    let years = [2010,2011, 2020, 2019, 2021]
	    
	    let autos = []
	    
	    let addCar = (newCar) => { autos.push(newCar)} 
	    
	    while (autos.length < 30) {
	        console.log(`Iteracion número ${autos.length}`)
	        let newCar = new car(brands[Math.floor(Math.random() * brands.length)], models[Math.floor(Math.random() * models.length)], years[Math.floor(Math.random() * years.length)]) 
	        console.log(newCar);
	        addCar(newCar);
	    }
	    
	    
	    console.log(autos.length);
	    
	```

* **Rafael Muñoz Pérez** (1)

	
	const MARCAS = [“Toyota”, “Ford”, “Ferrari”, “VW”, “BMW”, “Mercedez Benz”, “Nissan”];  
	const MODELOS = [“Sentra”, “Focus”, “Diablo”, “Camry”, “Corolla”, “A7”, “Jetta”, “Golf”,“Tacoma”,“Hilux”];  
	var vehiculos = [];  
	function auto(marca, modelo, year){  
	this.marca = marca;  
	this.modelo = modelo;  
	this.year = year;  
	}  
	for (let index = 0; index < 30; index++) {  
	var autoNuevo = new auto();  
	autoNuevo.marca = MARCAS[Math.floor(Math.random() * MARCAS.length)];  
	autoNuevo.modelo = MODELOS[Math.floor(Math.random()*MODELOS.length)];  
	autoNuevo.year = Math.floor(Math.random() * 20) + 2000;  
	vehiculos.push(autoNuevo);  
	}  
	for (const auto of vehiculos) {  
	console.log(auto);  
	}

* **danielbandera** (1)
![autosnuevos.PNG](https://static.platzi.com/media/user_upload/autosnuevos-04b32afd-b5a9-457a-80bf-0c6c2bd02c7f.jpg)

* **wAguilar** (1)

	```
	    var carro ;
	    var total = 30;
	    
	    
	    functionauto (marca, modelo, annio)
	    {
	        this.marca = marca;
	        this.modelo = modelo;
	        this.annio = annio;
	    }
	    
	    for (carro = 0; carro < total; carro++)
	    {
	        var marcaCarro = prompt("marca"); 
	        var modeloCarro = prompt("modelo"); 
	        var annioCarro = prompt("año");
	        var registroAuto = new auto (marcaCarro, modeloCarro,annioCarro);
	        document.write(`Auto ${marcaCarro}${modeloCarro}${annioCarro} <br>`);
	    }
	    
	    
	    
	    
	    
	    
	    
	    
	    
	    
	    
	    ``
	    
	```

* **Bryan Gallo** (1)

	
	Este es mi reto de la Función constructora hasta ahora voy entendiendo todo del curso el profe explica muy bien espero continuar así en los demás cursos de la escuela de JavaScript  
	![Captura de pantalla \(388\).png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%28388%29-44f7f230-b3ad-47ed-adb2-21004c4e5023.jpg)

* **edgar limones lozano** (1)

	```
	    var autos = [];
	    
	    functionauto(marca, modelo, annio){
	        this.marca = marca;
	        this.modelo = modelo;
	        this.annio = annio;
	    }
	    
	    functionmuestraAutos(){
	        for(var auto of autos){
	            console.log(auto);
	        }
	    }
	    
	    functioncrea3Autos(){
	        var i = 0;
	        do{
	            var marca = prompt('Introduce la marca el auto');
	            var modelo = prompt('Introduce el modelo el auto');
	            var annio = prompt('Introduce el año el auto');
	    
	            autos.push(new auto(marca, modelo, annio));
	            i++;
	        }while(i < 3);
	    
	        muestraAutos();
	    
	    }```
	    
	```

* **Derek Samuel Paúl Peña** (1)

	```
	    <code>
	    functioncars(brand, model, year) {
	        this.brand = brand;
	        this.model = model;
	        this.year = year;
	    }
	    
	    for(var i = 0; i < 30; i++) {
	        var respB = prompt('Escribe la marca del carro: ');
	        var respM = prompt('Escribe el modelo del carro: ');
	        var respY = prompt('Escribe el año de producción del carro: ');
	        let x = new cars(respB, respM, respY);
	        console.log(x);
	    }
	    
	```

* **Alejandro Cruzado Rosas** (1)

	```
	    var autos = [];
	    var marca = [];
	    var modelo = [];
	    var annio = [];
	    
	    for (var i = 0; i < 30; i++) {
	        marca[i] = prompt("Ingresa la marca del carro");
	    }
	    
	    for (var i = 0; i < 30; i++) {
	        modelo[i] = prompt("Ingresa el modelo del carro");
	    }
	    for (var i = 0; i < 30; i++) {
	        annio[i] = prompt("Ingresa el año del carro");
	    }
	    
	    function auto(marca, modelo, annio) {
	        this.marca = marca;
	        this.modelo = modelo;
	        this.annio = annio;
	    }
	    
	    for (var i = 0; i < 30; i++) {
	        autos[i] = new auto(marca[i],modelo[i],annio[i]);
	    }
	    
	    for(aut of autos){
	        console.log(aut);
	    }```
	    
	```

* **DevNaftan** (1)

	
	**Reto cumplido**
	``` 
	    // Pregunta el número de autos a ingresar
	    var numeroAutos = prompt("Ingrese el número de autos que va a registrar: ")
	    
	    // Crear los objetos a usar
	    var marcaObject   = [];
	    var modeloObject  = [];
	    var annioObject   = [];
	    
	    // Pregunta y guarda los datos ingresados
	    alert("Ingresa las marcas de los autos");
	    for(i=0; i<numeroAutos; i++) {
	      var marca   = prompt();
	      marcaObject.push(marca);
	    }
	    alert("Ingresa los modelos para los autos");
	    for(i=0; i<numeroAutos; i++) {
	      var modelo   = prompt();
	      modeloObject.push(modelo);
	    }
	    alert("Ingresa los años de los autos");
	    for(i=0; i<numeroAutos; i++) {
	      var annio   = Number(prompt());
	      annioObject.push(annio);
	    }
	    
	    // Función constructora
	    function autos(marca, modelo, annio) {
	      this.marca = marca;
	      this.modelo = modelo;
	      this.annio = annio;
	    }
	    
	    // Crea los objetos usando la función constructora y los almacena en variables automáticas
	    for(i=0; i<numeroAutos; i++) {
	      console.log(window["nuevoAuto" + i] = new autos(marcaObject[i], modeloObject[i], annioObject[i]));
	    }
	    
	```

* **Antonio Rafael González Ferrer** (1)

	
	No estoy seguro si es lo que se pidió pero va 😬
	``` 
	    functionautoMobile(brand, model, year, style)
	            {
	                this.brand = brand
	                this.model = model
	                this.year = year
	                this.style = style
	            }
	    
	            functioncarsCollection(quantity)
	            {
	                var carBrand, carModel, carYear, carStyle
	    
	                var collection = []
	    
	                for(var i = 0; i < quantity; i++)
	                {
	                    carBrand = prompt('Ingrese la marca del carro:')
	                    carModel = prompt('Ingrese el modelo del carro:')
	                    carYear = parseInt(prompt('Ingrese el año del carro'))
	                    carStyle = prompt('Ingrese el tipo de carro')
	    
	                    collection[i] = new autoMobile(carBrand, carModel, carYear, carStyle)
	                }
	    
	                return collection
	            }
	    
	            functioncollectionByBrand(carBrand, quantity)
	            {
	                var carModel, carYear, carStyle
	    
	                var collection = []
	    
	                for(var i = 0; i < quantity; i++)
	                {
	                    carModel = prompt('Ingrese el modelo del carro:')
	                    carYear = parseInt(prompt('Ingrese el año del carro'))
	                    carStyle = prompt('Ingrese el tipo de carro')
	    
	                    collection[i] = new autoMobile(carBrand, carModel, carYear, carStyle)
	                }
	    
	                return collection
	            }
	    
	            functionprintCollection(carCollection)
	            {
	                for(var i = 0; i < carCollection.length; i++)
	                {
	                    console.log(`Información del auto No ${i+1}:`)
	                    console.log(`Marca: ${carCollection[i].brand}`)
	                    console.log(`Modelo: ${carCollection[i].model}`)
	                    console.log(`Año: ${carCollection[i].year}`)
	                    console.log(`Tipo de Auto: ${carCollection[i].style}`)
	                }
	            }
	    
	            functionstartCollection()
	            {
	                var flag = true
	                
	                while(flag)
	                {
	                    var carsBrand
	                    var quantity = parseInt(prompt(`Escriba la cantidad de autos que desea añadir a su colección:`))
	                    if(isNaN(quantity) || quantity < 0)
	                    {
	                        alert('Debe ingresar un número de autos')
	                        flag = true;
	                    }
	                    else
	                    {
	                        carsBrand = prompt('Ingrese la marca de su colección de autos (deje vacío en caso de multi marca)')
	                        if(carsBrand === "" || !isNaN(carsBrand))
	                        {
	                            var newCollection = carsCollection(quantity)
	                            printCollection(newCollection)
	                        }
	                        else
	                        {
	                            var newCollection = collectionByBrand(carsBrand, quantity)
	                            printCollection(newCollection)
	                        }
	                        flag = false
	                    }
	                }
	            }
	    
	            startCollection()
	    
	```

* **stwanga** (1)

	```
	    var arrayMarca = ["Ford","Hyundai","Ferrari"]
	    var arrayModelo = ["Ford-100","Hyundai-100","Ferrari-100"]
	    var arrayAnnio = [1980,2000,2020]
	    
	    functionmiAutoAutomatico(marca, modelo, annio) {
	      this.marca = marca;
	      this.modelo = modelo;
	      this.annio = annio;
	    
	      console.log(`Detalles del auto: ${this.marca}${this.modelo}${this.annio}`);
	    }
	    
	    // nos aseguramos que todos sean de mismo tamaño
	    if (arrayMarca.length == arrayModelo.length && arrayModelo.length == arrayAnnio.length) {
	    
	        for (let index = 0; index < arrayMarca.length; index++) {
	            
	            // const element = array[index];
	            var nuevoAuto = new miAutoAutomatico(arrayMarca[index],arrayModelo[index],arrayAnnio[index]);
	    
	        }
	        
	    }else{
	        console.log ("Valida que el tamaño de los arrays son iguales");
	    }
	    
	```

* **Jhon Alexander Romero Gonzaga** (1)

	```
	    const currentYear = newDate();
	    const maxYear = Number(currentYear.getFullYear());
	    
	    const brands = [
	      "Toyota",
	      "Ford",
	      "Ferrari",
	      "Lamborghini",
	      "Chevrolet",
	      "Hyundai",
	      "Dodge"
	    ]
	    
	    const models = [
	      "Corolla",
	      "Raptor",
	      "Spider 458",
	      "Aventador",
	      "Camaro",
	      "Santa fe",
	      "Challenger"
	    ];
	    
	    const cars = [];
	    
	    functionCar(brand, model, year) {
	      this.brand = brand;
	      this.model = model;
	      this.year = year;
	    }
	    
	    const randomGenerate = (min, max) => {
	      returnMath.round(Math.random() * (max - min) + min);
	    }
	    
	    const switchBrand = model => {
	      switch (model) {
	        case0:
	          return brands[0]
	        case1:
	          return brands[1]
	        case2:
	          return brands[2]
	        case3:
	          return brands[3]
	        case4:
	          return brands[4]
	        case5:
	          return brands[5]
	        case6:
	          return brands[6]
	      }
	    }
	    
	    functiongenerateCars(maxCar) {
	      for (let i = 0; i < maxCar; i++) {
	        const model = randomGenerate(0, models.length - 1);
	        const brand = switchBrand(model);
	        const year = randomGenerate(minYear, maxYear);
	    
	        const makedCar = new Car(brand, models[model], year);
	        cars.push(makedCar);
	      }
	    }
	    
	    generateCars(50);
	    console.log(cars)```
	```

* **jaguarjs** (1)

	```
	    const modelos = ["Mustang","Camaro","Challenger"]
	    const colores = ["negro","blanco","rojo","amarillo","customizado"]
	    let carros = [];
	    
	    while(carros.length < 30){
	        const modelo = alAzar(0,modelos.length-1)
	        constcolor = alAzar(0,colores.length-1)
	        const annio = alAzar(1970,2020)
	    
	        const carroCreado = new crearCarro(modelos[modelo],colores[color],annio)
	        carros.push(carroCreado)
	        console.log(carroCreado)
	    }
	    
	    functionalAzar(minimo,maximo){
	        returnMath.round(Math.random()*(maximo-minimo)+minimo)
	    }
	    
	    functioncrearCarro(modelo,color,annio){
	        this.modelo = modelo;
	        this.color = color;
	        this.annio = annio;
	    }
	    
	```

* **Alejandro Ernesto Vargas Vaca** (1)

	```
	    var marcas_pool     = ["Ford","Hyundai","Honda"];
	    var modelos_pool    = ["Focus","i20","HR-V"];
	    var annios_pool     = [2020,2021,2019] ;
	    
	    functionauto(marca,modelo,annio){
	        this.marca = marca;
	        this.modelos = modelo;
	        this.annio = annio;
	    }
	    
	    var autos = [];
	    
	    for(var i = 0; i < marcas_pool.length; i++){
	        autos.push(new auto(marcas_pool[i],modelos_pool[i],annios_pool[i]));
	    }
	    
	```

* **Joseph Paucar** (1)

	```
	    brand_pool = ["Tesla", "Toyota", "Renault", "Suzuki"]
	    model_pool = ["Model 3", "Caldina", "Sifon", "Grand Nomade"]
	    year_pool = [2017, 2018, 2019, 2020]
	    
	    car_pool = [];
	    
	    functioncar(brand, model, year){
	        this.brand = brand;
	        this.model = model;
	        this.year = year;
	    }
	    
	    for(i=0; i<30; i++){
	        let rand = Math.floor(Math.random() * (4));
	        let rand2 = Math.floor(Math.random() * (4));
	        let rand3 = Math.floor(Math.random() * (4));
	        car_pool[i] = new car(brand_pool[rand], model_pool[rand2], year_pool[rand3]);
	    }
	    
	    console.log(car_pool);```
	    
	```

	* **MARCO ANTONIO FUERTES VASQUEZ** (1)

		
		Solo creando una operacion random (rand) y llamarla de acuerdo al atributo es lo mismo (a menos que en cada atributo tengas diferente lenght??

	* **Joseph Paucar** (1)

		
		Pasa que yo lo probé solo con un rand y me votaba valores iguales por eso opte por poner 3 para que no ocurra, imagino que se puede mejorar el código pero lo trabaje como pude 😛

* **Juan Zavala** (1)

	
	Excelente

* **Andres Felipe Galeano** (1)

	
	Una posible solución:
	``` 
	    var marca = ["Toyota","Chevrolet","Mazda","Masserati","Ford"];
	    var modelo = ["Sedan","Camioneta","Deportivo","qp"];
	    var annio = ["2019","2020","2021","2018"];
	    var newMarca;
	    var newModelo;
	    var newAnnio;
	    var autos = [];
	    
	    functionrandom_arr(x) {
	        let rand_n = x[Math.floor(Math.random() * x.length)];
	        return rand_n;
	    }
	    
	    functionauto(marca, modelo, annio){
	        this.marca = marca;
	        this.modelo = modelo;
	        this.annio = annio;
	    }
	    
	    
	    for (let i = 0; i < 30; i++){
	        let autoNuevo = new auto(newMarca = random_arr(marca),newModelo = random_arr(modelo), newAnnio = random_arr(annio));
	        console.log(autoNuevo);
	        autos.push(autoNuevo);
	    }
	    
	```

* **mr_alex** (1)

	```
	    var marcas=["Tesla", "Ford", "Toyota"];
	    
	    var modelos=["Model A", "Model B"];
	    
	    var anios=[2016, 2017, 2018, 2019, 2020];
	    
	    
	    
	    
	    
	    
	    functioncrearAutos(){
	        
	        var arrayAutos=[];
	        
	                for(var marca of marcas){
	                    for(var modelo of modelos){
	                        for(var anio of anios){
	                            var autoNuevo= new auto(marca, modelo, anio);
	                            arrayAutos.push(autoNuevo);
	                        }
	                    }
	                }
	           
	        var nAutos=arrayAutos.length;
	        console.log(`tengo ${nAutos} autos`);
	        
	        for(var misAutos of arrayAutos){
	            console.log(`${misAutos.marca}${misAutos.modelo}${misAutos.anio}`);
	        }
	        
	        
	    }
	    
	    
	    functionauto(marca, modelo, anio){
	        this.marca=marca;
	        this.modelo=modelo;
	        this.anio=anio;
	    }
	    
	    
	    crearAutos();
	    
	```
	
	![](![Captura.JPG](https://static.platzi.com/media/user_upload/Captura-a6d9fed7-49d6-452e-8412-e83caf8e19a1.jpg)

* **Gabriel Alejandro Delgado Álvarez** (1)

	```
	    for (i = 0; i < 30; i++) {
	        ModelRandom = Math.floor(Math.random() * 4)
	        MarcaRandom = Math.floor(Math.random() * 4)
	        AñoRandom = Math.floor(Math.random() * 4)
	    
	        let autoGenerado = new auto(marcas[MarcaRandom], modelos[ModelRandom], años[AñoRandom] );
	        console.log(autoGenerado);
	    }```
	    
	```

* **Daniel Melchor** (1)

	```
	    var marcas  = ["Bmw", "Audi", "Hyundai", "Nissan", "Toyota"];
	    var modelos = ["Grand", "Q5", "Tucson", "Quest", "Hilux"];
	    var annios  = [2020, 2019, 2018, 2017, 2016];
	    var Listado = [];
	    
	    functionauto(marca, modelo, annio) { 
	        this.marca  =  marca;
	        this.modelo =  modelo;
	        this.annio  =  annio;
	    };
	    
	    for(var i = 0; i < 30; i++){
	        pMarca  = Math.floor(Math.random()*5);
	        pModelo = Math.floor(Math.random()*5);
	        pAnio   = Math.floor(Math.random()*5);
	    
	        temporal = new auto(marcas[pMarca], modelos[pModelo], annios[pAnio]);
	     
	        Listado.push(temporal);
	    }
	    
	    for (const L of Listado) {
	        console.log(`Auto marca -> ${L.marca} modelo -> ${L.modelo} -> Año ${L.annio}`);
	    }```
	    
	```

* **Diego Fernando Rojas Quintero** (1)

	
	Reto superado
	
	![Captura.PNG](https://static.platzi.com/media/user_upload/Captura-b49065c9-f1ec-48a7-ad94-8f6234e64db0.jpg)

* **yeseniamosqueragil** (1)

	```
	    let arrayMarcas = ['Mazda','Renault','Chevrolet','Dodge','Citroen','Peugeot','BMW','Mercedez Benz'];
	    functionautos (marca, modelo, puertas) {
	        this.marca = marca,
	        this.modelo = modelo,
	        this.puertas = puertas
	    }
	    for (i=1 ; i<=30 ; i++){
	    	let randomModelo = Math.floor(Math.random() * (2020 - 1999) + 1999);
	    	let randomPuerta = Math.floor(Math.random() * (4 - 1) + 2);
	    	let randomMarca = arrayMarcas[Math.floor(Math.random() * 7)];
	    
	    	var auto = new autos(randomMarca,randomModelo,randomPuerta);
	    	console.log(auto);
	    }
	    
	```

* **eocas98** (1)

	
	Dejo mi solución
	``` 
	    let autoModelo = [
	        ["Toyota", "Corolla"],
	        ["Audi", "A3"],
	        ["Mitsubishi", "Lancer"],
	        ["Hyundai", "Elantra"],
	        ["Nissan", "Sentra"],
	        ["Audi", "Q3"],
	        ["Mitsubishi", "Outlander"],
	        ["Toyota", "RAV4"],
	        ["Tesla", "Model S"],
	        ["Subaru", "Legacy"]
	    ];
	    
	    let listaAutos = [];
	    let yearRandomAuto;
	    let autoRandom;
	    
	    functionauto(marca, modelo, year) {
	        this.marca = marca;
	        this.modelo = modelo;
	        this.year = year;
	    }
	    
	    for (let  i = 0; i < 30; i++) {
	        yearRandomAuto = Math.floor(Math.random() * (2021 - 2016) + 2016);
	        autoRandom = autoModelo[Math.floor(Math.random() * 10)];
	        autosTemp = new auto(autoRandom[0], autoRandom[1], yearRandomAuto);
	        listaAutos.push(autosTemp);
	    }
	    
	    listaAutos;
	    
	```

* **jee4nc1** (1)

	
	Este es mi codigo
	``` 
	    functionmakeAutos(marca,modelo,annio) {
	        this.marca = marca;
	        this.modelo = modelo;
	        this.annio = annio;
	    }
	    
	    for (var i = 0; i<30; i++) {
	        var auto = new makeAutos(`Tesla ${i}`,`Modelo ${i}`, `Año 2020`);
	        console.log(`Hola, este auto es de Marca ${auto.marca} y modelo ${auto.modelo} del ${auto.annio}`);
	    }
	    
	```

* **Almu_timkerbell** (1)

	```
	    var plato = ["arrozKimchi", "kimchiJeon", "sobaNoodles", "udon"];
	        var precio = ["£4.5", "£5.15", "£6", "£5.5"];
	        var rate = ["9", "9.5", "8.5", "8"];
	        
	        functionmenu (plato, precio, rate){
	            this.plato = plato;
	            this.precio = precio;
	            this.rate = rate;
	        }
	    
	        for (i = 0;  plato.length > i; i++){
	            var carta = new menu (plato[i],precio[i],rate[i]);
	            console.log(carta)
	        }```
	    
	```

* **Daniel Felipe Merchan Fuquen** (1)

	```
	    functionauto(marca, modelo, annio) {
	          this.marca = marca
	          this.modelo = modelo
	          this.annio = annio
	        }
	    
	        let carros = []
	        const produccionDeCarros = 30
	        for (var i = 0; i < produccionDeCarros; i++) {
	          let modelo = 2020 + i
	          var nuevoAuto = new auto ('Tesla', `Model ${i}`, modelo)
	          carros.push(nuevoAuto)
	          console.log(`Este el es nuevo auto: ${carros[i]['marca']}${carros[i]['modelo']}${carros[i]['annio']}`)
	        }
	    
	```

* **Estiventh Leonardo Neira Aldana** (1)

	```
	    functioncontructora (modelo, annio, precio) {
	        this.modelo = modelo,
	        this.annio = annio,
	        this.precio = precio
	    }
	    
	    Array = []
	    
	    for (let i = 0; i < 30; i++) {
	        var carro = new contructora ("Tesla" + i, 2020 + i, 30000);
	        Array.push(carro)
	        console.log(Array[i])
	    }```
	    
	```

* **luismoncada558** (1)

	```
	    //FUNCION CONSTRUCTORA
	    functionautosTemplate(car, model, year) {
	      this.car = car;
	      this.model = model;
	      this.year = year;
	    }
	    
	    // LISTA DE AUTO
	    letlist = [];
	    
	    //CANTIDAD DE AUTOS
	    let numberCars = 30;
	    
	    //LOOP
	    for (let i = 0; i <= numberCars; i++) {
	      let auto = new autosTemplate(`Auto ${i}`, `Modelo ${i}`, 2020);
	      list.push(auto);
	    }
	    
	    console.log(list);
	    
	    
	```

* **dariusv** (1)

	
	¿Alguien me podría explicar cual es el error en mi código?, intento ejecutarlo en la consola del navegador pero no hace nada  
	var carros= [];
	
	function carro(marca, modelo, annio){  
	this.marca = marca;  
	this.modelo = modelo;  
	this.annio = annio;  
	}
	
	for(var i = 1; i >= 30; i++){  
	var marcaNueva = "marca " \+ i;  
	var modeloNuevo = "modelo " \+ i;  
	var annioNuevo = "annio " \+ i;  
	var carroNuevo = new carro(marcaNueva, modeloNuevo, annioNuevo);  
	carros.push(carroNuevo);  
	}
	
	console.log(carros);

	* **jaimesan1231** (1)

		
		el problema esta en el for(var i = 1; i >= 30; i++) ese i >= 30 deberia ser i <= 30

* **hidalgolopezdaniel** (1)

	
	Les comparto otra forma de resolverlo con menos código que el ejercicio que publiqué hace unas horas:
	``` 
	    // CONSTRUCTOR
	    function grupo(nombre, genero, annio) {
	        this.nombre = nombre;
	        this.genero = genero;
	        this.annio = annio;
	        
	    nuevoGrupo = (nombre, genero, annio) => {
	        var nuevoGrupo = new grupo(nombre, genero, annio);
	        return (console.table(nuevoGrupo));
	    }
	    
	    nuevoGrupo("Anathema", "Post Rock", 1990);
	    nuevoGrupo("Tool", "Metal Progresivo", 1999);
	    nuevoGrupo("Cult of Luna", "Sludge Metal", 1998);
	    nuevoGrupo("Pixies", "Rock Alternativo", 1986);
	    nuevoGrupo("Intronaut", "Metal Progresivo", 1994);
	    nuevoGrupo("Opeth", "Death Metal Progresivo", 1991);```
	    
	```

* **hidalgolopezdaniel** (1)

	
	**Les comparto mi solución** \- Creo un Array vacío y por medio de una función agrego más Items.
	
	Al final me di cuenta que no necesite usar ningún ciclo. Voy a intentar una segunda solución usando algún ciclo.
	
	![QjKa8n5.png](https://static.platzi.com/media/user_upload/QjKa8n5-9c477ecf-ffdf-4cb2-aadf-db61e8de436e.jpg)
	``` 
	    // CONSTRUCTOR
	    functiongrupo(nombre, genero, annio) {
	        this.nombre = nombre;
	        this.genero = genero;
	        this.annio = annio;
	    }
	    
	    //Guardo los grupos que se van generando
	    const nuevosGrupos = [];
	    
	    //Se generan los nuevos grupos y se agregan al Array
	    functionagregarGrupo(nom, gen, ann) {
	        let nuevoGrupo = new grupo(nom, gen, ann);
	        nuevosGrupos.push(nuevoGrupo);
	    }
	    
	    //Aquí es donde agrego los grupos nuevos
	    agregarGrupo("Anathema", "Post Rock", 1990);
	    agregarGrupo("Tool", "Metal Progresivo", 1999);
	    agregarGrupo("Cult of Luna", "Sludge Metal", 1998);
	    agregarGrupo("Pixies", "Rock Alternativo", 1986);
	    agregarGrupo("Intronaut", "Metal Progresivo", 1994);
	    agregarGrupo("Opeth", "Death Metal Progresivo", 1991);
	    
	    //LLamo en Consola a los grupos generados
	    console.table(nuevosGrupos);```
	    
	```

* **Orlax** (1)

	
	Una solución :
	``` 
	    //función constructora
	    functionauto(marca, modelo, anio){
	        this.marca = marca;
	        this.modelo = modelo;
	        this.anio = anio;
	      }
	    
	    //declarar un array vacio
	      var autos = [];
	    
	    // crear nuevos objetos con la función constructora
	      for(i= 0; i<30; i++){
	        var aut =new auto("Toyota"+i, "Modelo" + i, 1990 + i);
	        autos.push(aut);
	      }
	      
	    //mostrar el array 
	      for(i= 0; i<30; i++){
	       console.log(`Marca: ${autos[i].marca} Modelo : ${autos[i].modelo} Año ${autos[i].anio}`) 
	      }
	    
	    
	```

* **Andrés Campuzano Garzón** (1)

	
	Reto:
	``` 
	    var listaCarros = [];
	    console.log(listaCarros);
	    
	    
	    functionauto(marca, modelo, year) {
	        this.marca = marca;
	        this.modelo = modelo;
	        this.year= year;
	    }
	    
	    for (let i = 1; i <= 30; i++) {
	        var autoNuevo = listaCarros.push(new auto('Tesla' + ' ' + [i], 'Model 3', (2020 + i)));
	    }
	    
	```

* **Alexei Alvarez** (1)

	```
	    let name = ["toyota", "subaru", "audi"];
	    let modelo = ["sport", "corrolla", "normal"];
	    let marca = ["toyota", "audi", "alfa"];
	    classmyCar{
	      constructor(name, modelo, marca) {
	        this.name = name;
	        this.modelo = modelo;
	        this.marca = marca;
	      }
	    }
	    
	    for (let i = 0; i < name.length && i < modelo.length && i < marca.length; i++) {
	      let operador = new myCar(name[i], modelo[i], marca[i]);
	      console.log(operador);
	    }
	    
	```
	
	este es mi aporte, que tal esta

	* **HENRY DSANTIAGO** (1)

		
		La condición del FOR está sobre explicada, no son necesarias tantas condiciones porque los 3 arrays poseen los mismos elementos. Bastaría con:
		``` 
		    for(let i = 0; i <name.length; i++)
		    
		```

	* **Alexei Alvarez** (0)

		
		Pero si fueran datos diferentes. Eso lo hice a la carrera.
		
		Por ejemplo año de lanzamiento.  
		Y precio
		
		Debería de hacerlo como lo hice o hay alguna otra forma.?

	* **HENRY DSANTIAGO** (1)

		
		Como lo hiciste está muy bien, no te enfoques en esas cosas por ahora, dedícate a aprender más del lenguaje, que tu lógica es muy buena.

* **Alfonso Luis Arrieta Hernández** (1)

	
	Aquí mi reto funcional.
	``` 
	    functionvehiculo (marca, modelo, annio){
	        this.marca=marca;
	        this.modelo=modelo;
	        this.annio=annio;
	    }
	    
	    for(let i= 0; i<4; i++){
	        let marca = prompt("Marca del automovil");
	        let modelo = prompt("Modelo del automovil");
	        let annio = prompt("año del automovil");
	    
	        const vehiculoNuevo = new vehiculo (marca, modelo, annio);
	        console.log(vehiculoNuevo);
	    }```
	    
	    
	```

* **Ronal Roberto Choque Copa** (1)
![udtt.png](https://static.platzi.com/media/user_upload/udtt-c5b7b1e1-6869-47ac-a7fe-cbdf93d0c3db.jpg)

* **Marcos Vargas** (1)
buenas noches, tengo una duda sobre la funcion constructora, es lo mismo que usar clases? que diferencia hay? cual es recomendable usar?

	* **Robinson Matias Aguilar Bascuñan** (1)

		
		claro puede ser lo mismo, ya que con las clases tu creas una funcion constructora en base a las variables de la clase, y tu clase pasaria a ser tu objeto, y es la que mas sirve, ya que mas adelante empezaras a ocupar patrones de diseño, y en el modelo MVC te servira
		
		lo que el muestra aqui es un ejemplo constructor con un objeto simple

* **Ariel Luna** (1)
Consulta:Si la funcion construcntora que se crea con la palabra reservada “new” crea una instancia de un objeto. Porque este objeto no he...

	* **Fernando Alejandro Yerena Ramos** (1)

		
		Espero explicarlo de la mejor manera. 😅
		
		<h3>Bases</h3>
		
		En JavaScript, internamente, casi todo es un objeto. [Las funciones son un tipo de objeto especial](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Function) y como cualquier objeto tiene métodos y atributos.
		
		Si vamos al inspector, creamos una función y la mandamos a llamar, pero sin los paréntesis, podremos ver su estructura.
		
		![](https://i.imgur.com/tTlSElg.png)
		
		Como ves tiene sus propios atributos. [<prototype> ](https://developer.mozilla.org/es/docs/Web/JavaScript/Herencia_y_la_cadena_de_protipos)es importante, podríamos decir que es quién le da la estructura de una función.
		
		<h3>Explicación</h3>
		
		Tomando en cuenta que casi todo en JavaScript es un objeto y que las funciones no son la excepción, veamos lo que sucede al usar **new**.
		
		Es verdad que cuando usamos `new`, este crea una instancia del objeto, pero ¿qué objeto?. En este caso, la instancia no es de **miAuto** ; es del **objeto Función** que almacenas en el atributo `constructor`. ¿Cómo comprobamos esto? Vamos al inspector y hagamos lo mismo que con `saludar()`
		
		Esto es lo que muestra:  
		![](https://i.imgur.com/NtKQFIz.png)
		
		Si te fijas despues de llamar a `Tesla` nos dice que tomo como base el objeto con el nombre constructor. Para comprobar que no es un atributo interno cambiemos el nombre de `constructor` por `nuevoAuto`
		
		Esto es lo que muestra:  
		![](https://i.imgur.com/1iMHWdf.png)
		
		Nos dice que el objeto del que está instanciando se llama nuevoAuto.
		
		<h3>Solución</h3>
		
		Ahora surge una pregunta, ¿por qué funciona si esa función anónima no tiene los atributos marca, modelo y año?
		
		Primero, [cuando usamos `new` el contexto de `this` cambia](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Operadores/new#Descripci%C3%B3n); deja de ser miAuto y pasa a ser el de la función anónima, almacenada en atributo `constructor`.
		
		Segundo, en este caso si no existe el atributo, cuando se ejecuta el constructor se va a crear. Es como si dijeramos:
		
		> De this objeto (llamado constructor) reserva un espacio en memoria llamado “marca” y en él, almacena lo que recibas como argumento en el parámetro marca.
		
		  * 
		
		
		> De this objeto (llamado constructor) reserva un espacio en memoria llamado “modelo” y en él, almacena lo que recibas como argumento en el parámetro modelo.
		
		  * 
		
		
		> De this objeto (llamado constructor) reserva un espacio en memoria llamado “año” y en él, almacena lo que recibas como argumento en el parámetro año.
		
		Entonces para que las próximas instancias tengan los métodos que tenías en `miAuto` tendrías que seguir esa misma lógica
		``` 
		    	this.detalleDelAuto = function(){
		    		console.log(`Auto ${this.modelo}${this.año}`)
		    	}
		    
		```
		
		Resultado:
		
		![](https://i.imgur.com/DoRQ1jU.png)

* **wlm.morant** (1)
var marcas = ['Tesla','Nikola'] var modelos = ['Modelo S','Modelo E','Modelo X'] var annio = 2020 var indexMarca = 0 var indexMode...

* **Almu_timkerbell** (1)
No entiendo muy bien qué hay que conseguir con el ejercicio. El ciclo “for”, ¿qué objetivo tiene? Al final del día, para crear un nuevo o...

	* **Diego Alexander Forero Higuera (Platzi)** (2)

		
		Hola, el ejercicio es que tengas por ejemplo un json con los datos de los 30 autos y con un ciclo for recorrer el json y crear una instancia de auto por cada elemento en el json.

# Métodos de Arrays

## 0190. Métodos de recorridos de Arrays

### Descripción:


### Comentarios:

* **axlina90** (9)

	
	 **.filter** : nos permite filtrar solo los elementos que deseamos (según ciertos criterios) y devolverlos en un nuevo array.  
	**.map** : crea un nuevo array con los resultados de la llamada a la función indicada aplicados a cada uno de sus elementos.

* **hidalgolopezdaniel** (7)

	
	Descubrí que existe esta pag: <https://jsconsole.com/>

* **Miguel Sequeiros Arapa** (6)

	
	Hay un montón de métodos útiles que harán vuestra vida más sencilla y que vuestro código sea más eficiente!!!
	
	chequéenlos en :  
	<https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array>

* **dariusv** (3)

	
	¿por que en la función del método .map() puedo escribir como parámetro “articulo” o “articulos” y obtengo el mismo resultado?  
	var nombreArticulos = articulos.map(function(articulo){  
	return articulo.nombre;  
	});
	
	var nombreArticulos = articulos.map(function(articulos){  
	return articulos.nombre;  
	});

	* **Alvaro Garracini** (7)

		
		Hola dariusv!
		
		Es porque el parámetro de la función es solamente un nombre con el cual se recorrerá el array.
		
		Puedes ponerle ‘pepito’ si quieres y funcionará, pero es una buena práctica usar nombres que hagan referencia con lo que se está trabajando.
		
		En este caso se usa ‘Articulos’ en plural para el array, porque son muchos. Y en el parámetro se usa ‘Articulo’ en singular porque es un solo artículo del array. El map() irá articulo por artículo recorriendo el array.
		
		Espero me haya explicado.
		
		Saludos 😃

* **Daniel .** (2)

	```
	    var autos = ['Audi','BMW','Chevrolet','Ford'];
	    var objetoAutos = [];
	    var modelos = [
	      ['A5','A3','A4','A6','S3','Q5','Q3','Q2','A1','TTS'],
	      ['Serie 6','Serie 7','Z4','M6','Serie 1','Serie 3','Serie 5','Serie 8','Serie 4','Serie 2'],
	      ['Alto','Astra','Bel Air','Camaro','Aveo','Cavalier','Celebrity','Citation','Corsa','Chevy'],
	      ['Fusion','Crown','Victoria','Falcon','Festiva','Fiesta','Focus','Granada','Laser','Mustang']
	    ];
	    
	    functionauto(marca,modelo,anio){
	      this.marca = marca;
	      this.modelo = modelo;
	      this.anio = anio;
	    }
	    
	    functiongenerarAuto(){
	      for(var i = 0; i < autos.length; i++){
	        for(var j = 0; j < modelos[i].length; j++) {
	          var autoObj = new auto(autos[i],modelos[i][j],2020);
	          objetoAutos.push(autoObj);
	          console.log(autoObj);
	        }
	      }
	    }```
	    
	```

* **Jhon Alexander Romero Gonzaga** (2)

	```
	    const articulos = [
	      { nombre: 'Bici', costo: 800000 },
	      { nombre: 'Tv', costo: 2000000 },
	      { nombre: 'Radio', costo: 350000 },
	      { nombre: 'Movil', costo: 3000000 },
	      { nombre: 'Cuaderno', costo: 50000 },
	      { nombre: 'PC', costo: 1900000 },
	      { nombre: 'Mouse', costo: 30000 },
	      { nombre: 'Escoba', costo: 10000 }
	    ];
	    
	    let articulosFitrados = articulos.filter( ({costo}) => costo < 500000 );
	    console.log(articulosFitrados);
	    
	    let nombreFitrados = articulos.map( ({nombre}) => nombre);
	    console.log(nombreFitrados);
	    
	```

* **yeseniamosqueragil** (2)

	```
	    var articulos = [
	    	{nombre:'Bici',costo:800000},
	    	{nombre:'Tv',costo:2000000},
	    	{nombre:'Radio',costo:350000},
	    	{nombre:'Movil',costo:3000000},
	    	{nombre:'Cuaderno',costo:50000},
	    	{nombre:'PC',costo:1900000},
	    	{nombre:'Mouse',costo:30000},
	    	{nombre:'Escoba',costo:10000}
	    ];
	    var filtraArticulos = articulosComprados.filter(function(articulo){
	        return articulo.costo <= 500000;
	    });
	    var mapearArticulos = articulosComprados.map(function(articulo){
	        return articulo.nombre;
	    });
	    var mapeaFiltro = filtraArticulos.map(function(articulo){
	        return articulo.nombre;
	    });
	    console.log(`Los articulos comprados son ${mapearArticulos} y los que tienen un valor menor a 500 mil son ${mapeaFiltro}.`);
	    
	```

	* **all_nexus** (1)

		
		cordial saludo, Yesenia tienes un error en tu código, debes iterar articulos, no articulosComprados, esto te generar un error articulosComprados is not define

* **Javier Armando Vargas Vega** (2)

	
	Esas funciones map y filter se ven muy poderosas.

* **Laurapregonero** (1)

	
	Esta Clase fue muy interesante por que el profe explico estos dos Métodos de una forma muy sencilla.
	
	FILTER(): Nos ayuda a filtar cosas especificas de este array.  
	MAP() : Nos ayuda a mapear el contenido del array y nos trae lo que necesitamos.

* **platzerito080420202** (1)

	
	El ejemplo es como un buscador.

* **eduvra** (1)

	
	Super bien explicado, Diego!

* **garciafran** (1)

	
	Muy importantes los metodos asociados a los array.
	``` 
	    //busqueda mediante filter
	    
	    var articulos = [
	        { nombre: "Bici", costo: 3000 },
	        { nombre: "tv", costo: 2500 },
	        { nombre: "libro", costo: 320 },
	        { nombre: "celular", costo: 20000 },
	        { nombre: "laptop", costo: 2500 },
	        { nombre: "teclado", costo: 500 },
	        { nombre: "audifonos", costo: 1700 }
	    ];
	    
	    var articulosFiltrados = articulos.filter(function(articulo) {
	        return articulo.costo <= 500
	    });
	    
	    articulosFiltrados
	    
	    //busqueda mediante map
	    var articulos = [
	        { nombre: "Bici", costo: 3000 },
	        { nombre: "tv", costo: 2500 },
	        { nombre: "libro", costo: 320 },
	        { nombre: "celular", costo: 20000 },
	        { nombre: "laptop", costo: 2500 },
	        { nombre: "teclado", costo: 500 },
	        { nombre: "audifonos", costo: 1700 }
	    ];
	    
	    var nombreArticulos = articulos.map(function(articulo){
	        return articulo.nombre
	    })
	    
	    nombreArticulos
	    
	    
	```

	* **platzerito080420202** (1)

		
		ajjjajajjja

* **carlosextra1** (1)

	
	Estos métodos son esenciales en JS, y no importa el framework, librería que estés usando. Estos metodos siempre siempre los vas a usar!!

* **picojohn** (1)

	
	buena clase

* **Beto Cortés** (1)

	```
	    var autos = ["Audi", "Tesla", "Nissan"];
	    var objetosCarrazos = [];
	    functionCarrazos(marca, modelo, gama){
	        this.marca = marca;
	        this,annio = annio;
	        this.modelo = modelo;
	        this.gama = gama;
	    }
	    
	    var modelos = [
	        ["A1", "A2", "A3", "A4"], ["Model 1", "Model 2", "Model 3", "Model X"],
	                  ["Platina", "pointer", "Tsuru", "Versa"]
	     ] ;
	    
	    var gamas = ["Baja", "Media", "Media premium", "Alta"]; 
	    
	    functiongenerarAutos(){
	        for(var i = 0; i>Carrazos.length;i++){
	            for(var j = 0; j > modelos[i].length;j++){
	    
	                var mostrarCarrazo = new    Carrazos(autos[i], modelos[i][j]; gamas[i]);
	                objetosCarrazos.push(mostrarCarrazo);
	                console.log(mostrarCarrazo);
	            }
	        }
	    }```
	    No sé si funcione
	    
	    
	```

	* **ag94e** (1)

		```
		    var autos = ["Audi", "Tesla", "Nissan"];
		    var objetosCarrazos = [];
		    functionCarrazos(marca, modelo, gama){
		        this.marca = marca;
		        this.modelo = modelo;
		        this.gama = gama;
		    }
		    
		    var modelos = [
		        ["A1", "A2", "A3", "A4"], ["Model 1", "Model 2", "Model 3", "Model X"],
		                  ["Platina", "pointer", "Tsuru", "Versa"]
		     ] ;
		    
		    var gamas = ["Baja", "Media", "Media premium", "Alta"]; 
		    
		    functiongenerarAutos(){
		        for(var i = 0; i<Carrazos.length;i++){
		            for(var j = 0; j < modelos[i].length;j++){
		                var mostrarCarrazo = new Carrazos(autos[i], modelos[i][j], gamas[i]);
		                objetosCarrazos.push(mostrarCarrazo);
		                console.log(mostrarCarrazo);
		            }
		        }
		    }
		    generarAutos();
		    
		```
		
		Solo cuida la sintaxis cuando generes el nuevo objeto, y en los for los operadores comparativos estaban al revés, si funciona! saludos. 😃

* **cesaraguilareduardoromero** (1)

	
	estos metodos de recorridos, son de mucha ayuda en proyectos avanzados

* **Javier Andres Gamboa Duarte** (1)

	
	super importantes estos métodos

* **Germán Moreno** (1)

	
	Entendido.

* **Germán González** (1)

	
	Ententidoooo

* **marlonhmp** (1)

	
	Entendido.

* **Christian David Sánchez** (1)

	
	 **Map** devuelve una nueva matriz de elementos donde ha aplicado alguna función en el elemento para que cambie el elemento original (normalmente). mientras que **Filter** devuelve una nueva matriz de los elementos de la matriz original (sin cambios en los valores originales).

* **Juan Zavala** (1)

	
	Excelente

* **Eleazar Carreón Álvarez** (1)

	```
	    const productos = [
	      { nombre: 'sabritas', precio: 10 },
	      { nombre: 'chetos', precio: 8 },
	      { nombre: 'coca', precio: 14 },
	    ];
	    
	    const productoMapeado = ({ nombre }) => {
	      nombre = 'barcel';
	      return nombre;
	    };
	    
	    const productosMapeados = productos.map(productoMapeado);
	    console.log(productosMapeados);
	    
	```

* **Martin L.** (1)

	
	cual es la diferencia entre map y filter?

	* **LinusToolbar** (6)

		
		con el prototipo de Map, modificas los elementos, mientras que con Filter, filtras o eliminas los elementos. Se aplicará o no según el criterio que vos desees

	* **Jair Israel Avilés Eusebio** (2)

		
		Complementandop el comentario de @LinusToolbar map regresa en un nuevo arreglo los elementos modificados manteniendo inmutable el arreglo original intacto.

* **Juan Agustín Spinello** (1)

	
	Estas funciones aplicadas a arrays son muy usadas en el día a día.

* **braulioondoedu** (1)

	
	muy bueno

* **Daniel Carmona** (1)

	
	Esto si no lo conocia

* **ironcap** (1)
¿Para qué usaría un MAP? porque incluso como lo veo, puedo regresar todo el objeto completo de cada iteración.

	* **Juan David Castro (Platzi)** (3)

		
		El método **`.map`** en JavaScript nos ayuda a crear un nuevo array a partir de uno anterior. Es muy útil cuando queremos añadir nuevas propiedades o simplemente recorrer el arreglo y dar un resultado diferente dependiendo de los valores de cada elemento del array.
		
		También existen los métodos **`.filter`** , **`find`** o **`.reduce`** que son algo así como variaciones de **.map** con testosteronas. Nos ayudan a conseguir resultados más específicos (como filtrar o encontrar el primer elemento que cumpla una condición).
		
		También existe el método **`.foreach`**. Es muy parecido a **`.map`**. La diferencia es que no crea un nuevo arreglo, sino que siempre modifica el array inicial.
		
		Te recomiendo ver la clase nuevamente. Y también puedes leer estos tutoriales:
		
		  * <https://codeburst.io/javascript-map-vs-foreach-f38111822c0f>
		  * [https://medium.com/@xadrijo/explorando-la-función-map-en-javascript-c04c42773fb6](https://medium.com/@xadrijo/explorando-la-funci%C3%B3n-map-en-javascript-c04c42773fb6)
		  * <https://medium.com/poka-techblog/simplify-your-javascript-use-map-reduce-and-filter-bd02c593cc2d>
		
		

## 0200. Recorriendo Arrays con .find(), .forEach() y .some()

### Descripción:


### Links:

* [Array - JavaScript | MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)

### Comentarios:

* **Diego Camino** (9)

	
	Por si a alguien le quedó alguna duda con respecto a la diferencia entre find y filter:
	
	El método find () devuelve el primer valor que coincide de la colección. Una vez que coincida con el valor en los resultados, no verificará los valores restantes en la colección de matriz.
	
	El método filter () devuelve los valores coincidentes en una matriz de la colección. Verificará todos los valores de la colección y devolverá los valores coincidentes en una matriz.

* **jaguarjs** (6)

	
	Esta pregunta me la hicieron en una entrevista:  
	¿Cual es la diferencia entre find y filter ?
	
	filter retorna todas las coincidencias y find retorna solo la primer coincidencia

	* **Gabriel De Andrade (Platzi)** (2)

		
		Como añadido, las documentaciones en español: [find()](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array/find), [filter()](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array/filter)

* **EddJoy** (5)

	```
	    var articulos = [
	        { nombre: "Bici", costo: 3000 },
	        { nombre: "TV", costo: 2500 },
	        { nombre: "Libro", costo: 320 },
	        { nombre: "Celular", costo: 10000 },
	        { nombre: "Laptop", costo: 20000 },
	        { nombre: "Teclado", costo: 500 },
	        { nombre: "Audifonos", costo: 1700 },
	    ];
	    
	    //filter Genera un nuevo array
	    var articulosFiltrados = articulos.filter(function(articulo){
	        return articulo.costo <= 500; //articulos con precio menor a 500 pesos
	    });
	    
	    //map Ayuda a mapear ciertos elementos de los articulos, es necesario generar nuevo array
	    var nombreArticulos = articulos.map(function(articulo){
	        return articulo.nombre;
	    });
	    
	    //find Ayuda a encontrar algo dentro del array articulos
	    var encuentraArticulo = articulos.find(function(articulo){
	        return articulo.nombre === "Laptop";
	    });
	    
	    //forEach No es necesario generar nuevo array, se utiliza para realizar un recorrido de un array principal
	    articulos.forEach(function(articulo){
	        console.log(articulo.nombre);
	    });
	    
	    //some Se genera nuevo array, regresa un condición en Boolean
	    var articulosBaratos = articulos.some(function(articulo){
	        return articulo.costo <= 700;
	    });```
	    
	```

* **Christian David Sánchez** (4)

	
	  * El método **forEach()** llama a una función (una función de devolución de llamada) una vez para cada elemento de la matriz.
	
	  * El método **map()** crea una nueva matriz al realizar una función en cada elemento de la matriz.
	
	  * El método filter() crea una nueva matriz con elementos de matriz que pasa una prueba.
	
	  * El método reduce() ejecuta una función en cada elemento de la matriz para producir (reducirlo) un solo valor.
	
	
	

* **Manuel Rivera** (3)

	
	Algunos métodos son muy similares, aunque son exclusivamente para una ocasión especifica

* **axlina90** (3)

	
	 **.find** : devuelve el valor del primer elemento del array que cumple la función de prueba proporcionada. En cualquier otro caso se devuelve undefined.  
	**.forEach** : ejecuta la función indicada una vez por cada elemento del array.  
	**.some** : comprueba si al menos un elemento del array cumple con la condición implementada por la función proporcionada.

* **carlosextra1** (2)

	
	some retorna true o false. Dependiendo si se cumple la validación ejecutada.

* **Jhon Alexander Romero Gonzaga** (2)

	```
	    const articulos = [
	      { nombre: 'Bici', costo: 800000 },
	      { nombre: 'Tv', costo: 2000000 },
	      { nombre: 'Radio', costo: 350000 },
	      { nombre: 'Movil', costo: 3000000 },
	      { nombre: 'Cuaderno', costo: 50000 },
	      { nombre: 'PC', costo: 1900000 },
	      { nombre: 'Mouse', costo: 30000 },
	      { nombre: 'Escoba', costo: 10000 }
	    ];
	    
	    let articulosFitrados = articulos.filter( ( {costo} ) => costo < 500000 ); // filtra todos los valores semejantes
	    console.log(articulosFitrados);
	    
	    let nombreFitrados = articulos.map( ( {nombre} ) => nombre);
	    console.log(nombreFitrados);
	    
	    let buscarArticulo = articulos.find( ( {nombre} ) => nombre === 'Cuaderno' ); // Devuelve el primer valor que encuentra
	    console.log(buscarArticulo);
	    
	    let printArticulos = articulos.forEach( ( {nombre, costo} ) => console.log(nombre, costo)); // Itera el array como un for of
	    
	    let exitenEsosArticulos = articulos.some( ( {costo} ) => costo <= 500000 ); // Devuelve Verdader cuando si existen o falso cuando no
	    console.log(exitenEsosArticulos);
	    
	```

* **Valente IA** (2)

	
	otra forma de llamar al foreach
	``` 
	    articulos.forEach(articulo => {
	        console.log(articulo.nombre);
	    });```
	    
	```

* **yeseniamosqueragil** (2)

	```
	    let i = 0;
	    var articulosComprados = [
	        {nombre:'Bici',costo:800000},
	        {nombre:'Tv',costo:2000000},
	        {nombre:'Radio',costo:350000},
	        {nombre:'Movil',costo:3000000},
	        {nombre:'Cuaderno',costo:50000},
	        {nombre:'PC',costo:1900000},
	        {nombre:'Mouse',costo:30000},
	        {nombre:'Escoba',costo:10000}
	    ];
	    var buscaArticuloCosto = articulosComprados.find(function(articulo){
	        if(articulo.nombre === 'PC'){
	            console.log('El articulo PC ya existe!!');
	        }
	    });
	    
	    buscaArticuloCosto;
	    
	    var iteraArticulos = articulosComprados.forEach(function(articulo){
	        i++;
	        console.log(`Articulo #${i}. ${articulo.nombre}`);
	    });
	    
	    var validaArticulo = articulosComprados.some(function(articulo){
	        return articulo.costo<=30000;
	    });
	    console.log(`¿Existe al menos 1 articulo de 30.000 o menos? ${validaArticulo ?'Si' :'No'}`);
	    
	```

* **hidalgolopezdaniel** (2)

	
	Apliqué el articulo.nombre === “Laptop” con el método FILTER y de igual forma funcionó. Dicho esto…  
	**¿Cuál sería el mejor método a elegir y por qué?**

	* **Ruben Padilla** (6)

		
		El método que uses depende del problema que quieras solucionar.
		
		  * _filter_ devuelve un array de todos los elementos que cumplan la condición. Un caso de uso sería para filtrar una lista de peliculas según su genero
		
		  * _find_ devuelve solo un elemento, el primero que cumpla la condición. Puedes hallar un usuario en una lista usando su _username_
		
		
		

* **Ronal Roberto Choque Copa** (2)

	
	Si solo el metodo .some() devuelve true o false… para que genera un nuevo Array?

	* **Sneyder Alfonso Barreto Buitrago** (7)

		
		¡Hola!  
		En realidad no retorna un nuevo array, ahí el profesor se confundió un poco. Como dice, simplemente retorna un valor booleano (true o false) dependiendo de que al menos un elemento dentro del array cumpla una condición que nosotros especificamos.  
		Un saludo.

* **Javier Armando Vargas Vega** (2)

	
	Buena clase.  
	Aunque parece que algo hizo falta, pues el siguiente video es la despedida…

	* **Karla Agraz** (2)

		
		Creo que se confundieron y pusieron los vídeos al revés, por la clase anterior de los Arrays, quizás por eso dice lo de la siguiente clase.

	* **Juan José Vega Quintero** (1)

		
		Sí, Objects

* **hidalgolopezdaniel** (2)
¿Qué método se utilizaría para buscar un rango de precio?.. es decir: precios menores a 600 y mayores a 350. En el ejemplo del maestro m...

	* **Ruben Padilla** (2)

		
		¡Hola, Daniel!  
		.  
		Para el caso que comentas puedes usar el metodo _filter_  
		.
		``` 
		    var articulos = [
		    	{ nombre: "Bici", costo: 3000 },
		    	{ nombre: "Tv", costo: 2500 },
		    	{ nombre: "Libro", costo: 320 },
		    	{ nombre: "Celular", costo: 10000 },
		    	{ nombre: "Laptop", costo: 20000 },
		    	{ nombre: "Teclado", costo: 500 },
		    	{ nombre: "Audifonos", costo: 1700 }
		    ]
		    
		    var filtrandoArticulos = articulos.filter( function ( articulo ) {
		    	if (articulo.costo > 350 && articulo.costo < 600) {
		    		return articulo
		    	}
		    })
		    
		    console.log(filtrandoArticulos) // [{ nombre: "Teclado", costo: 500 }]
		    
		```
		
		Saludos!

* **Ariel Alejandro Ureña Morales** (1)

	
	Excelente clase.

* **garciafran** (1)

	
	Capitulo bastante extenso
	``` 
	    //metodo find
	    var articulos = [
	        { nombre: "Bici", costo: 3000 },
	        { nombre: "tv", costo: 2500 },
	        { nombre: "libro", costo: 320 },
	        { nombre: "celular", costo: 20000 },
	        { nombre: "laptop", costo: 2500 },
	        { nombre: "teclado", costo: 500 },
	        { nombre: "audifonos", costo: 1700 }
	    ];
	    
	    var encuentraArticulo = articulos.find(function(articulo) {
	        return articulo.nombre === "laptop"
	    });
	    
	    //metodo forEach
	    var articulos = [
	        { nombre: "Bici", costo: 3000 },
	        { nombre: "tv", costo: 2500 },
	        { nombre: "libro", costo: 320 },
	        { nombre: "celular", costo: 20000 },
	        { nombre: "laptop", costo: 2500 },
	        { nombre: "teclado", costo: 500 },
	        { nombre: "audifonos", costo: 1700 }
	    ];
	    
	    articulos.forEach(function(articulo) {
	        console.log(articulo.nombre);
	    });
	    
	    //metodo some
	    var articulos = [
	        { nombre: "Bici", costo: 3000 },
	        { nombre: "tv", costo: 2500 },
	        { nombre: "libro", costo: 320 },
	        { nombre: "celular", costo: 20000 },
	        { nombre: "laptop", costo: 2500 },
	        { nombre: "teclado", costo: 500 },
	        { nombre: "audifonos", costo: 1700 }
	    ];
	    
	    var articulosBaratos = articulos.some(function(articulo){
	        return articulo.costo <= 700;
	    })```
	    
	```

* **carlosextra1** (1)

	
	Método some();

* **carlosextra1** (1)

	
	Otro método super esencial para programar en JS

* **picojohn** (1)

	
	buena clase, nos toca es practicar

* **cesaraguilareduardoromero** (1)

	
	El metodo some() es algo nuevo que no habia escuchado

* **Diego Camino** (1)

	
	Desconocía el método some()  
	Buena clase…

* **Germán Moreno** (1)

	
	Perfecto.

* **marlonhmp** (1)

	
	Muy utiles y bien exlicados.

* **Juan Esteban Galvis** (1)
Para validar si algo cumple la condición: **some()** Devolver un nuevo Array con los datos que cumplen la condición: **filter()

* **andrés eduardo betancourt bescanza** (1)

	
	Me parece un poco confuso a la hora de usar cada uno.

* **Juan Zavala** (1)

	
	Interesante

* **Sebastián Mera** (1)

	
	Aún no me queda claro porque se usa un parámetro “articulo” en las funciones, cual es su función. Ayuda!

	* **Diego Andres Cabrera Rojas** (1)

		
		El parámetro “articulo” se le pasa a la función ya que es con este dato que es un arreglo con el que trabaja cada método que se vieron en las clases , map, filter, some , etc… , con esto le estas diciendo , oye mira aquí te entrego este arreglo con los datos , haz el trabajo según yo te indique en el bloque de la función , y el dependiendo de esas condiciones o acciones cumple con su objetivo final.

* **hidalgolopezdaniel** (1)

	
	FOREACH: Falta que explique porque está usando "console.log" en lugar de "return" como lo había estado haciendo en otros métodos. Hice la prueba con return y no funciona pero me gustaría saber ¿por qué?.

	* **Ruben Padilla** (6)

		
		A diferencia de otros métodos, _forEach_ siempre retorna _undefined_ , por esta razón usa el `console.log` para mostrar los nombres de los artículos. Un caso de uso sería agregar elementos a un array:
		``` 
		    var articulos = [
		    	{ nombre: "Bici", costo: 3000 },
		    	{ nombre: "Laptop", costo: 20000 }
		    ]
		    
		    var nombreDeArticulos = []
		    
		    articulos.forEach( function ( articulo ) {
		    	nombreDeArticulos.push( articulo.nombre )
		    })
		    
		    console.log( nombreDeArticulos ) 
		    
		    
		```

* **lmoran** (1)

	
	Excelente curso

* **Martín Roldán** (1)

	
	Los ejemplos con **.forEach** y . **map** son parecidos. Cual es la diferencia?

	* **lmoran** (3)

		
		Una de las diferencias es que el .map va almacenar el resultado en un nuevo array.  
		En cambio el forEach te muestra el resultado en texto mas no en un array.

* **Daniel Carmona** (1)

	
	Una manera mas rápida de filtrar

* **wlm.morant** (1)
hay diferencia entre map y forEach ,podrian funcionar igual???

	* **Diego Alexander Forero Higuera (Platzi)** (1)

		
		Es la forma como funcionan, map ejecuta algo por cada elemento dentro de un array, con el forEach recorres el array y puedes hacer cosas más complejas sobre el array, como validar si el valor es impar etc.

* **Oscar Galicia** (1)
El .find no puede buscar varios articulos al mismo tiempo? lo intente y no me sirvio.

	* **Luis Arturo Lira Cerda** (1)

		
		No, el find sólo sirve con un elemento.
		
		Para hacer una operación que encontrara varios elementos tendrías que hacer una lógica un poco más compleja y adaptada a lo que quieres encontrar en el arreglo.

# Cierre

## 0210. Despedida

### Descripción:


### Links:

* [Curso Online de Fundamentos de JavaScript | Platzi](https://platzi.com/clases/fundamentos-javascript)

* [Curso de JavaScript Engine (V8) y el Navegador](https://platzi.com/clases/javascript-navegador)

* [Curso de ECMAScript 6+](https://platzi.com/clases/ecmascript-6/)

* [Obtén un mes gratis en Platzi](https://platzi.com/blog/un-mes-gratis-en-platzi/)

### Comentarios:

* **Cristian Alejandro Muñoz Cardona** (7)

	
	Los cursos que recomienda al final.
	
	  * [Fundamentos de JavaScript](https://platzi.com/clases/fundamentos-javascript/)
	  * [V8 y el navegador](https://platzi.com/clases/javascript-navegador/)
	  * [ECMAScript 6+](https://platzi.com/clases/ecmascript-6/)
	
	

* **carlosbaltazarespetia** (5)

	
	Si los profesores de las universidades, enseñaran como usted, todos amarian estudiar

* **urieelmm** (3)

	
	Alguien sabe si este profesor tiene mas cursos? Es excelente !!

	* **Christian Erik Velázquez Morales** (1)

		
		Tiene el de v8, maquetación con html y css, y creo que css grid. Tiene varios (misma temática). Todos son muy bien explicados y con mucha práctica.

* **Carlos Roa** (3)

	
	¿y cuales son esos dos métodos? = “false”

	* **Manuel Rivera** (2)

		
		No lo se Rick , jajajaj

* **ArielScc** (3)

	
	Buen curso…  
	Me dejo picado por los dos métodos más. pero fui a buscar y encontré muchos más [aquí](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array)

* **cesaraguilareduardoromero** (2)

	
	Muy buen curso, pero faltaron mas metodos

* **Javier Andres Gamboa Duarte** (2)

	
	Y los otros metodos?

* **dacarr** (2)

	
	Debería enseñar mas cursos referente a JS como el de fundamentos de JS, excelente profesor recordé y aprendí mas cosas

	* **Almu_timkerbell** (2)

		
		Sí, por favor. Llegué al vídeo 34 de Fundamentos, y lo dejé ahí porque no entendía más:(

* **Manuel Rivera** (2)

	
	Es un excelente profesor

* **Ariel Alejandro Ureña Morales** (1)

	
	Muy buen curso. Gracias por la recomendación.

* **Northerchild** (1)

	
	Genial, gracias por todo profe

* **Rudy Pinzon** (1)

	
	Muchas gracias, muy buen curso

* **Juan Gomez** (1)

	
	Excelente el Curso y el Profesor. Muchas Gracias

* **Sthepha04** (1)

	
	Muy bueno el curso! 😄

* **Jharell Alejandra Hidalgo Loya** (1)

	
	excelente curso ! gracias

* **Benjamin_Espinosa_N** (1)

	
	Muy ben curso para iniciar!! muchas gracias

* **carlosextra1** (1)

	
	Gracias!! excelente curso basico!

* **Orlando0302** (1)

	
	faltaron los otros métodos pero los buscare aparte

* **Juan Teixeira** (1)

	
	En este link hay otros metodos que pudieran ser los que quedaron pendientes xD
	
	<https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array>

* **fabio-hernan-mosquera-obando** (1)

	
	para mi es un curso fabuloso.

* **Daniel Cuevas** (1)

	
	¿Cuando sale la clase de métodos de recorridos de Arrays 3?

* **Jeisson Santiago Cortes Ortiz** (1)

	
	…

* **EdwardPL** (1)

	
	Muchas Gracias , Preparado para dar mi examen

* **marlonhmp** (1)

	
	Excelente curso me ayudo bastante.

* **JIMMY STEVE OSMA JEREZ** (1)

	
	Muy buen curso, Muchas Gracias

* **Christian David Sánchez** (1)

	
	Un excelente curso.  
	Les comparto un link para que puedan seguir aprendiendo: **<https://www.w3schools.com/js/default.asp>**

* **isabellaahc** (1)

	
	No está disponible la clase métodos de recorridos de arrays 3 😦 no me siento 100% lista para hacer la prueba uwu

* **mermib** (1)

	
	muy buen curso, básico pero conciso

* **Wandy Rafael Santana Evangelista** (1)

	
	De los mejores cursos que he tomado. 😃

* **Bryan Gallo** (1)

	
	Excelente Curso más que recomendado 😄

* **Rafael Alvarez Cardona** (1)

	
	Excelente curso! Gracias Diego! eres un crack, maquina, fiera.! 😄

* **Luis Gerardo Choloquinga Cocha** (1)

	
	Buen Curso!!

* **Gianfranco Giordano** (1)

	
	Hola compañeros. Soy nuevo en Platzi, una pregunta como se presenta el examen?

	* **Rafael Alvarez Cardona** (2)

		
		Amigo al finalizar cada curso te dan un tiempo especifico y un numero de preguntas! tienes que obtener una nota minima de **9** para poder pasar el examen en caso de que no logres la meta te dan 6 horas para que vuelvas a repetir el examen y puedas lograr el objetivo! 😄 espero haberte ayudado!

* **gonzaloPzl** (1)

	
	EXCELENTE CURSO!!

* **Ariel Luna** (1)

	
	Un Genio tengo una duda con el tema del constuctor de objetos. la pongo en preguntas.  
	Saludos

* **EmiGarello** (1)

	
	estubo genial!!!

* **Gilmar Natanael Morán Aquino** (1)

	
	Excelente Curso!!!

* **Jhon Alexander Romero Gonzaga** (1)

	
	Grande!!

* **Juan Zavala** (1)

	
	Excelente profesor, por ende, excelente curso

* **Joker11** (1)

	
	Buen curso explicado !

* **Javier Avalos** (1)

	
	Excelente curso, bien detallada la explicación

* **JuanDanielRR** (1)

	
	Like!!

* **Christian Erik Velázquez Morales** (1)

	
	Muchas Gracias! Gracias, por hacer que sea práctico, y muy comprensible (retroalimentación).

* **lmoran** (1)

	
	Muy bien explicado y entendible el curso.

* **Nagcely Mendoza** (1)

	
	Excelente curso, gracias por compartir tus conocimientos.

* **ferchodleon** (1)

	
	Muchas gracias, fue de gran ayuda este curso!!

* **dlee00** (1)

	
	Excelente curso, muchas gracias por todo!

* **Camilo Alexander Velandia Velandia** (1)

	
	buen curso

* **johngoyo88** (1)

	
	No entiendo, en la clase 20 dices que vas a enseñar en la siguiente clase dos métodos mas y me sale es la despedida. Pasa algo? le sucedió a otro o solo a mi? :?

	* **Oscar Galicia** (2)

		
		Esta al reves la clase 19 y la 20… O algo asi.

* **Diego Guillermo Yovera Coveñas** (1)

	
	Buen curso, no programo hace tiempo, me refrescaste todo bastante bien.

* **axlina90** (1)

	
	Excelente curso, aprendi bastante, explica muy bien, JavaScript poco lo uso pero ahora me gusta

* **braulioondoedu** (1)

	
	excelente profesor

* **quiquejesus94** (1)

	
	Me encanto el cusro exelente maestro 😃

* **Bryan Estiven Silva Mercado** (1)

	
	Un excelente profesor.

* **Daniel Carmona** (1)

	
	Me encantan los cursos

* **Lorenzo David Lezcano** (1)

	
	Me gusto mucho este curso, ahora a seguir aprendiendo con js!

* **Ariel Luna** (1)
Respuesta a: Objects: Función constructora Consulta:Si la funcion construcntora que se crea con la palabra reservada “new” crea una insta...

	* **John Botero** (1)

		
		Desde la ECMAScript2015 se puede implementar las clases para constructores.  
		<https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Classes/constructor>
		``` 
		    class auto {
		        constructor(marca, modelo, annio) {
		            this.marca = marca;
		            this.modelo = modelo;
		            this.annio = annio;
		        }
		    	set () {
		    	}
		    
		    	get () {
		    	}
		    }
		    
		```

