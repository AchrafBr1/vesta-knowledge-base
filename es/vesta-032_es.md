# VESTA 032

Detector de humo y monóxido de carbono (Serie SDCO-1-F1)

Introducción

La serie SDCO-1-F1 es un detector de humo y monóxido de carbono. Es capaz de enviar señales inalámbricas al Panel de Control al detectar partículas de humo o Monóxido de Carbono. El SDCO-1 está diseñado para montarse en el techo o en la parte superior de las escaleras donde se concentraría el humo para dar la alarma oportuna y proteger su hogar de los riesgos de incendio.

La serie SDCO-1 incluye los siguientes modelos:

| **Nombre del modelo** | **Calor** | **2 vías** | **Conexión en serie** |
| --------------------- | --------- | ---------- | --------------------- |
| SDCO-1-F1             |           |            |                       |
| SDCO-1H-SC            | en        |            | en                    |
| SDSU-1-F1-2F          |           | en         |                       |
| SDCO-1H-F1            | en        |            |                       |
| SDSU-1H-F1-2F         | en        | en         |                       |

Identificación de piezas

![](<.gitbook/assets/0 (11).png>)

1.  **Botón de prueba**

-   Presione el botón una vez para enviar una señal de prueba/aprendizaje.
-   Presione el botón una vez durante la alarma para ingresar al modo de silencio de alarma.
-   Mantenga presionado el botón durante 10 segundos. Suelte el botón cuando el SDCO emita 2 pitidos para ingresar a la calibración de humo y CO

proceso de autodiagnóstico.

-   Presione el botón dos veces para descargar completamente antes de insertar baterías nuevas.

1.  **Indicador LED**

**LED rojo**

-   Se enciende brevemente: transmitiendo señal de prueba/aprendizaje.
-   Parpadeo rápido: alarmante.
-   Parpadea cada segundo: en modo silencio de alarma.
-   Parpadea cada 2 segundos: En proceso de calentamiento y calibración.

**LED ámbar**

-   Parpadea cada 5 segundos: mal funcionamiento del dispositivo
-   Parpadea cada 45 segundos: condición de batería baja

**LED rojo y ámbar (naranja cuando se mira desde el exterior)**

-   Parpadea cada 4 segundos: Las baterías están extremadamente bajas y es necesario reemplazarlas.

1.  **Zumbador**
2.  **Orificios de montaje (para ganchos)**

Los ganchos del soporte de montaje pueden engancharse en sus orificios de montaje.

1.  **Soporte de montaje**
2.  **Tapa del compartimento de la batería**
3.  **Tornillo de fijación de la tapa del compartimento de la batería**
4.  **Muescas**
5.  **Puerto de actualización de firmware (USB tipo C)**

-   Solo para actualización de firmware con cable personalizado.**Tenga en cuenta:**El mal uso del cable USB tipo C normal puede provocar un mal funcionamiento del dispositivo.

Características

-   Detección de batería y batería baja
-   El SDCO-1 utiliza tres baterías de litio EL123AP como fuente de energía. Las baterías están incluidas en el paquete.
-   El SDCO tiene un mecanismo infalible que prohíbe cerrar la tapa sin antes instalar la batería.
-   Cuando el SDCO tiene poca batería, se transmitirá una señal de batería baja junto con las transmisiones de señal regulares. El LED ámbar parpadeará con un pitido de bajo volumen una vez cada 45 segundos.
-   Tanto el LED rojo como el ámbar parpadearán una vez cada 4 segundos cuando las baterías estén extremadamente bajas y sea necesario reemplazarlas.
-   Al cambiar las baterías, después de quitar las baterías viejas, presione el botón de prueba dos veces para descargarlas por completo antes de insertar baterías nuevas.
-   Empezando

**Paso 1:**Utilice un destornillador Phillips para aflojar el tornillo de fijación del compartimiento de la batería y retire la tapa del compartimiento de la batería.

**Paso 2:**Inserte 3 baterías en el compartimiento de baterías.

**Paso 3:**El detector SDCO emitirá 2 pitidos cortos y comenzará el proceso de calentamiento durante**1**minuto. El LED parpadeará cada 2 segundos.

**Etapa 4.**Durante el período de 1 minuto, aprenda en el detector de humo.

1.  Presione el botón Aprender/Probar una vez para transmitir un código de aprendizaje del sensor IR.
2.  Mantenga presionado el botón Aprender/Probar durante 3 segundos para transmitir un código de aprendizaje del sensor de humo/temperatura.**(Los pasos a. y b. son necesarios para los modelos conectados en serie)**.

Si el Panel de Control recibe la señal, el Detector de Humo emitirá un pitido de 2 tonos. Consulte el manual del Panel de control para completar el proceso de aprendizaje.

**Paso 5:**Cuando expire el período de calentamiento de 1 minuto, el detector SDCO emitirá un pitido para indicar que ahora ingresa al proceso de calibración. El

el proceso de calibración toma 1~7 minutos; El LED seguirá parpadeando durante la calibración.

**Paso 6:**Cuando se complete la calibración, el detector SDCO emitirá un sonido de 2 tonos y el LED dejará de parpadear para indicar que ahora está bajo

operación normal. Si la calibración falla, el detector SDCO emitirá pitidos continuos.

-   _**Detección de alarma**_

El detector SDCO activará la alarma de incendio cuando se active cualquiera de sus funciones de detección de humo o de detección de calor alto. Cuando se activa una alarma, el detector SDCO transmitirá una señal de alarma y activará la alarma con su zumbador incorporado. El LED rojo parpadeará rápidamente.

**Detección de humo:**

-   El detector SDCO comprueba la concentración de humo cada 8 segundos.
-   Siempre que la concentración de humo supere el umbral de detección, SDCO enviará una señal activa al Panel de Control y activará la alarma.
-   Si la concentración de humo persiste, el Detector SDCO seguirá enviando la señal activa cada 2 minutos al Panel de Control.
-   Si no se detecta humo durante 20 veces de detección continua, el SDCO transmitirá una señal de restauración y detendrá la alarma.

**Detección de calor (solo para los modelos SDCO-1H-F1 y SDCO-1H-F1-2W):**

-   El detector SDCO comprueba la temperatura cada 10 segundos.
-   La alarma se activará en las siguientes condiciones:

\-Cuando la temperatura aumenta 8,25 °C por minuto (tasa de aumento).

\-Cuando la temperatura supera los 57,25°C (calor alto).

-   Si no se detecta calor alto durante 20 veces de detección continua, el SDCO transmitirá una señal de restauración y dejará de dar la alarma.
-   Si la alarma se activó por una condición de calor alto (57,25 °C), la temperatura debe caer por debajo de 49 °C para que el detector deje de dar la alarma.
-   Si la alarma se activó por la condición de tasa de aumento (8,25 °C por minuto o más), la temperatura debe descender a 4 °C por debajo de la temperatura más alta detectada para que el detector deje de emitir la alarma.

**Detección de monóxido de carbono:**

-   El sensor de CO comprueba el nivel de concentración de CO cada 16 segundos. Si el nivel de concentración excede el umbral de detección, el detector SDCO transmitirá una señal de alarma y activará la alarma con su zumbador incorporado.
-   El sensor de CO cuenta con una función de autodiagnóstico y comprobará periódicamente el estado del sensor cada 12 horas.
-   La alarma se activará después de que se detecte la concentración de CO según el período de tiempo en la siguiente tabla: (cumple con la norma EN-50291)

| **nivel de concentración de CO** | **Tiempo necesario antes de dar la alarma** |
| -------------------------------- | ------------------------------------------- |
| 30 +/- 10% ppm                   | N / A                                       |
| 50 +/- 10%ppm                    | 60~90 minutos                               |
| 100 +/- 10% ppm                  | 10~40 minutos                               |
| 300 +/- 10% ppm                  | Menos de 3 minutos                          |

-   La alarma se activará después de que se detecte la concentración de CO según el período de tiempo en la siguiente tabla: (cumple con el estándar UL-2034)

| **nivel de concentración de CO** | **Tiempo necesario antes de dar la alarma** |
| -------------------------------- | ------------------------------------------- |
| 30 +/- 3%ppm                     | N / A                                       |
| 70 +/- 5%ppm                     | N / A                                       |
| 70 +/- 5%ppm                     | 60~240 minutos                              |
| 150 +/- 5% ppm                   | 10~50 minutos                               |
| 400 +/- 10% ppm                  | 4~15 minutes                                |

-   Una vez que el nivel de concentración de CO excede el umbral y persiste durante el tiempo indicado en la tabla anterior, el detector SDCO transmitirá la señal al panel de control y activará la alarma con su sirena incorporada.
-   Prueba del detector SDCO

Al presionar el botón de prueba en el detector SDCO, puede probar si el SDCO está funcionando normalmente.

-   Si el detector SDCO funciona normalmente, el LED rojo parpadeará una vez seguido de un pitido de dos tonos.
-   Si se emiten tres pitidos de 2 tonos (DO-DI DO-DI DO-DI), significa que el sensor de humo está averiado.
-   Si se emiten 5 pitidos (DO-Bi-Bi-Bi-DO), significa que el sensor de calor está averiado.
-   Si se emiten 7 pitidos (Bi-Bi-Bi-DO-Bi-Bi-Bi), significa que el sensor de CO está averiado.
-   _**Supervisión**_
-   Para los modelos SDCO-1(H)-F1, el detector SDCO transmitirá una señal de supervisión para informar su condición periódicamente cada 30 a 50 minutos.
-   Para los modelos SDCO-1(H)-F1-2W, el detector SDCO transmitirá una señal de supervisión para informar su condición periódicamente cada 90 a 110 minutos.
-   Si el panel de control no ha recibido la señal del detector de humo durante un período de tiempo preestablecido, el panel de control determinará que el detector de humo está averiado.
-   _Conexión en serie__(solo modelo conectado en serie)_
-   El detector de humo está en conexión en serie con otro detector de humo en el sistema de alarma. Cuando un detector de humo activa la alarma, el panel de control notificará a otros detectores de humo para que también activen la alarma incluso si aún no han detectado humo. La duración de la alarma estará de acuerdo con la configuración del Panel de Control.
-   No puede presionar el botón de función para silenciar la alarma activada por otros detectores de humo.
-   La alarma se restablecerá solo después de 3 minutos de tiempo de espera o hasta que el otro detector de humo que activa la alarma transmita una señal de restauración.
-   Silencio de alarma
-   Cuando el detector de humo emite una alarma, al presionar el botón de prueba, el detector de humo entrará en modo de silencio de alarma para silenciar la alarma durante 9 minutos. El timbre solo dejará de sonar después de que la alarma haya estado activada durante al menos 1 minuto. Si se presiona el botón antes de que la hora de la alarma llegue a 1 minuto, el detector de humo esperará hasta que la hora de la alarma llegue a 1 minuto antes de silenciarla.
-   Durante el período de silencio de alarma de 9 minutos, el LED rojo parpadeará una vez por segundo. El detector de humo seguirá monitoreando la concentración de humo durante el período de silencio de la alarma:

1.  Una vez transcurrido el período de silencio de alarma de 9 minutos, si la concentración de humo ha caído por debajo del umbral de alarma, el detector de humo emitirá un pitido de dos tonos y volverá al funcionamiento normal sin hacer sonar la alarma.
2.  Si la concentración de humo aún excede el umbral de alarma, el detector de humo comenzará a sonar nuevamente.
3.  Si la concentración de humo continúa aumentando durante el período de silencio de alarma y excede un segundo umbral de alarma, el detector de humo comenzará a sonar nuevamente. Una alarma activada al exceder el segundo umbral de alarma no se pudo silenciar presionando el botón de prueba.

-   Recalibración

El SDCO calibrará su sensor detector de humo cada vez que se aplique energía para garantizar una sensibilidad óptima al humo. Después de la instalación, las condiciones de funcionamiento del detector de humo pueden variar después de un tiempo, lo que puede afectar su función de detección de humo y requerir recalibración. Hay dos formas de recalibrar el detector de humo: calibración automática y calibración manual.

**Calibración automática:**

-   Después del encendido, el detector de humo realizará una calibración automática después de 4 horas.
-   Después de la primera calibración automática, el detector de humo realizará una calibración automática todos los meses. Durante el proceso de autocalibración, el detector de humo no emitirá ningún sonido.
-   Si la calibración automática falla, el LED ámbar parpadeará cada segundo junto con pitidos continuos y el detector de humo transmitirá una señal de falla de calibración.
-   Cuando falla la calibración automática del detector de humo, la función de alarma de humo seguirá funcionando normalmente utilizando el valor umbral tomado de la última calibración exitosa.

**Calibración manual:**

-   La calibración manual se puede realizar en cualquier momento que se desee:

1.  Mantenga presionado el botón Aprender/Probar durante 10 segundos y suéltelo cuando el detector de humo emita 2 pitidos.
2.  El detector de humo entrará en proceso de calibración. El indicador LED parpadeará cada 2 segundos.
3.  Una vez que el detector de humo finalice la recalibración, emitirá dos pitidos rápidos para indicarlo. El LED se apagará.
4.  Si el proceso de calibración falla, el detector de humo emitirá un sonido de alarma. Retire y vuelva a insertar la batería para reiniciar el proceso nuevamente.

![100-2](<.gitbook/assets/1 (15).png>)Instalación

-   Guía de instalación
-   Se recomienda que el sitio de instalación esté en el área central del techo.
-   La altura de montaje ideal para el detector SDCO es de 2,4 a 3 metros. El montaje por encima de 3 metros puede afectar el rendimiento de la detección.
-   No ubique el detector en los siguientes lugares:
-   La cocina: el humo de la cocina puede provocar una alarma no deseada.
-   ![100-3](<.gitbook/assets/2 (18).png>)Cerca de un ventilador, una lámpara fluorescente o un equipo de aire acondicionado: las corrientes de aire que emiten pueden afectar la sensibilidad del detector.
-   Cerca de vigas del techo o sobre un gabinete: el aire estancado en estas áreas puede afectar la sensibilidad del detector.
-   En la cima de un techo tipo estructura “A”.
-   Recomendación de instalación
-   **Limitaciones**
-   No instale el detector SDCO expuesto a la luz solar directa.
-   Evite instalar el detector SDCO en áreas donde los dispositivos puedan causar cambios rápidos de temperatura en el área de detección, es decir, aire acondicionado, calentadores, etc.
-   Evite grandes obstáculos en el área de detección.
-   No apunte directamente a fuentes de calor, p. Fuegos o calderas, y no encima de radiadores.
-   Montaje del detector SDCO

**Paso 1.**Coloque el detector SDCO en la ubicación de montaje deseada y use la función de prueba de rango para asegurarse de que el panel de control pueda recibir el detector SDCO en la ubicación de montaje.

**Paso 2.**El detector SDCO tiene un soporte de montaje para instalación en el techo. El soporte proporciona flexibilidad bidireccional.

**Paso 3.**Utilice los 4 orificios del soporte como plantilla para perforar orificios e insertar tacos de pared si es necesario.

**Etapa 4.**El usuario puede girar el soporte de montaje en el sentido de las agujas del reloj o en el sentido contrario a las agujas del reloj para bloquear el gancho. Asegúrese de que los tacos de pared estén al ras con la superficie de montaje.

**Paso 5.**Cuando la posición sea satisfactoria, atornille el soporte de montaje al techo.

**Paso 6.**Limpie bien el polvo, ya que puede ensuciar el sensor e impedir que funcione correctamente en caso de una emergencia.

**Paso 7.**El SDCO tiene tres muescas en su cubierta trasera para una fácil identificación, como se muestra a continuación.

![](<.gitbook/assets/3 (17).png>)

**Paso 8.**Sostenga el detector SDCO con especial cuidado y alinee las tres muescas con los ganchos del soporte de montaje.

**Paso 9.**Gire el detector SDCO en el sentido de las agujas del reloj para bloquear el gancho. La instalación ya está completa.
