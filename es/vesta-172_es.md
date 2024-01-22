# VESTA 172

**Sensor de calidad del aire (AQS-2-ZW)**

El sensor de calidad del aire AQS-2 es un sensor de calidad del aire interior Z-Wave™ que tiene como objetivo detectar y monitorear la concentración de CO2. El sensor de calidad del aire solo es compatible con el panel de control/puerta de enlace Z-Wave. Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. Al aprovechar la red de malla Z-Wave, los comandos se pueden enrutar a su destino a través de productos Z-Wave intermediarios que “escuchan”.

**Identificación de piezas**

![](<.gitbook/assets/0 (63).jpeg>)

**1. Botón de función**

\-Presione el botón una vez para enviar señales de nivel de concentración de CO2.

\-Presione el botón 3 veces en 1 segundo para transmitir un código de aprendizaje.

\-Mantenga presionado el botón durante 10 segundos para realizar el restablecimiento de fábrica.

**2.****DC Jack**

Se conecta a un adaptador de CC de 12 V y 1 A.

**Características**

![](<.gitbook/assets/1 (54).png>)

-   _**Fuente de alimentación**_

El sensor de calidad del aire se alimenta conectándolo con una salida de 12 V CC y un adaptador de 1 A. Asegúrese de utilizar únicamente un adaptador con la clasificación de voltaje de CA adecuada para evitar daños a los componentes, o utilice únicamente el adaptador de alimentación de CA incluido con el sensor de calidad del aire.

Si se detecta una falla de energía de CA, el sensor de calidad del aire enviará un informe de falla de CA al panel de control.

![](<.gitbook/assets/2 (59).png>)

-   _**Detección de dióxido de carbono**_
    -   El sensor de calidad del aire mide la concentración de CO2 cada 5 segundos y envía datos al panel de control cada 30 minutos. Si la concentración de CO2 cambia en +/- 100 ppm dos veces consecutivas, el sensor de calidad del aire informará al panel de control.
    -   Si la concentración de CO2 detectada es superior a 1000 ppm, el AQS-2 enviará una señal de alarma de CO2 al panel de control. Si la concentración de CO2 cae por debajo de 1000 ppm, el AQS-2 enviará una señal de restauración de CO2 al panel de control.
-   _**Agregar dispositivo (inclusión)**_

![](<.gitbook/assets/3 (60).png>)

Este producto se puede incluir y operar en cualquier red Z-Wave con otros dispositivos certificados Z-Wave de otros fabricantes y/u otras aplicaciones. Todos los nodos de la red que no funcionan con baterías actuarán como repetidores independientemente del proveedor para aumentar la confiabilidad de la red.

-   -   Conecte el adaptador de alimentación de CA; conéctelo al conector CC del sensor de calidad del aire para encenderlo.
    -   Coloque la puerta de enlace Z-Wave o el panel de control en**Inclusión**modo (consulte el manual del Z-Wave Gateway o del panel de control).
    -   En 1 segundo, presione el botón de función 3 veces.
    -   Consulte el manual de operación del Z-Wave Gateway o Panel de Control para completar el proceso de inclusión.
    -   Si el sensor ya ha sido**agregado**(incluido) en otra puerta de enlace/panel de control Z-Wave, o si el sensor no se puede agregar a la puerta de enlace/panel de control Z-Wave actual, exclúyalo primero (consulte_**Quitar dispositivo**_) antes de intentar**incluir**en el panel de control/puerta de enlace Z-Wave actual.
-   _**Eliminación del dispositivo (exclusión)**_

![](<.gitbook/assets/4 (59).png>)

El sensor de calidad del aire debe retirarse de la red Z-Wave existente antes de incluirlo en otra. Hay dos métodos disponibles para excluir un dispositivo.

**Modo de exclusión**

-   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de exclusión**(consulte el manual del Z-Wave Gateway o del panel de control).
-   En 1 segundo, presione el botón de función 3 veces y el dispositivo se eliminará de la red Z-Wave.

1

**Restablecimiento de fábrica**

_(Utilice el restablecimiento de fábrica únicamente cuando falte el panel de control/puerta de enlace de la red o no esté operativo)._

-   Mantenga presionado el botón de función durante 10 segundos para realizar el restablecimiento de fábrica.

_\\<NOTE>_

-   -   El restablecimiento de fábrica del dispositivo lo restaurará a la configuración predeterminada de fábrica (excluido de la red Z-Wave). La puerta de enlace Z-Wave o el panel de control aún mantendrán su configuración Z-Wave. Consulte el manual de la puerta de enlace o del panel de control sobre cómo eliminar la configuración Z-Wave del dispositivo.

![](<.gitbook/assets/5 (59).png>)

**Instalación**

![](<.gitbook/assets/6 (40).png>)

-   _**Colocación del sensor de calidad del aire**_

El sensor de calidad del aire debe colocarse sobre una superficie plana con un área abierta a su alrededor en la habitación que desea monitorear.

Cuanto más abierto sea el lugar de colocación, más precisas serán las mediciones de la calidad del aire.

**Información de onda Z**

**Tipo genérico:**Cambiar multinivel

**Tipo específico:**Color ajustable multinivel

**Identificación del tipo de producto:**0x0004

**ID del Producto:**0x0020

**Tipo de rol:**Siempre en esclavo (AOS)

**Seguridad:**S2 no autenticado

**Soporte/Control de Clase de Comando**

**Soporte CC obligatorio:**Información Z-Wave Plus CC, V2

Sensor Multinivel CC, V11 (seguridad 2)

Asociación CC, V2 (seguridad 2)

Asociación multicanal CC, V3 (seguridad 2)

Información del grupo de asociación CC (seguridad 2)

CC específico del fabricante, V2 (seguridad 2)

Servicio de transporte CC, V2

.Versión CC, V3 (seguridad 2)

.Restablecer dispositivo localmente CC (seguridad 2)

.Nivel de potencia CC (seguridad 2)

.CC de seguridad

Seguridad 2CC

.CC de supervisión

.Actualización de firmware MD CC, V4 (seguridad 2)

![](<.gitbook/assets/7 (34).png>)

-   _**Grupos de Z-Wave (clase de comando de asociación versión 2)**_

El AQS se puede configurar para enviar informes a dispositivos Z-Wave asociados. Soporta 1 grupo de asociación. Grupo 1 para “LifeLine”: (nodo máximo: 5)

Sensor Multinivel (COMANDO_CAMBIAR_MULTINIVEL, CONMUTADOR_MULTI NIVEL_INFORME)

Restablecimiento del dispositivo localmente

(DOMINIO_CLASE_DISPOSITIVO_REINICIAR_LOCALMENTE, DISPOSITIVO_REINICIAR_EN LA ZONA_NOTIFICACIÓN)

**Sensor multinivel:**A medida que los niveles de CO2 detectados cambian; El AQS transmitirá el comando multinivel del sensor.

**Restablecimiento de fábrica:**Cuando el AQS se haya restablecido al estado predeterminado de fábrica, enviará el reinicio del dispositivo localmente a todos los nodos del Grupo 1.

![](<.gitbook/assets/8 (37).png>)

-   _**Formato de datos de clase de comando**_
    -   Informe de CO2:\[DOMINIO_CLASE_SENSOR_MULTI NIVEL]\[SENSOR_MULTI NIVEL_INFORME]
        -   Si se transmite la señal de CO2 11 02 06 99, 0699 puede verse como 0x0699 en número hexadecimal. Puede convertir hexadecimal a decimal para comprobar el valor de CO2.

0699=0x0699=1689ppm

2
