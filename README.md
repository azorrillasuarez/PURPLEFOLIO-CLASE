# PORTFOLIO_FDW_2526

Diseño de referencia -> https://purplefolio.framer.website/


- Crear un archivo index.html y generar la estructura básica del HTML -> ! y ENTER

- Crear un archivo style.css (dentro de una carpetita)

- Enlazar el index.html y el style.css (y porbar que estan bien enlazados) -> seleccionar el body y cambiar el background-color

- EXTRA: Averiguar que tipografía esta usando el diseño de referencia purplefolio -> PISTA: usando DevTools



## ETIQUETAS SEMÁNTICAS DE HTML

Son etiquetas de HTML que le indican al navegador que parte de la web esta renderizando.

- <nav></nav> -> la usaremos para añadir todo el contenido del menú de navegación 

- <header></header> -> para la cabecera de la web

- <section></section> -> para definir secciones de la web. Se diferencian entre ellas con un id.

- <footer></footer> -> Para el pie de la web donde se encuentran algunos enlace importantes.

- ALT + Z: Acortar texto del código

- line-height: me sirve para modificar el interlineado en un elemento

- overflow: hidden (para ocultar el contenido en el contenedor)

## FLEXBOX

Las propiedades de css de flexbox me permiten cambiar la posición, el orden y el movimiento de los elementos de HTML. Con flexbox podemos controlar el posicionamiento y la estructuración del HTML con un funiconamiento responsive

Guía INDISPENSABLE de Flexbox -> https://css-tricks.com/snippets/css/a-guide-to-flexbox/

Este conjunto de propiedades sigue la filosofía del diseño responsive y funcionan siguiendo unas normas estructurales por lo que en el HTML necesitamos identificar dos partes:

1. Contenedor FLEX (El elemento padre)
2. El o los elementos flex (elementos hijos)

Para activar estas propiedades lo primero que debemos hacer es estructurar el HTML, luego localizar el elemento contenedor o padre y añadirle la propiedad de CSS -> display: flex;

En la mayoría de los casos vamos a maquetar el HTML con propiedades flexbox pero no estamos obligados. Dependiendo de la situación podemos maquetar el HTML usando ootras propiedades.


Lo ideal es tener un único css para todos los html.