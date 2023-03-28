# Proyecto Festival de Musica

En este proyecto creo que una pagina para un festival de música en el cual tenemos una sección sobre información general, una con los lineups y de ultimo vemos los dos posibles boletos a comprar

Este proyecto es un sitio web construido con HTML, CSS y JavaScript, y automatizado con la herramienta de construcción Gulp. Este archivo README proporciona información sobre cómo usar el proyecto y cómo se estructura el código fuente.

##Requisitos

Para ejecutar este proyecto en un entorno de desarrollo local, debes tener instalado Node.js y Gulp en tu computadora.



## Instalación

1. Clonar el repositorio: `git clone https://github.com/usuario/repo.git`
2. Instalar las dependencias: `npm install`

## Estructura del Proyecto

`src/` - Contiene los archivos fuente del proyecto, incluyendo HTML, SCSS y JavaScript.
`build/` - Contiene los archivos generados y optimizados del proyecto para producción.
`gulpfile.js` - Define las tareas de Gulp para construir y automatizar el proyecto.
`package.json` - Define las dependencias del proyecto y los scripts de construcción y ejecución.

## Tareas de Gulp

###css
Esta tarea compila los archivos SCSS del proyecto y los convierte en archivos CSS. Los archivos CSS resultantes se almacenan en la carpeta `build/css`.

### imagenes
Esta tarea optimiza las imágenes PNG y JPG del proyecto, almacena los archivos optimizados en la carpeta `build/img`.

### versionWebp
Esta tarea convierte las imágenes PNG y JPG del proyecto en formato WebP, almacena los archivos resultantes en la carpeta `build/img`.

### versionAvif
Esta tarea convierte las imágenes PNG y JPG del proyecto en formato AVIF, almacena los archivos resultantes en la carpeta `build/img`.

### javascript
Esta tarea minifica y optimiza los archivos JavaScript del proyecto, almacena los archivos resultantes en la carpeta `build/js`.

### dev
Esta tarea ejecuta las tareas imagenes, versionWebp, versionAvif, javascript y css en paralelo, y luego observa los cambios en los archivos fuente del proyecto, para que se ejecute automáticamente la tarea correspondiente cada vez que se detecte un cambio.

## Uso
Ejecuta el siguiente comando en la terminal para compilar los archivos SCSS, optimizar las imágenes y minificar el código JavaScript del proyecto:
`gulp dev`
Abre el archivo index.html en tu navegador para ver la versión optimizada del sitio web.

## Tecnologías utilizadas

- Gulp
- SCSS
- JavaScript
