# VESTA 051

-   Sensor de movimiento PIR de cortina (IRC-29)

El PIR detecta firmas infrarrojas para detectar movimientos dentro de un área asignada y le indica al panel de control que active la alarma si un intruso se cruza en su camino de detección.

El PIR consta de un diseño de dos partes formado por una cubierta y una base. El PIR contiene toda la electrónica y la óptica y la base proporciona un medio de fijación. La base tiene orificios ciegos para permitir el montaje en una superficie plana o en el techo.

El PIR tiene un interruptor de manipulación que se activará cuando se abra la cubierta o cuando se retire de la superficie montada. También puede alertarle sobre problemas de comunicación y situaciones de batería baja.

-   ![](<.gitbook/assets/0 (11).jpeg>)_**Identificar las piezas**_

1.  **Lente PIR**
2.  **Botón Aprender/Probar**

El botón de prueba se utiliza para probar el rendimiento de la radio y con fines de aprendizaje.

1.  **Indicador LED**

El indicador LED está dentro de la cubierta frontal y solo es visible cuando está activado.

1.  **Compartimiento de la batería**

El PIR utiliza 1 pila CR123A (3 V) como fuente de alimentación.

1.  **Manibela de encendido**

El interruptor de manipulación protege el PIR contra la apertura no autorizada de la cubierta o la extracción de la superficie de montaje.

1.  **Interruptor de puente de activación/desactivación de supervisión (JP2)**

![jumper close](<.gitbook/assets/1 (18).png>)![jumper open](<.gitbook/assets/2 (21).png>)

**Puente apagado**

si se elimina el enlace del puente o "**estacionado**”en un alfiler.

**Puente encendido**

El enlace del puente se inserta conectando los dos pines.

\-Cuando el puente está configurado en ON, la supervisión está deshabilitada.**(Valor predeterminado de fábrica para el modelo 433AM)**

\-Cuando el puente está configurado en APAGADO, la supervisión está habilitada.**(Valor predeterminado de fábrica para el modelo 868WF)**

_(**868FM**&**869FM**&**F1**modelos**NO**tiene JP2, la supervisión siempre está habilitada)._

1.  **Interruptor de puente aumentador de sensibilidad (JP3)**

![jumper open](<.gitbook/assets/3 (20).png>)

\-Si el puente está APAGADO (si el enlace del puente está retirado o "estacionado" en un pin), la sensibilidad de detección del PIR está en el nivel normal.**(Predeterminado de fábrica)**

![jumper close](<.gitbook/assets/4 (19).png>)

\-Si el puente está activado, la sensibilidad de detección de los PIR es alta.

1.  **Aislador de batería**

-   _**Tiempo de dormir**_

El PIR tiene un “**hora de dormir**”de aproximadamente 1 minuto para ahorrar energía. Después de transmitir un movimiento detectado, el PIR no retransmitirá durante 1 minuto; cualquier movimiento adicional detectado durante este período de sueño extenderá el tiempo de sueño en otro minuto. De esta manera, el movimiento continuo frente a un PIR no agotará indebidamente la batería.

-   _**Función de supervisión**_

Si está habilitado, el PIR realizará una autoprueba periódicamente transmitiendo una señal de supervisión una vez cada 30 a 50 minutos.

Si el Panel de Control no recibe las señales de Supervisión transmitidas desde un determinado PIR durante un tiempo preestablecido, aparecerá un “**Fuera de servicio**r” se generará un mensaje de error.

-   _**Ajuste de sensibilidad**_

Puede utilizar la función de aumento de sensibilidad para aumentar la sensibilidad de detección del PIR. Para aumentar la sensibilidad de detección, conecte el interruptor de puente (JP3) o el**EN**(valor predeterminado de fábrica. Para mantener la sensibilidad de detección normal, desconecte el interruptor de puente (JP3) o el**APAGADO**posición.

-   _**Modo de prueba**_

El PIR se puede poner en modo de prueba presionando el botón de prueba. En el modo de prueba, desactivará el temporizador de apagado y permitirá que el indicador LED parpadee cada vez que se detecte un movimiento. Cada vez que se presiona el botón de prueba, el PIR transmitirá una señal de prueba al panel de control para realizar una prueba de alcance de radio y entrará en el modo de prueba durante 3 minutos. Saldrá del modo de prueba automáticamente después de 3 minutos y volverá al modo normal.

-   _Indicador LED_

En el modo de funcionamiento normal, el indicador LED se enciende en las siguientes situaciones (para los modelos F1, el LED parpadea):

-   Cuando se detecta movimiento en condiciones de batería baja.
-   Cuando se abre o se retira la cubierta de la superficie de montaje y se activa el interruptor de manipulación.
-   Cuando se detecta movimiento si la condición de manipulación persiste.
-   Cuando se detecta movimiento en el modo de prueba.
-   Cuando se presiona el botón de prueba en condiciones de manipulación o si el PIR tiene poca batería.
-   _Batería_
-   El PIR utiliza una batería CR123A de 3V como fuente de energía.
-   El PIR presenta una función de detección de batería baja. Si se detecta un voltaje de batería bajo, se enviará una señal de batería baja al Panel de control junto con transmisiones de señal regulares para que el Panel de control muestre el estado correspondiente.
-   Para cada instalación, la batería la instala la fábrica antes del envío con un aislante insertado. Retire el aislante para activar la batería.
-   Al cambiar las baterías, retire las baterías viejas y presione el interruptor de manipulación dos veces para descargarlas antes de insertar baterías nuevas.
-   _Empezando_
-   Saque el aislante de la batería para activar la batería.
-   El indicador LED parpadeará durante 30 segundos. (El PIR se está calentando). Durante el período de calentamiento, el PIR no se activará. Se recomienda que se mantenga alejado del área de detección durante este tiempo. Una vez finalizado el período de calentamiento, el LED se apagará y el PIR estará listo para funcionar.
-   Coloque el Panel de control en modo de aprendizaje; consulte el manual del Panel de control para obtener más detalles.
-   Presione el botón de prueba.
-   Consulte el manual del Panel de control para completar el proceso de aprendizaje.
-   Después de aprender el PIR, coloque el Panel de control en "**Prueba de caminata**”, mantenga presionado el PIR en la ubicación deseada y presione el botón Prueba para confirmar que esta ubicación está dentro del alcance de la señal del panel de control; consulte el manual del panel de control para completar la prueba de caminata.
-   Cuando esté satisfecho de que el PIR funciona en la ubicación elegida, puede proceder al montaje.
-   _Cobertura de detección PIR_
-   Cuando se monta verticalmente, el PIR tiene una cobertura de detección horizontal de 10° y una cobertura de detección vertical de 110° hacia el frente.
-   El PIR solo se activará mediante movimientos a través de la cobertura horizontal de 10°.
-   El PIR se puede montar vertical u horizontalmente en la superficie de la pared o en el techo. Los diferentes métodos de montaje proporcionan diferentes coberturas y rangos de detección PIR (consulte**Métodos de montaje**a continuación para más detalles).
-   _Métodos de montaje_
-   El PIR está diseñado para montarse en una superficie plana de una pared o en el techo con los tornillos y tacos de fijación incluidos.
-   Si se retira a la fuerza el PIR montado, el área de seguridad contra manipulación quedará en la pared separada del PIR y entonces se activará la manipulación.
-   ![未命名-5](<.gitbook/assets/5 (5).jpeg>)La base tiene dos orificios ciegos, donde el plástico es más delgado y se puede romper para realizar el montaje.

1.  Retire el conjunto del tornillo de fijación y la cubierta.
2.  Rompe los nocauts en el interior de la base.
3.  Usando los agujeros como plantilla, taladre agujeros en la superficie.
4.  Inserte los tacos si lo fija en yeso o ladrillo.
5.  Atornille la base a los tacos de pared.
6.  Atornille la tapa a la base.

-   Existen diferentes métodos de montaje, incluidos el montaje vertical/horizontal y el montaje en techo, y cada uno de ellos tiene una aplicación diferente. Consulte los métodos de montaje siguientes.

**Montaje en pared vertical:**

-   Cuando se monta verticalmente, el PIR tiene un rango de detección de 10 metros únicamente contra movimiento horizontal.
-   Se sugiere montar el PIR verticalmente entre 1,4 y 1,6 metros sobre el suelo.
-   Evite el montaje a más de 1,7 metros, de lo contrario el rango de detección PIR podría verse afectado.

**Montaje en pared horizontal:**

-   Cuando se monta horizontalmente, el PIR tiene un rango de detección de 5 metros únicamente contra movimiento vertical. Esta práctica se utiliza generalmente para proteger a los intrusos de la claraboya o de la trampilla del tejado.
-   Evite el montaje por debajo de 2,2 metros, lo que puede afectar el rendimiento de la detección.

**Vertical****Horizontal**

![](<.gitbook/assets/6 (8).png>)![](<.gitbook/assets/7 (5).png>)

**Montaje en techo:**

-   Monte el PIR en el techo para mirar hacia abajo sobre una puerta o ventana.
-   Cuando se monta en el techo, el PIR solo puede detectar movimiento vertical contra el PIR dentro del rango de detección.
-   Cuando se monta a 2,4~A 3 metros de altura y mirando hacia abajo, el PIR tiene una cobertura de aproximadamente**5**metros a nivel del suelo.
-   Evite el montaje a más de 4 metros, lo que puede afectar el rendimiento de la detección.

![](<.gitbook/assets/8 (5).png>)

-   _Instalación_
-   Decida la ubicación del PIR si va a ser horizontal/vertical o montado en el techo.
-   Después de seleccionar el sitio de instalación, siga los pasos descritos anteriormente para montar el PIR.
-   Presione el botón de prueba para ingresar al modo de prueba. Camine por el área protegida observando cuando se enciende el LED y verifique que la cobertura de detección sea la adecuada.
-   Cuando se considera que la cobertura de detección es satisfactoria, la instalación ya está completa.
-   _Recomendaciones de instalación_

\\<Important NOTE>

-   Al decidir la altura del lugar de montaje del PIR, recuerde tener en cuenta el posible punto ciego. El punto ciego debajo del PIR aumenta proporcionalmente a la altura del sitio de montaje del PIR.
-   Tenga en cuenta que el rendimiento se ve afectado por factores externos, como la altura del objeto detectado, el rango de detección deseado, el área de instalación, etc. La altura de montaje sugerida se puede ajustar según los factores reales del entorno de instalación.
-   En una posición tal que un intruso normalmente se movería a través del campo de visión del PIR de lado a lado.
-   Donde su campo de visión no esté obstruido, p. por cortinas, adornos, etc.
-   **Limitaciones**
-   No coloque un PIR para mirar directamente a una puerta protegida por un contacto de puerta, esto podría causar que las señales de radio del contacto de puerta y del PIR se transmitan al mismo instante al entrar, anulándose entre sí.
-   No instale el PIR completamente expuesto a la luz solar directa.
-   Evite instalar el PIR en áreas donde los dispositivos puedan causar cambios rápidos de temperatura en el área de detección, es decir, aire acondicionado, calentadores, etc.
-   Evite grandes obstáculos en el área de detección.
-   No apuntar directamente a fuentes de calor, p. fuegos o calderas, y no encima de radiadores.
-   Evite mover objetos en el área de detección, como cortinas, tapices de pared, etc.
