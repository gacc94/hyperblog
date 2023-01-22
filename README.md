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

Mostrar historial de cambios en un arhcivo `git show miArchivo`

Mostrar cambios entre commits `git diff codigoHash1 codigoHAash2`

![Imagen de estados de git](/assets/estados-git-0acb84f7-5080-4098-99d9-59012a3b8e86-e5b46dbb-9bab-4d7c-aa74-c055ffcde639.webp)
 
volver en el tiempo en nuestro repositorio (--hard = )`git reset codigoHash  --hard`

ver cambios iniciales de cualquier commit `git checkout codigoHash miArchivo`

regresar a la rama master `git checkout master miArchivo`
