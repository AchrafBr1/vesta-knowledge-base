# VESTA 043

-   Interruptor de escenario inteligente WSS-4E-ZW
-   Introducción

WSS-4E-ZW es un interruptor de escenario de cuatro botones Z-Wave diseñado para controlar un grupo de dispositivos de automatización del hogar preprogramados simplemente presionando los botones de escenario bajo la misma red Z-Wave.

El Scenario Switch es un dispositivo habilitado para Z-Wave y es totalmente compatible con cualquier red habilitada para Z-Wave.

Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. Al aprovechar la red de malla Z-Wave, los comandos se pueden enrutar a su destino a través de productos Z-Wave intermediarios que “escuchan”.

![](<.gitbook/assets/0 (13).png>)

-   Introducción del dispositivo

**1. LED de escenario**

Hay cuatro LED de escenario, el LED se iluminará según el botón de escenario correspondiente presionado.

**2. Botón de escenario**

El interruptor de escenario tiene 4 botones de escenario:

![未命名-1](<.gitbook/assets/1 (7) (1).jpeg>)Botón 1

Botón 2

Botón 3

Botón 4

**3. Compartimento de la batería**

**4. Botón de función**

-   Presione el botón 3 veces en 1,5 segundos para transmitir un código de aprendizaje.
-   Mantenga presionado el botón durante 10 segundos para restablecer los valores de fábrica.

**5. LED (rojo)**

El LED rojo se enciende en las siguientes situaciones:

-   Parpadea una vez:

Cuando el interruptor de escenario está transmitiendo una señal.

-   Parpadea dos veces:

El Scenario Switch se ha agregado exitosamente a una red Z-Wave.

**6. Ojal de función**

-   Características
-   _Detección de batería y batería baja_

El Scenario Switch utiliza dos baterías alcalinas AA de 1,5 V como fuente de energía.

El Switch informará su porcentaje de batería al Panel de control respectivamente al 100%, 75%, 50%, 25%. Si el voltaje de la batería es bajo (25%), se enviará una señal de Batería baja al Panel de control para notificar al usuario.

El interruptor de escenario cuenta con la función de detección de batería baja. Cuando el voltaje de la batería es bajo, el interruptor de escenario transmitirá la señal de batería baja al coordinador Z-Wave.

-   _**Supervisión**_

Esta función utiliza la clase de comando Z-Wave Wake Up. La clase de comando de activación permite que el interruptor de luz alimentado por batería notifique al panel de control/puerta de enlace que está despierto y listo para recibir cualquier comando en cola. El período de tiempo del intervalo de despertar se programa automáticamente de acuerdo con la configuración del Panel de control cuando se incluye el interruptor de luz. El ajuste recomendado del tiempo de intervalo es entre 30 y 60 minutos.

-   _**Guión**_

Cuando se presiona un botón de escenario, el interruptor de escenario enviará una señal al panel de control para activar el escenario correspondiente (consulte el panel de control para obtener más detalles). El interruptor también emitirá un pitido como indicación.

-   _**Agregar dispositivo (inclusión)**_

Este producto se puede incluir y operar en cualquier red Z-Wave con otros dispositivos certificados Z-Wave de otros fabricantes y/u otras aplicaciones. Todos los nodos de la red que no funcionan con baterías actuarán como repetidores independientemente del proveedor para aumentar la confiabilidad de la red.

-   Retire la cubierta usando un destornillador.
-   Inserte la batería y luego vuelva a colocar la tapa.
-   Coloque el panel de control Z-Wave en**Modo de inclusión**(consulte el manual del panel de control Z-Wave).
-   En 1,5 segundos, presione el botón de función 3 veces.
-   Consulte el manual de funcionamiento de la puerta de enlace Z-Wave o del panel de control para completar el proceso de adición.
-   Si el dispositivo ya se ha agregado (incluido) en otra puerta de enlace/panel de control Z-Wave, o si el dispositivo no se puede agregar a la puerta de enlace/panel de control Z-Wave actual, intente eliminarlo primero (consulte_**Quitar dispositivo**_).
-   _**Eliminación del dispositivo (exclusión)**_

El dispositivo debe eliminarse de la red Z-Wave existente antes de agregarlo a otra.

**Modo de exclusión**

-   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de exclusión**(consulte el manual del Z-Wave o del panel de control).
-   En 1,5 segundos, presione el botón de función 3 veces y el dispositivo se eliminará de la red Z-Wave.

**Restablecimiento de fábrica**

El restablecimiento de fábrica del dispositivo lo restaurará a la configuración predeterminada de fábrica (es decir, no estará incluido en ninguna red Z-Wave). Utilice este procedimiento únicamente si la puerta de enlace Z-Wave o el panel de control se pierden o no funcionan.

-   Mantenga presionado el botón de función del dispositivo durante 10 segundos para restablecer los valores de fábrica.
-   _**Prueba de rango**_

Para probar si el dispositivo puede comunicarse con la puerta de enlace Z-Wave o el panel de control:

-   Coloque la puerta de enlace/panel en modo de prueba de alcance (Walk Test).
-   Presione el botón de función en el dispositivo.
-   La puerta de enlace/panel debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual de operación de la puerta de enlace/panel).
-   _**Modo de suspensión Z-Wave**_
-   El interruptor de escenario ingresará al modo de suspensión Z-Wave (para conservar energía) después de despertarse por un corto período de tiempo (~10 segundos). Mientras está en el modo de suspensión Z-Wave, las puertas de enlace o los paneles de control Z-Wave no pueden enviar comandos al Scenario Switch.
-   Para programar el interruptor de escenario utilizando el panel de control/puerta de enlace Z-Wave, envíe comandos al interruptor de escenario dentro del período de activación.
-   Instalación
-   El Scenario Switch está diseñado para montarse en una superficie plana con tornillos de fijación.
-   La base tiene 3 orificios ciegos, donde el plástico es más delgado, para fines de montaje.

1.  Retire la cubierta usando un destornillador.
2.  Rompe los nocauts apropiados en la base.
3.  Usando los agujeros como plantilla, taladre agujeros en la superficie.
4.  Atornille la base a la superficie.
5.  Vuelva a colocar la cubierta en la base y asegúrela apretando el tornillo de fijación.

![未命名-2](<.gitbook/assets/2 (2) (1).jpeg>)

-   Información de onda Z

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

-   _**Grupos de Z-Wave (clase de comando de asociación versión 2)**_

Grupo 1 para “LifeLine”:

Activación de escena CC

(DOMINIO_CLASE_ESCENA_ACTIVACIÓN)

Batería CC (COMANDO_CLASE_BÁSICO)

Restablecimiento del dispositivo localmente CC
