[Curso de Unit Testing para MEAN con Jasmine 1542](https://platzi.com/cursos/pruebas-unitarias)

# Bienvenida e Introducción [3765]

## 0010. ¿Qué son las pruebas unitarias [18791](https://platzi.com/clases/1542-pruebas-unitarias/18791-que-son-las-pruebas-unitarias/)

### Descripción:


¡Bienvenida o bienvenido al Curso de Unit Testing con Jasmine!

En esta ocasión nos acompaña Cristian Marquez: nómada digital, _blogger_ , _speaker_ , organizador de comunidades de programación y desarrollador JavaScript.

Las pruebas unitarias o Unit testing forman parte de los diferentes procedimientos que se pueden llevar a cabo dentro de la metodología ágil; código que sirve para probar otro código. Pequeñas pruebas creados específicamente para cubrir todos los requisitos del código y verificar sus resultados.

_¿Para qué sirven las pruebas unitarias?_

* **Red de seguridad** : Prevenir cambios inesperados en nuestras aplicaciones por miembros de nuestro equipo o, incluso, nosotros mismos.
* **Calidad del código** : Mejora continua de nuestro código. Podemos revisar y mejorar código viejo o contemplar casos de uso que no tuvimos en cuenta al comenzar el desarrollo.
* **Reducir costos** : Prevención y detección de errores a edad temprana, antes de que puedan salirse de control.



### Links:

* [Hacker Noon](https://hackernoon.com/)

### Comentarios:

* **Roberto Bock** (3) [556343](https://platzi.com/comentario/556343/) 
Excelenteee estaba esperando por un curso de estos!

* **Jaime Quintero Rodríguez** (2) [549676](https://platzi.com/comentario/549676/) 

	¿ De donde se descarga el proyecto final ?

	* **Ludwring Liccien** [549676] (1)

		[reposirorio de gitbhub del proyecto en angular](https://github.com/xthecapx/mean)

* **josealiriorojasclavijo** (1) [1069540](https://platzi.com/comentario/1069540/) 

	Conocomiento nuevo ven a mi, enserio deseo conocer sobre pruebas unitarias

* **Jhon Alexander Alvarez Romero** (1) [808380](https://platzi.com/comentario/808380/) 

	Realmente es algo necesario para el desarrollo de cualquier proyecto, espero entender mas y mejor de esta gran tecnica, vamos por ello

* **Elberth Jair Agreda Rosero** (1) [783614](https://platzi.com/comentario/783614/) 

	Con muchas expectativas!!

* **william andres rodriguez borja** (1) [652107](https://platzi.com/comentario/652107/) 

	Expectativa total esta genial el curso muy util

* **Adrian Camilo Caminos** (1) [549088](https://platzi.com/comentario/549088/) 

	Excelente porque la verdad nunca he echo prueba unitarias en Angular

	* **ricardocelis (Platzi)** [549088] (2)

		bienvenido entonces Adrian!

* **Jhon Alexander Alvarez Romero** (1) [72015](https://platzi.com/comentario/808385/) 
Realmente que tan necesario es tener ya aprobado el curso de node.js? adicional a eso los de CSS realmente afectan? tengo algunos pero no...

* **spajdz** (0) [60612](https://platzi.com/comentario/608203/) 
Hola! Tengo una consulta, como se puede hacer un spy a un request? el dejo un ejemplo como estpy trabajando el request: router.all(...

## 0020. ¿Por qué hacer pruebas unitarias [19195](https://platzi.com/clases/1542-pruebas-unitarias/19195-por-que-hacer-pruebas-unitarias/)

### Descripción:


La productividad, el valor generado, el presupuesto, el tiempo, son consideradas las variables más importantes en cualquier tipo de proyecto. Si le preguntas al dueño de la empresa el presupuesto va a ser lo principal. Si hablas con el dueño del producto, la productividad y el valor agregado serán su enfoque. Si hablas con el cliente probablemente el tiempo es lo más importante. Es por ello que vale la pena preguntarnos, ¿deberíamos reservar un espacio para la creación de pruebas unitarias?

Crear pruebas unitarias implica la creación de una aplicación en paralelo que permita ejecutar y probar nuestro código base. Es decir, dependiendo de las habilidades del programador, el tiempo dedicado a su creación puede llegar a ser igual o en algunos casos mayor al tiempo empleado para escribir la solución.

Veamos esto con un ejemplo. Imagina que una empresa tiene la tarea de crear un formulario para registrar asistentes a una conferencia. Como el presupuesto es ajustado, el grupo de desarrollo decide crear la solución sin un sistema de pruebas. La primera fase del proyecto fue un “éxito”. El equipo de pruebas encuentra un problema con las validaciones del formulario y un error en consola debido a un tipo de dato. El equipo de desarrollo resuelve el problema y finalmente se puede entregar el producto.

De la situación anterior podemos analizar lo siguiente:

  1. Si bien la primera entrega del producto fue exitosa, la falta de un sistema de alertas durante el tiempo de desarrollo, hizo que errores relacionados con tipos de datos solo fueran detectados durante las pruebas de calidad.

  2. La aplicación requirió de un nuevo ciclo de desarrollo para arreglar el problema.

  3. Debido al tamaño de la aplicación realizar realizar cambios serán bastante rápidos.




Ahora bien, supongamos que ese mismo sistema se utiliza para otro cliente pero esta vez se le debe agregar un sistema de autenticación. Una persona del equipo decide abandonar la empresa. El proceso desarrollo fue un éxito. El tiempo estimado se incrementó. Nuevamente no se creó un sistema de pruebas. Se requirieron dos rondas de pruebas adicionales y de desarrollo para poder realizar la entrega del producto.

Analicemos la situación anterior:

  1. El proyecto se atraso debido a la salida y al proceso de aprendizaje del nuevo desarrollador.

  2. Nuevamente no se realizó un sistema de pruebas en la aplicación.

  3. Se realizaron dos rondas de pruebas y de desarrollo adicionales a lo planeado.




¿Qué puedes concluir de estas situaciones?, ¿Cómo podrías mejorar el proceso de desarrollo de esta aplicación? Como ya te imaginarás, una de las cosas que se pudo mejorar sería la implementación de un sistema de pruebas. Sin embargo, ¿Cómo las pruebas unitarias te pueden ayudar en tus desarrollos?

## Las pruebas unitarias

Comencemos con la definición. Las pruebas unitarias no son más que un programa que permite probar nuestro código base. Es decir, las pruebas unitarias implica la creación de pequeños extractos de código que ejecutarán todas las líneas dentro de una función, de tal forma que se pueda verificar su comportamiento.

El tiempo dedicado para la creación de las pruebas unitarias debe ser incluido durante la fase de desarrollo, de tal forma que se pueda crear la solución y las pruebas relacionadas con el problema en un mismo momento.

## ¿Para qué sirven las pruebas unitarias?

Las pruebas unitarias sirven para:

  1. Red de seguridad: Cada vez que creas una prueba unitaria, estas analizado el código en partes pequeñas, por lo tanto, es posible crear un sistema de alertas ante futuros cambios en el código.

  2. Documentación: Debido a que tenemos una aplicación que va a ejecutar las líneas de código de nuestro programa, es el momento perfecto para documentar y verificar lo que esperamos que pase. Es decir, vamos a explicar nuestro código, mostrando cómo se deben utilizar.

  3. Calidad de código: Durante el proceso de creación de pruebas unitarias además de detectar errores, es el momento ideal para mejorar la solución o aplicar mejores patrones de diseño a nuestro código.

  4. Reducción de costos: Todos los puntos anteriores van a ayudar con la reducción de costos. Contar con una documentación adecuada nos va ayudar con futuras modificaciones al código o la incorporación de nuevos desarrolladores al proyecto. La red de seguridad y la calidad en el código va a permitir la detección de errores temprana, por lo tanto, va a prevenir que te atrases en las entregas.




## Conclusiones

Incorporar pruebas unitarias en un proyecto es una de las mejores decisiones que puedes tomar. Debes tener en cuenta que las pruebas no solo te van a ayudar a reducir costos, estas son creadas con el propósito de ayudarnos entre desarrolladores durante el proceso de creación de código.

Contar un set de pruebas puede tomar tiempo al principio, pero con práctica va a ser intuitivo y rápido. Los conceptos aprendidos durante este curso te van a ser de utilidad no solo para las pruebas creadas utilizando Jasmine, si no vas a tener las bases para la creación de tu propio sistema de pruebas o como bases para comenzar a utilizar otros frameworks.

### Comentarios:

* **Itzel Jimenez** (2) [701844](https://platzi.com/comentario/701844/) 

	Hola, sólo tengo comentarios sobre un par de typos, nada que afecte la comprensión pero quisiera compartirles:  
	reserver: ¿deberíamos reserver un espacio para la creación de pruebas unitarias?.  
	realizar dos veces: Debido al tamaño de la aplicación realizar realizar cambios serán bastante rápidos.  
	Por todo lo demás excelente, bien explicado, gracias.

* **Jhon Alexander Alvarez Romero** (1) [808382](https://platzi.com/comentario/808382/) 

	A mi forma de ver, creo que por mas poco que sea el presupuesto siempre deberiamos aplicarlas, ya que en un caso digamos donde seamos independientes y tengamos corto tiempo de realizar el codigo, lo ideal seria realizar las pruebas para podernos asegurar de tener que gastar mas tiempo en el desarrollo y poder cumplir mejor los tiempos de entrega

* **Wilson Marino Pablo Mendez** (1) [729473](https://platzi.com/comentario/729473/) 

	Interesante!! Vamonos con el curso 💻

# Creando un framework de pruebas básico [3766]

## 0030. Mi primera prueba unitaria en JavaScript [18792](https://platzi.com/clases/1542-pruebas-unitarias/18792-mi-primera-prueba-unitaria-en-javascript/)

### Descripción:


Características de las pruebas unitarias:

* Aunque los resultados deben ser específicos de cada test unitario desarrollado, los resultados se pueden automatizar, de forma que podemos hacer las pruebas de forma individual o en grupos.

* El proceso consta de pequeños test sobre parte del código, pero al final, se debe comprobar su totalidad.

* En el caso de repetir las pruebas de forma individual o grupal, el resultado debe ser siempre el mismo, dando igual el orden en que se realicen los test, los tests se almacenan para poder realizar estas repeticiones o poder usarlos en otras ocasiones.

* Es un código aislado que se ha creado con la misión de comprobar otro código muy concreto, no interfiere en el trabajo de otros desarrolladores.

* A pesar de lo que muchos desarrolladores opinen, el código de los tests unitarios no debe llevar más de 5 minutos en ser creado, están diseñados para hacer que el trabajo sea más rápido.




### Comentarios:

* **adevesa** (3) [576252](https://platzi.com/comentario/576252/) 

	Se menciona a Emmet. Para más información se puede ingresar a la siguiente página. https://docs.emmet.io

* **Jhon Alexander Alvarez Romero** (1) [808388](https://platzi.com/comentario/808388/) 

	Muy buena practica, es muy basica esta informacion tanto que deberia hacer un poco mas parte de la introduccion, gracias

* **Roberto Bock** (1) [582942](https://platzi.com/comentario/582942/) 

	Gracias Platzi por este curso! lo estaba deseando desde hace tiempo! no se imaginan lo mucho que he notado la importancia saber y entender este tema de las pruebas unitarias!

## 0040. Las funciones expect() y it() [18793](https://platzi.com/clases/1542-pruebas-unitarias/18793-las-funciones-expect-y-it/)

### Descripción:


Los errores en tiempo de ejecución también tienen como resultado un nuevo objeto `Error` que es creado y lanzado.

Normalmente los objetos de Error se crean con la intención de lanzarlos utilizando _throw_. Es posible manejar el error mediante _try catch_ :
``` 
    try {
        throw new Error("Algo salió mal!");
    } catch (e) {
        alert("Bien hecho");
    }
    
```

La función `it()` define una prueba de _jasmine_. Se llama así porque su nombre hace que las pruebas de lectura sean casi como leer en inglés.

El segundo argumento de la función `it()` es en sí mismo una función, que cuando se ejecute probablemente ejecutará un número de funciones `_expect()`.

Las funciones expect () se utilizan para probar realmente las cosas que “espera” que sean ciertas.

### Links:

* [
  Entiende los closures de JavaScript en Fundamentos de JavaScript
](https://platzi.com/clases/1339-fundamentos-javascript/12979-entiende-los-closures-de-javascript4100/)

### Comentarios:

## 0050. Organizando el código para correr en la web [18794](https://platzi.com/clases/1542-pruebas-unitarias/18794-organizando-el-codigo-para-correr-en-la-web/)

### Descripción:


El término refactorización se usa a menudo para describir la modificación del código fuente sin cambiar su comportamiento, lo que se conoce informalmente por _limpiar el código_.

La refactorización es la parte del mantenimiento del código que no arregla errores ni añade funcionalidad. El objetivo, por el contrario, es mejorar la facilidad de comprensión del código o cambiar su estructura y diseño y eliminar código muerto, para facilitar el mantenimiento en el futuro.

Añadir nuevo comportamiento a un programa puede ser difícil con la estructura dada del programa, así que un desarrollador puede refactorizarlo primero para facilitar esta tarea y luego añadir el nuevo comportamiento.

### Comentarios:

* **hnino** (6) [581353](https://platzi.com/comentario/581353/) 

	✔

* **Ernesto Briceño** (1) [992071](https://platzi.com/comentario/992071/) 

	El selector de emojis de Windows 10 funciona al pulsar a la vez la tecla Windows y el punto (Win + .)

* **BrayanValdesG** (1) [920284](https://platzi.com/comentario/920284/) 

	<https://emojipedia.org/>

* **Wilson Marino Pablo Mendez** (1) [764813](https://platzi.com/comentario/764813/) 

	Emojis en windows  
	_tecla window + signo ._

* **mauxiandrade** (1) [594401](https://platzi.com/comentario/594401/) 

	¿cómo se agrega el check y la x?

	* **Cristian Daniel Marquez Barrio** [594401] (1)

		No me queda claro a que te refieres. podrías ser más específica.

	* **mauxiandrade** [594401] (0)

		en la consola para mostrar si la prueba funciona o falla se coloca un ✔(la copie del comentario anterior) y una x, pero no sabía como colocarla.

	* **Cristian Daniel Marquez Barrio** [594401] (3)

		Te recomiendo esta página, ahi puedes copiar y pegar emojis <https://apps.timwhitlock.info/emoji/tables/unicode>

	* **Ale17273has** [594401] (1)

		Te dejo el snipet de código
		``` 
		    <functionit(title, callback) {
		      try {
		        callback();
		        console.log(`✅ ${title}`);
		      } catch (error) {
		        console.log(`❎ ${title}`);
		      }
		    }>
		    
		```

	* **maoacrlearn** [594401] (1)

		Creo que se les facilita agregar este tipo de caracteres al codigo por usar Mac ✔️✖️🤷‍♂️

	* **Carlos Flores** [594401] (1)

		En mac usa la combinación ctrl + cmd + barra espaciadora.

* **mauxiandrade** (1) [59671](https://platzi.com/comentario/594401/) 
¿cómo se agrega el check y la x?

	* **Cristian Daniel Marquez Barrio** [59671] (1)

		No me queda claro a que te refieres. podrías ser más específica.

## 0060. Organizando el código para correr utilizando nodejs [18795](https://platzi.com/clases/1542-pruebas-unitarias/18795-organizando-el-codigo-para-correr-utilizando-nodej/)

### Descripción:


Node.js es un entorno en tiempo de ejecución multiplataforma, de código abierto, para la capa del servidor (pero no limitándose a ello) basado en el lenguaje de programación ECMAScript

Fue creado con el enfoque de ser útil en la creación de programas de red altamente escalables, como por ejemplo, servidores web.

Ejemplo de un _hola mundo_ de un servidor _HTTP_ escrito en _Node.js_ :
``` 
    const http = require('http');
    
    const hostname = '127.0.0.1';
    const port = 1337;
    
    http.createServer((req, res) => {
      res.writeHead(200, { 'Content-Type': 'text/plain' });
      res.end('Hello World\n');
    }).listen(port, hostname, () => {
      console.log(`Server running at http://${hostname}:${port}/`);
    });
    
```

### Links:

* [Node.js](https://nodejs.org/es/)

### Comentarios:

* **Luis José Leopardi Velásquez** (5) [635957](https://platzi.com/comentario/635957/) 

	Podrías usar destructuring para obtener ‘it’ y ‘expect’ =D

* **Edison Perdomo** (2) [841777](https://platzi.com/comentario/841777/) 

	tienes razón  
	const { it } = require(’./framework’);  
	const { expect } = require(’./framework’);

* **BrayanValdesG** (1) [920347](https://platzi.com/comentario/920347/) 

	Si ya estás exportando del archivo framework.js puedes importar directamente const { it, espect } = require(’./framework’); … De está manera no necesitas un import cada vez que crees una función en ese archivo

* **Jessie Buckland Pérez** (1) [912209](https://platzi.com/comentario/912209/) 

	Impresionante, quizás se deba a que no estoy siguiendo la ruta ideal de aprendizaje de JS, TS, NodeJs etc, pero me pareció muy importante el inicio del curso, su introducción y como has planteado la organización de código para que sea utilizado por node. Enhorabuena!!!

* **Jessie Buckland Pérez** (1) [912192](https://platzi.com/comentario/912192/) 

	Técnica para usar código javascript en nodejs usando módulos.

# Análisis estático de código [3767]

## 0070. Herramientas de análisis estático de código [18796](https://platzi.com/clases/1542-pruebas-unitarias/18796-herramientas-de-analisis-estatico-de-codigo/)

### Descripción:


 **Linters** : Herramientas de alertas. Nos ayudan a seguir las reglas o convenciones de nuestros equipos sin tener que memorizar todo el libro de reglas; solo debemos programar y asegurarnos de que estas herramientas revisen nuestro código.

Por ejemplo: [ESLint](https://eslint.org), [JSHint](http://csscomb.com), [CSSComb](http://csscomb.com) o [scsslint](https://github.com/brigade/scss-lint).

**Corrección automática** : Herramientas que nos ayudan a revisar y arreglar nuestro código sin importar si usamos un editor de código u otro; funcionan para todos los casos y gustos de la comunidad. Por ejemplo: [Prettier](https://prettier.io).

**Tipado** : JavaScript es lenguaje de tipado dinámico, podemos cambiar el tipo de variables cada vez que queramos o necesitemos. Pero, podemos usar diferentes herramientas para implementar el tipado fuerte, es decir, que podamos usar variables con tipos diferentes al que definimos inicialmente (a menos que hagamos una conversión).

La herramienta de tipado más popular en JavaScript es [TypeScript](https://www.typescriptlang.org/) pero tambien existen algunas alternativas como [Flow](https://flow.org) y [React PropTypes](https://reactjs.org/docs/typechecking-with-proptypes.html).

### Links:

* [ESLint - Pluggable JavaScript linter](https://eslint.org)

* [Prettier · Opinionated Code Formatter](https://prettier.io)

* [CSScomb: Makes your code beautiful](http://csscomb.com)

* [CSScomb: Makes your code beautiful](http://csscomb.com)

* [GitHub - brigade/scss-lint: Configurable tool for writing clean and consistent SCSS](https://github.com/brigade/scss-lint)

* [
    
      TypeScript - JavaScript that scales.
    
  ](https://www.typescriptlang.org)

* [Flow: A Static Type Checker for JavaScript](https://flow.org)

* [Typechecking With PropTypes – React](https://reactjs.org/docs/typechecking-with-proptypes.html)

### Comentarios:

* **vanesora** (8) [561650](https://platzi.com/comentario/561650/) 

	Yo he trabajado con TypeScript con Angular y con React, y me parece super genial

* **ricardocelis (Platzi)** (8) [547991](https://platzi.com/comentario/547991/) 

	<https://eslint.org>  
	<https://prettier.io>  
	<http://csscomb.com>  
	<https://jshint.com>  
	<https://github.com/brigade/scss-lint>  
	<https://www.typescriptlang.org>  
	<https://flow.org>  
	<https://reactjs.org/docs/typechecking-with-proptypes.html>

## 0080. ESLint Agregando alertas a nuestro código con ECMA Script [18797](https://platzi.com/clases/1542-pruebas-unitarias/18797-eslint-agregando-alertas-a-nuestro-codigo-con-ecma/)

### Descripción:


ESLint es una herramienta que identifica y reporta patrones y errores en código ECMAScript/JavaScript. Es similar a JS-Lint y JSHint con algunas diferencias:

* ESLint usa Espree para analizar JavaScript.
* ESLint usa un AST para evaluar patrones en código.
* ESLint soporta plugins, cada regla es un plugin y puedes agregar más en desarrollo.



### Links:

* [ESLint - Pluggable JavaScript linter](https://eslint.org)

* [eslint-config-standard/eslintrc.json at master · standard/eslint-config-standard · GitHub](https://github.com/standard/eslint-config-standard/blob/master/eslintrc.json)

### Comentarios:

* **Davidre0795** (4) [550303](https://platzi.com/comentario/550303/) 

	[Link](https://github.com/standard/eslint-config-standard/blob/master/eslintrc.json)

	* **Damian Spizzirri** [550303] (3)

		Con eslint --init pueden generar el codigo automaticamente.

## 0090. Herramientas de corrección de estilo [18798](https://platzi.com/clases/1542-pruebas-unitarias/18798-herramientas-de-correccion-de-estilo/)

### Descripción:


Prettier es un formateador de código opinado. Aplica un estilo coherente al analizar su código y reimprimirlo con sus propias reglas que toman en cuenta la longitud máxima de la línea, envolviendo el código cuando sea necesario.

Puede ejecutarse en su editor al guardar, en un gancho de confirmación previa o en entornos CI para garantizar que su base de código tenga un estilo coherente sin que los desarrolladores tengan que publicar un comentario minucioso sobre una revisión de código.

Ofrece soporte para:

* JavaScript, including ES2017
* JSX
* Angular
* Vue
* Flow
* TypeScript
* CSS, Less, and SCSS
* HTML
* JSON
* GraphQL
* Markdown, including GFM and MDX
* YAML



Por ejemplo tenemos éste codigo de JavaScript mal formateado:
``` 
    foo(reallyLongArg(), omgSoManyParameters(), IShouldRefactorThis(), isThereSeriouslyAnotherOne());
    
```

Al pasar Prettier nos lo deja de una manera más legible:
``` 
    foo(
      reallyLongArg(),
      omgSoManyParameters(),
      IShouldRefactorThis(),
      isThereSeriouslyAnotherOne()
    );
    
```

### Links:

* [Prettier · Opinionated Code Formatter](https://prettier.io)

### Comentarios:

* **Ale17273has** (3) [617527](https://platzi.com/comentario/617527/) 

	Recomiendo no instalar cosas globales mejor dejarlas sobre el proyecto, en este caso para instalar como dependencia de desarrollo seria npm install --save-dev prettier

* **Cristian De Blasis** (2) [552991](https://platzi.com/comentario/552991/) 

	En mi caso al instalar Prettier no me formateaba al guardar. Para esto tuve que ir a File->Preference->Setting Text Editor-> Formating y active el combo “Format on Save”

	* **Kevin William Roberts Costa** [552991] (1)

		También está interesante setear esbenp.prettier-vscode como Default Formatter; por lo que entiendo sino funciona por defecto el vscode. Pero esto no está claro, por lo menos no funciona como en la clase.

* **Damian Spizzirri** (1) [618191](https://platzi.com/comentario/618191/) 

	eslint me arroja error al final del ultimo caracter, se les ocurre porque puede ser?? Despues del ; del saludar. Probe poniendolo entre { } y sacando el : pero sigue igual.
	``` 
	    const saludar = nombre => `Hola ${nombre}`;
	    
	    module.exports = saludar;
	    
	```

* **Gustavo Ramírez Apache** (1) [585914](https://platzi.com/comentario/585914/) 

	En el caso quie necesiten hacer override pueden crear un archivo para agregar lo que quieran ahi, por ejemplo en mi caso no uso ; por lo que lod esactive seteando semi en false . <https://prettier.io/docs/en/configuration.html>

* **ricardocelis (Platzi)** (1) [548021](https://platzi.com/comentario/548021/) 

	<https://prettier.io>

## 0100. Herramientas de tipado [18799](https://platzi.com/clases/1542-pruebas-unitarias/18799-herramientas-de-tipado/)

### Descripción:


TypeScript es un lenguaje de programación libre y de código abierto desarrollado y mantenido por Microsoft.

Es un superconjunto de JavaScript, que esencialmente añade tipado estático y objetos basados en clases.

TypeScript extiende la sintaxis de JavaScript, por tanto cualquier código JavaScript existente debería funcionar sin problemas.

Está pensado para grandes proyectos, los cuales a través de un compilador de TypeScript se traducen a código JavaScript original.

### Links:

* [
    
      TypeScript - JavaScript that scales.
    
  ](https://www.typescriptlang.org)

### Comentarios:

* **Wilson Fabian Pérez Sucuzhañay** (1) [561466](https://platzi.com/comentario/561466/) 

	donde podemos ver ese código ¿? no hay repositorio¿?

	* **Diego Alexander Forero Higuera (Platzi)** [561466] (2)

		Hola, encuentras el repo aquí <https://github.com/xthecapx/mean/> en clases más adelante lo encuentras también en la pestaña de archivos.

# Trabajando con Jasmine en el frontend [3762]

## 0110. Profundización en SpyOn Comandos más utilizados y cómo ponerlos a prueba [19189](https://platzi.com/clases/1542-pruebas-unitarias/19189-profundizacion-en-spyon-comandos-mas-utilizados-y-/)

### Descripción:


## Jasmine spyOn

La separación de responsabilidades es una de las buenas prácticas que encontramos en un proyecto de software. Separar responsabilidades significa agrupar código de tal manera que cada conjunto se encargue de una tarea específica.

Hablemos ahora de las pruebas unitarias. Cuando probamos un componente, queremos probar las responsabilidades que le estamos delegando al componente y no todo el código ejecutado. Es decir, si el componente A utiliza la función b(), lo que queremos probar es la lógica propia del componente y no el código de la función.

Veamos el siguiente ejemplo:
``` 
    function GetMonthApi() {
      this.currentMonth = function () {
        return 'May';
      }
      this.nextMonth = function () {
        return 'June'
      }
    }
    export function MonthCalculator() {
      this.api = new getMonthApi();
      this.getNextMonth = function() {
        return this.api.nextMonth();
      }
      this.getCurrentMonth = function() {
        return this.api.currentMonth();
      }
    }
    
```

La clase **`MonthCalculator`** nos permite calcular el valor del mes actual y el siguiente. Cómo puedes ver, la función **`getMonthApi`** es utilizada dentro de la clase. Si ejecutas el set de pruebas asociadas a nuestra clase se ejecuta en Mayo el valor del siguiente mes sería Junio, o si las corres en Enero el siguiente mes sería Febrero. ¿Ves el problema?.

Si ejecutamos código que se encuentre fuera del domino de un componente, nos podemos encontrar con resultados inesperados. Es por ello, que jasmine cuenta con un sistema de espías (spyOn), cuyo objetivo principal es interceptar la ejecución de una función y simular su resultado.

### Veamos un poco de código:

El primer método que vamos a probar es el de obtener el mes actual `currentMonth`. Si la prueba la creamos en mayo, el código debería ser:
``` 
    describe('MonthCalculator', () => {
      it('returns the current month', () => {
        // Arrange
        const monthCalculator = new MonthCalculator();  
        // Act
        const month = monthCalculator.currentMonth();
        // Assert
        expect(month).toBe('May');
      });
    });
    
```

Este código tiene un problema. La función **`currentMonth`** va a retornar un valor que depende del mes actual.

Como ya te podrás imaginar, el uso de espías resulta bastante útil en este caso debido a que podemos controlar el valor del mes retornado.

Es decir:
``` 
    describe('MonthCalculator', () => {
      it('returns the current month', () => {
        // Arrange
        const monthCalculator = new MonthCalculator();
        const spy = spyOn(
                     monthCalculator.api,
                     'currentMonth'
                   ).and.returnValue('Cristian Month');
        // Act
        const month = monthCalculator.currentMonth();
        // Assert
        expect(month).toBe('Cristian Month');
        expect(spy).toHaveBeenCalled();
      });
    });
    
```

La instancia del API la tenemos almacenada en la variable this.api de nuestra clase.  
Jasmine nos permite interceptar el llamado a nuestro API utilizando la función spyOn. Para ello, como primer parámetro debemos pasar el objeto que contiene el método que vamos a interceptar y como segundo parámetro el nombre del mismo.

Una vez creado nuestro espía, para poder controlar el valor retornado debemos concatenar lo siguiente: `.and.returnValue().`  
Finalmente Jasmine nos permite verificar la ejecución de la función por medio del operador `.toHaveBeenCalled().`

Cómo reto ve al siguiente **[enlace](https://stackblitz.com/edit/jasmine-testing-xthecapx)** , has un fork del proyecto y realiza las pruebas relacionadas con el método `nextMonth()`. Recuerda crear un espía para eliminar la dependencia con nuestra API.

### Finalmente, te dejo un listado de preguntas y respuestas sobre todo lo que puedes hacer con espías:

### ¿Cómo se crea un espía?
``` 
    spyOn(obj, 'method') // obj.method es una función
    
```

### ¿Cómo verificar que un método fue llamado?
``` 
    const ref = spyOn(obj, 'method');
    expect(ref).toHaveBeenCalled();
    // O directamente
    expect(obj.method).toHaveBeenCalled()
    
```

### ¿Cómo verificar que un método fue llamado con un parámetro específico?
``` 
    const ref = spyOn(obj, 'method');
    expect(ref).toHaveBeenCalledWith('foo', 'bar');
    // O directamente
    expect(obj.method).toHaveBeenCalledWith('foo', 'bar')
    
```

### ¿Cómo puedo verificar el número exacto de ejecuciones de un método?
``` 
    expect(obj.method.callCount).toBe(2)
    
```

### ¿Cómo espiar en un método sin modificar su comportamiento?
``` 
    spyOn(obj, 'method').andCallThrough()
    
```

### ¿Cómo puedo cambiar el valor retornado por un método?
``` 
    spyOn(obj, 'method').andReturn('value')
    
```

### ¿Cómo puedo sobreescribir un método?
``` 
    spyOn(obj, 'method').andCallFake(() => 'this is a function');
    
```

### Comentarios:

* **juan diego ramirez rojas** (3) [631255](https://platzi.com/comentario/631255/) 

	En este link explican spy0n de una manera mas facil <https://scriptverse.academy/tutorials/jasmine-spyon.html>

* **davidmoreno1989** (2) [577824](https://platzi.com/comentario/577824/) 

	Por favor revisar la redacción de este artículo, algunas frases están cortadas o incompletas.

	* **davidtoca (Platzi)** [577824] (1)

		Gracias por el reporte, ya lo vamos a revisar.

* **yisus_dev** (1) [1019261](https://platzi.com/comentario/1019261/) 

	hola, por acá les dejo un set de pruebas según la tarea que se manda a realizar en el post y les dejo la página donde se puede ver en acción dicho set
	``` 
	    describe('spyOn Platzi little class', () => {
	    
	      it('returns the current month', () => {
	        // Arrange
	        const monthCalculator = new MonthCalculator();  
	        // Act
	        const month = monthCalculator.getCurrentMonth();
	        // Assert
	        expect(month).toBe('May');
	      });
	    
	      it('returns the current month spy', () => {
	        // Arrange
	        const monthCalculator = new MonthCalculator();
	        const spy = spyOn(
	                     monthCalculator.api,
	                     'currentMonth'
	                   ).and.returnValue('Cristian Month');
	        // Act
	        const month = monthCalculator.getCurrentMonth();
	        // Assert
	        expect(month).toBe('Cristian Month');
	        expect(spy).toHaveBeenCalled();
	      });
	    
	      it('returns the next month method', () => {
	        // Arrange
	        const monthCalculator = new MonthCalculator();  
	        // Act
	        const month = monthCalculator.getNextMonth();
	        // Assert
	        expect(month).toBe('June');
	      });
	    
	      it('returns the next month spy', () => {
	        // Arrange
	        const monthCalculator = new MonthCalculator();
	        const spy = spyOn(
	                     monthCalculator.api,
	                     'nextMonth'
	                   ).and.returnValue('February Month');
	        // Act
	        const month = monthCalculator.getNextMonth();
	        // Assert
	        expect(month).toBe('February Month');
	        expect(spy).toHaveBeenCalled();
	      });
	    
	    });
	    
	```
	
	el codigo fuente es o el codigo de la solución es:
	``` 
	    (function(window) {
	      
	    functionGetMonthApi() {
	      this.currentMonth = function () {
	        return'May';
	      }
	      this.nextMonth = function () {
	        return'June'
	      }
	    }
	    functionMonthCalculator() {
	      this.api = new GetMonthApi();
	      this.getNextMonth = function() {
	        returnthis.api.nextMonth();
	      }
	      this.getCurrentMonth = function() {
	        returnthis.api.currentMonth();
	      }
	    }
	    
	      window.MonthCalculator = MonthCalculator;
	    
	    })(window);
	    
	```
	
	saludos!  
	en esta página web lo pueden verificar. esta super chido  
	<https://embed.plnkr.co/plunk/eDY1ap>

* **yisus_dev** (1) [1018956](https://platzi.com/comentario/1018956/) 

	este ejemplo esta malo, empece a realizar las pruebas en una pagina que corre jasmine con karma y de entrada
	``` 
	    this.api = new getMonthApi();
	    // instead
	    this.api = new GetMonthApi();
	    
	```
	
	simple en el test :
	``` 
	    <code>
	        // Act
	        const month = monthCalculator.currentMonth();
	    
	       // esta mal es : 
	        // Act
	        const month = monthCalculator.getCurrentMonth();
	    </code>
	    
	```

* **David Behar** (1) [1011159](https://platzi.com/comentario/1011159/) 

	Estoy batallando por entender cómo funcionan los espías, para eso intenté hacer un espía basado en el ejercicio que se muestra acá pero más realista (que sí regrese el verdadero mes),  
	.
	
	## No estoy pudiendo fakear la fecha para que regrese lo que quiero, ¿alguna recomendación?
	
	.  
	Código fuente: <https://github.com/behagoras/jasmine-tests/tree/currentDate>
	
	## months.js
	``` 
	    functiongetMonthApi() {
	      this.monthNames = ["January", "February", "March", "April", "May", "June",
	      "July", "August", "September", "October", "November", "December"];
	    
	      this.currentDate = newDate()
	      this.cmonth = this.currentDate.getMonth()
	    
	      this.currentMonth = function () {
	        returnthis.monthNames[this.cmonth-1]
	      }
	    
	      this.nextMonth = function () {
	        returnthis.monthNames[this.cmonth]
	      }
	    
	    }
	    
	    functionMonthCalculator() {
	    
	      this.api = new getMonthApi();
	    
	      this.getNextMonth = function() {
	        returnthis.api.nextMonth();
	      }
	      this.getCurrentMonth = function() {
	        returnthis.api.currentMonth();
	      }
	    }
	    
	```
	
	## months.spec.js
	``` 
	    module.exports = MonthCalculator
	    const MonthCalculator = require('../../src/components/months')
	    
	    describe('Month Calculator',()=>{
	      it('Should return current month',()=>{
	        const monthCalculator = new MonthCalculator()
	        const date = newDate("June 17, 1995 03:24:00")
	    
	        monthCalculator.api.currentDate=date
	        const spy = spyOn(monthCalculator.api, 'currentDate').and.resolveTo(date)
	    
	        console.log('monthCalculator.getCurrentMonth()',monthCalculator.getCurrentMonth())
	    
	        const y = monthCalculator.getCurrentMonth();
	        expect(y).toBe('June')
	    
	      })
	    })
	    
	```

	* **vladernn** [1011159] (1)

		Prueba a utilizar:
		``` 
		    <code>
		    .and.returnValue(date);
		    </code>
		    
		```
		
		en vez de:
		``` 
		    <code>
		    .and.resolveTo(date);
		    </code>
		    
		```

* **Damian Spizzirri** (1) [618240](https://platzi.com/comentario/618240/) 

	Puede ser que al proyecto le falte el archivo angular.json??

* **Damian Spizzirri** (1) [618237](https://platzi.com/comentario/618237/) 

	Descarge el projecto, ejecute npm install y despues ng serve.
	
	Me sale este error **_The serve command requires to be run in an Angular project, but a project definition could not be found_**
	
	Que onda??

* **Damian Spizzirri** (1) [618215](https://platzi.com/comentario/618215/) 

	Creo que no entendi la ultima pregunta. Yo con el CallFake puedo reescribir la funcion para que haga lo que yo quieaa??

* **Ale17273has** (1) [617540](https://platzi.com/comentario/617540/) 

	¿ Por que no todo se maneja con git hub?

* **mauxiandrade** (1) [595123](https://platzi.com/comentario/595123/) 

	“Cómo reto ve al siguiente enlace, has un fork del repo …”
	
	Cuál enlace??

	* **ricardocelis (Platzi)** [595123] (1)

		ya le aviso al team para que ajusten esta clase, gracias por avisar Mauxi

	* **mauxiandrade** [595123] (1)

		Ok estaré pendiente para realizar el repo

	* **ricardocelis (Platzi)** [595123] (1)

		ya está lista la lectura! con todo y el enlace al repo =)

* **Kevin William Roberts Costa** (0) [1042811](https://platzi.com/comentario/1042811/) 

	Me frustré muy feo con este curso 😦 me voy a cursar js de nuevo

## 0120. Configurar un ambiente de trabajo para trabajar con el framework jasmine [18779](https://platzi.com/clases/1542-pruebas-unitarias/18779-configurar-un-ambiente-de-trabajo-para-trabajar-co/)

### Descripción:


Jasmine es un framework de Desarrollo dirigido por comportamientos ( _Behavior Driven Development_ ) para realizar nuestras pruebas unitarias con JavaScript.

Puede ser ejecutado en el navegador pero también podemos usar un _headless browser_ para automatizar mejor las pruebas. Por ejemplo, con [PhantomJS](http://phantomjs.org), [CasperJS](http://casperjs.org/) o [ZombieJS](http://zombie.js.org/).

Tampoco necesitamos un DOM; por lo que, es posible hacer pruebas en cualquier Javascript Engine como Rhino o V8 (como Node.js).

_**¿Cómo funciona?**_

Las funciones principales de Jasmine para hacer pruebas son las siguientes:

* _**describe(a, b)**_ donde “a” es la descripción de nuestra suite y “b” la función anónima donde se incluirá toda la suite o serie de especificaciones.
* _**it(a, b)**_ donde “a” es la descripción de la especificación y “b” la función anónima donde se incluirán las expectativas (expectations) que debe cumplir la aplicación.
* _**expect(a)**_ donde “a” es un valor que será probado, mediante argumentos en cadena (method chaining). Por ejemplo: expect(true).not.toBe(false).
* _**beforeAll(a)**_ donde “a” será la función que se ejecutará antes de iniciar las pruebas.
* _**afterAll(a)**_ donde “a” será la función que se ejecutará después de iniciar las pruebas.
* _**beforeEach(a)**_ donde “a” será la función que se ejecutará antes de cada prueba.
* _**afterEach(a)**_ donde “a” será la función que se ejecutará después de cada prueba.



### Links:

* [Jasmine Documentation](https://jasmine.github.io/)

### Comentarios:

* **mario-salinas** (2) [571566](https://platzi.com/comentario/571566/) 

	Les dejo los links
	``` 
	    <link
	          rel="stylesheet"
	          type="text/css"
	          href="https://cdnjs.cloudflare.com/ajax/libs/jasmine/3.4.0/jasmine.css"
	        />
	    
	        <script
	          type="text/javascript"
	          src="https://cdnjs.cloudflare.com/ajax/libs/jasmine/3.4.0/jasmine.js"
	        ></script>
	        <script
	          type="text/javascript"
	          src="https://cdnjs.cloudflare.com/ajax/libs/jasmine/3.4.0/jasmine-html.js"
	        ></script>
	        <script
	          type="text/javascript"
	          src="https://cdnjs.cloudflare.com/ajax/libs/jasmine/3.4.0/boot.js"
	        ></script>
	    
	```

* **Roy Hodson** (1) [1052086](https://platzi.com/comentario/1052086/) 

	Con ctrl+d en vscode puedes seleccionar todas las incidencias de texto, para reemplazar un poco mas rapido

## 0130. Configurar Jasmine utilizando Node.js [18780](https://platzi.com/clases/1542-pruebas-unitarias/18780-configurar-jasmine-utilizando-nodejs/)

### Descripción:


Gracias a Node.js obtenemos algunas ventajas para desarrollar y probar nuestras aplicaciones. Necesitamos un archivo `package.json`, en caso de que tu proyecto no lo tenga todavía, puedes crearlo ejecutando el siguiente comando:

Vamos a necesitar un archivo `package.json`
``` 
    npm init
    
```

Debemos ejecutar los siguientes comandos para instalar e iniciar Jasmine en nuestro proyecto con Node.js:
``` 
    npm install --save-dev jasmine
    node node_modules/jasmine/bin/jasmine init
    
```

Por último, para correr las pruebas que vamos a crear en las próximas clases, debemos agregar un nuevo `script` en nuestro package.json y ejecutarlo con el comando `npm test`:
``` 
    "scripts": {
        "test": "jasmine"
    }
    
```

### Links:

* [Node.js](https://nodejs.org/es/)

### Comentarios:

* **tzalejo** (2) [956451](https://platzi.com/comentario/956451/) 

	Para ver la url de [jasmin](https://jasmine.github.io/pages/getting_started.html).  
	Saludos

* **Ale17273has** (1) [617570](https://platzi.com/comentario/617570/) 

	En caso que haya añadido la carpeta en el git add, sin haber creado el gitignore solo debe hacer un git reset node_modules y luego si ejecutan el commit

* **Ale17273has** (1) [617566](https://platzi.com/comentario/617566/) 

	Les recomiendo que en su proyecto git crear el archivo .gitignore para no subir los archivos modules asi quedaria
	
	<h1>See <http://help.github.com/ignore-files/> for more about ignoring files.</h1> <h1>compiled output</h1>
	
	/dist  
	/tmp  
	/out-tsc
	
	<h1>dependencies</h1>
	
	/node_modules
	
	<h1>IDEs and editors</h1>
	
	/.idea  
	.project  
	.classpath  
	.c9/  
	*.launch  
	.settings/  
	*.sublime-workspace
	
	<h1>IDE - VSCode</h1>
	
	.vscode/*  
	!.vscode/settings.json  
	!.vscode/tasks.json  
	!.vscode/launch.json  
	!.vscode/extensions.json
	
	<h1>misc</h1>
	
	/.sass-cache  
	/connect.lock  
	/coverage  
	/libpeerconnection.log  
	npm-debug.log  
	testem.log  
	/typings
	
	<h1>e2e</h1>
	
	/e2e/ _.js  
	/e2e/_.map
	
	<h1>System Files</h1>
	
	.DS_Store  
	Thumbs.db

## 0140. Primer set de pruebas con Jasmine [18781](https://platzi.com/clases/1542-pruebas-unitarias/18781-primer-set-de-pruebas-con-jasmine/)

### Descripción:


Funciones de Jasmine con las cuales podremos experimentar:

* `expect(x).toEqual(y)` verifica si ambos valores son iguales.
* `expect(x).toBe(y)` verifica si ambos objetos son iguales.
* `expect(x).toMatch(pattern)` verifica si el valor pertenece al patrón establecido.
* `expect(x).toBeDefined()` verifica si el valor está definido.
* `expect(x).toBeUndefined()` verifica si el valor es indefinido.
* `expect(x).toBeNull()` verifica si el valor es nulo.
* `expect(x).toBeTruthy()` verifica si el valor es verdadero.
* `expect(x).toBeFalsy();` verifica si el valor es falso.
* `expect(x).toContain(y)` verifica si el valor actual contiene el esperado.
* `expect(x).toBeLessThan(y)` verifica si el valor actual es menor que el esperado.
* `expect(x).toBeGreaterThan(y)` verifica si el valor actual es mayor que el esperado.



### Comentarios:

* **Ale17273has** (1) [617582](https://platzi.com/comentario/617582/) 

	Algunos de los test que cree
	``` 
	    <const saludar = require("../app");
	    
	    var x = true;
	    
	    const letra = "AB";
	    
	    var tmp = undefined;
	    
	    describe("Prueba de test para string", () => {
	      it("La función saluda", () => {
	        expect(saludar("Platzi")).toBe("Hola Platzi");
	      });
	    
	      it("Comprobar valores booleanos", () => {
	        expect(x).toBeTruthy();
	      });
	    
	      it("Comprobar valores iguales", () => {
	        expect(x).toEqual(true);
	      });
	    
	      it("Comprobar valores iguales", () => {
	        expect(x).toBe(true);
	      });
	    
	      it("Comprobar valores de expresiones regulares", () => {
	        expect(x).toMatch("[^AB]");
	      });
	    
	      it("Comprobar valores undefined", () => {
	        expect(tmp).toBeUndefined();
	      });
	    });
	    >
	    
	```

* **Gustavo Ramírez Apache** (1) [585966](https://platzi.com/comentario/585966/) 

	Pregunta que debo configurar en eslint para que no pida que este definido algo, osea en app.spect tenemos el it y el expect pero vsc me lo marca con rojito diciendo que no hay un error que no esta definido it y expect, que tengo que modificar en el slint para que no me muestre esto, porque la verdad es maluco y puede hacer que une se equivoque cojnh esos errores

	* **Cristian Daniel Marquez Barrio** [585966] (1)

		Hay varias formas de lograr esto:
		
		  1. Te dejo la documentación: <https://eslint.org/docs/user-guide/configuring#configuration-based-on-glob-patterns>
		  2. Puedes deshabilitar las reglas globalmente utilizando un archivo `.eslintrc.*` o `package.json`, de la siguiente manera:
		
		
		``` 
		    {
		      "rules": {
		        "quotes": [ 2, "double" ]
		      },
		    
		      "overrides": [
		        {
		          "files": [ "bin/*.js", "lib/*.js" ],
		          "excludedFiles": "*.test.js",
		          "rules": {
		            "quotes": [ 2, "single" ]
		          }
		        }
		      ]
		    }
		    
		```
		
		  1. La otra opción que tienes es deshabilitar las reglas con los comentarios. algo como
		
		
		``` 
		    /* eslint-disable no-alert, no-console */
		    
		    alert('foo');
		    console.log('bar');
		    
		    /* eslint-enable no-alert, no-console */
		    
		```

	* **Ale17273has** [585966] (1)

		Considero que lo mejor no es des habilitar el lint o ajustarlo a nuestro código, debido a que son estándares, recomiendo utilizar webstorm se ajusta al lint que uno le pase o a veces el mismo hace la correcion o la da sugerencia

	* **Diego Alberto Meneses Tamayo** [585966] (1)
<h1>Eslint y jasmin</h1>
		
		Para que es lint no genere alertas instalar el plugin
		``` 
		    https://www.npmjs.com/package/eslint-plugin-jasmine
		    
		```
		
		y en el archivo .eslintrc.js poner:
		``` 
		    env: {
		        jasmine: true
		    }
		    
		```

## 0150. Diccionario Jasmine [19190](https://platzi.com/clases/1542-pruebas-unitarias/19190-diccionario-jasmine/)

### Descripción:


Esta lectura te servirá de referencia para las cosas que puedes hacer con Jasmine:
``` 
    Creando un set de pruebas
    describe("Componente", () => {
      it("debería ...", () => {
        expect(true).toBe(true);
      });
    });
    
    Agrupando por funcionalidad
    describe("Componente", () => {
      describe("Funcionalidad uno", () => {
        it("debería ...", () => {
          expect(true).toBe(true);
        });
      });
    });
    
```

Matchers
``` 
    expect(false).not.toBe(true); // Prueba negativa
    comparación con ===, ejemplo: 1 === 1 1 !== '1'
    
    expect(thing).toBe(realThing);
    El valor no es undefined 
    
    expect(result).toBeDefined();
    El valor actual es falso, ejemplo:0, '', false
    
    expect(result).toBeFalsy();
    El valor actual es verdadero, ejemplo: 'sd', 1, true
    
    expect(thing).toBeTruthy();
    El valor actual es mayor al esperado
    
    expect(result).toBeGreaterThan(3);
    El valor actual es mayor o igual al esperado
    
    expect(result).toBeGreaterThanOrEqual(25);
    El valor actual es menor al esperado
    
    expect(result).toBeLessThan(0);
    El valor actual es menor o igual al esperado
    
    expect(result).toBeLessThanOrEqual(123);
    El valor actual es NaN
    
    expect(thing).toBeNaN();
    El valor actual es -Infinity 
    
    expect(thing).toBeNegativeInfinity();
    El valor actual es Infinity
    
    expect(thing).toBePositiveInfinity();
    El valor actual es null 
    
    expect(result).toBeNull();
    El valor actual continue una cadena. Ejemplo:
    
     'Hola mundo'.toContain('Hola') // true
    ['Hola', 'mundo'].toContain('Hola') // true
    expect(array).toContain(anElement); expect(string).toContain(substring);
    El valor actual es igual utilizando una comparación profunda
    
    expect(bigObject).toEqual({"foo": ['bar', 'baz']});
    El espía fue llamado
    
    expect(mySpy).toHaveBeenCalled(); expect(mySpy).not.toHaveBeenCalled();
    El espía fue llamado antes que otro
    
    expect(mySpy).toHaveBeenCalledBefore(otherSpy);
    El espía fue llamado n veces:
    
    expect(mySpy).toHaveBeenCalledTimes(3);
    El espía fue llamado con los siguientes parámetros
    
    expect(mySpy).toHaveBeenCalledWith('foo', 'bar', 2);
    Verificar si un elemento tiene una clase
    
    const el = document.createElement('div');
    el.className = 'foo bar baz';
    expect(el).toHaveClass('bar');
    El valor actual comparado con una expresión regular
    
    expect("my string").toMatch(/string$/); 
    expect("other string").toMatch("her");
    Ciclos de vida
    describe("Component", () => {
      // Shared variables
      var foo = 0;
    beforeAll(() => {})
      beforeEach(() => {})
      afterEach(() => {})
      afterAll(() => {})
    });
    Deshabilitando pruebas
    xdescribe("A spec", () => {
      it("waiting to be enable", function() {
        expect(true).toEqual(true);
      });
    });
    describe("A spec", () => {
      it("this run", () => {
        expect(true).toEqual(true);
      });
      xit("this is skipped", () => {
        expect(true).toEqual(true);
      });
    });
    Utilizando spyOn
    describe('A spy', () => {
      let foo,
        bar = null;
      beforeEach(() => {
        foo = {
          setBar: value => {
            bar = value;
          },
        };
        spyOn(foo, 'setBar');
        foo.setBar(123);
        foo.setBar(456, 'another param');
      });
      it('tracks that the spy was called', () => {
        expect(foo.setBar).toHaveBeenCalled();
      });
      it('tracks that the spy was called x times', () => {
        expect(foo.setBar).toHaveBeenCalledTimes(2);
      });
      it('tracks all the arguments of its calls', () => {
        expect(foo.setBar).toHaveBeenCalledWith(123);
        expect(foo.setBar).toHaveBeenCalledWith(456, 'another param');
      });
    });
    Crear espía cuando desconocemos si la función existe
    describe("Create a 'bare' spy", () => {
      let notSure;
      beforeEach(function() {
        notSure = jasmine.createSpy('notSure');
        notSure("I", "am", "a", "spy");
      });
      it("tracks that the spy was called", function() {
        expect(notSure).toHaveBeenCalled();
      });
    });
    Creando multiples espías en un mismo objeto
    describe("Multiple spies", () => {
      const tape;
      beforeEach(() => {
        tape = jasmine.createSpyObj('tape', ['play', 'pause', 'stop']);
        tape.play();
          tape.pause();
          tape.rewind(0);
        });
      it("creates spies for each requested function", () => {
        expect(tape.play).toBeDefined();
        expect(tape.pause).toBeDefined();
        expect(tape.stop).toBeDefined();
      });
    });
    Verificar una propiedad de un objeto
    describe("jasmine.objectContaining", () => {
      let foo;
      beforeEach(() => {
        foo = {
          a: 1,
          b: 2,
          bar: "baz"
        };
      });
      it("matches objects with the expect key/value pairs", () => {
        expect(foo).toEqual(jasmine.objectContaining({
          bar: "baz"
        }));
        expect(foo).not.toEqual(jasmine.objectContaining({
          c: 37
        }));
      });
    });
    Verificar una propiedad dentro de un objeto pasado como parámetro a una función
    describe('jasmine.objectContaining', () => {
      it('is useful for comparing arguments', () => {
        const callback = jasmine.createSpy('callback');
        callback({
          bar: 'baz',
        });
        expect(callback).toHaveBeenCalledWith(
          jasmine.objectContaining({
            bar: 'baz',
          })
        );
      });
    });
    Verificar un valor dentro de un arreglo
    describe("jasmine.arrayContaining", () => {
      let foo;
      beforeEach(function() {
        foo = [1, 2, 3, 4];
      });
      it("matches arrays with some of the values", () => {
        expect(foo).toEqual(jasmine.arrayContaining([3, 1]));
        expect(foo).not.toEqual(jasmine.arrayContaining([6]));
      });
    });
    Verificar un valor dentro de un arreglo pasado como parámetro a una función
    describe('jasmine.arrayContaining', () => {
      it('is useful when comparing arguments', () => {
        const callback = jasmine.createSpy('callback');
        callback([1, 2, 3, 4]);
       expect(callback)
         .toHaveBeenCalledWith(jasmine.arrayContaining([4, 2, 3]));
       expect(callback)
         .not.toHaveBeenCalledWith(jasmine.arrayContaining([5, 2]));
      });
    });
    Usando regex para comparar comparar cadenas de texto
    describe('jasmine.stringMatching', () => {
      it("matches as a regexp", () => {
        expect({foo: 'bar'})
          .toEqual({foo: jasmine.stringMatching(/^bar$/)});
        expect({foo: 'foobarbaz'})
          .toEqual({foo: jasmine.stringMatching('bar')});
      });
       describe("when used with a spy", () => {
        it("comparing arguments", () => {
          const callback = jasmine.createSpy('callback');
          callback('foobarbaz');
          expect(callback)
            .toHaveBeenCalledWith(jasmine.stringMatching('bar'));
          expect(callback)
            .not.toHaveBeenCalledWith(jasmine.stringMatching(/^bar$/));
        });
      });
    });
    
```

### Comentarios:

* **David Behar** (3) [1009736](https://platzi.com/comentario/1009736/) 

	Se confunde un poco con todo en el mismo bloque de código, acá un edit  
	Prueba negativa
	``` 
	    expect(false).not.toBe(true); comparación con ===, ejemplo: 1 === 11 !== '1'
	    
	```
	
	Igualdad completa:
	``` 
	    expect(thing).toBe(realThing);
	    
	```
	
	El valor no es undefined
	``` 
	    expect(result).toBeDefined();
	    
	```
	
	El valor actual es falso, ejemplo:0, ‘’, false
	``` 
	    expect(result).toBeFalsy();
	    
	```
	
	El valor actual es verdadero, ejemplo: ‘sd’, 1, true
	``` 
	    expect(thing).toBeTruthy();
	    
	```
	
	El valor actual es mayor al esperado
	``` 
	    expect(result).toBeGreaterThan(3);
	    
	```
	
	El valor actual es mayor o igual al esperado
	``` 
	    expect(result).toBeGreaterThanOrEqual(25);
	    
	```
	
	El valor actual es menor al esperado
	``` 
	    expect(result).toBeLessThan(0);
	    
	```
	
	El valor actual es menor o igual al esperado
	``` 
	    expect(result).toBeLessThanOrEqual(123);
	    
	```
	
	El valor actual es NaN
	``` 
	    expect(thing).toBeNaN();
	    
	```
	
	El valor actual es -Infinity
	``` 
	    expect(thing).toBeNegativeInfinity();
	    
	```
	
	El valor actual es Infinity
	``` 
	    expect(thing).toBePositiveInfinity();
	    
	```
	
	El valor actual es null
	``` 
	    expect(result).toBeNull();
	    
	```
	
	El valor actual continue una cadena. Ejemplo:
	``` 
	    'Hola mundo'.toContain('Hola') // true
	    ['Hola', 'mundo'].toContain('Hola') // true
	    expect(array).toContain(anElement); expect(string).toContain(substring);
	    
	```
	
	El valor actual es igual utilizando una comparación profunda
	``` 
	    expect(bigObject).toEqual({"foo": ['bar', 'baz']});
	    
	```
	
	El espía fue llamado
	``` 
	    expect(mySpy).toHaveBeenCalled(); expect(mySpy).not.toHaveBeenCalled();
	    
	```
	
	El espía fue llamado antes que otro
	``` 
	    expect(mySpy).toHaveBeenCalledBefore(otherSpy);
	    
	```
	
	El espía fue llamado n veces:
	``` 
	    expect(mySpy).toHaveBeenCalledTimes(3);
	    
	```
	
	El espía fue llamado con los siguientes parámetros
	``` 
	    expect(mySpy).toHaveBeenCalledWith('foo', 'bar', 2);
	    
	```
	
	Verificar si un elemento tiene una clase
	``` 
	    const el = document.createElement('div');
	    el.className = 'foo bar baz';
	    expect(el).toHaveClass('bar');
	    
	```
	
	El valor actual comparado con una expresión regular
	``` 
	    expect("my string").toMatch(/string$/); 
	    expect("other string").toMatch("her");
	    
	```
	
	Ciclos de vida
	``` 
	    describe("Component", () => {
	      // Shared variables
	      var foo = 0;
	    beforeAll(() => {})
	      beforeEach(() => {})
	      afterEach(() => {})
	      afterAll(() => {})
	    });
	    Deshabilitando pruebas
	    xdescribe("A spec", () => {
	      it("waiting to be enable", function() {
	        expect(true).toEqual(true);
	      });
	    });
	    describe("A spec", () => {
	      it("this run", () => {
	        expect(true).toEqual(true);
	      });
	      xit("this is skipped", () => {
	        expect(true).toEqual(true);
	      });
	    });
	    
	    
	```
	
	Utilizando spyOn
	``` 
	    describe('A spy', () => {
	      let foo,
	        bar = null;
	      beforeEach(() => {
	        foo = {
	          setBar: value => {
	            bar = value;
	          },
	        };
	        spyOn(foo, 'setBar');
	        foo.setBar(123);
	        foo.setBar(456, 'another param');
	      });
	      it('tracks that the spy was called', () => {
	        expect(foo.setBar).toHaveBeenCalled();
	      });
	      it('tracks that the spy was called x times', () => {
	        expect(foo.setBar).toHaveBeenCalledTimes(2);
	      });
	      it('tracks all the arguments of its calls', () => {
	        expect(foo.setBar).toHaveBeenCalledWith(123);
	        expect(foo.setBar).toHaveBeenCalledWith(456, 'another param');
	      });
	    });
	    
	```
	
	Crear espía cuando desconocemos si la función existe
	``` 
	    describe("Create a 'bare' spy", () => {
	      let notSure;
	      beforeEach(function() {
	        notSure = jasmine.createSpy('notSure');
	        notSure("I", "am", "a", "spy");
	      });
	      it("tracks that the spy was called", function() {
	        expect(notSure).toHaveBeenCalled();
	      });
	    });
	    
	```
	
	Creando multiples espías en un mismo objeto
	``` 
	    describe("Multiple spies", () => {
	      const tape;
	      beforeEach(() => {
	        tape = jasmine.createSpyObj('tape', ['play', 'pause', 'stop']);
	        tape.play();
	          tape.pause();
	          tape.rewind(0);
	        });
	      it("creates spies for each requested function", () => {
	        expect(tape.play).toBeDefined();
	        expect(tape.pause).toBeDefined();
	        expect(tape.stop).toBeDefined();
	      });
	    });
	    Verificar una propiedad de un objeto
	    describe("jasmine.objectContaining", () => {
	      let foo;
	      beforeEach(() => {
	        foo = {
	          a: 1,
	          b: 2,
	          bar: "baz"
	        };
	      });
	      it("matches objects with the expect key/value pairs", () => {
	        expect(foo).toEqual(jasmine.objectContaining({
	          bar: "baz"
	        }));
	        expect(foo).not.toEqual(jasmine.objectContaining({
	          c: 37
	        }));
	      });
	    });
	    
	    
	```
	
	Verificar una propiedad dentro de un objeto pasado como parámetro a una función
	``` 
	    describe('jasmine.objectContaining', () => {
	      it('is useful for comparing arguments', () => {
	        const callback = jasmine.createSpy('callback');
	        callback({
	          bar: 'baz',
	        });
	        expect(callback).toHaveBeenCalledWith(
	          jasmine.objectContaining({
	            bar: 'baz',
	          })
	        );
	      });
	    });
	    
	```
	
	Verificar un valor dentro de un arreglo
	``` 
	    describe("jasmine.arrayContaining", () => {
	      let foo;
	      beforeEach(function() {
	        foo = [1, 2, 3, 4];
	      });
	      it("matches arrays with some of the values", () => {
	        expect(foo).toEqual(jasmine.arrayContaining([3, 1]));
	        expect(foo).not.toEqual(jasmine.arrayContaining([6]));
	      });
	    });
	    
	```
	
	Verificar un valor dentro de un arreglo pasado como parámetro a una función
	``` 
	    describe('jasmine.arrayContaining', () => {
	      it('is useful when comparing arguments', () => {
	        const callback = jasmine.createSpy('callback');
	        callback([1, 2, 3, 4]);
	       expect(callback)
	         .toHaveBeenCalledWith(jasmine.arrayContaining([4, 2, 3]));
	       expect(callback)
	         .not.toHaveBeenCalledWith(jasmine.arrayContaining([5, 2]));
	      });
	    });
	    
	```
	
	Usando regex para comparar comparar cadenas de texto
	``` 
	    describe('jasmine.stringMatching', () => {
	      it("matches as a regexp", () => {
	        expect({foo: 'bar'})
	          .toEqual({foo: jasmine.stringMatching(/^bar$/)});
	        expect({foo: 'foobarbaz'})
	          .toEqual({foo: jasmine.stringMatching('bar')});
	      });
	       describe("when used with a spy", () => {
	        it("comparing arguments", () => {
	          const callback = jasmine.createSpy('callback');
	          callback('foobarbaz');
	          expect(callback)
	            .toHaveBeenCalledWith(jasmine.stringMatching('bar'));
	          expect(callback)
	            .not.toHaveBeenCalledWith(jasmine.stringMatching(/^bar$/));
	        });
	      });
	    });
	    
	```

* **Víctor Alejandro Sagal Muñoz** (1) [950345](https://platzi.com/comentario/950345/) 

	Un buen recurso como ayuda, pero se hace denso de entender que solo sea en texto y no con un video de apoyo.

* **Ale17273has** (1) [617583](https://platzi.com/comentario/617583/) 

	Gracias, otros que implemente yo
	
	const saludar = require("…/app");
	
	var x = true;
	
	const letra = “AB”;
	
	var tmp = undefined;
	
	describe(“Prueba de test para string”, () => {  
	it(“La función saluda”, () => {  
	expect(saludar(“Platzi”)).toBe(“Hola Platzi”);  
	});
	
	it(“Comprobar valores booleanos”, () => {  
	expect(x).toBeTruthy();  
	});
	
	it(“Comprobar valores iguales”, () => {  
	expect(x).toEqual(true);  
	});
	
	it(“Comprobar valores iguales”, () => {  
	expect(x).toBe(true);  
	});
	
	it(“Comprobar valores de expresiones regulares”, () => {  
	expect(x).toMatch("[^AB]");  
	});
	
	it(“Comprobar valores undefined”, () => {  
	expect(tmp).toBeUndefined();  
	});  
	});

# Probando Nodejs apps con Jasmine [3763]

## 0160. Introducción al módulo de testing del lado del servidor [18782](https://platzi.com/clases/1542-pruebas-unitarias/18782-introduccion-al-modulo-de-testing-del-lado-del-ser/)

### Descripción:


Vamos a crear las pruebas unitarias de una aplicación construida con el Stack MEAN: Node.js y Express.js en el backend, MongoDB como base de datos y Angular (con TypeScript) en el frontend.

Vamos a probar la interacción del frontend (Angular) con el servidor o con los clientes y cómo interactúa el servidor con el framework que hace las consultas a la base de datos y con el cliente que hace las peticiones. NO vamos a probar la base de datos directamente.

### Comentarios:

* **darwinyusef** (2) [770740](https://platzi.com/comentario/770740/) 

	Profe tengo una duda, asi de sencillo, Jasmin ó Jest ó Cypress la verdad no se cual aprender, yo diría Chocolate, Gomitas, Galletas difícil de decidir.

	* **nikosantis** [770740] (1)

		Yo también me lo pregunto.  
		En el curso de React Avanzado al final usamos un poquito de Cypress y tenía una interfaz gráfica extra para los tests y era bastante bueno. También está AVA que se usó en Node Avanzado. Jest creo que es muy similar a Jasmine.

* **William Vega** (2) [559882](https://platzi.com/comentario/559882/) 

	Me quedé sorprendido de la claridad semántica de las asersiones con expect(), me pregunto si sería posible utilizar este tipo de funciones para programar el código de la app misma? por ejemplo utilizar cosas como expect(variable).not().tobeNaN(), comprendo que para algunos casos esto implicaría escribir más código y es algo que fácilmente podría ser abusado para utilizar estas asersiones en lugar de expresiones más simples, (x != NaN), no obstante se ve fácilmente su utilidad al permitir la escritura de un código más claro; de otra manera porqué tomarse la molestia de crearlas y no dejar el testing framework con el uso de if’s o expresiones ternarias? Por otro lado yo nunca he visto en ningún lenguaje el uso de construcciones tan específicas (y tal número de las mismas) para hacer todo tipo de asersiones. Existe la forma de usar esto en javascript para la escritura del código de aplicación como parte del mismo? y si es así que tan práctico resultaría?

	* **Cristian Daniel Marquez Barrio** [559882] (3)

		Hola, te recomiendo revisar el curso de programación funcional (<https://platzi.com/cursos/funcional-js/>). El tipo de expresiones que describes es muy común utilizando programación funcional. La idea es tener código que se pueda leer como un libro.
		
		Yo en todos mis proyectos utilizo este estilo de programación, pues a pesar de que escribo un poco más de código, este queda mucho más claro y fácil de debuggiar.

* **William Vega** (2) [57061](https://platzi.com/comentario/559882/) 
Me quedé sorprendido de la claridad semántica de las asersiones con expect(), me pregunto si sería posible utilizar este tipo de funcione...

	* **Cristian Daniel Marquez Barrio** [57061] (3)

		Hola, te recomiendo revisar el curso de programación funcional (<https://platzi.com/cursos/funcional-js/>). El tipo de expresiones que describes es muy común utilizando programación funcional. La idea es tener código que se pueda leer como un libro.
		
		Yo en todos mis proyectos utilizo este estilo de programación, pues a pesar de que escribo un poco más de código, este queda mucho más claro y fácil de debuggiar.

## 0170. Configurando el proyecto Jasmine utilizando npm [18783](https://platzi.com/clases/1542-pruebas-unitarias/18783-configurando-el-proyecto-jasmine-utilizando-npm/)

### Descripción:


La diferencia entre `dependencies` (dependencias) y `devDependencies` (dependencias de desarrollo) es que las dependencias normales las instalamos siempre, en desarrollo o en producción. En cambio, las `devDependencies` son módulos que solo se vamos a necesitar en la etapa de desarrollo, no en producción.

Algunos buenos ejemplos de `dependencies` que se requerirían en tiempo de ejecución son, por ejemplo, _React, Redux, Express y Axios_.

Algunos buenos ejemplos de cuándo instalar `devDependencies` serían _Nodemon, Babel, ESLint_ y marcos de prueba como _Chai, Mocha, Enzyme, entre otros_.

### Comentarios:

* **Edison Perdomo** (7) [844420](https://platzi.com/comentario/844420/) 

	Si te genera fallo el npm run test:server coloca dentro del package.json la palabra node después la ruta del jasmine así
	
	“scripts”: {  
	“ng”: “ng”,  
	“start”: “ng build && node ./server/bin/www”,  
	“build”: “ng build”,  
	“test”: “ng test”,  
	“test:server”: “node ./node_modules/jasmine/bin/jasmine.js”,  
	“lint”: “ng lint”,  
	“e2e”: “ng e2e”  
	},

	* **jlrc23** [844420] (1)

		Eres un Dios, gracias!!!

* **Alexander Sandoval** (6) [556553](https://platzi.com/comentario/556553/) 

	El repositorio de Cristian se encuentra acá: <https://github.com/xthecapx/mean>
	
	Una vez clonen el repositorio ejecutan `npm install` para instalar las dependencias del proyecto.  
	Luego instalan Jasmine `npm install jasmine --save-dev`
	
	Luego comenzar los archivos de configuración de Jasmine: `./node_module/jasmine/bin/jasmine.js init`

* **David Marcelo Guamán Medina** (4) [675895](https://platzi.com/comentario/675895/) 

	Si están en windows 10 y llegaron al minuto 3:20 y no les funciona el jasmine.js init debe usar el siguiente comando:  
	node node_modules/jasmine/bin/jasmine init

* **Jorge Velasquez** (4) [574398](https://platzi.com/comentario/574398/) 

	Si tienen algún problema para inicializar el proyecto:  
	node node_modules/jasmine/bin/jasmine.js init

* **Elberth Jair Agreda Rosero** (2) [783793](https://platzi.com/comentario/783793/) 

	Si a alguien le interesa, cree este repositorio donde configure Typescript del lado del Backend y Frontend:  
	<https://github.com/elberthAgreda/docker-MEAN>

	* **Xavier Alexandro Basir Jeffrey** [783793] (1)

		Wow sumamente útil muchas gracias. Tenía errores por mi versión de node y npm. Y Usando docker y tu repo he podido proseguir con el curso

* **David Marcelo Guamán Medina** (2) [675913](https://platzi.com/comentario/675913/) 

	Ya para correr jasmine. js se utiliza el siguiente comando node node_modules/jasmine/bin/jasmine.js, esto se debe a que estamos corriendo jasmine dentro del proyecto.

## 0180. Agregando Plugins a Jasmine [18784](https://platzi.com/clases/1542-pruebas-unitarias/18784-agregando-plugins-a-jasmine/)

### Descripción:


Vamos a usar el plugin [jasmine-console-reporter](https://github.com/onury/jasmine-console-reporter) para obtener un resultado un poco más agradable y dinámico cuando corremos nuestras pruebas en la consola de comandos.

Para añadir este y otros plugins de Jasmine debemos crear un nuevo archivo llamado `specs.js` en la carpeta `/spec` con la siguiente configuración:
``` 
    const Jasmine = require('jasmine');
    const JasmineConsoleReporter = require('jasmine-console-reporter');
    
    const jasmine = new Jasmine();
    jasmine.loadConfigFile('spec/support/jasmine.json');
    
    const jasmineConsoleReporter = new JasmineConsoleReporter({
        colors: 1,
        cleanStack: 1,
        verbosity: 4,
        listStyle: 'indent',
        timeUnit: 'ms',
        timeThreshold: { ok: 500, warn: 1000, ouch: 3000 },
        activity: false,
        emoji: true,
        beep: true
    });
    
    jasmine.addReporter(jasmineConsoleReporter);
    jasmine.execute();
    
```

Y, por ultimo, agregar un nuevo campo en el la sección de `scripts` del `package.json` ejecutando archivo que acabamos de crear:
``` 
    "scripts": {
      ...
      "test:server:covegare": "node spec/specs.js",
      ...
    }
    
```

### Links:

* [GitHub - onury/jasmine-console-reporter: Progressive Console Reporter for Jasmine. Outputs detailed test results to the console, with beautiful layout and colors.](https://github.com/onury/jasmine-console-reporter)

### Comentarios:

## 0190. Configurando nuestro reporter [18785](https://platzi.com/clases/1542-pruebas-unitarias/18785-configurando-nuestro-reporter/)

### Descripción:


Los sistemas de reportes nos ayudan a navegar entre la información para saber cuánta cobertura tiene nuestro código con la red de seguridad que estamos programando.

Vamos a usar la librería [IstanbulJS](https://istanbul.js.org):
``` 
    npm install --save-dev nyc
    
```
``` 
    "scripts": {
      ...
      "test:server:coverage": "nyc node spec/specs.js",
      ...
    }
    
```

### Links:

* [Istanbul, a JavaScript test coverage tool.](https://istanbul.js.org)

### Comentarios:

* **mauxiandrade** (4) [595186](https://platzi.com/comentario/595186/) 

	“nyc”: {  
	“report-dir”: “./spec/istanbul/report”,  
	“temp-dir”: “./spec/istanbul”,  
	“reporter”: [ “text”, “text-summary”, “html” ],  
	“exclude”: [ “spec/**/ _" , "server/_.spec.js” ]  
	}

	* **Ale17273has** [595186] (1)

		Eso para que es?

	* **Usuario ESolutions** [595186] (1)

		en `"exclude"` te faltó el asterisco en `"server/*.spec.js"`

* **maoacrlearn** (2) [678489](https://platzi.com/comentario/678489/) 

	Creo que me quedo con JEST,
	
	Que dicen ustedes ?

	* **ricardocelis (Platzi)** [678489] (2)

		tambien me lllama mas la atencion JEST

	* **Elberth Jair Agreda Rosero** [678489] (2)

		Yo igual.

	* **David Behar** [678489] (1)

		A mi también me late más

* **Cristian De Blasis** (2) [560569](https://platzi.com/comentario/560569/) 

	Esta muy bueno el reporte de cobertura!.Quisiera saber si hay algun packete o tool que realice el test de time complexity.
	
	Muchas gracias

	* **Cristian Daniel Marquez Barrio** [560569] (2)

		Para temas relacionados con los tiempos de carga de un componente Angular, suelo utilizar (<https://zizzamia.github.io/perfume/>).
		
		Dentro de una prueba unitaria podrías utilizar el API de javascript y arrojar errores en el caso que un determinado método demore más tiempo del esperado. Te dejo el enlace <https://developer.mozilla.org/es/docs/Web/API/Performance/now>

* **Cristian De Blasis** (2) [57100](https://platzi.com/comentario/560569/) 
Esta muy bueno el reporte de cobertura!.Quisiera saber si hay algun packete o tool que realice el test de time complexity. Muchas gracias

	* **Cristian Daniel Marquez Barrio** [57100] (2)

		Para temas relacionados con los tiempos de carga de un componente Angular, suelo utilizar (<https://zizzamia.github.io/perfume/>).
		
		Dentro de una prueba unitaria podrías utilizar el API de javascript y arrojar errores en el caso que un determinado método demore más tiempo del esperado. Te dejo el enlace <https://developer.mozilla.org/es/docs/Web/API/Performance/now>

* **Damian Spizzirri** (1) [618486](https://platzi.com/comentario/618486/) 

	De donde sacaste esas configuracion para nyc?? Quiero encotrarla en la web istanbul pero no la encuentro. Sino parece que es magia jajaja.

	* **Cristian Daniel Marquez Barrio** [618486] (2)

		Las configuraciones del NYC las puedes encontrar en el github del proyecto: <https://github.com/istanbuljs/nyc>

* **ricardocelis (Platzi)** (1) [548049](https://platzi.com/comentario/548049/) 

	<https://istanbul.js.org>

## 0200. Pruebas en el servidor Verificando un status 200 en GET [18786](https://platzi.com/clases/1542-pruebas-unitarias/18786-pruebas-en-el-servidor-verificando-un-status-200-e/)

### Descripción:


Los “ **espías** ” son funciones de prueba que interceptan las llamadas a una función y recolectan datos sobre lo que sucede dentro ella: el número de veces que se llama una función, con qué parámetros y los valores de retorno de la función (o, si lanzó excepciones, los mensajes y la información del error).

Vamos a configurar un servidor exclusivo para ejecutar las pruebas unitarias de nuestra aplicación. Recuerda que NO vamos a probar la conexión con la base de datos, solo la interacción del servidor con la aplicación Front End. Por lo tanto, vamos a crear un servidor con la mínima configuración posible para hacer peticiones y probar que funcione correctamente.

Recuerda que usamos el método HTTP GET para solicitar datos de nuestra aplicación, no para borrar, actualizar oagregar información; solo visualizarla.

### Links:

* [Ejemplo "Hello World" de Express](https://expressjs.com/es/starter/hello-world.html)

* [morgan  -  npm](https://www.npmjs.com/package/morgan)

### Comentarios:

* **William Vega** (3) [560886](https://platzi.com/comentario/560886/) 

	Creo que esta clase se debió dividir en 3 clases diferentes. Está fantástica, pero me costó repetir el video más de 8 veces para poder reproducir cada paso, de entre los cuales, y en mi mera opinión, se obvian muchas cosas. Soy desarrollador de Angular desde hace cuatro años y de node desde hace dos y aún así me costó bastante trabajo el concepto de los spies, especialmente de las llamadas asíncronas y de la impersonificación de los callbacks, creo que para estudiantes con menos experiencia en node, sería muy bueno explicar estos temas con un poco más de detalle. Es respetuosamente una opinión.

	* **adrianrbp** [560886] (1)
El concepto de los spies es independiente del lenguaje de programación, siempre va a costar un poco más algunos conceptos nuevos, practicando haciendo tests se vuelve sencillo. También existen conceptos parecidos como mock, dummy, fake y stub que son test doubles.

	* **yisus_dev** [560886] (1)

		claro, lo que dice el compañero adrianbp es correcto. los spy es una manera de emular una funcion o un objeto para fingir un comportamiento. eso se aprende simplemente practicando, no es algo que se vea en los componentes de angular o en la programación normal de un proyecto sin pruebas. así que toca estudiar, leer, practicar y leer código de otros. saludos

* **ricardocelis (Platzi)** (3) [548050](https://platzi.com/comentario/548050/) 

	<https://expressjs.com/es/starter/hello-world.html>

## 0210. Pruebas en el servidor Probando el método GET y Reto con FindByID [18787](https://platzi.com/clases/1542-pruebas-unitarias/18787-pruebas-en-el-servidor-probando-el-metodo-get-y-re/)

### Descripción:


En la clase anterior probamos el código 200, lo que significa que todo está bien y nuestro servidor responde correctamente. En esta clase vamos a probar que nuestro servidor no funcione, nuestra prueba solo debe pasar si devuelve un error con el código 500, un error del servidor.

El reto de la clase es volver a probar el método get pero, esta vez, recibiendo parámetros. La lógica es casi la misma pero la ruta va a ser diferente y tenemos que cambiar algunos métodos como el `find` por el `findById`.

### Comentarios:

* **mauxiandrade** (3) [595328](https://platzi.com/comentario/595328/) 

	Yo lo hice de esta forma.
	``` 
	    it('200 and find pin by Id', (done) => {
	    			spyOn(Pins, 'findById').and.callFake((id, callBack) => {
	    				callBack(false, id);
	    			});
	    
	    			request.get('http://localhost:3000/api/1', (error, response, body) => {
	    				expect(response.statusCode).toBe(200);
	    				expect(error).toBe(null);
	    				expect(JSON.parse(response.body)).toEqual('1');
	    				done();
	    			});
	    		});```
	    
	    
	    Me encanta el curso por cierto.
	    
	    
	```

	* **Ale17273has** [595328] (1)

		Error and success
		``` 
		    < // GET findById
		        it("findById", done => {
		          spyOn(Pins, "findById").and.callFake((id, callBack) => {
		            callBack(false, id);
		          });
		    
		          request.get("http://localhost:3000/api/1", (error, response, body) => {
		            expect(response.statusCode).toBe(200);
		            expect(JSON.parse(response.body)).toEqual("1");
		            done();
		          });
		        });
		    
		         // GET findById error
		         it("findById", done => {
		          spyOn(Pins, "findById").and.callFake((id, callBack) => {
		            callBack(true, id);
		          });
		    
		          request.get("http://localhost:3000/api/1", (error, response, body) => {
		            expect(response.statusCode).toBe(500);
		            done();
		          });
		        });>
		    
		```

* **Jaime Quintero Rodríguez** (2) [551388](https://platzi.com/comentario/551388/) 

	Esta es mi solucion.
	``` 
	    // Get 200 FindById
	        it("200 and findById pin", done => {
	          const data = { id: 1 };
	          /* Dentro del Objeto Pins queremos espiar el metodo findById y ejecutamos nuestro propio metodo */
	          spyOn(Pins, "findById").and.callFake((id, callBack) => {
	            data.param = id;
	            callBack(false, data);
	          });
	      
	          request.get("http://localhost:3000/api/21312", (error, response, body) => {
	            expect(response.statusCode).toBe(200);
	            expect(error).toBe(null);
	            expect(JSON.parse(response.body)).toEqual({ id: 1, param: "21312" });
	            expect(JSON.parse(response.body).id).toEqual(1);
	            expect(JSON.parse(body).param).toEqual("21312");
	            done();
	          });
	        });
	    
	        //GET 500 FindById
	        it("500", done => {
	          const data = [{ id: 1 }];
	          /* Dentro del Objeto Pins queremos espiar el metodo find y ejecutamos nuestro propio metodo */
	          spyOn(Pins, "findById").and.callFake((id, callBack) => {
	            callBack(true, data);
	          });
	    
	          request.get("http://localhost:3000/api/21312", (error, response, body) => {
	            expect(response.statusCode).toBe(500);
	            done();
	          });
	        });
	    
	```

	* **William Vega** [551388] (4)

		Hola Wuolah, una pregunta, Qué pasa si hay más parámetros a una función a ser impersonada (faked)?, algo como:  
		data.params[‘id’] … quizá? Por cierto, gracias por el aporte. 😃

* **vladernn** (1) [1106377](https://platzi.com/comentario/1106377/) 

	```
	    <code>
	    it("200 and pinById", (done) => {
	        const data = [{ id: 1 }];
	        const id = 1;
	    
	        spyOn(Pins, "findById").and.callFake((id, callBack) => {
	          callBack(undefined, data);
	        });
	    
	        request.get("http://localhost:3000/api/1", (error, response, body) => {
	          expect(response.statusCode).toBe(200);
	          expect(JSON.parse(body)).toEqual([{ id: 1 }]);
	          done();
	        });
	      });
	    </code>
	    
	```

* **David Behar** (1) [1011337](https://platzi.com/comentario/1011337/) 

	Acá la solución del reto
	``` 
	      describe('GET custom pin', () => {
	        // GET 200
	        const data = [{id: 1}];
	        const elementId = '2132';
	    
	        it('should response with 200 and Get custom pin', (done) => {
	          spyOn(Pins, 'findById').and.callFake((id, callBack) => {
	            // callback = function(err, post)
	            expect(elementId).toEqual(id);
	            callBack(false, data); // error = false
	          });
	          request.get('http://localhost:3000/api/'+elementId, (error, response, body) => {
	            expect(response.statusCode).toBe(200);
	            expect(JSON.parse(response.body)).toEqual([{id: 1}]);
	            done();
	          });
	        });
	    
	    
	        // GET 500
	        it('Should return 500 when error', (done) =>{
	          spyOn(Pins, 'findById').and.callFake((id, callBack) => {
	            // callback = function(err, post)
	            callBack(true, data); // error = true
	          });
	          request.get('http://localhost:3000/api/'+elementId, (error, response, body) => {
	            expect(response.statusCode).toBe(500);
	            done();
	          });
	        });
	      });
	    
	```

* **David Behar** (1) [1011322](https://platzi.com/comentario/1011322/) 

	De dónde viene este callback?
	
	## Qué está llamando?
	``` 
	          spyOn(Pins, 'find').and.callFake((callBack) => {
	            callBack(true, data);
	          });
	    
	```

	* **vladernn** [1011322] (1)

		Según lo que yo entiendo es la función que devuelve en metodo find de Pins

* **Andrés Muñoz** (1) [675447](https://platzi.com/comentario/675447/) 

	```
	    describe("GET SINGLE PIN BY ID", () => {
	        // GET 200
	        it("should return 200 and find pin by id", done => {
	          const data = [{ _id: 1 }];
	          spyOn(pinsModel, "findById").and.callFake((id, callback) => {
	            callback(false, data);
	          });
	          request.get("http://localhost:3000/api/pin_id", (error, res, body) => {
	            expect(pinsModel.findById).toHaveBeenCalledWith('pin_id', jasmine.any(Function))
	            expect(res.statusCode).toBe(200);
	            expect(JSON.parse(res.body)).toEqual([{ _id: 1 }]);
	            done();
	          });
	        });
	    
	        // GET 500
	        it("should return 500", done => {
	          spyOn(pinsModel, "findById").and.callFake((id, callback) => {
	            callback(true, null);
	          });
	          request.get("http://localhost:3000/api/pin_id", (error, res, body) => {
	            expect(res.statusCode).toBe(500);
	            done();
	          });
	        });
	      });```
	    
	```

* **Damian Spizzirri** (1) [618581](https://platzi.com/comentario/618581/) 

	Como hago para validar el parametro que me llega por la url??

## 0220. Pruebas en el servidor Probando el método POST (request to server) [18788](https://platzi.com/clases/1542-pruebas-unitarias/18788-pruebas-en-el-servidor-probando-el-metodo-post-req/)

### Descripción:


Vamos a usar `axios`: una librería que nos ayuda a consultar y enviar datos a las URLs que le indiquemos con una sintaxis un poco diferente a la de la librería `request`. Podemos usarla, por ejemplo, para hacer consultas a nuestra propia aplicación para comprobar que obtenemos la información que esperamos.

Instalación de axios:
``` 
    npm install axios --save-dev
    
```

Vamos a probar el caso de éxito del método POST de nuestra API: la aplicación debe responder correctamente cuando los usuarios envían URLs de archivos PDF o páginas con código HTML común y corriente.

En este caso, vamos a utilizar datos “falsos” para correr las pruebas: en vez de descargar los recursos para consumir un PDFs o una páginas web, nosotros mismos vamos a escribir los datos con los que interactúa nuestro código para comprobar que la aplicación responde correctamente.

### Links:

* [axios  -  npm](https://www.npmjs.com/package/axios)

### Comentarios:

* **Jaime Quintero Rodríguez** (5) [552190](https://platzi.com/comentario/552190/) 

	En el callFake el primer parametro que recibe es Pin, por lo que si no lo pones da error el test con respuesta 500.
	
	spyOn(Pins, ‘create’).and.callFake((pin, callBack )=> {  
	callBack(false, {});  
	});```
	
	Tambien falta declarar
	
	var requestPromise = require(‘request-promise-native’);
	
	Creo que esta explicación se podría mejorar, es mas una demostración de sus conocimientos que una guía para aprender porque se hacen las cosas

* **mauxiandrade** (2) [602161](https://platzi.com/comentario/602161/) 

	Quiero hacer una prueba de un caso más complejo. tengo el la siguiente clase Trxs:
	``` 
	    const Mysql2Base = require("./Mysql2Base");
	    const TrxDetails = require("./../TrxDynamo");
	    const AuthorizationHelper = require("./../../helpers/authorization.helper");
	    
	    
	    classTrxsextendsMysql2Base{
	       constructor() {
	            super();
	            this.table = "trxs";
	            this.services_table = "servicios";
	       } 
	    
	       getAll(data){
	            returnnewPromise((resolve, reject) => {    
	            let query = 'some_query'
	                this.write(query).then( async queryResult => {
	                    try{             
	                        queryResult.forEach((element, idx, arr) => {
	                            queryResult[idx]["url"]= this.getCompleteUrl(element.idTrx, element.id_session);
	                            let trxDetail = new TrxDetails(element.idTrx);
	                            let getTrxDetail = await trxDetail.getTrxDetails();
	                            if(getTrxDetail.Count > 0 ){
	                               /*
	    				Codigo...
	    			   */
	                            }else{
	                                /*
	    				Codigo...
	    			   */
	                            }
	                        });
	    		    resolve(queryResult);          
	                    }catch(error){
	                        console.log("ERROR", error);
	                        reject(error);
	                    }    
	                }).catch(errorQuery => {
	                    reject(errorQuery);
	                });                   
	            }   
	       }
	    
	        getCompleteUrl(id, idSession) {
	            return'http://example.com' + AuthorizationHelper.generateAuthHeader(id, idSession);
	        }
	    
	    }
	    
	    module.exports = Trxs;
	    
	```
	
	La clase TrxDynamo (llamada TrxDetails en el codigo anterior) es así:
	``` 
	    const Trxs = require("./DYNAMODB/Trxs");
	    
	    classTrxDynamoextendsTrxs{
	        constructor(idTrx) {
	            super();
	            this.idTrx = idTrx;
	        }
	      
	        getTrxDetails() {
	            returnsuper.getTrxDetails(this.idTrx);
	        }
	    }
	    
	    module.exports = TrxDynamo;
	    
	```
	
	‘super.getTrxDetails()’ es un método de la clase Trxs (distinta a la primera) que es así:
	``` 
	    const DynamoBase = require("./DynamoBase");
	    
	    classTrxsextendsDynamoBase{
	    
	        constructor() {
	            super();
	            this.table = `tabla_trx_dynamo`;
	        }
	       
	        getTrxDetails(idTrx) {
	            returnnewPromise((resolve, reject) => {
	                let params = {
	                    TableName: this.table,
	                    KeyConditionExpression: "#idTrxs = :id",
	                    ExpressionAttributeNames: {
	                        "#idTrxs": "idTrxs",
	                    },
	                    ExpressionAttributeValues: {
	                        ":id": `${idTrx}`,
	      
	                    },
	                };
	    
	                super.executeQuery(params).then(saveResult => {
	                    console.log(saveResult);
	                    resolve(saveResult);
	                }).catch(errorSave => {
	                    console.log("No se pudo obtener los datos getTrxDetails");
	                    reject(errorSave);
	                });
	            });
	        }
	    
	    }
	    
	    module.exports = Trxs;
	    
	```
	
	En el spec tengo lo siguiente:
	``` 
	    const express = require('express');
	    const http = require('http');
	    const Trxs = require('./../models/MYSQL/Trxs');
	    const TrxDetails = require('./../models/DYNAMODB/Trxs');
	    
	    app.use(express.json());
	    app.set('port', 3000);
	    
	    describe('Transacciones', function() {
	    	let server;
	    	let trxs;
	    	let trxDetail;
	    	let data = {
	    		idServicio: '468',
	    		limit: '10'
	    	};
	    	let exampleObject = [
	    		{
	    			idTrx: 'id1',
	    			estado: 'COMPLETADA',
	    			source: 'WebpayPST'
	    		},
	    		{
	    			idTrx: 'id2',
	    			estado: 'PENDING',
	    			source: 'WebpayPST'
	    		}
	    	];
	    
	    	beforeAll(() => {
	    		server = http.createServer(app);
	    		server.listen(3000);
	    		trxs = new Trxs();
	    		trxDetail = new TrxDetails('id1');
	    		spyOn(trxs, 'write').and.returnValue(Promise.resolve(exampleObject));
	    		spyOn(trxDetail, 'getTrxDetails').and.returnValue(Promise.resolve({}));
	    		trxs.getAll(data);
	    	});
	    
	    	afterAll(() => 
	    		server.close();
	    	});
	    	it('debe escribir en trx', function(done) {
	    		expect(trxs.write).toHaveBeenCalled();
	    		done();
	    	});
	    	it('debe obtener detalles de trx', function(done) {
	    		expect(trxDetail.getTrxDetails).toHaveBeenCalled();
	    		done();
	    	});
	    	it('debe retornar algo', (done) => {
	    		expect(trxs.getAll).toBeTruthy();
	    		done();
	    	});
	    });
	    
	    
	```
	
	Al método ‘getCompleteUrl’ puedo acceder mediante spyOn porque es de la misma clase. Y el método ‘write’ pertenece a la clase Mysql2Base que está inicializada en el constructor con el super(), por lo tanto no tengo problema tampoco. Sin embargo, quiero aplicar spyOn al método ‘getTrxDetails’ de la clase Trxs (en el spec lo llamo TrxDetails) que está definido en la segunda clase Trxs que mencioné, es decir, desde getAll() se llama a getTrxDetails y de ahí se llama al getTrxDetails que quiero espiar y no funciona. Obtengo este resultado:
	
	  1. Transacciones  
	getTrxDetails id1  
	. ✔ debe escribir en trx (22ms)  
	F ✖ debe obtener detalles de trx (1 failure) (2ms)  
	. ✔ debe retornar algo (1ms)  
	Failed Specs:
	
	  2. Transacciones : debe obtener detalles de trx  
	Expected spy getTrxDetails to have been called.  
	at <Jasmine>  
	at UserContext.<anonymous> /home/mauxi/Documentos/ebs-api-dashboard/spec/server.spec.js:64:35  
	at <Jasmine>
	
	
	
	
	¿Cómo manejo este casos?

	* **mauxiandrade** [602161] (3)

		Conseguí la respuesta aquí <https://stackoverflow.com/questions/31364930/jasmine-how-to-spyon-instance-methods/31365042#31365042?newreg=778be54021bc4785a1b7a8c157568c59>  
		Sería un buen caso para incluir en el curso.

* **mario-salinas** (2) [573709](https://platzi.com/comentario/573709/) 

	Yo hice el ejercicio con request pero no entendí para que era el objeto post
	``` 
	    it("200", done => {
	          spyOn(Pins, "create").and.callFake((pin, callBack) => {
	            callBack(false, {});
	          });
	          spyOn(requestPromise, "get").and.returnValue(
	            Promise.resolve(
	              '<title>Platzi</title><meta name="description" content="Platzi description">'
	            )
	          );
	    
	          const assets = [{ url: "http://platzi.com" }];
	    
	          request.post(
	            "http://localhost:3000/api",
	            {
	              json: {
	                title: "title",
	                author: "author",
	                description: "description",
	                assets
	              }
	            },
	            (error, response, body) => {
	              expect(response.statusCode).toBe(200);
	              done();
	            }
	          );
	        });```
	```

	* **Yilmer Ramiro Guativa Rincón** [573709] (1)

		Era para colocar en cambio de objeto json en el metodo post

* **mauxiandrade** (2) [60202](https://platzi.com/comentario/602161/) 
Quiero hacer una prueba de un caso más complejo. tengo el la siguiente clase Trxs: const Mysql2Base = require("./Mysql2Base"); cons...

	* **mauxiandrade** [60202] (3)

		Conseguí la respuesta aquí <https://stackoverflow.com/questions/31364930/jasmine-how-to-spyon-instance-methods/31365042#31365042?newreg=778be54021bc4785a1b7a8c157568c59>  
		Sería un buen caso para incluir en el curso.

## 0230. Pruebas en el servidor Probando el método POST (request to PDF) [18789](https://platzi.com/clases/1542-pruebas-unitarias/18789-pruebas-en-el-servidor-probando-el-metodo-post-req/)

### Descripción:


### Comentarios:

* **Damian Spizzirri** (2) [618718](https://platzi.com/comentario/618718/) 

	Hola, quiero testear que de error este get requestPromise.get({ url: asset.url });
	
	Lo estoy haciendo asi, pero no anda, alguno me puede dar una mano??
	``` 
	        it("500", done => {
	          const pins = { title: "Platzi", author: "Platzi", description: "Platzi rules", percentage: 0, tags: [],assets: []};
	    
	          spyOn(requestPromise, "get").and.returnValue(        
	    		Promise.reject(new Error("Ocurrio un error"))
	          );
	    
	          const assets = [{ url: "http://platzi.com" }];
	          axios
	            .post("http://localhost:3000/api", {
	              title: "title",
	              author: "author",
	              description: "description",
	              assets
	            })
	              .catch(err => {
	              console.log(err);
	              expect(err.response.status).toBe(500);
	              done();
	            });
	        });
	    
	    
	```

	* **Ale17273has** [618718] (1)

		Que error sale

	* **mbc** [618718] (1)

		yo lo hice de esta manera y salio
		``` 
		       it('500 PDF', done => {
		                spyOn(Pins, 'create').and.callFake((pins, callBack) => {
		                    callBack(false, {});
		                });
		    
		                spyOn(requestPromise, "get").and.returnValue(        
		                   
		                );
		    
		                const assets = [{ url: 'http://platzi.com' }];
		          
		                axios.post('http://localhost:3000/api', { title: 'title', author: 'author', description: 'description', assets })
		                    .catch(error => {
		                        expect(error.response.status).toBe(500);
		                        done()
		                    })
		    
		            })
		    
		```

* **Byron Mesias Cueva Cabrera** (1) [903777](https://platzi.com/comentario/903777/) 
	
	![reto.jpg](https://static.platzi.com/media/user_upload/reto-53ade689-5120-4ee8-a322-323c65151bee.jpg)
	
	Pruebas realizadas hasta el 97%, solo me falta el catch de la función getMetadataFromAssets

* **nikosantis** (1) [890796](https://platzi.com/comentario/890796/) 

	Lo hice así:
	
	usando el error.response.status
	``` 
	    // 500
	        it('should return 500', done => {
	          spyOn(Pins, 'create').and.callFake((pins, callBack) => {
	            callBack(true, {})
	          })
	    
	          const assets = [{ url: 'http://nikolas.com' }]
	    
	          axios.post(
	            'http://localhost:3000/api',
	            { title: 'title', author: 'author', description: 'description', assets })
	            .catch(error => {
	              expect(error.response.status).toBe(500)
	              done()
	            })
	        })```
	    
	```

* **mario-salinas** (1) [573697](https://platzi.com/comentario/573697/) 

	Les dejo la manera de hacer las petición con request
	``` 
	    it("200 PDF", done => {
	          spyOn(Pins, "create").and.callFake((pins, callBack) => {
	            callBack(false, {});
	          });
	    
	          const assets = [{ url: "http://platzi.pdf" }];
	    
	          request.post(
	            "http://localhost:3000/api",
	            {
	              json: {
	                title: "title",
	                author: "author",
	                description: "description",
	                assets
	              }
	            },
	            (error, response, body) => {
	              expect(response.statusCode).toBe(200);
	              done();
	            }
	          );
	        });```
	```

* **Byron Mesias Cueva Cabrera** (1) [77409](https://platzi.com/comentario/903773/) 
Profe realice las pruebas hasta el 97% ya esta correcto, pero me falta la parte del catch de la promesa getMetadataFromAssets, no se com...

# Probando Angular apps con Jasmine [3764]

## 0240. Tipos de pruebas [18790](https://platzi.com/clases/1542-pruebas-unitarias/18790-tipos-de-pruebas/)

### Descripción:


Existen cinco tipos de pruebas, las cuales son:

* **Unitarias:** es una forma de comprobar el correcto funcionamiento de una unidad de código.
* **Integración** : son aquellas que se realizan en el ámbito del desarrollo de software una vez que se han aprobado las pruebas unitarias y lo que prueban es que todos los elementos unitarios que componen el software, funcionan juntos correctamente probándolos en grupo.
* **Funcionales:** es una prueba de tipo caja negra basada en la ejecución, revisión y retroalimentación de las funcionalidades previamente diseñadas para el software.
* **Carga/estrés:** la prueba de carga prueba de rendimiento utilizado para evaluar cómo actúa el sistema con una carga variable de usuarios pero dentro de los niveles esperados de la aplicación. Una prueba de estrés evalúa el sistema sometiéndolo a una carga creciente hasta que este falle.
* **Aceptación:** pertenecen a las últimas etapas previas a la liberación en firme de versiones nuevas a fin de determinar si cumplen con las necesidades y/o requerimientos de las empresas y sus usuarios.



### Comentarios:

* **Yilmer Ramiro Guativa Rincón** (1) [1084468](https://platzi.com/comentario/1084468/) 

	Este un recurso, es un libro gratuito de TDD (Test Driver Development)  
	<https://uniwebsidad.com/libros/tdd?from=librosweb>

## 0250. Pruebas en el frontend Probando el componente principal (App) [18822](https://platzi.com/clases/1542-pruebas-unitarias/18822-pruebas-en-el-frontend-probando-el-componente-prin/)

### Descripción:


Vamos a crear algunas pruebas para nuestro componente principal en el frontend: un conjunto de archivos que encontramos en la carpeta `src/app`.

El archivo `app.component.ts` se encarga de definir la lógica de nuestra aplicación. Por ahora, no tenemos nada, solo la referencia a otros componentes con tareas muy concretas que vamos a ir probando en las siguientes clases:

* `app.component.html`: Se encarga de renderizar el componente de navegación, `router-outlet`.
* `app.component.spec.ts`: Tiene todas las pruebas del componente App. Algunas de las pruebas por defecto no son muy útiles en este momento y vamos a reemplazarlas por algunas pruebas en el archivo `app.component.html` para confirmar que se incluye el componente `render-oulet` y la navegación funciona correctamente.



### Comentarios:

* **Jaume Parrot Altisent** (3) [726956](https://platzi.com/comentario/726956/) 

	Buenas, he hecho un copy&paste del código de ejemplo, pero me aparece este error:  
	![Captura de pantalla 2019-09-08 a las 20.57.15.png](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-09-08%20a%20las%2020.57.15-e43754b1-0685-4741-8a17-fe90c73acb45.jpg)  
	No se porque no encuentra la función ‘debugElement’.  
	Un saludo.

	* **iMade** [726956] (0)

		Hola! Pudiste resolver este problema…?? Actualmente me sale el mismo problema.

* **Daniel Puerta** (3) [625931](https://platzi.com/comentario/625931/) 

	Si al ejecutar ng test les sale el siguiente error:
	``` 
	    Data path “.builders['app-shell']” should have required property'class'
	    
	```
	
	Lo que deben hacer es cambiar la versión de “@angular-devkit/build-angular” a la “0.13.4” en el package.json

	* **iMade** [625931] (0)

		Gracias! Me ayudaste

	* **David Behar** [625931] (2)

		Pues yo no puedo ejecutar ng 😕

	* **sebastianandrada** [625931] (3)

		David tienes instalado angular en tu pc?

	* **David Behar** [625931] (1)

		Am, me parece que no, jeje 😅

* **adrianrbp** (1) [678525](https://platzi.com/comentario/678525/) 
Creo que las clases de acá en adelante pueden servir para cualquier frontEnd, incluyendo mobile, traduciendo cosas. Pero no sé nada de angular :D jaja, espero agregen contenido similar en otros cursos. Vuelvo cuando aprenda angular :p

	* **maoacrlearn** [678525] (2)

		Hola !, angular es el unico curso que me falta para copletar la carrera de** Arquitectura Frontend **, pienso que si bien primero haces el curso de Angular para enteder mejor los ejercicios, lo importantes es que prestes atencion en el comportamiento de los diferentes usos de Jasmine y podras avanzar sin saber angular.

	* **adrianrbp** [678525] (1)

		Vi un poco de angular, más de react, si que estaba buscando el uso Jasmine para luego practicar BDD que es similar a TDD.
		
		Tu comentario me ha hecho re-pensar y continuar el curso sin saber tanto angular 😄, mil gracias!!, igual iré un poco en paralelo con el curso de angular para tenerlo de referencia.

## 0260. Configurando los ciclos de vida [18823](https://platzi.com/clases/1542-pruebas-unitarias/18823-configurando-los-ciclos-de-vida/)

### Descripción:


Vamos a probar el objeto de configuración de las rutas de nuestra aplicación, el archivo `app.routing.module.ts`. Debemos exportar la variable `routes` con la palabra reservada `export const routes ...` para probarla desde nuestro nuevo archivo de pruebas: `app.routing.module.spec.ts`.

Recuerda que podemos reemplazar la función `describe` por `fdescribe` para solo ejecutar y probar esta parte de nuestra aplicación. Además, tenemos disponibles 4 nuevos módulos para configurar variables o código especial antes y después de la ejecución de cada prueba o de la totalidad de ellas: las funciones `beforeAll()`, `beforeEach`, `afterAll()` y `afterEach()`.

### Comentarios:

* **Yilmer Ramiro Guativa Rincón** (1) [1090688](https://platzi.com/comentario/1090688/) 

	me sale el siguiente error
	``` 
	    hasno exported member 'routes'
	    
	```

## 0270. Creando las pruebas del formulario Configuración [18835](https://platzi.com/clases/1542-pruebas-unitarias/18835-creando-las-pruebas-del-formulario-configuracion/)

### Descripción:


### Comentarios:

* **Andrés Cerón** (5) [548650](https://platzi.com/comentario/548650/) 

	Con Angular haciendo Unit Testing yo he escrito testeos haciendo SpyOn al service y un returnValue(dummyData).  
	También he otra visto otra manera que es haciendo un con httpMock.expectOne y despues .flush(dummyData);  
	Y en muchas partes también he visto tu manera que es hacer stubs, entonces ahora a mi pregunta.  
	Como o cuándo se debería usar qué o cuál es la forma “correcta”?  
	Gracias!

	* **Cristian Daniel Marquez Barrio** [548650] (6)

		Para este tipo de cosas mi regla es la siguiente:
		
		  1. Creo Stubs que cumplan con las condiciones iniciales del componente que voy a probar. Es decir, un stub que permita cumplir con las condiciones mínimas para instanciar el componente (Ejecutar el constructor y los ciclos de vida iniciales del componente).
		  2. Los SpyOn los utilizo para los caminos alternos, por ejemplo. Una vez creada la instancia del componente, creando espias puedo modificar la respuesta del servicio y ejecutar un resolve o un reject dependiendo de las lineas de código que quiera ejecutar.
		
		
		
		Saludos, espero te sirva la respuesta.

* **Damian Spizzirri** (4) [618832](https://platzi.com/comentario/618832/) 

	Yo lo que suelo hacer es crear un espia y modificar el comportamiento para que me devuelva un true, false, etc. Pero me parece que esto de los Stub es mejor.

* **Andrés Cerón** (3) [56095](https://platzi.com/comentario/548650/) 
Con Angular haciendo Unit Testing yo he escrito testeos haciendo SpyOn al service y un returnValue(dummyData). También he otra visto otra...

	* **Cristian Daniel Marquez Barrio** [56095] (6)

		Para este tipo de cosas mi regla es la siguiente:
		
		  1. Creo Stubs que cumplan con las condiciones iniciales del componente que voy a probar. Es decir, un stub que permita cumplir con las condiciones mínimas para instanciar el componente (Ejecutar el constructor y los ciclos de vida iniciales del componente).
		  2. Los SpyOn los utilizo para los caminos alternos, por ejemplo. Una vez creada la instancia del componente, creando espias puedo modificar la respuesta del servicio y ejecutar un resolve o un reject dependiendo de las lineas de código que quiera ejecutar.
		
		
		
		Saludos, espero te sirva la respuesta.

* **sergiocelisleon** (1) [981902](https://platzi.com/comentario/981902/) 

	alguien sabe como solventar este error?
	``` 
	    this.formFilter = this.formBuider.group({
	          operativeAgent: [[], []],
	          actualStatus: [[], []],
	          entryType: [[], []],
	          maintenanceOrigin: [[], []],
	          penaltyType: [[], []],
	          color: [[], []],
	          consecutive: ['', [Validators.maxLength(100), Validators.pattern('^[a-zA-Z0-9 ,]*$')]],
	          area: [[], []],
	          subarea: [[], []],
	          substation: [[], []],
	          elementType: [[], []],
	          element: [[], []],
	          scheduledStartDate: ['', [this.generalService.validateDatesReactive('scheduledStartDate', 'scheduledEndDate')]],
	          scheduledEndDate: ['', [this.generalService.validateDatesReactive('scheduledStartDate', 'scheduledEndDate')]],
	          startWeek: ['', []],
	          endWeek: ['', []],
	          carga: ['', []]
	        });
	    
	```
	
	Error: There is no FormControl instance attached to form control element with name: ‘scheduledStartDate’

## 0280. Creando las pruebas necesarias para un formulario. (Primeras pruebas) [18824](https://platzi.com/clases/1542-pruebas-unitarias/18824-creando-las-pruebas-necesarias-para-un-formulario-/)

### Descripción:


### Comentarios:

* **adrianrbp** (1) [682396](https://platzi.com/comentario/682396/) 
Interesante usar las keys del objeto y index del array para validar presencia explicita de objetos. Había visto que en los arrays se contaba la longitud para validar la presencia de nuevos datos.

## 0290. Probando el caso de exito al guardar un elemento en el servidor. [18825](https://platzi.com/clases/1542-pruebas-unitarias/18825-probando-el-caso-de-exito-al-guardar-un-elemento-e/)

### Descripción:


### Comentarios:

* **yisus_dev** (1) [1027322](https://platzi.com/comentario/1027322/) 

	¿qué es un casteo? ¿por qué en Jasmine no hablan de eso?
	
	Me gustaríua saber más de eso, porque en internet no es que le den mucha importancia, pero veo que es muy útil.

	* **Diego Alexander Forero Higuera (Platzi)** [1027322] (1)

		El casteo de datos consiste en convertir un tipo de dato en otro, por ejemplo si tienes un string con el texto “2020” puedes hacer un casteo a entero y quedaría 2020. No todos los datos se pueden castear si intentas convertir un string “hola” a entero va a lanzar un error.

* **Damian Spizzirri** (1) [618862](https://platzi.com/comentario/618862/) 

	A veces se me queda la pantalla de navegador en blanco y no me carga la pantalla de Jasmine, que puede ser? Y se me queda con un cartel similar a este en la consola
	
	**17 06 2019 20:28:43.538:INFO [Chrome 75.0.3770 (Linux 0.0.0)]: Connected on socket _9Ym5CWQzLZKN7buAAAA with id 91918410**

	* **Damian Spizzirri** [618862] (2)

		Si alguno le sirve, ya encontre el problema que al menos tenia yo,
		
		tenia mal este import
		
		Es asi --> import { NO_ERRORS_SCHEMA, CUSTOM_ELEMENTS_SCHEMA } from “@angular/core”;
		
		Pero yo lo tenia asi --> import { NO_ERRORS_SCHEMA, CUSTOM_ELEMENTS_SCHEMA } from “@angular/compiler/src/core”;
		
		Vaya uno a saber que tiene que ver, pero cambie eso y empezo a funcionar.

## 0300. Trabajando con event emitters [18826](https://platzi.com/clases/1542-pruebas-unitarias/18826-trabajando-con-event-emitters/)

### Descripción:


No solo podemos probar nuestros componentes personalizados con la ayuda de Angular (o cualquier otra herramienta por el estilo); también podemos probar los elementos estándares de HTML, por ejemplo, para confirmar que una etiqueta tiene el título que correcto.

Además, vamos a usar el comando `ng test --codeCovegare` para tener una mejor visualización de nuestro reporte.

### Links:

* [Angular](https://angular.io/api/platform-browser/By)

### Comentarios:

* **iMade** (4) [979552](https://platzi.com/comentario/979552/) 

	La parte del test al Output fue poco clara.

* **yisus_dev** (1) [1027180](https://platzi.com/comentario/1027180/) 

	osea esta parte para poder entenderla es necesario tener una buena base de Angular! es importante.

## 0310. Testeando ngZone y navegación. [18836](https://platzi.com/clases/1542-pruebas-unitarias/18836-testeando-ngzone-y-navegacion/)

### Descripción:


### Comentarios:

* **Gabriel Leonardo Pinto Pineda** (2) [706016](https://platzi.com/comentario/706016/) 

	Así implementé los tests sobre el componente “Action”
	``` 
	    it('should openLink', () => {
	        const event = new MouseEvent('click');
	        const eventCall = spyOn(event, 'preventDefault').and.callFake(() => {});
	        const dismiss = spyOn((<any>component).bottomSheetRef, 'dismiss');
	        const resolveActionObserver = spyOn(
	          (<any>component).pinsService,
	          'resolveActionObserver'
	        );
	        component.openLink(event, '');
	        expect(eventCall).toHaveBeenCalled();
	        expect(dismiss).toHaveBeenCalled();
	        expect(resolveActionObserver).toHaveBeenCalled();
	      });
	    
	```

* **vladernn** (1) [1118040](https://platzi.com/comentario/1118040/) 

	```
	    import { async, ComponentFixture, TestBed } from "@angular/core/testing";
	    
	    import { ActionsComponent } from "./actions.component";
	    import { MatBottomSheetRef } from "@angular/material";
	    import { PinsService } from "../pins/pins.service";
	    import { NO_ERRORS_SCHEMA, CUSTOM_ELEMENTS_SCHEMA } from "@angular/core";
	    
	    export class MatBottomSheetRefSTUB {
	      dismiss() {}
	    }
	    
	    export class PinsServiceSTUB {
	      resolveActionObserver(action) {}
	    }
	    
	    fdescribe("ActionsComponent", () => {
	      let component: ActionsComponent;
	      let fixture: ComponentFixture<ActionsComponent>;
	    
	      beforeEach(async(() => {
	        TestBed.configureTestingModule({
	          declarations: [ActionsComponent],
	          providers: [
	            { provide: MatBottomSheetRef, useClass: MatBottomSheetRefSTUB },
	            { provide: PinsService, useClass: PinsServiceSTUB },
	          ],
	          schemas: [NO_ERRORS_SCHEMA, CUSTOM_ELEMENTS_SCHEMA],
	        }).compileComponents();
	      }));
	    
	      beforeEach(() => {
	        fixture = TestBed.createComponent(ActionsComponent);
	        component = fixture.componentInstance;
	        fixture.detectChanges();
	      });
	    
	      it("should create", () => {
	        expect(component).toBeTruthy();
	      });
	    
	      it("preventDefault should be called", () => {
	        const mouseEvent = new MouseEvent("click");
	        const mouseEventSpy = spyOn(
	          mouseEvent,
	          "preventDefault"
	        ).and.callFake(() => {});
	        component.openLink(mouseEvent, "send");
	        expect(mouseEventSpy).toHaveBeenCalled();
	      });
	    
	      it("dismiss should be called", () => {
	        const mouseEvent = new MouseEvent("click");
	        spyOn(mouseEvent, "preventDefault").and.callFake(() => {});
	        const bottomSheetRefSpy = spyOn((<any>component).bottomSheetRef, "dismiss");
	        component.openLink(mouseEvent, "send");
	        expect(bottomSheetRefSpy).toHaveBeenCalled();
	      });
	    
	      it("dismiss should be called", () => {
	        const mouseEvent = new MouseEvent("click");
	        spyOn(mouseEvent, "preventDefault").and.callFake(() => {});
	        const pinsServiceSpy = spyOn(
	          (<any>component).pinsService,
	          "resolveActionObserver"
	        );
	        component.openLink(mouseEvent, "send");
	        expect(pinsServiceSpy).toHaveBeenCalled();
	      });
	    });
	    
	```

* **vladernn** (1) [1118008](https://platzi.com/comentario/1118008/) 

	```
	    it("edit mode should be true", () => {
	        const verifyEditMode = spyOn(component, "verifyEditMode").and.callThrough();
	    
	        fixture.ngZone.run(() => {
	          (<any>component).router.navigate(['app/add']); 
	          fixture.whenStable().then(() => {
	            expect(component.editMode).toBe(true);
	            expect(verifyEditMode).toHaveBeenCalled();
	          });
	        });
	      });
	    
	```

* **Damian Spizzirri** (1) [623778](https://platzi.com/comentario/623778/) 

	Configure asi para testear la ruta ‘/app/add’
	``` 
	    declarations: [LayoutComponent, FormComponent],
	          providers: [{ provide: MatBottomSheet, useClass: MatBottomSheetStub }],
	          imports: [RouterTestingModule.withRoutes([
	            { path: '', component: LayoutComponent },
	            {
	              path: "app", component: LayoutComponent,
	              children: [{ path: "add", component: FormComponent }]
	            },
	          ])],
	          schemas: [NO_ERRORS_SCHEMA, CUSTOM_ELEMENTS_SCHEMA]
	    
	```
	
	Y agregue este import  
	import { FormComponent } from ‘…/form/form.component’;
	
	Pero me da este error  
	Error: StaticInjectorError(DynamicTestModule)[FormComponent -> FormBuilder]:
	
	Que me falta hacer?

* **Damian Spizzirri** (1) [623746](https://platzi.com/comentario/623746/) 

	Que es ese (<any>component) que pones??

* **Damian Spizzirri** (1) [623733](https://platzi.com/comentario/623733/) 

	No me queda claro porque forzas la prueba. A caso no deberia correr y ya? Porque no te corren y tenes que forzarlo?

	* **Ronnel Moises Matallana Machado** [623733] (1)

		Es que como forzó las otras pruebas solo corren las forzadas,  
		en caso de no forzar ninguna, entonces corren todas, pero como el angular-cli te crea spec a todos los componentes por defecto, muchos te van a tirar errores o warning, entonces para evitar los errores y que sea mas limpio para el entendimiento de los demás el los ocultó forzando los que quiere correr solamente.

## 0320. Configurando el TestBed de el componente PINs [18827](https://platzi.com/clases/1542-pruebas-unitarias/18827-configurando-el-testbed-de-el-componente-pins/)

### Descripción:


### Comentarios:

* **Jessie Buckland Pérez** (1) [78041](https://platzi.com/comentario/914215/) 
¿En lugar de utilizar el JSON.* y los dos métodos para PINS podriamos utilizar …PINS? Es decir, en lugar de JSON usar la desestructuració...

## 0330. Creando un espia sobre el objecto window [18828](https://platzi.com/clases/1542-pruebas-unitarias/18828-creando-un-espia-sobre-el-objecto-window/)

### Descripción:


### Comentarios:

# Pruebas de integración de Angular apps con Jasmine [3769]

## 0340. Ejecutando funciones a través de eventos en el template [18829](https://platzi.com/clases/1542-pruebas-unitarias/18829-ejecutando-funciones-a-traves-de-eventos-en-el-tem/)

### Descripción:


Las pruebas de integración son pruebas que dependen de otras clases para obtener resultados en nuestros componentes.

Vamos a ejecutar algunas de estas pruebas en nuestros templates pero dependiendo de los resultados de los componentes marcados como clases. Además, vamos a probar algunos de nuestros servicios con la herramienta de simulación de eventos HTTP que nos provee el equipo de Angular.

### Comentarios:

## 0350. Probando la navegación [18837](https://platzi.com/clases/1542-pruebas-unitarias/18837-probando-la-navegacion/)

### Descripción:


### Comentarios:

## 0360. Probando servicios con HTTP [18830](https://platzi.com/clases/1542-pruebas-unitarias/18830-probando-servicios-con-http/)

### Descripción:


### Comentarios:

* **Damian Spizzirri** (1) [625247](https://platzi.com/comentario/625247/) 

	En que parte del codigo le estoy diciendo que si la ruta es /test me tiene que retornar “testing”, no entendi eso.
	``` 
	      service.get('/test').subscribe(response => {
	        console.log(response);
	        expect(response).toBe(result);
	      });
	```

* **Damian Spizzirri** (1) [625246](https://platzi.com/comentario/625246/) 

	No entendi el final, para que sirve el req.flush??

	* **Luis José Leopardi Velásquez** [625246] (2)

		Con el flush básicamente estas entregando los valores que has mockeado como respuesta del servidor

## 0370. Completando las pruebas del servicio HTTP [18838](https://platzi.com/clases/1542-pruebas-unitarias/18838-completando-las-pruebas-del-servicio-http/)

### Descripción:


### Comentarios:

## 0380. Cierre del curso [18831](https://platzi.com/clases/1542-pruebas-unitarias/18831-cierre-del-curso/)

### Descripción:


!Felicitaciones por terminar el Curso de Unit Testing con Jasmine!

En este curso aprendimos a trabajar con Jasmine a nivel profesional: integramos servicios, componentes y templates para detectar errores de forma automática ya que se nos pueden escapar cuando revisamos nuestro código a simple vista.

Vamos a repasar algunas buenas prácticas para trabajar en Unit Testing:

* Usar un sistema de control versiones como [GIT](https://git-scm.com) para facilitar la revisión de código con nuestros equipos y configurar herramientas de buenas prácticas (como linters y herramientas de tipado).
* Crear archivos separados con el _stub_ de una clase específica en vez de crear _stubs_ en cada uno de nuestros archivos de pruebas.
* Tu fuente de información siempre debe ser la página oficial de las herramientas que estas utilizando, en este caso, a la documentación oficial de Jasmine: [jasmine.github.io](https://jasmine.github.io).



Recuerda dejar todas tus dudas y comentarios en el sistema de discusiones de Platzi o contactando a nuestro profe por sus redes sociales ????.

### Links:

* [Jasmine Documentation](https://jasmine.github.io)

### Comentarios:

* **francves17** (3) [722471](https://platzi.com/comentario/722471/) 

	Existe algún repositorio con el código del proyecto y las pruebas realizadas en el curso?

	* **David Behar** [722471] (1)

		Sí, se encuentra acá: <https://github.com/xthecapx/mean>

* **Jaime Quintero Rodríguez** (1) [562181](https://platzi.com/comentario/562181/) 

	Estoy intentando hacer las pruebas de este codigo, pero por mas que intento no consigo solucionarlo. Si alguien puede ayudarme
	``` 
	    import { Component } from '@angular/core';
	    
	    import { Platform } from '@ionic/angular';
	    import { SplashScreen } from '@ionic-native/splash-screen/ngx';
	    import { StatusBar } from '@ionic-native/status-bar/ngx';
	    import { HttpClient } from '@angular/common/http';
	    import { StorageService } from './services/storage.service';
	    
	    @Component({
	      selector: 'app-root',
	      templateUrl: 'app.component.html'
	    })
	    export class AppComponent {
	      constructor(
	        private platform: Platform,
	        private splashScreen: SplashScreen,
	        private statusBar: StatusBar,
	        private httpClient: HttpClient,
	        private storageService: StorageService,
	      ) {
	        this.initializeApp();
	      }
	    
	      initializeApp() {
	        this.platform.ready().then(() => {
	          this.httpClient.get('https://s3-eu-west-1.amazonaws.com/wuolah-public/config/languages/lang/es_ES/config.json').toPromise().then(
	            (strings) => {
	              this.storageService.write('locale', strings);
	              this.statusBar.styleDefault();
	              this.splashScreen.hide();
	            }
	          );
	        });
	      }
	    }
	    
	```

	* **Diego Alexander Forero Higuera (Platzi)** [562181] (1)

		Cuéntanos que problema te da para poder ayudarte.

	* **Cristian Daniel Marquez Barrio** [562181] (1)

		Te recomiendo comenzar creando stubs para cada uno de los servicios que estas inyectando en el constructor y centrarte en completar el flujo principal de `initializeApp`.
		
		  1. El servicio `platform` debe tener un método `ready()` que retorne un `Promise.resolve('data')`;
		  2. Puedes utilizar el `HttpClientTestingModule` para resolver el `get`
		  3. El `storageService` debe tener un método `write`
		  4. El `statusBar` debe tener un método `styleDefault`
		  5. El `splashScreen` debe tener un método `hide`
		  6. En la primera prueba lo que debes esperar es que los métodos `write,`styleDefault`y`hide` sean llamados al crear la instancia del componente.
		
		

	* **Jaime Quintero Rodríguez** [562181] (1)

		Este es mi spec.ts. No me identifica Platfom.ready() como funcion y nisiquiera estoy realizando ninguna prueba
		``` 
		    <import { NO_ERRORS_SCHEMA, CUSTOM_ELEMENTS_SCHEMA } from '@angular/core';
		    import { TestBed, async, ComponentFixture } from '@angular/core/testing';
		    
		    import { Platform } from '@ionic/angular';
		    import { SplashScreen } from '@ionic-native/splash-screen/ngx';
		    import { StatusBar } from '@ionic-native/status-bar/ngx';
		    
		    import { AppComponent } from './app.component';
		    import { StorageService } from './services/storage.service';
		    import { HttpClientTestingModule, HttpTestingController } from '@angular/common/http/testing'
		    
		    
		    class PlatformStub {
		      ready(){
		        const data = {};
		        Promise.resolve();
		      }
		    }
		    
		    class SplashScreenStub {
		      hide() {}
		    }
		    
		    class StatusBarStub {
		      styleDefault(){}
		    }
		    
		    class StorageServiceStub {
		      write(){}
		    }
		    
		    
		    fdescribe('AppComponent', () => {
		    
		      letcomponent: AppComponent;
		      letfixture: ComponentFixture<AppComponent>;
		    
		      beforeEach(async(() => {
		    
		        TestBed.configureTestingModule({
		          declarations: [AppComponent],
		          schemas: [NO_ERRORS_SCHEMA, CUSTOM_ELEMENTS_SCHEMA],
		          providers: [
		            { provide: StatusBar, useValue: StatusBarStub },
		            { provide: SplashScreen, useValue: SplashScreenStub },
		            { provide: Platform, useValue: PlatformStub },
		            { provide: StorageService, useValue: StorageServiceStub }
		          ],
		          imports: [HttpClientTestingModule]
		        }).compileComponents();
		      }));
		    
		      beforeEach(() => {
		        fixture = TestBed.createComponent(AppComponent);
		        component = fixture.componentInstance;
		        fixture.detectChanges();
		      });
		    
		      it('should create the app', () => {
		        const fixture = TestBed.createComponent(AppComponent);
		        const app = fixture.debugElement.componentInstance;
		        expect(app).toBeTruthy();
		      });
		    
		      // describe('Should initialize the app', () => {
		    
		      //   it('should initialize the app', async () => {
		      //     TestBed.createComponent(AppComponent);
		    
		      //     const ready = spyOn((<any>component).Platform, 'ready');
		    
		      //     component.initializeApp()
		    
		      //     expect(ready).toHaveBeenCalled();
		          
		      //   });
		    
		      // })
		    
		    
		    });
		    >
		    
		```
		
		El errror que me da karma
		``` 
		    <AppComponent should createthe app
		    TypeError: this.platform.ready is notafunction
		    TypeError: this.platform.ready is notafunction
		        at AppComponent.ready [as initializeApp] (http://localhost:9876/_karma_webpack_/webpack:/src/app/app.component.ts:27:23)
		        atnew initializeApp (http://localhost:9876/_karma_webpack_/webpack:/src/app/app.component.ts:23:14)
		        at createClass (http://localhost:9876/_karma_webpack_/webpack:/node_modules/@angular/core/fesm5/core.js:22062:1)
		        at createDirectiveInstance (http://localhost:9876/_karma_webpack_/webpack:/node_modules/@angular/core/fesm5/core.js:21931:1)
		        at createViewNodes (http://localhost:9876/_karma_webpack_/webpack:/node_modules/@angular/core/fesm5/core.js:23157:1)
		        at createRootView (http://localhost:9876/_karma_webpack_/webpack:/node_modules/@angular/core/fesm5/core.js:23071:1)
		        at callWithDebugContext (http://localhost:9876/_karma_webpack_/webpack:/node_modules/@angular/core/fesm5/core.js:24079:1)
		        at Object.debugCreateRootView [as createRootView] (http://localhost:9876/_karma_webpack_/webpack:/node_modules/@angular/core/fesm5/core.js:23589:1)
		        at ComponentFactory_.push../node_modules/@angular/core/fesm5/core.js.ComponentFactory_.create (http://localhost:9876/_karma_webpack_/webpack:/node_modules/@angular/core/fesm5/core.js:21410:1)
		        at initComponent (http://localhost:9876/_karma_webpack_/webpack:/node_modules/@angular/core/fesm5/testing.js:1916:1)>
		    
		```

	* **Cristian Daniel Marquez Barrio** [562181] (1)

		Debería ser:
		
		  1. `{ provide: Platform, useClass: PlatformStub },`
		  2. `return Promise.resolve();`
		
		

* **Jaime Quintero Rodríguez** (1) [57221](https://platzi.com/comentario/562181/) 
Estoy intentando hacer las pruebas de este codigo, pero por mas que intento no consigo solucionarlo. Si alguien puede ayudarme impo...

	* **Diego Alexander Forero Higuera (Platzi)** [57221] (1)

		Cuéntanos que problema te da para poder ayudarte.

