

##CONFIGURACION INICIAL GLOBAL GIT

#git config --global user.name "nombre usuario"
#git config --global user.email "email usuario"
#git config --list : Para ver si las configuariones globales
#git checkout : para deshacer cambios en nuestro espacio de trabajo
#git checkout -f : para deshacer cambios forsozamente en nuestro espacio de trabajo
#git checkout 'hash del commit' : permite ir a ese commit (viajar al pasado)
#git checkout master : permite regresar al commit master (volver al presente)

GIT LOG MAS FUNCIONES
#git log --raw : Muestra lo que se modifico en cada historico de commit
#git log --summary: Muestra informacion mas condensada
#git log --oneline: Informacion condensada (hash resumido y mensaje)
#git log --oneline -n 2: Cantidad de commit que quiero ver en una linea
#git log --prety=format:"El autor del commit %h fue %an"
#git log --oneline --all: muestra toda la informacion
#git log --oneline --all --graph: Agrega puntos a las ramas para identificar

RAMAS
#git checkout -b 'nombre rama': Crear una nueva rama en el head que nos encontramos
#git branch: Muestra todas las ramas existentes
#git branch -D 'nombre rama': Elimina la rama


#MERGE
#git merge 'nombre de la rama':


#SUBIR A LA NUBE
#git push: empujar archivos a la nube
#git remote -v: Muestra las opciones para hacer fetch (jalar) y push (subir)
#git fetch 'nombre carpeta en la nube': sincroniza el log de la nube con el local
#git pull 'origen' 'rama': agrega lo traido por el fetch al area de trabajo

#ELIMINA RAMAS EN LA NUBE
#git push --delete origin 'nombre rama': para eliminar la rama en la nube