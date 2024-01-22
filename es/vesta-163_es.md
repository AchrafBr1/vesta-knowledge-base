# VESTA 163

**PRS5-P5-ZW**

**Interruptor de relé de potencia Z-Wave**

**Introducción**

El interruptor de relé de alimentación es capaz de recibir señales inalámbricas del coordinador en la red Z-Wave para activar o desactivar los aparatos conectados a él.

El interruptor de relé de alimentación es un dispositivo habilitado para Z-Wave y es totalmente compatible con cualquier red habilitada para Z-Wave.

Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. Aprovechando la red de malla Z-Wave, los comandos se pueden transmitir a su destino a través de productos Z-Wave intermediarios que "escuchan".

PRS5-P5-ZW también sirve como enrutador en la red Z-Wave. Después de ser incluido en la red Z-Wave, permite que otros dispositivos Z-Wave se unan a la red a través del interruptor de encendido.

**Identificación de piezas**

![](<.gitbook/assets/0 (58).jpeg>)

**1. Indicador LED**

El indicador LED se utiliza para indicar el estado del interruptor del relé de alimentación:

-   -   En:

El interruptor del relé de alimentación está encendido.

-   -   Apagado:

El interruptor del relé de alimentación está apagado.

-   -   Parpadea dos veces:

El interruptor de relé de alimentación se ha agregado correctamente a la red Z-Wave.

-   -   Parpadea tres veces

El interruptor de relé de alimentación se ha vinculado correctamente con un controlador.

-   -   Parpadea cinco veces

El interruptor de relé de alimentación no pudo vincularse con un controlador.

1.  **Botón de función**

El botón de función se utiliza para controlar el interruptor del relé de alimentación:

**Uso del botón de función:**

-   -   Presione el botón para activar/desactivar el interruptor del relé de alimentación
    -   Presione el botón 3 veces en 1,5 segundos para enviar un código de aprendizaje.
    -   Mantenga presionado el botón durante 3 segundos y luego suéltelo para vincularlo con un controlador
    -   Mantenga presionado el botón durante 10 segundos para restablecer los valores de fábrica.

1.  **Cable de conexión del interruptor externo 1 (rojo)**
2.  **Cable de conexión del interruptor externo 2 (naranja)**
3.  **Salida de carga de alimentación de línea de CA (amarillo)**
4.  **Entrada de energía neuronal de CA/Salida de carga de energía neutra de CA (azul)**
5.  **Entrada de alimentación de línea de CA (marrón)**

**Precaución**

-   Todos los trabajos en el dispositivo, incluida la instalación y el mantenimiento, deben ser realizados por un electricista calificado y autorizado.
-   Antes de la instalación o cualquier trabajo de mantenimiento, asegúrese de que la fuente de alimentación esté desconectada.
-   No conecte el dispositivo a cargas que excedan la corriente de carga admitida.

**Instalación**

-   _**Cableado con conector de empalme**_
    -   El interruptor de relé de alimentación viene con un cable integrado para conectarlo a una fuente de alimentación de CA, un electrodoméstico y un interruptor externo. Se proporcionan cinco conectores de empalme Wago 221 para la conexión.
    -   Los conectores de 2 y 3 hilos admiten cables sólidos y trenzados de 0,2 a 4 mm² (24–12 AWG).
    -   Antes de realizar el cableado, asegúrese de que la alimentación esté apagada. Para conectar los cables:

1

1.  Levante la palanca e inserte el cable marrón.**(Imagen 1, 2)**

![](<.gitbook/assets/1 (52).png>)

**Foto 1****Imagen 2**

1.  Empuje la palanca hacia abajo. La carcasa transparente le permite comprobar si el cable está conectado correctamente. Asegúrese de que el cable esté sujeto firmemente en su lugar y no se salga.**(Imagen 3, 4)**

![](<.gitbook/assets/2 (56).png>)

|                                                          | **Imagen 3**                       | **Imagen 4** |   |
| -------------------------------------------------------- | ---------------------------------- | ------------ | - |
| 3) De la misma manera que en los pasos 1 y 2, inserte en | otro polo el cable para conectar a |              |   |
| Entrada de alimentación de línea de CA.**(Imagen 5)**    |                                    |              |   |
|                                                          |                                    |              |   |
|                                                          |                                    |              |   |

![](<.gitbook/assets/3 (43).jpeg>)

**Imagen 5**

1.  Repita los pasos 1, 2 y 3 para conectar los otros cables con conectores.

Tenga en cuenta que el cable azul debe conectarse a un conector de 3 cables y luego conectarse a la entrada de energía neuronal de CA y a la salida de carga de energía neutra de CA.**(Imagen 6)**

![](<.gitbook/assets/4 (56).png>)

**Imagen 6**

**Configuración de red Z-Wave**

-   _**Agregar dispositivo (inclusión)**_

Este producto se puede incluir y operar en cualquier red Z-Wave con otros dispositivos certificados Z-Wave de otros fabricantes y/u otras aplicaciones. Todos los nodos de la red que no funcionan con baterías actuarán como repetidores independientemente del proveedor para aumentar la confiabilidad de la red.

-   Conecte el interruptor del relé de alimentación al cable de alimentación.
-   El interruptor del relé de alimentación emitirá un pitido de dos tonos.
-   Coloque la puerta de enlace Z-Wave o el panel de control en**Inclusión**o**Aprendiendo**modo (consulte el manual de la puerta de enlace Z-Wave o del panel de control).

2

-   -   En 1,5 segundos, presione el botón de función 3 veces. El interruptor del relé de alimentación emitirá un pitido de dos tonos.
    -   Consulte el manual de funcionamiento de la puerta de enlace Z-Wave o del panel de control para completar el proceso de aprendizaje.
    -   Si el sensor ya ha sido**incluido**(aprendido) en otra puerta de enlace/panel de control Z-Wave, o si el sensor no se puede aprender en la puerta de enlace/panel de control Z-Wave actual, exclúyalo primero (consulte_**Exclusión**_) antes de intentar**incluir**en el panel de control/puerta de enlace Z-Wave actual.
-   _**Eliminación del dispositivo (exclusión)**_

El interruptor de relé de alimentación debe retirarse de la red Z-Wave existente antes de incluirlo en otra. Hay dos métodos disponibles para excluir un dispositivo.

**Modo de exclusión**

-   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de exclusión**(consulte el manual de la puerta de enlace Z-Wave o del panel de control).
-   En 1,5 segundos, presione el botón de función 3 veces y el interruptor del relé de alimentación se eliminará de la red Z-Wave.

**Restablecimiento de fábrica**

_(Utilice el restablecimiento de fábrica únicamente cuando falte el panel de control/puerta de enlace de la red o no esté operativo)._

-   -   Mantenga presionado el botón de función durante 10 segundos para restablecer los valores de fábrica.

_\\<NOTE>_

-   -   -   El restablecimiento de fábrica del interruptor de relé de alimentación lo restaurará a la configuración predeterminada de fábrica (excluido de la red Z-Wave). La puerta de enlace o el panel de control Z-Wave seguirán manteniendo su configuración Z-Wave. Consulte el manual de la puerta de enlace o del panel de control sobre cómo eliminar la configuración Z-Wave del interruptor de relé de alimentación.
-   _**Prueba de rango**_

Para probar si el dispositivo puede comunicarse con la puerta de enlace Z-Wave o el panel de control:

-   -   Coloque la puerta de enlace/panel en modo de prueba de alcance (Walk Test).
    -   Presione el botón de función en el dispositivo.
    -   La puerta de enlace/panel debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual de operación de la puerta de enlace/panel).
-   _**Modo de suspensión Z-Wave**_
    -   El interruptor de relé de alimentación entrará en el modo de suspensión Z-Wave (para conservar energía) después de despertarse por un corto período de tiempo (~10 segundos). Mientras está en el modo de suspensión Z-Wave, las puertas de enlace o los paneles de control Z-Wave no pueden enviar comandos al interruptor de relé de alimentación.
    -   Para programar el interruptor del relé de alimentación, envíe comandos al interruptor del relé de alimentación dentro del período de activación.
-   _**Vinculación con el controlador**_

Después de unirse a la red Z-Wave, el Power Relay Switch puede vincularse con un dispositivo controlador que se puede usar para ajustar el nivel de salida de potencia del Power Relay Switch. Para vincular el interruptor de relé de alimentación y el dispositivo:

1.  Mantenga presionado el botón de función durante 3 segundos y luego suelte el botón. El interruptor de relé de potencia enviará una solicitud vinculante al coordinador.
2.  Consulte el manual de su controlador para enviar una solicitud vinculante para el dispositivo en un plazo de 16 segundos.
3.  Si la vinculación se realiza correctamente, el indicador LED del interruptor del relé de alimentación parpadeará 3 veces para confirmar. Ahora puede usar el controlador para ajustar el nivel de salida de energía para el interruptor de relé de alimentación.
4.  Si la vinculación no tiene éxito, el indicador LED del interruptor del relé de alimentación parpadeará 5 veces. Vuelva a intentar el proceso de vinculación.

![](<.gitbook/assets/5 (27).jpeg>)

**Operación**

-   _**Diagrama de conexión de cables**_
    -   Consulte el diagrama para conectar la iluminación de su hogar al interruptor de relé de alimentación.
-   _**Instalación**_
    -   Conecte el interruptor del relé de alimentación al cable de alimentación.
    -   Conecte el interruptor de relé de alimentación a la iluminación de su hogar. La iluminación debe estar en estado ON.
    -   Puede conectar un interruptor externo al interruptor del relé de alimentación según el diagrama para encender/apagar el interruptor del relé de alimentación.

3

-   -   _**NOTA IMPORTANTE**_**:**El interruptor de relé de alimentación no tiene una batería de respaldo y se apagará cuando falle la alimentación de CA.**NO**use el interruptor de relé de alimentación como enrutador para su sensor de seguridad o dispositivos de control de alarma, como contacto de puerta, sensor PIR, etc.; de lo contrario, los sensores perderán la conexión a la red Z-Wave si el interruptor de relé de alimentación se desconecta de la alimentación de CA. Planifique las ubicaciones de instalación de estos sensores de seguridad sin utilizar el interruptor de relé de alimentación y utilice únicamente un enrutador con batería de respaldo para ellos. La función de enrutador del interruptor de encendido debe**SOLO**Se puede utilizar para proporcionar una extensión del rango de señal para otros interruptores/atenuadores de alimentación.
-   _**Control de electrodomésticos**_
    -   Después de que el interruptor de relé de alimentación se haya unido con éxito a una red Z-Wave, el coordinador puede encender/apagar el dispositivo de forma remota.
    -   También puede presionar el botón en el interruptor del relé de alimentación para encender/apagar la luz.
    -   Puede encender/apagar el interruptor del relé de alimentación con un interruptor externo.
    -   Si ha vinculado un controlador con el interruptor de relé de alimentación, también puede utilizar el controlador para encender/apagar el interruptor de relé de alimentación.
    -   Si la entrada de alimentación de CA se desconecta del interruptor del relé de alimentación, su estado anterior de encendido/apagado se restaurará dentro de 1 minuto después de volver a conectar la entrada de alimentación de CA al interruptor del relé de alimentación.
-   _**Carga máxima de operación**_
    -   Para 110V: la carga máxima de operación es 1100W y 10A.
    -   Para 230V: la carga máxima de funcionamiento es de 2300W y 10A.
    -   Si el interruptor del relé de alimentación se sobrecalienta, cortará la energía automáticamente como medida de seguridad. El usuario debe desconectar y volver a conectar la alimentación de CA al interruptor de relé de alimentación después del corte para reanudar el funcionamiento normal.
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

The Switch can be set to send reports to associated Z-Wave devices. It supports one association group with five node support for Grouping 1. For grouping 1, the Switch will report its latest status to Z-Wave Gateway/Panel.

El grupo 1 incluye:

Interruptor binario CC (INTERRUPTOR_BINARIO_INFORME)

Medidor CC, v2 (METRO_INFORME_DOMINIO)

Restablecimiento del dispositivo localmente CC (COMANDO_CLASE_DISPOSITIVO_REINICIAR_EN LA ZONA)

-   Informe automático al Grupo 1 (Nodo máximo 5)
-   Informe de evento activado/desactivado

Al alternar entre Encendido/Apagado, enviará un Informe de cambio binario a los nodos del Grupo 1.

4
