# VESTA 191

**Contrôleur de relais ZigBee PRL-8ZBS(R)-AC-OTA**

**Introduction**

PRL-8ZBS-AC-OTA est un contrôleur de relais ZigBee qui peut être connecté à des appareils filaires et réglé sur l'état Normal Ouvert (N.O.) ou Normal Fermé (N.C.). Après avoir rejoint le réseau ZigBee, le contrôleur de relais peut être contrôlé via le réseau ZigBee pour activer les appareils connectés.

Le contrôleur de relais utilise la technologie ZigBee pour la transmission du signal sans fil. ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

Le contrôleur de relais sert de périphérique final dans le réseau ZigBee. Il peut être inclus dans le réseau ZigBee pour transmettre ou recevoir un signal, mais ne peut permettre à aucun autre appareil ZigBee de rejoindre le réseau via le contrôleur de relais.

Les modèles avec fonction routeur servent également de routeur dans le réseau ZigBee. Après avoir été inclus dans le réseau ZigBee, il permet à d'autres appareils ZigBee de rejoindre le réseau via le contrôleur de relais.

**Identification des pièces**

![](<.gitbook/assets/0 (78).jpeg>)

**1. Bouton de fonction**

Le bouton de fonction est utilisé pour réinitialiser le contrôleur de relais afin de rejoindre un réseau ZigBee disponible.

Appuyez et maintenez le bouton pendant 10 secondes, puis relâchez-le pour réinitialiser le contrôleur de relais.

**2. Indicateur LED (rouge)**

L'indicateur LED est utilisé pour indiquer l'état du relais :

-   Clignote une fois : le relais est réinitialisé.
-   Clignote deux fois : le relais a rejoint avec succès un réseau ZigBee.
-   Clignote une fois toutes les 20 minutes :
-   Le Relay a perdu la connexion à son réseau ZigBee actuel.

**Bornes de connexion**

Connectez le fil à la borne, serrez la vis pour fermer la tondeuse et maintenez le fil en place. Dévissez pour ouvrir la tondeuse pour retirer le fil connecté à la borne.

1.  **Ligne (entrée CA)**
2.  **Neutre**
3.  **NON**

Pour une connexion normale ouverte avec l’appareil.

1.  **Commun**
2.  **NC**

Pour une connexion normale et fermée avec l'appareil

**8. Pince anti-traction**

La pince est utilisée pour fixer les fils et fournir un soulagement de traction pour protéger les fils de la découpe métallique.

**9. Boucle de câblage**

La boucle de câblage est utilisée pour gérer les fils.

1

**spécification**

-   Source d'alimentation (alimentation externe) : 100-240VAC
-   Sortie relais : relais SPDT sans potentiel, charge de fonctionnement maximale : 10 A (résistif) à 24 V CC ou 240 V CA.
-   Fil toronné : 14~22 AWG
-   Température de fonctionnement : -10°C à 45°C (14°F à 113°F)
-   Humidité : jusqu'à 85 % sans condensation
-   Dimensions : 86 mm x 72 mm x 29 mm

![](<.gitbook/assets/1 (69).jpeg>)

**Environnement d'installation**

-   Le contrôleur de relais doit être installé à l’intérieur dans un endroit sec.
-   Il est recommandé d'installer l'appareil dans un boîtier en plastique résistant au feu.
-   N'installez pas l'appareil dans une boîte métallique pour optimiser la gamme Z-Wave.

![](<.gitbook/assets/2 (63).jpeg>)

**Prudence**

-   Tous les travaux sur l'appareil, y compris l'installation et la maintenance, doivent être effectués par un électricien qualifié et agréé.
-   Pour éviter les chocs électriques et/ou les dommages à l'équipement, débranchez l'alimentation électrique au niveau du fusible principal ou du disjoncteur avant l'installation et la maintenance.

Ne connectez pas l'appareil à des charges dépassant le courant de charge pris en charge.

![](<.gitbook/assets/3 (56).jpeg>)

**Installation**

Le câblage du PRL ne doit être effectué que par un technicien certifié possédant les connaissances et la formation appropriées en matière d'équipement électrique. Câblez le relais selon les instructions ci-dessous :

1.  Coupez l'alimentation électrique avant la connexion.
2.  Retirez le capot supérieur et retirez le collier de serrage.
3.  Connectez les bornes L et N de l'alimentation électrique aux bornes de ligne et neutre du PRL respectivement à travers le trou de câblage.
4.  En fonction de l'appareil que vous souhaitez contrôler via le relais, sélectionnez la borne NO ou NC et câblez le relais avec l'appareil pour établir une connexion normale ouverte ou normale avec l'appareil.
5.  Après avoir terminé le câblage de l'appareil, remplacez la pince anti-traction, utilisez la boucle de câblage pour gérer les fils et placez la boucle de câblage sur la base avec son espace (ouverture) positionné sur la gauche (comme dans le schéma ci-dessous).

![](<.gitbook/assets/4 (54).jpeg>)

1.  Remplacez le capot supérieur. Allumez l’alimentation pour allumer le contrôleur de relais.

2

**Configuration du réseau ZigBee**

![](<.gitbook/assets/5 (34).jpeg>)

-   _**Directives relatives aux appareils ZigBee**_

ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

![](<.gitbook/assets/6 (44).jpeg>)

-   _**Rejoindre le réseau ZigBee**_

En tant qu'appareil ZigBee, le contrôleur de relais doit rejoindre un réseau ZigBee pour recevoir des commandes. Veuillez suivre les étapes ci-dessous pour rejoindre le contrôleur de relais dans un réseau ZigBee.

-   1.  Connectez l'entrée d'alimentation au contrôleur de relais conformément aux instructions d'installation ci-dessus et mettez le contrôleur de relais sous tension.
    2.  Appuyez et maintenez enfoncé le bouton de fonction pendant 10 secondes pendant que le contrôleur de relais se réinitialise et commence à rechercher le réseau ZigBee existant. Veuillez vous assurer que la fonction d'autorisation de rejoindre sur le routeur ou le coordinateur de votre réseau ZigBee est activée.
    3.  Si le contrôleur de relais rejoint avec succès un réseau ZigBee, l'indicateur LED clignote deux fois pour confirmer.
    4.  Après avoir rejoint le réseau ZigBee, le contrôleur de relais sera automatiquement enregistré dans le réseau. Veuillez vérifier auprès du coordinateur du réseau ZigBee, du panneau de contrôle du système ou du CIE (équipement de contrôle et d'indication) pour confirmer si l'adhésion et l'enregistrement ont réussi.
    5.  Après avoir rejoint le réseau ZigBee, si le contrôleur de relais perd la connexion au réseau ZigBee actuel, l'indicateur LED clignote toutes les 20 minutes. Veuillez vérifier l'état de votre réseau ZigBee et la plage de signal du contrôleur de relais pour corriger la condition.
-   _**Suppression d'un appareil du réseau ZigBee (réinitialisation d'usine)**_

![](<.gitbook/assets/7 (39).png>)

Pour supprimer le contrôleur de relais du réseau ZigBee actuel, l'appareil doit être mis en configuration d'usine pour terminer la suppression de l'appareil. La fonction de réinitialisation d'usine effacera l'appareil de ses paramètres et informations stockés et l'invitera à rechercher un nouveau réseau ZigBee.

**Avant de retirer l'appareil, assurez-vous que le contrôleur de relais se trouve dans la plage actuelle du signal réseau ZigBee.**

-   1.  Appuyez et maintenez le bouton de fonction pendant 10 secondes, puis relâchez le bouton pour réinitialiser le contrôleur de relais.
    2.  Lors de la réinitialisation, l'appareil effacera les paramètres réseau ZigBee actuels et transmettra le signal au coordinateur ZigBee pour se retirer du réseau ZigBee actuel. Il recherchera ensuite à nouveau activement le réseau ZigBee disponible et rejoindra automatiquement le réseau.
-   _**Mise à niveau du micrologiciel OTA (pour la version OTA uniquement)**_

Le contrôleur de puissance prend en charge la fonction de mise à niveau du micrologiciel OTA via le réseau ZigBee, qui peut être lancée à partir du coordinateur du réseau ZigBee. Suivez les étapes ci-dessous pour effectuer la mise à niveau du micrologiciel OTA.

**Étape 1.**Vous devez accéder à votre coordinateur ZigBee pour effectuer la mise à niveau du micrologiciel en direct.

**Étape 2.**Sur la page Web de configuration, sélectionnez l'appareil que vous souhaitez mettre à niveau et sélectionnez le nouveau

Micrologiciel ZigBee fourni. Veuillez vous référer au manuel d'utilisation du coordinateur ZigBee pour plus de détails.

**Étape 3.**Appuyez sur « OK » pour démarrer le processus de mise à niveau et la LED continuera de clignoter. Pendant le processus OTA, veuillez ne pas effectuer d'autres actions ni éteindre le panneau.

**Étape 4.**La durée d'une mise à niveau prendra environ 20 à 30 minutes. Veuillez noter que la durée peut varier en fonction de la taille du fichier ou de la distance entre votre accessoire et le coordinateur.

**Étape 5.**Attendez que le micrologiciel termine la mise à jour. Lorsque la progression atteint 100 %, l'appareil se réinitialise automatiquement. Vous pouvez également actualiser à nouveau la page Web pour vous assurer que le micrologiciel de l'appareil est correctement mis à jour avec la version la plus récente affichée.

![](<.gitbook/assets/8 (40).png>)

-   _**Capacité du périphérique du routeur ZigBee (PRL-8ZBSR-AC uniquement)**_

Le modèle de contrôleur de relais avec fonction routeur permet à d'autres appareils ZigBee de rejoindre le réseau ZigBee via le routeur. Il a une capacité maximale de 40 appareils/routeurs.

**Opération**

![](<.gitbook/assets/9 (29).jpeg>)

-   _**Contrôle des relais**_
    -   Lorsque le contrôleur de relais a rejoint avec succès un réseau ZigBee, la passerelle/panneau de commande pourra le contrôler à distance pour l'allumer, l'éteindre ou basculer entre les conditions marche et arrêt. Veuillez vous référer à votre passerelle/panneau de contrôle ZigBee pour plus de détails.

3

**Annexe (Pour les développeurs uniquement)**

![](<.gitbook/assets/10 (40).png>)

-   _**ID du cluster de relais**_

**ID de l'appareil : On Off Sortie : 0x0002**

**Point de terminaison : 0x0A**

| **Du côté serveur**                                          |                   |                          |                  |                  |               |          |                  |                  |             |                 |            | **Côté client** |                 |   |   |
| ------------------------------------------------------------ | ----------------- | ------------------------ | ---------------- | ---------------- | ------------- | -------- | ---------------- | ---------------- | ----------- | --------------- | ---------- | --------------- | --------------- | - | - |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  | **Obligatoire**  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| De base (0x0000)                                             |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 | _Aucun_         |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| Identifier (0x0003)                                          |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| Marche/Arrêt (0x0006)                                        |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  | **Facultatif**   |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| Groupes (0x0004)                                             |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 | Aucun           |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| _**Attribut des informations de base sur le cluster**_      |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| **Identifier**                                               |                   | **Nom**                  | **Taper**        |                  | **Gamme**     |          | **Accéder**      | **Défaut**       |             | **Obligatoire** |            |                 |                 |   |   |
|                                                              |                   |                          |                  | **/ Facultatif** |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| 0x0000                                                       |                   | _Version ZCL_            | 8 bits non signé |                  | 0x00 –0xff    |          | Lire             | 0x01             |             | M.              |            |                 |                 |   |   |
|                                                              | entier            |                          |                  | seulement        |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| 0x0001                                                       |                   | Version de l'application | 8 bits non signé |                  | 0x00 – 0xff   |          | Lire             | 0x00             |             | Ô               |            |                 |                 |   |   |
|                                                              | entier            |                          |                  | seulement        |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| 0x0003                                                       |                   | _Version matérielle_     | 8 bits non signé |                  | 0x00 –0xff    |          | Lire             | 0                |             | Ô               |            |                 |                 |   |   |
|                                                              | entier            |                          |                  | seulement        |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| 0x0004                                                       |                   | _Nom du Fabricant_       | Personnage       |                  | 0 – 32 octets |          | Lire             | Climax           |             | Ô               |            |                 |                 |   |   |
|                                                              | Chaîne            |                          |                  | seulement        | Technologie   |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| 0x0005                                                       |                   | _Identifiant du modèle_  | Personnage       |                  | 0 – 32 octets |          | Lire             | (Version modèle) |             | Ô               |            |                 |                 |   |   |
|                                                              | Chaîne            |                          |                  | seulement        |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| 0x0006                                                       |                   | _CodeDate_               | Personnage       |                  | 0 – 16 octets |          | Lire             |                  |             | Ô               |            |                 |                 |   |   |
|                                                              | Chaîne            |                          |                  | seulement        |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| 0x0007                                                       |                   | _Source d'énergie_       | 8 bits           |                  | 0x00 –0xff    |          | Lire             |                  |             | M.              |            |                 |                 |   |   |
|                                                              |                   |                          | seulement        |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| 0x0010                                                       |                   | _EmplacementDescription_ | Personnage       |                  | 0 – 32 octets |          | Lire /           |                  |             | Ô               |            |                 |                 |   |   |
|                                                              | Chaîne            |                          |                  | Écrire           |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| 0x0011                                                       |                   | _Environnement physique_ | 8 bits           |                  | 0x00 –0xff    |          | Lire /           | 0x00             |             | Ô               |            |                 |                 |   |   |
|                                                              |                   |                          | Écrire           |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| 0x0012                                                       |                   | _Appareil activé_        | Booléen          |                  | 0x00 –0x01    |          | Lire /           | 0x01             |             | M.              |            |                 |                 |   |   |
|                                                              |                   |                          | Écrire           |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| _**Attribut des informations d'identification du cluster**_ |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| **Identifier**                                               |                   | **Nom**                  | **Taper**        |                  | **Gamme**     |          | **Accéder**      | **Défaut**       |             | **Obligatoire** |            |                 |                 |   |   |
|                                                              |                   |                          |                  | **/ Facultatif** |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| 0x0000                                                       |                   | _Identifier l'heure_     | Non signé        |                  | 0x00 –0xffff  |          | Lire /           | 0x0000           |             | M.              |            |                 |                 |   |   |
|                                                              | Entier de 16 bits |                          |                  | Écrire           |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| _**Attribut des informations sur le cluster marche/arrêt**_ |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| **Identifier**                                               |                   | **Nom**                  | **Taper**        |                  | **Gamme**     |          | **Accéder**      | **Défaut**       |             | **Obligatoire** |            |                 |                 |   |   |
|                                                              |                   |                          |                  | **/ Facultatif** |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| 0x0000                                                       |                   | _Allumé éteint_          | Booléen          |                  | 0x00 –0x01    |          | Lire             | 0x00             |             | M.              |            |                 |                 |   |   |
|                                                              |                   |                          | seulement        |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| _**Attributs du cluster Groupes Informations**_             |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| **Identifier**                                               |                   | **Nom**                  |                  | **Taper**        |               |          | **Gamme**        |                  | **Accéder** |                 | **Défaut** |                 | **Obligatoire** |   |   |
|                                                              |                   |                          |                  |                  |               |          | **/ Facultatif** |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |
| 0x0000                                                       |                   | _NomSupport_             |                  | Bitmap 8 bits    |               | x0000000 |                  | Lire             |             | -               |            | M.              |                 |   |   |
|                                                              |                   |                          |                  |                  | seulement     |          |                  |                  |             |                 |            |                 |                 |   |   |
|                                                              |                   |                          |                  |                  |               |          |                  |                  |             |                 |            |                 |                 |   |   |

![](<.gitbook/assets/11 (31).png>)![](<.gitbook/assets/12 (35).png>)![](<.gitbook/assets/13 (26).png>)

4
