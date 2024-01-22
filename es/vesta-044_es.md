# VESTA 044

-   Control remoto universal por infrarrojos UPIC-5ZW
-   Introducción

UPIC5-ZW es un control remoto por infrarrojos Z-Wave. Está diseñado para operar sus electrodomésticos transmitiendo señal IR. El control remoto por infrarrojos es capaz de aprender la señal de infrarrojos transmitida desde el control remoto del aparato. Después de aprender la señal, puede controlar remotamente el control remoto IR a través de la red Z-Wave para enviar la señal al aparato sin usar el control remoto manualmente.

El UPIC-5ZW es un dispositivo habilitado para Z-Wave y es totalmente compatible con cualquier red habilitada para Z-Wave.

Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. Al aprovechar la red de malla Z-Wave, los comandos se pueden enrutar a su destino a través de productos Z-Wave intermediarios que “escuchan”.

La serie de controles remotos por infrarrojos UPIC5 Z-Wave incluye los siguientes modelos:

**UPIC5-ZW**Control remoto por infrarrojos

**UPIC5-ZW-OTA**Control remoto por infrarrojos con función de actualización de firmware inalámbrica

-   Identificación de piezas

**1. Ojo de infrarrojos**

![](<.gitbook/assets/0 (10).jpeg>)

Transmite señal IR a los electrodomésticos.

**2. Botón Función/IR**

Presione el botón 3 veces en 1,5 segundos para enviar un código de aprendizaje.

Mantenga presionado el botón durante 10 segundos para restablecer los valores de fábrica.

Mantenga presionado el botón durante 3 segundos para ingresar al modo de aprendizaje de IR.

Presione el botón una vez para transmitir la señal/salir del modo de aprendizaje IR.

**3. LED de onda Z**

Parpadea una vez: el control remoto por infrarrojos está transmitiendo una señal

**4. LED indicador de infrarrojos**

Parpadeo lento: control remoto por infrarrojos en modo de aprendizaje por infrarrojos.

Quick Flash: el control remoto por infrarrojos recibe una señal de infrarrojos en el modo de aprendizaje o está transmitiendo una señal de infrarrojos

Parpadea cada medio segundo: los datos IR se borran

Apagado: el control remoto por infrarrojos está almacenando la señal de infrarrojos recibida en el modo de aprendizaje.

– El control remoto por infrarrojos está en modo inactivo.

**5. Receptor de señal de infrarrojos**

**6. Puente de potencia de transmisión IR baja (JP1)**

**Puente apagado**

si se elimina el enlace del puente o "**estacionado**”en un alfiler.

**Puente encendido**

El enlace del puente se inserta conectando los dos pines.

![](<.gitbook/assets/1 (17).png>)![](<.gitbook/assets/2 (20).png>)

Puente ON – Potencia de transmisión IR configurada en Baja.**(Predeterminado de fábrica)**

Puente APAGADO – Deseleccionado.

**7. Puente de potencia de transmisión IR alta (JP2)**

**Puente apagado**

si se elimina el enlace del puente o "**estacionado**”en un alfiler.

**Puente encendido**

El enlace del puente se inserta conectando los dos pines.

![](<.gitbook/assets/3 (19).png>)![](<.gitbook/assets/4 (18).png>)

Puente ON – Potencia de transmisión IR configurada en Alta.

Puente APAGADO – Deseleccionado.

**NOTA IMPORTANTE: Los puentes JP1 y JP2 NO PUEDEN configurarse en ON al mismo tiempo**

**8. Juego de interruptores DIP 1**

Para configurar el tipo de aparato

**9. Juego de interruptores DIP 2**

Para aprender y probar la señal IR

**10. Compartimento de la batería**

**11. Soporte giratorio para montaje en pared (opcional)**

-   Características
-   _Detección de batería y batería baja_

El control remoto por infrarrojos utiliza dos baterías de litio de 1,5 V como fuente de alimentación. Cuenta con la función de detección de batería baja. Cuando se detecta un voltaje de batería bajo, el control remoto por infrarrojos transmitirá una señal de batería baja al coordinador en la red Z-Wave.

El control remoto por infrarrojos informará su porcentaje de batería al panel de control respectivamente al 100%, 75%, 50%, 25%. El control remoto por infrarrojos también puede detectar el estado de batería baja. Cuando se detecta un voltaje de batería bajo (25%), la señal de batería baja se enviará al Panel de control junto con la transmisión de señal regular para que el Panel de control muestre el estado correspondiente.

-   _Agregar dispositivo (inclusión)_

Este producto se puede incluir y operar en cualquier red Z-Wave con otros dispositivos certificados Z-Wave de otros fabricantes y/u otras aplicaciones. Todos los nodos de la red que no funcionan con baterías actuarán como repetidores independientemente del proveedor para aumentar la confiabilidad de la red.

-   Inserte las pilas para encender el control remoto por infrarrojos.
-   Coloque la puerta de enlace Z-Wave o el panel de control en**Inclusión**o**Aprendiendo**modo (consulte el manual de la puerta de enlace Z-Wave o del panel de control).
-   En 1,5 segundos, presione el botón Función/IR 3 veces.
-   Consulte el manual de funcionamiento de la puerta de enlace Z-Wave o del panel de control para completar el proceso de aprendizaje.
-   Si el sensor ya ha sido**incluido**(aprendido) en otra puerta de enlace/panel de control Z-Wave, o si el sensor no se puede aprender en la puerta de enlace/panel de control Z-Wave actual, exclúyalo primero (consulte_**Exclusión**_) antes de intentar**incluir**en el panel de control/puerta de enlace Z-Wave actual.
-   _Eliminación del dispositivo (exclusión)_

El control remoto por infrarrojos debe retirarse de la red Z-Wave existente antes de incluirlo en otra. Hay dos métodos disponibles para excluir un dispositivo:

**Modo de exclusión**

-   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de exclusión**(consulte el manual de la puerta de enlace Z-Wave o del panel de control).
-   En 1,5 segundos, presione el botón Función/IR 3 veces y el control remoto IR se eliminará de la red Z-Wave.

**Restablecimiento de fábrica**

_(Utilice el restablecimiento de fábrica únicamente cuando falte el panel de control/puerta de enlace de la red o no esté operativo)._

-   Mantenga presionado el botón Función/IR del control remoto IR durante 10 segundos para restablecer los valores de fábrica.

_**\\<NOTE>**_

-   El restablecimiento de fábrica del control remoto por infrarrojos lo restaurará a la configuración predeterminada de fábrica (excluido de la red Z-Wave). La puerta de enlace o el panel de control Z-Wave seguirán manteniendo su configuración Z-Wave. Consulte el manual de la puerta de enlace o del panel de control sobre cómo eliminar la configuración Z-Wave del control remoto por infrarrojos.
-   _Modo de suspensión Z-Wave_
-   El control remoto por infrarrojos entrará en el modo de suspensión Z-Wave (para conservar energía) después de despertarse durante un breve período de tiempo (~10 segundos). Mientras está en el modo de suspensión Z-Wave, las puertas de enlace o los paneles de control Z-Wave no pueden enviar comandos al control remoto por infrarrojos.
-   Aprendizaje y prueba de señales IR

Para utilizar el control remoto por infrarrojos para controlar su electrodoméstico, el control remoto por infrarrojos primero debe aprender de la señal de infrarrojos enviada desde el control remoto del electrodoméstico. Siga las instrucciones a continuación para completar el proceso de aprendizaje.**Mantenga el receptor de infrarrojos alejado de la iluminación directa o la luz solar durante el proceso de aprendizaje para evitar interferencias.**

-   _**Aprendiendo**_

**Paso 1. Ingrese al modo de aprendizaje de infrarrojos**

1.  Siga las instrucciones en**Configuración de red Z-Wave**sección para unir el control remoto por infrarrojos a su red Z-Wave.
2.  Asegúrese de que todos los interruptores en el bloque de interruptores DIP estén configurados en**APAGADO**posición.
3.  Mantenga presionado el botón Función/IR durante 3 segundos y suéltelo cuando el LED IR comience a parpadear.
4.  El LED IR comenzará a parpadear lentamente para indicar que el control remoto IR ahora está ingresando al modo de aprendizaje IR.

EN

![](<.gitbook/assets/5 (4) (1).jpeg>)

APAGADO

**Paso 2. Seleccione el tipo de dispositivo**

El transmisor de infrarrojos puede aprender hasta 5 conjuntos de señales de infrarrojos para 5 aparatos diferentes.

Antes de comenzar a aprender, seleccione el número del aparato con el conjunto de interruptores DIP 1 antes de continuar con el aprendizaje de las señales. La señal IR aprendida se asignará al número de aparato seleccionado.

Seleccione el tipo de aparato de acuerdo con la siguiente tabla del conjunto de interruptores DIP 1. Para facilitar el reconocimiento y la operación desde la puerta de enlace/panel de control Climax Z-Wave, a cada tipo de dispositivo se le ha asignado un nombre para mostrar en la interfaz del panel de control; le sugerimos que aprenda en las señales IR según los tipos de aparatos mostrados.

| Cambiar 1 | Cambiar 2 | Cambiar 3 | Cambiar 4 | Cambiar 5 | Cambiar 6 | Tipo de aparato                 |
| --------- | --------- | --------- | --------- | --------- | --------- | ------------------------------- |
| EN        | APAGADO   | APAGADO   | APAGADO   | APAGADO   | APAGADO   | **Tipo 1 (Aire Acondicionado)** |
| X         | EN        | APAGADO   | APAGADO   | APAGADO   | APAGADO   | **Tipo 2 (Televisión)**         |
| X         | X         | EN        | APAGADO   | APAGADO   | APAGADO   | **Tipo 3 (audio doméstico)**    |
| X         | X         | X         | EN        | APAGADO   | APAGADO   | **Tipo 4 (decodificador)**      |
| X         | X         | X         | X         | EN        | APAGADO   | **Tipo 5 (Otros)**              |

"X" significa que la ubicación de este interruptor no tiene efecto en la selección del electrodoméstico.

**Ejemplo:**

1.  Para seleccionar aire acondicionado, deslice el interruptor 1 a ON y el interruptor 2-6 a OFF.
2.  Para seleccionar Televisión, deslice el interruptor 2 a ON y el interruptor 3-6 a OFF, ignore la posición del interruptor 1.

**Paso 3. Aprenda los datos de infrarrojos**

Cada tipo de aparato puede aprender hasta 8 señales IR, seleccionadas con el conjunto de interruptores DIP 2.

| Cambiar 1 | Cambiar 2 | Cambiar 3 | Cambiar 4 | Cambiar 5 | Cambiar 6 | Cambiar 7 | Cambiar 8 | Señal infrarroja |
| --------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- | ---------------- |
| EN        | APAGADO   | APAGADO   | APAGADO   | APAGADO   | APAGADO   | APAGADO   | APAGADO   | **1**            |
| X         | EN        | APAGADO   | APAGADO   | APAGADO   | APAGADO   | APAGADO   | APAGADO   | **2**            |
| X         | X         | EN        | APAGADO   | APAGADO   | APAGADO   | APAGADO   | APAGADO   | **3**            |
| X         | X         | X         | EN        | APAGADO   | APAGADO   | APAGADO   | APAGADO   | **4**            |
| X         | X         | X         | X         | EN        | APAGADO   | APAGADO   | APAGADO   | **5**            |
| X         | X         | X         | X         | X         | EN        | APAGADO   | APAGADO   | **6**            |
| X         | X         | X         | X         | X         | X         | EN        | APAGADO   | **7**            |
| X         | X         | X         | X         | X         | X         | X         | EN        | **8**            |

**Ejemplo:**

1.  Para seleccionar la señal IR 1, deslice el interruptor 1 a ON y el interruptor 2-8 a OFF.
2.  Para seleccionar la señal IR 2, deslice el interruptor 2 a ON y el interruptor 3-8 a OFF, ignore la posición del interruptor 1.
3.  Seleccione la señal IR deseada ajustando el interruptor DIP. Le sugerimos comenzar desde la señal IR 1 deslizando el interruptor 1 a la posición ON para seleccionar la señal IR 1.
4.  Apunte el control remoto IR de su electrodoméstico en la dirección opuesta al receptor IR para evitar que el receptor IR reciba señales IR no deseadas.
5.  Ajuste el control remoto IR a la configuración que desee, luego apunte el control remoto al receptor IR, luego presione el botón del control remoto para transmitir la señal IR.

**Ejemplo:**

1.  Para el control remoto del aire acondicionado, si configura el control remoto en “Modo frío, 18 °C, velocidad del ventilador automática” y apaga el control remoto, apunte el control remoto al receptor de infrarrojos y presione “ON”.

El receptor de infrarrojos aprenderá la señal "Modo frío, 18 °C, velocidad del ventilador automática" para el aire acondicionado.

1.  Para el control remoto de televisión, si apunta el control remoto al receptor de infrarrojos y presiona ON/Off.

El receptor de infrarrojos aprenderá la señal de encendido/apagado del televisor.

1.  Si la señal se recibe correctamente, el LED IR parpadeará rápidamente, luego se apagará para indicar que el control remoto IR está almacenando datos de la señal IR y luego parpadeará lentamente nuevamente. Si accidentalmente envió una señal IR incorrecta, apunte el control remoto hacia afuera para ajustar la configuración y apúntelo hacia el receptor IR para retransmitir la señal nuevamente. La nueva señal IR sobrescribirá la anterior.
2.  Después de terminar de aprender, cambie la configuración del interruptor DIP para aprender otra señal IR, repita el procedimiento del 2 al 4. Sugerimos proceder de la señal IR 1 a 8 deslizando el interruptor DIP 1 a 8 a la posición ON uno por uno.
3.  Repita el proceso para aprender un máximo de 8 señales para cada tipo de aparato.
4.  Puede ajustar la configuración del conjunto 2 del interruptor Dip para seleccionar otro tipo de electrodoméstico.

**Paso 4. Salga del modo de aprendizaje de IR**

1.  Después de terminar de aprender todas las señales IR, presione el botón Función/IR una vez para salir del modo de aprendizaje, luego deslice todos los interruptores a la posición APAGADO.

-   _**Pruebas**_

Después de completar el aprendizaje de las señales IR, siga las instrucciones a continuación para probar la transmisión de señales IR.

1.  No ingrese al modo de aprendizaje de IR, ajuste la configuración del interruptor DIP en consecuencia para seleccionar el tipo de dispositivo y el número de señal de IR como lo aprendió anteriormente.
2.  Presione el botón Función/IR una vez, el LED IR parpadeará rápidamente para indicar que está transmitiendo señal. Si no se aprende ninguna señal, el control remoto IR no enviará ninguna señal y el LED IR permanecerá apagado.
3.  Repita el procedimiento del 1 al 2 para probar todo lo aprendido en las señales IR.
4.  Después de finalizar todas las configuraciones, deslice todos los interruptores a la posición APAGADO.

-   _**Borrar datos de infrarrojos**_

Para eliminar toda la señal IR aprendida para un tipo de electrodoméstico, siga las instrucciones a continuación:

1.  Baterías remotas para apagar el control remoto IR.
2.  Seleccione el tipo de aparato que desea eliminar usando el interruptor DIP configurado 1 de acuerdo con la siguiente tabla

| Cambiar 1 | Cambiar 2 | Cambiar 3 | Cambiar 4 | Cambiar 5 | Cambiar 6 | Selección de electrodomésticos  |
| --------- | --------- | --------- | --------- | --------- | --------- | ------------------------------- |
| EN        | APAGADO   | APAGADO   | APAGADO   | APAGADO   | APAGADO   | **Tipo 1 (Aire Acondicionado)** |
| APAGADO   | EN        | APAGADO   | APAGADO   | APAGADO   | APAGADO   | **Tipo 2 (Televisión)**         |
| APAGADO   | APAGADO   | EN        | APAGADO   | APAGADO   | APAGADO   | **Tipo 3 (audio doméstico)**    |
| APAGADO   | APAGADO   | APAGADO   | EN        | APAGADO   | APAGADO   | **Tipo 4 (decodificador)**      |
| APAGADO   | APAGADO   | APAGADO   | APAGADO   | EN        | APAGADO   | **Tipo 5 (Otros)**              |

Deslice más de un interruptor a ON para seleccionar varios tipos de aparatos,

**Ejemplo:**

1.  Deslice el interruptor 1,2,3,4,5 a ON para seleccionar los 5 tipos de electrodomésticos.
2.  Deslice los interruptores 1 y 3 a ON para seleccionar Aire acondicionado y Audio para el hogar.
3.  Mantenga presionado el botón Función/IR e inserte las baterías para encender el transmisor de infrarrojos; no suelte el botón todavía.
4.  Continúe presionando ambos botones Función/IR hasta que el LED IR se encienda, luego suelte el botón
5.  El transmisor de infrarrojos borrará la señal de infrarrojos almacenada para los tipos de aparatos seleccionados y el LED de infrarrojos parpadeará continuamente.
6.  Deslice todos los interruptores a la posición APAGADO para volver al funcionamiento normal. El LED IR se apagará.

-   Instalación

El control remoto por infrarrojos está diseñado para montarse en la pared. Se puede montar atornillando directamente la cubierta posterior a la pared o instalando primero el soporte giratorio y luego instalando el cuerpo principal en el soporte. por favor refiérase a**Cobertura de señal IR y selección de LED IR**Consulte la siguiente sección para obtener información sobre la transmisión de señales IR antes de seleccionar la ubicación de montaje del control remoto IR.

-   _Montaje del control remoto por infrarrojos_

![](<.gitbook/assets/6 (7) (1).jpeg>)

El control remoto por infrarrojos está diseñado para montarse en la pared. Se puede montar atornillando directamente la cubierta posterior a la pared o instalando primero el soporte giratorio y luego instalando el cuerpo principal en el soporte. El IR Eye debe apuntar al electrodoméstico que desea controlar cuando el control remoto IR está instalado.

**NOTA: El soporte giratorio no está incluido en el envío estándar y está disponible previa solicitud.**

-   Montaje directo en la pared:

La cubierta trasera tiene 4 orificios ciegos, donde el plástico es más delgado, para fines de montaje.

1.  Abra la cubierta y atraviese los 4 orificios ciegos de la cubierta trasera.
2.  Utilice los agujeros como plantilla para perforar agujeros en la pared, inserte tacos si es necesario.
3.  Atornille la cubierta trasera a la pared.
4.  Vuelva a colocar la cubierta frontal en la cubierta trasera.

-   Montaje de soporte giratorio.

El soporte giratorio tiene un cabezal ajustable que se puede conectar al control remoto por infrarrojos. Después de instalar el soporte en la pared, el usuario puede ajustar el ángulo del cabezal para cambiar la dirección en la que mira el control remoto IR.

1.  La base del soporte giratorio tiene 2 orificios de montaje. Utilice los orificios como plantilla para perforar orificios en la pared e inserte tacos de pared si es necesario.
2.  Atornille el soporte a la pared.
3.  Enganche el control remoto por infrarrojos en los soportes usando los orificios en la parte posterior.
4.  Después de completar la instalación, puede usar un destornillador Philip para aflojar el tornillo en la parte superior del soporte, luego ajustar el ángulo del transmisor de infrarrojos y apretar el tornillo para bloquear el ángulo del soporte.

![](<.gitbook/assets/7 (6) (1).jpeg>)

-   Operación
-   _Control a través de puerta de enlace/panel de control Z-Wave_

El control remoto por infrarrojos se puede controlar a través de paneles de control/puerta de enlace Climax Z-Wave de forma remota para transmitir la señal de infrarrojos. Al seleccionar el tipo de aparato y el número de señal IR en el panel de control, el control remoto IR controlará el envío de la señal IR en consecuencia.

**Ejemplo:**

1.  Seleccione "Función de aire acondicionado 1" para controlar el control remoto IR y enviar la señal IR 1 aprendida en el tipo de aparato de aire acondicionado.

-   _Cobertura de señal IR y selección de LED IR_

![](<.gitbook/assets/8 (3) (1).jpeg>)

El IR Eye del control remoto IR incluye 6 LED que se utilizan para transmitir señales IR, con 1 LED central y 5 LED circundantes. Los 5 LED circundantes están colocados en un ángulo de 45° con respecto a la placa PCB.**Cobertura de señal LED:**

Cada LED transmite una señal IR en una cobertura de cono frente al LED. El LED Central se utiliza siempre en cada transmisión. También se puede seleccionar 1 de los 5 LED circundantes para transmitir señal para cada tipo de aparato mediante el panel de control/puerta de enlace Climax Z-Wave.

**Ejemplo:**

1.  Si selecciona el LED 1 para aire acondicionado, el control remoto IR transmitirá una señal tanto con el LED central como con el LED 1 cuando transmita una señal IR de tipo aparato de aire acondicionado.
2.  Si selecciona el LED 3 para Home Audio, el control remoto IR transmitirá la señal tanto con el LED central como con el LED 3 cuando transmita una señal IR tipo aparato de Home Audio.

Al instalar el control remoto por infrarrojos, seleccione el LED de infrarrojos utilizado a través de su panel de control de acuerdo con la ubicación de montaje del control remoto por infrarrojos para permitir que el transmisor de infrarrojos envíe señal a todos los electrodomésticos de su hogar. Consulte el manual de su puerta de enlace/panel de control Climax para obtener más información sobre la configuración y el control del control remoto por infrarrojos.

Consulte el diagrama a continuación para conocer la cobertura de la señal IR:

![](<.gitbook/assets/9 (1) (1) (1).jpeg>)

-   _Potencia de transmisión de infrarrojos_

Utilice los interruptores de puente (JP2 y JP3) para ajustar la potencia de transmisión de la señal IR. El valor predeterminado de fábrica está configurado en Potencia de transmisión baja (JP1 ON). Configurar el puente en JP2 aumentará el rango de transmisión de la señal IR.

-   _Comando de configuración de control AV simple_

El comando AV control set simple se utiliza para controlar un dispositivo AV a través del Panel de control:

Clase de comando: COMANDO_CLASE_SIMPLE_DE_CONTROL_V1

Comando: SIMPLE_DE_CONTROL_COLOCAR

Establezca los valores:

ID de artículo MSB: para tipo de aparato, 01~05

ID de artículo LSB: para datos de señal IR, 01~08

![](<.gitbook/assets/10 (2) (1).png>)

**Información de onda Z**

**Tipo de dispositivo:**Submedidor de energía

**Tipo de rol:**Informar sobre esclavo durmiente (RSS)

**Soporte/Control de Clase de Comando**

**Soporte CC obligatorio:**Asociación CC, v2

Información del grupo de asociación CC

CC de la batería

Restablecimiento del dispositivo localmente CC

CC específico del fabricante, v2

Configuración CC,

Control AV sencillo CC,

Versión CC, v2

Z-Wave Plus Información CC, v2

Nivel de potencia CC

Actualización de firmware CC, v2

-   _**Grupos de Z-Wave (clase de comando de asociación versión 2)**_

Grupo 1 para “LifeLine”:

Batería CC (COMANDO_CLASE_BÁSICO)

Restablecimiento del dispositivo localmente CC
