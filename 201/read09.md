# Formularios y Events en JS

Creo que el tema es personalmente relevante para mi por las aplicaciones inmediatas que tiene en mi trabajo, ya que mi posición es híbrida y tiene bastante de UX y de analista de datos, el conocer como funcionan los formularios y cómo funcionan los eventos al detalle es importante para mi día a día. 

## Formularios en HTML

1. ¿Por qué los formularios son tan importantes en el desarrollo web?

    Porque es uno de los principales puntos de interacción del usuario con la web, particularmente es una de las principales formas en las que el usuario puede dejar información, que dependiendo del caso se envían a un servidor para ser analizados y almacenados.
2. Al diseñar un formulario, ¿cuáles son algunas de las cosas más 
importantes a tener en cuenta sobre la experiencia de usuario?

    La más importante es hacer el formulario corto, porque mientras más largo, la tasa de abandono del mismo será más alta, por lo que se recomienda sólo solicitar los datos que se necesitan. Por otro lado, debe tener una buena estructura de la información que se solicita, agrupar las preguntas por tema es mejor que colocar miles de preguntas de diferentes temas una tras otra. Es recomendable que el tamaño del input sea lo más cercano posible a la información esperada. 
3. Enumera 5 elementos de los formularios y explica su importancia.

    1. `Form` es el contenedor de formulario. 
    2. `Label` es el contenedor de la etiqueta del campo que se solicita llenar al usuario.
    3. `Input` sirve para crear controles para los formularios con el fin de recibir información de los usuarios.
    4. `Button` sirve para poder habilitar el enviado de datos, siempre que se use el atributo submit. 
    5. `Fieldset` sirve para agrupar elementos de un form que tengan correlación. 


## Aprende JS

1. ¿Cómo describirías los event a un amigo sin conocimiento técnico?
    
    Un evento es cualquier cosa que sucede en el sistema y que sea capaz de proporcionar un método de reacción a la misma cuando suceda. Suceden dentro del navegador y normalmente están asociados a un elemento en particular. 
    
    Para poder reaccionar, hay que implementar un detector de eventos y un manejador de eventos, que son código, que se ejecuta cuando el evento suceda, el primero para identificar el evento y el segundo para que suceda la respuesta al evento.
2. Al utilizar el método addEventListener(), ¿cuáles son los 2 arguments que debes proporcionar?

    El tipo de evento, si es click, mouseover, keydown, etc). La función de callback, que se deberá ejecutar cuando suceda el evento especificado. 
3. Describe el objeto event. ¿Por qué el target dentro del objeto event es útil?

    Un objeto evento sirve para pasar información y características a los manejadores de eventos. 
4. ¿Cuál es la diferencia entre event bubbling y event capturing?

    Son métodos para capturar eventos en elementos que se encuentran anidados. Por ejemplo:
    ```
    <section>
    <div>
    <button> Botón </button>
    </div>
    </section>
    ```
    El primer caso es el manejo mediante bubbling, que va del elemento menos anidado al más anidado, por lo que gatillaría primero el evento del botón, luego del div, finalmente del section. Esto en algunos casos puede dar errores al ejecutar lo que sea que contenga el botón. Por lo que en esos casos se usa el evento capturing, que es el proceso inverso, va del más anidado al menos anidado. Así que primero gatillaria el section, luego el div, finalmente el botón. 

## Cosas en las que quiero profundizar

Quisiera profundizar en el conocimiento de javascript aplicado a medición y eventos. ¿Cómo se redacta?¿Qué casuísticas hay?¿Qué otras aplicaciones tiene?