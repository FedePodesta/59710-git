# Clase 06
Fecha 01/08/2022


## Programas para gestionar los repos 

* Github desktop
    https://desktop.github.com

* Git Kraken
    https://www.gitkraken.com

## Repositorios en la nube

* Github
     https://www.github.com
* GitLab
    https://about.gitlab.com

* Git Fork
    https://git-fork.com

* SOurce tree app

    https://sosurcetreeapp.com

* esto es un ejemplo

    https://sourcetreeapp.com

    
## GIT REBASE

Integra los cambios e la rama **master** en una nueva rama **rebase** que le faltan los comits que en **master** ahora están.

        git rebase <rama-que-me-quiero-traer>
        git rebase master

Una Vez solucionados los conflictos con

    git add

continuo  el rebase con 

    git rebase --continue


## GIT ADD (CONTINUACION)

    git add --patch


Y : Para confirmar el hunk (pedacito codigo)
N : Para descartar el hunk (Pedacito codigo)

## Git REBASE  INTERACTIVO (AVANZADO)

### para que sirve?

* ordenar commits
* corregir mensajes de los commits
* unir commits
* separar commits
```sh
    git rebase -i <hash> #Inmediato inferior a lo que quiero seleccionar
```
Una vez seleccionados los commits tengo que seguir los pasos que me dice git.

>r, reword: Cambiar el mensaje del commit
>s, squash: Nos permite fusionar commits.


## GIT PAGES



