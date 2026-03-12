# Accesibilidad Web - HTML5 + CSS3

## Descripción

Este proyecto consiste en el desarrollo de una página web informativa
sobre **accesibilidad web**, utilizando únicamente **HTML5 y CSS3**.

El objetivo principal es mostrar los conceptos fundamentales de la
accesibilidad en la web y aplicar buenas prácticas de diseño moderno,
estructura semántica y diseño adaptable.

La página presenta información sobre las **WCAG (Web Content
Accessibility Guidelines)**, sus principios, versiones y niveles de
conformidad.

------------------------------------------------------------------------

## Objetivos del proyecto

-   Comprender el concepto de **accesibilidad web**
-   Aplicar **HTML5 semántico** para estructurar el contenido
-   Utilizar **CSS3 moderno** para el diseño visual
-   Implementar **layouts con Flexbox y Grid**
-   Crear una web **responsive** adaptable a distintos dispositivos
-   Mejorar la **usabilidad y legibilidad del contenido**

------------------------------------------------------------------------

## Tecnologías utilizadas

-   HTML5
-   CSS3
-   Flexbox
-   CSS Grid
-   Media Queries (Responsive Design)

No se han utilizado frameworks ni librerías externas.

------------------------------------------------------------------------

## Estructura del proyecto

    /proyecto-accesibilidad
    │
    ├── index.html
    ├── styles.css
    └── README.md

------------------------------------------------------------------------

## Estructura de la página

La página utiliza **etiquetas semánticas de HTML5** para mejorar la
organización y accesibilidad del contenido.

-   `header`
-   `nav`
-   `main`
-   `aside`
-   `footer`

### Header

Contiene el título principal de la página y una breve descripción.

### Nav

Incluye el menú de navegación lateral que permite acceder rápidamente a
las diferentes secciones.

### Main

Contiene el contenido principal:

-   Introducción a la accesibilidad web
-   Importancia de la accesibilidad
-   Principios de las WCAG
-   Versiones y niveles WCAG
-   Herramientas de evaluación

### Aside

Sección lateral con información adicional y buenas prácticas de
accesibilidad.

### Footer

Pie de página con información general del proyecto.

------------------------------------------------------------------------

## Diseño y maquetación

El diseño combina **Flexbox y CSS Grid** para estructurar el contenido
de forma flexible y adaptable.

### Layout principal (Flexbox)

El layout general utiliza Flexbox para dividir la página en tres áreas
principales:

-   Navegación lateral
-   Contenido principal
-   Barra lateral

Ejemplo:

    .layout {
        display: flex;
    }

------------------------------------------------------------------------

### Grid de los principios WCAG

Los principios se presentan en forma de tarjetas utilizando **CSS
Grid**.

    .grid-principios {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(260px,1fr));
    }

Esto permite que las tarjetas:

-   Mantengan un tamaño mínimo
-   Se adapten automáticamente al ancho de la pantalla
-   Aprovechen mejor el espacio disponible

------------------------------------------------------------------------

### Grid de versiones y niveles

También se utiliza CSS Grid para mostrar las versiones y niveles de las
WCAG en tarjetas organizadas.

------------------------------------------------------------------------

## Diseño visual

Se han aplicado varios elementos visuales para mejorar la apariencia de
la página:

-   Gradientes de fondo
-   Tarjetas con sombras
-   Bordes redondeados
-   Efectos hover
-   Colores suaves en tonos azules

Esto ayuda a mejorar la jerarquía visual y la experiencia de usuario.

------------------------------------------------------------------------

## Responsive Design

La página se adapta a diferentes resoluciones mediante **Media
Queries**.

### Desktop

Layout en tres columnas:

NAV \| MAIN \| ASIDE

### Tablet

Las columnas se reorganizan en formato vertical.

### Smartphone

Los grids pasan a una sola columna para mejorar la lectura.

------------------------------------------------------------------------

## Conceptos de accesibilidad aplicados

Durante el desarrollo se han aplicado varias buenas prácticas:

-   Uso de **HTML semántico**
-   Jerarquía correcta de encabezados
-   Contenido estructurado
-   Navegación clara
-   Buena legibilidad del texto

------------------------------------------------------------------------

## Posibles mejoras futuras

-   Añadir iconos en las tarjetas
-   Implementar animaciones suaves
-   Añadir modo oscuro
-   Incluir ejemplos prácticos de accesibilidad
-   Añadir validación automática WCAG

------------------------------------------------------------------------

## Autor

Proyecto desarrollado como práctica de **HTML5 y CSS3** sobre
accesibilidad web por Álvaro Iglesias Gallego.
