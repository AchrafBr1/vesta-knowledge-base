# VESTA 340

**Module d'extension de sortie programmable série WEPC-1**

**Introduction**

Le module d'extension de sortie programmable série WEPC-1 est conçu pour fournir une sortie programmable pour le panneau hybride. Connecté au panneau hybride via une connexion BUS, il comprend 4 sorties relais programmables, qui peuvent être utilisées conjointement avec des panneaux compatibles. La série WEPC-1 est équipée de son propre boîtier, doté d'une protection contre les manipulations et d'indicateurs d'état LED.

**Le module d'extension de sortie programmable série WEPC-1 comprend les modèles suivants :**

**WEPC-1**– Module d'extension de sortie programmable

**WEPC-1B**– Module d'extension de sortie programmable avec batterie rechargeable

**Identifier les pièces**

**Vue de face****Vue arrière**

![](<.gitbook/assets/0 (18).jpeg>)

**Vue interne**

![](<.gitbook/assets/1 (12).jpeg>)

1

1.  **LED d'alimentation (rouge)**

Allumé – Alimenté par un adaptateur secteur 12 V ou un panneau hybride.

Éteint – Lorsque l'appareil est hors tension ou lorsqu'il est alimenté par une batterie rechargeable.

1.  **Zone 1~4 LED (rouge)**

La LED de zone correspondante s'allumera lorsque l'interrupteur de sortie du relais à contact sec est allumé, et la lumière LED s'éteindra lorsque l'interrupteur sera éteint.

1.  **LED de transmission (rouge)**

S'allume lorsque la connexion est normale entre le module d'extension et le panneau de commande.

1.  **Zone de échappée**

Lorsque le module d'extension est retiré de force de l'emplacement de montage, la zone se détache et permet d'activer l'interrupteur anti-sabotage.

1.  **Interrupteur anti-sabotage (pour montage mural)**

Le module d'extension est protégé par l'interrupteur anti-sabotage contre tout retrait non autorisé du lieu de montage.

1.  **Trous de montage**
2.  **Trou de câblage**
3.  **Borne de connexion de la batterie (pour WEPC-1B uniquement)**

Pour connecter la batterie rechargeable au PCB.

1.  **Cavalier de résistance de borne (J3)**

Lorsque le module d'extension est connecté en tant que périphérique BUS le plus éloigné sur une ligne BUS, veuillez régler le cavalier de résistance de borne du module d'extension et le commutateur de cavalier du premier périphérique BUS (généralement celui du panneau hybride) sur ON pour servir de résistances de terminaison. La capacité de communication de la ligne BUS connectée sera améliorée.

-   Mettez le cavalier sur OFF en retirant le lien du cavalier ou en « garant » le lien du cavalier sur une broche.

![](<.gitbook/assets/2 (34).png>)

\-Mettez le cavalier sur ON en reposant le lien du cavalier sur les deux broches.

1.  **Batterie rechargeable (pour WEPC-1B uniquement)**
2.  **Prise CC**

Pour connexion d'alimentation à découpage DC 12 V.

Pour fournir une alimentation stable et suffisante pour charger les batteries rechargeables du WEPC-1B, il est fortement recommandé d'utiliser un adaptateur secteur à découpage 12 V/1 A.

1.  **Terminal BUS enfichable**
2.  **Borne de sortie PGM du relais à contact sec**
3.  **Interrupteur anti-sabotage (pour le couvercle du boîtier)**

Le module d'extension est protégé par l'interrupteur anti-sabotage contre toute ouverture non autorisée du boîtier. Chaque fois que le couvercle du boîtier est ouvert, l'interrupteur anti-sabotage est activé.

1.  **Bouton de réinitialisation (réservé à un usage interne)**
2.  **Bouton de test**

Appuyez sur le bouton de test pour envoyer un signal de test au panneau de commande.

**Source de courant**

-   Le module d'extension est alimenté par le panneau hybride, qui peut fournir une source d'alimentation de 13,5 V au module d'extension. De plus, il est recommandé d'utiliser l'adaptateur secteur externe (12 V) lors de la connexion à des charges nécessitant une consommation d'énergie plus importante.
-   Lorsque l'alimentation électrique de l'adaptateur est interrompue et rétablie, le module d'extension transmettra respectivement un signal de panne secteur et un signal de restauration au panneau de commande.

2

**Batterie rechargeable (pour WEPC-1B uniquement)**

-   Pour WEPC-1B, une batterie rechargeable Ni-MH est préinstallée dans le module d'extension pour servir de secours en cas de panne de courant.
-   Veuillez connecter manuellement la batterie au PCB pour l'utiliser comme source d'alimentation de secours et/ou pour la charger automatiquement lorsque l'alimentation est connectée à partir de l'adaptateur ou du panneau hybride. \\<Note>Avant de connecter la batterie, assurez-vous que l'alimentation de la prise DC et/ou de la borne BUS est/sont coupées.

Il est fortement recommandé d'utiliser un adaptateur secteur à découpage 12 V/1 A pour fournir une alimentation stable et suffisante pour charger les batteries.

-   Lorsque la batterie rechargeable est faible, le module d'extension transmet un signal de batterie faible au panneau de commande. Une fois les batteries chargées, il transmettra également un signal de restauration de la batterie au panneau de commande.

**Autoprotection**

La série WEPC-1 dispose de deux interrupteurs anti-sabotage ; chacun est livré avec une fonction différente.

-   L'interrupteur anti-sabotage du couvercle du boîtier est situé à l'avant de la carte. Il est en position normale lorsque le boîtier est fermé. Une violation de sabotage se produit lorsque le boîtier est ouvert alors que le commutateur de sabotage est relâché (tamper ouvert).
-   L'interrupteur anti-sabotage pour montage mural est situé à l'arrière de la carte. Il est en position normale lorsque le module est bien fixé au mur. Une violation de l'autoprotection se produit lorsque le module est retiré de force de l'emplacement de montage, la zone se détache et permet d'activer l'interrupteur d'autoprotection.
-   L'autoprotection est considérée comme déclenchée si l'un des autoprotections est ouvert. L'autoprotection n'est considérée comme restaurée que lorsque les deux autoprotections sont à l'état fermé.

**Signal de surveillance**

-   Après avoir été appris dans le panneau de commande, le module d'extension transmettra automatiquement les signaux de supervision toutes les 20 à 30 secondes.

**Connexion au panneau hybride**

-   Avant la connexion, assurez-vous que l'alimentation électrique a été débranchée et que l'interrupteur de batterie du panneau a été glissé en position OFF.
-   Pour faciliter les connexions des câbles, les borniers de chaque module système sont codés par couleur.

| **Rouge** | VDD  |
| --------- | ---- |
| **Noir**  | GND  |
| **Jaune** | 485A |
| **Vert**  | 485B |

-   Pour une communication optimale de la connexion filaire entre la centrale et les appareils BUS connectés, assurez-vous que le cavalier de communication du dispositif BUS le plus éloigné et le cavalier J53 de la centrale sont réglés sur ON pour servir de résistance de terminaison. Assurez-vous d'activer uniquement les 2 cavaliers susmentionnés et de ne pas régler les cavaliers sur ON pour tout autre périphérique BUS intermédiaire.
-   La série WEPC-1 peut être connectée et alimentée soit par le panneau de commande via le terminal BUS, soit par l'alimentation externe via l'adaptateur 12 V. Si le module d'extension utilise une alimentation externe, assurez-vous de contourner la borne rouge VDD du panneau de commande à l'aide du connecteur d'épissure Wago 221.
-   Des connexions incorrectes entraîneront une panne ou un mauvais fonctionnement. Inspectez le câblage et assurez-vous que les connexions sont correctes avant de mettre sous tension.

3

-   Le schéma suivant montre comment WEPC-1 est connecté et alimenté par le panneau hybride.

![](<.gitbook/assets/3 (11).jpeg>)

-   Ce qui suit est la connexion du WEPC-1B au panneau hybride, le WEPC-1B étant alimenté par la source d'alimentation externe.

![](<.gitbook/assets/4 (11).jpeg>)

4

_\\<NOTE>_

-   _Assurez-vous de contourner la borne rouge VDD sur le panneau de commande à l'aide du connecteur d'épissure Wago 221 fourni. Connectez le terminal VDD au périphérique BUS suivant (VST-892-BUS par exemple) alimenté par le panneau hybride._
-   _La conception enfichable du terminal BUS améliore l’efficacité de l’installation. Avant le câblage, vous pouvez retirer les borniers de l'appareil pour faciliter l'utilisation et les rebrancher après le câblage. Lors de la réinstallation des borniers sur la carte, assurez-vous de les installer dans la même direction pour éviter les dangers potentiels._

**Commencer**

Après avoir connecté la carte d'extension au panneau hybride et terminé le câblage de l'appareil, veuillez procéder à l'apprentissage et à la programmation du capteur de l'interrupteur d'alimentation.

-   _**Apprentissage**_

**Étape 1.**Connectez le module d'extension au panneau de commande. Ensuite, allumez le panneau de commande**.**

**Étape 2.**Cliquer sur "**Apprentissage**» pour accéder à la page d'apprentissage.

**Étape 3.**Cliquer sur "**Commencer**» pour passer en mode apprentissage.

**Étape 4.**Cliquez sur**"Ajouter"**pour inclure le module d'extension dans le panneau.

**Étape 5.**Si le module d'extension est appris avec succès dans le système, le périphérique ajouté sera affiché dans la section « Périphérique appris ». Le type de périphérique sera affiché comme « Extenseur ».

-   _**Power Switch Sensor Programming**_

Une fois le module d'extension de sortie programmable ajouté, passez à la programmation du capteur de commutateur d'alimentation.

**Étape 1.**Cliquez sur Capteur filaire pour accéder à cette page Web. Vous verrez les extensions au bas de la page.

**Étape 2.**Cliquez sur « Modifier » à la fin de l'entrée de l'expandeur.

**Étape 3.**Sélectionnez et attribuez le commutateur de sortie pour chaque zone.

-   **Taper**: Sélectionnez pour activer l’interrupteur d’alimentation pour chaque zone dans le menu déroulant Type. Le paramètre par défaut est « Désactivé » et vous pouvez choisir d'attribuer l'interrupteur d'alimentation de sortie de relais à contact sec à une zone en sélectionnant « Interrupteur d'alimentation ».

**Étape 4.**Cliquez sur "**D'ACCORD**» pour enregistrer les modifications une fois terminé. Vous pouvez également cliquer sur «**Les rendements**t” pour saisir à nouveau toutes les informations.

**Étape 5.**Si le processus réussit, l’écran affichera «**Mis à jour avec succés.**" L'interrupteur d'alimentation sera attribué à une zone et une zone spécifiques.

**Étape 6.**Cliquez sur « PSS Contrôle » sous Gestion des appareils et vous entrerez**Capteur de commutateur d'alimentation**page web.

**Étape 7.**Sous cette page, vous pouvez allumer ou éteindre l'interrupteur d'alimentation de chaque zone.

**Étape 8.**Vous pouvez également modifier les paramètres et les informations de votre appareil. Cliquez sur "**Modifier**" à la fin de la saisie de l'appareil et cliquez sur " OK " pour enregistrer les modifications une fois terminé.

-   _**Identification**_

La fonction « Identifier » permet de localiser un périphérique BUS spécifique dans le système filaire BUS. Cette fonction est utile pour distinguer quel appareil est quel appareil, en particulier dans une grande installation où de nombreux appareils BUS sont inclus.

Pour localiser le module d'extension de sortie programmable dans le système BUS :

**Étape 1.**Sur la page Web du panneau hybride, cliquez sur « Identifier » sous la liste des appareils après l'entrée dans la colonne des appareils de l'expandeur.

![](<.gitbook/assets/5 (21).png>)

5

**Étape 2.**Si le module d'extension de sortie programmable reçoit le signal du panneau hybride, la page Web affichera un message de réussite et le voyant LED d'alimentation du WEPC-1(B) clignotera 10 fois pour indiquer à l'utilisateur où il se trouve.

_\\<NOTE>_

-   -   Si un message de délai d'attente s'affiche sur la page Web, cela signifie que le module d'extension de sortie programmable n'a pas reçu le signal du panneau.

Veuillez vérifier si WEPC-1(B) est correctement connecté au panneau à une distance de câblage appropriée.

-   _**Test de marche**_
-   Pour vous assurer que le module d'extension de sortie programmable est capable de communiquer avec le

Panneau une fois son apprentissage effectué, placez le panneau de commande en mode Test de marche et appuyez sur le bouton Test du WEPC-1(B) pour transmettre un signal de test au panneau de commande.

-   Lorsque le panneau reçoit le signal de test, il émet un bip et affiche les informations du WEPC-1(B) en conséquence en haut de la liste des appareils.

_\\<NOTE>_

-   S'il n'y a pas de réponse du panneau après avoir appuyé sur le bouton de test, cela signifie que le panneau n'a pas reçu le signal de test de l'appareil.

Veuillez vérifier si WEPC-1(B) est correctement connecté au panneau à une distance de câblage appropriée.

**Câblage PGM**

-   Le port PGM peut servir de sortie relais à contact sec.
-   Par défaut, N.C et COM sont définis comme étant en court-circuit.
-   Vous pouvez définir le N.O. et COM comme court-circuit en allumant l'interrupteur d'alimentation via la page Web de programmation.

**Paramètres par défaut****Paramétrage par page de programmation**

![](<.gitbook/assets/6 (11).jpeg>)![](<.gitbook/assets/7 (10).jpeg>)

**Comment monter le module d'extension de sortie programmable**

![](<.gitbook/assets/8 (8).jpeg>)

Le module d'extension de sortie programmable peut être monté au mur en suivant les étapes ci-dessous :

-   Desserrez la vis de fixation inférieure et retirez le capot avant,
-   En utilisant les trous de la carte d'extension de sortie programmable comme modèle, marquez les trous de perçage sur le mur.
-   Percez des trous à l’emplacement marqué sur le mur. Insérez des chevilles murales si nécessaire.
-   Vissez la base sur l'emplacement de montage.
-   Remettez en place le capot avant et serrez les vis de fixation inférieures.

6
