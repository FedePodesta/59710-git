# Clase 05

## GIT RESET


### GIT Reset soft
Elimine los commits que seleccione pero la info se guardo en el stagin area o index para poder commitearla despues

    git reset soft <hash>


### GIT Reset mixed
Elimine los commits que seleccione pero la info se guarda en el working directory

    git reset <hash>
    git reset --mixed

### GIT Reset Hard() <-- PELIGROSO
Por que pierdo lo que tenai dentro de los commits.

    git reset --hard <hash> 