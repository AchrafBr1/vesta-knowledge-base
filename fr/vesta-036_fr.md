# VESTA 036

**Capteur de mouvement PIR extérieur immunisé contre les animaux (EIR-32)**

L'EIR-32, un détecteur PIR extérieur fonctionnant sur batterie, permet une installation extérieure économique et sans effort tout en offrant des capacités de détection exceptionnelles.

Le capteur intégré avec sensibilité de détection élimine le risque de fausses alarmes causées par de petits animaux ou d'autres perturbations extérieures.

La fonction anti-masquage permet de détecter toute tentative d'aveuglement du détecteur en plaçant des objets dans son champ de vision.

De plus, la plage de détection réglable s'adapte efficacement à chaque environnement d'installation, offrant une tranquillité d'esprit tout en protégeant vos locaux et vos proches toute l'année.

-   _**Identifier les pièces**_

**Vue de face****Vue de l'intérieur****Vue arrière**

![](<.gitbook/assets/0 (32).png>)

1.  **Détecteur de proximité numérique**

Le détecteur permet de détecter toute tentative de masquage (blocage) d'un intrus.

1.  **Indicateur LED**

L'indicateur LED est utilisé pour indiquer l'état du système.

1.  **Capteur IR**

Le capteur est destiné à détecter des objets en mouvement.

1.  **Bouton de test**

Le bouton Test est utilisé pour tester les performances de la radio et à des fins d'apprentissage.

1.  **Bloc de commutateur DIP**

Il y a 8 commutateurs DIP pour régler les niveaux de sensibilité de fonction et de détection.

1.  **Interrupteur anti-sabotage**

L'EIR-32 est protégé par l'interrupteur anti-sabotage contre tout retrait non autorisé de la plaque de montage ou de l'emplacement de montage.

1.  **Compartiment à piles**
2.  **Plaque de montage**
3.  **Zone de échappée**

La zone de séparation comporte 6 découpes (2 pour le montage en surface et 4 pour le montage en coin) où le plastique est plus fin pour le montage par vis. Lorsque le détecteur est retiré de force de l'emplacement de montage, la zone de rupture se détache et permet d'activer l'interrupteur anti-sabotage.

**10. Bouclier de protection**

L'écran de protection protège le détecteur de proximité numérique de la pluie.

-   _**Indicateur LED**_

En mode de fonctionnement normal, le voyant LED reste éteint sauf :

-   Lorsque le capteur de mouvement est en état de batterie faible, chaque fois qu'il transmet un mouvement détecté, la LED clignote pendant

1

6 fois.

-   -   Lorsque l'interrupteur anti-sabotage est déclenché, la LED clignote 6 fois pour indiquer qu'elle transmet "**Altérer**» signale-t-il.
    -   Lorsque la condition de sabotage persiste, chaque fois qu'il transmet un mouvement détecté, la LED clignote 6 fois.
    -   En mode Test, la LED clignote 6 fois chaque fois qu'un mouvement est détecté.
-   _**Mode d'essai**_

Le capteur de mouvement peut être mis en mode Test pendant 10 minutes en appuyant une fois sur le bouton Test. En mode Test, la minuterie de mise en veille est désactivée et l'indicateur LED peut s'allumer pendant deux secondes chaque fois qu'un mouvement est détecté. Le capteur de mouvement quittera automatiquement le mode test après 10 minutes et reviendra en mode normal.

Pour mettre le capteur de mouvement en mode test constant, veuillez régler le commutateur DIP 1 (veuillez vous référer à_Tableau de position des commutateurs DIP_).

-   _**Batterie**_
    -   Le capteur de mouvement utilise deux piles au lithium AAL91 comme source d'alimentation.
    -   Le capteur de mouvement dispose d'une détection de tension de batterie faible. Lorsqu'une batterie faible est détectée, un signal de batterie faible sera envoyé au panneau de commande avec des transmissions de signal régulières pour que le panneau de commande affiche l'état en conséquence.
    -   **Pour changer la batterie :**

**Étape 1:**Naviguez dans le panneau de commande en mode programmation.

**Étape 2:**Retirez le capteur de mouvement de la position de montage et dévissez pour ouvrir le capot supérieur.

**Étape 3:**Retirez les anciennes piles et appuyez sur le bouton anti-sabotage pendant quelques secondes pour les décharger complètement.

**Étape 4:**Insérez deux nouvelles piles au lithium AAL91.

**Étape 5 :**Revissez le capot supérieur.

**Étape 6 :**Remontez le capteur de mouvement sur l'emplacement de montage.

**Étape 7 :**Naviguez dans le panneau de commande pour quitter le mode de programmation et revenir au mode de fonctionnement. La procédure est terminée.

-   _**Signal de surveillance**_
    -   Après l'installation, le capteur de mouvement transmettra automatiquement et périodiquement des signaux de surveillance au panneau de commande à des intervalles aléatoires de 30 à 50 minutes.
    -   Si le panneau de commande n'a pas reçu le signal du capteur de mouvement pendant la période de temps prédéfinie, le panneau de commande indiquera sur son écran que le capteur de mouvement particulier rencontre un problème de manque de signal.
-   _**Minuterie de mise en veille**_

Le capteur de mouvement dispose d'un « temps de veille » automatique d'environ une minute pour économiser l'énergie. Après avoir transmis un mouvement détecté, le capteur de mouvement ne retransmettra pas pendant une minute. Tout autre mouvement détecté au cours de cette période de sommeil d’une minute prolongera la durée du sommeil d’une minute supplémentaire. De cette façon, un mouvement continu devant le capteur de mouvement n’épuisera pas indûment la batterie.

-   _**Double Knock Function**_

Le capteur de mouvement a une fonction double coup. Si la fonction double coup est activée, le capteur de mouvement signalera une alarme au panneau de commande uniquement si deux mouvements sont détectés dans les 10 secondes. Si la fonction double frappe est désactivée, le capteur de mouvement signalera une alarme au panneau de commande lorsqu'un mouvement est détecté.

-   _**Détection de proximité**_
    -   Le détecteur de mouvement dispose d'un détecteur de proximité numérique capable de détecter toute tentative de masquage (blocage) d'un intrus.
    -   Lorsqu'un événement de masquage est détecté et que la condition de masquage dure 2 minutes, l'EIR-32 enverra un signal d'ouverture au panneau de commande pour informer l'utilisateur de la condition.
    -   Une fois le masquage/blocage supprimé pendant 2 minutes, l'EIR-32 enverra un signal de restauration anti-sabotage au panneau de commande.

_\\<NOTE>_

-   -   Tout mouvement de déclenchement IR effacera l’événement/condition de masquage actuellement détecté. Un événement de masquage doit être détecté et durer 2 minutes pour que le rapport d'auto-ouverture soit transmis.
-   _**Tableau de position des commutateurs DIP**_

La fonction de chaque commutateur DIP est répertoriée dans le tableau ci-dessous. Le commutateur DIP est soit activé, soit désactivé. La position supérieure indique ON et la position inférieure indique OFF.

|   | TREMPER      |   |           | Position  |                                           |                                         | Fonction |   |   |
| - | ------------ | - | --------- | --------- | ----------------------------------------- | --------------------------------------- | -------- | - | - |
|   |              |   |           |           |                                           |                                         |          |   |   |
|   | Commutateur1 |   |           | SUR       |                                           | Mode d'essai                            |          |   |   |
|   |              |   | DÉSACTIVÉ |           | Mode normal (par défaut)                  |                                         |          |   |   |
|   |              |   |           |           |                                           |                                         |          |   |   |
|   | Commutateur2 |   |           | SUR       |                                           | Réservé                                 |          |   |   |
|   |              |   | DÉSACTIVÉ |           |                                           |                                         |          |   |   |
|   |              |   |           |           |                                           |                                         |          |   |   |
|   |              |   |           | SUR       |                                           | PIR face à un mur dans un rayon de 10 m |          |   |   |
|   | Commutateur3 |   |           | DÉSACTIVÉ |                                           | PIR face à un espace ouvert             |          |   |   |
|   |              |   |           |           | (pas de mur à moins de 10 m) (par défaut) |                                         |          |   |   |
|   |              |   |           |           |                                           |                                         |          |   |   |
|   |              |   |           | SUR       |                                           | PIR face à une pelouse (par défaut)     |          |   |   |
|   | Commutateur4 |   |           | DÉSACTIVÉ |                                           | PIR face à un béton/pierre              |          |   |   |
|   |              |   |           | sol       |                                           |                                         |          |   |   |
|   |              |   |           |           |                                           |                                         |          |   |   |
|   |              |   |           |           |                                           |                                         |          |   |   |

![](<.gitbook/assets/1 (36).png>)

|   |              | TREMPER |           |              | Niveau de sensibilité                              |                                             |          |   |   |
| - | ------------ | ------- | --------- | ------------ | -------------------------------------------------- | ------------------------------------------- | -------- | - | - |
|   |              |         |           |              |                                                    |                                             |          |   |   |
|   | Commutateur5 |         |           | Commutateur6 |                                                    |                                             |          |   |   |
|   | SUR          |         |           | SUR          |                                                    | Faible; Animal de 60 kg (par défaut)        |          |   |   |
|   | SUR          |         |           | DÉSACTIVÉ    |                                                    | Moyen; animal de 35 kg                      |          |   |   |
|   | DÉSACTIVÉ    |         |           | SUR          |                                                    | Haut; animal de 20 kg                       |          |   |   |
|   | DÉSACTIVÉ    |         |           | DÉSACTIVÉ    |                                                    | Réservé                                     |          |   |   |
|   |              |         |           |              |                                                    |                                             |          |   |   |
|   | TREMPER      |         |           | Position     |                                                    |                                             | Fonction |   |   |
|   | Commutateur7 |         |           | SUR          |                                                    | Activer le double coup (par défaut)         |          |   |   |
|   |              |         | DÉSACTIVÉ |              | Désactivation du double coup                       |                                             |          |   |   |
|   |              |         |           |              |                                                    |                                             |          |   |   |
|   | Commutateur8 |         |           | SUR          |                                                    | Activer l'immunité aux animaux (par défaut) |          |   |   |
|   |              |         | DÉSACTIVÉ |              | Désactivation immunitaire des animaux de compagnie |                                             |          |   |   |
|   |              |         |           |              |                                                    |                                             |          |   |   |

![](<.gitbook/assets/2 (42).png>)

SUR

![](<.gitbook/assets/3 (40).png>)

DÉSACTIVÉ

_**\\<NOTE>**_

-   Après avoir modifié les paramètres du commutateur Dip, veuillez rallumer l'EIR-32 pour qu'il fonctionne avec les nouveaux paramètres du commutateur Dip.

2

-   _**Autoprotection**_
    -   L'EIR-32 est protégé par un interrupteur anti-sabotage qui est comprimé lorsqu'il est accroché au support de montage.
    -   Chaque fois que le capteur de mouvement est retiré de la plaque de montage, l'interrupteur anti-sabotage sera activé.
    -   Lorsque le capteur de mouvement est retiré de force de l'emplacement de montage, la zone Break Away de la plaque de montage se détache, permettant également d'activer l'interrupteur anti-sabotage.
    -   Le capteur de mouvement enverra un signal d'autoprotection pour rappeler à l'utilisateur la condition chaque fois que l'interrupteur d'autoprotection est activé.
-   _**Mise en route – Apprentissage du capteur de mouvement dans le panneau de commande**_
    -   Desserrez les vis de fixation et retirez le couvercle.
    -   En fonction de vos besoins, réglez le commutateur de sensibilité comme indiqué dans_Tableau de position des commutateurs DIP_.
    -   Insérez deux piles au lithium AAL91 dans le support de pile en prenant soin de connecter correctement la polarité.
    -   L'indicateur LED clignote pendant 60 secondes. Le capteur de mouvement chauffe. Pendant la période de réchauffement, le capteur de mouvement n'est pas activé. Il est recommandé de rester à l'écart de la zone de détection pendant cette période. Une fois la période de réchauffement terminée, la LED s'éteint et le détecteur de mouvement est prêt à fonctionner.
    -   Mettez le panneau de commande en mode apprentissage, reportez-vous au manuel du panneau de commande pour plus de détails.
    -   Appuyez une fois sur le bouton Test. L'indicateur LED clignotera trois fois.
    -   Si le panneau de commande reçoit le signal, il affichera les informations en conséquence. Reportez-vous au manuel du panneau de commande pour terminer le processus d'apprentissage. (Pour certains modèles de panneau de commande, le capteur de mouvement peut être appris comme un PIR ordinaire avec des attributs programmables et ainsi le panneau de commande signalera lorsqu'une alarme est déclenchée).
    -   Une fois le capteur de mouvement appris, mettez le panneau de commande en mode test de marche. Maintenez le capteur de mouvement à l'emplacement souhaité et appuyez sur le bouton Test pour confirmer que cet emplacement se trouve dans la plage de signal du panneau de commande.
    -   Lorsque vous êtes convaincu que le capteur de mouvement fonctionne à l'emplacement choisi, vous pouvez procéder à l'installation.

_\\<NOTE>_

-   -   -   **Test de marche**doit être effectuée pour confirmer le bon fonctionnement et la couverture du capteur de mouvement.
        -   Lors de l'apprentissage du capteur de mouvement ou de la réalisation d'un test de marche, évitez d'obstruer le détecteur anti-masquage avec votre main, sinon le signal d'ouverture sera transmis au panneau de commande si la condition de masquage dure 2 minutes.
-   _**Méthode de montage et d'installation**_
    -   **Montage avec plaque de montage :**
        -   -   Le capteur de mouvement est conçu pour être monté sur une surface plane ou dans un coin avec les vis de fixation et les chevilles fournies.
            -   La plaque de montage fournie comporte des découpes dans lesquelles le plastique est plus fin et peut être cassé à des fins de montage. Deux découpes sont destinées à la fixation en surface et quatre sont destinées à la fixation en coin, comme indiqué sur l'image.
            -   Pour monter l'EIR-32 avec le support de montage :
                1.  Utilisez la plaque de montage comme modèle pour percer des trous dans le mur pour les fiches.
                2.  Enfoncez les chevilles et fixez la plaque de montage au mur avec les vis.
                3.  Montez l'EIR-32 avec les crochets de la plaque de montage verrouillés sur le capot arrière de l'EIR-32, puis poussez vers le bas jusqu'à ce que vous entendiez un clic pour verrouiller le crochet.
                4.  Insérez l'écran de protection (le film protecteur des deux côtés doit d'abord être retiré).

![](<.gitbook/assets/4 (26).jpeg>)![](<.gitbook/assets/5 (34).png>)

3

-   **Montage avec plaque de montage et support rotatif (en option) :**
    -   Un support rotatif est fourni comme option de montage conviviale**(article en option, vendu séparément)**. Il est composé d'une base à fixer à la surface et d'une boule pivotante à fixer à la plaque de montage et à l'EIR-32.

![](<.gitbook/assets/6 (23).jpeg>)

-   Grâce au support rotatif, l'EIR-32 peut être tourné horizontalement pour offrir une couverture optimale.

Un tournevis spécial avec embout double face réversible et trois vis à douille étoile sont fournis pour fixer le support rotatif au mur.

![](<.gitbook/assets/7 (18).png>)

Veuillez utiliser le tournevis fourni pour serrer/desserrer les vis à douille étoile.

![](<.gitbook/assets/8 (21).png>)

-   Pour monter l'EIR-32 avec la plaque de montage et le support rotatif :
    1.  Fixez le support rotatif au mur avec les vis fournies.
    2.  Fixez la plaque de montage sur la boule pivotante avec la vis de fixation fixée à travers le trou de conception infaillible.
    3.  Montez l'EIR-32 avec les crochets de la plaque de montage verrouillés sur le capot arrière de l'EIR-32, puis poussez vers le bas jusqu'à ce que vous entendiez un clic pour verrouiller le crochet.
    4.  Insérez l'écran de protection (le film protecteur des deux côtés doit d'abord être retiré).

![](<.gitbook/assets/9 (20).png>)

4

1.  Faites pivoter la boule pivotante horizontalement pour ajuster l'angle de détection de l'EIR-32. (Lorsque la vis de réglage de l'angle est à moitié desserrée, la boule pivotante peut toujours tourner.)
2.  Lorsque l'EIR-32 est tourné vers une position avec la couverture de détection souhaitée, vous pouvez verrouiller la position en serrant fermement la vis de réglage de l'angle.

![](<.gitbook/assets/10 (10).jpeg>)

_\\<NOTE>_

-   -   Une fois l'EIR-32 monté, si le panneau de commande affiche l'état de défaut de sabotage de l'appareil, veuillez vous assurer que le détecteur anti-masquage n'est obstrué par aucun objet et attendez deux minutes pour voir si l'état de sabotage ouvert est effacé. Si l'état d'autoprotection persiste après deux minutes, veuillez retirer l'EIR-32 de l'emplacement de montage et vérifier si l'interrupteur d'autoprotection est correctement comprimé contre la plaque de montage.
-   _**Recommandations d'installation**_

**Il est recommandé d'installer le capteur de mouvement aux emplacements suivants :**

![](<.gitbook/assets/11 (14).png>)

-   À une hauteur de 2 mètres (mesurée à partir du bas du capteur de mouvement) au-dessus du sol pour de meilleures performances.
-   Dans un coin pour une vue plus large.
-   Là où un intrus se déplacerait normalement dans le champ de vision du capteur de mouvement.
-   Sur une surface ou dans un coin où les animaux sont inaccessibles.
-   Le capteur de mouvement a une portée de détection de 10 M lorsqu'il est monté à une hauteur de 2 mètres au-dessus du sol.

**Limites:**

-   N'exposez pas complètement le capteur de mouvement à la lumière directe du soleil.
-   Évitez les gros obstacles dans la zone de détection.
-   Ne faites pas face à des sources de chaleur telles que des incendies et des chaudières, et n'installez pas au-dessus des radiateurs.
-   N'essayez jamais de démonter ou de modifier l'appareil.
-   Veuillez installer le capteur de mouvement vers le haut. Ne l'inclinez pas.

![](<.gitbook/assets/12 (11).jpeg>)

-   N'installez pas le capteur de mouvement à proximité d'objets déplacés par le vent, tels que des arbres et du linge, car cela pourrait bloquer le champ de vision du capteur de mouvement.

![](<.gitbook/assets/13 (11).jpeg>)

5

-   Éliminez toutes les surfaces réfléchissant la lumière de la zone de détection, ainsi que les flaques d'eau.

![](<.gitbook/assets/14 (12).jpeg>)

-   Évitez de viser le chemin du flux d’air d’admission ou d’évacuation de l’unité extérieure.

![](<.gitbook/assets/15 (9).jpeg>)

_\\<IMPORTANT NOTE>_

-   Ajustez les commutateurs Dip en fonction de l'emplacement d'installation du capteur de mouvement pour des performances idéales. Si les paramètres du commutateur Dip ne correspondent pas à l'environnement d'installation, les performances du capteur de mouvement seront entravées et peuvent provoquer une fausse alarme ou une incapacité à détecter un mouvement.
-   Le capteur de mouvement détecte les différences entre l'objet en mouvement et l'arrière-plan. Si l'objet est stationnaire (c'est-à-dire ne bouge pas), le capteur de mouvement est incapable de le détecter.
-   Le capteur de mouvement a une caractéristique directionnelle et est le plus efficace pour détecter les intrus se déplaçant dans le champ de détection. Il est moins sensible pour détecter les mouvements directement vers le capteur de mouvement.
-   Pour de meilleures performances, n'oubliez pas d'ajuster la hauteur de montage du détecteur de mouvement par rapport à la hauteur de l'animal le plus grand de la maison. Les chiens plus grands nécessitent que le capteur de mouvement soit monté plus haut pour plus de convivialité.
-   Le détecteur de mouvement présente un angle mort d'environ 1 mètre en dessous lorsqu'il est monté à une hauteur de 2 mètres. La zone d'angle mort s'agrandit si vous montez le capteur de mouvement à une hauteur supérieure à 2 M et diminue si elle est inférieure à 2 M.
-   Sauf indication contraire, nous vous suggérons de conserver l'emplacement de montage du capteur de mouvement à 2 M pour des performances optimales. Si vous modifiez la hauteur de montage, veuillez effectuer un test de détection pour vous assurer que le capteur de mouvement peut détecter normalement un intrus à la hauteur souhaitée.

6
