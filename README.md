![Inputs en HTML](https://raw.githubusercontent.com/sergiecode/tipo-de-inputs-html/master/tipo-de-inputs.jpg)

#   Tutorial de Tipos de Inputs en HTML

Este repositorio contiene un tutorial sobre los diferentes tipos de elementos de entrada (inputs) en HTML, junto con ejemplos de código para cada uno. Los elementos de entrada son una parte esencial de la construcción de formularios y la interacción con los usuarios en páginas web. En este tutorial, exploraremos varios tipos de inputs y cómo se pueden utilizar en tu código HTML.

## Contenido

En este tutorial, encontrarás ejemplos de código para los siguientes tipos de inputs:

1.  **Text Input**: Un campo de entrada de texto básico que permite a los usuarios escribir texto.
2.  **Password Input**: Un campo similar al de texto, pero oculta los caracteres ingresados, útil para contraseñas.
3.  **Number Input**: Un campo de entrada numérico que permite a los usuarios ingresar números.
4.  **Image Input**: Un campo que permite a los usuarios seleccionar una imagen de su dispositivo.
5.  **Range Input**: Un control deslizante que permite a los usuarios seleccionar un valor dentro de un rango.
6.  **Date Input**: Un campo que muestra un calendario para seleccionar una fecha.
7.  **Button Input**: Un botón interactivo que los usuarios pueden hacer clic.
8.  **Checkbox Input**: Una casilla que permite a los usuarios seleccionar una o varias opciones.
9.  **Radio Input**: Botones de selección exclusiva que permiten a los usuarios elegir una opción de un conjunto.
10.  **File Input**: Un campo que permite a los usuarios cargar archivos desde su dispositivo.
11.  **Color Input**: Un campo que muestra un selector de color para elegir colores.

## Ejemplo de Código

```
<body>
    <div style="background-color: black; color: #3b83bd;padding: 100px; width: 250px; accent-color: #3b83bd;">
        <input type="text"> <br>
        <input type="password"> <br>
        <input type="number"> <br>
        <input type="image"> <br>
        <input type="range"> <br>
        <input type="date"> <br>
        <input type="button" value="Click me"> <br>
        <label><input type="checkbox" id="cbox1" value="first_checkbox">Subir Imagen</label><br> <br>
        <input type="radio" id="huey" name="drone" value="huey" checked><label for="huey">Frontend</label> <br>
        <input type="file"> <br>
        <input type="color"> <br>
    </div>
</body>
```
