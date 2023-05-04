Parte teorica
1.1.1 se usa el comando "git init"
1.1.2 se usa el comando "git rm -r" (nombre del directorio)
1.1.3 Si
1.1.4 se usa el comando "git add" (nombre del archivo)
1.1.5 se usa el comando "git status"
1.1.6 se usa el comando "git commit" (nombre del archivo)
1.1.7 un commit es una forma de guardar unos cambios hechos, es como una captura de pantalla de los cambios.
Parte Practica
1.2.3 
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   sandwich.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Eliseo_Alanis.txt

no changes added to commit (use "git add" and/or "git commit -a")
Explicacion: veo que sandwich.txt esta modificado ya fue comiteado antes y hay un nuevo arhcivo Eliseo_Alanis.txt que nunca fue agregado a git
1.2.5 luego de hacer el comando el archivo paso a estar en staging en vez de modified
1.2.7 Ahora ya no aparece el archivo sandwich.txt en el git status, porque se comiteo y se subio al repositorio
1.2.9 
commit 6a87964efdb1750d770c36062babda1f64352f30 (HEAD -> main)
Author: Eliseo <ealanistoledo@mail.austral.edu.ar>
Date:   Wed May 3 19:21:43 2023 -0300

    Agrego salsas

commit 725fd4c2acb8c0380c4050932d17702c1c2aaac6
Author: Eliseo <ealanistoledo@mail.austral.edu.ar>
Date:   Wed May 3 19:14:05 2023 -0300

    Agrego mi sandwich.txt

commit 579a34f2db78787d6f499242919e873d7a447480 (origin/main, origin/HEAD)
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
Explicacion: aparecen todos los commits que hice cada uno con su codigo unico, y se ordenan desde el mas reciente(Arriba) al mas antiguo (abajo)
1.2.10.1 en git log --oneline, observo lo mismo que en git log pero mas simplificado, su codigo que antes era largo ahora se encuentra recortado 
1.2.10.2 con este nuevo gt log nos muestra una version mas amplia que el git log normal, con la cantidad de cambios que se hicieron.
1.2.11 aparecen en verde los cambios agregados a los archivos y en rojo los ingredientes borrados.
1.2.14 no cambio nada porque como comitie el archivo no aparece ningun cambio en "git status" pero si lo hace en el "git log"
1.2.15 ahora cuando hacemos git status aparece "sandwich_feo.txt" como borrado del repositorio pero con git log --oneline sigue apareciendo guardado el commit con el archivo antes de que se borre
1.2.16 aparecen todos los commits que se hicieron. Tambien aparecen los commits de los archivos q se eliminaron

