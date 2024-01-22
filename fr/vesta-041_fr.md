# VESTA 041

**Sonde d'ambiance RS-23-ZW**V : R3

**Introduction**

RS-23-ZW est un capteur d'ambiance Z-Wave. Il dispose d'une fonction de détection de température et d'humidité pour surveiller votre environnement domestique. Les informations de température et d'humidité seront transmises au réseau Z-Wave et affichées sur l'écran LCD du capteur d'ambiance.

Le capteur d'ambiance est un appareil compatible Z-Wave et est entièrement compatible avec tout réseau compatible Z-Wave.

Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance. En profitant du réseau maillé Z-Wave, les commandes peuvent être transmises vers leur destination via des produits Z-Wave « d’écoute » intermédiaires.

La série de capteurs d'ambiance Z-Wave comprend les modèles suivants :

RS-23-ZW

![](<.gitbook/assets/0 (33).png>)

RS-23-ZW-OTA

**Identification des pièces**

**1. Écran LCD**

L'écran LCD affiche les informations suivantes :

-   Température en Fahrenheit / Celsius
-   Humidité RH%.
-   Connectivité réseau Z-Wave (![](<.gitbook/assets/1 (30).jpeg>)icône).

![](<.gitbook/assets/2 (27).jpeg>)

\-État de la batterie faible (icône).

-   -   Rétroéclairage LCD allumé : lorsque le bouton de fonction est enfoncé.

1.  **Bouton de fonction**
    -   Appuyez une fois sur le bouton pour :

Envoyez un signal de supervision avec des informations de température/humidité Allumez le rétroéclairage LCD pendant 10 secondes.

-   -   Appuyez 3 fois sur le bouton en 1,5 seconde pour transmettre le code d'apprentissage.
    -   Appuyez et maintenez le bouton enfoncé pendant 10 secondes pour réinitialiser les paramètres d'usine. Faire référence à**Suppression d'un périphérique (exclusion)**pour plus de détails.

1.  **Vis de base (ouverture/fermeture du couvercle)**

Lorsque le capot avant est installé sur le capot arrière, ouvrez le capot en desserrant la vis de base et fermez-le de la même manière.

1.  **Cavalier de réglage Fahrenheit/Celcius (JP1)**
    -   Si le cavalier est inséré entre les 2 broches supérieures, l'écran LCD affichera la température en Celsius. (**Défaut de fabrication**)
    -   Si le cavalier est inséré entre les 2 broches inférieures, l'écran LCD affichera la température en Fahrenheit.
2.  **Compartiment à piles**

![](<.gitbook/assets/3 (25).jpeg>)![](<.gitbook/assets/4 (27).jpeg>)

Le capteur d'ambiance est alimenté par deux piles alcalines AA 1,5 V

1.  **Quatrième de couverture**
2.  **Débouchures de montage mural**

**Caractéristiques**

-   _**Détection de température et d'humidité**_
    -   Le capteur d'ambiance transmettra régulièrement des signaux de température et d'humidité en fonction du réglage.

1

L'intervalle par défaut est de 10 minutes.

-   -   Lorsque la température change de +/- 2°C ou que l'humidité change de +/- 10 %, le capteur d'ambiance transmet également un signal.
    -   Vous pouvez également appuyer une fois sur le bouton de fonction pour transmettre manuellement un signal de température et d'humidité.
    -   La plage de détection de température est d'environ -10°C~50°C.( 14°F~122°F)
    -   La plage de détection d'humidité est d'environ 10 %~90 % d'humidité relative
-   _**Détection de batterie et de batterie faible**_
    -   Le capteur d'ambiance utilise deux piles alcalines de 1,5 V comme source d'alimentation. Les piles sont incluses dans le colis.
    -   Le capteur d'ambiance signalera son pourcentage de batterie au panneau de commande Z-Wave respectivement à 100 %, 75 %, 50 %, 25 % et 0 %. Si la tension de la batterie est faible (25 %), un signal de batterie faible sera envoyé au panneau de commande Z-Wave pour avertir l'utilisateur.
    -   Le capteur d'ambiance est doté d'une fonction de détection de batterie faible. Lorsque la tension de la batterie est faible, le capteur d'ambiance transmet un signal de batterie faible pour avertir l'utilisateur et affiche l'icône de batterie faible sur l'écran LCD.
    -   Lors du changement des piles, après avoir retiré les anciennes piles, appuyez deux fois sur le bouton de fonction pour les décharger complètement avant d'insérer de nouvelles piles.
-   _**Surveillance**_
    -   Cette fonction utilise la classe de commande de réveil Z-Wave. La classe de commande de réveil permet au capteur de pièce alimenté par batterie d'informer le panneau de commande/passerelle Z-Wave qu'il est réveillé et prêt à recevoir toutes les commandes en file d'attente. L'heure de réveil est programmée automatiquement en fonction des paramètres du panneau de commande Z-Wave lorsque le capteur d'ambiance est inclus. Le réglage recommandé de l'heure de réveil est supérieur à 60 minutes.
-   _**Ajout d'un appareil (inclusion)**_

Ce produit peut être inclus et utilisé dans n'importe quel réseau Z-Wave avec d'autres appareils certifiés Z-Wave d'autres fabricants et/ou d'autres applications. Tous les nœuds non alimentés par batterie du réseau agiront comme répéteurs, quel que soit le fournisseur, afin d'augmenter la fiabilité du réseau.

-   -   Retirez le couvercle en desserrant la vis de fixation.
    -   Insérez les 2 piles alcalines dans le compartiment des piles en respectant la bonne polarité comme indiqué sur le couvercle du compartiment des piles pour allumer le capteur d'ambiance.
    -   Mettez la passerelle Z-Wave ou le panneau de commande Z-Wave dans**Inclusion**ou**Apprentissage**mode (veuillez vous référer au manuel de la passerelle Z-wave ou du panneau de commande Z-Wave).
    -   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction.
    -   Reportez-vous au manuel d'utilisation de la passerelle Z-Wave ou du panneau de commande Z-Wave pour terminer le processus d'apprentissage.
    -   Si le capteur a déjà été**inclus**(appris) dans une autre passerelle Z-Wave/panneau de commande Z-Wave, ou si le capteur ne peut pas être appris dans la passerelle Z-Wave/panneau de commande Z-Wave actuelle, veuillez d'abord l'exclure (voir_**Exclusion**_) avant de tenter de**inclure**dans le panneau de commande Z-Wave Gateway/Z-Wave actuel.
-   _**Suppression d'un périphérique (exclusion)**_

Le capteur d'ambiance doit être retiré du réseau Z-Wave existant avant d'être inclus dans un autre. Il existe deux méthodes disponibles pour exclure un appareil.

**Mode d'exclusion**

-   Mettez la passerelle Z-Wave ou le panneau de commande Z-Wave dans**Mode d'exclusion**(veuillez vous référer à la passerelle Z-Wave ou au manuel du panneau de commande Z-Wave).
-   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction et le capteur d'ambiance sera supprimé du réseau Z-Wave.

**Retour aux paramètres d'usine**

_(Utilisez la réinitialisation d'usine uniquement lorsque le panneau de commande/passerelle réseau Z-Wave est manquant ou inutilisable)._

-   Retirez d'abord les piles du capteur d'ambiance.
-   Appuyez et maintenez le bouton de fonction. Tout en maintenant le bouton de fonction enfoncé, allumez le capteur d'ambiance en réinsérant les piles, attendez 10 secondes pour réinitialiser les paramètres d'usine.

_\\<NOTE>_

-   La réinitialisation d'usine du capteur d'ambiance le restaurera aux paramètres d'usine par défaut (exclus du réseau Z-wave). La passerelle Z-Wave ou le panneau de configuration Z-Wave conservera toujours ses paramètres Z-Wave. Veuillez vous référer au manuel de la passerelle ou du panneau de commande Z-Wave pour savoir comment supprimer les paramètres Z-Wave du capteur d'ambiance.

2

-   _**Test de portée**_

Pour tester si l'appareil est capable de communiquer avec la passerelle Z-Wave ou le panneau de commande Z-Wave :

-   -   Mettez la passerelle/le panneau en mode test de portée (Walk Test).
    -   Appuyez sur le bouton de fonction de l'appareil.
    -   Le panneau de commande de la passerelle/du panneau doit s'afficher si l'appareil se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation du panneau de commande de la passerelle/du panneau).
-   _**Mode veille Z-Wave**_
    -   Le capteur d'ambiance entrera en mode veille Z-Wave (pour économiser l'énergie) après une courte période de réveil (~10 secondes). En mode veille Z-Wave, les passerelles Z-Wave ou les panneaux de commande Z-Wave ne peuvent pas envoyer de commandes au capteur d'ambiance.
    -   Pour programmer le capteur d'ambiance, veuillez envoyer des commandes au capteur d'ambiance pendant la période de réveil.

**Installation**

-   _**Montage du capteur d'ambiance**_

Pour une meilleure qualité d'affichage LCD, le capteur d'ambiance doit être monté à environ 5∘au-dessus de la hauteur des yeux.

-   Montage à vis.

Lors du montage avec des vis, assurez-vous d'utiliser uniquement les vis fournies dans l'emballage par le fabricant d'origine, car des vis inappropriées peuvent endommager l'intérieur de l'appareil.

-   1.  Retirez le capot avant à l'aide d'un tournevis.
    2.  Brisez les découpes sur la couverture arrière.
    3.  En utilisant les trous comme gabarit, percez des trous dans la surface
    4.  Insérez les chevilles murales si vous fixez dans du plâtre ou de la brique
    5.  Vissez le couvercle arrière dans les chevilles murales
    6.  Revissez le capot avant sur le capot arrière
-   _**Informations sur la vague Z**_

**Type d'appareil:**Capteur - Notification

**Type de rôle :**Signalement de l'esclave endormi (RSS)

**Prise en charge/contrôle de classe de commande**

**Support CC obligatoire :**Association CC, v2 ou plus récente

Informations sur le groupe d'association CC

Batterie CC

Réinitialisation de l'appareil localement CC

CC spécifique au fabricant

Capteur CC multiniveau

Version CC, v2 ou plus récente

Réveillez-vous CC

Informations Z-Wave Plus CC

Mise à jour du micrologiciel CC, v2 (version OTA uniquement)

-   _**Groupes de Z-Wave (classe de commande d'association version 2)**_

Le capteur d'ambiance peut être configuré pour envoyer des rapports aux appareils Z-Wave associés. Elle soutient 3 groupes associatifs.

Groupe 1 pour « LifeLine » :

Capteur multiniveau CC,V5 (COMMANDE_CLASSE_CAPTEUR_MULTINIVEAU)

Batterie CC (COMMANDE_CLASSE_UTILISATEUR_BASIQUE)

Réinitialisation de l'appareil localement CC

_(Il prend en charge 1 nœud)_

Groupe 2 pour « Rapport de température » :

Capteur Multiniveau CC, v5 (COMMANDE_CLASSE_CAPTEUR_MULTINIVEAU)

_(il prend en charge 5 nœuds)_

3

Groupe 3 pour « Rapport d'humidité » :

Capteur multiniveau CC,V5 (COMMANDE_CLASSE_CAPTEUR_MULTINIVEAU)

_(il prend en charge 5 nœuds)_

4
