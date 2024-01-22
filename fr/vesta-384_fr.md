# VESTA 384

![](<.gitbook/assets/0 (116).jpeg>)**Détecteur de fumée filaire (SD-32-BUS)**

**Introduction**

Le SD-32-BUS est un détecteur de fumée filaire conçu pour vous protéger contre les risques potentiels d'incendie. Le détecteur de fumée utilise une technologie de capteur multicritère pour détecter les flammes à combustion rapide et les incendies qui couvent lentement, tout en incluant en même temps une technologie intelligente pour différencier la fumée de cuisson des urgences réelles d'incendie de maison potentiellement mortelles, éliminant ainsi pratiquement les fausses alarmes.

Le détecteur de fumée filaire peut également être interconnecté avec d'autres détecteurs de fumée du système d'alarme et déclenche une alarme lorsqu'un détecteur de fumée du système est déclenché.

**Identification des pièces**

![](<.gitbook/assets/1 (85).png>)

**1. Indicateur LED/bouton de test**

**LED rouge**

-   Flash rapide : Alarmant.
-   Clignote toutes les secondes : détecteur de fumée en mode silence d'alarme.
-   Clignote toutes les 2 secondes : détecteur de fumée en cours de processus de préchauffage et d'étalonnage.
-   Clignote brièvement : lorsque le bouton d'apprentissage est enfoncé pour voir si l'appareil fonctionne normalement.
-   S'allume brièvement : transmission du signal.

**LED orange**

-   Clignote toutes les secondes : l’étalonnage a échoué.
-   Clignote toutes les 5 secondes : échec de détection de fumée ou dysfonctionnement de l'appareil.

**Bouton de test**

-   -   Appuyez une fois sur le bouton pour :
        -   Envoyez un signal de test.
        -   Vérifiez la chambre de détection de fumée.
        -   Faire taire l'alarme lorsque le détecteur de fumée est en alarme.
    -   Appuyez et maintenez le bouton pendant 10 secondes pour entrer dans le processus d'étalonnage.

1.  **Avertisseur sonore**
2.  **Compartiment terminal BUS**
3.  **Crochets**
4.  **Trou pré-percé pour le câblage**
5.  **Vis de fixation du couvercle du compartiment terminal BUS**
6.  **Terminal de bus**
7.  **Commutateur de cavalier de résistance de borne**

When the Smoke Detector is connected as the furthest BUS device on a BUS line, please set the Smoke Detector 's terminal resistor jumper and the first BUS device’s (usually the Hybrid Panel’s) Jumper Switch to ON to serve as terminating resistors. The connected BUS line’s communication ability will be enhanced.

![](<.gitbook/assets/2 (83).jpeg>)

-   -   -   Si le cavalier est désactivé (le lien du cavalier est retiré ou « garé » sur une broche), la capacité de communication est au niveau normal.
    -   Si le cavalier est activé, la capacité de communication sera améliorée.

1.  **Support de montage**
2.  **Trous de montage**
3.  **Feuille de montage**

![](<.gitbook/assets/3 (81).jpeg>)

1

**Caractéristiques**

![](<.gitbook/assets/4 (96).png>)

-   _**Source de courant**_
    -   Lorsque le SD-32-BUS est câblé à un panneau hybride, une alimentation de 13,5 V peut être fournie par le panneau hybride.
-   _**Test du détecteur de fumée**_

![](<.gitbook/assets/5 (98).png>)

En appuyant sur le bouton Test du détecteur de fumée, vous pouvez tester si le détecteur de fumée fonctionne normalement.

-   -   Si le détecteur de fumée fonctionne normalement, la LED rouge sera allumée pendant 2 secondes suivie d'un bip à 2 tons.
    -   Si le buzzer émet 2 bips 3 fois, le message «**Chambre optique**» sur le détecteur de fumée est sale ou en panne.
-   _**Détection de l'accumulation de poussière**_
    -   Le détecteur vérifie régulièrement l'accumulation excessive de poussière à l'intérieur de la chambre optique.
    -   Si la chambre accumule de la poussière, le détecteur signalera au panneau pour informer l'utilisateur de le nettoyer.
    -   Si la chambre n'est toujours pas nettoyée et reçoit trop de poussière et ne fonctionne plus, le détecteur signalera au panneau un avertissement de maintenance.
-   _**Surveillance**_
    -   Le détecteur de fumée filaire transmettra automatiquement le signal de supervision au panneau de commande toutes les 75 secondes.
    -   Si le panneau de commande n'a pas reçu le signal du détecteur de fumée filaire pendant une période prédéfinie, le panneau de commande indiquera que le détecteur de fumée en question rencontre un problème de manque de signal.
-   _**Activation de l'alarme**_

![](<.gitbook/assets/6 (80).png>)![](<.gitbook/assets/7 (70).png>)![](<.gitbook/assets/8 (69).png>)

Le détecteur de fumée activera l'alarme incendie lorsque la détection de fumée est déclenchée. Lorsqu'une alarme est activée, le détecteur de fumée transmet un signal d'alarme et déclenche l'alarme grâce à son buzzer intégré.

**Détection de fumée :**

-   -   Le détecteur de fumée vérifie la concentration de fumée toutes les 8 secondes
    -   L'alarme est activée chaque fois que la concentration de fumée dépasse le seuil de détection et continuera jusqu'à ce que la concentration de fumée descende en dessous du seuil d'alarme.
    -   La LED rouge clignotera rapidement pendant l'alarme.
-   _**Silence d'alarme**_
    -   Lorsque le détecteur de fumée déclenche une alarme, appuyer sur le bouton Test mettra le détecteur de fumée en mode Silence d'alarme pour faire taire l'alarme pendant 9 minutes. Le buzzer ne cessera de sonner qu'après que l'alarme ait été activée pendant au moins 1 minute. Si le bouton est enfoncé avant que l'heure de l'alarme n'atteigne 1 minute, le détecteur de fumée attendra que l'heure de l'alarme atteigne 1 minute avant de désactiver l'alarme.
    -   Pendant la période de silence d'alarme de 9 minutes, la LED rouge clignote une fois par seconde. Le détecteur de fumée continuera à surveiller la concentration de fumée pendant la période de silence de l'alarme :
    -   Après l'expiration de la période de silence de l'alarme de 9 minutes, si la concentration de fumée descend en dessous du seuil d'alarme, le détecteur de fumée émettra un bip à 2 tons et reviendra à un fonctionnement normal sans déclencher d'alarme.
    -   Si la concentration de fumée dépasse toujours le seuil d'alarme, le détecteur de fumée recommencera à émettre une alarme.
    -   Si la concentration de fumée continue d'augmenter pendant la période de silence de l'alarme et dépasse un deuxième seuil d'alarme, le détecteur de fumée recommencera à émettre une alarme. Une alarme déclenchée par le dépassement du deuxième seuil d'alarme ne pouvait pas être désactivée en appuyant sur le bouton de test.
-   _**Interconnexion**_
    -   Le détecteur de fumée est interconnecté avec d'autres détecteurs de fumée du système d'alarme. Lorsqu'un détecteur de fumée active l'alarme, le panneau de commande informera les autres détecteurs de fumée de déclencher également l'alarme même s'ils n'ont pas encore détecté de fumée. La durée de l’alarme sera conforme aux paramètres du panneau de commande.
    -   Le désarmement du système arrêtera l'alarme des autres détecteurs de fumée activés par le panneau de commande. L'alarme déclenchée par le détecteur de fumée qui détecte la fumée ne s'arrêtera que lorsque la concentration de fumée descend en dessous du seuil d'alarme.
    -   Appuyer sur le bouton Test d'un détecteur de fumée désactivera uniquement l'alarme de ce détecteur de fumée spécifique, mais ne pourra pas désactiver l'alarme de tous les détecteurs de fumée interconnectés.
-   _**Prudence**_
    -   Le câblage du détecteur de fumée ne doit être effectué que par des techniciens certifiés possédant les connaissances et la formation appropriées en matière d'équipement électrique.
    -   Avant l'installation ou tout travail de maintenance, assurez-vous que l'alimentation électrique a été débranchée.
-   _**Câblage du détecteur de fumée**_
    -   Avant de connecter le détecteur de fumée filaire au BUS du système, veuillez couper l'alimentation.
    -   Pour faciliter les connexions des câbles, les borniers de chaque module du système BUS sont codés par couleur.

![](<.gitbook/assets/9 (67).png>)![](<.gitbook/assets/10 (29).jpeg>)![](<.gitbook/assets/11 (53).png>)![](<.gitbook/assets/12 (56).png>)![](<.gitbook/assets/13 (40).jpeg>)

| **Rouge** | VDD  |
| --------- | ---- |
| **Noir**  | GND  |
| **Jaune** | 485A |
| **Vert**  | 485B |

-   Plusieurs appareils BUS peuvent être connectés en série au panneau hybride. Pour une communication optimale des dispositifs de ligne BUS connectés, assurez-vous que les cavaliers de résistance terminale du premier (généralement le panneau hybride) et des dispositifs BUS les plus éloignés sur une ligne BUS sont réglés sur ON pour servir de résistances de terminaison. Assurez-vous d'activer uniquement les 2 cavaliers susmentionnés et de ne pas régler les cavaliers sur ON pour tout autre périphérique BUS intermédiaire.

_\\<NOTE>_

2

-   -   La conception enfichable des borniers BUS améliore l'efficacité de l'installation. Avant le câblage, vous pouvez retirer les borniers de la carte PCB pour faciliter l'utilisation et les rebrancher après le câblage.
    -   Après avoir débranché le terminal, lors de la réinstallation du terminal sur la carte, assurez-vous d'installer le terminal dans la même direction pour éviter les dangers potentiels.
-   Des connexions incorrectes entraîneront une panne ou un dysfonctionnement. Inspectez le câblage et assurez-vous que les connexions sont correctes avant de mettre sous tension.

![](<.gitbook/assets/14 (47).png>)

-   _**Commencer**_

**Étape 1**Connectez le détecteur au panneau. Ensuite, allumez le panneau, le détecteur de fumée sera également allumé.

**Étape 2**Une fois le détecteur de fumée alimenté, il émettra 2 bips courts et commencera**échauffez-vous pendant 1 minute**. La LED rouge clignote toutes les 2 secondes**.**

**Étape 3.**Lorsque le détecteur de fumée termine son préchauffage, il émettra un bip pour indiquer qu'il est entré**mode d'étalonnage**. Le mode d'étalonnage dure**1 minute**(Si l'étalonnage échoue, le détecteur de fumée réessayera l'étalonnage, le mode d'étalonnage durera au maximum 9 minutes). La LED rouge continuera à clignoter toutes les deux secondes pendant l'étalonnage.

**Étape 4.**Une fois l'étalonnage terminé, le détecteur de fumée émettra 2 bips courts et éteindra la LED pour revenir en mode normal._\\<NOTE>_

![](<.gitbook/assets/15 (44).png>)

-   Si l'étalonnage échoue, le détecteur de fumée émettra un bip continu. Veuillez éteindre le détecteur de fumée, puis le rallumer pour réessayer à partir de l'étape 1.

Une fois le processus d’échauffement et d’étalonnage terminé avec succès, vous pouvez procéder à l’apprentissage.

**Étape 5.**Mettez le panneau de configuration dans**mode d'apprentissage**.

**Étape 6**Le détecteur de fumée sera détecté s'il est correctement connecté au panneau hybride.

**Étape 7.**Cliquez sur "**Ajouter**» pour inclure le détecteur de fumée détecté dans le panneau de commande.

![](<.gitbook/assets/16 (49).png>)

-   _**Identification**_

La fonction « Identifier » permet de localiser un périphérique BUS spécifique dans le système filaire BUS. Cette fonction est utile pour distinguer quel appareil est quel appareil, en particulier dans une grande installation où de nombreux appareils BUS sont inclus.

Pour localiser le détecteur de fumée filaire dans le système BUS :

**Étape 1.**Sur la page Web du panneau hybride, cliquez sur « Identifier » sous la liste des appareils après l'entrée dans la colonne des appareils du SD-32-BUS.

**Étape 2.**Si le détecteur de fumée filaire reçoit le signal du panneau hybride, la page Web affichera un message de réussite et le voyant LED rouge du détecteur de fumée filaire clignotera 10 fois pour indiquer à l'utilisateur où il se trouve.

![](<.gitbook/assets/17 (39).png>)

_\\<NOTE>_

-   -   -   Si un message de délai d'attente s'affiche sur la page Web, cela signifie que le détecteur de fumée filaire n'a pas reçu le signal du panneau. Veuillez vérifier si le SD-32-BUS est correctement connecté au panneau à une distance de câblage appropriée.
-   _**Walk Test**_
    -   Pour vous assurer que le détecteur de fumée filaire est capable de communiquer avec le panneau après son apprentissage, placez le panneau de commande en mode test de marche et appuyez sur le bouton Test du SD-32-BUS pour transmettre un signal de test au panneau de commande.
    -   Lorsque le panneau reçoit le signal de test, il émet un bip et affiche les informations du détecteur de fumée filaire en conséquence en haut de la liste des appareils.

![](<.gitbook/assets/18 (49).png>)![](<.gitbook/assets/19 (48).png>)

_\\<NOTE>_

-   -   S'il n'y a pas de réponse du panneau après avoir appuyé sur le bouton de test, cela signifie que le panneau n'a pas reçu le signal de test de l'appareil.

Please check whether the Smoke Detector is connected properly to the Panel within appropriate wiring distance.

-   _**Réétalonnage**_

![](<.gitbook/assets/20 (35).png>)

Comme les conditions de fonctionnement du détecteur de fumée peuvent varier après un certain temps d'installation, vous souhaiterez peut-être recalibrer le Smoke 3.

Détecteur pour prendre une nouvelle valeur seuil de détection de fumée et assurer des performances optimales du détecteur de fumée. Pour faire ça:

-   Appuyez et maintenez enfoncé le bouton de test pendant 20 secondes et relâchez-le lorsque le détecteur de fumée émet 3 bips. L'appareil commencera l'étalonnage et la LED rouge clignotera toutes les 2 secondes pour l'indiquer.
-   Le processus d'étalonnage dure**1 minute**(Si l'étalonnage échoue, le détecteur de fumée réessayera l'étalonnage, le mode d'étalonnage durera au maximum 9 minutes).
-   Une fois l'étalonnage terminé, le détecteur de fumée émettra un bip à deux tons. La LED rouge cessera de clignoter pour indiquer qu'elle est revenue en mode normal.
-   Si l'étalonnage échoue, le détecteur de fumée émettra un bip continu et la LED orange clignotera toutes les secondes. Veuillez éteindre le détecteur de fumée, puis le rallumer pour redémarrer le détecteur de fumée.

**Entretien et nettoyage**

Un entretien et un nettoyage réguliers aideront à maintenir votre détecteur de fumée en bon état de fonctionnement.

-   Testez le détecteur de fumée chaque semaine pour vérifier que les sons d'alarme et les indicateurs fonctionnent correctement.
-   Nettoyez le détecteur de fumée au moins une fois tous les 6 mois.
    -   Aspirez doucement la saleté/poussière/petites particules accumulées dans la chambre et les fentes de détection de fumée.
    -   Nettoyez le boîtier en le passant soigneusement avec un chiffon humide et séchez-le. Ne mettez pas d’eau à l’intérieur de l’alarme.
    -   N'utilisez jamais de produits de nettoyage, de détergents ou de solvants sur le détecteur.
-   Évitez de pulvériser un assainisseur d'air, de la laque pour cheveux ou d'autres aérosols à proximité du détecteur de fumée.
-   Ne peignez ni ne modifiez le détecteur sous aucun prétexte.

**Expiration**

Le détecteur de fumée a une durée de vie maximale de**10 années**à compter de la date d'installation. Vous devez remplacer le détecteur de fumée immédiatement après 10 ans de service.

Il est recommandé d'écrire la date « Remplacer avant » (10 ans à compter de la date d'installation) au dos du détecteur avant l'installation.

**Installation**

_**Directive d'installation**_

 Il est recommandé que le site d'installation soit dans la zone centrale du plafond.

 Ne placez pas le détecteur dans les endroits suivants :

 La cuisine – La fumée provenant de la cuisson peut provoquer une alarme indésirable.

 À proximité d'un ventilateur, d'une lampe fluorescente ou d'un équipement de climatisation – les courants d'air qui en proviennent peuvent affecter la sensibilité du détecteur.

-   Près des poutres du plafond ou au-dessus d'une armoire – l'air stagnant dans ces zones peut affecter la sensibilité du détecteur.

 Au plus fort d’un «**UN**”type de plafond à ossature.

-   _**Montage du détecteur de fumée**_

**Étape 1.**Placez le détecteur de fumée à l'emplacement de montage souhaité.

**Étape 2.**Retirez la feuille de montage incluse dans l'emballage. La taille de l’image est égale à la taille réelle du détecteur de fumée et la conception perforée permet un retrait facile après l’installation.

**Étape 3.**Positionnez la plaque contre le plafond et utilisez les quatre trous comme gabarit pour percer des trous et insérer des chevilles si nécessaire.

Assurez-vous que les chevilles murales affleurent la surface de montage.

**Étape 4.**Placez le support de montage sur la feuille de montage et vissez-le au mur.

**Étape 5.**Le détecteur de fumée possède 4 crochets sur sa façade arrière. Tenez le détecteur de fumée avec beaucoup de soin et alignez les 4 encoches du support de montage avec les 4 crochets.

**Étape 6.**Tournez dans le sens des aiguilles d'une montre pour verrouiller le crochet.

**Étape 7.**L'installation est maintenant terminée. Vous pouvez maintenant déchirer la feuille de montage.

4
