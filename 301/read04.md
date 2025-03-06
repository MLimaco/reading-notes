#Formularios Controlados en React
En React, los formularios controlados permiten gestionar los datos ingresados por el usuario mediante el estado del componente. A diferencia de los formularios tradicionales en HTML, donde los valores se almacenan directamente en el DOM, en React cada campo de entrada está vinculado a una variable de estado, asegurando sincronización y control total sobre los datos.

## ¿Por qué usar formularios controlados?
- Mayor control: Permiten manejar y validar los datos fácilmente.
- Sincronización en tiempo real: La interfaz siempre refleja los valores actuales.
- Validaciones dinámicas: Se pueden verificar los datos antes de enviarlos.

## Manejo de Eventos en Formularios
React usa eventos como `onChange` y `onSubmit` para interactuar con los datos:

`onChange` actualiza el estado cuando el usuario escribe en un campo.
`onSubmit` se ejecuta al enviar el formulario, permitiendo validar los datos antes de procesarlos.
Validación y Manejo de Errores
Es importante validar los datos antes de enviarlos. Se pueden hacer validaciones:

En tiempo real (`onChange`) para retroalimentación inmediata.
Al enviar (`onSubmit`) para revisar todos los campos a la vez.

## Uso del Spread Operator (`...`)

Para actualizar el estado sin modificar el original, se usa el spread operator:

```
setFormulario({ ...formulario, nombre: event.target.value });
```

Esto mantiene el código limpio y seguro.

Los formularios controlados hacen que las aplicaciones sean más predecibles y fáciles de mantener, mejorando la experiencia del usuario.