# VESTA 305

**Módulo de expansión de salidas programables serie WEPC-1**

**Introducción**

El módulo de expansión de salidas programables de la serie WEPC-1 está diseñado para proporcionar salidas programables para el panel híbrido. Conectado al Panel Híbrido mediante conexión BUS, incluye 4 salidas de relé programables, que se pueden utilizar en conjunto con paneles compatibles. La serie WEPC-1 está equipada con su propia carcasa, que tiene protección contra manipulaciones e indicadores de estado LED.

**El módulo de expansión de salidas programables de la serie WEPC-1 incluye los siguientes modelos:**

**WEPC-1**– Módulo de expansión de salida programable

**WEPC-1B**– Módulo de expansión de salida programable con batería recargable

**Identificar las piezas**

**Vista frontal****Vista trasera**

![](<.gitbook/assets/0 (7).jpeg>)

**Vista interna**

![](<.gitbook/assets/1 (9).jpeg>)

1

1.  **LED de encendido (rojo)**

Encendido: alimentado por un adaptador de corriente de 12 V o un panel híbrido.

Apagado: cuando la alimentación está apagada o cuando funciona con una batería recargable.

1.  **Zona 1~4 LED (rojo)**

El LED de zona correspondiente se iluminará cuando el interruptor de salida del relé de contacto seco esté encendido y la luz LED se apagará cuando se apague el interruptor.

1.  **LED de transmisión (rojo)**

Se ilumina cuando la conexión es normal entre el Módulo de Expansión y el Panel de Control.

1.  **Área de ruptura**

Cuando el módulo de expansión se retira a la fuerza de la ubicación de montaje, el área se separará y permitirá que se active el interruptor de manipulación.

1.  **Interruptor antisabotaje (para montaje en pared)**

El módulo de ampliación está protegido mediante un interruptor antisabotaje contra cualquier extracción no autorizada del lugar de montaje.

1.  **Orificios de montaje**
2.  **Orificio de cableado**
3.  **Terminal de conexión de batería (solo para WEPC-1B)**

Para conectar el paquete de baterías recargables a la PCB.

1.  **Interruptor de puente de resistencia terminal (J3)**

Cuando el módulo de expansión está conectado como el dispositivo BUS más lejano en una línea BUS, configure el puente de resistencia terminal del módulo de expansión y el interruptor de puente del primer dispositivo BUS (generalmente el panel híbrido) en ON para que sirvan como resistencias de terminación. Se mejorará la capacidad de comunicación de la línea BUS conectada.

-   Apague el puente quitando el enlace del puente o "estacionando" el enlace del puente en un pin.

![](<.gitbook/assets/2 (5).png>)

\-Encienda el puente apoyando el enlace del puente en ambos pines.

1.  **Paquete de batería recargable (solo para WEPC-1B)**
2.  **DC Jack**

Para conexión de alimentación conmutada de 12 V CC.

Para suministrar energía estable y suficiente para cargar las baterías recargables del WEPC-1B, se recomienda encarecidamente utilizar un adaptador de corriente conmutado de 12 V/1 A.

1.  **Terminal de BUS enchufable**
2.  **Terminal de salida PGM del relé de contacto seco**
3.  **Interruptor de manipulación (para cubierta de caja)**

El módulo de expansión está protegido por el interruptor antisabotaje contra cualquier apertura no autorizada de la caja. Siempre que se abra la tapa de la caja, se activará el interruptor de manipulación.

1.  **Botón de reinicio (reservado para uso interno)**
2.  **Botón de prueba**

Presione el botón de prueba para enviar una señal de prueba al Panel de control.

**Fuente de alimentación**

-   El módulo de expansión recibe energía del panel híbrido, que puede proporcionar una fuente de alimentación de 13,5 V al módulo de expansión. Además, se recomienda utilizar el adaptador de corriente externo (12 V) cuando se conecta a cargas que requieren un mayor consumo de energía.
-   Cuando se interrumpe y restablece el suministro de energía del adaptador, el módulo de expansión transmitirá una señal de falla de CA y una señal de restauración respectivamente al Panel de control.

2

**Paquete de batería recargable (solo para WEPC-1B)**

-   Para WEPC-1B, un paquete de baterías recargables Ni-MH está preinstalado en el módulo de expansión para servir como respaldo en caso de un corte de energía.
-   Conecte el paquete de baterías a la PCB manualmente para usarlo como fuente de energía de respaldo y/o para cargarlo automáticamente cuando se conecta la energía desde el adaptador o el panel híbrido. \\<Note>Antes de conectar el paquete de baterías, asegúrese de que la alimentación del conector CC y/o del terminal BUS esté apagada.

Se recomienda encarecidamente utilizar un adaptador de corriente conmutado de 12 V/1 A para suministrar energía estable y suficiente para cargar las baterías.

-   Cuando el paquete de baterías recargables tiene poca energía, el módulo de expansión transmitirá una señal de batería baja al panel de control. Cuando las baterías se hayan cargado, también transmitirá una señal de restauración de la batería al Panel de control.

**Protección contra manipulación**

La serie WEPC-1 tiene dos interruptores antisabotaje; cada uno viene con una función diferente.

-   El interruptor de manipulación para la cubierta de la caja está ubicado en la parte frontal del tablero. Está en posición normal cuando el caso está cerrado. La infracción de manipulación ocurre cuando se abre el caso donde se libera el interruptor de manipulación (sabotaje abierto).
-   El interruptor antisabotaje para montaje en pared está ubicado en la parte posterior del tablero. Está en posición normal cuando el módulo está bien montado en la pared. La infracción de manipulación ocurre cuando el módulo se retira a la fuerza de la ubicación de montaje, el área se separará y permitirá que se active el interruptor de manipulación.
-   El sabotaje se considera activado si cualquiera de los sabotaje se abre. El tamper sólo se considera restablecido cuando ambos tamper están en estado cerrado.

**Señal de supervisión**

-   Después de ser programado en el Panel de Control, el módulo de Expansión transmitirá automáticamente Señales de Supervisión cada 20 a 30 segundos.

**Conexión al Panel Híbrido**

-   Antes de realizar la conexión, asegúrese de que se haya desconectado la fuente de alimentación y que el interruptor de la batería del panel se haya deslizado a la posición APAGADO.
-   Para ayudar con las conexiones de cables, los bloques de terminales de cada módulo del sistema están codificados por colores.

| **Rojo**     | VDD    |
| ------------ | ------ |
| **Negro**    | Tierra |
| **Amarillo** | 485A   |
| **Verde**    | 485B   |

-   Para una comunicación óptima de la conexión por cable entre el panel de control y los dispositivos BUS conectados, asegúrese de que el interruptor de puente de comunicación del dispositivo BUS más alejado y el interruptor de puente J53 del panel de control estén configurados en ON para que sirva como resistencia terminal. Asegúrese de habilitar solo los 2 interruptores de puente antes mencionados y no configurar los interruptores de puente en ON para ningún otro dispositivo BUS intermedio.
-   La serie WEPC-1 se puede conectar y alimentar mediante el panel de control a través del terminal BUS o la alimentación externa a través del adaptador de 12 V. Si el módulo de expansión utiliza alimentación externa, asegúrese de omitir el terminal VDD rojo en el panel de control usando el conector de empalme Wago 221.
-   Las conexiones incorrectas provocarán fallas o un funcionamiento incorrecto. Inspeccione el cableado y asegúrese de que las conexiones sean adecuadas antes de aplicar energía.

3

-   El siguiente diagrama muestra cómo WEPC-1 está conectado y alimentado por el panel híbrido.

![](<.gitbook/assets/3 (9).jpeg>)

-   La siguiente es la conexión del WEPC-1B al panel híbrido, con el WEPC-1B alimentado por la fuente de alimentación externa.

![](<.gitbook/assets/4 (9).jpeg>)

4

_\\<NOTE>_

-   _Asegúrese de omitir el terminal VDD rojo en el panel de control utilizando el conector de empalme Wago 221 proporcionado. Conecte el terminal VDD al siguiente dispositivo BUS (VST-892-BUS como ejemplo) que esté alimentado por el Panel Híbrido._
-   _El diseño enchufable del terminal BUS mejora la eficiencia de la instalación. Antes de realizar el cableado, puede quitar los bloques de terminales del dispositivo para facilitar su uso y enchufarlos nuevamente después del cableado. Al volver a instalar los bloques de terminales en la placa, asegúrese de instalarlos en la misma dirección para evitar posibles peligros._

**Empezando**

Después de conectar la placa de expansión al panel híbrido y completar el cableado del dispositivo, continúe con el aprendizaje y la programación del sensor del interruptor de encendido.

-   _**Aprendiendo**_

**Paso 1.**Conecte el Módulo de Expansión al Panel de Control. Luego, encienda el Panel de control.**.**

**Paso 2.**Haga clic en "**Aprendiendo**”para ingresar a la página de aprendizaje.

**Paso 3.**Haga clic en "**Comenzar**”para ingresar al modo de aprendizaje.

**Etapa 4.**Hacer clic**"Agregar"**para incluir el módulo de expansión en el panel.

**Paso 5.**Si el módulo de expansión se aprende correctamente en el sistema, el dispositivo agregado se mostrará en la sección "Dispositivo aprendido". El tipo de dispositivo se mostrará como "Expansor".

-   _**Programación del sensor del interruptor de encendido**_

Después de agregar el módulo de expansión de salida programable, proceda a la programación del sensor del interruptor de alimentación.

**Paso 1.**Haga clic en Sensor cableado para ingresar a esta página web. Verá los expansores en la parte inferior de la página.

**Paso 2.**Haga clic en "Editar" al final de la entrada del expansor.

**Paso 3.**Seleccione y asigne el interruptor de salida para cada zona.

-   **Tipo**: Seleccione para activar el interruptor de encendido para cada zona en el menú desplegable Tipo. La configuración predeterminada es "Desactivada" y puede optar por asignar el interruptor de alimentación de salida del relé de contacto seco a una zona seleccionando "Interruptor de alimentación".

**Etapa 4.**Haga clic en "**DE ACUERDO**”para guardar los cambios cuando haya terminado. Alternativamente, haga clic en "**Rendimientos**t” para volver a ingresar toda la información.

**Paso 5.**Si el proceso es exitoso, la pantalla mostrará “**Actualizado con éxito.**”El interruptor de encendido se asignará a un área y zona específicas.

**Paso 6.**Haga clic en "Control PSS" en Administración de dispositivos y accederá**Sensor del interruptor de encendido**Página web.

**Paso 7.**En esta página, puede encender o apagar el interruptor de encendido de cada zona.

**Paso 8.**También puede editar la configuración y la información de su dispositivo. Haga clic en "**Editar**”al final de la entrada del dispositivo y haga clic en “Aceptar” para guardar los cambios cuando haya terminado.

-   _**Identificación**_

La función "Identificar" se utiliza para localizar un dispositivo BUS específico en el sistema cableado BUS. Esta función es útil para distinguir qué dispositivo es cuál, especialmente en una instalación grande donde se incluyen numerosos dispositivos BUS.

Para ubicar el módulo de expansión de salidas programables en el sistema BUS:

**Paso 1.**En la página web del Panel híbrido, haga clic en "Identificar" debajo de la lista de dispositivos después de la entrada de la columna del dispositivo del Expansor.

![](<.gitbook/assets/5 (8).png>)

5

**Paso 2.**Si el módulo de expansión de salida programable recibe la señal del panel híbrido, la página web mostrará un mensaje de éxito y el indicador LED de alimentación del WEPC-1(B) parpadeará 10 veces para indicarle al usuario dónde está.

_\\<NOTE>_

-   -   Si se muestra un mensaje de tiempo de espera en la página web, significa que el Módulo de expansión de salidas programables no recibió la señal del panel.

Verifique si WEPC-1(B) está conectado correctamente al panel dentro de la distancia de cableado adecuada.

-   _**Prueba de caminata**_
-   Para asegurarse de que el módulo de expansión de salidas programables pueda comunicarse con el

Una vez aprendido el panel, coloque el panel de control en modo de prueba de recorrido y presione el botón de prueba en WEPC-1(B) para transmitir una señal de prueba al panel de control.

-   Cuando el Panel reciba la señal de prueba, emitirá un pitido y mostrará la información del WEPC-1(B) en consecuencia en la parte superior de la lista de dispositivos.

_\\<NOTE>_

-   Si no hay respuesta del Panel después de presionar el botón de prueba, significa que el Panel no recibió la señal de prueba del dispositivo.

Verifique si WEPC-1(B) está conectado correctamente al panel dentro de la distancia de cableado adecuada.

**Cableado PGM**

-   El puerto PGM puede servir como salida de relé de contacto seco.
-   Por defecto, N.C y COM están configurados como en cortocircuito.
-   Puede configurar el N.O. y COM como cortocircuito encendiendo el interruptor de encendido a través de la página web de programación.

**Configuración predeterminada****Configuración por página de programación**

![](<.gitbook/assets/6 (7).jpeg>)![](<.gitbook/assets/7 (7).jpeg>)

**Cómo montar el módulo de expansión de salidas programables**

![](<.gitbook/assets/8 (6).jpeg>)

El módulo de expansión de salidas programables se puede montar en la pared siguiendo los pasos a continuación:

-   Afloje el tornillo de fijación inferior y retire la cubierta frontal.
-   Usando los orificios de la placa de expansión de salidas programables como plantilla, marque los orificios de perforación en la pared.
-   Taladre agujeros en el lugar marcado en la pared. Inserte tacos de pared si es necesario.
-   Atornille la base en la ubicación de montaje.
-   Vuelva a colocar la cubierta frontal y apriete los tornillos de fijación inferiores.

6
