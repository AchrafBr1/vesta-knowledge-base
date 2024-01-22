# VESTA 194

![](<.gitbook/assets/0 (79).jpeg>)**Capteur de chute-3**

Ce capteur de chute est conçu pour activer le panneau de commande en appuyant manuellement sur un bouton ou en détectant automatiquement les chutes pour appeler de l'aide en cas d'urgence.

**A. Identification des pièces**

![](<.gitbook/assets/1 (59).png>)![](<.gitbook/assets/2 (64).jpeg>)

-   1.  **Boucle de lanière**
    2.  **LED verte/rouge**
        -   La LED verte clignote pendant 1 seconde : lorsqu'elle est allumée.
        -   LED verte CLIGNOTANT : transmission du signal à la centrale.
        -   LED rouge FLASH : transmission du signal au panneau de commande dans des conditions de batterie faible.
        -   LED rouge FLASH 3 fois : état de batterie faible détecté lors de la mise sous tension.
    3.  **Bouton actif**
        -   -   Appuyez sur le bouton actif pour activer le panneau de commande.
            -   Appuyez et maintenez le bouton pendant 8 secondes pour annuler l'alarme.
            -   Appuyez et maintenez le bouton pendant 8 secondes pour recevoir les données de niveau de sensibilité du panneau de commande.
    4.  **Couvercle du compartiment à piles**

1.  **Détection automatique de batterie faible**

![](<.gitbook/assets/3 (57).jpeg>)![](<.gitbook/assets/4 (64).png>)

Le capteur de chute dispose d'une détection automatique de batterie faible.

-   -   Une fois la batterie insérée, le capteur de chute vérifiera automatiquement la tension de la batterie et transmettra le signal d'état de la batterie au panneau de commande toutes les 24 heures. Si une batterie faible est détectée 3 fois de suite, le capteur de chute entrera en état de batterie faible et transmettra un signal de batterie faible toutes les 12 heures.

1.  **Apprendre en cas de chute**

Étape 1. Mettez le panneau de commande en mode d'apprentissage (Veuillez vous référer au manuel du panneau de commande pour plus de détails.) Étape 2. Appuyez sur le bouton du capteur de chute. Un signal radio sera transmis au panneau de commande.

Étape 3. Veuillez vous référer au manuel d'utilisation de votre panneau de contrôle pour terminer le processus d'apprentissage.

**D. Batterie**

Le capteur de chute utilise une pile au lithium CR2477 3 V comme source d'alimentation.

Si la tension de la batterie est faible, un signal de batterie faible sera envoyé au panneau de commande pour avertir l'utilisateur. De plus, lorsqu'elle est activée lorsque la batterie est faible, la LED rouge clignote pour rappeler à l'utilisateur de remplacer la batterie.

![](<.gitbook/assets/5 (66).png>)

_\\<NOTE>_

-   -   Il est interdit d'apprendre le capteur de chute au panneau de commande lorsque celui-ci est en état de batterie faible.

1.  **Réglage du niveau de sensibilité**

La sensibilité du capteur de chute est programmable à partir du panneau de commande. Cinq niveaux de sensibilité sont disponibles pour la sélection.

Le niveau 1 fait référence au niveau de sensibilité le plus bas, tandis que le niveau 5 fait référence au niveau de sensibilité le plus élevé.

| Niveau de sensibilité | Valeurs            |
| --------------------- | ------------------ |
|                       |                    |
| Niveau 1              | 130 ms             |
|                       |                    |
| Niveau 2              | 110 ms             |
|                       |                    |
| Niveau 3              | 90 ms (par défaut) |
|                       |                    |
| Niveau 4              | 70 ms              |
|                       |                    |
| Niveau 5              | 50 ms              |
|                       |                    |

![](<.gitbook/assets/6 (46).png>)

_\\<NOTE>_

-   Après avoir réglé le niveau de sensibilité à partir du panneau de commande, veuillez appuyer et maintenir enfoncé le bouton du capteur de chute pendant 8 heures.

1

![](<.gitbook/assets/7 (41).png>)secondes pour recevoir les données de niveau de sensibilité du panneau de commande. La LED (verte en mode normal ; rouge en cas de batterie faible) s'allumera lors de la réception de données du panneau de commande.

**F. Détection d'inactivité**

Si une chute est détectée, le capteur transmettra un signal d'alarme au panneau de commande. Si aucun mouvement brusque n'a été détecté dans les 10 secondes suivant la détection de chute, le capteur de chute transmettra un autre code d'inactivité au panneau de commande.

**G. Recommandation d'utilisation**

-   Meilleure façon de porter un capteur de chute**(O)**
    1.  Laissez-le pendre devant la poitrine et ajustez la longueur du collier pour que le capteur pende au bas du sternum comme indiqué sur l'image ci-dessous.
    2.  Portez le pendentif exposé à l’extérieur et devant tout vêtement ou veste lourde/plume.

![](<.gitbook/assets/8 (37).jpeg>)

-   -   1.  En cas de chute, il est préférable que le capteur de chute puisse toucher le sol.
    -   Mauvaise façon de porter un capteur de chute**(X)**
        1.  Un collier trop court (autour de la clavicule) ou trop long (sous le sternum) est susceptible de provoquer un faux déclenchement ou une absence de réponse.
        2.  Le capteur de chute porté dans une poche poitrine entraînera une condition non détectée.
    -   Placez soigneusement le capteur de chute sur un bureau lorsque vous ne l'utilisez pas afin d'éviter de déclencher une fausse alarme.
    -   En raison de la nature du mécanisme de détection des chutes, la détection des chutes ne peut pas être précise à 100 %. Les fausses alarmes ou les échecs de détection lors d’une utilisation quotidienne n’ont pas pu être complètement évités. Veuillez utiliser le bouton actif pour activer l'alarme manuellement lorsque cela est nécessaire pour garantir la sécurité.

1.  **Sleep Mode**
    -   Si le capteur de chute reste immobile pendant plus de 3 heures, il entrera en mode veille. Si un mouvement est détecté pendant le mode veille, le capteur de chute lancera un compte à rebours d'une minute pour revenir au mode de fonctionnement normal. La fonction de détection de chute est désactivée pendant la minuterie d'une minute et l'utilisateur est autorisé à mettre le capteur de chute sans activer de fausse alarme. Lorsque la minuterie d'une minute expire, le capteur de chute revient à son fonctionnement normal.
2.  **Essai**

Pendant le test, ne déclenchez pas le capteur de chute deux fois dans un intervalle de 10 secondes.

![](<.gitbook/assets/9 (38).png>)

_**Déclaration FCC**_

_Cet appareil est conforme à la partie 15 des règles FCC. L’exploitation est soumise aux deux conditions suivantes :_

1.  _Cet appareil ne doit pas provoquer d'interférences nuisibles et_
2.  _Cet appareil doit accepter toute interférence reçue, y compris les interférences susceptibles de provoquer un fonctionnement indésirable._

![](<.gitbook/assets/10 (21).jpeg>)

_**Attention FCC :**_

_Pour garantir une conformité continue, tout changement ou modification non expressément approuvé par la partie responsable de la conformité peut annuler le droit de l'utilisateur à utiliser cet équipement. (Exemple : utilisez uniquement des câbles d'interface blindés lors de la connexion à un ordinateur ou à des périphériques)._

2
