# Bienvenida

## 0010. Introducción y bienvenida al curso

### Descripción:


### Links:

* [Curso de Prework: Buenas Prácticas y Entorno de Desarrollo](https://platzi.com/cursos/prework/)

* [Curso Online de Fundamentos de JavaScript | Platzi](https://platzi.com/cursos/fundamentos-javascript/)

### Comentarios:

* **Mariana Valencia** (3)

	
	Este tema justamente lo estoy reforzando para entender el closure que se da en los hooks de React. Gracias 😄

* **alvaritokore** (2)

	
	Empezemos!!

* **lmoran** (1)

	
	A darle!

* **jesus-cruz-dominguez** (1)

	
	A seguir aprendiendo!

* **MartinMB** (1)

	
	A full

* **Karla Agraz** (1)

	
	👀👀

	* **OmarGbet** (1)

		
		Te sigo en Twitter, hola Karla (:

	* **Karla Agraz** (1)

		
		¡Holaa! 😄

* **Manuel Rivera** (1)

	
	😄

* **Camilo Alexander Velandia Velandia** (1)

	
	vamoss!!

* **JhonColorado07** (1)

	
	Vamos a seguir aprendiendo.

* **predator0077** (1)

	
	Vamos a darle con todo a este hermoso curso!!!

* **maria-del-carmen-rodriguez** (1)

	
	uauauauaua

* **ivofacundo** (1)

	
	vamos con otro curso más!!

* **Jean Carlos Nuñez Hernandez** (1)

	
	ufff tremendo curso

* **Kevin Jeremy Salazar Jimenez** (1)

	
	vamoh a darle

* **ferchodleon** (1)

	
	Aquí vamos!!!

* **Juan Carlos Valencia López** (1)

	
	starting

* **Harold David Molina Figueroa** (1)

	
	Comencemos

# Scope

## 0020. Qué es el Scope y cómo funciona el Global Scope

### Descripción:


### Links:

* [Download Visual Studio Code - Mac, Linux, Windows](https://code.visualstudio.com/download)

* [Code Runner - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)

### Comentarios:

* **Karla Agraz** (7)

	
	Scope: Es el alcance que va a tener una variable dentro del código. En otras palabras, el Scope se encargará de decidir a que bloques de código va a acceder una variable.
	
	**Global Scope** : No están dentro de funciones o bloques, por lo tanto se puede acceder a ellas de manera global.
	
	  * Con var podemos re-asignar una variable pero es una mala práctica.
	
	  * Con let y const no podemos, aparecerá un error.
	
	  * Es una mala práctica crear una variable sin las palabras reservadas: var, let y const.  
	Si se asigna una variable dentro de una función sin las palabras reservadas será una variable global.
	
	  * La doble asignación de una variable también es una mala práctica.
	
	
	

	* **Nathaly Stefani Riaño Bejarano** (2)

		
		Gran aporte! Gracias

* **Facundo Nicolás García Martoni (Platzi)** (6)

	
	Además de la extensión recomendada por Oscar en esta clase, pueden usar [nodemon](https://nodemon.io/) para ejecutar sus programas de JavaScript de manera instantánea al guardar el archivo 😃

* **Jose Armando Acevedo Angarita** (4)

	
	el comando para dejar todo por defecto en npm init es: npm init -y

	* **Jean Carlos Nuñez Hernandez** (1)

		
		si

	* **María José Ledesma (Platzi)** (1)

		
		¡Muchas gracias por el aporte!
		
		**¡Nunca pares de aprender!** 🦄

* **Daniel Hurtado** (4)

	
	Usen NPM init -y si no van a cambiar ningún valor por defecto (equivalente a enter enter enter enter)

* **Jair Israel Avilés Eusebio** (3)

	
	¿Cual es el Theme que el profesor tiene instalado en VScode? Me gusto bastante 😄

* **Cristian3** (3)

	
	Scopes de:
	
	  * **var** puede sobrescribir la declaración y asignación de una variable y alterar su valor
	  * **let** no permite volver a declarar una variable con el mismo nombre pero permite la asignación de un nuevo valor
	  * **const** tampoco permite reasignar una declaración ni asignación de un nuevo valor
	
	
	
	Una variable **sin var, let o const** , dentro de una función puede ser reconocida como una variable global pero esto es una mala práctica.

* **Mariana Valencia** (3)

	
	Para profundizar en por qué sucede todo esto, les recomiendo el libro “You don’t know JavaScript yet” que lo encuentran gratis en Github. Es denso pero vale la pena

	* **Rene Ismael Barrios Rojas** (1)

		
		Sera que tendras la Url por favor? 😃

	* **Rene Ismael Barrios Rojas** (1)

		
		Ya la encontre, muchas gracias por la recomendación. Gracias.

* **maria-del-carmen-rodriguez** (3)

	
	La palabra asignar puede sonar raro, creo que mas bien el instructor hace referencia a declarar, con la palabra var si se puede declarar de nuevo una variable, aunque eso es mala practica, pero con let no se puede declarar mas de una vez una variable dentro de un mismo scope, en cuanto a const aquí si no se puede asignar ni declarar por mas de 1 vez dentro de un mismo scope

* **José Arturo Soto Calderón** (2)

	
	Espero les sirva de apoyo.  
	<https://github.com/Jasaron1997/Platzi-Closures-Scope-JavaScript>  
	Es el codigo de las clases.

	* **María José Ledesma (Platzi)** (1)

		
		¡Muchas gracias por el aporte!
		
		**¡Nunca pares de aprender!** 🦄

	* **Cristian Fabian Tovar** (1)

		
		Bien parce!! me ahorraste un montón de tiempo

* **Santiago Jimenez** (1)

	
	[Running] node “c:\Users\EQUIPO\OneDrive\Escritorio\platzi java\closures y scope\tempCodeRunnerFile.js”  
	“node” no se reconoce como un comando interno o externo,  
	programa o archivo por lotes ejecutable.
	
	me sale eso error y no se como mejorarlo

* **Santiago Jimenez** (1)

	
	me sale este error “node” no se reconoce como un comando interno o externo,  
	programa o archivo por lotes ejecutable.

* **lmoran** (1)

	```
	    //MALAS PRACTICAS:
	    // Declarar solo nombre de variables sin su  tipo.
	    const helloWorlds = () => {
	      global = 'helloooo'
	    }
	    helloWorlds()
	    console.log(global)
	    
	    // Declarar la variable dentro de la función dos veces:
	    const helloWorlds = () => {
	      var global1 = (globalVar = 'helloooo luis')
	    }
	    helloWorlds()
	    console.log(globalVar)
	    
	```

* **Miguel Angel Martelo Quiroz** (1)

	
	`var``let` y `const` pueden usarse para crear variables globales, pero solamente `var` puede ser reasignada.
	
	estableciendo una variable sin las palabras reservadas `var let const` se puede asignar una variable global dentro de una función, es una MALA PRACTICA

* **juan martinez lopez** (1)

	
	Tengo una duda veo que el profe en los ejemplos de **globalVar** en el primero una el mismo nombre de la variable const helloWorld y el segundo ejemplo usa el mismo nombre de la función anotherFunction y le funciona bien no le afecta con las anteriores. Yo lo hice asi y me sale un error y si les cambio el nombre si me funciona bien

	* **Jair Israel Avilés Eusebio** (1)

		
		¿Cual fue el error que te salia? Probablemente se trate de una declaracion de variables duplicada.

	* **juan martinez lopez** (1)

		
		si digamos eran variables con el mismo nombre pero al profe si le corrieron pero a mi no tuve que cambiarles el nombre

* **joaquin-fontela** (1)

	
	Al intentar ejecutar dentro de Visual Studio me aparece lo siguiente:
	``` 
	    [Running] node "c:\Users\jocaf\desktop\joaquin\platzi\Platzi - Curso de Closures y Scope en JavaScript\src\Scope\tempCodeRunnerFile.js"
	    'node' isnot recognized as an internal or external command,
	    operable program or batch file.
	    
	    [Done] exited with code=1in0.077 seconds```
	    
	```

	* **Estanislao Albin Wotoszyn Grillo** (3)

		
		Chequea que tengas instalado node y que esté agregado al path

* **MartinMB** (1)

	
	No hacer, ok

* **OmarGbet** (1)

	
	Solo Var puede ser reasignado

	* **miguelangelsoler** (2)

		
		A las variables declaradas con **let** , tambien podemos reasignarles un valor, pero a diferencia de **var** no podemos volver a declarar una variable con el mismo nombre, algo asi:
		``` 
		    letmyVariable = 9
		    const myBoolean = true
		    if(myBoolean){
		      myVariable = "Im reasigned value"
		    }
		    
		    console.log(myVariable)
		    
		```

* **gorydev** (1)
var permite volver a declarar y reasignar una variable, let permite reasignar el valor de una variable pero no declararla de nuevo y const no permite que la variable sea reasignada o declarada de nuevo con excepción de objetos los cuales pueden ser mutados en sus propiedades aún si están declarados con const

* **Cristobal Peña** (1)

	
	No me dejó colocar la licencia MIT, por lo que tuve que dejar la que aparecía por defecto, la ISC. Está bien eso o me puede generar problemas después?

	* **hansfpc** (3)

		
		Está bien

* **Cristobal Peña** (1)

	
	Antes de hacer este curso me recomiendan haber hecho el de npm?

	* **miguelangelsoler** (1)

		
		No es necesario para este curso.

* **Mateo Aquino** (1)

	
	Entonces, si yo asigno una variable dentro de una función al ejecutarla, ¿la variable pasa a vivir dentro del entorno global?

	* **Manuel Rivera** (2)

		
		No, cuando utilizas la palabra reservada let y const, estan quedan disponibles solamente en el scope o bloque de código en el cuál fueron declaradas.  
		Te recomiendo este curso <https://platzi.com/clases/basico-javascript/>

	* **Manuel Rivera** (1)

		
		Puedes acceder desde el scope local al scope global, pero del global al local, no

	* **Jair Israel Avilés Eusebio** (1)

		
		Complementando el comentario anterior, si no especificas var, let o const en la declaracion de una variable dentro de una funcion si es reconocida como variable global (hoisting) aunque enfatizando lo que el profesor menciona, es una mala practica hacer esto.

* **JhonColorado07** (1)

	
	Excelentes tip a tener en cuenta con las variables globales.

* **klopo** (1)

	
	Necesito una aclaración!, entre 8:15 y 8:32 dice que solo var puede ser reasignada y que con let y const no vamos a poder asignar ningun valor a lo que ya hemos establecido!  
	Aclarenme, por que para mi let si deja reasignar valores, solo const es la que no!

	* **Juan Carrillo** (3)

		
		Obviamente hubo un error en tiempo de ejecución del video, quizás quería explicar el concepto con **const** , que **no puede ser reasignada **ya que es eso, una constante, aunque esto no aplica para todos los casos como cuando usamos const con listas u objetos.
		
		El detalle acá es que si miras con detenimiento usó:
		
		`let world = 'algo' let world = 'algo'`  
		y el error que muestra es porque se está redeclarando la variable, Caso contrario hacer:
		
		`world = 'algo',` no habría causado problemas.
		
		Así que asumo que el ejemplo que iba a dar era con const.

	* **César Oswaldo Mandamiento Salas** (3)

		
		No te confundas, lo que quiere decir Oscar es que con **var** tu puedes usar el mismo nombre de variable N veces e igual va a funcionar (tomando siempre el último valor en el orden de ejecución):
		``` 
		    var code = 'javascript';
		    var code = 'js';
		    // code = js
		    
		```
		
		Mientras que con **let** , si tu haz declarado una variable con let, no puedes volver a declarar la misma variable. Puedes cambiar su valor, pero no volverla a declarar.
		``` 
		    let code = 'javascript';
		    let code = 'js';
		    // ERROR! code ya existe.
		    // Si deseas obtener el mismo resultado que en **var**, sería:
		    let code = 'javascript';
		    code = 'js';
		    // code = js
		    
		```

* **Alejandra Iza** (1)

	
	Que plugin utilizas para los typos?

	* **David Flores** (3)

		
		[Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)

* **Jean Carlos Nuñez Hernandez** (1)

	
	El scope va a decidir a que bloque de codigo esta disponible

* **Cristobal Peña** (1)
Al declarar una variable sin las palabras reservadas var, let o const , como lo que hizo en la linea 17, en el fondo ¿es el equi...

	* **lokoplus** (1)

		
		Javascript te permite crear variables sin las palabras reservadas _var_ , _let_ o _const_

## 0030. Local Scope

### Descripción:


### Comentarios:

* **ivofacundo** (10)

	
	Lexical Scope / Ámbito Léxico: El intérprete de JavaScript funciona desde el ámbito de ejecución actual y funciona hasta encontrar la variable en cuestión. Si la variable no se encuentra en ningún ámbito, se genera una excepción.
	
	Este tipo de búsqueda se llama ámbito léxico. El alcance de una variable se define por su ubicación dentro del código fuente, y las funciones anidadas tienen acceso a las variables declaradas en su alcance externo. No importa de dónde se llame una función, o incluso cómo se llama, su alcance léxico depende solo de dónde se declaró la función.

	* **María José Ledesma (Platzi)** (1)

		
		¡Muchas gracias por el aporte!  
		**¡Nunca pares de aprender!** 🦄

	* **Nathaly Stefani Riaño Bejarano** (1)

		
		Excelente aclaración del concepto!

* **Cristian3** (4)

	
	El **scope local** nos permite acceder una variable en un bloque de código o estructura, como las funciones. Por lo tanto el scope global no puede acceder a las variables dentro de un bloque de código.
	
	**Si se anida una función dentro de otra** , las variables de la primera función van a poder ser accedidas dentro de la segunda.

* **eocas98** (4)

	
	Lo que entendí del ámbito léxico es que a pesar que tengas una variable global declarada e inicializada, puedes tener la misma variable declarada e inicializada con otro valor dentro de una función y esta última no reasignará su valor a la variable global.

* **Diego Alberto González González** (2)

	
	AL ser una variable global y ser declarada con var, cuando se utiliza dentro de una funcion, puede reasignarse su valor.
	
	Después cuando se declara una funcion dentro de la mima función y se regresa el valor de la variable local de la primera función, la variable local se hace global dentro de ese contexto. Por lo que el resultado es I am local.
	
	No se si me redacción fue lo bastante buena para darme a entender jaja

	* **María José Ledesma (Platzi)** (1)

		
		¡Gracias por el aporte, _Diego_!  
		**¡Nunca pares de aprender!** 🦄

* **lmoran** (1)

	```
	    //ambito lexico:
	    var global = 'I am global'
	    const helloWorld = () => {
	      var global = 'I am local'
	      constfunc = () => {
	        returnglobal
	      }
	      //va imprimir la variable local i am local
	      console.log(func())
	    }
	    helloWorld()
	    //va imprimir la variable global i am global
	    console.log(global)
	    
	```

* **MartinMB** (1)

	
	Muy interesante

* **Nathaly Stefani Riaño Bejarano** (1)

	
	Para que el código no se reviente, podemos agregar un try…catch
	``` 
	    const helloWorld = () => {
	      const hello = "Hello World!";
	      console.log("local hello:::: ", hello);
	    };
	    
	    helloWorld();
	    
	    try {
	      console.log("global hello:::: ", hello);
	    } catch (error) {
	      console.log("global hello error:::: ", error);
	    }
	    
	```

* **Karla Agraz** (1)

	
	Scope Local: Nos permite acceder a una variable en un bloque de código o una función, sólo tenemos acceso a ella en esa estructura.

* **JhonColorado07** (1)

	
	Good

	* **María José Ledesma (Platzi)** (2)

		
		 **¡Nunca pares de aprender!** 🦄

## 0040. Function Scope

### Descripción:


### Comentarios:

* **Freddy Lemus Barrera** (6)

	
	Siempre utilizar let y const, var es peligrosa. Gracias por esta clase.

* **mafevito** (5)

	
	Un pequeño resumen sobre como actúan las diferentes variables:
	
	  * Las variables escritas con la palabra clave **var** pueden ser redeclaradas, pero esto a futuro puede darnos problemas, así que es mejor no usarla.
	
	  * Las variables escritas con la palabra clave **let** no pueden ser redeclaradas, si lo haces mostrara un _**“error: esta variable ya ha sido declarada”**_ , pero su valor puede ser reasignado:
	
	
	
	``` 
	    let fruit = "apple";
	    fruit = "banana";
	    
	    console.log(fruit); // banana
	    
	```
	
	  * Las variables escritas con la palabra clave **const** no pueden ser redeclaradas o reasignadas, ya que const quiere decir que su valor será constante, es decir que no va a cambiar.
	
	

* **Camilo Ernesto Hurtado Cataño** (2)

	
	Para mi **let** se puede reasignar, mas no volver a declarar una variable con el mismo nombre, const no permite reasignar un valor

* **miguelangelsoler** (2)

	
	Desde la llegada de **let** y **const** , es casi obligatorio usar estas keywords y dejar **var** en el olvido.

* **lmoran** (1)

	
	Tener en cuenta let a = 3 let a = 4 no funciona, pero si colocamos let a = 3 y a = 4 si va funcionar:
	``` 
	    //otro ejemplo de reasinacion:
	    const antotherFunction = () => {
	      var x = 1
	      var x = 2
	      let a = 3
	      //error no se puede reasignar
	      // let a = 4
	      //una mala practica:
	      a = 4
	      console.log(x)
	      console.log(a)
	    }
	    antotherFunction()
	    
	```

* **jesus-cruz-dominguez** (1)

	
	Usar let y const en la mayor medida posible

* **Cristian3** (1)

	
	Las variables con **let** y **const** no se pueden volver asignar, esto nos ayuda a no sobre escribir los valores de nuestras variables erróneamente. La desventaja de usar **var** es que si no se tiene cuidado puede sobrescribir valores en nuestra variable y se aconseja no usarla.

	* **Jair Israel Avilés Eusebio** (1)

		
		Yo lo entiendo mas bien que defiendo variables con **let** y **const** no se pueden volver a declarar una existente. Usando **let** , permite asignar el valor sin restriccion, no asi con **const**.

* **Manuel Rivera** (1)

	
	Cuando declaramos una variable
	``` 
	    var example = 1
	    example = 2
	    
	    letexample1 = 1
	    example1 = 2
	    
	    const example2 = 1
	    example2 = 2
	    
	    
	    
	```
	
	La unica que no se puede reasignar un valor es a const

	* **María José Ledesma (Platzi)** (1)

		
		¡Muchas gracias por el aporte, _ManuelR_!
		
		**¡Nunca pares de aprender!** 🦄

	* **chavwilh_platzi** (1)

		
		Aunque somos estudiantes en esta plataforma, te recomiendo que coloques tus comentarios completos porque la idea es que nos convirtamos en profesionales, ej:  
		var example = 1;  
		var example =2;
		
		let example = 1;  
		.  
		.  
		.  
		por otra parte dentro de la función tampoco se puede reasignar variables declaradas con ‘Let’

	* **Manuel Rivera** (1)

		
		No entendí tu aporte bro , a que te refieres con comentarios completos ?

* **JhonColorado07** (1)

	
	Ok, buena recomendación.

## 0050. Block Scope

### Descripción:


### Comentarios:

* **David Behar** (9)

	
	## Un videíto increíble de var, let y const por si gustan entender mejor el scope
	
	.  
	[![var.png](https://static.platzi.com/media/user_upload/var-a6c190b4-ce6f-4e24-9ec8-17c4eb850221.jpg)](https://www.youtube.com/watch?v=ojrvxYcKeYg)  
	<https://www.youtube.com/watch?v=ojrvxYcKeYg>

	* **César Oswaldo Mandamiento Salas** (2)

		
		Valiosisimo aporte, se agradece

* **Jair Israel Avilés Eusebio** (3)

	
	<https://platzi.com/clases/1807-scope/25874-block-scope/?time=417> Esta fue una pregunta de entrevista de screening, define la salida de una ciclo usando var y let dentro de un setTimeout ¿cual es la salida? 😉

* **lmoran** (2)

	
	En for no debemos utilizar var i = 0 porque al imprimir va imprimir 10 veces el ultimo valor, ejemplo:
	``` 
	    //forno debemos utilizar var sino let
	    const anotherFunction = () => {
	      for (var i = 0; i < 10; i++) {
	        setTimeout(() => {
	          console.log(i)
	        }, 1000)
	      }
	    }
	    anotherFunction()
	    
	```
	
	Va imprimir: 10 10 10 10 10 10 10 10 10 10  
	**Pero con let: **
	``` 
	    const anotherFunction = () => {
	      for (let i = 0; i < 10; i++) {
	        setTimeout(() => {
	          console.log(i)
	        }, 1000)
	      }
	    }
	    anotherFunction()
	    
	```
	
	Va imprimir: 0 1 2 3 4 5 6 7 8 9

* **Cristian3** (2)

	
	Cuando declaramos una variable tipo **var** dentro de una función su scope va a poder ser accedido desde cualquier bloque dentro de la función. **Let** y **const** por otro lado solo funcionaran dentro del bloque declarado.

* **OmarGbet** (2)

	
	Oscar lo explica perfecto pero por si gustan otro ejemplo adicional recomiendo este video: [https://youtu.be/kQwaq2MMZ-Y](url)

* **Karla Agraz** (2)

	
	Dentro de una función podemos tener un bloque de código, por ejemplo: un if, mientras lo llamamos sobre una llave estará guardado dentro de un bloque.
	
	Si definimos un elemento con var podemos acceder en todos los elementos de la función, si lo llamamos fuera del bloque donde está, vamos a poder acceder a ese elemento.
	
	Con let y const no vamos a poder acceder a ellos porque se establecen dentro del bloque, solo se puede acceder a ellos dentro de ese bloque.

* **Roberto Bock** (2)

	
	Ok!! no sabía eso de quel scope del var aplica dentro de una función y que el scope del let y const aplica dentro de un bloque, mind blowing!

* **ivofacundo** (2)

	
	sigo sin entender el ejemplo del for y el setTimeout.
	
	traté de ejemplificarlo en mi cabeza llevándol al proceso que haría el engine de JS (callstack, callback queue, event loop, etc), pero me sigue sin cuadrar algunas cosas

	* **edanfesi** (2)

		
		lo que ocurre es que estamos definiendo la variable con `var` por ende hace que su scope sea global al momento de definirla. El for realiza la llamada 11 veces del timeOut y en cada llamada el for loop va incrementando el valor de i. Al momento de que se realice la llamada del `console.log(i)` entonces el valor de i ya es 10.

	* **David Flores** (7)

		
		Por cada iteración, a la cola de tareas se va el **setTimeout** con un valor de i, cuando es **let** , este valor no cambio por que su alcance es local y la cola de tareas ya no esta a su alcance, pero si es **var** , en todos los lugares donde exista esta variable se van a cambiar.

	* **Manuel Rivera** (1)

		
		Muy buena aclaración @dfloresdev

	* **Nathaly Stefani Riaño Bejarano** (1)

		
		Muy buenas aclaraciones!!! La explicación de @dfloresdev es muy acertada y explicaría también el caso en el que el tiempo de espera del setTimeOut fuera 0:
		``` 
		    for (var i = 0; i < 10; i++) {
		      setTimeout(() =>console.log(i), 0);
		    }
		    
		```
		
		Que deriva en el mismo resultado -> imprime 10 veces 10

* **ivofacundo** (2)

	
	por lo que entendí, las variables declaradas con **var** no toman en cuenta el scope de un bloque y se lo “saltan” por así decirlo y lo que hacen es asignar su scope a la función mas cercana o si no existe una función lo hace de manera global.

* **Kevin Jeremy Salazar Jimenez** (2)

	
	excelente clase!

* **Derek Samuel Paúl Peña** (2)

	
	estuvo muy bien explicado qué es un bloque en JavaScript y su relación con el Scope

* **33andres33** (1)

	
	supongo que este imprime 10 veces el 10 porque espera al código por el setTimeOut lo que significa que primero ejecuta la función del for, y esta al ser ejecutada pues va a ir sobrescribiendo sus variables, primero var i equivale 0 después 1 después 2 hasta llegar a 10, después de esto ejecuta el setTimeOut del console.log osea el 10 y de nuevo vuelve a hacer este paso vuelve al for sobreescribe las variables y ejecuta el 10 y asi hasta ejecutarlo las 10 veces. pueden hacer la prueba quitando el setTimeOut con el var y notaran que si imprime el ciclo de la manera correcta.

* **lmoran** (1)

	
	con let y const solo podemos acceder dentro de los bloques.

* **jaguarjs** (1)

	
	Var es una asignación del Scope local dentro de una funcion, pero let y const solo tienen un scope de bloque

* **JhonColorado07** (1)

	
	Uff en esta clase acabo de aprender lo peligroso que pueden llegar a ser las variables con **var** si no se le da un buen manejo.

# Closure

## 0060. ¿Qué es un closure

### Descripción:


### Comentarios:

* **Roberto Bock** (9)

	
	Bueno quisiera empezar con comentar que me costó entender esto, tuve que ver el video 2 veces para poderlo entender, me gustaría empezar con cambiar un poco los nombres de funciones y variables por algo menos confuso, y quizás mas divertido…
	``` 
	    const papa = (nuevoEngendro) =>{
	        var cantidadDeHijos = 0;
	        const crearEngendro = (nuevoEngendro) =>{
	            cantidadDeHijos += nuevoEngendro;
	            console.log(`cantidad de engendritos = ${cantidadDeHijos}`)
	        }
	        return crearEngendro;
	    }
	    
	    let traigamosHijosAlMundo = papa();
	    traigamosHijosAlMundo(1)  // cantidad de engendritos = 1
	    traigamosHijosAlMundo(1)  // cantidad de engendritos = 2
	    traigamosHijosAlMundo(1)  // cantidad de engendritos = 3
	    
	```
	
	Si estudiamos la función **papa** esta tiene la declaración de la variable **cantidaDeHijos** y la declaración de la función **crearEngendro** y al final retorna la función **crearEngendro** ,
	
	Ahora después de la declaración de la función papa viene la línea
	``` 
	    lettraigamosHijosAlMundo = papa();
	    
	```
	
	Notese el **PARENTESIS** () de la función papa
	``` 
	    let traigamosHijosAlMundo = papa(); // <-- este paréntesis indica que la función se está ejecutando
	    
	```
	
	este paréntesis indica que la función se está ejecutando, es decir cada línea de esa función se ejecuta una a una, y si recorremos línea a línea a la función tenemos  
	la declaración de **cantidadDeHijos** que vale 0  
	la declaración de la función **crearEngendro** y el retorno de esta función,
	
	así que finalmente **traigamosHijosAlMundo** vale lo que haya retornado la función **papa** que es **crearEngendro** (nótese que no se ejecuta la función crearEngendro sino que simplemente se retorna la referencia a ella)
	
	por ende cada vez que ejecutamos
	``` 
	    traigamosHijosAlMundo(1)
	    
	```
	
	realmente estamos es llamando a la función **crearEngendro** con todo su ámbito que es la variable cantidadDeHijos con valor de 0, y a este le suma lo que se le pase por parámetro,
	
	En la segunda ejecución de
	``` 
	    traigamosHijosAlMundo(1)
	    
	```
	
	no se está volviendo a correr todas las líneas de la función papa, esto ya se hizo en la asignación ( let traigamosHijosAlMundo = papa(); ), sino que realmente se está volviendo a llamar a **crearEngendro()** la cual había modificado su variable cantidadDeHijos en la primera llamada
	
	asi que pienso que la clave es entender que en esta asignación
	``` 
	    lettraigamosHijosAlMundo = papa();
	    
	```
	
	se ejecutó la función papá donde se declararó la variable de dicha función (cantidadDeHijos) y la función que retorna (crearEngendro) UNA SOLA VEZ! lo que se ejecuta multiples veces es el la función crearEngendro

	* **Nathaly Stefani Riaño Bejarano** (1)

		
		❤️ x1000! Que ejemplo y explicación tan acertados y detallados! 👏

* **eocas98** (6)

	
	He estado leyendo un poco y me gusta hacer este símil, planteemos una situación parecida al ejemplo del moneyBox sin usar closure y solo una función:
	``` 
	    let saveCoins = 0
	    
	    const moneyBox = (coins) => {
	    	saveCoins += coins
	            console.log(`MoneyBox: $${saveCoins}`)
	    }
	    
	    moneyBox(3)// 3
	    moneyBox(4)// 7
	    moneyBox(7)// 14
	    
	```
	
	En el código de arriba, alteramos la variable global saveCoins desde la función moneyBox() pero al hacer esto, podemos reasignar la variable saveCoins fuera de la función. Acá entra closure, donde utilizamos la función moneyBox para declarar e inicializar la variable saveCoins y retornar la función countCoins(coins) que incrementa saveCoins en coins.
	``` 
	    const moneyBox = () => {
	        let saveCoins = 0
	        const countCoins = (coins) => {
	            saveCoins += coins
	            console.log(`MoneyBox: $${saveCoins}`)
	        }
	        return countCoins
	    
	    let myMoneyBox = moneyBox()
	    myMoneyBox(4)// 4
	    myMoneyBox(6)// 6
	    myMoneyBox(10)// 10
	    }
	    
	```
	
	En esta parte, la variable saveCoins es una variable local para moneyBox() y una variable global para countCoins(coins) que es el closure. Asignamos la función moneyBox() a myMoneyBox para que saveCoins se inicialize en 0 y tenga un contexto, luego myMoneyBox se encarga de retornar la funcion countCoins y pasarle el parámetro y hacer la operación que altere a su vairbale global saveCoins.
	
	Arriba mencione que en el primer código nosotros podemos reasignar la variable saveCoins fuera de la función. Bueno pues en este segundo código es imposible tan siquiera llamar a saveCoins fue de moneyBox. Espero que ayude a comprender más este tema que es un poco complejo. Más abajo hay un aporte interesante de otro compañero.
	
	Fuentes:
	
	  1. <https://medium.com/@sergiodxa/definiendo-conceptos-closure-y-scope-en-javascript-9081f1e113e6>
	  2. <https://www.w3schools.com/js/js_function_closures.asp>
	
	

* **Jose Daniel Barría Reyes** (4)

	
	Codigo de la clase
	``` 
	    // const moneyBox = (coins) =>{
	    //     var saveCoins = 0;
	    //     saveCoins += coins;
	    //console.log(`Money box: $${saveCoins}`)
	    // } No funciona
	    
	    const moneyBox = (coins) =>{
	        var saveCoins = 0;
	        const countCoins = (coins) =>{
	            saveCoins += coins;
	            console.log(`MoneyBox: $${saveCoins}`)
	        }
	        return countCoins;
	    }
	    
	    let myMoneyBox = moneyBox();
	    myMoneyBox(5)
	    myMoneyBox(10)
	    
	```

* **Karla Agraz** (3)

	
	Closure: Es la combinación de una función y el ámbito léxico en la cual ha sido declarada dicha función. Un closure recuerda el ámbito en el cual ha sido creado.
	
	El closure recuerda la asignación del valor anterior porque queda en la memoria, al pasarle un nuevo valor nos dará como resultado la suma de estos elementos porque estamos usando la asignación de adición.
	``` 
	    const moneyBox = () => {
	      var saveCoins = 0;
	      const countCoins = coins => {
	        saveCoins += coins;
	        console.log(`MoneyBox: $${saveCoins}`);
	      };
	      return countCoins;
	    };
	    
	    let myMoneyBox = moneyBox();
	    
	    myMoneyBox(4); // 4
	    myMoneyBox(6); // 10
	    myMoneyBox(10); //20
	    
	```

* **lmoran** (2)

	
	**CLOSURE:** Es la combinación de una función y el ámbito léxico en la cual ha sido creada la función, en otras palabras, el closure recuerda el ámbito en el que ha sido creado.

* **Juan Carlos Valencia López** (2)

	
	lo que esta pasando es que al llamar la funcion MoneyBox() y guardarlo en la variable myMoneyBox lo que hace es solo guardar la función de retorno que es el countCoins, y cada vez que se llama myMonyBox lo que hace es solo sumar, lo cual está en la función de retorno. 😃

* **Camilo Ernesto Hurtado Cataño** (1)

	
	Para entenderte mejor este concepto les recomiendo la siguiente respuesta:  
	<https://platzi.com/comentario/919760/>

* **Juan Carlos Valencia López** (1)

	
	Entendí el concepto pero me gustaría saber como trabaja por dentro para que haga algo semejante a eso

* **JPinedaHN** (1)

	
	Es importante ver que también funciona con **let** , el clousure no funciona por el scope de la variable saveCoins, pues ya sea con var o con let, lo importante es que la función **countCoins **tenga el acceso a **saveCoins **cuando se crea.

* **JhonColorado07** (1)

	
	Un poco confuso pero a seguir leyendo

* **ZusMexSide** (1)
Esta vez no estoy comprendiendo bien me revuelve mucho 😅

* **Diego Alberto González González** (1)

	
	NO comprendo por que se le esta pasando un valor como parámetro a la variable myMoneyBox … ¿alguien que pueda explicarme esto ? Por favor

	* **zach** (3)

		
		moneyBox es una funcion que devuelve otra funcion.  
		en la linea
		``` 
		    letmyMoneyBox = moneyBox()
		    
		```
		
		se esta ejecutando la funcion moneyBox y esta almacenando en myMoneyBox la funcion countCoins que retorna.
		
		por lo que myMoneyBox es una funcion, la cual recibe como parametro coins y cada vez que se llama esta ejecutando el codigo declarado en la funcion countCoins

* **Jean Carlos Nuñez Hernandez** (1)

	
	El closure recuerda algun valor

* **Jean Carlos Nuñez Hernandez** (1)

	
	El cosure recuerda en el ambito que a sido creado

* **Jean Carlos Nuñez Hernandez** (1)

	
	Closure es la union de una funcion en el ambito y lexico donde ha sido declarda dicha funcion

* **Maximo Martinez Soria** (1)

	
	Esto es algo similar a declara `saveCoins` como `static`. Verdad?

	* **akiliki** (2)

		
		Yo creo que esa var saveCoins es como un atributo de un objeto.  
		Siendo la única forma que tienes para acceder a el es mediante el método countCoins que devuelves.
		
		Si saveCoins fuese como static, todas la instancias de la función moneyBox compartirían dicho valor y si no me equivoco no es así. Cada instancia tendría su valor.

	* **zach** (2)

		
		No es similiar, como te comenta akiliki, al declarar static tendrias el mismo valor para todas tus instancias, pero con closures puedes crear multiples instancias y cada una de ellas mantiene su propio contexto, lo que Oscar a explicado como ambito lexico.

	* **Maximo Martinez Soria** (1)

		
		Muchas gracias a ambos!

* **Cristobal Peña** (1)
¿Cómo es que la función myMoneyBox acepta como parámetro el valor de coins? No entiendo la mecánica…

	* **Juan Carlos Valencia López** (2)

		
		lo que esta pasando es que al llamar la funcion **MoneyBox()** y guardarlo en la variable **_myMoneyBox _**lo que hace es solo guardar la función de retorno que es el **countCoins** , y cada vez que se llama **myMonyBox()** lo que hace es solo sumar, lo cual está en la función de retorno.  
		😃 espero haberlo explicado bien

* **ZusMexSide** (1)
¿que es el ámbito léxico?

	* **Juan Felipe Peralta Zapata (Platzi)** (2)

		
		En la clase siguiente se explica la definición del ámbito léxico en Closures. De todas formas, aquí te dejo el enlace directo a la clase: <https://platzi.com/clases/1807-scope/25876-ambito-lexico-en-closures/>

## 0070. Ámbito léxico en closures

### Descripción:


### Comentarios:

* **Mariana Valencia** (5)

	
	Aprender closures es una de las cosas más valiosas en JavaScript. Saber usarlo marca unagran diferencia

* **Cristobal Peña** (4)

	
	“Mágico”
	
	Habría sido bueno que el profesor hubiera dedicado tiempo a explicar la mecánica del closure. Por qué es que la variable es capaz de mostrar un resultado diferente al que si ejecutamos la función directamente. Cuál es el papel de la memoria interna en este comportamiento, etc. Ahora está todo muy "mágico"  
	Los estudiantes han aportado valiosos comentarios en este sentido, pero son estudiantes como yo. No es lo mismo que te lo explique el profesor.  
	Es mi opinión.

	* **César Oswaldo Mandamiento Salas** (3)

		
		Hola Cristobal, cuando empecé a profundizar temas de Javascript me costaba entender algunas cosas pero con la práctica uno lo va entendiendo, además de complementarse con repasar algunos fundamentos.
		
		Nose si ya te haya quedado del todo claro pero puedo tratar de explicarte
		``` 
		    const buildCount = i => {
		      let count = i;
		      const displayCount = () => {
		        console.log(count++);
		      };
		      return displayCount;
		    };
		    
		    const myCount = buildCount(1);
		    // Al ejecutar buildCount(1), lo que se hace es
		    // declararse una variable let con el valor 1 (i = 1)
		    // esta variable solo vive dentro del scope buildCount
		    // el cual ahora está siendo grabado en myCount.
		    // Pero debes observar que la función retorna otra
		    // función displayCount, la cual ejecuta un console.log.
		    // Entonces, lo que se hace con esta línea de ejecución
		    // es crear un ámbito léxico y nuestra variable myCount
		    // quedaría igual a 
		    // myCount = () => {
		    //   console.log(count++); // imprime el valor actual de count y le suma 1 después de ejecutarlo.
		    // teniendo en cuenta que declaraste count = 1 (i=1)
		    // imprimiría 1 y en la siguiente ejecución 1+1 y así 
		    // Solo recuerda que la variable count vive en el scope creado
		    // en myCount()
		    // }
		    
		    myCount(); // 1
		    myCount(); // 2
		    myCount(); // 3
		    
		    const myOtherCount = buildCount(10);
		    // De acuerdo a lo que te expliqué, aquí se crea otro scope,
		    // el scope de myOtherCount, por ello no hay variación con el valor
		    // de la "instancia" anterior de buildCount
		    myOtherCount(); // 10
		    myOtherCount(); // 11
		    
		```

* **miguelangelsoler** (3)

	
	[Aqui un buen articulo acerca del tema](https://dmitripavlutin.com/simple-explanation-of-javascript-closures/)

	* **jagallego** (1)

		
		Muy buen articulo, muchas gracias.

* **jaguarjs** (2)

	
	**Si quieres hacer que el closure recuerde cualquier resultado, pasa el argumento también a la segunda función:  
	**  
	Ejemplo
	``` 
	    const llevaLaCuenta = (numero) => {
	      const cuenta = 0;
	      const aumentarcuenta = (numero) => {
	        cuenta+=numero
	        returnconsole.log(cuenta);
	      }
	      return aumentarcuenta
	    }
	    
	    let llevameLaCuenta = llevaLaCuenta()
	    
	    llevameLaCuenta(3)
	    llevameLaCuenta(4)
	    llevameLaCuenta(5)
	    
	    // IMPRIME   3712
	    
	    
	```

	* **v1ctorcontreras** (2)

		
		pasar como parametro numero en la funcion llevaLaCuenta no es necesario

* **Karla Agraz** (2)

	
	El ámbito léxico es cuando las funciones se ejecutan utilizando la cadena del alcance donde estaban vigente en su momento.
	
	Esto significa que podemos acceder al valor “count” dentro de la función porque es el alcance donde está asignado.
	
	Podemos tener varias formas de manejar la constante “buildCount”, significa que la podemos asignar a myCount y myOtherCount. Trabajaremos con el scope(alcance) que tiene esta variable, poder ejecutarla y empezar a contar desde donde necesitemos.
	``` 
	    const buildCount = i => {
	      let count = i;
	      const displayCount = () => {
	        console.log(count++);
	      };
	      return displayCount;
	    };
	    
	    const myCount = buildCount(1);
	    myCount(); // 1
	    myCount(); // 2
	    myCount(); // 3
	    
	    const myOtherCount = buildCount(10);
	    myOtherCount(); // 10
	    myOtherCount(); // 11
	    
	```

* **Ernesto Briceño** (2)

	
	## Código de la clase
	``` 
	    const buildCount = i => {
	      let count = i;
	      const displayCount = () => {
	        console.log(count++);
	      };
	      return displayCount;
	    };
	    
	    const myCount = buildCount(1);
	    myCount(); //1
	    myCount(); //2
	    myCount(); //3
	    
	    console.log("---------------");
	    const myOtherCount = buildCount(10);
	    myOtherCount(); //10
	    myOtherCount(); //11
	    
	    
	```

	* **Jose Daniel Barría Reyes** (1)

		
		Muchas gracias!

* **Gerardo Nava Pereda** (1)

	```
	    const buildSum = (n) => {
	    	returnsum(n + n);
	    	function sum(a, b) {
	    		return a + b
	    	}
	    }
	    
	    buildSum(2) // 4
	    
	```

* **bryanjavier** (1)

	
	Por que al ejecutar simplemente  
	buildCount(10);  
	no me aparece nada en consola si le estoy entregando el parámetro para ser ejecutada :'0 Mi no entender

	* **Nicolas Villabona** (2)

		
		Tuve tu misma duda, estuve buscando y de esta manera fue que lo entendí:
		
		Lo que pasa es que la función `buildCount()` nos está devolviendo la función interna `displayCount()` antes de ejecutarla ( si intentas hacer `console.log(displayCount()` lo podrás observar).
		
		Por esta razón es necesario que creemos el clousure `myCount`
		
		[En este link](https://developer.mozilla.org/es/docs/Web/JavaScript/Closures) hay un ejemplo similar (ejemplo 2)

	* **Manuel Rivera** (1)

		
		Por que la funcionalidad de esa función es devolver el método displayCount, por ende no te saldra nada en pantalla. Pero si esta devolviendo un valor, por eso es que se crea una nueva variable para reservar un espacio en el memory heap de ese método que nos esta devolviendo buildCount

* **JhonColorado07** (1)

	
	Un poco más claro.

* **Jean Carlos Nuñez Hernandez** (1)

	
	El ambito lexico ejecuta las funciones que ejecuta el alcance donde estaba vigente en ese momento

* **Juan Camilo Alvarez Jurado** (1)
Es una característica… interesante, y me queda claro cómo funciona… pero no le encuentro casos de uso prácticos como que la requieran usa...

## 0080. Cómo crear variables privadas con closures

### Descripción:


### Comentarios:

* **Karla Agraz** (5)

	
	Variables privadas con Closures: JS por su naturaleza no fomenta el uso de datos privados pero por medio de los Closures podemos crear valores que solo puedan ser accedidos por medio de métodos, que no van a estar disponibles fuera de esta función.

* **Rene Ismael Barrios Rojas** (3)

	
	esto tiene parecido con el patrón module, cool 😃

* **edanfesi** (3)

	```
	    const person = () => {
	      let saveName = "Name";
	      return {
	        getName: () => saveName,
	        setName: (name) => {
	          saveName = name;
	        },
	      };
	    };
	    
	    const newPerson = person();
	    console.log(newPerson.getName());
	    newPerson.setName('Edward');
	    console.log(newPerson.getName());```
	    
	```

* **jesus-cruz-dominguez** (2)

	```
	    <
	    const perro = ( nombre, raza ) => {
	        let _nombre = nombre;
	        let _raza = raza;
	    
	        return {
	            obtNombre: () => _nombre,
	            obtRaza: () => _raza,
	            asignarNombre: ( nuevoNombre) => _nombre = nuevoNombre,
	            asignarRaza: ( nuevaRaza ) => _raza = nuevaRaza
	        }
	    }
	    
	    const firulais = perro( 'Firulais', 'Sabueso');
	    const poppy = perro( 'Poppy', 'Labrador');
	    
	    console.log(firulais._nombre);//undefined
	    console.log(firulais.obtNombre());//firulais
	    console.log(firulais._raza);//undefined
	    console.log(firulais.obtRaza());//Sabueso
	    console.log(poppy.obtNombre());//Poppy
	    console.log(poppy.obtRaza());//Labrador>
	    
	```

* **Estanislao Albin Wotoszyn Grillo** (2)

	
	Cuando inicializa newPerson no usa var, let ni const porque JS permite no usar el syntax var si se inicializa directamente una variable. Es decir lo que hizo sería el equivalente a:  
	var newPerson = person();  
	Dicho esto, declaren variables con:  
	1.) const (excepto cuando la variable deba ser reasignada, const no lo permite)  
	2.) let (resto de las veces)
	
	3.) var (NUNCA)

	* **Pablo Domínguez Durán** (2)

		
		Compañero, no entendí nada de tu comentario

	* **Estanislao Albin Wotoszyn Grillo** (2)

		
		Jajaja no pasa nada. Si prestas atención en el minuto 3:00 inicializa a new person pero nunca declara la variable. Es decir no usa var newPerson, ni let newPerson, ni const newPerson. de allí la primera explicación que lo que hizo, es igual a declarar con var.  
		Luego de esa explicación dejé las buenas prácticas en JS para declarar variables en orden de mejor a peor con la explicación del porqué en paréntesis. Espero haber sido de ayuda y un poco más claro

* **René Sanchez** (2)

	
	hmm si tenemos estados globales y solo mediante funciones cambias estos se determinaria como un closure ?
	
	* * *
	
	Es bastante similar al concepto de la POO para solo con getters y setters manipular los datos lo cual hace mas seguro cada cambio sin ponerse crudamente al crearse.
	
	__
	
	De igual manera es similar el uso al respecto de funciones dentro del return para cambiar los datos y leerlo, esto no es la misma manera de hacerlo directamente dentro del scope para la persona ?
	
	Tambien esta a una forma para gregar las funciones y se vean mejores ademas que se parecen al exportar modulos de nodejs 💚:
	``` 
	    const person = () => {
	        // Convertir a una variable "privada"
	        // hacer que solo mediante la funcion se pueda cambiar el estado y no desde afuera sin funciones osea practicamente directamente cambiarle su valor
	        let guardarNombre = "Name";
	        // asegurar los cambios de la variable privada la cual soo se puede modificar por metodos y jamas por valor directo
	        const estadoNombre = () => {
	            return guardarNombre;
	        };
	        // Creacion de un pseudo-objeto para manipular estados
	        return {
	            getName: () => {
	                return guardarNombre;
	            },
	            setName: (nombre) => {
	                guardarNombre = nombre;
	            },
	            estadoNombre
	        };
	    };
	    
	    nuevaPersona = person();
	    console.log(nuevaPersona.getName());
	    nuevaPersona.setName('Rene');
	    console.log(nuevaPersona.getName());
	    console.log(nuevaPersona.estadoNombre());
	    
	```

	* **joaquin-fontela** (1)

		
		estadoNombre y getName no harian lo mismo?

	* **René Sanchez** (1)

		
		Exactamente la unica diferencia radica en como se agrega a la parte del pseudo-objeto, dentro de el tu creas las funciones para el closure o puedes crear la funcion antes como el estadoNombre por el cual solo tienes que dejar el nombre dentro del pseudo-objeto para ser utilizada.

* **Mildred Guerra Rodríguez** (2)

	```
	    const person = () => {
	      var saveName = 'Name';
	      return {
	        getname: () => {
	          return saveName;
	        },
	        setName: name => {
	          saveName = name;
	        },
	      }
	    }
	    
	    newPerson = person()
	    
	    newPerson.setName('Oscar')
	    console.log(newPerson.getname());
	    
	```

* **Paola Zarate** (1)

	
	Una pequena prueba intentando a acceder a las variable encapsulada saveName, por fuera de person.
	``` 
	    const person = () => {
	        var saveName = "Name";
	    
	        const getName = () => {
	            return saveName;
	        }
	    
	        const setName = (name) => {
	            saveName = name;
	        }
	    
	        return {
	            getName,
	            setName
	        }
	    }
	    
	    let newPerson = person();
	    console.log(newPerson.getName());
	    newPerson.setName('paola');
	    console.log(newPerson.getName());
	    
	    // intentando ingresar a saveName 
	    console.log('aaa ', newPerson.saveName);
	    console.log('bbbb ', person().saveName);
	    
	```
	
	//output  
	Name  
	paola  
	aaa undefined  
	bbbb undefined

* **Paola Zarate** (1)

	
	Este ejemplo esta basado en el patro modulo.
	
	El patrón Módulo encapsula “privacidad”, estado y organización mediante closures.  
	El patrón de módulo se usa para emular el concepto de clases de tal manera que podamos incluir tanto métodos públicos / privados como variables dentro de un solo objeto, asi todo lo que esta afuera puede acceder a los closures privados.
	``` 
	    <functiontesModule () {
	        var counter = 0;
	    
	        return {
	            incrementCounter: function () {
	                console.log('increment counter');
	                return counter++
	            },
	    
	            resetCounter: function () {
	                console.log("value previus to reset: " + counter)
	                reset = 0;
	            }
	        }
	    }
	    
	    let module1 = tesModule();
	    module1.incrementCounter();
	    module1.incrementCounter();
	    module1.incrementCounter();
	    module1.resetCounter();>
	    
	```
	
	//output  
	increment counter  
	increment counter  
	increment counter  
	value previus to reset: 3

* **Anibal Fernando Ortega Piedrahita** (1)

	
	Me genera una duda. Si es para crear variables privadas con el closure, porque cuando creo accedo directamente a la variable sin el get o el set funciona.
	``` 
	    newPerson = person();
	    newPerson.saveName = 'Anibal';
	    console.log(newPerson.saveName);
	    
	```
	
	Gracias por sacarme de la duda

	* **Estanislao Albin Wotoszyn Grillo** (2)

		
		Si no me equivoco ese saveName que acabas de inicializar NO ES el mismo que esta dentro de person. Es como si inicializaras una nueva variable saveName dentro de la instancia newPerson, no es lo mismo. La única forma de acceder al saveName de person es a través de las funciones definidas. Podes corroborar esto haciendo luego del código que pusiste:  
		console.log(newPerson.getName())  
		Esto te va a retornar el saveName dentro de person y no el que acabas de asignar

* **Jean Carlos Nuñez Hernandez** (1)

	
	Por medio de los closure podemos tener valores privados, ya que JS no los fomentas este tipo de valores

* **Kingsman7** (1)

	
	wow sorprendente. Claro si no quieres usar TypeScript.  
	mas sin envargo WOOOOOOOOOOOW

## 0090. Loops

### Descripción:


### Comentarios:

* **Karla Agraz** (3)

	
	Podemos crear Closures de diferentes formas y también de forma involuntaria, esto significa que no tenemos control de lo que estamos creando, tenemos que tener cuidado con nuestras asignaciones o bloques de código que de alguna manera nosotros no controlemos muchas veces sucede porque no establecimos nuestros elementos correctamente.
	
	Con el uso del Scope y los Closures podemos optimizar nuestros proyectos sin ningún problema.

* **Gerardo Nava Pereda** (3)

	
	Scope ( Alcance ) + Closure = Optimizar Proyectos

* **v1ctorcontreras** (2)

	
	Hola, entiendo por que i toma el valor 10 pero no entiendo por q se imprime 10 veces con ese valor, es decir js ejecuta el for i veces pero por q ejecuta el setTimeout tambien 10 veces… donde se guarda ese conteo si ya i llego a 10???

	* **Agustin_Moran** (4)

		
		Yo tengo igual algo de duda en esa parte
		
		Me parece que esto pasa porque la función setTimeout es una función asincrona (retorna un callback). Entonces cada que ocurre una iteración en el ciclo, se ejecuta el setTimeout y se manda a la cola de tareas, sin embargo, para cuando el setTimeout retorna una respuesta, el valor de i ya es 10, por lo que retorna las 10 veces el valor de 10.  
		Esto es lo que concluyo después de tomar el curso de asincronismo, pero la verdad no estoy 100% seguro ):

	* **Luis Arturo Lira Cerda** (5)

		
		Justamente es lo que dice Agustin, el for termina mucho antes que el primer setTimeOut y por eso vale 10.  
		Explico, al declarar la variable i con “var”, queda en el scope de la función, por lo que el al ejecutarse el primer console.log, i vale 10, debido a que “var” existe en toda la función, no solo en el for.
		
		En cambio, al declararlar con let, la variable i sólo existe en el scope del bloque del for, entonces, al iterarse, sí o sí, toma el valor actual de i.
		
		Poniéndolo en código. Declararla con var es lo mismo que hacer esto:
		``` 
		    const anotherFunction = () => {
		      let i = 0
		      for(i; i < 10; i++) {
		        setTimeout(() => {
		          console.log(i)
		        }, 1000)
		      }
		    }
		    anotherFunction()
		    
		```

	* **v1ctorcontreras** (2)

		
		Excelente explicacion, muchas gracias! antes, investigue con chrome DevTools y es justo lo que comentan

	* **Lluis Pitarch Ripolles** (1)

		
		La otra duda que se plantea al ser setTimeout una función asíncrona es que el console.log se ejecuta a la vez, es decir no pasa un segundo y se imprime un valor, otro segundo y el siguiente valor… Una vez se hacen las asignaciones de var i o let i se imprimen en la consola todas tras un segundo.
		
		En el caso de querer imprimir el valor tras un segundo entiendo que deberíamos usar una función async y usar await con el setTimeout

	* **33andres33** (1)

		
		Te doy la respuesta que di en la clase 5 de SCOPE. es lo que yo pense.
		
		supongo que este imprime 10 veces el 10 porque espera al código por el setTimeOut lo que significa que primero ejecuta la función del for, y esta al ser ejecutada pues va a ir sobrescribiendo sus variables, primero var i equivale 0 después 1 después 2 hasta llegar a 10, después de esto ejecuta el setTimeOut del console.log osea el 10 y de nuevo vuelve a hacer este paso vuelve al for sobreescribe las variables y ejecuta el 10 y asi hasta ejecutarlo las 10 veces. pueden hacer la prueba quitando el setTimeOut con el var y notaran que si imprime el ciclo de la manera correcta.

* **miguelangelsoler** (2)

	
	El keyword **var** ya no debería usarse para definir variables, se hace más complejo tener una referencia y scope claro de la misma

* **Jean Carlos Nuñez Hernandez** (2)

	
	Let nos da un scope en code block y asi podemos manejarlo en este bloque de codigo

* **Abraham Flores Cosme** (1)

	
	Demasiado interesante, este es un buen ejemplo para aprender definitivamente la diferencia entre los alcances que tiene var y let

* **zambombas** (1)

	
	¿Por que copiáis frases que dice el profesor y las pegáis aquí? Para que os den dos puntos?

	* **Gabriel De Andrade (Platzi)** (3)

		
		Para tener una especie de notas o resúmen del curso que quizás le puede servir a alguien más. [Curso de Estrategias para Aprender en Línea Efectivamente](https://platzi.com/clases/aprender/) 😄

	* **hansfpc** (4)

		
		Buscan puntos xd

	* **33andres33** (1)

		
		no se solo me interesa aprender

# Hoisting

## 0100. ¿Qué es el hoisting

### Descripción:


### Comentarios:

* **Samuel Mata** (11)

	
	Saludos amigos, como complemento a esta clase les comparto un articulo que escribi sobre este tema cuando me encontre con este comportamiento del motor de Javascript por primera vez.
	
	[Click aqui](https://blogs.saiyans.com.ve/developing-desarrollo/javascript-hoisting/), cualquier recomendacion es bien recibida 😃

	* **AryRosvall** (2)

		
		Excelente artículo, muy bien explicado y es muy inspiradora tu historia. Sigue así!

* **David Behar** (7)

	
	## Les dejo un video fantástico sobre hoisting de Sacha Lifs que está fantástico por si les quedaron dudas.
	
	.  
	[![hoisting.png](https://static.platzi.com/media/user_upload/hoisting-0fdae1cf-5aff-4dd0-b916-2e112fcb6c02.jpg)](https://www.youtube.com/watch?v=uI6o97A4IrI&t=1s)
	
	[https://www.youtube.com/watch?v=uI6o97A4IrI&t=1s](https://www.youtube.com/watch?v=uI6o97A4IrI&t=1s)

* **Estanislao Albin Wotoszyn Grillo** (5)

	
	El ‘levantamiento’ del que hablan es mas a fines didácticos y está bien, pero no es tan así, no es que FISICAMENTE levanta las declaraciones y las pone al principio como muchos explican. Lo que se hace en realidad es tomar ‘registros’ en memoria de donde está cada declaración(todo esto previo a que se ejecute el código en sí) y depende si es var, let, const o una función, JS va a asignarle referencias a cada una.  
	Si es:
	
	  * var : asigna la referencia undefined (si de acá viene el famoso undefined)
	
	  * let/const: asigna la referencia uninitialized(declarado pero no inicializado)
	
	  * función: guarda un registro con la función entera(por eso la podemos llamar antes de que este creada)
	
	
	

* **metta** (3)

	
	Recordar que las arrow functions no tienen la caracteristica de hoisting, entonces debemos tener cuidado en el orden de declaracion al menos en este ejemplo.

* **David Vargas Domínguez** (2)

	
	El intérprete de Javascript funciona en dos fases. En la primera, el intérprete lee declaraciones de variables y funciones. Y en la segunda sucede la ejecución del código el cual procesa function expressions y asignaciones a variables.
	
	Y por qué sucede esto del var hoisting?
	
	Según Brendan Eich, el creador de Javascript, var hoisting fue un efecto colateral del uso del hoisting de funciones. Seguramente debido a la rápida implementación y diseño de Javascript.
	
	<https://twitter.com/aravind030792/status/522379485895983104>

* **Karla Agraz** (2)

	
	Hoisting: Eleva las declaraciones, esto pasa en el momento en que se compila nuestro código antes de ser interpretado por el navegador.
	
	De esta forma podemos asignar nuestros valores o acceder a un valor que previamente no ha sido declarado dentro de esta estructura.

* **René Sanchez** (2)

	
	Aporte 💚
	``` 
	    // Hoisting
	    // Levantamiento de variables (ayuda que da javascript por defecto)
	    // cada identidificador sinuna declaracion si es una variable(var),let,const se terminara por convertir enuna var a; a = 2
	    a = 2;
	    console.log('valor a por hoisting: ', a);
	    var a;
	    // Hoisting funciona solo en las declaraciones de variables
	    console.log('valor a por var: ', a);
	    
	    console.log(a);
	    var a;
	    
	    // Hoisting para var y functions
	    // Solo nos jode en variables var
	    // para las funciones el levantamiento nos ayuda a que si esta funcion aunnoseha definido, este lo tomara como si definitivamente fuera a crearse pero mas tarde por lo cual lo deja y cuando termine este dice se encontro la funcion por ende si existe en este punto por lo cual se referencia a ella
	    
	    nameOfDog('Mascota Desde Hoisting')
	    
	    functionnameOfDog(name){
	        console.log(name);
	    }
	    
	    nameOfDog('Sandy sin hoisting')
	    
	```

	* **JhonColorado07** (1)

		
		Gracias.

* **Kingsman7** (2)

	
	Esta clase se llama. no tientes a la suerte

* **David Perez** (2)
Por qué "a" se declara sin var ni let ni const? Que significa esto

	* **romerodiesan** (5)

		
		Cuando asignas valor a una variable aun no declarada (con let, var, const) javascript la asigna inmediatamente de manera global al principio del programa. Y eso pasa en el proceso de compilación antes de que el navegador lo interprete.
		
		Si no entendiste mucho, te invito a que tomes el Curso de Engine V8 de Javascript.

* **Ricardo Exequiel De Angelis** (1)

	
	js es un lenguaje interpretado, como es que tambien compila no entiendo?minuto 2:10

	* **Gabriel De Andrade (Platzi)** (4)

		
		El motor V8 de Chrome y en general los motores de JS, hacen un proceso de optimización del código, cuando una pieza de código es muy usada los motores compilan este código a bytecode para que sea mucho más rápido ejecutar estas operaciones. [Curso de JavaScript Engine (V8) y el Navegador](https://platzi.com/clases/javascript-navegador/) 😄

	* **Cristobal Vega** (1)

		
		Esta técnica de compilación se le conoce como JIT (Just In Time).

* **Jose Daniel Barría Reyes** (1)

	
	Codigo de la clase
	``` 
	    //Hoisting : elevamiento de las declaraciones
	    //Solo en declaraciones, no en inicializaciones
	    
	    a = 2;
	    var a;
	    console.log(a) //Resultado: 2
	    
	    console.log(b);
	    var b = 2; // Resultado: undefined
	    
	    
	    nameOfDog('Doge') //Resultado: Doge
	    
	    functionnameOfDog(name){
	        console.log(name)
	    }
	    
	```

* **Jean Carlos Nuñez Hernandez** (1)

	
	Hoisting levantamiento de las declaraciones

* **ivofacundo** (1)

	
	entendido a la perfección!

# Debugging

## 0110. Debugging

### Descripción:


### Comentarios:

* **Pau Pregoni Juan** (3)

	
	Herramientas modernas para debuggear…
	
	**Yo:**
	``` 
	    console.log(menu)
	    console.log(menu.firstChild)
	    console.log(e)
	    console.log(e.toElement)
	    
	```

* **Jesús Adrián Arroyo Ceja** (2)

	
	Adicional a las Chrome devtools, VS Code tiene una erramienta para debugging que sirve para distintos lenguajes, al inicializar el proyecto de node con el comando npm init y crear un archivo package.json podemos utilizarlo con el botón de “play” y el bichito en la barra de actividades del editor de código (el de la izquierda". Para esta clase y algunas ocasiones me parece más sencillo y te ahorras el copiar y pegar.  
	Aquí mas info: <https://code.visualstudio.com/docs/editor/debugging>

* **Ricardo Martínez Murillo** (1)

	
	por que la variable declarada con “var” no aparece en el ambito global dentro del debugger?

	* **Camilo Alexander Velandia Velandia** (1)

		
		si aparece, revisa de nuevo

* **Jean Carlos Nuñez Hernandez** (1)

	
	La palabra debbuger se coloca donde sea necesario para interrumpir la ejecucion y ver los valores de flujo en el codigo

* **Jean Carlos Nuñez Hernandez** (1)

	
	Crhome devtools nos permite ver los scope de la variable, Waaoo!

* **Jean Carlos Nuñez Hernandez** (1)

	
	Chrome dev tool para hacer debugging

# Cierre

## 0120. Conclusiones

### Descripción:


### Links:

* [Curso Profesional de JavaScript](https://platzi.com/cursos/javascript-profesional/)

* [Curso de Asincronismo con JavaScript](https://platzi.com/cursos/asincronismo-js/)

* [Escuela de Javascript - Ruta de aprendizaje](https://platzi.com/escuela-javascript/)

* [Log in | Platzi](https://platzi.com/mi-suscripcion/referidos/)

### Comentarios:

* **Jean Carlos Nuñez Hernandez** (3)

	
	yuhuuuuuuuuuuuuuu! ahor hacer el exament

	* **Oscar Barajas Tavares (Platzi)** (1)

		
		A darle con todo!

* **René Sanchez** (2)

	
	Fue fantastico comprender estos conceptos y reforzarlos con el que tome antes sobre el motor de v8 con javascript, sin duda este fue el complemento completo para comprender y aplicandolo en mi desarrollo continuo conjunto enseñandole a mi equipo, muchas gracias 💚.

	* **Oscar Barajas Tavares (Platzi)** (2)

		
		Me da gusto saber que ha sido de tu agrado y reforzó tu aprendizaje.

* **lmoran** (1)

	
	Buen curso, Excelente profesor.

* **Bernardino Villagra Baez** (1)

	
	Me gusto muchisimo este curso. Tengo que decir que los cursos que he tomado con este profesor han sido geniales.

* **Pablo Domínguez Durán** (1)

	
	Me gustó mucho el curso 😃 Enhorabuena por JS!

* **Anibal Fernando Ortega Piedrahita** (1)

	
	Excelente curso. Me gusto demasiado por lo preciso que estuvo.

* **Fernando Cordero** (1)

	
	Excelente curso Oscar! igual que el de asincronismo

* **Diego Mierez** (1)

	
	Excelente curso. Es un placer tener profesores así 😃

* **José Robles Colonia** (1)

	
	Muchas gracias por el curso profe, excelente explicación.

* **eocas98** (1)

	
	Excelente curso, muchas gracias Oscar por tus explicaciones.

* **MartinMB** (1)

	
	Muy interesante

* **Karla Agraz** (1)

	
	Muchas gracias profe Oscar, excelente el curso para conocer más JavaScript. Me siento muy feliz de tener profes maravillosos 😊

* **Manuel Rivera** (1)

	
	Muchas gracias

* **fryma** (1)

	
	Es un excelente curso, para saber como funciona javascript.

* **Camilo Alexander Velandia Velandia** (1)

	
	estuvo muy bueno el curso, se complementa muy bien con el de javascript engine y asincronismo

* **JhonColorado07** (1)

	
	Excelente clase. Veo la importacia de tener todos estos conceptos claro porque en ocasiones solemos caer en errores y no se sabe el por qué. Gracias.

