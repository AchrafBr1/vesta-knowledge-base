# VESTA 171

**Vanne de radiateur thermostatique TRV-1ZW**

**Introduction**

TRV-1ZW est une vanne de radiateur Z-Wave conçue pour contrôler la température ambiante en contrôlant le débit d'eau chaude des radiateurs du réseau Z-Wave, c'est-à-dire la température ambiante intérieure.

La vanne de radiateur est un appareil compatible Z-Wave et est entièrement compatible avec tout réseau compatible Z-Wave.

Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance. En profitant du réseau maillé Z-Wave, les commandes peuvent être acheminées vers leur destination via des produits Z-Wave intermédiaires « d’écoute ».

**Identification des pièces**

1. **Capuchon de valve**
2. **Affichage LCD**

![](<.gitbook/assets/0 (49).png>) ![](<.gitbook/assets/1 (56).jpeg>)

1. ![](<.gitbook/assets/2 (51).jpeg>)**SUR**lorsque l'appareil est déjà ajouté au réseau Z-Wave.
2. ![](<.gitbook/assets/3 (46).jpeg>)**Indicateur de batterie faible.**
3. ![](<.gitbook/assets/4 (45).jpeg>)Allumé : Appareil réglé sur la température par défaut de 17 °C.

![](<.gitbook/assets/5 (28).jpeg>)Flash : fermeture de la vanne.

![](<.gitbook/assets/6 (38).jpeg>)Allumé : Appareil réglé sur la température par défaut de 21 °C.

![](<.gitbook/assets/7 (36).jpeg>)Flash : Ouverture de la vanne.

1. **Mode automatique/manuel.**
2. **Fonction Boost.**
3. **Fenêtre ouverte**.
4. **Indicateur de température.**

![](<.gitbook/assets/8 (36).png>)

**Autres : InS**: Lors de la mise sous tension de l'appareil (également pendant la période d'apprentissage).

\*\*Il y a:\*\*Le moteur de l'appareil fonctionne.

\*\*F1/F :\*\*la valve est bloquée,\*\*F2:\*\*aucune vanne installée.

**3. Boutons de fonction**

-\*\*Manuel/Auto :\*\*Passez en mode manuel ou automatique.

-\*\*Boost/Z-Wave :\*\*Accélérez le processus de chauffage/ajoutez-le au réseau Z-Wave.

-![](<.gitbook/assets/9 (21).jpeg>)Appuyez sur ce bouton pour changer instantanément les températures diurnes et nocturnes.

_**Jour par défaut**_![](<.gitbook/assets/10 (16).jpeg>)_température: 21\_°C_,**Nuit par défaut**\_![](<.gitbook/assets/11 (21).jpeg>)\_température: 17\_°C

1. **Capteur de température**
2. **Bouton de controle**

Ajustez la température manuellement.

**6. Compartiment à piles**

La vanne de radiateur est alimentée par deux piles alcalines AA de 1,5 V.

1

**Caractéristiques**

![](<.gitbook/assets/12 (31).png>)

* _**Batterie**_

La vanne de radiateur utilise deux piles alcalines AA de 1,5 V comme source d'alimentation. La vanne de radiateur signalera son pourcentage de batterie à la passerelle/au panneau de commande respectivement à 100 %, 75 %, 50 % et 25 %. Si la tension de la batterie est faible (25 %), un signal de batterie faible sera envoyé à la passerelle/au panneau de commande pour avertir l'utilisateur.

La vanne de radiateur peut détecter si la batterie est faible. Lorsqu'une faible tension de batterie est détectée, un signal de batterie faible

sera envoyé à la passerelle/au panneau de commande Z-Wave et l'écran LCD affichera![](<.gitbook/assets/13 (20).jpeg>)icône pour avertir l’utilisateur.

![](<.gitbook/assets/14 (19).png>)

* _**Mise sous tension/mode manuel/auto**_

**Allumer**: Lorsque la vanne de radiateur s'allume, son moteur commence à fonctionner avec un affichage LCD**InS**, l'appareil est prêt à être installé et démarre le processus d'apprentissage. (voir**Installation**pour plus de détails)

\*\*Mode manuel:\*\*En mode Manuel, vous pouvez utiliser les fonctions suivantes :

* ![](<.gitbook/assets/15 (17).jpeg>)Bouton : changez instantanément les températures jour/nuit.
* \*\*Bouton Boost :\*\*Accélérer le chauffage/Ajout d'un appareil dans la passerelle Z-Wave ou le panneau de commande.
* **Bouton de controle**: Contrôle de la température, réglé sur ON (mode saison été) et OFF (mode saison hiver).

\*\*Mode voiture :\*\*Le mode Auto n'est disponible que lorsque l'appareil est appris avec un panneau de commande. Après avoir appris à utiliser le panneau de commande, vous pouvez contrôler et définir automatiquement le programme horaire de la vanne de radiateur via le panneau de commande (veuillez vous référer au manuel de votre panneau de commande pour plus de détails). En mode automatique, vous pouvez utiliser les mêmes fonctions qu'en mode manuel. sauf le bouton de commande réglé sur la fonction ON et OFF.

![](<.gitbook/assets/16 (21).png>)

* _**Anti-givre**_

Lorsque la vanne de radiateur détecte un risque de gel, elle ouvre automatiquement la vanne pour que l'eau chaude s'écoule afin de maintenir la température et d'éviter un givre supplémentaire.

![](<.gitbook/assets/17 (17).png>)

* _**Anti-calcification**_

La vanne de radiateur ouvrira et fermera la vanne chaque semaine pour éviter la calcification. Pendant le processus anti-calcification, l'écran LCD affichera un**CAL**.

La valeur par défaut du processus anti-calcification est 23h00 tous les samedis.

![](<.gitbook/assets/18 (21).png>)

* _**Fonction Boost**_

Appuyez et maintenez enfoncé le bouton Boost pendant 3 secondes pour accélérer temporairement le processus de chauffage en ouvrant davantage la vanne. La fonction boost dure 5 minutes (écrans LCD : compte à rebours de 300 secondes). Si vous souhaitez annuler la fonction boost, appuyez à nouveau sur le bouton et maintenez-le enfoncé pendant 3 secondes.

![](<.gitbook/assets/19 (22).png>)

* _**Décalage du point de consigne**_

L'appareil est généralement installé dans un coin de la pièce et à proximité du tuyau de chauffage. En conséquence, la température relevée peut s'écarter de la température ambiante au centre de la pièce. Utilisez la fonction Offset du point de consigne pour compenser l’écart.

Pour calculer le décalage du point de consigne, soustrayez simplement la température ambiante à la température de l'appareil.

Exemple : Si la température de l'appareil est de 20°C et la température ambiante de 18°C, alors décalage du point de consigne =18 – 20= -2°C.

Une fois le décalage du point de consigne appliqué, l'appareil fonctionnera en fonction de la température ajustée.

Par exemple : Si la température de l'appareil est de 20 °C et que le décalage du point de consigne est de -2 °C, l'appareil fonctionnera en utilisant 18 °C comme référence réelle.

Pour programmer le décalage du point de consigne :

*
  1. Appuyez et maintenez le![](<.gitbook/assets/20 (11).jpeg>)pendant 3 secondes pour entrer dans le réglage du décalage.
  2. Rotate the Control Knob to desired offset temperature.
  3. Appuyez sur n’importe quelle touche pour terminer et quitter le réglage du décalage.
* _**Fenêtre ouverte**_

Si la vanne de radiateur détecte une baisse rapide de la température intérieure en ouvrant la fenêtre, la vanne de radiateur activera la fonction d'ouverture de fenêtre en fermant partiellement la vanne pour réduire le réglage de la température pendant 15 minutes. Le

L'écran LCD affichera le symbole, l'appareil vérifiera la température toutes les minutes. Après 15 minutes, la vanne du radiateur reviendra à la température réglée avec la vanne s'ouvrant à nouveau, la fonction d'ouverture de fenêtre se ferme.

* _**Bouton de controle**_

Tournez le bouton de commande pour régler la température, tournez dans le sens des aiguilles d'une montre pour réduire la température et dans le sens inverse des aiguilles d'une montre pour augmenter la température. La plage de température réglable est de 5°C à 30°C. Si vous tournez le bouton de commande à une température inférieure à 5°C sur On, après 1 minute, la vanne du radiateur ouvrira complètement la vanne, pour préserver la batterie, si vous tournez le bouton de commande à une température inférieure à 5°C sur Off, après 1 minute, la vanne de radiateur fermera complètement la vanne. Pour désactiver l'état ON/Off, veuillez tourner le bouton de commande ou appuyer sur

bouton . La fonction Boost n'est pas disponible sous le bouton de commande réglé sur l'état ON/Off.

\*\*SUR:\*\*Lorsqu'elle est allumée, la vanne est complètement ouverte. Cette fonction permet de préserver la durée de vie de la batterie en été, lorsque le chauffage n'est pas nécessaire. N'utilisez pas cette fonction en hiver lorsque le chauffage est activé,

2

sinon la température ambiante augmentera de manière incontrôlée.

\*\*DÉSACTIVÉ:\*\*Lorsqu'elle est sur OFF, la vanne est complètement fermée. Cette fonction est utilisée lorsque le chauffage est activé mais que le chauffage n'est pas requis dans une pièce sans occupants.

* _**Fonction de verrouillage des touches**_

Appuyez et maintenez enfoncés le bouton Auto/Manuel et le bouton pendant 3 secondes pour activer la fonction de verrouillage des touches. Si

Si l'opération est réussie, l'écran LCD affichera le symbole. Toutes les touches et actions du bouton de commande ne répondront pas\*\*.\*\*Si vous le souhaitez

pour annuler la fonction de verrouillage des touches, veuillez également appuyer et maintenir enfoncés le bouton Auto/Manuel et le bouton pendant 3 secondes.

* _**Télécommande**_

Une fois que la vanne de radiateur a rejoint un réseau Z-Wave, vous pouvez contrôler la vanne de radiateur via le coordinateur de réseau ou la passerelle Z-Wave. Veuillez vous référer au manuel de votre coordinateur/passerelle Z-Wave pour plus d'informations. Les fonctions suivantes sont uniquement disponibles pour le réglage via le coordinateur et la passerelle Z-Wave :

*
  * **Calendrier:**

Vous pouvez uniquement programmer la configuration du calendrier via le coordinateur/passerelle du réseau Z-Wave.

Paramétrage des horaires : jusqu'à 5 horaires peuvent être programmés pour chaque jour de la semaine avec le mode, le point de consigne et l'heure de début.

Contrôle du calendrier :

Normal - La vanne de radiateur exécutera le réglage du programme programmé en conséquence.

Pas de programme – La vanne de radiateur n'exécutera aucun programme défini jusqu'à ce qu'elle soit à nouveau réglée sur Normal.

* _**Ajout d'un appareil (inclusion)**_

Ce produit peut être inclus et utilisé dans n'importe quel réseau Z-Wave avec d'autres appareils certifiés Z-Wave d'autres fabricants et/ou d'autres applications. Tous les nœuds non alimentés par batterie du réseau agiront comme répéteurs, quel que soit le fournisseur, afin d'augmenter la fiabilité du réseau.

* Retirez le couvercle arrière de la vanne de radiateur et insérez 2 piles alcalines AA pour alimenter le radiateur.

Valve, l'écran LCD affichera**InS**et l'icône clignotera pour indiquer que le moteur de la vanne de radiateur fonctionne.

* Mettez le panneau de commande Z-Wave dans**Mode d'inclusion**(veuillez vous référer au manuel du panneau de commande Z-Wave).
* Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton Boost.
* Reportez-vous au manuel d'utilisation de la passerelle Z-Wave ou du panneau de commande pour terminer le processus d'ajout.
* Si l'appareil a déjà été ajouté (inclus) dans une autre passerelle/panneau de configuration Z-Wave, ou si l'appareil ne peut pas être ajouté à la passerelle/panneau de configuration Z-Wave actuelle, essayez d'abord de le supprimer (voir\_**Suppression d'un périphérique**\_).
* Lorsque le moteur cesse de fonctionner et que l'icône reste allumée, fixez le capuchon de la valve au tuyau.
* Tournez le capuchon de la valve dans le sens des aiguilles d'une montre pour serrer la valve du radiateur.
*
* _**Suppression d'un périphérique (exclusion)**_

L'appareil doit être supprimé du réseau Z-Wave existant avant d'être ajouté à un autre.**Mode d'exclusion**

* Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'exclusion**(veuillez vous référer au manuel du Z-Wave ou du panneau de commande).

3

*
  * Dans les 1,5 secondes, appuyez 3 fois sur le bouton Boost et l'appareil sera supprimé du réseau Z-Wave.

**Retour aux paramètres d'usine**

La réinitialisation d'usine de l'appareil le restaurera aux paramètres d'usine par défaut (c'est-à-dire qu'il n'est inclus dans aucun réseau Z-Wave). Veuillez utiliser cette procédure uniquement si la passerelle ou le panneau de commande Z-Wave est perdu ou inutilisable.

*
  * Appuyez et maintenez le bouton Boost pendant 10 secondes pour réinitialiser les paramètres d'usine.
* _**Test de portée**_

Pour tester si l'appareil est capable de communiquer avec la passerelle Z-Wave ou le panneau de commande :

*
  * Mettez la passerelle/le panneau en mode test de portée (Walk Test).
  * Appuyez et maintenez le bouton Boost pendant une seconde.
  * La passerelle/le panneau doit s'afficher si l'appareil se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation de la passerelle/du panneau).
* _**Mode veille Z-Wave**_
  * La vanne de radiateur entrera en mode veille Z-Wave (pour économiser l'énergie) après une courte période de réveil (\~10 secondes). En mode veille Z-Wave, les passerelles ou panneaux de commande Z-Wave ne peuvent pas envoyer de commandes à la vanne de radiateur.
  * Pour programmer la vanne de radiateur à l'aide de la passerelle/panneau de commande Z-Wave, veuillez envoyer des commandes à la vanne de radiateur pendant la période de réveil.
* _**Commande de jeu de configuration**_
  * La vanne de radiateur permet à l'utilisateur de définir des valeurs de délai d'ouverture et de fermeture. La valeur par défaut est de 2 minutes (max : 5 minutes).
  * Si 4 minutes sont définies pour le délai d'ouverture, l'appareil enverra un rapport d'ouverture d'état de fonctionnement 4 minutes après l'ouverture de la vanne. Si 4 minutes sont définies pour le délai de fermeture, la vanne sera fermée 4 minutes après l'envoi d'un rapport de fermeture d'état de fonctionnement.
  * La vanne dispose également d'un rapport d'état périodique ; la valeur par défaut est de 60 minutes. La minuterie sera réinitialisée chaque fois que l’état de fonctionnement est modifié.
  * La commande Configuration Set est utilisée pour définir la valeur d'un paramètre de configuration :

| 7                               |                                                           | 6                                           |                                                      | 5      |                                  | 4                         |   | 3 |   | 2            |   |        | 1 |   | 0 |
| ------------------------------- | --------------------------------------------------------- | ------------------------------------------- | ---------------------------------------------------- | ------ | -------------------------------- | ------------------------- | - | - | - | ------------ | - | ------ | - | - | - |
|                                 |                                                           |                                             | Classe de commande = COMMANDE\_CLASSE\_CONFIGURATION |        |                                  |                           |   |   |   |              |   |        |   |   |   |
|                                 |                                                           |                                             |                                                      |        | Commande=CONFIGURATION\_ENSEMBLE |                           |   |   |   |              |   |        |   |   |   |
|                                 |                                                           |                                             |                                                      |        |                                  | Numéro de paramètre       |   |   |   |              |   |        |   |   |   |
| Défaut                          |                                                           |                                             |                                                      |        | Réservé                          |                           |   |   |   |              |   | Taille |   |   |   |
|                                 |                                                           |                                             |                                                      |        |                                  | Valeur de configuration 1 |   |   |   |              |   |        |   |   |   |
|                                 |                                                           |                                             |                                                      |        |                                  |                           | … |   |   |              |   |        |   |   |   |
|                                 |                                                           |                                             |                                                      |        |                                  | Valeur de configuration N |   |   |   |              |   |        |   |   |   |
|                                 |                                                           |                                             |                                                      |        |                                  |                           |   |   |   |              |   |        |   |   |   |
| COMMANDE\_CLASSE\_CONFIGURATION |                                                           | Numéro de paramètre                         |                                                      | Taille |                                  | Valeur                    |   |   |   |              |   |        |   |   |   |
|                                 |                                                           |                                             |                                                      |        |                                  |                           |   |   |   |              |   |        |   |   |   |
|                                 |                                                           | Point de consigne\_compenser                |                                                      |        |                                  | 0                         |   |   |   |              | 2 | 0000   |   |   |   |
|                                 |                                                           |                                             |                                                      |        |                                  |                           |   |   |   |              |   |        |   |   |   |
|                                 | Délai de rapport d'ouverture de l'état de fonctionnement  |                                             | 1                                                    |        |                                  |                           |   | 1 |   | 2 (minutes)  |   |        |   |   |   |
|                                 |                                                           |                                             |                                                      |        |                                  |                           |   |   |   |              |   |        |   |   |   |
|                                 | Délai de rapport de fermeture de l'état de fonctionnement |                                             | 2                                                    |        |                                  |                           |   | 1 |   | 2 (minutes)  |   |        |   |   |   |
|                                 |                                                           |                                             |                                                      |        |                                  |                           |   |   |   |              |   |        |   |   |   |
|                                 |                                                           | Rapport de période d'état de fonctionnement |                                                      | 3      |                                  |                           |   |   | 1 | 60 (minutes) |   |        |   |   |   |
|                                 |                                                           |                                             |                                                      |        |                                  |                           |   |   |   |              |   |        |   |   |   |

* Valeur de décalage du point de consigne : 0x0064 = 100 = 1,00 ℃.

**Informations sur la vague Z**

\*\*Type d'appareil:\*\*Thermostat

\*\*Type de rôle :\*\*Écoute de l'esclave endormi (LSS)

**Prise en charge/contrôle de classe de commande**

\*\*Support CC obligatoire :\*\*Association CC, v2 ou plus récente

Informations sur le groupe d'association CC

Batterie CC

Réinitialisation de l'appareil localement CC

CC spécifique au fabricant

Niveau de puissance CC

Version CC, v2 ou plus récente

Informations Z-Wave Plus CC

Mode thermostat CC

Point de consigne du thermostat CC

Calendrier CC

4

Capteur CC multiniveau

Heure CC

Métadonnées de mise à jour du micrologiciel CC

État de fonctionnement du thermostat CC

* _**Groupes de Z-Wave (classe de commande d'association version 2)**_

Groupe 1 pour « LifeLine » :

Rapport de batterie CC

Réinitialisation du périphérique localement CC (COMMANDE\_CLASSE\_APPAREIL\_RÉINITIALISER\_LOCALEMENT)

Mode thermostat CC

Point de consigne du thermostat CC

Capteur CC multiniveau

Groupe 2 pour « État de fonctionnement du thermostat »

État de fonctionnement du thermostat CC

* Retour aux paramètres d'usine

Lorsque la vanne de radiateur est réinitialisée aux paramètres d'usine par défaut, elle enverra une réinitialisation locale de l'appareil à tous les nœuds du groupe 1.

5
