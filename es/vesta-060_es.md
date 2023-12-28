# VESTA 060

Sensor de contacto de puerta/vibración de impacto (DCSV-23)

DCSV-23 es un sensor de contacto de puerta/choque capaz de enviar una señal de puerta abierta al panel de control al detectar la apertura de puerta/ventana o la detección de choque/vibración.

![DCSV-23ZBS](<.gitbook/assets/0 (13).jpeg>)El diseño del sensor de contacto de puerta/vibración de impacto consta de una cubierta y una base. La cubierta contiene todos los componentes electrónicos y la base proporciona un medio para fijar el dispositivo. Un interruptor antisabotaje de PCB incluido proporciona protección contra manipulación contra la apertura y/o extracción no autorizada del dispositivo.

Identificación de piezas

1.  **Indicador LED/Botón de prueba**

-   Presione el botón una vez para enviar un código de aprendizaje o ingresar al modo de prueba durante 3 minutos.

1.  **Tornillo de fijación de la cubierta**
2.  **Orificios de montaje**
3.  **Manibela de encendido**

-   Proporciona protección contra manipulación contra la apertura y/o extracción no autorizada del dispositivo de la superficie de montaje.

1.  **Aislador de batería**
2.  **Puente de modo de detección (JP3)**

-   Consulte la sección_**Modo de detección de golpes/vibraciones**_para detalles.

1.  **Puente de ajuste de sensibilidad (JP4,JP5)**

-   Consulte la sección_**Ajuste de sensibilidad**_para detalles.

1.  **Puente del interruptor de láminas (JP1)**

-   Consulte la sección_**Interruptor de láminas**_para detalles.

1.  **Compartimiento de la batería**
2.  **Imán**
3.  **Imán Orificio para tornillo**
4.  **Espaciador magnético**

Características

Saltador**EN**(El enlace del puente está insertado): El interruptor de láminas está_**desactivado.**_

![jumper open](<.gitbook/assets/3 (21).png>)

Saltador**APAGADO**(El enlace del puente se retira o se estaciona en un pin): El interruptor de láminas está_**activado**_y el dispositivo ahora funciona como contacto de puerta. (_**Por defecto**_)

-   El interruptor de láminas debe desactivarse si el dispositivo no se utiliza como contacto de puerta.
-   _**Modo de detección de golpes/vibraciones**_
-   La función de detección de golpes/vibraciones del dispositivo puede activarse según el modo seleccionado.
-   **Modo de pulso único**

El dispositivo se activa mediante la detección de un único impulso que supera el umbral de detección.

-   **Modo de recuento de pulsos/vibración acumulada**

El dispositivo se activa por cualquiera de las siguientes condiciones:

1.  Cuando**3**los conteos de pulso se detectan dentro**20****segundos**.
2.  Cuando se detecta una vibración menor acumulada con**2 minutos**excede el umbral de detección.

-   Los modos de detección se seleccionan mediante el interruptor de puente JP3:

![jumper close](<.gitbook/assets/4 (20).png>)Saltador**EN**(El enlace del puente está insertado):**Modo de pulso único**. (_**Por defecto**_)

![jumper open](<.gitbook/assets/5 (13).png>)Saltador**APAGADO**(El enlace del puente se retira o se estaciona en un pin):**Modo de recuento de pulsos/vibración acumulada**

-   _**Ajuste de sensibilidad**_
-   Utilice el interruptor de puente JP4 y JP5 para determinar la sensibilidad requerida para activar el sensor de contacto de puerta/vibración de impacto. Consulte la tabla a continuación para seleccionar la sensibilidad deseada.

| JP4     | JP5     | Sensibilidad al choque    |
| ------- | ------- | ------------------------- |
| EN      | APAGADO | Bajo                      |
| APAGADO | EN      | Medio (_**por defecto**_) |
| EN      | EN      | Alto                      |

-   _**Batería**_
-   El sensor de contacto de puerta/vibración de impacto utiliza una batería de litio CR123 de 3 V como fuente de energía. La batería se instala en el compartimiento de la batería con un aislante de batería insertado. Para activar la batería, simplemente extraiga el aislante de la batería.
-   El sensor de contacto de puerta/vibración de impacto puede detectar una condición de batería baja. Cuando el voltaje de la batería es bajo, se enviará una señal de batería baja al panel de control para notificar la condición. El LED se iluminará cuando el sensor de contacto de puerta/vibración de impacto se active en un estado de batería baja. Cuando la batería se agota, el sensor de contacto de puerta/vibración de impacto detendrá todas sus funciones y el LED parpadeará cada 4 segundos.
-   Al cambiar las baterías, después de quitar las baterías viejas, presione el interruptor de manipulación dos veces para descargarlas por completo antes de insertar baterías nuevas.
-   _**Protección contra manipulación**_
-   El sensor de contacto de puerta/vibración de impacto está protegido por un interruptor antisabotaje que se comprime contra la superficie de montaje cuando se monta el sensor de contacto de puerta/vibración de impacto. Cada vez que se retira el sensor de contacto de puerta/vibración de impacto de la superficie montada o se abre la cubierta, se activará el interruptor de manipulación y el dispositivo enviará una señal de apertura de manipulación para recordarle al usuario la condición.
-   _**Supervisión**_
-   El sensor de contacto de puerta/vibración de impacto transmitirá automáticamente una señal de supervisión periódicamente al panel de control en intervalos aleatorios de 30 a 50 minutos.
-   Si el panel de control no ha recibido la señal del sensor de contacto de puerta/vibración de impacto durante un período de tiempo preestablecido, el panel de control indicará que el sensor de contacto de puerta/vibración de impacto en particular está experimentando un problema de falta de señal.
-   _**Modo de prueba**_
-   En el modo normal, presione el botón de prueba para transmitir una señal de prueba y un código de aprendizaje al panel de control. El sensor de contacto de puerta/vibración de impacto también entrará en el modo de prueba durante 3 minutos.
-   En el modo de prueba, el LED se iluminará cada vez que se active el sensor de contacto de puerta/vibración de impacto.
-   Cada pulsación adicional del botón de prueba restablecerá el tiempo del modo de prueba a 3 minutos.
-   _**Empezando**_
-   Retire el aislante de la batería en el sensor de contacto de puerta/vibración de impacto para encenderlo.
-   Coloque el panel de control en modo de aprendizaje (consulte el manual de operación del panel)
-   Presione el botón de prueba en el sensor de contacto de puerta/vibración de impacto
-   Consulte el manual de funcionamiento de su panel de control para completar el proceso de aprendizaje.
-   Después de que se haya aprendido el sensor de contacto de puerta/vibración de impacto, coloque el panel de control en (**Prueba de caminata**), mantenga presionado el sensor de contacto de puerta/vibración de impacto en la ubicación deseada y presione el botón de prueba para transmitir la señal de prueba al panel de control. Si el panel de control está dentro del rango de señal del sensor de contacto de puerta/vibración de impacto, el panel mostrará la información del sensor de vibración de impacto/contacto de puerta en consecuencia.
-   Continúe con el montaje y la instalación una vez que esté satisfecho de que la ubicación del sensor de contacto de puerta/vibración de impacto funciona correctamente.

Instalación

-   _Montaje del contacto de puerta/sensor de vibración de impacto_

![](<.gitbook/assets/6 (9).png>)**Montaje como contacto de puerta:**

-   El sensor de contacto de puerta/vibración de impacto debe instalarse en posición vertical o invertida para garantizar que el lado marcado con nervaduras mire hacia el imán.
-   La distancia entre el sensor de contacto de la puerta/vibración de impacto y el imán no debe ser superior a 15 mm cuando la puerta está cerrada.
-   Evite montar el sensor de contacto de puerta/vibración de impacto sobre una superficie metálica. Si se monta sobre una superficie metálica, asegúrese de probar si el sensor de contacto de puerta/vibración de impacto se puede activar cuando se abre la puerta.
-   Monte el dispositivo lo más alto posible.

**Montaje como sensor de vibración de impacto:**

-   montar en_**Hormigón, caja de seguridad, marcos de ventanas.**_
-   Cuando se monta en el marco de una puerta o ventana, el dispositivo también sirve como contacto de puerta.
-   Consulte la tabla a continuación para obtener información sobre el rango de detección de golpes/vibraciones y la configuración de sensibilidad según los diferentes materiales de superficie. Utilice el puente de ajuste de sensibilidad para seleccionar la sensibilidad deseada.

|                                                          | Ventana de vidrio                       | Puerta                                   | Pared de concreto | Caja de seguridad                         |   |
| -------------------------------------------------------- | --------------------------------------- | ---------------------------------------- | ----------------- | ----------------------------------------- | - |
| Espesor                                                  | >5mm                                    | &lt;40 mm                                | -                 | 3mm                                       |   |
| Material                                                 | <p>Regular/Templado/</p><p>Laminado</p> | Madera/Acero                             | Concreto          | Acero + Dióxido de Silicio                |   |
| Ubicación de instalación                                 | Marco de la ventana                     | Marco de la puerta                       | Muro              | 2 cm de distancia del pivote de la puerta |   |
| Modo de detección                                        | Modo de pulso único                     |  Conteo de pulsos / Vibración acumulada |                   |                                           |   |
| <p>Sensibilidad al impacto</p><p>(área de cobertura)</p> | Bajo                                    | 2000 mm                                  | 1000 mm           | 500 mm                                    | - |
| Medio                                                    | 3000 mm                                 | 2000 mm                                  | 1500 mm           | -                                         |   |
| Alto                                                     | 4000mm                                  | 3000 mm                                  | 2000 mm           | 1400 mm                                   |   |

![](<.gitbook/assets/7 (6).png>)

-   _Procedimiento de montaje_

1.  Utilice los 2 orificios de montaje de la cubierta posterior como plantilla para el posicionamiento.
2.  Utilice los tacos de pared proporcionados para la instalación de marcos de ventanas, paredes de concreto o cajas de seguridad.
3.  Atornille el sensor de contacto de puerta/vibración de impacto en los tacos de pared. (Se recomienda perforar cuando se monta en acero, como una caja de seguridad, o también puede utilizar la pegatina proporcionada en el paquete).
4.  Coloque el imán en la puerta usando un pequeño trozo de cinta adhesiva de doble cara o con los tornillos provistos.
5.  Para montar el imán, utilice los 2 orificios de los tornillos del imán como plantilla para la colocación adecuada de los orificios.

&lt;Nota>

-   El imán debe alinearse con el lado de la marca de la nervadura del contacto de la puerta. Si es necesario, aplique el espaciador del imán en la parte posterior del imán para alinear mejor el imán con las marcas de las nervaduras.

1.  Atornille el imán e inserte las dos tapas blancas en los orificios de los tornillos del imán para lograr una integridad estética.
2.  La instalación ya está completa.

\\<NOTE>

-   No monte el dispositivo sobre materiales superficiales donde se produzcan vibraciones frecuentes, para evitar falsas alarmas.
-   ![](<.gitbook/assets/8 (6).png>)Cuando lo monte en una caja de seguridad, monte el sensor de contacto/choque de la puerta a no más de 2 cm de distancia del pivote de la puerta (consulte la imagen a continuación).
