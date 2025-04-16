# VESTA-012N

**39N-BLE**

## <mark style="color:green;">**Clavier avec lecteur RFID et Bluetooth**</mark>

### _<mark style="background-color:yellow;">**Introduction**</mark>_

KPT-39N-BLE est un clavier avec fonction Bluetooth et lecteur RFID. Il est conçu pour permettre un le contrôle rapide de la centrale via un code utilisateur, un badge ou en approchant un smartphone associé en Bluetooth pour désarmer le système. Le clavier peut envoyer et recevoir des sign,aux RF de la centrale.\
Le clavier peut être installé sur une surface plane ou sur un mur à l'aide de vis. Il dispose également d'une autoprotection qui sera activée lors de toute tentative non autorisée d'ouvrir le couvercle ou retirer le clavier de son emplacement d'installation.

### _<mark style="background-color:yellow;">**Identification**</mark>_

![](<.gitbook/assets/3 (14).jpeg>)

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
NOTE:\
\- Un bip court retentira à chaque appui sur une touche, ce qui confirmera la validité de l'appui.\
\- 4 bips continus retentiront pour indiquer à l'utilisateur que la saisie est incorrecte et l'utilisateur est invité à répéter le processus.
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
* Alarme Panique - Appuyez sur les touches **1** et **3** simultanément (si la fonction est activée).
* Alarme Incendie - Appuyez sur les touches **4** et **6** simultanément (si la fonction est activée).
* Alarme Médicale - Appuyez sur les touches **7** et **9** simultanément (si la fonction est activée).
* Vérifier l'état de la centrale - En mode normal appuyez sur la touche **#**.
* Activer/Désactiver les bips d'entrée/sortie — Appuyez sur les touches **1** et **2** simultanément pendant 2 secondes (le clavier émettra un bip long pour indiquer que la fonction est activée et émettra 2 bips courts pour indiquer que la fonction est désactivée).



### _<mark style="background-color:yellow;">**Alimentation**</mark>_

* Le clavier utilise une pile lithium CR123 3 V comme source d'alimentation.
* Le clavier peut également détecter l'état de la batterie. Si la tension de la batterie est faible, la LED Alimentation clignote pendant 5 secondes pendant le fonctionnement. Le signal de batterie faible sera envoyé à la centrale.
* La batterie est préinstallée en usine.
* Lors du changement de batterie, appuyez plusieurs fois sur n'importe quelle touche avant d'insérer une nouvelle batterie.



### _<mark style="background-color:yellow;">**Mise en veille**</mark>_

* Lorsqu'il est inactif, le clavier est en **veille** et ne consomme pas d'énergie. Il s'activera pendant 5 secondes lorsqu'une touche sera utilisée.
* Après 5 secondes d'inactivité, le clavier revient en mode **veille**.



### _<mark style="background-color:yellow;">**Autoprotection**</mark>_

* Le clavier est protégé contre toute tentative d'ouverture du couvercle ou d'arrachement de sa surface d'installation.
* L'autoprotection est désactivée lorsque le clavier est en mode test.



### _<mark style="background-color:yellow;">**Supervision**</mark>_

* Après l'installation, le clavier transmet automatiquement des signaux de supervision à la centrale à un intervalle de 30 à 50 minutes.
* Si la centrale n'a pas reçu le signal du clavier pendant une période de temps prédéfinie, la centrale considérera le clavier comme hors service et réagira en fonction de sa configuration.



### _<mark style="background-color:yellow;">**Apprentissage du clavier dans la centrale**</mark>_

<mark style="background-color:green;">Étape 1.</mark> Mettez la centrale en **Mode d'apprentissage**. Veuillez vous référer au manuel de la centrale.\
<mark style="background-color:green;">Étape 2.</mark> Ajoutez le clavier à la centrale.

* **Mode normal**\
  En mode normal, maintenir les touches \* et # appuyées pendant 2 secondes pour transmettre le code d'apprentissage à la centrale.
* **Mode Test**\
  Mettez le clavier en Mode Test en saisissant le code (par défaut :**0000**), puis appuyez la touch&#x65;**＊**. Les trois touches <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252Fgit-blob-fe25c9957403e3c10f8e9d28f99d7d324e84ba0f%252F10%2520%2813%29.png%3Falt%3Dmedia&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=bf585e9e&#x26;sv=2" alt="" data-size="line"><img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252Fgit-blob-cf49690b317e6f3fb07c55fd84d849931f4c4cae%252F11%2520%289%29.jpeg%3Falt%3Dmedia&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=b5350c2d&#x26;sv=2" alt="" data-size="line"> s'allumeront avec un long bip.\
  Appuyez ensuite sur les touches **\*** et **7** pour transmettre le signal d'apprentissage. Le clavier émettra un bip long.

<mark style="background-color:green;">Étape 3.</mark> Reportez-vous au manuel de la centrale pour terminer le processus d'apprentissage. Si l'apprentissage réussit, le clavier émettra 3 bips dès réception du signal d'accusé de réception de la centrale. Si le clavier n'émet pas 3 bips,  veuillez répéter l'étape 2 pour transmettre à nouveau le code d'apprentissage.\
<mark style="background-color:green;">Étape 4.</mark> Une fois le clavier enregistrée, mettre la centrale en **Mode** **Test**, maintenez le clavier à l'emplacement souhaité et envoyez le code d'apprentissage à la centrale pour confirmer que l'emplacement se trouve dans la plage de signal de la centrale.



### _<mark style="background-color:yellow;">**Modifier la partition du clavier**</mark>_

* Suivez les instructions ci-dessous pour modifier la partition du clavier dans la centrale:
  1. Utilisez le menu de configuration pour modifier la partition du clavier.
  2. Mettez la centrale en **Mode apprentissage**.
  3. Maintenez les touches **＊** et **#** appuyées pendant 2 secondes pour transmettre le code d'apprentissage à la centrale.



### _<mark style="background-color:yellow;">**Procédure d'ajout/de suppression de badges**</mark>_

Le clavier est capable de transmettre les informations des badges à la centrale et vous pouvez attribuer un code utilisateur et un nom à chaque badge depuis la page web de la central. Les badges peuvent ensuite être utilisés pour contrôler le mode de fonctionnement du système d’alarme via le clavier. Le nombre de badges et de codes utilisateur est géré depuis la page web de la centrale.

1.  _**Ajouter un badge:**_\
    Lors de l'ajout d'un nouveau badge, le clavier doit être en mode normal.\
    <mark style="color:orange;">Étape 1.</mark> Accédez au menu PIN code de la page web de la centrale. Choisir la partition dans laquelle l'utilisateur doit être créé, saisissez un code utilisateur à 4 ou 6 chiffres et un nom d'utilisateur qui seront associés au badge.

    ![](<.gitbook/assets/17 (8).png>)

    <mark style="color:orange;">Étape 2.</mark>  Une fois le clavier appris dans la centrale, appuyez sur la touche <img src=".gitbook/assets/18 (5).jpeg" alt="" data-size="line"> du clavier. Appliquez le nouveau badge dans la zone de détection du clavier. Le rétroéclairage blanc s'activera accompagné de 4 bips pour indiquer que ce badge n'a jamais été enregistré au système.\
    <mark style="color:orange;">Étape 3</mark>. Cliquez sur le bouton Load du menu PIN code de la page web comme indiqué ci-dessous. L'identifiant du badge s'affichera. Cliquez sur Submit pour sauvegarder la configuration.

    ![](<.gitbook/assets/19 (11).png>)

    <mark style="color:orange;">Étape 4.</mark> Le badge est ajouté. Vous pouvez utiliser le badge pour armer en mode total/partiel ou désarmer le système. Lorsque le clavier démarre en insérant les piles, la LED orange clignote et le rétroéclairage blanc s'allume. Lorsque la LED est éteinte, attendez 10 secondes pour que le lecteur RFID soit fonctionnel.
2.  _**Supprimer un badge :**_\
    Étape 1. Accédez au menu PIN code de la page web de la centrale.\
    Étape 2. Supprimez manuellement le numéro du badge et cliquez sur Submit.

    ![](<.gitbook/assets/20 (9).png>)

    Étape 3. Le badge est effacé.



### _<mark style="background-color:yellow;">**Mode  programmation**</mark>_

**Entrez en mode programmation :**

* Mettez le clavier en mode programmation en saisissant le code (par défaut :**0000**), puis appuyez la sur la touch&#x65;**＊**. Les trois touches <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252Fgit-blob-fe25c9957403e3c10f8e9d28f99d7d324e84ba0f%252F10%2520%2813%29.png%3Falt%3Dmedia&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=bf585e9e&#x26;sv=2" alt="" data-size="line"><img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252Fgit-blob-cf49690b317e6f3fb07c55fd84d849931f4c4cae%252F11%2520%289%29.jpeg%3Falt%3Dmedia&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=b5350c2d&#x26;sv=2" alt="" data-size="line"> s'allumeront avec un bip long.

**Fonctions du mode programmation :**

* Appuyez sur les touches **\*** et **1** - Activez le mode BLE.
  * Sauf en appuyant sur les touches **＊** et **1** en mode de programmation pour accéder au mode couplage BLE, l'accès rapide au mode couplage BLE consiste à appuyer sur les touches **＊** et **0** simultanément pendant 2 secondes avec l'autoprotection du clavier déclenchée.
* Appuyez sur les touches **＊**&#x65;t **2** - Activez la fonction Alarme Panique (double touches)
* Appuyez sur les touches **＊**&#x65;t **3** - Activez la fonction Alarme Incendie (double touches)
* Appuyez sur les touches **＊**&#x65;t **4** - Activez la fonction Alarme Médicale (double touches)
* Appuyez sur les touches **＊**&#x65;t **5** - Désactivez toutes les fonctions double touches (par défaut)
* Appuyez sur les touches **＊** et **6** - Modifier le code du clavier - Saisir l'ancien code du clavier et appuyer sur la touche **\***. - Saisir le nouveau code à 4 chiffres et appuyer sur la touche **#**.
* Appuyez sur les touches **＊** et **8** - Activez la fonction armement sans code. _(Prière de se référer à "**Armement sans code utilisateur"** pour plus de détails)._
* Appuyez sur les touches **＊** et **9** - Activez la fonction armement avec code (par défaut). _(Prière de se référer à "**Armement avec code utilisateur"** pour plus de détails)._

**Sortir du mode programmation :**

* Appuyez sur la touche <img src=".gitbook/assets/image (12).png" alt="" data-size="line"> **deux fois** pour quitter le mode programmation. Alternativement, le clavier sortira automatiquement du mode programmation après 5 minutes d'inactivité et reviendra en mode veille. Toutes les LED s'éteindront et le clavier émettra un bip long.



### _<mark style="background-color:yellow;">**Contrôle du système**</mark>_

Après avoir terminé l'apprentissage du clavier dans la centrale, l'utilisateur peut changer le mode de fonctionnement du système à l'aide du clavier. Il existe deux manières d'armer le système.

1. Armement Total/Partiel en saisissant le code utilisateur.
2. Armement Total/Partiel sans saisir le code utilisateur.

Le désarmement du système nécessite toujours la saisie du code utilisateur.

**Armement Total/Partiel avec code utilisateur:**\
En mode programmation, appuyez sur les touches **＊** et **9** pour activer la fonction Armement avec code (**par défaut**).

* **Armement Total:** Saisir un code utilisateur et appuyer sur la touche <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252FdmFGjR3gtYCSEVljlGkc%252Fimage.png%3Falt%3Dmedia%26token%3Dc4b43939-98ae-40c5-a663-b236e45e91aa&#x26;width=40&#x26;dpr=4&#x26;quality=100&#x26;sign=4f761386&#x26;sv=2" alt="" data-size="line"> ou appuyez sur <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252FdmFGjR3gtYCSEVljlGkc%252Fimage.png%3Falt%3Dmedia%26token%3Dc4b43939-98ae-40c5-a663-b236e45e91aa&#x26;width=40&#x26;dpr=4&#x26;quality=100&#x26;sign=4f761386&#x26;sv=2" alt="" data-size="line"> et présenter le badge. Si aucun défaut n'est détecté et que l'armement est réalisé, la LED <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252F1duxNYMFKZqlqu0vvi8d%252Fimage.png%3Falt%3Dmedia%26token%3Dee7d40f2-471c-4ef5-9396-5a0f84b69f02&#x26;width=40&#x26;dpr=4&#x26;quality=100&#x26;sign=5eb073fa&#x26;sv=2" alt="" data-size="line"> s'allumera accompagnée d'un bip long.
* **Armement Partiel:** Saisir un code utilisateur et appuyer sur la touche <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252Fb4PDPCHyfQSaX9IYAoWP%252Fimage.png%3Falt%3Dmedia%26token%3D17033c6d-9eb3-463a-8f04-b85d06bf00dd&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=f84da075&#x26;sv=2" alt="" data-size="line"> ou appuyez sur <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252Fb4PDPCHyfQSaX9IYAoWP%252Fimage.png%3Falt%3Dmedia%26token%3D17033c6d-9eb3-463a-8f04-b85d06bf00dd&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=f84da075&#x26;sv=2" alt="" data-size="line"> et présenter le badge. Si aucun défaut n'est détecté et que l'armement est réalisé, la LED <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252FNmnuDxoa3GgdidX9GWHU%252Fimage.png%3Falt%3Dmedia%26token%3D803a0392-3e68-4856-9c3f-42bfcd016aca&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=39ccae56&#x26;sv=2" alt="" data-size="line"> s'allumera accompagnée de 3 bips.
* **Désarmement**: Saisir un code utilisateur et appuyer sur la touche <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252Ftb0iCBwAJBf60kqn8Fga%252Fimage.png%3Falt%3Dmedia%26token%3Dd8c2133f-1cbd-4899-b214-5d40cc39b168&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=3090d548&#x26;sv=2" alt="" data-size="line"> ou appuyez sur <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252Ftb0iCBwAJBf60kqn8Fga%252Fimage.png%3Falt%3Dmedia%26token%3Dd8c2133f-1cbd-4899-b214-5d40cc39b168&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=3090d548&#x26;sv=2" alt="" data-size="line"> et présenter le badge. Si le désarmement est réalisé, la LED <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252FrJyHIZTVerswVjjDyD4L%252Fimage.png%3Falt%3Dmedia%26token%3Dc3d65df2-acb1-4b6f-98d6-38f92c655932&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=8de5945b&#x26;sv=2" alt="" data-size="line">s'allumera accompagnée de 2 bips.

S'il y a une **Mémoire d'alarme** la LED <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252F6D7X8cEk4V8mFciKGA9V%252Fimage.png%3Falt%3Dmedia%26token%3D3002cd41-7b67-40ca-81f6-325844ee1be4&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=517d1f8e&#x26;sv=2" alt="" data-size="line"> et la LED de défaut s'allumeront avec 5 bips.

**Armement Total/Partiel sans code utilisateur**\
En mode programmation, appuyez sur les touches **＊** et **8** pour activer la fonction Armement sans code.

* **Armement Total:** Appuyez sur la touche <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252FdmFGjR3gtYCSEVljlGkc%252Fimage.png%3Falt%3Dmedia%26token%3Dc4b43939-98ae-40c5-a663-b236e45e91aa&#x26;width=40&#x26;dpr=4&#x26;quality=100&#x26;sign=4f761386&#x26;sv=2" alt="" data-size="line">. Si aucun défaut n'est détecté et que l'armement est réalisé, la LED <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252F1duxNYMFKZqlqu0vvi8d%252Fimage.png%3Falt%3Dmedia%26token%3Dee7d40f2-471c-4ef5-9396-5a0f84b69f02&#x26;width=40&#x26;dpr=4&#x26;quality=100&#x26;sign=5eb073fa&#x26;sv=2" alt="" data-size="line"> s'allumera accompagnée d'un bip long.
* **Armement Partiel:** Appuyer sur la touche <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252Fb4PDPCHyfQSaX9IYAoWP%252Fimage.png%3Falt%3Dmedia%26token%3D17033c6d-9eb3-463a-8f04-b85d06bf00dd&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=f84da075&#x26;sv=2" alt="" data-size="line">. Si aucun défaut n'est détecté et que l'armement est réalisé, la LED <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252FNmnuDxoa3GgdidX9GWHU%252Fimage.png%3Falt%3Dmedia%26token%3D803a0392-3e68-4856-9c3f-42bfcd016aca&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=39ccae56&#x26;sv=2" alt="" data-size="line"> s'allumera accompagnée de 3 bips longs.
* **Désarmement**: Saisir un code utilisateur et appuyer sur la touche <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252Ftb0iCBwAJBf60kqn8Fga%252Fimage.png%3Falt%3Dmedia%26token%3Dd8c2133f-1cbd-4899-b214-5d40cc39b168&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=3090d548&#x26;sv=2" alt="" data-size="line">. Si le désarmement est réalisé, la LED <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252FrJyHIZTVerswVjjDyD4L%252Fimage.png%3Falt%3Dmedia%26token%3Dc3d65df2-acb1-4b6f-98d6-38f92c655932&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=8de5945b&#x26;sv=2" alt="" data-size="line">s'allumera accompagnée de 2 bips.

S'il y a une **Mémoire d'alarme** la LED <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252F6D7X8cEk4V8mFciKGA9V%252Fimage.png%3Falt%3Dmedia%26token%3D3002cd41-7b67-40ca-81f6-325844ee1be4&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=517d1f8e&#x26;sv=2" alt="" data-size="line"> et la LED de défaut s'allumeront avec 5 bips



### _<mark style="background-color:yellow;">**Fonction Bluetooth pour désarmement avec smartphone**</mark>_

Pour utiliser la fonction Bluetooth du clavier afin de désarmer le système via un smartphone, la centrale doit être enregistrée sur le serveur Vesta.\
L'application **SmartHomeSec** est utilisée pour associer le téléphone au clavier en Bluetooth. Jusqu'à **25** smartphones peuvent être couplés au clavier pour désarmer le système via l'application SmartHomeSec.\
Veuillez accéder à l'APP Store ou à Google Play et rechercher **SmartHomeSec** pour télécharger l'application.

* <mark style="color:blue;">**Configuration Bluetooth**</mark>\ <mark style="color:blue;">**Association du clavier avec un smartphone**</mark>\
  **Étape 1.** Le clavier doit avoir son **autoprotection déclenchée**, placez le clavier en **Mode BLE** en appuyant simultanément les touches ＊ et  **0** appuyées pendant **2 secondes**. Lorsque vous entrez en mode BLE, le clavier émet un bip long et les LED verte et orange s'allument pendant l'utilisation du mode BLE.\
  **Étape 2.** Sur votre smartphone, ouvrez l'application **SmartHomeSec**, saisissez l'ID utilisateur et le mot de passe associé, puis appuyez sur Connecter pour vous connecter à votre compte.\
  &#xNAN;_&#x4E;ote:_ Assurez-vous que le Bluetooth soit activé dans les paramètres de votre smartphone.\
  <img src=".gitbook/assets/image (13).png" alt="" data-size="original">\
  **Étape 3.** Accédez à la liste des périphériques, sélectionnez le clavier. Cliquez sur "**Démarrer association Bluetooth**.\
  ![](<.gitbook/assets/image (14).png>)![](<.gitbook/assets/image (15).png>)\
  **Étape 4.** L'application commencera automatiquement à analyser le clavier qui est en mode BLE. Si la recherche ne démarre pas automatiquement, appuyez sur le bouton <img src=".gitbook/assets/image (16).png" alt="" data-size="line"> pour rechercher le clavier.\
  Lorsque le clavier détecté apparaît dans la liste, appuyez dessus pour accéder à la page Code PIN de couplage. Entrez le code PIN de couplage BLE **(Par défaut : 000000)** et appuyez le bouton **Couplage** pour continuer.\
  ![](<.gitbook/assets/image (17).png>)![](<.gitbook/assets/image (18).png>)![](<.gitbook/assets/image (19).png>)\
  &#xNAN;_&#x4E;ote:_ Pour modifier le code PIN de couplage, entrez le code PIN à 6 chiffres suivi de **＊** sur le clavier en mode BLE. Si le paramétrage du code PIN est confirmé, le clavier émet 1 bip long. Si le réglage du code PIN n'est pas confirmé, le clavier émet 4 bips.\
  **Étape 5.** Lorsque la boîte de dialogue Couplage réussi s'affiche sur l'application, le couplage est réussi.\
  Cliquez sur OK et vous serez dirigé vers le menu de configuration du clavier où vous devrez définir votre code utilisateur.\
  ![](<.gitbook/assets/image (20).png>)\
  **Étape 6.** Sélectionnez Code PIN et saisissez un code utilisateur de la centrale à 4 ou 6 chiffres.\
  Si l'utilisateur souhaite quitter cette page mais que le champ PIN utilisateur est vide, le système affichera un message d'erreur.\
  ![](<.gitbook/assets/image (21).png>)![](<.gitbook/assets/image (22).png>)\
  \
  &#xNAN;_**Veuillez noter:**_\
  _**-**_ Lorsque le clavier est en mode BLE, les utilisateurs peuvent coupler le clavier avec un ou plusieurs smartphones. Que le premier smartphone couplé soit connecté ou non, le deuxième smartphone et plusieurs autres peuvent être couplés avec le clavier en suivant les **Étapes 2\~6** dans les instructions ci-dessus.\
  \- Le clavier peut être associé à un maximum de 25 smartphones.\
  \
  **Étape 7.** Quittez le mode BLE en appuyant une fois sur la touche **#**. Sinon, le clavier quittera automatiquement le mode BLE après 5 minutes et reviendra en mode veille.\
  \
  <mark style="color:blue;">**Dissocier un clavier avec un ou plusieurs smartphones**</mark>\
  **Étape 1.** En **mode BLE**, vous pouvez dissocier un ou plusieurs smartphones du clavier.\
  Le clavier doit avoir son **autoprotection déclenchée**,  placez le clavier en **Mode BLE** en appuyant simultanément sur les touches **＊**&#x65;t **0** pendant **2 secondes**. Le clavier émet un bip long et les LED verte et orange s'allument.\
  \- Saisir **0 ou, 1 ou, 2 … 24** puis la touche **#** pour dissocier le 1er, le 2ème, le 3ème,… ou le 25ème smartphone.\
  \- Saisir **25** puis la touche **#** pour dissocier tous les smartphones.\
  **Étape 2.** En plus de dissocier le clavier de votre smartphone, vous devrez également supprimer la fonction Bluetooth du clavier dans votre application.\
  ![](<.gitbook/assets/image (24).png>)\
  **Étape 3.** Ensuite, supprimez le clavier couplé depuis votre smartphone. Naviguez dans le smartphone **Paramètres>Bluetooth>Mes appareils**. Appuyez sur le clavier associé et sélectionnez **Oubliez cet appareil** pour le supprimer de la liste.\
  \
  <mark style="color:blue;">**Désarmer le système via un smartphone**</mark>\
  Pour désarmer le système via un smartphone associé :\
  \- La fonction Bluetooth du smartphone doit être activée et l'application SmartHomeSec doit rester active en arrière-plan afin que l'appareil puisse communiquer avec l'application.\
  \- Un code utilisateur de la centrale à 4 ou 6 chiffres doit avoir été enregistré dans l'application SmartHomeSec.\
  Lorsque le système est armé, approchez-vous du clavier avec un smartphone associé. Une fois que le clavier détecte le smartphone dans la portée BLE, le système se désarme automatiquement.\
  \
  &#xNAN;_&#x4E;ote:_\
  _-_ La portée BLE peut différer selon les différents smartphones.\
  \- Une fois le système armé, un délai de 30 secondes est configuré pour que le smartphone soit hors de portée du clavier BLE. Le clavier commencera à détecter seulement après 30 secondes suite à l'armement. Si le smartphone associé se trouve dans la portée BLE lorsque le système s'arme, le système ne se désarmera pas tant que le délai de 30 secondes ne sera pas écoulé.



### _<mark style="background-color:yellow;">**Temporisation d'entrée/de sortie**</mark>_

* Une fois le son des temporisations d'entrée/de sortie activé en appuyant sur les touches **1** et **2** simultanément pendant 2 secondes (indiqué par un bip long), le clavier émettra des bips lorsque l'une des temporisations sera activée.
* Une fois le son des temporisations d'entrée/de sortie désactivé en appuyant sur les touches **1** et **2** simultanément pendant 2 secondes (indiqué par deux bips courts), restera silencieux pendant les temporisations d'entrée/de sortie.



### _<mark style="background-color:yellow;">**Conditions de défaut**</mark>_

Lorsque le clavier est en **MODE DE FONCTIONNEMENT NORMAL**

1. Lorsqu'un défaut existe dans la centrale, si le clavier est utilisé pour l'armement, la LED de défaut clignotera avec 3 bips pour indiquer une condition de défaut.
2. Lorsque le clavier désarme la centrale, la LED <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252F62JLaNrZYGDMWkpk9sfU%252Fimage.png%3Falt%3Dmedia%26token%3D9bdda193-6b70-4a65-bda5-d3de5b93bf14&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=ee2b4905&#x26;sv=2" alt="" data-size="line"> s'allumera avec deux bips indiquant un fonctionnement normal.
3. Si vous saisissez un code incorrect 4 fois en 10 minutes en mode test, le clavier désactivera les touches pendant 1 minute et toutes les LED clignoteront 3 fois avec 6 bips. Après 1 minute, il émettra un bip long indiquant le retour en mode normal.
4. Si vous saisissez un code incorrect 4 fois en 10 minutes lors d'un changement de mode, le clavier désactivera les touches pendant 5 minutes. Après 5 minutes, le clavier émettra un bip long indiquant le retour en mode normal.

### _<mark style="background-color:yellow;">**Réinitialisation**</mark>_ <a href="#retour-aux-parametres-dusine" id="retour-aux-parametres-dusine"></a>

La réinitialisation du clavier aux paramètres d'usine restaurera le code du clavier à 0000 et effacera les information relative à la centrale.\
&#xNAN;_**Réinitialiser aux paramètres d'usine :**_\
Étape 1: Retirez les piles et relâchez l'autoprotection.\
Étape 2:\
\- Si la fonction "**Armement Total/Partiel avec code**" est sélectionnée, maintenir la touche **3** appuyée en insérant la batterie.\
\- Si la fonction "**Armement Total/Partiel sans code**" est sélectionnée, maintenir la touche **4** appuyée en insérant la batterie.\
Étape 3:\
\- Maintenir la touche **3** jusqu'à ce que le clavier émette 3 bips pour indiquer une réinitialisation réussie.\
\- Maintenir la touche **4** jusqu'à ce que le clavier émette 4 bips pour indiquer une réinitialisation réussie.\
Étape 4: Relâchez la touche **3** ou **4**, le processus de réinitialisation est terminé. Après la réinitialisation, le code revient à la valeur par défaut, "**0000"**. Le clavier aura besoin d'un nouveau processus d'apprentissage pour refonctionner.

* Chaque fois que le clavier est retiré d'une centrale, il doit être également réinitialisé pour effacer la précédente centrale de sa mémoire



### _<mark style="background-color:yellow;">**Montage du clavier**</mark>_ <a href="#montage-du-clavier" id="montage-du-clavier"></a>

Pour monter le clavier :

1. Retirez le capot avant.
2. En utilisant les 2 trous de montage de la coque arrière comme gabarit, marquez les positions à l'endroit le plus approprié.
3. Insérez les chevilles murales si vous fixez sur une surface en plâtre ou en brique.
4. Vissez le clavier dans les chevilles.
5. Replacez le capot avant.
