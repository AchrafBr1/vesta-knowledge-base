# VESTA 206

**Interruptor de palanca de relé Z-Wave PRL-3ZW-AC**

**Introducción**

PRL-3ZW-AC es un interruptor de palanca de relé Z-Wave. El interruptor de palanca de relé se puede conectar a un dispositivo cableado y configurar en estado de apertura normal (N.O.). Después de unirse a la red Z-Wave, el interruptor de palanca de relé se puede controlar a través de la red Z-Wave para activar los dispositivos conectados.

Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. Al aprovechar la red de malla Z-Wave, los comandos se pueden enrutar a su destino a través de productos Z-Wave intermediarios que “escuchan”.

El relé puede controlar los nodos Z-Wave simplemente presionando el botón de función y también puede alertarlo sobre problemas de comunicación de señales.

La serie de interruptores de palanca de relé Z-Wave incluye los siguientes modelos:

PRL-3ZW-AC

PRL-xZO-AS-OTA

**Identificación de piezas**

![](<.gitbook/assets/0 (84).jpeg>)

**1. Indicador LED**

El indicador LED se utiliza para indicar el estado del relé:

-   -   LED encendido: relé encendido
    -   LED apagado: Relé apagado

1.  **Botón de función**

Presione el botón 3 veces en 1,5 segundos para enviar un código de aprendizaje.

Mantenga presionado el botón durante 10 segundos para restablecer los valores de fábrica.

Presione el botón para encender/apagar el relé.

**Terminales de conexión**

Conecte el cable al terminal, apriete el tornillo para cerrar la cortadora y mantenga el cable en su lugar. Desatornille para abrir el cortapelos y quitar el cable conectado al terminal.

1.  **Neutral**
2.  **Línea (entrada de CA)**

Para encender el PRL-3ZW, conecte los terminales L&N de la fuente de alimentación a los terminales L&N.

**5. NO**

Para conexión normal abierta con el dispositivo

**6. común**

Conecte los terminales NO y COM del dispositivo cableado a los terminales NO y COM del PRL-3ZW.

**Especificación**

-   Fuente de alimentación (alimentación externa): 100-240 VCA
-   Salida de relé: Relé SPDT libre de potencial, Carga máxima de operación: 5 A (resistiva) a 24 V CC o 240 V CA.
-   Cable trenzado: 14~22 CAE
-   Temperatura de funcionamiento: -10 °C a 45 °C (14 °F a 113 °F)
-   Humedad: Hasta 85% sin condensación
-   Dimensiones: 71 mm x 49 mm x 26 mm

![](<.gitbook/assets/1 (73).jpeg>)

**Entorno de instalación**

-   El interruptor de palanca de relé debe instalarse en interiores, en un lugar seco.
-   Se recomienda instalar el dispositivo en una caja de distribución de plástico resistente al fuego.
-   No instale el dispositivo en una caja de distribución metálica para optimizar el alcance Z-Wave.

1

![](<.gitbook/assets/2 (69).jpeg>)

**Precaución**

-   All works on the device, including installation and maintenance, must be performed by a qualified and licensed electrician.
-   Para evitar descargas eléctricas y/o daños al equipo, desconecte la energía eléctrica en el fusible principal o en el disyuntor antes de la instalación y el mantenimiento.
-   No conecte el dispositivo a cargas que excedan

![](<.gitbook/assets/3 (62).jpeg>)

corriente de carga soportada.

**Instalación**

Conecte el relé de acuerdo con las instrucciones a continuación o consulte el diagrama para obtener más información.

1.  Apague la fuente de alimentación antes de realizar la conexión.
2.  Conecte los terminales L y N de la fuente de alimentación a los terminales de Línea y Neutro de PRL respectivamente.
3.  Dependiendo del dispositivo que desee controlar a través del relé, seleccione el terminal NO y conecte el relé con el dispositivo para establecer una conexión abierta normal con el dispositivo.
4.  Después de completar el cableado, encienda la fuente de alimentación para encender el interruptor de palanca del relé.

![](<.gitbook/assets/4 (68).png>)

_\\<IMPORTANT NOTE>_

-   El cableado del PRL solo debe realizarlo un técnico certificado con el conocimiento y la capacitación adecuados en equipos eléctricos.

**Características**

![](<.gitbook/assets/5 (70).png>)

-   _**Agregar dispositivo (inclusión)**_
    -   Conecte la entrada de alimentación al interruptor de palanca de relé de acuerdo con las instrucciones de instalación anteriores y encienda el interruptor de palanca de relé.
    -   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de inclusión**(consulte el manual de la puerta de enlace Z-Wave o del panel de control).
    -   En 1,5 segundos, presione el botón de función 3 veces.
    -   Consulte el manual de funcionamiento de la puerta de enlace Z-Wave o del panel de control para completar el proceso de adición.
    -   Si el dispositivo ya se ha agregado (incluido) en otra puerta de enlace/panel de control Z-Wave, o si el dispositivo no se puede agregar a la puerta de enlace/panel de control Z-Wave actual, intente eliminarlo primero (consulte_**Quitar dispositivo**_).
-   _**Removing Device (Exclusion)**_

![](<.gitbook/assets/6 (49).png>)

El dispositivo debe eliminarse de la red Z-Wave existente antes de agregarlo a otra.**Modo de exclusión**

-   Coloque la puerta de enlace Z-Wave o el panel de control en**Exclusion mode**(consulte el manual de la puerta de enlace Z-Wave o del panel de control).
-   En 1,5 segundos, presione el botón de función 3 veces y el dispositivo se eliminará de la red Z-Wave.

**Restablecimiento de fábrica**

-   -   El restablecimiento de fábrica del dispositivo lo restaurará a la configuración predeterminada de fábrica (es decir, no estará incluido en ninguna red Z-Wave). Utilice este procedimiento únicamente si la puerta de enlace Z-Wave o el panel de control se pierden o no funcionan.
    -   Mantenga presionado el botón de función del dispositivo durante 10 segundos para restablecer los valores de fábrica.
-   _**Prueba de rango**_

![](<.gitbook/assets/7 (45).png>)

Para probar si el dispositivo puede comunicarse con la puerta de enlace Z-Wave o el panel de control:

-   Coloque la puerta de enlace/panel en modo de prueba de alcance (Walk Test).
-   Presione el botón de función en el dispositivo
-   La puerta de enlace/panel debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual de operación de la puerta de enlace/panel).

2

**Operación**

![](<.gitbook/assets/8 (40).jpeg>)

-   _**Control de relé**_
    -   Después de que el interruptor de palanca del relé se haya agregado exitosamente a una red Z-Wave, la puerta de enlace/panel de control puede controlar remotamente el relé para encenderlo, apagarlo o alternar entre la condición de encendido y apagado. Consulte su puerta de enlace/panel de control Z-Wave para obtener más detalles.

**Información de onda Z**

**Tipo de dispositivo:**Interruptor de encendido/apagado

**Tipo de rol:**Siempre en esclavo (AOS)

**Soporte/Control de Clase de Comando**

**Soporte CC obligatorio:**Asociación CC, v2 o más reciente

Información del grupo de asociación CC

CC básico

Interruptor binario CC

Restablecimiento del dispositivo localmente CC

CC específico del fabricante

Nivel de potencia CC

Versión CC, v2 o más reciente

Z-Wave Plus Información CC

**Soporte CC recomendado**: Metadatos de actualización de firmware CC

![](<.gitbook/assets/9 (41).png>)

-   _**Grupos de Z-Wave (clase de comando de asociación versión 2)**_

El Switch se puede configurar para enviar informes a dispositivos Z-Wave asociados. Admite un grupo de asociación con soporte para cinco nodos para el Grupo 1. Para el Grupo 1, el conmutador informará su último estado al panel/puerta de enlace Z-Wave.

Grupo 1 para “LifeLine”:

Interruptor binario CC (INTERRUPTOR_BINARIO_INFORME)

Restablecimiento del dispositivo localmente CC (COMANDO_CLASE_DISPOSITIVO_REINICIAR_EN LA ZONA)

-   Informe automático al Grupo 1 (Nodo máximo 5)
-   Informe de evento activado/desactivado

Al alternar entre Encendido/Apagado, enviará un Informe de cambio binario a los nodos del Grupo 1.

3
