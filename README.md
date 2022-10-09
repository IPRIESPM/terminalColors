# Terminal Colors

Una pequeña guia para usar colores en la terminal de bash

## Uso de secuencia de escape

En este apartado hablare de las variables de color, en las cuales he guardado unas secuencias de escape para modificar, el color de la fuente que muestra la terminal.
Una secuencia de escape, es un conjunto de caracteres que se interpreta de manera diferente a los caracteres literales, en nuestro caso \033 se interpreta como modificador de la fuente de la consola.

## Estructura secuencia de escape de color

Cada opción se separa con ; y para determinar el límite de la modificación se utiliza l

|Inicio del estilo|\033[|
|------------------|-----|
|Opción 1|Color de fondo|
|Opción 2|Color de fuente|
|Opción 3|Decoraciones|
|Final m|

## Tabla de Colores

|-|Color Fuente|Color Fondo|
|---------|-----------|---------|
|Negro|30|40|
|Rojo|31|41|
|Verde|32|42|
|Amarillo|33|43|
|Azul|34|44|
|Magenta|35|45|
|Cyan|36|46|
|Blanco|37|47|

## Tabla de efectos

|Código|Efecto|
|-----|------|
|1|**Negrita**|
|4|<ins>Subrayado</ins>|
|5|Parpadeo|
|7|Inverso|

|Ejemplo|Resultado|
|----|----|
|\033[42;31;1m Algún tipo de texto \033[0m|Algún tipo de texto|
