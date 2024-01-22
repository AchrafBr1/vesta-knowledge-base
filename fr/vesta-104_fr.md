# VESTA 104

-   Thermostat (série TMST-15ZW)
-   Introduction

TMST-15ZW est un thermostat alimenté par batterie. Il est conçu pour être intégré au système de chauffage et de refroidissement domestique pour le contrôle de l’environnement domestique. Le thermostat peut être utilisé manuellement à l'aide de l'écran LCD et des boutons, ou accessible à distance via le coordinateur Z-Wave. Il propose des modes de refroidissement et de chauffage avec point de consigne de température et programmation automatique pour vous permettre de contrôler facilement votre environnement domestique.

-   ![](<.gitbook/assets/0 (14).jpeg>)Identification des pièces

**1. Écran LCD**

L'écran LCD affiche les informations suivantes :

![](<.gitbook/assets/1 (21).png>)

1.  Icône du mode Chauffage : Lorsqu'il est affiché, le thermostat est en mode Chauffage.
2.  Icône du mode Refroidissement : Lorsqu'il est affiché, le thermostat est en mode Refroidissement.
3.  Icône de niveau de batterie : affichée uniquement lorsque le niveau de batterie est à 25 %, 50 % et 75 %. L'icône disparaîtra lorsque le niveau de la batterie sera inférieur à 15 %.
4.  Connectivité réseau Z-Wave :

Lorsqu'il est affiché, il indique que le thermostat n'est encore appris dans aucune passerelle/panneau, ou lorsque l'appareil perd la connexion au réseau Z-Wave actuel.

1.  Mode : sélection du mode, mode à distance et décalage
2.  Programme : Le thermostat exécutera le réglage du programme programmé.
3.  Lecture de température/point de consigne

**2. Bouton Bas (-).**

\-Appuyez sur le bouton et l'écran LCD affichera le point de consigne actuel, le mode et le réglage pendant 5 secondes. Dans les 5 secondes, appuyez sur le bouton Bas (-) pour diminuer le point de consigne.

\-Appuyez et maintenez pendant 3 secondes pour accéder au mode de programmation.

**3. Bouton Haut (+)**

\-Appuyez sur le bouton et l'écran LCD affichera le point de consigne actuel, le mode et le réglage pendant 5 secondes. Dans les 5 secondes, appuyez sur le bouton UP (+) pour augmenter le point de consigne.

\-Appuyez 3 fois en 1,5 seconde pour transmettre le code d'apprentissage, et « Joi NET » s'affichera sur l'écran LCD.

![](<.gitbook/assets/2 (25).png>)

**4. Trou de montage mural**

**5. Compartiment à piles**

Insérez 2 piles alcalines AA.

**6. Bornes de relais (retirez le couvercle du relais pour accéder)**

Bornes de relais 230V 5A NO/COM/NC.

Connectez-vous au système de chauffage/refroidissement de la maison.

**Caractéristiques**

-   _Détection de batterie et de batterie faible_

Le thermostat utilise 2 piles alcalines AA comme source d'alimentation. Le capteur signalera son pourcentage de batterie à la passerelle/au panneau de commande respectivement à 100 % (0x64), 75 % (0x4B), 50 % (0x32) et 25 % (0x19). Lorsque le niveau de la batterie est inférieur à 15 %, le capteur enverra 0xFF à la passerelle/au panneau de commande.

-   _Contrôle des relais_

Le thermostat contrôle le système de chauffage/refroidissement de la maison via un contrôle de relais. Ouvrez et retournez le couvercle arrière, retirez le couvercle interne du relais pour révéler les bornes de câblage. Lors du câblage du thermostat, faites passer le câble à travers l’ouverture centrale du couvercle arrière.

![](<.gitbook/assets/3 (4) (1).jpeg>)

-   _**Contrôle des modes**_

Le thermostat dispose de deux modes de fonctionnement : le mode local et le mode programmé.

-   **Mode local:**

Le mode local permet de régler la fonction Chauffage/Refroidissement du thermostat et les points de consigne à l'aide des boutons du thermostat.

-   **Mode programmé :**

Le mode programmé permet le mode Thermostat et le contrôle du point de consigne via la passerelle une fois l'apprentissage terminé.

Pour changer le mode de fonctionnement, veuillez vous référer à «_Mode de programmation_» pour plus de détails.

-   _**Chauffage/refroidissement et contrôle des points de consigne**_

Le thermostat de chauffage/refroidissement et le point de consigne ne peuvent être réglés localement que lorsque le thermostat est réglé en mode Local.

En mode local, appuyez sur la touche**EN HAUT**(**+**) ou**Vers le bas (-)**bouton pour régler le point de consigne.

En mode programmé, utilisez la passerelle/le panneau de commande pour régler le point de consigne à distance.

Plage de consigne de chaleur : 9°C~30°C.

Plage de consigne de refroidissement : 11°C~32°C

-   _**Télécommande**_

Une fois que le thermostat a rejoint un réseau Z-Wave, vous pouvez contrôler le thermostat via un coordinateur de réseau Z-Wave ou une passerelle. Veuillez vous référer au manuel de votre coordinateur/passerelle Z-Wave pour plus d'informations.

Les fonctions suivantes sont uniquement disponibles pour le réglage via le coordinateur et la passerelle Z-Wave :

-   **Calendrier:**

Vous pouvez uniquement programmer la configuration du calendrier via le coordinateur/passerelle du réseau Z-Wave.

Paramétrage des horaires : jusqu'à 5 horaires peuvent être programmés pour chaque jour de la semaine avec le mode, le point de consigne et l'heure de début.

Contrôle du calendrier :

Normal - Le thermostat exécutera le réglage de la programmation programmée en conséquence.

Maintenir – Le thermostat contournera le programme actuellement programmé et exécutera le programme suivant lorsqu'il commencera.

Aucun programme – Le thermostat n'exécutera aucun programme défini jusqu'à ce qu'il soit à nouveau réglé sur Normal.

-   _**Détection de température**_
-   Le thermostat dispose de capteurs de température intégrés et affichera la température sur l'écran LCD.
-   Le thermostat transmettra régulièrement des signaux de température en fonction du réglage. L'intervalle par défaut est de 5 minutes.
-   Vous pouvez également appuyer une fois sur le bouton réseau Z-Wave pour transmettre manuellement un signal de température.
-   _**Mode veille Z-Wave**_
-   Le thermostat entrera en mode veille Z-Wave (pour économiser l'énergie) après une courte période de réveil. En mode veille Z-wave, les passerelles ou panneaux de commande Z-Wave ne peuvent pas envoyer de commandes au thermostat.
-   _**Mode de programmation**_

**Étape 1.**Appuyez et maintenez enfoncé le bouton Bas (-) pendant 3 secondes pour accéder au mode de programmation.

**Étape 2.**Il y a 3 fonctions disponibles pour la programmation, y compris les fonctions du thermostat, le contrôle du relais à distance et le point de consigne.

Compenser. Vous pouvez appuyer sur le bouton HAUT (+) ou Bas (-) pour changer de mode.

**Étape 3.**Une fois la sélection terminée, attendez quelques secondes que le thermostat passe dans le mode sélectionné.

**Fonctions du thermostat (chauffage et refroidissement) :**

Dans ce mode, « Pro Mod » sera affiché sur l'écran LCD.

![](<.gitbook/assets/4 (22).png>)

Les modes de chauffage/refroidissement sont disponibles pour la sélection. Appuyez sur le bouton HAUT (+) pour sélectionner Chauffage et sur le bouton Bas (-) pour sélectionner Refroidissement.

Chauffage Refroidissement

![](<.gitbook/assets/5 (15).png>)

Une fois la sélection terminée, attendez quelques secondes que le thermostat quitte automatiquement le mode de réglage. Le thermostat entrera dans le dernier mode sélectionné.

**Contrôle du relais à distance :**

Dans ce mode, « Pro RM » s'affichera sur l'écran LCD.

Le mode télécommande vous permet de contrôler le relais à distance via le panneau de commande lorsque la fonction est activée. Le thermostat ne contrôlera pas le relais local en mode distant.

![](<.gitbook/assets/6 (10).png>)

-   Si le mode à distance est désactivé, « dS RM » s'affichera sur l'écran LCD.
-   Si le mode à distance est activé, « En RM » s'affichera sur l'écran LCD.

![](<.gitbook/assets/7 (7) (1).png>)

**Décalage du point de consigne :**

Dans ce mode, « Pro OFS » s'affichera sur l'écran LCD. La fonction Setpoint Offset vous permet de compenser l’écart. Pour calculer le décalage du point de consigne, soustrayez simplement la température ambiante à la température de l'appareil. En mode local, appuyez et maintenez le bouton Bas (-) pendant 3 secondes pour accéder au mode de programmation. Une fois la sélection terminée, attendez quelques secondes que le thermostat passe en sélection de mode.

![](<.gitbook/assets/8 (7) (1).png>)

Par exemple : Si la température de l'appareil est de 20 °C et la température ambiante de 18 °C, alors décalage du point de consigne = 18 – 20 = -2 °C.

Une fois le décalage du point de consigne appliqué, l'appareil fonctionnera en fonction de la température ajustée.

Par exemple : Si la température de l'appareil est de 20 °C et que le décalage du point de consigne est de -2 °C, l'appareil fonctionnera en utilisant 18 °C comme référence réelle.

-   _**Ajout d'un appareil (inclusion)**_

Ce produit peut être inclus et utilisé dans n'importe quel réseau Z-Wave avec d'autres appareils certifiés Z-Wave d'autres fabricants et/ou d'autres applications. Tous les nœuds non alimentés par batterie du réseau agiront comme répéteurs, quel que soit le fournisseur, afin d'augmenter la fiabilité du réseau.

-   Insérez deux piles alcalines AA dans le compartiment à piles.
-   Mettez le panneau de commande Z-Wave en mode Inclusion (veuillez vous référer au manuel du panneau de commande Z-Wave).
-   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton Haut (+) pour transmettre le code d'apprentissage, et « Joi NET » s'affichera sur l'écran LCD. Si le thermostat rejoint avec succès un réseau, l'icône de connexion Z-Wave disparaîtra sur l'écran LCD.
-   Reportez-vous au manuel d'utilisation de la passerelle Z-Wave ou du panneau de commande pour terminer le processus d'ajout.
-   Si l'appareil a déjà été ajouté (inclus) dans une autre passerelle/panneau de configuration Z-Wave, ou si l'appareil ne peut pas être ajouté à la passerelle/panneau de configuration Z-Wave actuelle, essayez d'abord de le supprimer (voir Suppression de l'appareil).
-   _**Suppression d'un périphérique (exclusion)**_

L'appareil doit être supprimé du réseau Z-Wave existant avant d'être ajouté à un autre.

**Mode d'exclusion :**

-   Mettez la passerelle Z-Wave ou le panneau de commande en mode Exclusion (veuillez vous référer au manuel du Z-Wave ou du panneau de commande).
-   Dans les 1,5 secondes, appuyez 3 fois sur le bouton Haut (+) et l'appareil sera supprimé du réseau Z-Wave. Si le thermostat est supprimé avec succès du réseau, l'icône de connexion Z-Wave apparaîtra sur l'écran LCD.

**Retour aux paramètres d'usine**

La réinitialisation d'usine de l'appareil le restaurera aux paramètres d'usine par défaut (c'est-à-dire qu'il n'est inclus dans aucun réseau Z-Wave). Veuillez utiliser cette procédure uniquement si la passerelle ou le panneau de commande Z-Wave est perdu ou inutilisable.

-   Appuyez et maintenez enfoncé le bouton Haut (+) de l'appareil pendant 10 secondes pour réinitialiser les paramètres d'usine.
-   _**Installation**_

Le thermostat est conçu pour être fixé au mur à l’aide des trous de montage situés sur le capot arrière.

1.  Avant le montage, assurez-vous d'abord de terminer le câblage du relais par l'ouverture sur le couvercle arrière.
2.  Utilisez les trous de montage sur le capot arrière comme modèle pour marquer l'emplacement de montage sur le mur.
3.  Percez des trous dans le mur et insérez une cheville murale si nécessaire, vissez le couvercle arrière sur l'emplacement de montage.
4.  Placez le corps principal du thermostat sur le capot arrière, l'installation est terminée.

**Informations sur la vague Z**

**Type d'appareil:**Thermostat

**Type de rôle :**Signalement de l'esclave endormi (RSS)

**Prise en charge/contrôle de classe de commande**

**Prise en charge CC obligatoire :**Association CC, v2

Informations sur le groupe d'association CC

Batterie CC

Réinitialisation de l'appareil localement CC

CC spécifique au fabricant, v2

VersionCC, v2

Niveau de puissance CC

Z-Wave Plus Info CC, v2

Association multicanal CC, v2

Réveil CC

Supervision CC

Mode Thermostat CC, v3

Point de consigne du thermostat CC, v3

État de fonctionnement du thermostat CC

Capteur CC multiniveau

Mise à jour du micrologiciel CC, v2 (version OTA uniquement)

_**Groupes Z-Wave (classe de commande d'association version 2)**_

Groupe 1 pour « LifeLine » :

Batterie CC (COMMANDE_CLASSE_BASIQUE)

Réinitialisation de l'appareil localement CC

Mode Thermostat CC, V3

Point de consigne du thermostat CC, V3

État de fonctionnement du thermostat CC

Capteur CC multiniveau

Groupe 2 pour l'état de fonctionnement du thermostat :

État de fonctionnement du thermostat CC
