# CSS
Las hojas de estilo en cascada (Cascading Style Sheets) son la razón por las que tenemos páginas web visualmente agradables. CSS es un lenguaje que altera como se presenta el contenido (documentos) en los navegadores web. 

Cuando hablamos de documentos hablamos de archivos de texto estructurado, en su mayoría HTML, pero podría también ser de otos formatos como SVG o XML. 

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
        p{
            color: rgba(255, 0, 0, 1.0); 
        }
</style>
```