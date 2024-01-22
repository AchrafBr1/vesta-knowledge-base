# VESTA 178

**Control de obturador (SCM-8ZBS)**

**Introducción**

SCM-8ZBS es un control de obturador ZigBee. El usuario puede controlar el SCM a través de la red ZigBee a distancia o manualmente vinculando un interruptor al control de persiana.

El control del obturador utiliza tecnología ZigBee para la transmisión de señales inalámbricas. ZigBee es un protocolo de comunicación inalámbrica que es confiable, tiene bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir una gran cantidad de dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

El Shutter Control sirve como dispositivo final en la red ZigBee. Puede incluirse en la red ZigBee para transmitir o recibir señales, pero no puede permitir que ningún otro dispositivo ZigBee se una a la red a través del control del obturador.

**Identificación de piezas**

1.  **Botón de función**
    -   Pulsar una vez: Transmitir una señal de supervisión.
    -   Mantenga presionado durante 3~9 segundos: ingresa al modo de calibración.
    -   Mantenga presionado durante 10 segundos: reinicie el control del obturador para unirse a la red ZigBee.
2.  **Indicador LED**

![](<.gitbook/assets/0 (67).jpeg>)

El indicador LED se utiliza para indicar el estado del control de persianas:

-   -   Parpadea una vez: el control del obturador se ha reiniciado.
    -   Parpadea dos veces: el control de persianas se ha unido exitosamente a una red ZigBee.
    -   Parpadea 5 veces: calibración manual exitosa.
    -   Parpadea una vez cada 20 minutos:

El Shutter Control ha perdido la conexión con su red ZigBee actual.

1.  **Orificios de montaje**
2.  **Interruptor local S1 (dirección abierta)**

Conecte un interruptor externo a este terminal. Activar

este interruptor para controlar el obturador para que gire hacia "Abrir"

dirección activando la salida del motor O1

Activar este interruptor cuando la persiana está rodando

hacia la dirección "Cerrar" detendrá la persiana.

**5. Interruptor local S2 (dirección de cierre)**

Conecte un interruptor externo a este terminal. Active este interruptor para controlar que la persiana gire hacia la dirección "Cerrar" activando la salida del motor O2.

Activar este interruptor cuando la persiana está girando hacia la dirección de apertura detendrá la persiana.

**6. Salida del motor O1 (dirección abierta)**

Conéctelo al terminal abierto del motor de la persiana.

**7. Salida del motor O2 (dirección de cierre)**

Conéctelo al terminal de cierre del motor de la persiana.

1.  **Entrada de alimentación L (conductor activo)**
2.  **Entrada de alimentación N (conductor neutro)**
3.  **Abrazadera de alivio de tensión**

La abrazadera se utiliza para asegurar los cables y proporcionar alivio de tensión para proteger los cables del recorte de metal.

**11. Hebilla de cableado**

La hebilla de cableado se utiliza para gestionar los cables.

1

**Especificación**

-   Fuente de alimentación: 110 - 230 VCA, 50/60 Hz
-   Corriente de carga admitida: 1/4 HP (caballos de fuerza); 1,8Amperios para motores con factor de potencia compensado (cargas inductivas)
-   Protocolo de comunicación: ZigBee Pro Home Automation 1.2, 2.4GHz

![](<.gitbook/assets/1 (59).jpeg>)

**Precaución**

-   Todos los trabajos en el dispositivo, incluida la instalación y el mantenimiento, deben ser realizados por un electricista calificado y autorizado.
-   Antes de la instalación o cualquier trabajo de mantenimiento, asegúrese de que la fuente de alimentación esté desconectada.
-   No conecte el dispositivo a cargas que excedan la corriente de carga admitida.
-   Conecte el dispositivo únicamente a un motor alimentado por CA.

**Instalación**

-   SCM-8ZBS debe conectarse según el siguiente diagrama:

![](<.gitbook/assets/2 (54).jpeg>)

-   -   Conecte el terminal N del SCM al terminal N de la fuente de alimentación.
    -   Conecte el terminal L del SCM al terminal L de la fuente de alimentación.
    -   Conecte el terminal O1 del SCM al terminal abierto del motor de la persiana.
    -   Conecte el terminal O2 del SCM al terminal de cierre del motor de la persiana.
    -   **(Conmutador local opcional)**Conecte los terminales S2 y S1 del SCM al terminal L de la fuente de alimentación.
-   Inserte cada cable en el terminal al que debe conectarse, apriete cada tornillo para cerrar las cortadoras y mantener los cables en su lugar.
-   Después de conectar los cables, utilice la hebilla de cableado para gestionar los cables y coloque la hebilla de cableado en la base con su espacio (abertura) colocado a la izquierda.

2

![](<.gitbook/assets/3 (49).jpeg>)

**Configuración de red ZigBee**

-   _**Guía del dispositivo ZigBee**_

ZigBee es un protocolo de comunicación inalámbrica que es confiable, tiene bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir varios dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

-   _**Unirse a la red ZigBee**_

Como dispositivo ZigBee, el control de obturador necesita unirse a una red ZigBee para recibir comandos. Siga los pasos a continuación para unir el control de obturador a una red ZigBee.

-   1.  Connect the power supply to the Shutter Control according to the installation instructions in previous section and power up the Shutter Control.
    2.  Mantenga presionado el botón de función durante 10 segundos mientras el control del obturador se reinicia y comienza a buscar la red ZigBee existente. Asegúrese de que la función de permiso para unirse en el enrutador o coordinador de su red ZigBee esté habilitada.
    3.  Si el control de obturador se une exitosamente a una red ZigBee, el indicador LED parpadeará dos veces para confirmar.
    4.  Después de unirse a la red ZigBee, el control de persianas se registrará en la red automáticamente. Consulte con el coordinador de la red ZigBee, el panel de control del sistema o el CIE (equipo de control e indicación) para confirmar si la inscripción y el registro se realizaron correctamente.
    5.  Después de unirse a la red ZigBee, si el control de obturador pierde la conexión con la red ZigBee actual, el indicador LED parpadeará cada 20 minutos. Verifique la condición de su red ZigBee y el rango de señal del control del obturador para corregir la condición.
-   _**Eliminación del dispositivo de la red ZigBee (restablecimiento de fábrica)**_

Para eliminar el control del obturador de la red ZigBee actual, se debe restablecer el control del obturador a valores de fábrica para completar la eliminación del dispositivo. La función de restablecimiento de fábrica borrará la información de configuración almacenada del control del obturador y solicitará al dispositivo que busque una nueva red ZigBee.

**Antes de retirar el dispositivo, asegúrese de que el control del obturador esté dentro del rango de señal de red ZigBee actual.**

1.  Mantenga presionado el botón de función durante 10 segundos, luego suelte el botón para restablecer el control del obturador.
2.  Al reiniciarse, el control del obturador borrará la configuración actual de la red ZigBee y transmitirá la señal al coordinador ZigBee para eliminarse de la red ZigBee actual. Luego buscará activamente nuevamente la red ZigBee disponible y se unirá a la red automáticamente.

**Supervisión**

El control de obturador transmitirá una señal de supervisión para informar su condición periódicamente según la configuración del usuario. El intervalo predeterminado de fábrica es de 30 minutos. El usuario también puede presionar el botón de función una vez para transmitir una señal de supervisión manualmente.

**Operación**

-   _**Calibración**_
    -   El tiempo de activación predeterminado del control de persianas es**4**minutos. Cuando se presiona el botón Arriba/Abajo o el coordinador de red ZigBee transmite el comando Arriba/Abajo, activará el motor de la persiana durante 4 minutos.
    -   Para que el Control de Persiana funcione correctamente es necesario calibrar su tiempo de activación. Hay dos formas de ajustar el tiempo de activación:
        -   **Comando ZigBee:**El tiempo de activación se puede ajustar enviando un comando desde el coordinador de red ZigBee. (Consulte el Apéndice – Atributo de grupo de nivel – OnTransitionTime / OffTransitionTime, unidad mínima ajustable 100 ms)
        -   **Calibración manual:**Calibre la activación según el procedimiento siguiente:

3

-   -   1.  Antes de la calibración, los interruptores locales externos deben estar conectados al control de persianas.
        2.  Mantenga presionado el botón Función durante 3~9 segundos y suéltelo para ingresar al modo de calibración. El control del obturador girará hacia la dirección "Abrir" durante 4 minutos al ingresar al modo de calibración.
        3.  Espere 4 minutos para que el control de la persiana deje de girar hacia la dirección "Abrir", luego active el interruptor local externo "Cerrar" conectado para cerrar la persiana.
        4.  Active el interruptor local externo “Abrir” en el momento en que la persiana esté completamente cerrada. El control del obturador registrará el tiempo transcurrido entre los pasos 3 y 4 como el nuevo "**hora de cierre**”.
        5.  El control del obturador girará hacia la dirección de apertura después del paso 4.
        6.  Active el interruptor local externo “Cerrar” en el momento en que la persiana esté completamente abierta. El control del obturador registrará el tiempo transcurrido entre los pasos 5 y 6 como el nuevo "**tiempo abierto**”.

Ejemplo

Si el obturador tarda 30 segundos en pasar de Abierto a Cerrado y 40 segundos en pasar de Cerrado a Abierto, el nuevo**hora de cierre**será**30**segundos y nuevo**tiempo abierto**será**40**segundos.

Después de la calibración, siempre que el control del obturador reciba una orden de cierre, girará hacia la dirección de cierre durante 30 segundos. Cuando reciba el comando de apertura, girará hacia la apertura durante 40 segundos.

-   -   El tiempo de activación se restablecerá a**4**minutos cada vez que el control de persianas se une a una red ZigBee.
    -   Si el proceso de calibración manual tiene éxito, el LED parpadeará 5 veces para indicarlo.
-   _**Control de obturador**_

**Red ZigBee**

-   Después de que el control de la persiana se haya unido con éxito a una red ZigBee, el coordinador puede controlar remotamente la persiana para abrirla, cerrarla o detenerla transmitiendo un comando a través de la red ZigBee.
-   Cuando el control de la persiana recibe una señal de apertura/cierre del coordinador, girará hacia la dirección de apertura/cierre de acuerdo con el tiempo de activación calibrado para abrir/cerrar completamente la persiana.
-   El estado del obturador también se puede ajustar por porcentaje desde 0%, 10%, 20%... hasta 100% a través del Coordinador ZigBee.
-   El porcentaje de apertura actual también se transmite al coordinador de ZigBee.

**Conmutador local**

-   -   Si se conecta un interruptor local opcional, los usuarios también pueden presionar el botón del interruptor para abrir/cerrar la persiana.
    -   Presione y suelte el interruptor durante menos de 1 segundo para controlar que el obturador se abra o cierre completamente.
    -   Mantenga presionado el interruptor durante más de 1 segundo para controlar la apertura y el cierre del obturador hasta que se suelte el interruptor. Cuando se suelta el interruptor, el obturador se detendrá.
    -   Al presionar el interruptor cuando la persiana se está moviendo en la dirección opuesta, se detendrá la persiana. Presione el interruptor nuevamente para abrir/cerrar la persiana.

Por ejemplo, presionar el interruptor hacia abajo cuando la persiana se está abriendo detendrá la persiana; presione el interruptor hacia abajo nuevamente para comenzar a cerrar la persiana.

-   _**Actualización de firmware OTA (solo para la versión OTA)**_

El control de obturador admite la función de actualización de firmware OTA a través de la red ZigBee, que puede iniciarse desde el coordinador de red ZigBee.

Siga los pasos a continuación para realizar la actualización del firmware OTA.

**Paso 1.**Debe acceder a su Coordinador ZigBee para realizar la actualización del firmware en el aire.**Paso 2.**En la página web de configuración, seleccione el dispositivo que desea actualizar y seleccione el nuevo

Se proporciona firmware ZigBee. Consulte el Manual del usuario del Coordinador ZigBee para obtener más detalles.

**Paso 3.**Presione "OK" para iniciar el proceso de actualización y el LED seguirá parpadeando. Durante el proceso de la OTA,

no realice ninguna otra acción ni apague el panel.

**Etapa 4.**La duración de una actualización tardará aproximadamente entre 20 y 30 minutos. Tenga en cuenta que la duración puede variar según el tamaño del archivo o la distancia entre su accesorio y el coordinador.

**Paso 5.**Espere a que el firmware complete la actualización. Cuando el progreso alcance el 100%, el dispositivo se reiniciará automáticamente. También puede actualizar la página web nuevamente para asegurarse de que el firmware del dispositivo se actualice correctamente y se muestre la versión más reciente.

**Apéndice (solo para desarrolladores)**

-   _**Control de obturador de relé de potencia con ID de grupo de medidores**_

**ID del dispositivo: Sombra: 0x0200**

**Punto final: 0x01**

| **Lado del servidor** |                 | **Lado del cliente** |
| --------------------- | --------------- | -------------------- |
|                       |                 |                      |
|                       | **Obligatorio** |                      |

Básico (0x0000)

_Ninguno_

4

Identificar(0x0003)

Activado/Desactivado(0x0006)

Control de nivel(0x0008)

Configuración de sombra (0x0x0100)

Grupos(0x0004)

Escenas (0x0005)

**Opcional**

| Ninguno                                                         |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 | Ninguno         |   |
| --------------------------------------------------------------- | ----------------------------- | --------------------- | ---------------------- | ---------------------- | -------------- | -------------- | -------------------- | -------------- | ---------- | --------------- | --------------- | --------------- | --------------- | --------------- | - |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| _**Atributo de información básica del clúster**_               |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| **Identificador**                                               | **Nombre**                    |                       |                        | **Tipo**               |                |                | **Rango**            |                | **Acceso** |                 | **Por defecto** | **Obligatorio** |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                | **/ Opcional** |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| 0x0000                                                          | _Versión ZCL_                 | 8 bits sin firmar     |                        | 0x00 –0xff             |                | Solo lectura   |                      | 0x01           | METRO      |                 |                 |                 |                 |                 |   |
|                                                                 |                               | entero                |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| 0x0001                                                          | Versión de la aplicación      | 8 bits sin firmar     |                        | 0x00 – 0xff            |                | Solo lectura   |                      | 0x00           | oh         |                 |                 |                 |                 |                 |   |
|                                                                 |                               | entero                |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| 0x0003                                                          | _Versión HW_                  | 8 bits sin firmar     |                        | 0x00 –0xff             |                | Solo lectura   | 0                    | oh             |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               | entero                |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| 0x0004                                                          | _Nombre del Fabricante_       | Cadena de caracteres  |                        | 0 – 32 bytes           |                | Solo lectura   |                      | Clímax         | oh         |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       | Tecnología             |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| 0x0005                                                          | _Identificador de modelo_     | Cadena de caracteres  |                        | 0 – 32 bytes           |                | Solo lectura   | (Versión del modelo) | oh             |            |                 |                 |                 |                 |                 |   |
| 0x0006                                                          | _Código de fecha_             | Cadena de caracteres  |                        | 0 – 16 bytes           |                | Solo lectura   |                      |                | oh         |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| 0x0007                                                          | _Fuente de alimentación_      |                       |                        | 8 bits                 |                | 0x00 –0xff     |                      | Solo lectura   |            |                 | METRO           |                 |                 |                 |   |
| 0x0010                                                          | _Descripción de la ubicación_ | Cadena de caracteres  |                        | 0 – 32 bytes           |                | Leer escribir  |                      |                | oh         |                 |                 |                 |                 |                 |   |
| 0x0011                                                          | _Entorno físico_              |                       |                        | 8 bits                 |                | 0x00 –0xff     |                      | Leer escribir  |            | 0x00            | oh              |                 |                 |                 |   |
| 0x0012                                                          | _Dispositivo habilitado_      |                       |                        | Booleano               |                | 0x00 –0x01     |                      | Leer escribir  |            | 0x01            | METRO           |                 |                 |                 |   |
| _**Atributo de información de identificación del clúster**_    |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| **Identificador**                                               | **Nombre**                    |                       |                        | **Tipo**               |                |                | **Rango**            |                | **Acceso** |                 | **Por defecto** | **Obligatorio** |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                | **/ Opcional** |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| 0x0000                                                          | _IdentificarTiempo_           | 16 bits sin firmar    |                        | 0x00 –0xffff           |                | Leer escribir  |                      | 0x0000         | METRO      |                 |                 |                 |                 |                 |   |
|                                                                 |                               | entero                |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| _**Atributo de información del clúster activado/desactivado**_ |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| **Identificador**                                               | **Nombre**                    |                       |                        | **Tipo**               |                |                | **Rango**            |                | **Acceso** |                 | **Por defecto** | **Obligatorio** |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                | **/ Opcional** |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| 0x0000                                                          | _Encendido apagado_           |                       |                        | Booleano               |                | 0x00 –0x01     |                      | Solo lectura   |            | 0x00            | METRO           |                 |                 |                 |   |
| _**Atributo de información del grupo de niveles**_             |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| **Identificador**                                               | **Nombre**                    |                       |                        | **Tipo**               |                | **Rango**      |                      | **Acceso**     |            | **Por defecto** | **Obligatorio** |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        | **/ Opcional** |                |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| 0x0000                                                          | _Nivel actual_                |                       |                        | No firmado             |                | 0x00 –0xff     |                      | Solo lectura   |            | 0x00            | METRO           |                 |                 |                 |   |
|                                                                 |                               | entero de 8 bits      |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| 0x0012                                                          | _En tiempo de transición_     |                       |                        | 16 bits sin firmar     |                | 0x0000 –       |                      | Leer escribir  |            | 0x0960          | oh              |                 |                 |                 |   |
|                                                                 |                               | entero                |                        | 0xFFFE                 |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| 0x0013                                                          | _ApagadoTiempodetransición_   |                       |                        | 16 bits sin firmar     |                | 0x0000 –       |                      | Leer escribir  |            | 0x0960          | oh              |                 |                 |                 |   |
|                                                                 |                               | entero                |                        | 0xFFFE                 |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| _**Atributos de la información del grupo de sombras**_         |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| **Identificador**                                               | **Nombre**                    |                       |                        | **Tipo**               |                |                | **Rango**            |                | **Acceso** |                 | **Por defecto** | **Obligatorio** |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                | **/ Opcional** |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| 0x0002                                                          | _Estado_                      |                       | mapa de bits de 8 bits |                        | 0000xxxxB      |                | Leer escribir        |                | 00000000B  | METRO           |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| 0x0010                                                          | _Límite cerrado_              | 16 bits sin firmar    |                        |                        | 0x0001 –       |                | Leer escribir        |                | 0x0001     | METRO           |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        | entero                 |                |                | 0xfffe               |                |            |                 |                 |                 |                 |                 |   |
| 0x0011                                                          | _Modo_                        | Enumeración de 8 bits |                        | 0x00 – 0xfe            |                | Leer escribir  |                      | 0x00           | METRO      |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| _**Atributos de la información del clúster Grupos**_           |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| **Identificador**                                               | **Nombre**                    |                       |                        | **Tipo**               |                |                | **Rango**            |                |            | **Acceso**      |                 |                 | **Por defecto** | **Obligatorio** |   |
|                                                                 |                               |                       |                        |                        |                |                |                      | **/ Opcional** |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| 0x0000                                                          | _NombreSoporte_               |                       |                        | mapa de bits de 8 bits |                | x0000000       |                      | Solo lectura   |            | -               | METRO           |                 |                 |                 |   |
| _**Atributos del grupo de escenas Información**_               |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| **Identificador**                                               | **Nombre**                    |                       |                        | **Tipo**               |                |                | **Rango**            |                |            | **Acceso**      |                 |                 | **Por defecto** | **Obligatorio** |   |
|                                                                 |                               |                       |                        |                        |                |                |                      | **/ Opcional** |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| 0x0000                                                          | _Recuento de escenas_         |                       |                        | 8 bits sin firmar      |                | 0x00 – 0xff    |                      | Solo lectura   |            |                 | 0x00            | METRO           |                 |                 |   |
|                                                                 |                               | entero                |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| 0x0001                                                          | _Escena actual_               |                       |                        | 8 bits sin firmar      |                | 0x00 – 0xff    |                      | Solo lectura   |            |                 | 0x00            | METRO           |                 |                 |   |
|                                                                 |                               | entero                |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| 0x0002                                                          | _Grupo actual_                |                       |                        | No firmado             |                | 0x0000 –       |                      | Solo lectura   |            |                 | 0x00            | METRO           |                 |                 |   |
|                                                                 |                               | entero de 16 bits     |                        |                        | 0xfff7         |                |                      |                |            |                 |                 |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                |                |                      |                |            |                 |                 |                 |                 |                 |   |
| 0x0003                                                          | _Escena válida_               |                       |                        | Booleano               |                | 0x00 – 0x01    |                      | Solo lectura   |            |                 | 0x00            | METRO           |                 |                 |   |
| 0x0004                                                          | _NombreSoporte_               |                       |                        | mapa de bits de 8 bits |                | x0000000       |                      | Solo lectura   |            | -               | METRO           |                 |                 |                 |   |
|                                                                 |                               |                       |                        |                        |                | 5              |                      |                |            |                 |                 |                 |                 |                 |   |
