# VESTA 154

**Capteur de mouvement de rideau extérieur EIRC-1-F1**

EIRC-1-F1 est un capteur de mouvement pour rideau extérieur équipé de la technologie de détection de mouvement PIR et micro-ondes. La combinaison de deux méthodes de détection améliore considérablement la précision de détection du capteur de mouvement et réduit le taux de fausses alarmes, en utilisant le PIR comme détection initiale et le micro-ondes comme confirmation avant de transmettre réellement le signal d'activation.

Le capteur de mouvement dispose également d'une fonction anti-masquage. Il est capable de détecter toute tentative d'aveuglement du capteur en plaçant des objets dans son champ de vision.

En utilisant la plaque de montage en forme de L, l'utilisateur peut choisir entre un montage plat ou un montage latéral lors de l'installation du capteur de mouvement sur le mur. Cette conception permet au capteur de mouvement de détecter les mouvements suspects au niveau de la porte d'entrée ou de détecter les intrus qui grimpent et franchissent les clôtures ou les murs.

_**Identification des pièces**_

**Devant\*\*\*\*Interne**

![](<.gitbook/assets/0 (46).png>)

\*\*1.\*\***Détecteur de proximité numérique**

Le détecteur permet de détecter toute tentative de masquage (blocage) d'un intrus.

1. **Lentille du capteur**
2. **LED de l'émetteur (rouge)**

La LED s'allume brièvement lorsque :

* Le bouton Apprendre/Test est enfoncé.
* L'interrupteur anti-sabotage est déclenché ou restauré.
* Un mouvement est détecté en mode test
* Un mouvement est détecté dans des conditions de batterie faible ou d'autoprotection pendant le fonctionnement normal.

Lorsque la batterie du capteur de mouvement est épuisée, la LED clignote toutes les 4 secondes.

**4. LED de détection de micro-ondes (bleue)**

La LED s'allume brièvement lorsque la détection micro-ondes est déclenchée en mode test ou en mode test micro-ondes.

**5. LED de détection IR (verte)**

La LED s'allume brièvement lorsque la détection IR est déclenchée en mode test.

1. **Interrupteur anti-sabotage**
2. **Commutateur de cavalier d'augmentation de sensibilité (JP3)**
   *
     * Si le cavalier est**DÉSACTIVÉ**(si le cavalier est retiré ou « garé » sur une broche), la sensibilité de détection du capteur de mouvement est au niveau normal.**(Défaut de fabrication)**
     * Si le cavalier est**SUR**, la sensibilité de détection du capteur de mouvement est élevée.
3. **Test micro-ondes activer/désactiver le cavalier (JP2)**
   * Lorsque le cavalier est réglé sur**SUR**, le capteur de mouvement est en mode test micro-ondes (veuillez consulter**Mode test micro-ondes**)
   * Lorsque le cavalier est réglé sur**DÉSACTIVÉ**, le mode test micro-ondes est désactivé.**(Défaut de fabrication)**

![](<.gitbook/assets/1 (49).jpeg>) ![](<.gitbook/assets/2 (46).jpeg>) ![](<.gitbook/assets/3 (56).png>)

1

![](<.gitbook/assets/4 (41).jpeg>)

1. **Commutateur de gamme de micro-ondes**

L'échelle de plage est affichée à droite avec la flèche pointant vers le niveau de sensibilité actuel :

*
  * En tournant dans le**Dans le sens des aiguilles d'une montre**augmente la portée de détection.
  * En tournant dans le**Direction dans le sens inverse des aiguilles d'une montre**diminue la portée de détection.**Défaut de fabrication**: est réglé sur moyen.

1. **Bouton Apprendre/Test**
2. **Compartiment à piles**
3. **L-Type Mounting Plate**
4. **Mounting Holes**
5. **Bouclier de protection**

L'écran de protection protège le détecteur de proximité numérique de la pluie.

_**Caractéristiques**_

* _**Détection de mouvement**_
  * The Motion Sensor has built-in PIR sensor and Microwave Transmitter. Motion Detection is performed by PIR Sensor during normal operation. When PIR Sensor detects movement, the Microwave Transmitter will be activated to verify the movement detection. If both PIR and Microwave confirms movement detection, the Motion Sensor will transmit detection signal.
  * Le signal de détection ne sera transmis que lorsque le PIR et le micro-ondes détectent un mouvement.
  * Ajustez le réglage du commutateur de plage micro-ondes pour régler l'émetteur micro-ondes et la plage de détection globale.
  * Lorsque le commutateur de portée des micro-ondes est réglé sur Maximum, le capteur de mouvement a une portée approximative de 11 mètres lorsqu'il est monté à 1,4\~1,6 m de hauteur.
  * Lorsque le commutateur de portée des micro-ondes est réglé sur Moyen, le capteur de mouvement a une portée approximative de 8,5 mètres lorsqu'il est monté à 1,4\~1,6 m de hauteur.
  * Lorsque le commutateur de portée des micro-ondes est réglé sur Minimum, le capteur de mouvement a une portée approximative de 4,5 mètres lorsqu'il est monté à 1,4\~1,6 m de hauteur.
* _**Minuterie de mise en veille**_

Le capteur de mouvement dispose d'un « temps de veille » automatique d'environ**1 minute**pour la conservation de l'énergie. Après avoir transmis un mouvement détecté, l'EIR ne retransmettra pas pendant une minute. Tout autre mouvement détecté au cours de cette période de sommeil d’une minute prolongera la durée du sommeil d’une minute supplémentaire. De cette façon, un mouvement continu devant l’EIR n’épuisera pas indûment la batterie.

* _**Mode d'essai**_

Le capteur de mouvement peut être mis en mode Test en appuyant sur le bouton Apprendre/Test. Le mode test dure 10 minutes et sera réinitialisé à 10 minutes en appuyant sur le bouton Apprendre/Test. En mode test, la minuterie de mise en veille est désactivée et les LED s'allument lorsqu'un mouvement est détecté. Utilisez le mode Test pour déterminer la couverture de détection du capteur de mouvement lors de l'installation du capteur.

* _**Mode test micro-ondes**_

Le mode test micro-ondes est uniquement destiné au test de la plage micro-ondes. Utilisez le cavalier JP2 pour activer le mode de test micro-ondes. Lorsque le capteur de mouvement est en mode test micro-ondes, la détection PIR est désactivée, l'émetteur micro-ondes sera activé pour envoyer à plusieurs reprises un signal micro-ondes pour la détection de mouvement. Lorsque le capteur de mouvement détecte un mouvement en mode test de micro-ondes, la LED bleue du micro-ondes s'allume brièvement pour l'indiquer.

Utilisez le mode test de micro-ondes pour déterminer la plage des micro-ondes et ajustez la plage avec le commutateur de plage des micro-ondes si nécessaire. Assurez-vous de désactiver le mode de test micro-ondes une fois le test terminé en réglant le cavalier JP2 sur OFF et en remettant le capteur de mouvement en fonctionnement normal.

* _**Batterie**_
  * Le capteur de mouvement utilise deux piles au lithium AA L91 comme source d'alimentation.
  * Le capteur de mouvement dispose d'une détection de batterie faible. Lorsqu'une faible tension de batterie est détectée, un signal de batterie faible sera envoyé au panneau de commande avec des transmissions de signal régulières.
  * Si la batterie n'est pas changée après la détection d'une batterie faible et que la batterie est complètement épuisée, le capteur de mouvement arrêtera tout fonctionnement. La LED rouge clignotera toutes les 4 secondes pour l'indiquer.
  * Lorsque vous changez les piles, après avoir retiré les anciennes piles, appuyez plusieurs fois sur l'interrupteur anti-sabotage ou sur Learn/Test pour les décharger complètement avant d'insérer de nouvelles piles.
* _**Surveillance**_
  * Après l'installation, le capteur de mouvement transmettra un signal de supervision au panneau de commande toutes les 30 à 50 minutes
  * Si le panneau de commande ne parvient pas à recevoir les signaux de surveillance du capteur de mouvement pendant une période de temps prédéfinie, le panneau de commande indiquera sur son écran que le capteur en question est en panne.
* _**Interrupteur anti-sabotage**_

L'interrupteur anti-sabotage du capteur de mouvement est en position normale (autoprotection fermée) lorsque le ressort est comprimé contre l'intérieur du capot arrière de l'appareil. Une violation d'autoprotection se produit lorsque le capot avant est retiré de la base et que l'interrupteur d'autoprotection est relâché.

2

* _**Détection de proximité**_
  * Le détecteur de mouvement dispose d'un détecteur de proximité numérique capable de détecter toute tentative de masquage (blocage) d'un intrus.
  * Lorsqu'un événement de masquage est détecté et que la condition de masquage dure 2 minutes, l'EIRC-1-F1 enverra un signal d'autoprotection au panneau de commande pour informer l'utilisateur de la condition.
  * Une fois le masquage/blocage supprimé pendant 2 minutes, EIRC-1-F1 enverra un signal de restauration anti-sabotage au panneau de commande.

_\\_

* Tout mouvement de déclenchement IR effacera l’événement/condition de masquage actuellement détecté. Un nouvel événement de masquage doit être détecté et durer 2 minutes pour que le rapport d'auto-ouverture soit transmis.

_**Apprentissage et installation**_

* _**Commencer**_
  1. Retirez le capot avant de la base en desserrant la vis de fixation inférieure.
  2. Orientez et insérez les piles selon la polarité.
  3. La LED rouge de l'émetteur commencera à clignoter pendant 30 secondes pour indiquer que le capteur de mouvement se réchauffe. Pendant la période de préchauffage, le capteur de mouvement ne sera pas activé. Il est recommandé de rester à l'écart de la zone de détection pendant cette période. Après la période de préchauffage, la LED rouge s'éteindra et le capteur de mouvement entrera en fonctionnement normal.
  4. Mettez le panneau de configuration en mode apprentissage ; reportez-vous au manuel du panneau de commande pour plus de détails.
  5. Appuyez sur le bouton Learn/Test pour transmettre le signal au panneau.
  6. Si le panneau reçoit un signal du capteur de mouvement, il affichera les informations du capteur en conséquence. Reportez-vous à votre panneau de configuration pour terminer le processus d'apprentissage.
  7. Une fois le capteur de mouvement appris, mettez le panneau de commande en mode « Test de marche », maintenez le capteur à l'emplacement souhaité et appuyez sur le commutateur de test pour confirmer que cet emplacement est à portée du signal du panneau de commande.
  8. Lorsque vous êtes satisfait de l'emplacement choisi, vous pouvez procéder à l'installation.

_\\_

*
  *
    * **Test de marche**doit être effectuée pour confirmer le bon fonctionnement et la couverture du capteur de mouvement.
    * Lors de l'apprentissage du capteur de mouvement ou de la réalisation d'un test de marche, évitez d'obstruer le détecteur anti-masquage avec votre main, sinon le signal d'ouverture sera transmis au panneau de commande si la condition de masquage dure 2 minutes.
* _**Méthode de montage**_
  * L'EIRC-1-F1 est conçu pour être monté au mur. Selon la façon dont vous utilisez la plaque de montage en forme de L, le détecteur de mouvement peut être monté à plat ou sur le côté lorsqu'il est installé au mur.

**Montage à plat**

1. Détachez l’ensemble base et couvercle EIRC-1-F1.
2. Utilisez les trous de montage sur le côté le plus long de la plaque de montage en forme de L comme gabarit pour percer des trous dans le mur pour les fiches. Fixez le côté le plus long de la plaque de montage au mur avec les vis fournies.**(Image 1)**
3. Fixez le capot arrière de l'EIRC-1-F1 à la plaque de montage avec les deux vis fournies.**(Photo 2)**

IV. Installez le capot avant sur le capot arrière et serrez la vis de fixation inférieure.**(Photo 2)**

1. Insérez l'écran de protection. (Veuillez retirer le film protecteur des deux côtés de l'écran de protection avant de l'insérer.)

**(Photo 3)**

![](<.gitbook/assets/5 (25).jpeg>)

3

**Montage latéral**

1. Détachez l’ensemble base et couvercle EIRC-1-F1.
2. Utilisez les trous de montage sur le côté étroit de la plaque de montage en forme de L comme gabarit pour percer des trous dans le mur pour les fiches. Fixez le côté étroit de la plaque de montage au mur avec les vis fournies.**(Image 1)**
3. Fixez le capot arrière de l'EIRC-1-F1 à la plaque de montage avec les deux vis fournies.**(Photo 2)**

IV. Installez le couvercle sur le couvercle arrière et serrez la vis de fixation inférieure.**(Photo 2)**

1. Insérez l'écran de protection.**(Photo 3)**(Veuillez retirer le film protecteur des deux côtés de l'écran de protection avant de l'insérer.)

![](<.gitbook/assets/6 (35).jpeg>)

_\\_

* Il y a trois écrous sur la plaque de montage, offrant deux niveaux de montage (haut/bas) pour la sélection. Une fois la plaque de montage fixée au mur, vous pouvez choisir de monter l'EIRC-1-F1 au niveau inférieur ou au niveau supérieur avec les deux vis fournies.

![](<.gitbook/assets/7 (34).jpeg>)

4

_\\_

*
  * Une fois l'EIRC-1-F1 monté, si le panneau de commande affiche l'état de défaut de sabotage de l'appareil, veuillez vous assurer que le détecteur anti-masquage n'est obstrué par aucun objet et attendez deux minutes pour voir si l'état de sabotage ouvert est effacé. . Si l'état d'autoprotection persiste après deux minutes, veuillez retirer le capteur de mouvement de l'emplacement de montage et vérifier si l'interrupteur d'autoprotection est correctement comprimé contre l'intérieur du capot arrière de l'appareil.
* _**Recommandations d'installation**_

Le capteur de mouvement doit être monté à 1,4 m\~1,6 m pour des performances optimales. Il a une portée maximale de 11 mètres lorsque le capteur micro-ondes est réglé sur la portée maximale et monté à 1,6 mètre de hauteur.

_\\_

*
  * Veuillez noter que les performances sont affectées par des facteurs externes, tels que la hauteur de l'objet détecté, la plage de détection souhaitée, la zone d'installation, etc. La hauteur de montage suggérée peut être ajustée en fonction des facteurs réels de l'environnement d'installation.
* **Il est recommandé d'installer le capteur de mouvement aux endroits suivants**
  * Montez dans une position telle qu’un intrus se déplacerait normalement dans le champ de vision du capteur.
  * Montez là où son champ de vision ne sera pas obstrué, par ex. par des rideaux, des ornements, etc.
* **Limites**
  * Ne positionnez pas un capteur de mouvement pour regarder directement une porte protégée par un contact de porte, cela pourrait provoquer la transmission des signaux radio du contact de porte et du capteur de mouvement au même instant lors de l'entrée, provoquant une collision de signaux.
  * N'installez pas le détecteur de mouvement complètement exposé à la lumière directe du soleil.
  * Évitez d'installer le capteur de mouvement dans des zones où les appareils peuvent provoquer un changement rapide de température dans la zone de détection, c'est-à-dire un climatiseur, des radiateurs, etc.
  * Évitez les gros obstacles dans la zone de détection.
  * Ne dirigez pas le capteur directement vers des sources de chaleur, par ex. feux ou chaudières, et pas au-dessus des radiateurs.
  * Évitez de déplacer des objets dans la zone de détection, par exemple un rideau, une tenture murale, etc.

![](<.gitbook/assets/8 (27).jpeg>)

5

![](<.gitbook/assets/9 (18).jpeg>)

6
