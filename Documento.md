# Practica 4

### Android Studio y Mi primer Hola Mundo
* El resultado debe mostrar una captura semejante a esta pantalla siguiente:

<img src="Medios\1.jpg"/>

### Tarea 1.1: Instalación de Android Studio 

* Android Studio proporciona un entorno de desarrollo integrado (IDE) completo, incluido un editor de código avanzado y un conjunto de plantillas de aplicación. Además, contiene herramientas para el desarrollo, depuración, pruebas y rendimiento que hacen que sea más rápido y fácil desarrollar aplicaciones. Puedes probar tus aplicaciones con una amplia gama de emuladores preconfigurados o en tu propio dispositivo móvil, crear aplicaciones de producción y publicar en la tienda de Google Play.
Normalmente, esta tarea es un poco sencilla si ya tiene experiencia instalando programas en cualquier sistema operativo, pero si tiene problemas al hacerlo siga la guía de instalación de Android Studio de la documentación.

* Android Studio es un entorno de desarrollo, un software, que cuenta con herramientas y servicios para que los desarrolladores puedan crear nuevas aplicaciones para Android. Muchos de los sistemas operativos actuales cuentan con este tipo de entornos de desarrollo, algo que ocurre también en el sistema operativo de Google.

1.	Si descargaste un archivo .exe (recomendado), haz doble clic en él para iniciarlo.
	Si descargaste un archivo .zip, extráelo y copia la carpeta android-studio en 	la carpeta Archivos de programa. A continuación, abre la carpeta android-	studio > bin y, luego, inicia studio64.exe (para máquinas de 64 bits) o 	studio.exe.
2.	Damos siguientes hasta finalizar.

3.	Sigue los pasos del asistente de configuración en Android Studio y asegúrate de instalar los paquetes de SDK que recomiende.

### Después de la instalación compruebe lo siguiente, si le falta algo complete lo necesario:
 * Verifique que ya cuente con el JDK de Java en cualquier versión

 <img src="Medios\2.PNG"/>

 * Verifique la ubicación de la instalación del SDK en Android Studio

  <img src="Medios\3.png"/>

  * Verifique que en Android Studio este seleccionada la versión del JDK instalada en su máquina.

  <img src="Medios\4.PNG"/>

  * Creación de un dispositivo virtual
Cada paso indicado anteriormente debe ir acompañada de una captura y un comentario sobre su realización.

  ### Tarea 1.2: Crear la aplicación Hello World
Esta tarea tendrá como resultado una aplicación de muestra Hola Mundo, únicamente para comprobar que Android Studio este instalado de forma correcta e iniciar con el aprendizaje de los conceptos básicos del desarrollo con Android Studio.

  * Crea el proyecto de aplicación

  Estando en la ventana principal de Bienvenido a Android Studio, haga clic en Iniciar un proyecto de Android Studio.

  Según la versión, es posible que primero seleccione la plantilla, entonces seleccione una plantilla Empty Activity en el panel correspondiente a Phone y Tablet.

  <img src="Medios\7.PNG"/>

  <Acá ya eh selecionado la plantilla en la que estaré realizando mi trabajo.>
  
  En la ventana de Configurar su proyecto, escriba Hello World para el nombre de la aplicación

  Compruebe la ubicación predeterminada del proyecto en donde desea almacenar su aplicación, en el caso de que esa no sea su ubicación preferida, puede cambiarla.

   <img src="Medios\8.png"/>
  
  Si no tiene pensado publicar la aplicación, puede dejar el nombre del paquete predeterminado.

  En las nuevas versiones se elige Kotlin como el lenguaje de programación predeterminado, en el caso de que no le aparezca seleccionado, establezca Kotlin.

  Indique que porcentaje de dispositivos usan la API nivel 19 y cuales son sus características que incluye según el apartado Help me choose.

  <img src="Medios\5.png"/>

  En mi caso agrege la API 19 ya que no me salian las menores a 19.

  De clic en finish, y espere que gradle sincronice todas las librerías necesarias para su aplicación, esto puede tardar un momento, sea paciente.

  Cada vez que inicia un proyecto le lanza un consejo del día, tome una captura del consejo que le salió.
  
   <img src="Medios\9.PNG"/>

  ### Aparece el editor de Android Studio

  * Haga clic en la pestaña activity_main.xml para ver el editor de diseño
  * Haga clic en la pestaña Diseño del editor de diseño, si aun no está seleccionada, para mostrar una representación gráfica del diseño como se muestra a continuación.

  <img src="Medios\6.PNG"/>

  * Haga clic en la pestaña MainActivity.kt o MainActivity.java

  <img src="Medios\10.PNG"/>

### Explore el proyecto en el panel Android

* Si aún no está seleccionado, haga clic en la pestaña Proyecto en la columna de la pestaña vertical en el lado izquierdo de la ventana de Android Studio. Aparece el panel Proyecto. Explore todos sus directorios.

<img src="Medios\11.PNG"/>

Acá estan los proyectos en conjunto con los directorios.

### Explore la carpeta Gradle Scripts

El sistema de compilación Gradle en Android Studio facilita la inclusión de archivos binarios externos u otros módulos de biblioteca en la compilación como dependencias.

La primera vez que se crea un proyecto de aplicación, el panel Proyecto > Android aparece con la carpeta Scripts de Gradle expandida como se muestra a continuación.

<img src="Medios\12.png"/>

* Si la carpeta Scripts de Gradle no está expandida, haga clic en el triángulo para expandirla.

En la imagen anterior sale con todos los archivos por que ya esta desplegada.

* Busque el archivo build.gradle (Project: Hello_World).

<img src="Medios\13.PNG"/>

Aquí es donde encontrará las opciones de configuración que son comunes a todos los módulos que componen su proyecto. Cada proyecto de Android Studio contiene un único archivo de compilación Gradle de nivel superior. La mayoría de las veces no necesitará realizar ningún cambio en este archivo, pero sigue siendo útil para entender su contenido.

* Busque el archivo build.gradle(Module:app).

<img src="Medios\14.PNG"/>
<img src="Medios\15.PNG"/>

Dentro del build.gradle(Module:app) esta su código correspondiente.

### Explorar la aplicación y la carpeta res

Lo primero que se hace es expandir la carpeta, para que nos salgan todos los archivo.

<img src="Medios\16.PNG"/>

Todo el código y los recursos de la aplicación se encuentran dentro de las carpetas app y res.

* Expanda la carpeta de la aplicación, la carpeta java y la carpeta com.example.android.helloworld para ver el archivo java MainActivity. Al hacer doble clic en el archivo se abre en el editor de código.

<img src="Medios\17.PNG"/>
<img src="Medios\18.PNG"/>

Ahí esta su código correspondiente. 

* Expanda la carpeta res y la carpeta de diseño y haga doble clic en el archivo activity_main.xml para abrirlo en el editor de diseño.

<img src="Medios\6.PNG"/>

### Explorar la carpeta de manifiestos
* Expanda la carpeta de manifiestos.

<img src="Medios\19.PNG"/>

* Abra el archivo AndroidManifest.xml.

<img src="Medios\20.PNG"/>

## En cada uno de estos ficheros, indique para que se utilizan en el proyecto Android

### Tarea 1.3: Use un AVD (Android Virtual Device)

Usará el administrador de dispositivos virtuales Android (AVD) para crear un dispositivo virtual (también conocido como emulador) que simula la configuración de un tipo determinado de dispositivo Android y usar ese dispositivo virtual para ejecutar la aplicación.

### Crear un dispositivo virtual de Android (AVD)

En Android Studio, seleccione Herramientas > Android > Administrador de AVD o haga clic en el icono Administrador de AVD en la barra de herramientas. Aparecerá la pantalla Sus dispositivos virtuales. Si ya ha creado dispositivos virtuales, la pantalla los muestra (como se muestra en la figura siguiente); de lo contrario se ve una lista en blanco.


<img src="Medios\21.PNG"/>
<img src="Medios\23.PNG"/>

Haga clic en + Crear dispositivo virtual. Aparece la ventana Seleccionar hardware que muestra una lista de dispositivos de hardware preconfigurados. Para cada dispositivo, la tabla proporciona una columna para su tamaño de visualización diagonal (Tamaño), resolución de pantalla en píxeles (Resolución) y densidad de píxeles (Densidad).

<img src="Medios\22.png"/>

En este caso yo usaré el pixel 3

* Haga clic en la pestaña Recomendado si aún no está seleccionada y elija qué versión del sistema Android se ejecutará en el dispositivo virtual (como Pie).

<img src="Medios\24.png"/>

Hay muchas más versiones disponibles que las que se muestran en la pestaña Recomendado. Mira las pestañas Imágenes x86 y Otras imágenes para verlas.

<img src="Medios\27.PNG"/>

Si un vínculo de descarga está visible junto a una imagen del sistema que desea utilizar, aún no está instalado. Haga clic en el vínculo para iniciar la descarga y haga clic en Finalizar cuando haya terminado.

* Después de elegir una imagen del sistema, haga clic en Siguiente. Aparece la ventana Dispositivo virtual Android (AVD). También puede cambiar el nombre del AVD. Compruebe la configuración y haga clic en Finalizar.

<img src="Medios\25.PNG"/>
<img src="Medios\26.PNG"/>
Ahi estan algunos de las varios api que hay

### Ejecute la aplicación en el dispositivo virtual

* En Android Studio, elija Run > Ejecutar aplicación o haga clic en el icono Ejecutar de la barra de herramientas.

La ejecución la realice con mi celular 

En la ventana Seleccionar destino de implementación, en Dispositivos virtuales disponibles, seleccione el dispositivo virtual que acaba de crear y haga clic en Aceptar.

<img src="Medios\28.PNG"/>

La ejecucion la estoy realizando desde un dispositivo movil.

* Este paso puede variar por si tiene un dispositivo predeterminado seleccionado

<img src="Medios\29.jpg"/>

* Cuando finalice puede observar un resultado semejante al siguiente:

<img src="Medios\1.jpg"/>

### Ejecute la aplicación en un dispositivo físico

* Muestre todos los pasos necesarios para ejecutar su aplicación utilizando su dispositivo físico

Desde mi dispositivo movil en la imagen anterior está, donde se ha ejecutado de una forma muy bien.

* Encienda la depuración USB en su dispositivo físico

<img src="Medios\30.jpg"/>

* Ejecute la aplicación en su dispositivo físico

### Cambiar la configuración de Gradle de la aplicación

* Cambiar la versión mínima del SDK para la aplicación



* Encuentre el fichero build.gradle (Module:app)

<img src="Medios\30.PNG"/>

* Busque la propiedad minSdkVersion a un nivel más bajo

<img src="Medios\29.PNG"/>

* Sincronice la nueva configuración de Gradle

<img src="Medios\31.PNG"/>

### Utilice instrucciones de Log para su aplicación

* Ver el panel logcat y sus diferentes opciones de vista

* Establecer una instrucción en el código Kotlin para imprimir en el log de la aplicación
