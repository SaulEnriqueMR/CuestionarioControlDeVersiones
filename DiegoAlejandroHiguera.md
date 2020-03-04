# Preguntas

1. **¿Qué es un sistema de control de versiones?**
Es una metodologia o herramienta que ayuda a guardar los cambios que se realizan en los archivos de un proyecto. Es un creador de copias de los archivos de mi trabajo que se van añadiendo con fecha y hora.
El control de versiones ayuda a automatizar ese proceso. Aquí es donde intervienen las herramientas de VCS. Realizan un seguimiento de todos los cambios para nosotros, manteniendo una copia de cada cambio realizado en el código en nuestros proyectos.Los sistemas de control de versiones distribuidos (DVCS) no son diferentes a ese respecto. Su objetivo principal sigue siendo ayudarnos a rastrear los cambios que hacemos en los proyectos en los que estamos trabajando. La diferencia entre VCS y DVCS es cómo los desarrolladores comunican us cambios entre sí.

1. **¿Cuáles son los objetivos de un sistema de control de versiones?**
Un sistema de control de versiones es el ayudar a detectar los cambios que se realizan en el proyecto que estamos trabajando, haciendo que los errores encontrados no supongan gran problema, pues se tenga la posibilidad de que si  asi lo queremos volver a una version anterior en donde no existia tal problema.

1. **¿Cuáles son las pautas para controlar los cambios de diseño?**
•	Seguir un procedimiento sistemático de control de cambios
•	Manejar solicitudes de cambio en grupos
•	Estimar el costo de cada cambio
•	Tener cuidado con los grandes volúmenes de cambio
•	Establecer un tablero de control de cambios o su equivalente de una manera que tenga sentido para el proyecto
•	Esté atento a la burocracia, pero no permitir que el miedo a la burocracia impida un cambio efectivo

1. **¿Qué es un repositorio?**
El repositorio es el lugar donde el sistema de control de versiones realiza un seguimiento de todos los cambios que realiza. La mayoría de los sistemas de control de versiones almacenan el estado actual del código, junto con cuándo se realizó cada cambio,quién lo hizo y un mensaje de registro de texto que  explica por qué hicieron el cambio.
Existen repositorios centralizados en donde hay un repositorio central al que todos envían sus cambios. Cada desarrollador conserva una copia de la última versión del repositorio, y cada vez que realiza un cambio, envía ese cambio de vuelta al repositorio principal.
El repositorio centralizado es una mejora sobre tener que acceder directamente a la máquina donde vive el repositorio, pero aún tiene limitaciones. Primero, solo tiene la última versión del código. Para ver el historial de cambios, debe solicitar esa información al repositorio.Eso trae el segundo problema. Debe poder acceder al repositorio remoto, normalmente a través de una red. Eso destaca una de las mayores ventajas de un DVCS(Sistema de control de  versiones distribuidos), que es el modelo que sigue Git.En lugar de tener  un repositorio central al que usted y todos los demás en su equipo envíen  cambios, cada uno tiene su propio repositorio que tiene toda la historia  del proyecto. Hacer una confirmación no implica conectarse a unrepositorio  remoto; El cambio se registra en su repositorio local.

1. **¿Qué se debe almacenar en un repositorio?**
Se debe almacenar en el repositorio el código fuente  de su proyecto. Sin eso, no puede corregir errores o implementar nuevas funciones. La mayoría de los proyectos tienen algún tipo de archivos de compilación. Estos  deben almacenarse para que pueda compilar su código fuente en algo utilizable. Otros elementos comunes para almacenar en su repositorio son archivos de  configuración de muestra, documentación, imágenes que se utilizan en la  aplicación y, por supuesto, pruebas unitarias.

1. **¿Cómo se puede determinar que incluir en un repositorio?**
Se debe de incluir todos los archivos que sean necesarios para que el proyecto  funcione de manera correcta, siempre se ha de preguntar si faltando un archivo se puede llegar a producir un error.La regla no se aplica a las herramientas que  debe usar. Debe incluir el archivo Ant build.xml pero no todo el programa Ant. 
Estas deben almacenarse por separado de su proyecto.

1. **¿Qué es un *Working Tree*?**
Es donde se tienen todos los archivos del proyecto: el código fuente, los archivos de compilación, las pruebas unitarias, etc., también se le conoce como la copia de trabajo. 
La vista actual del flujo de cambios y o modificaciones de archivos dentro de nuestro proyecto en el repositorio.

1. **¿Qué hace un *commit*?**
Contiene información sobre ese momento determinado, los cambios del autor desde el último commit, el  commit anterior (conocido como parent), etc.Otra forma de entenderlo también sería, como una "foto" de uno o varios archivos del repositorio en un momento determinado.
Agrega una nueva version al repositorio y almacena el mensaje de log y explica el cambio que hizo.

1. **¿Qué ocurre cuando se hace *push*?**
Es cuando se sube un cambio de mi repositorio local a mi repositorio remoto.
Se utiliza para subir confirmaciones de cambios realizadas en una rama local a un repositorio remoto.

1. **¿Qué ocurre cuando se hace *fetch*?**
Trae los cambios, pero los deja en otro branch, hasta que se hace el git merge para traerlos al branch local.
Contrario a push, obtiene los cambios de un repositorio remoto.

1. **¿Qué es un *branch* o rama?**
Una rama Git es simplemente un apuntador móvil apuntando a una de esas confirmaciones. La rama por defecto de Git es la rama master. Con la primera confirmación de cambios que realicemos, se creará esta rama principal master apuntando a dicha confirmación.
En cada confirmación de cambios que realicemos, la rama irá avanzando automáticamente.
Es el seguimiento de los cambios realizados en su contenido separado por otras ramas para que se puedan crear versiones alternativas. Se ocupan para desarrollar funcionalidades aisladas una de otras.

1. **¿Qué es un *merge*?**
La herramienta git merge se utiliza para fusionar uno o más ramas dentro de la rama que tienes activa. A continuación avanzará la rama actual al resultado de la fusión.
El comando git merge fue introducido por primera en Procedimientos Básicos de Ramificación. A pesar de que se utiliza en diversos lugares en el libro, hay muy pocas variaciones del comando merge — en general, sólo git merge <branch> con el nombre de la rama individual que se desea combinar.
Proceso de combinar 2 ramas, estos cambios deben ser aprovados por los colaboradores.

1. **¿Qué es un *strict locking*?**
Es que solo una persona puede tener una copia del código a la vez.
Se pide el repositorio para hacer cambios a un artefacto y evitando cambios simultaneos.

1. **¿Qué es un *optimistic locking*?**
Permite que varios desarrolladores trabajen en el mismo código en los mismos archivos con el supuesto de que la mayoría de las veces sus cambios no entrarán en conflicto.Permite que varios desarrolladores trabajen en el mismo código, en los mismos archivos con el supuesto de que la mayoria de las veces sus cambios no entrarán en conflicto.


# NO HACER

1. ¿Con qué comandos se configuran el nombre el correo para git?

1. ¿Qué es el archivo *.gitignore*?

2. ¿Qué debería poner en el archivo *.gitignore*?