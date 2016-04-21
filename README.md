Matthias Reimund
Kamill Raczynski
B2 Ingesup	

			Projet 2016 POO- puissance 4

Introduction :

Pour ce projet de POO,  Kamill et moi avons décidé de créer un jeu puissance 4 dans le langage de programmation C++.
Ce programme nécessitait, de comporter une histoire ainsi que plusieurs fonctionnalité.
Pour réaliser ce jeu de la meilleure manière qu’il soit nous nous sommes demandé quelles sont les caractéristiques de ce jeu.


I-Concept :

Le but du jeu est d'aligner 4 pions sur une grille comptant 6 rangées et 7 colonnes. Chaque joueur dispose de 21 pions d'une couleur (par convention, en général jaune ou rouge). Tour à tour les deux joueurs placent un pion dans la colonne de leur choix, le pion coulisse alors jusqu'à la position la plus basse possible dans la dite colonne à la suite de quoi c'est à l'adversaire de jouer. Le vainqueur est le joueur qui réalise le premier un alignement (horizontal, vertical ou diagonal) d'au moins quatre pions de sa couleur. Si, alors que toutes les cases de la grille de jeu sont remplies, aucun des deux joueurs n'a réalisé un tel alignement, la partie est déclarée nulle.


	Nous avons codé ce jeu pour qu’il apparaisse en ligne de commande, cette particularité nous mettait une contrainte dans certaines caractéristiques de ce jeu.
En effet le jeu ne dispose pas de couleur.
Pour régler ce problème de manière efficace nous avons décidé de remplacer les couleurs par un symbole (une croix ou un rond).


II-Histoire :
Apres les âpres de plusieurs guerres mondiales entre les deux grandes nations de la planète Pion, la situation s'était améliorée et le dialogue retrouva sa place parmi les pays.
 Poussé par la population, les grands gouvernements établirent une commission afin de trouver LA solution permettant de conserver la paix. Apres des siècles de réflexions, les sages mirent en place un concept qui permet d'allier stratégies et ruses pour assoir l'autorité de la nation au cœur pure. 
Les grands vaisseaux de guerres furent demis de leurs armes. De grands champs stellaires furent aménagés et une nouvel aire vit le jour Les sages appellent   ce système PUISSANCE 4.

III-Fonctionnalités :

	Le programme commence par afficher un menu.
Suite à ce menu le jouer a le choix :
-Comme pour le jeu  physique, ce puissance 4 que nous avons créé permet à deux personnes de jouer l’une contre l’autre, et ce en plaçant tour par tour les jetons.
	-Ce jeu permet aussi à un joueur seul de faire une partie contre une intelligence artificielle.

IV-Problème rencontré :

	Un des principaux problèmes rencontrés lors de ce projet était la partie intelligence artificiel.
En effet nous devions normalement disposé de plusieurs niveaux d’intelligence (1 pour 10 de QI, 2 pour 20 ect).
Le problème était que pour les niveaux deux et supérieure, l’intelligence artificielle jouer en même temps le nombre de coup correspondant à son niveau, (il jouait deux coups de suite quand il était niveau deux, 3 coups de suite au niveau 3 etc) 
Nous n’avons pas réussi à résoudre ce problème, et suite à l’échéance proche du projet nous avons décidé de supprimer les niveaux deux et supérieurs.

	Un deuxième problème rencontré est la gestion de la gravité.
En effet puisque le jeu est virtuel nous avons dû penser à un moyen de recréer la gravité puisque celle-ci est indispensable au bon fonctionnement du jeu.
Suite à notre réflexion nous avons décidé d’utiliser le principe des piles FIFO  pour simuler la gravité.
Les jetons iront donc se positionner sur la dernière case disponible au niveau de la colonne s’sélectionnée.   
