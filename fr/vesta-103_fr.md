# VESTA 103

**Contrôle de l'obturateur (SCM-8)**

**Introduction**

SCM-8 est une commande de volet roulant qui permet un fonctionnement pratique, une montée, une descente ou un arrêt à distance des volets roulants motorisés.

La commande de volet roulant dispose de deux sorties moteur pour la commande automatique et à distance et de deux interrupteurs locaux pour la commande manuelle en option. L'utilisateur peut contrôler le SCM-8 via le panneau de commande à distance ou manuellement en activant les commutateurs locaux.

Le SCM-8 est également équipé d'une pince anti-traction et d'une boucle de câblage pour l'intégrité électrique et mécanique, les performances globales et la sécurité.

**Identification des pièces**

1.  **Bouton de test**
    -   Appuyer une fois : transmettre le signal de supervision.
    -   Signaler la position actuelle au panneau de contrôle.
    -   Appuyez et maintenez enfoncé pendant 3 secondes : envoyez un code d'apprentissage.
    -   Appuyez et maintenez le bouton tout en allumant le contrôle de l'obturateur, maintenez le bouton enfoncé pendant environ 4 secondes, puis relâchez le bouton lorsque la LED

clignote 3 fois pour réinitialiser les paramètres d'usine.

-   -   Appuyez et maintenez enfoncé pendant 10 secondes : entrez en mode d'étalonnage.

1.  **Indicateur LED**

![](<.gitbook/assets/0 (48).jpeg>)

L'indicateur LED est utilisé pour indiquer l'état du contrôle d'obturation :

-   -   -   Clignote une fois : à la mise sous tension.
        -   Clignote deux fois : lorsque l’apprentissage est réussi.
        -   Clignote 3 fois : le contrôle de l'obturateur a été réinitialisé aux paramètres d'usine.
        -   S'allume en continu : en mode apprentissage.
        -   Clignote en continu : en mode Calibrage.

1.  **Trous de montage**
2.  **Commutateur local S1 (sens ouvert)**
    -   Connectez un commutateur externe à cette borne. Activez cet interrupteur pour contrôler que le volet roule dans la direction « Ouvert » en activant la sortie moteur O1.
    -   L'activation de cet interrupteur lorsque le volet roule dans le sens « Fermer » arrêtera le volet.
3.  **Commutateur local S2 (direction de fermeture)**
    -   Connectez un commutateur externe à cette borne. Activer

cet interrupteur pour contrôler le volet pour qu'il roule vers la direction « Fermer » en activant la sortie du moteur O2

-   -   L'activation de cet interrupteur lorsque le volet roule dans le sens « Ouvert » arrêtera le volet.

1.  **Sortie moteur O1 (sens ouvert)**

Connectez-vous à la borne ouverte du moteur de volet roulant.

**7. Sortie moteur O2 (direction fermée)**

Connectez-vous à la borne de fermeture du moteur d'obturation.

1.  **Entrée d'alimentation L (fil sous tension)**
2.  **Entrée d'alimentation N (fil neutre)**
3.  **Pince anti-traction**

La pince est utilisée pour fixer les fils et fournir un soulagement de traction pour protéger les fils de la découpe métallique.

**11. Boucle de câblage**

La boucle de câblage est utilisée pour gérer les fils.

1

**spécification**

-   Alimentation : 100 - 240 VCA, 50/60 Hz
-   Courant de charge pris en charge : 1/2 HP (puissance en chevaux) ; 3,6 A pour les moteurs avec facteur de puissance compensé (charges inductives)

![](<.gitbook/assets/1 (40).jpeg>)

**Prudence**

-   Tous les travaux sur l'appareil, y compris l'installation et la maintenance, doivent être effectués par un électricien qualifié et agréé.
-   Avant l'installation ou tout travail de maintenance, assurez-vous que l'alimentation électrique a été débranchée.
-   Ne connectez pas l'appareil à des charges dépassant le courant de charge pris en charge.
-   Veuillez connecter l'appareil uniquement à un moteur alimenté en courant alternatif.

**Câblage**

-   Le SCM-8 doit être connecté selon le schéma ci-dessous :

![](<.gitbook/assets/2 (35).jpeg>)

-   -   Connectez la borne N du SCM à la borne N de l'alimentation.
    -   Connectez la borne L du SCM à la borne L de l'alimentation.
    -   Connectez la borne O1 du SCM à la borne ouverte du moteur de volet roulant.
    -   Connectez la borne O2 du SCM à la borne de fermeture du moteur d'obturation.
    -   **(Commutateur local en option)**Connectez les bornes S2 et S1 du SCM à la borne L de l'alimentation.
-   Insérez chaque fil dans la borne à laquelle il doit être connecté, serrez chaque vis pour fermer la tondeuse et maintenir les fils en place.
-   Une fois les fils connectés, utilisez la boucle de câblage pour gérer les fils et placez la boucle de câblage sur la base avec son espace (ouverture) positionné sur la gauche.

![](<.gitbook/assets/3 (32).jpeg>)

2

**Apprentissage**

Étape 1 : Connectez l’alimentation électrique au contrôle d’obturation conformément aux instructions d’installation de la section précédente et mettez le contrôle d’obturation sous tension.

Étape 2 : Mettez le panneau de configuration en mode apprentissage.

Étape 3 : Appuyez et maintenez enfoncé le bouton Test de la commande d'obturation pendant 3 secondes pour envoyer un code d'apprentissage.

Étape 4 : La LED clignote une fois, puis s'allume de manière fixe une fois le bouton relâché, indiquant que la commande d'obturation est en mode d'apprentissage.

Étape 5 : Si le panneau de commande reçoit le signal du contrôle de l'obturateur, il affichera les informations en conséquence. Reportez-vous au manuel du panneau de commande pour terminer le processus d'apprentissage.

Étape 6 : Lorsque le contrôle de l'obturateur reçoit le code d'apprentissage du panneau de commande, la LED du contrôle de l'obturateur clignote deux fois puis s'éteint pour indiquer que le processus d'apprentissage est terminé.

_\\<NOTE>_

-   Après être entré en mode d'apprentissage, si le contrôle d'obturation ne reçoit pas d'accusé de réception du panneau de commande pendant 1 minute, il quittera automatiquement le mode d'apprentissage.
-   Si le contrôle de l'obturateur existe déjà dans un système de panneau de contrôle, vous devrez d'abord supprimer le contrôle de l'obturateur du panneau de contrôle avant de pouvoir l'apprendre dans un autre panneau de contrôle.

**Test de marche**

Pour tester si le contrôle de l'obturateur est capable de communiquer avec le panneau de contrôle :

-   Mettez le panneau de commande en mode test de marche.
-   Appuyez sur le bouton Test de la commande d'obturation.
-   Le panneau de commande doit afficher si la commande d'obturation se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation du panneau de commande).

**Montage**

-   Une fois que vous avez terminé le test de marche et que vous êtes convaincu que l'appareil est capable de communiquer avec la centrale d'alarme à l'emplacement choisi, procédez au montage.
-   Débranchez l'alimentation principale.
-   Desserrez la vis de fixation inférieure et retirez le couvercle supérieur de la commande d'obturation.
-   Utilisez les trous de montage sur la base pour marquer l'emplacement de montage sur le mur.
-   Percez des trous à l'emplacement marqué et insérez des chevilles murales si nécessaire, vissez la base sur l'emplacement de montage.
-   Remettez le capot supérieur et serrez la vis de fixation inférieure.

**Surveillance**

-   Une fois la commande d'obturation correctement apprise dans le panneau de commande, l'appareil transmettra automatiquement le signal de supervision ainsi que le rapport de position actuelle au panneau de commande à des intervalles aléatoires de 30 à 50 minutes.
-   Si le panneau de commande n'a pas reçu le signal de la commande d'obturation pendant la période de temps prédéfinie, le panneau de commande indiquera sur son écran que la commande d'obturation particulière rencontre un problème de manque de signal.

**Opération**

-   _**Étalonnage**_
    -   L’heure d’activation par défaut du contrôle d’obturation est**4**minutes. Lorsque le bouton Haut/Bas est enfoncé ou que le panneau de commande envoie une demande Haut/Bas, il activera le moteur de l'obturateur pendant 4 minutes.
    -   Pour que le contrôle d'obturation fonctionne correctement, son temps d'activation doit être calibré manuellement. Calibrez le temps d’activation selon les procédures ci-dessous :
        1.  Avant l'étalonnage, les commutateurs locaux externes doivent être connectés au contrôle d'obturation.
        2.  Appuyez et maintenez le bouton Test pendant 10 secondes, puis relâchez-le pour passer en mode Calibrage (la LED clignotera deux fois). La commande d'obturation roulera vers la direction « Ouvert » pendant 4 minutes après être entrée en mode Calibrage.
        3.  Attendez 4 minutes pour que le moteur de l'obturateur arrête de rouler, puis appuyez sur le bouton « Descente » pour abaisser le volet. (Si en moins de 4 minutes le volet a déjà atteint la position ouverte, vous pouvez appuyer sur le bouton « Bas » pour arrêter le moteur du volet. Appuyez ensuite à nouveau sur le bouton « Bas » pour abaisser le volet.)

3

1.  Appuyez sur le bouton « Up » au moment où l'obturateur est complètement fermé. La commande de l'obturateur enregistrera le temps nécessaire à l'obturateur pour passer de l'ouverture à la fermeture comme le nouveau "**la période de fermeture**”.
2.  La commande de l'obturateur roulera vers l'ouverture après l'étape 4 (lorsque le bouton « Haut » est enfoncé au moment où l'obturateur est complètement fermé).
3.  Appuyez sur le bouton « Descente » au moment où l'obturateur est complètement ouvert. La commande de l'obturateur enregistrera le temps nécessaire à l'obturateur pour passer de la fermeture à l'ouverture comme le nouveau "**temps ouvert**”.
4.  Une fois l'étalonnage terminé, le contrôle d'obturation enverra un rapport de position actuelle au panneau de commande et fonctionnera avec le nouveau temps de fermeture/ouverture.

Exemple

S'il faut 30 secondes au volet pour passer de l'ouverture à la fermeture et 40 secondes pour passer de la fermeture à l'ouverture, le nouveau**la période de fermeture**sera**30**secondes et nouveau**temps ouvert**sera**40**secondes.

Après l'étalonnage, chaque fois que le contrôle d'obturation reçoit une demande de fermeture, il roulera dans la direction de fermeture pendant 30 secondes. Lorsqu'il reçoit une demande d'ouverture, il roulera vers l'ouverture pendant 40 secondes.

-   -   L'heure d'activation sera réinitialisée à**4**minutes chaque fois que le contrôle d'obturation a été réinitialisé aux paramètres d'usine.
-   _**Contrôle de l'obturateur**_

**Télécommande**

-   Une fois le contrôle de l'obturateur correctement appris dans le panneau de commande, l'utilisateur peut contrôler à distance l'ouverture, la fermeture ou l'arrêt de l'obturateur via la page Web du panneau de commande.
-   Lorsque la commande de volet reçoit une demande d'ouverture/fermeture du panneau de commande, elle roule dans la direction d'ouverture/fermeture en fonction du temps d'activation calibré pour ouvrir/fermer complètement le volet.
-   L'état de l'obturateur peut également être ajusté par pourcentage de 0 %, 10 %, 20 %... à 100 % via la page Web du Panneau de configuration.
-   Le pourcentage d'ouverture actuel est également transmis au panneau de contrôle.

![](<.gitbook/assets/4 (48).png>)

**Commutateur local**

-   Si un commutateur local en option est connecté, les utilisateurs peuvent également appuyer sur le bouton de commutation pour ouvrir/fermer le volet.
-   Appuyez et relâchez l'interrupteur pendant moins d'une seconde pour contrôler l'ouverture ou la fermeture complète de l'obturateur.
-   Appuyer sur l'interrupteur lorsque l'obturateur se déplace dans la direction opposée arrêtera l'obturateur. Appuyez à nouveau sur l'interrupteur pour ouvrir/fermer l'obturateur.

Par exemple, appuyer sur l'interrupteur vers le bas lorsque le volet s'ouvre arrêtera le volet, appuyez à nouveau sur l'interrupteur vers le bas pour commencer à fermer le volet.

**Retour aux paramètres d'usine**

-   La réinitialisation d'usine du contrôle d'obturation effacera sa mémoire et la restaurera aux paramètres d'usine par défaut.
-   Appuyez et maintenez le bouton tout en allumant le contrôle d'obturation, maintenez le bouton enfoncé pendant environ 4 secondes, puis relâchez le bouton lorsque la LED clignote 3 fois pour réinitialiser les paramètres d'usine.

4
