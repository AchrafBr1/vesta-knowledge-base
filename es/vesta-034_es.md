# VESTA 034

**Manual del usuario del sensor de inclinación del garaje (Gdts-1)**

El sensor de inclinación del garaje monitorea la inclinación bidireccional de la puerta basculante del garaje. El sensor de inclinación del garaje se fija al marco del dispositivo monitoreado. Cuando la puerta está abierta y la superficie detectada está inclinada menos o igual a 35°(+-10) grados, o cuando la puerta está cerrada y la superficie detectada está inclinada más o igual a 55°(+-10) grados , el sensor de inclinación del garaje transmitirá una señal de alarma al panel de control. El dispositivo también tiene la capacidad de comunicar problemas de señal junto con situaciones de batería baja.

El diseño del sensor de inclinación del garaje consta de una cubierta y una base. La cubierta contiene todos los componentes electrónicos y la base proporciona un medio para fijar el dispositivo. Un interruptor antisabotaje de PCB incluido proporciona protección contra manipulación contra la apertura y/o extracción no autorizada del dispositivo.

**Identificación de piezas**

![](<.gitbook/assets/0 (32).jpeg>)

1.  **Botón de prueba/indicador LED**

**Botón de prueba:**

-   -   Presione el botón Prueba para transmitir un código de aprendizaje.
    -   Presione el botón Prueba para ingresar al modo de prueba durante 3 minutos.

**Indicador LED:**

-   -   El LED parpadeará 3 veces cuando esté transmitiendo un código de aprendizaje.
    -   El LED se iluminará cada vez que el dispositivo se active en el modo de prueba.
    -   El LED se iluminará cada vez que se active el interruptor de manipulación.
    -   (Puerta abierta) Cuando experimente una falla en el dispositivo o esté en modo de prueba, el LED parpadeará 6 veces.
    -   (Puerta cerrada) Cuando experimente una falla en el dispositivo o esté en modo de prueba, el LED parpadeará 6 veces. Después de 10 segundos, el LED parpadeará 3 veces.

1.  **Orificios de montaje**
    -   Se utiliza para fijar y atornillar el sensor de inclinación del garaje directamente en la parte superior de la puerta del garaje.
2.  **Manibela de encendido**
    -   Cuando el sensor de inclinación del garaje esté montado, el interruptor de manipulación quedará completamente comprimido contra la pared. Cuando se abre la cubierta del dispositivo o cuando se retira de la superficie montada, se activará el interruptor de manipulación. El LED parpadeará 6 veces y enviará una señal de apertura por manipulación para notificar a los usuarios de esta condición.
3.  **Aislador de batería**
4.  **Compartimiento de la batería**

**Características**

-   _**Indicador LED**_
    -   En el modo de funcionamiento normal, el LED se iluminará cuando se active el sensor de inclinación del garaje (dispositivo abierto o cerrado).
    -   Cuando se abre la cubierta del dispositivo o cuando se activa el interruptor de manipulación, el LED se iluminará.
    -   Cuando el sensor de inclinación del garaje está en modo de prueba, el LED se iluminará cada vez que se active.
    -   El LED se iluminará cuando el sensor de inclinación del garaje se active en estado de batería baja. Cuando la batería se agota, el sensor de inclinación del garaje detendrá todas sus funciones y el LED parpadeará cada 4 segundos.

1

-   _**Batería**_
    -   El sensor de inclinación del garaje funciona con una batería de litio CR123 de 3 V. Tenga en cuenta:**SIEMPRE**reemplace la batería con una del tamaño y voltaje correctos.
    -   El sensor de inclinación del garaje puede detectar condiciones de batería baja. Cuando el voltaje de la batería es bajo, se enviará una señal de batería baja al panel de control para notificar a los usuarios de esta condición. Cuando la batería se agote, el LED parpadeará cada 4 segundos y el dispositivo dejará de funcionar.
    -   Cuando reemplace una batería nueva, retire primero la batería vieja. Presione el interruptor de manipulación dos veces para descargar completamente antes de insertar una batería nueva.
-   _**Empezando**_
    -   Saque el aislante de la batería para proporcionar energía al dispositivo.
    -   Coloque el panel de control en modo de aprendizaje (consulte el manual de funcionamiento del panel de control para obtener más detalles).
    -   Presione el botón de prueba del sensor de inclinación del garaje para enviar un código de aprendizaje, el LED parpadeará 3 veces.
    -   Consulte el manual de funcionamiento de su panel de control para completar el proceso de aprendizaje.
    -   Una vez que se haya aprendido el sensor de inclinación del garaje, coloque el panel de control en el modo de prueba de recorrido, sostenga el sensor de inclinación del garaje en la ubicación deseada y presione el botón de prueba para transmitir la señal de prueba al panel de control. Si el panel de control está dentro del rango de señal del sensor de inclinación del garaje, el panel mostrará la información del sensor de inclinación del garaje en consecuencia.
    -   Asegúrese de que el sensor de inclinación del garaje esté dentro del alcance de la señal del panel de control antes del proceso de montaje e instalación.
-   _**Modo de prueba**_
    -   El sensor de inclinación del garaje se puede poner en modo de prueba de 3 minutos presionando el botón de prueba (también conocido como indicador LED) en la cubierta frontal.
    -   En el modo de prueba, el LED se iluminará cada vez que se active el sensor de inclinación del garaje.
    -   Para extender el temporizador del modo de prueba por otros 3 minutos, simplemente presione el botón de prueba.
-   _**Tamper Switch**_
    -   El sensor de inclinación del garaje estará protegido por un interruptor de manipulación cuando se monte al ras contra la superficie de montaje. Cuando se retira el dispositivo de la superficie de montaje o cuando se abre la cubierta del dispositivo, se activará su interruptor de manipulación. Luego, el dispositivo enviará una señal de apertura por manipulación al panel de control para notificar a los usuarios de esta condición.
-   _**Señal de supervisión**_
    -   El sensor de inclinación del garaje transmitirá una señal de supervisión al panel de control en intervalos aleatorios de 30 a 50 minutos.
    -   Si el panel de control no recibe ninguna señal de supervisión del sensor de inclinación del garaje durante un período de tiempo preestablecido, se generará un mensaje de falla "Fuera de servicio".

**Instalación**

![](<.gitbook/assets/1 (27).jpeg>)

-   _**Guía de instalación y recomendaciones**_

**Guía:**

-   El sensor de inclinación del garaje debe instalarse en la puerta del garaje. Cuando la puerta está abierta y la superficie detectada está inclinada menos o igual a 35°(+-10) grados, o cuando la puerta está cerrada y la superficie detectada está inclinada más o igual a 55°(+-10) grados , el sensor de inclinación del garaje transmitirá una señal de alarma al panel de control.

![](<.gitbook/assets/2 (25).jpeg>)



2

-   El sensor de inclinación del garaje debe montarse en el panel superior de la puerta del garaje, como se muestra a continuación.

![](<.gitbook/assets/3 (23).jpeg>)

**Recomendaciones:**

-   -   El sensor de inclinación del garaje está diseñado para montarse en una puerta basculante de garaje, no para usarse en una puerta enrollable. Monte el detector a una altura de 1,8 metros para un rendimiento óptimo.
    -   El dispositivo se montará verticalmente con el suelo y no tendrá más de +-5 grados cuando esté montado.
    -   Monte el dispositivo sobre una superficie seca y limpia. Asegúrese de que el dispositivo esté montado con el indicador LED en la parte superior.
-   _**Montaje del sensor de inclinación del garaje**_

![](<.gitbook/assets/4 (25).jpeg>)

Hay dos formas de montar el sensor de inclinación del garaje. Asegúrese de que la ubicación esté dentro del alcance de la señal del panel de control y siga los pasos a continuación para continuar:

**Montaje con tornillos:**

-   Encuentre una ubicación adecuada para instalar el sensor de inclinación del garaje. La superficie de montaje debe estar limpia y seca. Limpie a fondo la superficie de montaje si es necesario.
-   Utilice los dos orificios de montaje como plantilla para marcar y perforar los orificios de montaje.
-   Utilice los tacos de pared proporcionados para la instalación de yeso/ladrillo. Atornille el sensor de inclinación del garaje a la pared provista.

enchufes. Asegúrese de que los tacos estén al ras de la pared.

![](<.gitbook/assets/5 (18).jpeg>)

_\\<NOTE>_

-   Utilice este tipo de método de montaje únicamente cuando las puertas del garaje sean más gruesas que los tornillos.

**Montaje adhesivo:**

-   Encuentre una ubicación adecuada para instalar el sensor de inclinación del garaje. La superficie de montaje debe estar limpia y seca. Limpie a fondo la superficie de montaje si es necesario.
-   Retire la cubierta protectora de un lado de la almohadilla adhesiva de doble cara. Aplíquelo en la parte posterior del sensor de inclinación del garaje y presione firmemente durante 30 segundos para garantizar un buen contacto.
-   Retire el otro lado de la cinta adhesiva y presione firmemente el sensor de inclinación del garaje en la ubicación deseada durante otros 30 segundos. Evite aplicar la almohadilla adhesiva sobre superficies irregulares o volver a aplicarla para un rendimiento de detección óptimo.

3
