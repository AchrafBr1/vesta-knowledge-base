# VESTA 184

**Sensor de habitación RS-23ZBS**V: R3

**Introducción**

RS-23ZBS es un sensor de habitación ZigBee. Cuenta con función de detección de temperatura y humedad para monitorear los entornos de su hogar. La información de temperatura y humedad se transmitirá al coordinador en la red ZigBee y se mostrará en la pantalla LCD del Room Sensor.

El sensor de habitación utiliza tecnología ZigBee para la transmisión de señales inalámbricas. ZigBee es un protocolo de comunicación inalámbrica confiable, de bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir en una red una gran cantidad de dispositivos y coordinarlos para el intercambio de datos y la transmisión de señales.

El Room Sensor sirve como dispositivo final en la red ZigBee. Puede incluirse en la red ZigBee para transmitir señal tras la activación, pero no puede permitir que ningún otro dispositivo ZigBee se una a la red a través del sensor de habitación.

![](<.gitbook/assets/0 (72).jpeg>)

**Identificación de piezas**

**1. Pantalla LCD**

La pantalla LCD muestra la siguiente información:

-   -   Temperatura en grados Fahrenheit / Celsius
    -   % de humedad relativa.
    -   Conectividad de red ZigBee (![](<.gitbook/assets/1 (64).jpeg>)icono).
    -   Estado de batería baja (icono).
    -   Retroiluminación LCD encendida: cuando se presiona el botón de función.

1.  **Botón de función**
    -   Presione el botón una vez para:

Envía una señal de supervisión con información de temperatura/humedad. Enciende la luz de fondo de la pantalla LCD durante 10 segundos.

-   -   Mantenga presionado durante 10 segundos y luego suéltelo para restablecer el sensor de habitación.

1.  **Tornillo de base (abrir/cerrar cubierta)**

![](<.gitbook/assets/2 (58).jpeg>)

Cuando la cubierta frontal esté instalada en la cubierta posterior, ábrala aflojando el tornillo de la base y ciérrela de la misma manera.

1.  **Puente de ajuste Fahrenheit/Celcius (JP1)**
    -   Si el puente se inserta entre los 2 pines superiores, la pantalla LCD mostrará la temperatura en grados Celsius. (**Predeterminado de fábrica**)
    -   Si el puente se inserta entre los 2 pines inferiores, la pantalla LCD mostrará la temperatura en Fahrenheit.
2.  **Compartimiento de la batería**

![](<.gitbook/assets/3 (64).png>)

El sensor de habitación funciona con dos pilas alcalinas AA de 1,5 V.

1.  **Contraportada**
2.  **Perforaciones para montaje en pared**

**Características**

-   _**Detección de temperatura y humedad**_
    -   El sensor de habitación transmitirá señales de temperatura y humedad periódicamente según la configuración. El intervalo predeterminado de fábrica es de 10 minutos.
    -   Cuando la temperatura cambia +/- 2°C, o la humedad cambia +/- 10%, el sensor de habitación también transmitirá una señal.
    -   El nivel de cambio requerido para activar la transmisión de señal se puede programar usando el comando ZigBee Configure Reporting – parámetro de cambio reportable. Los valores predeterminados son: Temperatura:**200**por 2°C.

Humedad:**1000**por el 10%.

1

-   -   También puede presionar el botón de función una vez para transmitir una señal de temperatura y humedad manualmente.
    -   El rango de detección de temperatura es de aproximadamente -10 °C - 50 °C (14 °F - 122 °F).
    -   El rango de detección de humedad es aproximadamente del 10 % al 90 % de humedad relativa.
-   _**Detección de batería y batería baja**_
    -   El sensor de habitación utiliza dos pilas alcalinas de 1,5 V como fuente de alimentación. Las baterías están incluidas en el paquete.
    -   El sensor de habitación cuenta con la función de detección de batería baja. Cuando el voltaje de la batería es bajo, el sensor de habitación transmitirá una señal de batería baja para notificar al usuario y mostrar el icono de batería baja en la pantalla LCD.
    -   Al cambiar las baterías, después de quitar las baterías viejas, presione el botón de función dos veces para descargarlas por completo antes de insertar baterías nuevas.
-   _**Supervisión**_

El sensor de habitación transmitirá una señal de supervisión junto con la señal de temperatura y humedad para informar su condición periódicamente. El intervalo predeterminado de fábrica es de 10 minutos, que se puede ajustar según la configuración.

**Configuración de red ZigBee**

-   _**Guía del dispositivo ZigBee**_

ZigBee es un protocolo de comunicación inalámbrica confiable, de bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir una gran cantidad de dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

Debido a la estructura fundamental de la red ZigBee, el dispositivo ZigBee buscará y se unirá activamente a la red después de encenderse. Dado que realizar una tarea al conectarse a la red puede consumir algo de energía, es necesario seguir las instrucciones para evitar agotar la batería de un dispositivo ZigBee.

-   -   Asegúrese de que su enrutador o coordinador de red ZigBee esté encendido antes de insertar la batería en el dispositivo ZigBee.
    -   Asegúrese de que el enrutador o coordinador de red ZigBee esté encendido y dentro del alcance mientras un dispositivo ZigBee esté en uso.
    -   No retire un dispositivo ZigBee del enrutador o coordinador de red ZigBee sin quitar la batería del dispositivo ZigBee.
-   _**Unirse a la red ZigBee**_

Como dispositivo ZigBee, el sensor de habitación necesita unirse a una red ZigBee para transmitir señales de temperatura y humedad. Siga los pasos a continuación para unir el sensor de habitación a la red ZigBee.

-   1.  Inserte las baterías en el compartimiento de baterías para encender el sensor de habitación.
    2.  Después de encenderlo, presione y mantenga presionado el botón Función durante 10 segundos, luego suéltelo para unirse a la red. Asegúrese de que la función de permiso de unión en el enrutador o coordinador de su red ZigBee esté habilitada.
    3.  Si el sensor de habitación se une con éxito a una red ZigBee, el icono de conectividad de red ZigBee se mostrará en la pantalla LCD.
    4.  Después de unirse a la red ZigBee, el sensor de habitación se registrará en la red automáticamente. Consulte con su coordinador ZigBee, panel de control del sistema o CIE (Equipo de control e indicación) para confirmar si la inscripción y el registro se realizaron correctamente.
    5.  Después de unirse a la red y el registro se realiza correctamente, si el sensor de habitación pierde la conexión con el panel de control o el panel de control se apaga, el ícono de conectividad de red ZigBee en la pantalla LCD del sensor de habitación se apagará en 1 o 2 minutos.
    6.  Si la conexión y el registro de la red no se realizan correctamente, no se mostrará el icono de conectividad de red ZigBee. Verifique su coordinador de red ZigBee, panel de control o configuración CIE para asegurarse de que la función de permiso de unión esté disponible y luego use la función de restablecimiento de fábrica a continuación para unirse a la red ZigBee.
-   _**Eliminación del dispositivo de la red ZigBee (restablecimiento de fábrica)**_

Para eliminar el sensor de habitación de la red ZigBee actual, se debe restablecer el dispositivo a los valores de fábrica para completar la eliminación del dispositivo. La función de restablecimiento de fábrica borrará la información de configuración almacenada del dispositivo y solicitará al sensor de habitación que busque una nueva red ZigBee.

**Antes de retirar el dispositivo, asegúrese de que el sensor de habitación esté dentro del rango de señal de red ZigBee actual.**

1.  Mantenga presionado el botón de función durante 10 segundos, luego suelte el botón para restablecer el sensor de habitación.
2.  Al reiniciarse, el sensor de habitación borrará la configuración de red ZigBee actual y transmitirá la señal a

2

El coordinador de ZigBee se eliminará de la red ZigBee actual. Luego buscará activamente nuevamente la red ZigBee disponible y se unirá a la red automáticamente.

**Instalación**

-   _**Montaje del sensor de habitación**_

Para obtener la mejor calidad de pantalla LCD, el sensor de habitación debe montarse en una ubicación aproximadamente 5° por encima del nivel de los ojos.

-   Montaje con tornillos.

Al realizar el montaje con tornillos, asegúrese de utilizar únicamente los tornillos proporcionados en el paquete por el fabricante original, ya que tornillos inadecuados pueden dañar el interior del dispositivo.

-   1.  Retire la cubierta frontal con un destornillador.
    2.  Rompe los agujeros ciegos en la contraportada.
    3.  Usando los agujeros como plantilla, taladre agujeros en la superficie.
    4.  Inserte los tacos de pared si se fija en yeso o ladrillo.
    5.  Atornille la cubierta trasera a los tacos de pared.
    6.  Vuelva a atornillar la cubierta frontal a la cubierta trasera.
-   _**Uso del sensor de habitación con el enrutador ZigBee**_

_**NOTA IMPORTANTE**_

Si la ubicación de instalación del sensor de habitación está lejos del panel de control de su sistema y requiere enrutadores ZigBee para mejorar la intensidad de la señal.**NO**Utilice un enrutador ZigBee sin batería de respaldo. Un enrutador ZigBee sin batería se apagará durante un corte de energía de CA y el sensor de habitación conectado al enrutador perderá la conexión con la red ZigBee. Debe planificar la ubicación de instalación del sensor de habitación utilizando únicamente un enrutador ZigBee con batería de respaldo.

**Apéndice (solo para desarrolladores).**

-   _**ID del grupo de sensores de habitación**_

**ID del dispositivo: Sensor de temperatura 0x0302**

**Punto final: 0x01**

| **Lado del servidor**                 |                 | **Lado del cliente** |
| ------------------------------------- | --------------- | -------------------- |
|                                       |                 |                      |
|                                       | **Obligatorio** |                      |
|                                       |                 |                      |
| Básico (0x0000)                       |                 | _Ninguno_            |
|                                       |                 |                      |
| Identificar(0x0003)                   |                 |                      |
|                                       |                 |                      |
|                                       | **Opcional**    |                      |
|                                       |                 |                      |
| Configuración de energía (0x0001)     |                 | _Ninguno_            |
|                                       |                 |                      |
| Medición de temperatura (0x0402)      |                 |                      |
|                                       |                 |                      |
| Medición de humedad relativa (0x0405) |                 |                      |
|                                       |                 |                      |

|                  | _**Atributo de información básica del clúster**_ |            |   |              |              |                 |                 |   |   |
| ----------------- | ------------------------------------------------ | ---------- | - | ------------ | ------------ | --------------- | --------------- | - | - |
|                   |                                                  |            |   |              |              |                 |                 |   |   |
| **Identificador** | **Nombre**                                       | **Tipo**   |   | **Rango**    | **Acceso**   | **Por defecto** | **Obligatorio** |   |   |
|                   | **/ Opcional**                                   |            |   |              |              |                 |                 |   |   |
|                   |                                                  |            |   |              |              |                 |                 |   |   |
| 0x0000            | _Versión ZCL_                                    | No firmado |   | 0x00 –0xff   | Solo lectura | 0x01            | METRO           |   |   |
| entero de 8 bits  |                                                  |            |   |              |              |                 |                 |   |   |
|                   |                                                  |            |   |              |              |                 |                 |   |   |
| 0x0001            | Versión de la aplicación                         | No firmado |   | 0x00 –0xff   | Solo lectura | 0x00            | oh              |   |   |
| entero de 8 bits  |                                                  |            |   |              |              |                 |                 |   |   |
|                   |                                                  |            |   |              |              |                 |                 |   |   |
| 0x0003            | _Versión HW_                                     | No firmado |   | 0x00 –0xff   | Solo lectura | 0               | oh              |   |   |
| entero de 8 bits  |                                                  |            |   |              |              |                 |                 |   |   |
|                   |                                                  |            |   |              |              |                 |                 |   |   |
| 0x0004            | _Nombre del Fabricante_                          | Personaje  |   | 0 – 32 bytes | Solo lectura | Clímax          | oh              |   |   |
| Cadena            |                                                  | Tecnología |   |              |              |                 |                 |   |   |
|                   |                                                  |            |   |              |              |                 |                 |   |   |
| 0x0005            | _Identificador de modelo_                        | Personaje  |   | 0 – 32 bytes | Solo lectura | (Modelo         | oh              |   |   |
| Cadena            |                                                  | Versión)   |   |              |              |                 |                 |   |   |
|                   |                                                  |            |   |              |              |                 |                 |   |   |
| 0x0006            | _Código de fecha_                                | Personaje  |   | 0 – 16 bytes | Solo lectura |                 | oh              |   |   |
| Cadena            |                                                  |            |   |              |              |                 |                 |   |   |
|                   |                                                  |            |   |              |              |                 |                 |   |   |
| 0x0007            | _Fuente de alimentación_                         | 8 bits     |   | 0x00 –0xff   | Solo lectura |                 | METRO           |   |   |
| 0x0010            | _Descripción de la ubicación_                    | Personaje  |   | 0 – 32 bytes | Leer /       |                 | oh              |   |   |
| Cadena            |                                                  | Escribir   |   |              |              |                 |                 |   |   |
|                   |                                                  |            |   |              |              |                 |                 |   |   |
| 0x0011            | _Entorno físico_                                 | 8 bits     |   | 0x00 –0xff   | Leer /       | 0x00            | oh              |   |   |
|                   | Escribir                                         |            |   |              |              |                 |                 |   |   |
|                   |                                                  |            |   |              |              |                 |                 |   |   |
|                   |                                                  |            |   | 3            |              |                 |                 |   |   |

0x0012

_Dispositivo habilitado_

Booleano

0x00 –0x01

Leer /

Escribir

0x01

METRO

-   _**Atributo de información de identificación del clúster**_

| **Identificador** | **Nombre**          | **Tipo**   | **Rango**    | **Acceso** | **Por defecto** | **Obligatorio** |   |
| ----------------- | ------------------- | ---------- | ------------ | ---------- | --------------- | --------------- | - |
| **/ Opcional**    |                     |            |              |            |                 |                 |   |
|                   |                     |            |              |            |                 |                 |   |
| 0x0000            | _IdentificarTiempo_ | No firmado | 0x00 –0xffff | Leer /     | 0x0000          | METRO           |   |
| entero de 16 bits | Escribir            |            |              |            |                 |                 |   |
|                   |                     |            |              |            |                 |                 |   |

_**Atributo de la información del clúster de configuración de energía**_

| **Identificador** | **Nombre**                     | **Tipo**               | **Rango** | **Acceso** | **Por defecto** | **Obligatorio** |   |
| ----------------- | ------------------------------ | ---------------------- | --------- | ---------- | --------------- | --------------- | - |
| **/ Opcional**    |                                |                        |           |            |                 |                 |   |
|                   |                                |                        |           |            |                 |                 |   |
| 0x0035            | _Máscara de alarma de batería_ | mapa de bits de 8 bits | 0000 000x | Leer /     | 0000 0000       | oh              |   |
| Escribir          |                                |                        |           |            |                 |                 |   |
|                   |                                |                        |           |            |                 |                 |   |

_**Atributo de información del grupo de medición de temperatura**_

| **Identificador** | **Nombre**                                                                 | **Tipo**           | **Rango**         | **Acceso** | **Por defecto** | **Obligatorio** |   |   |
| ----------------- | -------------------------------------------------------------------------- | ------------------ | ----------------- | ---------- | --------------- | --------------- | - | - |
| **/ Opcional**    |                                                                            |                    |                   |            |                 |                 |   |   |
|                   |                                                                            |                    |                   |            |                 |                 |   |   |
| 0x0000            | Valor medido                                                               | Firmado de 16 bits | Valor MinMedido a | Leer       | 0x00            | METRO           |   |   |
| Entero            | Valor máximo medido                                                        | solo               |                   |            |                 |                 |   |   |
|                   |                                                                            |                    |                   |            |                 |                 |   |   |
|                   |                                                                            |                    |                   |            |                 |                 |   |   |
| 0x0001            | Valor mínimo medido                                                        | Firmado de 16 bits | 0x954d – 0x7ffe   | Leer       | -1000           | METRO           |   |   |
| Entero            | solo                                                                       | (-10℃)             |                   |            |                 |                 |   |   |
|                   |                                                                            |                    |                   |            |                 |                 |   |   |
| 0x0002            | Valor máximo medido                                                        | Firmado de 16 bits | 0x954e – 0x7fff   | Leer       | 5000            | METRO           |   |   |
| Entero            | solo                                                                       | (50℃)              |                   |            |                 |                 |   |   |
|                   |                                                                            |                    |                   |            |                 |                 |   |   |
| 0x0003            | Tolerancia                                                                 | 16 bits sin firmar | 0x0000 – 0x0800   | Leer       | 100             | oh              |   |   |
| Entero            | solo                                                                       | (1℃)               |                   |            |                 |                 |   |   |
|                   |                                                                            |                    |                   |            |                 |                 |   |   |
|                  | _**Atributo de la información del grupo de medición de humedad relativa**_ |                    |                   |            |                 |                 |   |   |
|                   |                                                                            |                    |                   |            |                 |                 |   |   |
| **Identificador** | **Nombre**                                                                 | **Tipo**           | **Rango**         | **Acceso** | **Por defecto** | **Obligatorio** |   |   |
| **/ Opcional**    |                                                                            |                    |                   |            |                 |                 |   |   |
|                   |                                                                            |                    |                   |            |                 |                 |   |   |
| 0x0000            | Valor medido                                                               | 16 bits sin firmar | Valor MinMedido a | Leer       |                 | METRO           |   |   |
| Entero            | Valor máximo medido                                                        | solo               |                   |            |                 |                 |   |   |
|                   |                                                                            |                    |                   |            |                 |                 |   |   |
|                   |                                                                            |                    |                   |            |                 |                 |   |   |
| 0x0001            | Valor mínimo medido                                                        | 16 bits sin firmar | 0x0000 – 0x270f   | Leer       | 0               | METRO           |   |   |
| Entero            | solo                                                                       | (0%)               |                   |            |                 |                 |   |   |
|                   |                                                                            |                    |                   |            |                 |                 |   |   |
| 0x0002            | Valor máximo medido                                                        | 16 bits sin firmar | 0x0001 – 0x2710   | Leer       | 10000           | METRO           |   |   |
| Es                | Entero                                                                     | solo               | (100%)            |            |                 |                 |   |   |
|                   |                                                                            |                    |                   |            |                 |                 |   |   |
| 0x0003            | Tolerancia                                                                 | 16 bits sin firmar | 0x0000 – 0x0800   | Leer       | 200             | oh              |   |   |
| Entero            | solo                                                                       | (2%)               |                   |            |                 |                 |   |   |
|                   |                                                                            |                    |                   |            |                 |                 |   |   |

4
