# VESTA 126

Manuel d'utilisation du contact de porte (DC-23 / DC-23-R3)

Le contact de porte surveille l'ouverture/fermeture d'appareils spécifiés (par exemple porte ou fenêtre). Le contact de porte est fixé au cadre de l'appareil surveillé à l'aide d'un aimant d'actionnement fixé sur l'appareil. Lorsque la porte ou la fenêtre s'ouvre, l'aimant s'éloigne du contact de porte, activant un interrupteur magnétique interne provoquant la transmission par le contact de porte d'un signal d'alarme au panneau central. L'appareil a également la capacité de communiquer les problèmes de signal ainsi que les situations de batterie faible.

La conception du contact de porte se compose d’un couvercle et d’une base. Le couvercle contient tous les composants électroniques et la base fournit un moyen de fixation de l'appareil. Un interrupteur anti-sabotage sur circuit imprimé fourni offre une protection contre l'ouverture et/ou le retrait non autorisé de l'appareil.

Le contact de porte de la série DC-23 comprend les modèles suivants :

DC-23 : Le couvercle des contacts de porte est fixé par une vis de fixation inférieure.

DC-23-R3 : le couvercle des contacts de porte est sécurisé par deux loquets en haut et en bas

![](<.gitbook/assets/0 (15).jpeg>)

Identification des pièces

1.  **Indicateur LED / Bouton Test**

Appuyez sur le bouton Test pour transmettre le code d'apprentissage ou passer en mode test pendant 3 min.

1.  **Trous de montage**

Utilisé pour fixer et visser le contact de porte directement sur le cadre de porte ou le mur.

1.  **Interrupteur anti-sabotage**

Lorsque le contact de porte est monté, l'interrupteur anti-sabotage sera activé lorsque le couvercle est ouvert ou lorsque le contact de porte est retiré de la surface montée.

1.  **Isolateur de batterie**
2.  **Cavalier de supervision (JP2)**

**(**_**Modèle 868WF uniquement**_**)**

**Cavalier**

si le cavalier est retiré ou "**garé**» sur une épingle.

**Cavalier**

Le cavalier est inséré, reliant les deux broches

![jumper close](<.gitbook/assets/1 (26).png>)![jumper open](<.gitbook/assets/2 (31).png>)

-   Cavalier ON : Supervision désactivée
-   Cavalier OFF : Supervision activée.**(Défaut de fabrication)**

1.  **Cavalier de commutateur à lames (JP3)**

![jumper close](<.gitbook/assets/3 (27).png>)![jumper open](<.gitbook/assets/4 (26).png>)

**Cavalier**

Le cavalier est inséré, reliant les deux broches

**Cavalier**

si le cavalier est retiré ou "**garé**» sur une épingle.

-   Cavalier activé : commutateur à lames désactivé. Seul l'appareil connecté au terminal d'extension activera le contact de porte.
-   Cavalier OFF : commutateur à lames activé.**(Par défaut d'usine pour tous les modèles)**

1.  **Borne d'extension**

En plus de l'interrupteur magnétique intégré, une borne de contact sec à 2 broches supplémentaire est fournie pour un interrupteur magnétique d'extension ou tout appareil doté d'une fonctionnalité N.C. (normalement fermé).

1.  ![](<.gitbook/assets/5 (18).png>)**Compartiment à piles**
2.  **Aimant**
3.  **Aimant Trou de vis**
4.  **Entretoise magnétique**

Caractéristiques

-   _**Indicateur LED**_
-   En mode de fonctionnement normal, la LED ne s'allumera pas lorsque le contact de porte est activé.
-   Lorsque la tension de la batterie du contact de porte est faible, chaque fois que le contact de porte est activé (appareil ouvert/fermé), la LED s'allumera pendant 2 secondes.
-   Lorsque le couvercle est ouvert ou que l'interrupteur anti-sabotage est déclenché, la LED s'allume pendant 2 secondes. Lorsqu'une condition de sabotage persiste, la LED s'allume pendant 2 secondes chaque fois que le contact de porte est activé.
-   Lorsque le contact de porte est en mode Test, la LED s'allume à chaque fois qu'il est activé.
-   Lorsque la batterie est épuisée, le contact de porte arrêtera toute fonction, la LED clignotera toutes les 4 secondes.
-   _**Borne d'extension**_

Le contact de porte dispose d'une borne d'extension pour offrir une flexibilité accrue. Le terminal d'extension forme une boucle fermée avec l'appareil qui y est connecté. Lorsque l'appareil est déclenché, la boucle est ouverte, le contact de porte sera également déclenché.

La borne d'extension et l'interrupteur magnétique interne peuvent fonctionner ensemble pour déclencher le contact de porte lorsque l'un d'eux est activé. Vous pouvez également choisir de désactiver l'interrupteur magnétique interne via le réglage du cavalier JP3.

Pour connecter l'appareil au terminal d'extension :

![](<.gitbook/assets/6 (10).jpeg>)**Pour le modèle DC-23 :**

1.  Ouvrez le couvercle du contact de porte à l'aide d'un tournevis pour desserrer la vis de fixation du couvercle au bas du couvercle du contact de porte. (Voir l'image ci-dessous sous l'angle de vue supérieur).
2.  L'extrémité supérieure du boîtier avant présente une découpe en plastique plus fine. Percez l'ouverture défonçable pour créer un trou pour la connexion du câblage à la borne d'extension.
3.  Connectez l'appareil au terminal d'extension

**Pour le modèle DC-23-R3 :**

1.  ![](<.gitbook/assets/7 (9).jpeg>)Utilisez votre pouce pour appuyer sur le loquet, tout en appuyant dessus, retirez le couvercle de la base du contact de porte (voir l'image ci-dessous sous l'angle de vue supérieur).
2.  L'extrémité supérieure du boîtier avant présente une découpe en plastique plus fine. Percez l'ouverture défonçable pour créer un trou pour la connexion du câblage à la borne d'extension.
3.  Connectez l'appareil au terminal d'extension

Le terminal Extension peut être utile dans la situation suivante.

-   Si le contact de porte ne peut pas être monté sur le cadre de la porte, vous pouvez connecter un interrupteur magnétique d'extension supplémentaire au terminal d'extension pour monter le contact de porte à distance.
-   Tout dispositif à contact sec avec boucle N.C. (fermeture normale) peut être connecté à la borne d'extension, faisant du contact de porte un émetteur universel.
-   Plusieurs dispositifs à contact sec peuvent être câblés avec le contact de porte, comme le montre le schéma ci-dessous.

![](<.gitbook/assets/8 (9).png>)

-   La borne d'extension et l'interrupteur magnétique interne peuvent fonctionner ensemble pour déclencher le contact de porte lorsque l'un d'eux est activé. Vous pouvez également choisir de désactiver l'interrupteur magnétique interne via le réglage du cavalier JP3. Si la borne d'extension et l'interrupteur magnétique interne sont utilisés et que l'un d'entre eux est déclenché (ouvert). Le contact de porte enverra un signal de fermeture (rétablissement) du contact de porte uniquement lorsque les deux sont fermés.
-   _**Batterie**_
-   Le contact de porte est alimenté par une pile au lithium CR123 3V. Veuillez noter:**TOUJOURS**remplacez la batterie par une taille et une tension correctes.
-   Le contact de porte peut détecter un état de batterie faible. Lorsque la tension de la batterie est faible, un signal de batterie faible sera envoyé au panneau de commande pour informer de la condition. La LED s'allumera lorsque le contact de porte est activé en cas de batterie faible. Lorsque la batterie est épuisée, le contact de porte arrêtera toute fonction, la LED clignotera toutes les 4 secondes.
-   Lors du changement de batterie, après avoir retiré les anciennes batteries, appuyez deux fois sur l'interrupteur anti-sabotage pour la décharger complètement avant d'insérer une nouvelle batterie.
-   _**Autoprotection**_
-   Le contact de porte est protégé par un interrupteur anti-sabotage qui est comprimé contre la surface de montage lorsque le contact de porte est monté. Chaque fois que le couvercle du contact de porte est ouvert ou retiré de la surface montée, l'interrupteur d'autoprotection sera activé et le contact de porte enverra un signal d'ouverture d'autoprotection pour rappeler à l'utilisateur la condition.
-   _**Signal de surveillance**_
-   La fonction de supervision pour le modèle 868WF est contrôlée par le réglage du cavalier JP2. Pour le modèle non-868WF, la fonction de supervision est toujours activée.
-   Lorsqu'il est activé, le contact de porte transmettra automatiquement des signaux de supervision périodiquement au panneau de commande à des intervalles aléatoires de 30 à 50 minutes.
-   Si le panneau de commande n'a pas reçu le signal du contact de porte pendant une période prédéfinie, le panneau de commande indiquera que le contact de porte particulier rencontre un problème de manque de signal.
-   _**Mode d'essai**_
-   En mode normal, appuyez sur le bouton Test pour transmettre un signal de test et un code d'apprentissage au panneau de commande. Le contact de porte entrera également en mode test pendant 3 minutes.
-   En mode test, la LED s'allumera chaque fois que le contact de porte est activé.
-   Chaque pression supplémentaire sur le bouton de test réinitialisera la durée du mode test à 3 minutes.
-   _**Commencer**_
-   Ouvrez le couvercle du contact de porte et insérez la batterie.
-   Mettez le panneau de commande en mode d'apprentissage (veuillez vous référer au manuel d'utilisation du panneau).
-   Appuyez sur le bouton Test du contact de porte.
-   Reportez-vous au manuel d'utilisation de votre panneau de commande pour terminer le processus d'apprentissage.
-   Une fois le contact de porte appris, placez le panneau de commande dans (**Test de marche)**mode, maintenez le contact de porte à l'emplacement souhaité et appuyez sur le bouton Test pour transmettre le signal de test au panneau de commande. Si le panneau de commande se trouve à portée du signal de contact de porte, le panneau affichera les informations de contact de porte en conséquence.
-   Procédez au montage et à l'installation une fois que vous êtes satisfait du bon fonctionnement de l'emplacement du contact de porte.

Installation

-   _Directive d'installation_
-   Le contact de porte doit être installé sur le cadre de porte/fenêtre et l'aimant sur la porte/fenêtre.
-   La distance entre le contact de porte et l'aimant ne doit pas dépasser 15 mm lorsque la porte est fermée.
-   Évitez de monter le contact de porte sur une surface métallique. En cas de montage sur une surface métallique, assurez-vous de tester si le contact de porte peut être déclenché lorsque la porte est ouverte.
-   Montez le contact de porte aussi haut que possible.
-   _**Montage du contact de porte**_

1.  Trouvez un emplacement approprié à proximité de votre porte/fenêtre pour installer le contact de porte.
2.  Le contact de porte comporte 2 marques de nervures sur un côté (voir la figure), marquant l'emplacement de l'interrupteur magnétique interne. Le contact de porte doit être installé soit verticalement, soit inversé pour garantir que le côté marqué par la nervure soit face à l'aimant.
3.  Pour monter le contact de porte :
4.  Utilisez les 2 trous de montage du contact de porte comme modèle pour le positionnement approprié des trous.
5.  Utilisez les chevilles murales fournies pour l'installation en plâtre/brique.
6.  Vissez le contact de porte dans les chevilles murales fournies.
7.  Pour monter l'aimant :
8.  Utilisez les 2 trous de vis magnétiques comme modèle pour un positionnement approprié des trous.

&lt;Remarque>

-   L'aimant ne doit pas être à plus de 15 mm du contact de porte lorsque la porte est fermée.
-   L'aimant doit s'aligner avec le côté marqué des nervures du contact de porte. Si nécessaire, appliquez l'entretoise magnétique à l'arrière de l'aimant pour mieux aligner l'aimant sur les marques de nervures.

1.  Vissez l'aimant sur la porte.
2.  Insérez les deux capuchons blancs dans les trous de vis magnétiques pour une intégrité esthétique.
3.  L'installation est maintenant terminée.

![](<.gitbook/assets/9 (9) (1).png>)

Déclaration FCC

Cet appareil est conforme à la partie 15 des règles FCC. L’exploitation est soumise aux deux conditions suivantes :

(1) Cet appareil ne doit pas provoquer d'interférences nuisibles, et

(2) Cet appareil doit accepter toute interférence reçue, y compris les interférences susceptibles de provoquer un fonctionnement indésirable.

Attention FCC :

Pour garantir une conformité continue, tout changement ou modification non expressément approuvé par la partie responsable de la conformité peut annuler le droit de l'utilisateur à utiliser cet équipement. (Exemple : utilisez uniquement des câbles d'interface blindés lors de la connexion à un ordinateur ou à des périphériques).
