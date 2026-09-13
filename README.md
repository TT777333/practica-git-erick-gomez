##### ***Erick Emmanuel Gómez Elizalde - 2630260***

# Creación y sincronización de repositorios con Git y GitHub

> Crear un repositorio local utilizando Git, sincronizarlo con un repositorio remoto en GitHub y comprobar el flujo
de trabajo en ambos sentidos

# Descripción del procedimiento realizado

Se abrio powershell, se busco un lugar donde hacer el projecto (`ls`,`cd`)se hizo una carpeta 
(`mkdir practica-git-erick-gomez`), se inicializo git (`git init`), se creo el archivo
*datos.txt* (`ni datos.txt`), se le agrego texto (`ac datos.txt "mi cuarto repositorio git"`),
se movio a staging (`git add .`), despues a DB git con un commit (`git commit -m "El primer commit"`),
se creo un repositorio en GitHub, se conecto el repositorio remoto al local 
(`git remote add origin git@github.com:TT777333/practica-git-erick-gomez.git`), se envio el
repositorio local a GitHub (`git push -u origin main`), se hicieron cambios desde GitHub, se descargaron
dichos cambios (`git pull origin main`), se hicieron cambios desde el repositorio local,
(`ac .\datos.txt "Este archivo fue modificado desde el repositorio local, en powershell!"`)
se guardaron (`git add .`, `git commit -m "Actualizacion desde el repositorio local"`) y se enviaron
al repositorio remoto (`git push`) y finalmente se creo este archivo *README.md* (en markdown viewer).

---

Se uso:

`git init` : Inicializa el repositorio git

`git branch -M main` : Crea una rama

`git status	` : Muestra archivos en untracked files o staging, ademas de cambios a commit

`git add .` : Mueve todos los archivos en untracked files a staging

`git commit -m` : Crea un commit con un mensaje personalizado

`git remote add origin` : Vincula un repositorio remoto especificado

`git remote -v` : Muestra los repositorios vinculados

`git push` : Envia los archivos en commit a el repositorio remoto vinculado de GitHub

`git pull origin main` : Integra los cambios del repositorio remoto al repositorio local

---

# Creación y vinculación de repositorios

El repositorio local se creo al inicializar git en la carpeta practica-git-erick-gomez con
`git init`

El repositorio local se vinculo a GitHub mediante el comando `git remote add  origin git@github.com:TT777333/practica-git-erick-gomez.git`

# Sincronización

La sincronización Local -> GitHub sirve de manera que se hacen cambios de manera local y luego se publican al
repositorio vinculado mediante el comando git push

La sincronización GitHub -> Local sirve de manera que se hacen cambios de manera remota y luego se extraen del
repositorio remoto al repositorio local mediante el comando git pull

---

## datos.txt
archivo de prueba para git add, commit y edicion de archivos desde git.

## README.md

archivo de descripcion de lo hecho y aprendido

---

# Conclusión

Me percato de un agujero en mi busqueda previa de comandos de git y repaso de temas, viendo que me olvide de los
comandos git remote y apenas descubri el comando git remote -v en esta actividad.

Ahora me esta mas claro el proceso de creacion, vinculacion y gestion de repositorios git, ademas de que necesito
memorizar, practicar y usar los comandos un poco mas.