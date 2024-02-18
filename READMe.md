# Curso de _Git_ y _GitHub_ 

Este es el parrafo de prueba

Agregando contenido adicional

Tercer parrafo de prueba 

## Comandos para _Git_ 

- **git comando -h**: para obtener ayuda
- **git add .**
- **git commit -m "mensaje"**
- **git push**
- **git branch _nombre-rama_**: Crear una rama
- **git branch --no-merged**: lista ramas no fusionadas en la rama actual
- **git branch --merged**: Lista rams fusionadas en la rama actual
- **git checkout _nombre-rama_**: Cambiar de rama
- **git checkout -b _rama_** : Crear rama y cambiarte a ella
- **git branch**: Para ver las ramas
- **git branch -d _rama_**: para eliminar la _rama_ localmente
- **git push origin --delete _rama_** : para eliminar las rama en GitHub
- **git merge _rama_**: Unir ramas(fast-forward)
- ***.log:** En el archivo ignore se pone para que se ignoren todos los archivos de ese tipo
- **git clone _url.git_** : Para clonar repositorios
- **git log** : Para mostrar el historial de commits o cambios con sus ids
- **git log --oneline** : mostrar los commits en una sola linea
- **git commit --amend --no-edit** : Para hacer un ligero cambio al último commit sin hacer otro(incluir el add .)
- **git commit --amend -m "new message"** : Para hacer un cambio al ultimo commit y un cambio al comentario
- **git reset --hard HEAD~1** : Elimina el último commit
- **git log > commits.txt** : Para creaar un archivo con el historial de commits
- **git log --oneline --graph --all** : muestra una grafica conel historial de cambios, ramas y fusiones
- **git reflog** : Muestra todo el historial, incluyendo cambios, elminaciones, fusiones
- **git diff** : Muesta las diferencias entre el directorio de trabajo y el staging
- **git status** : Nos muestra el listado de archivos nuevos 
- **git reset --mixed** : Borra el head y staging regraasando al  modificado
- **git reste --hard** : Borra todo: head, stagin y el modificado o working directory
- **git reset id-commit** : Deshace todos los cambios despues del commit indicad, preservando los cambios localmente
- **git reset --hard id-commit** : Desecha todo el historial y regresa al commit especificado
- **git tag** : para modificar la version despues del git add ., se pone git add v1.0.3


