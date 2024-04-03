EJERCICIO

Nota 1: Escribe cada comando que usaste.

Nota 2: Agregar un log.txt con lo hecho en el repositorio (usar git --no-pager log).

1. Crea tu primer repositorio en un directorio llamado git-workshop
2. Crea los archivos tuNombre.txt y musica.txt. Actualmente los archivos no requieren
tener contenido.
3. Agrega esos dos archivos al staging área y realiza el primer commit del repo.
4. Crea la rama yo++ y cámbiate a esa rama. Ahora que estás en la rama yo++, escriba
una o dos oraciones acerca de ti en el archivo .txt con tu nombre. Cuando hayas
concluido de redactar, agrega tus cambios al staging área y realiza un commit.
5. Ahora regresa al primer commit del repo usando git checkout master. Crea otra
rama: taller-info, y cámbiate a la rama. En el musica.txt, escribe una o dos oraciones
acerca de alguna música, agrega los cambios al staging área y realiza un commit.
6. Colócate en la rama master, e incorpora los cambios de yo++ a master mediante un
merge. Si existe algún conflicto intenta resolverlo.
7. Crea un repositorio público en GitHub, con el nombre <tu-nombre>-intro-git, p. ej.
pablo-intro-git.
8. Empuja los cambios de tu rama master a GitHub, para que los demás también
puedan ver tu repo.
9. Baja los archivos a una nueva carpeta en tu computadora (local)



PROCEDIMIENTO

1) Creé una carpeta llamada "git-workshop" e inicialicé el repositorio local corriendo el comando "git init" en la consola de GIT Bash.
2) Con el comando "touch" creé los archivos "arion.txt" y "musica.txt".
3) Tras ejecutar el comando "git add ." agregué ambos archivos txt al área de preparación. Confirmé los cambios hechos a través de un "git commit".
4) Generé un repositorio remoto público en GitHub y con "git remote add origin <url>" lo vinculé a mi proyecto local. Pushee los cambios en "Master" hasta el momento.
5) Desde "Master" generé la rama "yo++", en ella redacté un pequeño párrafo introductorio en el archivo "arion.txt", y para terminar corrí nuevamente los comandos "git add ." y "git commit". Pushee los cambios en "yo++" hasta el momento.
6) Otra vez desde "Master" generé otra rama: "taller-info"; ahí redacté un breve texto sobre música en el archivo "musica.txt", y corrí los comandos "git add ." y "git commit". Pushee los cambios en "taller-info" hasta el momento.
7) De vuelta en "Master", realicé un merge entre "Master" y "yo++". Finalicé el proyecto pusheando dicho merge en "Master".



COMANDOS USADOS (EN NINGÚN ORDEN EN PARTICULAR)

1) mkdir git-workshop
2) touch [archivo]
3) code .
4) git --no-pager log
5) git status
6) git init
7) git add .
8) git commit -m "[comentario]"
9) git merge [rama]
10) git branch [rama]
11) git checkout [rama]
12) git push -u origin [rama]
13) git remote add origin [url]
