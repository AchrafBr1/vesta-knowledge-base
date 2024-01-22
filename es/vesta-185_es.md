# VESTA 185

**Sensor de luz ambiental, humedad y temperatura LMHT-1ZBS**

**Introducción**

LMHT-1ZBS es un sensor de temperatura, humedad y luz ambiental ZigBee. Supervisa el entorno de su hogar y transmite la iluminancia (lux), la humedad y la temperatura medidas al coordinador en la red ZigBee.

El sensor utiliza tecnología ZigBee para la transmisión de señales inalámbricas. ZigBee es un protocolo de comunicación inalámbrica confiable, de bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir una gran cantidad de dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

El sensor sirve como dispositivo final en la red ZigBee. Puede incluirse en la red ZigBee para transmitir señal tras la activación, pero no puede permitir que ningún otro dispositivo ZigBee se una a la red a través del sensor.

**Identificación de piezas**

1.  **Sensor de luz/indicador LED**
    -   **Parpadea una vez:**Restablecimiento de fábrica
    -   **Parpadea dos veces:**Después de que el sensor se haya unido con éxito a una red ZigBee.
    -   **Parpadea 3 veces:**Batería insertada.
    -   **Parpadea 5 veces:**Batería baja detectada al insertar la batería.
    -   **Parpadea una vez cada 20 minutos:**El sensor ha perdido la conexión a su red ZigBee actual.
2.  **Sensor de temperatura**
3.  **Compartimiento de la batería**
4.  **Botón de función**
    -   Presione una vez para enviar una señal al coordinador.
    -   Mantenga presionado durante 10 segundos para restablecer el dispositivo.

![](<.gitbook/assets/0 (73).jpeg>)

**Características**

-   _**Monitoreo de iluminación, humedad y temperatura**_
    -   El sensor mide la iluminancia, la humedad y la temperatura para transmitir periódicamente los datos medidos al coordinador de la red ZigBee.

La lectura de iluminancia se transmite cada 30 minutos.

La lectura de humedad y temperatura se transmite cada 10 minutos. El sensor también transmitirá la señal automáticamente cuando:

-   -   -   La temperatura cambia +/- 2°C.
        -   La humedad cambia +/- 10%.
        -   Cuando la iluminancia actual cambia en +/- 10%.
        -   El nivel de cambio requerido para activar la transmisión de señal se puede programar usando el comando ZigBee Configure Reporting – parámetro de cambio reportable. Los valores predeterminados son:

Temperatura:**200**por 2°C.

Humedad:**1000**por el 10%.

Iluminancia:**10**por el 10%.

-   -   También puede presionar el botón de función una vez para transmitir la lectura actual manualmente.
-   _**Detección de batería y batería baja**_
    -   El sensor utiliza una batería de litio CR123A de 3 V como fuente de alimentación.
    -   El sensor cuenta con la función de detección de batería baja. Cuando el voltaje de la batería es bajo, el sensor transmitirá la señal de batería baja al coordinador en la red ZigBee.
    -   Al cambiar la batería, después de quitar las baterías viejas, presione el botón de función dos veces para descargarla completamente antes de insertar una batería nueva.
    -   Si se detecta un voltaje bajo de la batería al insertar una batería nueva, el indicador LED parpadeará 5 veces.

1

-   _**Supervisión**_

El sensor transmitirá una señal de supervisión junto con la señal de lectura para informar su condición periódicamente. El intervalo predeterminado de fábrica es de 30 minutos, que se puede ajustar según la configuración.

**Configuración de red ZigBee**

-   _**Guía del dispositivo ZigBee**_

ZigBee es un protocolo de comunicación inalámbrica confiable, de bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir una gran cantidad de dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

Debido a la estructura fundamental de la red ZigBee, el dispositivo ZigBee buscará y se unirá activamente a la red después de encenderse. Dado que realizar una tarea al conectarse a la red puede consumir algo de energía, es necesario seguir las instrucciones para evitar agotar la batería de un dispositivo ZigBee.

-   -   Asegúrese de que su enrutador o coordinador de red ZigBee esté encendido antes de insertar la batería en el dispositivo ZigBee.
    -   Asegúrese de que el enrutador o coordinador de red ZigBee esté encendido y dentro del alcance mientras un dispositivo ZigBee esté en uso.
    -   No retire un dispositivo ZigBee del enrutador o coordinador de red ZigBee sin quitar la batería del dispositivo ZigBee.
-   _**Unirse a la red ZigBee**_

Como dispositivo ZigBee, el sensor necesita unirse a una red ZigBee para transmitir la señal. Siga los pasos a continuación para unir el sensor a la red ZigBee.

-   1.  Separe el conjunto de la cubierta superior y la base e inserte la batería.
    2.  Mantenga presionado el botón de función durante 10 segundos mientras el sensor se reinicia (el LED parpadea una vez) y comienza a buscar la red ZigBee existente. Asegúrese de que la función de permiso para unirse en el enrutador o coordinador de su red ZigBee esté habilitada.
    3.  Si el sensor se une exitosamente a una red ZigBee, el indicador LED parpadeará dos veces para confirmar.
    4.  Después de unirse a la red ZigBee, el sensor se registrará en la red automáticamente. Consulte con su coordinador ZigBee, panel de control del sistema o CIE (Equipo de control e indicación) para confirmar si la inscripción y el registro se realizaron correctamente.
    5.  Después de unirse a la red ZigBee, si el sensor pierde la conexión con la red ZigBee actual, el LED parpadeará cada 20 minutos para indicarlo. Verifique el estado de su red ZigBee y el rango de señal del sensor para corregir la situación.
-   _**Eliminación del dispositivo de la red ZigBee (restablecimiento de fábrica)**_

Para eliminar el dispositivo de la red ZigBee actual, se debe restablecer el sensor a los valores de fábrica para completar la eliminación del dispositivo. La función de restablecimiento de fábrica borrará la información de configuración almacenada del dispositivo y solicitará al sensor que busque una nueva red ZigBee.

**Antes de retirar el dispositivo, asegúrese de que el sensor esté dentro del rango de señal de red ZigBee actual.**

1.  Mantenga presionado el botón de función durante 10 segundos, luego suelte el botón para restablecer el sensor.
2.  Al reiniciarse, el sensor borrará la configuración actual de la red ZigBee y transmitirá la señal al coordinador ZigBee para eliminarse de la red ZigBee actual. Luego buscará activamente nuevamente la red ZigBee disponible y se unirá a la red automáticamente.

**Instalación**

-   _**Montaje del sensor**_

El sensor se puede montar mediante dos métodos: montaje autoadhesivo o con tornillos.

**Montaje autoadhesivo**

1.  Limpiar la superficie con un desengrasante adecuado.
2.  Retire la cubierta protectora de un lado de la almohadilla adhesiva de doble cara y aplíquela firmemente en la parte posterior del dispositivo.
3.  Retire la otra cubierta y coloque/presione firmemente el dispositivo en el lugar deseado.

![](<.gitbook/assets/1 (65).jpeg>)

No utilice el método de montaje autoadhesivo en superficies mal pintadas y/o rugosas.

**Montaje con tornillos**

La base del sensor tiene dos orificios ciegos para tornillos, donde el plástico es más delgado para fines de montaje. Para montar el sensor:

1.  Separe el conjunto de la cubierta superior y la base aflojando el tornillo de fijación de la cubierta con un destornillador Philips.
2.  Rompe los nocauts en la base.

2

-   1.  Utilice los agujeros como plantilla para perforar dos agujeros e insertar los tacos.
    2.  Atornille la base a los tacos de pared.
    3.  Vuelva a colocar la cubierta superior sobre la base enganchando la base en el gancho de fijación y empujando la cubierta hacia la base.
    4.  Asegure y atornille la cubierta superior a su base con un destornillador Philips.
-   _**Usando el sensor con el enrutador ZigBee**_

_**NOTA IMPORTANTE**_

Si la ubicación de instalación del sensor está lejos del panel de control de su sistema y requiere enrutadores ZigBee para mejorar la intensidad de la señal.**NO**Utilice un enrutador ZigBee sin batería de respaldo. Un enrutador ZigBee sin batería se apagará durante un corte de energía de CA y el sensor conectado al enrutador perderá la conexión con la red ZigBee. Debe planificar la ubicación de instalación de su sensor utilizando únicamente un enrutador ZigBee con batería de respaldo.

-   _**Actualización de firmware OTA (solo para la versión OTA)**_

El sensor de luz ambiental, humedad y temperatura admite la función de actualización de firmware OTA a través de la red ZigBee, que se puede iniciar desde el coordinador de la red ZigBee. Siga los pasos a continuación para realizar la actualización del firmware OTA.**Paso 1.**Debe acceder a su Coordinador ZigBee para realizar la actualización del firmware en el aire.

**Paso 2.** On the configuration webpage, select the device that you wish to upgrade and select the new ZigBee firmware provided. Please refer to ZigBee Coordinator User Manual for details.

**Paso 3.**Presione "OK" para iniciar el proceso de actualización y el LED seguirá parpadeando. Durante el proceso de OTA, por favor haga

No realice ninguna otra acción ni apague el panel.

**Etapa 4.**La duración de una actualización tardará aproximadamente entre 20 y 30 minutos. Tenga en cuenta que la duración puede variar según el tamaño del archivo o la distancia entre su accesorio y el coordinador.

**Paso 5.**Espere a que el firmware complete la actualización. Cuando el progreso alcance el 100%, el dispositivo se reiniciará automáticamente. También puede actualizar la página web nuevamente para asegurarse de que el firmware del dispositivo se actualice correctamente y se muestre la versión más reciente.

**Apéndice**

**(La información del Apéndice es solo para desarrolladores).**

-   _**ID del grupo de sensores de luz**_

**ID del dispositivo: Sensor de luz 0x0106**

**Punto final: 0x01**

| **Lado del servidor**                 |                 | **Lado del cliente** |
| ------------------------------------- | --------------- | -------------------- |
|                                       |                 |                      |
|                                       | **Obligatorio** |                      |
|                                       |                 |                      |
| Básico (0x0000)                       |                 | Básico (0x0000)      |
|                                       |                 |                      |
| Identificar(0x0003)                   |                 | Identificar(0x0003)  |
|                                       |                 |                      |
| Medición de iluminancia (0x0400)      |                 |                      |
|                                       |                 |                      |
|                                       | **Opcional**    |                      |
|                                       |                 |                      |
| Configuración de energía (0x0001)     |                 | _Ninguno_            |
|                                       |                 |                      |
| Medición de temperatura (0x0402)      |                 |                      |
|                                       |                 |                      |
| Medición de humedad relativa (0x0405) |                 |                      |
|                                       |                 |                      |

-   _**Atributo de información básica del clúster**_

| **Identificador** | **Nombre**                    | **Tipo**          | **Rango**    | **Acceso** | **Por defecto**      | **Obligatorio** |   |
| ----------------- | ----------------------------- | ----------------- | ------------ | ---------- | -------------------- | --------------- | - |
| **/ Opcional**    |                               |                   |              |            |                      |                 |   |
|                   |                               |                   |              |            |                      |                 |   |
| 0x0000            | _Versión ZCL_                 | 8 bits sin firmar | 0x00 –0xff   | Leer       | 0x01                 | METRO           |   |
| entero            | solo                          |                   |              |            |                      |                 |   |
|                   |                               |                   |              |            |                      |                 |   |
| 0x0001            | Versión de la aplicación      | 8 bits sin firmar | 0x00 –0xff   | Leer       | 0x00                 | oh              |   |
| entero            | solo                          |                   |              |            |                      |                 |   |
|                   |                               |                   |              |            |                      |                 |   |
| 0x0003            | _Versión HW_                  | 8 bits sin firmar | 0x00 –0xff   | Leer       | 0                    | oh              |   |
| entero            | solo                          |                   |              |            |                      |                 |   |
|                   |                               |                   |              |            |                      |                 |   |
| 0x0004            | _Nombre del Fabricante_       | Personaje         | 0 – 32 bytes | Leer       | Clímax               | oh              |   |
| Cadena            | solo                          | Tecnología        |              |            |                      |                 |   |
|                   |                               |                   |              |            |                      |                 |   |
| 0x0005            | _Identificador de modelo_     | Personaje         | 0 – 32 bytes | Leer       | (Versión del modelo) | oh              |   |
| Cadena            | solo                          |                   |              |            |                      |                 |   |
|                   |                               |                   |              |            |                      |                 |   |
| 0x0006            | _Código de fecha_             | Personaje         | 0 – 16 bytes | Leer       |                      | oh              |   |
| Cadena            | solo                          |                   |              |            |                      |                 |   |
|                   |                               |                   |              |            |                      |                 |   |
| 0x0007            | _Fuente de alimentación_      | 8 bits            | 0x00 –0xff   | Leer       |                      | METRO           |   |
| solo              |                               |                   |              |            |                      |                 |   |
|                   |                               |                   |              |            |                      |                 |   |
| 0x0010            | _Descripción de la ubicación_ | Personaje         | 0 – 32 bytes | Leer /     |                      | oh              |   |
| Cadena            | Escribir                      |                   |              |            |                      |                 |   |
|                   |                               |                   |              |            |                      |                 |   |
|                   |                               |                   | 3            |            |                      |                 |   |

| 0x0011   | _Entorno físico_         | 8 bits   | 0x00 –0xff | Leer / | 0x00 | oh    |   |
| -------- | ------------------------ | -------- | ---------- | ------ | ---- | ----- | - |
| Escribir |                          |          |            |        |      |       |   |
|          |                          |          |            |        |      |       |   |
| 0x0012   | _Dispositivo habilitado_ | Booleano | 0x00 –0x01 | Leer / | 0x01 | METRO |   |
| Escribir |                          |          |            |        |      |       |   |
|          |                          |          |            |        |      |       |   |

_**Atributo de información de identificación del clúster**_

| **Identificador** | **Nombre**          | **Tipo**   | **Rango**    | **Acceso** | **Por defecto** | **Obligatorio** |   |
| ----------------- | ------------------- | ---------- | ------------ | ---------- | --------------- | --------------- | - |
| **/ Opcional**    |                     |            |              |            |                 |                 |   |
|                   |                     |            |              |            |                 |                 |   |
| 0x0000            | _IdentificarTiempo_ | No firmado | 0x00 –0xffff | Leer /     | 0x0000          | METRO           |   |
| entero de 16 bits | Escribir            |            |              |            |                 |                 |   |
|                   |                     |            |              |            |                 |                 |   |

_**Atributo de la información del clúster de configuración de energía**_

| **Identificador** | **Nombre**                     | **Tipo** | **Rango** | **Acceso** | **Por defecto** | **Obligatorio** |   |
| ----------------- | ------------------------------ | -------- | --------- | ---------- | --------------- | --------------- | - |
| **/ Opcional**    |                                |          |           |            |                 |                 |   |
|                   |                                |          |           |            |                 |                 |   |
| 0x0035            | _Máscara de alarma de batería_ | 8 bits   | 0000 000x | Leer /     | 0000 0000       | oh              |   |
| mapa de bits      | Escribir                       |          |           |            |                 |                 |   |
|                   |                                |          |           |            |                 |                 |   |

_**Atributo de la información del grupo de medición de iluminancia**_

| **Identificador** | **Nombre**            | **Tipo**            | **Rango**            | **Acceso** | **Por defecto** | **Obligatorio** |   |
| ----------------- | --------------------- | ------------------- | -------------------- | ---------- | --------------- | --------------- | - |
| **/ Opcional**    |                       |                     |                      |            |                 |                 |   |
|                   |                       |                     |                      |            |                 |                 |   |
|                   |                       | Firmado de 16 bits  | Valor mínimo medido  | Leer       |                 |                 |   |
| 0x0000            | _Valor medido_        | a                   | 0x00                 | METRO      |                 |                 |   |
| Entero            | solo                  |                     |                      |            |                 |                 |   |
|                   |                       | Valor máximo medido |                      |            |                 |                 |   |
|                   |                       |                     |                      |            |                 |                 |   |
| 0x0001            | _Valor mínimo medido_ | Firmado de 16 bits  | 0x0001 - 0xffffd     | Leer       | 1               | METRO           |   |
| Entero            | solo                  |                     |                      |            |                 |                 |   |
|                   |                       |                     |                      |            |                 |                 |   |
| 0x0002            | _Valor máximo medido_ | Firmado de 16 bits  | ValorMínimoMedido +1 | Leer       | 52742           | METRO           |   |
| Entero            | - 0xffffe             | solo                |                      |            |                 |                 |   |
|                   |                       |                     |                      |            |                 |                 |   |

-   _**Atributo de información del grupo de medición de temperatura**_

| **Identificador** | **Nombre**          | **Tipo**            | **Rango**           | **Acceso** | **Por defecto** | **Obligatorio** |   |
| ----------------- | ------------------- | ------------------- | ------------------- | ---------- | --------------- | --------------- | - |
| **/ Opcional**    |                     |                     |                     |            |                 |                 |   |
|                   |                     |                     |                     |            |                 |                 |   |
|                   |                     | Firmado de 16 bits  | Valor mínimo medido | Leer       |                 |                 |   |
| 0x0000            | Valor medido        | a                   | 0x00                | METRO      |                 |                 |   |
| Entero            | solo                |                     |                     |            |                 |                 |   |
|                   |                     | Valor máximo medido |                     |            |                 |                 |   |
|                   |                     |                     |                     |            |                 |                 |   |
| 0x0001            | Valor mínimo medido | Firmado de 16 bits  | 0x954d – 0x7ffe     | Leer       | -1000           | METRO           |   |
| Entero            | solo                | (-10℃)              |                     |            |                 |                 |   |
|                   |                     |                     |                     |            |                 |                 |   |
| 0x0002            | Valor máximo medido | Firmado de 16 bits  | 0x954e – 0x7fff     | Leer       | 5000            | METRO           |   |
| Entero            | solo                | (50℃)               |                     |            |                 |                 |   |
|                   |                     |                     |                     |            |                 |                 |   |
| 0x0003            | Tolerancia          | 16 bits sin firmar  | 0x0000 – 0x0800     | Leer       | 100             | oh              |   |
| Entero            | solo                | (1℃)                |                     |            |                 |                 |   |
|                   |                     |                     |                     |            |                 |                 |   |

-   _**Atributo de la información del grupo de medición de humedad relativa**_

| **Identificador** | **Nombre**          | **Tipo**            | **Rango**           | **Acceso** | **Por defecto** | **Obligatorio** |   |
| ----------------- | ------------------- | ------------------- | ------------------- | ---------- | --------------- | --------------- | - |
| **/ Opcional**    |                     |                     |                     |            |                 |                 |   |
|                   |                     |                     |                     |            |                 |                 |   |
|                   |                     | 16 bits sin firmar  | Valor mínimo medido | Leer       |                 |                 |   |
| 0x0000            | Valor medido        | a                   |                     | METRO      |                 |                 |   |
| Entero            | solo                |                     |                     |            |                 |                 |   |
|                   |                     | Valor máximo medido |                     |            |                 |                 |   |
|                   |                     |                     |                     |            |                 |                 |   |
| 0x0001            | Valor mínimo medido | 16 bits sin firmar  | 0x0000 – 0x270f     | Leer       | 0               | METRO           |   |
| Entero            | solo                | (0%)                |                     |            |                 |                 |   |
|                   |                     |                     |                     |            |                 |                 |   |
| 0x0002            | Valor máximo medido | 16 bits sin firmar  | 0x0001 – 0x2710     | Leer       | 10000           | METRO           |   |
| Entero            | solo                | (100%)              |                     |            |                 |                 |   |
|                   |                     |                     |                     |            |                 |                 |   |
| 0x0003            | Tolerancia          | 16 bits sin firmar  | 0x0000 – 0x0800     | Leer       | 200             | oh              |   |
| Entero            | solo                | (2%)                |                     |            |                 |                 |   |
|                   |                     |                     |                     |            |                 |                 |   |

4
