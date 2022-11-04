# Instalación de Java en el SO

###### Nombre del alumno:
Abián Castañeda Méndez

## Indice

- **[Introducción](#punto0)**
- **[¿Cómo instalar Java en Ubuntu desde repositorios?](#punto1)**
- **[¿Cómo instalar una versión específica de Java?](#punto2)**
- **[Configuración de las variables de entorno](#punto3)**
- **[Listar la versiones de OpenJDK instaladas](#punto4)**
- **[Actualización de las variables de entorno](#punto5)**


### Introducción <a name="punto0"></a>

En esta actividad compartiré con ustedes un sencillo tutorial de como instalar Java en nuestro sistema con el JDK el cual es un entorno de desarrollo y el entorno de ejecución JRE.

### ¿Cómo instalar Java en Ubuntu desde repositorios? <a name="punto1"></a>

Lo primero debemos de actualizar el sistema, después instalaremos Java y por último comprobaremos que tenemos instalado Java en nuestro sistema.

<img src="img\1.png">

### ¿Cómo instalar una versión específica de Java? <a name="punto2"></a>

Dependiendo de la versión que queramos instalar, haremos lo siguiente:

-  13

<img src="img\2.png">

- 11

<img src="img\3.png">

- 8 

<img src="img\4.png">

La versión que se debe de trabajar es la versión 8. Para ello verificaremos la versión de Java que se esta ejecutando.

<img src="img\5.png">

En el hipotético caso de que no se ejecute la versión 8, tendremos que configurar las variables de entorno.

### Configuración de las variables de entorno <a name="punto3"></a>

En este punto estableceremos las variables de entorno. Esta parte es necesaria dado que Linux necesita saber dónde está ubicado el programa para ejecutarlo y qué versión de Java debe usar de forma predeterminada.

### Listar la versiones de OpenJDK instaladas <a name="punto4"></a>

En este punto verificaremos que se han descargado las diferentes versiones de OpenJDK.

<img src="img\6.png">

### Actualización de las variables de entorno <a name="punto5"></a>

Editaremos y modificaremos el fichero profile y seleccionaremos la version 8.

<img src="img\7.png">

Otra manera de realizar esto sería añadir un código con el comando **nano** en una ruta que se verá en la siguiente imagen.

<img src="img\8.png">

Después haremos que el script sea ejecutable con chmod para que finalmente, cargue las variables de entorno usando el comando de source.

<img src="img\9.png">

<img src="img\10.png">




