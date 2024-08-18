# Lectura 5
## Medios en HTML

1. ¿Cuál es un caso práctico del atributo alt en una página web?

Para los usuarios que usan lectores de pantalla en caso de discapacidad visual, este atributo les permite tener una descripción de la imagen en cuestión siempre que se haya llenado. 

Del mismo modo también sirve cuando la imagen no se puede mostrar, ya sea porque se escribió mal el archivo, porque el formato no es aceptado por el navegador, o porque se rompió el enlace donde estaba alojada. 

2. ¿Cómo puedes mejorar la accesibilidad de las imágenes en un documento HTML?

Si se utiliza sólo los elementos title para describir una imagen y hay varias imágenes en el documento, para una persona con problemas de visión va a ser dificil identificar a que imagen corresponde cada titulo ya que los lectores de pantalla no proporcionan dicha información, por lo que es recomendable usar los elementos figure y figcaption, que permiten relacionar el titulo a la imagen correspondiente.

3. Da un ejemplo en el que el elemento figure sería útil en un documento HTML.

Basándome en la respuesta anterior, cuando hay multiples imágenes en una sola página. 

4. Describe la diferencia entre una imágen gif y una imágen svg, imagina que se lo estás explicando a una persona mayor de tu comunidad.

El formato gif es un formato que sirve para colocar animaciones simples, el formato SVG funciona para imágenes vectoriales, esto quiere decir imágenes que pueden agrandarse o reducirse sin perder la calidad de la misma, normalmente es usado para ilustraciones, elementos de interfaz, logos, iconos, diagramas. 

5. ¿Qué tipo de imagen usarías para mostrar una captura de pantalla en tu página web y por qué?

Utilizaría el formato webp, ya que es un formato que sirve para imagenes y tiene un buen nivel de compresión, es decir no pesa tanto y por lo tanto no realentiza el tiempo de carga de la web. 

## Aprende CSS

1. Describe la diferencia entre un color de primer plano y un color de fondo de un elemento HTML, imagina que estás hablando con una personas sin conocimientos técnicos

El color de fondo es como indica su nombre de fondo, esto quiere decir que si hay presente algún elemento con otro color, este se va a superponer. 

2. Tu amigo te pide que le des un retoque a su blog. ¿Cómo utilizarías color para darle carácter a su blog?

Definiría una paleta de colores, y asignaría un color principal para el fondo background-color; un color para las cajas de los elementos como menus, botones, cabecera, pie de página; y dos colores para los textos, uno que vaya con los colores de los elementos y otro para el cuerpo del blog. 

3. ¿Qué debes tener en cuenta al escoger tipos de letra para un documento HTML?

Creo que lo importante es definir fuentes que sean seguros para la web, por otro lado, sería recomendable elegir fuentes sans-serif que son de fácil lectura, las más agradable y segura para web es Helvética. 

4. ¿Cuál es la relación entre font-size, font-weight, y font-style con los elementos de texto en HTML?

Son las propiedades que definen como se va a presentar el texto en la web. El font size establece el tamaño del texto, el font-weight establece el grueso del peso y el font style sirve para activar el texto en cursivas.

5. Describe dos formas de añadir espaciado alrededor de los caracteres mostrados en un elemento h1.

Letter spacing y word spacing, la diferencia es que una controla el espacio entre letras y la otra entre palabras del texto. 