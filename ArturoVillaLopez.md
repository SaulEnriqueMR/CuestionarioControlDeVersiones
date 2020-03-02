# Preguntas

1. ¿Qué es un sistema de control de versiones?
	Es una metodologia o Herramientax para mantener múltiples versiones de sus artefactos, de modo que al modificar un archivo
	aún se permite acceder a las revisiones anteriores. Tambien permiten el desarrollo de software de manera colaborativa

1. ¿Cuáles son los objetivos de un sistema de control de versiones?
	Conservar y proporcionar acceso a todas las versiones de cada archivo que se haya almacenado en él y permite que los equipos colaboren

1. ¿Cuáles son las pautas para controlar los cambios de diseño?
	Seguir un procedimiento sistematico de control de cambios para cuando se tienen muchas solicitudes de cambio, Manejar las solicitudes de cambio en grupos para saber que cambios son realmente necesarios de aplicar, Estimar el costo de cada cambio, Tener cuidado con los grandes volumenes de cambios ya que son una señal de advertencia de que los requisitos, la arquitectura o los diseños no se hicieron lo suficientemente bien para respaldar una construccion efectiva, Establecer una junta de control de cambios con el equipo de trabajo y Estar atento a la burocracio sin que esta genre un miedo que implique el control efectivo del cambio.

1. ¿Qué es un repositorio?
	El repositorio es el lugar donde el sistema de control de versiones realiza un seguimiento de todos los cambios que se realizan.

1. ¿Qué se debe almacenar en un repositorio?
	Todo lo que necesita para trabajar en el proyecto. El repositorio necesita una copia de todo en el proyecto que sea esencial para que pueda modificarse, mejorarse y crear nuevas versiones del mismo. Otros elementos comunes para almacenar en el repositorio son archivos de configuración de muestra, documentación, imágenes que se utilizan en la aplicación y pruebas unitarias.

1. ¿Cómo se puede determinar que incluir en un repositorio?
	Conociendo las consecuencias de no tener tal archivo, y si su ausencia perjudicaria al proyecto.

1. ¿Qué es un *Working Tree*?
	El arbol de trabajo (*Working Tree*) es la vista actual en el repositorio en donde se tienen todos los archivos del proyecto: el código fuente, los archivos de compilación, las pruebas unitarias, etc.

1. ¿Qué hace un *commit*?
	agrega una nueva revisión al repositorio y almacena su mensaje de registro que explica lo que hizo el cambio. Esto proporciona un registro para revisar si alguna vez es necesario descubrir por qué se realizó un cambio determinado o cuándo se introdujo un error.

1. ¿Qué ocurre cuando se hace *push*?
	Es la mitad de lo que debe hacer para mantener el repositorio sincronizado con los archivos locales y viceversa.

	Se utiliza para subir confirmaciones de cambios realizadas en una rama local a un repositorio remoto.

1. ¿Qué ocurre cuando se hace *fetch*?
	Crea una copia de los cambios del repositorio remoto. Este paso es lo contrario a *Push*. En lugar de enviar cambios a otro repositorio, le pide al repositorio remoto que le envíe los cambios que tiene. Luego, fusiona esos cambios en el historial local.

1. ¿Qué es un *branch* o rama?
	Es un directorio aparte que copia todos los archivos de la *master* y permite realizar cambios o experimentar sin afectar al proyecto que ya esta aprobado. Ademas de que permite a cada integrante de los equipos trabajar por separado sin afectar los cambios de los demas.

1. ¿Qué es un *merge*?
	Es combinar los cambios entre dos ramas para poder hacerlas una sola siempre y cuando ya esten aprobados los cambios que se realizaran al proyecto.

1. ¿Qué es un *strict locking*?

	Es cuando un usuario solicita acceso al repositorio para modificar el archivo bloqueando el acceso a los demas

1. ¿Qué es un *optimistic locking*?
	Permite que varios desarrolladores trabajen en el mismo codigo y los mismos archivos con el supuesto de que la mayoria de las veces los cambios no estaran en conficto

<!-- 1. ¿Con qué comandos se configuran el nombre el correo para git?

1. ¿Qué es el archivo *.gitignore*?

2. ¿Qué debería poner en el archivo *.gitignore*? -->
