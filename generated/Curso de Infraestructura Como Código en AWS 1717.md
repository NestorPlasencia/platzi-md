[Curso de Infraestructura Como Código en AWS 1717](https://platzi.com/cursos/iaac-aws)

# Importancia de la Infraestructura como código [4694]

## 0010. Bienvenido al curso [23536](https://platzi.com/clases/1717-iaac-aws/23536-bienvenido-al-curso/)

### Descripción:


### Comentarios:

* **davidegc** (7) [800375](https://platzi.com/comentario/800375/) 

	esta muy bajo el volumen de este vídeo

* **Dante Castillo Z.** (1) [1062283](https://platzi.com/comentario/1062283/) 

	se ve interesante este curso…

* **Brayan Mamani** (1) [800994](https://platzi.com/comentario/800994/) 

	¡Un curso interesante!

* **Ronnie Moncayo** (1) [799164](https://platzi.com/comentario/799164/) 

	Excelente curso!

* **carlosextra1** (1) [798064](https://platzi.com/comentario/798064/) 

	ok

## 0020. Cómo desplegar infraestructura en Cloud [23537](https://platzi.com/clases/1717-iaac-aws/23537-como-desplegar-infraestructura-en-cloud/)

### Descripción:


### Comentarios:

* **Andres Alberto Ariza Mantilla** (2) [963022](https://platzi.com/comentario/963022/) 

	Buenos dias, tengo una duda, existe posibilidad de que el origen de un fallo que tumba un servidor se encuentre en la plantilla que lo despliega, a lo que voy es a lo siguiente, no sería bueno dedicar un tiempo a hacer un diagnostico del error que tumba el servidor antes de desplegar de nuevo, esto para descartar que el origen del error provenga desde la misma configuración inicial? o qué recomendarías para evitar que esto llegara a pasar?

* **Cristian David Franco Garcia** (2) [797378](https://platzi.com/comentario/797378/) 

	Buenas noches,
	
	Si vuelvo a desplegar la infraestructura:
	
	**1.** ¿debo indicar que se eliminen los recursos creados previamente?
	
	**2.** ¿Se eliminan todos los recursos, o solo los recursos donde hay cambios?

	* **Carlos Andrés Zambrano Barrera** [797378] (1)

		1- si desplegaste un template con 5 recursos, lo sobre-escribiste y le quitaste 2 recursos, el template toma el diferencial, te deja 3 recursos y te elimina los 2 que especificaste.
		
		2- Depende de lo que estes haciendo, si borras todo el stack se borran todos los recursos.

* **Alexander  Silvera** (1) [802740](https://platzi.com/comentario/802740/) 

	Buenas tardes, al utilizar muchos servicios el costo de la infraestructura no es mayor?? O sea cuando conviene realizar este tipo de infraestructura?? Es aplicable a proyectos pequeños o solo a grandes?? Saludos y gracias.

	* **Carlos Andrés Zambrano Barrera** [802740] (2)

		Es cambiar la forma de trabajar, el costo de CFN es 0! pero si haces los despliegues asi, tendrás mayor control de los recursos, trazabilidad y después volver a crearlos será muchísimo más fácil. Yo lo veo como una herramienta para cualquier tipo de proyecto!

## 0030. Herramientas para desplegar infraestructura como código [23538](https://platzi.com/clases/1717-iaac-aws/23538-herramientas-para-desplegar-infraestructura-como-c/)

### Descripción:


### Links:

* [Curso de Infraestructura Como Código con Terraform](https://platzi.com/clases/devops-terraform/)

### Comentarios:

* **jschenfeld** (3) [818246](https://platzi.com/comentario/818246/) 

	Herramientas:
	
	  1. **Terra** : despliegues multi cloud, posee una version open source y otra enterprise
	  2. **Pulumi** : despligues multi cloud, podes sacar ventajas tus conocimientos en un lenguaje
	  3. **Serverless Framework** : para el despliegue de Lambdas, dynamoDb, api gateway, s3, kinesis
	  4. **SDK** : provista diferentes lenguajes, para python se llama boto3
	  5. **CDK** (Cloud Development Kit): diferencia con el sdk, es que no va usar librerias particulares, sino que dentro del mismo codigo python vamos a llamar a los recursos y crealos. Por detras cdk va a generar un template de CFN.
	  6. **AWS SAM** (Serverless Aplication Model): para el despliegue de Lambdas, dynamoDb, api gateway, kinesis. Cambia la definición del recurso, para desplegar una lambda en CFN se declara como “AWS::Lambda::Function” y en SAM “AWS::Serverless::Function”
	
	

## 0040. Introducción y ventajas de usar Cloudformation [23539](https://platzi.com/clases/1717-iaac-aws/23539-introduccion-y-ventajas-de-usar-cloudformation/)

### Descripción:


### Comentarios:

* **Jean Carlos Nuñez Hernandez** (1) [797321](https://platzi.com/comentario/797321/) 

	Cloudformation esta buenisomo a usarlo!!

	* **Carlos Andrés Zambrano Barrera** [797321] (1)

		Es muy bueno!! Usalo y me cuentas cómo te va! Te ayudo con lo que requieras!

## 0050. Laboratorio # 1  explorando la consola de Cloudformation [23533](https://platzi.com/clases/1717-iaac-aws/23533-laboratorio-1-explorando-la-consola-de-cloudformat/)

### Descripción:


### Comentarios:

* **Jean Carlos Nuñez Hernandez** (2) [797329](https://platzi.com/comentario/797329/) 

	Waaao!! ahora me pongo con de una vez para sacarle provecho

# Funcionalidades y características en Cloudformation [4695]

## 0060. Anatomía de un template en Cloudformation [23534](https://platzi.com/clases/1717-iaac-aws/23534-anatomia-de-un-template-en-cloudformation/)

### Descripción:


### Comentarios:

## 0070. Clase práctica creación de un template [23535](https://platzi.com/clases/1717-iaac-aws/23535-clase-practica-creacion-de-un-template/)

### Descripción:


### Links:

* [Curso de Bases de Datos en AWS](https://platzi.com/clases/db-aws/)

### Comentarios:

* **nicolas-garcia-puerta** (1) [800962](https://platzi.com/comentario/800962/) 

	No se escucha, mas volumen

	* **Luigui Mario** [800962] (1)

		Cierto, deberian aumentar el volumen y volver a subir el video, se escucha muy bajo

	* **Erik Ochoa** [800962] (2)

		Gracias por el reporte, ya se ha corregido el volumen para esta clase. 😃

## 0080. Despliegue del template en Cloudformation [23540](https://platzi.com/clases/1717-iaac-aws/23540-despliegue-del-template-en-cloudformation/)

### Descripción:


### Comentarios:

* **Andres Alberto Ariza Mantilla** (1) [981125](https://platzi.com/comentario/981125/) 

	El volumen del video … suena muy muy pasito

	* **Erik Ochoa** [981125] (1)

		Los problemas de audio de esta clase han sido solucionados, por favor vuelve a probar.

* **nicolas-garcia-puerta** (1) [814010](https://platzi.com/comentario/814010/) 

	Las clases de Carlos son excelentes pero estan fallando con el audio

	* **Erik Ochoa** [814010] (1)

		Los problemas de audio de esta clase han sido solucionados, por favor vuelve a probar.

* **ceruizdev** (1) [802611](https://platzi.com/comentario/802611/) 

	Me arrojaba un error de ROLL_BACK ya que me habia quedado “Hash” en minuscula debe ser mayuscula  
	KeySchema:  
	\- AttributeName: !Ref DynamoAtributo  
	KeyType: HASH

	* **Carlos Andrés Zambrano Barrera** [802611] (1)

		Oka, pero pudiste desplegar adecuadamente?

	* **ceruizdev** [802611] (1)

		Sip sin mas problema!

## 0090. Caracteristícas finales del template en Cloudformation [23541](https://platzi.com/clases/1717-iaac-aws/23541-caracteristicas-finales-del-template-en-cloudforma/)

### Descripción:


### Comentarios:

* **Nestor Alfonso Portela Rincón** (2) [817867](https://platzi.com/comentario/817867/) 

	Excelente curso y muy interesante esta forma de desplegar recursos en AWS con código.

## 0100. Stacks características y despliegue [23542](https://platzi.com/clases/1717-iaac-aws/23542-stacks-caracteristicas-y-despliegue/)

### Descripción:


### Comentarios:

* **Mario Alonso Ruiz Garcia** (1) [1003818](https://platzi.com/comentario/1003818/) 

	Tengo la siguiente duda. Si creo un recurso para usar auto scaling group y tengo mis policitas de incrementar/decrementar el numero de instancias segun las politicas definidas estoy haciendo mal? porque la configuracion inicial tal vez se lanzo con 1 ec2, y por lo comentado del drift estaria modificando mi infraestructura dinamicamente. Espero me puedan ayudar, saludos!

* **Andres Alberto Ariza Mantilla** (1) [996131](https://platzi.com/comentario/996131/) 

	no me queda del todo claro, en el minuto 1:28 dice que si un recurso falla se hace rollback y no elimina los otros recursos para permitir hacer debug, pero mas adelante dice que el comportamiento es que siempre se eliminan todos los recursos si uno solo falla en crearse, entonces digamos que esa parte me confunde,…  
	Gracias

## 0110. Bonus ejemplo de stack [23543](https://platzi.com/clases/1717-iaac-aws/23543-bonus-ejemplo-de-stack/)

### Descripción:


### Links:

* [cloudformation/master.yml at composition-non-nested-stacks · czam01/cloudformation · GitHub](https://github.com/czam01/cloudformation/blob/composition-non-nested-stacks/master.yml)

### Comentarios:

* **Dante Castillo Z.** (1) [1071348](https://platzi.com/comentario/1071348/) 

	interante plantilla para desplegar un stack.

## 0120. Stack Sets despliegues multicuenta [23544](https://platzi.com/clases/1717-iaac-aws/23544-stack-sets-despliegues-multicuenta/)

### Descripción:


### Comentarios:

* **Dante Castillo Z.** (1) [1071366](https://platzi.com/comentario/1071366/) 

	Stacks Set  
	Que tipos de cuentas existen?  
	Cuentas administrador y cuentas target  
	Desde donde se despliegan recursos Multi Cuenta?  
	Se debe hacer desde una cuenta maestra que tenga permisos sobre las otras  
	Instancia de un Stack  
	Hace referencia a un stack dentro de una cuenta  
	Diferentes Parametros  
	Se pueden desplegar stack set que cambien de parametros dependiendo de la cuenta destino.

## 0130. Laboratorio # 2  desplegando un Stack Set en un esquema multi-cuenta [23545](https://platzi.com/clases/1717-iaac-aws/23545-laboratorio-2-desplegando-un-stack-set-en-un-esque/)

### Descripción:


### Comentarios:

* **Pedro Porras** (3) [884217](https://platzi.com/comentario/884217/) 

	Como se puede acceder a la herramienta que usas para manejar varias cuentas de AWS como lo muestras en el ejemplo?

	* **isra_rivero** [884217] (2)

		AWS Organization account
		
		The AWS Landing Zone is deployed into an AWS Organizations account. This account is used to manage configuration and access to AWS Landing Zone managed accounts. The AWS Organizations account provides the ability to create and financially manage member accounts. It contains the AWS Landing Zone configuration Amazon Simple Storage Service (Amazon S3) bucket and pipeline, account configuration StackSets, AWS Organizations Service Control Policies (SCPs), and AWS Single Sign-On (SSO) configuration.

* **Andres Alberto Ariza Mantilla** (2) [1010812](https://platzi.com/comentario/1010812/) 

	El curso esta interesante, lastima es que NUNCA RESPONDEN LAS PREGUNTAS

* **Andres Alberto Ariza Mantilla** (1) [996127](https://platzi.com/comentario/996127/) 

	Yo intente hacer el taller, pero el entorno que me sale a mi es completamente diferente, hay alguna herramienta o sección especial por donde pueda realizar los mismos pasos que se ejecutan en el video?

* **Andres Alberto Ariza Mantilla** (1) [82045](https://platzi.com/comentario/996123/) 
en el minuto 3:40 hablas sobre los roles de administración y ejecución, dices que ya deben estar previamente configurados pero no se mues...

## 0140. Nested Stacks composición y ejemplos [23546](https://platzi.com/clases/1717-iaac-aws/23546-nested-stacks-composicion-y-ejemplos/)

### Descripción:


### Comentarios:

* **Dante Castillo Z.** (1) [1071424](https://platzi.com/comentario/1071424/) 

	```
	    Nested Stacks
	    	Limites de CloudFormation
	    		100 Mappings : Stack
	    		200 Recursos: Stack
	    		51,200 bytes: Cuerpo de template para CreateStack, UpdateStack, or ValidateTemplate
	    		460,800 bytes: Tamaño maximo de template en S3
	    	Donde usar Nested Stacks
	    		Limites	
	    			Para crear recursos que necesiten pasar los limites de CloudFormation
	    		Granularidad
	    			Cada Recurso queda con un Stack independiente
	    		Orden
	    			Se pueden crear precedencias y condiciones entre recursos
	    		Interaccion
	    			Los stacks se comunican entre si a traves de outputs
	    
	```

## 0150. Laboratorio # 3 creación de recursos del Stack [23547](https://platzi.com/clases/1717-iaac-aws/23547-laboratorio-3-creacion-de-recursos-del-stack/)

### Descripción:


### Comentarios:

* **mariaocampo** (1) [837234](https://platzi.com/comentario/837234/) 

	Personalmente, siento que falta una mejor explicación de la infraestructura cómo código, el uso de plantillas ya creadas como ejemplo en todos los despliegues en cloudformation no ayuda mucho al propósito del curso que es enseñar infraestructura como código en aws, de lo que va del curso solo se ha desarrollado una sola plantilla

	* **julianqp5025** [837234] (2)

		Concuerdo con este comentario, de nada sirve trabajar con plantillas ya construidas.

* **ceruizdev** (1) [802672](https://platzi.com/comentario/802672/) 

	<https://github.com/czam01/cloudformation>

## 0160. Laboratorio #3 pruebas de funcionamiento del stack [23548](https://platzi.com/clases/1717-iaac-aws/23548-laboratorio-3-pruebas-de-funcionamiento-del-stack/)

### Descripción:


### Links:

* [Curso de Bases de Datos en AWS](https://platzi.com/clases/db-aws/)

### Comentarios:

* **ceruizdev** (2) [802708](https://platzi.com/comentario/802708/) 

	Buen lab todo a detalle!

	* **Carlos Andrés Zambrano Barrera** [802708] (1)

		Me alegra que te haya gustado!!!

* **Dante Castillo Z.** (1) [1071451](https://platzi.com/comentario/1071451/) 

	excelente explicación de este laboratorio!

## 0170. Laboratorio # 4 crear nuestro primer Nested Stack [23549](https://platzi.com/clases/1717-iaac-aws/23549-laboratorio-4-crear-nuestro-primer-nested-stack/)

### Descripción:


### Links:

* [Curso de Storage en AWS](https://platzi.com/clases/storage-aws/)

### Comentarios:

* **mariaocampo** (2) [837251](https://platzi.com/comentario/837251/) 

	Lo ideal sería explicar cómo crear una plantilla de estas :S

	* **Yank Carlos Reyes Espinal** [837251] (2)

		Viendo la estructura de estos archivos, solo pienso que mínimo se debe de tener un conocimiento tan profundo en aws, como los que ya tienen los ingenieros de aws los cuales se encargan de crear desde ceros los productos de aws… haha

	* **Dante Castillo Z.** [837251] (1)

		Eso se ve en el tema de Anatomia de un template y la clase practica para crearlo.

* **ramirobga** (1) [876144](https://platzi.com/comentario/876144/) 

	por favor comenten cuanto tiempo aprox toma crear el ejercicio. es importante para tener una referencia.

* **Andres Alberto Ariza Mantilla** (1) [82568](https://platzi.com/comentario/1007987/) 
Para los stacks anidados, no deberian cargarse primero para obtener las urls de estos y agregarlos al master.yml?

## 0180. Laboratorio #4 pruebas de funcionamiento del Nested Stack [23550](https://platzi.com/clases/1717-iaac-aws/23550-laboratorio-4-pruebas-de-funcionamiento-del-nested/)

### Descripción:


### Links:

* [Postman | The Collaboration Platform for API Development](https://www.getpostman.com)

### Comentarios:

## 0190. Laboratorio # 5 cómo crear un stack de forma gráfica con Designer [23551](https://platzi.com/clases/1717-iaac-aws/23551-laboratorio-5-como-crear-un-stack-de-forma-grafica/)

### Descripción:


### Comentarios:

* **Jorge David Duque Agudelo** (2) [916600](https://platzi.com/comentario/916600/) 

	Uno de los detalles que he encontrado con el Designer de AWS es que muchas veces no detecta errores, y marca que el template es válido, por ejm el más reciente que me pasó es que al crear en una plantilla de cloudformation un stack con un dashboard en formato YAML, el body del dashboard es en formato JSON y solo me mostró errores cuando intenté crear el stack, así que para validar prefiero directamente en cloudformation cargando el template.

# Funciones en Cloudformation [4696]

## 0200. Funciones intrínsecas GetAtt, FindInMap, Join, Split y Select [23552](https://platzi.com/clases/1717-iaac-aws/23552-funciones-intrinsecas-getatt-findinmap-join-split-/)

### Descripción:


### Links:

* [Referencia de tipos de recursos y propiedades de AWS - AWS CloudFormation](https://docs.aws.amazon.com/es_es/AWSCloudFormation/latest/UserGuide/aws-template-resource-type-ref.html)

### Comentarios:

* **Andres Alberto Ariza Mantilla** (1) [1016524](https://platzi.com/comentario/1016524/) 

	creo que en el minuto 7:28 hay un error en como se explica el Join,
	
	Examples  
	Join a Simple String Array  
	The following example returns: “a : b : c”.
	
	YAML  
	!Join [ “:”, [ a, b, c ] ]
	
	<https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/intrinsic-function-reference-join.html>

* **Jorge David Duque Agudelo** (1) [78184](https://platzi.com/comentario/916618/) 
¿Cuando se utiliza la función !GetAtt apuntando a un atributo como el ARN, este genera una dependencia hacía el recurso del que se está t...

## 0210. Funciones intrínsecas Sub, Ref y ImportValue. [23553](https://platzi.com/clases/1717-iaac-aws/23553-funciones-intrinsecas-sub-ref-y-importvalue/)

### Descripción:


### Comentarios:

* **Jorge David Duque Agudelo** (1) [78187](https://platzi.com/comentario/916652/) 
¿Puedo usar la función !ImportValue para traer un valor exportado de un stack creado en otra cuenta?

	* **Andres Alberto Ariza Mantilla** [78187] (1)

		Nunca responde!!

## 0220. Funciones condicionales If, Not, And y Equals [23554](https://platzi.com/clases/1717-iaac-aws/23554-funciones-condicionales-if-not-and-y-equals/)

### Descripción:


### Comentarios:

* **carlosbazanhuaman** (1) [1011823](https://platzi.com/comentario/1011823/) 

	mismo lenguaje de programacion.

# Automatización y despliegues de infraestructura como código [4697]

## 0230. Importancia de la automatización de infraestructura [23555](https://platzi.com/clases/1717-iaac-aws/23555-importancia-de-la-automatizacion-de-infraestructur/)

### Descripción:


### Comentarios:

## 0240. Cómo automatizar despliegues de infraestructura [23556](https://platzi.com/clases/1717-iaac-aws/23556-como-automatizar-despliegues-de-infraestructura/)

### Descripción:


### Comentarios:

## 0250. Creación de pipelines para despliegue de infraestructura [23557](https://platzi.com/clases/1717-iaac-aws/23557-creacion-de-pipelines-para-despliegue-de-infraestr/)

### Descripción:


### Comentarios:

## 0260. Laboratorio #6 Estructura de repositorio para despliegue de función lambda [23558](https://platzi.com/clases/1717-iaac-aws/23558-laboratorio-6-estructura-de-repositorio-para-despl/)

### Descripción:


### Comentarios:

* **carlosbazanhuaman** (1) [1011840](https://platzi.com/comentario/1011840/) 

	el concepto de pipeline es similar a los otros pipeline que existen.

## 0270. Laboratorio #6 prerequisitos para creación del pipeline [23559](https://platzi.com/clases/1717-iaac-aws/23559-laboratorio-6-prerequisitos-para-creacion-del-pipe/)

### Descripción:


### Comentarios:

* **Luis Ortiz** (1) [75176](https://platzi.com/comentario/865345/) 
¿Cuáles son los permisos específicos?

## 0280. Laboratorio #6 despliegue de pre requisitos [23560](https://platzi.com/clases/1717-iaac-aws/23560-laboratorio-6-despliegue-de-pre-requisitos/)

### Descripción:


### Comentarios:

## 0290. Laboratorio #6 creación del pipeline para el despliegue de una función lambda [23561](https://platzi.com/clases/1717-iaac-aws/23561-laboratorio-6-creacion-del-pipeline-para-el-despli/)

### Descripción:


### Comentarios:

* **Luis Ortiz** (1) [865337](https://platzi.com/comentario/865337/) 

	En la conexión del github tuve que hacer un Fork del repo para poder hacerlo de lo contrario no podia conectarme al repo **czam01**

## 0300. Laboratorio #6 verificación de recursos creados en el pipeline [23562](https://platzi.com/clases/1717-iaac-aws/23562-laboratorio-6-verificacion-de-recursos-creados-en-/)

### Descripción:


### Comentarios:

# Diagnostico de errores y seguridad en infraestructura como código. [4698]

## 0310. Seguridad en templates [23563](https://platzi.com/clases/1717-iaac-aws/23563-seguridad-en-templates/)

### Descripción:


### Comentarios:

## 0320. Troubleshooting [23564](https://platzi.com/clases/1717-iaac-aws/23564-troubleshooting/)

### Descripción:


### Comentarios:

## 0330. Seguridad en despliegues [23565](https://platzi.com/clases/1717-iaac-aws/23565-seguridad-en-despliegues/)

### Descripción:


Creando infraestructura como código en AWS a través de Cloudformation es una buena práctica para cualquier tipo de proyecto, sin embargo debemos tener en cuenta diferentes aspectos que nos permitirán asegurar todo el proceso de despliegue de recursos y servicios.

Secrets Manager  
Link: [https://docs.aws.amazon.com/es_es/secretsmanager/latest/userguide/intro.html ](https://docs.aws.amazon.com/es_es/secretsmanager/latest/userguide/intro.html)

AWS Secrets Manager es un servicio de AWS que permite administrar secretos y su ciclo de vida dentro de AWS. Pueden ser de diferentes tipos, puede controlarlos, rotarlos y cifrarlos.

Como vemos en la imagen podemos almacenar 4 tipos de secretos que se integran directamente con servicios de AWS como:  
1- **RDS** → Bases de datos relacionales (puedes ver más en nuestro curso de bases de datos en AWS).  
2- **Redshift Cluster **→ Servicio de Datalake en AWS(puedes ver más en nuestro curso de BigData en AWS)  
3- **DocumentDB** → Base de datos de documentos (parecida a Mongo DB).  
4- Otras bases de datos.

Por último se puede guardar otro tipo de secreto.

![Store a new secret .png](https://static.platzi.com/media/user_upload/Store%20a%20new%20secret%20-d6a661a9-6995-4bd2-8d83-2e3418277d1a.jpg)

Para cifrar tokens de github o información importante en nuestros templates de cloudformation utilizaremos la opción “Other type of secrets”, adicionalmente debemos seleccionar la llave KMS con la que ciframos el secreto.

**EJEMPLO**  
Necesitamos crear un [Codepipeline](https://docs.aws.amazon.com/es_es/AWSCloudFormation/latest/UserGuide/aws-resource-codepipeline-pipeline.html) usando Cloudformation y en una de las fases del pipeline tiene que leer el código de AWS, para esto debemos utilizar un token de conexión a Github, este token debe permanecer oculto por seguridad.

Para este fin debemos crear un secret en AWS Secrets Manager.

Este secreto almacenará un token de conexión a GitHub.

![secret key value.png](https://static.platzi.com/media/user_upload/secret%20key%20value-e329f22a-e5fb-4601-b595-0b4e90b4ab93.jpg)

Una vez almacenemos el secreto nos pedirá un nombre visible para guardarlo, en este caso lo pondremos como SecretGithub.

![secretgithub.png](https://static.platzi.com/media/user_upload/secretgithub-d0587bfa-118c-42a6-b666-02e9068e9189.jpg)

Cuando necesitemos utilizar este secreto en cloudformation tenemos que hacerlo de la siguiente forma:
``` 
     OAuthToken:"{{resolve:secretsmanager:SecretGithub:SecretString:TokenGithub}}"
    
```

En esta definición se puede observar dónde se utilizarán los nombre del secreto y la llave del mismo.

**Llave del secreto:** TokenGithub  
**Nombre del secreto: **SecretGithub

De esta forma podremos poner todo el código del template de Cloudformation en un repositorio y no tendremos expuesto ninguna información confidencial. Es importante aclarar que el role de Codepipeline debe tener permisos sobre secrets manager específicamente sobre GetSecretValue.

**PRICING**  
**Por secreto: ** $0.40 dólares por mes.  
**Por llamadas a la API: ** $0.05 dólares por cada 10.000 llamadas.

**AWS KMS**  
Link: <https://docs.aws.amazon.com/es_es/kms/latest/developerguide/overview.html>

Este servicio permite controlar las llaves de cifrado que se utilizan para el cifrado de información en AWS. Cuando se cree una llave KMS se deben especificar 2 niveles de permisos:

1- Quienes pueden usar la llave.  
2- Quienes son los administradores de la llave.

Adicionalmente este servicio se integra con Cloudtrail en AWS el cual registra todas las llamadas a la API, es decir, nos permite identificar quién, cuándo y cuántas veces han usado o intentado utilizar la llave.

Cuando utilizamos secrets manager podemos ver que el secreto termina siendo cifrado por KMS, podemos entonces elegir entre la llave predeterminada o alguna que nosotros hayamos creado.

**EJEMPLO**  
Necesitamos realizar el cifrado de una cadena de conexión, para este fin tendremos diferentes alternativas como:

* AWS CLI → <https://docs.aws.amazon.com/cli/latest/reference/kms/encrypt.html>
* AWS SDK PYTHON → <https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.encrypt>



Adicionalmente podemos utilizar otros lenguajes de programación soportados por AWS, para utilizar estas cadenas cifradas debemos garantizar que el servicio que accederá a él, tenga permisos para hacer actividades de Decrypt.

### Comentarios:

* **Cristian David Franco Garcia** (1) [835533](https://platzi.com/comentario/835533/) 

	Cual servicio debe tener el rol con permisos sobre secrets manager CodePipeline o CloudFormation?

## 0340. Laboratorio # 7 identificación de errores en despliegues [23566](https://platzi.com/clases/1717-iaac-aws/23566-laboratorio-7-identificacion-de-errores-en-desplie/)

### Descripción:


### Comentarios:

# Funciones lambda en Cloudformation [4699]

## 0350. Cómo desplegar lambda como función [23567](https://platzi.com/clases/1717-iaac-aws/23567-como-desplegar-lambda-como-funcion/)

### Descripción:


### Comentarios:

## 0360. Cómo desplegar lambda como función serverless [23568](https://platzi.com/clases/1717-iaac-aws/23568-como-desplegar-lambda-como-funcion-serverless/)

### Descripción:


### Comentarios:

## 0370. Laboratorio # 8  puesta en producción de nuestra función lambda [23569](https://platzi.com/clases/1717-iaac-aws/23569-laboratorio-8-puesta-en-produccion-de-nuestra-func/)

### Descripción:


### Comentarios:

# Conclusiones [4700]

## 0380. Conclusiones finales [23570](https://platzi.com/clases/1717-iaac-aws/23570-conclusiones-finales/)

### Descripción:


### Links:

* [Curso de Storage en AWS](https://platzi.com/clases/storage-aws/)

* [Curso de Bases de Datos en AWS](https://platzi.com/clases/db-aws/)

* [Curso de Big Data](https://platzi.com/clases/big-data/)

### Comentarios:

* **Danilo Pazos** (1) [910261](https://platzi.com/comentario/910261/) 

	Mi duda es la siguiente.  
	En ciertas ocasiones necesitamos adjuntar librerias externas a los lambdas, por lo que manualmente se adjunta un zip. Para estos casos, que es más recomendable? Manejarlo en un repositorio, en donde puedo tener muchos lambdas y solo algunos dependen de librerias. O lo manejamos desde s3?  
	En lo personal creo que sería mejor desde un repo, pero es posible hacerlo? Y mi duda sería cómo?  
	Obviamente mi consulta es para lambdas serverless functions.  
	Gracias.

	* **Jorge David Duque Agudelo** [910261] (1)

		En mi caso, lo que he hecho es trabajar las librerias externas que no se encuentren dentro del ecosistema de AWS como layers, y definirlas dentro del template de cloudformation en cada lambda que lo necesite.  
		Documentación oficial:  
		[Layers AWS Docs](https://docs.aws.amazon.com/lambda/latest/dg/configuration-layers.html)
		
		Espero esto pueda darte una alternativa.

