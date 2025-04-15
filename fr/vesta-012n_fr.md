---
icon: circle-chevron-right
---

# VESTA 012N

**KPT-39N-BLE**

## <mark style="color:blue;">**Clavier avec lecteur RFID et Bluetooth**</mark>

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

Étape 1. Mettez la centrale en **Mode d'apprentissage**. Veuillez vous référer au manuel de la centrale.\
Étape 2. Ajoutez le clavier à la centrale.

* **Mode normal**\
  En mode normal, maintenir les touches \* et # appuyées pendant 2 secondes pour transmettre le code d'apprentissage à la centrale.
* **Mode Test**\
  Mettez le clavier en Mode Test en saisissant le code (par défaut :**0000**), puis appuyez la touch&#x65;**＊**. Les trois touches <img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252Fgit-blob-fe25c9957403e3c10f8e9d28f99d7d324e84ba0f%252F10%2520%2813%29.png%3Falt%3Dmedia&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=bf585e9e&#x26;sv=2" alt="" data-size="line"><img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F908378341-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQPulEgH1xZnFX9QnBY0O%252Fuploads%252Fgit-blob-cf49690b317e6f3fb07c55fd84d849931f4c4cae%252F11%2520%289%29.jpeg%3Falt%3Dmedia&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=b5350c2d&#x26;sv=2" alt="" data-size="line"> s'allumeront avec un long bip.\
  Appuyez ensuite sur les touches **\*** et **7** pour transmettre le signal d'apprentissage. Le clavier émettra un bip long.

Étape 3. Reportez-vous au manuel de la centrale pour terminer le processus d'apprentissage. Si l'apprentissage réussit, le clavier émettra 3 bips dès réception du signal d'accusé de réception de la centrale. Si le clavier n'émet pas 3 bips,  veuillez répéter l'étape 2 pour transmettre à nouveau le code d'apprentissage.\
Étape 4. Une fois le clavier enregistrée, mettre la centrale en **Mode** **Test**, maintenez le clavier à l'emplacement souhaité et envoyez le code d'apprentissage à la centrale pour confirmer que l'emplacement se trouve dans la plage de signal de la centrale.



### _<mark style="background-color:yellow;">**Modifier la partition du clavier**</mark>_

* Suivez les instructions ci-dessous pour modifier la partition du clavier dans la centrale:
  1. Utilisez le menu de configuration pour modifier la partition du clavier.
  2. Mettez la centrale en **Mode apprentissage**.
  3. Maintenez les touches **＊** et **#** appuyées pendant 2 secondes pour transmettre le code d'apprentissage à la centrale.



### _<mark style="background-color:yellow;">**Procédure d'ajout/de suppression de badges**</mark>_

Le clavier est capable de transmettre les informations des badges à la centrale et vous pouvez attribuer un code utilisateur et un nom à chaque badge depuis la page web de la central. Les badges peuvent ensuite être utilisés pour contrôler le mode de fonctionnement du système d’alarme via le clavier. Le nombre de badges et de codes utilisateur est géré depuis la page web de la centrale.

1.  _**Ajouter un badge:**_\
    Lors de l'ajout d'un nouveau badge, le clavier doit être en mode normal.\
    Étape 1. Accédez au menu PIN code de la page web de la centrale. Choisir la partition dans laquelle l'utilisateur doit être créé, saisissez un code utilisateur à 4 ou 6 chiffres et un nom d'utilisateur qui seront associés au badge.\


    ![](<.gitbook/assets/17 (8).png>)

    Étape 2.  Une fois le clavier appris dans la centrale, appuyez sur la touche <img src=".gitbook/assets/18 (5).jpeg" alt="" data-size="line"> du clavier. Appliquez le nouveau badge dans la zone de détection du clavier. Le rétroéclairage blanc s'activera accompagné de 4 bips pour indiquer que ce badge n'a jamais été enregistré au système.\
    Étape 3. Cliquez sur le bouton Load du menu PIN code de la page web comme indiqué ci-dessous. L'identifiant du badge s'affichera. Cliquez sur Submit pour sauvegarder la configuration.\


    ![](<.gitbook/assets/19 (11).png>)

    Étape 4. Le badge est ajouté. Vous pouvez utiliser le badge pour armer en mode total/partiel ou désarmer le système. Lorsque le clavier démarre en insérant les piles, la LED orange clignote et le rétroéclairage blanc s'allume. Lorsque la LED est éteinte, attendez 10 secondes pour que le lecteur RFID soit fonctionnel.
2. _**Effacer un badge :**_

Étape 1. Accédez à la page Code PIN sur la page Web du Panneau de configuration.

Étape 2. Supprimez manuellement le numéro de balise et cliquez sur Soumettre.

![](<.gitbook/assets/20 (9).png>)

Étape 3. La balise est effacée.

* _**Mode de programmation**_

**Entrez en mode programmation :**

* Mettez le clavier à distance en mode programmation en entrant le code PIN KP (par défaut :**0000**), puis appuyez\*\*＊\*\*clé. Les trois

Les LED s'allumeront avec un long bip.

3

**Fonctions du mode de programmation :**

* Presse\*\*＊**clé et puis**1\*\*Touche : activez le mode de couplage BLE.
  * Sauf en appuyant sur la touche ＊ puis sur la touche 1 en mode de programmation pour accéder au mode de couplage BLE, l'accès rapide au mode de couplage BLE consiste à appuyer sur la touche ＊ et la touche 0 en même temps pendant 2 secondes sur le clavier en état d'autoprotection.
* Presse\*\*＊**clé et puis**2\*\*Touche — Activer la fonction d'alarme de panique à double touche (1+3)
* Presse\*\*＊**clé et puis**3\*\*Touche — Activer la fonction d'alarme incendie à double touche (4+6)
* Presse\*\*＊**clé et puis**4\*\*Touche — Activer la fonction d'alarme médicale à double touche (7+9)
* Presse\*\*＊**clé et puis**5\*\*clé – Désactiver toutes les fonctions Dual Key (par défaut)
* Presse\*\*＊**clé et puis**6\*\*touche — Modifier le code PIN du clavier
* Presse\*\*＊**clé alors**7\*\*clé - Transmettre le signal d'apprentissage. Le clavier à distance émettra un long bip.
* Presse\*\*＊**clé et puis**8\*\*Touche — Activer la fonction Armement/Accueil sans code PIN utilisateur.

_(Prière de se référer à "**Armement/Accueil sans code PIN du panneau de commande**» pour plus de détails)._

* Presse\*\*＊**clé et puis**9\*\*Touche — Activer Armer/Accueil avec la fonction de code PIN utilisateur du panneau de commande (par défaut).

(_Prière de se référer à "**Arm/Home with Control Panel PIN Code**" pour plus de détails_).

**Quitter le mode de programmation :**

*
  * Appuyez sur la touche Désarmer**deux fois**pour quitter le mode Programmation. Alternativement, le clavier distant quittera automatiquement le mode de programmation après 5 minutes d'inactivité et reviendra en mode veille. Toutes les LED s'éteindront et le clavier émettra un long bip.
* _**System Mode Control**_

Après avoir fini d'apprendre le clavier dans le panneau de commande du système d'alarme, l'utilisateur peut changer le système à l'aide du clavier.

Il existe deux manières d'armer le système.

1. Armement absent/domicile Armez le système en saisissant le code PIN utilisateur du panneau de commande.
2. Armement Absent/Départ Armez le système sans entrer le code PIN utilisateur du panneau de commande. Le désarmement du système nécessite toujours la saisie du code PIN utilisateur du panneau de commande.

**Armement/Accueil avec code PIN du panneau de commande :**

En mode programmation, appuyez sur la touche ＊ puis**9**pour activer la fonction Armement/Accueil avec code PIN utilisateur.

Étiquette NFC. Si le panneau ne présente aucun défaut et que l'armement est réussi, la LED s'allumera en même temps que

un long bip.

étiquette. Si le panneau ne présente aucun défaut et que l'armement est réussi, la LED s'allumera avec 3 bips.

appliquez une étiquette NFC. Si le désarmement réussit, la LED s'allumera avec 2

bips. S'il y a\*\*Mémoire d'alarme,\*\*la LED et la LED de défaut s'allumeront avec 5 bips.

**Armement/Accueil sans code PIN du panneau de commande :**

En mode programmation, appuyez sur la touche ＊ puis**8**Touche pour activer Arm/Home sans fonction de code PIN utilisateur

une marque. Si le désarmement réussit, la LED s'allumera avec 2 bips. S'il y a\*\*Mémoire d'alarme,\*\*le

La LED et la LED de défaut s'allumeront avec 5 bips. (Le désarmement nécessite toujours un code utilisateur du panneau de commande ou une étiquette NFC.)

* _**Fonction Bluetooth pour désarmer le système via un smartphone**_

Pour utiliser la fonction Bluetooth du clavier pour désarmer le système via un smartphone, le panneau de commande doit être enregistré sur Home Portal Server.

\_**Application Vesta Home 5**\_est utilisé pour le couplage Bluetooth du smartphone avec le clavier. Jusqu'à**25**les smartphones peuvent être couplés au clavier pour désarmer le système via l'application Vesta Home 5.

Veuillez accéder à l'APP Store ou à Google Play et effectuer une recherche\_**Vesta Maison 5**\_pour télécharger l'application.

* **Configuration Bluetooth**

**Couplage du clavier avec un ou plusieurs smartphones**

**Étape 1.Dans le clavierétat d'ouverture inviolable**, placez le clavier dans le**Mode de couplage BLE**en appuyant et en maintenant les deux\*\*＊\*\* key and **0**clé ensemble pour**2 secondes**. Lorsque vous entrez dans le mode de couplage BLE, le clavier émet un long bip et les LED verte et orange s'allument pendant le mode de couplage BLE.

**Étape 2.Sur votre smartphone, ouvrez le\_Application Vesta Home 5**\_, saisissez l'ID utilisateur et le mot de passe enregistrés, puis appuyez sur

Connectez-vous pour vous connecter à votre compte.\_Note:\_Assurez-vous que Bluetooth est activé pour les paramètres de votre smartphone.

\*\*Étape 3.\*\*Accédez à la page Tous les appareils, sélectionnez KPT-39N-BLE. Robinet "**Démarrer le couplage Bluetooth**.”

5

\*\*Étape 4.\*\*L'application commencera automatiquement à analyser le clavier qui est en mode de couplage BLE. S'il ne démarre pas

numérisation automatique, appuyez sur le bouton sur l'écran pour rechercher le clavier.

Lorsque le clavier détecté apparaît dans la liste, appuyez dessus pour accéder à la page Code PIN de couplage. Entrez le code PIN de couplage BLE\*\*(Par défaut : 000000)**et appuyez sur**Paire\*\*bouton pour continuer.

\_Note:\_Pour modifier le code PIN de couplage, entrez le code PIN à 6 chiffres et ＊ sur le clavier en mode de couplage BLE.

Si le paramétrage du code PIN est confirmé, le clavier émet 1 bip long. Si le réglage du code PIN n'est pas confirmé, le clavier émet 4 bips.

\*\*Étape 5.\*\*Lorsque la boîte de dialogue Couplage réussi s'affiche sur l'application, le couplage est réussi.

Cliquez sur OK et vous serez dirigé vers la page de configuration de l'appareil KPT où vous devrez définir votre code PIN.

6

\*\*Étape 6.\*\*Sélectionnez Code PIN et saisissez un code PIN utilisateur du panneau de commande à 4 ou 6 chiffres.

Si l'utilisateur souhaite quitter cette page mais que le champ PIN utilisateur est vide, le système affichera un message d'erreur.

_**Veuillez noter:**_

* Lorsque le clavier est en mode de couplage BLE, les utilisateurs peuvent coupler le clavier avec un ou plusieurs smartphones. Que le premier smartphone couplé soit connecté ou non, le deuxième smartphone et plusieurs peuvent être couplés avec le clavier en suivant les instructions**Étape 2\~6**dans les instructions ci-dessus.
* Le clavier peut être associé à un maximum de 25 smartphones.

\*\*Étape 7.**Quittez le mode de couplage BLE en appuyant sur**#\*\*clé une fois. Sinon, le clavier distant quittera automatiquement le mode de couplage BLE après 5 minutes et reviendra en mode veille.

**Dissocier un clavier avec un ou plusieurs smartphones**

**Étape 1.Sous le clavierMode de couplage BLE**, vous pouvez dissocier le clavier d'un ou plusieurs smartphones.

Dans le clavier**état d'ouverture inviolable**, placez le clavier dans le**Mode de couplage BLE**en appuyant et en maintenant les deux\*\*＊**clé et**0**clé ensemble pour**2 secondes\*\*. Le clavier émet un long bip et les LED verte et orange s'allument.

* Presse**0, ou 1, ou 2, … 24**clé et puis\*\*#\*\*clé — pour dissocier le 1er, le 2ème, le 3ème,… ou le 25ème smartphone.
* Presse**25**clé et puis\*\*#\*\*clé - pour dissocier tous les smartphones.

\*\*Étape 2.\*\*En plus de dissocier le clavier de votre smartphone, vous devrez également supprimer la fonction Bluetooth du clavier dans votre application Smartphone.

7

**Étape 3.Ensuite, supprimez le clavier couplé de votre smartphone. Naviguez dans le smartphoneParamètres**>**Bluetooth**>**Mes appareils.Appuyez sur le clavier couplé et sélectionnezOubliez cet appareil**pour le supprimer de la liste des appareils.

* **Désarmer le système via un smartphone**

Pour désarmer le système via un smartphone couplé :

*
  * La fonction Bluetooth du smartphone doit être activée et l'application Vesta Home 5 doit rester active en arrière-plan afin que l'appareil puisse communiquer avec l'application.
  * Un code utilisateur du panneau de commande à 4 ou 6 chiffres doit avoir été enregistré dans l'application Vesta Home 5.

Lorsque le système est armé, approchez-vous du clavier avec le smartphone couplé. Une fois que le clavier détecte le smartphone couplé dans la portée BLE, le système se désarme automatiquement.

_**Note:**_

*
  *
    * La portée BLE effective peut différer selon les différents appareils mobiles.
    * Une fois le système armé, un tampon de 30 secondes est configuré pour que le mobile couplé soit hors de portée du clavier BLE. Le clavier commencera à détecter seulement après que le système soit armé pendant 30 secondes. Si le mobile couplé se trouve dans la portée BLE lorsque le système s'arme, le système ne se désarmera pas tant que le tampon de 30 secondes ne sera pas écoulé.
* _**Son d'entrée/sortie**_
  * Une fois le son d'entrée/sortie activé en appuyant sur**1**touche +**2**en même temps pendant 2 secondes (indiqué par un bip long), le clavier émettra des bips lorsque la minuterie d'entrée/sortie est activée.
  * Une fois le son d'entrée/sortie désactivé en appuyant sur**1**touche +**2**en même temps pendant 2 secondes (indiqué par deux bips courts), le clavier restera silencieux lorsque la minuterie d'entrée/sortie sera activée.
* _**Conditions de panne**_

_Lorsque le clavier distant est sous**MODE DE FONCTIONNEMENT NORMAL,**_

*
  1. Lorsqu'une condition de défaut existe dans le panneau de commande, si le clavier est utilisé pour armer le panneau, la LED de défaut clignotera avec 3 bips pour indiquer une condition de défaut.
  2. Lorsque le clavier désarme le panneau, la LED s'allumera avec deux bips indiquant un fonctionnement normal.
  3. Si vous saisissez un code PIN KP incorrect 4 fois en 10 minutes en mode programmation, KP désactivera la fonction clé pendant 1 minute et toutes les LED clignoteront 3 fois avec 6 bips. Après 1 minute, il émettra un long bip pour indiquer que la fonction de la touche est revenue à la normale.
  4. Si vous saisissez un code PIN utilisateur incorrect 4 fois en 10 minutes lors du changement de mode système, KP désactivera la fonction clé pendant 5 minutes. Après 5 minutes, le clavier émettra un long bip pour indiquer que la fonction des touches est revenue à la normale.
* _**Retour aux paramètres d'usine**_

La réinitialisation du clavier aux paramètres d'usine par défaut restaurera le code PIN du clavier à 0000 et effacera toute la mémoire d'apprentissage du panneau.

_**Réinitialiser aux paramètres d'usine :**_

Étape 1 Retirez les piles et relâchez le dispositif anti-sabotage.

Étape 2 Si «**Armement/Accueil avec code PIN du panneau de commande**" La méthode est sélectionnée, appuyez et maintenez**3**clé tout en insérant la batterie.

.Si "**Armement/Accueil sans code PIN du panneau de commande**" La méthode est sélectionnée, appuyez et maintenez**4**clé tout en insérant la batterie.

Étape 3 Continuez à appuyer**3**jusqu'à ce que KP émette 3 bips pour indiquer une réinitialisation réussie.

.Continuez à appuyer sur la touche 4 jusqu'à ce que KP émette 4 bips pour indiquer une réinitialisation réussie.

Étape 4 : Libération**3**ou 4 touches, le processus de réinitialisation est terminé. Après la réinitialisation, le code PIN revient aux valeurs par défaut d'usine,**0000**.

Le clavier distant aura besoin d'un nouveau processus d'apprentissage pour commencer à fonctionner.

*
  * Chaque fois que le clavier est retiré du panneau de commande, il doit également être réinitialisé aux paramètres d'usine pour effacer la mémoire de son panneau de commande.
* _**Montage du clavier déporté**_

Pour monter le clavier déporté :

1. Retirez le capot avant.
2. En utilisant les 2 trous de montage de la coque arrière comme gabarit, marquez les positions à l'endroit le plus approprié.
   1. Insérez les chevilles murales si vous fixez sur une surface en plâtre ou en brique.

IV. Vissez le clavier déporté sur les chevilles.

V. Remplacez le capot avant.

8
