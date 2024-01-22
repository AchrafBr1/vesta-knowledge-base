# VESTA 312

**Série Mini-FIRE-LIVE**

**Introduction**

La série Mini-PIR-ZW est un capteur de mouvement infrarouge passif Z-Wave capable d'envoyer des signaux sans fil au coordinateur du réseau Z-Wave lors de la détection de mouvement. Le PIR dispose d'un capteur de température/lumière ambiante intégré en option qui fournit une lecture de température/lux qui sera transmise via le réseau Z-Wave à intervalles réguliers (modèle Mini-PIR-LT-ZW uniquement).

Le PIR peut être configuré à l'aide du coordinateur Z-Wave pour fonctionner soit comme un capteur de sécurité qui active l'alarme lorsqu'il est déclenché, soit comme un capteur de présence/vacance qui contrôle les fonctions domotiques ou d'éclairage via le coordinateur Z-Wave.

Le PIR est un appareil compatible Z-Wave et est entièrement compatible avec tout réseau compatible Z-Wave.

Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance. En profitant du réseau maillé Z-Wave, les commandes peuvent être transmises vers leur destination via des produits Z-Wave « d’écoute » intermédiaires.

La série Mini-PIR-ZW comprend les modèles suivants :

| **Nom du modèle** | **Détection de mouvement** | **Lumière et température** |
| ----------------- | -------------------------- | -------------------------- |
|                   |                            | **détection**              |
|                   |                            |                            |
| Mini-FIRE-LIVE    | DANS                       |                            |
|                   |                            |                            |
| Mini-FIRE-LT-LIVE | DANS                       | DANS                       |
|                   |                            |                            |

**Identification des pièces**

Le PIR est composé d'un corps principal et d'une base. Le corps principal doit être séparé de la base pour l'installation de la batterie et la configuration du réseau Z-Wave.

Pour séparer le corps principal et la base, tenez le PIR à deux mains et tournez la base vers la droite et le corps principal vers la gauche pour séparer.

![](<.gitbook/assets/0 (58).png>)

**1. Objectif IR avec indicateur LED**

L'indicateur LED est situé au centre de la lentille IR.

Le voyant LED s'allume dans les conditions suivantes :

-   -   Clignote une fois :

Le PIR transmet le code d'apprentissage/réinitialisation d'usine.

-   -   Clignote deux fois rapidement :

Le PIR a rejoint avec succès le réseau Z-Wave.

-   -   Clignote en mode de fonctionnement normal :

Le PIR a détecté un mouvement et il est actuellement en condition de batterie faible ou d'autoprotection.

1.  **Quatrième de couverture**

Retirez le couvercle arrière pour accéder au compartiment de la batterie et au bouton de fonction.

1.  **Bouton de fonction**
    -   Appuyez une fois sur le bouton pour envoyer un signal de supervision et passer en mode test.
    -   Appuyez 3 fois en 1,5 seconde pour transmettre un code d'apprentissage.
    -   Appuyez et maintenez le bouton pendant 10 secondes, puis relâchez-le pour réinitialiser les paramètres d'usine.
2.  **Compartiment à piles**

Le PIR est alimenté par une pile au lithium CR123A 3V.

1.  **Vis de réglage de l'angle de la base**
2.  **Trous de montage mural**

1

**Caractéristiques**

-   _**Minuterie de mise en veille**_

Le PIR a un « temps de veille » d'environ 1 minute pour économiser l'énergie. Après avoir transmis un mouvement détecté, le PIR ne retransmettra pas pendant 1 minute. Tout mouvement supplémentaire détecté pendant cette période de sommeil prolongera la durée du sommeil d'une minute supplémentaire. De cette manière, un mouvement continu devant un PIR n’épuisera pas indûment la batterie.

-   _**Signalisation d'arrêt de mouvement**_

Après chaque détection de mouvement, si 30 secondes s'écoulent sans détection, le PIR transmettra un signal « arrêt de mouvement » au coordinateur du réseau Z-Wave.

-   _**Détection de batterie et de batterie faible**_
    -   Le PIR utilise une pile au lithium CR123A 3V comme source d'alimentation. Le corps principal du PIR doit être retiré de la base pour accéder au compartiment des piles. Le compartiment à piles comporte une bande qui doit être pressée sous la pile lorsque la pile est insérée. Lorsque vous retirez la pâte, soulevez simplement la bande.
    -   Le PIR dispose d'une fonction de détection de batterie faible. Lorsque la tension de la batterie est faible, le PIR transmet le signal de batterie faible au coordinateur du réseau Z-Wave. Si un mouvement est détecté dans des conditions de batterie faible, l'indicateur LED clignote pour l'indiquer.
    -   Le PIR signalera son pourcentage de batterie à la passerelle/au panneau de commande respectivement à 100 %, 75 %, 50 % et 25 %. Si la tension de la batterie est faible (25 %), un signal de batterie faible sera envoyé au panneau de commande pour avertir l'utilisateur.
    -   Si la batterie n'est pas changée après une condition de batterie faible et est épuisée, la LED clignotera toutes les 2 secondes et le PIR arrêtera toutes les opérations.
    -   Lors du changement de batterie, après avoir retiré l'ancienne batterie, appuyez deux fois sur le bouton de fonction pour la décharger complètement avant d'insérer une nouvelle batterie.
-   _**Autoprotection**_

Le PIR est protégé par un interrupteur anti-sabotage situé à l’intérieur du corps principal du PIR. L'interrupteur anti-sabotage est activé chaque fois que le PIR est retiré de la base, et le PIR enverra un signal d'ouverture anti-sabotage pour rappeler à l'utilisateur la condition. Si un mouvement est détecté lorsque l'interrupteur anti-sabotage est ouvert, le PIR clignote pour l'indiquer.

-   _**Surveillance**_

Cette fonction utilise la classe de commande de réveil Z-Wave. La classe de commande de réveil permet au PIR alimenté par batterie d'informer le panneau de commande/la passerelle qu'il est réveillé et prêt à recevoir toutes les commandes en file d'attente. La période d’heure de réveil est programmée automatiquement en fonction des paramètres du panneau de commande lorsque le PIR est inclus. Le réglage recommandé de l'heure de réveil est supérieur à 60 minutes.

-   _**Mode d'essai**_
    -   Le mode test vous permet de vérifier la plage de détection du PIR.
    -   Appuyez une fois sur le bouton Fonction pour passer en mode Test pendant 3 minutes.
    -   Pendant le mode test, vous pouvez déclencher le capteur PIR pour vérifier sa couverture de détection. Si le PIR est déclenché, la LED s'allumera pour l'indiquer.
-   _**Détection de température (modèle Mini-PIR-LT-ZW uniquement)**_
    -   Le PIR avec capteur de température intégré transmettra régulièrement des signaux de température en fonction du réglage. L'intervalle par défaut est de 30 minutes.
    -   Lorsque la température change de +/- 2°C, le PIR transmettra également un signal.
    -   Vous pouvez également appuyer une fois sur le bouton de fonction pour transmettre manuellement un signal de température.
    -   La plage de détection de température est d'environ -10°C~50°C ( 14°F~122°F).
-   _**Surveillance de la lumière (modèle Mini-PIR-LT-ZW uniquement)**_
    -   Le PIR avec capteur de lumière ambiante intégré mesure l'éclairement et transmet régulièrement les données mesurées au coordinateur du réseau Z-Wave. L'intervalle par défaut est de 30 minutes.
    -   Lorsque l'éclairement actuel change de +/- 10 %, le PIR transmettra également un signal.
    -   Vous pouvez également appuyer une fois sur le bouton de fonction pour transmettre manuellement la lecture actuelle en lux.
-   _**Ajout d'un appareil (inclusion)**_

Ce produit peut être inclus et utilisé dans n'importe quel réseau Z-Wave avec d'autres appareils certifiés Z-Wave d'autres fabricants et/ou d'autres applications. Tous les nœuds non alimentés par batterie du réseau agiront comme répéteurs, quel que soit le fournisseur, afin d'augmenter la fiabilité du réseau.

-   Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'inclusion**(veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
-   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction.
-   Reportez-vous au manuel d'utilisation de la passerelle Z-Wave ou du panneau de commande pour terminer le processus d'ajout.
-   Si le PIR a déjà été ajouté (inclus) dans une autre passerelle/panneau de configuration Z-Wave, ou si l'appareil ne peut pas être ajouté à la passerelle/panneau de configuration Z-Wave actuelle, essayez d'abord de le supprimer (voir_**Suppression d'un périphérique**_).

2

-   _**Suppression d'un périphérique (exclusion)**_

Le PIR doit être supprimé du réseau Z-Wave existant avant d'être ajouté à un autre.

**Mode d'exclusion**

-   Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'exclusion**(veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
-   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction et le PIR sera supprimé du réseau Z-Wave.

**Retour aux paramètres d'usine**

_(Utilisez la réinitialisation d'usine uniquement lorsque le panneau de configuration/passerelle réseau est manquant ou inutilisable)._

-   Retirez d'abord la batterie du PIR.
-   Appuyez et maintenez le bouton de fonction. Tout en maintenant le bouton de fonction enfoncé, allumez le PIR en réinsérant la batterie, attendez 10 secondes pour réinitialiser les paramètres d'usine.

_\\<NOTE>_

-   -   La réinitialisation d'usine du PIR le restaurera aux paramètres d'usine par défaut (exclus du réseau Z-Wave). La passerelle ou le panneau de commande Z-Wave conservera toujours ses paramètres Z-Wave. Veuillez vous référer au manuel de la passerelle ou du panneau de commande pour savoir comment supprimer les paramètres PIR Z-Wave.
-   _**Test de portée**_

Pour tester si le PIR est capable de communiquer avec la passerelle Z-Wave ou le panneau de commande :

-   -   Mettez la passerelle/le panneau en mode test de portée (Walk Test).
    -   Appuyez sur le bouton de fonction du PIR.
    -   La passerelle/le panneau doit s'afficher si l'appareil se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation de la passerelle/du panneau).
-   _**Mode veille Z-Wave**_
    -   Le PIR entrera en mode veille Z-Wave (pour économiser l'énergie) après un réveil pendant une courte période (~10 secondes). En mode veille Z-Wave, les passerelles ou panneaux de contrôle Z-Wave ne peuvent pas envoyer de commandes au PIR.
    -   Pour programmer le PIR à l'aide de la passerelle/panneau de commande Z-Wave, veuillez envoyer des commandes au PIR pendant la période de réveil.

**Installation**

-   _**Hauteur de montage et couverture de détection PIR**_
    -   Il existe deux façons de déployer le Mini-PIR : le montage mural et le déploiement en surface.
    -   Le PIR a une couverture de détection d'un cône de 120∘à l'avant. Lorsqu'il est déployé sur une surface plane à environ 1,2 mètre au-dessus du sol, ou monté sur un mur à environ 2 mètres de haut, le PIR a une portée maximale de 10 mètres.
    -   La direction du PIR peut être modifiée en desserrant la vis de réglage de l'angle sur la base pour incliner le PIR de haut en bas.

![](<.gitbook/assets/1 (86).jpeg>)

3

-   _**Assemblée**_
    -   Le PIR est composé du corps principal et de la base. Voir les instructions ci-dessous pour fixer le corps principal sur la base ou détacher le corps principal après l'installation.
        1.  Connectez le corps principal à la base. (Figure 1)
        2.  Inclinez le PIR vers l'arrière jusqu'à ce que son dos touche la base. (Figure 2)

**Figure 1****Figure 2**

![](<.gitbook/assets/2 (81).png>)

1.  Tenez le corps principal du PIR avec votre main gauche et la base avec votre main droite. Ne touchez PAS la lentille IR, car elle pourrait être endommagée pendant le processus. (Figures 3, 4)
2.  À**verrouillage**le corps principal sur la base, tournez le corps principal avec votre main gauche loin de vous et tournez la base avec votre main droite vers vous en même temps dans la direction opposée jusqu'à ce que vous entendiez un clic. (Figure 3)
3.  À**libérer**le corps principal de la base, tournez le corps principal avec votre main gauche vers vous et appuyez vers le bas avec votre pouce droit éloigné de vous en même temps dans la direction opposée jusqu'à ce que vous entendiez un clic. (Figure 4)

**figure 3****Figure 4**

![](<.gitbook/assets/3 (79).png>)

-   _**Installation**_
    1.  Utilisez les 2 trous de montage sur la base PIR comme gabarit, percez des trous dans la surface.
    2.  Insérez les chevilles murales si vous le fixez dans du plâtre ou de la brique.
    3.  Vissez la base dans les chevilles murales. (Figure 5)
    4.  Accrochez le corps principal du PIR à la base et tournez-le pour verrouiller. (Figures 6, 7)
    5.  Desserrez les vis de réglage de l'angle puis inclinez le PIR jusqu'à ce que vous soyez satisfait de l'angle de détection. Serrez les vis pour fixer le PIR à l'angle défini. (Figure 8)

**Figure 5****Figure 6****Figure 7****Figure 8**

![](<.gitbook/assets/4 (60).jpeg>)

-   _**Directive d'installation**_
    -   **Il est recommandé d'installer le PIR aux emplacements suivants.**
        -   Dans une position telle qu’un intrus se déplacerait normalement d’un côté à l’autre du champ de vision du PIR.
        -   Où son champ de vision ne sera pas obstrué, par ex. par des rideaux, des ornements, etc.
    -   **Limites**
        -   N'installez pas le PIR dans un endroit exposé à la lumière directe du soleil, ou à proximité d'un appareil de chauffage/refroidissement et d'une ventilation.
        -   Ne dirigez pas le PIR vers une source de chaleur telle qu'un appareil de chauffage, un radiateur et une fenêtre.
        -   Ne pointez pas le PIR vers la fenêtre.
        -   Évitez les gros obstacles dans la zone de détection et évitez les objets en mouvement tels que les rideaux.

4

-   _**Informations sur la vague Z**_

**Type d'appareil:**Alarme de fumée de notification de capteur

**Type de rôle :**Signalement de l'esclave endormi (RSS)

**Groupe d'associations maximum :**6

**Prise en charge/contrôle de classe de commande**

**Support CC obligatoire :**

Informations Z-Wave Plus CC

Version CC, v2 ou plus récente

CC spécifique au fabricant

Réinitialisation de l'appareil localement CC

Niveau de puissance CC

Batterie CC

CapteurMultilevel CC, V5

Notification V4CC

Association CC, v2 ou plus récente

Informations sur le groupe d'association CC

Configuration CC

Mise à jour du micrologiciel Md CC

-   _**Groupes de Z-Wave (classe de commande d'association version 2)**_

Groupe 1 pour « LifeLine » :

Capteur multiniveau CC,V5

Notification CC,V4 (COMMANDE_CLASSE_Notification)

Batterie CC (COMMANDE_CLASSE_BASIQUE)

Réinitialisation de l'appareil localement CC

Groupe 2 pour « Ensemble de base PIR » :

CC de base (COMMANDE_CLASSE_BASIQUE)

Lorsque PIR actif, le groupe 2 enverra Basic Set (0xFF), Restore enverra (0x00)

Groupe 3 pour « Représentant de notification PIR » :

Notification CC, V4 (COMMANDE_CLASSE_NOTIFICATION)

Envoyez uniquement PIR Active (07,08) et Restore (07,00,01,08)

Groupe 4 pour « Rapport de température/lumière » (modèle Mini-PIR-LT-ZW uniquement) :

Capteur Multiniveau CC, V5 (COMMANDE_CLASSE_CAPTEUR_MULTINIVEAU)

Envoyez uniquement la température/lumière

Groupe 5 pour « Représentant des notifications HD » :

Notification CC,V4 (COMMANDE_CLASSE_NOTIFICATION)

Lorsque HD Active, le groupe 5 enverra (04,02), la restauration enverra (04,06)

Groupe 6 pour « Tamper rep » :

Notification CC,V4 (COMMANDE_CLASSE_NOTIFICATION)

Lorsque le sabotage est ouvert, le groupe 6 enverra (07,03), la restauration enverra (07,00,01,03)

5
