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

## Trabajar en proyectos Open Source (pull request)

1. Hacer un fork del proyecto  del cual quiero contribuir
(me va a copiar en mi cuenta el repo del proyecto original)
2. Me clono el fork desde mi cuenta
3. Trabajo normalmente. Subo los cambios (A repo propio)
4. me voy al proyecto original en el apartado Pull Request. Creo un nuevo pull resequet.Algunas veces aparece en mi repo la posibilidad de pull request.
--- 
5. Si el repo original sufrió más modificaciones.(commits). Voy a tener que actualizar mi fork.
6. voy a la cuenta del proyecto original y me copio la url del repositorio
7. Y Agrego en mi repo local, la url (el remoto) del proyecto original

    git remote upstream <URL-repositorio-original>

8. Me traigo los cambios del repositorio original a mi repo local

    git pull upstream <rama-que-quiero-actualizar>

9. Subo a mi repo remoto (fork) las actualizaciones del repo local

    git push origin <rama-a-actualizar>

## Apuntadores

> Apuntadores Dinamicos

* HEAD

> Apuntadores estaticos

* Ramas (Locales y remotas)
* TAG
* STASH

## Tags

> Listar Tags

    git tag

> Crear tags
    git tag <nombre>
    git tag v1.1 

> Borrar tags

    git tag -d <nombre tag>
    git tag -d hasta-aca-todo-ok

> Crear tag co versionado semantica

    git tag -a v1.0.0 <hash> -m "Version 1.0.0"
    git tag -a v1.0.0 f473780
