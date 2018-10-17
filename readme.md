# Proyecto 1 
## Miriam GitHub

## Paso 1 - Crear repositorio
Creación carpeta en documetos (local ordenador) <br> 
    también se puede a través de: <br> 
      $ git mkdir ______ <br> 
Iniciar el repositorio de esa carpeta (estando en la carpeta) <br> 
$ git init <br> 


## Paso 2 - Crear archivos 
Crear el archivo readme.md desde visual code <br> 
$ code /.Proyecto_1 <br> 

## Paso 3 - Guardar cambios
Añadir y guardar los cambios en el terminal <br> 
$ git status             *(comprobar los cambios que faltan por guardado)* <br> 
$ git add readme.md     <br> 
$git commit-am readme.md <br> 

## Paso 4 - Enlazar terminal con github
Enlazar git en el terminal con github <br> 
Crear repositorio en github <br> 
$ git remote add origin https://github.com/miriammg/Proyecto_1.git <br> 
$ git push -u origin master <br> 


## Paso 5 - Creación branch
Crear una nueva branch "rama2" <br> 
$ git checkout -b rama2 <br> 

## Paso 6 - Modificaciones en branch
Realizar modificaciones a traves de visual code  <br> 
*modificar lineas de readme.md (ya escritas) **important**   <br> 
*crear una nueva carpeta <br> 
*.. <br> 
$ git code ./___ <br> 
    *cambios* <br>  
$ git status <br> 
$ git add _____         (todos archivos)  <br>  
$ git commit "   " <br> 

## Paso 7 - Subir a Github
Subir todo a github <br> 
$ git push origin _____ (NOMBRE DE LA RAMA EN LA QUE ESTAS) <br> 

## Paso 8 
Volver a rama master <br> 
$ git checkout ____ <br> 

## Paso 9 - Merge
Hacer merge <br>  
$ git merge _____ (rama que deseas importar (no exportar)) <br> 


## Paso 10 - Conflito y resolución
Conflicto - <br> 
Conflicto en readme.md <br>  
Abrir readme.md con visual code <br> 
$ cat readme.md <br>  
Modificar en visual code (muy fácil opciones) <br> 

## Paso 11 - GUARDAR 
Guardar los cambios realizados en visual code
$ git status <br> 
$ git add <br> 
$ git commit -am "" <br>  
$ git push origin master   **important** <br> 


![Captura Network](Shot_Proyecto_1.png)

