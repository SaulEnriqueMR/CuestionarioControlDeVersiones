# Preguntas :octocat:

1.	**¿Qué es un sistema de control de versiones?**
> Un sistema de control de versiones (VCS) es una metodología o herramienta que permite realizar un seguimiento de los cambios que realiza en los archivos de su proyecto.
> Los sistemas de control de versiones, también conocidos como control de origen, sistemas de gestión de código fuente o sistemas de control de revisión, son un mecanismo para mantener múltiples versiones de sus archivos, de modo que cuando modifica un archivo aún puede acceder a las revisiones anteriores. También son un mecanismo mediante el cual las personas involucradas en la entrega de software colaboran.

1.	**¿Cuáles son los objetivos de un sistema de control de versiones?**
El objetivo es tener todo lo que pueda cambiar en cualquier momento de la vida del proyecto almacenado de manera controlada. Esto le permite recuperar una instantánea exacta del estado de todo el sistema, desde el entorno de desarrollo hasta el entorno de producción, en cualquier punto de la historia del proyecto.

1.	**¿Cuáles son las pautas para controlar los cambios de diseño?**
Seguir un procedimiento sistemático de control de cambios, manejar solicitudes de cambio en grupos, estimar el costo de cada cambio, tener cuidado con los grandes volúmenes de cambio, establecer un tablero de control de cambios o su equivalente de una manera que tenga sentido para el proyecto y esté atento a la burocracia, pero no permitir que el miedo a la burocracia impida un cambio efectivo

1.	**¿Qué es un repositorio?**
El repositorio es el lugar donde el sistema de control de versiones realiza un seguimiento de todos los cambios que haces.

1.	**¿Qué se debe almacenar en un repositorio?**
Se debe almacenar el estado actual del código, junto con cuándo se realizó cada cambio, quién lo hizo y un mensaje de registro que explica por qué hicieron el cambio.
Se debe almacenar todo en lo que necesitas para trabajar con tu proyecto.

1.	**¿Cómo se puede determinar que incluir en un repositorio?**
Se debe uno preguntar: "Si no tuviera X, ¿podría hacer mi trabajo en este proyecto? Si la respuesta es no, no podrías, entonces debería ser incluido. Como todas las buenas reglas, hay una excepción. La regla no se aplica a las herramientas que deberías usar.

1.	**¿Qué es un *Working Tree*?**
Es donde se tienen todos los archivos del proyecto: el código fuente, los archivos de compilación, las pruebas unitarias, etc., también se le conoce como la copia de trabajo.

1.	**¿Qué hace un *commit*?**
Commit: apunta a un determinado archivo, marcando como era en un momento determinado. Contiene información sobre ese momento determinado, los cambios del autor desde el último commit, el commit anterior (conocido como parent), etc. También se puede entender un commit, de una forma más imprecisa y coloquial, como la modificación o el conjunto de modificaciones a uno o varios archivos del repositorio. Otra forma de entenderlo también sería, como una "foto" de uno o varios archivos del repositorio en un momento determinado.

1.	**¿Qué ocurre cuando se hace *push*?**
Se utiliza git push para subir confirmaciones de cambios realizadas en tu rama local a un repositorio remoto.

1.	**¿Qué ocurre cuando se hace *fetch*?**
Se puede recuperar un trabajo nuevo realizado por otras personas. Extraer desde un repositorio permite obtener todas las etiquetas y ramas de seguimiento remoto sin fusionar estos cambios en tus propias ramas.

1.	**¿Qué es un *branch* o rama?**
Es el seguimiento de los cambios realizados en su contenido por separado de otras ramas para que se puedan crear historias alternativas.

1.	**¿Qué es un *merge*?**
Merge es tomar dos o más ramas y combinar su historia en una sola.

1.	**¿Qué es un *strict locking*?**
Es que solo una persona puede tener una copia del código a la vez.

1.	**¿Qué es un *optimistic locking*?**
Permite que varios desarrolladores trabajen en el mismo código en los mismos archivos con el supuesto de que la mayoría de las veces sus cambios no entrarán en conflicto.
