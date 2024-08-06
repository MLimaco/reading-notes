# Lectura 1 Primeros Pasos e Introducción a HTML

## Primeros Pasos

1. Crea un poema corto describiendo cómo HTTP envía datos entre computadoras.

El HTTP es un protocolo que permite al servidor comunicarse con clientes. Una vez que el navegador averigüó donde se encuentra la página web mediante el DNS, envía mensajes HTTP para que pueda enviar una copia de la página web al servidor y así mostrar la web y ejecutar todos los comandos contenidos.

2. Describe como los archivos HTML, CSS y JS son “analizados” en el navegador.

El navegador analiza los archivos de la siguiente forma: estructura es HTML, colores y estilos es CSS y funciones interactivas es Javascript.

3. ¿Cómo puedes encontrar imágenes para agregar a una página web?

Se buscan las imágenes que se deseen colocar y a partir de ahi o se descargan y se cargan directamente a un servidor donde se alojarán para poder ser llamadas por la web para mostrarse, o copias el enlace actual de la imagen y lo colocas en la web para que lo llame, claro que dependes de un tercero. Hay que considerar que todas las imagenes están protegidas por derechos de autor, así que es bueno usar un filtro de licencias. 

4. ¿Cómo creas una String en comparación con un Number en Javascript?

Se crea un string colocando el valor entre comillas o si se quiere convertir un numero a string usando la función toString(). En el caso de querer convertir una variable de string a number se usa el parseInt().

5. ¿Qué es una Variable y por qué son importantes en JavaScript?

Las variables son contenedores que pueden almacenar información. Se deben declarar antes de usarse y el valor que contienen puede cambiar o no según como se trabaje. El hecho que los valores de las variables puedan cambiar hace que la web tenga funciones dinámicas y personalizables.

## Introducción a HTML

1. ¿Qué es un atributo en HTML?

Es información adicional que se agrega a los elementos HTML. Esta información adicional no aparece visible en el contenido web pero que podría afectarla, pero se puede usar para diferentes cosas como agregar altura, anchura, describir una imagen, llamar un enlace, etc.

2. Describe la anatomía de un elemento en HTML.

Un elemento HTML está compuesto por una etiqueta de apertura y cierre, que son las que definen de que tipo de elemento se trata. En medio de ambas se encuentra el contenido. Sse debe considerar que dentro de la etiqueta de apertura puede colocarse atributos y estilos. 

3. ¿Cuál es la diferencia entre las etiquetas article y section?

Un elemento article separa un bloque de contenido del resto, sirve más para entradas de blog por ejemplo. El elemento section es para agrupar en lugar de separar. Se pueden usar ambas de forma combinada y es normal confundirlas. 

4. Qué elementos se incluyen en una página web “típica”?

Una web típica contiene un encabezado donde normalmente se coloca el logo de la empresa, barra de navegación que contiene los enlaces más importantes de la web, contenido el cual ocupa la mayoría del espacio y muestra la informacion de las diferentes páginas, barra lateral y pie de página.Se debe considerar que muchas veces en un sitio web casi todos los elementos menos el contenido y la barra lateral son estáticos. 

5. ¿Cómo influyen los metadatos en el Posicionamiento en buscadores (SEO)?

Google para poder posicionar la web analiza la información en los metadatos y valida que tengan correlación con el contenido que muestra la web, y a la vez correlación con la búsqueda del usuario. Es por ello que algunas páginas se posicionan mejor dependiendo de los términos usados en búsqueda del usuario pues pueden tener más o menos correlación. 

6. ¿Cómo se utliza el elemento meta en HTML cuando se quiere especificar metadata?

Se coloca dentro del elemento `<head>`, cuya función es contener información y metadatos de la web. El elemento meta es vacío, por lo que no tiene etiqueta de cierre y cada se usa por cada grupo de información que se quiere detallar en la web. Entonces si se quiere especificar: autor, keywords, titulo y descripción; se deberán crear cuatro elementos meta. 