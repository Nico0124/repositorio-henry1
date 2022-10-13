# repositorio-henry1
REPOSITORIO 1
nicol@LAPTOP-L431L4G8 MINGW64 ~/Desktop
$ cd ~

nicol@LAPTOP-L431L4G8 MINGW64 ~
$ mkdir CarpetaHenry

nicol@LAPTOP-L431L4G8 MINGW64 ~
$ cd ~

nicol@LAPTOP-L431L4G8 MINGW64 ~
$ cd CarpetaHenry

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry
$ git clone https://github.com/Nico0124/repositorio-henry1.git
Cloning into 'repositorio-henry1'...
warning: You appear to have cloned an empty repository.

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry
$ cd repositorio-henry1

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry/repositorio-henry1 (main)
$ touch archivo-ejemplo.js

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry/repositorio-henry1 (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        archivo-ejemplo.js

nothing added to commit but untracked files present (use "git add" to track)

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry/repositorio-henry1 (main)
$ git add archivo-ejemplo.js

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry/repositorio-henry1 (main)
$ git commit -m ¨Agregado nuevo archivo, archivo-ejemplo.js¨
error: pathspec 'nuevo' did not match any file(s) known to git
error: pathspec 'archivo,' did not match any file(s) known to git
error: pathspec 'archivo-ejemplo.js¨' did not match any file(s) known to git

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry/repositorio-henry1 (main)
$ git comit ¨agregado nuevo archivo, archivo-ejemplo.js¨
git: 'comit' is not a git command. See 'git --help'.

The most similar command is
        commit

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry/repositorio-henry1 (main)
$ git commit -m ¨Agregado nuevo archivo, archivo-ejemplo.js¨
error: pathspec 'nuevo' did not match any file(s) known to git
error: pathspec 'archivo,' did not match any file(s) known to git
error: pathspec 'archivo-ejemplo.js¨' did not match any file(s) known to git

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry/repositorio-henry1 (main)
$ git commit -m ´´archivo ejemplo terminado´´
error: pathspec 'ejemplo' did not match any file(s) known to git
error: pathspec 'terminado´´' did not match any file(s) known to git

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry/repositorio-henry1 (main)
$ git commit -m ¨archivo ejemplo terminado¨
error: pathspec 'ejemplo' did not match any file(s) known to git
error: pathspec 'terminado¨' did not match any file(s) known to git

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry/repositorio-henry1 (main)
$ git commit -m ´archivo ejemplo terminado´
error: pathspec 'ejemplo' did not match any file(s) known to git
error: pathspec 'terminado´' did not match any file(s) known to git

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry/repositorio-henry1 (main)
$ git commit -m
error: switch `m' requires a value

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry/repositorio-henry1 (main)
$ git comit -m ´archivo ejemplo terminado"
>
> git push
>
> git commit -m ´archivo ejemplo terminado"
git: 'comit' is not a git command. See 'git --help'.

The most similar command is
        commit

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry/repositorio-henry1 (main)
$ git commit -m "archivo ejemplo terminado"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'nicol@LAPTOP-L431L4G8.(none)')

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry/repositorio-henry1 (main)
$ git config -- global user.email nicolgonzalez2424@gmail.com
error: key does not contain a section: global

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry/repositorio-henry1 (main)
$ git config --global user.email nicolegonzalez2424@gmail.com

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry/repositorio-henry1 (main)
$ git config --global user.name Nico0124

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry/repositorio-henry1 (main)
$ git push
error: src refspec refs/heads/main does not match any
error: failed to push some refs to 'https://github.com/Nico0124/repositorio-henry1.git'

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry/repositorio-henry1 (main)
$ git commit -m "archivo ejemplo terminado"
[main (root-commit) 50e6b3e] archivo ejemplo terminado
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 archivo-ejemplo.js

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry/repositorio-henry1 (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 238 bytes | 119.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Nico0124/repositorio-henry1.git
 * [new branch]      main -> main

nicol@LAPTOP-L431L4G8 MINGW64 ~/CarpetaHenry/repositorio-henry1 (main)
$
