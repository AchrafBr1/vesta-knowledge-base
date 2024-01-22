# VESTA 042

PSM-29ZW / PSS-29ZW

Serie de interruptores de alimentación

Introducción

La serie Power Switch incluye los siguientes modelos:

**PSS-29ZW:**Interruptor de alimentación Z-Wave con función de enrutador

**PSM-29ZW:**Interruptor de alimentación Z-Wave con función de medidor y función de enrutador

Los interruptores de alimentación habilitados para Z-Wave son capaces de recibir señales inalámbricas del coordinador en la red Z-Wave para activar o desactivar los dispositivos conectados a él. El Power Switch también sirve como enrutador en la red Z-Wave. Después de ser incluido en la red Z-Wave, permite que otros dispositivos Z-Wave se unan a la red a través del interruptor de encendido.

El interruptor de encendido con función de medidor (PSM-29ZW) tiene la característica adicional de realizar un seguimiento del consumo de energía con el medidor de energía incorporado y transmitir los datos al coordinador regularmente.

Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. Aprovechando la red de malla Z-Wave, los comandos se pueden transmitir a su destino a través de productos Z-Wave intermediarios que "escuchan".

Los interruptores de alimentación Z-Wave permiten el acceso a la clase "S2 no autenticado" y admiten la inclusión Z-Wave SmartStart así como la inclusión clásica.

Identificación de piezas

1.Botón de función también conocido como indicador LED

El botón de función también funciona como indicador LED. El botón de función se utiliza para controlar el interruptor de encendido. El indicador LED se utiliza para indicar el estado del interruptor de encendido.

**Indicación LED:**

El indicador LED se enciende en las siguientes condiciones:

-   Encendido: encendido
-   Apagado: apagado
-   La luz roja parpadea dos veces:

1.El interruptor de encendido acaba de encenderse.

2.El interruptor de encendido acaba de restablecerse a los valores de fábrica.

**Uso del botón de función:**

-   Presione el botón de función para encender/apagar el interruptor de encendido.
-   Presione el botón de función 3 veces en 1,5 segundos para transmitir un código de aprendizaje.
-   Mantenga presionado el botón de función durante 10 segundos para restablecer los valores de fábrica.

| _Tipo F_                                                           | _Tipo J_                                                                                                                                                                                               | _Tipo B_ | _Tipo E_ | _Tipo G_ |
| ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------- | -------- | -------- |
| <img src=".gitbook/assets/0 (12).png" alt="" data-size="original"> | <img src=".gitbook/assets/1 (16).png" alt="" data-size="original"><img src=".gitbook/assets/2 (19).png" alt="" data-size="original"><img src=".gitbook/assets/3 (18).png" alt="" data-size="original"> |          |          |          |

**Características**

-   _**Agregar dispositivo (inclusión)**_

Este producto se puede incluir y operar en cualquier red Z-Wave con otros dispositivos certificados Z-Wave de otros fabricantes y/u otras aplicaciones. Todos los nodos de la red que no funcionan con baterías actuarán como repetidores independientemente del proveedor para aumentar la confiabilidad de la red.

El dispositivo admite tanto el proceso de inclusión clásico como el proceso de inclusión SmartStart.

**Inclusión clásica**

-   Conecte el interruptor de encendido a una toma de corriente.
-   Coloque la puerta de enlace Z-Wave o el panel de control en**Inclusión****modo**(consulte el manual del Z-Wave Gateway o del panel de control).
-   En 1,5 segundos, presione el botón de función 3 veces.
-   Consulte el manual de operación de Z-Wave Gateway o Panel de control para completar el proceso de adición.
-   Si el dispositivo ya se ha agregado (incluido) en otra puerta de enlace/panel de control Z-Wave, o si el dispositivo no se puede agregar a la puerta de enlace/panel de control Z-Wave actual, exclúyalo primero (consulte_**Quitar dispositivo**_) antes de intentar**incluir**en el panel de control/puerta de enlace Z-Wave actual.

**Inclusión SmartStart**

![](<.gitbook/assets/4 (17).png>)Z-Wave SmartStart utilizes the DSK of the device to enhance and simplify the inclusion process. DSK is Device Specific Key used for authentication. The DSK information is stored in the QR code format that is printed on a sticker and attached to the device.

-   Escanee la etiqueta del código QR en el interruptor de encendido para obtener DSK y transferirlo a la puerta de enlace Z-Wave.
-   Conecte el interruptor de alimentación a una toma de corriente y se enviará automáticamente una solicitud de inclusión de SmartStart al portal.
-   La puerta de enlace incluirá automáticamente el dispositivo al reconocerlo haciendo coincidir la solicitud de inclusión con el DSK obtenido.

&lt;NOTA>

-   El DSK del dispositivo se utiliza sólo durante la inclusión.
-   El DSK se puede leer sin que el interruptor de encendido esté encendido, por lo que es posible preparar la puerta de enlace para incluir el dispositivo antes de encender el interruptor de encendido.
-   _**Eliminación del dispositivo (exclusión)**_

El dispositivo debe eliminarse de la red Z-Wave existente antes de incluirlo en otra. Hay dos métodos disponibles para excluir un dispositivo.

**Modo de exclusión**

-   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de exclusión**(consulte el manual del Z-Wave Gateway o del panel de control).
-   En 1,5 segundos, presione el botón de función 3 veces y el dispositivo se eliminará de la red Z-Wave.

**Restablecimiento de fábrica**

_(Utilice el restablecimiento de fábrica únicamente cuando falte el panel de control/puerta de enlace de la red o no esté operativo)._

-   Mantenga presionado el botón de función del dispositivo durante 10 segundos para restablecer los valores de fábrica.

\\<NOTE>

-   El restablecimiento de fábrica del dispositivo lo restaurará a la configuración predeterminada de fábrica (excluido de la red Z-Wave). La puerta de enlace Z-Wave o el panel de control aún mantendrán su configuración Z-Wave. Consulte el manual de la puerta de enlace o del panel de control sobre cómo eliminar la configuración Z-Wave del dispositivo.
-   El restablecimiento de fábrica del dispositivo también borrará todos los datos de energía acumulados.
-   Antes de quitar o restablecer los valores de fábrica del interruptor de encendido, asegúrese de que la información DSK del dispositivo se haya eliminado o no exista en la puerta de enlace. Si elimina o restablece el dispositivo a los valores de fábrica, pero su DSK aún existe en la puerta de enlace, la puerta de enlace incluirá automáticamente el dispositivo nuevamente.
-   _Prueba de rango_

Para probar si el dispositivo puede comunicarse con Z-Wave Gateway o Panel de control:

-   Coloque la puerta de enlace/panel en modo de prueba de alcance (Prueba de caminata).
-   Presione el botón de función en el dispositivo.
-   La puerta de enlace/panel debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual de operación de la puerta de enlace/panel).
-   _Capacidad del dispositivo enrutador Z-Wave_

El interruptor de encendido permite que otros dispositivos Z-Wave se unan a la red Z-Wave a través del enrutador. La capacidad máxima de los dispositivos para unirse a la Red Z-Wave a través del Power Switch es de 255.

Operación

-   _**Control de electrodomésticos**_
-   Después de incluirlo en una puerta de enlace o panel de control Z-Wave, conecte un electrodoméstico al interruptor de encendido. Los datos de potencia y uso de energía de este electrodoméstico se transferirán al Panel de control.
-   Los usuarios pueden encender/apagar remotamente el aparato eléctrico a través del Panel de control (consulte el manual del Panel de control).
-   Al presionar el botón de función en el interruptor de encendido también se puede activar/desactivar el interruptor de encendido.
-   El interruptor de encendido transmite una señal con datos de energía al panel/puerta de enlace Z-Wave cada 10 minutos a partir de la última vez que se transmitió una señal.
-   Cuando se vuelve a enchufar el interruptor de alimentación después de haberlo desconectado de la toma de corriente, el estado anterior de encendido/apagado del interruptor de alimentación se reanudará inmediatamente.
-   _**Monitor de consumo de energía (solo PSM-29ZW)**_
-   Si la potencia de salida es inferior a 1 kW, PSM-29 transmitirá una señal al panel/puerta de enlace Z-Wave cuando la potencia se desvíe en +/- 2 W para actualizar la información de potencia del PSM-29.
-   Si la potencia de salida es superior a 1 kW, PSM-29 transmitirá una señal al panel/puerta de enlace Z-Wave cuando la potencia se desvíe en +/- 5 W para actualizar la información de potencia del PSM-29.
-   El interruptor de encendido transmite una señal con datos de energía al panel/puerta de enlace Z-Wave cada vez que el uso de energía aumenta en 0,1 kW/h.
-   Cuando la potencia es inferior a 20 W, es más probable que se produzcan errores de medición.
-   _**Especificación de energía**_
-   Para**110V:**la carga máxima de operación es 1760W y 16A. Advertencia: no exceda la carga máxima.
-   Para**230V:**la carga máxima de operación es 3680W y 16A. Advertencia: no exceda la carga máxima.
-   Si el interruptor de encendido se sobrecalienta, cortará la energía automáticamente como medida de seguridad. El interruptor de alimentación debe desconectarse y volverse a enchufar después de cortarlo para reanudar el funcionamiento normal.
-   _**Información de onda Z**_

**Tipo de dispositivo:**Interruptor de encendido/apagado

**Tipo de rol:**Siempre en esclavo (AOS)

**Soporte/Control de Clase de Comando**

**Soporte CC obligatorio:**Asociación CC, v2 o más reciente

Información del grupo de asociación CC

Medidor CC, v2

CC básico

Interruptor binario CC

Restablecimiento del dispositivo localmente CC

CC específico del fabricante

Nivel de potencia CC

Versión CC, v2 o más reciente

Z-Wave Plus Información CC

**Soporte CC recomendado:**Metadatos de actualización de firmware CC

-   _**Grupos de Z-Wave (clase de comando de asociación versión 2)**_

El Switch se puede configurar para enviar informes a dispositivos Z-Wave asociados. Admite un grupo de asociación con soporte de cinco nodos para el Grupo 1. Para el Grupo 1, el conmutador informará su último estado al panel/puerta de enlace Z-Wave.

El grupo 1 incluye:

Interruptor binario CC (INTERRUPTOR_BINARIO_INFORME)

Medidor CC, v2 (METRO_INFORME_DOMINIO)

Restablecimiento del dispositivo localmente CC (COMANDO_CLASE_DISPOSITIVO_REINICIAR_EN LA ZONA)

-   Informe automático al Grupo 1 (Nodo máximo 5)
-   Informe de evento activado/desactivado

Al alternar entre Encendido/Apagado, enviará un Informe de cambio binario a los nodos del Grupo 1.

-   Restablecimiento de fábrica

Cuando el interruptor de encendido se restablece a los valores predeterminados de fábrica, enviará el reinicio del dispositivo localmente a todos los nodos del grupo 1.
