# VESTA 313

**Liga de Leyendas-3ZW****Sensor de luz ambiental, humedad y temperatura**

**Introducción**

LMHT-3ZW es un sensor de temperatura, humedad y luz ambiental Z-Wave. Supervisa el entorno de su hogar y transmite la iluminancia (lux), la humedad y la temperatura medidas al coordinador en la red Z-Wave.

El sensor es un dispositivo habilitado para Z-Wave y es totalmente compatible con cualquier red habilitada para Z-Wave.

Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. Aprovechando la red de malla Z-Wave, los comandos se pueden transmitir a su destino a través de productos Z-Wave intermediarios que "escuchan".

**Identificación de piezas**

![](<.gitbook/assets/0 (105).jpeg>)

1.  **Sensor de luz/indicador LED**
    -   **Parpadea una vez:**Transmisión de código de aprendizaje/restablecimiento de fábrica.
    -   **Parpadea dos veces:**Después de que el sensor se haya agregado correctamente al panel de control/puerta de enlace Z-Wave.
2.  **Compartimiento de la batería**
3.  **Botón de función**
    -   Presione una vez para enviar una señal al coordinador.
    -   Mantenga presionado durante 10 segundos para restablecer los valores de fábrica.
    -   Presione 3 veces en 1,5 segundos para transmitir el código de aprendizaje.
4.  **Sensor de temperatura**

**Características**

-   _**Monitoreo de iluminación, humedad y temperatura**_
    -   El sensor mide la iluminancia, la humedad y la temperatura para transmitir los datos medidos al panel de control/puerta de enlace Z-Wave con regularidad.

La lectura de iluminancia/humedad y temperatura se transmite cada 1 minuto. El sensor también transmitirá la señal automáticamente cuando:

-   -   -   La temperatura cambia +/- 2°C.
        -   La humedad cambia +/- 10%.
        -   La iluminancia actual cambia en +/- 30%.
        -   Encienda el sensor insertando la batería.
    -   También puede presionar el botón de función una vez para transmitir la lectura actual manualmente.
-   _**Detección de batería y batería baja**_
    -   El sensor utiliza una batería de litio CR123A de 3 V como fuente de alimentación.
    -   El sensor cuenta con la función de detección de batería baja. Cuando el voltaje de la batería es bajo, el sensor transmitirá la señal de batería baja al portal/panel de control.
    -   El sensor informará su porcentaje de batería a la puerta de enlace/panel de control respectivamente al 100 %, 75 %, 50 % y 25 %. Si el voltaje de la batería es bajo (25%), se enviará una señal de Batería baja al Panel de control para notificar al usuario.
    -   Al cambiar la batería, después de quitar las baterías viejas, presione el botón de función dos veces para descargarla completamente antes de insertar una batería nueva.
-   _**Supervisión**_

Esta función utiliza la clase de comando Z-Wave Wake Up. La clase de comando de activación permite que el sensor alimentado por batería notifique al panel de control/puerta de enlace que está despierto y listo para recibir cualquier comando en cola. El período de tiempo para despertarse se programa automáticamente de acuerdo con la configuración del Panel de control cuando se incluye el sensor. La configuración recomendada para la hora de despertarse es de 60 minutos más.

1

-   _**Agregar dispositivo (inclusión)**_

Este producto se puede incluir y operar en cualquier red Z-Wave con otros dispositivos certificados Z-Wave de otros fabricantes y/u otras aplicaciones. Todos los nodos de la red que no funcionan con baterías actuarán como repetidores independientemente del proveedor para aumentar la confiabilidad de la red.

-   -   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de inclusión**(consulte el manual de la puerta de enlace Z-Wave o del panel de control).
    -   En 1,5 segundos, presione el botón de función 3 veces.
    -   Consulte el manual de funcionamiento de la puerta de enlace Z-Wave o del panel de control para completar el proceso de adición.
    -   Si el sensor ya se ha agregado (incluido) en otra puerta de enlace/panel de control Z-Wave, o si el dispositivo no se puede agregar a la puerta de enlace/panel de control Z-Wave actual, intente quitarlo primero (consulte_**Quitar dispositivo**_).
-   _**Eliminación del dispositivo (exclusión)**_

El sensor debe retirarse de la red Z-Wave existente antes de agregarlo a otra.

**Modo de exclusión**

-   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de exclusión**(consulte el manual de la puerta de enlace Z-Wave o del panel de control).
-   En 1,5 segundos, presione el botón de función 3 veces y el sensor se eliminará de la red Z-Wave.

**Restablecimiento de fábrica**

_(Utilice el restablecimiento de fábrica únicamente cuando falte el panel de control/puerta de enlace de la red o no esté operativo)._

-   Primero retire la batería del sensor.
-   Mantenga presionado el botón de función. Mientras mantiene presionado el botón de función, encienda el sensor reinsertando la batería y espere 10 segundos para restablecer los valores de fábrica.

_\\<NOTE>_

-   -   El restablecimiento de fábrica del sensor lo restaurará a la configuración predeterminada de fábrica (excluido de la red Z-Wave). La puerta de enlace o el panel de control Z-Wave seguirán manteniendo su configuración Z-Wave. Consulte el manual de la puerta de enlace o del panel de control sobre cómo eliminar la configuración del sensor Z-Wave.
-   _**Prueba de rango**_

Para probar si el sensor puede comunicarse con la puerta de enlace Z-Wave o el panel de control:

-   -   Coloque la puerta de enlace/panel en modo de prueba de alcance (Walk Test).
    -   Presione el botón de función en el sensor.
    -   La puerta de enlace/panel debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual de operación de la puerta de enlace/panel).
-   _**Modo de suspensión Z-Wave**_
    -   El sensor ingresará al modo de suspensión Z-Wave (para conservar energía) después de despertarse por un corto período de tiempo (~10 segundos). Mientras está en el modo de suspensión Z-Wave, las puertas de enlace o paneles de control Z-Wave no pueden enviar comandos al sensor.
    -   Para programar el sensor utilizando el panel de control/puerta de enlace Z-Wave, envíe comandos al sensor dentro del período de activación.

**Installation**

-   _**Montaje del sensor**_

El sensor se puede montar mediante dos métodos: montaje autoadhesivo o con tornillos.

**Montaje autoadhesivo**

1.  Limpiar la superficie con un desengrasante adecuado.
2.  Retire la cubierta protectora de un lado de la almohadilla adhesiva de doble cara y aplíquela firmemente en la parte posterior del dispositivo.
3.  Retire la otra cubierta y coloque/presione firmemente el dispositivo en el lugar deseado.

![](<.gitbook/assets/1 (87).jpeg>)

No utilice el método de montaje autoadhesivo en superficies mal pintadas y/o rugosas.

**Montaje con tornillos**

La base del sensor tiene dos orificios ciegos para tornillos, donde el plástico es más delgado para fines de montaje. Para montar el sensor:

1.  Separe el conjunto de la cubierta superior y la base aflojando el tornillo de fijación de la cubierta con un destornillador Philips.
2.  Rompe los nocauts en la base.

2

-   1.  Utilice los agujeros como plantilla para perforar dos agujeros e insertar los tacos.
    2.  Atornille la base a los tacos de pared.
    3.  Vuelva a colocar la cubierta superior sobre la base enganchando la base en el gancho de fijación y empujando la cubierta hacia la base.
    4.  Asegure y atornille la cubierta superior a su base con un destornillador Philips.
-   _**Información de onda Z**_

**Tipo de dispositivo:**Sensor - Notificación

**Tipo de rol:**Informar sobre esclavo durmiente (RSS)

**Soporte/Control de Clase de Comando**

**Soporte CC obligatorio:**

Asociación CC, v2

Información del grupo de asociación CC

CC de la batería

Restablecimiento del dispositivo localmente CC

CC específico del fabricante, v2

Sensor multinivel CC, V5

Versión CC, v2

Despierta CC, v2

Z-Wave Plus Información CC, v2

Nivel de potencia CC

Notificación CC, v4

Actualización de firmware CC, v2

-   _**Grupos de Z-Wave (clase de comando de asociación versión 2)**_

Grupo 1 para “LifeLine”:

Sensor Multinivel CC,V5 (COMANDO_CLASE_SENSOR_MULTI NIVEL)

Batería CC (COMANDO_CLASE_BÁSICO)

Restablecimiento del dispositivo localmente CC

Grupo 2 para “Informe de Temperatura”:

Sensor Multinivel CC,V5 (COMANDO_CLASE_SENSOR_MULTI NIVEL)

Grupo 3 para “Informe de Humedad”:

Sensor Multinivel CC, V5 (COMANDO_CLASE_SENSOR_MULTI NIVEL)

Grupo 4 para “Informe de Luminancia”:

Sensor Multinivel CC, V5 (COMANDO_CLASE_SENSOR_MULTI NIVEL)

3
