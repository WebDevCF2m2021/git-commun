# git-commun

## Premier projet de travail en groupe

## A faire

- Installez git sur votre machine : https://git-scm.com/
- Inscrivez-vous sur https://github.com/
- Mémorisez votre login, mot de passe et un email valide!

Lorsque vous ouvrirez une console de commande sur votre poste de travail, veillez à ce que cette commande fonctionne:

    git --version

Ensuite, **en utilisant votre login (name) et email pour vous connecter à Github**

    git config --global user.name "JohnDoe"
    git config --global user.email johndoe@example.com

Votre git sur votre poste de travail est désormait liable à votre compte github !  

Vous trouverez plus de détails à cette adresse : https://git-scm.com/book/fr/v2/D%C3%A9marrage-rapide-Param%C3%A9trage-%C3%A0-la-premi%C3%A8re-utilisation-de-Git

## Liste des commandes GIT

[Lien vers l'image git-cheat-sheet](https://raw.githubusercontent.com/mikhawa/g_i_t/main/img/Git-cheat-sheet.jpg "git-cheat-sheet")

## Marche à suivre

Merci à https://github.com/QuentinFayt pour la création originelle de la marche à suivre sur Discord !

Pour commencer faite un click droit dans n'importe quel dossier pour créer un projet git et sélectionner "Git Bash" (ou ouvrir la console sous mac) cela ouvre une console de commande. 

Git GUI quand à lui permet d'avoir une interface graphique pour un aspect plus visuel des changements effectués (ou tapez gitk dans la console sous mac).


---
$ **git init** : pour initialiser un projet .git

---
$ **git status** : permet de vérifier si la branche locale est up to date par rapport à ce qui est en ligne (si le projet est lié), et si des modifications sont existantes en local.

---
$ **git clone** : permet de créer un clone d'un dossier git existant sur un serveur => git clone https://github.com/MonPseudo/MonDossier.git créera un clone en local du dossier git MonDossier provenant de mon compte.

---
$ **git add** : permet d'ajouter un fichier dans la mémoire tampon directement en ajoutant le nom complet du fichier après, exemple : 
git add monfichier.txt, le fichier est donc suivi.

---
$ **git add .** : permet d'ajouter tout les fichiers du dossier courant dans la mémoire tampon, les fichiers seront donc suivis.

---
$ **git rm --cached fichier** : permet de retirer un fichier de la mémoire tampon, le fichier ne sera donc plus suivi. "git rm --cached NomDeFichier.txt" => retire le fichier "NomDeFichier.txt" du suivi

---
$ **git commit -m "un texte"** : permet de rajouter le commentaire "un texte" (à utiliser avant d'envoyer un fichier sur le dossier git en ligne.)

---
$ **git log** : permet de voir tout les commits fait précédemment

---
$ **git remote add origin https://github.com/PseudoGit/mondossier.git** : permet de faire en sorte de considérer le dossier "mondossier.git" à distance se trouvant à l'adresse https://github.com pour mon compte comme la branche originale

---
$ **git branch -M main** : permet de faire en sorte de travailler sur la branche main. 

---
$ **git push origin main** : permet d'essayer d'envoyer dans l'origine la branche main local et de créer un lien entre les deux. ("git push --set-upstream origin" main si la ligne ne fonctionne pas mais il faut faire attention avec cette ligne)

---
$ **git push** : permet d'envoyer tout les fichiers suivis ajoutés précédemment en local.

---
$ **git remote -v** : permet de vérifier sur quelle fork on travaille

---
$ **git remote add upstream https://github.com/PseudoDuChefDeProjet/ProjetOriginal.git** : rajouter un lien entre votre projet et le projet originel.

---
$ **git pull upstream main** : permet de mettre à jour votre dossier en LOCAL par rapport au dossier originel

---

## Pour créer un fork depuis un projet existant

Utile pour travailler en équipe (merci encore à @QuentinFayt ):

![alt text](https://raw.githubusercontent.com/mikhawa/git-commun/main/img/Quentin01.PNG "FR")
![alt text](https://raw.githubusercontent.com/mikhawa/git-commun/main/img/Quentin02.PNG "FR")
![alt text](https://raw.githubusercontent.com/mikhawa/git-commun/main/img/Quentin03.PNG "FR")

## Liste des commandes Linux

Elles sont utiles car git est créé par Linus Torvalds, créateur de Linux.

Quelque soit votre système d'exploitation (Windows, Mac ou Linux), ces commandes vous serons utiles !

### Liste minimale

    Les commandes de gestion des répertoires et des fichiers

    pwd (affiche le chemin absolu du répertoire courant)

    ls (list, affiche les répertoires et les fichiers du répertoire actif)
    ls -l (affiche le format long : types + droits + Nbre de liens + ....)

    cd chemin/existant (change directory)
    cd .. (répertoire parent)
    cd ~ (répertoire de base)
    cd - (répertoire précedent)
    cd / (répertoire racine)

    cp (copie)
    cp rapport*.txt sauvegarde.txt


    mv (move, renomme et déplace un fichier)
    mv source destination
    mv * dossier (déplace tous les fichiers du répertoire actif vers le répertoire (dossier)

    mkdir (créer un répertoire)
    mkdir répertoire

    rmdir (effacer un répertoire)
    rmdir dossier (supprime un répertoire vide)

    rm (remove, éfface!!!)

### PDF Linux

[Lien vers le PDF Commandes Linux](https://github.com/WebDevCF2m2021/git-commun/raw/main/commandes%20Linux/commandes_linux.pdf "Memento Linux")

[Lien vers le PDF Memento Linux](https://github.com/WebDevCF2m2021/git-commun/raw/main/commandes%20Linux/memento_linux.pdf "Memento Linux")



