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