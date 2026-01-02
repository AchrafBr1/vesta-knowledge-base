---
description: Pour toutes les centrales Vesta (radio, hybride)
icon: screwdriver
---

# Guide des centrales

Bienvenue dans **la base de connaissances pour les centrales VESTA sans fils et hybrides**. Ici, vous trouverez les informations essentielles pour l'installation, la configuration et la maintenance de vos centrales VESTA quelles soient sans fils ou hybrides.

Ce manuel est conçu pour les techniciens, les intégrateurs et les utilisateurs avancés qui ont besoin d'une compréhension détaillée de ces centrales. Il inclus des guides étape par étape, des conseils de dépannage, des informations de compatibilité et les meilleurs pratiques pour optimiser les performances du système.

## GUIDE RAPIDE

## 1. Enregistrement de la centrale et ajout d'un utilisateur

### 1.1 Enregistrement de la centrale en mode Installateur

<table data-view="cards"><thead><tr><th></th><th></th></tr></thead><tbody><tr><td><strong>Etape 1:</strong> Se connecter comme un installateur sur l'app <a href="../../guia-de-usuario-smarthomesec.md">SmartHomeSec</a>.</td><td><img src="../.gitbook/assets/image (9) (1) (2).png" alt="" data-size="original"></td></tr><tr><td><strong>Etape  2:</strong> Cliquez sur le bouton +  (ajouter une centrale).</td><td><img src="../.gitbook/assets/image (10) (1) (2).png" alt="" data-size="original"></td></tr><tr><td><strong>Etape  3:</strong> Saisir l'adresse MAC de la centrale qui se trouve sur l'étiquette de la centrale.</td><td><img src="../.gitbook/assets/image (11) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td></tr></tbody></table>

Une fois la centrale enregistrée en mode Installateur, elle est prête pour la configuration.

{% hint style="danger" %}
La centrale doit être démarrée et connectée à Internet. La centrale doit être enregistrée dans les 15 minutes après son démarrage.
{% endhint %}

{% hint style="success" %}
L'adresse MAC de la centrale se trouve sur une étiquette sur l'un des bords de la centrale. Le champ NOM, devrait contenir une information permettant d'identifier la centrale.
{% endhint %}

### 1.2 Ajout d'un compte Utilisateur

Le compte utilisateur sert à contrôler le système et est destiné à l'utilisateur final. Depuis l'application SmartHomeSec, ce compte permet d'armer, de désarmer et d'effectuer toutes les opérations. Il existe deux types de comptes utilisateurs : Master et Slave.

Le premier compte enregistré sera forcément le compte Master. La principale différence entre les comptes Master et Slave est que le compte Master permet de créer de nouveaux utilisateurs, tandis que le compte Slave ne le permet pas.

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Etape 1:</strong> Se connecter en mode Installateur (code par défaut - 7982).</td><td><img src="../.gitbook/assets/Imagen de WhatsApp 2024-06-02 a las 15.19.19_5e1f9a7f.jpg" alt="" data-size="original"></td><td></td></tr><tr><td><p><strong>Etape 2:</strong> Cliquez sur le bouton Système.</p><p><br><img src="../.gitbook/assets/image (14) (1) (1) (1) (1).png" alt=""></p></td><td></td><td></td></tr><tr><td><strong>Etape 3:</strong> Choisir Liste des comptes.</td><td></td><td><img src="../.gitbook/assets/image (15) (1) (1) (1).png" alt="" data-size="original"></td></tr><tr><td><strong>Etape 4:</strong> Cliquez sur le bouton  +.</td><td></td><td><img src="../.gitbook/assets/image (17) (1) (1) (1).png" alt="" data-size="original"></td></tr><tr><td><strong>Etape 5:</strong> S'il s'agit d'un nouvel utilisateur cliquez sur Créer un compte.</td><td><img src="../.gitbook/assets/image (18) (1) (1) (1).png" alt="" data-size="original"></td><td></td></tr><tr><td><p><strong>Etape 6:</strong> Remplir les informations pour créer le compte.</p><p><img src="../.gitbook/assets/image (19) (1) (1) (1).png" alt="" data-size="original"></p></td><td></td><td></td></tr></tbody></table>



{% hint style="success" %}
L'ajout d'un compte utilisateur est terminé! Pour plus d'informations sur l'utilisation du compte utilisateur, suivre les instructions du guide de l'utilisateur SmartHomeSec.
{% endhint %}

## 2. Ajout et configuration de périphériques

Pour ajouter et configurer un périphérique VESTA sans fils, veuillez suivre les étapes suivantes:

### 2.1 Ajouter une périphérique

**Etape 1:** Se rendre dans le menu de configuration de la centrale en mode Installateur:

<figure><img src="../.gitbook/assets/image (20) (1) (1) (1).png" alt="" width="192"><figcaption><p>Installer -> Settings</p></figcaption></figure>

**Etape 2:** Choisir le menu "Périphériques".

<figure><img src="../.gitbook/assets/image (21) (1) (1) (1).png" alt="" width="190"><figcaption><p>Installer -> Settings -> Devices</p></figcaption></figure>

**Etape 3:** Cliquez sur "Ajouter Périphérique".

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src="../.gitbook/assets/image (23) (1) (1) (1).png" alt="" data-size="original"></td><td></td><td></td></tr><tr><td><img src="../.gitbook/assets/image (24) (1) (1).png" alt="" data-size="original"></td><td></td><td></td></tr></tbody></table>

**Etape 4:** Choisir le type de périphérique à ajouter, ex: Détecteur de mouvement. Restez appuyé sur le bouton d'apprentissage du périphérique jusqu'au clignotement de sa led (consulter le manuel du périphérique pour des instructions détaillées).

**Etape 5**: Suivre les instructions indiquées pour terminer le processus d'apprentissage. La centrale confirmera l'ajout avec succès du périphérique.

<figure><img src="../.gitbook/assets/image (27) (1) (1).png" alt=""><figcaption><p>Bouton d'apprentissage des périphériques VESTA</p></figcaption></figure>

{% hint style="danger" %}
Important! Dans le cas des PIRCAMs et des claviers, l'appui sur la/les touches doit être de 3 à 4 secondes. Pour les autres périphériques, un appui court suffit pour les ajouter.
{% endhint %}

Une fois ajouté, le périphérique radio sera prêt à être utilisé et peut être configuré depuis le même menu. Un exemple de configuration est disponible dans le chapitre suivant.

### 2.2 Configuration d'une zone

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src="../.gitbook/assets/image (28) (1).png" alt="" data-size="original"></td><td></td><td></td></tr><tr><td><img src="../.gitbook/assets/image (30) (1).png" alt="" data-size="original"></td><td></td><td></td></tr><tr><td><img src="../.gitbook/assets/image (31) (1).png" alt="" data-size="original"></td><td></td><td></td></tr></tbody></table>

{% hint style="info" %}
Pour configurer correctement une zone, il est important d'être familiarisé avec les attributs disponibles et de leurs impacts sur le fonctionnement global du système.

Par exemple: Intrusion Intérieur est une zone instantanée et Temporisation d'Entrée est une zone temporisée. Ces attributs sont disponibles dans les modes de fonctionnement (Mode Total, Mode Partiel, Mode Arrêt).
{% endhint %}

## 3. Configuration de la centrale et transmission vers la télésurveillance

### 3.1 Paramètres de sécurité

Cette section indique comment ajuster la **durée de la sirène** en cas d'alarme et permet la configuration des **temporisations d'entrée/de sortie**. Pour identifier plus facilement les options critiques, elle seront indiquées par une cadre <mark style="color:red;">**rouge**</mark>.

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src="../.gitbook/assets/image (1) (2).png" alt="" data-size="original"></td><td>Configuration > Centrale</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (3) (2).png" alt="" data-size="original"></td><td>Configuration > Centrale > Sécurité</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (4) (2).png" alt="" data-size="original"></td><td><ol><li><strong>Durée de la sirène</strong> en cas d'alarme.</li><li>Activer cette option permet de retarder l'envoi des alarme de 30 secondes (<strong>il est recommandé de le laisser sur OFF</strong>).</li><li>Ajustement des <strong>temporisations d'entrée/de sortie</strong></li></ol></td><td></td></tr></tbody></table>

### 3.2 Paramètres de la centrale

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src="../.gitbook/assets/image (1) (2).png" alt="" data-size="original"></td><td>Configuration > Centrale</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (10) (2).png" alt="" data-size="original"></td><td>Configuration > Centrale > Centrale</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (7) (2).png" alt="" data-size="original"></td><td>Polling --> Test vert télésurveilleur</td><td></td></tr></tbody></table>

{% hint style="success" %}
## 🔧 **Paramètres \[Centrale > Centrale]**

**Rapport Perte secteur**\
Délai d'attente avant détection et transmission d'une perte secteur.

**Coupure cloud si perte secteur**\
Si activé, le système entre en mode économie en cas de coupure de courant (la centrale continue à transmettre tous les évènements mais l'app sera déconnectée). "Désactiver" = la centrale sera 100% connectée en cas de perte secteur.

**Rapport brouillage**\
Détection et transmission en cas de brouillage radio  (RF: F1 et SF1).

**Intervalle test cyclique**\
Intervalle de transmission d'un test de présence vers un télésurveilleur.

**Heure test cyclique**\
Heure à laquelle le test cyclique doit être réalisé.&#x20;

**Intervalle test GPRS/LTE**\
Fréquence de test du transmetteur GPRS/LTE.&#x20;

**Intervalle test ETHERNET**\
Idem ci-dessous pour la carte Ethernet.&#x20;

**Arrêt notification état périphérique**\
Si activé, la centrale n'affichera plus l'état des périphériques dans son interface (ouvert/fermé). Cela permet d'économiser des données mobile en cas de système sur carte SIM uniquement.

**Conformité PD6662**\
Norme Européenne pour les système d'intrusion.&#x20;

**Résolution PIRCAMs**\
Qualité de l'image des PIRCAMs.&#x20;

**PIRCAMs extérieur en N\&B**\
Permet ou non l'utilisation des PIRCAMs en noir et blanc, utilise pour les périphériques en extérieur.&#x20;

**Ethernet non utilisé**\
Si activé, ignore les pannes sur le port réseau.

**Rapport panne service (Ethernet)**\
Transmission en cas de perte de connexion vers son serveur.&#x20;

**Surcharge secteur heure redémarrage**\
Si une surcharge est détectée (uniquement pour modèle hybride), la centrale attendra x minutes avant de redémarrer.

**Tolérance zone câblées**\
Tolérance appliquée aux zones câblées avant de générer une alarme.&#x20;

**Désactiver sirène centrale**\
Si activé, la sirène de la centrale est inactive.

**Délai suppression cache DNS**\
Fréquence de mise à jour du domaine si un domaine est utilisé à la place d'une IP. Désactiver = pas de mise à jour.
{% endhint %}

### 3.3 Configuration des codes utilisateurs

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src="../.gitbook/assets/image (20) (1) (1) (1).png" alt="Instalador -> Ajustes" data-size="original"></td><td>Configuration</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (8) (2).png" alt="" data-size="original"></td><td>Configuration > Codes</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (9) (2).png" alt="" data-size="original"></td><td>Ajoutez un nom et un code à chaque utilisateur. Ce code le changement de mode depuis un clavier ou l'application (voir manuel pour plus d'informations). </td><td></td></tr></tbody></table>

### 3.4 Mise à jour de la centrale

Il est essentiel de maintenir la centrale à jour afin de garantir des performances et une sécurité optimales du système. Les mises à jour peuvent contenir des améliorations essentielles, des corrections de bugs et des correctifs de sécurité qui protègent contre les vulnérabilités connues.

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src="../.gitbook/assets/image (1) (2).png" alt="" data-size="original"></td><td>Configuration > Centrale</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (11) (2).png" alt="" data-size="original"></td><td>Centrale > Mise à jour FW</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (12) (2).png" alt="" data-size="original"></td><td>Choisir dans la liste la version la plus récente (le nombre le plus élevé, la lettre la plus élevée).</td><td></td></tr></tbody></table>

{% hint style="info" %}
NOTE:\
En 2G avec une faible couverture réseau, la mise à jour peut prendre jusqu'à 8 minutes.\
En 4G/LTE avec une bonne couverture réseau, la mise à jour peut prendre 3-5 minutes.
{% endhint %}

{% hint style="danger" %}
Une fois la centrale en mode mise à jour, <mark style="color:red;">**ne pas l'éteindre ou la déconnecter**</mark> quelques que soient les circonstances. La centrale redémarrera automatiquement.

ETEINDRE LA CENTRALE PENDANT LA MISE A JOUR PEUT LA RENDRE INOPERANTE.
{% endhint %}



### 3.5 Configuration de la transmission vers la télésurveillance

#### _**Transmission d'évènements**_

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src="../.gitbook/assets/image (13) (2).png" alt="" data-size="original"></td><td>Configuration > Transmissions</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (14) (2).png" alt="" data-size="original"></td><td>Dans le menu transmission, nous avons la transmission des événements et des images PIRCAMS.</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (15) (2).png" alt="" data-size="original"></td><td>Dans ce menu, nous configurons l'URL du télésurveilleur et surtout le GROUPE 2 ou supérieur, car le groupe 1 est utilisé pour l'APP. Voir ANNEXE 1 pour plus d'exemples.</td><td></td></tr></tbody></table>

#### ANNEXE 1

{% hint style="success" %}
Exemples de transmission d'**EVENEMENTS** dans différents protocoles:

**MANITOU (le plus utilisé en Espagne): ip://**<mark style="color:blue;">**ACCT**</mark>**@**<mark style="color:orange;">**IP**</mark>**:**<mark style="color:purple;">**PORT**</mark>**/MAN**

SIA: **ip://**<mark style="color:blue;">**ACCT**</mark>@<mark style="color:orange;">**IP**</mark>**:**<mark style="color:purple;">**PORT**</mark>/SIA2

CID: **ip://**<mark style="color:blue;">**ACCT**</mark>@<mark style="color:orange;">**IP**</mark>**:**<mark style="color:purple;">**PORT**</mark>/CID
{% endhint %}

Dans cette section, vous trouverez les protocoles de communication standard supportés par les centrales VESTA pour signaler directement les événements au télésurveilleur.\
Ces protocoles permettent à la centrale d'envoyer tous les ÉVÉNEMENTS, à l'exception des photos, sans avoir besoin de convertisseurs ou d'outils supplémentaires.

Si votre télésurveilleur utilise **l'un de ces protocoles** standard (tels que **MANITOU XML**, **SIA DC09** ou **Contact ID**), la centrale peut être configurée pour envoyer directement les rapports dans le format approprié.

{% hint style="warning" %}
Si votre télésurveilleur **ne supporte aucun des protocoles standard**, veuillez vous rendre à la section [ALARMSPACE](guide-des-centrales.md#id-3.1-parametres-de-securite) ci-dessous, qui explique comment intégrer des systèmes non standard à l'aide du logiciel de traduction VESTA.
{% endhint %}

{% hint style="info" %}
## Autres exemples: Configuration des URLs de transmission

Les URLs de transmission sont utilisées par l'installateur pour programmer les destinataires des évènements du système d'alarme

### Formats supportés

#### 1. CID via IP

**Format:** `ip://(Account Number)@(Server IP):(Port)/CID`\
**Exemple:** `ip://1234@54.183.182.247:8080/CID`

#### 2. SIA DC-09 via IP

**Format:** `ip://(Account Number)@(Server IP):(Port)/SIA2`\
**Exemple:** `ip://1234@54.183.182.247:8080/SIA2`

#### 3. SIA DC-09 via IP avec chiffrage AES

**Format:** `ip://(Account Number)@(Server IP):(Port)/SIA/KEY/(128, 192, or 256-bit Key)`\
**Exemple:** `ip://1234@54.183.182.247:8080/SIA/KEY/4A46321737F890F654D632103F86B4F3`

#### 4. SIA DC-09 utilisant les codes évènement CID via TCP IP (encapsulation)

**Format:** `ip://(Account Number)@(Server IP):(Port)/CID_SIA2`\
**Exemple:** `ip://1234@54.183.182.247:8080/CID_SIA2`

#### 5. SIA DC-09 utilisant les codes évènement CID via IP avec chiffrage HEX

**Format:** `ip://(Account Number)@(Server IP):(Port)/CID_SIA/KEY/(HEX Key)`\
**Exemple:** `ip://1234@54.183.182.247:8080/CID_SIA/KEY/4A46321737F890F654D632103F86B4F3`

#### 6. CSV via IP

**Format:** `ip://(Account Number)@(Server IP):(Port)/CSV`\
**Exemple:** `ip://1234@54.183.182.247:8080/CSV`

#### 7. CSV via IP avec authentification

**Format:** `ip://(Account Number)@(Server IP):(Port)/CSV/Username/Password`\
**Exemple:** `ip://1234@54.183.182.247:8080/CSV/abcd/1357`

#### 8. Email

**Format:** `mailto:user@example.com`\
**Exemple:** `mailto:john@gmail.com`



### Filtres

Choisir le type de filtre à appliquer par destinataires:

* **Tous les évènements:** Le système transmettra tous les évènements.
* **Evènements d'alarme:** Le système transmettra uniquement les évènements d'alarme.
* **Evènements d'état:** Le système transmettra uniquement les évènements (hors alarme)



### Configuration des groupes

Choisir un groupe de transmission pour votre destinataire. Le système suivra le principe de transmission suivant:

#### Structure des priorités

Les groupes sont classées dans l'ordre de priorité suivant: Groupe 1 → Groupe 2 → Groupe 3, etc.

#### Logique de transmission

1. **Dans un groupe:** Si la transmission vers le premier destinataire du groupe échoue, le système passera vers le prochain destinataire du même groupe.
2. **Succès groupe:** Si l'un des destinataires d'un groupe reçoit avec succès la transmission alors, le système considère que la transmission pour ce groupe est un succès et passe au groupe suivant.
3. **Echec groupe:** Si tous les destinataires sont en échec de transmission, le système effectue une nouvelle tentative conformément aux paramètres ci-dessous.
4. **Achèvement du cycle:** Après avoir essayé tous les groupes (Groupe 1 → Groupe 2 → ... → Groupe 5), si un groupe essentiel est en échec de transmission, le système redémarre le cycle de transmission.



#### Groupe Essentiel vs Optionnel

**Essentiel:**

* Le système transmettra à tous les groupes configurés comme Essentiels.
* Le système n'arrête jamais de transmettre jusqu'à ce qu'un groupe Essentiel ait acquitté correctement la transmission.
* Le Groupe 1 est toujours en Essentiel et ne peut être modifié.

**Optionnel:**

* Le système transmet seulement aux groupes Optionnels en cas d'échec sur les groupes précédents.
* Exemple: Si le Groupe 3 est en Optionnel, le système ne transmettra qu'au Groupe 3 si le Groupe 2 est en échec.

#### Tentatives

Choisir entre 1, 3, 5, 10, ou 99 tentatives.

Si la tentative de transmission vers tous les destinataires d'un groupe échoue, le système tentera de transmettre à nouveau à ce groupe selon le nombre de tentative configuré.



### Notes Importantes

⚠️ **Transmission vers l'app VESTA SmartHomeSec:**

* Lorsque la centrale est enregistrée avec l'app VESTA, l'URL 1 sera automatiquement configurée avec les information du serveur.
* **Ne modifiez pas** ces informations après l'enregistrement complet de la centrale ou la transmission vers le serveur peut échouer.
* Si vous avez besoin d'autres destinataires après le serveur, configurez les en utilisant un **groupe différent** de celui de l'URL 1 pour assurer le bon fonctionnement de la transmission.
{% endhint %}

#### 3.5.1 Utilisation du logiciel ALARMSPACE comme passerelle pour les protocoles  de communication non normalisés

Dans le cas ou le télésurveilleur ne supporterait pas l'un des protocoles listés ci-contre (MANITOU, XML, SIA DC09, CID, etc.), **VESTA dispose d'une solution sous forme de passerelle avec le logiciel ALARMSPACE.**

<figure><img src="../.gitbook/assets/image (48).png" alt=""><figcaption><p>ALARMSPACE</p></figcaption></figure>

**ALARMSPACE** fonctionne comme un traducteur entre la centrale VESTA et le télésurveilleur, convertissant les évènements VESTA dans le format attendu par le télésurveilleur. Cela assure une compatibilité complète même en cas d'utilisation d'un protocole propriétaire ou personnalisé par le télésurveilleur.

Le logiciel ALARMSPACE peut être installé sur n'importe quelle **base PC Windows** ou **machine virtuelle** dans l'infrastructure du télésurveilleur.

{% hint style="success" %}
Pour l'installation, veuillez contacter votre représentant VESTA.
{% endhint %}

### 3.6 Transmission d'images

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src="../.gitbook/assets/image (13) (2).png" alt="" data-size="original"></td><td>Configuration > Transmission</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (14) (2).png" alt="" data-size="original"></td><td>Dans le menu transmission, nous avons la transmission des événements et des images PIRCAMS.</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (16) (1) (1) (1).png" alt="" data-size="original"></td><td>Dans cette section nous configurons l'URL d télésurveilleur pour l'envoi d'images destinataire.</td><td></td></tr></tbody></table>

{% hint style="success" %}
Exemples de configuration avec différents protocoles:

:fire: **MANITOU**: <mark style="color:blue;">**ACCT**</mark>**@**<mark style="color:orange;">**IP**</mark>**:PORT**

**SMTP: Utilisez l'adresse e-mail du télésurveilleur**

**HTTP: Envoi d'image Http en base64**
{% endhint %}

#### _3.6.1 Transmission d'images pour le logiciel SENTINEL_

{% hint style="info" %}
Etape 1: Programmez le SMTP dans Configuration > Transmission&#x20;
{% endhint %}

<figure><img src="../.gitbook/assets/image (49).png" alt=""><figcaption><p>Exemple SMTP</p></figcaption></figure>

{% hint style="info" %}
Etape 2: Programmez l'e-mail fourni par le télésurveilleur dans le menu "Transmission d'images"
{% endhint %}

<figure><img src="../.gitbook/assets/image (50).png" alt=""><figcaption></figcaption></figure>



{% hint style="warning" %}
**IMPORTANT:** Si vous utilisez des caméras intégrées avec VESTA, vous devrez réduire la résolution à 2MP ou moins pour un fonctionnement correct.
{% endhint %}

## Domotique

La centrale dispose de fonctions de domotique avancées qui offrent un niveau très élevé de fonctionnalités conçues pour maximiser la sécurité du système. Ces fonctionnalités permettent, par exemple, de créer des règles selon lesquelles l'ouverture d'un détecteur d'ouverture déclenche automatiquement la capture d'une image ou l'activation d'un relais pour ouvrir ou fermer des circuits spécifiques. Ces capacités améliorent non seulement l'efficacité du système, mais permettent également d'apporter une réponse rapide et appropriée aux événements de sécurité.

{% hint style="success" %}
**Nombre de règle et de scénarios qui peuvent être créés:**<br>

* Règles: 100
* Scénarios: 50



Plus d'informations: [Scénarios et règles du système d'alarme VESTA](https://vestasecurity.eu/en/scenes-and-automatic-rules-of-the-vesta-alarm-system/) (anglais)
{% endhint %}

## Manuels Complets (Anglais)

<figure><img src="../.gitbook/assets/image (51).png" alt="" width="113"><figcaption><p>Hybrid Grade 3</p></figcaption></figure>

{% file src="../.gitbook/assets/Hybrid Panel-1_Installation Guide.pdf" %}

<figure><img src="../.gitbook/assets/image (52).png" alt="" width="113"><figcaption><p>Hybrid Lite</p></figcaption></figure>

{% file src="../.gitbook/assets/Hybrid Panel Lite 2G 4G _Installation Guide.pdf" %}

<figure><img src="../.gitbook/assets/image (53).png" alt="" width="113"><figcaption><p>Radio</p></figcaption></figure>

{% file src="../.gitbook/assets/HSGW-MAX8-DT18-SF1-DUAL 20220811.pdf" %}







