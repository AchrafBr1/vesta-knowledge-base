# VESTA 170

**PRLM-CH3-AC-ZW Interruptor de relé Z-Wave**

**Introducción**

**PRLM-CH3-AC-ZW es un interruptor de relé Z-Wave de 3 canales que se puede conectar a dispositivos cableados y configurar en estado de apertura normal (N.O.). Después de unirse a la red Z-Wave, el interruptor de relé se puede controlar a través de la red Z-Wave para activar los dispositivos conectados.**

**Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. Al aprovechar la red de malla Z-Wave, los comandos se pueden enrutar a su destino a través de productos Z-Wave intermediarios que “escuchan”.**

**El relé puede controlar los nodos Z-Wave simplemente presionando el botón de función y también puede alertarlo sobre problemas de comunicación de señales.**

**Identificación de piezas**

**La cubierta superior****Base**

![](<.gitbook/assets/0 (48).png>)

1.  **Botón de interruptor 1/Botón de función**
    -   **Presione el botón 3 veces en 1 segundo para enviar un código de aprendizaje.**
    -   **Mantenga presionado el botón durante 10 segundos para restablecer los valores de fábrica.**
    -   **Presione el botón para encender/apagar el canal de relé 1.**
2.  **Botón de cambio 2**
    -   **Presione el botón para encender/apagar el canal de relé 2.**
3.  **Botón de cambio 3**
    -   **Presione el botón para encender/apagar el canal de relé 3.**

![](<.gitbook/assets/1 (53).png>)

-   **NOTA>**

**Cuando se presiona el botón de interruptor 2/3, el canal de relé 2/3 cambiará instantáneamente a ON/OFF. Cuando se presiona el botón de interruptor 1, el canal de relé 1 cambiará a ON/OFF después de un segundo, porque el dispositivo necesita identificar si presionar el botón es para encender/apagar.**

**o para enviar un código de aprendizaje.**

1.  **Indicador LED 1**
2.  **Indicador LED 2**
3.  **Indicador LED 3**

**El indicador LED 1/2/3 se utiliza para indicar el estado del canal de relé 1/2/3:**

-   **LED 1 encendido/apagado: Canal de relé 1 encendido/apagado**
-   **LED 2 encendido/apagado: Canal de relé 2 encendido/apagado**
-   **LED 3 encendido/apagado: Canal de relé 3 encendido/apagado**

**Cuando se enciende, todos los LED parpadearán secuencialmente durante 1 ciclo.**

**Cuando esté en modo de aprendizaje, todos los LED parpadearán una vez por segundo.**

**Cuando el aprendizaje sea exitoso, todos los LED parpadearán rápidamente 3 veces.**

**7. Orificios de montaje**

**1**

**Terminales de conexión**

**Conecte el cable al terminal, apriete el tornillo para cerrar la cortadora y mantenga el cable en su lugar. Desatornille para abrir el cortapelos y quitar el cable conectado al terminal.**

1.  **Línea (entrada de CA)**
2.  **Neutral**
3.  **NO (Channel 1)**

**Para conexión normal abierta con el dispositivo**

1.  **Común (Canal 1)**
2.  **NO (Channel 2)**

**Para conexión normal abierta con el dispositivo**

1.  **Común (Canal 2)**
2.  **NO (Channel 3)**

**Para conexión normal abierta con el dispositivo**

1.  **Común (Canal 3)**
2.  **Abrazadera de alivio de tensión**

**Las abrazaderas se utilizan para asegurar los cables y proporcionar alivio de tensión para proteger los cables del recorte de metal.**

**17. Orificios para cableado**

**Especificación**

**Fuente de alimentación: 100 - 240 V CA**

**Corriente de carga admitida (para cada canal de relé): 5 A, 250 V CA o 5 A, 30 V CC**

**Cable trenzado: 14–22 AWG**

**Precaución**

**Todos los trabajos en el dispositivo, incluida la instalación y el mantenimiento, deben ser realizados por un electricista calificado y autorizado.**

**Antes de la instalación o cualquier trabajo de mantenimiento, asegúrese de que la fuente de alimentación esté desconectada. No conecte el dispositivo a cargas que excedan la corriente de carga admitida.**

**Instalación**

**Conecte el relé de acuerdo con las instrucciones a continuación.**

![](<.gitbook/assets/2 (50).jpeg>)

1.  **Apague la fuente de alimentación antes de realizar la conexión.**
2.  **Retire la cubierta superior y retire las abrazaderas de alivio de tensión.**
3.  **Conecte los terminales L y N de la fuente de alimentación a los terminales de Línea y Neutro del PRLM respectivamente a través del orificio de cableado.**
4.  **Dependiendo del dispositivo que desee controlar a través del canal de relé 1, seleccione el terminal NO y conecte el canal de relé 1 con el dispositivo a través del orificio de cableado para establecer una conexión abierta normal con el dispositivo.**
5.  **De la misma manera que en el paso 4, conecte el canal de retransmisión 2/3 a otros dispositivos cableados.**
6.  **Después de completar el cableado, reemplace las abrazaderas de alivio de tensión y la cubierta superior. Encienda la fuente de alimentación para encender el interruptor de relé.**

**Características**

![](<.gitbook/assets/3 (59).png>)

**Agregar dispositivo (inclusión)**

**Conecte la entrada de alimentación al interruptor de relé de acuerdo con las instrucciones de instalación anteriores y encienda el interruptor de relé.**

**Coloque la puerta de enlace Z-Wave o el panel de control en modo de inclusión (consulte el manual de la puerta de enlace o panel de control Z-Wave).**

**En 1 segundo, presione el botón de función 3 veces.**

**2**

**Consulte el manual de funcionamiento de la puerta de enlace Z-Wave o del panel de control para completar el proceso de adición.**

**Si el dispositivo ya se ha agregado (incluido) en otra puerta de enlace/panel de control Z-Wave, o si el dispositivo no se puede agregar a la puerta de enlace/panel de control Z-Wave actual, intente eliminarlo primero (consulte Extracción del dispositivo).**

**Eliminación del dispositivo (exclusión)**

![](<.gitbook/assets/4 (58).png>)

**El dispositivo debe eliminarse de la red Z-Wave existente antes de agregarlo a otra. Modo de exclusión**

**Coloque la puerta de enlace Z-Wave o el panel de control en modo de exclusión (consulte el manual de la puerta de enlace o panel de control Z-Wave).**

**En 1 segundo, presione el botón de función 3 veces y el dispositivo se eliminará de la red Z-Wave.**

**El restablecimiento de fábrica del dispositivo lo restaurará a la configuración predeterminada de fábrica (es decir, no estará incluido en ninguna red Z-Wave). Utilice este procedimiento únicamente si la puerta de enlace Z-Wave o el panel de control se pierden o no funcionan.**

**Mantenga presionado el botón de función del dispositivo durante 10 segundos para restablecer los valores de fábrica.**

**Prueba de rango**

![](<.gitbook/assets/5 (58).png>)

**Para probar si el dispositivo puede comunicarse con la puerta de enlace Z-Wave o el panel de control:**

**Coloque la puerta de enlace/panel en modo de prueba de alcance (Prueba de caminata). Presione el botón de función en el dispositivo**

**La puerta de enlace/panel debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual de operación de la puerta de enlace/panel).**

**Montaje**

**Una vez que haya finalizado la prueba de alcance y esté satisfecho de que el dispositivo puede comunicarse con la puerta de enlace Z-Wave en la ubicación elegida, continúe con el montaje.**

**Desconecte la fuente de alimentación principal.**

**Afloje el tornillo de fijación inferior y retire la cubierta superior del interruptor de relé. Utilice los orificios de la base para marcar la ubicación de montaje en la pared.**

**Taladre agujeros en el lugar marcado e inserte tacos de pared si es necesario, atornille la base en el lugar de montaje.**

**Vuelva a colocar la cubierta superior y apriete el tornillo de fijación inferior.**

![](<.gitbook/assets/6 (37).jpeg>)

**Operación**

![](<.gitbook/assets/7 (35).jpeg>)

**Control de relé**

**Después de que el interruptor de retransmisión se haya unido con éxito a una red Z-Wave, la puerta de enlace/panel de control puede controlar de forma remota el canal de retransmisión 1/2/3 para encenderlo o apagarlo. Consulte su puerta de enlace/panel de control Z-Wave para obtener más detalles.**

**El usuario también puede presionar manualmente el botón de interruptor 1/2/3 para encender/apagar el canal de relé 1/2/3.**

**3**

**Información de onda Z**

**Clase de dispositivo genérico: GENÉRICO_TIPO_CAMBIAR_BINARIO**

**Clase de dispositivo específica: ESPECÍFICO_TIPO_FUERZA_CAMBIAR_BINARIO**

**Tipo de rol: Siempre en esclavo (AOS)**

**Claves de seguridad compatibles: S2_NO AUTENTICADO**

**Biblioteca: esclavo 232 mejorado**

**Tipo de dispositivo del terminal 1: interruptor de tipo genérico binario y tipo específico interruptor de encendido/apagado**

**Tipo de dispositivo del terminal 1: interruptor de tipo genérico binario y tipo específico interruptor de encendido/apagado**

**Tipo de dispositivo del terminal 1: interruptor de tipo genérico binario y tipo específico interruptor de encendido/apagado**

**Soporte/Control de Clase de Comando**

**Clases de comando anunciadas en NIF**

**ZWave Plus Información CC**

**Servicio de Transporte CC**

**CC específico del fabricante, V2 (S2)**

**Restablecimiento del dispositivo localmente CC (S2)**

**Seguridad_2CC**

**Nivel de potencia CC (S2)**

**Versión CC, V2 (S2)**

**Asociación CC, V2 (S2)**

**Asociación multicanal CC, V3 (S2)**

**Información del grupo de asociación CC (S2)**

**CC multicanal (S2)**

**CC de supervisión**

**Actualización de firmware Md CC, V4 (S2)**

**Cambiar binario (S2)**

**Endpoints 123 implementa las siguientes clases de comando**

**ZWave Plus Información CC**

**Seguridad_2CC**

**Asociación CC, V2 (S2)**

**Asociación multicanal CC, V3 (S2)**

**Información del grupo de asociación CC (S2)**

**CC de supervisión**

**Cambiar binario (S2)**

**Mapeo de clase de comando básico: Binary Switch CC para los puntos finales 1, 2 y 3.**

![](<.gitbook/assets/8 (35).png>)

**Grupos de Z-Wave (clase de comando de asociación versión 2)**

| **Dispositivo raíz :** |                   |                       |                                                                              |
| ---------------------- | ----------------- | --------------------- | ---------------------------------------------------------------------------- |
| **IDENTIFICACIÓN**     | **Nombre**        | **Recuento de nodos** | **Descripción**                                                              |
| **1**                  | **Línea de vida** | **5**                 | **Admite las siguientes clases de comando:**                                 |
|                        |                   |                       | **Restablecimiento del dispositivo localmente: se activa al restablecerse.** |
|                        |                   |                       | **Switch Binary: activado por los puntos finales**                           |
| **2**                  | **Relé EP 1**     | **5**                 | **Espejo del punto final 1, grupo 2**                                        |

![](<.gitbook/assets/9 (35).png>)

**4**

![](<.gitbook/assets/10 (36).png>)

| **3**              | **Relevo EP 2**   | **5**                 | **Espejo del punto final 2, grupo 2**                        |
| ------------------ | ----------------- | --------------------- | ------------------------------------------------------------ |
| **4**              | **Relevo EP 3**   | **5**                 | **Espejo del punto final 3, grupo 2**                        |
| **Punto final 1:** |                   |                       |                                                              |
| **IDENTIFICACIÓN** | **Nombre**        | **Recuento de nodos** | **Descripción**                                              |
| **1**              | **Línea de vida** | **0**                 | **Espejo del dispositivo raíz, pero sin recuento de nodos.** |
| **2**              | **Relé EP 1**     | **5**                 | **Cambiar informe binario en caso de sobrecarga.**           |
| **Punto final 2:** |                   |                       |                                                              |
| **IDENTIFICACIÓN** | **Nombre**        | **Recuento de nodos** | **Descripción**                                              |
| **1**              | **Línea de vida** | **0**                 | **Espejo del dispositivo raíz, pero sin recuento de nodos.** |
| **2**              | **Relevo EP 2**   | **5**                 | **Cambiar informe binario en caso de sobrecarga.**           |
| **Punto final 3:** |                   |                       |                                                              |
| **IDENTIFICACIÓN** | **Nombre**        | **Recuento de nodos** | **Descripción**                                              |
| **1**              | **Línea de vida** | **0**                 | **Espejo del dispositivo raíz, pero sin recuento de nodos.** |
| **2**              | **Relevo EP 3**   | **5**                 | **Cambiar informe binario en caso de sobrecarga.**           |

![](<.gitbook/assets/11 (27).png>)![](<.gitbook/assets/12 (30).png>)![](<.gitbook/assets/13 (24).png>)![](<.gitbook/assets/14 (18).png>)

**5**
