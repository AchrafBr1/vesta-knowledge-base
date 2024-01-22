# VESTA 189

**Termostato TMST-15-ZBS**

**Introducción**

TMST-15-ZBS es un termostato ZigBee que funciona con baterías. Está diseñado para incorporarse al sistema de calefacción y refrigeración del hogar para el control del ambiente del hogar. El termostato se puede operar manualmente mediante la pantalla LCD y los botones, o se puede acceder a él de forma remota a través de la red ZigBee. Cuenta con modos de refrigeración y calefacción con punto de ajuste de temperatura y programación automática para que pueda controlar fácilmente el entorno de su hogar.

El termostato utiliza tecnología ZigBee para la transmisión de señales inalámbricas. ZigBee es un protocolo de comunicación inalámbrica confiable, de bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir en una red una gran cantidad de dispositivos y coordinarlos para el intercambio de datos y la transmisión de señales.

El termostato sirve como dispositivo final en la red ZigBee. Puede incluirse en la red ZigBee para transmitir señal tras la activación, pero no puede permitir que ningún otro dispositivo ZigBee se una a la red.

**La serie TMST-15-ZBS tiene los siguientes modelos:**

TMST-15-ZBS

tmst-15-zbs-outa

**Identificación de piezas**

![](<.gitbook/assets/0 (77).jpeg>)

**1. Pantalla LCD**

La pantalla LCD muestra la siguiente información:

![](<.gitbook/assets/1 (68).jpeg>)

1.  Icono de modo de calefacción: cuando se muestra, el termostato está en modo de calefacción.
2.  Icono de modo frío: cuando se muestra, el termostato está en modo frío.
3.  Icono de batería baja: cuando se muestra, el voltaje de la batería del termostato es bajo.
4.  Conectividad de red ZigBee:

El icono se muestra cuando el termostato aún no se ha aprendido en ninguna puerta de enlace/panel, o cuando el dispositivo pierde la conexión a la red ZigBee actual.

1.  Modo: selección de modo, modo remoto y compensación
2.  Horario: El termostato ejecutará la configuración del horario programado.
3.  Lectura de temperatura/punto de ajuste

**2. Botón Abajo (-).**

Presione para disminuir el punto de ajuste

Mantenga presionado durante 3 segundos para ingresar al modo de programación.

**3. Botón arriba (+)**

Presione para aumentar el punto de ajuste.

Mantenga presionado durante 10 segundos para ingresar al modo de aprendizaje y se mostrará "Joi NET" en la pantalla LCD.

![](<.gitbook/assets/2 (62).jpeg>)

1.  **Orificio de montaje en pared**
2.  **Compartimiento de la batería**

Inserte 2 pilas alcalinas AA.

**6. Terminales del relé (retire la cubierta del relé para acceder)**

Terminales de relé 230V 5A NO/COM/NC.

Conéctelo al sistema de calefacción/refrigeración del hogar.

1

**Características**

![](<.gitbook/assets/3 (55).jpeg>)

-   _**Detección de batería y batería baja**_

El termostato utiliza 2 pilas alcalinas AA como fuente de energía. El termostato cuenta con la función de detección de batería baja. Cuando el voltaje de la batería es bajo, el termostato transmitirá la señal de batería baja al coordinador en la red ZigBee.

![](<.gitbook/assets/4 (53).jpeg>)

-   _**Control de relé**_

El termostato controla el sistema de calefacción/refrigeración del hogar a través del control de relé. Abra y voltee la cubierta trasera, retire la cubierta interna del relé para revelar los terminales para el cableado. Al cablear el termostato, pase el cable a través de la abertura central en la cubierta trasera.

![](<.gitbook/assets/5 (64).png>)

-   _**Control de modo**_

El Termostato tiene dos modos de funcionamiento: Modo Local y Modo Programado.

![](<.gitbook/assets/6 (43).jpeg>)![](<.gitbook/assets/7 (41).jpeg>)

-   **Modo local:**

El modo local permite ajustar la función Calor/Enfriamiento del termostato y los puntos de ajuste mediante los botones del termostato.

-   **Modo programado:**

![](<.gitbook/assets/8 (36).jpeg>)![](<.gitbook/assets/9 (28).jpeg>)

El modo programado permite el modo termostato y el control del punto de ajuste a través de la puerta de enlace una vez completado el aprendizaje.

Para cambiar el modo de funcionamiento, consulte “_Modo de programación_”Sección para más detalles.

![](<.gitbook/assets/10 (39).png>)

-   _**Control de calefacción/refrigeración y punto de ajuste**_

El termostato de calefacción/refrigeración y el punto de ajuste solo se pueden ajustar localmente cuando el termostato está configurado en modo local.

Cuando esté en modo local, presione el botón**ARRIBA**(**+**) o**Abajo (-)**Botón para ajustar el punto de ajuste.

Cuando esté en modo programado, use la puerta de enlace/panel de control para ajustar el punto de ajuste de forma remota.

Rango de punto de ajuste de calor: 9°C~30°C.

Rango de punto de ajuste frío: 11°C~32ºC

![](<.gitbook/assets/11 (30).png>)

-   _**Control remoto**_

Después de que el termostato se una a una red ZigBee, puede controlar el termostato a través del coordinador o puerta de enlace de la red ZigBee. Consulte el manual de su coordinador/puerta de enlace ZigBee para obtener más información.

Las siguientes funciones solo están disponibles para configuración a través del coordinador y la puerta de enlace ZigBee:

![](<.gitbook/assets/12 (20).jpeg>)![](<.gitbook/assets/13 (25).jpeg>)

-   -   **Cronograma:**

Solo puede programar la configuración del horario a través del coordinador/puerta de enlace de red ZigBee.

Configuración de horarios: se pueden programar hasta 5 horarios para cada día de la semana con modo, punto de ajuste y hora de inicio. Control de Horarios:

Normal: el termostato ejecutará la configuración del horario programado en consecuencia.

Mantener: el termostato omitirá el cronograma actual y realizará el siguiente cronograma cuando comience. Sin cronograma: el termostato no ejecutará ningún cronograma establecido hasta que se establezca nuevamente en Normal.

-   _**Detección de temperatura**_
    -   El termostato tiene sensores de temperatura incorporados y mostrará la lectura de temperatura en la pantalla LCD.
    -   El termostato transmitirá señales de temperatura periódicamente según la configuración. El intervalo predeterminado de fábrica es de 10 minutos.
    -   Cuando la temperatura cambia +/- 2°C, el termostato también transmitirá una señal.
    -   También puede presionar el botón de red ZigBee una vez para transmitir una señal de temperatura manualmente.
-   _**Supervisión**_

![](<.gitbook/assets/14 (24).png>)![](<.gitbook/assets/15 (23).png>)

El termostato transmitirá una señal de supervisión cada 10 minutos junto con la temperatura, el modo actual y la información del punto de ajuste para informar su condición periódicamente.

2

-   ![](<.gitbook/assets/16 (25).png>)_**Modo de programación**_

**Paso 1.**Mantenga presionado el botón Abajo (-) durante 3 segundos para ingresar al modo de programación.

**Paso 2.**Hay 3 funciones disponibles para programación, incluidas las funciones del termostato, el control del relé remoto y la compensación del punto de ajuste. Puede presionar el botón ARRIBA (+) o Abajo (-) para cambiar de modo.

**Paso 3.**Después de finalizar la selección, espere unos segundos hasta que el termostato ingrese al modo seleccionado.

**Funciones del termostato (calefacción y refrigeración):**

En este modo, se mostrará "Pro Mod" en la pantalla LCD.

![](<.gitbook/assets/17 (17).jpeg>)

Los modos de calefacción/refrigeración están disponibles para su selección. Presione el botón ARRIBA (+) para seleccionar Calefacción y el botón Abajo (-) para seleccionar Refrigeración.

Refrigeración calefacción

![](<.gitbook/assets/18 (12).jpeg>)

Después de finalizar la selección, espere unos segundos hasta que el termostato salga del modo de configuración automáticamente. El termostato ingresará al último modo seleccionado.

**Control del relé remoto:**

En este modo, se mostrará “Pro RM” en la pantalla LCD. El modo remoto le permite controlar el relé remoto a través del panel de control cuando la función está habilitada. El termostato no controlará el relé local en modo remoto.

![](<.gitbook/assets/19 (26).png>)

-   Si el modo remoto está desactivado, se mostrará "dS RM" en la pantalla LCD.
-   Si el modo remoto está habilitado, se mostrará “En RM” en la pantalla LCD.

![](<.gitbook/assets/20 (18).png>)

**Compensación del punto de ajuste:**

En este modo, se mostrará “Pro OFS” en la pantalla LCD. La función de compensación del punto de ajuste le permite compensar la desviación. Para calcular la compensación del punto de ajuste, simplemente reste la temperatura ambiente a la temperatura del dispositivo. Cuando esté en modo local, presione y mantenga presionado el botón Abajo (-) durante 3 segundos para ingresar al modo de programación. Después de finalizar la selección, espere unos segundos hasta que el termostato ingrese al modo de selección.

Por ejemplo: si la temperatura del dispositivo es de 20 °C y la temperatura ambiente es de 18 °C, entonces la compensación del punto de ajuste = 18 – 20 = -2 °C.

Después de aplicar la compensación del punto de ajuste, el dispositivo funcionará de acuerdo con la temperatura ajustada.

Por ejemplo: si la lectura de temperatura del dispositivo es 20 °C, la compensación del punto de ajuste es -2 °C, el dispositivo funcionará utilizando 18 °C como referencia real.

**Configuración de red ZigBee**

-   _**Guía del dispositivo ZigBee**_

ZigBee es un protocolo de comunicación inalámbrica confiable, de bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir una gran cantidad de dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

Debido a la estructura fundamental de la red ZigBee, el dispositivo ZigBee buscará y se unirá activamente a la red después de encenderse. Dado que realizar una tarea al conectarse a la red puede consumir algo de energía, es necesario seguir las instrucciones para evitar agotar la batería de un dispositivo ZigBee.

-   Asegúrese de que su enrutador o coordinador de red ZigBee esté encendido antes de insertar la batería en el dispositivo ZigBee.
-   Asegúrese de que el enrutador o coordinador de red ZigBee esté encendido y dentro del alcance mientras un dispositivo ZigBee esté en uso.
-   No retire un dispositivo ZigBee del enrutador o coordinador de red ZigBee sin quitar la batería del dispositivo ZigBee.

3

-   _**Unirse a la red ZigBee**_

Como dispositivo ZigBee, el termostato debe unirse a una red ZigBee para que el usuario pueda controlarlo de forma remota. Siga los pasos a continuación para unir el termostato a la red ZigBee.

-   1.  Retire la tapa trasera del termostato e inserte 2 pilas alcalinas AA para encender el termostato.
    2.  Mantenga presionado el botón de red ZigBee durante 10 segundos y luego suéltelo para unirse a la red ZigBee. Asegúrese de que la función de permiso de unión en el enrutador o coordinador de su red ZigBee esté habilitada.
    3.  Espere varios segundos hasta que el termostato se una a la red ZigBee. Si el termostato se une exitosamente a una red, el ícono de conexión ZigBee desaparecerá en la pantalla LCD.
    4.  Después de unirse a la red ZigBee, el termostato se registrará automáticamente en el sistema de seguridad de la red. Verifique el panel de control del sistema de seguridad o CIE (Equipo de control e indicación) para confirmar si la inscripción y el registro se realizaron correctamente.
    5.  Después de unirse a la red ZigBee, si el termostato pierde la conexión con la red ZigBee actual, el icono de conexión ZigBee aparecerá después de 10 minutos. Verifique la condición de la red ZigBee y el rango de señal del termostato para corregir la situación.
-   _**Eliminación del dispositivo de la red ZigBee (restablecimiento de fábrica)**_

Para eliminar el termostato de la red ZigBee actual o configurarlo a los valores predeterminados de fábrica, siga los pasos a continuación:

**Retire el Termostato de la red ZigBee actual:**

1.  Antes de retirar el dispositivo, asegúrese de que el termostato esté dentro del rango de señal de la red ZigBee actual.
2.  Mantenga presionado el botón ARRIBA (+) durante 10 segundos y luego suelte el botón.
3.  El termostato se eliminará de la red ZigBee actual. Buscará activamente nuevamente la red ZigBee disponible y se unirá a la red automáticamente.

**Configure el termostato a los valores predeterminados de fábrica:**

-   1.  Presione los botones ARRIBA (+) y Abajo (-) al mismo tiempo y luego encienda el dispositivo.
    2.  Suelta los botones. El termostato borrará su configuración almacenada y volverá a los valores predeterminados de fábrica.
-   _**Actualización de firmware OTA**_

El termostato admite la función de actualización de firmware OTA a través de la red ZigBee, que puede iniciarse desde el coordinador de la red ZigBee.

Siga los pasos a continuación para realizar la actualización del firmware OTA.

**Paso 1.**Debe acceder a su Coordinador ZigBee para realizar la actualización del firmware en el aire.

**Paso 2.**En la página web de configuración, seleccione el dispositivo que desea actualizar y seleccione el nuevo firmware ZigBee proporcionado. Consulte el Manual del usuario del Coordinador ZigBee para obtener más detalles.

**Paso 3.**Presione "OK" para iniciar el proceso de actualización y el LED seguirá parpadeando. Durante el proceso OTA, no realice ninguna otra acción ni apague el panel.

**Etapa 4.**La duración de una actualización tardará aproximadamente entre 20 y 30 minutos. Tenga en cuenta que la duración puede variar según el tamaño del archivo o la distancia entre su accesorio y el coordinador.

**Paso 5**Espere a que el firmware complete la actualización. Cuando el progreso alcance el 100%, el dispositivo se reiniciará automáticamente. También puede actualizar la página web nuevamente para asegurarse de que el firmware del dispositivo se actualice correctamente y se muestre la versión más reciente.

**Instalación**

El termostato está diseñado para montarse en la pared utilizando los orificios de montaje de la cubierta posterior.

1.  Antes del montaje, asegúrese de completar primero el cableado del relé a través de la abertura de la cubierta trasera.
2.  Utilice los orificios de montaje de la cubierta posterior como plantilla para marcar la ubicación de montaje en la pared.
3.  Taladre agujeros en la pared e inserte el taco de pared si es necesario, atornille la cubierta posterior en la ubicación de montaje.
4.  Coloque el cuerpo principal del termostato en la cubierta posterior; la instalación estará completa.

**Apéndice (solo para desarrolladores).**

-   _**ID del grupo de termostatos**_

**ID del dispositivo: ZCL_HA_ID DEL DISPOSITIVO_TERMOSTATO 0x0301**

**Punto final: 0x01**

| **Lado del servidor** |                 | **Lado del cliente** |
| --------------------- | --------------- | -------------------- |
|                       |                 |                      |
|                       | **Obligatorio** |                      |

Básico (0x0000)

Configuración de energía (0x0001)

Identificar(0x0003)

_Identificar(0x0003)_

_Activado/Desactivado(0x0006)_

_Hora(0x000A)_

4

TERMOSTATO HVAC (0x0201)

Diagnóstico (0x0B05)

**Opcional**

_**Atributo de información básica del clúster**_

| **Identificador**                                             | **Nombre**                    | **Tipo**          | **Rango**     | **Acceso**    | **Por defecto** | **Obligatorio** |   |
| ------------------------------------------------------------- | ----------------------------- | ----------------- | ------------- | ------------- | --------------- | --------------- | - |
| **/ Opcional**                                                |                               |                   |               |               |                 |                 |   |
|                                                               |                               |                   |               |               |                 |                 |   |
| 0x0000                                                        | _Versión ZCL_                 | 8 bits sin firmar | 0x00 –0xff    | Solo lectura  | 0x01            | METRO           |   |
| entero                                                        |                               |                   |               |               |                 |                 |   |
|                                                               |                               |                   |               |               |                 |                 |   |
| 0x0001                                                        | Versión de la aplicación      | 8 bits sin firmar | 0x00 –0xff    | Solo lectura  | 0x00            | oh              |   |
| entero                                                        |                               |                   |               |               |                 |                 |   |
|                                                               |                               |                   |               |               |                 |                 |   |
| 0x0003                                                        | _Versión HW_                  | 8 bits sin firmar | 0x00 –0xff    | Solo lectura  | 0               | oh              |   |
| entero                                                        |                               |                   |               |               |                 |                 |   |
|                                                               |                               |                   |               |               |                 |                 |   |
| 0x0004                                                        | _Nombre del Fabricante_       | Personaje         | 0 – 32 bytes  | Solo lectura  | Clímax          | oh              |   |
| Cadena                                                        | Tecnología                    |                   |               |               |                 |                 |   |
|                                                               |                               |                   |               |               |                 |                 |   |
| 0x0005                                                        | _Identificador de modelo_     | Personaje         | 0 – 32 bytes  | Solo lectura  | (Modelo         | oh              |   |
| Cadena                                                        | Versión)                      |                   |               |               |                 |                 |   |
|                                                               |                               |                   |               |               |                 |                 |   |
| 0x0006                                                        | _Código de fecha_             | Personaje         | 0 – 16 bytes  | Solo lectura  |                 | oh              |   |
| Cadena                                                        |                               |                   |               |               |                 |                 |   |
|                                                               |                               |                   |               |               |                 |                 |   |
| 0x0007                                                        | _Fuente de alimentación_      | 8 bits            | 0x00 –0xff    | Solo lectura  |                 | METRO           |   |
| 0x0010                                                        | _Descripción de la ubicación_ | Personaje         | 0 – 32 bytes  | Leer escribir |                 | oh              |   |
| Cadena                                                        |                               |                   |               |               |                 |                 |   |
|                                                               |                               |                   |               |               |                 |                 |   |
| 0x0011                                                        | _Entorno físico_              | 8 bits            | 0x00 –0xff    | Leer escribir | 0x00            | oh              |   |
| 0x0012                                                        | _Dispositivo habilitado_      | Booleano          | 0x00 –0x01    | Leer escribir | 0x01            | oh              |   |
| 0xFFFD                                                        | _Revisión del clúster_        | uint16            | 0x0001-0xFFFE | Solo lectura  | 1               | METRO           |   |
| _**Atributo de energía Configurar información del clúster**_ |                               |                   |               |               |                 |                 |   |

| **Identificador**                                            | **Nombre**                     | **Tipo** | **Rango**     | **Acceso**    | **Por defecto** | **Obligatorio** |   |
| ------------------------------------------------------------ | ------------------------------ | -------- | ------------- | ------------- | --------------- | --------------- | - |
| **/ Opcional**                                               |                                |          |               |               |                 |                 |   |
|                                                              |                                |          |               |               |                 |                 |   |
| 0x0035                                                       | _Máscara de alarma de batería_ | mapa8    | 0b0000 000x   | Leer escribir | 0b0000          | oh              |   |
| 0000                                                         |                                |          |               |               |                 |                 |   |
|                                                              |                                |          |               |               |                 |                 |   |
| 0xFFFD                                                       | _Revisión del clúster_         | uint16   | 0x0001-0xFFFE | Solo lectura  | 1               | METRO           |   |
| _**Atributo de información de identificación del clúster**_ |                                |          |               |               |                 |                 |   |

| **Identificador**                                          | **Nombre**                                |             |                    | **Tipo**                 |                                          | **Rango**                    |               |              | **Acceso**      |                 | **Por defecto** | **Obligatorio** |   |
| ---------------------------------------------------------- | ----------------------------------------- | ----------- | ------------------ | ------------------------ | ---------------------------------------- | ---------------------------- | ------------- | ------------ | --------------- | --------------- | --------------- | --------------- | - |
|                                                            |                                           |             |                    |                          |                                          | **/ Opcional**               |               |              |                 |                 |                 |                 |   |
|                                                            |                                           |             |                    |                          |                                          |                              |               |              |                 |                 |                 |                 |   |
| 0x0000                                                     | _IdentificarTiempo_                       |             | 16 bits sin firmar |                          | 0x00 –0xffff                             |                              | Leer escribir |              | 0x0000          | METRO           |                 |                 |   |
|                                                            |                                           | entero      |                    |                          |                                          |                              |               |              |                 |                 |                 |                 |   |
|                                                            |                                           |             |                    |                          |                                          |                              |               |              |                 |                 |                 |                 |   |
| 0xFFFD                                                     | _Revisión del clúster_                    |             |                    | uint16                   |                                          | 0x0001-0xFFFE                |               | Solo lectura | 1               | METRO           |                 |                 |   |
| _**Atributo de la información del grupo de termostatos**_ |                                           |             |                    |                          |                                          |                              |               |              |                 |                 |                 |                 |   |
|                                                            |                                           |             |                    |                          |                                          |                              |               |              |                 |                 |                 |                 |   |
| **Identificador**                                          | **Nombre**                                |             | **Tipo**           |                          | **Rango**                                |                              | **Acceso**    |              | **Por defecto** | **Obligatorio** |                 |                 |   |
|                                                            |                                           |             |                    | **/ Opcional**           |                                          |                              |               |              |                 |                 |                 |                 |   |
|                                                            |                                           |             |                    |                          |                                          |                              |               |              |                 |                 |                 |                 |   |
| 0x0000                                                     | _Temperatura local_                       |             | 16 bits            |                          | 0x954d – 0x7fff                          |                              | Solo lectura  |              | 0x0000          | METRO           |                 |                 |   |
|                                                            |                                           |             |                    |                          |                                          |                              |               |              |                 |                 |                 |                 |   |
| 0x0003                                                     | _AbsMinHeatSetpointLimit_                 |             | 16 bits            |                          | 0x954d – 0x7fff                          |                              | Solo lectura  |              | 0x01F4          | oh              |                 |                 |   |
| 0x0004                                                     | _AbsMaxHeatSetpointLimit_                 |             | 16 bits            |                          | 0x954d – 0x7fff                          |                              | Solo lectura  |              | 0x0DAC          | oh              |                 |                 |   |
| 0x0005                                                     | _AbsMinCoolSetpointLimit_                 |             | 16 bits            |                          | 0x954d – 0x7fff                          |                              | Solo lectura  |              | 0x01F4          | oh              |                 |                 |   |
| 0x0006                                                     | _AbsMinCoolSetpointLimit_                 |             | 16 bits            |                          | 0x954d – 0x7fff                          |                              | Solo lectura  |              | 0x0DAC          | oh              |                 |                 |   |
|                                                            | _Punto de ajuste de enfriamiento ocupado_ |             |                    |                          | _Punto de ajuste mínimo de enfriamiento_ |                              | Leer /        |              |                 |                 |                 |                 |   |
| 0x0011                                                     |                                           | 16 bits     |                    | _Límite_–_máximo fresco_ |                                          |                              | 0x0A28        | METRO        |                 |                 |                 |                 |   |
|                                                            |                                           |             | Escribir           |                          |                                          |                              |               |              |                 |                 |                 |                 |   |
|                                                            |                                           |             |                    |                          |                                          | _Setpoint Limit_             |               |              |                 |                 |                 |                 |   |
|                                                            |                                           |             |                    |                          |                                          |                              |               |              |                 |                 |                 |                 |   |
|                                                            | _Punto de ajuste de calefacción ocupada_  |             |                    |                          | _Punto de ajuste de calor mínimo_        |                              | Leer /        |              |                 |                 |                 |                 |   |
| 0x0012                                                     |                                           | 16 bits     |                    | _Límite_–_Calor máximo_  |                                          |                              | 0x07D0        | METRO        |                 |                 |                 |                 |   |
|                                                            |                                           |             | Escribir           |                          |                                          |                              |               |              |                 |                 |                 |                 |   |
|                                                            |                                           |             |                    |                          |                                          | _Límite del punto de ajuste_ |               |              |                 |                 |                 |                 |   |
|                                                            |                                           |             |                    |                          |                                          |                              |               |              |                 |                 |                 |                 |   |
| 0x001B                                                     | _Secuenciadecontroldeoperación_           | 8 bits      |                    | 0x00 – 0x05              |                                          | Leer /                       |               | 0x04         | METRO           |                 |                 |                 |   |
| _norte_                                                    |                                           | Enumeración |                    |                          | Escribir                                 |                              |               |              |                 |                 |                 |                 |   |
|                                                            |                                           |             |                    |                          |                                          |                              |               |              |                 |                 |                 |                 |   |
| 0x001C                                                     | _Modo sistema_                            |             | 8 bits             |                          | 0x00 – 0x09                              |                              | Leer /        |              | 0x04            | METRO           |                 |                 |   |
|                                                            | Enumeración                               |             |                    | Escribir                 |                                          |                              |               |              |                 |                 |                 |                 |   |
|                                                            |                                           |             |                    |                          |                                          |                              |               |              |                 |                 |                 |                 |   |
| 0x0020                                                     | _InicioDeSemana_                          |             | 8 bits             |                          | 0x00 – 0x06                              |                              | Leer          |              | -               | oh              |                 |                 |   |
|                                                            | Enumeración                               |             |                    |                          |                                          |                              |               |              |                 |                 |                 |                 |   |
|                                                            |                                           |             |                    |                          |                                          |                              |               |              |                 |                 |                 |                 |   |
| 0x0021                                                     | _Número de transiciones semanales_        |             | wint8              |                          | 0x00 – 0xff                              |                              | Leer          |              | N / A           | oh              |                 |                 |   |
|                                                            |                                           |             |                    |                          | 5                                        |                              |               |              |                 |                 |                 |                 |   |

| 0x0022                                                    | _Número de transiciones diarias_         | wint8    | 0x00 – 0xff   |   | Leer           | N / A  | oh           |            |   |                 |                 |   |
| --------------------------------------------------------- | ---------------------------------------- | -------- | ------------- | - | -------------- | ------ | ------------ | ---------- | - | --------------- | --------------- | - |
| 0x0023                                                    | _Punto de ajuste de temperaturaMantener_ | 8 bits   | 0x00 – 0x01   |   | Leer /         | 0x00   | oh           |            |   |                 |                 |   |
| Enumeración                                               |                                          | Escribir |               |   |                |        |              |            |   |                 |                 |   |
|                                                           |                                          |          |               |   |                |        |              |            |   |                 |                 |   |
| 0x0025                                                    | _TermostatoProgramaciónOperaciones_      | mapa8    | 0b00xx xxxx   |   | Leer /         | 0b0000 | oh           |            |   |                 |                 |   |
| _También hace sonido_                                     |                                          | Escribir | 0000          |   |                |        |              |            |   |                 |                 |   |
|                                                           |                                          |          |               |   |                |        |              |            |   |                 |                 |   |
| 0xFF01                                                    | _Modo de control remoto del termostato_  | mapa8    | 0b0000 000x   |   | Leer /         | 0b0000 | oh           |            |   |                 |                 |   |
|                                                           | Escribir                                 | 0000     |               |   |                |        |              |            |   |                 |                 |   |
|                                                           |                                          |          |               |   |                |        |              |            |   |                 |                 |   |
| 0xFFFD                                                    | _Revisión del clúster_                   | uint16   | 0x0001-0xFFFE |   | Solo lectura   | 1      | METRO        |            |   |                 |                 |   |
| _**Atributo de información del clúster de diagnóstico**_ |                                          |          |               |   |                |        |              |            |   |                 |                 |   |
|                                                           |                                          |          |               |   |                |        |              |            |   |                 |                 |   |
| **Identificador**                                         | **Nombre**                               |          | **Tipo**      |   | **Rango**      |        |              | **Acceso** |   | **Por defecto** | **Obligatorio** |   |
|                                                           |                                          |          |               |   | **/ Opcional** |        |              |            |   |                 |                 |   |
|                                                           |                                          |          |               |   |                |        |              |            |   |                 |                 |   |
| 0x011C                                                    | _Último mensajeLQI_                      |          | 8 bits        |   | 0x00 – 0xFF    |        |              | Leer       |   | 0x00            | oh              |   |
| 0x011D                                                    | _Último mensajeRSSI_                     |          | 8 bits        |   | 0x00 – 0xFF    |        |              | Leer       |   | 0x00            | oh              |   |
| 0xFFFD                                                    | _Revisión del clúster_                   |          | uint16        |   | 0x0001-0xFFFE  |        | Solo lectura |            | 1 | METRO           |                 |   |

6
