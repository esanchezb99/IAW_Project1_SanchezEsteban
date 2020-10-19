# Comandos para git 

##### Configuración del sistema git 

- Configuramos el nombre para que se sepa quien ha hecho los commit `git config --global user.name "nombre del usuario"`

  

- Configuramos el correo electrónico para que se guarde y no tengamos que ponerlo cada vez que subamos los cambios `git config --global user.email "correo electronico"`

  

##### Iniciar el repositorio

- Iniciamos el repositorio git `git init`
- Lista los archivos y directorios agregados y modificados `git status`
- Muestra los cambios en los archivos creados `git diff` 
- Muestra el historial de commits de la sesión `git log` 
- Añadimos el archivo o los archivos al commit `git add "nombre del archivo"` se añadirán todos si cambiamos el nombre por `.`
- Hacer un commit `git commit -m "Descripción de los cambios "`
- Subimos el repositorio online con los cambios que hemos hecho `git push origin master`
- Para poder actualizar el repositorio con los cambios nuevos al repositorio local  `git pull`
- Creamos una rama de trabajo `git branch "Nombre"`
  - Listamos las ramas `git branch`
- Para poder cambiar de rama `git checkout "Rama"`
- Unir una rama actual con la especificada `git merge "Rama"`

















- Clonar un repositorio `git clone "url"` 


