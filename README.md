# Turtlebot-Project
Projet Robotique &amp; Domotique Communicantes (groupe de 4 etudiants)

Le but du projet de RDC est de rendre le robot communicant avec l’environnement dans lequel il évolue  en  se  basant  sur  deux  technologies  de  communication:  IEEE  802.11  (Wi-Fi)  et  IEEE 802.15.4 (ZigBee).  

Chaque robot sera équipé d’un netbook connecté en Wi-Fi et également d’une puce ZigBee interfacée via le netbook du robot grâce à un contrôleur Arduino branché en USB.  

En plus  du  robot,  plusieurs  contrôleurs  Arduino  Mega  équipés  de  puce  ZigBee,  de  capteurs  et/ou
d’actionneurs seront disséminés dans l’environnement afin de simuler divers objets communicants
(ampoule, serrures de portes, détecteur de fumée). 

Enfin, une interface web permettra de suivre le déplacement du robot sur la carte et de visualiser les différents états (mode programmé, mode événementiel).

Afin de créer un environnement pour le robot, nous avons effectué un mapping de la salle en lançant le SLAM avec Gmapping, ainsi nous avons obtenus deux fichiers utiles pour la suite :   
mapi5new.pgm et mapi5new.yaml.

Le fichier exemple_move_base.py permet au robot d'atteindre trois checkpoints les uns apres les autres sur la map associee.  
Ajout d'informations sur le niveau de batterie du robot et du netbook. 
