# VESTA-012

**KPT-39N**

## <mark style="color:green;">**Clavier avec lecteur RFID**</mark>

### <mark style="color:red;">**GUIDE RAPIDE**</mark>

<figure><img src=".gitbook/assets/VESTA-012N[1].jpg" alt="" width="225"><figcaption><p>VESTA-012 - KPT-39N-F1</p></figcaption></figure>

**Pour ajouter un clavier dans une centrale VESTA :**\
<mark style="color:orange;">**Étape 1:**</mark> Mettre la centrale en **Mode apprentissage.**\
<mark style="color:orange;">**Étape 2:**</mark> Appuyez sur les touches **\*** et **#** pendant 3 secondes pour envoyer le code d'apprentissage à la centrale.

\[❓] Comment mettre la centrale en mode apprentissage à partir de **SmartHomeSec**

{% @arcade/embed flowId="nNYzAkqIZ9RJt89JI6XK" url="https://app.arcade.software/share/nNYzAkqIZ9RJt89JI6XK" %}

**CERTIFICATIONS**

EN50131 Niveau 2, Classe II



### _<mark style="background-color:yellow;">**Identification**</mark>_

![](<.gitbook/assets/0 (6) (1).png>)

1. Armement Total
2. Armement Partiel
3. Désarmement
4. Alarme Panique (si activée)\
   \- appuyez sur **1** et **3** pour déclencher l'alarme panique
5. Alarme Incendie (si activée)\
   \- appuyez sur **4** et **6** pour déclencher l'alarme incendie
6. Alarme Médicale (si activée)\
   \- appuyez sur **7** et **9** pour déclencher l'alarme médicale.
7. Envoyer le code d'apprentissage\
   \- appuyez sur **＊**&#x65;t **7** (en Mode Test)\
   \- appuyez sur les touches # et 🞸 (en mode normal)
8. Touche **#**\
   \- appuyez pour vérifier l'état du système
9. Touche **\***
10. LED Défaut (orange)
11. LED Alimentation (verte)
12. Zone de détection RFID\
    &#x20;\- présentez votre badge dans cette zone pour contrôler le système
13. Autoprotection
14. Fixations
15. Badge

{% hint style="info" %}
NOTE:

* Un bip court retentira à chaque appui sur une touche, ce qui confirmera la validité de l'appui.
* 4 bips continus retentiront pour indiquer à l'utilisateur que la saisie est incorrecte et l'utilisateur est invité à répéter le processus.
{% endhint %}



### _<mark style="background-color:yellow;">**Voyant LED**</mark>_

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



### _<mark style="background-color:yellow;">**Fonctionnement général**</mark>_

* Entrez en mode test - Saisir le code du clavier, puis appuyez sur la touche **＊**.
* Alarme Panique - Appuyez sur les touches **1** et **3** simultanément (si la fonction est activée)
* Alarme Incendie - Appuyez sur les touches **4** et **6** simultanément (si la fonction est activée)
* Alarme Médicale - Appuyez sur les touches **7** et **9** simultanément (si la fonction est activée)
* Vérifier l'état de la centrale - En mode normal appuyez sur la touche **#**.
* Activer/Désactiver les bips d'entrée/sortie — Appuyez sur les touches **1** et **2** simultanement pendant 2 secondes (le clavier émettra un bip long pour indiquer que la fonction est activée et émettra 2 bips courts pour indiquer que la fonction est désactivée).

#### _<mark style="background-color:green;">**- Alimentation**</mark>_

* Le clavier utilise une pile lithium CR123 3 V comme source d'alimentation.
* Le clavier peut également détecter l'état de la batterie. Si la tension de la batterie est faible, la LED Alimentation clignote pendant 5 secondes pendant le fonctionnement. Le signal de batterie faible sera envoyé à la centrale.
* La batterie est préinstallée en usine.
* Lors du changement de batterie, appuyez plusieurs fois sur n'importe quelle touche avant d'insérer une nouvelle batterie.

#### _<mark style="background-color:green;">**- Mise en veille**</mark>_

* Lorsqu'il est inactif, le clavier est en **veille** et ne consomme pas d'énergie. Il s'activera pendant 5 secondes lorsqu'une touche sera utilisée.
* Après 5 secondes d'inactivité, le clavier revient en mode **veille**.

#### _<mark style="background-color:green;">**- Autoprotection**</mark>_

* Le clavier est protégé contre toute tentative d'ouverture du couvercle ou d'arrachement de sa surface d'installation.
* L'autoprotection est désactivée lorsqu'il est en mode test.



### _<mark style="background-color:yellow;">**Démarrage**</mark>_

<mark style="color:orange;">**Étape 1.**</mark> Mettez la centrale en mode apprentissage.\
<mark style="color:orange;">**Étape 2.**</mark> Ajout d'un clavier à la centrale

* **Mode Test :**
  1. Mettez le clavier en Mode Test en saisissant le code (par défaut :**0000**), puis appuyez la touch&#x65;**＊**. Les trois touches <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252Fgit-blob-fe25c9957403e3c10f8e9d28f99d7d324e84ba0f%252F10%2520%2813%29.png%3Falt%3Dmedia&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=bf585e9e&#x26;sv=2" alt="" data-size="line"><img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252Fgit-blob-cf49690b317e6f3fb07c55fd84d849931f4c4cae%252F11%2520%289%29.jpeg%3Falt%3Dmedia&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=b5350c2d&#x26;sv=2" alt="" data-size="line"> s'allumeront avec un long bip.
  2. Appuyez ensuite sur les touches **\*** et **7** pour transmettre le signal d'apprentissage. Le clavier émettra un bip long.
* **Fonction du mode test**&#x20;
  1. Appuyez sur les touches **＊**&#x65;t **1** - Entrez dans le mode apprentissage de badges
  2. Appuyez sur les touches **＊**&#x65;t **2** - Activez la fonction Alarme Panique (double touches)
  3. Appuyez sur les touches **＊**&#x65;t **3** - Activez la fonction Alarme Incendie (double touches)
  4. Appuyez sur les touches **＊**&#x65;t **4** - Activez la fonction Alarme Médicale (double touches)
  5. Appuyez sur les touches **＊**&#x65;t **5** - Désactivez toutes les fonctions double touches (par défaut)
  6. Appuyez sur les touches **＊** et **6** - Modifier le code du clavier\
     \- Saisir l'ancien code du clavier et appuyer sur la touche **\***.\
     \- Saisir le nouveau code à 4 chiffres et appuyer sur la touche **#**.
  7. Appuyez sur les touches **＊** et **8** - Activez la fonction armement sans code.\
     &#xNAN;_(Prière de se référer à "**Armement sans code utilisateur"** pour plus de détails)._
  8. Appuyez sur les touches **＊** et **9** - Activez la fonction armement avec code (par défaut).\
     &#xNAN;_(Prière de se référer à "**Armement avec code utilisateur"** pour plus de détails)._

{% hint style="info" %}
NOTES:

* Si le clavier n'a pas émis de bip long, cela signifie qu'il n'a pas envoyé le code d'apprentissage à la centrale, veuillez appuyer sur les touches **＊** puis **7** à nouveau pour renvoyer le code d'apprentissage.
* Si la centrale reçoit le code d'apprentissage, elle affichera les informations en conséquence. Reportez-vous au manuel d'utilisation de votre centrale pour terminer le processus d'apprentissage.
* Une fois que la centrale a reçu le signal du clavier, elle enverra un accusé de réception au clavier. Le clavier émettra alors 3 bips pour confirmer que l'accusé de réception a été reçu. Si le clavier n'émet pas 3 bips, veuillez redémarrer la procédure d'apprentissage.
{% endhint %}

<mark style="color:orange;">**Étape 3.**</mark> Une fois le clavier enregistrée, mettre la centrale en mode **Test de fonctionnement**. Maintenez le clavier à l'emplacement souhaité et envoyez le code d'apprentissage à la centrale pour confirmer que cet emplacement se trouve dans la plage de signal de la centrale. Pour envoyer le code d'apprentissage, soit appuyez sur les touches **\*** et **7** en Mode Test ou appuyez sur les touches **#** et **\*** simultanément en mode normal.\
<mark style="color:orange;">**Étape 4.**</mark> Lorsque vous êtes satisfait du fonctionnement du clavier à à l'emplacement choisi, vous pouvez procéder au montage du clavier en suivant les étapes décrites ci-dessous (voir **Montage du clavier**).\
<mark style="color:orange;">**Étape 5.**</mark> Appuyez sur la touche <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252F2MnHDzRPaVSuKYygr5PA%252Fimage.png%3Falt%3Dmedia%26token%3D5dbcd3d4-6f70-4fdf-9c3b-671ede8ec531&#x26;width=40&#x26;dpr=4&#x26;quality=100&#x26;sign=6a24b07d&#x26;sv=2" alt="" data-size="line"> **deux fois** pour quitter le mode Test et l'installation est terminée. Le clavier émettra un long bip et les trois LED de mode système s'éteindront. Le clavier revient au mode de fonctionnement normal.

{% hint style="info" %}
NOTE:\
Le clavier quittera automatiquement le mode test après 5 minutes d'inactivité et reviendra en mode veille. Toutes les LED s'éteindront et le clavier émettra un long bip
{% endhint %}



### _<mark style="background-color:yellow;">**Procédures d'apprentissage/effacement/installation des badges**</mark>_

NFC signifie Near Field Communication, qui est une technologie de communication sans fil qui établit une connexion entre deux appareils en les rapprochant. Vous pouvez stocker un code PIN utilisateur dans une étiquette NFC et utiliser l'étiquette NFC pour accéder au système d'alarme sans saisir de code PIN utilisateur sur le KPT-39N. Le clavier peut apprendre jusqu'à 100 étiquettes NFC avec jusqu'à 50 codes.\
&#xNAN;_<mark style="color:blue;">**A. Procédure d'apprentissage**</mark>**&#x20;:**_\
<mark style="color:orange;">**Étape 1.**</mark> Activez le clavier pour passer en mode test. Saisissez le code du clavier (par défaut :**0000**) suivi de la touche ＊. Lors de la saisie du code, le **LED Alimentation (verte)** s'allumera. La **LED Alimentation** s'éteindra et un bip long sera audible.\
<mark style="color:orange;">**Étape 2.**</mark> Appuyez sur les touches **＊** puis **1** pour accéder au mode d'apprentissage des badges. La **LED Défaut (orange)** s'allumera et un bip long sera audible.\
<mark style="color:orange;">**Étape 3.**</mark> Saisir le nouveau code utilisateur suivi de la touche **#**. Le clavier émettra un long bip et la LED orange commencera à clignoter pendant 5 secondes pour indiquer qu'il est prêt à apprendre un badge.\
<mark style="color:orange;">**Étape 4.**</mark> Dans les 5 secondes, placez un badge à proximité de la zone de détection du clavier pour l'associer avec le code utilisateur que vous venez de saisir.

* Chaque badge associé réinitialisera le délai d'apprentissage de badge de 5 secondes. Vous pouvez associer plusieurs badges avec un seul code utilisateur en appliquant les badges un par un.
* Le clavier sortira du mode apprentissage des badges après 5 secondes d'inactivité.
* Si le badge appris est seul, le clavier émettra 2 bips courts.
* Si le badge appris existe déjà dans le clavier (attribué à un autre code PIN), le clavier émettra 1 bip court.

<mark style="color:orange;">**Étape 5.**</mark> Pour apprendre un autre badge, veuillez répéter les étapes 3 à 4. Le clavier quittera automatiquement le mode d'apprentissage de badges après 5 secondes d'inactivité.\
<mark style="color:orange;">**Étape 6.**</mark> Appuyez sur la touche <img src=".gitbook/assets/4 (8).png" alt="" data-size="line"> pour quitter le mode d'apprentissage de badges.

* Condition d'erreur
  * Si le code utilisateur de la centrale saisi dépasse le nombre maximum de chiffres du code, la LED orange clignotera avec 4 bips courts pour indiquer une erreur.
  * Si le clavier a déjà stocké 50 codes utilisateurs, il émettra 4 bips courts pour indiquer une erreur lorsque vous tenterez de saisir le 51e code PIN.
  * Si le clavier a déjà stocké 100 badges, il émettra 4 bips courts pour indiquer une erreur lorsque vous tenterez d'apprendre le 101ème.

_<mark style="color:blue;">**B. Procédure de suppression :**</mark>_\
Vous pouvez effacer les informations de l'étiquette NFC.\
<mark style="color:orange;">**Étape 1.**</mark> Activez le clavier pour passer en mode test. Saisissez le code du clavier (par défaut :**0000**) suivi de la touche **＊**. Lors de la saisie du code PIN, la **LED alimentation (verte)** s'allumera. La **LED alimentation** s'éteindra alors et un bip long sera audible.\
<mark style="color:orange;">**Étape 2.**</mark> Appuyez sur les touches **＊** puis **1** pour accéder au mode d'apprentissage des badges. La **LED Défaut (orange)** s'allumera et un bip long sera audible.\
<mark style="color:orange;">**Étape 3.**</mark> Si vous souhaitez supprimer un code utilisateur stocké dans le clavier et tous les badges associés à ce codes, entrez le code utilisateur et appuyez sur la touche **＊**, un bip long retentira.\
Si vous souhaitez effacer uniquement un badge spécifique, appuyez sur la touche **＊**, un bi long retentira et la LED orange clignotera pendant 5 secondes. Appliquez le badge dans la zone de détection du clavier dans les 5 secondes :

* Si le badge existe dans le clavier, le clavier émettra 2 bips courts pour indiquer que les données du badge ont été supprimées.
* Si le badge appliqué n'existe pas sur le clavier, le clavier émettra 4 bips courts pour indiquer une erreur.
* Chaque présentation de badge réinitialisera le délai de suppression à 5 secondes, vous pouvez supprimer badges en les appliquant un par un.

<mark style="color:orange;">**Étape 4.**</mark> Le clavier quittera automatiquement le mode de suppression de badges après 5 secondes d'inactivité.\
<mark style="color:orange;">**Étape 5.**</mark> Appuyez sur la touche <img src=".gitbook/assets/4 (8).png" alt="" data-size="line"> pour quitter le mode de suppression de badges.

_<mark style="color:blue;">**C. Procédure d'installation d'étiquettes NFC :**</mark>_\
Les petites étiquettes NFC peuvent être placées au dos des smartphones, des cartes ou des porte-clés pour un accès facile.\
<mark style="color:orange;">**Étape 1.**</mark> Apprenez l'étiquette NFC au clavier.\
<mark style="color:orange;">**Étape 2.**</mark> Retirez la protection de l'étiquette NFC.\
<mark style="color:orange;">**Étape 3.**</mark> Appliquez l'étiquette NFC sur la coque arrière de votre téléphone portable, etc.\
<mark style="color:orange;">**Étape 4.**</mark> Vous pouvez maintenant utiliser l'étiquette NFC pour accéder au système.

{% hint style="info" %}
NOTES:

* Faites attention de ne pas plier l'étiquette NFC, car elle pourrait être endommagée et devenir inutilisable.
* Le KPT-39N prend uniquement en charge le protocole ISO 14443A pour les étiquettes NFC.
{% endhint %}



### _<mark style="background-color:yellow;">**Contrôle du système d'alarme**</mark>_

Après avoir terminé l'apprentissage du clavier dans la centrale, l'utilisateur peut changer le mode de fonctionnement du système à l'aide du clavier. Il existe deux manières d'armer le système.

1. Armement Total/Partiel en saisissant le code utilisateur.
2. Armement Total/Partiel sans saisir le code utilisateur.

Le désarmement du système nécessite toujours la saisie du code utilisateur.



**Armement Total/Partiel avec code utilisateur:**\
En mode Test, appuyez sur les touches **＊** et **9** pour activer la fonction Armement avec code (**par défaut**).

* **Armement Total:** Saisir un code utilisateur et appuyer sur la touche <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252FdmFGjR3gtYCSEVljlGkc%252Fimage.png%3Falt%3Dmedia%26token%3Dc4b43939-98ae-40c5-a663-b236e45e91aa&#x26;width=40&#x26;dpr=4&#x26;quality=100&#x26;sign=4f761386&#x26;sv=2" alt="" data-size="line"> ou appuyez sur <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252FdmFGjR3gtYCSEVljlGkc%252Fimage.png%3Falt%3Dmedia%26token%3Dc4b43939-98ae-40c5-a663-b236e45e91aa&#x26;width=40&#x26;dpr=4&#x26;quality=100&#x26;sign=4f761386&#x26;sv=2" alt="" data-size="line"> et présenter le badge. Si aucun défaut n'est détecté et que l'armement est réalisé, la LED <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252F1duxNYMFKZqlqu0vvi8d%252Fimage.png%3Falt%3Dmedia%26token%3Dee7d40f2-471c-4ef5-9396-5a0f84b69f02&#x26;width=40&#x26;dpr=4&#x26;quality=100&#x26;sign=5eb073fa&#x26;sv=2" alt="" data-size="line"> s'allumera accompagnée d'un bip long.
* **Armement Partiel:** Saisir un code utilisateur et appuyer sur la touche <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252Fb4PDPCHyfQSaX9IYAoWP%252Fimage.png%3Falt%3Dmedia%26token%3D17033c6d-9eb3-463a-8f04-b85d06bf00dd&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=f84da075&#x26;sv=2" alt="" data-size="line"> ou appuyez sur <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252Fb4PDPCHyfQSaX9IYAoWP%252Fimage.png%3Falt%3Dmedia%26token%3D17033c6d-9eb3-463a-8f04-b85d06bf00dd&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=f84da075&#x26;sv=2" alt="" data-size="line"> et présenter le badge. Si aucun défaut n'est détecté et que l'armement est réalisé, la LED <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252FNmnuDxoa3GgdidX9GWHU%252Fimage.png%3Falt%3Dmedia%26token%3D803a0392-3e68-4856-9c3f-42bfcd016aca&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=39ccae56&#x26;sv=2" alt="" data-size="line"> s'allumera accompagnée de 3 bips.
* **Désarmement**: Saisir un code utilisateur et appuyer sur la touche <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252Ftb0iCBwAJBf60kqn8Fga%252Fimage.png%3Falt%3Dmedia%26token%3Dd8c2133f-1cbd-4899-b214-5d40cc39b168&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=3090d548&#x26;sv=2" alt="" data-size="line"> ou appuyez sur <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252Ftb0iCBwAJBf60kqn8Fga%252Fimage.png%3Falt%3Dmedia%26token%3Dd8c2133f-1cbd-4899-b214-5d40cc39b168&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=3090d548&#x26;sv=2" alt="" data-size="line"> et présenter le badge. Si le désarmement est réalisé, la LED <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252FrJyHIZTVerswVjjDyD4L%252Fimage.png%3Falt%3Dmedia%26token%3Dc3d65df2-acb1-4b6f-98d6-38f92c655932&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=8de5945b&#x26;sv=2" alt="" data-size="line">s'allumera accompagnée de 2 bips.

S'il y a une **Mémoire d'alarme** la LED <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252F6D7X8cEk4V8mFciKGA9V%252Fimage.png%3Falt%3Dmedia%26token%3D3002cd41-7b67-40ca-81f6-325844ee1be4&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=517d1f8e&#x26;sv=2" alt="" data-size="line"> et la LED de défaut s'allumeront avec 5 bips.

**Armement Total/Partiel sans code utilisateur** En mode Test, appuyez sur les touches **＊** et **8** pour activer la fonction Armement sans code.

* **Armement Total:** Appuyez sur la touche <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252FdmFGjR3gtYCSEVljlGkc%252Fimage.png%3Falt%3Dmedia%26token%3Dc4b43939-98ae-40c5-a663-b236e45e91aa&#x26;width=40&#x26;dpr=4&#x26;quality=100&#x26;sign=4f761386&#x26;sv=2" alt="" data-size="line">. Si aucun défaut n'est détecté et que l'armement est réalisé, la LED <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252F1duxNYMFKZqlqu0vvi8d%252Fimage.png%3Falt%3Dmedia%26token%3Dee7d40f2-471c-4ef5-9396-5a0f84b69f02&#x26;width=40&#x26;dpr=4&#x26;quality=100&#x26;sign=5eb073fa&#x26;sv=2" alt="" data-size="line"> s'allumera accompagnée d'un bip long.
* **Armement Partiel:** Appuyer sur la touche <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252Fb4PDPCHyfQSaX9IYAoWP%252Fimage.png%3Falt%3Dmedia%26token%3D17033c6d-9eb3-463a-8f04-b85d06bf00dd&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=f84da075&#x26;sv=2" alt="" data-size="line">. Si aucun défaut n'est détecté et que l'armement est réalisé, la LED <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252FNmnuDxoa3GgdidX9GWHU%252Fimage.png%3Falt%3Dmedia%26token%3D803a0392-3e68-4856-9c3f-42bfcd016aca&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=39ccae56&#x26;sv=2" alt="" data-size="line"> s'allumera accompagnée de 3 bips longs.
* **Désarmement**: Saisir un code utilisateur et appuyer sur la touche <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252Ftb0iCBwAJBf60kqn8Fga%252Fimage.png%3Falt%3Dmedia%26token%3Dd8c2133f-1cbd-4899-b214-5d40cc39b168&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=3090d548&#x26;sv=2" alt="" data-size="line">. Si le désarmement est réalisé, la LED <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252FrJyHIZTVerswVjjDyD4L%252Fimage.png%3Falt%3Dmedia%26token%3Dc3d65df2-acb1-4b6f-98d6-38f92c655932&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=8de5945b&#x26;sv=2" alt="" data-size="line">s'allumera accompagnée de 2 bips.

S'il y a une **Mémoire d'alarme** la LED <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252F6D7X8cEk4V8mFciKGA9V%252Fimage.png%3Falt%3Dmedia%26token%3D3002cd41-7b67-40ca-81f6-325844ee1be4&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=517d1f8e&#x26;sv=2" alt="" data-size="line"> et la LED de défaut s'allumeront avec 5 bips.

#### _<mark style="background-color:green;">**- Temporisation d'entrée/de sortie**</mark>_

* Une fois le son des temporisations d'entrée/de sortie activé en appuyant sur les touches **1** et **2** simultanément pendant 2 secondes (indiqué par un bip long), le clavier émettra des bips lorsque l'une des temporisations sera activée.
* Une fois le son des temporisations d'entrée/de sortie désactivé en appuyant sur les touches **1** et **2** simultanément pendant 2 secondes (indiqué par deux bips courts), restera silencieux pendant les temporisations d'entrée/de sortie.



### _<mark style="background-color:yellow;">**Conditions de défaut**</mark>_

Lorsque le clavier est en **MODE DE FONCTIONNEMENT NORMAL**

1. Lorsqu'un défaut existe dans la centrale, si le clavier est utilisé pour l'armement, la LED de défaut clignotera avec 3 bips pour indiquer une condition de défaut.
2. Lorsque le clavier désarme la centrale, la LED <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252F62JLaNrZYGDMWkpk9sfU%252Fimage.png%3Falt%3Dmedia%26token%3D9bdda193-6b70-4a65-bda5-d3de5b93bf14&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=ee2b4905&#x26;sv=2" alt="" data-size="line"> s'allumera avec deux bips indiquant un fonctionnement normal.
3. Si vous saisissez un code incorrect 4 fois en 10 minutes en mode test, le clavier désactivera les touches pendant 1 minute et toutes les LED clignoteront 3 fois avec 6 bips. Après 1 minute, il émettra un bip long indiquant le retour en mode normal.
4. Si vous saisissez un code incorrect 4 fois en 10 minutes lors d'un changement de mode, le clavier désactivera les touches pendant 5 minutes. Après 5 minutes, le clavier émettra un bip long indiquant le retour en mode normal.



### _<mark style="background-color:yellow;">**Réinitialisation**</mark>_

La réinitialisation du clavier aux paramètres d'usine restaurera le code du clavier à 0000 et effacera les information relative à la centrale.\
&#xNAN;_<mark style="color:blue;">**Réinitialiser aux paramètres d'usine :**</mark>_\
<mark style="color:orange;">**Étape 1:**</mark> Retirez les piles et relâchez l'autoprotection.\
<mark style="color:orange;">**Étape 2:**</mark> \
\- Si la fonction "**Armement Total/Partiel avec code**" est sélectionnée, maintenir la touche **3** appuyée en insérant la batterie.\
\- Si la fonction "**Armement Total/Partiel sans code**" est sélectionnée, maintenir la touche **4** appuyée en insérant la batterie.\
<mark style="color:orange;">**Étape 3:**</mark>\
\- Maintenir la touche **3** jusqu'à ce que le clavier émette 3 bips pour indiquer une réinitialisation réussie.\
\- Maintenir la touche **4** jusqu'à ce que le clavier émette 4 bips pour indiquer une réinitialisation réussie. <mark style="color:orange;">**Étape 4:**</mark> Relâchez la touche **3** ou **4**, le processus de réinitialisation est terminé.\
Après la réinitialisation, le code revient à la valeur par défaut, "**0000"**. Le clavier aura besoin d'un nouveau processus d'apprentissage pour refonctionner.

* Chaque fois que le clavier est retiré d'une centrale, il doit être également réinitialisé pour effacer la précédente centrale de sa mémoire



### _<mark style="background-color:yellow;">**Installation**</mark>_

Pour installer le clavier :

1. Retirez le capot avant.
2. En utilisant les 2 trous de montage de la coque arrière comme gabarit, marquez les positions à l'endroit le plus approprié.
3. Insérez les chevilles murales si vous fixez sur une surface en plâtre ou en brique.
4. Vissez le clavier dans les chevilles.
5. Replacez le capot avant.
