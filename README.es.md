# RSS-medium
Lector rss para perfiles con posts en [Medium](https://medium.com). Presenta los posts mediante tarjetas que están en un carrusel. Utiliza Bootsrap, CSS y JQuery.

## Como usarlo

Para realizar la correcta implementación solo es encesario insertar las librerias de bootstrap y JQuery en el archivo index.html.

Posteriormente enlazar el archivo rss.js, en el cual se encuentran las variables de total de post a publicar(numPostsToShow) y el usuario (mediumUrl).
<code>
    const mediumUrl = 'https://ingegus.medium.com'; // URL de Medium
    const numPostsToShow = 4; // Número de posts a mostrar
</code>

Por otra parte utiliza el sitio https://rss2json.com para poder convertir el feed de Medium a un archivo Json y de esta forma poder hacer los proecesos de extracción.

### Características.

* Permite indicar cuantos post se desean publicar
* En caso de ser menos de 3 oculta los botones de navegación
* Botones con colores accesibles para facilitar la lectura
* En caso que el post no cuente con una imagen carga una imagen genérica, el logo de Medium

### Sitio de ejemplo
Pueden observar el funcionamiento final ingresando a https://ingegus.dev/RSS-medium/
