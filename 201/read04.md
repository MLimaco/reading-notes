# Lectura 4
## Aprende HTML
### Crea Hipervínculos

1. Para crear un enlace básico, ¿en qué elemento colocamos el texto u otro contenido?

El texto que se va a convertir en enlace se coloca dentro de un elemento `<a>`.

2. ¿Qué información contiene el atributo href?

El atributo `href` contiene el enlace a donde se va a dirigir al usuario.

3. ¿Cuáles son algunas de las formas en las que podemos asegurarnos de que los enlaces a nuestras páginas sean accesibles a todos los lectores?

Usando el atributo `title` puedes incluir una descripcion del enlace.

## CSS Layout
### CSS: Layout: Normal Flow CSS: Layout: Positioning

1. ¿A qué se refiere con “normal flow”?

Se refiere a la forma en que se presentan los elementos html de la pagina si no aplicas estilo alguno y no se altera de alguna forma su comportamiento.

2. ¿Cuáles son algunas de las diferencias entre los elementos block-level e inline?

Los bloques ocupan todo el espacio horizontal de la página desde donde comienzan. Los elementos inline sólo ocupan el espacio que usa para mostrar su contenido. Tienen diferencias en cómo se aplican los estilos, por ejemplo el margin y padding que en un elemento bloque se puede aplicar a todos los lados del elemento, mientras que en un elemento de línea se puede aplicar sólo a los lados. Por otro lado, cada que comienza una nueva línea en un elemento bloque, este desplaza hacia abajo a todos los otros elementos; mientras que un elemento inline puede convivir con otros elementos inline en la misma línea, no desplaza otros elementos hacia abajo. Por otro lado, la altura de los elementos block se puede definir sin necesidad de que haya contenido que lo defina, eso no sucede con los elementos inline.

3. El ___ positioning es la posición por defecto de todos los elementos en html.

Static positioning o `position : static`. El valor por default de cualquier elemento html. 

4. Nombra algunas ventajas de utilizar absolute positioning en un elemento. 

Permite el control preciso de su ubicación, lo que sirve para poder trabajar diseños complicados o superpuestos.

5. ¿Cuál es una diferencia clave entre fixed positioning y absolute positioning?

Aplicar absolute positioning a un elemento significa que este se posiciona en una coordenada fija del elemento "padre" elegible más cercano. Esto quiere decir que el elemento con absolute positioning depende de otro para posicionarse. Mientras tanto la posición relativa es en relación a la posición original del elemento.

Por otro lado el elemento con absolute positioning queda exento del flujo normal del HTML, esto quiere decir que si dicho elemento en la estructura html estaba contenido dentro de otro elemento, si no es un elemento padre elegible, el elemento con absolute positioning lo va a ignorar y va a moverse fuera de dicho elemento si puede hacerlo.



## Aprende JS
### Funciones

1. Describe la diferencia entre una declaración de función y una invocación de función.

Cuando declaras una función estás definiendo desde cero que es lo que va a hacer la función, que parámetros usará, que código ejecutará, etc. Cuando invocas una función la estás llamando para que se ejecute, para hacer esto tiene que invocarse la función y colocar los parámetros necesarios para que funcione o dará error.

2. ¿Cuál es la diferencia entre un parameter y un argument?

Un parámetro es una variable que se utiliza al declarar la función. Un argumento es el valor que se utiliza en lugar del parámetro al invocar o llamar la función.

## Miscelánea
### Beneficios del Pair Programming

1. Escoge 2 beneficios del pair programming y reflexiona acereca de cómo estos beneficios te pueden ayudar en tu carrera como programador.

    * Código de mayor calidad como resultado de la revisión en tiempor real.
    * Feedback rápido

    Creo que estos son los puntos más importantes en la forma en la que trabajo yo, dado que creo que es más práctico que una persona se enfoque en escribir código, desarrollar el producto y la otra persona se puede enfocar en hacer correcciones en tiempo real y fixear errores rápidamente.
