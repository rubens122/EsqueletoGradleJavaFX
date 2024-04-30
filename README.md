# Esqueleto gradle con las dependencias para JavaFX

#### Autor: José Ramón Jiménez Reyes

#### Descripción

En este repositorio hay tres ramas, cada una de ellas con un esqueleto gradle para JavaFX:

- [sencilla](../../tree/sencilla): Este proyecto simplemente lanza una ventana simple.
- [recursos](../../tree/recursos): Este proyecto lanza una ventana. El diseño está realizado con FXML, se utilizan los correspondientes controladores yy también se utilizan recursos como imágenes y hojas de estilo.
- [recursos-utilidades](../../tree/recursos-utilidades): Este otro proyecto hace lo mismo que el anterior. Sin embargo, hace uso de la clase `Controlador` y de la clase de utilidades `Controladores` que facilita el trabajo a la hora de cargar diferentes vistas FXML en nestra aplicación.

Cada proyecto contiene las dependencias **gradle** para trabajar con **JavaFX** y para empaquetarlo correctamente. Notar qure son proyectos no modulares, por lo que al ejecutarlos desde el IDE lanzará una advertencia indicándolo, que podemos obviar.

También contienen una clase principal de ejemplo `Main` y la correspondiente clase lanzadora `LanzadoraMain`.

#### Uso

Lo primero que debes hacer es clonar el repositorio en tu IDE, y cambiarte a la rama deseada.

Elimina el repositorio local, eliminando el directorio `.git`. Esto debes hacerlo desde el sistema de ficheros o desde la línea de comandos, ya que desde el IDE generalmente no se muestra este directorio. Generalmente, deberás refrescar para que el IDE sea consciente de los cambios.

Cambia el nombre del proyecto para adecuarlo a tus preferencias. Utiliza las funciones de refactorización que ofrece tu IDE para renombrar el proyecto. Es necesario que tamibén cambies el nombre de la carpeta que contiene el proyecto.

Abre el archivo `settings.gradle` y cambia el nombre de proyecto ahí también.

Si vas a utilizar un VCS, crea el repositorio conveniente.

Por último, empieza a hacer las modificaciones necesarias para crear tu aplicación.

#### Ejecución

Ejecutálo normalmente desde tu IDE o utiliza la tarea `run` asociada para ejecutarlo. Desde la línea de comandos puedes utilizar el comando `./gradlew run` (si queremos obviar la salida de gradle podemos ejecutarlo utilizando el siguiente comando `./gradlew --console plain --quiet run`).
