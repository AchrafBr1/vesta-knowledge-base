---
icon: lightbulb-exclamation-on
---

# Raytec avec VESTA

## <mark style="color:green;">Intégration des projecteurs RAYTEC avec les centrales VESTA</mark>

<figure><img src="../.gitbook/assets/image (47).png" alt="" width="375"><figcaption><p><a href="https://bydemes.com/es/marcas/raytec">RAYTEC</a></p></figcaption></figure>

Ce guide explique comment intégrer des projecteurs RAYTEC avec les centrales VESTA en utilisant des commandes HTTP GET. Ces commandes peuvent être configurées dans des scénarios ou des règles sur les centrales VESTA via la plateforme **SmartHomeSec**. Ci-dessous, les exemples détaillées pour allumer, éteindre ou faire clignoter une projecteur RAYTEC.

### _<mark style="background-color:yellow;">**1. Préparation**</mark>_

Avant de démarrer la configuration, assurez-vous d'avoir les information et éléments suivants:

* **Adresse IP du projecteur IP RAYTEC**: Adresse IP du périphérique (ex: `192.168.1.63`).
* **Identifiants**: Nom d'utilisateur (`admin`) et mot de passe (`Admin1234`) du périphérique RAYTEC.
* **Accès à la centrale VESTA**: Accès à la centrale VESTA via la plateforme **SmartHomeSec**.

### _<mark style="background-color:yellow;">**2. Commandes HTTP pour contrôler les projecteurs RAYTEC**</mark>_

Les commandes seront envoyées par HTTP GET depuis la centrale VESTA vers le projecteur RAYTEC. Ci-dessous, les commandes des différentes actions:

*   **Eteindre:**

    ```url
    http://admin:Admin1234@192.168.1.63/power.cgi?Power=off&LightType=WL
    ```
*   **Allumer 5 secondes:**

    ```url
    http://admin:Admin1234@192.168.1.63/power.cgi?LightType=WL&Power=on&Level=100&Time=5
    ```
*   **Clignotement 5 secondes:**

    ```url
    http://admin:Admin1234@192.168.1.63/deter.cgi?Deter=on&Level=20&DeterFreq=fast&DeterPat=sos&Time=5
    ```

### _<mark style="background-color:yellow;">**3. Configuration des commandes dans la centrale VESTA**</mark>_

Suivre les étapes suivantes pour configurer les commandes dans une centrale VESTA:

#### <mark style="color:orange;">**Etape 1:**</mark>**&#x20;Se rendre sur la plateforme SmartHomeSec Platform**

1. Connectez-vous avec votre compte **SmartHomeSec** sur un navigateur.
2. Choisir la centrale VESTA à configurer.

#### <mark style="color:orange;">**Etape 2:**</mark>**&#x20;Configurer les commandes dans des scénarios**

1. Se rendre dans le menu **Scénarios**.
2. Ajoutez un nouveau scénario ou éditez un scénario existant.
3. Choisir l'action  **HTTP GET**.
4. Saisir la commande HTTP désirée dans le champ correspondant:
   * Pour éteindre le projecteur, copiez la commande **Eteindre**.
   * Pour allumer le projecteur avec une temporisation, copiez la commande **Allumer**.
   * Pour faire clignoter le projecteur avec une temporisation, copiez la commande **Clignotement**.
5. Donnez une nom au scénarios comme "Eteindre projecteur RAYTEC", "Allumer projecteur RAYTEC 5s" ou "Clignotement projecteur RAYTEC".
6. Sauver la configuration.

#### <mark style="color:orange;">**Etape 3:**</mark>**&#x20;Configurer les commande dans une règle**

1. Se rendre dans le menu **Règles**.
2. Créez une nouvelle règle ou éditez une règle existante.
3. Configurez le déclencheur de la règle (ex: alarme, détection de mouvement, etc).
4. Dans les actions, choisir **HTTP GET.**
5. Collez la commande qui correspond à l'action que vous souhaitez déclencher.
6. Sauvez la règle avec un nom approprié.

### _<mark style="background-color:yellow;">**4. Vérification et tests**</mark>_

Après avoir configuré les commandes:

1. **Exécutez le scénario**: Depuis SmartHomeSec, lancez le scénario et vérifier le fonctionnement du projecteur RAYTEC.
2. **Déclenchez la règle**: Testez la règle en activant l'évènement déclencheur et vérifier le fonctionnement du projecteur RAYTEC.

### _<mark style="background-color:yellow;">**5. Dépannage**</mark>_

* **Erreur d'identification:** Assurez-vous que les identifiants utilisés pour le projecteur RAYTEC sont corrects (`admin:Admin1234`).
* **Connexion réseau:** Vérifiez que l'adresse IP du projecteur RAYTEC est correct et que les deux périphériques (centrale VESTA et projecteur RAYTEC) sont sur le même réseau local.
* **Commandes non exécutées:** Assurez-vous que la syntaxe de la commande HTTP soit correcte sans ajout d'espace ou de caractères.

### _<mark style="background-color:yellow;">**6. Sécurité**</mark>_

* Modifiez les identifiants par défaut du projecteur RAYTEC pour éviter les accès non autorisés.
* Assurez-vous que le réseau local sur lequel les périphériques se trouvent est correctement protégé avec mot de passe et chiffrage adéquat.

### _<mark style="background-color:yellow;">**7. Conclusion**</mark>_

L'intégration des projecteurs RAYTEC avec les centrales VESTA à l'aide des commandes HTTP GET est un processus simple qui permet une contrôle automatisé de l'éclairage en fonction du besoin utilisateur. En suivant ces étapes, vous pouvez contrôler efficacement les projecteurs RAYTEC depuis une centrale VESTA.

### _<mark style="background-color:yellow;">8. Vidéo</mark>_&#x20;

{% embed url="https://www.youtube.com/watch?ab_channel=ByDemesEspa%C3%B1a&v=fk_DxcPl_qc" %}
