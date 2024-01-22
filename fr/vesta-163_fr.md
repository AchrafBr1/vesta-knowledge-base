# VESTA 163

**PRS5-P5-ZW**

**Commutateur de relais de puissance Z-Wave**

**Introduction**

Le commutateur de relais de puissance est capable de recevoir des signaux sans fil du coordinateur du réseau Z-Wave pour activer/désactiver les appareils qui y sont connectés.

Le commutateur de relais de puissance est un appareil compatible Z-Wave et est entièrement compatible avec tout réseau compatible Z-Wave.

Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance. En profitant du réseau maillé Z-Wave, les commandes peuvent être transmises vers leur destination via des produits Z-Wave intermédiaires « d’écoute ».

PRS5-P5-ZW sert également de routeur dans le réseau Z-Wave. Après avoir été inclus dans le réseau Z-Wave, il permet à d'autres appareils Z-Wave de rejoindre le réseau via l'interrupteur d'alimentation.

**Identification des pièces**

![](<.gitbook/assets/0 (58).jpeg>)

**1. Indicateur LED**

L'indicateur LED est utilisé pour indiquer l'état du commutateur de relais de puissance :

-   -   Sur:

Le commutateur du relais de puissance est activé.

-   -   Désactivé:

Le commutateur du relais de puissance est éteint.

-   -   Clignote deux fois :

Le commutateur de relais de puissance a été ajouté avec succès au réseau Z-Wave.

-   -   Clignote trois fois

Le commutateur de relais de puissance s'est lié avec succès à un contrôleur.

-   -   Clignote cinq fois

Le commutateur de relais de puissance n'a pas pu se lier à un contrôleur.

1.  **Bouton de fonction**

Le bouton de fonction est utilisé pour contrôler le commutateur de relais de puissance :

**Utilisation du bouton de fonction :**

-   -   Appuyez sur le bouton pour activer/désactiver le commutateur de relais de puissance.
    -   Appuyez 3 fois sur le bouton en 1,5 seconde pour envoyer un code d'apprentissage.
    -   Appuyez et maintenez le bouton pendant 3 secondes puis relâchez pour vous lier à un contrôleur
    -   Appuyez et maintenez le bouton enfoncé pendant 10 secondes pour réinitialiser les paramètres d'usine.

1.  **Câble de connexion du commutateur externe 1 (rouge)**
2.  **Câble de connexion du commutateur externe 2 (Orange)**
3.  **Sortie de charge de puissance de ligne CA (jaune)**
4.  **Entrée d'alimentation neuronale CA/sortie de charge de puissance neutre CA (bleu)**
5.  **Entrée d'alimentation secteur CA (marron)**

**Prudence**

-   Tous les travaux sur l'appareil, y compris l'installation et la maintenance, doivent être effectués par un électricien qualifié et agréé.
-   Avant l'installation ou tout travail de maintenance, assurez-vous que l'alimentation électrique a été débranchée.
-   Ne connectez pas l'appareil à des charges dépassant le courant de charge pris en charge.

**Installation**

-   _**Câblage avec connecteur d'épissure**_
    -   Le commutateur de relais de puissance est livré avec un câble intégré pour la connexion à l'alimentation secteur, à l'appareil et au commutateur externe. Cinq connecteurs d'épissure Wago 221 sont fournis pour la connexion.
    -   Les connecteurs à 2 fils/3 fils acceptent les fils solides et toronnés de 0,2 à 4 mm² (24 à 12 AWG).
    -   Avant le câblage, assurez-vous que l'alimentation est coupée. Pour connecter les fils :

1

1.  Soulevez le levier et insérez le fil marron.**(Photo 1, 2)**

![](<.gitbook/assets/1 (52).png>)

**Image 1****Image 2**

1.  Repoussez le levier vers le bas. Le boîtier transparent vous permet de vérifier si le fil est correctement connecté. Assurez-vous que le fil est bien maintenu en place et ne se détachera pas.**(Photo 3, 4)**

![](<.gitbook/assets/2 (56).png>)

|                                                          | **Image 3**                              | **Image 4** |   |
| -------------------------------------------------------- | ---------------------------------------- | ----------- | - |
| 3) De la même manière qu'aux étapes 1 et 2, insérez dans | un autre pôle le fil pour se connecter à |             |   |
| Entrée d'alimentation de ligne CA.**(Photo 5)**          |                                          |             |   |
|                                                          |                                          |             |   |
|                                                          |                                          |             |   |

![](<.gitbook/assets/3 (43).jpeg>)

**Image 5**

1.  Répétez les étapes 1, 2 et 3 pour connecter les autres fils avec des connecteurs.

Veuillez noter que le fil bleu doit être connecté à un connecteur à 3 fils, puis connecté à l'entrée d'alimentation neuronale CA et à la sortie de charge de puissance neutre CA.**(Photo 6)**

![](<.gitbook/assets/4 (56).png>)

**Image 6**

**Configuration du réseau Z-Wave**

-   _**Ajout d'un appareil (inclusion)**_

Ce produit peut être inclus et utilisé dans n'importe quel réseau Z-Wave avec d'autres appareils certifiés Z-Wave d'autres fabricants et/ou d'autres applications. Tous les nœuds non alimentés par batterie du réseau agiront comme répéteurs, quel que soit le fournisseur, afin d'augmenter la fiabilité du réseau.

-   Connectez le commutateur de relais de puissance au câble d'alimentation.
-   Le commutateur de relais de puissance émettra un bip à 2 tons.
-   Mettez la passerelle Z-Wave ou le panneau de commande dans**Inclusion**ou**Apprentissage**mode (veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).

2

-   -   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction. Le commutateur de relais de puissance émettra un bip à 2 tons.
    -   Reportez-vous au manuel d'utilisation de la passerelle Z-Wave ou du panneau de commande pour terminer le processus d'apprentissage.
    -   Si le capteur a déjà été**inclus**(appris) dans une autre passerelle/panneau de commande Z-Wave, ou si le capteur ne peut pas être appris dans la passerelle/panneau de commande Z-Wave actuelle, veuillez d'abord l'exclure (voir_**Exclusion**_) avant de tenter de**inclure**dans la passerelle/panneau de configuration Z-Wave actuelle.
-   _**Suppression d'un périphérique (exclusion)**_

Le commutateur de relais de puissance doit être retiré du réseau Z-Wave existant avant d'être inclus dans un autre. Il existe deux méthodes disponibles pour exclure un appareil.

**Mode d'exclusion**

-   Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'exclusion**(veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
-   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction et le commutateur de relais de puissance sera supprimé du réseau Z-Wave.

**Retour aux paramètres d'usine**

_(Utilisez la réinitialisation d'usine uniquement lorsque le panneau de configuration/passerelle réseau est manquant ou inutilisable)._

-   -   Appuyez et maintenez enfoncé le bouton de fonction pendant 10 secondes pour réinitialiser les paramètres d'usine.

_\\<NOTE>_

-   -   -   La réinitialisation d'usine du commutateur de relais de puissance le restaurera aux paramètres d'usine par défaut (exclus du réseau Z-Wave). La passerelle ou le panneau de commande Z-Wave conservera toujours ses paramètres Z-Wave. Veuillez vous référer au manuel de la passerelle ou du panneau de commande pour savoir comment supprimer les paramètres Z-Wave du commutateur de relais de puissance.
-   _**Test de portée**_

Pour tester si l'appareil est capable de communiquer avec la passerelle Z-Wave ou le panneau de commande :

-   -   Mettez la passerelle/le panneau en mode test de portée (Walk Test).
    -   Appuyez sur le bouton de fonction de l'appareil.
    -   La passerelle/le panneau doit s'afficher si l'appareil se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation de la passerelle/du panneau).
-   _**Mode veille Z-Wave**_
    -   Le commutateur de relais d'alimentation entrera en mode veille Z-Wave (pour économiser l'énergie) après une courte période de réveil (~10 secondes). En mode veille Z-Wave, les passerelles ou panneaux de commande Z-Wave ne peuvent pas envoyer de commandes au commutateur de relais de puissance.
    -   Pour programmer le commutateur de relais de puissance, veuillez envoyer des commandes au commutateur de relais de puissance pendant la période de réveil.
-   _**Liaison avec le contrôleur**_

Après avoir rejoint le réseau Z-Wave, le commutateur de relais de puissance peut se lier à un dispositif de contrôle qui peut être utilisé pour ajuster le niveau de puissance de sortie du commutateur de relais de puissance. Pour lier le commutateur de relais de puissance et l'appareil :

1.  Appuyez et maintenez le bouton de fonction pendant 3 secondes, puis relâchez le bouton. Le commutateur de relais de puissance enverra une demande contraignante au coordinateur.
2.  Reportez-vous au manuel de votre contrôleur pour envoyer une demande de liaison pour l'appareil dans les 16 secondes.
3.  Si la liaison réussit, le voyant LED du commutateur de relais de puissance clignotera 3 fois pour confirmer. Vous pouvez maintenant utiliser le contrôleur pour régler le niveau de sortie de puissance du commutateur de relais de puissance.
4.  Si la liaison échoue, le voyant LED du commutateur de relais de puissance clignote 5 fois. Veuillez réessayer le processus de liaison.

![](<.gitbook/assets/5 (27).jpeg>)

**Opération**

-   _**Schéma de connexion des fils**_
    -   Reportez-vous au schéma pour connecter l'éclairage de votre maison au commutateur de relais de puissance.
-   _**Installation**_
    -   Connectez le commutateur de relais de puissance au câble d'alimentation.
    -   Connectez le commutateur de relais de puissance à l'éclairage de votre maison. L'éclairage doit être en état ON.
    -   Vous pouvez connecter un interrupteur externe au commutateur de relais de puissance selon le schéma pour allumer/éteindre le commutateur de relais de puissance.

3

-   -   _**NOTE IMPORTANTE**_**:**Le commutateur de relais d'alimentation n'a pas de batterie de secours et sera mis hors tension en cas de panne de courant CA.**NE PAS**utilisez le commutateur de relais de puissance comme routeur pour votre capteur de sécurité ou vos dispositifs de contrôle d'alarme tels que le contact de porte, le capteur PIR… etc., sinon les capteurs perdront la connexion au réseau Z-Wave si le commutateur de relais de puissance est déconnecté de l'alimentation secteur. Planifiez les emplacements d'installation de ces capteurs de sécurité sans utiliser le commutateur de relais de puissance et utilisez uniquement un routeur avec batterie de secours pour eux. La fonction routeur de l'interrupteur d'alimentation doit**SEULEMENT**Être utilisé pour fournir une extension de la plage de signal pour d'autres interrupteurs d'alimentation/variateur.
-   _**Contrôle des appareils**_
    -   Une fois que le commutateur de relais de puissance a rejoint avec succès un réseau Z-Wave, le coordinateur peut allumer/éteindre l'appareil à distance.
    -   Vous pouvez également appuyer sur le bouton du commutateur de relais de puissance pour allumer/éteindre la lumière.
    -   Vous pouvez allumer/éteindre le commutateur de relais de puissance avec un interrupteur externe.
    -   Si vous avez lié un contrôleur au commutateur de relais de puissance, vous pouvez également utiliser le contrôleur pour allumer/éteindre le commutateur de relais de puissance.
    -   Si l'entrée d'alimentation CA est déconnectée du commutateur de relais de puissance, son état marche/arrêt précédent sera restauré dans la minute qui suit la reconnexion de l'entrée d'alimentation CA au commutateur de relais de puissance.
-   _**Charge de fonctionnement maximale**_
    -   Pour 110 V : la charge de fonctionnement maximale est de 1 100 W et 10 A.
    -   Pour 230 V : la charge de fonctionnement maximale est de 2 300 W et 10 A.
    -   Si le commutateur du relais de puissance surchauffe, il coupera automatiquement l'alimentation par mesure de sécurité. L'utilisateur doit déconnecter et reconnecter l'alimentation CA au commutateur de relais de puissance après la coupure pour reprendre un fonctionnement normal.
-   _**Informations sur la vague Z**_

**Type d'appareil:**Interrupteur marche/arrêt

**Type de rôle :**Toujours sur esclave (AOS)

**Prise en charge/contrôle de classe de commande**

**Prise en charge CC obligatoire :**Association CC, v2 ou plus récente

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

4
