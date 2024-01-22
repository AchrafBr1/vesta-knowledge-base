# VESTA 184

**Sonde d'ambiance RS-23ZBS**V : R3

**Introduction**

RS-23ZBS est un capteur d'ambiance ZigBee. Il dispose d'une fonction de détection de température et d'humidité pour surveiller votre environnement domestique. Les informations de température et d'humidité seront transmises au coordinateur du réseau ZigBee et affichées sur l'écran LCD du capteur d'ambiance.

Le capteur d'ambiance utilise la technologie ZigBee pour la transmission du signal sans fil. ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

Le capteur d'ambiance sert de périphérique final dans le réseau ZigBee. Il peut être inclus dans le réseau ZigBee pour transmettre un signal lors de l'activation, mais ne peut permettre à aucun autre appareil ZigBee de rejoindre le réseau via le capteur de pièce.

![](<.gitbook/assets/0 (72).jpeg>)

**Identification des pièces**

**1. Écran LCD**

L'écran LCD affiche les informations suivantes :

-   -   Température en Fahrenheit / Celsius
    -   Humidité RH%.
    -   Connectivité réseau ZigBee (![](<.gitbook/assets/1 (64).jpeg>)icône).
    -   État de la batterie faible (icône).
    -   Rétroéclairage LCD allumé : lorsque le bouton de fonction est enfoncé.

1.  **Bouton de fonction**
    -   Appuyez une fois sur le bouton pour :

Envoyez un signal de supervision avec des informations de température/humidité Allumez le rétroéclairage LCD pendant 10 secondes.

-   -   Appuyez et maintenez pendant 10 secondes, puis relâchez pour réinitialiser le capteur d'ambiance.

1.  **Vis de base (ouverture/fermeture du couvercle)**

![](<.gitbook/assets/2 (58).jpeg>)

Lorsque le capot avant est installé sur le capot arrière, ouvrez le capot en desserrant la vis de base et fermez-le de la même manière.

1.  **Cavalier de réglage Fahrenheit/Celcius (JP1)**
    -   Si le cavalier est inséré entre les 2 broches supérieures, l'écran LCD affichera la température en Celsius. (**Défaut de fabrication**)
    -   Si le cavalier est inséré entre les 2 broches inférieures, l'écran LCD affichera la température en Fahrenheit.
2.  **Compartiment à piles**

![](<.gitbook/assets/3 (64).png>)

Le capteur d'ambiance est alimenté par deux piles alcalines AA 1,5 V

1.  **Quatrième de couverture**
2.  **Débouchures de montage mural**

**Caractéristiques**

-   _**Détection de température et d'humidité**_
    -   Le capteur d'ambiance transmettra régulièrement des signaux de température et d'humidité en fonction du réglage. L'intervalle par défaut est de 10 minutes.
    -   Lorsque la température change de +/- 2°C ou que l'humidité change de +/- 10 %, le capteur d'ambiance transmet également un signal.
    -   Le niveau de changement requis pour déclencher la transmission du signal est programmable à l'aide de la commande ZigBee Configure Reporting – paramètre Reportable Change. Les valeurs par défaut sont : Température :**200**pour 2°C.

Humidité:**1000**pour 10%.

1

-   -   Vous pouvez également appuyer une fois sur le bouton de fonction pour transmettre manuellement un signal de température et d'humidité.
    -   La plage de détection de température est d'environ -10 °C à 50 °C (14 °F à 122 °F).
    -   La plage de détection d'humidité est d'environ 10 % à 90 % HR.
-   _**Détection de batterie et de batterie faible**_
    -   Le capteur d'ambiance utilise deux piles alcalines de 1,5 V comme source d'alimentation. Les piles sont incluses dans le colis.
    -   Le capteur d'ambiance est doté d'une fonction de détection de batterie faible. Lorsque la tension de la batterie est faible, le capteur d'ambiance transmet un signal de batterie faible pour avertir l'utilisateur et affiche l'icône de batterie faible sur l'écran LCD.
    -   Lors du changement des piles, après avoir retiré les anciennes piles, appuyez deux fois sur le bouton de fonction pour les décharger complètement avant d'insérer de nouvelles piles.
-   _**Surveillance**_

Le capteur d'ambiance transmettra un signal de supervision ainsi que le signal de température et d'humidité pour signaler régulièrement son état. L'intervalle par défaut est de 10 minutes, qui peut être ajusté en fonction du réglage.

**Configuration du réseau ZigBee**

-   _**Directives relatives aux appareils ZigBee**_

ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

En raison de la structure fondamentale du réseau ZigBee, l'appareil ZigBee recherchera et rejoindra activement le réseau après la mise sous tension. Étant donné que l'exécution d'une tâche de connexion au réseau peut consommer de l'énergie, il est nécessaire de suivre les instructions pour éviter de vider la batterie d'un appareil ZigBee.

-   -   Assurez-vous que votre routeur ou coordinateur réseau ZigBee est sous tension avant d'insérer la batterie dans l'appareil ZigBee.
    -   Assurez-vous que le routeur ou le coordinateur réseau ZigBee est sous tension et à portée lorsqu'un appareil ZigBee est en cours d'utilisation.
    -   Ne retirez pas un appareil ZigBee du routeur ou du coordinateur réseau ZigBee sans retirer la batterie d'un appareil ZigBee.
-   _**Rejoindre le réseau ZigBee**_

En tant qu'appareil ZigBee, le capteur d'ambiance doit rejoindre un réseau ZigBee pour transmettre le signal de température et d'humidité. Veuillez suivre les étapes ci-dessous pour connecter le capteur de pièce au réseau ZigBee.

-   1.  Insérez les piles dans le compartiment à piles pour allumer le capteur d'ambiance.
    2.  Après la mise sous tension, maintenez enfoncé le bouton Fonction pendant 10 secondes, puis relâchez-le pour rejoindre le réseau. Veuillez vous assurer que la fonction d'autorisation de connexion sur le routeur ou le coordinateur de votre réseau ZigBee est activée.
    3.  Si le capteur d'ambiance rejoint avec succès un réseau ZigBee, l'icône de connectivité réseau ZigBee s'affichera sur l'écran LCD.
    4.  Après avoir rejoint le réseau ZigBee, le capteur d'ambiance sera automatiquement enregistré dans le réseau. Veuillez vérifier votre coordinateur ZigBee, votre panneau de contrôle du système ou votre CIE (équipement de contrôle et d'indication) pour confirmer si l'adhésion et l'enregistrement ont réussi.
    5.  Une fois l'accès au réseau effectué et l'enregistrement réussi, si le capteur d'ambiance perd la connexion avec le panneau de commande ou si le panneau de commande est éteint, l'icône de connectivité réseau ZigBee sur l'écran LCD du capteur d'ambiance s'éteindra au bout d'une ou deux minutes.
    6.  Si l'adhésion au réseau et l'enregistrement échouent, l'icône de connectivité réseau ZigBee ne s'affichera pas. Veuillez vérifier votre coordinateur de réseau ZigBee, votre panneau de commande ou les paramètres CIE pour vous assurer que la fonction d'autorisation de connexion est disponible, puis utilisez la fonction de réinitialisation d'usine ci-dessous pour rejoindre le réseau ZigBee.
-   _**Suppression d'un appareil du réseau ZigBee (réinitialisation d'usine)**_

Pour supprimer le capteur d'ambiance du réseau ZigBee actuel, l'appareil doit être réinitialisé aux paramètres d'usine pour terminer la suppression de l'appareil. La fonction de réinitialisation d'usine effacera l'appareil de ses informations de configuration stockées et invitera le capteur d'ambiance à rechercher un nouveau réseau ZigBee.

**Avant de retirer l'appareil, assurez-vous que le capteur d'ambiance se trouve dans la plage actuelle du signal du réseau ZigBee.**

1.  Appuyez et maintenez le bouton de fonction pendant 10 secondes, puis relâchez le bouton pour réinitialiser le capteur d'ambiance.
2.  Lors de la réinitialisation, le capteur d'ambiance effacera les paramètres réseau ZigBee actuels et transmettra le signal à

2

Coordinateur ZigBee pour se retirer du réseau ZigBee actuel. Il recherchera ensuite à nouveau activement le réseau ZigBee disponible et rejoindra automatiquement le réseau.

**Installation**

-   _**Montage du capteur d'ambiance**_

Pour une meilleure qualité d'affichage LCD, le capteur d'ambiance doit être monté à environ 5° au-dessus du niveau des yeux.

-   Montage à vis.

Lors du montage avec des vis, assurez-vous d'utiliser uniquement les vis fournies dans l'emballage par le fabricant d'origine, car des vis inappropriées peuvent endommager l'intérieur de l'appareil.

-   1.  Retirez le capot avant à l'aide d'un tournevis.
    2.  Brisez les découpes sur la couverture arrière.
    3.  En utilisant les trous comme gabarit, percez des trous dans la surface
    4.  Insérez les chevilles murales si vous fixez dans du plâtre ou de la brique
    5.  Vissez le couvercle arrière dans les chevilles murales
    6.  Revissez le capot avant sur le capot arrière.
-   _**Utilisation du capteur d'ambiance avec le routeur ZigBee**_

_**NOTE IMPORTANTE**_

Si l'emplacement d'installation du capteur d'ambiance est éloigné du panneau de commande de votre système et nécessite des routeurs ZigBee pour améliorer la force du signal.**NE PAS**utilisez un routeur ZigBee sans batterie de secours. Un routeur ZigBee sans batterie sera mis hors tension en cas de panne de courant et le capteur d'ambiance connecté au routeur perdra la connexion avec le réseau ZigBee. Vous devez planifier l'emplacement d'installation de votre capteur d'ambiance en utilisant uniquement le routeur ZigBee avec batterie de secours.

**Annexe(Pour les développeurs uniquement.)**

-   _**ID du groupe de capteurs de pièce**_

**ID de l'appareil : capteur de température 0x0302**

**Point de terminaison : 0x01**

| **Du côté serveur**                      |                 | **Côté client** |
| ---------------------------------------- | --------------- | --------------- |
|                                          |                 |                 |
|                                          | **Obligatoire** |                 |
|                                          |                 |                 |
| De base (0x0000)                         |                 | _Aucun_         |
|                                          |                 |                 |
| Identifier (0x0003)                      |                 |                 |
|                                          |                 |                 |
|                                          | **Facultatif**  |                 |
|                                          |                 |                 |
| Configuration de l'alimentation (0x0001) |                 | _Aucun_         |
|                                          |                 |                 |
| Mesure de température (0x0402)           |                 |                 |
|                                          |                 |                 |
| Mesure d'humidité relative (0x0405)      |                 |                 |
|                                          |                 |                 |

|                 | _**Attribut des informations de base sur le cluster**_ |            |   |               |                   |            |                 |   |   |
| ---------------- | ------------------------------------------------------ | ---------- | - | ------------- | ----------------- | ---------- | --------------- | - | - |
|                  |                                                        |            |   |               |                   |            |                 |   |   |
| **Identifier**   | **Nom**                                                | **Taper**  |   | **Gamme**     | **Accéder**       | **Défaut** | **Obligatoire** |   |   |
|                  | **/ Facultatif**                                       |            |   |               |                   |            |                 |   |   |
|                  |                                                        |            |   |               |                   |            |                 |   |   |
| 0x0000           | _Version ZCL_                                          | Non signé  |   | 0x00 –0xff    | Lecture seulement | 0x01       | M               |   |   |
| Entier de 8 bits |                                                        |            |   |               |                   |            |                 |   |   |
|                  |                                                        |            |   |               |                   |            |                 |   |   |
| 0x0001           | Version de l'application                               | Non signé  |   | 0x00 –0xff    | Lecture seulement | 0x00       | Ô               |   |   |
| Entier de 8 bits |                                                        |            |   |               |                   |            |                 |   |   |
|                  |                                                        |            |   |               |                   |            |                 |   |   |
| 0x0003           | _Version matérielle_                                   | Non signé  |   | 0x00 –0xff    | Lecture seulement | 0          | Ô               |   |   |
| Entier de 8 bits |                                                        |            |   |               |                   |            |                 |   |   |
|                  |                                                        |            |   |               |                   |            |                 |   |   |
| 0x0004           | _Nom du Fabricant_                                     | Personnage |   | 0 – 32 octets | Lecture seulement | Climax     | Ô               |   |   |
| Chaîne           |                                                        | Technology |   |               |                   |            |                 |   |   |
|                  |                                                        |            |   |               |                   |            |                 |   |   |
| 0x0005           | _Identifiant du modèle_                                | Personnage |   | 0 – 32 octets | Lecture seulement | (Modèle    | Ô               |   |   |
| Chaîne           |                                                        | Version)   |   |               |                   |            |                 |   |   |
|                  |                                                        |            |   |               |                   |            |                 |   |   |
| 0x0006           | _DateCode_                                             | Personnage |   | 0 – 16 octets | Lecture seulement |            | Ô               |   |   |
| Chaîne           |                                                        |            |   |               |                   |            |                 |   |   |
|                  |                                                        |            |   |               |                   |            |                 |   |   |
| 0x0007           | _Source d'énergie_                                     | 8 bits     |   | 0x00 –0xff    | Lecture seulement |            | M               |   |   |
| 0x0010           | _EmplacementDescription_                               | Personnage |   | 0 – 32 octets | Lire /            |            | Ô               |   |   |
| Chaîne           |                                                        | Écrire     |   |               |                   |            |                 |   |   |
|                  |                                                        |            |   |               |                   |            |                 |   |   |
| 0x0011           | _Environnement physique_                               | 8 bits     |   | 0x00 –0xff    | Lire /            | 0x00       | Ô               |   |   |
|                  | Écrire                                                 |            |   |               |                   |            |                 |   |   |
|                  |                                                        |            |   |               |                   |            |                 |   |   |
|                  |                                                        |            |   | 3             |                   |            |                 |   |   |

0x0012

_Appareil activé_

Booléen

0x00 –0x01

Lire /

Écrire

0x01

M

-   _**Attribut des informations d'identification du cluster**_

| **Identifier**    | **Nom**              | **Taper** | **Gamme**    | **Accéder** | **Défaut** | **Obligatoire** |   |
| ----------------- | -------------------- | --------- | ------------ | ----------- | ---------- | --------------- | - |
| **/ Facultatif**  |                      |           |              |             |            |                 |   |
|                   |                      |           |              |             |            |                 |   |
| 0x0000            | _Identifier l'heure_ | Non signé | 0x00 –0xffff | Lire /      | 0x0000     | M               |   |
| Entier de 16 bits | Écrire               |           |              |             |            |                 |   |
|                   |                      |           |              |             |            |                 |   |

_**Attribut des informations sur le cluster de configuration de l'alimentation**_

| **Identifier**   | **Nom**                       | **Taper**     | **Gamme** | **Accéder** | **Défaut** | **Obligatoire** |   |
| ---------------- | ----------------------------- | ------------- | --------- | ----------- | ---------- | --------------- | - |
| **/ Facultatif** |                               |               |           |             |            |                 |   |
|                  |                               |               |           |             |            |                 |   |
| 0x0035           | _Masque d'alarme de batterie_ | Bitmap 8 bits | 0000 000x | Lire /      | 0000 0000  | Ô               |   |
| Écrire           |                               |               |           |             |            |                 |   |
|                  |                               |               |           |             |            |                 |   |

_**Attribut des informations sur le cluster de mesure de la température**_

| **Identifier**   | **Nom**                                                                         | **Taper**         | **Gamme**           | **Accéder** | **Défaut** | **Obligatoire** |   |   |
| ---------------- | ------------------------------------------------------------------------------- | ----------------- | ------------------- | ----------- | ---------- | --------------- | - | - |
| **/ Facultatif** |                                                                                 |                   |                     |             |            |                 |   |   |
|                  |                                                                                 |                   |                     |             |            |                 |   |   |
| 0x0000           | La valeur de mesure                                                             | Signé 16 bits     | ValeurMinMeasured à | Lire        | 0x00       | M               |   |   |
| Entier           | Valeur MaxMeasured                                                              | seulement         |                     |             |            |                 |   |   |
|                  |                                                                                 |                   |                     |             |            |                 |   |   |
|                  |                                                                                 |                   |                     |             |            |                 |   |   |
| 0x0001           | Valeur MinMeasured                                                              | Signé 16 bits     | 0x954d – 0x7ffe     | Lire        | -1000      | M               |   |   |
| Entier           | seulement                                                                       | (-10℃)            |                     |             |            |                 |   |   |
|                  |                                                                                 |                   |                     |             |            |                 |   |   |
| 0x0002           | Valeur MaxMeasured                                                              | Signé 16 bits     | 0x954e – 0x7fff     | Lire        | 5000       | M               |   |   |
| Entier           | seulement                                                                       | (50℃)             |                     |             |            |                 |   |   |
|                  |                                                                                 |                   |                     |             |            |                 |   |   |
| 0x0003           | Tolérance                                                                       | 16 bits non signé | 0x0000 – 0x0800     | Lire        | 100        | Ô               |   |   |
| Entier           | seulement                                                                       | (1℃)              |                     |             |            |                 |   |   |
|                  |                                                                                 |                   |                     |             |            |                 |   |   |
|                 | _**Attribut des informations sur le cluster de mesure de l'humidité relative**_ |                   |                     |             |            |                 |   |   |
|                  |                                                                                 |                   |                     |             |            |                 |   |   |
| **Identifier**   | **Nom**                                                                         | **Taper**         | **Gamme**           | **Accéder** | **Défaut** | **Obligatoire** |   |   |
| **/ Facultatif** |                                                                                 |                   |                     |             |            |                 |   |   |
|                  |                                                                                 |                   |                     |             |            |                 |   |   |
| 0x0000           | La valeur de mesure                                                             | 16 bits non signé | ValeurMinMeasured à | Lire        |            | M               |   |   |
| Entier           | Valeur MaxMeasured                                                              | seulement         |                     |             |            |                 |   |   |
|                  |                                                                                 |                   |                     |             |            |                 |   |   |
|                  |                                                                                 |                   |                     |             |            |                 |   |   |
| 0x0001           | Valeur MinMeasured                                                              | 16 bits non signé | 0x0000 – 0x270f     | Lire        | 0          | M               |   |   |
| Entier           | seulement                                                                       | (0%)              |                     |             |            |                 |   |   |
|                  |                                                                                 |                   |                     |             |            |                 |   |   |
| 0x0002           | Valeur MaxMeasured                                                              | 16 bits non signé | 0x0001 – 0x2710     | Lire        | 10000      | M               |   |   |
| C'est            | Entier                                                                          | seulement         | (100%)              |             |            |                 |   |   |
|                  |                                                                                 |                   |                     |             |            |                 |   |   |
| 0x0003           | Tolérance                                                                       | 16 bits non signé | 0x0000 – 0x0800     | Lire        | 200        | Ô               |   |   |
| Entier           | seulement                                                                       | (2%)              |                     |             |            |                 |   |   |
|                  |                                                                                 |                   |                     |             |            |                 |   |   |

4
