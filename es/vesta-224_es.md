# VESTA 224

**Módulo de expansión de la serie WEZC-8**

**Introducción**

Esta guía de instalación se utilizará junto con el manual del usuario del panel híbrido al que está conectado el modelo de la serie WEZC-8.

El módulo de expansión de la serie WEZC-8 está diseñado para admitir la expansión del panel híbrido. Conectado al Panel Híbrido mediante conexión BUS, puede proporcionar la expansión de hasta 8 zonas en los paneles compatibles. La serie WEZC-8 está equipada con su propia carcasa, que tiene protección contra manipulaciones e indicadores de estado LED.

**El módulo de expansión de la serie WEZC-8 incluye los siguientes modelos:**

**WEZC-8**– Módulo de Expansión con 8 zonas cableadas

**WEZC-8B**– Módulo de Expansión con 8 zonas cableadas y batería recargable

**Identificar las piezas**

**Vista frontal****Vista trasera**

![](<.gitbook/assets/0 (6).jpeg>)

**Vista interna**

![](<.gitbook/assets/1 (8).jpeg>)

1

1.  **LED de encendido (rojo)**

Encendido: alimentado por un adaptador de corriente de 12 V o un panel híbrido.

Apagado: cuando la alimentación está apagada o cuando funciona con una batería recargable.

1.  **Zona 1~8 LED (rojo)**

El LED de zona correspondiente se iluminará cuando ciertas zonas estén activadas o tengan una condición de manipulación o enmascaramiento.

1.  **LED de transmisión (rojo)**

Se ilumina cuando la conexión o transmisión de señal es normal entre el Módulo de Expansión y el Panel de Control.

1.  **Área de ruptura**

Cuando el módulo de expansión se retira a la fuerza de la ubicación de montaje, el área se desprenderá, lo que provocará que se active el interruptor de manipulación.

1.  **Interruptor antisabotaje (para montaje en pared)**

El módulo de ampliación está protegido por el interruptor antisabotaje contra cualquier extracción no autorizada del lugar de montaje.

1.  **Orificios de montaje**
2.  **Orificio de cableado**
3.  **Terminal de conexión de batería (solo para WEZC-8B)**

Para conectar el paquete de baterías recargables a la PCB.

1.  **Paquete de batería recargable (solo para WEZC-8B)**
2.  **Interruptor de puente de resistencia terminal (J3)**

Cuando el módulo de expansión está conectado como el dispositivo BUS más lejano en una línea BUS, configure el puente de resistencia terminal del módulo de expansión y el interruptor de puente del primer dispositivo BUS (generalmente el panel híbrido) en ON para que sirvan como resistencias de terminación. Se mejorará la capacidad de comunicación de la línea BUS conectada.

![](<.gitbook/assets/2 (9).jpeg>)

Apague el puente quitando el enlace del puente o "estacionando" el enlace del puente en un pin.

![](<.gitbook/assets/3 (8).jpeg>)

Encienda el puente apoyando el enlace del puente en ambos pines.

**11. Conector CC**

Para conexión de alimentación conmutada de 12 V CC.

Para suministrar energía estable y suficiente para cargar las baterías recargables del WEZC-8B, se recomienda encarecidamente utilizar un adaptador de corriente conmutado de 12 V/1 A.

1.  **Terminal de BUS enchufable**
2.  **Terminal de zona y terminal de salida de voltaje auxiliar de 13,5 V y terminal GND**

El voltaje típico es de 13,5 V y puede variar según el voltaje de salida del terminal.

**14. Botón de prueba**

Presione el botón de prueba para enviar una señal de prueba al Panel de control.

1.  **Botón de reinicio (reservado para uso interno)**
2.  **Interruptor de manipulación (para cubierta de caja)**

El módulo de expansión está protegido por el interruptor antisabotaje contra cualquier apertura no autorizada de la caja. Siempre que se abra la tapa de la caja, se activará el interruptor de manipulación.

**Fuente de alimentación**

-   El módulo de expansión recibe energía del panel híbrido, que puede proporcionar una fuente de alimentación de 13,5 V al módulo de expansión. Además, se recomienda utilizar el adaptador de corriente externo (12 V) cuando se conecta a cargas que requieren un mayor consumo de energía.
-   Cuando se interrumpe y restablece el suministro de energía del adaptador, el módulo de expansión transmitirá una señal de falla de CA y una señal de restauración respectivamente al Panel de control.

2

**Paquete de batería recargable (solo para WEZC-8B)**

-   Para WEZC-8B, un paquete de baterías recargables Ni-MH está preinstalado en el módulo de expansión para servir como respaldo en caso de un corte de energía.
-   Conecte el paquete de baterías a la PCB manualmente para usarlo como fuente de energía de respaldo y/o para cargarlo automáticamente cuando se conecta la energía desde el adaptador o el panel híbrido. \\<Note>Antes de conectar el paquete de baterías, asegúrese de que la alimentación del conector CC y/o del terminal BUS esté apagada.

Se recomienda encarecidamente utilizar un adaptador de corriente conmutado de 12 V/1 A para suministrar energía estable y suficiente para cargar las baterías.

-   Cuando el paquete de baterías recargables tiene poca energía, el módulo de expansión transmitirá una señal de batería baja al panel de control. Cuando las baterías se hayan cargado, también transmitirá una señal de restauración de la batería al Panel de control.

**Protección contra manipulación**

La serie WEZC-8 tiene dos interruptores antisabotaje; cada uno viene con una función diferente.

-   El interruptor de manipulación para la cubierta de la caja está ubicado en la parte frontal del tablero. Está en posición normal cuando el caso está cerrado. La infracción de manipulación ocurre cuando se abre el caso donde se libera el interruptor de manipulación (sabotaje abierto).
-   El interruptor antisabotaje para montaje en pared está ubicado en la parte posterior del tablero. Está en posición normal cuando el módulo está bien montado en la pared. La infracción de manipulación ocurre cuando el módulo se retira a la fuerza de la ubicación de montaje; el área de separación se separará, lo que provocará que se active el interruptor de manipulación.
-   El sabotaje se considera activado si cualquiera de los sabotaje se abre. El tamper sólo se considera restaurado cuando ambos tamper están en estado cerrado.

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

-   Para una comunicación óptima de los dispositivos BUS conectados, asegúrese de que el dispositivo BUS más lejano

El interruptor de puente de resistencia terminal y el interruptor de puente J53 del panel de control están configurados en ON para servir como resistencias terminales. Asegúrese de habilitar solo los 2 interruptores de puente antes mencionados y no configurar los interruptores de puente en ON para ningún otro dispositivo BUS intermedio.

-   La serie WEZC-8 se puede conectar y alimentar mediante el panel de control a través del terminal BUS o la alimentación externa a través del adaptador de 12 V. Si el módulo de expansión utiliza alimentación externa, asegúrese de omitir el terminal VDD rojo en el panel de control utilizando el conector de empalme Wago 221.

3

-   Lo siguiente es el WEZC-8 conectado y alimentado por el panel híbrido:

![](<.gitbook/assets/4 (8).jpeg>)

-   La siguiente es la conexión del WEZC-8B al panel híbrido, con el WEZC-8B alimentado por una fuente de alimentación externa.

![](<.gitbook/assets/5 (6).jpeg>)

4

_Nota:_

-   _Asegúrese de omitir el terminal VDD rojo en el panel de control utilizando el conector de empalme Wago 221 proporcionado. Conecte el terminal VDD al siguiente dispositivo BUS (VST-892-BUS como ejemplo) que esté alimentado por el Panel Híbrido._
-   _El diseño enchufable de los bloques de terminales BUS mejora la eficiencia de la instalación. Antes de realizar el cableado, puede quitar los bloques de terminales del dispositivo para facilitar su uso y enchufarlos nuevamente después del cableado. Al volver a instalar los bloques de terminales en la placa, asegúrese de instalarlos en la misma dirección para evitar posibles peligros._
-   _Las conexiones incorrectas provocarán fallas o un funcionamiento incorrecto. Inspeccione el cableado y asegúrese de que las conexiones sean adecuadas antes de aplicar energía._

**Cableado de zona**

-   Las 8 zonas se pueden cablear para supervisar dispositivos NC (normalmente cerrados) o NO (normalmente abiertos), por ejemplo, sensores PIR, contactos de puertas, detectores de humo, sensores de agua, sensores de incendio, sensores de CO, detectores de gas, detectores de calor y rotura de cristales. detectores, etc
-   Conecte dispositivos cableados a cualquier terminal de zona.
-   Calibre del cable: Mínimo 22 AWG, máximo 19 AWG. No utilice cables blindados.
-   Las zonas cableadas admiten configuración de bucle de fin de línea único (SEOL) y doble fin de línea (DEOL), con valores de resistencia seleccionables de 1 KΩ, 2,2 KΩ, 3,74 KΩ, 4,7 KΩ, 5,6 KΩ, 6,8 K Ω , 8,2 KΩ, 10 KΩ ohmios.
-   El bucle triple de fin de línea (TEOL) se puede configurar en diferentes combinaciones: 4,7 KΩ, 6,8 KΩ,

12 KΩ (selección de valor de resistencia: 6,8 K), 4,7 KΩ/5,6 KΩ, 4,7 KΩ, 2,2 KΩ/3 KΩ (valor de resistencia

selección: 4,7 K), o 4,7 KΩ/5,6 KΩ, 5,6 KΩ, 2,2 KΩ/3 KΩ (selección del valor de resistencia: 5,6 K).

-   Instale las resistencias al final de cada bucle de zona lejos del panel de control. El Panel detectará si el circuito está seguro, abierto o en cortocircuito.
-   Para un bucle NC, tenga una resistencia EOL en serie con el bucle.
-   Para un bucle NO, tenga una resistencia EOL en paralelo (a través) del bucle. Consulte los siguientes diagramas para ver ejemplos de cableado.
-   Si se cambia el método de cableado de una zona, asegúrese de apagar y volver a encender el sistema para evitar activar la alarma.

Consulte los siguientes diagramas de los bucles 1 a 10 para ver ejemplos de cableado.

**NO/NC Wiring**

El panel puede detectar alarmas para los dispositivos NO o NC correspondientes a través de circuitos abiertos, seguros o en cortocircuito.

_\\<NOTE>_

 No hay resistencia EOL en los bucles 1 y 2.

**NO/NC Wiring**

1.2.

![](<.gitbook/assets/6 (6).jpeg>)![](<.gitbook/assets/7 (6).jpeg>)

5

**Cableado de resistencia de fin de línea única**

3.4.

![](<.gitbook/assets/8 (7).png>)

5.6.

![](<.gitbook/assets/9 (10).png>)

**Cableado de resistencia de doble fin de línea**

7. 8.

![](<.gitbook/assets/10 (11).png>)

**Cableado de triple EOL**

9.10.

![](<.gitbook/assets/11 (6).png>)

6

**Empezando**

Después de conectar la placa de expansión al panel híbrido y completar el cableado del dispositivo, proceda al aprendizaje y programación de zonas.

-   _**Aprendiendo**_

**Paso 1.**Conecte el Módulo de Expansión al Panel de Control. Luego, encienda el Panel de control.**.**

**Paso 2.**Haga clic en -**Aprendiendo**‖ para ingresar a la página de aprendizaje.

**Paso 3.**Haga clic en -**Comenzar**‖ para ingresar al modo de aprendizaje.

**Etapa 4.**Hacer clic**"Agregar"**para incluir el módulo de expansión en el panel.

**Paso 5.**Si el módulo de expansión se aprende exitosamente en el sistema, el dispositivo agregado se mostrará en la sección "Dispositivo aprendido". El tipo de dispositivo se mostrará como "Expansor".

-   _**Programación de zonas cableadas**_

Después de agregar el módulo de expansión, proceda a la programación de la zona cableada.

**Paso 1.**Haga clic en Sensor cableado para ingresar a esta página web. Verá los expansores en la parte inferior de la página.

**Paso 2.**Haga clic en "Editar" al final de la entrada del ampliador.

**Paso 3.**Edite el tipo de sensor cableado, cableado de zona y resistencia EOL para cada zona.

-   **Tipo**: Seleccione el tipo de sensor cableado para cada zona en el menú desplegable.
-   **Bucle**: Seleccione el número que corresponda al cableado de zona para cada zona en el menú desplegable. En esta página web, hay diagramas de cableado a continuación para su referencia.
-   **Resistor**: Seleccione la resistencia para el cableado de zona.
-   **Estado**: Aquí se mostrará el estado de cada zona (Restaurar, Sabotaje o Activación).

**Etapa 4.**Haga clic en ―**DE ACUERDO**‖ para guardar los cambios cuando haya terminado. Alternativamente, haga clic en ―**Rendimientos**t‖ para volver a ingresar toda la información.

**Paso 5.** If the process is successful, the screen will display ―**Actualizado con éxito.**‖ El sensor se asignará a un área y zona específicas. Para editar la configuración o la información del dispositivo, haga clic en ―**Editar**‖ al final de la entrada del dispositivo.

**Paso 6.**entraras**Editar dispositivo**Página web.

**Paso 7.**Edite la configuración y la información de su dispositivo. Haga clic en "Aceptar" para guardar los cambios cuando haya terminado.

-   _**Identificación**_

La función "Identificar" se utiliza para localizar un dispositivo BUS específico en el sistema cableado BUS. Esta función es útil para distinguir qué dispositivo es cuál, especialmente en una instalación grande donde se incluyen numerosos dispositivos BUS.

Para ubicar el Módulo de Expansión en el sistema BUS:

**Paso 1.**En la página web del Panel híbrido, haga clic en "Identificar" debajo de la lista de dispositivos después de la entrada de la columna de dispositivos del expansor.

![](<.gitbook/assets/12 (9).png>)

**Paso 2.**Si el Módulo de Expansión recibe la señal del Panel Híbrido, la página web mostrará un mensaje de éxito y el indicador LED de encendido del Módulo de Expansión parpadeará 10 veces para indicarle al usuario dónde está.

_\\<NOTE>_

-   Si se muestra un mensaje de tiempo de espera en la página web, significa que el Módulo de Expansión no recibió la señal del Panel.

Verifique si el módulo de expansión está conectado correctamente al panel dentro de la distancia de cableado adecuada.

7

-   _**Prueba de caminata**_
-   Para asegurarse de que el Módulo de Expansión pueda comunicarse con el Panel después de su

aprendido, coloque el panel de control en modo de prueba de caminata y presione el botón de prueba en WEZC-8 para transmitir una señal de prueba al panel de control.

-   Cuando el Panel reciba la señal de prueba, emitirá un pitido y mostrará la información del Módulo de Expansión correspondiente en la parte superior de la lista de dispositivos.

_\\<NOTE>_

-   Si no hay respuesta del Panel después de presionar el botón de prueba, significa que el Panel no recibió la señal de prueba del dispositivo.

Verifique si el módulo de expansión está conectado correctamente al panel dentro de la distancia de cableado adecuada.

**Cómo montar el módulo de expansión**

El módulo de expansión se puede montar en la pared. Siga los pasos a continuación para montarlo:

-   Afloje el tornillo de fijación inferior y retire la cubierta frontal.
-   Usando los orificios del módulo de expansión como plantilla, marque los orificios en la pared.
-   Taladre agujeros en el lugar marcado en la pared. Inserte tacos de pared si es necesario.
-   Atornille la base en la ubicación de montaje.
-   Vuelva a colocar la cubierta frontal y apriete los tornillos de fijación inferiores.

![](<.gitbook/assets/13 (3).jpeg>)

8
