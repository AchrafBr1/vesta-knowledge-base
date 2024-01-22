# VESTA 180

**SCS-1-ZBS Interruptor de control de obturador**

**Introducción**

SCS-1-ZBS es un interruptor de control de persianas de tres botones ZigBee diseñado para controlar un grupo de dispositivos domóticos preprogramados simplemente presionando los botones del escenario. Al configurar el escenario de control de contraventanas en el panel de control/coordinador de red ZigBee, el interruptor de control de contraventanas podrá controlar el movimiento de las contraventanas simplemente presionando sus botones.

El Shutter Switch utiliza tecnología ZigBee para la transmisión de señales inalámbricas. ZigBee es un protocolo de comunicación inalámbrica confiable, de bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir una gran cantidad de dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

El Shutter Switch sirve como dispositivo final en la red ZigBee. Puede incluirse en la red ZigBee para transmitir señal tras la activación y puede controlar cualquier dispositivo ZigBee, pero no puede permitir que ningún otro dispositivo ZigBee se una a la red a través del interruptor del obturador.

El interruptor de control de persianas SCS-1 ZigBee incluye los siguientes modelos:

SCS-1-ZBS

SCS-1-ZBS-OTA

![](<.gitbook/assets/0 (69).jpeg>)

**Introducción del dispositivo**

**1. LED de escenario**

Cuando se presiona cualquiera de los 3 botones de escenario, el LED se iluminará brevemente

**2. Botones de escenario**

El interruptor de control del obturador tiene 3 botones de escenario

1.  **Compartimiento de la batería**
2.  **Botón de función**
    -   Mantenga presionado durante 10 segundos para restablecer.
3.  **LED ZigBee (rojo)**

El LED rojo se enciende en las siguientes situaciones:

-   -   Parpadea una vez:

Al enviar señal de control/reinicio/aprendizaje.

-   -   Parpadea dos veces:

El interruptor de control de persianas se ha unido con éxito a una red ZigBee.

1.  **Ojal de función**

**Características**

![](<.gitbook/assets/1 (61).jpeg>)

-   _**Detección de batería y batería baja**_

El interruptor de control del obturador utiliza dos baterías alcalinas AA de 1,5 V como fuente de energía. El interruptor cuenta con la función de detección de batería baja. Cuando el voltaje de la batería es bajo, el interruptor de control del obturador transmitirá la señal de batería baja al coordinador de red ZigBee.

![](<.gitbook/assets/2 (62).png>)

-   _**Supervisión**_

El interruptor de control del obturador transmitirá una señal de supervisión para informar su condición periódicamente según el intervalo de tiempo establecido por el usuario. El intervalo predeterminado de fábrica es de 30 minutos.

![](<.gitbook/assets/3 (63).png>)

-   _**Control de escenario y obturador**_

Cuando se presiona un botón de escenario, el interruptor de control del obturador enviará una señal al panel de control para

1

active el escenario correspondiente (consulte el Panel de control para obtener más detalles). Configure el escenario en el Panel de control para controlar la función de apertura/cierre/parada de la persiana para operar la persiana a través del interruptor de control de escenario. El interruptor emitirá un pitido como indicación cuando se presione el botón.

**Configuración de red ZigBee**

![](<.gitbook/assets/4 (48).jpeg>)

-   _**Guía del dispositivo ZigBee**_

ZigBee es un protocolo de comunicación inalámbrica confiable, de bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir una gran cantidad de dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

Debido a la estructura fundamental de la red ZigBee, el dispositivo ZigBee buscará y se unirá activamente a la red después de encenderse. Dado que realizar una tarea al conectarse a la red puede consumir algo de energía, es necesario seguir las instrucciones para evitar agotar la batería de un dispositivo ZigBee.

-   -   Asegúrese de que su enrutador o coordinador de red ZigBee esté encendido antes de insertar la batería en el dispositivo ZigBee.
    -   Asegúrese de que el enrutador o coordinador de red ZigBee esté encendido y dentro del alcance mientras un dispositivo ZigBee esté en uso.
    -   No retire un dispositivo ZigBee del enrutador o coordinador de red ZigBee sin quitar la batería del dispositivo ZigBee.
-   _**Unirse a la red ZigBee**_

![](<.gitbook/assets/5 (31).jpeg>)

Como dispositivo ZigBee, el interruptor de control del obturador debe unirse a una red ZigBee para conectarse a los dispositivos ZigBee. Siga los pasos a continuación para unir el interruptor de control del obturador a la red ZigBee.

-   1.  Retire la cubierta usando un destornillador.
    2.  Inserte la batería y luego vuelva a colocar la tapa.
    3.  Mantenga presionado el botón de función durante 10 segundos y suéltelo cuando el LED rojo parpadee una vez para unirse a la red ZigBee. Asegúrese de habilitar la función de permiso de unión en el enrutador o coordinador de su red ZigBee.
    4.  Si el interruptor de control del obturador se une exitosamente a una red ZigBee, el indicador LED rojo parpadeará dos veces para confirmar.
    5.  Después de unirse a la red ZigBee, el interruptor de control del obturador se registrará en la red automáticamente. Consulte el coordinador de la red ZigBee, el panel de control del sistema o el CIE (equipo de control e indicación) para confirmar si la inscripción y el registro se realizaron correctamente.
-   _**Eliminación del dispositivo de la red ZigBee (restablecimiento de fábrica)**_

![](<.gitbook/assets/6 (41).png>)

Para eliminar el dispositivo de la red ZigBee actual, el interruptor de control del obturador debe colocarse en Restablecimiento de fábrica para completar la eliminación del dispositivo. La función de restablecimiento de fábrica borrará la información de configuración almacenada del dispositivo y solicitará al interruptor de control del obturador que busque una nueva red ZigBee.

**Antes de retirar el dispositivo, asegúrese de que el interruptor de control del obturador esté dentro del rango de señal de red ZigBee actual.**

-   1.  Elimine el control del obturador del panel de control/CIE actual.
    2.  Mantenga presionado el botón de función durante 10 segundos, luego suelte el botón para restablecer el dispositivo.
    3.  Al reiniciarse, el interruptor de control del obturador borrará la configuración actual de la red ZigBee y transmitirá la señal al coordinador ZigBee para eliminarse de la red ZigBee actual. Luego buscará activamente nuevamente la red ZigBee disponible y se unirá a la red automáticamente.
-   _**Actualización de firmware OTA (solo para la versión OTA)**_

![](<.gitbook/assets/7 (37).jpeg>)

El interruptor de control del obturador admite la función de actualización del firmware OTA a través de la red ZigBee, que puede iniciarse desde el coordinador de la red ZigBee.

Siga los pasos a continuación para realizar la actualización del firmware OTA.

**Paso 1.**Debe acceder a su Coordinador ZigBee para realizar la actualización del firmware en el aire.

**Paso 2.**En la página web de configuración, seleccione el dispositivo que desea actualizar y seleccione el nuevo firmware ZigBee proporcionado. Consulte el Manual del usuario del Coordinador ZigBee para obtener más detalles.

**Paso 3.**Presione "OK" para iniciar el proceso de actualización y el LED seguirá parpadeando. Durante el proceso OTA, no realice ninguna otra acción ni apague el panel.

**Etapa 4.**La duración de una actualización tardará aproximadamente entre 20 y 30 minutos. Tenga en cuenta que la duración puede variar según el tamaño del archivo o la distancia entre su accesorio y el coordinador.

**Paso 5.**Espere a que el firmware complete la actualización. Cuando el progreso alcance el 100%, el dispositivo se reiniciará automáticamente. También puede actualizar la página web nuevamente para asegurarse de que el firmware del dispositivo se actualice correctamente y se muestre la versión más reciente.

![](<.gitbook/assets/8 (31).jpeg>)

**Instalación**

-   El interruptor de control de persianas está diseñado para montarse en una superficie plana con tornillos de fijación.
-   La base tiene 3 orificios ciegos, donde el plástico es más delgado, para fines de montaje.
    1.  Retire la cubierta usando un destornillador.
    2.  Rompe los nocauts apropiados en la base.
    3.  Usando los agujeros como plantilla, taladre agujeros en la superficie.

2

1.  Atornille la base a la superficie.
2.  Vuelva a colocar la cubierta en la base y asegúrela apretando el tornillo de fijación.

![](<.gitbook/assets/9 (23).jpeg>)

-   **Apéndice (solo para desarrolladores)**

_**ID de grupo del selector de escenas**_

**ID del dispositivo: Selector de escena 0x0004**

**Punto final: 0x01**

| **Lado del servidor** |                 | **Lado del cliente** |
| --------------------- | --------------- | -------------------- |
|                       |                 |                      |
|                       | **Obligatorio** |                      |

Básico (0x0000)

Identificar(0x0003)

Identificar (0x0003)

Grupos (0x0004)

Escenas (0x0005)

**Opcional**

Configuración de energía (0x0001)

_Ninguno_

-   _**Atributo de información básica del clúster**_

| _**Identificador**_ | _**Nombre**_                  | _**Tipo**_        | _**Rango**_  | _**Acceso**_ | _**Por defecto**_  | _**Obligatorio**_ |   |
| ------------------- | ----------------------------- | ----------------- | ------------ | ------------ | ------------------ | ----------------- | - |
| _**/ Opcional**_    |                               |                   |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |
| 0x0000              | _Versión ZCL_                 | 8 bits sin firmar | 0x00 –0xff   | Leer         | 0x01               | METRO             |   |
| entero              | solo                          |                   |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |
| 0x0001              | Versión de la aplicación      | 8 bits sin firmar | 0x00 – 0xff  | Leer         | 0x00               | oh                |   |
| entero              | solo                          |                   |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |
| 0x0003              | _Versión HW_                  | 8 bits sin firmar | 0x00 –0xff   | Leer         | 0                  | oh                |   |
| entero              | solo                          |                   |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |
| 0x0004              | _Nombre del Fabricante_       | Personaje         | 0 – 32 bytes | Leer         | Clímax             | oh                |   |
| Cadena              | solo                          | Tecnología        |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |
| 0x0005              | _Identificador de modelo_     | Personaje         | 0 – 32 bytes | Leer         | (Número de modelo) | oh                |   |
| Cadena              | solo                          |                   |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |
| 0x0006              | _Código de fecha_             | Personaje         | 0 – 16 bytes | Leer         |                    | oh                |   |
| Cadena              | solo                          |                   |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |
| 0x0007              | _Fuente de alimentación_      | 8 bits            | 0x00 –0xff   | Leer         |                    | METRO             |   |
| solo                |                               |                   |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |
| 0x0010              | _Descripción de la ubicación_ | Personaje         | 0 – 32 bytes | Leer /       |                    | oh                |   |
| Cadena              | Escribir                      |                   |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |
| 0x0011              | _Entorno físico_              | 8 bits            | 0x00 –0xff   | Leer /       | 0x00               | oh                |   |
| Escribir            |                               |                   |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |
| 0x0012              | _Dispositivo habilitado_      | Booleano          | 0x00 –0x01   | Leer /       | 0x01               | METRO             |   |
| Escribir            |                               |                   |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |

-   _**Atributo de información de identificación del clúster**_

| **Identificador** | **Nombre**                                                                | **Tipo**     | **Rango**    | **Acceso** | **Por defecto** | **Obligatorio** |   |
| ----------------- | ------------------------------------------------------------------------- | ------------ | ------------ | ---------- | --------------- | --------------- | - |
| **/ Opcional**    |                                                                           |              |              |            |                 |                 |   |
|                   |                                                                           |              |              |            |                 |                 |   |
| 0x0000            | _IdentificarTiempo_                                                       | No firmado   | 0x00 –0xffff | Leer /     | 0x0000          | METRO           |   |
| entero de 16 bits | Escribir                                                                  |              |              |            |                 |                 |   |
|                   |                                                                           |              |              |            |                 |                 |   |
|                   | _**Atributo de la información del clúster de configuración de energía**_ |              |              |            |                 |                 |   |
|                   |                                                                           |              |              |            |                 |                 |   |
| **Identificador** | **Nombre**                                                                | **Tipo**     | **Rango**    | **Acceso** | **Por defecto** | **Obligatorio** |   |
| **/ Opcional**    |                                                                           |              |              |            |                 |                 |   |
|                   |                                                                           |              |              |            |                 |                 |   |
| 0x0035            | Máscara de alarma de batería                                              | mapa de bits | 0000 - 000x  | Leer /     | 0000 0000       | oh              |   |
| (8 bits)          | Escribir                                                                  |              |              |            |                 |                 |   |
|                   |                                                                           |              |              |            |                 |                 |   |

3

_**ID del grupo de controladores de cortinas (para panel HPGW-G)**_

**ID del dispositivo: Controlador de persiana 0x0201**

**Punto final: 0x01**

| **Lado del servidor** |                 | **Lado del cliente** |
| --------------------- | --------------- | -------------------- |
|                       |                 |                      |
|                       | **Obligatorio** |                      |

Básico (0x0000)

Identificar(0x0003)

Identificar (0x0003)

Encendido/Apagado (0x0006)

Control de nivel (0x0008)

**Opcional**

Configuración de energía (0x0001)

_Ninguno_

-   _**Atributo de información básica del clúster**_

| _**Identificador**_ | _**Nombre**_                  | _**Tipo**_        | _**Rango**_  | _**Acceso**_ | _**Por defecto**_  | _**Obligatorio**_ |   |
| ------------------- | ----------------------------- | ----------------- | ------------ | ------------ | ------------------ | ----------------- | - |
| _**/ Opcional**_    |                               |                   |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |
| 0x0000              | _Versión ZCL_                 | 8 bits sin firmar | 0x00 –0xff   | Leer         | 0x01               | METRO             |   |
| entero              | solo                          |                   |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |
| 0x0001              | Versión de la aplicación      | 8 bits sin firmar | 0x00 – 0xff  | Leer         | 0x00               | oh                |   |
| entero              | solo                          |                   |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |
| 0x0003              | _Versión HW_                  | 8 bits sin firmar | 0x00 –0xff   | Leer         | 0                  | oh                |   |
| entero              | solo                          |                   |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |
| 0x0004              | _Nombre del Fabricante_       | Personaje         | 0 – 32 bytes | Leer         | Clímax             | oh                |   |
| Cadena              | solo                          | Tecnología        |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |
| 0x0005              | _Identificador de modelo_     | Personaje         | 0 – 32 bytes | Leer         | (Número de modelo) | oh                |   |
| Cadena              | solo                          |                   |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |
| 0x0006              | _Código de fecha_             | Personaje         | 0 – 16 bytes | Leer         |                    | oh                |   |
| Cadena              | solo                          |                   |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |
| 0x0007              | _Fuente de alimentación_      | 8 bits            | 0x00 –0xff   | Leer         |                    | METRO             |   |
| solo                |                               |                   |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |
| 0x0010              | _Descripción de la ubicación_ | Personaje         | 0 – 32 bytes | Leer /       |                    | oh                |   |
| Cadena              | Escribir                      |                   |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |
| 0x0011              | _Entorno físico_              | 8 bits            | 0x00 –0xff   | Leer /       | 0x00               | oh                |   |
| Escribir            |                               |                   |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |
| 0x0012              | _Dispositivo habilitado_      | Booleano          | 0x00 –0x01   | Leer /       | 0x01               | METRO             |   |
| Escribir            |                               |                   |              |              |                    |                   |   |
|                     |                               |                   |              |              |                    |                   |   |

-   _**Atributo de información de identificación del clúster**_

| **Identificador** | **Nombre**                                                                | **Tipo**     | **Rango**    | **Acceso** | **Por defecto** | **Obligatorio** |   |
| ----------------- | ------------------------------------------------------------------------- | ------------ | ------------ | ---------- | --------------- | --------------- | - |
| **/ Opcional**    |                                                                           |              |              |            |                 |                 |   |
|                   |                                                                           |              |              |            |                 |                 |   |
| 0x0000            | _IdentificarTiempo_                                                       | No firmado   | 0x00 –0xffff | Leer /     | 0x0000          | METRO           |   |
| entero de 16 bits | Escribir                                                                  |              |              |            |                 |                 |   |
|                   |                                                                           |              |              |            |                 |                 |   |
|                   | _**Atributo de la información del clúster de configuración de energía**_ |              |              |            |                 |                 |   |
|                   |                                                                           |              |              |            |                 |                 |   |
| **Identificador** | **Nombre**                                                                | **Tipo**     | **Rango**    | **Acceso** | **Por defecto** | **Obligatorio** |   |
| **/ Opcional**    |                                                                           |              |              |            |                 |                 |   |
|                   |                                                                           |              |              |            |                 |                 |   |
| 0x0035            | Máscara de alarma de batería                                              | mapa de bits | 0000 - 000x  | Leer /     | 0000 0000       | oh              |   |
| (8 bits)          | Escribir                                                                  |              |              |            |                 |                 |   |
|                   |                                                                           |              |              |            |                 |                 |   |

4
