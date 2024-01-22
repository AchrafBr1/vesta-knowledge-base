# VESTA 175

**PRS5-ZBS(MD)/PRM5-ZBS(MD)**

**Série de commutateurs de relais de puissance**

**Introduction**

La série de commutateurs de relais de puissance comprend les modèles suivants :

**PRS5-ZBS :**Interrupteur d'alimentation du relais ZigBee

**PRS5-ZBSR :**Commutateur d'alimentation à relais ZigBee avec fonction routeur

**prm5-zbus :**Interrupteur d'alimentation à relais ZigBee avec compteur

**prm5-jabsr :**Interrupteur d'alimentation à relais ZigBee avec fonction compteur et routeur

Les interrupteurs d'alimentation sont capables de recevoir des signaux sans fil du coordinateur du réseau Zigbee pour allumer/éteindre les appareils qui y sont connectés.

Le commutateur de relais de puissance utilise la technologie ZigBee pour la transmission du signal sans fil. ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

Les modèles dotés de fonctions de compteur ont la particularité supplémentaire de suivre la consommation d'énergie grâce au compteur d'énergie intégré et de transmettre régulièrement les données au coordinateur.

Les modèles avec fonction routeur servent également de routeur dans le réseau ZigBee. Après avoir été inclus dans le réseau ZigBee, il permet à d'autres appareils ZigBee de rejoindre le réseau via le Power Switch.

Les modèles dotés de la fonction OTA prennent en charge la fonction de mise à niveau du micrologiciel OTA via le réseau ZigBee, qui peut être lancée à partir du coordinateur du réseau ZigBee.

![](<.gitbook/assets/0 (66).jpeg>)

| **Numéro de modèle.** | **Mètre** | **Routeur ZigBee** | **COMMANDE** |
| --------------------- | --------- | ------------------ | ------------ |
|                       |           |                    |              |
| **PRS5-ZBS**          | **Non**   | **Non**            | **Non**      |
|                       |           |                    |              |
| **Isthmique**         | **Non**   | **Non**            | **Oui**      |
|                       |           |                    |              |
| **PRS5-ZBSR**         | **Non**   | **Oui**            | **Non**      |
|                       |           |                    |              |
| **Isthmique**         | **Non**   | **Oui**            | **Oui**      |
|                       |           |                    |              |
| **prm5-zbus**         | **Oui**   | **Non**            | **Non**      |
|                       |           |                    |              |
| **prm5-zabus-ata**    | **Oui**   | **Non**            | **Oui**      |
|                       |           |                    |              |
| **prm5-jabsr**        | **Oui**   | **Oui**            | **Non**      |
|                       |           |                    |              |
| **Prm5-Jabsr-Aata**   | **Oui**   | **Oui**            | **Oui**      |
|                       |           |                    |              |

**Identification des pièces**

**1. Indicateur LED**

L'indicateur LED est utilisé pour indiquer l'état du commutateur de relais de puissance :

-   -   Sur:

Le commutateur du relais de puissance est activé.

-   -   Désactivé:

Le commutateur du relais de puissance est éteint.

-   -   Clignote deux fois :

Le commutateur relais de puissance a rejoint avec succès un réseau ZigBee.

-   -   Clignote 5 fois

Le commutateur de relais de puissance s'est lié avec succès à un contrôleur

-   -   Clignote toutes les 20 minutes

Le commutateur relais de puissance a perdu la connexion à son réseau ZigBee actuel

1.  **Bouton de fonction**

**Utilisation du bouton de fonction :**

-   -   Appuyez sur le bouton pour activer/désactiver le commutateur de relais de puissance.
    -   Appuyez et maintenez le bouton pendant 10 secondes, puis relâchez-le pour réinitialiser le commutateur du relais de puissance.
    -   Appuyez et maintenez le bouton pendant 3 secondes puis relâchez pour vous lier à un contrôleur

1.  **Câble de connexion du commutateur externe 1**

1

1.  **Câble de connexion du commutateur externe 2**
2.  **Sortie de charge de puissance de ligne CA**
3.  **Entrée de puissance neuronale CA/Sortie de charge de puissance neutre CA**
4.  **Entrée d'alimentation secteur CA**

**Configuration du réseau ZigBee**

-   _**Directives relatives aux appareils ZigBee**_

ZigBee est un protocole de communication sans fil fiable, à faible consommation d'énergie et à haute efficacité de transmission. Basé sur la norme IEEE802.15.4, ZigBee permet d'inclure un grand nombre d'appareils dans un réseau et de les coordonner pour l'échange de données et la transmission de signaux.

En raison de la structure fondamentale du réseau ZigBee, l'appareil ZigBee recherchera et rejoindra activement le réseau après la mise sous tension.

-   _**Rejoindre le réseau ZigBee**_

En tant qu'appareil ZigBee, le commutateur relais de puissance doit rejoindre un réseau ZigBee pour recevoir des commandes et transmettre des informations sur la consommation d'énergie. Veuillez suivre les étapes ci-dessous pour rejoindre le commutateur de relais de puissance dans un réseau ZigBee.

-   1.  Connectez le commutateur de relais de puissance au câble d'alimentation.
    2.  Appuyez et maintenez le bouton Fonction pendant 10 secondes, puis relâchez-le pour rejoindre le réseau. Veuillez vous assurer que la fonction d'autorisation de rejoindre sur le routeur ou le coordinateur de votre réseau ZigBee est activée.
    3.  Si le commutateur de relais de puissance rejoint avec succès un réseau ZigBee, l'indicateur LED clignote deux fois pour confirmer.
    4.  Après avoir rejoint le réseau ZigBee, le commutateur relais de puissance sera automatiquement enregistré dans le réseau. Veuillez vérifier auprès du coordinateur du réseau Zigbee, du panneau de contrôle du système ou du CIE (équipement de contrôle et d'indication) pour confirmer si l'adhésion et l'enregistrement ont réussi.
    5.  Si l'enregistrement et l'adhésion au réseau échouent, veuillez vérifier votre coordinateur de réseau ZigBee, votre panneau de commande système ou les paramètres CIE pour vous assurer que la fonction d'autorisation de participation est disponible, puis utilisez la fonction de réinitialisation d'usine ci-dessous pour rejoindre le réseau ZigBee.
-   _**Liaison avec le contrôleur**_

Après avoir rejoint le réseau ZigBee, le commutateur de relais de puissance peut se lier à un dispositif de contrôle qui peut être utilisé pour ajuster le niveau de puissance de sortie du commutateur de relais de puissance. Pour lier le commutateur de relais de puissance et l'appareil :

-   1.  Appuyez et maintenez le bouton de fonction pendant 3 secondes, puis relâchez le bouton. Le commutateur de relais de puissance enverra une demande contraignante au coordinateur.
    2.  Reportez-vous au manuel de votre contrôleur pour envoyer une demande de liaison pour l'appareil dans les 16 secondes.
    3.  Si la liaison réussit, le voyant LED du commutateur de relais de puissance clignotera 5 fois pour confirmer. Vous pouvez maintenant utiliser le contrôleur pour régler le niveau de sortie de puissance du commutateur de relais de puissance.
    4.  Si la liaison échoue, veuillez réessayer le processus de liaison.
-   _**Suppression d'un appareil du réseau ZigBee (réinitialisation d'usine)**_

Pour supprimer l'interrupteur d'alimentation du réseau ZigBee actuel, l'interrupteur d'alimentation doit être mis en réinitialisation d'usine pour terminer la suppression de l'appareil. La fonction de réinitialisation d'usine effacera le commutateur d'alimentation de ses paramètres et informations stockés et invitera le commutateur d'alimentation à rechercher un nouveau réseau ZigBee.

**Avant de retirer l'appareil, assurez-vous que l'interrupteur d'alimentation se trouve dans la plage actuelle du signal réseau ZigBee.**

-   1.  Appuyez et maintenez le bouton de fonction pendant 10 secondes, puis relâchez le bouton pour réinitialiser l'interrupteur d'alimentation.
    2.  Lors de la réinitialisation, l'interrupteur d'alimentation effacera les paramètres réseau ZigBee actuels et transmettra le signal au coordinateur ZigBee pour se retirer du réseau ZigBee actuel. Il recherchera ensuite à nouveau activement le réseau ZigBee disponible et rejoindra automatiquement le réseau.
-   _**Capacité du périphérique de routeur ZigBee (PRS5-ZBSR/PRM5-ZBSR uniquement)**_

Les modèles Power Switch avec fonction routeur permettent à d'autres appareils ZigBee de rejoindre le réseau ZigBee via le routeur. Le routeur Power Switch a une capacité maximale de 40 appareils, dont 10 routeurs ; le routeur Power Switch Meter a une capacité maximale de 10 appareils, dont 5 routeurs.

| **Numéro de modèle.**     | **Appareil ZigBee maximal** | **ZigBee maximal** |   |
| ------------------------- | --------------------------- | ------------------ | - |
| **+ Capacité du routeur** | **Capacité du routeur**     |                    |   |
|                           |                             |                    |   |
|                           |                             |                    |   |
| **PRS5-ZBSR**             | **40**                      | **10**             |   |
|                           |                             |                    |   |
| **prm5-jabsr**            | **10**                      | **5**              |   |
|                           |                             |                    |   |

-   _**Mise à niveau du micrologiciel OTA (pour la version OTA uniquement)**_

Le commutateur de relais de puissance prend en charge la fonction de mise à niveau du micrologiciel OTA via le réseau ZigBee, qui peut être lancée à partir du coordinateur du réseau ZigBee. Suivez les étapes ci-dessous pour effectuer la mise à niveau du micrologiciel OTA.

2

**Étape 1.**Vous devez accéder à votre coordinateur ZigBee pour effectuer la mise à niveau du micrologiciel en direct.**Étape 2.**Sur la page Web de configuration, sélectionnez l'appareil que vous souhaitez mettre à niveau et sélectionnez le nouveau

Micrologiciel ZigBee fourni. Veuillez vous référer au manuel d'utilisation du coordinateur ZigBee pour plus de détails.

**Étape 3.**Appuyez sur « OK » pour démarrer le processus de mise à niveau et la LED continuera à clignoter. Pendant le processus OTA,

veuillez ne pas effectuer d'autres actions ni éteindre le panneau.

**Étape 4.**La durée d'une mise à niveau prendra environ 20 à 30 minutes. Veuillez noter que la durée peut varier en fonction de la taille du fichier ou de la distance entre votre accessoire et le coordinateur.

**Étape 5.**Attendez que le micrologiciel termine la mise à jour. Lorsque la progression atteint 100 %, l'appareil se réinitialise automatiquement. Vous pouvez également actualiser à nouveau la page Web pour vous assurer que le micrologiciel de l'appareil est correctement mis à jour avec la version la plus récente affichée.

**Prudence**

-   Tous les travaux sur l'appareil, y compris l'installation et la maintenance, doivent être effectués par un électricien qualifié et agréé.
-   Avant l'installation ou tout travail de maintenance, assurez-vous que l'alimentation électrique a été débranchée.
-   Ne connectez pas l'appareil à des charges dépassant le courant de charge pris en charge.

**Installation**

-   _**Câblage avec connecteur d'épissure**_
    -   Le commutateur de relais de puissance est livré avec un câble intégré pour la connexion à l'alimentation secteur, à l'appareil et au commutateur externe. Cinq connecteurs d'épissure Wago 221 sont fournis pour la connexion.
    -   Les connecteurs à 2 fils/3 fils acceptent les fils solides et toronnés de 0,2 à 4 mm² (24 à 12 AWG).
    -   Avant le câblage, assurez-vous que l'alimentation est coupée. Pour connecter les fils :
        1.  Soulevez le levier et insérez le fil marron.**(Photo 1, 2)**

![](<.gitbook/assets/1 (55).png>)

**Image 1****Image 2**

1.  Repoussez le levier vers le bas. Le boîtier transparent vous permet de vérifier si le fil est correctement connecté. Assurez-vous que le fil est bien maintenu en place et ne se détachera pas.**(Photo 3, 4)**

![](<.gitbook/assets/2 (60).png>)

|                                                          | **Image 3**                              | **Image 4** |   |
| -------------------------------------------------------- | ---------------------------------------- | ----------- | - |
| 3) De la même manière qu'aux étapes 1 et 2, insérez dans | un autre pôle le fil pour se connecter à |             |   |
| Entrée d'alimentation de ligne CA.**(Photo 5)**          |                                          |             |   |
|                                                          |                                          |             |   |
|                                                          |                                          |             |   |

![](<.gitbook/assets/3 (48).jpeg>)

**Image 5**

3

1.  Répétez les étapes 1, 2 et 3 pour connecter les autres fils avec des connecteurs.

Veuillez noter que le fil bleu doit être connecté à un connecteur à 3 fils, puis connecté à l'entrée d'alimentation neuronale CA et à la sortie de charge de puissance neutre CA.**(Photo 6)**

![](<.gitbook/assets/4 (61).png>)

**Image 6**

**Opération**

-   _**Schéma de connexion des fils**_
    -   Reportez-vous au schéma pour connecter l'éclairage de votre maison au commutateur de relais de puissance.
-   _**Installation**_
    -   Connectez le commutateur de relais de puissance au câble d'alimentation.
    -   Connectez le commutateur de relais de puissance à l'éclairage de votre maison. L'éclairage doit être en état ON.
    -   Vous pouvez connecter un interrupteur externe au commutateur de relais de puissance selon le schéma pour allumer/éteindre le commutateur de relais de puissance.
    -   _**NOTE IMPORTANTE**_**:**Le commutateur de relais d'alimentation n'a pas de batterie de secours et sera mis hors tension en cas de panne de courant CA.**NE PAS**utilisez le commutateur de relais de puissance comme routeur pour votre capteur de sécurité ou vos dispositifs de contrôle d'alarme tels que le contact de porte, le capteur PIR… etc., sinon les capteurs perdront la connexion au réseau ZigBee si le commutateur de relais de puissance est déconnecté de l'alimentation secteur. Planifiez les emplacements d'installation de ces capteurs de sécurité sans utiliser le commutateur de relais de puissance et utilisez uniquement un routeur avec batterie de secours pour eux. La fonction routeur de l'interrupteur d'alimentation doit**SEULEMENT**Être utilisé pour fournir une extension de la plage de signal pour d'autres interrupteurs d'alimentation/variateur.
-   _**Contrôle des appareils**_
    -   Une fois que le commutateur de relais de puissance a rejoint avec succès un réseau ZigBee, le coordinateur peut allumer/éteindre l'appareil à distance.
    -   Vous pouvez également appuyer sur le bouton du commutateur de relais de puissance pour allumer/éteindre la lumière.
    -   Vous pouvez allumer/éteindre le commutateur de relais de puissance avec un interrupteur externe.
    -   Si vous avez lié un contrôleur au commutateur de relais de puissance, vous pouvez également utiliser le contrôleur pour allumer/éteindre le commutateur de relais de puissance.
    -   Si l'entrée d'alimentation CA est déconnectée du commutateur de relais de puissance, son état marche/arrêt précédent sera restauré dans la minute qui suit la reconnexion de l'entrée d'alimentation CA au commutateur de relais de puissance.
-   _**Moniteur de consommation d'énergie (PRM5-ZBS/PRM5-ZBSR uniquement)**_
    -   Le commutateur de relais de puissance transmettra un signal avec ses données de consommation d'énergie toutes les deux minutes au coordinateur du réseau ZigBee.
    -   Chaque fois que la production d'énergie du commutateur d'alimentation change de +/- 2 W, il transmettra automatiquement un signal avec les données de consommation d'énergie au coordinateur du réseau ZigBee pour mise à jour.
    -   Le commutateur d'alimentation transmet un signal avec les données d'alimentation au coordinateur chaque fois que la consommation d'énergie accumulée augmente de 0,1 kW/h.
    -   Le compteur a une précision de +/- 5%.
    -   Pour effacer le commutateur d'alimentation de ses données de consommation d'énergie accumulées, suivez les étapes ci-dessous :
        1.  Débranchez le commutateur de relais de puissance de la prise de courant.
        2.  Appuyez et maintenez le bouton de fonction et rebranchez l'alimentation tout en maintenant le bouton enfoncé.
        3.  Maintenez le bouton enfoncé et relâchez-le après 3 secondes. Les données de consommation d'énergie accumulées seront effacées.

![](<.gitbook/assets/5 (30).jpeg>)

4

-   _**Charge de fonctionnement maximale**_
    -   Pour 110 V : la charge de fonctionnement maximale est de 1 100 W et 10 A.
    -   Pour 230 V : la charge de fonctionnement maximale est de 2 300 W et 10 A.
    -   Si le commutateur du relais de puissance surchauffe, il coupera automatiquement l'alimentation par mesure de sécurité. L'utilisateur doit déconnecter et reconnecter l'alimentation CA au commutateur de relais de puissance après la coupure pour reprendre un fonctionnement normal.

**Annexe (Pour les développeurs uniquement)**

_**Commutateur de relais de puissance avec ID de groupe de compteurs**_

**ID de l'appareil : Prise de courant secteur : 0x0009**

**Point de terminaison : 0x01**

| **Du côté serveur**                             |                 | **Côté client** |
| ----------------------------------------------- | --------------- | --------------- |
|                                                 |                 |                 |
|                                                 | **Obligatoire** |                 |
|                                                 |                 |                 |
| De base (0x0000)                                |                 | _Aucun_         |
|                                                 |                 |                 |
| Identifier (0x0003)                             |                 |                 |
|                                                 |                 |                 |
| Groupes (0x0004)                                |                 |                 |
|                                                 |                 |                 |
| Scènes (0x0005)                                 |                 |                 |
|                                                 |                 |                 |
| Marche/Arrêt (0x0006)                           |                 |                 |
|                                                 |                 |                 |
|                                                 | **Facultatif**  |                 |
|                                                 |                 |                 |
| Mesure (0x0705) (PRM5-ZBS/PRM5-ZBSR uniquement) |                 | Aucun           |
|                                                 |                 |                 |

_**Attribut des informations de base sur le cluster**_

| **Identifier**                                               | **Nom**                  |                      | **Taper**         |           |               | **Gamme**        |                  |                   | **Accéder**       |         | **Défaut** | **Obligatoire** |                 |                 |   |   |
| ------------------------------------------------------------ | ------------------------ | -------------------- | ----------------- | --------- | ------------- | ---------------- | ---------------- | ----------------- | ----------------- | ------- | ---------- | --------------- | --------------- | --------------- | - | - |
|                                                              |                          |                      |                   |           |               | **/ Facultatif** |                  |                   |                   |         |            |                 |                 |                 |   |   |
|                                                              |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
| 0x0000                                                       | _Version ZCL_            | 8 bits non signé     |                   |           | 0x00 –0xff    |                  |                  | Lecture seulement |                   | 0x01    | M          |                 |                 |                 |   |   |
|                                                              | entier                   |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
|                                                              |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
| 0x0001                                                       | Version de l'application | 8 bits non signé     |                   |           | 0x00 – 0xff   |                  |                  | Lecture seulement |                   | 0x00    | Ô          |                 |                 |                 |   |   |
|                                                              | entier                   |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
|                                                              |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
| 0x0003                                                       | _Version matérielle_     | 8 bits non signé     |                   |           | 0x00 –0xff    |                  |                  | Lecture seulement | 0                 | Ô       |            |                 |                 |                 |   |   |
|                                                              | entier                   |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
|                                                              |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
| 0x0004                                                       | _Nom du Fabricant_       | Chaîne de caractères |                   |           | 0 – 32 octets |                  |                  | Lecture seulement |                   | Climax  | Ô          |                 |                 |                 |   |   |
|                                                              |                          |                      |                   |           | Technologie   |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
|                                                              |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
| 0x0005                                                       | _Identifiant du modèle_  | Chaîne de caractères |                   |           | 0 – 32 octets |                  |                  | Lecture seulement |                   | (Modèle | Ô          |                 |                 |                 |   |   |
|                                                              |                          |                      |                   |           | Version)      |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
|                                                              |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
| 0x0006                                                       | _DateCode_               | Chaîne de caractères |                   |           | 0 – 16 octets |                  |                  | Lecture seulement |                   |         | Ô          |                 |                 |                 |   |   |
|                                                              |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
| 0x0007                                                       | _Source d'énergie_       |                      | 8 bits            |           |               | 0x00 –0xff       |                  |                   | Lecture seulement |         |            | M               |                 |                 |   |   |
| 0x0010                                                       | _EmplacementDescription_ | Chaîne de caractères |                   |           | 0 – 32 octets |                  |                  | Lire écrire       |                   |         | Ô          |                 |                 |                 |   |   |
| 0x0011                                                       | _Environnement physique_ |                      | 8 bits            |           |               | 0x00 –0xff       |                  |                   | Lire écrire       |         | 0x00       | Ô               |                 |                 |   |   |
| 0x0012                                                       | _Appareil activé_        |                      | Booléen           |           |               | 0x00 –0x01       |                  |                   | Lire écrire       |         | 0x01       | Ô               |                 |                 |   |   |
| 0xFFFD                                                       | _Révision du cluster_    |                      | uint16            |           | 0x0001-0xFFFE |                  |                  | Lecture seulement | 1                 | M       |            |                 |                 |                 |   |   |
| _**Attribut des informations d'identification du cluster**_ |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
|                                                              |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
| **Identifier**                                               | **Nom**                  |                      |                   | **Taper** |               |                  | **Gamme**        | **Accéder**       |                   |         | **Défaut** | **Obligatoire** |                 |                 |   |   |
|                                                              |                          |                      |                   |           |               | **/ Facultatif** |                  |                   |                   |         |            |                 |                 |                 |   |   |
|                                                              |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
| 0x0000                                                       | _Identifier l'heure_     |                      | 16 bits non signé |           |               | 0x00 –0xffff     | Lire écrire      |                   | 0x0000            | M       |            |                 |                 |                 |   |   |
|                                                              |                          | entier               |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
|                                                              |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
| 0xFFFD                                                       | _Révision du cluster_    |                      |                   | uint16    |               |                  | 0x0001-0xFFFE    | Lecture seulement |                   | 1       | M          |                 |                 |                 |   |   |
| _**Attributs du cluster Groupes Informations**_             |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
|                                                              |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
| **Identifier**                                               | **Nom**                  |                      | **Taper**         |           |               | **Gamme**        |                  | **Accéder**       |                   |         |            | **Défaut**      | **Obligatoire** |                 |   |   |
|                                                              |                          |                      |                   |           |               | **/ Facultatif** |                  |                   |                   |         |            |                 |                 |                 |   |   |
|                                                              |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
| 0x0000                                                       | _NomSupport_             |                      | Bitmap 8 bits     |           |               | x0000000         |                  | Lecture seulement |                   | -       | M          |                 |                 |                 |   |   |
| 0xFFFD                                                       | _Révision du cluster_    |                      | uint16            |           |               | 0x0001-0xFFFE    |                  | Lire              |                   | 1       | M          |                 |                 |                 |   |   |
|                                                              |                          |                      |                   | seulement |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
|                                                              |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
| _**Attributs du cluster Scènes Informations**_              |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
|                                                              |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
| **Identifier**                                               | **Nom**                  |                      |                   | **Taper** |               |                  | **Gamme**        |                   | **Accéder**       |         |            |                 | **Défaut**      | **Obligatoire** |   |   |
|                                                              |                          |                      |                   |           |               |                  | **/ Facultatif** |                   |                   |         |            |                 |                 |                 |   |   |
|                                                              |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
| 0x0000                                                       | _NomSupport_             |                      | Bitmap 8 bits     |           |               | x0000000         |                  | Lecture seulement |                   |         | 0x00       | M               |                 |                 |   |   |
| 0x0001                                                       | _Scène actuelle_         |                      | 8 bits non signé  |           |               | 0x00 – 0xff      |                  | Lecture seulement |                   |         |            | 0x00            | M               |                 |   |   |
|                                                              |                          | entier               |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
|                                                              |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
| 0x0002                                                       | _Groupe actuel_          |                      |                   | Non signé |               |                  | 0x0000 – 0xfff7  |                   | Lecture seulement |         |            |                 | 0x00            | M               |   |   |
|                                                              | Entier de 16 bits        |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
|                                                              |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
| 0x0003                                                       | _ScèneValide_            |                      |                   | Booléen   |               |                  | 0x00 – 0x01      |                   | Lecture seulement |         |            | 0x00            | M               |                 |   |   |
| 0x0004                                                       | _NomSupport_             |                      | Bitmap 8 bits     |           |               | x0000000         |                  | Lecture seulement |                   | -       | M          |                 |                 |                 |   |   |
| 0xFFFD                                                       | _Révision du cluster_    |                      |                   | uint16    |               |                  | 0x0001-0xFFFE    |                   | Lire              |         | 1          | M               |                 |                 |   |   |
|                                                              |                          |                      |                   |           | seulement     |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |
|                                                              |                          |                      |                   |           |               |                  |                  |                   |                   |         |            |                 |                 |                 |   |   |

5

-   _**Attribut des informations sur le cluster marche/arrêt**_

| **Identifier**   | **Nom**               | **Taper** | **Gamme**     | **Accéder**       | **Défaut** | **Obligatoire** |   |
| ---------------- | --------------------- | --------- | ------------- | ----------------- | ---------- | --------------- | - |
| **/ Facultatif** |                       |           |               |                   |            |                 |   |
|                  |                       |           |               |                   |            |                 |   |
| 0x0000           | _Allumé éteint_       | Booléen   | 0x00 –0x01    | Lecture seulement | 0x00       | M               |   |
| 0xFFFD           | _Révision du cluster_ | uint16    | 0x0001-0xFFFE | Lire              | 1          | M               |   |
| seulement        |                       |           |               |                   |            |                 |   |
|                  |                       |           |               |                   |            |                 |   |

_**Attributs des informations du cluster de mesure (ensemble d'attributs d'informations de lecture)**_

| **Identifier** | **Nom**        | **Taper**          | **Gamme**      |   | **Accéder**       | **Défaut** | **Obligatoire** |   |
| -------------- | -------------- | ------------------ | -------------- | - | ----------------- | ---------- | --------------- | - |
|                | **t**          | **/ Facultatif**   |                |   |                   |            |                 |   |
|                |                |                    |                |   |                   |            |                 |   |
| 0x00           | Somme actuelle | 48 bits non signés | 0x000000000000 | à | Lecture seulement |            | M               |   |
| Livré          | Entier         | 0xFFFFFFFFFFFF     |                |   |                   |            |                 |   |
|                |                |                    |                |   |                   |            |                 |   |

_**Attributs des informations du cluster de mesure (ensemble d'attributs de formatage)**_

| **Identifier**   | **Nom**                        | **Taper**          | **Gamme**   | **Accéder**       | **Défaut** | **Obligatoire** |   |
| ---------------- | ------------------------------ | ------------------ | ----------- | ----------------- | ---------- | --------------- | - |
| **/ Facultatif** |                                |                    |             |                   |            |                 |   |
|                  |                                |                    |             |                   |            |                 |   |
| 0x00             | Unité de mesure                | Énumération 8 bits | 0x00 à 0xFF | Lecture seulement | 0x00       | M               |   |
| 0x01             | Multiplier                     | 24 bits non signé  | 0x000000 à  | Lecture seulement | 1          | Ô               |   |
| Entier           | 0xFFFFFF                       |                    |             |                   |            |                 |   |
|                  |                                |                    |             |                   |            |                 |   |
| 0x02             | Diviseur                       | 24 bits non signé  | 0x000000 à  | Lecture seulement | 10000      | Ô               |   |
| Entier           | 0xFFFFFF                       |                    |             |                   |            |                 |   |
|                  |                                |                    |             |                   |            |                 |   |
| 0x03             | SommationFormation             | BitMap 8 bits      | 0x00 à 0xFF | Lecture seulement | 0xF9       | M               |   |
| 0x04             | DemandFormating                | BitMap 8 bits      | 0x00 à 0xFF | Lecture seulement | 0Ksasa     | Ô               |   |
| 0x06             | Type de périphérique de mesure | BitMap 8 bits      | 0x00 à 0xFF | Lecture seulement | 0x00       | M               |   |

_**Attributs des informations du cluster de mesure (ensemble d'attributs historiques)**_

| **Identifier**   | **Nom**               | **Taper**     | **Gamme**    | **Accéder**       | **Défaut** | **Obligatoire** |   |
| ---------------- | --------------------- | ------------- | ------------ | ----------------- | ---------- | --------------- | - |
| **/ Facultatif** |                       |               |              |                   |            |                 |   |
|                  |                       |               |              |                   |            |                 |   |
| 0x00             | Demande instantanée   | Signé 24 bits | -8 388 607 à | Lecture seulement | 0x00       | Ô               |   |
| Entier           | 8,388,607             |               |              |                   |            |                 |   |
|                  |                       |               |              |                   |            |                 |   |
| 0xFFFD           | _Révision du cluster_ | uint16        | 0x0001-0xFFF | Lire              | 1          | M               |   |
| ET               | seulement             |               |              |                   |            |                 |   |
|                  |                       |               |              |                   |            |                 |   |

6
