# VESTA 359

**Manuel d'utilisation du contact de porte filaire (DC-23-BUS)**

DC-23-BUS est un contact de porte filaire qui surveille l'ouverture/fermeture d'appareils spécifiés (par exemple, porte ou fenêtre). Le contact de porte filaire est fixé au cadre de l'appareil surveillé à l'aide d'un aimant d'actionnement fixé à l'appareil. Lorsque la porte ou la fenêtre s'ouvre, l'aimant s'éloigne du contact de porte filaire, activant un interrupteur magnétique interne, permettant au contact de porte filaire de transmettre des signaux d'alarme via BUS au panneau de commande.

Avec un terminal d'extension intégré, le DC-23-BUS peut également être connecté à un appareil filaire pour servir d'émetteur universel.

La conception du contact de porte filaire se compose d'un couvercle et d'une base. Le couvercle contient tous les composants électroniques et la base fournit un moyen de fixation de l'appareil. Un interrupteur anti-sabotage sur circuit imprimé fourni offre une protection contre l'ouverture et/ou le retrait non autorisé de l'appareil.

**Identification des pièces**

![](<.gitbook/assets/0 (2).jpeg>)

1. **Indicateur LED / Bouton Test**

Appuyez sur le bouton Test pour passer en mode test pendant 3 minutes.

1. **Vis de fixation du couvercle**
2. **Commutateur de cavalier d'entrée (JP2)**

![](<.gitbook/assets/1 (3).png>)

**Cavalier\*\*\*\*Cavalier**

![](<.gitbook/assets/2 (3).jpeg>) ![](<.gitbook/assets/3 (1) (1).jpeg>)

Le cavalier est inséré, reliant les deux. Le cavalier est retiré ou "**garé**" sur une

épingles. épingle.

*
  * Cavalier ON : Normalement fermé (N.C.) est défini.
  * Jumper OFF : Normalement ouvert (N.O.) est réglé\*\*(Défaut de fabrication)\*\*.

1. **Commutateur de cavalier de résistance de borne**

Lorsque le contact de porte est connecté en tant que périphérique BUS le plus éloigné sur une ligne BUS, veuillez régler le cavalier de résistance terminal du contact de porte et le commutateur de cavalier du premier périphérique BUS (généralement le panneau hybride) sur ON pour servir de résistances de terminaison. La capacité de communication de la ligne BUS connectée sera améliorée.

![](<.gitbook/assets/4 (2).png>)

**Cavalier**

Le cavalier est inséré, reliant les deux broches.

**Cavalier**

Le lien de cavalier est supprimé ou "**garé**» sur une épingle.

*
  * Si le cavalier est activé, la capacité de communication sera améliorée.
  * Si le cavalier est désactivé, la capacité de communication est au niveau normal.

1. **Terminal de bus**
2. **Borne d'extension**

En plus de l'interrupteur magnétique intégré, une borne de contact sec supplémentaire à 2 broches est fournie pour un interrupteur magnétique d'extension ou tout appareil avec le N.C. (normalement fermé) ou N.O. Fonctionnalité (normalement ouverte).

1. **Interrupteur anti-sabotage**

Lorsque le contact de porte filaire est monté, l'interrupteur anti-sabotage sera activé lorsque le couvercle est ouvert ou lorsque le contact de porte filaire est retiré de la surface de montage.

1. **Trous de montage**

Permet de fixer et visser le Contact de Porte directement sur le cadre de la porte ou sur le mur.

1

1. **Zone de séparation pour les trous de câblage (pour terminal de bus)**
2. **Aimant**
3. **Trou de vis magnétique**
4. **Entretoise magnétique**

**Caractéristiques**

![](<.gitbook/assets/5 (4).png>)

* _**Indicateur LED**_
  * En mode de fonctionnement normal, la LED ne s'allume pas lorsque le contact de porte filaire est activé.
  * Lorsque le couvercle du contact de porte filaire est ouvert ou que l'interrupteur anti-sabotage est déclenché, la LED clignote 3 fois. Lorsque la condition de sabotage persiste, la LED clignote 3 fois chaque fois que le contact de porte filaire est activé.
  * Lorsque le contact de porte filaire est en mode test, la LED clignote 3 fois à chaque fois qu'elle est activée.
* _**Borne d'extension**_

![](<.gitbook/assets/6 (2).png>)

Le DC-23-BUS dispose d'un terminal d'extension pour offrir une flexibilité accrue. Selon le réglage de JP2, le terminal d'extension forme une boucle fermée (normalement fermée (N.C.)) ou ouverte (normalement ouverte (N.O.)) avec l'appareil qui y est connecté. Lorsque l'appareil connecté au terminal d'extension est déclenché, le contact de porte filaire sera déclenché.

| Pour connecter l'appareil au terminal d'extension : | _**Vue de dessus du DC-23-BUS**_ |   |
| --------------------------------------------------- | -------------------------------- | - |
|                                                     |                                  |   |

![](<.gitbook/assets/7 (1).jpeg>)

1. Ouvrez le couvercle du contact de porte filaire avec un tournevis en desserrant la vis de fixation du couvercle au bas de l'appareil.
2. L'extrémité supérieure du boîtier avant présente une découpe en plastique plus fine. Percez l'ouverture défonçable pour créer un trou pour la connexion du câblage à la borne d'extension.
3. Connectez l'appareil au terminal d'extension.

![](<.gitbook/assets/8 (1).jpeg>)

Le terminal d'extension peut être utile dans les situations suivantes :

* Si le contact de porte filaire ne peut pas être monté sur le cadre de porte, vous pouvez connecter un interrupteur magnétique d'extension supplémentaire au terminal d'extension pour monter le contact de porte à distance.
* Tout appareil à contact sec avec un N.C. (Normal Fermé) ou N.O. La boucle (normalement ouverte) peut être connectée à la borne d'extension, ce qui fait que le contact de porte filaire sert d'émetteur universel.
* Plusieurs dispositifs à contact sec peuvent être câblés avec le contact de porte filaire, comme indiqué dans l'image ci-dessous.

![](<.gitbook/assets/9 (5).png>)

* _**Source de courant**_
  * Lorsque le DC-23-BUS est câblé à un panneau hybride, une alimentation de 13,5 V peut être fournie par le panneau hybride.
* _**Autoprotection**_
  * Le contact de porte filaire est protégé par un interrupteur anti-sabotage qui est comprimé contre la surface de montage lorsque le contact de porte filaire est monté en place. Chaque fois que le couvercle du contact de porte filaire est ouvert ou retiré de la surface de montage, l'interrupteur anti-sabotage sera activé et le contact de porte filaire enverra un signal d'ouverture anti-effraction pour rappeler à l'utilisateur la condition.
* _**Signal de surveillance**_
  * Le contact de porte filaire transmettra automatiquement des signaux de supervision périodiquement au panneau de commande à des intervalles aléatoires de 20 à 30 secondes.
  * Si le panneau de commande n'a pas reçu le signal du contact de porte filaire pendant une période prédéfinie, le panneau de commande indiquera que le contact de porte particulier rencontre un problème de manque de signal.
* _**Mode d'essai**_
  * En mode normal, appuyez sur le bouton Test pour transmettre un signal de test au panneau de commande. Le contact de porte filaire entrera en mode test pendant 3 minutes.
  * En mode test, la LED clignote 3 fois chaque fois que le contact de porte filaire est activé.
  * Chaque pression supplémentaire sur le bouton Test réinitialisera la période du mode Test à 3 minutes.

![](<.gitbook/assets/10 (5).png>) ![](<.gitbook/assets/11 (3).png>) ![](<.gitbook/assets/12 (4).png>)

2

* ![](<.gitbook/assets/13 (5).png>)_**Prudence**_
  * Le câblage du contact de porte ne doit être effectué que par des techniciens certifiés possédant les connaissances et la formation appropriées en matière d'équipement électrique.
  * Avant l'installation ou tout travail de maintenance, assurez-vous que l'alimentation électrique a été débranchée.
* _**Câblage des contacts de porte**_
  *
    * Avant de connecter le contact de porte filaire au BUS du système, veuillez couper l'alimentation.
    * Pour faciliter les connexions des câbles, les borniers de chaque module du système BUS sont codés par couleur.

![](<.gitbook/assets/14 (4).png>) ![](<.gitbook/assets/15 (2).jpeg>)

| **Rouge** | VDD  |
| --------- | ---- |
| **Noir**  | GND  |
| **Jaune** | 485A |
| **Vert**  | 485B |

* Plusieurs appareils BUS peuvent être connectés en série au panneau hybride. Pour une communication optimale des appareils de ligne BUS connectés, assurez-vous que les commutateurs de cavalier de résistance terminale du premier (généralement le panneau hybride) et des appareils BUS les plus éloignés sur une ligne BUS sont réglés. sur ON pour servir de résistances de terminaison. Assurez-vous d'activer uniquement les 2 cavaliers susmentionnés et de ne pas régler les cavaliers sur ON pour tout autre périphérique BUS intermédiaire.

_\\_

*
  * La conception enfichable des borniers BUS améliore l'efficacité de l'installation. Avant le câblage, vous pouvez retirer les borniers de la carte PCB pour faciliter l'utilisation et les rebrancher après le câblage.
  * Après avoir débranché le terminal, lors de la réinstallation du terminal sur la carte, assurez-vous d'installer le terminal dans la même direction pour éviter les dangers potentiels.
* Des connexions incorrectes entraîneront une panne ou un dysfonctionnement. Inspectez le câblage et assurez-vous que les connexions sont correctes avant de mettre sous tension.

![](<.gitbook/assets/16 (5).png>)

* _**Apprentissage**_

Veuillez suivre les étapes ci-dessous pour intégrer l'appareil au panneau hybride.

Étape 1 : Connectez l’appareil au panneau. Ensuite, allumez le panneau.

Étape 2 : Sur la page Web du Panel, cliquez sur «**Apprentissage**» pour accéder à la page d'apprentissage.

Étape 3 : Cliquez sur «**Commencer**» pour passer en mode apprentissage.

Étape 4 : Cliquez sur «**Ajouter**» pour inclure l'appareil dans le panneau.

Étape 5 : Si le périphérique est correctement appris dans le panneau, il sera affiché dans la section « Périphérique appris ».

* Une fois appris dans le panneau, le DC-23-BUS sera reconnu comme 2 appareils distincts et occupera 2 zones dans le panneau.

![](<.gitbook/assets/17 (3).png>)

3

![](<.gitbook/assets/18 (5).png>)

* Pour différencier les 2 appareils distincts, il est conseillé de renommer le nom de l'appareil par

en cliquant sur « Modifier » sous la liste des appareils après l'entrée dans la colonne des appareils.

Comme indiqué sur la page Device Edit, l'ID avec les deux derniers chiffres de "**00**" représente l'interrupteur magnétique interne.

![](<.gitbook/assets/19 (4).png>)

L’identifiant avec les deux derniers chiffres de «**02**" représente le terminal d'extension.

![](<.gitbook/assets/20 (4).png>)

* _**Identification**_

La fonction « Identifier » permet de localiser un périphérique BUS spécifique dans le système filaire BUS. Cette fonction est utile pour distinguer quel appareil est quel appareil, en particulier dans une grande installation où de nombreux appareils BUS sont inclus.

Pour localiser le contact de porte filaire dans le système BUS :

\*\*Étape 1.\*\*Sur la page Web du panneau hybride, cliquez sur « Identifier » sous la liste des appareils après l'entrée dans la colonne des appareils du DC-23-BUS.

\*\*Étape 2.\*\*Si le contact de porte filaire reçoit le signal du panneau hybride, la page Web affichera un message de réussite et l'indicateur LED du contact de porte filaire clignotera 10 fois pour indiquer à l'utilisateur où il se trouve.

_\\_

*
  *
    * Si un message de délai d'attente s'affiche sur la page Web, cela signifie que le contact de porte filaire n'a pas reçu le signal du panneau.

Veuillez vérifier si le DC-23-BUS est correctement connecté au panneau à une distance de câblage appropriée.

* _**Test de marche**_
  * Pour vous assurer que le contact de porte filaire est capable de communiquer avec le panneau après son apprentissage, placez le panneau de commande en mode test de marche et appuyez sur le bouton Test du DC-23-BUS pour transmettre un signal de test au panneau de commande.
  * Lorsque le panneau reçoit le signal de test, il émet un bip et affiche les informations du contact de porte filaire en conséquence en haut de la liste des appareils.

_\\_

* S'il n'y a pas de réponse du panneau après avoir appuyé sur le bouton de test, cela signifie que le panneau n'a pas reçu le signal de test de l'appareil.

Veuillez vérifier si le DC-23-BUS est correctement connecté au panneau à une distance de câblage appropriée.

**Installation**

* _**Directive d'installation**_
  * Le contact de porte filaire doit être installé sur le cadre de porte/fenêtre et l'aimant sur la porte/fenêtre.
  * La distance entre le contact de porte filaire et l'aimant ne doit pas dépasser 15 mm lorsque la porte est fermée.
  * Évitez de monter le contact de porte filaire sur des surfaces métalliques. S'il est monté sur des surfaces métalliques, assurez-vous de tester si le contact de porte filaire peut être déclenché lorsque la porte est ouverte.
  * Montez le contact de porte filaire aussi haut que possible.
* _**Montage du contact de porte filaire**_

1. Trouvez un emplacement approprié à proximité de votre porte/fenêtre pour installer le contact de porte filaire.
2. Le contact de porte filaire comporte 2 marques de nervures sur un côté (voir la figure), marquant l'emplacement de l'interrupteur magnétique interne. Le contact de porte filaire doit être installé verticalement ou inversé pour garantir que le côté marqué par la nervure soit face à l'aimant.
3. Pour monter le contact de porte filaire :
   *
     1. Utilisez les 2 trous de montage comme gabarit et percez des trous dans le cadre à monter.
     2. Utilisez les chevilles murales fournies pour l'installation en plâtre/brique.
     3. Vissez le contact de porte dans les chevilles murales fournies.
4. Pour monter l'aimant :
   1. Utilisez les 2 trous de vis magnétiques comme gabarit et percez des trous dans la porte/fenêtre à monter.

* _REMARQUE >_
  * L'aimant ne doit pas être à plus de 15 mm du contact de porte filaire lorsque la porte est fermée.
  * L'aimant doit être aligné avec le côté marqué des nervures du contact de porte filaire. Si nécessaire, appliquez l'entretoise magnétique à l'arrière de l'aimant pour mieux aligner l'aimant sur les marques de nervures.
  * Vissez l'aimant sur la porte/fenêtre.
  * Insérez les deux capuchons blancs dans les trous de vis magnétiques pour une intégrité esthétique.

1. L'installation est maintenant terminée.

4
