# GILET 009N

**Capteur de mouvement PIR (série IR-16)**

Notre algorithme de processeur de signal adaptatif numérisé permet à ce PIR de capter les mouvements dans une zone assignée et signale au panneau de commande d'activer l'alarme si un intrus croise son chemin de détection.

Le PIR se compose d’une conception en deux parties composée d’un couvercle et d’une base. Le couvercle contient toute l'électronique et l'optique et la base fournit un moyen de fixation. La base comporte des découpes pour permettre un montage sur une surface plane ou dans un coin avec un support triangulaire pour un montage en coin.

Un interrupteur anti-sabotage qui sera activé lorsque le couvercle est détaché de la base empêche tout accès non autorisé et tout retrait de la surface de montage. Le PIR peut également vous alerter des problèmes de communication et des situations de batterie faible.

Le PIR est conçu pour offrir une portée de détection typique de 12 mètres lorsqu'il est monté à 2 mètres au-dessus du sol.

**Le capteur PIR de la série IR-16 comprend les modèles suivants**:

![](<.gitbook/assets/0 (22).jpeg>)

IR-16 – Capteur PIR avec batterie au lithium 3,6 V

IRP-16 – Capteur PIR immunisé contre les animaux avec batterie au lithium 3,6 V

IR-16SL – Capteur PIR avec batterie au lithium 3V

IRP-16SL – Capteur PIR immunisé contre les animaux avec batterie au lithium 3 V

-   _**Identifier les pièces.**_

**1. Bouton de test/indicateur LED**

Le bouton de test est utilisé pour tester les performances de la radio et à des fins d'apprentissage.

L'indicateur LED est utilisé pour indiquer l'état du système.

**2. Interrupteur anti-sabotage**

L'interrupteur anti-sabotage protège le boîtier contre l'ouverture.

1.  **Isolateur de batterie**
2.  **Support de montage d'angle**
3.  **Commutateur d'activation/désactivation de la supervision (JP2)**
    -   Si le cavalier est OFF (si le lien du cavalier est retiré ou "**garé**" sur une broche), la fonction Supervision est activée.**(Par défaut d'usine pour les modèles de fréquence 868 WF)**
    -   Si le cavalier est activé, la fonction de supervision de l'IR-16 est désactivée.**(Par défaut d'usine pour**

![](<.gitbook/assets/1 (30).png>)![](<.gitbook/assets/2 (13).jpeg>)

**Modèles de fréquence 433AM et 868AM)**

-   -   -   **433FM**/**868 modèles de fréquence FM**ne prend pas en charge le cavalier JP2, la supervision est toujours activée et ne peut pas être désactivée.
    -   **Commutateur de cavalier d'augmentation de sensibilité (JP3)**
        -   Si le cavalier est OFF (si le lien du cavalier est retiré ou "**garé**" sur une broche), la sensibilité de détection de l'IR-16SL est au niveau normal. (**Paramètres d'usine pour les modèles non immunisés contre les animaux**)
        -   Si le cavalier est activé, la sensibilité de détection de l'IR-16 est élevée.**(Par défaut d'usine pour les modèles immunisés contre les animaux)**
    -   **Interrupteur anti-sabotage**
-   _**Minuterie de mise en veille**_

![](<.gitbook/assets/3 (13).jpeg>)![](<.gitbook/assets/4 (14).jpeg>)

Le PIR a un «**Temps de sommeil**" d'environ 1 minute pour économiser l'énergie. Après avoir transmis un mouvement détecté, le PIR ne retransmettra pas pendant 1 minute ; tout mouvement supplémentaire détecté pendant cette période de sommeil réinitialisera la minuterie de sommeil d'une minute. De cette manière, un mouvement continu devant un PIR n’épuisera pas indûment la batterie.

-   _**Fonction de surveillance**_

S'il est activé, lorsque le PIR est en mode de fonctionnement normal, il effectuera un auto-test périodiquement en transmettant un signal de supervision une fois toutes les 30 à 50 minutes.

Si le panneau de commande ne parvient pas à recevoir les signaux de surveillance transmis par un certain PIR pendant une durée prédéfinie, un message «**Hors service**r” sera généré.

-   _**Fonction d'augmentation de la sensibilité**_

Vous pouvez utiliser la fonction d’augmentation de sensibilité pour augmenter la sensibilité de détection de l’IR. Pour augmenter la sensibilité de détection, veuillez reconnecter le commutateur de cavalier d'augmentation de sensibilité à**SUR**position. Pour maintenir la sensibilité de détection normale, reconnectez le cavalier à**DÉSACTIVÉ**position (par défaut d’usine).

-   _**Mode d'essai**_

Le PIR peut être mis en mode Test en appuyant sur le bouton Test sur le capot avant. En mode Test, il désactivera la minuterie de mise en veille et permettra à l'indicateur LED de clignoter à chaque fois qu'un mouvement est détecté. Chaque fois que vous appuyez sur le bouton Test, le PIR transmettra un signal de test au panneau de commande pour le test de portée radio et entrera en mode test pendant 3 minutes. Il quittera automatiquement le mode test après 3 minutes et reviendra en mode normal.

-   _**Indicateur LED**_

En mode de fonctionnement normal, le voyant LED ne s'allumera pas sauf dans les situations suivantes :

-   Lorsque le PIR est en état de batterie faible, chaque fois qu'il transmet un mouvement détecté, la LED s'allume pendant environ 2 secondes.
-   Lorsque le couvercle est ouvert et que l'interrupteur anti-sabotage est violé, la LED s'allume pendant 2 secondes. pour indiquer qu'il transmet le

1

“**Altérer**» signale-t-il.

-   -   Lorsque la condition de sabotage persiste, chaque fois qu'il transmet un mouvement détecté, la LED s'allumera.
    -   Lorsque le PIR est en mode Test, la LED s'allume à chaque fois qu'un mouvement est détecté.
-   _**Batterie**_

Le capteur de mouvement PIR de la série IR-16 utilise différentes piles au lithium comme source d'alimentation :

-   Les modèles non SL utilisent une pile au lithium AA 3,6 V (ER14505) comme source d'alimentation.
-   Les modèles SL utilisent une pile au lithium 3 V 2/3 A (CR123) comme source d'alimentation.

Lorsqu'une faible tension de batterie est détectée, un signal de batterie faible sera envoyé au panneau de commande avec des transmissions de signal régulières pour que le panneau de commande affiche l'état en conséquence.

La batterie est installée en usine avant expédition avec un isolant inséré.

_\\<NOTE>_

-   -   -   -   Lors du changement des piles, après avoir retiré les anciennes piles, appuyez deux fois sur l'interrupteur anti-sabotage pour les décharger complètement avant d'insérer de nouvelles piles.
-   _**Commencer**_
    -   Retirez l'isolant de la batterie pour activer la batterie.
    -   L'indicateur LED clignote pendant 30 secondes. (Le PIR s'échauffe). Pendant la période de préchauffage, le PIR ne sera pas activé. Il est recommandé de rester à l'écart de la zone de détection pendant cette période. Une fois la période de préchauffage terminée, la LED s'éteindra et le PIR sera prêt à fonctionner.
    -   Mettez le panneau de commande en mode apprentissage, reportez-vous au manuel du panneau de commande pour plus de détails.
    -   Appuyez sur le bouton de test sur le capot avant.
    -   Reportez-vous au manuel du panneau de commande pour terminer le processus d'apprentissage.
    -   Une fois le PIR appris, placez le panneau de commande sur «**Test de marche**", maintenez le PIR à l'emplacement souhaité et appuyez sur le bouton Test pour confirmer que cet emplacement est à portée du signal du panneau de commande, reportez-vous au manuel du panneau de commande pour terminer le test de marche.
    -   Lorsque vous êtes convaincu que le PIR fonctionne à l'emplacement choisi, vous pouvez procéder au montage.
-   _**Méthode de montage**_
    -   Le PIR est conçu pour être monté sur une surface plane ou dans un coin avec les vis de fixation et les chevilles fournies.
    -   La base comporte des découpes, là où le plastique est plus fin, à des fins de montage. Quatre découpes sont destinées à la fixation en surface.
    -   Pour le montage en coin, un support triangulaire est fourni pour ajouter une protection anti-effraction arrière. Montez d'abord le support triangulaire sur le mur avec les deux bâtons de pointage en haut face à vous. Fixez le PIR sur les crochets du support triangulaire ou vissez le PIR dessus.
    -   Pour le montage en surface, un support rotatif en option est fourni pour permettre aux utilisateurs d'ajuster la plage de détection. Grâce au support rotatif, l'IR-16 peut pivoter de 80 degrés horizontalement et de 70 degrés verticalement pour offrir une couverture optimale.
        -   **Montage en coin :**

I. Casser les deux découpes du support triangulaire.

![](<.gitbook/assets/5 (9).jpeg>)

1.  En utilisant les deux trous comme gabarit, percez des trous dans la surface du coin.
2.  Insérez les chevilles murales.

IV. Vissez le support triangulaire dans les chevilles murales avec les deux bâtons de pointage en haut face à vous (utilisez un tournevis Philips).

1.  Fixez le PIR sur les crochets du support triangulaire.

VI. Si nécessaire, ouvrez le PIR en retirant l'ensemble vis de fixation et couvercle à l'aide d'un tournevis Philips.

VII. Percez les ouvertures défonçables appropriées pour la fixation des coins.

VIII. En utilisant les découpes de fixation d'angle comme modèle, percez à nouveau des trous dans la surface du coin.

![](<.gitbook/assets/6 (13).jpeg>)

IX. Insérez les chevilles murales si vous le fixez dans du plâtre ou de la brique.

1.  Fixez le PIR sur les crochets du support triangulaire.

XI. Vissez la base dans les chevilles murales à l'aide d'un tournevis Philips.

XII. Revissez le couvercle sur sa base à l'aide d'un tournevis Philips.

-   **Montage en saillie :**

1.  Retirez la vis de fixation et l'ensemble couvercle à l'aide d'un tournevis Philips.
2.  Percez les trous appropriés sur la base.
3.  En utilisant les trous comme gabarit, percez des trous dans la surface.

IV. Insérez les chevilles murales si vous le fixez dans du plâtre ou de la brique.

-   -   1.  Vissez la base dans les chevilles murales à l'aide d'un tournevis Philips.

VI. Revissez le couvercle sur sa base à l'aide d'un tournevis Philips.

-   **Montage en surface avec support rotatif (article en option, vendu séparément) :**Le support rotatif peut être monté au mur à l'aide des vis fournies.
    1.  Vissez le support rotatif dans le mur.

1.  Insérez les 3 crochets du support rotatif dans les 3 trous de la base en conséquence.

2

-   -   1.  Faites pivoter le support pour obtenir la plage de détection appropriée et serrez la vis de fixation.
-   _**Installation**_
    -   Décidez de l'emplacement du PIR et s'il doit être monté en coin ou en surface.
    -   Une fois le site d'installation sélectionné, suivez les étapes décrites ci-dessus pour monter le PIR.
    -   Appuyez sur le bouton Test pour accéder au mode Test. Parcourez la zone protégée en notant quand la LED s'allume et vérifiez que la couverture de détection est adéquate.
    -   Lorsque la couverture de détection s'avère satisfaisante, l'installation est désormais terminée.
-   _**Recommandations d'installation**_

**PIR régulier**

-   La portée de détection peut atteindre 12 mètres si le PIR est monté à 2 mètres au-dessus du sol.

**PIR immunisé contre les animaux**

-   Le PIR Pet-Immune prend en charge la fonction d'immunité aux animaux et ne détectera pas les animaux pesant jusqu'à 27 kg dans un rayon de 7 mètres afin de minimiser les situations de fausse alarme.
-   Si nécessaire, vous pouvez ajuster la hauteur du PIR en fonction de la taille de votre animal pour une performance immunitaire optimale. Un emplacement d'installation plus élevé offrira un plus grand espace immunisé contre les animaux de compagnie, mais augmentera également l'angle mort sous le PIR.

![](<.gitbook/assets/7 (12).jpeg>)

Pour tirer pleinement parti du PIR, les directives suivantes doivent être prises en compte :

-   **Il est recommandé d'installer le PIR aux emplacements suivants**
    -   Montez le détecteur à une hauteur de 1,9 M à 2,0 M pour de meilleures performances :

_\\<IMPORTANT NOTE>_

-   -   Lorsque vous décidez de la hauteur du site de montage du PIR, n'oubliez pas de prendre en compte l'éventuel angle mort. L'angle mort sous le PIR s'agrandit proportionnellement à la hauteur du site de montage du PIR.
    -   Veuillez noter que les performances sont affectées par des facteurs externes, tels que la hauteur de l'objet détecté, la plage de détection souhaitée, la zone d'installation… etc. La hauteur de montage suggérée peut être ajustée en fonction des facteurs réels de l'environnement d'installation.
-   Lorsque l'IR-16 est monté avec un support rotatif, il n'aura pas la zone de détection normale (comme dans le diagramme ci-dessus) ni la plage d'immunité typique aux animaux de compagnie.
    -   Montez là où les animaux ne peuvent pas accéder à la zone de détection en grimpant sur des meubles ou d'autres objets.
    -   Ne dirigez pas le détecteur vers des escaliers sur lesquels les animaux peuvent monter.
    -   Dans une position telle qu’un intrus se déplacerait normalement d’un côté à l’autre du champ de vision du PIR.
    -   Dans un coin pour donner la vue la plus large.
    -   Où son champ de vision ne sera pas obstrué, par ex. par des rideaux, des ornements, etc.
-   **Limites**
    -   Ne positionnez pas un PIR pour regarder directement une porte protégée par un contact de porte, cela pourrait provoquer la transmission des signaux radio du contact de porte et du PIR au même instant lors de l'entrée, s'annulant mutuellement.
    -   N'installez pas le PIR complètement exposé à la lumière directe du soleil.
    -   Évitez d'installer le PIR dans des zones où les appareils peuvent provoquer un changement rapide de température dans la zone de détection, c'est-à-dire un climatiseur, un chauffage, etc.
    -   Évitez les gros obstacles dans la zone de détection.
    -   Ne pas pointer directement vers des sources de chaleur, par ex. feux ou chaudières, et pas au-dessus des radiateurs.
    -   Évitez de déplacer des objets dans la zone de détection, par exemple un rideau, une tenture murale, etc.

3
