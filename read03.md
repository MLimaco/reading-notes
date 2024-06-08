# Introducción a Git
Notas
# Resolución de Preguntas
1. ¿Qué es el control de versiones?
Es un sistema que permite revisar varias versiones de un documento o grupo de documentos mediante el guardado de cambios constante. Mediante el control de versiones se puede modificar un archivo para regresar a una versión anterior, mantener el control de que cambios se hicieron e incluso compararlo. Funciona no sólo como forma segura de evitar que se pierdan los avances, sino también para facilitar la detección de errores al momento de realizar cambios en un archivo. Por otro lado, permite que multiples personas puedan trabajar en paralelo en el mismo proyecto a través del DCVS (control de versiones distribuido), cada usuario tiene una copia del repositorio, pero estas copias intercambian y actualizan revisiones entre sí. 
2. ¿Qué es “clone” en Git?
Clonar es crear una copia de un repositorio existente. Al momento de clonar un repositorio, generas una copia de todas las versiones del proyecto en el repositorio.
3. ¿Cuál es el comando para rastrear y preparar archivos?
`$ git add *.c` `$ git add LICENSE` `$ git commit -m “any message here”`
5. ¿Cuál es el comando para tomar una instantánea de los archivos modificados?
`$ git commit -a`
6. ¿Cuál es el comando para enviar los archivos modificados a Github?
`$ git push origin master`
