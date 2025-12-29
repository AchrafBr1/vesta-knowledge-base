# 🇫🇷 VESTA-009

**IR(P)-29**

## **Détecteur PIR**

### **Introduction**

Le détecteur PIR capte une signature infrarouge pour détecter les mouvements dans une zone donnée et signale à la centrale de déclencher une alarme si un intrus croise sa zone de détection.\
Le détecteur PIR est composé de deux éléments, le couvercle et la base. Le couvercle contient toute l'électronique et l'optique et la base fournit un moyen de fixation. La base comporte des découpes pour permettre un montage sur une surface plane ou dans un angle avec un support triangulaire.\
Le détecteur PIR dispose d'une autoprotection qui s'activera lorsque le couvercle est ouvert. Il peut également vous alerter des problèmes de communication et des situations de batterie faible.\
Le détecteur  PIR est conçu pour offrir une portée de 12 mètres lorsqu'il est monté à 2 mètres de haut.\
Les modèles avec immunité animaux de la série IR-29 prennent en charge la fonction d'immunité aux animaux et ne détecteront pas les animaux pesant jusqu'à 27 kg dans un rayon de 7 mètres afin de minimiser les situations de fausse alarme.\
\
**Les détecteurs PIR de la série IR-29 sont les suivants:**\
\
IR-29 / IR-29 F1 – Détecteur PIR avec piles alcalines\
IRP-29 / IRP-29 F1 – Détecteur PIR, immunité animaux avec piles alcalines\
IR-29SL / IR-29SL-F1 – Détecteur PIR avec batterie au lithium\
IRP-29SL / IRP-29SL-F1 – Détecteur PIR, immunité animaux avec batterie au lithium



### **Identification**<br>

<figure><img src=".gitbook/assets/0 (3) (1).png" alt=""><figcaption></figcaption></figure>



1. **Bouton de test/Voyant LED**\
   Le bouton de test est utilisé pour tester les performances du signal radio et pour l'apprentissage.\
   Le voyant LED est utilisé pour indiquer l'état du périphérique.
2. **Opercule de batterie**
3. **Cavalier de supervision (JP2)**\
   Le cavalier est inséré pour relier les deux broches.\
   \- Cavalier On : la supervision est désactivée (**par défaut pour les modèles 433AM**).\
   \- Cavalier Off : la supervision est activée (**par défaut pour les modèles 868WF**).\
   Pour les modèles **433AM** ou **868WF** ne disposant pas de cavalier  JP2, la supervision est activée et ne peut pas être désactivée.
4. **Cavalier de sensibilité (JP3)**\
   **-** Cavalier Off : la sensibilité du détecteur PIR est au niveau normal **(par défaut pour les modèles sans immunité animaux)**.\
   \- Cavalier On : la sensibilité du détecteur PIR est élevée (par défaut pour les modèles avec immunité animaux).
5. **Autoprotection**\
   L'autoprotection protège le détecteur PIR contre toute ouverture non autorisée du couvercle.



#### **- Mise en veille**

Le détecteur PIR a une "**mise en veille**" d'environs 1 minute pour économiser de l'énergie. Après avoir transmis un mouvement détecté, le détecteur PIR ne retransmettra pas pendant 1 minute. Tout mouvement détecté pendant cette période réinitialisera la temporisation de mise en veille de 1 minute. Un mouvement continu devant le PIRCAM n'épuisera donc pas la batterie.

#### **- Supervision**

Si elle est activée (voir ci-dessus), lorsque le détecteur PIR est en mode de fonctionnement normal, il effectuera un auto-test en transmettant un signal de supervision une fois toutes les 30 à 50 minutes.\
Si la centrale ne parvient pas à recevoir les signaux de supervision pendant une durée définie, un message de défaut sera généré.

#### **- Augmentation de la sensibilité**

Vous pouvez utiliser la fonction d’augmentation de sensibilité pour augmenter la sensibilité de détection du détecteur PIR. Pour augmenter la sensibilité de détection, connectez le cavalier (JP3) ou le mettre en position ON (par défaut pour les modèles avec immunité animaux). Pour maintenir une sensibilité normale, déconnectez le cavalier (JP3) ou le mettre en position OFF (par défaut pour les modèles sans immunité animaux).

#### **- Mode test**

Le détecteur  PIR peut être mis en mode Test en appuyant sur le bouton test. En mode Test, il désactivera la mise en veille et permettra au voyant LED de clignoter à chaque fois qu'un mouvement est détecté. Chaque fois que vous appuyez sur le bouton de test, le détecteur PIR transmettra un signal de test à la centrale pour un test de portée radio et entrera en mode test pendant 3 minutes. Le mode test expirera après 3 minutes.

#### **- Voyant LED**

En mode de fonctionnement normal, le voyant LED s'allume dans les situations suivantes (pour les modèles F1, le voyant clignote à la place) :\
\- Lorsqu'un mouvement est détecté dans des conditions de batterie faible.\
\- Lorsque le couvercle est ouvert et que l'autoprotection est déclenchée.\
\- Lorsqu'un mouvement est détecté si la condition d'autoprotection persiste.\
\- Lorsqu'un mouvement est détecté en mode test.\
\- Lorsque le bouton de test est enfoncé dans des conditions d'autoprotection ou si le détecteur PIR détecte une batterie faible.

#### **- Batterie**

Le détecteur PIR de la série IR-29 utilise des piles alcalines ou lithium comme source d'alimentation :\
\- Les modèles alimentés par des piles alcalines utilisent deux piles alcalines AA de 1,5 V.\
\- Les modèles alimentés par piles lithium utilisent une batterie au lithium 3 V 2/3 A (EL123AP).\
\
Le détecteur PIR dispose d'une fonction de détection de batterie faible. Si une faible tension de batterie est détectée, un signal de batterie faible sera envoyé à la centrale avec des transmissions régulières pour que la centrale affiche l'état en conséquence.\
\
Pour chaque installation, la batterie est installée en usine avant expédition avec un isolant inséré.

{% hint style="info" %}
NOTE:\
Lors du changement des piles, après avoir retiré les anciennes piles, appuyez deux fois sur l'autoprotection pour décharger complètement avant d'insérer de nouvelles piles.
{% endhint %}



### **Démarrage**

_**-**_ Retirez l'isolant de la batterie pour activer la batterie.\
\- Le voyant LED clignote pendant 30 secondes (le détecteur PIR démarre). Pendant la période de démarrage, le détecteur PIR ne sera pas actif. Une fois la période de démarrage terminée, le voyant LED s'éteindra et le PIR sera prêt à fonctionner.\
\- Mettez la centrale en mode apprentissage, reportez-vous au manuel de la centrale pour plus de détails.\
\- Appuyez sur le bouton de test du le capot avant.\
\- Reportez-vous au manuel de la centrale pour terminer le processus d'apprentissage.\
\- Une fois le détecteur PIR appris, mettez la centrale en  "**Test de fonctionnement"**, maintenez le détecteur PIR à l'emplacement souhaité et appuyez sur le bouton test pour confirmer que cet emplacement est à portée de signal de la centrale, reportez-vous au manuel de la centrale pour terminer le test de fonctionnement.\
\- Lorsque vous êtes convaincu que le détecteur PIR fonctionne à l'emplacement choisi, vous pouvez procéder au montage.



### **Type d'installation**

_**-**_ Le PIR est conçu pour être monté sur une surface plane ou dans un coin avec les vis de fixation et les chevilles fournies.\
\- La base dispose de découpes où le plastique est plus fin pour l'installation. Deux découpes sont destinées à une pose en applique et quatre sont destinées à une pose en angle,  comme indiqué sur l'image.\
\- Pour le montage en angle, un support triangulaire est fourni pour ajouter une autoprotection arrière. Le support comprend également deux emplacements de fixation.\
\- Pour le montage en applique, un support articulé en option est disponible pour permettre aux utilisateurs d'ajuster la plage de détection. Grâce au support articulé, le détecteur PIR peut pivoter de 80° horizontalement et de 70° verticalement pour offrir une couverture optimale.



* **Installation en applique :**\
  1\. Ouvrez le couvercle en desserrant la vis.\
  2\. Percez les découpes à l'intérieure de la base.\
  3\. Utilisez les trous comme gabarit pour percer la surface de fixation.\
  4\. Insérez les chevilles murales si vous le fixez dans du plâtre ou de la brique.\
  5\. Vissez la base dans les chevilles murales.\
  6\. Installez le couvercle sur la base et serrez.



* **Installation en angle sans support**\
  1\. Percez les découpes sur les champs de la base.\
  2\. Utilisez les trous comme gabarit pour percer la surface de fixation.\
  3\. Insérez les chevilles murales si vous le fixez dans du plâtre ou de la brique.\
  4\. Vissez la base dans les chevilles murales.\
  5\. Installez le couvercle sur la base et serrez.

<figure><img src=".gitbook/assets/3 (5) (1).png" alt="" width="107"><figcaption></figcaption></figure>



*   **Installation en angle avec support :**\
    1\. Percez les emplacements du support triangulaire.\
    2\. Utilisez les trous comme gabarit pour percer des trous sur la surface en angle.\
    3\. Insérez les chevilles murales.\
    4\. Vissez le support triangulaire dans les chevilles murales avec les deux pions de fixation en haut face à vous.\
    5\. Fixez le détecteur PIR sur les crochets du support triangulaire.\
    \
    <br>

    <figure><img src=".gitbook/assets/4 (5) (1).png" alt="" width="97"><figcaption></figcaption></figure>
* **Installation avec adhésif**\
  1\. L'emplacement doit être propre, sec et lisse. Nettoyer l'emplacement avec un dégraissant adapté si nécessaire.\
  2\. Deux pastilles adhésives double face sont fixées sur le support triangulaire avant expédition.\
  3\. Retirez le revêtement de protection des pastilles adhésives double face.\
  4.Fixez le support triangulaire dans l'angle souhaité avec les deux pions de centrage en haut face à vous.\
  5\. Fixez le PIR sur les crochets du support triangulaire.



* **Installation en applique avec support articulé (en option, vendu séparément):**\
  Le support articulé peut être monté au mur à l'aide des vis fournies.\
  1\. Vissez le support articulé au mur.\
  2\. Insérez les 3 crochets du support articulé dans les 3 trous de la base.\
  3\. Faites pivoter le support pour obtenir la plage de détection souhaitez et serrez la vis de fixation.<br>

<figure><img src=".gitbook/assets/5 (4) (1).png" alt=""><figcaption></figcaption></figure>



### **Installation**

_**-**_ Décidez de l'emplacement du détecteur PIR et s'il doit être monté en angle ou en applique.\
\- Une fois l'emplacement d'installation sélectionné, suivez les étapes décrites ci-dessus pour installer le détecteur PIR.\
\- Appuyez sur le bouton test pour démarrer le mode test. Parcourez la zone protégée en vérifiant la LED s'allume et vérifiez que la couverture de détection est adéquate.\
\- Lorsque la couverture de détection s'avère satisfaisante, l'installation est désormais terminée.

#### **Recommandations d'installation**

Le détecteur PIR est conçu pour offrir une portée de détection de 12 mètres lorsqu'il est installé à 2 mètres de haut.\
Pour la série avec immunité animaux, il offre une portée d'immunité de 7 mètres lorsqu'il est installé à 1,9-2,0m de haut. S'il est installé plus haut, la portée de l'immunité animaux sera plus grande.\
\
Pour tirer pleinement parti du détecteur PIR, les directives suivantes doivent être prises en compte :\
**Il est recommandé d'installer le PIR aux emplacements suivants:**\
**-** Installez le détecteur à une hauteur de 1,9 M à 2,0 M pour de meilleures performances.



![](<.gitbook/assets/6 (7).png>)

{% hint style="warning" %}
NOTES:

* Pour obtenir de meilleures performances avec la série disposant de l'immunité animaux, n'oubliez pas d'ajuster la hauteur de pose du détecteur PIR par rapport à la hauteur de l'animal le plus grand de la maison. Les animaux de compagnie plus grands que la moyenne peuvent nécessiter que le détecteur PIR soit monté plus haut pour l'immunité animaux.
* Lorsque vous décidez de la hauteur de pose du détecteur PIR, n'oubliez pas de prendre en compte l'éventuel angle mort. L'angle mort sous le détecteur PIR s'agrandit proportionnellement en fonction de la hauteur de pose.
* Veuillez noter que les performances sont affectées par des facteurs externes, tels que la hauteur de l'objet détecté, la plage de détection souhaitée, la zone d'installation… etc. La hauteur de montage suggérée peut être ajustée en fonction des facteurs réels de l'environnement d'installation.
* Lorsque le détecteur PIR est installé avec un support articulé, il n'aura pas la zone de détection normale (comme dans le diagramme ci-dessus) ni la plage d'immunité animaux classique.
* Installez le détecteur PIR là où les animaux ne peuvent pas accéder à la zone de détection en grimpant sur des meubles ou d'autres objets.
* Ne dirigez pas le détecteur vers des escaliers où lesquels les animaux peuvent monter.
* Dans une position telle qu’un intrus se déplacerait normalement d’un côté à l’autre du champ de détection du PIR.
* Dans un angle pour une scène plus large.
* Où son champ de vision ne sera pas obstrué, par ex. par des rideaux, des ornements, etc.
{% endhint %}

{% hint style="danger" %}
Limites:

* Ne positionnez pas un détecteur PIR directement vers une porte protégée par un détecteur d'ouverture, cela pourrait provoquer la transmission des signaux radio du contact de porte et du PIR au même instant lors de l'entrée, s'annulant mutuellement.
* N'installez pas le PIR complètement exposé à la lumière directe du soleil.
* Évitez d'installer le PIR dans des zones où les appareils peuvent provoquer un changement rapide de température dans la zone de détection, c'est-à-dire un climatiseur, un chauffage, etc.
* Évitez les gros obstacles dans la zone de détection.
* Ne pas pointer directement vers des sources de chaleur, par ex. feux ou chaudières, et pas au-dessus des radiateurs.
* Évitez de déplacer des objets dans la zone de détection, par exemple un rideau, une tenture murale, etc.
{% endhint %}
