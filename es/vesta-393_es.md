# VESTA 393

![](<.gitbook/assets/0 (6).png>)**Lector de etiquetas con cable (TG-15N-BUS)**

-   _**Introducción**_

TG-15N-BUS es un lector de etiquetas que puede comunicarse y alimentarse con el panel híbrido a través de una conexión BUS.

El lector de etiquetas con cable está integrado con etiquetas NFC para que pueda armar o desarmar rápidamente su sistema de alarma con solo deslizar el dedo.

El dispositivo consta de un diseño de dos partes formado por una tapa y una base. La tapa contiene toda la electrónica y la base proporciona un medio de fijación. El interruptor antisabotaje protege el gabinete contra la apertura o el retiro de la superficie de montaje.

![](<.gitbook/assets/1 (4).png>)

-   _**Identificar las piezas**_

1.  **LED verde LED rojo LED naranja Botón de brazo**
2.  **Zona de sensores (para etiquetas)**
3.  **Terminal de autobus**
4.  **Interruptor de puente de resistencia terminal**

Cuando el lector de etiquetas cableado esté conectado como el dispositivo BUS más lejano en una línea BUS, configure el puente de resistencia del terminal del lector y el interruptor de puente del primer dispositivo BUS (generalmente el panel híbrido) en ON para que sirvan como resistencias de terminación. Se mejorará la capacidad de comunicación de la línea BUS conectada.

![](<.gitbook/assets/2 (6).jpeg>)![](<.gitbook/assets/3 (5).png>)

**Puente encendido**

![](<.gitbook/assets/4 (6).jpeg>)

Se inserta el enlace del puente, conectando los dos pines.

**Puente apagado**

El enlace del puente se elimina o "**estacionado**”en un alfiler.

-   -   Si el puente está APAGADO, la capacidad de comunicación está en nivel normal.
    -   Si el puente está activado, se mejora la capacidad de comunicación.

1.  **Botón Aprender**
2.  **Manosear**
3.  **Tornillo de fijación**
4.  **Perforaciones para tornillos de montaje**
5.  **Orificio de cableado del autobús**

![](<.gitbook/assets/5 (3).jpeg>)

1

-   ![](<.gitbook/assets/6 (6).png>)_**Indicador LED:**_
    -   **LED verde:**
        -   Luz encendida durante 3 segundos: cuando el panel de control está en modo desarmado
        -   Destella durante 5 segundos: cuando se presiona el botón Armar (_Coloque la etiqueta cerca de la Zona del Sensor para Armar el sistema durante estos 5 segundos_)
        -   Parpadea 10 veces: cuando se hace clic en “identificar” en la página web del Panel.
    -   **LED rojo:**
        -   Luz encendida durante 3 segundos: cuando el panel de control está en modo armado
        -   Parpadea durante 3 segundos: cuando el sistema se desarma después de una alarma
    -   **LED naranja:**
        -   Luz encendida durante 3 segundos: cuando TG-15N-BUS detecta una etiqueta y pierde la conexión con el Panel de control
-   _**Fuerza:**_

![](<.gitbook/assets/7 (3).jpeg>)![](<.gitbook/assets/8 (3).jpeg>)![](<.gitbook/assets/9 (8).png>)

Cuando el TG-15N-BUS está cableado a un panel híbrido, el panel híbrido puede proporcionar una fuente de alimentación de 13,5 V.

![](<.gitbook/assets/10 (9).png>)

-   _**Protección contra manipulación:**_
    -   El lector de etiquetas cableado está protegido contra cualquier intento de abrir la tapa o separar el lector de su superficie de montaje (consulte**Lector de etiquetas de montaje**para detalles).
    -   Cuando se activa la manipulación del lector, se enviará una señal de manipulación al Panel de control para que el Panel de control muestre el estado. Una vez enviada la señal, el Lector vuelve al modo inactivo.
-   _**Supervisión**_
    -   Después de la instalación, el lector de etiquetas cableado transmitirá automáticamente señales de supervisión periódicamente al panel de control en intervalos aleatorios de 20 a 30 segundos.
-   _**Precaución**_
    -   El cableado del lector de etiquetas cableado solo debe ser realizado por técnicos certificados con el conocimiento y la capacitación adecuados en equipos eléctricos.
    -   Antes de la instalación o cualquier trabajo de mantenimiento, asegúrese de que la fuente de alimentación esté desconectada.
-   _**Cableado del lector de etiquetas:**_
    -   Antes de conectar el lector de etiquetas cableado al bus del sistema, apague la alimentación.
    -   Para facilitar la conexión de cables, los bloques de terminales de cada módulo del sistema BUS están codificados por colores.

![](<.gitbook/assets/11 (4).png>)![](<.gitbook/assets/12 (6).png>)![](<.gitbook/assets/13 (6).png>)![](<.gitbook/assets/14 (3).jpeg>)

| **Rojo**     | VDD    |
| ------------ | ------ |
|              |        |
| **Negro**    | Tierra |
|              |        |
| **Amarillo** | 485A   |
|              |        |
| **Verde**    | 485B   |
|              |        |

-   Se pueden conectar varios dispositivos BUS en serie al panel híbrido. Para una comunicación óptima de los dispositivos de línea BUS conectados, asegúrese de que los interruptores de puente de resistencia terminal del primer dispositivo (generalmente el panel híbrido) y del último dispositivo BUS en una línea BUS estén configurados en ON para que sirvan como resistencias de terminación. Asegúrese de habilitar solo los 2 interruptores de puente antes mencionados y no configurar los interruptores de puente en ON para ningún otro dispositivo BUS intermedio.

![](<.gitbook/assets/15 (5).png>)

_\\<NOTE>_

-   El diseño enchufable de los bloques de terminales BUS mejora la eficiencia de la instalación. Antes de realizar el cableado, puede retirar los bloques de terminales de la placa PCB para facilitar su uso y enchufarlos nuevamente después del cableado.
-   Después de desconectar el terminal, al volver a instalarlo en la placa, asegúrese de instalar el terminal en la misma dirección para evitar posibles peligros.

2

-   Las conexiones incorrectas provocarán fallas o mal funcionamiento. Inspeccione el cableado y asegúrese de que las conexiones sean adecuadas antes de aplicar energía.

![](<.gitbook/assets/16 (8).png>)

-   _**Primeros pasos: aprendizaje del lector de etiquetas cableado en el panel de control**_

Siga los pasos a continuación para aprender el dispositivo en el panel híbrido.

**Paso 1.**Conecte el dispositivo al Panel. Luego, encienda el Panel.

**Paso 2.**En la página web del Panel, haga clic en “**Aprendiendo**”para ingresar a la página de aprendizaje.

**Paso 3.**Haga clic en "**Comenzar**”para ingresar al modo de aprendizaje; El lector de etiquetas cableado se mostrará justo después de que el panel entre en modo de aprendizaje.

**Etapa 4.**Haga clic en "**Agregar**”para incluir el dispositivo en el Panel.

**Paso 5.**Si el dispositivo se aprende correctamente en el Panel, se mostrará en la sección "Dispositivo aprendido".

![](<.gitbook/assets/17 (5).png>)

-   _**Identificación**_

La función "Identificar" se utiliza para localizar un dispositivo BUS específico en el sistema cableado BUS. Esta función es útil para distinguir qué dispositivo es cuál, especialmente en una instalación grande donde se incluyen numerosos dispositivos BUS.

Para ubicar el lector de etiquetas cableado en el sistema BUS:

**Paso 1.**En la página web del Panel híbrido, haga clic en "Identificar" debajo de la lista de dispositivos después de la entrada de la columna del dispositivo del lector de etiquetas.

**Paso 2.**Si el TG-15N-BUS recibe la señal del panel híbrido, la página web mostrará un mensaje de éxito y el LED verde del TG-15N-BUS parpadeará 10 veces para indicarle al usuario dónde está.

![](<.gitbook/assets/18 (8).png>)

_\\<NOTE>_

-   -   Si se muestra un mensaje de tiempo de espera en la página web, significa que TG-15N-BUS no recibió la señal del Panel.

Verifique si el TG-15N-BUS está conectado correctamente al panel dentro de la distancia de cableado adecuada.

-   _**Prueba de caminata**_

![](<.gitbook/assets/19 (7).png>)

-   Para asegurarse de que el lector de etiquetas cableado pueda comunicarse con el panel después de su aprendizaje, coloque el panel de control en modo de prueba de recorrido y presione el botón de aprendizaje en el TG-15N-BUS para transmitir una señal de prueba al panel de control.

3

-   Cuando el Panel reciba la señal de prueba, emitirá un pitido y mostrará la información del Lector en consecuencia en la parte superior de la lista de dispositivos.

![](<.gitbook/assets/20 (5).png>)

_\\<NOTE>_

-   -   Si no hay respuesta del Panel después de presionar el botón de aprendizaje, significa que el Panel no recibió la señal de prueba del dispositivo.

Verifique si el TG-15N-BUS está conectado correctamente al panel dentro de la distancia de cableado adecuada.

-   _**Montaje del lector de etiquetas cableado:**_

La base tiene tres orificios ciegos para fines de montaje. Para montar el lector de etiquetas cableado:

-   -   1.  Desenrosque el tornillo de fijación.
        2.  Retire la cubierta del lector.
        3.  Coloque el terminal BUS en la PCB; Pase los cables a través del orificio de cableado del BUS como se muestra en la figura.
        4.  Rompe los nocauts en la base.
    -   Utilice los troqueles como plantilla y taladre agujeros en la superficie a montar.
        1.  Inserte los tacos si el dispositivo se va a fijar sobre yeso o ladrillo.
        2.  Atornille la base a los tacos.
    -   Vuelva a colocar la tapa en la base y atornille el tornillo de fijación.

_**\\<NOTE>**_

-   -   Si se retira a la fuerza el lector montado, el área de separación quedará en la pared separada del lector y se activará la manipulación.
-   _**Aprendizaje/eliminación de etiquetas**_
    -   -   Antes de aprender una etiqueta en el Panel de control, asegúrese de que el lector de etiquetas cableado haya sido aprendido en el Panel de control.
        -   Después de encender por primera vez el lector de etiquetas con cable, espere 10 segundos para que el lector habilite la función del sensor de etiquetas.
-   A_**Aprender**_la etiqueta en el Panel de control:**Paso 1.**Desarmar el sistema.

**Step 2.**Ir a la página web local >**Código PIN**. Seleccionar**Área**. Coloque la etiqueta cerca de la Zona del Sensor y el Lector enviará el número de identificación de la etiqueta al Panel de Control. El Lector emitirá 4 pitidos. Hacer clic**Carga**botón en la página web.

_**\\<NOTE>**_

-   -   Si la etiqueta se ha aprendido en el sistema, cuando coloque la etiqueta cerca de la zona del sensor, emitirá 2 pitidos y el LED verde se encenderá durante 3 segundos para ingresar al modo de desarmado.

**Paso 3.**Cuando el número de identificación de la etiqueta se muestre en la página web, ingrese un código de usuario de 4 dígitos y asigne un nombre de usuario a la etiqueta.

4

**Etapa 4.**Hacer clic**DE ACUERDO**en la página web para guardar la configuración.

**Paso 5.**El aprendizaje de etiquetas está completo.

-   A_**Eliminar**_la etiqueta del Panel de control:**Paso 1.**Desarmar el sistema.

**Paso 2.**Ir a la página web local >**Código PIN**. Seleccionar**Área**. Coloque la etiqueta cerca de la Zona del Sensor y el Lector enviará el número de identificación de la etiqueta al Panel de Control. El lector de etiquetas emitirá 2 pitidos y el LED verde se encenderá durante 3 segundos. Busque una columna de número de etiqueta en blanco y haga clic**Carga**para verificar el número de identificación de la etiqueta que se eliminará.

_**\\<NOTE>**_

-   Si la etiqueta no se ha aprendido en el sistema, cuando la coloque cerca del lector de etiquetas cableado, emitirá 4 pitidos para notificar a los usuarios de la falla.

**Paso 3.**Según el número de identificación de la etiqueta, busque el mismo número de identificación de la etiqueta en la lista y marque**Borrar**.

-   **Ejemplo:**Como se muestra en las imágenes, los números 1 y 2 de la lista son las etiquetas aprendidas existentes. Después de colocar la etiqueta cerca del lector y hacer clic**Carga**en la columna en blanco No.3, el número de identificación de la etiqueta que se muestra en el No. 3 es el mismo que el del No. 2, por lo que el No. 2 es la etiqueta que se debe quitar. Garrapata**Borrar**en las columnas No. 2 y No. 3 para quitar la etiqueta.

**Etapa 4.**Hacer clic**DE ACUERDO**en la página web para guardar el cambio.

**Paso 5.**La eliminación de la etiqueta está completa.

-   _**Operación:**_

Después de completar el aprendizaje de la etiqueta en el lector de etiquetas cableado, ahora puede cambiar el sistema al modo Armar o Desarmar:

1.  **Control del modo de desarmado:**Aplique la etiqueta cerca de la Zona del Sensor en modo armado; el Lector emitirá 2 pitidos cuando el Panel reciba la señal de desarmado y cambie exitosamente al Modo Desarmado.
2.  **Control del modo armado:**Presione el botón Armar una vez y el LED verde parpadeará rápidamente durante 5 segundos; luego aplique la etiqueta cerca de la Zona del Sensor durante estos 5 segundos, el Lector de Etiquetas emitirá 1 pitido largo para indicar que el Panel ha recibido la solicitud de armado exitosamente.
3.  **Flash LED:**Si el sistema está armado, el LED rojo se encenderá durante 3 segundos. Cuando esté desarmado, el LED verde se encenderá durante 3 segundos.
4.  **Manosear:**Cuando se activa la manipulación, el lector de etiquetas cableado transmitirá una señal de alarma de manipulación al panel de control inmediatamente y volverá al modo inactivo.

5
