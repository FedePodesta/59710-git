# Clase 04

## GIT CHERRY PICK

**IMPORTANTE:** Tengo que estar ubicado en la rama que espero traerme el o los commits.
    
    git cherry-pick<hash>

## GIT ALIAS 

### Para crear alias

git config --global alias.ll "log --oneline --decorate --all --graph"
git config --global alias.l "log --oneline"
git config --global alias.s "status --short"

## Para listar alias

    git config --get-regexp alias

## Para quitar un alias

    git config --global --unset alias.s