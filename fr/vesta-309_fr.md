# VESTA 309

![](<.gitbook/assets/0 (57).png>)**Détecteur de fumée et de monoxyde de carbone (SDCO-3-RhTHM-ZW-SC-AC-OTA) Introduction**

SDCO-3-RhTHM-ZW-SC-AC-OTA est un détecteur de fumée et de monoxyde de carbone Z-Wave avec capteur PIR intégré, détection de température, d'humidité et de chaleur, ainsi que des invites vocales et permet d'accéder au « S2 Classe « non authentifié » et prend en charge à la fois l'inclusion Z-Wave SmartStart et l'inclusion classique. Il est capable d'envoyer des signaux sans fil à la passerelle/au panneau de commande Z-Wave lors de la détection de particules de fumée ou de monoxyde de carbone. L'appareil est également connecté en série avec d'autres capteurs de la passerelle Z-Wave pour servir de sirène supplémentaire. Lorsqu'un autre capteur du réseau Z-Wave est activé et envoie un signal d'alarme, le détecteur de fumée déclenche également une alarme avec son buzzer intégré faisant office de sirène pour aider à émettre un avertissement sonore (pour les modèles à connexion série).

Le SDCO-3 est conçu pour être monté au plafond ou au sommet des cages d'escalier lorsque la fumée se concentre afin de déclencher une alarme en temps opportun et de protéger votre maison des risques d'incendie.

Le détecteur SDCO est un appareil compatible Z-Wave et est entièrement compatible avec tout réseau compatible Z-Wave. Z-Wave est un protocole de communication sans fil qui utilise une radio RF de faible puissance.

![](<.gitbook/assets/1 (72).png>)

_**Identification des pièces**_

1. **Conférencier**
2. **Bouton**
   * Appuyez une fois sur le bouton pour envoyer un test d'alarme, un test d'alarme désactivé et des signaux de température et d'humidité pour tester le détecteur de fumée et de monoxyde de carbone.
   * Appuyez sur le bouton pendant 5 secondes, relâchez le bouton jusqu'à ce que la LED orange s'allume. Ensuite, la LED orange commencera à clignoter pour indiquer qu'elle est entrée en mode snooze. Voir Mode Snooze temporaire dans la section Fonctionnalités pour plus de détails.
   * Appuyez une fois sur le bouton pendant l'alarme pour faire taire l'alarme.
   * Appuyez 3 fois sur le bouton en 1,5 seconde pour envoyer un code d'inclusion.
   * Appuyez et maintenez le bouton pendant 10 secondes. Relâchez le bouton lorsque vous entendez 2 bips pour entrer dans le processus d'étalonnage de la fumée et d'autodiagnostic du CO.
   * Appuyez et maintenez le bouton pendant 20 secondes. Relâchez le bouton lorsque vous entendez 3 bips pour effectuer une réinitialisation d'usine.
   * Appuyez deux fois sur le bouton avant d'insérer de nouvelles piles.
3. **Capteur de mouvement PIR**
4. **Indicateur LED**

**LED rouge**

* S'allume brièvement : transmission du signal.
* Flash rapide : Alarmant.
* Clignote toutes les secondes : en mode silence d’alarme.
* Clignote toutes les 2 secondes : pendant le processus d’échauffement et d’étalonnage.
* Clignote rapidement 3 fois toutes les 8 secondes : de la fumée est détectée pendant la période de vérification d'incendie.
* Clignote rapidement 2 fois toutes les 5 secondes : en mode snooze

**LED ambre**

* Clignote toutes les secondes : mise sous tension de l'appareil/échec de l'étalonnage.
* Clignote deux fois toutes les 5 secondes : dysfonctionnement de l'appareil.
* Clignote toutes les 45 secondes : état de batterie faible

**LED rouge et orange (orange lorsque vous regardez de l'extérieur)**

* S'allume : le capteur de température/humidité est en panne.
* Clignote toutes les 4 secondes : Batterie épuisée.

1

1. **Avertisseur sonore**
2. **Trous de montage**
3. **Support de montage**
4. **Interrupteur anti-sabotage**
5. **Couvercle du compartiment à piles**
6. **Coupe-batterie (à l'intérieur)**
7. **Trou pré-percé pour le câblage**
8. **Vis de fixation du couvercle du compartiment à piles**
9. **Encoches**
10. **Port de mise à jour du micrologiciel (USB Type-C)**
    * Pour la mise à jour du micrologiciel avec un câble personnalisé uniquement.\*\*Veuillez noter:\*\*Une mauvaise utilisation d’un câble USB Type C normal peut entraîner un dysfonctionnement de l’appareil.

**Caractéristiques**

![](<.gitbook/assets/2 (80).png>)

* _**Détection de batterie et de batterie faible**_
  * Le modèle SDCO-3-RhTHM-ZW-SC-AC-OTA utilise CA 100-240 V comme source d'alimentation et dispose de trois piles rechargeables AAA Ni-MH de 600 mAh comme batterie de secours en cas de panne de courant. La batterie est incluse dans le colis.
  * Lorsque la batterie rechargeable est en charge, le détecteur SDCO signalera son pourcentage de batterie à la passerelle/au panneau de commande respectivement à 100 %, 90 %, 80 %, 70 %, 60 %, 50 %, 40 %, 30 % et 20 %. (batterie faible).
  * Si une panne de courant alternatif est détectée, le détecteur SDCO enverra un rapport de panne de courant alternatif au panneau de commande.
  * Lorsque la batterie du détecteur SDCO est faible, un signal de batterie faible sera transmis avec les transmissions de signaux régulières. La LED orange clignotera accompagnée d'un bip de faible volume une fois toutes les 45 secondes.
  * Les LED rouge et orange clignoteront une fois toutes les 4 secondes lorsque la batterie est épuisée.
* _**Interrupteur anti-sabotage**_
  * Le détecteur SDCO est protégé par un interrupteur anti-sabotage qui est comprimé lorsque le détecteur SDCO est accroché au support de montage. Lorsque le détecteur SDCO est retiré du support de montage, l'interrupteur d'autoprotection sera activé et le détecteur SDCO enverra un signal d'autoprotection au panneau de commande du système pour rappeler à l'utilisateur cette condition.
  * Le détecteur SDCO enverra un signal de fermeture inviolable au panneau de commande une fois l'appareil accroché au support de montage. Veuillez noter que le détecteur SDCO doit d'abord être inclus dans le réseau Z-Wave.
* _**Mode sensibilité**_
  * Le niveau de sensibilité de l'appareil peut être ajusté à l'aide de la commande de configuration de Z-Wave. Jusqu'à huit niveaux de sensibilité peuvent être configurés (par défaut : 0x04). Réglez 0x01 pour le niveau de sensibilité le plus élevé. Veuillez vous référer à la page 11\*\*"Configurations"\*\*pour plus de détails.
* _**Mode répétition temporaire**_
  * Cette fonction vous permet de suspendre la fonction de détection de mouvement pendant une période de temps spécifiée pour éviter les alertes de mouvement indésirables sans avoir à désarmer l'appareil.
  * Par défaut, la fonction est désactivée et peut être activée en appuyant sur le bouton pendant 5 secondes, ce qui active le mode pendant 5 minutes. Vous pouvez également activer le mode à l'aide de la commande de configuration de Z-Wave, et jusqu'à 36 heures peuvent être configurées. Le mode snooze prendra fin dès que vous appuierez sur un bouton ou utiliserez l'appareil. Veuillez vous référer à la page 12\*\*"Configurations"\*\*pour plus de détails.
* _**Ajout d'un appareil (inclusion)**_

![](<.gitbook/assets/3 (78).png>) ![](<.gitbook/assets/4 (83).png>) ![](<.gitbook/assets/5 (82).png>) ![](<.gitbook/assets/6 (62).png>)

L'appareil prend en charge à la fois le processus d'inclusion classique et le processus d'inclusion SmartStart.

**Inclusion classique**

Ce produit peut être inclus et utilisé dans n'importe quel réseau Z-Wave avec d'autres appareils certifiés Z-Wave d'autres fabricants et/ou applications. Tous les nœuds du réseau non alimentés par batterie agiront comme des répéteurs, quel que soit le fournisseur, afin d'augmenter la fiabilité du réseau.

* Pour ajouter le détecteur SDCO au panneau de commande, vous devez d'abord le connecter à l'alimentation secteur (secteur). Veuillez suivre les étapes ci-dessous pour continuer.

\*\*Étape 1.\*\*Avant de commencer, recherchez le disjoncteur ou la boîte à fusibles.

\*\*Étape 2.\*\*Une fois que vous l'avez trouvé, ouvrez la porte et éteignez l'interrupteur principal.

\*\*Étape 3.\*\*Deux connecteurs d'épissure Wago 221 sont fournis. Retirez un connecteur. Tirez le levier vers le haut et insérez le fil blanc.\*\*Étape 4.\*\*Repoussez le levier vers le bas. Le boîtier transparent vous permet de vérifier si le fil est correctement connecté.**Assurez-vous que le**

**le fil est fermement maintenu en place avant de continuer.**

\*\*Étape 5.\*\*Répétez les étapes 3 et 4 pour insérer le fil noir. L'insertion des deux fils du même côté (à droite), comme indiqué ci-dessous, des deux connecteurs permet une installation plus facile dans les étapes suivantes.

\*\*Étape 6.\*\*Insérez les fils CA dans les deux connecteurs respectivement, comme indiqué ci-dessous. Si vous placez l'interrupteur de la batterie sur la position ON, la batterie rechargeable commencera à se charger.

![](<.gitbook/assets/7 (56).png>)

_Figure 1. Insérez les fils blanc et noir._

![](<.gitbook/assets/8 (57).png>)

_Figure 2. Vérifiez si les fils sont correctement connectés._

![](<.gitbook/assets/9 (52).png>)

_Figure 3. Insérez les fils CA._

![](<.gitbook/assets/10 (54).png>)

2

\*\*Étape 7.\*\*Retournez le détecteur SDCO. Vous entendrez « Bienvenue, détecteur de fumée et détecteur de monoxyde de carbone », indiquant qu'il est prêt pour une configuration ultérieure (pour les modèles connectés en série uniquement).

* Le détecteur SDCO permet aux utilisateurs de configurer une invite de localisation pour une zone, d'afficher la liste complète des emplacements et des instructions de configuration, veuillez vous référer à «_**Invite vocale**_» Section pour plus de détails. Il est recommandé d'effectuer un processus de préchauffage et d'étalonnage**avant**inclure votre appareil dans le coordinateur Z-Wave.

**\\**

1. Le détecteur SDCO émettra 2 bips courts et commencera le processus de préchauffage pour**1**minute. La LED clignotera toutes les 2 secondes.
2. À l'expiration de la période de préchauffage d'une minute, le détecteur SDCO émettra un bip pour indiquer qu'il entre maintenant dans le processus d'étalonnage. Le processus d'étalonnage prend 1\~7 minutes ; la LED continuera à clignoter pendant l'étalonnage.
3. Une fois l'étalonnage terminé, le détecteur SDCO émettra un son à 2 tons et la LED cessera de clignoter pour indiquer qu'il fonctionne maintenant normalement. Si l'étalonnage échoue, le détecteur SDCO émettra des bips continus.

**\\**

1. Mettez la passerelle ou le panneau de commande Z-Wave en mode Inclusion (veuillez vous référer au manuel de la passerelle ou du panneau de commande Z-Wave).
2. Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton.
3. Reportez-vous au manuel d'utilisation de la passerelle Z-Wave ou du panneau de commande pour terminer le processus d'inclusion.
4. Si le capteur a déjà été inclus dans une autre passerelle/panneau de commande Z-Wave, ou si le capteur ne peut pas être inclus dans la passerelle/panneau de commande Z-Wave actuelle, veuillez d'abord l'exclure (voir Exclusion) avant d'essayer de l'inclure. dans la passerelle/panneau de configuration Z-Wave actuel.

**Inclusion de SmartStart**

![](<.gitbook/assets/11 (29).jpeg>)

Z-Wave SmartStart utilise le DSK de l'appareil pour améliorer et simplifier le processus d'inclusion. DSK est une clé spécifique à l'appareil utilisée pour la communication d'authentification. Les informations DSK sont stockées au format QR code imprimé sur une étiquette et collée à l'extérieur de l'appareil.

Avec un contrôleur Z-wave fournissant l'inclusion SmartStart, l'appareil compatible SmartStart peut être ajouté à un réseau Z-Wave en scannant le code QR Z-Wave sur le produit. Sans aucune autre action, l'appareil sera ajouté automatiquement dans les 10 minutes suivant sa mise sous tension à proximité du réseau.

*
  * Mettez la passerelle Z-Wave ou le panneau de commande dans**Mode d'inclusion**(veuillez vous référer au manuel de la passerelle Z-Wave ou du panneau de commande).
  * Scannez le code QR sur le détecteur SDCO pour récupérer**DSK**.
  * Allumez le détecteur SDCO, une demande d’inclusion SmartStart sera automatiquement envoyée à la passerelle.
  * La passerelle inclura automatiquement l'appareil lors de la reconnaissance de l'appareil en faisant correspondre la demande d'inclusion avec le DSK obtenu
    * Le DSK de l'appareil n'est utilisé que lors de l'inclusion.
    * Le DSK peut être lu sans allumer le détecteur SDCO, il est donc possible de préparer la passerelle pour inclure l'appareil avant d'installer et de mettre sous tension le détecteur SDCO.
    * Si l'appareil a déjà été ajouté (inclus) dans une autre passerelle/panneau de commande Z-Wave, veuillez d'abord l'exclure (voir\_**Suppression d'un périphérique**\_) avant d'essayer de l'inclure dans la passerelle/panneau de configuration Z-Wave actuel. L'appareil n'enverra pas de message

Demande d'inclusion SmartStart s'il se trouve déjà dans une passerelle/un panneau de configuration Z-Wave.

* _**Suppression d'un périphérique (exclusion)**_

![](<.gitbook/assets/12 (46).png>)

Le détecteur SDCO doit être supprimé du réseau Z-Wave existant avant d'être inclus dans un autre.

*
  * Mettez la passerelle ou le panneau de commande Z-Wave en mode d'exclusion (veuillez vous référer au manuel de la passerelle ou du panneau de commande Z-Wave).
  * Dans un délai de 1,5 seconde, appuyez 3 fois sur le bouton et le détecteur SDCO sera supprimé du réseau Z-Wave.
* _**Invite vocale (pour les modèles à connexion série)**_

![](<.gitbook/assets/13 (34).png>)

Le détecteur SDCO permet à l'utilisateur de configurer une invite de localisation pour une zone (par exemple, cuisine ou sous-sol). Lorsqu'une alarme est déclenchée, le détecteur SDCO émettra l'invite vocale préprogrammée pour alerter l'utilisateur d'évacuer. Pour la première configuration, veuillez suivre les étapes ci-dessous :

\*\*Étape 1.\*\*Allumez l’interrupteur de la batterie.

\*\*Étape 2.\*\*L'invite n° 1 « Bienvenue, détecteur de fumée et détecteur de monoxyde de carbone » sera diffusée.

\*\*Étape 3.\*\*L'invite n°2 « Aucun emplacement programmé » sera diffusée.

\*\*Étape 4.\*\*L'invite n°3 « Pour sélectionner l'emplacement, appuyez et maintenez le bouton maintenant » sera jouée.

\*\*Étape 5.\*\*Maintenez le bouton enfoncé et l'invite n°4 « Pour programmer l'emplacement, appuyez et maintenez le bouton une fois que l'emplacement est entendu » sera jouée.\*\*Étape 6.\*\*Continuez à maintenir le bouton enfoncé et l'invite n°6 « Emplacement » sera jouée, suivie des emplacements à sélectionner.

(à partir de l'invite n° 11-31).

\*\*.Étape 7.\*\*Pour configurer une invite de localisation souhaitée, relâchez simplement le bouton.

\*\*. ..\*\*\*\*.Étape 8.\*\*L'appareil émettra l'invite n°7 « Programmé » après avoir relâché le bouton et émettra 2 bips pour confirmation.

| Non | Invite vocale                                                                                                 | Condition                                    |   |   |
| --- | ------------------------------------------------------------------------------------------------------------- | -------------------------------------------- | - | - |
| 1   | Bienvenue, Avertisseur de Fumée et Détecteur de Monoxyde de Carbone                                           | Joué lorsque l'appareil est allumé.          |   |   |
| 2   | Aucun emplacement programmé                                                                                   | Joué pour la première configuration.         |   |   |
| 3   | Pour sélectionner l'emplacement, appuyez et maintenez le bouton maintenant.                                   | Joué pour la configuration de l'emplacement. |   |   |
| 4   | Pour programmer l'emplacement, appuyez et maintenez le bouton enfoncé une fois que l'emplacement est entendu. | Joué pour la configuration de l'emplacement. |   |   |
|     |                                                                                                               |                                              |   |   |
| 5   | Aucun emplacement programmé                                                                                   | Joué pour la configuration de l'emplacement. |   |   |
| 6   | Emplacement                                                                                                   | Joué pour la configuration de l'emplacement. |   |   |
| 7   | Programmé                                                                                                     | Joué pour la configuration de l'emplacement. |   |   |

3

| 8  | Urgence, monoxyde de carbone dans\[nom de la localisation]. | Joué lorsqu'une alarme est déclenchée.           |   |
| -- | ----------------------------------------------------------- | ------------------------------------------------ | - |
| 9  | Urgence, fumée dedans\[nom de la localisation].             | Joué lorsqu'une alarme est déclenchée.           |   |
|    |                                                             |                                                  |   |
| 10 | Évacuer                                                     | Joué lorsqu'une alarme est déclenchée.           |   |
| 11 | Sous-sol                                                    | Joué pour la sélection de l'emplacement.         |   |
| 12 | Salle                                                       | Joué pour la sélection de l'emplacement.         |   |
| 13 | Bureau                                                      | Joué pour la sélection de l'emplacement.         |   |
| 14 | Chambre principale                                          | Joué pour la sélection de l'emplacement.         |   |
| 15 | Chambre à coucher                                           | Joué pour la sélection de l'emplacement.         |   |
| 16 | Chambre d'amis                                              | Joué pour la sélection de l'emplacement.         |   |
| 17 | Cuisine                                                     | Joué pour la sélection de l'emplacement.         |   |
| 18 | Salle à manger                                              | Joué pour la sélection de l'emplacement.         |   |
| 19 | Salon                                                       | Joué pour la sélection de l'emplacement.         |   |
| 20 | Lessive                                                     | Joué pour la sélection de l'emplacement.         |   |
| 21 | Grenier                                                     | Joué pour la sélection de l'emplacement.         |   |
| 22 | Garderie                                                    | Joué pour la sélection de l'emplacement.         |   |
| 23 | Toilettes                                                   | Joué pour la sélection de l'emplacement.         |   |
|    |                                                             |                                                  |   |
| 24 | Salle technique                                             | Joué pour la sélection de l'emplacement.         |   |
|    |                                                             |                                                  |   |
| 25 | Garde-robe                                                  | Joué pour la sélection de l'emplacement.         |   |
|    |                                                             |                                                  |   |
| 26 | Salon mansardé                                              | Joué pour la sélection de l'emplacement.         |   |
|    |                                                             |                                                  |   |
| 27 | Salon du sous-sol                                           | Joué pour la sélection de l'emplacement.         |   |
| 28 | Escalier                                                    | Joué pour la sélection de l'emplacement.         |   |
| 29 | Garage                                                      | Joué pour la sélection de l'emplacement.         |   |
| 30 | Appartement en location                                     | Joué pour la sélection de l'emplacement.         |   |
| 31 | Aucun emplacement                                           | Joué lorsqu'aucun emplacement n'est sélectionné. |   |

* Lorsqu'une alarme de CO, de fumée et/ou de température est déclenchée, la sirène sera activée selon la durée ci-dessous et suivie de messages vocaux pour avertir l'utilisateur d'évacuer.

|                  | Type d'alarme |   |                                                              |                                                             | Modèle d'alarme et d'avertissement vocal |                                                        |                                                                      |                                               |                              |           | Condition    |   |   |   |   |   |   |   |   |   |   |
| ---------------- | ------------- | - | ------------------------------------------------------------ | ----------------------------------------------------------- | ---------------------------------------- | ------------------------------------------------------ | -------------------------------------------------------------------- | --------------------------------------------- | ---------------------------- | --------- | ------------ | - | - | - | - | - | - | - | - | - | - |
|                  |               |   |                                                              | **(Répéter)**                                               |                                          |                                                        | Joué après le son d'avertissement intermittent                       |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              |                                                             |                                          |                                                        |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  | Fumée/chaleur |   |                                                              | Bip --- Bip --- Bip ------ Bip --- Bip --- Bip              |                                          |                                                        | lorsqu'une alarme de fumée ou de chaleur se déclenche. S'il te plaît |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   | Urgence, fumée dedans\[nom de la localisation].              | Emplacement                                                 | .                                        |                                                        |                                                                      | notez que l'invite de localisation sera jouée |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              |                                                             |                                          |                                                        |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              | Évacuer.                                                    |                                          |                                                        |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              |                                                             |                                          | selon le nom de l'emplacement préprogrammé.            |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              |                                                             |                                          |                                                        |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              | **(Répéter)**                                               |                                          |                                                        | Joué après le son d'avertissement intermittent                       |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              |                                                             |                                          |                                                        |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  | CO            |   |                                                              | Bip-Bip-Bip-Bip                                             |                                          |                                                        | lorsqu'une alarme de monoxyde de carbone se déclenche.               |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   | Urgence, monoxyde de carbone dans\[nom de la localisation].  |                                                             |                                          | Veuillez noter que l'invite de localisation sera jouée |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              |                                                             |                                          |                                                        |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              | Emplacement. Évacuer.                                       |                                          |                                                        |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              |                                                             |                                          | selon le nom de l'emplacement préprogrammé.            |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              |                                                             |                                          |                                                        |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              | **(Répéter)**                                               |                                          |                                                        |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              | Bip---Bip---Bip---Bip-Bip-Bip-Bip-----                      |                                          |                                                        | Joué après le son d'avertissement intermittent                       |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              | Bip --- Bip --- Bip                                         |                                          |                                                        | lorsqu'une fumée/chaleur et du monoxyde de carbone                   |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
| Fumée/Chaleur+CO |               |   | Urgence, fumée dedans\[nom de la localisation]. Emplacement. |                                                             |                                          | une alarme est détectée. Veuillez noter l'emplacement  |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              |                                                             |                                          |                                                        |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              | Évacuer.                                                    |                                          |                                                        |                                                                      |                                               | l'invite sera jouée selon le |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              | Urgence, monoxyde de carbone dans\[nom de la localisation]. |                                          |                                                        | nom d'emplacement préprogrammé.                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              | Emplacement. Évacuer.                                       |                                          |                                                        |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              |                                                             |                                          |                                                        |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              | **(Répéter)**                                               |                                          |                                                        | Joué                                                                 | un son d'avertissement                        | quand                        | un voleur |              |   |   |   |   |   |   |   |   |   |   |
|                  | Insectes      |   |                                                              | Son d'alarme pendant 6,5 secondes                           |                                          |                                                        |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              |                                                             | une alarme est détectée.                 |                                                        |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              |                                                             |                                          |                                                        |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              |                                                             |                                          |                                                        |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              | **(Répéter)**                                               |                                          |                                                        | Joué                                                                 |                                               | émet un bip lorsqu'un        | Eau       | l'alarme est |   |   |   |   |   |   |   |   |   |   |
|                  | Eau           |   |                                                              | Bip-Bip-Bip-Bip pendant 6,5 secondes                        |                                          |                                                        |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              |                                                             | détecté.                                 |                                                        |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              |                                                             |                                          |                                                        |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |
|                  |               |   |                                                              |                                                             |                                          |                                                        |                                                                      |                                               |                              |           |              |   |   |   |   |   |   |   |   |   |   |

![](<.gitbook/assets/14 (34).png>)

* _**Vérification incendie**_
  * La vérification d'incendie peut être utilisée pour configurer une minuterie de vérification à l'aide de la commande de configuration de Z-Wave pour le détecteur SDCO. Lorsque la minuterie de vérification d'incendie est réglée, le détecteur SDCO commence à décompter la minuterie de vérification d'incendie lorsque l'appareil est déclenché. Jusqu'à 150 secondes peuvent être définies (par défaut : 0 seconde). Veuillez vous référer à la page 10\*\*"Configurations"\*\*pour plus de détails.
  * Si la fonction de vérification d'incendie est activée, la LED rouge clignotera rapidement 3 fois toutes les 8 secondes si de la fumée est détectée pendant cette période. Une fois la minuterie de vérification d'incendie expirée, le détecteur SDCO activera l'alarme incendie si la concentration de fumée dépasse le seuil de détection.
* _**Détection d'alarme**_

![](<.gitbook/assets/15 (34).png>)

Le détecteur SDCO activera l'alarme incendie lorsque sa fonction de détection de fumée ou de détection de chaleur élevée est déclenchée. Lorsqu'une alarme est activée, le détecteur SDCO transmet un signal d'alarme et déclenche une alarme grâce à son buzzer intégré, la LED rouge clignote rapidement.

**Détection de fumée :**

* Le détecteur SDCO vérifie la concentration de fumée toutes les 8 secondes

4

* Chaque fois que la concentration de fumée dépasse le seuil de détection, le détecteur SDCO envoie un signal actif au panneau de commande et active l'alarme.
* Si la concentration de fumée persiste, le détecteur SDCO continuera à envoyer le signal actif toutes les minutes au panneau de commande.
* Si aucune fumée n'est détectée pendant 20 temps de détection continus, le détecteur SDCO transmettra un signal de restauration.

**Détection de chaleur :**

* Le détecteur SDCO vérifie la température toutes les 10 secondes.
* L'alarme sera activée dans les conditions suivantes :
  * Lorsque la température augmente de 8,25°C par minute (taux de montée).
  * Lorsque la température dépasse 57,25°C (chaleur élevée).
* Si aucune chaleur élevée n'est détectée pendant 16 temps de détection continus, le détecteur SDCO transmettra un signal de restauration.
* Si l'alarme a été déclenchée par une condition de chaleur élevée (57,25°C), la température doit descendre en dessous de 49°C pour que le détecteur cesse de déclencher l'alarme.

**Détection du monoxyde de carbone :**

 Le capteur de CO vérifiera le niveau de concentration de CO toutes les 16 secondes, si le niveau de concentration dépasse le seuil de détection, le détecteur SDCO transmettra un signal d'alarme et déclenchera une alarme avec son buzzer intégré.

 Le capteur de CO dispose d'une fonction d'autodiagnostic et vérifiera régulièrement l'état de santé ou l'état du capteur toutes les 12 heures.

 L'alarme sera activée après détection de la concentration de CO selon la durée indiquée dans le tableau suivant : (conforme à la norme EN-50291)

| **Niveau de concentration de CO** | **Temps mis avant de alarmer** |
| --------------------------------- | ------------------------------ |
| 30 +/- 10% ppm                    | N / A                          |
| 50 +/- 10% ppm                    | 60\~90 minutes                 |
| 100 +/- 10% ppm                   | 10\~40 minutes                 |
| 300 +/- 10% ppm                   | Moins de 3 minutes             |

 L'alarme sera activée après la détection de la concentration de CO selon la durée indiquée dans le tableau suivant : (conforme à la norme UL-2034)

| **Niveau de concentration de CO** | **Temps mis avant de alarmer** |                 |
| --------------------------------- | ------------------------------ | --------------- |
| 30                                | +/- 3% ppm                     | N / A           |
| 70                                | +/- 5% ppm                     | N / A           |
| 70                                | +/- 5% ppm                     | 60\~240 minutes |
| 150 +/- 5% ppm                    | 10\~50 minutes                 |                 |
| 400                               | +/- 10 % ppm                   | 4\~15 minutes   |

 Une fois que le niveau de concentration de CO dépasse le seuil et persiste pendant la durée indiquée dans le tableau ci-dessus, le détecteur SDCO transmettra le signal au coordinateur Z-Wave et déclenchera l'alarme avec sa sirène intégrée.

 Si le CO descend en dessous de 30 ppm pendant 10 temps de détection continus, le SDCO transmettra un signal de restauration.

**Détection de température et d'humidité :**

Le capteur de température et d'humidité transmettra régulièrement des signaux de température et d'humidité en fonction du réglage. L'intervalle par défaut est de 30 à 33 minutes.

*
  * Le détecteur SDCO enverra un signal de température lorsque la température change de +/- 2°C.
  * Vous pouvez également appuyer une fois sur le bouton pour transmettre manuellement un signal de température.
* _**Détection IR**_
  * Le détecteur SDCO transmettra un signal au panneau de commande si un mouvement est détecté dans la couverture de détection IR. Le buzzer ne retentira pas et la LED ne clignotera pas. Veuillez vous référer à votre panneau de configuration pour plus de détails.
  * Dans 60 secondes, s'il n'y a plus de détection de mouvement ou d'alerte, l'IR sera restauré et reviendra à un fonctionnement normal.
* _**Test du détecteur SDCO**_

![](<.gitbook/assets/16 (36).png>) ![](<.gitbook/assets/17 (29).png>)

En appuyant sur le bouton du détecteur SDCO, vous pouvez tester si le détecteur SDCO fonctionne normalement.

*
  * Si le détecteur SDCO fonctionne normalement, la LED rouge clignotera une fois suivie d'un bip à 2 tons.
  * Si trois bips bicolores (DO-DI DO-DI DO-DI) sont émis, cela signifie que le capteur de fumée est en panne.
  * Si 5 bips (DO-Bi-Bi-Bi-DO) sont émis, cela signifie que le capteur de chaleur est en panne.
  * Si 7 bips (Bi-Bi-Bi-DO-Bi-Bi-Bi) sont émis, cela signifie que le capteur de CO est en panne.
* _**Silence d'alarme**_
  * Il existe deux manières de mettre manuellement le SDCO en mode Silence d'alarme : en appuyant sur le bouton ou en envoyant**Contrôle scène/sirène ou contrôle marche/arrêt sirène**commande. Quelle que soit la méthode, le SDCO entrera en mode Silence d’alarme. Après la période, un signal de restauration sera envoyé. Veuillez vous référer à la page 8\*\*« Urgence de fumée/Urgence de fumée résolu&#x65;**\_**, Urgence de chaleur résolue et Urgence CO/**\_**&#x55;rgence CO résolue »\*\*pour plus de détails.

![](<.gitbook/assets/18 (35).png>)

**En appuyant sur le bouton :**

* Lorsque le détecteur de fumée déclenche une alarme, appuyer sur le bouton mettra le détecteur de fumée en mode Silence d'alarme pour faire taire l'alarme.

**Envoi de la commande Commande Scène/Sirène ou Commande On/Off Sirène :**

* La commande de contrôle scène/sirène vous permet de programmer différents types d'alarme avec indication de localisation.**Veuillez noter que cette commande NE PEUT PAS être utilisée pour arrêter la sirène et les invites vocales d'une alarme réelle.**
* Pour désactiver la sirène et les invites vocales à l'aide de cette commande, définissez Basic Set : 0x00. Le détecteur SDCO entrera alors en mode Silence d’alarme.
* La commande Siren On/Off Control vous permet de contrôler la sirène d’un détecteur de fumée.**Veuillez noter que cette commande NE PEUT PAS être utilisée pour arrêter la sirène et les invites vocales d'une alarme réelle.**
* Pour désactiver la sirène à l'aide de cette commande, définissez Basic Set : 0x00. Le détecteur SDCO entrera alors en mode Silence d’alarme.
* Pendant la période de silence de l'alarme, la LED rouge clignote une fois par seconde. Le détecteur de fumée continuera à surveiller la concentration de fumée pendant la période de silence de l'alarme :
  1. Une fois la période de silence de l'alarme expirée, si la concentration de fumée descend en dessous du seuil d'alarme, le détecteur de fumée émettra un bip à 2 tons et reviendra à un fonctionnement normal sans déclencher d'alarme.

5

*
  1. Si la concentration de fumée dépasse toujours le seuil d'alarme, le détecteur de fumée recommencera à émettre une alarme.
  2. Si la concentration de fumée continue d'augmenter pendant la période de silence de l'alarme et dépasse un deuxième seuil d'alarme, le détecteur SDCO recommencera à émettre une alarme. Une alarme activée par dépassement du deuxième seuil d'alarme peut être désactivée en appuyant sur le bouton.
* _**Réétalonnage**_

![](<.gitbook/assets/19 (35).png>)

Le détecteur SDCO calibrera son capteur de détecteur de fumée à chaque fois que l'alimentation est appliquée pour garantir une sensibilité optimale à la fumée. Après l'installation, l'état de fonctionnement du détecteur de fumée peut varier après un certain temps, ce qui peut affecter sa fonction de détection de fumée et nécessiter un recalibrage. Il existe deux manières de recalibrer le détecteur de fumée : le calibrage automatique et le calibrage manuel.

**Calibrage automatique :**

* Après avoir été mis sous tension, le détecteur de fumée effectuera un auto-étalonnage après 4 heures.
* Après le premier calibrage automatique, le détecteur de fumée effectuera un calibrage automatique chaque mois. Pendant le processus d'auto-calibrage, le détecteur de fumée n'émettra aucun son.
* Si l'étalonnage automatique échoue, la LED orange clignotera toutes les secondes avec des bips continus.
* Lorsque l'étalonnage automatique du détecteur de fumée échoue, la fonction d'alarme de fumée fonctionnera toujours normalement en utilisant la valeur seuil issue du dernier étalonnage réussi.

**Calibrage manuel :**

* L'étalonnage manuel peut être effectué à tout moment, comme vous le souhaitez :
  1. Appuyez et maintenez le bouton pendant 10 secondes et relâchez lorsque le détecteur de fumée émet 2 bips.
  2. Le détecteur de fumée entrera dans le processus d'étalonnage. L'indicateur LED clignotera toutes les 2 secondes.
  3. Une fois le recalibrage terminé, le détecteur de fumée émettra deux bips rapides pour l'indiquer. La LED s'éteindra.
  4. Si le processus d'étalonnage échoue, le détecteur de fumée émettra une alarme sonore. Veuillez retirer et réinsérer la batterie pour redémarrer le processus.
* _**Identification de l'appareil**_

![](<.gitbook/assets/20 (25).png>)

La fonction est disponible pour vous permettre d'identifier le détecteur SDCO parmi vos appareils en envoyant des commandes Z-Wave à la passerelle. Si l'appareil reçoit le signal avec succès, le voyant de l'appareil commencera à clignoter. Le nombre de cycles de clignotement est programmable à l'aide des commandes Z-Wave Indicator CC. Prière de se référer à "\_**Format de données de classe de commande »**\_pour plus de détails.

* _**Retour aux paramètres d'usine**_

_(Utilisez la réinitialisation d'usine uniquement lorsque le panneau de configuration/passerelle réseau est manquant ou inutilisable)._

* Appuyez et maintenez enfoncé le bouton du détecteur SDCO pendant 20 secondes. Relâchez le bouton lorsque vous entendez 3 bips pour effectuer une réinitialisation d'usine.

_\\_

* La réinitialisation d'usine du SDCO le restaurera aux paramètres d'usine par défaut (exclus du réseau Z-Wave). La passerelle ou le panneau de commande Z-Wave conservera toujours ses paramètres Z-Wave. Veuillez vous référer au manuel de la passerelle ou du panneau de commande pour savoir comment supprimer les paramètres Z-Wave du SDCO.

**Entretien et nettoyage**

Un entretien et un nettoyage réguliers aideront à maintenir votre détecteur SDCO en bon état de fonctionnement.

* Testez le détecteur SDCO chaque semaine pour vérifier que les sons d'alarme et les indicateurs fonctionnent correctement.
* Nettoyez le détecteur SDCO au moins une fois tous les 6 mois.
  * Aspirez doucement la saleté/poussière/petites particules accumulées dans la chambre et les fentes de détection de fumée.
  * Nettoyez le boîtier en le passant soigneusement avec un chiffon humide et séchez-le. Ne mettez pas d’eau à l’intérieur de l’alarme.
  * N'utilisez jamais de produits de nettoyage, de détergents ou de solvants sur le détecteur.
* Évitez de pulvériser un assainisseur d'air, de la laque pour cheveux ou d'autres aérosols à proximité du détecteur SDCO.
* Ne peignez ni ne modifiez le détecteur sous aucun prétexte.

**Expiration**

Le détecteur SDCO a une durée de vie maximale de**10 années**à compter de la date d'installation. Vous devez remplacer le détecteur SDCO immédiatement après 10 ans de service.

Il est recommandé d'écrire la date « Remplacer avant » (10 ans à compter de la date d'installation) au dos du détecteur avant l'installation.

**Installation**

* _**Directive d'installation**_
  * Il est recommandé d'installer l'appareil dans la zone centrale du plafond. Lorsqu'il est monté au plafond, le PIR offre de meilleures performances de détection contre les mouvements horizontaux.
  * La hauteur de montage idéale pour le détecteur SDCO est comprise entre 2,4 mètres et 3 mètres. Un montage à plus de 3 mètres peut affecter les performances de détection.
  * N'installez pas le détecteur dans les endroits suivants :
    * La cuisine – La fumée provenant de la cuisson peut provoquer une alarme indésirable.
    * À proximité d'un ventilateur, d'une lampe fluorescente ou d'un climatiseur – les courants d'air qui en proviennent peuvent affecter la sensibilité du détecteur.
    * Près des poutres du plafond ou au-dessus d'une armoire – l'air stagnant dans ces zones peut affecter la sensibilité du détecteur.
    * Au plus fort d’un «**UN**”type de plafond à ossature.
  * Le détecteur SDCO peut prendre en charge une couverture de détection dans un rayon de 4 mètres.

6

* _**Recommandation d'installation**_
  * **Limites**
    * N’exposez pas le détecteur SDCO à la lumière directe du soleil.
    * Évitez d'installer le détecteur SDCO dans des zones où des appareils tels que des climatiseurs ou des radiateurs peuvent provoquer un changement rapide de température dans la zone de détection.
    * Évitez les gros obstacles dans la zone de détection.
    * Ne pointez pas directement vers des sources de chaleur, par exemple des incendies ou des chaudières, ni au-dessus de radiateurs.
* _**Montage du détecteur SDCO**_

\*\*Étape 1.\*\*Avant de commencer, recherchez le disjoncteur ou la boîte à fusibles.

\*\*Étape 2.\*\*Une fois que vous l'avez trouvé, ouvrez la porte et éteignez l'interrupteur principal.

\*\*Étape 3.\*\*Placez le détecteur SDCO à l'emplacement de montage souhaité et utilisez le test de portée pour vous assurer que le SDCO peut être reçu par le panneau de commande à l'emplacement de montage.

\*\*Étape 4.\*\*Deux connecteurs d'épissure Wago 221 sont fournis. Retirez un connecteur. Tirez le levier vers le haut et insérez le fil blanc.

\*\*Étape 5.\*\*Repoussez le levier vers le bas. Le boîtier transparent vous permet de vérifier si le fil est correctement connecté.**Assurez-vous que le fil est bien maintenu en place avant de continuer.**

\*\*Étape 6.\*\*Répétez les étapes 4 et 5 pour insérer le fil noir. L'insertion des deux fils du même côté (à droite), comme indiqué ci-dessous, des deux connecteurs permet une installation plus facile dans les étapes suivantes.

\*\*Étape 7.\*\*Insérez les fils CA dans les deux connecteurs respectivement, comme indiqué ci-dessous.

_Figure 1. Insérez les fils blanc et noir._

_Figure 2. Vérifiez si les fils_

_sont correctement connectés._

_Figure 3. Insérez les fils CA._

\*\*Étape 8.\*\*Le détecteur SDCO dispose d'un support de montage pour une installation au plafond. Le support offre une flexibilité bidirectionnelle.

\*\*Étape 9.\*\*Utilisez les 4 trous du support comme gabarit pour percer des trous et insérer des chevilles murales si nécessaire.

\*\*Étape 10.\*\*L'utilisateur peut faire pivoter le support de montage dans le sens des aiguilles d'une montre ou dans le sens inverse pour verrouiller le crochet. Assurez-vous que les chevilles murales affleurent la surface de montage.

\*\*Étape 11.\*\*Une fois la position satisfaisante, vissez le support de montage au plafond.

\*\*Étape 12.\*\*Essuyez soigneusement la poussière, sinon cela peut salir le capteur et l'empêcher de fonctionner correctement en cas d'urgence.

\*\*Étape 13.\*\*Utilisez un tournevis cruciforme pour retirer la vis de fixation du compartiment à piles. Retirez le couvercle du compartiment à piles et fixez le câble à la carte PCB du détecteur SDCO. La conception infaillible offre une procédure d’installation facile.

\*\*Étape 14.\*\*Placez les deux connecteurs d'épissure dans l'espace à côté de la batterie rechargeable.

\*\*Étape 15.\*\*Remettez le couvercle du compartiment à piles à sa place et serrez la vis de fixation. Le trou pré-percé sur le couvercle améliore sa flexibilité.

\*\*Étape 16.\*\*Le SDCO comporte trois encoches sur son capot arrière (comme illustré ci-dessous) pour accrocher l'appareil au support de montage.

\*\*Étape 17.\*\*Tenez le détecteur SDCO avec beaucoup de précaution et accrochez-le au support de montage.

\*\*Étape 18.\*\*Faites pivoter le détecteur SDCO dans le sens des aiguilles d’une montre pour verrouiller le crochet. L'installation est maintenant terminée.

\*\*Étape 19.\*\*Allumez l’interrupteur d’alimentation principal pour une opération ultérieure.

**Informations sur la vague Z**

\*\*Type d'appareil:\*\*Alarme de fumée de notification de capteur

\*\*Type de rôle :\*\*Toujours sur esclave (AOS)

\*\*Identifiant du fabricant :\*\*0x018E

\*\*ID du type de produit :\*\*0x0003

\*\*Identifiant du produit :\*\*0x0115

\*\*Groupe d'associations maximum :\*\*3

**Classe de commande prise en charge :**

| **Classe de commande**                    | **Version** | **Classe de sécurité requise**             |
| ----------------------------------------- | ----------- | ------------------------------------------ |
|                                           |             |                                            |
| Association                               | 2           | Classe de sécurité accordée la plus élevée |
|                                           |             |                                            |
| Informations sur le groupe d'associations | 3           | Classe de sécurité accordée la plus élevée |
|                                           |             |                                            |
| Basique                                   | 2           | Classe de sécurité accordée la plus élevée |
|                                           |             |                                            |
| Batterie                                  | 1           | Classe de sécurité accordée la plus élevée |
|                                           |             |                                            |
| Capteur multiniveau                       | 11          | Classe de sécurité accordée la plus élevée |
|                                           |             |                                            |
| Activation de la scène                    | 1           | Classe de sécurité accordée la plus élevée |
|                                           |             |                                            |
|                                           |             | 7                                          |

| Notification                                | 8 | Classe de sécurité accordée la plus élevée |
| ------------------------------------------- | - | ------------------------------------------ |
|                                             |   |                                            |
| Réinitialisation de l'appareil localement   | 1 | Classe de sécurité accordée la plus élevée |
|                                             |   |                                            |
| Métadonnées de mise à jour du micrologiciel | 5 | Classe de sécurité accordée la plus élevée |
|                                             |   |                                            |
| Spécifique à la fabrication                 | 2 | Classe de sécurité accordée la plus élevée |
|                                             |   |                                            |
| Multicanal                                  | 4 | Classe de sécurité accordée la plus élevée |
|                                             |   |                                            |
| Association multicanal                      | 3 | Classe de sécurité accordée la plus élevée |
|                                             |   |                                            |
| Niveau d'énergie                            | 1 | Classe de sécurité accordée la plus élevée |
|                                             |   |                                            |
| Changer de binaire                          | 2 | Classe de sécurité accordée la plus élevée |
|                                             |   |                                            |
| Configuration                               | 1 | Classe de sécurité accordée la plus élevée |
|                                             |   |                                            |
| État de fonctionnement du thermostat        | 2 | Classe de sécurité accordée la plus élevée |
|                                             |   |                                            |
| Version                                     | 3 | Classe de sécurité accordée la plus élevée |
|                                             |   |                                            |
| Service de transport                        | 2 | Aucun                                      |
|                                             |   |                                            |
| Informations sur Z-Wave Plus                | 2 | Aucun                                      |
|                                             |   |                                            |
| Sécurité                                    | 1 | Aucun                                      |
|                                             |   |                                            |
| Sécurité 2                                  | 1 | Aucun                                      |
|                                             |   |                                            |
| Surveillance                                | 1 | Aucun                                      |
|                                             |   |                                            |

* _**Groupes de Z-Wave (classe de commande d'association version 2)**_

Groupe 1 pour « LifeLine » : (nœud max : 5)

Batterie CC (COMMANDE\_CLASSE\_BATTERIE)

SensorMutilevel CC, V11 (COMMANDE\_CLASSE\_CAPTEUR\_MULTINIVEAU)

Notification CC,V8 (COMMANDE\_CLASSE\_NOTIFICATION)

CC de base (COMMANDE\_CLASSE\_BASIQUE)

Réinitialisation du périphérique localement CC (COMMANDE\_CLASSE\_APPAREIL\_RÉINITIALISER\_LOCALEMENT)

Groupe 2 pour « Sensor Basic set » : (nœud max : 5)

CC de base (COMMANDE\_CLASSE\_BASIQUE)

Lorsque le détecteur de fumée est actif, il enverra un jeu de base (0xFF) dans le groupe 2.

Lorsque le détecteur de fumée est restauré, il enverra le réglage de base (0x00) dans le groupe 2.

Groupe 3 pour « Scene set » : (nœud max : 5)

Activation de scène CC (COMMANDE\_CLASSE\_SCÈNE\_ACTIVATION)

Une fois le groupe 3 ajouté, il enverra une commande d'activation de scène en cas d'alarme SC, HD ou CO.

Une fois le groupe 3 ajouté, il enverra une commande d'activation de scène lorsque SC, HD ou CO sera restauré.

Prière de se référer à\_Tableau 2\_Siren Control, il enverra 00 00 lorsque le détecteur de fumée sera restauré.

* _**Format de données de classe de commande**_
  * **Panne/Rétablissement CA :\[COMMANDE\_CLASSE\_NOTIFICATION]\[NOTIFICATION\_RAPPORT]**
* Lorsqu'une panne de courant alternatif est détectée, le SDCO enverra un signal de panne de courant alternatif au panneau de commande. Lorsque l'alimentation secteur est rétablie, le SDCO enverra un signal de restauration au panneau de commande.

|  | Panne de courant alternatif : | 00 00 00FF 08 02 00 00 |
| - | ----------------------------- | ---------------------- |
|  | Restauration CA :             | 00 00 00FF 08 03 00 00 |

* **Batterie:\[COMMANDE\_CLASSE\_BATTERIE]\[BATTERIE\_RAPPORT]**
  * 0x64 --- Batterie pleine à 100 %
  * 0x5A --- 90% batterie
  * 0x50 --- 80% Batterie
  * 0x46 --- 70 % de batterie
  * 0x3C --- 60 % de batterie
  * 0x32 --- 50 % de batterie
  * 0x28 --- 40 % de batterie
  * 0x1E --- 30 % de batterie
  * 0x14 --- 20 % de batterie faible
  * 0xFF --- Batterie morte (coupée)
  * Coupure --- L'appareil cessera de fonctionner et les LED rouge et orange clignoteront toutes les 4 secondes.
  * Si l'interrupteur de la batterie est réglé sur OFF, le SDCO enverra 00 % pour avertir l'utilisateur. Veuillez noter que lorsqu'elle est réglée sur OFF, la batterie ne sera pas chargée lorsque l'alimentation secteur est connectée et elle ne servira pas non plus de source d'alimentation de secours en cas d'absence d'alimentation secteur.

8

*
  * Lorsque l'alimentation secteur est appliquée, la batterie rechargeable se chargera en même temps et le SDCO signalera son pourcentage de batterie à la passerelle/au panneau de commande respectivement à 20 %, 30 %, 40 %, 50 %, 60 %, 70 %. , 80 %, 90 % et 100 %.
  * Lorsque l'alimentation secteur est coupée ou qu'une panne de courant se produit, le SDCO utilise sa batterie rechargeable intégrée et indique son pourcentage de batterie. Une fois l'alimentation secteur rétablie, le SDCO signalera le pourcentage de batterie détecté. Lorsque la tension de la batterie détectée est de 4,3 V ou plus, le SDCO indiquera son pourcentage de batterie à 60 % et commencera à charger la batterie. Lorsque la tension de la batterie détectée est inférieure à 4,3 V, le SDCO indiquera respectivement son pourcentage de batterie et commencera à charger la batterie.
* **Rapport de température/humidité :\[COMMANDE\_CLASSE\_CAPTEUR\_MULTINIVEAUX]\[CAPTEUR\_MULTINIVEAUX\_RAPPORT]**
  * L'utilisateur peut appuyer une fois sur le bouton pour envoyer des informations de température et d'humidité au panneau de commande.
* Si signal de température 01 42**08CC**est transmis:

**08CC**peut être considéré comme 0x**08CC**en nombre hexadécimal. Vous pouvez convertir l'hexadécimal en décimal et diviser par 100 pour vérifier les données de température (en Celsius).

0x08CC=2252=25,52℃.

*
  * Si signal humidité 05 02**00 nid**est transmis:

**003C**peut être considéré comme 0x**003C**en nombre hexadécimal. Vous pouvez convertir l'hexadécimal en décimal pour vérifier le niveau d'humidité (en pourcentage).

003C=0x003C=60%

* **Test du détecteur de fumée/Test du détecteur de fumée désactivé : \[COMMANDE\_CLASSE\_NOTIFICATION]\[NOTIFICATION\_RAPPORT]**
  * L'utilisateur peut appuyer une fois sur le bouton pour envoyer des signaux de test de détecteur de fumée et de test de détecteur de fumée désactivé au panneau de commande.
  * Test détecteur de fumée : 00 00 00 FF 01 03 00
  * Test avertisseur de fumée désactivé : 00 00 00 FF 01 00 01 03
  * 01=type d'alarme ; 03=test détecteur de fumée
* **Urgence de fumée/Urgence de fumée résolue :\[COMMANDE\_CLASSE\_NOTIFICATION]\[NOTIFICATION\_RAPPORT]**

 Détecteur de fumée : 00 00 00 FF 01 01 0B 77 06 00 42 61 73 65 6D 65 6E 74

Remarque : 0B 77 06 00 42 61 73 65 6D 65 6E 74 correspond à l'emplacement "Sous-sol".

* Un détecteur de fumée sera activé une fois que la concentration de fumée dépasse le seuil de détection, ou bien activé manuellement en envoyant des commandes, le SDCO peut être réduit au silence et passer en mode Silence d'alarme. Prière de se référer à "\_**Silence d'alarme**» pour plus de détails.\_Le SDCO enverra un rapport de silence d'alarme dans les trois conditions suivantes :

|  Lorsque la concentration de fumée descend en dessous du seuil d'alarme, le SDCO enverra :            | 00 00 00FF 01 06 01 01 |   |   |   |   |
| ------------------------------------------------------------------------------------------------------ | ---------------------- | - | - | - | - |
|  Lorsque l'utilisateur appuie sur le bouton pour arrêter l'alarme, le SDCO enverra :                  |                        |   |   |   |   |
| 00 00 00FF 01 06 01 02                                                                                 |                        |   |   |   |   |
|  Lorsque l'utilisateur envoie une commande d'arrêt de sirène pour arrêter l'alarme, le SDCO enverra : |                        |   |   |   |   |
| 00 00 00FF 01 06 01 03                                                                                 |                        |   |   |   |   |
| Prière de se référer à "**Commande de contrôle marche/arrêt de la sirène**» pour plus de détails.      |                        |   |   |   |   |

*
  * Remarque : Si plusieurs alarmes sont activées, les événements de silence d'alarme seront envoyés respectivement.
  * Une fois le SDCO réduit au silence, si aucune fumée n'est détectée pendant 20 temps de détection continus, le SDCO transmettra un signal de restauration : 00 00 00 FF 01 00 01 01.
* **Urgence de chaleur/Urgence de chaleur résolue :\[COMMANDE\_CLASSE\_NOTIFICATION]\[NOTIFICATION\_RAPPORT]**

|  Alarme de chaleur : | 00 00 00FF  | 04 01 | 0Б штш 06 00 42 61 штз 65 ШД 65 ШТЕ штч                       |
| --------------------- | ----------- | ----- | ------------------------------------------------------------- |
| Note:                 | 0B 77 06 00 | 42 61 | 73 65 6D 65 6E 74 est lorsque l'emplacement est « Sous-sol ». |

* Une alarme de chaleur sera activée une fois que le SDCO aura atteint la condition de taux de montée ou de chaleur élevée, ou bien activée manuellement en envoyant des commandes, le SDCO peut être réduit au silence et passer en mode de silence d'alarme. Prière de se référer à "\_**Silence d'alarme**» pour plus de détails.\_Le SDCO enverra un rapport de silence d'alarme dans les trois conditions suivantes :

|  Lorsque la température descend en dessous du seuil d'alarme, le SDCO enverra :                       | 00 00 00FF 04 09 01 01 |   |   |   |   |
| ------------------------------------------------------------------------------------------------------ | ---------------------- | - | - | - | - |
|  Lorsque l'utilisateur appuie sur le bouton pour arrêter l'alarme, le SDCO enverra :                  |                        |   |   |   |   |
| 00 00 00FF 04 09 01 02                                                                                 |                        |   |   |   |   |
|  Lorsque l'utilisateur envoie une commande d'arrêt de sirène pour arrêter l'alarme, le SDCO enverra : |                        |   |   |   |   |
| 00 00 00FF 01 06 01 03                                                                                 |                        |   |   |   |   |
| Prière de se référer à "**Commande de contrôle marche/arrêt de la sirène**» pour plus de détails.      |                        |   |   |   |   |

*
  * Remarque : Si plusieurs alarmes sont activées, les événements de silence d'alarme seront envoyés respectivement.
  * Une fois le SDCO désactivé, si aucune chaleur élevée n'est détectée pendant 16 temps de détection continus, le SDCO transmettra un signal de restauration : 00 00 00 FF 04 00 01 01.
* **Urgence CO/Urgence CO résolue :\[COMMANDE\_CLASSE\_NOTIFICATION]\[NOTIFICATION\_RAPPORT]**

 Alarme CO : 00 00 00 FF 02 01 0B 77 06 00 42 61 73 65 6D 65 6E 74

Remarque : 0B 77 06 00 42 61 73 65 6D 65 6E 74 correspond à l'emplacement "Sous-sol".

* Une alarme de CO sera activée une fois que la concentration de CO dépasse le seuil de détection, ou bien activée manuellement par l'envoi de commandes, le SDCO peut être réduit au silence et passer en mode Silence d'alarme. Prière de se référer à "\_**Silence d'alarme**» pour plus de détails.\_Le SDCO enverra un rapport de silence d'alarme dans les trois conditions suivantes :

|                                                                                    | Lorsque la concentration de CO descend en dessous de 30 ppm, le SDCO enverra : | 00 00 00FF 02 06 01 01 |   |   |   |   |
| ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ | ---------------------- | - | - | - | - |
|                                                                                    |                                                                                |                        |   |   |   |   |
| Lorsque l'utilisateur appuie sur le bouton pour arrêter l'alarme, le SDCO enverra : | 00 00 00FF 02 06 01 02                                                         |                        |   |   |   |   |
|                                                                                     |                                                                                |                        |   |   |   |   |

**Veuillez noter qu'une alarme activée par dépassement du deuxième seuil d'alarme peut être désactivée en appuyant sur le bouton.**

|  Lorsque l'utilisateur envoie une commande d'arrêt de sirène pour arrêter l'alarme, le SDCO enverra : | 00 00 00FF 01 06 01 03 |   |   |   |
| ------------------------------------------------------------------------------------------------------ | ---------------------- | - | - | - |
|                                                                                                        |                        |   |   |   |

*
  * Remarque : Si plusieurs alarmes sont activées, les événements de silence d'alarme seront envoyés respectivement.
  * Une fois le SDCO réduit au silence, si le CO descend en dessous de 30 ppm pendant 10 temps de détection continus, le SDCO transmettra un signal de restauration : 00 00 00 FF 02 00 01 01.
* **Emplacement:**
  * Lorsqu'un détecteur de fumée, une alarme de chaleur ou une alarme de CO est déclenché, il enverra une notification avec le nom de l'emplacement. Pour les modèles connectés en série, l'emplacement préprogrammé sera également transmis.
  * Si un avertisseur de fumée se déclenche au sous-sol, 00 00 00 FF 01 01**0Б штш 06 00 42 61 штз 65 ШД 65 ШТЕ штч**sera envoyé, comme indiqué dans le tableau 1 ci-dessous

_**Tableau 1**_

| 1 | V1 | Type d'alarme   | 0x00 | Pas mis en œuvre |
| - | -- | --------------- | ---- | ---------------- |
|   |    |                 |      |                  |
| 2 | V1 | Niveau d'alarme | 0x00 | Pas mis en œuvre |
|   |    |                 |      |                  |

9

| 3  | Réservé                             | 0x00             | Champ réservé                                       |
| -- | ----------------------------------- | ---------------- | --------------------------------------------------- |
|    |                                     |                  |                                                     |
| 4  | Statut des notifications            | 0xFF             | Le rapport non sollicité est activé                 |
|    |                                     |                  |                                                     |
| 5  | Type de notification                | 0x01             | Détecteur de fumé                                   |
|    |                                     |                  |                                                     |
| 6  | Événement                           | 0x01             | Fumée détectée                                      |
|    |                                     |                  |                                                     |
| 7  | Longueur des paramètres d'événement | 0x0B             | Longueur du paramètre d'événement = 11              |
|    |                                     |                  |                                                     |
| 8  | Événement Parm 1                    | 0balayage        | Nom du nœud et identifiant CC d'emplacement         |
|    |                                     |                  |                                                     |
| 9  | Événement Parm 2                    | 0x06             | ID de commande du rapport sur l'emplacement du nœud |
|    |                                     |                  |                                                     |
| 10 | Événement Parm 3                    | 0x00             | Parm de commande : Char = ASCII                     |
|    |                                     |                  |                                                     |
| 11 | Événement Parm 4                    | 0x42             | Cmd Parm : emplacement du nœud Car 1 = B            |
|    |                                     |                  |                                                     |
| 12 | Événement Parm 5                    | 0x61             | Cmd Parm : emplacement du nœud Char 2 = a           |
|    |                                     |                  |                                                     |
| 13 | Événement Parm 6                    | 0 comme balayage | Cmd Parm : emplacement du nœud Char 3 = s           |
|    |                                     |                  |                                                     |
| 14 | Événement Parm 7                    | 0x65             | Cmd Parm : emplacement du nœud Char 4 = e           |
|    |                                     |                  |                                                     |
| 15 | Événement Parm 8                    | 0x6D             | Cmd Parm : emplacement du nœud Char 5 = m           |
|    |                                     |                  |                                                     |
| 16 | Événement Parm 9                    | 0x65             | Cmd Parm : emplacement du nœud Char 6 = e           |
|    |                                     |                  |                                                     |
| 17 | Événement Parm 10                   | 0x6E             | Cmd Parm : emplacement du nœud Car 7 = n            |
|    |                                     |                  |                                                     |
| 18 | Événement Parm 11                   | 0x74             | Cmd Parm : emplacement du nœud Car 8 = t            |
|    |                                     |                  |                                                     |

* **Rapport d'ouverture/fermeture de sabotage :\[COMMANDE\_CLASSE\_NOTIFICATION]\[NOTIFICATION\_RAPPORT]**
  * Le SDCO est protégé par un interrupteur anti-sabotage qui est comprimé lorsque le SDCO est accroché au support de montage. Lorsque le SDCO est retiré du support de montage, le commutateur d'autoprotection sera activé et le SDCO enverra un signal d'autoprotection au panneau de commande du système pour rappeler à l'utilisateur cette condition.
  * Autoprotection :00 00 00 FF 07 03 00 00
  * Une fois le SDCO accroché au support de montage, il enverra un signal de fermeture inviolable au panneau de commande.
* **Capteur PIR**
  *
    * Le SDCO transmettra un signal au panneau de commande si un mouvement est détecté dans la couverture de détection IR.
  * PIR Actif : 00 00 00 FF 07 07 0B 77 06 00 42 61 73 65 6D 65 6E 74
  * Remarque : 00 00 00 FF 07 07 0B 77 06 00 42 61 73 65 6D 65 6E 74 correspond à l'emplacement « Sous-sol ».
  * Restauration PIR : 00 00 00 FF 07 00 01 07
* **Contrôle scène/sirène :\[COMMANDE\_CLASSE\_SCÈNE\_ACTIVATION]\[SCÈNE\_ACTIVATION\_SET] (pour les modèles connectés en série) :**
  * ID de scène : type d'alarme (Tableau 2)
  * Durée de gradation : 0x00\~0x14

_**Tableau 2**_

| Btkh\~7 | Bit 4    | Bit 3        | Bit 2     | Bit 1     | Bit 0     |   |
| ------- | -------- | ------------ | --------- | --------- | --------- | - |
|         |          |              |           |           |           |   |
|         |          |              |           |           |           |   |
|         |          |              |           |           | Alarme SD |   |
| 0       | Insectes | Alarme d'eau | Alarme CO | Alarme HD |           |   |
|         |          |              |           |           |           |   |

* Nom de l'emplacement /Bit4\~0/Num, comme indiqué dans le tableau 3 ci-dessous

_**Tableau 3**_

*
  * Invite en anglais

| Nombre (hexadécimal) | Nom de la localisation | Nombre (hexadécimal) | Nom de la localisation  |
| -------------------- | ---------------------- | -------------------- | ----------------------- |
|                      |                        |                      |                         |
| 0                    | Sous-sol               | B                    | Garderie                |
| 1                    | Salle                  | C                    | Toilettes               |
| 2                    | Bureau                 | D                    | Salle technique         |
| 3                    | Chambre principale     | ET                   | Garde-robe              |
| 4                    | Chambre à coucher      | F                    | Salon mansardé          |
| 5                    | Chambre d'amis         | 10                   | Salon du sous-sol       |
| 6                    | Cuisine                | 11                   | Escalier                |
| 7                    | Salle à manger         | 12                   | Garage                  |
| 8                    | Salon                  | 13                   | Appartement en location |
| 9                    | Lessive                | 14                   | Aucun emplacement       |
| UN                   | Grenier                |                      |                         |

* Invite norvégienne

Nombre (hexadécimal)

Nom de la localisation

Nombre (hexadécimal)

10

Nom de la localisation

| 0  | Salon              | B  | Pièce de stockage |
| -- | ------------------ | -- | ----------------- |
| 1  | Cuisine            | C  | Toilettes         |
| 2  | Couloir            | D  | Salle technique   |
| 3  | Chambre principale | ET | Garde-robe        |
| 4  | Chambre d'enfants  | F  | À l'étage         |
| 5  | Chambre à coucher  | 10 | En bas            |
| 6  | À manger           | 11 | Escalier          |
| 7  | Lessive            | 12 | Garage            |
| 8  | Grenier            | 13 | Unité de location |
| 9  | Bureau             | 14 | Le bâtiment       |
| UN | Sous-sol           |    |                   |

*
  *
    * Pour activer le carillon de porte, définissez l'ID de scène : 0x00 et la durée de gradation : 0xF1.
    * Pour arrêter la sirène et les invites vocales générées par cette commande, définissez l'ID de scène : 0x00 et la durée de gradation : 0x00.**Veuillez noter que cette commande NE PEUT PAS être utilisée pour arrêter la sirène et les invites vocales d'une alarme réelle.**
    * Pour arrêter la sirène et les invites vocales d'une alarme réelle, définissez l'ID de scène : 0xFF et la durée de gradation : 0x00.
* **Commande marche/arrêt de la sirène :\[COMMANDE\_CLASSE\_BASIQUE]\[BASIQUE\_ENSEMBLE]**
  *
    * La sirène du SDCO peut être contrôlée à l'aide des commandes Basic Set On/Off (pour détecteur de fumée uniquement, sans indication de localisation).
    * Pour allumer la sirène à l'aide de cette commande, définissez Basic Set : 0xFF. Le modèle sonore de la sirène est le même que celui d'un détecteur de fumée.
    * Pour désactiver la sirène à l'aide de cette commande, définissez Basic Set : 0x00.\*\*Veuillez noter que cette commande NE PEUT PAS être utilisée pour arrêter la sirène d'une alarme réelle.\*\*Le SDCO entrera en mode Silence d'alarme et enverra un signal de rétablissement d'alarme après la période.
  * **Indicateur**Contrôle\*\*:\[COMMANDE\_CLASSE\_INDICATEUR]\[INDICATEUR\_ENSEMBLE]\*\*
    * L'indicateur LED du SDCO peut être contrôlé à l'aide des commandes Indicator Set.
    * Les commandes suivantes peuvent être utilisées pour définir la commande d'indicateur :

|   | 7 |         |   | 6                                                                        | 5                               | 4               | 3 |   | 2 |   | 1 | 0 |
| - | - | ------- | - | ------------------------------------------------------------------------ | ------------------------------- | --------------- | - | - | - | - | - | - |
|   |   |         |   |                                                                          |                                 |                 |   |   |   |   |   |   |
|   |   |         |   | Classe de commande = COMMANDE\_CLASSE\_INDICATEUR                        |                                 |                 |   |   |   |   |   |   |
|   |   |         |   |                                                                          |                                 |                 |   |   |   |   |   |   |
|   |   |         |   |                                                                          | Commande = INDICATEUR\_ENSEMBLE |                 |   |   |   |   |   |   |
|   |   |         |   |                                                                          |                                 |                 |   |   |   |   |   |   |
|   |   |         |   | Valeur de l'indicateur 0 (ID de l'indicateur 0=00, ID de propriété 0=01) |                                 |                 |   |   |   |   |   |   |
|   |   |         |   |                                                                          |                                 |                 |   |   |   |   |   |   |
|   |   | Réservé |   |                                                                          | Nombre d'objets d'indicateur    |                 |   |   |   |   |   |   |
|   |   |         |   |                                                                          |                                 |                 |   |   |   |   |   |   |
|   |   |         |   |                                                                          |                                 | ID indicateur 1 |   |   |   |   |   |   |

ID de propriété 1

Valeur 1

* Indicateur activé (0xFF) --- fonction d'indicateur activée
* Indicateur désactivé (0x00) --- fonction indicateur désactivée
* Nombre d'objets d'indicateur (0x01) --- pour contrôler l'ID d'indicateur LED 1
* ID de l'indicateur (0x43) --- indication du bouton

|   | ID de l'indicateur |   |   | Description         |   |                                                    | Apparence et utilisation |   |   |
| - | ------------------ | - | - | ------------------- | - | -------------------------------------------------- | ------------------------ | - | - |
|   |                    |   |   |                     |   |                                                    |                          |   |   |
|   |                    |   |   |                     |   |                                                    |                          |   |   |
|   | 0x43               |   |   | BOUTON1\_INDICATION |   | Utilisez pour attirer l’attention sur le bouton 1. |                          |   |   |

* ID de l'indicateur (0x44) --- redémarrage du MCU

|                                                             |   | ID de l'indicateur |   |   | Description         |                        |                                                   | Apparence et utilisation |                                                                |                        |   |   |   |
| ----------------------------------------------------------- | - | ------------------ | - | - | ------------------- | ---------------------- | ------------------------------------------------- | ------------------------ | -------------------------------------------------------------- | ---------------------- | - | - | - |
|                                                             |   |                    |   |   |                     |                        |                                                   |                          |                                                                |                        |   |   |   |
|                                                             |   |                    |   |   |                     |                        |                                                   |                          |                                                                |                        |   |   |   |
|                                                             |   | 0x44               |   |   | BOUTON2\_INDICATION |                        | Utiliser pour attirer l'attention sur le bouton 2 |                          |                                                                |                        |   |   |   |
|  ID de propriété (0x00-0xFE) --- LED allumée\_temps libres |   |                    |   |   |                     |                        |                                                   |                          |                                                                |                        |   |   |   |
|                                                             |   | Valeur             |   |   |                     | Description générale   |                                                   |                          |                                                                | Utilisation spécifique |   |   |   |
|                                                             |   | 0x04               |   |   |                     | Sur\_Désactivé\_Cycles | Nombre de activés\_Désactivé\_Période à courir    |                          |                                                                |                        |   |   |   |
|                                                             |   |                    |   |   |                     |                        |                                                   |                          | 0x00 – 0xFE = 0 à 254 fois                                     |                        |   |   |   |
|                                                             |   |                    |   |   |                     |                        |                                                   |                          | 0xFF = Exécuter jusqu'à ce qu'il soit arrêté par On\_Désactivé |                        |   |   |   |
|                                                             |   |                    |   |   |                     |                        |                                                   |                          |                                                                |                        |   |   |   |

 Si vous souhaitez que le SDCO clignote 5 fois pour indiquer son emplacement, envoyez : 0xFF 01 43 04 05

 Si vous souhaitez que le SDCO cesse de clignoter une fois que vous connaissez son emplacement, envoyez : 0x00 01 43 04 05  Pour plus de détails, veuillez vous référer à «_**Spécification de classe de commande d'application Z-Wave SDS-13781-1**_”.

**Configurations :\[COMMANDE\_CLASSE\_CONFIGURATION]\[CONFIGURATION\_ENSEMBLE]**

 Numéro de paramètre : 0x01\~0x0A

 Taille : 0x01

 Réservé : 0x00

 Par défaut : 0x00

 Valeur de configuration : 0xXX

| Numéro de paramètre | Valeur de configuration |
| ------------------- | ----------------------- |
|                     |                         |
| 0x01, sensibilité   | 0x01~~0x08 (0~~70),     |
|                     | par défaut : 0x04       |

0x02, période de vérification

0x00~~0x96 (0~~150 secondes),

11

|                                        | par défaut 0x00                        |
| -------------------------------------- | -------------------------------------- |
|                                        |                                        |
| 0x03, version du matériel SD           | 0/1 (0 :ancien, 1 :nouveau) toujours 1 |
|                                        |                                        |
| 0x04, seuil de température             | 4~~50 (2~~25 degrés),                  |
|                                        | par défaut : 4                         |
|                                        |                                        |
| 0x05, heure du rapport automatique     | 0\~240 minutes                         |
|                                        | par défaut : 30                        |
|                                        |                                        |
| 0x06, emplacement                      | 0\~20                                  |
| (prière de se référer à\_Tableau 3\_)  |                                        |
|                                        |                                        |
| 0x07, ajuster la température           | +127\~-128                             |
|                                        | (0,1 degré pour chaque valeur)         |
|                                        |                                        |
| 0x08, ajuster l'humidité               | +127\~-128                             |
|                                        | (1% pour chaque valeur)                |
|                                        |                                        |
| 0x09, Défaut matériel                  | 0x00\~0xFF                             |
| (prière de se référer à\_Tableau 4\_   |                                        |
| défaut matériel répertorié ci-dessous) |                                        |
|                                        |                                        |
| 0x0A, répétition temporaire            | 0\~7                                   |
| (prière de se référer à\_Tableau 5\_)  |                                        |
|                                        |                                        |
| 0x0B, Langue                           | 01\~05                                 |
|                                        | 01 : anglais                           |
|                                        | 02 : Norvégien (par défaut)            |
|                                        | 03 : Suédois                           |
|                                        | 04 : finnois                           |
|                                        | 05 : Danois                            |
|                                        |                                        |

\_**Tableau 4**\_0x09 (défaut matériel)

| Ça arrive                                                                                | Bit6 | Btkh          |        |                      | Bit4          | je l'ai acheté                                       | Bêta       | Bit1          | Bit0       |   |
| ---------------------------------------------------------------------------------------- | ---- | ------------- | ------ | -------------------- | ------------- | ---------------------------------------------------- | ---------- | ------------- | ---------- | - |
|                                                                                          |      |               |        |                      |               |                                                      |            |               |            |   |
| X                                                                                        | X    | CA            |        | Logiciel de batterie | Altérer       | CO                                                   | HD         | Dakota du Sud |            |   |
|                                                                                          |      | 0 : Restaurer |        |                      | 0 : Activé    | 1 : Ouvrir                                           | 1 : cassé  | 1 : cassé     | 1 : cassé  |   |
|                                                                                          |      | 1 : Échec     |        |                      | 1 : Désactivé | 0 : Fermer                                           | 0 : normal | 0 : normal    | 0 : normal |   |
|                                                                                          |      |               |        |                      |               |                                                      |            |               |            |   |
|  SD cassé : si Bit0=1, il enverra une commande de notification « 00 00 00 FF 01 FE 00 » |      |               |        |                      |               |                                                      |            |               |            |   |
|  HD cassé : si Bit1=1, il enverra une commande de notification « 00 00 00 FF 04 FE 00 » |      |               |        |                      |               |                                                      |            |               |            |   |
|  CO cassé : si Bit2=1, il enverra une commande de notification « 00 00 00 FF 02 FE 00 » |      |               |        |                      |               |                                                      |            |               |            |   |
| \_**Tableau 5**\_0x10 (Répétition Temporaire)                                           |      |               |        |                      |               |                                                      |            |               |            |   |
|                                                                                          |      |               | Valeur |                      |               | Durée                                                |            |               |            |   |
|                                                                                          |      |               |        |                      |               |                                                      |            |               |            |   |
|                                                                                          |      |               | 0      |                      |               | Désactiver (la minuterie sera immédiatement arrêtée) |            |               |            |   |
|                                                                                          |      |               |        |                      |               |                                                      |            |               |            |   |
|                                                                                          |      |               | 1      |                      |               |                                                      | 5 minutes  |               |            |   |
|                                                                                          |      |               |        |                      |               |                                                      |            |               |            |   |
|                                                                                          |      |               | 2      |                      |               |                                                      | 30 minutes |               |            |   |
|                                                                                          |      |               |        |                      |               |                                                      |            |               |            |   |
|                                                                                          |      |               | 3      |                      |               |                                                      | 60 minutes |               |            |   |
|                                                                                          |      |               |        |                      |               |                                                      |            |               |            |   |
|                                                                                          |      |               | 4      |                      |               |                                                      | 8 heures   |               |            |   |
|                                                                                          |      |               |        |                      |               |                                                      |            |               |            |   |
|                                                                                          |      |               | 5      |                      |               |                                                      | 12 heures  |               |            |   |
|                                                                                          |      |               |        |                      |               |                                                      |            |               |            |   |
|                                                                                          |      |               | 6      |                      |               |                                                      | 24 heures  |               |            |   |
|                                                                                          |      |               |        |                      |               |                                                      |            |               |            |   |
|                                                                                          |      |               | 7      |                      |               |                                                      | 36 heures  |               |            |   |
|                                                                                          |      |               |        |                      |               |                                                      |            |               |            |   |

* **Retour aux paramètres d'usine**

Si l'appareil est appris et que le bouton de test est enfoncé et maintenu pendant 20 secondes avec 3 bips pour la réinitialisation d'usine, il enverra

\[COMMANDE\_CLASSE\_APPAREIL\_RÉINITIALISER\_LOCALEMENT]\[APPAREIL\_RÉINITIALISER\_LOCALEMENT\_NOTIFICATION]

 L'appareil sera automatiquement exclu pour la nouvelle version de PC Controller.

12
