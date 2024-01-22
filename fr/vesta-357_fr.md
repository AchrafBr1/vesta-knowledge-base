# VESTA 357

**Caméra filaire extérieure à capteur de mouvement PIR (VST-892EX-BUS)**

VST-892EX-BUS est une caméra filaire extérieure à capteur de mouvement infrarouge passif (PIR). Il est capable d'envoyer des signaux filaires et des images capturées (qualité d'image jusqu'à 640 x 480 pixels) via BUS au panneau de commande lors de la détection de mouvement.

Doté d'une capacité d'éclairage nocturne, d'un boîtier résistant aux UV et étanche selon la norme IPX6, le VST-892EX-BUS est idéal pour les cours arrière, les pelouses, les portails, les couloirs extérieurs et les couloirs.

La caméra PIR extérieure est conçue avec une portée de détection typique de 10 mètres lorsqu'elle est montée à une hauteur de 2,3 mètres au-dessus du sol. Il offre une immunité aux animaux pesant jusqu'à 60 kilos avec trois niveaux de sensibilité sélectionnables pour s'adapter à différents environnements.

De plus, le VST-892EX-BUS est conçu avec le détecteur de proximité numérique. La fonction anti-masquage permet de détecter toute tentative d'aveuglement du détecteur en plaçant des objets dans son champ de vision.

La configuration à distance est prise en charge pour la caméra à capteur de mouvement PIR. Outre le réglage du commutateur DIP, les utilisateurs peuvent également activer/désactiver la fonction double coup et l'immunité aux animaux, et régler la sensibilité de la caméra PIR à partir de la page Web du panneau de commande ou du serveur du portail domestique.

![](<.gitbook/assets/0 (2).png>)

-   _**Identifier les pièces**_

![](<.gitbook/assets/1 (1) (1).jpeg>)

1.  **Détecteur de proximité numérique**

Le détecteur de proximité numérique permet de détecter toute tentative de masquage (blocage) d'un intrus.

1.  **Indicateur LED (rouge)**

L'indicateur LED est utilisé pour indiquer l'état du système.

1.  **LED clignotante**

Le Flash LED fournit suffisamment de lumière pour capturer des images dans des conditions de faible éclairage.

1.  **Capteur IR**

Le capteur est destiné à détecter des objets en mouvement.

-   1.  **Objectif de caméra PIR**

1.  **Autoprotection interne**
2.  **Bouton Test et apprentissage**

\-Appuyez une fois sur le bouton pour passer en mode test pendant 10 minutes.

1.  **Bloc de commutateur DIP**

Il y a 8 commutateurs DIP pour régler les niveaux de sensibilité de fonction et de détection.

1.  **Commutateur de cavalier de résistance de borne**

Lorsque la caméra à capteur de mouvement PIR est connectée en tant que périphérique BUS le plus éloigné sur une ligne BUS, veuillez régler le cavalier de résistance terminal de la caméra à capteur de mouvement PIR et le commutateur de cavalier du premier périphérique BUS (généralement le panneau hybride) sur ON pour servir de résistances de terminaison. . La capacité de communication de la ligne BUS connectée sera améliorée.

![](<.gitbook/assets/2 (1) (1).jpeg>)![](<.gitbook/assets/3 (3).png>)

**Cavalier**

![](<.gitbook/assets/4 (1).jpeg>)

Le cavalier est inséré, reliant les deux broches.

**Cavalier**

Le lien de cavalier est supprimé ou "**garé**» sur une épingle.

-   -   Si le cavalier est désactivé, la capacité de communication est au niveau normal.
    -   Si le cavalier est activé, la capacité de communication sera améliorée.

1.  **Terminal de bus**

1

1.  **Trou de câblage BUS**
2.  **Support de montage**
3.  **Crochets**
4.  **Trous de montage**

![](<.gitbook/assets/5 (3).png>)

-   _**Indicateur LED**_

Lorsqu'il est activé, l'indicateur LED s'allume dans les conditions suivantes :

-   Lorsque la caméra PIR est dans des conditions de défaut (inviolabilité ou conditions de masquage continu), chaque fois qu'elle transmet un mouvement détecté, la LED clignote une fois.
-   Après avoir appuyé une fois sur le bouton de test pour passer en mode test, la LED clignote pendant 60 secondes pour indiquer que la caméra à capteur de mouvement PIR est en train de se réchauffer.
-   En mode Test, la LED clignote une fois chaque fois qu'un mouvement est détecté.

La LED ne clignotera pas si la caméra PIR est normale et n'est pas en mode test.

![](<.gitbook/assets/6 (1) (1).png>)

_\\<NOTE>_

-   -   L'indicateur LED peut être activé en réglant le commutateur DIP 2 sur la position ON. Prière de se référer à**Tableau de position des commutateurs DIP**ci-dessous pour plus de détails.
-   _**Capture d'image**_

![](<.gitbook/assets/7 (2).png>)

Lorsque le système d'alarme est armé, la caméra PIR capturera 1, 3 ou 6 images d'alarme avec une résolution de 640 x 480 ou 320 x 240 (programmable depuis le panneau de commande) lors de la détection de mouvement. Vous pouvez également demander manuellement à la caméra PIR de prendre une photo via le panneau de configuration. Les images capturées seront transférées au panneau de commande pour vérification visuelle des alarmes.

![](<.gitbook/assets/8 (3).png>)

_\\<NOTE>_

-   -   Si votre caméra PIR est installée à un endroit où le champ de vision de la caméra est un environnement complexe avec une lumière intense ou beaucoup de couleurs, les images capturées seront de grande taille, ce qui pourrait entraîner une troncature lorsque les images sont transmises au panneau de commande. .
-   _**Période d'échauffement**_

![](<.gitbook/assets/9 (3).png>)

La caméra PIR se réchauffe pendant 60 secondes lorsqu'elle est allumée par le panneau de commande lors de l'entrée en mode armé.

![](<.gitbook/assets/10 (3).png>)

-   _**Mode d'essai**_
    -   La caméra PIR peut être mise en mode Test pendant 10 minutes en appuyant une fois sur le bouton test.
    -   En mode test, les fonctions de capture d'image sont désactivées. L'indicateur LED clignote une fois chaque fois qu'un mouvement est détecté.
    -   La caméra PIR quittera automatiquement le mode test après 10 minutes et reviendra en mode normal.
    -   En mode test, l'indicateur LED doit être activé en réglant le commutateur DIP 2 sur la position ON, et la fonction Double Knock doit être désactivée en réglant le commutateur DIP 7 sur la position OFF, pour que les utilisateurs puissent tester la plage de détection.
-   _**Fonction double coup**_
    -   La caméra PIR a une fonction double coup. Si la fonction double coup est activée, la caméra PIR signalera une alarme au panneau de commande uniquement si deux mouvements sont détectés dans les 10 secondes. Si la fonction double coup est désactivée, la caméra PIR signalera une alarme au panneau de commande lorsqu'un mouvement est détecté.
-   _**Tableau de position des commutateurs DIP**_

![](<.gitbook/assets/11 (2).png>)![](<.gitbook/assets/12 (3).png>)

La fonction de chaque commutateur DIP est répertoriée dans le tableau ci-dessous. Le commutateur DIP est soit activé, soit désactivé. La position supérieure indique ON et la position inférieure indique OFF.

![](<.gitbook/assets/13 (3).png>)

Position DIP

Allumer

1 OFF

Allumer

2 ARRÊT

Fonction

Mode d'essai

Mode normal (par défaut)

Indicateur LED activé (par défaut)

Indicateur LED désactivé

| TREMPER       | Niveau de sensibilité |                                     |           |   |
| ------------- | --------------------- | ----------------------------------- | --------- | - |
| Commutateur 5 | Commutateur 6         |                                     |           |   |
| SUR           | SUR                   | Faible; animal de 60 kg             | SUR       |   |
| SUR           | DÉSACTIVÉ             | Moyen; Animal de 35 kg (par défaut) |           |   |
| DÉSACTIVÉ     | SUR                   | Haut; animal de 20 kg               | DÉSACTIVÉ |   |
|               |                       |                                     |           |   |

![](<.gitbook/assets/14 (2).png>)

Changer

3

SUR

DÉSACTIVÉ

SUR

Caméra PIR face à un mur dans un rayon de 10 m

Caméra PIR face à un espace ouvert (pas de mur à moins de 10 m) (par défaut)

Caméra PIR face à une pelouse

| DÉSACTIVÉ     | DÉSACTIVÉ | Réservé                      |   |
| ------------- | --------- | ---------------------------- | - |
| TREMPER       | Position  | Fonction                     |   |
|               | SUR       | Détection de double coup     |   |
| Commutateur 7 | (défaut)  |                              |   |
|               |           |                              |   |
|               | DÉSACTIVÉ | Détection normale            |   |
| Commutateur 8 | SUR       | Immunité aux animaux activée |   |
|               |           |                              |   |

Changer

4 ARRÊT

(défaut)

Caméra PIR face à un

sol en béton/pierre

OFF Immunité aux animaux désactivée (par défaut)

_\\<NOTE>_

-   Après avoir modifié les paramètres du commutateur Dip, veuillez rallumer la caméra PIR pour appliquer les nouveaux paramètres du commutateur Dip.

![](.gitbook/assets/15.jpeg)

2

-   ![](<.gitbook/assets/16 (3).png>)_**Réglage à distance**_
    -   La caméra à capteur de mouvement PIR prend en charge le réglage à distance de la fonction double coup, de la sensibilité et de l'immunité aux animaux.
    -   Lorsque la caméra PIR est allumée, sa fonction double coup est déterminée par le réglage DIP SW7, la sensibilité est déterminée par DIP SW5 et SW6 et l'immunité aux animaux est déterminée par DIP SW8. Les utilisateurs peuvent soit ajuster les paramètres du commutateur DIP, soit modifier à distance les paramètres de la fonction double frappe, de la sensibilité et de l'immunité aux animaux domestiques sur la page Web du panneau de commande ou sur le serveur du portail d'accueil. Le réglage à distance écrasera les paramètres du commutateur DIP.

**Page Web du panneau de configuration**:

-   -   1.  Sur la page Web locale du panneau, accédez à la page Modifier l'appareil et saisissez la configuration de la caméra PIR dans la section Paramètres du capteur. Cliquez sur OK pour confirmer.

Veuillez vous référer au tableau ci-dessous pour les détails de configuration. Par exemple, si vous souhaitez désactiver la fonction double frappe et régler le niveau de sensibilité sur Faible, vous pouvez saisir 00.

| **Configuration IR** | **Double coup** | **Sensibilité**                 | **Immunité aux animaux** |
| -------------------- | --------------- | ------------------------------- | ------------------------ |
| 00                   | Non             | Faible                          | Oui                      |
| 20                   | Non             | Moyen                           | Oui                      |
| 40                   | Non             | Haut                            | Oui                      |
| 60                   | Non             | Immunité aux animaux désactivée | Non                      |
| 80                   | Oui             | Faible                          | Oui                      |
| A0                   | Oui             | Moyen                           | Oui                      |
| C0                   | Oui             | Haut                            | Oui                      |
| E0                   | Oui             | Immunité aux animaux désactivée | Non                      |

**Serveur de portail domestique**:

-   -   -   1.  Sur Home Portal Server, accédez à la page Paramètres du périphérique, cliquez sur la ligne du périphérique VST-892EX et sélectionnez « Configuration IR ».
            2.  Sélectionnez la fonction Double Knock (Activer/Désactiver), la Sensibilité (Élevée/Moyenne/Faible) et l'immunité aux animaux (Activer/Désactiver) dans le menu déroulant, puis cliquez sur « Soumettre » pour confirmer le paramètre.
-   _**Signal de surveillance**_
    -   -   Après l'installation, la caméra PIR transmettra automatiquement et périodiquement des signaux de surveillance au panneau de commande à des intervalles aléatoires de 20 à 30 secondes.
-   _**Autoprotection**_
    -   -   La caméra PIR est protégée par un interrupteur anti-sabotage interne qui est comprimé lorsque la caméra PIR est accrochée au support de montage. Lorsque la caméra PIR est retirée du support de montage, le commutateur d'autoprotection sera activé et la caméra PIR enverra un signal d'autoprotection au panneau de commande pour rappeler à l'utilisateur cette condition.
-   _**Anti-masquage**_
    -   -   La caméra PIR dispose d'un détecteur de proximité numérique capable de détecter toute tentative de masquage (blocage) d'un intrus.
        -   Lorsqu'un événement de masquage est détecté et que la condition de masquage dure 3 minutes, le VST-892EX-BUS enverra un signal d'alarme de masquage au panneau de commande pour informer l'utilisateur de la condition de masquage.
        -   Une fois le masquage/blocage supprimé pendant 3 minutes, le VST-892EX-BUS enverra un signal de restauration au panneau de commande.
-   _**Source de courant**_
    -   -   Lorsque le VST-892EX-BUS est câblé à un panneau hybride, une alimentation de 13,5 V peut être fournie par le panneau hybride.
-   _**Prudence**_![](.gitbook/assets/17.jpeg)
    -   Le câblage de la caméra PIR ne doit être effectué que par des techniciens certifiés possédant les connaissances et la formation appropriées en matière d'équipement électrique.
    -   Avant l'installation ou tout travail de maintenance, assurez-vous que l'alimentation électrique a été débranchée.
-   _**Câblage de la caméra PIR extérieure**_
    -   -   Avant de connecter la caméra PIR au bus système, veuillez couper l'alimentation.
        -   Pour faciliter les connexions des câbles, les borniers de chaque module du système BUS sont codés par couleur.

![](<.gitbook/assets/18 (3).png>)![](<.gitbook/assets/19 (3).png>)![](<.gitbook/assets/20 (2).png>)

| **Rouge** | VDD  |
| --------- | ---- |
| **Noir**  | GND  |
| **Jaune** | 485A |
| **Vert**  | 485B |

-   Plusieurs appareils BUS peuvent être connectés en série au panneau hybride. Pour une communication optimale des dispositifs de ligne BUS connectés, assurez-vous que les cavaliers de résistance terminale du premier (généralement le panneau hybride) et des dispositifs BUS les plus éloignés sur une ligne BUS sont réglés sur ON pour servir de résistances de terminaison. Assurez-vous d'activer uniquement les 2 cavaliers susmentionnés et de ne pas régler les cavaliers sur ON pour tout autre périphérique BUS intermédiaire.

_\\<NOTE>_

-   La conception enfichable des borniers BUS améliore l'efficacité de l'installation. Avant le câblage, vous pouvez retirer les borniers de la carte PCB pour faciliter l'utilisation et les rebrancher après le câblage.

3

-   -   Après avoir débranché le terminal, lors de la réinstallation du terminal sur la carte, assurez-vous d'installer le terminal dans la même direction pour éviter les dangers potentiels.
-   Des connexions incorrectes entraîneront une panne ou un mauvais fonctionnement. Inspectez le câblage et assurez-vous que les connexions sont correctes avant de mettre sous tension.
-   _**Mise en route – Apprentissage de la caméra PIR dans le panneau de commande**_

Veuillez suivre les étapes ci-dessous pour intégrer l'appareil au panneau hybride.

Étape 1. Connectez l'appareil au panneau. Ensuite, allumez le panneau.

Étape 2. Sur la page Web du Panel, cliquez sur «**Apprentissage**» pour accéder à la page d'apprentissage.

Étape 3. Cliquez sur «**Commencer**» pour passer en mode apprentissage.

Étape 4. Cliquez sur «**Add**» pour inclure l'appareil dans le panneau.

Étape 5. Si le périphérique est correctement appris dans le panneau, il sera affiché dans la section « Périphérique appris ».

-   _**Identification**_

Le "**Identifier**La fonction " est utilisée pour localiser un périphérique BUS spécifique dans le système filaire BUS. Cette fonction est utile pour distinguer quel appareil est quel appareil, en particulier dans une grande installation où de nombreux appareils BUS sont inclus.

Pour localiser la caméra PIR dans le système BUS :

**Étape 1.**Sur la page Web du panneau hybride, cliquez sur « Identifier » sous la liste des appareils après l'entrée dans la colonne des appareils de la caméra infrarouge.

**Étape 2.**Si la caméra PIR reçoit le signal du panneau hybride, la page Web affichera un message de réussite et l'indicateur LED de la caméra PIR clignotera 10 fois pour indiquer à l'utilisateur où elle se trouve.

_\\<NOTE>_

-   -   -   Si un message de délai d'attente s'affiche sur la page Web, cela signifie que la caméra PIR n'a pas reçu le signal du panneau.

Veuillez vérifier si la caméra PIR est correctement connectée au panneau à une distance de câblage appropriée.

-   _**Test de marche**_
    -   Pour vous assurer que la caméra PIR est capable de communiquer avec le panneau après son apprentissage, placez le panneau de commande en mode test de marche et appuyez sur le bouton de test du VST-892EX-BUS pour transmettre un signal de test au panneau.
    -   Lorsque le panneau reçoit le signal de test, il émet un bip et affiche les informations de la caméra PIR en conséquence en haut de la liste des appareils.

_\\<NOTE>_

-   -   -   S'il n'y a pas de réponse du panneau après avoir appuyé sur le bouton de test, cela signifie que le panneau n'a pas reçu le signal de test de l'appareil.

Veuillez vérifier si la caméra PIR est correctement connectée au panneau à une distance de câblage appropriée.

-   _**Méthode de montage et d'installation**_
    -   **Montage avec le support de montage :**
        -   -   La caméra PIR peut être montée sur une surface plane avec les vis de fixation, les chevilles murales et le support de montage fourni.
            -   Le support de montage fourni comporte des ouvertures défonçables, où le plastique est plus fin et peut être cassé pour le montage

4

but.

-   Pour monter le VST-892EX-BUS avec le support de montage :
    1.  Utilisez le support de montage comme gabarit et percez 2 trous dans le mur pour les chevilles.
    2.  Insérez les chevilles murales et fixez le support de montage au mur avec les vis.
    3.  Accrochez le VST-892EX-BUS au support de montage, puis**poussez vers le bas jusqu'à ce que vous entendiez un clic**.

_\\<NOTE>_

-   Veuillez vous assurer que la caméra PIR est correctement accrochée au support de montage, de sorte que l'interrupteur anti-sabotage interne soit complètement enfoncé.
-   **Montage avec le support de montage et le support rotatif :**

Un support rotatif est fourni comme option de montage conviviale**(article en option, vendu séparément)**. Il est composé d'une base à fixer sur une surface et d'une boule pivotante pour fixer le support de montage au support rotatif.

Grâce au support rotatif, la caméra PIR peut être tournée horizontalement pour offrir une couverture optimale.

Un tournevis spécial avec un embout double face réversible et trois vis à douille étoile sont fournis pour fixer le support rotatif au mur. Veuillez utiliser le tournevis fourni pour serrer/desserrer les vis à douille étoile.

5

-   -   Pour monter le VST-892EX-BUS avec le support de montage et le support rotatif :

1.  Fixez le support rotatif au mur avec les vis fournies.
2.  Fixez le support de montage sur la boule pivotante avec la vis de fixation fixée à travers le trou de conception infaillible.
3.  Accrochez le VST-892EX-BUS au support de montage, puis poussez vers le bas jusqu'à ce que vous entendiez un clic.
4.  Faites pivoter la boule pivotante horizontalement pour ajuster l'angle de détection du VST-892EX-BUS. (Lorsque la vis de réglage de l'angle est à moitié desserrée, la boule pivotante peut toujours tourner.)
5.  Lorsque le VST-892EX-BUS est tourné vers une position offrant la couverture de détection souhaitée, vous pouvez verrouiller la position en serrant fermement la vis de réglage de l'angle.

-   _**Recommandations d'installation**_

**Il est recommandé d'installer la caméra PIR aux emplacements suivants :**

-   À une hauteur de 2,3 mètres (mesurée à partir du bas de la caméra) au-dessus du niveau du sol pour de meilleures performances
-   Dans un coin pour une vue plus large
-   À un endroit où un intrus se déplacerait normalement dans le champ de vision de la caméra PIR
-   Sur une surface ou dans un coin où les animaux sont inaccessibles
-   La caméra PIR a une portée de détection de 10 mètres lorsqu'elle est montée à une hauteur de 2,3 mètres au-dessus du sol.

**Plage de détection 892EX-BUS**

6

**Limites:**

-   -   N'exposez pas complètement la caméra PIR à la lumière directe du soleil.
    -   Évitez les gros obstacles dans la zone de détection.
    -   Ne faites pas face à des sources de chaleur telles que des incendies et des chaudières, directement ou installez-les au-dessus des radiateurs.
    -   N'essayez jamais de démonter ou de modifier l'appareil.
-   Veuillez installer la caméra PIR directement. Ne l'inclinez pas.
-   N'installez pas la caméra à capteur de mouvement là où des objets sont déplacés par le vent, tels que des arbres et du linge, car cela pourrait bloquer le champ de vision de la caméra à capteur de mouvement.

7

_\\<IMPORTANT NOTE>_

-   Ajustez les commutateurs Dip en fonction de l'emplacement d'installation de la caméra PIR pour des performances idéales. Si les paramètres du commutateur Dip ne correspondent pas à l'environnement d'installation, les performances de la caméra PIR seront entravées et pourraient provoquer une fausse alarme ou une incapacité à détecter un mouvement.
-   La caméra PIR détecte les différences entre l'objet en mouvement et l'arrière-plan. Si l'objet est inactif (c'est-à-dire ne bouge pas), la caméra PIR est incapable de le détecter.
-   La caméra PIR a une caractéristique directionnelle et est la plus efficace pour détecter les intrus se déplaçant dans son champ de détection. Il est moins sensible pour détecter les mouvements directement devant la caméra PIR.
-   Pour de meilleures performances, n'oubliez pas d'ajuster la hauteur de montage de la caméra à détecteur de mouvement par rapport à la hauteur de l'animal le plus grand de la maison. Les chiens plus grands nécessitent que la caméra à capteur de mouvement soit montée plus haut pour plus de convivialité.
-   La caméra PIR présente un angle mort d'environ 1 mètre sous la caméra lorsqu'elle est montée à une hauteur de 2,3 mètres. La zone d'angle mort s'agrandit si la caméra PIR est montée à une hauteur supérieure à 2,3 mètres, et diminue si elle est montée à une hauteur inférieure à cette hauteur.
-   Sauf nécessité, il est suggéré de maintenir l'emplacement de montage de la caméra PIR à une hauteur de 2,3 mètres pour des performances optimales. Si vous modifiez la hauteur de montage, veuillez effectuer un test de détection pour vous assurer que la caméra PIR peut normalement détecter les intrus à la hauteur choisie.

8
