# VESTA 260

**Medidor de interruptor de alimentación en carril DIN (Serie PSM-DIN3-ZW)**

El interruptor de encendido es capaz de recibir señales inalámbricas del coordinador en la red Z-Wave para activar o desactivar los aparatos conectados a él. El Power Switch también permite realizar un seguimiento del consumo de energía con un medidor de energía incorporado y transmitir los datos a la red Z-Wave con regularidad.

El interruptor de encendido es un dispositivo habilitado para Z-Wave y es totalmente compatible con cualquier red habilitada para Z-Wave.

Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. Aprovechando la red de malla Z-Wave, los comandos se pueden transmitir a su destino a través de productos Z-Wave intermediarios que "escuchan".

La serie PSM-DIN3-ZW incluye los siguientes modelos:

PSM-DIN3-ZW

PSM-DINX-ZO-OTA

![](<.gitbook/assets/0 (98).jpeg>)

-   _**Identificar las piezas**_
    1.  **Conector de entrada**
    2.  **Conector de salida**
    3.  **Puerto de antena externa**
    4.  **Indicador LED**
    5.  **Botón de función**

Presione el botón de función 3 veces en 1,5 segundos para transmitir un código de aprendizaje

Mantenga presionado durante 10 segundos para restablecer los valores de fábrica. Presione una vez para encender/apagar el aparato conectado.

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

**Antes de la instalación, asegúrese de que la fuente de alimentación esté desconectada.**

-   -   Conecte el terminal L del conector de entrada al terminal L de la fuente de alimentación; utilice un fusible para el cable. Conecte el terminal N del conector de entrada al terminal N de la fuente de alimentación.
    -   Conecte el terminal N del conector de salida al terminal N del dispositivo externo y conecte el terminal L del conector de salida al terminal L del dispositivo externo.
    -   Conecte la antena externa al puerto de antena externa.
    -   Monte el dispositivo dentro del gabinete eléctrico usando un riel DIN.
-   _**Inclusión (adición o dispositivo de aprendizaje)**_

![](<.gitbook/assets/1 (82).jpeg>)

Este producto se puede incluir y operar en cualquier red Z-Wave con otros dispositivos certificados Z-Wave de otros fabricantes y/u otras aplicaciones. Todos los nodos de la red que no funcionan con baterías actuarán como repetidores independientemente del proveedor para aumentar la confiabilidad de la red.

-   Encienda el dispositivo encendiendo la fuente de alimentación externa.
-   Coloque la puerta de enlace Z-wave o el panel de control en**Inclusión**o**Aprendiendo**modo (consulte el manual de la puerta de enlace Z-wave o del panel de control).
-   En 1,5 segundos, presione el botón de función 3 veces.

1

-   -   Consulte el manual de funcionamiento de la puerta de enlace Z-wave o del panel de control para completar el proceso de aprendizaje.
    -   Si el dispositivo ya ha sido**incluido**(aprendido) en otra puerta de enlace/panel de control Z-wave, o si el dispositivo no se puede aprender en la puerta de enlace/panel de control Z-wave actual, exclúyalo primero (consulte_**Exclusión**_) antes de intentar**incluir**en el panel de control/puerta de enlace Z-wave actual.
-   _**Exclusión (eliminación del dispositivo)**_

El dispositivo debe eliminarse de la red Z-wave existente antes de incluirlo en otra. Hay dos métodos disponibles para excluir un dispositivo.

**Modo de exclusión**

-   Coloque la puerta de enlace Z-wave o el panel de control en**Modo de exclusión**(consulte el manual de la puerta de enlace Z-wave o del panel de control).
-   En 1,5 segundos, presione el botón de función 3 veces y el dispositivo se eliminará de la red Z-wave.

**Restablecimiento de fábrica**

_(Utilice el restablecimiento de fábrica únicamente cuando falte el panel de control/puerta de enlace de la red o no esté operativo)._

-   -   Mantenga presionado el botón de función del dispositivo durante 10 segundos para restablecer los valores de fábrica.

_\\<NOTE>_

-   -   -   El restablecimiento de fábrica del dispositivo lo restaurará a la configuración predeterminada de fábrica (excluido de la red Z-wave). La puerta de enlace o el panel de control Z-wave seguirán manteniendo su configuración Z-wave. Consulte el manual de la puerta de enlace o del panel de control sobre cómo eliminar la configuración Z-wave del dispositivo.
        -   El restablecimiento de fábrica del dispositivo también borrará todos los datos de energía acumulados.
-   _**Prueba de rango**_

Para probar si el dispositivo puede comunicarse con Z-Wave Gateway o Panel de control:

-   -   -   Coloque la puerta de enlace/panel en modo de prueba de alcance (Prueba de caminata).
        -   Presione el botón de función en el dispositivo.
        -   La puerta de enlace/panel debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual de operación de la puerta de enlace/panel).
-   _**Operación**_
    -   After being included into a Z-wave gateway or control panel, plug a home appliance into the Power Switch. This home appliance’s power and energy usage data will be transferred to the Gateway / Control Panel.
    -   Al presionar el botón del interruptor de encendido también se puede activar/desactivar el interruptor de encendido.
    -   Encienda/apague remotamente el aparato eléctrico a través del Panel de Control (consulte el manual de su Panel de Control).
    -   Si la potencia de salida es inferior a 1kW, PSM-DIN3 transmitirá una señal a la puerta de enlace/panel Z-wave cuando la potencia se desvíe en +/- 2W para actualizar la información de potencia de PSM-DIN3.

Si la potencia de salida es superior a 1kW, PSM-DIN3 transmitirá una señal a la puerta de enlace/panel Z-wave cuando la potencia se desvíe en +/- 5W para actualizar la información de potencia de PSM-DIN3.

-   -   PSM-DIN3 transmite una señal con datos de energía a la puerta de enlace/panel Z-wave cada 10 minutos a partir de la última vez que se transmitió una señal.
    -   El interruptor de encendido transmite una señal con datos de energía a la puerta de enlace/panel Z-wave cada vez que el uso de energía aumenta en 0,1 kW/h.
    -   Si se vuelve a conectar la alimentación del interruptor de alimentación tras una desconexión anterior, el estado anterior de encendido/apagado del interruptor de alimentación se reanudará inmediatamente.
    -   Cuando la potencia es inferior a 20 W, es más probable que se produzcan errores de medición.
-   _**Especificación de energía**_
    -   Para**110V:**la carga máxima de operación es 3300W y 30A. Advertencia: no exceda la carga máxima.
    -   Para**230V:**la carga máxima de operación es 6900W y 30A. Advertencia: no exceda la carga máxima.
-   _**Protección contra el sobrecalentamiento**_

Cuando el interruptor de encendido se sobrecalienta, se apagará automáticamente. Cuando la temperatura vuelva a la normalidad, se encenderá automáticamente para reanudar el funcionamiento normal.

-   _**Información de onda Z**_

**Tipo de dispositivo:**Conmutador de tipo genérico binario

**Tipo de rol:**Siempre en esclavo (AOS)

**Tipo de producto:**0x0004

2

**ID del Producto:**0x0013

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

Medidor CC, v2

Cambiar CC binario

Supervisión CC, (S2)

Actualización de firmware Md CC, (S2)

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

-   Valor presente:**41 64 00 00 50 14**
-   Valor anterior:**00 00 00 00**

Ejemplo 2:**41 74 00 00 27 10**FF FF**00 00 00 00**W (00002710 = 10000 = 10W)

-   Valor presente:**41 74 00 00 27 10**
-   Valor anterior:**00 00 00 00**

3
