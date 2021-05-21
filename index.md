---
layout: default
title: "Inicio"
nav_order: 0
---
# Mi primer sitio web 
## Estático, en la nube, escalable, responsivo, simple y serverless

Hola! Bienvenidos al demo final del curso [Introducción a las tecnologías web para no programadores](https://boolean.cl/cursos/intro-a-web). Crearemos un sitio completo usando los fundamentos del desarrollo web: **HTML**, **CSS** y **Javascript**. Entendiendo y aplicando estos fundamentos los estudiantes podrán afrontar de mejor manera los siguientes niveles de abstracción que componen el ecosistema actual de frameworks y librerías. Veremos lo rápido y sencillo que es crear un *Landing Page* efectivo y moderno, pero también entenderemos los limites de este enfoque cuando pasemos a construir aplicaciones en lugar de sitios.

**Con esta guía el estudiante podrá:**

  1. Desplegar sitios web con Github Pages o similares 
  2. Crear sitios responsivos utilizando el framework Bootstrap
  3. Procesar formularios de contacto
  4. Agregar contacto directo por WhatsApp


<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css">
<a href="https://api.whatsapp.com/send?phone=51955081075&text=Hola%21%20Quisiera%20m%C3%A1s%20informaci%C3%B3n%20sobre%20Varela%202." class="whatsapp__float" target="_blank">
<i class="fa fa-whatsapp my-float"></i>
</a>
  

En concreto vamos a construir un sitio web completo para mostrar nuestros productos y un formulario de contacto. Las herramientas que usaremos durante este proyecto son:

  + [Github](https://github.com/)
  + [Github Desktop](https://desktop.github.com/)
  + [Visual Studio Code](https://code.visualstudio.com/)
  + [Netlify](https://code.visualstudio.com/)

>Si tienes dudas en cómo instalar y configurar estas herramientas consulta con tu equipo de mentores por los videos de los laboratorios.

## Frontend

Usaremos la dupla **VueJS**/**Vuetify** más los *plugins* **Vue-Router** y **Vuex** para construir una Single Page Application (SPA). 

## Backend

Construiremos un servidor **NodeJS** con la librería **Express**. La autenticación en todo el stack será implementada usando el servicio de **Firebase**. 

## Deployment

La aplicación será publicada en la plataforma **Heroku** con un proceso de despliegue en **Github actions**. Con esta arquitectura las **soluciones** podrán consumir a futuro servicios de **Firebase** y/o **Heroku**.

## Calidad y mantenimiento

Utilizaremos **Cypress** para las pruebas de extremo a extremo (e2e) integrando Backend y Frontend. **Jest** para pruebas unitarias y herramientas como **eslint** y **husky** para resguardar la calidad del código. 

<hr/>
<blockquote style="background-color:PaleGoldenRod;padding:20px">
  <h3>Advertencia</h3>
  <p>La elección de los frameworks y plataformas se hizo considerando alta productividad con baja curva de aprendizaje para enfocarnos en el uso del lenguaje Javascript en un proceso de desarrollo Ágil. En Boolean creemos que la metodología de desarrollo es tanto o más importante que las tecnologías o frameworks. En otras palabras, la metodología usada en esta guía aplica a cualquier combinación de frameworks o librerías Javascript (React, Angular, Koa, etc).</p>
</blockquote>
<hr/>

El resultado final será similar a las siguientes imágenes:

<figure>
  <img src="docs/images/00-demoScreen-1.png" alt="Lo que haremos 1">
  <figcaption style="text-align:right">Vista login de la aplicación</figcaption>
</figure>

<hr>

<figure>
  <img src="docs/images/00-demoScreen-2.png" alt="Lo que haremos 2">
  <figcaption style="text-align:right">Vista página de productos</figcaption>
</figure>

Manos a la obra!
