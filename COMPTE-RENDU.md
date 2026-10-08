# TP 01

## Partie 0

Question 0 : 

git version 2.43.0

## Partie 1

Question 1 :

https://github.com/RaphMOULY

## Partie 2
Question 2 : 

1) 
```
user.name=RaphMOULY
user.email=raphmly@gmail.com
init.defaultbranch=main
core.editor=nano
```


2)   

l'option `--global` indiquer que la configuration ou l'action demandée doit s'appliquer à l'ensemble de l'utilisateur, et non pas uniquement au projet ou au dossier actuel

C'est réglage sont enregistrer dans ~/tp-git
## Partie 3 

### Question 3.1

git status répond:
```
fatal: ni ceci ni aucun de ses répertoires parents (jusqu'au point de montage /) n'est un dépôt git
Arrêt à la limite du système de fichiers (GIT_DISCOVERY_ACROSS_FILESYSTEM n'est pas défini).
```
Il répond ca car le dossier n'a pas etait transformer en dépôt

### Question 3.2

git init a créé le dossier .git/

et nous ne pouvons pas le voir avec un simple ls car cest un fichier cacher.

git status me dit 
```Sur la branche main

Aucun commit

rien à valider (créez/copiez des fichiers et utilisez "git add" pour les suivre)
```

### Question 3.3
 dans le repertoire de travail

### Question 3.4
README.md ce trouve dans "branche main"

### Question 3.5
```
Author: RaphMOULY <raphmly@gmail.com>
Date:   Thu Oct 8 09:19:54 2026 +0200

    Création du README
```
le hash comporte 40 caractere en hexadécimale et il représente 160 bits

### Question 3.7 
git status me décrit que le "README.md" est modifié.

le + en début de ligne du git diff me montre tout les ajouts qui ont etait fait depuis le dernier git add 

### Question 3.8