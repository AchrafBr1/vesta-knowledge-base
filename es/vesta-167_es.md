# VESTA 167

**Control de obturador (SCM-5ZW)**

**Introducción**

SCM-5ZW es un control de obturador Z-Wave. El usuario puede controlar el SCM a través de la red Z-Wave a distancia o manualmente vinculando un interruptor al SCM.

Sube, baja o se detiene de forma automática o remota a mitad de camino, el SCM-5ZW está directamente conectado y controla tratamientos de ventanas motorizados, cortinas y persianas interiores y exteriores, pantallas de proyección y puertas de garaje o puertas de entrada de su hogar.

El control del obturador solo es compatible con el panel de control/puerta de enlace Z-Wave. Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. Al aprovechar la red de malla Z-Wave, los comandos se pueden enrutar a su destino a través de productos Z-Wave intermediarios que “escuchan”.

![](<.gitbook/assets/0 (60).jpeg>)

**Identificación de piezas**

1.  **Indicador LED**
    -   Encendido: el LED parpadea dos veces.
    -   Aprendizaje exitoso: el LED parpadea 3 veces.
    -   Restablecimiento de fábrica: el LED parpadea dos veces.
2.  **Botón de función**
    -   Presione el botón de función y el control del obturador enviará un informe multinivel.
    -   Presione el botón de función 3 veces en 1,5 segundos para incluir o excluir el control del obturador en/de la red Z-Wave.
    -   Mantenga presionado el botón Función durante 10 segundos para restablecer.
3.  **Cable de conexión de entrada de alimentación N (Conductor Neutro) (Azul)**
4.  **Cable de conexión de entrada de alimentación L (conductor activo) (marrón)**
5.  **Cable de conexión del interruptor local S2 (dirección descendente) (naranja)**

Si el SCM está conectado de acuerdo con_**Instalación**_debajo, la persiana se bajará durante 4 minutos después de que se active el interruptor.

Al activar este interruptor cuando la persiana está subiendo, se detendrá la persiana.

**6. Cable de conexión del interruptor local S1 (dirección ascendente) (rojo)**

Si el SCM está conectado de acuerdo con_**Instalación**_debajo, la persiana se subirá durante 4 minutos después de activar el interruptor.

Activar este interruptor cuando la persiana está bajando la detendrá.

**7. Cable de conexión de salida del motor O1 (dirección ascendente) (amarillo)**

Conéctelo al terminal Arriba del motor de la persiana.

**8. Cable de conexión de salida del motor O2 (dirección descendente) (verde)**

Conéctelo al terminal de bajada del motor de la persiana.

**Especificación**

-   Fuente de alimentación: 110 - 230 VCA, 50/60 Hz
-   Corriente de carga admitida: 1/4 HP (caballos de fuerza); 1,8Amperios para motores con factor de potencia compensado (cargas inductivas)
-   Protocolo de comunicación: módulo serie Z-Wave Plus 500

![](<.gitbook/assets/1 (53).jpeg>)

**Precaución**

-   Todos los trabajos en el dispositivo, incluida la instalación y el mantenimiento, deben ser realizados por un electricista calificado y autorizado.
-   Antes de la instalación o cualquier trabajo de mantenimiento, asegúrese de que la fuente de alimentación esté desconectada.
-   No conecte el dispositivo a cargas que excedan la corriente de carga admitida.
-   Conecte el dispositivo únicamente a un motor alimentado por CA.

1

**Características**

-   _**Agregar dispositivo (inclusión)**_

Este producto se puede incluir y operar en cualquier red Z-Wave con otros dispositivos certificados Z-Wave de otros fabricantes y/u otras aplicaciones. Todos los nodos de la red que no funcionan con baterías actuarán como repetidores independientemente del proveedor para aumentar la confiabilidad de la red.

-   -   Conecte la alimentación al control del obturador (consulte las instrucciones del manual).**Instalación**).
    -   Coloque la puerta de enlace Z-wave o el panel de control en**Modo de inclusión**(consulte el manual de la puerta de enlace Z-wave o del panel de control).
    -   En 1,5 segundos, presione el botón de función 3 veces.
    -   Consulte el manual de funcionamiento de la puerta de enlace Z-wave o del panel de control para completar el proceso de adición.
    -   Si el dispositivo ya se ha agregado (incluido) en otro panel de control/puerta de enlace Z-wave, o si el dispositivo no se puede agregar al panel de control/puerta de enlace Z-wave actual, intente eliminarlo primero (consulte_**Quitar dispositivo**_).
-   _**Eliminación del dispositivo (exclusión)**_

El dispositivo debe eliminarse de la red Z-wave existente antes de agregarlo a otra.

**Modo de exclusión**

-   Coloque la puerta de enlace Z-wave o el panel de control en**Modo de exclusión**(consulte el manual de la puerta de enlace Z-wave o del panel de control).
-   En 1,5 segundos, presione el botón de función 3 veces y el dispositivo se eliminará de la red Z-wave.

**Restablecimiento de fábrica**

_(Utilice el restablecimiento de fábrica únicamente cuando falte el panel de control/puerta de enlace de la red o no esté operativo)._

El restablecimiento de fábrica del dispositivo lo restaurará a la configuración predeterminada de fábrica (es decir, no estará incluido en ninguna red Z-wave).

-   -   Mantenga presionado el botón de función del dispositivo durante 10 segundos para restablecer los valores de fábrica.
-   _**Prueba de rango**_

Para probar si el dispositivo puede comunicarse con la puerta de enlace Z-wave o el panel de control:

-   Coloque la puerta de enlace/panel en modo de prueba de alcance (Prueba de caminata).
-   Presione el botón de función en el dispositivo.
-   La puerta de enlace/panel debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual de operación de la puerta de enlace/panel).

**Instalación**

-   _**Cableado con conector de empalme**_
    -   SCM-5 viene con abrazaderas y cables terminales integrados (conectores de empalme Wago 221).
    -   Los conectores de 2 cables admiten cables sólidos y trenzados de 0,2 a 4 mm² (24–12 AWG).
    -   Conecte el SCM-5 a la alimentación de CA, a los interruptores locales y al motor de la persiana con los conectores.
    -   Antes de realizar el cableado, asegúrese de que la alimentación esté apagada. Para conectar los cables:
        1.  Levante la palanca e inserte el cable.**(Imagen 1, 2)**

**Foto 1****Imagen 2**

![](<.gitbook/assets/2 (57).png>)

1.  Empuje la palanca hacia abajo. La carcasa transparente le permite comprobar si el cable está conectado correctamente. Asegúrese de que el cable esté sujeto firmemente en su lugar y no se salga.**(Imagen 3, 4)**

2

**Imagen 3****Imagen 4**

![](<.gitbook/assets/3 (57).png>)

-   1.  De la misma manera que en los pasos 1 y 2, conecte los otros cables con conectores.
-   SCM-5 debe conectarse de acuerdo con el siguiente diagrama:

![](<.gitbook/assets/4 (43).jpeg>)

-   Conecte el terminal N del SCM al terminal N de la fuente de alimentación.
-   Conecte el terminal L del SCM al terminal L de la fuente de alimentación.
-   Conecte el terminal O1 del SCM al terminal abierto del motor de la persiana.
-   Conecte el terminal O2 del SCM al terminal de cierre del motor de la persiana.
-   **(Conmutador local opcional)**Conecte los terminales S2 y S1 del SCM al terminal L de la fuente de alimentación.

**Operación**

-   _**Control de obturador**_
    -   **Control manual**

Si se conecta un interruptor local opcional, el usuario puede presionar y mantener presionado el botón del interruptor local arriba/abajo (S1 arriba; S2 abajo) durante 1 segundo para controlar el obturador. Cuando se activa, la persiana se subirá/bajará. Cuando la persiana está rodando, el usuario puede detenerla presionando el botón de dirección opuesta.

-   -   **Red Z-Wave**

Después de que el control de obturador se haya incluido exitosamente en una red Z-Wave, el controlador Z-Wave puede controlar el obturador con el comando Z-wave Switch Binary Set o Switch Multilevel Set, usando los siguientes parámetros:

-   -   -   Valor: 0x00~0% (0%)~99%, 0% = cierre total, 99% = apertura total)
        -   Duración de la atenuación: 0x00
    -   A medida que comienza cada movimiento hacia arriba/abajo, se envía el comando de cambio de nivel inicial del interruptor multinivel para iniciar la transición al nuevo nivel. Mientras el SCM está en movimiento, puede enviar el comando de cambio de nivel de parada del interruptor multinivel para detener el SCM.

3

-   _**Calibración**_
    -   El tiempo de activación predeterminado del control de persianas es**4**minutos.

Cuando se presiona el botón Arriba/Abajo, se activará el motor de la persiana durante 4 minutos.

Cuando se recibe un comando Z-Wave del controlador Z-Wave, determinará el porcentaje de recorrido del obturador utilizando 4 minutos como base para el cálculo.

-   -   Para que el control del obturador funcione correctamente, su tiempo de activación debe calibrarse de acuerdo con la distancia real de recorrido del obturador. Hay dos formas de ajustar el tiempo de activación:
        -   **Calibración manual:**Calibre la activación según el procedimiento siguiente:
            1.  Antes de la calibración, los interruptores locales externos deben estar conectados al control de persianas.
            2.  Mantenga presionado el botón Función durante 3 segundos y suéltelo para ingresar al modo de Calibración. El motor del obturador se activará durante 4 minutos cuando el control del obturador entre en modo de calibración.
            3.  Espere 4 minutos hasta que el motor de la persiana deje de girar y luego presione el botón "Abajo" para bajar la persiana. (Si la persiana alcanzó la posición abierta en menos de 4 minutos, puede presionar el botón "Abajo" para detener el motor de la persiana. Luego presione el botón "Abajo" nuevamente para bajar la persiana).
            4.  Tan pronto como la persiana esté completamente cerrada, presione el botón "Arriba". El control del obturador registrará el tiempo que tardó el obturador en abrirse y cerrarse como el nuevo "**hora de cierre**”.
            5.  Después de presionar el botón "Arriba" en el momento en que la persiana esté completamente cerrada, la persiana se enrollará hacia la dirección de apertura.
            6.  Presione el botón "Abajo" en el momento en que el obturador esté completamente abierto. El control del obturador registrará el tiempo que tardó el obturador en pasar de cerrado a abierto como el nuevo "**tiempo abierto**”.
            7.  El control de obturador enviará un informe multinivel (0x63), con su valor actual, valor objetivo y/o duración, al controlador cada vez que cambie su nivel.
        -   Por ejemplo, si el obturador tarda 30 segundos en moverse de la posición "Arriba" a "Abajo", su nuevo tiempo de cierre será de 30 segundos. Después de la calibración, siempre que se presione el botón "Abajo", el obturador bajará durante 30 segundos.
        -   Si la persiana tarda 40 segundos en pasar de la posición “Abajo” a “Arriba”, su nuevo tiempo de apertura será de 40 segundos. Después de la calibración, siempre que se presione el botón "Arriba", el obturador se subirá durante 40 segundos.
        -   **Comando Z-Wave:**Además de la calibración manual, los usuarios también pueden ajustar el tiempo de activación enviando un comando desde el controlador Z-Wave con el comando Configuración CC, utilizando los siguientes parámetros:

| **Configuración**               | **Número de parámetro** | **Tamaño** | **Valor**     | **Por defecto**       |
| ------------------------------- | ----------------------- | ---------- | ------------- | --------------------- |
| Configuración de tiempo abierto | 0x01                    | 0x02       | 0x0000~0x00F0 | 0x00F0 (240 seg)      |
|                                 |                         |            | (segundo)     |                       |
|                                 |                         |            |               |                       |
| Configuración de hora de cierre | 0x02                    | 0x02       | 0x0000~0x00F0 | 0x00F0 (240 seg)      |
|                                 |                         |            | (segundo)     |                       |
|                                 |                         |            |               |                       |
| Posición actual                 | 0x03                    | 0x02       | 0x0000~0x0063 | 0x0063 (99%)          |
|                                 |                         |            | (%)           | Completamente abierto |
|                                 |                         |            |               |                       |

-   Número de parámetro: 0x01~0x03
    -   Para el parámetro 1, los usuarios pueden configurar el tiempo de apertura (de abajo a arriba) en un valor que oscila entre 0 y 255 segundos.
    -   Para el parámetro 2, los usuarios pueden configurar el tiempo de cierre (de arriba a abajo) en un valor que oscila entre 0 y 255 segundos.
    -   Para el parámetro 3, los usuarios pueden establecer la posición actual en un valor que oscila entre %0 y %99.
-   Tamaño: 0x02. Este campo se utiliza para especificar el tamaño del valor real.
-   Valor de configuración: 0x0000~0x00F0 (segundos)
-   El control de la persiana comenzará a moverse al recibir el comando de onda Z Cambiar conjunto binario o Cambiar conjunto multinivel, y el movimiento se ejecutará según la configuración de posición actual.

Ejemplo de configuración:

| Número de parámetro | Tamaño | Valor |                |
| ------------------- | ------ | ----- | -------------- |
|                     |        |       |                |
| 01                  | 02     | 0064  | (100 segundos) |
|                     |        |       |                |
| 02                  | 02     | 0064  | (100 segundos) |
|                     |        |       |                |
| 03                  | 02     | 0032  | (50%)          |
|                     |        |       |                |

CAMBIAR_MULTI NIVEL_CONFIGURAR: 0x00 (0%)

SCM bajará (de arriba a abajo) durante 50 segundos: (100/100)\*(100-50)

-   El tiempo de activación se restablecerá a**4**minutos cada vez que el control de obturador se incluye en la red Z-Wave o cuando se restablece de fábrica.

_**\\<NOTE>:**_La posición actual predeterminada del control del obturador está configurada en 99% (completamente abierto). Se recomienda abrir completamente el obturador antes de calibrar con el comando Z-Wave; de ​​lo contrario, también vuelva a ajustar la configuración de Posición actual con el comando.

4

-   _**Información de onda Z**_

**Clase de dispositivo genérico:**CAMBIAR_MULTI NIVEL

**Clase de dispositivo específica:**CLASE_C_MOTOR_CONTROL

**Tipo de rol:**ESCLAVO_SIEMPRE_EN

**Soporte/Control de Clase de Comando**

**Soporte CC obligatorio:**

Z-Wave Plus Información CC

Servicio de Transporte CC

Seguridad_2CC

CC de supervisión

Cambiar binario (S2)

Cambiar CC multinivel (S2)

Información del grupo de asociación CC (S2)

Restablecimiento del dispositivo localmente CC (S2)

Configuración CC (S2)

CC específico del fabricante, V2 (S2)

Nivel de potencia CC (S2)

Actualización de firmware Md CC, V4 (S2)

Asociación CC, V2 (S2)

Versión CC, V2 (S2)

Asociación multicanal CC, V3 (S2)

-   _**Grupos de Z-Wave (clase de comando de asociación versión 2)**_

_**Grupo 1 para “LifeLine”: (nodo máximo x 1)**_

Cambiar CC multinivel, (COMANDO_CLASE_CAMBIAR_MULTI NIVEL)

\#.CAMBIAR_MULTI NIVEL_INFORME

\#.CAMBIAR_MULTI NIVEL_COMENZAR_NIVEL_CAMBIAR

\#.CAMBIAR_MULTI NIVEL_DETENER_NIVEL_CAMBIAR

Restablecimiento del dispositivo localmente CC, (COMANDO_CLASE_DISPOSITIVO_REINICIAR_EN LA ZONA)

-   Cuando SCM comience a moverse, enviará\[CAMBIAR_MULTI NIVEL_COMENZAR_NIVEL_CAMBIAR]
-   Cuando SCM deje de moverse, enviará\[CAMBIAR_MULTI NIVEL_DETENER_NIVEL_CAMBIAR]
-   Siempre que SCM cambie su posición, enviará\[CAMBIAR_MULTI NIVEL_INFORME]

5
