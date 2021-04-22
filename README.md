# comandoGit
Curso de creación de empresas donde exponemos todos los comandos que permite git y para que sirve.

•	git init
o	Inicia git desde el proyecto en donde están ubicados
•	git clone
o	Clonar el repositorio desde bitbucket a la computadora local, o servidor
o	Para clonar una rama específica de un repositorio, escriba --branch <branch name> antes de la url del repositorio:
git clone --branch branch name url 
•	 git restore
o	Restablece cambios realizados anteriormente
•	 git log
o	Muestra las acciones realizadas
•	 git config
o	Con este comando pueden ver las configuraciones de git y o configurar ciertas cosas, depende de cada uno.
•	 git fetch
o	Trae las ramas hechas
•	 git add .
o	Agrega a la cola, los archivos editados
•	 git status
o	Muestra el estado de los archivos, si está en rojo los archivos no están agregados en la cola, si están en verde los archivos están agregados en cola y listos para realizar el commit.
•	 git commit -m 'mensaje'
o	Confirma los archivos a subir, MENSAJE BIEN DETALLADO
•	 git push origin nombredelarama
o	Envia los cambios a la rama correspondiente
•	 git pull origin nombredelarama
o	Trae los cambios hechos en alguna rama  o master
•	git branch
o	Muestra la rama en la se está
•	 git checkout nombredelarama
o	 se cambia a esa rama
•	 git checkout -b nombredelarama
o	Crea una rama nueva y se cambia a esa rama
•	Si hubiese un conflicto hacer lo siguiente:
o	Se hace un "git pull origin master o developer" en la rama de cada uno
o	Arreglar los conflictos que muestra, ya sea aceptar ambos o uno de los dos
o	Y añadir los cambios, hacer el commit, y el push. 

