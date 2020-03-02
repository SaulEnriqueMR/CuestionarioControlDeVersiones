#Preguntas
1. ¿Qué es un sistema de control de versiones?
R=  Metodología a herramienta que registra los cambios realizados en un artefacto a lo largo del tiempo de modo que puedes Recuperar versiones específicas más adelante

1. ¿Cuáles son los objetivos de un sistema de control de versiones?
 R =  Mantener y proveer acceso a cada versión que un archivo ha tenido desde que se almacenó y proveer una formade metadatos

1. ¿Cuáles son las pautas para controlar los cambios de diseño?
R =  Seguir un procedimiento sistemático de control de cambios
• Manejar solicitudes de cambio en grupos
• Estimar el costo de cada cambio
• Tener cuidado con los grandes volúmenes de cambio
• Establecer un tablero de control de cambios o su equivalente de una manera 
que tenga sentido para el proyecto
• Esté atento a la burocracia, pero no permitir que el miedo a la burocracia 
impida un cambio efectivo


1. 	 ¿Qué es un repositorio?
R = un almacén donde el sistema controlador de versiones mantiene los cambios que se han hecho.
	

1. 	¿Qué se debe almacenar en un repositorio?
R= 
 Se debe guardar todo lo necesario para continuar con el proyecto: 
El código fuente del proyecto, build files, archivos de configuración, imágenes, pruebas de unidad.

 1. ¿Cómo se puede determinar que incluir en un repositorio?
R = Determinar qué es lo que necesario para hacer que el proyecto pueda funcionar

Responder si borro “X”, puedo continuar con mi trabajo

1.  ¿Qué es un *Working Tree*?
R = Es la vista actual del repositorio, contiene los archivos del proyecto. Puede referirse a la copia para trabajar. El directorio de los archivos

1. ¿Qué hace un *commit*?
R= Añade una nueva versión en el repositorio y guarda un mensaje explicando qué es lo que se cambió

1. ¿Qué ocurre cuando se hace *push*?
R = Enviar los cambios a un repositorio en específico
Se utiliza para subir confirmaciones de cambios realizadas en una rama local a un repositorio remoto

1.  ¿Qué ocurre cuando se hace *fetch*?
R = Pedir al repositorio los cambios que se han hecho
Contrario al push, obtiene los cambios de un repositorio remoto

1.  ¿Qué es un *branch* o rama?
R = Es el seguimiento de los cambios realizados en su contenido separado por otras ramas para que se puedan crear versiones alternativas. Se ocupan para desarrollar funcionalidades aisladas unas de otras

1.  ¿Qué es un *merge*?
R = Proceso de combinar 2 ramas, estos cambios deben ser aprobados por los colaboradores

1.  ¿Qué es un *strict locking*?
R = se pide al repositorio para hacer cambios a un artefacto y evitando cambios simultáneos

1.  ¿Qué es un *optimistic locking*?
R = Permite que varios desarrolladores trabajen el mismo código y los mismos archivos con el supuesto de que la mayoría de las veces sus cambios no entrarán de las veces sus cambios no entraran en conflicto

1.  ¿Con qué comandos se configuran el nombre el correo para git?
R = git config --global user.email "email@example.com"


1.  ¿Qué es el archivo *.gitignore*?
R= el archivo que menciona las terminaciones de los archivos que queremos ignorar

1.  ¿Qué debería poner en el archivo *.gitignore*? -->
R = las terminaciones de los archivos que no necesitamos
