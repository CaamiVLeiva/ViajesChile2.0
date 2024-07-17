# Proyecto "Viajes Chile"

## Descripción del Proyecto

Este proyecto es la landing page de Viajes Chile, desarrollada como parte de un proyecto final del módulo, utilizando HTML, Sass, y JavaScript para la lógica interactiva.

## Estructura del Proyecto

El proyecto sigue una estructura organizada con los siguientes archivos y carpetas:

- **index.html**: Página principal del sitio, estructurada con etiquetas semánticas HTML y estilos de Sass.
- **assets/**:
  - **css/**: Contiene `main.css` y `main.css.map` para estilos compilados desde Sass.
  - **img/**: Directorio para imágenes utilizadas en el proyecto, incluyendo fotos de testimonios y recursos gráficos.
  - **js/**: Incluye `index.js` para funcionalidades JavaScript del sitio.
  - **sass/**:
    - **abstracts/**: Archivos Sass de variables como `_variables.scss`.
    - **base/**: Estilos base como `_reset.scss` y `_typography.scss`.
    - **components/**: Estilos de componentes como `_cards.scss`, `_carrusel.scss`, `_navbar.scss`, y `_testimonio.scss`.
    - **shame/**: Archivos de Sass para estilos que requieren refactorización futura como `_shame.scss`.
    - **vendors/**: Archivos de integración con frameworks como `_bootstrap.scss`.

## Diagrama de Estructura
```
└── 📁ProyectoFinalModulo
    └── .gitignore
    └── 📁assets
        └── 📁css
            └── main.css
            └── main.css.map
        └── 📁img
            └── card1.jpg
            └── card2.jpg
            └── card3.jpg
            └── card4.jpg
            └── carousel1.jpg
            └── carousel2.jpg
            └── carousel3.jpg
            └── quienes-somos.jpg
            └── testimonio1.jpg
            └── testimonio2.jpg
            └── testimonio3.jpg
            └── viajes.svg
        └── 📁js
            └── index.js
        └── 📁sass
            └── 📁abstracts
                └── _variables.scss
            └── 📁base
                └── _reset.scss
                └── _typography.scss
            └── 📁components
                └── _cards.scss
                └── _carrusel.scss
                └── _navbar.scss
                └── _testimonio.scss
            └── 📁layout
            └── main.scss
            └── 📁pages
            └── 📁shame
                └── _shame.scss
            └── 📁themes
            └── 📁vendors
                └── _bootstrap.scss
    └── index.html
    └── package-lock.json
    └── package.json
    └── README.md
```


## Instrucciones de Uso

Para ejecutar este proyecto localmente:

1. Clona este repositorio: `git clone https://github.com/CaamiVLeiva/ViajesChile2.0.git`
2. Abre `index.html` en tu navegador web.

## Recursos Adicionales

- [Documentación de Bootstrap](https://getbootstrap.com/docs/)
- [Font Awesome Icons](https://fontawesome.com/icons)
