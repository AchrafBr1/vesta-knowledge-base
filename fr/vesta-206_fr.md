# VESTA 206

**Interrupteur à bascule de relais Z-Wave PRL-3ZW-AC**

**Introduction**

PRL-3ZW-AC est un interrupteur à bascule de relais Z-Wave. L'interrupteur à bascule de relais peut être connecté à un appareil filaire et réglé sur l'état Normal Ouvert (N.O.). Après avoir rejoint le réseau Z-Wave, le commutateur à bascule de relais peut être contrôlé via le réseau Z-Wave pour activer les appareils connectés.

Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance. En profitant du réseau maillé Z-Wave, les commandes peuvent être acheminées vers leur destination via des produits Z-Wave intermédiaires « d’écoute ».

Le relais peut contrôler les nœuds Z-Wave en appuyant simplement sur le bouton de fonction et peut également vous alerter des problèmes de communication.

La série d'interrupteurs à bascule de relais Z-Wave comprend les modèles suivants :

PRL-3ZW-AC

PRL-xZO-AS-OTA

**Identification des pièces**

![](<.gitbook/assets/0 (84).jpeg>)

**1. Indicateur LED**

L'indicateur LED est utilisé pour indiquer l'état du relais :

-   -   LED allumée : relais activé
    -   LED éteinte : relais éteint

1.  **Bouton de fonction**

Appuyez 3 fois sur le bouton en 1,5 seconde pour envoyer un code d'apprentissage.

Appuyez et maintenez le bouton enfoncé pendant 10 secondes pour réinitialiser les paramètres d'usine.

Appuyez sur le bouton pour allumer/éteindre le relais.

**Bornes de connexion**

Connectez le fil à la borne, serrez la vis pour fermer la tondeuse et maintenez le fil en place. Dévissez pour ouvrir la tondeuse pour retirer le fil connecté à la borne.

1.  **Neutre**
2.  **Ligne (entrée CA)**

Pour alimenter le PRL-3ZW, connectez les bornes L&N de l'alimentation aux bornes L&N.

**5. NON**

Pour une connexion normale ouverte avec l'appareil

**6. Commun**

Connectez les bornes NO & COM de l'appareil filaire aux bornes NO & COM du PRL-3ZW.

**spécification**

-   Source d'alimentation (alimentation externe) : 100-240VAC
-   Sortie relais : relais SPDT sans potentiel, charge de fonctionnement maximale : 5 A (résistif) à 24 V CC ou 240 V CA.
-   Fil toronné : 14~22 AWG
-   Température de fonctionnement : -10°C à 45°C (14°F à 113°F)
-   Humidité : jusqu'à 85 % sans condensation
-   Dimensions : 71 mm x 49 mm x 26 mm

![](<.gitbook/assets/1 (73).jpeg>)

**Environnement d'installation**

-   L'interrupteur à bascule du relais doit être installé à l'intérieur dans un endroit sec.
-   Il est recommandé d'installer l'appareil dans un boîtier en plastique résistant au feu.
-   N'installez pas l'appareil dans une boîte métallique pour optimiser la gamme Z-Wave.

1

![](<.gitbook/assets/2 (69).jpeg>)

**Prudence**

-   Tous les travaux sur l'appareil, y compris l'installation et la maintenance, doivent être effectués par un électricien qualifié et agréé.
-   Pour éviter les chocs électriques et/ou les dommages à l'équipement, débranchez l'alimentation électrique au niveau du fusible principal ou du disjoncteur avant l'installation et la maintenance.
-   Ne connectez pas l'appareil à des charges dépassant

![](<.gitbook/assets/3 (62).jpeg>)

Courant de charge pris en charge.

**Installation**

Câblez le relais selon les instructions ci-dessous ou reportez-vous au schéma pour plus d'informations.

1.  Veuillez éteindre l'alimentation avant la connexion.
2.  Connectez les bornes L et N de l'alimentation électrique aux bornes Ligne et Neutre du PRL respectivement.
3.  En fonction de l'appareil que vous souhaitez contrôler via le relais, sélectionnez la borne NO et câblez le relais avec l'appareil pour établir une connexion normale ouverte avec l'appareil.
4.  Une fois le câblage terminé, mettez sous tension pour allumer l'interrupteur à bascule du relais.

![](<.gitbook/assets/4 (68).png>)

_\\<IMPORTANT NOTE>_

-   Le câblage du PRL ne doit être effectué que par un technicien certifié possédant les connaissances et la formation appropriées en matière d'équipement électrique.

**Caractéristiques**

![](<.gitbook/assets/5 (70).png>)

-   _**Ajout d'un appareil (inclusion)**_
    -   Connectez l'entrée d'alimentation à l'interrupteur à bascule de relais conformément aux instructions d'installation ci-dessus et mettez l'interrupteur à bascule de relais sous tension.
    -   Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'inclusion**(veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
    -   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction.
    -   Reportez-vous au manuel d'utilisation de la passerelle Z-Wave ou du panneau de commande pour terminer le processus d'ajout.
    -   Si l'appareil a déjà été ajouté (inclus) dans une autre passerelle/panneau de configuration Z-Wave, ou si l'appareil ne peut pas être ajouté à la passerelle/panneau de configuration Z-Wave actuelle, essayez d'abord de le supprimer (voir_**Suppression d'un périphérique**_).
-   _**Suppression d'un périphérique (exclusion)**_

![](<.gitbook/assets/6 (49).png>)

L'appareil doit être supprimé du réseau Z-Wave existant avant d'être ajouté à un autre.**Mode d'exclusion**

-   Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'exclusion**(veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
-   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction et l'appareil sera supprimé du réseau Z-Wave.

**Retour aux paramètres d'usine**

-   -   La réinitialisation d'usine de l'appareil le restaurera aux paramètres d'usine par défaut (c'est-à-dire qu'il n'est inclus dans aucun réseau Z-Wave). Veuillez utiliser cette procédure uniquement si la passerelle ou le panneau de commande Z-Wave est perdu ou inutilisable.
    -   Appuyez et maintenez enfoncé le bouton de fonction de l'appareil pendant 10 secondes pour réinitialiser les paramètres d'usine.
-   _**Test de portée**_

![](<.gitbook/assets/7 (45).png>)

Pour tester si l'appareil est capable de communiquer avec la passerelle Z-Wave ou le panneau de commande :

-   Mettez la passerelle/le panneau en mode test de portée (Walk Test).
-   Appuyez sur le bouton de fonction de l'appareil
-   La passerelle/le panneau doit s'afficher si l'appareil se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation de la passerelle/du panneau).

2

**Opération**

![](<.gitbook/assets/8 (40).jpeg>)

-   _**Contrôle des relais**_
    -   Une fois l'interrupteur à bascule du relais ajouté avec succès à un réseau Z-Wave, la passerelle/panneau de commande peut contrôler à distance le relais pour l'allumer, l'éteindre ou basculer entre les conditions marche et arrêt. Veuillez vous référer à votre passerelle/panneau de commande Z-Wave pour plus de détails.

**Informations sur la vague Z**

**Type d'appareil:**Interrupteur marche/arrêt

**Type de rôle :**Toujours sur esclave (AOS)

**Prise en charge/contrôle de classe de commande**

**Support CC obligatoire :**Association CC, v2 ou plus récente

Informations sur le groupe d'association CC

CC de base

Commutateur binaire CC

Réinitialisation de l'appareil localement CC

CC spécifique au fabricant

Niveau de puissance CC

Version CC, v2 ou plus récente

Informations Z-Wave Plus CC

**Prise en charge CC recommandée**: Mise à jour du micrologiciel Métadonnées CC

![](<.gitbook/assets/9 (41).png>)

-   _**Groupes de Z-Wave (classe de commande d'association version 2)**_

Le commutateur peut être configuré pour envoyer des rapports aux appareils Z-Wave associés. Il prend en charge un groupe d'association avec cinq nœuds pour le groupe 1. Pour le groupe 1, le commutateur signalera son dernier état à la passerelle/au panneau Z-Wave.

Groupe 1 pour « LifeLine » :

Commutateur binaire CC (COMMUTATEUR_BINAIRE_RAPPORT)

Réinitialisation du périphérique localement CC (COMMANDE_CLASSE_APPAREIL_RÉINITIALISER_LOCALEMENT)

-   Rapport automatique au groupe 1 (nœud maximum 5)
-   Rapport d'événement marche/arrêt

Lors du basculement entre On/Off, il enverra un rapport de commutation binaire aux nœuds du groupe 1.

3
