# VESTA 172

**Capteur de qualité de l'air (AQS-2-ZW)**

Le capteur de qualité de l'air AQS-2 est un capteur de qualité de l'air intérieur Z-Wave™ qui vise à détecter et surveiller la concentration de CO2. Le capteur de qualité de l'air est compatible uniquement avec la passerelle/panneau de commande Z-Wave. Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance. En profitant du réseau maillé Z-Wave, les commandes peuvent être acheminées vers leur destination via des produits Z-Wave intermédiaires « d’écoute ».

**Identification des pièces**

![](<.gitbook/assets/0 (63).jpeg>)

**1. Bouton de fonction**

\-Appuyez une fois sur le bouton pour envoyer des signaux de niveau de concentration de CO2.

\-Appuyez 3 fois sur le bouton en 1 seconde pour transmettre un code d'apprentissage.

\-Appuyez et maintenez le bouton enfoncé pendant 10 secondes pour effectuer une réinitialisation d'usine.

**2.****Prise CC**

Se connecte à un adaptateur CC 12 V 1 A.

**Caractéristiques**

![](<.gitbook/assets/1 (54).png>)

-   _**Source de courant**_

Le capteur de qualité de l'air est alimenté par une connexion avec une sortie DC 12 V et un adaptateur 1 A. Assurez-vous d'utiliser uniquement un adaptateur avec la tension nominale CA appropriée pour éviter d'endommager les composants, ou utilisez uniquement l'adaptateur secteur CA fourni avec le capteur de qualité de l'air.

Si une panne de courant CA est détectée, le capteur de qualité de l'air enverra un rapport de panne de courant CA au panneau de commande.

![](<.gitbook/assets/2 (59).png>)

-   _**Détection du dioxyde de carbone**_
    -   Le capteur de qualité de l'air mesure la concentration de CO2 toutes les 5 secondes et transmet les données au panneau de commande toutes les 30 minutes. Si la concentration de CO2 change de +/- 100 ppm pendant deux fois consécutives, le capteur de qualité de l'air en informera le panneau de commande.
    -   Si la concentration de CO2 détectée est supérieure à 1 000 ppm, l'AQS-2 enverra un signal d'alarme CO2 au panneau de commande. Si la concentration de CO2 descend en dessous de 1 000 ppm, l'AQS-2 enverra un signal de restauration du CO2 au panneau de commande.
-   _**Ajout d'un appareil (inclusion)**_

![](<.gitbook/assets/3 (60).png>)

Ce produit peut être inclus et utilisé dans n'importe quel réseau Z-Wave avec d'autres appareils certifiés Z-Wave d'autres fabricants et/ou d'autres applications. Tous les nœuds non alimentés par batterie du réseau agiront comme répéteurs, quel que soit le fournisseur, afin d'augmenter la fiabilité du réseau.

-   -   Branchez l'adaptateur secteur ; connectez-le à la prise CC du capteur de qualité de l'air pour le mettre sous tension.
    -   Mettez la passerelle Z-Wave ou le panneau de commande dans**Inclusion**mode (veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
    -   En 1 seconde, appuyez 3 fois sur le bouton de fonction.
    -   Reportez-vous au manuel d'utilisation de la passerelle Z-Wave ou du panneau de commande pour terminer le processus d'inclusion.
    -   Si le capteur a déjà été**ajoutée**(inclus) dans une autre passerelle/panneau de commande Z-Wave, ou si le capteur ne peut pas être ajouté à la passerelle/panneau de commande Z-Wave actuelle, veuillez d'abord l'exclure (voir_**Suppression d'un périphérique**_) avant de tenter de**inclure**dans la passerelle/panneau de configuration Z-Wave actuelle.
-   _**Suppression d'un périphérique (exclusion)**_

![](<.gitbook/assets/4 (59).png>)

Le capteur de qualité de l'air doit être retiré du réseau Z-Wave existant avant d'être inclus dans un autre. Il existe deux méthodes disponibles pour exclure un appareil.

**Mode d'exclusion**

-   Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'exclusion**(veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
-   En 1 seconde, appuyez 3 fois sur le bouton de fonction et l'appareil sera supprimé du réseau Z-Wave.

1

**Retour aux paramètres d'usine**

_(Utilisez la réinitialisation d'usine uniquement lorsque le panneau de configuration/passerelle réseau est manquant ou inutilisable)._

-   Appuyez et maintenez le bouton de fonction pendant 10 secondes pour effectuer une réinitialisation d'usine.

_\\<NOTE>_

-   -   La réinitialisation d'usine de l'appareil le restaurera aux paramètres d'usine par défaut (exclus du réseau Z-Wave). La passerelle ou le panneau de configuration Z-Wave conservera toujours ses paramètres Z-Wave. Veuillez vous référer au manuel de la passerelle ou du panneau de commande pour savoir comment supprimer les paramètres Z-Wave de l'appareil.

![](<.gitbook/assets/5 (59).png>)

**Installation**

![](<.gitbook/assets/6 (40).png>)

-   _**Placer le capteur de qualité de l'air**_

Le capteur de qualité de l'air doit être placé sur une surface plane entourée d'un espace ouvert dans la pièce que vous souhaitez surveiller.

Plus le lieu de placement est ouvert, plus les mesures de la qualité de l’air seront précises.

**Informations sur la vague Z**

**Type générique :**Changer de multiniveau

**Type spécifique :**Couleur réglable à plusieurs niveaux

**ID du type de produit :**0x0004

**Identifiant du produit :**0x0020

**Type de rôle :**Toujours sur esclave (AOS)

**Security:**S2 non authentifié

**Prise en charge/contrôle de classe de commande**

**Support CC obligatoire :**Z-Wave Plus Info CC, V2

Capteur Multiniveau CC, V11 (sécurité 2)

Association CC, V2 (sécurité 2)

Association multicanal CC, V3 (sécurité 2)

Informations sur le groupe d'association CC (sécurité 2)

CC spécifique au fabricant, V2 (sécurité 2)

Service de transport CC, V2

.Version CC, V3 (sécurité 2)

.Réinitialisation de l'appareil localement CC (sécurité 2)

.Niveau de puissance CC (sécurité 2)

.CC de sécurité

Sécurité 2 CC

.Supervision CC

.Mise à jour du firmware MD CC, V4 (sécurité 2)

![](<.gitbook/assets/7 (34).png>)

-   _**Groupes de Z-Wave (classe de commande d'association version 2)**_

L'AQS peut être configuré pour envoyer des rapports aux appareils Z-Wave associés. Il soutient 1 groupe associatif. Groupe 1 pour « LifeLine » : (nœud maximum : 5)

Capteur multiniveau (COMMANDE_CHANGER_MULTINIVEAU, COMMUTATEUR_MULTINIVEAUX_RAPPORT)

Réinitialisation de l'appareil localement

(COMMANDE_CLASSE_APPAREIL_RÉINITIALISER_LOCALEMENT, APPAREIL_RÉINITIALISER_LOCALEMENT_NOTIFICATION)

**Capteur multiniveau :**Au fur et à mesure que les niveaux de CO2 détectent des changements ; l'AQS transmettra la commande à plusieurs niveaux du capteur.

**Retour aux paramètres d'usine:**Lorsque l'AQS a été réinitialisé à l'état par défaut d'usine, il enverra une réinitialisation locale de l'appareil à tous les nœuds du groupe 1.

![](<.gitbook/assets/8 (37).png>)

-   _**Format de données de classe de commande**_
    -   Rapport CO2 :\[COMMANDE_CLASSE_CAPTEUR_MULTINIVEAUX]\[CAPTEUR_MULTINIVEAUX_RAPPORT]
        -   Si le signal CO2 11 02 06 99 est transmis, 0699 peut être visualisé sous la forme 0x0699 en nombre hexadécimal. Vous pouvez convertir l'hexadécimal en décimal pour vérifier la valeur du CO2.

0699=0x0699=1689 ppm

2
