Utilizo "git clone" para clonar el repositorio local.


Utilizo "cd devjumpers" para poder entrar al repositorio.


Utilizo "touch README.md" para poder crear un documento llamado README.md


Para agregar los cambios use "git add".


Seguido a esto, use el "git commit -m "commit inicial" " y el "git push" para poder subir estos cambios al repositorio remoto.


Pasando a la parte de ignorar archivos, use "touch privado.txt" para poder crear un archivo con el nombre de "privado.txt" y "mkdir privada" para poder crear una carpeta con el nombre privado.


Con "touch .gitignore" cree un archivo con nombre ".gitignore"


Creo un fichero con "touch 1.txt".


Pasando a la parte de ramas, creo una nueva rama y me posiciono en ella usando "git checkout -b "v0.2" "


Utilizo "touch 2.txt" para crear un fichero en la rama.


Utilizo un "git add . ", "git commit -m " "creacion de .gitignore , cracion de archivo 1.txt, creacion de branch, creacion de archivo 2.txt"" y "git push" para poder subir los cambios al repositorio remoto.


Me salta un error y utilizo "git push --set-upstream origin v0.2"


Utilizo "git checkout main" para volver a la rama principal.


Utilizo "git merge v0.2" para unificar las ramas.


Modifico el archivo "1.txt" agregando un "Hola" y agregando un "commit -m "escribo hola en 1.txt" "


Utilizo "git checkout v0.2" para moverme a la rama.


Utilizo un "git add". y luego pongo un "Adios en el archivo 1.txt". Agrega un "git commit -m "escribo adios en 1.txt"


Utilizo "git checkout main" para volver a la rama principal.


Utilizo "git merge v0.2" donde me encontré con el conflicto.


Con "git branch --merged" vi que ramas se fusionaron y también utilice "git branch --no-merged" que muestra que ramas no se fusionaron.


Después utilice un "git add". y un "git commit -m "conflicto solucionado"


Con "git branch -D v0.2" borre la rama v0.2


Cambios: git log --oneline --decorate --all --graph
* ce17901 (HEAD -> principal) conflicto solucionado
|\
| * 6d22391 escribo adios en 1.txt
* | a92ce98 escribo hola en 1.txt
|/
* 5ce8002 (origin/v0.2) creación de .gitignore, creación de archivo 1.txt, creación de branch, creación de archivo 2.txt
* 4770459 (origen/principal) compromiso inicial
