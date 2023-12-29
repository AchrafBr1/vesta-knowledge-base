# VESTA 051

-   Capteur de mouvement PIR pour rideau (IRC-29)

Le PIR détecte la signature infrarouge pour capter les mouvements dans une zone assignée et signale au panneau de commande d'activer l'alarme si un intrus croise son chemin de détection.

Le PIR se compose d’une conception en deux parties composée d’un couvercle et d’une base. Le PIR contient toute l'électronique et l'optique et la base fournit un moyen de fixation. La base comporte des découpes pour permettre le montage sur une surface plane ou au plafond.

Le PIR dispose d'un interrupteur anti-sabotage qui sera activé lorsque le couvercle est ouvert ou lorsqu'il est retiré de la surface montée. Il peut également vous alerter des problèmes de communication et des situations de batterie faible.

-   ![](<.gitbook/assets/0 (11).jpeg>)_**Identifier les pièces**_

1.  **Lentille PIR**
2.  **Bouton Apprendre/Test**

Le bouton de test est utilisé pour tester les performances de la radio et à des fins d'apprentissage.

1.  **Indicateur LED**

L'indicateur LED se trouve à l'intérieur du capot avant et n'est visible que lorsqu'il est activé.

1.  **Compartiment à piles**

Le PIR utilise 1 pile CR123A (3 V) comme source d'alimentation.

1.  **Interrupteur anti-sabotage**

L'interrupteur anti-sabotage protège le PIR contre l'ouverture non autorisée du couvercle ou le retrait de la surface de montage.

1.  **Commutateur d'activation/désactivation de la supervision (JP2)**

![jumper close](<.gitbook/assets/1 (18).png>)![jumper open](<.gitbook/assets/2 (21).png>)

**Cavalier**

si le cavalier est retiré ou "**garé**» sur une épingle.

**Cavalier**

Le cavalier est inséré reliant les deux broches

\-Lorsque le cavalier est réglé sur ON, la supervision est désactivée.**(Par défaut d'usine pour le modèle 433AM)**

\-Lorsque le cavalier est réglé sur OFF, la supervision est activée.**(Par défaut d'usine pour le modèle 868WF)**

_(**868FM**&**869FM**&**F1**des modèles**NE PAS**avez JP2, la supervision est toujours activée)._

1.  **Commutateur de cavalier d'augmentation de sensibilité (JP3)**

![jumper open](<.gitbook/assets/3 (20).png>)

\-Si le cavalier est désactivé (si le lien du cavalier est retiré ou « garé » sur une broche), la sensibilité de détection du PIR est au niveau normal.**(Défaut de fabrication)**

![jumper close](<.gitbook/assets/4 (19).png>)

\-Si le cavalier est sur ON, la sensibilité de détection des PIR est élevée.

1.  **Isolateur de batterie**

-   _**Minuterie de mise en veille**_

Le PIR a un «**Temps de sommeil**" d'environ 1 minute pour économiser l'énergie. Après avoir transmis un mouvement détecté, le PIR ne retransmettra pas pendant 1 minute ; tout mouvement supplémentaire détecté pendant cette période de sommeil prolongera la durée du sommeil d'une minute supplémentaire. De cette façon, un mouvement continu devant un PIR n’épuisera pas indûment la batterie.

-   _**Fonction de surveillance**_

S'il est activé, le PIR effectuera un auto-test périodiquement en transmettant un signal de supervision une fois toutes les 30 à 50 minutes.

Si le panneau de commande ne parvient pas à recevoir les signaux de supervision transmis par un certain PIR pendant une durée prédéfinie, un message «**Hors service**r” sera généré.

-   _**Ajustement de la sensibilité**_

Vous pouvez utiliser la fonction d’augmentation de sensibilité pour augmenter la sensibilité de détection du PIR. Pour augmenter la sensibilité de détection, connectez le cavalier (JP3) ou le**SUR**position (par défaut d'usine. Pour maintenir une sensibilité de détection normale, débranchez le cavalier (JP3) ou le**DÉSACTIVÉ**position.

-   _**Mode d'essai**_

Le PIR peut être mis en mode Test en appuyant sur le bouton Test. En mode Test, il désactivera la minuterie de mise en veille et permettra à l'indicateur LED de clignoter à chaque fois qu'un mouvement est détecté. Chaque fois que vous appuyez sur le bouton de test, le PIR transmettra un signal de test au panneau de commande pour un test de portée radio et entrera en mode test pendant 3 minutes. Il quittera automatiquement le mode test après 3 minutes et reviendra en mode normal.

-   _Indicateur LED_

En mode de fonctionnement normal, le voyant LED s'allume dans les situations suivantes (pour les modèles F1, le voyant clignote à la place) :

-   Lorsqu'un mouvement est détecté dans des conditions de batterie faible.
-   Lorsque le couvercle est ouvert/retiré de la surface de montage et que l'interrupteur anti-sabotage est déclenché.
-   Lorsqu'un mouvement est détecté si la condition de sabotage persiste.
-   Lorsqu'un mouvement est détecté en mode Test.
-   Lorsque le bouton de test est enfoncé dans des conditions de sabotage ou si le PIR est sous batterie faible.
-   _Batterie_
-   Le PIR utilise une pile 3V CR123A comme source d'alimentation.
-   Le PIR dispose d'une fonction de détection de batterie faible. Si une faible tension de batterie est détectée, un signal de batterie faible sera envoyé au panneau de commande avec des transmissions de signal régulières pour que le panneau de commande affiche l'état en conséquence.
-   Pour chaque installation, la batterie est installée en usine avant expédition avec un isolant inséré. Retirez l'isolant pour activer la batterie.
-   Lorsque vous changez les piles, retirez les anciennes piles et appuyez deux fois sur l'interrupteur anti-sabotage pour les décharger avant d'insérer de nouvelles piles.
-   _Commencer_
-   Retirez l'isolant de la batterie pour activer la batterie.
-   L'indicateur LED clignote pendant 30 secondes. (Le PIR s'échauffe). Pendant la période de préchauffage, le PIR ne sera pas activé. Il est recommandé de rester à l'écart de la zone de détection pendant cette période. Une fois la période de préchauffage terminée, la LED s'éteindra et le PIR sera prêt à fonctionner.
-   Mettez le panneau de commande en mode apprentissage, reportez-vous au manuel du panneau de commande pour plus de détails.
-   Appuyez sur le bouton Test.
-   Reportez-vous au manuel du panneau de commande pour terminer le processus d'apprentissage.
-   Une fois le PIR appris, placez le panneau de commande sur «**Test de marche**", maintenez le PIR à l'emplacement souhaité et appuyez sur le bouton Test pour confirmer que cet emplacement est à portée du signal du panneau de commande, reportez-vous au manuel du panneau de commande pour terminer le test de marche.
-   Lorsque vous êtes convaincu que le PIR fonctionne à l'emplacement choisi, vous pouvez procéder au montage.
-   _Couverture de détection PIR_
-   Lorsqu'il est monté verticalement, le PIR a une couverture de détection horizontale de 10° et une couverture de détection verticale de 110° vers l'avant.
-   Le PIR ne sera activé que par des mouvements sur la couverture horizontale de 10°.
-   Le PIR peut être monté verticalement, horizontalement sur la surface du mur ou au plafond. Différentes méthodes de montage offrent différentes couvertures et portées de détection PIR (veuillez vous référer à**Méthodes de montage**ci-dessous pour plus de détails).
-   _Méthodes de montage_
-   Le PIR est conçu pour être monté sur une surface plane sur un mur ou sur un plafond avec les vis de fixation et les chevilles fournies.
-   Si le PIR monté est retiré de force, la zone de rupture du sabotage sera laissée sur le mur séparée du PIR, le sabotage sera alors déclenché.
-   ![未命名-5](<.gitbook/assets/5 (5).jpeg>)La base comporte deux découpes, où le plastique est plus fin et peut être cassé à des fins de montage.

1.  Retirez la vis de fixation et l'ensemble couvercle.
2.  Brisez les découpes à l’intérieur de la base.
3.  En utilisant les trous comme gabarit, percez des trous dans la surface.
4.  Insérez les chevilles murales si vous le fixez dans du plâtre ou de la brique.
5.  Vissez la base dans les chevilles murales.
6.  Vissez le couvercle sur la base.

-   Il existe différentes méthodes de montage, notamment les montages verticaux/horizontaux et au plafond, et chacune d'elles a une application différente. Veuillez vous référer aux méthodes de montage ci-dessous.

**Support mural vertical :**

-   Lorsqu'il est monté verticalement, le PIR a une portée de détection de 10 mètres contre les mouvements horizontaux uniquement.
-   Il est suggéré de monter le PIR verticalement entre 1,4 et 1,6 mètres au-dessus du sol.
-   Évitez de monter à plus de 1,7 mètres, sinon la plage de détection PIR pourrait être affectée.

**Support mural horizontal :**

-   Lorsqu'il est monté horizontalement, le PIR a une portée de détection de 5 mètres contre les mouvements verticaux uniquement. Cette pratique est généralement utilisée pour protéger les intrus d’un puits de lumière ou d’une trappe de toit.
-   Évitez de monter en dessous de 2,2 mètres, ce qui pourrait affecter les performances de détection.

**Verticale****Horizontal**

![](<.gitbook/assets/6 (8).png>)![](<.gitbook/assets/7 (5).png>)

**Montage au plafond :**

-   Montez le PIR au plafond pour regarder vers le bas au-dessus d'une porte ou d'une fenêtre.
-   Lorsqu'il est monté au plafond, le PIR ne peut détecter que les mouvements verticaux par rapport au PIR dans la plage de détection.
-   Lorsqu'il est monté à 2,4~D'une hauteur de 3 mètres et en regardant vers le bas, le PIR a une couverture d'environ**5**mètres au niveau du sol.
-   Évitez de monter à plus de 4 mètres, ce qui pourrait affecter les performances de détection.

![](<.gitbook/assets/8 (5).png>)

-   _Installation_
-   Décidez de l'emplacement du PIR s'il doit être horizontal/vertical ou monté au plafond.
-   Une fois le site d'installation sélectionné, suivez les étapes décrites ci-dessus pour monter le PIR.
-   Appuyez sur le bouton Test pour accéder au mode Test. Parcourez la zone protégée en notant quand la LED s'allume et vérifiez que la couverture de détection est adéquate.
-   Lorsque la couverture de détection s'avère satisfaisante, l'installation est désormais terminée.
-   _Recommandations d'installation_

\\<Important NOTE>

-   Lorsque vous décidez de la hauteur du site de montage du PIR, n'oubliez pas de prendre en compte l'éventuel angle mort. L'angle mort sous le PIR s'agrandit proportionnellement à la hauteur du site de montage du PIR.
-   Veuillez noter que les performances sont affectées par des facteurs externes, tels que la hauteur de l'objet détecté, la plage de détection souhaitée, la zone d'installation… etc. La hauteur de montage suggérée peut être ajustée en fonction des facteurs réels de l'environnement d'installation.
-   Dans une position telle qu’un intrus se déplacerait normalement d’un côté à l’autre du champ de vision du PIR.
-   Où son champ de vision ne sera pas obstrué, par ex. par des rideaux, des ornements, etc.
-   **Limites**
-   Ne positionnez pas un PIR pour regarder directement une porte protégée par un contact de porte, cela pourrait provoquer la transmission des signaux radio du contact de porte et du PIR au même instant lors de l'entrée, s'annulant mutuellement.
-   N'installez pas le PIR complètement exposé à la lumière directe du soleil.
-   Évitez d'installer le PIR dans des zones où les appareils peuvent provoquer un changement rapide de température dans la zone de détection, c'est-à-dire un climatiseur, un chauffage, etc.
-   Évitez les gros obstacles dans la zone de détection.
-   Ne pas pointer directement vers des sources de chaleur, par ex. feux ou chaudières, et pas au-dessus des radiateurs.
-   Évitez de déplacer des objets dans la zone de détection, par exemple un rideau, une tenture murale, etc.
