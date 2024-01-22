# VESTA 384

![](<.gitbook/assets/0 (116).jpeg>)**Detector de humo con cable (SD-32-BUS)**

**Introducción**

SD-32-BUS es un detector de humo con cable diseñado para protegerle contra posibles riesgos de incendio. El detector de humo utiliza tecnología de sensores multicriterio para detectar entre llamas de combustión rápida y fuegos de combustión lenta, mientras que al mismo tiempo incluye tecnología inteligente para diferenciar entre el humo de la cocina y las emergencias reales de incendios domésticos que ponen en peligro la vida, eliminando virtualmente las alarmas molestas.

El detector de humo con cable también se puede interconectar con otros detectores de humo en el sistema de alarma y activa la alarma cuando se activa cualquier detector de humo en el sistema.

**Identificación de piezas**

![](<.gitbook/assets/1 (85).png>)

**1. Indicador LED/Botón de prueba**

**LED rojo**

-   Parpadeo rápido: alarmante.
-   Parpadea cada 1 segundo: Detector de humo en modo de silencio de alarma.
-   Parpadea cada 2 segundos: Detector de humo en proceso de calentamiento y calibración.
-   Parpadea brevemente: cuando se presiona el botón Aprender para ver si el dispositivo funciona normalmente.
-   Se enciende brevemente: Transmitiendo señal.

**LED naranja**

-   Parpadea cada segundo: Falló la calibración.
-   Parpadea cada 5 segundos: falló la detección de humo o el dispositivo no funciona correctamente.

**Botón de prueba**

-   -   Presione el botón una vez para:
        -   Envía una señal de prueba.
        -   Verifique la cámara de detección de humo.
        -   Silenciar la alarma cuando el detector de humo da la alarma.
    -   Mantenga presionado el botón durante 10 segundos para ingresar al proceso de calibración.

1.  **Zumbador**
2.  **Compartimento de terminal de autobús**
3.  **Manos**
4.  **Orificio preperforado para cableado.**
5.  **Tornillo de fijación de la tapa del compartimento del terminal BUS**
6.  **Terminal de autobus**
7.  **Interruptor de puente de resistencia terminal**

Cuando el detector de humo esté conectado como el dispositivo BUS más alejado de una línea BUS, configure el puente de resistencia terminal del detector de humo y el interruptor de puente del primer dispositivo BUS (generalmente el panel híbrido) en ON para que sirvan como resistencias terminales. Se mejorará la capacidad de comunicación de la línea BUS conectada.

![](<.gitbook/assets/2 (83).jpeg>)

-   -   -   Si el puente está APAGADO (el enlace del puente está retirado o "estacionado" en un pin), la capacidad de comunicación está en nivel normal.
    -   Si el puente está activado, se mejorará la capacidad de comunicación.

1.  **Soporte de montaje**
2.  **Orificios de montaje**
3.  **Hoja de montaje**

![](<.gitbook/assets/3 (81).jpeg>)

1

**Características**

![](<.gitbook/assets/4 (96).png>)

-   _**Fuente de alimentación**_
    -   Cuando el SD-32-BUS está cableado a un panel híbrido, el panel híbrido puede proporcionar una fuente de alimentación de 13,5 V.
-   _**Prueba del detector de humo**_

![](<.gitbook/assets/5 (98).png>)

Al presionar el botón de prueba en el detector de humo, puede probar si el detector de humo está funcionando normalmente.

-   -   Si el detector de humo funciona normalmente, el LED rojo se encenderá durante 2 segundos seguido de un pitido de 2 tonos.
    -   Si el timbre suena 2 tonos y 3 veces, el "**Cámara óptica**”en el detector de humo está sucio o fuera de servicio.
-   _**Detección de acumulación de polvo**_
    -   El detector comprueba periódicamente si hay acumulación excesiva de polvo dentro de la cámara óptica.
    -   Si la cámara acumula polvo, el detector informará al Panel para notificar al usuario que la limpie.
    -   Si la cámara aún no se limpia y recibe demasiado polvo y ya no funciona, el detector informará al Panel para recibir una advertencia de mantenimiento.
-   _**Supervisión**_
    -   El detector de humo cableado transmitirá automáticamente una señal de supervisión al panel de control cada 75 segundos.
    -   Si el panel de control no ha recibido la señal del detector de humo cableado durante un período de tiempo preestablecido, el panel de control indicará que el detector de humo en particular está experimentando un problema de falta de señal.
-   _**Activación de alarma**_

![](<.gitbook/assets/6 (80).png>)![](<.gitbook/assets/7 (70).png>)![](<.gitbook/assets/8 (69).png>)

El detector de humo activará la alarma de incendio cuando se active la detección de humo. Cuando se activa una alarma, el detector de humo transmitirá una señal de alarma y activará la alarma con su zumbador incorporado.

**Detección de humo:**

-   -   El detector de humo comprueba la concentración de humo cada 8 segundos.
    -   La alarma se activa cada vez que la concentración de humo excede el umbral de detección y continuará hasta que la concentración de humo caiga por debajo del umbral de alarma.
    -   El LED rojo parpadeará rápidamente durante la alarma.
-   _**Silencio de alarma**_
    -   Cuando el detector de humo emite una alarma, al presionar el botón de prueba, el detector de humo entrará en modo de silencio de alarma para silenciar la alarma durante 9 minutos. El timbre sólo dejará de sonar después de que la alarma haya estado activada durante al menos 1 minuto. Si se presiona el botón antes de que la hora de la alarma llegue a 1 minuto, el detector de humo esperará hasta que la hora de la alarma llegue a 1 minuto antes de silenciarla.
    -   Durante el período de silencio de alarma de 9 minutos, el LED rojo parpadeará una vez por segundo. El detector de humo seguirá monitoreando la concentración de humo durante el período de silencio de la alarma:
    -   Una vez transcurrido el período de silencio de alarma de 9 minutos, si la concentración de humo ha caído por debajo del umbral de alarma, el detector de humo emitirá un pitido de dos tonos y volverá al funcionamiento normal sin hacer sonar la alarma.
    -   Si la concentración de humo aún excede el umbral de alarma, el detector de humo comenzará a sonar nuevamente.
    -   Si la concentración de humo continúa aumentando durante el período de silencio de alarma y excede un segundo umbral de alarma, el detector de humo comenzará a sonar nuevamente. Una alarma activada al exceder el segundo umbral de alarma no se pudo silenciar presionando el botón de prueba.
-   _**Interconexión**_
    -   El detector de humo está interconectado con otros detectores de humo en el sistema de alarma. Cuando un detector de humo activa la alarma, el panel de control notificará a otros detectores de humo para que también activen la alarma incluso si aún no han detectado humo. La duración de la alarma estará de acuerdo con la configuración del Panel de Control.
    -   Desarmar el sistema detendrá la alarma de otros detectores de humo activados por el panel de control. La alarma activada por el detector de humo que detecta humo solo se detendrá cuando la concentración de humo caiga por debajo del umbral de alarma.
    -   Al presionar el botón de prueba de un detector de humo solo se silenciará la alarma de ese detector de humo específico, pero no se puede silenciar la alarma de todos los detectores de humo interconectados.
-   _**Precaución**_
    -   El cableado del detector de humo solo debe ser realizado por técnicos certificados con el conocimiento y la capacitación adecuados en equipos eléctricos.
    -   Antes de la instalación o cualquier trabajo de mantenimiento, asegúrese de que la fuente de alimentación esté desconectada.
-   _**Cableado del detector de humo**_
    -   Antes de conectar el detector de humo con cable al BUS del sistema, apague la alimentación.
    -   Para ayudar con las conexiones de cables, los bloques de terminales de cada módulo del sistema BUS están codificados por colores.

![](<.gitbook/assets/9 (67).png>)![](<.gitbook/assets/10 (29).jpeg>)![](<.gitbook/assets/11 (53).png>)![](<.gitbook/assets/12 (56).png>)![](<.gitbook/assets/13 (40).jpeg>)

| **Rojo**     | VDD    |
| ------------ | ------ |
| **Negro**    | Tierra |
| **Amarillo** | 485A   |
| **Verde**    | 485B   |

-   Se pueden conectar varios dispositivos BUS en serie al panel híbrido. Para una comunicación óptima de los dispositivos de línea BUS conectados, asegúrese de que los interruptores de puente de resistencia terminal del primer dispositivo (generalmente el panel híbrido) y del último dispositivo BUS en una línea BUS estén configurados en ON para que sirvan como resistencias de terminación. Asegúrese de habilitar solo los 2 interruptores de puente antes mencionados y no configurar los interruptores de puente en ON para ningún otro dispositivo BUS intermedio.

_\\<NOTE>_

2

-   -   El diseño enchufable de los bloques de terminales BUS mejora la eficiencia de la instalación. Antes de realizar el cableado, puede retirar los bloques de terminales de la placa PCB para facilitar su uso y enchufarlos nuevamente después del cableado.
    -   Después de desconectar el terminal, al volver a instalarlo en la placa, asegúrese de instalar el terminal en la misma dirección para evitar posibles peligros.
-   Las conexiones incorrectas provocarán fallas o mal funcionamiento. Inspeccione el cableado y asegúrese de que las conexiones sean adecuadas antes de aplicar energía.

![](<.gitbook/assets/14 (47).png>)

-   _**Empezando**_

**Paso 1**Conecte el detector al Panel. Luego, encienda el panel y el detector de humo también se encenderá.

**Paso 2**Después de suministrar energía al detector de humo, emitirá 2 pitidos cortos y comenzará**calentar durante 1 minuto**. El LED rojo parpadeará cada 2 segundos.**.**

**Paso 3.**Cuando el detector de humo complete el calentamiento, emitirá un pitido para indicar que ha entrado**modo de calibración**. El modo de calibración dura**1 minuto**(Si la calibración falla, el detector de humo volverá a intentar la calibración, el modo de calibración durará 9 minutos como máximo). El LED rojo seguirá parpadeando cada dos segundos durante la calibración.

**Etapa 4.**Cuando se complete la calibración, el detector de humo emitirá 2 pitidos cortos y apagará el LED para volver al modo normal._\\<NOTE>_

![](<.gitbook/assets/15 (44).png>)

-   Si la calibración falla, el detector de humo emitirá un pitido continuo. Apague el detector de humo y luego vuelva a encenderlo para volver a intentar desde el paso 1.

Una vez completado con éxito el proceso de calentamiento y calibración, puede continuar con el aprendizaje.

**Paso 5.**Coloque el panel de control en**modo de aprendizaje**.

**Paso 6**El detector de humo será detectado si está correctamente conectado al Panel Híbrido.

**Paso 7.**Haga clic en "**Agregar**”para incluir el detector de humo detectado en el Panel de control.

![](<.gitbook/assets/16 (49).png>)

-   _**Identificación**_

La función "Identificar" se utiliza para localizar un dispositivo BUS específico en el sistema cableado BUS. Esta función es útil para distinguir qué dispositivo es cuál, especialmente en una instalación grande donde se incluyen numerosos dispositivos BUS.

Para ubicar el detector de humo cableado en el sistema BUS:

**Paso 1.**En la página web del Panel híbrido, haga clic en "Identificar" debajo de la lista de dispositivos después de la entrada de la columna del dispositivo del SD-32-BUS.

**Paso 2.**Si el detector de humo con cable recibe la señal del panel híbrido, la página web mostrará un mensaje de éxito y el indicador LED rojo del detector de humo con cable parpadeará 10 veces para indicarle al usuario dónde está.

![](<.gitbook/assets/17 (39).png>)

_\\<NOTE>_

-   -   -   Si se muestra un mensaje de tiempo de espera en la página web, significa que el detector de humo con cable no recibió la señal del panel. Verifique si el SD-32-BUS está conectado correctamente al panel dentro de la distancia de cableado adecuada.
-   _**Prueba de caminata**_
    -   Para asegurarse de que el detector de humo con cable pueda comunicarse con el panel después de su aprendizaje, coloque el panel de control en modo de prueba de caminata y presione el botón de prueba en SD-32-BUS para transmitir una señal de prueba al panel de control.
    -   Cuando el panel reciba la señal de prueba, emitirá un pitido y mostrará la información del detector de humo con cable en la parte superior de la lista de dispositivos.

![](<.gitbook/assets/18 (49).png>)![](<.gitbook/assets/19 (48).png>)

_\\<NOTE>_

-   -   Si no hay respuesta del Panel después de presionar el botón de prueba, significa que el Panel no recibió la señal de prueba del dispositivo.

Verifique si el detector de humo está conectado correctamente al panel dentro de la distancia de cableado adecuada.

-   _**Recalibración**_

![](<.gitbook/assets/20 (35).png>)

Como las condiciones de funcionamiento del detector de humo pueden variar después de haber sido instalado durante algún tiempo, es posible que desees recalibrar el Smoke 3.

Detector para tomar un nuevo valor umbral de detección de humo y garantizar un rendimiento óptimo del detector de humo. Para hacer esto:

-   Mantenga presionado el botón de prueba durante 20 segundos y suéltelo cuando el detector de humo emita 3 pitidos. El dispositivo comenzará la calibración y el LED rojo parpadeará cada 2 segundos para indicarlo.
-   El proceso de calibración dura**1 minuto**(Si la calibración falla, el detector de humo volverá a intentar la calibración, el modo de calibración durará 9 minutos como máximo).
-   Cuando finalice la calibración, el detector de humo emitirá un pitido de dos tonos. El LED rojo dejará de parpadear para indicar que ha vuelto al modo normal.
-   Si la calibración falla, el detector de humo emitirá un pitido continuo y el LED naranja parpadeará cada segundo. Apague el detector de humo y luego vuelva a encenderlo para reiniciar el detector de humo.

**Mantenimiento y limpieza**

El mantenimiento y la limpieza regulares ayudarán a mantener su detector de humo en buen estado de funcionamiento.

-   Pruebe el detector de humo semanalmente para verificar que los sonidos de la alarma y los indicadores estén funcionando correctamente.
-   Limpie el detector de humo al menos una vez cada 6 meses.
    -   Aspire suavemente la suciedad, el polvo y las pequeñas partículas acumuladas en la cámara y las ranuras de detección de humo.
    -   Limpie la carcasa pasándola bien con un paño húmedo y séquela. No deje entrar agua dentro de la alarma.
    -   Nunca utilice agentes de limpieza, detergentes o disolventes en el detector.
-   Evite rociar ambientadores, lacas para el cabello u otros aerosoles cerca del detector de humo.
-   No pinte ni modifique el detector bajo ninguna circunstancia.

**Vencimiento**

El detector de humo tiene una vida útil máxima de**10 años**desde la fecha de instalación. Debe reemplazar el detector de humo inmediatamente después de 10 años de servicio.

Se recomienda escribir la fecha de "Reemplazo antes de" (10 años a partir de la fecha de instalación) en la parte posterior del detector antes de la instalación.

**Instalación**

_**Guía de instalación**_

 Se recomienda que el sitio de instalación esté en el área central del techo.

 No ubique el detector en los siguientes lugares:

 La cocina: el humo de la cocina puede provocar una alarma no deseada.

 Cerca de un ventilador, una lámpara fluorescente o un equipo de aire acondicionado: las corrientes de aire que emiten pueden afectar la sensibilidad del detector.

-   Near ceiling beams or over a cabinet – stagnant air in these areas may affect the sensitivity of the detector.

 En el pico de un “**A**”tipo de marco de techo.

-   _**Montaje del detector de humo**_

**Paso 1.**Coloque el detector de humo en la ubicación de montaje deseada.

**Paso 2.**Saque la hoja de montaje incluida en el paquete. El tamaño de la imagen equivale al tamaño real del detector de humo y el diseño perforado permite retirarlo fácilmente después de la instalación.

**Paso 3.**Coloque la lámina ajustada contra el techo y utilice los cuatro orificios como plantilla para perforar orificios e insertar tacos de pared si es necesario.

Asegúrese de que los tacos de pared estén al ras con la superficie de montaje.

**Etapa 4.**Coloque el soporte de montaje encima de la hoja de montaje y atorníllelo a la pared.

**Paso 5.**El detector de humo tiene 4 ganchos en su tapa trasera. Sostenga el detector de humo con especial cuidado y alinee las 4 muescas del soporte de montaje con los 4 ganchos.

**Paso 6.**Gire en el sentido de las agujas del reloj para bloquear el gancho.

**Paso 7.**La instalación ya está completa. Ahora puedes arrancar la hoja de montaje.

4
