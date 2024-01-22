# VESTA 222

**PSS-29-F1/PSM-29-F1**

![](<.gitbook/assets/0 (92).jpeg>)

**Série de commutateurs d'alimentation**

**Introduction**

La série Power Switch est conçue pour permettre à l'utilisateur d'allumer/éteindre à distance un appareil qui y est connecté.

La série Power Switch comprend les modèles suivants :

**PSS-29-F1 :**Interrupteur

**PSM-29-F1 :**Interrupteur d'alimentation avec compteur

Le modèle PSM-29-F1 dispose d'un wattmètre intégré pour mesurer la consommation électrique. Les données énergétiques collectées seront signalées au panneau de commande.

L'intégration du Power Switch dans votre système domotique vous permettra de contrôler facilement les appareils électroménagers à des fins de confort ou d'économie d'énergie.

**Identification des pièces**

![](<.gitbook/assets/1 (78).jpeg>)

**1. Bouton de test, également appelé indicateur LED**

Le bouton de test sert également d'indicateur LED. Le bouton de test est utilisé pour contrôler l'interrupteur d'alimentation. L'indicateur LED est utilisé pour indiquer l'état de l'interrupteur d'alimentation.

**Indication LED :**

Le voyant LED s'allume dans les conditions suivantes :

-   Allumé : l'interrupteur d'alimentation est allumé.
-   Éteint : L'interrupteur d'alimentation est éteint.
-   Clignote deux fois : à la mise sous tension.
-   Clignote lentement : En mode apprentissage.
-   Clignote trois fois : lorsque l’apprentissage est réussi.
-   Clignote brièvement : transmission du signal RF

**Utilisation du bouton de test :**

-   Appuyez sur le bouton pour allumer/éteindre l'interrupteur d'alimentation
-   Appuyez et maintenez le bouton pendant 3 secondes pour envoyer un code d'apprentissage.
-   Appuyez et maintenez le bouton enfoncé tout en allumant l'interrupteur d'alimentation, puis relâchez le bouton lorsque la LED s'allume pour réinitialiser les paramètres d'usine.

**Commencer**

Étape 1 : branchez l’interrupteur d’alimentation sur la prise de courant.

Étape 2 : Mettez le panneau de configuration en mode apprentissage.

Étape 3 : Appuyez et maintenez enfoncé le bouton Test de l'interrupteur d'alimentation pendant 3 secondes pour envoyer un code d'apprentissage.

Étape 4 : La LED commencera à clignoter lentement, indiquant que l'interrupteur d'alimentation est en mode d'apprentissage.

Étape 5 : Si le panneau de commande reçoit le signal de l'alimentation

commutateur, il affichera les informations en conséquence. Reportez-vous au manuel du panneau de commande pour terminer le processus d'apprentissage.

Étape 6 : Lorsque l'interrupteur d'alimentation reçoit le code d'apprentissage du panneau de commande, la LED de l'interrupteur d'alimentation clignote 3 fois puis s'éteint pour indiquer que le processus d'apprentissage est terminé.

![](<.gitbook/assets/2 (72).png>)

_\\<NOTE>_

-   Après être entré en mode d'apprentissage, l'interrupteur d'alimentation ne quittera pas automatiquement le mode d'apprentissage à moins qu'il ne reçoive un accusé de réception du panneau de commande ou à moins que le bouton Test soit enfoncé.
-   Si l'interrupteur d'alimentation existe déjà dans un système du panneau de commande, vous devrez d'abord retirer l'interrupteur d'alimentation du panneau de commande avant de pouvoir l'apprendre dans un autre panneau de commande.

1

**Test de marche**

Pour tester si l'interrupteur d'alimentation est capable de communiquer avec le panneau de commande :

-   Mettez le panneau de commande en mode test de marche.
-   Appuyez sur le bouton Test de l'interrupteur d'alimentation.
-   Le panneau de commande doit afficher si l'interrupteur d'alimentation se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation du panneau de commande).

**Surveillance**

-   Une fois l'interrupteur d'alimentation correctement appris dans le panneau de commande, l'appareil transmettra automatiquement le signal de supervision ainsi que l'état ON/OFF au panneau de commande à des intervalles aléatoires de 30 à 50 minutes.
-   Si le panneau de commande n'a pas reçu le signal de l'interrupteur d'alimentation pendant la période de temps prédéfinie, le panneau de commande indiquera sur son écran que l'interrupteur d'alimentation concerné rencontre un problème de manque de signal.

**Opération**

![](<.gitbook/assets/3 (67).jpeg>)

-   _**Installation**_
    -   Branchez l'interrupteur d'alimentation sur une prise de courant, puis branchez l'appareil dans la prise de l'interrupteur d'alimentation. L'appareil doit être en état ON.
-   _**Contrôle des appareils**_
    -   Une fois l'interrupteur d'alimentation correctement appris dans le panneau de commande, le panneau de commande peut allumer/éteindre à distance l'interrupteur d'alimentation pour contrôler l'appareil. Veuillez vous référer au manuel de votre panneau de commande pour plus de détails.
    -   Vous pouvez également appuyer sur le bouton de l'interrupteur d'alimentation pour basculer son état marche/arrêt
    -   Si l'interrupteur d'alimentation est retiré de la prise de courant, après avoir rebranché l'interrupteur d'alimentation, son état marche/arrêt précédent et les données de production d'énergie actuelles (PSM-29-F1 uniquement) seront transmis au panneau de commande.
-   _**Moniteur de consommation d'énergie (pour PSM-29-F1 uniquement)**_

![](<.gitbook/assets/4 (58).jpeg>)![](<.gitbook/assets/5 (39).jpeg>)

Avec un wattmètre intégré pour mesurer la consommation électrique, le commutateur de wattmètre PSM-29-F1 transmettra les données de consommation d'énergie au panneau de commande lorsque :

-   -   Lorsque l'interrupteur du wattmètre est activé/désactivé.
    -   Chaque fois que la production d'énergie de l'interrupteur d'alimentation change de +/- 2 W.
    -   Chaque fois que la consommation d’énergie accumulée augmente de 0,2 kW/h.
-   _**Charge de fonctionnement maximale**_
    -   Pour 110 V : la charge de fonctionnement maximale est de 1 760 W et 16 A.
    -   Pour 230V : la charge de fonctionnement maximale est de 3680W et 16A.
    -   Si l'interrupteur d'alimentation surchauffe, il coupera automatiquement l'alimentation par mesure de sécurité. L'indicateur LED clignotera rapidement. Après la coupure, l'interrupteur d'alimentation reprendra son fonctionnement normal si la température descend en dessous du point seuil.

![](<.gitbook/assets/6 (49).jpeg>)![](<.gitbook/assets/7 (52).png>)

_\\<NOTE>_

-   La charge de fonctionnement maximale de_**Tapez B**_est de 110 V, 1 650 W et 15 A, ce qui est différent de la charge de fonctionnement maximale pour 110 V et 230 V indiquée ci-dessus.

**Retour aux paramètres d'usine**

-   La réinitialisation d'usine de l'interrupteur d'alimentation effacera sa mémoire et la restaurera aux paramètres d'usine par défaut.
-   Appuyez et maintenez enfoncé le bouton de test tout en allumant l'interrupteur d'alimentation, puis relâchez le bouton lorsque la LED s'allume pour réinitialiser les paramètres d'usine.

2
