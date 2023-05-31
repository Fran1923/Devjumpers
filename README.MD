Arbusta@N-429 MINGW64 ~/Desktop
$ mkdir "ejercicio_final_Git_hub"

Arbusta@N-429 MINGW64 ~/Desktop
$ CD "ejercicio_final_Git_hub"
bash: CD: command not found

Arbusta@N-429 MINGW64 ~/Desktop
$ cd "ejercicio_final_Git"
bash: cd: ejercicio_final_Git: No such file or directory

Arbusta@N-429 MINGW64 ~/Desktop
$ cd: "ejercicio_final_Git_hub"
bash: cd:: command not found

Arbusta@N-429 MINGW64 ~/Desktop
$ cd "ejercicio_final_Git_hub"

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub
$ git clone https://github.com/Fran1923/Devjumpers.git
Cloning into 'Devjumpers'...
warning: You appear to have cloned an empty repository.

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub
$ touch README.md

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub
$ cd "Devjumpers"

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ touch README.MD

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ ls
README.MD

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ status
bash: status: command not found

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.MD

nothing added to commit but untracked files present (use "git add" to track)

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git init
Reinitialized existing Git repository in C:/Users/Arbusta/Desktop/ejercicio_final_Git_hub/Devjumpers/.git/

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git add .

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.MD


Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git push
error: src refspec refs/heads/main does not match any
error: failed to push some refs to 'https://github.com/Fran1923/Devjumpers.git'

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git commit -m "se crea repositorio y se agrega la carpeta README.md"
[main (root-commit) 940ae4f] se crea repositorio y se agrega la carpeta README.md
 1 file changed, 34 insertions(+)
 create mode 100644 README.MD

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git push
remote: Permission to Fran1923/Devjumpers.git denied to fabramoff.
fatal: unable to access 'https://github.com/Fran1923/Devjumpers.git/': The requested URL returned error: 403

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ Git config --global user.name "Fran1923"

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ ls
README.MD

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git push
remote: Permission to Fran1923/Devjumpers.git denied to fabramoff.
fatal: unable to access 'https://github.com/Fran1923/Devjumpers.git/': The requested URL returned error: 403

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git clone https://github.com/Fran1923/Devjumpers.git
Cloning into 'Devjumpers'...
warning: You appear to have cloned an empty repository.

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git push -u origin main
remote: Permission to Fran1923/Devjumpers.git denied to fabramoff.
fatal: unable to access 'https://github.com/Fran1923/Devjumpers.git/': The requested URL returned error: 403

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ ^C

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git push -u origin main
remote: Permission to Fran1923/Devjumpers.git denied to fabramoff.
fatal: unable to access 'https://github.com/Fran1923/Devjumpers.git/': The requested URL returned error: 403

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git push -u origin main
remote: Permission to Fran1923/Devjumpers.git denied to fabramoff.
fatal: unable to access 'https://github.com/Fran1923/Devjumpers.git/': The requested URL returned error: 403

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 534 bytes | 534.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Fran1923/Devjumpers.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$




Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ ls
README.MD  privada/  privado.txt

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git add .

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git add privada

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        new file:   privado.txt


Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git commit -m "Se agrega carpeta Privada y archivo Privado.txt"
[main acef316] Se agrega carpeta Privada y archivo Privado.txt
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 .gitignore
 create mode 100644 privado.txt

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git add .

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git commit -m "Se ignoran los archivos y la carpeta privada"
[main 6bef6b5] Se ignoran los archivos y la carpeta privada
 1 file changed, 2 insertions(+)

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 650 bytes | 650.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Fran1923/Devjumpers.git
   5a7d5f1..6bef6b5  main -> main

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ touch 1.txt

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git checkout -b v0.2
Switched to a new branch 'v0.2'

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (v0.2)
$ touch 2.txt

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (v0.2)
$ git add .

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (v0.2)
$ git commit -m "Se crea rama y los ficheros 1 y 2.txt"
[v0.2 b84b847] Se crea rama y los ficheros 1 y 2.txt
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 1.txt
 create mode 100644 2.txt

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (v0.2)
$ git push -u origin v0.2
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 334 bytes | 334.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'v0.2' on GitHub by visiting:
remote:      https://github.com/Fran1923/Devjumpers/pull/new/v0.2
remote:
To https://github.com/Fran1923/Devjumpers.git
 * [new branch]      v0.2 -> v0.2
branch 'v0.2' set up to track 'origin/v0.2'.

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (v0.2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git merge v0.2
Updating 6bef6b5..b84b847
Fast-forward
 1.txt | 0
 2.txt | 0
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 1.txt
 create mode 100644 2.txt

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Fran1923/Devjumpers.git
   6bef6b5..b84b847  main -> main

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git add .

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git commit -m "Se agrega comentarios archivo 1"
[main 43a4b72] Se agrega comentarios archivo 1
 1 file changed, 1 insertion(+)

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git checkout v0.2
Switched to branch 'v0.2'
Your branch is up to date with 'origin/v0.2'.

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (v0.2)
$ git add .

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (v0.2)
$ git commit -m "Se agrega comentarios archivo 1"
[v0.2 42aa081] Se agrega comentarios archivo 1
 1 file changed, 1 insertion(+)

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (v0.2)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git merge v0.2
Auto-merging 1.txt
CONFLICT (content): Merge conflict in 1.txt
Automatic merge failed; fix conflicts and then commit the result.

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main|MERGING)
$ git branch --merge
* main

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main|MERGING)
$ git branch --no-merge
  v0.2

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main|MERGING)
$ git add .

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main|MERGING)
$ git commit -m "Conflicto resuelto"
[main 37aa9b3] Conflicto resuelto

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git merge
Already up to date.

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git push
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 8 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (9/9), 700 bytes | 700.00 KiB/s, done.
Total 9 (delta 4), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), completed with 1 local object.
To https://github.com/Fran1923/Devjumpers.git
   b84b847..37aa9b3  main -> main

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git branch -D v0.2
Deleted branch v0.2 (was 42aa081).

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git log --oneline --decorate --all --graph
*   37aa9b3 (HEAD -> main, origin/main) Conflicto resuelto
|\
| * 42aa081 Se agrega comentarios archivo 1
* | 43a4b72 Se agrega comentarios archivo 1
|/
* b84b847 (origin/v0.2) Se crea rama y los ficheros 1 y 2.txt
* 6bef6b5 Se ignoran los archivos y la carpeta privada
* acef316 Se agrega carpeta Privada y archivo Privado.txt
* 5a7d5f1 Se modifica archivo README.MD
* 940ae4f se crea repositorio y se agrega la carpeta README.md

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git add .

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git commit -m "se borra la rama"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Arbusta@N-429 MINGW64 ~/Desktop/ejercicio_final_Git_hub/Devjumpers (main)
$ git push
Everything up-to-date

| Nombre               | GitHub                          |
| -------------------- | ------------------------------- |
| Matias Albujar       | [Matias-lab-ARB](https://github.com/Matias-lab-ARB)     |
| Yuneidis Serna   | [YuneidisLS](https://github.com/YuneidisLS) |

