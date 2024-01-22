# VESTA 182

**Parlamento**

**Interruptor de relé ZigBee**

**Introducción**

PRLM-CH3-AC-ZBS(R) es un interruptor de relé ZigBee de 3 canales que se puede conectar a dispositivos cableados y configurar en estado de apertura normal (N.O.). Después de unirse a la red ZigBee, el interruptor de retransmisión se puede controlar a través de la red ZigBee para activar los dispositivos conectados.

El Relay Switch utiliza tecnología ZigBee para la transmisión de señales inalámbricas. ZigBee es un protocolo de comunicación inalámbrica confiable, de bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir una gran cantidad de dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

El Relay Switch también cuenta con función de enrutador. Sirve como enrutador en la red ZigBee. Después de ser incluido en la red ZigBee, permite que otros dispositivos ZigBee se unan a la red a través del Relay Switch.

**Identificación de piezas**

**La cubierta superior****Base**

![](<.gitbook/assets/0 (71).jpeg>)

1.  **Botón de interruptor 1/Botón de función**
    -   El botón de función se utiliza para restablecer el interruptor de relé para unirse a una red ZigBee disponible.
    -   Mantenga presionado el botón durante 10 segundos y luego suéltelo para restablecer el interruptor de relé.
    -   Presione el botón para encender/apagar el canal de relé 1.
2.  **Botón de cambio 2**
    -   Presione el botón para encender/apagar el canal de relé 2.
3.  **Botón de cambio 3**
    -   Presione el botón para encender/apagar el canal de relé 3.

![](<.gitbook/assets/1 (56).png>)

-   _NOTA>_
    -   Cuando se presiona el botón de interruptor 2/3, el canal de relé 2/3 cambiará instantáneamente a ON/OFF.
    -   Cuando se presiona el botón de interruptor 1, el canal de relé 1 cambiará a ON/OFF después de 0,5 segundos, porque el dispositivo necesita identificar si presionar el botón es para encender/apagar o para restablecer el relé.

1.  **Indicador LED 1**
2.  **Indicador LED 2**
3.  **Indicador LED 3**

El indicador LED 1/2/3 se utiliza para indicar el estado del canal de relé 1/2/3:

-   LED 1 encendido/apagado: Canal de relé 1 encendido/apagado
-   LED 2 encendido/apagado: Canal de relé 2 encendido/apagado
-   LED 3 encendido/apagado: Canal de relé 3 encendido/apagado

1

Cuando se enciende, todos los LED parpadearán secuencialmente durante 1 ciclo.

Todos los LED parpadearán cada segundo después de que el relé se haya reiniciado, lo que indica que está en modo de aprendizaje.

Todos los LED parpadearán tres veces cuando el relé se haya unido exitosamente a una red ZigBee.

**7. Orificios de montaje**

**Terminales de conexión**

Conecte el cable al terminal, apriete el tornillo para cerrar la cortadora y mantenga el cable en su lugar. Desatornille para abrir el cortapelos y quitar el cable conectado al terminal.

1.  **Línea (entrada de CA)**
2.  **Neutral**
3.  **NO (Channel 1)**

Para conexión normal abierta con el dispositivo

1.  **Común (Canal 1)**
2.  **NO (Channel 2)**

Para conexión normal abierta con el dispositivo

1.  **Común (Canal 2)**
2.  **NO (Channel 3)**

Para conexión normal abierta con el dispositivo

1.  **Común (Canal 3)**
2.  **Abrazadera de alivio de tensión**

Las abrazaderas se utilizan para asegurar los cables y proporcionar alivio de tensión para proteger los cables del recorte de metal.

**17. Orificios para cableado**

**Especificación**

-   Fuente de alimentación: 100 - 240 V CA
-   Corriente de carga admitida (para cada canal de relé): 5 A, 250 V CA o 5 A, 30 V CC
-   Cable trenzado: 14–22 AWG

**Precaución**

-   Todos los trabajos en el dispositivo, incluida la instalación y el mantenimiento, deben ser realizados por un electricista calificado y autorizado.
-   Antes de la instalación o cualquier trabajo de mantenimiento, asegúrese de que la fuente de alimentación esté desconectada.
-   No conecte el dispositivo a cargas que excedan la corriente de carga admitida.

**Instalación**

Conecte el relé de acuerdo con las instrucciones a continuación.

1.  Apague la fuente de alimentación antes de realizar la conexión.
2.  Retire la cubierta superior y retire las abrazaderas de alivio de tensión.
3.  Conecte los terminales L y N de la fuente de alimentación a los terminales de Línea y Neutro del PRLM respectivamente a través del orificio de cableado.
4.  Dependiendo del dispositivo que desee controlar a través del canal de relé 1, seleccione el terminal NO y conecte el canal de relé 1 con el dispositivo a través del orificio de cableado para establecer una conexión abierta normal con el dispositivo.
5.  De la misma manera que en el paso 4, conecte el canal de retransmisión 2/3 a otros dispositivos cableados.
6.  Después de completar el cableado, reemplace las abrazaderas de alivio de tensión y la cubierta superior. Encienda la fuente de alimentación para encender el interruptor de relé.

![](<.gitbook/assets/2 (56).jpeg>)

2

**Configuración de red ZigBee**

![](<.gitbook/assets/3 (51).jpeg>)

-   _**Guía del dispositivo ZigBee**_

ZigBee es un protocolo de comunicación inalámbrica confiable, de bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir una gran cantidad de dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

![](<.gitbook/assets/4 (49).jpeg>)

-   _**Unirse a la red ZigBee**_

Como dispositivo ZigBee, el Relay necesita unirse a una red ZigBee para recibir comandos. Siga los pasos a continuación para agregar el relé a una red ZigBee.

-   1.  Conecte la entrada de alimentación al relé de acuerdo con las instrucciones de instalación anteriores y encienda el interruptor del relé.
    2.  Mantenga presionado el botón de función durante 10 segundos mientras el relé se reinicia y comienza a buscar la red ZigBee existente. Asegúrese de que la función de permiso para unirse en el enrutador o coordinador de su red ZigBee esté habilitada.
    3.  Si el relé se une exitosamente a una red ZigBee, el indicador LED parpadeará tres veces para confirmar.
    4.  Después de unirse a la red ZigBee, el Relay se registrará en la red automáticamente. Consulte con el coordinador de la red ZigBee, el panel de control del sistema o el CIE (equipo de control e indicación) para confirmar si la inscripción y el registro se realizaron correctamente.
-   _**Eliminación del dispositivo de la red ZigBee (restablecimiento de fábrica)**_

![](<.gitbook/assets/5 (61).png>)

Para eliminar el dispositivo de la red ZigBee actual, se debe restablecer el interruptor de relé a valores de fábrica para completar la eliminación del dispositivo. La función de restablecimiento de fábrica borrará la información de configuración almacenada del dispositivo y le pedirá que busque una nueva red ZigBee.

**Antes de retirar el dispositivo, asegúrese de que el interruptor de relé esté dentro del rango de señal de red ZigBee actual.**

-   1.  Elimine el dispositivo del panel de control/CIE actual.
    2.  Mantenga presionado el botón de función durante 10 segundos, luego suelte el botón para restablecer el dispositivo.
    3.  Al reiniciarse, el dispositivo borrará la configuración de red ZigBee actual y transmitirá la señal al coordinador de ZigBee para eliminarse de la red ZigBee actual. Luego buscará activamente nuevamente la red ZigBee disponible y se unirá a la red automáticamente.
-   _**Prueba de rango**_

![](<.gitbook/assets/6 (42).png>)

Para probar si el dispositivo puede comunicarse con el coordinador de red ZigBee o el panel de control:

-   -   Coloque la puerta de enlace/panel en modo de prueba de alcance (Prueba de caminata).
    -   Presione el botón de función en el dispositivo
    -   La puerta de enlace/panel debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual de operación de la puerta de enlace/panel).
-   _**Capacidad del dispositivo enrutador ZigBee**_

![](<.gitbook/assets/7 (37).png>)

El Relay Switch presenta la función de enrutador que permite que otros dispositivos ZigBee se unan a la red ZigBee a través del enrutador. Tiene una capacidad máxima de 40 dispositivos/enrutadores.

**Supervisión**

El interruptor de relé transmitirá una señal de supervisión para informar periódicamente el estado de encendido/apagado del canal de relé 1/2/3 de acuerdo con la configuración del usuario. El intervalo predeterminado de fábrica es de 30 minutos.

**Montaje**

-   Una vez que haya finalizado la prueba de alcance y esté satisfecho de que el dispositivo puede comunicarse con el panel de control en la ubicación elegida, continúe con el montaje.
-   Desconecte la fuente de alimentación principal.
-   Afloje el tornillo de fijación inferior y retire la cubierta superior del interruptor de relé.
-   Utilice los orificios de la base para marcar la ubicación de montaje en la pared.
-   Taladre agujeros en el lugar marcado e inserte tacos de pared si es necesario, atornille la base en el lugar de montaje.
-   Vuelva a colocar la cubierta superior y apriete el tornillo de fijación inferior.

3

![](<.gitbook/assets/8 (32).jpeg>)

**Operación**

![](<.gitbook/assets/9 (24).jpeg>)

-   _**Control de relé**_
    -   Después de que el interruptor de retransmisión se haya unido exitosamente a una red ZigBee, la puerta de enlace/panel de control puede controlar remotamente el canal de retransmisión 1/2/3 para encenderlo o apagarlo. Consulte su puerta de enlace/panel de control ZigBee para obtener más detalles.
    -   El usuario también puede presionar manualmente el botón de interruptor 1/2/3 para encender/apagar el canal de relé 1/2/3.
-   _**Actualización de firmware OTA**_

![](<.gitbook/assets/10 (18).jpeg>)

El Relay Switch admite la función de actualización de firmware OTA a través de la red ZigBee, que se puede iniciar desde el coordinador de la red ZigBee.

Siga los pasos a continuación para realizar la actualización del firmware OTA.

**Paso 1.**Debe acceder a su Coordinador ZigBee para realizar la actualización del firmware en el aire.**Paso 2.**En la página web de configuración, seleccione el dispositivo que desea actualizar y seleccione el

Se proporciona nuevo firmware ZigBee. Consulte el Manual del usuario del Coordinador ZigBee para obtener más detalles.

**Paso 3.**Presione "Aceptar" para iniciar el proceso de actualización. Durante el proceso OTA, no realice ninguna otra acción ni apague el panel.

**Etapa 4.**La duración de una actualización tardará aproximadamente entre 20 y 30 minutos. Tenga en cuenta que la duración puede variar según el tamaño del archivo o la distancia entre su accesorio y el coordinador.

**Paso 5.**Espere a que el firmware complete la actualización. Cuando el progreso alcance el 100%, el dispositivo se reiniciará automáticamente. También puede actualizar la página web nuevamente para asegurarse de que el firmware del dispositivo se actualice correctamente y se muestre la versión más reciente.

**Apéndice (solo para desarrolladores)**

![](<.gitbook/assets/11 (28).png>)

-   _**ID del grupo de retransmisión**_

**ID del dispositivo: Activado Desactivado Salida: 0x0002**

**Punto final: 0x0A**

| **Lado del servidor** |                 | **Lado del cliente** |
| --------------------- | --------------- | -------------------- |
|                       |                 |                      |
|                       | **Obligatorio** |                      |

Básico (0x0000)

Identificar(0x0003)

Activado/Desactivado(0x0006)

_Ninguno_

**Opcional**

Grupos(0x0004)

Ninguno

-   _**Atributo de información básica del clúster**_

| **Identificador** | **Nombre**               | **Tipo**          | **Rango**   | **Acceso** | **Por defecto** | **Obligatorio** |   |
| ----------------- | ------------------------ | ----------------- | ----------- | ---------- | --------------- | --------------- | - |
| **/ Opcional**    |                          |                   |             |            |                 |                 |   |
|                   |                          |                   |             |            |                 |                 |   |
| 0x0000            | _Versión ZCL_            | 8 bits sin firmar | 0x00 –0xff  | Leer       | 0x01            | METRO           |   |
| entero            | solo                     |                   |             |            |                 |                 |   |
|                   |                          |                   |             |            |                 |                 |   |
| 0x0001            | Versión de la aplicación | 8 bits sin firmar | 0x00 – 0xff | Leer       | 0x00            | oh              |   |
| entero            | solo                     |                   |             |            |                 |                 |   |
|                   |                          |                   |             |            |                 |                 |   |
| 0x0003            | _Versión HW_             | 8 bits sin firmar | 0x00 –0xff  | Leer       | 0               | oh              |   |
| entero            | solo                     |                   |             |            |                 |                 |   |
|                   |                          |                   |             |            |                 |                 |   |

4

| 0x0004   | _Nombre del Fabricante_       | Personaje  | 0 – 32 bytes | Leer   | Clímax               | oh    |   |
| -------- | ----------------------------- | ---------- | ------------ | ------ | -------------------- | ----- | - |
| Cadena   | solo                          | Tecnología |              |        |                      |       |   |
|          |                               |            |              |        |                      |       |   |
| 0x0005   | _Identificador de modelo_     | Personaje  | 0 – 32 bytes | Leer   | (Versión del modelo) | oh    |   |
| Cadena   | solo                          |            |              |        |                      |       |   |
|          |                               |            |              |        |                      |       |   |
| 0x0006   | _Código de fecha_             | Personaje  | 0 – 16 bytes | Leer   |                      | oh    |   |
| Cadena   | solo                          |            |              |        |                      |       |   |
|          |                               |            |              |        |                      |       |   |
|          |                               |            |              |        |                      |       |   |
| 0x0007   | _Fuente de alimentación_      | 8 bits     | 0x00 –0xff   | Leer   |                      | METRO |   |
| solo     |                               |            |              |        |                      |       |   |
|          |                               |            |              |        |                      |       |   |
| 0x0010   | _Descripción de la ubicación_ | Personaje  | 0 – 32 bytes | Leer / |                      | oh    |   |
| Cadena   | Escribir                      |            |              |        |                      |       |   |
|          |                               |            |              |        |                      |       |   |
| 0x0011   | _Entorno físico_              | 8 bits     | 0x00 –0xff   | Leer / | 0x00                 | oh    |   |
| Escribir |                               |            |              |        |                      |       |   |
|          |                               |            |              |        |                      |       |   |
| 0x0012   | _Dispositivo habilitado_      | Booleano   | 0x00 –0x01   | Leer / | 0x01                 | METRO |   |
| Escribir |                               |            |              |        |                      |       |   |
|          |                               |            |              |        |                      |       |   |

![](<.gitbook/assets/12 (19).jpeg>)

-   _**Atributo de información de identificación del clúster**_

![](<.gitbook/assets/13 (22).jpeg>)

| **Identificador**                                               | **Nombre**          | **Tipo**   | **Rango**    | **Acceso** | **Por defecto** | **Obligatorio** |   |
| --------------------------------------------------------------- | ------------------- | ---------- | ------------ | ---------- | --------------- | --------------- | - |
| **/ Opcional**                                                  |                     |            |              |            |                 |                 |   |
|                                                                 |                     |            |              |            |                 |                 |   |
| 0x0000                                                          | _IdentificarTiempo_ | No firmado | 0x00 –0xffff | Leer /     | 0x0000          | METRO           |   |
| entero de 16 bits                                               | Escribir            |            |              |            |                 |                 |   |
|                                                                 |                     |            |              |            |                 |                 |   |
| _**Atributo de información del clúster activado/desactivado**_ |                     |            |              |            |                 |                 |   |

![](<.gitbook/assets/14 (22).png>)

| **Identificador**                                     | **Nombre**          | **Tipo** | **Rango**  | **Acceso** | **Por defecto** | **Obligatorio** |   |
| ----------------------------------------------------- | ------------------- | -------- | ---------- | ---------- | --------------- | --------------- | - |
| **/ Opcional**                                        |                     |          |            |            |                 |                 |   |
|                                                       |                     |          |            |            |                 |                 |   |
| 0x0000                                                | _Encendido apagado_ | Booleano | 0x00 –0x01 | Leer       | 0x00            | METRO           |   |
| solo                                                  |                     |          |            |            |                 |                 |   |
|                                                       |                     |          |            |            |                 |                 |   |
| _**Atributos de la información del clúster Grupos**_ |                     |          |            |            |                 |                 |   |

![](<.gitbook/assets/15 (20).png>)

| **Identificador** | **Nombre**      | **Tipo**               | **Rango** | **Acceso** | **Por defecto** | **Obligatorio** |   |
| ----------------- | --------------- | ---------------------- | --------- | ---------- | --------------- | --------------- | - |
| **/ Opcional**    |                 |                        |           |            |                 |                 |   |
|                   |                 |                        |           |            |                 |                 |   |
| 0x0000            | _NombreSoporte_ | mapa de bits de 8 bits | x0000000  | Leer       | -               | METRO           |   |
| solo              |                 |                        |           |            |                 |                 |   |
|                   |                 |                        |           |            |                 |                 |   |

5
