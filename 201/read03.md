# Lectura 3

## Aprende HTML

### Listas Ordenada y No ordenada

1. ¿Cuándo se puede utilizar una lista no ordenada en tu documento HTML?

La lista no ordenada se utiliza con el elemento ul. Se utiliza cuando se quiere enlistar items sin ninguna prioridad u orden en particular.

2. ¿Cómo cambias el estilo bullet de la lista de elementos no ordenados?

El estilo de bullet se cambia con la propiedad list-style-type: (aqui va circle, square, etc). Fuente: w3schools.com

3. ¿Cuándo debes usar una lista ordenada o lista no ordenada en tu documento HTML?

Citando el texto, cuando se cumplen los siguientes requisitos se debe usar una lista ordenada: cuando se quiere seguir pasos en un orden, indicaciones, items en orden creciente o decreciente.

4. Describe dos formas en las que puedes cambiar los números en los elementos de la lista proporcionados por una lista ordenada

Se puede cambiar los números en los elementos con los atributos start, que define un nuevo número en el que comenzará la lista en adelante, y el atributo reversed que asignará los números de mayor a menor.

## Aprende CSS

### The Box Model

1. Describe las propiedades de margin y padding en CSS como si fueran los personajes de una historia. ¿Cuál es su rol en la historia: “El Box Model”?

Si vemos el box model como una caja que vamos a enviar en Olva, el padding el relleno suave de la parte interna de la caja que se pone por si hay contenido frágil no se rompa. Mientras más relleno interno menos espacio para el contenido y viceversa. El margen se podría decir que es la envoltura externa de la caja. A diferencia de la interna no importa cuanto envuelvas la caja externamente, el tamaño de la caja original no varía, solo ocupa espacio de forma externa.

2. Enumera y describe las cuatro partes de un box del elementos HTML según el box model.

    1. Contenido `width` `height`: el espacio donde se muestra el contenido de la caja.
    2. Relleno `padding`: espacio en blanco interior que va alrededor del contenido.
    3. Borde `border`: como su nombre lo indica es el borde de la caja, delimita alto y ancho. Va sobre el relleno y antes del margen.
    4. Margen `margin`: recubrimiento externo de la caja.
Fuente: w3 school

## Aprende JS

### Arrays. Operadores y Expresiones. Condicionales. Bucles

1. ¿Qué tipos de datos puedes almacenar en un `Array`?

El array es una lista ordenada de variables, cada item enlistado ocupa un espacio empezando del 0 en adelante.

2. ¿El array `people` es un array de JavaScript válido? De ser así, ¿cómo puedo acceder a los valores almacenados? Y si no, ¿por qué?

```
const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
```

El array people es un array dentro de un array. Si se puede acceder a los elementos almacenados de dos formas:

   1. Llamando a todo el listado completo.

```
console.log(people[0]);
```

    2. Llamando a un elemento especifico dentro de uno de los listados.

```
console.log(people[0][3]);
```
Fuente: chatgpt

3. Enumera cinco opreadores abreviados de asignación en javascript y describe lo que hacen.

|nombre|operador|significado|descripción|
|--------|-----------|-----------|------------|
|adición|`x+=y`|`x=x+y`| suma el valor de y a la variable x|
|resta|`x-=y`|`x=x-y`| resta el valor de y a la variable x |
|multiplicación|`x*=y`|`x=x*y`| multiplica el valor de y con el de x|
|división|`x/=y`|`x=x/y`| divide el valor de x entre y|
|exponenciación|`x**=y`|`x=x**y`|eleva el valor de x a la potencia de y|

4. Lee el código a continuación, evalúa la última `expresión` y explica cuál sería el resultado y por qué.

```
 let a = 10;
 let b = 'dog';
 let c = false;

 // evalúa esto
 (a + c) + b;
```
Analizamos la primera parte, es una suma de un número con un booleano, por lo que el booleano se asume como 0
```
a+c = 10 + false
a+c = 10
```
En la segunda parte se concatena la respuesta de la pregunta anterior con el valor de c
```
(a+c)+b = (10)+dog
(a+c)+b = 10dog
```
Fuente: chatgpt

5. Describe un ejemplo cotidiano de por qué una declaración condicional se debería usar en un programa en JavaScript.

Una declaración condicional se puede utilizar en un videojuego para saludar al jugador al iniciar el mismo. Identificandolo si es un jugador nuevo o no en base a si tiene un archivo de guardado. 
```
"¡Bienvenido  " + (hasSaved ? "jugador nuevo!" : "de vuelta, jugador!");
```
6. Da un ejempo de por qué un `Bucle` es últil en JavaScript.

Para poder realizar operaciones sin la necesidad de escribir el código una y otra vez. Por ejemplo en el laboratorio 2, que se generó el bucle `for` en el ejercicio de la puntuación de las preguntas del juego del about me, para no tener que escribir la operación de suma o resta de puntaje varias veces, se refactorizó utilizando un bucle `for`
```
const cuestionario = [
    "¿Mi segundo nombre es Angel?",
    "¿Me gustan los libros más que los videojuegos?",
    "¿He invertido más de 1000 horas en World of Warcraft?",
    "¿Puedo pasar hasta 48 horas corridas jugando videojuegos?",
    "¿Me gusta jugar Fifa?",
];

const respuestas = [
    "Si",
    "No",
    "Si",
    "Si",
    "No",
];

let respuestasCorrectas = 0;
let respuestasIncorrectas = 0;

for (let i = 0; i < cuestionario.length; i++) {
    const comparacionRespuestas = prompt(cuestionario[i]);
    if (respuestas[i].toLowerCase() === comparacionRespuestas.toLowerCase()) {
        respuestasCorrectas++;
        alert("¡Respuesta Correcta! Parece que si me conoces 😉");
    } else {
        respuestasIncorrectas++;
        alert("¡Jaaa Jaaa Te Equivocaste!");
    }
}
```