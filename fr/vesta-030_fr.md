# VESTA 030

**Répéteur (RP-29)**

Le Répéteur est conçu pour augmenter l’efficacité et la polyvalence du système d’alarme. C'est un appareil qui rend votre système plus puissant en augmentant la distance maximale possible entre l'unité principale (panneau de commande) et les appareils.

-   **Identifier les pièces**

![C:\\Documents and Settings\\C0874.CLIMAX-TECH\\桌面\\done\\to be completed\\manual pictures\\RP-23 20140415.jpg](<.gitbook/assets/0 (5) (1).jpeg>)

1.  **LED d'alimentation (verte)**

**Sur**– Alimenté par un adaptateur secteur ou une batterie rechargeable

**Éclair**– Batterie rechargeable faible en puissance

1.  **LED de mode (jaune)**

**Sur**– Le répéteur est en mode apprentissage (panneau) ou en mode effacement

**Éclair**(1 flash toutes les secondes) – Le répéteur est en mode test de marche

**Flash lent**(1 flash toutes les 2 secondes) – Le répéteur est en mode apprentissage (appareil)

1.  **Transmission : LED de réception (bleue)**

La LED bleue s'allume lorsque le répéteur reçoit une transmission de signal

1.  **Transmission : LED de transmission (rouge)**

La LED rouge s'allume lorsque le répéteur transmet un signal.

1.  **Bloc de commutation fonctionnel**
2.  **Bouton de test**
3.  **Coupe-batterie**
4.  **Housse amovible**
5.  **Interrupteur anti-sabotage**
6.  **Trou de montage**
7.  **Prise d'alimentation CC**
8.  **Support de montage**

-   **Source de courant**

Un adaptateur secteur est nécessaire pour se connecter à une prise de courant murale. Assurez-vous d'utiliser uniquement un adaptateur avec la tension nominale CA appropriée pour éviter d'endommager les composants. Un adaptateur secteur de sortie DC 12 V 1 A est généralement utilisé pour alimenter le répéteur.

**Application de l'adaptateur secteur :**

Pour connecter l'adaptateur secteur :

1.  Localisez l'adaptateur secteur et branchez-le sur la prise d'alimentation CC.
2.  Branchez l'adaptateur secteur sur une prise de courant murale.
3.  Le répéteur émettra un bip long et la LED verte s'allumera.

**Panne CA/Rétablissement CA :**

Le répéteur enverra un signal de panne de courant alternatif au panneau de commande lorsque l'adaptateur secteur est débranché pendant 30 à 60 secondes. Lorsque l'adaptateur secteur est rebranché pendant 30 à 60 secondes, le répéteur enverra un signal de restauration CA au panneau de commande.

**Batterie rechargeable:**

En plus de l'adaptateur, le répéteur contient une batterie rechargeable qui sert d'alimentation de secours en cas de panne de courant.

Lorsque l'adaptateur secteur est branché sur la prise d'alimentation CC, faites glisser l'interrupteur de la batterie sur la position ON pour que l'adaptateur secteur alimente le répéteur et recharge en même temps la batterie. Il faut environ 72 heures pour charger complètement la batterie.

Lorsque l'adaptateur secteur est débranché, le répéteur sera alimenté par la batterie rechargeable.

Le répéteur peut détecter la tension de la batterie. Lorsque la tension de la batterie est faible, la LED verte clignote pour indiquer l'état de la batterie faible.

-   **Bloc de commutation fonctionnel**

![C:\\Documents and Settings\\C0874.CLIMAX-TECH\\桌面\\done\\to be completed\\manual pictures\\RP-23 switch block.jpg](<.gitbook/assets/1 (2) (1).jpeg>)Le bloc de commutation fonctionnel détermine le mode dans lequel se trouve le répéteur. Un commutateur en position haute indique le (**SUR**) Mode. De même, un interrupteur en position basse indique le (**DÉSACTIVÉ**) Mode.

|                   | Fonction                                   | SUR                             | DÉSACTIVÉ            |
| ----------------- | ------------------------------------------ | ------------------------------- | -------------------- |
| Commutateur DIP1  | Apprendre l'appareil                       | Mode d'apprentissage (appareil) | Mode normal          |
| Commutateur DIP2  | Test de portée ou de marche                | Mode test de marche             | Mode normal          |
| Commutateur DIP 3 | Retour aux paramètres d'usine              | Mode Effacer                    | Mode normal          |
| Commutateur DIP 4 | Apprendre dans le panneau de configuration | Mode d'apprentissage (panneau)  | Mode normal          |
| Commutateur DIP 6 | Réglage unidirectionnel/bidirectionnel     | Bidirectionnel                  | Sens Unique          |
| Commutateur DIP 8 | Fonction anti-sabotage                     | Désactiver                      | Mode normal (activé) |

Les commutateurs DIP 5 et 7 sont réservés.

\\<Note>

-   Veuillez modifier le réglage du commutateur DIP 1 à 4 lorsque le répéteur est alimenté, car la modification du commutateur DIP 1 à 4 n'est valide que lorsque le répéteur est alimenté. Par exemple, le commutateur DIP 3 est glissé en position On lorsque le répéteur est éteint. Lorsque le répéteur est allumé, il n’entrera PAS en mode Effacer. Cependant, si le commutateur DIP 3 est d'abord glissé vers la position Off, puis vers la position On lorsque le répéteur est allumé, le répéteur entrera en mode Clear.
-   Veuillez régler la position du commutateur DIP 6 pour l'appareil unidirectionnel/bidirectionnel lorsque le répéteur est éteint. Une fois le réglage terminé, veuillez allumer le répéteur et l'apprendre/réapprendre dans le panneau pour que le réglage prenne effet.
-   Pour le réglage du commutateur DIP 8, veuillez éteindre le répéteur avant de modifier le réglage du commutateur DIP. Les nouveaux paramètres du Dip Switch 8 prendront effet lorsque le répéteur sera remis sous tension.
-   **Signal de surveillance**
-   Après avoir été appris dans le panneau de commande, le répéteur transmettra automatiquement des signaux de supervision toutes les 30 à 50 minutes lorsqu'il fonctionnera comme un appareil unidirectionnel. S'il fonctionne comme un appareil bidirectionnel, le répéteur transmettra automatiquement des signaux de supervision toutes les 90 à 120 minutes.
-   Si le panneau de commande n'a pas reçu le signal du répéteur pendant une période de temps prédéfinie, le panneau de commande l'indiquera sur son écran pour montrer que le répéteur rencontre un problème de manque de signal.
-   **Réglage unidirectionnel/bidirectionnel**
-   Le répéteur peut fonctionner comme un appareil unidirectionnel ou un appareil bidirectionnel. Lorsqu'il est programmé comme dispositif bidirectionnel, le répéteur peut recevoir un accusé de réception du panneau de commande pour garantir une transmission réussie.
-   Le répéteur fonctionnera comme un**bidirectionnel**appareil lorsque le commutateur DIP 6 est glissé vers**SUR**position. Cela fonctionnera comme un**Sens Unique**appareil lorsque le commutateur DIP 6 est glissé vers**DÉSACTIVÉ**position.
-   Veuillez régler la position du commutateur DIP 6 pour l'appareil unidirectionnel/bidirectionnel lorsque le répéteur est éteint. Une fois le réglage terminé, veuillez allumer le répéteur et l'apprendre/réapprendre dans le panneau pour que le réglage prenne effet.
-   **Apprendre dans le panneau de configuration**

1.  Pour apprendre le répéteur dans le panneau de commande, faites glisser le commutateur DIP 4 sur la position On en mode normal. Le répéteur émettra 1 bip long et la LED jaune s'allumera.
2.  Mettez le panneau de commande en mode apprentissage (veuillez vous référer au manuel du panneau de commande).
3.  Appuyez sur le bouton Test. Le répéteur transmettra un code de test au panneau de commande lorsque la LED rouge s'allumera et que le répéteur émettra 1 bip.
4.  Si le répéteur reçoit un signal d'accusé de réception du panneau de commande dans les 60 secondes, l'apprentissage est réussi. La LED bleue s'allumera pendant 1 seconde tandis que le répéteur émettra 1 bip long.

Si le répéteur ne reçoit pas de signal d'accusé de réception de la centrale dans les 60 secondes, l'apprentissage a échoué et est indiqué par le voyant jaune clignotant 3 fois. Veuillez répéter les étapes 3 et 4.

1.  Faites glisser le commutateur DIP 4 sur la position Arrêt. Le répéteur émettra 1 bip long et la LED jaune s'éteindra lorsque le répéteur reviendra en mode normal.

-   **Apprentissage du répéteur dans le répéteur**

Si le répéteur A apprend avec le répéteur B :

1.  Mise du répéteur B en mode apprentissage : en mode normal, faites glisser le commutateur DIP 1 du répéteur B sur la position On. Le répéteur B émettra 1 bip long et la LED jaune clignotera lentement (1 flash toutes les 2 secondes).
2.  Appuyez sur le bouton Test du répéteur A pour envoyer un code d'apprentissage. Le répéteur A émettra 1 bip et la LED rouge s'allumera.

Si le répéteur B reçoit le code d'apprentissage du répéteur A, il émettra 1 bip long et la LED bleue s'allumera pendant 1 seconde pour indiquer un apprentissage réussi.

Si le répéteur B reçoit le code d'apprentissage du répéteur A et que le répéteur A a déjà été appris, le répéteur B émettra 2 bips et la LED bleue s'allumera pendant 1 seconde.

\\<Note>

-   Veuillez ne pas procéder à un apprentissage croisé des répéteurs, par ex. Apprentissage du répéteur A dans le répéteur B et apprentissage du répéteur B dans le répéteur A.
-   Tous les répéteurs devront être appris dans le panneau de contrôle.

1.  Une fois l'apprentissage terminé, faites glisser le commutateur DIP 1 du répéteur B sur la position Off. Le répéteur B émettra 1 bip long et la LED jaune s'éteindra lorsque le répéteur B reviendra en mode normal.

-   **Appareil d'apprentissage en répéteur**

1.  En mode normal, faites glisser le commutateur DIP 1 sur la position On. Le répéteur émettra 1 bip long et la LED jaune clignotera lentement (1 flash toutes les 2 secondes).
2.  Veuillez vous référer aux manuels des appareils pour savoir comment envoyer le code d'apprentissage à partir des appareils.

**Pour la caméra PIR, veuillez appuyer une fois sur le bouton de test pour envoyer un code d'apprentissage au répéteur.**

Si le répéteur reçoit un code d'apprentissage d'un nouvel appareil, il émettra 1 bip long et la LED bleue s'allumera pendant 1 seconde pour indiquer un apprentissage réussi.

Si le répéteur reçoit un code d'apprentissage d'un appareil déjà appris dans le répéteur, il émettra 2 bips et la LED bleue s'allumera pendant 1 seconde.

**Un maximum de 60 appareils (y compris les répéteurs) peuvent être appris dans le répéteur, et jusqu'à 8 caméras PIR sont prises en charge. Si l'utilisateur tente d'apprendre sur un 61ème appareil, le répéteur émettra 4 bips.**

\\<Note>

-   Si plusieurs répéteurs sont utilisés, veuillez uniquement apprendre les appareils dans le(s) répéteur(s) le plus proche des zones de fonctionnement des appareils.
-   Tous les appareils appris dans le répéteur doivent également être appris dans le panneau de commande.

1.  Une fois l’apprentissage terminé, faites glisser le commutateur DIP 1 sur la position Off. Le répéteur émettra 1 bip long, la LED jaune s'éteindra lorsque le répéteur reviendra en mode normal.

-   **Mode test de marche**

Le panneau de commande appris ou les appareils appris peuvent vérifier la portée de leur signal avec le répéteur si le répéteur passe en mode test de marche.

1.  En mode normal, faites glisser le commutateur DIP 2 sur la position On. Le répéteur émettra 1 bip long et la LED jaune clignotera (1 flash toutes les secondes).
2.  Lorsque le répéteur reçoit des signaux du panneau de commande ou des appareils enregistrés, il émet un long bip et la LED bleue s'allume pendant 1 seconde. Le signal est ensuite retransmis lorsque la LED rouge s'allume pendant 1 seconde.
3.  Pour quitter le mode test de marche, faites glisser le commutateur DIP 2 sur la position Off. Le répéteur émettra 1 bip long et la LED jaune s'éteindra.

-   **Mode Effacer (réinitialisation d'usine)**

Effacez la mémoire précédemment programmée et réinitialisez le répéteur aux paramètres d'usine par défaut.

1.  En mode normal, faites glisser le commutateur DIP 3 sur la position On. Le répéteur émettra 1 bip long et la LED jaune s'allumera.
2.  Appuyez et maintenez enfoncé le bouton Test pendant 5 secondes. Le répéteur émettra 1 bip long pour indiquer que tous les appareils appris et le panneau de commande sont effacés du répéteur.
3.  Pour quitter le mode Clear, faites glisser le commutateur DIP 3 sur la position Off. Le répéteur émettra 1 bip long et la LED jaune s'éteindra.

\\<Note>

-   Chaque fois que le répéteur est retiré du panneau de commande, il doit également être réinitialisé aux paramètres d'usine pour effacer la mémoire de son panneau de commande.
-   **Opération**

Si le répéteur reçoit un signal de la centrale (par exemple une commande), le signal est retransmis au(x) périphérique(s) correspondant(s) depuis le répéteur. Les LED de transmission s'allumeront en conséquence.

Si le répéteur reçoit un signal d'un appareil (par exemple un signal d'alarme), le signal est retransmis à la centrale depuis le répéteur. Les LED de transmission s'allumeront en conséquence.

-   **Comment monter le répéteur**

Le répéteur peut être placé sur la table, monté au mur ou partout où vous le souhaitez. Suivez les étapes ci-dessous pour monter le répéteur :

1.  En utilisant les trous du support de montage comme gabarit, percez des trous dans la surface de montage.
2.  Insérez les chevilles murales si vous fixez dans du plâtre ou de la brique. Vissez le support de montage au mur.

![](<.gitbook/assets/2 (17).png>)

1.  Accrochez le répéteur au support de montage mural (avec les trous de montage du répéteur).

![](<.gitbook/assets/3 (16).png>)

1.  Tenez le répéteur et poussez-le doucement vers le bas comme indiqué ci-dessous.

![](<.gitbook/assets/4 (15).png>)

-   **Autoprotection**
-   L'interrupteur anti-sabotage est en position de fonctionnement normale (autoprotection fermée) lorsque le répéteur est accroché au support de montage mural. Une violation de sabotage se produit lorsque le répéteur est retiré du crochet où l'interrupteur de sabotage est relâché (tamper ouvert).
-   La fonction de protection contre les manipulations peut être**désactivé**lorsque le commutateur DIP 8 est glissé en position ON. C'est**activé**lorsque le commutateur DIP 8 est glissé en position OFF. La modification du réglage du commutateur Dip 8 deviendra valide lorsque le répéteur sera remis sous tension.
-   **Recommandations**

Il est fortement suggéré de garder une distance entre chaque répéteur et/ou panneau de commande principal pour éviter les signalisations croisées.

Si un appareil particulier se trouve dans une plage acceptable pour que le panneau de commande reçoive son signal de transmission, il est fortement recommandé d'apprendre l'appareil directement dans le panneau de commande plutôt que dans le répéteur.

Lors de la mise en cascade de répéteurs pour former un relais de transmission, il est fortement recommandé de ne pas relier plus de 2 couches de répéteurs.

\\<Note>

-   Pour les appareils directement contrôlés par le panneau pour allumer/éteindre, par ex. interrupteurs d'alimentation, commutateurs de compteur de puissance, contrôleurs de vannes, commandes de volets roulants ou commutateurs d'entrée et de sortie, veuillez relier une seule couche de répéteur(s).
-   Pour le clavier, il est également recommandé de relier une seule couche de répéteur(s).

**Plusieurs répéteurs**

Si plusieurs répéteurs sont utilisés, veuillez suivre les directives ci-dessous pour des performances optimales :

1.  Lors de la liaison de répéteurs pour former une rediffusion de transmission, il est recommandé de ne pas relier plus de deux couches de répéteurs.

Dans l'exemple ci-dessous (Périphérique vers B vers A vers le panneau de commande), le répéteur A, le répéteur B et le périphérique doivent tous être appris dans le panneau de commande.

L'appareil doit être appris dans son répéteur le plus proche (répété B). Le répéteur B doit être appris dans le répéteur A. (N'apprenez pas le répéteur A dans le répéteur B.)

Exemple:

![C:\\Documents and Settings\\C0874.CLIMAX-TECH\\桌面\\done\\to be completed\\manual pictures\\RP coverage device.jpg](<.gitbook/assets/5 (2) (1).jpeg>)

1.  Si un appareil est situé entre la couverture RF de plusieurs répéteurs et la centrale :

Exemple 1:

![C:\\Documents and Settings\\C0874.CLIMAX-TECH\\桌面\\done\\to be completed\\manual pictures\\RP coverage eg1.jpg](<.gitbook/assets/6 (5) (1).jpeg>)

D'après le diagramme affiché, l'appareil est situé entre les zones de couverture RF des répéteurs B et C. Les utilisateurs peuvent choisir d'apprendre l'appareil dans le répéteur B uniquement, dans le répéteur C uniquement ou dans les répéteurs B et C.

C'est**recommandé**pour apprendre l'appareil au répéteur B uniquement (et non au répéteur C) afin de réduire le trafic du signal.

\\<Note>

-   Pour le système ci-dessus, le répéteur C est également appris dans le répéteur A ou B ou les deux afin que les signaux du répéteur C puissent être relayés vers la centrale via le répéteur A ou B, ou l'un des deux.

Exemple 2 :

![C:\\Documents and Settings\\C0874.CLIMAX-TECH\\桌面\\done\\to be completed\\manual pictures\\RP coverage eg2.jpg](<.gitbook/assets/7 (4) (1).jpeg>)

D'après le diagramme affiché, l'appareil est situé entre les zones de couverture RF du répéteur A, B et C. Les utilisateurs peuvent choisir d'apprendre l'appareil dans le répéteur A uniquement, d'apprendre uniquement dans le répéteur B, d'apprendre uniquement par le répéteur C ou d'apprendre par les répéteurs. A, B et C.

C'est**recommandé**pour apprendre l'appareil au répéteur A uniquement ou au répéteur B uniquement (et non au répéteur C) afin de réduire le trafic des signaux.

\\<Note>

-   Pour le système ci-dessus, le répéteur C est également appris dans le répéteur A ou B ou les deux afin que les signaux du répéteur C puissent être relayés vers la centrale via le répéteur A ou B, ou l'un des deux.

1.  En règle générale, la plupart des appareils restent dans la même zone de couverture RF. Pour les exceptions telles qu'une télécommande, veuillez apprendre l'appareil à tous les répéteurs (et panneau de commande) du système.
