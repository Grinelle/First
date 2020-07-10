créer un dossier GIT dans le dossier document de l'ordi

Commande dans GIT CMD

cd GIT ( aller dans le dossier GIT)
git --version

git config --global user.name "utilisateur"
git config --global user.email "email"

git config -l 


dir  (se positionner là où on veut aller)
mkdir nom_projet ( création d'un dossier projet)
cd nom_projet  (aller dans le dossier nom_projet)
cd..  ( permet de remonter d'un niveau)

git init ( créer un dossier .git dans le dossier nom_projet)
git status

(créer d'abord dans l'éditeur un fichier index pour l'ajouter, faire add puis commit)
git add <nom_du_fichier_1>
git add <nom_du_fichier_2>

git commit --message "texte du message" ( sans accent sur caractère)
raccourci ==> git commit -m "texte du message"
git diff
git diff master..B1 ( voit difference entre les 2 branches)

git log ( voit tous les messages)


git branch ma-fonction  ( créer une branche )
git checkout nouvelle-branche (sort de master et  aller sur la branche)

git checkout master ( sortir de la  ligne master)

fusion des branches:
git merge nouvelle-branche

git branch -d nombranche ( supprimer une branche avec vérification, si merge non effectué , supression impossible)
git branch -D nombranche ( supprimer une branche SANS vérification) ATTENTION !

GIT visualisation des branches d'un projet
https://onlywei.github.io/explain-git-with-d3/

git officiel compte sur https://github.com/

envoi de projet en ligne à partager :

récupérer sur Github le lien  à la création du projet

  => git remote add origin https://github.com/Grinelle /nom_projet.git
taper dans git cmd ce lien puis :

git remote -v (vérification du fichier)
git push -u origin master ( envoi le projet sur github)

git pull origin master   ( récupérer)
git pull <distant> <branche>  (récupérer)

application en local

windows.github.com

