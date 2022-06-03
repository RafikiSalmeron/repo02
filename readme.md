# Ejercicio 2
## 2.1 Crea un repositorio llamado repo02 desde GitHub.
Vamos a Github y creamos el repositorio. 

## 2.2 Posteriormente, clónalo, añade un fichero reame.md y haz un commit.
Primero copiamos la ruta del repositorio que nos da GitHub (.git) y ejecutamos git clone -> ``` git clone https://github.com/USUARIO/repo02.git ```  
Añadimos el fichero readme.md -> ``` touch readme.md ```  
Y realizamos el commit y el push de igual forma que en el ejercicio 1 
```
git add . 
git commit -m "Añado el fichero readme.md"
git push
```

## 2.3 Resumen de comandos git
|Comando |Función |
|:---- | ----:|
|git status| Nos permite ver en que situación área de trabajo se encuentran nuestros ficheros.|
|git add| Nos permite añadir los cambios a ña staging area.|
|git rm --cached| Nos permite sacar un fichero nuevo de la staging area.|
|git restore --staged| Nos permite descartar los cambios de un fichero existente de la staging area.|
|git commit| Nos permite realizar el envío de los cambios al repositorio local, es decir "Guardar los cambios" en el repositorio local.|
|git log | Nos permite visualizar un historial de commits.|
|git push | Nos permite subir todos los cambios (commits) al repositorio remoto.|
|git pull | Nos permite bajar todos los cambios del repositorio remoto al local.|
|git remote add |Nos permite asociar nuestro repositorio local a un repositorio remoto.|
|git remote -v |Nos permite ver que repositorios tenemos asociados para comprobar el flujo.|
|git branch | Nos permite situarnos en distintas ramas.|
|git clone | Nos permite clonar un repositorio remoto para trabajar con él.|
