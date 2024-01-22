# VESTA 189

**Thermostat TMST-15-ZBS**

**Introduction**

TMST-15-ZBS est un thermostat ZigBee alimenté par batterie. Il est conçu pour être intégré au système de chauffage et de refroidissement domestique pour le contrôle de l’environnement domestique. Le thermostat peut être commandé manuellement à l'aide de l'écran LCD et des boutons, ou accessible à distance via le réseau ZigBee. Il propose des modes de refroidissement et de chauffage avec un point de consigne de température et un programme automatique pour vous permettre de contrôler facilement votre environnement domestique.

Le thermostat utilise la technologie ZigBee pour la transmission du signal sans fil. ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

Le thermostat sert de périphérique final dans le réseau ZigBee. Il peut être inclus dans le réseau ZigBee pour transmettre un signal lors de l'activation, mais ne peut permettre à aucun autre appareil ZigBee de rejoindre le réseau.

**La série TMST-15-ZBS comprend les modèles suivants :**

TMST-15-ZBS

tmst-15-zbs-outa

**Identification des pièces**

![](<.gitbook/assets/0 (77).jpeg>)

**1. Écran LCD**

L'écran LCD affiche les informations suivantes :

![](<.gitbook/assets/1 (68).jpeg>)

1.  Icône du mode Chauffage : Lorsqu'il est affiché, le thermostat est en mode Chauffage.
2.  Icône du mode Refroidissement : Lorsqu'il est affiché, le thermostat est en mode Refroidissement.
3.  Icône de batterie faible : lorsqu'elle est affichée, la tension de la batterie du thermostat est faible.
4.  Connectivité réseau ZigBee :

L'icône s'affiche lorsque le thermostat n'est pas encore appris dans une passerelle/panneau, ou lorsque l'appareil perd la connexion au réseau ZigBee actuel.

1.  Mode : sélection du mode, mode à distance et décalage
2.  Programme : Le thermostat exécutera le réglage du programme programmé.
3.  Lecture de température/point de consigne

**2. Bouton Bas (-).**

Appuyer pour diminuer le point de consigne

Appuyez et maintenez enfoncé pendant 3 secondes pour accéder au mode de programmation.

**3. Bouton Haut (+)**

Appuyez pour augmenter le point de consigne.

Appuyez et maintenez pendant 10 secondes pour entrer en mode d'apprentissage, et « Joi NET » s'affichera sur l'écran LCD.

![](<.gitbook/assets/2 (62).jpeg>)

1.  **Trou de montage mural**
2.  **Compartiment à piles**

Insérez 2 piles alcalines AA.

**6. Bornes de relais (retirez le couvercle du relais pour accéder)**

Bornes de relais 230V 5A NO/COM/NC.

Connectez-vous au système de chauffage/refroidissement de la maison.

1

**Caractéristiques**

![](<.gitbook/assets/3 (55).jpeg>)

-   _**Détection de batterie et de batterie faible**_

Le thermostat utilise 2 piles alcalines AA comme source d'alimentation. Le thermostat dispose d'une fonction de détection de batterie faible. Lorsque la tension de la batterie est faible, le thermostat transmet le signal de batterie faible au coordinateur du réseau ZigBee.

![](<.gitbook/assets/4 (53).jpeg>)

-   _**Contrôle des relais**_

Le thermostat contrôle le système de chauffage/refroidissement de la maison via un contrôle de relais. Ouvrez et retournez le couvercle arrière, retirez le couvercle interne du relais pour révéler les bornes de câblage. Lors du câblage du thermostat, faites passer le câble à travers l’ouverture centrale du couvercle arrière.

![](<.gitbook/assets/5 (64).png>)

-   _**Contrôle des modes**_

Le thermostat dispose de deux modes de fonctionnement : le mode local et le mode programmé.

![](<.gitbook/assets/6 (43).jpeg>)![](<.gitbook/assets/7 (41).jpeg>)

-   **Mode local:**

Le mode local permet de régler la fonction Chauffage/Refroidissement du thermostat et les points de consigne à l'aide des boutons du thermostat.

-   **Mode programmé :**

![](<.gitbook/assets/8 (36).jpeg>)![](<.gitbook/assets/9 (28).jpeg>)

Le mode programmé permet le mode Thermostat et le contrôle du point de consigne via la passerelle une fois l'apprentissage terminé.

Pour changer le mode de fonctionnement, veuillez vous référer à «_Mode de programmation_» pour plus de détails.

![](<.gitbook/assets/10 (39).png>)

-   _**Chauffage/refroidissement et contrôle des points de consigne**_

Le thermostat de chauffage/refroidissement et le point de consigne ne peuvent être réglés localement que lorsque le thermostat est réglé en mode Local.

En mode local, appuyez sur la touche**EN HAUT**(**+**) ou**Vers le bas (-)**bouton pour régler le point de consigne.

En mode programmé, utilisez la passerelle/le panneau de commande pour régler le point de consigne à distance.

Plage de consigne de chaleur : 9°C~30°C.

Plage de consigne de refroidissement : 11°C~32°C

![](<.gitbook/assets/11 (30).png>)

-   _**Télécommande**_

Une fois que le thermostat a rejoint un réseau ZigBee, vous pouvez contrôler le thermostat via le coordinateur de réseau ou la passerelle ZigBee. Veuillez vous référer au manuel de votre coordinateur/passerelle ZigBee pour plus d'informations.

Les fonctions suivantes sont uniquement disponibles pour le réglage via le coordinateur et la passerelle ZigBee :

![](<.gitbook/assets/12 (20).jpeg>)![](<.gitbook/assets/13 (25).jpeg>)

-   -   **Calendrier:**

Vous pouvez uniquement programmer la configuration du calendrier via le coordinateur/passerelle réseau ZigBee.

Paramétrage des horaires : jusqu'à 5 horaires peuvent être programmés pour chaque jour de la semaine avec le mode, le point de consigne et l'heure de début. Contrôle du calendrier :

Normal - Le thermostat exécutera le réglage de la programmation programmée en conséquence.

Maintenir – Le thermostat contournera le programme actuellement programmé et exécutera le programme suivant lorsqu'il commencera. Aucun programme – Le thermostat n'exécutera aucun programme défini jusqu'à ce qu'il soit à nouveau réglé sur Normal.

-   _**Détection de température**_
    -   Le thermostat dispose de capteurs de température intégrés et affichera la température sur l'écran LCD.
    -   Le thermostat transmettra régulièrement des signaux de température en fonction du réglage. L'intervalle par défaut est de 10 minutes.
    -   Lorsque la température change de +/- 2°C, le thermostat transmettra également un signal.
    -   Vous pouvez également appuyer une fois sur le bouton réseau ZigBee pour transmettre manuellement un signal de température.
-   _**Surveillance**_

![](<.gitbook/assets/14 (24).png>)![](<.gitbook/assets/15 (23).png>)

Le thermostat transmettra un signal de supervision toutes les 10 minutes ainsi que les informations sur la température, le mode actuel et le point de consigne pour signaler régulièrement son état.

2

-   ![](<.gitbook/assets/16 (25).png>)_**Mode de programmation**_

**Étape 1.**Appuyez et maintenez enfoncé le bouton Bas (-) pendant 3 secondes pour accéder au mode de programmation.

**Étape 2.**Il existe 3 fonctions disponibles pour la programmation, notamment les fonctions du thermostat, le contrôle du relais à distance et le décalage du point de consigne. Vous pouvez appuyer sur le bouton HAUT (+) ou Bas (-) pour changer de mode.

**Étape 3.**Une fois la sélection terminée, attendez quelques secondes que le thermostat passe dans le mode sélectionné.

**Fonctions du thermostat (chauffage et refroidissement) :**

Dans ce mode, « Pro Mod » sera affiché sur l'écran LCD.

![](<.gitbook/assets/17 (17).jpeg>)

Les modes de chauffage/refroidissement sont disponibles pour la sélection. Appuyez sur le bouton HAUT (+) pour sélectionner Chauffage et sur le bouton Bas (-) pour sélectionner Refroidissement.

Chauffage Refroidissement

![](<.gitbook/assets/18 (12).jpeg>)

Une fois la sélection terminée, attendez quelques secondes que le thermostat quitte automatiquement le mode de réglage. Le thermostat entrera dans le dernier mode sélectionné.

**Contrôle du relais à distance :**

Dans ce mode, « Pro RM » s'affichera sur l'écran LCD. Le mode télécommande vous permet de contrôler le relais à distance via le panneau de commande lorsque la fonction est activée. Le thermostat ne contrôlera pas le relais local en mode distant.

![](<.gitbook/assets/19 (26).png>)

-   Si le mode à distance est désactivé, « dS RM » s'affichera sur l'écran LCD.
-   Si le mode à distance est activé, « En RM » s'affichera sur l'écran LCD.

![](<.gitbook/assets/20 (18).png>)

**Décalage du point de consigne :**

Dans ce mode, « Pro OFS » s'affichera sur l'écran LCD. La fonction Setpoint Offset vous permet de compenser l’écart. Pour calculer le décalage du point de consigne, soustrayez simplement la température ambiante à la température de l'appareil. En mode local, maintenez enfoncé le bouton Bas (-) pendant 3 secondes pour accéder au mode de programmation. Une fois la sélection terminée, attendez quelques secondes que le thermostat passe en sélection de mode.

Par exemple : Si la température de l'appareil est de 20 °C et la température ambiante de 18 °C, alors décalage du point de consigne = 18 – 20 = -2 °C.

Une fois le décalage du point de consigne appliqué, l'appareil fonctionnera en fonction de la température ajustée.

Par exemple : Si la température de l'appareil est de 20 °C et que le décalage du point de consigne est de -2 °C, l'appareil fonctionnera en utilisant 18 °C comme référence réelle.

**Configuration du réseau ZigBee**

-   _**Directives relatives aux appareils ZigBee**_

ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

En raison de la structure fondamentale du réseau ZigBee, l'appareil ZigBee recherchera et rejoindra activement le réseau après la mise sous tension. Étant donné que l'exécution d'une tâche de connexion au réseau peut consommer de l'énergie, il est nécessaire de suivre les instructions pour éviter de vider la batterie d'un appareil ZigBee.

-   Assurez-vous que votre routeur ou coordinateur réseau ZigBee est allumé avant d'insérer la batterie dans l'appareil ZigBee.
-   Assurez-vous que le routeur ou le coordinateur réseau ZigBee est sous tension et à portée lorsqu'un appareil ZigBee est en cours d'utilisation.
-   Ne retirez pas un appareil ZigBee du routeur ou du coordinateur réseau ZigBee sans retirer la batterie d'un appareil ZigBee.

3

-   _**Rejoindre le réseau ZigBee**_

En tant qu'appareil ZigBee, le thermostat doit rejoindre un réseau ZigBee pour que l'utilisateur puisse le contrôler à distance. Veuillez suivre les étapes ci-dessous pour connecter le thermostat au réseau ZigBee.

-   1.  Retirez le couvercle arrière du thermostat et insérez 2 piles alcalines AA pour alimenter le thermostat.
    2.  Appuyez et maintenez enfoncé le bouton du réseau ZigBee pendant 10 secondes, puis relâchez pour rejoindre le réseau ZigBee. Veuillez vous assurer que la fonction d'autorisation de connexion sur le routeur ou le coordinateur de votre réseau ZigBee est activée.
    3.  Attendez quelques secondes que le thermostat rejoigne le réseau ZigBee. Si le thermostat parvient à rejoindre un réseau, l'icône de connexion ZigBee disparaîtra sur l'écran LCD.
    4.  Après avoir rejoint le réseau ZigBee, le thermostat sera automatiquement enregistré dans le système de sécurité du réseau. Veuillez vérifier le panneau de contrôle du système de sécurité ou le CIE (équipement de contrôle et d'indication) pour confirmer si l'adhésion et l'enregistrement ont réussi.
    5.  Après avoir rejoint le réseau ZigBee, si le thermostat perd la connexion au réseau ZigBee actuel, l'icône de connexion ZigBee apparaîtra après 10 minutes. Veuillez vérifier l'état du réseau ZigBee et la plage du signal du thermostat pour corriger la situation.
-   _**Suppression d'un appareil du réseau ZigBee (réinitialisation d'usine)**_

Pour supprimer le thermostat du réseau ZigBee actuel ou définir les valeurs par défaut d'usine, veuillez suivre les étapes ci-dessous :

**Supprimez le thermostat du réseau ZigBee actuel :**

1.  Avant de retirer l'appareil, assurez-vous que le thermostat se trouve dans la plage actuelle du signal du réseau ZigBee.
2.  Appuyez et maintenez le bouton UP (+) pendant 10 secondes, puis relâchez le bouton.
3.  Le thermostat sera supprimé du réseau ZigBee actuel. Il recherchera à nouveau activement le réseau ZigBee disponible et rejoindra automatiquement le réseau.

**Réglez le thermostat aux valeurs par défaut d'usine :**

-   1.  Appuyez simultanément sur les boutons HAUT (+) et Bas (-), puis allumez l'appareil.
    2.  Relâchez les boutons. Le thermostat effacera ses paramètres stockés et reviendra aux valeurs par défaut d'usine.
-   _**Mise à niveau du micrologiciel OTA**_

Le thermostat prend en charge la fonction de mise à niveau du micrologiciel OTA via le réseau ZigBee, qui peut être lancée à partir du coordinateur du réseau ZigBee.

Suivez les étapes ci-dessous pour effectuer la mise à niveau du micrologiciel OTA.

**Étape 1.**Vous devez accéder à votre coordinateur ZigBee pour effectuer la mise à niveau du micrologiciel en direct.

**Étape 2.**Sur la page Web de configuration, sélectionnez l'appareil que vous souhaitez mettre à niveau et sélectionnez le nouveau firmware ZigBee fourni. Veuillez vous référer au manuel d'utilisation du coordinateur ZigBee pour plus de détails.

**Étape 3.**Appuyez sur « OK » pour démarrer le processus de mise à niveau et la LED continuera de clignoter. Pendant le processus OTA, veuillez ne pas effectuer d'autres actions ni éteindre le panneau.

**Étape 4.**La durée d'une mise à niveau prendra environ 20 à 30 minutes. Veuillez noter que la durée peut varier en fonction de la taille du fichier ou de la distance entre votre accessoire et le coordinateur.

**Étape 5**.Attendez que la mise à jour du micrologiciel soit terminée. Lorsque la progression atteint 100 %, l'appareil se réinitialise automatiquement. Vous pouvez également actualiser à nouveau la page Web pour vous assurer que le micrologiciel de l'appareil est correctement mis à jour avec la version la plus récente affichée.

**Installation**

Le thermostat est conçu pour être fixé au mur à l’aide des trous de montage situés sur le capot arrière.

1.  Avant le montage, assurez-vous d'abord de terminer le câblage du relais à travers l'ouverture sur le couvercle arrière.
2.  Utilisez les trous de montage sur le capot arrière comme modèle pour marquer l'emplacement de montage sur le mur.
3.  Percez des trous dans le mur et insérez une cheville murale si nécessaire, vissez le couvercle arrière sur l'emplacement de montage.
4.  Placez le corps principal du thermostat sur le capot arrière, l'installation est terminée.

**Annexe(Pour les développeurs uniquement.)**

-   _**ID du groupe de thermostats**_

**ID de l'appareil : ZCL_HA_REFERENCE DE L'APPAREIL_THERMOSTAT 0x0301**

**Point de terminaison : 0x01**

| **Du côté serveur** |                 | **Côté client** |
| ------------------- | --------------- | --------------- |
|                     |                 |                 |
|                     | **Obligatoire** |                 |

De base (0x0000)

Configuration de l'alimentation (0x0001)

Identifier (0x0003)

_Identifier (0x0003)_

_Marche/Arrêt (0x0006)_

_Heure (0x000A)_

4

THERMOSTAT CVC (0x0201)

Diagnostic (0x0B05)

**Facultatif**

_**Attribut des informations de base sur le cluster**_

| **Identifier**                                                                     | **Nom**                  | **Taper**        | **Gamme**     | **Accéder**       | **Défaut** | **Obligatoire** |   |
| ---------------------------------------------------------------------------------- | ------------------------ | ---------------- | ------------- | ----------------- | ---------- | --------------- | - |
| **/ Facultatif**                                                                   |                          |                  |               |                   |            |                 |   |
|                                                                                    |                          |                  |               |                   |            |                 |   |
| 0x0000                                                                             | _Version ZCL_            | 8 bits non signé | 0x00 –0xff    | Lecture seulement | 0x01       | M.              |   |
| entier                                                                             |                          |                  |               |                   |            |                 |   |
|                                                                                    |                          |                  |               |                   |            |                 |   |
| 0x0001                                                                             | Version de l'application | 8 bits non signé | 0x00 –0xff    | Lecture seulement | 0x00       | Ô               |   |
| entier                                                                             |                          |                  |               |                   |            |                 |   |
|                                                                                    |                          |                  |               |                   |            |                 |   |
| 0x0003                                                                             | _Version matérielle_     | 8 bits non signé | 0x00 –0xff    | Lecture seulement | 0          | Ô               |   |
| entier                                                                             |                          |                  |               |                   |            |                 |   |
|                                                                                    |                          |                  |               |                   |            |                 |   |
| 0x0004                                                                             | _Nom du Fabricant_       | Personnage       | 0 – 32 octets | Lecture seulement | Climax     | Ô               |   |
| Chaîne                                                                             | Technologie              |                  |               |                   |            |                 |   |
|                                                                                    |                          |                  |               |                   |            |                 |   |
| 0x0005                                                                             | _Identifiant du modèle_  | Personnage       | 0 – 32 octets | Lecture seulement | (Modèle    | Ô               |   |
| Chaîne                                                                             | Version)                 |                  |               |                   |            |                 |   |
|                                                                                    |                          |                  |               |                   |            |                 |   |
| 0x0006                                                                             | _CodeDate_               | Personnage       | 0 – 16 octets | Lecture seulement |            | Ô               |   |
| Chaîne                                                                             |                          |                  |               |                   |            |                 |   |
|                                                                                    |                          |                  |               |                   |            |                 |   |
| 0x0007                                                                             | _Source d'énergie_       | 8 bits           | 0x00 –0xff    | Lecture seulement |            | M.              |   |
| 0x0010                                                                             | _EmplacementDescription_ | Personnage       | 0 – 32 octets | Lire écrire       |            | Ô               |   |
| Chaîne                                                                             |                          |                  |               |                   |            |                 |   |
|                                                                                    |                          |                  |               |                   |            |                 |   |
| 0x0011                                                                             | _Environnement physique_ | 8 bits           | 0x00 –0xff    | Lire écrire       | 0x00       | Ô               |   |
| 0x0012                                                                             | _Appareil activé_        | Booléen          | 0x00 –0x01    | Lire écrire       | 0x01       | Ô               |   |
| 0xFFFD                                                                             | _Révision du cluster_    | uint16           | 0x0001-0xFFFE | Lecture seulement | 1          | M.              |   |
| _**Attribut des informations sur le cluster de configuration de l'alimentation**_ |                          |                  |               |                   |            |                 |   |

| **Identifier**                                               | **Nom**                       | **Taper** | **Gamme**     | **Accéder**       | **Défaut** | **Obligatoire** |   |
| ------------------------------------------------------------ | ----------------------------- | --------- | ------------- | ----------------- | ---------- | --------------- | - |
| **/ Facultatif**                                             |                               |           |               |                   |            |                 |   |
|                                                              |                               |           |               |                   |            |                 |   |
| 0x0035                                                       | _Masque d'alarme de batterie_ | carte8    | 0b0000 000x   | Lire écrire       | 0b0000     | Ô               |   |
| 0000                                                         |                               |           |               |                   |            |                 |   |
|                                                              |                               |           |               |                   |            |                 |   |
| 0xFFFD                                                       | _Révision du cluster_         | uint16    | 0x0001-0xFFFE | Lecture seulement | 1          | M.              |   |
| _**Attribut des informations d'identification du cluster**_ |                               |           |               |                   |            |                 |   |

| **Identifier**                                                 | **Nom**                                       |             |                   | **Taper**                   |                                                | **Gamme**                     |                   |                   | **Accéder** |                 | **Défaut** | **Obligatoire** |   |
| -------------------------------------------------------------- | --------------------------------------------- | ----------- | ----------------- | --------------------------- | ---------------------------------------------- | ----------------------------- | ----------------- | ----------------- | ----------- | --------------- | ---------- | --------------- | - |
|                                                                |                                               |             |                   |                             |                                                | **/ Facultatif**              |                   |                   |             |                 |            |                 |   |
|                                                                |                                               |             |                   |                             |                                                |                               |                   |                   |             |                 |            |                 |   |
| 0x0000                                                         | _Identifier l'heure_                          |             | 16 bits non signé |                             | 0x00 –0xffff                                   |                               | Lire écrire       |                   | 0x0000      | M.              |            |                 |   |
|                                                                |                                               | entier      |                   |                             |                                                |                               |                   |                   |             |                 |            |                 |   |
|                                                                |                                               |             |                   |                             |                                                |                               |                   |                   |             |                 |            |                 |   |
| 0xFFFD                                                         | _Révision du cluster_                         |             |                   | uint16                      |                                                | 0x0001-0xFFFE                 |                   | Lecture seulement | 1           | M.              |            |                 |   |
| _**Attribut des informations sur le cluster de thermostats**_ |                                               |             |                   |                             |                                                |                               |                   |                   |             |                 |            |                 |   |
|                                                                |                                               |             |                   |                             |                                                |                               |                   |                   |             |                 |            |                 |   |
| **Identifier**                                                 | **Nom**                                       |             | **Taper**         |                             | **Gamme**                                      |                               | **Accéder**       |                   | **Défaut**  | **Obligatoire** |            |                 |   |
|                                                                |                                               |             |                   | **/ Facultatif**            |                                                |                               |                   |                   |             |                 |            |                 |   |
|                                                                |                                               |             |                   |                             |                                                |                               |                   |                   |             |                 |            |                 |   |
| 0x0000                                                         | _Température locale_                          |             | 16 bits           |                             | 0x954d – 0x7fff                                |                               | Lecture seulement |                   | 0x0000      | M.              |            |                 |   |
|                                                                |                                               |             |                   |                             |                                                |                               |                   |                   |             |                 |            |                 |   |
| 0x0003                                                         | _AbsMinHeatSetpointLimit_                     |             | 16 bits           |                             | 0x954d – 0x7fff                                |                               | Lecture seulement |                   | 0x01F4      | Ô               |            |                 |   |
| 0x0004                                                         | _AbsMaxHeatSetpointLimit_                     |             | 16 bits           |                             | 0x954d – 0x7fff                                |                               | Lecture seulement |                   | 0x0DAC      | Ô               |            |                 |   |
| 0x0005                                                         | _AbsMinCoolSetpointLimit_                     |             | 16 bits           |                             | 0x954d – 0x7fff                                |                               | Lecture seulement |                   | 0x01F4      | Ô               |            |                 |   |
| 0x0006                                                         | _AbsMinCoolSetpointLimit_                     |             | 16 bits           |                             | 0x954d – 0x7fff                                |                               | Lecture seulement |                   | 0x0DAC      | Ô               |            |                 |   |
|                                                                | _Point de consigne de refroidissement occupé_ |             |                   |                             | _Point de consigne minimum de refroidissement_ |                               | Lire /            |                   |             |                 |            |                 |   |
| 0x0011                                                         |                                               | 16 bits     |                   | _Limite_–_Max Cool_         |                                                |                               | 0x0A28            | M.                |             |                 |            |                 |   |
|                                                                |                                               |             | Écrire            |                             |                                                |                               |                   |                   |             |                 |            |                 |   |
|                                                                |                                               |             |                   |                             |                                                | _Limite du point de consigne_ |                   |                   |             |                 |            |                 |   |
|                                                                |                                               |             |                   |                             |                                                |                               |                   |                   |             |                 |            |                 |   |
|                                                                | _Point de consigne de chauffage occupé_       |             |                   |                             | _Point de consigne de chaleur minimum_         |                               | Lire /            |                   |             |                 |            |                 |   |
| 0x0012                                                         |                                               | 16 bits     |                   | _Limite_–_Chaleur maximale_ |                                                |                               | 0x07D0            | M.                |             |                 |            |                 |   |
|                                                                |                                               |             | Écrire            |                             |                                                |                               |                   |                   |             |                 |            |                 |   |
|                                                                |                                               |             |                   |                             |                                                | _Limite du point de consigne_ |                   |                   |             |                 |            |                 |   |
|                                                                |                                               |             |                   |                             |                                                |                               |                   |                   |             |                 |            |                 |   |
| 0x001B                                                         | _ControlSequenceOfOperatio_                   | 8 bits      |                   | 0x00 – 0x05                 |                                                | Lire /                        |                   | 0x04              | M.          |                 |            |                 |   |
| _n_                                                            |                                               | Énumération |                   |                             | Écrire                                         |                               |                   |                   |             |                 |            |                 |   |
|                                                                |                                               |             |                   |                             |                                                |                               |                   |                   |             |                 |            |                 |   |
| 0x001C                                                         | _Mode Système_                                |             | 8 bits            |                             | 0x00 – 0x09                                    |                               | Lire /            |                   | 0x04        | M.              |            |                 |   |
|                                                                | Énumération                                   |             |                   | Écrire                      |                                                |                               |                   |                   |             |                 |            |                 |   |
|                                                                |                                               |             |                   |                             |                                                |                               |                   |                   |             |                 |            |                 |   |
| 0x0020                                                         | _Début De La Semaine_                         |             | 8 bits            |                             | 0x00 – 0x06                                    |                               | Lire              |                   | -           | Ô               |            |                 |   |
|                                                                | Énumération                                   |             |                   |                             |                                                |                               |                   |                   |             |                 |            |                 |   |
|                                                                |                                               |             |                   |                             |                                                |                               |                   |                   |             |                 |            |                 |   |
| 0x0021                                                         | _Nombre de transitions hebdomadaires_         |             | hiver8            |                             | 0x00 – 0xff                                    |                               | Lire              |                   | N / A       | Ô               |            |                 |   |
|                                                                |                                               |             |                   |                             | 5                                              |                               |                   |                   |             |                 |            |                 |   |

| 0x0022                                                         | _Nombre de transitions quotidiennes_    | hiver8 | 0x00 – 0xff   |   | Lire              | N / A  | Ô                 |             |   |            |                 |   |
| -------------------------------------------------------------- | --------------------------------------- | ------ | ------------- | - | ----------------- | ------ | ----------------- | ----------- | - | ---------- | --------------- | - |
| 0x0023                                                         | _TempératureSetpointHold_               | 8 bits | 0x00 – 0x01   |   | Lire /            | 0x00   | Ô                 |             |   |            |                 |   |
| Énumération                                                    |                                         | Écrire |               |   |                   |        |                   |             |   |            |                 |   |
|                                                                |                                         |        |               |   |                   |        |                   |             |   |            |                 |   |
| 0x0025                                                         | _ThermostatProgrammationExploitation_   | carte8 | 0b00xx xxxx   |   | Lire /            | 0b0000 | Ô                 |             |   |            |                 |   |
| _Fait aussi du son_                                            |                                         | Écrire | 0000          |   |                   |        |                   |             |   |            |                 |   |
|                                                                |                                         |        |               |   |                   |        |                   |             |   |            |                 |   |
| 0xFF01                                                         | _ThermostatMode de contrôle à distance_ | carte8 | 0b0000 000x   |   | Lire /            | 0b0000 | Ô                 |             |   |            |                 |   |
|                                                                | Écrire                                  | 0000   |               |   |                   |        |                   |             |   |            |                 |   |
|                                                                |                                         |        |               |   |                   |        |                   |             |   |            |                 |   |
| 0xFFFD                                                         | _Révision du cluster_                   | uint16 | 0x0001-0xFFFE |   | Lecture seulement | 1      | M.                |             |   |            |                 |   |
| _**Attribut des informations sur le cluster de diagnostics**_ |                                         |        |               |   |                   |        |                   |             |   |            |                 |   |
|                                                                |                                         |        |               |   |                   |        |                   |             |   |            |                 |   |
| **Identifier**                                                 | **Nom**                                 |        | **Taper**     |   | **Gamme**         |        |                   | **Accéder** |   | **Défaut** | **Obligatoire** |   |
|                                                                |                                         |        |               |   | **/ Facultatif**  |        |                   |             |   |            |                 |   |
|                                                                |                                         |        |               |   |                   |        |                   |             |   |            |                 |   |
| 0x011C                                                         | _DernierMessageLQI_                     |        | 8 bits        |   | 0x00 – 0xFF       |        |                   | Lire        |   | 0x00       | Ô               |   |
| 0x011D                                                         | _DernierMessageRSSI_                    |        | 8 bits        |   | 0x00 – 0xFF       |        |                   | Lire        |   | 0x00       | Ô               |   |
| 0xFFFD                                                         | _Révision du cluster_                   |        | uint16        |   | 0x0001-0xFFFE     |        | Lecture seulement |             | 1 | M.         |                 |   |

6
