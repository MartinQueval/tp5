# tp3
Nom : Marrouche Mohamad
Groupe : 02
**Année :2023
IUT Le Havre - Cours GIT

# Compte-rendu TP3 Introduction GIT

## Inviter des collaborateurs dans un dépôt personnel
Tout d'abord, une personne dans le groupe crée un dépôt dans github qui aura le même contenu que le tp2.
Ensuite, cette personne va partager ce dépôt dans **invite a collaborator** aux autres membres du groupe.

## Les branches
Si nous voulons tester quelque chose sans que cela n'engendre la branche principale (main/master), nous pouvons créer une deuxième branche pour faire cela.

Nous avons maintenant créé une nouvelle branche de test appelé test avec la commande `git checkout -b test`. Pour voir sur quelle branche nous sommes, on utilise la commande `git branch`.

## Deux branches --> Une branche
Si on veut merger les deux branches, test et main/master , on va sur la branche main `git checkout main` et on tape la commande :
`git merge test`
