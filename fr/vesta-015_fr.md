# VESTA 015

**Capteur de mouvement PIR à dôme (IRD-23 / IRD-23SL)**

Le capteur de mouvement Dome PIR est conçu pour être monté au plafond pour fournir une couverture de détection à 360° sans angles morts pour capter les mouvements dans une zone assignée et signale au panneau de commande d'activer l'alarme si un intrus croise son chemin de détection.

Le PIR se compose d'une conception en deux parties composée d'un corps principal PIR et d'un couvercle arrière pour le montage mural. Le corps principal contient toute l’électronique et l’optique et la base fournit un moyen d’installation.

Le corps principal du PIR est doté d'un interrupteur anti-sabotage qui sera activé lorsque le corps principal est retiré du capot arrière pour empêcher tout accès non autorisé et tout retrait de la surface de montage. Le PIR peut également vous alerter des problèmes de communication et des situations de batterie faible.

Le Dome PIR comprend 2 modèles :

IRD-23 : Alimenté par 2 piles alcalines AA de 1,5 V

IRD-23SL : alimenté par 1 pile au lithium CR123A 3 V

-   _**Identifier les pièces.**_

**1. Bouton de test, également appelé indicateur LED**

Le bouton de test sert également d'indicateur LED. Le bouton de test est utilisé pour tester les performances de la radio et à des fins d'apprentissage. L'indicateur LED est utilisé pour indiquer l'état du système.

1.  **Capteur IR**
2.  **Commutateur de cavalier d'augmentation de sensibilité (JP3)**

![](<.gitbook/assets/0 (25).jpeg>)

C'est un cavalier à 2 broches

-   Si le cavalier est OFF (si le lien du cavalier est retiré ou "**garé »**sur une épingle),

la sensibilité de détection du PIR est au niveau normal. (**Défaut de fabrication**)

![](<.gitbook/assets/1 (18).jpeg>)

-   -   Si le cavalier est sur ON, la sensibilité de détection du PIR est élevée.

1.  **Interrupteur anti-sabotage**

L'interrupteur anti-sabotage protège le PIR du retrait de l'emplacement de montage.

**5. Battery Compartment**

IRD-23 : 2 piles alcalines AA 1,5 V.

IRD-23SL : 1 pile CR123A lithium 3V

-   1.  **Trous de montage**
    2.  **Crochets**
    3.  **Débouchures de montage au plafond (intérieur)**
-   _**Indicateur LED**_

En mode de fonctionnement normal, le voyant LED ne s'allumera pas sauf dans les situations suivantes :

-   -   Lorsque le PIR est en état de batterie faible, chaque fois qu'il transmet un mouvement détecté, la LED s'allume pendant environ 2 secondes.
    -   Lorsque le couvercle est ouvert et que l'interrupteur anti-sabotage est violé, la LED s'allume pendant

2 sec. pour indiquer qu'il transmet le "**Altérer**» signale-t-il.

-   -   Lorsque la condition de sabotage persiste, chaque fois qu'il transmet un mouvement détecté, la LED s'allumera.
    -   Lorsque le PIR est en mode Test, la LED s'allume à chaque fois qu'un mouvement est détecté.
-   _**Minuterie de mise en veille**_

_**Corps principal du PIR**_

![](<.gitbook/assets/2 (17).jpeg>)

_**Quatrième de couverture**_

![](<.gitbook/assets/3 (16).jpeg>)

Le PIR a un «**Temps de sommeil**" d'environ 1 minute pour économiser l'énergie. Après avoir transmis un mouvement détecté, le PIR ne retransmettra pas pendant 1 minute ; tout mouvement supplémentaire détecté pendant cette période de sommeil prolongera la durée du sommeil d'une minute supplémentaire. De cette façon, un mouvement continu devant un PIR n’épuisera pas indûment la batterie.

-   _**Fonction de surveillance**_

Le PIR transmet un signal de supervision toutes les 30 à 50 minutes. Si le panneau de commande ne parvient pas à recevoir les signaux de supervision transmis par un certain PIR pendant une durée prédéfinie, un message «**Hors service**r” sera généré.

-   _**Fonction d'augmentation de la sensibilité**_

Vous pouvez utiliser la fonction d’augmentation de sensibilité pour augmenter la sensibilité de détection de l’IR. Pour augmenter la sensibilité de détection, veuillez régler le cavalier JP3 sur**SUR**position. Pour maintenir la sensibilité de détection normale, réglez le cavalier JP3 sur**DÉSACTIVÉ**position (par défaut d’usine).

-   _**Mode d'essai**_

1

Le PIR peut être mis en mode Test en appuyant sur le bouton Test, également appelé LED, sur le capot avant. En mode Test, il désactivera la minuterie de mise en veille et permettra à l'indicateur LED de clignoter à chaque fois qu'un mouvement est détecté. Chaque fois que vous appuyez sur le bouton Test, le PIR transmettra un signal de test au panneau de commande pour le test de portée radio et entrera en mode test pendant 3 minutes. Il quittera automatiquement le mode test après 3 minutes et reviendra en mode normal.

-   _**Batterie**_

Le PIR utilise différentes batteries selon le modèle PIR :

IRD-23 : 2 piles alcalines AA 1,5 V

IRD-23SL : 1 pile CR123A lithium 3V

Les piles sont incluses dans le colis. Le PIR dispose d'une fonction de détection de batterie faible. Un signal de batterie faible sera envoyé au panneau de commande avec des transmissions de signal régulières pour que le panneau de commande affiche l'état en conséquence.

_\\<NOTE>_

-   -   Lors du changement des piles, après avoir retiré les anciennes piles, appuyez deux fois sur l'interrupteur anti-sabotage pour les décharger complètement avant d'insérer de nouvelles piles.
-   _**Interrupteur anti-sabotage**_

Le PIR dispose d'un interrupteur anti-sabotage situé à l'arrière du corps principal du PIR. Lorsque le PIR est correctement installé sur le capot arrière, l'interrupteur anti-sabotage sera compressé. Lorsque le PIR est retiré du capot arrière, l'interrupteur d'autoprotection sera activé et déclenchera le PIR pour envoyer un signal d'autoprotection au panneau de commande.

-   _**Commencer**_
    -   Insérez la batterie dans le compartiment à batterie.
    -   Le voyant LED clignote régulièrement pendant 30 secondes. (Le PIR s'échauffe). Pendant la période de réchauffement, le PIR ne sera pas activé. Il est recommandé de rester à l'écart de la zone de détection pendant cette période. Une fois la période de réchauffement terminée, la lumière s'éteindra et le PIR sera prêt à fonctionner.
    -   Mettez le panneau de commande en mode apprentissage, reportez-vous au manuel du panneau de commande pour plus de détails.
    -   Appuyez sur le bouton d'apprentissage/test sur le capot avant.
    -   Si le panneau de commande reçoit un signal PIR, il affichera les informations en conséquence, reportez-vous au manuel du panneau de commande pour terminer le processus d'apprentissage.
    -   Une fois le PIR appris, placez le panneau de commande sur «**Test de marche**", maintenez le PIR à l'emplacement souhaité et appuyez sur le bouton Test pour confirmer que cet emplacement est à portée du signal du panneau de commande.
    -   Lorsque vous êtes convaincu que le PIR fonctionne à l'emplacement choisi, vous pouvez procéder à l'installation.
-   _**Directive d'installation**_
    -   Le PIR est conçu pour être monté au plafond
    -   Lorsqu'il est monté à 2,7 mètres de hauteur, le PIR offre une couverture de détection d'un cercle de 360° d'environ**6**diamètre en mètres.
    -   Lorsqu'il est monté à 4 mètres de hauteur, le PIR offre une couverture de détection d'un cercle de 360° avec environ**8** meter diameter.
    -   Pour des performances optimales, faites pivoter le PIR de manière à ce que l'intrus se déplace d'un côté à l'autre dans sa zone de détection.

_\\<NOTE>_

-   -   Pour connaître les « faces » du PIR. Tenez le PIR avec l’indicateur LED pointant vers le haut, et les côtés gauche et droit du PIR sont considérés comme les côtés du PIR. Le capteur PIR est plus sensible lorsque l'intrus se déplace d'un côté à l'autre
-   Reportez-vous aux schémas ci-dessous pour plus d’informations.

![](<.gitbook/assets/4 (32).png>)

-   **Il est recommandé d'installer le PIR aux emplacements suivants.**
    -   Dans une zone de plafond avec une vue complète de sa couverture de détection non obstruée par des appareils électroménagers et des meubles.
    -   Près de l'entrée d'une pièce ou d'une maison pour surveiller l'activité d'entrée.
-   **Limites**
    -   Si une porte est déjà protégée par un contact de porte, n'installez pas le PIR trop près de la porte. Si le contact de porte et le PIR sont déclenchés et transmettent un signal en même temps, les signaux peuvent entrer en collision et s'annuler.
    -   N'installez pas le PIR exposé à la lumière directe du soleil.
    -   Évitez d'installer le PIR dans des zones où les appareils peuvent provoquer un changement rapide de température dans la zone de détection, c'est-à-dire dans l'air.

2

climatiseur, radiateurs, etc.

-   -   -   -   Évitez les gros obstacles dans la zone de détection.
            -   Ne pointez pas directement vers des sources de chaleur, par ex. Feux ou chaudières, et pas au-dessus des radiateurs.
            -   Évitez de déplacer des objets dans la zone de détection, par exemple un rideau, une tenture murale, etc.
    -   After the installation site is selected, follow the steps below to mount the PIR.
    -   Appuyez sur le bouton Test pour accéder au mode Test. Parcourez la zone protégée en notant quand la LED s'allume et vérifiez que la couverture de détection est adéquate.
    -   Lorsque la couverture de détection s'avère satisfaisante, l'installation est désormais terminée.
-   _**Méthode de montage**_
    -   Le PIR est conçu pour être monté au plafond
    -   La coque arrière comporte 4 découpes où le plastique est plus fin pour un montage au plafond.
    -   Après avoir terminé l'apprentissage du PIR et le test de marche, procédez au montage du PIR conformément aux instructions ci-dessous I. Percez les 4 découpes à l'intérieur de la couverture arrière.

1.  Utilisez les houes défonçables comme gabarit, percez des trous dans le plafond et insérez une cheville murale si nécessaire.

III. Vissez le couvercle arrière au plafond en fonction des trous percés.

IV. Le couvercle arrière comporte des numéros à l'intérieur pour marquer le numéro du trou de montage, qui correspond au numéro du crochet de montage à l'arrière du corps principal. Alignez le trou de montage avec le crochet de montage lors de l'installation. Reportez-vous à la figure ci-dessous pour connaître l'emplacement du crochet de montage et du trou.

_**Vue arrière du corps principal PIR**__**Vue intérieure de la couverture arrière**_

![](<.gitbook/assets/5 (13).jpeg>)

1.  Installez le corps principal PIR sur le capot arrière. Installez les crochets du capot arrière sur les trous de montage du corps principal PIR VI. Faites pivoter le corps principal du PIR dans le sens des aiguilles d'une montre pour verrouiller les crochets dans le trou de montage. Reportez-vous à la figure ci-dessous,

VII. Le montage du PIR est maintenant terminé.

![](<.gitbook/assets/6 (16).jpeg>)

3
