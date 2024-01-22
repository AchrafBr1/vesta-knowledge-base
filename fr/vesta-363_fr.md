# VESTA 363

**Prolongateur de portée isolé BUS (ISL-1-BUS)**

**Introduction**

The ISL-1-BUS is an isolated range extender. It can extend the communication range and amplify the signal of wired security system over long distances, while protecting the connected devices against short circuit downstream. The isolator has galvanically separated the input and output terminals. In case when there is a short circuit at the output, all the devices connected to the input of ISL-1-BUS will continue to operate without interruption. The ISL-1-BUS can also boost the voltage up to 13.5V for BUS devices connected to output.

**Identifier les pièces**

![](<.gitbook/assets/0 (5).png>)

1.  **Sortie de câblage BUS pour lignes d'entrée**
2.  **Terminal BUS enfichable pour l'entrée**
3.  **LED pour terminal BUS (entrée)**

La LED s'allume lorsque la borne de sortie BUS A est alimentée.

1.  **Cavalier de résistance de borne pour entrée de borne**

![](<.gitbook/assets/1 (5).jpeg>)

Mettez le cavalier sur OFF en retirant ou en « garant » le lien du cavalier.

![](<.gitbook/assets/2 (4).jpeg>)

Mettez le cavalier sur ON en reposant le lien du cavalier sur les deux broches.

1.  **LED pour borne BUS (sortie A)**

La LED s'allume lorsque la borne de sortie BUS A est alimentée.

1.  **Cavalier de résistance de borne pour borne BUS (sortie A)**

![](<.gitbook/assets/3 (4).jpeg>)Mettez le cavalier sur OFF en retirant ou en « garant » le lien du cavalier.

![](<.gitbook/assets/4 (5).jpeg>)

Mettez le cavalier sur ON en reposant le lien du cavalier sur les deux broches.

1.  **Borne BUS enfichable pour la sortie A**

The LED lights up when the BUS output terminal A is powered.

1.  **Sortie de câblage BUS pour lignes de sortie**
2.  **Sortie B du terminal BUS enfichable**
3.  **LED pour borne BUS (sortie B)**

La LED s'allume lorsque la borne de sortie BUS B est alimentée.

1

1.  **Cavalier de résistance de borne pour borne BUS (sortie B)**

La même fonction que le cavalier de résistance de borne pour la sortie de borne A.

_**Veuillez noter:**_

-   _**Après avoir débranché le(s) terminal(s), lors de la réinstallation du(des) terminal(s) sur la carte, assurez-vous d'installer le(s) terminal(s) dans la même orientation pour éviter les dangers potentiels.**_

**Source de courant**

L'ISL-1-BUS est alimenté par le BUS du panneau hybride. En tant que booster, l'ISL-1-BUS peut fournir une alimentation de 13,5 V, 0,5 A sur chacune de ses bornes de sortie A et B.

**Connexion du câblage**

L'ajout de l'ISL-1-BUS au système BUS existant étendra la portée du BUS et augmentera la puissance jusqu'à 13,5 V, 0,5 A pour chacune de ses bornes de sortie A et B.

Comme la borne d'entrée et les deux bornes de sortie indépendantes sont galvaniquement séparées, l'ISL-1-BUS protège les appareils connectés contre les courts-circuits en aval.

When adding the ISL-1-BUS to the BUS system, BUS will be split into 3 independent BUS segments (BUS line1, BUS line 2, and BUS line 3).

-   Comme le montre le schéma ci-dessous, Hybrid Panel, en tant que premier périphérique BUS sur**BUS ligne 1**est connecté à l'entrée ISL-1-BUS, qui est le périphérique le plus éloigné sur la ligne BUS 1. Assurez-vous de régler les cavaliers de résistance terminale du panneau hybride et l'entrée ISL-1-BUS sur ON pour servir de résistance de terminaison.
-   Les deux bornes de sortie individuelles de l'ISL-1-BUS sont chacune connectées à des appareils BUS distincts via**BUS line 2**et**BUS ligne 3**. La borne de sortie A est le premier appareil sur la ligne BUS 2 ; la borne de sortie B est le premier appareil sur la ligne BUS 3. Assurez-vous de régler les cavaliers de résistance de borne sur ON pour les deux sorties ISL-1-BUS ainsi que pour les appareils BUS les plus éloignés à la fin de chaque ligne BUS pour servir de résistance de terminaison.
-   Le nombre total de dispositifs BUS (appelés « nœuds » ; le panneau hybride compte pour un nœud) sur chaque ligne BUS doit être inférieur ou égal à 32. Sinon, des anomalies du signal BUS pourraient survenir. Dans l’exemple ci-dessous, il y a au total 3 lignes de BUS :**BUS ligne 1**contient 2 nœuds (Hybrid Panel et ISL-1-BUS),**BUS ligne 2**contient 3 nœuds (ISL-1-BUS et 2 appareils BUS),**BUS ligne 3**dispose de 3 nœuds (ISL-1-BUS et 2 appareils BUS).

![](<.gitbook/assets/5 (2).jpeg>)

_**Veuillez également noter :**_

-   _**Comme ISL-1-BUS fournit jusqu'à 0,5 A pour chacune de ses 2 bornes de sortie, il est recommandé de connecter les appareils BUS un par un à la borne de sortie d'ISL-1-BUS pour assurer un fonctionnement optimal du système. Veuillez essayer d'éviter de connecter tous les appareils à la borne de sortie en même temps.**_
-   _**Étant donné que le panneau de commande alimente l'ISL-1-BUS, la distance maximale de câblage entre le panneau de commande et l'ISL-1-BUS est de 300 pieds.**_
-   _**Il est recommandé de n'avoir qu'un seul ISL-1-BUS sur une seule ligne BUS.**_

2
