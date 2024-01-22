# VESTA 167

**Contrôle de l'obturateur (SCM-5ZW)**

**Introduction**

SCM-5ZW est un contrôle d'obturation Z-Wave. L'utilisateur peut contrôler le SCM via le réseau Z-Wave à distance ou manuellement en reliant un commutateur au SCM.

Enroulant, descendant ou arrêtant à mi-chemin automatiquement ou à distance, le SCM-5ZW est directement connecté et contrôle les habillages de fenêtres motorisés, les stores et stores intérieurs et extérieurs, l'écran de projection et la porte de garage ou le portail d'allée de votre maison.

Le contrôle d'obturation est compatible uniquement avec la passerelle/panneau de commande Z-Wave. Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance. En profitant du réseau maillé Z-Wave, les commandes peuvent être acheminées vers leur destination via des produits Z-Wave intermédiaires « d’écoute ».

![](<.gitbook/assets/0 (60).jpeg>)

**Identification des pièces**

1.  **Indicateur LED**
    -   Mise sous tension : la LED clignote deux fois.
    -   Apprentissage réussi : la LED clignote 3 fois.
    -   Réinitialisation d'usine : la LED clignote deux fois.
2.  **Bouton de fonction**
    -   Appuyez sur le bouton de fonction et le contrôle d'obturation enverra un rapport à plusieurs niveaux.
    -   Appuyez 3 fois sur le bouton de fonction en 1,5 seconde pour inclure ou exclure le contrôle d'obturation dans/du réseau Z-Wave.
    -   Appuyez et maintenez enfoncé le bouton de fonction pendant 10 secondes pour réinitialiser.
3.  **Câble de connexion d'entrée d'alimentation N (fil neutre) (bleu)**
4.  **Câble de connexion d'entrée d'alimentation L (Live Lead) (marron)**
5.  **Câble de connexion du commutateur local S2 (direction vers le bas) (orange)**

Si SCM est connecté selon_**Installation**_ci-dessous, l'obturateur s'abaissera pendant 4 minutes après l'activation de l'interrupteur.

L'activation de cet interrupteur lorsque le volet est en cours d'enroulement arrêtera le volet.

**6. Câble de connexion du commutateur local S1 (direction vers le haut) (rouge)**

Si SCM est connecté selon_**Installation**_ci-dessous, l'obturateur s'enroulera pendant 4 minutes après l'activation de l'interrupteur.

L'activation de cet interrupteur lorsque le volet est descendu arrêtera le volet.

**7. Câble de connexion de la sortie moteur O1 (direction vers le haut) (jaune)**

Connectez-vous à la borne supérieure du moteur de volet roulant.

**8. Câble de connexion de la sortie moteur O2 (direction vers le bas) (vert)**

Connectez-vous à la borne bas du moteur de volet roulant.

**spécification**

-   Alimentation : 110 - 230 VCA, 50/60 Hz
-   Courant de charge pris en charge : 1/4 HP (puissance en chevaux) ; 1,8 A pour les moteurs à facteur de puissance compensé (charges inductives)
-   Protocole de communication : module série Z-Wave Plus 500

![](<.gitbook/assets/1 (53).jpeg>)

**Prudence**

-   Tous les travaux sur l'appareil, y compris l'installation et la maintenance, doivent être effectués par un électricien qualifié et agréé.
-   Avant l'installation ou tout travail de maintenance, assurez-vous que l'alimentation électrique a été débranchée.
-   Ne connectez pas l'appareil à des charges dépassant le courant de charge pris en charge.
-   Veuillez connecter l'appareil uniquement à un moteur alimenté en courant alternatif.

1

**Caractéristiques**

-   _**Ajout d'un appareil (inclusion)**_

Ce produit peut être inclus et utilisé dans n'importe quel réseau Z-Wave avec d'autres appareils certifiés Z-Wave d'autres fabricants et/ou d'autres applications. Tous les nœuds non alimentés par batterie du réseau agiront comme répéteurs, quel que soit le fournisseur, afin d'augmenter la fiabilité du réseau.

-   -   Connectez l’alimentation au contrôle de l’obturateur (voir le manuel**Installation**).
    -   Mettez la passerelle Z-wave ou le panneau de commande dans**Mode d'inclusion**(veuillez vous référer au manuel de la passerelle Z-wave ou du panneau de commande).
    -   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction.
    -   Reportez-vous au manuel d'utilisation de la passerelle Z-wave ou du panneau de commande pour terminer le processus d'ajout.
    -   Si l'appareil a déjà été ajouté (inclus) dans une autre passerelle/panneau de configuration Z-wave, ou si l'appareil ne peut pas être ajouté à la passerelle/panneau de configuration Z-wave actuelle, essayez d'abord de le supprimer (voir_**Suppression d'un périphérique**_).
-   _**Suppression d'un périphérique (exclusion)**_

L'appareil doit être supprimé du réseau Z-wave existant avant d'être ajouté à un autre.

**Mode d'exclusion**

-   Mettez la passerelle Z-wave ou le panneau de commande dans**Mode d'exclusion**(veuillez vous référer au manuel de la passerelle Z-wave ou du panneau de commande).
-   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction et l'appareil sera supprimé du réseau Z-wave.

**Retour aux paramètres d'usine**

_(Utilisez la réinitialisation d'usine uniquement lorsque le panneau de configuration/passerelle réseau est manquant ou inutilisable)._

La réinitialisation d'usine de l'appareil le restaurera aux paramètres d'usine par défaut (c'est-à-dire qu'il n'est inclus dans aucun réseau Z-wave).

-   -   Appuyez et maintenez enfoncé le bouton de fonction de l'appareil pendant 10 secondes pour réinitialiser les paramètres d'usine.
-   _**Test de portée**_

Pour tester si l'appareil est capable de communiquer avec la passerelle Z-wave ou le panneau de commande :

-   Mettez la passerelle/le panneau en mode test de portée (Walk Test).
-   Appuyez sur le bouton de fonction de l'appareil.
-   La passerelle/le panneau doit afficher si l'appareil se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation de la passerelle/du panneau).

**Installation**

-   _**Câblage avec connecteur d'épissure**_
    -   Le SCM-5 est livré avec des fils terminaux et des pinces intégrés (connecteurs d'épissure Wago 221).
    -   Les connecteurs à 2 fils acceptent les fils solides et toronnés de 0,2 à 4 mm² (24 à 12 AWG).
    -   Veuillez connecter le SCM-5 à l'alimentation secteur, aux interrupteurs locaux et au moteur de volet avec les connecteurs.
    -   Avant le câblage, assurez-vous que l'alimentation est coupée. Pour connecter les fils :
        1.  Soulevez le levier et insérez le fil.**(Photo 1, 2)**

**Image 1****Image 2**

![](<.gitbook/assets/2 (57).png>)

1.  Repoussez le levier vers le bas. Le boîtier transparent vous permet de vérifier si le fil est correctement connecté. Assurez-vous que le fil est bien maintenu en place et ne se détachera pas.**(Photo 3, 4)**

2

**Image 3****Image 4**

![](<.gitbook/assets/3 (57).png>)

-   1.  De la même manière qu'aux étapes 1 et 2, connectez les autres fils avec des connecteurs.
-   SCM-5 doit être connecté selon le schéma ci-dessous :

![](<.gitbook/assets/4 (43).jpeg>)

-   Connectez la borne N du SCM à la borne N de l'alimentation.
-   Connectez la borne L du SCM à la borne L de l'alimentation.
-   Connectez la borne O1 du SCM à la borne ouverte du moteur de volet roulant.
-   Connectez la borne O2 du SCM à la borne de fermeture du moteur d'obturation.
-   **(Commutateur local en option)**Connectez les bornes S2 et S1 du SCM à la borne L de l'alimentation.

**Opération**

-   _**Contrôle de l'obturateur**_
    -   **Contrôle manuel**

Si un commutateur local en option est connecté, l'utilisateur peut appuyer et maintenir enfoncé le bouton du commutateur local haut/bas (S1 haut ; S2 bas) pendant 1 seconde pour contrôler l'obturateur. Lorsqu’il est activé, l’obturateur monte/descend. Lorsque le volet roule, l'utilisateur peut arrêter le volet en appuyant sur le bouton de sens opposé.

-   -   **Réseau Z-Wave**

Une fois que le contrôle de l'obturateur a été inclus avec succès dans un réseau Z-Wave, le contrôleur Z-Wave peut contrôler l'obturateur avec la commande Z-wave Switch Binary Set ou Switch Multilevel Set, en utilisant les paramètres ci-dessous :

-   -   -   Valeur : 0x00~0% (0%)~99 %, 0 % = Fermeture complète, 99 % = Ouverture complète)
        -   Durée de gradation : 0x00
    -   Lorsque chaque mouvement de haut en bas commence, la commande de changement de niveau de démarrage du commutateur multiniveau est envoyée pour initier la transition vers le nouveau niveau. Pendant que le SCM est en mouvement, vous pouvez envoyer une commande de changement de niveau d'arrêt du commutateur à plusieurs niveaux pour arrêter le SCM.

3

-   _**Étalonnage**_
    -   L’heure d’activation par défaut du contrôle d’obturation est**4**minutes.

Lorsque le bouton Haut/Bas est enfoncé, le moteur de l'obturateur est activé pendant 4 minutes.

Lorsqu'une commande Z-Wave est reçue du contrôleur Z-Wave, celui-ci déterminera le pourcentage de course de l'obturateur en utilisant 4 minutes comme base de calcul.

-   -   Pour que le contrôle d'obturation fonctionne correctement, son temps d'activation doit être calibré en fonction de la distance réelle de déplacement de l'obturateur. Il existe deux manières de régler le temps d'activation :
        -   **Calibrage manuel :**Calibrez l’activation selon la procédure ci-dessous :
            1.  Avant l'étalonnage, les commutateurs locaux externes doivent être connectés au contrôle d'obturation.
            2.  Appuyez et maintenez le bouton Fonction pendant 3 secondes et relâchez-le pour passer en mode Calibrage. Le moteur de l'obturateur démarrera pendant 4 minutes lorsque la commande de l'obturateur entrera en mode d'étalonnage.
            3.  Attendez 4 minutes pour que le moteur de l'obturateur arrête de rouler, puis appuyez sur le bouton « Bas » pour abaisser l'obturateur. (Si le volet a atteint la position ouverte en moins de 4 minutes, vous pouvez appuyer sur le bouton « Bas » pour arrêter le moteur du volet. Appuyez ensuite à nouveau sur le bouton « Bas » pour abaisser le volet.)
            4.  Dès que le volet est complètement fermé, appuyez sur le bouton « Up ». La commande de l'obturateur enregistrera le temps nécessaire à l'obturateur pour passer de l'ouverture à la fermeture comme le nouveau "**la période de fermeture**”.
            5.  Après avoir appuyé sur le bouton « Haut » au moment où le volet est complètement fermé, le volet s'enroulera vers la direction ouverte.
            6.  Appuyez sur le bouton « Descente » au moment où l'obturateur est complètement ouvert. La commande de l'obturateur enregistrera le temps nécessaire à l'obturateur pour passer de la fermeture à l'ouverture comme le nouveau "**temps ouvert**”.
            7.  Le contrôle d'obturation enverra un rapport à plusieurs niveaux (0x63), avec sa valeur actuelle, sa valeur cible et/ou sa durée, au contrôleur chaque fois que son niveau change.
        -   Par exemple, s'il faut 30 secondes au volet pour passer de la position « Haut » à « Bas », son nouveau temps de fermeture sera de 30 secondes. Après l'étalonnage, chaque fois que vous appuyez sur le bouton « Descente », l'obturateur s'abaisse pendant 30 secondes.
        -   S'il faut 40 secondes au volet pour passer de la position « Bas » à « Haut », son nouveau temps d'ouverture sera de 40 secondes. Après l'étalonnage, chaque fois que vous appuyez sur le bouton « Haut », l'obturateur s'enroule pendant 40 secondes.
        -   **Commande Z-Wave :**Outre l'étalonnage manuel, les utilisateurs peuvent également ajuster le temps d'activation en envoyant une commande depuis le contrôleur Z-Wave avec la commande Configuration CC, en utilisant les paramètres ci-dessous :

| **Paramètre**                   | **Numéro de paramètre** | **Taille** | **Valeur**    | **Défaut**        |
| ------------------------------- | ----------------------- | ---------- | ------------- | ----------------- |
| Réglage du temps d'ouverture    | 0x01                    | 0x02       | 0x0000~0x00F0 | 0x00F0 (240 s)    |
|                                 |                         |            | (seconde)     |                   |
|                                 |                         |            |               |                   |
| Réglage de l'heure de fermeture | 0x02                    | 0x02       | 0x0000~0x00F0 | 0x00F0 (240 s)    |
|                                 |                         |            | (seconde)     |                   |
|                                 |                         |            |               |                   |
| Position actuelle               | 0x03                    | 0x02       | 0x0000~0x0063 | 0x0063 (99%)      |
|                                 |                         |            | (%)           | Pleinement ouvert |
|                                 |                         |            |               |                   |

-   Numéro de paramètre : 0x01~0x03
    -   Pour le paramètre 1, les utilisateurs peuvent définir le temps d'ouverture (de bas en haut) sur une valeur comprise entre 0 et 255 secondes.
    -   Pour le paramètre 2, les utilisateurs peuvent définir le temps de fermeture (de haut en bas) sur une valeur comprise entre 0 et 255 secondes.
    -   Pour le paramètre 3, les utilisateurs peuvent définir la position actuelle sur une valeur comprise entre %0 et %99.
-   Taille : 0x02. Ce champ est utilisé pour spécifier la taille de la valeur réelle.
-   Valeur de configuration : 0x0000~0x00F0 (secondes)
-   La commande d'obturateur commencera le mouvement dès réception de la commande Z-wave Switch Binary Set ou Switch Multilevel Set, et le mouvement sera exécuté en fonction du réglage de la position actuelle.

Exemple de paramètre de configuration :

| Numéro de paramètre | Taille | Valeur |                |
| ------------------- | ------ | ------ | -------------- |
|                     |        |        |                |
| 01                  | 02     | 0064   | (100 secondes) |
|                     |        |        |                |
| 02                  | 02     | 0064   | (100 secondes) |
|                     |        |        |                |
| 03                  | 02     | 0032   | (50%)          |
|                     |        |        |                |

CHANGER_MULTINIVEAUX_ENSEMBLE : 0x00 (0%)

SCM roulera vers le bas (de haut en bas) pendant 50 secondes : (100/100)\*(100-50)

-   L'heure d'activation sera réinitialisée à**4**minutes chaque fois que le contrôle d'obturation est inclus dans le réseau Z-Wave ou lorsqu'il est réinitialisé aux paramètres d'usine.

_**\\<NOTE>:**_La position actuelle par défaut du contrôle d'obturation est réglée sur 99 % (ouverture totale). Il est recommandé d'ouvrir complètement l'obturateur avant de calibrer avec la commande Z-Wave, sinon veuillez également réajuster le paramètre de position actuelle avec la commande.

4

-   _**Informations sur la vague Z**_

**Classe d'appareil générique :**CHANGER_MULTINIVEAUX

**Classe d'appareil spécifique :**CLASSE_C_MOTEUR_CONTRÔLE

**Type de rôle :**ESCLAVE_TOUJOURS_SUR

**Prise en charge/contrôle de classe de commande**

**Prise en charge CC obligatoire :**

Informations Z-Wave Plus CC

Service de transport CC

Sécurité_2 CC

Supervision CC

Commutation binaire (S2)

Changer CC multiniveau (S2)

Informations sur le groupe d'association CC (S2)

Réinitialisation de l'appareil localement CC (S2)

Configuration CC (S2)

Spécifique au fabricant CC, V2 (S2)

Niveau de puissance CC (S2)

Mise à jour du micrologiciel Md CC, V4 (S2)

Association CC, V2 (S2)

Version CC, V2 (S2)

Multi Channel Association CC, V3 (S2)

-   _**Groupes de Z-Wave (classe de commande d'association version 2)**_

_**Groupe 1 pour « LifeLine » : (nœud maximum x 1)**_

Commutez CC multiniveau, (COMMANDE_CLASSE_CHANGER_MULTINIVEAU)

\#.CHANGER_MULTINIVEAUX_RAPPORT

\#.CHANGER_MULTINIVEAUX_COMMENCER_NIVEAU_CHANGEMENT

\#.CHANGER_MULTINIVEAUX_ARRÊT_NIVEAU_CHANGEMENT

Réinitialisation du périphérique localement CC, (COMMANDE_CLASSE_APPAREIL_RÉINITIALISER_LOCALEMENT)

-   Lorsque le SCM commence à bouger, il enverra\[CHANGER_MULTINIVEAUX_COMMENCER_NIVEAU_CHANGEMENT]
-   Lorsque le SCM arrête de bouger, il enverra\[CHANGER_MULTINIVEAUX_ARRÊT_NIVEAU_CHANGEMENT]
-   Chaque fois que SCM change de position, il enverra\[CHANGER_MULTINIVEAUX_RAPPORT]

5
