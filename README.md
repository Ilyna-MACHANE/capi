# Planning Poker ♠️♦️🃏

__Comment utiliser l'application :__

Ouvrez le fichier index.html

Choisir soit commençer une nouvelle partie ou continuer, ne pas toucher à autre chose avant cette étape.


__Si reprendre une partie :__


Pendant une pause (carte café), un fichier progression.json est téléchargé. Il contient toutes les informations nécessaires pour reprendre la partie.

Cliquez sur "Reprendre une Partie" et chargez le fichier progression.json pour reprendre la partie exactement là où elle a été arrêtée.


__Si nouvelle partie :__


Saisissez le nombre de joueurs et le nom de chacun

Sélectionnez le fichier backlog.JSON contenant les tâches à estimer

Cliquez sur "Charger un fichier JSON".

Choisissez le mode de jeu :

Unanimité : Tous les joueurs doivent se mettre d'accord sur une estimation

Moyenne : Une moyenne est calculée à partir des votes des joueurs

Cliquez sur "Démarrer" pour commencer la partie


__Déroulement du vote :__


Pour chaque tâche, les joueurs votent en choisissant une carte parmi les suivantes :

{"0", "1", "2", "3", "5", "8", "13", "20", "40", "100", "café"}

Les joueurs votent chacun leur tour

Carte café fonctionne seulement si tous les joueurs l'ont choisie 


__Fin de partie :__


Une fois toutes les tâches estimées, un message s'affiche pour indiquer la fin de la session.

Cliquez sur "Télécharger Résultats" pour enregistrer les résultats finaux dans un fichier JSON.


*PS : pour choisir à nouveau la même carte, il faut appuyer sur une autre carte et revenir sur celle voulue.*
