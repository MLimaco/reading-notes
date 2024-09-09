# Lecturas
## Contenido de audio y video

1. Explica cómo la capacidad de utilizar video y audio en la web ha ido evolucionando desde el comienzo de los 2000.

En un primer comienzo era muy difícil por la capacidad del ancho de banda, luego se empezó a trabajar con la ayuda de plugins como FLASH, pero era muy inseguro y poco compatible con HTML y CSS, además de tener problemas de accesibilidad. 

Hoy en día, gracias a HTML5, se trabaja con soluciones nativas con los elementos video y audio que se controlan mediante javascript APIs.

2. Describe el uso de los atributos src y controls en el elemento `<video>`.

El src, maneja la ruta al video que se desea incrustar. El elemento controls permite implementar la interfaz  de control en el browser.

3. ¿Por qué es importante tener contenido de respaldo en el elemento `<video>`?

Porque puede haber casos de personas con browsers antiguos que no tengan soporte html5, que necesiten ver el video. Con el fallback content, al menos pueden ver un enlace donde ver el video en otra web, o un texto descriptivo. 

4. Escribe una historia corta en donde `<audio>` y `<video>` son personajes. 

Erase una vez los amigos audio y video que se sentían muy excluidos del mundo online por ser muy grandes para las fiestas web. Hasta que un día con ayuda de flash, pudieron ver las fiestas por videollamada usando un anticuado y poco seguro artefacto, no era la mejor solución, pero era un primer comienzo.

Hasta que un día les llegó una invitación para las fiestas web, habían sido invitadas y tenían su propia puerta de entrada, los elementos audio y video, para ellas solas. Y encima les dijeron que los días que no pudieran entrar a la fiesta podían dejar instrucciones para que igual las puedan ver llamadas fallback content.

Y así vivieron felices para siempre. 

5. ¿En qué se diferencia el layout Grid del Flex?

El layout flex funcionan en una dirección, ya sea una fila o una columna. Mientras tanto el layour grid funciona en ambas direcciones, lo que implica un diseño bidimensional, permitiendo trabajar varias filas y columnas al mismo tiempo (MDN Web Docs).

6. Grid container, grid item, y grid line son algunos de los términos importantes que se deben entender al utilizar Grid. Por favor describe estos términos en unas pocas frases.

- Grid Container. Es el elemento en el que se aplicará el grid y el “padre” de los ítems del grid.
- Grid Item. Son los hijos del grid container. 
- Grid Line. Son las líneas dividorias que conforman la estructura del grid. Pueden ser verticales, horizontales, en fila o columna.
- Grid Cell. Es la unidad del grid. 
- Grid Track. Es el espacio entre dos grid lines adyacentes. Se pueden pensar en ellos “como filas o columnas”. 
Imágenes Responsivas

7. Además de hacer que un sitio se vea atractivo visualmente en diferentes tamaños de pantalla, ¿por qué los desarrolladores deberían hacer imágenes responsivas?

Para evitar dificultades al usuario al momento de navegar por la web en dispositivos de pantallas muy pequeñas, además de temas como: resolución adecuada para cada pantalla, ahorro de ancho de banda en caso de pantallas pequeñas, efectos negativos de la rasterización de imágenes en caso se quiera mostrar imágenes en pantallas de alta resolución, etc. 

8. Define los siguientes atributos de <img>: srcset y sizes. Escribe un ejemplo de cómo se usan.

- Srcset, permite seleccionar diferentes fuentes para diferentes pantallas, y modificar el tamaño que ocupan las mismas en relación al ancho. 
- Sizes, se utiliza en conjunto con el srcset para definir el ancho de las imágenes. 

9. ¿Cómo es que srcset es más útil para las imágenes responsivas que CSS o JavaScript?

Porque para que funcionen correctamente primero habría que cargar la imagen original, luego la responsiva y sería un proceso fastidioso para el usuario. 

## Cosas en las que me gustaría profundizar

Creo que en el tema de imágenes responsivas, incluso más que el audio o video ya que son cosas que no veo mucho en la práctica, y cuando se trabajan se hace como incrustados, sin embargo el tema de imágenes responsivas si es algo que creo que puede ser fundamental. 