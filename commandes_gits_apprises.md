#  **COMMANDES GITS APPRISES**

##  1) => **LES BALISES DE CLASSE 1 OU BALISES DE PARAMETRAGE ET DE CONFIGURATION**

Liste:
1. ***cd***: cette commande linux permet de se déplacer dans les dossiers de votre machine
2. ***mkdir***: cette commande permet de créer des répertoires
3. ***git config --global***: cette commande a pour rôle de configurer son depot local au niveau des informations tel que (nom de l'utilisateur, son email; configurer son interface <color.status, color.diff, color branch>)
4. ***git init***: cette commande a pour but initialisation de notre dépôt local
5. ***git add***: cette commande permet d'ajouter un fichier a notre dépôt local une fois modification terminer afin de pouvoir s'y déplacer a l'intérieur 
6. ***git status***: permet de contrôler le statut d'un fichier
7. ***git commit -m***: permet d'ajouter un ou plusieurs fichiers indexer a notre depot local
8. ***git branch -d "name of the branch***: permet de supprimer une branche de notre choix ou créer  par erreur dans le dépôt  local
9. ***git branch -D "name of the branch"***: permet de supprimer une branche de notre choix, même si on l'as déjà apporter des modifications

##  B => **LES BALISES DE CLASSE 2 OU BALISES D'INTERRACTION ENTRE LE DEPOT LOCAL ET DISTANT**

Listes:
1. ***git push***: cette commande a pour but de copier les travail de l'utilisateur du dépôt local vers le dépôt distant
2. ***git pull***: cette  commande a pour but de faire un fetch du contenu d'un dépôt distant et pour le télécharger, puis mettre à jour immédiatement le dépôt local qui correspond a ce contenu
3. ***git fetch***: a pour but de récupérer les modifications présentes sur le serveur distant que vous n'avez pas encore sur votre copie local
4. ***git --amend***: permet de modifier un commits
5. ***git branch -M "nom de la branche"***: permet de changer de branche
6. ***git check out***: permet de basculer entre les branches créer avec (git granch)

## C => **LES BALISES DE CLASSE 3 OU BALISES DE CORRECTIONS D'HISTORIQUE**

Listes: 
1. ***git rebase***: permet de réécrire l'historique de la branche qu'on veut rebase 
2. ***git stash***: permet de mettre de cote notre code si on décide amorcer un autre code 
3. ***git bisect***: permet d'identifier les commits erronés
4. ***git stash pop***: permet de reprendre le travail après avoir régler un problème 

## 2) => **CONCLUSION**

*Durant cette première partie de cours j'ai pu prendre connaissances de l'existence de plusieurs balises et cela a mon avantage car elles sont un intermédiaire très important pour pouvoir transiter entre les terminaux et les dépôts distants*
