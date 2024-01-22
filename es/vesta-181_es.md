# VESTA 181

**Interruptor de palanca de relé ZigBee PRL-1ZBS(R)-AC**

**Introducción**

PRL-1ZBS es un interruptor de palanca de relé ZigBee. El interruptor de palanca de relé se puede conectar a un dispositivo cableado y configurar en estado de apertura normal (N.O.) o cierre normal (N.C.). Después de unirse a la red ZigBee, el interruptor de palanca de relé se puede controlar a través de la red ZigBee para activar los dispositivos conectados.

El interruptor de palanca de relé utiliza tecnología ZigBee para la transmisión de señales inalámbricas. ZigBee es un protocolo de comunicación inalámbrica que es confiable, tiene bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir una gran cantidad de dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

El interruptor de palanca de relé sirve como dispositivo final en la red ZigBee. Puede incluirse en la red ZigBee para transmitir o recibir señales, pero no puede permitir que ningún otro dispositivo ZigBee se una a la red a través del interruptor de palanca de relé.

Los modelos con función de enrutador también sirven como enrutador en la red ZigBee. Después de ser incluido en la red ZigBee, permite que otros dispositivos ZigBee se unan a la red a través del interruptor de encendido.

**Identificación de piezas**

![](<.gitbook/assets/0 (70).jpeg>)

**1. Indicador LED**

El indicador LED se utiliza para indicar el estado del relé:

-   -   Parpadea una vez: el relé se ha reiniciado.
    -   Parpadea dos veces: el relé se ha unido exitosamente a una red ZigBee.
    -   Parpadea una vez cada 20 minutos:

El Relay ha perdido la conexión a su red ZigBee actual.

1.  **Botón de función**

El botón de función se utiliza para restablecer el interruptor de palanca de relé para unirse a una red ZigBee disponible.

Mantenga presionado el botón durante 10 segundos y luego suéltelo para restablecer el interruptor de palanca del relé.

**Terminales de conexión**

Presione el botón para abrir el cortapelos para cada terminal y conectar el cableado. Suelte el botón para cerrar la cortadora y mantener el cable en su lugar.

1.  **Reservado**
2.  **Línea (entrada de CA)**
3.  **Neutral**
4.  **NO**

Para conexión normal abierta con el dispositivo

1.  **Común**
2.  **CAROLINA DEL NORTE**

Para conexión normal cercana con el dispositivo

**Especificación**

-   Fuente de alimentación (alimentación externa): 100-240 VCA
-   Salida de relé: relé SPDT libre de potencial, carga máxima de operación: 5 A (resistiva) a 24 V CC o 240 V CA
-   Cable trenzado: 16-26 AWG
-   Temperatura de funcionamiento: -10 °C a 45 °C (14 °F a 113 °F)
-   Humedad: Hasta 85% sin condensación
-   Dimensiones: 71,1 mm x 49 mm x 26 mm

1

![](<.gitbook/assets/1 (62).jpeg>)

**Entorno de instalación**

-   El controlador de relé debe instalarse en interiores, en un lugar seco.
-   Se recomienda instalar el dispositivo en una caja de distribución de plástico resistente al fuego.
-   No instale el dispositivo en una caja de distribución metálica para optimizar el alcance de RF.

![](<.gitbook/assets/2 (55).jpeg>)

**Precaución**

-   Todos los trabajos en el dispositivo, incluida la instalación y el mantenimiento, deben ser realizados por un electricista calificado y autorizado.
-   Para evitar descargas eléctricas y/o daños al equipo, desconecte la energía eléctrica en el fusible principal o en el disyuntor antes de la instalación y el mantenimiento.
-   No conecte el dispositivo a cargas que excedan la corriente de carga admitida.

![](<.gitbook/assets/3 (50).jpeg>)

**Instalación**

La especificación de cableado de los orificios de inserción es AWG 16-26 o Ø 1,31-0,129 (mm²).

Conecte el relé de acuerdo con las instrucciones a continuación o consulte el diagrama para obtener más información.

1.  Apague la fuente de alimentación antes de realizar la conexión.
2.  Conecte los terminales L y N de la fuente de alimentación a los terminales de Línea y Neutro de PRL respectivamente.
3.  Dependiendo del dispositivo que desee controlar a través del relé, seleccione el terminal NO o NC y conecte el relé con el dispositivo para establecer una conexión de apertura normal o cierre normal con el dispositivo.
4.  Después de completar el cableado, encienda la fuente de alimentación para encender el interruptor de palanca del relé.

_\\<IMPORTANT NOTE>_

-   El cableado del PRL solo debe realizarlo un técnico certificado con el conocimiento y la capacitación adecuados en equipos eléctricos.

**Configuración de red ZigBee**

-   _**Guía del dispositivo ZigBee**_

ZigBee es un protocolo de comunicación inalámbrica que es confiable, tiene bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir una gran cantidad de dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

-   _**Unirse a la red ZigBee**_

Como dispositivo ZigBee, el Relay necesita unirse a una red ZigBee para recibir comandos. Siga los pasos a continuación para unir el Relay a una red ZigBee.

-   1.  Conecte la entrada de alimentación al interruptor de palanca de relé de acuerdo con las instrucciones de instalación anteriores y encienda el interruptor de palanca de relé.
    2.  Mantenga presionado el botón de función durante 10 segundos mientras el relé se reinicia y comienza a buscar la red ZigBee existente. Asegúrese de que la función de permiso para unirse en el enrutador o coordinador de su red ZigBee esté habilitada.
    3.  Si el interruptor de palanca de relé se une con éxito a una red ZigBee, el indicador LED parpadeará dos veces para confirmar.
    4.  Después de unirse a la red ZigBee, el interruptor de palanca de retransmisión se registrará automáticamente en la red. Consulte con el coordinador de la red ZigBee, el panel de control del sistema o el CIE (equipo de control e indicación) para confirmar si la inscripción y el registro se realizaron correctamente.
    5.  Después de unirse a la red ZigBee, si el interruptor de palanca de relé pierde la conexión con la red ZigBee actual, el indicador LED parpadeará cada 20 minutos. Verifique la condición de su red ZigBee y el rango de señal del interruptor de palanca de relé para corregir la condición.
-   _**Eliminación del dispositivo de la red ZigBee (restablecimiento de fábrica)**_

Para eliminar el interruptor de palanca de relé de la red ZigBee actual, el dispositivo debe restablecerse a los valores de fábrica para completar la eliminación del dispositivo. La función de restablecimiento de fábrica borrará la configuración y la información almacenadas del dispositivo y le pedirá que busque una nueva red ZigBee.

2

**Antes de retirar el dispositivo, asegúrese de que el interruptor de palanca de relé esté dentro del rango de señal de red ZigBee actual.**

-   1.  Mantenga presionado el botón de función durante 10 segundos, luego suelte el botón para restablecer el interruptor de palanca del relé.
    2.  Al reiniciarse, el dispositivo borrará la configuración de red ZigBee actual y transmitirá la señal al coordinador de ZigBee para eliminarse de la red ZigBee actual. Luego buscará activamente nuevamente la red ZigBee disponible y se unirá a la red automáticamente.
-   _**Capacidad del dispositivo enrutador ZigBee (solo PRL-1ZBSR-AC)**_

El modelo Relay Toggle Switch con función Router permite que otros dispositivos ZigBee se unan a la Red ZigBee a través del Router. Tiene una capacidad máxima de 40 dispositivos/enrutadores.

**Operación**

-   _**Control de relé**_
    -   Después de que el interruptor de palanca del relé se haya unido exitosamente a una red ZigBee, el panel de control/coordinador puede controlar remotamente el relé para encenderlo, apagarlo o alternar entre la condición de encendido y apagado. Consulte a su coordinador/panel de control de ZigBee para obtener más detalles.

**Apéndice (solo para desarrolladores)**

-   _**ID del grupo de retransmisión**_

**ID del dispositivo: Activado Desactivado Salida: 0x0002**

**Punto final: 0x0A**

| **Lado del servidor**                                        |                   |                               |                   |            |              |            | **Lado del cliente** |           |                 |   |
| ------------------------------------------------------------ | ----------------- | ----------------------------- | ----------------- | ---------- | ------------ | ---------- | -------------------- | --------- | --------------- | - |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
|                                                              |                   |                               | **Obligatorio**   |            |              |            |                      |           |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
| Básico (0x0000)                                              |                   |                               |                   |            |              |            |                      | _Ninguno_ |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
| Identificar(0x0003)                                          |                   |                               |                   |            |              |            |                      |           |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
| Activado/Desactivado(0x0006)                                 |                   |                               |                   |            |              |            |                      |           |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
|                                                              |                   |                               | **Opcional**      |            |              |            |                      |           |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
| Grupos(0x0004)                                               |                   |                               |                   |            |              |            |                      | Ninguno   |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
| _**Atributo de información básica del clúster**_            |                   |                               |                   |            |              |            |                      |           |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
| **Identificador**                                            |                   | **Nombre**                    | **Tipo**          |            | **Rango**    | **Acceso** | **Por defecto**      |           | **Obligatorio** |   |
|                                                              |                   |                               | **/ Opcional**    |            |              |            |                      |           |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
| 0x0000                                                       |                   | _Versión ZCL_                 | 8 bits sin firmar |            | 0x00 –0xff   | Leer       | 0x01                 |           | METRO           |   |
|                                                              | entero            |                               | solo              |            |              |            |                      |           |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
| 0x0001                                                       |                   | Versión de la aplicación      | 8 bits sin firmar |            | 0x00 – 0xff  | Leer       | 0x00                 |           | oh              |   |
|                                                              | entero            |                               | solo              |            |              |            |                      |           |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
| 0x0003                                                       |                   | _Versión HW_                  | 8 bits sin firmar |            | 0x00 –0xff   | Leer       | 0                    |           | oh              |   |
|                                                              | entero            |                               | solo              |            |              |            |                      |           |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
| 0x0004                                                       |                   | _Nombre del Fabricante_       | Personaje         |            | 0 – 32 bytes | Leer       | Clímax               |           | oh              |   |
|                                                              | Cadena            |                               | solo              | Tecnología |              |            |                      |           |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
| 0x0005                                                       |                   | _Identificador de modelo_     | Personaje         |            | 0 – 32 bytes | Leer       | (Versión del modelo) |           | oh              |   |
|                                                              | Cadena            |                               | solo              |            |              |            |                      |           |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
| 0x0006                                                       |                   | _Código de fecha_             | Personaje         |            | 0 – 16 bytes | Leer       |                      |           | oh              |   |
|                                                              | Cadena            |                               | solo              |            |              |            |                      |           |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
| 0x0007                                                       |                   | _Fuente de alimentación_      | 8 bits            |            | 0x00 –0xff   | Leer       |                      |           | METRO           |   |
|                                                              |                   | solo                          |                   |            |              |            |                      |           |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
| 0x0010                                                       |                   | _Descripción de la ubicación_ | Personaje         |            | 0 – 32 bytes | Leer /     |                      |           | oh              |   |
|                                                              | Cadena            |                               | Escribir          |            |              |            |                      |           |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
| 0x0011                                                       |                   | _Entorno físico_              | 8 bits            |            | 0x00 –0xff   | Leer /     | 0x00                 |           | oh              |   |
|                                                              |                   | Escribir                      |                   |            |              |            |                      |           |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
| 0x0012                                                       |                   | _Dispositivo habilitado_      | Booleano          |            | 0x00 –0x01   | Leer /     | 0x01                 |           | METRO           |   |
|                                                              |                   | Escribir                      |                   |            |              |            |                      |           |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
| _**Atributo de información de identificación del clúster**_ |                   |                               |                   |            |              |            |                      |           |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
| **Identificador**                                            |                   | **Nombre**                    | **Tipo**          |            | **Rango**    | **Acceso** | **Por defecto**      |           | **Obligatorio** |   |
|                                                              |                   |                               | **/ Opcional**    |            |              |            |                      |           |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |
| 0x0000                                                       |                   | _IdentificarTiempo_           | No firmado        |            | 0x00 –0xffff | Leer /     | 0x0000               |           | METRO           |   |
|                                                              | entero de 16 bits |                               | Escribir          |            |              |            |                      |           |                 |   |
|                                                              |                   |                               |                   |            |              |            |                      |           |                 |   |

3

-   _**Atributo de información del clúster activado/desactivado**_

| **Identificador** | **Nombre**          | **Tipo** | **Rango**  | **Acceso** | **Por defecto** | **Obligatorio** |   |
| ----------------- | ------------------- | -------- | ---------- | ---------- | --------------- | --------------- | - |
| **/ Opcional**    |                     |          |            |            |                 |                 |   |
|                   |                     |          |            |            |                 |                 |   |
| 0x0000            | _Encendido apagado_ | Booleano | 0x00 –0x01 | Leer       | 0x00            | METRO           |   |
| solo              |                     |          |            |            |                 |                 |   |
|                   |                     |          |            |            |                 |                 |   |

_**Atributos de la información del clúster Grupos**_

| **Identificador** | **Nombre**      | **Tipo**               | **Rango** | **Acceso** | **Por defecto** | **Obligatorio** |   |
| ----------------- | --------------- | ---------------------- | --------- | ---------- | --------------- | --------------- | - |
| **/ Opcional**    |                 |                        |           |            |                 |                 |   |
|                   |                 |                        |           |            |                 |                 |   |
| 0x0000            | _NombreSoporte_ | mapa de bits de 8 bits | x0000000  | Leer       | -               | METRO           |   |
| solo              |                 |                        |           |            |                 |                 |   |
|                   |                 |                        |           |            |                 |                 |   |

4
