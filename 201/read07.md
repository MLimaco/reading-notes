# Programación orientada a objetos, Tablas en HTML

## Domain Modeling

1. Explica por qué necesitamos los modelos de dominio.

    Para poder verificar y validar el entendimiento del problema. Por otro lado, permite definir el vocabulario que se va a utilizar entre el equipo técnico y el equipo de negocio. 

## Conceptos básicos de las tablas HTML

2. ¿Por qué no se debe utilizar tablas para los layout de página?

    1.	Reducen la accesibilidad visual a los usuarios que tienen discapacidades, ya que los software de lectura de pantalla leen etiquetas html, por lo que en una tabla seria dificultoso que el software funcione correctamente.
    2.	Entorpece el proceso de mantenimiento y limpieza del código, además de la depuración del mismo. 
    3.	No son adaptativos. Su ancho es dependiente de aquello que contienen, por lo que adaptarlo a todas las pantallas requeriría mucho esfuerzo.

3. Enumera y describe 3 diferentes elementos semánticos HTML utilizados en un <table>.

    1.	TR, table row, define el inicio y fin de una fila de la tabla. Para abrir filas nuevas se debe volver a usar el elemento.
    2.	TD, table data, es la celda, el elemento mas pequeño de la tabla, contiene información. 
    3.	TH, table header, es la cabecera de la columna, se usa para definir la información que va a contener la columna o fila en cuestión. 


## Introducción a los Constructores

4. ¿Qué es un constructor y cuáles son las ventajas de utilizarlo?

    Son funciones para definir objetos y sus correspondientes características. Se utiliza bastante en prototipos o cuando no hay claridad de cuantos objetos hay que crear.a

5. ¿Cómo es que el término this se diferencia cuando se utiliza en un objeto literal y cuando se utiliza en un constructor? Herencia prototípica Prototipos nativos.

    Cuando se usa en un objeto literal, hace referencia al objeto en el que se está definiendo. Cuando se usa en un objeto constructor hace referencia al resultado, es decir el nuevo objeto que se va a crear.

6. Explica los prototipos y las herencias por medio de una analogía sobre tu experiencia laboral previa.

Para poder enviar materiales a diseñar para mis anuncios tengo templates o plantillas, los prototipos son como esas plantillas. Simplemente hay que cambiar texto e imagen de fondo y la plantilla se encarga de colocar bordes, estilog gráfico, fuentes, logo de marca, etc. 

En el caso de las herencias es como hacer duplicados de campañas, al crear el duplicado la nueva campaña puede "heredar" configuraciones de la original, haciendome el trabajo mucho más fácil. 

## Cosas de las que quiero saber más

Creo que no he entendido bien el tema de objetos constructores y heredados, sobre el resto lo entiendo. Entiendo la importancia de aclarar porqué no se debe construir en tablas, ya que antes era bastante común y la verdad que es un método poco amigable y complejo. 

Por otro lado, el tema de domain modeling lo comprendo, tengo que entenderlo, pero me sigue pareciendo complejo de ejecutar. 
