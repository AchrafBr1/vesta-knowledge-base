# VESTA 171

**Válvula termostática para radiador TRV-1ZW**

**Introducción**

TRV-1ZW es una válvula de radiador Z-Wave diseñada para controlar la temperatura ambiente controlando el flujo de agua caliente de los radiadores en la red Z-Wave, es decir, la temperatura ambiente interior.

La válvula del radiador es un dispositivo habilitado para Z-Wave y es totalmente compatible con cualquier red habilitada para Z-Wave.

Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. Al aprovechar la red de malla Z-Wave, los comandos se pueden enrutar a su destino a través de productos Z-Wave intermediarios que “escuchan”.

**Identificación de piezas**

1.  **Tapa de válvula**
2.  **Pantalla LCD**

![](<.gitbook/assets/0 (49).png>)![](<.gitbook/assets/1 (56).jpeg>)

1.  ![](<.gitbook/assets/2 (51).jpeg>)**EN**cuando el dispositivo ya está agregado a la red Z-Wave.
2.  ![](<.gitbook/assets/3 (46).jpeg>)**Indicador de batería baja.**
3.  ![](<.gitbook/assets/4 (45).jpeg>)Encendido: Dispositivo configurado a la temperatura predeterminada de 17 °C.

![](<.gitbook/assets/5 (28).jpeg>)Parpadeo: Válvula cerrando.

![](<.gitbook/assets/6 (38).jpeg>)Encendido: Dispositivo configurado a la temperatura predeterminada de 21 °C.

![](<.gitbook/assets/7 (36).jpeg>)Flash: Apertura de válvula.

1.  **Modo automático/manual.**
2.  **Función de impulso.**
3.  **Ventana abierta**.
4.  **Indicador de temperatura.**

![](<.gitbook/assets/8 (36).png>)

**Otros: InS**: Cuando se enciende el dispositivo (también durante el período de aprendizaje).

**Hay:**funcionamiento del motor del dispositivo.

**F1/F:**la válvula está atascada,**Categoría:**no hay válvula instalada.

**3. Botones de función**

\-**Manual/Automático:**Ingrese al modo Manual o Automático.

\-**Impulso/ Onda Z:**Acelere el proceso de calentamiento/agregue a la red Z-Wave.

\-![](<.gitbook/assets/9 (21).jpeg>)Presione este botón para cambiar instantáneamente las temperaturas diurnas y nocturnas.

_**Día predeterminado**_![](<.gitbook/assets/10 (16).jpeg>)_temperatura: 21_°C_,**Noche predeterminada**_![](<.gitbook/assets/11 (21).jpeg>)_temperatura: 17_°C

1.  **Sensor de temperatura**
2.  **Perilla de control**

Ajuste la temperatura manualmente.

**6. Compartimento de la batería**

La válvula del radiador funciona con dos pilas alcalinas AA de 1,5 V.

1

**Características**

![](<.gitbook/assets/12 (31).png>)

-   _**Batería**_

La válvula del radiador utiliza dos pilas alcalinas AA de 1,5 V como fuente de alimentación. La válvula del radiador informará su porcentaje de batería a la puerta de enlace/panel de control respectivamente al 100%, 75%, 50%, 25%. Si el voltaje de la batería es bajo (25%), se enviará una señal de batería baja al portal/panel de control para notificar al usuario.

La válvula del radiador puede detectar si la batería está baja. Cuando se detecta un voltaje de batería bajo, aparece una señal de batería baja.

se enviará al panel de control/puerta de enlace Z-Wave y la pantalla LCD mostrará![](<.gitbook/assets/13 (20).jpeg>)icono para notificar al usuario.

![](<.gitbook/assets/14 (19).png>)

-   _**Encendido/Manual/Modo automático**_

**Encendido**: Cuando la válvula del radiador se enciende, su motor comienza a funcionar con la pantalla LCD**En s**, el dispositivo está listo para la instalación y comienza el proceso de aprendizaje. (ver**Instalación**para detalles)

**Modo manual:**En el modo Manual, puede utilizar las siguientes funciones:

-   ![](<.gitbook/assets/15 (17).jpeg>)Botón: cambia la temperatura día/noche al instante.
-   **Botón de impulso:**Acelere el calentamiento / agregue un dispositivo a Z-Wave Gateway o al panel de control.
-   **Perilla de control**: Controla la temperatura, configurada en ON (modo de temporada de verano) y OFF (modo de temporada de invierno).

**Modo coche:**El modo automático solo está disponible cuando el dispositivo se aprende con un panel de control. Después de aprender con el panel de control, puede controlar y configurar el horario de la válvula del radiador automáticamente a través del panel de control (consulte el manual del panel de control para obtener más detalles). En el modo automático, puede usar las mismas funciones que en el modo manual. excepto la perilla de control configurada en la función ON y OFF.

![](<.gitbook/assets/16 (21).png>)

-   _**anti-glaseado**_

Cuando la válvula del radiador detecta un peligro de escarcha, automáticamente abrirá la válvula para que fluya agua caliente a fin de mantener la temperatura y evitar más escarcha.

![](<.gitbook/assets/17 (17).png>)

-   _**Anticalcificación**_

La válvula del radiador se abrirá y cerrará semanalmente para evitar la calcificación. Durante el proceso anticalcificación, la pantalla LCD mostrará un**CALIFORNIA**.

El valor predeterminado para el proceso anticalcificación es las 23:00 horas todos los sábados.

![](<.gitbook/assets/18 (21).png>)

-   _**Función de impulso**_

Mantenga presionado el botón Boost durante 3 segundos para acelerar temporalmente el proceso de calentamiento abriendo aún más la válvula. La función de impulso dura 5 minutos (pantallas LCD: cuenta atrás de 300 segundos). Si desea cancelar la función de impulso, presione y mantenga presionado el botón durante 3 segundos nuevamente.

![](<.gitbook/assets/19 (22).png>)

-   _**Compensación del punto de ajuste**_

El dispositivo generalmente se instala en la esquina de la habitación y cerca de la tubería de calefacción. Como resultado, su lectura de temperatura puede desviarse de la temperatura ambiente en el centro de la habitación. Utilice la función de compensación del punto de ajuste para compensar la desviación.

Para calcular la compensación del punto de ajuste, simplemente reste la temperatura ambiente a la temperatura del dispositivo.

Ejemplo: si la temperatura del dispositivo es de 20 °C y la temperatura ambiente es de 18 °C, entonces la compensación del punto de ajuste = 18 – 20 = -2 °C.

Después de aplicar la compensación del punto de ajuste, el dispositivo funcionará de acuerdo con la temperatura ajustada.

Por ejemplo: si la lectura de temperatura del dispositivo es 20 °C, la compensación del punto de ajuste es -2 °C, el dispositivo funcionará utilizando 18 °C como referencia real.

Para programar la compensación del punto de ajuste:

-   1.  Mantenga presionado el![](<.gitbook/assets/20 (11).jpeg>)durante 3 segundos para ingresar al ajuste de compensación.
    2.  Gire la perilla de control hasta alcanzar la temperatura de compensación deseada.
    3.  Presione cualquier tecla para finalizar y salir del ajuste de compensación.
-   _**Ventana abierta**_

Si la válvula del radiador detecta que la temperatura interior cae rápidamente al abrir la ventana, la válvula del radiador activará la función Abrir ventana cerrando parcialmente la válvula para reducir el ajuste de temperatura durante 15 minutos. El

La pantalla LCD mostrará el símbolo y el dispositivo comprobará la temperatura cada minuto. Después de 15 minutos, la válvula del radiador volverá a la temperatura establecida, la válvula se abrirá nuevamente y la función de ventana abierta se cerrará.

-   _**Perilla de control**_

Gire la perilla de control para ajustar la temperatura, gírela en el sentido de las agujas del reloj para reducir la temperatura y en el sentido contrario a las agujas del reloj para aumentarla. El rango de temperatura ajustable es de 5°C a 30°C. Si gira la perilla de control a menos de 5 °C para encender, después de 1 minuto, la válvula del radiador abrirá la válvula completamente para preservar la energía de la batería; si gira la perilla de control a menos de 5 °C para apagar, después de 1 minuto, La válvula del radiador cerrará la válvula por completo. Para desactivar el estado ON/OFF, gire la perilla de control o presione

botón . La función Boost no está disponible cuando la perilla de control está configurada en estado ON/OFF.

**EN:**Cuando se coloca en ON, la válvula se abre completamente. Esta función se utiliza para conservar la vida útil de la batería durante el verano, cuando no se requiere calefacción. No utilice esta función en invierno cuando el calentador esté activado,

2

De lo contrario, la temperatura ambiente aumentará incontrolablemente.

**APAGADO:**Cuando se apaga, la válvula se cierra completamente. Esta función se utiliza cuando el calentador está activado pero no se requiere calefacción en una habitación sin ocupantes.

-   _**Función de bloqueo de teclas**_

Mantenga presionados el botón Auto/Manual y el botón durante 3 segundos para habilitar la función de bloqueo de teclas. Si

exitosamente la pantalla LCD mostrará el símbolo. Todas las teclas y acciones de la perilla de control no responderán**.**Si lo desea

Para cancelar la función de bloqueo de teclas, mantenga presionados el botón Auto/Manual y el botón durante 3 segundos de la misma manera.

-   _**Control remoto**_

Después de que la válvula del radiador se una a una red Z-Wave, puede controlar la válvula del radiador a través del coordinador o puerta de enlace de la red Z-Wave. Consulte el manual de su coordinador/puerta de enlace Z-Wave para obtener más información. Las siguientes funciones solo están disponibles para configurar a través del coordinador y la puerta de enlace Z-Wave:

-   -   **Cronograma:**

Solo puede programar la configuración del horario a través del coordinador/puerta de enlace de red Z-Wave.

Configuración de horarios: se pueden programar hasta 5 horarios para cada día de la semana con modo, punto de ajuste y hora de inicio.

Control de Horarios:

Normal: la válvula del radiador ejecutará la configuración programada en consecuencia.

Sin programación: la válvula del radiador no ejecutará ninguna programación establecida hasta que se establezca nuevamente en Normal.

-   _**Agregar dispositivo (inclusión)**_

Este producto se puede incluir y operar en cualquier red Z-Wave con otros dispositivos certificados Z-Wave de otros fabricantes y/u otras aplicaciones. Todos los nodos de la red que no funcionan con baterías actuarán como repetidores independientemente del proveedor para aumentar la confiabilidad de la red.

-   Retire la tapa trasera de la válvula del radiador e inserte 2 pilas alcalinas AA para encender el radiador.

Válvula, la pantalla LCD mostrará**En s**y el ícono parpadeará para indicar que el motor de la válvula del radiador está funcionando.

-   Coloque el panel de control Z-Wave en**Modo de inclusión**(consulte el manual del panel de control Z-Wave).
-   En 1,5 segundos, presione el botón Boost 3 veces
-   Consulte el manual de funcionamiento de la puerta de enlace Z-Wave o del panel de control para completar el proceso de adición.
-   Si el dispositivo ya se ha agregado (incluido) en otra puerta de enlace/panel de control Z-Wave, o si el dispositivo no se puede agregar a la puerta de enlace/panel de control Z-Wave actual, intente eliminarlo primero (consulte_**Quitar dispositivo**_).
-   Cuando el motor deje de funcionar y el ícono cambie a fijo, coloque la tapa de la válvula en la tubería.
-   Gire la tapa de la válvula en el sentido de las agujas del reloj para apretar la válvula del radiador.
-
-   _**Eliminación del dispositivo (exclusión)**_

El dispositivo debe eliminarse de la red Z-Wave existente antes de agregarlo a otra.**Modo de exclusión**

-   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de exclusión**(consulte el manual del Z-Wave o del panel de control).

3

-   -   En 1,5 segundos, presione el botón Boost 3 veces y el dispositivo se eliminará de la red Z-Wave.

**Restablecimiento de fábrica**

El restablecimiento de fábrica del dispositivo lo restaurará a la configuración predeterminada de fábrica (es decir, no estará incluido en ninguna red Z-Wave). Utilice este procedimiento únicamente si la puerta de enlace Z-Wave o el panel de control se pierden o no funcionan.

-   -   Mantenga presionado el botón Boost durante 10 segundos para restablecer los valores de fábrica.
-   _**Prueba de rango**_

Para probar si el dispositivo puede comunicarse con la puerta de enlace Z-Wave o el panel de control:

-   -   Coloque la puerta de enlace/panel en modo de prueba de alcance (Walk Test).
    -   Mantenga presionado el botón Boost durante un segundo.
    -   La puerta de enlace/panel debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual de operación de la puerta de enlace/panel).
-   _**Modo de suspensión Z-Wave**_
    -   La válvula del radiador entrará en el modo de suspensión Z-Wave (para conservar energía) después de despertarse por un corto período de tiempo (~10 segundos). Mientras está en el modo de suspensión Z-Wave, las puertas de enlace o paneles de control Z-Wave no pueden enviar comandos a la válvula del radiador.
    -   Para programar la válvula del radiador utilizando el panel de control/puerta de enlace Z-Wave, envíe los comandos a la válvula del radiador dentro del período de activación.
-   _**Comando de conjunto de configuración**_
    -   La válvula del radiador permite al usuario configurar valores de retardo de apertura y cierre. El valor predeterminado es 2 minutos (máximo: 5 minutos).
    -   Si se configuran 4 minutos para el retardo de apertura, el dispositivo enviará un informe de apertura del estado de funcionamiento 4 minutos después de que se abra la válvula. Si se configuran 4 minutos para el retraso de cierre, la válvula se cerrará 4 minutos después de que se envíe un informe de cierre del estado de operación.
    -   La válvula también cuenta con informe de estado periódico; el valor predeterminado es 60 minutos. El temporizador se restablecerá cada vez que se cambie el estado de funcionamiento.
    -   El comando de configuración se utiliza para establecer el valor de un parámetro de configuración:

| 7                           |                                                       | 6                                           |                                                | 5      |                               | 4                        |   | 3 |   | 2            |   |        | 1 |   | 0 |
| --------------------------- | ----------------------------------------------------- | ------------------------------------------- | ---------------------------------------------- | ------ | ----------------------------- | ------------------------ | - | - | - | ------------ | - | ------ | - | - | - |
|                             |                                                       |                                             | Clase de comando = COMANDO_CLASE_CONFIGURACIÓN |        |                               |                          |   |   |   |              |   |        |   |   |   |
|                             |                                                       |                                             |                                                |        | Comando=CONFIGURACIÓN_COLOCAR |                          |   |   |   |              |   |        |   |   |   |
|                             |                                                       |                                             |                                                |        |                               | Número de parámetro      |   |   |   |              |   |        |   |   |   |
| Por defecto                 |                                                       |                                             |                                                |        | Reservado                     |                          |   |   |   |              |   | Tamaño |   |   |   |
|                             |                                                       |                                             |                                                |        |                               | Valor de configuración 1 |   |   |   |              |   |        |   |   |   |
|                             |                                                       |                                             |                                                |        |                               |                          | … |   |   |              |   |        |   |   |   |
|                             |                                                       |                                             |                                                |        |                               | Valor de configuración N |   |   |   |              |   |        |   |   |   |
|                             |                                                       |                                             |                                                |        |                               |                          |   |   |   |              |   |        |   |   |   |
| DOMINIO_CLASE_CONFIGURACIÓN |                                                       | Número de parámetro                         |                                                | Tamaño |                               | Valor                    |   |   |   |              |   |        |   |   |   |
|                             |                                                       |                                             |                                                |        |                               |                          |   |   |   |              |   |        |   |   |   |
|                             |                                                       | Punto fijo_compensar                        |                                                |        |                               | 0                        |   |   |   |              | 2 | 0000   |   |   |   |
|                             |                                                       |                                             |                                                |        |                               |                          |   |   |   |              |   |        |   |   |   |
|                             | Retardo de informe de estado abierto de operación     |                                             | 1                                              |        |                               |                          |   | 1 |   | 2 minutos)   |   |        |   |   |   |
|                             |                                                       |                                             |                                                |        |                               |                          |   |   |   |              |   |        |   |   |   |
|                             | Retraso del informe de cierre del estado de operación |                                             | 2                                              |        |                               |                          |   | 1 |   | 2 minutos)   |   |        |   |   |   |
|                             |                                                       |                                             |                                                |        |                               |                          |   |   |   |              |   |        |   |   |   |
|                             |                                                       | Informe del período del estado de operación |                                                | 3      |                               |                          |   |   | 1 | 60 (minutos) |   |        |   |   |   |
|                             |                                                       |                                             |                                                |        |                               |                          |   |   |   |              |   |        |   |   |   |

-   Valor de compensación del punto de ajuste: 0x0064 = 100 = 1,00 ℃.

**Información de onda Z**

**Tipo de dispositivo:**Termostato

**Tipo de rol:**Escuchando al esclavo durmiente (LSS)

**Soporte/Control de Clase de Comando**

**Soporte CC obligatorio:**Asociación CC, v2 o más reciente

Información del grupo de asociación CC

CC de la batería

Restablecimiento del dispositivo localmente CC

CC específico del fabricante

Nivel de potencia CC

Versión CC, v2 o más reciente

Z-Wave Plus Información CC

Modo termostato CC

Punto de ajuste del termostato CC

Horario CC

4

Sensor CC multinivel

Hora CC

Metadatos de actualización de firmware CC

Estado de funcionamiento del termostato CC

-   _**Grupos de Z-Wave (clase de comando de asociación versión 2)**_

Grupo 1 para “LifeLine”:

Informe de batería CC

Restablecimiento del dispositivo localmente CC (COMANDO_CLASE_DISPOSITIVO_REINICIAR_EN LA ZONA)

Modo termostato CC

Punto de ajuste del termostato CC

Sensor CC multinivel

Grupo 2 para “Estado de funcionamiento del termostato”

Estado de funcionamiento del termostato CC

-   Restablecimiento de fábrica

Cuando la válvula del radiador se restablece a los valores predeterminados de fábrica, enviará el reinicio del dispositivo localmente a todos los nodos del grupo 1.

5
