# EJERCICIO 3 iTrabajando con ramas y uniones.
#### paso1:  
lo primereo que tengo que hacer es crear una nueva rama llamada primera para ello usamos el comando **git branch primera**  
![captura donde se ve como se crea una rama](imagenes/cap3.2.png)  
##### paso2:  
ahora nos **moveremos** a la nueva rama con **git checkout**  
![captura donde me muevo de rama](imagenes/cap3.1.png) 
ahora creamo un nuevo documento que solamene este en esta rama  
![captura donde creo un nuevo documento en la rama primera y no esta en la rama main](imagenes/cap3.3.png)  
ahora fusionamos ambas ramas con el comando **git merge primera** estando situados en la rama main  
![captura donde junto las dos ramas](imagenes/cap3.4.png)  
#### paso3:  
en este paso borraremos la rama **primera**  
![captura donde elimino la rama primera](imagenes/cap3.5.png)  
#### paso4:  
creo una nueva rama y me muevo a ella
![captura donde creo una nueva rama y me muevo a ella](imagenes/cap3.6.png)  
ahora desde la nueva rama modificamos un archivo ya creado para crear conflicto, nos aseguraremos que ambas ramas esten cerrados con commit.
![captura donde junto las dos ramas](imagenes/cap3.7.png)  
asi nos aseguraremos que cuando hagamos el merge nos de un conflicto
![captura donde se ve el conflicto](imagenes/cap3.8.png)  
#### paso5:
En el ultimo paso nos encargaremos de arreglar el conflcito en el docmento que se nos a abierto borraremos la parte que no queramos guadrdar.  
![captura donde junto las dos ramas](imagenes/cap3.9.png)  
despues que lo arreglamos nos movemos a la rama segunda y lo subimos al repositorio remoto.
![captura donde junto las dos ramas](imagenes/cap3.10.png)  