Git Commands - Comandos Git
============

___

_Una lista de Comandos git_

### Getting & Creating Projects - (Obtención y creación de proyectos)

| Command | Descripción |
| ------- | ----------- |
| `git init` | Inicializar un repositorio local de Git |
| `git clone ssh://git@github.com/[nombre de usuario]/[repositorio-nombre].git` | Crear una copia local de un repositorio remoto |

### Basic Snapshotting - (Instantáneas básicas)

| Command | Descripción |
| ------- | ----------- |
| `git status` | Comprobar estado |
| `git add [file-name.txt]` | Añadir un archivo al área de ensayo |
| `git add -A` | Agregue todos los archivos nuevos y modificados al área de puesta en escena |
| `git commit -m "[mensaje de confirmación]"` | Commit cambios |
| `git rm -r [file-name.txt]` | Eliminar un archivo (o carpeta) |

### Branching & Merging - (Ramificación y fusión)

| Command | Descripción |
| ------- | ----------- |
| `git branch` | Lista de branches (el asterisco indica el actual branch) |
| `git branch -a` | Lista todos los branches (local and remote) |
| `git branch [branch nombre]` | Crear un nuevo branch |
| `git branch -d [branch nombre]` | Eliminar un branch |
| `git push origin --delete [branch nombre]` | Eliminar un branch remoto |
| `git checkout -b [branch nombre]` | Crear un nuevo branch y cambia a este |
| `git checkout -b [branch nombre] origin/[branch nombre]` | Clonar un branch remoto y cambia a este |
| `git branch -m [old branch nombre] [nuevo nombre branch]` | Rename a local branch |
| `git checkout [branch nombre]` | Cambiar a un branch |
| `git checkout -` | Cambie al ultimo branch revisado |
| `git checkout -- [file-name.txt]` | Descartar cambios en un archivo |
| `git merge [branch nombre]` | Merge a un branch dentro del branch activo |
| `git merge [source branch] [target branch]` | Merge a branch into a target branch |
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
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Añadir un repositorio remoto |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Establecer una rama de origen de un repositorio a SSH |

### Inspection & Comparison - Inspección y comparación

| Command | Descripción |
| ------- | ----------- |
| `git log` | Ver cambios |
| `git log --summary` | Ver cambios (detallado) |
| `git log --oneline` | Ver cambios (brevemente) |
| `git diff [source branch] [objetivo branch]` | Vista previa de cambios antes de fusionar |
