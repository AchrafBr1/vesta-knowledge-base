# VESTA 296

**Commande d'obturation sur rail DIN (SCM-6-AS-DIN2-ZW)**

**Introduction**

SCM-6-AS-DIN2-ZW est une commande d'obturation Z-Wave™. L'utilisateur peut contrôler le SCM via le réseau Z-Wave à distance ou manuellement en reliant un interrupteur au contrôle de l'obturateur.

Enroulable, descendant ou arrêté à mi-chemin automatiquement ou à distance, le SCM-6-AS-ZW est directement connecté et contrôle les habillages de fenêtres motorisés, les stores et stores intérieurs et extérieurs, l'écran de projection et la porte de garage ou le portail d'allée de votre maison. .

Le contrôle d'obturation est compatible uniquement avec la passerelle/panneau de commande Z-Wave. Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance. En profitant du réseau maillé Z-Wave, les commandes peuvent être acheminées vers leur destination via des produits Z-Wave intermédiaires « d’écoute ».

Le contrôle d'obturation Z-Wave permet d'accéder à la classe « S2 non authentifié » et prend en charge l'inclusion Z-Wave SmartStart ainsi que l'inclusion classique.

**Identification des pièces**

![](<.gitbook/assets/0 (103).jpeg>)

1.  **Port d'antenne externe**
2.  **Indicateur LED**
    -   Mise sous tension : la LED clignote deux fois.
    -   En mode calibrage automatique : la LED clignote une fois par seconde.
    -   Réinitialisation d'usine : la LED clignote deux fois.
    -   En appuyant sur le commutateur local S1/S2 : LED allumée.
3.  **Bouton de fonction**
    -   -   Appuyez sur le bouton de fonction et le contrôle d'obturation enverra un rapport à plusieurs niveaux.
        -   Appuyez sur le bouton de fonction 3 fois en 1 seconde pour inclure ou exclure le contrôle d'obturation dans/du réseau Z-Wave.
        -   Appuyez et maintenez le bouton de fonction pendant 10 secondes pour réinitialiser.
        -   Appuyez et maintenez le bouton de fonction pendant 3 secondes, puis relâchez-le pour passer en mode d'étalonnage automatique.
4.  **Borne de sortie de puissance L (fil sous tension)**
5.  **Borne d'entrée d'alimentation CA L (fil sous tension)**
6.  **Borne d'entrée d'alimentation CA N (fil neutre)**
7.  **Borne de commutation locale S2 (direction fermée)**

Connectez un commutateur externe au terminal. Activez cet interrupteur pour contrôler que le volet roule dans la direction « Ouvert » en activant la sortie du moteur O2.

L'activation de cet interrupteur lorsque le volet roule dans le sens « Ouvert » arrêtera le volet.

**8. Borne de commutation locale S1 (direction ouverte)**

Connectez un commutateur externe au terminal. Activez cet interrupteur pour contrôler que le volet roule dans la direction « Ouvert » en activant la sortie moteur O1.

L'activation de cet interrupteur lorsque le volet roule dans le sens « Fermer » arrêtera le volet.

**9. Borne de sortie du moteur O2 (sens de fermeture)**

Connectez-vous à la borne de fermeture du moteur d'obturation.

**10. Borne de sortie du moteur O1 (sens ouvert)**

Connectez-vous à la borne ouverte du moteur de volet roulant.

**11. Borne de sortie de puissance N (fil neutre)**

**spécification**

-   Alimentation : 100 - 240 VCA, 50/60 Hz
-   Courant de charge pris en charge : 3 A pour les moteurs avec facteur de puissance compensé (charges inductives)
-   Protocole de communication : module série Z-Wave Plus 700

1

![](<.gitbook/assets/1 (85).jpeg>)**Prudence**

-   Tous les travaux sur l'appareil, y compris l'installation et la maintenance, doivent être effectués par un électricien qualifié et agréé.
-   Avant l'installation ou tout travail de maintenance, assurez-vous que l'alimentation électrique a été débranchée.
-   Ne connectez pas l'appareil à des charges dépassant le courant de charge pris en charge.
-   Veuillez connecter l'appareil uniquement à un moteur alimenté en courant alternatif.

**Câblage et installation**

**Avant l'installation, assurez-vous que l'alimentation électrique a été débranchée.**

-   Le SCM-6-AS-DIN2-ZW doit être connecté selon les 2 schémas ci-dessous :

**Câblage 1****Câblage 2**

![](<.gitbook/assets/2 (79).png>)

-   -   Connectez respectivement les bornes L et N d'entrée d'alimentation CA du SCM aux bornes L et N de l'alimentation.
    -   Connectez la borne de sortie de puissance N du SCM à la borne N du moteur de volet roulant.
    -   Connectez la borne O1 du SCM à la borne ouverte du moteur de volet roulant.
    -   Connectez la borne O2 du SCM à la borne de fermeture du moteur d'obturation.
    -   **(Commutateurs locaux en option)**Connectez les bornes S2 et S1 du SCM à 2 commutateurs externes et connectez 2 commutateurs externes à la borne L de l'alimentation.
-   Insérez chaque fil dans la borne à laquelle il doit être connecté selon 2 schémas de câblage

illustré ci-dessus et serrez la vis de chaque borne.

-   Connectez l'antenne externe au port d'antenne externe.
-   Montez l'appareil à l'intérieur du boîtier électrique à l'aide d'un rail DIN.

**Caractéristiques**

-   _**Ajout d'un appareil (inclusion)**_

Ce produit peut être inclus et utilisé dans n'importe quel réseau Z-Wave avec d'autres appareils certifiés Z-Wave d'autres fabricants et/ou d'autres applications. Tous les nœuds non alimentés par batterie du réseau agiront comme répéteurs, quel que soit le fournisseur, afin d'augmenter la fiabilité du réseau. L'appareil prend en charge à la fois le processus d'inclusion classique et le processus d'inclusion SmartStart.

**Inclusion classique**

-   Connectez l'alimentation à la commande d'obturation (voir le manuel**Câblage et installation**).
-   Mettez la passerelle Z-wave ou le panneau de commande dans**Mode d'inclusion**(veuillez vous référer au manuel de la passerelle Z-wave ou du panneau de commande).
-   En 1 seconde, appuyez 3 fois sur le bouton de fonction.
-   Reportez-vous au manuel d'utilisation de la passerelle Z-wave ou du panneau de commande pour terminer le processus d'ajout.
-   Si l'appareil a déjà été ajouté (inclus) dans une autre passerelle/panneau de configuration Z-wave, ou si l'appareil ne peut pas être ajouté à la passerelle/panneau de configuration Z-wave actuelle, essayez d'abord de le supprimer (voir_**Suppression d'un périphérique**_).

2

**Inclusion de SmartStart**

Z-Wave SmartStart utilise le DSK de l'appareil pour améliorer et simplifier le processus d'inclusion. DSK est une clé spécifique à l'appareil utilisée pour l'authentification. Les informations DSK sont stockées au format QR code imprimé sur un autocollant et attaché à l'appareil.

![](<.gitbook/assets/3 (69).jpeg>)

-   -   -   Scannez l'autocollant QR Code sur le côté droit du contrôle d'obturation pour obtenir le DSK et le transférer vers la passerelle Z-Wave.
        -   Connectez l'alimentation au contrôle d'obturation, une demande d'inclusion SmartStart sera automatiquement envoyée à la passerelle.
        -   La passerelle inclura automatiquement l'appareil lors de la reconnaissance de l'appareil en faisant correspondre la demande d'inclusion avec le DSK obtenu.
    -   _REMARQUE>_
        -   -   Le DSK de l'appareil n'est utilisé que lors de l'inclusion.
            -   Le DSK peut être lu sans que le contrôle d'obturation soit allumé, il est donc possible de préparer la passerelle pour inclure l'appareil avant de mettre sous tension le contrôle d'obturateur.
            -   Avant de supprimer ou de réinitialiser les paramètres d'usine du contrôle d'obturation,

veuillez vous assurer que les informations DSK de l'appareil ont été supprimées ou n'existent pas dans la passerelle. Si vous supprimez ou réinitialisez l'appareil aux paramètres d'usine, mais que son DSK existe toujours dans la passerelle, la passerelle inclura automatiquement à nouveau l'appareil.

-   _**Suppression d'un périphérique (exclusion)**_

L'appareil doit être supprimé du réseau Z-wave existant avant d'être ajouté à un autre.**Mode d'exclusion**

-   Mettez la passerelle Z-wave ou le panneau de commande dans**Mode d'exclusion**(veuillez vous référer au manuel de la passerelle Z-wave ou du panneau de commande).
-   Dans un délai d'une seconde, appuyez 3 fois sur le bouton de fonction et l'appareil sera supprimé du réseau Z-wave.

**Retour aux paramètres d'usine**

_(Utilisez la réinitialisation d'usine uniquement lorsque le panneau de configuration/passerelle réseau est manquant ou inutilisable)._

La réinitialisation d'usine de l'appareil le restaurera aux paramètres d'usine par défaut (c'est-à-dire qu'il n'est inclus dans aucun réseau Z-wave).

-   -   Appuyez et maintenez enfoncé le bouton de fonction de l'appareil pendant 10 secondes pour réinitialiser les paramètres d'usine.
-   _**Test de portée**_

Pour tester si l'appareil est capable de communiquer avec la passerelle Z-wave ou le panneau de commande :

-   Mettez la passerelle/le panneau en mode test de portée (Walk Test).
-   Appuyez sur le bouton de fonction de l'appareil.
-   La passerelle/le panneau doit afficher si l'appareil se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation de la passerelle/du panneau).

**Opération**

-   _**Contrôle de l'obturateur**_
    -   **Contrôle manuel**

Si un commutateur local en option est connecté, l'utilisateur peut appuyer et maintenir enfoncé le bouton du commutateur local haut/bas (S1 haut ; S2 bas) pendant 1 seconde pour contrôler l'obturateur. Lorsqu’il est activé, l’obturateur monte/descend.

Lorsque le volet roule, l'utilisateur peut arrêter le volet en appuyant sur le bouton de sens opposé.

-   -   **Réseau Z-Wave**

Une fois que le contrôle de l'obturateur a été inclus avec succès dans un réseau Z-Wave, le contrôleur Z-Wave peut contrôler l'obturateur avec la commande Z-wave Switch Binary Set ou Switch Multilevel Set, en utilisant les paramètres ci-dessous :

-   -   -   Valeur : 0x00~0% (0%)~99 %, 0 % = Fermeture complète, 99 % = Ouverture complète)
        -   Durée de gradation : 0x00
-   _**Étalonnage**_
    -   L’heure d’activation par défaut du contrôle d’obturation est**4**minutes.

Lorsque le bouton Haut/Bas est enfoncé, le moteur de l'obturateur est activé pendant 4 minutes.

Lorsqu'une commande Z-Wave est reçue du contrôleur Z-Wave, celui-ci déterminera le pourcentage de course de l'obturateur en utilisant 4 minutes comme base de calcul.

-   -   Pour que le contrôle d'obturation fonctionne correctement, son temps d'activation doit être calibré en fonction de la distance réelle de déplacement de l'obturateur. Il existe deux manières de régler le temps d'activation :

3

-   **Calibrage automatique :**Calibrez l'activation selon la procédure ci-dessous :
    1.  Appuyez et maintenez le bouton de fonction pendant 3 secondes, puis relâchez-le pour passer en mode d'étalonnage automatique. La LED commencera à clignoter une fois par seconde ; le moteur de l'obturateur roulera vers le haut.
    2.  Lorsque le moteur de l'obturateur roule vers le haut et s'arrête, il roule alors automatiquement vers le bas et enregistre le temps qu'il faut pour passer de la position ouverte (haut) à la position fermée (bas) comme nouveau

“**la période de fermeture**”.

-   1.  Lorsque le moteur de l'obturateur descend vers le bas, il s'enroule et enregistre le temps qu'il faut pour passer de la position fermée (en bas) à la position ouverte (en haut) comme le nouveau "**temps ouvert**”.
    2.  Lorsque toutes les actions sont terminées, le contrôle d'obturation enverra un message MULTILEVEL_RAPPORT : 0x63 au contrôleur indiquant que la position actuelle est en haut. La LED s'éteindra lorsque le moteur d'obturation quittera le mode d'étalonnage automatique.
    3.  Après l'étalonnage, le moteur de volet fonctionnera selon les temps de montée et de descente nouvellement enregistrés.
-   Par exemple, s'il faut 30 secondes au volet pour passer de la position « Haut » à « Bas », son nouveau temps de fermeture sera de 30 secondes. Après l'étalonnage, chaque fois que vous appuyez sur le bouton « Descente », l'obturateur s'abaisse pendant 30 secondes.
-   S'il faut 40 secondes au volet pour passer de la position « Bas » à « Montée », son nouveau temps d'ouverture sera
    1.  secondes. Après l'étalonnage, chaque fois que vous appuyez sur le bouton « Haut », l'obturateur s'enroule pendant 40 secondes.
-   **Commande Z-Wave :**Outre l'étalonnage automatique, les utilisateurs peuvent également ajuster le temps d'activation en envoyant une commande depuis le contrôleur Z-Wave avec la commande Configuration CC, en utilisant les paramètres ci-dessous :

| **Paramètre**                   | **Paramètre** |   | **Taille** | **Valeur**                          | **Défaut**        |                |   |
| ------------------------------- | ------------- | - | ---------- | ----------------------------------- | ----------------- | -------------- | - |
|                                 | **Nombre**    |   |            |                                     |                   |                |   |
|                                 |               |   |            |                                     |                   |                |   |
| Réglage du temps d'ouverture    | 0x01          |   | 0x02       | 0x0000~0x0960 (0,1 s)               | 0x0960            | (240 secondes) |   |
|                                 |               |   |            |                                     |                   |                |   |
| Réglage de l'heure de fermeture | 0x02          |   | 0x02       | 0x0000~0x0960 (0,1 s)               | 0x0960            | (240 secondes) |   |
|                                 |               |   |            |                                     |                   |                |   |
| Position actuelle               | 0x03          |   | 0x02       | 0x0000~0x0063 (%)                   | 0x0063            | (99%)          |   |
|                                 |               |   |            |                                     | Pleinement ouvert |                |   |
|                                 |               |   |            |                                     |                   |                |   |
| Étalonnage                      | 0x04          |   | 0x01       | 0 – l'appareil n'est pas calibré    | 0                 |                |   |
|                                 |               |   |            | (lecture seulement)                 |                   |                |   |
|                                 |               |   |            | 1 - l'appareil est calibré          |                   |                |   |
|                                 |               |   |            | (lecture seulement)                 |                   |                |   |
|                                 |               |   |            | 2- forcer l'exécution de l'appareil |                   |                |   |
|                                 |               |   |            | étalonnage                          |                   |                |   |
|                                 |               |   |            |                                     |                   |                |   |

-   Numéro de paramètre : 0x01~0x04
    -   Pour le paramètre 1, les utilisateurs peuvent définir le temps d'ouverture (de bas en haut) sur une valeur comprise entre 0 et 240 secondes.
    -   Pour le paramètre 2, les utilisateurs peuvent définir le temps de fermeture (de haut en bas) sur une valeur comprise entre 0 et 240 secondes.
    -   Pour le paramètre 3, les utilisateurs peuvent définir la position actuelle sur une valeur comprise entre %0 et %99.
    -   Pour le paramètre 4, les utilisateurs peuvent définir une valeur pour forcer l'appareil à exécuter l'étalonnage ou vérifier l'état d'étalonnage par valeur. Réglez la valeur sur 2 pour que l'appareil exécute l'étalonnage. Si la valeur est 0, cela signifie que l'appareil n'est pas calibré. Si la valeur est 1, cela signifie que l'appareil est calibré.
-   Taille : 0x02. Ceci est utilisé pour spécifier la taille de la valeur réelle.
-   Valeur de configuration : 0x0000~0x0960 (0,1 seconde)
-   La commande d'obturateur commencera le mouvement dès réception de la commande Z-wave Switch Binary Set ou Switch Multilevel Set, et le mouvement sera exécuté en fonction du réglage de la position actuelle.

Exemple de paramètre de configuration :

|                                           | **Numéro de paramètre** | **Taille** | **Valeur**             |
| ----------------------------------------- | ----------------------- | ---------- | ---------------------- |
|                                           |                         |            |                        |
|                                           | 01                      | 02         | 0x03E8 (100 secondes)  |
|                                           |                         |            |                        |
|                                           | 02                      | 02         | 0x03E8 (100 secondes)  |
|                                           | 03                      | 02         | 0032 (50%)             |
|                                           |                         |            |                        |
|                                           | 04                      | 01         | 2- forcer l'appareil à |
|                                           |                         |            | exécuter l'étalonnage  |
| CHANGER_MULTINIVEAUX_ENSEMBLE : 0x00 (0%) |                         |            |                        |

SCM roulera vers le bas (de haut en bas) pendant 50 secondes : (1000/1000)\*(100-50)

-   L'heure d'activation sera réinitialisée à**4**minutes chaque fois que le contrôle d'obturation est inclus dans le réseau Z-Wave ou lorsqu'il est réinitialisé aux paramètres d'usine.

_**\\<NOTE>:**_La position actuelle par défaut du contrôle d'obturation est réglée sur 99 % (ouverture totale). Il est recommandé d'ouvrir complètement l'obturateur avant de calibrer avec la commande Z-Wave, sinon veuillez également réajuster le paramètre de position actuelle avec la commande.

4

**Informations sur la vague Z**

**Type d'appareil:**GÉNÉRIQUE_TAPER_CHANGER_MULTINIVEAUX

**Type spécifique :**SPÉCIFIQUE_TAPER_CLASSE_C_MOTEUR_CONTRÔLE

**Type de rôle :**Toujours sur esclave (AOS)

**Identifiant du fabricant :**0x018E

**ID du type de produit :**0x0004

**Identifiant du produit :**0x0105

**Classe de commande prise en charge :**

| **Classe de commande**                      | **Version** | **Classe de sécurité requise**             |
| ------------------------------------------- | ----------- | ------------------------------------------ |
|                                             |             |                                            |
| Association                                 | 2           | Classe de sécurité accordée la plus élevée |
| Informations sur le groupe d'associations   | 3           | Classe de sécurité accordée la plus élevée |
| Basique                                     | 2           | Classe de sécurité accordée la plus élevée |
| Réinitialisation de l'appareil localement   | 1           | Classe de sécurité accordée la plus élevée |
| Métadonnées de mise à jour du micrologiciel | 5           | Classe de sécurité accordée la plus élevée |
| Spécifique à la fabrication                 | 2           | Classe de sécurité accordée la plus élevée |
| Multicanal                                  | 4           | Classe de sécurité accordée la plus élevée |
| Association multicanal                      | 3           | Classe de sécurité accordée la plus élevée |
| Niveau d'énergie                            | 1           | Classe de sécurité accordée la plus élevée |
| Changer de binaire                          | 2           | Classe de sécurité accordée la plus élevée |
| Changer de multiniveau                      | 4           | Classe de sécurité accordée la plus élevée |
| Configuration                               | 1           | Classe de sécurité accordée la plus élevée |
| Version                                     | 3           | Classe de sécurité accordée la plus élevée |
| Service de transport                        | 2           | Aucun                                      |
| Informations sur Z-Wave Plus                | 2           | Aucun                                      |
| Sécurité 2                                  | 1           | Aucun                                      |
| Sécurité                                    | 1           | Aucun                                      |
| Surveillance                                | 1           | Aucun                                      |

**Groupes associatifs :**

**IDENTIFIANT**

1

| **Nom**           | **Nombre de nœuds** | **Description**                                                                  |
| ----------------- | ------------------- | -------------------------------------------------------------------------------- |
| Corde de sécurité | 40                  | Prend en charge les classes de commandes suivantes :                             |
|                   |                     | ● Réinitialisation locale de l'appareil : déclenchée lors de la réinitialisation |
|                   |                     | ● Rapport Switch Multilevel : rapport du                                         |
|                   |                     | changement de poste                                                              |
|                   |                     |                                                                                  |

5