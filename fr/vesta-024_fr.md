---
icon: circle-chevron-right
---

# VESTA 024

**VST-862EX**

## <mark style="color:green;">**PIRCAM Extérieur**</mark>&#x20;

### _<mark style="background-color:yellow;">**Introduction**</mark>_

VST-862EX est un détecteur de mouvement infrarouge passif (PIR) avec caméra. Il est capable d'envoyer des signaux sans fil et des images capturées (qualité d'image jusqu'à 640 x 480 pixels) à la centrale lors de la détection de mouvement.\
Doté d'une capacité d'éclairage nocturne, d'un boîtier résistant aux UV et étanche selon la norme IP45, le VST-862EX est idéal pour les jardins, les pelouses, les portails, les couloirs et les allées.\
Le PIRCAM extérieur est conçu pour offrir une portée de détection de 10 mètres lorsqu'il est installé à 2 mètres au-dessus du sol. Il offre une immunité aux animaux jusqu'à 60 kilos avec deux niveaux de sensibilité sélectionnables pour s'adapter à différents environnements.\
Le VST-862EX est également compatible avec le répéteur RP-29/routeur RMB-29 de Climax, qui peut étendre davantage la portée de communication RF dans les zones difficiles d'accès.

**La série VST-862EX comprend les modèles suivants**:\
VST-862EX – Détecteur de mouvement PIR  avec caméra et LED blanche\
VST-862EX-IL – Détecteur de mouvement PIR avec caméra et LED infrarouge

### _<mark style="background-color:yellow;">**Identification**</mark>_

![](<.gitbook/assets/1 (22).jpeg>)

![](<.gitbook/assets/0 (27).jpeg>)

1. **LED blanche/LED infrarouge**\
   La LED blanche (pour le VST-862EX) ou la LED infrarouge (pour le VST-862EX-IL) fournissent suffisamment de lumière pour la capture d'images dans des conditions de faible luminosité.
2. **Indicateur LED (rouge)**\
   Le voyant LED est utilisé pour indiquer l'état du système.
3. **Capteur IR**\
   Le capteur est destiné à détecter les objets en mouvement.
4. **Objectif du PIRCAM**
5. **Bouton Test\Apprentissage**\
   \- Maintenir appuyé le bouton pendant 3 secondes pour envoyer un code d'apprentissage, puis relâchez le bouton lorsque la LED rouge s'allume.\
   \- Appuyez une fois sur le bouton pour passer en mode test pendant 10 minutes.\
   \- Appuyez une fois sur le bouton pour envoyer un code d'apprentissage au répéteur/routeur.
6. **Autoprotection**
7. **Interrupteurs DIP**\
   Il y a 8 interrupteurs DIP pour régler les fonctions et la sensibilité de détections.
8. **Compartiment à piles**
9. **Support de fixation**

### _<mark style="background-color:yellow;">**Voyant LED**</mark>_

Lorsqu'il est activé, le voyant LED s'allume dans les conditions suivantes :\
\- Lorsque l'autoprotection est déclenchée, la LED clignote 6 fois pour indiquer qu'elle transmet un signal "**Autoprotection**".\
\- Lorsque le PIRCAM est en condition de défaut (autoprotection, batterie basse persistante), chaque fois qu'il transmet un mouvement, la LED clignote 6 fois.\
\- Après avoir appuyé une fois sur le bouton Test pour passer en mode Test, la LED clignote pendant 60 secondes pour indiquer que le PIRCAM est en train de démarrer.\
\- En mode Test, la LED s'allumera pendant 2 secondes chaque fois qu'un mouvement est détecté.

{% hint style="info" %}
NOTE:

L'indicateur LED peut être activé en réglant le DIP Switch 2 sur la position ON. Prière de se référer au **Tableau de position des DIP switchs** pour plus de détails.
{% endhint %}

### _<mark style="background-color:yellow;">**Capture d'image**</mark>_

Lorsque le système d'alarme est armé, le PIRCAM capturera 1, 3 ou 6 images d'alarme en résolutions 640 x 480 ou 320 x 240 (programmable depuis la centrale) lors de la détection de mouvement. Vous pouvez également demander manuellement au PIRCAM de prendre une photo via la centrale. Les images capturées seront transférées à la centrale pour vérification visuelle des alarmes.

{% hint style="info" %}
NOTE:

Si votre PIRCAM est installé à un endroit où la scène est un environnement complexe avec une lumière intense ou beaucoup de couleurs, les images capturées seront de grande taille, ce qui pourrait entraîner une coupure lorsque les images sont transmises à la centrale.
{% endhint %}

### _<mark style="background-color:yellow;">**Période de démarrage**</mark>_

Le PIRCAM à une période de démarrage de 60 secondes dans les conditions suivantes :\
\- Lorsque le PIRCAM est activé par la centrale en cas d'armement u d'armement avec défaut.\
\- Lorsque le bouton Test est utilisé une fois pour entrer en mode test.\
La LED rouge clignotera lentement pendant la période de démarrage. Pendant cette période de 60 secondes, le PIRCAM ne sera pas actif.

### _<mark style="background-color:yellow;">**Mode Test**</mark>_

* Le PIRCAM peut être mise en mode Test pendant 10 minutes en appuyant une fois sur le bouton Test. En mode Test, les fonctions de minuterie de mise en veille et de capture d'image sont désactivées. Le voyant LED s'allume pendant deux secondes chaque fois qu'un mouvement est détecté. Le PIRCAM quittera automatiquement le mode test après 10 minutes et reviendra en mode normal.
* Pour mettre le PIRCAM en mode test constamment, veuillez régler le DIP switch 1 sur ON (veuillez consulter le **Tableau de position des DIP switchs** pour plus de détails).

### _<mark style="background-color:yellow;">**Supervision**</mark>_

* Après l'installation, le PIRCAM transmettra automatiquement et périodiquement des signaux de supervision à la centrale aléatoirement de 30 à 50 minutes.
* Si la centrale ne reçoit le signal du PIRCAM pendant la période de temps définie, la centrale indiquera sur son écran que le PIRCAM rencontre un problème de perte de signal.

### _<mark style="background-color:yellow;">**Mise en veille**</mark>_

Le PIRCAM dispose d'une « mise en veille » automatique d'environ une minute pour économiser l'énergie. Après avoir transmis la détection d'un mouvement, le PIRCAM ne retransmettra pas pendant une minute. Tout autre mouvement détecté au cours de cette période de veille d’une minute prolongera la durée de veille minute supplémentaire. De cette façon, un mouvement continu devant le PIRCAM n’épuisera pas la batterie.

### _<mark style="background-color:yellow;">**Fonction double détection**</mark>_

Le PIRCAM à une fonction de double détection. Si cette fonction est activée, le PIRCAM signalera une alarme à la centrale uniquement si deux mouvements sont détectés dans les 10 secondes. Si la fonction double détection est désactivée, le PIRCAM signalera une alarme à la centrale lorsqu'un mouvement est détecté.

### _<mark style="background-color:yellow;">**Autoprotection**</mark>_

Le PIRCAM est protégée par une autoprotection qui est comprimée lorsque le PIRCAM est fixé à son support. Lorsque le PIRCAM est retiré de sons support, l'autoprotection sera activée et le PIRCAM enverra un signal d'autoprotection à la centrale pour informer l'utilisateur de cette condition.

### _<mark style="background-color:yellow;">**Tableau de position des DIP switchs**</mark>_

La fonction de chaque switch DIP est répertoriée dans le tableau ci-dessous. Le switch DIP est soit activé, soit désactivé. La position haute indique ON et la position basse indique OFF.

![](<.gitbook/assets/2 (37).png>)

| DIP      | Position | Fonction                                                                     |
| -------- | -------- | ---------------------------------------------------------------------------- |
| Switch 1 | ON       | Mode Test                                                                    |
|          | OFF      | Mode Normal (par défaut)                                                     |
| Switch 2 | ON       | Led activée (par défaut)                                                     |
|          | OFF      | Led désactivée                                                               |
| Switch 3 | ON       | PIR faisant face à un mur                                                    |
|          | OFF      | PIUR faisant face à une scène ouverte (aucune mur dans les 10m) (par défaut) |
| Switch 4 | ON       | PIR faisant face à une espace végétalisée (pelouse) (par défaut)             |
|          | OFF      | PIR faisant face à une scène maçonnée (béton, pavets)                        |
| Switch 5 | Switch 6 | Sensibilité immunité animaux                                                 |
| ON       | ON       | Basse, 60kg (par défaut)                                                     |
| ON       | OFF      | Haute, 35kg                                                                  |
| OFF      | ON       | non utilisé                                                                  |
| OFF      | OFF      | non utilisé                                                                  |
| Switch 7 | ON       | Double détection activée (par défaut)                                        |
|          | OFF      | Double détection désactivée                                                  |
| Switch 8 | ON       | Immunité animaux activée (par défaut)                                        |
|          | OFF      | Immunité animaux désactivée                                                  |

{% hint style="info" %}
NOTE:\
Après avoir modifié la position des switchs, veuillez rallumer le PIRCAM afin qu'il fonctionne avec les nouveaux paramètres.
{% endhint %}

### _<mark style="background-color:yellow;">**Batterie**</mark>_

* La caméra PIR utilise quatre piles au lithium AAL91 comme source d'alimentation.
* La caméra PIR dispose d'une détection de tension de batterie faible. Lorsqu'une batterie faible est détectée, un signal de batterie faible sera envoyé au panneau de commande avec des transmissions de signal régulières pour que le panneau de commande affiche l'état en conséquence.
* **Pour changer les piles :**

\*\*Étape 1:\*\*Retirez la caméra PIR de la position de montage et desserrez la vis de fixation du couvercle arrière.

\*\*Étape 2:\*\*Insérez un tournevis à tête plate dans la zone évidée du capot arrière, puis soulevez délicatement le capot arrière.

![](<.gitbook/assets/3 (34).png>)

\*\*Étape 3:\*\*Retirez les anciennes piles et appuyez deux fois sur le bouton test pour les décharger complètement.

\*\*Étape 4:\*\*Insérez quatre nouvelles piles au lithium AAL91.

\*\*Étape 5 :\*\*Appuyez une fois sur le bouton de test. Un signal de batterie normale sera envoyé au panneau de commande.

\*\*Étape 6 :\*\*Revissez le capot arrière.

\*\*Étape 7 :\*\*Remontez la caméra PIR à l'emplacement de montage.

* _**Mise en route – Apprentissage de la caméra PIR dans le panneau de commande**_
  * Desserrez la vis de fixation inférieure, puis insérez un tournevis à tête plate pour soulever le capot arrière.
  * En fonction de vos besoins, réglez le commutateur de sensibilité comme indiqué dans\_Tableau de position des commutateurs DIP\_.
  * Insérez quatre piles au lithium AAL91 dans le support de pile en prenant soin de connecter correctement la polarité.
  * Mettez le panneau de commande en mode apprentissage, reportez-vous au manuel du panneau de commande pour plus de détails.
  * Appuyez et maintenez le bouton Test pendant 3 secondes pour envoyer un code d'apprentissage, puis relâchez le bouton lorsque la LED rouge s'allume. La LED sera allumée pendant 20 secondes, indiquant que la caméra PIR est en mode apprentissage.
  * Si le panneau de commande reçoit le signal de la caméra PIR, il affichera les informations en conséquence. Dans les 20 secondes lorsque le voyant de la caméra PIR est allumé, sélectionnez la caméra PIR sur la page Web du panneau de commande et cliquez sur\*\*"ajouter"\*\*pour l'inclure dans le panneau. Reportez-vous au manuel du panneau de commande pour plus de détails.
  * Lorsque la caméra PIR reçoit un accusé de réception du panneau de commande, la LED de la caméra PIR clignote 6 fois puis s'éteint pour indiquer un apprentissage réussi.
  * Une fois la caméra PIR apprise, mettez le panneau de commande en mode test de marche. Maintenez la caméra PIR à l'emplacement souhaité et appuyez sur le bouton Test pour confirmer que cet emplacement se trouve dans la plage de signal du panneau de commande.
  * Lorsque vous êtes convaincu que la caméra PIR fonctionne à l'emplacement choisi, vous pouvez procéder à l'installation.

_\\_









Après avoir maintenu le bouton Test enfoncé pendant 3 secondes, la LED de la caméra PIR s'allumera pendant 20 secondes. Si la caméra PIR ne reçoit pas d'accusé de réception du panneau de commande dans ce délai de 20 secondes, la LED s'éteindra. Le bouton Test doit être enfoncé à nouveau pendant 3 secondes pour renvoyer un code d'apprentissage.

Si la caméra PIR existe déjà dans un système du panneau de configuration, vous devrez d'abord supprimer la caméra PIR du panneau de configuration avant de pouvoir l'enregistrer dans un autre panneau de configuration.

**Test de marche**doit être effectuée pour confirmer le bon fonctionnement et la couverture du PIR.

![](<.gitbook/assets/4 (19).jpeg>)

Lors de l'apprentissage de la caméra PIR dans un répéteur/routeur, veuillez appuyer une fois sur le bouton Test (au lieu de le maintenir enfoncé pendant 3 secondes) pour envoyer un code d'apprentissage.

* _**Modifier la zone de fonctionnement de la caméra PIR**_

Suivez les instructions ci-dessous pour modifier la zone de la caméra PIR dans le panneau de commande.

1. Utilisez la fonction Modifier l'appareil du panneau pour modifier les paramètres de la zone de la caméra PIR.
2. Appuyez et maintenez enfoncé le bouton Test pendant 3 secondes sur la caméra PIR pour envoyer un signal au panneau, puis relâchez le bouton lorsque la LED s'allume.

3

* _**Méthode de montage et d'installation**_
  * **Montage avec support de montage :**
    * La caméra PIR peut être montée sur une surface plane ou dans un coin avec les vis de fixation, les chevilles et le support de montage fourni.
    * La plaque de montage fournie comporte des découpes dans lesquelles le plastique est plus fin et peut être cassé à des fins de montage. Deux découpes sont destinées à la fixation en surface et quatre sont destinées à la fixation en coin, comme indiqué sur l'image.
    * Pour monter le VST-862EX avec le support de montage :
      1. Utilisez le support de montage comme modèle pour percer des trous dans le mur pour les chevilles.
      2. Enfoncez les chevilles et fixez le support de montage au mur avec les vis.
      3. Montez le VST-862EX avec les crochets du support de montage verrouillés sur le capot arrière du VST-862EX, puis poussez vers le bas jusqu'à ce que vous entendiez un clic.

_\\_

* Veuillez vous assurer que la caméra PIR est correctement accrochée au support de montage, afin que l'interrupteur anti-sabotage interne soit entièrement compressé.

![](<.gitbook/assets/5 (27).png>)

* Veuillez éviter de monter la caméra PIR sur des surfaces inégales. Si un montage dans un coin sur des surfaces inégales est toujours nécessaire, vous pouvez fixer les 4 entretoises en mousse adhésive à l'arrière du support de montage pour permettre une relaxation des contraintes.

![](<.gitbook/assets/6 (18).png>)

* **Montage avec support de montage et support rotatif :**

Un support rotatif est fourni comme option de montage conviviale\*\*(article en option, vendu séparément)\*\*. Il est composé d'une base à fixer à la surface et d'une boule pivotante à fixer au support de montage et au VST-862EX.

Grâce au support rotatif, la caméra PIR peut être tournée horizontalement pour offrir une couverture optimale.

![](<.gitbook/assets/7 (17).jpeg>)

4

Un tournevis spécial avec embout double face réversible et trois vis à douille étoile sont fournis pour fixer le support rotatif au mur.

![](<.gitbook/assets/8 (16).png>)

Veuillez utiliser le tournevis fourni pour serrer/desserrer les vis à douille étoile.

![](<.gitbook/assets/9 (17).png>)

*
  * Pour monter le VST-862EX avec le support de montage et le support rotatif :

1. Fixez le support rotatif au mur avec les vis fournies.
2. Fixez le support de montage sur la boule pivotante avec la vis de fixation fixée à travers le trou de conception infaillible.
3. Montez le VST-862EX avec les crochets du support de montage verrouillés sur le capot arrière du VST-862EX, puis poussez vers le bas jusqu'à ce que vous entendiez un clic.

![](<.gitbook/assets/10 (15).png>)

5

1. Faites pivoter la boule pivotante horizontalement pour ajuster l'angle de détection du VST-862EX. (Lorsque la vis de réglage de l'angle est à moitié desserrée, la boule pivotante peut toujours tourner.)

![](<.gitbook/assets/11 (13).jpeg>)

*
  1. Lorsque le VST-862EX est tourné vers une position avec la couverture de détection souhaitée, vous pouvez verrouiller la position en serrant fermement la vis de réglage de l'angle.
* _**Recommandations d'installation**_

**Il est recommandé d'installer la caméra PIR aux emplacements suivants :**

* À une hauteur de 2 mètres (mesurée à partir du bas de la caméra) au-dessus du niveau du sol pour de meilleures performances.
* Dans un coin pour une vue plus large.
* Là où un intrus se déplacerait normalement dans le champ de vision de la caméra PIR.
* Une surface ou un coin où les animaux sont inaccessibles.
* La caméra PIR a une portée de détection de 10 M lorsqu'elle est montée à une hauteur de 2 mètres au-dessus du sol.

**Plage de détection du VST-862EX**

![](<.gitbook/assets/12 (8).jpeg>)

**Limites:**

* N'exposez pas complètement la caméra PIR à la lumière directe du soleil.
* Évitez les gros obstacles dans la zone de détection.
* Ne faites pas face à des sources de chaleur telles que des incendies et des chaudières, et n'installez pas au-dessus des radiateurs.
* N'essayez jamais de démonter ou de modifier l'appareil.
* Veuillez installer la caméra PIR directement. Ne l'inclinez pas.

![](<.gitbook/assets/13 (7).jpeg>)

6

* N'installez pas la caméra à capteur de mouvement à proximité d'objets déplacés par le vent, tels que des arbres et du linge, car cela pourrait bloquer le champ de vision de la caméra à capteur de mouvement.

![](<.gitbook/assets/14 (9).jpeg>)

* Éliminez toutes les surfaces réfléchissant la lumière de la zone de détection, ainsi que les flaques d'eau.

![](<.gitbook/assets/15 (8).jpeg>)

* Évitez de regarder directement le trajet du flux d’air d’admission ou d’évacuation de l’unité extérieure.

![](<.gitbook/assets/16 (8).jpeg>)

_\\_

* Ajustez les commutateurs Dip en fonction de l'emplacement d'installation de la caméra PIR pour des performances idéales. Si les paramètres du commutateur Dip ne correspondent pas à l'environnement d'installation, les performances de la caméra PIR seront entravées et pourraient provoquer une fausse alarme ou une incapacité à détecter un mouvement.
* La caméra PIR détecte les différences entre l'objet en mouvement et l'arrière-plan. Si l'objet est stationnaire (c'est-à-dire ne bouge pas), la caméra PIR est incapable de le détecter.
* La caméra PIR a une caractéristique directionnelle et est la plus efficace pour détecter les intrus se déplaçant dans le champ de détection. Il est moins sensible pour détecter les mouvements directement vers la caméra PIR.
* La caméra PIR présente un angle mort d'environ 1 mètre sous la caméra lorsqu'elle est montée à une hauteur de 2 mètres. La zone d'angle mort s'agrandit si vous montez la caméra PIR à une hauteur supérieure à 2 M et diminue si elle est inférieure à 2 M.
* Sauf si cela est nécessaire, nous vous suggérons de maintenir la caméra PIR à la hauteur suggérée pour des performances optimales. Si vous modifiez la hauteur de montage, veuillez effectuer un test de détection pour vous assurer que la caméra PIR peut détecter normalement un intrus à la hauteur souhaitée.

7
