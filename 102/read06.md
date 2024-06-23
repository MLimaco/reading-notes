# Páginas web dinámicas con JavaScript

Javascript o JS es un lenguaje de programación diferente a Java, que se le conoce como lenguaje "ligero", esto quiere decir que el código de javascript se ejecuta sólo cuando se necesita, permitiendo correr diferentes programas de manera más eficiente y rápida.

Javascript corre en la gran mayoría de navegadores ya que se suele incluir alguno que otro código javascript en la página HTML para ejecutar alguna función en particular, a esto normalmente se le conoce como ejecución del lado de cliente. Pero, también es capaz de correr en otros programas como node.js, io.js, etc; estos programas, mediante javascript, permiten ejecutar acciones del lado del servidor como por ejemplo conectar una web a una base de datos.

Cuando trabajamos con HTML se puede ingresar el código javascript directamente en el archivo HTML o se puede también trabajar por separado en una hoja aparte con la terminación .js y agregarla al archivo HTML mediante la etiqueta <script>.

```
<body>
<script src= "app.js"></script>
</body>
```

Se debe considerar que existen diversas formas de que el javascript pueda mostrar "texto" para que el usuario pueda leer, las mas simples son:

* `alert` muestra un modal en el navegador con el texto indicado.

* `document.write` cambia o muestra texto directamente en el navegador, sin necesidad de pop ups.

* `console.log` muestra texto en la consola, esto quiere decir que no es visible a simple vista para el usuario pero puede acceder a el accediendo a la consola, que es donde normalmente se muestran errores y alertas.

* `confirm` muestra un modal con el texto indicado y los botones ok/cancel.

* `prompt` de manera similar al confirm muestra un modal en el navegador con el texto indicado, los botones ok/cancel y ademas un espacio para que el usuario pueda llenar.

Cuando uno habla de JavaScript comúnmente podría estarse refiriendo a 3 diferentes ejecuciones:

1. El propio lenguaje de programación, que es capaz de correr en servidores y navegadores.
2. El DOM API, se refiere al conjunto de códigos javascript que permiten interactuan con el DOM (o estructura) de una web.
3. El server API, o el sistema de intercambio de datos entre el servidor y los dispositivos o clientes. Normalmente ejecutados a través de node.js con javascript.

# Resolución de las Preguntas

1. ¿Qué son las variables en JavaScript?

Una variable es como una caja con un "nombre" al que se le puede asignar un valor. Este valor se asigna mediante declaraciones y normalmente se le pone un "nombre" para más adelante poder referirte o "llamar" a esa variable.
En el siguiente ejemplo, en lugar de escribir `2+2+2+2` y `3*3*3` es más fácil definir esos ejercicios matemáticos como 2 variables y luego sumarlos.

```
// Variables
let x = (2 + 2 + 2 + 2); // x es igual a 2+2+2+2
let y = (3 * 3 * 3); // y es igual a 3*3*3

// Mandar el resultado a la consola
console.log(X + Y); // mostrará en la consola: X + Y = 35
```

2. ¿Qué significa “declarar” una variable?

Una declaración es una instrucción, "declarar una variable" es la instrucción de asignarle un nombre a un valor y "guardarlo" para poder usarlo luego, ya sea para una operación matemática (como en el ejemplo anterior) o para luego "mostrarlo" de forma más sencilla. Por ejemplo.

```
// Variables
let saludo = "Bienvenido a este ejemplo"; // cada que llame a la variable bienvenido el valor será el texto "Bienvenido a este ejemplo"

// Mandar el resultado a la consola
console.log(saludo); // mostrará "Bienvenido a este ejemplo" en la consola
```

3. ¿Qué es un operador de “asignación” y qué hace?

Los operadores de asignación son operadores que asignan un valor a una variable. Ya usamos el más básico, =, muchas veces — simplemente asigna a la variable de la izquierda, el valor de la derecha:
Un operador de asignación se utiliza para dar un valor a una variable. Este valor dependerá del operador que se utilice. La gran mayoría de veces se utiliza el `=` para declarar variables. Significa que el valor a la derecha del `=` está asignado a la variable a su izquierda. Pero esto puede hacerse más complejo, se puede sumar, restar, multiplicar y otro sin fin de operaciones.
Estos operadores se pueden  usar para por ejemplo correr contadores de tiempo en una página, o ejecutar una barra de progreso en un aplicativo web que se actualice gradualmente con el tiempo.

4. ¿Cómo se llama la información recibida del usuario?

Se les llama "inputs" y se puede hacer mediante algunas funciones como `prompt` o `confirm`, que permiten al usuario proporcionar "información" a través de una web, por ejemplo.
