# Clase 04

## GIT CHERRY PICK

**IMPORTANTE:** Tengo que estar ubicado en la rama que espero traerme el o los commits.
    
    git cherry-pick<hash>¨
    git cherry -pick <hash1> <has2> <has3>
    git cherry-pick <hash>^..<hash> #Todos los commits incluidos en el rango y además los extremos
     git cherry-pick <hash>..<hash> # Solo me trae los que estan entre esos 2 commits, no las puntas

### SI tengo varios commits, no uno. Voy a tener que hacer 

    git cherry-pick --continue


### Para Abortar el proceso de cherry. picking

    git cherry-pick --abort

## GIT ALIAS 

### Para crear alias

git config --global alias.ll "log --oneline --decorate --all --graph"
git config --global alias.l "log --oneline"
git config --global alias.s "status --short"

## Para listar alias

    git config --get-regexp alias

## Para quitar un alias

    git config --global --unset alias.s

## GIT STASH
Es construido basado en una estructura de datos conocida como pila.

> ¿Qué me permite el stash?

Me permite registrar temporalmente los cambios del working directory y el stagin AREA.

¿Puedo subir al remoto los stash?

NO. solo estan en el repositorio local.No se pueden subir al remoto.


### Crear un stash

    git stash

### Listar los Stash

    git stash list

### Recuperar un stash

**NOTA:** si el stash que estoy tratando de recuperar genera un conflicto con mi codigo, o sea con el codigo que esta en repositorio directory. Me va a dejar en la caja de stash que estoy sacando. Si no hay conflictos, borra el stash.


### Borrar el ultimo stash

    git stash drop
    git stash drop stash @{4}


### Si quiero aplicar un stash particular ( Sol oaplica, no borra lo aplicado)

    git stash apply stash@{4}
    git stash apply stash@{2}

### Si quiero aplicar un stash en una rama nueva.

    git stash branch <rama-a-aplicar-stash>


## Versiones DESKTOP

* Git Kraken: hhtps://www.gitkraken.com/

*Github Desktop : https://desktop.github.com


## Buenas prácticas para generar mensajes de commits

https://medium.com/@jmz12/buenas-pr%c3%a1cticas-para-comits-5eb4c86b9a47