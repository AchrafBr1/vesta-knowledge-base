# VESTA 060

Capteur de contact de porte/choc et vibration (DCSV-23)

DCSV-23 est un capteur de contact/choc de porte capable d'envoyer un signal d'ouverture de porte au panneau de commande lors de la détection d'une ouverture de porte/fenêtre ou d'une détection de choc/vibration.

![DCSV-23ZBS](<.gitbook/assets/0 (13).jpeg>)La conception du capteur de contact de porte/choc et vibration se compose d’un couvercle et d’une base. Le couvercle contient tous les composants électroniques et la base fournit un moyen de fixation de l'appareil. Un interrupteur anti-sabotage sur circuit imprimé fourni offre une protection contre l'ouverture et/ou le retrait non autorisé de l'appareil.

Identification des pièces

1.  **Indicateur LED/bouton de test**

-   Appuyez une fois sur le bouton pour envoyer un code d'apprentissage ou passer en mode test pendant 3 minutes.

1.  **Vis de fixation du couvercle**
2.  **Trous de montage**
3.  **Interrupteur anti-sabotage**

-   Fournit une protection contre l’ouverture et/ou le retrait non autorisé de l’appareil de la surface de montage.

1.  **Isolateur de batterie**
2.  **Cavalier du mode de détection (JP3)**

-   Se référer à la rubrique_**Mode de détection de chocs/vibrations**_pour plus de détails.

1.  **Cavalier de réglage de la sensibilité (JP4,JP5)**

-   Se référer à la rubrique_**Ajustement de la sensibilité**_pour plus de détails.

1.  **Cavalier du commutateur à lames (JP1)**

-   Se référer à la rubrique_**Commutateur à lames**_pour plus de détails.

1.  **Compartiment à piles**
2.  **Aimant**
3.  **Aimant Trou de vis**
4.  **Entretoise magnétique**

Caractéristiques

Sauteur**SUR**(Le cavalier est inséré) : Le commutateur à lames est_**désactivé.**_

![jumper open](<.gitbook/assets/3 (21).png>)

Sauteur**DÉSACTIVÉ**(Le cavalier est retiré ou garé sur une broche) : Le commutateur Reed est_**activé**_et l'appareil fonctionne désormais comme un contact de porte. (_**Défaut**_)

-   L'interrupteur à lames doit être désactivé si l'appareil n'est pas utilisé comme contact de porte.
-   _**Mode de détection de chocs/vibrations**_
-   La fonction de détection de chocs/vibrations de l’appareil peut être déclenchée en fonction des différents modes sélectionnés.
-   **Mode impulsion unique**

L'appareil est déclenché par une seule détection d'impulsion qui dépasse le seuil de détection.

-   **Nombre d'impulsions/mode de vibration accumulée**

L'appareil est déclenché par l'une des conditions suivantes :

1.  Quand**3**le nombre d'impulsions est détecté dans**20****secondes**.
2.  Lorsque des vibrations mineures accumulées sont détectées avec**2 minutes**dépasse le seuil de détection.

-   Les modes de détection sont sélectionnés à l'aide du cavalier JP3 :

![jumper close](<.gitbook/assets/4 (20).png>)Sauteur**SUR**(Le cavalier est inséré) :**Mode impulsion unique**. (_**Défaut**_)

![jumper open](<.gitbook/assets/5 (13).png>)Sauteur**DÉSACTIVÉ**(Le lien de cavalier est retiré ou garé sur une broche) :**Nombre d'impulsions/mode de vibration accumulée**

-   _**Ajustement de la sensibilité**_
-   Utilisez les commutateurs de cavalier JP4 et JP5 pour déterminer la sensibilité requise pour activer le contact de porte/capteur de vibrations de choc. Reportez-vous au tableau ci-dessous pour sélectionner la sensibilité souhaitée.

| JP4       | JP5       | Sensibilité aux chocs |
| --------- | --------- | --------------------- |
| SUR       | DÉSACTIVÉ | Faible                |
| DÉSACTIVÉ | SUR       | Moyen (_**défaut**_)  |
| SUR       | SUR       | Haut                  |

-   _**Batterie**_
-   Le capteur de contact de porte/vibration de choc utilise une pile au lithium CR123 3 V comme source d'alimentation. La batterie est installée dans le compartiment à batterie avec un isolant de batterie inséré. Pour activer la batterie, retirez simplement l'isolant de la batterie.
-   Le capteur de contact de porte/choc et vibration peut détecter un état de batterie faible. Lorsque la tension de la batterie est faible, un signal de batterie faible sera envoyé au panneau de commande pour informer de la condition. La LED s'allumera lorsque le contact de porte/capteur de vibrations de choc est activé lorsque la batterie est faible. Lorsque la batterie est épuisée, le contact de porte/capteur de vibrations de choc arrêtera toutes les fonctions, la LED clignotera toutes les 4 secondes.
-   Lors du changement des piles, après avoir retiré les anciennes piles, appuyez deux fois sur l'interrupteur anti-sabotage pour les décharger complètement avant d'insérer de nouvelles piles.
-   _**Autoprotection**_
-   Le capteur de contact de porte/choc et de vibration est protégé par un interrupteur anti-sabotage qui est comprimé contre la surface de montage lorsque le contact de porte/capteur de choc et de vibration est monté. Chaque fois que le contact de porte/capteur de vibrations de choc est retiré de la surface montée ou que le couvercle est ouvert, l'interrupteur d'autoprotection sera activé et l'appareil enverra un signal d'ouverture d'autoprotection pour rappeler à l'utilisateur la condition.
-   _**Surveillance**_
-   Le capteur de contact de porte/choc et vibration transmettra automatiquement un signal de supervision périodiquement au panneau de commande à des intervalles aléatoires de 30 à 50 minutes.
-   Si le panneau de commande n'a pas reçu le signal du contact de porte/capteur de vibrations de choc pendant une période prédéfinie, le panneau de commande indiquera que le contact de porte/capteur de vibrations de choc particulier rencontre un problème de manque de signal.
-   _**Mode d'essai**_
-   En mode normal, appuyez sur le bouton Test pour transmettre un signal de test et un code d'apprentissage au panneau de commande. Le capteur de contact de porte/choc et vibration entrera également en mode test pendant 3 minutes.
-   En mode test, la LED s'allume chaque fois que le contact de porte/capteur de vibrations de choc est activé.
-   Chaque pression supplémentaire sur le bouton de test réinitialisera la durée du mode test à 3 minutes.
-   _**Commencer**_
-   Retirez l'isolant de la batterie sur le contact de porte/capteur de vibrations de choc pour mettre sous tension.
-   Mettez le panneau de commande en mode d'apprentissage (veuillez vous référer au manuel d'utilisation du panneau)
-   Appuyez sur le bouton de test du contact de porte/capteur de vibrations de choc
-   Reportez-vous au manuel d'utilisation de votre panneau de commande pour terminer le processus d'apprentissage.
-   Une fois le capteur de contact de porte/choc et vibration appris, placez le panneau de commande dans (**Test de marche**), maintenez le contact de porte/capteur de vibrations de choc à l'emplacement souhaité et appuyez sur le bouton de test pour transmettre le signal de test au panneau de commande. Si le panneau de commande se trouve dans la plage de signal du contact de porte/capteur de vibrations, le panneau affichera les informations du contact de porte/capteur de vibrations en conséquence.
-   Procédez au montage et à l'installation une fois que vous êtes convaincu que l'emplacement du contact de porte/capteur de vibrations de choc fonctionne correctement.

Installation

-   _Montage du contact de porte/capteur de vibrations_

![](<.gitbook/assets/6 (9).png>)**Montage comme contact de porte :**

-   Le capteur de contact de porte/choc et vibration doit être installé soit à la verticale, soit à l'envers pour garantir que le côté marqué par la nervure soit face à l'aimant.
-   La distance entre le contact de porte/capteur de vibrations et de choc et l'aimant ne doit pas dépasser 15 mm lorsque la porte est fermée.
-   Évitez de monter le contact de porte/capteur de vibrations de choc sur une surface métallique. En cas de montage sur une surface métallique, assurez-vous de tester si le contact de porte/le capteur de vibrations de choc peuvent être déclenchés lorsque la porte est ouverte.
-   Montez l'appareil le plus haut possible.

**Montage comme capteur de vibrations et de chocs :**

-   monter sur_**Béton, coffre-fort, encadrements de fenêtres.**_
-   Lorsqu'il est monté sur un cadre de porte/fenêtre, l'appareil sert également de contact de porte.
-   Reportez-vous au tableau ci-dessous pour obtenir des informations sur la plage de détection des chocs/vibrations et le réglage de la sensibilité en fonction des différents matériaux de surface. Utilisez le cavalier de réglage de la sensibilité pour sélectionner la sensibilité souhaitée.

|                                                         | Fenêtre                                  | Porte                                         | Mur en béton | Coffre-fort                 |   |
| ------------------------------------------------------- | ---------------------------------------- | --------------------------------------------- | ------------ | --------------------------- | - |
| Épaisseur                                               | >5mm                                     | &lt;40mm                                      | -            | 3mm                         |   |
| Matériel                                                | <p>Régulier/Tempéré/</p><p>Feuilleté</p> | Bois/Acier                                    | Béton        | Acier + Dioxyde de Silicium |   |
| Emplacement d'installation                              | Cadre de fenêtre                         | Cadre de porte                                | Mur          | 2 cm du pivot de la porte   |   |
| Mode de détection                                       | Mode impulsion unique                    |  Nombre d'impulsions / vibrations accumulées |              |                             |   |
| <p>Sensibilité aux chocs</p><p>(zone de couverture)</p> | Faible                                   | 2000mm                                        | 1000mm       | 500 mm                      | - |
| Moyen                                                   | 3000 mm                                  | 2000mm                                        | 1500mm       | -                           |   |
| Haut                                                    | 4000 mm                                  | 3000 mm                                       | 2000mm       | 1400 mm                     |   |

![](<.gitbook/assets/7 (6).png>)

-   _Procédure de montage_

1.  Utilisez les 2 trous de montage sur la couverture arrière comme modèle pour le positionnement.
2.  Utilisez les chevilles murales fournies pour l'installation de cadres de fenêtres, de murs en béton ou de coffres-forts.
3.  Vissez le contact de porte/capteur de vibrations dans les chevilles murales. (Le perçage est recommandé lors du montage sur de l'acier tel qu'un coffre-fort, ou vous pouvez également utiliser l'autocollant fourni dans l'emballage).
4.  Fixez l'aimant sur la porte à l'aide d'un petit morceau de ruban adhésif double face ou avec les vis fournies.
5.  Pour monter l'aimant, utilisez les 2 trous de vis de l'aimant comme modèle pour un positionnement approprié des trous.

&lt;Remarque>

-   L'aimant doit s'aligner avec le côté marqué des nervures du contact de porte. Si nécessaire, appliquez l'entretoise magnétique à l'arrière de l'aimant pour mieux aligner l'aimant sur les marques de nervures.

1.  Vissez l'aimant et insérez les deux capuchons blancs dans les trous de vis de l'aimant pour une intégrité esthétique.
2.  L'installation est maintenant terminée.

\\<NOTE>

-   Ne montez pas l'appareil sur des matériaux de surface soumis à des vibrations fréquentes, afin d'éviter de fausses alarmes.
-   ![](<.gitbook/assets/8 (6).png>)Lors du montage sur un boîtier de sécurité, montez le capteur de contact/choc de porte à moins de 2 cm du pivot de la porte (reportez-vous à l'image ci-dessous).
