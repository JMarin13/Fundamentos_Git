# Fundamentos de Git
Primeros comandos de git

### git init
Creación de repositorio local

### git config --global user.name "nombreUsuario"
Definir el nombre del usuario que va a interactuar con git desde el PC

### git config --global user.email "correoUsuario"
Definir el correo del usuario que va a interactuar con git desde el PC

### git status
Revisar el estado del repositorio local

### git add nombreArchivo
Añadir los cambios a stage de un archivo determinado

### git add .
Añadir los cambios a stage de todos los archivos modificados

### git commit -m "mensaje del commit"
Añadir los cambios de stage a pendientes por subir a GitHub

### git log
Visualizar todos los commits realizados a detalle

### git log --oneline
Visualizar todos los commits realizados resumidos

### git checkout codigoCommit
Cambiarme a una rama temporal para visualizar el código de algún commit específico

### git switch nombreRama
Cambiarme a una rama en específico

### git checkout nombreRama
Cambiarme a una rama en específico y crearla si no existe

### git restore --staged nombreArchivo
Retroceder los cambios de un archivo específico que está en stage

### git restore nombreArchivo
Retroceder los cambios de un archivo específico que está modificado sin stage

### git mv nombreViejo nombreNuevo
Renombrar un archivo

### git rm nombreArchivo
Eliminar un archivo