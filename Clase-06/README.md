# Clase 06


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