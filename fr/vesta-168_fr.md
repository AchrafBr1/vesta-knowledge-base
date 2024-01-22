# VESTA 168

**Commutateur de commande d'obturateur SCS-1-ZW**

**Introduction**

SCS-1-ZW est un interrupteur de commande de volet à trois boutons Z-Wave conçu pour contrôler un groupe d'appareils domotiques préprogrammés en appuyant simplement sur les boutons de scénario sous le même réseau Z-Wave.

Le commutateur de commande d'obturation est un appareil compatible Z-Wave et est entièrement compatible avec tout réseau compatible Z-Wave.

Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance. En profitant du réseau maillé Z-Wave, les commandes peuvent être acheminées vers leur destination via des produits Z-Wave intermédiaires « d’écoute ».

![](<.gitbook/assets/0 (61).jpeg>)

**Présentation de l'appareil**

**1. LED de scénario**

Lorsque l'un des 3 boutons de scénario est enfoncé, la LED s'allume brièvement

**2. Boutons de scénario**

Le commutateur de commande d'obturation dispose de 3 boutons de scénario

1.  **Compartiment à piles**
2.  **Bouton de fonction**
    -   Appuyez 3 fois sur le bouton en 1,5 seconde pour transmettre un code d'apprentissage.
    -   Appuyez et maintenez pendant 10 secondes pour réinitialiser.
3.  **LED (rouge)**

La LED rouge s'allume dans les situations suivantes :

-   -   Clignote une fois :

Lorsque le commutateur de commande Sutter transmet un signal.

-   -   Clignote deux fois :

Le commutateur de commande d'obturation a été ajouté avec succès à un réseau Z-Wave.

1.  **Fonction Boutonnière**

**Caractéristiques**

![](<.gitbook/assets/1 (54).jpeg>)

-   _**Détection de batterie et de batterie faible**_

Le commutateur de commande d’obturation utilise deux piles alcalines AA de 1,5 V comme source d’alimentation.

Le Switch signalera son pourcentage de batterie au panneau de commande respectivement à 100 %, 75 %, 50 % et 25 %. Si la tension de la batterie est faible (25 %), un signal de batterie faible sera envoyé au panneau de commande pour avertir l'utilisateur. Le commutateur de commande d'obturation est doté d'une fonction de détection de batterie faible. Lorsque la tension de la batterie est faible, le commutateur de scénario transmet le signal de batterie faible au coordinateur Z-Wave.

![](<.gitbook/assets/2 (58).png>)

-   _**Surveillance**_

Cette fonction utilise la classe de commande de réveil Z-Wave. La classe de commande de réveil permet au commutateur alimenté par batterie d'informer le panneau de commande/la passerelle qu'il est réveillé et prêt à recevoir toutes les commandes en file d'attente. La période d’intervalle de réveil est programmée automatiquement en fonction des paramètres du panneau de commande lorsque le commutateur est inclus. Le réglage recommandé du temps d'intervalle est compris entre 30 et 60 minutes.

![](<.gitbook/assets/3 (58).png>)

-   _**Scénario et contrôle de l'obturateur**_

Lorsqu'un bouton de scénario est enfoncé, le commutateur de commande d'obturation enverra un signal au panneau de commande pour activer le scénario correspondant (voir Panneau de commande pour plus de détails). Définissez le scénario dans le panneau de configuration sur

1

Contrôlez la fonction d'ouverture/fermeture/arrêt du volet pour faire fonctionner le volet via l'interrupteur de commande de scénario.

L'interrupteur émettra un bip pour indiquer que le bouton est enfoncé.

![](<.gitbook/assets/4 (57).png>)

-   _**Ajout d'un appareil (inclusion)**_

Ce produit peut être inclus et utilisé dans n'importe quel réseau Z-Wave avec d'autres appareils certifiés Z-Wave d'autres fabricants et/ou d'autres applications. Tous les nœuds non alimentés par batterie du réseau agiront comme répéteurs, quel que soit le fournisseur, afin d'augmenter la fiabilité du réseau.

-   -   Retirez le couvercle à l'aide d'un tournevis.
    -   Insérez la batterie puis replacez le couvercle.
    -   Mettez le panneau de commande Z-Wave dans**Mode d'inclusion**(veuillez vous référer au manuel du panneau de commande Z-Wave).
    -   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction.
    -   Reportez-vous au manuel d'utilisation de la passerelle Z-Wave ou du panneau de commande pour terminer le processus d'ajout.
    -   Si l'appareil a déjà été ajouté (inclus) dans une autre passerelle/panneau de configuration Z-Wave, ou si l'appareil ne peut pas être ajouté à la passerelle/panneau de configuration Z-Wave actuelle, essayez d'abord de le supprimer (voir_**Suppression d'un périphérique**_).
-   _**Suppression d'un périphérique (exclusion)**_

![](<.gitbook/assets/5 (56).png>)

L'appareil doit être supprimé du réseau Z-Wave existant avant d'être ajouté à un autre.**Mode d'exclusion**

-   Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'exclusion**(veuillez vous référer au manuel du Z-Wave ou du panneau de commande).
-   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction et l'appareil sera supprimé du réseau Z-Wave.

**Retour aux paramètres d'usine**

La réinitialisation d'usine de l'appareil le restaurera aux paramètres d'usine par défaut (c'est-à-dire qu'il n'est inclus dans aucun réseau Z-Wave). Veuillez utiliser cette procédure uniquement si la passerelle ou le panneau de commande Z-Wave est perdu ou inutilisable.

-   -   Appuyez et maintenez enfoncé le bouton de fonction de l'appareil pendant 10 secondes pour réinitialiser les paramètres d'usine.
-   _**Test de portée**_

![](<.gitbook/assets/6 (38).png>)

Pour tester si l'appareil est capable de communiquer avec la passerelle Z-Wave ou le panneau de commande :

-   -   Mettez la passerelle/le panneau en mode test de portée (Walk Test).
    -   Appuyez sur le bouton de fonction de l'appareil.
    -   La passerelle/le panneau doit s'afficher si l'appareil se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation de la passerelle/du panneau).
-   _**Mode veille Z-Wave**_
    -   Le commutateur de commande d'obturation entrera en mode veille Z-Wave (pour économiser l'énergie) après une courte période de réveil (~10 secondes). En mode veille Z-Wave, les passerelles ou panneaux de commande Z-Wave ne peuvent pas envoyer de commandes au commutateur de commande d'obturateur.
    -   Pour programmer le commutateur de commande d'obturateur à l'aide de la passerelle/panneau de commande Z-Wave, veuillez envoyer des commandes au commutateur de commande d'obturateur pendant la période de réveil.

![](<.gitbook/assets/7 (32).png>)![](<.gitbook/assets/8 (29).jpeg>)

**Installation**

-   L'interrupteur de commande de volet est conçu pour être monté sur une surface plane avec des vis de fixation.
-   La base comporte 3 découpes, là où le plastique est plus fin, à des fins de montage.
    1.  Retirez le couvercle à l'aide d'un tournevis.
    2.  Percez les trous appropriés sur la base.
    3.  En utilisant les trous comme gabarit, percez des trous dans la surface.
    4.  Vissez la base dans la surface.
    5.  Remettez le couvercle sur la base et fixez-le en serrant la vis de fixation.

![](<.gitbook/assets/9 (19).jpeg>)

2

**Informations sur la vague Z**

**Type d'appareil:**Capteur - Notification

**Type de rôle :**Signalement de l'esclave endormi (RSS)

**Prise en charge/contrôle de classe de commande**

**Prise en charge CC obligatoire :**Association CC, v2

Informations sur le groupe d'association CC

Batterie CC

Réinitialisation de l'appareil localement CC

CC spécifique au fabricant, v2

Activation de scène CC

VersionCC, v2

Réveillez-vous CC, v2

Z-Wave Plus Info CC, v2

Niveau de puissance CC

Notification CC, v4

Mise à jour du micrologiciel CC, v2

![](<.gitbook/assets/10 (34).png>)

-   _**Groupes de Z-Wave (classe de commande d'association version 2)**_

Groupe 1 pour « LifeLine » :

Activation de scène CC

(COMMANDE_CLASSE_SCÈNE_ACTIVATION)

Batterie CC (COMMANDE_CLASSE_BASIQUE)

Réinitialisation de l'appareil localement CC

3
