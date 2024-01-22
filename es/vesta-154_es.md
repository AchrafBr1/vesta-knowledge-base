# VESTA 154

**Sensor de movimiento de cortina para exteriores EIRC-1-F1**

EIRC-1-F1 es un sensor de movimiento de cortina para exteriores que está equipado con tecnología de detección de movimiento PIR y microondas. La combinación de métodos de detección dual mejora en gran medida la precisión de detección del sensor de movimiento y reduce la tasa de falsas alarmas, al utilizar el PIR como detección inicial y el microondas como confirmación antes de transmitir la señal de activación.

El sensor de movimiento también cuenta con función antienmascaramiento. Es capaz de detectar cualquier intento de cegar el sensor colocando objetos en su campo de visión.

Al utilizar la placa de montaje en forma de L, el usuario puede elegir entre montaje plano o montaje lateral al instalar el sensor de movimiento en la pared. Este diseño permite que el sensor de movimiento detecte movimientos sospechosos en la puerta de entrada o detecte intrusos trepando y rompiendo vallas o paredes.

_**Identificación de piezas**_

**Frente****Interno**

![](<.gitbook/assets/0 (46).png>)

**1.****Detector de proximidad digital**

El detector se utiliza para detectar cualquier intento de enmascaramiento (bloqueo) por parte de un intruso.

1.  **Lente del sensor**
2.  **LED del transmisor (rojo)**

El LED se enciende brevemente cuando:

-   Se presiona el botón Aprender/Probar.
-   El interruptor de manipulación se activa o se restablece.
-   Se detecta movimiento en el modo de prueba
-   Se detecta movimiento en condiciones de batería baja o apertura por manipulación durante el funcionamiento normal.

Cuando la batería del sensor de movimiento se agota, el LED parpadea cada 4 segundos.

**4. LED de detección de microondas (azul)**

El LED se ilumina brevemente cuando se activa la detección de microondas en el modo de prueba o en el modo de prueba de microondas.

**5. LED de detección de infrarrojos (verde)**

El LED se ilumina brevemente cuando se activa la detección de infrarrojos en el modo de prueba.

1.  **Manibela de encendido**
2.  **Interruptor de puente aumentador de sensibilidad (JP3)**
    -   -   Si el puente es**APAGADO**(si el puente se retira o se "estaciona" en un pin), la sensibilidad de detección del sensor de movimiento está en el nivel normal.**(Predeterminado de fábrica)**
        -   Si el puente es**EN**, la sensibilidad de detección del sensor de movimiento es alta.
3.  **Interruptor de puente de activación/desactivación de prueba de microondas (JP2)**
    -   Cuando el puente está configurado como**EN**, el sensor de movimiento está en modo de prueba de microondas (consulte**Modo de prueba de microondas**)
    -   Cuando el puente está configurado como**APAGADO**, el modo de prueba de microondas está desactivado.**(Predeterminado de fábrica)**

![](<.gitbook/assets/1 (49).jpeg>)![](<.gitbook/assets/2 (46).jpeg>)![](<.gitbook/assets/3 (56).png>)

1

![](<.gitbook/assets/4 (41).jpeg>)

1.  **Interruptor de rango de microondas**

La escala de rango se muestra a la derecha con la flecha apuntando al nivel de sensibilidad actual:

-   -   Girando en el**Sentido de las agujas del reloj**aumenta el rango de detección.
    -   Girando en el**Dirección en sentido antihorario**disminuye el rango de detección.**Predeterminado de fábrica**: está configurado en medio.

1.  **Botón Aprender/Probar**
2.  **Compartimiento de la batería**
3.  **Placa de montaje tipo L**
4.  **Orificios de montaje**
5.  **Escudo protector**

La pantalla protectora protege el detector de proximidad digital de la lluvia.

_**Características**_

-   _**Detección de movimiento**_
    -   El sensor de movimiento tiene un sensor PIR incorporado y un transmisor de microondas. La detección de movimiento la realiza el sensor PIR durante el funcionamiento normal. Cuando el sensor PIR detecta movimiento, el transmisor de microondas se activará para verificar la detección de movimiento. Si tanto PIR como Microondas confirman la detección de movimiento, el sensor de movimiento transmitirá la señal de detección.
    -   La señal de detección solo se transmitirá cuando tanto el PIR como el microondas detecten movimiento.
    -   Ajuste la configuración del interruptor de rango de microondas para sintonizar el transmisor de microondas y el rango de detección general.
    -   Cuando el interruptor de alcance de microondas está configurado en Máximo, el sensor de movimiento tiene un alcance aproximado de 11 metros cuando se monta a 1,4~1,6 m de altura.
    -   Cuando el interruptor de alcance del microondas está configurado en Medio, el sensor de movimiento tiene un alcance aproximado de 8,5 metros cuando se monta a 1,4~1,6 m de altura.
    -   Cuando el interruptor de alcance de microondas está configurado en Mínimo, el sensor de movimiento tiene un alcance aproximado de 4,5 metros cuando se monta a 1,4~1,6 m de altura.
-   _**Tiempo de dormir**_

El sensor de movimiento presenta un “tiempo de reposo” automático de aproximadamente**1 minuto**para la conservación de energía. Después de transmitir un movimiento detectado, el EIR no retransmitirá durante un minuto. Cualquier movimiento adicional detectado dentro de este período de sueño de un minuto extenderá el tiempo de sueño en otro minuto. De esta manera, el movimiento continuo frente al EIR no agotará excesivamente la batería.

-   _**Modo de prueba**_

El sensor de movimiento se puede poner en modo de prueba presionando el botón Aprender/Prueba. El modo de prueba dura 10 minutos y se restablecerá a 10 minutos al presionar cualquier botón de aprendizaje/prueba. En el modo de prueba, el temporizador de apagado está desactivado y los LED se iluminarán cuando se detecte movimiento. Utilice el modo de prueba para determinar la cobertura de detección del sensor de movimiento al instalar el sensor.

-   _**Modo de prueba de microondas**_

El modo de prueba de microondas es solo para pruebas de alcance de microondas. Utilice el puente JP2 para habilitar el modo de prueba de microondas. Cuando el sensor de movimiento está en modo de prueba de microondas, la detección PIR está desactivada, el transmisor de microondas se activará para enviar repetidamente una señal de microondas para la detección de movimiento. Cuando el sensor de movimiento detecta movimiento en el modo de prueba de microondas, el LED azul del microondas se iluminará brevemente para indicarlo.

Utilice el modo de prueba de microondas para determinar el rango de microondas y ajuste el rango con el interruptor de rango de microondas si es necesario. Asegúrese de desactivar el modo de prueba de microondas después de completar la prueba configurando el puente JP2 en APAGADO y regresando el sensor de movimiento a su funcionamiento normal.

-   _**Batería**_
    -   El sensor de movimiento utiliza dos baterías de litio AA L91 como fuente de energía.
    -   El sensor de movimiento presenta detección de batería baja; cuando se detecta un voltaje de batería bajo, se enviará una señal de batería baja al panel de control junto con transmisiones de señal regulares.
    -   Si no se cambia la batería después de la detección de batería baja y la batería está completamente agotada, el sensor de movimiento detendrá toda operación. El LED rojo parpadeará cada 4 segundos para indicarlo.
    -   Al cambiar las baterías, después de retirar las baterías viejas, presione el interruptor de manipulación o el modo de aprendizaje/prueba un par de veces para descargarlas por completo antes de insertar baterías nuevas.
-   _**Supervisión**_
    -   Después de la instalación, el sensor de movimiento transmitirá una señal de supervisión al panel de control cada 30 a 50 minutos.
    -   Si el panel de control no recibe las señales de supervisión del sensor de movimiento durante un período de tiempo preestablecido, el panel de control indicará en su pantalla que el sensor en particular está fuera de servicio.
-   _**Manibela de encendido**_

El interruptor antisabotaje del sensor de movimiento está en posición normal (sabotaje cerrado) cuando el resorte se comprime contra el interior de la cubierta posterior del dispositivo. La infracción de manipulación ocurre cuando se retira la cubierta frontal de la base y se suelta el interruptor de manipulación.

2

-   _**Detección de proximidad**_
    -   El sensor de movimiento tiene un detector de proximidad digital que puede detectar cualquier intento de enmascaramiento (bloqueo) por parte de un intruso.
    -   Cuando se detecta un evento de enmascaramiento y la condición de enmascaramiento dura 2 minutos, EIRC-1-F1 enviará una señal de apertura por manipulación al panel de control para notificar al usuario de la condición.
    -   Después de eliminar el enmascaramiento/bloqueo durante 2 minutos, EIRC-1-F1 enviará una señal de restauración de manipulación al panel de control.

_\\<NOTE>_

-   Cualquier movimiento del disparador IR borrará el evento/condición de enmascaramiento actualmente detectado. Se debe detectar un nuevo evento de enmascaramiento y durar 2 minutos para que se transmita el informe de apertura por manipulación.

_**Aprendizaje e instalación**_

-   _**Empezando**_
    1.  Retire la cubierta frontal de la base aflojando el tornillo de fijación inferior.
    2.  Oriente e inserte las baterías según la polaridad.
    3.  El LED rojo del transmisor comenzará a parpadear durante 30 segundos para indicar que el sensor de movimiento se está calentando. Durante el período de calentamiento, el sensor de movimiento no se activará. Se recomienda que se mantenga alejado del área de detección durante este tiempo. Después del período de calentamiento, el LED rojo se apagará y el sensor de movimiento entrará en funcionamiento normal.
    4.  Ponga el Panel de Control en modo de aprendizaje; consulte el manual del Panel de control para obtener más detalles.
    5.  Presione el botón Aprender/Probar para transmitir la señal al panel.
    6.  Si el panel recibe una señal del sensor de movimiento, mostrará la información del sensor en consecuencia. Consulte su Panel de control para completar el proceso de aprendizaje.
    7.  Una vez que se haya aprendido el sensor de movimiento, coloque el panel de control en modo “Prueba de caminata”, sostenga el sensor en la ubicación deseada y presione el interruptor de prueba para confirmar que esta ubicación esté dentro del alcance de la señal del panel de control.
    8.  Cuando esté satisfecho con la ubicación elegida, puede continuar con la instalación.

_\\<NOTE>_

-   -   -   **Prueba de caminata**Se debe realizar una prueba para confirmar el funcionamiento y la cobertura adecuados del sensor de movimiento.
        -   Al aprender el sensor de movimiento o realizar la prueba de caminata, evite obstruir el detector antienmascaramiento con la mano; de lo contrario, la señal de apertura se transmitirá al panel de control si la condición de enmascaramiento dura 2 minutos.
-   _**Método de montaje**_
    -   El EIRC-1-F1 está diseñado para montarse en la pared. Dependiendo de cómo utilice la placa de montaje en forma de L, el sensor de movimiento puede montarse de forma plana o lateral cuando se instala en la pared.

**Montaje plano**

1.  Separe el conjunto de base y cubierta del EIRC-1-F1.
2.  Utilice los orificios de montaje en el lado más largo de la placa de montaje en forma de L como plantilla para perforar orificios en la pared para los enchufes. Fije el lado más largo de la placa de montaje en la pared con los tornillos proporcionados.**(Foto 1)**
3.  Fije la cubierta posterior de EIRC-1-F1 a la placa de montaje con dos tornillos proporcionados.**(Imagen 2)**

IV. Coloque la cubierta frontal en la cubierta trasera y apriete el tornillo de fijación inferior.**(Imagen 2)**

1.  Inserte el escudo protector. (Retire la película protectora de ambos lados del protector antes de insertarla).

**(Imagen 3)**

![](<.gitbook/assets/5 (25).jpeg>)

3

**Montaje lateral**

1.  Separe el conjunto de base y cubierta del EIRC-1-F1.
2.  Utilice los orificios de montaje en el lado angosto de la placa de montaje en forma de L como plantilla para perforar orificios en la pared para los enchufes. Fije el lado angosto de la placa de montaje en la pared con los tornillos suministrados.**(Foto 1)**
3.  Fije la cubierta posterior de EIRC-1-F1 a la placa de montaje con dos tornillos proporcionados.**(Imagen 2)**

IV. Coloque la cubierta en la cubierta posterior y apriete el tornillo de fijación inferior.**(Imagen 2)**

1.  Inserte el escudo protector.**(Imagen 3)**(Retire la película protectora de ambos lados del protector antes de insertarla).

![](<.gitbook/assets/6 (35).jpeg>)

_\\<NOTE>_

-   Hay tres tuercas en la placa de montaje, lo que proporciona dos niveles de montaje (alto/bajo) para seleccionar. Después de fijar la placa de montaje en la pared, puede optar por montar el EIRC-1-F1 en el nivel inferior o superior con dos tornillos proporcionados.

![](<.gitbook/assets/7 (34).jpeg>)

4

_\\<NOTE>_

-   -   Después de montar el EIRC-1-F1, si el panel de control muestra el estado de falla de manipulación para el dispositivo, asegúrese de que el detector antienmascaramiento no esté obstruido por ningún objeto y espere dos minutos para ver si se borra el estado de apertura de manipulación. . Si el estado de apertura por manipulación persiste después de dos minutos, retire el sensor de movimiento de la ubicación de montaje y verifique si el interruptor contra manipulación está comprimido correctamente contra el interior de la cubierta posterior del dispositivo.
-   _**Recomendaciones de instalación**_

El sensor de movimiento debe montarse a 1,4 m.~1,6 m para un rendimiento óptimo. Tiene un alcance máximo de 11 metros cuando el sensor de microondas está configurado en el alcance máximo y montado a 1,6 metros de altura.

_\\<IMPORTANT NOTE>_

-   -   Tenga en cuenta que el rendimiento se ve afectado por factores externos, como la altura del objeto detectado, el rango de detección deseado, el área de instalación, etc. La altura de montaje sugerida se puede ajustar según los factores reales del entorno de instalación.
-   **Se recomienda instalar el sensor de movimiento en las siguientes ubicaciones**
    -   Móntelo en una posición tal que un intruso normalmente se mueva a través del campo de visión del sensor.
    -   Monte donde no se obstruya su campo de visión, p. por cortinas, adornos, etc.
-   **Limitaciones**
    -   No coloque un sensor de movimiento para mirar directamente a una puerta protegida por un contacto de puerta, esto podría causar que las señales de radio del contacto de puerta y del sensor de movimiento se transmitan al mismo instante al entrar, provocando una colisión de señales.
    -   No instale el sensor de movimiento completamente expuesto a la luz solar directa.
    -   Evite instalar el sensor de movimiento en áreas donde los dispositivos puedan causar cambios rápidos de temperatura en el área de detección, es decir, aire acondicionado, calentadores, etc.
    -   Evite grandes obstáculos en el área de detección.
    -   No apunte el sensor directamente hacia fuentes de calor, p. fuegos o calderas, y no encima de radiadores.
    -   Evite mover objetos en el área de detección, como cortinas, tapices de pared, etc.

![](<.gitbook/assets/8 (27).jpeg>)

5

![](<.gitbook/assets/9 (18).jpeg>)

6
