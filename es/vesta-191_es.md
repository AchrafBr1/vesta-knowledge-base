# VESTA 191

**Controlador de relé ZigBee PRL-8ZBS(R)-AC-OTA**

**Introducción**

PRL-8ZBS-AC-OTA es un controlador de relé ZigBee que se puede conectar a dispositivos cableados y configurar en estado de apertura normal (N.O.) o cierre normal (N.C.). Después de unirse a la red ZigBee, el controlador de relé se puede controlar a través de la red ZigBee para activar los dispositivos conectados.

El controlador de relé utiliza tecnología ZigBee para la transmisión de señales inalámbricas. ZigBee es un protocolo de comunicación inalámbrica confiable, de bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir una gran cantidad de dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

El controlador de relé sirve como dispositivo final en la red ZigBee. Puede incluirse en la red ZigBee para transmitir o recibir señales, pero no puede permitir que ningún otro dispositivo ZigBee se una a la red a través del controlador de relé.

Los modelos con función de enrutador también sirven como enrutador en la red ZigBee. Después de ser incluido en la red ZigBee, permite que otros dispositivos ZigBee se unan a la red a través del Controlador de Relé.

**Identificación de piezas**

![](<.gitbook/assets/0 (78).jpeg>)

**1. Botón de función**

El botón de función se utiliza para restablecer el controlador de relé para unirse a una red ZigBee disponible.

Mantenga presionado el botón durante 10 segundos y luego suéltelo para restablecer el controlador de relé.

**2. Indicador LED (rojo)**

El indicador LED se utiliza para indicar el estado del relé:

-   Parpadea una vez: el relé se ha reiniciado.
-   Parpadea dos veces: el relé se ha unido exitosamente a una red ZigBee.
-   Parpadea una vez cada 20 minutos:
-   El Relay ha perdido la conexión a su red ZigBee actual.

**Terminales de conexión**

Conecte el cable al terminal, apriete el tornillo para cerrar la cortadora y mantenga el cable en su lugar. Desatornille para abrir el cortapelos y quitar el cable conectado al terminal.

1.  **Línea (entrada de CA)**
2.  **Neutral**
3.  **NO**

Para conexión normal abierta con el dispositivo.

1.  **Común**
2.  **CAROLINA DEL NORTE**

Para conexión normal cercana con el dispositivo

**8. Abrazadera de alivio de tensión**

La abrazadera se utiliza para asegurar los cables y proporcionar alivio de tensión para proteger los cables del recorte de metal.

**9. Hebilla de cableado**

La hebilla de cableado se utiliza para gestionar los cables.

1

**Especificación**

-   Fuente de alimentación (alimentación externa): 100-240 VCA
-   Salida de relé: relé SPDT libre de potencial, carga máxima de operación: 10 A (resistiva) a 24 V CC o 240 V CA
-   Cable trenzado: 14~22 CAE
-   Temperatura de funcionamiento: -10 °C a 45 °C (14 °F a 113 °F)
-   Humedad: Hasta 85% sin condensación
-   Dimensiones: 86 mm x 72 mm x 29 mm

![](<.gitbook/assets/1 (69).jpeg>)

**Entorno de instalación**

-   El controlador de relé debe instalarse en interiores, en un lugar seco.
-   Se recomienda instalar el dispositivo en una caja de distribución de plástico resistente al fuego.
-   No instale el dispositivo en una caja de distribución metálica para optimizar el alcance Z-Wave.

![](<.gitbook/assets/2 (63).jpeg>)

**Precaución**

-   Todos los trabajos en el dispositivo, incluida la instalación y el mantenimiento, deben ser realizados por un electricista calificado y autorizado.
-   Para evitar descargas eléctricas y/o daños al equipo, desconecte la energía eléctrica en el fusible principal o en el disyuntor antes de la instalación y el mantenimiento.

No conecte el dispositivo a cargas que excedan la corriente de carga admitida.

![](<.gitbook/assets/3 (56).jpeg>)

**Instalación**

El cableado del PRL solo debe realizarlo un técnico certificado con el conocimiento y la capacitación adecuados en equipos eléctricos. Conecte el relé de acuerdo con las instrucciones a continuación:

1.  Apague la fuente de alimentación antes de la conexión.
2.  Retire la cubierta superior y retire la abrazadera de alivio de tensión.
3.  Conecte los terminales L y N de la fuente de alimentación a los terminales de Línea y Neutro de PRL respectivamente a través del orificio de cableado.
4.  Dependiendo del dispositivo que desee controlar a través del relé, seleccione el terminal NO o NC y conecte el relé con el dispositivo para establecer una conexión de apertura normal o cierre normal con el dispositivo.
5.  Después de completar el cableado del dispositivo, reemplace la abrazadera de alivio de tensión, use la hebilla de cableado para administrar los cables y coloque la hebilla de cableado en la base con su espacio (abertura) colocado a la izquierda (como en el diagrama a continuación).

![](<.gitbook/assets/4 (54).jpeg>)

1.  Vuelva a colocar la cubierta superior. Encienda la fuente de alimentación para encender el controlador de relé.

2

**Configuración de red ZigBee**

![](<.gitbook/assets/5 (34).jpeg>)

-   _**Guía del dispositivo ZigBee**_

ZigBee es un protocolo de comunicación inalámbrica confiable, de bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir una gran cantidad de dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

![](<.gitbook/assets/6 (44).jpeg>)

-   _**Unirse a la red ZigBee**_

Como dispositivo ZigBee, el controlador de relé necesita unirse a una red ZigBee para recibir comandos. Siga los pasos a continuación para unir el controlador de relé a una red ZigBee.

-   1.  Conecte la entrada de alimentación al controlador de relé de acuerdo con las instrucciones de instalación anteriores y encienda el controlador de relé.
    2.  Mantenga presionado el botón de función durante 10 segundos mientras el controlador de relé se reinicia y comienza a buscar la red ZigBee existente. Asegúrese de que la función de permiso para unirse en el enrutador o coordinador de su red ZigBee esté habilitada.
    3.  Si el controlador de relé se une exitosamente a una red ZigBee, el indicador LED parpadeará dos veces para confirmar.
    4.  Después de unirse a la red ZigBee, el controlador de relé se registrará en la red automáticamente. Consulte el coordinador de la red ZigBee, el panel de control del sistema o el CIE (equipo de control e indicación) para confirmar si la inscripción y el registro se realizaron correctamente.
    5.  Después de unirse a la red ZigBee, si el controlador de relé pierde la conexión a la red ZigBee actual, el indicador LED parpadeará cada 20 minutos. Verifique la condición de su red ZigBee y el rango de señal del controlador de relé para corregir la condición.
-   _**Eliminación del dispositivo de la red ZigBee (restablecimiento de fábrica)**_

![](<.gitbook/assets/7 (39).png>)

Para eliminar el controlador de relé de la red ZigBee actual, se debe restablecer el dispositivo a los valores de fábrica para completar la eliminación del dispositivo. La función de restablecimiento de fábrica borrará la configuración y la información almacenadas del dispositivo y le pedirá que busque una nueva red ZigBee.

**Antes de retirar el dispositivo, asegúrese de que el controlador de relé esté dentro del rango de señal de red ZigBee actual.**

-   1.  Mantenga presionado el botón de función durante 10 segundos, luego suelte el botón para restablecer el controlador de relé.
    2.  Al reiniciarse, el dispositivo borrará la configuración de red ZigBee actual y transmitirá la señal al coordinador de ZigBee para eliminarse de la red ZigBee actual. Luego buscará activamente nuevamente la red ZigBee disponible y se unirá a la red automáticamente.
-   _**Actualización de firmware OTA (solo para la versión OTA)**_

El controlador de potencia admite la función de actualización de firmware OTA a través de la red ZigBee, que puede iniciarse desde el coordinador de red ZigBee. Siga los pasos a continuación para realizar la actualización del firmware OTA.

**Paso 1.**Debe acceder a su Coordinador ZigBee para realizar la actualización del firmware en el aire.

**Paso 2.**En la página web de configuración, seleccione el dispositivo que desea actualizar y seleccione el nuevo

Se proporciona firmware ZigBee. Consulte el Manual del usuario del Coordinador ZigBee para obtener más detalles.

**Paso 3.**Presione "OK" para iniciar el proceso de actualización y el LED seguirá parpadeando. Durante el proceso OTA, no realice ninguna otra acción ni apague el panel.

**Etapa 4.**La duración de una actualización tardará aproximadamente entre 20 y 30 minutos. Tenga en cuenta que la duración puede variar según el tamaño del archivo o la distancia entre su accesorio y el coordinador.

**Paso 5.**Espere a que el firmware complete la actualización. Cuando el progreso alcance el 100%, el dispositivo se reiniciará automáticamente. También puede actualizar la página web nuevamente para asegurarse de que el firmware del dispositivo se actualice correctamente y se muestre la versión más reciente.

![](<.gitbook/assets/8 (40).png>)

-   _**Capacidad del dispositivo enrutador ZigBee (solo PRL-8ZBSR-AC)**_

El modelo Relay Controller con función Router permite que otros dispositivos ZigBee se unan a la Red ZigBee a través del Router. Tiene una capacidad máxima de 40 dispositivos/enrutadores.

**Operación**

![](<.gitbook/assets/9 (29).jpeg>)

-   _**Control de relé**_
    -   Cuando el controlador de relé se haya unido exitosamente a una red ZigBee, la puerta de enlace/panel de control podrá controlarlo de forma remota para encenderlo, apagarlo o alternar entre la condición de encendido y apagado. Consulte su puerta de enlace/panel de control ZigBee para obtener más detalles.

3

**Apéndice (solo para desarrolladores)**

![](<.gitbook/assets/10 (40).png>)

-   _**ID del grupo de retransmisión**_

**ID del dispositivo: Activado Desactivado Salida: 0x0002**

**Punto final: 0x0A**

| **Lado del servidor**                                           |                   |                               |                   |                        |              |          |                |                      |            |                 |                 | **Lado del cliente** |                 |   |   |
| --------------------------------------------------------------- | ----------------- | ----------------------------- | ----------------- | ---------------------- | ------------ | -------- | -------------- | -------------------- | ---------- | --------------- | --------------- | -------------------- | --------------- | - | - |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   | **Obligatorio**        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| Básico (0x0000)                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      | _Ninguno_       |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| Identificar(0x0003)                                             |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| Activado/Desactivado(0x0006)                                    |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   | **Opcional**           |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| Grupos(0x0004)                                                  |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      | Ninguno         |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| _**Atributo de información básica del clúster**_               |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| **Identificador**                                               |                   | **Nombre**                    | **Tipo**          |                        | **Rango**    |          | **Acceso**     | **Por defecto**      |            | **Obligatorio** |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   | **/ Opcional**         |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| 0x0000                                                          |                   | _Versión ZCL_                 | 8 bits sin firmar |                        | 0x00 –0xff   |          | Leer           | 0x01                 |            | METRO           |                 |                      |                 |   |   |
|                                                                 | entero            |                               |                   | solo                   |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| 0x0001                                                          |                   | Versión de la aplicación      | 8 bits sin firmar |                        | 0x00 – 0xff  |          | Leer           | 0x00                 |            | oh              |                 |                      |                 |   |   |
|                                                                 | entero            |                               |                   | solo                   |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| 0x0003                                                          |                   | _Versión HW_                  | 8 bits sin firmar |                        | 0x00 –0xff   |          | Leer           | 0                    |            | oh              |                 |                      |                 |   |   |
|                                                                 | entero            |                               |                   | solo                   |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| 0x0004                                                          |                   | _Nombre del Fabricante_       | Personaje         |                        | 0 – 32 bytes |          | Leer           | Clímax               |            | oh              |                 |                      |                 |   |   |
|                                                                 | Cadena            |                               |                   | solo                   | Tecnología   |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| 0x0005                                                          |                   | _Identificador de modelo_     | Personaje         |                        | 0 – 32 bytes |          | Leer           | (Versión del modelo) |            | oh              |                 |                      |                 |   |   |
|                                                                 | Cadena            |                               |                   | solo                   |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| 0x0006                                                          |                   | _Código de fecha_             | Personaje         |                        | 0 – 16 bytes |          | Leer           |                      |            | oh              |                 |                      |                 |   |   |
|                                                                 | Cadena            |                               |                   | solo                   |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| 0x0007                                                          |                   | _Fuente de alimentación_      | 8 bits            |                        | 0x00 –0xff   |          | Leer           |                      |            | METRO           |                 |                      |                 |   |   |
|                                                                 |                   |                               | solo              |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| 0x0010                                                          |                   | _Descripción de la ubicación_ | Personaje         |                        | 0 – 32 bytes |          | Leer /         |                      |            | oh              |                 |                      |                 |   |   |
|                                                                 | Cadena            |                               |                   | Escribir               |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| 0x0011                                                          |                   | _Entorno físico_              | 8 bits            |                        | 0x00 –0xff   |          | Leer /         | 0x00                 |            | oh              |                 |                      |                 |   |   |
|                                                                 |                   |                               | Escribir          |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| 0x0012                                                          |                   | _Dispositivo habilitado_      | Booleano          |                        | 0x00 –0x01   |          | Leer /         | 0x01                 |            | METRO           |                 |                      |                 |   |   |
|                                                                 |                   |                               | Escribir          |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| _**Atributo de información de identificación del clúster**_    |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| **Identificador**                                               |                   | **Nombre**                    | **Tipo**          |                        | **Rango**    |          | **Acceso**     | **Por defecto**      |            | **Obligatorio** |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   | **/ Opcional**         |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| 0x0000                                                          |                   | _IdentificarTiempo_           | No firmado        |                        | 0x00 –0xffff |          | Leer /         | 0x0000               |            | METRO           |                 |                      |                 |   |   |
|                                                                 | entero de 16 bits |                               |                   | Escribir               |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| _**Atributo de información del clúster activado/desactivado**_ |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| **Identificador**                                               |                   | **Nombre**                    | **Tipo**          |                        | **Rango**    |          | **Acceso**     | **Por defecto**      |            | **Obligatorio** |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   | **/ Opcional**         |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| 0x0000                                                          |                   | _Encendido apagado_           | Booleano          |                        | 0x00 –0x01   |          | Leer           | 0x00                 |            | METRO           |                 |                      |                 |   |   |
|                                                                 |                   |                               | solo              |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| _**Atributos de la información del clúster Grupos**_           |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| **Identificador**                                               |                   | **Nombre**                    |                   | **Tipo**               |              |          | **Rango**      |                      | **Acceso** |                 | **Por defecto** |                      | **Obligatorio** |   |   |
|                                                                 |                   |                               |                   |                        |              |          | **/ Opcional** |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |
| 0x0000                                                          |                   | _NombreSoporte_               |                   | mapa de bits de 8 bits |              | x0000000 |                | Leer                 |            | -               |                 | METRO                |                 |   |   |
|                                                                 |                   |                               |                   |                        | solo         |          |                |                      |            |                 |                 |                      |                 |   |   |
|                                                                 |                   |                               |                   |                        |              |          |                |                      |            |                 |                 |                      |                 |   |   |

![](<.gitbook/assets/11 (31).png>)![](<.gitbook/assets/12 (35).png>)![](<.gitbook/assets/13 (26).png>)

4
