---
icon: circle-chevron-right
---

# VESTA-007

**VST-862**

PIRCAM intérieur

**Introduction**

VST-862 est détecteur de mouvement infrarouge passif (PIR) avec caméra. Il est capable d'envoyer des signaux RF et des images (qualité d'image jusqu'à 640 x 480 pixels) à la centrale suite à la détection d'un mouvement.\
Le PIRCAM est conçu pour offrir une portée de détection de 12 mètres lorsqu'il est installé à 2 mètres de haut. Pour les modèles avec immunité animaux,  la portée de l'immunité est de 7 mètres pour 27kg, vos animaux domestiques ne déclencheront pas de fausses alarmes dans les limites énoncées. Pour les modèles compatibles avec le répéteur RP-29/routeur RMB-29 de Climax (**Modèles P5 uniquement**), la portée de communication RF peut être encore étendue pour les zones difficiles à atteindre.\
Le PIRCAM est composé de deux éléments, le couvercle et la base. Le couvercle contient toute l'électronique et l'optique et la base fournie un moyen de fixation. La base comporte des découpes pour permettre un montage sur une surface plane ou dans un angle avec un support triangulaire.

**La série VST-862 comprend les modèles suivants :**

| **Nom du modèle** | **LED clignotante** | **LED IR** | **Immunité animaux** | **Compatibilité répéteur** |
| ----------------- | ------------------- | ---------- | -------------------- | -------------------------- |
| VST-862-(P5)      | OUI                 |            |                      | Modèle P5 uniquement       |
| VST-862-IL-(P5)   |                     | OUI        |                      | Modèle P5 uniquement       |
| VST-862P-(P5)     | OUI                 |            | OUI                  | Modèle P5 uniquement       |
| VST-862P-IL-(P5)  |                     | OUI        | OUI                  | Modèle P5 uniquement       |

* **Identification**

![852Pro R8\_20160629](<.gitbook/assets/0 (8).jpeg>)

1. **LED clignotante / LED IR**\
   La LED clignotante (pour 862(P)) ou la LED IR (pour 862(P)-IL) fournie suffisamment de lumière pour la capture d'images dans des conditions de faible éclairage.
2. **LED bleue/bouton de fonction**\
   **LED bleue:**\
   (Prière de se référer à **Voyant LED** dans la description ci-dessous pour plus de détails)\
   **Utilisation du bouton de fonction :**\
   **-** Maintenez le bouton appuyé pendant 3 secondes pour envoyer un code d'apprentissage, relâchez lorsque la LED bleue s'allume (pour les centrales autonomes, après avoir appuyé et maintenu le bouton pendant 3 secondes, veuillez appuyer sur le bouton **de nouveau** pendant une seconde pour envoyer le code d'apprentissage).\
   \- Appuyez une fois sur le bouton pour passer en mode test pendant 3 minutes.\
   \- Appuyez une fois sur le bouton pour envoyer un code d'apprentissage au répéteur/routeur (Modèles P5 uniquement).
3. **Capteur IR**
4. **Objectif de caméra PIR**
5. **Couvercle du compartiment à batteries**
6. **Autoprotection**
7. **Compartiment à batterie**
8. **Cavalier de réglage de la sensibilité (JP3)**\
   Le cavalier est inséré pour relier les deux broches.\
   \- Cavalier On : le niveau de sensibilité du PIR est réglé sur Haut.\
   \- Cavalier Off : le niveau de sensibilité du PIR est réglé sur Normal (**par défaut**).
9. **Cavalier de mise en veille (JP2)**\
   Le cavalier est inséré pour relier les deux broches.\
   \- Cavalier On : après la détection de mouvement, la caméra PIR n'entre pas en mode veille et transmettra à nouveau le signal de détection immédiatement si elle est déclenchée (**par défaut**).\
   \- Cavalier Off : la caméra PIR a une "**mise en veille**" d'environ 1 minute après la détection de mouvement pour économiser l'énergie.

**Caractéristiques**

* _**Voyant LED**_\
  En fonctionnement normal, la LED bleue ne s'allumera pas sauf dans les situations suivantes :\
  \- Lorsque le PIRCAM est en état de batterie faible, chaque fois qu'il transmet un mouvement détecté, la LED bleue clignote pendant 2 secondes.\
  \- Lorsque le couvercle est ouvert et que l'autoprotection est déclenchée, la LED bleue clignote pendant 2 secondes pour indiquer qu'il transmet le signal "Autoprotection".\
  \- Lorsque la condition de sabotage persiste, chaque fois qu'il transmet un mouvement détecté, la LED bleue clignote pendant 2 secondes.\
  \- Lorsque le PIRCAM entre en mode test, la LED bleue clignote pendant 1 seconde. Pendant le mode Test, la LED bleue clignote également pendant 2 secondes à chaque fois qu'un mouvement est détecté.\
  \- Lorsque le PIRCAM est en période de démarrage de 30 secondes, la LED bleue clignote lentement.\
  \- Lorsque le PIRCAM transmet des images capturées dans des conditions de défaut (batterie faible, autoprotection), la LED bleue clignote en continu.
* _**Capture d'image**_\
  Lorsque le système d'alarme est armé, le PIRCAM capturera 1, 3 ou 6 images d'alarme en résolutions 640 x 480 ou 320 x 240 (programmable depuis la centrale) lors de la détection de mouvement. Vous pouvez également demander manuellement au PIRCAM de prendre une photo via la centrale. Les images capturées seront transférées vers la centrale pour que les utilisateurs puissent les consulter.
* _**Période de démarrage**_\
  Lorsque la centrale est armée ou lorsque le PIRCAM est mis en mode test, un période de démarrage de 30 secondes démarre. Pendant cette période, le PIRCAM ne sera pas actif. La LED bleue clignotera lentement pendant la période de démarrage uniquement lorsque le PIRCAM entre en mode test.
* _**Mise en veille**_\
  Quand**Cavalier 2**est réglé sur Off, la caméra PIR a un «**Temps de sommeil**" d'environ 1 minute pour économiser l'énergie. Après avoir transmis un mouvement détecté, la caméra PIR ne retransmettra pas pendant 1 minute. Tout mouvement détecté pendant cette période réinitialisera le temps de sommeil à 1 minute. Un mouvement continu devant la caméra PIR n'épuisera donc pas la batterie.
* _Détection de batterie et de batterie faible_

La caméra PIR utilise trois**Piles au lithium CR123A 3V**comme source d'énergie. Retirez le couvercle du compartiment des piles et insérez les piles pour activer la caméra PIR.

La caméra PIR dispose d'une fonction de détection de batterie faible. Lorsque la tension de la batterie est faible, la caméra PIR transmet le signal de batterie faible au panneau de commande. Si un mouvement est détecté dans des conditions de batterie faible, la LED bleue clignote pendant 2 secondes.

Lors du changement de batterie, après avoir retiré l'ancienne batterie, appuyez deux fois sur l'interrupteur anti-sabotage ou sur le bouton de fonction pour la décharger complètement avant d'insérer de nouvelles piles.

* _**Autoprotection**_

La caméra PIR est protégée par un interrupteur anti-sabotage qui est compressé lorsque la caméra PIR est correctement installée. Lorsque la caméra PIR est retirée de la surface montée ou que son couvercle est ouvert, l'interrupteur d'autoprotection sera activé et la caméra PIR enverra un signal d'autoprotection au panneau de commande du système pour rappeler à l'utilisateur la condition. Si un mouvement est détecté lorsque l'interrupteur anti-sabotage est ouvert, la LED bleue clignote pendant 2 secondes.

* _**Surveillance**_

La caméra PIR effectuera périodiquement un auto-test en transmettant un signal de supervision toutes les 30 à 50 minutes.

* _**Mode d'essai**_
* Le mode test vous permet de vérifier la plage de détection de la caméra PIR (et non la couverture de prise de vue).
* Appuyez une fois sur le bouton Fonction pour passer en mode Test pendant 3 minutes, la LED bleue clignotera pendant 1 seconde.
* La caméra PIR se réchauffera pendant 30 secondes. Veuillez ne pas déclencher la caméra pendant cette période d'échauffement.
* Après la période de préchauffage, vous pouvez déclencher la caméra PIR pour vérifier la plage de détection IR. Si la caméra PIR est déclenchée, la LED bleue clignote pendant 2 secondes.

\\

* Pour que le mode test fonctionne correctement, il est recommandé de désactiver la minuterie de mise en veille.
* _Apprentissage_
* Retirez le couvercle du compartiment à piles en desserrant la vis du compartiment à piles.
* Insérez les piles. Orientez la batterie selon l'indication de polarité.
* Mettez le panneau de commande en mode apprentissage, reportez-vous au manuel du panneau de commande pour plus de détails.
* Appuyez et maintenez le bouton de fonction pendant 3 secondes, relâchez le bouton lorsque la LED bleue s'allume. (Pour le panneau fonctionnant sur batterie, après avoir appuyé et maintenu enfoncé le bouton de fonction pendant 3 secondes, veuillez appuyer sur le bouton de fonction**encore**pendant une seconde.)
* La LED bleue s'allumera pendant 25 secondes en mode d'apprentissage, ajoutez la caméra PIR au panneau de commande pendant cette période (référez-vous à votre panneau de commande pour terminer l'apprentissage en cours). Si le PIR est ajouté avec succès au panneau de commande, la LED bleue clignotera 6 fois pour l'indiquer. Si le PIR n'est pas ajouté dans les 25 secondes, veuillez répéter le processus d'apprentissage.

\\

* Si la caméra PIR existe déjà dans un système du panneau de configuration, vous devrez d'abord supprimer la caméra PIR du panneau de configuration avant de pouvoir l'enregistrer dans un autre panneau de configuration.
* Lors de l'apprentissage de la caméra PIR dans un répéteur/routeur, veuillez appuyer une fois sur le bouton de fonction (au lieu de le maintenir enfoncé pendant 3 secondes) pour envoyer un code d'apprentissage. (Modèles P5 uniquement)
* _Test de marche_
* Une fois la caméra PIR apprise, placez le panneau de commande sur «**Test de marche**", maintenez la caméra PIR à l'emplacement souhaité et appuyez sur le bouton de fonction pour confirmer que cet emplacement est à portée du signal du panneau de commande, reportez-vous au manuel du panneau de commande pour effectuer le test de marche.
* Lorsque vous êtes convaincu que la caméra PIR fonctionne à l'emplacement choisi, vous pouvez procéder au montage.
* _**Modifier la zone de fonctionnement de la caméra PIR**_
* Suivez les instructions ci-dessous pour modifier la zone de la caméra PIR dans le panneau de configuration.

1. Utilisez la fonction Modifier l'appareil du panneau pour modifier les paramètres de la zone de la caméra PIR.
2. Appuyez et maintenez enfoncé le bouton de fonction pendant 3 secondes sur la caméra PIR pour envoyer un signal au panneau, puis relâchez le bouton lorsque la LED s'allume. (Pour le panneau fonctionnant sur batterie, après avoir appuyé et maintenu enfoncé le bouton de fonction pendant 3 secondes, veuillez appuyer sur le bouton de fonction**encore**pendant une seconde pour envoyer un signal.)

* Installation
* _Directive d'installation_
* La caméra PIR est conçue pour être montée sur une surface plane ou dans un coin avec les vis de fixation et les chevilles fournies.
* La base comporte des découpes, là où le plastique est plus fin, à des fins de montage. Deux découpes sont destinées à la fixation en surface et un support de montage triangulaire est utilisé pour la fixation en coin.
* La portée de détection peut atteindre 12 mètres si la caméra PIR est montée à 2 mètres au-dessus du sol.
* Les modèles Pet-Immune offrent une portée typique PET IMMUNE de 7 mètres lorsqu'ils sont montés entre 1,9 et 2 mètres au-dessus du sol. Si nécessaire, vous pouvez régler la hauteur de la caméra PIR en fonction de la taille de votre animal pour une performance immunitaire optimale. Un emplacement d'installation plus élevé offrira un plus grand espace immunisé contre les animaux de compagnie, mais augmentera également l'angle mort sous la caméra PIR.
* Lorsque le VST-862 est monté avec un support rotatif, il n'aura pas la zone de détection normale (comme dans le diagramme) ni la plage d'immunité typique aux animaux.

![](<.gitbook/assets/5 (2) (1).png>)

**Il est recommandé d'installer la caméra PIR aux endroits suivants**

* Montez là où les animaux ne peuvent pas accéder à la zone de détection en grimpant sur des meubles ou d'autres objets.
* Ne dirigez pas le détecteur vers des escaliers sur lesquels les animaux peuvent monter.
* Dans une position telle qu’un intrus se déplacerait normalement dans le champ de vision du PIR.
* Entre 1,9 et 2 m du sol pour de meilleures performances.
* Dans un coin pour donner la vue la plus large.
* Où son champ de vision ne sera pas obstrué, par ex. par des rideaux, des ornements, etc.
* **Limites**
* N'installez pas la caméra PIR complètement exposée à la lumière directe du soleil.
* Évitez d'installer la caméra PIR dans des zones où les appareils peuvent provoquer un changement rapide de température dans la zone de détection, c'est-à-dire un climatiseur, un chauffage, etc.
* Évitez les gros obstacles dans la zone de détection.
* Ne pas pointer directement vers des sources de chaleur, par ex. Feux ou chaudières, et pas au-dessus des radiateurs.
* Évitez de déplacer des objets dans la zone de détection, par exemple un rideau, une tenture murale, etc.
* **Assurez-vous de toujours maintenir la force du signal RSSI stable à « 4 ».**
* ![852 r3 knockouts](<.gitbook/assets/6 (2) (1).jpeg>)_Montage de la caméra PIR_
* Le PIR est conçu pour être monté sur une surface plane ou dans un coin avec les vis de fixation et les chevilles fournies.
* Pour le montage en coin, un support triangulaire est fourni pour ajouter une protection anti-effraction arrière. Le support comprend également deux entrées défonçables à monter au mur.
* Pour le montage en surface, un support rotatif en option est fourni pour permettre aux utilisateurs d'ajuster la plage de détection. Grâce au support rotatif, le VST-862 peut pivoter de 80 degrés horizontalement et de 70 degrés verticalement pour offrir une couverture optimale.
* **Montage en coin :**

1. Percez les deux découpes du support triangulaire.
2. Utilisez les deux trous comme gabarit pour percer des trous sur la surface du coin.
3. Insérez les chevilles murales.
4. Vissez le support triangulaire dans les chevilles murales avec les deux bâtons de pointage en haut face à vous.
5. Fixez la caméra PIR sur les crochets du support triangulaire.

* **Montage en saillie :**

1. ![triangular bracket](<.gitbook/assets/7 (8).jpeg>)![triangular bracket](<.gitbook/assets/8 (7).jpeg>)Ouvrez le couvercle en desserrant la vis du couvercle à l'aide d'un tournevis Philips.
2. Brisez les 2 découpes de surface au centre de la base.
3. Utilisez les trous comme gabarit pour percer des trous sur la surface.
4. Insérez les chevilles murales si vous le fixez dans du plâtre ou de la brique.
5. Vissez la base dans les chevilles murales.
6. Installez le couvercle sur la base et serrez.

* **Montage en surface avec support rotatif (article en option, vendu séparément) :**

Le support rotatif peut être monté au mur à l'aide des vis fournies.

1. Vissez le support rotatif dans le mur.
2. Insérez les 3 crochets du support rotatif dans les 3 trous de la base en conséquence.
3. Faites pivoter le support pour obtenir la plage de détection appropriée et serrez la vis de fixation.

![](<.gitbook/assets/9 (11).png>)

Remarque : L'erreur de contrôle ou le contrôle d'erreur est dû au fait qu'un appareil normalement PIRCAM ou une caméra pir n'a pas été ajouté en appuyant sur le bouton d'apprentissage pendant 4 secondes.
