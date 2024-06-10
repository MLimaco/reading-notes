# Wireframes y Conceptos Básicos de HTML
## Wireframes
La creación de wireframes es una práctica común en el campo del UX. Consiste en el *planteamiento de la estructura o jerarquía de información para el diseño de web/app/producto*. Para el proceso hay que haber realizado previamente una investigación y análisis del usuario en relación al producto, luego se procede a diseñar, hay que considerar como necesitamos que el usuario procese la información de la web y experimentar como es que el usuario interactúa con la interface del producto.  

Al momento de diseñar, hay que tener en cuenta que *los wireframes normalmente se diagraman usando elementos básicos*, sin color, fuentes y a veces sin texto; puede ser utilizando herramientas online o incluso a mano. Esto para *evitar distracciones*. La razón de esto es que si un usuario no sabe a donde ir en un simple diagrama del producto, es irrelevante qué colores o texto se utilicen. 

Una vez realizadas todas las pruebas de los diagramas básicos recién se procede a hacer un prototipado más complejo usando colores, textos, tipograficas. Este prototipo debe poder realizarse en una herramienta que sea capaz de permitir al equipo hacer pruebas con los clientes, es decir que permita la navegación sin realizar desarrollo. Puede usarse herramientas como figma o sketch, que tienen esta función haciendo unos pocos clics. 

## HTML
HTML o HyperText Markup Language, es el *lenguaje de marcado que se usa para definir la estructura del contenido de una página web mediante elementos*. Un elemento encierra diferentes partes del contenido de la web mediante etiquetas de apertura y cierre y le otorga características, de modo que dichas partes encerradas en un elemento particular tendrán características atribuidas de la etiqueta con la que fueron encerradas y serán diferentes a otras partes que hayan sido etiquetadas de otra forma en otros elementos. 

Como se mencionó líneas atrás los elementos están compuestos de etiquetas de apertura y cierre que encierran parte del contenido de la web. Se debe considerar que en la etiqueta de cierre se puede también colocar atributos, estos contienen información adicional del contenido que es visible sólamente al momento de revisar el código, es decir, no se visualiza al momento de renderizar la web. 

# Resolución de Preguntas
1. ¿Qué es HTML y por qué lo usamos?
HTML es un **lenguaje de marcado** cuyo nombre viene de las siglas de HyperText Markup Language. Se utiliza para **estructurar las páginas web y sus contenidos**. Mediante elementos logra que el contenido luzca o se comporte de una forma en particular.
2. ¿Cuáles son las 3 partes principales de un elemento HTML?
Las partes de un elemento son las siguientes:
    1. **Etiqueta de Apertura**: Define donde comienza el elemento, consiste en el nombre del tipo de elemento encerrado entre paréntesis angulares `<>`. 
    2. **Etiqueta de Cierre**: Define donde finaliza un elemento. Es idéntico a la etiqueta de apertura, salvo por la presencia de un `/` antes del nombre de la etiqueta. 
    3. **Contenido**: Es el contenido de un elemento, puede ser por ejemplo texto, vacío, imágenes, vídeos, etc.
3. ¿Cómo se llama cuando le das información extra a un elemento?
A la informacion adicional de un elemento se le llama atributo. Este no aparece visualmente al momento de previsualizar el elemento. Un atributo debe tener: 
    1. un espacio entre el nombre del atributo y el nombre del elemento (o el elemento anterior si hay mas de un elemento)
    2. nombre del atributo seguido de simbolo igual `=`
    3. el valor del atributo entre comillas `"nombreDelAtributo"`
4. ¿Qué es un elemento semántico?
Un elemento semántico es aquel que **define el significado, estructura o estilo de una palabra**. Ayudan a estructurar la página para que sea legible para el buscador de Google además de ayudar a la legibilidad para los usuarios.