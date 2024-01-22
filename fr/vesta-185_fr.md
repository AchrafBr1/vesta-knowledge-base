# VESTA 185

**Capteur de lumière ambiante, d'humidité et de température LMHT-1ZBS**

**Introduction**

LMHT-1ZBS est un capteur de lumière ambiante, d'humidité et de température ZigBee. Il surveille votre environnement domestique et transmet l'éclairement (lux), l'humidité et la température mesurés au coordinateur du réseau ZigBee.

Le capteur utilise la technologie ZigBee pour la transmission du signal sans fil. ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

Le capteur sert de périphérique final dans le réseau ZigBee. Il peut être inclus dans le réseau ZigBee pour transmettre un signal lors de l'activation, mais ne peut permettre à aucun autre appareil ZigBee de rejoindre le réseau via le capteur.

**Identification des pièces**

1.  **Capteur de lumière/indicateur LED**
    -   **Clignote une fois :**Retour aux paramètres d'usine
    -   **Clignote deux fois :**Une fois que le capteur a rejoint avec succès un réseau ZigBee.
    -   **Clignote 3 fois :**Batterie insérée.
    -   **Clignote 5 fois :**Batterie faible détectée lors de l'insertion de la batterie.
    -   **Clignote une fois toutes les 20 minutes :**Le capteur a perdu la connexion à son réseau ZigBee actuel.
2.  **Capteur de température**
3.  **Compartiment à piles**
4.  **Bouton de fonction**
    -   Appuyez une fois pour envoyer un signal au coordinateur.
    -   Appuyez et maintenez pendant 10 secondes pour réinitialiser l'appareil.

![](<.gitbook/assets/0 (73).jpeg>)

**Caractéristiques**

-   _**Surveillance de l'éclairage, de l'humidité et de la température**_
    -   Le capteur mesure l'éclairement, l'humidité et la température pour transmettre régulièrement les données mesurées au coordinateur du réseau ZigBee.

La lecture de l'éclairement est transmise toutes les 30 minutes.

La lecture de l'humidité et de la température est transmise toutes les 10 minutes. Le capteur transmettra également automatiquement le signal lorsque :

-   -   -   La température change de +/- 2°C.
        -   L'humidité change de +/- 10%.
        -   Lorsque l'éclairement actuel change de +/- 10 %.
        -   Le niveau de changement requis pour déclencher la transmission du signal est programmable à l'aide de la commande ZigBee Configure Reporting – paramètre Reportable Change. Les valeurs par défaut sont :

Température:**200**pour 2°C.

Humidité:**1000**pour 10%.

Éclairement :**10**pour 10%.

-   -   Vous pouvez également appuyer une fois sur le bouton de fonction pour transmettre manuellement la lecture actuelle.
-   _**Détection de batterie et de batterie faible**_
    -   Le capteur utilise une pile au lithium CR123A 3V comme source d'alimentation.
    -   Le capteur dispose d'une fonction de détection de batterie faible. Lorsque la tension de la batterie est faible, le capteur transmet le signal de batterie faible au coordinateur du réseau ZigBee.
    -   Lors du changement de batterie, après avoir retiré les anciennes batteries, appuyez deux fois sur le bouton de fonction pour la décharger complètement avant d'insérer une nouvelle batterie.
    -   Si une faible tension de batterie est détectée lors de l'insertion d'une nouvelle batterie, l'indicateur LED clignote 5 fois.

1

-   _**Surveillance**_

Le capteur transmettra un signal de supervision avec le signal de lecture pour signaler régulièrement son état. L'intervalle par défaut est de 30 minutes, qui peut être ajusté en fonction du réglage.

**Configuration du réseau ZigBee**

-   _**Directives relatives aux appareils ZigBee**_

ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

En raison de la structure fondamentale du réseau ZigBee, l'appareil ZigBee recherchera et rejoindra activement le réseau après la mise sous tension. Étant donné que l'exécution d'une tâche de connexion au réseau peut consommer de l'énergie, il est nécessaire de suivre les instructions pour éviter de vider la batterie d'un appareil ZigBee.

-   -   Assurez-vous que votre routeur ou coordinateur réseau ZigBee est sous tension avant d'insérer la batterie dans l'appareil ZigBee.
    -   Assurez-vous que le routeur ou le coordinateur réseau ZigBee est sous tension et à portée lorsqu'un appareil ZigBee est en cours d'utilisation.
    -   Ne retirez pas un appareil ZigBee du routeur ou du coordinateur réseau ZigBee sans retirer la batterie d'un appareil ZigBee.
-   _**Rejoindre le réseau ZigBee**_

En tant qu'appareil ZigBee, le capteur doit rejoindre un réseau ZigBee pour transmettre le signal. Veuillez suivre les étapes ci-dessous pour connecter le capteur au réseau ZigBee.

-   1.  Détachez le couvercle supérieur et l’ensemble de base et insérez la batterie.
    2.  Appuyez et maintenez enfoncé le bouton de fonction pendant 10 secondes pendant que le capteur se réinitialise (la LED clignote une fois) et commence à rechercher le réseau ZigBee existant. Veuillez vous assurer que la fonction d'autorisation de rejoindre sur le routeur ou le coordinateur de votre réseau ZigBee est activée.
    3.  Si le capteur rejoint avec succès un réseau ZigBee, l'indicateur LED clignote deux fois pour confirmer.
    4.  Après avoir rejoint le réseau ZigBee, le capteur sera automatiquement enregistré dans le réseau. Veuillez vérifier votre coordinateur ZigBee, votre panneau de contrôle du système ou votre CIE (équipement de contrôle et d'indication) pour confirmer si l'adhésion et l'enregistrement ont réussi.
    5.  Après avoir rejoint le réseau ZigBee, si le capteur perd la connexion avec le réseau ZigBee actuel, la LED clignotera toutes les 20 minutes pour l'indiquer. Veuillez vérifier l'état de votre réseau ZigBee et la plage du signal du capteur pour corriger la situation.
-   _**Suppression d'un appareil du réseau ZigBee (réinitialisation d'usine)**_

Pour supprimer l'appareil du réseau ZigBee actuel, le capteur doit être mis en configuration d'usine pour terminer la suppression de l'appareil. La fonction de réinitialisation d'usine effacera l'appareil de ses informations de configuration stockées et invitera le capteur à rechercher un nouveau réseau ZigBee.

**Avant de retirer l'appareil, assurez-vous que le capteur se trouve dans la plage actuelle du signal du réseau ZigBee.**

1.  Appuyez et maintenez le bouton de fonction pendant 10 secondes, puis relâchez le bouton pour réinitialiser le capteur.
2.  Lors de la réinitialisation, le capteur effacera les paramètres réseau ZigBee actuels et transmettra le signal au coordinateur ZigBee pour se retirer du réseau ZigBee actuel. Il recherchera ensuite à nouveau activement le réseau ZigBee disponible et rejoindra automatiquement le réseau.

**Installation**

-   _**Montage du capteur**_

Le capteur peut être monté de deux manières : montage auto-adhésif ou par vis.

**Montage autocollant**

1.  Nettoyer la surface avec un dégraissant adapté.
2.  Retirez le revêtement de protection d'un côté du tampon adhésif double face et appliquez-le fermement à l'arrière de l'appareil.
3.  Retirez l'autre revêtement et placez/appuyez fermement sur l'appareil à l'emplacement souhaité.

![](<.gitbook/assets/1 (65).jpeg>)

N'utilisez pas la méthode de montage autocollante sur des surfaces mal peintes et/ou rugueuses.

**Montage à vis**

La base du capteur comporte deux alvéoles de vis, où le plastique est plus fin à des fins de montage. Pour monter le capteur :

1.  Détachez l'ensemble couvercle supérieur et base en desserrant la vis de fixation du couvercle à l'aide d'un tournevis Philips.
2.  Brisez les trous sur la base.

2

-   1.  Utilisez les trous comme gabarit pour percer deux trous et insérer les chevilles murales.
    2.  Vissez la base dans les chevilles murales.
    3.  Remettez le capot supérieur sur la base en accrochant la base au crochet de fixation et en poussant le capot vers la base.
    4.  Fixez et revissez le capot supérieur sur sa base à l'aide d'un tournevis Philips.
-   _**Utilisation du capteur avec le routeur ZigBee**_

_**NOTE IMPORTANTE**_

Si l'emplacement d'installation du capteur est éloigné du panneau de commande de votre système et nécessite des routeurs ZigBee pour améliorer la force du signal.**NE PAS**utilisez un routeur ZigBee sans batterie de secours. Un routeur ZigBee sans batterie sera mis hors tension en cas de panne de courant et le capteur connecté au routeur perdra la connexion avec le réseau ZigBee. Vous devez planifier l'emplacement d'installation de votre capteur en utilisant uniquement le routeur ZigBee avec batterie de secours.

-   _**Mise à niveau du micrologiciel OTA (pour la version OTA uniquement)**_

Le capteur de lumière ambiante, d'humidité et de température prend en charge la fonction de mise à niveau du micrologiciel OTA via le réseau ZigBee, qui peut être lancée à partir du coordinateur du réseau ZigBee. Suivez les étapes ci-dessous pour effectuer la mise à niveau du micrologiciel OTA.**Étape 1.**Vous devez accéder à votre coordinateur ZigBee pour effectuer la mise à niveau du micrologiciel en direct.

**Étape 2.**Sur la page Web de configuration, sélectionnez l'appareil que vous souhaitez mettre à niveau et sélectionnez le nouveau firmware ZigBee fourni. Veuillez vous référer au manuel d'utilisation du coordinateur ZigBee pour plus de détails.

**Étape 3.**Appuyez sur « OK » pour démarrer le processus de mise à niveau et la LED continuera de clignoter. Pendant le processus OTA, veuillez faire

n'effectuez aucune autre action et n'éteignez pas le panneau.

**Étape 4.**La durée d'une mise à niveau prendra environ 20 à 30 minutes. Veuillez noter que la durée peut varier en fonction de la taille du fichier ou de la distance entre votre accessoire et le coordinateur.

**Étape 5.**Attendez que le micrologiciel termine la mise à jour. Lorsque la progression atteint 100 %, l'appareil se réinitialise automatiquement. Vous pouvez également actualiser à nouveau la page Web pour vous assurer que le micrologiciel de l'appareil est correctement mis à jour avec la version la plus récente affichée.

**annexe**

**(Les informations de l'annexe sont réservées aux développeurs.)**

-   _**ID du groupe de capteurs de lumière**_

**ID de l'appareil : capteur de lumière 0x0106**

**Point de terminaison : 0x01**

| **Du côté serveur**                      |                 | **Côté client**     |
| ---------------------------------------- | --------------- | ------------------- |
|                                          |                 |                     |
|                                          | **Obligatoire** |                     |
|                                          |                 |                     |
| De base (0x0000)                         |                 | De base (0x0000)    |
|                                          |                 |                     |
| Identifier (0x0003)                      |                 | Identifier (0x0003) |
|                                          |                 |                     |
| Mesure d'éclairement (0x0400)            |                 |                     |
|                                          |                 |                     |
|                                          | **Facultatif**  |                     |
|                                          |                 |                     |
| Configuration de l'alimentation (0x0001) |                 | _Aucun_             |
|                                          |                 |                     |
| Mesure de température (0x0402)           |                 |                     |
|                                          |                 |                     |
| Mesure d'humidité relative (0x0405)      |                 |                     |
|                                          |                 |                     |

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
| 0x0006           | _DateCode_               | Personnage       | 0 – 16 octets | Lire        |                  | Ô               |   |
| Chaîne           | seulement                |                  |               |             |                  |                 |   |
|                  |                          |                  |               |             |                  |                 |   |
| 0x0007           | _Source d'énergie_       | 8 bits           | 0x00 –0xff    | Lire        |                  | M.              |   |
| seulement        |                          |                  |               |             |                  |                 |   |
|                  |                          |                  |               |             |                  |                 |   |
| 0x0010           | _EmplacementDescription_ | Personnage       | 0 – 32 octets | Lire /      |                  | Ô               |   |
| Chaîne           | Écrire                   |                  |               |             |                  |                 |   |
|                  |                          |                  |               |             |                  |                 |   |
|                  |                          |                  | 3             |             |                  |                 |   |

| 0x0011 | _Environnement physique_ | 8 bits  | 0x00 –0xff | Lire / | 0x00 | Ô  |   |
| ------ | ------------------------ | ------- | ---------- | ------ | ---- | -- | - |
| Écrire |                          |         |            |        |      |    |   |
|        |                          |         |            |        |      |    |   |
| 0x0012 | _Appareil activé_        | Booléen | 0x00 –0x01 | Lire / | 0x01 | M. |   |
| Écrire |                          |         |            |        |      |    |   |
|        |                          |         |            |        |      |    |   |

_**Attribut des informations d'identification du cluster**_

| **Identifier**    | **Nom**              | **Taper** | **Gamme**    | **Accéder** | **Défaut** | **Obligatoire** |   |
| ----------------- | -------------------- | --------- | ------------ | ----------- | ---------- | --------------- | - |
| **/ Facultatif**  |                      |           |              |             |            |                 |   |
|                   |                      |           |              |             |            |                 |   |
| 0x0000            | _Identifier l'heure_ | Non signé | 0x00 –0xffff | Lire /      | 0x0000     | M.              |   |
| Entier de 16 bits | Écrire               |           |              |             |            |                 |   |
|                   |                      |           |              |             |            |                 |   |

_**Attribut des informations sur le cluster de configuration de l'alimentation**_

| **Identifier**   | **Nom**                       | **Taper** | **Gamme** | **Accéder** | **Défaut** | **Obligatoire** |   |
| ---------------- | ----------------------------- | --------- | --------- | ----------- | ---------- | --------------- | - |
| **/ Facultatif** |                               |           |           |             |            |                 |   |
|                  |                               |           |           |             |            |                 |   |
| 0x0035           | _Masque d'alarme de batterie_ | 8 bits    | 0000 000x | Lire /      | 0000 0000  | Ô               |   |
| image bitmap     | Écrire                        |           |           |             |            |                 |   |
|                  |                               |           |           |             |            |                 |   |

_**Attribut des informations sur le cluster de mesure de l'éclairement**_

| **Identifier**   | **Nom**               | **Taper**          | **Gamme**             | **Accéder** | **Default** | **Obligatoire** |   |
| ---------------- | --------------------- | ------------------ | --------------------- | ----------- | ----------- | --------------- | - |
| **/ Facultatif** |                       |                    |                       |             |             |                 |   |
|                  |                       |                    |                       |             |             |                 |   |
|                  |                       | Signé 16 bits      | Valeur MinMeasured    | Lire        |             |                 |   |
| 0x0000           | _La valeur de mesure_ | à                  | 0x00                  | M.          |             |                 |   |
| Entier           | seulement             |                    |                       |             |             |                 |   |
|                  |                       | Valeur MaxMeasured |                       |             |             |                 |   |
|                  |                       |                    |                       |             |             |                 |   |
| 0x0001           | _Valeur MinMeasured_  | Signé 16 bits      | 0x0001 - 0xffffd      | Lire        | 1           | M.              |   |
| Entier           | seulement             |                    |                       |             |             |                 |   |
|                  |                       |                    |                       |             |             |                 |   |
| 0x0002           | _Valeur MaxMeasured_  | Signé 16 bits      | Valeur MinMeasured +1 | Lire        | 52742       | M.              |   |
| Entier           | - 0xffffe             | seulement          |                       |             |             |                 |   |
|                  |                       |                    |                       |             |             |                 |   |

-   _**Attribut des informations sur le cluster de mesure de la température**_

| **Identifier**   | **Nom**             | **Taper**          | **Gamme**          | **Accéder** | **Défaut** | **Obligatoire** |   |
| ---------------- | ------------------- | ------------------ | ------------------ | ----------- | ---------- | --------------- | - |
| **/ Facultatif** |                     |                    |                    |             |            |                 |   |
|                  |                     |                    |                    |             |            |                 |   |
|                  |                     | Signé 16 bits      | Valeur MinMeasured | Lire        |            |                 |   |
| 0x0000           | La valeur de mesure | à                  | 0x00               | M.          |            |                 |   |
| Entier           | seulement           |                    |                    |             |            |                 |   |
|                  |                     | Valeur MaxMeasured |                    |             |            |                 |   |
|                  |                     |                    |                    |             |            |                 |   |
| 0x0001           | Valeur MinMeasured  | Signé 16 bits      | 0x954d – 0x7ffe    | Lire        | -1000      | M.              |   |
| Entier           | seulement           | (-10℃)             |                    |             |            |                 |   |
|                  |                     |                    |                    |             |            |                 |   |
| 0x0002           | Valeur MaxMeasured  | Signé 16 bits      | 0x954e – 0x7fff    | Lire        | 5000       | M.              |   |
| Entier           | seulement           | (50℃)              |                    |             |            |                 |   |
|                  |                     |                    |                    |             |            |                 |   |
| 0x0003           | Tolérance           | 16 bits non signé  | 0x0000 – 0x0800    | Lire        | 100        | Ô               |   |
| Entier           | seulement           | (1℃)               |                    |             |            |                 |   |
|                  |                     |                    |                    |             |            |                 |   |

-   _**Attribut des informations sur le cluster de mesure de l'humidité relative**_

| **Identifier**   | **Nom**             | **Taper**          | **Gamme**          | **Accéder** | **Défaut** | **Obligatoire** |   |
| ---------------- | ------------------- | ------------------ | ------------------ | ----------- | ---------- | --------------- | - |
| **/ Facultatif** |                     |                    |                    |             |            |                 |   |
|                  |                     |                    |                    |             |            |                 |   |
|                  |                     | 16 bits non signé  | Valeur MinMeasured | Lire        |            |                 |   |
| 0x0000           | La valeur de mesure | à                  |                    | M.          |            |                 |   |
| Entier           | seulement           |                    |                    |             |            |                 |   |
|                  |                     | Valeur MaxMeasured |                    |             |            |                 |   |
|                  |                     |                    |                    |             |            |                 |   |
| 0x0001           | Valeur MinMeasured  | 16 bits non signé  | 0x0000 – 0x270f    | Lire        | 0          | M.              |   |
| Entier           | seulement           | (0%)               |                    |             |            |                 |   |
|                  |                     |                    |                    |             |            |                 |   |
| 0x0002           | Valeur MaxMeasured  | 16 bits non signé  | 0x0001 – 0x2710    | Lire        | 10000      | M.              |   |
| Entier           | seulement           | (100%)             |                    |             |            |                 |   |
|                  |                     |                    |                    |             |            |                 |   |
| 0x0003           | Tolérance           | 16 bits non signé  | 0x0000 – 0x0800    | Lire        | 200        | Ô               |   |
| Entier           | seulement           | (2%)               |                    |             |            |                 |   |
|                  |                     |                    |                    |             |            |                 |   |

4
