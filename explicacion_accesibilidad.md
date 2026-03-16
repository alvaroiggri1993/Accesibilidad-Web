# Accesibilidad Web -- Explicación del proyecto

## 1. ¿Qué es la accesibilidad web?

La **accesibilidad web** consiste en diseñar páginas web que puedan ser
utilizadas por **todas las personas**, independientemente de sus
capacidades o limitaciones.

Esto incluye usuarios con:

-   👁️ Discapacidad visual (personas ciegas o con baja visión)
-   🔊 Discapacidad auditiva (personas sordas)
-   🖐️ Problemas de movilidad o psicomotricidad
-   🧠 Dificultades cognitivas
-   📱 Personas que usan móviles o dispositivos diferentes

El objetivo es que **nadie tenga barreras para acceder a la
información**.

------------------------------------------------------------------------

# 2. Por qué este proyecto es un buen ejemplo de accesibilidad

Este proyecto utiliza varias técnicas recomendadas por el **W3C (World
Wide Web Consortium)** y las **WCAG (Web Content Accessibility
Guidelines)**.

Se aplican buenas prácticas tanto en **HTML** como en **CSS**.

------------------------------------------------------------------------

# 3. Uso de HTML semántico

El código utiliza etiquetas que describen claramente la estructura de la
página.

Ejemplo:

``` html
<header>
<nav>
<main>
<section>
<aside>
<footer>
```

Estas etiquetas ayudan a:

-   Los **lectores de pantalla**
-   Los **buscadores**
-   La **organización del contenido**

Por ejemplo:

``` html
<header>
    <h1>Accesibilidad Web</h1>
</header>
```

Indica claramente que es el **encabezado principal de la página**.

------------------------------------------------------------------------

# 4. Navegación clara

La página incluye un menú de navegación sencillo:

``` html
<nav>
    <ul>
        <li><a href="#intro">Introducción</a></li>
    </ul>
</nav>
```

Esto permite que los usuarios:

-   encuentren fácilmente las secciones
-   naveguen por la página de forma sencilla

------------------------------------------------------------------------

# 5. Enlace para saltar al contenido

Se incluye un **skip link**, que permite a los usuarios de teclado
saltar el menú.

``` html
<a href="#intro" class="skip-link">Saltar al contenido</a>
```

Esto es muy útil para:

-   personas que usan **lectores de pantalla**
-   usuarios que navegan con **teclado**

------------------------------------------------------------------------

# 6. Texto alternativo en imágenes

Las imágenes incluyen un atributo `alt`.

``` html
<img src="lector-pantalla.jpg"
alt="Persona utilizando un lector de pantalla">
```

Esto permite que los **lectores de pantalla describan la imagen** a
personas ciegas.

------------------------------------------------------------------------

# 7. Contenido accesible para diferentes discapacidades

El proyecto incluye ejemplos de accesibilidad para varios tipos de
usuarios.

### Discapacidad visual

-   uso de texto alternativo
-   navegación por teclado

### Discapacidad auditiva

-   uso de vídeos que pueden tener subtítulos

### Dificultades motoras

-   botones grandes
-   interacción sencilla

``` html
<button class="boton-accesible">
Botón accesible grande
</button>
```

### Dificultades cognitivas

-   lenguaje simple
-   listas fáciles de entender
-   estructura clara

------------------------------------------------------------------------

# 8. Diseño adaptable (Responsive)

El sitio funciona en distintos dispositivos:

-   ordenador
-   tablet
-   móvil

Esto se consigue con **media queries en CSS**.

Ejemplo:

``` css
@media (max-width:900px){
    .layout{
        flex-direction:column;
    }
}
```

Esto reorganiza la página en pantallas pequeñas.

------------------------------------------------------------------------

# 9. Navegación con teclado

El CSS incluye estilos para mostrar el foco del teclado:

``` css
a:focus,
button:focus{
    outline:3px solid rgb(80,90,220);
}
```

Esto permite saber **qué elemento está seleccionado** al navegar con la
tecla **TAB**.

------------------------------------------------------------------------

# 10. Estructura clara y organizada

La información se presenta con:

-   títulos (`h1`, `h2`, `h3`)
-   listas
-   secciones diferenciadas

Esto mejora la **comprensión del contenido**.

------------------------------------------------------------------------

# 11. Conclusión

Este proyecto es un buen ejemplo de accesibilidad porque:

-   usa **HTML semántico**
-   tiene **navegación clara**
-   incluye **texto alternativo**
-   permite **navegación por teclado**
-   muestra ejemplos para **diferentes tipos de discapacidad**
-   tiene **diseño adaptable para móviles**

Gracias a estas características, la página puede ser utilizada por **más
personas y en más dispositivos**, lo cual es el objetivo principal de la
accesibilidad web.
