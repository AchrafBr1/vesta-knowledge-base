# GILET 060N

**Contact de porte/capteur de choc (DCSV-29-2W)**

DCSV-29-2W est un capteur de contact/choc de porte capable d'envoyer des signaux sans fil au panneau de commande lors de la détection d'une ouverture de porte/fenêtre ou d'un bris de vitre et d'une détection de choc.

La conception du capteur de contact de porte/choc se compose d’un couvercle et d’une base. Le couvercle contient tous les composants électroniques et la base fournit un moyen de fixation de l'appareil. Un interrupteur anti-sabotage sur circuit imprimé fourni offre une protection contre l'ouverture et/ou le retrait non autorisé de l'appareil.

![](<.gitbook/assets/0 (43).jpeg>)

**Identification des pièces**

1.  **Indicateur LED/bouton de test**
    -   Appuyez une fois sur le bouton pour envoyer un code d'apprentissage ou passer en mode test pendant 3 minutes.
2.  **Vis de fixation du couvercle**
3.  **Trous de montage**
4.  **Interrupteur anti-sabotage**
    -   Fournit une protection contre l’ouverture et/ou le retrait non autorisé de l’appareil de la surface de montage.
5.  **Isolateur de batterie**
6.  **Compartiment à piles**
7.  **Aimant**
8.  **Aimant Trou de vis**
9.  **Entretoise magnétique**

**Caractéristiques**

![](<.gitbook/assets/1 (37).jpeg>)

-   _**Indicateur LED**_
    -   En mode de fonctionnement normal, la LED ne s'allume pas lorsque l'appareil est activé.
    -   Lorsque la tension de la batterie de l'appareil est faible, la LED clignote rapidement lorsque l'appareil est déclenché.
    -   Lorsque l'interrupteur anti-sabotage est déclenché, la LED clignote rapidement. Lorsqu'une condition de sabotage persiste, la LED clignote rapidement chaque fois que l'appareil est déclenché. (Pour l'activation du contact de porte uniquement).
    -   En mode Test, la LED clignote rapidement à chaque fois que l'appareil est déclenché.
    -   Lorsque la batterie est épuisée, la LED clignote toutes les 4 secondes.
    -   La LED ne clignotera pas si l'autoprotection de l'appareil et la batterie sont normales et ne sont pas en mode test.
    -   Si la LED clignote pour indiquer la transmission du signal, elle clignotera deux fois rapidement dès réception de l'accusé de réception du panneau.
    -   Lorsque la commande de programmation du panneau de commande est reçue avec succès, la LED deviendra plus lumineuse puis s'assombrira.
-   _**Détection d'ouverture de porte et détection de choc**_

![](<.gitbook/assets/2 (48).png>)

Le dispositif se déclenche lors de l'ouverture d'une porte/fenêtre ou d'une détection de choc dépassant le seuil de détection.

![](<.gitbook/assets/3 (29).jpeg>)

-   _**Matériaux de surface de montage**_

L'appareil prend en charge la détection des chocs sur divers matériaux, notamment le verre, le bois, le métal et le béton. Après l'installation, vous pouvez sélectionner le matériau de la surface montée sur le panneau de commande. La valeur par défaut est définie comme

![](<.gitbook/assets/4 (43).png>)

**Bois**

-   _**Sensibilité**_
    -   La sensibilité requise pour activer le contact de porte/capteur de choc est déterminée à partir du panneau de commande.
    -   Trois niveaux de sensibilité sont sélectionnables :**Faible**,**Moyen**, et**Haut**. La valeur par défaut est définie comme**Moyen**.

1

-   ![](<.gitbook/assets/5 (21).jpeg>)_**Batterie**_
    -   Le capteur de contact/choc de porte utilise une pile au lithium CR123 3 V comme source d'alimentation. La batterie est installée dans le compartiment à batterie avec un isolant de batterie inséré. Pour activer la batterie, retirez simplement l'isolant de la batterie.
    -   Le capteur de contact de porte/choc peut détecter un état de batterie faible. Lorsque la tension de la batterie est faible, un signal de batterie faible sera envoyé au panneau de commande pour informer de la condition. La LED s'allumera lorsque le contact de porte/capteur de choc est activé en cas de batterie faible. Lorsque la batterie est épuisée, le contact de porte/capteur de choc arrêtera toutes les fonctions, la LED clignotera toutes les 4 secondes.
    -   Lors du changement des piles, après avoir retiré les anciennes piles, appuyez deux fois sur l'interrupteur anti-sabotage pour les décharger complètement avant d'insérer de nouvelles piles.
-   _**Tamper Protection**_
    -   Le contact de porte/capteur de choc est protégé par un interrupteur anti-sabotage qui est comprimé contre la surface de montage lorsque le contact de porte/capteur de choc est monté. Chaque fois que le contact de porte/capteur de choc est retiré de la surface montée ou que le couvercle est ouvert, l'interrupteur d'autoprotection sera activé et l'appareil enverra un signal d'ouverture d'autoprotection pour rappeler à l'utilisateur la condition.
    -   Le signal d'auto-ouverture sera transmis avec le contact de porte au panneau de commande. L'état de défaut d'autoprotection sera affiché uniquement dans la zone des dispositifs CC du panneau de commande.
-   _**Surveillance**_
    -   En fonctionnement normal, le contact de porte et le capteur de choc enverront un signal de supervision au panneau de commande séparément à des intervalles aléatoires de 90 à 110 minutes.
    -   Si le panneau de commande n'a pas reçu le signal de supervision du contact de porte/capteur de choc pendant une période prédéfinie, le panneau de commande indiquera que le contact de porte/capteur de choc particulier rencontre un problème d'absence de signal.
-   _**Mode d'essai**_
    -   En mode normal, appuyez sur le bouton Test pour transmettre un signal de test et un code d'apprentissage au panneau de commande. Le capteur de contact de porte/choc entrera également en mode test pendant 3 minutes.
    -   En mode test, la LED s'allumera chaque fois que le contact de porte/capteur de choc est activé.
    -   Chaque pression supplémentaire sur le bouton de test réinitialisera la durée du mode test à 3 minutes.
-   _**Commencer**_
    -   Retirez l'isolant de la batterie sur le contact de porte/capteur de choc pour allumer.
    -   Mettez le panneau de commande en mode d'apprentissage (veuillez vous référer au manuel d'utilisation du panneau)
    -   Appuyez sur le bouton de test du contact de porte/capteur de choc.
    -   Reportez-vous au manuel d'utilisation de votre panneau de commande pour terminer le processus d'apprentissage.
    -   Une fois appris dans le panneau de commande, le DCSV-29-2W sera reconnu comme 2 appareils distincts (contact de porte et capteur de choc) et occupera 2 zones dans le panneau.
    -   Définissez le niveau de matériau et de sensibilité :
        1.  Une fois le DCSV-29-2W appris dans le panneau de commande, appuyez une fois sur le bouton Test du DCSV-29-2W.
        2.  Accédez à la page Web du Panneau de configuration pour modifier l'appareil.
        3.  Sélectionnez le matériau et le niveau de sensibilité dans la page Paramètres du périphérique. Cliquez sur OK pour confirmer.

![](<.gitbook/assets/6 (28).jpeg>)![](<.gitbook/assets/7 (25).jpeg>)![](<.gitbook/assets/8 (18).jpeg>)![](<.gitbook/assets/9 (26).png>)![](<.gitbook/assets/10 (13).jpeg>)![](<.gitbook/assets/11 (18).png>)![](<.gitbook/assets/12 (22).png>)

2

-   -   1.  Appuyez sur le bouton de test du DCSV-29-2W pour recevoir les données de matériau et de niveau de sensibilité du panneau de commande. La LED s'éteindra d'abord, puis deviendra plus lumineuse et s'assombrira, indiquant que la commande de programmation du panneau de commande a été reçue avec succès.
-   _**Test de marche**_
    -   Une fois le contact de porte/capteur de choc appris, placez le panneau de commande dans (**Test de marche**), maintenez le contact de porte/capteur de choc à l'emplacement souhaité et appuyez sur le bouton de test pour transmettre le signal de test au panneau de commande. Si le panneau de commande se trouve dans la plage du signal de contact de porte/capteur de choc, le panneau affichera les informations de contact de porte/capteur de choc en conséquence.
    -   Procédez au montage et à l'installation une fois que vous êtes convaincu que le contact de porte/capteur de choc fonctionne correctement à l'emplacement souhaité.

![](<.gitbook/assets/13 (14).jpeg>)

**Installation**

![](<.gitbook/assets/14 (16).jpeg>)

-   _**Montage du contact de porte/capteur de choc**_

**Montage comme contact de porte :**

-   Le contact de porte/capteur de choc doit être installé avec le côté marqué par la nervure face à l'aimant.
-   La distance entre le contact de porte/capteur de choc et l'aimant ne doit pas dépasser 15 mm lorsque la porte est fermée.
-   Montez l'appareil le plus haut possible.

![](<.gitbook/assets/15 (12).jpeg>)

**Montage comme capteur de choc :**

Reportez-vous au tableau ci-dessous pour obtenir des informations sur l'emplacement d'installation et l'épaisseur des différents matériaux :

|                                |                  |                        | Fenêtre  | Porte en bois/métal | Mur en béton |   |
| ------------------------------ | ---------------- | ---------------------- | -------- | ------------------- | ------------ | - |
|                                | **Épaisseur**    | >5mm                   | &lt;40mm | -                   |              |   |
|                                |                  |                        |          |                     |              |   |
| **Emplacement d'installation** | Cadre de fenêtre | Porte                  | Mur      |                     |              |   |
|                                |                  |                        |          |                     |              |   |
|                                |                  | **Faible sensibilité** | 0,5M     | 0.5M                | 0,25 M       |   |
| **Détection des chocs**        |                  |                        |          |                     |              |   |
| **Sensibilité moyenne**        | 1M               | 1M                     | 0,5M     |                     |              |   |
| **Rayon**                      |                  |                        |          |                     |              |   |
|                                |                  |                        |          |                     |              |   |
|                                |                  |                        |          |                     |              |   |
|                                |                  | **Haute sensibilité**  | 1,5M     | 2M                  | 1M           |   |
|                                |                  |                        |          |                     |              |   |

![](<.gitbook/assets/16 (10).jpeg>)

3

-   ![](<.gitbook/assets/17 (10).jpeg>)_**Procédure de montage**_
    1.  Utilisez les 2 trous de montage sur la couverture arrière comme modèle pour le positionnement.
    2.  Utilisez les chevilles murales fournies pour l'installation de cadres de fenêtres ou de murs en béton.
    3.  Vissez le contact de porte/capteur de choc dans les chevilles murales. (Le perçage est recommandé lors du montage sur de l'acier, ou vous pouvez également utiliser l'autocollant fourni dans l'emballage).
    4.  Fixez l'aimant sur la porte à l'aide d'un petit morceau de ruban adhésif double face ou avec les vis fournies.
    5.  Pour monter l'aimant, utilisez les 2 trous de vis de l'aimant comme modèle pour un positionnement approprié des trous.
        -   _REMARQUE >_
            -   L'aimant doit s'aligner avec le côté marqué des nervures du contact de porte. Si nécessaire, appliquez l'entretoise magnétique à l'arrière de l'aimant pour mieux aligner l'aimant sur les marques de nervures.
    6.  Vissez l'aimant et insérez les deux capuchons blancs dans les trous de vis de l'aimant pour une intégrité esthétique.
    7.  L'installation est maintenant terminée.

![](<.gitbook/assets/18 (14).png>)![](<.gitbook/assets/19 (4).jpeg>)

4
