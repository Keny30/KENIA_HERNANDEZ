Tarea Tecnicas de programacion git, Pasos:

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (main)
$ git add .

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (main)
$ git commit -m "Commit inicial"
[main (root-commit) e51854b] Commit inicial
 1 file changed, 11 insertions(+)
 create mode 100644 INDEX.html

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 360 bytes | 360.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Keny30/KENIA_HERNANDEZ.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (main)
$ git checkout -b Rama2 master
fatal: 'master' is not a commit and a branch 'Rama2' cannot be created from it

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (main)
$ git checkout -b master Rama2
fatal: 'Rama2' is not a commit and a branch 'master' cannot be created from it

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (main)
$ git checkout -b main Rama2
fatal: 'Rama2' is not a commit and a branch 'main' cannot be created from it

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (main)
$ git checkout -b Rama2 main
Switched to a new branch 'Rama2'

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (Rama2)
$ git status
On branch Rama2
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   INDEX.html

no changes added to commit (use "git add" and/or "git commit -a")

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (Rama2)
$ git add .

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (Rama2)
$ git commit -m
error: switch `m' requires a value

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (Rama2)
$ git commit -m "07/04/2024, KENIA, Nuevo comentario"
[Rama2 b2efe47] 07/04/2024, KENIA, Nuevo comentario
 1 file changed, 1 insertion(+), 1 deletion(-)

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (Rama2)
$ git status
On branch Rama2
nothing to commit, working tree clean

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (Rama2)
$ git push -u Rama2
fatal: 'Rama2' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (Rama2)
$ git push -u origin Rama2
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 338 bytes | 338.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Rama2' on GitHub by visiting:
remote:      https://github.com/Keny30/KENIA_HERNANDEZ/pull/new/Rama2
remote:
To https://github.com/Keny30/KENIA_HERNANDEZ.git
 * [new branch]      Rama2 -> Rama2
branch 'Rama2' set up to track 'origin/Rama2'.

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (Rama2)
$ git add .

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (Rama2)
$ git commit -m "07/04/2024, KENIA, Segundo Comentario"
[Rama2 534a65a] 07/04/2024, KENIA, Segundo Comentario
 1 file changed, 1 insertion(+)

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (Rama2)
$ git push -u origin Rama2
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 311 bytes | 311.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Keny30/KENIA_HERNANDEZ.git
   b2efe47..534a65a  Rama2 -> Rama2
branch 'Rama2' set up to track 'origin/Rama2'.

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (Rama2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (main)
$ git pull origin Rama2
From https://github.com/Keny30/KENIA_HERNANDEZ
 * branch            Rama2      -> FETCH_HEAD
Updating e51854b..534a65a
Fast-forward
 INDEX.html | 3 ++-
 1 file changed, 2 insertions(+), 1 deletion(-)

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (main)
$ git merge Rama2
Already up to date.

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (main)
$ git push -u origin main
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Keny30/KENIA_HERNANDEZ.git
   e51854b..534a65a  main -> main
branch 'main' set up to track 'origin/main'.

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (main)
$ git branch -d Rama2
Deleted branch Rama2 (was 534a65a).

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (main)
$ git branch
* main

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Comercial MPPCR@Gerencia-Logistica MINGW64 ~/Desktop/Tecnicas Programacion/KENIA_HERNANDEZ (main)
$ git push origin --delete Rama2
To https://github.com/Keny30/KENIA_HERNANDEZ.git
 - [deleted]         Rama2

