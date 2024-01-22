# VESTA 180

**Commutateur de commande d'obturateur SCS-1-ZBS**

**Introduction**

SCS-1-ZBS est un interrupteur de commande de volet à trois boutons ZigBee conçu pour contrôler un groupe d'appareils domotiques préprogrammés en appuyant simplement sur les boutons de scénario. En définissant le scénario de contrôle de l'obturateur sur le coordinateur/panneau de commande du réseau ZigBee, l'interrupteur de commande de l'obturateur pourra contrôler le mouvement de l'obturateur en appuyant simplement sur ses boutons.

Le Shutter Switch utilise la technologie ZigBee pour la transmission du signal sans fil. ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

Le Shutter Switch sert de périphérique final dans le réseau ZigBee. Il peut être inclus dans le réseau ZigBee pour transmettre un signal lors de l'activation et peut contrôler n'importe quel appareil ZigBee, mais ne peut permettre à aucun autre appareil ZigBee de rejoindre le réseau via le commutateur d'obturation.

Le commutateur de commande d'obturation SCS-1 ZigBee comprend les modèles suivants :

SCS-1-ZBS

SCS-1-ZBS-OTA

![](<.gitbook/assets/0 (69).jpeg>)

**Présentation de l'appareil**

**1. LED de scénario**

Lorsque l'un des 3 boutons de scénario est enfoncé, la LED s'allume brièvement

**2. Boutons de scénario**

Le commutateur de commande d'obturation dispose de 3 boutons de scénario

1.  **Compartiment à piles**
2.  **Bouton de fonction**
    -   Appuyez et maintenez pendant 10 secondes pour réinitialiser.
3.  **LED ZigBee (rouge)**

La LED rouge s'allume dans les situations suivantes :

-   -   Clignote une fois :

Lors de l'envoi du signal de contrôle/réinitialisation/apprentissage.

-   -   Clignote deux fois :

Le commutateur de commande d'obturation a rejoint avec succès un réseau ZigBee.

1.  **Fonction Boutonnière**

**Caractéristiques**

![](<.gitbook/assets/1 (61).jpeg>)

-   _**Détection de batterie et de batterie faible**_

Le commutateur de commande d’obturation utilise deux piles alcalines AA de 1,5 V comme source d’alimentation. Le commutateur est doté d'une fonction de détection de batterie faible. Lorsque la tension de la batterie est faible, le commutateur de commande d'obturation transmet le signal de batterie faible au coordinateur du réseau ZigBee.

![](<.gitbook/assets/2 (62).png>)

-   _**Surveillance**_

Le commutateur de commande d'obturation transmettra un signal de supervision pour signaler régulièrement son état en fonction de l'intervalle de temps défini par l'utilisateur. L'intervalle par défaut est de 30 minutes.

![](<.gitbook/assets/3 (63).png>)

-   _**Scénario et contrôle de l'obturateur**_

Lorsqu'un bouton de scénario est enfoncé, le commutateur de commande d'obturation enverra un signal au panneau de commande pour

1

activer le scénario correspondant (voir Panneau de configuration pour plus de détails). Définissez le scénario dans le panneau de commande pour contrôler la fonction d'ouverture/fermeture/arrêt du volet afin de faire fonctionner le volet via l'interrupteur de commande de scénario. L'interrupteur émettra un bip pour indiquer que le bouton est enfoncé.

**Configuration du réseau ZigBee**

![](<.gitbook/assets/4 (48).jpeg>)

-   _**Directives relatives aux appareils ZigBee**_

ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

En raison de la structure fondamentale du réseau ZigBee, l'appareil ZigBee recherchera et rejoindra activement le réseau après la mise sous tension. Étant donné que l'exécution d'une tâche de connexion au réseau peut consommer de l'énergie, il est nécessaire de suivre les instructions pour éviter de vider la batterie d'un appareil ZigBee.

-   -   Assurez-vous que votre routeur ou coordinateur réseau ZigBee est sous tension avant d'insérer la batterie dans l'appareil ZigBee.
    -   Assurez-vous que le routeur ou le coordinateur réseau ZigBee est sous tension et à portée lorsqu'un appareil ZigBee est en cours d'utilisation.
    -   Ne retirez pas un appareil ZigBee du routeur ou du coordinateur réseau ZigBee sans retirer la batterie d'un appareil ZigBee.
-   _**Rejoindre le réseau ZigBee**_

![](<.gitbook/assets/5 (31).jpeg>)

En tant qu'appareil ZigBee, le commutateur de commande d'obturation doit rejoindre un réseau ZigBee pour se connecter aux appareils ZigBee. Veuillez suivre les étapes ci-dessous pour connecter le commutateur de commande d'obturateur au réseau ZigBee.

-   1.  Retirez le couvercle à l'aide d'un tournevis.
    2.  Insérez la batterie puis replacez le couvercle.
    3.  Appuyez et maintenez le bouton de fonction pendant 10 secondes et relâchez lorsque la LED rouge clignote une fois pour rejoindre le réseau ZigBee. Veuillez vous assurer d'activer la fonction d'autorisation de participation sur le routeur ou le coordinateur de votre réseau ZigBee.
    4.  Si le commutateur de commande d'obturation rejoint avec succès un réseau ZigBee, l'indicateur LED rouge clignote deux fois pour confirmer.
    5.  Après avoir rejoint le réseau ZigBee, le commutateur de commande d'obturation sera automatiquement enregistré dans le réseau. Veuillez vérifier auprès du coordinateur du réseau ZigBee, du panneau de contrôle du système ou du CIE (équipement de contrôle et d'indication) pour confirmer si l'adhésion et l'enregistrement ont réussi.
-   _**Suppression d'un appareil du réseau ZigBee (réinitialisation d'usine)**_

![](<.gitbook/assets/6 (41).png>)

Pour supprimer l'appareil du réseau ZigBee actuel, le commutateur de commande d'obturation doit être mis sur la réinitialisation d'usine pour terminer la suppression de l'appareil. La fonction de réinitialisation d'usine effacera l'appareil de ses informations de configuration stockées et invitera le commutateur de commande d'obturation à rechercher un nouveau réseau ZigBee.

**Avant de retirer l'appareil, assurez-vous que le commutateur de commande d'obturation se trouve dans la plage actuelle du signal réseau ZigBee.**

-   1.  Supprimez le contrôle de l'obturateur du panneau de configuration actuel/CIE.
    2.  Appuyez et maintenez le bouton de fonction pendant 10 secondes, puis relâchez le bouton pour réinitialiser l'appareil.
    3.  Lors de la réinitialisation, le commutateur de commande d'obturation effacera les paramètres réseau ZigBee actuels et transmettra le signal au coordinateur ZigBee pour se retirer du réseau ZigBee actuel. Il recherchera ensuite à nouveau activement le réseau ZigBee disponible et rejoindra automatiquement le réseau.
-   _**Mise à niveau du micrologiciel OTA (pour la version OTA uniquement)**_

![](<.gitbook/assets/7 (37).jpeg>)

Le commutateur de commande d'obturation prend en charge la fonction de mise à niveau du micrologiciel OTA via le réseau ZigBee, qui peut être lancée à partir du coordinateur du réseau ZigBee.

Suivez les étapes ci-dessous pour effectuer la mise à niveau du micrologiciel OTA.

**Étape 1.**Vous devez accéder à votre coordinateur ZigBee pour effectuer la mise à niveau du micrologiciel en direct.

**Étape 2.**Sur la page Web de configuration, sélectionnez l'appareil que vous souhaitez mettre à niveau et sélectionnez le nouveau firmware ZigBee fourni. Veuillez vous référer au manuel d'utilisation du coordinateur ZigBee pour plus de détails.

**Étape 3.**Appuyez sur « OK » pour démarrer le processus de mise à niveau et la LED continuera de clignoter. Pendant le processus OTA, veuillez ne pas effectuer d'autres actions ni éteindre le panneau.

**Étape 4.**La durée d'une mise à niveau prendra environ 20 à 30 minutes. Veuillez noter que la durée peut varier en fonction de la taille du fichier ou de la distance entre votre accessoire et le coordinateur.

**Étape 5.**Attendez que le micrologiciel termine la mise à jour. Lorsque la progression atteint 100 %, l'appareil se réinitialise automatiquement. Vous pouvez également actualiser à nouveau la page Web pour vous assurer que le micrologiciel de l'appareil est correctement mis à jour avec la version la plus récente affichée.

![](<.gitbook/assets/8 (31).jpeg>)

**Installation**

-   L'interrupteur de commande de volet est conçu pour être monté sur une surface plane avec des vis de fixation.
-   La base comporte 3 découpes, là où le plastique est plus fin, à des fins de montage.
    1.  Retirez le couvercle à l'aide d'un tournevis.
    2.  Percez les trous appropriés sur la base.
    3.  En utilisant les trous comme gabarit, percez des trous dans la surface.

2

1.  Vissez la base dans la surface.
2.  Remettez le couvercle sur la base et fixez-le en serrant la vis de fixation.

![](<.gitbook/assets/9 (23).jpeg>)

-   **Annexe (Pour les développeurs uniquement)**

_**ID du cluster de sélecteur de scène**_

**ID de l'appareil : sélecteur de scène 0x0004**

**Point de terminaison : 0x01**

| **Du côté serveur** |                 | **Côté client** |
| ------------------- | --------------- | --------------- |
|                     |                 |                 |
|                     | **Obligatoire** |                 |

De base (0x0000)

Identifier (0x0003)

Identifier (0x0003)

Groupes (0x0004)

Scènes (0x0005)

**Facultatif**

Configuration de l'alimentation (0x0001)

_Aucun_

-   _**Attribut des informations de base sur le cluster**_

| _**Identifier**_   | _**Nom**_                | _**Taper**_      | _**Gamme**_   | _**Accéder**_ | _**Défaut**_       | _**Obligatoire**_ |   |
| ------------------ | ------------------------ | ---------------- | ------------- | ------------- | ------------------ | ----------------- | - |
| _**/ Facultatif**_ |                          |                  |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |
| 0x0000             | _Version ZCL_            | 8 bits non signé | 0x00 –0xff    | Lire          | 0x01               | M.                |   |
| entier             | seulement                |                  |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |
| 0x0001             | Version de l'application | 8 bits non signé | 0x00 – 0xff   | Lire          | 0x00               | Ô                 |   |
| entier             | seulement                |                  |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |
| 0x0003             | _Version matérielle_     | 8 bits non signé | 0x00 –0xff    | Lire          | 0                  | Ô                 |   |
| entier             | seulement                |                  |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |
| 0x0004             | _Nom du Fabricant_       | Personnage       | 0 – 32 octets | Lire          | Climax             | Ô                 |   |
| Chaîne             | seulement                | Technologie      |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |
| 0x0005             | _Identifiant du modèle_  | Personnage       | 0 – 32 octets | Lire          | (Numéro de modèle) | Ô                 |   |
| Chaîne             | seulement                |                  |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |
| 0x0006             | _CodeDate_               | Personnage       | 0 – 16 octets | Lire          |                    | Ô                 |   |
| Chaîne             | seulement                |                  |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |
| 0x0007             | _Source d'énergie_       | 8 bits           | 0x00 –0xff    | Lire          |                    | M.                |   |
| seulement          |                          |                  |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |
| 0x0010             | _EmplacementDescription_ | Personnage       | 0 – 32 octets | Lire /        |                    | Ô                 |   |
| Chaîne             | Écrire                   |                  |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |
| 0x0011             | _Environnement physique_ | 8 bits           | 0x00 –0xff    | Lire /        | 0x00               | Ô                 |   |
| Écrire             |                          |                  |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |
| 0x0012             | _Appareil activé_        | Booléen          | 0x00 –0x01    | Lire /        | 0x01               | M.                |   |
| Écrire             |                          |                  |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |

-   _**Attribut des informations d'identification du cluster**_

| **Identifier**    | **Nom**                                                                            | **Taper** | **Gamme**    | **Accéder** | **Défaut** | **Obligatoire** |   |
| ----------------- | ---------------------------------------------------------------------------------- | --------- | ------------ | ----------- | ---------- | --------------- | - |
| **/ Facultatif**  |                                                                                    |           |              |             |            |                 |   |
|                   |                                                                                    |           |              |             |            |                 |   |
| 0x0000            | _Identifier l'heure_                                                               | Non signé | 0x00 –0xffff | Lire /      | 0x0000     | M.              |   |
| Entier de 16 bits | Écrire                                                                             |           |              |             |            |                 |   |
|                   |                                                                                    |           |              |             |            |                 |   |
|                   | _**Attribut des informations sur le cluster de configuration de l'alimentation**_ |           |              |             |            |                 |   |
|                   |                                                                                    |           |              |             |            |                 |   |
| **Identifier**    | **Nom**                                                                            | **Taper** | **Gamme**    | **Accéder** | **Défaut** | **Obligatoire** |   |
| **/ Facultatif**  |                                                                                    |           |              |             |            |                 |   |
|                   |                                                                                    |           |              |             |            |                 |   |
| 0x0035            | Masque d'alarme de batterie                                                        | Bitmap    | 0000 - 000x  | Lire /      | 0000 0000  | Ô               |   |
| (8 bits)          | Écrire                                                                             |           |              |             |            |                 |   |
|                   |                                                                                    |           |              |             |            |                 |   |

3

_**ID du cluster du contrôleur de stores (pour le panneau HPGW-G)**_

**ID de l'appareil : Contrôleur de stores 0x0201**

**Point de terminaison : 0x01**

| **Du côté serveur** |                 | **Côté client** |
| ------------------- | --------------- | --------------- |
|                     |                 |                 |
|                     | **Obligatoire** |                 |

De base (0x0000)

Identifier (0x0003)

Identifier (0x0003)

Marche/Arrêt (0x0006)

Contrôle de niveau (0x0008)

**Facultatif**

Configuration de l'alimentation (0x0001)

_Aucun_

-   _**Attribut des informations de base sur le cluster**_

| _**Identifier**_   | _**Nom**_                | _**Taper**_      | _**Gamme**_   | _**Accéder**_ | _**Défaut**_       | _**Obligatoire**_ |   |
| ------------------ | ------------------------ | ---------------- | ------------- | ------------- | ------------------ | ----------------- | - |
| _**/ Facultatif**_ |                          |                  |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |
| 0x0000             | _Version ZCL_            | 8 bits non signé | 0x00 –0xff    | Lire          | 0x01               | M.                |   |
| entier             | seulement                |                  |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |
| 0x0001             | Version de l'application | 8 bits non signé | 0x00 – 0xff   | Lire          | 0x00               | Ô                 |   |
| entier             | seulement                |                  |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |
| 0x0003             | _Version matérielle_     | 8 bits non signé | 0x00 –0xff    | Lire          | 0                  | Ô                 |   |
| entier             | seulement                |                  |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |
| 0x0004             | _Nom du Fabricant_       | Personnage       | 0 – 32 octets | Lire          | Climax             | Ô                 |   |
| Chaîne             | seulement                | Technologie      |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |
| 0x0005             | _Identifiant du modèle_  | Personnage       | 0 – 32 octets | Lire          | (Numéro de modèle) | Ô                 |   |
| Chaîne             | seulement                |                  |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |
| 0x0006             | _CodeDate_               | Personnage       | 0 – 16 octets | Lire          |                    | Ô                 |   |
| Chaîne             | seulement                |                  |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |
| 0x0007             | _Source d'énergie_       | 8 bits           | 0x00 –0xff    | Lire          |                    | M.                |   |
| seulement          |                          |                  |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |
| 0x0010             | _EmplacementDescription_ | Personnage       | 0 – 32 octets | Lire /        |                    | Ô                 |   |
| Chaîne             | Écrire                   |                  |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |
| 0x0011             | _Environnement physique_ | 8 bits           | 0x00 –0xff    | Lire /        | 0x00               | Ô                 |   |
| Écrire             |                          |                  |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |
| 0x0012             | _Appareil activé_        | Booléen          | 0x00 –0x01    | Lire /        | 0x01               | M.                |   |
| Écrire             |                          |                  |               |               |                    |                   |   |
|                    |                          |                  |               |               |                    |                   |   |

-   _**Attribut des informations d'identification du cluster**_

| **Identifier**    | **Nom**                                                                            | **Taper** | **Gamme**    | **Accéder** | **Défaut** | **Obligatoire** |   |
| ----------------- | ---------------------------------------------------------------------------------- | --------- | ------------ | ----------- | ---------- | --------------- | - |
| **/ Facultatif**  |                                                                                    |           |              |             |            |                 |   |
|                   |                                                                                    |           |              |             |            |                 |   |
| 0x0000            | _Identifier l'heure_                                                               | Non signé | 0x00 –0xffff | Lire /      | 0x0000     | M.              |   |
| Entier de 16 bits | Écrire                                                                             |           |              |             |            |                 |   |
|                   |                                                                                    |           |              |             |            |                 |   |
|                   | _**Attribut des informations sur le cluster de configuration de l'alimentation**_ |           |              |             |            |                 |   |
|                   |                                                                                    |           |              |             |            |                 |   |
| **Identifier**    | **Nom**                                                                            | **Taper** | **Gamme**    | **Accéder** | **Défaut** | **Obligatoire** |   |
| **/ Facultatif**  |                                                                                    |           |              |             |            |                 |   |
|                   |                                                                                    |           |              |             |            |                 |   |
| 0x0035            | Masque d'alarme de batterie                                                        | Bitmap    | 0000 - 000x  | Lire /      | 0000 0000  | Ô               |   |
| (8 bits)          | Écrire                                                                             |           |              |             |            |                 |   |
|                   |                                                                                    |           |              |             |            |                 |   |

4
