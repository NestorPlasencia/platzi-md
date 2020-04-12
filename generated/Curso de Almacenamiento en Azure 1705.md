[Curso de Almacenamiento en Azure 1705](https://platzi.com/cursos/almacenamiento-azure)

# Introducción al curso [4618]

## 0010. PaaS y su oferta [23079](https://platzi.com/clases/1705-almacenamiento-azure/23079-paas-y-su-oferta/)

### Descripción:


 **PaaS** es Plataforma como servicio. Es quizás la más nutrida de todas las ofertas de cómputo en la nube, no solo Azure. Son los servicios con los que posiblemente estás más familiarizados, Azure cuenta con servicios como Web Apps para desplegar tus aplicaciones y hacerlas disponibles al público, servicios de almacenamiento y de base de datos.

### Links:

* [Curso de Azure Iaas](https://platzi.com/clases/azure-iaas/)

### Comentarios:

* **Christian David Sánchez** (2) [779186](https://platzi.com/comentario/779186/) 

	Iniciemos un curso más con Azure! 😎😎😎

* **dipibos** (1) [1060898](https://platzi.com/comentario/1060898/) 

	Que interesante. Espero poder comprender todas las funcionalidades incluidas en Azure!!

## 0020. Herramientas y recursos de este curso [23080](https://platzi.com/clases/1705-almacenamiento-azure/23080-herramientas-y-recursos-de-este-curso/)

### Descripción:


A lo largo de este curso necesitaremos con algunos rercusos y herramientas:

* Un IDE (Visual Studio) o Editor de código (VSCode)
* Un administrador para SQL



**¿Qué es un grupo de recursos?**

Un grupo de recursos te permiten englobar en un gran repositorio todos los componentes de una solución, prueba o por clientes.  
Screen reader support enabled.

### Links:

* [Visual Studio 2019 | Visual Studio](https://visualstudio.microsoft.com/vs/)

* [Visual Studio Code - Code Editing. Redefined](https://code.visualstudio.com/)

### Comentarios:

* **carlosbazanhuaman** (1) [897856](https://platzi.com/comentario/897856/) 

	visual code es la voz.

* **Christian David Sánchez** (1) [779206](https://platzi.com/comentario/779206/) 

	VSCode tiene superpoderes 😎😲💪

* **Yunier Hernandez** (1) [754819](https://platzi.com/comentario/754819/) 

	Se ve genial, llevaba tiempo esperando este curso. Me gusto mucho este primer vídeo.

# Almacenamiento [4619]

## 0030. Instalación de tu entorno de trabajo [23081](https://platzi.com/clases/1705-almacenamiento-azure/23081-instalacion-de-tu-entorno-de-trabajo/)

### Descripción:


Ahora que estamos comenzando con el curso de Azure vas a tener que instalar Visual Studio Code. Me encantaría aclararte que esta aplicación no se compara con Visual Studio. El hermano mayor que no solo edita el código, sino que también lo edita y tiene muchísimas características más.

Aclaro que no importa el Sistema Operativo o la herramienta que utilices, si hubo un factor determinante en elegir Visual Studio Code, o como los amigos lo llaman, VS Code, es simplemente porque esta es la única herramienta que es capaz de ser instalada en cualquier SO y sin mayor problema.

Solo debes ir a: [https://code.visualstudio.com/download ](url)

![Azure 7.png](https://static.platzi.com/media/user_upload/Azure%207-8363268b-149f-4130-b892-f48166b9b41b.jpg)

Descarga el paquete que corresponda a tu sistema operativo. Me encantaría hacer especial énfasis en que si tienes una distribución Linux que trabaje con la tienda de aplicaciones Snap puedes descargar y actualizar desde ahí tu aplicación.

Estoy seguro que con unos solos clics tendrás a Visual Studio Code listo para trabajar. ¡A divertirnos!

### Comentarios:

* **carlosbazanhuaman** (1) [897866](https://platzi.com/comentario/897866/) 

	hay que probar en ubuntu a ver que tal se comporta.

* **Christian David Sánchez** (1) [779212](https://platzi.com/comentario/779212/) 

	VSCode 💪

## 0040. Servicios y tipos de almacenamiento [23082](https://platzi.com/clases/1705-almacenamiento-azure/23082-servicios-y-tipos-de-almacenamiento/)

### Descripción:


El almacenamiento tiene que ver con cuatro matices y cada uno de ellos tienen un objetivo diferente.

**Blob** : Imagina que es un disco duro virtual enorme que te permitirá almacenar teras de información. Puedes dividirlo en **“frío”** con información que no utilizas pero quieres guardar y en “activo” donde buscas información como video o imágenes de manera constante.

**FIle** : Crea unidades de disco duro virtual para montarlas en otras maquinas sin importar el tipo de sistema operativo

**Queue** : Van a pasar por partes las solicitudes para que sean atendidas una por una. Esto es muy útil para evitar cuellos de botellas en tráfico de alta demanda.

**Table** : Es capaz de almacenar registro creando una especie de base de datos.

### Comentarios:

* **Christian David Sánchez** (2) [779227](https://platzi.com/comentario/779227/) 

	4 maneras de trabajar en Almacenamiento de Azure
	
	* File
	* Blob
	* Queue
	* Table
	
	

* **moises-bravo** (1) [927284](https://platzi.com/comentario/927284/) 

	Blob frío serviría en modo de un almacenamiento de respaldo de los archivos de la plataforma, y el blob activo para los archivos en caliente .

* **carlosbazanhuaman** (1) [897877](https://platzi.com/comentario/897877/) 

	dijo Aurora? de aws?

	* **eyesidmorenov** [897877] (1)

		dijo Ahora…

* **carlosbazanhuaman** (1) [897867](https://platzi.com/comentario/897867/) 

	El disco duro gigante = Blob.  
	Justo lo que necesitaba.

* **Robinson Maqui** (1) [858909](https://platzi.com/comentario/858909/) 

	Empezando con Azure, se agradece.

## 0050. Creación de recursos desde el portal [23083](https://platzi.com/clases/1705-almacenamiento-azure/23083-creacion-de-recursos-desde-el-portal/)

### Descripción:


### Comentarios:

* **alexgv04** (1) [872909](https://platzi.com/comentario/872909/) 

	para saber cual región es la indicada por cercanía y latencia pueden usar esta pagina: <http://www.azurespeed.com/> para colombia es el este de US

* **alexgv04** (1) [872884](https://platzi.com/comentario/872884/) 

	en el storage podríamos tener un sitio web estático, también se podría almacenar todos los asset de una pagina web, hdinsigth lo utiliza como almacenamiento en el cluster es el HDFS y el símil con aws es S3.

* **Christian David Sánchez** (1) [779269](https://platzi.com/comentario/779269/) 

	 **Crear un recurso de Almacenamiento:**
	
	* Click en Storage Accounts
	* Click en ADD
	* Click en CrearNuevoRecurso
	* Nombrar el recurso creado
	* Nombrar la cuenta de almacenamiento.
	* Click en Create
	
	
	
	Tips Geo-redundant es como una copia de seguridad o replicación de tus datos.

* **VictorDolce** (1) [78093](https://platzi.com/comentario/915262/) 
se debe de crear una cuenta den azure ??

	* **Juan David Castro (Platzi)** [78093] (2)

		Por supuesto.

* **carlosbazanhuaman** (1) [77194](https://platzi.com/comentario/899988/) 
Se puede alojar sitios estáticos en el storage?

	* **Juan David Castro (Platzi)** [77194] (1)

		¡Claro! Puedes seguir estos tutoriales:
		
		👉 <https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website>  
		👉 <https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website-how-to>

## 0060. Azure Storage Explorer [23084](https://platzi.com/clases/1705-almacenamiento-azure/23084-azure-storage-explorer/)

### Descripción:


### Links:

* [Explorador de Azure Storage: administración de almacenamiento en nube | Microsoft Azure](https://azure.microsoft.com/es-mx/features/storage-explorer)

### Comentarios:

* **Christian David Sánchez** (1) [779318](https://platzi.com/comentario/779318/) 

	Azure Storage Explorer
	
	* Descargar e instalar Storage Explorer desde <https://bit.ly/2BawyQM>
	* Copiar la connectionString de access Keys.
	* Conectarnos a Azure desde StorageExplorer.
	* Elegir la opcion “mediante connectionstring”
	* Configurar la conexión en el Storage Explorer
	
	

## 0070. Tips de seguridad para almacenamiento en .NET Core [23085](https://platzi.com/clases/1705-almacenamiento-azure/23085-tips-de-seguridad-para-almacenamiento-en-net-core/)

### Descripción:


### Links:

* [Curso de C# con .Net Core | Platzi](https://platzi.com/cursos/c-sharp/)

* [
        NuGet Gallery
        | Microsoft.Extensions.Configuration 3.0.0
    ](https://www.nuget.org/packages/Microsoft.Extensions.Configuration)

* [
        NuGet Gallery
        | Microsoft.Extensions.Configuration.FileExtensions 3.0.0-preview9.19423.4
    ](https://www.nuget.org/packages/Microsoft.Extensions.Configuration.FileExtensions/3.0.0-preview9.19423.4)

### Comentarios:

* **Erick Lenin Córdova Dávila** (1) [985824](https://platzi.com/comentario/985824/) 

	avoid some sintaxError using @id:ms-vscode.csharp or [https://github.com/OmniSharp/omnisharp-vscode](vscode.csharp)

* **Christian David Sánchez** (1) [779350](https://platzi.com/comentario/779350/) 

	Para crear un proyecto de consola:  
	**dotnet new console -n nombreProyecto**
	
	Paquetes instalados:
	
	* Microsoft.Extensions.Configuration:  
	**dotnet add package Microsoft.Extensions.Configuration --version 2.2.0**
	* Microsoft.Extensions.Configuration.FileExtensions:  
	**dotnet add package Microsoft.Extensions.Configuration.FileExtensions --version 2.2.0**
	
	

## 0080. Configurando appsettings.json en tu proyecto [23086](https://platzi.com/clases/1705-almacenamiento-azure/23086-configurando-appsettingsjson-en-tu-proyecto/)

### Descripción:


### Links:

* [
        NuGet Gallery
        | Microsoft.Extensions.Configuration.Json 3.0.0
    ](https://www.nuget.org/packages/Microsoft.Extensions.Configuration.json)

### Comentarios:

* **Christian David Sánchez** (2) [779373](https://platzi.com/comentario/779373/) 

	Compilar el proyecto:  
	**dotnet build**
	
	Paquete agreagado:
	
	* Microsoft.Extensions.Configuration.Json:  
	**dotnet add package Microsoft.Extensions.Configuration.Json --version 2.2.0**
	
	* En programm.cs agregar los espacios de nombre de los paquetes que instalamos en la aplicación.  
	**using Microsoft.Extensions.Configuration;  
	using Microsoft.Extensions.Configuration.Json;  
	using Microsoft.Extensions.Configuration.FileExtensions;**
	
	
	

* **joserodrigomorenocordero** (1) [787890](https://platzi.com/comentario/787890/) 

	```
	    var builder = new ConfigurationBuilder()
	                       .SetBasePath(Directory.GetCurrentDirectory())
	                       .AddJsonFile("appsettings.json", optional: false, reloadOnChange: true);
	                  
	        
	                var configuration = builder.Build();
	    
	```

## 0090. Crear contenedores en Blob Storage con .NET Core [23087](https://platzi.com/clases/1705-almacenamiento-azure/23087-crear-contenedores-en-blob-storage-con-net-core/)

### Descripción:


### Links:

* [
        NuGet Gallery
        | Microsoft.Azure.Storage.Blob 11.0.1
    ](https://www.nuget.org/packages/Microsoft.Azure.Storage.Blob)

### Comentarios:

* **Christian David Sánchez** (2) [779500](https://platzi.com/comentario/779500/) 

	Paquete agregado:
	
	* Microsoft.Azure.Storage.Blob  
	**dotnet add package Microsoft.Azure.Storage.Blob --version 11.1.0**
	
	

* **carlosbazanhuaman** (1) [900085](https://platzi.com/comentario/900085/) 

	ese paquete de azure.Storega.Blob tambien existe para otros lenguajes como nodeJS?

	* **daniel alonso** [900085] (1)

		Al parecer si, <https://www.npmjs.com/package/azure-storage>

## 0100. Agregar archivos en Blob Storage con .NET Core [23088](https://platzi.com/clases/1705-almacenamiento-azure/23088-agregar-archivos-en-blob-storage-con-net-core/)

### Descripción:


### Comentarios:

* **Christian David Sánchez** (1) [779600](https://platzi.com/comentario/779600/) 

	Para subir un archivo:
	``` 
	    CloudBlockBlob miBlob = contenedor.GetBlockBlobReference("foto.jpg"); 
	    //parametro = nombre del archivo
	    using (var fileStream = System.IO.File.OpenRead(@"rayo.jpg"))
	    {
	          miBlob.UploadFromStream(fileStream);
	    }
	    Console.WriteLine("El archivo se subio a Azure");
	    
	```

## 0110. Agregando una unidad de File Storage en Windows [23496](https://platzi.com/clases/1705-almacenamiento-azure/23496-agregando-una-unidad-de-file-storage-en-windows/)

### Descripción:


El Almacenamiento tipo File es una de las herramientas que más útiles puedes encontrar debido a que te puede ser de utilidad para casos profesionales y también para efectos personales. Al final, quién no desea tener unos cuantos terabytes de almacenamiento con un costo muy bajo y con ventajas como compartir esta información entre tus equipos de trabajo fácilmente.

Te recuerdo que esta lectura es completamente opcional dependiendo del Sistema Operativo que estés usando.

Si usas una distribución de Linux basada en Debian como Ubuntu entonces puedes ver el equivalente de este artículo aquí.

Si usas una máquina con Mac OS entonces puedes ver el equivalente de este artículo aquí.

#### Agregar una unidad de File Storage en Windows.

Comienza por crear la unidad de almacenamiento desde el Explorador de almacenamiento, recuerda que el nombre debe ir enteramente en minúsculas para no tener ningún error.  
![alma 1.png](https://static.platzi.com/media/user_upload/alma%201-f78337db-b989-42a9-bb63-50ab575a3c5e.jpg)

Después de eso, ve a tu portal y abre el índice de tu almacenamiento y selecciona la opción de Archivos.  
![alma 2.png](https://static.platzi.com/media/user_upload/alma%202-c80014a0-7c81-43f9-8493-134a5451837f.jpg)

Selecciona el File Share que acabas de crear desde tu Explorador.  
![alma 3.png](https://static.platzi.com/media/user_upload/alma%203-f05e22e9-304f-49a3-ae82-5d1997e9f38b.jpg)

Selecciona la opción de **Conectar**.  
![alma 4.png](https://static.platzi.com/media/user_upload/alma%204-3f1ef3a0-06c2-4599-af27-6251f327b8eb.jpg)

Aquí podrás ver que las tres opciones se despliegan. Copia todos los comandos que aparecen en la primera opción. Abre una sesión de PowerShell, si, porque ¡hasta en Windows las mejores herramientas se configuran en línea de comandos! Y ejecuta el script, que, de hecho, se ejecutará solo.  
![alma 5.png](https://static.platzi.com/media/user_upload/alma%205-ad4edf01-ac0c-4c37-95a0-ce7dd9f7fddd.jpg)

Ve a tu explorador de Windows en la opción de Este equipo y selecciona la opción de Agregar unidad compartida.  
![alma 6.png](https://static.platzi.com/media/user_upload/alma%206-482a8a3d-351b-4ba7-8200-d0b193d93375.jpg)

Con esto, tendrás ya agregada la unidad en tu explorador de Windows.  
![alma 7.png](https://static.platzi.com/media/user_upload/alma%207-fa44e8b4-79a1-480f-b70f-75de24fa175f.jpg)

¿Quieres divertirte? Entra a tu unidad, copia algunos archivos, vuelve a tu explorador y observa como esos archivos están ya visibles ahí. ¡Muy bien! Ahora tienes un disco duro que puedes compartir con quien tú quieras para tener archivos generales.

### Comentarios:

* **carlosbazanhuaman** (1) [900142](https://platzi.com/comentario/900142/) 

	muy interesante, es practico para poder trabajar con archivos compartidos por diferentes oficinas.

* **Christian David Sánchez** (1) [779608](https://platzi.com/comentario/779608/) 

	Geniaaaaaaal!!!😎😲💪

## 0120. Agregando una unidad de File Storage en Linux [23497](https://platzi.com/clases/1705-almacenamiento-azure/23497-agregando-una-unidad-de-file-storage-en-linux/)

### Descripción:


El Almacenamiento tipo File es una de las herramientas que más útiles puedes encontrar debido a que te puede ser de utilidad para casos profesionales y también para efectos personales. Al final, quién no desea tener unos cuantos terabytes de almacenamiento con un costo muy bajo y con ventajas como compartir esta información entre tus equipos de trabajo fácilmente.

Te recuerdo que esta lectura es completamente opcional dependiendo del Sistema Operativo que estés usando.

Si usas una máquina con Windows entonces puedes ver el equivalente de este artículo aquí.

Si usas una máquina con Mac OS entonces puedes ver el equivalente de este artículo aquí.

#### Agregar una unidad de File Storage en Linux.

Comienza por crear la unidad de almacenamiento desde el Explorador de almacenamiento, recuerda que el nombre debe ir enteramente en minúsculas para no tener ningún error.  
![hola1.png](https://static.platzi.com/media/user_upload/hola1-ec80c0e2-3a19-4ae6-8a0b-234a7b8153b7.jpg)

Después de eso, ve a tu portal y abre el índice de tu almacenamiento y selecciona la opción de Archivos.  
![hola2.png](https://static.platzi.com/media/user_upload/hola2-73cf1301-c851-4517-bc5f-5d554d0748ae.jpg)

Selecciona el File Share que acabas de crear desde tu Explorador.  
![hola3.png](https://static.platzi.com/media/user_upload/hola3-1bfb612e-e320-4e75-bb34-91d81b157d71.jpg)

Selecciona la opción de **Conectar**.  
![hola4.png](https://static.platzi.com/media/user_upload/hola4-68085953-3324-4366-ae69-16fb6787e381.jpg)

Aquí podrás ver que las tres opciones se despliegan. Haz una pausa en el portal y verifica que tu equipo tenga ya instalados un par de paquetes (dependiendo de la distribución podrá ser que ya estén instalados). Comienza primero por **cifs-utils**.  
![hola5.png](https://static.platzi.com/media/user_upload/hola5-d60765d4-f0e8-4361-b0d6-5e3899aeec30.jpg)

Después ve por **nfs-common**.  
![hola6.png](https://static.platzi.com/media/user_upload/hola6-ee49da8f-46ee-4225-b3a5-c162b67fc267.jpg)

Y una vez que ambos paquetes estén instalados entonces pega lo que el portal de Azure te pide pegar.  
![hola7.png](https://static.platzi.com/media/user_upload/hola7-39ec7154-c646-4d99-9042-59f1b5bd9dbc.jpg)

Todos los comandos que se encuentran en fila dentro de lo que copiaste se ejecutarán uno a uno, el último será el único que se esperará a que presiones **ENTER** para comenzar su ejecución. No hay ningún mensaje de confirmación, aunque tampoco hay uno que muestre algún error. Si todo sale bien, abre entonces una ventana para explorar tus archivos y ve al disco duro.

En la unidad de tu máquina, selecciona la carpeta **mnt**.

¡Listo! Tendrás ahí tu unidad montada.

Algo que notarás es que la carpeta viene desde raíz así que necesitarás un par de clics para llegar a la carpeta de almacenamiento en donde podrás insertar todos tus archivos sin problemas.

¡Disfruta comenzando a respaldar todas esas fotos de tus dispositivos!

### Comentarios:

* **carlosbazanhuaman** (1) [900144](https://platzi.com/comentario/900144/) 

	muy practico para compartir informacion con varias areas

* **Christian David Sánchez** (1) [779621](https://platzi.com/comentario/779621/) 

	Continuemos 😎

## 0130. Agregando una unidad de File Storage en MacOS [23526](https://platzi.com/clases/1705-almacenamiento-azure/23526-agregando-una-unidad-de-file-storage-en-macos/)

### Descripción:


El Almacenamiento tipo File es una de las herramientas que más útiles puedes encontrar debido a que te puede ser de utilidad para casos profesionales y también para efectos personales. Al final, quién no desea tener unos cuantos terabytes de almacenamiento con un costo muy bajo y con ventajas como compartir esta información entre tus equipos de trabajo fácilmente.

Te recuerdo que esta lectura es completamente opcional dependiendo del Sistema Operativo que estés usando.

Si usas una distribución de Linux basada en Debian como Ubuntu entonces puedes ver el equivalente de este artículo aquí.

Si usas una máquina con Windows entonces puedes ver el equivalente de este artículo aquí.

#### Agregar una unidad de File Storage en MacOS

Comienza por crear la unidad de almacenamiento desde el Explorador de almacenamiento, recuerda que el nombre debe ir enteramente en minúsculas para no tener ningún error.  
![az1.png](https://static.platzi.com/media/user_upload/az1-c25304d0-3074-449c-84f3-4005a2415aba.jpg)

Después de eso, ve a tu portal y abre el índice de tu almacenamiento y selecciona la opción de Archivos.  
![az2.png](https://static.platzi.com/media/user_upload/az2-7b6c6ae3-ee4b-48f8-a926-82a19f8b32f7.jpg)  
Selecciona el File Share que acabas de crear desde tu Explorador.  
![az3.png](https://static.platzi.com/media/user_upload/az3-ed6bfd22-6ac2-4f23-bfcf-8d746475ffaf.jpg)  
Selecciona la opción de Conectar.  
![az4.png](https://static.platzi.com/media/user_upload/az4-6ef86cd1-fe49-4480-8da0-404e23c4701b.jpg)  
Aquí podrás ver que las tres opciones se despliegan. Selecciona MacOS. En tu Finder selecciona dentro del menú Go. La opción de Connect to Server.  
![az5.png](https://static.platzi.com/media/user_upload/az5-b1496c56-48c4-4b05-9e96-d685bd93a316.jpg)  
En la ventana que aparece, agrega la dirección de este tipo (la puedes copiar desde tu portal de Azure).

smb://botsgeneralstorage.file.core.windows.net/botsgeneralstorage

Cuando eso suceda, te aparecerá una pantalla como la siguiente.  
![az6.png](https://static.platzi.com/media/user_upload/az6-3e617e8e-dce4-4aa6-9c79-0881eb9a83c6.jpg)  
Acepta con el botón de **Conectar**. La siguiente pestaña te pedirá un usuario y contraseña.  
![az7.png](https://static.platzi.com/media/user_upload/az7-17ede8fb-78a7-4427-9b8d-6f7b0d0e00c5.jpg)  
Estos datos los puedes obtener en tu portal de Azure. En la sección de **Claves de acceso**.  
![az8.png](https://static.platzi.com/media/user_upload/az8-6cbdec5c-0325-4cc3-bfe0-aaaa41aabae7.jpg)  
El usuario es el nombre de la cuenta, la contraseña es la clave de key1. Cuando todo esté listo puedes ver la nueva ventana con tu unidad lista.  
![az9.png](https://static.platzi.com/media/user_upload/az9-f4056ee8-5d95-4edf-a43f-9db803699681.jpg)  
Desplázate un poco hacia abajo y verás que la unidad ya está montada y lista para compartir archivos.  
![az10.png](https://static.platzi.com/media/user_upload/az10-74db47f2-0cac-47b0-a4bd-20ed78ea9f23.jpg)  
¿Quieres divertirte? Entra a tu unidad, copia algunos archivos, vuelve a tu explorador y observa como esos archivos están ya visibles ahí. ¡Muy bien! Ahora tienes un disco duro que puedes compartir con quien tú quieras para tener archivos generales.

### Comentarios:

* **carlosbazanhuaman** (1) [900146](https://platzi.com/comentario/900146/) 

	esto es como tener un usb gigante.

# Table Storage [4620]

## 0140. Configuración para trabajar con Table Storage [23089](https://platzi.com/clases/1705-almacenamiento-azure/23089-configuracion-para-trabajar-con-table-storage/)

### Descripción:


### Comentarios:

* **carlosbazanhuaman** (1) [927111](https://platzi.com/comentario/927111/) 

	jajaja estamos en almacenamiento pero vemos db, microsoft debe poner orden en sus productos.

* **Christian David Sánchez** (1) [779650](https://platzi.com/comentario/779650/) 

	Crear un recurso de Cosmos DB
	
	* Click en Add
	* Buscar Azure Cosmos DB
	* Elegir el grupo de recurso,
	* Nombrar la cuenta de CosmosDB
	* Elegir la location
	* Las opciones Geo-redundancy y multi-region es recomendada dejarlas disable
	
	

## 0150. Aplicación para Table Storage [23090](https://platzi.com/clases/1705-almacenamiento-azure/23090-aplicacion-para-table-storage/)

### Descripción:


### Links:

* [
        NuGet Gallery
        | Microsoft.Azure.Cosmos.Table 1.0.5
    ](https://www.nuget.org/packages/Microsoft.Azure.Cosmos.Table)

### Comentarios:

* **Christian David Sánchez** (1) [779843](https://platzi.com/comentario/779843/) 

	Paquete instalado:
	
	* Microsoft.Azure.Cosmos.Table:  
	**< PackageReference Include=“Microsoft.Azure.Cosmos.Table” Version=“1.0.5” />**
	
	

## 0160. Operación INSERT en Table Storage [23091](https://platzi.com/clases/1705-almacenamiento-azure/23091-operacion-insert-en-table-storage/)

### Descripción:


### Comentarios:

* **rmgelvez** (1) [935130](https://platzi.com/comentario/935130/) 

	No entendi esa relacion rara entre Storage y Cosmos, buscaré mas informacion de eso pero excelente ejercicio!

* **carlosbazanhuaman** (1) [900253](https://platzi.com/comentario/900253/) 

	tableStorage es una buena opcion para nuevo proyectos donde necesitemos almacenar informacion no tan relacional.

* **Christian David Sánchez** (1) [780097](https://platzi.com/comentario/780097/) 

	```
	    TableOperation insertOperation = TableOperation.InsertOrMerge(contacto);
	    TableResultresult = await table.ExecuteAsync(insertOperation);
	    Contacto insertedContact = result.ResultasContacto;
	    Console.WriteLine("contacto agregado");
	    
	```

## 0170. Operaciones CRUD en Table Storage [23092](https://platzi.com/clases/1705-almacenamiento-azure/23092-operaciones-crud-en-table-storage/)

### Descripción:


¿Insertaste ya tu entidad como en el video? ¿Eres feliz de que pudiste lograr la inserción de la entidad? Bueno, pues ya llevas la mitad, vamos ahora por las siguientes operaciones. Solo verifica que tu entidad está por ahora ya visible en el portal de Azure. Para hacerlo, debes ir al portal y seleccionar tu base de datos de CosmosDB y elegir la opción de exploración de datos.

![table1.png](https://static.platzi.com/media/user_upload/table1-5ef2c586-de9e-412f-be27-bf437a84a27a.jpg)

Con tu entidad lista ahora podemos comenzar a ver las siguientes dos operaciones restantes. Aprovecha la entidad que ya creaste para seguir con la siguiente operación. La de inserción fue la que ya hicimos. Podemos ver en el portal a tu nueva entidad y guardaremos para el final la operación de lectura.

Comencemos con la operación para actualizar el registro recién creado. Para hacer eso lo único que debes hacer es modificar los datos de tu contacto recién creado.
``` 
            {
                Contacto contacto = new Contacto("Espinoza", "Miranda")
                {
                    Email = "miranda@outlook.com",
                    Telefono = "8118748461"
                };
     
                TableOperation insertOrMergeOperation = TableOperation.InsertOrMerge(contacto);
                TableResult result = await table.ExecuteAsync(insertOrMergeOperation);
                Contacto insertedCustomer = result.Result as Contacto;
                Console.WriteLine("Entidad modificada");
            }
    
    
```

Nota que solo modifiqué un par de dígitos del contacto para ver que si haya un cambio. ¡Ah! Si, también modifiqué el mensaje de la consola para avisar que el registro fue modificado. Ejecuta tu aplicación y ve a tu portal de Azure, podrás ver el cambio reflejado ahí.

![Table2.png](https://static.platzi.com/media/user_upload/Table2-00098ffb-e83b-40a9-afc7-d77e088b6139.jpg)

Bastante sencillo ¿no es así? El mismo método te permite insertar o actualizar y eso es fenomenal en términos de reutilización de código, sin embargo, debes notar también que si no cuidas tu código y no generas una nueva entidad lo que sucederá es que puedes reemplazar accidentalmente un registro en lugar de crear uno nuevo así que ten mucho cuidado.  
Vamos ahora con la operación de lectura, es decir, la operación que debe mostrar en mi aplicación el registro que tengo en la base de datos. No hay mucha ciencia aquí, solo usas un objeto de tipo TableOperation, y con este objeto podemos buscar a nuestro elemento. Estaría muy bien que jugaras con esta línea para no solo obtener un registro sino todos en una lista. ¿Qué tendrías que hacer aquí? En fin, el resultado de la operación se va a un objeto TableResult que es de donde puedes obtener el resultado para mostrar en la terminal.
``` 
            {
                TableOperation retrieveOperation = TableOperation.Retrieve<Contacto>("Espinoza", "Miranda"); 
                TableResult result = await table.ExecuteAsync(retrieveOperation);
                Contacto customer = result.Result as Contacto;
     
                if (customer != null)
                {
                Console.WriteLine("{0}\t{1}\t{2}\t{3}", customer.PartitionKey, customer.RowKey, customer.Email, customer.Telefono);
                }
            }
    
    
```

Al ejecutar tu aplicación, el resultado en tu terminal debe ser parecido a esto.  
![table3.png](https://static.platzi.com/media/user_upload/table3-079c0792-6f52-4e77-97d2-9bb1e52f8599.jpg)

Ya tenemos tres de las cuatro operaciones básicas. Vamos con la final y la más triste de todas. La operación de eliminar. Aquí esencialmente se repite lo mismo.
``` 
            {
                Contacto contacto = new Contacto("Espinoza", "Miranda")
                {
                    Email = "miranda@outlook.com",
                    Telefono = "8118748461",
                    ETag = "*"
                };
     
                TableOperation deleteOperation = TableOperation.Delete(contacto);
                TableResult result = await table.ExecuteAsync(deleteOperation);
     
                Console.WriteLine("Resultado de la operación: " + result.RequestCharge);
            }
    
```

La gran diferencia es que entre las propiedades de tu nueva entidad debes agregar una propiedad adicional llamada ETag, nunca he sabido la razón exacta alguien una vez me dijo que se trataba de una medida de seguridad para evitar borrar accidentalmente, alguien también me dijo que se trataba de algo legado de las primeras versiones de almacenamiento. De una u otra manera solo agrega esta propiedad y después de eso regresa a tu portal. Verás que tu carpeta está vacía.

![table4.png](https://static.platzi.com/media/user_upload/table4-596d2f81-8d4f-45ad-8fc8-ed399e5e4101.jpg)

De esta manera es que podrás ejecutar cualquiera de todas tus operaciones básicas de edición en Table Storage ¡Diviértete comenzando a hacer procesos más complejos!

### Comentarios:

* **rmgelvez** (1) [935177](https://platzi.com/comentario/935177/) 

	Lo use sin el ETag y tambien lo elimino

* **carlosbazanhuaman** (1) [900262](https://platzi.com/comentario/900262/) 

	hay que reforzar el tema de los async

	* **juan camilo castillo saucedo** [900262] (2)

		En los cursos de net core se ve el tema mejor explicado

* **Christian David Sánchez** (1) [780837](https://platzi.com/comentario/780837/) 

	Muy buena la explicación, y entendible todo 😎

## 0180. Operaciones de entrada en Queues [23093](https://platzi.com/clases/1705-almacenamiento-azure/23093-operaciones-de-entrada-en-queues/)

### Descripción:


### Comentarios:

* **moises-bravo** (1) [1030107](https://platzi.com/comentario/1030107/) 

	Creo ha faltado que se explique mejor en que casos de deben usar cada uno de los servicios que hemos estado estudiando

* **carlosbazanhuaman** (1) [927154](https://platzi.com/comentario/927154/) 

	cuales podrian ser las aplicaciones mas usuales para este tipo de servicio normalmente?

* **Christian David Sánchez** (1) [782486](https://platzi.com/comentario/782486/) 

	Paquete instalado:  
	Microsoft.Azure.Storage.Queue  
	**< PackageReference Include=“Microsoft.Azure.Storage.Queue” Version=“11.1.0” />**

## 0190. Aplicación para Queues [23094](https://platzi.com/clases/1705-almacenamiento-azure/23094-aplicacion-para-queues/)

### Descripción:


### Comentarios:

* **carlosbazanhuaman** (1) [900302](https://platzi.com/comentario/900302/) 

	la base de storage para todos los objetos es la misma y eso ayuda a que sea mas facil entender

* **Christian David Sánchez** (1) [782509](https://platzi.com/comentario/782509/) 

	```
	    //realiza la conexion con el Storage Account
	    CloudStorageAccount myClient = CloudStorageAccount.Parse(configuration["connectionstring"]);
	    
	    //crea la instancia Queue que se usara.
	    CloudQueueClient queueClient = myClient.CreateCloudQueueClient();
	    
	    //crea my queue.
	    CloudQueue queue = queueClient.GetQueueReference("myFirstQueue");
	    queue.CreateIfNotExist(); //Crear si no existe mi queue`
	    
	```

## 0200. Consumir Colas [23095](https://platzi.com/clases/1705-almacenamiento-azure/23095-consumir-colas/)

### Descripción:


### Comentarios:

* **Giame Carlos Fajardo Santos** (1) [833571](https://platzi.com/comentario/833571/) 

	Aunque resolviste mi duda me rompiste el corazon cuando mencionas que es necesario crear el archivo local para luego subirlo. :')

## 0210. Crear un archivo en Blob a partir de cada Queue [23096](https://platzi.com/clases/1705-almacenamiento-azure/23096-crear-un-archivo-en-blob-a-partir-de-cada-queue/)

### Descripción:


### Comentarios:

* **moises-bravo** (1) [1030565](https://platzi.com/comentario/1030565/) 

	Este es el código que usamos en el clase pero me da error al final, ya revise el código varias veces
	``` 
	    using System;
	    using System.IO;
	    using Microsoft.Extensions.Configuration;
	    using Microsoft.Azure.Storage;
	    using Microsoft.Azure.Storage.Queue;
	    using Microsoft.Azure.Storage.Blob;
	    
	    
	    namespace QueueConsole
	    {
	        class Program
	        {
	            static void Main(string[] args)
	            {
	                var builder = new ConfigurationBuilder()
	                       .SetBasePath(Directory.GetCurrentDirectory())
	                       .AddJsonFile("appsettings.json");
	                 IConfiguration config = new ConfigurationBuilder()
	                       .AddJsonFile("appsettings.json",true,true).Build();
	    CloudStorageAccount myClient = CloudStorageAccount.Parse(config ["ConectionString"]);
	                CloudQueueClient queueClient = myClient.CreateCloudQueueClient();
	                CloudQueue queue = queueClient.GetQueueReference("filaprocesos");
	                CloudQueueMessage peekedMessage = queue.PeekMessage();
	                CloudBlobClient blobClient = myClient.CreateCloudBlobClient();
	                CloudBlobContainer container = blobClient.GetContainerReference("contenedorregistros");
	                container.CreateIfNotExists();
	                foreach (CloudQueueMessage item in queue.GetMessages(20, TimeSpan.FromSeconds(100)))
	                {
	                    string filePath = string.Format(@"log{0}.txt",item.Id);
	                    TextWriter tempFile = File.CreateText(filePath);
	                    var message = queue.GetMessage().AsString;
	                    tempFile.WriteLine(message);
	                    Console.WriteLine("Archivo Creado");
	                    tempFile.Close();
	    
	                    using(var fileStream =System.IO.File.OpenRead(filePath))
	                    {
	                        CloudBlockBlob myblob = container.GetBlockBlobReference(string.Format("log{0}.txt", item.Id));
	                        myblob.UploadFromStream(fileStream);
	                        Console.WriteLine("blob Creado");
	                    }
	    
	                    queue.DeleteMessage(item);
	                }
	                Console.ReadLine(); 
	            }    
	        }
	    }
	    
	    
	```
	
	me aparece este erro:
	
	Unhandled exception. Microsoft.Azure.Storage.StorageException: The specified queue does not exist.  
	at Microsoft.Azure.Storage.Core.Executor.Executor.ExecuteAsync[T](RESTCommand`1 cmd, IRetryPolicy policy, OperationContext operationContext, CancellationToken token) at Microsoft.Azure.Storage.Core.Executor.Executor.<>c__DisplayClass0_0`1.<ExecuteSync>b__0()  
	at Microsoft.Azure.Storage.Core.Util.CommonUtility.RunWithoutSynchronizationContext[T](Func`1 actionToRun) at Microsoft.Azure.Storage.Core.Executor.Executor.ExecuteSync[T](RESTCommand`1 cmd, IRetryPolicy policy, OperationContext operationContext)  
	at Microsoft.Azure.Storage.Queue.CloudQueue.PeekMessages(Int32 messageCount, QueueRequestOptions options, OperationContext operationContext)  
	at Microsoft.Azure.Storage.Queue.CloudQueue.PeekMessage(QueueRequestOptions options, OperationContext operationContext)

# Cierre [4621]

## 0220. Cierre [23097](https://platzi.com/clases/1705-almacenamiento-azure/23097-cierre/)

### Descripción:


¡Felicidades por haber llegado hasta aquí!

Aprendiste a subir archivos a Blob Storage, crear tablas e insertar registros en Table Storage, Crear colas y consumir colas en Queue. TIenes posibilidades increíbles para aplicar todos estos conocimientos.

### Links:

* [Curso de C# con .Net Core | Platzi](https://platzi.com/clases/c-sharp/)

* [Curso de ASP.NET Core](https://platzi.com/clases/aspnet-core/)

* [Curso de Azure Iaas](https://platzi.com/clases/azure-iaas/)

* [Curso de Web Apps y Logic Apps en Azure](https://platzi.com/clases/web-apps/)

* [Curso de SQL en Azure](https://platzi.com/clases/sql-azure/)

### Comentarios:

