# Unforgettable_Git
CURSO GIT Paso a paso.

Definición 1. Un control de versiones es una herramienta para gestionar cambios o colaborar con más personas en un fichero. Entre los principales usos.

1. Conceptos previos.

Definición 1.1. Un repositorio es una colección de ficheros y directorios que queremos versionar.
Definición 1.2. Un cambio es una modificación de ficheros.

2. Tipos de controles de versiones.

2. 1. Control de versiones centralizados. 

Para leer el Libro de Ajedrez, Dados y Tablas de Alfonso X el Sabio de la Real Biblioteca del Monasterio de San Lorenzo de El Escorial, 
hay que leerlo en persona. Si quiero estudiarlo en mi casa, tendré que conseguir una versión escaneada de los capítulos que me interesan, 
no me puedo llevar ni copiar el manuscrito entero. Si alguna persona tiene que restaurarlo, o Alfonso X resucita y quiere añadir nuevas jugadas, entonces, tiene que pedir un permiso y tiene que ir a la biblioteca.

2. 1. Control de versiones distribuidos.

Josechu sube los apuntes al Moodle. Todos tenemos acceso a los apuntes de Josechu de Geometría. Trabajas sobre ellos, los emborronas, añades gráficas. No necesito estar en las clase de Josechu para ver sus apuntes en la pizarra, porque los tengo descargados (offline). Josechu tampoco puede ver las atrozidades matemáticas que escribo porque todavía no le he mandado las erratas (push/pull de archivos). Las erratas que vemos tienen que 
ser enviadas a Josechu para que haga las modificaciones, y los estudiantes no se encuentren con un signo menos donde no había. Josechu es el repositorio central.

Aquí es dónde enocontramos Git :). Un sistema de control de versiones distribuido.

3. Git 
 3. 1. Conceptos previos.

Definición 3.1. Un registro histórico es la trazabilidad del fichero. ¿Quién lo modifició?¿Cuándo?¿Por qué?
Definición 3.2. Un commit es la unidad mínima de almacenamiento.

3. 2. ¿Para qué usamos Git?

Tenemos Git para mi. Voy controlando los cambios que hago.

O podemos usar Git con más gente. Sincronizar a todas las personas que colaboran en un proyecto a través de un repositorio central. En este caso el repositorio central/remoto se llama GitHub. 

¿Cómo vamos trabajando con las modificaciones de los ficheros?

Tenemos tres identidades en las que vamos pasando los archivos: 
Mi ordenador-GitHub (el repositorio central/remoto)-Servidor

<img src="./image1.jpg" />