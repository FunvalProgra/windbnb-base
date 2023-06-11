# Instrucciones

Bienvenido al mini proyecto del nivel 2. En este proyecto estaremos aplicando los adquiridos tanto en el nivel 1 como lo que estás aprendiendo en el nivel 2. Sigue las instrucciones de este archivo para completar el proyecto y ten en cuenta que estas mismas instrucciones se tomaran en cuenta para la evaluación del proyecto.

## Instrucciones generales

Una nueva empresa en el sector de viajes llamada **windbnb** ha solicitado tu ayuda para crear una aplicación web que permita a los usuarios buscar y filtrar alojamientos en diferentes lugares. El diseño de la aplicación web ya está terminado y ahora necesita que lleves a codigo este proyecto. Por suerte, ya tienes una base de código que puedes utilizar para comenzar a trabajar. Segun las instrucciones que el cliente nos ha dado, te daré las instrucciones para completar el proyecto.

El Figma del proyecto se encuentra en el siguiente enlace: [Windbnb](https://www.figma.com/file/KGNH8dbclXT1vzXLyPrBeu/Windbnb?node-id=0-1)

## Instrucciones del proyecto

### Layout | Diseño

El diseño de esta página web debe ser 100% responsive. Debes asegurarte de que el diseño se adapte a diferentes tamaños de pantalla. Para lograr esto, el cliente y tu han acordado que se trabajará con la librería de Bootstrap 5. Para los estilos **que no se puedan** lograr con Bootstrap, puedes utilizar CSS puro.

Dentro del archivo Figma verás que hay 2 vistas principales: **Mobile** y **Desktop**. Te recomendamos que trabajes con la vista **Mobile** primero y luego con la vista **Desktop**. Esto te ayudará a enfocarte en la responsividad de la página web, a la vez que Bootstrap está creado con este enfoque.

### Fuentes

Las fuentes para este proyecto las hemos traido de [Google Fonts](https://fonts.google.com/). Ya hemos importado las fuentes a usar al proyecto. Para usarlas desde CSS, puedes utilizar la siguiente sintaxis:

```css
font-family: 'Montserrat', sans-serif; /* Fuente principal */
font-family: 'Mulish', sans-serif; /* Fuente secundaria */
```

### Iconos

Para los iconos, utilizaremos la librería de iconos de Google: [Material Icons](https://fonts.google.com/icons). Para usarlos puede seguir el enlace anterior y buscar el icono que necesite. Una vez que lo encuentre, copie el código que se le proporciona y peguelo en el HTML. Por ejemplo:

```html
<i class="material-icons-sharp">favorite</i>
```


### Código base

Se te proporciona un código base para comenzar con el proyecto. Te recomendamos revisarlo y entenderlo para que puedas aprovecharlo al máximo. Puedes modificarlo de considerarlo necesairio, sin embargo debes tener cuidado con ello, ya que la base que se te entrega está pensada para que puedas completar el proyecto sin tener que modificarla demasiado. Algunas cosas que no debes modificar son:

- El nombre de los archivos y carpetas proporcionados.
- El archivo `stays.json` que contiene los datos de los alojamientos.
- El archivo `index.html` que contiene la estructura de la página web. Varios de los estilos ya están listos, sin embargo, debes completarlos para que se adapten a los requerimientos del proyecto.

## Consideraciones para la calificación

A continuación te diremos cuales son los puntos que se tomarán en cuenta para la calificacion del proyecto:

- El diseño debe ser 100% responsive.
- El diseño debe ser lo más fiel posible al proporcionado en el archivo Figma.
- Los colores, fuentes, tamaños de letra, etc. deben ser los proporcionados en el archivo Figma.
- El proyecto debe ser desarrollado con Bootstrap 5. Para los estilos **que no se puedan** lograr con Bootstrap, puedes utilizar CSS puro.
- Los datos deben ser obtenidos del archivo `stays.json` y no deben ser escritos a mano.
- El proyecto debe ser modulado y estructurado de forma que sea fácil de entender y mantener.
- El proyecto debe ser publicado en GitHub Pages.
- El proyecto debe tener más de un commit.
- La estructura de carpetas actual se debe respetar.
- Las funciones dentro de los distintos modulos (`app.js`, `data.js` y `dom.js`) debe ir de acorde a su nombre.
- El proyecto debe ser subido a GitHub y el enlace debe ser enviado para su revisión.
