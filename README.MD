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
