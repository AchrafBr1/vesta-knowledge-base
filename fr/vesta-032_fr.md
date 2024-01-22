# VESTA 032

Détecteur de fumée et de monoxyde de carbone (série SDCO-1-F1)

Introduction

La série SDCO-1-F1 est un détecteur de fumée et de monoxyde de carbone. Il est capable d'envoyer des signaux sans fil au panneau de commande lors de la détection de particules de fumée ou de monoxyde de carbone. Le SDCO-1 est conçu pour être monté au plafond ou au sommet des cages d'escalier où la fumée se concentrerait pour déclencher une alarme en temps opportun et protéger votre maison des risques d'incendie.

La série SDCO-1 comprend les modèles suivants :

| **Nom du modèle** | **Chaleur** | **2 voies** | **Connexion série** |
| ----------------- | ----------- | ----------- | ------------------- |
| SDCO-1-F1         |             |             |                     |
| SDCO-1H-SC        | dans        |             | dans                |
| SDSU-1-F1-2F      |             | dans        |                     |
| SDCO-1H-F1        | dans        |             |                     |
| SDSU-1H-F1-2F     | dans        | dans        |                     |

Identification des pièces

![](<.gitbook/assets/0 (11).png>)

1.  **Bouton de test**

-   Appuyez une fois sur le bouton pour envoyer un signal de test/apprentissage.
-   Appuyez une fois sur le bouton pendant l'alarme pour passer en mode silence d'alarme.
-   Appuyez et maintenez le bouton pendant 10 secondes. Relâchez le bouton lorsque le SDCO émet 2 bips pour entrer dans l'étalonnage de la fumée et le CO.

processus d’autodiagnostic.

-   Appuyez deux fois sur le bouton pour décharger complètement avant d'insérer de nouvelles piles.

1.  **Indicateur LED**

**LED rouge**

-   S'allume brièvement : transmission du signal de test/apprentissage.
-   Flash rapide : Alarmant.
-   Clignote toutes les secondes : en mode silence d'alarme.
-   Clignote toutes les 2 secondes : pendant le processus de préchauffage et d’étalonnage.

**LED ambre**

-   Clignote toutes les 5 secondes : dysfonctionnement de l'appareil
-   Clignote toutes les 45 secondes : état de batterie faible

**LED rouge et orange (orange lorsque vous regardez de l'extérieur)**

-   Clignote toutes les 4 secondes : les piles sont extrêmement faibles et doivent être remplacées.

1.  **Avertisseur sonore**
2.  **Trous de montage (pour crochets)**

Les crochets du support de montage peuvent s'accrocher à ses trous de montage.

1.  **Support de montage**
2.  **Couvercle du compartiment à piles**
3.  **Vis de fixation du couvercle du compartiment à piles**
4.  **Encoches**
5.  **Port de mise à jour du micrologiciel (USB Type-C)**

-   Pour la mise à jour du micrologiciel avec un câble personnalisé uniquement.**Veuillez noter:**Une mauvaise utilisation d’un câble USB Type C normal peut entraîner un dysfonctionnement de l’appareil.

Caractéristiques

-   Détection de batterie et de batterie faible
-   Le SDCO-1 utilise trois batteries au lithium EL123AP comme source d'alimentation. Les piles sont incluses dans le colis.
-   Le SDCO dispose d'un mécanisme infaillible qui interdit la fermeture du couvercle sans installer au préalable la batterie.
-   Lorsque la batterie du SDCO est faible, un signal de batterie faible sera transmis avec les transmissions de signaux régulières. La LED orange clignotera avec un bip de faible volume toutes les 45 secondes.
-   Les LED rouge et orange clignotent toutes les 4 secondes lorsque les piles sont extrêmement faibles et doivent être remplacées.
-   Lors du changement des piles, après avoir retiré les anciennes piles, appuyez deux fois sur le bouton Test pour les décharger complètement avant d'insérer de nouvelles piles.
-   Commencer

**Étape 1:**Utilisez un tournevis cruciforme pour desserrer la vis de fixation du compartiment à piles et retirez le couvercle du compartiment à piles.

**Étape 2:**Insérez 3 piles dans le compartiment à piles.

**Étape 3:**Le détecteur SDCO émettra 2 bips courts et commencera le processus de préchauffage pour**1**minute. La LED clignotera toutes les 2 secondes.

**Étape 4.**Pendant la période d'une minute, apprenez dans le détecteur de fumée.

1.  Appuyez une fois sur le bouton Apprendre/Test pour transmettre un code d'apprentissage du capteur IR.
2.  Appuyez et maintenez enfoncé le bouton Apprendre/Test pendant 3 secondes pour transmettre un code d'apprentissage du capteur de fumée/température.**(l'étape a. et l'étape b. sont toutes deux requises pour les modèles connectés en série)**.

Si le panneau de commande reçoit le signal, le détecteur de fumée émettra un bip à 2 tons. Reportez-vous au manuel du panneau de commande pour terminer le processus d'apprentissage.

**Étape 5 :**À l'expiration de la période de préchauffage d'une minute, le détecteur SDCO émettra un bip pour indiquer qu'il entre maintenant dans le processus d'étalonnage. Le

le processus d'étalonnage prend 1~7 minutes ; la LED continuera à clignoter pendant l'étalonnage.

**Étape 6 :**Une fois l'étalonnage terminé, le détecteur SDCO émettra un son à 2 tons et la LED cessera de clignoter pour indiquer qu'il est maintenant sous

fonctionnement normal. Si l'étalonnage échoue, le détecteur SDCO émettra des bips continus.

-   _**Détection d'alarme**_

Le détecteur SDCO activera l'alarme incendie lorsque sa fonction de détection de fumée ou de détection de chaleur élevée est déclenchée. Lorsqu'une alarme est activée, le détecteur SDCO transmet un signal d'alarme et déclenche une alarme grâce à son buzzer intégré. La LED rouge clignotera rapidement.

**Détection de fumée :**

-   Le détecteur SDCO vérifie la concentration de fumée toutes les 8 secondes
-   Chaque fois que la concentration de fumée dépasse le seuil de détection, SDCO enverra un signal actif au panneau de commande et activera l'alarme.
-   Si la concentration de fumée persiste, le détecteur SDCO continuera à envoyer le signal actif toutes les 2 minutes au panneau de commande.
-   Si aucune fumée n'est détectée pendant 20 temps de détection continus, le SDCO transmettra un signal de restauration et arrêtera l'alarme.

**Détection de chaleur (pour les modèles SDCO-1H-F1 et SDCO-1H-F1-2W uniquement) :**

-   Le détecteur SDCO vérifie la température toutes les 10 secondes.
-   L'alarme sera activée dans les conditions suivantes :

\-Lorsque la température augmente de 8,25°C par minute (taux de montée).

\-Lorsque la température dépasse 57,25°C (chaleur élevée).

-   Si aucune chaleur élevée n'est détectée pendant 20 temps de détection continus, le SDCO transmettra un signal de restauration et cessera de déclencher une alarme.
-   Si l'alarme a été déclenchée par une condition de chaleur élevée (57,25°C), la température doit descendre en dessous de 49°C pour que le détecteur cesse de déclencher l'alarme.
-   Si l'alarme a été déclenchée par une condition de taux d'augmentation (8,25 °C par minute ou plus), la température doit descendre à 4 °C en dessous de la température la plus élevée détectée pour que le détecteur arrête de déclencher l'alarme.

**Détection du monoxyde de carbone :**

-   Le capteur de CO vérifie le niveau de concentration de CO toutes les 16 secondes. Si le niveau de concentration dépasse le seuil de détection, le détecteur SDCO transmettra un signal d'alarme et déclenchera une alarme grâce à son buzzer intégré.
-   Le capteur de CO dispose d'une fonction d'autodiagnostic et vérifiera régulièrement l'état de santé ou l'état du capteur toutes les 12 heures.
-   L'alarme sera activée après détection de la concentration de CO selon la durée indiquée dans le tableau suivant : (conforme à la norme EN-50291)

| **Niveau de concentration de CO** | **Temps mis avant de alarmer** |
| --------------------------------- | ------------------------------ |
| 30 +/- 10% ppm                    | N / A                          |
| 50 +/- 10% ppm                    | 60~90 minutes                  |
| 100 +/- 10 % ppm                  | 10~40 minutes                  |
| 300 +/- 10 % ppm                  | Moins de 3 minutes             |

-   L'alarme sera activée après la détection de la concentration de CO selon la durée indiquée dans le tableau suivant : (conforme à la norme UL-2034)

| **Niveau de concentration de CO** | **Temps mis avant de alarmer** |
| --------------------------------- | ------------------------------ |
| 30 +/- 3% ppm                     | N / A                          |
| 70 +/- 5% ppm                     | N / A                          |
| 70 +/- 5% ppm                     | 60~240 minutes                 |
| 150 +/- 5% ppm                    | 10~50 minutes                  |
| 400 +/- 10% ppm                   | 4~15 minutes                   |

-   Une fois que le niveau de concentration de CO dépasse le seuil et persiste pendant la durée indiquée dans le tableau ci-dessus, le détecteur SDCO transmettra le signal au panneau de commande et déclenchera une alarme avec sa sirène intégrée.
-   Test du détecteur SDCO

En appuyant sur le bouton Test du détecteur SDCO, vous pouvez tester si le SDCO fonctionne normalement.

-   Si le détecteur SDCO fonctionne normalement, la LED rouge clignotera une fois suivie d'un bip à 2 tons.
-   Si trois bips sonores (DO-DI DO-DI DO-DI) sont émis, cela signifie que le capteur de fumée est en panne.
-   Si 5 bips (DO-Bi-Bi-Bi-DO) sont émis, cela signifie que le capteur de chaleur est en panne.
-   Si 7 bips (Bi-Bi-Bi-DO-Bi-Bi-Bi) sont émis, cela signifie que le capteur de CO est en panne.
-   _**Surveillance**_
-   Pour les modèles SDCO-1(H)-F1, le détecteur SDCO transmettra un signal de supervision pour signaler régulièrement son état toutes les 30 à 50 minutes.
-   Pour les modèles SDCO-1(H)-F1-2W, le détecteur SDCO transmettra un signal de supervision pour signaler régulièrement son état toutes les 90 à 110 minutes.
-   Si le panneau de commande n'a pas reçu le signal du détecteur de fumée pendant une période de temps prédéfinie, le panneau de commande déterminera que le détecteur de fumée est en panne.
-   _Connexion série__(modèle connecté en série uniquement)_
-   Le détecteur de fumée est en connexion série avec d'autres détecteurs de fumée du système d'alarme. Lorsqu'un détecteur de fumée active l'alarme, le panneau de commande informera les autres détecteurs de fumée de déclencher également l'alarme même s'ils n'ont pas encore détecté de fumée. La durée de l’alarme sera conforme aux paramètres du panneau de commande.
-   Vous ne pouvez pas appuyer sur le bouton de fonction pour désactiver l'alarme activée par d'autres détecteurs de fumée.
-   L'alarme ne sera restaurée qu'après un délai de 3 minutes ou jusqu'à ce que l'autre détecteur de fumée qui déclenche l'alarme transmette un signal de rétablissement.
-   Silence d'alarme
-   Lorsque le détecteur de fumée déclenche une alarme, appuyer sur le bouton Test mettra le détecteur de fumée en mode Silence d'alarme pour faire taire l'alarme pendant 9 minutes. Le buzzer ne cessera de retentir qu'après que l'alarme ait été activée pendant au moins 1 minute. Si le bouton est enfoncé avant que l'heure de l'alarme n'atteigne 1 minute, le détecteur de fumée attendra que l'heure de l'alarme atteigne 1 minute avant de désactiver l'alarme.
-   Pendant la période de silence d'alarme de 9 minutes, la LED rouge clignote une fois par seconde. Le détecteur de fumée continuera à surveiller la concentration de fumée pendant la période de silence de l'alarme :

1.  Après l'expiration de la période de silence de l'alarme de 9 minutes, si la concentration de fumée descend en dessous du seuil d'alarme, le détecteur de fumée émettra un bip à 2 tons et reviendra à un fonctionnement normal sans déclencher d'alarme.
2.  Si la concentration de fumée dépasse toujours le seuil d'alarme, le détecteur de fumée recommencera à émettre une alarme.
3.  Si la concentration de fumée continue d'augmenter pendant la période de silence de l'alarme et dépasse un deuxième seuil d'alarme, le détecteur de fumée recommencera à émettre une alarme. Une alarme déclenchée par le dépassement du deuxième seuil d'alarme ne pouvait pas être désactivée en appuyant sur le bouton de test.

-   Réétalonnage

Le SDCO calibrera son capteur de détecteur de fumée à chaque fois que l'alimentation est appliquée pour garantir une sensibilité optimale à la fumée. Après l'installation, l'état de fonctionnement du détecteur de fumée peut varier après un certain temps, ce qui peut affecter sa fonction de détection de fumée et nécessiter un recalibrage. Il existe deux manières de recalibrer le détecteur de fumée : le calibrage automatique et le calibrage manuel.

**Calibrage automatique :**

-   Après la mise sous tension, le détecteur de fumée effectuera un calibrage automatique après 4 heures.
-   Après le premier calibrage automatique, le détecteur de fumée effectuera un calibrage automatique chaque mois. Pendant le processus d'auto-calibrage, le détecteur de fumée n'émettra aucun son.
-   Si l'étalonnage automatique échoue, la LED orange clignotera toutes les secondes avec des bips continus et le détecteur de fumée transmettra un signal d'échec d'étalonnage.
-   Lorsque l'étalonnage automatique du détecteur de fumée échoue, la fonction d'alarme de fumée fonctionnera toujours normalement en utilisant la valeur seuil issue du dernier étalonnage réussi.

**Calibrage manuel :**

-   L'étalonnage manuel peut être effectué à tout moment, comme vous le souhaitez :

1.  Appuyez et maintenez enfoncé le bouton Apprendre/Test pendant 10 secondes et relâchez-le lorsque le détecteur de fumée émet 2 bips.
2.  Le détecteur de fumée entrera dans le processus d'étalonnage. L'indicateur LED clignotera toutes les 2 secondes.
3.  Une fois le recalibrage terminé, le détecteur de fumée émettra deux bips rapides pour l'indiquer. La LED s'éteindra.
4.  Si le processus d'étalonnage échoue, le détecteur de fumée émettra une alarme sonore. Veuillez retirer et réinsérer la batterie pour redémarrer le processus.

![100-2](<.gitbook/assets/1 (15).png>)Installation

-   Directive d'installation
-   Il est recommandé que le site d'installation se situe au centre du plafond.
-   La hauteur de montage idéale pour le détecteur SDCO est comprise entre 2,4 mètres et 3 mètres. Un montage à plus de 3 mètres peut affecter les performances de détection.
-   Ne placez pas le détecteur dans les endroits suivants :
-   La cuisine – La fumée provenant de la cuisson peut provoquer une alarme indésirable.
-   ![100-3](<.gitbook/assets/2 (18).png>)À proximité d'un ventilateur, d'une lampe fluorescente ou d'un équipement de climatisation – les courants d'air qui en proviennent peuvent affecter la sensibilité du détecteur.
-   Près des poutres du plafond ou au-dessus d'une armoire – l'air stagnant dans ces zones peut affecter la sensibilité du détecteur.
-   Au sommet d’un plafond de type « A ».
-   Recommandation d'installation
-   **Limites**
-   N’installez pas le détecteur SDCO exposé à la lumière directe du soleil.
-   Évitez d'installer le détecteur SDCO dans des zones où les appareils peuvent provoquer un changement rapide de température dans la zone de détection, c'est-à-dire un climatiseur, des radiateurs, etc.
-   Évitez les gros obstacles dans la zone de détection.
-   Ne pointez pas directement vers des sources de chaleur, par ex. Feux ou chaudières, et pas au-dessus des radiateurs.
-   Montage du détecteur SDCO

**Étape 1.**Placez le détecteur SDCO à l'emplacement de montage souhaité et utilisez la fonction de test de portée pour vous assurer que le détecteur SDCO peut être reçu par le panneau de commande à l'emplacement de montage.

**Étape 2.**Le détecteur SDCO dispose d'un support de montage pour une installation au plafond. Le support offre une flexibilité bidirectionnelle.

**Étape 3.**Utilisez les 4 trous du support comme gabarit pour percer des trous et insérer des chevilles murales si nécessaire.

**Étape 4.**L'utilisateur peut faire pivoter le support de montage dans le sens des aiguilles d'une montre ou dans le sens inverse pour verrouiller le crochet. Assurez-vous que les chevilles murales affleurent la surface de montage.

**Étape 5.**Lorsque la position est satisfaisante, vissez le support de montage au plafond.

**Étape 6.**Essuyez soigneusement la poussière, sinon cela peut salir le capteur et l'empêcher de fonctionner correctement en cas d'urgence.

**Étape 7.**Le SDCO comporte trois encoches sur sa couverture arrière pour une identification facile, comme indiqué ci-dessous.

![](<.gitbook/assets/3 (17).png>)

**Étape 8.**Tenez le détecteur SDCO avec beaucoup de soin et alignez les trois encoches avec les crochets du support de montage.

**Étape 9.**Faites pivoter le détecteur SDCO dans le sens des aiguilles d’une montre pour verrouiller le crochet. L'installation est maintenant terminée.
