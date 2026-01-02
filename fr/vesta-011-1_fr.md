# 🇫🇷 VESTA-011

**KP-39**

## **Clavier sans fils**

### **Identification**

<figure><img src=".gitbook/assets/image (9) (1) (1) (1).png" alt="" width="375"><figcaption></figcaption></figure>

1. Armement Total
2. Armement Partiel
3. Désarmement
4. Alarme Panique (si activée)
   * appuyez sur **1** et **3** pour déclencher l'alarme Panique
5. Alarme Incendie (si activée)
   * appuyez sur **4** et **6** pour déclencher l'alarme Incendie
6. Alarme Médicale (si activée)
   * appuyez sur **7** et **9** pour déclencher l'alarme Médicale
7. Envoi du code d'apprentissage
   * appuyez sur **＊**&#x65;t **7** (en Mode Test)
   * appuyez sur **#** et **\*** (en mode normal)
8. Touche **#**
9. Touche  \*
10. LED Défaut (orange)
11. LED Alimentation (verte)
12. Trous de fixation
13. Autoprotection

{% hint style="info" %}
NOTE:

* Un bip court retentira à chaque appui sur une touche, ce qui confirmera la validité de l'appui.
* 4 bips continus retentiront pour indiquer à l'utilisateur que la saisie est incorrecte et l'utilisateur est invité à répéter le processus.
{% endhint %}



### **Voyants LED**

* **LED Alimentation (verte) :**
  * Allumée pendant 5 secondes: saisie correcte.
  * Clignote pendant 5 secondes : batterie faible en mode normal.
  * Si le voyant d'alimentation s'éteint avant qu'une saisie ne soit terminée, la saisie est ignorée.
* **LED Défaut (orange) :**
  * Désarmement et LED orange allumée avec 5 bips : mémoire d'alarme (dépend de la centrale).
  * Clignotante:
    * Clignotante uniquement : Aucune réponse envoyée par la centrale dans les 10 secondes.
    * Clignote avec 2 bips : demande d'armement Partiel depuis Armement Total.
    * Clignote avec 3 bips : demande d'armement Total/Partiel avec défaut.
    * Clignote accompagné de 4 bips : code incorrect.



### **Fonctionnement  Général**

* Entrez en mode test - Saisir le code du clavier, puis appuyez sur la touche **＊**.
* Alarme Panique - Appuyez sur les touches **1** et **3** simultanément (si la fonction est activée)
* Alarme Incendie - Appuyez sur les touches **4** et **6** simultanément (si la fonction est activée)
* Alarme Médicale - Appuyez sur les touches **7** et **9** simultanément (si la fonction est activée)
* Vérifier l'état de la centrale - En mode normal appuyez sur la touche **#**.
* Activer/Désactiver les bips d'entrée/sortie — Appuyez sur les touches **1** et **2** simultanement pendant 2 secondes (le clavier émettra un bip long pour indiquer que la fonction est activée et émettra 2 bips courts pour indiquer que la fonction est désactivée).

#### **- Alimentation**

* Le clavier utilise une pile lithium CR123 3 V comme source d'alimentation.
* Le clavier peut également détecter l'état de la batterie. Si la tension de la batterie est faible, la LED Alimentation clignote pendant 5 secondes pendant le fonctionnement. Le signal de batterie faible sera envoyé à la centrale.
* La batterie est préinstallée en usine.
* Lors du changement de batterie, appuyez plusieurs fois sur n'importe quelle touche avant d'insérer une nouvelle batterie.

#### **- Mise en veille**

* Lorsqu'il est inactif, le clavier est en **veille** et ne consomme pas d'énergie. Il s'activera pendant 5 secondes lorsqu'une touche sera utilisée.
* Après 5 secondes d'inactivité, le clavier revient en mode **veille**.

#### **- Autoprotection**

* Le clavier est protégé contre toute tentative d'ouverture du couvercle ou d'arrachement de sa surface d'installation.
* L'autoprotection est désactivée lorsqu'il est en mode test.

#### **- Supervision**

* Après l'installation, le clavier transmet automatiquement des signaux de supervision à la centrale à un intervalle de 30 à 50 minutes.
* Si la centrale n'a pas reçu le signal du clavier pendant une période de temps prédéfinie, la centrale considérera le clavier comme hors service et réagira en fonction de sa configuration.



### **Démarrage**

**Étape 1.** Mettez la centrale en mode apprentissage.\
**Étape 2.** Ajout d'un clavier à la centrale

* **Mode Test :**
  1. Mettez le clavier Test en saisissant le code (par défaut :**0000**), puis appuyez la touch&#x65;**＊**.\
     Les trois touches <img src=".gitbook/assets/10 (13).png" alt="" data-size="line"><img src=".gitbook/assets/11 (9).jpeg" alt="" data-size="line"> s'allumeront avec un long bip.
  2. Appuyez ensuite sur les touches **\*** et **7** pour transmettre le signal d'apprentissage. Le clavier émettra un bip long.
* **Fonction du mode test :**
  1. Appuyez sur les touches **＊**&#x65;t **2** - Activez la fonction Alarme Panique  (double touches)
  2. Appuyez sur les touches **＊**&#x65;t **3** - Activez la fonction Alarme Incendie  (double touches)
  3. Appuyez sur les touches **＊**&#x65;t **4** - Activez la fonction Alarme Médicale  (double touches)
  4. Appuyez sur les touches **＊**&#x65;t **5** - Désactivez toutes les fonctions double touches (par défaut)
  5. Appuyez sur les touches **＊** et **6** - Modifier le code du clavier\
     \- Saisir l'ancien code du clavier et appuyer sur la touche **\***.\
     \- Saisir le nouveau code à 4 chiffres et appuyer sur la touche **#**.
  6. Appuyez sur les touches **＊** et **8** - Activez la fonction armement sans code.\
     &#xNAN;_(Prière de se référer à "**Armement sans code utilisateur"** pour plus de détails)._
  7. Appuyez sur les touches **＊** et **9** - Activez la fonction armement avec code (par défaut).\
     &#xNAN;_(Prière de se référer à "**Armement avec code utilisateur"** pour plus de détails)._

{% hint style="info" %}
NOTES:

* Si le clavier n'a pas émis de bip long, cela signifie qu'il n'a pas envoyé le code d'apprentissage à la centrale, veuillez appuyer sur les touches **＊** puis **7** à nouveau pour renvoyer le code d'apprentissage.
* Si la centrale reçoit le code d'apprentissage, elle affichera les informations en conséquence. Reportez-vous au manuel d'utilisation de votre centrale pour terminer le processus d'apprentissage.
* Une fois que la centrale a reçu le signal du clavier, elle enverra un accusé de réception au clavier. Le clavier émettra alors 3 bips pour confirmer que l'accusé de réception a été reçu. Si le clavier n'émet pas 3 bips, veuillez redémarrer la procédure d'apprentissage.
{% endhint %}

**Étape 3.** Une fois le clavier enregistré, mettre la centrale en mode **Test de fonctionnement**. Maintenez le clavier à l'emplacement souhaité et envoyez le code d'apprentissage à la centrale pour confirmer que cet emplacement se trouve dans la plage de signal de la centrale. Pour envoyer le code d'apprentissage, soit appuyez sur les touches **\*** et **7** en Mode Test ou appuyez sur les touches **#** et **\*** simultanément en mode normal.\
**Étape 4.** Lorsque vous êtes satisfait du fonctionnement du clavier à à l'emplacement choisi, vous pouvez procéder au montage du clavier en suivant les étapes décrites ci-dessous (voir **Montage du clavier**).\
**Étape 5.** Appuyez sur la touche <img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line"> **deux fois** pour quitter le mode Test et l'installation est terminée. Le clavier émettra un long bip et les trois LED de mode système s'éteindront. Le clavier revient au mode de fonctionnement normal.

{% hint style="info" %}
NOTE:\
Le clavier quittera automatiquement le mode test après 5 minutes d'inactivité et reviendra en mode veille. Toutes les LED s'éteindront et le clavier émettra un long bip.
{% endhint %}



### **Contrôle du système d'alarme**

Après avoir terminé l'apprentissage du clavier dans la centrale, l'utilisateur peut changer le mode de fonctionnement du système à l'aide du clavier.\
Il existe deux manières d'armer le système.

1. Armement Total/Partiel en saisissant le code utilisateur.
2. Armement Total/Partiel sans saisir le code utilisateur.

Le désarmement du système nécessite toujours la saisie du code utilisateur.



**Armement Total/Partiel avec code utilisateur:**\
En mode Test, appuyez sur les touches **＊** et **9** pour activer la fonction Armement avec code (**par défaut**).

* **Armement Total:** Saisir un code utilisateur et appuyer sur la touche <img src=".gitbook/assets/image (3) (1) (1) (1) (1) (1).png" alt="" data-size="line">. Si aucun défaut n'est détecté et que l'armement est réalisé, la LED <img src=".gitbook/assets/image (4) (1) (1) (1).png" alt="" data-size="line"> s'allumera accompagnée d'un bip long.
* **Armement Partiel:** Saisir un code utilisateur et appuyer sur la touche <img src=".gitbook/assets/image (5) (1) (1).png" alt="" data-size="line">. Si aucun défaut n'est détecté et que l'armement est réalisé, la LED <img src=".gitbook/assets/image (6) (1) (1).png" alt="" data-size="line"> s'allumera accompagnée de 3 bips longs.
* **Désarmement**: Saisir un code utilisateur et appuyer sur la touche <img src=".gitbook/assets/image (7) (1) (1).png" alt="" data-size="line">. Si le désarmement est réalisé, la LED <img src=".gitbook/assets/image (8) (1) (1).png" alt="" data-size="line">s'allumera accompagnée de 2 bips.

S'il y a une **Mémoire d'alarme** la LED <img src=".gitbook/assets/image (9) (1) (1).png" alt="" data-size="line"> et la LED de défaut s'allumeront avec 5 bips.\
\
**Armement Total/Partiel sans code utilisateur**\
En mode Test, appuyez sur les touches **＊** et **8** pour activer la fonction Armement sans code.

* **Armement Total:** Appuyez sur la touche <img src=".gitbook/assets/image (3) (1) (1) (1) (1) (1).png" alt="" data-size="line">. Si aucun défaut n'est détecté et que l'armement est réalisé, la LED <img src=".gitbook/assets/image (4) (1) (1) (1).png" alt="" data-size="line"> s'allumera accompagnée d'un bip long.
* **Armement Partiel:** Appuyer sur la touche <img src=".gitbook/assets/image (5) (1) (1).png" alt="" data-size="line">. Si aucun défaut n'est détecté et que l'armement est réalisé, la LED <img src=".gitbook/assets/image (6) (1) (1).png" alt="" data-size="line"> s'allumera accompagnée de 3 bips longs.
* **Désarmement**: Saisir un code utilisateur et appuyer sur la touche <img src=".gitbook/assets/image (7) (1) (1).png" alt="" data-size="line">. Si le désarmement est réalisé, la LED <img src=".gitbook/assets/image (8) (1) (1).png" alt="" data-size="line">s'allumera accompagnée de 2 bips.

S'il y a une **Mémoire d'alarme** la LED <img src=".gitbook/assets/image (9) (1) (1).png" alt="" data-size="line"> et la LED de défaut s'allumeront avec 5 bips.

#### **Temporisation d'entrée/de sortie**

* Une fois le son des temporisations d'entrée/de sortie activé en appuyant sur les touches **1** et **2** simultanément pendant 2 secondes (indiqué par un bip long), le clavier émettra des bips lorsque l'une des temporisations sera activée.
* Une fois le son des temporisations d'entrée/de sortie désactivé en appuyant sur les touches **1** et **2** simultanément pendant 2 secondes (indiqué par deux bips courts), restera silencieux pendant les temporisations d'entrée/de sortie.



### **Conditions de défaut**

Lorsque le clavier est en **MODE DE FONCTIONNEMENT NORMAL**

1. Lorsqu'un défaut existe dans la centrale, si le clavier est utilisé pour l'armement, la LED de défaut clignotera avec 3 bips pour indiquer une condition de défaut.
2. Lorsque le clavier désarme la centrale, la LED <img src=".gitbook/assets/image (10) (1) (1).png" alt="" data-size="line"> s'allumera avec deux bips indiquant un fonctionnement normal.
3. Si vous saisissez un code incorrect 4 fois en 10 minutes en mode test, le clavier désactivera les touches pendant 1 minute et toutes les LED clignoteront 3 fois avec 6 bips. Après 1 minute, il émettra un bip long indiquant le retour en mode normal.
4. Si vous saisissez un code incorrect 4 fois en 10 minutes lors d'un changement de mode, le clavier désactivera les touches pendant 5 minutes. Après 5 minutes, le clavier émettra un bip long indiquant le retour en mode normal.



### **Réinitialisation**

La réinitialisation du clavier aux paramètres d'usine restaurera le code du clavier à 0000 et effacera les information relative à la centrale.\
&#xNAN;_**Réinitialiser aux paramètres d'usine :**_\
**Étape 1:** Retirez les piles et relâchez l'autoprotection.\
**Étape 2:**\
\- Si la fonction "**Armement Total/Partiel avec code**" est sélectionnée, maintenir la touche **3** appuyée en insérant la batterie.\
\- Si la fonction "**Armement Total/Partiel sans code**" est sélectionnée, maintenir la touche **4** appuyée en insérant la batterie.\
**Étape 3:**\
\- Maintenir la touche **3** jusqu'à ce que le clavier émette 3 bips pour indiquer une réinitialisation réussie.\
\- Maintenir la touche **4** jusqu'à ce que le clavier émette 4 bips pour indiquer une réinitialisation réussie.\
**Étape 4:** Relâchez la touche **3** ou **4**, le processus de réinitialisation est terminé.

*   Après la réinitialisation, le code revient à la valeur par défaut, "**0000"**. Le clavier aura besoin d'un nouveau processus d'apprentissage pour refonctionner.

    Chaque fois que le clavier est retiré d'une centrale, il doit être également réinitialisé pour effacer la précédente centrale de sa mémoire



### **Installation**

Pour installer le clavier :

1. Retirez le capot avant.
2. En utilisant les 2 trous de montage de la coque arrière comme gabarit, marquez les positions à l'endroit le plus approprié.
3. Insérez les chevilles murales si vous fixez sur une surface en plâtre ou en brique.
4. Vissez le clavier dans les chevilles.
5. Replacez le capot avant.
