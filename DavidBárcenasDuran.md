# Preguntas

1. ¿Qué es un sistema de control de versiones?

Es un sistema que registra los cambios realizados en un archivo o conjunto de artefactos a lo largo del tiempo de modo que puede recuperar versiones anteriores

2. ¿Cuáles son los objetivos de un sistema de control de versiones?

Mantener huella de los cambios y proveer acceso a cada versión que un archivo ha tenido desde que se almaceno y proveer una forma de metadatos

3. ¿Cuáles son las pautas para controlar los cambios de diseño?

4. ¿Qué es un repositorio?

Es el lugar donde el sistema de control de versiones realiza un seguimiento de todos los cambios que hace

5. ¿Qué se debe almacenar en un repositorio?

Se debe guardar todo lo necesario para continuar con el proyecto, esto incluye: código fuente, archivos de configuración, documentación, recursos, pruebas unitarias.

6. ¿Cómo se puede determinar que incluir en un repositorio?

Responder a la pregunta ¿Si no tuviera “X” podría terminar con mi trabajo en este proyecto? Si la respuesta es no, debe incluir.

7. ¿Qué es un *Working Tree*?

La vista actual del flujo de cambios y o modificaciones de archivos dentro de nuestro proyecto en el repositorio

8. ¿Qué hace un *commit*?

Agrega una nueva versión al repo y almacena el mensaje de log y explica el cambio que hizo

9.  ¿Qué ocurre cuando se hace *push*?

Se utiliza para subir confirmaciones de cambios realizados en una rama local a un respositorio remoto.

10. ¿Qué ocurre cuando se hace *fetch*?

Contrario a push, obtiene los cambios de un repositorio remoto

11. ¿Qué es un *branch* o rama?

Es el seguimiento de los cambios realizados en su contenido separado por otras ramas para que se puedan crear versiones alternativas. Se ocupan para desarrollar funcionalidades aisladas

12. ¿Qué es un *merge*?

Proceso de combinar dos ramas, estos cambios den ser aprobados por los colaboradores

13. ¿Qué es un *strict locking*?

Se pide al repositorio para hacer cambios a un artefacto y evitando cambios simultaneos

14. ¿Qué es un *optimistic locking*?

Permite que varios desarrolladores trabajen en el mismo código y los mismos archivos con el suspuesto que la mayoría de las veces su cambios no entraran el conflicto

15. ¿Con qué comandos se configuran el nombre el correo para git?

$ git config --global user.email (correo)

16. ¿Qué es el archivo *.gitignore*?

Es un archivo que se ocupa para ocultar ciertos archivos que se desea que git ignore y no los tome en cuenta en el control de versiones.

17. ¿Qué debería poner en el archivo *.gitignore*?
 
Archivos inecesarios para la ejecución del programa, compilados por ejemplo.
