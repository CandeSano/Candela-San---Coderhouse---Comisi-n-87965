# 3ra Entrega – Sitio Web Responsive con SASS  
Candela Sano - Coderhouse – Comisión 87965

## ✔ Estructura del proyecto

/
├── index.html
├── pages/
│ ├── contacto.html
│ ├── productos.html
│ ├── servicios.html
│ └── nosotros.html
├── assets/
│ ├── css/
│ │ └── style.css
│ ├── scss/
│ │ ├── abstracts/
│ │ ├── base/
│ │ ├── components/
│ │ ├── layout/
│ │ ├── pages/
│ │ ├── themes/
│ │ ├── vendors/
│ │ └── style.scss
│ └── img/
└── README.md

## ✔ Arquitectura SASS
El proyecto implementa la estructura recomendada para proyectos escalables:

abstracts/ → variables, mixins, funciones
base/ → reset, tipografías
components/ → botones, tarjetas, formularios, menú
layout/ → header, navegación, footer, grilla
pages/ → estilos específicos por página
themes/ → estilos globales del tema, animaciones
vendors/ → overrides de Bootstrap
style.scss → archivo principal que importa todos los parciales

## ✔ Compilación SASS
Para compilar los estilos:

1. Abrir el archivo `assets/scss/style.scss`.  
2. Activar **Watch Sass** desde VSCode.  
3. El compilador genera automáticamente:

assets/css/style.css

## ✔ Tecnologías utilizadas

- HTML5  
- CSS3  
- SASS (SCSS)  
- Bootstrap 5  
- Flexbox y Grid  
- Git y GitHub  
- GitHub Pages  

## ✔ Deploy

El sitio puede visualizarse desde GitHub Pages.  
URL del deploy:  

https://candesano.github.io/Candela-San---Coderhouse---Comisi-n-87965/index.html
