# VESTA 041

**Sensor de ambiente RS-23-ZW**V:R3

**Introducción**

RS-23-ZW es un sensor de habitación Z-Wave. Cuenta con función de detección de temperatura y humedad para monitorear los entornos de su hogar. La información de temperatura y humedad se transmitirá a la red Z-Wave y se mostrará en la pantalla LCD del sensor de habitación.

El Room Sensor es un dispositivo habilitado para Z-Wave y es totalmente compatible con cualquier red habilitada para Z-Wave.

Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. Aprovechando la red de malla Z-Wave, los comandos se pueden transmitir a su destino a través de productos Z-Wave intermediarios que "escuchan".

La serie de sensores de habitación Z-Wave incluye los siguientes modelos:

RS-23-ZW

![](<.gitbook/assets/0 (33).png>)

RS-23-ZW-OTA

**Identificación de piezas**

**1. Pantalla LCD**

La pantalla LCD muestra la siguiente información:

-   Temperatura en grados Fahrenheit / Celsius
-   % de humedad relativa.
-   Conectividad de red Z-Wave (![](<.gitbook/assets/1 (30).jpeg>)icono).

![](<.gitbook/assets/2 (27).jpeg>)

\-Estado de batería baja (icono).

-   -   Retroiluminación LCD encendida: cuando se presiona el botón de función.

1.  **Botón de función**
    -   Presione el botón una vez para:

Envía una señal de supervisión con información de temperatura/humedad. Enciende la luz de fondo de la pantalla LCD durante 10 segundos.

-   -   Presione el botón 3 veces en 1,5 segundos para transmitir el código de aprendizaje.
    -   Mantenga presionado el botón durante 10 segundos para restablecer los valores de fábrica. Referirse a**Eliminación del dispositivo (exclusión)**para detalles.

1.  **Tornillo de base (abrir/cerrar cubierta)**

Cuando la cubierta frontal esté instalada en la cubierta posterior, ábrala aflojando el tornillo de la base y ciérrela de la misma manera.

1.  **Puente de ajuste Fahrenheit/Celcius (JP1)**
    -   Si el puente se inserta entre los 2 pines superiores, la pantalla LCD mostrará la temperatura en grados Celsius. (**Predeterminado de fábrica**)
    -   Si el puente se inserta entre los 2 pines inferiores, la pantalla LCD mostrará la temperatura en Fahrenheit.
2.  **Compartimiento de la batería**

![](<.gitbook/assets/3 (25).jpeg>)![](<.gitbook/assets/4 (27).jpeg>)

El sensor de habitación funciona con dos pilas alcalinas AA de 1,5 V.

1.  **Contraportada**
2.  **Perforaciones para montaje en pared**

**Características**

-   _**Detección de temperatura y humedad**_
    -   El sensor de habitación transmitirá señales de temperatura y humedad periódicamente según la configuración.

1

El intervalo predeterminado de fábrica es de 10 minutos.

-   -   Cuando la temperatura cambia +/- 2°C, o la humedad cambia +/- 10%, el sensor de habitación también transmitirá una señal.
    -   También puede presionar el botón de función una vez para transmitir una señal de temperatura y humedad manualmente.
    -   El rango de detección de temperatura es de aproximadamente -10 °C.~50°C.( 14°F~122°F)
    -   El rango de detección de humedad es de aproximadamente 10%.~90% humedad relativa
-   _**Detección de batería y batería baja**_
    -   El sensor de habitación utiliza dos pilas alcalinas de 1,5 V como fuente de alimentación. Las baterías están incluidas en el paquete.
    -   El sensor de habitación informará su porcentaje de batería al panel de control Z-Wave respectivamente al 100%, 75%, 50%, 25%, 0%. Si el voltaje de la batería es bajo (25%), se enviará una señal de batería baja al panel de control Z-Wave para notificar al usuario.
    -   El sensor de habitación cuenta con la función de detección de batería baja. Cuando el voltaje de la batería es bajo, el sensor de habitación transmitirá una señal de batería baja para notificar al usuario y mostrar el icono de batería baja en la pantalla LCD.
    -   Al cambiar las baterías, después de quitar las baterías viejas, presione el botón de función dos veces para descargarlas por completo antes de insertar baterías nuevas.
-   _**Supervisión**_
    -   Esta función utiliza la clase de comando Z-Wave Wake Up. La clase de comando de activación permite que el sensor de habitación alimentado por batería notifique al panel de control/puerta de enlace Z-Wave que está despierto y listo para recibir cualquier comando en cola. La hora de despertarse se programa automáticamente de acuerdo con la configuración del panel de control Z-Wave cuando se incluye el sensor de habitación. La configuración recomendada para la hora de despertarse es de 60 minutos más.
-   _**Agregar dispositivo (inclusión)**_

Este producto se puede incluir y operar en cualquier red Z-Wave con otros dispositivos certificados Z-Wave de otros fabricantes y/u otras aplicaciones. Todos los nodos de la red que no funcionan con baterías actuarán como repetidores independientemente del proveedor para aumentar la confiabilidad de la red.

-   -   Retire la tapa aflojando el tornillo de fijación.
    -   Inserte las 2 baterías alcalinas en el compartimiento de baterías conectando la polaridad correcta como se muestra en la tapa del compartimiento de baterías para encender el sensor de habitación.
    -   Coloque la puerta de enlace Z-Wave o el panel de control Z-Wave en**Inclusión**o**Aprendiendo**modo (consulte el manual de la puerta de enlace Z-wave o del panel de control Z-Wave).
    -   En 1,5 segundos, presione el botón de función 3 veces.
    -   Consulte el manual de funcionamiento de la puerta de enlace Z-Wave o del panel de control Z-Wave para completar el proceso de aprendizaje.
    -   Si el sensor ya ha sido**incluido**(aprendido) en otro Z-Wave Gateway/Panel de control Z-Wave, o si el sensor no se puede aprender en el Z-Wave Gateway/Panel de control Z-Wave actual, exclúyalo primero (consulte_**Exclusión**_) antes de intentar**incluir**en el panel de control Z-Wave Gateway/Z-Wave actual.
-   _**Eliminación del dispositivo (exclusión)**_

El sensor de habitación debe retirarse de la red Z-Wave existente antes de incluirlo en otra. Hay dos métodos disponibles para excluir un dispositivo.

**Modo de exclusión**

-   Coloque la puerta de enlace Z-Wave o el panel de control Z-Wave en**Modo de exclusión**(consulte el manual de la puerta de enlace Z-Wave o del panel de control Z-Wave).
-   En 1,5 segundos, presione el botón de función 3 veces y el sensor de habitación se eliminará de la red Z-Wave.

**Restablecimiento de fábrica**

_(Utilice el restablecimiento de fábrica únicamente cuando el panel de control/puerta de enlace de la red Z-Wave no esté disponible o no funcione)._

-   Primero retire las baterías del sensor de habitación.
-   Mantenga presionado el botón de función. Mientras mantiene presionado el botón de función, encienda el sensor de habitación reinsertando las baterías y espere 10 segundos para restablecer los valores de fábrica.

_\\<NOTE>_

-   El restablecimiento de fábrica del sensor de habitación lo restaurará a la configuración predeterminada de fábrica (excluido de la red Z-wave). La puerta de enlace Z-Wave o el panel de control Z-Wave aún mantendrán su configuración Z-Wave. Consulte el manual de la puerta de enlace o del panel de control Z-Wave sobre cómo eliminar la configuración Z-Wave del sensor de habitación.

2

-   _**Prueba de rango**_

Para probar si el dispositivo puede comunicarse con la puerta de enlace Z-Wave o el panel de control Z-Wave:

-   -   Coloque la puerta de enlace/panel en modo de prueba de alcance (Walk Test).
    -   Presione el botón de función en el dispositivo.
    -   El panel de control de la puerta de enlace/panel debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual de funcionamiento del panel de control de la puerta de enlace/panel).
-   _**Modo de suspensión Z-Wave**_
    -   El sensor de habitación entrará en el modo de suspensión Z-Wave (para ahorrar energía) después de despertarse durante un breve período de tiempo (~10 segundos). Mientras está en el modo de suspensión Z-Wave, las puertas de enlace Z-Wave o los paneles de control Z-Wave no pueden enviar comandos al sensor de habitación.
    -   Para programar el sensor de habitación, envíe comandos al sensor de habitación dentro del período de despertar.

**Instalación**

-   _**Montaje del sensor de habitación**_

Para obtener la mejor calidad de pantalla LCD, el sensor de habitación debe montarse aproximadamente a 5° por encima del nivel de los ojos.

-   Montaje con tornillos.

Al realizar el montaje con tornillos, asegúrese de utilizar únicamente los tornillos proporcionados en el paquete por el fabricante original, ya que tornillos inadecuados pueden dañar el interior del dispositivo.

-   1.  Retire la cubierta frontal con un destornillador.
    2.  Rompe los agujeros ciegos en la contraportada.
    3.  Usando los agujeros como plantilla, taladre agujeros en la superficie.
    4.  Insert the wall plugs if fixing into plaster or brick
    5.  Atornille la cubierta trasera a los tacos de pared.
    6.  Atornille la cubierta frontal nuevamente a la cubierta trasera.
-   _**Información de onda Z**_

**Tipo de dispositivo:**Sensor - Notificación

**Tipo de rol:**Informar sobre esclavo durmiente (RSS)

**Soporte/Control de Clase de Comando**

**Soporte CC obligatorio:**Asociación CC, v2 o más reciente

Información del grupo de asociación CC

CC de la batería

Restablecimiento del dispositivo localmente CC

CC específico del fabricante

Sensor CC multinivel

Versión CC, v2 o más reciente

Despierta CC

Z-Wave Plus Información CC

Actualización de firmware CC, v2 (solo versión OTA)

-   _**Grupos de Z-Wave (clase de comando de asociación versión 2)**_

El sensor de habitación se puede configurar para enviar informes a dispositivos Z-Wave asociados. Soporta 3 grupos de asociaciones.

Grupo 1 para “LifeLine”:

Sensor Multinivel CC,V5 (COMANDO_CLASE_SENSOR_MULTI NIVEL)

Batería CC (COMANDO_CLASE_USUARIO_BÁSICO)

Restablecimiento del dispositivo localmente CC

_(Admite 1 nodo)_

Grupo 2 para “Informe de Temperatura”:

Sensor CC multinivel, v5 (COMANDO_CLASE_SENSOR_MULTI NIVEL)

_(admite 5 nodos)_

3

Grupo 3 para “Informe de Humedad”:

Sensor Multinivel CC,V5 (COMANDO_CLASE_SENSOR_MULTI NIVEL)

_(admite 5 nodos)_

4
