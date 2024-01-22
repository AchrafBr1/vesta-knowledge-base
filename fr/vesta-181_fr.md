# VESTA 181

**Commutateur à bascule de relais ZigBee PRL-1ZBS(R)-AC**

**Introduction**

PRL-1ZBS est un interrupteur à bascule de relais ZigBee. L'interrupteur à bascule de relais peut être connecté à un appareil filaire et réglé sur l'état Normal Ouvert (N.O.) ou Normal Fermé (N.C.). Après avoir rejoint le réseau ZigBee, le commutateur à bascule relais peut être contrôlé via le réseau ZigBee pour activer les appareils connectés.

Le commutateur à bascule relais utilise la technologie ZigBee pour la transmission du signal sans fil. ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

Le commutateur à bascule relais sert de périphérique final dans le réseau ZigBee. Il peut être inclus dans le réseau ZigBee pour transmettre ou recevoir un signal, mais ne peut permettre à aucun autre appareil ZigBee de rejoindre le réseau via le commutateur à bascule de relais.

Les modèles avec fonction routeur servent également de routeur dans le réseau ZigBee. Après avoir été inclus dans le réseau ZigBee, il permet à d'autres appareils ZigBee de rejoindre le réseau via le Power Switch.

**Identification des pièces**

![](<.gitbook/assets/0 (70).jpeg>)

**1. Indicateur LED**

L'indicateur LED est utilisé pour indiquer l'état du relais :

-   -   Clignote une fois : le relais est réinitialisé.
    -   Clignote deux fois : le relais a rejoint avec succès un réseau ZigBee.
    -   Clignote une fois toutes les 20 minutes :

Le Relay a perdu la connexion à son réseau ZigBee actuel.

1.  **Bouton de fonction**

Le bouton de fonction est utilisé pour réinitialiser le commutateur à bascule de relais pour rejoindre un réseau ZigBee disponible.

Appuyez et maintenez le bouton pendant 10 secondes, puis relâchez-le pour réinitialiser l'interrupteur à bascule du relais.

**Bornes de connexion**

Appuyez sur le bouton pour ouvrir la tondeuse pour chaque borne et connecter le câblage. Relâchez le bouton pour fermer la tondeuse et maintenir le fil en place.

1.  **Réservé**
2.  **Ligne (entrée CA)**
3.  **Neutre**
4.  **NON**

Pour une connexion normale ouverte avec l'appareil

1.  **Commun**
2.  **NC**

Pour une connexion normale et fermée avec l'appareil

**spécification**

-   Source d'alimentation (alimentation externe) : 100-240VAC
-   Sortie relais : relais SPDT sans potentiel, charge de fonctionnement maximale : 5 A (résistif) à 24 V CC ou 240 V CA.
-   Fil toronné : 16-26 AWG
-   Température de fonctionnement : -10°C à 45°C (14°F à 113°F)
-   Humidité : jusqu'à 85 % sans condensation
-   Dimensions : 71,1 mm x 49 mm x 26 mm

1

![](<.gitbook/assets/1 (62).jpeg>)

**Environnement d'installation**

-   Le contrôleur de relais doit être installé à l’intérieur dans un endroit sec.
-   Il est recommandé d'installer l'appareil dans un boîtier en plastique résistant au feu.
-   N'installez pas l'appareil dans un boîtier métallique pour optimiser la portée RF.

![](<.gitbook/assets/2 (55).jpeg>)

**Prudence**

-   Tous les travaux sur l'appareil, y compris l'installation et la maintenance, doivent être effectués par un électricien qualifié et agréé.
-   Pour éviter les chocs électriques et/ou les dommages à l'équipement, débranchez l'alimentation électrique au niveau du fusible principal ou du disjoncteur avant l'installation et la maintenance.
-   Ne connectez pas l'appareil à des charges dépassant le courant de charge pris en charge.

![](<.gitbook/assets/3 (50).jpeg>)

**Installation**

Les spécifications de câblage des trous d’insertion sont AWG 16-26 ou Ø 1,31-0,129 (mm²).

Câblez le relais selon les instructions ci-dessous ou reportez-vous au schéma pour plus d'informations.

1.  Veuillez éteindre l'alimentation avant la connexion.
2.  Connectez les bornes L et N de l'alimentation électrique aux bornes Ligne et Neutre du PRL respectivement.
3.  En fonction de l'appareil que vous souhaitez contrôler via le relais, sélectionnez la borne NO ou NC et câblez le relais avec l'appareil pour établir une connexion normale ouverte ou normale avec l'appareil.
4.  Une fois le câblage terminé, mettez sous tension pour allumer l'interrupteur à bascule du relais.

_\\<IMPORTANT NOTE>_

-   Le câblage du PRL ne doit être effectué que par un technicien certifié possédant les connaissances et la formation appropriées en matière d'équipement électrique.

**Configuration du réseau ZigBee**

-   _**Directives relatives aux appareils ZigBee**_

ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

-   _**Rejoindre le réseau ZigBee**_

En tant qu'appareil ZigBee, le relais doit rejoindre un réseau ZigBee pour recevoir des commandes. Veuillez suivre les étapes ci-dessous pour rejoindre le Relay dans un réseau ZigBee.

-   1.  Connectez l'entrée d'alimentation à l'interrupteur à bascule de relais conformément aux instructions d'installation ci-dessus et mettez l'interrupteur à bascule de relais sous tension.
    2.  Appuyez et maintenez enfoncé le bouton de fonction pendant 10 secondes pendant que le relais se réinitialise et commence à rechercher le réseau ZigBee existant. Veuillez vous assurer que la fonction d'autorisation de rejoindre sur le routeur ou le coordinateur de votre réseau ZigBee est activée.
    3.  Si le commutateur à bascule de relais rejoint avec succès un réseau ZigBee, l'indicateur LED clignotera deux fois pour confirmer.
    4.  Après avoir rejoint le réseau ZigBee, le commutateur à bascule relais sera automatiquement enregistré dans le réseau. Veuillez vérifier auprès du coordinateur du réseau ZigBee, du panneau de contrôle du système ou du CIE (équipement de contrôle et d'indication) pour confirmer si l'adhésion et l'enregistrement ont réussi.
    5.  Après avoir rejoint le réseau ZigBee, si le commutateur à bascule relais perd la connexion au réseau ZigBee actuel, l'indicateur LED clignote toutes les 20 minutes. Veuillez vérifier l'état de votre réseau ZigBee et la plage du signal du commutateur à bascule du relais pour corriger la condition.
-   _**Suppression d'un appareil du réseau ZigBee (réinitialisation d'usine)**_

Pour supprimer le commutateur à bascule de relais du réseau ZigBee actuel, l'appareil doit être mis en configuration d'usine pour terminer la suppression de l'appareil. La fonction de réinitialisation d'usine effacera l'appareil de ses paramètres et informations stockés et l'invitera à rechercher un nouveau réseau ZigBee.

2

**Avant de retirer l'appareil, assurez-vous que l'interrupteur à bascule du relais se trouve dans la plage actuelle du signal réseau ZigBee.**

-   1.  Appuyez et maintenez le bouton de fonction pendant 10 secondes, puis relâchez le bouton pour réinitialiser l'interrupteur à bascule du relais.
    2.  Lors de la réinitialisation, l'appareil effacera les paramètres réseau ZigBee actuels et transmettra le signal au coordinateur ZigBee pour se retirer du réseau ZigBee actuel. Il recherchera ensuite à nouveau activement le réseau ZigBee disponible et rejoindra automatiquement le réseau.
-   _**Capacité du périphérique du routeur ZigBee (PRL-1ZBSR-AC uniquement)**_

Le modèle de commutateur à bascule relais avec fonction routeur permet à d'autres appareils ZigBee de rejoindre le réseau ZigBee via le routeur. Il a une capacité maximale de 40 appareils/routeurs.

**Opération**

-   _**Contrôle des relais**_
    -   Une fois que l'interrupteur à bascule du relais a rejoint avec succès un réseau ZigBee, le coordinateur/panneau de commande peut contrôler à distance le relais pour l'allumer, l'éteindre ou basculer entre les conditions marche et arrêt. Veuillez vous référer à votre coordinateur/panneau de contrôle ZigBee pour plus de détails.

**Annexe (Pour les développeurs uniquement)**

-   _**ID du cluster de relais**_

**ID de l'appareil : On Off Sortie : 0x0002**

**Point de terminaison : 0x0A**

| **Du côté serveur**                                          |                   |                          |                  |             |               |             | **Côté client**  |         |                 |   |
| ------------------------------------------------------------ | ----------------- | ------------------------ | ---------------- | ----------- | ------------- | ----------- | ---------------- | ------- | --------------- | - |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
|                                                              |                   |                          | **Obligatoire**  |             |               |             |                  |         |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
| De base (0x0000)                                             |                   |                          |                  |             |               |             |                  | _Aucun_ |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
| Identifier (0x0003)                                          |                   |                          |                  |             |               |             |                  |         |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
| Marche/Arrêt (0x0006)                                        |                   |                          |                  |             |               |             |                  |         |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
|                                                              |                   |                          | **Facultatif**   |             |               |             |                  |         |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
| Groupes (0x0004)                                             |                   |                          |                  |             |               |             |                  | Aucun   |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
| _**Attribut des informations de base sur le cluster**_      |                   |                          |                  |             |               |             |                  |         |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
| **Identifier**                                               |                   | **Nom**                  | **Taper**        |             | **Gamme**     | **Accéder** | **Défaut**       |         | **Obligatoire** |   |
|                                                              |                   |                          | **/ Facultatif** |             |               |             |                  |         |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
| 0x0000                                                       |                   | _Version ZCL_            | 8 bits non signé |             | 0x00 –0xff    | Lire        | 0x01             |         | M.              |   |
|                                                              | entier            |                          | seulement        |             |               |             |                  |         |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
| 0x0001                                                       |                   | Version de l'application | 8 bits non signé |             | 0x00 – 0xff   | Lire        | 0x00             |         | Ô               |   |
|                                                              | entier            |                          | seulement        |             |               |             |                  |         |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
| 0x0003                                                       |                   | _Version matérielle_     | 8 bits non signé |             | 0x00 –0xff    | Lire        | 0                |         | Ô               |   |
|                                                              | entier            |                          | seulement        |             |               |             |                  |         |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
| 0x0004                                                       |                   | _Nom du Fabricant_       | Personnage       |             | 0 – 32 octets | Lire        | Climax           |         | Ô               |   |
|                                                              | Chaîne            |                          | seulement        | Technologie |               |             |                  |         |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
| 0x0005                                                       |                   | _Identifiant du modèle_  | Personnage       |             | 0 – 32 octets | Lire        | (Version modèle) |         | Ô               |   |
|                                                              | Chaîne            |                          | seulement        |             |               |             |                  |         |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
| 0x0006                                                       |                   | _DateCode_               | Personnage       |             | 0 – 16 octets | Lire        |                  |         | Ô               |   |
|                                                              | Chaîne            |                          | seulement        |             |               |             |                  |         |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
| 0x0007                                                       |                   | _Source d'énergie_       | 8 bits           |             | 0x00 –0xff    | Lire        |                  |         | M.              |   |
|                                                              |                   | seulement                |                  |             |               |             |                  |         |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
| 0x0010                                                       |                   | _EmplacementDescription_ | Personnage       |             | 0 – 32 octets | Lire /      |                  |         | Ô               |   |
|                                                              | Chaîne            |                          | Écrire           |             |               |             |                  |         |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
| 0x0011                                                       |                   | _Environnement physique_ | 8 bits           |             | 0x00 –0xff    | Lire /      | 0x00             |         | Ô               |   |
|                                                              |                   | Écrire                   |                  |             |               |             |                  |         |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
| 0x0012                                                       |                   | _Appareil activé_        | Booléen          |             | 0x00 –0x01    | Lire /      | 0x01             |         | M.              |   |
|                                                              |                   | Écrire                   |                  |             |               |             |                  |         |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
| _**Attribut des informations d'identification du cluster**_ |                   |                          |                  |             |               |             |                  |         |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
| **Identifier**                                               |                   | **Nom**                  | **Taper**        |             | **Gamme**     | **Accéder** | **Défaut**       |         | **Obligatoire** |   |
|                                                              |                   |                          | **/ Facultatif** |             |               |             |                  |         |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |
| 0x0000                                                       |                   | _Identifier l'heure_     | Non signé        |             | 0x00 –0xffff  | Lire /      | 0x0000           |         | M.              |   |
|                                                              | Entier de 16 bits |                          | Écrire           |             |               |             |                  |         |                 |   |
|                                                              |                   |                          |                  |             |               |             |                  |         |                 |   |

3

-   _**Attribut des informations sur le cluster marche/arrêt**_

| **Identifier**   | **Nom**         | **Taper** | **Gamme**  | **Accéder** | **Défaut** | **Obligatoire** |   |
| ---------------- | --------------- | --------- | ---------- | ----------- | ---------- | --------------- | - |
| **/ Facultatif** |                 |           |            |             |            |                 |   |
|                  |                 |           |            |             |            |                 |   |
| 0x0000           | _Allumé éteint_ | Booléen   | 0x00 –0x01 | Lire        | 0x00       | M.              |   |
| seulement        |                 |           |            |             |            |                 |   |
|                  |                 |           |            |             |            |                 |   |

_**Attributs du cluster Groupes Informations**_

| **Identifier**   | **Nom**      | **Taper**     | **Gamme** | **Accéder** | **Défaut** | **Obligatoire** |   |
| ---------------- | ------------ | ------------- | --------- | ----------- | ---------- | --------------- | - |
| **/ Facultatif** |              |               |           |             |            |                 |   |
|                  |              |               |           |             |            |                 |   |
| 0x0000           | _NomSupport_ | Bitmap 8 bits | x0000000  | Lire        | -          | M.              |   |
| seulement        |              |               |           |             |            |                 |   |
|                  |              |               |           |             |            |                 |   |

4
