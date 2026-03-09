# AE6.1 - Proyecto HTML/CSS: Presentación Web "AllShoes"

https://josemi2004.github.io/LND_Tarea/

**Desarrollador/a:** José Miguel Hernández Hernanz
**Fecha:** 09/03/2026

---

## 1. Descripción del Proyecto
Este proyecto es la materialización web de una serie de mockups gráficos (5 diapositivas) proporcionados por el cliente para la tienda "AllShoes". El objetivo principal ha sido actuar como puente entre el diseño gráfico y la funcionalidad web, transformando las imágenes estáticas en un sitio web navegable, interactivo y accesible, utilizando exclusivamente las tecnologías de HTML5 y CSS3.

## 2. Estructura del Proyecto
El proyecto está organizado de la siguiente manera para mantener un entorno de trabajo limpio y lógico:

- `index.html`: Página principal (Diapositiva 1 - Inicio).
- `sobre_nosotros.html`: Información de la empresa (Diapositiva 2).
- `cursos.html`: Listado de formaciones (Diapositiva 3).
- `tienda.html`: Catálogo de productos (Diapositiva 4).
- `contacto.html`: Formulario de atención al cliente (Diapositiva 5).
- `estilos.css`: Hoja de estilos principal que controla el diseño visual de todas las páginas.
- `/Imagenes/`: Carpeta que contiene todos los recursos visuales y logos utilizados en la web.

## 3. Cómo Navegar por el Proyecto
La navegación ha sido diseñada para ser fluida e intuitiva:
1. Para comenzar, simplemente abre el archivo **`index.html`** en cualquier navegador web moderno (Chrome, Firefox, Edge, etc.).
2. En la parte superior de todas las páginas encontrarás una barra de navegación (Cabecera) que te permitirá desplazarte libremente entre las 5 secciones (Inicio, Sobre Nosotros, Cursos, Tienda, Contacto).
3. Todas las transiciones y enlaces están gestionados nativamente a través de etiquetas ancla (`<a>`), sin recargas innecesarias.

## 4. Decisiones Técnicas y Metodología de Trabajo
Para garantizar la máxima calidad y cumplir con los requisitos establecidos, el desarrollo se ha basado en los siguientes pilares:

* **Estructura Semántica (HTML5):** Se han utilizado etiquetas semánticas (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`) para dar un significado lógico al contenido, mejorando el SEO y la estructuración interna.
* **Estilizado Fiel al Mockup (CSS3):** Se ha respetado al milímetro la paleta de colores (negro, blanco, naranja, gris), la tipografía y la disposición de los elementos solicitados en los bocetos originales.
* **Nomenclatura en Español y Descriptiva (Requisito Obligatorio):** Todos los selectores de clases e identificadores (`id`) se han redactado en español, dejando claro qué elemento controlan (ej: `.logo-contenedor`, `.titulo-seccion`, `.boton-compra`), lo que facilita la lectura y mantenimiento del código por parte de otros desarrolladores.
* **Interactividad sin JavaScript:** Se han añadido efectos interactivos como transiciones suaves y cambios de color al pasar el cursor (`:hover`) en botones, enlaces y tarjetas de productos, usando puramente CSS.

## 5. Aspectos a tener en cuenta 
* **Comentarios en el Código:** Cumpliendo con los requisitos obligatorios, el código fuente no ha sido sobrecomentado. Solo se han incluido comentarios estructurales para separar secciones principales o justificar decisiones CSS importantes, manteniendo el código limpio.
* **Accesibilidad:** Se han incluido atributos `alt` en todas las imágenes y un contraste de colores adecuado para garantizar que la web sea comprensible por lectores de pantalla y accesible para todos los usuarios.
