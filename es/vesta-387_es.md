# VESTA 387

**Módulo de fuente de alimentación auxiliar (PWB-1-BUS)**

**Introducción**

El PWB-1-BUS es un módulo de fuente de alimentación auxiliar que se puede conectar en el sistema BUS de datos para proporcionar una fuente de alimentación máxima de 13,5 V y 5 A a los dispositivos BUS conectados. El módulo PWB-1-BUS es supervisado y comunica al Panel todos los cambios de estado, incluido el estado de alimentación de CA, el nivel de la batería, el estado de manipulación y los datos de consumo de energía.

**Identificar las piezas**

![](<.gitbook/assets/0 (4).jpeg>)

1.  **Terminales de conexión BUS al dispositivo BUS alimentado**(4 hilos: V, G, A, B)
2.  **BUS Connection Terminals to powered BUS device**(4 hilos: V, G, A, B)
3.  **Terminales de Conexión BUS al Panel Híbrido**(3 cables: G, A, B)
4.  **Interruptor de batería**

Deslice el interruptor de la batería a la posición ON, de modo que la batería de respaldo se cargue cuando se conecte la alimentación de CA y sirva como fuente de energía de respaldo cuando falte la alimentación de CA.

1.  **Terminal de batería**

Se conecta a la batería de respaldo (una batería de plomo-ácido sellada de 12 V 7,0 Ah o 12 V 17,2 Ah)

1.  **Orificios de montaje**
2.  **Terminal de alimentación**

Se conecta a una fuente de alimentación de 20 Vac 50 Hz/60 Hz, 4 A (80 VA).

1.  **Interruptor de puente de resistencia terminal (J3)**

Cuando el módulo de fuente de alimentación está conectado en la línea BUS como el dispositivo BUS más alejado del panel híbrido, configure los puentes de resistencia terminal del módulo de fuente de alimentación y el panel híbrido en ON. Se mejorará la capacidad de comunicación de la línea BUS.

-   -   El puente de resistencia terminal de PWB-1-BUS generalmente se usa cuando el módulo de fuente de alimentación se conecta por primera vez al panel híbrido sin ningún dispositivo BUS conectado.

Puede configurar el puente de resistencia terminal del módulo de fuente de alimentación y el puente de resistencia terminal del panel híbrido en ON para probar si PWB-1-BUS puede comunicarse bien con el panel.

Si la comunicación con el Panel es correcta, puede comenzar a conectar el PWB-1-BUS a los dispositivos alimentados. Luego, apague el puente de resistencia terminal del módulo de fuente de alimentación y, en su lugar, configure el puente de resistencia terminal del dispositivo más alejado de la línea BUS en ON.

![](<.gitbook/assets/1 (6).jpeg>)

Si el puente está APAGADO (el enlace del puente está retirado o "estacionado" en un pin), la capacidad de comunicación está en nivel normal.

![](<.gitbook/assets/2 (5).jpeg>)

Si el puente está activado (el enlace del puente descansa en ambos pines), se mejora la capacidad de comunicación.

1

1.  **Indicador LED**
2.  **Terminal de interruptor de manipulación**Se conecta al interruptor de manipulación de la tapa.

**Accesorios**

1.  Punto muerto\*4
2.  Tuerca separadora\*4
3.  Cable de batería de 12V 7.0Ah\*2 (+, -)

**Fuente de alimentación**

**Fuente de alimentación:**

-   El PWB-1-BUS está conectado a una fuente de alimentación de 20 Vca 50 Hz/60 Hz, 4 A (80 VA).
-   Cuando se interrumpe y se restablece el suministro de energía, PWB-1-BUS transmitirá una falla de CA y restaurará la señal respectivamente.

**Batería recargable:**

-   Se puede conectar una batería de plomo-ácido sellada de 12 V 7,0 Ah o 12 V 17,2 Ah para que sirva como respaldo en caso de un corte de energía.
-   Durante el funcionamiento normal, la alimentación de CA se utiliza para suministrar energía al PWB-1-BUS y al mismo tiempo recargar la batería. Se necesitan aproximadamente 48 horas para cargar completamente una batería de 12 V 7,0 Ah y 72 horas para cargar completamente una batería de 12 V 17,2 Ah.
-   Si el interruptor de la batería está en APAGADO, la batería no se cargará cuando esté conectada la alimentación de CA y tampoco servirá como fuente de alimentación de respaldo cuando falte la alimentación de CA. Necesitas cambiar la batería a**EN**para que se cargue cuando se conecta la alimentación de CA y sirva como fuente de alimentación de respaldo cuando falta la alimentación de CA.
-   Cuando la batería tiene poca energía, PWB-1-BUS transmitirá una señal de batería baja. Cuando la batería se haya cargado, PWB-1-BUS transmitirá la señal de restauración de la batería.
-   Cuando la batería está desconectada, el interruptor de la batería está apagado o se detecta una falla en la batería, PWB-1-BUS informará que la batería falta o está agotada al panel de control.

**Salida de potencia:**

-   PWB-1-BUS puede suministrar un máximo de 13,5 V, 5 A de potencia a los dispositivos BUS conectados.

**Protección contra manipulación**

-   El interruptor de manipulación para la puerta del gabinete está en posición normal cuando la puerta está cerrada. La infracción de manipulación ocurre cuando se abre la puerta donde se libera el interruptor de manipulación (sabotaje abierto). Se informará una señal de apertura por manipulación al panel de control.

**Conexión al Panel y dispositivos BUS**

**PRECAUCIÓN:**

**Retire toda la energía (CA y batería) antes de realizar cualquier conexión. El cableado del sistema de alarma solo debe realizarlo un técnico certificado con el conocimiento y la capacitación adecuados en equipos eléctricos.**

-   Para ayudar con las conexiones de cables, los bloques de terminales de cada módulo del sistema BUS están codificados por colores.

**Códigos de color del bloque de terminales**

| **Rojo**     | VDD    |
| ------------ | ------ |
| **Negro**    | Tierra |
| **Amarillo** | 485A   |
| **Verde**    | 485B   |

-   Al conectar el PWB-1-BUS al panel híbrido, conecte solo los tres terminales (GND, 485A, 485B). Consulte la imagen a continuación.
-   Al conectar el PWB-1-BUS a los dispositivos alimentados por el módulo de fuente de alimentación, conecte 4 terminales. (VDD, TIERRA, 485A, 485B).

Consulte los ejemplos de conexión de dispositivos BUS (VST-892-BUS y DC-23-BUS) a continuación.

2

![](<.gitbook/assets/3 (5).jpeg>)

_\\<NOTE>_

-   El diseño enchufable de los bloques de terminales BUS mejora la eficiencia de la instalación. Antes de realizar el cableado, puede quitar los bloques de terminales del dispositivo para facilitar su uso y enchufarlos nuevamente después del cableado.

Al volver a instalar los bloques de terminales en la placa, asegúrese de instalarlos en la misma dirección para evitar posibles peligros.

-   Las conexiones incorrectas provocarán fallas o un funcionamiento incorrecto. Inspeccione el cableado y asegúrese de que las conexiones sean adecuadas antes de aplicar energía.

**Empezando**

Después de conectar el módulo de fuente de alimentación auxiliar al panel híbrido (consulte_**Conexión al Panel y dispositivos BUS**_sección para más detalles), continúe con el aprendizaje.

-   _**Aprendiendo**_

**Paso 1.**Después de que el PWB-1-BUS esté conectado al panel híbrido, encienda el panel de control.

**Paso 2.**En la página web del Panel de control, haga clic en "**Aprendiendo**”para ingresar a la página de aprendizaje.

**Paso 3.**Haga clic en "**Comenzar**”para ingresar al modo de aprendizaje.

**Etapa 4.**Hacer clic**"Agregar"**para incluir el módulo de alimentación auxiliar en el panel.

**Paso 5.**Si el módulo de fuente de alimentación auxiliar se aprende correctamente en el sistema, el dispositivo agregado se mostrará en la sección "Dispositivo aprendido". El tipo de dispositivo se mostrará como "PWB".

-   _**Identificación**_

El "**Identificar**La función ”se utiliza para localizar un dispositivo BUS específico en el sistema cableado BUS. Esta función es útil para distinguir qué dispositivo es cuál, especialmente en una instalación grande donde se incluyen numerosos dispositivos BUS.

Para ubicar PWB-1-BUS en el sistema BUS:

![](<.gitbook/assets/4 (4).png>)

**Paso 1.**En la página web de Hybrid Panel, haga clic en "Identificar" debajo de la lista de dispositivos después de la entrada de la columna de dispositivos de PWB.

**Paso 2.**Si PWB-1-BUS recibe la señal del panel híbrido, la página web mostrará un mensaje de éxito y el indicador LED del PWB-1-BUS parpadeará 10 veces para indicarle al usuario dónde está.

_\\<NOTE>_

-   Si se muestra un mensaje de tiempo de espera en la página web, significa que el PWB-1-BUS no recibió la señal del Panel.

3

Verifique si PWB-1-BUS está conectado correctamente al panel dentro de la distancia de cableado adecuada.

**Señal de supervisión**

-   Después de ser programado en el Panel de control, el módulo de fuente de alimentación transmitirá automáticamente señales de supervisión cada 20 a 30 segundos.

**Monitor de consumo de energía**

-   Después de ser aprendido en el Panel de control, el módulo de fuente de alimentación transmitirá automáticamente datos de consumo de energía, incluido el nivel de la batería, el voltaje del BUS y la corriente del BUS al Panel de control cada 30 a 50 minutos.

![](<.gitbook/assets/5 (7).png>)





Cuando el nivel de batería sea inferior o igual al 20%, se enviará una señal de batería baja al Panel.

Cuando el nivel de la batería es 0%, indica una de las siguientes situaciones: batería desconectada, interruptor de la batería en posición apagada o falla de la batería.

El usuario también puede consultar manualmente los datos de consumo de energía en**Editar dispositivo**página.

![](<.gitbook/assets/6 (5).png>)

**Montaje del PWB-1-BUS en el gabinete (AWO300)**

-   Localice el**Ubicaciones de separación en el gabinete AWO300**(○1 – A, B, C, D), y el**Orificios de montaje en el PWB-1-BUS**(○2 – A, B, C, D).

![](<.gitbook/assets/7 (6).png>)

4

-   Utilice los separadores proporcionados para montar de forma segura el PWB-1-BUS en el gabinete.

![](<.gitbook/assets/8 (6).png>)

-   Una vez completado todo el cableado, instale la batería de respaldo. Las opciones de batería incluyen: Una batería de plomo-ácido sellada de 12 V 7,0 Ah o 12 V 17,2 Ah.

Para instalar la batería, siga los pasos a continuación:

-   1.  Conecte el cable GND (Negro) al polo negativo (-) de la batería.
    2.  Conecte el cable de alimentación (rojo) al polo positivo (+) de la batería.
    3.  Fije la batería de respaldo al gabinete.
-   Conecte el interruptor antisabotaje de la puerta del gabinete al terminal antisabotaje.
-   Conecte el terminal de alimentación a una fuente de alimentación de 20 Vca 50 Hz/60 Hz, 4 A (80 VA). Deslice el interruptor de la batería a ON.

![](<.gitbook/assets/9 (7).png>)

5
