![git-andycarmo](https://user-images.githubusercontent.com/83571422/140892258-5303a3df-eff7-4d2f-a948-2123c5100dcc.jpg)

![](https://img.shields.io/github/license/Andycarmo/Git-Commands)  
Comandos Git - `Git Commands` - 
============

___

_Una lista de Comandos git_

### Creación - Clonación de proyecto - `Getting & Creating Projects`

| Command | Descripción |
| ------- | ----------- |
| `git init` | Inicializar un repositorio local de Git |
| `git clone https://git@github.com/[nombre de usuario]/[repositorio-nombre].git` | Crear una copia local de un repositorio remoto |

### Creación de proyecto local - Git Bash_

| Command | Descripción |
| ------- | ----------- |
| `cd desktop` | te ubicas en el escritorio |
| `ls` | listar lo que en la carpeta se encuentre |
| `pwd` | Da la ubicacion actual |

### Eliminar Untracked´s - `Cleaning & Delete`

| Command | Descripción |
| ------- | ----------- |
| `git clean -d` |  Listar los directorios que van a ser borrados. |
| `git clean -d -n` | Con la opción -n para listar todos los archivos y directorios no rastreados que van a ser borrados. |
| `git clean -d -f` | Eliminar todos los archivos y directorios no rastreados. |
| `git clean -f` |  Eliminar sólo los archivos no rastreados. |
| `git clean -d -i` |  Borrar los archivos y directorios no rastreados interactivamente. |
| `git clean -d -f -x` |  Eliminar todos los archivos y directorios no rastreados e ignorados. |
| `git clean -x` |  Eliminar sólo los archivos y directorios ignorados. |

### Instantáneas Básicas - `Basic Snapshotting` 

| Command | Descripción |
| ------- | ----------- |
| `git status` | Comprobar estado |
| `git add [file-name.txt]` | Añadir un archivo al área de ensayo |
| `git add -A` | Agregue todos los archivos nuevos y modificados al área de puesta en escena |
| `git commit -m "[mensaje de confirmación]"` | Commit cambios |
| `git commit -m 'merge commit'` | `master/MERGING` Reversion   |
| `git rm -r [file-name.txt]` | Eliminar un archivo (o carpeta) |

### Ramificación y Fusión - `Branching & Merging`

| Command | Descripción |
| ------- | ----------- |
| `git branch` | Listar todas las ramas presentes en el repositorio (el asterisco indica la rama actual) |
| `git branch -a` | Lista todos las ramas (local y remote) |
| `git branch [nombre de la rama]` | Crear un nueva rama |
| `git branch -d [nombre de la rama]` | Eliminar una rama |
| `git push origin --delete [nombre de la rama]` | Eliminar un branch remoto |
| `git checkout -b [nombre de la rama]` | Crear un nuevo branch y cambia a este |
| `git checkout -b [nombre de la rama] origin/[branch nombre]` | Clonar un branch remoto y cambia a este |
| `git branch -m [nombre viejo de la rama] [nombre nuevo de la rama]` | Renombrar a una rama local |
| `git checkout [nombre de la rama]` | Cambiar a una rama especifica |
| `git switch [nombre de la rama]` | Cambiar a una rama especifica |
| `git checkout -` | Cambiar a la ultima rama revisado |
| `git checkout -- [file-name.txt]` | Descartar cambios en un archivo |
| `git merge [nombre de la rama]` | Agrega los cambios de una rama dentro de la rama activa |
| `git merge [source branch] [target branch]` | Fusiona una rama dentro de otra rama |
| `git stash` | Guardar cambios en un directorio de trabajo sucio |
| `git stash clear` | Eliminar todas las entradas guardadas |

### Compartir y Actualizar proyectos - `Sharing & Updating Projects` 

| Command | Descripción |
| ------- | ----------- |
| `git push origin [branch name]` | Empujar un branch a un repositorio remoto |
| `git push -u origin [branch name]` | Empujar cambios a un repositorio remoto (y recordar el branch) |
| `git push` | Empujar cambiosa un repositorio remoto (branch recordado) |
| `git push origin --delete [branch name]` | Eliminar un branch remoto |
| `git pull` | Actualizar repositorio local al nuevo commit |
| `git pull origin [branch nombre]` | Jalar los cambios desde el repositorio remoto |
| `git remote -v` | Ver los repositorios remotos junto a sus URL´s |
| `git remote add origin <host-or-remoteURL>` | conectar el repositorio local a un servidor remoto |
| `git remote <nombre-del-repositorio>` | Borrar una conexión a un repositorio remoto especifico |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Añadir un repositorio remoto |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Establecer una rama de origen de un repositorio a SSH |

### Inspección y Comparación - `Inspection & Comparison` 

| Command | Descripción |
| ------- | ----------- |
| `git log` | Ver cambios |
| `git log --summary` | Ver cambios (detallado) |
| `git log --oneline` | Ver cambios (brevemente) |
| `git diff [source branch] [objetivo branch]` | Vista previa de cambios antes de fusionar |


### `Micellaneous`

| Command | Descripción |
| ------- | ----------- |
| `touch [nombre del archivo].[tipo de archivo (Ej .html)]` | Crear un archivo dentro del proyecto |
| `git reflog` | Muestra historial de actualizaciones en los extremos de las ramas. |

_Para mas info sobre Git Commands_ https://www.hostinger.co/tutoriales/comandos-de-git


git init 
