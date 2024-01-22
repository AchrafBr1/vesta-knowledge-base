# VESTA 173

**RSB-1ZBS**

**Ampoule intelligente RGBW**

**Introduction**

![](<.gitbook/assets/0 (64).jpeg>)

Le RSB-1ZBS est une ampoule couleur LED intelligente ZigBee. Il comporte à la fois un réglage multicolore et un contrôle du niveau de lumière. Une fois connecté à un réseau ZigBee, l'utilisateur pourra contrôler Light Bulb à distance depuis le coordinateur du réseau ZigBee.

L'ampoule utilise la technologie ZigBee pour la transmission du signal sans fil. ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

L'ampoule sert également de route dans le réseau ZigBee. Après avoir été inclus dans le réseau ZigBee, il permet à d'autres appareils ZigBee de rejoindre le réseau via l'ampoule.

**Configuration du réseau ZigBee**

![](<.gitbook/assets/1 (57).jpeg>)

-   _**Directives relatives aux appareils ZigBee**_

ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

En raison de la structure fondamentale du réseau ZigBee, l'appareil ZigBee recherchera et rejoindra activement le réseau après la mise sous tension.

-   -   Assurez-vous que votre routeur ou coordinateur réseau ZigBee est sous tension avant d'allumer l'appareil ZigBee.
    -   Assurez-vous que votre routeur ou coordinateur réseau ZigBee est sous tension et à portée lorsqu'un appareil ZigBee est en cours d'utilisation.
    -   Ne retirez pas un appareil ZigBee du routeur ou du coordinateur réseau ZigBee sans éteindre l'appareil ZigBee.
-   _**Rejoindre le réseau ZigBee**_

![](<.gitbook/assets/2 (52).jpeg>)

En tant qu'appareil ZigBee, l'ampoule doit rejoindre un réseau ZigBee pour envoyer et recevoir des signaux de commande. Veuillez suivre les étapes ci-dessous pour ajouter l'ampoule au réseau ZigBee.

Étape 1. Faites défiler l'ampoule dans la douille de la lampe. Ne pas encore alimenter.

Étape 2. Activez la fonction d'autorisation de participation sur le routeur ou le coordinateur de votre réseau ZigBee.

Étape 3. Allumez l'ampoule pendant 3~5 secondes. (Pas plus de 5 secondes), puis éteignez-le.

Étape 4. Répétez l'étape 3 trois (3) fois pour un total de quatre (4) cycles ON/OFF.

Étape 5. Allumez l'ampoule pour la 5ème fois, l'appareil se réinitialisera et commencera à rechercher un nouveau réseau ZigBee.

Étape 6. Après avoir rejoint le réseau ZigBee, l'ampoule sera automatiquement enregistrée dans le système de sécurité du réseau. Veuillez vérifier auprès du coordinateur du réseau ZigBee, du panneau de commande du système ou du CIE (équipement de contrôle et d'indication) pour confirmer si l'adhésion et l'enregistrement ont réussi.

![](<.gitbook/assets/3 (61).png>)![](<.gitbook/assets/4 (46).jpeg>)

-   _**Suppression d'un appareil du réseau ZigBee (réinitialisation d'usine)**_

Pour supprimer l'ampoule du réseau ZigBee actuel, l'appareil doit être placé en réinitialisation d'usine pour terminer la suppression de l'appareil. La fonction de réinitialisation d'usine effacera l'ampoule de ses paramètres et informations stockés et invitera l'ampoule à rechercher un nouveau réseau ZigBee.

**Avant de retirer l'appareil, assurez-vous que l'ampoule se trouve dans la plage actuelle du signal du réseau ZigBee.**

1.  Supprimez l'ampoule du panneau de configuration actuel / CIE.
2.  Éteignez l'ampoule.
3.  Allumer l'ampoule pour 3~5 secondes. (Pas plus de 5 secondes), puis éteignez-le.
4.  Répétez l'étape 3 3 fois pour un total de 4 cycles ON/OFF
5.  Allumez l'ampoule pour la 5ème fois, l'appareil se réinitialisera et commencera à rechercher un nouveau réseau ZigBee.
6.  Lors de la réinitialisation, l'ampoule effacera les paramètres réseau ZigBee actuels et transmettra le signal au coordinateur ZigBee pour se retirer du réseau ZigBee actuel. Il recherchera ensuite à nouveau activement le réseau ZigBee disponible et rejoindra automatiquement le réseau.

1

![](<.gitbook/assets/5 (29).jpeg>)![](<.gitbook/assets/6 (39).jpeg>)

-   _**Capacité du périphérique du routeur ZigBee**_

La fonction Ampoule avec routeur permet à d'autres appareils ZigBee de rejoindre le réseau ZigBee via le routeur. L’Ampoule a une capacité maximale de 7 appareils, dont 4 routeurs.

**Caractéristiques**

![](<.gitbook/assets/7 (35).png>)

-   _**Réglage de la couleur et de la saturation**_

La couleur et la saturation de l'ampoule peuvent être ajustées à distance à partir des coordinateurs ZigBee en envoyant des commandes.

![](<.gitbook/assets/8 (38).png>)

-   _**Réglage du niveau de lumière**_

L'ampoule a un éclairage à intensité variable, le pourcentage de lumière peut être ajusté à distance depuis les coordinateurs ZigBee en envoyant des commandes.

![](<.gitbook/assets/9 (36).png>)

-   _**Surveillance**_

L'ampoule transmettra un signal de supervision pour signaler régulièrement son état en fonction des paramètres de l'utilisateur. L'intervalle par défaut est de 10 minutes.

**Annexe (Pour les développeurs uniquement)**

![](<.gitbook/assets/10 (37).png>)

-   _**ID du groupe d'ampoules**_

**ID de l'appareil : Couleur_Intensité variable_Lumière : 0x0102**

**Point de terminaison : 0x01**

| **Du côté serveur**            |                                                                 |                                                           | **Côté client** |         |   |   |
| ------------------------------ | --------------------------------------------------------------- | --------------------------------------------------------- | --------------- | ------- | - | - |
|                                |                                                                 |                                                           |                 |         |   |   |
|                                |                                                                 | **Obligatoire**                                           |                 |         |   |   |
|                                |                                                                 |                                                           |                 |         |   |   |
| De base (0x0000)               |                                                                 |                                                           |                 | _Aucun_ |   |   |
|                                |                                                                 |                                                           |                 |         |   |   |
| Identifier (0x0003)            |                                                                 |                                                           |                 |         |   |   |
|                                |                                                                 |                                                           |                 |         |   |   |
| Groupes (0x0004)               |                                                                 |                                                           |                 |         |   |   |
|                                |                                                                 |                                                           |                 |         |   |   |
| Scènes (0x0005)                |                                                                 |                                                           |                 |         |   |   |
|                                |                                                                 |                                                           |                 |         |   |   |
| MarcheArrêt(0x0006)            |                                                                 |                                                           |                 |         |   |   |
|                                |                                                                 |                                                           |                 |         |   |   |
| Contrôle de niveau (0x0008)    |                                                                 |                                                           |                 |         |   |   |
|                                |                                                                 |                                                           |                 |         |   |   |
| Contrôle des couleurs (0x0300) |                                                                 |                                                           |                 |         |   |   |
|                                |                                                                 |                                                           |                 |         |   |   |
|                                |                                                                 | **Facultatif**                                            |                 |         |   |   |
|                                |                                                                 |                                                           |                 |         |   |   |
| _Aucun_                        |                                                                 |                                                           |                 | _Aucun_ |   |   |
|                                |                                                                 |                                                           |                 |         |   |   |
|                                |                                                                 |                                                           |                 |         |   |   |
| **Cluster de rapports**        |                                                                 | Marche/Arrêt (0x0006)                                     |                 |         |   |   |
| **Attribut de rapport**        |                                                                 | ATTRIDE_SUR_DÉSACTIVÉ (0x0000)                            |                 |         |   |   |
| **Type de données**            |                                                                 | ZCL_TYPE DE DONNÉES_BOOLÉEN                               |                 |         |   |   |
| **minReportInt**               |                                                                 | 0                                                         |                 |         |   |   |
| **maxReportInt**               |                                                                 | valeur par défaut : 0x258 s (600 s)                       |                 |         |   |   |
|                                |                                                                 |                                                           |                 |         |   |   |
| **Cluster de rapports**        |                                                                 | Contrôle de niveau (0x0008)                               |                 |         |   |   |
| **Attribut de rapport**        |                                                                 | ATTRIDE_NIVEAU_ACTUEL_NIVEAU (0x0000)                     |                 |         |   |   |
| **Type de données**            |                                                                 | ZCL_TYPE DE DONNÉES_HIVER8                                |                 |         |   |   |
| **minReportInt**               |                                                                 | 0                                                         |                 |         |   |   |
| **maxReportInt**               |                                                                 | valeur par défaut : 0x258 s (600 s)                       |                 |         |   |   |
|                                |                                                                 |                                                           |                 |         |   |   |
| **Cluster de rapports**        |                                                                 | Contrôle des couleurs (0x0300)                            |                 |         |   |   |
| **Attribut de rapport**        |                                                                 | ATTRIDE_ÉCLAIRAGE_COULEUR_CONTRÔLE_ACTUEL_TEINTE (0x0000) |                 |         |   |   |
| **Type de données**            |                                                                 | ZCL_TYPE DE DONNÉES_HIVER8                                |                 |         |   |   |
|                                | ATTRIDE_ÉCLAIRAGE_COULEUR_CONTRÔLE_ACTUEL_SATURATION (0x0001)   |                                                           |                 |         |   |   |
|                                |                                                                 |                                                           |                 |         |   |   |
| **Type de données**            |                                                                 | ZCL_TYPE DE DONNÉES_HIVER8                                |                 |         |   |   |
|                                | ATTRIDE_ÉCLAIRAGE_COULEUR_CONTRÔLE_COULEUR_TEMPÉRATURE (0x0007) |                                                           |                 |         |   |   |
|                                |                                                                 |                                                           |                 |         |   |   |
| **Type de données**            |                                                                 | ZCL_TYPE DE DONNÉES_UINT16                                |                 |         |   |   |
| **minReportInt**               |                                                                 | 0                                                         |                 |         |   |   |
| **maxReportInt**               |                                                                 | valeur par défaut : 0x258 s (600 s)                       |                 |         |   |   |
|                                |                                                                 | 2                                                         |                 |         |   |   |

![](<.gitbook/assets/11 (22).jpeg>)![](<.gitbook/assets/12 (18).jpeg>)

-   ![](<.gitbook/assets/13 (25).png>)_**Attribut des informations de base sur le cluster**_

| **Identifier**                                               | **Nom**                  | **Taper**        | **Gamme**     | **Accéder**       | **Défaut**         | **Obligatoire** |   |
| ------------------------------------------------------------ | ------------------------ | ---------------- | ------------- | ----------------- | ------------------ | --------------- | - |
| **/ Facultatif**                                             |                          |                  |               |                   |                    |                 |   |
|                                                              |                          |                  |               |                   |                    |                 |   |
| 0x0000                                                       | _Version ZCL_            | 8 bits non signé | 0x00 –0xff    | Lecture seulement | 0x01               | M               |   |
| entier                                                       |                          |                  |               |                   |                    |                 |   |
|                                                              |                          |                  |               |                   |                    |                 |   |
| 0x0003                                                       | Version matérielle       | 8 bits non signé | 0x00 –0xff    | Lecture seulement | 0                  | Ô               |   |
| entier                                                       |                          |                  |               |                   |                    |                 |   |
|                                                              |                          |                  |               |                   |                    |                 |   |
| 0x0004                                                       | _Nom du Fabricant_       | Personnage       | 0 – 32 octets | Lecture seulement | Technologie Climax | Ô               |   |
| Chaîne                                                       |                          |                  |               |                   |                    |                 |   |
|                                                              |                          |                  |               |                   |                    |                 |   |
| 0x0005                                                       | _Identifiant du modèle_  | Personnage       | 0 – 32 octets | Lecture seulement | SLCB_00.00.03.01   | Ô               |   |
| Chaîne                                                       | TC                       |                  |               |                   |                    |                 |   |
|                                                              |                          |                  |               |                   |                    |                 |   |
| 0x0006                                                       | _DateCode_               | Personnage       | 0 – 16 octets | Lecture seulement | 20170124           | Ô               |   |
| Chaîne                                                       |                          |                  |               |                   |                    |                 |   |
|                                                              |                          |                  |               |                   |                    |                 |   |
| 0x0007                                                       | _Source d'énergie_       | 8 bits           | 0x00 –0xff    | Lecture seulement |                    | M               |   |
| Énumération                                                  |                          |                  |               |                   |                    |                 |   |
|                                                              |                          |                  |               |                   |                    |                 |   |
| 0x0010                                                       | _EmplacementDescription_ | Personnage       | 0 – 32 octets | Lire écrire       |                    | Ô               |   |
| chaîne                                                       |                          |                  |               |                   |                    |                 |   |
|                                                              |                          |                  |               |                   |                    |                 |   |
| 0x0011                                                       | _Environnement physique_ | 8 bits           | 0x00 –0xff    | Lire écrire       | 0x00               | Ô               |   |
| Énumération                                                  |                          |                  |               |                   |                    |                 |   |
|                                                              |                          |                  |               |                   |                    |                 |   |
| 0x0012                                                       | _Appareil activé_        | Booléen          | 0x00 –0x01    | Lire écrire       | 0x01               | M               |   |
| _**Attribut des informations d'identification du cluster**_ |                          |                  |               |                   |                    |                 |   |

![](<.gitbook/assets/14 (20).png>)

| **Identifier**                                            | **Nom**              | **Taper** | **Gamme**    | **Accéder** | **Défaut** | **Obligatoire /** |   |
| --------------------------------------------------------- | -------------------- | --------- | ------------ | ----------- | ---------- | ----------------- | - |
| **Facultatif**                                            |                      |           |              |             |            |                   |   |
|                                                           |                      |           |              |             |            |                   |   |
| 0x0000                                                    | _Identifier l'heure_ | Non signé | 0x00 –0xffff | Lire écrire | 0x0000     | M                 |   |
| Entier de 16 bits                                         |                      |           |              |             |            |                   |   |
|                                                           |                      |           |              |             |            |                   |   |
| _**Attribut des informations sur le cluster de groupe**_ |                      |           |              |             |            |                   |   |

![](<.gitbook/assets/15 (19).png>)

| **Identifier**                                                       | **Nom**                    |                             |                            |                  |               | **Taper**         |          |                   |             | **Gamme**         |                   |                   | **Accéder**       |                   |             | **Défaut** | **Obligatoire /** |                   |   |   |   |   |   |   |   |
| -------------------------------------------------------------------- | -------------------------- | --------------------------- | -------------------------- | ---------------- | ------------- | ----------------- | -------- | ----------------- | ----------- | ----------------- | ----------------- | ----------------- | ----------------- | ----------------- | ----------- | ---------- | ----------------- | ----------------- | - | - | - | - | - | - | - |
|                                                                      |                            |                             |                            |                  |               |                   |          |                   |             |                   |                   | **Facultatif**    |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
|                                                                      |                            |                             |                            |                  |               |                   |          |                   |             |                   |                   |                   |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
| 0x0000                                                               | _NomSupport_               |                             |                            |                  | Bitmap 8 bits |                   |          | X0000000          |             | Lecture seulement |                   |                   |                   | -                 |             | M          |                   |                   |   |   |   |   |   |   |   |
| _**Attribut des informations sur le cluster de scènes**_            |                            |                             |                            |                  |               |                   |          |                   |             |                   |                   |                   |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
| **Identifier**                                                       | **Nom**                    |                             |                            |                  |               | **Taper**         |          |                   |             | **Gamme**         |                   |                   | **Accéder**       |                   | **Défaut**  |            | **Obligatoire**   |                   |   |   |   |   |   |   |   |
|                                                                      |                            |                             |                            |                  |               |                   |          |                   |             |                   | **/ Facultatif**  |                   |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
|                                                                      |                            |                             |                            |                  |               |                   |          |                   |             |                   |                   |                   |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
| 0x0000                                                               | _Nombre de scènes_         |                             | Entier non signé de 8 bits |                  | 0x00 – 0xff   |                   |          | Lecture seulement |             | 0x00              |                   | M                 |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
| 0x0001                                                               | _Scène actuelle_           |                             | Entier non signé de 8 bits |                  | 0x00 – 0xff   |                   |          | Lecture seulement |             | 0x00              |                   | M                 |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
| 0x0002                                                               | _Groupe actuel_            | Entier non signé de 16 bits |                            | 0x0000 – 0xfff7  |               | Lecture seulement |          | 0x00              |             | M                 |                   |                   |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
| 0x0003                                                               | _ScèneValide_              |                             |                            |                  |               | Booléen           |          |                   |             | 0x00 – 0x01       |                   |                   | Lecture seulement |                   | 0x00        |            | M                 |                   |   |   |   |   |   |   |   |
| 0x0004                                                               | _NomSupport_               |                             |                            |                  |               | Bitmap 8 bits     |          |                   |             | X0000000          |                   |                   | Lecture seulement |                   | -           |            | M                 |                   |   |   |   |   |   |   |   |
| _**Attribut des informations sur le cluster marche/arrêt**_         |                            |                             |                            |                  |               |                   |          |                   |             |                   |                   |                   |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
| **Identifier**                                                       | **Nom**                    |                             |                            |                  |               | **Taper**         |          |                   |             |                   | **Gamme**         |                   |                   |                   | **Accéder** |            | **Défaut**        | **Obligatoire /** |   |   |   |   |   |   |   |
|                                                                      |                            |                             |                            |                  |               |                   |          |                   |             |                   |                   |                   | **Facultatif**    |                   |             |            |                   |                   |   |   |   |   |   |   |   |
|                                                                      |                            |                             |                            |                  |               |                   |          |                   |             |                   |                   |                   |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
| 0x0000                                                               | _Allumé éteint_            |                             |                            |                  |               | Booléen           |          |                   | 0x00 – 0x01 |                   |                   | Lecture seulement |                   | 0x00              |             | M          |                   |                   |   |   |   |   |   |   |   |
| _**Attribut des informations du cluster de contrôle de niveau**_    |                            |                             |                            |                  |               |                   |          |                   |             |                   |                   |                   |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
| **Identifier**                                                       | **Nom**                    |                             |                            |                  |               | **Taper**         |          |                   |             | **Gamme**         |                   |                   | **Accéder**       |                   | **Défaut**  |            | **Obligatoire**   |                   |   |   |   |   |   |   |   |
|                                                                      |                            |                             |                            |                  |               |                   |          |                   |             |                   | **/ Facultatif**  |                   |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
|                                                                      |                            |                             |                            |                  |               |                   |          |                   |             |                   |                   |                   |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
| 0x0000                                                               | _Niveau actuel_            |                             | Entier non signé de 8 bits |                  | 0x00 – 0xff   |                   |          | Lecture seulement |             | 0x00              |                   | M                 |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
| _**Attribut des informations du cluster de contrôle des couleurs**_ |                            |                             |                            |                  |               |                   |          |                   |             |                   |                   |                   |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
| **Identifier**                                                       | **Nom**                    |                             |                            |                  |               | **Taper**         |          |                   |             | **Gamme**         |                   |                   |                   | **Accéder**       |             | **Défaut** |                   | **Obligatoire**   |   |   |   |   |   |   |   |
|                                                                      |                            |                             |                            |                  |               |                   |          |                   |             |                   |                   | **/ Facultatif**  |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
|                                                                      |                            |                             |                            |                  |               |                   |          |                   |             |                   |                   |                   |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
| 0x0000                                                               | _Teinte actuelle_          |                             |                            |                  |               | Non signé         |          |                   |             | 0x00 – 0xff       |                   |                   |                   | Lecture seulement |             |            | 0x00              |                   | M |   |   |   |   |   |   |
|                                                                      |                            |                             |                            | Entier de 8 bits |               |                   |          |                   |             |                   |                   |                   |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
|                                                                      |                            |                             |                            |                  |               |                   |          |                   |             |                   |                   |                   |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
| 0x0001                                                               | _Saturation actuelle_      |                             |                            |                  | Non signé     |                   |          |                   | 0x00 – 0xfe |                   |                   |                   | Lecture seulement |                   |             | 0x00       |                   | M                 |   |   |   |   |   |   |   |
|                                                                      |                            |                             | Entier de 8 bits           |                  |               |                   |          |                   |             |                   |                   |                   |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
|                                                                      |                            |                             |                            |                  |               |                   |          |                   |             |                   |                   |                   |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
| 0x0007                                                               | _CouleurTempératureMireds_ |                             | Non signé                  |                  |               |                   | 0x0000 – |                   |             |                   | Lecture seulement | 0x00fa (4000K)    |                   | M                 |             |            |                   |                   |   |   |   |   |   |   |   |
|                                                                      | Entier de 16 bits          |                             |                            |                  | 0xfeff        |                   |          |                   |             |                   |                   |                   |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
|                                                                      |                            |                             |                            |                  |               |                   |          |                   |             |                   |                   |                   |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
| 0x0008                                                               | _Mode de couleur_          |                             |                            |                  |               | 8 bits            |          |                   | 0x00 – 0x02 |                   | Lecture seulement |                   |                   | 0x01              |             | M          |                   |                   |   |   |   |   |   |   |   |
|                                                                      |                            |                             |                            | énumération      |               |                   |          |                   |             |                   |                   |                   |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |
|                                                                      |                            |                             |                            |                  |               |                   |          |                   |             |                   |                   |                   |                   |                   |             |            |                   |                   |   |   |   |   |   |   |   |

![](<.gitbook/assets/16 (22).png>)![](<.gitbook/assets/17 (18).png>)![](<.gitbook/assets/18 (22).png>)![](<.gitbook/assets/19 (23).png>)

3
