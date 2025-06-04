# VESTA-015

**IRD-23 / IRD-23SL**

## <mark style="color:green;">**Détecteur PIR dôme**</mark>

### _<mark style="background-color:yellow;">**Introduction**</mark>_

Le détecteur PIR dôme est conçu pour être monté au plafond et fournir une couverture de détection à 360° sans angles morts pour capter les mouvements dans une zone donnée et signaler à la centrale d'activer l'alarme si un intrus croise la zone de détection.\
Le détecteur PIR se compose de deux parties: la partie principale qui est le détecteur PIR et d'une base de fixation. La partie principale contient toute l’électronique et l’optique et la base fournit un moyen d’installation.\
La partie principale du détecteur PIR est dotée d'une autoprotection qui sera activée lorsque le corps de l'appareil est retirée de sa base pour empêcher tout accès non autorisé et tout retrait de la surface d'installation. Le détecteur PIR peut également vous alerter des problèmes de communication et des situations de batterie faible.\
\
Le détecteur PIR dôme est décliné en 2 modèles :\
\- IRD-23: alimenté par 2 piles alcalines AA de 1,5V\
\- IRD-23SL: alimenté par 1 pile lithium CR123A 3V



### _<mark style="background-color:yellow;">**Identification.**</mark>_

![Partie principale](<.gitbook/assets/2 (17).jpeg>)

![Base de fixation](<.gitbook/assets/3 (16).jpeg>)

1. **Bouton test/Voyant LED**\
   Le bouton de test sert également de voyant LED. Le bouton de test est utilisé pour tester la communication radio et pour l'apprentissage. Le voyant LED est utilisé pour indiquer l'état de l'appareil.
2. **Capteur IR**
3. **Cavalier d'augmentation de sensibilité (JP3)**\
   Le cavalier est inséré pour relier les deux broches.\
   \- Cavalier On : le niveau de sensibilité du PIR est réglé sur Haut. <img src=".gitbook/assets/image (2) (1) (1) (1).png" alt="" data-size="line">\
   \- Cavalier Off : le niveau de sensibilité du PIR est réglé sur Normal (**par défaut**). <img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line">
4. **Autoprotection**\
   L'autoprotection protège le détecteur PIR en cas d'ouverture/d'arrachement.
5. **Batterie**\
   **-** IRD-23 : 2 piles alcalines AA 1,5V\
   \- IRD-23SL : 1 pile lithium CR123A 3V
6. **Fixations**
7. **Crochets**
8. **Emplacements de fixation (intérieur)**

#### _<mark style="background-color:green;">**- Voyant LED**</mark>_

En mode normal, le voyant LED ne s'allumera pas sauf dans les situations suivantes:

* Lorsque le PIR est en état de batterie faible, chaque fois qu'il transmet la détection d'un mouvement, la LED s'allume pendant environ 2 secondes.
* Lorsque l'appareil est ouvert et que l'autoprotection est déclenchée, la LED s'allume pendant 2 sec. pour indiquer la transmission d'un signal **Autoprotection**.
* Lorsque la condition d'autoprotection persiste, chaque fois qu'il transmet la détectetion d'un mouvement, la LED s'allumera.
* Lorsque le PIR est en mode Test, la LED s'allume à chaque fois qu'un mouvement est détecté.

#### _<mark style="background-color:green;">**- Mise en veille**</mark>_

Le détecteur PIR a une "**mise en veille**" d'environs 1 minute pour économiser de l'énergie. Après avoir transmis un mouvement détecté, le détecteur PIR ne retransmettra pas pendant 1 minute. Tout mouvement détecté pendant cette période réinitialisera la temporisation de mise en veille de 1 minute. Un mouvement continu devant le PIR n'épuisera donc pas la batterie.

#### _<mark style="background-color:green;">**- Supervision**</mark>_

Le PIR transmet un signal de supervision toutes les 30 à 50 minutes. Si la centrale ne parvient pas à recevoir les signaux de supervision pendant une durée définie, un message de défaut sera généré.

#### _<mark style="background-color:green;">**- Augmentation de la sensibilité**</mark>_

Vous pouvez utiliser la fonction d’augmentation de sensibilité pour augmenter la sensibilité de détection du détecteur PIR. Pour augmenter la sensibilité de détection, connectez le cavalier (JP3) ou le mettre en position ON. Pour maintenir une sensibilité normale, déconnectez le cavalier (JP3) ou le mettre en position OFF (par défaut).

#### _<mark style="background-color:green;">**- Mode d'essai**</mark>_

Le détecteur PIR peut être mis en mode Test/voyant LED en appuyant sur le bouton test. En mode Test, il désactivera la mise en veille et permettra au voyant LED de clignoter à chaque fois qu'un mouvement est détecté. Chaque fois que vous appuyez sur le bouton de test, le détecteur PIR transmettra un signal de test à la centrale pour un test de portée radio et entrera en mode test pendant 3 minutes. Le mode test expirera après 3 minutes.

#### _<mark style="background-color:green;">**- Batterie**</mark>_

Le PIR utilise différentes batteries selon le modèle PIR :\
\- IRD-23 : 2 piles alcalines AA 1,5V\
\- IRD-23SL : 1 pile lithiumCR123A 3V

Le détecteur PIR dispose d'une fonction de détection de batterie faible. Si une faible tension de batterie est détectée, un signal de batterie faible sera envoyé à la centrale avec des transmissions régulières pour que la centrale affiche l'état en conséquence.

{% hint style="info" %}
NOTE:

* Lors du changement des piles, après avoir retiré les anciennes piles, appuyez deux fois sur l'autoprotection pour décharger complètement avant d'insérer de nouvelles piles.
{% endhint %}

#### _<mark style="background-color:green;">**- Autoprotection**</mark>_

Le PIR dispose d'une autoprotection située sur la partie principale du PIR. Lorsque le PIR est correctement installé sur sa base, l'autoprotection est compressée. Lorsque le PIR est ouvert, l'autoprotection sera activée et déclenchera l'envoi d'un signal d'autoprotection à la centrale.



### _<mark style="background-color:yellow;">**Démarrage**</mark>_

* Insérez la batterie.
* Le voyant LED clignote pendant 30 secondes (le détecteur PIR démarre). Pendant la période de démarrage, le détecteur PIR ne sera pas actif. Une fois la période de démarrage terminée, le voyant LED s'éteindra et le PIR sera prêt à fonctionner.
* Mettez la centrale en mode apprentissage, reportez-vous au manuel de la centrale pour plus de détails.
* Appuyez sur le bouton d'apprentissage/voyant test sur la face avant.
* Si la centrale reçoit le signal du PIR, elle affichera les informations en conséquence. Reportez-vous au manuel de la centrale pour terminer le processus d'apprentissage.
* Une fois le détecteur PIR appris, mettez la centrale en "**Test de fonctionnement"**, maintenez le détecteur PIR à l'emplacement souhaité et appuyez sur le bouton test pour confirmer que cet emplacement est à portée de signal de la centrale.
* Lorsque vous êtes convaincu que le détecteur PIR fonctionne à l'emplacement choisi, vous pouvez procéder au montage.



### _<mark style="background-color:yellow;">**Type d'installation**</mark>_

* Le PIR est conçu pour être installé au plafond.
* Lorsqu'il est installé à 2,7 mètres de haut, le PIR offre une couverture 360° d'environs **6m** de diamètre.
* Lorsqu'il est installé à 4 mètres de haut, le PIR offre une couverture 360° d'environs **8m** de diamètre.
* Pour des performances optimales, faites pivoter le PIR de manière à ce que l'intrus se déplace d'un côté à l'autre dans sa zone de détection.

{% hint style="info" %}
NOTE:\
Pour connaître les « faces » du PIR. Tenez le PIR avec le voyant LED pointant vers le haut, les côtés gauche et droit du PIR sont considérés comme les côtés du PIR. Le capteur PIR est plus sensible lorsque l'intrus se déplace d'un côté vers l'autre
{% endhint %}

* Reportez-vous aux schémas ci-dessous pour plus d’informations.

![](<.gitbook/assets/4 (32).png>)

* **Il est recommandé d'installer le PIR dans les emplacements suivants.**
  * Dans une zone ou plafond dispose d'une vue complète sur la zone de détection non obstruée par des appareils électroménagers ou des meubles.
  * Près de l'entrée d'une pièce ou d'une maison pour surveiller l'activité d'entrée.

{% hint style="danger" %}
Limites:

* Ne positionnez pas un détecteur PIR directement vers une porte protégée par un détecteur d'ouverture, cela pourrait provoquer la transmission des signaux radio du contact de porte et du PIR au même instant lors de l'entrée, s'annulant mutuellement.
* N'installez pas le PIR complètement exposé à la lumière directe du soleil.
* Évitez d'installer le PIR dans des zones où les appareils peuvent provoquer un changement rapide de température dans la zone de détection, c'est-à-dire un climatiseur, un chauffage, etc.
* Évitez les gros obstacles dans la zone de détection.
* Ne pas pointer directement vers des sources de chaleur, par ex. feux ou chaudières, et pas au-dessus des radiateurs.
* Évitez de déplacer des objets dans la zone de détection, par exemple un rideau, une tenture murale, etc
{% endhint %}

* Après avoir sélectionné l'emplacement d'installation, suivre les étapes ci-dessous pour installer le PIR.
* Appuyez sur le bouton Test pour accéder au mode Test. Parcourez la zone protégée en notant quand la LED s'allume et vérifiez que la couverture de détection soit correcte.
* Lorsque la détection s'avère satisfaisante, l'installation est désormais terminée.



#### _<mark style="background-color:green;">**Méthode de montage**</mark>_

* Le PIR est conçu pour être monté au plafond
* La base dispose de 4 découpes où le plastique est plus fin pour la fixation au plafond.
* Après avoir terminé l'apprentissage du PIR et le test de fonctionnement, procédez à la fixation du PIR conformément aux instructions ci-dessous:



1. Percez les 4 découpes de la base.
2. Utilisez ces découpes comme gabarit, percez les trous dans le plafond et insérez une cheville murale si nécessaire.
3. Vissez la base au plafond en fonction des trous percés.
4. La base comporte des numéros à l'intérieur pour marquer les trous de fixation qui correspond aux numéros des clips à l'arrière de la partie principale. Alignez les trous avec les clips. Reportez-vous à la figure ci-dessous pour connaître l'emplacement des clips et des trous.

![Gauche: parti principale; Droite: Base](<.gitbook/assets/5 (13).jpeg>)

5. Installez la partie principale sur la base. Faites correspondre les clips avec les trous de fixation.
6. pivotez la partie principale du PIR dans le sens des aiguilles d'une montre pour verrouiller les clips. Reportez-vous à la figure ci-dessous.
7. &#x20;L'installation du PIR est maintenant terminé.

![](<.gitbook/assets/6 (16).jpeg>)
