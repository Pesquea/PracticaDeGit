Capítulo 1: Introducción a Git (conceptos y configuraciones)
Git es un sistema de control de versiones distribuido creado por Linus Torvalds.

Un sistema de control de versiones nos permite guardar el historial de cambios de nuestros proyectos y trabajar con otros colaboradores en un mismo proyecto.

El concepto más importante de git es el repositorio. Un repositorio es una carpeta que va a almacenar todo el historial de cambios de un proyecto.

Para crear un repositorio ejecuta el comando git init sobre la carpeta de tu proyecto. Eso va a crear una carpeta oculta llamada .git.

El historial de cambios se crea a partir de commits. Un commit es una fotografía de tu proyecto en un momento determinado.

Para ver el estado del repositorio utiliza el comando git status

Capítulo 2: Flujo de trabajo básico

Hay tres áreas principales: el directorio de trabajo, el área de preparación (o stage) y el repositorio.

Directorio de trabajo: Es el lugar donde trabajamos en los archivos. Aquí es donde se realizan modificaciones, se agregan archivos nuevos o eliminan archivos existentes.

Área de preparación (Stage): Después de hacer modificaciones en los archivos, deben agregarse al área de preparación antes de confirmar los cambios. Esto se hace utilizando el comando "git add". El área de preparación es como un área intermedia donde se seleccionan los cambios que se desean incluir en la próxima confirmación.

Repositorio: Es donde Git almacena el historial completo de tu proyecto, incluyendo todas las versiones anteriores. Después de agregar los cambios al área de preparación, pueden ser confirmados al repositorio utilizando el comando "git commit". Cada confirmación tiene un mensaje asociado que describe los cambios realizados.

El flujo de trabajo básico sigue estos pasos:

Inicializar un repositorio: Se puede iniciar un repositorio Git en el directorio de trabajo utilizando el comando "git init".

Realizar cambios: Trabajar en los archivos, realizar modificaciones, agregar nuevos archivos o eliminar archivos existentes.

Agregar cambios al área de preparación: Se utiliza el comando "git add" para agregar los cambios al área de preparación. Se puede especificar archivos específicos o agregar todos los cambios con "git add ." (punto).

Confirmar los cambios: Se utiliza el comando "git commit" para confirmar los cambios del área de preparación al repositorio. Se incluye un mensaje descriptivo para cada confirmación.

Repetir los pasos 2-4: Se continúa trabajando en los archivos, repitiendo los pasos de realizar cambios, agregar al área de preparación y confirmar los cambios según sea necesario.

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

