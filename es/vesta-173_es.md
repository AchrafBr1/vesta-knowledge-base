# VESTA 173

**RSB-1ZBS**

**Bombilla inteligente RGBW**

**Introducción**

![](<.gitbook/assets/0 (64).jpeg>)

La RSB-1ZBS es una bombilla LED de color inteligente ZigBee. Cuenta con ajuste multicolor y control de nivel de luz. Cuando se une a una red ZigBee, el usuario podrá controlar Light Bulb de forma remota desde el coordinador de la red ZigBee.

La bombilla utiliza tecnología ZigBee para la transmisión de señales inalámbricas. ZigBee es un protocolo de comunicación inalámbrica confiable, de bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir en una red una gran cantidad de dispositivos y coordinarlos para el intercambio de datos y la transmisión de señales.

La bombilla también sirve como ruta en la red ZigBee. Después de ser incluido en la red ZigBee, permite que otros dispositivos ZigBee se unan a la red a través de Light Bulb.

**Configuración de red ZigBee**

![](<.gitbook/assets/1 (57).jpeg>)

-   _**Guía del dispositivo ZigBee**_

ZigBee es un protocolo de comunicación inalámbrica confiable, de bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir una gran cantidad de dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

Debido a la estructura fundamental de la red ZigBee, el dispositivo ZigBee buscará y se unirá activamente a la red después de encenderse.

-   -   Asegúrese de que su enrutador o coordinador de red ZigBee esté encendido antes de encender el dispositivo ZigBee.
    -   Asegúrese de que su enrutador o coordinador de red ZigBee esté encendido y dentro del alcance mientras un dispositivo ZigBee esté en uso.
    -   No retire un dispositivo ZigBee del enrutador o coordinador de red ZigBee sin apagar el dispositivo ZigBee.
-   _**Unirse a la red ZigBee**_

![](<.gitbook/assets/2 (52).jpeg>)

Como dispositivo ZigBee, Light Bulb necesita unirse a una red ZigBee para enviar y recibir señales de comando. Siga los pasos a continuación para agregar la bombilla a la red ZigBee.

Paso 1. Introduzca la bombilla en el portalámparas. No suministre energía todavía.

Paso 2. Habilite la función de permiso de unión en el enrutador o coordinador de su red ZigBee.

Paso 3. Enciende la bombilla durante 3~5 segundos. (No más de 5 segundos), luego apáguelo.

Paso 4. Repita el Paso 3 tres (3) veces para un total de cuatro (4) ciclos de ENCENDIDO/APAGADO.

Paso 5. Encienda la bombilla por quinta vez, el dispositivo se reiniciará y comenzará a buscar una nueva red ZigBee.

Paso 6. Después de unirse a la red ZigBee, la bombilla se registrará automáticamente en el sistema de seguridad de la red. Consulte con el coordinador de la red ZigBee, el panel de control del sistema o el CIE (equipo de control e indicación) para confirmar si la unión y el registro se realizaron correctamente.

![](<.gitbook/assets/3 (61).png>)![](<.gitbook/assets/4 (46).jpeg>)

-   _**Eliminación del dispositivo de la red ZigBee (restablecimiento de fábrica)**_

Para eliminar la bombilla de la red ZigBee actual, el dispositivo debe colocarse en Restablecimiento de fábrica para completar la eliminación del dispositivo. La función de restablecimiento de fábrica borrará la configuración y la información almacenadas de la bombilla y le solicitará que busque una nueva red ZigBee.

**Antes de retirar el dispositivo, asegúrese de que la bombilla esté dentro del rango de señal de red ZigBee actual.**

1.  Elimina la bombilla del panel de control/CIE actual.
2.  Apague la bombilla.
3.  Encender la bombilla para 3~5 segundos. (No más de 5 segundos), luego apáguelo.
4.  Repita el paso 3 3 veces para un total de 4 ciclos de encendido/apagado.
5.  Encienda la bombilla por quinta vez, el dispositivo se reiniciará y comenzará a buscar una nueva red ZigBee.
6.  Al reiniciarse, la bombilla borrará la configuración actual de la red ZigBee y transmitirá la señal al coordinador ZigBee para eliminarse de la red ZigBee actual. Luego buscará activamente nuevamente la red ZigBee disponible y se unirá a la red automáticamente.

1

![](<.gitbook/assets/5 (29).jpeg>)![](<.gitbook/assets/6 (39).jpeg>)

-   _**Capacidad del dispositivo enrutador ZigBee**_

La función Bombilla con enrutador permite que otros dispositivos ZigBee se unan a la red ZigBee a través del enrutador. Light Bulb tiene una capacidad máxima de 7 dispositivos, incluidos 4 enrutadores.

**Características**

![](<.gitbook/assets/7 (35).png>)

-   _**Ajuste de color y saturación**_

El color y la saturación de la bombilla se pueden ajustar desde los coordinadores ZigBee de forma remota mediante el envío de comandos.

![](<.gitbook/assets/8 (38).png>)

-   _**Ajuste del nivel de luz**_

La Bombilla tiene iluminación regulable, el porcentaje de luz se puede ajustar desde los Coordinadores ZigBee de forma remota mediante el envío de comandos.

![](<.gitbook/assets/9 (36).png>)

-   _**Supervisión**_

La bombilla transmitirá una señal de supervisión para informar su condición periódicamente según la configuración del usuario. El intervalo predeterminado de fábrica es de 10 minutos.

**Apéndice (solo para desarrolladores)**

![](<.gitbook/assets/10 (37).png>)

-   _**ID del grupo de bombillas**_

**ID del dispositivo: Color_Regulable_Luz: 0x0102**

**Punto final: 0x01**

| **Lado del servidor**    |                                                            |                                                           | **Lado del cliente** |           |   |   |
| ------------------------ | ---------------------------------------------------------- | --------------------------------------------------------- | -------------------- | --------- | - | - |
|                          |                                                            |                                                           |                      |           |   |   |
|                          |                                                            | **Obligatorio**                                           |                      |           |   |   |
|                          |                                                            |                                                           |                      |           |   |   |
| Básico (0x0000)          |                                                            |                                                           |                      | _Ninguno_ |   |   |
|                          |                                                            |                                                           |                      |           |   |   |
| Identificar(0x0003)      |                                                            |                                                           |                      |           |   |   |
|                          |                                                            |                                                           |                      |           |   |   |
| Grupos(0x0004)           |                                                            |                                                           |                      |           |   |   |
|                          |                                                            |                                                           |                      |           |   |   |
| Escenas (0x0005)         |                                                            |                                                           |                      |           |   |   |
|                          |                                                            |                                                           |                      |           |   |   |
| EncendidoApagado(0x0006) |                                                            |                                                           |                      |           |   |   |
|                          |                                                            |                                                           |                      |           |   |   |
| Control de nivel(0x0008) |                                                            |                                                           |                      |           |   |   |
|                          |                                                            |                                                           |                      |           |   |   |
| Control de color(0x0300) |                                                            |                                                           |                      |           |   |   |
|                          |                                                            |                                                           |                      |           |   |   |
|                          |                                                            | **Opcional**                                              |                      |           |   |   |
|                          |                                                            |                                                           |                      |           |   |   |
| _Ninguno_                |                                                            |                                                           |                      | _Ninguno_ |   |   |
|                          |                                                            |                                                           |                      |           |   |   |
|                          |                                                            |                                                           |                      |           |   |   |
| **Grupo de informes**    |                                                            | Encendido/Apagado (0x0006)                                |                      |           |   |   |
| **Atributo del informe** |                                                            | ATRID_EN_APAGADO (0x0000)                                 |                      |           |   |   |
| **Tipo de datos**        |                                                            | ZCL_TIPO DE DATOS_BOOLEANO                                |                      |           |   |   |
| **minReporteInt**        |                                                            | 0                                                         |                      |           |   |   |
| **maxReportInt**         |                                                            | valor predeterminado: 0x258 seg (600 seg)                 |                      |           |   |   |
|                          |                                                            |                                                           |                      |           |   |   |
| **Grupo de informes**    |                                                            | Control de nivel (0x0008)                                 |                      |           |   |   |
| **Atributo del informe** |                                                            | ATRID_NIVEL_ACTUAL_NIVEL (0x0000)                         |                      |           |   |   |
| **Tipo de datos**        |                                                            | ZCL_TIPO DE DATOS_WINT8                                   |                      |           |   |   |
| **minReporteInt**        |                                                            | 0                                                         |                      |           |   |   |
| **maxReportInt**         |                                                            | valor predeterminado: 0x258 seg (600 seg)                 |                      |           |   |   |
|                          |                                                            |                                                           |                      |           |   |   |
| **Grupo de informes**    |                                                            | Control de color (0x0300)                                 |                      |           |   |   |
| **Atributo del informe** |                                                            | ATRID_ENCENDIENDO_COLOR_CONTROL_ACTUAL_TONALIDAD (0x0000) |                      |           |   |   |
| **Tipo de datos**        |                                                            | ZCL_TIPO DE DATOS_WINT8                                   |                      |           |   |   |
|                          | ATRID_ENCENDIENDO_COLOR_CONTROL_ACTUAL_SATURACIÓN (0x0001) |                                                           |                      |           |   |   |
|                          |                                                            |                                                           |                      |           |   |   |
| **Tipo de datos**        |                                                            | ZCL_TIPO DE DATOS_WINT8                                   |                      |           |   |   |
|                          | ATRID_ENCENDIENDO_COLOR_CONTROL_COLOR_TEMPERATURA (0x0007) |                                                           |                      |           |   |   |
|                          |                                                            |                                                           |                      |           |   |   |
| **Tipo de datos**        |                                                            | ZCL_TIPO DE DATOS_UINT16                                  |                      |           |   |   |
| **minReporteInt**        |                                                            | 0                                                         |                      |           |   |   |
| **maxReportInt**         |                                                            | valor predeterminado: 0x258 seg (600 seg)                 |                      |           |   |   |
|                          |                                                            | 2                                                         |                      |           |   |   |

![](<.gitbook/assets/11 (22).jpeg>)![](<.gitbook/assets/12 (18).jpeg>)

-   ![](<.gitbook/assets/13 (25).png>)_**Atributo de información básica del clúster**_

| **Identificador**                                            | **Nombre**                    | **Tipo**          | **Rango**    | **Acceso**    | **Por defecto**   | **Obligatorio** |   |
| ------------------------------------------------------------ | ----------------------------- | ----------------- | ------------ | ------------- | ----------------- | --------------- | - |
| **/ Opcional**                                               |                               |                   |              |               |                   |                 |   |
|                                                              |                               |                   |              |               |                   |                 |   |
| 0x0000                                                       | _Versión ZCL_                 | 8 bits sin firmar | 0x00 –0xff   | Solo lectura  | 0x01              | METRO           |   |
| entero                                                       |                               |                   |              |               |                   |                 |   |
|                                                              |                               |                   |              |               |                   |                 |   |
| 0x0003                                                       | Versión HW                    | 8 bits sin firmar | 0x00 –0xff   | Solo lectura  | 0                 | oh              |   |
| entero                                                       |                               |                   |              |               |                   |                 |   |
|                                                              |                               |                   |              |               |                   |                 |   |
| 0x0004                                                       | _Nombre del Fabricante_       | Personaje         | 0 – 32 bytes | Solo lectura  | Tecnología Clímax | oh              |   |
| Cadena                                                       |                               |                   |              |               |                   |                 |   |
|                                                              |                               |                   |              |               |                   |                 |   |
| 0x0005                                                       | _Identificador de modelo_     | Personaje         | 0 – 32 bytes | Solo lectura  | SLCB_00.00.03.01  | oh              |   |
| Cadena                                                       | TC                            |                   |              |               |                   |                 |   |
|                                                              |                               |                   |              |               |                   |                 |   |
| 0x0006                                                       | _Código de fecha_             | Personaje         | 0 – 16 bytes | Solo lectura  | 20170124          | oh              |   |
| Cadena                                                       |                               |                   |              |               |                   |                 |   |
|                                                              |                               |                   |              |               |                   |                 |   |
| 0x0007                                                       | _Fuente de alimentación_      | 8 bits            | 0x00 –0xff   | Solo lectura  |                   | METRO           |   |
| Enumeración                                                  |                               |                   |              |               |                   |                 |   |
|                                                              |                               |                   |              |               |                   |                 |   |
| 0x0010                                                       | _Descripción de la ubicación_ | Personaje         | 0 – 32 bytes | Leer escribir |                   | oh              |   |
| cadena                                                       |                               |                   |              |               |                   |                 |   |
|                                                              |                               |                   |              |               |                   |                 |   |
| 0x0011                                                       | _Entorno físico_              | 8 bits            | 0x00 –0xff   | Leer escribir | 0x00              | oh              |   |
| Enumeración                                                  |                               |                   |              |               |                   |                 |   |
|                                                              |                               |                   |              |               |                   |                 |   |
| 0x0012                                                       | _Dispositivo habilitado_      | Booleano          | 0x00 –0x01   | Leer escribir | 0x01              | METRO           |   |
| _**Atributo de información de identificación del clúster**_ |                               |                   |              |               |                   |                 |   |

![](<.gitbook/assets/14 (20).png>)

| **Identificador**                                 | **Nombre**          | **Tipo**   | **Rango**    | **Acceso**    | **Por defecto** | **Obligatorio /** |   |
| ------------------------------------------------- | ------------------- | ---------- | ------------ | ------------- | --------------- | ----------------- | - |
| **Opcional**                                      |                     |            |              |               |                 |                   |   |
|                                                   |                     |            |              |               |                 |                   |   |
| 0x0000                                            | _IdentificarTiempo_ | No firmado | 0x00 –0xffff | Leer escribir | 0x0000          | METRO             |   |
| entero de 16 bits                                 |                     |            |              |               |                 |                   |   |
|                                                   |                     |            |              |               |                 |                   |   |
| _**Atributo de información del grupo de grupo**_ |                     |            |              |               |                 |                   |   |

![](<.gitbook/assets/15 (19).png>)

| **Identificador**                                               | **Nombre**               |                             |                            |                  |                        | **Tipo**               |          |              |             | **Rango**    |                |                | **Acceso**   |              |                 | **Por defecto** | **Obligatorio /** |                   |       |   |   |   |   |   |   |
| --------------------------------------------------------------- | ------------------------ | --------------------------- | -------------------------- | ---------------- | ---------------------- | ---------------------- | -------- | ------------ | ----------- | ------------ | -------------- | -------------- | ------------ | ------------ | --------------- | --------------- | ----------------- | ----------------- | ----- | - | - | - | - | - | - |
|                                                                 |                          |                             |                            |                  |                        |                        |          |              |             |              |                | **Opcional**   |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
|                                                                 |                          |                             |                            |                  |                        |                        |          |              |             |              |                |                |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
| 0x0000                                                          | _NombreSoporte_          |                             |                            |                  | mapa de bits de 8 bits |                        |          | X0000000     |             | Solo lectura |                |                |              | -            |                 | METRO           |                   |                   |       |   |   |   |   |   |   |
| _**Atributo de información del grupo de escenas**_             |                          |                             |                            |                  |                        |                        |          |              |             |              |                |                |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
| **Identificador**                                               | **Nombre**               |                             |                            |                  |                        | **Tipo**               |          |              |             | **Rango**    |                |                | **Acceso**   |              | **Por defecto** |                 | **Obligatorio**   |                   |       |   |   |   |   |   |   |
|                                                                 |                          |                             |                            |                  |                        |                        |          |              |             |              | **/ Opcional** |                |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
|                                                                 |                          |                             |                            |                  |                        |                        |          |              |             |              |                |                |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
| 0x0000                                                          | _Recuento de escenas_    |                             | Entero de 8 bits sin signo |                  | 0x00 – 0xff            |                        |          | Solo lectura |             | 0x00         |                | METRO          |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
| 0x0001                                                          | _Escena actual_          |                             | Entero de 8 bits sin signo |                  | 0x00 – 0xff            |                        |          | Solo lectura |             | 0x00         |                | METRO          |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
| 0x0002                                                          | _Grupo actual_           | Entero de 16 bits sin signo |                            | 0x0000 – 0xfff7  |                        | Solo lectura           |          | 0x00         |             | METRO        |                |                |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
| 0x0003                                                          | _Escena válida_          |                             |                            |                  |                        | Booleano               |          |              |             | 0x00 – 0x01  |                |                | Solo lectura |              | 0x00            |                 | METRO             |                   |       |   |   |   |   |   |   |
| 0x0004                                                          | _NombreSoporte_          |                             |                            |                  |                        | mapa de bits de 8 bits |          |              |             | X0000000     |                |                | Solo lectura |              | -               |                 | METRO             |                   |       |   |   |   |   |   |   |
| _**Atributo de información del clúster activado/desactivado**_ |                          |                             |                            |                  |                        |                        |          |              |             |              |                |                |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
| **Identificador**                                               | **Nombre**               |                             |                            |                  |                        | **Tipo**               |          |              |             |              | **Rango**      |                |              |              | **Acceso**      |                 | **Por defecto**   | **Obligatorio /** |       |   |   |   |   |   |   |
|                                                                 |                          |                             |                            |                  |                        |                        |          |              |             |              |                |                | **Opcional** |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
|                                                                 |                          |                             |                            |                  |                        |                        |          |              |             |              |                |                |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
| 0x0000                                                          | _Encendido apagado_      |                             |                            |                  |                        | Booleano               |          |              | 0x00 – 0x01 |              |                | Solo lectura   |              | 0x00         |                 | METRO           |                   |                   |       |   |   |   |   |   |   |
| _**Atributo de información del grupo de control de nivel**_    |                          |                             |                            |                  |                        |                        |          |              |             |              |                |                |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
| **Identificador**                                               | **Nombre**               |                             |                            |                  |                        | **Tipo**               |          |              |             | **Rango**    |                |                | **Acceso**   |              | **Por defecto** |                 | **Obligatorio**   |                   |       |   |   |   |   |   |   |
|                                                                 |                          |                             |                            |                  |                        |                        |          |              |             |              | **/ Opcional** |                |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
|                                                                 |                          |                             |                            |                  |                        |                        |          |              |             |              |                |                |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
| 0x0000                                                          | _Nivel actual_           |                             | Entero de 8 bits sin signo |                  | 0x00 – 0xff            |                        |          | Solo lectura |             | 0x00         |                | METRO          |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
| _**Atributo de información del grupo de control de color**_    |                          |                             |                            |                  |                        |                        |          |              |             |              |                |                |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
| **Identificador**                                               | **Nombre**               |                             |                            |                  |                        | **Tipo**               |          |              |             | **Rango**    |                |                |              | **Acceso**   |                 | **Por defecto** |                   | **Obligatorio**   |       |   |   |   |   |   |   |
|                                                                 |                          |                             |                            |                  |                        |                        |          |              |             |              |                | **/ Opcional** |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
|                                                                 |                          |                             |                            |                  |                        |                        |          |              |             |              |                |                |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
| 0x0000                                                          | _Tono actual_            |                             |                            |                  |                        | No firmado             |          |              |             | 0x00 – 0xff  |                |                |              | Solo lectura |                 |                 | 0x00              |                   | METRO |   |   |   |   |   |   |
|                                                                 |                          |                             |                            | entero de 8 bits |                        |                        |          |              |             |              |                |                |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
|                                                                 |                          |                             |                            |                  |                        |                        |          |              |             |              |                |                |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
| 0x0001                                                          | _Saturación actual_      |                             |                            |                  | No firmado             |                        |          |              | 0x00 – 0xfe |              |                |                | Solo lectura |              |                 | 0x00            |                   | METRO             |       |   |   |   |   |   |   |
|                                                                 |                          |                             | entero de 8 bits           |                  |                        |                        |          |              |             |              |                |                |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
|                                                                 |                          |                             |                            |                  |                        |                        |          |              |             |              |                |                |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
| 0x0007                                                          | _ColorTemperaturaMireds_ |                             | No firmado                 |                  |                        |                        | 0x0000 – |              |             |              | Solo lectura   | 0x00fa (4000K) |              | METRO        |                 |                 |                   |                   |       |   |   |   |   |   |   |
|                                                                 | entero de 16 bits        |                             |                            |                  | 0xfeff                 |                        |          |              |             |              |                |                |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
|                                                                 |                          |                             |                            |                  |                        |                        |          |              |             |              |                |                |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
| 0x0008                                                          | _Modo de color_          |                             |                            |                  |                        | 8 bits                 |          |              | 0x00 – 0x02 |              | Solo lectura   |                |              | 0x01         |                 | METRO           |                   |                   |       |   |   |   |   |   |   |
|                                                                 |                          |                             |                            | enumeración      |                        |                        |          |              |             |              |                |                |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |
|                                                                 |                          |                             |                            |                  |                        |                        |          |              |             |              |                |                |              |              |                 |                 |                   |                   |       |   |   |   |   |   |   |

![](<.gitbook/assets/16 (22).png>)![](<.gitbook/assets/17 (18).png>)![](<.gitbook/assets/18 (22).png>)![](<.gitbook/assets/19 (23).png>)

3
