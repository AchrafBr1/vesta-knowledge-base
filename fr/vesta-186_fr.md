# VESTA 186

**Série de commutateurs d'alimentation PSS-29ZBS(R) / PSM-29ZBS(R)**

**Introduction**

La série Power Switch comprend les modèles suivants :

**PSS-29ZBS :**Interrupteur d'alimentation ZigBee

**PSS-29ZBSR :**Interrupteur d'alimentation ZigBee avec fonction routeur

**PSM-29ZBS :**Interrupteur d'alimentation ZigBee avec compteur

**PSM-29ZBSR :**Interrupteur d'alimentation ZigBee avec fonction compteur et routeur

Les interrupteurs d'alimentation sont capables de recevoir des signaux sans fil du coordinateur du réseau ZigBee pour allumer/éteindre les appareils qui y sont connectés.

Le Power Switch utilise la technologie ZigBee pour la transmission du signal sans fil. ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

Les modèles dotés de fonctions de compteur (PSM-29ZBS / PSM-29ZBSR) ont la fonctionnalité supplémentaire de suivre la consommation d'énergie grâce au compteur d'énergie intégré et de transmettre régulièrement les données au coordinateur.

Les modèles avec fonction routeur (PSS-29ZBSR / PSM-29ZBSR) servent également de routeur dans le réseau ZigBee. Après avoir été inclus dans le réseau ZigBee, il permet à d'autres appareils ZigBee de rejoindre le réseau via le Power Switch.

| **Numéro de modèle.** | **Mètre** | **Routeur ZigBee** |
| --------------------- | --------- | ------------------ |
|                       |           |                    |
| **PSS-29ZBS**         | **Non**   | **Non**            |
|                       |           |                    |
| **PSS-29ZBSR**        | **Non**   | **Oui**            |
|                       |           |                    |
| **PSM-29ZBS**         | **Oui**   | **Non**            |
|                       |           |                    |
| **PSM-29ZBSR**        | **Oui**   | **Oui**            |
|                       |           |                    |

**Identification des pièces**

**1. Bouton de fonction, également appelé indicateur LED**

Le bouton de fonction sert également d'indicateur LED. Le bouton de fonction est utilisé pour contrôler l’interrupteur d’alimentation. L'indicateur LED est utilisé pour indiquer l'état de l'interrupteur d'alimentation.

**Indication LED :**

Le voyant LED s'allume dans les conditions suivantes :

-   Sur:

L'interrupteur d'alimentation est allumé.

-   Désactivé:

L'interrupteur d'alimentation est éteint.

-   Clignote deux fois :

Le Power Switch a rejoint avec succès un réseau ZigBee.

-   Clignote 5 fois

L'interrupteur d'alimentation s'est lié avec succès à un contrôleur

-   Clignote toutes les 20 minutes

Le Power Switch a perdu la connexion à son réseau ZigBee actuel

(**PSS-29ZBS et PSM-29ZBS uniquement**)

**Utilisation du bouton de fonction :**

-   Appuyez sur le bouton pour allumer/éteindre l'interrupteur d'alimentation
-   Appuyez et maintenez le bouton pendant 10 secondes, puis relâchez-le pour réinitialiser l'interrupteur d'alimentation.
-   Appuyez et maintenez le bouton pendant 3 secondes, puis relâchez-le pour vous lier à un contrôleur.

_**Tapez F**__**Tapez B**_

![](<.gitbook/assets/0 (74).jpeg>)

_**Type L**__**Type J**_

1

**Configuration du réseau ZigBee**

![](<.gitbook/assets/1 (66).jpeg>)

-   _**Directives relatives aux appareils ZigBee**_

ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

![](<.gitbook/assets/2 (59).jpeg>)

-   _**Rejoindre le réseau ZigBee**_

En tant qu'appareil ZigBee, le Power Switch doit rejoindre un réseau ZigBee pour recevoir des commandes et transmettre des informations sur la consommation d'énergie. Suivez les étapes ci-dessous pour rejoindre le Power Switch dans un réseau ZigBee.

-   1.  Branchez l'interrupteur d'alimentation sur une prise de courant.
    2.  Appuyez et maintenez enfoncé le bouton de fonction pendant 10 secondes pendant que l'interrupteur d'alimentation se réinitialise et commence à rechercher le réseau ZigBee existant. Veuillez vous assurer que la fonction d'autorisation de rejoindre sur le routeur ou le coordinateur de votre réseau ZigBee est activée.
    3.  Si l'interrupteur d'alimentation rejoint avec succès un réseau ZigBee, l'indicateur LED clignote deux fois pour confirmer.
    4.  Après avoir rejoint le réseau ZigBee, le Power Switch sera automatiquement enregistré dans le réseau. Veuillez vérifier auprès du coordinateur du réseau ZigBee, du panneau de contrôle du système ou du CIE (équipement de contrôle et d'indication) pour confirmer si l'adhésion et l'enregistrement ont réussi.
    5.  Si l'enregistrement et l'adhésion au réseau échouent, veuillez vérifier votre coordinateur de réseau ZigBee, votre panneau de commande système ou les paramètres CIE pour vous assurer que la fonction d'autorisation de participation est disponible, puis utilisez la fonction de réinitialisation d'usine ci-dessous pour rejoindre le réseau ZigBee.
-   _**Liaison avec le contrôleur**_

![](<.gitbook/assets/3 (53).jpeg>)

Après avoir rejoint le réseau ZigBee, l'interrupteur d'alimentation peut se lier à un dispositif de contrôle qui peut être utilisé pour allumer/éteindre l'interrupteur d'alimentation. Pour lier l'interrupteur d'alimentation et l'appareil :

-   1.  Appuyez et maintenez le bouton de fonction pendant 3 secondes, puis relâchez le bouton. Le commutateur d'alimentation enverra une demande contraignante au coordinateur.
    2.  Reportez-vous au manuel de votre contrôleur pour envoyer une demande de liaison pour l'appareil dans les 16 secondes.
    3.  Si la liaison réussit, le voyant LED de l'interrupteur d'alimentation clignotera 5 fois pour confirmer. Vous pouvez maintenant utiliser le contrôleur pour régler le niveau de puissance de sortie de l'interrupteur d'alimentation.
    4.  Si la liaison échoue, veuillez réessayer le processus de liaison.
-   _**Suppression d'un appareil du réseau ZigBee (réinitialisation d'usine)**_

![](<.gitbook/assets/4 (62).png>)

Pour supprimer l'interrupteur d'alimentation du réseau ZigBee actuel, l'interrupteur d'alimentation doit être mis en réinitialisation d'usine pour terminer la suppression de l'appareil. La fonction de réinitialisation d'usine effacera le commutateur d'alimentation de ses paramètres et informations stockés et invitera le commutateur d'alimentation à rechercher un nouveau réseau ZigBee.

**Avant de retirer l'appareil, assurez-vous que l'interrupteur d'alimentation se trouve dans la plage actuelle du signal réseau ZigBee.**

-   1.  Appuyez et maintenez le bouton de fonction pendant 10 secondes, puis relâchez le bouton pour réinitialiser l'interrupteur d'alimentation.
    2.  Lors de la réinitialisation, l'interrupteur d'alimentation effacera les paramètres réseau ZigBee actuels et transmettra le signal au coordinateur ZigBee pour se retirer du réseau ZigBee actuel. Il recherchera ensuite à nouveau activement le réseau ZigBee disponible et rejoindra automatiquement le réseau.
-   _**Capacité du périphérique de routeur ZigBee (PSS-29ZBSR / PSM-29ZBSR uniquement)**_

![](<.gitbook/assets/5 (62).png>)

Les modèles Power Switch avec fonction routeur permettent à d'autres appareils ZigBee de rejoindre le réseau ZigBee via le routeur. Le routeur Power Switch a une capacité maximale de 40 appareils, dont 10 routeurs ; le routeur Power Switch Meter a une capacité maximale de 10 appareils, dont 5 routeurs.

| **Numéro de modèle.**     | **Appareil ZigBee maximal** | **ZigBee maximal** |   |
| ------------------------- | --------------------------- | ------------------ | - |
| **+ Capacité du routeur** | **Capacité du routeur**     |                    |   |
|                           |                             |                    |   |
|                           |                             |                    |   |
| **PSS-29ZBS**             | **40**                      | **10**             |   |
|                           |                             |                    |   |
| **PSM-29ZBSR**            | **10**                      | **5**              |   |
|                           |                             |                    |   |

**Opération**

![](<.gitbook/assets/6 (42).jpeg>)

-   _**Installation**_
    -   Branchez l'interrupteur d'alimentation sur une prise de courant, puis branchez l'appareil sur la prise de l'interrupteur d'alimentation. L'appareil doit être en état ON.
    -   _**NOTE IMPORTANTE**_**:**L'interrupteur d'alimentation n'a pas de batterie de secours et sera mis hors tension en cas de panne de courant CA.**NE PAS**utilisez l'interrupteur d'alimentation comme routeur pour votre capteur de sécurité ou vos dispositifs de contrôle d'alarme tels que le contact de porte, le capteur PIR… etc., sinon les capteurs perdront la connexion au réseau ZigBee si l'interrupteur d'alimentation est débranché de l'alimentation secteur. Planifiez les emplacements d'installation de ces capteurs de sécurité sans utiliser l'interrupteur d'alimentation et utilisez uniquement un routeur avec batterie de secours pour eux. La fonction routeur de l'interrupteur d'alimentation doit**SEULEMENT**Être utilisé pour fournir une extension de la plage de signal pour d'autres interrupteurs d'alimentation/variateur.

2

-   ![](<.gitbook/assets/7 (39).jpeg>)_**Contrôle des appareils**_
    -   Une fois que l'interrupteur d'alimentation a rejoint avec succès un réseau ZigBee, le coordinateur peut allumer/éteindre l'interrupteur d'alimentation à distance pour contrôler l'appareil.
    -   Vous pouvez également appuyer sur le bouton de l'interrupteur d'alimentation pour basculer son état marche/arrêt
    -   Si vous avez lié un contrôleur à l'interrupteur d'alimentation, vous pouvez également utiliser le contrôleur pour allumer/éteindre l'interrupteur d'alimentation.
    -   Si l'interrupteur d'alimentation est retiré de la prise de courant, après avoir rebranché l'interrupteur d'alimentation, son état marche/arrêt précédent sera restauré dans un délai d'une minute.
-   _**Moniteur de consommation d'énergie (PSM-29ZBS / PSM-29ZBSR uniquement)**_
    -   Les modèles Power Switch avec compteur intégré transmettront un signal avec ses données de consommation électrique toutes les 10 minutes au coordinateur du réseau ZigBee.
    -   Chaque fois que la production d'énergie du commutateur d'alimentation change de +/- 2 W, il transmettra automatiquement un signal avec les données de consommation d'énergie au coordinateur du réseau ZigBee pour mise à jour.
    -   Le commutateur d'alimentation transmet un signal avec les données d'alimentation au coordinateur chaque fois que la consommation d'énergie accumulée augmente de 0,1 kW/h.
    -   Le compteur a une précision de +/- 5%.
    -   Pour effacer le commutateur d'alimentation de ses données de consommation d'énergie accumulées, suivez les étapes ci-dessous :
        1.  Débranchez l'interrupteur d'alimentation de la prise de courant.
        2.  Appuyez et maintenez enfoncé le bouton de fonction et rebranchez l'interrupteur d'alimentation tout en maintenant le bouton enfoncé.
        3.  Maintenez le bouton enfoncé et relâchez-le après 3 secondes. Les données de consommation d'énergie accumulées seront effacées.
-   _**Charge de fonctionnement maximale**_
    -   Pour 110 V : la charge de fonctionnement maximale est de 1 760 W et 16 A.
    -   Pour 230V : la charge de fonctionnement maximale est de 3680W et 16A.
    -   Si l'interrupteur d'alimentation surchauffe, il coupera automatiquement l'alimentation par mesure de sécurité. L'interrupteur d'alimentation doit être débranché et rebranché après la coupure pour reprendre un fonctionnement normal.

![](<.gitbook/assets/8 (33).jpeg>)![](<.gitbook/assets/9 (26).jpeg>)

**Annexe (Pour les développeurs uniquement)**

![](<.gitbook/assets/10 (38).png>)

_**ID du cluster de commutateurs d'alimentation**_

| **ID de l'appareil : Prise de courant secteur : 0x0009** | **/ INTELLIGENT_PRISE : 0x0051** |                 |
| -------------------------------------------------------- | -------------------------------- | --------------- |
| **Point de terminaison : 0x01**                          |                                  |                 |
|                                                          |                                  |                 |
| **Du côté serveur**                                      |                                  | **Côté client** |
|                                                          |                                  |                 |
|                                                          | **Obligatoire**                  |                 |

De base (0x0000)

Identifier (0x0003)

Marche/Arrêt (0x0006)

Groupes (0x0004)

Scènes (0x0005) (**PSS-29ZBS / PSS-29ZBSR uniquement**)

Mesure (0x0702)(**PSM-29ZBS /PSM-29ZBSR uniquement**)

**Facultatif**

Groupes (0x0004)

_Aucun_

_Aucun_

-   _**Attribut des informations de base sur le cluster**_

| **Identifier**   | **Nom**                  | **Taper**   | **Gamme**  | **Accéder**       | **Défaut** | **Obligatoire** |   |
| ---------------- | ------------------------ | ----------- | ---------- | ----------------- | ---------- | --------------- | - |
| **/ Facultatif** |                          |             |            |                   |            |                 |   |
|                  |                          |             |            |                   |            |                 |   |
| 0x0000           | _Version ZCL_            | Non signé   | 0x00 –0xff | Lecture seulement | 0x01       | M.              |   |
| Entier de 8 bits |                          |             |            |                   |            |                 |   |
|                  |                          |             |            |                   |            |                 |   |
| 0x0001           | Version de l'application | Non signé   | 0x00 –0xff | Lecture seulement | 0x00       | Ô               |   |
| Entier de 8 bits |                          |             |            |                   |            |                 |   |
|                  |                          |             |            |                   |            |                 |   |
| 0x0003           | _Version matérielle_     | Non signé   | 0x00 –0xff | Lecture seulement | 0          | Ô               |   |
| Entier de 8 bits |                          |             |            |                   |            |                 |   |
|                  |                          |             |            |                   |            |                 |   |
| 0x0004           | _Nom du Fabricant_       | Personnage  | 0–32       | Lecture seulement | Climax     | Ô               |   |
| Chaîne           | octets                   | Technologie |            |                   |            |                 |   |
|                  |                          |             |            |                   |            |                 |   |
| 0x0005           | _Identifiant du modèle_  | Personnage  | 0–32       | Lecture seulement | (Modèle    | Ô               |   |
| Chaîne           | octets                   | Version)    |            |                   |            |                 |   |
|                  |                          |             |            |                   |            |                 |   |
| 0x0006           | _DateCode_               | Personnage  | 0–16       | Lecture seulement |            | Ô               |   |
| Chaîne           | octets                   |             |            |                   |            |                 |   |
|                  |                          |             |            |                   |            |                 |   |
| 0x0007           | _Source d'énergie_       | 8 bits      | 0x00 –0xff | Lecture seulement |            | M.              |   |
|                  |                          |             | 3          |                   |            |                 |   |

| 0x0010                                                       | _EmplacementDescription_ | Personnage       | 0–32         |   |                   | Lire écrire |            | Ô               |   |   |
| ------------------------------------------------------------ | ------------------------ | ---------------- | ------------ | - | ----------------- | ----------- | ---------- | --------------- | - | - |
| Chaîne                                                       | octets                   |                  |              |   |                   |             |            |                 |   |   |
|                                                              |                          |                  |              |   |                   |             |            |                 |   |   |
| 0x0011                                                       | _Environnement physique_ | 8 bits           | 0x00 –0xff   |   |                   | Lire écrire | 0x00       | Ô               |   |   |
| 0x0012                                                       | _Appareil activé_        | Booléen          | 0x00 –       |   |                   | Lire écrire | 0x01       | M.              |   |   |
| 0x01                                                         |                          |                  |              |   |                   |             |            |                 |   |   |
|                                                              |                          |                  |              |   |                   |             |            |                 |   |   |
| _**Attribut des informations d'identification du cluster**_ |                          |                  |              |   |                   |             |            |                 |   |   |
|                                                              |                          |                  |              |   |                   |             |            |                 |   |   |
| **Identifier**                                               | **Nom**                  | **Taper**        | **Gamme**    |   | **Accéder**       |             | **Défaut** | **Obligatoire** |   |   |
|                                                              |                          | **/ Facultatif** |              |   |                   |             |            |                 |   |   |
|                                                              |                          |                  |              |   |                   |             |            |                 |   |   |
| 0x0000                                                       | _Identifier l'heure_     | Non signé        | 0x00 –0xffff |   | Lire /            |             | 0x0000     | M.              |   |   |
| Entier de 16 bits                                            |                          | Écrire           |              |   |                   |             |            |                 |   |   |
|                                                              |                          |                  |              |   |                   |             |            |                 |   |   |
| _**Attributs du cluster Groupes Informations**_             |                          |                  |              |   |                   |             |            |                 |   |   |
|                                                              |                          |                  |              |   |                   |             |            |                 |   |   |
| **Identifier**                                               | **Nom**                  | **Taper**        | **Gamme**    |   | **Accéder**       |             | **Défaut** | **Obligatoire** |   |   |
|                                                              |                          | **/ Facultatif** |              |   |                   |             |            |                 |   |   |
|                                                              |                          |                  |              |   |                   |             |            |                 |   |   |
| 0x0000                                                       | _NomSupport_             | Bitmap 8 bits    | x0000000     |   | Lecture seulement |             | -          | M.              |   |   |

![](<.gitbook/assets/11 (29).png>)![](<.gitbook/assets/12 (34).png>)![](<.gitbook/assets/13 (24).jpeg>)

-   _**Attributs du cluster Scènes Informations**_

![](<.gitbook/assets/14 (20).jpeg>)

| **Identifier**                                               | **Nom**          | **Taper**         | **Gamme**       | **Accéder**       | **Défaut** | **Obligatoire** |   |
| ------------------------------------------------------------ | ---------------- | ----------------- | --------------- | ----------------- | ---------- | --------------- | - |
| **/ Facultatif**                                             |                  |                   |                 |                   |            |                 |   |
|                                                              |                  |                   |                 |                   |            |                 |   |
| 0x0000                                                       | Nombre de scènes | 8 bits non signé  | 0x00 – 0xff     | Lecture seulement | 0x00       | M.              |   |
| entier                                                       |                  |                   |                 |                   |            |                 |   |
|                                                              |                  |                   |                 |                   |            |                 |   |
| 0x0001                                                       | _Scène actuelle_ | 8 bits non signé  | 0x00 – 0xff     | Lecture seulement | 0x00       | M.              |   |
| entier                                                       |                  |                   |                 |                   |            |                 |   |
|                                                              |                  |                   |                 |                   |            |                 |   |
| 0x0002                                                       | _Groupe actuel_  | 16 bits non signé | 0x0000 – 0xfff7 | Lecture seulement | 0x00       | M.              |   |
|                                                              | entier           |                   |                 |                   |            |                 |   |
|                                                              |                  |                   |                 |                   |            |                 |   |
| 0x0003                                                       | _ScèneValide_    | Booléen           | 0x00 – 0x01     | Lecture seulement | 0x00       | M.              |   |
| 0x0004                                                       | _NomSupport_     | Bitmap 8 bits     | x0000000        | Lecture seulement | -          | M.              |   |
| _**Attribut des informations sur le cluster marche/arrêt**_ |                  |                   |                 |                   |            |                 |   |

![](<.gitbook/assets/15 (22).png>)

| **Identifier**   | **Nom**         | **Taper** | **Gamme**  | **Accéder**       | **Défaut** | **Obligatoire** |   |
| ---------------- | --------------- | --------- | ---------- | ----------------- | ---------- | --------------- | - |
| **/ Facultatif** |                 |           |            |                   |            |                 |   |
|                  |                 |           |            |                   |            |                 |   |
| 0x0000           | _Allumé éteint_ | Booléen   | 0x00 –0x01 | Lecture seulement | 0x00       | M.              |   |

![](<.gitbook/assets/16 (24).png>)

_**Attributs des informations du cluster de comptage (attribut d'informations de lecture)**_

![](<.gitbook/assets/17 (16).jpeg>)

_**(PSM-29ZBS / PSM-29ZBSR uniquement)**_

| **Identifier**   | **Nom**        | **Taper**      | **Gamme**        | **Accéder** | **Défaut** | **Obligatoire** |   |
| ---------------- | -------------- | -------------- | ---------------- | ----------- | ---------- | --------------- | - |
| **/ Facultatif** |                |                |                  |             |            |                 |   |
|                  |                |                |                  |             |            |                 |   |
| 0x00             | Somme actuelle | Non signé      | 0x000000000000 à | Lire        |            | M.              |   |
| Livré            | Entier 48 bits | 0xFFFFFFFFFFFF | Seulement        |             |            |                 |   |
|                  |                |                |                  |             |            |                 |   |

![](<.gitbook/assets/18 (24).png>)

_**Attributs des informations du cluster de mesure (ensemble d'attributs de formatage)**_

![](<.gitbook/assets/19 (7).jpeg>)

_**(PSM-29ZBS / PSM-29ZBSR uniquement)**_

| **Identifier**   | **Nom**                      | **Taper**     | **Gamme**   | **Accéder**       | **Défaut** | **Obligatoire** |   |
| ---------------- | ---------------------------- | ------------- | ----------- | ----------------- | ---------- | --------------- | - |
| **/ Facultatif** |                              |               |             |                   |            |                 |   |
|                  |                              |               |             |                   |            |                 |   |
| 0x00             | Unité de mesure              | 8 bits        | 0x00 à 0xFF | Lecture seulement | 0x00       | M.              |   |
| Énumération      |                              |               |             |                   |            |                 |   |
|                  |                              |               |             |                   |            |                 |   |
| 0x01             | Multiplier                   | Non signé     | 0x000000 à  | Lecture seulement | 1          | Ô               |   |
| Entier 24 bits   | 0xFFFFFF                     |               |             |                   |            |                 |   |
|                  |                              |               |             |                   |            |                 |   |
| 0x02             | Diviseur                     | Non signé     | 0x000000 à  | Lecture seulement | 10000      | Ô               |   |
| Entier 24 bits   | 0xFFFFFF                     |               |             |                   |            |                 |   |
|                  |                              |               |             |                   |            |                 |   |
| 0x03             | SommationFormation           | BitMap 8 bits | 0x00 à 0xFF | Lecture seulement | 0xF9       | M.              |   |
| 0x04             | DemandFormating              | BitMap 8 bits | 0x00 à 0xFF | Lecture seulement | 0Ksasa     | Ô               |   |
| 0x06             | Type de dispositif de mesure | BitMap 8 bits | 0x00 à 0xFF | Lecture seulement | 0x00       | M.              |   |

![](<.gitbook/assets/20 (17).png>)

-   _**Attributs des informations du cluster de mesure (ensemble d'attributs historiques) (PSM-29ZBS / PSM-29ZBSR uniquement)**_

| **Identifier**   | **Nom**             | **Taper**     | **Gamme**    | **Accéder**       | **Défaut** | **Obligatoire** |   |
| ---------------- | ------------------- | ------------- | ------------ | ----------------- | ---------- | --------------- | - |
| **/ Facultatif** |                     |               |              |                   |            |                 |   |
|                  |                     |               |              |                   |            |                 |   |
| 0x00             | Demande instantanée | Signé 24 bits | -8 388 607 à | Lecture seulement | 0x00       | Ô               |   |
| Entier           | 8,388,607           |               |              |                   |            |                 |   |
|                  |                     |               |              |                   |            |                 |   |

4
