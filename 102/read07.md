# Programación con JavaScript

Al momento de programar con JavaScript hay que considerar el "control flow" o control de flujo, es decir, el orden en el que el código se va a ejecutar. Esto quiere decir que todo el código se va a ejecutar de arriba para abajo a menos que existan excepciones. 

Estas excepciones son las estructuras de control, código que tiene el poder de alterar el control de flujo. Estas pueden ser: 

1. Sentencia de bloque: Agrupa varias declaraciones para que se ejecuten al mismo tiempo.
2. Sentencia condicional: Sólo se ejecutan si se cumple la condición indicada (if/else).
3. Sentencias de iteración: Siempre que la condición se cumpla se mantienen constantemente en ejecución.
4. Sentencia switch: Similar a las condicionales, sólo se ejecuta si se cumple con los casos indicados. 
5. Sentencia break: Interrumpe una sentencia de iteración o switch.
6. Sentencia continue: Interrumpe la sentencia de iteración actual y hace que se continúe con la siguiente. 

Todos los bloques de código que realizan tareas específicas en JavaScript se llaman "funciones". Y estas se ejecutan al ser "llamadas" mediante un evento, código o al configurar el llamado automático cuando creas la función. 

La estructura de una función es la siguiente: 
1. Definición: se suele aperturar con la palabra clave function.
2. Nombre de la función: para facilitar el llamado, las funciones deben estar nombradas usando letras, dígitos, etc. Es recomendable utilizar la convención camelCase. 
3. Parámetro o parámetros: Los parámetros son valores que serán reemplazados al ejecutar la función y están nombrados. Puede ser un sólo valor, o múltiples valores separados por comas. 
4. Argumentos: Son los valores reales que se pasan a la función cuando esta es invocada.
5. Cuerpo o fórmula: Lo que va a suceder cuando se llame a la función. Va entre corchetes {}. 

# Resolución de las Preguntas

1. ¿Qué es “Control Flow” (Control de Flujo)?

Es el orden en el que es ejecutado el código. En el caso de JavaScript se ejecuta de arriba para abajo excepto cuando existen condicionales, loops, funciones y eventos específicos. 

2. ¿Qué es una “function” (Función) de JavaScript?

Una función es código que ejecuta una tarea en particular en reacción a un "llamado" que puede ser por un evento, por código o autoinvocada. 

3. ¿Qué significa “invoke” o “call” en una función?

Es cuando se llama a la función para que se ejecute:

    1. Evento: cuando la función sucede en reacción a una acción en el navegador como por ejemplo un clic en algún elemento particular, o una carga de página. 
    2. Código JavaScript: cuando usas un script para ejecutar la función definida anteriormente. 
    3. Auto-invocada: cuando la función no necesita ningún script adicional para ejecutarse. 

4. ¿Para qué sirven los paréntesis () cuando defines una función?

Los paréntesis sirven para cuando definas una función coloques los parámetros dentro. Ejemplo: 

```
// definición de la función
function saludar(nombre) {
  return "Hola, " + nombre + "!";
}
// llamada de la función
let mensaje = saludar("Ana");
console.log(mensaje);  // Imprime "Hola, Ana!"
```