# VESTA 182

**Parlement**

**Commutateur de relais ZigBee**

**Introduction**

PRLM-CH3-AC-ZBS(R) est un commutateur de relais ZigBee à 3 canaux qui peut être connecté à des appareils filaires et réglé sur l'état Normal Ouvert (N.O.). Après avoir rejoint le réseau ZigBee, le commutateur relais peut être contrôlé via le réseau ZigBee pour activer les appareils connectés.

Le commutateur relais utilise la technologie ZigBee pour la transmission du signal sans fil. ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

Le commutateur relais dispose également d'une fonction de routeur. Il sert de routeur dans le réseau ZigBee. Après avoir été inclus dans le réseau ZigBee, il permet à d'autres appareils ZigBee de rejoindre le réseau via le Relay Switch.

**Identification des pièces**

**Le couvercle supérieur****Base**

![](<.gitbook/assets/0 (71).jpeg>)

1.  **Bouton de commutation 1/Bouton de fonction**
    -   Le bouton de fonction est utilisé pour réinitialiser le commutateur relais afin de rejoindre un réseau ZigBee disponible.
    -   Appuyez et maintenez le bouton pendant 10 secondes, puis relâchez-le pour réinitialiser le commutateur de relais.
    -   Appuyez sur le bouton pour allumer/éteindre le canal relais 1.
2.  **Bouton de commutation 2**
    -   Appuyez sur le bouton pour allumer/éteindre le canal relais 2.
3.  **Bouton de commutation 3**
    -   Appuyez sur le bouton pour allumer/éteindre le canal relais 3.

![](<.gitbook/assets/1 (56).png>)

-   _REMARQUE>_
    -   Lorsque le bouton de commutation 2/3 est enfoncé, le canal relais 2/3 passe instantanément à ON/OFF.
    -   Lorsque le bouton de commutation 1 est enfoncé, le canal de relais 1 passe à ON/OFF après 0,5 seconde, car l'appareil doit identifier si la pression sur le bouton est pour allumer/éteindre ou pour réinitialiser le relais.

1.  **Indicateur LED 1**
2.  **Indicateur LED 2**
3.  **Indicateur LED 3**

Les indicateurs LED 1/2/3 sont utilisés pour indiquer l'état du canal relais 1/2/3 :

-   LED 1 marche/arrêt : relais canal 1 marche/arrêt
-   LED 2 marche/arrêt : relais canal 2 marche/arrêt
-   LED 3 marche/arrêt : relais canal 3 marche/arrêt

1

Lorsqu'elles sont allumées, toutes les LED clignotent séquentiellement pendant 1 cycle.

Toutes les LED clignoteront toutes les secondes après la réinitialisation du relais, indiquant qu'il est en mode d'apprentissage.

Toutes les LED clignoteront trois fois lorsque le relais aura rejoint avec succès un réseau ZigBee.

**7. Trous de montage**

**Bornes de connexion**

Connectez le fil à la borne, serrez la vis pour fermer la tondeuse et maintenez le fil en place. Dévissez pour ouvrir la tondeuse pour retirer le fil connecté à la borne.

1.  **Ligne (entrée CA)**
2.  **Neutre**
3.  **NON (Canal 1)**

Pour une connexion normale ouverte avec l'appareil

1.  **Commun (Canal 1)**
2.  **NON (Canal 2)**

Pour une connexion normale ouverte avec l'appareil

1.  **Commun (Canal 2)**
2.  **NON (Canal 3)**

Pour une connexion normale ouverte avec l'appareil

1.  **Commun (Canal 3)**
2.  **Pince anti-traction**

Les pinces sont utilisées pour fixer les fils et fournir un soulagement de traction pour protéger les fils de la découpe métallique.

**17. Trous de câblage**

**spécification**

-   Alimentation : 100 - 240 V CA
-   Courant de charge pris en charge (pour chaque canal de relais) : 5A, 250VAC ou 5A, 30VDC
-   Fil toronné : 14-22 AWG

**Prudence**

-   Tous les travaux sur l'appareil, y compris l'installation et la maintenance, doivent être effectués par un électricien qualifié et agréé.
-   Avant l'installation ou tout travail de maintenance, assurez-vous que l'alimentation électrique a été débranchée.
-   Ne connectez pas l'appareil à des charges dépassant le courant de charge pris en charge.

**Installation**

Câblez le relais selon les instructions ci-dessous.

1.  Veuillez éteindre l'alimentation avant la connexion.
2.  Retirez le capot supérieur et retirez les colliers de serrage.
3.  Connectez les bornes L et N de l'alimentation électrique aux bornes de ligne et neutre du PRLM respectivement à travers le trou de câblage.
4.  En fonction de l'appareil que vous souhaitez contrôler via le canal relais 1, sélectionnez la borne NO et câblez le canal relais 1 avec l'appareil à travers le trou de câblage pour établir une connexion normale ouverte avec l'appareil.
5.  De la même manière qu'à l'étape 4, connectez le canal relais 2/3 à d'autres appareils filaires.
6.  Une fois le câblage terminé, remplacez les colliers de serrage et le couvercle supérieur. Allumez l’alimentation pour allumer le commutateur de relais.

![](<.gitbook/assets/2 (56).jpeg>)

2

**Configuration du réseau ZigBee**

![](<.gitbook/assets/3 (51).jpeg>)

-   _**Directives relatives aux appareils ZigBee**_

ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

![](<.gitbook/assets/4 (49).jpeg>)

-   _**Rejoindre le réseau ZigBee**_

En tant qu'appareil ZigBee, le relais doit rejoindre un réseau ZigBee pour recevoir des commandes. Veuillez suivre les étapes ci-dessous pour ajouter le relais à un réseau ZigBee.

-   1.  Connectez l'entrée d'alimentation au relais conformément aux instructions d'installation ci-dessus et mettez le commutateur de relais sous tension.
    2.  Appuyez et maintenez enfoncé le bouton de fonction pendant 10 secondes pendant que le relais se réinitialise et commence à rechercher le réseau ZigBee existant. Veuillez vous assurer que la fonction d'autorisation de rejoindre sur le routeur ou le coordinateur de votre réseau ZigBee est activée.
    3.  Si le relais rejoint avec succès un réseau ZigBee, l'indicateur LED clignotera trois fois pour confirmer.
    4.  Après avoir rejoint le réseau ZigBee, le relais sera automatiquement enregistré dans le réseau. Veuillez vérifier auprès du coordinateur du réseau ZigBee, du panneau de commande du système ou du CIE (équipement de contrôle et d'indication) pour confirmer si l'adhésion et l'enregistrement ont réussi.
-   _**Suppression d'un appareil du réseau ZigBee (réinitialisation d'usine)**_

![](<.gitbook/assets/5 (61).png>)

Pour supprimer l'appareil du réseau ZigBee actuel, le commutateur de relais doit être mis en réinitialisation d'usine pour terminer la suppression de l'appareil. La fonction de réinitialisation d'usine effacera l'appareil de ses informations de configuration stockées et invitera l'appareil à rechercher un nouveau réseau ZigBee.

**Avant de retirer l'appareil, assurez-vous que le commutateur de relais se trouve dans la plage actuelle du signal réseau ZigBee.**

-   1.  Supprimez l'appareil du panneau de contrôle actuel / CIE.
    2.  Appuyez et maintenez le bouton de fonction pendant 10 secondes, puis relâchez le bouton pour réinitialiser l'appareil.
    3.  Lors de la réinitialisation, l'appareil effacera les paramètres réseau ZigBee actuels et transmettra le signal au coordinateur ZigBee pour se retirer du réseau ZigBee actuel. Il recherchera ensuite à nouveau activement le réseau ZigBee disponible et rejoindra automatiquement le réseau.
-   _**Test de portée**_

![](<.gitbook/assets/6 (42).png>)

Pour tester si l'appareil est capable de communiquer avec le coordinateur de réseau ZigBee ou le panneau de contrôle :

-   -   Mettez la passerelle/le panneau en mode test de portée (Walk Test).
    -   Appuyez sur le bouton de fonction de l'appareil
    -   La passerelle/le panneau doit afficher si l'appareil se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation de la passerelle/du panneau).
-   _**Capacité du périphérique du routeur ZigBee**_

![](<.gitbook/assets/7 (37).png>)

Le commutateur relais dispose d'une fonction de routeur qui permet à d'autres appareils ZigBee de rejoindre le réseau ZigBee via le routeur. Il a une capacité maximale de 40 appareils/routeurs.

**Surveillance**

Le commutateur de relais transmettra un signal de supervision pour signaler régulièrement l'état ON/OFF du canal de relais 1/2/3 en fonction des paramètres de l'utilisateur. L'intervalle par défaut est de 30 minutes.

**Montage**

-   Une fois que vous avez terminé le test de portée et que vous êtes convaincu que l'appareil est capable de communiquer avec le panneau de commande à l'emplacement choisi, procédez au montage.
-   Débranchez l'alimentation principale.
-   Desserrez la vis de fixation inférieure et retirez le couvercle supérieur du commutateur relais.
-   Utilisez les trous sur la base pour marquer l'emplacement de montage sur le mur.
-   Percez des trous à l'emplacement marqué et insérez des chevilles murales si nécessaire, vissez la base sur l'emplacement de montage.
-   Remettez le capot supérieur et serrez la vis de fixation inférieure.

3

![](<.gitbook/assets/8 (32).jpeg>)

**Opération**

![](<.gitbook/assets/9 (24).jpeg>)

-   _**Contrôle des relais**_
    -   Une fois que le commutateur relais a rejoint avec succès un réseau ZigBee, la passerelle/panneau de commande peut contrôler à distance le canal relais 1/2/3 pour l'allumer/l'éteindre. Veuillez vous référer à votre passerelle/panneau de contrôle ZigBee pour plus de détails.
    -   L'utilisateur peut également appuyer manuellement sur le bouton de commutation 1/2/3 pour allumer/éteindre le canal relais 1/2/3.
-   _**Mise à niveau du micrologiciel OTA**_

![](<.gitbook/assets/10 (18).jpeg>)

Le commutateur relais prend en charge la fonction de mise à niveau du micrologiciel OTA via le réseau ZigBee, qui peut être lancée à partir du coordinateur du réseau ZigBee.

Suivez les étapes ci-dessous pour effectuer la mise à niveau du micrologiciel OTA.

**Étape 1.**Vous devez accéder à votre coordinateur ZigBee pour effectuer la mise à niveau du micrologiciel en direct.**Étape 2.**Sur la page Web de configuration, sélectionnez l'appareil que vous souhaitez mettre à niveau et sélectionnez le

nouveau firmware ZigBee fourni. Veuillez vous référer au manuel d'utilisation du coordinateur ZigBee pour plus de détails.

**Étape 3.**Appuyez sur « OK » pour démarrer le processus de mise à niveau. Pendant le processus OTA, veuillez ne pas effectuer d'autres actions ni éteindre le panneau.

**Étape 4.**La durée d'une mise à niveau prendra environ 20 à 30 minutes. Veuillez noter que la durée peut varier en fonction de la taille du fichier ou de la distance entre votre accessoire et le coordinateur.

**Étape 5.**Attendez que le micrologiciel termine la mise à jour. Lorsque la progression atteint 100 %, l'appareil se réinitialise automatiquement. Vous pouvez également actualiser à nouveau la page Web pour vous assurer que le micrologiciel de l'appareil est correctement mis à jour avec la version la plus récente affichée.

**Annexe (Pour les développeurs uniquement)**

![](<.gitbook/assets/11 (28).png>)

-   _**ID du cluster de relais**_

**ID de l'appareil : On Off Sortie : 0x0002**

**Point de terminaison : 0x0A**

| **Du côté serveur** |                 | **Côté client** |
| ------------------- | --------------- | --------------- |
|                     |                 |                 |
|                     | **Obligatoire** |                 |

De base (0x0000)

Identifier (0x0003)

Marche/Arrêt (0x0006)

_Aucun_

**Facultatif**

Groupes (0x0004)

Aucun

-   _**Attribut des informations de base sur le cluster**_

| **Identifier**   | **Nom**                  | **Taper**        | **Gamme**   | **Accéder** | **Défaut** | **Obligatoire** |   |
| ---------------- | ------------------------ | ---------------- | ----------- | ----------- | ---------- | --------------- | - |
| **/ Facultatif** |                          |                  |             |             |            |                 |   |
|                  |                          |                  |             |             |            |                 |   |
| 0x0000           | _Version ZCL_            | 8 bits non signé | 0x00 –0xff  | Lire        | 0x01       | M               |   |
| entier           | seulement                |                  |             |             |            |                 |   |
|                  |                          |                  |             |             |            |                 |   |
| 0x0001           | Version de l'application | 8 bits non signé | 0x00 – 0xff | Lire        | 0x00       | Ô               |   |
| entier           | seulement                |                  |             |             |            |                 |   |
|                  |                          |                  |             |             |            |                 |   |
| 0x0003           | _Version matérielle_     | 8 bits non signé | 0x00 –0xff  | Lire        | 0          | Ô               |   |
| entier           | seulement                |                  |             |             |            |                 |   |
|                  |                          |                  |             |             |            |                 |   |

4

| 0x0004    | _Nom du Fabricant_       | Personnage  | 0 – 32 octets | Lire   | Climax           | Ô |   |
| --------- | ------------------------ | ----------- | ------------- | ------ | ---------------- | - | - |
| Chaîne    | seulement                | Technologie |               |        |                  |   |   |
|           |                          |             |               |        |                  |   |   |
| 0x0005    | _Identifiant du modèle_  | Personnage  | 0 – 32 octets | Lire   | (Version modèle) | Ô |   |
| Chaîne    | seulement                |             |               |        |                  |   |   |
|           |                          |             |               |        |                  |   |   |
| 0x0006    | _DateCode_               | Personnage  | 0 – 16 octets | Lire   |                  | Ô |   |
| Chaîne    | seulement                |             |               |        |                  |   |   |
|           |                          |             |               |        |                  |   |   |
|           |                          |             |               |        |                  |   |   |
| 0x0007    | _Source d'énergie_       | 8 bits      | 0x00 –0xff    | Lire   |                  | M |   |
| seulement |                          |             |               |        |                  |   |   |
|           |                          |             |               |        |                  |   |   |
| 0x0010    | _EmplacementDescription_ | Personnage  | 0 – 32 octets | Lire / |                  | Ô |   |
| Chaîne    | Écrire                   |             |               |        |                  |   |   |
|           |                          |             |               |        |                  |   |   |
| 0x0011    | _Environnement physique_ | 8 bits      | 0x00 –0xff    | Lire / | 0x00             | Ô |   |
| Écrire    |                          |             |               |        |                  |   |   |
|           |                          |             |               |        |                  |   |   |
| 0x0012    | _Appareil activé_        | Booléen     | 0x00 –0x01    | Lire / | 0x01             | M |   |
| Écrire    |                          |             |               |        |                  |   |   |
|           |                          |             |               |        |                  |   |   |

![](<.gitbook/assets/12 (19).jpeg>)

-   _**Attribut des informations d'identification du cluster**_

![](<.gitbook/assets/13 (22).jpeg>)

| **Identifier**                                               | **Nom**              | **Taper** | **Gamme**    | **Accéder** | **Défaut** | **Obligatoire** |   |
| ------------------------------------------------------------ | -------------------- | --------- | ------------ | ----------- | ---------- | --------------- | - |
| **/ Facultatif**                                             |                      |           |              |             |            |                 |   |
|                                                              |                      |           |              |             |            |                 |   |
| 0x0000                                                       | _Identifier l'heure_ | Non signé | 0x00 –0xffff | Lire /      | 0x0000     | M               |   |
| Entier de 16 bits                                            | Écrire               |           |              |             |            |                 |   |
|                                                              |                      |           |              |             |            |                 |   |
| _**Attribut des informations sur le cluster marche/arrêt**_ |                      |           |              |             |            |                 |   |

![](<.gitbook/assets/14 (22).png>)

| **Identifier**                                   | **Nom**         | **Taper** | **Gamme**  | **Accéder** | **Défaut** | **Obligatoire** |   |
| ------------------------------------------------ | --------------- | --------- | ---------- | ----------- | ---------- | --------------- | - |
| **/ Facultatif**                                 |                 |           |            |             |            |                 |   |
|                                                  |                 |           |            |             |            |                 |   |
| 0x0000                                           | _Allumé éteint_ | Booléen   | 0x00 –0x01 | Lire        | 0x00       | M               |   |
| seulement                                        |                 |           |            |             |            |                 |   |
|                                                  |                 |           |            |             |            |                 |   |
| _**Attributs du cluster Groupes Informations**_ |                 |           |            |             |            |                 |   |

![](<.gitbook/assets/15 (20).png>)

| **Identifier**   | **Nom**      | **Taper**     | **Gamme** | **Accéder** | **Défaut** | **Obligatoire** |   |
| ---------------- | ------------ | ------------- | --------- | ----------- | ---------- | --------------- | - |
| **/ Facultatif** |              |               |           |             |            |                 |   |
|                  |              |               |           |             |            |                 |   |
| 0x0000           | _NomSupport_ | Bitmap 8 bits | x0000000  | Lire        | -          | M               |   |
| seulement        |              |               |           |             |            |                 |   |
|                  |              |               |           |             |            |                 |   |

5
