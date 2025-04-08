---
icon: circle-chevron-right
---

# VESTA 009N

**IR-16**



**Détecteur PIR**



**Introduction**

Notre algorithme de processeur de signal adaptatif numérisé permet à ce détecteur PIR de capter les mouvements dans la zone de couverture et de signaler une alarme à la centrale si un intrus croise sa zone de détection.\
Le détecteur PIR est composé de deux éléments, le couvercle et la base. Le couvercle contient toute l'électronique et l'optique et la base fournit un moyen de fixation. La base comporte des découpes pour permettre un montage sur une surface plane ou dans un angle avec un support triangulaire.\
Le détecteur PIR dispose d'une autoprotection qui s'activera lorsque le couvercle est ouvert. Il peut également vous alerter des problèmes de communication et des situations de batterie faible.\
Le détecteur  PIR est conçu pour offrir une portée de 12 mètres lorsqu'il est monté à 2 mètres de haut.\
\
**Les détecteurs de la série IR-16 sont les suivants:**\
\
IR-16 – Détecteur PIR avec batterie lithium 3,6 V\
IRP-16 – Détecteur PIR, immunité animaux avec batterie lithium 3,6 V\
IR-16SL – Détecteur PIR avec batterie au lithium 3V\
IRP-16SL – Détecteur PIR, immunité animaux avec batterie au lithium 3 V

\


* _**Identification**_

<figure><img src=".gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

1. **Bouton de test/indicateur LED**\
   Le bouton de test est utilisé pour tester les performances du signal radio et pour l'apprentissage.   \
   Le voyant LED est utilisé pour indiquer l'état du périphérique.
2. **Autoprotection**\
   L'autoprotection protège le détecteur PIR contre l'ouverture bu boîtier.
3. **Opercule de batterie**
4.  **Support d'angle**\


    <figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>
5. **Cavalier de supervision (JP2)**\
   **-** Cavalier Off : la supervision est activée (**par défaut pour les modèles 868WF**)\
   **-** Cavalier On : la supervision est désactivée (**par défaut pour les modèles 433AM**)\
   Pour les modèles **433AM** ou **868WF** ne disposant pas de cavalier JP2, la supervision est activée et ne peut pas être désactivée
6. **Cavalier de sensibilité (JP3)**\
   **-** Cavalier Off : la sensibilité du détecteur PIR est au niveau normal **(par défaut pour les modèles sans immunité animaux)**.\
   \- Cavalier On : la sensibilité du détecteur PIR est élevée (par défaut pour les modèles avec immunité animaux)**.**
7. **Autoprotection**



* _**Mise en veille**_\
  Le détecteur PIR a une "**mise en veille**" d'environs 1 minute pour économiser de l'énergie. Après avoir transmis un mouvement détecté, le détecteur PIR ne retransmettra pas pendant 1 minute. Tout mouvement détecté pendant cette période réinitialisera la temporisation de mise en veille de 1 minute. Un mouvement continu devant le PIRCAM n'épuisera donc pas la batterie.



* _**Supervision**_\
  Si elle est activée (voir ci-dessus), lorsque le détecteur PIR est en mode de fonctionnement normal, il effectuera un auto-test en transmettant un signal de supervision une fois toutes les 30 à 50 minutes.  \
  Si la centrale ne parvient pas à recevoir les signaux de supervision pendant une durée définie, un message de défaut sera généré



* _**Augmentation de la sensibilité**_\
  Vous pouvez utiliser la fonction d’augmentation de sensibilité pour augmenter la sensibilité de détection du détecteur PIR. Pour augmenter la sensibilité de détection, connectez le cavalier (JP3) ou le mettre en position ON (par défaut pour les modèles avec immunité animaux). Pour maintenir une sensibilité normale, déconnectez le cavalier (JP3) ou le mettre en position OFF (par défaut pour les modèles sans immunité animaux)



* _**Mode d'essai**_\
  Le détecteur PIR peut être mis en mode Test en appuyant sur le bouton test. En mode Test, il désactivera la mise en veille et permettra au voyant LED de clignoter à chaque fois qu'un mouvement est détecté. Chaque fois que vous appuyez sur le bouton de test, le détecteur PIR transmettra un signal de test à la centrale pour un test de portée radio et entrera en mode test pendant 3 minutes. Le mode test expirera après 3 minutes



* _**Voyant LED**_

En mode de fonctionnement normal, le voyant LED ne s'allumera pas sauf dans les situations suivantes :

* Lorsque le PIR est en état de batterie faible, chaque fois qu'il transmet un mouvement détecté, la LED s'allume pendant environ 2 secondes.
* Lorsque le couvercle est ouvert et que l'interrupteur anti-sabotage est violé, la LED s'allume pendant 2 secondes. pour indiquer qu'il transmet le

1

“**Altérer**» signale-t-il.

*
  * Lorsque la condition de sabotage persiste, chaque fois qu'il transmet un mouvement détecté, la LED s'allumera.
  * Lorsque le PIR est en mode Test, la LED s'allume à chaque fois qu'un mouvement est détecté.
* _**Batterie**_

Le capteur de mouvement PIR de la série IR-16 utilise différentes piles au lithium comme source d'alimentation :

* Les modèles non SL utilisent une pile au lithium AA 3,6 V (ER14505) comme source d'alimentation.
* Les modèles SL utilisent une pile au lithium 3 V 2/3 A (CR123) comme source d'alimentation.

Lorsqu'une faible tension de batterie est détectée, un signal de batterie faible sera envoyé au panneau de commande avec des transmissions de signal régulières pour que le panneau de commande affiche l'état en conséquence.

La batterie est installée en usine avant expédition avec un isolant inséré.

_\\_

*
  *
    *
      * Lors du changement des piles, après avoir retiré les anciennes piles, appuyez deux fois sur l'interrupteur anti-sabotage pour les décharger complètement avant d'insérer de nouvelles piles.
* _**Commencer**_
  * Retirez l'isolant de la batterie pour activer la batterie.
  * L'indicateur LED clignote pendant 30 secondes. (Le PIR s'échauffe). Pendant la période de préchauffage, le PIR ne sera pas activé. Il est recommandé de rester à l'écart de la zone de détection pendant cette période. Une fois la période de préchauffage terminée, la LED s'éteindra et le PIR sera prêt à fonctionner.
  * Mettez le panneau de commande en mode apprentissage, reportez-vous au manuel du panneau de commande pour plus de détails.
  * Appuyez sur le bouton de test sur le capot avant.
  * Reportez-vous au manuel du panneau de commande pour terminer le processus d'apprentissage.
  * Une fois le PIR appris, placez le panneau de commande sur «**Test de marche**", maintenez le PIR à l'emplacement souhaité et appuyez sur le bouton Test pour confirmer que cet emplacement est à portée du signal du panneau de commande, reportez-vous au manuel du panneau de commande pour terminer le test de marche.
  * Lorsque vous êtes convaincu que le PIR fonctionne à l'emplacement choisi, vous pouvez procéder au montage.
* _**Méthode de montage**_
  * Le PIR est conçu pour être monté sur une surface plane ou dans un coin avec les vis de fixation et les chevilles fournies.
  * La base comporte des découpes, là où le plastique est plus fin, à des fins de montage. Quatre découpes sont destinées à la fixation en surface.
  * Pour le montage en coin, un support triangulaire est fourni pour ajouter une protection anti-effraction arrière. Montez d'abord le support triangulaire sur le mur avec les deux bâtons de pointage en haut face à vous. Fixez le PIR sur les crochets du support triangulaire ou vissez le PIR dessus.
  * Pour le montage en surface, un support rotatif en option est fourni pour permettre aux utilisateurs d'ajuster la plage de détection. Grâce au support rotatif, l'IR-16 peut pivoter de 80 degrés horizontalement et de 70 degrés verticalement pour offrir une couverture optimale.
    * **Montage en coin :**

I. Casser les deux découpes du support triangulaire.

![](<.gitbook/assets/5 (9).jpeg>)

1. En utilisant les deux trous comme gabarit, percez des trous dans la surface du coin.
2. Insérez les chevilles murales.

IV. Vissez le support triangulaire dans les chevilles murales avec les deux bâtons de pointage en haut face à vous (utilisez un tournevis Philips).

1. Fixez le PIR sur les crochets du support triangulaire.

VI. Si nécessaire, ouvrez le PIR en retirant l'ensemble vis de fixation et couvercle à l'aide d'un tournevis Philips.

VII. Percez les ouvertures défonçables appropriées pour la fixation des coins.

VIII. En utilisant les découpes de fixation d'angle comme modèle, percez à nouveau des trous dans la surface du coin.

![](<.gitbook/assets/6 (13).jpeg>)

IX. Insérez les chevilles murales si vous le fixez dans du plâtre ou de la brique.

1. Fixez le PIR sur les crochets du support triangulaire.

XI. Vissez la base dans les chevilles murales à l'aide d'un tournevis Philips.

XII. Revissez le couvercle sur sa base à l'aide d'un tournevis Philips.

* **Montage en saillie :**

1. Retirez la vis de fixation et l'ensemble couvercle à l'aide d'un tournevis Philips.
2. Percez les trous appropriés sur la base.
3. En utilisant les trous comme gabarit, percez des trous dans la surface.

IV. Insérez les chevilles murales si vous le fixez dans du plâtre ou de la brique.

*
  *
    1. Vissez la base dans les chevilles murales à l'aide d'un tournevis Philips.

VI. Revissez le couvercle sur sa base à l'aide d'un tournevis Philips.

* \*\*Montage en surface avec support rotatif (article en option, vendu séparément) :\*\*Le support rotatif peut être monté au mur à l'aide des vis fournies.
  1. Vissez le support rotatif dans le mur.

1. Insérez les 3 crochets du support rotatif dans les 3 trous de la base en conséquence.

2

*
  *
    1. Faites pivoter le support pour obtenir la plage de détection appropriée et serrez la vis de fixation.
* _**Installation**_
  * Décidez de l'emplacement du PIR et s'il doit être monté en coin ou en surface.
  * Une fois le site d'installation sélectionné, suivez les étapes décrites ci-dessus pour monter le PIR.
  * Appuyez sur le bouton Test pour accéder au mode Test. Parcourez la zone protégée en notant quand la LED s'allume et vérifiez que la couverture de détection est adéquate.
  * Lorsque la couverture de détection s'avère satisfaisante, l'installation est désormais terminée.
* _**Recommandations d'installation**_

**PIR régulier**

* La portée de détection peut atteindre 12 mètres si le PIR est monté à 2 mètres au-dessus du sol.

**PIR immunisé contre les animaux**

* Le PIR Pet-Immune prend en charge la fonction d'immunité aux animaux et ne détectera pas les animaux pesant jusqu'à 27 kg dans un rayon de 7 mètres afin de minimiser les situations de fausse alarme.
* Si nécessaire, vous pouvez ajuster la hauteur du PIR en fonction de la taille de votre animal pour une performance immunitaire optimale. Un emplacement d'installation plus élevé offrira un plus grand espace immunisé contre les animaux de compagnie, mais augmentera également l'angle mort sous le PIR.

![](<.gitbook/assets/7 (12).jpeg>)

Pour tirer pleinement parti du PIR, les directives suivantes doivent être prises en compte :

* **Il est recommandé d'installer le PIR aux emplacements suivants**
  * Montez le détecteur à une hauteur de 1,9 M à 2,0 M pour de meilleures performances :

_\\_

*
  * Lorsque vous décidez de la hauteur du site de montage du PIR, n'oubliez pas de prendre en compte l'éventuel angle mort. L'angle mort sous le PIR s'agrandit proportionnellement à la hauteur du site de montage du PIR.
  * Veuillez noter que les performances sont affectées par des facteurs externes, tels que la hauteur de l'objet détecté, la plage de détection souhaitée, la zone d'installation… etc. La hauteur de montage suggérée peut être ajustée en fonction des facteurs réels de l'environnement d'installation.
* Lorsque l'IR-16 est monté avec un support rotatif, il n'aura pas la zone de détection normale (comme dans le diagramme ci-dessus) ni la plage d'immunité typique aux animaux de compagnie.
  * Montez là où les animaux ne peuvent pas accéder à la zone de détection en grimpant sur des meubles ou d'autres objets.
  * Ne dirigez pas le détecteur vers des escaliers sur lesquels les animaux peuvent monter.
  * Dans une position telle qu’un intrus se déplacerait normalement d’un côté à l’autre du champ de vision du PIR.
  * Dans un coin pour donner la vue la plus large.
  * Où son champ de vision ne sera pas obstrué, par ex. par des rideaux, des ornements, etc.
* **Limites**
  * Ne positionnez pas un PIR pour regarder directement une porte protégée par un contact de porte, cela pourrait provoquer la transmission des signaux radio du contact de porte et du PIR au même instant lors de l'entrée, s'annulant mutuellement.
  * N'installez pas le PIR complètement exposé à la lumière directe du soleil.
  * Évitez d'installer le PIR dans des zones où les appareils peuvent provoquer un changement rapide de température dans la zone de détection, c'est-à-dire un climatiseur, un chauffage, etc.
  * Évitez les gros obstacles dans la zone de détection.
  * Ne pas pointer directement vers des sources de chaleur, par ex. feux ou chaudières, et pas au-dessus des radiateurs.
  * Évitez de déplacer des objets dans la zone de détection, par exemple un rideau, une tenture murale, etc.

3
