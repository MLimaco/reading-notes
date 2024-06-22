# Operadores y Bucles

En JavaScript se define como una expresión cualquier fragmento de código cuyo propósito sea dar un valor, un ejemplo simple de una expresión es la asignación de una variable. 

Existen diferentes tipos de expresiones: 

* Aritméticas: se tratan como número.
* Cadenas: se tratan como cadenas de caracteres (string)
* Lógicas: se evaluan como verdadero o falso
* Expresiones primarias: palabras clave y expresiones javascript
* Expresiones de lado izquierda: son el objetivo de una asignación

Los operadores son símbolos que permiten realizar operaciones matemáticas, comparativas y lógicas. Puede ser desde un simple = igual que, un && y, || o, += sumatoria con asignación, etc. 

Existen diferentes tipos de operadores según la tarea que desempeñan, aquí ingresaremos algunos que se usan con mayor frecuencia durante la etapa de aprendizaje básico:
* Operadores de asignación: son aquellos que asignan un valor a una variable o constante. Puede ir desde un simple igual que `=`, una operación de resta `-=` o un asignador lógico equivalente a "y" `&=` u "o" `|=`
* Operadores de comparación: son aquellos que comparan dos elementos y asigna un valor "verdadero" o "falso". Por ejemplo: 
```
let x = 1;
let y = 2;

1 == x // será "verdadero" siempre que efectivamente x y 1 sean iguales, caso contrario será falso

3 != x // será "verdadero" siemrpe que efectivamente 3 sea diferente a x

"3" !== x // será "verdadero" siempre que 3 sea diferente de x ya sea en valor o en tipo, el 3 del ejemplo es un string, no un int. 
```
* Operadores aritméticos: son aquellos que toman los elementos y devuelven como resultado un sólo valor numérico. Va desde los clásicos sumar, restar, dividir, multiplicar; hasta operadores más complejos como exponentes, operadores unarios, etc. 

Los bucles son soluciones rápidas a tareas que necesitan ejecutarse varias veces, se recomienda mucho que se asigne una condición para que el bucle se detenga ya que tener tareas corriendo ad infinitum es una mala praxis. 

# Resolución de las Preguntas

1. ¿Qué es una `expresión` en JavaScript?

Una expresión es un fragmento de código que tiene como propósito dar cualquier resultado o valor. Puede ser definir una variable, una operación matemática o incluso una concatenación de textos. 

2. ¿Por qué usaríamos un bucle en nuestro código?

Para realizar acciones repetidamente. Puede usarse por ejemplo para hacer calcular un factorial, que es un proceso repetido de multiplicaciones. 

3. ¿Cuándo deja de ejecutarse un bucle `for`?

Se deja de ejecutar cuando una condición específica se declara como "falsa". En la estructura de una expresion form, se marco en negrita la condicional que debe ser falsa para que se detenga el bucle.


`for``([expresiónInicial];` **`[expresiónCondicional]`**`;[expresiónDeActualización])`

4. ¿Cuántas veces se ejecutará un bucle `while`?

El bucle se ejecutará siempre que la condición sea verdadera. Por ejemplo para hacer un contador que vaya del 1 al 5, el while es la condición que debe validarse como verdadera para que se siga ejecutando el bucle, en ese caso debe ser menor o igual a 5. Si el valor de la variable llega a 6, ya no ejecuta el bucle.   

```
let i = 1; // donde inicia el contador

while (i <= 5) { // condicion a validar
    console.log(i); // ejecucion (muestra en la consola)
    i++; // incrementa de 1 en 1
}
```