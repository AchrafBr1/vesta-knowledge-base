# VESTA-429

### PLUG & JOUER AVEC VESTA

{% indice style="succès" %}
Guide de câblage avec VESTA HYBRID PANEL :{%endint%}

<figure><img src=".gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

### INTRODUCTION

Les détecteurs filaires VESTA représentent le meilleur choix pour les installations résidentielles et industrielles du secteur de la sécurité. Il utilise uniquement des PIR numériques, évitant ainsi la conversion qui doit généralement être effectuée dans les détecteurs traditionnels, où le PIR analogique est amplifié et converti en numérique. Grâce à la technologie TOTALEMENT numérique, le détecteur est beaucoup plus précis dans la détection des intrusions et ne subit pas d'altérations telles que : la lumière blanche, la lumière ultraviolette, la température, le mouvement de l'air dû aux systèmes de chauffage/refroidissement et il est totalement insensible aux ondes électromagnétiques rayonnées et conduites. perturbations. Les détecteurs ProLine sont équipés de lentilles conçues par AMC et fabriquées par Fresnel Technologies, Inc. La technologie LODIFF® pour la réalisation optique en combinaison avec les matériaux POLY IR® en font un produit de la plus haute qualité et efficacité. Tous les détecteurs ProLine sont insensibles aux animaux avec une portée de 15 m et un angle de 100 degrés. Le capteur est équipé de modules micro-ondes de dernière génération, avec un bruit de fond très faible, et peut être alimenté avec différentes fréquences conformément à la législation de chaque pays.

<table data-view="cards"><thead><tr><th></th><th></th><th></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td><p><img src=".gitbook/assets/image (11).png" alt="" data-size="original"></p><p>White light protection The detector is digitally filtered from white light.</p></td><td></td><td></td><td></td></tr><tr><td><p><img src=".gitbook/assets/image (10).png" alt="" data-size="original"></p><p>Full digital PIR The detector has no analog components, the full digital PIR is connected directly to the microprocessor.</p></td><td></td><td></td><td></td></tr><tr><td><img src=".gitbook/assets/image (9).png" alt="" data-size="original"></td><td>High RFI protection Thanks to the total lack of traditional amplifiers, the detector has a very high RFI immunity.</td><td></td><td></td></tr><tr><td><img src=".gitbook/assets/image (12).png" alt="" data-size="original"></td><td>Pet immunity All our detectors are pet immune up to 15 Kg, thanks to the new lens design combined with the digital analysis system.</td><td></td><td></td></tr><tr><td><img src=".gitbook/assets/image (13).png" alt="" data-size="original"></td><td>Ultraviolet stabilization POLY IR®4 material for lenses The lens materials is POLY IR®. It offer the best combination of transmittance, environmental stability, and color of any polymer. Materials available for the 8-14 micron region of the infrared.</td><td></td><td></td></tr><tr><td><p><img src=".gitbook/assets/image (14).png" alt="" data-size="original"></p><p>LODIFF® Fresnel Lens Technology The lens array is made by tiling pieces of LODIFF® lenses. These lenses offer significantly improved performance over typical constant-groove-width Fresnel.</p></td><td></td><td></td><td></td></tr></tbody></table>

### PROCÉDURE D'INSTALLATION

-   À l'aide d'un tournevis fin, desserrez la vis en bas et ouvrez le boîtier (voir figure 1).
-   Retirez le PCB de la base en faisant levier sur les supports ABS (voir figure 2)
-   Percez la frappe sur la base du couvercle au point de fixation souhaité (ou utilisez le support pivotant en option non certifié IMQ)
-   Percez le bouton sur la base et fixez une vis entre le mur et le couvercle pour une protection arrière contre l'effraction (voir fig2).
-   hauteur recommandée de 1,8m à 2,2m
-   faites glisser le câble dans la banquette arrière et hors du trou supérieur
-   Câblez les bornes en suivant les connexions indiquées sur la figure.

<figure><img src=".gitbook/assets/image (15).png" alt=""><figcaption><p>Fig. 1</p></figcaption></figure>

<figure><img src=".gitbook/assets/image (16).png" alt=""><figcaption><p>Fig. 2 </p></figcaption></figure>

{% indice style="info" %}
REMARQUE : ne couvrez pas, partiellement ou totalement, le champ de vision du détecteur REMARQUE : la fonction immunitaire des animaux n'est pas certifiée IMQ
{% indice de fin %}

### FONCTIONS LED

En fonctionnement normal :

-   <mark style="color:green;">**LED VERTE**</mark>: Alarme PIR
-   <mark style="color:yellow;">**LED JAUNE**</mark>: Alarme MO
-   <mark style="color:blue;">**LED BLEUE**</mark>: Alarme générale (PIR et MW)
-   AM VERSION: in case of masking, the LED corresponding to the masked technology flashes with the opening the alarm contacts with MASK contact AM version (antimasking version) The AM version provides a continuous self test, in case of anomaly lasting more than 15 seconds the sensor will report the folowing signaling:
-   ALIMENTATION AU-DELÀ DES SEUILS NOMINAUX : Clignotement alternatif des leds jaune et verte avec contact masque ouvert
-   AUTOTEST PIR FILED LED verte clignotante avec contact MASQUE ouvert
-   MW déposé AUTO-TEST Led jaune clignotante avec contact MASQUE ouvert

### RÉGLAGE ET CONNEXION

Dip 1 --> off = led éteinte - on = led allumée\*

Dip 2 -> off = 15mt - on = plage de 7mt

Dip 3 --> off = 1 impulsion - on = 2 impulsions

Dip 4 - 5 --> OFF-OFF = ET ON-OFF=OU ON-ON=AUTO OU\*

Plage de réglage = utilisé uniquement pour MW

Cavaliers T - A - EOL ouverts = tous contacts libres sans résistances

Cavaliers T - A - EOL fermés = double équilibrage (voir valeurs ci-dessous)

ALARME : bornes NC (cavalier EOL ouvert)

Autoprotection : bornes NC (cavalier EOL ouvert)

MASQUE : borne NC (avec cavalier EOL ouvert - uniquement pour la version AM)

BS : terminal pour télécommande LED et MW

DT2AM + et - = ALIMENTATION : alimentation 9 - 15Vcc @ 27 mA nominal

<figure><img src=".gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (20).png" alt=""><figcaption><p>Datasheet</p></figcaption></figure>

\\
VUE DE CÔTÉ

<figure><img src=".gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>
