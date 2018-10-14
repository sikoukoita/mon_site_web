# Exercice 1
## Créez un dépôt sur le serveur Gogs et récupérez-le dans un dépôt local.
Pour cela, il faut aller à la page d'accueil gogs pour voir notre dépot et puis aller dans l'onglet code. Il ya plusieurs possibilités
pour récupérer le dépot en local.J'ai plutôt utilisé les lignes de commandes en utilisant HTTPS.

## Ajoutez/commitez/pushez quelques fichiers et vérifiez sur le site Gogs que les modifications sont bien sur le serveur.


# Exercice 2
## Associez-vous à un ou deux collègues.
Je me suis associé à Siriman pour accéder à ses dossiers.
![]
##Créez un dépôt sur le serveur Gogs et ajoutez vos collègues comme collaborateurs

J'ai ajouté mon collègue siriman comme collaborateur en cliquant sur l'onglet *collaboration*.
## Récupérez votre dépôt et ajoutez/commitez/pushez quelques fichiers.
J'ai ajouté des fichiers f1 et f2 ensuite les ai commités en utilisant la commande git commit -a.Après je les ai envoyés sur le serveur
en utilisant la commande **git push**.
![]

## Demandez à vos collègues de récupérer votre projet.
J'ai demandé à mon collègue Siriman de récupérer mon projet nommé et de mon côté j'ai modifié un de ses fichiers
![]

## Demandez à un collègue de commiter/pusher une modification et vérifiez que vous arrivez à la récupérer de votre côté.
Reçu les fichiers que siriman a pushés 
![]
## Faites maintenant des modifications en parallèle sur un même fichier.
J'ai essayé de modifier les mêmes fichiers que siriman ce qui crée un conflit en lui et moi.
être en conflit c'est lorsque deux personnes essaient de travailler en même temps sur un seul fichier ou de modifier un seul fichier
à la fois.
![]

## Vérifiez que vous avez bien un conflit, résolvez-le et synchronisez tout le monde.
 Lors d'un conflit, la commande git merge nous sera très utile. Eller permet de nous afficher l'interface entre les versions en conflit
 et en décider de quellemanière merger les différentes versions du fichier.
![]
