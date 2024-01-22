# VESTA 187

**Commutateur de scénario intelligent WSS-4E-ZBS**

**Introduction**

WSS-4E-ZBS est un commutateur de scénario à quatre boutons tactiles ZigBee conçu pour contrôler un groupe d'appareils domotiques préprogrammés en appuyant simplement sur les boutons tactiles du scénario sous le même réseau ZigBee.

Le Scenario Switch utilise la technologie ZigBee pour la transmission du signal sans fil. ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

Le Scenario Switch sert de périphérique final dans le réseau ZigBee. Il peut être inclus dans le réseau ZigBee pour transmettre un signal lors de l'activation et peut contrôler n'importe quel appareil ZigBee, mais ne peut permettre à aucun autre appareil ZigBee de rejoindre le réseau via le commutateur de scénario.

Le commutateur de scénario à quatre boutons tactiles WSS-4E ZigBee comprend les modèles suivants :

WSS-4E-ZBS

VSS-CHE-ZBS-OTA

![](<.gitbook/assets/0 (75).jpeg>)

**Présentation de l'appareil**

**1. LED de scénario**

Il y a quatre LED de scénario, la LED s'allumera en fonction du bouton tactile de scénario correspondant enfoncé.

Lorsque le commutateur de scénario reçoit un accusé de réception du panneau de commande après avoir appuyé sur un bouton, il clignote une fois et émet un bip à titre d'indication.

Si la LED clignote deux fois lorsque vous appuyez sur le bouton tactile, cela signifie que le panneau de commande ZigBee n'a pas pu recevoir le signal envoyé par le commutateur de scénario, veuillez vérifier la connectivité ZigBee.

**2. Bouton tactile de scénario**

Le commutateur de scénario dispose de 4 boutons tactiles de scénario :

Toucher le bouton 1

![](<.gitbook/assets/1 (67).jpeg>)

Touchez le bouton 2

Touchez le bouton 3

Touchez le bouton 4

1.  **Compartiment à piles**
2.  **Bouton de fonction**
    -   Appuyez et maintenez pendant 10 secondes pour réinitialiser.
3.  **LED ZigBee (rouge)**

La LED rouge s'allume dans les situations suivantes :

-   -   Clignote une fois :

Lors de l'envoi d'un signal de contrôle, de réinitialisation ou d'apprentissage.

Lorsque le commutateur de scénario reçoit un accusé de réception du panneau de commande après avoir appuyé sur un bouton.

-   -   Clignote deux fois :

Le Scenario Switch a rejoint avec succès un réseau ZigBee.

1.  **Fonction Boutonnière**

**Caractéristiques**

![](<.gitbook/assets/2 (60).jpeg>)

-   _**Détection de batterie et de batterie faible**_

Le commutateur de scénario utilise deux piles alcalines AA de 1,5 V comme source d'alimentation. Le commutateur de scénario est doté d'une fonction de détection de batterie faible. Lorsque la tension de la batterie est faible, le commutateur de scénario transmet le signal de batterie faible au coordinateur du réseau ZigBee.

1

-   ![](<.gitbook/assets/3 (65).png>)_**Scénario**_

Lorsqu'un bouton tactile de scénario est enfoncé, le commutateur de scénario enverra un signal au panneau de commande pour activer le scénario correspondant (voir le panneau de commande pour plus de détails).

**Configuration du réseau ZigBee**

![](<.gitbook/assets/4 (51).jpeg>)

-   _**Directives relatives aux appareils ZigBee**_

ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

En raison de la structure fondamentale du réseau ZigBee, l'appareil ZigBee recherchera et rejoindra activement le réseau après la mise sous tension. Étant donné que l'exécution d'une tâche de connexion au réseau peut consommer de l'énergie, il est nécessaire de suivre les instructions pour éviter de vider la batterie d'un appareil ZigBee.

-   -   Assurez-vous que votre routeur ou coordinateur réseau ZigBee est allumé avant d'insérer la batterie dans l'appareil ZigBee.
    -   Assurez-vous que le routeur ou le coordinateur réseau ZigBee est sous tension et à portée lorsqu'un appareil ZigBee est en cours d'utilisation.
    -   Ne retirez pas un appareil ZigBee du routeur ou du coordinateur réseau ZigBee sans retirer la batterie d'un appareil ZigBee.
-   _**Rejoindre le réseau ZigBee**_

![](<.gitbook/assets/5 (33).jpeg>)

En tant qu'appareil ZigBee, le commutateur de scénario doit rejoindre un réseau ZigBee pour se connecter aux appareils ZigBee.

Veuillez suivre les étapes ci-dessous pour rejoindre le commutateur de scénario au réseau ZigBee.

-   1.  Retirez le couvercle à l'aide d'un tournevis.
    2.  Insérez la batterie puis replacez le couvercle.
    3.  Appuyez et maintenez le bouton de fonction pendant 10 secondes et relâchez lorsque la LED rouge clignote une fois pour rejoindre le réseau ZigBee. Veuillez vous assurer d'activer la fonction d'autorisation de participation sur le routeur ou le coordinateur de votre réseau ZigBee.
    4.  Si le commutateur de scénario rejoint avec succès un réseau ZigBee, l'indicateur LED rouge clignote deux fois pour confirmer.
    5.  Après avoir rejoint le réseau ZigBee, le Scenario Switch sera automatiquement enregistré dans le réseau. Veuillez vérifier auprès du coordinateur du réseau ZigBee, du panneau de commande du système ou du CIE (équipement de contrôle et d'indication) pour confirmer si l'adhésion et l'enregistrement ont réussi.
-   _**Suppression d'un appareil du réseau ZigBee (réinitialisation d'usine)**_

![](<.gitbook/assets/6 (43).png>)

Pour supprimer le commutateur de scénario du réseau ZigBee actuel, le commutateur doit être mis en réinitialisation d'usine pour terminer la suppression de l'appareil. La fonction de réinitialisation d'usine effacera le d de ses informations de configuration stockées et invitera le commutateur de scénario à rechercher un nouveau réseau ZigBee.

**Avant de retirer l'appareil, assurez-vous que le commutateur de scénario se trouve dans la plage actuelle du signal réseau ZigBee.**

-   1.  Appuyez et maintenez le bouton de fonction pendant 10 secondes, puis relâchez le bouton pour réinitialiser le commutateur de scénario.
    2.  Lors de la réinitialisation, le commutateur de scénario effacera les paramètres réseau ZigBee actuels et transmettra le signal au coordinateur ZigBee pour se retirer du réseau ZigBee actuel. Il recherchera ensuite à nouveau activement le réseau ZigBee disponible et rejoindra automatiquement le réseau.
-   _**Mise à niveau du micrologiciel OTA (pour la version OTA uniquement)**_

![](<.gitbook/assets/7 (38).png>)

Le commutateur de scénario à quatre boutons tactiles prend en charge la fonction de mise à niveau du micrologiciel OTA via le réseau ZigBee, qui peut être lancée à partir du coordinateur du réseau ZigBee. Suivez les étapes ci-dessous pour effectuer la mise à niveau du micrologiciel OTA.**Étape 1.**Vous devez accéder à votre coordinateur ZigBee pour effectuer la mise à niveau du micrologiciel en direct.

**Étape 2.**Sur la page Web de configuration, sélectionnez l'appareil que vous souhaitez mettre à niveau et sélectionnez le nouveau firmware ZigBee fourni. Veuillez vous référer au manuel d'utilisation du coordinateur ZigBee pour plus de détails.

**Étape 3.**Appuyez sur « OK » pour démarrer le processus de mise à niveau et la LED continuera à clignoter. Pendant le processus OTA,

veuillez ne pas effectuer d'autres actions ni éteindre le panneau.

**Étape 4.**La durée d'une mise à niveau prendra environ 20 à 30 minutes. Veuillez noter que la durée peut varier en fonction de la taille du fichier ou de la distance entre votre accessoire et le coordinateur.

**Étape 5.**Attendez que le micrologiciel termine la mise à jour. Lorsque la progression atteint 100 %, l'appareil se réinitialise automatiquement. Vous pouvez également actualiser à nouveau la page Web pour vous assurer que le micrologiciel de l'appareil est correctement mis à jour avec la version la plus récente affichée.

**Installation**

-   Le Scenario Switch est conçu pour être monté sur une surface plane avec des vis de fixation.
-   La base comporte 3 découpes, là où le plastique est plus fin, à des fins de montage.
    1.  Retirez le couvercle à l'aide d'un tournevis.
    2.  Percez les trous appropriés sur la base.
    3.  En utilisant les trous comme gabarit, percez des trous dans la surface.
    4.  Vissez la base dans la surface.
    5.  Remettez le couvercle sur la base et fixez-le en serrant la vis de fixation.

2

![](<.gitbook/assets/8 (34).jpeg>)

-   **Annexe (Pour les développeurs uniquement)**
    -   _**ID du cluster de sélecteur de scène**_

**ID de l'appareil : sélecteur de scène 0x0004**

**Point de terminaison : 0x01**

| **Du côté serveur**                      |        |                          |                                                             |                    |               |                  |                     | **Côté client**    |                 |                   |   |
| ---------------------------------------- | ------ | ------------------------ | ----------------------------------------------------------- | ------------------ | ------------- | ---------------- | ------------------- | ------------------ | --------------- | ----------------- | - |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             | **Obligatoire**    |               |                  |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
| De base (0x0000)                         |        |                          |                                                             |                    |               |                  | Identifier (0x0003) |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
| Identifier (0x0003)                      |        |                          |                                                             |                    |               | Groupes (0x0004) |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    | Scènes (0x0005) |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             | **Facultatif**     |               |                  |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
| Configuration de l'alimentation (0x0001) |        |                          |                                                             |                    |               |                  | _Aucun_             |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
|                                          |        |                         | _**Attribut des informations de base sur le cluster**_      |                    |               |                  |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
| _**Identifier**_                         |        |                          | _**Nom**_                                                   | _**Taper**_        |               | _**Gamme**_      |                     | _**Accéder**_      | _**Défaut**_    | _**Obligatoire**_ |   |
|                                          |        |                          |                                                             | _**/ Facultatif**_ |               |                  |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
| 0x0000                                   |        |                          | _Version ZCL_                                               | 8 bits non signé   |               | 0x00 –0xff       |                     | Lire               | 0x01            | M                 |   |
|                                          |        | entier                   |                                                             |                    | seulement     |                  |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
| 0x0001                                   |        | Version de l'application | 8 bits non signé                                            | 0x00 – 0xff        |               | Lire             | 0x00                | Ô                  |                 |                   |   |
|                                          | entier |                          | seulement                                                   |                    |               |                  |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
| 0x0003                                   |        |                          | _Version matérielle_                                        | 8 bits non signé   |               | 0x00 –0xff       |                     | Lire               | 0               | Ô                 |   |
|                                          |        | entier                   |                                                             |                    | seulement     |                  |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
| 0x0004                                   |        | _Nom du Fabricant_       | Personnage                                                  | 0 – 32 octets      |               | Lire             | Climax              | Ô                  |                 |                   |   |
|                                          | Chaîne |                          | seulement                                                   | Technologie        |               |                  |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
| 0x0005                                   |        |                          | _Identifiant du modèle_                                     | Personnage         | 0 – 32 octets |                  | Lire                | (Numéro de modèle) | Ô               |                   |   |
|                                          |        | Chaîne                   |                                                             | seulement          |               |                  |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
| 0x0006                                   |        |                          | _DateCode_                                                  | Personnage         | 0 – 16 octets |                  | Lire                |                    | Ô               |                   |   |
|                                          |        | Chaîne                   |                                                             | seulement          |               |                  |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
| 0x0007                                   |        |                          | _Source d'énergie_                                          | 8 bits             |               | 0x00 –0xff       |                     | Lire               |                 | M                 |   |
|                                          |        |                          |                                                             | seulement          |               |                  |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
| 0x0010                                   |        | _EmplacementDescription_ | Personnage                                                  | 0 – 32 octets      |               | Lire /           |                     | Ô                  |                 |                   |   |
|                                          | Chaîne |                          | Écrire                                                      |                    |               |                  |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
| 0x0011                                   |        | _Environnement physique_ | 8 bits                                                      |                    | 0x00 –0xff    |                  | Lire /              | 0x00               | Ô               |                   |   |
|                                          |        |                          | Écrire                                                      |                    |               |                  |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
| 0x0012                                   |        |                          | _Appareil activé_                                           | Booléen            | 0x00 –0x01    |                  | Lire /              | 0x01               | M               |                   |   |
|                                          |        |                          | Écrire                                                      |                    |               |                  |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
|                                          |        |                         | _**Attribut des informations d'identification du cluster**_ |                    |               |                  |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
| **Identifier**                           |        |                          | **Nom**                                                     | **Taper**          |               | **Gamme**        |                     | **Accéder**        | **Défaut**      | **Obligatoire**   |   |
|                                          |        |                          |                                                             | **/ Facultatif**   |               |                  |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |
| 0x0000                                   |        |                          | _Identifier l'heure_                                        | Non signé          | 0x00 –0xffff  |                  | Lire /              | 0x0000             | M               |                   |   |
|                                          |        | Entier de 16 bits        |                                                             | Écrire             |               |                  |                     |                    |                 |                   |   |
|                                          |        |                          |                                                             |                    |               |                  |                     |                    |                 |                   |   |

-   _**Attribut des informations sur le cluster de configuration de l'alimentation**_

| **Identifier**   | **Nom**                     | **Taper** | **Gamme**   | **Accéder** | **Défaut** | **Obligatoire** |   |
| ---------------- | --------------------------- | --------- | ----------- | ----------- | ---------- | --------------- | - |
| **/ Facultatif** |                             |           |             |             |            |                 |   |
|                  |                             |           |             |             |            |                 |   |
| 0x0035           | Masque d'alarme de batterie | Bitmap    | 0000 - 000x | Lire /      | 0000 0000  | Ô               |   |
| (8 bits)         | Écrire                      |           |             |             |            |                 |   |
|                  |                             |           |             |             |            |                 |   |

3
