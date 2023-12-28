# VESTA 044

-   Télécommande universelle infrarouge UPIC-5ZW
-   Introduction

UPIC5-ZW est une télécommande infrarouge Z-Wave. Il est conçu pour faire fonctionner vos appareils électroménagers en transmettant un signal IR. La télécommande IR est capable d'apprendre le signal IR transmis par la télécommande de l'appareil. Après avoir appris le signal, vous pouvez contrôler à distance la télécommande infrarouge via le réseau Z-Wave pour envoyer le signal à l'appareil sans utiliser la télécommande manuellement.

L'UPIC-5ZW est un appareil compatible Z-Wave et est entièrement compatible avec tout réseau compatible Z-Wave.

Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance. En profitant du réseau maillé Z-Wave, les commandes peuvent être acheminées vers leur destination via des produits Z-Wave intermédiaires « d’écoute ».

La série de télécommandes infrarouges UPIC5 Z-Wave comprend les modèles suivants :

**UPIC5-ZW**Télécommande infrarouge

**UPIC5-ZW-OTA**Télécommande infrarouge avec fonction de mise à niveau du micrologiciel en direct

-   Identification des pièces

**1. Oeil IR**

![](<.gitbook/assets/0 (10).jpeg>)

Transmet le signal IR aux appareils.

**2. Bouton Fonction/IR**

Appuyez 3 fois sur le bouton en 1,5 seconde pour envoyer un code d'apprentissage.

Appuyez et maintenez le bouton enfoncé pendant 10 secondes pour réinitialiser les paramètres d'usine.

Appuyez et maintenez le bouton enfoncé pendant 3 secondes pour accéder au mode d'apprentissage IR.

Appuyez une fois sur le bouton pour transmettre le signal/quitter le mode d'apprentissage IR.

**3. Z-WaveLED**

Clignote une fois – La télécommande IR transmet un signal

**4. Indicateur LED IR**

Flash lent – ​​Télécommande IR en mode d'apprentissage IR.

Flash rapide – La télécommande IR reçoit un signal IR en mode d'apprentissage ou transmet un signal IR

Flash toutes les demi-secondes – données IR effacées

Éteint – La télécommande IR stocke le signal IR reçu en mode d'apprentissage.

– La télécommande IR est en mode veille.

**5. Récepteur de signaux infrarouges**

**6. Cavalier de puissance de transmission IR faible (JP1)**

**Cavalier**

si le cavalier est retiré ou "**garé**» sur une épingle.

**Cavalier**

Le cavalier est inséré reliant les deux broches

![](<.gitbook/assets/1 (17).png>)![](<.gitbook/assets/2 (20).png>)

Cavalier ON – Puissance de transmission IR réglée sur Faible.**(Défaut de fabrication)**

Cavalier OFF – Désélectionné.

**7. Cavalier de puissance de transmission IR élevé (JP2)**

**Cavalier**

si le cavalier est retiré ou "**garé**» sur une épingle.

**Cavalier**

Le cavalier est inséré reliant les deux broches

![](<.gitbook/assets/3 (19).png>)![](<.gitbook/assets/4 (18).png>)

Cavalier ON – Puissance de transmission IR réglée sur High.

Cavalier OFF – Désélectionné.

**REMARQUE IMPORTANTE : les cavaliers JP1 et JP2 NE PEUVENT PAS être réglés sur ON en même temps**

**8. Jeu de commutateurs DIP 1**

Pour régler le type d'appareil

**9. Jeu de commutateurs DIP 2**

Pour apprendre et tester le signal IR

**10. Compartiment à piles**

**11. Support rotatif de montage mural (en option)**

-   Caractéristiques
-   _Détection de batterie et de batterie faible_

La télécommande IR utilise deux piles au lithium de 1,5 V comme source d'alimentation. Il dispose d'une fonction de détection de batterie faible. Lorsqu'une faible tension de batterie est détectée, la télécommande infrarouge transmet le signal de batterie faible au coordinateur du réseau Z-Wave.

La télécommande IR signalera son pourcentage de batterie au panneau de commande respectivement à 100 %, 75 %, 50 % et 25 %. La télécommande IR peut également détecter l'état de la batterie faible. Lorsqu'une faible tension de batterie est détectée (25 %), le signal de batterie faible sera envoyé au panneau de commande avec une transmission régulière du signal pour que le panneau de commande affiche l'état en conséquence.

-   _Ajout d'un appareil (inclusion)_

Ce produit peut être inclus et utilisé dans n'importe quel réseau Z-Wave avec d'autres appareils certifiés Z-Wave d'autres fabricants et/ou d'autres applications. Tous les nœuds non alimentés par batterie du réseau agiront comme répéteurs, quel que soit le fournisseur, afin d'augmenter la fiabilité du réseau.

-   Insérez les piles pour allumer la télécommande IR.
-   Mettez la passerelle Z-Wave ou le panneau de commande dans**Inclusion**ou**Apprentissage**mode (veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
-   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton Fonction/IR.
-   Reportez-vous au manuel d'utilisation de la passerelle Z-Wave ou du panneau de commande pour terminer le processus d'apprentissage.
-   Si le capteur a déjà été**inclus**(appris) dans une autre passerelle/panneau de commande Z-Wave, ou si le capteur ne peut pas être appris dans la passerelle/panneau de commande Z-Wave actuelle, veuillez d'abord l'exclure (voir_**Exclusion**_) avant de tenter de**inclure**dans la passerelle/panneau de configuration Z-Wave actuelle.
-   _Suppression d'un périphérique (exclusion)_

La télécommande IR doit être supprimée du réseau Z-Wave existant avant d'être incluse dans un autre. Il existe deux méthodes disponibles pour exclure un appareil :

**Mode d'exclusion**

-   Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'exclusion**(veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
-   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton Fonction/IR et la télécommande IR sera supprimée du réseau Z-Wave.

**Retour aux paramètres d'usine**

_(Utilisez la réinitialisation d'usine uniquement lorsque le panneau de configuration/passerelle réseau est manquant ou inutilisable)._

-   Appuyez et maintenez enfoncé le bouton Fonction/IR de la télécommande IR pendant 10 secondes pour réinitialiser les paramètres d'usine.

_**\\<NOTE>**_

-   La réinitialisation d'usine de la télécommande infrarouge la restaurera aux paramètres d'usine par défaut (exclue du réseau Z-Wave). La passerelle ou le panneau de commande Z-Wave conservera toujours ses paramètres Z-Wave. Veuillez vous référer au manuel de la passerelle ou du panneau de commande pour savoir comment supprimer les paramètres Z-Wave de la télécommande infrarouge.
-   _Mode veille Z-Wave_
-   La télécommande infrarouge entrera en mode veille Z-Wave (pour économiser l'énergie) après une courte période de réveil (~10 secondes). En mode veille Z-Wave, les passerelles ou panneaux de contrôle Z-Wave ne peuvent pas envoyer de commandes à la télécommande infrarouge.
-   Apprentissage et test du signal IR

Afin d'utiliser la télécommande IR pour contrôler votre appareil électroménager, la télécommande IR doit d'abord apprendre le signal IR envoyé par la télécommande de l'appareil. Suivez les instructions ci-dessous pour terminer le processus d’apprentissage.**Veuillez garder le récepteur IR à l'écart de l'éclairage direct ou de la lumière du soleil pendant le processus d'apprentissage pour éviter les interférences.**

-   _**Apprentissage**_

**Étape 1. Entrez en mode d'apprentissage IR**

1.  Suivez les instructions dans**Configuration du réseau Z-Wave**section pour rejoindre la télécommande IR dans votre réseau Z-Wave.
2.  Assurez-vous que tous les interrupteurs du bloc de commutateurs DIP sont réglés sur**DÉSACTIVÉ**position.
3.  Appuyez et maintenez enfoncé le bouton Fonction/IR pendant 3 secondes et relâchez-le lorsque la LED IR commence à clignoter.
4.  La LED IR commencera à clignoter lentement pour indiquer que la télécommande IR passe maintenant en mode d'apprentissage IR.

SUR

![](<.gitbook/assets/5 (4).jpeg>)

DÉSACTIVÉ

**Étape 2. Sélectionnez le type d'appareil**

L'émetteur IR peut apprendre jusqu'à 5 ensembles de signaux IR pour 5 appareils différents.

Avant de commencer l'apprentissage, sélectionnez le numéro de l'appareil avec le jeu de commutateurs Dip 1 avant de procéder à l'apprentissage des signaux. Le signal IR appris sera attribué au numéro d'appareil sélectionné.

Sélectionnez le type d’appareil selon le tableau suivant du jeu de commutateurs Dip 1. Pour faciliter la reconnaissance et le fonctionnement à partir de la passerelle/panneau de commande Climax Z-Wave, chaque type d'appareil a reçu un nom d'affichage sur l'interface du panneau de commande, nous vous suggérons d'apprendre les signaux IR en fonction des types d'appareils affichés.

| Commutateur 1 | Commutateur 2 | Commutateur 3 | Commutateur 4 | Commutateur 5 | Commutateur 6 | Type d'appareil               |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ----------------------------- |
| SUR           | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | **Type 1 (climatiseur)**      |
| X             | SUR           | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | **Type 2 (Télévision)**       |
| X             | X             | SUR           | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | **Type 3 (audio domestique)** |
| X             | X             | X             | SUR           | DÉSACTIVÉ     | DÉSACTIVÉ     | **Type 4 (décodeur)**         |
| X             | X             | X             | X             | SUR           | DÉSACTIVÉ     | **Type 5 (Autres)**           |

« X » signifie que l'emplacement de cet interrupteur n'a aucun effet sur la sélection de l'appareil.

**Exemple:**

1.  Pour sélectionner le climatiseur, faites glisser l'interrupteur 1 sur ON et l'interrupteur 2-6 sur OFF.
2.  Pour sélectionner Télévision, faites glisser le commutateur 2 sur ON et le commutateur 3-6 sur OFF, ignorez la position du commutateur 1.

**Étape 3. Apprenez les données IR**

Chaque type d'appareil peut apprendre jusqu'à 8 signaux IR, sélectionnés avec le jeu de commutateurs Dip 2.

| Commutateur 1 | Commutateur 2 | Commutateur 3 | Commutateur 4 | Commutateur 5 | Commutateur 6 | Commutateur 7 | Commutateur 8 | Signal infrarouge |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ----------------- |
| SUR           | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | **1**             |
| X             | SUR           | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | **2**             |
| X             | X             | SUR           | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | **3**             |
| X             | X             | X             | SUR           | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | **4**             |
| X             | X             | X             | X             | SUR           | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | **5**             |
| X             | X             | X             | X             | X             | SUR           | DÉSACTIVÉ     | DÉSACTIVÉ     | **6**             |
| X             | X             | X             | X             | X             | X             | SUR           | DÉSACTIVÉ     | **7**             |
| X             | X             | X             | X             | X             | X             | X             | SUR           | **8**             |

**Exemple:**

1.  Pour sélectionner le signal IR 1, faites glisser le commutateur 1 sur ON et le commutateur 2-8 sur OFF.
2.  Pour sélectionner le signal IR 2, faites glisser le commutateur 2 sur ON et le commutateur 3-8 sur OFF, ignorez la position du commutateur 1.
3.  Sélectionnez le signal IR souhaité en ajustant le commutateur DIP. Nous vous suggérons de commencer par le signal IR 1 en faisant glisser l'interrupteur 1 sur la position ON pour sélectionner le signal IR 1.
4.  Pointez la télécommande IR de votre appareil dans la direction opposée au récepteur IR pour empêcher le récepteur IR de recevoir un signal IR indésirable.
5.  Ajustez la télécommande IR au réglage souhaité, puis pointez la télécommande vers le récepteur IR, puis appuyez sur le bouton de la télécommande pour transmettre le signal IR.

**Exemple:**

1.  Pour la télécommande du climatiseur, si vous réglez la télécommande sur « Mode refroidissement, 18 °C, vitesse du ventilateur automatique » et que vous éteignez la télécommande, pointez la télécommande vers le récepteur IR et appuyez sur « ON ».

Le récepteur IR apprendra le signal « Mode Cool, 18°C, Vitesse du ventilateur Auto » pour le climatiseur.

1.  Pour la télécommande du téléviseur, si vous pointez la télécommande vers le récepteur IR et appuyez sur ON/Off.

Le récepteur IR apprendra le signal ON/OFF pour le téléviseur.

1.  Si le signal est reçu avec succès, la LED IR clignote rapidement, puis s'éteint pour indiquer que la télécommande IR stocke les données du signal IR, puis clignote à nouveau lentement. Si vous avez accidentellement envoyé le mauvais signal IR, éloignez la télécommande pour ajuster le réglage, pointez-la vers le récepteur IR pour retransmettre le signal. Le nouveau signal IR écrasera l'ancien.
2.  Une fois l'apprentissage terminé, modifiez le réglage du commutateur DIP pour apprendre un autre signal IR, répétez la procédure de 2 à 4. Nous vous suggérons de passer du signal IR 1 à 8 en faisant glisser les commutateurs DIP 1 à 8 en position ON un par un.
3.  Répétez le processus pour apprendre un maximum de 8 signaux pour chaque type d'appareil.
4.  Vous pouvez ajuster le paramètre Dip Switch set 2 pour sélectionner un autre type d’appareil.

**Étape 4. Quitter le mode d'apprentissage IR**

1.  Après avoir fini d'apprendre tous les signaux IR, appuyez une fois sur le bouton Fonction/IR pour quitter le mode d'apprentissage, puis faites glisser tous les interrupteurs en position OFF.

-   _**Essai**_

Après avoir terminé l'apprentissage des signaux IR, suivez les instructions ci-dessous pour tester la transmission des signaux IR.

1.  N'entrez pas en mode d'apprentissage IR, ajustez le paramètre du commutateur Dip en conséquence pour sélectionner le type d'appareil et le numéro de signal IR comme précédemment appris.
2.  Appuyez une fois sur le bouton Fonction/IR, la LED IR clignotera rapidement pour indiquer qu'elle transmet un signal. Si aucun signal n’est appris, la télécommande IR n’enverra aucun signal et la LED IR restera éteinte.
3.  Répétez la procédure de 1 à 2 pour tester tous les signaux IR appris.
4.  Après avoir terminé tous les réglages, faites glisser tous les interrupteurs en position OFF.

-   _**Effacement des données IR**_

Pour supprimer tous les signaux IR appris pour un type d'appareil, suivez les instructions ci-dessous :

1.  Piles à distance pour éteindre la télécommande IR.
2.  Sélectionnez le type d'appareil que vous souhaitez supprimer à l'aide du jeu de commutateurs Dip 1 selon le tableau suivant.

| Commutateur 1 | Commutateur 2 | Commutateur 3 | Commutateur 4 | Commutateur 5 | Commutateur 6 | Sélection d'appareils         |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ----------------------------- |
| SUR           | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | **Type 1 (climatiseur)**      |
| DÉSACTIVÉ     | SUR           | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | **Type 2 (Télévision)**       |
| DÉSACTIVÉ     | DÉSACTIVÉ     | SUR           | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | **Type 3 (audio domestique)** |
| DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | SUR           | DÉSACTIVÉ     | DÉSACTIVÉ     | **Type 4 (décodeur)**         |
| DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | SUR           | DÉSACTIVÉ     | **Type 5 (Autres)**           |

Faites glisser plusieurs interrupteurs sur ON pour sélectionner plusieurs types d'appareils,

**Exemple:**

1.  Faites glisser l'interrupteur 1,2,3,4,5 sur ON pour sélectionner les 5 types d'appareils.
2.  Faites glisser les interrupteurs 1 et 3 sur ON pour sélectionner Climatiseur et Home Audio.
3.  Appuyez et maintenez enfoncé le bouton Fonction/IR et insérez les piles pour alimenter l'émetteur IR, ne relâchez pas encore le bouton.
4.  Maintenez les deux boutons Fonction/IR enfoncés jusqu'à ce que la LED IR s'allume, puis relâchez le bouton.
5.  L'émetteur IR effacera le signal IR stocké pour les types d'appareils sélectionnés, la LED IR clignotera en continu.
6.  Faites glisser tous les interrupteurs en position OFF pour revenir au fonctionnement normal. La LED IR s'éteindra.

-   Installation

La télécommande IR est conçue pour être montée au mur. Il peut être monté soit en vissant directement le couvercle arrière sur le mur, soit en installant d'abord le support rotatif, puis en installant le corps principal sur le support. Veuillez vous référer au**Couverture du signal IR et sélection des LED IR**section ci-dessous pour plus d’informations sur la transmission du signal IR avant de sélectionner l’emplacement de montage de la télécommande IR.

-   _Montage de la télécommande IR_

![](<.gitbook/assets/6 (7).jpeg>)

La télécommande IR est conçue pour être montée au mur. Il peut être monté soit en vissant directement le couvercle arrière sur le mur, soit en installant d'abord le support rotatif, puis en installant le corps principal sur le support. L'IR Eye doit être pointé vers l'appareil électroménager que vous souhaitez contrôler lorsque la télécommande IR est installée.

**REMARQUE : Le support rotatif n’est pas inclus dans la livraison standard et est disponible sur demande.**

-   Montage mural direct :

La coque arrière comporte 4 découpes, là où le plastique est plus fin, à des fins de montage.

1.  Ouvrez le couvercle et percez les 4 découpes sur le couvercle arrière.
2.  Utilisez les trous comme gabarit pour percer des trous dans le mur, insérez des chevilles murales si nécessaire.
3.  Vissez le couvercle arrière sur le mur.
4.  Remettez le capot avant sur le capot arrière.

-   Montage sur support rotatif.

Le support rotatif possède une tête réglable qui peut être fixée à la télécommande IR. Après avoir installé le support sur le mur, l'utilisateur peut régler l'angle de la tête pour changer la direction vers laquelle la télécommande IR est orientée.

1.  La base du support rotatif dispose de 2 trous de montage. Utilisez les trous comme gabarit pour percer des trous dans le mur, insérez des chevilles murales si nécessaire.
2.  Vissez le support au mur.
3.  Accrochez la télécommande IR aux supports en utilisant les trous à l'arrière.
4.  Une fois l'installation terminée, vous pouvez utiliser un tournevis Philip pour desserrer la vis située sur le dessus du support, puis ajuster l'angle de l'émetteur IR et serrer la vis pour verrouiller l'angle du support.

![](<.gitbook/assets/7 (6).jpeg>)

-   Opération
-   _Contrôle via la passerelle Z-Wave/panneau de commande_

La télécommande IR peut être contrôlée à distance via la passerelle/panneaux de commande Climax Z-Wave pour transmettre le signal IR. La sélection du type d'appareil et du numéro de signal IR à partir du panneau de commande permettra à la télécommande IR d'envoyer le signal IR en conséquence.

**Exemple:**

1.  Sélectionnez «Fonction de climatiseur 1» pour contrôler la télécommande IR pour envoyer le signal IR 1 appris dans le type d'appareil de climatiseur.

-   _Couverture du signal IR et sélection des LED IR_

![](<.gitbook/assets/8 (3).jpeg>)

L'œil IR de la télécommande IR comprend 6 LED utilisées pour transmettre des signaux IR, avec 1 LED centrale et 5 LED environnantes. Les 5 LED environnantes sont positionnées à un angle de 45° par rapport à la carte PCB.**Couverture du signal LED :**

Chaque LED transmet un signal IR dans une couverture conique devant la LED. La LED centrale est toujours utilisée à chaque transmission. 1 des 5 LED environnantes peut également être sélectionnée pour transmettre le signal pour chaque type d'appareil en utilisant la passerelle/panneau de commande Climax Z-Wave.

**Exemple:**

1.  Si vous sélectionnez la LED 1 pour le climatiseur, la télécommande IR transmettra un signal avec la LED centrale et la LED 1 lorsqu'elle transmettra un signal IR de type appareil de climatiseur.
2.  Si vous sélectionnez LED 3 pour Home Audio, la télécommande IR transmettra un signal avec la LED centrale et la LED 3 lorsqu'elle transmettra un signal IR de type appareil Home Audio.

Lors de l'installation de la télécommande IR, sélectionnez la LED IR utilisée via votre panneau de commande en fonction de l'emplacement de montage de la télécommande IR pour permettre à l'émetteur IR d'envoyer un signal à tous les appareils de votre maison. Veuillez vous référer au manuel de votre passerelle/panneau de commande Climax pour plus d'informations sur le réglage et le contrôle de la télécommande infrarouge.

Veuillez vous référer au schéma ci-dessous pour connaître la couverture du signal IR :

![](<.gitbook/assets/9 (1).jpeg>)

-   _Puissance de transmission infrarouge_

Utilisez les cavaliers (JP2 et JP3) pour régler la puissance de transmission du signal IR. La valeur par défaut est réglée sur Faible puissance de transmission (JP1 ON). Le réglage du cavalier sur JP2 augmentera la portée de transmission du signal IR.

-   _Commande de réglage de contrôle AV simple_

La simple commande AV control set est utilisée pour contrôler un périphérique AV via le panneau de configuration :

Classe de commande : COMMANDE_CLASSE_SIMPLE_DE_CONTRÔLE_V1

Commande : SIMPLE_DE_CONTRÔLE_ENSEMBLE

Définissez les valeurs :

ID d'article MSB : pour le type d'appareil, 01~05

ID d'article LSB : pour les données de signal IR, 01~08

![](<.gitbook/assets/10 (2).png>)

**Informations sur la vague Z**

**Type d'appareil:**Compteur d'énergie secondaire

**Type de rôle :**Signalement de l'esclave endormi (RSS)

**Prise en charge/contrôle de classe de commande**

**Mandatory CC Support:**Association CC, v2

Informations sur le groupe d'association CC

Batterie CC

Réinitialisation de l'appareil localement CC

CC spécifique au fabricant, v2

Configuration CC,

Contrôle AV simple CC,

VersionCC, v2

Z-Wave Plus Info CC, v2

Niveau de puissance CC

Mise à jour du micrologiciel CC, v2

-   _**Groupes de Z-Wave (classe de commande d'association version 2)**_

Groupe 1 pour « LifeLine » :

Batterie CC (COMMANDE_CLASSE_BASIQUE)

Réinitialisation de l'appareil localement CC
