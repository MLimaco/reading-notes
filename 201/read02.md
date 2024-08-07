# Lectura 2 Conceptos básicos de HTML, CSS y JS

## Introducción a HTML
1. ¿Por qué es importante utilizar elementos semánticos en nuestro HTML?

Porque otorga al contenido que contiene diferentes funciones según el elemento en el que están contenidos, que puede afectar desde el aspecto del mismo hasta su aplicación en los resultados de los diferentes motores de búsqueda. Los elementos semánticos bien utilizados ofrecen varias ventajas además de la estética de los mismos. 

2. ¿Cuántos niveles de encabezado existen en HTML?

Seis elementos de encabezados que van desde el h1 hasta el h6, siendo el h1 el principal y el resto subtítulos contenidos uno dentro de otro. 

3. ¿Cuáles son algunos de los usos para los elementos <sup> y <sub>?

Son el súper indice y sub indice respectivamente. 

4. Al utilizar el elemento <abbr>, ¿qué atributo se debe añadir para proporcionar una ampliación del término?

Sirven para proporcionar una explicación ampliada o extra de un elemento, normalmente abreviaciones o acrónimos. Va acompañada de un atributo title, y se muestra como un tooltip. 

## Aprende CSS
1. ¿De qué formas podemos añadir CSS a nuestro HTML?

De tres formas, hoja de estilo interna usando la etiqueta style en el head del document html; hoja de estilo externa usando un archivo css adjunto; finalmente inline, es decir como atributo dentro de cada elemento del documento HTML.

2. ¿Por qué deberíamos evitar utilizar estilos inline?

Por dos  razones: dificulta la lectura del código ya que se encuentra mezclada la estructura de la web con estilos y además entorpece el proceso de dar mantenimiento a la web. 

3. Revisa el código a continuación y responde a las siguientes preguntas:
```
   h2 {
     color: black;
     padding: 5px;
   }
```
4. ¿Qué representa el selector?

Es un elemento del documento html al que se le aplicará un estilo. Cada regla de CSS se asigna a un selector o grupo de selectores.  En el código en particular el selector representa el primer subtítulo (h2).

5. ¿Qué componentes son declaraciones CSS?

El selector (h2), las propiedades a alterar (color y padding) y los valores que se asignan a cada propiedad (black, 5px). 

6. ¿Qué componentes se consideran propiedades?

Son valores asociados a las características de estilo que podemos identificar como color, altura, color de fondo, etc. En el caso específico del código: el color y el padding. 

## Aprende JS
### Fundamentos de JavaScript
1. ¿Qué tipo de dato es una secuencia de texto entre comillas simples?

Es un tipo de dato string.

2. Enumera 4 tipos de operadores en JavaScript.

Sumar/concatenar, resta/multiplicacion/división, negación, igualdad. 

3. Describe un problema práctico que puedes resolver con una función.

Basándonos en el ejercicio del curso anterior, para poder mostrar respuestas válidas en base a preguntas. De modo que si a alguien le pregunto su edad sólo se acepte respuestas numéricas y no respuestas vacías o con letras o caracteres especiales.

### Tomando decisiones en tu código — condicionales.

1. Si una declaración if comprueba un __ y si resulta ___, entonces el código se ejecutará.

2. ¿Cuál es el uso del else if?

Sirve para especificar una nueva condición si la condición original es falsa (fuente W3 Schools).

3. Enumera 3 tipos de operadores de comparación.

Igual `===`, no igual o diferente `!==`, mayor y menor que `<` `>`, mayor e igual y menor e igual `<=` `>=`. 

4. ¿Cuál es la diferencia entre los operadores lógicos && y ||?

El operador `&&` significa `y` y se utiliza cuando se quiere evaluar dos o más condiciones en una misma función y que ambas se deban cumplir. El caso de `||` significa `o` y se utiliza cuando se quiere evaluar dos o más condiciones en la misma función y que cumpla cualquiera de ellas. 