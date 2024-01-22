# VESTA 140

**Contrôleur de relais Z-Wave PRL-8-ZW-AC**

**Introduction**

PRL-8-ZW-AC est un contrôleur de relais Z-Wave qui peut être connecté à des appareils filaires et réglé sur l'état Normal Ouvert (N.O.) ou Normal Fermé (N.C.). Après avoir rejoint le réseau Z-Wave, le contrôleur de relais peut être contrôlé via le réseau Z-Wave pour activer les appareils connectés. Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance. Le contrôleur de relais Z-Wave permet d'accéder à la classe « S2 non authentifié ».

**Identification des pièces**

**1. Bouton de fonction**

![](<.gitbook/assets/0 (53).jpeg>)

Appuyez 3 fois sur le bouton en 1,5 seconde pour envoyer un code d'apprentissage.

Appuyez et maintenez le bouton enfoncé pendant 10 secondes pour réinitialiser les paramètres d'usine.

Appuyez sur le bouton pour allumer/éteindre le relais.

**2. Indicateur LED (rouge)**

L'indicateur LED est utilisé pour indiquer l'état du relais :

-   LED allumée : relais activé
-   LED éteinte : relais éteint

**Bornes de connexion**

Connectez le fil à la borne, serrez la vis pour fermer la tondeuse et maintenez le fil en place. Dévissez pour ouvrir la tondeuse pour retirer le fil connecté à la borne.

1.  **Ligne (entrée CA)**
2.  **Neutre**
3.  **NON**

Pour une connexion normale ouverte avec l’appareil.

1.  **Commun**
2.  **NC**

Pour une connexion normale et fermée avec l'appareil

**8. Pince anti-traction**

La pince est utilisée pour fixer les fils et fournir un soulagement de traction pour protéger les fils de la découpe métallique.

**9. Boucle de câblage**

La boucle de câblage est utilisée pour gérer les fils.

**spécification**

-   Source d'alimentation (alimentation externe) : 100-240VAC
-   Sortie relais : relais SPDT sans potentiel, charge de fonctionnement maximale : 10 A (résistif) à 24 V CC ou 240 V CA.
-   Fil toronné : 14~22 AWG
-   Température de fonctionnement : -10°C à 45°C (14°F à 113°F)
-   Humidité : jusqu'à 85 % sans condensation
-   Dimensions : 86 mm x 72 mm x 29 mm

![](<.gitbook/assets/1 (45).jpeg>)

**Environnement d'installation**

-   Le contrôleur de relais doit être installé à l’intérieur dans un endroit sec.

1

-   Il est recommandé d'installer l'appareil dans un boîtier en plastique résistant au feu.
-   N'installez pas l'appareil dans une boîte métallique pour optimiser la gamme Z-Wave.

![](<.gitbook/assets/2 (41).jpeg>)

**Prudence**

-   Tous les travaux sur l'appareil, y compris l'installation et la maintenance, doivent être effectués par un électricien qualifié et agréé.
-   Pour éviter les chocs électriques et/ou les dommages à l'équipement, débranchez l'alimentation électrique au niveau du fusible principal ou du disjoncteur avant l'installation et la maintenance.

Ne connectez pas l'appareil à des charges dépassant le courant de charge pris en charge.

**Installation**

![](<.gitbook/assets/3 (38).jpeg>)

Le câblage du PRL ne doit être effectué que par un technicien certifié possédant les connaissances et la formation appropriées en matière d'équipement électrique. Câblez le relais selon les instructions ci-dessous :

1.  Coupez l'alimentation électrique avant la connexion.
2.  Retirez le capot supérieur et retirez le collier de serrage.
3.  Connectez les bornes L et N de l'alimentation électrique aux bornes de ligne et neutre du PRL respectivement à travers le trou de câblage.
4.  En fonction de l'appareil que vous souhaitez contrôler via le relais, sélectionnez la borne NO ou NC et câblez le relais avec l'appareil pour établir une connexion normale ouverte ou normale avec l'appareil.
5.  Après avoir terminé le câblage de l'appareil, remplacez le serre-câble, utilisez

la boucle de câblage pour gérer les fils, et placez la boucle de câblage sur la base avec son espace (ouverture) positionné à gauche (comme sur le schéma ci-dessous).

![](<.gitbook/assets/4 (39).jpeg>)

1.  Remplacez le capot supérieur. Allumez l’alimentation pour allumer le contrôleur de relais.

**Réseau Z-Wave**

![](<.gitbook/assets/5 (51).png>)

-   _**Ajout d'un appareil (inclusion)**_
    -   Connectez l'alimentation électrique au contrôleur de relais conformément aux instructions d'installation de la section précédente et mettez le contrôleur de relais sous tension.
    -   Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'inclusion**(veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
    -   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction.
    -   Reportez-vous au manuel d'utilisation de la passerelle Z-Wave ou du panneau de commande pour terminer le processus d'ajout.
    -   Si l'appareil a déjà été ajouté (inclus) dans une autre passerelle/panneau de configuration Z-Wave, ou si l'appareil ne peut pas être ajouté à la passerelle/panneau de configuration Z-Wave actuelle, essayez d'abord de le supprimer (voir_**Suppression d'un périphérique**_).
-   _**Suppression d'un périphérique (exclusion)**_

![](<.gitbook/assets/6 (33).png>)

L'appareil doit être supprimé du réseau Z-Wave existant avant d'être ajouté à un autre.**Mode d'exclusion**

-   Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'exclusion**(veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
-   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction et l'appareil sera supprimé du réseau Z-Wave.

**Retour aux paramètres d'usine**

2

-   -   La réinitialisation d'usine de l'appareil le restaurera aux paramètres d'usine par défaut (c'est-à-dire qu'il n'est inclus dans aucun réseau Z-Wave). Veuillez utiliser cette procédure uniquement si la passerelle ou le panneau de commande Z-Wave est perdu ou inutilisable.
    -   Appuyez et maintenez enfoncé le bouton de fonction de l'appareil pendant 10 secondes pour réinitialiser les paramètres d'usine.
-   _**Test de portée**_

![](<.gitbook/assets/7 (28).png>)

Pour tester si l'appareil est capable de communiquer avec la passerelle Z-Wave ou le panneau de commande :

-   Mettez la passerelle/le panneau en mode test de portée (Walk Test).
-   Appuyez sur le bouton de fonction de l'appareil.
-   La passerelle/le panneau doit s'afficher si l'appareil se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation de la passerelle/du panneau).

**Opération**

![](<.gitbook/assets/8 (23).jpeg>)

-   _**Contrôle des relais**_
    -   Lorsque le contrôleur de relais a rejoint avec succès un réseau Z-Wave, la passerelle/panneau de commande pourra contrôler à distance le relais pour l'allumer, l'éteindre ou basculer entre les conditions marche et arrêt. Veuillez vous référer à votre passerelle/panneau de contrôle Z-Wave pour plus de détails.

**Informations sur la vague Z**

**Type d'appareil:**Interrupteur marche/arrêt

**Type de rôle :**Toujours sur esclave (AOS)

**Prise en charge/contrôle de classe de commande**

**Support CC obligatoire :**Informations Z-Wave Plus CC

Association CC, (S2)

Association multicanal CC, (S2)

Informations sur le groupe d'association CC, (S2)

Service de transport CC

VersionCC, (S2)

CC spécifique au fabricant, (S2)

Réinitialisation de l'appareil localement CC, (S2)

Niveau de puissance CC, (S2)

Changer CC binaire

Supervision CC, (S2)

Mise à jour du micrologiciel Md CC, (S2)

-   _**Groupes de Z-Wave (classe de commande d'association version 2)**_

Le commutateur peut être configuré pour envoyer des rapports aux appareils Z-Wave associés. Il prend en charge un groupe d'association avec cinq nœuds pour le groupe 1. Pour le groupe 1, le commutateur signalera son dernier état à la passerelle/au panneau Z-Wave.

Groupe 1 pour « LifeLine » : (nœud max : 5)

Changer CC binaire (COMMANDE_CLASSE_CHANGER_BINAIRE)

Device Reset Locally CC (COMMAND_CLASSE_APPAREIL_RÉINITIALISER_LOCALEMENT)

Lors du basculement entre On/Off, il enverra un rapport de commutation binaire aux nœuds du groupe 1.

3
