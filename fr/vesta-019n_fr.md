# 🇫🇷 VESTA-019N

**DC-23 / DC-23-R3**

## Détecteur d'ouverture avec extension filaire

### **Introduction**

Le détecteur d'ouverture surveille l'ouverture/fermeture d'éléments spécifiques (par exemple porte ou fenêtre). L'électronique est fixée au cadre de l'élément à surveiller tandis que l'aimant est fixé sur la partie mobile. Lorsque la porte ou la fenêtre s'ouvre, l'aimant s'éloigne du détecteur d'ouverture, activant un interrupteur magnétique interne provoquant la transmission par le détecteur d'un signal d'alarme vers la centrale. L'appareil a également la capacité de communiquer les problèmes de transmission ainsi que les situations de batterie faible.

Le détecteur d'ouverture se compose d'un couvercle et d'une base. L'ensemble contient tous les composants électroniques et la base permet la fixation de l'appareil. Une autoprotection sur le circuit imprimé offre une protection contre l'ouverture/l'arrachement non autorisé de l'appareil.

Le détecteur d'ouverture de la série DC-23 est décliné en 2 modèles:\
\- DC-23: Le couvercle du détecteur d'ouverture est fixé par une vis.\
\- DC-23-R3: Le couvercle du détecteur d'ouverture est fixé par clips

### **Identification**

<figure><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1).png" alt="" width="255"><figcaption></figcaption></figure>

1. **Voyant LED/Bouton Test**\
   Appuyez sur le bouton Test pour transmettre le code d'apprentissage ou passer en mode test pendant 3 min.
2. **Trous de fixation**\
   Pour fixer et visser le contact de porte directement sur le cadre de porte ou le mur.
3. **Autoprotection**\
   Lorsque le détecteur d'ouverture est installé, l'autoprotection déclenchera lorsque le couvercle sera ouvert ou lorsqu'il sera retiré de sa surface d'installation.
4. **Opercule de batterie**
5. **Cavalier de l'extension (JP2)**\
   Le cavalier est inséré pour relier les deux broches.\
   \- Cavalier On : le contact doit être de type NF (Normalement Fermé). <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252F0p4nSEK1AO4PxDL25eFj%252Fimage.png%3Falt%3Dmedia%26token%3Df98fa98a-eb3a-4b7c-8f15-483b715bc4a1&#x26;width=22&#x26;dpr=4&#x26;quality=100&#x26;sign=f62bfe51&#x26;sv=2" alt="" data-size="line"> \
   \- Cavalier Off : le contact doit être de type NO (Normalement Ouvert - **réglage par défaut**). <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252FZYhxX59Fs1O8h4oz0qP5%252Fimage.png%3Falt%3Dmedia%26token%3Dfcb10a11-57bc-41e3-9246-a7bd2959a7d6&#x26;width=29&#x26;dpr=4&#x26;quality=100&#x26;sign=73d4f567&#x26;sv=2" alt="" data-size="line">
6. **Cavalier de l'Interrupteur à Lame Souple ILS (JP3)**\
   Le cavalier est inséré pour relier les deux broches.\
   \- Cavalier On : l'ILS est désactivé.<img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252F0p4nSEK1AO4PxDL25eFj%252Fimage.png%3Falt%3Dmedia%26token%3Df98fa98a-eb3a-4b7c-8f15-483b715bc4a1&#x26;width=22&#x26;dpr=4&#x26;quality=100&#x26;sign=f62bfe51&#x26;sv=2" alt="" data-size="line">\
   Seul le dispositif câblé sur l'extension activera le détecteur d'ouverture.\
   \- Cavalier Off : l'ILS est activé (**par défaut**). <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252FZYhxX59Fs1O8h4oz0qP5%252Fimage.png%3Falt%3Dmedia%26token%3Dfcb10a11-57bc-41e3-9246-a7bd2959a7d6&#x26;width=29&#x26;dpr=4&#x26;quality=100&#x26;sign=73d4f567&#x26;sv=2" alt="" data-size="line">
7. **Extension**\
   En plus de l'ILS, un bornier 2 broches pour un contact sec est disponible pour relier tout autre appareil NO/NF.
8. **Piles**
9. **Aimant**
10. **Fixation aimant**
11. **Entretoise**

![](<.gitbook/assets/7 (16).jpeg>)

### **Caractéristiques**

#### **- Voyant LED**

En mode normal, le voyant LED ne s'allumera pas sauf dans les situations suivantes:

* Lorsque le détecteur d'ouverture est en état de batterie faible, chaque fois qu'il transmet, la LED s'allume pendant environ 2 secondes.
* Lorsque l'appareil est ouvert et que l'autoprotection est déclenchée, la LED s'allume pendant 2 sec. pour indiquer la transmission d'un signal **Autoprotection**. Lorsque la condition d'autoprotection persiste, chaque fois qu'il transmet, la LED s'allumera.
* Lorsque le détecteur est en mode Test, la LED s'allume à chaque fois qu'il est déclenché.
* Lorsque la batterie est épuisée, le contact de porte arrêtera toute fonction, la LED clignotera toutes les 4 secondes

#### **- Borne d'extension**

Le détecteur d'ouverture dispose d'un bornier d'extension pour plus de flexibilité. L'appareil connecté doit former NO (normalement ouverte) ou NF (normalement fermée) sur le bornier selon la position du cavalier JP2. L'appareil est déclenché, lorsque la boucle change d'état.\
Le bornier d'extension et l'ILS peuvent fonctionner ensemble pour déclencher le détecteur d'ouverture lorsque l'un d'eux est activé. Vous pouvez également choisir de désactiver l'ILS via le réglage du cavalier JP3.

Pour connecter l'appareil au bornier d'extension :

* **Pour le modèle DC-23 :**

![](<.gitbook/assets/10 (8).jpeg>)

1. Ouvrez le couvercle du détecteur d'ouverture à l'aide d'un tournevis pour desserrer la vis de fixation située en bas (voir l'image ci-dessus en vue de dessus).
2. L'extrémité supérieure du boîtier présente une découpe. Percez cette ouverture pour créer un passage de câble vers le bornier d'extension.
3. Connectez l'appareil au bornier d'extension.

* **Pour le modèle DC-23-R3 :**

1. Utilisez votre pouce pour appuyer sur le loquet, tout en appuyant dessus, retirez le couvercle de la base du détecteur d'ouverture (voir l'image ci-dessus en vue de dessus).
2. L'extrémité supérieure du boîtier présente une découpe. Percez cette ouverture pour créer un passage de câble vers le bornier d'extension.
3. Connectez l'appareil au bornier d'extension.

![](<.gitbook/assets/11 (12).jpeg>)

Le bornier d'extension peut être utile dans la situation suivante.

* Si le détecteur d'ouverture ne peut pas être installé sur le cadre de la porte, vous pouvez connecter un détecteur d'ouverture filaire sur le bornier d'extension.
* Tout appareil disposant d'un contact sec NO (normalement ouvert) ou NF (normalement fermé) peut être câblé au bornier d'extension, faisant du détecteur d'ouverture un émetteur universel.
* Plusieurs appareils NO/NF peuvent être câblés avec le détecteur d'ouverture, comme le montre le schéma ci-dessous.

![](<.gitbook/assets/12 (7).jpeg>)

* La bornier d'extension et l'ILS peuvent fonctionner ensemble pour déclencher le détecteur d'ouverture lorsque l'un d'eux est activé. Vous pouvez également choisir de désactiver l'ILS via le réglage du cavalier JP3. Si le bornier d'extension et l'ILS sont utilisés et que l'un d'entre eux est déclenché, le détecteur d'ouverture transmettra l'information à la centrale d'alarme. Le signal de fermeture (rétablissement) du détecteur d'ouverture sera envoyé uniquement lorsque les 2 contacts seront fermés.

#### **Batterie**

* Le détecteur d'ouverture est alimenté par une pile lithium CR123 3V. Veuillez noter de **TOUJOURS** remplacer la batterie par un modèle de taille et tension équivalentes.
* Le détecteur d'ouverture peut détecter une batterie faible. Lorsque la tension de la batterie est faible, un signal batterie faible sera envoyé à la centrale. La LED s'allumera lorsque le détecteur d'ouverture est activé en cas de batterie faible. Lorsque la batterie est épuisée, le détecteur d'ouverture arrêtera toute fonction, la LED clignotera toutes les 4 secondes.
* Lors du changement de batterie, après avoir retiré l'ancienne batterie, appuyez deux fois sur l'autoprotection pour une décharge complète avant d'insérer une nouvelle batterie.

#### **Autoprotection**

* Le détecteur d'ouverture est protégé par une autoprotection qui est comprimée contre la surface de fixation. Chaque fois que le couvercle du détecteur d'ouverture est ouvert ou lorsqu'il est retiré de son emplacement, l'autoprotection sera activée et le détecteur enverra un signal d'autoprotection à la centrale pour informer l'utilisateur.

#### **Supervision**

* La supervision pour le modèle 868WF est contrôlée par le réglage du cavalier JP2. Pour le modèle non-868WF, la fonction de supervision est toujours activée.
* Lorsqu'elle est activée, le détecteur d'ouverture transmettra automatiquement des signaux de supervision périodiquement vers la centrale à des intervalles aléatoires de 30 à 50 minutes.
* Si la centrale n'a pas reçu le signal du détecteur d'ouverture pendant une période prédéfinie, elle indiquera que ce périphérique rencontre un problème de perte de signal.

#### **Mode test**

* En mode normal, appuyez sur le bouton Test pour transmettre un signal de test et un code d'apprentissage à la centrale. Le détecteur d'ouverture entrera également en mode test pendant 3 minutes.
* En mode test, la LED s'allumera chaque fois que le détecteur sera activé.
* Chaque pression supplémentaire sur le bouton Test réinitialisera la durée du mode test à 3 minutes.



### **Démarrage**

* Ouvrez le détecteur d'ouverture et insérez la batterie.
* Mettez la centrale en mode apprentissage (veuillez vous référer au manuel d'utilisation de la centrale).
* Appuyez sur le bouton Test du détecteur d'ouverture.
* Reportez-vous au manuel d'utilisation de votre centrale pour terminer le processus d'apprentissage.
* Une fois le détecteur d'ouverture appris, placez la centrale en test de fonctionnement, maintenez le détecteur d'ouverture à l'emplacement souhaité et appuyez sur le bouton Test pour transmettre le signal de test à la centrale. Si la centrale se trouve à portée de signal de détecteur, la centrale affichera les informations de détecteur d'ouverture en conséquence.
* Procédez à l'installation une fois que vous êtes convaincu que l'emplacement du périphérique permet une fonctionnement correct.



### **Installation**

*   **Directives d'installation**

    * Le détecteur d'ouverture doit être installé sur le cadre de porte/fenêtre et l'aimant sur la porte/fenêtre.
    * La distance entre le détecteur d'ouverture et l'aimant ne doit pas dépasser 15 mm lorsque la porte est fermée.
    * Évitez d'installer le détecteur d'ouverture sur une surface métallique. En cas d'installation sur une surface métallique, assurez-vous de tester si le détecteur d'ouverture peut être déclenché lorsque la porte est ouverte.
    * Installez le détecteur d'ouverture aussi haut que possible.



#### **Montage du détecteur d'ouverture**

1. Trouvez un emplacement approprié à proximité de votre porte/fenêtre pour installer le détecteur d'ouverture.
2. Le détecteur d'ouverture comporte 2 repères sur un côté (voir image), marquant l'emplacement de l'ILS. Le détecteur d'ouverture doit être installé soit verticalement, soit inversé pour garantir que le côté marqué par les repères soit face à l'aimant.
3. Pour installer le détecteur d'ouverture :
   1. Utilisez les 2 trous de fixation du détecteur d'ouverture porte comme modèle pour le positionnement approprié.
   2. Utilisez les chevilles murales fournies pour l'installation en plâtre/brique.
   3. Vissez le détecteur d'ouverture dans les chevilles murales fournies.
4. Pour monter l'aimant :
   1. Utilisez les 2 trous de fixation comme modèle pour un positionnement approprié.
   2. Vissez l'aimant sur la porte.
   3. Insérez les deux capuchons blancs pour une intégrité esthétique.

{% hint style="info" %}
NOTE:

* L'aimant ne doit pas être à plus de 15 mm du détecteur d'ouverture lorsque la porte est fermée.
* L'aimant doit s'aligner avec le côté marqué des repères sur le détecteur d'ouverture. Si nécessaire, appliquez l'entretoise à l'arrière de l'aimant pour mieux aligner l'aimant sur les repères.
{% endhint %}

5. L'installation est maintenant terminée.

<figure><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1).png" alt="" width="375"><figcaption></figcaption></figure>

Déclaration FCC

Cet appareil est conforme à la partie 15 des règles FCC. L’exploitation est soumise aux deux conditions suivantes : (1) Cet appareil ne doit pas provoquer d'interférences nuisibles, et (2) Cet appareil doit accepter toute interférence reçue, y compris les interférences susceptibles de provoquer un fonctionnement indésirable.

Avertissement FCC : Pour garantir une conformité continue, tout changement ou modification non expressément approuvé par la partie responsable de la conformité peut annuler le droit de l'utilisateur à utiliser cet équipement. (Exemple : utilisez uniquement des câbles d'interface blindés lors de la connexion à un ordinateur ou à des périphériques).
