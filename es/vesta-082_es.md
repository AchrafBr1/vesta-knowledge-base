# VESTA 082

**WADC-1****Contacto de puerta de prevención de deambulación**

WADC-1 es un contacto de puerta que combina sensores PIR para monitorear las aperturas de la puerta y detectar los movimientos a su alrededor. Diseñado especialmente para quienes padecen demencia y son propensos a deambular, WADC-1 transmitirá señales al panel de control para notificar al cuidador cuando el usuario abre la puerta, moviéndose desde el interior de la habitación hacia el exterior.

WADC-1 tiene dos niveles de sensibilidad ajustables que ofrecen aún más comodidad de uso. Cuando se monta a una altura de 2,1~A 2,3 metros del suelo, cada uno de los sensores PIR tiene un patrón de cobertura de 3 x 1 metros a nivel del suelo.

![](<.gitbook/assets/0 (37).png>)

-   _**Identificar las piezas**_

**1. Indicador LED (rojo)**

El indicador LED se utiliza para indicar el estado del sensor PIR Zona 2 (área de apertura de puerta) y el contacto de la puerta.

**2. Indicador LED (verde)**

El indicador LED se utiliza para indicar el estado del sensor PIR Zona 1 y el contacto de la puerta.

**3. Botón de prueba**

Presione el botón Prueba para transmitir el código de aprendizaje o ingresar al modo de prueba durante 3 minutos.

**4. Interruptor de puente aumentador de sensibilidad (JP3)**

![](<.gitbook/assets/1 (38).jpeg>)

**Puente encendido**

![](<.gitbook/assets/2 (51).png>)

Se inserta el enlace del puente, conectando los dos pines.

**Puente apagado**

![](<.gitbook/assets/3 (30).jpeg>)

El enlace del puente se elimina o "**estacionado**”en un alfiler.

-   -   Si el puente está APAGADO, la sensibilidad de detección de los PIR está en el nivel normal. (**Predeterminado de fábrica**)
    -   Si el puente está activado, la sensibilidad de detección de los PIR está configurada en alta.

1.  **Interruptor de puente de configuración de sensor único/múltiple (JP4)**

![](<.gitbook/assets/4 (33).jpeg>)

**Puente encendido**

![](<.gitbook/assets/5 (42).png>)

Se inserta el enlace del puente, conectando los dos pines.

**Puente apagado**

![](<.gitbook/assets/6 (29).jpeg>)

El enlace del puente se elimina o "**estacionado**”en un alfiler.

-   -   Si el puente está APAGADO, WADC-1 será reconocido como 3 sensores (sensor PIR de zona 1, sensor PIR de zona 2 y contacto de puerta).
    -   Si el puente está activado, WADC-1 será reconocido como 1 sensor (WADC). (**Predeterminado de fábrica**)

1.  **Interruptor de puente de dirección de apertura de puerta (JP5)**

![](<.gitbook/assets/7 (23).png>)

**Puente encendido**

Se inserta el enlace del puente, conectando los dos pines.

Asegúrese de que JP5 esté configurado en ON para que la configuración sea efectiva.

**Puente apagado**

![](<.gitbook/assets/8 (27).png>)

El enlace del puente se elimina o "**estacionado**”en un alfiler.

-   -   Coloque el puente en APAGADO si la puerta donde está instalado el imán está diseñada para abrirse hacia afuera. (**Predeterminado de fábrica**)
    -   Coloque el puente en ON si la puerta donde está instalado el imán está diseñada para abrirse hacia adentro.

1.  **Compartimiento de la batería**
2.  **Manibela de encendido**

Cuando WADC-1 esté montado en su lugar, el interruptor de manipulación se activará cuando se abra la cubierta o cuando se retire el dispositivo de la superficie de montaje.

1

-   1.  **Imán**
-   _**Función de supervisión**_
    -   -   El sensor PIR Zona 1, el sensor PIR Zona 2 y el contacto de puerta transmitirán su señal de supervisión por separado al panel de control cada 30 a 50 minutos.
        -   Si el Panel de control no recibe las señales de supervisión transmitidas desde un determinado dispositivo durante un tiempo preestablecido, se generará un mensaje de falla "Fuera de servicio".
-   _**Función de aumento de sensibilidad (JP3)**_

![](<.gitbook/assets/9 (13).jpeg>)![](<.gitbook/assets/10 (14).jpeg>)

Puede utilizar la función de aumento de sensibilidad para aumentar la sensibilidad de detección de los sensores PIR. Para aumentar la sensibilidad de detección, conecte el interruptor de puente (JP3) para configurarlo en el**EN**posición. Para mantener la sensibilidad de detección normal, desconecte el interruptor de puente (JP3) para configurarlo en el**APAGADO**posición (valor predeterminado de fábrica).

![](<.gitbook/assets/11 (17).jpeg>)

-   _**Función de configuración de sensor único/múltiple (JP4)**_

Puede utilizar el interruptor de puente (JP4) para decidir si reconoce el dispositivo como un sensor único o como sensores múltiples después de que el dispositivo se haya aprendido en el Panel de control. Si el interruptor de puente (JP4) está configurado en ON, WADC-1 será reconocido como 1 sensor. Siempre que se detecte un movimiento, el LED parpadeará. Si el interruptor de puente está configurado en APAGADO, WADC-1 será reconocido como 3 sensores separados (sensor PIR de zona 1, sensor PIR de zona 2 y contacto de puerta).

![](<.gitbook/assets/12 (23).png>)

_\\<NOTE>_

-   -   Siempre antes de cambiar la configuración de JP4, asegúrese de quitar la batería primero. Presione el botón de prueba varias veces, cambie a la configuración del puente deseada y vuelva a insertar la batería. Los cambios serán efectivos después de que se proporcione energía de la batería al dispositivo.
-   _**Detección de dirección de puerta abierta (JP5)**_

![](<.gitbook/assets/13 (16).jpeg>)

Puede utilizar el interruptor de puente para configurar la dirección de apertura de su puerta. Para que la configuración sea efectiva, asegúrese de configurar JP4 en ON primero. Si la puerta donde está instalado el imán está diseñada para abrirse hacia afuera, coloque el interruptor de puente (JP5) en APAGADO.

Si la puerta está diseñada para abrirse hacia adentro, coloque el interruptor de puente (JP5) en ON.

![](<.gitbook/assets/14 (17).jpeg>)

-   _**Modo de prueba**_
    -   En el modo normal, al presionar el botón de prueba se transmitirá una señal de prueba al panel de control para realizar una prueba de alcance de radio y el WADC-1 ingresará al modo de prueba durante 3 minutos. Saldrá del modo de prueba automáticamente después de 3 minutos y volverá al modo normal.
    -   En modo de prueba, el indicador LED verde o rojo parpadeará cada vez que se detecte un movimiento en PIR Zona 1 o PIR Zona 2 (área de apertura de puerta); Tanto el LED azul como el LED rojo parpadearán cuando se active el contacto de la puerta.
    -   Puede verificar el rango de detección de los sensores PIR Zona 1 y Zona 2 activando los sensores.
-   _**Indicador LED**_

![](<.gitbook/assets/15 (14).jpeg>)

En el modo de funcionamiento normal, los indicadores LED parpadearán en las siguientes situaciones:

-   -   Cuando se detecta movimiento en PIR Zona 1 o PIR Zona 2 (área de apertura de puerta) en condiciones de falla (batería baja, manipulación abierta) o en modo de prueba, el LED verde o el LED rojo parpadearán.
    -   Cuando el contacto de la puerta se activa en condiciones de falla (batería baja, apertura por manipulación) o en modo de prueba, tanto el LED verde como el LED rojo parpadearán.
    -   Cuando se abre la cubierta y se activa el interruptor de manipulación, tanto el LED verde como el LED rojo parpadearán.
    -   Cuando se presiona el botón de prueba en condiciones de falla (batería baja, manipulación abierta), tanto el LED verde como el LED rojo parpadearán.
    -   Cuando la batería se agota, WADC-1 detendrá todas las funciones, tanto el LED verde como el LED rojo parpadearán cada 4 segundos.
-   _**Batería**_
    -   WADC-1 utiliza una batería de litio CR123 de 3V como fuente de energía:
    -   WADC-1 presenta una función de detección de batería baja. Si se detecta un voltaje bajo de la batería, se enviará una señal de batería baja al Panel de control junto con transmisiones de señal regulares para que el Panel de control muestre el estado correspondiente.
    -   Al cambiar la batería, después de retirar la batería vieja, presione el interruptor de manipulación dos veces para descargarla completamente antes de insertar una batería nueva.
-   _**Empezando**_
    -   Saque el aislante de la batería para activar la batería.
    -   Coloque el Panel de control en modo de aprendizaje; consulte el manual del Panel de control para obtener más detalles.
    -   Presione el botón de prueba en el costado para enviar un código de aprendizaje al Panel de control.
    -   Cuando JP4 está activado, WADC-1 será reconocido como**1 sensor**(WADC) y ocupa 1 zona en el Panel de control después de que se aprende en el Panel de control.
    -   Cuando JP4 está en OFF, WADC-1 será reconocido como**3 sensores separados**(sensor PIR Zona 1, sensor PIR Zona 2 y contacto de puerta) y ocupar**3 zonas**en el Panel de control después de que se haya aprendido en el Panel de control.
    -   Consulte el manual del Panel de control para completar el proceso de aprendizaje.
-   _**Prueba de caminata**_
    -   Después de aprender WADC-1, coloque el Panel de control en "**Prueba de caminata**", mantenga presionado WADC-1 en la ubicación deseada y presione el botón Prueba para confirmar si esta ubicación está dentro del alcance de la señal del Panel de control; consulte Control

![](<.gitbook/assets/16 (12).jpeg>)![](<.gitbook/assets/17 (11).jpeg>)![](<.gitbook/assets/18 (9).jpeg>)

2

Manual del panel para completar la prueba de caminata.

-   -   Cuando esté satisfecho de que WADC-1 funciona en la ubicación elegida, puede proceder al montaje.
-   _**Guía de instalación**_
    -   WADC-1 debe instalarse en el marco de la puerta, justo encima de la puerta, para mirar hacia abajo y monitorear los movimientos alrededor de la puerta.
    -   El imán debe instalarse en la puerta en el lado opuesto de la ubicación del interruptor magnético interno del contacto de la puerta.
    -   El WADC-1 tiene 2 marcas de nervaduras en un lado (consulte la figura), que marcan la ubicación del interruptor magnético interno. El imán debe alinearse con el lado de la marca de la nervadura del WADC-1 como se muestra en la figura siguiente.

![](<.gitbook/assets/19 (6).jpeg>)![](<.gitbook/assets/20 (8).jpeg>)

-   Si la puerta donde está instalado el imán está diseñada para abrirse hacia afuera, configure**JP5 a APAGADO**(**Asegúrese de que JP4 esté configurado en ON para que la configuración sea efectiva**). La distancia entre el WADC-1 y el imán no debe ser superior a 5 mm con la puerta cerrada.
-   Si la puerta donde está instalado el imán está diseñada para abrirse hacia adentro, configure**JP5 a ENCENDIDO**(**Asegúrese de que JP4 esté configurado en ON para que la configuración sea efectiva**). La distancia entre el WADC-1 y el imán no debe ser superior a 5 mm con la puerta cerrada.

3

1.  La superficie de montaje debe estar limpia, seca y lisa. Limpie la superficie de montaje con un desengrasante adecuado si

necesario.

1.  Retire el revestimiento de un lado de la cinta adhesiva de doble cara. Aplique la cinta adhesiva en la parte posterior del dispositivo y presione firmemente durante 30 segundos para asegurar una buena adherencia.
    1.  Retire el otro revestimiento y presione firmemente el contacto de la puerta en la ubicación deseada durante 30 segundos.

_\\<NOTE>_

-   -   -   No utilice la instalación de cinta adhesiva sobre una superficie con pintura descascarada o agrietada, o sobre una superficie rugosa.
        -   No vuelva a aplicar la cinta adhesiva 3M. No se puede reutilizar
-   **Montaje con tornillos**

La base tiene dos orificios ciegos, donde el plástico es más delgado, para fines de montaje. (consulte la figura de la derecha)

Para montar el contacto de puerta:

-   1.  Retire la cubierta desatornillando el tornillo de seguridad de la cubierta con un destornillador Philips.

1.  Rompe los nocauts en la base.
2.  Usando los agujeros como plantilla, taladre ambos agujeros.

IV. Inserte tacos de pared si lo fija en yeso o ladrillo.

1.  Atornille la base al taco de pared con un destornillador Philips.

VI. Fije la cubierta a la base y apriete el tornillo de seguridad de la cubierta.

-   -   Coloque el imán en la puerta utilizando el pequeño trozo de cinta adhesiva de doble cara. El imán debe alinearse con el lado de la marca de la nervadura del contacto de la puerta. La instalación ya está completa.
-   _**Recomendaciones de instalación**_
    -   WADC-1 debe instalarse en la parte del marco de la puerta que está justo encima de la puerta para mirar hacia abajo y monitorear los movimientos.
    -   Cuando se monta a una altura de 2,1~2,3 metros y mirando hacia abajo, los sensores PIR (PIR Zona 1 y Zona 2) tienen cada uno un patrón de cobertura de 3 x 1 metros a nivel del suelo.

4
