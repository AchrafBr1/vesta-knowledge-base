# VESTA 296

**Control de persianas en carril DIN (SCM-6-AS-DIN2-ZW)**

**Introducción**

SCM-6-AS-DIN2-ZW es un control de obturador Z-Wave™. El usuario puede controlar el SCM a través de la red Z-Wave a distancia o manualmente vinculando un interruptor al control del obturador.

Sube, baja o se detiene de forma automática o remota a mitad de camino, el SCM-6-AS-ZW está directamente conectado y controla tratamientos de ventanas motorizados, cortinas y persianas interiores y exteriores, pantallas de proyección y puertas de garaje o puertas de entrada de su hogar. .

El control del obturador solo es compatible con el panel de control/puerta de enlace Z-Wave. Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. Al aprovechar la red de malla Z-Wave, los comandos se pueden enrutar a su destino a través de productos Z-Wave intermediarios que “escuchan”.

El control de obturador Z-Wave permite el acceso a la clase "S2 no autenticado" y admite la inclusión Z-Wave SmartStart así como la inclusión clásica.

**Identificación de piezas**

![](<.gitbook/assets/0 (103).jpeg>)

1.  **Puerto de antena externa**
2.  **Indicador LED**
    -   Encendido: el LED parpadea dos veces.
    -   En modo de calibración automática: el LED parpadea una vez por segundo.
    -   Restablecimiento de fábrica: el LED parpadea dos veces.
    -   Al presionar el interruptor local S1/S2: LED encendido.
3.  **Botón de función**
    -   -   Presione el botón de función y el control del obturador enviará un informe multinivel.
        -   Presione el botón de función 3 veces en 1 segundo para incluir o excluir el control del obturador en/de la red Z-Wave.
        -   Mantenga presionado el botón de función durante 10 segundos para restablecer.
        -   Mantenga presionado el botón de función durante 3 segundos y luego suéltelo para ingresar al modo de calibración automática.
4.  **Terminal de salida de alimentación L (conductor activo)**
5.  **Terminal L de entrada de alimentación de CA (conductor activo)**
6.  **Terminal de entrada de alimentación de CA N (conductor neutro)**
7.  **Terminal del interruptor local S2 (dirección de cierre)**

Conecte un interruptor externo al terminal. Active este interruptor para controlar que la persiana gire hacia la dirección "Abrir" activando la salida del motor O2.

Activar este interruptor cuando la persiana está girando hacia la dirección "Abrir" detendrá la persiana.

**8. Terminal del interruptor local S1 (dirección abierta)**

Conecte un interruptor externo al terminal. Active este interruptor para controlar que la persiana gire hacia la dirección "Abrir" activando la salida del motor O1.

Activar este interruptor cuando la persiana está girando hacia la dirección "Cerrar" detendrá la persiana.

**9. Terminal de salida del motor O2 (dirección de cierre)**

Conéctelo al terminal de cierre del motor de la persiana.

**10. Terminal de salida del motor O1 (dirección abierta)**

Conéctelo al terminal abierto del motor de la persiana.

**11. Terminal de salida de energía N (conductor neutro)**

**Especificación**

-   Fuente de alimentación: 100 - 240 VCA, 50/60 Hz
-   Corriente de carga admitida: 3 amperios para motores con factor de potencia compensado (cargas inductivas)
-   Protocolo de comunicación: módulo serie Z-Wave Plus 700

1

![](<.gitbook/assets/1 (85).jpeg>)**Precaución**

-   Todos los trabajos en el dispositivo, incluida la instalación y el mantenimiento, deben ser realizados por un electricista calificado y autorizado.
-   Antes de la instalación o cualquier trabajo de mantenimiento, asegúrese de que la fuente de alimentación esté desconectada.
-   No conecte el dispositivo a cargas que excedan la corriente de carga admitida.
-   Conecte el dispositivo únicamente a un motor alimentado por CA.

**Cableado e instalación**

**Antes de la instalación, asegúrese de que la fuente de alimentación esté desconectada.**

-   SCM-6-AS-DIN2-ZW debe conectarse según los 2 diagramas siguientes:

**Cableado 1****Cableado 2**

![](<.gitbook/assets/2 (79).png>)

-   -   Conecte el terminal L y N de entrada de alimentación de CA del SCM al terminal L y N de la fuente de alimentación respectivamente.
    -   Conecte el terminal de salida de energía N del SCM al terminal N del motor de la persiana.
    -   Conecte el terminal O1 del SCM al terminal abierto del motor de la persiana.
    -   Conecte el terminal O2 del SCM al terminal de cierre del motor de la persiana.
    -   **(Conmutadores locales opcionales)**Conecte los terminales S2 y S1 del SCM a 2 interruptores externos y conecte 2 interruptores externos al terminal L de la fuente de alimentación.
-   Inserte cada cable en el terminal al que debe conectarse de acuerdo con 2 diagramas de cableado

como se muestra arriba y apriete el tornillo de cada terminal.

-   Conecte la antena externa al puerto de antena externa.
-   Monte el dispositivo dentro del gabinete eléctrico usando un riel DIN.

**Características**

-   _**Agregar dispositivo (inclusión)**_

Este producto se puede incluir y operar en cualquier red Z-Wave con otros dispositivos certificados Z-Wave de otros fabricantes y/u otras aplicaciones. Todos los nodos de la red que no funcionan con baterías actuarán como repetidores independientemente del proveedor para aumentar la confiabilidad de la red. El dispositivo admite tanto el proceso de inclusión clásico como el proceso de inclusión SmartStart.

**Inclusión clásica**

-   Conecte la alimentación al control del obturador (consulte las instrucciones del manual).**Cableado e instalación**).
-   Coloque la puerta de enlace Z-wave o el panel de control en**Modo de inclusión**(consulte el manual de la puerta de enlace Z-wave o del panel de control).
-   En 1 segundo, presione el botón de función 3 veces.
-   Consulte el manual de funcionamiento de la puerta de enlace Z-wave o del panel de control para completar el proceso de adición.
-   Si el dispositivo ya se ha agregado (incluido) en otro panel de control/puerta de enlace Z-wave, o si el dispositivo no se puede agregar al panel de control/puerta de enlace Z-wave actual, intente eliminarlo primero (consulte_**Quitar dispositivo**_).

2

**Inclusión de SmartStart**

Z-Wave SmartStart utiliza el DSK del dispositivo para mejorar y simplificar el proceso de inclusión. DSK es una clave específica del dispositivo que se utiliza para la autenticación. La información DSK se almacena en formato de código QR que se imprime en una pegatina y se adhiere al dispositivo.

![](<.gitbook/assets/3 (69).jpeg>)

-   -   -   Escanee la etiqueta del código QR en el lado derecho del control del obturador para obtener DSK y transferirlo a la puerta de enlace Z-Wave.
        -   Conecte la alimentación al control de obturador y se enviará automáticamente una solicitud de inclusión de SmartStart al portal.
        -   La puerta de enlace incluirá automáticamente el dispositivo al reconocerlo haciendo coincidir la solicitud de inclusión con el DSK obtenido.
    -   _NOTA>_
        -   -   El DSK del dispositivo se utiliza sólo durante la inclusión.
            -   El DSK se puede leer sin que el control del obturador esté encendido, por lo que es posible preparar la puerta de enlace para incluir el dispositivo antes de encender el control del obturador.
            -   Antes de quitar o restablecer los valores de fábrica del control del obturador,

asegúrese de que la información DSK del dispositivo se haya eliminado o no exista en la puerta de enlace. Si elimina o restablece el dispositivo a los valores de fábrica, pero su DSK aún existe en la puerta de enlace, la puerta de enlace incluirá automáticamente el dispositivo nuevamente.

-   _**Eliminación del dispositivo (exclusión)**_

El dispositivo debe eliminarse de la red Z-wave existente antes de agregarlo a otra.**Modo de exclusión**

-   Coloque la puerta de enlace Z-wave o el panel de control en**Modo de exclusión**(consulte el manual de la puerta de enlace Z-wave o del panel de control).
-   En 1 segundo, presione el botón de función 3 veces y el dispositivo se eliminará de la red Z-wave.

**Restablecimiento de fábrica**

_(Utilice el restablecimiento de fábrica únicamente cuando falte el panel de control/puerta de enlace de la red o no esté operativo)._

El restablecimiento de fábrica del dispositivo lo restaurará a la configuración predeterminada de fábrica (es decir, no estará incluido en ninguna red Z-wave).

-   -   Mantenga presionado el botón de función del dispositivo durante 10 segundos para restablecer los valores de fábrica.
-   _**Prueba de rango**_

Para probar si el dispositivo puede comunicarse con la puerta de enlace Z-wave o el panel de control:

-   Coloque la puerta de enlace/panel en modo de prueba de alcance (Prueba de caminata).
-   Presione el botón de función en el dispositivo.
-   La puerta de enlace/panel debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual de operación de la puerta de enlace/panel).

**Operación**

-   _**Control de obturador**_
    -   **Control manual**

Si se conecta un interruptor local opcional, el usuario puede presionar y mantener presionado el botón del interruptor local arriba/abajo (S1 arriba; S2 abajo) durante 1 segundo para controlar el obturador. Cuando se activa, la persiana se subirá/bajará.

Cuando la persiana está rodando, el usuario puede detenerla presionando el botón de dirección opuesta.

-   -   **Red Z-Wave**

Después de que el control de obturador se haya incluido exitosamente en una red Z-Wave, el controlador Z-Wave puede controlar el obturador con el comando Z-wave Switch Binary Set o Switch Multilevel Set, usando los siguientes parámetros:

-   -   -   Valor: 0x00~0% (0%)~99%, 0% = cierre total, 99% = apertura total)
        -   Duración de la atenuación: 0x00
-   _**Calibración**_
    -   El tiempo de activación predeterminado del control de persianas es**4**minutos.

Cuando se presiona el botón Arriba/Abajo, se activará el motor de la persiana durante 4 minutos.

Cuando se recibe un comando Z-Wave del controlador Z-Wave, determinará el porcentaje de recorrido del obturador utilizando 4 minutos como base para el cálculo.

-   -   Para que el control del obturador funcione correctamente, su tiempo de activación debe calibrarse de acuerdo con la distancia real de recorrido del obturador. Hay dos formas de ajustar el tiempo de activación:

3

-   **Calibración automática:**Calibre la activación según el procedimiento siguiente:
    1.  Mantenga presionado el botón de función durante 3 segundos y luego suéltelo para ingresar al modo de calibración automática. El LED comenzará a parpadear una vez por segundo; El motor de la persiana se enrollará hasta la parte superior.
    2.  Cuando el motor de la persiana suba hasta la parte superior y se detenga, automáticamente bajará y registrará el tiempo que tarda en rodar desde la posición abierta (arriba) a la posición cerrada (abajo) como la nueva

“**hora de cierre**”.

-   1.  Cuando el motor de la persiana baje hasta el fondo, se enrollará y registrará el tiempo que tarda en rodar desde la posición cerrada (inferior) a la posición abierta (superior) como el nuevo "**tiempo abierto**”.
    2.  Cuando se completen todas las acciones, el control del obturador enviará un MULTINIVEL_INFORME: 0x63 al controlador indicando que la posición actual está en la parte superior. El LED se apagará cuando el motor del obturador salga del modo de calibración automática.
    3.  Después de la calibración, el motor de la persiana funcionará de acuerdo con los tiempos de subida y bajada recién registrados.
-   Por ejemplo, si el obturador tarda 30 segundos en moverse de la posición "Arriba" a "Abajo", su nuevo tiempo de cierre será de 30 segundos. Después de la calibración, siempre que se presione el botón "Abajo", el obturador bajará durante 30 segundos.
-   Si la persiana tarda 40 segundos en moverse de la posición "Abajo" a "Arriba", su nuevo tiempo de apertura será
    1.  segundos. Después de la calibración, siempre que se presione el botón "Arriba", el obturador se subirá durante 40 segundos.
-   **Comando Z-Wave:**Además de la calibración automática, los usuarios también pueden ajustar el tiempo de activación enviando un comando desde el controlador Z-Wave con el comando Configuración CC, utilizando los siguientes parámetros:

| **Configuración**               | **Parámetro** |   | **Tamaño** | **Valor**                              | **Por defecto**       |                |   |
| ------------------------------- | ------------- | - | ---------- | -------------------------------------- | --------------------- | -------------- | - |
|                                 | **Número**    |   |            |                                        |                       |                |   |
|                                 |               |   |            |                                        |                       |                |   |
| Configuración de tiempo abierto | 0x01          |   | 0x02       | 0x0000~0x0960 (0,1 seg)                | 0x0960                | (240 segundos) |   |
|                                 |               |   |            |                                        |                       |                |   |
| Configuración de hora de cierre | 0x02          |   | 0x02       | 0x0000~0x0960 (0,1 seg)                | 0x0960                | (240 segundos) |   |
|                                 |               |   |            |                                        |                       |                |   |
| Posición actual                 | 0x03          |   | 0x02       | 0x0000~0x0063 (%)                      | 0x0063                | (99%)          |   |
|                                 |               |   |            |                                        | Completamente abierto |                |   |
|                                 |               |   |            |                                        |                       |                |   |
| Calibración                     | 0x04          |   | 0x01       | 0 – el dispositivo no está calibrado   | 0                     |                |   |
|                                 |               |   |            | (solo lectura)                         |                       |                |   |
|                                 |               |   |            | 1 - el dispositivo está calibrado      |                       |                |   |
|                                 |               |   |            | (solo lectura)                         |                       |                |   |
|                                 |               |   |            | 2- dispositivo de fuerza para ejecutar |                       |                |   |
|                                 |               |   |            | calibración                            |                       |                |   |
|                                 |               |   |            |                                        |                       |                |   |

-   Número de parámetro: 0x01~0x04
    -   Para el parámetro 1, los usuarios pueden configurar el tiempo de apertura (de abajo a arriba) en un valor que oscila entre 0 y 240 segundos.
    -   Para el parámetro 2, los usuarios pueden configurar el tiempo de cierre (de arriba a abajo) en un valor que oscila entre 0 y 240 segundos.
    -   Para el parámetro 3, los usuarios pueden establecer la posición actual en un valor que oscila entre %0 y %99.
    -   Para el parámetro 4, los usuarios pueden establecer un valor para forzar al dispositivo a ejecutar la calibración o verificar el estado de la calibración por valor. Establezca el valor en 2 para que el dispositivo ejecute la calibración. Si el valor es 0, representa que el dispositivo no está calibrado. Si el valor es 1, representa que el dispositivo está calibrado.
-   Tamaño: 0x02. Esto se utiliza para especificar el tamaño del valor real.
-   Valor de configuración: 0x0000~0x0960 (0,1 segundos)
-   El control de la persiana comenzará a moverse al recibir el comando de onda Z Cambiar configuración binaria o Cambiar configuración multinivel, y el movimiento se ejecutará según la configuración de posición actual.

Ejemplo de configuración:

|                                           | **Número de parámetro** | **Tamaño** | **Valor**                     |
| ----------------------------------------- | ----------------------- | ---------- | ----------------------------- |
|                                           |                         |            |                               |
|                                           | 01                      | 02         | 0x03E8 (100 segundos)         |
|                                           |                         |            |                               |
|                                           | 02                      | 02         | 0x03E8 (100 segundos)         |
|                                           | 03                      | 02         | 0032 (50%)                    |
|                                           |                         |            |                               |
|                                           | 04                      | 01         | 2- fuerza el dispositivo para |
|                                           |                         |            | ejecutar calibración          |
| CAMBIAR_MULTI NIVEL_CONFIGURAR: 0x00 (0%) |                         |            |                               |

SCM bajará (de arriba a abajo) durante 50 segundos: (1000/1000)\*(100-50)

-   El tiempo de activación se restablecerá a**4**minutos cada vez que el control de obturador se incluye en la red Z-Wave o cuando se restablece de fábrica.

_**\\<NOTE>:**_La posición actual predeterminada del control del obturador está configurada en 99% (completamente abierto). Se recomienda abrir completamente el obturador antes de calibrar con el comando Z-Wave; de ​​lo contrario, también vuelva a ajustar la configuración de Posición actual con el comando.

4

**Información de onda Z**

**Tipo de dispositivo:**GENÉRICO_TIPO_CAMBIAR_MULTI NIVEL

**Tipo específico:**ESPECÍFICO_TIPO_CLASE_C_MOTOR_CONTROL

**Tipo de rol:**Siempre en esclavo (AOS)

**Identificación del fabricante:**0x018E

**Identificación del tipo de producto:**0x0004

**ID del Producto:**0x0105

**Clase de comando admitida:**

| **Clase de comando**                        | **Versión** | **Clase de seguridad requerida**     |
| ------------------------------------------- | ----------- | ------------------------------------ |
|                                             |             |                                      |
| Asociación                                  | 2           | Clase de seguridad más alta otorgada |
| Información del grupo de asociación         | 3           | Clase de seguridad más alta otorgada |
| Básico                                      | 2           | Clase de seguridad más alta otorgada |
| Restablecimiento del dispositivo localmente | 1           | Clase de seguridad más alta otorgada |
| Metadatos de actualización de firmware      | 5           | Clase de seguridad más alta otorgada |
| Específico de fabricación                   | 2           | Clase de seguridad más alta otorgada |
| Multicanal                                  | 4           | Clase de seguridad más alta otorgada |
| Asociación multicanal                       | 3           | Clase de seguridad más alta otorgada |
| Nivel de potencia                           | 1           | Clase de seguridad más alta otorgada |
| Cambiar binario                             | 2           | Clase de seguridad más alta otorgada |
| Cambiar multinivel                          | 4           | Clase de seguridad más alta otorgada |
| Configuración                               | 1           | Clase de seguridad más alta otorgada |
| Versión                                     | 3           | Clase de seguridad más alta otorgada |
| Servicio de transporte                      | 2           | Ninguno                              |
| Información sobre Z-Wave Plus               | 2           | Ninguno                              |
| Seguridad 2                                 | 1           | Ninguno                              |
| Seguridad                                   | 1           | Ninguno                              |
| Supervisión                                 | 1           | Ninguno                              |

**Grupos de asociación:**

**IDENTIFICACIÓN**

1

| **Nombre**    | **Recuento de nodos** | **Descripción**                                                           |
| ------------- | --------------------- | ------------------------------------------------------------------------- |
| Línea de vida | 40                    | Admite las siguientes clases de comando:                                  |
|               |                       | ● Restablecimiento del dispositivo localmente: se activa al restablecerse |
|               |                       | ● Informe Switch Multilevel: informe realizado por el                     |
|               |                       | cambio de posición                                                        |
|               |                       |                                                                           |

5
