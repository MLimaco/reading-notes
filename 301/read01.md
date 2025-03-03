# React - Pasar funciones como props

Pasar funciones como props en React permite que un componente hijo ejecute una lógica definida en su componente padre, manteniendo un flujo de datos unidireccional y modular.

## ¿Por qué usarlo?

Facilita la comunicación entre componentes sin necesidad de estados globales. Los componentes hijos pueden activar eventos en el padre sin conocer su implementación, mejorando la reutilización del código.

## Conceptos clave

Comunicación de datos vs. comunicación de eventos: Mientras las props de datos solo transmiten información, las funciones permiten al hijo afectar el estado del padre.

Responsabilidad y flujo de control: Aunque el hijo ejecuta la función, el control sigue en el padre, asegurando coherencia en la lógica.

Estado centralizado vs. local: Si varios componentes dependen del estado, se centraliza en el padre; si solo afecta al hijo, se maneja localmente.

Funciones anónimas y de flecha: Usarlas directamente en `onClick` puede causar re-renderizados innecesarios; es preferible definirlas fuera del JSX.

Delegación de responsabilidades: La validación de datos debe hacerse en el hijo si es específica de su función, o en el padre si impacta la lógica global.

Escalabilidad y legibilidad: Pasar muchas funciones como props puede afectar la claridad del código; en aplicaciones complejas, patrones como `Context API` pueden ser útiles.

Pasar funciones como props es una técnica esencial en React para mantener un código modular, reutilizable y fácil de mantener.