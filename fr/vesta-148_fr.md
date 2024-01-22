# VESTA 148

**EIRP-J1/EIRC-J2 Apprendre dans les instructions**

L'émetteur GEN-TX est installé à l'intérieur des EIRP-J1 et EIRC-J2, leur permettant d'envoyer des signaux RF sans fil au panneau de commande.

Les antennes du GEN-TX sont différentes selon la fréquence 433 et 868.

**PIRE-J1****EIRC-J2****Fréquence 433****Fréquence 868**

![](<.gitbook/assets/0 (43).png>)

-   _**Identifier les pièces**_

1.  **Bouton Apprendre/Test**
2.  **Batterie (CR2)**
3.  **Cavalier de supervision (JP2)**
4.  **Indicateur LED (rouge)**

![](<.gitbook/assets/1 (49).png>)![](<.gitbook/assets/2 (54).png>)

-   _**Indicateur LED**_

En mode de fonctionnement normal, le voyant LED reste éteint sauf :

-   -   Lorsque le détecteur de mouvement est en état de batterie faible, chaque fois qu'il transmet un mouvement détecté, la LED clignote 6 fois.
    -   Lorsque l'interrupteur anti-sabotage est déclenché, la LED clignote 6 fois pour indiquer qu'elle transmet "**Altérer**» signale-t-il.
    -   Lorsque la condition de sabotage persiste, chaque fois qu'il transmet un mouvement détecté, la LED clignote 6 fois.
    -   Lorsque la batterie est épuisée, la LED clignote toutes les 4 secondes.
-   _**Apprentissage**_
    -   Pour l'EIRP-J1, veuillez d'abord détacher le boîtier arrière et la plaque de montage. Pour EIRC-J2, veuillez d'abord détacher la base de montage. (Veuillez vous référer aux instructions d'installation du VXI-R et du FTN-R-PT pour plus de détails.)
    -   Retirez l'isolant de la batterie pour activer la batterie.
    -   Mettez le panneau de commande en mode apprentissage, reportez-vous au manuel du panneau de commande pour plus de détails.
    -   Appuyez sur le bouton Apprendre.
    -   Reportez-vous au manuel du panneau de commande pour terminer le processus d'apprentissage.

![](<.gitbook/assets/3 (53).png>)

1

-   ![](<.gitbook/assets/4 (53).png>)_**Test de marche**_
    -   Une fois le détecteur appris, placez le panneau de commande sur «**Test de marche**", maintenez le détecteur à l'emplacement souhaité et appuyez sur le bouton Test pour confirmer que cet emplacement est à portée du signal du panneau de commande, reportez-vous au manuel du panneau de commande pour terminer le test de marche.
    -   Lorsque vous êtes convaincu que le détecteur fonctionne à l'emplacement choisi, vous pouvez procéder au montage.
-   _**Batterie**_
    -   Le détecteur utilise une pile au lithium « CR2 » de 3 V comme source d’alimentation.
    -   Lorsqu'une batterie faible est détectée, un signal de batterie faible sera envoyé au panneau de commande avec des transmissions de signal régulières pour que le panneau de commande affiche l'état en conséquence.
    -   Lorsque la batterie est épuisée, le détecteur arrêtera toutes ses fonctions, la LED clignotera toutes les 4 secondes.
    -   Lors du changement de batterie, après avoir retiré l'ancienne batterie, appuyez deux fois sur le bouton d'apprentissage pour la décharger complètement avant d'insérer une nouvelle batterie.
-   _**Surveillance**_
    -   Après l'installation, le détecteur transmettra automatiquement et périodiquement des signaux de surveillance au panneau de commande à des intervalles aléatoires de 30 à 50 minutes.
    -   Si le panneau de commande n'a pas reçu le signal du détecteur pendant la période de temps prédéfinie, le panneau de commande indiquera sur son écran que le détecteur en question rencontre un problème de manque de signal.

![](<.gitbook/assets/5 (52).png>)![](<.gitbook/assets/6 (34).png>)![](<.gitbook/assets/7 (32).jpeg>)

**Cavalier OFF (par défaut d'usine)**

\-Lorsque le cavalier (JP2) est réglé sur OFF, la supervision est activée.

**Cavalier activé**

![](<.gitbook/assets/8 (25).jpeg>)

-   Lorsque le cavalier (JP2) est réglé sur ON, la supervision est désactivée.

2
