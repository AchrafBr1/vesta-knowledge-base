# VESTA 309

![](<.gitbook/assets/0 (57).png>)**Detector de humo y monóxido de carbono (SDCO-3-RhTHM-ZW-SC-AC-OTA) Introducción**

SDCO-3-RhTHM-ZW-SC-AC-OTA es un detector de humo y monóxido de carbono Z-Wave con sensor PIR incorporado, detección de temperatura, humedad y calor, así como indicaciones de voz y permite el acceso al “S2 Clase no autenticada” y admite tanto Z-Wave SmartStart Inclusion como Inclusion clásica. Es capaz de enviar señales inalámbricas al panel de control/puerta de enlace Z-Wave al detectar partículas de humo o monóxido de carbono. El dispositivo también está conectado en serie con otros sensores en la puerta de enlace Z-Wave para que sirva como sirena adicional. Cuando cualquier otro sensor en la red Z-Wave se activa y envía una señal de alarma, el detector de humo también activará la alarma con su zumbador incorporado como sirena para ayudar a emitir una advertencia sonora (para modelos de conexión en serie).

El SDCO-3 está diseñado para montarse en el techo o en la parte superior de las escaleras cuando el humo se concentra para dar la alarma oportuna y proteger su hogar de los riesgos de incendio.

El detector SDCO es un dispositivo habilitado para Z-Wave y es totalmente compatible con cualquier red habilitada para Z-Wave. Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia.

![](<.gitbook/assets/1 (72).png>)

_**Identificación de piezas**_

1. **Vocero**
2. **Botón**
   * Presione el botón una vez para enviar una prueba de alarma, prueba de alarma desactivada y señales de temperatura y humedad para probar el detector de humo y monóxido de carbono.
   * Presione el botón durante 5 segundos, suelte el botón hasta que se encienda el LED ámbar. Luego, el LED ámbar comenzará a parpadear para indicar que ha entrado en modo de repetición. Consulte Modo de repetición temporal en la sección Funciones para obtener más detalles.
   * Presione el botón una vez durante la alarma para silenciarla.
   * Presione el botón 3 veces en 1,5 segundos para enviar un código de inclusión.
   * Mantenga presionado el botón durante 10 segundos. Suelte el botón cuando escuche 2 pitidos para ingresar al proceso de calibración de humo y autodiagnóstico de CO.
   * Mantenga presionado el botón durante 20 segundos. Suelte el botón cuando escuche 3 pitidos para realizar el restablecimiento de fábrica.
   * Presione el botón dos veces antes de insertar baterías nuevas.
3. **Sensor de movimiento PIR**
4. **Indicador LED**

**LED rojo**

* Se enciende brevemente: Transmitiendo señal.
* Parpadeo rápido: alarmante.
* Parpadea cada segundo: en modo de silencio de alarma.
* Parpadea cada 2 segundos: En proceso de calentamiento y calibración.
* Parpadea rápidamente 3 veces cada 8 segundos: se detecta humo durante el período de verificación de incendio.
* Parpadea rápidamente 2 veces cada 5 segundos: cuando está en modo de repetición

**LED ámbar**

* Parpadea cada segundo: encendido del dispositivo/fallo de calibración.
* Parpadea dos veces cada 5 segundos: Mal funcionamiento del dispositivo.
* Parpadea cada 45 segundos: condición de batería baja

**LED rojo y ámbar (naranja cuando se mira desde el exterior)**

* Se enciende: Falló el sensor de temperatura/humedad.
* Parpadea cada 4 segundos: Batería agotada.

1

1. **Zumbador**
2. **Orificios de montaje**
3. **Soporte de montaje**
4. **Manibela de encendido**
5. **Tapa del compartimento de la batería**
6. **Interruptor de batería (interior)**
7. **Orificio preperforado para cableado.**
8. **Tornillo de fijación de la tapa del compartimento de la batería**
9. **Muescas**
10. **Puerto de actualización de firmware (USB tipo C)**
    * Solo para actualización de firmware con cable personalizado.\*\*Tenga en cuenta:\*\*El mal uso del cable USB tipo C normal puede provocar un mal funcionamiento del dispositivo.

**Características**

![](<.gitbook/assets/2 (80).png>)

* _**Detección de batería y batería baja**_
  * El modelo SDCO-3-RhTHM-ZW-SC-AC-OTA utiliza CA 100-240 V como fuente de alimentación y tiene tres baterías recargables AAA Ni-MH de 600 mAh como batería de respaldo en caso de corte de energía. La batería está incluida en el paquete.
  * Cuando la batería recargable se esté cargando, el detector SDCO informará su porcentaje de batería a la puerta de enlace/panel de control respectivamente al 100 %, 90 %, 80 %, 70 %, 60 %, 50 %, 40 %, 30 % y 20 %. (batería baja).
  * Si se detecta una falla de energía de CA, el detector SDCO enviará un informe de falla de CA al panel de control.
  * Cuando el detector SDCO tiene poca batería, se transmitirá una señal de batería baja junto con las transmisiones de señal regulares. El LED ámbar parpadeará acompañado de un pitido de bajo volumen una vez cada 45 segundos.
  * Tanto el LED rojo como el ámbar parpadearán una vez cada 4 segundos cuando la batería esté agotada.
* _**Manibela de encendido**_
  * El detector SDCO está protegido por un interruptor de manipulación que se comprime cuando el detector SDCO se engancha al soporte de montaje. Cuando se retira el detector SDCO del soporte de montaje, el interruptor de manipulación se activará y el detector SDCO enviará una señal de apertura de manipulación al panel de control del sistema para recordarle al usuario esta condición.
  * El detector SDCO enviará una señal de cierre por manipulación al panel de control después de que el dispositivo esté enganchado al soporte de montaje. Tenga en cuenta que el detector SDCO debe incluirse primero en la red Z-Wave.
* _**Modo de sensibilidad**_
  * El nivel de sensibilidad del dispositivo se puede ajustar mediante el comando de configuración de Z-Wave. Se pueden configurar hasta ocho niveles de sensibilidad (predeterminado: 0x04). Establezca 0x01 para el nivel de sensibilidad más alto. Consulte la página 11.\*\*“Configuraciones”\*\*sección para más detalles.
* _**Modo de repetición temporal**_
  * Esta función le permite pausar la función de detección de movimiento durante un período de tiempo específico para evitar alertas de movimiento no deseadas sin tener que desarmar el dispositivo.
  * Por defecto, la función está deshabilitada y se puede activar presionando el botón durante 5 segundos, lo que habilita el modo durante 5 minutos. También puede activar el modo usando el comando de configuración de Z-Wave y se pueden configurar hasta 36 horas. El modo de repetición finalizará tan pronto como presione cualquier botón o opere el dispositivo. Consulte la página 12.\*\*“Configuraciones”\*\*sección para más detalles.
* _**Agregar dispositivo (inclusión)**_

![](<.gitbook/assets/3 (78).png>) ![](<.gitbook/assets/4 (83).png>) ![](<.gitbook/assets/5 (82).png>) ![](<.gitbook/assets/6 (62).png>)

El dispositivo admite tanto el proceso de inclusión clásico como el proceso de inclusión SmartStart.

**Inclusión clásica**

Este producto se puede incluir y operar en cualquier red Z-Wave con otros dispositivos certificados Z-Wave de otros fabricantes y/o aplicaciones. Todos los nodos de la red que no funcionan con baterías actuarán como repetidores independientemente del proveedor para aumentar la confiabilidad de la red.

* Para agregar el detector SDCO al panel de control, primero debe conectarlo a la alimentación de CA (red). Siga los pasos a continuación para continuar.

\*\*Paso 1.\*\*Antes de comenzar, busque el disyuntor o la caja de fusibles.

\*\*Paso 2.\*\*Una vez que lo haya encontrado, abra la puerta y apague el interruptor principal.

\*\*Paso 3.\*\*Se proporcionan dos conectores de empalme Wago 221. Saque un conector. Levante la palanca e inserte el cable blanco.\*\*Etapa 4.\*\*Empuje la palanca hacia abajo. La carcasa transparente le permite comprobar si el cable está conectado correctamente.**Asegúrate que**

**el cable esté bien sujeto en su lugar antes de continuar.**

\*\*Paso 5.\*\*Repita los pasos 3 y 4 para insertar el cable negro. Insertar los dos cables en el mismo lado (derecho), como se muestra a continuación, de los dos conectores facilita la instalación en los siguientes pasos.

\*\*Paso 6.\*\*Inserte los cables de CA en los dos conectores respectivamente, como se muestra a continuación. Si gira el interruptor de la batería a la posición ON, la batería recargable comenzará a cargarse.

![](<.gitbook/assets/7 (56).png>)

_Figura 1. Inserte los cables blanco y negro._

![](<.gitbook/assets/8 (57).png>)

_Figura 2. Verifique si los cables están conectados correctamente._

![](<.gitbook/assets/9 (52).png>)

_Figura 3. Inserte los cables de CA._

![](<.gitbook/assets/10 (54).png>)

2

\*\*Paso 7.\*\*Dé la vuelta al detector SDCO. Escuchará "Bienvenido, alarma de humo y detector de monóxido de carbono", lo que indica que está listo para realizar más configuraciones (solo para modelos conectados en serie).

* El detector SDCO permite a los usuarios configurar un mensaje de ubicación para un área, para ver la lista completa de ubicaciones e instrucciones de configuración; consulte "_**Mensaje de voz**_”Sección para más detalles. Se recomienda realizar el proceso de calentamiento y calibración.**antes**incluyendo su dispositivo en el coordinador Z-Wave.

**\\**

1. El detector SDCO emitirá 2 pitidos cortos y comenzará el proceso de calentamiento durante**1**minuto. El LED parpadeará cada 2 segundos.
2. When 1-minute warm up period expires, the SDCO Detector will emit a beep to indicate it now enters calibration process. The calibration process takes 1\~7 minutos; El LED seguirá parpadeando durante la calibración.
3. Cuando se complete la calibración, el detector SDCO emitirá un sonido de dos tonos y el LED dejará de parpadear para indicar que ahora está en funcionamiento normal. Si la calibración falla, el detector SDCO emitirá pitidos continuos.

**\\**

1. Coloque la puerta de enlace Z-Wave o el panel de control en modo de inclusión (consulte el manual de la puerta de enlace o panel de control Z-Wave).
2. En 1,5 segundos, presione el botón 3 veces.
3. Consulte el manual de operación de la puerta de enlace o panel de control Z-Wave para completar el proceso de inclusión.
4. Si el sensor ya se ha incluido en otra puerta de enlace/panel de control Z-Wave, o si el sensor no se puede incluir en la puerta de enlace/panel de control Z-Wave actual, exclúyalo primero (consulte Exclusión) antes de intentar incluirlo. en el panel de control/puerta de enlace Z-Wave actual.

**Inclusión SmartStart**

![](<.gitbook/assets/11 (29).jpeg>)

Z-Wave SmartStart utiliza el DSK del dispositivo para mejorar y simplificar el proceso de inclusión. DSK es una clave específica del dispositivo que se utiliza para la comunicación de autenticación. La información DSK se almacena en formato de código QR que se imprime en una etiqueta y se adhiere al exterior del dispositivo.

Con un controlador Z-wave que proporciona inclusión SmartStart, el dispositivo habilitado para SmartStart se puede agregar a una red Z-Wave escaneando el código QR Z-Wave en el producto. Sin ninguna otra acción, el dispositivo se agregará automáticamente dentro de los 10 minutos posteriores a su encendido en las proximidades de la red.

*
  * Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de inclusión**(consulte el manual de la puerta de enlace Z-Wave o del panel de control).
  * Escanee el código QR en el detector SDCO para recuperar**DSK**.
  * Encienda el detector SDCO y se enviará automáticamente una solicitud de inclusión de SmartStart al portal.
  * La puerta de enlace incluirá automáticamente el dispositivo al reconocerlo haciendo coincidir la solicitud de inclusión con el DSK obtenido.
    * El DSK del dispositivo se utiliza sólo durante la inclusión.
    * El DSK se puede leer sin encender el detector SDCO, por lo que es posible preparar la puerta de enlace para incluir el dispositivo antes de instalar y encender el detector SDCO.
    * Si el dispositivo ya se ha agregado (incluido) en otra puerta de enlace/panel de control Z-Wave, exclúyalo primero (consulte\_**Quitar dispositivo**\_) antes de intentar incluirlo en el panel de control/puerta de enlace Z-Wave actual. El dispositivo no enviará un

Solicitud de inclusión de SmartStart si ya está en un Gateway/Panel de control Z-Wave.

* _**Eliminación del dispositivo (exclusión)**_

![](<.gitbook/assets/12 (46).png>)

El detector SDCO debe retirarse de la red Z-Wave existente antes de incluirlo en otra.

*
  * Coloque la puerta de enlace Z-Wave o el panel de control en modo de exclusión (consulte el manual de la puerta de enlace o panel de control Z-Wave).
  * En 1,5 segundos, presione el botón 3 veces y el detector SDCO se eliminará de la red Z-Wave.
* _**Aviso de voz (para modelos de conexión en serie)**_

![](<.gitbook/assets/13 (34).png>)

El detector SDCO permite al usuario configurar un mensaje de ubicación para un área (por ejemplo, cocina o sótano). Cuando se activa una alarma, el detector SDCO reproducirá el mensaje de voz preprogramado para alertar al usuario que debe evacuar. Para la configuración por primera vez, siga los pasos a continuación:

\*\*Paso 1.\*\*Encienda el interruptor de la batería.

\*\*Paso 2.\*\*Se reproducirá el mensaje n.º 1 “Bienvenido, alarma de humo y detector de monóxido de carbono”.

\*\*Paso 3.\*\*Se reproducirá el mensaje n.º 2 “No hay ubicación programada”.

\*\*Etapa 4.\*\*Se reproducirá el mensaje n.° 3 “Para seleccionar la ubicación, presione y mantenga presionado el botón ahora”.

\*\*Paso 5.\*\*Continúe presionando el botón y se reproducirá el mensaje #4 “Para programar la ubicación, presione y mantenga presionado el botón después de escuchar la ubicación”.\*\*Paso 6.\*\*Continúe presionando el botón y se reproducirá el mensaje #6 “Ubicación” seguido de las ubicaciones para seleccionar.

(del mensaje #11-31).

\*\*.Paso 7.\*\*Para configurar un mensaje de ubicación deseado, simplemente suelte el botón.

\*\*. ..\*\*\*\*.Paso 8.\*\*El dispositivo reproducirá el mensaje #7 “Programado” después de que suelte el botón y emitirá 2 pitidos de confirmación.

| No | Mensaje de voz                                                                              | Condición                                          |   |   |
| -- | ------------------------------------------------------------------------------------------- | -------------------------------------------------- | - | - |
| 1  | Bienvenido, Alarma de humo y detector de monóxido de carbono                                | Se reproduce cuando el dispositivo está encendido. |   |   |
| 2  | Ninguna ubicación programada                                                                | Jugado por primera vez.                            |   |   |
| 3  | Para seleccionar la ubicación, mantenga presionado el botón ahora.                          | Reproducido para configurar la ubicación.          |   |   |
| 4  | Para programar la ubicación, mantenga presionado el botón después de escuchar la ubicación. | Reproducido para configurar la ubicación.          |   |   |
|    |                                                                                             |                                                    |   |   |
| 5  | Ninguna ubicación programada                                                                | Reproducido para configurar la ubicación.          |   |   |
| 6  | Ubicación                                                                                   | Reproducido para configurar la ubicación.          |   |   |
| 7  | Programado                                                                                  | Reproducido para configurar la ubicación.          |   |   |

3

| 8  | Emergencia, monóxido de carbono en\[nombre del lugar]. | Se reproduce cuando se activa una alarma.               |   |
| -- | ------------------------------------------------------ | ------------------------------------------------------- | - |
| 9  | Emergencia, Humo en\[nombre del lugar].                | Se reproduce cuando se activa una alarma.               |   |
|    |                                                        |                                                         |   |
| 10 | Evacuar                                                | Se reproduce cuando se activa una alarma.               |   |
| 11 | Sótano                                                 | Jugado para la selección de ubicación.                  |   |
| 12 | Sala                                                   | Jugado para la selección de ubicación.                  |   |
| 13 | Oficina                                                | Jugado para la selección de ubicación.                  |   |
| 14 | Recamara principal                                     | Jugado para la selección de ubicación.                  |   |
| 15 | Dormitorio                                             | Jugado para la selección de ubicación.                  |   |
| 16 | Cuarto de huéspedes                                    | Jugado para la selección de ubicación.                  |   |
| 17 | Cocina                                                 | Jugado para la selección de ubicación.                  |   |
| 18 | Comedor                                                | Jugado para la selección de ubicación.                  |   |
| 19 | Sala de estar                                          | Jugado para la selección de ubicación.                  |   |
| 20 | Lavadero                                               | Jugado para la selección de ubicación.                  |   |
| 21 | Ático                                                  | Jugado para la selección de ubicación.                  |   |
| 22 | Guardería                                              | Jugado para la selección de ubicación.                  |   |
| 23 | Baño                                                   | Jugado para la selección de ubicación.                  |   |
|    |                                                        |                                                         |   |
| 24 | Sala técnica                                           | Jugado para la selección de ubicación.                  |   |
|    |                                                        |                                                         |   |
| 25 | Armario                                                | Jugado para la selección de ubicación.                  |   |
|    |                                                        |                                                         |   |
| 26 | Salón del ático                                        | Jugado para la selección de ubicación.                  |   |
|    |                                                        |                                                         |   |
| 27 | Sala de estar del sótano                               | Jugado para la selección de ubicación.                  |   |
| 28 | Escalera                                               | Jugado para la selección de ubicación.                  |   |
| 29 | Cochera                                                | Jugado para la selección de ubicación.                  |   |
| 30 | Alquiler Apartamento                                   | Jugado para la selección de ubicación.                  |   |
| 31 | Sin ubicación                                          | Se reproduce cuando no se selecciona ninguna ubicación. |   |

* Cuando se activa una alarma de CO, humo y/o temperatura, la sirena se activará según el tiempo que se indica a continuación y seguida de indicaciones de voz para notificar al usuario que debe evacuar.

|               | Tipo de alarma |   |                                                        |                                                        | Patrón de alarma y advertencia por voz |                                                               |                                                             |                                                            |                                           |           | Condición    |   |   |   |   |   |   |   |   |   |   |
| ------------- | -------------- | - | ------------------------------------------------------ | ------------------------------------------------------ | -------------------------------------- | ------------------------------------------------------------- | ----------------------------------------------------------- | ---------------------------------------------------------- | ----------------------------------------- | --------- | ------------ | - | - | - | - | - | - | - | - | - | - |
|               |                |   |                                                        | **(Repetir)**                                          |                                        |                                                               | Reproducido después del sonido de advertencia intermitente. |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        |                                                        |                                        |                                                               |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               | Humo/Calor     |   |                                                        | Bip---bip---bip------bip---bip---bip---bip             |                                        |                                                               | cuando se activa una alarma de humo o calor. Por favor      |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   | Emergencia, Humo en\[nombre del lugar].                | Ubicación                                              | .                                      |                                                               |                                                             | tenga en cuenta que se reproducirá el mensaje de ubicación |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        |                                                        |                                        |                                                               |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        | Evacuar.                                               |                                        |                                                               |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        |                                                        |                                        | según el nombre de la ubicación preprogramada.                |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        |                                                        |                                        |                                                               |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        | **(Repetir)**                                          |                                        |                                                               | Reproducido después del sonido de advertencia intermitente. |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        |                                                        |                                        |                                                               |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               | CO             |   |                                                        | Bip-bip-bip-bip                                        |                                        |                                                               | cuando se activa una alarma de monóxido de carbono.         |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   | Emergencia, monóxido de carbono en\[nombre del lugar]. |                                                        |                                        | Tenga en cuenta que se reproducirá el mensaje de ubicación.   |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        |                                                        |                                        |                                                               |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        | Ubicación. Evacuar.                                    |                                        |                                                               |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        |                                                        |                                        | según el nombre de la ubicación preprogramada.                |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        |                                                        |                                        |                                                               |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        | **(Repetir)**                                          |                                        |                                                               |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        | Bip---bip---bip---bip-bip-bip-bip-----                 |                                        |                                                               | Reproducido después del sonido de advertencia intermitente. |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        | Bip---bip---bip                                        |                                        |                                                               | cuando hay humo/calor y monóxido de carbono                 |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
| Humo/Calor+CO |                |   | Emergencia, Humo en\[nombre del lugar]. Ubicación.     |                                                        |                                        | se detecta una alarma. Por favor tenga en cuenta la ubicación |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        |                                                        |                                        |                                                               |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        | Evacuar.                                               |                                        |                                                               |                                                             |                                                            | El aviso se reproducirá de acuerdo con el |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        | Emergencia, monóxido de carbono en\[nombre del lugar]. |                                        |                                                               | nombre de ubicación preprogramado.                          |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        | Ubicación. Evacuar.                                    |                                        |                                                               |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        |                                                        |                                        |                                                               |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        | **(Repetir)**                                          |                                        |                                                               | Jugó                                                        | un sonido de advertencia                                   | cuando                                    | un ladrón |              |   |   |   |   |   |   |   |   |   |   |
|               | Insectos       |   |                                                        | Sonido de alarma durante 6,5 segundos.                 |                                        |                                                               |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        |                                                        | se detecta una alarma.                 |                                                               |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        |                                                        |                                        |                                                               |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        |                                                        |                                        |                                                               |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        | **(Repetir)**                                          |                                        |                                                               | Jugó                                                        |                                                            | suena cuando un                           | Agua      | la alarma es |   |   |   |   |   |   |   |   |   |   |
|               | Agua           |   |                                                        | Bip-bip-bip-bip durante 6,5 segundos                   |                                        |                                                               |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        |                                                        | detectado.                             |                                                               |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        |                                                        |                                        |                                                               |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |
|               |                |   |                                                        |                                                        |                                        |                                                               |                                                             |                                                            |                                           |           |              |   |   |   |   |   |   |   |   |   |   |

![](<.gitbook/assets/14 (34).png>)

* _**Verificación de incendio**_
  * La verificación de incendios se puede utilizar para configurar el temporizador de verificación mediante el comando de configuración de Z-Wave para el detector SDCO. Cuando se configura el temporizador de verificación de incendios, el detector SDCO comenzará a contar el temporizador de verificación de incendios cuando se active el dispositivo. Se pueden configurar hasta 150 segundos (predeterminado: 0 segundos). Consulte la página 10.\*\*“Configuraciones”\*\*sección para más detalles.
  * Si la función de verificación de incendio está habilitada, el LED rojo parpadeará rápidamente 3 veces cada 8 segundos si se detecta humo durante este período. Una vez que expire el temporizador de verificación de incendio, el detector SDCO activará la alarma de incendio si la concentración de humo excede el umbral de detección.
* _**Detección de alarma**_

![](<.gitbook/assets/15 (34).png>)

El detector SDCO activará la alarma de incendio cuando se active cualquiera de sus funciones de detección de humo o de detección de calor alto. Cuando se activa una alarma, el detector SDCO transmitirá una señal de alarma y activará la alarma con su zumbador incorporado; el LED rojo parpadeará rápidamente.

**Detección de humo:**

* El detector SDCO comprueba la concentración de humo cada 8 segundos.

4

* Siempre que la concentración de humo supere el umbral de detección, el detector SDCO enviará una señal activa al panel de control y activará la alarma.
* Si la concentración de humo persiste, el Detector SDCO seguirá enviando la señal activa cada minuto al Panel de Control.
* Si no se detecta humo durante 20 veces de detección continua, el detector SDCO transmitirá una señal de restauración.

**Detección de Calor:**

* El detector SDCO comprueba la temperatura cada 10 segundos.
* La alarma se activará en las siguientes condiciones:
  * Cuando la temperatura aumenta 8,25 °C por minuto (tasa de aumento).
  * Cuando la temperatura supera los 57,25°C (calor alto).
* Si no se detecta calor alto durante 16 tiempos de detección continuos, el detector SDCO transmitirá una señal de restauración.
* Si la alarma se activó por una condición de calor alto (57,25 °C), la temperatura debe caer por debajo de 49 °C para que el detector deje de dar la alarma.

**Detección de monóxido de carbono:**

 El sensor de CO verificará el nivel de concentración de CO cada 16 segundos; si el nivel de concentración excede el umbral de detección, el detector SDCO transmitirá una señal de alarma y activará la alarma con su zumbador incorporado.

 El sensor de CO cuenta con una función de autodiagnóstico y comprobará periódicamente el estado del sensor cada 12 horas.

 La alarma se activará después de que se detecte la concentración de CO según el período de tiempo en la siguiente tabla: (cumple con la norma EN-50291)

| **nivel de concentración de CO** | **Tiempo necesario antes de dar la alarma** |
| -------------------------------- | ------------------------------------------- |
| 30 +/- 10% ppm                   | N / A                                       |
| 50 +/- 10%ppm                    | 60\~90 minutos                              |
| 100 +/- 10% ppm                  | 10\~40 minutos                              |
| 300 +/- 10% ppm                  | Menos de 3 minutos                          |

 La alarma se activará después de que se detecte la concentración de CO según el período de tiempo en la siguiente tabla: (cumple con el estándar UL-2034)

| **nivel de concentración de CO** | **Tiempo necesario antes de dar la alarma** |                 |
| -------------------------------- | ------------------------------------------- | --------------- |
| 30                               | +/- 3% ppm                                  | N / A           |
| 70                               | +/- 5% ppm                                  | N / A           |
| 70                               | +/- 5% ppm                                  | 60\~240 minutos |
| 150 +/- 5% ppm                   | 10\~50 minutos                              |                 |
| 400                              | +/- 10% ppm                                 | 4\~15 minutos   |

 Una vez que el nivel de concentración de CO excede el umbral y persiste durante el tiempo que se indica en la tabla anterior, el detector SDCO transmitirá la señal al coordinador Z-Wave y activará la alarma con su sirena incorporada.

 Si el CO cae por debajo de 30 ppm durante 10 tiempos de detección continuos, el SDCO transmitirá una señal de restauración.

**Detección de temperatura y humedad:**

El sensor de temperatura y humedad transmitirá señales de temperatura y humedad regularmente según la configuración. El intervalo predeterminado de fábrica es de 30 a 33 minutos.

*
  * El detector SDCO enviará una señal de temperatura cuando la temperatura cambie en +/- 2°C.
  * También puede presionar el botón una vez para transmitir una señal de temperatura manualmente.
* _**Detección de infrarrojos**_
  * El detector SDCO transmitirá una señal al panel de control si se detecta algún movimiento dentro de la cobertura de detección de infrarrojos. El timbre no sonará y el LED no parpadeará. Consulte su Panel de control para obtener más detalles.
  * En 60 segundos, si no hay más detección de movimiento o alertas, el IR se restaurará y volverá a su funcionamiento normal.
* _**Prueba del detector SDCO**_

![](<.gitbook/assets/16 (36).png>) ![](<.gitbook/assets/17 (29).png>)

Al presionar el botón del detector SDCO, puede probar si el detector SDCO está funcionando normalmente.

*
  * Si el detector SDCO funciona normalmente, el LED rojo parpadeará una vez seguido de un pitido de dos tonos.
  * Si se emiten tres pitidos de 2 tonos (DO-DI DO-DI DO-DI), significa que el sensor de humo está averiado.
  * Si se emiten 5 pitidos (DO-Bi-Bi-Bi-DO), significa que el sensor de calor está averiado.
  * Si se emiten 7 pitidos (Bi-Bi-Bi-DO-Bi-Bi-Bi), significa que el sensor de CO está averiado.
* _**Silencio de alarma**_
  * Hay dos formas de poner manualmente el SDCO en modo de silencio de alarma: presionando el botón o enviando**Control de escena/sirena o control de encendido/apagado de sirena**dominio. Con cualquiera de los métodos, el SDCO entrará en el modo de silencio de alarma. Después del período, se enviará una señal de restauración. Consulte la página 8.**“Emergencia por humo/Emergencia por humo despejada**_**, Emergencia de calor eliminada y Emergencia de CO/**_\*\*Emergencia de CO despejada”\*\*sección para más detalles.

![](<.gitbook/assets/18 (35).png>)

**Presionando el botón:**

* Cuando el detector de humo emite una alarma, al presionar el botón el detector de humo entrará en modo de silencio de alarma para silenciar la alarma.

**Envío del comando de control de escena/sirena o control de encendido/apagado de sirena:**

* El comando de control de escena/sirena le permite programar diferentes tipos de alarma con indicación de ubicación.**Tenga en cuenta que este comando NO PUEDE usarse para detener la sirena y las indicaciones de voz de una alarma real.**
* Para apagar la sirena y las indicaciones de voz usando este comando, configure el Conjunto básico: 0x00. El detector SDCO entrará entonces en modo de silencio de alarma.
* El comando de control de encendido/apagado de sirena le permite controlar la sirena de una alarma de humo.**Tenga en cuenta que este comando NO PUEDE usarse para detener la sirena y las indicaciones de voz de una alarma real.**
* Para apagar la sirena usando este comando, configure el Conjunto básico: 0x00. El detector SDCO entrará entonces en modo de silencio de alarma.
* Durante el período de silencio de la alarma, el LED rojo parpadeará una vez por segundo. El detector de humo seguirá monitoreando la concentración de humo durante el período de silencio de la alarma:
  1. Una vez transcurrido el período de silencio de la alarma, si la concentración de humo ha caído por debajo del umbral de alarma, el detector de humo emitirá un pitido de dos tonos y volverá al funcionamiento normal sin hacer sonar la alarma.

5

*
  1. Si la concentración de humo aún excede el umbral de alarma, el detector de humo comenzará a sonar nuevamente.
  2. Si la concentración de humo continúa aumentando durante el período de silencio de alarma y excede un segundo umbral de alarma, el detector SDCO comenzará a emitir la alarma nuevamente. Una alarma activada al exceder el segundo umbral de alarma podría silenciarse presionando el botón.
* _**Recalibración**_

![](<.gitbook/assets/19 (35).png>)

El detector SDCO calibrará su sensor detector de humo cada vez que se aplique energía para garantizar una sensibilidad óptima al humo. Después de la instalación, las condiciones de funcionamiento del detector de humo pueden variar después de un tiempo, lo que puede afectar su función de detección de humo y requerir recalibración. Hay dos formas de recalibrar el detector de humo: calibración automática y calibración manual.

**Calibración automática:**

* Después de encenderlo, el detector de humo realizará una calibración automática después de 4 horas.
* Después de la primera calibración automática, el detector de humo realizará una calibración automática todos los meses. Durante el proceso de autocalibración, el detector de humo no emitirá ningún sonido.
* Si la calibración automática falla, el LED ámbar parpadeará cada segundo junto con pitidos continuos.
* Cuando falla la calibración automática del detector de humo, la función de alarma de humo seguirá funcionando normalmente utilizando el valor umbral tomado de la última calibración exitosa.

**Calibración manual:**

* La calibración manual se puede realizar en cualquier momento que se desee:
  1. Mantenga presionado el botón durante 10 segundos y suéltelo cuando el detector de humo emita 2 pitidos.
  2. El detector de humo entrará en proceso de calibración. El indicador LED parpadeará cada 2 segundos.
  3. Una vez que el detector de humo finalice la recalibración, emitirá dos pitidos rápidos para indicarlo. El LED se apagará.
  4. Si el proceso de calibración falla, el detector de humo emitirá un sonido de alarma. Retire y vuelva a insertar la batería para reiniciar el proceso nuevamente.
* _**Identificar el dispositivo**_

![](<.gitbook/assets/20 (25).png>)

La función está disponible para que usted identifique el detector SDCO entre sus dispositivos enviando comandos Z-Wave al Gateway. Si el dispositivo recibe la señal correctamente, el LED del dispositivo comenzará a parpadear. El número de ciclos de parpadeo se puede programar mediante los comandos CC del indicador Z-Wave. Por favor refiérase a "\_**Formato de datos de clase de comando”**\_sección para más detalles.

* _**Restablecimiento de fábrica**_

_(Utilice el restablecimiento de fábrica únicamente cuando falte el panel de control/puerta de enlace de la red o no esté operativo)._

* Mantenga presionado el botón del detector SDCO durante 20 segundos. Suelte el botón cuando escuche 3 pitidos para realizar el restablecimiento de fábrica.

_\\_

* El restablecimiento de fábrica del SDCO lo restaurará a la configuración predeterminada de fábrica (excluido de la red Z-Wave). La puerta de enlace o el panel de control Z-Wave seguirán manteniendo su configuración Z-Wave. Consulte el manual de la puerta de enlace o del panel de control sobre cómo eliminar la configuración Z-Wave del SDCO.

**Mantenimiento y limpieza**

El mantenimiento y la limpieza regulares ayudarán a mantener su detector SDCO en buen estado de funcionamiento.

* Pruebe el detector SDCO semanalmente para verificar que la alarma suene y los indicadores funcionen correctamente.
* Limpie el detector SDCO al menos una vez cada 6 meses.
  * Aspire suavemente la suciedad, el polvo y las pequeñas partículas acumuladas en la cámara y las ranuras de detección de humo.
  * Limpie la carcasa pasándola bien con un paño húmedo y séquela. No deje entrar agua dentro de la alarma.
  * Nunca utilice agentes de limpieza, detergentes o disolventes en el detector.
* Evite rociar ambientadores, lacas para el cabello u otros aerosoles cerca del detector SDCO.
* No pinte ni modifique el detector bajo ninguna circunstancia.

**Vencimiento**

El detector SDCO tiene una vida útil máxima de**10 años**desde la fecha de instalación. Debe reemplazar el detector SDCO inmediatamente después de 10 años de servicio.

Se recomienda escribir la fecha de "Reemplazo antes de" (10 años a partir de la fecha de instalación) en la parte posterior del detector antes de la instalación.

**Instalación**

* _**Guía de instalación**_
  * Se recomienda instalar el dispositivo en la zona central del techo. Cuando se monta en el techo, el PIR tiene un mejor rendimiento de detección contra el movimiento horizontal.
  * La altura de montaje ideal para el detector SDCO es de 2,4 a 3 metros. El montaje por encima de 3 metros puede afectar el rendimiento de la detección.
  * No instale el detector en las siguientes ubicaciones:
    * La cocina: el humo de la cocina puede provocar una alarma no deseada.
    * Cerca de un ventilador, una lámpara fluorescente o un aire acondicionado: las corrientes de aire que emiten pueden afectar la sensibilidad del detector.
    * Cerca de vigas del techo o sobre un gabinete: el aire estancado en estas áreas puede afectar la sensibilidad del detector.
    * En la cima de un “**A**”tipo de marco de techo.
  * El detector SDCO puede admitir una cobertura de detección dentro de un radio de 4 metros.

6

* _**Installation Recommendation**_
  * **Limitaciones**
    * No exponga el detector SDCO a la luz solar directa.
    * Evite instalar el detector SDCO en áreas donde dispositivos como aires acondicionados o calentadores puedan causar cambios rápidos de temperatura en el área de detección.
    * Evite grandes obstáculos en el área de detección.
    * No apunte directamente a fuentes de calor, como fuegos o calderas, ni tampoco encima de radiadores.
* _**Montaje del detector SDCO**_

\*\*Paso 1.\*\*Antes de comenzar, busque el disyuntor o la caja de fusibles.

\*\*Paso 2.\*\*Una vez que lo haya encontrado, abra la puerta y apague el interruptor principal.

\*\*Paso 3.\*\*Coloque el detector SDCO en la ubicación de montaje deseada y utilice la prueba de rango para asegurarse de que el panel de control pueda recibir el SDCO en la ubicación de montaje.

\*\*Etapa 4.\*\*Se proporcionan dos conectores de empalme Wago 221. Saque un conector. Levante la palanca e inserte el cable blanco.

\*\*Paso 5.\*\*Empuje la palanca hacia abajo. La carcasa transparente le permite comprobar si el cable está conectado correctamente.**Asegúrese de que el cable esté bien sujeto en su lugar antes de continuar.**

\*\*Step 6.\*\*Repita los pasos 4 y 5 para insertar el cable negro. Insertar los dos cables en el mismo lado (derecho), como se muestra a continuación, de los dos conectores facilita la instalación en los siguientes pasos.

\*\*Paso 7.\*\*Inserte los cables de CA en los dos conectores respectivamente, como se muestra a continuación.

_Figura 1. Inserte los cables blanco y negro._

_Figura 2. Compruebe si los cables_

_están conectados correctamente._

_Figura 3. Inserte los cables de CA._

\*\*Paso 8.\*\*El detector SDCO tiene un soporte de montaje para instalación en el techo. El soporte proporciona flexibilidad bidireccional.

\*\*Paso 9.\*\*Utilice los 4 orificios del soporte como plantilla para perforar orificios e insertar tacos de pared si es necesario.

\*\*Paso 10.\*\*El usuario puede girar el soporte de montaje en sentido horario o antihorario para bloquear el gancho. Asegúrese de que los tacos de pared estén al ras con la superficie de montaje.

\*\*Paso 11.\*\*Una vez que la posición sea satisfactoria, atornille el soporte de montaje al techo.

\*\*Paso 12.\*\*Limpie bien el polvo, ya que puede ensuciar el sensor e impedir que funcione correctamente en caso de una emergencia.

\*\*Paso 13.\*\*Utilice un destornillador Phillips para quitar el tornillo de fijación del compartimiento de la batería. Retire la tapa del compartimiento de la batería y conecte el cable a la placa PCB del detector SDCO. El diseño infalible proporciona un procedimiento de instalación sencillo.

\*\*Paso 14.\*\*Coloque los dos conectores de empalme en el espacio al lado de la batería recargable.

\*\*Paso 15.\*\*Vuelva a colocar la tapa del compartimento de la batería en su lugar y apriete el tornillo de fijación. El orificio preperforado en la cubierta mejora su flexibilidad.

\*\*Paso 16.\*\*El SDCO tiene tres muescas en su cubierta posterior (como se muestra a continuación) para enganchar el dispositivo al soporte de montaje.

\*\*Paso 17.\*\*Sostenga el detector SDCO con especial cuidado y enganche el detector en el soporte de montaje.

\*\*Paso 18.\*\*Gire el detector SDCO en el sentido de las agujas del reloj para bloquear el gancho. La instalación ya está completa.

\*\*Paso 19.\*\*Encienda el interruptor de alimentación principal para continuar con la operación.

**Información de onda Z**

\*\*Tipo de dispositivo:\*\*Alarma de humo con notificación de sensor

\*\*Tipo de rol:\*\*Siempre en esclavo (AOS)

\*\*Identificación del fabricante:\*\*0x018E

\*\*Identificación del tipo de producto:\*\*0x0003

\*\*ID del Producto:\*\*0x0115

\*\*Grupo de asociación máximo:\*\*3

**Clase de comando admitida:**

| **Clase de comando**                | **Versión** | **Clase de seguridad requerida**     |
| ----------------------------------- | ----------- | ------------------------------------ |
|                                     |             |                                      |
| Asociación                          | 2           | Clase de seguridad más alta otorgada |
|                                     |             |                                      |
| Información del grupo de asociación | 3           | Clase de seguridad más alta otorgada |
|                                     |             |                                      |
| Básico                              | 2           | Clase de seguridad más alta otorgada |
|                                     |             |                                      |
| Batería                             | 1           | Clase de seguridad más alta otorgada |
|                                     |             |                                      |
| Sensor multinivel                   | 11          | Clase de seguridad más alta otorgada |
|                                     |             |                                      |
| Activación de escena                | 1           | Clase de seguridad más alta otorgada |
|                                     |             |                                      |
|                                     |             | 7                                    |

| Notificación                                | 8 | Clase de seguridad más alta otorgada |
| ------------------------------------------- | - | ------------------------------------ |
|                                             |   |                                      |
| Restablecimiento del dispositivo localmente | 1 | Clase de seguridad más alta otorgada |
|                                             |   |                                      |
| Metadatos de actualización de firmware      | 5 | Clase de seguridad más alta otorgada |
|                                             |   |                                      |
| Específico de fabricación                   | 2 | Clase de seguridad más alta otorgada |
|                                             |   |                                      |
| Multicanal                                  | 4 | Clase de seguridad más alta otorgada |
|                                             |   |                                      |
| Asociación multicanal                       | 3 | Clase de seguridad más alta otorgada |
|                                             |   |                                      |
| Nivel de potencia                           | 1 | Clase de seguridad más alta otorgada |
|                                             |   |                                      |
| Cambiar binario                             | 2 | Clase de seguridad más alta otorgada |
|                                             |   |                                      |
| Configuración                               | 1 | Clase de seguridad más alta otorgada |
|                                             |   |                                      |
| Estado de funcionamiento del termostato     | 2 | Clase de seguridad más alta otorgada |
|                                             |   |                                      |
| Versión                                     | 3 | Clase de seguridad más alta otorgada |
|                                             |   |                                      |
| Servicio de transporte                      | 2 | Ninguno                              |
|                                             |   |                                      |
| Información sobre Z-Wave Plus               | 2 | Ninguno                              |
|                                             |   |                                      |
| Seguridad                                   | 1 | Ninguno                              |
|                                             |   |                                      |
| Seguridad 2                                 | 1 | Ninguno                              |
|                                             |   |                                      |
| Supervisión                                 | 1 | Ninguno                              |
|                                             |   |                                      |

* _**Grupos de Z-Wave (clase de comando de asociación versión 2)**_

Grupo 1 para “LifeLine”: (nodo máximo: 5)

Batería CC (COMANDO\_CLASE\_BATERÍA)

SensorMutinivel CC, V11 (COMANDO\_CLASE\_SENSOR\_MULTI NIVEL)

Notificación CC,V8 (COMANDO\_CLASE\_NOTIFICACIÓN)

CC básico (COMANDO\_CLASE\_BÁSICO)

Restablecimiento del dispositivo localmente CC (COMANDO\_CLASE\_DISPOSITIVO\_REINICIAR\_EN LA ZONA)

Grupo 2 para “Conjunto básico de sensores”: (nodo máximo: 5)

CC básico (COMANDO\_CLASE\_BÁSICO)

Cuando el Detector de Humo esté activo, enviará el Conjunto Básico (0xFF) en el Grupo 2.

Cuando se restablezca el detector de humo, enviará la configuración básica (0x00) en el grupo 2.

Grupo 3 para “Conjunto de escena”: (nodo máximo: 5)

Activación de escena CC (COMANDO\_CLASE\_ESCENA\_ACTIVACIÓN)

Después de agregar el Grupo 3, enviará un comando de activación de escena cuando suene la alarma SC, HD o CO.

Después de agregar el Grupo 3, enviará el comando de activación de escena cuando se restablezca SC, HD o CO.

Por favor refiérase a\_Tabla 2\_Control de sirena, enviará 00 00 cuando se restablezca el detector de humo.

* _**Formato de datos de clase de comando**_
  * **AC Failure/Restore: \[DOMINIO\_CLASE\_NOTIFICACIÓN]\[NOTIFICACIÓN\_INFORME]**
* Cuando se detecta una falla de energía de CA, el SDCO enviará una señal de falla de CA al Panel de control. Cuando se restablezca la alimentación de CA, el SDCO enviará una señal de restauración al panel de control.

|  | Fallo de CA:        | 00 00 00 FF 08 02 00 00 |
| - | ------------------- | ----------------------- |
|  | Restauración de CA: | 00 00 00 FF 08 03 00 00 |

* **Batería:\[DOMINIO\_CLASE\_BATERÍA]\[BATERÍA\_INFORME]**
  * 0x64 --- 100% batería llena
  * 0x5A --- 90% de batería
  * 0x50 --- 80% de batería
  * 0x46 --- 70% de batería
  * 0x3C --- 60% de batería
  * 0x32 --- 50% de batería
  * 0x28 --- 40% de batería
  * 0x1E --- 30% de batería
  * 0x14 --- 20% de batería baja
  * 0xFF --- Batería agotada (cortada)
  * Corte --- El dispositivo dejará de funcionar y los LED rojo y ámbar parpadearán cada 4 segundos.
  * Si el interruptor de la batería está configurado en APAGADO, el SDCO enviará 00% para notificar al usuario. Tenga en cuenta que cuando se configura en APAGADO, la batería no se cargará cuando la alimentación de CA esté conectada y tampoco servirá como fuente de energía de respaldo cuando falta la alimentación de CA.

8

*
  * Cuando se aplica alimentación de CA, la batería recargable se cargará al mismo tiempo y el SDCO informará su porcentaje de batería al portal/panel de control respectivamente al 20%, 30%, 40%, 50%, 60%, 70%. , 80%, 90% y 100%.
  * Cuando se corta la alimentación de CA o se produce un corte de energía, el SDCO utilizará su batería recargable incorporada e informará su porcentaje de batería. Después de que se vuelva a aplicar energía de CA, el SDCO informará el porcentaje de batería detectado. Cuando el voltaje de la batería detectado es de 4,3 V o superior, el SDCO informará su porcentaje de batería al 60 % y comenzará a cargar la batería. Cuando el voltaje de la batería detectado es inferior a 4,3 V, el SDCO informará su porcentaje de batería respectivamente y comenzará a cargar la batería.
* **Informe de temperatura/humedad:\[DOMINIO\_CLASE\_SENSOR\_MULTI NIVEL]\[SENSOR\_MULTI NIVEL\_INFORME]**
  * El usuario puede presionar el botón una vez para enviar información de temperatura y humedad al Panel de control.
* Si señal de temperatura 01 42**08CC**es transmitida:

**08CC**se puede ver como 0x**08CC**en número hexadecimal. Puede convertir hexadecimal a decimal y dividir por 100 para verificar los datos de temperatura (en Celsius).

0x08CC=2252=25,52 ℃.

*
  * Si señal de humedad 05 02**00 nido**es transmitida:

**003C**se puede ver como 0x**003C**en número hexadecimal. Puede convertir hexadecimal a decimal para comprobar el nivel de humedad (en porcentaje).

003C=0x003C=60%

* **Prueba de alarma de humo/Prueba de alarma de humo desactivada::\[DOMINIO\_CLASE\_NOTIFICACIÓN]\[NOTIFICACIÓN\_INFORME]**
  * El usuario puede presionar el botón una vez para enviar señales de prueba de alarma de humo y prueba de alarma de humo desactivada al panel de control.
  * Prueba de alarma de humo: 00 00 00 FF 01 03 00
  * Prueba de alarma de humo desactivada: 00 00 00 FF 01 00 01 03
  * 01=tipo de alarma; 03=prueba de alarma de humo
* **Emergencia por humo/Emergencia por humo eliminada:\[DOMINIO\_CLASE\_NOTIFICACIÓN]\[NOTIFICACIÓN\_INFORME]**

 Alarma de humo: 00 00 00 FF 01 01 0B 77 06 00 42 61 73 65 6D 65 6E 74

Nota: 0B 77 06 00 42 61 73 65 6D 65 6E 74 es cuando la ubicación es “Sótano”.

* Se activará una alarma de humo después de que la concentración de humo supere el umbral de detección, o se activará manualmente enviando comandos, el SDCO se puede silenciar y entrar en el modo de silencio de alarma. Por favor refiérase a "\_**Silencio de alarma**”sección para más detalles.\_La SDCO enviará un informe de silencio de alarma en las tres condiciones siguientes:

|  Cuando la concentración de humo haya caído por debajo del umbral de alarma, el SDCO enviará:     | 00 00 00 FF 01 06 01 01 |   |   |   |   |
| -------------------------------------------------------------------------------------------------- | ----------------------- | - | - | - | - |
|  Cuando el usuario presiona el botón para detener la alarma, el SDCO enviará:                     |                         |   |   |   |   |
| 00 00 00 FF 01 06 01 02                                                                            |                         |   |   |   |   |
|  Cuando el usuario envía un comando de apagado de sirena para detener la alarma, el SDCO enviará: |                         |   |   |   |   |
| 00 00 00 FF 01 06 01 03                                                                            |                         |   |   |   |   |
| Por favor refiérase a "**Comando de control de encendido/apagado de sirena**" para detalles.       |                         |   |   |   |   |

*
  * Nota: Si se activan varias alarmas, los eventos de silencio de alarma se enviarán respectivamente.
  * Después de silenciar el SDCO, si no se detecta humo durante 20 veces de detección continua, el SDCO transmitirá una señal de restauración: 00 00 00 FF 01 00 01 01.
* **Emergencia por calor/Emergencia por calor eliminada:\[DOMINIO\_CLASE\_NOTIFICACIÓN]\[NOTIFICACIÓN\_INFORME]**

|  Alarma de calor: | 00 00 00 FF | 04 01 | 0Б штш 06 00 42 61 штз 65 ШД 65 ШТЕ штч               |
| ------------------ | ----------- | ----- | ----------------------------------------------------- |
| Nota:              | 0B 77 06 00 | 42 61 | 73 65 6D 65 6E 74 es cuando la ubicación es “Sótano”. |

* Se activará una alarma de calor después de que el SDCO alcance la condición de tasa de aumento o calor alto, o se activará manualmente enviando comandos, el SDCO se puede silenciar y entrar en el modo de silencio de alarma. Por favor refiérase a "\_**Silencio de alarma**”sección para más detalles.\_La SDCO enviará un informe de silencio de alarma en las tres condiciones siguientes:

|  Cuando la temperatura haya caído por debajo del umbral de alarma, el SDCO enviará:               | 00 00 00 FF 04 09 01 01 |   |   |   |   |
| -------------------------------------------------------------------------------------------------- | ----------------------- | - | - | - | - |
|  Cuando el usuario presiona el botón para detener la alarma, el SDCO enviará:                     |                         |   |   |   |   |
| 00 00 00 FF 04 09 01 02                                                                            |                         |   |   |   |   |
|  Cuando el usuario envía un comando de apagado de sirena para detener la alarma, el SDCO enviará: |                         |   |   |   |   |
| 00 00 00 FF 01 06 01 03                                                                            |                         |   |   |   |   |
| Por favor refiérase a "**Comando de control de encendido/apagado de sirena**" para detalles.       |                         |   |   |   |   |

*
  * Nota: Si se activan varias alarmas, los eventos de silencio de alarma se enviarán respectivamente.
  * Después de silenciar el SDCO, si no se detecta calor alto durante 16 tiempos de detección continuos, el SDCO transmitirá una señal de restauración: 00 00 00 FF 04 00 01 01.
* **Emergencia de CO/Emergencia de CO despejada:\[DOMINIO\_CLASE\_NOTIFICACIÓN]\[NOTIFICACIÓN\_INFORME]**

 Alarma de CO: 00 00 00 FF 02 01 0B 77 06 00 42 61 73 65 6D 65 6E 74

Nota: 0B 77 06 00 42 61 73 65 6D 65 6E 74 es cuando la ubicación es “Sótano”.

* Se activará una alarma de CO después de que la concentración de CO supere el umbral de detección, o bien se activará manualmente enviando comandos, el SDCO se puede silenciar y entrar en el modo de silencio de alarma. Por favor refiérase a "\_**Silencio de alarma**”sección para más detalles.\_La SDCO enviará un informe de silencio de alarma en las tres condiciones siguientes:

|                                                                             | Cuando la concentración de CO haya caído por debajo de 30 ppm, el SDCO enviará: | 00 00 00 FF 02 06 01 01 |   |   |   |   |
| ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------- | ----------------------- | - | - | - | - |
|                                                                             |                                                                                 |                         |   |   |   |   |
| Cuando el usuario presiona el botón para detener la alarma, el SDCO enviará: | 00 00 00 FF 02 06 01 02                                                         |                         |   |   |   |   |
|                                                                              |                                                                                 |                         |   |   |   |   |

**Tenga en cuenta que una alarma activada al exceder el segundo umbral de alarma se puede silenciar presionando el botón.**

|  Cuando el usuario envía un comando de apagado de sirena para detener la alarma, el SDCO enviará: | 00 00 00 FF 01 06 01 03 |   |   |   |
| -------------------------------------------------------------------------------------------------- | ----------------------- | - | - | - |
|                                                                                                    |                         |   |   |   |

*
  * Nota: Si se activan varias alarmas, los eventos de silencio de alarma se enviarán respectivamente.
  * Después de silenciar el SDCO, si el CO cae por debajo de 30 ppm durante 10 tiempos de detección continuos, el SDCO transmitirá una señal de restauración: 00 00 00 FF 02 00 01 01.
* **Ubicación:**
  * Cuando se activa una alarma de humo, una alarma de calor o una alarma de CO, enviará una notificación con el nombre de la ubicación. Para los modelos conectados en serie, también se transmitirá la ubicación preprogramada.
  * Si se activa una alarma de humo en el sótano, 00 00 00 FF 01 01**0Б штш 06 00 42 61 штз 65 ШД 65 ШТЕ штч**se enviará, como se muestra en la Tabla 1 a continuación

_**tabla 1**_

| 1 | V1 | Tipo de alarma  | 0x00 | No se ha implementado |
| - | -- | --------------- | ---- | --------------------- |
|   |    |                 |      |                       |
| 2 | V1 | Nivel de alarma | 0x00 | No se ha implementado |
|   |    |                 |      |                       |

9

| 3  | Reservado                             | 0x00           | Campo reservado                              |
| -- | ------------------------------------- | -------------- | -------------------------------------------- |
|    |                                       |                |                                              |
| 4  | Estado de notificación                | 0xFF           | El informe no solicitado está activado       |
|    |                                       |                |                                              |
| 5  | Tipo de notificación                  | 0x01           | Alarma de humo                               |
|    |                                       |                |                                              |
| 6  | Evento                                | 0x01           | Humo detectado                               |
|    |                                       |                |                                              |
| 7  | Longitud de los parámetros del evento | 0x0B           | Longitud del parámetro del evento = 11       |
|    |                                       |                |                                              |
| 8  | Evento Parámetro 1                    | 0barrido       | Nombre de nodo y ubicación CC ID             |
|    |                                       |                |                                              |
| 9  | Parámetro del evento 2                | 0x06           | ID del comando Informe de ubicación del nodo |
|    |                                       |                |                                              |
| 10 | Evento Parámetro 3                    | 0x00           | Parámetro de comando: Char = ASCII           |
|    |                                       |                |                                              |
| 11 | Evento Parámetro 4                    | 0x42           | Cmd Parm: Ubicación del nodo Char 1 = B      |
|    |                                       |                |                                              |
| 12 | Evento Parámetro 5                    | 0x61           | Cmd Parm: Ubicación del nodo Char 2 = a      |
|    |                                       |                |                                              |
| 13 | Evento Parámetro 6                    | 0 como barrido | Cmd Parm: Ubicación del nodo Char 3 = s      |
|    |                                       |                |                                              |
| 14 | Evento Parámetro 7                    | 0x65           | Cmd Parm: Ubicación del nodo Char 4 = e      |
|    |                                       |                |                                              |
| 15 | Evento Parámetro 8                    | 0x6D           | Cmd Parm: Ubicación del nodo Char 5 = m      |
|    |                                       |                |                                              |
| 16 | Evento Parámetro 9                    | 0x65           | Cmd Parm: Ubicación del nodo Char 6 = e      |
|    |                                       |                |                                              |
| 17 | Evento Parámetro 10                   | 0x6E           | Cmd Parm: Ubicación del nodo Char 7 = n      |
|    |                                       |                |                                              |
| 18 | Evento Parámetro 11                   | 0x74           | Cmd Parm: Ubicación del nodo Char 8 = t      |
|    |                                       |                |                                              |

* **Informe de apertura/cierre de manipulación:\[DOMINIO\_CLASE\_NOTIFICACIÓN]\[NOTIFICACIÓN\_INFORME]**
  * El SDCO está protegido por un interruptor antisabotaje que se comprime cuando el SDCO se engancha al soporte de montaje. Cuando se retira el SDCO del soporte de montaje, el interruptor de manipulación se activará y el SDCO enviará una señal de apertura de manipulación al panel de control del sistema para recordarle al usuario esta condición.
  * Sabotaje abierto: 00 00 00 FF 07 03 00 00
  * Después de que el SDCO esté enganchado al soporte de montaje, enviará una señal de cierre antisabotaje al panel de control.
* **Sensor PIR**
  *
    * El SDCO transmitirá una señal al panel de control si se detecta algún movimiento dentro de la cobertura de detección de infrarrojos.
  * PIR activo: 00 00 00 FF 07 07 0B 77 06 00 42 61 73 65 6D 65 6E 74
  * Nota: 00 00 00 FF 07 07 0B 77 06 00 42 61 73 65 6D 65 6E 74 es cuando la ubicación es “Sótano”.
  * Restaurar PIR: 00 00 00 FF 07 00 01 07
* **Control de escena/sirena:\[DOMINIO\_CLASE\_ESCENA\_ACTIVACIÓN]\[ESCENA\_ACTIVACIÓN\_SET] (para modelos conectados en serie):**
  * ID de escena: tipo de alarma (Tabla 2)
  * Duración de la atenuación: 0x00\~0x14

_**Tabla 2**_

| btkh\~7 | Bit 4    | Bit 3          | Bit 2        | Bit 1                     | Bit 0     |   |
| ------- | -------- | -------------- | ------------ | ------------------------- | --------- | - |
|         |          |                |              |                           |           |   |
|         |          |                |              |                           |           |   |
|         |          |                |              |                           | Alarma SD |   |
| 0       | Insectos | Alarma de agua | Alarma de CO | alarma de alta definición |           |   |
|         |          |                |              |                           |           |   |

* Nombre de ubicación /Bit4\~0/Num, como se muestra en la Tabla 3 a continuación

_**Tabla 3**_

*
  * Aviso en inglés

| Núm (hexadecimal) | Nombre del lugar    | Núm (hexadecimal) | Nombre del lugar         |
| ----------------- | ------------------- | ----------------- | ------------------------ |
|                   |                     |                   |                          |
| 0                 | Sótano              | B                 | Guardería                |
| 1                 | Sala                | C                 | Baño                     |
| 2                 | Oficina             | D                 | Sala técnica             |
| 3                 | Recamara principal  | Y                 | Armario                  |
| 4                 | Dormitorio          | F                 | Salón del ático          |
| 5                 | Cuarto de huéspedes | 10                | Sala de estar del sótano |
| 6                 | Cocina              | 11                | Escalera                 |
| 7                 | Comedor             | 12                | Cochera                  |
| 8                 | Sala de estar       | 13                | Alquiler Apartamento     |
| 9                 | Lavadero            | 14                | Sin ubicación            |
| A                 | Ático               |                   |                          |

* Aviso noruego

Núm (hexadecimal)

Nombre del lugar

Núm (hexadecimal)

10

Nombre del lugar

| 0 | Sala de estar       | B  | Trastero           |
| - | ------------------- | -- | ------------------ |
| 1 | Cocina              | C  | Baño               |
| 2 | Pasillo             | D  | Sala técnica       |
| 3 | Recamara principal  | Y  | Armario            |
| 4 | Cuarto de los niños | F  | Piso superior      |
| 5 | Dormitorio          | 10 | Abajo              |
| 6 | Comida              | 11 | Escalera           |
| 7 | Lavadero            | 12 | Cochera            |
| 8 | Ático               | 13 | Unidad de alquiler |
| 9 | Oficina             | 14 | El edificio        |
| A | Sótano              |    |                    |

*
  *
    * Para activar el timbre de la puerta, configure ID de escena: 0x00 y Duración de atenuación: 0xF1.
    * Para detener la sirena y los mensajes de voz generados por este comando, configure ID de escena: 0x00 y Duración de atenuación: 0x00.**Tenga en cuenta que este comando NO PUEDE usarse para detener la sirena y las indicaciones de voz de una alarma real.**
    * Para detener la sirena y las indicaciones de voz de una alarma real, configure ID de escena: 0xFF y Duración de atenuación: 0x00.
* **Control de encendido/apagado de sirena:\[DOMINIO\_CLASE\_BÁSICO]\[BÁSICO\_COLOCAR]**
  *
    * La sirena de SDCO se puede controlar mediante comandos de encendido/apagado de configuración básica (solo para alarma de humo, sin indicación de ubicación).
    * Para encender la sirena usando este comando, configure el Conjunto básico: 0xFF. El patrón de sonido de la sirena es el mismo que el de una alarma de humo.
    * Para apagar la sirena usando este comando, configure el Conjunto básico: 0x00.\*\*Tenga en cuenta que este comando NO PUEDE usarse para detener la sirena de una alarma real.\*\*El SDCO entrará en el modo de silencio de alarma y enviará una señal de restauración de alarma después del período.
  * **Indicador**Control\*\*:\[DOMINIO\_CLASE\_INDICADOR]\[INDICADOR\_COLOCAR]\*\*
    * El indicador LED de SDCO se puede controlar mediante los comandos del conjunto de indicadores.
    * Se pueden utilizar los siguientes comandos para configurar el comando del indicador:

|   | 7 |           |   | 6                                                                   | 5                               | 4                  | 3 |   | 2 |   | 1 | 0 |
| - | - | --------- | - | ------------------------------------------------------------------- | ------------------------------- | ------------------ | - | - | - | - | - | - |
|   |   |           |   |                                                                     |                                 |                    |   |   |   |   |   |   |
|   |   |           |   | Clase de comando = COMANDO\_CLASE\_INDICADOR                        |                                 |                    |   |   |   |   |   |   |
|   |   |           |   |                                                                     |                                 |                    |   |   |   |   |   |   |
|   |   |           |   |                                                                     | Comando = INDICADOR\_COLOCAR    |                    |   |   |   |   |   |   |
|   |   |           |   |                                                                     |                                 |                    |   |   |   |   |   |   |
|   |   |           |   | Valor del indicador 0 (ID del indicador 0=00, ID de propiedad 0=01) |                                 |                    |   |   |   |   |   |   |
|   |   |           |   |                                                                     |                                 |                    |   |   |   |   |   |   |
|   |   | Reservado |   |                                                                     | Recuento de objetos indicadores |                    |   |   |   |   |   |   |
|   |   |           |   |                                                                     |                                 |                    |   |   |   |   |   |   |
|   |   |           |   |                                                                     |                                 | ID del indicador 1 |   |   |   |   |   |   |

ID de propiedad 1

Valor 1

* Indicador activado (0xFF) --- función del indicador activada
* Indicador activado (0x00) --- función del indicador desactivada
* Conteo de objetos indicadores (0x01) --- para controlar el indicador LED ID 1
* ID del indicador (0x43) --- indicación del botón

|   | ID del indicador |   |   | Descripción         |   |                                                 | Apariencia y uso |   |   |
| - | ---------------- | - | - | ------------------- | - | ----------------------------------------------- | ---------------- | - | - |
|   |                  |   |   |                     |   |                                                 |                  |   |   |
|   |                  |   |   |                     |   |                                                 |                  |   |   |
|   | 0x43             |   |   | BOTÓN 1\_INDICACIÓN |   | Úselo para llamar la atención sobre el botón 1. |                  |   |   |

* ID del indicador (0x44) --- reinicio de MCU

|                                                                 |   | ID del indicador |   |   | Descripción        |                     |                                                     | Apariencia y uso |                                                           |                |   |   |   |
| --------------------------------------------------------------- | - | ---------------- | - | - | ------------------ | ------------------- | --------------------------------------------------- | ---------------- | --------------------------------------------------------- | -------------- | - | - | - |
|                                                                 |   |                  |   |   |                    |                     |                                                     |                  |                                                           |                |   |   |   |
|                                                                 |   |                  |   |   |                    |                     |                                                     |                  |                                                           |                |   |   |   |
|                                                                 |   | 0x44             |   |   | BOTÓN2\_INDICACIÓN |                     | Úselo para llamar la atención sobre el botón 2.     |                  |                                                           |                |   |   |   |
|  ID de propiedad (0x00-0xFE) --- LED encendido\_tiempos libres |   |                  |   |   |                    |                     |                                                     |                  |                                                           |                |   |   |   |
|                                                                 |   | Valor            |   |   |                    | Descripción general |                                                     |                  |                                                           | Uso específico |   |   |   |
|                                                                 |   | 0x04             |   |   |                    | En\_Apagado\_Ciclos | Número de encendido\_Apagado\_Periodo para ejecutar |                  |                                                           |                |   |   |   |
|                                                                 |   |                  |   |   |                    |                     |                                                     |                  | 0x00 – 0xFE = 0-254 veces                                 |                |   |   |   |
|                                                                 |   |                  |   |   |                    |                     |                                                     |                  | 0xFF = Ejecutar hasta que se detenga mediante On\_Apagado |                |   |   |   |
|                                                                 |   |                  |   |   |                    |                     |                                                     |                  |                                                           |                |   |   |   |

 Si desea que el SDCO parpadee 5 veces para mostrar su ubicación, envíe: 0xFF 01 43 04 05

 Si desea que el SDCO deje de parpadear una vez que conozca su ubicación, envíe: 0x00 01 43 04 05  Para obtener más detalles, consulte “_**SDS-13781-1 Especificación de clase de comando de aplicación Z-Wave**_”.

**Configuraciones:\[DOMINIO\_CLASE\_CONFIGURACIÓN]\[CONFIGURACIÓN\_COLOCAR]**

 Número de parámetro: 0x01\~0x0A

 Tamaño: 0x01

 Reservado: 0x00

 Predeterminado: 0x00

 Valor de configuración: 0xXX

| Número de parámetro | Valor de configuración |
| ------------------- | ---------------------- |
|                     |                        |
| 0x01, Sensibilidad  | 0x01~~0x08 (0~~70),    |
|                     | predeterminado: 0x04   |

0x02, Período de verificación

0x00~~0x96 (0~~150 segundos),

11

|                                                  | predeterminado 0x00                |
| ------------------------------------------------ | ---------------------------------- |
|                                                  |                                    |
| 0x03, versión de hardware SD                     | 0/1 (0:antiguo, 1:nuevo) siempre 1 |
|                                                  |                                    |
| 0x04, umbral de temperatura                      | 4~~50 (2~~25 grados),              |
|                                                  | predeterminado: 4                  |
|                                                  |                                    |
| 0x05, tiempo de informe automático               | 0\~240 minutos                     |
|                                                  | predeterminado: 30                 |
|                                                  |                                    |
| 0x06, Ubicación                                  | 0\~20                              |
| (por favor refiérase a\_Tabla 3\_)               |                                    |
|                                                  |                                    |
| 0x07, ajustar temperatura                        | +127\~-128                         |
|                                                  | (0,1 grados para cada valor)       |
|                                                  |                                    |
| 0x08, ajustar la humedad                         | +127\~-128                         |
|                                                  | (1% por cada valor)                |
|                                                  |                                    |
| 0x09, fallo de hardware                          | 0x00\~0xFF                         |
| (por favor refiérase a\_Tabla 4\_                |                                    |
| fallo de hardware que se enumera a continuación) |                                    |
|                                                  |                                    |
| 0x0A, repetición temporal                        | 0\~7                               |
| (por favor refiérase a\_Tabla 5\_)               |                                    |
|                                                  |                                    |
| 0x0B, Idioma                                     | 01\~05                             |
|                                                  | 01: inglés                         |
|                                                  | 02: noruego (predeterminado)       |
|                                                  | 03: sueco                          |
|                                                  | 04: finlandés                      |
|                                                  | 05: danés                          |
|                                                  |                                    |

\_**Tabla 4**\_0x09 (fallo de hardware)

| Está viniendo                                                                   | Bit6 | btkh        |       |            | Bit4         | Yo lo compré                                          | Beta            | Bit1           | Bit0     |   |
| ------------------------------------------------------------------------------- | ---- | ----------- | ----- | ---------- | ------------ | ----------------------------------------------------- | --------------- | -------------- | -------- | - |
|                                                                                 |      |             |       |            |              |                                                       |                 |                |          |   |
| X                                                                               | X    | C.A.        |       | Batería SW | Manosear     | CO                                                    | alta definición | Dakota del Sur |          |   |
|                                                                                 |      | 0:Restaurar |       |            | 0: encendido | 1: Abierto                                            | 1: roto         | 1: roto        | 1: roto  |   |
|                                                                                 |      | 1: Fallo    |       |            | 1: Apagado   | 0:Cerrar                                              | 0:Normal        | 0:Normal       | 0:Normal |   |
|                                                                                 |      |             |       |            |              |                                                       |                 |                |          |   |
|  SD rota: si Bit0=1, enviará un comando de notificación “00 00 00 FF 01 FE 00” |      |             |       |            |              |                                                       |                 |                |          |   |
|  HD roto: si Bit1=1, enviará un comando de notificación “00 00 00 FF 04 FE 00” |      |             |       |            |              |                                                       |                 |                |          |   |
|  CO roto: si Bit2=1, enviará un comando de notificación “00 00 00 FF 02 FE 00” |      |             |       |            |              |                                                       |                 |                |          |   |
| \_**Tabla 5**\_0x10 (posposición temporal)                                     |      |             |       |            |              |                                                       |                 |                |          |   |
|                                                                                 |      |             | Valor |            |              | Duración                                              |                 |                |          |   |
|                                                                                 |      |             |       |            |              |                                                       |                 |                |          |   |
|                                                                                 |      |             | 0     |            |              | Desactivar (el cronómetro se detendrá inmediatamente) |                 |                |          |   |
|                                                                                 |      |             |       |            |              |                                                       |                 |                |          |   |
|                                                                                 |      |             | 1     |            |              |                                                       | 5 minutos       |                |          |   |
|                                                                                 |      |             |       |            |              |                                                       |                 |                |          |   |
|                                                                                 |      |             | 2     |            |              |                                                       | 30 minutos      |                |          |   |
|                                                                                 |      |             |       |            |              |                                                       |                 |                |          |   |
|                                                                                 |      |             | 3     |            |              |                                                       | 60 minutos      |                |          |   |
|                                                                                 |      |             |       |            |              |                                                       |                 |                |          |   |
|                                                                                 |      |             | 4     |            |              |                                                       | 8 horas         |                |          |   |
|                                                                                 |      |             |       |            |              |                                                       |                 |                |          |   |
|                                                                                 |      |             | 5     |            |              |                                                       | 12 horas        |                |          |   |
|                                                                                 |      |             |       |            |              |                                                       |                 |                |          |   |
|                                                                                 |      |             | 6     |            |              |                                                       | 24 horas        |                |          |   |
|                                                                                 |      |             |       |            |              |                                                       |                 |                |          |   |
|                                                                                 |      |             | 7     |            |              |                                                       | 36 horas        |                |          |   |
|                                                                                 |      |             |       |            |              |                                                       |                 |                |          |   |

* **Restablecimiento de fábrica**

Si se aprende el dispositivo y se presiona y mantiene presionado el botón de prueba durante 20 segundos junto con 3 pitidos para el restablecimiento de fábrica, enviará

\[DOMINIO\_CLASE\_DISPOSITIVO\_REINICIAR\_EN LA ZONA]\[DISPOSITIVO\_REINICIAR\_EN LA ZONA\_NOTIFICACIÓN]

 El dispositivo se excluirá automáticamente para la nueva versión de PC Controller.

12
