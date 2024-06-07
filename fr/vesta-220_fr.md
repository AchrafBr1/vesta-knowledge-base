# VESTA 220

**Commande de porte de garage Z-Wave (GDC-3)**

**Introduction**

GDC-3 est une commande de porte de garage Z-Wave qui se connecte à l'ouvre-porte de garage. Après avoir rejoint un réseau Z-Wave, le GDC-3 peut recevoir des commandes via le réseau Z-Wave pour activer l'ouvre-porte de garage connecté, offrant ainsi une opération pratique pour ouvrir ou fermer la porte de garage à distance.

Le GDC-3 comprend également un capteur d'inclinaison de porte de garage (Tilt-GDC3) qui peut être installé sur une porte de garage inclinable, ou un contact de porte de garage (DC-16SL-GDC3 / DC-32-EX-GDC3) qui peut être utilisé sur une porte de garage à ouverture horizontale pour signaler l'état de la porte de garage lorsque la porte de garage est « ouverte » ou « fermée ».

Avant que la porte de garage activée ne commence à bouger, les LED d'avertissement du GDC-3 clignoteront et la sirène intégrée émettra des bips d'alarme.

Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance. La commande de porte de garage Z-Wave permet d'accéder à la classe « S2 non authentifié » et prend en charge l'inclusion Z-Wave SmartStart ainsi que l'inclusion classique.

**Identification des pièces**

**GDC-3 (Contrôle de porte de garage)**

![](<.gitbook/assets/0 (90).jpeg>)

1. **Indicateur LED vert**
   * **Sur**: Connecté à l’alimentation électrique.
   * \*\*Clignote avec la LED rouge pendant 5 secondes :\*\*Avant que la porte du garage ne bouge.
2. **Indicateur LED rouge**
   * \*\*Clignote une fois par seconde :\*\*En mode apprentissage pour Tilt-GDC3.
   * \*\*Clignote une fois toutes les 5 secondes :\*\*Tilt-GDC3 faible en batterie
   * \*\*Clignote avec la LED verte pendant 5 secondes :\*\*Avant que la porte du garage ne bouge.
3. **Bouton de fonction**
   * Appuyez sur le bouton 3 fois en 1 seconde pour inclure ou exclure l'appareil dans/du réseau Z-Wave.
   * Appuyez et maintenez le bouton enfoncé pendant 10 secondes pour réinitialiser les paramètres d'usine.
   * Appuyez une fois sur le bouton pour ouvrir/fermer la porte du garage.
4. **Bornes de connexion**

Connectez-vous aux bornes de la console murale à bouton-poussoir sur l’ouvre-porte de garage.

1. **Prise DC (avec fonction de verrouillage)**

Branchez un adaptateur secteur DC 9V1A et faites-le pivoter de 90 degrés dans le sens des aiguilles d'une montre jusqu'à la position de verrouillage. Pour retirer l'adaptateur, faites-le pivoter de 90 degrés dans le sens inverse des aiguilles d'une montre jusqu'à la position ouverte d'origine et retirez-le.

1. **Bouton Apprendre**

Utilisez un outil pointu pour appuyer une fois sur le bouton d'apprentissage pour passer en mode d'apprentissage pour Tilt-GDC3.

1. **Trous de montage**
2. **Support de montage**

1

**Tilt-GDC3 (Capteur d'inclinaison de porte de garage)**

![](<.gitbook/assets/1 (77).jpeg>)

**1. Bouton de test/indicateur LED**

**Bouton de test :**

* Appuyez sur le bouton Test pour transmettre un code d'apprentissage au GDC-3.
* Appuyez sur le bouton Test pour signaler la position de la porte de garage et entrez en mode test pendant 3 minutes. En mode test, la LED s'allumera chaque fois que le capteur d'inclinaison de la porte de garage est activé.

**Indicateur LED :**

*
  * La LED clignote 3 fois lorsqu'elle transmet un code d'apprentissage.
  * La LED s'allumera chaque fois que l'appareil est déclenché en mode test.
  * La LED s'allumera chaque fois que l'interrupteur anti-sabotage est activé.
  * (Porte ouverte) En cas de panne de l'appareil ou en mode test, la LED clignote 6 fois.
  * (Porte fermée) En cas de panne de l'appareil ou en mode test, la LED clignote 6 fois. Après 10 secondes, la LED clignote 3 fois.
  * Lorsque la batterie est épuisée, le capteur d'inclinaison de porte de garage arrêtera toutes ses fonctions et la LED clignotera toutes les 4 secondes.

1. **Trous de montage**

Utilisé pour fixer et visser le capteur d'inclinaison de porte de garage directement sur la partie supérieure de la porte de garage.

**3. Interrupteur anti-sabotage**

Lorsque le capteur d'inclinaison de la porte de garage est monté, l'interrupteur anti-sabotage sera complètement enfoncé contre la porte de garage.

Lorsque le couvercle de l'appareil est ouvert ou lorsqu'il est retiré de la surface de montage, l'interrupteur anti-sabotage est activé.

La LED clignotera 6 fois et enverra un signal d'autoprotection pour informer les utilisateurs de cette condition.

1. **Isolateur de batterie**
2. **Compartiment à piles**

Le capteur d'inclinaison de porte de garage est alimenté par une pile au lithium CR123 3V. Lorsque la tension de la batterie est faible, un signal de batterie faible sera envoyé au panneau de commande pour informer les utilisateurs de cette condition.

**DC-16SL-GDC3 (Contact de porte de garage)**

![](<.gitbook/assets/2 (71).jpeg>)

**1. Indicateur LED**

En mode de fonctionnement normal, le voyant LED reste éteint sauf dans les situations suivantes :

\-Lorsque l’interrupteur anti-sabotage du contact de porte est déclenché.

2

*
  * Chaque fois que le contact de porte est activé en raison d'un déclenchement de sabotage ou d'une condition de batterie faible.
  * Chaque fois que le contact de porte est activé et transmet le signal en mode test.

1. **Bouton de test**
   * Appuyez sur le bouton Test pour transmettre un code d'apprentissage au GDC-3.
   * Appuyez sur le bouton Test pour signaler la position de la porte de garage et entrez en mode test pendant 3 minutes. En mode test, la LED s'allumera chaque fois que le contact de porte est activé.
2. **Compartiment à piles**

Le contact de porte est alimenté par un**Pile au lithium 3V CR2**. Lorsque la tension de la batterie est faible, un signal de batterie faible sera envoyé au panneau de commande pour informer les utilisateurs de cette condition.

1. **Trou de vis de fixation du couvercle**
2. **KO**
3. **Interrupteur anti-sabotage**

Il est conçu pour protéger contre le retrait non autorisé de l'emplacement de montage, l'ouverture du couvercle ou une installation instable. Lorsque l'autoprotection est déclenchée, un signal d'autoprotection sera signalé au panneau de commande via GDC-3 et la LED s'allumera également.

1. **Trou d'isolant de batterie**
2. **Marques de côtes**
3. **Aimant**

Montez l'aimant sur le côté du contact de porte où il comporte 2 marques de nervures pour indiquer la position de l'interrupteur magnétique interne. Le contact de porte doit être installé verticalement ou inversé pour garantir que le côté marqué par la nervure soit face à l'aimant.

1. **Aimant Trou de vis**
2. **Entretoise magnétique**

**DC-32-EX-GDC3 (Contact de porte de garage extérieur)**

![](<.gitbook/assets/3 (66).jpeg>)

1. **Couvercle de protection**
2. **Couvercle de la batterie**

3

\*\*3.\*\***Interrupteur anti-sabotage avant**

Lorsque le couvercle de la batterie est retiré, l'interrupteur anti-sabotage avant est activé.

1. **Indicateur LED**
2. **Bouton Apprendre/Test**

Utilisez un outil pointu pour appuyer sur le bouton pour transmettre le code d'apprentissage ou passer en mode test pendant 3 minutes.

Appuyez sur le bouton Test pour signaler la position de la porte de garage et entrez en mode test pendant 3 minutes. En mode test, la LED s'allumera chaque fois que le contact de porte est activé.

\*\*6.\*\***Compartiment à piles**

Le contact de porte utilise deux piles au lithium AA L91 comme source d'alimentation.

\*\*7.\*\***Interrupteur anti-sabotage arrière**

Chaque fois que le contact de porte est retiré de la surface de montage, l'interrupteur anti-sabotage arrière est activé.

1. **Crochets**
2. **Trous de verrouillage**
3. **KO**
4. **Zone de échappée**

**Commencer**

![](<.gitbook/assets/4 (75).png>)

* _**Apprenez Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 dans GDC-3**_

Allumez le tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 et connectez le GDC-3 à l'alimentation.

* Utilisez un outil pointu pour appuyer une fois sur le bouton d'apprentissage du GDC-3 pour passer en mode d'apprentissage. Le GDC-3 émettra un bip et la LED rouge commencera à clignoter.
* Appuyez sur le bouton de test de Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 pour envoyer un code d'apprentissage à GDC3, la LED clignotera 3 fois.
* Si l'apprentissage est réussi, le GDC-3 émettra 2 bips pour l'indiquer. Si Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 a déjà été ajouté dans GDC-3, GDC-3 émettra un son Di-Do pour alerter l'utilisateur.
* Utilisez un outil pointu pour appuyer à nouveau sur le bouton d'apprentissage du GDC-3 pour revenir au mode normal, la LED rouge s'éteindra. Alternativement, le GDC-3 quittera automatiquement le mode d'apprentissage avec 5 bips après 1 minute d'inactivité.

![](<.gitbook/assets/5 (76).png>)

*
  * _REMARQUE >_
    * La commande de porte de garage ne prend en charge qu'un seul capteur. Si un deuxième capteur (soit un capteur d'inclinaison, soit un contact de porte) est appris dans GDC-3, l'ancien capteur sera remplacé par le capteur nouvellement appris.
* _**Ajout de GDC-3 dans le système (inclusion)**_

![](<.gitbook/assets/6 (55).png>)

L'appareil prend en charge à la fois le processus d'inclusion classique et le processus d'inclusion SmartStart.

**Inclusion classique**

* Connectez le GDC-3 à l'alimentation
* Mettez la passerelle Z-wave ou le panneau de commande dans**Mode d'inclusion**(veuillez vous référer au manuel d'utilisation de la passerelle Z-wave ou du panneau de commande).
* En 1 seconde, appuyez 3 fois sur le bouton de fonction.
* Reportez-vous au manuel d'utilisation de la passerelle Z-wave ou du panneau de commande pour terminer le processus d'ajout.
* Si la commande de porte de garage a déjà été ajoutée/incluse dans une autre passerelle/panneau de commande Z-wave, ou si elle ne peut pas être ajoutée à la passerelle/panneau de commande Z-wave actuelle, essayez d'abord de la supprimer (voir\_**Suppression d'un périphérique**\_).

**Inclusion de SmartStart**

Les produits compatibles SmartStart peuvent être ajoutés à un réseau Z-Wave en scannant le code QR Z-Wave présent sur le produit avec un contrôleur fournissant l'inclusion SmartStart. Aucune autre action n'est requise et le produit SmartStart sera ajouté automatiquement dans les 10 minutes suivant sa mise sous tension à proximité du réseau. Z-Wave SmartStart utilise les informations DSK de l'appareil pour améliorer et simplifier le processus d'inclusion.**DSK**signifie Device Specific Key utilisé pour l’authentification et la communication cryptée. Les informations DSK sont stockées au format QR code qui est imprimé sur une étiquette et collée sur la face avant de l'appareil, comme dans l'exemple illustré à droite.

![](<.gitbook/assets/7 (45).jpeg>)

* Scannez le code QR au dos du GDC-3 pour obtenir le**DSK**Informations et transfert vers la passerelle Z-Wave.
* Connectez le GDC-3 à l'alimentation électrique, une demande d'inclusion SmartStart sera automatiquement envoyée à la passerelle.
* La passerelle inclura automatiquement l'appareil lors de la reconnaissance du

4

périphérique en faisant correspondre la demande d’inclusion avec le DSK obtenu.

![](<.gitbook/assets/8 (51).png>)

*
  * _REMARQUE>_
    * Le DSK de l'appareil n'est utilisé que lors de l'inclusion.
    * Le DSK peut être lu sans la mise sous tension du GDC-3, il est donc possible de préparer la passerelle pour inclure l'appareil avant d'installer et de mettre sous tension la commande de porte de garage.
    * Si GDC-3 a déjà été**inclus**(appris) dans une autre passerelle/panneau de configuration Z-Wave, veuillez d'abord l'exclure (voir\_**Exclusion**\_) avant de tenter de**inclure**dans la passerelle/panneau de configuration Z-Wave actuelle. GDC-3 n'enverra pas de demande d'inclusion SmartStart s'il se trouve déjà dans une passerelle/un panneau de configuration Z-Wave.
* _**Suppression de GDC-3 du système (exclusion)**_

![](<.gitbook/assets/9 (46).png>)

La commande de porte de garage doit être supprimée du réseau Z-wave existant avant d'être ajoutée à un autre.**Mode d'exclusion**

*
  *
    *
      * Mettez la passerelle Z-wave ou le panneau de commande dans**Mode d'exclusion**(veuillez vous référer au manuel d'utilisation de la passerelle Z-wave ou du panneau de commande).
      * Dans un délai d'une seconde, appuyez 3 fois sur le bouton de fonction et l'appareil sera supprimé du réseau Z-wave.

**Retour aux paramètres d'usine**

_(Utilisez la réinitialisation d'usine uniquement lorsque le panneau de configuration/passerelle réseau est manquant ou inutilisable)._

La réinitialisation d'usine de l'appareil le restaurera aux paramètres d'usine par défaut (c'est-à-dire qu'il n'est inclus dans aucun réseau Z-wave).

*
  *
    *
      * Appuyez et maintenez enfoncé le bouton de fonction de l'appareil pendant 10 secondes pour effectuer une réinitialisation d'usine.
  * _REMARQUE>_
    * Avant de supprimer ou de réinitialiser le GDC-3 aux paramètres d'usine, veuillez vous assurer que les informations DSK de l'appareil ont été supprimées ou n'existent pas dans la passerelle. Si vous supprimez ou réinitialisez l'appareil aux paramètres d'usine, mais que ses informations DSK existent toujours dans la passerelle, la passerelle inclura automatiquement à nouveau l'appareil.
* _**Test de portée**_

![](<.gitbook/assets/10 (48).png>) ![](<.gitbook/assets/11 (40).png>)

Pour tester si la commande de porte de garage est capable de communiquer avec la passerelle Z-Wave ou le panneau de commande :

* Mettez la passerelle/le panneau en mode test de portée (Walk Test).
* Appuyez sur le bouton de fonction de l'appareil.
* La passerelle/panneau de commande doit afficher si l'appareil se trouve dans la plage de fonctionnement (veuillez vous référer au manuel d'utilisation de la passerelle/panneau de commande).

**Installation**

![](<.gitbook/assets/12 (25).jpeg>)

**Montage du capteur d'inclinaison de porte de garage (Tilt-GDC3)**

* Le capteur d'inclinaison de porte de garage est conçu pour être monté sur une porte de garage basculante ou basculante, et non pour être utilisé sur une porte de garage enroulable. Il est utilisé pour signaler l'état lorsque la porte de garage est « ouverte », « fermée » ou en mouvement.
* L'appareil doit être monté verticalement par rapport au sol (il ne doit pas être incliné de plus de +-5 degrés une fois monté).
* Montez l'appareil sur une surface sèche et propre. Assurez-vous que l'appareil est monté avec l'indicateur LED sur le dessus.
* Le capteur d'inclinaison de porte de garage doit être monté tout en haut du panneau de la porte de garage, comme indiqué ci-dessous.

![](<.gitbook/assets/13 (31).jpeg>)

* Il existe deux façons de monter le capteur d'inclinaison de porte de garage. Montage à vis :
  1. Trouvez un emplacement approprié pour installer le capteur d'inclinaison de porte de garage. La surface de montage doit être propre et sèche. Nettoyez soigneusement la surface de montage si nécessaire.
  2. Utilisez les deux trous de montage comme modèle pour marquer et percer les trous de montage.
  3. Utilisez les chevilles murales fournies pour l'installation en plâtre/brique. Vissez le capteur d'inclinaison de la porte de garage dans les chevilles murales fournies. Assurez-vous que les chevilles murales affleurent la surface de montage.

![](<.gitbook/assets/14 (29).png>)

5

* ![](<.gitbook/assets/15 (29).png>)_REMARQUE>_
  * N'utilisez ce type de méthode de montage que lorsque les portes de garage sont plus épaisses que la longueur des vis.

![](<.gitbook/assets/16 (31).png>)

Montage adhésif :

1. Trouvez un emplacement approprié pour installer le capteur d'inclinaison de porte de garage. La surface de montage doit être propre et sèche. Nettoyez soigneusement la surface de montage si nécessaire.
2. Retirez un côté des doublures du tampon adhésif double face. Appliquez-le à l'arrière du capteur d'inclinaison de porte de garage et appuyez fermement pendant 30 secondes pour assurer un bon contact.
3. Retirez la doublure restante sur le tampon adhésif et appuyez fermement sur le capteur d'inclinaison de porte de garage à l'endroit souhaité pendant 30 secondes supplémentaires. Veuillez éviter d'appliquer le tampon adhésif sur une surface inégale ou de le réappliquer.

**Montage du contact de porte de garage (DC-16SL-GDC3)**

* Le contact de porte est conçu pour être utilisé sur une porte de garage à ouverture horizontale pour signaler l'état de la porte de garage lorsque la porte de garage est « ouverte » ou « fermée ».
* Veuillez installer le contact de porte sur l'objet le plus fixe (tel que le cadre de la porte) et monter l'aimant sur l'objet le plus mobile (tel que la porte de garage).

![](<.gitbook/assets/17 (20).jpeg>)

* Montez l'aimant à l'aide des vis fournies. Alignez l'aimant en fonction de la marque de nervure sur le contact de porte.
* Si nécessaire, utilisez l'entretoise magnétique pour mieux aligner l'aimant sur les marques de nervures.
  *
    * _REMARQUE >_
      * L'aimant ne doit pas être à plus de 15 mm du contact de porte lorsque la porte est fermée.
      * Les deux capuchons blancs fournis peuvent être insérés dans les trous de vis de l'aimant pour une intégrité esthétique.
* Il existe deux manières de monter le contact de porte : montage autocollant ou montage par vis. Montage autocollant :
  1. La surface de montage doit être propre, sèche et lisse. Nettoyer la surface de montage avec un dégraissant adapté si nécessaire.
  2. Retirez un côté des doublures du tampon adhésif double face. Appliquez le tampon adhésif au dos de l'appareil et appuyez fermement pendant 30 secondes pour assurer un bon contact.
  3. Retirez le revêtement restant sur le tampon adhésif et appuyez fermement sur le contact de porte à l'emplacement souhaité pendant 30 secondes.

_\\_

*
  *
    *
      * N'utilisez pas la méthode d'installation du tampon adhésif sur une surface dont la peinture est écaillée ou craquelée, ou sur une surface rugueuse.
      * Veuillez ne pas réappliquer le tampon adhésif 3M. Il ne peut pas être réutilisé

![](<.gitbook/assets/18 (30).png>) ![](<.gitbook/assets/19 (31).png>) ![](<.gitbook/assets/20 (22).png>)

Montage à vis :

La base comporte deux découpes, là où le plastique est plus fin, à des fins de montage.

Pour monter le contact de porte :

1. Retirez le couvercle en dévissant la vis de fixation du couvercle avec un tournevis cruciforme.
2. Brisez les trous sur la base.
3. Utilisez les trous comme gabarit et percez deux trous.
4. Insérez des chevilles murales si vous fixez dans du plâtre ou de la brique.
5. Vissez la base dans la prise murale avec un tournevis cruciforme.
6. Fixez le couvercle à la base et serrez la vis de fixation du couvercle.

**Montage du contact de porte de garage extérieur (DC-32-EX-GDC3)**

* Le contact de porte étanche est conçu pour être utilisé sur une porte de garage à ouverture horizontale pour signaler l'état du 6

porte de garage lorsque la porte de garage est « ouverte » ou « fermée ».

* Il est recommandé de placer le Contact de Porte sur le cadre fixe de la porte de garage, et l'aimant sur la porte de garage.
* Les marques de nervures sur l'aimant et le contact de porte doivent être alignées (**FIGUE. 1**).
* L'aimant ne doit pas être à plus de 3 cm du côté marqué du contact de porte lorsque la porte est fermée.
* Le contact de porte est doté d'un interrupteur anti-sabotage sur son couvercle arrière. Assurez-vous que l'appareil est positionné à l'intérieur du support de manière à ce que le ressort de l'interrupteur anti-sabotage soit appuyé contre la zone de séparation qui est lâchement connectée au support.

Si le contact de porte est retiré du mur de force, la zone de séparation se détachera du support et restera attachée à la surface de montage, activant ainsi l'interrupteur anti-sabotage.

**FIGUE. 1**

* Pour monter le contact de porte :
  *
    1. Le support de montage fourni comporte 3 découpes où le plastique est plus fin et peut être cassé à des fins de montage. (**FIGUE. 2**)
    2. Utilisez le support de montage comme modèle pour percer des trous dans le mur pour les chevilles. (**FIGUE. 3**)
    3. Enfoncez les chevilles et fixez le support de montage au mur avec les vis.
    4. Montez le contact de porte avec les crochets du couvercle arrière du contact de porte verrouillés sur les trous de verrouillage du support de montage, puis poussez vers le bas pour verrouiller le crochet. (**FIGUE. 4**)
  * _REMARQUE >_
    *
      * Assurez-vous que l'interrupteur anti-sabotage arrière du contact de porte est appuyé contre la zone de séparation du support de montage.

**FIGUE. 2**

 Fixez les vis de fixation inférieures.

5\)Remettez le couvercle de protection en place.

 Il existe deux façons de monter l'aimant : le montage adhésif et le montage par vis.

 Montage par vis :

1. Vissez le support de montage à la porte avec les deux vis fournies.
2. Fixez l'aimant au support de montage.

_\\_

* L'entretoise magnétique fournie peut être utilisée en faisant toucher le côté avec les mots noirs au support de montage.

entre l'aimant et la porte pour faciliter l'alignement et l'installation.

7

* Montage adhésif :
  1. Vous pouvez également utiliser le ruban adhésif double face fourni pour fixer directement l'aimant à la porte.

_\\_

*
  *
    * Assurez-vous que la surface de montage doit être propre, sèche et lisse avant de fixer l'aimant avec du ruban adhésif double face sur la porte et que l'aimant doit être fermement appuyé contre la porte pendant 30 secondes.
  * L'installation est maintenant terminée.

**FIGUE. 3**

**FIGUE. 4**

**Montage de la commande de porte de garage (GDC-3)**

* La commande de porte de garage est généralement montée au plafond, près de l'ouvre-porte de garage et de la prise de courant.

8

_**AVERTISSEMENT :**_

*
  1. Avant l'installation, assurez-vous de débrancher l'alimentation électrique de l'ouvre-porte de garage.
     1. La commande de porte de garage GDC-3 doit être installée en vue de la porte de garage, où les alarmes visuelles et sonores peuvent être clairement vues et entendues.

1. Utilisez le support de montage comme modèle, marquez les deux trous de montage, percez des trous dans l'emplacement de montage et insérez des chevilles murales si nécessaire.
2. Vissez le support de montage à l'emplacement marqué avec les deux crochets tournés vers l'extérieur.
3. Accrochez la commande de porte de garage au support de montage mural (avec les trous de montage de la commande de porte de garage).
4. Poussez la commande de porte de garage (dans la direction indiquée sur l'image ci-dessous) pour la verrouiller dans le support de montage.
5. Connectez les bornes GDC-3 aux bornes de la console murale à bouton-poussoir de l'ouvre-porte de garage. L’un ou l’autre fil peut être connecté à l’une ou l’autre borne. (Les terminaux de console murale peuvent être nommés « PWC », « WC », « PB », « PUSHBUTTON » ou « RED » et « WHITE ». Les noms et emplacements des terminaux varient selon le modèle.)
6. Branchez l'adaptateur secteur de sortie DC 9 V 1 A et connectez-le à l'alimentation.
7. Rétablissez l’alimentation de votre ouvre-porte de garage.

9

**Opération**

* _**Fonctionnement de la porte de garage**_
  * Une fois que GDC-3 a été inclus dans le réseau Z-Wave, la passerelle Z-Wave peut ouvrir ou fermer la porte de garage à distance avec Z-Wave

commande\[COMMANDE\_CLASSE\_BARRIÈRE\_OPÉRATEUR] et\[BARRIÈRE\_OPÉRATEUR\_SET], en utilisant les paramètres ci-dessous :

*
  *
    * Ouvert : Valeur cible = 0xFF
    * Fermer : Valeur cible = 0x00
  * Les utilisateurs peuvent également appuyer une fois sur le bouton de fonction pour ouvrir/fermer la porte du garage.
  * Avant que la porte de garage activée ne commence à bouger, les indicateurs LED d'avertissement (vert et rouge) clignoteront et des bips d'alarme retentiront pendant 5 secondes. Lorsque la porte de garage commence à bouger, la position de la porte de garage sera signalée à la passerelle Z-Wave.

\[COMMANDE\_CLASSE\_BARRIÈRE\_OPÉRATEUR]\[BARRIÈRE\_OPÉRATEUR\_RAPPORT] état :

|  | BARRIÈRE\_OPÉRATEUR\_FERMÉ     | 0x00 |
| - | ------------------------------ | ---- |
|  | BARRIÈRE\_OPÉRATEUR\_FERMETURE | 0xFC |
|  | BARRIÈRE\_OPÉRATEUR\_ARRÊTÉ    | 0xFD |
|  | BARRIÈRE\_OPÉRATEUR\_OUVERTURE | 0xFE |
|  | BARRIÈRE\_OPÉRATEUR\_OUVRIR    | 0xFF |

*
  * Une fois que le GDC-3 démarre le mouvement de la porte de garage, vous devrez attendre 35 secondes que la porte de garage s'ouvre ou se ferme complètement avant de pouvoir envoyer une deuxième commande d'ouverture/fermeture ou appuyer sur le bouton de fonction pour ouvrir/fermer. Si une deuxième commande est envoyée ou si le bouton de fonction est enfoncé dans les 35 secondes, GDC-3 enverra un signal occupé à la passerelle Z-Wave.

\[COMMANDE\_CLASSE\_APPLICATION\_STATUT]\[APPLICATION\_OCCUPÉ]

*
  *
    *
      * Statut : 0x00
      * Temps d'attente : 0x00
    * Lorsque la porte du garage est ouverte, GDC-3 contournera toute commande d'ouverture de la passerelle Z-Wave. Lorsque la porte du garage est fermée, GDC-3 contournera toute commande de fermeture de la passerelle Z-Wave.
* _**Volume sonore de l'alarme**_
  *
    * Avant que la porte de garage activée ne commence à bouger, les indicateurs LED d'avertissement clignoteront et des bips d'alarme retentiront pendant 5 secondes. Les utilisateurs peuvent régler le volume sonore de l'alarme en envoyant une commande depuis la passerelle Z-Wave avec la commande Configuration CC, en utilisant les paramètres ci-dessous :

10

* S : Taille
* D : Par défaut

| Non. | Nom                       | S | Min. | Max. | D | Description    |
| ---- | ------------------------- | - | ---- | ---- | - | -------------- |
|      |                           |   |      |      |   |                |
| 1    | Niveau sonore de l'alarme | 1 | 0    | 2    | 2 | 0 : silencieux |
|      |                           |   |      |      |   | 1 : petit      |
|      |                           |   |      |      |   | 2 : fort       |
|      |                           |   |      |      |   |                |

* _**Caractéristiques du capteur d'inclinaison de porte de garage (Tilt-GDC3) / contact de porte (DC-16SL-GDC3) / contact de porte extérieure (DC-32-EX-GDC3)**_
  * Détection de position de porte de garage

Chaque fois que la position de la porte de garage change, Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 signalera la position de la porte au GDC-3, et GDC-3 signalera à la passerelle Z-Wave avec Z -Commande Wave

\[COMMANDE\_CLASSE\_BARRIÈRE\_OPÉRATEUR]\[BARRIÈRE\_OPÉRATEUR\_RAPPORT].

|  | BARRIÈRE\_OPÉRATEUR\_FERMÉ     | 0x00                             |
| - | ------------------------------ | -------------------------------- |
|  | BARRIÈRE\_OPÉRATEUR\_FERMETURE | 0xFC (pour Tilt-GDC3 uniquement) |
|  | BARRIÈRE\_OPÉRATEUR\_ARRÊTÉ    | 0xFD (pour Tilt-GDC3 uniquement) |
|  | BARRIÈRE\_OPÉRATEUR\_OUVERTURE | 0xFE (pour Tilt-GDC3 uniquement) |
|  | BARRIÈRE\_OPÉRATEUR\_OUVRIR    | 0xFF                             |

* Autoprotection

Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 est protégé par un interrupteur anti-sabotage. Lorsque l'appareil est retiré de la surface de montage ou lorsque le couvercle de l'appareil est ouvert, son interrupteur anti-sabotage est activé. L'appareil enverra ensuite un signal d'ouverture de sécurité au GDC-3, et le GDC-3 fera rapport à la passerelle Z-Wave avec la commande Z-Wave.\[COMMANDE\_CLASSE\_NOTIFICATION]\[NOTIFICATION\_RAPPORT].

*
  * Ouvert : 00 00 00 FF 07 03 00 00
  * Fermeture : 00 00 00 FF 07 00 01 03
* Signal de surveillance

Le Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 transmettra le signal de supervision ainsi que la position de la porte de garage au GDC-3 toutes les 15 à 20 minutes. GDC-3 fera rapport à la passerelle Z-Wave en utilisant\[BARRIÈRE\_OPÉRATEUR\_RAPPORT].

Si la passerelle Z-Wave ne parvient pas à recevoir de signaux de supervision du Tilt-GDC3 / DC-16SL-GDC / DC-32-EX-GDC pendant une période de temps prédéfinie, un message d'erreur « Hors service » sera affiché. généré.

*
  * Erreur de supervision : 00 00 00 FF 06 49 00
  * Restauration : 00 00 00 FF 06 00 00 (l'état de la batterie et le signal de supervision doivent revenir à la normale)
* Batterie faible

Le Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 dispose de la fonction de détection de batterie faible. Lorsque la tension de la batterie est faible, le capteur d'inclinaison/contact de porte transmettra un signal de batterie faible au GDC-3, et le GDC-3 fera rapport à la passerelle Z-Wave avec la commande Z-Wave.\[COMMANDE\_CLASSE\_NOTIFICATION]\[NOTIFICATION\_RAPPORT].

*
  * Batterie faible : 00 00 00 FF 06 4A 00
  * Restauration : 00 00 00 FF 06 00 00 (l'état de la batterie et le signal de supervision doivent revenir à la normale)

**Informations sur la vague Z**

\*\*Type d'appareil:\*\*GÉNÉRIQUE\_TAPER\_ENTRÉE\_CONTRÔLE

\*\*Type spécifique :\*\*SPÉCIFIQUE\_TAPER\_SÉCURISÉ\_BARRIÈRE\_AJOUTER SUR

\*\*Type d'icône :\*\*ICÔNE\_TAPER\_GÉNÉRIQUE\_BARRIÈRE

\*\*Type de rôle :\*\*Toujours sur esclave (AOS)

\*\*Sécurité:\*\*Mauvais\_NON AUTHENTIFIÉ

\*\*Identifiant du fabricant :\*\*0x018E

\*\*ID du type de produit :\*\*0x0004

\*\*Identifiant du produit :\*\*0x0127

* _**Classe de commande prise en charge**_

11

| **Classe de commande**                      | **Version** | **Classe de sécurité requise**             |
| ------------------------------------------- | ----------- | ------------------------------------------ |
|                                             |             |                                            |
| Association                                 | 2           | Classe de sécurité accordée la plus élevée |
|                                             |             |                                            |
| Informations sur le groupe d'associations   | 3           | Classe de sécurité accordée la plus élevée |
|                                             |             |                                            |
| Basique                                     | 2           | Classe de sécurité accordée la plus élevée |
|                                             |             |                                            |
| Réinitialisation de l'appareil localement   | 1           | Classe de sécurité accordée la plus élevée |
|                                             |             |                                            |
| Métadonnées de mise à jour du micrologiciel | 5           | Classe de sécurité accordée la plus élevée |
|                                             |             |                                            |
| Spécifique à la fabrication                 | 2           | Classe de sécurité accordée la plus élevée |
|                                             |             |                                            |
| Multicanal                                  | 4           | Classe de sécurité accordée la plus élevée |
|                                             |             |                                            |
| Association multicanal                      | 3           | Classe de sécurité accordée la plus élevée |
|                                             |             |                                            |
| Niveau d'énergie                            | 1           | Classe de sécurité accordée la plus élevée |
|                                             |             |                                            |
| Configuration                               | 1           | Classe de sécurité accordée la plus élevée |
|                                             |             |                                            |
| Notification                                | 8           | Classe de sécurité accordée la plus élevée |
|                                             |             |                                            |
| Opérateur de barrière                       | 1           | Classe de sécurité accordée la plus élevée |
|                                             |             |                                            |
| État de la candidature                      | 1           | Classe de sécurité accordée la plus élevée |
|                                             |             |                                            |
| Version                                     | 3           | Classe de sécurité accordée la plus élevée |
|                                             |             |                                            |
| Service de transport                        | 2           | Aucun                                      |
|                                             |             |                                            |
| Informations sur Z-Wave Plus                | 2           | Aucun                                      |
|                                             |             |                                            |
| Sécurité 2                                  | 1           | Aucun                                      |
|                                             |             |                                            |
| Surveillance                                | 1           | Aucun                                      |
|                                             |             |                                            |

* _**Groupes associatifs**_

| **IDENTIFIANT** | **Nom**           | **Max.** | **Description**                                                                                           |
| --------------- | ----------------- | -------- | --------------------------------------------------------------------------------------------------------- |
|                 |                   | **Nœud** |                                                                                                           |
|                 |                   |          |                                                                                                           |
| 1               | Corde de sécurité | 5        | Prend en charge les classes de commandes suivantes :                                                      |
|                 |                   |          |  Rapport de notification : déclenché par une altération, une batterie faible, une erreur de supervision. |
|                 |                   |          |  Rapport Opérateur Barrière : GDC ouvert/fermé.                                                          |
|                 |                   |          |  Rapport d'application occupée : déclenché à partir du jeu d'opérateur de barrière dans les 35 secondes. |
|                 |                   |          |  Réinitialisation locale de l'appareil : déclenchée lors de la réinitialisation                          |
|                 |                   |          |                                                                                                           |

12
