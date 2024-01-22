# VESTA 222

**PSS-29-F1/ PSM-29-F1**

![](<.gitbook/assets/0 (92).jpeg>)

**Serie de interruptores de alimentación**

**Introducción**

La serie Power Switch está diseñada para que el usuario encienda/apague de forma remota un dispositivo conectado a ella.

La serie Power Switch incluye los siguientes modelos:

**PSS-29-F1:**Interruptor de alimentación

**PSM-29-F1:**Interruptor de encendido con medidor

El modelo PSM-29-F1 lleva incorporado un medidor de potencia para medir el consumo eléctrico. Los datos de energía recopilados se informarán al panel de control.

La integración del interruptor de encendido en su sistema domótico le permitirá controlar cómodamente los electrodomésticos para su comodidad o para ahorrar energía.

**Identificación de piezas**

![](<.gitbook/assets/1 (78).jpeg>)

**1. Botón de prueba, también conocido como indicador LED**

El botón de prueba también funciona como indicador LED. El botón de prueba se utiliza para controlar el interruptor de encendido. El indicador LED se utiliza para indicar el estado del interruptor de encendido.

**Indicación LED:**

El indicador LED se enciende en las siguientes condiciones:

-   Encendido: el interruptor de encendido está encendido.
-   Apagado: el interruptor de encendido está apagado.
-   Parpadea dos veces: cuando está encendido.
-   Parpadea lentamente: En modo de aprendizaje.
-   Parpadea tres veces: cuando el aprendizaje es exitoso.
-   Parpadea brevemente: transmisión de señal RF

**Uso del botón de prueba:**

-   Presione el botón para activar/desactivar el interruptor de encendido
-   Mantenga presionado el botón durante 3 segundos para enviar un código de aprendizaje.
-   Mantenga presionado el botón mientras enciende el interruptor de encendido, luego suelte el botón cuando el LED se encienda para restablecer los valores de fábrica.

**Empezando**

Paso 1: conecte el interruptor de encendido a la toma de corriente.

Paso 2: ponga el Panel de control en modo de aprendizaje.

Paso 3: Mantenga presionado el botón Prueba en el interruptor de encendido durante 3 segundos para enviar un código de aprendizaje.

Paso 4: El LED comenzará a parpadear lentamente, indicando que el interruptor de encendido está en modo de aprendizaje.

Paso 5: Si el Panel de Control recibe la señal de la fuente de alimentación

interruptor, mostrará la información correspondiente. Consulte el manual del Panel de control para completar el proceso de aprendizaje.

Paso 6: Cuando el interruptor de encendido reciba el código de aprendizaje del panel de control, el LED del interruptor de encendido parpadeará 3 veces y luego se apagará para indicar que el proceso de aprendizaje se ha completado.

![](<.gitbook/assets/2 (72).png>)

_\\<NOTE>_

-   Después de ingresar al modo de aprendizaje, el interruptor de encendido no saldrá automáticamente del modo de aprendizaje a menos que reciba confirmación del panel de control o que se presione el botón de prueba.
-   Si el interruptor de encendido ya existe en un sistema de panel de control, primero deberá quitarlo del panel de control antes de poder configurarlo en un panel de control diferente.

1

**Prueba de caminata**

Para probar si el interruptor de encendido puede comunicarse con el panel de control:

-   Coloque el panel de control en modo de prueba de recorrido.
-   Presione el botón de prueba en el interruptor de encendido.
-   El panel de control debería mostrar si el interruptor de encendido está dentro del rango de operación (consulte el manual de operación del panel de control).

**Supervisión**

-   Después de que el interruptor de encendido se haya programado correctamente en el panel de control, el dispositivo transmitirá automáticamente una señal de supervisión junto con el estado de encendido/apagado al panel de control en intervalos aleatorios de 30 a 50 minutos.
-   Si el panel de control no ha recibido la señal del interruptor de encendido durante el período de tiempo preestablecido, el panel de control indicará en su pantalla que el interruptor de encendido en particular está experimentando un problema de falta de señal.

**Operación**

![](<.gitbook/assets/3 (67).jpeg>)

-   _**Instalación**_
    -   Conecte el interruptor de encendido a una toma de corriente, luego conecte el aparato al enchufe del interruptor de encendido. El aparato debe estar en estado ON.
-   _**Control de electrodomésticos**_
    -   Una vez que el interruptor de encendido se haya aprendido correctamente en el panel de control, el panel de control puede encender/apagar de forma remota el interruptor de encendido para controlar el electrodoméstico. Consulte el manual de su Panel de control para obtener más detalles.
    -   También puede presionar el botón en el interruptor de encendido para alternar su estado de encendido/apagado.
    -   Si se retira el interruptor de alimentación del tomacorriente, después de volver a enchufarlo, su estado de encendido/apagado anterior y los datos de salida de energía actual (solo PSM-29-F1) se transmitirán al panel de control.
-   _**Monitor de consumo de energía (solo para PSM-29-F1)**_

![](<.gitbook/assets/4 (58).jpeg>)![](<.gitbook/assets/5 (39).jpeg>)

Con un medidor de energía incorporado para medir el consumo de electricidad, el interruptor medidor de energía PSM-29-F1 transmitirá datos de consumo de energía al panel de control cuando:

-   -   Cuando el interruptor del medidor de potencia está encendido/apagado.
    -   Siempre que la salida de energía del interruptor de encendido cambie en +/- 2W.
    -   Siempre que el consumo de energía acumulado aumente en 0,2 kW/h.
-   _**Carga máxima de operación**_
    -   Para 110V: la carga máxima de operación es 1760W y 16A.
    -   Para 230V: la carga máxima de funcionamiento es de 3680W y 16A.
    -   Si el interruptor de encendido se sobrecalienta, cortará la energía automáticamente como medida de seguridad. El indicador LED parpadeará rápidamente. Después del corte, el interruptor de encendido reanudará su funcionamiento normal si la temperatura cae por debajo del punto umbral.

![](<.gitbook/assets/6 (49).jpeg>)![](<.gitbook/assets/7 (52).png>)

_\\<NOTE>_

-   La carga operativa máxima de_**Tipo B**_es 110 V, 1650 W y 15 A, que es diferente de la carga operativa máxima para 110 V y 230 V indicada anteriormente.

**Restablecimiento de fábrica**

-   El restablecimiento de fábrica del interruptor de encendido borrará su memoria y lo restaurará a la configuración predeterminada de fábrica.
-   Mantenga presionado el botón de prueba mientras enciende el interruptor de encendido, luego suelte el botón cuando el LED se encienda para restablecer los valores de fábrica.

2
