# VESTA 217

**Routeur RMB-29**

**Introduction**

RMB-29 est un routeur sans fil alimenté par courant alternatif avec batterie de secours intégrée. La conception « plug-n-play » permet un déploiement rapide et pratique de votre système. Ce prolongateur de signal sans fil est conçu pour rendre votre système plus puissant en augmentant la distance maximale possible et en augmentant la latence du signal dans les zones difficiles d'accès. De plus, il est également optimal pour recevoir et transmettre des signaux du panneau de commande, et vice versa.

**Identification des pièces**

**1. Bouton de test/indicateur LED**

Utilisation du bouton de test :

![](<.gitbook/assets/0 (88).jpeg>)

-   Appuyez une fois pour quitter le processus d'apprentissage en cours.
-   Apprentissage dans le panneau de commande et apprentissage du capteur dans le routeur_(Veuillez vous référer aux sections respectives pour plus de détails.)_

Indicateur LED (vert et rouge) :

|                  | LED verte                     | LED rouge                  |
| ---------------- | ----------------------------- | -------------------------- |
|                  |                               |                            |
| Constante sur    | -                             | Apprendre à contrôler      |
|                  |                               | Panneau                    |
|                  |                               |                            |
| Allumé pour 1    | Mise sous tension             | -                          |
| deuxième         |                               |                            |
|                  |                               |                            |
| Flasher une fois | Signal de réception envoyé    | Transmettre son signal ;   |
|                  | du capteur                    | Capteurs de retransmission |
|                  |                               | signal                     |
|                  |                               |                            |
| Éclair           | Apprentissage du capteur dans | -                          |
|                  | Routeur                       |                            |
|                  |                               |                            |

**Caractéristiques**

![](<.gitbook/assets/1 (64).png>)

-   _**Réglage unidirectionnel/bidirectionnel**_

Le routeur peut fonctionner comme un appareil unidirectionnel ou un appareil bidirectionnel. Lorsqu'il est programmé comme périphérique bidirectionnel, le routeur peut recevoir un accusé de réception du panneau de commande pour garantir une transmission réussie. Veuillez suivre les étapes ci-dessous pour effectuer le réglage unidirectionnel/bidirectionnel.

**Étape 1.**Branchez le routeur sur la prise de courant. Le routeur émettra 1 bip long et la LED verte s'allumera pendant une seconde.

**Étape 2.**Appuyez et maintenez enfoncé le bouton de test pendant 10 secondes. Relâchez le bouton lorsque vous entendez 3 bips.

**Étape 3.**Le routeur entrera en « Mode de configuration » pendant 5 secondes.

**Étape 4.**Dans les 5 secondes, appuyez sur le bouton de test pour définir le routeur comme appareil unidirectionnel ou bidirectionnel. Le routeur émettra 2 bips si la configuration en tant que périphérique bidirectionnel est terminée ; le routeur émettra un long bip si la configuration en tant que périphérique unidirectionnel est terminée.

-   En « Mode de réglage », chaque pression sur le bouton de test réinitialise la durée du mode de réglage à 5 secondes supplémentaires. Après 5 secondes d'inactivité, le routeur émettra 2 bips et reviendra en mode normal.

**Étape 5.**Après avoir terminé le réglage de l'appareil unidirectionnel/bidirectionnel, veuillez apprendre/réapprendre le routeur dans le panneau pour que le paramètre mis à jour prenne effet.

![](<.gitbook/assets/2 (69).png>)

-   _**Apprentissage du panneau de configuration**_

**Étape 1.**Pour apprendre le routeur au panneau de commande, branchez le routeur à la prise de courant. Le routeur émettra 1 bip long et la LED verte s'allumera pendant une seconde.

**Étape 2.**Mettez le panneau de configuration en mode apprentissage.

**Étape 3.**Appuyez et maintenez enfoncé le bouton de test pendant 5 secondes. Relâchez le bouton lorsque vous entendez 2 bips.**Étape 4.**Le routeur entrera dans le processus « Apprentissage du panneau de configuration » et émettra un long bip. Le rouge

La LED restera allumée en permanence.

**Étape 5.**Si le routeur reçoit avec succès le signal du panneau de commande dans les 60 secondes, il émettra

1

3 bips. La LED rouge s'éteindra et reviendra en mode normal.

&lt;_NOTE_>

-   Pour quitter le processus actuel « Apprentissage du panneau de configuration », appuyez une fois sur le bouton de test et le routeur émettra 2 bips. La LED rouge s'éteindra et reviendra en mode normal.

![](<.gitbook/assets/3 (70).png>)

-   _**Apprentissage du routeur dans le routeur**_

Pour apprendre le routeur A au routeur B :

**Étape 1.**Appuyez sur le bouton test du routeur B pendant 3 secondes. Relâchez le bouton lorsque le routeur B émet un bip. Le routeur B entrera dans le processus « Apprentissage du routeur/capteur dans le routeur » et émettra un long bip. La LED verte commencera à clignoter.

**Étape 2.**Appuyez une fois sur le bouton de test du routeur A pour envoyer un code d'apprentissage au routeur B.

**Étape 3.**Lorsque le routeur B reçoit le signal envoyé par le routeur A, il émet un long bip pour confirmer. Si le routeur A a déjà été ajouté au routeur B, le routeur B émettra 2 bips pour avertir l'utilisateur.

&lt;_NOTE_>

-   Pour quitter le processus actuel « Apprentissage du routeur/capteur dans le routeur », appuyez une fois sur le bouton de test et le routeur émettra 2 bips et reviendra en mode normal.
-   Veuillez ne pas procéder à un apprentissage croisé des routeurs, par ex. Apprentissage du routeur A dans le routeur B et apprentissage du routeur B dans le routeur A.
-   Tous les routeurs devront être enregistrés dans le panneau de configuration.

![](<.gitbook/assets/4 (73).png>)

-   _**Apprentissage du capteur dans le routeur**_

**Étape 1.**Pour apprendre un capteur dans le routeur, maintenez enfoncé le bouton de test du routeur pendant 3 secondes. Relâchez le bouton lorsque le routeur émet un bip. Le routeur entrera dans le processus « Apprentissage du routeur/capteur dans le routeur » et émettra un long bip. La LED verte commencera à clignoter.

**Étape 2.**Veuillez vous référer aux manuels des appareils pour savoir comment envoyer le code d'apprentissage à partir des appareils.

**Pour la caméra PIR, veuillez appuyer une fois sur le bouton de test pour envoyer un code d'apprentissage au routeur.**

**Étape 3.**Lorsque le routeur reçoit le signal envoyé par le capteur, il émet un long bip pour confirmer. Si le capteur avait déjà été ajouté au routeur, il émettra 2 bips pour avertir l'utilisateur.

**Un maximum de 60 appareils (y compris les routeurs) peuvent être programmés dans le routeur, et jusqu'à 8 caméras PIR sont prises en charge. Si l'utilisateur tente d'apprendre sur un 61ème appareil, le routeur émettra 4 bips.**

&lt;_NOTE_>

-   Pour quitter le processus actuel « Apprentissage du routeur/capteur dans le routeur », appuyez une fois sur le bouton de test et le routeur émettra 2 bips et reviendra en mode normal.
-   Si plusieurs routeurs sont utilisés, veuillez uniquement apprendre les appareils au(x) routeur(s) les plus proches des zones de fonctionnement des appareils.
-   Tous les appareils appris dans le routeur doivent également être appris dans le panneau de commande.

![](<.gitbook/assets/5 (74).png>)

-   _**Opération**_

Si le routeur reçoit un signal d'un appareil, la LED verte clignote une fois et retransmet le signal au panneau de commande. La LED rouge clignotera une fois en mode transmission.

Si le routeur reçoit un signal du panneau de commande, le signal sera retransmis au(x) périphérique(s) correspondant(s) depuis le routeur.

_\\<NOTE>_

-   Si l'utilisateur ne parvient pas à apprendre d'abord un capteur dans le panneau de commande, le signal reçu ne peut pas être retransmis au panneau de commande. La LED verte clignotera une fois et l'appareil émettra 4 bips.

![](<.gitbook/assets/6 (54).png>)

-   _**Source de courant**_

Le routeur est alimenté par le secteur. Branchez le routeur sur une prise de courant pour activer le routeur. Il y a une batterie rechargeable à l'intérieur du routeur qui sert de secours en cas de panne de courant. Il faut environ 72 heures pour charger complètement la batterie. En fonctionnement normal, l'alimentation secteur est utilisée pour alimenter le routeur et en même temps recharger la batterie.

![](<.gitbook/assets/7 (50).png>)

-   _**Détection de batterie et de batterie faible**_

Le routeur est alimenté par quatre piles rechargeables AAA 1,2 V Ni-MH. Après une panne de courant CA, le routeur transmettra un signal de batterie faible au panneau de commande lorsqu'une faible tension de batterie est détectée. Pour restaurer la batterie, rebranchez l'alimentation secteur dans la prise de courant.

![](<.gitbook/assets/8 (49).png>)

-   _**Détection de panne de courant alternatif**_

2

Chaque fois que le routeur est débranché de la prise de courant, le routeur transmet un signal de panne de courant alternatif au panneau de commande pour informer de la situation. Lorsque le routeur est rebranché sur la prise de courant, il transmettra un code de restauration AC.

![](<.gitbook/assets/9 (44).png>)

-   _**Surveillance**_

Une fois appris dans le panneau de commande, le routeur transmettra automatiquement des signaux de supervision toutes les 30 à 50 minutes lorsqu'il fonctionnera comme un appareil unidirectionnel.

Le routeur transmettra automatiquement des signaux de supervision toutes les 90 à 120 minutes lorsqu'il fonctionnera comme un appareil bidirectionnel.

![](<.gitbook/assets/10 (47).png>)

-   _**Retour aux paramètres d'usine**_

La fonction de réinitialisation d'usine effacera tous les appareils et le panneau de commande mémorisés. Pour réinitialiser le routeur, veuillez suivre les étapes ci-dessous :

**Étape 1.**Appuyez et maintenez enfoncé le bouton de test pendant 3 secondes. Relâchez le bouton lorsque le routeur émet un bip.

**Étape 2.**Le routeur entrera dans le processus « Apprentissage du capteur dans le routeur » et émettra un long bip. La LED verte commencera à clignoter.

**Étape 3.**Appuyez et maintenez enfoncé le bouton de test pendant encore 5 secondes. Relâchez le bouton lorsque vous entendez 3 bips.

**Étape 4.**La réinitialisation d'usine est terminée. Tous les périphériques d'apprentissage et le panneau de configuration sont effacés du routeur.

![](<.gitbook/assets/11 (39).png>)

-   _**Recommandations**_

Il est fortement suggéré de garder une distance entre chaque routeur et le panneau de contrôle pour éviter les signaux croisés.

Si un périphérique particulier se trouve dans une plage acceptable pour que le panneau de contrôle reçoive son signal de transmission, il est fortement recommandé d'apprendre le périphérique directement dans le panneau de contrôle plutôt que dans le routeur.

Lors de la mise en cascade de routeurs pour former un relais de transmission, il est fortement recommandé de ne pas relier plus de 2 couches de routeurs.

![](<.gitbook/assets/12 (40).png>)

_\\<NOTE>_

-   Pour les appareils directement contrôlés par le panneau pour allumer/éteindre, par ex. interrupteurs d'alimentation, commutateurs de compteur de puissance, contrôleurs de vannes, commandes de volets roulants ou commutateurs d'entrée et de sortie, veuillez créer un lien**une seule couche**du ou des routeurs.
-   Pour le clavier, il est également recommandé de relier**une seule couche**du ou des routeurs.

**Plusieurs routeurs**

Si plusieurs routeurs sont utilisés, veuillez suivre les directives ci-dessous pour des performances optimales :

1.  Lors de la liaison de routeurs pour former une rediffusion de transmission, il est recommandé de ne pas relier plus de deux couches de routeurs.

Dans l'exemple ci-dessous (Périphérique vers B vers A vers Panneau de configuration), le routeur A, le routeur B et le périphérique doivent tous être appris dans le panneau de configuration.

L'appareil doit être appris dans son routeur le plus proche (routeur B). Le routeur B doit être appris dans le routeur A. (N'apprenez pas le routeur A dans le routeur B.)

Exemple:

![](<.gitbook/assets/13 (30).jpeg>)

1.  Si un appareil est situé entre la couverture RF de plusieurs routeurs et le panneau de commande : Exemple 1 :

3

![](<.gitbook/assets/14 (25).jpeg>)

D'après le diagramme affiché, l'appareil est situé entre les zones de couverture RF des routeurs B et C. Les utilisateurs peuvent choisir d'apprendre l'appareil dans le routeur B uniquement, dans le routeur C uniquement ou dans les routeurs B et C.

C'est**recommandé**pour apprendre le périphérique au routeur B uniquement (et non au routeur C) afin de réduire le trafic du signal.

![](<.gitbook/assets/15 (28).png>)

_\\<NOTE>_

-   Pour le système ci-dessus, le routeur C est également appris dans le routeur A ou B ou les deux afin que les signaux du routeur C puissent être relayés vers la centrale via le routeur A ou B, ou l'un des deux.

Exemple 2 :

![](<.gitbook/assets/16 (17).jpeg>)

D'après le diagramme affiché, l'appareil est situé entre les zones de couverture RF des routeurs A, B et C. Les utilisateurs peuvent choisir d'apprendre l'appareil dans le routeur A uniquement, d'apprendre uniquement dans le routeur B, d'apprendre uniquement par le routeur C ou d'apprendre par les routeurs. A, B et C.

C'est**recommandé**pour apprendre l'appareil au routeur A uniquement ou au routeur B uniquement (et non au routeur

-   1.  pour réduire le trafic des signaux._\\<NOTE>_
        -   Pour le système ci-dessus, le routeur C est également appris dans le routeur A ou B ou les deux afin que les signaux du routeur C puissent être relayés vers la centrale via le routeur A ou B, ou l'un des deux.

1.  En règle générale, la plupart des appareils restent dans la même zone de couverture RF. Pour les exceptions telles qu'une télécommande, veuillez apprendre l'appareil dans tous les routeurs (et panneau de commande) du système.

![](<.gitbook/assets/17 (25).png>)

4
