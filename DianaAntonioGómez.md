APreguntas
1.	¿Qué es un sistema de control de versiones?
Es un mecanismo para mantener múltiples versiones de artefactos, de manera que cuando se modifica uno, es posible acceder a las revisiones previas. También es un mecanismo por el cual personas involucradas en la entrega de software colaboran.

PROF: Metodología o herramienta que registra los cambios en un archivo/ artefacto o conjunto de archivos a lo largo del tiempo de modo que puedes recuperar versiones especificas más adelante.
2.	¿Cuáles son los objetivos de un sistema de control de versiones?
Retener y proveer de acceso a cada versión de cada archivo que se ha almacenado en el sistema de control de versiones.
    Proveer de una forma para que los metadatos se agreguen a archivos únicos o colecciones de archivos.
Permitir a equipos distribuidos a través del espacio y tiempo colaborar.
PROF: Mantener la huella de los cambios y proveer
3.	¿Cuáles son las pautas para controlar los cambios de diseño?
Siga un procedimiento sistemático de control de cambios
Manejar solicitudes de cambio en grupos
Estime el costo de cada cambio
Tenga cuidado con los grandes volúmenes de cambio
Establezca un tablero de control de cambios o su equivalente de una manera que tenga sentido para su
proyecto
Esté atento a la burocracia, pero no permita que el miedo a la burocracia impida un cambio efectivo.
controlar

4.	¿Qué es un repositorio?
El repositorio es el lugar donde el sistema de control de versiones realiza un seguimiento de todos los cambios que realiza.
5.	¿Qué se debe almacenar en un repositorio?
Todo lo que necesitas para trabajar en tu proyecto.
Algún tipo de archivos de compilación. Algunos de los más comunes son Makefiles, Rakefiles o Ant’s build.xml.
Archivos de configuración de muestra, documentación, imágenes que se utilizan en la aplicación y, por supuesto, pruebas unitarias.
Prof: Se debe guardar todo lo necesario para continuar con el proyecto, esto incluye: código fuente, archivos de configuración, documentación, recursos, pruebas unitarias.
6.	¿Cómo se puede determinar que incluir en un repositorio?
Responder a la pregunta ¿Si no tuviera “X” pordria terminar con mi trabajo en este proyecto? Si e son, se debe incluir
7.	¿Qué es un *Working Tree*?
Un árbol de trabajo es la vista actual del flujo de cambios y o modificaciones de archivos dentro de nuestro proyecto en el repositorio
8.	¿Qué hace un *commit*?
Agrega una nueva versión al repositorio y almacena el mensaje de log y explica el cambio que hizo
9.	¿Qué ocurre cuando se hace *push*?
Push es lo que hace cuando desea enviar sus datos a otro repositorio para que puedan compartirse con otros desarrolladores.
10.	¿Qué ocurre cuando se hace *fetch*?
Crea una copia de los cambios del repositorio remoto para usted. Este paso es como el reverso de empujar. En lugar de enviar cambios a otro repositorio, le pide al repositorio remoto que le envíe los cambios que tiene.
11.	¿Qué es un *branch* o rama?
a.	El seguimiento de los cambios realizados en su contenido separado por otras ramas para que se puedan crear versiones alternativas. Se ocupan para desarrollar funcionalidades aisladas unas de otras.
12.	¿Qué es un *merge*?
Fusionar es tomar dos o más ramas y combinar su historia en una sola. Git se fusiona de la misma manera que lo haría. Compara dos conjuntos de cambios e intenta determinar dónde ocurrieron los cambios. Cuando ocurren cambios en diferentes partes de un archivo, Git puede fusionarlos automáticamente
13.	¿Qué es un *strict locking*?
Solo una persona puede tener una copia del código a la vez.
14.	¿Qué es un *optimistic locking*?
El bloqueo optimista permite que varios desarrolladores trabajen en el mismo código en los mismos archivos con el supuesto de que la mayoría de las veces sus cambios no entrarán en conflicto.
