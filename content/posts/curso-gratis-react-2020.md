---
title: Curso gratis de ReactJS 2020 con clases en vivo
date: '2020-05-17'
image: '/images/curso-gratis-react-2020.jpg'
description: Aprende qué es React, crea una aplicación desde cero, crea tus propios hooks y añade infinite scroll y testing con estas clases en vivo gratis.
language: 🇪🇸
toc: true
tags:
- react
---

Las últimas semanas he estado emitiendo todos los viernes un live coding **[en mi canal de Youtube](https://www.youtube.com/c/midudev?sub_confirmation=1)** donde hemos ido construyendo paso a paso y desde cero **una aplicación de React para buscar Gifs utilizando la API de Giphy.**

### Primera clase: [Aprendiendo React desde cero](https://youtu.be/T_j60n1zgu0)
{{< youtube id="T_j60n1zgu0" >}}
{{< subscribe-to-youtube >}}

En esta clase aprendemos React desde cero y respondamos a las preguntas: **¿Qué es React? ¿Por qué deberías aprenderlo?** ¿Por qué lo necesitamos? ¿Qué es JSX?

También vemos **qué son las props y state**. Definimos el concepto de componente y vemos cómo usar eventos. Cómo funciona el renderizado condicional y usamos un hook, `useState` para añadir estado a nuestros componentes.

### Segunda clase: [Crea un app con create-react-app](https://youtu.be/QBLbXgeXMU8)
{{< youtube id="QBLbXgeXMU8" >}}
{{< subscribe-to-youtube >}}

Ahora que **ya conocemos los conceptos básicos de React**, es el momento de **crear nuestra primera aplicación con todo lo aprendido.** En esta clase conocemos la herramienta `create-react-app` que nos permite crear desde cero una aplicación y nos permite no tener que preocuparnos por la configuración. Así empezaremos a crear nuestra aplicación para buscar gifs.

También vemos más hooks, como `useEffect` para ejecutar código cada vez que nuestro componentes se renderiza o sus dependencias cambian. Además también hacemos las primeras llamadas a una API y vemos cómo lo podemos gestionar.

### Tercera clase: [Custom Hooks y React Context](https://youtu.be/2qgs7buSnHQ)
{{< youtube id="2qgs7buSnHQ" >}}
{{< subscribe-to-youtube >}}

**Subimos de nivel con los hooks.** En esta clase vemos cómo podemos crear nuestro propio hook para reutilizar parte de la lógica a la hora de buscar Gifs. También vemos cómo podemos manejar un formulario para escuchar sus eventos y por qué es una buena práctica utilizar el `onSubmit` y evitar escuchar simplemente el `onClick` de un botón.

Además conocemos **React Context, una funcionalidad de la biblioteca que nos permite compartir información entre componentes sin que le lleguen por las props.** Esto, además, nos permitirá crear una especie de estado global. Hablamos de las buenas prácticas sobre esto y cómo podemos conseguirlo.

### Cuarta clase: [Lazy Load, Suspense y Paginación](https://youtu.be/VcxXipZg1-0)
{{< youtube id="VcxXipZg1-0" >}}
{{< subscribe-to-youtube >}}

**Para mejorar el rendimiento de nuestro sitio conocemos el concepto de Lazy Load** y cómo podemos hacer que nuestra aplicación se separe en `chunks`. Estos `chunks` o `pedazos` de la app se descargarán solo cuando sea necesario. Lo hacemos con una nueva sección que en móvil no aparece de forma que lo cargaremos sólo cuando hagamos scroll. Para ello creamos un nuevo hook llamado `useNearScreen`.

Para hacerlo descubrimos `React.lazy`, que nos permite cargar dinámicamente nuestros componentes. Sin embargo, veremos que esto no funciona tal cuál si no que tenemos que envolver el componentente que se carga de forma diferida con un componente de React llamado `<Suspense>` y que nos permite indicarle un `fallback`, un elemento que se renderizará mientras se carga el nuevo.

Además, **añadimos paginación** a nuestra aplicación, para poder ver más gifs.

### Quinta clase: [CSS Grid, Infinite Scroll y Testing](https://youtu.be/oCHdFiCgOSE)
{{< youtube id="oCHdFiCgOSE" >}}
{{< subscribe-to-youtube >}}

Cuando hicmos la paginación, vimos que no se estaban añadiendo correctamente los resultados. Así que en esta clase **mejoramos el layout de nuestra app utilizando **CSS Grid**** y vemos cómo podríamos hacer un diseño `masonry` (por ahora **sólo con Firefox Nightly pero... es un momento WOW!** 🤩).

Además, conseguimos **reusar el hook `useNearScreen` para añadirle Infinite Scroll** a nuestra aplicación y vemos los problemas que nos podemos encontrar y cómo solucionarlo con `useCallback` y usando la función `debounce`.

Finalmente, empezaremos a ver algo de testing con `Jest` y `@testing-library/react`. Además de algún test muy básico, también veremos cómo podemos probar **componentes que se cargan de forma asíncrona.**

### Sexta clase: [React.memo, mejora el rendimiento de la app y Deploy con Vercel] (https://www.youtube.com/watch?v=Wo7_OVtu1ls)
{{< youtube id="Wo7_OVtu1ls" >}}
{{< subscribe-to-youtube >}}

Ahora es el momento de **optimizar nuestra aplicación**. Para ello, aprenderemos qué son las **React Developer Tools** y cómo podemos sacarle partido para detectar renderizados innecesarios en nuestra aplicación. También aprendemos qué es `React.memo` y cómo podemos usarlo para arreglar esos problemas de optimización.

Finalmente, haremos un **deploy desde la terminal gracias a los servicios gratuitos de Vercel**, que nos ofrecerá SSL y una URL para compartir con nuestros colegas.

### Séptima clase: [SEO con React y Deploy Integrado con GitHub](https://www.youtube.com/watch?v=b-pwpHaYOTI)
{{< youtube id="b-pwpHaYOTI" >}}
{{< subscribe-to-youtube >}}

Ahora que ya tenemos nuestra aplicación de **React ⚛️** desplegada en producción, es el momento de asegurarnos que Google va a ver los títulos y descripciones correctos. Para ello vamos a hacer algo de SEO con nuestra app de React. Primero lo creamos desde cero, con un custom hook, llamado **useTitle** y otro **useSEO**. Pero veremos que esto es difícil de hacer que mantener, así que pasaremos a usar **react-helmet.** Conoceremos otra alternativa, llamada `react-head` que es algo más liviano y también muy interesante.

Para acabar la clase, vamos a ver cómo crear un **continuous deployment en GitHub** y que nos deje una URL deployada por cada Pull Request usando **Vercel** y su integración con este servicio.

### Suscríbete: [¿Quieres más videos sobre frontend? ¡Suscríbete a mi canal!](https://www.youtube.com/c/midudev?sub_confirmation=1)
{{< subscribe-to-youtube >}}