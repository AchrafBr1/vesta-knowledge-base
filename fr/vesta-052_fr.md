# VESTA 052

-   POVS-1-ZW
-   Capteur d'occupation/vacance PIR
-   Introduction

POVS-1-ZW est un capteur de mouvement infrarouge passif Z-Wave. Il est capable d'envoyer des signaux sans fil au coordinateur du réseau Z-Wave lors de la détection de mouvement. Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance. Les capteurs de mouvement infrarouges passifs Z-Wave permettent d'accéder à la classe « S2 non authentifié » et prennent en charge l'inclusion Z-Wave SmartStart ainsi que l'inclusion classique.

-   Identification des pièces
-   ![Mini-PIR B 2](<.gitbook/assets/0 (12).jpeg>)1. Objectif IR avec indicateur LED

L'indicateur LED est situé au centre de la lentille IR.

Le voyant LED s'allume dans les conditions suivantes :

-   Clignote une fois après avoir appuyé sur le bouton de fonction :

Le PIR passe en mode Inclusion/Exclusion ou détecte un mouvement en mode Test.

**2. Compartiment à piles**

Le PIR est alimenté par une pile au lithium CR123A 3V.

**3. Bouton de fonction**

-   Appuyez une fois sur le bouton dans les 30 secondes suivant l'insertion de la batterie pour accéder à l'inclusion ou\\
    Mode d'exclusion.
-   Appuyez une fois sur le bouton en fonctionnement normal pour envoyer une commande de notification de réveil\\
    et entrez en mode test.
-   Appuyez et maintenez le bouton pendant 10 secondes, puis relâchez-le pour réinitialiser le PIR aux paramètres d'usine.

**4. Socle magnétique**

Le PIR est déployé sur la base magnétique lors de l'installation. L'aimant à l'intérieur du PIR et de la base garantira que le PIR reste attaché à la base quels que soient l'emplacement et l'angle du PIR.

-   Caractéristiques
-   _**Détection d'occupation/vacance**_

Lorsque le PIR détecte un mouvement, il transmet un signal de déclenchement. Le PIR commence alors le décompte du minuteur d'occupation/vacance. La durée de la minuterie est réglable de**30 secondes**à**60 minutes**et doit être réglé à partir du coordinateur/panneau de commande du réseau Z-Wave.

Pendant la minuterie, si le PIR détecte un mouvement, la minuterie sera réinitialisée.

Lorsque la minuterie expire sans aucune détection de mouvement, le PIR transmettra un signal de restauration de détection de mouvement et reviendra au fonctionnement normal.

Prière de se référer à_**Configuration de la classe de commande**_pour plus de détails sur les paramètres.

-   _**Ajustement de la sensibilité**_

La sensibilité PIR peut être ajustée pour répondre à différentes exigences en tant que capteur de sécurité ou de présence/vacance. Jusqu'à 5 niveaux de sensibilité peuvent être sélectionnés via le coordinateur réseau/panneau de commande Z-Wave. Suivez les étapes ci-dessous pour régler la sensibilité :

1.  Appuyez une fois sur le bouton de fonction du PIR, le PIR se réveillera.
2.  Dans les 10 secondes, réglez la nouvelle sensibilité PIR à partir du panneau de commande (veuillez vous référer au manuel de votre panneau de commande pour plus de détails). Le panneau enverra un signal au PIR pour terminer le réglage.
3.  Si le réglage de la sensibilité n'est pas terminé dans cet intervalle, recommencez à partir de l'étape 1.

Please refer to _**Configuration de la classe de commande**_pour plus de détails sur les paramètres.

-   _Détection de batterie et de batterie faible_

Le PIR utilise une pile au lithium CR123A 3V comme source d'alimentation. Le corps principal doit être retiré de la base pour accéder au compartiment des piles. Le compartiment à piles comporte une bande qui doit être pressée sous la pile lorsque la pile est insérée. Lorsque vous retirez la pâte, soulevez simplement la bande.

Le PIR dispose d'une fonction de détection de batterie faible. Lorsque la tension de la batterie est faible, le PIR transmet le signal de batterie faible au coordinateur du réseau Z-Wave.

Si la batterie n'est pas changée après une batterie faible et est épuisée, le PIR arrêtera toutes les opérations.

Lors du changement de batterie, après avoir retiré l'ancienne batterie, appuyez deux fois sur le bouton de fonction pour la décharger complètement avant d'insérer une nouvelle batterie.

-   _**Réveillez-vous**_

Cette fonction utilise la classe de commande de réveil Z-Wave. La classe de commande de réveil permet au PIR alimenté par batterie d'informer le panneau de commande/la passerelle qu'il est réveillé et prêt à recevoir toutes les commandes en file d'attente. La période d’intervalle de réveil est programmée automatiquement en fonction des paramètres du panneau de commande lorsque le PIR est inclus. Le réglage recommandé du temps d'intervalle se situe entre 60 minutes.

-   _**Mode d'essai**_
-   Le mode test vous permet de vérifier la plage de détection du PIR.
-   Pour accéder au mode Test, appuyez une fois sur le bouton de fonction pour accéder au mode Test pendant 3 minutes.
-   Pendant le mode test, vous pouvez déclencher le capteur PIR pour vérifier sa couverture de détection. Si le PIR est déclenché, la LED clignote une fois pour l'indiquer.
-   _**Ajout d'un appareil (inclusion)**_

L'appareil prend en charge à la fois le processus d'inclusion classique et le processus d'inclusion SmartStart. Ce produit peut être inclus et utilisé dans n'importe quel réseau Z-Wave avec d'autres appareils certifiés Z-Wave d'autres fabricants et/ou d'autres applications. Tous les nœuds non alimentés par batterie du réseau agiront comme répéteurs, quel que soit le fournisseur, afin d'augmenter la fiabilité du réseau.

-   **Inclusion classique**
-   Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'inclusion**(veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
-   Insérez la batterie et appuyez une fois sur le bouton dans les 30 secondes. Reportez-vous au manuel d'utilisation de la passerelle Z-Wave ou du panneau de commande pour terminer le processus d'ajout.
-   Si l'appareil a déjà été ajouté (inclus) dans une autre passerelle/panneau de configuration Z-Wave, ou si l'appareil ne peut pas être ajouté à la passerelle/panneau de configuration Z-Wave actuelle, essayez d'abord de le supprimer (voir_**Suppression d'un périphérique**_).

**Inclusion de SmartStart**

![](<.gitbook/assets/1 (19).png>)![](<.gitbook/assets/2 (22).png>)

Les produits compatibles SmartStart peuvent être ajoutés à un réseau Z-Wave en scannant le code QR Z-Wave présenté sur le produit avec un contrôleur fournissant l'inclusion SmartStart. Aucune autre action n'est requise et le produit SmartStart sera ajouté automatiquement dans les 10 minutes suivant sa mise sous tension à proximité du réseau. Z-Wave SmartStart utilise le DSK de l'appareil pour améliorer et simplifier le processus d'inclusion.**DSK**est la clé spécifique au périphérique utilisée pour l'authentification. Les informations DSK sont stockées au format QR code qui est imprimé sur une étiquette et collé à l'extérieur de l'appareil, comme exemple illustré sur le côté droit.

-   Scannez le QR Code présent sur la base du POVS-1-ZW pour obtenir**DSK**et transfert vers la passerelle Z-Wave.

**Exemple uniquement**

-   Allumez le POVS-1-ZW, une demande d'inclusion SmartStart sera automatiquement envoyée à la passerelle.
-   La passerelle inclura automatiquement l'appareil lors de la reconnaissance de l'appareil en faisant correspondre la demande d'inclusion avec le DSK obtenu

&lt;REMARQUE>

-   Le DSK de l'appareil n'est utilisé que lors de l'inclusion.
-   Le DSK peut être lu sans la mise sous tension du POVS, il est donc possible de préparer la passerelle pour inclure l'appareil avant d'installer et de mettre sous tension le POVS-1-ZW.
-   Si le POVS-1-ZW a déjà été**inclus**(appris) dans une autre passerelle/panneau de contrôle Z-Wave, veuillez d'abord l'exclure (voir_**Exclusion**_) avant de tenter de**inclure**dans la passerelle/panneau de configuration Z-Wave actuelle. Le POVS-1-ZW n'enverra pas de demande d'inclusion SmartStart s'il se trouve déjà dans une passerelle/un panneau de commande Z-Wave.
-   _**Suppression d'un périphérique (exclusion)**_

L'appareil doit être supprimé du réseau Z-Wave existant avant d'être ajouté à un autre.

**Mode d'exclusion**

-   Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'exclusion**(veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
-   Insérez la batterie et appuyez une fois sur le bouton dans les 30 secondes. L'appareil sera supprimé du réseau Z-Wave.

**Retour aux paramètres d'usine**

_(Utilisez la réinitialisation d'usine uniquement lorsque le panneau de configuration/passerelle réseau est manquant ou inutilisable)._

-   La réinitialisation d'usine de l'appareil le restaurera aux paramètres d'usine par défaut (c'est-à-dire qu'il n'est inclus dans aucun réseau Z-Wave). Veuillez utiliser cette procédure uniquement si la passerelle ou le panneau de commande Z-Wave est perdu ou inutilisable.
-   Appuyez et maintenez enfoncé le bouton de fonction de l'appareil pendant 10 secondes pour réinitialiser les paramètres d'usine.

&lt;REMARQUE>

-   Avant de supprimer ou de réinitialiser le POVS-1-ZW aux paramètres d'usine, veuillez vous assurer que les informations DSK de l'appareil ont été supprimées ou n'existent pas dans la passerelle. Si vous supprimez ou réinitialisez l'appareil aux paramètres d'usine, mais que son DSK existe toujours dans la passerelle, la passerelle inclura automatiquement à nouveau l'appareil.
-   _**Test de portée**_

Pour tester si l'appareil est capable de communiquer avec la passerelle Z-Wave ou le panneau de commande :

-   Mettez la passerelle/le panneau en mode test de portée (Walk Test).
-   Appuyez sur le bouton de fonction de l'appareil.
-   La passerelle/le panneau doit s'afficher si l'appareil se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation de la passerelle/du panneau).
-   _**Mode veille Z-Wave**_
-   Le PIR entrera en mode veille Z-Wave (pour économiser l'énergie) après un réveil pendant une courte période (~10 secondes). En mode veille Z-Wave, les passerelles ou panneaux de contrôle Z-Wave ne peuvent pas envoyer de commandes au PIR.
-   Pour programmer le PIR à l'aide de la passerelle/panneau de commande Z-Wave, veuillez envoyer des commandes au PIR pendant la période de réveil.
-   Installation
-   _Hauteur de montage et couverture de détection PIR_
-   Le PIR a une couverture de détection d'un cône de 120∘à l'avant. Lorsqu'il est monté entre 1,2 m et 2,1 m de hauteur et face vers l'avant, le PIR a une portée maximale de 10 mètres.
-   La direction du PIR peut être modifiée en tournant simplement le PIR sur la base. Après avoir changé de direction, assurez-vous de tester la fonction de détection pour confirmer la nouvelle couverture de détection.
-   _Assemblée_
-   Le PIR est composé d’une couverture avant et d’une couverture arrière. Le capot arrière doit être séparé pour l'installation de la batterie et la configuration du réseau Z-Wave.
-   Pour séparer le capot arrière, tenez le PIR à deux mains et tournez selon l'image ci-dessous pour ouvrir le PIR.

![Mini-PIR B](<.gitbook/assets/3 (3) (1).jpeg>)

-   _Installation_
-   Le corps principal PIR est doté d'un aimant interne en bas et à l'arrière, qui fixe le corps principal à la base de l'aimant PIR lorsqu'il est placé sur la base. Les emplacements des aimants sont identifiés par la marque circulaire sur le boîtier.
-   La fonction de détection de mouvement du PIR est directionnelle. Il est plus sensible aux mouvements latéraux et moins sensible aux mouvements verticaux de haut en bas. Utilisez l'emplacement de l'aimant inférieur comme référence pour déterminer la direction horizontale et verticale du PIR.
-   La base PIR dispose de 2 trous de montage utilisés pour l'installation en surface avec les vis de fixation et les chevilles fournies. La base contient également un aimant. Un côté de la base comporte une ouverture pour marquer la face avant de la base. Le corps principal doit être placé sur la base avec la lentille face à l’ouverture avant pour garantir que la couverture de détection du PIR n’est pas obstruée par la base.

![](<.gitbook/assets/4 (1) (1).jpeg>)

1.  Utilisez les 2 trous de montage sur la base PIR comme gabarit, percez des trous dans la surface.
2.  Insérez les chevilles murales si vous le fixez dans du plâtre ou de la brique.
3.  Vissez la base dans les chevilles murales.
4.  Placez le PIR sur la base. L'aimant à l'intérieur du PIR et de la base garantira que le PIR reste attaché à la base.
5.  Faites pivoter le PIR pour ajuster la couverture de détection en fonction de la trajectoire de mouvement attendue de l'intrus. Assurez-vous que l'intrus se déplace d'un côté à l'autre de la couverture de détection PIR.

-   _Directive d'installation_
-   **Il est recommandé d'installer le PIR aux emplacements suivants.**
-   Dans une position telle qu'un intrus se déplacerait normalement à travers le champ de vision du PIR d'un côté à l'autre, évitez d'installer là où l'intrus se déplace à travers la couverture de détection du PIR de haut en bas.
-   Entre 1,9 et 2 m au-dessus du sol pour de meilleures performances face à l'avant.
-   Où son champ de vision ne sera pas obstrué, par ex. par des rideaux, des ornements, etc.
-   **Limites**
-   N'installez pas le PIR dans un endroit exposé à la lumière directe du soleil, ou à proximité d'un appareil de chauffage/refroidissement et d'une ventilation.
-   Ne dirigez pas le PIR vers une source de chaleur telle qu'un appareil de chauffage, un radiateur et une fenêtre.
-   Ne pointez pas le PIR vers la fenêtre.
-   Évitez les gros obstacles dans la zone de détection et évitez les objets en mouvement tels que les rideaux.
-   Évitez les endroits où les animaux peuvent grimper et compromettre leur immunité, comme les escaliers.
-   Informations sur la vague Z

**Type d'appareil:**Notification de capteur de type générique

**Type de rôle :**Rapport de sommeil des esclaves (RSS)

**Identifiant du fabricant :**0x018E

**ID du type de produit :**0x0001

**Identifiant du produit :**0x0104

**Supported Command Class:**

| **Classe de commande**                      | **Version** | **Classe de sécurité requise**             |
| ------------------------------------------- | ----------- | ------------------------------------------ |
| Association                                 | 2           | Classe de sécurité accordée la plus élevée |
| Informations sur le groupe d'associations   | 3           | Highest Granted Security Class             |
| Réinitialisation de l'appareil localement   | 1           | Classe de sécurité accordée la plus élevée |
| Métadonnées de mise à jour du micrologiciel | 5           | Classe de sécurité accordée la plus élevée |
| Spécifique à la fabrication                 | 2           | Classe de sécurité accordée la plus élevée |
| Multicanal                                  | 4           | Classe de sécurité accordée la plus élevée |
| Association multicanal                      | 3           | Classe de sécurité accordée la plus élevée |
| Niveau d'énergie                            | 1           | Classe de sécurité accordée la plus élevée |
| Notification                                | 8           | Classe de sécurité accordée la plus élevée |
| Batterie                                    | 1           | Classe de sécurité accordée la plus élevée |
| Réveillez-vous                              | 2           | Classe de sécurité accordée la plus élevée |
| Configuration                               | 1           | Classe de sécurité accordée la plus élevée |
| Version                                     | 3           | Classe de sécurité accordée la plus élevée |
| Service de transport                        | 2           | Aucun                                      |
| Informations sur Z-Wave Plus                | 2           | Aucun                                      |
| Sécurité 2                                  | 1           | Aucun                                      |
| Surveillance                                | 1           | Aucun                                      |

**Groupes associatifs :**

| **IDENTIFIANT** | **Nom**           | **Nombre de nœuds** | **Description**                                                                                                                                                                                                                                   |
| --------------- | ----------------- | ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1               | Corde de sécurité | 5                   | <p>Prend en charge les classes de commandes suivantes :</p><ul><li>Device Reset Locally: triggered upon reset</li><li>Rapport de notification : déclenché par PIR</li><li>Rapport de batterie : lorsque le niveau de la batterie change</li></ul> |
| 2               | Ensemble de base  | 5                   | <p>Lorsque le PIR se déclenche, le groupe 2 envoie 0xFF.</p><p>Lors de la restauration PIR, le groupe 2 envoie 0x00.</p>                                                                                                                          |

**Configuration de la classe de commande :**

| **Nombre** | **Nom**                  | **Taille** | **Le minimum** | **Maximum** | **Default** | **Description**                                                                                                                                                                                                                                                             |
| ---------- | ------------------------ | ---------- | -------------- | ----------- | ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1          | Sensibilité IR           | 1          | 1              | 5           | 4           | <p>Réglage du niveau de sensibilité :</p><ul><li>1 : le plus bas ; 5 : le plus élevé</li><li>Lorsque le maximum est supérieur à 5, 5 sera la valeur définie ; lorsque le minimum est inférieur à 1, 1 sera la valeur définie.</li></ul>                                     |
| 2          | Temps de restauration IR | 1          | 1              | 120         | 1           | <p>La durée de la minuterie est réglable de 30 secondes à 60 minutes :</p><ul><li>1 : 30 secondes ; 120 : 60 minutes</li><li>Lorsque le maximum est supérieur à 120, 120 sera la valeur définie ; lorsque le minimum est inférieur à 1, 1 sera la valeur définie.</li></ul> |
