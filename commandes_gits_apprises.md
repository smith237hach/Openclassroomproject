#  **COMMANDES GITS APPRISES**

##  1 **INTRODUCTION**

*au fur et en mesure j'ai pu prendre compte de l'existence de plusieurs balises permetteant de prendre controle de **GIT** et d'interagir avec **GITHUB** je leurs aient subdiviser en plusieurs classe*

##  A **LES BALISES DE CLASSE 1 OU BALISES DE PARAMETRAGE ET DE CONFIGURATION**

Liste:
1. ***cd***: cette commande linux permet de se deplacer dans les dossiers de votre machine
2. ***mkdir***: cette commande permet de creer un fichier dans le documents ou l'utilisateur travail
3. ***git config --global***: cette commande a pour role de configurer son depot local au niveau des informations tel que (nom de l'utilisateur, son email; configurer son interface <color.status, color.diff, color branch>)
4. ***git init***: cette commande a pour but initialisation de notre depot local
5. ***git add***: cette commande permet d'ajouter un fichier a notre depot local une fois modification terminer afin de pouvoir s'y deplacer a l'interieur 
6. ***git status***: permet de controler le status d'un fichier
7. ***git commit -m***: permet d'ajouter un ou plusieurs fichiers indexer a notre depot local

##  B **LES BALISES DE CLASSE 2 OU BALISES D'INTERRACTION ENTRE LE DEPOT LOCAL ET DISTANT**

Listes:
1. ***git push***: cette commande a pour but de copier les travail de l'utilisateur du depot local vers le depot distant
2. ***git pull***: cettte commande a pour but de faire un fetch du contenu d'un depot distant et pour le telecharger, puis mettre a jour immediatement le depot local qui correspond a ce contenu
3. ***git fetch***: a pour but de recuperer les modifications presentes sur le serveur distant que vous n'avez pas encore sur votre copie local
4. ***git --amend***: permet de modifier un commits
5. ***git branch -M "nom de la branche"***: permet de changer de branche
6. ***git check out***: permet de basculer entre les branches creer avec (git granch)

## C **LES BALISES DE CLASSE 3 OU BALISES DE CORRECTIONS D'HISTORIQUE**

Listes: 
1. ***git rebase***: permet de reecrire l'historique de la branche qu'on veux rebase 
2. ***git stash***: permet de mettre de cote notre code si on decide amorcer un autre code 
3. ***git bisect***: permet d'identifier les commits erroner
4. ***git stash pop***: permet de reprendre le travail apres avoir regler un probleme 

## 2 **CONCLUSION**

*Durant cette premiere partie de cours j'ai pu prendre connaissances de l'existence de plusieurs balises et cela a mon avantage car elles sont un intermediaire tres important pour pouvoir transiter entre les terminaux et les depot distant*