---
icon: door-open
---

# Danalock avec VESTA

### _<mark style="background-color:yellow;">Introduction</mark>_

Ce document vous guidera étape par étape dans le processus d'installation, d'ajout et d'étalonnage des verrous **SALTO** modèles **SALTO-015** et **SALTO-17** avec une centrale **VESTA** en utilisant la technologie **Z-WAVE**.

{% tabs %}
{% tab title="SALTO-017" %}
<figure><img src="../.gitbook/assets/image (3).png" alt="" width="375"><figcaption><p><a href="https://bydemes.com/es/productos/intrusion/alarma-vesta/dispositivos-z-wave/SALTO-017">SALTO-017</a></p></figcaption></figure>
{% endtab %}

{% tab title="SALTO-15" %}
<figure><img src="../.gitbook/assets/image (1) (1).png" alt="" width="375"><figcaption><p><a href="https://bydemes.com/es/productos/intrusion/alarma-vesta/dispositivos-z-wave/SALTO-015/especificaciones">SALTO-015</a></p></figcaption></figure>
{% endtab %}

{% tab title="SALTO-005" %}
<figure><img src="../.gitbook/assets/image (2) (1).png" alt="" width="375"><figcaption><p><a href="https://bydemes.com/es/productos/intrusion/alarma-vesta/dispositivos-z-wave/SALTO-005">UE Cylinder adapter; SALTO-005</a></p></figcaption></figure>
{% endtab %}
{% endtabs %}

Les verrous SALTO fournissent une solution de contrôle d'accès avancée et sécurisée et l'intégration avec les centrales VESTA vous permet de gérer et de contrôler l'accès en temps réel. Ce manuel est conçu pour simplifié le processus d'installation, vous assurant de prendre rapidement avantage des bénéfices apportés par cette intégration.

### _<mark style="background-color:yellow;">Directives</mark>_

#### <mark style="background-color:green;">**Prérequis**</mark>

* Assurez-vous que votre centrale VESTA dispose du Z-WAVE. Veuillez vous rendre sur le site [bydemes WEB](https://www.bydemes.com) pour vérifier les caractéristiques de votre centrale:&#x20;

{% hint style="warning" %}
Si votre centrale ne possède pas le Z-WAVE, vous pouvez installer le module [VESTA-240](https://bydemes.com/es/productos/intrusion/alarma-vesta/modulos-y-expansores/VESTA-240).
{% endhint %}

* Vérifiez que votre cylindre dispose d'une double débrayage: cela signifie que si vous insérez une clé depuis l'extérieur, il est toujours possible d'ouvrir ou fermer depuis l'intérieur.

{% hint style="info" %}
Si vous avez un cylindre à double débrayage et que vous souhaitez conserver vos clés, vous devrez utiliser l'adaptateur [SALTO-005](https://bydemes.com/es/productos/intrusion/alarma-vesta/dispositivos-z-wave/SALTO-005).&#x20;
{% endhint %}

<figure><img src="../.gitbook/assets/image (3) (1).png" alt=""><figcaption><p><a href="https://danalock.com/Download/262/key-turner-for-danalock-v3-4-manuals/id:LVadaoMcVWAAAAAAAAAE3g/Inst_Guide_KEY_TURNER_ADAPTER_DCSLAE_Euro%20Profile_For_DANALOCK_V3_225741?_gl=1*1a8j53d*_ga*MTg3NjUzNzk3My4xNzI0NDI3MDMz*_up*MQ..*_ga_DKYNTPZRT6*MTcyNDQyNzAzMi4xLjEuMTcyNDQyNzA5MS4wLjAuMA..">Manual Guide to install key adapter</a></p></figcaption></figure>



### _<mark style="background-color:yellow;">**Installation**</mark>_

#### <mark style="background-color:green;">**Montage du verrou**</mark>

{% embed url="https://www.youtube.com/watch?v=U3gK4cPas_g" %}

### _<mark style="background-color:yellow;">**Connexion Z-WAVE**</mark>_

Une fois l'installation terminée et les batteries installées, Il faut enregistrer le verrou dans la centrale VESTA. Le processus d'enregistrement est nécessaire pour associer le verrou à la centrale VESTA et avoir la gestion depuis la centrale.

{% hint style="success" %}
L'option d'**exclusion est très importante** pour être en mesure de laisser le périphérique sans aucune information ni donnée d'association. De cette manière, il peut être ajouté correctement à une centrale VESTA.\
Avant d'ajouter le verrou à une centrale VESTA, il est crucial de réaliser une opération "d'exclusion". Exclure le périphérique assure que toutes données d'une précédente connexion stockées dans le verrou seront effacées. Cette étape permet de faire une reset du verrou, supprimant les anciennes données réseau pour permettre un nouvel ajout (ou "inclusion") dans la centrale VESTA (Noeud Z-WVE de la centrale). Si vous ignorez cette étape, le verrou peut contenir d'anciennes données d'association qui peuvent interférer dans le processus d'ajour et provoquer des problème de connexion.
{% endhint %}

### _<mark style="background-color:yellow;">**Exclusion Z-WAVE**</mark>_

#### Etape 1: Accdez à la configuration de la centrale depuis l'app en mdoe installateur:

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption><p>Installer -> Settings</p></figcaption></figure>

#### Etape 2: Choisir "Périphériques" dans le menu.

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption><p>Installer -> Settings -> Devices</p></figcaption></figure>

#### Etape 3: Choisir ensuite le mode "Exclusion".

<figure><img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F1580875003-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FZJzpNocHhYVmD43GZobR%252Fuploads%252Fgit-blob-57cf8661f10d9a1a81f5c73c9d4b8a9cb1155299%252Fimage%2520%2823%29.png%3Falt%3Dmedia&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=ae3d2057&#x26;sv=1" alt="" width="375"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption><p>Select EXCLUDE</p></figcaption></figure>

#### Etape 4. Cliquez une fois sur le bouton du verrou.

<figure><img src="../.gitbook/assets/image (7).png" alt="" width="375"><figcaption><p>Press button 1 time for Inclusion/exclusion </p></figcaption></figure>



{% hint style="warning" %}
Lorsque le bouton aura été utilisé une fois, <mark style="color:green;">la led verte du verrou clignotera</mark>, avec la centrale en mode exclusion, **patientez pendant 1 minute**. Dans l'app SmartHomeSec, un "?" peut apparaitre dans la fenêtre d'exclusion, c'est normal. Une fois le "?" affiché, fermé la fennêtre d'exclusion.
{% endhint %}

### _<mark style="background-color:yellow;">**Ajout du verrou en Z-WAVE sur VESTA**</mark>_

{% hint style="danger" %}
Il est crucial d'avoir exécuté le mode exclusion avant.
{% endhint %}

**Etape 1:** Dans la liste des périphériques, choisir "Ajouter périphériques":&#x20;

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

**Etape 2:** Cliquez sur le bouton du verrou une fois.

<figure><img src="../.gitbook/assets/image (10).png" alt="" width="375"><figcaption><p>Press button 1 time for Inclusion/exclusion </p></figcaption></figure>



{% hint style="success" %}
Lorsque le bouton aura été utilisé une fois, <mark style="color:green;">la led verte du verrou clignotera</mark>, avec la centrale en mode ajout, **patientez pendant 1 minute**. Dans l'app SmartHomeSec, lorsque le verrou s'affichera, vous pourrez l'ajouter et le contrôler depuis le menu Domotique :tada:
{% endhint %}

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

### _<mark style="background-color:yellow;">**Etalonnage**</mark>_

Pour étalonner le verrou, suivez les étapes suivantes avec attention:

* **Mettre le verrou en position déverrouillée**: Tournez le verrou en position déverrouillée. Si nécessaire, lever la poignée.
* **Etalonnage**: Cliquez sur le **bouton** du verrou **3 fois de suite**. Le verrou se calibrera automatiquement et s'arrêtera en position verrouillée.

<figure><img src="../.gitbook/assets/image (12).png" alt="" width="375"><figcaption><p>Auto-Calibration</p></figcaption></figure>

* **Ajustement de la position déverrouillée**: Tournez le verrou dans la position où il est juste déverrouillé (pas plus loin). Cliquez sur le bouton du verrou une fois.
* **Ajustement de la position verrouillée:** Tournez le verrou dans la position où il est juste verrouillé (pas plus loin). Cliquez sur le bouton du verrou une foi.



{% hint style="success" %}
:tada: **Félicitations!** Votre verrou est installé et prêt à contrôler votre porte automatiquement.
{% endhint %}

{% embed url="https://www.youtube.com/watch?v=sVfnPlKUDag" %}



## Informations supplémentaires

### Danalock V3 - commandes par clics

<figure><img src="../.gitbook/assets/image (13).png" alt="" width="563"><figcaption></figcaption></figure>

### &#x20;Comment changer les batteries?&#x20;

{% embed url="https://www.youtube.com/watch?v=BSEDeONvS2k" %}
