# lookart
Projet commun 3waGr1

#########################################################################################

NOTES : 

Pour suivre ces premières instructions, 
	il faut installer Git sur son ordi.
	il faut se créer un comtpe sur https://github.com
	... Peut-être d'autres manips...
	
J'invite chacun à mettre à jour ce Readme avec l'explication de vos manip/install
Ca aidera les autres, et ça vous fera manipuler un peu

on est d'accord que les [noms entre crochets] correspondent à des données variables selon les besoins/envies

#########################################################################################

METHODES DE TRAVAIL :

J'ai laissé la branche master comme repertoire par défaut (par simplicité)
Une branche de sauvegarde sera créée par la suite
Prenez l'habitude de créer une branche personnelle lorsque vous développez une nouvelle fonctionnalité
Les lignes commencant par un tidle : ~ correspondent à des commandes à entrer dans la console,
			souvent en se positionnant dans le dossier de travail (www/lookart)

#########################################################################################

Mise en place de l'espace de travail : 

		//A remplir au fur et à mesure

Récupération du contenu du repository :

Sur votre ordi, dans le dossier [chemin d'accès]/www/
Créer un nouveau dossier de travail (par exemple "lookart")

Ouvrez la console GitBash (ou Command Windows, ou le Terminal Linux)
Positionnez vous dans le dossier précédemment créé

~ cd [lecteur]:
~ cd [chemin d'accès]/www/lookart

Initialisation de l'espace de travail
~ git init

Récupération du contenu du repository
~ git pull https://github.com/Samsuffi/lookart.git

16/05/17 : Vous devriez avoir ce fichier Readme dans votre dossier lookart

#########################################################################################

Commandes utiles :

~ cd [to] : "change directory"-espace-pathDirectory permet de se positionner dans le pathDirectory

		Exemples :
		~ cd e: : se positionner dans le lecteur E: (utiliser C:, D:, etc selon votre install)
		~ cd wamp/www/lookart : se positionner dans le dossier lookart
		
~ [commande] --help ou [commande] -h ou [commande] -? : au moins une de ces options permet de voir la doc de la commande

~ pwd : adresse du repertoire courant

~ dir ou ls : voir le contenu du dossier courant

~ ls -l -a ou ls -la : comande ls avec des options d'affichage utiles

---------------------------------------------------------------------------------------------------

~ git init : initialisation du repertoire de travail

~ git status : LA commande que vous allez le plus utiliser !

~ git add [fichier ou dossier] : ajouter le fichier/dossier à l'index .git pour le commit

~ git commit -m "[votre message]" : créer un commit qui aura pour titre "[votre message]"

~ git push origin [branche] : mettre à jour la branche du repository avec votre travail

~ git pull [adresse] : mettre à jour votre dossier depuis le repository

#########################################################################################
