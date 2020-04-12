[Curso de Firestore para Android 1532](https://platzi.com/cursos/firestore)

# Bienvenida e introducción [3744]

## 0010. Introducción al curso [18726](https://platzi.com/clases/1532-firestore/18726-introduccion-al-curso9973/)

### Descripción:


¡Bienvenido al curso!

En esta ocasión nos acompaña Santiago Carrillo, Google Developer Expert en Android con más de 7 años desarrollando aplicaciones nativas.

**Firebase** es una plataforma de infraestructura para aplicaciones web y móviles. Nos facilita desarrollar nuestros productos sin tener que preocuparnos por la infraestructura.

* Autenticación: Este módulo te permite crear cuentas temporales las cuales pueden acceder a los datos protegidos con reglas de seguridad

* Cloud Firestore: Nos da una base de datos en tiempo real, no sincronizada, NoSQL y flexible a escalar a las diferentes configuraciones que quieras.




### Comentarios:

* **Juan David Castro (Platzi)** (3) [545989](https://platzi.com/comentario/545989/) 

	Servicios de Firebase:
	
	* Firestore es una base de datos NoSQL que nos permite almacenar y sincronizar en tiempo real los datos e nuestra aplicación ✌️📝.
	* La autenticación (en mi opinión, lo herramienta más útil de Firebase 😍🎉) nos permite crear, autenticar y administrar los usuarios de nuestras aplicaciones con email y password, login y signup con redes sociales, correos electrónicos de recuperación de contraseña, entre muchas otras cosas geniales 🚫🏁 ✖️ ✔️.
	* Cloud Storage para almacenar archivos estáticos 😮.
	* Cloud Messaging para enviar notificaciones 📩.
	* Firebase Hosting para desplegar nuestras aplicaciones _(hasta dónde tengo entendido son despliegues común y corrientes)_ y Cloud Functions para despliegues sin programar el código backend de la aplicación 🙃🆙.
	
	

	* **Disando7** [545989] (2)

		El último punto, que dice, sin programar el código backend de la aplicación, no es tan así. Ya que en Cloud Functions sería parte del backend de nuestra app y obviamente hay que programarlo, pero de igual manera Firebase se encarga casi que el 100% del backend de nuestra app. Genial 😉

* **Brayan Mamani** (2) [550298](https://platzi.com/comentario/550298/) 

	Excelente un proyecto Android con Firebase y Kotlin.

* **Juan David Castro (Platzi)** (2) [545988](https://platzi.com/comentario/545988/) 

	Notas de la clase:
	
	* Todas _(bueno, casi todas :sweat_smiles)_ las aplicaciones necesitan programar código backend para sus diferentes funcionalidades: guardar info en bases de datos, almacenar archivos, autenticar usuarios, etc 😮.
	* Firebase en un _BAAS (Backend as a Service)_. Google se encargará de crear y administrar las funciones, bases de datos e infraestructura de nuestra aplicación. Nuestra tarea sólo será trabajar algunas configuraciones en su plataforma _([firebase.google.com](http://firebase.google.com))_ y construir nuestra aplicación 😱🎉.
	* Nos permite construir aplicaciones para [Android](https://platzi.com/clases/firebase/), [IOS](https://platzi.com/clases/apps-ios/) y para [Web](https://platzi.com/clases/firebase-web).
	* Toda esta infraestructura funciona con Google Cloud, así que, tenemos muchas posibilidades para escalar nuestras aplicaciones 👌.
	
	

* **Valeria Calcina Cisneros** (1) [1039032](https://platzi.com/comentario/1039032/) 

	Me servirá de mucho no tener que preocuparme tanto por la infraestructura 😄

* **Alexander Mateo** (1) [738710](https://platzi.com/comentario/738710/) 

	Excelente! 😄

* **Andres Felipe Jacquin Burgos** (1) [729015](https://platzi.com/comentario/729015/) 

	Excelente todo lo que se puede hacer con FIrebase

## 0020. Configuración de Firebase para Android. [18727](https://platzi.com/clases/1532-firestore/18727-configuracion-de-firebase-para-android/)

### Descripción:


Nuestro proyecto será [CryptoTrader](https://github.com/sancarbar/android-firestore-platzi-crypto-trade): una aplicación de criptomonedas que usará un servicio de autenticación y actualizará los datos de nuestras criptomonedas en tiempo real.

### Links:

* [GitHub - sancarbar/android-firestore-platzi-crypto-trade: Proyecto base para el curso de Platzi sobre Android Realtime usando Firestore](https://github.com/sancarbar/android-firestore-platzi-crypto-trade)

* [Sign in - Google Accounts](https://console.firebase.google.com/)

### Comentarios:

* **Brayan Mamani** (5) [550479](https://platzi.com/comentario/550479/) 

	Adiós Java, bienvenido Kotlin para mis futuras aplicaciones.

* **joseadrian** (2) [55900](https://platzi.com/comentario/546641/) 
El código está en kotlin?, considero que primero debieron liberar el curso de kotlin para reforzar el conocimiento.

	* **aragonesteban (Platzi)** [55900] (5)

		Puedes tomar el Curso de Kotlin para Android para que tengas bases sobre el lenguaje de programación.
		
		<https://platzi.com/clases/kotlin-android/>

* **Loui Recio Izaguirre** (1) [1001088](https://platzi.com/comentario/1001088/) 

	Hermoso pero me causa conflicto no ver el thema Darcula, corazón si no te gustan los temas blancos

* **Victor_Flores2206** (1) [549394](https://platzi.com/comentario/549394/) 

	bueno a aprender kotlin

* **joseadrian** (1) [546641](https://platzi.com/comentario/546641/) 

	El código está en kotlin?, considero que primero debieron liberar el curso de kotlin para reforzar el conocimiento.

	* **aragonesteban (Platzi)** [546641] (5)

		Puedes tomar el Curso de Kotlin para Android para que tengas bases sobre el lenguaje de programación.
		
		<https://platzi.com/clases/kotlin-android/>

* **Santiago Alejandro Moreno** (1) [82056](https://platzi.com/comentario/996419/) 
me aparece “License for package Android SDK Platform 28 not accepte” no se que pueda ser :c

* **Engel_1010** (1) [76563](https://platzi.com/comentario/889452/) 
No me funciona el proyecto, me sale este error: Manifest merger failed : uses-sdk:minSdkVersion 15 cannot be smaller than version 16 decl...

	* **Erik Ochoa** [76563] (1)

		Este es un problema de incompatibilidad de versiones, cambia la versión del sdk de tu proyecto en tu archivo `manifest` por la versión 16 tal como lo sugiere el error.
		
		Aquí documentación sobre el [<use-sdk>](https://developer.android.com/guide/topics/manifest/uses-sdk-element).

* **Jonathan Steven Bernal Perilla** (0) [70252](https://platzi.com/comentario/771561/) 
Excelente, me ayuda a reforzar lo aprendido en el curso de kotlin para android

	* **DAVID8512** [70252] (2)

		Te funciono el proyecto de Github? lograste conectar la aplicacion a Firestore?

# Autenticación Anónima [3745]

## 0030. Autenticación anónima con Firebase [18728](https://platzi.com/clases/1532-firestore/18728-autenticacion-anonima-con-firebase/)

### Descripción:


Vamos a implementar la autenticación anónima de Firebase Authentication para crear cuentas temporales que pueden acceder a datos protegidos por reglas de seguridad.

Para importar la librería de Firebase Authentication debes copiar y pegar el link de autenticación en la sección de dependencias del archivo `build.gradle` y sincronizar tu proyecto para descargar la librería para utilizarla en nuestro proyecto:
``` 
    dependencies: {
            ...
            implementation 'com.google.firebase:firebase-core:16.0.7'
            implementation 'com.google.firebase:firebase-auth:16.1.0'
            ...
    }
    
```

Recuerda activar el método de autenticación anónima desde la consola de Firebase para que los usuarios queden registrados y los podamos controlar.

### Comentarios:

* **Disando7** (4) [720855](https://platzi.com/comentario/720855/) 

	Aun sin estar autenticado lo lleva a la siguiente actividad?.  
	La razón es que el profe olvido quitar o comentar lo que estaba después del listener “startMainActivity(username)”

# Entendiendo Cloud Firestore [3746]

## 0040. Conociendo el Modelo de Datos de Firestore [18729](https://platzi.com/clases/1532-firestore/18729-conociendo-el-modelo-de-datos-de-firestore/)

### Descripción:


Cloud Firestore es una base de datos no relacional muy flexible.

Tenemos un modelo de datos basado en dos tipos de objetos: Los **Documentos** (diccionarios de datos que podemos guardar y trabajar en forma de llaves y valores) y **Colecciones** (conjuntos de documentos).

Los documentos pueden ser sencillos o complejos, es decir, con llaves y valores y modelos de datos más avanzados; listas y objetos con más documentos en forma de llaves y valores o, incluso, más listas de documentos.

También podemos trabajar con **referencias** para acceder a nuestros documentos con “atajos” y realizar operaciones.

Recuerda que entre menos complejo es el modelo de datos de tu base de datos mejor será su desempeño.

### Links:

* [https://en.bitcoin.it/w/images/en/2/29/BC_Logo_.png](https://en.bitcoin.it/w/images/en/2/29/BC_Logo_.png)

* [https://cdn.stateofthedapps.com/dapps/ethxeth/product_image_ethxeth_e26173ff274bcc8b6d6721a0dae2587384ba17506910bb0c186c7843dd33723b_opti.png](https://cdn.stateofthedapps.com/dapps/ethxeth/product_image_ethxeth_e26173ff274bcc8b6d6721a0dae2587384ba17506910bb0c186c7843dd33723b_opti.png)

* [https://cdn4.iconfinder.com/data/icons/crypto-currency-and-coin-2/256/neo_neocoin-512.png](https://cdn4.iconfinder.com/data/icons/crypto-currency-and-coin-2/256/neo_neocoin-512.png)

### Comentarios:

* **Disando7** (2) [720865](https://platzi.com/comentario/720865/) 

	Esta es la [documentación](https://firebase.google.com/docs/firestore/data-model?authuser=0) oficial de cloud firestore, que trata sobre el modelo de datos que se maneja

* **Fernando Díaz Meza** (1) [72122](https://platzi.com/comentario/810816/) 
donde se encuentra los ejemplo ?

	* **Juan David Castro (Platzi)** [72122] (1)

		¡Hola! ¿A qué ejemplos te refieres? He visto la clase y no encuentro que el profesor haya mencionado algún ejemplo de algo en este clase.

## 0050. Gestión de Índices en Firestore [18730](https://platzi.com/clases/1532-firestore/18730-gestion-de-indices-en-firestore/)

### Descripción:


Los **índices** son la forma que Firebase y muchas otras bases de datos usan para realizar búsquedas y consultas de forma eficiente y escalable. Gracias a los índices nos ahorramos el tiempo y trabajo al evitar buscar nuestra información dato por dato en toda nuestra base de datos, que resultaría algo lento y poco escalable.

**Tipos de índices** :

* **Campo único** : Almacenan el orden de todos los documentos en una colección de un sólo campo. Podemos realizar consultas con los comparadores `<`, `<=`, `==`, `>=` y `array_contains`.
* **Compuestos** : Almacenan el orden de todos los documentos en una colección que contiene _subcampos_. Usamos los mismos comparadores pero podemos hacer operaciones más complejas.



Los **modos** nos ayudan a organizar nuestros índices de forma ascendente, descendente o con el modo `array_contains` para comprobar la existencia de nuestros índices en una cierta colección.

También es muy importante controlar la **auto indexación** , algunos índices que Firestore crea por defecto de la siguiente manera:

* **Campos simples** (no colecciones): Dos índices de campo único (ascendente y descendente).
* **Diccionarios** : Dos índices de campo único (ascendente y descendente) por cada uno de los subcampos.
* **Colecciones** : Un índice de tipo `array_contains`.



### Links:

* [
  Gestión de Índices en Firestore en Curso de Firestore para Android
](https://platzi.com/clases/1532-firestore/18730-gestion-de-indices-en-firestore/)

### Comentarios:

* **Juan David Castro (Platzi)** (2) [545990](https://platzi.com/comentario/545990/) 

	Los **índices** son la capacidad de consultar nuestra información mucho más rápido: calculamos la ubicación exacta de nuestro contenido en vez de recorrer la base de datos hasta encontrar la información que buscamos.
	
	Gracias a los índices podemos realizar búsquedas especiales con múltiples filtros y ordenamientos a las peticiones de nuestra aplicación con Firestore sin afectar la _performance_ y la velocidad de nuestra aplicación.

* **Juan David Castro (Platzi)** (1) [545992](https://platzi.com/comentario/545992/) 

	Ejemplos de índices de campo único:
	``` 
	    citiesRef.where("name", "==", "Bogotá")
	    citiesRef.where("population", "<", "100000")
	    citiesRef.where("regions", "array_contains", "Amazonas")
	    
	```
	
	Ejemplos de índices compuestos:
	``` 
	    citiesRef.where("country", "==", "Colombia").orderBy("population", "asc")
	    citiesRef.where("population", "<", "100000").where("population", "<", 3000)
	    citiesRef.where("regions", "array_contains", "Amazonas").where("population", ">", 3000)
	    
	```

# Creación y Gestión de Datos [3747]

## 0060. Creación y gestión de datos en Firestore [18731](https://platzi.com/clases/1532-firestore/18731-creacion-y-gestion-de-datos-en-firestore/)

### Descripción:


### Comentarios:

* **joseadrian** (2) [547505](https://platzi.com/comentario/547505/) 

	Ese campo se agrega solo a ese documento, no a toda la colección, cierto?

	* **Brayan Mamani** [547505] (1)

		Supuestamente si.

	* **Daniel Esteves** [547505] (1)

		Exactamente así, solo se agregará a el documento que se esté escribiendo pero no a los demás

## 0070. Estructura y creación de Datos en Firestore Practica [18732](https://platzi.com/clases/1532-firestore/18732-estructura-y-creacion-de-datos-en-firestore-practi/)

### Descripción:


Recuerda añadir el módulo de implementación de Firestore en la sección de dependencias del archivo `build.gradle`:
``` 
    dependencies: {
            ...
            implementation 'com.google.firebase:firebase-core:16.0.7'
            implementation 'com.google.firebase:firebase-auth:16.1.0'
            implementation 'com.google.firebase:firebase-firestore:18.1.0'
            ...
    }
    
```

### Comentarios:

## 0080. Estructura y creación de Datos en Firestore Practica con Login Activity [18733](https://platzi.com/clases/1532-firestore/18733-estructura-y-creacion-de-datos-en-firestore-practi/)

### Descripción:


### Comentarios:

* **Juan David Castro (Platzi)** (3) [545994](https://platzi.com/comentario/545994/) 

	Actualización rápida de las reglas de seguridad para permitir el acceso y la escritura de la base de datos cuando queremos crear la colección y los documentos de nuestros usuarios:
	``` 
	    service cloud.firestore {
	      match /databases/{database}/documents {
	        match /{document=**} {
	          allow read, write: iftrue
	        }
	      }
	    }
	    
	```

## 0090. Transacciones y Escritura Batch en Firestore [18734](https://platzi.com/clases/1532-firestore/18734-transacciones-y-escritura-batch-en-firestore/)

### Descripción:


Las **transacciones** son un conjunto de múltiples operaciones de lectura y escritura que podemos agrupar y ejecutar en una sola transacción para realizar cualquier trabajo sobre uno o más documentos de una colección.

La **Escritura en Batch** o escritura por lotes también nos permite agrupar y ejecutar múltiples operaciones pero solo si son de escritura (crear, editar o eliminar información).

Estas dos herramientas funcionan muy bien cuando queremos hacer migración de datos o muchas operaciones simultáneas de escritura sobre una misma colección.

### Comentarios:

* **Juan David Castro (Platzi)** (2) [545997](https://platzi.com/comentario/545997/) 

	Ejemplo de Transacciones:
	``` 
	    val bogDocRef = db.collection("cities").document("BOG")
	    
	    db.runTransaction { transaction ->
	      val snapshot = transaction.get(bogDocRef)
	      val newPopulation = snapshot.getDouble("population")!! + 1
	      transaction.update(bogDocRef, "population", newPopulation)
	      null
	    }
	      .addOnSuccessListener { Log.d(TAG, "Transaction success!") }
	      .addOnFailureListener { e -> Log.w(TAG, "Transaction failure.!", e) }
	    
	```
	
	Ejemplo de Escritura en Batch:
	``` 
	    val batch = db.batch()
	    val bogotaRef = db.collection("cities").document("BOG")
	    
	    batch.set(bogotaRef, City())
	    batch.update(bogotaRef, "population", 1000000L)
	    batch.delete(bogotaRef)
	    
	    batch.commit().addOnCompleteListener
	    
	```

	* **jquiroga** [545997] (1)

		Cual es la sentencia que instancia la variable “db” ?

	* **Juan David Castro (Platzi)** [545997] (1)

		Esta:
		``` 
		    firebase.initializeApp({
		      apiKey: '### FIREBASE API KEY ###',
		      authDomain: '### FIREBASE AUTH DOMAIN ###',
		      projectId: '### CLOUD FIRESTORE PROJECT ID ###'
		    });
		    
		    var db = firebase.firestore();
		    
		```

* **Juan David Castro (Platzi)** (1) [545995](https://platzi.com/comentario/545995/) 

	> Cloud Firestore admite operaciones atómicas para la lectura y la escritura de datos. En un conjunto de operaciones atómicas, todas las operaciones se aplican de manera correcta o no se aplica ninguna de ellas. Cada transacción o escritura en lote puede escribir en un máximo de 500 documentos.
	> 
	> * **Transacciones** : una transacción es un conjunto de operaciones de lectura y de escritura en uno o más documentos.
	> * **Escrituras en lotes** : una escritura en lotes es un conjunto de operaciones de escritura en uno o más documentos.
	> 
	
	
	* [Transacciones y escrituras por lotes en Firestore - Firebase Docs](https://firebase.google.com/docs/firestore/manage-data/transactions?hl=es-419)
	
	

# Lectura de Datos [3748]

## 0100. Lectura de Documentos de Firestore [18735](https://platzi.com/clases/1532-firestore/18735-lectura-de-documentos-de-firestore/)

### Descripción:


En esta clase el profesor Santiago Carrillo nos explica cómo realizar la lectura de nuestros documentos en Firebase.

Firebase es una tecnología de Google para crear aplicaciones móviles: nos ayuda desarrollar nuestros productos sin tener que preocuparnos por la infraestructura. Firestore es una base de datos no relacional muy flexible que funciona a partir de documentos y colecciones. Existen dos formas de leer datos con Firestore: de forma directa (llamando a un método para obtener los datos) y observando los datos, donde debemos asignar un listener para ser notificados cuando hay modificaciones de los datos (funciona muy bien para construir aplicaciones en tiempo real).

Santiago Carrillo es Google Developer Expert en Android y tiene más de 7 años desarrollando aplicaciones nativas.

### Comentarios:

## 0110. Consultas en Firestore Sencillas y Compuestas, Orden y  Límites de Datos [18736](https://platzi.com/clases/1532-firestore/18736-consultas-en-firestore-sencillas-y-compuestas-orde/)

### Descripción:


Firestore nos proporciona muchas formas de consultar los documentos de nuestras bases de datos: consultas sencillas para ordenar o filtrar nuestros documentos a partir de un valor (por ejemplo, si `name` es igual a `Bogotá`) o consultas compuestas si necesitamos especificar más de un filtro (por ejemplo, si `name` es igual a `Bogotá` y `country` es igual a `Colombia`).

Tipos de filtros para nuestras consultas:

* `.whereEqualTo("campo-que-debemos-comparar", "valor que debe tener")`
* `.whereLessThan("campo-que-debemos-comparar", NúmeroMáximo)`
* `.whereGreaterThan("campo-que-debemos-comparar", NúmeroMínimo)`
* `.whereArrayContains("campo-que-debemos-comparar", "valor que debe tener nuestro array")`
* Otros filtros: `.whereLessThanOrEqualTo`, `whereGreaterThanOrEqualTo`, `orderBy`, `limit`, entre otros



Sin embargo, nuestras consultas compuestas deben seguir algunas reglas: no podemos filtrar rangos de valores en campos diferentes.

✅ Ejemplos correctos:

* Dos filtros de igualdad en campos diferentes:  
`.whereEqualTo("country", "Colombia").whereEqualTo("capital", true)`

* Un filtro de igualdad y otro de rango en campos diferentes:  
`.whereEqualTo("country", "Colombia").whereLessThan("population", 100000)`

* Un filtro de rango y otro de ordenamiento con el mismo campo:  
`.whereGreaterThan("population", 100000).orderBy("population").limit(10)`




???? Ejemplos incorrectos:

* Dos filtros de rango en campos diferentes  
`.whereGreaterThan("population", 100000).whereLessThan("antiquity", 100)`

* Un filtro de rango y otro de ordenamiento en campos diferentes:  
`.whereGreaterThan("population", 100000).orderBy("country")`




### Comentarios:

* **Juan David Castro (Platzi)** (1) [545998](https://platzi.com/comentario/545998/) 

	* [Ejemplos y limitaciones de Consultas Simples y Compuestas en Cloud Firestore - Firebase Docs](https://firebase.google.com/docs/firestore/query-data/queries?hl=es-419)
	* [Paginar datos con cursores de consulta - Firebase Docs](https://firebase.google.com/docs/firestore/query-data/query-cursors?hl=es-419)
	
	

## 0120. Acceso a Datos Offline [18737](https://platzi.com/clases/1532-firestore/18737-acceso-a-datos-offline/)

### Descripción:


Firestore nos permite implementar la persistencia de datos en nuestras aplicaciones cuando nuestros dispositivos no tienen acceso a internet. Firestore habilita estas características por defecto pero podemos usar el siguiente código:
``` 
    val settings = FirebaseFirestoreSettings.Builder().setPersistenceEnabled(true).build()
    
    db.firestoreSettings = settings
    
```

### Comentarios:

* **Juan David Castro (Platzi)** (2) [545999](https://platzi.com/comentario/545999/) 

	En JavaScript (Firebase para Web) la persistencia de datos offline NO viene habilitada por defecto y debemos activarla con el siguiente código:
	``` 
	    firebase.firestore().enablePersistence()
	    
	```
	
	* [Enable offline data en JavaScript - Firebase Docs](https://firebase.google.com/docs/firestore/manage-data/enable-offline)
	* [Offline Capabilities in JavaScript - Firebase Docs](https://firebase.google.com/docs/database/web/offline-capabilities)
	* [Enabling Offline Capabilities on Android - Firebase Docs](https://firebase.google.com/docs/database/android/offline-capabilities)
	
	

# Reglas y Seguridad [3749]

## 0130. Reglas de Seguridad en Firestore [18738](https://platzi.com/clases/1532-firestore/18738-reglas-de-seguridad-en-firestore/)

### Descripción:


Las reglas de seguridad nos ayudan a limitar el acceso de nuestros datos a los usuarios o administradores correctos sin necesidad de escribir código de autorización y autenticación para el servidor.

Estas reglas las usamos para determinar quién tiene permisos de lectura o escritura a la información de nuestras bases de datos, podemos restringir el acceso a documentos específicos o a toda una colección de documentos dependiendo de nuestra lógica de negocios.

Todas las reglas de seguridad se crean usando la declaración `match` para identificar los documentos de la base de datos y permite el acceso o no a estos datos con la expresión `allow`. Recuerda que podemos crear nuestras reglas desde la consola de Firebase o con la herramienta de [Firebase CLI](https://firebase.google.com/docs/cli) creando un archivo `.rules` y desplegandolo a Firebase con el comando `firebase deploy --only firebase:rules`:

Por ejemplo:
``` 
    service cloud.firestore {
      match /databases/{database}/documents {
          match /<some_path>/ {
            allow read, write: if <some_condition>;
          }
      }
    }
    
```

### Links:

* [https://firebase.google.com/docs/cli](https://firebase.google.com/docs/cli)

### Comentarios:

* **Juan David Castro (Platzi)** (1) [546002](https://platzi.com/comentario/546002/) 

	㊙️👮 **Ejemplos** de reglas de seguridad en Firestore 🔶
	
	* Permitir acceso de lectura y escritura en todos los documentos a cualquier usuario autenticado:
	
	
	``` 
	    service cloud.firestore {
	      match /databases/{database}/documents {
	        match /{document=**} {
	          allow read, write: if request.auth.id != null;
	        }
	      }
	    }
	    
	```
	
	* Denegar el acceso de lectura y escritura a todos los usuarios en cualquier condición:
	
	
	``` 
	    service cloud.firestore {
	      match /databases/{database}/documents {
	        match /{document=**} {
	          allow read, write: iffalse;
	        }
	      }
	    }
	    
	```
	
	* Permitir el acceso de lectura y escritura a todos los usuarios en cualquier condición ( **!NUNCA USES ESTA REGLA EN PRODUCCIÓN!** ):
	
	
	``` 
	    service cloud.firestore {
	      match /databases/{database}/documents {
	        match /{document=**} {
	          allow read, write: iftrue;
	        }
	      }
	    }
	    
	```
	
	* Permitir la escritura del documento de usuarios solo si el usuarios que queremos modificar es el mismo usuario que intenta modificar su información:
	
	
	``` 
	    service cloud.firestore {
	      match /databases/{database}/documents {
	        match /users {
	          allow read, write: if request.resource.data.username == resource.data.username;
	        }
	      }
	    }
	    
	```

* **Juan David Castro (Platzi)** (1) [546001](https://platzi.com/comentario/546001/) 

	* [Reglas de seguridad en Firebase - Platzi en YouTube](https://youtu.be/4H4RtemB9oE)
	* [Reglas de Seguridad de Firebase: ejemplo práctico](https://platzi.com/blog/reglas-de-seguridad-de-firebase-ejemplo-practico/)
	
	

* **Juan David Castro (Platzi)** (1) [546000](https://platzi.com/comentario/546000/) 

	La línea de la expresión allow siempre debe terminar con punto y coma (;).

## 0140. Estructurando reglas de seguridad en Firestore [18739](https://platzi.com/clases/1532-firestore/18739-estructurando-reglas-de-seguridad-en-firestore/)

### Descripción:


Las reglas de seguridad también nos permiten restringir o aplicar alguna de nuestras reglas a acciones, documentos y colecciones específicas, podemos permitir lectura pero no la escritura, la creación pero no la actualización y borrado, entre otras:
``` 
    match /<colecciones-o-documentos> {
      // Escritura de documentos no existentes
      allow create: if <condition>;
      // Escritura de documentos existentes
      allow update: if <condition>;
      // Eliminación de documentos
      allow delete: if <condition>;
    }
    
```

También podemos definir funciones personalizadas para reutilizar condiciones en diferentes reglas de seguridad:
``` 
    service cloud.firestore {
      match /databases/{database}/documents {
        function signedInOrPublic() {
          return request.auth.uid != null || resource.data.visibility == 'public';
        }
    
        match /cities/{city} {
          allow read, write: if signedInOrPublic();
        }
    
        match /users/{user} {
          allow read, write: if signedInOrPublic();
        }
      }
    }
    
```

### Links:

* [https://firebase.google.com/docs/firestore/security/rules-structure](https://firebase.google.com/docs/firestore/security/rules-structure)

* [Writing conditions for Cloud Firestore Security Rules  |  Firebase](https://firebase.google.com/docs/firestore/security/rules-conditions)

### Comentarios:

* **Juan David Castro (Platzi)** (2) [546006](https://platzi.com/comentario/546006/) 

	Reglas de seguridad para el control de usuarios:
	``` 
	    service cloud.firestore {
	      match /databases/{database}/documents {
	        match /users/{userId} {
	          // Permite modificar la información de los usuarios si el userId del modificador es el mismo del usuario a modificar
	          allow read, update, delete: if request.auth.uid == userID;
	          // Permite crear usuarios si estamos autenticados porque, si el usuario no existe, no podemos verificar los IDs
	          allow create: if request.auth.uid != null;
	        }
	      }
	    }
	    
	```
	
	Reglas de seguridad para verificar la actualización de las ciudades:
	``` 
	    service cloud.firestore {
	      match /databases/{database}/documents {
	        match /cities/{city} {
	          // Permite modificar la información de las ciudades si su población es mayor a xx y sigue teniendo el mismo nombre
	          allow update: if request.resource.data.population > 0
	            && request.resource.data.name == resource.data.name;
	        }
	      }
	    }
	    
	```
	
	Permitir que la información de cada documento defina si puede ser leída o actualizada:
	``` 
	    service cloud.firestore {
	      match /databases/{database}/documents {
	        match /cities/{city} {
	          // Podemos definir desde la creación del documento si puede ser leída o editada por otros usuarios
	          allow read: resource.data.visibility == "public";
	        }
	      }
	    }
	    
	```

## 0150. Configurando y Probando Reglas de Seguridad en Firestore [18740](https://platzi.com/clases/1532-firestore/18740-configurando-y-probando-reglas-de-seguridad-en-fir/)

### Descripción:


Firebase nos ofrece un simulador, una herramienta para comprobar que nuestras reglas de seguridad permiten o restringen el acceso a nuestros datos de manera correcta.

Sin embargo, recuerda que no podemos confiar al 100% en este simulador, la mejor forma de comprobar que nuestras reglas realmente funcionan como esperamos es programando el código de nuestras aplicaciones y probando su funcionamiento.

### Links:

* [Fix insecure rules  |  Firebase](https://firebase.google.com/docs/firestore/security/insecure-rules)

* [Test your Cloud Firestore Security Rules  |  Firebase](https://firebase.google.com/docs/firestore/security/test-rules-emulator)

### Comentarios:

* **Juan David Castro (Platzi)** (2) [546008](https://platzi.com/comentario/546008/) 

	* [Reglas de Seguridad Avanzadas con Firebase y Firestore](https://platzi.com/blog/reglas-de-seguridad-avanzadas-con-firebase-y-firestore/)
	
	

# Trading App en Realtime [3750]

## 0160. Configuración Adapter Criptomonedas [18741](https://platzi.com/clases/1532-firestore/18741-configuracion-adapter-criptomonedas/)

### Descripción:


Dirección que se menciona durante la clase para agregar al proyecto

‘com.squareup.picasso:picasso:2.71828’

### Links:

* [Picasso](https://square.github.io/picasso)

### Comentarios:

* **Juan David Castro (Platzi)** (1) [546009](https://platzi.com/comentario/546009/) 

	<https://square.github.io/picasso>

## 0170. Configuración RecyclerView Criptomonedas [18742](https://platzi.com/clases/1532-firestore/18742-configuracion-recyclerview-criptomonedas/)

### Descripción:


### Comentarios:

## 0180. Panel Balance Criptomonedas Usuario [18743](https://platzi.com/clases/1532-firestore/18743-panel-balance-criptomonedas-usuario/)

### Descripción:


Enlace para obtener el Layout del ejercicio:

<https://raw.githubusercontent.com/sancarbar/android-firestore-platzi-crypto-trade/9.Panel-balance-criptomonedas-usuario/app/src/main/res/layout/coin_info.xml>

### Links:

* [https://raw.githubusercontent.com/sancarbar/android-firestore-platzi-crypto-trade/9.Panel-balance-criptomonedas-usuario/app/src/main/res/layout/coin_info.xml](https://raw.githubusercontent.com/sancarbar/android-firestore-platzi-crypto-trade/9.Panel-balance-criptomonedas-usuario/app/src/main/res/layout/coin_info.xml)

### Comentarios:

## 0190. Actualizaciones Realtime Criptomonedas [18744](https://platzi.com/clases/1532-firestore/18744-actualizaciones-realtime-criptomonedas/)

### Descripción:


### Comentarios:

## 0200. Generación Aleatoria de Criptomonedas [18745](https://platzi.com/clases/1532-firestore/18745-generacion-aleatoria-de-criptomonedas/)

### Descripción:


### Comentarios:

* **Sergio0017** (1) [1002662](https://platzi.com/comentario/1002662/) 

	Posiblemente me equivoque pero me parece que hay un error en una pregunta del examen, la pregunta dice, que cuales de los siguientes datos no pertenecen a firestore y todas las posibles respuestas son datos que si pertenecen

# Repaso [3751]

## 0210. Repaso conceptos principales del curso [18746](https://platzi.com/clases/1532-firestore/18746-repaso-conceptos-principales-del-curso/)

### Descripción:


¡Felicitaciones por terminar el Curso de Firestore para Android en Platzi!

Aprendimos qué es Firebase y cómo nos ayuda a crear aplicaciones más rápidas y seguras sin preocuparnos de la infraestructura, implementamos la autenticación anónima con Firebase Authentication y usamos todas las características de Cloud Firestore: Tipos de Consultas, Estructuras y Modelado de Datos, Índices y sus buenas prácticas, Reglas de Seguridad Avanzadas y Lectura + Actualización de datos en Tiempo Real.

Recuerda resolver los ejercicios, completar el examen, darle 5 estrellas al profesor y dejar todas tus dudas o comentarios en la sección de discusiones.

### Comentarios:

