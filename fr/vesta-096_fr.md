# VESTA 096

-   Caméra à capteur de mouvement PIR
-   VST-862
-   Introduction

VST-862 est une caméra à capteur de mouvement infrarouge passif (PIR). Il est capable d'envoyer des signaux sans fil et des images capturées (qualité d'image jusqu'à 640 x 480 pixels) au panneau de commande lors de la détection de mouvement.

La caméra PIR est conçue pour offrir une portée de détection typique de 12 mètres lorsqu'elle est montée à 2 mètres au-dessus du sol. Pour les modèles immunisés contre les animaux, une portée de 7 mètres est fournie, vos animaux domestiques ne déclencheront pas de fausses alarmes à cette distance. Pour les modèles compatibles avec le répéteur RP-29/le routeur RMB-29 de Climax**(Modèles P5 uniquement)**, la portée de communication RF peut être encore étendue dans les zones difficiles d'accès.

La caméra PIR se compose d'une conception en deux parties composée d'un couvercle et d'une base. Le couvercle contient toute l'électronique et l'optique et la base fournit un moyen de fixation. La base comporte des découpes pour permettre un montage sur une surface plane ou dans un coin avec un support triangulaire pour un montage en coin.

-   La série VST-862 comprend les modèles suivants :

| **Nom du modèle** | **LED clignotante** | **LED infrarouge** | **Immunisé contre les animaux** | **Compatible avec le répéteur** |
| ----------------- | ------------------- | ------------------ | ------------------------------- | ------------------------------- |
| VST-862-(P5)      | DANS                |                    |                                 | Modèle P5 uniquement            |
| VST-862-IL-(P5)   |                     | DANS               |                                 | Modèle P5 uniquement            |
| VST-862P-(P5)     | DANS                |                    | DANS                            | Modèle P5 uniquement            |
| VST-862P-IL-(P5)  |                     | DANS               | DANS                            | Modèle P5 uniquement            |

-   ![](<.gitbook/assets/0 (15).png>)
-   Identification des pièces

1.  **LED flash / LED infrarouge**

La LED flash (pour 862(P)) ou la LED infrarouge (pour 862(P)-IL) fournit suffisamment de lumière pour la capture d'images dans des conditions de faible éclairage.

1.  **LED bleue/bouton de fonction**

**LED bleue :**

(Prière de se référer à_**Indicateur LED**_description ci-dessous pour plus de détails)

**Utilisation du bouton de fonction :**

-   Appuyez et maintenez le bouton enfoncé pendant 3 secondes pour envoyer un code d'apprentissage, relâchez lorsque la LED bleue s'allume. (Pour le panneau fonctionnant sur batterie, après avoir appuyé et maintenu le bouton pendant 3 secondes, veuillez appuyer sur le bouton**encore**pendant une seconde pour envoyer un code d'apprentissage.)
-   Appuyez une fois sur le bouton pour passer en mode test pendant 3 minutes.
-   Appuyez une fois sur le bouton pour envoyer un code d'apprentissage au répéteur/routeur. (Modèles P5 uniquement)

1.  **Capteur IR**
2.  **Objectif de caméra PIR**
3.  **Couvercle du compartiment à piles**
4.  **Interrupteur anti-sabotage**
5.  **Compartiment à piles**
6.  **Cavalier de réglage de la sensibilité (JP3)**

![jumper open](<.gitbook/assets/1 (20).png>)![jumper close](<.gitbook/assets/2 (24).png>)

**Cavalier**

si le cavalier est retiré ou "**garé**» sur une épingle.

**Cavalier**

Le cavalier est inséré pour relier les deux broches.

-   Jumper On : le niveau de sensibilité du PIR est réglé sur High.
-   Jumper Off : le niveau de sensibilité du PIR est réglé sur Normal. (**Défaut de fabrication**)

1.  **Commutateur de cavalier de minuterie de mise en veille (JP2)**

![jumper open](<.gitbook/assets/3 (23).png>)![jumper close](<.gitbook/assets/4 (21).png>)

**Cavalier**

si le cavalier est retiré ou "**garé**» sur une épingle.

**Cavalier**

Le cavalier est inséré pour relier les deux broches.

-   Cavalier activé : après la détection de mouvement, la caméra PIR n'entre pas en mode veille et transmettra à nouveau le signal de détection immédiatement si elle est déclenchée (**Défaut de fabrication**).
-   Cavalier : la caméra PIR a un "**Temps de sommeil**" d'environ 1 minute après la détection de mouvement pour économiser l'énergie.
-   Caractéristiques
-   _**Indicateur LED**_

En mode de fonctionnement normal, la LED bleue ne s'allumera pas sauf dans les situations suivantes :

-   Lorsque la caméra PIR est en état de batterie faible, chaque fois qu'elle transmet un mouvement détecté, la LED bleue clignote pendant 2 secondes.
-   Lorsque le couvercle est ouvert et que l'interrupteur anti-sabotage est violé, la LED bleue clignote pendant 2 secondes pour indiquer qu'elle transmet le signal « Tamper ».
-   Lorsque la condition de sabotage persiste, chaque fois qu'il transmet un mouvement détecté, la LED bleue clignote pendant 2 secondes.
-   Lorsque la caméra PIR entre en mode test, la LED bleue clignote pendant 1 seconde. Pendant le mode Test, la LED bleue clignote également pendant 2 secondes à chaque fois qu'un mouvement est détecté.
-   Lorsque la caméra PIR est en période de préchauffage de 30 secondes, la LED bleue clignote lentement.
-   Lorsque la caméra PIR transmet des images capturées dans des conditions de défaut (batterie faible, interrupteur anti-sabotage activé), la LED bleue clignote en continu.
-   _**Capture d'image**_

Lorsque le système d'alarme est armé, la caméra PIR capturera 1, 3 ou 6 images d'alarme en résolutions 640 x 480 ou 320 x 240 (programmable depuis le panneau de commande) lors de la détection de mouvement. Vous pouvez également demander manuellement à la caméra PIR de prendre une photo via le panneau de configuration. Les images capturées seront transférées vers le panneau de configuration pour que les utilisateurs puissent les consulter.

-   _**Période d'échauffement**_

Lorsque le système du panneau de commande passe en mode armé ou lorsque la caméra PIR est mise en mode test, la caméra PIR se réchauffe pendant 30 secondes. Pendant la période de préchauffage de 30 secondes, la caméra PIR ne sera pas activée. La LED bleue clignotera lentement pendant la période de préchauffage uniquement lorsque le PIR entre en mode test.

-   _**Minuterie de mise en veille**_

When **Cavalier 2**est réglé sur Off, la caméra PIR a un «**Temps de sommeil**" d'environ 1 minute pour économiser l'énergie. Après avoir transmis un mouvement détecté, la caméra PIR ne retransmettra pas pendant 1 minute. Tout mouvement détecté pendant cette période réinitialisera le temps de sommeil à 1 minute. Un mouvement continu devant la caméra PIR n'épuisera donc pas la batterie.

-   _Détection de batterie et de batterie faible_

La caméra PIR utilise deux**Piles alcalines « AA » de 1,5 V**en connexion en série comme source d'alimentation. Retirez le couvercle du compartiment des piles et insérez les piles pour activer la caméra PIR.

La caméra PIR dispose d'une fonction de détection de batterie faible. Lorsque la tension de la batterie est faible, la caméra PIR transmet le signal de batterie faible au panneau de commande. Si un mouvement est détecté dans des conditions de batterie faible, la LED bleue clignote pendant 2 secondes.

Lors du changement de batterie, après avoir retiré l'ancienne batterie, appuyez deux fois sur l'interrupteur anti-sabotage ou sur le bouton de fonction pour la décharger complètement avant d'insérer de nouvelles piles.

-   _**Autoprotection**_

La caméra PIR est protégée par un interrupteur anti-sabotage qui est compressé lorsque la caméra PIR est correctement installée. Lorsque la caméra PIR est retirée de la surface montée ou que son couvercle est ouvert, l'interrupteur d'autoprotection sera activé et la caméra PIR enverra un signal d'autoprotection au panneau de commande du système pour rappeler à l'utilisateur la condition. Si un mouvement est détecté lorsque l'interrupteur anti-sabotage est ouvert, la LED bleue clignote pendant 2 secondes.

-   _**Surveillance**_

La caméra PIR effectuera périodiquement un auto-test en transmettant un signal de supervision toutes les 30 à 50 minutes.

-   _**Mode d'essai**_
-   Le mode test vous permet de vérifier la plage de détection de la caméra PIR (et non la couverture de prise de vue).
-   Appuyez une fois sur le bouton Fonction pour passer en mode Test pendant 3 minutes, la LED bleue clignotera pendant 1 seconde.
-   La caméra PIR se réchauffera pendant 30 secondes. Veuillez ne pas déclencher la caméra pendant cette période d'échauffement.
-   Après la période de préchauffage, vous pouvez déclencher la caméra PIR pour vérifier la plage de détection IR. Si la caméra PIR est déclenchée, la LED bleue clignote pendant 2 secondes.

\\<Note>

-   Pour que le mode test fonctionne correctement, il est recommandé de désactiver la minuterie de mise en veille.
-   _Apprentissage_
-   Retirez le couvercle du compartiment à piles en desserrant la vis du compartiment à piles.
-   Insérez les piles. Orientez la batterie selon l'indication de polarité.
-   Mettez le panneau de commande en mode apprentissage, reportez-vous au manuel du panneau de commande pour plus de détails.
-   Appuyez et maintenez le bouton de fonction pendant 3 secondes, relâchez le bouton lorsque la LED bleue s'allume. (Pour le panneau fonctionnant sur batterie, après avoir appuyé et maintenu enfoncé le bouton de fonction pendant 3 secondes, veuillez appuyer sur le bouton de fonction**encore**pendant une seconde.)
-   La LED bleue s'allumera pendant 25 secondes en mode d'apprentissage, ajoutez la caméra PIR au panneau de commande pendant cette période (référez-vous à votre panneau de commande pour terminer l'apprentissage en cours). Si le PIR est ajouté avec succès au panneau de commande, la LED bleue clignotera 6 fois pour l'indiquer. Si le PIR n'est pas ajouté dans les 25 secondes, veuillez répéter le processus d'apprentissage.

\\<Note>

-   Si la caméra PIR existe déjà dans un système du panneau de configuration, vous devrez d'abord supprimer la caméra PIR du panneau de configuration avant de pouvoir l'enregistrer dans un autre panneau de configuration.
-   Lors de l'apprentissage de la caméra PIR dans un répéteur/routeur, veuillez appuyer une fois sur le bouton de fonction (au lieu de le maintenir enfoncé pendant 3 secondes) pour envoyer un code d'apprentissage. (Modèles P5 uniquement)
-   _Test de marche_
-   Une fois la caméra PIR apprise, placez le panneau de commande sur «**Test de marche**", maintenez la caméra PIR à l'emplacement souhaité et appuyez sur le bouton de fonction pour confirmer que cet emplacement est à portée du signal du panneau de commande, reportez-vous au manuel du panneau de commande pour effectuer le test de marche.
-   Lorsque vous êtes convaincu que la caméra PIR fonctionne à l'emplacement choisi, vous pouvez procéder au montage.
-   _**Modifier la zone de fonctionnement de la caméra PIR**_
-   Suivez les instructions ci-dessous pour modifier la zone de la caméra PIR dans le panneau de configuration.

1.  Utilisez la fonction Modifier l'appareil du panneau pour modifier les paramètres de la zone de la caméra PIR.
2.  Appuyez et maintenez enfoncé le bouton de fonction pendant 3 secondes sur la caméra PIR pour envoyer un signal au panneau, puis relâchez le bouton lorsque la LED s'allume. (Pour le panneau fonctionnant sur batterie, après avoir appuyé et maintenu enfoncé le bouton de fonction pendant 3 secondes, veuillez appuyer sur le bouton de fonction**encore**pendant une seconde pour envoyer un signal.)

-   Installation
-   _Directive d'installation_
-   La caméra PIR est conçue pour être montée sur une surface plane ou dans un coin avec les vis de fixation et les chevilles fournies.
-   La base comporte des découpes, là où le plastique est plus fin, à des fins de montage. Deux découpes sont destinées à la fixation en surface et un support de montage triangulaire est utilisé pour la fixation en coin.
-   La portée de détection peut atteindre 12 mètres si la caméra PIR est montée à 2 mètres au-dessus du sol.
-   Les modèles Pet-Immune offrent une portée typique PET IMMUNE de 7 mètres lorsqu'ils sont montés entre 1,9 et 2 mètres au-dessus du sol. Si nécessaire, vous pouvez régler la hauteur de la caméra PIR en fonction de la taille de votre animal pour une performance immunitaire optimale. Un emplacement d'installation plus élevé offrira un plus grand espace immunisé contre les animaux de compagnie, mais augmentera également l'angle mort sous la caméra PIR.
-   Lorsque le VST-862 est monté avec un support rotatif, il n'aura pas la zone de détection normale (comme dans le diagramme) ni la plage d'immunité typique aux animaux.

![](<.gitbook/assets/5 (14).png>)

**Il est recommandé d'installer la caméra PIR aux endroits suivants**

-   Montez là où les animaux ne peuvent pas accéder à la zone de détection en grimpant sur des meubles ou d'autres objets.
-   Ne dirigez pas le détecteur vers des escaliers sur lesquels les animaux peuvent monter.
-   Dans une position telle qu’un intrus se déplacerait normalement dans le champ de vision du PIR.
-   Entre 1,9 et 2 m du sol pour de meilleures performances.
-   Dans un coin pour donner la vue la plus large.
-   Où son champ de vision ne sera pas obstrué, par ex. par des rideaux, des ornements, etc.
-   **Limites**
-   N'installez pas la caméra PIR complètement exposée à la lumière directe du soleil.
-   Évitez d'installer la caméra PIR dans des zones où les appareils peuvent provoquer un changement rapide de température dans la zone de détection, c'est-à-dire un climatiseur, un chauffage, etc.
-   Évitez les gros obstacles dans la zone de détection.
-   Ne pas pointer directement vers des sources de chaleur, par ex. Feux ou chaudières, et pas au-dessus des radiateurs.
-   Évitez de déplacer des objets dans la zone de détection, par exemple un rideau, une tenture murale, etc.
-   **Assurez-vous de toujours maintenir la force du signal RSSI stable à « 4 ».**
-   ![852 r3 knockouts](<.gitbook/assets/6 (8) (1).jpeg>)_Montage de la caméra PIR_
-   Le PIR est conçu pour être monté sur une surface plane ou dans un coin avec les vis de fixation et les chevilles fournies.
-   Pour le montage en coin, un support triangulaire est fourni pour ajouter une protection anti-effraction arrière. Le support comprend également deux entrées défonçables à monter au mur.
-   Pour le montage en surface, un support rotatif en option est fourni pour permettre aux utilisateurs d'ajuster la plage de détection. Grâce au support rotatif, le VST-862 peut pivoter de 80 degrés horizontalement et de 70 degrés verticalement pour offrir une couverture optimale.
-   **Montage en coin :**

1.  ![triangular bracket](<.gitbook/assets/7 (7) (1).jpeg>)![triangular bracket](<.gitbook/assets/8 (4) (1).jpeg>)Percez les deux découpes du support triangulaire.
2.  Utilisez les deux trous comme gabarit pour percer des trous sur la surface du coin.
3.  Insérez les chevilles murales.
4.  Vissez le support triangulaire dans les chevilles murales avec les deux bâtons de pointage en haut face à vous.
5.  Fixez la caméra PIR sur les crochets du support triangulaire.

-   **Montage en saillie :**

1.  Ouvrez le couvercle en desserrant la vis du couvercle à l'aide d'un tournevis Philips.
2.  Brisez les 2 découpes de surface au centre de la base.
3.  Utilisez les trous comme gabarit pour percer des trous sur la surface.
4.  Insérez les chevilles murales si vous le fixez dans du plâtre ou de la brique.
5.  Vissez la base dans les chevilles murales.
6.  Installez le couvercle sur la base et serrez.

-   **Montage en surface avec support rotatif (article en option, vendu séparément) :**

Le support rotatif peut être monté au mur à l'aide des vis fournies.

1.  Vissez le support rotatif dans le mur.
2.  Insérez les 3 crochets du support rotatif dans les 3 trous de la base en conséquence.
3.  Faites pivoter le support pour obtenir la plage de détection appropriée et serrez la vis de fixation.

![](<.gitbook/assets/9 (7) (1).png>)
