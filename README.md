# Commandes GIT

## Création d'un dépôt

- git --version : véfifie la version de git
- git init : créer un dépôt git
- git remote add origin "url_dépôt" : fait un lien de connexion entre le dépôt local et le dépôt distant

## Ajout et envoi des fichiers

1) git add : ajoute les documents à envoyer

- git add nom_fichier nom_fichier2

<br>

2) git commit : permet de mettre l'adresse sur l'enveloppe (exemple)

- Important : Ajouter les identifiants (email et nom) pour pouvoir commit
--> git config user.email "email"
--> git config user.name "name"

- Note : on peut ajotuer --global pour tout le temps utiliser le même compte, mais pas pratique s'il faut changer de compte

- git commit -m "mon message pour le comit"

<br>

3) git push : les envoient sur le dépôt

- git push origin master ou git push origin main


- Github nous demande ensuite notre username et notre token
