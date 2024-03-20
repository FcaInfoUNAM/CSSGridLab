[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/isN1HfpU)
# CSS básico

Este repositorio tiene como objetivo reflexionar, repasar y comprender el uso de CSS en archivos CSS

Escribe en un archivo de texto llamado entregable.txt las respuestas a las preguntas del laboratrorio

## Paso1

Clona el repositorio en tu local

1. Visualiza el navbar en el navegador
2. Analiza el archivo custom css y explica en entregable.txt qué elementos serían afectados en los siguientes casos:

    ```css 
    nav a {...} 
    ```
    ```css
    nav , a {...}
    ```
    ```css
    .l, .o, .v, .e, .r {...}   
    ```
3. Comenta las líneas
```css
nav a img{
    filter: brightness(0) invert(1);
}
```
4. Explica en entregable.txt qué es lo que hace la propiedad filter y cómenta si hay algunas propiedades que usarías en tus fotos
5. Descomenta lo previamente comentado

## Paso2

1. Cambia los colores del nav con la paleta de colores proporcionada en root, utiliza amarillo y naranja
```css
nav {
    ...
    background-image:...;
    ...
}
```
2. Ahora que sabes definir colores en valores mediante root genera tu paleta de colores con el siguiente prefijo: --tuNombre por ejemplo:
```css
:root{
    --pedroNoe-azul:...;
    --pedroNoe-amarillo:...;
    --pedroNoe-rojo:...;
    --pedroNoe-morado:...;
    --pedroNoe-naranja:...;
    --pedroNoe-verde:...;
}
```
Puedes utilizar generadores de paletas de color en línea.

## Paso3

1. Revisa las líneas de la clase .grid y checa la [documentación de mozilla](https://developer.mozilla.org/es/docs/Web/CSS/CSS_grid_layout)
2. Modifica el CSS de las clases .l .o .v .e .r para que esten alineadas en una sola columna y ordenadas para que digan LOVER
3. Modifica el CSS de las clases .l .o .v .e .r para que esten alineadas en una sola columna y ordenadas para que digan REVOL
4. Realiza un commit con el comentario "REVOL"
```cmd
git add ./css/custom.css
git commit -m "REVOL"
```
## Paso4

1. Modifica el CSS de las clases .l .o .v .e .r para que esten alineadas en una sola fila (de arriba a abajo) y ordenadas para que digan REVOL
2. Modifica el CSS de las clases .l .o .v .e .r para que esten alineadas en una sola fila y ordenadas para que digan LOVER
3. Realiza un commit con el comentario "LOVER"
```cmd
git add ./css/custom.css
git commit -m "LOVER"
```
## Paso5
2. Modifica el CSS de las clases .l .o .v .e .r para que esten alineadas en diagonal y ordenadas para que digan REVOL
3. Realiza un commit con el comentario "Diagonal"
4. Cambia los colores a la paleta de colores que creaste
```cmd
git add ./css/custom.css
git commit -m "Diagonal"
```
## Paso6
1. Guarda los cambios
2. Agrega los cambios a tu repositorio junto al archivo entregable.txt
``` cmd
git add entreganle.txt
git add inbdex.html 
```
3. Haz una rama llamada entregable
```cmd 
git branch entregable 
```
4. Cambiate a la rama recién creada
``` 
git checkout entregable 
```
5. Realza un push sobre la rama nueva
```cmd 
git commit -m "entregable"
git push origin entregable 
```
6. solicita un pullrequest en github