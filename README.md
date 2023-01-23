# Curso de GIT

Imagen de Obtenida de Platzi:...
![Inicial](./assets/Que_es_Git-8f5b6780-47b4-4ff7-9a8a-6fdec5a0f1af.webp)
## Configuracion de git

Lista de configuracion `git config`

Configurar git desde editor de codigo `git config --global -e`

configuracion global user`git config --global user.name "Gusatavo Caqui"`

configuracion global email`git config --global user.email "gustavo@gmail.com"`

Listar configuracion `git config --list`

## Comandos Iniciales

inicializar seguimiento del directorio `git init`

añadir un archivo `git add miArchivo`

retirar del estado add (--cached = retirar del almacemanimto)`git rm --cached miArchivo`

Mostrar todo el historial de git `git log`

Mostrar el historial de git con el espacion en memoria ocupado `git log --stat `

Mostrar historial de cambios en un arhcivo `git show miArchivo`

Mostrar cambios entre commits `git diff codigoHash1 codigoHAash2`

![Imagen de estados de git](/assets/estados-git-0acb84f7-5080-4098-99d9-59012a3b8e86-e5b46dbb-9bab-4d7c-aa74-c055ffcde639.webp)
 
volver en el tiempo en nuestro repositorio (--hard = )`git reset codigoHash  --hard`

ver cambios iniciales de cualquier commit `git checkout codigoHash miArchivo`

regresar a la rama master `git checkout master miArchivo`

## Clonar Repositorio

Crea una copia en local con todos los cambios realizados en ese 
proyecto `git clone url`


## Ramas

Realizar un merge / Unir ramas / es un commit `git merge ramaHijas`

Crear una rama `git branch NombreRama`

Dirigirse a una rama `git checkout NombreRama`

## Comienzos en Github

Añande el repsoitorio en remoto mendiante
http(s) `git remote add origin https://github.com/gacc94/hyperblog.git`

Verificar los comandos de forma verbal al acceso 
remoto `git remote -v`

Cambiar de nombre de manera obligatoria para subir a remoto
el repositorio de master a main `git branch -M main`

Enviar al origen que es el repositorio remoto creado la rama master 
`git push -u origin main`


# Configuracion KEY SSH

configurar 
llave ssh `ssh-keygen -t -rsa -b 4096 -C "gustavocaqui94@gmail.com"`
passphrase `gacc94`

Establecer origin con ssh
`git regit remote set-url origin git@github.com:gacc94/hyperblog.git`



