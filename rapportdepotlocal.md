# Présentation GIT:
Pour rappel, git est un système décentralisé, libre non seulement il est gratuit mais également a une approche peer to peer contrairement à d'autres outils.
Git aide les developpeurs et les chefs de projet d'avoir une pléthore de code.C'est un logiciel effectivement complet.On peut très bien travailler à distance, ce qui le rend très utile. C'est le logiciel le plus utilisé au monde actuellement.

# Exercice

## Créez un nouveau dépôt local, ajoutez des fichiers et faites quelques modifications+commits ; affichez l'état du dépôt à chaque étape.
Pour créer un dépot local sur git, il faut utiliser la commande mkdir suivi le nom  que l'on souhaite donner à notre dépôt local.
Pour vérifier que le dossier a été bien créé, il suffit taper la commande ls sur le terminal.On peut également utilser une autre commande
très utile qui permet de dire tout simplement de se déplacer en arrière.
La commande git init nous permet d'initialiser notre projet.Cette dernière va ajouter un dossier caché .get.
Finalement ce dossier va contenir un ensemble d'informatiwons qui nous permettent la gestion de notre dossier comme étant un dépot git.
Le dossier contient l'historique de nos midifications, la zone d'index, autres informations pour la gestion.

![](C:/Users/lenovo/Desktop/Git/depotlocal.PNG")

## Renommez et supprimez quelques fichiers.
Pour renommer les fichiers et les repertoires, j'ai utilisé la commande mv qui ne sert pas seulement à renommer mais aussi à dépalcer
les fichiers.Pour cela, j'ai créé  des trois fichiers(f1,f2,f3) et les ai renommés par fichier1, fichier2 et fichier3.
Pour supprimer, j'ai créé le quatrième fichier "fichierasupprimer" en utilisant la commande rm (le nom du fichier).

![](C:/Users/lenovo/Desktop/Git/fichierasupprimer.PNG")

## Affichez l'historique des commits et revenez dans un état précédent du dépot. Vérifiez que vos fichiers reviennent bien à l'état correspondant au commit.
La commande git log permet de lister des commits
L'hiistorique du depôt git est constitué d'un ensemble de commits reliés entre eux par un pointeur. Un ensemble de commits reliés entre 
eux, qui constituent ce qu'on appelle une BRANCHE.
Master, c'est la branche principale; un commit est constitué tout d'abord d'un identifiant unique de 40 caractères, d'un ensemble de modifications, les informations sur le développeur(utilisateur), des commentaires.

![](C:/Users/lenovo/Desktop/Git/historique.PNG")

## Ajoutez une étiquette à un ancien commit et vérifiez que vous la voyez dans l'historique des commits ou avec un client Git graphique
Pour ajouter une étiquette à un ancien commit, la commande gitk (étiquette) a été utilisée suivie le nom.

![](C:/Users/lenovo/Desktop/Git/etiquette.PNG")

## Testez les suppressions de commits.
La commande git tag --delete permet de supprimer 





