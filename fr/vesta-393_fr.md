# VESTA 393

![](<.gitbook/assets/0 (6).png>)**Lecteur d'étiquettes filaire (TG-15N-BUS)**

-   _**Introduction**_

TG-15N-BUS est un lecteur d'étiquettes capable de communiquer avec le panneau hybride et d'être alimenté par celui-ci via une connexion BUS.

Le lecteur d'étiquettes filaire est intégré aux étiquettes NFC pour vous permettre d'armer ou de désarmer rapidement votre système d'alarme d'un simple glissement.

L'appareil se compose d'une conception en deux parties composée d'un couvercle et d'une base. Le couvercle contient toute l'électronique et le socle assure un moyen de fixation. L'interrupteur anti-sabotage protège le boîtier contre toute ouverture ou tout retrait de la surface de montage.

![](<.gitbook/assets/1 (4).png>)

-   _**Identifier les pièces**_

1.  **LED verte LED rouge LED orange Bouton d'activation**
2.  **Zone de capteur (pour les balises)**
3.  **Terminal de bus**
4.  **Commutateur de cavalier de résistance de borne**

Lorsque le lecteur d'étiquettes filaire est connecté en tant que périphérique BUS le plus éloigné sur une ligne BUS, veuillez régler le cavalier de résistance de borne du lecteur et le commutateur de cavalier du premier périphérique BUS (généralement le panneau hybride) sur ON pour servir de résistances de terminaison. La capacité de communication de la ligne BUS connectée sera améliorée.

![](<.gitbook/assets/2 (6).jpeg>)![](<.gitbook/assets/3 (5).png>)

**Cavalier**

![](<.gitbook/assets/4 (6).jpeg>)

Le cavalier est inséré, reliant les deux broches.

**Cavalier**

Le lien de cavalier est supprimé ou "**garé**» sur une épingle.

-   -   Si le cavalier est désactivé, la capacité de communication est au niveau normal.
    -   Si le cavalier est activé, la capacité de communication est améliorée.

1.  **Bouton Apprendre**
2.  **Altérer**
3.  **Vis de fixation**
4.  **Découpes pour vis de montage**
5.  **Trou de câblage BUS**

![](<.gitbook/assets/5 (3).jpeg>)

1

-   ![](<.gitbook/assets/6 (6).png>)_**Indicateur LED :**_
    -   **LED verte :**
        -   S'allume pendant 3 secondes : lorsque le panneau de commande est en mode désarmement
        -   Clignote pendant 5 secondes : lorsque le bouton d'armement est enfoncé (_Placez l'étiquette près de la zone de capteur pour armer le système pendant ces 5 secondes_)
        -   Clignote 10 fois : lorsque l’on clique sur « identifier » sur la page Web du Panel.
    -   **LED rouge :**
        -   S'allume pendant 3 secondes : lorsque le panneau de commande est en mode Armement
        -   Clignote pendant 3 secondes : lorsque le système est désarmé après une alarme
    -   **LED orange :**
        -   S'allume pendant 3 secondes : lorsque le TG-15N-BUS détecte une balise car il perd la connexion avec le panneau de commande
-   _**Pouvoir:**_

![](<.gitbook/assets/7 (3).jpeg>)![](<.gitbook/assets/8 (3).jpeg>)![](<.gitbook/assets/9 (8).png>)

Lorsque le TG-15N-BUS est câblé à un panneau hybride, une alimentation de 13,5 V peut être fournie par le panneau hybride.

![](<.gitbook/assets/10 (9).png>)

-   _**Autoprotection:**_
    -   Le Lecteur de Tag Filaire est protégé contre toute tentative d'ouverture du couvercle ou de détachement du Lecteur de sa surface de montage (voir**Lecteur d'étiquettes de montage**pour plus de détails).
    -   Lorsque l'autoprotection du lecteur est déclenchée, un signal d'autoprotection sera envoyé au panneau de commande pour que celui-ci affiche l'état. Une fois le signal envoyé, le Reader revient en mode veille.
-   _**Surveillance**_
    -   Après l'installation, le lecteur d'étiquettes filaire transmettra automatiquement des signaux de supervision périodiquement au panneau de commande à des intervalles aléatoires de 20 à 30 secondes.
-   _**Prudence**_
    -   Le câblage du lecteur d'étiquettes filaire doit être effectué uniquement par des techniciens certifiés possédant les connaissances et la formation appropriées en matière d'équipement électrique.
    -   Avant l'installation ou tout travail de maintenance, assurez-vous que l'alimentation électrique a été débranchée.
-   _**Câblage du lecteur d'étiquettes :**_
    -   Avant de connecter le Wired Tag Reader au bus système, veuillez couper l’alimentation.
    -   Pour faciliter la connexion des câbles, les borniers de chaque module du système BUS sont codés par couleur.

![](<.gitbook/assets/11 (4).png>)![](<.gitbook/assets/12 (6).png>)![](<.gitbook/assets/13 (6).png>)![](<.gitbook/assets/14 (3).jpeg>)

| **Rouge**  | VDD  |
| ---------- | ---- |
|            |      |
| **Noir**   | GND  |
|            |      |
| **Yellow** | 485A |
|            |      |
| **Vert**   | 485B |
|            |      |

-   Plusieurs appareils BUS peuvent être connectés en série au panneau hybride. Pour une communication optimale des dispositifs de ligne BUS connectés, assurez-vous que les cavaliers de résistance terminale du premier (généralement le panneau hybride) et des dispositifs BUS les plus éloignés sur une ligne BUS sont réglés sur ON pour servir de résistances de terminaison. Assurez-vous d'activer uniquement les 2 cavaliers susmentionnés et de ne pas régler les cavaliers sur ON pour tout autre périphérique BUS intermédiaire.

![](<.gitbook/assets/15 (5).png>)

_\\<NOTE>_

-   La conception enfichable des borniers BUS améliore l’efficacité de l’installation. Avant le câblage, vous pouvez retirer les borniers de la carte PCB pour faciliter l'utilisation et les rebrancher après le câblage.
-   Après avoir débranché le terminal, lors de la réinstallation du terminal sur la carte, assurez-vous d'installer le terminal dans la même direction pour éviter les dangers potentiels.

2

-   Des connexions incorrectes entraîneront une panne ou un dysfonctionnement. Inspectez le câblage et assurez-vous que les connexions sont correctes avant de mettre sous tension.

![](<.gitbook/assets/16 (8).png>)

-   _**Mise en route – Apprentissage du lecteur de balises filaire dans le panneau de configuration**_

Veuillez suivre les étapes ci-dessous pour intégrer l'appareil au panneau hybride.

**Étape 1.**Connectez l'appareil au panneau. Ensuite, allumez le panneau.

**Étape 2.**Sur la page Web du Panel, cliquez sur «**Apprentissage**» pour accéder à la page d'apprentissage.

**Étape 3.**Cliquez sur "**Commencer**» pour passer en mode apprentissage ; le lecteur d'étiquettes filaire s'affichera juste après que le panneau entre en mode d'apprentissage.

**Étape 4.**Cliquez sur "**Ajouter**» pour inclure l'appareil dans le panneau.

**Étape 5.**Si le périphérique est correctement appris dans le panneau, il sera affiché dans la section « Périphérique appris ».

![](<.gitbook/assets/17 (5).png>)

-   _**Identification**_

La fonction « Identifier » permet de localiser un périphérique BUS spécifique dans le système filaire BUS. Cette fonction est utile pour distinguer quel appareil est quel appareil, en particulier dans une grande installation où de nombreux appareils BUS sont inclus.

Pour localiser le lecteur d'étiquettes filaire dans le système BUS :

**Étape 1.**Sur la page Web de Hybrid Panel, cliquez sur « Identifier » sous la liste des appareils après l'entrée dans la colonne des appareils du Tag Reader.

**Étape 2.**Si le TG-15N-BUS reçoit le signal du panneau hybride, la page Web affichera un message de réussite et la LED verte du TG-15N-BUS clignotera 10 fois pour indiquer à l'utilisateur où il se trouve.

![](<.gitbook/assets/18 (8).png>)

_\\<NOTE>_

-   -   Si un message de délai d'attente s'affiche sur la page Web, cela signifie que le TG-15N-BUS n'a pas reçu le signal du panneau.

Veuillez vérifier si le TG-15N-BUS est correctement connecté au panneau à une distance de câblage appropriée.

-   _**Test de marche**_

![](<.gitbook/assets/19 (7).png>)

-   Pour vous assurer que le lecteur d'étiquettes filaire est capable de communiquer avec le panneau après son apprentissage, placez le panneau de commande en mode test de marche et appuyez sur le bouton d'apprentissage du TG-15N-BUS pour transmettre un signal de test au panneau de commande.

3

-   Lorsque le panneau reçoit le signal de test, il émet un bip et affiche les informations du lecteur en conséquence en haut de la liste des appareils.

![](<.gitbook/assets/20 (5).png>)

_\\<NOTE>_

-   -   S'il n'y a pas de réponse du panneau après avoir appuyé sur le bouton d'apprentissage, cela signifie que le panneau n'a pas reçu le signal de test de l'appareil.

Veuillez vérifier si le TG-15N-BUS est correctement connecté au panneau à une distance de câblage appropriée.

-   _**Montage du lecteur d'étiquettes filaire :**_

La base comporte trois découpes pour le montage. Pour monter le lecteur d'étiquettes filaire :

-   -   1.  Dévissez la vis de fixation.
        2.  Retirez le couvercle du Reader.
        3.  Montez le terminal BUS sur le PCB ; faites passer les fils à travers le trou de câblage du BUS comme indiqué sur la figure.
        4.  Brisez les trous sur la base.
    -   Utilisez les découpes comme gabarit et percez des trous dans la surface à monter.
        1.  Insérez les chevilles murales si l'appareil doit être fixé sur du plâtre ou des briques.
        2.  Vissez la base sur les chevilles.
    -   Remettez le couvercle sur la base et revissez la vis de fixation.

_**\\<NOTE>**_

-   -   Si le lecteur monté est retiré de force, la zone de séparation sera laissée sur le mur, séparée du lecteur, et l'autoprotection sera alors déclenchée.
-   _**Apprentissage/suppression de balises**_
    -   -   Avant d'apprendre une balise dans le panneau de commande, assurez-vous que le lecteur de balises filaire a été appris dans le panneau de commande.
        -   Après la première mise sous tension du lecteur d'étiquettes filaire, veuillez attendre 10 secondes pour que le lecteur active la fonction de capteur d'étiquette.
-   À_**Apprendre**_la balise dans le panneau de configuration :**Étape 1.**Désarmez le système.

**Étape 2.**Accédez à la page Web locale >**Code PIN**. Sélectionner**Zone**. Placez l'étiquette près de la zone de capteur et le lecteur enverra le numéro d'identification de l'étiquette au panneau de commande. Le Reader émettra 4 bips. Cliquez sur**Charger**bouton sur la page Web.

_**\\<NOTE>**_

-   -   Si l'étiquette a été apprise dans le système, lorsque vous placez l'étiquette près de la zone de capteur, elle émettra 2 bips et la LED verte s'allumera pendant 3 secondes pour passer en mode désarmement.

**Étape 3.**Lorsque le numéro d'identification de la balise est affiché sur la page Web, entrez un code utilisateur à 4 chiffres et attribuez un nom d'utilisateur à la balise.

4

**Étape 4.**Cliquez sur**D'ACCORD**sur la page Web pour enregistrer les paramètres.

**Étape 5.**L’apprentissage des balises est terminé.

-   À_**Retirer**_la balise du panneau de configuration :**Étape 1.**Désarmez le système.

**Étape 2.**Accédez à la page Web locale >**Code PIN**. Sélectionner**Zone**. Placez l'étiquette près de la zone de capteur et le lecteur enverra le numéro d'identification de l'étiquette au panneau de commande. Le Tag Reader émettra 2 bips et la LED verte s'allumera pendant 3 secondes. Recherchez une colonne de numéro d'étiquette vide et cliquez sur**Charger**pour vérifier le numéro d’identification du tag à supprimer.

_**\\<NOTE>**_

-   Si l'étiquette n'a pas été apprise dans le système, lorsque vous placez l'étiquette à proximité du lecteur d'étiquette filaire, celui-ci émettra 4 bips pour informer les utilisateurs du défaut.

**Étape 3.**En fonction du numéro d'identification du tag, recherchez le numéro d'identification du même tag dans la liste et cochez**Supprimer**.

-   **Exemple:**Comme le montrent les images, les numéros 1 et 2 de la liste sont les balises apprises existantes. Après avoir placé la balise près du lecteur et cliqué sur**Charger**dans la colonne vide n°3, le numéro d’identification de l’étiquette indiqué dans le n° 3 est le même que celui du n° 2, donc le n° 2 est l’étiquette à supprimer. Cocher**Supprimer**dans les colonnes n°2 et n°3 pour supprimer la balise.

**Étape 4.**Cliquez sur**D'ACCORD**sur la page Web pour enregistrer la modification.

**Étape 5.**La suppression du tag est terminée.

-   _**Opération:**_

Après avoir terminé l'apprentissage du tag dans le lecteur de tags filaire, vous pouvez maintenant basculer le système en mode Armer ou Désarmer :

1.  **Contrôle du mode de désarmement :**Appliquez l'étiquette à proximité de la zone de capteur en mode armé ; le lecteur émettra 2 bips lorsque le panneau recevra le signal de désarmement et passera avec succès en mode désarmement.
2.  **Contrôle du mode d'armement :**Appuyez une fois sur le bouton d'armement et la LED verte clignotera rapidement pendant 5 secondes ; puis appliquez l'étiquette près de la zone de capteur pendant ces 5 secondes, le lecteur d'étiquette émettra 1 bip long pour indiquer que le panneau a reçu avec succès la demande d'armement.
3.  **Flash LED :**Si le système est armé, la LED rouge s'allumera pendant 3 secondes. Une fois désarmé, la LED verte s'allumera pendant 3 secondes.
4.  **Altérer:**Lorsque le sabotage est déclenché, le lecteur d'étiquettes filaire transmet immédiatement un signal d'alarme de sabotage au panneau de commande et revient en mode veille.

5
