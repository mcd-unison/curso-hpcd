---
title: Actividades de aprendizaje
subtitle: Para la semana del 11 al 16 de abril
layout: page
show_sidebar: false
hide_hero: true
hide_footer: true
---

## La linea de comando de UNIX (CLI)

Para esta semana, vamos a realizar en forma autogestiva el curso de *Software Carpentry* sobre herramientas de UNIX, el cual se puede desarrollar [en ingles](http://swcarpentry.github.io/shell-novice/) o [en español](https://swcarpentry.github.io/shell-novice-es/)

[Aquí puedes descargar lo necesario](https://github.com/mcd-unison/curso-hpcd/raw/main/bash/imagen-docker.zip) para generar una imagen de *Docker* y crear un contenedor con todas las herramientas necesarias para el curso.

Para generar la imágen y el contenedor realiza lo siguiente   

1. Descomprime el archivo y lleva tu terminal de docker a ese directorio.
   
2. Ejecuta los siguientes comandos (no olvides poner el username tuyo): 
   ```bash
   $ docker build -t username/bash-curso .
   $ docker run --rm -it username/bash-curso
   ```

Recuerda que si quieres que sea persistente el contenedor tienes que crear un contenedor con nombre que no desaparezca al terminar. Algo así como
   
```bash
$ docker run -it --name bash-curso username/bash-curso
```

y cuando salgas y quieras regresar a continuar solo es necesario ejecutar:

```bash
$ docker start -at bash-curso
```

Buena suerte y que sea muy provechosa esta semana.





