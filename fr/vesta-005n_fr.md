# 🇫🇷 VESTA-005N

**SRV-23B**

## **Sirène intérieure sur prise secteur**

### **Introduction**

SRV-23B est une sirène intérieure et un carillon alimenté par une prise secteur avec batterie de secours. Avec le haut-parleur intégré, SRV-23B est capable d'émettre le son du carillon, les bips d'entrée/de sortie, de déclencher une alarme et de lire des messages vocaux pour informer les utilisateurs de l'état actuel du système.

### **Identification**

![](<.gitbook/assets/0 (20).jpeg>)

1. **Bouton de test/Voyant LED**\
   **-** Appuyez une fois pour envoyer un test/code d'apprentissage.\
   \- La LED clignote une fois : le bouton est enfoncé.\
   \- La LED clignote en continu : la sirène est en alarme.\
   \- La LED reste allumée : la sirène est en mode apprentissage.
2. **Haut-parleur**



### **Caractéristiques**

#### **- Activation de l'alarme**

Lorsqu'une alarme est déclenchée, la sirène et le voyant fonctionneront en continu . Si une temporisation est programmée dans la centrale d'alarme, la sirène sera activée en fonction de la durée programmée. Si le système d'alarme n'a pas de temporisation, la sirène sera activée pendant 15 minutes.\
Si la centrale a déjà déclenchée, au désarmement, la sirène diffusera le message vocal suivant :\
&#xNAN;_"Vous avez une alarme en mémoire."_

#### **- Message vocaux**

La sirène émet différentes indications audio et messages vocaux en fonction de l'état du système de sécurité, comme indiqué dans le tableau ci-dessous.\
Vous pouvez modifier le volume de la synthèse vocale Haut, Moyen et Bas via la configuration de la centrale. Le volume par défaut est réglé sur Moyen. Veuillez vous référer à votre centrale pour plus de détails.

| **Condition**               | **Indication audio**                                                         |
| --------------------------- | ---------------------------------------------------------------------------- |
| Alarme                      | Alarme continue                                                              |
| Armement total              | Vocal: "_Armement total partition 1/2."_                                     |
| Armement partiel            | Vocal: "_Armement partiel partition 1/2._                                    |
| Désarmement                 | Vocale: "_Désarmement partition 1/2._                                        |
| Mémoire d'alarme            | Vocal: "_Vous avez une alarme en mémoire. Veuillez vérifier partition 1/2."_ |
| Protection périmétrique PIR | Vocal: "Intrusion extérieure. Veuillez vérifier partition 1/2."              |
| Carillon                    | _Ding Dong_                                                                  |
| Bips d'entrée               | _Bips_                                                                       |
| Bips de sortie              | _Bips_                                                                       |

#### **- Alimentation**

La sirène est alimentée par une prise secteur. Branchez la sirène sur une prise de courant pour l'activer. La sirène entrera en mode de fonctionnement normal. SRV-23B, est équipée d'une batterie rechargeable qui sert de secours en cas de panne de courant. En fonctionnement normal, l'alimentation secteur est utilisée pour alimenter la sirène et en même temps recharger la batterie.

#### **- Détection de batterie faible**

Après une panne de courant, la sirène transmettra un signal de batterie faible à la centrale lorsque le seuil de batterie faible sera atteint. Pour restaurer la batterie, rebranchez l'alimentation secteur dans la prise de courant. Après 12 heures, la sirène transmettra une notification de batterie faible restaurée à la centrale.

#### **- Détection de panne secteur**

Chaque fois que la sirène est retirée de la prise de courant, elle transmettra un signal de perte secteur à la centrale pour informer les utilisateurs de la situation. La sirène utilisera alors à sa batterie interne.\
Lorsque la sirène est rebranchée sur la prise de courant, elle enverra un signal de rétablissement de l'alimentation secteur à la centrale.

#### **- Supervision**

La sirène transmet un signal de supervision à la centrale une fois toutes les 30 à 50 minutes pendant le fonctionnement normal.\
Si ce signal n'est pas reçu pendant la durée programmée, la centrale indiquera que la sirène en question rencontre un problème de fonctionnement.



### **Démarrage**

1. Branchez la sirène à la prise de courant. La LED clignotera une fois pour indiquer qu'elle est maintenant en mode de fonctionnement normal.
2. Mettez la centrale en mode apprentissage.
3. Appuyez une fois sur le bouton de la sirène pour transmettre un code d'apprentissage à la centrale. La sirène émettra un bip et la LED s'allumera pour indiquer que la sirène est maintenant en mode apprentissage.
4. La mise en mode apprentissage de la sirène durera jusqu'à 1 minute.
5. Si dans la minute qui suit, la sirène reçoit un accusé de réception de la centrale, la sirène émettra quatre bips et la LED s'éteindra. L'apprentissage est désormais terminé.
6. Si en 1 minute la sirène reçoit un accusé de réception de la centrale et n'émet qu'un seul bip, cela signifie que la sirène a été préalablement apprise dans la centrale.
7. Si après 1 minute la sirène ne reçoit pas d'accusé de réception de la centrale, la sirène émettra 5 bips et la LED s'éteindra. L’apprentissage a échoué. Veuillez répéter le processus d'apprentissage.



### **Programmation de la sirène**

Suivez les instructions ci-dessous pour modifier la partition de la sirène et modifier les paramètres de la sirène dans la centrale.

**Étape 1 :** modifiez la configuration de la sirène  (partition, réglages) depuis la page de configuration de la centrale et appuyez sur le bouton OK pour confirmer. La sirène émettra 3 bips.

**Étape 2 :** Appuyez sur le bouton test de la sirène pour envoyer un signal à la centrale.

**Étape 3 :** Lorsque la sirène reçoit un signal d'accusé de réception de la centrale,  elle émettra 2 bips pour indiquer que le paramètre a été mis à jour. La sirène reviendra à un fonctionnement normal.



### **Réinitialisation**

La sirène peut être réinitialisée et sa mémoire effacée en suivant les étapes suivantes :

1. Supprimez la sirène de la centrale. Reportez-vous au manuel d'utilisation de votre centrale pour plus de détails.
2. Débranchez la sirène de la prise de courant et débranchez la batterie.
3. Maintenez appuyé le bouton d'apprentissage tout en rebranchant la batterie rechargeable, puis en branchant la sirène sur la prise de courant. Si la batterie peut fournir de l'énergie, vous pouvez insérer la batterie uniquement sans brancher la sirène sur la prise de courant.
4. Maintenez le bouton enfoncé pendant environ 7 secondes jusqu'à ce que la sirène émette 2 bips courts, puis un bip long.
5. Relâchez le bouton, la réinitialisation est terminée.



{% hint style="success" %}
Si la centrale dispose de plus de 2 partitions, la sirène n'indiquera pas le numéro de partition dans les message vocaux.
{% endhint %}
