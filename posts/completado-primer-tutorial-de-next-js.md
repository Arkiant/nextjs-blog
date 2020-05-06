---
title: "Completado Primer tutorial de next.js"
date: "2020-05-06"
---

Este tutorial de next.js ha sido genial, he podido aprender bastantes cosas acerca de este framework.

He practicado cosas tales como, Static Generation y Server-side Rendering, librerías externas como remark para renderizar markdown, muy útil si por ejemplo queremos utilizar **headless cms** como strapi, rutas dinámicas, navegación entre páginas, cómo cargar assets, metadata, css y un largo etcétera.

Lo que más me ha gustado son los tips que te van enseñando a lo largo del tutorial, son útiles para tenerlos en cuenta incluso para otros frameworks o lenguajes, sean o no de frontend.

Del framework lo que más me ha llamado la atención son las urls dinámicas (muy sencillas de implementar) y el no tener que elegir entre Static Pages o Server Side Rendering, ya que te permite utilizar el método que prefieras en cada página:

- Las que no se van a modificar (**Static Generation**).
- Las que son personalizadas para cada request (**Server-side Rendering**).

Ambas son geniales para proyectos que necesiten de SEO, pero esto no acaba aquí, también puede haber páginas que se rendericen en el lado del cliente (**Client rendering**) como por ejemplo en paneles de administración porque estos no necesitan ser indexados por Google.

Algo que me ha encantado del framework es que puedes tener un sitio estático pero a la vez obtener datos de una API, por ejemplo si queremos generar una web mediante una API y generar estáticamente las páginas, se puede hacer, además tiene una característica al obtener las urls dinámicas que se llama **fallback** que si activamos podremos generar las páginas estáticas que no tengamos generadas al vuelo, es decir, podremos llamar a una URL que no ha sido generada en tiempo de compilación y generarla en el momento de pedirla. Como por ejemplo, la ficha de producto de un e-commerce, se generará al pedirla por primera vez y el siguiente cliente que pida la misma ficha de producto se le mostrará directamente la que ha sido generada con anterioridad, de esa manera no tenemos por qué generar todas las páginas estáticas de un e-commerce que podría tardar mucho tiempo, en tiempo de compilación.

El tutorial es una buena manera de empezar con Next. Antes de ponerte a hacer este tutorial, es aconsejable hacer el de [react](https://es.reactjs.org/tutorial/tutorial.html) para obtener las nociones básicas del funcionamiento de esta biblioteca de javascript y de ese modo, conseguir las bases para entender Next.

¡Saludos!.
