# VESTA 166

**Contrôle de l'obturateur (SCM-8ZW)**

**Introduction**

SCM-8ZW est un contrôle d'obturation Z-Wave. L'utilisateur peut contrôler le SCM via le réseau Z-Wave à distance ou manuellement en reliant un commutateur au SCM.

Enroulable, descendant ou arrêté à mi-chemin automatiquement ou à distance, le SCM-8 est directement connecté et contrôle les habillages de fenêtres motorisés, les stores et stores intérieurs et extérieurs, l'écran de projection et la porte de garage ou le portail d'allée de votre maison.

Le contrôle d'obturation est compatible uniquement avec la passerelle/panneau de commande Z-Wave. Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance. En profitant du réseau maillé Z-Wave, les commandes peuvent être acheminées vers leur destination via des produits Z-Wave intermédiaires « d’écoute ».

**Identification des pièces**

1.  **Bouton de fonction**
    -   Appuyez sur le bouton 3 fois en 1,5 seconde pour inclure ou exclure l'appareil du réseau Z-Wave.
    -   Appuyez et maintenez le bouton enfoncé pendant 10 secondes pour réinitialiser les paramètres d'usine.
    -   Appuyez sur le bouton et le contrôle d'obturation enverra un rapport à plusieurs niveaux.
2.  **Indicateur LED (rouge)**
    -   Mise sous tension : la LED clignote deux fois.
    -   Apprentissage réussi : la LED clignote 3 fois.
    -   Réinitialisation d'usine : la LED clignote deux fois.
3.  **Trous de montage**
4.  **Commutateur local S1 (sens ouvert)**
    -   Si le SCM est connecté conformément à la section Installation, le volet s'enroulera pendant 4 minutes après l'activation de l'interrupteur.
    -   L'activation de cet interrupteur lorsque le volet est descendu arrêtera le volet.
5.  **Commutateur local S2 (direction de fermeture)**
    -   Si le SCM est connecté conformément à la section Installation, le volet s'abaissera pendant 4 minutes après l'activation de l'interrupteur.
    -   L'activation de cet interrupteur lorsque le volet est en cours d'enroulement arrêtera le volet.
6.  **Sortie moteur O1 (sens ouvert)**
    -   Connectez-vous à la borne supérieure du moteur de volet roulant.
7.  **Sortie moteur O2 (direction de fermeture)**
    -   Connectez-vous à la borne bas du moteur de volet roulant.
8.  **Borne d'entrée d'alimentation L (fil sous tension)**
9.  **Borne d'entrée d'alimentation N (fil neutre)**
10. **Pince anti-traction**
    -   La pince est utilisée pour fixer les fils et fournir un soulagement de traction pour protéger les fils de la découpe métallique.
11. **Boucle de câblage**
    -   La boucle de câblage est utilisée pour gérer les fils.

![](<.gitbook/assets/0 (59).jpeg>)

**spécification**

-   Alimentation : 100 - 240 VCA, 50/60 Hz
-   Courant de charge pris en charge : 1/2 HP (puissance en chevaux) ; 3,6 A pour les moteurs avec facteur de puissance compensé (charges inductives)

1

-   _**Prudence**_![](<.gitbook/assets/1 (52).jpeg>)
    -   Tous les travaux sur l'appareil, y compris l'installation et la maintenance, doivent être effectués par un électricien qualifié et agréé.
    -   Avant l'installation ou tout travail de maintenance, assurez-vous de débrancher l'alimentation électrique.
    -   Ne connectez pas l'appareil à des charges dépassant le courant de charge pris en charge.
    -   Veuillez connecter l'appareil uniquement à un moteur alimenté en courant alternatif.
-   _**Ajout d'un appareil (inclusion)**_

Ce produit peut être inclus et utilisé dans n'importe quel réseau Z-Wave avec d'autres appareils certifiés Z-Wave d'autres fabricants et/ou d'autres applications. Tous les nœuds non alimentés par batterie du réseau agiront comme répéteurs, quel que soit le fournisseur, afin d'augmenter la fiabilité du réseau.

-   -   Connectez l’alimentation au contrôle de l’obturateur (voir le manuel**Installation**).
    -   Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'inclusion**(veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
    -   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction.
    -   Reportez-vous au manuel d'utilisation de la passerelle Z-Wave ou du panneau de commande pour terminer le processus d'ajout.
    -   Si l'appareil a déjà été ajouté (inclus) dans une autre passerelle/panneau de configuration Z-Wave, ou si l'appareil ne peut pas être ajouté à la passerelle/panneau de configuration Z-Wave actuelle, essayez d'abord de le supprimer (voir_**Suppression d'un périphérique**_).
-   _**Suppression d'un périphérique (exclusion)**_

L'appareil doit être supprimé du réseau Z-Wave existant avant d'être ajouté à un autre.**Mode d'exclusion**

-   Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'exclusion**(veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
-   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction et l'appareil sera supprimé du réseau Z-Wave.

**Retour aux paramètres d'usine**

_(Utilisez la réinitialisation d'usine uniquement lorsque le panneau de configuration/passerelle réseau est manquant ou inutilisable)._

-   -   La réinitialisation d'usine de l'appareil le restaurera aux paramètres d'usine par défaut (c'est-à-dire exclu du réseau Z-Wave).
    -   Appuyez et maintenez enfoncé le bouton de fonction de l'appareil pendant 10 secondes pour réinitialiser les paramètres d'usine.
-   _**Test de portée**_

Pour tester si l'appareil est capable de communiquer avec la passerelle Z-Wave ou le panneau de commande :

-   Mettez la passerelle/le panneau en mode test de portée (Walk Test).
-   Appuyez sur le bouton de fonction de l'appareil
-   La passerelle/le panneau doit s'afficher si l'appareil se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation de la passerelle/du panneau).

**Installation**

-   Veuillez utiliser la taille de fil recommandée de AWG 14-22 ou Ø 2,08-0,326 (mm²). Connectez le SCM selon le schéma ci-dessous :

![](<.gitbook/assets/2 (48).jpeg>)

-   Connectez la borne L du SCM à la borne L de l'alimentation.
-   Connectez la borne N du SCM à la borne N de l'alimentation.
-   Connectez la borne O1 du SCM à la borne haut du moteur de volet roulant.

2

-   Connectez la borne O2 du SCM à la borne Bas du moteur de volet.
-   _**(Commutateur local en option)**_Connectez les bornes S1 et S2 du SCM à la borne L de l'alimentation.
-   Insérez chaque fil dans la borne à laquelle il doit être connecté, serrez chaque vis pour fermer la tondeuse et maintenir les fils en place.
-   Une fois les fils connectés, utilisez la boucle de câblage pour gérer les fils et placez la boucle de câblage sur la base avec son espace (ouverture) positionné sur la gauche.

![](<.gitbook/assets/3 (44).jpeg>)

**Opération**

-   _**Contrôle de l'obturateur**_
    -   **Contrôle manuel**

Si un commutateur local en option est connecté, l'utilisateur peut appuyer et maintenir enfoncé le bouton du commutateur local haut/bas (S1 haut ; S2 bas) pendant 1 seconde pour contrôler l'obturateur. Lorsqu’il est activé, l’obturateur monte/descend.

Lorsque le volet roule, l'utilisateur peut arrêter le volet en appuyant sur le bouton de sens opposé.

-   -   **Réseau Z-Wave**

Une fois que le contrôle de l'obturateur a été inclus avec succès dans un réseau Z-Wave, le contrôleur Z-Wave peut contrôler l'obturateur avec la commande Z-Wave Switch Binary Set ou Switch Multilevel Set, en utilisant les paramètres ci-dessous :

-   -   -   Valeur : 0x00~0% (0%)~99 %, 0 % = Fermeture complète, 99 % = Ouverture complète)
        -   Durée de gradation : 0x00
    -   Lorsque chaque mouvement de haut en bas commence, la commande de changement de niveau de démarrage du commutateur multiniveau est envoyée pour initier la transition vers le nouveau niveau. Pendant que le SCM est en mouvement, vous pouvez envoyer une commande de changement de niveau d'arrêt du commutateur à plusieurs niveaux pour arrêter le SCM.
-   _**Étalonnage**_
    -   L’heure d’activation par défaut du contrôle d’obturation est**4**minutes.

Lorsque le bouton Haut/Bas est enfoncé, le moteur de l'obturateur est activé pendant 4 minutes.

Lorsqu'une commande Z-Wave est reçue du contrôleur Z-Wave, celui-ci déterminera le pourcentage de course de l'obturateur en utilisant 4 minutes comme base de calcul.

-   -   Pour que le contrôle d'obturation fonctionne correctement, son temps d'activation doit être calibré en fonction de la distance réelle de déplacement de l'obturateur. Il existe deux manières de régler le temps d'activation :
        -   **Calibrage manuel :**Calibrez l’activation selon la procédure ci-dessous :
            1.  Avant l'étalonnage, les commutateurs locaux externes doivent être connectés au contrôle d'obturation.
            2.  Appuyez et maintenez le bouton Fonction pendant 3 secondes et relâchez-le pour passer en mode Calibrage. Le moteur de l'obturateur démarrera pendant 4 minutes lorsque la commande de l'obturateur entrera en mode d'étalonnage.
            3.  Attendez 4 minutes pour que le moteur de l'obturateur arrête de rouler, puis appuyez sur le bouton « Descente » pour abaisser le volet. (Si en moins de 4 minutes le volet a déjà atteint la position ouverte, vous pouvez appuyer sur le bouton « Bas » pour arrêter le moteur du volet. Appuyez ensuite à nouveau sur le bouton « Bas » pour abaisser le volet.)
            4.  Dès que le volet est complètement fermé, appuyez sur le bouton « Up ». La commande de l'obturateur enregistrera le temps nécessaire à l'obturateur pour passer de l'ouverture à la fermeture comme le nouveau "**la période de fermeture**”.
            5.  Après avoir appuyé sur le bouton « Haut » au moment où le volet est complètement fermé, le volet s'enroulera vers la direction ouverte.
            6.  Appuyez sur le bouton « Descente » au moment où l'obturateur est complètement ouvert. La commande de l'obturateur enregistrera le temps nécessaire à l'obturateur pour passer de la fermeture à l'ouverture comme le nouveau "**temps ouvert**”.
            7.  Le contrôle d'obturation enverra un rapport à plusieurs niveaux, avec sa valeur actuelle, sa valeur cible et/ou sa durée, au contrôleur chaque fois que son niveau change.
        -   Par exemple, s'il faut 30 secondes au volet pour passer de la position « Haut » à « Bas », son nouveau temps de fermeture sera de 30 secondes. Après l'étalonnage, chaque fois que vous appuyez sur le bouton « Descente », l'obturateur s'abaisse pendant 30 secondes.
        -   S'il faut 40 secondes au volet pour passer de la position « Bas » à « Haut », son nouveau temps d'ouverture sera de 40 secondes. Après l'étalonnage, chaque fois que vous appuyez sur le bouton « Haut », l'obturateur s'enroule pendant 40 secondes.

3

-   **Commande Z-Wave :**Outre l'étalonnage manuel, les utilisateurs peuvent également ajuster le temps d'activation en envoyant une commande depuis le contrôleur Z-Wave avec la commande Configuration CC, en utilisant les paramètres ci-dessous :

| **Paramètre**                   | **Numéro de paramètre** | **Taille** | **Valeur**    | **Défaut**        |
| ------------------------------- | ----------------------- | ---------- | ------------- | ----------------- |
| Réglage du temps d'ouverture    | 0x01                    | 0x02       | 0x0000~0x00FF | 0x00F0 (240 s)    |
|                                 |                         |            | (seconde)     |                   |
|                                 |                         |            |               |                   |
| Réglage de l'heure de fermeture | 0x02                    | 0x02       | 0x0000~0x00FF | 0x00F0 (240 s)    |
|                                 |                         |            | (seconde)     |                   |
|                                 |                         |            |               |                   |
| Position actuelle               | 0x03                    | 0x02       | 0x0000~0x0063 | 0x0063 (99%)      |
|                                 |                         |            | (%)           | Pleinement ouvert |
|                                 |                         |            |               |                   |

 Numéro de paramètre : 0x01~0x03

 Pour le paramètre 1, l'utilisateur peut régler le temps d'ouverture (de bas en haut) à une valeur comprise entre 0 et 255 secondes.

 Pour le paramètre 2, les utilisateurs peuvent régler le temps de fermeture (de haut en bas) à une valeur comprise entre 0 et 255 secondes.

 Pour le paramètre 3, les utilisateurs peuvent définir la position actuelle sur une valeur comprise entre %0 et %99.

 Taille : 0x02. Ce champ est utilisé pour spécifier la taille de la valeur réelle.

 Valeur de configuration : 0x0000~0x00FF (secondes)

 La commande d'obturation commencera le mouvement dès réception de la commande Z-Wave Switch Binary Set ou Switch Multilevel Set, et le mouvement sera exécuté en fonction du réglage de la position actuelle.

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

 Le temps d'activation sera réinitialisé à**4**minutes chaque fois que le contrôle d'obturation est inclus dans le réseau Z-Wave ou lorsqu'il est réinitialisé aux paramètres d'usine.

_**\\<NOTE>:**_La position actuelle par défaut du contrôle d'obturation est réglée sur 99 % (ouverture totale). Il est recommandé d'ouvrir complètement l'obturateur avant de calibrer avec la commande Z-Wave, sinon veuillez également réajuster le paramètre de position actuelle avec la commande.

-   _**Informations sur la vague Z**_

**Classe d'appareil générique :**CHANGER_MULTINIVEAUX

**Classe d'appareil spécifique :**CLASSE_C_MOTEUR_CONTRÔLE

**Type de rôle :**ESCLAVE_TOUJOURS_SUR

**Prise en charge/contrôle de classe de commande**

**Prise en charge CC obligatoire :**Informations Z-Wave Plus CC

Service de transport CC

Sécurité_2 CC

Supervision CC

Commutation binaire (S2)

Commutateur multiniveau CC, V4 (S2)

Informations sur le groupe d'association CC (S2)

Réinitialisation de l'appareil localement CC (S2)

Configuration CC (S2)

Spécifique au fabricant CC, V2 (S2)

Niveau de puissance CC (S2)

Mise à jour du micrologiciel Md CC, V4 (S2)

Association CC, V2 (S2)

Version CC, V2 (S2)

Association multicanal CC, V3 (S2)

-   _**Groupes de Z-Wave (classe de commande d'association version 2)**_

_**Groupe 1 pour « LifeLine » : (nœud maximum x 1)**_

Commutateur multiniveau CC, V4 (COMMANDE_CLASSE_CHANGER_MULTINIVEAU)

\#.CHANGER_MULTINIVEAUX_RAPPORT

Réinitialisation locale de l'appareil CC, V4 (COMMANDE_CLASSE_APPAREIL_RÉINITIALISER_LOCALEMENT)

-   Lorsque le SCM change de position :\[CHANGER_MULTINIVEAUX_RAPPORT] 4
