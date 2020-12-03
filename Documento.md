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

