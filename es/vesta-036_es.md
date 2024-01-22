# VESTA 036

**Sensor de movimiento PIR inmune a mascotas para exteriores (EIR-32)**

El EIR-32, un detector PIR para exteriores que funciona con baterías, permite una instalación en exteriores económica y sin esfuerzo al tiempo que proporciona capacidades de detección excepcionales.

El sensor incorporado con sensibilidad de detección elimina la posibilidad de falsas alarmas causadas por animales pequeños u otras perturbaciones exteriores.

La función antienmascaramiento permite detectar cualquier intento de cegar el detector colocando objetos en su campo de visión.

Además, el rango de detección ajustable ofrece una combinación eficaz para cada entorno de instalación, lo que proporciona un estilo de vida tranquilo y, al mismo tiempo, protege sus instalaciones y a sus seres queridos durante todo el año.

-   _**Identificar las piezas**_

**Vista frontal****Vista interior****Vista trasera**

![](<.gitbook/assets/0 (32).png>)

1.  **Detector de proximidad digital**

El detector se utiliza para detectar cualquier intento de enmascaramiento (bloqueo) por parte de un intruso.

1.  **Indicador LED**

El indicador LED se utiliza para indicar el estado del sistema.

1.  **Sensor de infrarrojos**

El sensor está destinado a detectar objetos en movimiento.

1.  **Botón de prueba**

El botón Prueba se utiliza para probar el rendimiento de la radio y con fines de aprendizaje.

1.  **Bloque de interruptores DIP**

Hay 8 interruptores DIP para configurar los niveles de sensibilidad de detección y función.

1.  **Manibela de encendido**

El EIR-32 está protegido por el interruptor de manipulación contra cualquier extracción no autorizada de la placa de montaje o de la ubicación de montaje.

1.  **Compartimiento de la batería**
2.  **Placa de montaje**
3.  **Área de ruptura**

El área de separación tiene 6 orificios ciegos (2 para montaje en superficie y 4 para montaje en esquina) donde el plástico es más delgado para montaje con tornillos. Cuando el detector se retira a la fuerza de la ubicación de montaje, el área de separación se separará y permitirá que se active el interruptor de manipulación.

**10. Escudo protector**

La pantalla protectora protege el detector de proximidad digital de la lluvia.

-   _**Indicador LED**_

En el modo de funcionamiento normal, el indicador LED permanece apagado excepto:

-   Cuando el sensor de movimiento tiene batería baja, cada vez que transmite un movimiento detectado, el LED parpadeará durante

1

6 veces.

-   -   Cuando se activa el interruptor de manipulación, el LED parpadeará 6 veces para indicar que está transmitiendo "**Manosear**”señal.
    -   Cuando la condición de Tamper persiste, cada vez que transmite un movimiento detectado, el LED parpadeará 6 veces.
    -   En el modo de prueba, el LED parpadeará 6 veces cada vez que se detecte un movimiento.
-   _**Modo de prueba**_

El sensor de movimiento se puede poner en modo de prueba durante 10 minutos presionando el botón de prueba una vez. En el modo de prueba, el temporizador de apagado está desactivado y el indicador LED está habilitado para iluminarse durante dos segundos cada vez que se detecta un movimiento. El sensor de movimiento saldrá automáticamente del modo de prueba después de 10 minutos y volverá al modo normal.

Para poner el sensor de movimiento en modo de prueba constante, ajuste el interruptor DIP 1 (consulte_Tabla de posiciones del interruptor DIP_).

-   _**Batería**_
    -   El sensor de movimiento utiliza dos baterías de litio AAL91 como fuente de energía.
    -   El sensor de movimiento presenta detección de voltaje de batería baja. Cuando se detecta batería baja, se enviará una señal de batería baja al Panel de control junto con transmisiones de señal regulares para que el Panel de control muestre el estado correspondiente.
    -   **Para cambiar la batería:**

**Paso 1:**Navegue por el Panel de control al modo de programación.

**Paso 2:**Retire el sensor de movimiento de la posición de montaje y desatorníllelo para abrir la cubierta superior.

**Paso 3:**Retire las baterías viejas y presione el botón de manipulación durante unos segundos para descargarlas por completo.

**Etapa 4:**Inserte dos baterías de litio AAL91 nuevas.

**Paso 5:**Vuelva a atornillar la cubierta superior.

**Paso 6:**Vuelva a montar el sensor de movimiento en la ubicación de montaje.

**Paso 7:**Navegue por el Panel de control para salir del modo de programación y volver al modo de operación. El procedimiento está completo.

-   _**Señal de supervisión**_
    -   Después de la instalación, el sensor de movimiento transmitirá automáticamente señales de supervisión periódicamente al panel de control en intervalos aleatorios de 30 a 50 minutos.
    -   Si el panel de control no ha recibido la señal del sensor de movimiento durante el período de tiempo preestablecido, el panel de control indicará en su pantalla que el sensor de movimiento en particular está experimentando un problema de falta de señal.
-   _**Tiempo de dormir**_

El sensor de movimiento presenta un “tiempo de suspensión” automático de aproximadamente un minuto para conservar energía. Después de transmitir un movimiento detectado, el sensor de movimiento no volverá a transmitir durante un minuto. Cualquier movimiento adicional detectado dentro de este período de sueño de un minuto extenderá el tiempo de sueño en otro minuto. De esta manera, el movimiento continuo frente al sensor de movimiento no agotará excesivamente la batería.

-   _**Función de doble golpe**_

El sensor de movimiento tiene una función de doble golpe. Si la función de doble golpe está habilitada, el sensor de movimiento informará una alarma al panel de control solo si se detectan dos movimientos dentro de 10 segundos. Si la función de doble golpe está desactivada, el sensor de movimiento informará una alarma al panel de control cuando se detecte un movimiento.

-   _**Detección de proximidad**_
    -   El sensor de movimiento tiene un detector de proximidad digital que puede detectar cualquier intento de enmascaramiento (bloqueo) por parte de un intruso.
    -   Cuando se detecta un evento de enmascaramiento y la condición de enmascaramiento dura 2 minutos, el EIR-32 enviará una señal de apertura por manipulación al panel de control para notificar al usuario de la condición.
    -   Después de eliminar el enmascaramiento/bloqueo durante 2 minutos, el EIR-32 enviará una señal de restauración de manipulación al panel de control.

_\\<NOTE>_

-   -   Cualquier movimiento del disparador IR borrará el evento/condición de enmascaramiento actualmente detectado. Se debe detectar un evento de enmascaramiento y durar 2 minutos para que se transmita el informe de apertura por manipulación.
-   _**Tabla de posiciones del interruptor DIP**_

La función de cada interruptor DIP se enumera en la siguiente tabla. El interruptor DIP está encendido o apagado. La posición superior indica ENCENDIDO y la posición inferior indica APAGADO.

|   | ADEREZO      |   |         | Posición |                                             |                                        | Función |   |   |
| - | ------------ | - | ------- | -------- | ------------------------------------------- | -------------------------------------- | ------- | - | - |
|   |              |   |         |          |                                             |                                        |         |   |   |
|   | Interruptor1 |   |         | EN       |                                             | Modo de prueba                         |         |   |   |
|   |              |   | APAGADO |          | Modo normal (predeterminado)                |                                        |         |   |   |
|   |              |   |         |          |                                             |                                        |         |   |   |
|   | interruptor2 |   |         | EN       |                                             | Reservado                              |         |   |   |
|   |              |   | APAGADO |          |                                             |                                        |         |   |   |
|   |              |   |         |          |                                             |                                        |         |   |   |
|   |              |   |         | EN       |                                             | PIR frente a una pared a menos de 10 m |         |   |   |
|   | interruptor3 |   |         | APAGADO  |                                             | PIR frente a un espacio abierto        |         |   |   |
|   |              |   |         |          | (sin pared a menos de 10 m)(predeterminado) |                                        |         |   |   |
|   |              |   |         |          |                                             |                                        |         |   |   |
|   |              |   |         | EN       |                                             | PIR frente al césped (predeterminado)  |         |   |   |
|   | interruptor4 |   |         | APAGADO  |                                             | PIR frente a hormigón/piedra           |         |   |   |
|   |              |   |         | suelo    |                                             |                                        |         |   |   |
|   |              |   |         |          |                                             |                                        |         |   |   |
|   |              |   |         |          |                                             |                                        |         |   |   |

![](<.gitbook/assets/1 (36).png>)

|   |              | ADEREZO |         |              | Nivel de sensibilidad           |                                                       |         |   |   |
| - | ------------ | ------- | ------- | ------------ | ------------------------------- | ----------------------------------------------------- | ------- | - | - |
|   |              |         |         |              |                                 |                                                       |         |   |   |
|   | interruptor5 |         |         | interruptor6 |                                 |                                                       |         |   |   |
|   | EN           |         |         | EN           |                                 | Bajo; Mascota de 60 kg (predeterminado)               |         |   |   |
|   | EN           |         |         | APAGADO      |                                 | Medio; mascota de 35 kilos                            |         |   |   |
|   | APAGADO      |         |         | EN           |                                 | Alto; mascota de 20 kilos                             |         |   |   |
|   | APAGADO      |         |         | APAGADO      |                                 | Reservado                                             |         |   |   |
|   |              |         |         |              |                                 |                                                       |         |   |   |
|   | ADEREZO      |         |         | Posición     |                                 |                                                       | Función |   |   |
|   | interruptor7 |         |         | EN           |                                 | Habilitar doble golpe (predeterminado)                |         |   |   |
|   |              |         | APAGADO |              | Deshabilitar doble golpe        |                                                       |         |   |   |
|   |              |         |         |              |                                 |                                                       |         |   |   |
|   | interruptor8 |         |         | EN           |                                 | Habilitación de inmunidad a mascotas (predeterminado) |         |   |   |
|   |              |         | APAGADO |              | Desactivación inmune a mascotas |                                                       |         |   |   |
|   |              |         |         |              |                                 |                                                       |         |   |   |

![](<.gitbook/assets/2 (42).png>)

EN

![](<.gitbook/assets/3 (40).png>)

APAGADO

_**\\<NOTE>**_

-   Después de cambiar la configuración del interruptor DIP, vuelva a encender el EIR-32 para que funcione con las nuevas configuraciones del interruptor DIP.

2

-   _**Protección contra manipulación**_
    -   EIR-32 está protegido por un interruptor de manipulación que se comprime cuando se engancha al soporte de montaje.
    -   Siempre que se retire el sensor de movimiento de la placa de montaje, se activará el interruptor de manipulación.
    -   Cuando el sensor de movimiento se retira a la fuerza de la ubicación de montaje, el área de separación en la placa de montaje se desprenderá, lo que también permitirá que se active el interruptor de manipulación.
    -   El sensor de movimiento enviará una señal de apertura antisabotaje para recordarle al usuario la condición cada vez que se active el interruptor antisabotaje.
-   _**Primeros pasos: aprender el sensor de movimiento en el panel de control**_
    -   Afloje los tornillos de fijación y retire el conjunto de la cubierta.
    -   Según sus necesidades, configure el interruptor de sensibilidad como se muestra en_Tabla de posiciones del interruptor DIP_.
    -   Inserte dos baterías de litio AAL91 en el portapilas teniendo cuidado de conectar la polaridad correctamente.
    -   El indicador LED parpadeará durante 60 segundos. El sensor de movimiento se está calentando. Durante el período de calentamiento, el sensor de movimiento no se activa. Se recomienda que se mantenga alejado del área de detección durante este tiempo. Una vez finalizado el período de calentamiento, el LED se atenúa y el sensor de movimiento está listo para funcionar.
    -   Coloque el Panel de control en modo de aprendizaje; consulte el manual del Panel de control para obtener más detalles.
    -   Presione el botón Prueba una vez. El indicador LED parpadeará tres veces.
    -   Si el Panel de Control recibe la señal, mostrará la información correspondiente. Consulte el manual del Panel de control para completar el proceso de aprendizaje. (Para ciertos modelos de panel de control, el sensor de movimiento se puede aprender como un PIR normal con atributos programables y, por lo tanto, el panel de control informará cuando se active una alarma).
    -   Una vez que se haya aprendido el sensor de movimiento, coloque el panel de control en modo de prueba de recorrido. Mantenga el sensor de movimiento en la ubicación deseada y presione el botón Probar para confirmar que esta ubicación está dentro del rango de señal del panel de control.
    -   Cuando esté satisfecho de que el sensor de movimiento funciona en la ubicación elegida, puede continuar con la instalación.

_\\<NOTE>_

-   -   -   **Prueba de caminata**Se debe realizar una prueba para confirmar el funcionamiento y la cobertura adecuados del sensor de movimiento.
        -   Cuando aprenda el sensor de movimiento o realice una prueba de caminata, evite obstruir el detector antienmascaramiento con la mano; de lo contrario, la señal de apertura se transmitirá al panel de control si la condición de enmascaramiento dura 2 minutos.
-   _**Método de montaje e instalación**_
    -   **Montaje con placa de montaje:**
        -   -   El sensor de movimiento está diseñado para montarse en una superficie plana o en una esquina con los tornillos y tacos de fijación incluidos.
            -   La placa de montaje proporcionada tiene orificios ciegos, donde el plástico es más delgado y se puede romper para realizar el montaje. Dos orificios ciegos son para fijación en superficie y cuatro orificios ciegos para fijación en esquina, como se muestra en la imagen.
            -   Para montar el EIR-32 con soporte de montaje:
                1.  Utilice la placa de montaje como plantilla para perforar agujeros en la pared para los enchufes.
                2.  Introduzca los tacos y fije la placa de montaje a la pared con los tornillos.
                3.  Monte el EIR-32 con los ganchos de la placa de montaje asegurados en la cubierta posterior del EIR-32 y luego empuje hacia abajo hasta que escuche un clic para bloquear el gancho.
                4.  Inserte la pantalla protectora (primero se debe retirar la película protectora de ambos lados).

![](<.gitbook/assets/4 (26).jpeg>)![](<.gitbook/assets/5 (34).png>)

3

-   **Montaje con placa de montaje y soporte giratorio (Opcional):**
    -   Se proporciona un soporte giratorio como opción de montaje fácil de usar.**(artículo opcional, se vende por separado)**. Se compone de una base para fijar a superficie y una bola giratoria para fijar a placa de montaje y EIR-32.

![](<.gitbook/assets/6 (23).jpeg>)

-   Con el soporte giratorio, el EIR-32 se puede girar horizontalmente para proporcionar una cobertura óptima.

Para fijar el soporte giratorio a la pared se suministra un destornillador especial con punta reversible de doble cara y tres tornillos con cabeza de estrella.

![](<.gitbook/assets/7 (18).png>)

Utilice el destornillador proporcionado para apretar o aflojar los tornillos con casquillo de estrella.

![](<.gitbook/assets/8 (21).png>)

-   Para montar el EIR-32 con placa de montaje y soporte giratorio:
    1.  Fije el soporte giratorio a la pared con los tornillos suministrados.
    2.  Fije la placa de montaje en la bola giratoria con el tornillo de fijación asegurado a través del orificio de diseño infalible.
    3.  Monte el EIR-32 con los ganchos de la placa de montaje asegurados en la cubierta posterior del EIR-32 y luego empuje hacia abajo hasta que escuche un clic para bloquear el gancho.
    4.  Inserte la pantalla protectora (primero se debe retirar la película protectora de ambos lados).

![](<.gitbook/assets/9 (20).png>)

4

1.  Gire la bola giratoria horizontalmente para ajustar el ángulo de detección del EIR-32. (Cuando el tornillo de ajuste del ángulo está medio aflojado, la bola giratoria aún se puede girar).
2.  Cuando se gira el EIR-32 a una posición con la cobertura de detección deseada, puede bloquear la posición apretando firmemente el tornillo de ajuste del ángulo.

![](<.gitbook/assets/10 (10).jpeg>)

_\\<NOTE>_

-   -   Después de montar el EIR-32, si el panel de control muestra el estado de falla de manipulación del dispositivo, asegúrese de que el detector antienmascaramiento no esté obstruido por ningún objeto y espere dos minutos para ver si se borra el estado de apertura de manipulación. Si el estado de apertura por manipulación persiste después de dos minutos, retire el EIR-32 de la ubicación de montaje y verifique si el interruptor contra manipulación está comprimido correctamente contra la placa de montaje.
-   _**Recomendaciones de instalación**_

**Se recomienda instalar el sensor de movimiento en las siguientes ubicaciones:**

![](<.gitbook/assets/11 (14).png>)

-   A una altura de 2 metros (medida desde la parte inferior del sensor de movimiento) sobre el suelo para un mejor rendimiento.
-   En una esquina para la vista más amplia.
-   Donde un intruso normalmente se movería a través del campo de visión del sensor de movimiento.
-   En una superficie o en un rincón donde los animales sean inaccesibles.
-   El sensor de movimiento tiene un rango de detección de 10 m cuando se monta a una altura de 2 metros sobre el suelo.

**Limitaciones:**

-   No exponga completamente el sensor de movimiento a la luz solar directa.
-   Evite grandes obstáculos en el área de detección.
-   No lo acerque a fuentes de calor como incendios y calderas, ni lo instale encima de radiadores.
-   Nunca intente desmontar o modificar la unidad.
-   Instale el sensor de movimiento hacia arriba. No lo incline.

![](<.gitbook/assets/12 (11).jpeg>)

-   No instale el sensor de movimiento donde haya objetos movidos por el viento, como árboles y ropa, que puedan bloquear el campo de visión del sensor de movimiento.

![](<.gitbook/assets/13 (11).jpeg>)

5

-   Retire todas las superficies que reflejen la luz del área de detección, así como los charcos de agua.

![](<.gitbook/assets/14 (12).jpeg>)

-   Evite apuntar a la ruta del flujo de aire de entrada o salida de la unidad exterior.

![](<.gitbook/assets/15 (9).jpeg>)

_\\<IMPORTANT NOTE>_

-   Ajuste los interruptores DIP según la ubicación de instalación del sensor de movimiento para un rendimiento ideal. Si la configuración del interruptor DIP no coincide con el entorno de instalación, el rendimiento del sensor de movimiento se verá afectado y puede causar falsas alarmas o incapacidad para detectar movimiento.
-   El sensor de movimiento detecta diferencias entre el objeto en movimiento y el fondo. Si el objeto está estacionario (es decir, sin moverse), el sensor de movimiento no puede detectarlo.
-   El sensor de movimiento tiene una característica direccional y es más eficaz para detectar intrusos que se mueven a través del campo de detección. Es menos sensible para detectar movimiento directamente hacia el sensor de movimiento.
-   Para obtener el mejor rendimiento, recuerde ajustar la altura de montaje del sensor de movimiento con respecto a la altura de la mascota más alta de la casa. Los perros más altos requieren que el sensor de movimiento esté montado más alto para que admitan mascotas.
-   El sensor de movimiento tiene un punto ciego de aproximadamente 1 metro debajo cuando se monta a una altura de 2 metros. El área del punto ciego aumentará si monta el sensor de movimiento a más de 2 M y se reducirá si monta a menos de 2 M.
-   A menos que sea necesario, sugerimos mantener la ubicación de montaje del sensor de movimiento a 2 m para un rendimiento óptimo. Si cambia la altura de montaje, realice una prueba de detección para asegurarse de que el sensor de movimiento pueda detectar intrusos normalmente a la altura deseada.

6
