+++
title = 'Bootstrap'
date = 2024-11-12T12:51:05+01:00
draft = false
+++

Fuente información: [Rockcontent](https://rockcontent.com/es/blog/bootstrap/)

## Qué es y para qué sirve 

> Bootstrap es un framework front-end utilizado para desarrollar aplicaciones web y sitios mobile first, con un layout que se adapta a la pantalla del dispositivo utilizado por el usuario. ¡Aprende todo sobre esta tecnología y cómo utilizarla!


## ¿Qué es Bootstrap?
Bootstrap es un framework CSS desarrollado por Twitter en 2010, para estandarizar las herramientas de la compañía.

Inicialmente, se llamó Twitter Blueprint y, un poco más tarde, en 2011, se transformó en código abierto y su nombre cambió para Bootstrap. Desde entonces fue actualizado varias veces y ya se encuentra en la versión 4.4.

El framework combina CSS y JavaScript para estilizar los elementos de una página HTML. Permite mucho más que, simplemente, cambiar el color de los botones y los enlaces.

Esta es una herramienta que proporciona interactividad en la página, por lo que ofrece una serie de componentes que facilitan la comunicación con el usuario, como menús de navegación, controles de página, barras de progreso y más.

Además de todas las características que ofrece el framework, su principal objetivo es permitir la construcción de sitios web responsive para dispositivos móviles.

Esto significa que las páginas están diseñadas para funcionar en desktop, tablets y smartphones, de una manera muy simple y organizada.

## ¿Cómo funciona?
Bootstrap está constituido por una serie de archivos CSS y JavaScript responsables de asignar características específicas a los elementos de la página.

Hay un archivo principal llamado bootstrap.css, que contiene una definición para todos los estilos utilizados. 

Básicamente, la estructura del framework se compone de dos directorios:

- css: contiene los archivos necesarios para la estilización de los elementos y una alternativa al tema original;

- js: contiene la parte posterior del archivo bootstrap.js (original y minificado), responsable de la ejecución de aplicaciones de estilo que requieren manipulación interactiva.

## Ejemplos de funcionalidades

### Sistema de Grid

```html
<div class="container">
    <div class="row">
        <div class="col-md-4">Columna 1</div>
        <div class="col-md-4">Columna 2</div>
        <div class="col-md-4">Columna 3</div>
    </div>
</div>

```

### Botones personalizables

```html
<button type="button" class="btn btn-primary">Botón Primario</button>
<button type="button" class="btn btn-secondary">Botón Secundario</button>

```

### Barra de navegación

```html
<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">Logo</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
            <li class="nav-item active">
                <a class="nav-link" href="#">Inicio</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Características</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Precios</a>
            </li>
        </ul>
    </div>
</nav>

```
