# VESTA 179

**Contrôle de l'obturateur (SCM-5ZBS)**

**Introduction**

SCM-5ZBS est un contrôle d'obturation ZigBee. L'utilisateur peut contrôler le SCM via le réseau ZigBee à distance ou manuellement en reliant un interrupteur au contrôle d'obturation.

Le contrôle d'obturation utilise la technologie ZigBee pour la transmission du signal sans fil. ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

Le Shutter Control sert de périphérique final dans le réseau ZigBee. Il peut être inclus dans le réseau ZigBee pour transmettre ou recevoir un signal, mais ne peut permettre à aucun autre appareil ZigBee de rejoindre le réseau via le contrôle de l'obturateur.

La série SCM-5 ZigBee Shutter Control comprend les modèles suivants :

SCM-5ZBS

SCM-5ZBS-OTA

![](<.gitbook/assets/0 (68).jpeg>)

**Identification des pièces**

**1. Indicateur LED**

L'indicateur LED est utilisé pour indiquer l'état du contrôle d'obturation :

-   -   Clignote une fois : la commande d'obturation est réinitialisée.
    -   Clignote deux fois : Le Shutter Control a rejoint avec succès un réseau ZigBee.
    -   Clignote 5 fois : calibrage manuel réussi.
    -   Clignote une fois toutes les 20 minutes :

Le Shutter Control a perdu la connexion à son réseau ZigBee actuel.

1.  **Bouton de fonction**
    -   Appuyer une fois : transmettre un signal de supervision.
    -   Appuyez et maintenez pendant 3~9 secondes : entrez en mode d'étalonnage.
    -   Appuyez et maintenez pendant 10 secondes : réinitialisez le contrôle de l'obturateur pour rejoindre le réseau ZigBee.
2.  **Câble de connexion d'entrée d'alimentation N (fil neutre) (bleu)**
3.  **Câble de connexion d'entrée d'alimentation L (Live Lead) (marron)**
4.  **Câble de connexion du commutateur local S2 (direction de fermeture) (orange)**

Connectez un commutateur externe au câble. Activez cet interrupteur pour contrôler que le volet roule dans la direction « Fermer » en activant la sortie du moteur O2.

L'activation de cet interrupteur lorsque le volet roule vers l'ouverture arrêtera le volet.

**6. Câble de connexion du commutateur local S1 (direction ouverte) (rouge)**

Connectez un commutateur externe au câble. Activez cet interrupteur pour contrôler que le volet roule vers la direction « Ouvert » en activant la sortie du moteur O1. L'activation de cet interrupteur lorsque le volet roule vers la direction « Fermé » arrêtera le volet.

**7. Câble de connexion de la sortie moteur O1 (sens ouvert) (jaune)**

Connectez-vous à la borne ouverte du moteur de volet roulant.

**8. Câble de connexion de la sortie moteur O2 (direction fermée) (vert)**

Connectez-vous à la borne de fermeture du moteur d'obturation.

**spécification**

-   Alimentation : 110 - 230 VCA, 50/60 Hz
-   Courant de charge pris en charge : 1/4 HP (puissance en chevaux) ; 1,8 A pour les moteurs à facteur de puissance compensé (charges inductives)
-   Protocole de communication : ZigBee Pro Domotique 1.2, 2,4 GHz

1

![](<.gitbook/assets/1 (60).jpeg>)**Prudence**

-   Tous les travaux sur l'appareil, y compris l'installation et la maintenance, doivent être effectués par un électricien qualifié et agréé.
-   Avant l'installation ou tout travail de maintenance, assurez-vous que l'alimentation électrique a été débranchée.
-   Ne connectez pas l'appareil à des charges dépassant le courant de charge pris en charge.
-   Veuillez connecter l'appareil uniquement à un moteur alimenté en courant alternatif.

**Configuration du réseau ZigBee**

-   _**Directives relatives aux appareils ZigBee**_

ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un certain nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

-   _**Rejoindre le réseau ZigBee**_

En tant qu'appareil ZigBee, le Shutter Control doit rejoindre un réseau ZigBee pour recevoir des commandes. Veuillez suivre les étapes ci-dessous pour rejoindre le contrôle d'obturation dans un réseau ZigBee.

-   1.  Connectez le câble d'alimentation au câble de connexion d'entrée d'alimentation (bleu et marron) sur la commande d'obturation avec le connecteur fourni.
    2.  Appuyez et maintenez enfoncé le bouton de fonction pendant 10 secondes pendant que le contrôle de l'obturateur se réinitialise et commence à rechercher le réseau ZigBee existant. Veuillez vous assurer que la fonction d'autorisation de rejoindre sur le routeur ou le coordinateur de votre réseau ZigBee est activée.
    3.  Si le contrôle d'obturation rejoint avec succès un réseau ZigBee, l'indicateur LED clignotera deux fois pour confirmer.
    4.  Après avoir rejoint le réseau ZigBee, le Shutter Control sera automatiquement enregistré dans le réseau. Veuillez vérifier auprès du coordinateur du réseau ZigBee, du panneau de contrôle du système ou du CIE (équipement de contrôle et d'indication) pour confirmer si l'adhésion et l'enregistrement ont réussi.
    5.  Après avoir rejoint le réseau ZigBee, si le Shutter Control perd la connexion au réseau ZigBee actuel, l'indicateur LED clignote toutes les 20 minutes. Veuillez vérifier l'état de votre réseau ZigBee et la plage du signal de commande d'obturation pour corriger la condition.
-   _**Suppression d'un appareil du réseau ZigBee (réinitialisation d'usine)**_

Pour supprimer le contrôle de l'obturateur du réseau ZigBee actuel, le contrôle de l'obturateur doit être mis en réinitialisation d'usine pour terminer la suppression de l'appareil. La fonction de réinitialisation d'usine effacera le contrôle d'obturation de ses informations de configuration stockées et invitera l'appareil à rechercher un nouveau réseau ZigBee.

**Avant de retirer l'appareil, assurez-vous que le contrôle de l'obturateur se trouve dans la plage actuelle du signal réseau ZigBee.**

1.  Appuyez et maintenez le bouton de fonction pendant 10 secondes, puis relâchez le bouton pour réinitialiser le contrôle de l'obturateur.
2.  Lors de la réinitialisation, le contrôle d'obturation effacera les paramètres réseau ZigBee actuels et transmettra le signal au coordinateur ZigBee pour se retirer du réseau ZigBee actuel. Il recherchera ensuite à nouveau activement le réseau ZigBee disponible et rejoindra automatiquement le réseau.

**Surveillance**

Le contrôle d'obturation transmettra un signal de supervision pour signaler régulièrement son état en fonction des paramètres de l'utilisateur. L'intervalle par défaut est de 30 minutes. L'utilisateur peut également appuyer une fois sur le bouton de fonction pour transmettre manuellement un signal de supervision.

**Installation**

-   _**Câblage avec connecteur d'épissure**_
    -   Le SCM-5 est livré avec des fils terminaux et des pinces intégrés (connecteurs d'épissure Wago 221).
    -   Les connecteurs à 2 fils acceptent les fils solides et toronnés de 0,2 à 4 mm² (24 à 12 AWG).
    -   Veuillez connecter le SCM-5 à l'alimentation secteur, aux interrupteurs locaux et au moteur de volet avec les connecteurs.
    -   Avant le câblage, assurez-vous que l'alimentation est coupée. Pour connecter les fils :
        1.  Soulevez le levier et insérez le fil.**(Photo 1, 2)**

2

**Image 1****Image 2**

![](<.gitbook/assets/2 (61).png>)

1.  Repoussez le levier vers le bas. Le boîtier transparent vous permet de vérifier si le fil est correctement connecté. Assurez-vous que le fil est bien maintenu en place et ne se détachera pas.**(Photo 3, 4)**

**Image 3****Image 4**

![](<.gitbook/assets/3 (62).png>)

-   1.  De la même manière qu'aux étapes 1 et 2, connectez les autres fils avec des connecteurs.
-   Le SCM-5 doit être connecté selon le schéma ci-dessous :

![](<.gitbook/assets/4 (47).jpeg>)

-   Connectez la borne N du SCM à la borne N de l'alimentation.
-   Connectez la borne L du SCM à la borne L de l'alimentation.
-   Connectez la borne O1 du SCM à la borne ouverte du moteur de volet roulant.
-   Connectez la borne O2 du SCM à la borne de fermeture du moteur d'obturation.
-   **(Commutateur local en option)**Connectez les bornes S2 et S1 du SCM à la borne L de l'alimentation.

3

**Opération**

-   _**Étalonnage**_
    -   L’heure d’activation par défaut du contrôle d’obturation est**4**minutes. Lorsque le bouton Haut/Bas est enfoncé ou que le coordinateur du réseau ZigBee transmet la commande Haut/Bas, il activera le moteur de l'obturateur pendant 4 minutes.
    -   Pour que le contrôle d'obturation fonctionne correctement, son temps d'activation doit être calibré. Il existe deux manières de régler le temps d'activation :
        -   **Commande ZigBee :**L'heure d'activation peut être ajustée en envoyant une commande depuis le coordinateur du réseau ZigBee. (Voir Annexe – Attribut de cluster de niveau – OnTransitionTime / OffTransitionTime, unité minimale réglable 100 ms)
        -   **Calibrage manuel :**Calibrez l’activation selon la procédure ci-dessous :
            1.  Avant l'étalonnage, les commutateurs locaux externes doivent être connectés au contrôle d'obturation.
            2.  Appuyez et maintenez enfoncé le bouton Fonction pendant 3~9 secondes et relâchez pour passer en mode calibrage. La commande d'obturation roulera vers la direction « Ouvert » pendant 4 minutes lors de l'entrée en mode d'étalonnage.
            3.  Attendez 4 minutes pour que le contrôle de l'obturateur arrête de rouler dans le sens « Ouvert », puis activez l'interrupteur local externe « Fermeture » ​​connecté pour fermer le volet.
            4.  Activer l'interrupteur local externe « Ouvert » dès que le volet est complètement fermé. Le contrôle de l'obturateur enregistrera le temps qu'il a fallu entre les étapes 3 et 4 comme nouveau "**la période de fermeture**”.
            5.  La commande d'obturation roulera vers la direction ouverte après l'étape 4.
            6.  Activer l'interrupteur local externe « Fermer » dès que le volet est complètement ouvert. Le contrôle de l'obturateur enregistrera le temps qu'il a fallu entre les étapes 5 et 6 comme nouveau "**temps ouvert**”.

Exemple

S'il faut 30 secondes au volet pour passer de l'ouverture à la fermeture et 40 secondes pour passer de la fermeture à l'ouverture, le nouveau**la période de fermeture**sera**30**secondes et nouveau**temps ouvert**sera**40**secondes.

Après l'étalonnage, chaque fois que le contrôle d'obturation reçoit une commande de fermeture, il roulera vers la direction de fermeture pendant 30 secondes. Lorsqu'il reçoit une commande d'ouverture, il roulera vers l'ouverture pendant 40 secondes.

-   -   L'heure d'activation sera réinitialisée à**4**minutes chaque fois que le Shutter Control rejoint un réseau ZigBee.
    -   Si le processus d'étalonnage manuel réussit, la LED clignotera 5 fois pour l'indiquer.
-   _**Contrôle de l'obturateur**_

**Réseau ZigBee**

-   Une fois que le contrôle de volet a rejoint avec succès un réseau ZigBee, le coordinateur peut contrôler à distance l'ouverture, la fermeture ou l'arrêt du volet en transmettant la commande via le réseau ZigBee.
-   Lorsque la commande d'obturation reçoit un signal d'ouverture/fermeture du coordinateur, elle roulera dans la direction d'ouverture/fermeture en fonction du temps d'activation calibré pour ouvrir/fermer complètement l'obturateur.
-   L'état de l'obturateur peut également être ajusté par pourcentage de 0 %, 10 %, 20 %... à 100 % via le coordinateur ZigBee.
-   Le pourcentage d'ouverture actuel est également transmis au coordinateur ZigBee.

**Commutateur local**

-   -   Si un commutateur local en option est connecté, les utilisateurs peuvent également appuyer sur le bouton de commutation pour ouvrir/fermer le volet.
    -   Appuyez et relâchez l'interrupteur pendant moins d'une seconde pour contrôler l'ouverture ou la fermeture complète de l'obturateur.
    -   Appuyez et maintenez l'interrupteur pendant plus d'une seconde pour contrôler l'ouverture et la fermeture de l'obturateur jusqu'à ce que l'interrupteur soit relâché. Lorsque le commutateur est relâché, l’obturateur s’arrête.
    -   Appuyer sur l'interrupteur lorsque l'obturateur se déplace dans la direction opposée arrêtera l'obturateur. Appuyez à nouveau sur l'interrupteur pour ouvrir/fermer l'obturateur.

Par exemple, appuyer sur l'interrupteur vers le bas lorsque le volet s'ouvre arrêtera le volet, appuyez à nouveau sur l'interrupteur vers le bas pour commencer à fermer le volet.

-   _**Mise à niveau du micrologiciel OTA (pour la version OTA uniquement)**_

Le contrôle d'obturation prend en charge la fonction de mise à niveau du micrologiciel OTA via le réseau ZigBee, qui peut être lancée à partir du coordinateur du réseau ZigBee.

Suivez les étapes ci-dessous pour effectuer la mise à niveau du micrologiciel OTA.

**Étape 1.**Vous devez accéder à votre coordinateur ZigBee pour effectuer la mise à niveau du micrologiciel en direct.**Étape 2.**Sur la page Web de configuration, sélectionnez l'appareil que vous souhaitez mettre à niveau et sélectionnez le nouveau

Micrologiciel ZigBee fourni. Veuillez vous référer au manuel d'utilisation du coordinateur ZigBee pour plus de détails.

**Étape 3.**Appuyez sur « OK » pour démarrer le processus de mise à niveau et la LED continuera de clignoter. Pendant le processus OTA,

veuillez ne pas effectuer d'autres actions ni éteindre le panneau.

**Étape 4.**La durée d'une mise à niveau prendra environ 20 à 30 minutes. Veuillez noter que la durée peut varier en fonction de la taille du fichier ou de la distance entre votre accessoire et le coordinateur.

**Étape 5.**Attendez que le micrologiciel termine la mise à jour. Lorsque la progression atteint 100 %, l'appareil se réinitialise

4

automatiquement. Vous pouvez également actualiser à nouveau la page Web pour vous assurer que le micrologiciel de l'appareil est correctement mis à jour avec la version la plus récente affichée.

**Annexe (Pour les développeurs uniquement)**

-   _**Commande d'obturateur de relais de puissance avec ID de groupe de compteurs**_

**ID de l'appareil : ombre : 0x0200**

**Point de terminaison : 0x01**

| **Du côté serveur**                                          |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 | **Côté client** |            |                 |   |
| ------------------------------------------------------------ | - | ------------------------ | -------------------- | ------------- | ----------------- | ---------------- | ----------------- | ---------------- | ----------------- | ----------- | ----------- | --------------- | --------------- | ---------- | --------------- | - |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               | **Obligatoire**   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| De base (0x0000)                                             |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 | _Aucun_         |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| Identifier (0x0003)                                          |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| Marche/Arrêt (0x0006)                                        |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| Contrôle de niveau (0x0008)                                  |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| Configuration de l'ombre (0x0x0100)                          |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| Groupes (0x0004)                                             |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| Scènes (0x0005)                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               | **Facultatif**    |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| Aucun                                                        |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 | Aucun      |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| _**Attribut des informations de base sur le cluster**_      |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| **Identifier**                                               |   | **Nom**                  |                      |               | **Taper**         |                  |                   | **Gamme**        |                   | **Accéder** |             | **Défaut**      | **Obligatoire** |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  | **/ Facultatif**  |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| 0x0000                                                       |   | _Version ZCL_            | 8 bits non signé     |               | 0x00 –0xff        |                  | Lecture seulement |                  | 0x01              | M.          |             |                 |                 |            |                 |   |
|                                                              |   |                          | entier               |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| 0x0001                                                       |   | Version de l'application | 8 bits non signé     |               | 0x00 – 0xff       |                  | Lecture seulement |                  | 0x00              | Ô           |             |                 |                 |            |                 |   |
|                                                              |   |                          | entier               |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| 0x0003                                                       |   | _Version matérielle_     | 8 bits non signé     |               | 0x00 –0xff        |                  | Lecture seulement | 0                | Ô                 |             |             |                 |                 |            |                 |   |
|                                                              |   |                          | entier               |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| 0x0004                                                       |   | _Nom du Fabricant_       | Chaîne de caractères |               | 0 – 32 octets     |                  | Lecture seulement |                  | Climax            | Ô           |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      | Technologie   |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| 0x0005                                                       |   | _Identifiant du modèle_  | Chaîne de caractères |               | 0 – 32 octets     |                  | Lecture seulement | (Version modèle) | Ô                 |             |             |                 |                 |            |                 |   |
| 0x0006                                                       |   | _CodeDate_               | Chaîne de caractères |               | 0 – 16 octets     |                  | Lecture seulement |                  |                   | Ô           |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| 0x0007                                                       |   | _Source d'énergie_       |                      |               | 8 bits            |                  | 0x00 –0xff        |                  | Lecture seulement |             |             | M.              |                 |            |                 |   |
| 0x0010                                                       |   | _EmplacementDescription_ | Chaîne de caractères |               | 0 – 32 octets     |                  | Lire écrire       |                  |                   | Ô           |             |                 |                 |            |                 |   |
| 0x0011                                                       |   | _Environnement physique_ |                      |               | 8 bits            |                  | 0x00 –0xff        |                  | Lire écrire       |             | 0x00        | Ô               |                 |            |                 |   |
| 0x0012                                                       |   | _Appareil activé_        |                      |               | Booléen           |                  | 0x00 –0x01        |                  | Lire écrire       |             | 0x01        | M.              |                 |            |                 |   |
| _**Attribut des informations d'identification du cluster**_ |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| **Identifier**                                               |   | **Nom**                  |                      |               | **Taper**         |                  |                   | **Gamme**        |                   | **Accéder** |             | **Défaut**      | **Obligatoire** |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  | **/ Facultatif**  |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| 0x0000                                                       |   | _Identifier l'heure_     | 16 bits non signé    |               | 0x00 –0xffff      |                  | Lire écrire       |                  | 0x0000            | M.          |             |                 |                 |            |                 |   |
|                                                              |   |                          | entier               |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| _**Attribut des informations sur le cluster marche/arrêt**_ |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| **Identifier**                                               |   | **Nom**                  |                      |               | **Taper**         |                  |                   | **Gamme**        |                   | **Accéder** |             | **Défaut**      | **Obligatoire** |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  | **/ Facultatif**  |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| 0x0000                                                       |   | _Allumé éteint_          |                      |               | Booléen           |                  | 0x00 –0x01        |                  | Lecture seulement |             | 0x00        | M.              |                 |            |                 |   |
| _**Attribut des informations sur le cluster de niveaux**_   |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| **Identifier**                                               |   | **Nom**                  |                      |               | **Taper**         |                  | **Gamme**         |                  | **Accéder**       |             | **Défaut**  | **Obligatoire** |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   | **/ Facultatif** |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| 0x0000                                                       |   | _Niveau actuel_          |                      |               | Non signé         |                  | 0x00 –0xff        |                  | Lecture seulement |             | 0x00        | M.              |                 |            |                 |   |
|                                                              |   |                          | Entier de 8 bits     |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| 0x0012                                                       |   | _SurTransitionTime_      |                      |               | 16 bits non signé |                  | 0x0000 –          |                  | Lire écrire       |             | 0x0960      | Ô               |                 |            |                 |   |
|                                                              |   |                          | entier               |               | 0xFFFE            |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| 0x0013                                                       |   | _HorsTransitionTime_     |                      |               | 16 bits non signé |                  | 0x0000 –          |                  | Lire écrire       |             | 0x0960      | Ô               |                 |            |                 |   |
|                                                              |   |                          | entier               |               | 0xFFFE            |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| _**Attributs du cluster Shade Informations**_               |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| **Identifier**                                               |   | **Nom**                  |                      |               | **Taper**         |                  |                   | **Gamme**        |                   | **Accéder** |             | **Défaut**      | **Obligatoire** |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  | **/ Facultatif**  |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| 0x0002                                                       |   | _Statut_                 |                      | Bitmap 8 bits |                   | 0000xxxx B       |                   | Lire écrire      |                   | 00000000B   | M.          |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| 0x0010                                                       |   | _Limite Fermée_          | 16 bits non signé    |               |                   | 0x0001 –         |                   | Lire écrire      |                   | 0x0001      | M.          |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               | entier            |                  |                   | 0xfffe           |                   |             |             |                 |                 |            |                 |   |
| 0x0011                                                       |   | _Mode_                   | Énumération 8 bits   |               | 0x00 – 0xfe       |                  | Lire écrire       |                  | 0x00              | M.          |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| _**Attributs du cluster Groupes Informations**_             |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| **Identifier**                                               |   | **Nom**                  |                      |               | **Taper**         |                  |                   | **Gamme**        |                   |             | **Accéder** |                 |                 | **Défaut** | **Obligatoire** |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  | **/ Facultatif**  |             |             |                 |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  |                   |                  |                   |             |             |                 |                 |            |                 |   |
| 0x0000                                                       |   | _NomSupport_             |                      |               | Bitmap 8 bits     |                  | x0000000          |                  | Lecture seulement |             | -           | M.              |                 |            |                 |   |
|                                                              |   |                          |                      |               |                   |                  | 5                 |                  |                   |             |             |                 |                 |            |                 |   |

-   _**Attributs du cluster Scènes Informations**_

| **Identifier**    | **Nom**            | **Taper**        | **Gamme**   | **Accéder**       | **Défaut** | **Obligatoire** |   |
| ----------------- | ------------------ | ---------------- | ----------- | ----------------- | ---------- | --------------- | - |
| **/ Facultatif**  |                    |                  |             |                   |            |                 |   |
|                   |                    |                  |             |                   |            |                 |   |
| 0x0000            | _Nombre de scènes_ | 8 bits non signé | 0x00 – 0xff | Lecture seulement | 0x00       | M.              |   |
| entier            |                    |                  |             |                   |            |                 |   |
|                   |                    |                  |             |                   |            |                 |   |
| 0x0001            | _Scène actuelle_   | 8 bits non signé | 0x00 – 0xff | Lecture seulement | 0x00       | M.              |   |
| entier            |                    |                  |             |                   |            |                 |   |
|                   |                    |                  |             |                   |            |                 |   |
| 0x0002            | _Groupe actuel_    | Non signé        | 0x0000 –    | Lecture seulement | 0x00       | M.              |   |
| Entier de 16 bits | 0xfff7             |                  |             |                   |            |                 |   |
|                   |                    |                  |             |                   |            |                 |   |
| 0x0003            | _ScèneValide_      | Booléen          | 0x00 – 0x01 | Lecture seulement | 0x00       | M.              |   |
| 0x0004            | _NomSupport_       | Bitmap 8 bits    | x0000000    | Lecture seulement | -          | M.              |   |

6
