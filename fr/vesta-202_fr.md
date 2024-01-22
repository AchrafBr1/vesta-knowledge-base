# VESTA 202

**Capteur de mouvement PIR série IR(P)-29**

Le PIR détecte la signature infrarouge pour capter les mouvements dans une zone assignée et signale au panneau de commande d'activer l'alarme si un intrus croise son chemin de détection.

Le PIR se compose d’une conception en deux parties composée d’un couvercle et d’une base. Le couvercle contient toute l'électronique et l'optique et la base fournit un moyen de fixation. La base comporte des découpes pour permettre le montage sur une surface plane ou dans un coin

Le PIR dispose d'un interrupteur anti-sabotage qui sera activé lorsque le couvercle est ouvert. Il peut également vous alerter des problèmes de communication et des situations de batterie faible.

Le PIR est conçu pour offrir une portée de détection typique de 12 mètres lorsqu'il est monté à 2 mètres au-dessus du sol.

Les modèles Pet-Immune du capteur PIR de la série IR-29 prennent en charge la fonction d'immunité aux animaux et ne détecteront pas les animaux pesant jusqu'à 27 kg dans un rayon de 7 mètres afin de minimiser les situations de fausse alarme.

**Le capteur PIR de la série IR-29 comprend les modèles suivants**:

IR-29 / IR-29 F1 – Capteur PIR avec piles alcalines

IRP-29 / IRP-29 F1 – Capteur PIR Pet Immune avec piles alcalines

IR-29SL / IR-29SL-F1 – Capteur PIR avec batterie au lithium.

IRP-29SL / IRP-29SL-F1 – Capteur PIR immunisé contre les animaux avec batterie au lithium

![](<.gitbook/assets/0 (53).png>)![](<.gitbook/assets/1 (72).jpeg>)

-   _**Identifier les pièces**_

**1. Bouton de test/indicateur LED**

Le bouton de test est utilisé pour tester les performances de la radio et à des fins d'apprentissage.

L'indicateur LED est utilisé pour indiquer l'état du système.

-   1.  **Isolateur de batterie**

1.  **Commutateur d'activation/désactivation de la supervision (JP2)**

![](<.gitbook/assets/2 (67).jpeg>)

**Cavalier**

![](<.gitbook/assets/3 (68).png>)

**Cavalier**

![](<.gitbook/assets/4 (57).jpeg>)

Le lien de cavalier est inséré

si le cavalier est retiré ou "**garé**”

reliant les deux broches

sur une épingle.

-   Lorsqu’elle est définie sur ON, la supervision est désactivée.**(Par défaut d'usine pour les modèles de fréquence 433AM)**
-   Lorsqu'elle est définie sur OFF, la supervision est activée.**(Par défaut d'usine pour les modèles de fréquence 868WF)**

**433FM**et**Modèles de fréquence 868FM**ne prend pas en charge le cavalier JP2, la supervision est activée et ne peut pas être désactivée.

**4. Cavalier d'augmentation de sensibilité (JP3)**

-   -   Lorsqu'elle est réglée sur OFF, la sensibilité de détection du PIR est au niveau normal.**(Par défaut d'usine pour les non**

**Modèles immunisés contre les animaux)**

-   -   Lorsqu'elle est réglée sur ON, la sensibilité de détection des PIR est élevée. (Par défaut d'usine pour les modèles Pet-Immune)

1.  **Interrupteur anti-sabotage**

L'interrupteur anti-sabotage protège le PIR contre toute ouverture non autorisée du couvercle.

![](<.gitbook/assets/5 (68).png>)

-   _**Minuterie de mise en veille**_

Le PIR a un «**Temps de sommeil**" d'environ 1 minute pour économiser l'énergie. Après avoir transmis un message détecté

mouvement, le PIR ne retransmettra pas pendant 1 minute ; tout mouvement supplémentaire détecté pendant cette période de sommeil prolongera la durée du sommeil d'une minute supplémentaire. De cette manière, un mouvement continu devant un PIR n’épuisera pas indûment la batterie.

![](<.gitbook/assets/6 (47).jpeg>)

-   _**Fonction de surveillance**_

S'il est activé (voir tableau ci-dessus), lorsque le PIR est en mode de fonctionnement normal, il effectuera un auto-test périodiquement en transmettant un signal de supervision une fois toutes les 30 à 50 minutes.

Si le panneau de commande ne parvient pas à recevoir les signaux de surveillance transmis par un certain PIR pendant une durée prédéfinie, un message «**Hors service**r” sera généré.

![](<.gitbook/assets/7 (43).png>)

-   _**Fonction d'augmentation de la sensibilité**_

Vous pouvez utiliser la fonction d’augmentation de sensibilité pour augmenter la sensibilité de détection du PIR. Pour augmenter la sensibilité de détection, connectez le cavalier (JP3) ou le**SUR**position (par défaut d’usine pour les modèles Pet-Immune). Pour maintenir une sensibilité de détection normale, débranchez le cavalier (JP3) ou le**DÉSACTIVÉ**position (par défaut d'usine pour les modèles non immunisés contre les animaux).

![](<.gitbook/assets/8 (43).png>)

-   _**Mode d'essai**_

Le PIR peut être mis en mode Test en appuyant sur le bouton Test sur le capot avant. En mode Test, il désactivera la minuterie de mise en veille et permettra à l'indicateur LED de clignoter à chaque fois qu'un mouvement est détecté. Chaque fois que vous appuyez sur le bouton de test, le PIR transmettra un signal de test au panneau de commande pour un test de portée radio et entrera en mode test pendant 3 minutes. Le mode test expirera après 3 minutes.

![](<.gitbook/assets/9 (31).jpeg>)

-   _**Indicateur LED**_

En mode de fonctionnement normal, le voyant LED s'allume dans les situations suivantes (pour les modèles F1, le voyant clignote à la place) :

-   -   Lorsqu'un mouvement est détecté dans des conditions de batterie faible
    -   Lorsque le couvercle est ouvert et que l'interrupteur anti-sabotage est déclenché.
    -   Lorsqu'un mouvement est détecté si la condition de sabotage persiste.
    -   Lorsqu'un mouvement est détecté en mode Test
    -   Lorsque le bouton de test est enfoncé dans des conditions de sabotage ou si le PIR est sous batterie faible.
-   _**Batterie**_

![](<.gitbook/assets/10 (23).jpeg>)

Le capteur de mouvement PIR de la série IR-29 utilise des piles alcalines ou au lithium comme source d'alimentation :

-   Les modèles alimentés par des piles alcalines utilisent deux piles alcalines AA de 1,5 V comme source d'alimentation.
-   Les modèles alimentés au lithium utilisent une batterie au lithium 3 V 2/3 A (EL123AP) comme source d'alimentation.

1

Le PIR dispose d'une fonction de détection de batterie faible. Si une faible tension de batterie est détectée, un signal de batterie faible sera envoyé au panneau de commande avec des transmissions de signal régulières pour que le panneau de commande affiche l'état en conséquence.

Pour chaque installation, la batterie est installée en usine avant expédition avec un isolant inséré.

![](<.gitbook/assets/11 (33).png>)

_\\<NOTE>_

-   -   -   -   Lors du changement des piles, après avoir retiré les anciennes piles, appuyez deux fois sur l'interrupteur anti-sabotage pour les décharger complètement avant d'insérer de nouvelles piles.
-   _**Commencer**_
    -   Retirez l'isolant de la batterie pour activer la batterie.
    -   L'indicateur LED clignote pendant 30 secondes. (Le PIR s'échauffe). Pendant la période de préchauffage, le PIR ne sera pas activé. Une fois la période de préchauffage terminée, la LED s'éteindra et le PIR sera prêt à fonctionner.
    -   Mettez le panneau de commande en mode apprentissage, reportez-vous au manuel du panneau de commande pour plus de détails.
    -   Appuyez sur le bouton de test sur le capot avant.
    -   Reportez-vous au manuel du panneau de commande pour terminer le processus d'apprentissage.
    -   Une fois le PIR appris, placez le panneau de commande sur «**Test de marche**” mode, hold the PIR in the desired location, and press the Test button to confirm this location is within signal range of the Control Panel, refer to Control Panel manual to complete Walk Test.
    -   Lorsque vous êtes convaincu que le PIR fonctionne à l'emplacement choisi, vous pouvez procéder au montage.
-   _**Méthode de montage**_
    -   Le PIR est conçu pour être monté sur une surface plane ou dans un coin avec les vis de fixation et les chevilles fournies.
    -   La base comporte des découpes, où le plastique est plus fin et peut être cassé à des fins de montage. Deux découpes sont destinées à la fixation en surface et quatre sont destinées à la fixation en coin, comme indiqué sur l'image.
    -   Pour le montage en coin, un support triangulaire est fourni pour ajouter une protection anti-effraction arrière. Le support comprend également deux découpes à monter au mur.
    -   Pour le montage en surface, un support rotatif en option est fourni pour permettre aux utilisateurs d'ajuster la plage de détection. Grâce au support rotatif, l'IR-29 peut être pivoté de 80 degrés horizontalement et de 70 degrés verticalement pour offrir une couverture optimale.
        -   **Montage en coin :**

I.Briser les KO aux quatre coins.

![](<.gitbook/assets/12 (22).jpeg>)![](<.gitbook/assets/13 (26).jpeg>)![](<.gitbook/assets/14 (22).jpeg>)

1.  En utilisant les quatre trous comme gabarit, percez des trous dans la surface du coin.
2.  Insérez les chevilles murales

IV. Vissez la base dans la cheville murale.

-   1.  Vissez le couvercle sur la base.
-   **Montage en angle avec support triangulaire :**

Le support triangulaire peut être monté au mur à l'aide de vis fournies ou de pastilles adhésives double face.

![](<.gitbook/assets/15 (25).png>)![](<.gitbook/assets/16 (15).jpeg>)

Montage à vis

1.  Percez les deux découpes du support triangulaire.
2.  En utilisant les deux trous comme gabarit, percez des trous dans la surface du coin. Insérez les chevilles murales.
3.  Vissez le support triangulaire dans les chevilles murales avec les deux bâtons de pointage en haut face à vous.

IV. Fixez le PIR sur les crochets du support triangulaire. Montage autocollant

![](<.gitbook/assets/17 (21).png>)

1.  Le coin de montage doit être propre, sec et lisse. Nettoyer le coin de montage avec un dégraissant adapté si nécessaire.
2.  Deux pastilles adhésives double face sont fixées sur le support triangulaire avant expédition.

III. Retirez le revêtement de protection des pastilles adhésives double face.

IV. Fixez le support triangulaire sur le coin souhaité avec les deux bâtons de pointage en haut face à vous.

-   1.  Fixez le PIR sur les crochets du support triangulaire.
-   **Montage en saillie :**
    1.  Retirez la vis de fixation et l'ensemble couvercle.

1.  Percez les trous à l'intérieur de la base

![](<.gitbook/assets/18 (13).jpeg>)

1.  En utilisant les trous comme gabarit, percez des trous dans la surface.

IV. Insérez les chevilles murales si vous le fixez dans du plâtre ou de la brique.

-   1.  Vissez la base dans les chevilles murales.

VI. Vissez le couvercle sur la base.

-   **Montage en surface avec support rotatif (article en option, vendu séparément) :**Le support rotatif peut être monté au mur à l'aide des vis fournies.
    1.  Vissez le support rotatif dans le mur.

VI. Insérez les 3 crochets du support rotatif dans les 3 trous de la base en conséquence.

VII. Faites pivoter le support pour obtenir la plage de détection appropriée et serrez la vis de fixation.

![](<.gitbook/assets/19 (8).jpeg>)

-   _**Installation**_
    -   Décidez de l'emplacement du PIR et s'il doit être monté en coin ou en surface.
    -   Une fois le site d'installation sélectionné, suivez les étapes décrites ci-dessus pour monter le PIR.
    -   Appuyez sur le bouton Test pour accéder au mode Test. Parcourez la zone protégée en notant quand la LED s'allume et vérifiez que la couverture de détection est adéquate.
    -   Lorsque la couverture de détection s'avère satisfaisante, l'installation est désormais terminée.
-   _**Recommandations d'installation**_

![](<.gitbook/assets/20 (14).jpeg>)

Le PIR est conçu pour offrir une portée de détection typique de 12 mètres lorsqu'il est monté à 2 mètres au-dessus du sol.

Pour la série Pet-Immune PIR, il offre une portée PET IMMUNE typique de 7 mètres lorsqu'il est monté à 1,9-2,0 mètres au-dessus du sol. S'il est monté plus haut au-dessus du sol, il offre une portée PET IMMUNE plus grande.

Pour tirer pleinement parti du PIR, les directives suivantes doivent être prises en compte :

-   **Il est recommandé d'installer le PIR aux emplacements suivants**
    -   Montez le détecteur à une hauteur de 1,9 M à 2,0 M pour de meilleures performances :

2

_\\<IMPORTANT NOTE>_

-   Pour obtenir les performances les plus souhaitables de la série Pet-Immune PIR, n'oubliez pas d'ajuster la hauteur du site de montage du PIR par rapport à la hauteur de l'animal le plus grand de la maison. Les animaux de compagnie plus grands que la moyenne peuvent nécessiter que le PIR soit monté plus haut pour l'immunité des animaux.





Lorsque vous décidez de la hauteur du site de montage du PIR, n'oubliez pas de prendre en compte l'éventuel angle mort. L'angle mort sous le PIR s'agrandit proportionnellement à la hauteur du site de montage du PIR.

Veuillez noter que les performances sont affectées par des facteurs externes, tels que la hauteur de l'objet détecté, la plage de détection souhaitée, la zone d'installation… etc. La hauteur de montage suggérée peut être ajustée en fonction des facteurs réels de l'environnement d'installation.

-   Lorsque l'IR-29 est monté avec un support rotatif, il n'aura pas la zone de détection normale (comme dans le diagramme ci-dessus) ni la plage d'immunité typique aux animaux de compagnie.
    -   Montez là où les animaux ne peuvent pas accéder à la zone de détection en grimpant sur des meubles ou d'autres objets.
    -   Ne dirigez pas le détecteur vers des escaliers sur lesquels les animaux peuvent monter.
    -   Dans une position telle qu’un intrus se déplacerait normalement d’un côté à l’autre du champ de vision du PIR.
    -   Dans un coin pour donner la vue la plus large.
    -   Où son champ de vision ne sera pas obstrué, par ex. par des rideaux, des ornements, etc.
-   **Limites**

|  Ne pas installer à l'extérieur.                                                  |  Évitez les gros obstacles dans la zone de détection.                     |
| ---------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
|                                                                                    |                                                                            |
|  N'installez pas le PIR complètement exposé à la lumière directe                  |  Évitez les vapeurs ou l'humidité élevée qui peuvent provoquer            |
| lumière du soleil.                                                                 | condensation.                                                              |
|                                                                                    |                                                                            |
|  Évitez de déplacer des objets dans la zone de détection, c'est-à-dire un rideau, |  Évitez la lumière réfléchie par des surfaces lumineuses, par ex. miroir, |
| tenture murale, etc.                                                               | fenêtre.                                                                   |
|                                                                                    |                                                                            |
|  Évitez d'installer le PIR dans des zones où les appareils peuvent                |  Évitez les surfaces réfléchissantes dans la zone de détection. Reflété   |
| provoquer un changement rapide de température dans la détection                    | les signatures infrarouges peuvent conduire à de fausses alarmes.          |
| zone, c'est-à-dire climatiseur, radiateurs, etc.                                   |                                                                            |
|                                                                                    |                                                                            |
| 3                                                                                  |                                                                            |
