#Cuestionario Control De Versiones
1.	¿Qué es un sistema de control de versiones?
c.	Metodología o herramienta que registra los cambios en un archivo/ artefacto o conjunto de archivos a lo largo del tiempo de modo que puedes recuperar versiones especificas más adelante.

2.	¿Cuáles son los objetivos de un sistema de control de versiones?
c.	Mantener y proveer acceso a cada versión que un archivo ha tenido desde que se almaceno y proveer una forma de metadatos (información para describir los datos guardados). Además, permite a los equipos distribuidos colaborar.

3.	¿Cuáles son las pautas para controlar los cambios de diseño?
a.	Seguir un procedimiento sistemático de control de cambios.
b.	Manejar solicitudes de cambios en grupos
i.	Escribir todos los cambios e ideas para revisarlos en conjunto y elegir cual es el mas beneficial al proyecto.
c.	Estimar el costo de cada cambio
i.	Estimar el tiempo, revisión del código, la actualización a todos los integrantes del proyecto, etc.
d.	Estar alerta de altos volúmenes de cambios
i.	Es una alerta de que los requerimientos, arquitectura o diseño de alto nivel no esta bien hecho como para soportar la construcción.
e.	Establecer un panel para el control de cambios
i.	Ayuda a que las personas tengan una petición de cambio como: características, errores,
f.	Mantener la disciplina en los cambios con burocracia pero no al punto de que impida el control efectivo de cambios

4.	¿Qué es un repositorio?
c.	Es un lugar donde se pueden mandar los cambios remotamente por medio de la conexión a la red a una central donde todos envían sus cambios y cada desarrollador mantiene una copia de los últimos cambios en el repositorio.

5.	¿Qué se debe almacenar en un repositorio?
c.	Prof: Se debe guardar todo lo necesario para continuar con el proyecto, esto incluye: código fuente, archivos de configuración, documentación, recursos, pruebas unitarias.

6.	¿Cómo se puede determinar que incluir en un repositorio?
a.	Responder a la pregunta ¿Si no tuviera “X” pordria terminar con mi trabajo en este proyecto? Si e son, se debe incluir

7.	¿Qué es un *Working Tree*?
b.	Un árbol de trabajo es la vista actual del flujo de cambios y o modificaciones de archivos dentro de nuestro proyecto en el repositorio

8.	¿Qué hace un *commit*?
b.	Agrega una nueva versión al repositorio y almacena el mensaje de log y explica el cambio que hizo

9.	¿Qué ocurre cuando se hace *push*?
a.	Se utiliza para subir confirmaciones de cambios realizadas en una rama local a un repositorio remoto

10.	¿Qué ocurre cuando se hace *fetch*?
a.	Contrario a push, obtiene los cambios de un repositorio remoto

11.	¿Qué es un *branch* o rama?
a.	El seguimiento de los cambios realizados en su contenido separado por otras ramas para que se puedan crear versiones alternativas. Se ocupan para desarrollar funcionalidades ausladas unas de otras

12.	¿Qué es un *merge*?
a.	Proceso de combinar 2 ramas, estos cambios deben ser aprobados por los colaboradores

13.	¿Qué es un *strict locking*?
a.	Se pide al repositorio para hacer cambios a 1 artefacto evitando cambios simultaneos

14.	¿Qué es un *optimistic locking*?
a.	Permite que varios desarrolladores trabajen en el mismo código y los mismos archivos con el supuesto de que la mayoría de las veces sus cambios no entraran en conflicto.
