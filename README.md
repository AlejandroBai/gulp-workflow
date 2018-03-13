# Workflow de desarrollo Frontend con Gulp.js

Entorno de trabajo para el Desarrollo Web Frontend usando [GULP.JS](https://gulpjs.com/) como gestor de tareas

## ¿Qué es esto?

Este Workflow está diseñado para facilitar el desarrolllo Frontend. Compila y minifica HTML, CSS y JavaScript. Minifica archivos y concatena. Además está provisto de un servidor local con BrowserSync para testear en tiempo real lo que vamos desarrollando incluso en dispositivos externos conectados a la misma IP del wifi.

El resultado es un espacio para el desarrollo con dos simples comandos en el terminal. Y con otro comando una exportación para subir a nuestro servidor lo que hagamos, ya optimizado y funcionando.

### Conocimientos
Se requiere conocimientos de HTML, CSS y JavaScript. Así como nociones básicas de uso de terminal, node y npm.

### Requisitos

Para que este Workflow funcione hay que tener instalado Node.js. Puedes instalarlo desde su web oficial:
* [NODE.JS](https://nodejs.org/es/)

Una vez instalado puedes comprobar en el terminal el número de versión para confirmar que se ha instalado correctamente:

```
$ node -v
v9.6.1
```

También debemos instalar Git
* [GIT](https://git-scm.com/downloads)

Y lo mismo, una vez instalado puedes comprobar en el terminal el número de versión para confirmar que se ha instalado correctamente:

```
$ git --version
git version 2.14.3
```

### Instación del Workflow

Para descargar el proyecto, puedes hacerlo desde el enlace que provee GitHub y descargar todo el paquete en .zip:
* [Workflow-Gulp](https://github.com/AlejandroBai/bai-frontend-workflow-gulp.git)

O copiar en el terminal lo siguiente:
```
$ npm git clone https://github.com/AlejandroBai/bai-frontend-workflow-gulp.git
```

### Instación de todas las dependencias para que funcione

Antes de comenzar, vamos a la carpeta raíz donde tenemos todo el paquete de archivos descargados / clonados y ejecutamos:

```
$ npm install
```

Tras eso, tenemos varias opciones:

### Ver

Permite únicamente ver el proyecto en un servidor local

```
$ gulp
```
### Archivos de desarrollo

Permite exportar el proyecto para desarrollo. No incluye minificación, optimización ni servidor para ver los cambios

```
$ gulp dev
```

### Para trabajar día a día en el deesarrollo

Es la suma entre las dos anteriores. Nos permite ver los cambios en tiempo real y exporta el proyecto a medida que lo desarrollamos. Es el comando que más se utiliza y el que ejecutarás a diario para desarrollar tu proyecto.

Crea un servidor local con hot reloading y con opciones de vincular dispositivos externos, como el móvil para testear las diferentes vistas responsive.

```
$ gulp work
```

### Archivos de producción una vez concluido

Permite exportar el proyecto para producción. Incluye minificación y optimización de todos los archivos e imágenes. Todo queda listo para publicar.

```
$ gulp dist
```

## Conclusión

Espero que te guste y sea cómodo utilizar este entorno básico. Es un buen comienzo para comenzar a desarrollar proyectos con una estructura más profesional y organizada. ¡Ánimo!