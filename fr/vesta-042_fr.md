# VESTA 042

PSM-29ZW/PSS-29ZW

Série de commutateurs d'alimentation

Introduction

La série Power Switch comprend les modèles suivants :

**PSS-29ZW :**Interrupteur d'alimentation Z-Wave avec fonction routeur

**PSM-29ZW :**Interrupteur d'alimentation Z-Wave avec fonction compteur et fonction routeur

Les interrupteurs d'alimentation compatibles Z-Wave sont capables de recevoir des signaux sans fil du coordinateur du réseau Z-Wave pour activer/désactiver les appareils qui y sont connectés. Le Power Switch sert également de routeur dans le réseau Z-Wave. Après avoir été inclus dans le réseau Z-Wave, il permet à d'autres appareils Z-Wave de rejoindre le réseau via l'interrupteur d'alimentation.

L'interrupteur d'alimentation avec fonction de compteur (PSM-29ZW) a la fonctionnalité supplémentaire de suivre la consommation d'énergie grâce au compteur d'énergie intégré et de transmettre régulièrement les données au coordinateur.

Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance. En profitant du réseau maillé Z-Wave, les commandes peuvent être transmises vers leur destination via des produits Z-Wave intermédiaires « d’écoute ».

Les commutateurs d'alimentation Z-Wave permettent d'accéder à la classe « S2 non authentifié » et prennent en charge l'inclusion Z-Wave SmartStart ainsi que l'inclusion classique.

Identification des pièces

1.Bouton de fonction ou indicateur LED

Le bouton de fonction sert également d'indicateur LED. Le bouton de fonction est utilisé pour contrôler l’interrupteur d’alimentation. L'indicateur LED est utilisé pour indiquer l'état de l'interrupteur d'alimentation.

**Indication LED :**

Le voyant LED s'allume dans les conditions suivantes :

-   Allumé : sous tension
-   Éteint : mise hors tension
-   Le voyant rouge clignote deux fois :

1.L'interrupteur d'alimentation vient d'être allumé.

2.L'interrupteur d'alimentation vient d'être réinitialisé aux paramètres d'usine.

**Utilisation du bouton de fonction :**

-   Appuyez sur le bouton de fonction pour allumer/éteindre l'interrupteur d'alimentation.
-   Appuyez sur le bouton de fonction 3 fois en 1,5 seconde pour transmettre un code d'apprentissage.
-   Appuyez et maintenez enfoncé le bouton de fonction pendant 10 secondes pour réinitialiser les paramètres d'usine.

| _Tapez F_                                                          | _Type J_                                                                                                                                                                                               | _Tapez B_ | _Type E_ | _Type G_ |
| ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | -------- | -------- |
| <img src=".gitbook/assets/0 (12).png" alt="" data-size="original"> | <img src=".gitbook/assets/1 (16).png" alt="" data-size="original"><img src=".gitbook/assets/2 (19).png" alt="" data-size="original"><img src=".gitbook/assets/3 (18).png" alt="" data-size="original"> |           |          |          |

**Caractéristiques**

-   _**Ajout d'un appareil (inclusion)**_

Ce produit peut être inclus et utilisé dans n'importe quel réseau Z-Wave avec d'autres appareils certifiés Z-Wave d'autres fabricants et/ou d'autres applications. Tous les nœuds non alimentés par batterie du réseau agiront comme répéteurs, quel que soit le fournisseur, afin d'augmenter la fiabilité du réseau.

L'appareil prend en charge à la fois le processus d'inclusion classique et le processus d'inclusion SmartStart.

**Inclusion classique**

-   Branchez l'interrupteur d'alimentation sur une prise de courant.
-   Mettez la passerelle Z-Wave ou le panneau de commande dans**Inclusion****mode**(veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
-   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction.
-   Reportez-vous au manuel d'utilisation de la passerelle Z-Wave ou du panneau de commande pour terminer le processus d'ajout.
-   Si l'appareil a déjà été ajouté (inclus) dans une autre passerelle/panneau de configuration Z-Wave, ou si l'appareil ne peut pas être ajouté à la passerelle/panneau de configuration Z-Wave actuelle, veuillez d'abord l'exclure (voir_**Suppression d'un périphérique**_) avant de tenter de**inclure**dans la passerelle/panneau de configuration Z-Wave actuelle.

**Inclusion de SmartStart**

![](<.gitbook/assets/4 (17).png>)Z-Wave SmartStart utilise le DSK de l'appareil pour améliorer et simplifier le processus d'inclusion. DSK est une clé spécifique à l'appareil utilisée pour l'authentification. Les informations DSK sont stockées au format QR code imprimé sur un autocollant et attaché à l'appareil.

-   Scannez l'autocollant QR Code sur l'interrupteur d'alimentation pour obtenir le DSK et le transférer vers la passerelle Z-Wave.
-   Branchez l'interrupteur d'alimentation sur une prise de courant, une demande d'inclusion SmartStart sera automatiquement envoyée à la passerelle.
-   La passerelle inclura automatiquement l'appareil lors de la reconnaissance de l'appareil en faisant correspondre la demande d'inclusion avec le DSK obtenu

&lt;REMARQUE>

-   Le DSK de l'appareil n'est utilisé que lors de l'inclusion.
-   Le DSK peut être lu sans que l'interrupteur d'alimentation soit allumé, il est donc possible de préparer la passerelle pour inclure l'appareil avant de mettre l'interrupteur d'alimentation sous tension.
-   _**Suppression d'un périphérique (exclusion)**_

L'appareil doit être supprimé du réseau Z-Wave existant avant d'être inclus dans un autre. Il existe deux méthodes disponibles pour exclure un appareil.

**Mode d'exclusion**

-   Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'exclusion**(veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
-   Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton de fonction et l'appareil sera supprimé du réseau Z-Wave.

**Retour aux paramètres d'usine**

_(Utilisez la réinitialisation d'usine uniquement lorsque le panneau de configuration/passerelle réseau est manquant ou inutilisable)._

-   Appuyez et maintenez enfoncé le bouton de fonction de l'appareil pendant 10 secondes pour réinitialiser les paramètres d'usine.

\\<NOTE>

-   La réinitialisation d'usine de l'appareil le restaurera aux paramètres d'usine par défaut (exclus du réseau Z-Wave). La passerelle ou le panneau de configuration Z-Wave conservera toujours ses paramètres Z-Wave. Veuillez vous référer au manuel de la passerelle ou du panneau de commande pour savoir comment supprimer les paramètres Z-Wave de l'appareil.
-   La réinitialisation d'usine de l'appareil effacera également toutes les données d'alimentation accumulées.
-   Avant de retirer ou de réinitialiser l'interrupteur d'alimentation aux paramètres d'usine, veuillez vous assurer que les informations DSK de l'appareil ont été supprimées ou n'existent pas dans la passerelle. Si vous supprimez ou réinitialisez l'appareil aux paramètres d'usine, mais que son DSK existe toujours dans la passerelle, la passerelle inclura automatiquement à nouveau l'appareil.
-   _Test de portée_

Pour tester si l'appareil est capable de communiquer avec la passerelle Z-Wave ou le panneau de commande :

-   Mettez la passerelle/le panneau en mode test de portée (Walk Test).
-   Appuyez sur le bouton de fonction de l'appareil.
-   La passerelle/panneau doit s'afficher si l'appareil se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation de la passerelle/panneau).
-   _Capacité du périphérique du routeur Z-Wave_

L'interrupteur d'alimentation permet à d'autres appareils Z-Wave de rejoindre le réseau Z-Wave via le routeur. La capacité maximale des appareils pouvant rejoindre le réseau Z-Wave via le commutateur d'alimentation est de 255.

Opération

-   _**Contrôle des appareils**_
-   Après avoir été inclus dans une passerelle ou un panneau de commande Z-Wave, branchez un appareil électroménager sur l'interrupteur d'alimentation. Les données de consommation d’énergie et d’énergie de cet appareil électroménager seront transférées au panneau de commande.
-   Les utilisateurs peuvent allumer/éteindre l'appareil électrique à distance via le panneau de commande (veuillez vous référer au manuel de votre panneau de commande).
-   Appuyer sur le bouton de fonction de l'interrupteur d'alimentation peut également allumer/éteindre l'interrupteur d'alimentation.
-   L'interrupteur d'alimentation transmet un signal avec des données d'alimentation à la passerelle/au panneau Z-Wave toutes les 10 minutes à partir de la dernière transmission d'un signal.
-   Lorsque l'interrupteur d'alimentation est rebranché après avoir été retiré de la prise de courant, l'état marche/arrêt précédent de l'interrupteur d'alimentation reprendra immédiatement.
-   _**Moniteur de consommation d'énergie (PSM-29ZW uniquement)**_
-   Si la puissance de sortie est inférieure à 1 kW, le PSM-29 transmettra un signal à la passerelle/au panneau Z-Wave lorsque la puissance dévie de +/- 2 W pour mettre à jour les informations de puissance du PSM-29.
-   Si la puissance de sortie est supérieure à 1 kW, le PSM-29 transmettra un signal à la passerelle/au panneau Z-Wave lorsque la puissance dévie de +/- 5 W pour mettre à jour les informations de puissance du PSM-29.
-   L'interrupteur d'alimentation transmet un signal avec des données d'alimentation à la passerelle/au panneau Z-Wave chaque fois que la consommation d'énergie augmente de 0,1 kW/h.
-   Lorsque la puissance est inférieure à 20 W, une erreur de mesure est plus susceptible de se produire.
-   _**Spécification de puissance**_
-   Pour**110V :**la charge de fonctionnement maximale est de 1760 W et 16 A. Attention : veuillez ne pas dépasser la charge maximale.
-   Pour**230V :**la charge de fonctionnement maximale est de 3680 W et 16 A. Attention : veuillez ne pas dépasser la charge maximale.
-   Si l'interrupteur d'alimentation surchauffe, il coupera automatiquement l'alimentation par mesure de sécurité. L'interrupteur d'alimentation doit être débranché et rebranché après la coupure pour reprendre un fonctionnement normal.
-   _**Informations sur la vague Z**_

**Type d'appareil:**Interrupteur marche/arrêt

**Type de rôle :**Toujours sur esclave (AOS)

**Prise en charge/contrôle de classe de commande**

**Prise en charge CC obligatoire :**Association CC, v2 ou plus récente

Informations sur le groupe d'association CC

Compteur CC, v2

CC de base

Commutateur binaire CC

Réinitialisation de l'appareil localement CC

CC spécifique au fabricant

Niveau de puissance CC

Version CC, v2 ou plus récente

Informations Z-Wave Plus CC

**Prise en charge CC recommandée :**Métadonnées de mise à jour du micrologiciel CC

-   _**Groupes de Z-Wave (classe de commande d'association version 2)**_

Le commutateur peut être configuré pour envoyer des rapports aux appareils Z-Wave associés. Il prend en charge un groupe d'association avec cinq nœuds pour le groupe 1. Pour le groupe 1, le commutateur signalera son dernier état à la passerelle/au panneau Z-Wave.

Le groupe 1 comprend :

Commutateur binaire CC (COMMUTATEUR_BINAIRE_RAPPORT)

Compteur CC, v2 (METRE_RAPPORT_COMMANDE)

Réinitialisation du périphérique localement CC (COMMANDE_CLASSE_APPAREIL_RÉINITIALISER_LOCALEMENT)

-   Rapport automatique au groupe 1 (nœud maximum 5)
-   Rapport d'événement marche/arrêt

Lors du basculement entre On/Off, il enverra un rapport de commutation binaire aux nœuds du groupe 1.

-   Retour aux paramètres d'usine

Lorsque l'interrupteur d'alimentation est réinitialisé aux paramètres d'usine par défaut, il enverra une réinitialisation locale de l'appareil à tous les nœuds du groupe 1.
