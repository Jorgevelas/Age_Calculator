# Age_generator

Este proyecto consiste en un calculador de edad que permite mostrar la edad exacta de una persona apartir de una fecha establcida por el usuario la aplicacion le permite ver cuantos años,meses y dias tiene actualmente construida utilizando HTML, CSS y JavaScript.y utilizando de ejemplo el video de greatstack A continuación, se detallan los componentes principales del código y su funcionalidad.

[![imagen-2024-08-29-114203848.png](https://i.postimg.cc/mZyxmwQg/imagen-2024-08-29-114203848.png)](https://postimg.cc/kDGh4W10)


Estructura del Proyecto
Archivos Principales
index.html: Este archivo contiene la estructura básica de la aplicacion.
style.css: Archivo de estilos que define la apariencia de la aplicacion.
index.js: Script que maneja las funciones y acciones de la aplicacion.

HTML:
La estructura HTML define el diseño de la página web.

La sección contiene metadatos y recursos necesarios para la página. Incluye:

meta nombre="viewport" content="ancho=ancho del dispositivo, escala inicial=1.0"
título de la página web
enlaces a la hoja de estilo y fuentes externas
Incluye un contenedor para agrupar y esta compuesto por
Contenedor Principal: Utiliza un <div> con la clase container que alberga toda la  
aplicacion.
Dos <div>s que agrupan el contenido y boton para el calculo de la edad.
Boton: posee un boton que permite hacer el calculo de la edad correctamente.
y un parrafo que permite ver el resultado de la operacion
a diferencia de mis anteriores proyectos este cuenta con los titulos y parrafos en el idioma ingles

CSS
el estilo CSS define la apariencia de los elementos dentro de la página web colores posicionamiento entre otros.
asi cimo el estilo del calendario.

JAVASCRIPT
el script permite realizar el calculo la edad exacta del usuario hasta el día actual y muestra el resultado en pantalla y cuenta con 

calculateAge(): Calcula la edad basada en la fecha de nacimiento ingresada.
getDaysInMonth(year, month): Retorna el número de días del mes específico considerando el año (para años bisiestos).
