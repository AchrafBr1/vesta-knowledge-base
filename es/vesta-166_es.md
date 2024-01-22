# VESTA 166

**Control de obturador (SCM-8ZW)**

**Introducción**

SCM-8ZW es un control de obturador Z-Wave. El usuario puede controlar el SCM a través de la red Z-Wave a distancia o manualmente vinculando un interruptor al SCM.

Sube, baja o se detiene de forma automática o remota a mitad de camino, el SCM-8 está directamente conectado y controla tratamientos de ventanas motorizados, cortinas y persianas interiores y exteriores, pantallas de proyección y puertas de garaje o puertas de entrada de su hogar.

El control del obturador solo es compatible con el panel de control/puerta de enlace Z-Wave. Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. Al aprovechar la red de malla Z-Wave, los comandos se pueden enrutar a su destino a través de productos Z-Wave intermediarios que “escuchan”.

**Identificación de piezas**

1.  **Botón de función**
    -   Presione el botón 3 veces en 1,5 segundos para incluir o excluir el dispositivo de la red Z-Wave.
    -   Mantenga presionado el botón durante 10 segundos para restablecer los valores de fábrica.
    -   Presione el botón y el control del obturador enviará un informe multinivel.
2.  **Indicador LED (rojo)**
    -   Encendido: el LED parpadea dos veces.
    -   Aprendizaje exitoso: el LED parpadea 3 veces.
    -   Restablecimiento de fábrica: el LED parpadea dos veces.
3.  **Orificios de montaje**
4.  **Interruptor local S1 (dirección abierta)**
    -   Si el SCM está conectado de acuerdo con la sección Instalación, la persiana se subirá durante 4 minutos después de que se active el interruptor.
    -   Activar este interruptor cuando la persiana está bajando la detendrá.
5.  **Interruptor local S2 (dirección de cierre)**
    -   Si el SCM está conectado de acuerdo con la sección Instalación, la persiana se bajará durante 4 minutos después de que se active el interruptor.
    -   Al activar este interruptor cuando la persiana está subiendo, se detendrá la persiana.
6.  **Salida del motor O1 (dirección abierta)**
    -   Conéctelo al terminal Arriba del motor de la persiana.
7.  **Salida del motor O2 (dirección de cierre)**
    -   Conéctelo al terminal de bajada del motor de la persiana.
8.  **Terminal de entrada de alimentación L (conductor activo)**
9.  **Terminal de entrada de alimentación N (conductor neutro)**
10. **Abrazadera de alivio de tensión**
    -   La abrazadera se utiliza para asegurar los cables y proporcionar alivio de tensión para proteger los cables del recorte de metal.
11. **Hebilla de cableado**
    -   La hebilla de cableado se utiliza para gestionar los cables.

![](<.gitbook/assets/0 (59).jpeg>)

**Especificación**

-   Fuente de alimentación: 100 - 240 VCA, 50/60 Hz
-   Corriente de carga admitida: 1/2 HP (caballos de fuerza); 3,6Amperios para motores con factor de potencia compensado (cargas inductivas)

1

-   _**Precaución**_![](<.gitbook/assets/1 (52).jpeg>)
    -   Todos los trabajos en el dispositivo, incluida la instalación y el mantenimiento, deben ser realizados por un electricista calificado y autorizado.
    -   Antes de la instalación o cualquier trabajo de mantenimiento, asegúrese de desconectar la fuente de alimentación.
    -   No conecte el dispositivo a cargas que excedan la corriente de carga admitida.
    -   Conecte el dispositivo únicamente a un motor alimentado por CA.
-   _**Agregar dispositivo (inclusión)**_

Este producto se puede incluir y operar en cualquier red Z-Wave con otros dispositivos certificados Z-Wave de otros fabricantes y/u otras aplicaciones. Todos los nodos de la red que no funcionan con baterías actuarán como repetidores independientemente del proveedor para aumentar la confiabilidad de la red.

-   -   Conecte la alimentación al control del obturador (consulte las instrucciones del manual).**Instalación**).
    -   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de inclusión**(consulte el manual de la puerta de enlace Z-Wave o del panel de control).
    -   En 1,5 segundos, presione el botón de función 3 veces.
    -   Consulte el manual de funcionamiento de la puerta de enlace Z-Wave o del panel de control para completar el proceso de adición.
    -   Si el dispositivo ya se ha agregado (incluido) en otra puerta de enlace/panel de control Z-Wave, o si el dispositivo no se puede agregar a la puerta de enlace/panel de control Z-Wave actual, intente eliminarlo primero (consulte_**Quitar dispositivo**_).
-   _**Eliminación del dispositivo (exclusión)**_

El dispositivo debe eliminarse de la red Z-Wave existente antes de agregarlo a otra.**Modo de exclusión**

-   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de exclusión**(consulte el manual de la puerta de enlace Z-Wave o del panel de control).
-   En 1,5 segundos, presione el botón de función 3 veces y el dispositivo se eliminará de la red Z-Wave.

**Restablecimiento de fábrica**

_(Utilice el restablecimiento de fábrica únicamente cuando falte el panel de control/puerta de enlace de la red o no esté operativo)._

-   -   El restablecimiento de fábrica del dispositivo lo restaurará a la configuración predeterminada de fábrica (es decir, excluido de la red Z-Wave).
    -   Mantenga presionado el botón de función del dispositivo durante 10 segundos para restablecer los valores de fábrica.
-   _**Prueba de rango**_

Para probar si el dispositivo puede comunicarse con la puerta de enlace Z-Wave o el panel de control:

-   Coloque la puerta de enlace/panel en modo de prueba de alcance (Walk Test).
-   Presione el botón de función en el dispositivo
-   La puerta de enlace/panel debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual de operación de la puerta de enlace/panel).

**Instalación**

-   Utilice el tamaño de cable recomendado de AWG 14-22 o Ø 2,08-0,326 (mm²). Conecte el SCM según el siguiente diagrama:

![](<.gitbook/assets/2 (48).jpeg>)

-   Conecte el terminal L del SCM al terminal L de la fuente de alimentación.
-   Conecte el terminal N del SCM al terminal N de la fuente de alimentación.
-   Conecte el terminal O1 del SCM al terminal arriba del motor de la persiana.

2

-   Conecte el terminal O2 del SCM al terminal inferior del motor de la persiana.
-   _**(Conmutador local opcional)**_Conecte los terminales S1 y S2 del SCM al terminal L de la fuente de alimentación.
-   Inserte cada cable en el terminal al que debe conectarse, apriete cada tornillo para cerrar las cortadoras y mantener los cables en su lugar.
-   Después de conectar los cables, utilice la hebilla de cableado para gestionar los cables y coloque la hebilla de cableado en la base con su espacio (abertura) colocado a la izquierda.

![](<.gitbook/assets/3 (44).jpeg>)

**Operación**

-   _**Control de obturador**_
    -   **Control manual**

Si se conecta un interruptor local opcional, el usuario puede presionar y mantener presionado el botón del interruptor local arriba/abajo (S1 arriba; S2 abajo) durante 1 segundo para controlar el obturador. Cuando se activa, la persiana se subirá/bajará.

Cuando la persiana está rodando, el usuario puede detenerla presionando el botón de dirección opuesta.

-   -   **Red Z-Wave**

Después de que el control de obturador se haya incluido exitosamente en una red Z-Wave, el controlador Z-Wave puede controlar el obturador con el comando Z-Wave Switch Binary Set o Switch Multilevel Set, usando los siguientes parámetros:

-   -   -   Valor: 0x00~0% (0%)~99%, 0% = cierre total, 99% = apertura total)
        -   Duración de la atenuación: 0x00
    -   A medida que comienza cada movimiento hacia arriba/abajo, se envía el comando de cambio de nivel inicial del interruptor multinivel para iniciar la transición al nuevo nivel. Mientras el SCM está en movimiento, puede enviar el comando de cambio de nivel de parada del interruptor multinivel para detener el SCM.
-   _**Calibración**_
    -   El tiempo de activación predeterminado del control de persianas es**4**minutos.

Cuando se presiona el botón Arriba/Abajo, se activará el motor de la persiana durante 4 minutos.

Cuando se recibe un comando Z-Wave del controlador Z-Wave, determinará el porcentaje de recorrido del obturador utilizando 4 minutos como base para el cálculo.

-   -   Para que el control del obturador funcione correctamente, su tiempo de activación debe calibrarse de acuerdo con la distancia real de recorrido del obturador. Hay dos formas de ajustar el tiempo de activación:
        -   **Calibración manual:**Calibre la activación según el procedimiento siguiente:
            1.  Antes de la calibración, los interruptores locales externos deben estar conectados al control de persianas.
            2.  Mantenga presionado el botón Función durante 3 segundos y suéltelo para ingresar al modo de Calibración. El motor del obturador se activará durante 4 minutos cuando el control del obturador entre en modo de calibración.
            3.  Espere 4 minutos hasta que el motor de la persiana deje de girar, luego presione el botón "Abajo" para bajar la persiana. (Si en menos de 4 minutos la persiana ya ha alcanzado la posición abierta, puede presionar el botón "Abajo" para detener el motor de la persiana. Luego presione el botón "Abajo" nuevamente para bajar la persiana).
            4.  Tan pronto como la persiana esté completamente cerrada, presione el botón "Arriba". El control del obturador registrará el tiempo que tardó el obturador en abrirse y cerrarse como el nuevo "**hora de cierre**”.
            5.  Después de presionar el botón "Arriba" en el momento en que la persiana esté completamente cerrada, la persiana se enrollará hacia la dirección de apertura.
            6.  Presione el botón "Abajo" en el momento en que el obturador esté completamente abierto. El control del obturador registrará el tiempo que tardó el obturador en pasar de cerrado a abierto como el nuevo "**tiempo abierto**”.
            7.  El control de persianas enviará un informe multinivel, con su valor actual, valor objetivo y/o duración, al controlador cada vez que cambie su nivel.
        -   Por ejemplo, si el obturador tarda 30 segundos en moverse de la posición "Arriba" a "Abajo", su nuevo tiempo de cierre será de 30 segundos. Después de la calibración, siempre que se presione el botón "Abajo", el obturador bajará durante 30 segundos.
        -   Si la persiana tarda 40 segundos en pasar de la posición “Abajo” a “Arriba”, su nuevo tiempo de apertura será de 40 segundos. Después de la calibración, siempre que se presione el botón "Arriba", el obturador se subirá durante 40 segundos.

3

-   **Comando Z-Wave:**Además de la calibración manual, los usuarios también pueden ajustar el tiempo de activación enviando un comando desde el controlador Z-Wave con el comando Configuración CC, utilizando los siguientes parámetros:

| **Configuración**               | **Número de parámetro** | **Tamaño** | **Valor**     | **Por defecto**       |
| ------------------------------- | ----------------------- | ---------- | ------------- | --------------------- |
| Configuración de tiempo abierto | 0x01                    | 0x02       | 0x0000~0x00FF | 0x00F0 (240 seg)      |
|                                 |                         |            | (segundo)     |                       |
|                                 |                         |            |               |                       |
| Configuración de hora de cierre | 0x02                    | 0x02       | 0x0000~0x00FF | 0x00F0 (240 seg)      |
|                                 |                         |            | (segundo)     |                       |
|                                 |                         |            |               |                       |
| Posición actual                 | 0x03                    | 0x02       | 0x0000~0x0063 | 0x0063 (99%)          |
|                                 |                         |            | (%)           | Completamente abierto |
|                                 |                         |            |               |                       |

 Número de parámetro: 0x01~0x03

 Para el parámetro 1, los usuarios pueden configurar el tiempo de apertura (de abajo a arriba) en un valor que oscila entre 0 y 255 segundos.

 Para el parámetro 2, los usuarios pueden configurar el tiempo de cierre (de arriba a abajo) en un valor que oscila entre 0 y 255 segundos.

 Para el parámetro 3, los usuarios pueden establecer la posición actual en un valor que oscila entre %0 y %99.

 Tamaño: 0x02. Este campo se utiliza para especificar el tamaño del valor real.

 Valor de configuración: 0x0000~0x00FF (segundos)

 El control de la persiana comenzará a moverse al recibir el comando Z-Wave Switch Binary Set o Switch Multilevel Set, y el movimiento se ejecutará según la configuración de posición actual.

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

 El tiempo de activación se restablecerá a**4**minutos cada vez que el control de obturador se incluye en la red Z-Wave o cuando se restablece de fábrica.

_**\\<NOTE>:**_La posición actual predeterminada del control del obturador está configurada en 99% (completamente abierto). Se recomienda abrir completamente el obturador antes de calibrar con el comando Z-Wave; de ​​lo contrario, también vuelva a ajustar la configuración de Posición actual con el comando.

-   _**Información de onda Z**_

**Clase de dispositivo genérico:**CAMBIAR_MULTI NIVEL

**Clase de dispositivo específica:**CLASE_C_MOTOR_CONTROL

**Tipo de rol:**ESCLAVO_SIEMPRE_EN

**Soporte/Control de Clase de Comando**

**Soporte CC obligatorio:**Z-Wave Plus Información CC

Servicio de Transporte CC

Seguridad_2CC

CC de supervisión

Cambiar binario (S2)

Conmutador CC multinivel, V4 (S2)

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

Switch Multinivel CC, V4 (COMANDO_CLASE_CAMBIAR_MULTI NIVEL)

\#.CAMBIAR_MULTI NIVEL_INFORME

Restablecimiento del dispositivo localmente CC, V4 (COMANDO_CLASE_DISPOSITIVO_REINICIAR_EN LA ZONA)

-   Cuando SCM cambia de posición:\[CAMBIAR_MULTI NIVEL_INFORME] 4
