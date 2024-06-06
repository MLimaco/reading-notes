# Notas

## Editores de Texto
El artículo trata sobre la importancia de elegir un buen editor de texto y qué es un editor de texto. Primero que  nada, un editor de texto es una herramienta que permite escribir y administrar texto **especialmente** para crear un sitio web, aunque esto puede extenderse a más  tipos de scripts no sólo limitarse a web. Es muy importante poder elegir un buen editor de texto, ya que es una de las herramientas más importantes del desarrollo web, sin embargo hay que considerar que cada editor de texto es diferente y cada programador puede tener su editor favorito. Para poder elegir bien un editor hay que considerar los siguientes 4 puntos: 
1. El editor de texto debe poder autocompletar codigo. Ayuda mucho al momento de redactar código ya que no sólo evita errores, sino que puede ahorrar tiempo haciendo sugerencias de cómo terminar el código que el usuario está redactando y ayudar con el cerrado de etiquetas, corchetes, comillas, etc.
2. Debe ser capaz de resaltar sintaxis. Colorea los diferentes atributos del código de diferentes colores, esto facilita la lectura del código además de acelerar el descarte de errores en el código.
3. Debe tener una gran selección de extensiones. Las extensiones son complementos para el editor de texto que le permite realizar funciones adicionales a las del programa base. Con estas el usuario puede customizar el editor y que este crezca con él conforme se va complejizando el trabajo. Muchos usuarios eligen editores basandose sólamente en la selección de extensiones disponibles o el soporte que la propia comunidad o marca le dan.
4. Variedad de temas. Para mi este es el punto menos importante, pero dependerá del usuario. La variedad de temas permite cambiar por ejemplo el fondo del editor de texto, los colores del resaltado de sintaxis, etc. Para algunos usuarios es por un tema de comodidad visual pero para alguien con daltonismo, por ejemplo, esto puede ser vital. 
Muchos usuarios se preguntan por qué simplemente no utilizar el bloc de notas que viene con windows o el Text Edit de mac, la razón de esto es que estos editores son excesivamente básicos, se pueden usar, sí, pero el trabajo sería muy lento y difícil; además de que es fácil olvidarse de asegurarse que el texto que uno codea no tenga formato, ya que estos editores también tienen opciones para poner negrita, cursiva, etc al texto y eso interfiere con el código.

## Línea de Comandos
Una terminal de línea de comandos es una interface de texto que interactua con el sistema. Puede realizar las mismas acciones que se hacen en el GUI (Graphic User Interface o la interface de tu computadora que funciona con ventanas y clics) y más. Muchos usuarios lo ven como un reemplazo del GUI, en realidad se debería ver como un adicional con funciones extras.
La terminal de línea de comandos funciona como indica su nombre, con comandos que un usuario va tipeando e ingresando mientras la terminal responde con la acción solicitada. Para los que usamos windows se requerirá un cliente SSH, en el curso usamos Git Bash, la gran mayoría de terminales utilizan un comportamiento denominado como **shell**.
Lo más importante para trabajar con línea de comandos es saber donde estamos y navegar a través del directorio, esto se puede lograr con los comandos `pwd`,`ls` y `cd`.
* `pwd` nos permitirá ubicarnos en el directorio, por default nos mostrará la home a menos que estemos en una carpeta específica, en cuyo caso mostrará la ruta en cuestión.
* `ls` enlistará los elementos de la ubicación actual. Este comando puedes complejizarlo para mostrar más información, pero eso lo trataremos más adelante.
* `cd` se utiliza para navegar a través del directorio, puedes indicarle a que ubicación dirigirte. Por si solo te enviará a la home y con `..` al lado te hará retroceder un nivel en el directorio.
Lo siguiente que debes considerar es aprender a crear carpetas y archivos. Esto se consigue con los comandos `mkdir` y `touch`.
* `mkdir` permite crear carpetas en el directorio, asegurate de estar ubicado antes de crear una carpeta nueva.
* `touch` touch puede crear archivos vacíos.
Algo importnate a recordar cuando trabajas con línea de comandos, esta es **case sensitive** esto quiere decir que el uso de mayúsculas y minúsculas es importante. Todos los comandos indicados aquí son en minúsculas, si se cambiara algun caracter por una mayúscula el resultado podría ser completamente diferente al esperado. 

# Resolución de Preguntas
1. ¿Cuáles son las cuatro características importantes que se deben buscar en un editor de texto?
    1. Autocompletar Codigo
    2. Resaltado de Sintaxis
    3. Disponibilidad de amplia gama de extensiones
    4. Temas   
2. ¿Qué hacen los siguientes comandos?
    1. `pwd`
        Print Working Directory, indica en que ubicación del directorio estas ubicado. Ej: `/c/Users/limac`
    2. `ls`
        List. Enlista los elementos o archivos de una ubicación designada. Es bastante útil para cuando no sabes a que carpeta acceder por ejemplo. Puedes agregarle indicadores para cambiar la forma en que se listan los archivos. Ej: con `ls -l` puedes obtener un listado largo y detallado de los archivos de una carpeta que mostrara el owner, ultima edición y otros datos de los archivos.  
    3. `cd`
        Change Directory. Sirve para cambiar de ubicación en el directorio. Si usas solo `cd` te enviará directamente al home, pero puedes especificar a que parte del directorio deseas ir.
    4. `mkdir`
        Make directory. Con el puedes crear carpetas dentro del directorio. Asegúrate antes de estar en la ubicación deseada. 
    5. `touch`
        Crea archivos vacíos. A diferencia del `mkdir` este no crea carpetas. 
4. ¿Puedes explicar qué sucede en el siguiente escenario si ingresas estos comandos y argumentos en la línea de comandos? (Los argumentos son instrucciones adicionales dadas a un comando).
    1. `cd projects`
        Cambia la ubicación del directorio a la carpeta projects.
    2. `mkdir new-project`
        Crea una nueva carpeta en el directorio llamada new-project
    3. `touch new-project/newfile.md`
        Crea un archivo llamado newfile.md en la carpeta new-project
    4. `cd ..`
        Retrocede un nivel en el directorio
    5. `ls projects/new-project`
        Enlista los elementos de la carpeta new-project. 
