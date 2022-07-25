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


### Crear un stash

    git stash

### Listar los Stash

    git stash list

### Recuperar un stash

**NOTA:** si el stash que estoy tratando de recuperar genera un conflicto con mi codigo, o sea con el codigo que esta en el working directory. Me va a dejar en la caja de stash el stash. Si no hay conflictos, borra el stash.
