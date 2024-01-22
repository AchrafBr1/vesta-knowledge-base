# VESTA 162

**PRM2-ZW-P5**

**Commutateur de relais de puissance Z-Wave avec compteur**

**Introduction**

Le commutateur de relais de puissance est capable de recevoir des signaux sans fil du coordinateur du réseau Z-Wave pour activer/désactiver les appareils qui y sont connectés.

Le commutateur de relais de puissance est un appareil compatible Z-Wave et est entièrement compatible avec tout réseau compatible Z-Wave.

Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance. En profitant du réseau maillé Z-Wave, les commandes peuvent être transmises vers leur destination via des produits Z-Wave « d’écoute » intermédiaires.

Le PRM2-ZW-P5 a la fonctionnalité supplémentaire de suivre la consommation d'énergie grâce au compteur d'énergie intégré et de transmettre régulièrement les données au coordinateur.

PRM2-ZW-P5 sert également de routeur dans le réseau Z-Wave. Après avoir été inclus dans le réseau Z-Wave, il permet à d'autres appareils Z-Wave de rejoindre le réseau via l'interrupteur d'alimentation.

**Identification des pièces**

![](<.gitbook/assets/0 (57).jpeg>)

**1. Indicateur LED**

L'indicateur LED est utilisé pour indiquer l'état du commutateur de relais de puissance :

-   -   Sur:

Le commutateur du relais de puissance est activé.

-   -   Désactivé:

Le commutateur du relais de puissance est éteint.

1.  **Bouton de fonction**

Le bouton de fonction est utilisé pour contrôler le commutateur de relais de puissance :

**Utilisation du bouton de fonction :**

-   -   Appuyez sur le bouton pour activer/désactiver le commutateur de relais de puissance.
    -   Appuyez sur le bouton 3 fois en 1,5 seconde pour ajouter/supprimer du réseau Z-Wave.
    -   Appuyez et maintenez le bouton enfoncé pendant 10 secondes pour réinitialiser les paramètres d'usine.

1.  **Borne 1 du commutateur externe**
2.  **Borne 2 du commutateur externe**
3.  **Entrée d'alimentation secteur CA**
4.  **Entrée de puissance neuronale CA**
5.  **Sortie de charge de puissance neutre CA**
6.  **Sortie de charge de puissance de ligne CA**

**Opération**

-   _**Schéma de connexion des fils**_
    -   Reportez-vous au schéma pour connecter vos appareils au commutateur de relais de puissance.
-   _**Installation**_

![](<.gitbook/assets/1 (51).jpeg>)

**Étape 1:**Coupez l'alimentation électrique du câble d'alimentation pour des raisons de sécurité et pour vous assurer que le fil ne court-circuitera pas pendant le processus d'installation.

**Étape 2:**Connectez le câble d'alimentation d'entrée CA au connecteur d'entrée et le câble d'alimentation de sortie au connecteur de sortie.

**Étape 3:**Pour la connexion d'un commutateur externe, connectez le commutateur à la commande de commutateur externe.

**Étape 4:**Une fois le câblage terminé, rétablissez l’alimentation électrique du câble d’alimentation.

1

-   _**Ajout d'un appareil (inclusion)**_

Ce produit peut être inclus et utilisé dans n'importe quel réseau Z-Wave avec d'autres appareils certifiés Z-Wave d'autres fabricants et/ou d'autres applications. Tous les nœuds non alimentés par batterie du réseau agiront comme répéteurs, quel que soit le fournisseur, afin d'augmenter la fiabilité du réseau.

-   -   Connectez le commutateur de relais de puissance au câble d'alimentation.
    -   Mettez la passerelle Z-Wave ou le panneau de commande dans**Inclusion**ou**Apprentissage**mode (veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
    -   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction.
    -   Reportez-vous au manuel d'utilisation de la passerelle Z-Wave ou du panneau de commande pour terminer le processus d'apprentissage.
    -   Si le capteur a déjà été**inclus**(appris) dans une autre passerelle/panneau de commande Z-Wave, ou si le capteur ne peut pas être appris dans la passerelle/panneau de commande Z-Wave actuelle, veuillez d'abord l'exclure (voir_**Exclusion**_) avant de tenter de**inclure**dans la passerelle/panneau de configuration Z-Wave actuelle.
-   _**Suppression d'un périphérique (exclusion)**_

Le commutateur de relais de puissance doit être retiré du réseau Z-Wave existant avant d'être inclus dans un autre. Il existe deux méthodes disponibles pour exclure un appareil.

**Mode d'exclusion**

-   Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'exclusion**(veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
-   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction et le commutateur de relais de puissance sera supprimé du réseau Z-Wave.

**Retour aux paramètres d'usine**

_(Utilisez la réinitialisation d'usine uniquement lorsque le panneau de configuration/passerelle réseau est manquant ou inutilisable)._

-   -   Appuyez et maintenez le bouton de fonction pendant 10 secondes pour réinitialiser les paramètres d'usine.

_\\<NOTE>_

-   -   -   La réinitialisation d'usine du commutateur de relais de puissance le restaurera aux paramètres d'usine par défaut (exclus du réseau Z-Wave). La passerelle ou le panneau de commande Z-Wave conservera toujours ses paramètres Z-Wave. Veuillez vous référer au manuel de la passerelle ou du panneau de commande pour savoir comment supprimer les paramètres Z-Wave du commutateur de relais de puissance.
-   _**Test de portée**_

Pour tester si l'appareil est capable de communiquer avec la passerelle Z-Wave ou le panneau de commande :

-   -   -   Mettez la passerelle/le panneau en mode test de portée (Walk Test).
        -   Appuyez sur le bouton de fonction de l'appareil.
        -   La passerelle/le panneau doit s'afficher si l'appareil se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation de la passerelle/du panneau).
-   _**Contrôle des appareils**_
    -   Une fois que le commutateur de relais de puissance a rejoint avec succès un réseau Z-Wave, le coordinateur peut allumer/éteindre l'appareil à distance.
    -   Vous pouvez également appuyer sur le bouton du commutateur de relais de puissance pour allumer/éteindre la lumière.
    -   Vous pouvez allumer/éteindre le commutateur de relais de puissance avec un interrupteur externe.
    -   Si vous avez lié un contrôleur au commutateur de relais de puissance, vous pouvez également utiliser le contrôleur pour allumer/éteindre le commutateur de relais de puissance.
    -   Si l'entrée d'alimentation CA est déconnectée du commutateur de relais de puissance, son état marche/arrêt précédent sera restauré dans la minute qui suit la reconnexion de l'entrée d'alimentation CA au commutateur de relais de puissance.
-   _**Moniteur de consommation d'énergie**_
    -   Le commutateur de relais de puissance transmettra un signal avec ses données de consommation d'énergie toutes les minutes au coordinateur du réseau Z-Wave.
    -   Chaque fois que la production d'énergie du commutateur d'alimentation change de +/- 2 W, il transmettra automatiquement un signal avec les données de consommation d'énergie au coordinateur du réseau Z-Wave pour mise à jour.
    -   Le commutateur d'alimentation transmet un signal avec les données d'alimentation au coordinateur chaque fois que la consommation d'énergie accumulée augmente de 0,1 kW/h.
    -   Le compteur a une précision de +/- 5%.
    -   2 méthodes pour effacer le commutateur de relais de puissance de ses données de consommation d'énergie accumulées :
        -   1.  Utilisez la classe de commande de réinitialisation du compteur.
            2.  Exécutez la réinitialisation d'usine. Appuyez et maintenez le bouton de fonction pendant 10 secondes.

_\\<NOTE>_

-   Si vous exécutez la réinitialisation d'usine, l'appareil sera supprimé du réseau Z-wave. Vous devez l'inclure à nouveau. Pour les instructions d’inclusion, veuillez vous référer à la section de_**Ajout d'un appareil (inclusion)**._

2

-   _**Charge de fonctionnement maximale**_
    -   Pour 110 V : la charge de fonctionnement maximale est de 1 100 W et 10 A.
    -   Pour 230 V : la charge de fonctionnement maximale est de 2 300 W et 10 A.
    -   Si le commutateur du relais de puissance surchauffe, il coupera automatiquement l'alimentation par mesure de sécurité. L'utilisateur doit déconnecter et reconnecter l'alimentation CA au commutateur de relais de puissance après la coupure pour reprendre un fonctionnement normal.
-   _**Informations sur la vague Z**_

**Type d'appareil:**Interrupteur marche/arrêt

**Type de rôle :**Toujours sur esclave (AOS)

**Prise en charge/contrôle de classe de commande**

**Support CC obligatoire :**Association CC, v2 ou plus récente

Informations sur le groupe d'association CC

Compteur CC, v2

CC de base

Commutateur binaire CC

Réinitialisation de l'appareil localement CC

CC spécifique au fabricant

Niveau de puissance CC

Version CC, v2 ou plus récente

Informations Z-Wave Plus CC

**Prise en charge CC recommandée :**Métadonnées de mise à jour du micrologiciel CC

-   _**Groupes de Z-Wave (classe de commande d'association version 2)**_

Le commutateur peut être configuré pour envoyer des rapports aux appareils Z-Wave associés. Il prend en charge un groupe d'association avec cinq nœuds pour le groupe 1. Pour le groupe 1, le commutateur signalera son dernier état à la passerelle/au panneau Z-Wave.

Le groupe 1 comprend :

Commutateur binaire CC (COMMUTATEUR_BINAIRE_RAPPORT)

Compteur CC, v2 (METRE_RAPPORT_COMMANDE)

Réinitialisation du périphérique localement CC (COMMANDE_CLASSE_APPAREIL_RÉINITIALISER_LOCALEMENT)

-   Rapport automatique au groupe 1 (nœud maximum 5)
-   Rapport d'événement marche/arrêt

Lors du basculement entre On/Off, il enverra un rapport de commutation binaire aux nœuds du groupe 1.

3
