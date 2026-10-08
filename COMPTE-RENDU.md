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
 permet d'obtenir un historique clair et de faciliter la relecture et d'isoler des futurs problemes

### Question 4.1
git show montre : 
```commit 83ef344f0811a34a1a8f1963ce50a59a856381f1
Author: RaphMOULY <raphmly@gmail.com>
Date:   Thu Oct 8 09:19:54 2026 +0200

    Création du README

diff --git a/Compte_rendu.md b/Compte_rendu.md
new file mode 100755
index 0000000..5aa7021
--- /dev/null

```
il me montre qui est l'auteur, l'email de la personne, la date et les modifications apportées en spécifiant les fichiers 

### Question 4.2 
il a restorer depuis le dernier commit 

### Question 4.3

il ce trouve dans le rÉpertoire de travail, il n'a pas etait supprimer du disque.

### Question 4.4

brouillon debug erreur et test on etait supprimer apres l'ajout de `.gitignore` 

`*log` désigne les noms terminant par .log

### Question 4.5
le premier readme contenait juste les questions de 0 a 3.2 ce qui a changé l'ajout des autre question

### Question 5.2
1.
les fichiers :
`id_ed25519` et `id_ed25519.pub`
le deuxieme est la clé publique car il possede .pub a la fin

2.
rwx------ pour les 2 clés 
car seul celui qui as créer la clé peux y acceder

### Question 5.4 
```he authenticity of host 'github.com (140.82.121.3)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
Hi RaphMOULY! You've successfully authenticated, but GitHub does not provide shell access.
```
### Question 6.1