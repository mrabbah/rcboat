# RC BOAT
----
L'objectif est de construire un bateau autonome.

Exemple:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/ktYViivw27A/0.jpg)](https://www.youtube.com/watch?v=ktYViivw27A)

Pour atteindre cette objectif nous allons procéder par phases:

## Phase 1 (Etat des lieux)
L'objectif de cette phase est d'étudier le robot en notre possession, ensuite déterminer 


1. Définir un schéma électique du robot actuel
![shémas global](images/1.png)

2. Choix des capteurs nécessaires (idéalement trouvé des cartes contenant le tout: 

	* gyroscope, acceleromètre, gps..., 
	* caméra
	* LIDAR (en option n'est pas obligatoire en première version)

	
	![](images/2.png)


3. Choix des cartes embarquées nécessaires
4. Choix des composants électroniques pour la commande des moteurs (Exemple: H-Bridge, Servo-moteur...)


	![](images/3.png)

5. Etude de l'étanchiété: l'objectif est d'avoir une vision sur comment on va protéger les composants électorniques
6. Etude les sources d'alimentation nécéssaires (batteries...). 


## Phase 2 (Vision cible)

1. Définir le shcéma électrique cible

![shémas global](images/4.png)

2. Définir le montage mécanique cible
3. Définir le schéma énergitique cible
4. Définir les interfaces de communication (communication entre capteurs et carte embarquée, communication entre moteurs et carte embarquée, communication entre carte embarquée et ordianateur distant)

![shémas global](images/5.png)
5. Phase familiarisation avec les cartes embarquées 
6. Acquisition du matériels

## Phase 3 (Réalisation)

1. Montage du bateau (énergitique, mécanique et électronique)
2. Programmation de la carte embarquée partie commande et partie acquisition des données depuis les capteurs
3. Tests unitaires
4. Tests d'intégrations

## Phase 4 (Tests)
Validation du prototype avec des tests grandeur nature.

## Sources

* Autonomous Boat - Build Log and Testing

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/uRW1qGQBFtc/0.jpg)](https://www.youtube.com/watch?v=uRW1qGQBFtc)

Notes : 

	* Dimension: 600x390 mm
	* DST-700 brushless DC motor
	* HobbyKing 20A Blue ESC
	* Taranis X9D Plus
	* FrSky V8FR-II
	* APM 2.6

*  [ARDUPILOT](http://ardupilot.org/rover/docs/parameters.html)
*  Autonomous Box Boat - Long Range Waypoint Mission - RCTESTFLIGHT

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/PlUmG3CFadw/0.jpg)](https://www.youtube.com/watch?v=PlUmG3CFadw)

Notes:



	* https://drive.google.com/file/d/17pscxfwTCLuxO1fSMs6sBwvtXfGYWXCk/view

* Boat Autopilot Project - Overview and Explaination

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/UF1n_a_od8Y/0.jpg)](https://www.youtube.com/watch?v= UF1n_a_od8Y)

Notes: [LINK](https://www.instructables.com/id/Boat-Autopilot/)



