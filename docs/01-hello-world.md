---
layout: default
title: "Hola mundo literal"
nav_order: 1
---

# "Hola mundo!" Y lo digo en serio

Experimentaremos lo sencillo que es publicar nuestras nuestras ideas en un sitio web público y contar con una vitrina propia y flexible para nuestros clientes.

Lo primero es crear un nuevo repositorio con la herramienta Github Desktop. Recuerda darle un nombre no muy creativo por ahora, evitando tíldes y carácteres como la *ñ*. Los espacios serán reemplazados por *-* automáticamente por la herramienta. 

> **Atención** Cuando veas `nombre-de-tu-proyecto` recuerda reemplazarlo con el nombre que le diste a tu proyecto.

![Creando un nuevo reopositorio en Github Desktop](images/00-hello-world.JPG)

Una vez creado el repositorio minimizamos Github Desktop por un momento y abrimos el programa Visual Studio Code.

En este programa nos dirigimos, en la esquina superior izquierda, a `file > open folder`. Aquí seleccionamos la carpeta que creó Github Desktop dentro de `/Documentos/GitHub/nombre-de-tu-proyecto`

Deberíamos ver algo como la siguiente imagen:

![Visual Studio Code con el proyecto recién creado por Github Desktop](images/01-hello-world.png)

Acá crearemos el archivo `index.html` y agregaremos la plantilla de inicio desde el sitio de [Bootstrap](https://getbootstrap.com/docs/4.6/getting-started/introduction/#starter-template)

Cambiamos el contenido de la etiqueta `h1` por "Hola Mundo" y guardamos con `ctrl + s`.

Suficiente! Llevemos esto al mundo. Volvamos a Github Desktop y generamos nuestra primera versión con un *commit*. Luego clic en el botón publicar y vamos al repositorio en el navegador web.

![Primer commit en GHD](images/01-hello-world-2.png)

Solo nos falta habilitar este repositorio como sitio estático en la sección *pages* al interior de *settings* como en la siguiente imágen:

![Configurar GH pages](images/01-hello-world-3.png)

Tan solo con eso ya tenemos nuestro `Hola mundo` completamente en vivo para cualquier navegador conectado a Internet. Un muy buen comienzo!
