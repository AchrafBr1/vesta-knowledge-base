# VESTA 188

**Télécommande universelle infrarouge UPIC-5ZBS**

**Introduction**

UPIC5-ZBS est une télécommande infrarouge ZigBee. Il est conçu pour faire fonctionner vos appareils électroménagers en transmettant un signal IR. La télécommande IR est capable d'apprendre le signal IR transmis par la télécommande de l'appareil. Après avoir appris le signal, vous pouvez contrôler à distance la télécommande infrarouge via le réseau ZigBee pour envoyer le signal à l'appareil sans utiliser la télécommande manuellement et prendre en charge la capacité de mise à jour du micrologiciel Over-the-Air (OTA). La télécommande IR utilise la technologie ZigBee pour la transmission du signal sans fil. ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

La télécommande IR sert de périphérique final dans le réseau ZigBee. Il peut être inclus dans le réseau ZigBee pour transmettre un signal lors de l'activation, mais ne peut permettre à aucun autre appareil ZigBee de rejoindre le réseau via l'appareil lui-même.

**Identification des pièces**

![](<.gitbook/assets/0 (76).jpeg>)

1.  **Oeil IR**

Transmet le signal IR aux appareils.

1.  **Bouton ZigBee**
2.  **Bouton IR**
3.  **ZigBeeLED**

Clignote deux fois – La télécommande IR rejoint avec succès le réseau ZigBee Clignote toutes les 20 minutes – La télécommande IR a perdu la connexion à son réseau ZigBee actuel.

1.  **Indicateur LED IR**

Flash lent – ​​Télécommande IR en mode d'apprentissage IR.

Flash rapide – La télécommande IR reçoit un signal IR en mode d'apprentissage ou transmet un signal IR

Flash toutes les demi-secondes – données IR effacées

Éteint – La télécommande IR stocke le signal IR reçu en mode d'apprentissage.

– La télécommande IR est en mode veille.

1.  **Récepteur de signaux infrarouges**
2.  **Cavalier de puissance de transmission IR faible (JP1)**

![](<.gitbook/assets/1 (57).png>)

**Cavalier****Cavalier**

![](<.gitbook/assets/2 (61).jpeg>)![](<.gitbook/assets/3 (54).jpeg>)

Le cavalier est inséré reliant les deux broches

si le cavalier est retiré ou "**garé**» sur une épingle.

Cavalier ON – Puissance de transmission IR réglée sur Faible.**(Défaut de fabrication)**Cavalier OFF – Désélectionné.

**8. Cavalier de puissance de transmission IR élevé (JP2)**

![](<.gitbook/assets/4 (52).jpeg>)

**Cavalier****Cavalier**

![](<.gitbook/assets/5 (63).png>)

Le cavalier est inséré reliant les deux broches

si le cavalier est retiré ou "**garé**» sur une épingle.

Cavalier ON – Puissance de transmission IR réglée sur High.

Cavalier OFF – Désélectionné.

**REMARQUE IMPORTANTE : les cavaliers JP1 et JP2 NE PEUVENT PAS être réglés sur ON en même temps**

1.  **Ensemble de commutateurs DIP 1**

Pour régler le type d'appareil

1.  **Ensemble de commutateurs DIP 2**

Pour apprendre et tester le signal IR

1.  **Compartiment à piles**
2.  **Support rotatif de montage mural (en option)**

1

**Caractéristiques**

-   _**Détection de batterie et de batterie faible**_

La télécommande IR utilise deux piles au lithium de 1,5 V comme source d'alimentation. Il dispose d'une fonction de détection de batterie faible. Lorsqu'une faible tension de batterie est détectée, la télécommande infrarouge transmet le signal de batterie faible au coordinateur du réseau ZigBee.

-   _**Surveillance**_

La télécommande IR transmettra un signal de supervision pour signaler régulièrement son état en fonction des paramètres de l'utilisateur. L'intervalle par défaut est de 30 minutes. L'utilisateur peut également appuyer une fois sur le bouton ZigBee pour transmettre manuellement un signal de supervision.

**Configuration du réseau ZigBee**

-   _**Directives relatives aux appareils ZigBee**_

La télécommande IR est un protocole de communication sans fil fiable, à faible consommation d'énergie et à efficacité de transmission élevée. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

En raison de la structure fondamentale du réseau ZigBee, l'appareil ZigBee recherchera et rejoindra activement le réseau après la mise sous tension. Étant donné que l'exécution d'une tâche de connexion au réseau peut consommer de l'énergie, il est nécessaire de suivre les instructions pour éviter de vider la batterie d'un appareil ZigBee.

-   Assurez-vous que le routeur/coordinateur réseau ZigBee est allumé avant d'insérer la batterie dans l'appareil ZigBee.
-   Assurez-vous que le routeur/coordinateur réseau ZigBee est allumé et à portée pendant que l'appareil ZigBee est utilisé.

\-Ne retirez pas un appareil ZigBee du routeur ou du coordinateur réseau ZigBee sans retirer la batterie d'un appareil ZigBee.

-   _**Rejoindre le réseau ZigBee**_

En tant qu'appareil ZigBee, la télécommande IR doit rejoindre un réseau ZigBee pour recevoir la commande du coordinateur du réseau ZigBee afin de transmettre le signal IR. Veuillez suivre les étapes ci-dessous pour connecter la télécommande IR au réseau ZigBee.

-   1.  Insérez les piles pour allumer la télécommande IR.
    2.  **P.**Appuyez et maintenez enfoncé le bouton ZigBee pendant 10 secondes, puis relâchez-le pour rejoindre le réseau. Veuillez vous assurer que la fonction d'autorisation de connexion sur le routeur ou le coordinateur de votre réseau ZigBee est activée.
    3.  Après avoir rejoint le réseau ZigBee, la télécommande IR sera automatiquement enregistrée dans le système de sécurité du réseau. Veuillez vérifier le panneau de contrôle du système de sécurité ou le CIE (équipement de contrôle et d'indication) pour confirmer si l'adhésion et l'enregistrement ont réussi.
    4.  Si la télécommande infrarouge rejoint avec succès le réseau ZigBee, la LED ZigBee clignote deux fois pour l'indiquer.
    5.  Après avoir rejoint le réseau ZigBee, si la télécommande infrarouge perd la connexion au réseau ZigBee actuel, l'indicateur LED ZigBee clignote toutes les 20 minutes. Veuillez vérifier l'état du réseau ZigBee et la plage du signal de la télécommande IR pour corriger la situation.
-   _**Suppression d'un appareil du réseau ZigBee (réinitialisation d'usine)**_

Pour supprimer l'appareil du réseau ZigBee actuel, la télécommande infrarouge doit être réglée sur la réinitialisation d'usine pour terminer la suppression de l'appareil. La fonction de réinitialisation d'usine effacera la télécommande infrarouge de ses informations de configuration stockées et invitera l'appareil à rechercher un nouveau réseau ZigBee.

**Avant de retirer l'appareil, assurez-vous qu'il se trouve dans la plage actuelle du signal réseau ZigBee.**

-   1.  Supprimez la télécommande IR du panneau de commande actuel / CIE.
    2.  Appuyez et maintenez le bouton de fonction pendant 10 secondes, puis relâchez le bouton pour réinitialiser l'appareil.
    3.  Lors de la réinitialisation, la télécommande infrarouge effacera les paramètres réseau ZigBee actuels et transmettra le signal au coordinateur ZigBee pour se retirer du réseau ZigBee actuel. Il recherchera ensuite à nouveau activement le réseau ZigBee disponible et rejoindra automatiquement le réseau.
-   _**Mise à niveau du micrologiciel OTA**_
-   L'appareil prend en charge la fonction de mise à niveau du micrologiciel OTA via le réseau ZigBee, qui peut être lancée à partir du coordinateur du réseau ZigBee.
-   Suivez les étapes ci-dessous pour effectuer la mise à niveau du micrologiciel OTA.

1.  Vous devez accéder à votre coordinateur ZigBee pour effectuer la mise à niveau du micrologiciel en direct.
2.  Sur la page Web de configuration, sélectionnez l'appareil que vous souhaitez mettre à niveau et sélectionnez le nouveau firmware ZigBee fourni. Veuillez vous référer au manuel d'utilisation du coordinateur ZigBee pour plus de détails.
3.  Appuyez sur OK pour démarrer le processus de mise à niveau. N'effectuez aucune autre action et n'éteignez pas le panneau.
4.  La durée d'une mise à niveau prendra environ 20 à 30 minutes. Veuillez noter que la durée peut varier en fonction de la taille du fichier ou de la distance entre votre accessoire et le coordinateur.
5.  Attendez que le micrologiciel termine la mise à jour. Lorsque la progression atteint 100 %, l'appareil se réinitialise automatiquement. Vous pouvez également actualiser à nouveau la page Web pour vous assurer que le micrologiciel de l'appareil est correctement mis à jour avec la version la plus récente affichée.

2

**Apprentissage et test du signal IR**

Afin d'utiliser la télécommande IR pour contrôler votre appareil électroménager, la télécommande IR doit d'abord apprendre le signal IR envoyé par la télécommande de l'appareil. Suivez les instructions ci-dessous pour terminer le processus d’apprentissage.

**Veuillez garder le récepteur IR à l'écart de l'éclairage direct ou de la lumière du soleil pendant le processus d'apprentissage pour éviter les interférences.**

-   _**Apprentissage**_

**Étape 1. Entrez en mode d'apprentissage IR**

1.  Suivez les instructions dans**Configuration du réseau ZigBee**pour rejoindre la télécommande IR dans votre réseau ZigBee.
2.  Assurez-vous que tous les interrupteurs du bloc de commutateurs DIP sont réglés sur**DÉSACTIVÉ**position.
3.  Appuyez et maintenez le bouton IR pendant 10 secondes et relâchez-le lorsque la LED IR commence à clignoter.
4.  La LED IR commencera à clignoter lentement pour indiquer que la télécommande IR est

![](<.gitbook/assets/6 (44).png>)

| nous passons maintenant en mode d'apprentissage IR. | SUR       |   |
| --------------------------------------------------- | --------- | - |
| **Étape 2. Sélectionnez le type d'appareil**        | DÉSACTIVÉ |   |
|                                                     |           |   |

L'émetteur IR peut apprendre jusqu'à 5 ensembles de signaux IR pour 5 appareils différents.

Avant de commencer l'apprentissage, sélectionnez le numéro de l'appareil avec le jeu de commutateurs Dip 1 avant de procéder à l'apprentissage des signaux. Le signal IR appris sera attribué au numéro d'appareil sélectionné.

Sélectionnez le type d’appareil selon le tableau suivant du jeu de commutateurs Dip 1. Pour faciliter la reconnaissance et le fonctionnement à partir du panneau de commande Climax ZigBee, chaque type d'appareil a reçu un nom d'affichage sur l'interface du panneau de commande, nous vous suggérons d'apprendre les signaux IR en fonction des types d'appareils affichés.

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

-   1.  Pour sélectionner le signal IR 1, faites glisser le commutateur 1 sur ON et le commutateur 2-8 sur OFF.
    2.  Pour sélectionner le signal IR 2, faites glisser le commutateur 2 sur ON et le commutateur 3-8 sur OFF, ignorez la position du commutateur 1.

1.  Sélectionnez le signal IR souhaité en ajustant le commutateur DIP. Nous vous suggérons de commencer à partir du signal IR 1 en faisant glisser l'interrupteur 1 sur la position ON pour sélectionner le signal IR 1.
2.  Pointez la télécommande IR de votre appareil dans la direction opposée au récepteur IR pour empêcher l'IR

Le récepteur ne reçoit pas de signal IR indésirable.

1.  Ajustez la télécommande IR au réglage souhaité, puis pointez la télécommande vers le récepteur IR, puis appuyez sur le bouton de la télécommande pour transmettre le signal IR.

**Exemple:**

-   1.  Pour la télécommande du climatiseur, si vous réglez la télécommande sur « Mode refroidissement, 18 °C, vitesse du ventilateur automatique » et que vous éteignez la télécommande, pointez la télécommande vers le récepteur IR et appuyez sur « ON ».

Le récepteur IR apprendra le signal « Mode froid, 18 °C, vitesse du ventilateur automatique » pour le climatiseur.

-   1.  Pour la télécommande du téléviseur, si vous pointez la télécommande vers le récepteur IR et appuyez sur ON/Off. Le récepteur IR apprendra le signal ON/OFF pour le téléviseur.

1.  Si le signal est reçu avec succès, la LED IR clignote rapidement, puis s'éteint pour indiquer que la télécommande IR stocke les données du signal IR, puis clignote à nouveau lentement. Si vous avez accidentellement envoyé le mauvais signal IR, éloignez la télécommande pour ajuster le réglage, pointez-la vers le récepteur IR pour retransmettre le signal. Le nouveau signal IR écrasera l'ancien.
2.  Une fois l'apprentissage terminé, modifiez le réglage du commutateur DIP pour apprendre un autre signal IR, répétez la procédure de 2 à 4. Nous vous suggérons de passer du signal IR 1 à 8 en faisant glisser les commutateurs DIP 1 à 8 en position ON un par un.
3.  Répétez le processus pour apprendre un maximum de 8 signaux pour chaque type d'appareil.

3

-   1.  Vous pouvez ajuster le paramètre Dip Switch set 2 pour sélectionner un autre type d’appareil.

**Étape 4. Quitter le mode d'apprentissage IR**

-   1.  Après avoir fini d'apprendre tous les signaux IR, appuyez une fois sur le bouton IR pour quitter le mode d'apprentissage, puis faites glisser tous les interrupteurs en position OFF.
-   _**Essai**_

Après avoir terminé l'apprentissage des signaux IR, suivez les instructions ci-dessous pour tester la transmission des signaux IR.

-   1.  N'entrez pas en mode d'apprentissage IR, ajustez le paramètre du commutateur Dip en conséquence pour sélectionner le type d'appareil et le numéro de signal IR comme précédemment appris.
    2.  Appuyez une fois sur le bouton IR, la LED IR clignotera rapidement pour indiquer qu'elle transmet le signal. Si aucun signal n’est appris, la télécommande IR n’enverra aucun signal et la LED IR restera éteinte.
    3.  Répétez la procédure de 1 à 2 pour tester tous les signaux IR appris.
    4.  Après avoir terminé tous les réglages, faites glisser tous les interrupteurs en position OFF.
-   _**Effacement des données IR**_

Pour supprimer tous les signaux IR appris pour un type d'appareil, suivez les instructions ci-dessous :

1.  Retirez les piles pour éteindre la télécommande infrarouge.
2.  Sélectionnez le type d'appareil que vous souhaitez supprimer à l'aide du jeu de commutateurs Dip 1 selon le tableau suivant.

| Commutateur 1 | Commutateur 2 | Commutateur 3 | Commutateur 4 | Commutateur 5 | Commutateur 6 | Sélection d'appareils    |                          |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------------------ | ------------------------ |
| SUR           | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | **Type 1 (climatiseur)** |                          |
| DÉSACTIVÉ     | SUR           | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | **Type 2**               | **(Télévision)**         |
| DÉSACTIVÉ     | DÉSACTIVÉ     | SUR           | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | **Tapez 3**              | **(Audio domestique)**   |
| DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | SUR           | DÉSACTIVÉ     | DÉSACTIVÉ     | **Tapez 4**              | **(Décodeur numérique)** |
| DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | DÉSACTIVÉ     | SUR           | DÉSACTIVÉ     | **Tapez 5**              | **(Autres)**             |

Faites glisser plusieurs interrupteurs sur ON pour sélectionner plusieurs types d'appareils,

**Exemple:**

-   1.  Faites glisser l'interrupteur 1,2,3,4,5 sur ON pour sélectionner les 5 types d'appareils.
    2.  Faites glisser les interrupteurs 1 et 3 sur ON pour sélectionner Climatiseur et Home Audio.

1.  Appuyez et maintenez les boutons IR et ZigBee et insérez les piles pour alimenter l'émetteur IR, ne relâchez pas encore les boutons.
2.  Maintenez les boutons IR et ZigBee enfoncés jusqu'à ce que la LED IR s'allume, puis relâchez les boutons.
3.  L'émetteur IR effacera le signal IR stocké pour les types d'appareils sélectionnés, la LED IR clignotera en continu.
4.  Faites glisser tous les interrupteurs en position OFF pour revenir au fonctionnement normal. La LED IR s'éteindra.

**Installation**

La télécommande IR est conçue pour être montée au mur. Il peut être monté soit en vissant directement le couvercle arrière sur le mur, soit en installant d'abord le support rotatif, puis en installant le corps principal sur le support. Veuillez vous référer au**Couverture du signal IR et sélection des LED IR**section ci-dessous pour plus d’informations sur la transmission du signal IR avant de sélectionner l’emplacement de montage de la télécommande IR.

-   _**Montage de la télécommande IR**_

![](<.gitbook/assets/7 (40).jpeg>)

La télécommande IR est conçue pour être montée au mur. Il peut être monté soit en vissant directement le couvercle arrière sur le mur, soit en installant d'abord le support rotatif, puis en installant le corps principal sur le support. L'IR Eye doit être pointé vers l'appareil électroménager que vous souhaitez contrôler lorsque la télécommande IR est installée.

**REMARQUE : Le support rotatif n’est pas inclus dans la livraison standard et est disponible sur demande.**

-   Montage mural direct :

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

4

![](<.gitbook/assets/8 (35).jpeg>)

**Opération**

-   _**Contrôle via le panneau de configuration ZigBee**_

La télécommande IR peut être contrôlée à distance via les panneaux de commande Climax ZigBee pour transmettre le signal IR. La sélection du type d'appareil et du numéro de signal IR à partir du panneau de commande permettra à la télécommande IR d'envoyer le signal IR en conséquence.

**Exemple:**

-   1.  Sélectionnez «Fonction de climatiseur 1» pour contrôler la télécommande IR pour envoyer le signal IR 1 appris dans l'air

Type d'appareil de conditionnement.

-   _**Couverture du signal IR et sélection des LED IR**_

![](<.gitbook/assets/9 (27).jpeg>)

L'œil IR de la télécommande IR comprend 6 LED utilisées pour transmettre des signaux IR, avec 1 LED centrale et 5 LED environnantes. Les 5 LED environnantes sont positionnées à un angle de 45° par rapport à la carte PCB.**Couverture du signal LED :**

Chaque LED transmet un signal IR dans une couverture conique devant la LED. Les LED peuvent être sélectionnées pour transmettre le signal pour chaque type d'appareil en utilisant votre passerelle.

**Exemple:**

un. Si vous sélectionnez la LED 1 pour le climatiseur, la télécommande IR transmettra le signal avec la LED 1 lorsqu'elle transmettra un signal IR de type appareil de climatisation.

1.  Si vous sélectionnez LED 2 et LED 3 pour Home Audio, la télécommande IR transmettra un signal avec LED 2 et LED 3 lorsqu'elle transmettra un signal IR de type appareil Home Audio.

Lors de l'installation de la télécommande IR, sélectionnez la LED IR utilisée via votre panneau de commande en fonction de l'emplacement de montage de la télécommande IR pour permettre à l'émetteur IR d'envoyer un signal à tous les appareils de votre maison. Veuillez vous référer au manuel de votre panneau de commande Climax pour plus d'informations sur le réglage et le contrôle de la télécommande IR.

Veuillez vous référer au schéma ci-dessous pour connaître la couverture du signal IR :

5

![](<.gitbook/assets/10 (20).jpeg>)

-   _**Puissance de transmission infrarouge**_

Utilisez les cavaliers (JP2 et JP3) pour régler la puissance de transmission du signal IR. La valeur par défaut est réglée sur Faible puissance de transmission (JP1 ON). Le réglage du cavalier sur JP2 augmentera la portée de transmission du signal IR.

6

**Annexe (Pour les développeurs uniquement)**

_**ID de cluster UPIC**_

**ID de l'appareil : UPIC 0x0307 (propriétaire)**

**Point de terminaison : 0x01**

| **Du côté serveur** |                 | **Côté client** |
| ------------------- | --------------- | --------------- |
|                     |                 |                 |
|                     | **Obligatoire** |                 |

De base (0x0000)

Alimentation CFG (0x0001)

Identifier (0x0003)

Thermostat CVC (0x0201)

Identifier (0x0003)

**Facultatif**

_Aucun_

_Aucun_

-   _**Attribut des informations de base sur le cluster**_

| **Identifier**   | **Nom**                  | **Taper**        | **Gamme**     | **Accéder** | **Défaut**       | **Obligatoire** |   |
| ---------------- | ------------------------ | ---------------- | ------------- | ----------- | ---------------- | --------------- | - |
| **/ Facultatif** |                          |                  |               |             |                  |                 |   |
|                  |                          |                  |               |             |                  |                 |   |
| 0x0000           | _Version ZCL_            | 8 bits non signé | 0x00 –0xff    | Lire        | 0x01             | M.              |   |
| entier           | seulement                |                  |               |             |                  |                 |   |
|                  |                          |                  |               |             |                  |                 |   |
| 0x0001           | Version de l'application | 8 bits non signé | 0x00 –0xff    | Lire        | 0x00             | Ô               |   |
| entier           | seulement                |                  |               |             |                  |                 |   |
|                  |                          |                  |               |             |                  |                 |   |
| 0x0003           | _Version matérielle_     | 8 bits non signé | 0x00 –0xff    | Lire        | 0                | Ô               |   |
| entier           | seulement                |                  |               |             |                  |                 |   |
|                  |                          |                  |               |             |                  |                 |   |
| 0x0004           | _Nom du Fabricant_       | Personnage       | 0 – 32 octets | Lire        | Climax           | Ô               |   |
| Chaîne           | seulement                | Technologie      |               |             |                  |                 |   |
|                  |                          |                  |               |             |                  |                 |   |
| 0x0005           | _Identifiant du modèle_  | Personnage       | 0 – 32 octets | Lire        | (Version modèle) | Ô               |   |
| Chaîne           | seulement                |                  |               |             |                  |                 |   |
|                  |                          |                  |               |             |                  |                 |   |
| 0x0006           | _CodeDate_               | Personnage       | 0 – 16 octets | Lire        |                  | Ô               |   |
| Chaîne           | seulement                |                  |               |             |                  |                 |   |
|                  |                          |                  |               |             |                  |                 |   |
| 0x0007           | _Source d'énergie_       | 8 bits           | 0x00 –0xff    | Lire        |                  | M.              |   |
| seulement        |                          |                  |               |             |                  |                 |   |
|                  |                          |                  |               |             |                  |                 |   |
| 0x0010           | _EmplacementDescription_ | Personnage       | 0 – 32 octets | Lire /      |                  | Ô               |   |
| Chaîne           | Écrire                   |                  |               |             |                  |                 |   |
|                  |                          |                  |               |             |                  |                 |   |
| 0x0011           | _Environnement physique_ | 8 bits           | 0x00 –0xff    | Lire /      | 0x00             | Ô               |   |
| Écrire           |                          |                  |               |             |                  |                 |   |
|                  |                          |                  |               |             |                  |                 |   |
| 0x0012           | _Appareil activé_        | Booléen          | 0x00 –0x01    | Lire /      | 0x01             | M.              |   |
| Écrire           |                          |                  |               |             |                  |                 |   |
|                  |                          |                  |               |             |                  |                 |   |

_**Attribut des informations sur le cluster Power CFG**_

| **Identifier**   | **Nom**                         | **Taper**          | **Gamme** | **Accéder**       | **Défaut** | **Obligatoire** |   |
| ---------------- | ------------------------------- | ------------------ | --------- | ----------------- | ---------- | --------------- | - |
| **/ Facultatif** |                                 |                    |           |                   |            |                 |   |
|                  |                                 |                    |           |                   |            |                 |   |
| 0x0035           | _MASQUE D'ALARME CHAUVE-SOURIS_ | Énumération 8 bits | Tous      | Lecture seulement | 0x00       | M.              |   |

_**Attribut des informations d'identification du cluster**_

| **Identifier**   | **Nom**              | **Taper**         | **Gamme**    | **Accéder** | **Défaut** | **Obligatoire** |   |
| ---------------- | -------------------- | ----------------- | ------------ | ----------- | ---------- | --------------- | - |
| **/ Facultatif** |                      |                   |              |             |            |                 |   |
|                  |                      |                   |              |             |            |                 |   |
| 0x0000           | _Identifier l'heure_ | 16 bits non signé | 0x00 –0xffff | Lire écrire | 0x0000     | M.              |   |
| entier           |                      |                   |              |             |            |                 |   |
|                  |                      |                   |              |             |            |                 |   |

_**Attribut des informations sur le cluster de thermostats**_

| **Identifier**   | **Nom**                   | **Taper** | **Gamme**      | **Accéder** | **Défaut**   | **Obligatoire** |   |
| ---------------- | ------------------------- | --------- | -------------- | ----------- | ------------ | --------------- | - |
| **/ Facultatif** |                           |           |                |             |              |                 |   |
|                  |                           |           |                |             |              |                 |   |
| 0x001C           | _Mode système_            | 8 bits    | Tous           | Lire écrire | 0x04         | M.              |   |
| Énumération      |                           |           |                |             |              |                 |   |
|                  |                           |           |                |             |              |                 |   |
| 0x1011           | _Sélectionnez envoyer IR_ | UINT 40   | 0CSAAFFFFFFFF- | Lire écrire | 0x2020202020 | Ô               |   |
| _DIRIGÉ_         | 0x0101010101              |           |                |             |              |                 |   |
|                  |                           |           |                |             |              |                 |   |

**Mode système (0x001C) :**

Cet attribut détermine quel signal IR transmettre lorsque l'UPIC reçoit une commande du panneau, en fonction du type et de la fonction du signal IR appris.

UPIC peut apprendre jusqu'à 5 ensembles de types IR, 8 signaux pour chaque type. Lors de la transmission du signal, le signal IR doit être

spécifié avec cet attribut.

Le format est 0x_**XY**_

7

X = Type d'appareil (1~5)

Y = numéro de signal IR (1~8)

Par exemple, si l'UPIC a appris un signal IR sur le type d'appareil 1, un signal IR 8, le panneau doit envoyer une commande avec le paramètre d'attribut 0x._**18**_pour que l'UPIC transmette ce signal.

**Sélectionnez Envoyer la LED IR (0x1011) :**

UPIC peut contrôler jusqu'à 5 types d'appareils (Type 1~5) avec ses 6 LED IR. Il peut être configuré pour envoyer un signal IR avec différentes LED en utilisant cet attribut.

Le format doit être lu comme suit, en utilisant la valeur par défaut 0x2020202020 comme exemple

| 0x20                   | 0x20                   | 0x20                   | 0x20                   | 0x20                   |
| ---------------------- | ---------------------- | ---------------------- | ---------------------- | ---------------------- |
|                        |                        |                        |                        |                        |
| LED IR à utiliser avec | LED IR à utiliser avec | LED IR à utiliser avec | LED IR à utiliser avec | LED IR à utiliser avec |
| Type d'appareil 1      | Type d'appareil 2      | Type d'appareil 3      | Type d'appareil 4      | Type d'appareil 5      |
|                        |                        |                        |                        |                        |

Pour chaque valeur de type d'appareil, la valeur doit être lue dans Bit0~5, au format suivant :

| Valeur          | dans    |           |      | 2     |              |              |                | 0            |       |              |              |
| --------------- | ------- | --------- | ---- | ----- | ------------ | ------------ | -------------- | ------------ | ----- | ------------ | ------------ |
| Hexadécimal     |         |           |      |       |              |              |                |              |       |              |              |
| ombre           |         |           |      |       |              |              |                |              |       |              |              |
|                 |         |           |      |       |              |              |                |              |       |              |              |
| Numéro de bit   |         | Ça arrive | BIT6 |       | Btkh         | BIT4         | je l'ai acheté | Bêta         |       | BIT1         | BIT0         |
|                 |         |           |      |       |              |              |                |              |       |              |              |
| Valeur en       | Peu     | 0         | 0    |       | 1            | 0            | 0              | 0            |       | 0            | 0            |
| nombre          |         |           |      |       |              |              |                |              |       |              |              |
|                 |         |           |      |       |              |              |                |              |       |              |              |
| Numéro de LED à | Réservé | Réservé   |      | LED 6 | LED 5        | DEL 4        | LED 3          |              | DEL 2 | LED 1        |              |
| être activé     |         |           |      |       | 1=activer    | 1=activer    | 1=activer      | 1=activer    |       | 1=activer    | 1=activer    |
|                 |         |           |      |       | 0=désactiver | 0=désactiver | 0=désactiver   | 0=désactiver |       | 0=désactiver | 0=désactiver |
|                 |         |           |      |       |              |              |                |              |       |              |              |

Par exemple : 0x20 = 0010 0000 dans le numéro de bit, ce qui signifie que seule la LED 6 (la LED centrale) sera activée lorsque l'UPIC transmettra un signal IR dans ce type d'appareil.

Si vous souhaitez définir le signal IR à transmettre à la fois avec la LED 2 et la LED 6, la valeur en numéro de bit sera 0010 0010 = 0x22

| 0       | 0       | 1       | 0          |
| ------- | ------- | ------- | ---------- |
|         |         |         |            |
| Réservé | Réservé | LED 6   | LED 5      |
|         |         | Activer | Désactiver |
|         |         |         |            |

| 0          | 0          | 1       | 0          |
| ---------- | ---------- | ------- | ---------- |
|            |            |         |            |
| DEL 4      | LED 3      | DEL 2   | LED 1      |
| Désactiver | Désactiver | Activer | Désactiver |
|            |            |         |            |

0010 0010 en nombre de bits = 0x22 en nombre hexadécimal, si vous souhaitez appliquer ce paramètre au type d'appareil 1 uniquement et laisser l'autre type d'appareil inchangé, le paramètre d'attribut final sera : 0x**22**20202020

| 0x22                     | 0x20                     | 0x20                     | 0x20                     | 0x20                     |
| ------------------------ | ------------------------ | ------------------------ | ------------------------ | ------------------------ |
|                          |                          |                          |                          |                          |
| LED IR à utiliser        | LED IR à utiliser        | LED IR à utiliser        | LED IR à utiliser        | LED IR à utiliser        |
| avec appareil de type 1, | avec appareil de type 2, | avec appareil de type 3, | avec appareil de type 4, | avec appareil de type 5, |
| LED 6&2                  | LED 6                    | LED 6                    | LED 6                    | LED 6                    |
|                          |                          |                          |                          |                          |

Vous pouvez utiliser cet attribut pour programmer quelles LED doivent être activées pour différents types d'appareils IR._**NOTE IMPORTANTE:**_

Bien qu'il soit possible de définir la transmission de plusieurs LED lors de l'envoi d'un signal IR, veuillez définir**PAS PLUS DE 2**LED à activer. La raison de cette limitation est que pour chaque LED supplémentaire activée, la consommation électrique augmentera considérablement. Si vous activez plus de 2 LED, la batterie sera épuisée en un temps beaucoup plus court que ce qui est idéal.

8
