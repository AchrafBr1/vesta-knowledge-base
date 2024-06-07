# VESTA 199

**Manuel d'utilisation du contact de porte (DC-16SL)**

Le contact de porte surveille l'ouverture/fermeture d'appareils spécifiés (par exemple porte ou fenêtre). Le contact de porte est fixé au cadre de l'appareil surveillé à l'aide d'un aimant d'actionnement fixé sur l'appareil. Lorsque la porte ou la fenêtre s'ouvre, l'aimant s'éloigne du contact de porte, activant un interrupteur magnétique interne provoquant la transmission par le contact de porte d'un signal d'alarme au panneau de commande. L'appareil a également la capacité de communiquer les problèmes de signal ainsi que les situations de batterie faible.

La conception du contact de porte est composée d'un couvercle et d'une base. Le couvercle contient tous les composants électroniques et la base fournit un moyen de fixation de l'appareil. Un interrupteur anti-sabotage sur circuit imprimé fourni offre une protection contre l'ouverture et/ou le retrait non autorisé de l'appareil.

**Le contact de porte comprend les modèles de fréquence suivants :**

**433 m**

**433FM F1**

**868WF**

**868FM**

**868FM F1**

**869FM**

**869 F1**

![](<.gitbook/assets/0 (80).jpeg>)

* _**Identifier les pièces**_

![](<.gitbook/assets/1 (60).png>)

1. **Indicateur LED**
2. **Bouton Apprendre/Test**

\-Appuyez sur le bouton Test pour transmettre un code d'apprentissage.

\-Appuyez une fois sur le bouton Test pour passer en mode Test pendant 3 minutes.

1. **Cavalier de supervision (JP2)**

**Cavalier**

![](<.gitbook/assets/2 (65).jpeg>)

**Cavalier**

![](<.gitbook/assets/3 (59).jpeg>)

Le lien de cavalier est inséré si le lien de cavalier est retiré ou "**garé**» sur une épingle.

\~\~-\~\~Lorsque le cavalier est réglé sur ON, la supervision est désactivée.**(Par défaut d'usine pour 433AM)**

\-Lorsque le cavalier est réglé sur OFF, la supervision est activée.**(Par défaut d'usine pour les modèles 868WF, 868FM, 869FM)**

_**Les modèles 433FM-F1, 868FM-F1 et 869-F1 n'ont pas ce cavalier installé et la supervision est toujours activée**_

1. **Batterie**
2. **Trou de vis de fixation du couvercle**
3. **KO**
4. **Interrupteur anti-sabotage**
5. **Trou d'isolant de batterie**
6. **Marques de côtes**
7. **Aimant**

\-Montez l'aimant sur le côté du contact de porte où il comporte 2 nervures pour indiquer la position de l'interrupteur magnétique interne. Le contact de porte doit être installé soit verticalement, soit inversé pour garantir que le côté marqué par la nervure soit face à l'aimant.

1

*
  1. **Aimant Trou de vis**
  2. **Entretoise magnétique**
* _**Accessoires inclus**_
  *
    1. 1 aimant
    2. 2 vis
    3. 1 tampon adhésif double face
    4. 2 chevilles murales
    5. 2 vis de montage de l'aimant
    6. 1 entretoise magnétique
    7. 2 casquettes blanches
* _**Indicateur LED**_

![](<.gitbook/assets/4 (55).jpeg>) ![](<.gitbook/assets/5 (36).jpeg>)

En mode de fonctionnement normal, le voyant LED reste éteint sauf dans les situations suivantes :

*
  * Lorsque l’interrupteur anti-sabotage du contact de porte est déclenché.
  * Chaque fois que le contact de porte est activé avec une condition de sabotage ou de batterie faible.
  * Chaque fois que le contact de porte est activé et transmet le signal en mode test.
* _**Surveillance**_
  * S'il est activé, le contact de porte transmettra automatiquement des signaux de supervision périodiquement au panneau de commande à des intervalles aléatoires de 30 à 50 minutes en mode de fonctionnement normal.
  * Si le panneau de commande n'a pas reçu le signal du contact de porte pendant une période prédéfinie, le panneau de commande indiquera que ce contact de porte particulier rencontre un problème de manque de signal.
* _**Interrupteur anti-sabotage**_
  * Il est conçu pour protéger contre le retrait non autorisé de l'emplacement de montage, l'ouverture du couvercle ou une installation instable. Lorsque l'autoprotection est déclenchée, le contact de porte émettra un signal au panneau de commande pour rapport, la LED s'allumera également.
* _**Batterie**_

![](<.gitbook/assets/6 (45).jpeg>) ![](<.gitbook/assets/7 (42).jpeg>) ![](<.gitbook/assets/8 (38).jpeg>)

Le contact de porte utilise un**Pile au lithium 3V CR2**en tant que source d'alimentation, il est également capable de détecter une batterie faible. Lorsque la batterie est faible, un signal de batterie faible sera envoyé au panneau de commande avec une transmission régulière. La LED s'allumera lorsque le contact de porte est activé en cas de batterie faible. Lorsque la batterie est épuisée, le contact de porte arrêtera toutes les fonctions et la LED clignotera toutes les 4 secondes.

* **Changement de batterie :**

Une fois la batterie retirée, appuyez 5 à 6 fois sur le bouton Apprendre/Test pour la décharger complètement avant d'insérer la nouvelle batterie.

![](<.gitbook/assets/9 (39).png>)

_\\_

*
  * En raison des caractéristiques de la batterie, après avoir inséré une nouvelle batterie dans le contact de porte, celui-ci vérifiera automatiquement si cette batterie fonctionne correctement ou non dans les 16 minutes suivant l'insertion.
* _**Mode d'essai**_

![](<.gitbook/assets/10 (22).jpeg>)

Le contact de porte peut être mis en mode test pendant 3 minutes en appuyant une fois sur le bouton test situé sur le capot avant. Pendant le mode Test, le voyant LED s'allumera lors du déclenchement. À chaque pression sur le bouton de test, le contact de porte transmettra un signal de test au panneau de commande pour un test de portée radio et réinitialise le mode de test à la durée de 3 minutes. Il quittera automatiquement le mode test après 3 minutes et reviendra au mode de fonctionnement normal.

![](<.gitbook/assets/11 (25).jpeg>)

* _**Commencer**_

Étape 1 : retirez régulièrement l'isolant de la batterie.

Étape 2 : Mettez le panneau de commande en mode d'apprentissage, reportez-vous au manuel du panneau de commande pour plus de détails.

Étape 3 : Appuyez sur le bouton de test du contact de porte pour envoyer un signal au panneau de commande.

Étape 4 : Si le panneau de commande reçoit le signal avec succès, le panneau de commande doit répondre (par exemple en émettant des bips). Reportez-vous au manuel de votre panneau de configuration pour terminer le processus d'apprentissage.

Étape 5 : Une fois le contact de porte appris, placez le panneau de commande sur «**Test de marche**", maintenez le contact de porte à

l'emplacement souhaité et appuyez sur le bouton Test pour confirmer si cet emplacement est à portée du signal du panneau de commande.

Étape 6 : Lorsque vous êtes satisfait du contact de porte à l'emplacement choisi, procédez à l'installation.

![](<.gitbook/assets/12 (21).jpeg>)

* _**Installation**_

Étape 1 : Montez le contact de porte en utilisant l'une des méthodes ci-dessous.

Étape 2 : Montez l'aimant sur l'objet le plus mobile (comme la porte) à l'aide des vis fournies.

Alignez l'aimant en fonction de la marque de nervure sur le contact de porte.

Si nécessaire, utilisez l'entretoise magnétique pour mieux aligner l'aimant sur les marques de nervures.

![](<.gitbook/assets/13 (28).png>)

* _REMARQUE >_
  * L'aimant ne doit pas dépasser**15mm**du détecteur lorsque la porte est fermée.
  * Les deux capuchons blancs fournis peuvent être insérés dans les trous de vis de l'aimant pour une intégrité esthétique.

2

* ![](<.gitbook/assets/14 (21).jpeg>)_**Méthodes de montage**_

Il existe deux manières de monter le contact de porte : montage autocollant ou montage par vis.

![](<.gitbook/assets/15 (19).jpeg>)

* **Montage autocollant**

I. La surface de montage doit être propre, sèche et lisse. Nettoyer le

surface de montage avec un dégraissant approprié si nécessaire.

1. Retirez le revêtement protecteur d'un côté du tampon adhésif double face. Appliquer à l'arrière de l'appareil et appuyer fermement pour

30 secondes pour assurer un bon contact.

1. Retirez l'autre couvercle et appuyez fermement sur le contact de porte.

l'endroit souhaité pendant 30 secondes.

![](<.gitbook/assets/16 (27).png>)

_\\_

*
  * N'utilisez pas la méthode d'installation avec tampon adhésif sur une surface dont la peinture est écaillée ou craquelée, ou sur une surface rugueuse.
  * Veuillez ne pas réappliquer le ruban adhésif 3M. Il ne peut pas être réutilisé
  * Veuillez installer le contact de porte sur l'objet le plus fixe (tel qu'un cadre de porte ou un cadre de fenêtre) et monter l'aimant sur l'objet le plus mobile (tel qu'une porte ou une fenêtre).
* **Montage à vis**

La base comporte deux découpes, là où le plastique est plus fin, à des fins de montage. Pour monter le contact de porte :

*
  *
    1. Retirez le couvercle en dévissant la vis de fixation du couvercle à l'aide d'un tournevis Philips.

![](<.gitbook/assets/17 (18).jpeg>)

1. Brisez le KO sur la base.
2. En utilisant les trous comme gabarit, percez les deux trous.

IV. Insérez des chevilles murales si vous fixez dans du plâtre ou de la brique.

1. Vissez la base dans la prise murale à l'aide d'un tournevis Philips.

VI. Fixez le couvercle à la base et serrez la vis de fixation du couvercle.

3
