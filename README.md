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
