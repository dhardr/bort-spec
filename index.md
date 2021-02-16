# BORT Spec
v-1.0.0

Intro
Es una micro red social que permite publicar “anuncios” o “novedades” o “mini blogs” de sus usuarios para ser compartidos. Cómo está pensada para ser utilizada en entornos pequeños (grupo de trabajo, o de amigos, o del club de barrio), todos los usuarios verán todo el contenido y no hay concepto de “seguidores”. Todo el mundo tiene el mismo feed.

Para el desarrollo, se pueden seguir 2 caminos que tienen elementos en común y otros muy distintos:

- Con MVC (Model View Controller):
Con esta arquitectura, el sistema funcionará como una Web “clásica” donde la mayoría de la lógica de front-end se ejecuta del lado del servidor. Es decir, que el server nos va a entregar HTML/CSS/JS ya renderizado y no haremos demasiada manipulación del DOM a través de Javascript. Este es el caso para los que quieran trabajar en una tecnología típica de las intranets y los entornos empresariales.

- Con SPA (Single Page Application):
Aquí, sugiero el framework Vue JS, pero se puede utilizar React, Angular o Svelte (que los conozco menos). En este caso, vamos a delegar al servidor las operaciones de datos pero no el renderizado de HTML. Es decir, que el front-end se construye 100% con manipulaciones del DOM en Javascript, pero utilizando un framework de programación reactiva como los mencionados arriba. Este es el caso para las aplicaciones/sitios que son públicos y están pensados para uso masivo.\

Con cualquiera de los dos puedo hacer una app empresarial o popular, utilizar una u otra tecnología tiene que ver más con lo que sucede en la industria y no tanto porque se presente alguna restricción técnica que impida usar una u otra para un caso específico.\ 
También se pueden hacer soluciones híbridas que incorporen elementos de las dos.\
En cualquier caso utilizaremos una base de datos MySQL. Para el server, la propuesta es utilizar ASPNET con C#.\ 
Si alguien quiere trabajar en Python en vez de C# puede hacerlo. También podemos utilizar Node Js. Pero tengan en cuenta que en esos otros casos limitan mi posibilidad de asistirlos.

[Link](url) and ![Image](src)
```
