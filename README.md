# proyecto
Introducción a la informática 
pc@MiGuEl MINGW64 ~ (main)
$ cd destok
bash: cd: destok: No such file or directory

pc@MiGuEl MINGW64 ~ (main)
$ cd desktop

pc@MiGuEl MINGW64 ~/desktop (main)
$ mkdir animales_salvajes

pc@MiGuEl MINGW64 ~/desktop (main)
$ cd animales_salvajes

pc@MiGuEl MINGW64 ~/desktop/animales_salvajes (main)
$ mkdir carnivoros herbivoros omnivoros

pc@MiGuEl MINGW64 ~/desktop/animales_salvajes (main)
$ ls
carnivoros/  herbivoros/  omnivoros/

pc@MiGuEl MINGW64 ~/desktop/animales_salvajes (main)
$ touch leon.txt cebra.txt conejo.tx

pc@MiGuEl MINGW64 ~/desktop/animales_salvajes (main)
$ ls
carnivoros/  cebra.txt  conejo.tx  herbivoros/  leon.txt  omnivoros/

pc@MiGuEl MINGW64 ~/desktop/animales_salvajes (main)
$ git add .

pc@MiGuEl MINGW64 ~/desktop/animales_salvajes (main)
$ ls
carnivoros/  cebra.txt  conejo.tx  herbivoros/  leon.txt  omnivoros/

pc@MiGuEl MINGW64 ~/desktop/animales_salvajes (main)
$ git commit -m
error: switch `m' requires a value

pc@MiGuEl MINGW64 ~/desktop/animales_salvajes (main)
$ git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


pc@MiGuEl MINGW64 ~/desktop/animales_salvajes (main)
$ git add animales_salvajes
fatal: pathspec 'animales_salvajes' did not match any files

pc@MiGuEl MINGW64 ~/desktop/animales_salvajes (main)
$ git init main
Initialized empty Git repository in C:/Users/pc/Desktop/animales_salvajes/main/.git/

pc@MiGuEl MINGW64 ~/desktop/animales_salvajes (main)
$ git commit -m
error: switch `m' requires a value

pc@MiGuEl MINGW64 ~/desktop/animales_salvajes (main)
$ git commit -m primer examen
error: pathspec 'examen' did not match any file(s) known to git

pc@MiGuEl MINGW64 ~/desktop/animales_salvajes (main)
$ git init main
Reinitialized existing Git repository in C:/Users/pc/Desktop/animales_salvajes/main/.git/

pc@MiGuEl MINGW64 ~/desktop/animales_salvajes (main)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

pc@MiGuEl MINGW64 ~/desktop/animales_salvajes (main)
$ git init -b main
Initialized empty Git repository in C:/Users/pc/Desktop/animales_salvajes/.git/

pc@MiGuEl MINGW64 ~/desktop/animales_salvajes (main)
$ git add . && commit -m "initial commit"
error: 'main/' does not have a commit checked out
fatal: adding files failed

pc@MiGuEl MINGW64 ~/desktop/animales_salvajes (main)
$
