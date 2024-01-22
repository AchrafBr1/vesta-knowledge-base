# VESTA 027

**Convertidor de cableado a inalámbrico (HWC-1B)**

HWC-1B es un convertidor de cableado a inalámbrico que convierte sensores cableados existentes de sistemas de alarma de seguridad en tecnología inalámbrica. HWC-1B se puede instalar en una ubicación preferible donde pueda enviar informes al Panel de control fácilmente sin preocuparse más por los escenarios cableados tradicionales. Para lograr esto, los sensores cableados existentes se conectan a las zonas de entrada del HWC-1B, por lo que no es necesario reemplazar los dispositivos cableados con transmisores individuales.

El convertidor fácil de usar consta de 9 zonas de entrada, cada una de las cuales se puede conectar al sensor de seguridad existente mediante cableado, p. Sensor PIR, contacto de puerta, detector de humo, sensor de agua, sensor de incendio, sensor de CO, detector de gas, detector de calor y detector de rotura de cristales, etc. Esto ahorra costes de instalación y proporciona a hogares y empresas mayor comodidad y funcionalidad eficiente para los usuarios. .

-   **Identificación de piezas**

1.  **Indicador LED**
    -   **LED1 de alimentación de entrada (verde/rojo):**

![](<.gitbook/assets/0 (29).jpeg>)

LED verde encendido: la alimentación de CA está conectada.

LED rojo encendido: fallo de alimentación de CA.

-   **LED de estado 2 (amarillo):**

ON: Batería baja o desconexión.

Flash: Fallo en la carga de la batería.

-   **LED3 de transmisión (verde):**

El LED verde parpadea cuando se transmite cualquier señal.

-   **LED4 de calibración de entrada (verde):**

ON: Al presionar y mantener presionado el botón de calibración durante 2 segundos.

ON: Cuando la calibración de entrada es exitosa.

-   **Requiere calibración LED5 (rojo):**

Flash: cuando la entrada necesita calibrarse.

ENCENDIDO: Al presionar y mantener presionado el botón de calibración durante

-   1.  segundos.

1.  **Botón de prueba/aprendizaje (SW11).**
2.  **Botón de calibración (SW12)**
3.  **Botón de reinicio (SW1)**
4.  **Terminal:**Z1~Zonas de entrada Z9.

(Ver_**Diagrama de aplicación**_para más detalles.)

1.  **Botón de interruptor de manipulación (SW20).**
2.  **Terminal de alimentación**(Ver_**Diagrama de aplicación**_para más detalles.)

![](<.gitbook/assets/1 (24).jpeg>)

**+12V/TIERRA:**Conecte a la fuente de alimentación.

**12VAUX/TIERRA:**Proporciona 12 V CC a 100 mA para alimentar los dispositivos conectados.

1.  **Paquete de baterias recargables**
2.  **Conector de dos pines**

El conector de dos clavijas se utiliza para conectar el paquete de baterías recargables.

1.  **Orificios de montaje**

-   **Fuente de alimentación**

1

**Aplicación del adaptador de corriente:**

-   Encienda el HWC-1B conectando el adaptador CA-CC de 12 V de dos cables al terminal +12 V/GND.
-   Cuando se interrumpe y se restablece el suministro de energía, el HWC-1B transmitirá una falla de CA y restaurará la señal respectivamente.

**Batería recargable:**

-   Un 1,2 V\*8 baterías recargables AAA Ni-MH de 750 mAh están instaladas dentro del HWC-1B para servir como respaldo en caso de un corte de energía. El paquete de baterías no viene conectado de fábrica. Conecte la batería si desea utilizarla como energía de respaldo.
-   HWC-1B cargará la batería recargable automáticamente cuando se suministre energía y la batería recargable esté conectada. Cuando se interrumpe el suministro de energía, el HWC-1B pasará a utilizar la batería recargable y continuará funcionando.
-   Cuando la batería recargable tiene poca energía, el HWC-1B transmitirá una señal de batería baja. Cuando la batería se haya cargado, el HWC-1B transmitirá la señal de restauración de la batería.

**Salida de potencia:**

-   -   HWC-1B puede suministrar energía de 12 V y 100 mA a los dispositivos conectados a través del terminal de alimentación.
-   **Paquete de baterias recargables**
    -   HWC-1B cargará la batería automáticamente cuando se conecte la alimentación. Cuando se interrumpe el suministro de energía, el HWC-1B pasará a utilizar la batería recargable y continuará funcionando.
-   **Diagrama de aplicación**

![](<.gitbook/assets/2 (22).jpeg>)

La Terminal (Z1~Zonas de entrada Z9) permiten conectar sensores cableados existentes al convertidor HWC-1B:

-   Cada zona de entrada solo está disponible para un sensor cableado.
-   Es imprescindible que todas las zonas de entrada que se utilicen tengan una resistencia EOL (con un valor de 1k a 10k ohmios).
-   Mantenga las zonas de instalación existentes que ya tienen resistencia EOL (con un valor de 1 k a 10 k ohmios).
-   Para un bucle NC sin resistencia EOL, agregue una en serie con el bucle.
-   Para un bucle NO sin resistencia EOL, agregue una en paralelo (a través) del bucle. Debe estar ubicado al final del bucle, lejos del Panel de control.

_\\<NOTE>_

-   -   Si desea cambiar los cables en la zona de entrada, primero apague el HWC-1B, luego cambie la ubicación de entrada de los cables como prefiera y encienda el HWC-1B nuevamente. Presione el botón de calibración para finalizar el proceso de cambio.
-   **(SW12) Botón de calibración**

Después de cablear los sensores existentes al HWC-1B, inicie el proceso de calibración que le permite al HWC-1B saber qué zona estará activa y qué resistencias EOL se utilizarán. Cualquier zona abierta o no utilizada no será reconocida ni reportada al Panel de Control.

-   Asegúrese de que todas las zonas estén bien conectadas.
-   Mantenga presionado el botón Calibración**(Su12)**durante 2 segundos. Tanto el LED4 (verde) como el LED5 (rojo) se encenderán.
-   Cuando se complete la calibración, el LED5 (rojo) se apagará. El LED4 (verde) permanecerá encendido para indicar que la calibración se realizó correctamente.
-   Cuando falla la calibración, el LED4 (verde) se apagará y el LED5 (rojo) parpadeará para indicar un error.

_\\<NOTE>_

-   La Zona 1 debe estar cableada para que HWC-1B funcione normalmente y utilice la función de calibración.

2

-   **(SW11) Aprendizaje / Prueba de caminata**
    -   Asegúrese de que los dispositivos estén conectados y calibrados correctamente antes de continuar con el aprendizaje.
    -   Consulte el manual de su panel de control para poner el panel en modo de aprendizaje.
    -   Presione el botón Probar/Aprender**SW11**para enviar código de aprendizaje al Panel de control.
    -   Consulte el manual de funcionamiento de su panel de control para completar el proceso de aprendizaje.
    -   El botón Prueba/Aprendizaje también se utiliza para la función Prueba de caminata. Coloque el panel en modo de prueba de caminata y presione el botón para verificar el alcance y la intensidad de la señal.

![](<.gitbook/assets/3 (36).png>)

_\\<NOTE>_

Número de zona

-   -   Cuando HWC-1B se aprende en el sistema de alarma, cada zona activa será reconocida como tipo de dispositivo de contacto de puerta. Los usuarios pueden editar el nombre del dispositivo y seleccionar el tipo de alarma para cada sensor conectado en la página Editar dispositivo.
    -   Cada zona de entrada aprendida enviará un código RF individual al Panel de control. El número de zona se indica con el último dígito del ID del dispositivo.
    -   El propio estado del HWC-1B (batería baja, manipulación, etc.) se transmite a través de la Zona 1.
-   **Supervisión**
    -   El convertidor transmitirá automáticamente señales de supervisión periódicamente al panel de control en intervalos aleatorios de 30 a 50 minutos en el modo de funcionamiento normal.
    -   If the Control Panel has not received the signal from the Converter for a preset period time, the Control Panel will indicate that particular Converter is experiencing an out-of-signal problem.
-   **(SW20) Interruptor de manipulación**
    -   Está diseñado para proteger contra la apertura no autorizada de la cubierta. Cuando se activa el interruptor de manipulación, el HWC-1B emitirá una señal de apertura de manipulación al panel de control para informar.
-   **Procedimientos de instalación**

El HWC-1B se puede montar en la pared con el soporte de montaje proporcionado o con los orificios de montaje preperforados. Siga los pasos a continuación para continuar.

1.  **Con soporte de montaje:**
2.  Saque el soporte de montaje proporcionado.
3.  Utilice los 2 orificios de montaje centrales del soporte de montaje para marcar posiciones en la pared.
4.  Taladre orificios en el lugar de montaje e instale tacos de pared si es necesario.
5.  Instale los tornillos de montaje en la ubicación marcada como se muestra a continuación.

![](<.gitbook/assets/4 (22).jpeg>)

3

1.  Conecte el HWC-1B al soporte como se muestra a continuación.

![](<.gitbook/assets/5 (15).jpeg>)

1.  Sostenga el HWC-1B y empújelo suavemente hacia abajo como se muestra a continuación.

![](<.gitbook/assets/6 (19).jpeg>)

**B: Con orificios de montaje preperforados:**

-   1.  Presione hacia abajo los orificios preperforados en los bordes del HWC-1B y levante suavemente la cubierta frontal al mismo tiempo.
    2.  Utilice los 4 orificios de montaje alrededor del borde de la cubierta posterior para marcar las posiciones de los orificios en la pared.
    3.  Taladre agujeros en el lugar de montaje e instale tacos de pared.
    4.  Atornille la cubierta trasera en la ubicación marcada.
    5.  Vuelva a colocar la cubierta frontal. La instalación está completa.
-   **Restablecimiento de fábrica**

El restablecimiento de fábrica borrará el HWC-1B de toda la información de la zona calibrada.

1.  Desconecte tanto la fuente de alimentación como la batería.
2.  Mantenga presionado el**Botón de prueba/aprendizaje (SW11)**, mientras mantiene presionado el botón, aplique energía para encender el HWC-1B al mismo tiempo.
3.  Continúe presionando el botón durante 3 segundos.
4.  LED 1~3 se encenderá. Suelte el botón cuando los LED se enciendan. El restablecimiento de fábrica está completo.

4
