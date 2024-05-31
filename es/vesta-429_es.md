# VESTA-429

### CONECTAR Y JUGAR CON VESTA

{% sugerencia estilo="éxito" %}
Guía de cableado con PANEL HÍBRIDO VESTA:{%endint%}

<figure><img src=".gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

### INTRODUCCIÓN

Los detectores cableados VESTA representan la mejor opción para instalaciones residenciales e industriales en el sector de la seguridad. Utiliza únicamente PIR digitales, evitando así la conversión que generalmente se debe realizar en los detectores tradicionales, donde el PIR analógico se amplifica y se convierte a digital. Gracias a la tecnología TOTALMENTE digital, el detector es mucho más preciso en la detección de intrusiones y no sufre alteraciones tales como: luz blanca, luz ultravioleta, temperatura, movimiento de aire debido a sistemas de calefacción/refrigeración y es totalmente inmune a las radiaciones electromagnéticas radiadas y conducidas. disturbios. Los detectores ProLine están equipados con lentes diseñadas por AMC y fabricadas por Fresnel Technologies, Inc. La tecnología LODIFF® para la realización de ópticas en combinación con los materiales POLY IR® lo convierten en un producto de la más alta calidad y eficiencia. Todos los detectores ProLine son inmunes a las mascotas con un alcance de 15 m y un ángulo de 100 grados. El sensor está equipado con módulos de microondas de última generación, con muy bajo ruido de fondo, y puede alimentarse con diferentes frecuencias de acuerdo con la legislación de cada país.

<table data-view="cards"><thead><tr><th></th><th></th><th></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td><p><img src=".gitbook/assets/image (11).png" alt="" data-size="original"></p><p>White light protection The detector is digitally filtered from white light.</p></td><td></td><td></td><td></td></tr><tr><td><p><img src=".gitbook/assets/image (10).png" alt="" data-size="original"></p><p>Full digital PIR The detector has no analog components, the full digital PIR is connected directly to the microprocessor.</p></td><td></td><td></td><td></td></tr><tr><td><img src=".gitbook/assets/image (9).png" alt="" data-size="original"></td><td>High RFI protection Thanks to the total lack of traditional amplifiers, the detector has a very high RFI immunity.</td><td></td><td></td></tr><tr><td><img src=".gitbook/assets/image (12).png" alt="" data-size="original"></td><td>Pet immunity All our detectors are pet immune up to 15 Kg, thanks to the new lens design combined with the digital analysis system.</td><td></td><td></td></tr><tr><td><img src=".gitbook/assets/image (13).png" alt="" data-size="original"></td><td>Ultraviolet stabilization POLY IR®4 material for lenses The lens materials is POLY IR®. It offer the best combination of transmittance, environmental stability, and color of any polymer. Materials available for the 8-14 micron region of the infrared.</td><td></td><td></td></tr><tr><td><p><img src=".gitbook/assets/image (14).png" alt="" data-size="original"></p><p>LODIFF® Fresnel Lens Technology The lens array is made by tiling pieces of LODIFF® lenses. These lenses offer significantly improved performance over typical constant-groove-width Fresnel.</p></td><td></td><td></td><td></td></tr></tbody></table>

### PROCEDIMIENTO DE INSTALACIÓN

-   Con un destornillador fino, afloje el tornillo en la parte inferior y abra la carcasa (consulte la figura 1).
-   Retire la PCB de la base haciendo palanca en los soportes de ABS (ver figura 2)
-   Perforar el golpe de la base de la tapa en el punto deseado de fijación (o utilizar el soporte giratorio opcional no certificado IMQ)
-   Perfore el conector en la base y fije un tornillo entre la pared y la cubierta para proteger la parte trasera contra manipulaciones (ver figura 2).
-   altura recomendada de 1,8mt a 2,2mt
-   Deslice el cable dentro del asiento trasero y sáquelo por el orificio superior.
-   Conecte los terminales siguiendo las conexiones que se muestran en la figura.

<figure><img src=".gitbook/assets/image (15).png" alt=""><figcaption><p>Fig. 1</p></figcaption></figure>

<figure><img src=".gitbook/assets/image (16).png" alt=""><figcaption><p>Fig. 2 </p></figcaption></figure>

{% sugerencia estilo="info" %}
NOTA: no cubra, parcial o totalmente, el campo de visión del detector NOTA: la función inmune a mascotas no está certificada IMQ
{% final %}

### FUNCIONES LED

Durante el funcionamiento normal:

-   <mark style="color:green;">**LED VERDE**</mark>: Alarma PIR
-   <mark style="color:yellow;">**LED AMARILLO**</mark>: Alarma MO
-   <mark style="color:blue;">**LED AZUL**</mark>: Alarma General (PIR y MW)
-   VERSIÓN AM: en caso de enmascaramiento, el LED correspondiente a la tecnología enmascarado parpadea al abrir los contactos de alarma con contacto MÁSCARA Versión AM (versión antienmascaramiento) La versión AM proporciona un autotest continuo, en caso de anomalía que dura más de 15 segundos el El sensor informará la siguiente señalización:
-   ALIMENTACIÓN MÁS ALLÁ DE LOS UMBRALES NOMINALES: Parpadeo alternativo de los led amarillo y verde con el contacto de máscara abierto
-   AUTOTEST PIR FILED LED verde parpadeando con contacto MÁSCARA abierto
-   MW archivado AUTOTEST Led amarillo parpadeando con contacto MÁSCARA abierto

### AJUSTE Y CONEXIÓN

Dip 1--> apagado = led apagado - encendido = led encendido\*

Inmersión 2 --> apagado = 15mt - encendido = rango de 7mt

Dip 3 --> apagado = 1 pulso - encendido = 2 pulsos

Dip 4 - 5 --> OFF-OFF = Y ON-OFF=O ON-ON=AUTO O\*

Rango de ajuste = usado solo para MW

Puentes T - A - EOL abierto = todos los contactos libres sin resistencias

Puentes T - A - EOL cerrado = doble equilibrio (ver valores a continuación)

ALARMA: terminales NC (puente EOL abierto)

Sabotaje: terminales NC (puente EOL abierto)

MÁSCARA: terminal NC (con puente EOL abierto -sólo para versión AM)

BS: terminal para control remoto de LED y MW

DT2AM + y - = ALIMENTACIÓN: alimentación 9 - 15Vcc @ 27 mA nominal

<figure><img src=".gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (20).png" alt=""><figcaption><p>Datasheet</p></figcaption></figure>

\\
VISTA LATERAL

<figure><img src=".gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>
