# CSS
Las hojas de estilo en cascada (Cascading Style Sheets) son la razón por las que tenemos páginas web visualmente agradables.Este fue desarrollado por el grupo del W3C llamado CSS Working Group. CSS es un lenguaje que altera como se presenta el contenido (documentos) en los navegadores web. 

Cuando hablamos de documentos hablamos de archivos de texto estructurado, en su mayoría HTML, pero podría también ser de otos formatos como SVG o XML. 

El CSS está compuesto por reglas que a su vez están compuestas por los siguientes elementos. 
1. Selector: es el elemento html que se verá afectado por la regla. 
2. Llaves de apertura y cierre: Especifica que todo lo que contenga afectará al selector al que pertenecen. 
3. Declaraciones: Esta compuesta por 2 sub elementos:
    1. Propiedad: Es una característica que se va a asociar al valor de la regla. Por ejemplo color, tamaño de letra, fuente, etc. 
    2. Valor: Es la definición específica de la propiedad a la que hace referencia. Por ejemplo: si la propiedad es color, el valor puede especificar que sea rojo. Si la propiedad refiere al tamaño de fuente, el valor podría ser un número, posiblemente 12. 

Hay que tener en consideración que el lenguaje se divide en módulos (MDN), y cada modulo abarca propiedades en especifico. Esto facilita la búsqueda de información. 

# Resolución de Preguntas
1. ¿Cuál es el propósito de CSS?
El CSS, u hoja de estilo en cascada, permiten controlar con precisión como se ven los elementos html en los navegadores. Con esto nos referimos a fuentes, tamaños, colores, etc. 
2. ¿Cuáles son las tres formas de insertar CSS en tu proyecto?
    1. Inline: aplicando css a cada uno de los elementos html de la web utilizando la regla `style`. Los cambios se aplican elemento por elemento. 
    2. Interna: aplicando css usando la regla style en el `<head></head>`. Sirve para aplicar estilos a una sóla página web, no aplica estilos a todas las páginas. Para ello habría que aplicar el style página por página. 
    3. Externa: a través de una hoja de estilos externa, esta se puede aplicar a multiples páginas. Es el método más usado para aplicar CSS. 
3. Escribe un ejemplo de una regla CSS que daría texto rojo a todos los elementos `<p>`.
```
<style>
        p {
            color: red; 
        }
</style>
```