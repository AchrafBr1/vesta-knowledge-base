# VESTA 224

**Module d'extension série WEZC-8**

**Introduction**

Ce guide d'installation doit être utilisé conjointement avec le manuel d'utilisation du panneau hybride, auquel le modèle de la série WEZC-8 est connecté.

Le module d'extension de la série WEZC-8 est conçu pour prendre en charge l'extension du panneau hybride. Connecté au Panneau Hybride via une connexion BUS, il peut assurer l'extension jusqu'à 8 zones sur les panneaux compatibles. La série WEZC-8 est équipée de son propre boîtier, doté d'une protection anti-effraction et d'indicateurs d'état LED.

**Le module d'extension de la série WEZC-8 comprend les modèles suivants :**

**WEZC-8**– Module d'extension avec 8 zones filaires

**WEZC-8B**– Module d'extension avec 8 zones filaires et batterie rechargeable

**Identifier les pièces**

**Vue de face****Vue arrière**

![](<.gitbook/assets/0 (6).jpeg>)

**Vue interne**

![](<.gitbook/assets/1 (8).jpeg>)

1

1.  **LED d'alimentation (rouge)**

Allumé – Alimenté par un adaptateur secteur 12 V ou un panneau hybride.

Éteint – Lorsque l'appareil est hors tension ou lorsqu'il est alimenté par une batterie rechargeable.

1.  **Zone 1~8 LED (rouge)**

La LED de zone correspondante s'allumera lorsque certaines zones sont déclenchées ou ont une condition de sabotage ou de masquage.

1.  **LED de transmission (rouge)**

S'allume lorsque la connexion ou la transmission du signal est normale entre le module d'extension et le panneau de commande.

1.  **Zone de échappée**

Lorsque le module d'extension est retiré de force de l'emplacement de montage, la zone sera détachée, provoquant l'activation du commutateur d'autoprotection.

1.  **Interrupteur anti-sabotage (pour montage mural)**

Le module d'extension est protégé par l'interrupteur anti-sabotage contre tout retrait non autorisé du lieu de montage.

1.  **Trous de montage**
2.  **Trou de câblage**
3.  **Borne de connexion de la batterie (pour WEZC-8B uniquement)**

Pour connecter la batterie rechargeable au PCB.

1.  **Batterie rechargeable (pour WEZC-8B uniquement)**
2.  **Cavalier de résistance de borne (J3)**

Lorsque le module d'extension est connecté en tant que périphérique BUS le plus éloigné sur une ligne BUS, veuillez régler le cavalier de résistance de borne du module d'extension et le cavalier du premier périphérique BUS (généralement celui du panneau hybride) sur ON pour servir de résistances de terminaison. La capacité de communication de la ligne BUS connectée sera améliorée.

![](<.gitbook/assets/2 (9).jpeg>)

Mettez le cavalier sur OFF en retirant le lien du cavalier ou en « garant » le lien du cavalier sur une broche.

![](<.gitbook/assets/3 (8).jpeg>)

Mettez le cavalier sur ON en reposant le lien du cavalier sur les deux broches.

**11. Prise CC**

Pour connexion d'alimentation à découpage DC 12 V.

Pour fournir une alimentation stable et suffisante pour charger les batteries rechargeables du WEZC-8B, il est fortement recommandé d'utiliser un adaptateur secteur à découpage 12 V/1 A.

1.  **Terminal de BUS enfichable**
2.  **Borne de zone, borne de sortie de tension auxiliaire 13,5 V et borne GND**

La tension typique est de 13,5 V et peut varier en fonction de la tension de sortie du terminal.

**14. Bouton de test**

Appuyez sur le bouton de test pour envoyer un signal de test au panneau de commande.

1.  **Bouton de réinitialisation (réservé à un usage interne)**
2.  **Interrupteur anti-sabotage (pour le couvercle du boîtier)**

Le module d'extension est protégé par l'interrupteur anti-sabotage contre toute ouverture non autorisée du boîtier. Chaque fois que le couvercle du boîtier est ouvert, l'interrupteur anti-sabotage est activé.

**Source de courant**

-   Le module d'extension est alimenté par le panneau hybride, qui peut fournir une source d'alimentation de 13,5 V au module d'extension. De plus, il est recommandé d'utiliser l'adaptateur secteur externe (12 V) lors de la connexion à des charges nécessitant une consommation d'énergie plus importante.
-   Lorsque l'alimentation électrique de l'adaptateur est interrompue et rétablie, le module d'extension transmettra respectivement un signal de panne secteur et un signal de restauration au panneau de commande.

2

**Batterie rechargeable (pour WEZC-8B uniquement)**

-   Pour le WEZC-8B, une batterie rechargeable Ni-MH est préinstallée dans le module d'extension pour servir de secours en cas de panne de courant.
-   Veuillez connecter manuellement la batterie au PCB pour l'utiliser comme source d'alimentation de secours et/ou pour la charger automatiquement lorsque l'alimentation est connectée à partir de l'adaptateur ou du panneau hybride. \\<Note>Avant de connecter la batterie, assurez-vous que l'alimentation de la prise DC et/ou de la borne BUS est/sont coupées.

Il est fortement recommandé d'utiliser un adaptateur secteur à découpage 12 V/1 A pour fournir une alimentation stable et suffisante pour charger les batteries.

-   Lorsque la batterie rechargeable est faible, le module d'extension transmet un signal de batterie faible au panneau de commande. Une fois les batteries chargées, il transmettra également un signal de restauration de la batterie au panneau de commande.

**Autoprotection**

La série WEZC-8 dispose de deux interrupteurs anti-sabotage ; chacun est livré avec une fonction différente.

-   L'interrupteur anti-sabotage du couvercle du boîtier est situé à l'avant de la carte. Il est en position normale lorsque le boîtier est fermé. Une violation de sabotage se produit lorsque le boîtier est ouvert alors que le commutateur de sabotage est relâché (tamper ouvert).
-   L'interrupteur anti-sabotage pour montage mural est situé à l'arrière de la carte. Il est en position normale lorsque le module est bien fixé au mur. Une violation de sabotage se produit lorsque le module est retiré de force de l'emplacement de montage ; la zone de sécurité sera détachée, ce qui entraînera l'activation du commutateur d'autoprotection.
-   L'autoprotection est considérée comme déclenchée si l'un des autoprotections est ouvert. Le sabotage n'est considéré comme restauré que lorsque les deux sabotages sont à l'état fermé.

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

-   Pour une communication optimale des appareils BUS connectés, assurez-vous que l'appareil BUS le plus éloigné

Le cavalier de résistance de borne et le cavalier J53 du panneau de commande sont réglés sur ON pour servir de résistances de terminaison. Assurez-vous d'activer uniquement les 2 cavaliers susmentionnés et de ne pas régler les cavaliers sur ON pour tout autre périphérique BUS intermédiaire.

-   La série WEZC-8 peut être connectée et alimentée soit par le panneau de commande via la borne BUS, soit par l'alimentation externe via l'adaptateur 12 V. Si le module d'extension utilise une alimentation externe, assurez-vous de contourner la borne rouge VDD du panneau de commande à l'aide du connecteur d'épissure Wago 221.

3

-   Ce qui suit est le WEZC-8 connecté et alimenté par le panneau hybride :

![](<.gitbook/assets/4 (8).jpeg>)

-   Ce qui suit est la connexion du WEZC-8B au panneau hybride, le WEZC-8B étant alimenté par une source d'alimentation externe.

![](<.gitbook/assets/5 (6).jpeg>)

4

_Note:_

-   _Assurez-vous de contourner la borne rouge VDD sur le panneau de commande à l'aide du connecteur d'épissure Wago 221 fourni. Connectez le terminal VDD au périphérique BUS suivant (VST-892-BUS par exemple) alimenté par le panneau hybride._
-   _La conception enfichable des borniers BUS améliore l'efficacité de l'installation. Avant le câblage, vous pouvez retirer les borniers de l'appareil pour faciliter l'utilisation et les rebrancher après le câblage. Lors de la réinstallation des borniers sur la carte, assurez-vous de les installer dans la même direction pour éviter les dangers potentiels._
-   _Des connexions incorrectes entraîneront une panne ou un mauvais fonctionnement. Inspectez le câblage et assurez-vous que les connexions sont correctes avant de mettre sous tension._

**Câblage des zones**

-   Les 8 zones peuvent être câblées pour superviser des appareils NC (normalement fermés) ou NO (normalement ouverts), par exemple des capteurs PIR, des contacts de porte, des détecteurs de fumée, des capteurs d'eau, des capteurs d'incendie, des capteurs de CO, des détecteurs de gaz, des détecteurs de chaleur et des bris de verre. détecteurs, etc.
-   Connectez des appareils câblés à n’importe quel terminal de zone.
-   Calibre du fil : minimum 22 AWG, maximum 19 AWG. N'utilisez pas de fil blindé.
-   Les zones câblées prennent en charge la configuration de boucle simple fin de ligne (SEOL) et double fin de ligne (DEOL), avec des valeurs de résistance sélectionnables de 1 KΩ, 2,2 KΩ, 3,74 KΩ, 4,7 KΩ, 5,6 KΩ, 6,8 KΩ. , 8,2 KΩ, 10 KΩ ohms.
-   La boucle triple fin de ligne (TEOL) peut être configurée dans différentes combinaisons : 4,7 KΩ, 6,8 KΩ,

12KΩ (sélection de la valeur de la résistance : 6,8K), 4,7KΩ/5,6KΩ, 4,7KΩ, 2,2KΩ/3KΩ (valeur de la résistance

sélection : 4,7K), ou 4,7KΩ/5,6KΩ, 5,6KΩ, 2,2KΩ/3KΩ (sélection de la valeur de la résistance : 5,6K).

-   Veuillez installer la ou les résistances à l'extrémité de chaque boucle de zone, loin du panneau de commande. Le panneau détectera si le circuit est sécurisé, ouvert ou court-circuité.
-   Pour une boucle NC, veuillez avoir une résistance EOL en série avec la boucle.
-   Pour une boucle NO, veuillez avoir une résistance EOL en parallèle (à travers) la boucle. Veuillez vous référer aux schémas suivants pour des exemples de câblage.
-   Si une méthode de câblage de zone est modifiée, assurez-vous de mettre le système hors tension, puis de le rallumer pour éviter de déclencher l'alarme.

Veuillez vous référer aux schémas suivants des boucles 1 à 10 pour des exemples de câblage.

**Câblage NO/NF**

Le panneau peut détecter l'alarme des appareils NO ou NC correspondants via les circuits ouverts, sécurisés ou en court-circuit.

_\\<NOTE>_

 Il n'y a pas de résistance EOL dans la boucle 1 et la boucle 2

**Câblage NO/NF**

1.2.

![](<.gitbook/assets/6 (6).jpeg>)![](<.gitbook/assets/7 (6).jpeg>)

5

**Câblage d'une résistance de fin de ligne unique**

3.4.

![](<.gitbook/assets/8 (7).png>)

5.6.

![](<.gitbook/assets/9 (10).png>)

**Câblage de résistances à double fin de ligne**

7.8.

![](<.gitbook/assets/10 (11).png>)

**Câblage triple EOL**

9.10.

![](<.gitbook/assets/11 (6).png>)

6

**Commencer**

Après avoir connecté la carte d'extension au panneau hybride et terminé le câblage de l'appareil, veuillez procéder à l'apprentissage et à la programmation des zones.

-   _**Apprentissage**_

**Étape 1.**Connectez le module d'extension au panneau de commande. Ensuite, allumez le panneau de commande**.**

**Étape 2.**Cliquer sur -**Apprentissage**» pour accéder à la page d'apprentissage.

**Étape 3.**Cliquer sur -**Commencer**» pour passer en mode apprentissage.

**Étape 4.**Cliquez sur**"Ajouter"**pour inclure le module d'extension dans le panneau.

**Étape 5.**Si le module d'extension est correctement appris dans le système, le périphérique ajouté sera affiché dans la section « Périphérique appris ». Le type de périphérique sera affiché comme « Extenseur ».

-   _**Programmation de zones filaires**_

Une fois le module d'extension ajouté, passez à la programmation de la zone filaire.

**Étape 1.**Cliquez sur Capteur filaire pour accéder à cette page Web. Vous verrez les extensions au bas de la page.

**Étape 2.**Cliquez sur « Modifier » à la fin de l'entrée de l'extension.

**Étape 3.**Modifiez le type de capteur câblé, le câblage de la zone et la résistance EOL pour chaque zone.

-   **Taper**: Sélectionnez le type de capteur filaire pour chaque zone dans le menu déroulant.
-   **Boucle**: Sélectionnez le numéro correspondant au câblage de zone pour chaque zone dans le menu déroulant. Sur cette page Web, vous trouverez ci-dessous des schémas de câblage pour votre référence.
-   **Résistance**: Sélectionnez la résistance pour le câblage de la zone.
-   **Statut**: L'état de chaque zone — Restauration, Autoprotection ou Déclenchement — sera affiché ici.

**Étape 4.**Cliquez sur -**D'ACCORD**‖ pour enregistrer les modifications une fois terminé. Vous pouvez également cliquer sur ―**Les rendements**t‖ pour saisir à nouveau toutes les informations.

**Étape 5.**Si le processus réussit, l'écran affichera ―**Mis à jour avec succés.**‖ Le capteur sera attribué à une zone et une zone spécifiques. Pour modifier les paramètres ou les informations de l'appareil, cliquez sur ―**Modifier**» à la fin de la saisie de l'appareil.

**Étape 6.**Vous entrerez**Modifier l'appareil**page web.

**Étape 7.**Modifiez les paramètres et les informations de votre appareil. Cliquez sur « OK » pour enregistrer les modifications lorsque vous avez terminé.

-   _**Identification**_

La fonction « Identifier » permet de localiser un périphérique BUS spécifique dans le système filaire BUS. Cette fonction est utile pour distinguer quel appareil est quel appareil, en particulier dans une grande installation où de nombreux appareils BUS sont inclus.

Pour localiser le module d'extension dans le système BUS :

**Étape 1.**Sur la page Web du panneau hybride, cliquez sur « Identifier » sous la liste des périphériques après l'entrée dans la colonne des périphériques de l'expandeur.

![](<.gitbook/assets/12 (9).png>)

**Étape 2.**Si le module d'extension reçoit le signal du panneau hybride, la page Web affichera un message de réussite et le voyant LED d'alimentation du module d'extension clignotera 10 fois pour indiquer à l'utilisateur où il se trouve.

_\\<NOTE>_

-   Si un message de délai d'attente s'affiche sur la page Web, cela signifie que le module d'extension n'a pas reçu le signal du panneau.

Veuillez vérifier si le module d'extension est correctement connecté au panneau à une distance de câblage appropriée.

7

-   _**Test de marche**_
-   Pour vous assurer que le module d'extension est capable de communiquer avec le panneau une fois qu'il est

appris, placez le panneau de commande en mode test de marche et appuyez sur le bouton Test du WEZC-8 pour transmettre un signal de test au panneau de commande.

-   Lorsque le panneau reçoit le signal de test, il émet un bip et affiche les informations du module d'extension en conséquence en haut de la liste des appareils.

_\\<NOTE>_

-   S'il n'y a pas de réponse du panneau après avoir appuyé sur le bouton de test, cela signifie que le panneau n'a pas reçu le signal de test de l'appareil.

Veuillez vérifier si le module d'extension est correctement connecté au panneau à une distance de câblage appropriée.

**Comment monter le module d'extension**

Le module d'extension peut être monté au mur. Suivez les étapes ci-dessous pour le monter :

-   Desserrez la vis de fixation inférieure et retirez le capot avant.
-   En utilisant les trous du module d'extension comme modèle, marquez les trous de perçage sur le mur.
-   Percez des trous à l’emplacement marqué sur le mur. Insérez des chevilles murales si nécessaire.
-   Vissez la base sur l'emplacement de montage.
-   Remettez en place le capot avant et serrez les vis de fixation inférieures.

![](<.gitbook/assets/13 (3).jpeg>)

8
