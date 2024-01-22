# VESTA 050

**Alarme de reconnaissance vocale (VRA)**

L'alarme de reconnaissance vocale (VRA) reconnaît les commandes vocales ou les mots-clés prédéfinis et active une alarme d'aide. En plus de l'activation vocale, le VRA dispose également d'un gros bouton permettant aux utilisateurs d'appeler à l'aide en cas d'urgence.

-   **Identification des pièces**

**Vue de face****Vue arrière****Side View**

![](<.gitbook/assets/0 (39).jpeg>)

1.  **Bouton d'aide (avec rétroéclairage bleu)**
    1.  Appuyez une fois pour envoyer un code d'apprentissage ou activer une alarme de panique
    2.  Appuyez et maintenez le bouton enfoncé pendant 8 secondes pour envoyer un code d'annulation au panneau de commande.
    3.  Le rétroéclairage bleu clignote lorsque le signal est transmis au panneau de commande.
2.  **Indicateur LED (vert/ambre)**

-   LED verte allumée : lorsqu'une alimentation externe est connectée.
-   LED verte éteinte : lorsque l'alimentation externe est retirée.
-   La LED orange clignote trois fois : état de batterie faible détecté lors de la mise sous tension.
-   La LED orange clignote une fois toutes les 5 secondes : état de batterie faible détecté pendant le fonctionnement.
    1.  **Microphone pour VR (reconnaissance vocale)**
    2.  **Compartiment à piles**
    3.  **DIP Switches**
    4.  **Trou de serrure**
    5.  **Prise CC (avec fonction de verrouillage)**

Branchez un adaptateur secteur DC 5 V et faites-le pivoter de 90 degrés dans le sens des aiguilles d'une montre jusqu'à la position de verrouillage. Pour retirer l'adaptateur, faites-le pivoter de 90 degrés dans le sens inverse des aiguilles d'une montre jusqu'à la position ouverte d'origine et retirez-le.

-   **Source de courant**
    -   -   Le VRA peut être alimenté en se connectant à une alimentation 5 V CC ou à deux batteries de type C.
        -   Lorsque le VRA est connecté à une alimentation 5 V CC, la LED verte s'allume. Lorsque l'alimentation CC est coupée, le VRA passe à l'utilisation de piles (si les piles sont déjà installées et ne sont pas épuisées) et continue de fonctionner ; La LED verte s'éteindra.
        -   Lorsqu'il est alimenté par des piles de type C, le VRA transmettra tout état de batterie faible détecté ainsi que

1

transmissions régulières de signaux d'état au panneau de commande pour affichage en conséquence.

-   -   Lors du changement des piles, veuillez retirer le couvercle arrière en dévissant la vis de fixation inférieure, puis en insérant un tournevis à tête plate pour soulever le couvercle arrière. Retirez les anciennes piles, puis appuyez deux fois sur le bouton Aide pour les décharger complètement avant d'insérer de nouvelles piles.
-   **Signal de surveillance**
    -   Une fois appris dans le panneau de commande, le VRA transmettra automatiquement les signaux de supervision toutes les 30 à 50 minutes.
    -   If the Control Panel has not received the supervision signal from VRA for a preset period of time, the Control Panel will indicate that the Voice Recognition Alarm is out-of-signal range or is out of order.
-   **Sensibilité**
    -   La fonction de reconnaissance vocale a trois niveaux de sensibilité : élevé, moyen, faible. Lorsque le niveau de sensibilité est réglé sur élevé, le VRA détectera plus facilement le mot-clé/commande et déclenchera l'alarme.
    -   Veuillez utiliser un outil pointu pour ajuster les positions du commutateur DIP afin de définir le niveau de sensibilité.

|   |                  |                  |             |                                       |              |   |
| - | ---------------- | ---------------- | ----------- | ------------------------------------- | ------------ | - |
|   |                  |                  |             |                                       |              |   |
|   |                  | **TREMPER**      |             | **Recherche (niveau de sensibilité)** |              |   |
|   |                  |                  |             |                                       |              |   |
|   | **Commutateur1** |                  |             |                                       |              |   |
|   |                  | **Commutateur2** |             |                                       |              |   |
|   |                  |                  |             |                                       |              |   |
|   | DÉSACTIVÉ        |                  | DÉSACTIVÉ   |                                       | Faible       |   |
|   |                  |                  |             |                                       |              |   |
|   | ON               |                  | DÉSACTIVÉ   |                                       | Moyen        |   |
|   |                  |                  |             |                                       |              |   |
|   | DÉSACTIVÉ        |                  | SUR         |                                       | Haut         |   |
|   |                  |                  |             |                                       |              |   |
|   |                  |                  |             |                                       |              |   |
|   |                  |                  | **TREMPER** |                                       | **Fonction** |   |
|   |                  |                  |             |                                       |              |   |
|   | **Commutateur3** |                  |             |                                       | Réservé      |   |
|   |                  | **Commutateur4** |             |                                       |              |   |
|   |                  |                  |             |                                       |              |   |

![](<.gitbook/assets/1 (33).jpeg>)![](<.gitbook/assets/2 (45).png>)

_\\<NOTE>_

-   -   Une fois les paramètres du commutateur Dip modifiés, veuillez débrancher l'alimentation électrique (l'alimentation externe et les piles doivent être retirées), puis rebrancher l'alimentation au VRA. VRA va

fonctionne avec le niveau de sensibilité nouvellement défini après la remise sous tension.

-   **Commencer**
    -   Retirez le capot arrière en dévissant la vis de fixation inférieure, puis en insérant un tournevis à tête plate pour soulever le capot arrière.
    -   En fonction de vos besoins, réglez le commutateur de sensibilité comme indiqué dans le tableau de position du commutateur DIP.
        -   Allumez l'alarme de reconnaissance vocale en la connectant à une alimentation 5 V CC ou à deux piles de type C.
        -   Mettez le panneau de configuration en mode apprentissage
        -   Appuyez sur le bouton de l'alarme de reconnaissance vocale pour transmettre un code d'apprentissage.
        -   Reportez-vous au manuel d’utilisation de votre panneau de commande pour terminer le processus d’apprentissage.
        -   Remplacez le capot arrière.
-   **Test de marche**
    -   -   Une fois le VRA appris avec succès, placez le panneau de commande en mode test de marche, puis appuyez sur le bouton du VRA pour confirmer que cet emplacement est à portée du signal du panneau de commande. Reportez-vous au manuel du panneau de commande pour effectuer le test de marche.
-   **Opération**
    -   -   Une fois le VRA appris avec succès, appuyer une fois sur le bouton activera une alarme d'aide. Lorsque le bouton est enfoncé, le VRA émet un bip.
        -   L'utilisateur peut également prononcer la commande vocale spécifique pour activer une alarme d'aide. Lorsque les mots déclencheurs sont reconnus, le VRA émet un long bip.
        -   Les mots déclencheurs peuvent être « SARA Alarm (allemand) » ou « Help Me (anglais) », selon la version du micrologiciel. "SARA Alarm (allemand)" doit être prononcé deux fois dans les 5 secondes pour déclencher l'alarme, tandis que

2

« Help Me (English) » ne doit être prononcé qu'une seule fois pour activer l'alarme.

-   Appuyer et maintenir le bouton enfoncé pendant 8 secondes ou plus enverra un code d'annulation au panneau de commande pour arrêter l'alarme.

**Façons de demander de l’aide**

![](<.gitbook/assets/3 (45).png>)

OU

**Prononcez le mot-clé déclencheur.****Appuyez sur le bouton Aide.**

![](<.gitbook/assets/4 (29).jpeg>)

_\\<NOTE>_

-   -   Pour garantir la précision de la reconnaissance vocale, évitez d’installer VRA dans une pièce grande ou bruyante.
    -   L'environnement idéal pour la reconnaissance vocale est le silence ou le silence partiel. Si vous appelez la commande vocale avec une voix normale, veuillez parler à moins de 2 mètres du VRA pour garantir le déclenchement de l'alarme.
    -   La fonction de reconnaissance vocale dispose de trois niveaux de sensibilité. Vous pouvez tester avec eux et sélectionner le niveau qui convient le mieux à votre emplacement de montage.
-   **Installation**

Après avoir effectué un test de marche pour confirmer que le VRA se trouve à portée du signal du panneau de commande et que vous êtes satisfait que le niveau de sensibilité sélectionné fonctionne à l'emplacement choisi, vous pouvez procéder à l'installation. Il existe deux manières d'installer VRA : le montage mural et le déploiement en surface.

-   **Montage mural**

Assurez-vous que le VRA est installé à environ la hauteur de la poitrine (environ 130 cm à 150 cm au-dessus du sol), là où le bouton peut être facilement accessible et utilisé.

-   1.  Identifiez le trou de serrure à l'arrière du VRA, percez un trou dans le mur et installez la cheville murale fournie (Figure 1). Monter la vis de fixation et laisser la partie non filetée pour suspendre le VRA, comme indiqué sur la Figure 2.

Figure 1 Figure 2

![](<.gitbook/assets/5 (19).jpeg>)![](<.gitbook/assets/6 (26).jpeg>)

3

1.  Ajustez la fente en trou de serrure du VRA sur la tête de vis. Poussez doucement et fermement le VRA vers le bas, comme indiqué ci-dessous. (Figure 5,6)

Figure 5 Figure 6

![](<.gitbook/assets/7 (23).jpeg>)![](<.gitbook/assets/8 (16).jpeg>)

-   **Placement en surface**

Le VRA est livré avec un coussinet antidérapant sur le dos. Le dispositif peut également être déployé sur une surface plane sans être installé à un emplacement fixe.

![](<.gitbook/assets/9 (23).png>)

4
