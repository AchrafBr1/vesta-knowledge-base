---
icon: circle-chevron-right
---

# VESTA 019N

**Manuel d'utilisation du contact de porte (DC-23 / DC-23-R3)**

Le contact de porte surveille l'ouverture/fermeture d'appareils spécifiés (par exemple, portes ou fenêtres). Le contact de porte est fixé au cadre de l'appareil surveillé à l'aide d'un aimant d'actionnement fixé sur l'appareil. Lorsque la porte ou la fenêtre s'ouvre, l'aimant s'éloigne du contact de porte, activant un interrupteur magnétique interne, permettant au contact de porte de transmettre des signaux d'alarme au panneau de commande. L'appareil a également la capacité de communiquer les problèmes de signal ainsi que les situations de batterie faible.

La conception du contact de porte se compose d’un couvercle et d’une base. Le couvercle contient toute l'électronique et la base fournit un moyen de fixation du contact de porte. Un interrupteur anti-sabotage sur circuit imprimé fourni offre une protection contre l'ouverture et/ou le retrait non autorisé de l'appareil.

Le contact de porte de la série DC-23 comprend les modèles suivants :

DC-23 : Le couvercle du contact de porte est fixé par une vis de fixation inférieure.

DC-23-R3 : Le couvercle du contact de porte est sécurisé par deux loquets en haut et en bas.

![](<.gitbook/assets/0 (26).png>)

**Identification des pièces**

1. **Indicateur LED / Bouton Test**

Appuyez sur le bouton Test pour transmettre un code d'apprentissage ou passer en mode test pendant 3 min.

1. **Trous de montage**

Permet de fixer et visser le Contact de Porte directement sur le cadre de la porte ou sur le mur.

1. **Interrupteur anti-sabotage**

Lorsque le contact de porte est monté, l'interrupteur anti-sabotage sera activé lorsque le couvercle est ouvert ou lorsque le contact de porte est retiré de la surface de montage.

1. **Isolateur de batterie**
2. **Cavalier de supervision (JP2) (**_**Modèle 868WF uniquement**_**)**

![](<.gitbook/assets/1 (21).jpeg>)

**Cavalier**

![](<.gitbook/assets/2 (20).jpeg>) ![](<.gitbook/assets/3 (19).jpeg>)

Le cavalier est inséré, reliant les deux broches

**Cavalier**

Le lien de cavalier est supprimé ou "**garé**» sur une épingle.

* Cavalier ON : Supervision désactivée
* Cavalier OFF : Supervision activée\*\*(Défaut de fabrication)\*\*.

**6. Cavalier de commutateur à lames (JP3)**

![](<.gitbook/assets/4 (18).jpeg>)

**Cavalier**

![](<.gitbook/assets/5 (14).jpeg>) ![](<.gitbook/assets/6 (17).jpeg>)

Le cavalier est inséré, reliant les deux broches

**Cavalier**

Le lien de cavalier est supprimé ou "**garé**» sur une épingle.

*
  * Cavalier activé : commutateur à lames désactivé. Seul l'appareil connecté au terminal d'extension activera le contact de porte.
  * Cavalier OFF : commutateur à lames activé\*\*(Par défaut d'usine pour tous les modèles)\*\*.

1. **Borne d'extension**

En plus de l'interrupteur magnétique intégré, une borne de contact sec à 2 broches supplémentaire est fournie pour un interrupteur magnétique d'extension ou tout appareil doté d'une fonctionnalité N.C. (normalement fermé).

1. **Compartiment à piles**
2. **Aimant**
3. **Aimant Trou de vis**
4. **Entretoise magnétique**

![](<.gitbook/assets/7 (16).jpeg>)

1

**Caractéristiques**

![](<.gitbook/assets/8 (12).jpeg>)

* _**Indicateur LED**_
  * En mode de fonctionnement normal, la LED ne s'allume pas lorsque le contact de porte est activé.
  * Lorsque la tension de la batterie du contact de porte est faible, chaque fois que le contact de porte est activé (appareil ouvert/fermé), la LED s'allumera pendant 2 secondes.
  * Lorsque le couvercle est ouvert ou que l'interrupteur anti-sabotage est déclenché, la LED s'allume pendant 2 secondes. Lorsque la condition de sabotage persiste, la LED s'allume pendant 2 secondes chaque fois que le contact de porte est activé.
  * Lorsque le contact de porte est en mode test, la LED s'allume à chaque fois qu'il est activé.
  * Lorsque la batterie est épuisée, le contact de porte arrêtera toutes les fonctions et la LED clignotera toutes les 4 secondes.
* _**Borne d'extension**_

![](<.gitbook/assets/9 (7).jpeg>)

Le contact de porte dispose d'une borne d'extension pour offrir une flexibilité accrue. Le terminal d'extension forme une boucle fermée avec l'appareil qui y est connecté. Lorsque l'appareil est déclenché avec la boucle ouverte, le contact de porte sera également déclenché. La borne d'extension et l'interrupteur magnétique interne peuvent fonctionner ensemble pour déclencher le contact de porte lorsque l'un d'eux est activé. Vous pouvez également choisir de désactiver l'interrupteur magnétique interne via le réglage du cavalier JP3.

Pour connecter l'appareil au terminal d'extension :

**Pour le modèle DC-23 :**

![](<.gitbook/assets/10 (8).jpeg>)

1. Ouvrez le couvercle du contact de porte avec un tournevis pour desserrer la vis de fixation du couvercle en bas du couvercle du contact de porte (voir l'image de la vue de dessus à droite).
2. L'extrémité supérieure du boîtier avant présente une découpe en plastique plus fine. Percez l'ouverture défonçable pour créer un trou pour la connexion du câblage à la borne d'extension.
3. Connectez l'appareil au terminal d'extension

**Pour le modèle DC-23-R3 :**

1. Utilisez votre pouce pour appuyer sur le loquet, tout en appuyant dessus, retirez le couvercle de la base du contact de porte (voir l'image vue de dessus à droite).
2. L'extrémité supérieure du boîtier avant présente une découpe en plastique plus fine. Percez l'ouverture défonçable pour créer un trou pour la connexion du câblage à la borne d'extension.
3. Connectez l'appareil au terminal d'extension

![](<.gitbook/assets/11 (12).jpeg>)

Le terminal d'extension peut être utile dans la situation suivante.

* Si le contact de porte ne peut pas être monté sur le cadre de la porte, vous pouvez connecter un

interrupteur magnétique d'extension supplémentaire au terminal d'extension pour monter le contact de porte à distance.

* Tous les dispositifs à contact sec dotés d'une boucle N.C. (fermeture normale) peuvent être connectés à la borne d'extension, faisant du contact de porte un émetteur universel.
* Plusieurs dispositifs à contact sec peuvent être câblés avec le contact de porte, comme indiqué dans l'image ci-dessous.

![](<.gitbook/assets/12 (7).jpeg>)

*
  *
    * La borne d'extension et l'interrupteur magnétique interne peuvent fonctionner ensemble pour déclencher le contact de porte lorsque l'un d'eux est activé ; vous pouvez également choisir de désactiver le commutateur magnétique interne via le réglage du cavalier JP3. Si la borne d'extension et l'interrupteur magnétique interne sont utilisés et que l'un d'entre eux est déclenché (ouvert), un signal de déclenchement sera envoyé au panneau de commande. Le contact de porte enverra un signal de fermeture (rétablissement) du contact de porte uniquement lorsque les deux sont fermés.
* _**Batterie**_
  * Le contact de porte est alimenté par une pile au lithium CR123 3V. Veuillez noter:**TOUJOURS**remplacez la batterie par une taille et une tension correctes.
  * Le contact de porte peut détecter des conditions de batterie faible. Lorsque la tension de la batterie est faible, un signal de batterie faible sera envoyé au panneau de commande pour indiquer la condition. La LED s'allumera lorsque le contact de porte est activé dans un état de batterie faible. Lorsque la batterie est épuisée, le contact de porte arrêtera toutes les fonctions et la LED clignotera toutes les 4 secondes.

![](<.gitbook/assets/13 (6).jpeg>)

2

*
  * Lors du changement de batterie, après avoir retiré la batterie usagée, appuyez deux fois sur l'interrupteur anti-sabotage pour la décharger complètement avant d'insérer une nouvelle batterie.
* _**Autoprotection**_
  * Le contact de porte est protégé par un interrupteur anti-sabotage qui est enfoncé contre la surface de montage lorsque le contact de porte est monté en place. Chaque fois que le couvercle du contact de porte est ouvert ou retiré de la surface de montage, l'interrupteur d'autoprotection sera activé et le contact de porte enverra un signal d'autoprotection pour rappeler à l'utilisateur la condition.
* _**Signal de surveillance**_
  * La fonction de supervision pour le modèle 868WF est contrôlée par le réglage du cavalier JP2. Pour le modèle non-868WF, la fonction de supervision est toujours activée.
  * Lorsqu'il est activé, le contact de porte transmettra automatiquement des signaux de supervision périodiquement au panneau de commande à des intervalles aléatoires de 30 à 50 minutes.
  * Si le panneau de commande n'a pas reçu le signal du contact de porte pendant une période prédéfinie, le panneau de commande indiquera que le contact de porte particulier rencontre un problème de manque de signal.
* _**Mode d'essai**_
  * En mode normal, appuyez sur le bouton de test pour transmettre un signal de test et un code d'apprentissage au panneau de commande. Le contact de porte entrera également en mode test pendant 3 minutes.
  * En mode test, la LED s'allumera chaque fois que le contact de porte est activé.
  * Chaque pression supplémentaire sur le bouton de test réinitialisera la période du mode test à 3 minutes.
* _**Commencer**_
  * Ouvrez le couvercle du contact de porte et insérez la batterie.
  * Mettez le panneau de commande en mode apprentissage (veuillez vous référer au manuel d'utilisation du panneau).
  * Appuyez sur le bouton de test du contact de porte.
  * Reportez-vous au manuel d'utilisation de votre panneau de commande pour terminer le processus d'apprentissage.
  * Une fois le contact de porte appris, placez le panneau de commande dans (\*\*Test de marche)\*\*mode, maintenez le contact de porte à l'emplacement souhaité et appuyez sur le bouton de test pour transmettre un signal de test au panneau de commande. Si le panneau de commande se trouve dans la plage du signal du contact de porte, le panneau affichera les informations du contact de porte en conséquence.
  * Procédez au montage et à l'installation une fois que vous êtes convaincu que le contact de porte fonctionne correctement à l'emplacement souhaité.

![](<.gitbook/assets/14 (8).jpeg>) ![](<.gitbook/assets/15 (7).jpeg>) ![](<.gitbook/assets/16 (7).jpeg>) ![](<.gitbook/assets/17 (7).jpeg>)

**Installation**

![](<.gitbook/assets/18 (7).jpeg>)

* _**Directive d'installation**_
  * Le contact de porte doit être installé sur le cadre de porte/fenêtre et l'aimant sur la porte/fenêtre.
  * La distance entre le contact de porte et l'aimant ne doit pas dépasser 15 mm lorsque la porte est fermée.
  * Évitez de monter le contact de porte sur des surfaces métalliques. Si un montage sur une surface métallique est nécessaire, assurez-vous de tester si le contact de porte peut être déclenché lorsque la porte est ouverte.
  * Montez le contact de porte aussi haut que possible.
* _**Montage du contact de porte**_

![](<.gitbook/assets/19 (3).jpeg>)

1. Trouvez un emplacement approprié à proximité de votre porte/fenêtre pour installer le contact de porte.
2. Le contact de porte comporte 2 marques de nervures sur un côté (voir l'image ci-dessous), marquant l'emplacement de l'interrupteur magnétique interne. Le contact de porte doit être installé soit verticalement, soit inversé pour garantir que le côté marqué par la nervure soit face à l'aimant.
3. Pour monter le contact de porte :
   1. Utilisez les 2 trous de montage du contact de porte comme modèle pour le positionnement approprié des trous.
   2. Utilisez les chevilles murales fournies pour l'installation en plâtre/brique.
   3. Vissez le contact de porte dans les chevilles murales fournies.
4. Pour monter l'aimant :
5. Utilisez les 2 trous de vis magnétiques comme modèle pour un positionnement approprié des trous.

_\<REMARQUE>_

*
  *
    * L'aimant ne doit pas être à plus de 15 mm du contact de porte lorsque la porte est fermée.
    * L'aimant doit s'aligner avec le côté marqué des nervures du contact de porte. Si nécessaire, appliquez l'entretoise magnétique à l'arrière de l'aimant pour mieux aligner l'aimant sur les marques de nervures.
  * Vissez l'aimant sur la porte.
  * Insérez les deux capuchons blancs dans les trous de vis magnétiques pour une intégrité esthétique.

![](<.gitbook/assets/20 (11).png>)

3

5.L'installation est maintenant terminée.

Déclaration FCC

Cet appareil est conforme à la partie 15 des règles FCC. L’exploitation est soumise aux deux conditions suivantes :

1. Cet appareil ne doit pas provoquer d'interférences nuisibles et
2. Cet appareil doit accepter toute interférence reçue, y compris les interférences susceptibles de provoquer un fonctionnement indésirable.

Attention FCC :

Pour garantir une conformité continue, tout changement ou modification non expressément approuvé par la partie responsable de la conformité peut annuler le droit de l'utilisateur à utiliser cet équipement. (Exemple : utilisez uniquement des câbles d'interface blindés lors de la connexion à un ordinateur ou à des périphériques).

4
