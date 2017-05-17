# lookart
Projet commun 3waGr1

A Symfony project created on May 17, 2017, 10:55 pm.


#########################################################################################

## NOTES : 

Pour suivre ces premières instructions, 
-	installer Git sur son ordi. [Dernière version](http://git-scm.com/downloads)
-	créer un compte sur https://github.com
-	... Peut-être d'autres manips...
	
J'invite chacun à mettre à jour ce Readme avec l'explication de vos manip/install

Ca aidera les autres, et ça vous fera manipuler un peu

#########################################################################################

## METHODES DE TRAVAIL :

J'ai laissé la branche master comme repertoire par défaut (par simplicité)

Une branche de sauvegarde sera créée par la suite

Prenez l'habitude de créer une branche personnelle lorsque vous développez une nouvelle fonctionnalité

`Les lignes de commandes` sont à entrer dans la console, depuis le repertoire de travail (www/lookart)

#########################################################################################

## Comment contribuer à un projet Open Source ? (méthodologie standard)

1. Fork it (cela copie le projet dans votre compte GitHub)
2. Create your feature branch `git checkout -b [fonctionnalité-perso]`
3. Commit your changes `git commit -am "Ajout de nouvelles fonctionnalités`
4. Push to the branch `git push origin [fonctionnalité-perso]`
5. Create new Pull Request

#########################################################################################

### Mise en place de l'espace de travail : 

	//A remplir au fur et à mesure

Récupération du contenu du repository :
* Sur votre ordi, dans le dossier [chemin d'accès]/www/
* Créer un nouveau dossier de travail (par exemple "lookart")
* Ouvrez la console GitBash (ou Command Windows, ou le Terminal Linux)
* Positionnez vous dans le dossier précédemment créé
```
cd [lecteur]:
cd [chemin d'accès]/www/lookart
```
* Initialisation de l'espace de travail
```
git init
```
* **Fork it** depuis https://github.com/Samsuffi/lookart.git
* Copiez le contenu de votre repository dans votre dossier
```
git clone https://github.com/[votrecompte]/lookart.git 
```
Vous devriez avoir le projet votre dossier www/lookart

* **Create branch**
* Faites vos modifications
* **Commit**
* **Push** dans votre repository
* **Pull Request** pour que le dossier principal soit mis à jour (nécessite une intervention humaine)

#########################################################################################

#### Commandes utiles :

Sous les terminaux type Linux (Terminal ou GitBash) la touche tabulation 
	permet une écriture automatique des chemins d'accès à partir des premières lettres pertinentes
	avec trois dossiers [local, wamp, windows],
	
`cd l` |tab| trouve local, mais `cd w` |tab| ne trouvera pas, il faudra préciser wi ou wa

`cd [to]` : "change directory"-espace-pathDirectory permet de se positionner dans le pathDirectory

	Exemples :
	`cd e:` : se positionner dans le lecteur E: (utiliser C:, D:, etc selon votre install)
	`cd wamp/www/lookart` : se positionner dans le dossier lookart
	
		
`[commande] --help`, `[commande] -h` ou` [commande] -?` : au moins une de ces options permet de voir la doc de la commande

`pwd` : adresse du repertoire courant

`dir` ou `ls` : voir le contenu du dossier courant

`ls -l -a` ou `ls -la` : comande ls avec des options d'affichage utiles

---------------------------------------------------------------------------------------------------

`git init` : initialisation du repertoire de travail

`git status` : LA commande que vous allez le plus utiliser !

`git add` [fichier ou dossier] : ajouter le fichier/dossier à l'index .git pour le commit

`git commit -m "[votre message]"` : créer un commit qui aura pour titre "[votre message]"

`git push origin [branche]` : mettre à jour la branche du repository avec votre travail

`git pull [adresse]` : mettre à jour votre dossier depuis le repository

#########################################################################################

#### Liens utiles :

[Mises en formes courantes sur les articles GitHub (ex. Readme)](https://help.github.com/articles/basic-writing-and-formatting-syntax)
