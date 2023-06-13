# RepoExamen

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (produccion)
$ git branch
  checkout
  main
* produccion
  recurso_humano
  ventas

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (produccion)
$ git branch -D checkout
Deleted branch checkout (was 3d788c8).

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (produccion)
$ git branch
  main
* produccion
  recurso_humano
  ventas

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (produccion)
$ git init
Reinitialized existing Git repository in D:/Documentos/RepoExamen/.git/

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (produccion)
$ git add materiaprima.txt

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (produccion)
$ git add productofinal.txt

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (produccion)
$ git add produccion.jpg

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (produccion)
$ git commit -m "modifique produccion"
[produccion f568546] modifique produccion
 6 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 materiaprima.txt
 create mode 100644 produccion.jpg
 create mode 100644 produccion/casa.jpg
 create mode 100644 produccion/materiaprima.txt
 create mode 100644 produccion/productofinal.txt
 create mode 100644 productofinal.txt

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (produccion)
$ git push origin produccion
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 8.29 KiB | 565.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/brayangallegos7/RepoExamen.git
   3d788c8..f568546  produccion -> produccion

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (produccion)
$ git checkout ventas
Switched to branch 'ventas'

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (ventas)
$ git init
Reinitialized existing Git repository in D:/Documentos/RepoExamen/.git/

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (ventas)
$ git add tiendas.txt

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (ventas)
$ git commit -m "modifique ventas"
[ventas 790387d] modifique ventas
 1 file changed, 3 insertions(+)
 create mode 100644 tiendas.txt

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (ventas)
$ git push origin ventas
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 326 bytes | 65.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'ventas' on GitHub by visiting:
remote:      https://github.com/brayangallegos7/RepoExamen/pull/new/ventas
remote:
To https://github.com/brayangallegos7/RepoExamen.git
 * [new branch]      ventas -> ventas

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (ventas)
$ git checkout

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (ventas)
$ git checkout recurso_humano
Switched to branch 'recurso_humano'

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$ git init
Reinitialized existing Git repository in D:/Documentos/RepoExamen/.git/

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$ git add empleados.txt

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$ git commit -m "modifique recursos humanos"
[recurso_humano 0a92a9e] modifique recursos humanos
 1 file changed, 5 insertions(+)
 create mode 100644 empleados.txt

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$ git push origin recurso_humano
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 358 bytes | 59.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'recurso_humano' on GitHub by visiting:
remote:      https://github.com/brayangallegos7/RepoExamen/pull/new/recurso_humano
remote:
To https://github.com/brayangallegos7/RepoExamen.git
 * [new branch]      recurso_humano -> recurso_humano

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$ git checkout master
error: pathspec 'master' did not match any file(s) known to git

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (main)
$ git merge produccion
Updating 3d788c8..f568546
Fast-forward
 materiaprima.txt             |   0
 produccion.jpg               | Bin 0 -> 8100 bytes
 produccion/casa.jpg          | Bin 0 -> 8100 bytes
 produccion/materiaprima.txt  |   0
 produccion/productofinal.txt |   0
 productofinal.txt            |   0
 6 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 materiaprima.txt
 create mode 100644 produccion.jpg
 create mode 100644 produccion/casa.jpg
 create mode 100644 produccion/materiaprima.txt
 create mode 100644 produccion/productofinal.txt
 create mode 100644 productofinal.txt

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (main)
$ git push origin main 
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/brayangallegos7/RepoExamen.git
   3d788c8..f568546  main -> main

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (main)
$ git add .

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (main)
$ git commit -m "modifique main"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (main)
$ git push origin main 
Everything up-to-date

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (main)
$ git checkout recurso_humano
Switched to branch 'recurso_humano'

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$ git status
On branch recurso_humano
nothing to commit, working tree clean

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$ git add .

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$ git commit -m "agregue 5 empleados"
[recurso_humano cc07ca4] agregue 5 empleados
 1 file changed, 5 insertions(+)

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$ git push origin recurso_humano
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 391 bytes | 65.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/brayangallegos7/RepoExamen.git
   0a92a9e..cc07ca4  recurso_humano -> recurso_humano

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$ git log
commit cc07ca435436c2fe46706d379fd823fd6812569a (HEAD -> recurso_humano, origin/recurso_humano)
Author: brayangallegos7 <gallegosestrada.07@gmail.com>
Date:   Mon Jun 12 17:00:22 2023 -0700

    agregue 5 empleados

commit 0a92a9ea438403cd62cf39ce1a07962d35aa86ef
Author: brayangallegos7 <gallegosestrada.07@gmail.com>
Date:   Mon Jun 12 16:56:02 2023 -0700

    modifique recursos humanos

commit 3d788c8797fa0731a83830637d04450a29b2b829
Author: brayangallegos7 <gallegosestrada.07@gmail.com>
Date:   Mon Jun 12 16:39:20 2023 -0700

    first commit

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$ git log oneline
fatal: ambiguous argument 'oneline': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$ git log -oneline
fatal: unrecognized argument: -oneline

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (main)
$ git merge recurso_humano
Merge made by the 'ort' strategy.
 empleados.txt | 10 ++++++++++
 1 file changed, 10 insertions(+)
 create mode 100644 empleados.txt

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (main)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (main)
$ git add .

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (main)
$ git commit -m "hice merge de recursos humanos a main"
On branch main
Your branch is ahead of 'origin/main' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (main)
$ git push origin main 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 312 bytes | 62.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/brayangallegos7/RepoExamen.git
   f568546..a316644  main -> main

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (main)
$ git checkout ventas
Switched to branch 'ventas'

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (ventas)
$ git add .

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (ventas)
$ git commit -m "agregue 2 tiendas"
[ventas eaa97bc] agregue 2 tiendas
 1 file changed, 3 insertions(+), 1 deletion(-)

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (ventas)
$ git push origin ventas
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 341 bytes | 42.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/brayangallegos7/RepoExamen.git
   790387d..eaa97bc  ventas -> ventas

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (ventas)
$ git checkout recurso_humanos
error: pathspec 'recurso_humanos' did not match any file(s) known to git

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (ventas)
$ git checkout recurso_humano
Switched to branch 'recurso_humano'

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$ git add .

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$ git commit -m "agregue fotos empleados"
[recurso_humano 2e0ae34] agregue fotos empleados
 5 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 fotos_empleados/cocina.jpg
 create mode 100644 fotos_empleados/comedor.jpg
 create mode 100644 fotos_empleados/descarga (1).jpg
 create mode 100644 fotos_empleados/descarga.jpg
 create mode 100644 fotos_empleados/produccion.jpg

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$ git push origin recurso_humano
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 42.40 KiB | 1.09 MiB/s, done.
Total 8 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/brayangallegos7/RepoExamen.git
   cc07ca4..2e0ae34  recurso_humano -> recurso_humano

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$ git add .

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$ git commit -m "agregue sueldo empleados"
[recurso_humano 38f958c] agregue sueldo empleados
 1 file changed, 4 insertions(+)
 create mode 100644 sueldos.txt

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$ git push origin recurso_humano
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 336 bytes | 33.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/brayangallegos7/RepoExamen.git
   2e0ae34..38f958c  recurso_humano -> recurso_humano

braya@GallegosPC MINGW64 /d/Documentos/RepoExamen (recurso_humano)
$
