1. ¿Cómo se inicializa un repositorio local? (que comando se debe ejecutar?)
La manera de inicializar un repositorio local es con el comando git init.

2. ¿Cómo hago para que un directorio deje de ser controlado por git? (que comando se debe ejecutar?)
Para que un directorio deje de ser controlado por git utlizamos el comando git rm.

3. Si agrego un archivo a un directorio que ya está siendo controlado por git, ¿está siendo controlado por git?
Si agrego un archivo a un directorio que está siendo controlado por git, el archivo también está controlado.

4. ¿Qué comando se utiliza para agregar un archivo al repositorio local?
Se usa el comando git add.

5. ¿Cómo determino que archivos fueron modificados? (que comando se debe ejecutar?)
Lo determino con el comando git status.

6. ¿Qué comando se utiliza para hacer un commit?
Para hacer un commit se usa el comando git commit -m "Comentario".
 
7. En sus propias palabras, ¿qué es un commit?
Un commit es una parte para poder guardar cambios en un archivo del repositorio.

Practica

1.2.3 
On branch juanmartin_lagomarsino
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   sandwich.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        juanmartin_lagomarsino.txt

no changes added to commit (use "git add" and/or "git commit -a")

En este mensaje nos muestra que el archivo sandwich.txt ya fue commiteado previamente, pero desde ese momento fue modificado. Por otro lado, nos muestra que hay un nuevo archivo llamado "juanmartin_lagomarsino.txt".

4.5
On branch juanmartin_lagomarsino
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   sandwich.txt

Luego de ejecutar el comando paso a estar en staging, en vez de modified.


6.7
Luego de escribir el comando, solo muestra el archivo "juanmartin_lagomarsino.txt".
 
9.
Author: Juan Martin Lagomarsino <JMLagomarsino@mail.austral.edu.ar>
Date:   Tue Jun 13 19:39:01 2023 -0300

    Agrego salsas

commit 8015e49cc0e35d6daea43e4dbc862832a07a5ee1
Author: Juan Martin Lagomarsino <JMLagomarsino@mail.austral.edu.ar>
Date:   Tue Jun 13 19:32:06 2023 -0300

    Agrego mi sandwich.txt

commit 178991498e1fefa1ef54177b45849671b8392331
Author: Juan Martin Lagomarsino <JMLagomarsino@mail.austral.edu.ar>
Date:   Tue Jun 13 19:24:06 2023 -0300

    Agrego mi sandwich.txt

commit cfa26c73c64c4f6172e85d81bd6a1736200bdbc7
Author: Juan Martin Lagomarsino <JMLagomarsino@mail.austral.edu.ar>
Date:   Thu May 4 13:47:16 2023 -0300

    Agrego mi sandwich.txt

commit 579a34f2db78787d6f499242919e873d7a447480 (origin/main, origin/HEAD, main)
Author: Sebastian Iglesias <sebiglesias@users.noreply.github.com>
Date:   Wed Apr 19 17:27:00 2023 -0300

    Agrego instrucciones para instalar claves ssh en windows con git bash.

commit 786904f65d58dafd7c392efdc806cd91ba0cbb01
Author: Sebastian Iglesias <sebastian@getcaribou.com>
Date:   Mon Apr 17 21:58:56 2023 -0300

    Initial commit - repo setup

commit 140733d1b371966335eace561a02d3464af47664
Author: Sebastian Iglesias <sebiglesias@users.noreply.github.com>
Date:   Mon Apr 17 20:02:55 2023 -0300

    Initial commit
Nos muestra el historial de commits del más antiguo al mas actual.

10.
git log --oneline : Nos muestra una version abreviada del historial.
git log --stat : Nos muestra información estadistica de los cambios.

11. 
con git diff comparo los archivos y las diferencias de las palabra entre uno y otro

14.
Aparece sandwich2_feo.txt como modificado y no aparece el sanwich2.txt creado y modificado originariamente.

15.
En el git status vemos que el archivo sandwich2_feo.txt esta borrado y no se lo ve más, y en el git log --oneline observamos que aparece el comentario con el que hicimos commit para guardar el cambio de borrar el archivo sandwich2_feo.txt.

16.
Muestra un resumen estadístico de los cambios realizados en cada confirmación (commit) en la rama actual.
