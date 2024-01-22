# VESTA 092

**VRCP-DECT****Extension de voix**

VRCP-DECT est un prolongateur vocal qui permet aux utilisateurs d'appeler une aide d'urgence avec une commande de reconnaissance vocale ou en appuyant sur un seul bouton. VRCP-DECT dispose d'une reconnaissance vocale intégrée et peut activer un appel d'urgence vers CMS par des commandes vocales ou des mots-clés prédéfinis. Il convient aux soins médicaux et aux personnes âgées, aux maisons à plusieurs étages et aux locaux plus grands.

-   _**Identification des pièces :**_

![](<.gitbook/assets/0 (47).jpeg>)

1.  **Bouton d'alarme**
    -   -   Appuyez sur le bouton pour obtenir de l'aide et ouvrir une communication bidirectionnelle.
        -   Appuyez et maintenez enfoncé le bouton pendant 5 secondes pendant la communication bidirectionnelle pour demander au panneau de commande de mettre fin à la communication. Le panneau de contrôle mettra fin ou non à la communication en fonction des paramètres utilisateur.
2.  **LED rouge**
    -   Allumé : VRCP-DECT n'a pas été appris dans la centrale.
    -   Clignote toutes les 5 secondes : batterie faible
    -   3 s allumé, 3 s éteint : défaut CA
    -   Clignote deux fois : apprentissage réussi
3.  **LED verte**
    -   -   Allumé : VRCP-DECT est en cours d'apprentissage dans la centrale. VRCP-DECT est en communication bidirectionnelle
4.  **Conférencier**
5.  **Microphone pour VR (reconnaissance vocale)**
6.  **Microphone pour communication bidirectionnelle**
7.  **Prise CC**
    -   Connexion de l'adaptateur secteur DC 9V 1A SPS
8.  **Bouton Test/Apprentissage**

1

-   -   Appuyez et maintenez le bouton enfoncé pendant 3 secondes jusqu'à ce que VRCP-DECT émette 1 bip long pour indiquer qu'il est entré en mode d'apprentissage.

1.  **Coupe-batterie**
2.  **Interrupteur DIP**
3.  **Trous de montage**
4.  **Marque triangulaire**
    -   La marque triangulaire doit pointer vers le haut lorsque le support est fixé au mur.

-   _**Source de courant:**_

Le Voice Extender peut être alimenté soit par le secteur, soit par une batterie.

**Alimentation CA :**Un adaptateur secteur SPS DC 9 V 1 A est fourni pour la connexion à l'alimentation secteur.

-   Lorsque l'alimentation secteur est déconnectée, la LED rouge s'allume/s'éteint toutes les 3 secondes pour indiquer un défaut secteur. DECT sera désactivé pour économiser la batterie.
-   Une fois l'alimentation secteur rétablie, la LED rouge s'éteindra pour indiquer la restauration d'un défaut secteur. DECT sera rallumé et reconnecté au panneau de commande.

**Batterie:**Lorsque l'alimentation secteur est déconnectée, le VRCP-DECT passe à l'utilisation d'une batterie rechargeable à l'intérieur.

-   -   Lorsque la tension de la batterie est faible, le VRCP-DECT enverra un signal de batterie faible au panneau de commande pour informer de la situation.
    -   L'état de batterie faible sera rétabli 12 heures après la fourniture de l'alimentation secteur au VRCP-DECT. VRCP-DECT enverra également un signal de restauration de batterie faible au panneau de commande.
    -   Si l'interrupteur de la batterie est réglé sur OFF, la batterie ne sera pas chargée lorsque l'alimentation secteur est connectée et elle ne servira pas non plus de source d'alimentation de secours en cas d'absence d'alimentation secteur. Vous devez allumer la batterie pour qu'elle soit chargée lorsque l'alimentation secteur est connectée et qu'elle serve de source d'alimentation de secours lorsque l'alimentation secteur est manquante.
-   _**Signal de surveillance**_
    -   -   Après l'installation, le VRCP-DECT transmettra automatiquement le signal de supervision au panneau de commande toutes les 24 heures.
-   _**Sensibilité de la reconnaissance vocale**_
-   La fonction de reconnaissance vocale a trois niveaux de sensibilité : élevé, moyen, faible. Lorsque le niveau de sensibilité est réglé sur élevé, VRCP-DECT détectera plus facilement les mots-clés/commandes et déclenchera l'alarme.
-   Veuillez utiliser un outil pointu pour ajuster les positions du commutateur DIP afin de définir le niveau de sensibilité.

![](<.gitbook/assets/1 (44).png>)

|   |                  | **TREMPER**      |           |   | **Recherche (niveau de sensibilité)** |   |   |   |
| - | ---------------- | ---------------- | --------- | - | ------------------------------------- | - | - | - |
|   |                  |                  |           |   |                                       |   |   |   |
|   |                  |                  |           |   |                                       |   |   |   |
|   | **Commutateur1** |                  |           |   |                                       |   |   |   |
|   |                  | **Commutateur2** |           |   |                                       |   |   |   |
|   |                  |                  |           |   |                                       |   |   |   |
|   | DÉSACTIVÉ        |                  | DÉSACTIVÉ |   | Faible                                |   |   |   |
|   |                  |                  |           |   |                                       |   |   |   |
|   | SUR              |                  | DÉSACTIVÉ |   | Moyen                                 |   |   |   |
|   |                  |                  |           |   |                                       |   |   |   |
|   | DÉSACTIVÉ        |                  | SUR       |   | Haut                                  |   |   |   |
|   |                  |                  |           |   |                                       |   |   |   |

![](<.gitbook/assets/2 (34).jpeg>)

_**\\<NOTE>**_

-   Une fois les paramètres du commutateur Dip modifiés, veuillez débrancher l'alimentation (l'alimentation externe et les piles doivent être retirées), puis rebranchez l'alimentation au VRCP-DECT. VRCP-DECT fonctionnera avec un nouveau réglage de sensibilité après la remise sous tension.

2

-   _**Procédures d'apprentissage :**_

Step 1. Open Panel webpage and start with learning mode. Please refer to the Control Panel manual for details.

Étape 2. Appuyez et maintenez enfoncé le bouton d'apprentissage du VRCP-DECT pendant 3 secondes jusqu'à ce que vous entendiez un long bip, puis relâchez le bouton. VRCP-DECT entrera en mode d'apprentissage pendant 30 secondes. La LED verte sera allumée pendant le mode d'apprentissage.

Étape 3. Lorsque le panneau de commande reçoit le signal du VRCP-DECT, il affichera les informations en conséquence. Si l'appareil que vous souhaitez apprendre existe déjà dans le système, les informations sur l'appareil seront affichées dans la section Appareil appris. Sinon, les informations sur le périphérique seront affichées dans la section Périphérique détecté.

Étape 4.VRCP-DECT émettra deux bips pour indiquer un apprentissage réussi dès réception d'un accusé de réception du panneau de commande.

Étape 5. Cliquez sur « Ajouter » sur la page Web pour inclure le périphérique sélectionné dans le panneau.

_**\\<NOTE>**_

-   -   Si le VRCP-DECT ne reçoit pas d'accusé de réception du panneau de commande pendant le mode d'apprentissage de 30 secondes, il émettra un bip faible pour indiquer que l'apprentissage a échoué et quittera le mode d'apprentissage. La LED verte s'éteindra et la LED rouge s'allumera. Veuillez effectuer à nouveau les étapes d'apprentissage.
-   _**Operation:**_

**Rapport d'urgence**

-   Lorsque vous appuyez sur le**ALARME**ou prononcez la commande vocale spécifique, un rapport d'urgence sera envoyé et une communication bidirectionnelle sera établie selon la durée définie dans votre panneau de contrôle. La LED verte s'allumera pendant la communication.
-   Les mots déclencheurs peuvent être « SARA Alarm (allemand) », « SARA Help (anglais) » ou « Help Me (anglais) », selon la version du micrologiciel. « SARA Alarm (allemand) » doit être prononcé deux fois dans les 5 secondes pour déclencher l'alarme, tandis que « SARA Help (anglais) » ou « Help Me (anglais) » ne doit être prononcé qu'une seule fois pour activer l'alarme.

**Façons de demander de l’aide**

![](<.gitbook/assets/3 (50).png>)

**ou**

-   VRCP-DECT mettra fin à l'appel à l'expiration du délai. La LED verte s'éteindra.
-   Pendant la communication bidirectionnelle, vous pouvez appuyer et maintenir le bouton ALARME pendant 5 secondes pour demander au panneau de commande de mettre fin à la communication. Le panneau de commande mettra fin ou non à la communication bidirectionnelle en fonction des paramètres de l'utilisateur.

3

![](<.gitbook/assets/4 (46).png>)

_**\\<NOTE>**_

-   Lorsque l'option de rappel est activée sur le panneau de commande, la LED verte restera allumée une fois l'appel terminé. La LED verte s'éteindra lorsque la minuterie de rappel sera terminée. Veuillez vous référer au manuel du panneau de configuration pour plus de détails sur la fonction de rappel.
-   Lorsque la fonction d'annulation VRCP-DECT est activée sur le panneau de commande, appuyer sur le bouton du VRCP-DECT mettra fin à la communication bidirectionnelle. Lorsque la fonction d'annulation VRCP-DECT est désactivée, appuyer sur le bouton du VRCP-DECT ne mettra pas fin à la communication bidirectionnelle.
-   Pour garantir la précision de la reconnaissance vocale, évitez d'installer VRCP-DECT dans une pièce grande ou bruyante.
-   L'environnement idéal pour la reconnaissance vocale est le silence ou le silence partiel. Si vous appelez la commande vocale avec une voix normale, veuillez parler à moins de 2 mètres du VRCP-DECT pour garantir le déclenchement de l'alarme.
-   La fonction de reconnaissance vocale dispose de trois niveaux de sensibilité. Vous pouvez tester avec eux et sélectionner le niveau qui convient le mieux à votre emplacement de montage.

**Rapport d'alarme déclenché par d'autres appareils**

-   Lorsqu'une alarme est déclenchée par un appareil appris dans le panneau de commande et que « 808RV » est sélectionné pour la fonction Marche bidirectionnelle sur la page Web de cet appareil, une communication bidirectionnelle sera automatiquement démarrée avec VRCP-DECT sans aucune pression sur un bouton.

_**\\<NOTE>**_

-   Cette fonction de prise automatique d'appel et d'ouverture de communication bidirectionnelle n'est disponible que lorsque l'alimentation secteur est connectée au VRCP-DECT.
-   Si l'alimentation secteur est déconnectée du VRCP-DECT, le DECT sera désactivé, le VRCP-DECT ne pourra pas répondre à l'appel et une communication bidirectionnelle sera démarrée avec GX à la place.

![](<.gitbook/assets/5 (45).png>)

4

**Appel entrant**

-   -   Lorsqu'il y a un appel entrant, appuyer sur le bouton ALARME du VRCP-DECT prendra l'appel.
-   _**Montage du VRCP-DECT**_

Une fois que le VRCP-DECT a été appris avec succès et que vous avez effectué un test de marche pour confirmer que l'appareil est à portée de signal du panneau de commande, vous êtes également satisfait que le niveau de sensibilité sélectionné fonctionne à l'emplacement choisi, vous pouvez procéder à l'installation. . Le VRCP-DECT peut être monté au mur ou déployé sur une surface plane.

**Montage mural**

Assurez-vous que le VRCP-DECT est installé à peu près à hauteur de poitrine, là où le bouton est facilement accessible et utilisé.

1.  Percez les 2 ouvertures défonçables sur le support de montage mural.
2.  Utilisez les 2 trous comme gabarit pour délimiter les positions des trous. Assurez-vous que le symbole triangulaire sur le support pointe vers le haut.
3.  Percez 2 trous et vissez le support au mur.
4.  Connectez un adaptateur secteur DC 9V 1A SPS à la prise DC et gardez le câble bien placé

![](<.gitbook/assets/6 (31).jpeg>)

1.  Installez le VRCP-DECT sur le support de montage. Assurez-vous que la marque imprimée sur le VRCP-DECT doit être alignée avec la marque supérieure sur le support.
2.  Faites pivoter le VRCP-DECT dans le sens des aiguilles d'une montre jusqu'à la position de verrouillage.

![](<.gitbook/assets/7 (27).jpeg>)

**Placement en surface**

Le VRCP-DECT peut être déployé sur une surface plane sans être installé à un emplacement fixe.

1.  Nettoyez l'arrière du VRCP-DECT avec un dégraissant.
2.  Connectez l'adaptateur secteur DC 9V 1A SPS à la prise DC et gardez le câble bien placé à droite ou à gauche. (**Image 1**)
3.  Retirez le support papier du tampon antidérapant et appliquez-le au dos du VRCP-DECT. (**Image 2**)
4.  Placez le VRCP-DECT à l'emplacement souhaité. (**Image 3**)

5

**Image 1****Image 2****Image 3**

![](<.gitbook/assets/8 (29).png>)

6
