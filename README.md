#Les commande GIT

*git clone <link>*
> liaison dépots avec votre ordinateur local

*git add <name file> (selection d'un fichier)*
> (selection de tout les fichier) ou -A

> Permet la mise en attente des fichiers vers
le serveur en ligne (pour mon cas github)

*git commit -m "text"*
> rédige les actions faites par l'utilisateur
et création du commit! (le -m "text"; n'est pas obligatoire !)

*git push*
> envoi du commit sur le dépos en ligne

*git push --set-upstream origin <name_branch>*
> envoi de la branche en ligne

*git fetch*
> récupération des données du dépos

*git branch <name_branch>*
> créer une branche pour créer des envois sur une partie du code appart
( cette commande doit être executer en premier si l'on veut changer de branche)

*git checkout <name_branch>*
> se placer sur la branche afin d'ajouter du contenu et des ajouts

*git merge*
> importation des commits vers une branche

*git pull*
> mettre tout à jour entre le serveur github et le dossier local
