---
icon: video
---

# Gamme Vesta Advanced (avec SmartHomeSec) (FR)

## Etes-vous prêt à découvrir la nouvelle gamme de caméras VESTA ADVANCED?

{% embed url="https://drive.google.com/file/d/1snvNV-L2JUDdsPN4qwz1_Xb32DzoiepE/view?usp=sharing" %}

### Qu'est-ce que cette intégration VESTA apporte?

<figure><img src="../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

### Démarrage avec la centrale VESTA en 3 étapes

{% stepper %}
{% step %}
### Mise à jour de la caméra IP ([vidéo rapide](gamme-vesta-advanced-avec-smarthomesec-fr.md#videos-rapides))

Pour mettre à jour la caméra, suivre les étapes suivantes:

1.  **Téléchargement du firmware**: Assurez-vous d'avoir téléchargé le firmware qui correspond à votre modèle de caméra depuis la liste ci-dessous:<br>

    [**Téléchargement**](/broken/pages/mAPTavYKheZkaX25IPPQ)<br>
2. [**Accéder à l'interface locale**](gamme-vesta-advanced-avec-smarthomesec-fr.md#connexion-a-linterface-locale): Se connecter à l'interface web locale de la caméra (IP par défaut: _192.168.1.86_).
3. **Se rendre dans la configuration**: Cliquez sur le menu "Setup".
4. **Se rendre dans le menu Système**: Cliquez sur "System'.
5. **Se rendre dans le menu Mise à jour**: Cliquez sur "Upgrade" et sélectionnez le fichier précédemment téléchargé pour démarrer le processus de mise à jour.

<figure><img src="../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Mise à jour centrale et application SmartHomeSec

{% hint style="info" %}
Il est important de s'assurer que la **centrale utilise  la version** **34F ou plus** et que l'**application soit en version 3.6.0 ou plus**. Ces mises à jour disposent de l'intégration. Vérifiez et mettez à jour régulièrement vos périphériques pour conserver la compatibilité et maintenir une performance optimale.
{% endhint %}
{% endstep %}

{% step %}
### Ajouter une caméra à la centrale

1. **Vérification réseau:** Assurez-vous que la caméra et le centrale VESTA soient connectées sur le même réseau.
2. **Configuration app SmartHomeSec:**
   * Ouvrir l'app et se connecter avec le **compte utilisateur maître**.
   * Se rendre dans le menu "**Caméras**" et choisir l'option "**VESTA ADVANCED**."
3. **Recherche de caméra:**
   * Le système commencera à **scanner le réseau pour trouver les nouvelles caméras automatiquement**.
4. **Choix de la caméra:**
   * Choisir l'une des caméras de la liste et saisir **l'identifiant et le mot de passe**. Utilisez les mêmes identifiants que ceux utilisés lors de la connexion à l'interface web locale de la caméra.
{% endstep %}
{% endstepper %}

<figure><img src="../.gitbook/assets/ADV-settings.gif" alt=""><figcaption></figcaption></figure>

## Vidéos rapides

### - Comment mettre à jour une caméra ou un NVR VESTA ADV - Etape par étape

{% embed url="https://www.youtube.com/watch?v=Y9w5Lkq4Zjg" %}

### - Comment configurer les règles IVS sur les caméras VESTA ADV&#x20;

Les règles de **vidéosurveillance intelligente (IVS)** sont des algorithmes avancés d'analyse vidéo utilisés pour améliorer les fonctionnalités de votre caméra VESTA ADV ou de votre NVR. Ces règles permettent au système de détecter automatiquement certains événements et d'y réagir, ce qui améliore la sécurité et réduit les fausses alarmes. Les règles IVS courantes comprennent :

1. **Détection d'intrusion :** alerte lorsqu'un objet/une personne pénètre dans une zone prédéfinie.
2. **Tripwire :** se déclenche lorsqu'un objet/une personne franchit une ligne définie..
3. **Cross region :** Se déclenche lorsqu'un objet/humain traverse ou apparaît dans une zone définie..

Pour programmer les règles IVS dans votre système VESTA ADV, procédez comme suit:&#x20;

{% embed url="https://www.youtube.com/watch?v=jQ_gjPbs73A" %}

### - Comment configurer l'enregistrement continu sur la carte MicroSD de la caméra IP:

1. **Configuration du stockage:**
   * Se rendre dans le menu "**Storage**".
   * Cliquez sur "Destination" et assurez-vous que "**Schedule**" soit activé.
   * Dans "**Schedule**" assurez-vous tout soit activé 24/7 ou sur les jours désirés.

<figure><img src="../.gitbook/assets/step-step-SD.gif" alt=""><figcaption></figcaption></figure>

### **Connexion à l'interface locale:**&#x20;

{% hint style="success" %}
**Etape 1:** Ouvrir un navigateur, saisir l'adresse IP de la caméra dans la barre d'adresse (par défaut **192.168.1.86**) puis valider.

**Etape 2:** Saisir l'identifiant et le mot de passe, **l'identifiant pas défaut est “admin”**.

![](<../.gitbook/assets/image (44).png>)

**Etape 3:** Lorsque vous vous connectez pour la première fois, la caméra affichera une demande de changement mot de passe. Veuillez saisir un mot de passe pour le compte administrateur et le conserver.

![](<../.gitbook/assets/image (45).png>)



**Reset du mot de passe:** Si l'utilisateur oublie le mo de passe, cliquez sur Reset Password pour obtenir une clé. Une fois cette clé envoyé à nos techniciens, une nouvelle clé de décodage sera générée pour l'utilisateur et le **mot de passe** sera forcé à sa valeur **par défaut** **“123456”.**
{% endhint %}

### Gamme VESTA ADVANCED manuel complet (anglais)

{% file src="../.gitbook/assets/VESTA Advanced Series .doc" %}

### Guide rapide (anglais)

{% file src="../.gitbook/assets/Quickly User Manual v25.pdf" %}

***

### Dépannage caméra et Problèmes de configuration

#### Erreur Activation CGI

<figure><img src="../.gitbook/assets/image (56).png" alt=""><figcaption></figcaption></figure>

Si la centrale vous invite à activer le CGI sur la caméra (alors que le CGI est déjà activé), cela peut être dû à des modifications apportées aux paramètres utilisateur. Cela peut se produire si :

* Un client a modifié manuellement les paramètres utilisateur de la caméra (modification des droits d'administrateur).
* La caméra a été ajoutée à un enregistreur tiers, qui l'a initialisée d'une manière qui a modifié les données utilisateur.

**Solution :**\
Réinitialisez la caméra aux paramètres d'usine. Après la réinitialisation, la caméra fonctionnera correctement.\
(Remarque : ce problème est généralement lié à des modifications des paramètres utilisateur).
