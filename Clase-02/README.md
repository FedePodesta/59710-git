## Clase 02

### Agregar un Remoto

### Agregar remoto

    git remote add origin <URL>
    git remote add origin hhtps://github.com/cuentausuario/51234-git.git

### Verificar los remotos

    git remote
    git remote -v

### Para subir el repo local al remoto

    git push -u origin master

## GITIGNORE
ME permite descargar archivos y carpetas que no quiero subir

## GITKEEP
Me permite mantener y versionar carpetas vacías.

## GIT COMMIT

### PARA HACER UN COMMIT

    git commit - m "Mensaje"

### PAra hacer un git add y un git commit en simultaneo
Los archivos que quiero hacer commit deben estar un seguimiento. si los archivos no estan en seguimiento (o Sea) no untraked,no me los va a agregar al git add.

    git commit -am "Mensaje"


### Para enmendar un commit 
Agrego los archivos que me olvidé
    git add .clase-02/cualquiera.md
y luego hago el amend

    git commit --amend


## Status de archivos

* UNTRACKED: Archivos que nos e agregaron al index (staging area) o sea archivos que estan en el working directory (WD)

* Unmodified: Son Archivos que ya estan en el repositorio. Osea que ya tienen una foto.

* Modified: Son archivos que ya estan en el repositorio pero respecto al working directory tienen modificaciones detectadas por git. O sea compara la foto del repositorio con el WD.

* Staged: Archivos que estan confirmados para ser un proximo comit.




