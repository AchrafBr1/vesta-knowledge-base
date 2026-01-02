---
icon: puzzle-piece
---

# Caméras IP Dahua avec VESTA (FR)

<figure><img src="../.gitbook/assets/dhlogo.png" alt="" width="375"><figcaption></figcaption></figure>

{% hint style="success" %}
### 🎯 Synchronisation des captures avec l'alarme – Caméras Dahua de Série 3

VESTA peut désormais afficher la **capture exacte** prise par les caméras Dahua de Série 3 au moment même où **un événement IVS est déclenché**, tel qu'un franchissement de ligne ou une détection d'intrusion.

Pour que cela fonctionne, une configuration simple est nécessaire côté caméra. Une fois celle-ci effectuée, vous obtiendrez **une confirmation visuelle en temps réel à 100 %** de la cause de l'alarme, entièrement intégrée à l'écosystème VESTA.

Ce guide explique comment configurer votre caméra Dahua afin que:

* 📷 Elle capture et stocke les images réelles des événements IVS.
* 🔄 VESTA reçoive automatiquement ces images à chaque alarme.

Commençons. 👇
{% endhint %}

## Synchronisation des captures avec l'alarme – Caméras Dahua de Série 3

Pour vous assurer que VESTA reçoit la capture réelle de l'événement exactement au moment où une alarme IVS est déclenchée (franchissement de ligne, intrusion dans une zone, etc.), suivez ces étapes simples :

{% stepper %}
{% step %}
#### Etape 1 – Mettre à jour le firmware de la caméra

Assurez-vous que la caméra Dahua dispose du firmware suivant.

<a href="https://drive.google.com/file/d/1zkh94OKpVQYT1qfo-vdXhGA5WtnERrT5/view?usp=drive_link" class="button primary" data-icon="down-to-bracket">Téléchargez le firmware</a>
{% endstep %}

{% step %}
#### Etape 2 – Insérez une carte microSD

Insérez une carte **microSD** dans la caméra (_il s'agit de l'emplacement où l'image réelle sera enregistrée_).
{% endstep %}

{% step %}
#### Etape 3 – Activez les captures dans l'IVS

* Se rendre dans les **paramètres IVS** de la caméra.
* Editez chaque règles (Franchissement de ligne, Intrusion, etc.).
* Activez la fonction **“Capture instantanée”** pour chaque règle.

Cela permet à la caméra d'enregistrer une image réelle lorsqu'un événement est déclenché.
{% endstep %}
{% endstepper %}

<figure><img src="../.gitbook/assets/IVS.png" alt="" width="375"><figcaption><p>Première image dans le système VESTA</p></figcaption></figure>

***

### Modèles compatibles (Séries 3)

* DAHUA-4670 - DH-IPC-HFW3449T1P-AS-PV-0280B-S5-Black
* DAHUA-4558 - DH-IPC-HDW3849HP-AS-PV-0280B-S5-B
* DAHUA-4297N - DH-IPC-HDW3449HP-AS-PV-0280B-S5-B
* DAHUA-4667 - DH-IPC-HFW3549T1P-AS-PV-0280B-S5
* DAHUA-4547 - DH-IPC-HFW3849T1P-AS-PV-0280B-S5-B
* DAHUA-4543 - DH-IPC-HDW3549HP-AS-PV-0280B-S5-BLACK
* DAHUA-4454 - DH-IPC-HDW3549HP-AS-PV-0280B-S5
* DAHUA-4436 - DH-IPC-HFW3849T1P-AS-PV-0280B-S5
* DAHUA-4401 - DH-IPC-HFW3449T1P-AS-PV-0280B-S5
* DAHUA-4400 - DH-IPC-HDW3849HP-AS-PV-0280B-S5
* DAHUA-4399 - DH-IPC-HDW3449HP-AS-PV-0280B-S5
* DAHUA-4602 - DH-IPC-HFW3449T1-ZAS-PV-27135-S5-B
* DAHUA-4606 - DH-IPC-HDBW3849R1P-ZAS-PV-27135-S5
* DAHUA-4588 - DH-IPC-HDBW3449R1P-ZAS-PV-27135-S5
* DAHUA-4457 - DH-IPC-HFW3849T1P-ZAS-PV-27135-S5
* DAHUA-4386 - DH-IPC-HDW3549HP-ZAS-PV-27135-S5
* DAHUA-4766-FO - DH-IPC-HDBW3549R1P-ZAS-PV-27135-S5
* DAHUA-4561 - DH-IPC-HDW3449HP-ZAS-PV-27135-S5-Black
* DAHUA-4560 - DH-IPC-HDW3849HP-ZAS-PV-27135-S5-Black
* DAHUA-4557 - DH-IPC-HFW3449T1P-ZAS-PV-27135-S5-BLACK
* DAHUA-4455 - DH-IPC-HFW3449T1P-ZAS-PV-27135-S5
* DAHUA-4453 - DH-IPC-HDW3449HP-ZAS-PV-27135-S5
* DAHUA-4116N - DH-IPC-HDW3849HP-ZAS-PV-27135-S5

{% hint style="info" %}
D'autres modèles de la série 2 seront ajoutés à la mi-août.
{% endhint %}

***

Intégration **DAHUA**:

### **Si la caméra dispose de la fonction désarmement**

\- La centrale Vesta sera en mesure de contrôler l'armement et le désarmement de la caméra. Dans ce cas, les asservissements sonores et lumineux de la caméra pourront déclencher en fonction de l'état de la centrale.

\- L'activation de l'alarme et les capture fonctionneront normalement.

### **Si la caméra ne dispose pas de la fonction désarmement**

\- Dans ce cas, le contrôler des asservissement de la caméra est perdu donc ils seront en permanence actifs. Même si la centrale Vesta est désarmé, les asservissement sonores et lumineux seront constamment actifs car la centrale ne peut pas les contrôler.

\- Les fonctionnalités de la caméra sont les mêmes que la centrale soit armée ou non.

### **Délai de capture d'image**

Le délai de capture correct est entre 1 et 3 secondes. Un délai de capture d'environs 5 secondes ou plus indique un ralentissement dans le réseau.

Un moyen pratique pour déterminer ce délai consiste à exécuter  une requête HTTP pour prendre une photo. La commande est la suivante: http://user:password@CAMERA\_IP/cgi-bin/snapshot.cgi?

Exemple: http://admin:Admin1234@192.168.10.182/cgi-bin/snapshot.cgi?

### **P2P Caméra Dahua**

Avec SmartHomeSec, il st possible d'ajouter une caméra à une zone de la centrale à l'aide de son numéro de série (P2P ID). Cela permettra aux utilisateurs maîtres ou esclaves avec permission de visualiser le live depuis l'application. Donc, il est essentiel d'ajouter d'abord la caméra dans la centrale VESTA puis, si un enregistrement vidéo est requis, de l'intégrer via son adresse IP dans l'enregistreur Dahua. L'enregistrement peut également être local en utilisant une carte micro SD dans la caméra directement.

{% hint style="info" %}
NOTE:

L'intégration Vesta/Dahua ne fonctionne qu'avec les photos, pas les vidéos. Le réglage correspondant doit être réalisé sur la zone utilisée par la caméra.
{% endhint %}

### **Durée entre deux alarmes**

Pour une vérification correcte, il y a un délai de 3 minutes entre les détections.
