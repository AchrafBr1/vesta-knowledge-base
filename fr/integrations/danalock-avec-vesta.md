---
hidden: true
icon: door-open
---

# Danalock avec VESTA

### _<mark style="background-color:yellow;">Introduction</mark>_

Ce document vous guidera étape par étape dans le processus d'installation, d'ajout et d'étalonnage des verrous **SALTO** modèles **SALTO-015** et **SALTO-17** avec une centrale **VESTA** en utilisant la technologie **Z-WAVE**.

{% tabs %}
{% tab title="SALTO-017" %}
<figure><img src="../.gitbook/assets/image.png" alt="" width="375"><figcaption><p><a href="https://bydemes.com/es/productos/intrusion/alarma-vesta/dispositivos-z-wave/SALTO-017">SALTO-017</a></p></figcaption></figure>
{% endtab %}

{% tab title="SALTO-15" %}
<figure><img src="../.gitbook/assets/image (1).png" alt="" width="375"><figcaption><p><a href="https://bydemes.com/es/productos/intrusion/alarma-vesta/dispositivos-z-wave/SALTO-015/especificaciones">SALTO-015</a></p></figcaption></figure>
{% endtab %}

{% tab title="SALTO-005" %}
<figure><img src="../.gitbook/assets/image (2).png" alt="" width="375"><figcaption><p><a href="https://bydemes.com/es/productos/intrusion/alarma-vesta/dispositivos-z-wave/SALTO-005">UE Cylinder adapter; SALTO-005</a></p></figcaption></figure>
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

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption><p><a href="https://danalock.com/Download/262/key-turner-for-danalock-v3-4-manuals/id:LVadaoMcVWAAAAAAAAAE3g/Inst_Guide_KEY_TURNER_ADAPTER_DCSLAE_Euro%20Profile_For_DANALOCK_V3_225741?_gl=1*1a8j53d*_ga*MTg3NjUzNzk3My4xNzI0NDI3MDMz*_up*MQ..*_ga_DKYNTPZRT6*MTcyNDQyNzAzMi4xLjEuMTcyNDQyNzA5MS4wLjAuMA..">Manual Guide to install key adapter</a></p></figcaption></figure>



### _<mark style="background-color:yellow;">**Installation**</mark>_

#### <mark style="background-color:green;">**Montage du verrou**</mark>

{% embed url="https://www.youtube.com/watch?v=U3gK4cPas_g" %}

### _<mark style="background-color:yellow;">**Connexion Z-WAVE:**</mark> <mark style="background-color:yellow;"></mark> <mark style="background-color:yellow;"></mark><mark style="background-color:yellow;">Procédure d'ajout dans une centrale VESTA via Z-WAVE.</mark>_

Once the installation is complete and the batteries are installed, we are going to proceed with the registration in VESTA.\
After you have physically installed the SALTO lock and inserted the batteries, the next step is to register the lock with the VESTA panel. This registration process is necessary to link the lock to the VESTA system so that it can be managed and controlled through the panel.

{% hint style="success" %}
This **exclude option is very important** to be able to leave the device without information and registration data, so that it can be correctly added to the VESTA coordinator.\
Before adding the lock to the VESTA system, it’s crucial to perform an “exclude” operation. Excluding the device ensures that any previous connection data or registration information stored on the lock is erased. This step essentially resets the lock, removing any old network data, so it’s ready to be correctly added (or "included") to the VESTA coordinator (the central Z-WAVE hub). If you skip this step, the lock might have leftover data that could interfere with the new registration process, leading to connection issues.
{% endhint %}

### **Exclude Z-WAVE DANALOCK**

#### Step 1: Access the panel configuration from the installer APP:

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption><p>Installer -> Settings</p></figcaption></figure>

#### Step 2: Select "Devices" in the menu.

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption><p>Installer -> Settings -> Devices</p></figcaption></figure>

#### Step 3: In the menu click "Exclude device".

<figure><img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F1580875003-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FZJzpNocHhYVmD43GZobR%252Fuploads%252Fgit-blob-57cf8661f10d9a1a81f5c73c9d4b8a9cb1155299%252Fimage%2520%2823%29.png%3Falt%3Dmedia&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=ae3d2057&#x26;sv=1" alt="" width="375"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption><p>Select EXCLUDE</p></figcaption></figure>

#### Step 4. Now click once on the lock button.

<figure><img src="../.gitbook/assets/image (7).png" alt="" width="375"><figcaption><p>Press button 1 time for Inclusion/exclusion </p></figcaption></figure>



{% hint style="warning" %}
Once the lock button has been pressed only once, <mark style="color:green;">Danalock led is green blinking</mark>, and the panel is in exclusion mode, **wait for 1 minute**. In the SmartHomeSec APP a question "?" mark may appear in the exclusion box, this is normal. once it appears close the exclusion window.
{% endhint %}



### **Add Z-WAVE DANALOCK in VESTA**

{% hint style="danger" %}
It is crucial to have made the [exclusion ](danalock-avec-vesta.md#exclude-z-wave-danalock)before
{% endhint %}

**Step 1:** In device list of SmartHomeSec, choose Add device:&#x20;

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

#### Step 2. Now click once on the lock button.

<figure><img src="../.gitbook/assets/image (10).png" alt="" width="375"><figcaption><p>Press button 1 time for Inclusion/exclusion </p></figcaption></figure>



{% hint style="success" %}
Once the lock button has been pressed only once, <mark style="color:green;">Danalock led is green blinking</mark>, and the panel is in adding mode, **wait for 1 minute**. In the SmartHomeSec APP you will see the doorlock, add It and you can control it from automations :tada:
{% endhint %}

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

### **Calibration**

To calibrate your Danalock, follow these steps carefully:

* **Set the Danalock to the Unlocked Position**: Turn the Danalock to the unlocked position. If necessary, lift the handle.
* **Start Calibration**: Click the **button** on the **Danalock 3 times**. The lock will automatically calibrate and stop in the locked position.

<figure><img src="../.gitbook/assets/image (12).png" alt="" width="375"><figcaption><p>Auto-Calibration</p></figcaption></figure>

* **Adjust to the Unlocked Position**: Turn the Danalock to the position where it is just unlocked (not further). Click the button on the Danalock once.
* **Adjust to the Locked Position**: Turn the Danalock to the position where it is just locked (not further). Click the button on the Danalock once.



{% hint style="success" %}
:tada: **Congratulations!** Your lock is installed and ready to control your door automatically.
{% endhint %}

{% embed url="https://www.youtube.com/watch?v=sVfnPlKUDag" %}



## Extra information

### Danalock V3 click commands

<figure><img src="../.gitbook/assets/image (13).png" alt="" width="563"><figcaption></figcaption></figure>

### &#x20;How to change battery?&#x20;

{% embed url="https://www.youtube.com/watch?v=BSEDeONvS2k" %}
