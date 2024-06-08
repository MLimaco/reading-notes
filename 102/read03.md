# Introducción a Git
Git es el sistema de control de versiones distribuido nacido en el 2005, creado por el equipo de Linus Torvalds durante el desarrollo del kernel de Linux con un flujo similar a BitKeeper, el sistema de control de versiones usado con anterioridad y que dicho equipo abandonó después de diferentes tensiones entre la comunidad Linux y la empresa detrás de BitKeeper, que además empezó a cobrar por el servicio.

Un sistema de control de versiones es aquel que permite a los usuarios **guardar diferentes versiones de un archivo o conjunto de archivos** de modo que estos puedan en **cualquier momento** acceder a ellos si es necesario, monitorear los cambios y comparar cambios para encontrar por ejemplo errores en el código. Esto se consigue mediante *snapshots, seguimiento de datos y estados*.

* Snapshot: Cada que guardas una versión cambiada de un proyecto mediante el comando `commit` Git crea un snapshot, es decir, una copia del proyecto en el estado actual del `commit`. 
* Seguimiento de datos: todos y absolutamente cada uno de los cambios realizados en cualquier archivo que compone un proyecto es monitoreado por git (siempre que se suba, claro). Este monitoreo permite también saber si algún archivo se corrompió o perdió al momento de cargar los datos. 
* Estados: Git maneja 3 estados para poder trabajar nuestros archivos.
     * Commited: los archivos se encuentran almacenados en la base de datos local. 
     * Modified: los archivos han sido alterados pero no almacenados en la base de datos local.
     * Staged: estado marcado de un archivo alterado que va a ser "commiteado".

A su vez existen diferentes sistemas de control de versiones:
* Local: los sistemas de control de versiones locales se encuentran alojados en el disco duro de la computadora en la que se trabaja.
* Centralizado: los sistemas de control de versiones centralizados se encuentran alojados en un sólo servidor que almacena todos los cambios y versiones de archivos. A diferencia del local, esta version facilitó el trabajo colaborativo dejando ver a los programadores los avances de los otros así como establecer administradores que puedan controlar los permisos de los programadores involucrados.
* Distribuido: es el sistema de control de versiones que trabaja con repositorios espejo, es decir copias exactas del repositorio en los dispositivos de los programadores involucrados en la colaboración. De este modo deja de tener el principal problema de los anteriores dos sistemas, la dependencia de un sólo repositorio que si se malogra o corrompe pone en riesgo todo el trabajo. Al existir copias espejo alojadas en las computadoras de los trabajadores, existen varios backups en caso de algún error. 

# Resolución de Preguntas
1. ¿Qué es el control de versiones?
Es un sistema que permite revisar varias versiones de un documento o grupo de documentos mediante el guardado de cambios constante. Mediante el control de versiones se puede modificar un archivo para regresar a una versión anterior, mantener el control de que cambios se hicieron e incluso compararlo. Funciona no sólo como forma segura de evitar que se pierdan los avances, sino también para facilitar la detección de errores al momento de realizar cambios en un archivo. Por otro lado, permite que multiples personas puedan trabajar en paralelo en el mismo proyecto a través del DCVS (control de versiones distribuido), cada usuario tiene una copia del repositorio, pero estas copias intercambian y actualizan revisiones entre sí. 
2. ¿Qué es “clone” en Git?
Clonar es crear una copia de un repositorio existente. Al momento de clonar un repositorio, generas una copia de todas las versiones del proyecto en el repositorio.
3. ¿Cuál es el comando para rastrear y preparar archivos?
`$ git add *nombre del archivo*` también puede ser `$ git add *nombre del archivo*`
5. ¿Cuál es el comando para tomar una instantánea de los archivos modificados?
`$ git commit -m "especificacion de los cambios realizados"`
6. ¿Cuál es el comando para enviar los archivos modificados a Github?
`$ git push origin main`
