# VESTA 015

**Sensor de movimiento PIR domo (IRD-23 / IRD-23SL)**

El sensor de movimiento Dome PIR está diseñado para montarse en el techo para proporcionar una cobertura de detección de 360 ​​∘ sin puntos ciegos para detectar movimientos dentro de un área asignada y le indica al panel de control que active la alarma si un intruso cruza su camino de detección.

El PIR consta de un diseño de dos partes formado por un cuerpo principal del PIR y una cubierta trasera para montaje en pared. El cuerpo principal contiene toda la electrónica y la óptica y la base proporciona un medio de instalación.

El cuerpo principal del PIR tiene un interruptor antisabotaje que se activará cuando se retire el cuerpo principal de la cubierta posterior para evitar el acceso no autorizado y su extracción de la superficie de montaje. El PIR también puede alertarle sobre problemas de comunicación y situaciones de batería baja.

El Dome PIR incluye 2 modelos:

IRD-23: Funciona con 2 pilas alcalinas AA de 1,5 V

IRD-23SL: Alimentado por 1 batería de litio CR123A de 3V

-   _**Identificando las piezas.**_

**1. Botón de prueba, también conocido como indicador LED**

El botón de prueba y también funciona como indicador LED. El botón de prueba se utiliza para probar el rendimiento de la radio y con fines de aprendizaje. El indicador LED se utiliza para indicar el estado del sistema.

1.  **Sensor de infrarrojos**
2.  **Interruptor de puente aumentador de sensibilidad (JP3)**

![](<.gitbook/assets/0 (25).jpeg>)

Es un interruptor de puente de 2 pines.

-   Si el puente está APAGADO (si se quita el enlace del puente o "**estacionado”**en un pin),

La sensibilidad de detección del PIR está en un nivel normal. (**Predeterminado de fábrica**)

![](<.gitbook/assets/1 (18).jpeg>)

-   -   Si el puente está activado, la sensibilidad de detección del PIR es alta.

1.  **Manibela de encendido**

El interruptor antisabotaje protege el PIR para que no se retire de la ubicación montada.

**5. Compartimento de la batería**

IRD-23: 2 pilas alcalinas AA de 1,5V.

IRD-23SL: 1 pila CR123A de litio de 3V

-   1.  **Orificios de montaje**
    2.  **Manos**
    3.  **Perforaciones para montaje en techo (interior)**
-   _**Indicador LED**_

En el modo de funcionamiento normal, el indicador LED no se encenderá excepto en las siguientes situaciones:

-   -   Cuando el PIR está en condición de batería baja, cada vez que transmite un movimiento detectado, el LED se iluminará durante aproximadamente 2 segundos.
    -   Cuando se abre la cubierta y se viola el interruptor de manipulación, el LED se iluminará durante

2 segundos. para indicar que está transmitiendo el “**Manosear**”señal.

-   -   Cuando la condición de Tamper persiste, cada vez que transmita un movimiento detectado, el LED se encenderá.
    -   Cuando el PIR está en modo de prueba, el LED se iluminará cada vez que se detecte un movimiento.
-   _**Tiempo de dormir**_

_**Cuerpo principal del PIR**_

![](<.gitbook/assets/2 (17).jpeg>)

_**Contraportada**_

![](<.gitbook/assets/3 (16).jpeg>)

El PIR tiene un “**hora de dormir**”de aproximadamente 1 minuto para ahorrar energía. Después de transmitir un movimiento detectado, el PIR no retransmitirá durante 1 minuto; cualquier movimiento adicional detectado durante este período de sueño extenderá el tiempo de sueño en otro minuto. De esta manera, el movimiento continuo frente a un PIR no agotará indebidamente la batería.

-   _**Función de supervisión**_

El PIR transmite una señal de supervisión una vez cada 30 a 50 minutos. Si el Panel de Control no recibe las señales de Supervisión transmitidas desde un determinado PIR durante un tiempo preestablecido, aparecerá un “**Fuera de servicio**r” se generará un mensaje de error.

-   _**Función de aumento de sensibilidad**_

Puede utilizar la función de aumento de sensibilidad para aumentar la sensibilidad de detección del IR. Para aumentar la sensibilidad de detección, configure el puente JP3 en**EN**posición. Para mantener la sensibilidad de detección normal, configure el puente JP3 en**APAGADO**posición (valor predeterminado de fábrica).

-   _**Modo de prueba**_

1

El PIR se puede poner en modo de prueba presionando el botón de prueba, también conocido como LED, en la cubierta frontal. En el modo de prueba, desactivará el temporizador de apagado y permitirá que el indicador LED parpadee cada vez que se detecte un movimiento. Cada vez que presione el botón de prueba, el PIR transmitirá una señal de prueba al panel de control para probar el alcance de la radio y entrará en el modo de prueba durante 3 minutos. Saldrá del modo de prueba automáticamente después de 3 minutos y volverá al modo normal.

-   _**Batería**_

El PIR utiliza diferentes baterías según el modelo de PIR:

IRD-23: 2 pilas alcalinas AA de 1,5 V

IRD-23SL: 1 pila CR123A de litio de 3V

Las baterías están incluidas en el paquete. El PIR cuenta con función de detección de batería baja. Se enviará una señal de batería baja al Panel de control junto con transmisiones regulares de señales para que el Panel de control muestre el estado correspondiente.

_\\<NOTE>_

-   -   Al cambiar las baterías, después de quitar las baterías viejas, presione el interruptor de manipulación dos veces para descargarlas por completo antes de insertar baterías nuevas.
-   _**Manibela de encendido**_

El PIR tiene un interruptor de manipulación ubicado en la parte posterior del cuerpo principal del PIR. Cuando el PIR esté instalado correctamente en la cubierta posterior, el interruptor de manipulación se comprimirá. Cuando se retira el PIR de la cubierta posterior, el interruptor de manipulación se activará y activará el PIR para enviar una señal de apertura de manipulación al panel de control.

-   _**Empezando**_
    -   Inserte la batería en el compartimiento de la batería.
    -   El indicador LED parpadea constantemente durante 30 segundos. (El PIR se está calentando). Durante el período de calentamiento, el PIR no se activará. Se recomienda que se mantenga alejado del área de detección durante este tiempo. Una vez finalizado el período de calentamiento, la luz se apagará y el PIR estará listo para funcionar.
    -   Coloque el Panel de control en modo de aprendizaje; consulte el manual del Panel de control para obtener más detalles.
    -   Presione el botón de aprendizaje/prueba en la cubierta frontal.
    -   Si el panel de control recibe una señal PIR, mostrará la información correspondiente; consulte el manual del panel de control para completar el proceso de aprendizaje.
    -   Después de aprender el PIR, coloque el Panel de control en "**Prueba de caminata**”, mantenga presionado el PIR en la ubicación deseada y presione el botón Prueba para confirmar que esta ubicación está dentro del alcance de la señal del panel de control.
    -   Cuando esté satisfecho de que el PIR funciona en la ubicación elegida, puede continuar con la instalación.
-   _**Guía de instalación**_
    -   El PIR está diseñado para montarse en el techo.
    -   Cuando se monta a una altura de 2,7 metros, el PIR proporciona una cobertura de detección de un círculo de 360° con aproximadamente**6**metros de diámetro.
    -   Cuando se monta a una altura de 4 metros, el PIR proporciona una cobertura de detección de un círculo de 360° con aproximadamente**8**metros de diámetro.
    -   Para un rendimiento óptimo, gire el PIR para que el intruso se mueva a través de su área de detección de lado a lado.

_\\<NOTE>_

-   -   Para conocer los “lados” del PIR. Sostenga el PIR con el indicador LED apuntando hacia arriba, y los lados izquierdo y derecho del PIR se consideran los lados del PIR. El sensor PIR es más sensible cuando el intruso se mueve de un lado a otro
-   Consulte los diagramas a continuación para obtener más información.

![](<.gitbook/assets/4 (32).png>)

-   **Se recomienda instalar el PIR en las siguientes ubicaciones.**
    -   En una zona del techo con vista completa de su cobertura de detección sin obstáculos por electrodomésticos y muebles.
    -   Cerca de la entrada de una habitación o casa para monitorear la actividad de entrada.
-   **Limitaciones**
    -   Si una puerta ya está protegida por un contacto de puerta, no instale el PIR demasiado cerca de la puerta. Si el contacto de puerta y el PIR se activan y transmiten señales al mismo tiempo, las señales pueden colisionar y cancelarse entre sí.
    -   No instale el PIR expuesto a la luz solar directa.
    -   Evite instalar el PIR en áreas donde los dispositivos puedan causar cambios rápidos de temperatura en el área de detección, es decir, aire

2

acondicionadores, calentadores, etc.

-   -   -   -   Evite grandes obstáculos en el área de detección.
            -   No apunte directamente a fuentes de calor, p. Fuegos o calderas, y no encima de radiadores.
            -   Evite mover objetos en el área de detección, como cortinas, tapices de pared, etc.
    -   Después de seleccionar el sitio de instalación, siga los pasos a continuación para montar el PIR.
    -   Presione el botón de prueba para ingresar al modo de prueba. Camine por el área protegida observando cuando se enciende el LED y verifique que la cobertura de detección sea la adecuada.
    -   Cuando se considera que la cobertura de detección es satisfactoria, la instalación ya está completa.
-   _**Método de montaje**_
    -   El PIR está diseñado para montarse en el techo.
    -   La cubierta trasera tiene 4 orificios ciegos donde el plástico es más delgado para montaje en techo.
    -   Después de finalizar el aprendizaje del PIR y la prueba de caminata, proceda a montar el PIR de acuerdo con las instrucciones a continuación I. Rompa los 4 orificios ciegos en el interior de la cubierta posterior.

1.  Utilice las azadas perforadoras como plantilla, taladre agujeros en el techo e inserte el taco de pared si es necesario.

III. Atornille la cubierta trasera al techo según los agujeros perforados.

IV. La cubierta posterior tiene números en el interior para marcar el número del orificio de montaje, que corresponde al número del gancho de montaje en la parte posterior del cuerpo principal. Alinee el orificio de montaje con el gancho de montaje durante la instalación. Consulte la figura a continuación para conocer la ubicación del gancho y el orificio de montaje.

_**Vista trasera del cuerpo principal del PIR**__**Vista interior de la contraportada**_

![](<.gitbook/assets/5 (13).jpeg>)

1.  Instale el cuerpo principal del PIR en la cubierta trasera. Coloque los ganchos de la cubierta posterior en los orificios de montaje del cuerpo principal VI del PIR. Gire el cuerpo principal del PIR en el sentido de las agujas del reloj para bloquear los ganchos en el orificio de montaje. Consulte la figura a continuación,

VII. El montaje del PIR ya está completo.

![](<.gitbook/assets/6 (16).jpeg>)

3
