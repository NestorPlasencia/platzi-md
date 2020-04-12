[Curso de Programación Funcional en JavaScript por Bedu 1497](https://platzi.com/cursos/funcional-js)

# Introducción al curso y conceptos base [3339]

## 0010. ¿Qué es la programación funcional [16791](https://platzi.com/clases/1497-funcional-js/16791-que-es-la-programacion-funcional/)

### Descripción:


En esta clase el profesor David Colín nos explica qué es la programación funcional y cómo nos ayuda a crear código más conciso, legible y fácil de probar.

La programación funcional es un paradigma de programación, una forma diferente de entender el código. Buscamos explicar qué hay que hacer, en vez de cómo lo debemos hacer. Tampoco utilizamos clases o constructores, más bien declaramos objetos con propiedades que actualizamos sin modificar los objetos iniciales (funciones puras e inmutabilidad).

### Comentarios:

* **Juan David Castro (Platzi)** (13) [486733](https://platzi.com/comentario/486733/) 

	Notas de la clase:
	
	* 🌄 La programación funcional es una nueva forma de pensar y entender nuestro código.
	* 👨‍👩‍👧‍👦 El objetivo es crear código más conciso, legible y fácil de probar.
	* 🔀 Existen otros paradigmas como la Programación Orientada a Objetos (POO) y la Programación por Procedimientos.
	* 🤓 Buscamos resolver el _“qué hay que hacer”_ en vez del _“cómo lo debemos hacer”_ (código declarativo).
	
	

	* **Carlos Gómez Mont** [486733] (1)

		Super aporte, gracias!!

	* **Juan David Castro (Platzi)** [486733] (2)

		* [Introduction To Protocol Oriented Programming](https://medium.com/swlh/introduction-to-protocol-oriented-programming-1ff3862f9a3c) 🤔
		
		

* **Juan David Castro (Platzi)** (5) [486730](https://platzi.com/comentario/486730/) 

	**POO 🆚 Programación Funcional** :
	``` 
	    // POO
	    classPerson{
	            constructor(name, age) {
	                    this.name = name
	                    this.age = age
	            }
	            getOld() {
	                    this.age += 1
	            }
	    }
	    
	    let person = new Person('JuanDC', 15)
	    person.getOld() // 16
	    
	    // Functional
	    const juandc = {
	            name: 'JuanDC',
	            age: 15
	    }
	    
	    const getOld = person => Object.assign(
	        {},
	        person,
	        { age: person.age + 1}
	    )
	    getOld(juandc) // 16
	    
	```

	* **Carlos Gómez Mont** [486730] (1)

		Gracias por compartir, saludos!!

* **Sebastian Elias Medina Donoso** (4) [608740](https://platzi.com/comentario/608740/) 

	¿por qué el titulo dice “por Bedu”?

	* **Jhon Alexander Perez Valencia** [608740] (3)

		Talvez es un convenio o algo asi.🤔🤔
		
		> Bedu es una academia con metodología innovadora que te prepara para cubrir las necesidades del mercado laboral actual. ¡Combina la mejor experiencia y tecnología en un solo curso!  
		>  <https://bedu.org/>

	* **Jose Padron (Platzi)** [608740] (3)

		Este junto con el curso de react redux y el de firebase y vue son cursos que los profesores son de Bedu, están geniales los cursos.

	* **Jean Carlos Nuñez Hernandez** [608740] (1)

		Me gustan los cursos por bedu aqui en platzi

* **Danelia Sanchez Sanchez** (4) [494656](https://platzi.com/comentario/494656/) 

	Comparto estos artículos:
	
	[Introducción a programación funcional en Javascript](https://medium.com/laboratoria-developers/introducci%C3%B3n-a-la-programaci%C3%B3n-funcional-en-javascript-parte-1-e0b1d0b2142e)  
	[Master the JavaScript Interview: What is Functional Programming?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0)

* **Juan David Castro (Platzi)** (4) [486731](https://platzi.com/comentario/486731/) 

	 **P. Imperativa 🆚 P. Declarativa**
	``` 
	    // Imperative
	    let array = [1,2,3]
	    let array2 = []
	    
	    for (let i = 0; i<array.length;i++) {
	            array2.push(array[i]*2) // [2,4,6]
	    }
	    
	    // Declarative
	    let array = [1,2,3]
	    let array2 = array.map(item => item*2) // [2,4,6]
	    
	```

* **Julio J Yépez** (3) [486487](https://platzi.com/comentario/486487/) 

	Para qué sirve la Programación Funcional

* **Abner Paul Ccari Lindo** (2) [831035](https://platzi.com/comentario/831035/) 

	Gran explicacion!

* **jorgehernandezjd** (2) [493765](https://platzi.com/comentario/493765/) 

	Programación funcional significa que cuando estés desarrollando tu código tienes que enfocarte en que hay que hacer en lugar de como hay que harcelo

* **Jaime Arcos** (2) [490643](https://platzi.com/comentario/490643/) 

	Programación funcional (pros):
	
	> Menos código  
	>  Más legible  
	>  Más fácil de mantener y testear

* **Nigtdreams** (1) [771848](https://platzi.com/comentario/771848/) 

	se ve increible

* **waldoaraque** (1) [684691](https://platzi.com/comentario/684691/) 

	Interesante se ve el curso!

* **Jhon Alexander Perez Valencia** (1) [615414](https://platzi.com/comentario/615414/) 

	muy buenos ejemplos.

* **dcortesnet** (1) [545705](https://platzi.com/comentario/545705/) 

	En ejemplo de Imperativo vs declarativo, utilizar en esté caso funciones como map genera una menor la carga en el procesador que utilizar un for ?

	* **Juan David Castro (Platzi)** [545705] (1)

		No necesariamente. El **`.map`** lo podemos reemplazar por un ciclo **`for`** común y corriente. Pero teniendo que escribir “a mano” podemos no prepararnos para todos los casos (por ejemplo, que el array esté vacío).
		
		Puedes ver la implementación de algunas de estas funcionalidades o incluso escribir el código que corren. Creo que sería un buen ejercicio.
		
		👉 <https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array/map#Polyfill>  
		👉 <https://www.youtube.com/watch?v=lUygjLgVUNs>

* **Hebert  lughi villafuerte ccacala** (1) [486545](https://platzi.com/comentario/486545/) 

	good!

* **Carlos Gómez Mont** (1) [486522](https://platzi.com/comentario/486522/) 

	Genial, super practica, al ritmo que vamos es muy necesario. BTW en Flutter también utilizamos código declarativo con Dart.

## 0020. Introducción al curso [16790](https://platzi.com/clases/1497-funcional-js/16790-introduccion-al-curso4995/)

### Descripción:


¡Bienvenido al Curso de Programación Funcional en JavaScript!

Gracias a la programación funcional vamos a mejorar el tiempo y la calidad del código que escribimos, va a ser mucho más fácil de leer, compartir y probar.

En esta ocasión nos acompaña el profesor David Colin, Desarrollador JavaScript Full Stack en SalesLoft.

### Comentarios:

* **David Antonio Ordóñez Cornejo** (3) [545100](https://platzi.com/comentario/545100/) 

	Ya me cayeron bien, porfin un curso de FP

* **Alejandro Bracho** (3) [486223](https://platzi.com/comentario/486223/) 

	Muy emocionado con el curso jejejeje

* **Lina María Montaño Ramírez** (2) [493187](https://platzi.com/comentario/493187/) 

	Vengo por recomendacion de Julio, espero aprender y afianzar aquellos vacios.

* **Carlos Gómez Mont** (2) [486511](https://platzi.com/comentario/486511/) 

	Muy chevere intro, gracias por compartir tu historia, que siga el éxito y a darle!

* **Juan Arrebillaga** (2) [486253](https://platzi.com/comentario/486253/) 

	Alla vamos!

* **Carlos Andrés Garcés González** (1) [669855](https://platzi.com/comentario/669855/) 

	Que problema tendría una mejor solución con POO que con Funcional?

	* **waldoaraque** [669855] (2)

		Considero que no un “problema” como tal se solucionaría específicamente con FP, más bien, es una forma de hacer código más óptimo porque a fin de cuentas menos instrucciones hace el código más ligero y rápido de procesar… No son temas de estándar de desarrollo, simplemente metodologías de trabajo.

	* **Cesar Rodriguez** [669855] (1)

		definitivamente videojuegos

* **Jhon Alexander Perez Valencia** (1) [615417](https://platzi.com/comentario/615417/) 

	suena genial este curso!!!

* **Freddy Córdova Arana** (1) [542443](https://platzi.com/comentario/542443/) 

	Suena genial!

* **Juan Manuel Viveros Martinez** (1) [502187](https://platzi.com/comentario/502187/) 

	vamos con toda

* **Alfonso Navarro** (1) [498078](https://platzi.com/comentario/498078/) 
Emocionado con todo el tema de JavaScript

* **Jaime Arcos** (1) [490629](https://platzi.com/comentario/490629/) 

	Suena muy bien!

* **sebastianandrada** (1) [489744](https://platzi.com/comentario/489744/) 

	por fin! esperaba ansioso este curso

* **prsanchez** (1) [489626](https://platzi.com/comentario/489626/) 

	here we go

## 0030. Boilerplate Base para el proyecto del curso [16792](https://platzi.com/clases/1497-funcional-js/16792-boilerplate/)

### Descripción:


El proyecto de este curso es un **contador de calorías** , podemos agregar diferentes alimentos, calorías, proteínas y carbohidratos que deben sumarse de manera automática.

Recuerda que el código base ya está listo y lo puedes descargar en la sección de archivos de la clase.

### Comentarios:

* **Fernando Alejandro Yerena Ramos** (6) [611567](https://platzi.com/comentario/611567/) 

	Para quienes prefieran continuar el curso usando una plantilla con **HTML, CSS** y **JS _vanilla_** , les dejo el enlace a: [mi repositorio del curso](https://github.com/ferdinandalexa/Calories_Counter).
	
	Es la misma plantilla que encuentran en la pestaña de “ _Recursos_ ”, pero sin Bootstrap ni JQuery. Espero les sirva y que no encuentren inconveniente al usarla. Siéntanse libres de hacer PR. Con gusto los recibiré.
	
	_Nunca paren de aprender_ ñ.ñ/

	* **Fernando Alejandro Yerena Ramos** [611567] (3)

		Plantilla del proyecto: <https://github.com/ferdinandalexa/Calories_Counter/tree/v0.1.0>

* **Bryan Estiven Silva Mercado** (2) [506533](https://platzi.com/comentario/506533/) 

	Vamos a empezar a aprender algo nuevo de js , Emocionado!

* **elviejomenu** (2) [51291](https://platzi.com/comentario/489511/) 
Emocionado con este curso… Es indispensable tener conocimientos previos en JS ?

	* **Melisa Lozano (Platzi)** [51291] (2)

		Si es que tienes conocimientos básicos en programación te recomiendo tomar primero este curso para estar un poco más en contexto [Fundamentos de JavaScript  
		](https://platzi.com/clases/fundamentos-javascript/)

* **Juan Carlos Valencia López** (1) [1042400](https://platzi.com/comentario/1042400/) 

	Que paquete de iconos usa el profe?

* **Andrés Fleiz** (1) [495392](https://platzi.com/comentario/495392/) 

	Muy buen curso!

* **elviejomenu** (1) [489511](https://platzi.com/comentario/489511/) 

	Emocionado con este curso…  
	Es indispensable tener conocimientos previos en JS ?

	* **Melisa Lozano (Platzi)** [489511] (2)

		Si es que tienes conocimientos básicos en programación te recomiendo tomar primero este curso para estar un poco más en contexto [Fundamentos de JavaScript  
		](https://platzi.com/clases/fundamentos-javascript/)

	* **gusgonzalez060** [489511] (3)

		El curso de “JQuery a JavaScript vanilla” también te va a servir mucho para entender las bases del lenguaje.

	* **IDavidC** [489511] (2)

		Lo más importante es ver algo de ES6 primero ya que la mayoría de los ejemplos están usando arrow functions

* **Cristobal Peña** (1) [83722](https://platzi.com/comentario/1033308/) 
¿Hay algún curso específico para aprender a construir este tipo de HTML para hacer aplicaciones web?

	* **Ruben Padilla** [83722] (1)

		¡Hola, Cristobal!
		
		Te recomiendo el [Curso de Desarrollo Web Online](https://platzi.com/clases/html5-css3/)

# Funciones [3340]

## 0040. Funciones Algebraicas y Funciones de JavaScript [16793](https://platzi.com/clases/1497-funcional-js/16793-funciones-en-javascript4078/)

### Descripción:


Por lo general, utilizamos las funciones de JavaScript para realizar algunas operaciones o una secuencia de procedimientos. También podemos convertir una función algebraica a una función pura de JavaScript: definimos una función `F` que recibe el parámetro `X` y devuelve el valor de `X*2`.
``` 
    F(x) = 2 * x
    
```

Por supuesto, la manera de utilizar este tipo de funciones es asignando el valor de `X`:
``` 
    F(2) = 2 * 2
    F(2) = 4
    
```

Estas funciones siempre van a devolver el mismo resultado, es decir, si entregamos el parámetro `2`, siempre vamos a recibir un `4`, si entregamos el parámetro `3`, siempre vamos a recibir `6` y así sucesivamente.

Las funciones en JavaScript funcionan de la misma manera:
``` 
    const double = (x) => x*2
    double(2) // 4
    
```

En la siguiente clase vamos a ver otros ejemplos de funciones puras en JavaScript.

### Comentarios:

* **Juan David Castro (Platzi)** (10) [486734](https://platzi.com/comentario/486734/) 

	 **3 Formas diferentes para declarar la función`double` en JavaScript:**
	``` 
	    // Normal Function
	    functiondouble(x) {
	            return x * 2
	    }
	    
	    // Arrow Function
	    const double = (x) => {
	            return x * 2
	    }
	    
	    // Short Arrow Function
	    const double = x => x*2
	    
	```

	* **Juan Luis Rojas León** [486734] (4)

		```
		    // Self Invoking
		    (function(x) {
		    	returnx * 2
		    })(number)
		    
		    // Self Invoking Arrow Function
		    ((x) = x => x * 2)(number)
		    
		```

* **Julio J Yépez** (10) [486501](https://platzi.com/comentario/486501/) 

	Hace un tiempo hice este artículo para el curso de Redux sobre algunos conceptos tratados en esta clase, quizás lo encuentren de utilidad: [Funciones Puras: Una breve introducción a la …](https://platzi.com/tutoriales/1200-redux/1797-funciones-puras-una-breve-introduccion-a-la-programacion-funcional/)

	* **Carlos Gómez Mont** [486501] (2)

		Super aporte, gracias!!

	* **Bryan Estiven Silva Mercado** [486501] (2)

		Gracias , iré a leerlo enseguida

* **Martín Leyva** (9) [486505](https://platzi.com/comentario/486505/) 

	Hay un excelente curso en está plataforma donde se explica el concepto de función.
	
	Es el curso de: **Cálculo para Análisis de Datos** , que imparte **_Marce Valenzuela._**
	
	En la Lección 3: **Función, Dominio y Contradominio** explica el concepto de función.
	
	**Función** : es la relación que hay entre dos conjuntos, a través de la cual a cada elemento del primer conjunto se le asigna un único elemento del segundo conjunto o ninguno.
	
	Les recomiendo ampliamente que cuando tengan oportunidad cursen el curso mencionado y el resto de cursos la **Carrera “Matemáticas para la Programación”** eso va a hacer diferencia en tu manera de resolver los problemas.

	* **Carlos Gómez Mont** [486505] (2)

		Gracias por compartir, saludos!!

	* **Nathaly Stefani Riaño Bejarano** [486505] (3)

		Me gustó ésta definición de función: “Una función es una correspondencia entre dos conjuntos de forma que a cada elemento del conjunto inicial (variable independiente) le corresponda un único elemento del conjunto final (variable dependiente)”
		
		El curso de fundamentos de matemáticas también retoma todos estos conceptos para formar una base sólida! 💪

* **Juan David Castro (Platzi)** (4) [486735](https://platzi.com/comentario/486735/) 

	¡Noooooo! ¡Volvió el profe de matemáticas 😱😱😱!

* **Martín Leyva** (4) [486489](https://platzi.com/comentario/486489/) 

	El ejemplo de la función explicada por David codificada en JavaScript:
	``` 
	    constdouble = (x) => x*2
	    double(2) // 4```
	    
	```

* **Kingsman7** (1) [639811](https://platzi.com/comentario/639811/) 

	wow wow wow, mi mente acaba de explotar. Las matemáticas que aprendí si sirvieron de algo y hoy me di cuenta

## 0050. Funciones puras [16795](https://platzi.com/clases/1497-funcional-js/16795-funciones-puras/)

### Descripción:


Las funciones puras siempre devuelven el mismo resultado cuando reciben los mismos parámetros. En cambio, otras funciones que dependen de factores externos (como el tiempo o una petición HTTP) no siempre pueden devolver el mismo resultado aunque reciban los mismos parámetros, incluso, pueden no necesitar recibir parámetros para ejecutarse correctamente.

Ejemplos de funciones puras:
``` 
    const double = x => x*2
    double(2) // siempre es 4
    double(3) // siempre es 6
    
    const isGreaterThan = (value, comparison) => value > comparison
    isGreaterThan(5, 6) // siempre devuelve false
    isGreaterThan(8, 6) // siempre devuelve true
    
```

Ejemplos de funciones que NO son puras:
``` 
    const time = () => new Data().toLocalTimeString()
    time() // siempre devuelve un resultado diferente
    
```

### Comentarios:

* **Eliseo Geraldo González** (8) [486308](https://platzi.com/comentario/486308/) 

	Las funciones puras no dependen de factores externos y son predecibles, trabajan con los argumentos que asignamos y constantes como números, o PI.
	``` 
	    // función pura
	    functionpriceAfterTax(productPrice) {
	      return (productPrice * 0.20) + productPrice;
	    }
	    
	```
	
	En el caso de que nuestra función utilice variables externas, se considera impura, si otro desarrollador o proceso puede cambiar el valor de `tax` en el siguiente ejemplo, el valor de retorno no sería predecible.
	``` 
	    // función impura
	    var tax = 20;
	    
	    functioncalculateTax(productPrice) {
	     return (productPrice * (tax/100)) + productPrice; 
	    }
	    
	```

	* **Carlos Gómez Mont** [486308] (1)

		Super aporte, gracias!!

* **Danelia Sanchez Sanchez** (5) [494792](https://platzi.com/comentario/494792/) 

	[Introducción a la programación funcional en JavaScript — Parte 2: Funciones Puras](https://medium.com/laboratoria-developers/introducci%C3%B3n-a-la-programaci%C3%B3n-funcional-en-javascript-parte-2-funciones-puras-b99e08c2895d)

* **Enrique Devars (Platzi)** (4) [663816](https://platzi.com/comentario/663816/) 

	## Definición de función pura
	
	<https://platzi.com/clases/1497-funcional-js/16795-funciones-puras/?time=87>

* **Cristian David Franco Garcia** (4) [532185](https://platzi.com/comentario/532185/) 

	Mi definición sobre función pura:
	
	**Función pura:** Conjunto de pasos finitos que trabajan únicamente con los parámetros de entrada que recibe y siempre regresa el mismo resultado para dichos parámetros de entrada. No interactúa con variables globales.

* **Juan David Castro (Platzi)** (3) [486737](https://platzi.com/comentario/486737/) 

	 _Is a parameter and an argument one and the same?_ 🤔🤔🤔
	
	* [Parameters vs Arguments in JavaScript - Yash Agrawal](https://codeburst.io/parameters-arguments-in-javascript-eb1d8bd0ef04)
	
	

* **Juan David Castro (Platzi)** (2) [486738](https://platzi.com/comentario/486738/) 

	* [Funciones Puras: Una breve introducción a la Programación Funcional - @jjyepez en el Curso de Redux](https://platzi.com/tutoriales/1200-redux/1797-funciones-puras-una-breve-introduccion-a-la-programacion-funcional/)
	* [What Is a Pure Function in JavaScript?](https://medium.freecodecamp.org/what-is-a-pure-function-in-javascript-acb887375dfe)
	
	

* **noemk2** (1) [487690](https://platzi.com/comentario/487690/) 

	la única función No-pura es con la fecha o el tiempo?

	* **Sebastian Gutierrez** [487690] (5)

		hola @noemk2, no necesariamente, que se use la fecha o el tiempo no quiere decir que sea una función no pura, por ejemplo, la libraría [date-fns](https://github.com/date-fns/date-fns/) está hecha para trabajar con las fechas y el tiempo, sin embargo tiene su base en funciones puras e inmutables
		
		Básicamente una función que retorna valores no predecibles es considerada un función no pura, por ejemplo, si creas una función que devuelve un número aleatorio entre un rango de dos números, es considerada una función no pura, ya que a pesar de recibir siempre los mismos parámetros, no podemos saber cual resultado obtendremos.
		``` 
		    const getRandomNumber = (min, max) => {
		      returnMath.floor((Math.random() * max) + min);
		    }
		    
		    getRandomNumber(1, 10); // 3
		    getRandomNumber(1, 10); // 9
		    getRandomNumber(1, 10); // 2
		    
		```
		
		Estos dos aspectos son clave para reconocer funciones puras, si no cumplen con una de estas, entonces son impuras
		
		* Dada los mismo argumentos siempre retornaran los mismos resultados
		* No produce efectos secundarios
		
		

	* **Juan David Castro (Platzi)** [487690] (1)

		Cualquier función que pueda NO devolver el mismo resultado enviando los mismos argumentos NO es una función pura. Por ejemplo, las fechas y peticiones a una API no son funciones puras.

* **Juan David Castro (Platzi)** (1) [486736](https://platzi.com/comentario/486736/) 

	Notas de la clase:
	
	* 👀 Podemos distinguir a las funciones puras porque siempre que pasemos los mismos argumentos vamos a recibir los mismos resultados.
	* ✈️ Las funciones puras NO pueden depender de factores o procedimientos externos como una consulta al tiempo o una API.
	
	

	* **Carlos Gómez Mont** [486736] (1)

		Gracias por compartir, saludos!!

	* **Juan David Castro (Platzi)** [486736] (5)
![](https://pbs.twimg.com/media/DxaL23-VAAA4t6m?format=jpg&name=medium)

	* **Andres Rivera** [486736] (2)

		Juan no sabes lo que me ayudo en el sentido memetécnico esa imagen

* **noemk2** (1) [51125](https://platzi.com/comentario/487690/) 
la única función No-pura es con la fecha o el tiempo?

	* **Sebastian Gutierrez** [51125] (5)

		hola @noemk2, no necesariamente, que se use la fecha o el tiempo no quiere decir que sea una función no pura, por ejemplo, la libraría [date-fns](https://github.com/date-fns/date-fns/) está hecha para trabajar con las fechas y el tiempo, sin embargo tiene su base en funciones puras e inmutables
		
		Básicamente una función que retorna valores no predecibles es considerada un función no pura, por ejemplo, si creas una función que devuelve un número aleatorio entre un rango de dos números, es considerada una función no pura, ya que a pesar de recibir siempre los mismos parámetros, no podemos saber cual resultado obtendremos.
		``` 
		    const getRandomNumber = (min, max) => {
		      returnMath.floor((Math.random() * max) + min);
		    }
		    
		    getRandomNumber(1, 10); // 3
		    getRandomNumber(1, 10); // 9
		    getRandomNumber(1, 10); // 2
		    
		```
		
		Estos dos aspectos son clave para reconocer funciones puras, si no cumplen con una de estas, entonces son impuras
		
		* Dada los mismo argumentos siempre retornaran los mismos resultados
		* No produce efectos secundarios
		
		

## 0060. Proyecto Obtener el valor de los inputs [16794](https://platzi.com/clases/1497-funcional-js/16794-obtener-valor-de-un-input/)

### Descripción:


### Comentarios:

* **Eliseo Geraldo González** (16) [486321](https://platzi.com/comentario/486321/) 

	Los IDs de los elementos HTML están registrados como variables gloables, esto **NO** es un beta, [está respaldado por el standard de HTML 5](http://2ality.com/2012/08/ids-are-global.html).
	``` 
	    <div>
	      <inputid="$carbs"value="340">
	    </div>
	    
	```
	
	Luego podemos acceder al elementos simplemente escribiendo el ID en la terminal o en JavaScript.
	``` 
	    console.log($carbs.value) // => 340
	    
	```
	
	No hay necesidad de selectores para IDs.

	* **Juan Reyes** [486321] (1)

		Buen dato. No conocía esta manera de acceder a los elementos.

	* **Carlos Gómez Mont** [486321] (1)

		Gracias por compartir, saludos!!

	* **asaucedormz** [486321] (1)

		No conocía que se podían acceder a los elementos por id de esta forma, gracias

	* **elviejomenu** [486321] (1)

		Para testear lo que dice el compañero pero con un valor por defecto en la consola utilicen la siguiente linea :
		``` 
		    console.log(description.value = 123)
		    
		```

	* **Nathaly Stefani Riaño Bejarano** [486321] (3)

		Estuve buscando y encontré que JS tiene acceso a los id que se declaran en el HTML debido a que estos se comportan como variables globales, pero es un mala práctica hacerlo de ésta forma, siempre es mejor utilizar getElementById()
		
		Pueden ver las respuestas completas en:
		
		<https://stackoverflow.com/questions/6381425/is-there-a-spec-that-the-id-of-elements-should-be-made-global-variable>
		
		<https://stackoverflow.com/questions/37224092/accessing-a-div-using-id-without-getelementbyid-and-jquery/37224123>

	* **Miguel Gil Rosas** [486321] (1)

		Es verdad, pero el id debe cumplir con el estándar de nombres de JS. Un id como input-calories funciona como id pero no serviría como nombre en JS ¡Cuidado con eso!

	* **Victor Lozada** [486321] (1)

		Creo que llenar el scope global de esa manera no es la mejor practica…

	* **Jorge Mendez Ortega** [486321] (1)

		Que loco esa manera no la conocia men, gracias por el aporte

* **Miguel Gil Rosas** (10) [494610](https://platzi.com/comentario/494610/) 

	Es un poquito triste que en un curso de programación funcional en los tiempos que corren se use jQuery para acceder a los elementos del DOM. Entiendo que si usas Bootstrap ya te lo tienes que traer pero aún así… 😦

	* **Victor Lozada** [494610] (2)

		Opino lo mismo !

	* **Bryan Estiven Silva Mercado** [494610] (2)

		sin dudas

	* **oteka21** [494610] (2)

		Bueno yo pensé lo mismo y lo que voy a hacer es tratar de seguir el curso sin utilizar jquery en lo absoluto.
		
		#TeamVanillaJs

* **Jorge Mendez Ortega** (7) [537848](https://platzi.com/comentario/537848/) 

	No megusta usar `jQuery` entiendo que por facilidad y practicidad se utilize pero en caso estoy utilizando `JS` puro por lo que el codigo queda de la siguiente manera.
	``` 
	    const compose = (...functions) => data =>
	        functions.reduceRight((value, func) => func(value), data)
	    
	    const $DESCRIPTION = document.getElementById("description");
	    const $CALORIAS = document.getElementById("calorias");
	    const $CARBOIDRATOS = document.getElementById("carboidratos");
	    const $PROTEINAS = document.getElementById("proteinas");
	    
	    
	```
	
	N **ota:** Como una buena práctica estoy utilizando el signo `$` para identificar de manera más fácil las referencias al `DOM`.
	
	Como se muestra en la imagen al igual que con `jQuery` puedo tener acceso a las propiedades del los `inputs`, por cierto en ves de utilizar `document.getElementById("calorias");` podria a ver utilizado `document.querySelector("#calorias");`
	
	![Captura de pantalla 2019-03-17 a la\(s\) 20.41.05.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-03-17%20a%20la%28s%29%2020.41.05-c9ceb678-8981-4fea-9257-f37e762a5ba7.jpg)

* **nodezi** (4) [486400](https://platzi.com/comentario/486400/) 

	let inputs = document.getElementsByTagName(‘input’)
	
	let {  
	desc,  
	cal,  
	carb,  
	prote } = inputs

	* **dcortesnet** [486400] (2)

		let { description, calories, carbohydrates, protein } = document.getElementsByTagName(‘input’);
		
		sería mejor, ya que inputs lo estas guardando en memoria y es innecesario

	* **oteka21** [486400] (1)

		Wow! que buena jugada, la voy a implementar

* **juan-pablo-castro** (2) [660012](https://platzi.com/comentario/660012/) 

	js
	``` 
	    const $Calories = document.getElementById ("Calories");
	    const $description = document.getElementById ("description");
	    const $carbs = document.getElementById ("carbs");
	    const $Protein = document.getElementById ("Protein");
	    
	    console.log (`Calories: ${$Calories.value}`);```
	    
	    html
	    
	    
	    
	```
	``` 
	                  <input type="text" class="form-control mb-2 mr-sm-2" placeholder="Description" id= "Description">
	              </div>
	              <div class="col">
	                  <input type="number" min="0" class="form-control mb-2 mr-sm-2" placeholder="Calories" id= "Calories">
	              </div>
	              <div class="col">
	                  <input type="number" min="0" class="form-control mb-2 mr-sm-2" placeholder="Carbs" id= "carbs">
	              </div>
	              <div class="col">
	                  <input type="number" min="0" class="form-control mb-2 mr-sm-2" placeholder="Protein" id= "Protein">
	              </div>```
	    
	```

* **Bryan Estiven Silva Mercado** (2) [506552](https://platzi.com/comentario/506552/) 

	me hubiera gustado que se use JS puro en el proyecto

* **asaucedormz** (2) [488176](https://platzi.com/comentario/488176/) 

	document.querySelector(’#carbs’)

* **emanuel-alejandro-mamani** (1) [869211](https://platzi.com/comentario/869211/) 

	yo lo hice de la siguente manera, espero que les ayude
	``` 
	    const data = {
	        'description': document.getElementById('description').value,
	        'calories': document.getElementById('calories').value,
	        'carbs': document.getElementById('carbs').value,
	        'protein': document.getElementById('protein').value
	      }
	    
	```

* **diegoagd10** (1) [502621](https://platzi.com/comentario/502621/) 

	Porque no definir las variables como const (Para que sean inmutables)?

	* **Erik Ochoa (Platzi)** [502621] (2)

		Concuerdo, yo las hubiera definido como const, incluso por costrumbre en JQuery antepongo el ‘$’ para saber que son elementos del DOM.
		``` 
		    const $description = $('#description')
		    
		```
		
		No hay ningun problema con usar **let** , pero si creo que son elementos que dificilmente vamos a necesitar que cambien y por eso conviene usar **const**.

	* **IDavidC** [502621] (5)

		Declarar objetos con `const` no los hace inmutables:
		``` 
		    constpost = {
		    	title: "Some Title"
		    }
		    
		    post.title = "New Title"
		    
		    console.log(post.title) // "New Title"
		    
		```

	* **Bryan Estiven Silva Mercado** [502621] (2)

		La declaración de una constante crea una referencia de sólo lectura. No significa que el valor que tiene sea inmutable, sino que el identificador de variable no puede ser reasignado, por lo tanto, en el caso de que la asignación a la constante sea un objeto, el objeto si que puede ser alterado.
		
		Una constante no puede compartir su nombre con una función o variable en el mismo ámbito.
		
		[Mozila](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Sentencias/const)

	* **David Antonio Ordóñez Cornejo** [502621] (2)

		Para hacer inmutables tipos estructurados de datos se pueden usar lenses de Ramda, o librerías como immutable.js

* **noemk2** (1) [487721](https://platzi.com/comentario/487721/) 

	Jquery Vs. VanillaJs  
	$(’#description’) Vs. document.getElementById(‘description’)

	* **Nathaly Stefani Riaño Bejarano** [487721] (3)

		Para obtener el valor con VanillaJS:
		``` 
		    let description = document.getElementById('description')
		    console.log(description.value)
		    
		```

	* **Andres Rivera** [487721] (1)

		¿esto también es vanilla: document.querySelector(’#descripcion’) ?

	* **Nathaly Stefani Riaño Bejarano** [487721] (2)

		Hola anriacodg! Si! Esa sintaxis es JavaScript Vanilla

	* **Andres Rivera** [487721] (1)

		Gracias Natha

* **diegoagd10** (1) [52224](https://platzi.com/comentario/502621/) 
Porque no definir las variables como const (Para que sean inmutables)?

	* **Erik Ochoa (Platzi)** [52224] (2)

		Concuerdo, yo las hubiera definido como const, incluso por costrumbre en JQuery antepongo el ‘$’ para saber que son elementos del DOM.
		``` 
		    const $description = $('#description')
		    
		```
		
		No hay ningun problema con usar **let** , pero si creo que son elementos que dificilmente vamos a necesitar que cambien y por eso conviene usar **const**.

## 0070. Objetos y Tipos de Memoria en JavaScript [16797](https://platzi.com/clases/1497-funcional-js/16797-objetos-y-tipos-de-memoria/)

### Descripción:


Un objeto es una referencia a un espacio en memoria, cada vez que creamos un objeto, este se guarda en la memoria (no sabemos exactamente dónde) y podemos acceder a su valor gracias a las coordenadas.

Existen dos tipos de memoria: Stack y Heap.  
La memoria **Stack** es mucho más rápida y nos permite almacenar los datos de forma ““ordenada”” y en JavaScript la utilizamos para guardar datos primitivos, como booleanos, números o _strings_. En cambio, los objetos utilizan la memoria **Heap** , una memoria que nos permite guardar grandes cantidades de información pero con un poco menos de velocidad.

Estos dos conceptos nos van a ayudar mucho a la hora de copiar objetos cuando utilizamos la programación funcional.

### Comentarios:

* **Julio J Yépez** (22) [486531](https://platzi.com/comentario/486531/) 

	En otras palabras, las variables primitivas se almacenan y se acceden _por valor_ , mientras que las variables de tipo objeto se almacenan y acceden _por referencia_.
	
	Es por esta razón que al declarar una constante primitiva no podemos cambiar luego su valor, pero al declarar una constante de tipo objeto, si podemos cambiar en cualquier momento los atributos o propiedades que tiene definidos internamente.

	* **Nathaly Stefani Riaño Bejarano** [486531] (2)

		Que buena observación! No había notado lo de los objetos y sus atributos… así sean declarados constantes

	* **Bryan Estiven Silva Mercado** [486531] (2)

		Muy buen aporte , me queda claro agregado a otra definición que leí hace poco.

	* **David Antonio Ordóñez Cornejo** [486531] (1)

		Exacto

* **Eliseo Geraldo González** (12) [486346](https://platzi.com/comentario/486346/) 

	Los tipos de datos no primitivos, se referencian por memoria, es esta también la razón por la que comparar dos objetos diferentes, con las mismas caraterísticas obtenemos `false`, es decir, en `(object1 === object2)` no se compara el objeto, se compara si se encuentras en la misma posición de memoria.
	``` 
	    const object1 = { value: 10 }
	    const object2 = object1
	    const object3 = { value: 10 }
	    
	    console.log(object1 == object2);
	    // → true
	    console.log(object1 == object3);
	    // → false
	    
	```
	
	Porque…
	``` 
	          +-----------------+------------------+------------------+
	          |     object1     |      object2     |     object3      |
	          +-----------------+------------------+------------------+
	          |||||
	          |   {value: 10} <-----------+        |   {value: 10}    |
	          ||||    
	          +-----------------+------------------+------------------+
	    ```
	```

	* **Carlos Gómez Mont** [486346] (1)

		Gracias por compartir, saludos!!

* **Juan David Castro (Platzi)** (7) [486744](https://platzi.com/comentario/486744/) 

	Notas de la clase:
	
	* 🎳 Los objetos son referencias a un espacio en memoria.
	* 🎩 La mayoría de lenguajes de programación utilizan dos tipos de memorias: **Stack** y **Heap**.
	* 📁 La memoria **Stack** es muy rápida pero sin tanto espacio, aquí guardamos los valores primitivos de nuestras variables (true, false, ‘JuanDC’, 16, etc).
	* 🌪 La memoria **Heap** es un poco más lenta y nos permite guardar grandes cantidades de información (son como los tornados: grandes, lentos y desordenados). En esta memoria guardamos los valores de los objetos (`{...}`).
	
	

	* **Carlos Gómez Mont** [486744] (1)

		Super aporte, gracias!!

* **Juan David Castro (Platzi)** (3) [486745](https://platzi.com/comentario/486745/) 

	* [Does JavaScript use stack or heap for memory allocation or both?](https://hashnode.com/post/does-javascript-use-stack-or-heap-for-memory-allocation-or-both-cj5jl90xl01nh1twuv8ug0bjk) 😬
	
	

	* **edanfesi** [486745] (1)

		Excelente aporte! Gracias.

* **Marco Antonio Macedo Preciado** (3) [66290](https://platzi.com/comentario/705654/) 
¿Las funciones se guardan en stack o en heap? 🤔

	* **Juan David Castro (Platzi)** [66290] (2)

		 **¡Stack!** 😉
		
		👉 <https://medium.com/@muratcatal/understanding-javascript-heap-stack-event-loops-and-callback-queue-6fdec3cfe32e>

* **Juan David Castro (Platzi)** (2) [486742](https://platzi.com/comentario/486742/) 

	En este vídeo nuestro profe **Javier Santaolalla** del [Curso de Matemáticas para Física](https://platzi.com/clases/fisica-matematica/) nos explica muy sencillo qué son y para qué sirven las Matrices:
	
	* [Matrices en el Curso de Matemáticas para Física](https://platzi.com/clases/1447-fisica-matematica/17102-matrices4706/)
	
	

* **juan jose hernandez llamas** (1) [1004052](https://platzi.com/comentario/1004052/) 

	El concepto de stack es más complejo…
	
	"La pila de llamadas, pila de ejecución, pila de función, pila de control, pila de tiempo de ejecución o simplemente call stack es una estructura dinámica de datos que almacena la información sobre las subrutinas activas de un programa en ejecución. Cuando hacemos una llamada a una función, un bloque en el tope de la pila es reservado para guardar las variables locales junto con algunos datos necesarios para garantizar el funcionamiento adecuado de la estructura (como la dirección a la que tendrá que retornar el hilo de ejecución cuando termine la función). Después de retornar, el bloque de la pila que ocupaba el llamado, se libera para poder utilizarse más adelante de ser necesario.
	
	Se llama pila de ejecución porque es una estructura de datos que funciona bajo el concepto de LIFO (last in first out). Esto hace que sea más sencillo mantener el control de los bloques que deben ser liberados, puesto que será aquel que esté en el tope de la pila."
	
	No sé si lo retomes después, pero creo yo, que hubiera sido mejor dejarlo claro desde un inicio,o dejar todo el concepto hasta después y no dejarlo a medias
	
	fuente: <https://codingornot.com/diferencias-entre-heap-y-stack>

	* **platzerito080420202** [1004052] (1)

		y porque estas en el curso? si lo sabes? jaja xd o es solo para validar tu conocimiento y persona??¿?

* **edanfesi** (1) [832457](https://platzi.com/comentario/832457/) 

	Hola chicos, les dejo un resumen que hice (con lo visto en clase y complementando con lecturas que conseguí):
	
	<h3>Stack</h3>
	
	* Una Stack es una región de memoria que opera en modo First-In-Last-Out.
	* Cuando se crea un nuevo thread, puede ser por un programa, se crea una nueva pila.
	* Es pequeña y puede usarse para almacenar de manera rápida y obtener data temporal.
	* La memoria Stack es mucho más rápida y nos permite almacenar los datos de manera “organizada” y en JS la utilizamos para almacena datos primitivos.
	
	<h3>Heap</h3>
	* También es llamado ‘free store’.
	* Es una región grande de memoria que puede ser usado para almacenar data de manera desorganizada y arbitraria.
	* Es usada para estructuras de datos.
	* La información se obtiene a través de referencias.
	
	

## 0080. Copiar y modificar objetos en JavaScript [16796](https://platzi.com/clases/1497-funcional-js/16796-copiar-objetos/)

### Descripción:


En JavaScript tenemos diferentes formas de copiar y modificar elementos o variables, normalmente, basta con asignar dos variables e indicar que la segunda es igual a la primera:
``` 
    let a = 1
    let b = a
    
    console.log(a, b) // 1, 1
    
```

De esta forma podemos copiar el valor de otra variable y realizar modificaciones más adelante:
``` 
    let a = 1
    let b = a
    b += 1
    
    console.log(a, b) // 1, 2
    
```

Sin embargo, todo esto cambia cuando trabajamos con objetos. Así como aprendimos en la clase anterior, los objetos se comportan distinto al resto de datos primitivos dentro de JavaScript.

Cuando asignamos el valor de una variable de tipo objeto a otras variables, en realidad, estamos copiando la referencia al objeto inicial. Esto quiere decir que, a pesar de que modifiquemos la copia de nuestras variables de tipo objeto, en realidad, estamos modificando el objeto original y, por lo tanto, todas las variables con la referencia a este objeto que acabamos de modificar:
``` 
    let car = {
            color: 'red',
            year: 2019,
            km: 0,
    }
    
    let car2 = car
    car2.color = 'blue'
    
    console.log(car, car2) // ambos objetos tienen color azul, no solo `car2`
    
```

En vez de copiar los valores de nuestros objetos, cuando utilizamos el `=` lo que copiamos es la referencia al objeto con sus respectivos valores. Esto lo podemos solucionar utilizando la función `Object.assign`:
``` 
    let car = {
            color: 'red',
            year: 2019,
            km: 0,
    }
    
    let car2 = Object.assign({} , car)
    car2.color = 'blue'
    
    console.log(car, car2) // `car` es de color rojo y `car2` de color azul
    
```

Sin embargo, este método no es suficiente para copiar y modificar objetos con subobjetos por el mismo problema de las referencias. La mejor manera copiar los valores de nuestros objetos en vez de sus referencias es utilizando las funciones `JSON.parse` y `JSON.stringify`:
``` 
    let car = {
            color: 'red',
            year: 2019,
            km: 0,
            owner: {
                    name: 'David',
                    age: 25
            }
    }
    
    let car2 = JSON.parse(JSON.stringify(car))
    car2.owner.age += 1
    
    console.log(car, car2) // el dueño de `car2` es un año mayor al dueño de `car`
    
```

### Comentarios:

* **Julio J Yépez** (17) [486539](https://platzi.com/comentario/486539/) 

	```
	    Object.assign({}, car)
	    
	```
	
	Solo copia los datos por valor en el primer nivel de propiedades, mientras que los objetos de los siguientes niveles son asignados por referencia, de la misma manera que si se hiciera con " = "

	* **Julio J Yépez** [486539] (10)

		Para resolver este problema necesitamos apoyarnos en otros dos métodos de la clase estática JSON de JavaScript: **`.parse()`** y **`.stringify()`**

* **Juan David Castro (Platzi)** (7) [486746](https://platzi.com/comentario/486746/) 

	Esta clase me voló la cabeza. Ya había utilizado `JSON.parse` y `JSON.stringify` pero no tenia ni idea de su utilidad para copiar y modificar objetos y objetos de objetos. ¡Bravo! 👏👏👏
	
	* [JSON.parse() | MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/JSON/parse)
	* [JSON.stringify() | MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/JSON/stringify)
	
	

	* **Gabriel De Andrade (Platzi)** [486746] (3)

		Totalmente de acuerdo! Nunca pensé en esa forma de usar `JSON.parse` y `JSON.stringify` que profe tan cool!

	* **Juan David Castro (Platzi)** [486746] (1)

		* [How to Remove Array Duplicates in ES6](https://medium.com/dailyjs/how-to-remove-array-duplicates-in-es6-5daa8789641c)
		
		

	* **Juan David Castro (Platzi)** [486746] (1)

		* [Aprende a Copiar Objetos en JavaScript sin morir en el intento | Platzi Blog](https://platzi.com/blog/como-copiar-objetos-en-javascript-sin-morir-en-el-intento/)
		
		

* **Juan David Castro (Platzi)** (5) [486747](https://platzi.com/comentario/486747/) 

	* [Spread Operator Does Not Deep Copy Properties](https://bambielli.com/til/2017-01-29-spread-operator-deep-copy/)
	
	

	* **Carlos Gómez Mont** [486747] (1)

		Super aporte, gracias!!

* **Jorge Mendez Ortega** (4) [537886](https://platzi.com/comentario/537886/) 

	`JSON.stringify` realmente recibe 3 parámetros de los cuales son
	
	**value :** Cadena a convertir en JSON.
	
	**replace :** Este parámetro es opcional, Una función que altera el comportamiento del proceso de conversión a cadena de texto
	
	**space :** este puede ser un número el cual determina la identación de la cadena.
	
	[Documentación de `JSON.stringify`](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/JSON/stringify)

* **diegoagd10** (4) [502626](https://platzi.com/comentario/502626/) 

	Esta es otra forma de crear un copia del objeto original:
	``` 
	    let car = { color: 'Black', year: '2019', km: 0 }
	    // Copiando car a newCar sin hacer referencia al mismo pointer
	    let newCar = { ...car }
	    
	```
	
	Referencia:  
	Curso de fundamentos de javascript de Platzi 😃

	* **Cristobal Peña** [502626] (1)

		¿Sabes si esto realmente copia el objeto? Por el Profe Sacha en ese curso hablaba de un objeto “virtual”.
		
		Este es el link de la clase para los interesados
		
		[](https://platzi.com/clases/1339-fundamentos-javascript/12894-parametros-como-referencia-o-como-val-7/)

* **Dgn** (3) [677897](https://platzi.com/comentario/677897/) 

	```
	    let persona = {
	        nombre: 'MAR',
	        apellido: 'AR',
	        edad: 24,
	        datos: {
	            carrera: 'ING'
	        }
	    }
	    
	    let personaCopy = {
	        ...persona,
	        nombre:'JE'
	    }
	    
	    console.log(personaCopy);
	    console.log(persona);
	    
	```

* **Nathaly Stefani Riaño Bejarano** (3) [489780](https://platzi.com/comentario/489780/) 

	El método JSON.stringify() convierte un valor dado en JavaScript a una cadena JSON y El método JSON.parse() analiza una cadena de texto como JSON.

* **raparisg** (2) [546912](https://platzi.com/comentario/546912/) 

	En caso de que tenga un objeto así:
	``` 
	    let car = {
	      color : 'blue',
	      brand : 'bmw',
	      owner : {
	        name : 'Ramón',
	        saludar : () => console.log('Hola mundo')
	      }
	    }
	    
	```
	
	Como vemos, este objeto tiene otro objeto dentro que posee una función “saludar” y si hago un JSON.stringify de este objeto imprime:
	``` 
	    {"color":"blue","brand":"bmw","owner":{"name":"Ramón"}}
	    
	```
	
	¿Cuál es la manera más óptima de copiar este objeto por valor? En este caso es preferible utilizar una clase e ir creando instancias de esta clase? ¿O existe otra manera sin necesidad de crearla?

	* **David Antonio Ordóñez Cornejo** [546912] (3)

		Creo que ma manera mas conveniente es una función factory o apoyarse en una librería como Ramda o Lodash, que hacen deepcopy.

	* **Juan David Castro (Platzi)** [546912] (1)

		Puedes usar un segundo argumento en la función **`JSON.stringify`**. Este se va a encargar de evaluar cada uno de los elementos que va a convertir en string, así que podemos invocar al método **`.toString`** de nuestras funciones para que no perdamos sus funcionalidades cuando las recuperemos con **`JSON.parse`**.
		``` 
		    var obj = {
		      foo: function() {
		        return"I'm a function!";
		      }
		    };
		    
		    var json = JSON.stringify(obj, function(key, value) {
		      if (typeof value === 'function') {
		        return value.toString();
		      } else {
		        return value;
		      }
		    });
		    
		    console.log(json);
		    // {"foo":"function () { return \"I'm a function!\" }"}
		    
		```
		
		Referencia: <https://stackoverflow.com/questions/18089033/json-stringify-does-not-process-object-methods>.

* **Edgar de Jesus Mendoza Ortegon** (2) [528462](https://platzi.com/comentario/528462/) 

	Nunca me había topado con algún problema de querer modificar los valores de un objeto anidado.
	
	vaya que este TRUCO no me lo sabia
	``` 
	    let car = {
	            color: 'red',
	            year: 2019,
	            km: 0,
	            owner: {
	                    name: 'David',
	                    age: 25
	            }
	    }
	    
	    let car2 = JSON.parse(JSON.stringify(car))
	    car2.owner.age += 1
	    
	    console.log(car, car2)
	    
	```

* **jesusmurf** (2) [498224](https://platzi.com/comentario/498224/) 

	Estos conocimientos están muy bien para cuando trabajamos con estados en Redux.

* **elviejomenu** (2) [492357](https://platzi.com/comentario/492357/) 

	La Forma mas efectiva para copiar los objetos es utilizando los métodos :  
	JSON.parse(JSON.stringify(objetoAcopiar))  
	pues nos permitirá copiar todos los niveles que tenga nuestro objeto.  
	Así mismo poder alterarlos.
	``` 
	    let newCar1 = JSON.parse(JSON.stringify(car1));
	    console.log(car1, newCar1);
	    
	    newCar1.year = 2000;
	    newCar1.owner.age = 26;
	    newCar1.owner.name = "Jesusito";
	    console.log(car1, newCar1);
	    
	```

* **asaucedormz** (2) [488195](https://platzi.com/comentario/488195/) 

	let car = {  
	color: ‘red’,  
	km: 0,  
	year: 2019  
	};  
	let newCar = {…car}; // crear una copia de car, utilizando el Spread Operator
	
	<https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Operadores/Spread_operator>

	* **hernan__giraldo** [488195] (3)

		Debemos tener en cuenta que el spread operator, al igual que el Object.assign, sólo copia los datos por valor en el primer nivel de propiedades

	* **asaucedormz** [488195] (1)

		estas en lo correcto es una copia superficial (shallow copy) lo mejor es hacer una copia profunda (deep copy), hay librerías que ayudan mucho a manejar estructuras de datos ya con algoritmos optimizados para cada caso como lodash y underscore.js

* **Julio J Yépez** (2) [486546](https://platzi.com/comentario/486546/) 

	Los problemas que genera el manejo de datos **por referencia** , cuando su valor no puede ser predecible o cuando el comportamiento es inesperado a lo largo del programa, está relacionado con la **mutabilidad de estados**.  
	¡Seguramente lo vemos más adelante!

	* **Carlos Gómez Mont** [486546] (2)

		Gracias por compartir, saludos!!

* **Erik Ricardo Sánchez Pérez** (1) [1105537](https://platzi.com/comentario/1105537/) 

	Al momento de hacer
	``` 
	    JSON.parse(JSON.stringify({}))
	    
	```
	
	si es solo un objeto no hay problema. Les recomiendo esta [lectura](https://medium.com/@pmzubar/why-json-parse-json-stringify-is-a-bad-practice-to-clone-an-object-in-javascript-b28ac5e36521) para que entiendan en que momentos es conveniente hacer eso o hacer un deepclone

* **Miguel Angel Martelo Quiroz** (1) [1080264](https://platzi.com/comentario/1080264/) 

	Cuando tenemos objetos dentro de objetos, `Object.assing()`solo va a copiar los valores del objeto de primer nivel. Para copiar los valores completos de un objeto dentro de otro debemos utilizar `JSON.parse(JSON.stringify(car))`

* **Miguel Angel Martelo Quiroz** (1) [1080249](https://platzi.com/comentario/1080249/) 

	Cuando compiamos objetos, si trabajamos con `newCar = car`, estamos copiando la referencia del objeto, si trabajamos con `newCar = Object.assign({}, car)` copiamos el valor de la variable car (El objeto).

* **Cristobal Peña** (1) [1033564](https://platzi.com/comentario/1033564/) 

	Se puede estudiar JSON en Platzi? Hay algún curso recomendado? Gracias.

* **Cristobal Peña** (1) [1033539](https://platzi.com/comentario/1033539/) 

	En el curso de Fundamentos de Java Script también se tocó este tema. Aqui dejo el enlace:  
	[](https://platzi.com/clases/1339-fundamentos-javascript/12894-parametros-como-referencia-o-como-val-7/)

* **Jhon Alexander Perez Valencia** (1) [617440](https://platzi.com/comentario/617440/) 

	JSON.parse y JSON.stringify:

* **Victor Lozada** (1) [503215](https://platzi.com/comentario/503215/) 

	Me surge una duda, en caso de que dentro de nuestro objecto guardemos una función ejemplo :
	``` 
	    let a = {
	    	b: function(msj){
	    		console.log(msj)
	    	}
	    }
	    
	    
	```
	
	como haríamos para copiar la funcion dentro ? ya que al utilizar `JSON.stringify()` de esta forma
	``` 
	    let a = {
	    	b: function(msj){
	    		console.log(msj)
	    	}
	    }
	    JSON.stringify(a) // "{}" 
	    
	    
	```
	
	retornaríamos un objeto en donde se estarían omitiendo todas las propiedades que tengan como valor una función.

	* **IDavidC** [503215] (3)

		Para tu ejemplo en particular sería con `Object.assign()`:
		``` 
		    let a = {
		    	b: function(msg) {
		    		console.log(msj)
		    	}
		    }
		    console.log(a) // {b: f}
		    
		    let c = Object.assign({}, a)
		    console.log(c) // {b: f}
		    
		```

	* **WilliamVelazquez** [503215] (2)

		Y en el caso de que el objeto tenga dentro otro objeto el cual tenga la función? Cómo sería? Porque si entendí bien en esa situación ya no funcionaría el Object.assign(), no?  
		Saludos!

	* **Juan David Castro (Platzi)** [503215] (1)

		¡Hola! Mira mi respuesta a esta otra pregunta de la clase: <https://platzi.com/comentario/546912/>. 😉

* **juan barreto** (1) [502263](https://platzi.com/comentario/502263/) 

	Excelente curso! esta problematica con los objetos la tuve hace un tiempo cuando no tenia mucha idea de la programación funcional, de a ver tenido este curso antes me hubiese ahorra muchísimos dolores de cabeza

* **raparisg** (1) [55931](https://platzi.com/comentario/546912/) 
En caso de que tenga un objeto así: let car = { color : 'blue', brand : 'bmw', owner : { name : 'Ramón', saludar : ()...

	* **David Antonio Ordóñez Cornejo** [55931] (3)

		Creo que ma manera mas conveniente es una función factory o apoyarse en una librería como Ramda o Lodash, que hacen deepcopy.

* **Victor Lozada** (1) [52282](https://platzi.com/comentario/503215/) 
Me surge una duda, en caso de que dentro de nuestro objecto guardemos una función ejemplo : let a = { b: function(msj){ console....

	* **IDavidC** [52282] (3)

		Para tu ejemplo en particular sería con `Object.assign()`:
		``` 
		    let a = {
		    	b: function(msg) {
		    		console.log(msj)
		    	}
		    }
		    console.log(a) // {b: f}
		    
		    let c = Object.assign({}, a)
		    console.log(c) // {b: f}
		    
		```

## 0090. Utilizando inmutabilidad en nuestras funciones [16798](https://platzi.com/clases/1497-funcional-js/16798-inmutabilidad-en-funciones/)

### Descripción:


Otra característica de las funciones puras es la inmutabilidad. Si necesitamos modificar el valor de los parámetros que reciben nuestras funciones, debemos copiar el valor de los argumentos y modificar estas nuevas variables, así evitamos modificar innecesariamente variables con las que nuestras funciones puras no tienen nada que ver.

Ejemplo:
``` 
    // Con mutaciones
    const addToList = (list, item, quantity) => {
    	list.push({ // modificamos el argumento `list`
    		item,
    		quantity
    	})
    	return list
    }
    
    //  Sin mutaciones (inmutabilidad)
    const addToList = (list, item, quantity) => {
    	const newList = JSON.parse(JSON.stringify(list))
    	newList.push({ // modificamos la copia del argumento
    		item,
    		quantity
    	})
    
    	return newList
    }
    
```

### Comentarios:

* **Julio J Yépez** (15) [486567](https://platzi.com/comentario/486567/) 

	La _inmutabilidad_ en las propiedades o atributos de un objeto es fundamental para poder predecir su comportamiento o valor (estado) en el futuro. Al crear nuevos objetos cambiados (mutados), sin alterar el objeto original, nos aseguramos de estar siendo muy explícitos al hacer modificaciones, reduciendo el riesgo de cambios indeseados o hechos por simple descuido o desconocimiento. Esta característica es especialmente útil en todo lo relacionado a las pruebas de software o _testings_.

	* **Julio J Yépez** [486567] (2)

		Como vimos en clases anteriores, la _inmutabilidad_ se hace particularmente necesaria en el manejo de objetos, ya que estos, por defecto, se están pasando siempre por referencia y no por valor.

	* **Carlos Gómez Mont** [486567] (2)

		Gracias por compartir, saludos!!

* **diegoagd10** (10) [502633](https://platzi.com/comentario/502633/) 

	Otra forma de copiar arreglos en javascript usando ecmascript teniendo en consideracion que la version de actual de chrome ya soporta ecmascript2015:
	``` 
	    const addToList = (list, item, quantity) => [
	      ...list,
	      { item, quantity }
	    ]
	    
	```
	
	**Referencia:**  
	<https://vincent.billey.me/pure-javascript-immutable-array/>

	* **Jorge Mendez Ortega** [502633] (11)

		si pero recuerda que al utilizar `spread operator` solo estamos copiando las referencias del primer nivel por lo que tendriamos algo como esto.
		
		![Captura de pantalla 2019-03-18 a la\(s\) 16.06.43.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-03-18%20a%20la%28s%29%2016.06.43-c6990305-4a06-4469-bf2f-352e596f7f6f.jpg)
		
		Como se puede ver estamos creando una constante llamada `OBJETO_1` y luego creamos una constante llamada `OBJETO_2` en la cual estamos copiando el `OBJETO_1`, al realizar el `console.log` podemos ver que los objetos son iguales, Después cambiamos propiedades del `OBJETO_2` después realizamos nuevamente un `console.log` y podemos ver que en ambos objetos se modificó el nodo info aun que solo lo modificamos en el `OBJETO_2`(para este punto rompemos la condicion de inmutabilidad) esto es por el manejo de las referencias de memoria que se explicaron en el video anterior.
		
		por eso al realizar la copia de objetos se esta utiliza  
		`JSON.parse` y JSON.stringify` ya que al utilizarlos en conjunto permite generar nuevas referencias .

	* **oteka21** [502633] (1)

		Que buen aporte!!

	* **Victor Martin Ortiz Palacio** [502633] (2)

		En la pagina de mdn, hay ejemplos, y advertencias, como la que menciona @konami12jorge, les dejo el enlace por si quieren ver mas ejemplos.
		
		<https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Object/assign#Advertencia_para_clonado_profundol>

* **Juan David Castro (Platzi)** (4) [486748](https://platzi.com/comentario/486748/) 

	* [How to handle immutability in JavaScript](https://gomakethings.com/how-to-handle-immutability-in-javascript/)
	* [Immutability vs Immutable.js - Medium](https://itnext.io/immutable-vs-immutable-js-d524bf515bcd)
	* [What are the benefits of immutability? - Redux FAQ](https://redux.js.org/faq/immutable-data)
	
	

	* **Carlos Gómez Mont** [486748] (1)

		Super aporte, gracias!!

* **Eliseo Geraldo González** (3) [486381](https://platzi.com/comentario/486381/) 

	En programación funcional se trata de no mutar ninguna variable dentro de nuestra aplicación, con el fin de que nuestras funciones sean más transparentes y predecibles.

* **Alejandra Iza** (1) [656424](https://platzi.com/comentario/656424/) 

	usar concat podria ser una mejor alternativa

* **Kingsman7** (1) [642147](https://platzi.com/comentario/642147/) 

	me caí, me levando, me caí y me vuelvo a levantar. wow las cosas que uno se entera.

* **Alfonso Navarro** (1) [497304](https://platzi.com/comentario/497304/) 

	En realidad no veo aun el uso de esta accion pero igualmente es bueno conocer estos conceptos por si en algun momento lo pudiecemos necesitar.

## 0100. Proyecto Validar inputs [16799](https://platzi.com/clases/1497-funcional-js/16799-validar-inputs/)

### Descripción:


### Comentarios:

* **Nathaly Stefani Riaño Bejarano** (14) [490377](https://platzi.com/comentario/490377/) 

	Con VanillaJS:
	``` 
	    let description = document.getElementById('description')
	    let calories = document.getElementById('calories')
	    let carbs = document.getElementById('carbs')
	    let protein = document.getElementById('protein')
	    
	    const validateInputs = () => {
	      description.value ? '' : description.classList.add('is-invalid')
	      calories.value ? '' : calories.classList.add('is-invalid')
	      carbs.value ? '' : carbs.classList.add('is-invalid')
	      protein.value ? '' : protein.classList.add('is-invalid')
	    
	      if(description.value && calories.value && carbs.value && protein.value) {
	        console.log('OK!')
	      }
	    }
	    
	    description.addEventListener('keydown', () => description.classList.remove('is-invalid'))
	    calories.addEventListener('keydown', () => calories.classList.remove('is-invalid'))
	    carbs.addEventListener('keydown', () => carbs.classList.remove('is-invalid'))
	    protein.addEventListener('keydown', () => protein.classList.remove('is-invalid'))
	    
	```

	* **Miguel Herreros Cejas** [490377] (1)

		Muchas gracias por tu aporte. Llevo tiempo sin programar en Jquery y me ha sido de gran utilidad.

* **diegoagd10** (7) [503047](https://platzi.com/comentario/503047/) 

	Mi ejemplo:
	``` 
	    const IS_INVALID = 'is-invalid'
	    
	    const description = document.getElementById('description')
	    const calories = document.getElementById('calories')
	    const carbs = document.getElementById('carbs')
	    const protein = document.getElementById('protein')
	    const inputs = [description, calories, carbs, protein]
	    
	    const isValid = elem => elem.value
	    
	    const isFormValid = () =>
	      isValid(description) && isValid(calories) && isValid(carbs) && isValid(protein)
	    
	    const showInvalid =
	      elem => isValid(elem) ? '' : elem.classList.add(IS_INVALID)
	    
	    const addKeydownEvent = elem =>
	      elem.addEventListener('keydown', () => elem.classList.remove(IS_INVALID))
	    
	    inputs.forEach(addKeydownEvent)
	    
	    const validateInputs = () => {
	      inputs.forEach(showInvalid)
	    
	      if (isFormValid()) {
	        console.log('OK')
	      }
	    }
	    
	```

* **iLuisCastillo** (4) [613142](https://platzi.com/comentario/613142/) 

	Buen video para recordar javascript puro, con frameworks o librerias actualmente el manejo es mas sencillo. Para evitar el uso de JQuery, lo he realizado de otra manera:
	``` 
	    const $ = id => document.getElementById(id);
	    
	    let formInputs = {
	      description: $('description'),
	      calories: $('calories'),
	      carbs: $('carbs'),
	      protein: $('protein'),
	    }
	    
	    const inputEntries = Object.entries(formInputs);
	    
	    const validateInputs = () => {
	      inputEntries.forEach(prop => {
	        if (!prop[1].value) {
	          formInputs[`${prop[0]}`].classList.add('is-invalid');
	        }
	      });
	    
	      if(Object.values(formInputs).every(({ value }) => value)) {
	        alert('All inputs are fill')
	      }
	    }
	    
	    const removeInvalidType = () => {
	      inputEntries.forEach(prop => {
	        prop[1].addEventListener('keypress', () => {
	          formInputs[`${prop[0]}`]
	            .classList
	              .remove('is-invalid')
	        });
	      })
	    }
	    
	    removeInvalidType();
	    
	    
	    
	```
	
	Un saludo a la comunidad 😃!

* **swapuruguay** (4) [492418](https://platzi.com/comentario/492418/) 
Badtante decepcionado del curso, que utilice jQuery en lugar de VanillaJS me desmotiva bastante.

* **ivanruiz__** (3) [585944](https://platzi.com/comentario/585944/) 

	Espero que mi código sirva! Si es así hacédmelo saber y seguiré publicándolo 😃
	``` 
	    const description = $('#description');
	    const carbs = $('#carbs');
	    const calories = $('#calories');
	    const protein = $('#protein');
	    
	    
	    removeIsInvalidOnKeyPress = (...inputs) => {
	      for(let input of inputs) {
	        input.keypress(() => {
	            input.removeClass('is-invalid');
	        })
	      }
	    }
	    
	    removeIsInvalidOnKeyPress(description, carbs, calories, protein);
	    
	    const isInputValid = input => {
	      const inputValue = input.val();
	      
	      if(!inputValue) input.addClass('is-invalid');
	    
	      return Boolean(inputValue);
	    }
	    
	    const inputsAreValid = (...inputs) => {
	      return !inputs
	        .map(input => isInputValid(input))
	        .includes(false) 
	    }
	    
	    const validateInputs = () => {
	      if(inputsAreValid(description, carbs, calories, protein)) {
	        alert('OK')
	      }
	    } ```
	    
	```

* **Gabriel De Andrade (Platzi)** (3) [490904](https://platzi.com/comentario/490904/) 

	El operador ternario también funciona en el último `if` y se escribiría de la siguiente manera
	``` 
	    $description.value && $calories.value && $carbs.value && $proteins.value && console.log('works')
	    
	```
	
	Aunque cabe destacar que es un poco confuso si no se tiene el else por que es el mismo símbolo que la concatenación de condiciones

* **Nicolás Arias** (2) [684082](https://platzi.com/comentario/684082/) 

	También en lugar de usar el operador ternario para añadir las clases podemos usar el operador &&, de la siguiente forma:
	``` 
	    description.val() && description.addClass('is-invalid')
	    
	```
	
	El operador and solo ejecuta lo que está después únicamente si la primera expresión da un [Truthy](https://developer.mozilla.org/es/docs/Glossary/Truthy).

* **juan_prieto_r** (2) [578234](https://platzi.com/comentario/578234/) 

	Mi aporte 😃
	``` 
	    let validaInput = document.querySelector('.mb-2').addEventListener('click', () => {
	      let description = document.getElementById('description');
	      let calories = document.getElementById('calories');
	      let carbs = document.getElementById('carbs');
	      let protein = document.getElementById('protein');
	    
	      description.value ? '' : description.classList.add('is-invalid'), description.classList.add('is-valid');
	      calories.value ? '' : calories.classList.add('is-invalid'), calories.classList.add('is-valid');
	      carbs.value ? '' : carbs.classList.add('is-invalid'), carbs.classList.add('is-valid');
	      protein.value ? '' : protein.classList.add('is-invalid'), protein.classList.add('is-valid');
	    
	      description.addEventListener('keypress', () => { description.classList.remove('is-invalid');});
	      calories.addEventListener('click', () => { description.classList.remove('is-invalid');});
	      carbs.addEventListener('click', () => { carbs.classList.remove('is-invalid');});
	      protein.addEventListener('click', () => { protein.classList.remove('is-invalid');});
	    
	      if(description.value  && calories.value && carbs.value && protein.value) {
	        console.log('ok');
	      }
	    
	    });```
	    
	```

* **David Antonio Ordóñez Cornejo** (2) [546379](https://platzi.com/comentario/546379/) 

	Intentando ser muy funcional:
	``` 
	    const compose = (...functions) => data => functions.reduceRight((value, func) => func(value), data)
	    
	    let $description = document.querySelector('#description')
	    let $calories = document.querySelector('#calories')
	    let $carbs = document.querySelector('#carbs')
	    let $proteins = document.querySelector('#proteins')
	    let $addButton = document.querySelector('#add-button')
	    
	    var trackInput = ($input) => {
	      setTimeout(() => {
	        $input.value !== '' ? $input.classList.remove('is-invalid') : $input.classList.add('is-invalid')
	      }, 200)
	    }
	    
	    $description.addEventListener('keypress', trackInput.bind(null, $description))
	    $calories.addEventListener('keypress', trackInput.bind(null, $calories))
	    $carbs.addEventListener('keypress', trackInput.bind(null, $carbs))
	    $proteins.addEventListener('keypress', trackInput.bind(null, $proteins))
	    
	    const validateInputs = ($inputs) => $inputs.forEach(trackInput)
	    const validateForm = validateInputs.bind(null, [$description, $calories, $carbs, $proteins])
	    const processInputs = ($inputs, calllback) => {
	      const flag = $inputs.every($input => $input.value !== '')
	      flag === true ? $inputs.forEach($input => { console.log($input.value) }) : console.log('Skipping')
	    }
	    
	    const processForm = processInputs.bind(null, [$description, $calories, $carbs, $proteins], console.log)
	    const manageCaloriesForm = compose(validateForm, processForm)
	    $addButton.addEventListener('click', manageCaloriesForm)
	    
	```

* **David Antonio Ordóñez Cornejo** (2) [546359](https://platzi.com/comentario/546359/) 

	Mi aporte:
	``` 
	    const compose = (...functions) => data =>
	      functions.reduceRight((value, func) => func(value), data)
	    
	      // DOM elements
	    let $description = document.querySelector('#description')
	    let $calories = document.querySelector('#calories')
	    let $carbs = document.querySelector('#carbs')
	    let $proteins = document.querySelector('#proteins')
	    let $addButton = document.querySelector('#add-button')
	    
	    // Update an input field depending of input value
	    var trackInput = ($input) => {
	      setTimeout(() => {
	        if ($input.value !== '') {
	          $input.classList.remove('is-invalid')
	        }
	      }, 250)
	    }
	    
	    // Add handlers to validate keypresses
	    $description.addEventListener('keypress', trackInput.bind(null, $description))
	    $calories.addEventListener('keypress', trackInput.bind(null, $calories))
	    $carbs.addEventListener('keypress', trackInput.bind(null, $carbs))
	    $proteins.addEventListener('keypress', trackInput.bind(null, $proteins))
	    
	    // Validate a list of input fields
	    const validateInputs = ($inputs) => {
	      $inputs.forEach($input => {
	        if ($input.value === '') {
	          $input.classList.add('is-invalid')
	        } else {
	          $input.classList.remove('is-invalid')
	        }
	      })
	    }
	    
	    // Bind inputs before to make the function point free
	    const validateForm = validateInputs.bind(null, [$description, $calories, $carbs, $proteins])
	    
	    // Process the inputs
	    const processInputs = ($inputs, calllback) => {
	      const flag = $inputs.every($input => $input.value !== '')
	      if (flag === true) {
	        $inputs.forEach($input => { console.log($input.value) })
	      }
	    }
	    
	    // Bind inputs before to make the function point free
	    const processForm = processInputs.bind(null, [$description, $calories, $carbs, $proteins], console.log)
	    
	    // Compose validateForm and ProcessForm in one general event handler
	    const manageCaloriesForm = compose(validateForm, processForm)
	    
	    // Add the composed handler to validate and process the form
	    $addButton.addEventListener('click', manageCaloriesForm)
	    
	```

* **Jorge Mendez Ortega** (2) [538541](https://platzi.com/comentario/538541/) 

	Para todos los que no queremos utilizar `jQuery` podrias intentar generar la practica usando `JS` puro también conocido como `VanillaJS`, les comparto el ejemplo que estoy realizando sin utilizar `jQuery` se que varios están haciendo lo mismo.
	``` 
	    const compose = (...functions) => data =>
	        functions.reduceRight((value, func) => func(value), data)
	    
	    // Se utiliza $ para identificar que una variable o constante hace referencia 
	    // a elementos del DOM
	    const $DESCRIPTION = document.getElementById("description");
	    const $CALORIAS = document.getElementById("calorias");
	    const $CARBOIDRATOS = document.getElementById("carboidratos");
	    const $PROTEINAS = document.getElementById("proteinas");
	    const ERROR_CLASS = "is-invalid";
	    
	    // Asignacion de evntos siempre que se desea asignar un evento aun elemento del DOM
	    // es necesario utilizar addEventListener
	    $DESCRIPTION.addEventListener("keypress", () => $DESCRIPTION.classList.remove(ERROR_CLASS));
	    $CALORIAS.addEventListener("keypress", () => $CALORIAS.classList.remove(ERROR_CLASS));
	    $CARBOIDRATOS.addEventListener("keypress", () => $CARBOIDRATOS.classList.remove(ERROR_CLASS));
	    $PROTEINAS.addEventListener("keypress", () => $PROTEINAS.classList.remove(ERROR_CLASS));
	    
	    // funcion para validar los inputs
	    const validateInputs = () => {
	        // Por cuestion de buenas practicas el resultado de una condición
	        // Ternaria tiene que ser asignada a una variable o constante
	        const DESCRIPTION_CLASS = (($DESCRIPTION.value) ? "" : ERROR_CLASS);
	        $DESCRIPTION.classList.add(DESCRIPTION_CLASS);
	    
	        const CALORIAS_CLASS = (($CALORIAS.value) ? "" : ERROR_CLASS);
	        $CALORIAS.classList.add(CALORIAS_CLASS);
	    
	        const CARBOIDRATOS_CLASS = (($CARBOIDRATOS.value) ? "" : ERROR_CLASS);
	        $CARBOIDRATOS.classList.add(CARBOIDRATOS_CLASS);
	    
	        const PROTEINAS_CLASS = (($PROTEINAS.value) ? "" : ERROR_CLASS);
	        $PROTEINAS.classList.add(PROTEINAS_CLASS);
	    
	        if ($DESCRIPTION.value && $CALORIAS.value && $CARBOIDRATOS.value && $PROTEINAS.value) {
	            console.log("Oki Doki");
	        }
	    };
	    
	```

* **onlinejaime** (2) [493228](https://platzi.com/comentario/493228/) 

	Mi aportación, con bonito efecto UX:
	
	* Primero, poned como id del h1 ‘counter’:
	
	
	
	<div class=“card-header”>  
	<h1 id=“counter”>Calories Counter</h1>  
	</div>
	
	* Segundo:
	
	
	
	let description = $(’#description’) // id’s de los inputs  
	let calories = $(’#calories’)  
	let carbs = $(’#carbs’)  
	let protein = $(’#protein’)
	
	calories.keypress(() =>{  
	calories.removeClass(‘is-invalid’)  
	counter.innerHTML=counter.innerHTML==“Por favor, inserta datos”?“Calories Counter”:“Calories Counter”  
	})
	
	carbs.keypress(() =>{  
	carbs.removeClass(‘is-invalid’)  
	counter.innerHTML=counter.innerHTML==“Por favor, inserta datos”?“Calories Counter”:“Calories Counter”  
	})
	
	description.keypress(() =>{  
	description.removeClass(‘is-invalid’)  
	counter.innerHTML=counter.innerHTML==“Por favor, inserta datos”?“Calories Counter”:“Calories Counter”  
	})
	
	protein.keypress(() =>{  
	protein.removeClass(‘is-invalid’)  
	counter.innerHTML=counter.innerHTML==“Por favor, inserta datos”?“Calories Counter”:“Calories Counter”  
	})
	
	const validateInputs = () => {  
	description.val() ? ‘’ : description.addClass(‘is-invalid’)  
	calories.val() ? ‘’ : calories.addClass(‘is-invalid’)  
	carbs.val() ? ‘’ : carbs.addClass(‘is-invalid’)  
	protein.val() ? ‘’ : protein.addClass(‘is-invalid’)  
	description.val() ? ‘’ : counter.innerHTML=counter.innerHTML==“Calories Counter”?“Por favor, inserta datos”:"Por favor, inserta datos"  
	calories.val() ? ‘’ : counter.innerHTML=counter.innerHTML==“Calories Counter”?“Por favor, inserta datos”:"Por favor, inserta datos"  
	carbs.val() ? ‘’ : counter.innerHTML=counter.innerHTML==“Calories Counter”?“Por favor, inserta datos”:"Por favor, inserta datos"  
	protein.val() ? ‘’ : counter.innerHTML=counter.innerHTML==“Calories Counter”?“Por favor, inserta datos”:“Por favor, inserta datos”  
	}

* **devdanielgo** (2) [492294](https://platzi.com/comentario/492294/) 

	No esta más decir que el callback, reultado de evento de escribir dentro de un input devuleve this en el caso de jQuery y event en el caso de Vanilla, por lo que no es necesario volver a escribir el nombre del input para quitarle la clase:
	``` 
	    const compose = (...functions) => data =>
	      functions.reduceRight((value, func) => func(value), data)
	    
	      let $description = $('#description');
	      let $carbs = $('#carbs');
	      let $calories = $('#calories');
	      let $protein = $('#protein');
	    
	    
	      $description.bind('input', function(){
	        $(this).removeClass('is-invalid');
	      })
	    
	      $carbs.bind('input', function(){
	        $(this).removeClass('is-invalid');
	      })
	    
	      $calories.bind('input', function(){
	        $(this).removeClass('is-invalid');
	      })
	    
	      $protein.bind('input', function(){
	        $(this).removeClass('is-invalid');
	      })
	    
	      const  validateInputs = () => {
	        $description.val() ? '': $description.addClass('is-invalid');
	        $carbs.val() ? '': $carbs.addClass('is-invalid');
	        $calories.val() ? '': $calories.addClass('is-invalid');
	        $protein.val() ? '': $protein.addClass('is-invalid');
	    
	        if($description.val() && $carbs.val() && $calories.val() && $protein.val()){
	          console.log('ok');
	        }
	      }
	    
	```

* **noemk2** (2) [489605](https://platzi.com/comentario/489605/) 

	para Vanilla: classList.add()  
	para Jquery: addClass()

* **aragonesteban (Platzi)** (2) [489601](https://platzi.com/comentario/489601/) 

	Podemos reducir los keypress removiendo los corchetes de cada arrow function 😊![](https://firebasestorage.googleapis.com/v0/b/login-ionic-app.appspot.com/o/onkeypress.png?alt=media&token=27f2ff15-9b81-4370-ab35-ef742aaf8ba7)

* **Flavio Moises Salinas Cari** (1) [1019744](https://platzi.com/comentario/1019744/) 

	queda mejor, para mi.
	
	description.val() && description.addClass(‘is-invalid’);

* **edanfesi** (1) [836591](https://platzi.com/comentario/836591/) 

	Hola chicos, les dejo mi código:
	``` 
	    const compose = (...functions) => data =>
	      functions.reduceRight((value, func) => func(value), data)
	    
	    let description = document.getElementById('description');
	    let calories = document.getElementById('calories');
	    let carbs = document.getElementById('carbs');
	    let protein = document.getElementById('protein');
	    
	    description.onkeypress = () => {
	      description.classList.remove('is-invalid');
	    };
	    
	    calories.onkeypress = () => {
	      calories.classList.remove('is-invalid');
	    }
	    
	    carbs.onkeypress = () => {
	      carbs.classList.remove('is-invalid');
	    }
	    
	    protein.onkeypress = () => {
	      protein.classList.remove('is-invalid');
	    }
	    
	    const validateInputs = () => {
	      description.value ? '' : description.classList.add('is-invalid');
	      calories.value ? '' : calories.classList.add('is-invalid');
	      carbs.value ? '' : carbs.classList.add('is-invalid');
	      protein.value ? '' : protein.classList.add('is-invalid');
	    
	      if (description.value && calories.value && carbs.value && protein.value) {
	        console.log('ok');
	      }
	    }
	    
	```

	* **Gabriel De Andrade (Platzi)** [836591] (1)

		Hola! Está cool, pero no utilizaría `let` en el código pues no hay razón para usarlo y en programación funcional lo mejor es usar constantes siempre 😄

* **David Franco** (1) [660159](https://platzi.com/comentario/660159/) 

	```
	    const compose = (...functions) => data =>
	        functions.reduceRight((value, func) => func(value), data)
	    
	    const description = document.getElementById("description");
	    const calories = document.getElementById("calories");
	    const carbs = document.getElementById("carbs");
	    const protein = document.getElementById("protein");
	    
	    description.addEventListener('keypress', () => {
	        description.classList.remove('is-invalid')
	    })
	    calories.addEventListener('keypress', () => {
	        calories.classList.remove('is-invalid')
	    })
	    carbs.addEventListener('keypress', () => {
	        carbs.classList.remove('is-invalid')
	    })
	    protein.addEventListener('keypress', () => {
	        protein.classList.remove('is-invalid')
	    })
	    
	    const validateInputs = () => {
	    
	        description.value ? '' : description.classList.add('is-invalid'), description.classList.add('is-valid')
	        calories.value ? '' : calories.classList.add('is-invalid'), calories.classList.add('is-valid')
	        carbs.value ? '' : carbs.classList.add('is-invalid'), carbs.classList.add('is-valid')
	        protein.value ? '' : protein.classList.add('is-invalid'), protein.classList.add('is-valid')
	    
	        if (description.value && calories.value && carbs.value && protein.value) {
	            console.log('ok');
	        }
	    }
	    
	    
	```
	
	<code>
	``` 
	    
	    
	```

	* **luis-fernando-yupanqui-taco** [660159] (2)

		const compose = (…functions) => data =>  
		functions.reduceRight((value, func) => func(value), data)
		
		El compose para que sirve , ademas de los …

* **swapuruguay** (1) [492417](https://platzi.com/comentario/492417/) 
Bastante decepcionado del curso, que utilice jQuery en lugar de VanillaJS d

* **asaucedormz** (1) [488384](https://platzi.com/comentario/488384/) 

	```
	    const compose = (...functions) => data =>
	      functions.reduceRight((value, func) => func(value), data)
	    
	    
	    description.onkeypress = () => {
	      description.classList.remove('is-invalid');
	    }
	    
	    carbs.onkeypress = () => {
	      carbs.classList.remove('is-invalid');
	    }
	    
	    calories.onkeypress = () => {
	      calories.classList.remove('is-invalid');
	    }
	    
	    protein.onkeypress = () => {
	      protein.classList.remove('is-invalid');
	    }
	    
	    const validateInputs = () => {
	      description.value ? '' : description.classList.add('is-invalid');
	      carbs.value ? '' : carbs.classList.add('is-invalid');
	      calories.value ? '' : calories.classList.add('is-invalid');
	      protein.value ? '' : protein.classList.add('is-invalid');
	    
	      if (description.value && carbs.value && calories.value && protein.value) {
	        console.log('OK');
	      }
	    }
	    
	```

* **nodezi** (1) [486515](https://platzi.com/comentario/486515/) 

	let inputs = document.getElementsByTagName(‘input’)  
	let btn = document.getElementById(‘btn’)  
	let con = 0
	
	let validInput = () => {  
	con = 0  
	for (let input of inputs) {  
	input.addEventListener(“keypress”,validKeyPress)  
	addClassInvalid(input)  
	}
	``` 
	    if(con == 4){
	         console.log("todo esta ok")
	    }else{
	         console.log("algo esta mal")
	    }
	    
	```
	
	}
	
	let validKeyPress = (e) => {  
	e.target.classList.remove(‘is-invalid’)  
	}
	
	let addClassInvalid = (input) => {  
	if(input.value == “”){  
	input.classList.add(“is-invalid”)  
	con–  
	}else{  
	con++  
	input.classList.remove(“is-invalid”)  
	}  
	}
	
	btn.addEventListener(‘click’,validInput)

	* **Carlos Gómez Mont** [486515] (1)

		Gracias por compartir, saludos!!

# Estado compartido en funciones [3341]

## 0110. Estado compartido o shared state [16801](https://platzi.com/clases/1497-funcional-js/16801-shared-state/)

### Descripción:


Shared State significa que diferentes métodos trabajan a partir de una misma variable. y, así como aprendimos en clases anteriores, cuando modificamos variables con el mismo objeto de referencia podemos encontrarnos con algunos problemas y obtener resultados inesperados a pesar de ejecutar el mismo código y recibir los mismos parámetros:
``` 
    // Intento #1
    const a = {
            value: 2
    }
    
    const addOne = () => a.value += 1
    const timesTwo = () => a.value *= 2
    
    addOne()
    timesTwo()
    
    console.log(a.value) // 6
    
    // Sin embargo, si ejecutamos las mismas funciones en orden invertido
    // obtenemos resultados diferentes
    
    timesTwo()
    addOne()
    
    console.log(a.value) // 5 !??
    
```

Para resolver este tipo de problemas debemos utilizar la programación funcional, en vez de modificar la variable original, nuestras funciones deben copiar y modificar sus argumentos:
``` 
    const b = {
            value: 2
    }
    
    const addOne = x => Object.assign({}, x, { value: x.value + 1 })
    const timesTwo = x => Object.assign({}, x, { value: x.value * 2 })
    
    addOne(b)
    timesTwo(b)
    
    // El resultado siempre es el mismo a pesar de
    // ejecutar las funciones en orden diferente
    
    timesTwo(b)
    addOne(b)
    
    console.log(b.value)
    
```

### Comentarios:

* **Gilberto Asuaje** (2) [888368](https://platzi.com/comentario/888368/) 

	```
	    console.log(addOne(timesTwo(b))) // imprime 5
	    
	```
	
	debido a que se ejecuta promero `timesTwo()` va ejeceutando de adentro hacia afuera de los paréntesis

* **bryan.a.sanchez.98** (2) [491689](https://platzi.com/comentario/491689/) 

	<https://dev.to/aligoren/javascript-repositories-i-follow-1fa8>

* **Alirio Alejandro Angel Arenas** (2) [78136](https://platzi.com/comentario/915802/) 
que tanto afecta el rendimiento de la app si se sobre usara el metodo de inmutabilidad? como determinar correctamente cuando debemos hace...

	* **Gabriel De Andrade (Platzi)** [78136] (1)

		Hey, hice un tuto sobre esto [Estructura de Datos inmutables](https://platzi.com/tutoriales/1642-javascript-profesional/4559-estructuras-de-datos-inmutables/) 😄

* **lizardojara** (1) [878295](https://platzi.com/comentario/878295/) 

	Estos temas son muy interesantes.

* **Carol Estefanny Masmela Escamilla** (0) [910963](https://platzi.com/comentario/910963/) 

	Que diferencia hay entre el Object.assign y el spread syntax(…) para crear copias de los objetos?

	* **gorydev** [910963] (1)

		Puedes leer acerca de ambos aquí: <https://thecodebarbarian.com/object-assign-vs-object-spread.html>

## 0120. Proyecto Agregar elementos a la lista [16800](https://platzi.com/clases/1497-funcional-js/16800-agregar-elementos-a-la-lista/)

### Descripción:


### Comentarios:

* **Julio J Yépez** (8) [486592](https://platzi.com/comentario/486592/) 

	El estilo usado por el profesor para definir funciones como constantes y no como functions se llama regularmente en JavaScript: arrow function, aunque en términos más generales también las podemos encontrar como funciones lambda y es una característica introducida por EcmaScript.

	* **Julio J Yépez** [486592] (2)

		Acá un poco más sobre este tipo de funciones:
		
		* <https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Funciones/Arrow_functions>
		* <https://hacks.mozilla.org/2015/06/es6-in-depth-arrow-functions/>
		
		

	* **Carlos Gómez Mont** [486592] (2)

		Gracias por compartir, saludos!!

	* **Gonzalo Ferrando** [486592] (1)

		Muy bueno!

* **edanfesi** (4) [836652](https://platzi.com/comentario/836652/) 

	Si no quieren utilizar parseInt pueden colocar ‘+’ antes y les hará el cast a entero:
	``` 
	    const newItem = {
	        description: description.value,
	        calories: +calories.value,
	        carbs: +carbs.value,
	        protein: +protein.value,
	      }```
	    
	```

* **jbarriospd** (4) [603543](https://platzi.com/comentario/603543/) 

	Dejo mi aporte, codigo en JS puro
	``` 
	    const compose = (...functions) => data => functions.reduceRight((value, func)=> func (value), data)
	    
	    const description = document.getElementById("description");
	    const calorias = document.getElementById("calories");
	    const carbohidratos = document.getElementById("carbs");
	    const proteinas = document.getElementById("protein");
	    const button = document.getElementById('buttonplus')
	    
	    const IS_INVALID = 'is-invalid'
	    const inputs = [description,calorias,carbohidratos,proteinas]
	    
	    letlist = []
	    
	    // si parametro(las variables) que pase por la función tiene un valor, es valido
	    
	    const isValid = elem => elem.value
	    
	    // El formulario será valido cuando todos los argumentos de cada funcion tenga un valor (estos ya pasaron para ser
	     // validados en la funcion anterior)
	    const isFormValid = () => isValid(description) && isValid(calorias) && isValid(carbohidratos) && isValid(proteinas)
	    
	    // si el parametro que se pase por esta funcion tiene no tiene valor: '' (comprobado por la funcion isValid) 
	    // entonces agregale una clase que se llame 'is-invalid'
	    const showInvalid = elem => isValid(elem) ? '' : elem.classList.add(IS_INVALID)
	    
	    // el elemento que pase por la funcion se le pondrá un evento al digitar una tecla, cuando esto suceda se le quitara la clase is-invalid'
	    const addKeyDownEvent = elem => elem.addEventListener('keydown', ()=> elem.classList.remove(IS_INVALID))
	    
	    // recorre la funcion addKeyDownEvent poniendole los nombres de los inputs del array
	    inputs.forEach(addKeyDownEvent)
	    
	    // recorra los elementos del array en la funcion showInvalid y luego si la condicion de la funcion isFormValid 
	    // se cumple (Todos los imput tiene algun valor) realiza la funcion add()
	    const validateInputs = () => {
	    
	        inputs.forEach(showInvalid)
	    
	        if(isFormValid()) {
	            add()
	        }
	    }
	    
	    // adiciona los valores del formulario al array vacio list y despues limpia el formulario
	    const add = () => {
	      const newItem = {
	        description: description.value,
	        calorias: calorias.value,
	        carbohidratos: carbohidratos.value,
	        proteinas: proteinas.value,
	      }
	        list.push(newItem)
	        cleanInputs()
	        console.log(list)
	    }
	    
	    // Limpia el formulario
	    const cleanInputs = () => {
	        description.value =''
	        calorias.value =''
	        carbohidratos.value =''
	        proteinas.value =''
	    }
	    
	```

	* **José Agustin Rios** [603543] (1)

		Flaco, gracias

* **asaucedormz** (3) [488396](https://platzi.com/comentario/488396/) 

	igual en lugar de list.push() se puede hacer uso del spread operator  
	list = […list, newItem]
	``` 
	     const compose = (...functions) => data =>
	      functions.reduceRight((value, func) => func(value), data)
	    
	    
	    description.onkeypress = () => {
	      description.classList.remove('is-invalid')
	    }
	    
	    carbs.onkeypress = () => {
	      carbs.classList.remove('is-invalid')
	    }
	    
	    calories.onkeypress = () => {
	      calories.classList.remove('is-invalid')
	    }
	    
	    protein.onkeypress = () => {
	      protein.classList.remove('is-invalid')
	    }
	    
	    let list = [];
	    
	    const validateInputs = () => {
	      description.value ? '' : description.classList.add('is-invalid')
	      carbs.value ? '' : carbs.classList.add('is-invalid')
	      calories.value ? '' : calories.classList.add('is-invalid')
	      protein.value ? '' : protein.classList.add('is-invalid')
	    
	      if (description.value && carbs.value && calories.value && protein.value) {
	        add()
	      }
	    }
	    
	    const add = () => {
	      const newItem = {
	        description: description.value,
	        calories: parseInt(calories.value),
	        carbs: parseInt(carbs.value),
	        protein: parseInt(protein.value)
	      }
	    
	      list = [...list, newItem]
	      cleanInputs()
	      console.log(list)
	    }
	    
	    const cleanInputs = () => {
	      description.value = ''
	      carbs.value = ''
	      calories.value = ''
	      protein.value = ''
	    }
	    
	```

* **mario-salinas** (2) [488572](https://platzi.com/comentario/488572/) 

	Si alguien prefiere usar VanillaJS así pueden limpiar los campos  
	let cleanInputs = () => {  
	description.value = ''  
	calories.value = 0  
	carbs.value = 0  
	protein.value = 0  
	}

	* **beaps** [488572] (3)

		A los otros campos también les puse un string vacío porque entonces te sustituye el valor del placeholder por un 0
		``` 
		    const cleanInputs = () => {
		      description.value = "";
		      carbs.value = "";
		      calories.value = "";
		      protein.value = "";
		    };
		    
		    
		```

* **Brayan Murcia Sanchez** (2) [58952](https://platzi.com/comentario/584472/) 
profe una pregunta, si quisiera editar uno de los elementos como selecciono el item del array, pues lo hice recorriendo el array con un f...

	* **Ana Lima (Platzi)** [58952] (2)

		¡Hola!
		
		En caso de que solamente quieras modificar un valor, no te recomiendo usar un ciclo para hacer eso.
		
		Como buenas prácticas, te recomiendo que utilices los ciclos cuando vayas a realizar modificaciones en 2 o más elementos.

* **GABRIVP** (1) [751124](https://platzi.com/comentario/751124/) 

	Para agregar los nuevos elementos a la lista no debería ser de forma inmutable también?

* **Brayan Murcia Sanchez** (1) [584472](https://platzi.com/comentario/584472/) 

	profe una pregunta, si quisiera editar uno de los elementos como selecciono el item del array, pues lo hice recorriendo el array con un for, pero tengo esa sensación de que no es la forma optima de hacerlo
	``` 
	    for (var i inlist) {
	         if (list[i].value == value) {
	            list[i].desc = desc;
	            break; 
	         }
	       }
	    
	```

	* **Ana Lima (Platzi)** [584472] (2)

		¡Hola!
		
		En caso de que solamente quieras modificar un valor, no te recomiendo usar un ciclo para hacer eso.
		
		Como buenas prácticas, te recomiendo que utilices los ciclos cuando vayas a realizar modificaciones en 2 o más elementos.

	* **Fernando Alejandro Yerena Ramos** [584472] (2)

		Puedes utilizar el método `.filter()`  
		Lo que hará es devolverte un _array_ con los elementos que cumplan con la condición que decidas.
		``` 
		    	letitem = list.filter(currentItem => currentItem == value)
		    
		```
		
		Te recomiendo estas lecturas con respecto al tema:
		
		* [Array.prototype.filter()](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array/filter)
		* [JavaScript — Learn to Chain Map, Filter, and Reduce](https://codeburst.io/javascript-learn-to-chain-map-filter-and-reduce-acd2d0562cd4)
		* [Learn & Understand JavaScript’s Filter Function](https://codeburst.io/learn-understand-javascripts-filter-function-bde87bce206)
		
		

* **pecaspersonalizados** (1) [567394](https://platzi.com/comentario/567394/) 

	¿la función cleanInputs es una función pura?

	* **aragonesteban (Platzi)** [567394] (4)

		Hola, `clearInputs()` no es una función pura ya que depende de factores externos como los inputs para efectuar su ejecución, además no recibe argumentos para trabajar con ellos y retornar un valor predecible.  
		Te dejo un concepto rápido de las funciones puras:  
		**Las funciones puras no dependen de factores externos y son predecibles, trabajan con los argumentos que asignamos y siempre devuelve el mismo resultado dependiendo de los argumentos pasados.**

* **Jorge Mendez Ortega** (1) [538596](https://platzi.com/comentario/538596/) 

	Por si le funciona a le funciona dejo mi ejemplo donde estoy utilizando `JS` puro sin utilizar`jQuery`
	``` 
	    const compose = (...functions) => data => functions.reduceRight((value, func) => func(value), data);
	    
	    // Se utiliza $ para identificar que una variable o constante hace referencia
	    // a elementos del DOM
	    const $DESCRIPTION = document.getElementById("description");
	    const $CALORIAS = document.getElementById("calorias");
	    const $CARBOIDRATOS = document.getElementById("carboidratos");
	    const $PROTEINAS = document.getElementById("proteinas");
	    const ERROR_CLASS = "is-invalid";
	    const SUCCESS_CLASS = "is-valid";
	    
	    // Arreglo de elementos
	    const LIST = [];
	    
	    
	    // Asignacion de evntos siempre que se desea asignar un evento aun elemento del DOM
	    // es necesario utilizar addEventListener
	    $DESCRIPTION.addEventListener("keypress", () => $DESCRIPTION.classList.remove(ERROR_CLASS));
	    $CALORIAS.addEventListener("keypress", () => $CALORIAS.classList.remove(ERROR_CLASS));
	    $CARBOIDRATOS.addEventListener("keypress", () => $CARBOIDRATOS.classList.remove(ERROR_CLASS));
	    $PROTEINAS.addEventListener("keypress", () => $PROTEINAS.classList.remove(ERROR_CLASS));
	    
	    // Limpiando inputs
	    const cleanInputs = () => {
	        $DESCRIPTION.classList.remove(SUCCESS_CLASS);
	        $DESCRIPTION.value = "";
	        $CALORIAS.classList.remove(SUCCESS_CLASS);
	        $CALORIAS.value = "";
	        $CARBOIDRATOS.classList.remove(SUCCESS_CLASS);
	        $CARBOIDRATOS.value = "";
	        $PROTEINAS.classList.remove(SUCCESS_CLASS);
	        $PROTEINAS.value = "";
	    };
	    
	    // Agregar elementos en la lista
	    const addElement = () => {
	        const newItem = {
	            description: $DESCRIPTION.value,
	            calorias: $CALORIAS.value,
	            carboidratos: $CARBOIDRATOS.value,
	            proteinas: $PROTEINAS.value,
	        };
	        LIST.push(newItem);
	        cleanInputs();
	    };
	    
	    // funcion para validar los inputs
	    const validateInputs = () => {
	        // Por cuestion de buenas practicas el resultado de una condición
	        // Ternaria tiene que ser asignada a una variable o constante
	        const DESCRIPTION_CLASS = (($DESCRIPTION.value) ? SUCCESS_CLASS : ERROR_CLASS);
	        $DESCRIPTION.classList.add(DESCRIPTION_CLASS);
	    
	        const CALORIAS_CLASS = (($CALORIAS.value) ? SUCCESS_CLASS : ERROR_CLASS);
	        $CALORIAS.classList.add(CALORIAS_CLASS);
	    
	        const CARBOIDRATOS_CLASS = (($CARBOIDRATOS.value) ? SUCCESS_CLASS : ERROR_CLASS);
	        $CARBOIDRATOS.classList.add(CARBOIDRATOS_CLASS);
	    
	        const PROTEINAS_CLASS = (($PROTEINAS.value) ? SUCCESS_CLASS : ERROR_CLASS);
	        $PROTEINAS.classList.add(PROTEINAS_CLASS);
	    
	        if ($DESCRIPTION.value && $CALORIAS.value && $CARBOIDRATOS.value && $PROTEINAS.value) {
	            addElement();
	        }
	    };
	    
	```

* **eddyarellanes** (1) [489480](https://platzi.com/comentario/489480/) 

	En este ejemplo, ¿No sería más correcto en la función add, mandar como parámetro la descripción, calorías y proteínas. Porque de otra manera no se está aplicando el concepto de funciones puras.

	* **Revés Estal** [489480] (2)

		Seria igual, ya que la función add esta tomando es el valor de la propiedad value, que retorna un string. En ningún momento se usa la referencia a un objeto.

* **pecaspersonalizados** (1) [57629](https://platzi.com/comentario/567394/) 
¿la función cleanInputs es una función pura?

	* **aragonesteban (Platzi)** [57629] (4)

		Hola, `clearInputs()` no es una función pura ya que depende de factores externos como los inputs para efectuar su ejecución, además no recibe argumentos para trabajar con ellos y retornar un valor predecible.  
		Te dejo un concepto rápido de las funciones puras:  
		**Las funciones puras no dependen de factores externos y son predecibles, trabajan con los argumentos que asignamos y siempre devuelve el mismo resultado dependiendo de los argumentos pasados.**

# Composición de funciones, Closures y Currying [3342]

## 0130. Funciones compuestas o Function Composition [16803](https://platzi.com/clases/1497-funcional-js/16803-function-composition/)

### Descripción:


Conocemos como **Function Composition** a las funciones que obtenemos como resultado de combinar otras dos o más funciones, el resultado de cada función es el argumento de la siguiente y así sucesivamente.

### Comentarios:

* **Julio J Yépez** (13) [486612](https://platzi.com/comentario/486612/) 

	La sintaxis que vemos en el min 03:36 es similar a la manera en que se usan los _closures_ , que seguramente se explicará más adelante en el curso. La clave allí es que **`tag('h1')`** est[a retornando una función, que espera como parámetro el contenido.
	
	La función **tag** , podría ser escrita usando un estilo más convencional así:
	``` 
	    functiontag( t ){
	        returnfunction ( content ){
	            return`<${t}>${content}</${t}>`
	        }
	    }
	    
	```

	* **Julio J Yépez** [486612] (7)

		También pudo haber sido definida como una función convencional:
		``` 
		    functiontag( t, content ){
		        return`<${t}>${content}</${t}>`
		    }
		    
		```
		
		¯\\_(ツ)_/¯

	* **WilliamVelazquez** [486612] (4)

		De hecho como mencionas se pudo realizar igual con arrow function pero pasando doble parámetro quedando así:
		``` 
		    const tag = (t,content) => `<${t}>${content}</${t}>`
		    
		```
		
		Seguiría funcionando igual. 😃

	* **Juan David Castro (Platzi)** [486612] (2)

		La diferencia es que podemos crear una función para crear solo títulos h1, otra para párrafos, etc. Osea que **`tag`** solo sería una función constructora de funciones. Si recibimos ambos argumentos en la misma función debemos especificar el tipo de etiqueta que queremos crear.
		``` 
		    functiontag(t, content){
		        return`<${t}>${content}</${t}>`;
		    }
		    
		    tag("h2", "contenido");
		    tag("h2", "otro contenido");
		    tag("p", "párafo");
		    
		    functiontag(t){
		        returnfunction (content) {
		            return`<${t}>${content}</${t}>`;
		        } 
		    }
		    
		    const h2 = tag("h2");
		    const p = tag("p");
		    
		    h2("contenido");
		    h2("otro contenido");
		    p("un párrafo");
		    
		```

* **Juan David Castro (Platzi)** (10) [486749](https://platzi.com/comentario/486749/) 

	* [Componiendo funciones en JavaScript - Yeison Daza](https://yeisondaza.com/componiendo-funciones-en-javascript/)
	* [Functional JavaScript: Function Composition For Every Day Use - Hackernoon](https://hackernoon.com/javascript-functional-composition-for-every-day-use-22421ef65a10)
	* [Master the JavaScript Interview: What is Function Composition? - Medium](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-function-composition-20dfb109a1a0)
	
	![](https://cdn-images-1.medium.com/max/750/1*H2I0oeAQb24PLphVX0m9hg.jpeg)

	* **Carlos Gómez Mont** [486749] (1)

		Super aporte, gracias!!

* **Eliseo Geraldo González** (7) [486443](https://platzi.com/comentario/486443/) 

	Veo que el código es poco “funcional”, no sería mejor utilizar map, en lugar de hacer un for? creía que uno de los conceptos de la programación funcional era no tener que definir como pasaban las cosas, solo, que iba a pasar

	* **IDavidC** [486443] (8)

		Por supuesto, más adelante hacemos un refactor de esas funciones. Si no estamos acostumbrados a ver código declarativo es más fácil entender los conceptos de forma imperativa, una vez dominados podemos pensar de manera más funcional.

	* **Eliseo Geraldo González** [486443] (1)

		Si, una disculpa, me adelanté con mi comentario

	* **oteka21** [486443] (1)

		pensé lo mismo, y me vine a verificar los comentarios si alguien mas tenia mi misma opinión

* **Julio J Yépez** (4) [486607](https://platzi.com/comentario/486607/) 

	En el min 03:04, la manera de componer una cadena incrustándole variables con el formato **`${var}`** … se le llama _template literal_ y es una característica introducida por **EcmaScript**. Lo principal es el uso de apóstrofes diagonales o tildes graves como delimitadores de la cadena, en lugar de apóstrofes rectos, usados en JavaScript para cadenas convencionales (sin variables incrustadas).
	``` 
	    // cadena regular delimitada por apóstrofes
	    const hi = 'Hola Mundo'
	    // Hola Mundo
	    
	    // template literal delimitada por símbolo de tilde grave
	    const saludo = `${hi} nuevo`
	    // Hola Mundo nuevo
	    
	```

	* **Carlos Gómez Mont** [486607] (1)

		Gracias por compartir, saludos!!

	* **marygaby1308** [486607] (3)

		si no esto mal también se llaman `backticks`

	* **Julio J Yépez** [486607] (1)

		Ciertamente.  
		¡Gracias por el dato @marygaby1308!

* **iLuisCastillo** (3) [613172](https://platzi.com/comentario/613172/) 

	Lo he realizado de esta manera. Map retorna el nuevo arreglo con n items.
	``` 
	    const attrsToString = (obj = {}) => {
	      const keys = Object.keys(obj);
	      const attrs = (keys.map(key => `${key}="${obj[key]}"`)).join(' ');
	      return attrs;
	    }```
	    
	```

* **Gabriel De Andrade (Platzi)** (3) [491100](https://platzi.com/comentario/491100/) 

	La sintáxis que utiliza el profesor para insertar variables dentro del String se llama “Template Literals” o en Español “Plantillas de cadena de texto”
	
	* [Plantillas de cadena de texto - MDN Web Docs](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/template_strings)
	
	

* **T-gold** (2) [1065823](https://platzi.com/comentario/1065823/) 

	Una consulta? porque se utiliza doble => => en la funcion tag en lugar de ( t, content)=>  
	??

	* **Cesar Colina** [1065823] (1)

		Es basicamente una composicion de funciones, evalua primero la funcion mas interna y luego vas hacia afuera

	* **T-gold** [1065823] (1)

		gracias!

* **Danelia Sanchez Sanchez** (2) [496225](https://platzi.com/comentario/496225/) 

	[Introducción a la programación funcional en JavaScript — Parte 3: Composición](https://medium.com/laboratoria-developers/introducci%C3%B3n-a-la-programaci%C3%B3n-funcional-en-javascript-parte-3-composici%C3%B3n-f82ac871dcfb)

* **Cristobal Peña** (1) [1042547](https://platzi.com/comentario/1042547/) 

	Les pido disculpas por si esta pregunta resulta demasiado básica, pero me he estado rompiendo el coco tratando de entender un parte del código. ¿Por qué en la línea 16 se escribe obj[attr] y no obj.attr para acceder al atributo del objeto? Intenté usar la segunda opción, pero da error.
	
	Muchas gracias!

	* **albertodsosa** [1042547] (1)

		Con el operador de punto accedes a una propiedad o atributo que ya conoces. En este caso se está iterando o recorriendo los atributos y el parámetro `attr` es valor de la key que tendrá el objeto en cada una de las iteraciones y esta sintaxis nos permite acceder al valor dinámicamente sin tener que conocerlo previamente. ¿No se si me explico?.

	* **Cristobal Peña** [1042547] (1)

		Gracias Alberto. Pensé que entra ambos tipos de notaciones no había una diferencia práctica pero veo que sí la hay.
		
		Saludos.

* **lechesdarwin** (1) [811161](https://platzi.com/comentario/811161/) 

	```
	    console.log("el codigo compartido se guarda como imagen?")
	    
	```

* **Bruno Diharce** (1) [572979](https://platzi.com/comentario/572979/) 

	Esto me hace acuerdo a la extension en VSCode para seleccionar todo lo que quieras dentro de un div con class x (por ej.)

* **David Antonio Ordóñez Cornejo** (1) [547317](https://platzi.com/comentario/547317/) 

	Aquí una explicación super interesante de composition  
	[Functional programming design patterns by Scott Wlaschin](https://www.youtube.com/watch?v=E8I19uA-wGY)

* **Jorge Mendez Ortega** (1) [538775](https://platzi.com/comentario/538775/) 

	En vez de utilizar `Object.keys` podríamos utilizar `Object.entries` con lo que el código que estamos utilizando queda de la siguiente manera.
	``` 
	    const attributesToString = (obj = {}) => {
	        const ENTRIES = Object.entries(obj);
	        const ATTRS = [];
	        for (let i = 0; i < ENTRIES.length; i += 1) {
	            const AUX = ENTRIES[i]
	            const ATTR = AUX[0];
	            const VALUE = AUX[1];
	            ATTRS.push(` ${ATTR}="${VALUE}"`);
	        }
	        return ATTRS.join("");
	    };
	    
	```
	
	[Documentacion de `Object.entries`](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Object/entries)

* **Julio J Yépez** (1) [486601](https://platzi.com/comentario/486601/) 

	IMO: Otra manera de definir el concepto de _function composition_ sería que a una función A se le pasa como parámetro la ejecución _inline_ de otra función B.

* **Cristobal Peña** (1) [83959](https://platzi.com/comentario/1039073/) 
Me llama demasiado la atención que la sitaxis correcta sea console.log(tag(‘h1’)(‘Title’)) y que sea incorrecto colocar un paréntesis más...

	* **Cristobal Peña** [83959] (2)

		Bueno, me autoresponderé. La respuesta a esta pregunta tiene que ver con el concepto “currying” que se aborda en la clase 16.

* **Eliseo Geraldo González** (1) [51026](https://platzi.com/comentario/486443/) 
Veo que el código es poco “funcional”, no sería mejor utilizar map, en lugar de hacer un for? creía que uno de los conceptos de la progra...

	* **IDavidC** [51026] (8)

		Por supuesto, más adelante hacemos un refactor de esas funciones. Si no estamos acostumbrados a ver código declarativo es más fácil entender los conceptos de forma imperativa, una vez dominados podemos pensar de manera más funcional.

## 0140. Completando las funciones para generar etiquetas HTML [16802](https://platzi.com/clases/1497-funcional-js/16802-funciones-para-generar-etiquetas-html/)

### Descripción:


### Comentarios:

* **Juan David Castro (Platzi)** (6) [486753](https://platzi.com/comentario/486753/) 

	Este es un micro-framework que nos ayuda a construir aplicaciones web utilizando Componentes, muy parecido a React y Vue:
	
	* [Hyperapp is a JavaScript micro-framework for building web applications - Github](https://github.com/jorgebucaran/hyperapp)
	
	

	* **Carlos Gómez Mont** [486753] (1)

		Super aporte, gracias!!

	* **MauricioHernanCabrera** [486753] (1)

		Esta genial eso!

	* **Jorge Mendez Ortega** [486753] (2)

		para este caso no es como si utilizaramos webcomponents con `js` puro

* **waldoaraque** (4) [685261](https://platzi.com/comentario/685261/) 

	¿seguros que este código es más fácil de mantener?

	* **GABRIVP** [685261] (3)

		probablemente no.

* **Jorge Mendez Ortega** (2) [538788](https://platzi.com/comentario/538788/) 

	Siguiendo el taller y con un poco de curiosidad las funciones que estamos utilizando pueden quedar de la manera siguiente.
	``` 
	    // consiguiendo los atributes para las etiquetas HTML
	    const attributesToString = (obj = {}) => {
	        const ENTRIES = Object.entries(obj);
	        const ATTRS = [];
	        for (let i = 0; i < ENTRIES.length; i += 1) {
	            const AUX = ENTRIES[i];
	            const ATTR = AUX[0];
	            const VALUE = AUX[1];
	            ATTRS.push(`${ATTR}="${VALUE}"`);
	        }
	        return ATTRS.join("");
	    };
	    
	    // Creando etiquetas html con atributos
	    const createTagAttr = obj => (content = "") => {
	        const { tag, attr } = obj;
	        return `
	          <${tag}${attr ? ` ${attributesToString(attr)}` : ""}>
	            ${content}
	          </${tag}>`;
	    };
	    
	    // Generando tag de maner dinamica
	    const createTag = (tag) => {
	        const TAG = (typeof tag === "string")
	            ? createTagAttr({ tag })
	            : createTagAttr(tag);
	        return TAG;
	    };```
	    
	    para poder invocar todo dela siguiente manera. 
	    
	    
	    
	```
	
	createTag({tag:“h1”, attr:{“class”: “Success”}})(“Galletas mmmm”);
	``` 
	    espero pueda ser de utilidad par alguien.
	```

* **GABRIVP** (1) [764697](https://platzi.com/comentario/764697/) 

	Es un error de principiantes verificar si un objeto tiene propiedades con un simple obj.attr ? ‘’ : ‘’ porque un objecto vacio es truthy

* **Bryan Estiven Silva Mercado** (1) [506840](https://platzi.com/comentario/506840/) 

	Comprender el uso de las tres funciones me costo ver los vídeos un par de veces mas pero ahora quedo perfectamente entendido

## 0150. Closures en programación funcional [16805](https://platzi.com/clases/1497-funcional-js/16805-closures-en-programacion-funcional/)

### Descripción:


Los Closures son funciones que retornan otras funciones y recuerdan el _scope_ en el que fueron creadas, es decir, son funciones que utilizan principios de la programación funcional, no modifica el valor de variables u objetos externos, más bien, utilizan sus propias variables independientes (a partir de los parámetros que reciban estas funciones) para dar resultados correctos.

### Comentarios:

* **Juan David Castro (Platzi)** (6) [486755](https://platzi.com/comentario/486755/) 

	* [Closures | MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Closures)
	* [Definiendo conceptos: Closure y Scope en JavaScript - @sergiodxa](https://medium.com/@sergiodxa/definiendo-conceptos-closure-y-scope-en-javascript-9081f1e113e6)
	* [Entendiendo closures en JavaScript - Yeison Daza](https://yeisondaza.com/entendiendo-closures-en-javascript/)
	
	

	* **Carlos Gómez Mont** [486755] (1)

		Super aporte, gracias!!

* **Gabriel De Andrade (Platzi)** (5) [491870](https://platzi.com/comentario/491870/) 

	Closures: Es una función que retorna otra función  
	Ejemplo:
	``` 
	    functionbuildSum(a){
	    	returnfunction(b){
	    		return a+b
	    	}
	    }
	    
	```
	
	Y con arrow functions:
	``` 
	    const buildSum = a => b => a+b
	    
	```
	
	Y si quieren indagar un poco mas a lo que ser refiere el profesor con “scope” les dejo este post de Fanny:
	
	[Qué es y cómo funciona el scope en JavaScript](https://platzi.com/blog/como-funciona-el-scope-en-javascript/)

	* **elviejomenu** [491870] (3)

		Me parece mas practico e igual de legible hacer closures con arrow function , a continuación un ejemplo donde la primera función tiene 2 parámetros y la segunda uno solo :
		``` 
		    const buildSum = (value1, valu2) => value3 => (value1 + valu2) * value3;
		    console.log(buildSum(10, 20)(2));
		    
		```

	* **Carlos A Sanchez** [491870] (2)

		Con esa definición, entonces esto podría ser un closure:
		``` 
		    functionbuildingFakeClosure(){
		    	returnfunction(){
		    		console.log('Am I a closure?')
		    	}
		    }
		    
		```

* **danielplb** (4) [492053](https://platzi.com/comentario/492053/) 

	Es un buen ejemplo, aunque no estoy de acuerdo con que los clojures son “funciones que retornan otras funciones”. propiamente dicho.
	
	Estaría mejor definirlo como funciones internas que tienen acceso a las variables de sus funciones externas.
	
	Y es por esa razón que en javascript las funciones que retornan funciones son tan utiles.

	* **David Antonio Ordóñez Cornejo** [492053] (2)

		Los closures son funciones como valor que tienen acceso a todas las variables en su scope durante su creacion, lo que posibilita benecifiarse de los closures es que pueden ser retornadas de otras funciones, en este caso de hablamos de Funciones de Orden Superior

* **Jorge Eliecer Rangel Jimenez** (2) [554535](https://platzi.com/comentario/554535/) 

	Closures Arrow Function
	``` 
	    const buildSuma = (a) => (b) => a + b```
	    
	```

* **David Antonio Ordóñez Cornejo** (2) [547363](https://platzi.com/comentario/547363/) 

	Un closure
	``` 
	    // A little closure
	    const buildIncrementer = (inc, num) => () => num += inc
	    const incrementOne = buildIncrementer(1, 5)
	    console.log(incrementOne()) // 6
	    console.log(incrementOne()) // 7
	    console.log(incrementOne()) // 8
	    
	```

* **Dgn** (1) [690732](https://platzi.com/comentario/690732/) 

	```
	    buildSum = a => b => a+b
	    
	    console.log(buildSum(5)(5));```
	    
	```

* **Kingsman7** (1) [642186](https://platzi.com/comentario/642186/) 

	he usado Clousers en todo este tiempo y no sabia

## 0160. Currying [16804](https://platzi.com/clases/1497-funcional-js/16804-currying/)

### Descripción:


Gracias a los closures es posible implementar el **Currying** , descomponer funciones complejas en otras funciones más pequeñas donde cada función recibe un solo argumento. A continuación un ejemplo:
``` 
    // Sin Currying
    function sumThreeNumbers(a, b, c) {
            return a + b + c
    }
    
    console.log(sumThreeNumbers(1, 2, 3)) // 6
    
    function sumThreeNumbers(a) {
            return function(b) {
                    return function(c) {
                            return a + b + c
                    }
            }
    }
    
    console.log(sumThreeNumbers(1)(2)(3)) // 6
    
```

### Comentarios:

* **Juan David Castro (Platzi)** (8) [530950](https://platzi.com/comentario/530950/) 
	
	![](https://instagram.fbog7-1.fna.fbcdn.net/vp/2afd4c50372ac30fb1b12b7216239a04/5D149465/t51.2885-15/e35/51848190_261900188076515_1356668544216340184_n.jpg?_nc_ht=instagram.fbog7-1.fna.fbcdn.net)

	* **Gonzalo Ferrando** [530950] (1)

		jajajajajaa

* **Julio J Yépez** (6) [492790](https://platzi.com/comentario/492790/) 

	Acá les dejo un hilo interesante sobre el currying …  
	[Entendiendo el currying](https://twitter.com/jjyepez/status/1089744373917642752)

* **Gabriel De Andrade (Platzi)** (6) [491949](https://platzi.com/comentario/491949/) 

	Cuales son las ventajas en el mundo real de usar Currying?

	* **Julio J Yépez** [491949] (9)

		Una de las ventajas es que si al momento de invocar una función que espera más de un parámetro, tienes solo uno de ellos, pues la función no generará un error, sino que retornará otra función que estará preparada para recibir el resto de parámetros que esperabas originalmente.
		
		Es un poco complejo de explicar / entender, más aún en el contexto de JavaScript … pero en lenguajes “con alma de programación funcional” como Heskell, es sumamente útil y común encontrarle uso práctico a esta técnica.
		
		En [este artículo](https://www.campusmvp.es/recursos/post/Que-es-la-Currificacion-en-programacion-funcional.aspx) seguramente lo verás con mayor claridad.

	* **Bryan Estiven Silva Mercado** [491949] (2)

		tenía la misma duda gracias por el aporte

	* **Gabriel De Andrade (Platzi)** [491949] (4)

		Gracias JJ! Gran aporte, a lo largo de la práctica he ido aplicando los conceptos y me he encontrado con ventajas claras sobretodo en closures, como cuando quieres pasar una función como parametro sin ejecutarla como con los `addEventListener` puedes usar los closures y si quieres mas adelante ejecutarla de otra manera con Currying.
		
		Segin vayas integrando este paradigma en tus aplicaciones vas a ir dandote cuenta de cuando necesitas utilizar todos estos elementos

	* **David Antonio Ordóñez Cornejo** [491949] (1)

		Excelente explicacion

	* **David Antonio Ordóñez Cornejo** [491949] (7)

		La ventaja que yo veo en usar currying es que puedes convertir funciones que reciben muchos parametros en funciones que reciben un solo parámetro, lo cual la vuelve apta para ser compuesta con otras funciones que de igual forma reciben un solo parámetro.
		
		Al hacer currying, digamos, que podemos preconfigurar funciones y hacer código mucho mas modular.
		``` 
		    const saludo = (mensaje) => (name) => name + mensaje
		    const saludarFeliz = saludo('Hola estimado')
		    
		    saludarFeliz('Giddo van Rossum')//  Hola estimado Giddo van Rossum
		    saludarFeliz('Rasmus Lerdorf')//  Hola estimado Rasmus Lerdorf
		    saludarFeliz('Brendan Eich')//  Hola estimado Brendan Eich
		    
		    const saludarEnojado = saludo('Ashh!')
		    
		    saludarEnojado('Giddo van Rossum')//  Ashh! Giddo van Rossum
		    saludarEnojado('Rasmus Lerdorf')//  Ashh! Rasmus Lerdorf
		    saludarEnojado('Brendan Eich')//  Ashh! Brendan Eich
		    
		    
		    const saludoBipolar = compose(saludarEnojado, saludarFeliz)
		    saludoBipolar('Brendan Eich')// Ashh! Hola estimado Brendan Eich
		    
		```

	* **Matias Niz** [491949] (2)

		Lo mismo que @davidherzlos un claro ejemplo es la implementacion de middleware’s en express.

* **Juan David Castro (Platzi)** (4) [486756](https://platzi.com/comentario/486756/) 

	Versión reducida de la función `sumThreeNumbers` utilizando _currying_ y _arrow functions_ :
	``` 
	    const sumThreeNumbers = a => b => c => a + b + c
	    
	    console.log(sumThreeNumbers(1)(2)(3)) // 6
	    
	```

	* **Carlos Gómez Mont** [486756] (1)

		Gracias por compartir, saludos!!

* **Leandro Casco** (3) [492946](https://platzi.com/comentario/492946/) 

	Si quieren usar currying recomiendo Ramda.js <https://ramdajs.com/docs/#curry>.
	
	Ademas todas las funciones de ramda ya vienen curryficadas.

* **Juan David Castro (Platzi)** (3) [486758](https://platzi.com/comentario/486758/) 

	* [Currying in JS: The Many Ways - Medium](https://hackernoon.com/currying-in-js-d9ddc64f162e) 😬
	
	

	* **Carlos Gómez Mont** [486758] (1)

		Super aporte, gracias!!

	* **WilliamVelazquez** [486758] (1)

		Borraron esa entrada, de casualidad estará en otro lado?

	* **Juan David Castro (Platzi)** [486758] (3)

		Creo que es esta: <https://hackernoon.com/javascript-and-functional-programming-currying-pt-4-96e3230782ab>

	* **WilliamVelazquez** [486758] (1)

		Muchas gracias, lo revisaré! 😃

* **Gabriel De Andrade (Platzi)** (3) [51466](https://platzi.com/comentario/491949/) 
Cuales son las ventajas en el mundo real de usar Currying?

	* **Julio J Yépez** [51466] (9)

		Una de las ventajas es que si al momento de invocar una función que espera más de un parámetro, tienes solo uno de ellos, pues la función no generará un error, sino que retornará otra función que estará preparada para recibir el resto de parámetros que esperabas originalmente.
		
		Es un poco complejo de explicar / entender, más aún en el contexto de JavaScript … pero en lenguajes “con alma de programación funcional” como Heskell, es sumamente útil y común encontrarle uso práctico a esta técnica.
		
		En [este artículo](https://www.campusmvp.es/recursos/post/Que-es-la-Currificacion-en-programacion-funcional.aspx) seguramente lo verás con mayor claridad.

* **T-gold** (2) [1066061](https://platzi.com/comentario/1066061/) 

	entendi el concepto pero no entiendo cual es el beneficio de descomponerlas de este modo?
	
	mejor mantenimiento?

	* **Carlos Bueno Tavares** [1066061] (1)

		x2

* **edanfesi** (2) [841385](https://platzi.com/comentario/841385/) 

	Ejemplo en forma de arrow function:
	``` 
	    const sumThreeNumbers = a => b => c => a + b + c;
	    
	```

* **Christian Armando Consuelo Mayén** (1) [796067](https://platzi.com/comentario/796067/) 

	El currying es buena práctica para entender las bases de composición de funciones y funciones de orden mayor. La verdad es una forma diferente pero a la vez tiene toda la lógica del mundo.

* **pecaspersonalizados** (1) [566297](https://platzi.com/comentario/566297/) 

	¿Cuál es la diferencia entre funciones compuestas y currying?

	* **Diego Alexander Forero Higuera (Platzi)** [566297] (3)

		La diferencia es en la forma en que se crean las funciones, encontré esta lectura que me parece interesante <https://medium.com/javascript-scene/curry-and-function-composition-2c208d774983>

	* **aragonesteban (Platzi)** [566297] (3)

		Hola!  
		Las **funciones compuestas** es cuando combinamos dos o mas funciones para generar una nueva función, muy parecido a lo que hace la función `connect` en **Redux**.  
		Ahora, el **Currying** lo que hace es descomponer funciones en otras funciones más pequeñas para que reciban cada una un sólo argumento y retornar un sólo valor.  
		A simple vista pueden ser muy parecidos en cuanto al código pero ambos tienen implementaciones diferentes.  
		Espero haberte ayudado, saludos!

* **** (1) [563529](https://platzi.com/comentario/563529/) 

	Creo que esto representa lo que está escrito en libros de cualquier lenguaje de programación moderno…  
	< divide y venceras > ó también, lo que se conoce como la abstracción

* **danielplb** (1) [491889](https://platzi.com/comentario/491889/) 

	genial, la idea de funciones currificadas seria ir pasando los argumentos de una función parcialmente a medida que son obtenidos.
	``` 
	    leta = sumThreeNumbers(1)
	    letb = a(2)
	    letc = b(3)
	    
	    console.log(c) // 6
	    
	    
	```

* **pecaspersonalizados** (1) [57538](https://platzi.com/comentario/566297/) 
¿Cuál es la diferencia entre funciones compuestas y currying?

	* **Diego Alexander Forero Higuera (Platzi)** [57538] (3)

		La diferencia es en la forma en que se crean las funciones, encontré esta lectura que me parece interesante <https://medium.com/javascript-scene/curry-and-function-composition-2c208d774983>

## 0170. Proyecto Construyendo filas y celdas [16806](https://platzi.com/clases/1497-funcional-js/16806-construyendo-filas-y-celdas/)

### Descripción:


### Comentarios:

* **Bryan Estiven Silva Mercado** (6) [506851](https://platzi.com/comentario/506851/) 

	espero que mas adelante se explique la función del principio un poco mas

	* **memowii** [506851] (20)

		Tratando de explicar la función compose. Tenemos lo siguiente:
		
		La función compose está realizando una composición de funciones. Recordando la notación matemática, y teniendo en consideración las funciones f y g, vemos que la composición de estas es la siguiente (g º f)(x) = g(f(x)). Lo que quiere decir que el resultado de f(x) es pasado a la función g, y g regresa un valor.
		
		Después de esa breve teoría expliquemos el código la función compose. Tenemos que compose está definida de la siguiente forma:
		``` 
		    const compose = (...functions) => data => functions.reduceRight((value, func) => 
		    func(value), data)
		    
		```
		
		Para hacer la lectura de compose más fácil, quitemos las arrow function, por lo que la función quedaría así:
		``` 
		    functioncompose(...functions){ // (*)
		      returnfunction(data){ // (**)
		        return functions.reduceRight(function(value, func){ // (***)
		          return func(value)
		        }, data)
		      }
		    }
		    
		```
		
		Y también recordemos la manera en como compose está siendo utilizada en el proyecto del curso, para entender la composición que se está realizando.:
		``` 
		    const tableRow = items => compose(tableRowTag, tableCells)(items);
		    
		```
		
		Empecemos por entender qué significa la sentencia _…functions_. Esa sentencia está haciendo uso de los _rest parameters_ de JS. Los _rest parameters_ pueden ser utilizados en la definición de una función con los “…”. Significan, literalmente, “reune los parámetros restantes en un array”. Por lo anterior, y por la forma en cómo está siendo aplicada la función _compose_ , tenemos que:
		
		_…functions_ va a generar el siguiente _array_ , _functions = [tableRowTag, tableCells]_ , que va a poder se utilizado dentro de _compose_.
		
		En la línea (**) vemos que _compose_ está regresando una función, cuyo parámetro es _data_ , eso implica, que al momento de usar _compose_ en nuestro proyecto se le esté pasando la variable _items_ , de otra manera la funcionalidad de _compose_ no se cumpliría por completo.
		``` 
		    compose(tableRowTag, tableCells)(items)
		    
		```
		
		En la línea (***), vemos que se está haciendo utilización de la función _reduceRight_ en el array _functions_ , y cuyo _initialValue_ es _data_. _reduceRight_ funciona de manera invesa a _reduce_ , o sea que empieza a tomar valores de derecha a izquierda.
		
		Para la primera interación de _reduceRight_ , se tienen los siguientes valores:
		``` 
		    value = data // pero data = [item.description, item.calories, item.carbs, item.protein, removeButton]
		    func = tableCells
		    
		```
		
		Y cuya ejecución de código que realiza es:
		``` 
		    tableCells([item.description, item.calories, item.carbs, item.protein, removeButton])
		    
		```
		
		El resultado de la función anterior es un string, que va a tener la siguiente forma:
		``` 
		    "<td>description</td><td>calories</td><td>carbs</td><td>removeButton</td>"
		    
		```
		
		Para la segunda iteración de _reduceRight_ , tenemos los siguientes valores:
		``` 
		    value = "<td>description</td><td>calories</td><td>carbs</td><td>removeButton</td>"
		    func = tableRowTag
		    
		```
		
		La ejecución que realiza es:
		``` 
		    tableRowTag("<td>description</td><td>calories</td><td>carbs</td><td>removeButton</td>")
		    
		```
		
		Y función que realiza la función _tableRowTag_ es agregar la etiqueta _tr_ al elemento que se le pase como argumento.
		
		Por lo que el resultado de haber ejecutado la función _compose_ de esta forma:
		``` 
		    compose(tableRowTag, tableCells)(items)
		    
		```
		
		Da como resultado:
		``` 
		    "<tr><td>description</td><td>calories</td><td>carbs</td><td>removeButton</td></tr>"
		    
		```
		
		Y esa cadena va a ser agregada al tbody de nuestro proyecto.

	* **Nathaly Stefani Riaño Bejarano** [506851] (1)

		Muchas gracias por la aclaración! Me ayudo a comprender el ejercicio.

	* **eduardo110298** [506851] (1)

		no, no, yo le pido la B E N D I C I Ó N a **memowii** por esa explicación. Me ayudó mucho!! Gracias

	* **Juan David Castro (Platzi)** [506851] (1)

		👉 <https://www.freecodecamp.org/news/pipe-and-compose-in-javascript-5b04004ac937/>  
		👉 <https://medium.com/javascript-scene/curry-and-function-composition-2c208d774983>  
		👉 <https://www.sitepoint.com/function-composition-in-javascript/>

* **aragonesteban (Platzi)** (5) [489676](https://platzi.com/comentario/489676/) 

	🤯🤯🤯🤯🤯

# Higher Order Functions [3343]

## 0180. Introducción a las Higher Order Functions [16807](https://platzi.com/clases/1497-funcional-js/16807-introduccion-a-las-higher-order-functions/)

### Descripción:


Por ahora, todas las funciones que hemos construido se pueden definir como _First Class Functions_ , sin embargo, existen otro tipo de funciones que conocemos como _Higher Order Functions_ o funciones de alto orden y podemos distinguirlas porque reciben otra función como argumento.

Un buen ejemplo de funciones de alto orden es la función `.map` de JavaScript:
``` 
    // Ciclo for (sin HOF)
    const array = [1, 2, 3]
    const array2 = []
    
    for (let i = 0; let i < array.length; i++) {
            array2.push(array[i] * 2)
    }
    
    // Utilizando la función .map (HOF)
    const array = [1, 2, 3]
    const array2 = array.map(item => item * 2)
    
    // Ambas formas devuelven el mismo resultado,
    // sin embargo, utilizando HOFs podemos escribir
    // código mucho más legible y fácil de entender
    console.log(array2) // [2, 4, 6]
    
```

### Comentarios:

* **Julio J Yépez** (10) [492811](https://platzi.com/comentario/492811/) 

	**`.map()`** forma parte de un grupo de métodos disponibles para el tipo de dato _array_ (más bien de su clase _prototype_ ) exclusivamente, y que permite hacer un recorrido por los elementos de dicho _array_ y realizar algunas acciones sobre éstos utilizando el paradigma de la programación funcional. Estos métodos son:
	
	* **`.map()`** : ejecuta una función por cada uno de los elementos del arreglo y retorna en sí mismo el arreglo resultante (mutado).
	* **`.forEach()`** : Similar al método anterior pero no retorna en sí misma el array resultante.
	* **`.filter()`** : devuelve un arreglo con los elementos que cumplen con una condición buleana determinada por una función que se pasa por parámetro.
	* **`.reduce()`** : aplica una función definida a los diferentes elementos del arreglo para obtener a fin de cuentas un valor resultante. Es similar a una función de agregado.
	
	

	* **Julio J Yépez** [492811] (3)

		La clase que define el tipo de dato _array_ tiene muchos otros métodos interesantes, acá una referencia: <https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array>

	* **gusgonzalez060** [492811] (2)

		Como siempre de gran ayuda tus aportes, gracias amigo!!!

* **Leandro Casco** (5) [492948](https://platzi.com/comentario/492948/) 

	Como complementar con las High Order Functions recomiendo usar tambien la notación _point free_ al definir nuevas funciones. Esta notacion nos permite invocar funciones sin hacer referencia a los valores de entrada.
	
	Por ejemplo:
	``` 
	    const even = x => x % 2 === 0;
	    
	    const filtered = [1, 2, 3, 4, 5, 6].filter(even); // => [2, 4, 6]
	    
	```

* **Juan David Castro (Platzi)** (4) [486760](https://platzi.com/comentario/486760/) 

	⚛ Los **Higher Order Components** (HOCs) son funciones que reciben y devuelven un componente mucho modificado, son muy utilizados en librerías como React.js para reutilizar o añadir funcionalidades a nuestros componentes.
	
	Peeero cada vez se utilizan menos porque hay otros patrones (Render Props y React Hooks) que nos otorgan los mismos resultados pero con código (componentes) aún más legibles y fáciles de escribir 👌.
	
	* [Higher-Order Components – React Docs](https://reactjs.org/docs/higher-order-components.html)
	
	

	* **Carlos Gómez Mont** [486760] (1)

		Gracias por compartir, saludos!!

	* **Juan David Castro (Platzi)** [486760] (2)

		¡No hagas trampa, @ccegmpp! ¬¬ :una

* **David Daza** (3) [538713](https://platzi.com/comentario/538713/) 

	Las funciones de alto orden (HOF) pueden entenderse como funciones que reciben como parámetro a otras funciones. Bajo esa premisa, la función `map` puede ser implementada de la siguiente forma
	``` 
	    const map = (array, transform) => {
	        const mapped = []
	        for (let i = 0; i < array.length; i++) {
	            mapped.push(transform(array[i]))
	        }
	        return mapped
	    }
	    
	```
	
	Y ser usada así
	``` 
	    map([1, 2, 3], (number) => number * 2) // [2, 4, 6]
	    
	```
	
	Obviamente esto ya existe en el core de Javascript pero está bueno saber cómo utilizar el concepto de HOF para alguna situación particular que se nos presente.

## 0190. Proyecto Actualizando el total de calorías [16808](https://platzi.com/clases/1497-funcional-js/16808-actualizar-totales/)

### Descripción:


### Comentarios:

* **Julio J Yépez** (13) [492817](https://platzi.com/comentario/492817/) 

	Comprendo la facilidad que ofrece el uso de **jQuery** en el proyecto para seleccionar elementos del DOM; pero, creo que hubiera estado más acorde con la onda EcmaSript-ProgramaciónFuncional, si en lugar de jQuery, se hubiera usado JavaScript _vanilla_ : **`document.querySelector('#id-selector')`** …
	
	¡Aún así, el curso va muy bien!  
	Seguimos.

	* **Gabriel De Andrade (Platzi)** [492817] (8)

		Agregando a esto recuerdo que se puede usar la propiedad `textContent` de JavaScript para lograr cambiar el texto quedando algo así:  
		`document.querySelector('#id-selector').textContent = 'value'`
		
		¡Coincido, muy buen curso!

	* **jorg92_** [492817] (2)

		También podría quedar de la siguiente manera:
		``` 
		    let descripcion = document.getElementById('descripcion')
		    
		    descripcion.value = 'texto'
		    
		```

	* **Alfonso Navarro** [492817] (1)

		Totalmente de acuerdo Platzi nos esta vendiendo la idea de dejar JQuery por un lado (Lo cual me parece perfecto), pero por otro se sigue utilizando.

	* **Jorge Mendez Ortega** [492817] (2)

		Si usas value no se cambia el texto de la celda, tienes que utilizar `textContent`

* **Victor Lozada** (4) [504374](https://platzi.com/comentario/504374/) 

	Si les parece mas rápido y sencillo utilizar la nomenclatura de jQuery `$('#element')` para acceder a los elementos del dom, pueden hacer uso de esta sin necesidad de cargar la librería con la siguiente función:
	``` 
	    //probando en la home de platzi (https://platzi.com/) desde la consola
	    
	    const $ = element => document.querySelector(element)
	    const spanNumber = $('#home-v4 > div > div.HeroContent > div > div.HeroContent-content > div.HeroContent-stats > div > div:nth-child(1) > span:nth-child(1)')
	    console.log(spanNumber) // nos mostrara un elemento span
	    
	```
	
	![](https://i.imgur.com/ZQqrvRG.png)
	
	**AVISO** : de esta forma no podrás usar los métodos de jQuery como `val()` o `text()` ,pero tendrás disponibles todos los métodos nativos de los elementos HTML como .innerText o .textContent entre muchísimos mas claro.
	
	![](https://i.imgur.com/VcrGcyy.gif)

* **jorge william reaño reyes** (4) [499551](https://platzi.com/comentario/499551/) 

	let updateTotals = () => {  
	let scal = items.reduce((acum,item) => acum +=parseInt(item.cal) ,0)  
	let scarb = items.reduce((acum,item) => acum +=parseInt(item.carb) ,0)  
	let sprote = items.reduce((acum,item) => acum +=parseInt(item.prote) ,0)  
	}

* **Jorge Mendez Ortega** (3) [542754](https://platzi.com/comentario/542754/) 

	Ejemplo utlizando `JS puro` o lo que tambien se conoce como vanilla
	``` 
	    const compose = (...functions) => data => functions.reduceRight((value, func) => func(value), data);
	    
	    // Se utiliza $ para identificar que una variable o constante hace referencia
	    // a elementos del DOM
	    const $DESCRIPTION = document.getElementById("description");
	    const $CALORIAS = document.getElementById("calorias");
	    const $CARBOIDRATOS = document.getElementById("carboidratos");
	    const $PROTEINAS = document.getElementById("proteinas");
	    const ERROR_CLASS = "is-invalid";
	    const SUCCESS_CLASS = "is-valid";
	    
	    // Arreglo de elementos
	    const LIST = [];
	    
	    // consiguiendo los atributes para las etiquetas HTML
	    const attributesToString = (obj = {}) => {
	        const ENTRIES = Object.entries(obj);
	        const ATTRS = [];
	        for (let i = 0; i < ENTRIES.length; i += 1) {
	            const AUX = ENTRIES[i];
	            const ATTR = AUX[0];
	            const VALUE = AUX[1];
	            ATTRS.push(`${ATTR}="${VALUE}"`);
	        }
	        return ATTRS.join("");
	    };
	    
	    // Creando etiquetas html con atributos
	    const createTagAttr = obj => (content = "") => {
	        const { tag, attr } = obj;
	        return `
	          <${tag}${attr ? ` ${attributesToString(attr)}` : ""}>
	            ${content}
	          </${tag}>`;
	    };
	    
	    // Generando tag de maner dinamica
	    const createTag = (tag) => {
	        const TAG = (typeof tag === "string")
	            ? createTagAttr({ tag })
	            : createTagAttr(tag);
	        return TAG;
	    };
	    
	    // Asignacion de evntos siempre que se desea asignar un evento aun elemento del DOM
	    // es necesario utilizar addEventListener
	    $DESCRIPTION.addEventListener("keypress", () => $DESCRIPTION.classList.remove(ERROR_CLASS));
	    $CALORIAS.addEventListener("keypress", () => $CALORIAS.classList.remove(ERROR_CLASS));
	    $CARBOIDRATOS.addEventListener("keypress", () => $CARBOIDRATOS.classList.remove(ERROR_CLASS));
	    $PROTEINAS.addEventListener("keypress", () => $PROTEINAS.classList.remove(ERROR_CLASS));
	    
	    // Limpiando inputs
	    const cleanInputs = () => {
	        $DESCRIPTION.classList.remove(SUCCESS_CLASS);
	        $DESCRIPTION.value = "";
	        $CALORIAS.classList.remove(SUCCESS_CLASS);
	        $CALORIAS.value = "";
	        $CARBOIDRATOS.classList.remove(SUCCESS_CLASS);
	        $CARBOIDRATOS.value = "";
	        $PROTEINAS.classList.remove(SUCCESS_CLASS);
	        $PROTEINAS.value = "";
	    };
	    
	    const updateTotals = () => {
	        let carboidratos = 0;
	        let proteinas = 0;
	        let calorias = 0;
	        // Por buenas praxticas se utiliza un forEach y cumple la mism funcion que se busca
	        // practicamente una funcion de alto orden, no utiizo el map por que  map siempre regresa
	        // algo y de momento no importa capturar lo que regresa la iteracion que realizamos.
	        LIST.forEach((item) => {
	            carboidratos += item.carboidratos;
	            proteinas += item.proteinas;
	            calorias += item.calorias;
	        });
	        document.querySelector("#totalCalorias").textContent = calorias;
	        document.querySelector("#totalCarboidratos").textContent = carboidratos;
	        document.querySelector("#totalProteinas").textContent = proteinas;
	    };
	    
	    // Agregar elementos en la lista
	    const addElement = () => {
	        const newItem = {
	            description: $DESCRIPTION.value,
	            calorias: parseInt($CALORIAS.value, 10),
	            carboidratos: parseInt($CARBOIDRATOS.value, 10),
	            proteinas: parseInt($PROTEINAS.value, 10),
	        };
	        LIST.push(newItem);
	        cleanInputs();
	        updateTotals();
	    };
	    
	    // funcion para validar los inputs
	    const validateInputs = () => {
	        // Por cuestion de buenas practicas el resultado de una condición
	        // Ternaria tiene que ser asignada a una variable o constante
	        const DESCRIPTION_CLASS = (($DESCRIPTION.value) ? SUCCESS_CLASS : ERROR_CLASS);
	        $DESCRIPTION.classList.add(DESCRIPTION_CLASS);
	    
	        const CALORIAS_CLASS = (($CALORIAS.value) ? SUCCESS_CLASS : ERROR_CLASS);
	        $CALORIAS.classList.add(CALORIAS_CLASS);
	    
	        const CARBOIDRATOS_CLASS = (($CARBOIDRATOS.value) ? SUCCESS_CLASS : ERROR_CLASS);
	        $CARBOIDRATOS.classList.add(CARBOIDRATOS_CLASS);
	    
	        const PROTEINAS_CLASS = (($PROTEINAS.value) ? SUCCESS_CLASS : ERROR_CLASS);
	        $PROTEINAS.classList.add(PROTEINAS_CLASS);
	    
	        if ($DESCRIPTION.value && $CALORIAS.value && $CARBOIDRATOS.value && $PROTEINAS.value) {
	            addElement();
	        }
	    };
	    
	    
	```

* **Carlos David Sanchez Moreno** (3) [499683](https://platzi.com/comentario/499683/) 

	VanillaJS
	``` 
	    const compose = (...functions) => data =>
	      functions.reduceRight((value, func) => func(value), data)
	    
	    
	    const attrsToString = (obj = {}) => {
	    
	      const keys = Object.keys(obj)
	      let attrs = []
	    
	      for(let i = 0; i < keys.length; i++){
	        let attr = keys[i]
	        attrs.push(`${attr}="${obj[attr]}"`)
	      }
	      
	      conststring = attrs.join('')
	      returnstring
	    }// string
	    
	    const tagAttrs = obj => (content = '') => 
	    `<${obj.tag}${obj.attrs ? ' ' : ''}${attrsToString(obj.attrs)}>content<${obj.tag}>`
	    
	    const tag = t => {
	      if (typeof t === 'String'){
	        tagAttrs({tag: t})
	      }else{
	        tagAttrs(t)
	      }
	    }
	    
	    const tableRowTag = tag('tr')
	    // const tableRow = items => tableRowTag(tableCells(items))
	    const tableRow = items => compose(tableRowTag, tableCells)(items)
	    
	    const tableCell = tag('td')
	    const tableCells = items => item.map(tableCell).join('')
	    
	    
	    letlist = []
	    let description = document.getElementById('description')
	    let calories = document.getElementById('calories')
	    let carbs = document.getElementById('carbs')
	    let protein = document.getElementById('proteins')
	    let btn = document.getElementById('btn')
	    
	    const validateInputs = () => {
	      description.value ? '' : description.classList.add('is-invalid')
	      calories.value ? '' : calories.classList.add('is-invalid')
	      carbs.value ? '' : carbs.classList.add('is-invalid')
	      protein.value ? '' : protein.classList.add('is-invalid')
	    
	      if(description.value && calories.value && carbs.value && protein.value) {
	        console.log('OK!')
	        add()
	        cleanInputs()
	        updateTotals()
	      }
	    }
	    
	    btn.addEventListener('click', validateInputs)
	    
	    description.addEventListener('keydown', () => description.classList.remove('is-invalid'))
	    calories.addEventListener('keydown', () => calories.classList.remove('is-invalid'))
	    carbs.addEventListener('keydown', () => carbs.classList.remove('is-invalid'))
	    proteins.addEventListener('keydown', () => proteins.classList.remove('is-invalid'))
	    
	    const add = () => {
	      const newItem = {
	        description: description.value,
	        calories: parseInt(calories.value),
	        carbs: parseInt(carbs.value),
	        proteins: parseInt(proteins.value)
	      }
	      list.push(newItem)
	      console.log(list)
	    }
	    
	    const updateTotals = () => {
	      let calories = 0, carbs = 0, proteins = 0
	    
	      list.map(item => {
	        calories += item.calories
	        carbs += item.carbs
	        proteins += item.proteins
	      })
	    
	      document.getElementById('totalCalories').innerHTML = calories
	      document.getElementById('totalCarbs').innerHTML = carbs
	      document.getElementById('totalProteins').innerHTML = proteins
	    
	    }
	    
	    const cleanInputs = () => {
	      description.value = ' '
	      calories.value = ' '
	      carbs.value = ' '
	      protein.value = ' '
	    }
	    
	    
	```

* **Ulises German Rios Romero** (2) [634848](https://platzi.com/comentario/634848/) 

	Este es mi código para la parte de updateTotals, utilize textContent, ya que innerHTML no me convence mucho para este caso
	``` 
	    //Las puse a parte por si se usan en otro momento, si no simplemente se pasan a la función
	    const totalCalories = document.getElementById('totalCalories')
	    const totalCarbs = document.getElementById('totalCarbs')
	    const totalProteins = document.getElementById('totalProteins')
	    
	    const updateTotals = () => {
	    	let calories = 0, carbs = 0, protein= 0
	    	list.map(item => {
	    		calories += item.calories,
	    		carbs += item.carbs,
	    		protein += item.protein
	    	})
	    	console.log(calories)
	    	totalCalories.textContent = calories
	    	totalCarbs.textContent = carbs
	    	totalProteins.textContent = protein
	    }
	    
	```

## 0200. Proyecto Mostrar elementos [16963](https://platzi.com/clases/1497-funcional-js/16963-mostrar-elementos/)

### Descripción:


### Comentarios:

* **Julio J Yépez** (9) [492837](https://platzi.com/comentario/492837/) 

	La función **`renderItems()`** redefinida sin jQuery, sería algo como:
	``` 
	    const renderItems = () => {
	    
	      document.querySelector('tbody').innerHTML = ''
	    
	      list.map(item => {
	    
	        const row = document.createElement('tr')
	    
	        row.innerHTML = tableRow([
	          item.description,
	          item.calories,
	          item.carbs,
	          item.protein
	        ])
	    
	        document.querySelector('tbody').appendChild( row )
	      })
	    }
	    
	```
	
	IMO

	* **Gabriel De Andrade (Platzi)** [492837] (5)

		Yo por mi parte modifiqué el `innerHTML` De una vez en el elemento HTML quedando algo así
		``` 
		    const renderItems = () => {
		      
		      const listWrapper = document.querySelector('tbody')
		    
		      listWrapper.innerHTML = ""  
		    
		      list.map(item => {    
		        listWrapper.innerHTML += tableRow([
		    			item.description, 
		    			item.calories, 
		    			item.carbs, 
		    			item.proteins
		    		])
		      })
		    }
		    
		```

	* **Fernando Alejandro Yerena Ramos** [492837] (1)

		@gabrielelpido, ¿Al colocar `+=` no se repiten los elementos ya renderizados de la lista, en la tabla? 🤔

	* **Gabriel De Andrade (Platzi)** [492837] (2)

		@FerdinandAlexa No debería, por que cada que se ejecuta la función el innerHTML se vacia en con :  
		`listWrapper.innerHTML = ""`

* **Jorge Mendez Ortega** (7) [542937](https://platzi.com/comentario/542937/) 

	Una variante de la función `renderItems`, para este caso no utilizamos `jQuery` y tampoco utilizo el `createElement` de `JS` ya que realmente es inecesario ya que la creacion de los tags ya existe dentro de las funciones.
	``` 
	    const renderItems = () => {
	        // otra manera de poder obtener un elemento por el name TAG
	        // solo que este metodo consigue un arreglo de elementos
	        const $CONTAINER = document.getElementsByTagName("tbody")[0];
	        $CONTAINER.innerHTML = "";
	        const ROWS = LIST.map((item) => {
	            const {
	                calorias, description,
	                carboidratos, proteinas,
	            } = item;
	            return tableRow([description, calorias, carboidratos, proteinas]);
	        });
	        $CONTAINER.innerHTML = ROWS.join("");
	    };
	    
	```

	* **Diego Andres Cardenas Caro** [542937] (1)

		Genia. me gusto tu solucion sin usar jquery y aplicando destructuring. 👌

* **Jorge Mendez Ortega** (3) [542758](https://platzi.com/comentario/542758/) 

	Una manera un poco diferente de crear elementos de manera dinamica
	``` 
	    const createElement = Object.create({ config: null, customSettings: null, contetPanel: null }, {
	        init:
	        {
	            get() {
	                this.config = {
	                    tag: "div",
	                    id: `id_${Math.random().toString(36).substr(2)}`,
	                    label: "empty",
	                };
	                Object.assign(this.config, this.customSettings);
	            }, // get:function
	        }, // init
	        factory:
	        {
	            get() {
	                if (this.contetPanel !== null) {
	                    const panel = document.createElement(this.config.tag);
	                    let source = "";
	                    let config = "";
	                    const ENTRIES = Object.entries(this.config);
	                    ENTRIES.forEach((item) => {
	                        const PROPERTY = item[0];
	                        config = this.config[PROPERTY];
	                        source = (PROPERTY === "infoText") ? `panel.innerHTML = '${config}';` : `panel.${PROPERTY} = '${config}';`;
	                        eval(source);
	                    });
	    
	                    if (this.config.label !== "" && this.config.label !== "empty") {
	                        const tagLabel = document.createElement("label");
	                        tagLabel.innerHTML = this.config.label;
	                        this.contetPanel.appendChild(tagLabel);
	                    }// if (config.label != '' && config.label != 'empty')
	                    this.contetPanel.appendChild(panel);
	                    this.contetPanel = null;
	                }
	            }, // get:function()
	        }, // factory
	        create:
	        {
	            value(custom, selector = "") {
	                this.customSettings = custom;
	                this.contetPanel = (selector !== "") ? document.querySelector(selector) : document.body;
	                this.init;
	                this.factory;
	                returnthis.config.id;
	            }, // value
	        }, // create
	    });// createElement
	    
	    const CONFIG = {
	        tag: "div",
	        id: "demo",
	        className: "style",
	    }
	    
	    // ejemplo
	    createElement.create(CONFIG, "body");
	    
	```

* **Bryan Estiven Silva Mercado** (2) [507360](https://platzi.com/comentario/507360/) 

	obtengo el siguiente error
	
	**main.js:150 Uncaught TypeError: undefined is not a function**
	
	El error es en esta linea
	``` 
	    const tableCells = items => items.map(tableCell).join('')
	    
	```
	
	alguna idea ?

	* **Bryan Estiven Silva Mercado** [507360] (1)

		tableCell tiene un estado de undefined

	* **Danelia Sanchez Sanchez** [507360] (4)

		Podría ser algún error de digitación, a mí me sucedió que en la función `tag` había omitido la palabra ****`return`****.

	* **IDavidC** [507360] (2)

		Tu función ejecuta tableCell, ya declaraste esa función?
		``` 
		    const tableCell = tag('td')
		    
		```

	* **Cristian David Franco Garcia** [507360] (5)

		Modifique la función **tag** de tal forma que quede como la siguiente:
		``` 
		    const tag = t => {
		      if (typeof (t) === 'string') {
		        returntagAttributes({ tag: t });
		      }
		      returntagAttributes(t);
		    }
		    
		```

* **Bryan Estiven Silva Mercado** (1) [52582](https://platzi.com/comentario/507360/) 
obtengo el siguiente error main.js:150 Uncaught TypeError: undefined is not a function El error es en esta linea c...

	* **Bryan Estiven Silva Mercado** [52582] (1)

		tableCell tiene un estado de undefined

## 0210. Proyecto Eliminar elementos [16964](https://platzi.com/clases/1497-funcional-js/16964-eliminar-elementos/)

### Descripción:


### Comentarios:

* **Julio J Yépez** (15) [492850](https://platzi.com/comentario/492850/) 

	Algo interesante que se ve en esta clase es cómo cada vez que se hace algún cambio a la lista es necesario llamar a la función que vacía la tabla y luego la que hace el _render_ de los _items_. Esto sucede porque se está usando jQuery como librería de renderizado.
	
	Otras librerías (o _frameworks_ ) como React, Angular o Vue no requieren el renderizado manual con cada cambio de estado porque utilizan un paradigma de programación llamado **reactivo** basado en el patrón de diseño de _Observers_. Entidades de ES que permiten detectar el cambio de “estado” y ejecutar el re-renderizado de los elementos del DOM cuyo valor/contenido dependan de éste. (bueno … más o menos) 😉
	
	Algunas referencias sobre este tema:
	
	* [Observer (patrón de diseño)  
	](https://es.wikipedia.org/wiki/Observer_\(patr%C3%B3n_de_dise%C3%B1o\))
	* [¿Qué es la Programación Reactiva? Una introducción](https://profile.es/blog/que-es-la-programacion-reactiva-una-introduccion/)
	* [El Manifiesto de los Sistemas Reactivos](https://www.reactivemanifesto.org/es)
	
	

	* **David Antonio Ordóñez Cornejo** [492850] (1)

		Muy bueno el aporte.

	* **Yulissa Terán Cerquín** [492850] (1)

		Además de Angular,  
		¿React y Vue también usan observers?

	* **Juan David Castro (Platzi)** [492850] (1)

		👋 Hello, **@Yulii**!
		
		👉 <https://webdevstudios.com/2019/02/19/observable-pattern-in-javascript/>  
		👉 <https://www.thedevnotebook.com/2017/08/the-observer-pattern-in-javascript.html>  
		👉 <https://medium.com/javascript-in-plain-english/react-hooks-and-the-observer-pattern-1e4274f0e5f5>  
		👉 <https://www.javascriptstuff.com/component-communication/#6-observer-pattern>

* **Juan David Castro (Platzi)** (11) [486761](https://platzi.com/comentario/486761/) 

	La función `.map` de JavaScript puede recibir un segundo argumento que por convención se llama `index` y nos sirve para obtener la posición de un elemento dentro de nuestro array 👍.
	
	* [Learn & Understand JavaScript’s Map Function - codeburst](https://codeburst.io/learn-understand-javascripts-map-function-ffc059264783)
	
	

	* **Carlos Gómez Mont** [486761] (1)

		Super aporte, gracias!!

	* **danielplb** [486761] (2)

		También recibe como tercero el Array al que pertenece el elemento

	* **Jorge Mendez Ortega** [486761] (2)

		De hecho la función `map` puede recibir 3 parámetros
		
		* CurrenValue : El elemento actual del array que se está procesando
		* Index: El índice del elemento actual dentro del `array`.
		* Array: El array sobre el que se llama `map`.
		
		
		
		[Funció map](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array/map)

* **Jorge Mendez Ortega** (4) [543184](https://platzi.com/comentario/543184/) 

	Practica general del curso sin utilizar `jQuery` 🤢, para este caso solo se utilizo `JS` puro lo cual también se conoce como `vanilla`.
	``` 
	    const compose = (...functions) => data => functions.reduceRight((value, func) => func(value), data);
	    
	    // Se utiliza $ para identificar que una variable o constante hace referencia
	    // a elementos del DOM
	    const $DESCRIPTION = document.getElementById("description");
	    const $CALORIAS = document.getElementById("calorias");
	    const $CARBOIDRATOS = document.getElementById("carboidratos");
	    const $PROTEINAS = document.getElementById("proteinas");
	    const ERROR_CLASS = "is-invalid";
	    const SUCCESS_CLASS = "is-valid";
	    
	    // Arreglo de elementos
	    let LIST = [];
	    
	    // consiguiendo los atributes para las etiquetas HTML
	    const attributesToString = (obj = {}) => {
	        const ENTRIES = Object.entries(obj);
	        const ATTRS = [];
	        for (let i = 0; i < ENTRIES.length; i += 1) {
	            const AUX = ENTRIES[i];
	            const ATTR = AUX[0];
	            const VALUE = AUX[1];
	            ATTRS.push(`${ATTR}="${VALUE}"`);
	        }
	        return ATTRS.join("");
	    };
	    
	    // Creando etiquetas html con atributos
	    const createTagAttr = obj => (content = "") => {
	        const { tag, attr } = obj;
	        return `
	          <${tag}${attr ? ` ${attributesToString(attr)}` : ""}>
	            ${content}
	          </${tag}>`;
	    };
	    
	    // Generando tag de maner dinamica
	    const createTag = (tag) => {
	        const TAG = (typeof tag === "string")
	            ? createTagAttr({ tag })
	            : createTagAttr(tag);
	        return TAG;
	    };
	    
	    const trashIcon = createTag({ tag: "i", attr: { class: "fas fa-trash-alt" } })("");
	    const tableCell = createTag("td");
	    const tableCells = items => items.map(tableCell).join("");
	    
	    const tableRowTag = createTag("tr");
	    const tableRow = items => compose(tableRowTag, tableCells)(items);
	    
	    
	    // Asignacion de evntos siempre que se desea asignar un evento aun elemento del DOM
	    // es necesario utilizar addEventListener
	    $DESCRIPTION.addEventListener("keypress", () => $DESCRIPTION.classList.remove(ERROR_CLASS));
	    $CALORIAS.addEventListener("keypress", () => $CALORIAS.classList.remove(ERROR_CLASS));
	    $CARBOIDRATOS.addEventListener("keypress", () => $CARBOIDRATOS.classList.remove(ERROR_CLASS));
	    $PROTEINAS.addEventListener("keypress", () => $PROTEINAS.classList.remove(ERROR_CLASS));
	    
	    // Limpiando inputs
	    const cleanInputs = () => {
	        $DESCRIPTION.classList.remove(SUCCESS_CLASS);
	        $DESCRIPTION.value = "";
	        $CALORIAS.classList.remove(SUCCESS_CLASS);
	        $CALORIAS.value = "";
	        $CARBOIDRATOS.classList.remove(SUCCESS_CLASS);
	        $CARBOIDRATOS.value = "";
	        $PROTEINAS.classList.remove(SUCCESS_CLASS);
	        $PROTEINAS.value = "";
	    };
	    
	    // Actualizando totales
	    const updateTotals = () => {
	        let carboidratos = 0;
	        let proteinas = 0;
	        let calorias = 0;
	        // Por buenas praxticas se utiliza un forEach y cumple la mism funcion que se busca
	        // practicamente una funcion de alto orden, no utiizo el map por que  map siempre regresa
	        // algo y de momento no importa capturar lo que regresa la iteracion que realizamos.
	        LIST.forEach((item) => {
	            carboidratos += item.carboidratos;
	            proteinas += item.proteinas;
	            calorias += item.calorias;
	        });
	        document.querySelector("#totalCalorias").textContent = calorias;
	        document.querySelector("#totalCarboidratos").textContent = carboidratos;
	        document.querySelector("#totalProteinas").textContent = proteinas;
	    };
	    
	    // Permite realizar el rendereo de los items
	    const renderItems = () => {
	        // otra manera de poder obtener un elemento por el name TAG
	        // solo que este metodo consigue un arreglo de elementos
	        const $CONTAINER = document.getElementsByTagName("tbody")[0];
	        $CONTAINER.innerHTML = "";
	        const ROWS = LIST.map((item, index) => {
	            const {
	                calorias, description,
	                carboidratos, proteinas,
	            } = item;
	            const removeButton = createTag({
	                tag: "button",
	                attr: {
	                    class: "btn btn-outline-danger",
	                    onclick: `removeItem(${index})`,
	                },
	            })(trashIcon);
	    
	            return tableRow([description, calorias, carboidratos, proteinas, removeButton]);
	        });
	        $CONTAINER.innerHTML = ROWS.join("");
	    };
	    
	    
	    // Agregar elementos en la lista
	    const addElement = () => {
	        const newItem = {
	            description: $DESCRIPTION.value,
	            calorias: parseInt($CALORIAS.value, 10),
	            carboidratos: parseInt($CARBOIDRATOS.value, 10),
	            proteinas: parseInt($PROTEINAS.value, 10),
	        };
	        LIST.push(newItem);
	        cleanInputs();
	        updateTotals();
	        renderItems();
	    };
	    
	    // funcion para validar los inputs
	    const validateInputs = () => {
	        // Por cuestion de buenas practicas el resultado de una condición
	        // Ternaria tiene que ser asignada a una variable o constante
	        const DESCRIPTION_CLASS = (($DESCRIPTION.value) ? SUCCESS_CLASS : ERROR_CLASS);
	        $DESCRIPTION.classList.add(DESCRIPTION_CLASS);
	    
	        const CALORIAS_CLASS = (($CALORIAS.value) ? SUCCESS_CLASS : ERROR_CLASS);
	        $CALORIAS.classList.add(CALORIAS_CLASS);
	    
	        const CARBOIDRATOS_CLASS = (($CARBOIDRATOS.value) ? SUCCESS_CLASS : ERROR_CLASS);
	        $CARBOIDRATOS.classList.add(CARBOIDRATOS_CLASS);
	    
	        const PROTEINAS_CLASS = (($PROTEINAS.value) ? SUCCESS_CLASS : ERROR_CLASS);
	        $PROTEINAS.classList.add(PROTEINAS_CLASS);
	    
	        if ($DESCRIPTION.value && $CALORIAS.value && $CARBOIDRATOS.value && $PROTEINAS.value) {
	            addElement();
	        }
	    };
	    
	    // Permite remover un item seleccionado
	    const removeItem = (position) => {
	        LIST = LIST.filter((item, index) => position !== index);
	        updateTotals();
	        renderItems();
	    };
	    
	```

* **Victor Lozada** (4) [505002](https://platzi.com/comentario/505002/) 

	Otra forma de eliminar el item de la lista es utilizando el metodo `.filter()` quedaria asi:
	``` 
	    const removeItem = (index) => {
	    //list.splice(index,1) esto sera sustituido por el código debajo 
	      list = list.filter((item,i) => i !== index)
	    
	      updateTotals()
	      renderItems()
	    }
	    
	    
	```
	
	Para saber mas sobre este método : [Array.prototype.filter() - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array/filter) 👍🏻

* **Julio J Yépez** (2) [492842](https://platzi.com/comentario/492842/) 

	En el min **`05:02`** se observa cómo se cambia la sintaxis de la _arrow function_ de **`item => {`** a **`(item, index) => {`**. Esto es porque al recibir solo un parámetro, no es necesario encerrarlo entre paréntesis, pero cuando es más de uno sí.

* **T-gold** (1) [1066789](https://platzi.com/comentario/1066789/) 

	Cuando elimino el item me dice que deleteItem no esta definida pero si lo esta  
	ademas la funcion me aparece sombreada como si nunca la hubiese llamado
	
	const deleteItem= (index)=>{  
	list.splice(index,1)
	``` 
	      updateTotals()  
	      renderItems()
	    }
	    
	    
	    
	    const renderItems = () => {
	    
	      const listWrapper = document.querySelector('tbody')
	    
	      listWrapper.innerHTML = ""  
	    
	      list.map((item,index) => {    
	        const boton = tag({
	          tag:"button",
	          attrs:{
	            class:"btn btn-outline-danger",
	            onclick: `deleteItem(${index}) ` 
	          },
	        })(trashIcon)
	        
	        listWrapper.innerHTML += tableRow([
	          item.description, 
	          item.calories, 
	          item.carbs, 
	          item.protein,
	          boton   
	        ])
	      })
	    }
	```

# Bonus: Declarative Programming [3374]

## 0220. Programación Declarativa [16966](https://platzi.com/clases/1497-funcional-js/16966-declarative-programming/)

### Descripción:


La programación imperativa consiste en explicar paso a paso cómo conseguir un resultado, en cambio, la programación declarativa se centra en qué hay que hacer.

Podemos utilizar programación declarativa trabajando con funciones especiales de JavaScript. Por ejemplo, en vez de utilizar un ciclo `for`, podemos utilizar la función `.map` para ejecutar alguna función en cada elemento de una _array_ , el resultado es el mismo pero, cuando utilizamos métodos declarativos es mucho más fácil de leer y entender nuestro código a primera vista.

### Comentarios:

* **Juan David Castro (Platzi)** (7) [491874](https://platzi.com/comentario/491874/) 

	Estos conceptos también se pueden aplicar a la estructura de carpetas de nuestras aplicaciones:
	``` 
	    // Traditional MVC:
	    - Controllers/{auth, blog, search, ...}
	    - Models/{...}
	    - Views/{...}
	    
	    // Qué en vez de cómo:
	    - Auth/{model,controller,view}
	    - Blog/{...}
	    - Pay/{...}
	    - Search/{...}
	    ...
	    
	```
	
	* [The life-changing (and time-saving!) magic of Feature Focused code organisation.](https://builtwithdot.net/blog/changing-how-your-code-is-organized-could-speed-development-from-weeks-to-days)
	
	

	* **Julio J Yépez** [491874] (2)

		¡Qué interesante enfoque aplicado a la organización de las carpetas!  
		Ilustra muy bien la diferencia.

* **Juan David Castro (Platzi)** (6) [486764](https://platzi.com/comentario/486764/) 

	Otro muy buen ejemplo de programación declarativa es el método `.filter` de JavaScript (ni siquiera debo explicar qué es lo que hace porque es más que claro) 😛:
	``` 
	    // Imperative
	    const arr = [1, 2, 3, 4]
	    const arr2 = []
	    
	    for (let i = 0; i < arr.length; i++) {
	            if (arr[i] % 2) {
	                    arr2.push(arr[i])
	            }
	    }
	    
	    console.log(arr2) // [1, 3]
	    
	    // Declarative
	    const numbers = [1, 2, 3, 4]
	    const oddNumbers = numbers.filter(number => number % 2)
	    
	    console.log(oddNumbers) // [1, 3]
	    
	```

	* **Carlos Gómez Mont** [486764] (1)

		Gracias por compartir, saludos!!

* **Fernando Alejandro Yerena Ramos** (5) [616311](https://platzi.com/comentario/616311/) 

	Avanzando con el proyecto, agregué la opción de modificar los valores la lista de _items_.
	
	Todo consejo y PR es bienvenido:
	
	* [Repositorio - Calories Counter](https://github.com/ferdinandalexa/Calories_Counter).
	* [Github Page - Calories Counter](https://ferdinandalexa.github.io/Calories_Counter/)
	
	
	
	ñ.ñ/

	* **Cristian Fabian Tovar** [616311] (2)

		Yo me ahorré bastante tiempo con ese repositorio

* **Julio J Yépez** (5) [492862](https://platzi.com/comentario/492862/) 

	Entonces, según el concepto simplificado de lo que es la **Programación Declarativa** y en particular la **Programación Funcional** , ¿sería posible concluir que es contra-intuitiva en relación a los enfoques de algoritmos más tradicionales como los diagramas de flujo y el pseudocódigo de la programación estructurada?
	
	Y, si este es el paradigma de la programación ideal, ¿lo que estamos aprendiendo en la mayoría de las escuelas tradicionales será tarde o temprano completamente inútil? 🤔 Quizás solo sirva un poco para incentivar la formación del pensamiento lógico / algorítmico y nada más …
	
	¿opiniones?

	* **WilliamVelazquez** [492862] (1)

		Creo que es bueno conocer ambos paradigmas, quizá en cuestión académica sea más fácil explicar como actualmente se hace y por lo mismo seguirá de esa forma, sin embargo, deberían una vez comprendido de esa manera cambiarlo a este paradigma.

	* **WilliamVelazquez** [492862] (2)

		Por otro lado nos sirve el pseudocódigo de la programación estructurada para explicar algo a personas ‘NO’ técnicas y que necesitan entender ciertos procesos del negocio. Quizá si no se enseñara así nos resultaría más difícil explicar el cómo con los demás.  
		Algunas personas no están conformes con el “Qué harás?” algunos inversionistas o accionistas querrán el “Cómo lo harás?”, aunque al final en la implementación ya será de la forma más óptima posible. 😉
		
		En mi humilde opinión. Saludos JJ! 😃

* **Julio J Yépez** (5) [492858](https://platzi.com/comentario/492858/) 

	```
	    // IF imperativo
	    letvar// --- genera un estado mutable ... no funcional
	    if( condicion ){
	      var = hacerAlgo()
	    } else {
	      var = hacerOtraCosa()
	    }
	    
	    // IF declarativo (ternario) - Programación Funcional
	    constvar = condicion ? hacerAlgo() : hacerOtraCosa
	    
	```
	
	La manera declarativa en la Programación Funcional es más corta, más clara, más mantenible y no requiere de un estado mutable

* **Juan David Castro (Platzi)** (4) [486765](https://platzi.com/comentario/486765/) 

	* [From imperative to functional JavaScript](https://codeburst.io/from-imperative-to-functional-javascript-5dc9e16d9184) 😬
	
	

	* **Carlos Gómez Mont** [486765] (1)

		Super aporte, gracias!!

* **Kingsman7** (3) [642226](https://platzi.com/comentario/642226/) 

	esta clase se llama. La paciencia es una Virtud

* **David Antonio Ordóñez Cornejo** (2) [548130](https://platzi.com/comentario/548130/) 

	Como comenta el profe en esta clase, la programación declarativa se trata más de describir qué se evalua vs el cómo se evalúa(imperativa)
	
	Sin embargo creo que los ejemplos que pone el profe se refieren a un estilo de programar que da preferencia a las expressions que a los statements, pues los statements pueden crear efectos laterales y mutabilidad.  
	¿Qué opinan?

* **Victor Lozada** (2) [505008](https://platzi.com/comentario/505008/) 

	Alguno le ha dado un vistazo a los `Pipeline Operators` ? Opinan a que nos ayudaría a tener un código mas declarativo y atendible ? ([Pipeline Operators | MDN ](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Pipeline_operator))

	* **WilliamVelazquez** [505008] (1)

		Suena como a ver las cosas más Human Readable, es decir, en lugar de buscar el “( )” más anidado y de ahí realizar las operaciones, seguirás el orden de lectura tradicional, o sea, realizar todo en orden conforme lo vas leyendo.  
		Pero no sé, creo ya estamos acostumbrados a la nomenclatura actual.  
		Saludos!

# Conclusiones [3373]

## 0230. Conclusiones [16965](https://platzi.com/clases/1497-funcional-js/16965-conclusiones7125/)

### Descripción:


¡Felicitaciones por terminar el Curso de Programación Funcional en JavaScript!

Ahora conocemos la diferencia entre escribir código de forma imperativa y declarativa, también dominamos conceptos como _Closures_ , _Currying_ , Funciones puras, inmutabilidad, entre otros. Gracias a esto podemos escribir código mucho más fácil de leer y testear.

No olvides completar el proyecto del curso, aprobar el examen y tomar otros cursos excelentes para complementar todo lo que aprendiste:

* [Carrera de Backend con JavaScript](https://platzi.com/backend-javascript/)
* [Curso de Jest](https://platzi.com/jest)
* [Curso de Programación Orientada a Objetos: POO](https://platzi.com/cursos/oop/)
* [Curso de Introducción a PHP](https://platzi.com/php/)



### Comentarios:

* **Julio J Yépez** (13) [492868](https://platzi.com/comentario/492868/) 

	**Dato curioso:**  
	Aún cuando en JavaScript se pueden implementar los principios básicos de la Programación Funcional, este no es un lenguaje ideal para el máximo aprovechamiento de los beneficios de este paradigma, sino que más bien ha ido adoptando estos conceptos y técnicas para hacerse más robusto y acorde con areas del conocimiento que son más estrictas y rigurosas, como es el caso de las **Matemáticas**.
	
	De hecho es poco conocido por los desarrolladores en general que existen lenguajes de programación que realmente fueron creados pensando en este paradigma desde su esencia. A estos lenguajes se les llama **Puros**.
	
	A continuación una lista de lenguajes **Puros** e **Impuros** que implementan los principios de la **Programación Funcional**.
	
	## Puros:
	
	* Agda
	* Charity
	* Clean
	* Coq (Gallina)
	* Cuneiform
	* Curry
	* Elm
	* Haskell
	* Hope
	* Idris
	* Joy
	* Mercury
	* Miranda
	* KRC
	* SAC
	* SASL
	* SequenceL
	
	
	
	## Impuros:
	
	* APL
	* ATS
	* CAL
	* C++ (a partir de C++11)
	* C#
	* Ceylon
	* D
	* Dart
	* Curl
	* ECMAScript
	* ActionScript
	* ECMAScript for XML
	* JavaScript
	* JScript
	* Erlang
	* Elixir
	* LFE
	* F#
	* Groovy
	* Hop
	* J
	* Java (since version 8)
	* Julia
	* Kotlin
	* Lisp
	* Clojure
	* Common Lisp
	* Dylan
	* Emacs Lisp
	* LFE
	* Little b
	* Logo
	* Scheme
	* Racket (formerly PLT Scheme)
	* Tea
	* Mathematica
	* ML
	* Standard ML (SML)
	* Alice
	* OCaml
	* Nemerle
	* Nim
	* Opal
	* OPS5
	* Perl
	* Perl 6
	* PHP
	* Python
	* Q (equational programming language)
	* Q (programming language from Kx Systems)
	* R
	* Red
	* Ruby
	* REFAL
	* Rust
	* Scala
	* Spreadsheets
	* Wolfram Language
	
	

	* **David Antonio Ordóñez Cornejo** [492868] (1)

		Muy buen aporte

* **Juan David Castro (Platzi)** (7) [486766](https://platzi.com/comentario/486766/) 

	¡Otros artículos para mejorar y aplicar todo lo que aprendimos en el curso 🎉!
	
	* [Understanding Design Patterns in JavaScript](https://blog.bitsrc.io/understanding-design-patterns-in-javascript-13345223f2dd)
	* [Understanding Throttling and Debouncing](https://blog.bitsrc.io/understanding-throttling-and-debouncing-973131c1ba07)
	
	

* **Cristobal Peña** (2) [1049872](https://platzi.com/comentario/1049872/) 

	Para ser sincero no me gustó mucho el curso. Esperaba algo más como el curso de Programación Orietada a Objetos (<http://platzi.com/clases/oop/>), en el que se explicaron los conceptos fundamentales de ese paradigma mediante ejemplos muy sencillos, construidos íntegramente durante el desarrollo del curso. Fue un curso espectacular.  
	Tal vez este sea un curso más avanzado, pero yo que vengo siguiendo la ruta de aprendizaje de la Escuela de Javascript y se me hizo complejo.
	
	Mi crítica principal es que dediqué más neuronas a entender el código del proyecto (por ejemplo no conozco jquery) que en asimilar los conceptos de la PF.
	
	Es mi humilde opinión.  
	Saludos.

* **Byhako** (2) [938309](https://platzi.com/comentario/938309/) 

	Un excelente curso, todo muy claro pero me parece un poco extraño que Freddy normalmente nos dice que jQuery ya no se usa, y sin embargo tiene cursos basados en jQuery.

* **WilliamVelazquez** (2) [546288](https://platzi.com/comentario/546288/) 

	Si esos son los conceptos fundamentales, Cuáles son los temas avanzados para dominar la programación funcional? 😮

	* **Julio J Yépez** [546288] (4)

		Jejeje Willliam, los temas avanzados son precisamente poner en práctica todos estos conceptos en un proyecto complejo, en el que participen múltiples desarrolladores y que todos manejen el mismo estilo de programación y el mantenimiento como un reloj suizo! XD … #SíSePuede!

	* **David Antonio Ordóñez Cornejo** [546288] (3)

		Podría decir que son:  
		functors,  
		Monoids,  
		Monads,  
		Partial application,  
		Polimorfismo funcional  
		Y algun largo etcetera

	* **WilliamVelazquez** [546288] (1)

		Jeje pues a practicar Julio! xD

	* **WilliamVelazquez** [546288] (2)

		😮 No Suenan intensos esos puntos david!  
		Les daré una revisada! Gracias 😄  
		Saludos!

	* **David Antonio Ordóñez Cornejo** [546288] (4)

		Hay dos materiales que conozco de programación funcional en Javascript que revisan conceptos mas avanzados:
		
		[Conference: Functional Programming Design Patterns by Scott Wlaschin](https://www.youtube.com/watch?v=E8I19uA-wGY&t=442s)  
		[Book: Functional Programming in Javascript(Luis Atencio)](https://www.amazon.com/Functional-Programming-JavaScript-functional-techniques/dp/1617292826)
		
		Saludos!

	* **David Antonio Ordóñez Cornejo** [546288] (1)

		Aunque la primer liga es un video mas en el contexto de F#, pero los conceptos son muy interesantes y aplicables a JS.

	* **WilliamVelazquez** [546288] (1)

		Perfecto David, gracias 😃  
		Veré los recursos que compartes.  
		Saludos!

* **Julio J Yépez** (2) [492863](https://platzi.com/comentario/492863/) 

	¡Gracias David por un curso realmente interesante!  
	¡Buen trabajo! 👏👏👏

* **lizardojara** (1) [878385](https://platzi.com/comentario/878385/) 

	Un curso muy interesante, siempre es bueno repasar los conceptos fundamentales.

* **edanfesi** (1) [842674](https://platzi.com/comentario/842674/) 

	¡Excelente curso! Me encantaron todas las explicaciones.

* **lechesdarwin** (1) [807579](https://platzi.com/comentario/807579/) 

	Aqui hablan sobre el tema de “y combinator” en el area de las mates no la empresa?

* **David Antonio Ordóñez Cornejo** (1) [548131](https://platzi.com/comentario/548131/) 

	Muchas Gracias, fue un gran curso!!

* **Marlet Rodríguez de Anda** (1) [529203](https://platzi.com/comentario/529203/) 

	Super David!!!

* **csrarias** (1) [496997](https://platzi.com/comentario/496997/) 

	excelente curso aunque tender que verlo varias veces para entender bien este tipo de programacion

* **Juan David Castro (Platzi)** (1) [486769](https://platzi.com/comentario/486769/) 

	* [10 errores comunes de programadores junior | PlatziLive](https://www.youtube.com/watch?v=YJ0u-MpYpM4&t=1s) 😬
	
	

* **WilliamVelazquez** (1) [55885](https://platzi.com/comentario/546288/) 
Si esos son los conceptos fundamentales, Cuáles son los temas avanzados para dominar la programación funcional? 😮

	* **Julio J Yépez** [55885] (4)

		Jejeje Willliam, los temas avanzados son precisamente poner en práctica todos estos conceptos en un proyecto complejo, en el que participen múltiples desarrolladores y que todos manejen el mismo estilo de programación y el mantenimiento como un reloj suizo! XD … #SíSePuede!

