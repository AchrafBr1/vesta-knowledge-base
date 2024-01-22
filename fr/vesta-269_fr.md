# VESTA 269

**Pince multimètre (CLMT-1ZW)**

CL-Meter-ZW est une pince multimètre Z-Wave visant à surveiller et à signaler la quantité totale d'électricité utilisée dans votre installation en connectant la pince au câble d'alimentation.

Le compteur d'énergie est un appareil compatible Z-Wave et est entièrement compatible avec tout réseau compatible Z-Wave.

Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance. En profitant du réseau maillé Z-Wave, les commandes peuvent être acheminées vers leur destination via des produits Z-Wave intermédiaires « d’écoute ».

![](<.gitbook/assets/0 (100).jpeg>)

**Identification des pièces**

**1. LED rouge**

Clignote une fois :

Lorsque la pince multimètre transmet un signal.

Flasher deux fois :

La pince multimètre a rejoint avec succès un réseau Z-Wave.

1.  **Câble d'entrée CA**
2.  **Câble de transformateur de courant (CT2)**
3.  **Câble de transformateur de courant (CT1)**
4.  **Bouton de fonction**

\-Appuyez une fois sur le bouton pour signaler la valeur du compteur au réseau Z-Wave.

\-Appuyez 3 fois sur le bouton en 1,5 seconde pour transmettre un code d'apprentissage.

\-Appuyez et maintenez le bouton enfoncé pendant 10 secondes pour réinitialiser la pince multimètre aux paramètres d'usine.

1.  **Réservé**
2.  **Trou de montage**
3.  **Crochets de montage**
4.  **Support de montage**

**Installation**

![](<.gitbook/assets/1 (69).png>)

-   _**Câblage**_

![](<.gitbook/assets/2 (76).png>)**AVERTISSEMENT**

Le câblage de l'appareil ne doit être effectué que par un électricien agréé. Le disjoncteur principal du boîtier de circuit doit être éteint pour effectuer l’installation.

La spécification du fil du trou d'insertion est AWG18 ou Ø 1,02 (mm²).

La spécification de la pince est 60A Ø 10mm

Veuillez vous assurer que l'alimentation principale de votre installation est également coupée avant l'installation. Suivez les étapes ci-dessous :

1.  Connectez le câble d'entrée CA à une prise proche du boîtier électrique pour allumer la pince multimètre.
2.  Ouvrez la pince comme indiqué sur l'image ci-dessous. La pince doit être appliquée sur un câble électrique. La direction de la flèche sur la pince doit pointer vers la bonne direction du flux de courant électrique (**KL**). Si la flèche est orientée dans le sens inverse, la lecture affichera une valeur négative (-), mais cela n'influencera pas les lectures.

![](<.gitbook/assets/3 (74).png>)

**K**

**L**

1.  Suivez les schémas ci-dessous à titre d'exemple ; clipsez les pinces des câbles électriques sur le 2 câble d'alimentation entrant connecté au Disjoncteur Principal.

![](<.gitbook/assets/4 (79).png>)

-   _**Montage**_

La pince multimètre est dotée d'un support de montage à des fins de montage.

1.  Utilisez le support de montage comme modèle pour marquer les deux trous sur le mur pour l'installation des vis.
2.  Vissez le support de montage sur le mur selon l'emplacement marqué. Installez des chevilles murales si nécessaire.
3.  Localisez les crochets du support de montage et alignez les crochets avec les trous de montage de la pince multimètre. Insérez les crochets dans les trous de montage comme sur l'image ci-dessous. L'installation est maintenant terminée.

![](<.gitbook/assets/5 (79).png>)

-   _**Ajout d'un appareil (inclusion)**_

Ce produit peut être inclus et utilisé dans n'importe quel réseau Z-Wave avec d'autres appareils certifiés Z-Wave d'autres fabricants et/ou d'autres applications. Tous les nœuds non alimentés par batterie du réseau agiront comme répéteurs, quel que soit le fournisseur, afin d'augmenter la fiabilité du réseau.

-   -   Branchez le câble d’entrée CA dans la prise pour allumer la pince multimètre.
    -   Mettez le panneau de commande Z-Wave dans**Mode d'inclusion**(veuillez vous référer au manuel du panneau de commande Z-Wave).
    -   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction.
    -   Reportez-vous au manuel d'utilisation de la passerelle Z-Wave ou du panneau de commande pour terminer le processus d'ajout.
    -   Si l'appareil a déjà été ajouté (inclus) dans une autre passerelle/panneau de configuration Z-Wave, ou si l'appareil ne peut pas être ajouté à la passerelle/panneau de configuration Z-Wave actuelle, essayez d'abord de le supprimer (voir_**Suppression d'un périphérique**_).
-   _**Suppression d'un périphérique (exclusion)**_

![](<.gitbook/assets/6 (59).png>)

L'appareil doit être supprimé du réseau Z-Wave existant avant d'être ajouté à un autre.**Mode d'exclusion**

-   Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'exclusion** (please refer to the Z-Wave or control panel manual).
-   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction et l'appareil sera supprimé du réseau Z-Wave.

**Retour aux paramètres d'usine**

La réinitialisation d'usine de l'appareil le restaurera aux paramètres d'usine par défaut (c'est-à-dire qu'il n'est inclus dans aucun réseau Z-Wave). Veuillez utiliser cette procédure uniquement si la passerelle ou le panneau de commande Z-Wave est perdu ou inutilisable.

-   -   Appuyez et maintenez enfoncé le bouton de fonction de l'appareil pendant 10 secondes pour réinitialiser les paramètres d'usine.
-   _**Test de portée**_

![](<.gitbook/assets/7 (54).png>)

Pour tester si l'appareil est capable de communiquer avec la passerelle Z-Wave ou le panneau de commande :

-   -   Mettez la passerelle/le panneau de commande en mode test de portée (Walk Test).
    -   Appuyez sur le bouton de fonction de l'appareil.
    -   La passerelle/panneau de commande doit s'afficher si l'appareil se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation de la passerelle/panneau de commande).
-   _**Moniteur de consommation d'énergie**_
    -   -   La pince multimètre transmettra un signal de la pince elle-même avec ses données de consommation d'énergie toutes les 10 minutes au coordinateur du réseau Z-Wave.
            -   La lecture de la pince sur le câble du transformateur de courant CT-1 est signalée au canal 1 du compteur.
            -   La lecture de la pince sur le câble du transformateur de courant CT-2 est signalée au canal 2 du compteur.
        -   Chaque fois que la production d'énergie de la pince change de +/- 2 W, la pince multimètre transmettra automatiquement un signal avec les données de consommation d'énergie au coordinateur du réseau Z-Wave pour mise à jour.
        -   La pince multimètre transmet un signal avec des données de puissance au coordinateur chaque fois que la consommation d'énergie accumulée de la pince augmente de 0,1 kW/h.
        -   La pince a une précision de +/- 5 %.
        -   Pour effacer la pince de ses données de consommation d'énergie accumulées, suivez les étapes ci-dessous :

![](<.gitbook/assets/8 (54).png>)

1.  Débranchez le câble CA pour éteindre la pince multimètre.
2.  Appuyez et maintenez enfoncé le bouton de fonction, tout en maintenant le bouton enfoncé, allumez la pince multimètre en rebranchant le câble secteur.
3.  Relâchez le bouton de fonction lorsque la LED rouge commence à clignoter rapidement.
4.  Débranchez et rebranchez le câble AC, le nettoyage est terminé.

-   ![](<.gitbook/assets/9 (50).png>)_**Charge de fonctionnement maximale**_
    -   110V : 6600W et 60A
    -   230V : 13800W et 60A.

**Informations sur la vague Z**

**Type d'appareil:**Compteur pour toute la maison - Simple

**Type de rôle :**Toujours sur esclave (AOS)

Prise en charge/contrôle de classe de commande

Support CC obligatoire : Association CC, v2

Informations sur le groupe d'association CC

Réinitialisation de l'appareil localement CC

Manufacturer Specific CC, v2

Association multicanal CC, V3

CC multicanal, V4

Compteur CC, V2

CRC 16 ENCAP

VersionCC, v2

Z-Wave Plus Info CC, v2

Niveau de puissance CC,

Mise à jour du micrologiciel CC, v2

![](<.gitbook/assets/10 (52).png>)

-   _**Groupes de Z-Wave (classe de commande d'association version 2)**_

Le compteur peut être configuré pour envoyer des rapports aux appareils Z-Wave associés. Il prend en charge 3 groupes d'association dont chaque groupe prend en charge un nœud. Groupe 1~Groupe 3 support METER_RAPPORT_COMMANDE_Classe

Groupe 1 pour « LifeLine » : (nœud maximum : 1)

Réinitialisation de l'appareil localement CC, V2

Compteur CC, V2

Pour le groupe 1, la pince multimètre indiquera :

1.  La somme de la consommation électrique instantanée (Watt) lue sur CT1 et CT2
2.  La somme de la consommation électrique accumulée (KWh) lue sur CT1 et CT2 Groupe 2 pour le « compteur CT1 » (nœud maximum : 1)

Compteur CC, V2

Pour le groupe 2, le Switch signalera :

1.  Consommation d'énergie instantanée (Watt) lue sur CT1
2.  Consommation d'énergie accumulée (KWh) lue sur CT1 Groupe 3 pour le « compteur CT2 » : (nœud maximum : 1)

Compteur CC, V2

Pour le groupe 3, le Switch signalera

-   1.  La somme de la consommation électrique instantanée (Watt) lue sur CT2
    2.  La somme de la consommation d'énergie accumulée (KWh) lue sur CT2
-   _**Association multicanal de Z-Wave**_

![](<.gitbook/assets/11 (42).png>)

La classe de commande d'association multicanal est utilisée pour créer des liaisons d'application avec des ressources de point de terminaison multicanal ainsi qu'avec des périphériques racine. La classe de commande peut gérer les nœuds avec et sans points finaux.

Pour Root, il prend en charge au maximum 1 nœud et au maximum 3 groupes d'association

| Racine   | Profil 2 octets                | Classe de commande                        | Nom de groupe                              |
| -------- | ------------------------------ | ----------------------------------------- | ------------------------------------------ |
|          |                                |                                           | (UTF-8)                                    |
| Groupe 1 | Général : bouée de sauvetage   | L'appareil est réinitialisé localement et | "Corde de sécurité"                        |
|          |                                | rapport de compteur                       |                                            |
| Groupe 2 | Compteur : Compteur électrique | rapport de compteur                       | « Compteur CT 1 »                          |
|          |                                |                                           | (miroir du point final 1 groupe2)          |
| Groupe 3 | Compteur : Compteur électrique | rapport de compteur                       | « Compteur CT 2 »                          |
|          |                                |                                           | (miroir du point de terminaison 2 groupe2) |

Pour le point de terminaison 1, il prend en charge un maximum de 1 nœud et un maximum de 2 groupes d'association.

| Point final 1 | Profil 2 octets                | Classe de commande  | Nom de groupe         |
| ------------- | ------------------------------ | ------------------- | --------------------- |
|               |                                |                     | (UTF-8)               |
| Groupe 1      | Général : bouée de sauvetage   | rapport de compteur | « Ligne de vie EP 1 » |
| Groupe 2      | Compteur : Compteur électrique | rapport de compteur | « Compteur CT 1 »     |

Pour Endpoint 2, il prend en charge un maximum de 1 nœud et un maximum de 2 groupes d'association.

| Point de terminaison 2 | Profil 2 octets                | Classe de commande  |   | Nom de groupe         |   |   |
| ---------------------- | ------------------------------ | ------------------- | - | --------------------- | - | - |
|                        |                                |                     |   | (UTF-8)               |   |   |
|                        |                                |                     |   |                       |   |   |
| Groupe 1               | Général : bouée de sauvetage   | rapport de compteur |   | « Ligne de vie EP 2 » |   |   |
| Groupe 2               | Compteur : Compteur électrique | rapport de compteur |   | « Compteur CT 2 »     |   |   |

-   ![](<.gitbook/assets/12 (44).png>)_**Point de terminaison sélectionné**_

Si le contrôleur peut utiliser Multi_Classe de commande de canal pour accéder au point final de la pince multimètre, vous pouvez configurer la valeur du point final pour réagir à la classe de commande du compteur V2.

**Point final sélectionné 1 : (pour CT1 du premier canal)**

-   Type d'appareil : compteur simple
-   Classes de commandes prises en charge Z-Wave Plus Info CC, V2 Association CC, V2 Association Informations sur le groupe CC Multi Channel Association CC, V3 Meter CC, V2
-   Description:

Pour le point final 1, la pince multimètre signalera

-   1.  Consommation d'énergie instantanée (Watt) lue sur CT1.
    2.  Consommation d'énergie accumulée (KWh) lue sur CT1.

**Point final sélectionné 2 : (pour CT2 du deuxième canal)**

-   Type d'appareil : compteur simple
-   Classes de commandes prises en charge Informations Z-Wave Plus CC, V2 Association CC, V2 Informations sur le groupe d'association CC Association multicanal CC, V3 Compteur CC, V2
-   Description:

Pour le point final 2, la pince multimètre signalera

-   1.  Consommation d'énergie instantanée (Watt) lue sur CT2.
    2.  Consommation d'énergie accumulée (KWh) lue sur CT2
