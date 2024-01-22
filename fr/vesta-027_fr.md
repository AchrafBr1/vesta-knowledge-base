# VESTA 027

**Convertisseur filaire vers sans fil (HWC-1B)**

HWC-1B est un convertisseur filaire vers sans fil qui convertit les capteurs filaires existants des systèmes d'alarme de sécurité en technologie sans fil. Le HWC-1B peut être installé à un emplacement préférable où il peut envoyer facilement des rapports au panneau de commande sans plus se soucier des scénarios filaires traditionnels. Pour y parvenir, les capteurs filaires existants sont connectés aux zones d'entrée du HWC-1B, il n'est donc pas nécessaire de remplacer les appareils filaires par des transmetteurs individuels.

Le convertisseur facile à utiliser se compose de 9 zones d'entrée, chacune pouvant être connectée à un capteur de sécurité existant par câblage, par ex. Capteur PIR, contact de porte, détecteur de fumée, capteur d'eau, capteur d'incendie, capteur de CO, détecteur de gaz, détecteur de chaleur et détecteur de bris de verre, etc. Cela permet d'économiser sur les coûts d'installation et offre aux maisons et aux entreprises une commodité accrue et des fonctionnalités efficaces pour les utilisateurs. .

-   **Identification des pièces**

1.  **Indicateur LED**
    -   **Alimentation d'entrée LED1 (vert/rouge) :**

![](<.gitbook/assets/0 (29).jpeg>)

LED verte allumée : l'alimentation secteur est connectée.

LED rouge allumée : coupure secteur.

-   **Statut LED2 (jaune) :**

ON : Batterie faible ou déconnexion.

Flash : échec de chargement de la batterie.

-   **LED de transmission 3 (verte) :**

La LED verte clignote lorsqu'un signal est transmis.

-   **LED d'étalonnage d'entrée 4 (verte) :**

ON : Lorsque vous appuyez et maintenez le bouton d'étalonnage pendant 2 secondes.

ON : lorsque l'étalonnage de l'entrée est réussi.

-   **Nécessite un étalonnage LED5 (rouge) :**

Flash : lorsque l'entrée doit être calibrée.

ON : Lorsque vous appuyez et maintenez le bouton d'étalonnage pendant

-   1.  secondes.

1.  **Bouton Test/Apprentissage (SW11).**
2.  **Bouton d'étalonnage (SW12)**
3.  **Bouton de réinitialisation (SW1)**
4.  **Terminal:**Z1~Zones d'entrée Z9.

(Voir_**Diagramme d'application**_pour plus de détails.)

1.  **Bouton de commutation anti-sabotage (SW20).**
2.  **Borne d'alimentation**(Voir_**Diagramme d'application**_pour plus de détails.)

![](<.gitbook/assets/1 (24).jpeg>)

**+12V/terre :**Connectez-vous à l’alimentation.

**12VAUX/GND :**Fournit 12 V CC à 100 mA pour alimenter les appareils connectés.

1.  **Batterie rechargeable**
2.  **Connecteur à deux broches**

Le connecteur à deux broches est utilisé pour la connexion au bloc batterie rechargeable.

1.  **Trous de montage**

-   **Source de courant**

1

**Application de l'adaptateur secteur :**

-   Allumez le HWC-1B en connectant l'adaptateur AC-DC 12 V à deux fils à la borne +12 V/GND.
-   Lorsque l'alimentation électrique est interrompue et rétablie, le HWC-1B transmettra respectivement le signal de panne CA et de restauration.

**Batterie rechargeable:**

-   Un 1,2 V\*8 batteries rechargeables AAA Ni-MH de 750 mAh sont installées à l'intérieur du HWC-1B pour servir de secours en cas de panne de courant. La batterie n'est pas connectée en usine. Veuillez connecter la batterie si vous souhaitez l'utiliser comme alimentation de secours.
-   HWC-1B will charge the rechargeable battery pack automatically when power is supplied and the rechargeable battery pack is connected. When power supply is interrupted, HWC-1B will switch to using the rechargeable battery and continue operation.
-   Lorsque la batterie rechargeable est faible, le HWC-1B transmettra un signal de batterie faible. Lorsque la batterie est chargée, le HWC-1B transmettra le signal de restauration de la batterie.

**Puissance de sortie :**

-   -   Le HWC-1B peut fournir une alimentation 12 V, 100 mA aux appareils connectés via la borne d'alimentation.
-   **Batterie rechargeable**
    -   Le HWC-1B chargera automatiquement la batterie lorsque l'alimentation est connectée. Lorsque l'alimentation électrique est interrompue, le HWC-1B passe à l'utilisation de la batterie rechargeable et continue de fonctionner.
-   **Diagramme d'application**

![](<.gitbook/assets/2 (22).jpeg>)

Le terminal (Z1~Zones d'entrée Z9) permettent de connecter des capteurs filaires existants au convertisseur HWC-1B :

-   Chaque zone d'entrée n'est disponible que pour un seul capteur filaire.
-   Il est essentiel que toutes les zones d'entrée utilisées soient équipées d'une résistance EOL (d'une valeur de 1k à 10k ohms).
-   Conservez les zones d'installation existantes qui ont déjà une résistance EOL (d'une valeur de 1k à 10k ohms).
-   Pour une boucle NC sans résistance EOL, veuillez en ajouter une en série avec la boucle.
-   Pour une boucle NO sans résistance EOL, veuillez en ajouter une en parallèle (à travers) la boucle. Il doit être situé à l'extrémité de la boucle, loin du panneau de commande.

_\\<NOTE>_

-   -   Si vous souhaitez changer les fils sur la zone d'entrée, veuillez d'abord éteindre le HWC-1B, puis changer l'emplacement d'entrée des fils selon vos préférences et rallumer le HWC-1B. Appuyez sur le bouton d'étalonnage pour finaliser le processus de changement.
-   **(SW12) Bouton d'étalonnage**

Après avoir connecté les capteurs existants au HWC-1B, lancez le processus d'étalonnage qui permet au HWC-1B d'apprendre quelle zone sera active et quelles résistances EOL sont utilisées. Toute zone inutilisée/ouverte ne sera pas reconnue et signalée au panneau de contrôle.

-   Assurez-vous que toutes les zones sont bien connectées.
-   Appuyez et maintenez le bouton d'étalonnage**(Su12)**pendant 2 secondes. Les LED4 (vert) et LED5 (rouge) s'allumeront.
-   Une fois l'étalonnage terminé, la LED5 (rouge) s'éteindra. La LED4 (verte) restera allumée pour indiquer que l'étalonnage est réussi.
-   Lorsque l'étalonnage échoue, la LED4 (verte) s'éteint, la LED5 (rouge) clignote pour indiquer une erreur.

_\\<NOTE>_

-   La zone 1 doit être câblée pour que le HWC-1B fonctionne normalement et utilise la fonction d'étalonnage.

2

-   **(SW11) Apprentissage / Test de marche**
    -   Assurez-vous que les appareils sont connectés et correctement calibrés avant de procéder à l’apprentissage.
    -   Reportez-vous au manuel de votre panneau de commande pour mettre le panneau en mode d'apprentissage.
    -   Appuyez sur le bouton Test/Apprentissage**SW11**pour envoyer le code d'apprentissage au panneau de configuration.
    -   Reportez-vous au manuel d'utilisation de votre panneau de commande pour terminer le processus d'apprentissage.
    -   Le bouton Test/Apprentissage est également utilisé pour la fonction Walk Test. Mettez le panneau en mode Walk Test et appuyez sur le bouton pour vérifier la portée et la force du signal.

![](<.gitbook/assets/3 (36).png>)

_\\<NOTE>_

Numéro de zone

-   -   Lorsque HWC-1B est appris dans le système d'alarme, chaque zone active sera reconnue comme type de dispositif de contact de porte. Les utilisateurs peuvent modifier le nom de l'appareil et sélectionner le type d'alarme pour chaque capteur connecté dans la page Modification de l'appareil.
    -   Chaque zone d'entrée apprise enverra un code RF individuel au panneau de commande. Le numéro de zone est indiqué par le dernier chiffre de l'ID de l'appareil.
    -   Le propre statut du HWC-1B (batterie faible, sabotage, etc.) est transmis via la zone 1.
-   **Surveillance**
    -   Le convertisseur transmettra automatiquement des signaux de supervision périodiquement au panneau de commande à des intervalles aléatoires de 30 à 50 minutes en mode de fonctionnement normal.
    -   Si le panneau de commande n'a pas reçu le signal du convertisseur pendant une période prédéfinie, le panneau de commande indiquera que le convertisseur particulier rencontre un problème de manque de signal.
-   **(SW20) Interrupteur anti-sabotage**
    -   Il est conçu pour protéger contre l’ouverture non autorisée du couvercle. Lorsque l'interrupteur anti-sabotage est déclenché, le HWC-1B émet un signal d'ouverture anti-sabotage au panneau de commande pour rapport.
-   **Procédures d'installation**

Le HWC-1B peut être fixé au mur avec le support de montage fourni ou avec les trous de montage pré-percés. Veuillez suivre les étapes ci-dessous pour continuer.

1.  **Avec support de montage :**
2.  Retirez le support de montage fourni.
3.  Utilisez les 2 trous de montage centraux sur le support de montage pour marquer les positions sur le mur.
4.  Percez des trous à l'emplacement de montage et installez des chevilles murales si nécessaire.
5.  Installez les vis de montage à l'emplacement marqué, comme indiqué ci-dessous.

![](<.gitbook/assets/4 (22).jpeg>)

3

1.  Fixez le HWC-1B sur le support comme indiqué ci-dessous.

![](<.gitbook/assets/5 (15).jpeg>)

1.  Tenez le HWC-1B et poussez-le doucement vers le bas comme indiqué ci-dessous.

![](<.gitbook/assets/6 (19).jpeg>)

**B : Avec trous de montage pré-perforés :**

-   1.  Appuyez sur les trous pré-perforés sur les bords du HWC-1B et soulevez doucement le capot avant en même temps.
    2.  Utilisez les 4 trous de montage autour du bord du capot arrière pour marquer la position des trous sur le mur.
    3.  Percez des trous à l’emplacement de montage et installez des chevilles murales.
    4.  Vissez le capot arrière à l’emplacement marqué.
    5.  Remettez le capot avant en place. L'installation est maintenant terminée.
-   **Retour aux paramètres d'usine**

La réinitialisation d'usine effacera le HWC-1B de toutes les informations de zone calibrée.

1.  Débranchez l'alimentation électrique et la batterie.
2.  Press and hold the **Bouton Test/Apprentissage (SW11)**, while holding the button, apply power to power on HWC-1B at the same time.
3.  Maintenez le bouton enfoncé pendant 3 secondes.
4.  LED 1~3 s'allumera. Relâchez le bouton lorsque les LED s'allument. La réinitialisation d'usine est terminée.

4
