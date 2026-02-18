USER@BENEDICT MINGW64 ~
$ mkdir projects

USER@BENEDICT MINGW64 ~
$ cd projects

USER@BENEDICT MINGW64 ~/projects
$ mkdir week1 week2

USER@BENEDICT MINGW64 ~/projects
$ cd week1

USER@BENEDICT MINGW64 ~/projects/week1
$ touch hello.txt

USER@BENEDICT MINGW64 ~/projects/week1
$ ls
hello.txt

USER@BENEDICT MINGW64 ~/projects/week1
$ cp hello.txt /c/Users/USER/projects/week2/hello_copy.txt

USER@BENEDICT MINGW64 ~/projects/week1
$ ls
hello.txt

USER@BENEDICT MINGW64 ~/projects/week1
$ rm hello.txt

USER@BENEDICT MINGW64 ~/projects/week1
$ ls

USER@BENEDICT MINGW64 ~/projects/week1
$ cd ..

USER@BENEDICT MINGW64 ~/projects
$ ls week2
hello_copy.txt

USER@BENEDICT MINGW64 ~/projects
$ cd ..

USER@BENEDICT MINGW64 ~
$ cd projects

USER@BENEDICT MINGW64 ~/projects
$ vim about_me.txt

USER@BENEDICT MINGW64 ~/projects
$ git init
Initialized empty Git repository in C:/Users/USER/projects/.git/

USER@BENEDICT MINGW64 ~/projects (master)
$ git add .
warning: in the working copy of 'about_me.txt', LF will be replaced by CRLF the next time Git touches it

USER@BENEDICT MINGW64 ~/projects (master)
$ git commit -m "my first commit."
[master (root-commit) 37751be] my first commit
 2 files changed, 1 insertion(+)
 create mode 100644 about_me.txt
 create mode 100644 week2/hello_copy.txt

USER@BENEDICT MINGW64 ~/projects (master)
$ git remote add origin https://github.com/Berabari-Age/command-line-basics.git

USER@BENEDICT MINGW64 ~/projects (master)
$ git branch -M main

USER@BENEDICT MINGW64 ~/projects (main)
$ git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 426 bytes | 142.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Berabari-Age/command-line-basics.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
