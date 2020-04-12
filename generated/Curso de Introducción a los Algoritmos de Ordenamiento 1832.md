[Curso de Introducción a los Algoritmos de Ordenamiento 1832](https://platzi.com/cursos/ordenamiento)

# Introducción [5423]

## 0010. Introducción al curso y bienvenida [26686](https://platzi.com/clases/1832-ordenamiento/26686-introduccion-al-curso-y-bienvenida/)

### Descripción:


### Links:

* [Curso de Introducción al Pensamiento Computacional con Python](https://platzi.com/clases/python-cs/)

* [Taller de Creación de Router para Single Page App con JavaScript](https://platzi.com/clases/singlepage-app/)

### Comentarios:

* **Daniel Carmona** (3) [1031759](https://platzi.com/comentario/1031759/) 

	A reforzar conocimiento, es algo que no le entendí a la primera, pero que quiero aprenderlo al 100.

* **eddyarellanes** (3) [1031520](https://platzi.com/comentario/1031520/) 

	Les recomiendo para practicar:  
	<https://codesignal.com/developers/>
	
	Tiene problemas de algoritmos simples, de grafos, de DB y son ejercicios de Interviews de empresas como Google, Uber, Amazon, etc.

* **Hanier Steve Morales Pérez** (2) [1036412](https://platzi.com/comentario/1036412/) 

	Los Algoritmos de Ordenamiento se encargan de brindar un orden dado a un set de elementos.
	
	Un arreglo ordenado es un arreglo que tiene un orden específicamente definido (por ejemplo [a,b,c,d] es un arreglo ordenado alfabéticamente.

* **Hanier Steve Morales Pérez** (2) [1036393](https://platzi.com/comentario/1036393/) 

	Un gusto tenerte de vuelta Ricardo. Con mucho ánimo para el curso 😄

* **jezz-barrientos** (2) [1033504](https://platzi.com/comentario/1033504/) 

	A seguir aprendiendo, con muchas expectativas del curso.

* **miguelp.** (2) [1030506](https://platzi.com/comentario/1030506/) 

	RETO TERMINARLO EN UNA SEMANA APARTIR DE AHORA.

* **joeldm011** (2) [1030320](https://platzi.com/comentario/1030320/) 

	Muy emocionado de tomar este curso!!! Vamo a darle.  
	Saludos Ricardo 😃

* **garbull** (1) [1070241](https://platzi.com/comentario/1070241/) 

	este curso no lo puedo ver desde la app

	* **Manuel Eguiluz** [1070241] (1)
Yo lo estoy viendo desde la aplicación móvil.

* **Dagoberto Porras Plata** (1) [1046313](https://platzi.com/comentario/1046313/) 

	Ricardo un crack!

* **Jean Carlos Nuñez Hernandez** (1) [1040257](https://platzi.com/comentario/1040257/) 

	este curso promete mucho vamos pues!

* **hydroxseguridad** (1) [1031260](https://platzi.com/comentario/1031260/) 

	Yo tambien estoy muy interesado por la nueva carrera! y es muy necesario hoy en dia!

* **martin-c** (1) [1030590](https://platzi.com/comentario/1030590/) 

	Cuando sale la nueva carrera hay alguna fecha

* **onyx** (1) [1030478](https://platzi.com/comentario/1030478/) 

	Acabe de pasar por ese tema en la U, espero complementar conocimientos con este curso 😄

* **Royer Guerrero Pinilla** (1) [1030435](https://platzi.com/comentario/1030435/) 

	Estaba esperando este curso, me gustaría que platzi hiciera una carrera de computer science

# Bubble Sort [5424]

## 0020. Algoritmo Bubble Sort [26687](https://platzi.com/clases/1832-ordenamiento/26687-algoritmo-bubble-sort/)

### Descripción:


### Comentarios:

* **Hanier Steve Morales Pérez** (1) [1036418](https://platzi.com/comentario/1036418/) 

	​Bubble Sort u Ordenamiento de Burbuja (Algoritmo más simple que existe). Se le llama así por que va seleccionando los elementos adyacentes, cambia el número que está en la posición incorrecta a la posición correcta. Es un Algoritmo super lento y poco eficiente, primero por que necesitas dos bucles y segundo, por la cantidad de iteraciones del mismo.

* **jezz-barrientos** (1) [1033524](https://platzi.com/comentario/1033524/) 

	Buena clase vamos por mas.

* **Daniel Carmona** (1) [1032385](https://platzi.com/comentario/1032385/) 

	Mi primer método de ordenamiento que vi en programación, me recuerda la escuela.

* **hydroxseguridad** (1) [1031275](https://platzi.com/comentario/1031275/) 

	Interesante!

* **Royer Guerrero Pinilla** (1) [1030458](https://platzi.com/comentario/1030458/) 

	El Bubble Sort básicamente es un switch de arr[i] y arr[i+1] cuando arr[i] sea mayor que arr[i+1] para ordenar una lista

* **joeldm011** (1) [1030346](https://platzi.com/comentario/1030346/) 

	La nueva intro muy bonita por cierto!  
	En la universidad en la materia de Estructura de datos recuerdo que vi este metodo, lo supe implementar pero hoy dia no recuerdo a ciencia cierta como fue.  
	Asi que me servira mucho volverlo a ver.

## 0030. Diseño y análisis de Bubble Sort [26688](https://platzi.com/clases/1832-ordenamiento/26688-diseno-y-analisis-de-bubble-sort/)

### Descripción:


### Comentarios:

* **Royer Guerrero Pinilla** (4) [1030471](https://platzi.com/comentario/1030471/) 

	Estaría super un curso enfocado a BIG O

	* **Cristhian Franco** [1030471] (2)

		Un curso avanzado de algoritmos enfocado en optimizacion para Big O estaria genial en el futuro.

	* **ricardocelis (Platzi)** [1030471] (3)

		lo tengo en el mapa!

* **Hanier Steve Morales Pérez** (2) [1036458](https://platzi.com/comentario/1036458/) 

	Bubble Sort hace uso de dos bucles o ciclos. El primero que está encargando de recorrer todo nuestro vector, y el segundo que se está encargando de ejecutar las comparaciones cada vez que se avanza.

* **Manuel Rivera** (2) [1033718](https://platzi.com/comentario/1033718/) 

	con JS
	
	Genero un arreglo de 10 valores al azar y luego aplico el BubbleSort
	``` 
	    function bubbleSort(arr) {
	      if (arr.length === 0) {
	        return arr;
	      } else {
	        let i, j;
	        for (i = 0; i < arr.length - 1; i++) {
	          for (j = 0; j < arr.length - 1; j++) {
	            if (arr[j] > arr[j + 1]) {
	              let temp = arr[j];
	              arr[j] = arr[j + 1];
	              arr[j + 1] = temp;
	            }
	          }
	        }
	      }
	      return arr;
	    }
	    
	    const numbers = new Array(10)
	      .fill(0)
	      .map(() => Math.floor(Math.random() * 11));
	    console.log(numbers);
	    console.log(bubbleSort(numbers));```
	    
	```

* **jezz-barrientos** (2) [1033552](https://platzi.com/comentario/1033552/) 

	Excelente explicacion.

	* **ricardocelis (Platzi)** [1033552] (2)

		GraciaS Jeezz!!!

* **joeldm011** (2) [1032922](https://platzi.com/comentario/1032922/) 

	Muy bien explicado!!  
	A pasar esto a código!!!

* **hydroxseguridad** (2) [1031362](https://platzi.com/comentario/1031362/) 

	me encanto el ejemplo escrito manualmente y el grafico para darle mas entendimiento al algoritmo.

	* **ricardocelis (Platzi)** [1031362] (1)

		Gracias Hydrox!

* **Daniel Carmona** (1) [1032400](https://platzi.com/comentario/1032400/) 

	Me encanto, lo entendí a la perfección.

* **Diego Joaquin  Colina** (1) [1032042](https://platzi.com/comentario/1032042/) 

	Muy bien Explicado!!!

* **joeldm011** (1) [83713](https://platzi.com/comentario/1032932/) 
Me surgió una duda. ¿En cada recorrido del bucle siempre compara x valor con el de a lado hasta que recorre todo el arreglo verdad? Cuand...

	* **Ruben Padilla** [83713] (1)

		 _Bubble Sort_ en cada iteración recorre todo el set de datos y puede realizar varios cambios. Incluso cuando el set de datos ya está ordenado realiza una iteración final para verificar que no debe hacer más cambios.

## 0040. Configuración de Entorno [26689](https://platzi.com/clases/1832-ordenamiento/26689-configuracion-de-entorno/)

### Descripción:


### Links:

* [Curso de Introducción al Pensamiento Computacional con Python](https://platzi.com/clases/python-cs/)

### Comentarios:

* **Daniel Carmona** (4) [1032965](https://platzi.com/comentario/1032965/) 

	Lo ando haciendo en jupyter.

* **joeldm011** (2) [1032934](https://platzi.com/comentario/1032934/) 

	Yo usaba PyCharm pero usare esta forma en Visual usando la terminal!

* **hydroxseguridad** (2) [1031382](https://platzi.com/comentario/1031382/) 

	Yo uso el IDE de PyCharm

* **jezz-barrientos** (1) [1033570](https://platzi.com/comentario/1033570/) 

	VScode listo y funcionando

## 0050. Implementación de Bubble Sort [26727](https://platzi.com/clases/1832-ordenamiento/26727-implementacion-de-bubble-sort/)

### Descripción:


### Comentarios:

* **jezz-barrientos** (2) [1033594](https://platzi.com/comentario/1033594/) 

	El reto seria asi:
	``` 
	    defbubbleSort(array):
	    	n = len(array)
	    
	    	for i in range(n):
	    		print(array)
	    		for j in range(0, n-i-1):
	    			if array[j] > array[j+1] :
	    				array[j], array[j+1] = array[j+1], array[j]
	    				
	    
	    
	    
	```

* **estebansolorzano** (2) [1030352](https://platzi.com/comentario/1030352/) 

	Es interesante el curso sobre algoritmos, pero pienso que durante los cursos deben enseñar mas sobre las buenas practicas y como trabajar en python (en este caso) como PEP8 o por ejemplo al imprimir hacer algo como.
	``` 
	    for i inarray:
	        print(i)
	    
	```
	
	Inclusive asi es mucho mejor que ponerse uno a usar len, range y %d. y no simplemente hacerlo “como caiga”.
	
	Almenos es mi punto de vista

* **Filiberto Santillán** (1) [1100134](https://platzi.com/comentario/1100134/) 

	He aquí una solución para el problema con JS. También la implementación para romper el ciclo en caso de concluir.  
	.  
	![IMG_41CD43040D6E-1.jpg](https://static.platzi.com/media/user_upload/IMG_41CD43040D6E-1-bee2aa9f-168e-41d5-9d72-30f9096d10b3.jpg)

* **Manuel Eguiluz** (1) [1078191](https://platzi.com/comentario/1078191/) 

	Mi implementación en java.
	``` 
	    import java.util.Arrays;
	    import java.util.Random;
	    import java.util.function.Predicate;
	    
	    publicclassBubbleSort8{
	    
	        public void bubbleSort(finalintarray[], final Predicate<Integer> sortType) {
	            finalint n = array.length;
	            boolean sorted = false;
	            int temp;
	            print("Size n: %d%n%n", n);
	    
	            // Subtract 1 to avoid traversing the first element cause it is already ordered.
	            // Break it to avoid useless loop if it's ordered
	            for (int i = 0; i < n - 1 && !sorted; i++) {
	                print("Iteration %d input %s%n", i + 1, Arrays.toString(array));
	                sorted = true;
	                // One is subtracted to be able to compare the penultimate and the last.
	                // [j] > [j + 1].
	                for (int j = 0; j < n - i - 1; j++) {
	                    finalboolean swaps = sortType.test(j);
	                    print("Comparing array[%d]=%s, array[%d]=%s, swaps=%b%n", j, array[j], j + 1, array[j + 1], swaps);
	    
	                    if (swaps) {
	                        // swap arr[j+1] and arr[i]
	                        temp = array[j];
	                        array[j] = array[j + 1];
	                        array[j + 1] = temp;
	                        sorted = false;
	                    }
	                }
	    
	                print("Iteration %d ouput %s%n", i + 1, Arrays.toString(array));
	                print("%s%n%n", "-".repeat(46)); // Java 11 only
	            }
	        }
	    
	        private void print(final String template, final Object... values) {
	            System.out.printf(template, values);
	        }
	    
	        publicstatic void main(final String args[]) {
	            finalint n = 6;
	            finalint randomNumbers[] = new Random().ints(n, 0, 100).toArray();
	            final Predicate<Integer> orderAsc = j -> randomNumbers[j] > randomNumbers[j + 1];
	    
	            final BubbleSort8 bubbleSort = new BubbleSort8();
	            bubbleSort.bubbleSort(randomNumbers, orderAsc);
	        }
	    }
	    
	```

* **Mariano Navarrete** (1) [1049096](https://platzi.com/comentario/1049096/) 

	```
	    let arr = [3,1,2,5,8,10,9,6];
	    
	    const bubbleSort = (arr) => {
	        let size = arr.length - 1;
	        let aux = 0;
	        let iter = 0;
	        for(let i = 0; i < size; i++) {
	            for(let j = 0; j < size - i; j++ ){
	                if(arr[j] > arr[j+1]){
	                    aux = arr[j];
	                    arr[j] = arr[j+1];
	                    arr[j+1] = aux;
	                    iter++;
	                }
	                console.log(arr + ` pasada ${j}`);
	            }       
	            if(iter === 0){
	                break;
	            }
	            iter = 0;
	        } 
	    }
	    
	    bubbleSort(arr);
	    
	```

* **Cristhian Arce** (1) [1044827](https://platzi.com/comentario/1044827/) 

	```
	    import random
	    
	    ar = [random.randint(0,1000) for _ in range(100)]
	    
	    defbubbleSort(ar):
	        for i in range(0,len(ar)-1):
	            for j in range(0,len(ar)-1):
	                if(ar[j]!=ar[j+1]):
	                    if(ar[j]>ar[j+1]):
	                        temp = ar[j]
	                        ar[j]=ar[j+1]
	                        ar[j+1]=temp
	        return ar
	    print(bubbleSort(ar))
	    
	```

* **anorak** (1) [1037398](https://platzi.com/comentario/1037398/) 

	En Java…
	``` 
	    import java.util.Arrays;
	    
	    public class Main {
	        public static void main(String[] args) {
	            int[] lista = {9, 8, 7, 6};
	            System.out.println("Array de números sin ordenar:");
	            System.out.println(Arrays.toString(lista));
	            System.out.println("Número de elementos: " + lista.length);
	            System.out.println("///////////");
	            //variable para contar los intercambios.
	            int cuentaintercambios = 0;
	            //Usamos un bucle anidado, saldra cuando este ordenado el array.
	            //Si hay intercambios, es porque no esta ordenado.
	            for (boolean ordenado = false; !ordenado; ) {
	                for (int i = 0; i < lista.length - 1; i++) {
	                    if (lista[i] > lista[i + 1]) {
	                        //Intercambiamos valores
	                        int variableauxiliar = lista[i];
	                        lista[i] = lista[i + 1];
	                        lista[i + 1] = variableauxiliar;
	                        //Indicamos que hay un cambio.
	                        cuentaintercambios++;
	                        System.out.println("Números que se mueven: " + variableauxiliar + "-" + lista[i]);
	                        System.out.println(Arrays.toString(lista));
	                    }
	                }
	                //Si no hay intercambios, es que esta ordenado.
	                if (cuentaintercambios == 0) {
	                    ordenado = true;
	                }
	                //Inicializamos la variable de nuevo para que empiece a contar de nuevo.
	                cuentaintercambios = 0;
	            }
	            System.out.println("///////////");
	            System.out.println("Array de números ordenado:");
	            System.out.println(Arrays.toString(lista));
	        }
	    }
	    
	```

* **Eduardo Zamarron Muñoz** (1) [1033917](https://platzi.com/comentario/1033917/) 

	Reto en JS.
	``` 
	    function bubbleSort(arr){
	      let arrLength = arr.length;
	      let swapped = false;
	      for (let i = 0; i < arrLength; i++) {
	        swapped = false;
	        for (let j = 0; j < arrLength - i; j++) {
	          if ( arr[j] > arr[j+1] ){
	            [ arr[j], arr[j+1] ]= [ arr[j+1], arr[j] ];
	            swapped = true;
	          }
	        }
	        if(swapped === false){
	          break;
	        }
	      }
	    }
	    arr = [2,3,9,4,8,1,5]; 
	    bubbleSort(arr);
	    console.log(arr);
	    
	```

* **Manuel Rivera** (1) [1033893](https://platzi.com/comentario/1033893/) 

	Reto con JS, una buena práctica tambiés es que debemos saber si el arreglo que recibimos tiene longitud. E n este caso el ciclo solo se realizará si el primer elemento es mayor que el elemento en la posición que siguiente.
	``` 
	    function bubbleSort(arr) {
	      if (arr.length === 0) {
	        return arr;
	      } else {
	        let i, j;
	        for (i = 0; i < arr.length - 1; i++) {
	          console.log(arr);
	          for (j = 0; j < arr.length - 1; j++) {
	            if (arr[j] > arr[j + 1]) {
	              let temp = arr[j];
	              arr[j] = arr[j + 1];
	              arr[j + 1] = temp;
	            }
	          }
	        }
	      }
	      return arr;
	    }
	    
	    const numbers2 = new Array(10)
	      .fill(0)
	      .map(() => Math.floor(Math.random() * 11));
	    console.log(numbers2);
	    console.log(bubbleSort(numbers2));```
	    
	    
	```

* **Cristhian Franco** (1) [1033480](https://platzi.com/comentario/1033480/) 

	Aqui esta el reto en Java, imprime el array cada vez que se hace un cambio:
	``` 
	    public class MyClass {
	        public static void main(String args[]) {
	          int[] arr = {190, 1200, 1, 2, 4, 55, 1000, 6, 800};
	          
	          for(int i = 0; i < arr.length; i++){
	              for(int j = 0; j < arr.length-i-1; j++){
	                    if(arr[j] > arr[j+1]){
	                        int aux = arr[j+1];
	                        arr[j+1] = arr[j];
	                        arr[j]  = aux;
	                        for(int k = 0; k < arr.length; k++){
	                            System.out.print(arr[k]+ " ");
	                        }
	                        System.out.println(" ");
	                    } 
	                }
	            }
	        }
	    }
	    
	```

	* **Manuel Eguiluz** [1033480] (1)

		Puedes usar también el método java.util.Arrays.toString(arr)

* **joeldm011** (1) [1033148](https://platzi.com/comentario/1033148/) 

	Codigo en Java.  
	Solo es cuestion de Mandarlo llamar de igual manera e imprimir si asi se desea.
	``` 
	    publicstaticvoidbubbleS(intarray[]){
	            int aux, n = array.length; //Tamaño del Arreglo.
	    
	            for (int i = 0; i < n; i++) { //For que nos ayudara a recorrer todo el Array.
	                for (int j = 0; j < (n - i - 1); j++) { //For que Compara a los valores adyacentes
	    
	                    if (array[j] > array[j + 1]) { // Comparacion de numero mayor que el de a lado
	                        aux = array[j]; // Variable auxiliar para guardar el valor anterior de la posicion j
	                        array[j] = array[j + 1]; //Asignacion del valor mas pequeño en la posicion correcta
	                        array[j + 1] = aux; // Asignacion del valor Mayor en la posicion correcta
	                    }
	                }
	            }
	            
	        }
	    
	```
	
	Main para llamar al metodo:
	``` 
	    public static void main(String args[]) {
	            //Metodo de Ordenamiento: BubbleSort de forma Ascendente.
	            
	            // Declaramos un Array.
	            
	            int array[] ={23,1,6543,12,12,76,23,2,8765,3};
	            
	            System.out.println("El array Original es:");
	            for(int i:array){
	                System.out.print(i+" ");
	            }
	            
	            bubbleS(array);
	            
	            System.out.println("\n-----------------------------------------------------");
	            System.out.println("El array ordenado es:");
	            for(int i: array){
	                System.out.print(i+" ");
	            }
	            System.out.println("");
	        }
	    
	```

	* **Manuel Eguiluz** [1033148] (1)

		Puedes usar también el método java.util.Arrays.toString(arr) para convertir un arreglo a un cádena.

* **Daniel Carmona** (1) [1033124](https://platzi.com/comentario/1033124/) 

	Solo puse que contara las veces que hizo algún cambio
	
	![Comentario.png](https://static.platzi.com/media/user_upload/Comentario-dbe91379-fe4c-4abb-941a-c7d4df31d87a.jpg)

* **eddyarellanes** (1) [1031897](https://platzi.com/comentario/1031897/) 

	Lo mismo pero Descendente y usando while en el segundo Loop. Disculpen que las variables no sean más descriptivas, ya tiene rato que lo hice ja
	``` 
	    defsimpleSort(arr):
	    
	        n = len(arr)
	    
	        for i in range(n):
	            j = 0
	            stop = n - i
	            while j < stop - 1:
	                if arr[j] > arr[j + 1]:
	                    (arr[j], arr[j+1]) = (arr[j+1], arr[j])
	                j += 1
	        return arr
	    
	```

* **hydroxseguridad** (1) [1031463](https://platzi.com/comentario/1031463/) 

	uff buenisimo!!!

* **Royer Guerrero Pinilla** (1) [1030775](https://platzi.com/comentario/1030775/) 

	Solución reto
	``` 
	    # Bubble Sort Algoritmo
	    
	    defbubbleSort(array):
	        n = len(array)
	    
	        for i in range(n):
	            stop = True
	            print(array)
	            for j in range(0, n-i-1):
	                if array[j] > array[j+1]:
	                    print(f'Swap: [{array[j]}][{array[j+1]}] => [{array[j+1]}][{array[j]}]')
	                    array[j], array[j+1] = array[j+1], array[j]
	                    stop = False
	    
	                    if stop == True:
	                        break
	    
	            print('-----')
	    
	    array = [190, 120, 840, 1, 6, 845]
	    bubbleSort(array)
	    
	```

# Selection Sort [5425]

## 0060. Algoritmo Selection Sort [26691](https://platzi.com/clases/1832-ordenamiento/26691-algoritmo-selection-sort/)

### Descripción:


### Comentarios:

* **Manuel Rivera** (2) [1033901](https://platzi.com/comentario/1033901/) 

	Este no lo había escuchado, suena como algo parecido al mergeSort 🗽.

* **jezz-barrientos** (2) [1033604](https://platzi.com/comentario/1033604/) 

	Interesenta clase.

* **joeldm011** (2) [1033173](https://platzi.com/comentario/1033173/) 

	Suena interesante!  
	Ya quiero ver como se implementa 😃

* **Daniel Carmona** (2) [1033128](https://platzi.com/comentario/1033128/) 

	Un algoritmo nuevo!

* **hydroxseguridad** (1) [1032179](https://platzi.com/comentario/1032179/) 

	wow! interesante!

* **Royer Guerrero Pinilla** (1) [1031211](https://platzi.com/comentario/1031211/) 

	No se me quedo del todo claro pero lo que entendí es que va comparando para encontrar el elemento de menor valor y luego hace swaping con el valor más alto que les siga

## 0070. Diseño y análisis de Selection Sort [26692](https://platzi.com/clases/1832-ordenamiento/26692-diseno-y-analisis-de-selection-sort/)

### Descripción:


### Comentarios:

* **Hanier Steve Morales Pérez** (3) [1036835](https://platzi.com/comentario/1036835/) 

	Te veías más viejo Ricardo xD

* **NicoMano** (2) [1032583](https://platzi.com/comentario/1032583/) 

	El dato de la edad 😄

* **jezz-barrientos** (1) [1034013](https://platzi.com/comentario/1034013/) 

	Interesante algoritmo, a implementarlo

* **joeldm011** (1) [1033174](https://platzi.com/comentario/1033174/) 

	Se ve muy interesante este algoritmo, lo que me da curiosidad es como se hace eso del subarreglo… Me da mucha curiosidad.  
	Vamo al codigo.

* **Daniel Carmona** (1) [1033142](https://platzi.com/comentario/1033142/) 

	Muy bien explicado.

* **hydroxseguridad** (1) [1032195](https://platzi.com/comentario/1032195/) 

	muy claro! 😃

## 0080. Implementación de Selection Sort [26693](https://platzi.com/clases/1832-ordenamiento/26693-implementacion-de-selection-sort/)

### Descripción:


### Comentarios:

* **clozarr** (1) [1089961](https://platzi.com/comentario/1089961/) 

	```
	    /*
	    	 * Selection Sort Iterative
	    	 **/
	    	public static int[] selectionSort(int[] items) {
	    
	    		int swapElement = 0;
	    		for (int i = 0; i < items.length; i++) {
	    
	    			int indexMenor = i;
	    
	    			for (int j = (i + 1); j < items.length; j++) {
	    
	    				if (items[indexMenor] > items[j]) {
	    
	    					indexMenor = j;
	    
	    				}
	    			}
	    
	    			swapElement = items[i];
	    			items[i] = items[indexMenor];
	    			items[indexMenor] = swapElement;
	    
	    		}
	    
	    		return items;
	    	}```
	    
	```

* **Manuel Eguiluz** (1) [1079288](https://platzi.com/comentario/1079288/) 

	Mi solución en java.
	``` 
	    import java.util.Arrays;
	    import java.util.Random;
	    import java.util.function.BiPredicate;
	    
	    public class SelectionSort {
	    
	        publicvoidsort(finalint array[], final BiPredicate<Integer, Integer> sortType) {
	            finalint n = array.length;
	            boolean sorted = false;
	            int idxDes;
	            int temp;
	            print("Size n: %d%n%n", n);
	    
	            for (int i = 0; i < n && !sorted; i++) {
	                print("Iteration %d input %s%n", i + 1, Arrays.toString(array));
	                sorted = true;
	    
	                // Buscando el indice del valor más bajo
	                idxDes = i;
	                for (int j = i + 1; j < array.length; j++) {
	                    if (sortType.test(j, idxDes)) {
	                        idxDes = j;
	                        sorted = false;
	                    }
	                }
	    
	                // Cambio del minimo elemento con el primer elemento
	                temp = array[i];
	                array[i] = array[idxDes];
	                array[idxDes] = temp;
	    
	                print("Iteration %d ouput %s%n", i + 1, Arrays.toString(array));
	                print("%s%n%n", "-".repeat(46)); // Java 11 only
	    
	            }
	    
	        }
	    
	        privatevoidprint(finalString template, finalObject... values) {
	            System.out.printf(template, values);
	        }
	    
	        publicstaticvoid main(String[] args) {
	            finalint n = 6;
	            finalint randomNumbers[] = new Random().ints(n, 0, 100).toArray();
	            final BiPredicate<Integer, Integer> orderAsc = (j, idxDes) -> randomNumbers[idxDes] > randomNumbers[j];
	    
	            final SelectionSort selectionSort = new SelectionSort();
	            selectionSort.sort(randomNumbers, orderAsc);
	        }
	    
	    }
	    
	```

* **Mariano Navarrete** (1) [1050681](https://platzi.com/comentario/1050681/) 

	```
	    let arr = [3,1,2,5,8,10,9,6];
	    
	    const selectionSort = (arr) => {
	        let tam = arr.length;
	        let aux = 0;
	        for (let i = 0; i < tam; i++){
	            let indMin = i;
	            for (let j = i + 1; j < tam; j++){
	                if(arr[indMin] > arr[j]){
	                    indMin = j;
	                }
	            }
	            aux = arr[i];
	            arr[i] = arr[indMin];
	            arr[indMin] = aux;
	            console.log(arr);
	        } 
	    }
	    
	    selectionSort(arr);
	    
	```

* **anorak** (1) [1049579](https://platzi.com/comentario/1049579/) 

	En Java.
	``` 
	    import java.util.Arrays;
	    public class SelectionSort {
	        public static void main(String[] args) {
	            int lista[] = {5, 9, 3, 7, 1, 8};
	            System.out.println("Número de elementos en la lista: " + lista.length);
	            // Uno por uno se mueve en el subarray desordenado
	            for (int i = 0; i < lista.length - 1; i++) {
	                // Buscar el minimo elemento en una lista desordenada
	                int min_idx = i;
	                for (int j = i + 1; j < lista.length; j++) {
	                    if (lista[j] < lista[min_idx])
	                        min_idx = j; //buscando el índice más bajo
	                }
	                System.out.println("Número menor: " + lista[min_idx] + " | Índice original: " + min_idx);
	                System.out.println(Arrays.toString(lista));
	                // Cambio del minimo elemento con el primer elemento
	                int temp = lista[min_idx];
	                lista[min_idx] = lista[i];
	                lista[i] = temp;
	                System.out.println("Índice final: " + i + " | Se mueve el: " + lista[min_idx]);
	            }
	    
	            System.out.println("Lista Ordenada: " + Arrays.toString(lista));
	        }
	    
	    
	    }
	    
	    
	```

* **jezz-barrientos** (1) [1034309](https://platzi.com/comentario/1034309/) 

	```
	    for i in range(len(A)): 
	        print(A)  
	        min_idx = i 
	        for j in range(i+1, len(A)): 
	            
	            if A[min_idx] > A[j]: 
	                min_idx = j 
	                  
	    
	        A[i], A[min_idx] = A[min_idx], A[i] 
	      
	    
	    print ("Sorted array") 
	    for i in range(len(A)): 
	        print("%d" %A[i])  ```
	    
	```

* **Eduardo Zamarron Muñoz** (1) [1034011](https://platzi.com/comentario/1034011/) 

	Código en JS.
	``` 
	    function selectionSort(arr) {
	      let arrLength = arr.length;
	      let minorIndex;
	      for (let i = 0; i < arrLength; i++) { 
	       minorIndex = i;
	        for (let j = i; j < arrLength; j++) {
	          if ( arr[minorIndex] > arr[j] )
	         minorIndex = j;
	        }
	    
	        [ arr[i], arr[minorIndex] ] = [ arr[minorIndex], arr[i] ]; 
	        console.log(arr);  
	      } 
	    }
	    
	    arr = [700, 312, 8, 12, 1, 66, -40, 859, 24, 0, -120]
	    selectionSort(arr)
	    console.log("El arreglo ordenado es: \n")
	    console.log(arr);```
	    
	```

* **Daniel Carmona** (1) [1033150](https://platzi.com/comentario/1033150/) 
	
	![Comentario2.png](https://static.platzi.com/media/user_upload/Comentario2-1ff36eb0-4648-4222-b581-65a4ddb9f04f.jpg)

* **hydroxseguridad** (1) [1032248](https://platzi.com/comentario/1032248/) 

	mas claro! mmuy buenisimo profe

* **Royer Guerrero Pinilla** (1) [1031284](https://platzi.com/comentario/1031284/) 

	Reto solucionado 👨‍💻
	``` 
	    # Selection Sort Algoritmo
	    array = [2, 23, 34, 100, 59, 951, 6]
	    
	    def selectionSort(array):
	        
	        for i inrange(len(array)):
	            idxDes = i
	            
	            for j inrange(i + 1, len(array)):
	                print(array)
	                ifarray[idxDes] > array[j]:
	                    idxDes = j
	        
	            array[i], array[idxDes] = array[idxDes], array[i]
	    
	    
	    selectionSort(array)
	    print(array)    
	    
	```

* **Royer Guerrero Pinilla** (1) [1031231](https://platzi.com/comentario/1031231/) 

	Luego de todo ya lo entieno, lo que se hace es recorrer el array original buscando el valor minimo y ese valor lo enviamos a un nuevo array con el fin de ir creando un array ordenado

# Cierre [5426]

## 0090. Comparación de algoritmos Bubble Sort y Selection Sort [26694](https://platzi.com/clases/1832-ordenamiento/26694-comparacion-de-algoritmos-bubble-sort-y-selection-/)

### Descripción:


### Links:

* [🚀Platzi: ‎Cursos Online Profesionales de Tecnología](https://platzi.com/clases/learning-path/ai/)

* [Curso de Introducción a la Terminal y Línea de comandos](https://platzi.com/clases/terminal/)

### Comentarios:

* **Royer Guerrero Pinilla** (3) [1031315](https://platzi.com/comentario/1031315/) 

	Quería mostrar un gif de la velocidad de los algoritmos pero no fue posible team platzi deberían mejorar eso 😥😥😥, de todas formas les dejo el link  
	[Velocidad de algoritmos de ordenamiento](https://pythonizame.s3.amazonaws.com/media/uploads/2015/11/04/fq0a8hx.gif)

	* **Eduardo Zamarron Muñoz** [1031315] (1)

		Es interesante, porque en ese GIF parece que gana BubbleSort.

* **Hanier Steve Morales Pérez** (2) [1037004](https://platzi.com/comentario/1037004/) 

	Investigacion bien chingona guardado cuatro y media am.docx xD jajajaja crack!!

* **joeldm011** (2) [1035987](https://platzi.com/comentario/1035987/) 

	Interesante el tiempo que les toma a cada algoritmo ordenarlos.

* **jezz-barrientos** (2) [1034334](https://platzi.com/comentario/1034334/) 

	La notación Big-O nos proporciona una manera de saber cómo se va a comportar un algoritmo en función de los argumentos que le pasemos y la escala de los mismos.

* **Daniel Carmona** (1) [1033158](https://platzi.com/comentario/1033158/) 
	
	![Comentario2.png](https://static.platzi.com/media/user_upload/Comentario2-3969ee6d-fc81-4740-8bb5-ebc86f5f5f5e.jpg)

* **hydroxseguridad** (1) [1032263](https://platzi.com/comentario/1032263/) 

	Emocionante! se deberia dar mas cursos en relacion a un estudio profundo de otros algoritmos en Python!

* **Royer Guerrero Pinilla** (1) [1031319](https://platzi.com/comentario/1031319/) 

	Entiendo que el Insert sort es mas rapido deberian explicarlo

## 0100. Cierre del curso y próximos pasos [26695](https://platzi.com/clases/1832-ordenamiento/26695-cierre-del-curso-y-proximos-pasos/)

### Descripción:


### Links:

* [https://twitter.com/CelisMX](https://twitter.com/CelisMX)

### Comentarios:

* **jezz-barrientos** (2) [1034336](https://platzi.com/comentario/1034336/) 

	me gustaria ver en futuro REDES NEURONALES Algoritmos de Aprendizaje.

* **Nagcely Mendoza** (1) [1060270](https://platzi.com/comentario/1060270/) 

	Excelente curso, me gustaría ver un algoritmos para encontrar la ruta crítica de un proyecto.

* **Gianmarco Palacios Frisancho** (1) [1044331](https://platzi.com/comentario/1044331/) 

	buen inicio para introducir en el tema gracias

* **joeldm011** (1) [1035990](https://platzi.com/comentario/1035990/) 

	Fue un muy buen curso! Alguno que me recomienden para mejorar en estructuras de datos?

* **Eduardo Zamarron Muñoz** (1) [1034034](https://platzi.com/comentario/1034034/) 

	Me gustaría que algoritmos más complejos fueran explicados en siguientes cursos, en el curso de Algoritmos pasado las explicaciones se quedaban cortas.  
	Este formato es mejor que el del curso pasado.

* **Daniel Carmona** (1) [1033160](https://platzi.com/comentario/1033160/) 

	Me gusto, me gustaría poder ver más algoritmos de ordenamiento, vi muchos en la U y quisiera reforzar mis conocimientos.

* **hydroxseguridad** (1) [1032268](https://platzi.com/comentario/1032268/) 

	Estoy muy de acuerdo en que haya mas cursos relacionado a los algoritmos. excelente curso!

* **Royer Guerrero Pinilla** (1) [1031329](https://platzi.com/comentario/1031329/) 

	El curso es bueno se explican bien los algoritmos tal vez se podrían abarcar más 2 se queda un poco corto 4 o 5 estaría bien

