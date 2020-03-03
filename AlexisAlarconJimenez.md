1. ¿Qué es un sistema de control de versiones?
es una herramienta que permite mantener un control de los cambios, que se van          haciendo en un proyecto, guardando una copia del proyecto antes de realizar cualquier tipo de modificación, permitiendo retomarla en caso de ser necesario. (metodologia o herramienta que registra los cambios realizados en un artefato a lo largo del tiempo de modo que puedes recuperar versiones especificas mas adelate)

1. ¿Cuáles son los objetivos de un sistema de control de versiones?
guardar todas las versiones de un proyecto permitiendo regresar a las anteriores, o retomarlas en caso de pérdida de información o errores críticos en la versión actual.()
 
1. ¿Cuáles son las pautas para controlar los cambios de diseño?
teniendo un sistema de análisis de cambios, determinado que costo tendria en el proyecto realizar algún cambio.(Manejar solicitudes de cambio en grupos
• Estimar el costo de cada cambio
• Tener cuidado con los grandes volúmenes de cambio
• Establecer un tablero de control de cambios o su equivalente de una manera
que tenga sentido para el proyecto
• Esté atento a la burocracia, pero no permitir que el miedo a la burocracia
impida un cambio efectivo)

1. ¿Qué es un repositorio?
es donde el sistema de control de versiones guarda las diferentes versiones del proyecto.
(lugar donde el sistema de control de versiones realiza el seguimiento de todos lso cambios que hace almacena la historia de todo lo que se le deposito)

1. ¿Qué se debe almacenar en un repositorio?
todas las versiones que se desarrollen de un proyecto que se puedan considerar diferentes una de otra(todo lo necesario para continuar con el proyecto 
copia de todo el proyecto para que se pueda modificar y mejorar
se necesita una copia de todo el proyecto para qe se pueda modificar y mejorar
codigo funete archivos de compilacion, archivos de configuracion y pruebas unitn y pruebas unitarias )

1. ¿Cómo se puede determinar que incluir en un repositorio?
determinando si lo que queremos incluir sería de utilidad para el proyecto, de lo contrario no debería incluirse.(respondr a la pregunta si no tuviera x podria continuar con mi trabajo en este proyecto si la respuesta es no s edebe incluir )

1. ¿Qué es un *Working Tree*?
es en donde están guardados todos los archivos que forman parte del proyecto(la vista actual del flujo de cambio y o modificacines de archivos dentro de nuestro proyecto en el repositorio)

1. ¿Qué hace un *commit*?
añade una nueva revisión a alguna de las versiones, y añadir un comentario de explicación de por qué se hizo tal cambio.

1. ¿Qué ocurre cuando se hace *push*?
se hace una actualización de los cambios en el servidor central para que los demás miembros del equipo puedan visualizar dichos cambios. (se utiliza  para subir confirmaciones de cambio s realizadas en una rama local a un repositorio remoto)

1. ¿Qué ocurre cuando se hace *fetch*?
contrario al push obtiene los cambios de un repositorio remoto
 
1. ¿Qué es un *branch* o rama?
es le seguimiento de los cambios realizados en su contenido separado por otras ramas para que se puedan crear versiones alternativas. se ocupan para desarrollar funcionalidades aisladas unas de otras

1. ¿Qué es un *merge*?
proceso de combinar 2 ramas, estos cambio deben ser aprobados por los colaboradores

1. ¿Qué es un *strict locking*?
evita que 1 archivo pueda ser modificado al mismo tiempo por 2 personas diferentes hasta que el candado
se pide al repositorio para hacer cambios y bloque el acceso a los demás

1. ¿Qué es un *optimistic locking*?
permite que varios desarrolladores trabajen en el mismo codigo y los mismmos archivos con el supuesto de que la mayoria de las veces sus cambios no entrarn en conflicto

 1. ¿Con qué comandos se configuran el nombre el correo para git?
con el uso del comando git config


1. ¿Qué es el archivo *.gitignore*?
es una herramienta que le indica a git que archivos debe omitir cuando guarde cosas en el repositorio.

2. ¿Qué debería poner en el archivo *.gitignore*? 
todas la rutas y archivos que no son requeridos 
