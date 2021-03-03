# Workshop_Unity_Basics
Présentation des bases d'Unity

Version d'Unity utilisée pour ce workshop : Unity 2020.2.2f1

1. Intro

Pourquoi s’intéresser à Unity ? 
Ça monte en réputation, la communauté est grande et active, possible de faire des jeux avancés en 2D et en 3D, facile d’utilisation et c’est gratuit.

2. Présentation de l’interface graphique d’Unity :

<img width="1792" alt="Interface_Unity" src="https://user-images.githubusercontent.com/59643688/109830940-435ec400-7c3f-11eb-88ac-a73e04abf60e.png">

	Scene —> Élément principal pour la construction du jeu. Tous les éléments que vous allez ajouter, les positionner, les réajuster, etc… ce sera sur la Scene.
	Hierarchy —> Liste tous les éléments présents dans la Scene.
	Game —> Test en direct du jeu. Sélectionner « Maximize on Play » pour tester le jeu en plein écran.
	Boutons : Play / Pause / Next
  
  <img width="125" alt="Play" src="https://user-images.githubusercontent.com/59643688/109830953-478ae180-7c3f-11eb-8b88-6c68d6c9c3b9.png">

  	Sert pour lancer le test du jeu.
	Project —> Tous les fichiers du jeu : Images, Scripts, Font, Sounds, etc…
	Inspector —> Donne les informations sur l’élément que vous sélectionner dans le panneau Hierarchy.

	Les panneaux visibles sur la capture d’écran sont les éléments principaux.
	Il existe d’autres onglets que l’on peut rajouter. Ces onglets sont listés dans la section « Window » en haut de la fenêtre.
	Aussi vous avez la possibilité de réorganiser les onglets à votre guise.

3. GameObjects
	Ce sont LES éléments du jeu.
	C’est-à-dire, tous les objets présents dans votre jeu est un GameObject.
	<img width="1105" alt="CreateEmpty" src="https://user-images.githubusercontent.com/59643688/109831547-d566cc80-7c3f-11eb-88db-555e69dbab65.png">

	Lorsque vous faites un clic droit sur votre GameObject, ce qui est listé dans le menu déroulant sont en fait des composants, chacun possédant sa fonctionnalité.
	
	
<img width="499" alt="GameObject3" src="https://user-images.githubusercontent.com/59643688/109831567-dbf54400-7c3f-11eb-9444-5d2d7dbb0d0e.png">

	Ce composant sera alors un élément « fils » du GameObject utilisable ensuite.


4. C# dans Unity

	Pour faire simple : les scripts sont utilisé pour contrôler le comportement d’un composant d’un GameObject.
	Travailler avec les scripts est essentiel pour « muscler » le gameplay.
	Exemple : pour ajouter système de sauvegarde.

5. Asset Store

<img width="1335" alt="AssetStore" src="https://user-images.githubusercontent.com/59643688/109831746-034c1100-7c40-11eb-9832-37cc2824b20f.png">

	Comme le dit son nom, dans ce store vous trouverez d’innombrables assets. Des images, des fonts, du materiel UI, etc… à importer à votre jeu.
	Malheureusement pour certains, les assets présents (les plus beaux) sont pour la plupart toujours payants MAIS il en existe des gratuits.

6. À vous !

	Je vous invite à télécharger et importer ce kit de jeu dans votre Unity. Vous verrez alors un peu l’architecture d’un jeu.
	
	
	<img width="1792" alt="KitJeu" src="https://user-images.githubusercontent.com/59643688/109831768-0941f200-7c40-11eb-81ea-a343dc2fa133.png">

Fin.
