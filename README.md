# hello-world
Test repository

essaie modif


## récupération du projet
dans un terminal
```git clone https://github.com/ibechd/hello-world.git```
pour récupérer le projet en local

## modification du document
edition du document avec n'importe quel éditeur de texte
suivi des commandes 

```git commit -a -m "ajout d'un commentaire" ```

pour enregistrer les modifications des fichiers dans ma version locale du projet puis 

```git push```

pour mettre à jour la version git en ligne sur github.


## récupération de mes modifications par d'autres personnes

- soit la personne n'a pas encore récupéré le projet et du cout elle doit faire un ```git clone https://github.com/ibechd/hello-world.git```

- soit la personne à déjà récupéré le projet et là elle doit faire un ```git pull```. 

### dans le cas d'un "git pull"

git va vérifier si la version locale de la personne peut être "mergé" avec la version de github.

- Si il n'y a pas de pb, les modifications seront automatiquement appliquées à la version locale de l'utilisateur qui a fait le ```git pull```.
- Si il y a conflit entre un ou plusieurs fichiers, il faudra alors d'abord résoudre les conflits avant de pouvoir mettre à jour sa version locale.

Il faut simplement faire attention à ce que deux personnes ne réalisent pas des modifications différentes sur le même fichier et cherchent à les "pousser" (git pull) sur github en même temps.

Il faudra qu'un des deux utilisateurs récupère les modifications de l'autre avant de "pousser" les siennes sur github.