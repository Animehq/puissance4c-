Matthias Reimund
Kamill Raczynski
B2 Ingesup	

			Projet 2016 POO- puissance 4

Introduction�:

Pour ce projet de POO,  Kamill et moi avons d�cid� de cr�er un jeu puissance 4 dans le langage de programmation C++.
Ce programme n�cessitait, de comporter une histoire ainsi que plusieurs fonctionnalit�.
Pour r�aliser ce jeu de la meilleure mani�re qu�il soit nous nous sommes demand� quelles sont les caract�ristiques de ce jeu.


I-Concept�:

Le but du jeu est d'aligner 4 pions sur une grille comptant 6 rang�es et 7 colonnes. Chaque joueur dispose de 21 pions d'une couleur (par convention, en g�n�ral jaune ou rouge). Tour � tour les deux joueurs placent un pion dans la colonne de leur choix, le pion coulisse alors jusqu'� la position la plus basse possible dans la dite colonne � la suite de quoi c'est � l'adversaire de jouer. Le vainqueur est le joueur qui r�alise le premier un alignement (horizontal, vertical ou diagonal) d'au moins quatre pions de sa couleur. Si, alors que toutes les cases de la grille de jeu sont remplies, aucun des deux joueurs n'a r�alis� un tel alignement, la partie est d�clar�e nulle.


	Nous avons cod� ce jeu pour qu�il apparaisse en ligne de commande, cette particularit� nous mettait une contrainte dans certaines caract�ristiques de ce jeu.
En effet le jeu ne dispose pas de couleur.
Pour r�gler ce probl�me de mani�re efficace nous avons d�cid� de remplacer les couleurs par un symbole (une croix ou un rond).


II-Histoire�:
Apres les �pres de plusieurs guerres mondiales entre les deux grandes nations de la plan�te Pion, la situation s'�tait am�lior�e et le dialogue retrouva sa place parmi les pays.
 Pouss� par la population, les grands gouvernements �tablirent une commission afin de trouver LA solution permettant de conserver la paix. Apres des si�cles de r�flexions, les sages mirent en place un concept qui permet d'allier strat�gies et ruses pour assoir l'autorit� de la nation au c�ur pure. 
Les grands vaisseaux de guerres furent demis de leurs armes. De grands champs stellaires furent am�nag�s et une nouvel aire vit le jour Les sages appellent   ce syst�me PUISSANCE 4.

III-Fonctionnalit�s�:

	Le programme commence par afficher un menu.
Suite � ce menu le jouer a le choix�:
-Comme pour le jeu  physique, ce puissance 4 que nous avons cr�� permet � deux personnes de jouer l�une contre l�autre, et ce en pla�ant tour par tour les jetons.
	-Ce jeu permet aussi � un joueur seul de faire une partie contre une intelligence artificielle.

IV-Probl�me rencontr�:

	Un des principaux probl�mes rencontr�s lors de ce projet �tait la partie intelligence artificiel.
En effet nous devions normalement dispos� de plusieurs niveaux d�intelligence (1 pour 10 de QI, 2 pour 20 ect).
Le probl�me �tait que pour les niveaux deux et sup�rieure, l�intelligence artificielle jouer en m�me temps le nombre de coup correspondant � son niveau, (il jouait deux coups de suite quand il �tait niveau deux, 3 coups de suite au niveau 3 etc) 
Nous n�avons pas r�ussi � r�soudre ce probl�me, et suite � l��ch�ance proche du projet nous avons d�cid� de supprimer les niveaux deux et sup�rieurs.

	Un deuxi�me probl�me rencontr� est la gestion de la gravit�.
En effet puisque le jeu est virtuel nous avons d� penser � un moyen de recr�er la gravit� puisque celle-ci est indispensable au bon fonctionnement du jeu.
Suite � notre r�flexion nous avons d�cid� d�utiliser le principe des piles FIFO  pour simuler la gravit�.
Les jetons iront donc se positionner sur la derni�re case disponible au niveau de la colonne s�s�lectionn�e.   
