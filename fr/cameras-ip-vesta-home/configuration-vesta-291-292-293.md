---
description: >-
  La série VESTA-291/292 et 293 est une gamme de caméras sans fils pour usage
  intérieur et extérieur. Elles permettent une vidéo surveillance avec une
  installation simplifiée.
icon: camera-cctv
---

# Configuration VESTA-291/292/293

<figure><img src="../.gitbook/assets/Immagine2.png" alt="" width="375"><figcaption></figcaption></figure>

{% hint style="info" %}
Le modèle VESTA-292 sera utilisé tout au long de ce document mais, les étapes sont identiques pour les modèles VESTA-291 et VESTA-293.
{% endhint %}

<figure><img src="../.gitbook/assets/1 (1).png" alt=""><figcaption></figcaption></figure>

### _<mark style="background-color:yellow;">Préparation</mark>_

<mark style="color:orange;">**Etape 1:**</mark>  Branchez l'alimentation de la caméra.\
\
<mark style="color:orange;">**Etape 2:**</mark> Attendez que la LED de la caméra soit <mark style="color:green;">**VERTE**</mark> fixe pour une connexion en Ethernet (câble) ou <mark style="color:green;">**VERTE**</mark> clignotante pour une connexion en Wi-Fi.

### _<mark style="background-color:yellow;">Initialisation et ajout de la caméra avec SmartHomeSec</mark>_

Utilisez l'application SmartHomeSec avec le compte utilisateur maître pour initialiser et ajouter la caméra au système.

<figure><img src="../.gitbook/assets/100.png" alt=""><figcaption><p>Etape 1                                                                Etape 2                                                           Etape 3</p></figcaption></figure>

<mark style="color:orange;">**Etape 1:**</mark> Avec l'app SmartHomeSec, se connecter en mode utilisateur avec le compte utilisateur maître.\
\
<mark style="color:orange;">**Etape 2:**</mark> Cliquez sur l'icône représentant une caméra.\
\
<mark style="color:orange;">**Etape 3:**</mark> Cliquez sur le bouton "+" pour ajouter une caméra.

<figure><img src="../.gitbook/assets/image (37).png" alt=""><figcaption><p>Etape 4                                                                                                             Etape 5 </p></figcaption></figure>

<mark style="color:orange;">**Etape 4:**</mark> Cliquez sur l'icône VESTA/Imou.\
\
<mark style="color:orange;">**Etape 5:**</mark> Scannez le QR code de la caméra et cliquez sur "Suivant".\
\
<mark style="color:orange;">**Etape 6:**</mark> Choisir comment la caméra doit être ajoutée au système.

*

    <figure><img src="../.gitbook/assets/image (38).png" alt=""><figcaption><p>Etape 6</p></figcaption></figure>
* &#x20;Ajouter à l'équipement: La caméra et la centrale doivent utiliser le même réseau local. De cette manière, la caméra sera totalement prise en charge par la centrale et l'application.&#x20;

{% hint style="success" %}
Avantages du mode "Ajouter à l'équipement":

* La caméra sera une zone d'intrusion dans la centrale et pourra générer des alarmes.
* L'accès aux enregistrements sur la CARTE SD est possible.
* Détection de mouvement.
* Contrôle des fonctions Pan/Tilt pour le modèle VESTA-292
{% endhint %}

* Ajouter au cloud: La caméra sera ajoutée en utilisant le cloud. L'utilisateur ne verra que le live de la caméra depuis l'application.

{% hint style="success" %}
Avantages du mode "Ajouter au cloud":

* La caméra peut être installée un réseau différent (ou un autre site).
* Les utilisateurs avec une centrale connectée uniquement en 4G peuvent avoir des caméras connectées à leurs comptes.
{% endhint %}

<mark style="color:orange;">**Etape 7:**</mark> Choisir le mode de communication avec la caméra (Ethernet ou Wi-Fi)

{% hint style="warning" %}
La caméra et la centrale doivent être sur le même réseau, veillez à vérifier avant de continuer.&#x20;
{% endhint %}

<figure><img src="../.gitbook/assets/102.png" alt=""><figcaption><p>Etape 7</p></figcaption></figure>

{% hint style="info" %}
En cas d'utilisation du mode de communication Ethernet, veuillez directement consulter l'étape 12.
{% endhint %}

<mark style="color:orange;">**Etape 8:**</mark> Connexion Wi-Fi

{% hint style="warning" %}
Le téléphone doit être connecté au réseau Wi-Fi sur lequel vous voulez ajouter la caméra (2.4GHz uniquement).
{% endhint %}

<figure><img src="../.gitbook/assets/102.2.png" alt=""><figcaption><p>Etape 8                                                                Etape 9                                                                 Etape 10</p></figcaption></figure>

{% hint style="info" %}
**Si vous connectez votre camera via Wi-Fi mais que vous ne parvenez pas à passer à l'étape de recherche d'adresse IP, pas d'inquiétude. Cela peut se produire si le périphérique a temporairement perdu sa connexion Internet lors du changement de réseau et n'a pas réussi à se reconnecter correctement.**

Pour continuer:

* Vérifiez si la led de la caméra est <mark style="color:green;">**VERTE**</mark>**&#x20;**<mark style="color:$primary;">**fixe**</mark> (non clignotante).
* Si c'est le cas, revenez à l'étape précédente et sélectionnez ETHERNET au lieu de Wi-Fi — la configuration devrait alors fonctionner correctement..

![](<../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1).png>)
{% endhint %}

<mark style="color:orange;">**Etape 9:**</mark> Connectez votre téléphone à la caméra en cliquant sur "Rejoindre" (selon le modèle de téléphone cette étape est optionnelle).\
\
<mark style="color:orange;">**Etape 10:**</mark> Choisir le réseau et cliquez sur "Suivant".

<figure><img src="../.gitbook/assets/103.png" alt=""><figcaption><p> Etape 11                                                                Etape 12                                                                    Etape 13</p></figcaption></figure>

<mark style="color:orange;">**Etape 11:**</mark> Saisir le clé de sécurité du réseau Wi-Fi sélectionné.\
\
<mark style="color:orange;">**Etape 12:**</mark> L'application affichera  l'identifiant utilisateur et le mot de passe de la caméra.

<figure><img src="../.gitbook/assets/104.png" alt=""><figcaption><p>                                                                                                                    Etape 12                                                                                                                                                  </p></figcaption></figure>

{% hint style="warning" %}
NOTE:

Si les champs Identifiants et mot de passe ne sont pas automatiquement renseignés, voir ci-dessous: \
Identifiant: admin\
Mot de passe: code de sécurité de la caméra (présent sur l'étiquette du produit)
{% endhint %}

<figure><img src="../.gitbook/assets/image (39).png" alt="" width="375"><figcaption><p>Mot de passe/Code de sécurité</p></figcaption></figure>

CONFIGURATION TERMINEE

<figure><img src="../.gitbook/assets/21.jpg" alt="" width="185"><figcaption></figcaption></figure>



### _<mark style="background-color:yellow;">Dépannage</mark>_

**Je ne retrouve pas l'adresse IP de la caméra durant les étapes de configuration:**

1\.   Assurez-vous que la centrale VESTA et la caméra soient connectées sur le même réseau.

2\.   Redémarrez le switch ou le routeur sur lequel les équipements sont connectés.

***

**Je ne parviens pas a terminée la configuration en Wi-Fi:**

1\.   Vérifiez que la centrale VESTA soit bien équipée du dernier firmware.

2\.   Assurez-vous d'avoir la fonction de localisation d'activée pour l'application SmartHomeSec APP.

3\.   Assurez-vous d'avoir donné à l'application la permission de se connecter aux réseaux Wi-Fi et, si elle demande les autorisations acceptées les.

<figure><img src="../.gitbook/assets/image (14) (1) (1).png" alt=""><figcaption><p>Autorisation Wi-Fi</p></figcaption></figure>

***

**Réglage de l'horloge VESTA-29x:**

| Index zone | Index pour Vesta | Ville                                                       |
| ---------- | ---------------- | ----------------------------------------------------------- |
| 0          | 32               | international date line West                                |
| 1          | 31               | -11 UTC                                                     |
| 2          | 30               | Hawaii                                                      |
| 3          | 29               | Alaska                                                      |
| 4          | 28               | Pacific time (United States and Canada)                     |
| 5          | 28               | Baja California                                             |
| 6          | 27               | Chihuahua, La Paz, Mazatlan                                 |
| 7          | 27               | Mountain time (United States and Canada)                    |
| 8          | 27               | Arizona                                                     |
| 9          | 26               | Guadalajara, Mexico City, Monterrey                         |
| 10         | 26               | Saskatchewan                                                |
| 11         | 26               | Central time (United States and Canada)                     |
| 12         | 26               | Central America                                             |
| 13         | 25               | Bogota, Lima                                                |
| 14         | 25               | Eastern time (United States and Canada)                     |
| 15         | 25               | Indiana (East)                                              |
| 16         | 24               | Caracas                                                     |
| 17         | 24               | Atlantic time (Canada)                                      |
| 18         | 24               | Cuiaba                                                      |
| 19         | 24               | Georgetown, La Paz, Manaus, San Juan                        |
| 20         | 24               | San Diego                                                   |
| 21         | 24               | Asunción                                                    |
| 22         | 23               | Newfoundland                                                |
| 23         | 22               | Brasilia                                                    |
| 24         | 22               | Buenos Aires                                                |
| 25         | 22               | Greenland                                                   |
| 26         | 22               | Cayenne, Fortaleza                                          |
| 27         | 22               | Montevideo-Asian                                            |
| 28         | 22               | El Salvador                                                 |
| 29         | 21               | -02 UTC                                                     |
| 30         | 21               | mid-Atlantic                                                |
| 31         | 20               | Cape Verde Islands                                          |
| 32         | 20               | Azores                                                      |
| 33         | 0                | Dublin, Edinburgh, Lisbon, London                           |
| 34         | 0                | Casablanca                                                  |
| 35         | 0                | mengluoweiya, Reykjavik                                     |
| 36         | 0                | coordinated universal time                                  |
| 37         | 1                | Tripoli                                                     |
| 38         | 1                | Amsterdam, Berlin, Bern, Rome, sitegeermo, Viana do Castelo |
| 39         | 1                | Belgrade, buladesilafa, Budapest, lubueryana, Prague        |
| 40         | 1                | Brussels, Copenhagen, Madrid, Paris                         |
| 41         | 1                | Sarajevo, Skopje, Warsaw, Zagreb                            |
| 42         | 1                | Windhoek                                                    |
| 43         | 1                | West Central Africa                                         |
| 44         | 2                | Beirut                                                      |
| 45         | 2                | Damascus                                                    |
| 46         | 2                | Eastern Europe                                              |
| 47         | 2                | Harare, Pretoria                                            |
| 48         | 2                | Helsinki, base shop, Riga, Sofia, Tallinn, Vilnius          |
| 49         | 2                | Cairo                                                       |
| 50         | 2                | Athens, Bucharest                                           |
| 51         | 2                | +02 UTC                                                     |
| 52         | 3                | yisitabuer                                                  |
| 53         | 3                | Amman                                                       |
| 54         | 3                | Baghdad                                                     |
| 55         | 3                | Kaliningrad, Minsk                                          |
| 56         | 3                | Kuwait, Riyadh                                              |
| 57         | 3                | Nairobi                                                     |
| 58         | 4                | Tehran                                                      |
| 59         | 5                | Abu Dhabi, Muscat                                           |
| 60         | 5                | Yerevan                                                     |
| 61         | 5                | Baku                                                        |
| 62         | 5                | Tbilisi                                                     |
| 63         | 5                | Port Louis                                                  |
| 64         | 3                | Moscow, St Petersburg, Volgograd                            |
| 65         | 6                | Kabul                                                       |
| 66         | 7                | asihabade, Marrakech                                        |
| 67         | 7                | Islamabad, Karachi                                          |
| 68         | 8                | Chennai, Kolkata, Mumbai, New Delhi                         |
| 69         | 8                | silijiaya Worcester lamp Pula                               |
| 70         | 9                | Kathmandu                                                   |
| 71         | 10               | Astana                                                      |
| 72         | 10               | Dhaka                                                       |
| 73         | 10               | Yekaterinburg                                               |
| 74         | 11               | Yangon                                                      |
| 75         | 12               | Bangkok, Hanoi, Jakarta                                     |
| 76         | 12               | Novosibirsk                                                 |
| 77         | 13               | Beijing, Chongqing, Hong Kong S.A.R., Urumqi                |
| 78         | 13               | Kuala Lumpur, Singapore                                     |
| 79         | 13               | Krasnoyarsk                                                 |
| 80         | 13               | Perth                                                       |
| 81         | 13               | Chinese Taipei                                              |
| 82         | 13               | Ulan Bator                                                  |
| 83         | 14               | Osaka, Sapporo, Tokyo                                       |
| 84         | 14               | Seoul                                                       |
| 85         | 14               | Il Yakutsk                                                  |
| 86         | 15               | Adelaide                                                    |
| 87         | 15               | Darwin                                                      |
| 88         | 16               | Brisbane                                                    |
| 89         | 16               | Guam, Port Moresby                                          |
| 90         | 16               | Hobart                                                      |
| 91         | 16               | Canberra, Melbourne, Sydney                                 |
| 92         | 16               | James Yakutsk                                               |
| 93         | 17               | Vladivostok                                                 |
| 94         | 17               | Solomon Islands, xinhaliduoniya                             |
| 95         | 17               | Magadan                                                     |
| 96         | 18               | Auckland, Wellington                                        |
| 97         | 18               | Fiji                                                        |
| 98         | 18               | +12 UTC                                                     |
| 99         | 19               | Nukualofa                                                   |
| 100        | 19               | Samoa                                                       |

***

**La caméra n'est pas prête:**

Faire une reset de la caméra.

Pour faire une reset de la caméra, veuillez maintenir enfoncé le bouton RESET pendant 10 secondes (la caméra émettra un bip et la led deviendra rouge)

{% hint style="info" %}
&#x20;NOTES:\
Pour le modèle VESTA-292, le bouton est situé sous l'objectif.<br>
{% endhint %}

<figure><img src="../.gitbook/assets/image (41).png" alt="" width="375"><figcaption><p>Reset VESTA-292</p></figcaption></figure>
