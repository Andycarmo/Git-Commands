![git-andycarmo](https://user-images.githubusercontent.com/83571422/140892258-5303a3df-eff7-4d2f-a948-2123c5100dcc.jpg)


Git Commands - Comandos Git
============

___

_Una lista de Comandos git_

### Getting & Creating Projects - (Obtención y creación de proyectos)

| Command | Descripción |
| ------- | ----------- |
| `git init` | Inicializar un repositorio local de Git |
| `git clone https://git@github.com/[nombre de usuario]/[repositorio-nombre].git` | Crear una copia local de un repositorio remoto |

### Basic Snapshotting - (Instantáneas básicas)

| Command | Descripción |
| ------- | ----------- |
| `git status` | Comprobar estado |
| `git add [file-name.txt]` | Añadir un archivo al área de ensayo |
| `git add -A` | Agregue todos los archivos nuevos y modificados al área de puesta en escena |
| `git commit -m "[mensaje de confirmación]"` | Commit cambios |
| `git commit -m 'merge commit'` | `master/MERGING` Reversion   |
| `git rm -r [file-name.txt]` | Eliminar un archivo (o carpeta) |

### Branching & Merging - (Ramificación y fusión)

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
| `git checkout -` | Cambiar a la ultima rama revisado |
| `git checkout -- [file-name.txt]` | Descartar cambios en un archivo |
| `git merge [nombre de la rama]` | Fusiona una rama dentro de la rama activa |
| `git merge [source branch] [target branch]` | Fusiona una rama dentro de otra rama |
| `git stash` | Guardar cambios en un directorio de trabajo sucio |
| `git stash clear` | Eliminar todas las entradas guardadas |

### Sharing & Updating Projects - Compartir y actualizar proyectos

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

### Inspection & Comparison - Inspección y comparación

| Command | Descripción |
| ------- | ----------- |
| `git log` | Ver cambios |
| `git log --summary` | Ver cambios (detallado) |
| `git log --oneline` | Ver cambios (brevemente) |
| `git diff [source branch] [objetivo branch]` | Vista previa de cambios antes de fusionar |

_Para mas info sobre Git Commands_ https://www.hostinger.co/tutoriales/comandos-de-git
