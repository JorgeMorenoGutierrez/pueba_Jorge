# EJERCICIO 1 introducion a GIT Y GITHUB.
#### paso1:
Lo  primero que haremos sera crear un nuevo repositorio en local, esto lo haremos creando un nuevo directorio y haciendo un git init estando posicionado dentro del directorio. 
![captura iniciando el git](/Imágenes/cap1iaw.png)  
Una vez iniciado creamos dos archivos de texto dentro del repositorio  
![captura de los archivos dentro del repositorio](/Imágenes/cap2iaw.png)
#### paso2: 
ahora **subimos** el repositorio a nuestro github esto lo haremos con el comando **git remote add origin https://nombre de usuario:token@github.com/JorgeMorenoGutierrez/prueba2_Jorge.git** y **git push -u origin master**  
![captura de los comandos para sincronizar los repositorios](/Imágenes/cap3iaw.png)
#### paso3:
ahora subimos el contenido con el comando **git push**
![captura subiendo los archivos](/Imágenes/cap4iaw.png)  
#### paso4:  
Ahora desde una maquina virtual lo clonaremos esto lo haremos con el comando **git clone https://USERNAME:TOKEN@github.com/USERNAME/REPO.git**
![captura clonando el repositorio apoyandonos de una conexion ssh](/Imágenes/cap6iaw.png)   
en este caso estoy utilizando una conexion ssh para que me resulte mas facil copiar los comando y el token.  
#### paso5:  
ahora desde nuestra maquina real cambiaremos los ficheros, añadiremos un nuevo fichero y subiremos los cambios con el camino tipico de github **git add . git commit -m y git push.**
![captura creando un archivo nuevo](/Imágenes/cap7iaw.png)  
![captura modificando un archivo ya creado](/Imágenes/cap8iaw.png)  
![captura demostrando el estado antes de empezar a subir las cosas](/Imágenes/cap9iaw.png)  
![captura del aspecto del repositorio antes de los cambios](/Imágenes/cap10iaw.png)  
![captura de los comandos necesarios para subir las cosas](/Imágenes/cap11iaw.png)  
se me ha olvidado el **git add .**
![captura del repositorio despues del cambio](/Imágenes/cap12iaw.png)  
#### paso 5:
ahora volveremos a **sincronizar** el repositorio que clonamos en la maquina virtual con el **git hub**
![captura del apecto del repositorio antes del pull](/Imágenes/capt13iaw.png)  
ahora hacemos un **git pull**.
![captura del apecto del repositorio antes del pull](/Imágenes/cap14.png)  
con esto ya habremos terminado la primera parte de esta tarea.
