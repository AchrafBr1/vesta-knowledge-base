# VESTA 259

**Compteur de puissance sur rail DIN (série PSM-DIN2-ZW)**

![](<.gitbook/assets/0 (97).jpeg>)

L'interrupteur d'alimentation est capable de recevoir des signaux sans fil du coordinateur du réseau Z-Wave pour allumer/éteindre les appareils qui y sont connectés. Le Power Switch permet également de suivre la consommation d'énergie grâce au compteur d'énergie intégré et de transmettre régulièrement les données au réseau Z-Wave.

Le Power Switch est un appareil compatible Z-Wave et est entièrement compatible avec tout réseau compatible Z-Wave.

Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance. En profitant du réseau maillé Z-Wave, les commandes peuvent être transmises vers leur destination via des produits Z-Wave intermédiaires « d’écoute ».

![](<.gitbook/assets/1 (81).jpeg>)

La série PSM-DIN2-ZW comprend les modèles suivants :

PSM-DIN2-ZW

PSM-DIN2-ZW-OTA

![](<.gitbook/assets/2 (75).png>)![](<.gitbook/assets/3 (68).jpeg>)

-   _**Identifier les pièces**_
    1.  **Connecteur d'entrée**
    2.  **Connecteur de sortie**
    3.  **Port d'antenne externe**
    4.  **Indicateur LED**
    5.  **Bouton de fonction**

\-Appuyez sur le bouton de fonction 3 fois en 1,5 seconde pour envoyer un code d'apprentissage.

\-Appuyez et maintenez enfoncé pendant 10 secondes pour réinitialiser les paramètres d'usine.

![](<.gitbook/assets/4 (78).png>)

-   _**Indicateur LED**_
    -   Allumé : sous tension
    -   Éteint : mise hors tension
    -   Le voyant rouge clignote deux fois : 1. L'interrupteur d'alimentation vient d'être allumé,_ou_
        1.  L'interrupteur d'alimentation vient d'être réinitialisé aux paramètres d'usine.
-   _**Prudence**_
    -   Tous les travaux sur l'appareil, y compris l'installation et la maintenance, doivent être effectués par un électricien qualifié et agréé.
    -   Avant l'installation ou tout travail de maintenance, assurez-vous que l'alimentation électrique a été débranchée.
    -   Ne connectez pas l'appareil à des charges dépassant le courant de charge pris en charge.
-   _**Câblage et installation**_

![](<.gitbook/assets/5 (78).png>)![](<.gitbook/assets/6 (58).png>)

**Avant l'installation, assurez-vous que l'alimentation électrique a été débranchée.**

![](<.gitbook/assets/7 (46).jpeg>)

-   -   Connectez la borne L du connecteur d'entrée à la borne L de l'alimentation, veuillez utiliser un fusible pour le fil. Connectez la borne N du connecteur d'entrée à la borne N de l'alimentation.
    -   Connectez la borne N du connecteur de sortie à la borne N du périphérique externe et connectez la borne L du connecteur de sortie à la borne L du périphérique externe.
    -   Connectez l'antenne externe au port d'antenne externe.
    -   Montez l'appareil à l'intérieur du boîtier électrique à l'aide d'un rail DIN.
-   _**Inclusion (ajout ou dispositif d'apprentissage)**_

![](<.gitbook/assets/8 (53).png>)

Ce produit peut être inclus et utilisé dans n'importe quel réseau Z-Wave avec d'autres appareils certifiés Z-Wave d'autres fabricants et/ou d'autres applications. Tous les nœuds non alimentés par batterie du réseau agiront comme répéteurs, quel que soit le fournisseur, afin d'augmenter la fiabilité du réseau.

-   Allumez l’appareil en allumant l’alimentation externe.
-   Mettez la passerelle Z-Wave ou le panneau de commande dans**Inclusion**ou**Apprentissage**mode (veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
-   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction.
-   Reportez-vous au manuel d'utilisation de la passerelle Z-Wave ou du panneau de commande pour terminer le processus d'ajout.

1

-   -   Si l'appareil a déjà été ajouté (inclus) dans une autre passerelle/panneau de configuration Z-Wave, ou si l'appareil ne peut pas être ajouté à la passerelle/panneau de configuration Z-Wave actuelle, veuillez d'abord l'exclure (voir_**Exclusion**_) avant d'essayer de l'inclure dans la passerelle/panneau de configuration Z-Wave actuel.
-   _**Exclusion (suppression d'un périphérique)**_

![](<.gitbook/assets/9 (49).png>)

L'appareil doit être supprimé du réseau Z-Wave existant avant d'être inclus dans un autre. Il existe deux méthodes disponibles pour exclure un appareil.

**Mode d'exclusion**

-   Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'exclusion**(veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
-   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction et l'appareil sera supprimé du réseau Z-Wave.

**Retour aux paramètres d'usine**

_(Utilisez la réinitialisation d'usine uniquement lorsque le panneau de configuration/passerelle réseau est manquant ou inutilisable)._

-   -   Appuyez et maintenez enfoncé le bouton de fonction de l'appareil pendant 10 secondes pour réinitialiser les paramètres d'usine.

_\\<NOTE>_

-   -   -   La réinitialisation d'usine de l'appareil le restaurera aux paramètres d'usine par défaut (exclus du réseau Z-Wave). La passerelle ou le panneau de configuration Z-Wave conservera toujours ses paramètres Z-Wave. Veuillez vous référer au manuel de la passerelle ou du panneau de commande pour savoir comment supprimer les paramètres Z-Wave de l'appareil.
        -   La réinitialisation d'usine de l'appareil effacera également toutes les données d'alimentation accumulées.
-   _**Test de portée**_

![](<.gitbook/assets/10 (51).png>)![](<.gitbook/assets/11 (41).png>)

Pour tester si l'appareil est capable de communiquer avec la passerelle Z-Wave ou le panneau de commande :

-   -   -   Mettez la passerelle/le panneau en mode test de portée (Walk Test).
        -   Appuyez sur le bouton de fonction de l'appareil.
        -   La passerelle/panneau doit s'afficher si l'appareil se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation de la passerelle/panneau).
-   _**Opération**_
    -   Après avoir été inclus dans une passerelle ou un panneau de commande Z-Wave, branchez un appareil électroménager sur l'interrupteur d'alimentation. Les données de consommation d’énergie et d’énergie de cet appareil électroménager seront transférées au panneau de commande.
    -   Appuyer sur le bouton de l'interrupteur d'alimentation peut également allumer/éteindre l'interrupteur d'alimentation.
    -   Allumez/éteignez l'appareil électrique à distance via le panneau de commande (veuillez vous référer au manuel de votre panneau de commande).
    -   Si la puissance de sortie est inférieure à 1 kW, le PSM-DIN2 transmettra un signal à la passerelle/au panneau Z-Wave lorsque la puissance dévie de +/- 2 W pour mettre à jour les informations d'alimentation du PSM-DIN2.

Si la puissance de sortie est supérieure à 1 kW, le PSM-DIN2 transmettra un signal à la passerelle/au panneau Z-Wave lorsque la puissance dévie de +/- 5 W pour mettre à jour les informations d'alimentation du PSM-DIN2.

-   -   PSM-DIN2 transmet un signal avec des données d'alimentation à la passerelle/panneau de commande Z-Wave toutes les 10 minutes à partir de la dernière fois qu'un signal est transmis.
    -   L'interrupteur d'alimentation transmet un signal avec des données d'alimentation à la passerelle/au panneau de commande Z-Wave chaque fois que la consommation d'énergie augmente de 0,1 kW/h.
    -   Si l'alimentation de l'interrupteur d'alimentation est reconnectée après une déconnexion précédente, l'état marche/arrêt précédent de l'interrupteur d'alimentation reprendra immédiatement.
    -   Lorsque la puissance est inférieure à 20 W, une erreur de mesure est plus susceptible de se produire.
-   _**Spécification de puissance**_
    -   Pour**110V :**la charge de fonctionnement maximale est de 1760 W et 16 A. Attention : veuillez ne pas dépasser la charge maximale.
    -   Pour**230V :**la charge de fonctionnement maximale est de 3680 W et 16 A. Attention : veuillez ne pas dépasser la charge maximale.
-   _**Informations sur la vague Z**_

![](<.gitbook/assets/12 (43).png>)![](<.gitbook/assets/13 (32).png>)![](<.gitbook/assets/14 (31).png>)

**Type d'appareil:**Type générique de commutateur binaire

**Type de rôle :**Toujours sur esclave (AOS)

**Type de produit:**0x0004

**Identifiant du produit :**0x0003

**Prise en charge/contrôle de classe de commande**

**Prise en charge CC obligatoire :**Informations Z-Wave Plus CC

Association CC ,(S2)

Association multicanal CC, (S2)

Informations sur le groupe d'association CC, (S2)

Service de transport CC

VersionCC,(S2)

CC spécifique au fabricant, (S2)

Réinitialisation de l'appareil localement CC, (S2)

Niveau de puissance CC, (S2)

2

Compteur CC, v2

Changer CC binaire

Supervision CC,(S2)

Mise à jour du micrologiciel Md CC, (S2)

![](<.gitbook/assets/15 (31).png>)

-   _**Groupes de Z-Wave (classe de commande d'association version 2)**_

Le commutateur peut être configuré pour envoyer des rapports aux appareils Z-Wave associés. Il prend en charge un groupe d'association avec cinq nœuds pour le groupe 1. Pour le groupe 1, le commutateur signalera son dernier état à la passerelle/au panneau Z-Wave. Groupe 1 pour « LifeLine » : (nœud max : 5)

Changer CC binaire (COMMANDE_CLASS_CHANGER_BINAIRE)

Compteur CC (COMMANDE_CLASSE_MÈTRE)

Réinitialisation du périphérique localement CC (COMMANDE_CLASSE_APPAREIL_RÉINITIALISER_LOCALEMENT)

-   Rapport automatique au groupe 1 (nœud maximum 5)
-   Rapport d'événement marche/arrêt

Lors du basculement entre On/Off, il enverra un rapport de commutation binaire aux nœuds du groupe 1.

-   Retour aux paramètres d'usine

Lorsque l'interrupteur d'alimentation est réinitialisé aux paramètres d'usine par défaut, il enverra une réinitialisation locale de l'appareil à tous les nœuds du groupe 1.

-   Rapport du compteur :
    -   Si la puissance de sortie est inférieure à 1 kW, le PSM-DIN2 transmettra un signal à la passerelle/au panneau Z-Wave lorsque la puissance dévie de +/- 2 W pour mettre à jour les informations d'alimentation du PSM-DIN2.
    -   Si la puissance de sortie est supérieure à 1 kW, le PSM-DIN2 transmettra un signal à la passerelle/au panneau Z-Wave lorsque la puissance dévie de +/- 5 W pour mettre à jour les informations d'alimentation du PSM-DIN2.
    -   PSM-DIN2 transmet un signal avec des données d'alimentation à la passerelle/panneau de commande Z-Wave toutes les 10 minutes à partir de la dernière fois qu'un signal est transmis.
    -   L'interrupteur d'alimentation transmet un signal avec des données d'alimentation à la passerelle/au panneau de commande Z-Wave chaque fois que la consommation d'énergie augmente de 0,1 kW/h.
    -   Format des données :

Exemple 1:**41 64 00 00 50 14**FF FF**00 00 00 00**kWh (00005014 = 20500 = 20,5)

-   -   -   Valeur actuelle:**41 64 00 00 50 14**
        -   Valeur précédente :**00 00 00 00**

Exemple 2 :**41 74 00 00 27 10**FF FF**00 00 00 00**W (00002710 = 10 000 = 10 W)

-   Valeur actuelle:**41 74 00 00 27 10**
-   Valeur précédente :**00 00 00 00**

3
