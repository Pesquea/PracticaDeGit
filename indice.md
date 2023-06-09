Capítulo 1: Introducción a Git (conceptos y configuraciones)
Git es un sistema de control de versiones distribuido creado por Linus Torvalds.

Un sistema de control de versiones nos permite guardar el historial de cambios de nuestros proyectos y trabajar con otros colaboradores en un mismo proyecto.

El concepto más importante de git es el repositorio. Un repositorio es una carpeta que va a almacenar todo el historial de cambios de un proyecto.

Para crear un repositorio ejecuta el comando git init sobre la carpeta de tu proyecto. Eso va a crear una carpeta oculta llamada .git.

El historial de cambios se crea a partir de commits. Un commit es una fotografía de tu proyecto en un momento determinado.

Para ver el estado del repositorio utiliza el comando git status

Capítulo 2: Flujo de trabajo básico
Capítulo 3: Gestion de rama
git branch: crea una rama
git checkout <nombre de la rama>: moverse a la rama seleccionada.
git checkout -b "<nombre de la rama>: crear una rama y moverse a la rama nueva.
git branch -d <nombre de la rama>: borra la rama seleccionada.
git status: Muestra las caracteristicas de la rama principal.
git merge <nombre de la rama>: Fusionar la rama con la rama main
Capitulo 4. Repositorios remotos
 git remote add: Agregar repositorio nuevo
 git add: crea un archivo o adiciona cambios a uno en el directorio de trabajo de git
 git commit: guarda cambios realizados en el area de preparación

