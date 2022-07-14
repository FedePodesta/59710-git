# Clase 01

## COMANDO DE CONSOLA BÁSICOS

* ls: Listar Directorios
* cd: Cambiar de directorio

    cd <directorio>
    cd Clase-01

* cd .. : Salgo de un directorio
* touch : Creo archivos vacios

    touch <nombre-archivo>
    touch archivo1.txt archivos2.txt

* mkdir : Creo Directorios
    mkdir <nombre-directorio>
    mkdir dir1 dir2 dir3

* rm: Borrar archivos
    rm <archivo-a-borrar>
    rm index.html

* rmdir
    rmdir <directorio-a-borrar>
    rmdir dir1

* clear

    Limpia la consola

### GIT

> Saber si tengo git instalado

    git --version

> Configuracion imporante de git (primera vez y unica)
GLOBAL:para todos los repo que se creen en el equipo


    git config --global user.name "Usuario"
    git config --global user.email ""correo@gmail.com"

    

> Inicializar repositorio git (crear repositorio)

    git init

> Configuracion de repositorio con un usuario y mail diferente
LOCAL : Configura usuario y mail para el repositorio actual
    git config --global user.name "Usuario"
    git config --global user.email "correo@gmail.com"

