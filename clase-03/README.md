# Clase 03

## GIT RAMAS (BRANCHS)

>Crear una rama
    git branch <nombre-rama>

> Moverme entre ramas

    git switch <nombre-rama>
    git switch dev

> Para Ver las ramas

    git branch
> Para borrar una rama

    git branch -d <nombre-rama>
    git branch -d dev

> Para forzar el borrado de una ramas
recuerden que ester flag me sirve para confirmar el borrado de una rama que no fue fusionada con ninguna otra.

    git branch -D <nombre-rama>
    git branch D dev

## GIT MERGE (fusiones)
combinar losc ambios de una rama con otra. Normalmente en un nuevo commit
**IMPORTANTE:** tengo que estar en la rama que espero traerme los cambios. O sea que si quiero traerme los cambios de dev a master tengo que estar sobre la rama master y ejecutar el siguiente comando

    git merge <nombre-rama>
    git merge dev
### --------------- ###
### Tipos de Fusiones / MERGE
### --------------- ###

* Fast-Forward(Union automatica. Git no necesita de la asistencia del usuario)

* Recursivo (Union automatica). Tampoco hay conflictos.

* Manual (Conflictos) Ocurre cuando hay modificaciones en las mismas lineas de un archivo o varios archivos

### -------------------------