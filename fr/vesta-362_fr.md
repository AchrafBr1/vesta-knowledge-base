# VESTA 362

**Sirène intérieure filaire (SR-35-BUS)**

SR-35-BUS est une sirène intérieure câblée utilisée pour l'indication d'alarme du système. Lorsqu'un signal d'alarme est reçu du panneau de commande, la sirène intérieure filaire s'active pour attirer l'attention. L'appareil peut également fonctionner avec le panneau de commande pour émettre des sons de délai d'entrée et de sortie, et également vous alerter en cas de violation de sabotage.

![](<.gitbook/assets/0 (3).jpeg>)

**Identifier les pièces**

![](<.gitbook/assets/1 (4).jpeg>)

1.  **Bouton Apprendre**
2.  **Commutateur de cavalier de résistance de borne**

Lorsque la sirène intérieure filaire est connectée en tant que périphérique BUS le plus éloigné sur une ligne BUS, veuillez régler le cavalier de résistance de borne de la sirène intérieure filaire et le commutateur de cavalier du premier périphérique BUS (généralement le panneau hybride) sur ON pour servir de terminaison.

résistances. La capacité de communication de la ligne BUS connectée sera améliorée.

![](<.gitbook/assets/2 (4).png>)

**Cavalier**

**Cavalier**

Le cavalier est inséré, reliant les deux broches.

Le lien de cavalier est supprimé ou "**garé**» sur une épingle.

-   -   Si le cavalier est désactivé, la capacité de communication est au niveau normal.
    -   Si le cavalier est activé, la capacité de communication est améliorée.

1.  **Terminal de bus**
2.  **Vis de fixation inférieure**
3.  **Interrupteur anti-sabotage**

L'interrupteur anti-sabotage sera activé lorsque la sirène sera retirée du support de montage.

1.  **Zone de séparation pour le câblage du BUS**
2.  **Support de montage**

![](<.gitbook/assets/3 (4).png>)

1

![](<.gitbook/assets/4 (4).jpeg>)**Source de courant**

-   Lorsque le SR-35-BUS est câblé à un panneau hybride, une alimentation de 13,5 V peut être fournie par le panneau hybride.

![](<.gitbook/assets/5 (1) (1).jpeg>)

**Surveillance**

La sirène intérieure filaire transmettra un signal de supervision toutes les 20 à 30 secondes en mode de fonctionnement normal.

Si ce signal n'est pas reçu, la centrale d'alarme indiquera que la sirène en question rencontre un problème de dysfonctionnement.

![](<.gitbook/assets/6 (4).png>)

**Aperçu des fonctions**

-   **Mémoire d'alarme**

Si une alarme s'est déclenchée en votre absence et que le système n'a pas été désarmé avant l'expiration de la durée de l'alarme, la sirène intérieure filaire émettra une courte alarme lorsque le système est désarmé pour avertir l'utilisateur qu'une alarme s'est déclenchée en son absence. Cela suggère que l’intrus pourrait toujours se trouver dans les locaux.

-   **Durée de l'alarme**

Lorsqu'une alarme est activée par le panneau de commande, celui-ci demandera à la sirène intérieure filaire de déclencher une alarme en fonction de la durée de l'alarme du panneau. Lorsque la durée de l'alarme du panneau expire, le panneau demandera à l'appareil d'arrêter l'alarme.

Si la sirène intérieure filaire ne reçoit pas le signal du panneau de commande pour arrêter l'alarme, elle déclenchera une alarme pendant 15 minutes maximum, puis arrêtera l'alarme.

Par exemple:

-   -   Si la durée de l’alarme du panneau est réglée sur plus de 15 minutes, après l’activation d’une alarme, au lieu d’attendre l’expiration de la durée de l’alarme du panneau, l’alarme s’arrêtera après 15 minutes.
    -   Si la centrale est en mode désarmé et que l'interrupteur anti-sabotage de la sirène est déclenché, la sirène intérieure filaire n'activera pas l'alarme puisque la centrale est en mode désarmé et activera l'alarme pendant 15 minutes en raison du déclenchement d'une auto-surveillance.
-   **Anti-sabotage de sirène**

La Sirène Intérieure Filaire est protégée contre toute tentative d'ouverture du couvercle ou de détachement de l'appareil de sa surface de montage.

Si l'appareil détecte une condition de sabotage, il activera la sirène pour la durée d'alarme programmée. Un signal d'autoprotection sera envoyé au panneau de commande avec des transmissions de signaux régulières pour que le panneau de commande affiche l'état en conséquence. Si la condition d'autoprotection persiste, l'appareil émettra une série de cinq bips pour indiquer un défaut, soit à chaque fois que le système est armé, soit lorsque l'autoprotection est activée.

-   **Indication de l'état audio**

Lors de l'armement/désarmement du système, différentes méthodes sont utilisées pour distinguer les différents statuts de l'utilisateur, comme indiqué dans le tableau ci-dessous.

![](<.gitbook/assets/7 (5).png>)![](<.gitbook/assets/8 (5).png>)![](<.gitbook/assets/9 (6).png>)

| **Statut**                   | **Son de la sirène**     |
| ---------------------------- | ------------------------ |
|                              |                          |
| Bras/Accueil                 | 1 bip                    |
| Désarmer                     | 2 bips                   |
| Bras (autoprotection)        | 5 bips                   |
| Désarmer (autoprotection)    | 5 bips                   |
| Son de délai d'entrée/sortie | Bips du compte à rebours |

![](<.gitbook/assets/10 (8).png>)![](<.gitbook/assets/11 (4).jpeg>)![](<.gitbook/assets/12 (2).jpeg>)

**Prudence**

-   Le câblage de la sirène intérieure filaire ne doit être effectué que par des techniciens certifiés possédant les connaissances et la formation appropriées en matière d'équipement électrique.
-   Avant l'installation ou tout travail de maintenance, assurez-vous que l'alimentation électrique a été débranchée.

![](<.gitbook/assets/13 (2).jpeg>)

**Câblage de la sirène**

-   Avant de connecter la sirène intérieure filaire au bus système, veuillez couper l'alimentation.
-   Pour faciliter les connexions des câbles, les borniers de chaque module du système BUS sont codés par couleur.

![](<.gitbook/assets/14 (2).jpeg>)

| **Rouge** | VDD  |
| --------- | ---- |
| **Noir**  | GND  |
| **Jaune** | 485A |
| **Vert**  | 485B |

2

-   Plusieurs appareils BUS peuvent être connectés en série au panneau hybride. Pour une communication optimale des dispositifs de ligne BUS connectés, assurez-vous que les cavaliers de résistance terminale du premier (généralement le panneau hybride) et des dispositifs BUS les plus éloignés sur une ligne BUS sont réglés sur ON pour servir de résistances de terminaison. Assurez-vous d'activer uniquement les 2 cavaliers susmentionnés et de ne pas régler les cavaliers sur ON pour tout autre périphérique BUS intermédiaire.

![](<.gitbook/assets/15 (4).png>)

_\\<NOTE>_

-   -   La conception enfichable des borniers BUS améliore l'efficacité de l'installation. Avant le câblage, vous pouvez retirer les borniers de la carte PCB pour faciliter l'utilisation et les rebrancher après le câblage.
    -   Après avoir débranché le terminal, lors de la réinstallation du terminal sur la carte, assurez-vous d'installer le terminal dans la même direction pour éviter les dangers potentiels.
-   Des connexions incorrectes entraîneront une panne ou un mauvais fonctionnement. Inspectez le câblage et assurez-vous que les connexions sont correctes avant de mettre sous tension.

![](<.gitbook/assets/16 (7).png>)

**Apprentissage**

Veuillez suivre les étapes ci-dessous pour apprendre la sirène intérieure filaire au panneau hybride.

Étape 1. Connectez l'appareil au panneau. Ensuite, allumez le panneau.

Étape 2. Sur la page Web du Panel, cliquez sur «**Apprentissage**» pour accéder à la page d'apprentissage.

Étape 3. Cliquez sur «**Commencer**» pour passer en mode apprentissage.

Étape 4. Cliquez sur «**Ajouter**» pour inclure l'appareil dans le panneau.

Étape 5. Si le périphérique est correctement appris dans le panneau, il sera affiché dans la section « Périphérique appris ».

![](<.gitbook/assets/17 (3).jpeg>)

**Identification**

Le "**Identifier**La fonction " est utilisée pour localiser un périphérique BUS spécifique dans le système filaire BUS. Cette fonction est utile pour distinguer quel appareil est quel appareil, en particulier dans une grande installation où de nombreux appareils BUS sont inclus.

Pour localiser la sirène intérieure filaire dans le système BUS :

**Étape 1.**Sur la page Web du panneau hybride, cliquez sur « Identifier » sous la liste des appareils après l'entrée dans la colonne des appareils de la sirène.

**Étape 2.**Si le SR-35-BUS reçoit le signal du panneau hybride, la page Web affichera un message de réussite et la sirène intérieure filaire émettra 10 bips pour indiquer à l'utilisateur où elle se trouve.

![](<.gitbook/assets/18 (7).png>)

_\\<NOTE>_

-   Si un message de délai d'attente s'affiche sur la page Web, cela signifie que la sirène intérieure filaire n'a pas reçu le signal du panneau.

Veuillez vérifier si le SR-35-BUS est correctement connecté au panneau à une distance de câblage appropriée.

![](<.gitbook/assets/19 (6).png>)

3

![](<.gitbook/assets/20 (2).jpeg>)**Test de marche**

-   Pour vous assurer que la sirène intérieure filaire est capable de communiquer avec le panneau après son apprentissage, placez le panneau de commande en mode test de marche et appuyez sur le bouton d'apprentissage du SR-35-BUS pour transmettre un signal de test au panneau de commande.
-   Lorsque le panneau reçoit le signal de test, il émet un bip et affiche les informations de la sirène en conséquence en haut de la liste des appareils.

_\\<NOTE>_

-   S'il n'y a pas de réponse du panneau après avoir appuyé sur le bouton d'apprentissage, cela signifie que le panneau n'a pas reçu le signal de test de l'appareil.

Veuillez vérifier si le SR-35-BUS est correctement connecté au panneau à une distance de câblage appropriée.

**Installation**

Étape 1. Trouvez l'emplacement où la sirène intérieure filaire doit être montée.

Étape 2. Utilisez le support de montage comme modèle pour percer 3 trous sur le mur pour les chevilles.

Étape 3. Enfoncez les chevilles et vissez le support de montage au mur avec 3 vis.

Étape 4. Accrochez la sirène au support de montage, puis poussez vers le bas jusqu'à ce que vous entendiez un clic.

_\\<NOTE>_

-   Veuillez vous assurer que l'appareil est correctement accroché au support de montage, de sorte que l'interrupteur anti-sabotage soit complètement enfoncé.

Étape 5. Vérifiez si l'installation a réussi en testant à partir du panneau de commande avec fonction d'armement et de désarmement.

Un armement/désarmement réussi sera indiqué par le tableau fourni ci-dessus dans**Indication de l'état audio**section.

_\\<NOTE>_

-   Si 5 bips courts sont entendus lors de l'armement/désarmement, cela signifie que l'autoprotection n'est pas complètement enfoncée. Vérifiez que l'autoprotection est correctement configurée et testez à nouveau à partir du panneau de commande.

Étape 6. L'installation est maintenant terminée.

4
