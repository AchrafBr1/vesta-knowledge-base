# VESTA 259

**Medidor de interruptor de potencia en carril DIN (Serie PSM-DIN2-ZW)**

![](<.gitbook/assets/0 (97).jpeg>)

El interruptor de encendido es capaz de recibir señales inalámbricas del coordinador en la red Z-Wave para activar o desactivar los aparatos conectados a él. El Power Switch también permite realizar un seguimiento del consumo de energía con un medidor de energía incorporado y transmitir los datos a la red Z-Wave con regularidad.

El interruptor de encendido es un dispositivo habilitado para Z-Wave y es totalmente compatible con cualquier red habilitada para Z-Wave.

Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. Aprovechando la red de malla Z-Wave, los comandos se pueden transmitir a su destino a través de productos Z-Wave intermediarios que "escuchan".

![](<.gitbook/assets/1 (81).jpeg>)

La serie PSM-DIN2-ZW incluye los siguientes modelos:

PSM-DIN2-ZW

PSM-DIN2-ZW-OTA

![](<.gitbook/assets/2 (75).png>)![](<.gitbook/assets/3 (68).jpeg>)

-   _**Identificar las piezas**_
    1.  **Conector de entrada**
    2.  **Conector de salida**
    3.  **Puerto de antena externa**
    4.  **Indicador LED**
    5.  **Botón de función**

\-Presione el botón de función 3 veces en 1,5 segundos para enviar un código de aprendizaje.

\-Mantenga presionado durante 10 segundos para restablecer los valores de fábrica.

![](<.gitbook/assets/4 (78).png>)

-   _**Indicador LED**_
    -   Encendido: encendido
    -   Apagado: apagado
    -   La luz roja parpadea dos veces: 1. El interruptor de encendido acaba de encenderse,_o_
        1.  El interruptor de encendido acaba de restablecerse a los valores de fábrica.
-   _**Precaución**_
    -   Todos los trabajos en el dispositivo, incluida la instalación y el mantenimiento, deben ser realizados por un electricista calificado y autorizado.
    -   Antes de la instalación o cualquier trabajo de mantenimiento, asegúrese de que la fuente de alimentación esté desconectada.
    -   No conecte el dispositivo a cargas que excedan la corriente de carga admitida.
-   _**Cableado e instalación**_

![](<.gitbook/assets/5 (78).png>)![](<.gitbook/assets/6 (58).png>)

**Antes de la instalación, asegúrese de que la fuente de alimentación esté desconectada.**

![](<.gitbook/assets/7 (46).jpeg>)

-   -   Conecte el terminal L del conector de entrada al terminal L de la fuente de alimentación; utilice un fusible para el cable. Conecte el terminal N del conector de entrada al terminal N de la fuente de alimentación.
    -   Conecte el terminal N del conector de salida al terminal N del dispositivo externo y conecte el terminal L del conector de salida al terminal L del dispositivo externo.
    -   Conecte la antena externa al puerto de antena externa.
    -   Monte el dispositivo dentro del gabinete eléctrico usando un riel DIN.
-   _**Inclusión (adición o dispositivo de aprendizaje)**_

![](<.gitbook/assets/8 (53).png>)

Este producto se puede incluir y operar en cualquier red Z-Wave con otros dispositivos certificados Z-Wave de otros fabricantes y/u otras aplicaciones. Todos los nodos de la red que no funcionan con baterías actuarán como repetidores independientemente del proveedor para aumentar la confiabilidad de la red.

-   Encienda el dispositivo encendiendo la fuente de alimentación externa.
-   Coloque la puerta de enlace Z-Wave o el panel de control en**Inclusión**o**Aprendiendo**modo (consulte el manual del Z-Wave Gateway o del panel de control).
-   En 1,5 segundos, presione el botón de función 3 veces.
-   Consulte el manual de funcionamiento del Z-Wave Gateway o del panel de control para completar el proceso de adición.

1

-   -   Si el dispositivo ya se ha agregado (incluido) en otra puerta de enlace/panel de control Z-Wave, o si el dispositivo no se puede agregar a la puerta de enlace/panel de control Z-Wave actual, exclúyalo primero (consulte_**Exclusión**_) antes de intentar incluirlo en el panel de control/puerta de enlace Z-Wave actual.
-   _**Exclusión (eliminación del dispositivo)**_

![](<.gitbook/assets/9 (49).png>)

El dispositivo debe eliminarse de la red Z-Wave existente antes de incluirlo en otra. Hay dos métodos disponibles para excluir un dispositivo.

**Modo de exclusión**

-   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de exclusión**(consulte el manual del Z-Wave Gateway o del panel de control).
-   En 1,5 segundos, presione el botón de función 3 veces y el dispositivo se eliminará de la red Z-Wave.

**Restablecimiento de fábrica**

_(Utilice el restablecimiento de fábrica únicamente cuando falte el panel de control/puerta de enlace de la red o no esté operativo)._

-   -   Mantenga presionado el botón de función del dispositivo durante 10 segundos para restablecer los valores de fábrica.

_\\<NOTE>_

-   -   -   El restablecimiento de fábrica del dispositivo lo restaurará a la configuración predeterminada de fábrica (excluido de la red Z-Wave). La puerta de enlace Z-Wave o el panel de control aún mantendrán su configuración Z-Wave. Consulte el manual de la puerta de enlace o del panel de control sobre cómo eliminar la configuración Z-Wave del dispositivo.
        -   El restablecimiento de fábrica del dispositivo también borrará todos los datos de energía acumulados.
-   _**Prueba de rango**_

![](<.gitbook/assets/10 (51).png>)![](<.gitbook/assets/11 (41).png>)

Para probar si el dispositivo puede comunicarse con Z-Wave Gateway o Panel de control:

-   -   -   Coloque la puerta de enlace/panel en modo de prueba de alcance (Prueba de caminata).
        -   Presione el botón de función en el dispositivo.
        -   La puerta de enlace/panel debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual de operación de la puerta de enlace/panel).
-   _**Operación**_
    -   Después de incluirlo en una puerta de enlace o panel de control Z-Wave, conecte un electrodoméstico al interruptor de encendido. Los datos de potencia y uso de energía de este electrodoméstico se transferirán al Panel de control.
    -   Al presionar el botón del interruptor de encendido también se puede activar/desactivar el interruptor de encendido.
    -   Encienda/apague remotamente el aparato eléctrico a través del Panel de Control (consulte el manual de su Panel de Control).
    -   Si la potencia de salida es inferior a 1 kW, PSM-DIN2 transmitirá una señal al panel/puerta de enlace Z-Wave cuando la potencia se desvíe en +/- 2 W para actualizar la información de potencia de PSM-DIN2.

Si la potencia de salida es superior a 1 kW, PSM-DIN2 transmitirá una señal al panel/puerta de enlace Z-Wave cuando la potencia se desvíe en +/- 5 W para actualizar la información de potencia de PSM-DIN2.

-   -   PSM-DIN2 transmite una señal con datos de energía al panel de control/puerta de enlace Z-Wave cada 10 minutos a partir de la última vez que se transmitió una señal.
    -   El interruptor de encendido transmite una señal con datos de energía al panel de control/puerta de enlace Z-Wave cada vez que el uso de energía aumenta en 0,1 kW/h.
    -   Si se vuelve a conectar la alimentación del interruptor de alimentación tras una desconexión anterior, el estado anterior de encendido/apagado del interruptor de alimentación se reanudará inmediatamente.
    -   Cuando la potencia es inferior a 20 W, es más probable que se produzcan errores de medición.
-   _**Especificación de energía**_
    -   Para**110V:**la carga máxima de operación es 1760W y 16A. Advertencia: no exceda la carga máxima.
    -   Para**230V:**la carga máxima de operación es 3680W y 16A. Advertencia: no exceda la carga máxima.
-   _**Información de onda Z**_

![](<.gitbook/assets/12 (43).png>)![](<.gitbook/assets/13 (32).png>)![](<.gitbook/assets/14 (31).png>)

**Tipo de dispositivo:**Conmutador de tipo genérico binario

**Tipo de rol:**Siempre en esclavo (AOS)

**Tipo de producto:**0x0004

**ID del Producto:**0x0003

**Soporte/Control de Clase de Comando**

**Soporte CC obligatorio:**Z-Wave Plus Información CC

Asociación CC, (S2)

Asociación multicanal CC, (S2)

Información del grupo de asociación CC, (S2)

Servicio de Transporte CC

Versión CC, (S2)

CC específico del fabricante, (S2)

Restablecimiento del dispositivo localmente CC, (S2)

Nivel de potencia CC, (S2)

2

Medidor CC, v2

Cambiar CC binario

Supervisión CC, (S2)

Actualización de firmware Md CC, (S2)

![](<.gitbook/assets/15 (31).png>)

-   _**Grupos de Z-Wave (clase de comando de asociación versión 2)**_

El Switch se puede configurar para enviar informes a dispositivos Z-Wave asociados. Admite un grupo de asociación con soporte de cinco nodos para el Grupo 1. Para el Grupo 1, el conmutador informará su último estado al panel/puerta de enlace Z-Wave. Grupo 1 para “LifeLine”: (nodo máximo: 5)

Cambiar CC binario (COMANDO_CLASE_CAMBIAR_BINARIO)

Medidor CC (COMANDO_CLASE_METRO)

Restablecimiento del dispositivo localmente CC (COMANDO_CLASE_DISPOSITIVO_REINICIAR_EN LA ZONA)

-   Informe automático al Grupo 1 (Nodo máximo 5)
-   Informe de evento activado/desactivado

Al alternar entre Encendido/Apagado, enviará un Informe de cambio binario a los nodos del Grupo 1.

-   Restablecimiento de fábrica

Cuando el interruptor de encendido se restablece a los valores predeterminados de fábrica, enviará el reinicio del dispositivo localmente a todos los nodos del grupo 1.

-   Informe del medidor:
    -   Si la potencia de salida es inferior a 1 kW, PSM-DIN2 transmitirá una señal al panel/puerta de enlace Z-Wave cuando la potencia se desvíe en +/- 2 W para actualizar la información de potencia de PSM-DIN2.
    -   Si la potencia de salida es superior a 1 kW, PSM-DIN2 transmitirá una señal al panel/puerta de enlace Z-Wave cuando la potencia se desvíe en +/- 5 W para actualizar la información de potencia de PSM-DIN2.
    -   PSM-DIN2 transmite una señal con datos de energía al panel de control/puerta de enlace Z-Wave cada 10 minutos a partir de la última vez que se transmitió una señal.
    -   El interruptor de encendido transmite una señal con datos de energía al panel de control/puerta de enlace Z-Wave cada vez que el uso de energía aumenta en 0,1 kW/h.
    -   Formato de datos:

Ejemplo 1:**41 64 00 00 50 14**FF FF**00 00 00 00**kWh (00005014 = 20500 = 20,5)

-   -   -   Valor presente:**41 64 00 00 50 14**
        -   Valor anterior:**00 00 00 00**

Ejemplo 2:**41 74 00 00 27 10**FF FF**00 00 00 00**W (00002710 = 10000 = 10W)

-   Valor presente:**41 74 00 00 27 10**
-   Valor anterior:**00 00 00 00**

3
