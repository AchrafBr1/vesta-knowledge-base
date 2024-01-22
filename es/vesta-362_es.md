# VESTA 362

**Sirena interior cableada (SR-35-BUS)**

SR-35-BUS es una sirena interior cableada que se utiliza para indicación de alarma del sistema. Cuando se recibe una señal de alarma desde el panel de control, la sirena interior cableada se activará para llamar la atención. El dispositivo también puede funcionar con el Panel de control para emitir sonidos de retardo de entrada y salida, y también alertarle sobre violaciones de manipulación.

![](<.gitbook/assets/0 (3).jpeg>)

**Identificar las piezas**

![](<.gitbook/assets/1 (4).jpeg>)

1.  **Botón Aprender**
2.  **Interruptor de puente de resistencia terminal**

Cuando la sirena interior cableada esté conectada como el dispositivo BUS más lejano en una línea BUS, configure el puente de resistencia terminal de la sirena interior cableada y el interruptor de puente del primer dispositivo BUS (generalmente el panel híbrido) en ON para que sirva como terminal.

resistencias. Se mejorará la capacidad de comunicación de la línea BUS conectada.

![](<.gitbook/assets/2 (4).png>)

**Puente encendido**

**Puente apagado**

Se inserta el enlace del puente, conectando los dos pines.

El enlace del puente se elimina o "**estacionado**”en un alfiler.

-   -   Si el puente está APAGADO, la capacidad de comunicación está en nivel normal.
    -   Si el puente está activado, se mejora la capacidad de comunicación.

1.  **Terminal de autobus**
2.  **Tornillo de fijación inferior**
3.  **Manibela de encendido**

El interruptor de manipulación se activará cuando se retire la sirena del soporte de montaje.

1.  **Área de separación para cableado de BUS**
2.  **Soporte de montaje**

![](<.gitbook/assets/3 (4).png>)

1

![](<.gitbook/assets/4 (4).jpeg>)**Fuente de alimentación**

-   Cuando el SR-35-BUS está cableado a un panel híbrido, el panel híbrido puede proporcionar una fuente de alimentación de 13,5 V.

![](<.gitbook/assets/5 (1) (1).jpeg>)

**Supervisión**

La sirena interior cableada transmitirá una señal de supervisión cada 20 a 30 segundos en el modo de funcionamiento normal.

Si no se recibe esta señal, el panel de control indicará que la sirena en particular está experimentando un problema de avería.

![](<.gitbook/assets/6 (4).png>)

**Descripción general de funciones**

-   **Memoria de alarma**

Si se activó una alarma en su ausencia y el sistema no se desarmó antes de que expirara la duración de la alarma, la sirena interior cableada hará sonar una alarma breve cuando el sistema esté desarmado para advertir al usuario que se activó una alarma mientras no estaba. Esto sugiere que el intruso todavía podría estar dentro del local.

-   **Duración de la alarma**

Cuando el panel de control activa una alarma, el panel notificará a la sirena interior cableada para que comience a sonar de acuerdo con la duración de la alarma del panel. Cuando expire la duración de la alarma del Panel, el Panel notificará al dispositivo que detenga la alarma.

Si la sirena interior cableada no recibe la señal del panel de control para detener la alarma, sonará durante un máximo de 15 minutos y luego la detendrá.

Por ejemplo:

-   -   Si la duración de la alarma del panel está configurada en más de 15 minutos, después de activarse una alarma, en lugar de esperar a que expire la duración de la alarma del panel, la alarma se detendrá después de 15 minutos.
    -   Si el panel está en modo desarmado y el interruptor de manipulación de la sirena se activa, la sirena interior cableada no activará la alarma ya que el panel está en modo desarmado y activará la alarma durante 15 minutos debido a la activación de manipulación.
-   **Manipulación de sirena**

La sirena interior con cable está protegida contra cualquier intento de abrir la tapa o separar el dispositivo de su superficie de montaje.

Si el dispositivo detecta una condición de manipulación, activará la sirena durante la duración de la alarma programada. Se enviará una señal de manipulación al Panel de control junto con transmisiones de señales regulares para que el Panel de control muestre el estado correspondiente. Si la condición de manipulación continúa, el dispositivo emitirá una serie de cinco pitidos para indicar una falla cada vez que el sistema esté armado o cuando la manipulación esté habilitada.

-   **Indicación de estado de audio**

Mientras se arma/desarma el sistema, se utilizan diferentes métodos para distinguir varios estados para el usuario, como se enumera en la siguiente tabla.

![](<.gitbook/assets/7 (5).png>)![](<.gitbook/assets/8 (5).png>)![](<.gitbook/assets/9 (6).png>)

| **Estado**                          | **Sonido de sirena** |
| ----------------------------------- | -------------------- |
|                                     |                      |
| Armar/Inicio                        | 1 pitido             |
| Desarmar                            | 2 pitidos            |
| Brazo (sabotaje)                    | 5 pitidos            |
| Desarmar (sabotaje)                 | 5 pitidos            |
| Sonido de retardo de entrada/salida | Count-down beeps     |

![](<.gitbook/assets/10 (8).png>)![](<.gitbook/assets/11 (4).jpeg>)![](<.gitbook/assets/12 (2).jpeg>)

**Precaución**

-   El cableado de la sirena interior cableada solo debe realizarlo técnicos certificados con el conocimiento y la capacitación adecuados en equipos eléctricos.
-   Antes de la instalación o cualquier trabajo de mantenimiento, asegúrese de que la fuente de alimentación esté desconectada.

![](<.gitbook/assets/13 (2).jpeg>)

**Cableado de sirena**

-   Antes de conectar la sirena interior cableada al bus del sistema, apague la alimentación.
-   Para ayudar con las conexiones de cables, los bloques de terminales de cada módulo del sistema BUS están codificados por colores.

![](<.gitbook/assets/14 (2).jpeg>)

| **Rojo**     | VDD    |
| ------------ | ------ |
| **Negro**    | Tierra |
| **Amarillo** | 485A   |
| **Verde**    | 485B   |

2

-   Se pueden conectar varios dispositivos BUS en serie al panel híbrido. Para una comunicación óptima de los dispositivos de línea BUS conectados, asegúrese de que los interruptores de puente de resistencia terminal del primer dispositivo (generalmente el panel híbrido) y del último dispositivo BUS en una línea BUS estén configurados en ON para que sirvan como resistencias de terminación. Asegúrese de habilitar solo los 2 interruptores de puente antes mencionados y no configurar los interruptores de puente en ON para ningún otro dispositivo BUS intermedio.

![](<.gitbook/assets/15 (4).png>)

_\\<NOTE>_

-   -   El diseño enchufable de los bloques de terminales BUS mejora la eficiencia de la instalación. Antes de realizar el cableado, puede retirar los bloques de terminales de la placa PCB para facilitar su uso y enchufarlos nuevamente después del cableado.
    -   Después de desconectar el terminal, al volver a instalarlo en la placa, asegúrese de instalar el terminal en la misma dirección para evitar posibles peligros.
-   Las conexiones incorrectas provocarán fallas o un funcionamiento incorrecto. Inspeccione el cableado y asegúrese de que las conexiones sean adecuadas antes de aplicar energía.

![](<.gitbook/assets/16 (7).png>)

**Aprendiendo**

Siga los pasos a continuación para configurar la sirena interior cableada en el panel híbrido.

Paso 1. Conecte el dispositivo al Panel. Luego, encienda el Panel.

Paso 2. En la página web del Panel, haga clic en “**Aprendiendo**”para ingresar a la página de aprendizaje.

Paso 3. Haga clic en "**Comenzar**”para ingresar al modo de aprendizaje.

Paso 4. Haga clic en "**Agregar**”para incluir el dispositivo en el Panel.

Paso 5. Si el dispositivo se reconoce correctamente en el Panel, se mostrará en la sección "Dispositivo aprendido".

![](<.gitbook/assets/17 (3).jpeg>)

**Identificación**

El "**Identificar**La función ”se utiliza para localizar un dispositivo BUS específico en el sistema cableado BUS. Esta función es útil para distinguir qué dispositivo es cuál, especialmente en una instalación grande donde se incluyen numerosos dispositivos BUS.

Para ubicar la sirena interior cableada en el sistema BUS:

**Paso 1.**En la página web del Panel híbrido, haga clic en "Identificar" debajo de la lista de dispositivos después de la entrada de la columna del dispositivo de la sirena.

**Paso 2.**Si SR-35-BUS recibe la señal del panel híbrido, la página web mostrará un mensaje de éxito y la sirena interior cableada emitirá 10 pitidos para indicarle al usuario dónde está.

![](<.gitbook/assets/18 (7).png>)

_\\<NOTE>_

-   Si se muestra un mensaje de tiempo de espera en la página web, significa que la sirena interior cableada no recibió la señal del panel.

Verifique si SR-35-BUS está conectado correctamente al panel dentro de la distancia de cableado adecuada.

![](<.gitbook/assets/19 (6).png>)

3

![](<.gitbook/assets/20 (2).jpeg>)**Prueba de caminata**

-   Para asegurarse de que la sirena interior cableada pueda comunicarse con el panel después de su aprendizaje, coloque el panel de control en modo de prueba de caminata y presione el botón de aprendizaje en SR-35-BUS para transmitir una señal de prueba al panel de control.
-   Cuando el panel reciba la señal de prueba, emitirá un pitido y mostrará la información de la sirena en consecuencia en la parte superior de la lista de dispositivos.

_\\<NOTE>_

-   Si no hay respuesta del Panel después de presionar el botón de aprendizaje, significa que el Panel no recibió la señal de prueba del dispositivo.

Verifique si SR-35-BUS está conectado correctamente al panel dentro de la distancia de cableado adecuada.

**Instalación**

Paso 1. Busque la ubicación donde se montará la sirena interior cableada.

Paso 2. Utilice el soporte de montaje como plantilla para perforar 3 orificios en la pared para los enchufes.

Paso 3. Introduzca los tacos y atornille el soporte de montaje a la pared con 3 tornillos.

Paso 4. Enganche la sirena en el soporte de montaje y luego empújela hacia abajo hasta que escuche un clic.

_\\<NOTE>_

-   Asegúrese de que el dispositivo esté correctamente enganchado al soporte de montaje, de modo que el interruptor de manipulación esté completamente presionado.

Paso 5. Verifique si la instalación fue exitosa probando desde el Panel de control con la función de armado y desarmado.

El armado/desarmado exitoso se indicará en la tabla proporcionada arriba en**Indicación de estado de audio**sección.

_\\<NOTE>_

-   Si se escuchan 5 pitidos cortos durante el armado/desarmado, significa que el sabotaje no está completamente presionado. Verifique para asegurarse de que la manipulación esté configurada correctamente y pruebe nuevamente desde el Panel de control.

Paso 6. La instalación ya está completa.

4
