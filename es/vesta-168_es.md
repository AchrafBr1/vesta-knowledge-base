# VESTA 168

**SCS-1-ZW Interruptor de control de obturador**

**Introducción**

SCS-1-ZW es un interruptor de control de persianas de tres botones Z-Wave diseñado para controlar un grupo de dispositivos domóticos preprogramados simplemente presionando los botones del escenario bajo la misma red Z-Wave.

El interruptor de control del obturador es un dispositivo habilitado para Z-Wave y es totalmente compatible con cualquier red habilitada para Z-Wave.

Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. Al aprovechar la red de malla Z-Wave, los comandos se pueden enrutar a su destino a través de productos Z-Wave intermediarios que “escuchan”.

![](<.gitbook/assets/0 (61).jpeg>)

**Introducción del dispositivo**

**1. LED de escenario**

Cuando se presiona cualquiera de los 3 botones de escenario, el LED se iluminará brevemente

**2. Botones de escenario**

El interruptor de control del obturador tiene 3 botones de escenario

1.  **Compartimiento de la batería**
2.  **Botón de función**
    -   Presione el botón 3 veces en 1,5 segundos para transmitir un código de aprendizaje.
    -   Mantenga presionado durante 10 segundos para restablecer.
3.  **LED (rojo)**

El LED rojo se enciende en las siguientes situaciones:

-   -   Parpadea una vez:

Cuando el interruptor de control Sutter está transmitiendo una señal.

-   -   Parpadea dos veces:

El interruptor de control del obturador se ha agregado exitosamente a una red Z-Wave.

1.  **Ojal de función**

**Características**

![](<.gitbook/assets/1 (54).jpeg>)

-   _**Detección de batería y batería baja**_

El interruptor de control del obturador utiliza dos baterías alcalinas AA de 1,5 V como fuente de energía.

El Switch informará su porcentaje de batería al Panel de control respectivamente al 100%, 75%, 50%, 25%. Si el voltaje de la batería es bajo (25%), se enviará una señal de Batería baja al Panel de control para notificar al usuario. El interruptor de control del obturador cuenta con la función de detección de batería baja. Cuando el voltaje de la batería es bajo, el interruptor de escenario transmitirá la señal de batería baja al coordinador Z-Wave.

![](<.gitbook/assets/2 (58).png>)

-   _**Supervisión**_

Esta función utiliza la clase de comando Z-Wave Wake Up. La clase de comando de activación permite que el conmutador alimentado por batería notifique al panel de control/puerta de enlace que está despierto y listo para recibir cualquier comando en cola. El período de tiempo del intervalo de despertar se programa automáticamente de acuerdo con la configuración del Panel de control cuando se incluye el interruptor. El ajuste recomendado del tiempo de intervalo es entre 30 y 60 minutos.

![](<.gitbook/assets/3 (58).png>)

-   _**Control de escenario y obturador**_

Cuando se presiona un botón de escenario, el interruptor de control del obturador enviará una señal al panel de control para activar el escenario correspondiente (consulte el Panel de control para obtener más detalles). Configure el escenario en el Panel de control para

1

controle la función de apertura/cierre/parada de la persiana para operar la persiana a través del interruptor de control de escenario.

El interruptor emitirá un pitido como indicación cuando se presione el botón.

![](<.gitbook/assets/4 (57).png>)

-   _**Agregar dispositivo (inclusión)**_

Este producto se puede incluir y operar en cualquier red Z-Wave con otros dispositivos certificados Z-Wave de otros fabricantes y/u otras aplicaciones. Todos los nodos de la red que no funcionan con baterías actuarán como repetidores independientemente del proveedor para aumentar la confiabilidad de la red.

-   -   Retire la cubierta usando un destornillador.
    -   Inserte la batería y luego vuelva a colocar la tapa.
    -   Coloque el panel de control Z-Wave en**Modo de inclusión**(consulte el manual del panel de control Z-Wave).
    -   En 1,5 segundos, presione el botón de función 3 veces.
    -   Consulte el manual de funcionamiento de la puerta de enlace Z-Wave o del panel de control para completar el proceso de adición.
    -   Si el dispositivo ya se ha agregado (incluido) en otra puerta de enlace/panel de control Z-Wave, o si el dispositivo no se puede agregar a la puerta de enlace/panel de control Z-Wave actual, intente eliminarlo primero (consulte_**Quitar dispositivo**_).
-   _**Eliminación del dispositivo (exclusión)**_

![](<.gitbook/assets/5 (56).png>)

El dispositivo debe eliminarse de la red Z-Wave existente antes de agregarlo a otra.**Modo de exclusión**

-   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de exclusión**(consulte el manual del Z-Wave o del panel de control).
-   En 1,5 segundos, presione el botón de función 3 veces y el dispositivo se eliminará de la red Z-Wave.

**Restablecimiento de fábrica**

El restablecimiento de fábrica del dispositivo lo restaurará a la configuración predeterminada de fábrica (es decir, no estará incluido en ninguna red Z-Wave). Utilice este procedimiento únicamente si la puerta de enlace Z-Wave o el panel de control se pierden o no funcionan.

-   -   Mantenga presionado el botón de función del dispositivo durante 10 segundos para restablecer los valores de fábrica.
-   _**Prueba de rango**_

![](<.gitbook/assets/6 (38).png>)

Para probar si el dispositivo puede comunicarse con la puerta de enlace Z-Wave o el panel de control:

-   -   Coloque la puerta de enlace/panel en modo de prueba de alcance (Walk Test).
    -   Presione el botón de función en el dispositivo.
    -   La puerta de enlace/panel debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual de operación de la puerta de enlace/panel).
-   _**Modo de suspensión Z-Wave**_
    -   El interruptor de control del obturador ingresará al modo de suspensión Z-Wave (para conservar energía) después de despertarse por un corto período de tiempo (~10 segundos). Mientras está en el modo de suspensión Z-Wave, las puertas de enlace o paneles de control Z-Wave no pueden enviar comandos al interruptor de control del obturador.
    -   Para programar el interruptor de control del obturador usando el panel de control/puerta de enlace Z-Wave, envíe comandos al interruptor de control del obturador dentro del período de activación.

![](<.gitbook/assets/7 (32).png>)![](<.gitbook/assets/8 (29).jpeg>)

**Instalación**

-   El interruptor de control de persianas está diseñado para montarse en una superficie plana con tornillos de fijación.
-   La base tiene 3 orificios ciegos, donde el plástico es más delgado, para fines de montaje.
    1.  Retire la cubierta usando un destornillador.
    2.  Rompe los nocauts apropiados en la base.
    3.  Usando los agujeros como plantilla, taladre agujeros en la superficie.
    4.  Atornille la base a la superficie.
    5.  Vuelva a colocar la cubierta en la base y asegúrela apretando el tornillo de fijación.

![](<.gitbook/assets/9 (19).jpeg>)

2

**Información de onda Z**

**Tipo de dispositivo:**Sensor - Notificación

**Tipo de rol:**Informar sobre esclavo durmiente (RSS)

**Soporte/Control de Clase de Comando**

**Soporte CC obligatorio:**Asociación CC, v2

Información del grupo de asociación CC

CC de la batería

Restablecimiento del dispositivo localmente CC

CC específico del fabricante, v2

Activación de escena CC

Versión CC, v2

Despierta CC, v2

Z-Wave Plus Información CC, v2

Nivel de potencia CC

Notificación CC, v4

Actualización de firmware CC, v2

![](<.gitbook/assets/10 (34).png>)

-   _**Grupos de Z-Wave (clase de comando de asociación versión 2)**_

Grupo 1 para “LifeLine”:

Activación de escena CC

(DOMINIO_CLASE_ESCENA_ACTIVACIÓN)

Batería CC (COMANDO_CLASE_BÁSICO)

Restablecimiento del dispositivo localmente CC

3
