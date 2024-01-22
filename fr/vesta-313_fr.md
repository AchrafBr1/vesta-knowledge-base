# VESTA 313

**League of Legends-3ZW****Capteur de lumière ambiante, d'humidité et de température**

**Introduction**

LMHT-3ZW est un capteur de lumière ambiante, d'humidité et de température Z-Wave. Il surveille votre environnement domestique et transmet l'éclairement (lux), l'humidité et la température mesurés au coordinateur du réseau Z-Wave.

Le capteur est un appareil compatible Z-Wave et est entièrement compatible avec tout réseau compatible Z-Wave.

Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance. En profitant du réseau maillé Z-Wave, les commandes peuvent être transmises vers leur destination via des produits Z-Wave intermédiaires « d’écoute ».

**Identification des pièces**

![](<.gitbook/assets/0 (105).jpeg>)

1.  **Capteur de lumière/indicateur LED**
    -   **Clignote une fois :**Transmission du code d'apprentissage/réinitialisation d'usine.
    -   **Clignote deux fois :**Une fois le capteur ajouté avec succès à la passerelle/panneau de configuration Z-Wave.
2.  **Compartiment à piles**
3.  **Bouton de fonction**
    -   Appuyez une fois pour envoyer un signal au coordinateur.
    -   Appuyez et maintenez enfoncé pendant 10 secondes pour réinitialiser les paramètres d'usine.
    -   Appuyez 3 fois en 1,5 seconde pour transmettre le code d'apprentissage.
4.  **Capteur de température**

**Caractéristiques**

-   _**Surveillance de l'éclairage, de l'humidité et de la température**_
    -   Le capteur mesure l'éclairement, l'humidité et la température pour transmettre régulièrement les données mesurées au panneau de commande/passerelle Z-Wave.

La lecture de l’éclairement/humidité et de la température est transmise toutes les minutes. Le capteur transmettra également automatiquement le signal lorsque :

-   -   -   La température change de +/- 2°C.
        -   L'humidité change de +/- 10%.
        -   L'éclairement actuel change de +/- 30 %.
        -   Allumez le capteur en insérant la batterie.
    -   Vous pouvez également appuyer une fois sur le bouton de fonction pour transmettre manuellement la lecture actuelle.
-   _**Détection de batterie et de batterie faible**_
    -   Le capteur utilise une pile au lithium CR123A 3V comme source d'alimentation.
    -   Le capteur dispose d'une fonction de détection de batterie faible. Lorsque la tension de la batterie est faible, le capteur transmet le signal de batterie faible à la passerelle/au panneau de commande.
    -   Le capteur signalera son pourcentage de batterie à la passerelle/au panneau de commande respectivement à 100 %, 75 %, 50 % et 25 %. Si la tension de la batterie est faible (25 %), un signal de batterie faible sera envoyé au panneau de commande pour avertir l'utilisateur.
    -   Lors du changement de batterie, après avoir retiré les anciennes batteries, appuyez deux fois sur le bouton de fonction pour la décharger complètement avant d'insérer une nouvelle batterie.
-   _**Surveillance**_

Cette fonction utilise la classe de commande de réveil Z-Wave. La classe de commande de réveil permet au capteur alimenté par batterie d'informer le panneau de commande/la passerelle qu'il est réveillé et prêt à recevoir toutes les commandes en file d'attente. La période d’heure de réveil est programmée automatiquement en fonction des paramètres du panneau de commande lorsque le capteur est inclus. Le réglage recommandé de l'heure de réveil est supérieur à 60 minutes.

1

-   _**Ajout d'un appareil (inclusion)**_

Ce produit peut être inclus et utilisé dans n'importe quel réseau Z-Wave avec d'autres appareils certifiés Z-Wave d'autres fabricants et/ou d'autres applications. Tous les nœuds non alimentés par batterie du réseau agiront comme répéteurs, quel que soit le fournisseur, afin d'augmenter la fiabilité du réseau.

-   -   Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'inclusion**(veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
    -   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction.
    -   Refer to the operation manual of the Z-Wave gateway or control panel to complete the adding process.
    -   Si le capteur a déjà été ajouté (inclus) dans une autre passerelle/panneau de commande Z-Wave, ou si l'appareil ne peut pas être ajouté à la passerelle/panneau de commande Z-Wave actuelle, essayez d'abord de le supprimer (voir_**Suppression d'un périphérique**_).
-   _**Suppression d'un périphérique (exclusion)**_

Le capteur doit être supprimé du réseau Z-Wave existant avant d'être ajouté à un autre.

**Mode d'exclusion**

-   Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'exclusion**(veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
-   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction et le capteur sera supprimé du réseau Z-Wave.

**Retour aux paramètres d'usine**

_(Utilisez la réinitialisation d'usine uniquement lorsque le panneau de configuration/passerelle réseau est manquant ou inutilisable)._

-   Retirez d'abord la batterie du capteur.
-   Appuyez et maintenez enfoncé le bouton de fonction. Tout en maintenant le bouton de fonction enfoncé, allumez le capteur en réinsérant la batterie, attendez 10 secondes pour réinitialiser les paramètres d'usine.

_\\<NOTE>_

-   -   La réinitialisation d'usine du capteur le restaurera aux paramètres d'usine par défaut (exclus du réseau Z-Wave). La passerelle ou le panneau de commande Z-Wave conservera toujours ses paramètres Z-Wave. Veuillez vous référer au manuel de la passerelle ou du panneau de commande pour savoir comment supprimer les paramètres du capteur Z-Wave.
-   _**Test de portée**_

Pour tester si le capteur est capable de communiquer avec la passerelle Z-Wave ou le panneau de commande :

-   -   Mettez la passerelle/le panneau en mode test de portée (Walk Test).
    -   Appuyez sur le bouton de fonction du capteur.
    -   La passerelle/le panneau doit s'afficher si l'appareil se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation de la passerelle/du panneau).
-   _**Mode veille Z-Wave**_
    -   Le capteur entrera en mode veille Z-Wave (pour économiser l'énergie) après une courte période de réveil (~10 secondes). En mode veille Z-Wave, les passerelles ou panneaux de contrôle Z-Wave ne peuvent pas envoyer de commandes au capteur.
    -   Pour programmer le capteur à l'aide de la passerelle/panneau de commande Z-Wave, veuillez envoyer des commandes au capteur pendant la période de réveil.

**Installation**

-   _**Montage du capteur**_

Le capteur peut être monté de deux manières : montage auto-adhésif ou par vis.

**Montage autocollant**

1.  Nettoyer la surface avec un dégraissant adapté.
2.  Retirez le revêtement de protection d'un côté du tampon adhésif double face et appliquez-le fermement à l'arrière de l'appareil.
3.  Retirez l'autre revêtement et placez/appuyez fermement sur l'appareil à l'emplacement souhaité.

![](<.gitbook/assets/1 (87).jpeg>)

N'utilisez pas la méthode de montage autocollante sur des surfaces mal peintes et/ou rugueuses.

**Montage à vis**

La base du capteur comporte deux alvéoles de vis, où le plastique est plus fin à des fins de montage. Pour monter le capteur :

1.  Détachez l'ensemble couvercle supérieur et base en desserrant la vis de fixation du couvercle à l'aide d'un tournevis Philips.
2.  Brisez les trous sur la base.

2

-   1.  Utilisez les trous comme gabarit pour percer deux trous et insérer les chevilles murales.
    2.  Vissez la base dans les chevilles murales.
    3.  Remettez le capot supérieur sur la base en accrochant la base au crochet de fixation et en poussant le capot vers la base.
    4.  Fixez et revissez le capot supérieur sur sa base à l'aide d'un tournevis Philips.
-   _**Informations sur la vague Z**_

**Type d'appareil:**Capteur - Notification

**Type de rôle :**Signalement de l'esclave endormi (RSS)

**Prise en charge/contrôle de classe de commande**

**Prise en charge CC obligatoire :**

Association CC, v2

Informations sur le groupe d'association CC

Batterie CC

Réinitialisation de l'appareil localement CC

CC spécifique au fabricant, v2

Capteur multiniveau CC, V5

VersionCC, v2

Réveillez-vous CC, v2

Z-Wave Plus Info CC, v2

Niveau de puissance CC

Notification CC, v4

Mise à jour du micrologiciel CC, v2

-   _**Groupes de Z-Wave (classe de commande d'association version 2)**_

Groupe 1 pour « LifeLine » :

Capteur multiniveau CC,V5 (COMMANDE_CLASSE_CAPTEUR_MULTINIVEAU)

Batterie CC (COMMANDE_CLASSE_BASIQUE)

Réinitialisation de l'appareil localement CC

Groupe 2 pour « Rapport de température » :

Capteur multiniveau CC,V5 (COMMANDE_CLASSE_CAPTEUR_MULTINIVEAU)

Groupe 3 pour « Rapport d'humidité » :

Capteur Multiniveau CC, V5 (COMMANDE_CLASSE_CAPTEUR_MULTINIVEAU)

Groupe 4 pour « Rapport de Luminance » :

Capteur Multiniveau CC, V5 (COMMANDE_CLASSE_CAPTEUR_MULTINIVEAU)

3
