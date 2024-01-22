# VESTA 170

**PRLM-CH3-AC-ZW Commutateur de relais Z-Wave**

**Introduction**

**PRLM-CH3-AC-ZW est un commutateur de relais Z-Wave à 3 canaux qui peut être connecté à des appareils filaires et réglé sur l'état Normal Ouvert (N.O.). Après avoir rejoint le réseau Z-Wave, le commutateur relais peut être contrôlé via le réseau Z-Wave pour activer les appareils connectés.**

**Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance. En profitant du réseau maillé Z-Wave, les commandes peuvent être acheminées vers leur destination via des produits Z-Wave intermédiaires « d’écoute ».**

**Le relais peut contrôler les nœuds Z-Wave en appuyant simplement sur le bouton de fonction et peut également vous alerter des problèmes de communication.**

**Identification des pièces**

**Le couvercle supérieur****Base**

![](<.gitbook/assets/0 (48).png>)

1.  **Bouton de commutation 1/Bouton de fonction**
    -   **Appuyez sur le bouton 3 fois en 1 seconde pour envoyer un code d'apprentissage.**
    -   **Appuyez et maintenez le bouton enfoncé pendant 10 secondes pour réinitialiser les paramètres d'usine.**
    -   **Appuyez sur le bouton pour allumer/éteindre le canal relais 1.**
2.  **Bouton de commutation 2**
    -   **Appuyez sur le bouton pour allumer/éteindre le canal relais 2.**
3.  **Bouton de commutation 3**
    -   **Appuyez sur le bouton pour allumer/éteindre le canal relais 3.**

![](<.gitbook/assets/1 (53).png>)

-   **REMARQUE>**

**Lorsque le bouton de commutation 2/3 est enfoncé, le canal relais 2/3 passe instantanément à ON/OFF. Lorsque le bouton de commutation 1 est enfoncé, le canal relais 1 passe à ON/OFF après une seconde, car l'appareil doit identifier si la pression sur le bouton est pour allumer/éteindre.**

**ou pour envoyer un code d'apprentissage.**

1.  **Indicateur LED 1**
2.  **Indicateur LED 2**
3.  **Indicateur LED 3**

**Les indicateurs LED 1/2/3 sont utilisés pour indiquer l'état du canal relais 1/2/3 :**

-   **LED 1 marche/arrêt : relais canal 1 marche/arrêt**
-   **LED 2 marche/arrêt : relais canal 2 marche/arrêt**
-   **LED 3 marche/arrêt : relais canal 3 marche/arrêt**

**Lorsqu'elles sont allumées, toutes les LED clignotent séquentiellement pendant 1 cycle.**

**En mode d'apprentissage, toutes les LED clignotent une fois par seconde.**

**Lorsque l'apprentissage est réussi, toutes les LED clignotent rapidement 3 fois.**

**7. Trous de montage**

**1**

**Bornes de connexion**

**Connectez le fil à la borne, serrez la vis pour fermer la tondeuse et maintenez le fil en place. Dévissez pour ouvrir la tondeuse pour retirer le fil connecté à la borne.**

1.  **Ligne (entrée CA)**
2.  **Neutre**
3.  **NON (Canal 1)**

**Pour une connexion normale ouverte avec l'appareil**

1.  **Commun (Canal 1)**
2.  **NON (Canal 2)**

**Pour une connexion normale ouverte avec l'appareil**

1.  **Commun (Canal 2)**
2.  **NON (Canal 3)**

**Pour une connexion normale ouverte avec l'appareil**

1.  **Commun (Canal 3)**
2.  **Pince anti-traction**

**Les pinces sont utilisées pour fixer les fils et fournir un soulagement de traction pour protéger les fils de la découpe métallique.**

**17. Trous de câblage**

**spécification**

**Alimentation : 100 - 240 V CA**

**Courant de charge pris en charge (pour chaque canal de relais) : 5A, 250VAC ou 5A, 30VDC**

**Fil toronné : 14-22 AWG**

**Prudence**

**Tous les travaux sur l'appareil, y compris l'installation et la maintenance, doivent être effectués par un électricien qualifié et agréé.**

**Before installation or any maintenance work, make sure the power supply has been disconnected. Do not connect the device to loads exceeding supported load current.**

**Installation**

**Câblez le relais selon les instructions ci-dessous.**

![](<.gitbook/assets/2 (50).jpeg>)

1.  **Veuillez éteindre l'alimentation avant la connexion.**
2.  **Retirez le capot supérieur et retirez les colliers de serrage.**
3.  **Connectez les bornes L et N de l'alimentation électrique aux bornes de ligne et neutre du PRLM respectivement à travers le trou de câblage.**
4.  **En fonction de l'appareil que vous souhaitez contrôler via le canal relais 1, sélectionnez la borne NO et câblez le canal relais 1 avec l'appareil à travers le trou de câblage pour établir une connexion normale ouverte avec l'appareil.**
5.  **De la même manière qu'à l'étape 4, connectez le canal relais 2/3 à d'autres appareils filaires.**
6.  **Une fois le câblage terminé, remplacez les colliers de serrage et le couvercle supérieur. Allumez l’alimentation pour allumer le commutateur de relais.**

**Caractéristiques**

![](<.gitbook/assets/3 (59).png>)

**Ajout d'un appareil (inclusion)**

**Connect the power input to the Relay Switch according to Installation instruction above and power up the Relay Switch.**

**Mettez la passerelle ou le panneau de commande Z-Wave en mode Inclusion (veuillez vous référer au manuel de la passerelle ou du panneau de commande Z-Wave).**

**Within 1 second, press the Function Button 3 times.**

**2**

**Reportez-vous au manuel d'utilisation de la passerelle Z-Wave ou du panneau de commande pour terminer le processus d'ajout.**

**Si l'appareil a déjà été ajouté (inclus) dans une autre passerelle/panneau de configuration Z-Wave, ou si l'appareil ne peut pas être ajouté à la passerelle/panneau de configuration Z-Wave actuelle, essayez d'abord de le supprimer (voir Suppression de l'appareil).**

**Suppression d'un périphérique (exclusion)**

![](<.gitbook/assets/4 (58).png>)

**L'appareil doit être supprimé du réseau Z-Wave existant avant d'être ajouté à un autre. Mode d'exclusion**

**Mettez la passerelle ou le panneau de commande Z-Wave en mode d'exclusion (veuillez vous référer au manuel de la passerelle ou du panneau de commande Z-Wave).**

**En 1 seconde, appuyez 3 fois sur le bouton de fonction et l'appareil sera supprimé du réseau Z-Wave.**

**La réinitialisation d'usine de l'appareil le restaurera aux paramètres d'usine par défaut (c'est-à-dire qu'il n'est inclus dans aucun réseau Z-Wave). Veuillez utiliser cette procédure uniquement si la passerelle ou le panneau de commande Z-Wave est perdu ou inutilisable.**

**Appuyez et maintenez enfoncé le bouton de fonction de l'appareil pendant 10 secondes pour réinitialiser les paramètres d'usine.**

**Test de portée**

![](<.gitbook/assets/5 (58).png>)

**Pour tester si l'appareil est capable de communiquer avec la passerelle Z-Wave ou le panneau de commande :**

**Mettez la passerelle/le panneau en mode test de portée (Walk Test). Appuyez sur le bouton de fonction de l'appareil**

**La passerelle/le panneau doit afficher si l'appareil se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation de la passerelle/du panneau).**

**Montage**

**After you have finished the range test, and you are satisfied that the device is able to communicate with the Z-Wave gateway in the chosen location, proceed to mounting.**

**Débranchez l'alimentation principale.**

**Desserrez la vis de fixation inférieure et retirez le couvercle supérieur du commutateur relais. Utilisez les trous sur la base pour marquer l'emplacement de montage sur le mur.**

**Percez des trous à l'emplacement marqué et insérez des chevilles murales si nécessaire, vissez la base sur l'emplacement de montage.**

**Remettez le capot supérieur et serrez la vis de fixation inférieure.**

![](<.gitbook/assets/6 (37).jpeg>)

**Operation**

![](<.gitbook/assets/7 (35).jpeg>)

**Contrôle des relais**

**Une fois que le commutateur relais a rejoint avec succès un réseau Z-Wave, la passerelle/panneau de commande peut contrôler à distance le canal relais 1/2/3 pour l'allumer/l'éteindre. Veuillez vous référer à votre passerelle/panneau de commande Z-Wave pour plus de détails.**

**L'utilisateur peut également appuyer manuellement sur le bouton de commutation 1/2/3 pour allumer/éteindre le canal relais 1/2/3.**

**3**

**Informations sur la vague Z**

**Classe d'appareil générique : GÉNÉRIQUE_TAPER_CHANGER_BINAIRE**

**Classe d'appareil spécifique : SPÉCIFIQUE_TAPER_POWER_CHANGER_BINAIRE**

**Type de rôle : Toujours sur esclave (AOS)**

**Clés de sécurité prises en charge : S2_NON AUTHENTIFIÉ**

**Bibliothèque : 232 esclave amélioré**

**Type d'appareil du point final 1 : interrupteur de type générique binaire et interrupteur d'alimentation marche/arrêt de type spécifique**

**Type d'appareil du point final 1 : interrupteur de type générique binaire et interrupteur d'alimentation marche/arrêt de type spécifique**

**Type d'appareil du point final 1 : interrupteur de type générique binaire et interrupteur d'alimentation marche/arrêt de type spécifique**

**Prise en charge/contrôle de classe de commande**

**Classes de commande annoncées dans NIF**

**ZWave Plus Info CC**

**Service de transport CC**

**Spécifique au fabricant CC, V2 (S2)**

**Réinitialisation de l'appareil localement CC (S2)**

**Sécurité_2 CC**

**Niveau de puissance CC (S2)**

**Version CC, V2 (S2)**

**Association CC, V2 (S2)**

**Association multicanal CC, V3 (S2)**

**Informations sur le groupe d'association CC (S2)**

**CC multicanal (S2)**

**Supervision CC**

**Mise à jour du micrologiciel Md CC, V4 (S2)**

**Commutation binaire (S2)**

**Endpoints 123 implémente les classes de commandes suivantes**

**ZWave Plus Info CC**

**Sécurité_2 CC**

**Association CC, V2 (S2)**

**Association multicanal CC, V3 (S2)**

**Informations sur le groupe d'association CC (S2)**

**Supervision CC**

**Commutation binaire (S2)**

**Mappage de classe de commande de base : Binary Switch CC pour les points de terminaison 1, 2 et 3.**

![](<.gitbook/assets/8 (35).png>)

**Z-Wave’s Groups (Association Command Class Version 2)**

| **Périphérique racine :** |                       |                     |                                                                                     |
| ------------------------- | --------------------- | ------------------- | ----------------------------------------------------------------------------------- |
| **IDENTIFIANT**           | **Nom**               | **Nombre de nœuds** | **Description**                                                                     |
| **1**                     | **Corde de sécurité** | **5**               | **Prend en charge les classes de commandes suivantes :**                            |
|                           |                       |                     | **Réinitialisation locale de l'appareil : déclenchée lors de la réinitialisation.** |
|                           |                       |                     | **Switch Binary : déclenché par les points de terminaison**                         |
| **2**                     | **Relais EP 1**       | **5**               | **Miroir du point de terminaison 1, groupe 2**                                      |

![](<.gitbook/assets/9 (35).png>)

**4**

![](<.gitbook/assets/10 (36).png>)

| **3**               | **Relais EP 2**       | **5**               | **Miroir du point de terminaison 2, groupe 2**                |
| ------------------- | --------------------- | ------------------- | ------------------------------------------------------------- |
| **4**               | **Relais EP 3**       | **5**               | **Miroir du point de terminaison 3, groupe 2**                |
| **Point final 1 :** |                       |                     |                                                               |
| **IDENTIFIANT**     | **Nom**               | **Nombre de nœuds** | **Description**                                               |
| **1**               | **Corde de sécurité** | **0**               | **Miroir du périphérique racine, mais sans nombre de nœuds.** |
| **2**               | **Relais EP 1**       | **5**               | **Activer le rapport binaire en cas de surcharge.**           |
| **Point final 2 :** |                       |                     |                                                               |
| **IDENTIFIANT**     | **Nom**               | **Nombre de nœuds** | **Description**                                               |
| **1**               | **Corde de sécurité** | **0**               | **Miroir du périphérique racine, mais sans nombre de nœuds.** |
| **2**               | **Relais EP 2**       | **5**               | **Activer le rapport binaire en cas de surcharge.**           |
| **Point final 3 :** |                       |                     |                                                               |
| **IDENTIFIANT**     | **Nom**               | **Nombre de nœuds** | **Description**                                               |
| **1**               | **Corde de sécurité** | **0**               | **Miroir du périphérique racine, mais sans nombre de nœuds.** |
| **2**               | **Relais EP 3**       | **5**               | **Activer le rapport binaire en cas de surcharge.**           |

![](<.gitbook/assets/11 (27).png>)![](<.gitbook/assets/12 (30).png>)![](<.gitbook/assets/13 (24).png>)![](<.gitbook/assets/14 (18).png>)

**5**
