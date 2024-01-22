# VESTA 169

**Controlador de relé Z-Wave PRL1-ZW-AC**

**Introducción**

PRL1-ZW-AC es un controlador de relé Z-Wave que se puede conectar a dispositivos cableados y configurar en estado de apertura normal (N.O.) o cierre normal (N.C.). Después de unirse a la red Z-Wave, el controlador de relé se puede controlar a través de la red Z-Wave para activar los dispositivos conectados. Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia.

**Identificación de piezas**

![](<.gitbook/assets/0 (62).jpeg>)

**1. Indicador LED**

El indicador LED se utiliza para indicar el estado del relé:

-   -   LED encendido: relé encendido
    -   LED apagado: Relé apagado

1.  **Botón de función**

Presione el botón 3 veces en 1,5 segundos para enviar un código de aprendizaje.

Mantenga presionado el botón durante 10 segundos para restablecer los valores de fábrica.

Presione el botón para encender/apagar el relé.

**Terminales de conexión**

Para realizar la conexión del cable, empuje el cable dentro del terminal y manténgalo en su lugar. Para quitar el cable conectado, presione el botón que se encuentra encima del terminal y luego retire el cable.

1.  **Reservado**
2.  **Line (AC input)**
3.  **Neutral**
4.  **NO**

![](<.gitbook/assets/1 (55).jpeg>)

Para conexión normal abierta con el dispositivo.

1.  **Común**
2.  **CAROLINA DEL NORTE**

Para conexión normal cercana con el dispositivo

**Especificación**

-   Fuente de alimentación (alimentación externa): 100-240 VCA
-   Salida de relé: relé SPDT libre de potencial, carga máxima de operación: 5 A (resistiva) a 24 V CC o 240 V CA
-   Cable trenzado: 16-26 AWG
-   Operating Temperature: -10°C to 45°C (14°F to 113°F)
-   Humedad: Hasta 85% sin condensación
-   Dimensiones: 71,1 mm x 49 mm x 26 mm

![](<.gitbook/assets/2 (49).jpeg>)

**Entorno de instalación**

-   El controlador de relé debe instalarse en interiores, en un lugar seco.
-   Se recomienda instalar el dispositivo en una caja de distribución de plástico resistente al fuego.
-   No instale el dispositivo en una caja de distribución metálica para optimizar el alcance de RF.

![](<.gitbook/assets/3 (45).jpeg>)

**Precaución**

-   Todos los trabajos en el dispositivo, incluida la instalación y el mantenimiento, deben ser realizados por un electricista calificado y autorizado.
-   Para evitar descargas eléctricas y/o daños al equipo, desconecte la energía eléctrica en el fusible principal o en el disyuntor antes de la instalación y el mantenimiento.
-   No conecte el dispositivo a cargas que excedan la corriente de carga admitida.

1

**Installation**

La especificación de cableado de los orificios de inserción es AWG 16-26 o Ø 1,31-0,129 (mm²).

Conecte el relé de acuerdo con las instrucciones a continuación:

![](<.gitbook/assets/4 (44).jpeg>)

1.  Apague la fuente de alimentación antes de la conexión.
2.  Conecte los terminales L y N de la fuente de alimentación a los terminales de Línea y Neutro de PRL respectivamente.
3.  Dependiendo del dispositivo que desee controlar a través del relé, seleccione el terminal NO o NC y conecte el relé con el dispositivo para establecer una conexión de apertura normal o cierre normal con el dispositivo.
4.  Después de completar el cableado del dispositivo, encienda la fuente de alimentación para encender el controlador de relé.

![](<.gitbook/assets/5 (57).png>)

_\\<IMPORTANT NOTE>_

-   El cableado del PRL sólo debe ser realizado por personal certificado.

Técnico con conocimientos y formación adecuados en equipos eléctricos.

**Red Z-Wave**

![](<.gitbook/assets/6 (39).png>)

-   _**Agregar dispositivo (inclusión)**_
    -   Conecte la fuente de alimentación al controlador de relé de acuerdo con las instrucciones de instalación de la sección anterior y encienda el controlador de relé.
    -   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de inclusión**(consulte el manual de la puerta de enlace Z-Wave o del panel de control).
    -   En 1,5 segundos, presione el botón de función 3 veces.
    -   Consulte el manual de funcionamiento de la puerta de enlace Z-Wave o del panel de control para completar el proceso de adición.
    -   Si el dispositivo ya se ha agregado (incluido) en otra puerta de enlace/panel de control Z-Wave, o si el dispositivo no se puede agregar a la puerta de enlace/panel de control Z-Wave actual, intente eliminarlo primero (consulte_**Quitar dispositivo**_).
-   _**Eliminación del dispositivo (exclusión)**_

![](<.gitbook/assets/7 (33).png>)

El dispositivo debe eliminarse de la red Z-Wave existente antes de agregarlo a otra.**Modo de exclusión**

-   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de exclusión**(consulte el manual de la puerta de enlace Z-Wave o del panel de control).
-   En 1,5 segundos, presione el botón de función 3 veces y el dispositivo se eliminará de la red Z-Wave.

**Restablecimiento de fábrica**

-   -   El restablecimiento de fábrica del dispositivo lo restaurará a la configuración predeterminada de fábrica (es decir, no estará incluido en ninguna red Z-Wave). Utilice este procedimiento únicamente si la puerta de enlace Z-Wave o el panel de control se pierden o no funcionan.
    -   Mantenga presionado el botón de función del dispositivo durante 10 segundos para restablecer los valores de fábrica.
-   _**Prueba de rango**_

![](<.gitbook/assets/8 (34).png>)

Para probar si el dispositivo puede comunicarse con la puerta de enlace Z-Wave o el panel de control:

-   Coloque la puerta de enlace/panel en modo de prueba de alcance (Walk Test).
-   Presione el botón de función en el dispositivo.
-   La puerta de enlace/panel debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual de operación de la puerta de enlace/panel).

**Operación**

![](<.gitbook/assets/9 (20).jpeg>)

-   _**Control de relé**_
    -   Cuando el controlador de relé se haya unido exitosamente a una red Z-Wave, la puerta de enlace/panel de control podrá controlar remotamente el relé para encenderlo, apagarlo o alternar entre la condición de encendido y apagado. Consulte su puerta de enlace/panel de control Z-Wave para obtener más detalles.

2

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

Version CC, v2 or newer

Z-Wave Plus Información CC

**Soporte CC recomendado**: Metadatos de actualización de firmware CC

![](<.gitbook/assets/10 (35).png>)

-   _**Grupos de Z-Wave (clase de comando de asociación versión 2)**_

El Switch se puede configurar para enviar informes a dispositivos Z-Wave asociados. Admite un grupo de asociación con soporte para cinco nodos para el Grupo 1. Para el Grupo 1, el conmutador informará su último estado al panel/puerta de enlace Z-Wave.

Grupo 1 para “LifeLine”:

Interruptor binario CC (INTERRUPTOR_BINARIO_INFORME)

Restablecimiento del dispositivo localmente CC (COMANDO_CLASE_DISPOSITIVO_REINICIAR_EN LA ZONA)

-   Informe automático al Grupo 1 (Nodo máximo 5)
-   Informe de evento activado/desactivado

Al alternar entre Encendido/Apagado, enviará un Informe de cambio binario a los nodos del Grupo 1.

3
