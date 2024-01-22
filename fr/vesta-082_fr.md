# VESTA 082

**WADC-1****Contact de porte anti-errance**

WADC-1 est un contact de porte qui combine des capteurs PIR pour surveiller les ouvertures de la porte et détecter les mouvements autour d'elle. Conçu spécialement pour les personnes souffrant de démence et sujettes à l'errance, WADC-1 transmettra des signaux au panneau de commande pour avertir le soignant lorsque l'utilisateur ouvre la porte, se déplaçant de l'intérieur de la pièce vers l'extérieur.

WADC-1 dispose de deux niveaux de sensibilité réglables qui offrent en outre une commodité d'utilisation. Lorsqu'il est monté à une hauteur de 2,1~À 2,3 mètres au-dessus du sol, les capteurs PIR ont chacun une couverture de 3 x 1 mètres au niveau du sol.

![](<.gitbook/assets/0 (37).png>)

-   _**Identifier les pièces**_

**1. Indicateur LED (rouge)**

L'indicateur LED est utilisé pour indiquer l'état du capteur PIR Zone 2 (zone d'ouverture de la porte) et du contact de porte.

**2. Indicateur LED (vert)**

L'indicateur LED est utilisé pour indiquer l'état du capteur PIR Zone 1 et du contact de porte.

**3. Bouton de test**

Appuyez sur le bouton Test pour transmettre le code d'apprentissage ou passer en mode test pendant 3 minutes.

**4. Cavalier d'augmentation de sensibilité (JP3)**

![](<.gitbook/assets/1 (38).jpeg>)

**Cavalier**

![](<.gitbook/assets/2 (51).png>)

Le cavalier est inséré, reliant les deux broches.

**Cavalier**

![](<.gitbook/assets/3 (30).jpeg>)

Le lien de cavalier est supprimé ou "**garé**» sur une épingle.

-   -   Si le cavalier est sur OFF, la sensibilité de détection des PIR est au niveau normal. (**Défaut de fabrication**)
    -   Si le cavalier est sur ON, la sensibilité de détection des PIR est réglée sur élevée.

1.  **Commutateur de cavalier de réglage de capteur unique/multiple (JP4)**

![](<.gitbook/assets/4 (33).jpeg>)

**Cavalier**

![](<.gitbook/assets/5 (42).png>)

Le cavalier est inséré, reliant les deux broches.

**Cavalier**

![](<.gitbook/assets/6 (29).jpeg>)

Le lien de cavalier est supprimé ou "**garé**» sur une épingle.

-   -   Si le cavalier est désactivé, le WADC-1 sera reconnu comme 3 capteurs (capteur PIR de zone 1, capteur PIR de zone 2 et contact de porte).
    -   Si le cavalier est activé, WADC-1 sera reconnu comme 1 capteur (WADC). (**Défaut de fabrication**)

1.  **Commutateur de cavalier de sens d'ouverture de porte (JP5)**

![](<.gitbook/assets/7 (23).png>)

**Cavalier**

Le cavalier est inséré, reliant les deux broches.

Assurez-vous que JP5 est réglé sur ON pour que le réglage soit efficace.

**Cavalier**

![](<.gitbook/assets/8 (27).png>)

Le lien de cavalier est supprimé ou "**garé**» sur une épingle.

-   -   Réglez le cavalier sur OFF si la porte où l'aimant est installé est conçue pour être ouverte vers l'extérieur. (**Défaut de fabrication**)
    -   Réglez le cavalier sur ON si la porte où l'aimant est installé est conçue pour être ouverte vers l'intérieur.

1.  **Compartiment à piles**
2.  **Interrupteur anti-sabotage**

Lorsque le WADC-1 est monté en place, l'interrupteur anti-sabotage sera activé lorsque le couvercle est ouvert ou lorsque l'appareil est retiré de la surface de montage.

1

-   1.  **Aimant**
-   _**Fonction de surveillance**_
    -   -   Le capteur PIR Zone 1, le capteur PIR Zone 2 et le contact de porte transmettront leur signal de supervision séparément au panneau de commande toutes les 30 à 50 minutes.
        -   Si la centrale ne parvient pas à recevoir les signaux de supervision transmis par un certain appareil pendant une durée prédéfinie, un message d'erreur « Hors service » sera généré.
-   _**Fonction d'augmentation de la sensibilité (JP3)**_

![](<.gitbook/assets/9 (13).jpeg>)![](<.gitbook/assets/10 (14).jpeg>)

Vous pouvez utiliser la fonction d’augmentation de sensibilité pour augmenter la sensibilité de détection des capteurs PIR. Pour augmenter la sensibilité de détection, connectez le cavalier (JP3) à régler sur le**SUR**position. Pour maintenir une sensibilité de détection normale, débranchez le cavalier (JP3) pour le régler sur**DÉSACTIVÉ**position (par défaut d’usine).

![](<.gitbook/assets/11 (17).jpeg>)

-   _**Fonction de réglage de capteurs simples/multiples (JP4)**_

Vous pouvez utiliser le cavalier (JP4) pour décider de reconnaître l'appareil comme un seul capteur ou plusieurs capteurs une fois l'appareil appris dans le panneau de commande. Si le cavalier (JP4) est réglé sur ON, WADC-1 sera reconnu comme 1 capteur. Chaque fois qu'un mouvement est détecté, la LED clignote. Si le cavalier est réglé sur OFF, le WADC-1 sera reconnu comme 3 capteurs distincts (capteur PIR de zone 1, capteur PIR de zone 2 et contact de porte).

![](<.gitbook/assets/12 (23).png>)

_\\<NOTE>_

-   -   Chaque fois avant de modifier le réglage du JP4, assurez-vous d'abord de retirer la batterie. Appuyez plusieurs fois sur le bouton de test, modifiez le réglage du cavalier souhaité et réinsérez la batterie. Les modifications entreront en vigueur une fois que l’appareil sera alimenté par la batterie.
-   _**Détection du sens d'ouverture de la porte (JP5)**_

![](<.gitbook/assets/13 (16).jpeg>)

Vous pouvez utiliser le cavalier pour définir le sens d'ouverture de votre porte. Pour que le réglage soit efficace, assurez-vous d'abord de régler JP4 sur ON. Si la porte où l'aimant est installé est conçue pour être ouverte vers l'extérieur, réglez le cavalier (JP5) sur OFF.

Si la porte est conçue pour être ouverte vers l'intérieur, réglez le cavalier (JP5) sur ON.

![](<.gitbook/assets/14 (17).jpeg>)

-   _**Mode d'essai**_
    -   En mode normal, appuyer sur le bouton Test transmettra un signal de test au panneau de commande pour le test de portée radio, et WADC-1 entrera en mode test pendant 3 minutes. Il quittera automatiquement le mode test après 3 minutes et reviendra en mode normal.
    -   En mode Test, l'indicateur LED vert ou rouge clignote chaque fois qu'un mouvement est détecté dans la zone PIR 1 ou la zone PIR 2 (zone d'ouverture de porte) ; la LED bleue et la LED rouge clignoteront lorsque le contact de porte est activé.
    -   Vous pouvez vérifier la plage de détection des capteurs PIR Zone 1 et Zone 2 en déclenchant les capteurs.
-   _**Indicateur LED**_

![](<.gitbook/assets/15 (14).jpeg>)

En mode de fonctionnement normal, les indicateurs LED clignotent dans les situations suivantes :

-   -   Lorsqu'un mouvement est détecté dans la zone PIR 1 ou la zone PIR 2 (zone d'ouverture de porte) dans des conditions de défaut (batterie faible, auto-surveillance) ou en mode test, la LED verte ou la LED rouge clignote.
    -   Lorsque le contact de porte est activé dans des conditions de défaut (batterie faible, auto-ouverture) ou en mode test, la LED verte et la LED rouge clignotent.
    -   Lorsque le couvercle est ouvert et que l'interrupteur anti-sabotage est déclenché, la LED verte et la LED rouge clignotent.
    -   Lorsque le bouton de test est enfoncé dans des conditions de défaut (pile faible, auto-surveillance), la LED verte et la LED rouge clignotent.
    -   Lorsque la batterie est épuisée, le WADC-1 arrêtera toutes les fonctions, la LED verte et la LED rouge clignoteront toutes les 4 secondes.
-   _**Batterie**_
    -   WADC-1 utilise une pile au lithium 3V CR123 comme source d'alimentation :
    -   WADC-1 dispose d'une fonction de détection de batterie faible. Si une faible tension de batterie est détectée, un signal de batterie faible sera envoyé au panneau de commande avec des transmissions de signal régulières pour que le panneau de commande affiche l'état en conséquence.
    -   Lors du changement de batterie, après avoir retiré l'ancienne batterie, appuyez deux fois sur l'interrupteur anti-sabotage pour la décharger complètement avant d'insérer une nouvelle batterie.
-   _**Commencer**_
    -   Retirez l'isolant de la batterie pour activer la batterie.
    -   Mettez le panneau de commande en mode apprentissage, reportez-vous au manuel du panneau de commande pour plus de détails.
    -   Appuyez sur le bouton de test sur le côté pour envoyer un code d'apprentissage au panneau de commande.
    -   Lorsque JP4 est réglé sur ON, WADC-1 sera reconnu comme**1 capteur**(WADC) et occupe 1 zone dans le panneau de commande après son apprentissage dans le panneau de commande.
    -   Lorsque JP4 est réglé sur OFF, WADC-1 sera reconnu comme**3 capteurs séparés**(capteur PIR Zone 1, capteur PIR Zone 2 et contact de porte) et occupez**3 zones**dans le panneau de configuration après son apprentissage dans le panneau de configuration.
    -   Reportez-vous au manuel du panneau de commande pour terminer le processus d'apprentissage.
-   _**Test de marche**_
    -   Une fois WADC-1 appris, placez le panneau de commande sur «**Test de marche**", maintenez WADC-1 à l'emplacement souhaité et appuyez sur le bouton Test pour confirmer si cet emplacement est à portée du signal du panneau de commande, reportez-vous à Contrôle

![](<.gitbook/assets/16 (12).jpeg>)![](<.gitbook/assets/17 (11).jpeg>)![](<.gitbook/assets/18 (9).jpeg>)

2

Manuel du panneau pour effectuer le test de marche.

-   -   Lorsque vous êtes convaincu que WADC-1 fonctionne à l'emplacement choisi, vous pouvez procéder au montage.
-   _**Directive d'installation**_
    -   WADC-1 doit être installé sur le cadre de la porte juste au-dessus de la porte pour regarder vers le bas et surveiller les mouvements autour de la porte.
    -   L'aimant doit être installé sur la porte du côté opposé à l'emplacement de l'interrupteur magnétique interne du contact de porte.
    -   Le WADC-1 comporte 2 marques de nervures sur un côté (voir la figure), marquant l'emplacement de l'interrupteur magnétique interne. L'aimant doit s'aligner avec le côté marqué des nervures du WADC-1, comme indiqué dans la figure ci-dessous.

![](<.gitbook/assets/19 (6).jpeg>)![](<.gitbook/assets/20 (8).jpeg>)

-   Si la porte sur laquelle l'aimant est installé est conçue pour être ouverte vers l'extérieur, veuillez régler**JP5 sur OFF**(**Assurez-vous que JP4 est réglé sur ON pour que le réglage soit efficace.**). La distance entre le WADC-1 et l'aimant ne doit pas dépasser 5 mm lorsque la porte est fermée.
-   Si la porte sur laquelle l'aimant est installé est conçue pour être ouverte vers l'intérieur, veuillez régler**JP5 à ON**(**Assurez-vous que JP4 est réglé sur ON pour que le réglage soit efficace.**). La distance entre le WADC-1 et l'aimant ne doit pas dépasser 5 mm lorsque la porte est fermée.

3

1.  La surface de montage doit être propre, sèche et lisse. Nettoyez la surface de montage avec un dégraissant approprié si

nécessaire.

1.  Retirez la doublure d'un côté du ruban adhésif double face. Appliquez le ruban adhésif au dos de l'appareil et appuyez fermement pendant 30 secondes pour garantir une bonne adhérence.
    1.  Retirez l'autre doublure et appuyez fermement sur le contact de porte à l'emplacement souhaité pendant 30 secondes.

_\\<NOTE>_

-   -   -   N'utilisez pas l'installation du ruban adhésif sur une surface avec de la peinture écaillée ou craquelée, ou sur une surface rugueuse.
        -   Veuillez ne pas réappliquer le ruban adhésif 3M. Il ne peut pas être réutilisé
-   **Montage à vis**

La base comporte deux découpes, là où le plastique est plus fin, à des fins de montage. (voir figure de droite)

Pour monter le contact de porte :

-   1.  Retirez le couvercle en dévissant la vis de fixation du couvercle à l'aide d'un tournevis Philips.

1.  Brisez les trous sur la base.
2.  En utilisant les trous comme gabarit, percez les deux trous.

IV. Insérez des chevilles murales si vous fixez dans du plâtre ou de la brique.

1.  Vissez la base dans la prise murale à l'aide d'un tournevis Philips.

VI. Fixez le couvercle à la base et serrez la vis de fixation du couvercle.

-   -   Fixez l'aimant sur la porte à l'aide du petit morceau de ruban adhésif double face. L'aimant doit s'aligner avec le côté marqué des nervures du contact de porte. L'installation est maintenant terminée.
-   _**Recommandations d'installation**_
    -   WADC-1 doit être installé sur la partie du cadre de porte qui se trouve juste au-dessus de la porte pour regarder vers le bas et surveiller les mouvements.
    -   Lorsqu'il est monté à une hauteur de 2,1~2,3 mètres et face vers le bas, les capteurs PIR (PIR Zone 1 et Zone 2) ont chacun une couverture de 3 x 1 mètres au niveau du sol.

4
