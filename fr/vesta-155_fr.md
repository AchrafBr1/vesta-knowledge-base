# VESTA 155

Module DI/DO (DIO-52-B)

Introduction

DIO-52-B est un module DI/DO qui intègre des appareils filaires dans des réseaux sans fil pour créer des réponses automatisées et améliore la sécurité et la commodité.

Le module DI/DO possède des bornes d'entrée et de sortie numériques intégrées. Il peut être connecté à un seul capteur, interrupteur ou appareil pour recevoir une commande marche/arrêt du panneau de commande via DO et renvoyer l'état actuel via DI au panneau.

Le DIO-52-B peut également être connecté à des appareils séparés. Avec la règle Domotique définie dans le Panel, l'appareil connecté à son point DI peut être transformé en déclencheur d'événements, et son point DO en répondeur d'événements. Lorsque « Mode suiveur d'entrée » est sélectionné dans le panneau de commande, le terminal DO est interconnecté au terminal DI et le dispositif du terminal DO sera activé par le déclencheur du dispositif du terminal DI.

**Le couvercle supérieur****Base**

![](<.gitbook/assets/0 (21).png>)

**Identification des pièces**

1.  **Bouton de test**

Appuyez une fois pour envoyer un code d'apprentissage au panneau de commande.

1.  **Indicateur LED**

Le voyant LED s'allume dans les conditions suivantes :

-   Clignote 6 fois :

Lorsque la borne d'entrée est déclenchée ou lorsque le commutateur transmet un signal.

-   Clignote 3 fois :

Lorsque le terminal de sortie est déclenché.

-   Clignote une fois toutes les 4 secondes :

Les piles sont extrêmement faibles et doivent être remplacées.

1.  **Compartiment à piles**
2.  **Borne d'alimentation**
3.  **Borne d'entrée numérique (DI)**
4.  **Borne de sortie numérique (DO)**

-   Lors de la connexion du fil à chaque borne, veuillez utiliser un mini tournevis cruciforme pour visser/dévisser la borne. Évitez d'utiliser un tournevis à tête plate, car cela pourrait provoquer des éraflures.

1.  **Trous de montage**
2.  **Pinces anti-traction**

Les pinces sont utilisées pour fixer les fils et fournir un soulagement de traction pour protéger les fils des coupures métalliques.

1.  **Trous de câblage**

Caractéristiques

-   _**Source de courant**_

**Alimentation secteur et batterie**

-   Le DIO-52-B peut être alimenté par un adaptateur 5-12 V CC à deux fils lorsqu'il est connecté à la borne d'alimentation, ou il peut être alimenté par trois piles au lithium CR123.
-   Lorsque le terminal d'alimentation et les batteries sont tous deux utilisés, le DIO-52-B s'alimentera uniquement via l'adaptateur.

**Détection de batterie faible**

-   Le DIO-52-B est doté d'une fonction de détection de batterie faible. Lorsque la tension de la batterie est faible, le DIO-52-B transmet un signal de batterie faible pour avertir l'utilisateur. Lors du changement des piles, après avoir retiré les anciennes piles, appuyez deux fois sur le bouton Test pour les décharger complètement avant d'insérer de nouvelles piles.
-   _**Surveillance**_

DIO-52-B transmettra régulièrement un signal de supervision toutes les 30 à 50 minutes pour signaler son état.

-   _Commencer_

1.  Insérez les piles ou connectez l'adaptateur à deux fils 5-12 V CC pour alimenter le DIO-52-B.
2.  Mettez le panneau de commande en mode d'apprentissage, reportez-vous au manuel du panneau de commande pour plus de détails.
3.  Appuyez une fois sur le bouton Test, la LED clignotera 6 fois.
4.  Si le panneau de commande reçoit le signal, il affichera les informations en conséquence, reportez-vous au manuel du panneau de commande pour terminer le processus d'apprentissage.

\\<NOTE>

-   Une fois appris dans le panneau de commande, le DIO-52-B sera reconnu comme 2 appareils distincts (DI et DO), occupant 2 zones dans le panneau.
-   _**Test de marche**_
-   Une fois le DIO-52-B appris, placez le panneau de commande dans (**Test de marche**), maintenez le module DI/DO à l'emplacement souhaité et appuyez sur le bouton Test pour transmettre le signal de test au panneau de commande. Si le panneau de commande se trouve dans la plage de signal DIO-52-B, le panneau affichera les informations DI\\&DO en conséquence.
-   Procédez au montage et à l'installation une fois que vous êtes convaincu que le module DI/DO fonctionne correctement à l'emplacement souhaité.
-   _**Mode de fonctionnement**_

Le module DI/DO peut fonctionner selon différents modes sélectionnés sur la page Web du panneau de commande ou sur le serveur du portail domestique (la fonction de sélection du mode n'est pas disponible dans l'application Vesta Home 5). Veuillez sélectionner le mode dans**FAIRE Modifier l'appareil**page.

| **Page Web du panneau de configuration**                           | **Serveur de portail domestique**                                  |
| ------------------------------------------------------------------ | ------------------------------------------------------------------ |
| <img src=".gitbook/assets/1 (28).png" alt="" data-size="original"> | <img src=".gitbook/assets/2 (33).png" alt="" data-size="original"> |

-   **Contrôle des appareils :**

Lorsque le DIO-52-B est utilisé pour le contrôle de l'appareil, les bornes d'entrée et de sortie sont connectées au même appareil, par ex. un robinet d'eau.

La borne de sortie est utilisée pour recevoir le signal marche/arrêt du panneau de commande pour allumer/éteindre l'appareil connecté, tandis que la borne d'entrée est utilisée pour transmettre l'état actuel de l'appareil connecté au panneau.

Lorsque le mode « Contrôle de l'appareil » est sélectionné, vous pouvez allumer/éteindre à distance l'appareil connecté à partir de la page Web du panneau de commande, du serveur Home Portal ou de l'application Vesta Home 5, mais le paramètre d'entrée de suivi de sortie dans DO sera désactivé. Vous pouvez programmer des règles domotiques, la page Web Scènes sur le panneau ou le serveur de portail domestique pour intégrer l'appareil connecté au DIO-52-B avec d'autres appareils dans le panneau de commande.

![](<.gitbook/assets/3 (29).png>)

Exemple de pratique DI/DO pour le contrôle des appareils :

![](<.gitbook/assets/4 (28).png>)

-   **Appareils séparés :**

Dans ce mode, les bornes d'entrée et de sortie du DIO-52-B sont connectées à des appareils séparés. Le terminal d'entrée est utilisé pour surveiller l'activation de l'appareil connecté et transmettre le signal de déclenchement au panneau de commande. La borne de sortie est utilisée pour recevoir le signal marche/arrêt du panneau de commande pour allumer/éteindre l'appareil connecté.

Lorsque le DIO-52-B fonctionne dans ce mode, le paramètre d'entrée de suivi de sortie dans DO est désactivé. Les utilisateurs peuvent programmer des règles domotiques, la page Web Scènes sur le panneau ou le serveur de portail domestique pour transformer le point DI en déclencheur d'événements et le point DO en répondeur d'événements.

Exemple de pratique DI/DO pour des appareils séparés :

La borne d'entrée DI est connectée à un capteur de fuite d'eau et la sortie DO est connectée à une vanne d'eau. En définissant une règle domotique sur HPS, le panneau éteindra automatiquement la vanne d'eau lorsque le capteur de fuite d'eau sera déclenché.

| **Paramètres DI**                                                  | **Paramètres FAIRE**                                               |
| ------------------------------------------------------------------ | ------------------------------------------------------------------ |
| <img src=".gitbook/assets/5 (20).png" alt="" data-size="original"> | <img src=".gitbook/assets/6 (12).png" alt="" data-size="original"> |

| **Règle domotique**                                               |
| ----------------------------------------------------------------- |
| <img src=".gitbook/assets/7 (9).png" alt="" data-size="original"> |

![](<.gitbook/assets/8 (10).png>)

-   **Suiveur d'entrée :**

Dans ce mode, les bornes d'entrée et de sortie du DIO-52-B sont connectées à des appareils séparés. Le dispositif terminal de sortie est interconnecté au dispositif terminal d'entrée.

Lorsque le périphérique terminal d’entrée est déclenché, le périphérique terminal de sortie s’active en fonction du paramètre Output Follow Input. Veuillez vous référer à la section ci-dessous_**Paramètres DI et DO**_pour plus de détails.

Une fois le mode « Input Follower » sélectionné, la fonction Home Automation Rule & Apply Scene sur Home Portal Server sera désactivée. Vous devrez programmer le**Sortie Suivre Entrée**sur la page DO Device Edit, de sorte que le périphérique du terminal de sortie s'active en conséquence après le déclenchement du périphérique du terminal d'entrée.

Exemple de pratique DI/DO pour Input Follower :

Après avoir sélectionné le mode « Input Follower » sur la page d'édition du périphérique DO, sélectionnez « Latch » pour le paramètre Output Follow Input. Le dispositif terminal de sortie sera activé instantanément lorsque le dispositif terminal d’entrée est déclenché.

![](<.gitbook/assets/9 (10) (1).png>)

![](<.gitbook/assets/10 (4) (1).png>)

-   _**Paramètres DI et DO**_
-   **Borne de sortie (DO) :**

Programmez les paramètres DO dans**FAIRE Modifier l'appareil**sur la page Web du Panel ou sur le serveur du portail d'accueil.

| **Page Web du panneau de configuration**                               | **Serveur de portail domestique**                                       |
| ---------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| <img src=".gitbook/assets/11 (3) (1).png" alt="" data-size="original"> | <img src=".gitbook/assets/12 (1) (1).jpeg" alt="" data-size="original"> |

Allumer via l'application :

-   **Ne fais rien**– Le périphérique de sortie Do ne peut pas être activé via APP.
-   **Ne pas éteindre** - The Do output device will not switch off after being switched on via APP.
-   **Éteindre après 1 à 240 secondes/5 à 30 minutes**– Après avoir été allumé via APP pendant la durée sélectionnée, le périphérique de sortie Do s'éteint.

Statut pour 0 : saisissez la description de l'état 0 pour le terminal de sortie.

Statut pour 1 : saisissez la description de l'état 1 pour le terminal de sortie.

Inverser l'entrée : sélectionnez cette option pour modifier l'ordre de l'état 0 et de l'état 1 pour l'entrée DI. Lorsque « Oui » est sélectionné, l'ordre de l'état 0 et de l'état 1 pour l'entrée DI sera modifié.

Inverser la sortie : sélectionnez cette option pour modifier l'ordre de l'état 0 et de l'état 1 pour la sortie DO. Lorsque « Oui » est sélectionné, l'ordre de l'état 0 et de l'état 1 pour la sortie DO sera modifié.

Entrée de suivi de sortie : Cette fonction est disponible uniquement lorsque le mode de fonctionnement « Suiveur à 3 entrées » est sélectionné.

-   **Non**-Lorsque le périphérique terminal d'entrée est déclenché, le périphérique terminal de sortie ne sera pas activé.
-   **Loquet**-Le dispositif terminal de sortie sera activé instantanément lorsque le dispositif terminal d'entrée est déclenché.
-   **Allumé pendant 10 à 240 secondes/5 à 30 minutes**- Lorsque le périphérique terminal d'entrée est déclenché, le périphérique terminal de sortie sera activé pour une durée définie.

Mode de fonctionnement : sélectionnez le mode de fonctionnement du DIO-52-B. Veuillez vous référer à la section précédente pour plus de détails.

-   **Entrée terminale (DI) :**

Programmez les paramètres DI dans**Modifier le périphérique DI**sur la page Web du Panel ou sur le serveur du portail d'accueil.

| **Page Web du panneau de configuration**                               | **Serveur de portail domestique**                                      |
| ---------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| <img src=".gitbook/assets/13 (3) (1).png" alt="" data-size="original"> | <img src=".gitbook/assets/14 (2) (1).png" alt="" data-size="original"> |

Statut pour 0 : saisissez la description de l'état 0 pour le terminal d'entrée.

Statut pour 1 : saisissez la description de l'état 1 pour le terminal d'entrée.

Installation

Le DIO-52-B peut être déployé sur une surface plane ou monté au mur. Une fois que vous avez terminé le test de marche et que vous êtes convaincu que l'appareil est capable de communiquer avec la centrale d'alarme à l'emplacement choisi, procédez à l'installation.

1.  Débranchez l'alimentation principale.
2.  Desserrez la vis de fixation inférieure et retirez le couvercle supérieur du DIO-52-B.
3.  Utilisez les trous sur la base pour marquer l'emplacement de montage sur le mur.
4.  Percez des trous à l'emplacement marqué et insérez des chevilles murales si nécessaire, vissez la base sur l'emplacement de montage.
5.  Remettez le capot supérieur et serrez la vis de fixation inférieure.
