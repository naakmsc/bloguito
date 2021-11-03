# Mi Bloguito.com :tw-1f48e:

Este es un proyecto para aprender git con github.

###Aprendido:

- Inicializar un proyecto local con `git init`
- Verificar cambios con `git status`
- Agregar seguimiento a los archivos con `git add (archivo) o (.) `
- Guardar cambios en git con `git commit -m ""`
- Verificar la rama con `git branch`
- Crear una rama `git branch (fix-code)`
- Borrando ramas `git branch -D (fix-code)`
- Cambiar de rama con `git checkout (rama)`
- Hacer un reset del proyecto a un commit anterior sin borrar los que esta espera`git reset (hash) --soft`
- Hacer un reset duro del proyecto borrando cualquier cambio en espera `git reset (hash) --hard`
- Traer actualizacion de github `git pull origin main`
- Enviar cambios a github `git push origin main`
- Ignorar archivos con un archivo llamado `.gitignore`
- Clonar repositiorios con `git clone (url repositorio)`
- Agregar mis datos de usuario a git `git config --global -user.name "Nombre"` `git config --global -user.email "Correo"`
- Haciendo Rebase `git rebase (main)` luego ` git rebase (fix-ghost)`
- Crear Alias `alias vista="git log --all --graph --decorate --online"`
- Utilizar stash para guardar un cambio sin hacerle commit `git stash`
- Revisar los stash guardados `git stash list`
- Borrar los stash `git stash drop`
- Enviar los stash a una rama nueva `git stash branch (nombre-rama)`
- Recuperar el stash guardado `git stash pop`
- Limpiar de archivos que no son necesarios del proyecto `git clean` 
- Dejar claro que se va a borrar sin borrarlo aun `git clean --dry-run`
- Borrar definitivamente archivos no necesarios `git clean -f`
- Usando Cherry para traer commits de otras ramas `git cherry-pick (codigo)`
- Usando Tags para ponerle version a los commits `git tag -a v1.0 "Mensaje del tag" (hash del commit)`
- Ver los tags desde git `git tag`
- Ver los tags con mas informacion `git show-ref --tags`
- Ver todos los cambios por un grandisimo error `git reflog`
- Añadir un cambio olvidado a un commit sin hacer otro `git commit --amend`
- Buscar algo en especifico `git grep (nombre)` con la linea `git grep -n (nombre)`
- Buscar un texto en especifico en los commits `git log -S "nombre"`


**Table of Contents**

[TOCM]

[TOC]

##Nos vemos



