# GIT-GITHUB: Ejercitación Final

## Repositorio devjumpers
```
1. Creé un repositorio con el nombre "devjumpers" en GitHub y copié su enlace.
2. Cloné el repositorio en la terminal con el comando "git clone https://github.com/Cristian550/devjumpers.git"
```
## README 
```
3. Usé el comando "cd devjumpers" para moverme al repositorio local.
4. Creé el documento README.md con el comando "touch README.md"
```
## Commit inical
```
5. Documenté todos lo pasos y comandos utilizados hasta el momento en el "README.md"
6. Usé los comandos "git add ." y "git commit -m "commit inicial"" para guardar los cambios y prepararlos para subirlos al repositorio remoto.
```
## Push inicial
```
7. Subí los cambios al repositorio remoto con el comando "git push".
```
## Ignorar archivos
```
8. Creé un fichero llamado "privado.txt" y una carpeta llamada "privada" con los comandos "touch privado.txt" y "mkdir privada".
9. Creé el archivo .gitignore con el comando "touch .gitignore" y escribí en el: "/privado.txt" y "/privada", para que git los ignore.  
```
## Añadir fichero 1.txt
```
10. Añadí un archivo con el nombre "1.txt" al repositorio con el comando "touch 1.txt"
```
## Crear una rama v0.2
```
11. Creé una rama llamadada "v0.2" con el comado "git branch v0.2" y luego usé "git checkout v0.2" para posicionarme en esa rama.
```
## Añadir fichero 2.txt
```
12. Añadí un archivo "2.txt" en la rama v0.2
```
## Crear rama remota v0.2
```
13. Usé los comandos "git add ." y "git commit -m "rama v0.2 y 2.txt creados"" para guardar los cambios y prepararlos para subirlos al repositorio remoto.
14. usé "git push" pero ocurrió un error, para resolverlo usé otro comando "git push --set-upstream origin v0.2" para crear una rama en el repositorio remoto y poder pushear los cambios correctamente.
```
## Merge directo
```
15. Usé los comandos "git add ." y "git commit -m "cambios en el README.md"" para guardar los cambios que hice en el README.md.
16. Cambié a la rama master con el comando "git checkout main" e hice un merge de la rama v0.2 en el main correctamente.
```
## Merge con conflicto
```
17. Escribí "hola" en el 1.txt y usé "git add ." y "git commit -m "se escribió hola en 1.txt""
18. Cambié a la rama v0.2 y escribí "adios" en el 1.txt, luego usé "git add ." y "git commit -m "se escribió adios en 1.txt""
19. Me posicioné en el main con "git checkout main", usé "git add ." y "git commit -m "más cambios en el README.md"" para guardar los cambios que hice en el README.md.
20. Hice merge con "git merge v0.2" y apareció un conflicto.
```
## Listado de ramas
```
21. Hice un "git branch --merged" para listar las ramas con merge y un "git brach --no-merged" para las ramas sin merge.
``` 
## Arreglar conflicto
```
22. Arreglé el conflicto quedándome con ambos textos y re-organizándolos, después usé el "git add." y "git commit -m "conflictos resueltos"" para luego pushear con "git push". 
```
## Borrar rama
```
23. Borré la rama v0.2 con el comando "git branch -D v0.2".
```
## Listado de cambios
```
24. Listé los commits con sus ramas y tags con el comando "git log --oneline --decorate --all --graph":
*   918d11b (HEAD -> main, origin/main) conflictos resueltos
|\
| * 48d989f se escribió adios en 1.txt
* | 58134b5 más cambios en en README.md
* | 200e992 se escribió hola en 1.txt
* | c4486b6 merge directo
|/
* 205d7b9 cambios en el README.md
* 624d3b9 (origin/v0.2) rama v0.2 y 2.txt creados
* d0c99ac privado.txt, privada, .gitignore y 1.txt añadidos
* 4ce6d1d commit inicial
```
## Cuenta de GITHUB
* Me puse una foto de perfil y activé el factor de autentificación.

## Uso social de GITHUB
* Seguí a mis compañeros de clase y sus repositorios, también les dí una estrella.

## Crear una tabla
* Realicé una tabla con la información de mis compañeros de clase:

|NOMBRE         |GITHUB         |
|-----------    |-----------    |
|Enzo Franco    |[EnzoFranco31](https://github.com/EnzoFranco31)    |
|Alejo Paiva    |[BLUHD823](https://github.com/BLUHD823)    |
|Geraldine Montufar |[Geraldine1997](https://github.com/Geraldine1997)  |
|Franco Formigo |[francobenjaminformigo](https://github.com/francobenjaminformigo)  |
|Maria Artega    |[maryjse](https://github.com/maryjse)  |

## Colaboradores
* Colaborador: Enzo Franco.