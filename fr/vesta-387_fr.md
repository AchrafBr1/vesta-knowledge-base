# VESTA 387

**Module d'alimentation auxiliaire (PWB-1-BUS)**

**Introduction**

Le PWB-1-BUS est un module d'alimentation auxiliaire qui peut être connecté au système BUS de données pour fournir une alimentation maximale de 13,5 V, 5 A aux appareils BUS connectés. Le module PWB-1-BUS est supervisé et communique au panneau tous les changements d'état, y compris l'état de l'alimentation secteur, le niveau de la batterie, l'état de l'autoprotection et les données de consommation d'énergie.

**Identifier les pièces**

![](<.gitbook/assets/0 (4).jpeg>)

1.  **Bornes de connexion BUS au dispositif BUS alimenté**(4 fils : V, G, A, B)
2.  **Bornes de connexion BUS au dispositif BUS alimenté**(4 fils : V, G, A, B)
3.  **Bornes de connexion BUS au panneau hybride**(3 fils : G, A, B)
4.  **Coupe-batterie**

Faites glisser l'interrupteur de la batterie sur la position ON, de sorte que la batterie de secours soit chargée lorsque l'alimentation secteur est connectée et serve de source d'alimentation de secours lorsque l'alimentation secteur est manquante.

1.  **Terminal de la batterie**

Se connecte à une batterie de secours (une batterie au plomb scellée 12 V 7,0 Ah ou 12 V 17,2 Ah).

1.  **Trous de montage**
2.  **Borne d'alimentation**

Se connecte à une alimentation 20 V CA 50 Hz/60 Hz, 4 A (80 VA).

1.  **Cavalier de résistance de borne (J3)**

Lorsque le module d'alimentation est connecté à la ligne BUS en tant que périphérique BUS le plus éloigné du panneau hybride, veuillez régler les cavaliers de résistance terminale du module d'alimentation et du panneau hybride sur ON. La capacité de communication de la ligne BUS sera améliorée.

-   -   Le cavalier de résistance terminale du PWB-1-BUS est généralement utilisé lorsque le module d'alimentation est connecté pour la première fois au panneau hybride sans aucun périphérique BUS alimenté connecté.

Vous pouvez régler le cavalier de résistance terminale du module d'alimentation et le cavalier de résistance terminale du panneau hybride sur ON pour tester si le PWB-1-BUS peut bien communiquer avec le panneau.

Si la communication avec le panneau est testée correctement, vous pouvez commencer à connecter le PWB-1-BUS aux appareils alimentés. Ensuite, veuillez désactiver le cavalier de résistance terminale du module d'alimentation et régler à la place le cavalier de résistance terminale de l'appareil le plus éloigné de la ligne BUS.

![](<.gitbook/assets/1 (6).jpeg>)

Si le cavalier est désactivé (le lien du cavalier est retiré ou « garé » sur une broche), la capacité de communication est au niveau normal.

![](<.gitbook/assets/2 (5).jpeg>)

Si le cavalier est activé (le lien du cavalier repose sur les deux broches), la capacité de communication est améliorée.

1

1.  **Indicateur LED**
2.  **Borne de sécurité**Se connecte au commutateur d'autoprotection du couvercle.

**Accessoires**

1.  Impasse\*4
2.  Écrou d'écartement\*4
3.  Câble de batterie 12 V 7,0 Ah\*2 (+, -)

**Source de courant**

**Source d'énergie:**

-   Le PWB-1-BUS est connecté à une alimentation 20 V CA 50 Hz/60 Hz, 4 A (80 VA).
-   Lorsque l'alimentation est interrompue et rétablie, le PWB-1-BUS transmettra respectivement le signal de panne CA et de restauration.

**Batterie rechargeable:**

-   Une batterie au plomb scellée 12 V 7,0 Ah ou 12 V 17,2 Ah peut être connectée pour servir de secours en cas de panne de courant.
-   Pendant le fonctionnement normal, l'alimentation secteur est utilisée pour alimenter le PWB-1-BUS et en même temps recharger la batterie. Il faut environ 48 heures pour charger complètement une batterie 12 V 7,0 Ah et 72 heures pour charger complètement une batterie 12 V 17,2 Ah.
-   Si l'interrupteur de la batterie est réglé sur OFF, la batterie ne sera pas chargée lorsque l'alimentation secteur est connectée et elle ne servira pas non plus de source d'alimentation de secours en cas d'absence d'alimentation secteur. Vous devez changer la batterie**SUR**pour qu'il soit chargé lorsque l'alimentation secteur est connectée et serve de source d'alimentation de secours lorsque l'alimentation secteur est manquante.
-   Lorsque la batterie est faible, le PWB-1-BUS transmettra un signal de batterie faible. Lorsque la batterie est chargée, le PWB-1-BUS transmettra le signal de restauration de la batterie.
-   Lorsque la batterie est déconnectée, l'interrupteur de la batterie est éteint ou une panne de batterie est détectée, le PWB-1-BUS signalera la batterie manquante/déchargée au panneau de commande.

**Puissance de sortie :**

-   Le PWB-1-BUS peut fournir une alimentation maximale de 13,5 V, 5 A aux appareils BUS connectés.

**Autoprotection**

-   L'interrupteur anti-sabotage de la porte du boîtier est en position normale lorsque la porte est fermée. Une violation du sabotage se produit lorsque la porte est ouverte à l'endroit où l'interrupteur de sabotage est relâché (tamper ouvert). Un signal d’auto-ouverture sera signalé au panneau de commande.

**Connexion aux appareils Panel et BUS**

**PRUDENCE:**

**Coupez toute alimentation (AC et batterie) avant d’effectuer des connexions. Le câblage du système d’alarme ne doit être effectué que par un technicien certifié possédant les connaissances et la formation appropriées en matière d’équipement électrique.**

-   Pour faciliter les connexions des câbles, les borniers de chaque module du système BUS sont codés par couleur.

**Codes couleurs du bornier**

| **Rouge** | VDD  |
| --------- | ---- |
| **Noir**  | GND  |
| **Jaune** | 485A |
| **Vert**  | 485B |

-   Lors de la connexion du PWB-1-BUS au panneau hybride, connectez uniquement les trois bornes (GND, 485A, 485B). Veuillez vous référer à l'image ci-dessous.
-   Lors de la connexion du PWB-1-BUS aux appareils alimentés par le module d'alimentation, veuillez connecter 4 bornes. (VDD, GND, 485A, 485B).

Veuillez vous référer aux exemples de connexion de périphériques BUS (VST-892-BUS et DC-23-BUS) ci-dessous.

2

![](<.gitbook/assets/3 (5).jpeg>)

_\\<NOTE>_

-   La conception enfichable des borniers BUS améliore l'efficacité de l'installation. Avant le câblage, vous pouvez retirer les borniers de l'appareil pour faciliter l'utilisation et les rebrancher après le câblage.

Lors de la réinstallation des borniers sur la carte, assurez-vous de les installer dans la même direction pour éviter les dangers potentiels.

-   Des connexions incorrectes entraîneront une panne ou un mauvais fonctionnement. Inspectez le câblage et assurez-vous que les connexions sont correctes avant de mettre sous tension.

**Commencer**

Après avoir connecté le module d'alimentation auxiliaire au panneau hybride (veuillez vous référer à_**Connexion aux appareils Panel et BUS**_pour plus de détails), veuillez passer à l'apprentissage.

-   _**Apprentissage**_

**Étape 1.**Une fois le PWB-1-BUS connecté au panneau hybride, allumez le panneau de commande.

**Étape 2.**Sur la page Web du Panneau de configuration, cliquez sur «**Apprentissage**» pour accéder à la page d'apprentissage.

**Étape 3.**Cliquer sur "**Commencer**» pour passer en mode apprentissage.

**Étape 4.**Cliquez sur**"Ajouter"**pour inclure le module d'alimentation auxiliaire dans le panneau.

**Étape 5.**Si le module d'alimentation auxiliaire est correctement appris dans le système, le périphérique ajouté sera affiché dans la section « Périphérique appris ». Le type de périphérique sera affiché comme « PWB ».

-   _**Identification**_

Le "**Identifier**La fonction " est utilisée pour localiser un périphérique BUS spécifique dans le système filaire BUS. Cette fonction est utile pour distinguer quel appareil est quel appareil, en particulier dans une grande installation où de nombreux appareils BUS sont inclus.

Pour localiser PWB-1-BUS dans le système BUS :

![](<.gitbook/assets/4 (4).png>)

**Étape 1.**Sur la page Web de Hybrid Panel, cliquez sur « Identifier » sous la liste des appareils après l'entrée dans la colonne des appareils de PWB.

**Étape 2.**Si le PWB-1-BUS reçoit le signal du panneau hybride, la page Web affichera un message de réussite et l'indicateur LED du PWB-1-BUS clignotera 10 fois pour indiquer à l'utilisateur où il se trouve.

_\\<NOTE>_

-   Si un message de délai d'attente s'affiche sur la page Web, cela signifie que le PWB-1-BUS n'a pas reçu le signal du panneau.

3

Veuillez vérifier si le PWB-1-BUS est correctement connecté au panneau à une distance de câblage appropriée.

**Signal de surveillance**

-   Après avoir été appris dans le panneau de commande, le module d'alimentation transmettra automatiquement les signaux de supervision toutes les 20 à 30 secondes.

**Moniteur de consommation d'énergie**

-   Après avoir été appris dans le panneau de commande, le module d'alimentation transmettra automatiquement les données de consommation d'énergie, y compris le niveau de la batterie, la tension du BUS et le courant du BUS, au panneau de commande toutes les 30 à 50 minutes.

![](<.gitbook/assets/5 (7).png>)





Lorsque le niveau de la batterie est inférieur ou égal à 20 %, un signal de batterie faible sera envoyé au panneau.

Lorsque le niveau de la batterie est de 0 %, cela indique l'une des situations suivantes : batterie déconnectée, interrupteur de batterie en position d'arrêt ou panne de batterie.

L'utilisateur peut également interroger manuellement les données de consommation d'énergie sur**Modifier l'appareil**page.

![](<.gitbook/assets/6 (5).png>)

**Montage du PWB-1-BUS dans le boîtier (AWO300)**

-   Localisez le**emplacements d'espacement sur le boîtier AWO300**(○1 – A, B, C, D), et le**trous de montage sur le PWB-1-BUS**(○2 – A, B, C, D).

![](<.gitbook/assets/7 (6).png>)

4

-   Utilisez les entretoises fournies pour monter solidement le PWB-1-BUS dans le boîtier.

![](<.gitbook/assets/8 (6).png>)

-   Une fois tout le câblage terminé, installez la batterie de secours. Les options de batterie incluent : Une batterie au plomb scellée 12 V 7,0 Ah ou 12 V 17,2 Ah.

Pour installer la batterie, suivez les étapes ci-dessous :

-   1.  Connectez le câble GND (noir) au pôle négatif (-) de la batterie.
    2.  Connectez le câble d'alimentation (rouge) au pôle positif (+) de la batterie
    3.  Fixez la batterie de secours au boîtier.
-   Connectez le commutateur d'autoprotection de la porte du boîtier à la borne d'autoprotection.
-   Connectez la borne d'alimentation à une alimentation 20 V CA 50 Hz/60 Hz, 4 A (80 VA). Faites glisser l'interrupteur de la batterie sur ON.

![](<.gitbook/assets/9 (7).png>)

5
