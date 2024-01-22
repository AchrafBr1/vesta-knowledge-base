# VESTA 136

-   Sensor de movimiento PIR Serie IR(P)-29

El PIR detecta firmas infrarrojas para detectar movimientos dentro de un área asignada y le indica al panel de control que active la alarma si un intruso se cruza en su camino de detección.

El PIR consta de un diseño de dos partes formado por una cubierta y una base. La cubierta contiene toda la electrónica y la óptica y la base proporciona un medio de fijación. La base tiene orificios ciegos para permitir el montaje en una superficie plana o en una esquina.

El PIR tiene un interruptor de manipulación que se activará cuando se abra la cubierta. También puede alertarle sobre problemas de comunicación y situaciones de batería baja.

El PIR está diseñado para ofrecer un rango de detección típico de 12 metros cuando se monta a 2 metros sobre el suelo.

Los modelos Pet-Immune del sensor PIR de la serie IR-29 admiten además la función de inmunidad a mascotas y no detectarán mascotas de hasta 27 kg dentro de un rango de 7 metros para minimizar la situación de falsas alarmas.

**El sensor PIR serie IR-29 incluye los siguientes modelos**:

IR-29 / IR-29 F1 – Sensor PIR con pilas alcalinas

IRP-29 / IRP-29 F1 – Sensor PIR inmune a mascotas con pilas alcalinas

IR-29SL / IR-29SL-F1 – Sensor PIR con batería de litio.

![](<.gitbook/assets/0 (20).png>)IRP-29SL / IRP-29SL-F1 – Sensor PIR inmune a mascotas con batería de litio

-   _**Identificar las piezas**_

**1. Botón de prueba/indicador LED**

El botón de prueba se utiliza para probar el rendimiento de la radio y con fines de aprendizaje.

El indicador LED se utiliza para indicar el estado del sistema.

**2. Aislador de batería**

**3. Interruptor de puente de activación/desactivación de supervisión (JP2)**

![jumper open](<.gitbook/assets/1 (27).png>)![jumper close](<.gitbook/assets/2 (32).png>)

**Puente apagado**

si se elimina el enlace del puente o "**estacionado**”en un alfiler.

**Puente encendido**

El enlace del puente se inserta conectando los dos pines.

-   Cuando se establece en ON, la supervisión está desactivada.**(Valor predeterminado de fábrica para los modelos de frecuencia 433AM)**
-   Cuando se establece en APAGADO, la supervisión está habilitada.**(Valor predeterminado de fábrica para los modelos de frecuencia 868WF)**

**433 FM**y**Modelos de frecuencia 868FM**no admite el interruptor de puente JP2, la supervisión está habilitada y no se puede deshabilitar.

**4. Interruptor de puente aumentador de sensibilidad (JP3)**

-   Cuando se configura en APAGADO, la sensibilidad de detección del PIR está en el nivel normal.**(Valor predeterminado de fábrica para modelos no inmunes a mascotas)**
-   Cuando se establece en ON, la sensibilidad de detección de PIR es alta. (Valor predeterminado de fábrica para los modelos inmunes a mascotas)

**5. Interruptor de manipulación**

El interruptor de manipulación protege el PIR contra la apertura no autorizada de la cubierta.

-   _**Tiempo de dormir**_

El PIR tiene un “**hora de dormir**”de aproximadamente 1 minuto para ahorrar energía. Después de transmitir un movimiento detectado, el PIR no retransmitirá durante 1 minuto; cualquier movimiento adicional detectado durante este período de sueño extenderá el tiempo de sueño en otro minuto. De esta manera, el movimiento continuo frente a un PIR no agotará indebidamente la batería.

-   _**Función de supervisión**_

Si está habilitado (consulte la tabla anterior), cuando el PIR esté en modo de funcionamiento normal, realizará una autoprueba periódicamente transmitiendo una señal de supervisión una vez cada 30 a 50 minutos.

Si el Panel de Control no recibe las señales de Supervisión transmitidas desde un determinado PIR durante un tiempo preestablecido, aparecerá un “**Fuera de servicio**r” se generará un mensaje de error.

-   _**Función de aumento de sensibilidad**_

Puede utilizar la función de aumento de sensibilidad para aumentar la sensibilidad de detección del PIR. Para aumentar la sensibilidad de detección, conecte el interruptor de puente (JP3) o el**EN**posición (valor predeterminado de fábrica para los modelos inmunes a mascotas). Para mantener una sensibilidad de detección normal, desconecte el interruptor de puente (JP3) o el**APAGADO**posición (valor predeterminado de fábrica para modelos no inmunes a mascotas).

-   _**Modo de prueba**_

El PIR se puede poner en modo de prueba presionando el botón de prueba en la cubierta frontal. En el modo de prueba, desactivará el temporizador de apagado y permitirá que el indicador LED parpadee cada vez que se detecte un movimiento. Cada vez que se presiona el botón de prueba, el PIR transmitirá una señal de prueba al panel de control para realizar una prueba de alcance de radio y entrará en el modo de prueba durante 3 minutos. El modo de prueba finalizará después de 3 minutos.

-   _Indicador LED_

En el modo de funcionamiento normal, el indicador LED se ilumina en las siguientes situaciones (para los modelos F1, el LED parpadea):

-   Cuando se detecta movimiento en condiciones de batería baja
-   Cuando se abre la cubierta y se activa el interruptor de manipulación.
-   Cuando se detecta movimiento si la condición de manipulación persiste.
-   Cuando se detecta movimiento en el modo de prueba
-   Cuando se presiona el botón de prueba en condiciones de manipulación o si el PIR tiene poca batería.
-   _Batería_

El sensor de movimiento PIR de la serie IR-29 se utiliza con baterías alcalinas o de litio como fuente de energía:

-   Los modelos de alimentación alcalina utilizan dos pilas alcalinas AA de 1,5 V como fuente de alimentación.
-   Los modelos que funcionan con litio utilizan una batería de litio de 3V 2/3A (EL123AP) como fuente de energía.

El PIR presenta una función de detección de batería baja. Si se detecta un voltaje de batería bajo, se enviará una señal de batería baja al Panel de control junto con transmisiones de señal regulares para que el Panel de control muestre el estado correspondiente.

Para cada instalación, la batería la instala la fábrica antes del envío con un aislante insertado.

\\<NOTE>

-   Al cambiar las baterías, después de quitar las baterías viejas, presione el interruptor de manipulación dos veces para descargarlas por completo antes de insertar baterías nuevas.
-   _Empezando_
-   Saque el aislante de la batería para activar la batería.
-   El indicador LED parpadeará durante 30 segundos. (El PIR se está calentando). Durante el período de calentamiento, el PIR no se activará. Una vez finalizado el período de calentamiento, el LED se apagará y el PIR estará listo para funcionar.
-   Coloque el Panel de control en modo de aprendizaje; consulte el manual del Panel de control para obtener más detalles.
-   Presione el botón de prueba en la cubierta frontal.
-   Consulte el manual del Panel de control para completar el proceso de aprendizaje.
-   Después de aprender el PIR, coloque el Panel de control en "**Prueba de caminata**”, mantenga presionado el PIR en la ubicación deseada y presione el botón Prueba para confirmar que esta ubicación está dentro del alcance de la señal del panel de control; consulte el manual del panel de control para completar la prueba de caminata.
-   Cuando esté satisfecho de que el PIR funciona en la ubicación elegida, puede proceder al montaje.
-   _Método de montaje_
-   El PIR está diseñado para montarse en una superficie plana o en una esquina con los tornillos y tapones de fijación incluidos.
-   ![](<.gitbook/assets/3 (28).png>)La base tiene orificios ciegos, donde el plástico es más delgado y se puede romper para realizar el montaje. Dos orificios ciegos son para fijación en superficie y cuatro orificios ciegos para fijación en esquina, como se muestra en la imagen.
-   Para el montaje en esquina, se proporciona un soporte triangular para agregar protección contra manipulación trasera. El soporte también incluye dos orificios ciegos para montar en la pared.
-   Para montaje en superficie, se proporciona un soporte giratorio opcional para que los usuarios ajusten el rango de detección. Con el soporte giratorio, el IR-29 se puede girar 80 grados horizontalmente y 70 grados verticalmente para brindar una cobertura óptima.
-   **Montaje en esquina:**

1.  Rompe los nocauts de las cuatro esquinas.
2.  Usando los cuatro agujeros como plantilla, taladre agujeros en la superficie de la esquina.
3.  Inserte los tacos de pared.
4.  Atornille la base al taco de pared.
5.  ![](<.gitbook/assets/4 (27).png>)Atornille la tapa a la base.

-   **Montaje en esquina con soporte triangular:**

El soporte triangular se puede montar en la pared con los tornillos proporcionados o con almohadillas adhesivas de doble cara.

Montaje con tornillos

1.  Rompe los dos orificios ciegos del soporte triangular.
2.  Usando los dos agujeros como plantilla, taladre agujeros en la superficie de la esquina. Inserte tacos de pared.
3.  Atornille el soporte triangular en los tacos de pared con los dos punteros de arriba hacia usted.
4.  Coloque el PIR en los ganchos del soporte triangular.

Montaje autoadhesivo

1.  La esquina de montaje debe estar limpia, seca y lisa. Limpie la esquina de montaje con un desengrasante adecuado si es necesario.
2.  Antes del envío, se colocan dos almohadillas adhesivas de doble cara en el soporte triangular.
3.  Retire la cubierta protectora de las almohadillas adhesivas de doble cara.
4.  Fije el soporte triangular en la esquina deseada con los dos punteros en la parte superior mirando hacia usted.
5.  Coloque el PIR en los ganchos del soporte triangular.

-   **Superficie montanosa:**

1.  Retire el conjunto del tornillo de fijación y la cubierta.
2.  ![](<.gitbook/assets/5 (19).png>)Rompe los nocauts en el interior de la base.
3.  Usando los agujeros como plantilla, taladre agujeros en la superficie.
4.  Inserte los tacos si lo fija en yeso o ladrillo.
5.  Atornille la base a los tacos de pared.
6.  Atornille la tapa a la base.

-   **Montaje en superficie con soporte giratorio (artículo opcional, se vende por separado):**

El soporte giratorio se puede montar en la pared con los tornillos proporcionados.

1.  Atornille el soporte giratorio a la pared.
2.  Coloque los 3 ganchos del soporte giratorio en los 3 orificios de la base en consecuencia.
3.  Gire el soporte para obtener el rango de detección adecuado y apriete el tornillo de fijación.

-   _Instalación_
-   Decida la ubicación del PIR y si se montará en una esquina o en una superficie.
-   Después de seleccionar el sitio de instalación, siga los pasos descritos anteriormente para montar el PIR.
-   Presione el botón de prueba para ingresar al modo de prueba. Camine por el área protegida observando cuando se enciende el LED y verifique que la cobertura de detección sea la adecuada.
-   Cuando se considera que la cobertura de detección es satisfactoria, la instalación ya está completa.
-   _Recomendaciones de instalación_

El PIR está diseñado para ofrecer un rango de detección típico de 12 metros cuando se monta a 2 metros sobre el suelo.

Para la serie Pet-Immune PIR, ofrece un alcance típico de PET IMMUNE de 7 metros cuando se monta a 1,9-2,0 metros sobre el suelo. Si se monta a mayor altura sobre el suelo, proporciona un rango INMUNE al PET más amplio.

Para aprovechar al máximo el PIR, se deben considerar las siguientes pautas:

-   **Se recomienda instalar el PIR en las siguientes ubicaciones**
-   Monte el detector a una altura de 1,9 M a 2,0 M para obtener el mejor rendimiento:

![](<.gitbook/assets/6 (11).png>)

\\<Important NOTE>

-   Para obtener el rendimiento más deseable de la serie Pet-Immune PIR, recuerde ajustar la altura del sitio de montaje del PIR con respecto a la altura del animal más alto de la casa. Las mascotas más altas que el promedio pueden requerir que el PIR esté montado más alto para fines de inmunidad a las mascotas.
-   Al decidir la altura del lugar de montaje del PIR, recuerde tener en cuenta el posible punto ciego. El punto ciego debajo del PIR aumenta proporcionalmente a la altura del sitio de montaje del PIR.
-   Tenga en cuenta que el rendimiento se ve afectado por factores externos, como la altura del objeto detectado, el rango de detección deseado, el área de instalación, etc. La altura de montaje sugerida se puede ajustar según los factores reales del entorno de instalación.
-   Cuando el IR-29 se monta con un soporte giratorio, no tendrá el área de detección normal (como en el diagrama anterior) ni el rango inmune típico a las mascotas.
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
