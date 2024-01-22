# CHALECO 060N

**Contacto de puerta/sensor de impacto (DCSV-29-2W)**

DCSV-29-2W es un sensor de contacto/impacto de puerta que es capaz de enviar señales inalámbricas al panel de control al detectar la apertura de una puerta/ventana o la detección de rotura o impacto de vidrio de ventana.

El diseño del sensor de contacto/golpe de puerta consta de una cubierta y una base. La cubierta contiene todos los componentes electrónicos y la base proporciona un medio para fijar el dispositivo. Un interruptor antisabotaje de PCB incluido proporciona protección contra manipulación contra la apertura y/o extracción no autorizada del dispositivo.

![](<.gitbook/assets/0 (43).jpeg>)

**Identificación de piezas**

1.  **Indicador LED/Botón de prueba**
    -   Presione el botón una vez para enviar un código de aprendizaje o ingresar al modo de prueba durante 3 minutos.
2.  **Tornillo de fijación de la cubierta**
3.  **Orificios de montaje**
4.  **Manibela de encendido**
    -   Proporciona protección contra manipulación contra la apertura y/o extracción no autorizada del dispositivo de la superficie de montaje.
5.  **Aislador de batería**
6.  **Compartimiento de la batería**
7.  **Imán**
8.  **Imán Orificio para tornillo**
9.  **Espaciador magnético**

**Características**

![](<.gitbook/assets/1 (37).jpeg>)

-   _**Indicador LED**_
    -   En el modo de funcionamiento normal, el LED no se iluminará cuando se active el dispositivo.
    -   Cuando el voltaje de la batería del dispositivo es bajo, el LED parpadeará rápidamente cuando se active el dispositivo.
    -   Cuando se activa el interruptor de manipulación, el LED parpadeará rápidamente. Cuando persiste una condición de manipulación, el LED parpadeará rápidamente cada vez que se active el dispositivo. (Solo para activación de contacto de puerta).
    -   Cuando esté en modo de prueba, el LED parpadeará rápidamente cada vez que se active el dispositivo.
    -   Cuando la batería esté agotada, el LED parpadeará cada 4 segundos.
    -   El LED no parpadeará si la manipulación del dispositivo y la batería son normales y no están en modo de prueba.
    -   Si el LED parpadea para indicar transmisión de señal, parpadeará dos veces rápidamente al recibir el reconocimiento del panel.
    -   Cuando el comando de programación del Panel de control se reciba exitosamente, el LED se volverá más brillante y luego se apagará.
-   _**Detección de apertura de puertas y detección de golpes**_

![](<.gitbook/assets/2 (48).png>)

El dispositivo se activa al abrir una puerta/ventana o al detectar un impacto que supera el umbral de detección.

![](<.gitbook/assets/3 (29).jpeg>)

-   _**Materiales de superficie de montaje**_

El dispositivo admite la detección de impactos en diversos materiales, incluidos vidrio, madera, metal y hormigón. Después de la instalación, puede seleccionar el material de la superficie montada en el Panel de control. El valor predeterminado se establece como

![](<.gitbook/assets/4 (43).png>)

**Madera**

-   _**Sensibilidad**_
    -   La sensibilidad requerida para activar el sensor de contacto/choque de la puerta se determina desde el panel de control.
    -   Se pueden seleccionar tres niveles de sensibilidad:**Bajo**,**Medio**, y**Alto**. El valor predeterminado se establece como**Medio**.

1

-   ![](<.gitbook/assets/5 (21).jpeg>)_**Batería**_
    -   El sensor de contacto/golpe de puerta utiliza una batería de litio CR123 de 3 V como fuente de energía. La batería se instala en el compartimiento de la batería con un aislante de batería insertado. Para activar la batería, simplemente extraiga el aislante de la batería.
    -   El sensor de contacto de puerta/choque puede detectar una condición de batería baja. Cuando el voltaje de la batería es bajo, se enviará una señal de batería baja al panel de control para notificar la condición. El LED se iluminará cuando el sensor de contacto/choque de la puerta se active en un estado de batería baja. Cuando la batería se agota, el sensor de contacto/choque de la puerta detendrá todas sus funciones y el LED parpadeará cada 4 segundos.
    -   Al cambiar las baterías, después de quitar las baterías viejas, presione el interruptor de manipulación dos veces para descargarlas por completo antes de insertar baterías nuevas.
-   _**Protección contra manipulación**_
    -   El contacto de la puerta/sensor de impacto está protegido por un interruptor antisabotaje que se comprime contra la superficie de montaje cuando se monta el contacto de la puerta/sensor de impacto. Cada vez que se retira el sensor de contacto/choque de la puerta de la superficie montada o se abre la cubierta, se activará el interruptor de manipulación y el dispositivo enviará una señal de apertura de manipulación para recordarle al usuario la condición.
    -   La señal de apertura por manipulación se transmitirá con el contacto de puerta al panel de control. El estado de falla de manipulación se mostrará solo en la zona del dispositivo de CC en el Panel de control.
-   _**Supervisión**_
    -   Cuando está en funcionamiento normal, el contacto de la puerta y el sensor de impacto enviarán una señal de supervisión al panel de control por separado en intervalos aleatorios de 90 a 110 minutos.
    -   Si el panel de control no ha recibido la señal de supervisión del contacto de puerta/sensor de impacto durante un período de tiempo preestablecido, el panel de control indicará que el contacto de puerta/sensor de impacto en particular está experimentando un problema de falta de señal.
-   _**Modo de prueba**_
    -   En el modo normal, presione el botón de prueba para transmitir una señal de prueba y un código de aprendizaje al panel de control. El sensor de contacto/choque de la puerta también entrará en el modo de prueba durante 3 minutos.
    -   En el modo de prueba, el LED se iluminará cada vez que se active el contacto de puerta/sensor de impacto.
    -   Cada pulsación adicional del botón de prueba restablecerá el tiempo del modo de prueba a 3 minutos.
-   _**Empezando**_
    -   Retire el aislante de la batería en el contacto de la puerta/sensor de impacto para encenderlo.
    -   Coloque el panel de control en modo de aprendizaje (consulte el manual de operación del panel)
    -   Presione el botón de prueba en el contacto de la puerta/sensor de impacto.
    -   Consulte el manual de funcionamiento de su panel de control para completar el proceso de aprendizaje.
    -   Cuando se aprende en el Panel de control, el DCSV-29-2W será reconocido como 2 dispositivos separados (contacto de puerta y sensor de impacto) y ocupará 2 zonas en el panel.
    -   Establezca el material y el nivel de sensibilidad:
        1.  Después de que DCSV-29-2W se haya aprendido en el Panel de control, presione el botón de prueba en DCSV-29-2W una vez.
        2.  Vaya a la página web del Panel de control para editar el dispositivo.
        3.  Seleccione el material y el nivel de sensibilidad en la página Configuración del dispositivo. Haga clic en Aceptar para confirmar.

![](<.gitbook/assets/6 (28).jpeg>)![](<.gitbook/assets/7 (25).jpeg>)![](<.gitbook/assets/8 (18).jpeg>)![](<.gitbook/assets/9 (26).png>)![](<.gitbook/assets/10 (13).jpeg>)![](<.gitbook/assets/11 (18).png>)![](<.gitbook/assets/12 (22).png>)

2

-   -   1.  Presione el botón de prueba de DCSV-29-2W para recibir datos del nivel de sensibilidad y material desde el panel de control. El LED primero se apagará, luego se volverá más brillante y se oscurecerá, lo que indica que el comando de programación del panel de control se recibió correctamente.
-   _**Prueba de caminata**_
    -   Después de que se haya aprendido el contacto de la puerta/sensor de impacto, coloque el panel de control en (**Prueba de caminata**), mantenga presionado el sensor de contacto/choque de la puerta en la ubicación deseada y presione el botón de prueba para transmitir la señal de prueba al panel de control. Si el panel de control está dentro del rango de señal del contacto de la puerta/sensor de impacto, el panel mostrará la información del contacto de la puerta/sensor de impacto en consecuencia.
    -   Continúe con el montaje y la instalación una vez que esté satisfecho de que el sensor de contacto/impacto de la puerta funciona correctamente en la ubicación deseada.

![](<.gitbook/assets/13 (14).jpeg>)

**Instalación**

![](<.gitbook/assets/14 (16).jpeg>)

-   _**Montaje del contacto de puerta/sensor de impacto**_

**Montaje como contacto de puerta:**

-   El sensor de contacto/impacto de la puerta debe instalarse con el lado marcado con nervaduras mirando hacia el imán.
-   La distancia entre el contacto de la puerta/sensor de impacto y el imán no debe ser superior a 15 mm cuando la puerta está cerrada.
-   Monte el dispositivo lo más alto posible.

![](<.gitbook/assets/15 (12).jpeg>)

**Montaje como sensor de impacto:**

Consulte la siguiente tabla para obtener información sobre la ubicación de instalación y el espesor de los diferentes materiales:

|                                 |                     |                       | Ventana de vidrio | Puerta de madera/metal | Pared de concreto |   |
| ------------------------------- | ------------------- | --------------------- | ----------------- | ---------------------- | ----------------- | - |
|                                 | **Espesor**         | >5mm                  | &lt;40 mm         | -                      |                   |   |
|                                 |                     |                       |                   |                        |                   |   |
| **Ubicación de la instalación** | Marco de la ventana | Puerta                | Muro              |                        |                   |   |
|                                 |                     |                       |                   |                        |                   |   |
|                                 |                     | **Baja sensibilidad** | 0,5 millones      | 0,5 millones           | 0,25 millones     |   |
| **Detección de golpes**         |                     |                       |                   |                        |                   |   |
| **Sensibilidad media**          | 1M                  | 1M                    | 0,5 millones      |                        |                   |   |
| **Radio**                       |                     |                       |                   |                        |                   |   |
|                                 |                     |                       |                   |                        |                   |   |
|                                 |                     |                       |                   |                        |                   |   |
|                                 |                     | **Alta sensibilidad** | 1,5 millones      | madre                  | 1M                |   |
|                                 |                     |                       |                   |                        |                   |   |

![](<.gitbook/assets/16 (10).jpeg>)

3

-   ![](<.gitbook/assets/17 (10).jpeg>)_**Procedimiento de montaje**_
    1.  Utilice los 2 orificios de montaje de la cubierta posterior como plantilla para el posicionamiento.
    2.  Utilice los tacos de pared suministrados para la instalación de marcos de ventanas/paredes de hormigón.
    3.  Atornille el contacto de la puerta/sensor de impacto en los tacos de pared. (Se recomienda taladrar cuando se monta en acero, o también puede utilizar la pegatina proporcionada en el paquete).
    4.  Coloque el imán en la puerta usando un pequeño trozo de cinta adhesiva de doble cara o con los tornillos provistos.
    5.  Para montar el imán, utilice los 2 orificios de los tornillos del imán como plantilla para la colocación adecuada de los orificios.
        -   _NOTA >_
            -   El imán debe alinearse con el lado de la marca de la nervadura del contacto de la puerta. Si es necesario, aplique el espaciador del imán en la parte posterior del imán para alinear mejor el imán con las marcas de las nervaduras.
    6.  Atornille el imán e inserte las dos tapas blancas en los orificios de los tornillos del imán para lograr una integridad estética.
    7.  La instalación ya está completa.

![](<.gitbook/assets/18 (14).png>)![](<.gitbook/assets/19 (4).jpeg>)

4
