# Preguntas

1. ¿Qué es un sistema de control de versiones?
	Es una herramienta que provee mecanismos para ayudar a versionar y darle seguimiento y control a los cambios en los archivos de tu proyecto
	Permite accesar a todas las versiones del codigo fuente y tambien permite la colaboracion entre los miembros del equipo
1. ¿Cuáles son los objetivos de un sistema de control de versiones?
	Retener y proveer acceso a todas las versiones de algun archivo que se haya almacenado en ellos
	Proveer mecanismos para que equipos de personas colaboren en el mismo proyecto 
1. ¿Cuáles son las pautas para controlar los cambios de diseño?
	Seguir un procedimiento de cambios sistematico
		Haciendo esto se vuelve claro que cambios seran considerados para añadirlos como cambios al repositorio
	Manejar peticiones de cambio en grupos
		Puede ser tentador realizar cambios al proyecto conforme lleguen ideas, sin embargo esto puede ocasionar que algunos cambios muy buenos se consideren en el contexto de fechas de entrega atrazados, lo cual lleva a que nunca se implementen.
		Una posible solicion es ir almacenando los cambios y luego considerarlos por lotes para implementar los que se consideren mas beneficos para el proyecto
	Estimar el costo de cada cambio
		Es importante estimar el costo de cada cambio, tomando en cuenta el tiempo que tomara implementarlo incluyendo las pruebas, las revisiones de codigo y los cambios que se tengan que realizar a la documentacion
	Tener cuidado con altas cantidades de cambios
		Los cambios son inevitables en cualquier proyecto de software, sin embargo es importante saber que altos volumenes de cambios son señales de que los requerimientos, el diseño o la arquitectura no fueron bien hechos.
	Establecer un comite de control de cambios
		Los comités de control de cambio tienen el tranajo de separar los buenos cambios de los malos cambios.
		Ellos se reunen a analizar los cambios propuestos y pueden aceptarlos, rechzarlos o sugerir cambios a ellos.
	Tener cuidad con que la burocracia se entrometa en el proceso de control de cambios}
		Es importante asegurarse de controlar los cambios y documentarlos.
		Muchos proyectos pueden terminar sin ser entregados a tiempo al acordar cambios sin documentarlos ya que estos cambios nunca se estimarion
1. ¿Qué es un repositorio?
	Es donde el sistema de control de versiones da seguimiento a todos los cambios que hagas 
1. ¿Qué se debe almacenar en un repositorio?
	El codigo fuente actual, los cambios que se han hecho, la fecha de cada cambio, el autor del cambio y un mensaje que diga porque se hizo el cambio
	Tambien deberian almacenarse scripts de bases de datos, pruebas, artefactos de diseño, docuementacion, librerias, etc...
	En general, todo lo que necesites para trabajar en tu proyecto y que podria cambiar o modificarse con el paso del tiempo
1. ¿Cómo se puede determinar que incluir en un repositorio?
	Se deberia almacenar todo lo que en un proyecto que se necesita modificar o mejorar conforme pase el tiempo
1. ¿Qué es un *Working Tree*?
	La vista actual del respositorio en la que estas trabajando y tiene todos los archivos del repositorio
1. ¿Qué hace un *commit*?
	Añade una nueva version de los archivos al repositorio y el mensaje explicando porque se hicieron los cambios 
1. ¿Qué ocurre cuando se hace *push*?
	Envia los datos del repositorio local a otros repositorios para mantenerlos sincronizados
1. ¿Qué ocurre cuando se hace *fetch*?
	Crea una copio de los cambios hechos en algun repositorio remoto en tu maquina local 
1. ¿Qué es un *branch* o rama?
	Es una divergencia del repositorio principal. Cada branch da seguimiento y control a sus cambios independientemente de las demas branches
1. ¿Qué es un *merge*?
	Es cuando se combinan los cambios de dos branches en una sola
1. ¿Qué es un *strict locking*?
	Es un tipo de bloqueo en algunos sistemas de control de version que evita que multiples usuarios realizen cambios a la vez. Cada vez que un usuario solicita realizar cambios al repositorio, el repositorio bloquea los cambios de otros usuarios
	Una de sus desventajas es que disminuye la productividad ya que solo una persona puede trabajr en el repositorio a la vez
1. ¿Qué es un *optimistic locking*?
	Es un tipo de bloqueo en algunos sistemas de control de version que asume que en la mayoria de los casos, los cambios de multiples desarrolladores no crearan conflictos
	Permite a mas de una persona trabajar al mismo tiempo por lo que incrementa la productividad
<!-- 1. ¿Con qué comandos se configuran el nombre el correo para git?

1. ¿Qué es el archivo *.gitignore*?

2. ¿Qué debería poner en el archivo *.gitignore*? -->
