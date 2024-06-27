# Creación de Animaciones con Transition, Keyframes y Transform

## Descripción

Este proyecto demuestra cómo utilizar las propiedades `transition` en CSS para crear animaciones y transiciones dinámicas en elementos HTML. A través de varios ejemplos prácticos, se muestran diferentes formas de animar elementos sin la necesidad de utilizar JavaScript.

## Estructura del Proyecto

- **index.html**: El archivo HTML principal que contiene la estructura básica de la página.
- **style.css**: El archivo CSS que contiene las definiciones de estilo y las animaciones.

## Contenido

### 1. Transition

La propiedad `transition` permite definir cambios suaves entre los estados de las propiedades CSS. En este proyecto se demuestra cómo utilizar `transition` para animar propiedades como el color de fondo, el ancho, y otros.

Ejemplo:
```css
.elemento {
    background-color: #4CAF50;
    transition: background-color 0.5s ease;
}

.elemento:hover {
    background-color: #45a049;
}
