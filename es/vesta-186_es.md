# VESTA 186

**Serie de interruptores de alimentación PSS-29ZBS(R) / PSM-29ZBS(R)**

**Introducción**

La serie Power Switch incluye los siguientes modelos:

**PSS-29ZBS:**Interruptor de encendido ZigBee

**PSS-29ZBSR:**Interruptor de alimentación ZigBee con función de enrutador

**PSM-29ZBS:**Interruptor de encendido ZigBee con medidor

**PSM-29ZBSR:**Interruptor de alimentación ZigBee con función de medidor y enrutador

Los interruptores de alimentación son capaces de recibir señales inalámbricas del coordinador en la red ZigBee para activar o desactivar los aparatos conectados a él.

El interruptor de encendido utiliza tecnología ZigBee para la transmisión de señales inalámbricas. ZigBee es un protocolo de comunicación inalámbrica que es confiable, tiene bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir una gran cantidad de dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

Los modelos con funciones de medidor (PSM-29ZBS / PSM-29ZBSR) tienen la característica adicional de realizar un seguimiento del consumo de energía con el medidor de energía incorporado y transmitir los datos al coordinador regularmente.

Los modelos con función de enrutador (PSS-29ZBSR / PSM-29ZBSR) también sirven como enrutador en la red ZigBee. Después de ser incluido en la red ZigBee, permite que otros dispositivos ZigBee se unan a la red a través del interruptor de encendido.

| **Model No.**  | **Metro** | **Enrutador ZigBee** |
| -------------- | --------- | -------------------- |
|                |           |                      |
| **PSS-29ZBS**  | **No**    | **No**               |
|                |           |                      |
| **PSS-29ZBSR** | **No**    | **Sí**               |
|                |           |                      |
| **PSM-29ZBS**  | **Sí**    | **No**               |
|                |           |                      |
| **PSM-29ZBSR** | **Sí**    | **Sí**               |
|                |           |                      |

**Identificación de piezas**

**1. Botón de función, también conocido como indicador LED**

El botón de función también funciona como indicador LED. El botón de función se utiliza para controlar el interruptor de encendido. El indicador LED se utiliza para indicar el estado del interruptor de encendido.

**Indicación LED:**

El indicador LED se enciende en las siguientes condiciones:

-   En:

El interruptor de encendido está encendido.

-   Apagado:

El interruptor de encendido está apagado.

-   Parpadea dos veces:

El interruptor de alimentación se ha unido con éxito a una red ZigBee.

-   Parpadea 5 veces

El interruptor de encendido se ha vinculado exitosamente con un controlador.

-   Parpadea cada 20 minutos

El interruptor de encendido ha perdido la conexión a su red ZigBee actual

(**Sólo PSS-29ZBS y PSM-29ZBS**)

**Uso del botón de función:**

-   Presione el botón para activar/desactivar el interruptor de encendido
-   Mantenga presionado el botón durante 10 segundos y luego suéltelo para restablecer el interruptor de encendido.
-   Mantenga presionado el botón durante 3 segundos y luego suéltelo para vincularlo con un controlador.

_**Tipo F**__**Tipo B**_

![](<.gitbook/assets/0 (74).jpeg>)

_**Tipo L**__**Tipo J**_

1

**Configuración de red ZigBee**

![](<.gitbook/assets/1 (66).jpeg>)

-   _**Guía del dispositivo ZigBee**_

ZigBee es un protocolo de comunicación inalámbrica que es confiable, tiene bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir una gran cantidad de dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

![](<.gitbook/assets/2 (59).jpeg>)

-   _**Unirse a la red ZigBee**_

Como dispositivo ZigBee, el Power Switch necesita unirse a una red ZigBee para recibir comandos y transmitir información sobre el consumo de energía. Siga los pasos a continuación para unir el interruptor de encendido a una red ZigBee.

-   1.  Conecte el interruptor de encendido a una toma de corriente.
    2.  Mantenga presionado el botón de función durante 10 segundos mientras el interruptor de encendido se reinicia y comienza a buscar la red ZigBee existente. Asegúrese de que la función de permiso para unirse en el enrutador o coordinador de su red ZigBee esté habilitada.
    3.  Si el interruptor de encendido se une exitosamente a una red ZigBee, el indicador LED parpadeará dos veces para confirmar.
    4.  Después de unirse a la red ZigBee, el interruptor de encendido se registrará en la red automáticamente. Consulte con el coordinador de la red ZigBee, el panel de control del sistema o el CIE (equipo de control e indicación) para confirmar si la inscripción y el registro se realizaron correctamente.
    5.  Si el registro y la conexión a la red no tienen éxito, verifique su coordinador de red ZigBee, el panel de control del sistema o la configuración CIE para asegurarse de que la función de permiso para unirse esté disponible y luego use la función de restablecimiento de fábrica a continuación para unirse a la red ZigBee.
-   _**Vinculación con el controlador**_

![](<.gitbook/assets/3 (53).jpeg>)

Después de unirse a la red ZigBee, el interruptor de encendido puede vincularse con un dispositivo controlador que puede usarse para encender/apagar el interruptor de encendido. Para vincular el interruptor de encendido y el dispositivo:

-   1.  Mantenga presionado el botón de función durante 3 segundos y luego suelte el botón. El Power Switch enviará una solicitud vinculante al coordinador.
    2.  Consulte el manual de su controlador para enviar una solicitud vinculante para el dispositivo en un plazo de 16 segundos.
    3.  Si la vinculación se realiza correctamente, el indicador LED del interruptor de encendido parpadeará 5 veces para confirmar. Ahora puede usar el controlador para ajustar el nivel de salida de energía del interruptor de encendido.
    4.  Si la vinculación no tiene éxito, vuelva a intentar el proceso de vinculación.
-   _**Eliminación del dispositivo de la red ZigBee (restablecimiento de fábrica)**_

![](<.gitbook/assets/4 (62).png>)

Para eliminar el interruptor de encendido de la red ZigBee actual, se debe poner el interruptor de encendido en restablecimiento de fábrica para completar la eliminación del dispositivo. La función de restablecimiento de fábrica borrará el interruptor de encendido de su configuración e información almacenadas y le solicitará al interruptor de encendido que busque una nueva red ZigBee.

**Antes de retirar el dispositivo, asegúrese de que el interruptor de encendido esté dentro del rango de señal de red ZigBee actual.**

-   1.  Mantenga presionado el botón de función durante 10 segundos, luego suelte el botón para restablecer el interruptor de encendido.
    2.  Al reiniciarse, el interruptor de encendido borrará la configuración actual de la red ZigBee y transmitirá la señal al coordinador ZigBee para eliminarse de la red ZigBee actual. Luego buscará activamente nuevamente la red ZigBee disponible y se unirá a la red automáticamente.
-   _**Capacidad del dispositivo enrutador ZigBee (solo PSS-29ZBSR / PSM-29ZBSR)**_

![](<.gitbook/assets/5 (62).png>)

Los modelos Power Switch con función Router permiten que otros dispositivos ZigBee se unan a la Red ZigBee a través del Router. El Power Switch Router tiene una capacidad máxima de 40 dispositivos, incluidos 10 enrutadores; El enrutador Power Switch Meter tiene una capacidad máxima de 10 dispositivos, incluidos 5 enrutadores.

| **Model No.**                 | **Dispositivo ZigBee máximo** | **ZigBee máximo** |   |
| ----------------------------- | ----------------------------- | ----------------- | - |
| **+ Capacidad del enrutador** | **Capacidad del enrutador**   |                   |   |
|                               |                               |                   |   |
|                               |                               |                   |   |
| **PSS-29ZBS**                 | **40**                        | **10**            |   |
|                               |                               |                   |   |
| **PSM-29ZBSR**                | **10**                        | **5**             |   |
|                               |                               |                   |   |

**Operación**

![](<.gitbook/assets/6 (42).jpeg>)

-   _**Instalación**_
    -   Conecte el interruptor de encendido a una toma de corriente y luego conecte el aparato al enchufe del interruptor de encendido. El aparato debe estar en estado ON.
    -   _**NOTA IMPORTANTE**_**:**El interruptor de encendido no tiene una batería de respaldo y se apagará cuando falle la alimentación de CA.**NO**use el interruptor de encendido como enrutador para su sensor de seguridad o dispositivos de control de alarma, como contacto de puerta, sensor PIR, etc.; de lo contrario, los sensores perderán la conexión a la red ZigBee si el interruptor de encendido se desconecta de la alimentación de CA. Planifique las ubicaciones de instalación de estos sensores de seguridad sin usar el interruptor de encendido y use solo un enrutador con batería de respaldo para ellos. La función de enrutador del interruptor de encendido debe**SOLO**Se puede utilizar para proporcionar una extensión del rango de señal para otros interruptores/atenuadores de alimentación.

2

-   ![](<.gitbook/assets/7 (39).jpeg>)_**Control de electrodomésticos**_
    -   Después de que el interruptor de encendido se haya unido exitosamente a una red ZigBee, el coordinador puede encender/apagar remotamente el interruptor de encendido para controlar el aparato.
    -   También puede presionar el botón en el interruptor de encendido para alternar su estado de encendido/apagado.
    -   Si ha vinculado un controlador con el interruptor de encendido, también puede usar el controlador para encender/apagar el interruptor de encendido.
    -   Si se retira el interruptor de encendido del tomacorriente, después de volver a enchufarlo, su estado anterior de encendido/apagado se restablecerá en 1 minuto.
-   _**Monitor de consumo de energía (solo PSM-29ZBS / PSM-29ZBSR)**_
    -   Los modelos Power Switch con medidor incorporado transmitirán una señal con los datos de su consumo de energía cada 10 minutos al coordinador de red ZigBee.
    -   Siempre que la salida de energía del interruptor de alimentación cambie en +/- 2 W, transmitirá automáticamente una señal con datos de consumo de energía al coordinador de red ZigBee para su actualización.
    -   El interruptor de alimentación transmite una señal con datos de energía al coordinador cada vez que el uso de energía acumulada aumenta en 0,1 kW/h.
    -   El medidor tiene una precisión de +/- 5%.
    -   Para borrar los datos de consumo de energía acumulado del interruptor de encendido, siga los pasos a continuación:
        1.  Desenchufe el interruptor de encendido del tomacorriente.
        2.  Mantenga presionado el botón de función y vuelva a enchufar el interruptor de encendido mientras mantiene presionado el botón.
        3.  Continúe presionando el botón y suéltelo después de 3 segundos. Se borrarán los datos de consumo de energía acumulado.
-   _**Carga máxima de operación**_
    -   Para 110V: la carga máxima de operación es 1760W y 16A.
    -   Para 230V: la carga máxima de funcionamiento es de 3680W y 16A.
    -   Si el interruptor de encendido se sobrecalienta, cortará la energía automáticamente como medida de seguridad. El interruptor de alimentación debe desconectarse y volverse a enchufar después de cortarlo para reanudar el funcionamiento normal.

![](<.gitbook/assets/8 (33).jpeg>)![](<.gitbook/assets/9 (26).jpeg>)

**Apéndice (solo para desarrolladores)**

![](<.gitbook/assets/10 (38).png>)

_**ID del grupo de interruptores de alimentación**_

| **ID del dispositivo: Toma de corriente: 0x0009** | **/ ELEGANTE_ENCHUFE: 0x0051** |                      |
| ------------------------------------------------- | ------------------------------ | -------------------- |
| **Punto final: 0x01**                             |                                |                      |
|                                                   |                                |                      |
| **Lado del servidor**                             |                                | **Lado del cliente** |
|                                                   |                                |                      |
|                                                   | **Obligatorio**                |                      |

Básico (0x0000)

Identificar(0x0003)

Activado/Desactivado(0x0006)

Grupos(0x0004)

Escenas (0x0005) (**Sólo PSS-29ZBS / PSS-29ZBSR**)

Medición(0x0702)(**Sólo PSM-29ZBS/PSM-29ZBSR**)

**Opcional**

Grupos(0x0004)

_Ninguno_

_Ninguno_

-   _**Atributo de información básica del clúster**_

| **Identificador** | **Nombre**                | **Tipo**   | **Rango**  | **Acceso**   | **Por defecto** | **Obligatorio** |   |
| ----------------- | ------------------------- | ---------- | ---------- | ------------ | --------------- | --------------- | - |
| **/ Opcional**    |                           |            |            |              |                 |                 |   |
|                   |                           |            |            |              |                 |                 |   |
| 0x0000            | _Versión ZCL_             | No firmado | 0x00 –0xff | Solo lectura | 0x01            | METRO           |   |
| entero de 8 bits  |                           |            |            |              |                 |                 |   |
|                   |                           |            |            |              |                 |                 |   |
| 0x0001            | Versión de la aplicación  | No firmado | 0x00 –0xff | Solo lectura | 0x00            | oh              |   |
| entero de 8 bits  |                           |            |            |              |                 |                 |   |
|                   |                           |            |            |              |                 |                 |   |
| 0x0003            | _Versión HW_              | No firmado | 0x00 –0xff | Solo lectura | 0               | oh              |   |
| entero de 8 bits  |                           |            |            |              |                 |                 |   |
|                   |                           |            |            |              |                 |                 |   |
| 0x0004            | _Nombre del Fabricante_   | Personaje  | 0–32       | Solo lectura | Clímax          | oh              |   |
| Cadena            | bytes                     | Tecnología |            |              |                 |                 |   |
|                   |                           |            |            |              |                 |                 |   |
| 0x0005            | _Identificador de modelo_ | Personaje  | 0–32       | Solo lectura | (Modelo         | oh              |   |
| Cadena            | bytes                     | Versión)   |            |              |                 |                 |   |
|                   |                           |            |            |              |                 |                 |   |
| 0x0006            | _Código de fecha_         | Personaje  | 0–16       | Solo lectura |                 | oh              |   |
| Cadena            | bytes                     |            |            |              |                 |                 |   |
|                   |                           |            |            |              |                 |                 |   |
| 0x0007            | _Fuente de alimentación_  | 8 bits     | 0x00 –0xff | Solo lectura |                 | METRO           |   |
|                   |                           |            | 3          |              |                 |                 |   |

| 0x0010                                                       | _Descripción de la ubicación_ | Personaje              | 0–32         |   |              | Leer escribir |                 | oh              |   |   |
| ------------------------------------------------------------ | ----------------------------- | ---------------------- | ------------ | - | ------------ | ------------- | --------------- | --------------- | - | - |
| Cadena                                                       | bytes                         |                        |              |   |              |               |                 |                 |   |   |
|                                                              |                               |                        |              |   |              |               |                 |                 |   |   |
| 0x0011                                                       | _Entorno físico_              | 8 bits                 | 0x00 –0xff   |   |              | Leer escribir | 0x00            | oh              |   |   |
| 0x0012                                                       | _Dispositivo habilitado_      | Booleano               | 0x00 –       |   |              | Leer escribir | 0x01            | METRO           |   |   |
| 0x01                                                         |                               |                        |              |   |              |               |                 |                 |   |   |
|                                                              |                               |                        |              |   |              |               |                 |                 |   |   |
| _**Atributo de información de identificación del clúster**_ |                               |                        |              |   |              |               |                 |                 |   |   |
|                                                              |                               |                        |              |   |              |               |                 |                 |   |   |
| **Identificador**                                            | **Nombre**                    | **Tipo**               | **Rango**    |   | **Acceso**   |               | **Por defecto** | **Obligatorio** |   |   |
|                                                              |                               | **/ Opcional**         |              |   |              |               |                 |                 |   |   |
|                                                              |                               |                        |              |   |              |               |                 |                 |   |   |
| 0x0000                                                       | _IdentificarTiempo_           | No firmado             | 0x00 –0xffff |   | Leer /       |               | 0x0000          | METRO           |   |   |
| entero de 16 bits                                            |                               | Escribir               |              |   |              |               |                 |                 |   |   |
|                                                              |                               |                        |              |   |              |               |                 |                 |   |   |
| _**Atributos de la información del clúster Grupos**_        |                               |                        |              |   |              |               |                 |                 |   |   |
|                                                              |                               |                        |              |   |              |               |                 |                 |   |   |
| **Identificador**                                            | **Nombre**                    | **Tipo**               | **Rango**    |   | **Acceso**   |               | **Por defecto** | **Obligatorio** |   |   |
|                                                              |                               | **/ Opcional**         |              |   |              |               |                 |                 |   |   |
|                                                              |                               |                        |              |   |              |               |                 |                 |   |   |
| 0x0000                                                       | _NombreSoporte_               | mapa de bits de 8 bits | x0000000     |   | Solo lectura |               | -               | METRO           |   |   |

![](<.gitbook/assets/11 (29).png>)![](<.gitbook/assets/12 (34).png>)![](<.gitbook/assets/13 (24).jpeg>)

-   _**Atributos del grupo de escenas Información**_

![](<.gitbook/assets/14 (20).jpeg>)

| **Identificador**                                               | **Nombre**          | **Tipo**               | **Rango**       | **Acceso**   | **Por defecto** | **Obligatorio** |   |
| --------------------------------------------------------------- | ------------------- | ---------------------- | --------------- | ------------ | --------------- | --------------- | - |
| **/ Opcional**                                                  |                     |                        |                 |              |                 |                 |   |
|                                                                 |                     |                        |                 |              |                 |                 |   |
| 0x0000                                                          | Recuento de escenas | 8 bits sin firmar      | 0x00 – 0xff     | Solo lectura | 0x00            | METRO           |   |
| entero                                                          |                     |                        |                 |              |                 |                 |   |
|                                                                 |                     |                        |                 |              |                 |                 |   |
| 0x0001                                                          | _Escena actual_     | 8 bits sin firmar      | 0x00 – 0xff     | Solo lectura | 0x00            | METRO           |   |
| entero                                                          |                     |                        |                 |              |                 |                 |   |
|                                                                 |                     |                        |                 |              |                 |                 |   |
| 0x0002                                                          | _Grupo actual_      | 16 bits sin firmar     | 0x0000 – 0xfff7 | Solo lectura | 0x00            | METRO           |   |
|                                                                 | entero              |                        |                 |              |                 |                 |   |
|                                                                 |                     |                        |                 |              |                 |                 |   |
| 0x0003                                                          | _Escena válida_     | Booleano               | 0x00 – 0x01     | Solo lectura | 0x00            | METRO           |   |
| 0x0004                                                          | _NombreSoporte_     | mapa de bits de 8 bits | x0000000        | Solo lectura | -               | METRO           |   |
| _**Atributo de información del clúster activado/desactivado**_ |                     |                        |                 |              |                 |                 |   |

![](<.gitbook/assets/15 (22).png>)

| **Identificador** | **Nombre**          | **Tipo** | **Rango**  | **Acceso**   | **Por defecto** | **Obligatorio** |   |
| ----------------- | ------------------- | -------- | ---------- | ------------ | --------------- | --------------- | - |
| **/ Opcional**    |                     |          |            |              |                 |                 |   |
|                   |                     |          |            |              |                 |                 |   |
| 0x0000            | _Encendido apagado_ | Booleano | 0x00 –0x01 | Solo lectura | 0x00            | METRO           |   |

![](<.gitbook/assets/16 (24).png>)

_**Atributos de la información del grupo de medición (atributo de información de lectura)**_

![](<.gitbook/assets/17 (16).jpeg>)

_**conjunto) (PSM-29ZBS / PSM-29ZBSR solamente)**_

| **Identificador** | **Nombre**        | **Tipo**       | **Rango**        | **Acceso** | **Por defecto** | **Obligatorio** |   |
| ----------------- | ----------------- | -------------- | ---------------- | ---------- | --------------- | --------------- | - |
| **/ Opcional**    |                   |                |                  |            |                 |                 |   |
|                   |                   |                |                  |            |                 |                 |   |
| 0x00              | Resumen actual    | No firmado     | 0x000000000000 a | Leer       |                 | METRO           |   |
| Entregado         | Entero de 48 bits | 0xFFFFFFFFFFFF | Solo             |            |                 |                 |   |
|                   |                   |                |                  |            |                 |                 |   |

![](<.gitbook/assets/18 (24).png>)

_**Atributos de la información del clúster de medición (conjunto de atributos de formato)**_

![](<.gitbook/assets/19 (7).jpeg>)

_**(PSM-29ZBS / PSM-29ZBSR solamente)**_

| **Identificador** | **Nombre**                      | **Tipo**               | **Rango**    | **Acceso**   | **Por defecto** | **Obligatorio** |   |
| ----------------- | ------------------------------- | ---------------------- | ------------ | ------------ | --------------- | --------------- | - |
| **/ Opcional**    |                                 |                        |              |              |                 |                 |   |
|                   |                                 |                        |              |              |                 |                 |   |
| 0x00              | Unidad de medida                | 8 bits                 | 0x00 a 0xFF  | Solo lectura | 0x00            | METRO           |   |
| Enumeración       |                                 |                        |              |              |                 |                 |   |
|                   |                                 |                        |              |              |                 |                 |   |
| 0x01              | Multiplicador                   | No firmado             | 0x000000 a   | Solo lectura | 1               | oh              |   |
| Entero de 24 bits | 0xFFFFFF                        |                        |              |              |                 |                 |   |
|                   |                                 |                        |              |              |                 |                 |   |
| 0x02              | Divisor                         | No firmado             | 0x000000 a   | Solo lectura | 10000           | oh              |   |
| 24-bit Integer    | 0xFFFFFF                        |                        |              |              |                 |                 |   |
|                   |                                 |                        |              |              |                 |                 |   |
| 0x03              | SumaFormato                     | Mapa de bits de 8 bits | 0x00 a 0xFF  | Solo lectura | 0xF9            | METRO           |   |
| 0x04              | Formato de demanda              | Mapa de bits de 8 bits | 0x00 to 0xFF | Solo lectura | 0Ksasa          | oh              |   |
| 0x06              | Tipo de dispositivo de medición | Mapa de bits de 8 bits | 0x00 a 0xFF  | Solo lectura | 0x00            | METRO           |   |

![](<.gitbook/assets/20 (17).png>)

-   _**Atributos de la información del grupo de medición (conjunto de atributos históricos) (solo PSM-29ZBS / PSM-29ZBSR)**_

| **Identificador** | **Nombre**          | **Tipo**           | **Rango**    | **Acceso**   | **Por defecto** | **Obligatorio** |   |
| ----------------- | ------------------- | ------------------ | ------------ | ------------ | --------------- | --------------- | - |
| **/ Opcional**    |                     |                    |              |              |                 |                 |   |
|                   |                     |                    |              |              |                 |                 |   |
| 0x00              | Demanda Instantánea | Firmado de 24 bits | -8.388.607 a | Solo lectura | 0x00            | oh              |   |
| Entero            | 8,388,607           |                    |              |              |                 |                 |   |
|                   |                     |                    |              |              |                 |                 |   |

4
