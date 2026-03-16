# Accesibilidad Web - HTML5 + CSS3

## Descripción

Este proyecto consiste en el desarrollo de una página web informativa
sobre **accesibilidad web**, utilizando únicamente **HTML5 y CSS3**.

El objetivo principal es mostrar los conceptos fundamentales de la
accesibilidad en la web y aplicar buenas prácticas de **estructura
semántica, diseño accesible y diseño adaptable**.

La página presenta información sobre las **WCAG (Web Content
Accessibility Guidelines)**, sus principios, versiones y niveles de
conformidad, además de incluir **ejemplos prácticos de accesibilidad
para distintos tipos de usuarios**.

------------------------------------------------------------------------

# Objetivos del proyecto

-   Comprender el concepto de **accesibilidad web**
-   Aplicar **HTML5 semántico** para estructurar el contenido
-   Utilizar **CSS3 moderno** para el diseño visual
-   Implementar **layouts con Flexbox y Grid**
-   Crear una web **responsive** adaptable a distintos dispositivos
-   Mejorar la **usabilidad y legibilidad del contenido**
-   Incluir **ejemplos reales de accesibilidad para diferentes
    usuarios**

------------------------------------------------------------------------

# Tecnologías utilizadas

-   HTML5
-   CSS3
-   Flexbox
-   CSS Grid
-   Media Queries (Responsive Design)

------------------------------------------------------------------------

# Estructura del proyecto

    /proyecto-accesibilidad
    │
    ├── index.html
    ├── style.css
    └── README.md

------------------------------------------------------------------------

# Estructura de la página

La página utiliza **etiquetas semánticas de HTML5** para mejorar la
organización y accesibilidad del contenido.

Elementos principales utilizados:

-   `header`
-   `nav`
-   `main`
-   `section`
-   `article`
-   `aside`
-   `footer`

Estas etiquetas ayudan a que **lectores de pantalla y navegadores
interpreten correctamente la estructura del contenido**.

------------------------------------------------------------------------

# Secciones de la página

## Header

Contiene el título principal de la página y una breve descripción del
tema.

------------------------------------------------------------------------

## Nav

Incluye el menú de navegación lateral que permite acceder rápidamente a
las diferentes secciones:

-   Introducción
-   Importancia de la accesibilidad
-   Principios WCAG
-   Versiones y niveles
-   Herramientas de evaluación
-   Ejemplos de accesibilidad

------------------------------------------------------------------------

## Main

Contiene el contenido principal de la página:

-   Introducción a la accesibilidad web
-   Importancia de la accesibilidad
-   Principios de las WCAG
-   Versiones y niveles WCAG
-   Herramientas de evaluación
-   Ejemplos de accesibilidad

------------------------------------------------------------------------

# Ejemplos de accesibilidad

La página incluye ejemplos prácticos para distintos tipos de usuarios.

## Discapacidad visual

Se utilizan imágenes con **texto alternativo (`alt`)** para que los
lectores de pantalla puedan describirlas.

``` html
<img src="lector-pantalla.jpg"
alt="Persona utilizando un lector de pantalla">
```

------------------------------------------------------------------------

## Discapacidad auditiva

Se incluyen vídeos que pueden incorporar **subtítulos** para facilitar
la comprensión del contenido.

------------------------------------------------------------------------

## Dificultades motoras

Se utilizan **botones grandes y fáciles de pulsar**, lo que facilita la
interacción para personas con movilidad reducida.

``` html
<button class="boton-accesible">
Botón accesible grande
</button>
```

------------------------------------------------------------------------

## Dificultades cognitivas

El contenido está diseñado con:

-   lenguaje sencillo
-   frases cortas
-   listas organizadas
-   navegación clara

Esto facilita la comprensión del contenido.

------------------------------------------------------------------------

# Aside

Sección lateral que incluye:

-   datos interesantes sobre accesibilidad
-   buenas prácticas de desarrollo accesible

------------------------------------------------------------------------

# Footer

Pie de página con información general del proyecto.

------------------------------------------------------------------------

# Diseño y maquetación

El diseño combina **Flexbox y CSS Grid** para estructurar el contenido
de forma flexible y adaptable.

------------------------------------------------------------------------

## Layout principal (Flexbox)

El layout general utiliza Flexbox para dividir la página en tres áreas
principales:

-   Navegación lateral
-   Contenido principal
-   Barra lateral

``` css
.layout {
    display: flex;
}
```

------------------------------------------------------------------------

## Grid de los principios WCAG

Los principios se presentan en forma de tarjetas utilizando **CSS
Grid**.

``` css
.grid-principios {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px,1fr));
}
```

Esto permite que las tarjetas:

-   mantengan un tamaño mínimo
-   se adapten automáticamente al ancho de la pantalla
-   aprovechen mejor el espacio disponible

------------------------------------------------------------------------

# Diseño visual

Se han aplicado varios elementos visuales para mejorar la apariencia de
la página:

-   Gradientes de fondo
-   Tarjetas con sombras
-   Bordes redondeados
-   Efectos hover
-   Colores suaves en tonos azules

Esto ayuda a mejorar la jerarquía visual y la experiencia de usuario.

------------------------------------------------------------------------

# Responsive Design

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

# Características de accesibilidad implementadas

Durante el desarrollo se han aplicado varias buenas prácticas:

-   Uso de **HTML semántico**
-   Jerarquía correcta de encabezados
-   Navegación clara
-   Texto alternativo en imágenes
-   Botones accesibles
-   Navegación mediante teclado
-   Indicador visual de foco (`:focus`)
-   Enlace para **saltar al contenido** (skip link)

``` html
<a href="#intro" class="skip-link">
Saltar al contenido
</a>
```

Esto permite a los usuarios de teclado acceder directamente al contenido
principal.

------------------------------------------------------------------------

# Posibles mejoras futuras

-   Añadir iconos en las tarjetas
-   Implementar subtítulos reales en los vídeos
-   Añadir modo oscuro
-   Implementar alto contraste
-   Añadir control para aumentar el tamaño del texto
-   Integrar validación automática WCAG

------------------------------------------------------------------------

# Autor

Proyecto desarrollado como práctica de **HTML5 y CSS3** sobre
accesibilidad web.

Autor: **Álvaro Iglesias Gallego**
