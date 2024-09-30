# Lectura 06

## Conceptos básicos de los objetos JavaScript

1. Cómo le describirías un objeto a un amigo sin conocimiento técnico con el que creciste?
    Un objeto es un conjunto de datos agrupados. Por ejemplo si yo fuera un objeto seria:

    Objeto Michael: edad, educacion, trabajo, direccion, etc.
2. ¿Cuáles son algunas de las ventajas de crear objetos literales?

    Simplicidad: a diferencia de los objetos creados via funciones son mas faciles de crear, identificar y ejecutar. Tambien son mas faciles de modificar. 

3. ¿En qué se diferencian los objetos de los arrays?

    Un objeto esta ordenado por llave y contenido, mientras los arrays son una lista de valores, por la misma razon cuando quieres acceder al contenido de un objeto debes llamarlo por la llave, mientras los items dentro del array son llamados por la posicion que ocupan en la lista.

4. Da un ejemplo acerca de los momentos en los que necesitarías utilizar bracket notation para acceder a la propiedad de un objeto en vez de dot notation.

    Cuando intentas acceder a una clave que es un numero y no un string.

    ```
    const inventario = {
    1001: "manzanas",
    1002: "naranjas"
    };
    console.log(inventario[1001]); // "manzanas"
    ```

    Fuente: chatgpt.

5. Evalúa el siguiente código. ¿A qué se refiere el término this y cuál es la ventaja de utilizarlo?
```
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```

En el codigo `this` refiere al objeto `dog`.

## Introducción al DOM

6. ¿Qué es el DOM?

    Siglas de Document Object Model. Es una representacion del documento de forma ordenada a traves de nodos.

7. Describe brevemente la relación entre el DOM y JavaScript.

    Javascript utiliza el DOM para acceder al documento y sus elementos para alterarlo. El contenido de la página es almacenado en DOM y el acceso y la manipulación se hace vía JavaScript