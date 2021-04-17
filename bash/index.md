---
layout: default
title: Herramientas de UNIX
subtitle: y la belleza del CLI
hero_image: /curso-hpcd/img/linuxbanner.jpg
hero_darken: true
hide_footer: true
---

1. Curso de *Software Carpentry* sobre herramientas de UNIX [en ingles](http://swcarpentry.github.io/shell-novice/) y [en español](https://swcarpentry.github.io/shell-novice-es/)

2. [Aquí puedes descargar lo necesario](https://github.com/mcd-unison/curso-hpcd/raw/main/bash/imagen-docker.zip) para generar una imagen de *Docker* y crear un contenedor con los datos necesarios para el curso de *Software Carpentry*.   
   1. Descomprime el archivo y lleva tu terminal de docker a ese directorio.
   
   2. Ejecuta los siguientes comandos (no olvides poner el username tuyo): 
      ```bash
      $ docker build -t username/bash-curso .
      $ docker run --rm -it username/bash-curso
      ```
      Recuerda que si quieres que sea persistente el contenedor tienes que crear un contenedor con nombre que no desaparezca al terminar.

3. [No necesitas una GUI](https://github.com/you-dont-need/You-Dont-Need-GUI)
4. [Data Science at the command line](https://www.datascienceatthecommandline.com)
5. [Uso común de `curl`](https://curl.se/docs/manual.html)
6. [Pequeño tutorial de `sed`](https://www.grymoire.com/Unix/Sed.html)
7. [Un tutorial no tan malo como la mayoría de `awk`](https://www.tutorialspoint.com/awk/index.htm)
8. [El paquete de funciones `csvkit`](https://csvkit.readthedocs.io/en/latest/)
