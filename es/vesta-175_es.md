# VESTA 175

**PRS5-ZBS(R)/PRM5-ZBS(R)**

**Serie de interruptores de relé de potencia**

**Introducción**

La serie de interruptores de relé de potencia incluye los siguientes modelos:

**PRS5-ZBS:**Interruptor de alimentación de relé ZigBee

**PRS5-ZBSR:**Interruptor de alimentación de relé ZigBee con función de enrutador

**prm5-zbus:**Interruptor de alimentación de relé ZigBee con medidor

**prm5-jabsr:**Interruptor de alimentación de relé ZigBee con función de medidor y enrutador

Los interruptores de alimentación son capaces de recibir señales inalámbricas del coordinador en la red Zigbee para activar/desactivar los aparatos conectados a él.

El interruptor de relé de potencia utiliza tecnología ZigBee para la transmisión de señales inalámbricas. ZigBee es un protocolo de comunicación inalámbrica confiable, de bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir una gran cantidad de dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

Los modelos con funciones de medidor tienen la característica adicional de realizar un seguimiento del consumo de energía con el medidor de energía incorporado y transmitir los datos al coordinador regularmente.

Los modelos con función de enrutador también sirven como enrutador en la red ZigBee. Después de ser incluido en la red ZigBee, permite que otros dispositivos ZigBee se unan a la red a través del interruptor de encendido.

Los modelos con función OTA admiten la función de actualización de firmware OTA a través de la red ZigBee, que se puede iniciar desde el coordinador de red ZigBee.

![](<.gitbook/assets/0 (66).jpeg>)

| **Model No.**       | **Metro** | **Enrutador ZigBee** | **ORDEN** |
| ------------------- | --------- | -------------------- | --------- |
|                     |           |                      |           |
| **PRS5-ZBS**        | **No**    | **No**               | **No**    |
|                     |           |                      |           |
| **ístmico**         | **No**    | **No**               | **Sí**    |
|                     |           |                      |           |
| **PRS5-ZBSR**       | **No**    | **Sí**               | **No**    |
|                     |           |                      |           |
| **ístmico**         | **No**    | **Sí**               | **Sí**    |
|                     |           |                      |           |
| **prm5-zbus**       | **Sí**    | **No**               | **No**    |
|                     |           |                      |           |
| **prm5-zabus-ata**  | **Sí**    | **No**               | **Sí**    |
|                     |           |                      |           |
| **prm5-jabsr**      | **Sí**    | **Sí**               | **No**    |
|                     |           |                      |           |
| **Prm5-Jabsr-Aata** | **Sí**    | **Sí**               | **Sí**    |
|                     |           |                      |           |

**Identificación de piezas**

**1. Indicador LED**

El indicador LED se utiliza para indicar el estado del interruptor del relé de alimentación:

-   -   En:

El interruptor del relé de alimentación está encendido.

-   -   Apagado:

El interruptor del relé de alimentación está apagado.

-   -   Parpadea dos veces:

El Power Relay Switch se ha unido con éxito a una red ZigBee.

-   -   Parpadea 5 veces

El interruptor de relé de alimentación se ha vinculado correctamente con un controlador

-   -   Parpadea cada 20 minutos

El Power Relay Switch ha perdido la conexión a su red ZigBee actual

1.  **Botón de función**

**Uso del botón de función:**

-   -   Presione el botón para activar/desactivar el interruptor del relé de alimentación
    -   Mantenga presionado el botón durante 10 segundos y luego suéltelo para restablecer el interruptor del relé de alimentación.
    -   Mantenga presionado el botón durante 3 segundos y luego suéltelo para vincularlo con un controlador

1.  **Cable de conexión del interruptor externo 1**

1

1.  **Cable de conexión del interruptor externo 2**
2.  **Salida de carga de alimentación de línea de CA**
3.  **Entrada de energía neuronal de CA/Salida de carga de energía neutra de CA**
4.  **Entrada de alimentación de línea de CA**

**Configuración de red ZigBee**

-   _**Guía del dispositivo ZigBee**_

ZigBee es un protocolo de comunicación inalámbrica confiable, de bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir una gran cantidad de dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

Debido a la estructura fundamental de la red ZigBee, el dispositivo ZigBee buscará y se unirá activamente a la red después de encenderse.

-   _**Unirse a la red ZigBee**_

Como dispositivo ZigBee, el Power Relay Switch necesita unirse a una red ZigBee para recibir comandos y transmitir información sobre el consumo de energía. Siga los pasos a continuación para unir el interruptor de relé de potencia a una red ZigBee.

-   1.  Conecte el interruptor del relé de alimentación al cable de alimentación.
    2.  Mantenga presionado el botón Función durante 10 segundos, luego suéltelo para unirse a la red. Asegúrese de que la función de permiso para unirse en el enrutador o coordinador de su red ZigBee esté habilitada.
    3.  Si el interruptor de relé de alimentación se une con éxito a una red ZigBee, el indicador LED parpadeará dos veces para confirmar.
    4.  Después de unirse a la red ZigBee, el Power Relay Switch se registrará en la red automáticamente. Consulte con el coordinador de la red Zigbee, el panel de control del sistema o el CIE (equipo de control e indicación) para confirmar si la inscripción y el registro se realizaron correctamente.
    5.  Si el registro y la conexión a la red no tienen éxito, verifique su coordinador de red ZigBee, el panel de control del sistema o la configuración CIE para asegurarse de que la función de permiso para unirse esté disponible y luego use la función de restablecimiento de fábrica a continuación para unirse a la red ZigBee.
-   _**Vinculación con el controlador**_

Después de unirse a la red ZigBee, el Power Relay Switch puede vincularse con un dispositivo controlador que se puede utilizar para ajustar el nivel de salida de potencia del Power Relay Switch. Para vincular el interruptor de relé de alimentación y el dispositivo:

-   1.  Mantenga presionado el botón de función durante 3 segundos y luego suelte el botón. El interruptor de relé de potencia enviará una solicitud vinculante al coordinador.
    2.  Consulte el manual de su controlador para enviar una solicitud vinculante para el dispositivo en un plazo de 16 segundos.
    3.  Si la vinculación se realiza correctamente, el indicador LED del interruptor del relé de alimentación parpadeará 5 veces para confirmar. Ahora puede usar el controlador para ajustar el nivel de salida de energía para el interruptor de relé de alimentación.
    4.  Si la vinculación no tiene éxito, vuelva a intentar el proceso de vinculación.
-   _**Eliminación del dispositivo de la red ZigBee (restablecimiento de fábrica)**_

Para eliminar el interruptor de encendido de la red ZigBee actual, se debe poner el interruptor de encendido en restablecimiento de fábrica para completar la eliminación del dispositivo. La función de restablecimiento de fábrica borrará el interruptor de encendido de su configuración e información almacenadas y le solicitará al interruptor de encendido que busque una nueva red ZigBee.

**Antes de retirar el dispositivo, asegúrese de que el interruptor de encendido esté dentro del rango de señal de red ZigBee actual.**

-   1.  Mantenga presionado el botón de función durante 10 segundos, luego suelte el botón para restablecer el interruptor de encendido.
    2.  Al reiniciarse, el interruptor de encendido borrará la configuración actual de la red ZigBee y transmitirá la señal al coordinador ZigBee para eliminarse de la red ZigBee actual. Luego buscará activamente nuevamente la red ZigBee disponible y se unirá a la red automáticamente.
-   _**Capacidad del dispositivo enrutador ZigBee (solo PRS5-ZBSR/PRM5-ZBSR)**_

Los modelos Power Switch con función Router permiten que otros dispositivos ZigBee se unan a la Red ZigBee a través del Router. El Power Switch Router tiene una capacidad máxima de 40 dispositivos, incluidos 10 enrutadores; El enrutador Power Switch Meter tiene una capacidad máxima de 10 dispositivos, incluidos 5 enrutadores.

| **Model No.**                 | **Dispositivo ZigBee máximo** | **ZigBee máximo** |   |
| ----------------------------- | ----------------------------- | ----------------- | - |
| **+ Capacidad del enrutador** | **Capacidad del enrutador**   |                   |   |
|                               |                               |                   |   |
|                               |                               |                   |   |
| **PRS5-ZBSR**                 | **40**                        | **10**            |   |
|                               |                               |                   |   |
| **prm5-jabsr**                | **10**                        | **5**             |   |
|                               |                               |                   |   |

-   _**Actualización de firmware OTA (solo para la versión OTA)**_

El interruptor de relé de potencia admite la función de actualización de firmware OTA a través de la red ZigBee, que se puede iniciar desde el coordinador de red ZigBee. Siga los pasos a continuación para realizar la actualización del firmware OTA.

2

**Paso 1.**Debe acceder a su Coordinador ZigBee para realizar la actualización del firmware en el aire.**Paso 2.**En la página web de configuración, seleccione el dispositivo que desea actualizar y seleccione el nuevo

Se proporciona firmware ZigBee. Consulte el Manual del usuario del Coordinador ZigBee para obtener más detalles.

**Paso 3.**Presione "OK" para iniciar el proceso de actualización y el LED seguirá parpadeando. Durante el proceso de la OTA,

no realice ninguna otra acción ni apague el panel.

**Etapa 4.**La duración de una actualización tardará aproximadamente entre 20 y 30 minutos. Tenga en cuenta que la duración puede variar según el tamaño del archivo o la distancia entre su accesorio y el coordinador.

**Paso 5.**Espere a que el firmware complete la actualización. Cuando el progreso alcance el 100%, el dispositivo se reiniciará automáticamente. También puede actualizar la página web nuevamente para asegurarse de que el firmware del dispositivo se actualice correctamente y se muestre la versión más reciente.

**Precaución**

-   Todos los trabajos en el dispositivo, incluida la instalación y el mantenimiento, deben ser realizados por un electricista calificado y autorizado.
-   Antes de la instalación o cualquier trabajo de mantenimiento, asegúrese de que la fuente de alimentación esté desconectada.
-   No conecte el dispositivo a cargas que excedan la corriente de carga admitida.

**Instalación**

-   _**Cableado con conector de empalme**_
    -   El interruptor de relé de alimentación viene con un cable integrado para conectarlo a una fuente de alimentación de CA, un electrodoméstico y un interruptor externo. Se proporcionan cinco conectores de empalme Wago 221 para la conexión.
    -   Los conectores de 2 y 3 hilos admiten cables sólidos y trenzados de 0,2 a 4 mm² (24–12 AWG).
    -   Antes de realizar el cableado, asegúrese de que la alimentación esté apagada. Para conectar los cables:
        1.  Levante la palanca e inserte el cable marrón.**(Imagen 1, 2)**

![](<.gitbook/assets/1 (55).png>)

**Foto 1****Imagen 2**

1.  Empuje la palanca hacia abajo. La carcasa transparente le permite comprobar si el cable está conectado correctamente. Asegúrese de que el cable esté sujeto firmemente en su lugar y no se salga.**(Imagen 3, 4)**

![](<.gitbook/assets/2 (60).png>)

|                                                          | **Imagen 3**                       | **Imagen 4** |   |
| -------------------------------------------------------- | ---------------------------------- | ------------ | - |
| 3) De la misma manera que en los pasos 1 y 2, inserte en | otro polo el cable para conectar a |              |   |
| Entrada de alimentación de línea de CA.**(Imagen 5)**    |                                    |              |   |
|                                                          |                                    |              |   |
|                                                          |                                    |              |   |

![](<.gitbook/assets/3 (48).jpeg>)

**Imagen 5**

3

1.  Repita los pasos 1, 2 y 3 para conectar los otros cables con conectores.

Tenga en cuenta que el cable azul debe conectarse a un conector de 3 cables y luego conectarse a la entrada de energía neuronal de CA y a la salida de carga de energía neutra de CA.**(Imagen 6)**

![](<.gitbook/assets/4 (61).png>)

**Imagen 6**

**Operación**

-   _**Diagrama de conexión de cables**_
    -   Consulte el diagrama para conectar la iluminación de su hogar al interruptor de relé de alimentación.
-   _**Instalación**_
    -   Conecte el interruptor del relé de alimentación al cable de alimentación.
    -   Conecte el interruptor de relé de alimentación a la iluminación de su hogar. La iluminación debe estar en estado ON.
    -   Puede conectar un interruptor externo al interruptor del relé de alimentación según el diagrama para encender/apagar el interruptor del relé de alimentación.
    -   _**NOTA IMPORTANTE**_**:**El interruptor de relé de alimentación no tiene una batería de respaldo y se apagará cuando falle la alimentación de CA.**NO**utilice el interruptor de relé de alimentación como enrutador para su sensor de seguridad o dispositivos de control de alarma, como contacto de puerta, sensor PIR, etc.; de lo contrario, los sensores perderán la conexión a la red ZigBee si el interruptor de relé de alimentación se desconecta de la alimentación de CA. Planifique las ubicaciones de instalación de estos sensores de seguridad sin utilizar el interruptor de relé de alimentación y utilice únicamente un enrutador con batería de respaldo para ellos. La función de enrutador del interruptor de encendido debe**SOLO**Se puede utilizar para proporcionar una extensión del rango de señal para otros interruptores/atenuadores de alimentación.
-   _**Control de electrodomésticos**_
    -   Después de que el interruptor de relé de alimentación se haya unido con éxito a una red ZigBee, el coordinador puede encender/apagar el dispositivo de forma remota.
    -   También puede presionar el botón en el interruptor del relé de alimentación para encender/apagar la luz.
    -   Puede encender/apagar el interruptor del relé de alimentación con un interruptor externo.
    -   Si ha vinculado un controlador con el interruptor de relé de alimentación, también puede utilizar el controlador para encender/apagar el interruptor de relé de alimentación.
    -   Si la entrada de alimentación de CA se desconecta del interruptor del relé de alimentación, su estado anterior de encendido/apagado se restaurará dentro de 1 minuto después de volver a conectar la entrada de alimentación de CA al interruptor del relé de alimentación.
-   _**Monitor de consumo de energía (solo PRM5-ZBS/PRM5-ZBSR)**_
    -   El Power Relay Switch transmitirá una señal con sus datos de consumo de energía cada dos minutos al coordinador de red ZigBee.
    -   Siempre que la salida de energía del interruptor de alimentación cambie en +/- 2 W, transmitirá automáticamente una señal con datos de consumo de energía al coordinador de red ZigBee para su actualización.
    -   El interruptor de encendido transmite una señal con datos de energía al coordinador cada vez que el uso de energía acumulada aumenta en 0,1 kW/h.
    -   El medidor tiene una precisión de +/- 5%.
    -   Para borrar los datos de consumo de energía acumulado del interruptor de encendido, siga los pasos a continuación:
        1.  Desconecte el interruptor del relé de alimentación del tomacorriente.
        2.  Mantenga presionado el botón de función y vuelva a conectar la alimentación mientras mantiene presionado el botón.
        3.  Continúe presionando el botón y suéltelo después de 3 segundos. Se borrarán los datos de consumo de energía acumulado.

![](<.gitbook/assets/5 (30).jpeg>)

4

-   _**Carga máxima de operación**_
    -   Para 110V: la carga máxima de operación es 1100W y 10A.
    -   Para 230V: la carga máxima de funcionamiento es de 2300W y 10A.
    -   Si el interruptor del relé de alimentación se sobrecalienta, cortará la energía automáticamente como medida de seguridad. El usuario debe desconectar y volver a conectar la alimentación de CA al interruptor de relé de alimentación después del corte para reanudar el funcionamiento normal.

**Apéndice (solo para desarrolladores)**

_**Interruptor de relé de alimentación con ID de grupo de medidores**_

**ID del dispositivo: Toma de corriente: 0x0009**

**Punto final: 0x01**

| **Lado del servidor**                       |                 | **Lado del cliente** |
| ------------------------------------------- | --------------- | -------------------- |
|                                             |                 |                      |
|                                             | **Obligatorio** |                      |
|                                             |                 |                      |
| Básico (0x0000)                             |                 | _Ninguno_            |
|                                             |                 |                      |
| Identificar(0x0003)                         |                 |                      |
|                                             |                 |                      |
| Grupos(0x0004)                              |                 |                      |
|                                             |                 |                      |
| Escenas (0x0005)                            |                 |                      |
|                                             |                 |                      |
| Activado/Desactivado(0x0006)                |                 |                      |
|                                             |                 |                      |
|                                             | **Opcional**    |                      |
|                                             |                 |                      |
| Medición (0x0705) (solo PRM5-ZBS/PRM5-ZBSR) |                 | Ninguno              |
|                                             |                 |                      |

_**Atributo de información básica del clúster**_

| **Identificador**                                            | **Nombre**                    |                      | **Tipo**               |            |               | **Rango**      |                 |               | **Acceso**    |         | **Por defecto** | **Obligatorio** |                 |                 |   |   |
| ------------------------------------------------------------ | ----------------------------- | -------------------- | ---------------------- | ---------- | ------------- | -------------- | --------------- | ------------- | ------------- | ------- | --------------- | --------------- | --------------- | --------------- | - | - |
|                                                              |                               |                      |                        |            |               | **/ Opcional** |                 |               |               |         |                 |                 |                 |                 |   |   |
|                                                              |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
| 0x0000                                                       | _Versión ZCL_                 | 8 bits sin firmar    |                        |            | 0x00 –0xff    |                |                 | Solo lectura  |               | 0x01    | METRO           |                 |                 |                 |   |   |
|                                                              | entero                        |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
|                                                              |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
| 0x0001                                                       | Versión de la aplicación      | 8 bits sin firmar    |                        |            | 0x00 – 0xff   |                |                 | Solo lectura  |               | 0x00    | oh              |                 |                 |                 |   |   |
|                                                              | entero                        |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
|                                                              |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
| 0x0003                                                       | _Versión HW_                  | 8 bits sin firmar    |                        |            | 0x00 –0xff    |                |                 | Solo lectura  | 0             | oh      |                 |                 |                 |                 |   |   |
|                                                              | entero                        |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
|                                                              |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
| 0x0004                                                       | _Nombre del Fabricante_       | Cadena de caracteres |                        |            | 0 – 32 bytes  |                |                 | Solo lectura  |               | Clímax  | oh              |                 |                 |                 |   |   |
|                                                              |                               |                      |                        |            | Tecnología    |                |                 |               |               |         |                 |                 |                 |                 |   |   |
|                                                              |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
| 0x0005                                                       | _Identificador de modelo_     | Cadena de caracteres |                        |            | 0 – 32 bytes  |                |                 | Solo lectura  |               | (Modelo | oh              |                 |                 |                 |   |   |
|                                                              |                               |                      |                        |            | Versión)      |                |                 |               |               |         |                 |                 |                 |                 |   |   |
|                                                              |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
| 0x0006                                                       | _Código de fecha_             | Cadena de caracteres |                        |            | 0 – 16 bytes  |                |                 | Solo lectura  |               |         | oh              |                 |                 |                 |   |   |
|                                                              |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
| 0x0007                                                       | _Fuente de alimentación_      |                      | 8 bits                 |            |               | 0x00 –0xff     |                 |               | Solo lectura  |         |                 | METRO           |                 |                 |   |   |
| 0x0010                                                       | _Descripción de la ubicación_ | Cadena de caracteres |                        |            | 0 – 32 bytes  |                |                 | Leer escribir |               |         | oh              |                 |                 |                 |   |   |
| 0x0011                                                       | _Entorno físico_              |                      | 8 bits                 |            |               | 0x00 –0xff     |                 |               | Leer escribir |         | 0x00            | oh              |                 |                 |   |   |
| 0x0012                                                       | _Dispositivo habilitado_      |                      | Booleano               |            |               | 0x00 –0x01     |                 |               | Leer escribir |         | 0x01            | oh              |                 |                 |   |   |
| 0xFFFD                                                       | _Revisión del clúster_        |                      | uint16                 |            | 0x0001-0xFFFE |                |                 | Solo lectura  | 1             | METRO   |                 |                 |                 |                 |   |   |
| _**Atributo de información de identificación del clúster**_ |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
|                                                              |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
| **Identificador**                                            | **Nombre**                    |                      |                        | **Tipo**   |               |                | **Rango**       | **Acceso**    |               |         | **Por defecto** | **Obligatorio** |                 |                 |   |   |
|                                                              |                               |                      |                        |            |               | **/ Opcional** |                 |               |               |         |                 |                 |                 |                 |   |   |
|                                                              |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
| 0x0000                                                       | _IdentificarTiempo_           |                      | 16 bits sin firmar     |            |               | 0x00 –0xffff   | Leer escribir   |               | 0x0000        | METRO   |                 |                 |                 |                 |   |   |
|                                                              |                               | entero               |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
|                                                              |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
| 0xFFFD                                                       | _Revisión del clúster_        |                      |                        | uint16     |               |                | 0x0001-0xFFFE   | Solo lectura  |               | 1       | METRO           |                 |                 |                 |   |   |
| _**Atributos de la información del clúster Grupos**_        |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
|                                                              |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
| **Identificador**                                            | **Nombre**                    |                      | **Tipo**               |            |               | **Rango**      |                 | **Acceso**    |               |         |                 | **Por defecto** | **Obligatorio** |                 |   |   |
|                                                              |                               |                      |                        |            |               | **/ Opcional** |                 |               |               |         |                 |                 |                 |                 |   |   |
|                                                              |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
| 0x0000                                                       | _NombreSoporte_               |                      | mapa de bits de 8 bits |            |               | x0000000       |                 | Solo lectura  |               | -       | METRO           |                 |                 |                 |   |   |
| 0xFFFD                                                       | _Revisión del clúster_        |                      | uint16                 |            |               | 0x0001-0xFFFE  |                 | Leer          |               | 1       | METRO           |                 |                 |                 |   |   |
|                                                              |                               |                      |                        | solo       |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
|                                                              |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
| _**Atributos del grupo de escenas Información**_            |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
|                                                              |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
| **Identificador**                                            | **Nombre**                    |                      |                        | **Tipo**   |               |                | **Rango**       |               | **Acceso**    |         |                 |                 | **Por defecto** | **Obligatorio** |   |   |
|                                                              |                               |                      |                        |            |               |                | **/ Opcional**  |               |               |         |                 |                 |                 |                 |   |   |
|                                                              |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
| 0x0000                                                       | _NombreSoporte_               |                      | mapa de bits de 8 bits |            |               | x0000000       |                 | Solo lectura  |               |         | 0x00            | METRO           |                 |                 |   |   |
| 0x0001                                                       | _Escena actual_               |                      | 8 bits sin firmar      |            |               | 0x00 – 0xff    |                 | Solo lectura  |               |         |                 | 0x00            | METRO           |                 |   |   |
|                                                              |                               | entero               |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
|                                                              |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
| 0x0002                                                       | _Grupo actual_                |                      |                        | No firmado |               |                | 0x0000 – 0xfff7 |               | Solo lectura  |         |                 |                 | 0x00            | METRO           |   |   |
|                                                              | entero de 16 bits             |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
|                                                              |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |
| 0x0003                                                       | _Escena válida_               |                      |                        | Booleano   |               |                | 0x00 – 0x01     |               | Solo lectura  |         |                 | 0x00            | METRO           |                 |   |   |
| 0x0004                                                       | _NombreSoporte_               |                      | mapa de bits de 8 bits |            |               | x0000000       |                 | Solo lectura  |               | -       | METRO           |                 |                 |                 |   |   |
| 0xFFFD                                                       | _Revisión del clúster_        |                      |                        | uint16     |               |                | 0x0001-0xFFFE   |               | Leer          |         | 1               | METRO           |                 |                 |   |   |
|                                                              |                               |                      |                        |            | solo          |                |                 |               |               |         |                 |                 |                 |                 |   |   |
|                                                              |                               |                      |                        |            |               |                |                 |               |               |         |                 |                 |                 |                 |   |   |

5

-   _**Atributo de información del clúster activado/desactivado**_

| **Identificador** | **Nombre**             | **Tipo** | **Rango**     | **Acceso**   | **Por defecto** | **Obligatorio** |   |
| ----------------- | ---------------------- | -------- | ------------- | ------------ | --------------- | --------------- | - |
| **/ Opcional**    |                        |          |               |              |                 |                 |   |
|                   |                        |          |               |              |                 |                 |   |
| 0x0000            | _Encendido apagado_    | Booleano | 0x00 –0x01    | Solo lectura | 0x00            | METRO           |   |
| 0xFFFD            | _Revisión del clúster_ | uint16   | 0x0001-0xFFFE | Leer         | 1               | METRO           |   |
| solo              |                        |          |               |              |                 |                 |   |
|                   |                        |          |               |              |                 |                 |   |

_**Atributos de la información del grupo de medición (conjunto de atributos de información de lectura)**_

| **Identificador** | **Nombre**     | **Tipo**           | **Rango**      |   | **Acceso**   | **Por defecto** | **Obligatorio** |   |
| ----------------- | -------------- | ------------------ | -------------- | - | ------------ | --------------- | --------------- | - |
|                   | **t**          | **/ Opcional**     |                |   |              |                 |                 |   |
|                   |                |                    |                |   |              |                 |                 |   |
| 0x00              | Resumen actual | 48 bits sin firmar | 0x000000000000 | a | Solo lectura |                 | METRO           |   |
| Entregado         | Entero         | 0xFFFFFFFFFFFF     |                |   |              |                 |                 |   |
|                   |                |                    |                |   |              |                 |                 |   |

_**Atributos de la información del clúster de medición (conjunto de atributos de formato)**_

| **Identificador** | **Nombre**                      | **Tipo**               | **Rango**   | **Acceso**   | **Por defecto** | **Obligatorio** |   |
| ----------------- | ------------------------------- | ---------------------- | ----------- | ------------ | --------------- | --------------- | - |
| **/ Opcional**    |                                 |                        |             |              |                 |                 |   |
|                   |                                 |                        |             |              |                 |                 |   |
| 0x00              | Unidad de medida                | Enumeración de 8 bits  | 0x00 a 0xFF | Solo lectura | 0x00            | METRO           |   |
| 0x01              | Multiplicador                   | 24 bits sin firmar     | 0x000000 a  | Solo lectura | 1               | oh              |   |
| Entero            | 0xFFFFFF                        |                        |             |              |                 |                 |   |
|                   |                                 |                        |             |              |                 |                 |   |
| 0x02              | Divisor                         | 24 bits sin firmar     | 0x000000 a  | Solo lectura | 10000           | oh              |   |
| Entero            | 0xFFFFFF                        |                        |             |              |                 |                 |   |
|                   |                                 |                        |             |              |                 |                 |   |
| 0x03              | SumaFormato                     | Mapa de bits de 8 bits | 0x00 a 0xFF | Solo lectura | 0xF9            | METRO           |   |
| 0x04              | Formato de demanda              | Mapa de bits de 8 bits | 0x00 a 0xFF | Solo lectura | 0Ksasa          | oh              |   |
| 0x06              | Tipo de dispositivo de medición | Mapa de bits de 8 bits | 0x00 a 0xFF | Solo lectura | 0x00            | METRO           |   |

_**Atributos de la información del grupo de medición (conjunto de atributos históricos)**_

| **Identificador** | **Nombre**             | **Tipo**           | **Rango**    | **Acceso**   | **Por defecto** | **Obligatorio** |   |
| ----------------- | ---------------------- | ------------------ | ------------ | ------------ | --------------- | --------------- | - |
| **/ Opcional**    |                        |                    |              |              |                 |                 |   |
|                   |                        |                    |              |              |                 |                 |   |
| 0x00              | Demanda Instantánea    | Firmado de 24 bits | -8.388.607 a | Solo lectura | 0x00            | oh              |   |
| Entero            | 8,388,607              |                    |              |              |                 |                 |   |
|                   |                        |                    |              |              |                 |                 |   |
| 0xFFFD            | _Revisión del clúster_ | uint16             | 0x0001-0xFFF | Leer         | 1               | METRO           |   |
| Y                 | solo                   |                    |              |              |                 |                 |   |
|                   |                        |                    |              |              |                 |                 |   |

6
