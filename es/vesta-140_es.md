# VESTA 140

**Controlador de relé Z-Wave PRL-8-ZW-AC**

**Introducción**

PRL-8-ZW-AC es un controlador de relé Z-Wave que se puede conectar a dispositivos cableados y configurar en estado de apertura normal (N.O.) o cierre normal (N.C.). Después de unirse a la red Z-Wave, el controlador de relé se puede controlar a través de la red Z-Wave para activar los dispositivos conectados. Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. El controlador de relé Z-Wave permite el acceso a la clase "S2 no autenticado".

**Identificación de piezas**

**1. Botón de función**

![](<.gitbook/assets/0 (53).jpeg>)

Presione el botón 3 veces en 1,5 segundos para enviar un código de aprendizaje.

Mantenga presionado el botón durante 10 segundos para restablecer los valores de fábrica.

Presione el botón para encender/apagar el relé.

**2. Indicador LED (rojo)**

El indicador LED se utiliza para indicar el estado del relé:

-   LED encendido: relé encendido
-   LED apagado: Relé apagado

**Terminales de conexión**

Conecte el cable al terminal, apriete el tornillo para cerrar la cortadora y mantenga el cable en su lugar. Desatornille para abrir el cortapelos y quitar el cable conectado al terminal.

1.  **Línea (entrada de CA)**
2.  **Neutral**
3.  **NO**

Para conexión normal abierta con el dispositivo.

1.  **Común**
2.  **CAROLINA DEL NORTE**

Para conexión normal cercana con el dispositivo

**8. Abrazadera de alivio de tensión**

La abrazadera se utiliza para asegurar los cables y proporcionar alivio de tensión para proteger los cables del recorte de metal.

**9. Hebilla de cableado**

La hebilla de cableado se utiliza para gestionar los cables.

**Especificación**

-   Fuente de alimentación (alimentación externa): 100-240 VCA
-   Salida de relé: relé SPDT libre de potencial, carga máxima de operación: 10 A (resistiva) a 24 V CC o 240 V CA
-   Cable trenzado: 14~22 CAE
-   Temperatura de funcionamiento: -10 °C a 45 °C (14 °F a 113 °F)
-   Humedad: Hasta 85% sin condensación
-   Dimensiones: 86 mm x 72 mm x 29 mm

![](<.gitbook/assets/1 (45).jpeg>)

**Entorno de instalación**

-   El controlador de relé debe instalarse en interiores, en un lugar seco.

1

-   Se recomienda instalar el dispositivo en una caja de distribución de plástico resistente al fuego.
-   No instale el dispositivo en una caja de distribución metálica para optimizar el alcance Z-Wave.

![](<.gitbook/assets/2 (41).jpeg>)

**Precaución**

-   Todos los trabajos en el dispositivo, incluida la instalación y el mantenimiento, deben ser realizados por un electricista calificado y autorizado.
-   Para evitar descargas eléctricas y/o daños al equipo, desconecte la energía eléctrica en el fusible principal o en el disyuntor antes de la instalación y el mantenimiento.

No conecte el dispositivo a cargas que excedan la corriente de carga admitida.

**Instalación**

![](<.gitbook/assets/3 (38).jpeg>)

El cableado del PRL solo debe realizarlo un técnico certificado con el conocimiento y la capacitación adecuados en equipos eléctricos. Conecte el relé de acuerdo con las instrucciones a continuación:

1.  Apague la fuente de alimentación antes de la conexión.
2.  Retire la cubierta superior y retire la abrazadera de alivio de tensión.
3.  Conecte los terminales L y N de la fuente de alimentación a los terminales de Línea y Neutro de PRL respectivamente a través del orificio de cableado.
4.  Dependiendo del dispositivo que desee controlar a través del relé, seleccione el terminal NO o NC y conecte el relé con el dispositivo para establecer una conexión de apertura normal o cierre normal con el dispositivo.
5.  Después de completar el cableado del dispositivo, reemplace la abrazadera de alivio de tensión, use

la hebilla de cableado para gestionar los cables y coloque la hebilla de cableado en la base con su espacio (abertura) colocado a la izquierda (como en el diagrama a continuación).

![](<.gitbook/assets/4 (39).jpeg>)

1.  Vuelva a colocar la cubierta superior. Encienda la fuente de alimentación para encender el controlador de relé.

**Red Z-Wave**

![](<.gitbook/assets/5 (51).png>)

-   _**Agregar dispositivo (inclusión)**_
    -   Conecte la fuente de alimentación al controlador de relé de acuerdo con las instrucciones de instalación de la sección anterior y encienda el controlador de relé.
    -   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de inclusión** (please refer to the Z-Wave gateway or control panel manual).
    -   En 1,5 segundos, presione el botón de función 3 veces.
    -   Consulte el manual de funcionamiento de la puerta de enlace Z-Wave o del panel de control para completar el proceso de adición.
    -   Si el dispositivo ya se ha agregado (incluido) en otra puerta de enlace/panel de control Z-Wave, o si el dispositivo no se puede agregar a la puerta de enlace/panel de control Z-Wave actual, intente eliminarlo primero (consulte_**Quitar dispositivo**_).
-   _**Eliminación del dispositivo (exclusión)**_

![](<.gitbook/assets/6 (33).png>)

El dispositivo debe eliminarse de la red Z-Wave existente antes de agregarlo a otra.**Modo de exclusión**

-   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de exclusión**(consulte el manual de la puerta de enlace Z-Wave o del panel de control).
-   En 1,5 segundos, presione el botón de función 3 veces y el dispositivo se eliminará de la red Z-Wave.

**Restablecimiento de fábrica**

2

-   -   El restablecimiento de fábrica del dispositivo lo restaurará a la configuración predeterminada de fábrica (es decir, no estará incluido en ninguna red Z-Wave). Utilice este procedimiento únicamente si la puerta de enlace Z-Wave o el panel de control se pierden o no funcionan.
    -   Mantenga presionado el botón de función del dispositivo durante 10 segundos para restablecer los valores de fábrica.
-   _**Prueba de rango**_

![](<.gitbook/assets/7 (28).png>)

Para probar si el dispositivo puede comunicarse con la puerta de enlace Z-Wave o el panel de control:

-   Coloque la puerta de enlace/panel en modo de prueba de alcance (Walk Test).
-   Presione el botón de función en el dispositivo.
-   La puerta de enlace/panel debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual de operación de la puerta de enlace/panel).

**Operación**

![](<.gitbook/assets/8 (23).jpeg>)

-   _**Control de relé**_
    -   Cuando el controlador de relé se haya unido exitosamente a una red Z-Wave, la puerta de enlace/panel de control podrá controlar remotamente el relé para encenderlo, apagarlo o alternar entre la condición de encendido y apagado. Consulte su puerta de enlace/panel de control Z-Wave para obtener más detalles.

**Información de onda Z**

**Tipo de dispositivo:**Interruptor de encendido/apagado

**Tipo de rol:**Siempre en esclavo (AOS)

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

Cambiar CC binario

Supervisión CC, (S2)

Actualización de firmware Md CC, (S2)

-   _**Grupos de Z-Wave (clase de comando de asociación versión 2)**_

El Switch se puede configurar para enviar informes a dispositivos Z-Wave asociados. Admite un grupo de asociación con soporte de cinco nodos para el Grupo 1. Para el Grupo 1, el conmutador informará su último estado al panel/puerta de enlace Z-Wave.

Agrupación 1 para “LifeLine”: (nodo máximo: 5)

Cambiar CC binario (COMANDO_CLASE_CAMBIAR_BINARIO)

Restablecimiento del dispositivo localmente CC (COMANDO_CLASE_DISPOSITIVO_REINICIAR_EN LA ZONA)

Al alternar entre Encendido/Apagado, enviará un Informe de cambio binario a los nodos del Grupo 1.

3
