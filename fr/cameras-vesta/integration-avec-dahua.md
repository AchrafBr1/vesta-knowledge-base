# Intégration avec Dahua

Intégration **DAHUA**:

### _<mark style="background-color:yellow;">**Si la caméra dispose de la fonction désarmement**</mark>_

\- La centrale Vesta sera en mesure de contrôler l'armement et le désarmement de la caméra. Dans ce cas, les asservissements sonores et lumineux de la caméra pourront déclencher en fonction de l'état de la centrale.

\- L'activation de l'alarme et les capture fonctionneront normalement.

### _<mark style="background-color:yellow;">**Si la caméra ne dispose pas de la fonction désarmement**</mark>_

\- Dans ce cas, le contrôler des asservissement de la caméra est perdu donc ils seront en permanence actifs. Même si la centrale Vesta est désarmé, les asservissement sonores et lumineux seront constamment actifs car la centrale ne peut pas les contrôler.

\- Les fonctionnalités de la caméra sont les mêmes que la centrale soit armée ou non.

### _<mark style="background-color:yellow;">**Délai de capture d'image**</mark>_

Le délai de capture correct est entre 1 et 3 secondes. Un délai de capture d'environs 5 secondes ou plus indique un ralentissement dans le réseau.

Un moyen pratique pour déterminer ce délai consiste à exécuter  une requête HTTP pour prendre une photo. La commande est la suivante: http://user:password@CAMERA\_IP/cgi-bin/snapshot.cgi?

Exemple: http://admin:Admin1234@192.168.10.182/cgi-bin/snapshot.cgi?

### _<mark style="background-color:yellow;">**P2P Caméra Dahua**</mark>_

Avec SmartHomeSec, il st possible d'ajouter une caméra à une zone de la centrale à l'aide de son numéro de série (P2P ID). Cela permettra aux utilisateurs maîtres ou esclaves avec permission de visualiser le live depuis l'application. Donc, il est essentiel d'ajouter d'abord la caméra dans la centrale VESTA puis, si un enregistrement vidéo est requis, de l'intégrer via son adresse IP dans l'enregistreur Dahua. L'enregistrement peut également être local en utilisant une carte micro SD dans la caméra directement.

{% hint style="info" %}
NOTE:

L'intégration Vesta/Dahua ne fonctionne qu'avec les photos, pas les vidéos.\
Le réglage correspondant doit être réalisé sur la zone utilisée par la caméra.
{% endhint %}

### _<mark style="background-color:yellow;">**Durée entre deux alarmes**</mark>_

Pour une vérification correcte, il y a une temporisation de 3 minutes entre les détection.
