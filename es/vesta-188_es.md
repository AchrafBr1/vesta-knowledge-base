# VESTA 188

**Control remoto universal por infrarrojos UPIC-5ZBS**

**Introducción**

UPIC5-ZBS es un control remoto por infrarrojos ZigBee. Está diseñado para operar sus electrodomésticos transmitiendo señal IR. El control remoto por infrarrojos es capaz de aprender la señal de infrarrojos transmitida desde el control remoto del aparato. Después de aprender la señal, puede controlar remotamente el control remoto IR a través de la red ZigBee para enviar la señal al dispositivo sin usar el control remoto manualmente y admitir la capacidad de actualización de firmware por aire (OTA). El control remoto por infrarrojos utiliza tecnología ZigBee para la transmisión de señales inalámbricas. ZigBee es un protocolo de comunicación inalámbrica confiable, de bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir una gran cantidad de dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

El control remoto por infrarrojos sirve como dispositivo final en la red ZigBee. Puede incluirse en la red ZigBee para transmitir señal tras la activación, pero no puede permitir que ningún otro dispositivo ZigBee se una a la red a través del propio dispositivo.

**Identificación de piezas**

![](<.gitbook/assets/0 (76).jpeg>)

1.  **Ojo infrarrojo**

Transmite señal IR a los electrodomésticos.

1.  **Botón ZigBee**
2.  **Botón de infrarrojos**
3.  **ZigBeeLED**

Parpadea dos veces: el control remoto por infrarrojos se une exitosamente a la red ZigBee. Parpadea cada 20 minutos: el control remoto por infrarrojos ha perdido la conexión con su red ZigBee actual.

1.  **LED indicador de infrarrojos**

Parpadeo lento: control remoto por infrarrojos en modo de aprendizaje por infrarrojos.

Quick Flash: el control remoto por infrarrojos recibe una señal de infrarrojos en el modo de aprendizaje o está transmitiendo una señal de infrarrojos

Parpadea cada medio segundo: los datos IR se borran

Apagado: el control remoto por infrarrojos está almacenando la señal de infrarrojos recibida en el modo de aprendizaje.

– El control remoto por infrarrojos está en modo inactivo.

1.  **Receptor de señal infrarroja**
2.  **Puente de potencia de transmisión IR baja (JP1)**

![](<.gitbook/assets/1 (57).png>)

**Puente encendido****Puente apagado**

![](<.gitbook/assets/2 (61).jpeg>)![](<.gitbook/assets/3 (54).jpeg>)

El enlace del puente se inserta conectando los dos pines.

si se elimina el enlace del puente o "**estacionado**”en un alfiler.

Puente ON – Potencia de transmisión IR configurada en Baja.**(Predeterminado de fábrica)**Puente APAGADO – Deseleccionado.

**8. Puente de potencia de transmisión IR alta (JP2)**

![](<.gitbook/assets/4 (52).jpeg>)

**Puente encendido****Puente apagado**

![](<.gitbook/assets/5 (63).png>)

El enlace del puente se inserta conectando los dos pines.

si se elimina el enlace del puente o "**estacionado**”en un alfiler.

Puente ON – Potencia de transmisión IR configurada en Alta.

Puente APAGADO – Deseleccionado.

**NOTA IMPORTANTE: Los puentes JP1 y JP2 NO PUEDEN configurarse en ON al mismo tiempo**

1.  **Juego de interruptores DIP 1**

Para configurar el tipo de aparato

1.  **Juego de interruptores DIP 2**

Para aprender y probar la señal IR

1.  **Compartimiento de la batería**
2.  **Soporte giratorio para montaje en pared (opcional)**

1

**Características**

-   _**Detección de batería y batería baja**_

El control remoto por infrarrojos utiliza dos baterías de litio de 1,5 V como fuente de alimentación. Cuenta con la función de detección de batería baja. Cuando se detecta un voltaje bajo de la batería, el control remoto por infrarrojos transmitirá la señal de batería baja al coordinador en la red ZigBee.

-   _**Supervisión**_

El control remoto por infrarrojos transmitirá una señal de supervisión para informar su condición periódicamente según la configuración del usuario. El intervalo predeterminado de fábrica es de 30 minutos. El usuario también puede presionar el botón ZigBee una vez para transmitir una señal de supervisión manualmente.

**Configuración de red ZigBee**

-   _**Guía del dispositivo ZigBee**_

El control remoto por infrarrojos es un protocolo de comunicación inalámbrico confiable, de bajo consumo de energía y alta eficiencia de transmisión. Basado en el estándar IEEE802.15.4, ZigBee permite incluir una gran cantidad de dispositivos en una red y coordinarlos para el intercambio de datos y la transmisión de señales.

Debido a la estructura fundamental de la red ZigBee, el dispositivo ZigBee buscará y se unirá activamente a la red después de encenderse. Dado que realizar una tarea al conectarse a la red puede consumir algo de energía, es necesario seguir las instrucciones para evitar agotar la batería de un dispositivo ZigBee.

-   Asegúrese de que el enrutador/coordinador de red ZigBee esté encendido antes de insertar la batería en el dispositivo ZigBee.
-   Asegúrese de que el enrutador/coordinador de red ZigBee esté encendido y dentro del alcance mientras el dispositivo ZigBee esté en uso.

\-No retire un dispositivo ZigBee del enrutador o coordinador de red ZigBee sin quitar la batería del dispositivo ZigBee.

-   _**Unirse a la red ZigBee**_

Como dispositivo ZigBee, el control remoto IR necesita unirse a una red ZigBee para recibir comandos del coordinador de red ZigBee para transmitir la señal IR. Siga los pasos a continuación para unir el control remoto por infrarrojos a la red ZigBee.

-   1.  Inserte las pilas para encender el control remoto por infrarrojos.
    2.  **PAG**Mantenga presionado el botón ZigBee durante 10 segundos, luego suéltelo para unirse a la red. Asegúrese de que la función de permiso de unión en el enrutador o coordinador de su red ZigBee esté habilitada.
    3.  Después de unirse a la red ZigBee, el control remoto por infrarrojos se registrará automáticamente en el sistema de seguridad de la red. Verifique el panel de control del sistema de seguridad o CIE (Equipo de control e indicación) para confirmar si la inscripción y el registro se realizaron correctamente.
    4.  Si el control remoto por infrarrojos se une exitosamente a la red ZigBee, el LED ZigBee parpadeará dos veces para indicarlo.
    5.  Después de unirse a la red ZigBee, si el control remoto por infrarrojos pierde la conexión con la red ZigBee actual, el indicador LED ZigBee parpadeará cada 20 minutos. Verifique la condición de la red ZigBee y el rango de la señal del control remoto IR para corregir la situación.
-   _**Eliminación del dispositivo de la red ZigBee (restablecimiento de fábrica)**_

Para eliminar el dispositivo de la red ZigBee actual, se debe restablecer el control remoto por infrarrojos a los valores de fábrica para completar la eliminación del dispositivo. La función de restablecimiento de fábrica borrará la información de configuración almacenada del control remoto por infrarrojos y solicitará al dispositivo que busque una nueva red ZigBee.

**Antes de retirar el dispositivo, asegúrese de que esté dentro del rango de señal de red ZigBee actual.**

-   1.  Elimine el control remoto IR del panel de control/CIE actual.
    2.  Mantenga presionado el botón de función durante 10 segundos, luego suelte el botón para restablecer el dispositivo.
    3.  Al reiniciarse, el control remoto por infrarrojos borrará la configuración actual de la red ZigBee y transmitirá la señal al coordinador ZigBee para eliminarse de la red ZigBee actual. Luego buscará activamente nuevamente la red ZigBee disponible y se unirá a la red automáticamente.
-   _**Actualización de firmware OTA**_
-   El dispositivo admite la función de actualización de firmware OTA a través de la red ZigBee, que puede iniciarse desde el coordinador de red ZigBee.
-   Siga los pasos a continuación para realizar la actualización del firmware OTA.

1.  Debe acceder a su Coordinador ZigBee para realizar la actualización del firmware en el aire.
2.  En la página web de configuración, seleccione el dispositivo que desea actualizar y seleccione el nuevo firmware ZigBee proporcionado. Consulte el Manual del usuario del Coordinador ZigBee para obtener más detalles.
3.  Presione Aceptar para iniciar el proceso de actualización; no realice ninguna otra acción ni apague el panel.
4.  La duración de una actualización tardará aproximadamente entre 20 y 30 minutos. Tenga en cuenta que la duración puede variar según el tamaño del archivo o la distancia entre su accesorio y el coordinador.
5.  Espere a que el firmware complete la actualización. Cuando el progreso alcance el 100%, el dispositivo se reiniciará automáticamente. También puede actualizar la página web nuevamente para asegurarse de que el firmware del dispositivo se actualice correctamente y se muestre la versión más reciente.

2

**Aprendizaje y prueba de señales IR**

Para utilizar el control remoto por infrarrojos para controlar su electrodoméstico, el control remoto por infrarrojos primero debe aprender de la señal de infrarrojos enviada desde el control remoto del electrodoméstico. Siga las instrucciones a continuación para completar el proceso de aprendizaje.

**Mantenga el receptor de infrarrojos alejado de la iluminación directa o la luz solar durante el proceso de aprendizaje para evitar interferencias.**

-   _**Aprendiendo**_

**Paso 1. Ingrese al modo de aprendizaje de infrarrojos**

1.  Siga las instrucciones en**Configuración de red ZigBee**sección para unir el control remoto por infrarrojos a su red ZigBee.
2.  Asegúrese de que todos los interruptores en el bloque de interruptores DIP estén configurados en**APAGADO**posición.
3.  Mantenga presionado el botón IR durante 10 segundos y suéltelo cuando el LED IR comience a parpadear.
4.  El LED IR comenzará a parpadear lentamente para indicar que el control remoto IR está

![](<.gitbook/assets/6 (44).png>)

| ahora ingresando al modo de aprendizaje IR.   | EN      |   |
| --------------------------------------------- | ------- | - |
| **Paso 2. Seleccione el tipo de dispositivo** | APAGADO |   |
|                                               |         |   |

El transmisor de infrarrojos puede aprender hasta 5 conjuntos de señales de infrarrojos para 5 aparatos diferentes.

Antes de comenzar a aprender, seleccione el número del aparato con el conjunto de interruptores DIP 1 antes de continuar con el aprendizaje de las señales. La señal IR aprendida se asignará al número de aparato seleccionado.

Seleccione el tipo de aparato de acuerdo con la siguiente tabla del Juego de interruptores DIP 1. Para facilitar el reconocimiento y la operación desde el panel de control Climax ZigBee, a cada tipo de dispositivo se le ha asignado un nombre para mostrar en la interfaz del panel de control; le sugerimos que aprenda en las señales IR según los tipos de electrodomésticos mostrados.

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

-   1.  Para seleccionar la señal IR 1, deslice el interruptor 1 a ON y el interruptor 2-8 a OFF.
    2.  Para seleccionar la señal IR 2, deslice el interruptor 2 a ON y el interruptor 3-8 a OFF, ignore la posición del interruptor 1.

1.  Seleccione la señal IR deseada ajustando el interruptor DIP. Le sugerimos comenzar desde la señal IR 1 deslizando el interruptor 1 a la posición ON para seleccionar la señal IR 1.
2.  Apunte el control remoto IR de su electrodoméstico en la dirección opuesta al receptor IR para evitar que el IR

El receptor no reciba señales IR no deseadas.

1.  Ajuste el control remoto IR a la configuración que desee, luego apunte el control remoto al receptor IR, luego presione el botón del control remoto para transmitir la señal IR.

**Ejemplo:**

-   1.  Para el control remoto del aire acondicionado, si configura el control remoto en “Modo frío, 18 °C, velocidad del ventilador automática” y apaga el control remoto, apunte el control remoto al receptor de infrarrojos y presione “ON”.

El receptor de infrarrojos aprenderá la señal "Modo frío, 18 °C, velocidad del ventilador automática" para el aire acondicionado.

-   1.  Para el control remoto de televisión, si apunta el control remoto al receptor de infrarrojos y presiona ON/Off. El receptor de infrarrojos aprenderá la señal de encendido/apagado del televisor.

1.  Si la señal se recibe correctamente, el LED IR parpadeará rápidamente, luego se apagará para indicar que el control remoto IR está almacenando datos de la señal IR y luego parpadeará lentamente nuevamente. Si accidentalmente envió una señal IR incorrecta, apunte el control remoto hacia afuera para ajustar la configuración y apúntelo hacia el receptor IR para retransmitir la señal nuevamente. La nueva señal IR sobrescribirá la anterior.
2.  Después de terminar de aprender, cambie la configuración del interruptor DIP para aprender otra señal IR, repita el procedimiento del 2 al 4. Sugerimos proceder de la señal IR 1 a 8 deslizando el interruptor DIP 1 a 8 a la posición ON uno por uno.
3.  Repita el proceso para aprender un máximo de 8 señales para cada tipo de aparato.

3

-   1.  Puede ajustar la configuración del conjunto 2 del interruptor Dip para seleccionar otro tipo de electrodoméstico.

**Paso 4. Salga del modo de aprendizaje de IR**

-   1.  Después de terminar de aprender todas las señales IR, presione el botón IR una vez para salir del modo de aprendizaje, luego deslice todos los interruptores a la posición APAGADO.
-   _**Pruebas**_

Después de completar el aprendizaje de las señales IR, siga las instrucciones a continuación para probar la transmisión de señales IR.

-   1.  No ingrese al modo de aprendizaje de IR, ajuste la configuración del interruptor DIP en consecuencia para seleccionar el tipo de dispositivo y el número de señal de IR como lo aprendió anteriormente.
    2.  Presione el botón IR una vez, el LED IR parpadeará rápidamente para indicar que está transmitiendo señal. Si no se aprende ninguna señal, el control remoto IR no enviará ninguna señal y el LED IR permanecerá apagado.
    3.  Repita el procedimiento del 1 al 2 para probar todo lo aprendido en las señales IR.
    4.  Después de finalizar todas las configuraciones, deslice todos los interruptores a la posición APAGADO.
-   _**Borrar datos de infrarrojos**_

Para eliminar toda la señal IR aprendida para un tipo de electrodoméstico, siga las instrucciones a continuación:

1.  Retire las baterías para apagar el control remoto por infrarrojos.
2.  Seleccione el tipo de aparato que desea eliminar usando el interruptor DIP configurado 1 de acuerdo con la siguiente tabla

| Cambiar 1 | Cambiar 2 | Cambiar 3 | Cambiar 4 | Cambiar 5 | Cambiar 6 | Selección de electrodomésticos  |                               |
| --------- | --------- | --------- | --------- | --------- | --------- | ------------------------------- | ----------------------------- |
| EN        | APAGADO   | APAGADO   | APAGADO   | APAGADO   | APAGADO   | **Tipo 1 (Aire Acondicionado)** |                               |
| APAGADO   | EN        | APAGADO   | APAGADO   | APAGADO   | APAGADO   | **Tipo 2**                      | **(Televisión)**              |
| APAGADO   | APAGADO   | EN        | APAGADO   | APAGADO   | APAGADO   | **Tipo 3**                      | **(Audio casero)**            |
| APAGADO   | APAGADO   | APAGADO   | EN        | APAGADO   | APAGADO   | **Tipo 4**                      | **(Fijar la caja de encima)** |
| APAGADO   | APAGADO   | APAGADO   | APAGADO   | EN        | APAGADO   | **Tipo 5**                      | **(Otros)**                   |

Deslice más de un interruptor a ON para seleccionar varios tipos de aparatos,

**Ejemplo:**

-   1.  Deslice el interruptor 1,2,3,4,5 a ON para seleccionar los 5 tipos de electrodomésticos.
    2.  Deslice los interruptores 1 y 3 a ON para seleccionar Aire acondicionado y Audio para el hogar.

1.  Mantenga presionados los botones IR y ZigBee e inserte las baterías para encender el transmisor IR; no suelte los botones todavía.
2.  Continúe presionando los botones IR y ZigBee hasta que el LED IR se encienda, luego suelte los botones
3.  El transmisor de infrarrojos borrará la señal de infrarrojos almacenada para los tipos de aparatos seleccionados y el LED de infrarrojos parpadeará continuamente.
4.  Deslice todos los interruptores a la posición APAGADO para volver al funcionamiento normal. El LED IR se apagará.

**Instalación**

El control remoto por infrarrojos está diseñado para montarse en la pared. Se puede montar atornillando directamente la cubierta posterior a la pared o instalando primero el soporte giratorio y luego instalando el cuerpo principal en el soporte. por favor refiérase a**Cobertura de señal IR y selección de LED IR**Consulte la siguiente sección para obtener información sobre la transmisión de señales IR antes de seleccionar la ubicación de montaje del control remoto IR.

-   _**Montaje del control remoto por infrarrojos**_

![](<.gitbook/assets/7 (40).jpeg>)

El control remoto por infrarrojos está diseñado para montarse en la pared. Se puede montar atornillando directamente la cubierta posterior a la pared o instalando primero el soporte giratorio y luego instalando el cuerpo principal en el soporte. El IR Eye debe apuntar al electrodoméstico que desea controlar cuando el control remoto IR está instalado.

**NOTA: El soporte giratorio no está incluido en el envío estándar y está disponible previa solicitud.**

-   Montaje directo en la pared:

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

4

![](<.gitbook/assets/8 (35).jpeg>)

**Operación**

-   _**Control a través del panel de control ZigBee**_

El control remoto por infrarrojos se puede controlar a través de los paneles de control Climax ZigBee de forma remota para transmitir la señal de infrarrojos. Al seleccionar el tipo de aparato y el número de señal IR en el panel de control, el control remoto IR controlará el envío de la señal IR en consecuencia.

**Ejemplo:**

-   1.  Seleccione "Función de aire acondicionado 1" para controlar el control remoto IR y enviar la señal IR 1 aprendida en Aire.

Tipo de aparato acondicionador.

-   _**Cobertura de señal IR y selección de LED IR**_

![](<.gitbook/assets/9 (27).jpeg>)

El IR Eye del control remoto IR incluye 6 LED que se utilizan para transmitir señales IR, con 1 LED central y 5 LED circundantes. Los 5 LED circundantes están colocados en un ángulo de 45° con respecto a la placa PCB.**Cobertura de señal LED:**

Cada LED transmite una señal IR en una cobertura de cono frente al LED. Los LED se pueden seleccionar para transmitir señal para cada tipo de dispositivo utilizando su puerta de enlace.

**Ejemplo:**

a. Si selecciona el LED 1 para aire acondicionado, el control remoto IR transmitirá la señal con el LED 1 cuando transmita una señal IR de tipo aparato de aire acondicionado.

1.  Si selecciona el LED 2 y el LED 3 para Home Audio, el control remoto IR transmitirá la señal tanto con el LED 2 como con el LED 3 cuando transmita una señal IR tipo aparato de Home Audio.

Al instalar el control remoto por infrarrojos, seleccione el LED de infrarrojos utilizado a través de su panel de control de acuerdo con la ubicación de montaje del control remoto por infrarrojos para permitir que el transmisor de infrarrojos envíe señal a todos los electrodomésticos de su hogar. Consulte el manual del panel de control Climax para obtener más información sobre la configuración y el control del control remoto por infrarrojos.

Consulte el diagrama a continuación para conocer la cobertura de la señal IR:

5

![](<.gitbook/assets/10 (20).jpeg>)

-   _**Potencia de transmisión de infrarrojos**_

Utilice los interruptores de puente (JP2 y JP3) para ajustar la potencia de transmisión de la señal IR. El valor predeterminado de fábrica está configurado en Potencia de transmisión baja (JP1 ON). Configurar el puente en JP2 aumentará el rango de transmisión de la señal IR.

6

**Apéndice (solo para desarrolladores)**

_**ID del grupo UPIC**_

**ID del dispositivo: UPIC 0x0307 (propietario)**

**Punto final: 0x01**

| **Lado del servidor** |                 | **Lado del cliente** |
| --------------------- | --------------- | -------------------- |
|                       |                 |                      |
|                       | **Obligatorio** |                      |

Básico (0x0000)

CFG de energía (0x0001)

Identificar(0x0003)

Termostato HVAC (0x0201)

Identificar(0x0003)

**Opcional**

_Ninguno_

_Ninguno_

-   _**Atributo de información básica del clúster**_

| **Identificador** | **Nombre**                    | **Tipo**          | **Rango**    | **Acceso** | **Por defecto**      | **Obligatorio** |   |
| ----------------- | ----------------------------- | ----------------- | ------------ | ---------- | -------------------- | --------------- | - |
| **/ Opcional**    |                               |                   |              |            |                      |                 |   |
|                   |                               |                   |              |            |                      |                 |   |
| 0x0000            | _Versión ZCL_                 | 8 bits sin firmar | 0x00 –0xff   | Leer       | 0x01                 | METRO           |   |
| entero            | solo                          |                   |              |            |                      |                 |   |
|                   |                               |                   |              |            |                      |                 |   |
| 0x0001            | Versión de la aplicación      | 8 bits sin firmar | 0x00 –0xff   | Leer       | 0x00                 | oh              |   |
| entero            | solo                          |                   |              |            |                      |                 |   |
|                   |                               |                   |              |            |                      |                 |   |
| 0x0003            | _Versión HW_                  | 8 bits sin firmar | 0x00 –0xff   | Leer       | 0                    | oh              |   |
| entero            | solo                          |                   |              |            |                      |                 |   |
|                   |                               |                   |              |            |                      |                 |   |
| 0x0004            | _Nombre del Fabricante_       | Personaje         | 0 – 32 bytes | Leer       | Clímax               | oh              |   |
| Cadena            | solo                          | Tecnología        |              |            |                      |                 |   |
|                   |                               |                   |              |            |                      |                 |   |
| 0x0005            | _Identificador de modelo_     | Personaje         | 0 – 32 bytes | Leer       | (Versión del modelo) | oh              |   |
| Cadena            | solo                          |                   |              |            |                      |                 |   |
|                   |                               |                   |              |            |                      |                 |   |
| 0x0006            | _Código de fecha_             | Personaje         | 0 – 16 bytes | Leer       |                      | oh              |   |
| Cadena            | solo                          |                   |              |            |                      |                 |   |
|                   |                               |                   |              |            |                      |                 |   |
| 0x0007            | _Fuente de alimentación_      | 8 bits            | 0x00 –0xff   | Leer       |                      | METRO           |   |
| solo              |                               |                   |              |            |                      |                 |   |
|                   |                               |                   |              |            |                      |                 |   |
| 0x0010            | _Descripción de la ubicación_ | Personaje         | 0 – 32 bytes | Leer /     |                      | oh              |   |
| Cadena            | Escribir                      |                   |              |            |                      |                 |   |
|                   |                               |                   |              |            |                      |                 |   |
| 0x0011            | _Entorno físico_              | 8 bits            | 0x00 –0xff   | Leer /     | 0x00                 | oh              |   |
| Escribir          |                               |                   |              |            |                      |                 |   |
|                   |                               |                   |              |            |                      |                 |   |
| 0x0012            | _Dispositivo habilitado_      | Booleano          | 0x00 –0x01   | Leer /     | 0x01                 | METRO           |   |
| Escribir          |                               |                   |              |            |                      |                 |   |
|                   |                               |                   |              |            |                      |                 |   |

_**Atributo de información del clúster Power CFG**_

| **Identificador** | **Nombre**                        | **Tipo**              | **Rango** | **Acceso**   | **Por defecto** | **Obligatorio** |   |
| ----------------- | --------------------------------- | --------------------- | --------- | ------------ | --------------- | --------------- | - |
| **/ Opcional**    |                                   |                       |           |              |                 |                 |   |
|                   |                                   |                       |           |              |                 |                 |   |
| 0x0035            | _MÁSCARA DE ALARMA DE MURCIÉLAGO_ | Enumeración de 8 bits | Todo      | Solo lectura | 0x00            | METRO           |   |

_**Atributo de información de identificación del clúster**_

| **Identificador** | **Nombre**          | **Tipo**           | **Rango**    | **Acceso**    | **Por defecto** | **Obligatorio** |   |
| ----------------- | ------------------- | ------------------ | ------------ | ------------- | --------------- | --------------- | - |
| **/ Opcional**    |                     |                    |              |               |                 |                 |   |
|                   |                     |                    |              |               |                 |                 |   |
| 0x0000            | _IdentificarTiempo_ | 16 bits sin firmar | 0x00 –0xffff | Leer escribir | 0x0000          | METRO           |   |
| entero            |                     |                    |              |               |                 |                 |   |
|                   |                     |                    |              |               |                 |                 |   |

_**Atributo de la información del grupo de termostatos**_

| **Identificador** | **Nombre**             | **Tipo**  | **Rango**      | **Acceso**    | **Por defecto** | **Obligatorio** |   |
| ----------------- | ---------------------- | --------- | -------------- | ------------- | --------------- | --------------- | - |
| **/ Opcional**    |                        |           |                |               |                 |                 |   |
|                   |                        |           |                |               |                 |                 |   |
| 0x001C            | _Modo del sistema_     | 8 bits    | Todo           | Leer escribir | 0x04            | METRO           |   |
| Enumeración       |                        |           |                |               |                 |                 |   |
|                   |                        |           |                |               |                 |                 |   |
| 0x1011            | _Seleccione enviar IR_ | UNIDAD 40 | 0CSAAFFFFFFFF- | Leer escribir | 0x2020202020    | oh              |   |
| _CONDUJO_         | 0x0101010101           |           |                |               |                 |                 |   |
|                   |                        |           |                |               |                 |                 |   |

**Modo del sistema (0x001C):**

Este atributo determina qué señal IR transmitir cuando UPIC recibe un comando del panel, de acuerdo con lo aprendido en Tipo y función de señal IR.

UPIC puede aprender hasta 5 conjuntos de tipos de IR, 8 señales para cada tipo. Al transmitir señal, la señal IR debe ser

especificado con este atributo.

El formato es 0x_**XY**_

7

X = Tipo de aparato (1~5)

Y = IR signal Number (1~8)

Por ejemplo, si el UPIC ha aprendido una señal IR en el tipo de dispositivo 1, señal IR 8, el panel debe enviar un comando con la configuración de atributo 0x._**18**_para que UPIC transmita esta señal.

**Seleccione Enviar LED IR (0x1011):**

UPIC puede controlar hasta 5 tipos de electrodomésticos (Tipo 1~5) con sus 6 LED IR. Se puede configurar para enviar señal IR con diferentes LED usando este atributo.

El formato debe leerse de la siguiente manera, utilizando el valor predeterminado 0x2020202020 como ejemplo

| 0x20                 | 0x20                 | 0x20                 | 0x20                 | 0x20                 |
| -------------------- | -------------------- | -------------------- | -------------------- | -------------------- |
|                      |                      |                      |                      |                      |
| LED IR para usar con | LED IR para usar con | LED IR para usar con | LED IR para usar con | LED IR para usar con |
| Tipo de aparato 1    | Tipo de aparato 2    | Tipo de aparato 3    | Tipo de aparato 4    | Tipo de aparato 5    |
|                      |                      |                      |                      |                      |

Para cada valor de tipo de dispositivo, el valor debe leerse en Bit0~5, en el siguiente formato:

| Valor           | en        |               |      | 2     |                |                |                | 0              |       |                |                |
| --------------- | --------- | ------------- | ---- | ----- | -------------- | -------------- | -------------- | -------------- | ----- | -------------- | -------------- |
| hexadecimal     |           |               |      |       |                |                |                |                |       |                |                |
| ocre oscuro     |           |               |      |       |                |                |                |                |       |                |                |
|                 |           |               |      |       |                |                |                |                |       |                |                |
| Número de TBI   |           | Está viniendo | BIT6 |       | btkh           | BIT4           | Yo lo compré   | Beta           |       | BIT1           | BIT0           |
|                 |           |               |      |       |                |                |                |                |       |                |                |
| Valor en        | Poco      | 0             | 0    |       | 1              | 0              | 0              | 0              |       | 0              | 0              |
| número          |           |               |      |       |                |                |                |                |       |                |                |
|                 |           |               |      |       |                |                |                |                |       |                |                |
| Número de LED a | Reservado | Reservado     |      | LED 6 | LED 5          | LED 4          | LED 3          |                | LED 2 | LED 1          |                |
| ser activado    |           |               |      |       | 1=habilitar    | 1=habilitar    | 1=habilitar    | 1=habilitar    |       | 1=habilitar    | 1=habilitar    |
|                 |           |               |      |       | 0=deshabilitar | 0=deshabilitar | 0=deshabilitar | 0=deshabilitar |       | 0=deshabilitar | 0=deshabilitar |
|                 |           |               |      |       |                |                |                |                |       |                |                |

Por ejemplo: 0x20 = 0010 0000 en el número de bit, lo que significa que solo el LED 6 (el LED central) se activará cuando UPIC transmita una señal IR en este tipo de dispositivo.

Si desea configurar la señal IR para que se transmita tanto con el LED 2 como con el LED 6, el valor en el número de bit será 0010 0010 = 0x22

| 0         | 0         | 1        | 0          |
| --------- | --------- | -------- | ---------- |
|           |           |          |            |
| Reservado | Reservado | LED 6    | LED 5      |
|           |           | Permitir | Desactivar |
|           |           |          |            |

| 0          | 0          | 1        | 0          |
| ---------- | ---------- | -------- | ---------- |
|            |            |          |            |
| LED 4      | LED 3      | LED 2    | LED 1      |
| Desactivar | Desactivar | Permitir | Desactivar |
|            |            |          |            |

0010 0010 en número de bit = 0x22 en número hexadecimal, si desea aplicar esta configuración solo al tipo de dispositivo 1 y dejar el otro tipo de dispositivo sin cambios, la configuración del atributo final será: 0x**22**20202020

| 0x22                | 0x20                | 0x20                | 0x20                | 0x20                |
| ------------------- | ------------------- | ------------------- | ------------------- | ------------------- |
|                     |                     |                     |                     |                     |
| LED IR a utilizar   | LED IR a utilizar   | LED IR a utilizar   | LED IR a utilizar   | LED IR a utilizar   |
| con aparato tipo 1, | con aparato tipo 2, | con aparato tipo 3, | con aparato tipo 4, | con aparato tipo 5, |
| LED 6 y 2           | LED 6               | LED 6               | LED 6               | LED 6               |
|                     |                     |                     |                     |                     |

Puede utilizar este atributo para programar qué LED deben activarse para diferentes tipos de dispositivos IR._**NOTA IMPORTANTE:**_

Aunque es posible configurar la transmisión de múltiples LED al enviar una señal IR, configure**NO MÁS DE 2**LED para activar. La razón de esta limitación es que por cada LED adicional activado, el consumo de energía aumentará drásticamente. Si activas más de 2 LEDs la batería se agotará en un tiempo mucho menor del ideal.

8
