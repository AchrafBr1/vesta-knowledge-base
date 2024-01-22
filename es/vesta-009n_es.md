# CHALECO 009N

**Sensor de movimiento PIR (Serie IR-16)**

Nuestro algoritmo de procesador de señal adaptativo digitalizado permite que este PIR detecte movimientos dentro de un área asignada y le indique al panel de control que active la alarma si un intruso se cruza en su camino de detección.

El PIR consta de un diseño de dos partes formado por una cubierta y una base. La cubierta contiene toda la electrónica y la óptica y la base proporciona un medio de fijación. La base tiene orificios ciegos para permitir el montaje en una superficie plana o en una esquina con un soporte triangular para montaje en esquina.

La provisión para un interruptor de manipulación que se activará cuando la cubierta se retire de la base evita el acceso no autorizado y su extracción de la superficie de montaje. El PIR también puede alertarle sobre problemas de comunicación y situaciones de batería baja.

El PIR está diseñado para ofrecer un rango de detección típico de 12 metros cuando se monta a 2 metros sobre el suelo.

**El sensor PIR serie IR-16 incluye los siguientes modelos**:

![](<.gitbook/assets/0 (22).jpeg>)

IR-16 – Sensor PIR con batería de Litio de 3.6V

IRP-16 – Sensor PIR inmune a mascotas con batería de litio de 3,6 V

IR-16SL – Sensor PIR con batería de Litio de 3V

IRP-16SL – Sensor PIR inmune a mascotas con batería de litio de 3V

-   _**Identificando las piezas.**_

**1. Botón de prueba/indicador LED**

El botón de prueba se utiliza para probar el rendimiento de la radio y con fines de aprendizaje.

El indicador LED se utiliza para indicar el estado del sistema.

**2. Interruptor de manipulación**

El interruptor de manipulación protege la carcasa contra la apertura.

1.  **Aislador de batería**
2.  **Soporte de montaje en esquina**
3.  **Interruptor de puente de activación/desactivación de supervisión (JP2)**
    -   Si el puente está APAGADO (si se quita el enlace del puente o "**estacionado**”en un pin), la función de Supervisión está habilitada.**(Valor predeterminado de fábrica para los modelos de frecuencia 868 WF)**
    -   Si el puente está activado, la función de supervisión del IR-16 está desactivada.**(Predeterminado de fábrica para**

![](<.gitbook/assets/1 (30).png>)![](<.gitbook/assets/2 (13).jpeg>)

**Modelos de frecuencia 433AM y 868AM)**

-   -   -   **433FM**/**868 modelos de frecuencia FM**no admite el interruptor de puente JP2, la supervisión siempre está habilitada y no se puede deshabilitar.
    -   **Interruptor de puente aumentador de sensibilidad (JP3)**
        -   Si el puente está APAGADO (si se quita el enlace del puente o "**estacionado**”en un pin), la sensibilidad de detección del IR-16SL está en el nivel normal. (**Valor predeterminado de fábrica para modelos no inmunes a mascotas**)
        -   Si el puente está activado, la sensibilidad de detección del IR-16 es alta.**(Valor predeterminado de fábrica para modelos inmunes a mascotas)**
    -   **Manibela de encendido**
-   _**Tiempo de dormir**_

![](<.gitbook/assets/3 (13).jpeg>)![](<.gitbook/assets/4 (14).jpeg>)

El PIR tiene un “**hora de dormir**”de aproximadamente 1 minuto para ahorrar energía. Después de transmitir un movimiento detectado, el PIR no retransmitirá durante 1 minuto; cualquier movimiento adicional detectado durante este período de sueño restablecerá el temporizador de sueño de 1 minuto. De esta manera, el movimiento continuo frente a un PIR no agotará indebidamente la batería.

-   _**Función de supervisión**_

Si está habilitado, cuando el PIR esté en modo de funcionamiento normal, realizará una autoprueba periódicamente transmitiendo una señal de supervisión una vez cada 30 a 50 minutos.

Si el Panel de Control no recibe las señales de Supervisión transmitidas desde un determinado PIR durante un tiempo preestablecido, aparecerá un “**Fuera de servicio**r” se generará un mensaje de error.

-   _**Función de aumento de sensibilidad**_

Puede utilizar la función de aumento de sensibilidad para aumentar la sensibilidad de detección del IR. Para aumentar la sensibilidad de detección, vuelva a conectar el interruptor de puente de aumento de sensibilidad a**EN**posición. Para mantener la sensibilidad de detección normal, vuelva a conectar el puente al**APAGADO**posición (valor predeterminado de fábrica).

-   _**Modo de prueba**_

El PIR se puede poner en modo de prueba presionando el botón de prueba en la cubierta frontal. En el modo de prueba, desactivará el temporizador de apagado y permitirá que el indicador LED parpadee cada vez que se detecte un movimiento. Cada vez que presione el botón de prueba, el PIR transmitirá una señal de prueba al panel de control para probar el alcance de la radio y entrará en el modo de prueba durante 3 minutos. Saldrá del modo de prueba automáticamente después de 3 minutos y volverá al modo normal.

-   _**Indicador LED**_

En el modo de funcionamiento normal, el indicador LED no se encenderá excepto en las siguientes situaciones:

-   Cuando el PIR está en condición de batería baja, cada vez que transmite un movimiento detectado, el LED se iluminará durante aproximadamente 2 segundos.
-   Cuando se abre la cubierta y se viola el interruptor de manipulación, el LED se iluminará durante 2 segundos. para indicar que está transmitiendo el

1

“**Manosear**”señal.

-   -   Cuando la condición de Tamper persiste, cada vez que transmita un movimiento detectado, el LED se encenderá.
    -   Cuando el PIR está en modo de prueba, el LED se iluminará cada vez que se detecte un movimiento.
-   _**Batería**_

El sensor de movimiento PIR de la serie IR-16 utiliza diferentes baterías de litio como fuente de energía:

-   Los modelos sin SL utilizan una batería de litio AA (ER14505) de 3,6 V como fuente de alimentación.
-   Los modelos SL utilizan una batería de litio de 3V 2/3A (CR123) como fuente de energía.

Cuando se detecta un voltaje de batería bajo, se enviará una señal de batería baja al Panel de control junto con transmisiones de señales regulares para que el Panel de control muestre el estado correspondiente.

La batería la instala la fábrica antes del envío con un aislante insertado.

_\\<NOTE>_

-   -   -   -   Al cambiar las baterías, después de quitar las baterías viejas, presione el interruptor de manipulación dos veces para descargarlas por completo antes de insertar baterías nuevas.
-   _**Empezando**_
    -   Saque el aislante de la batería para activar la batería.
    -   El indicador LED parpadeará durante 30 segundos. (El PIR se está calentando). Durante el período de calentamiento, el PIR no se activará. Se recomienda que se mantenga alejado del área de detección durante este tiempo. Una vez finalizado el período de calentamiento, el LED se apagará y el PIR estará listo para funcionar.
    -   Coloque el Panel de control en modo de aprendizaje; consulte el manual del Panel de control para obtener más detalles.
    -   Presione el botón de prueba en la cubierta frontal.
    -   Consulte el manual del Panel de control para completar el proceso de aprendizaje.
    -   Después de aprender el PIR, coloque el Panel de control en "**Prueba de caminata**”, mantenga presionado el PIR en la ubicación deseada y presione el botón Prueba para confirmar que esta ubicación está dentro del alcance de la señal del panel de control; consulte el manual del panel de control para completar la prueba de caminata.
    -   Cuando esté satisfecho de que el PIR funciona en la ubicación elegida, puede proceder al montaje.
-   _**Método de montaje**_
    -   El PIR está diseñado para montarse en una superficie plana o en una esquina con los tornillos y tapones de fijación incluidos.
    -   La base tiene orificios ciegos, donde el plástico es más delgado, para fines de montaje. Cuatro orificios ciegos son para la fijación de superficies.
    -   Para el montaje en esquina, se proporciona un soporte triangular para agregar protección contra manipulación trasera. Primero monte el soporte triangular en la pared con los dos punteros en la parte superior mirando hacia usted. Coloque el PIR en los ganchos del soporte triangular o atorníllelo.
    -   Para montaje en superficie, se proporciona un soporte giratorio opcional para que los usuarios ajusten el rango de detección. Con el soporte giratorio, el IR-16 se puede girar 80 grados horizontalmente y 70 grados verticalmente para brindar una cobertura óptima.
        -   **Montaje en esquina:**

I.Rompe los dos orificios ciegos del soporte triangular.

![](<.gitbook/assets/5 (9).jpeg>)

1.  Usando los dos agujeros como plantilla, taladre agujeros en la superficie de la esquina.
2.  Inserte los tacos de pared.

IV. Atornille el soporte triangular en los tacos de pared con los dos punteros de arriba hacia usted (use un destornillador Philips).

1.  Coloque el PIR en los ganchos del soporte triangular.

VI. Si es necesario, abra el PIR quitando el tornillo de fijación y el conjunto de la cubierta con un destornillador Philips.

VII. Rompe los orificios ciegos de fijación de las esquinas correspondientes.

VIII. Utilizando los orificios ciegos de fijación de las esquinas como plantilla, vuelva a taladrar agujeros en la superficie de la esquina.

![](<.gitbook/assets/6 (13).jpeg>)

IX. Inserte los tacos si lo fija en yeso o ladrillo.

1.  Coloque el PIR en los ganchos del soporte triangular.

XI. Atornille la base a los tacos de pared con un destornillador Philips.

XII. Vuelva a atornillar la cubierta a su base con un destornillador Philips.

-   **Superficie montanosa:**

1.  Retire el conjunto del tornillo de fijación y la cubierta con un destornillador Philips.
2.  Rompe los nocauts apropiados en la base.
3.  Usando los agujeros como plantilla, taladre agujeros en la superficie.

IV. Inserte los tacos si lo fija en yeso o ladrillo.

-   -   1.  Atornille la base a los tacos de pared con un destornillador Philips.

VI. Vuelva a atornillar la cubierta a su base con un destornillador Philips.

-   **Montaje en superficie con soporte giratorio (artículo opcional, se vende por separado):**El soporte giratorio se puede montar en la pared con los tornillos proporcionados.
    1.  Atornille el soporte giratorio a la pared.

1.  Coloque los 3 ganchos del soporte giratorio en los 3 orificios de la base en consecuencia.

2

-   -   1.  Gire el soporte para obtener el rango de detección adecuado y apriete el tornillo de fijación.
-   _**Instalación**_
    -   Decida la ubicación del PIR y si se montará en una esquina o en una superficie.
    -   Después de seleccionar el sitio de instalación, siga los pasos descritos anteriormente para montar el PIR.
    -   Presione el botón de prueba para ingresar al modo de prueba. Camine por el área protegida observando cuando se enciende el LED y verifique que la cobertura de detección sea la adecuada.
    -   Cuando se considera que la cobertura de detección es satisfactoria, la instalación ya está completa.
-   _**Recomendaciones de instalación**_

**PIR normal**

-   El rango de detección es de hasta 12 metros si el PIR se monta a 2 metros del suelo.

**PIR inmune a mascotas**

-   El PIR inmune a mascotas admite la función de inmunidad a mascotas y no detectará mascotas de hasta 27 kg dentro de un rango de 7 metros para minimizar la situación de falsas alarmas.
-   Si es necesario, puede ajustar la altura del PIR según el tamaño de su mascota para lograr un rendimiento inmunológico óptimo. Una ubicación de instalación más alta proporcionará un mayor espacio inmune a las mascotas, pero también aumentará el punto ciego bajo el PIR.

![](<.gitbook/assets/7 (12).jpeg>)

Para aprovechar al máximo el PIR, se deben considerar las siguientes pautas:

-   **Se recomienda instalar el PIR en las siguientes ubicaciones**
    -   Monte el detector a una altura de 1,9 M a 2,0 M para obtener el mejor rendimiento:

_\\<IMPORTANT NOTE>_

-   -   Al decidir la altura del lugar de montaje del PIR, recuerde tener en cuenta el posible punto ciego. El punto ciego debajo del PIR aumenta proporcionalmente a la altura del sitio de montaje del PIR.
    -   Tenga en cuenta que el rendimiento se ve afectado por factores externos, como la altura del objeto detectado, el rango de detección deseado, el área de instalación, etc. La altura de montaje sugerida se puede ajustar según los factores reales del entorno de instalación.
-   Cuando el IR-16 se monta con un soporte giratorio, no tendrá el área de detección normal (como en el diagrama anterior) ni el rango inmune típico a las mascotas.
    -   Monte donde los animales no puedan llegar a la zona de detección trepando a muebles u otros objetos.
    -   No apunte el detector hacia escaleras por las que puedan subir los animales.
    -   En una posición tal que un intruso normalmente se movería a través del campo de visión del PIR de lado a lado.
    -   En una esquina para dar la vista más amplia.
    -   Donde su campo de visión no esté obstruido, p.e. por cortinas, adornos, etc.
-   **Limitaciones**
    -   No coloque un PIR para mirar directamente a una puerta protegida por un contacto de puerta, esto podría causar que las señales de radio del contacto de puerta y del PIR se transmitan al mismo instante al entrar, anulándose entre sí.
    -   No instale el PIR completamente expuesto a la luz solar directa.
    -   Evite instalar el PIR en áreas donde los dispositivos puedan causar cambios rápidos de temperatura en el área de detección, es decir, aire acondicionado, calentadores, etc.
    -   Evite grandes obstáculos en el área de detección.
    -   No apuntar directamente a fuentes de calor, p. fuegos o calderas, y no encima de radiadores.
    -   Evite mover objetos en el área de detección, como cortinas, tapices de pared, etc.

3
