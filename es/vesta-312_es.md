# VESTA 312

**Serie Mini-FUEGO-EN VIVO**

**Introducción**

La serie Mini-PIR-ZW es un sensor de movimiento infrarrojo pasivo Z-Wave que es capaz de enviar señales inalámbricas al coordinador en la red Z-Wave al detectar movimiento. El PIR tiene un sensor de temperatura/luz ambiental incorporado opcional que proporciona una lectura de temperatura/lux que se transmitirá a través de la red Z-Wave en intervalos regulares (solo modelo Mini-PIR-LT-ZW).

El PIR se puede configurar utilizando el coordinador Z-Wave para que funcione como un sensor de seguridad que activa la alarma cuando se activa, o como un sensor de ocupación/vacancia que controla la automatización del hogar o las funciones de iluminación a través del coordinador Z-Wave.

El PIR es un dispositivo habilitado para Z-Wave y es totalmente compatible con cualquier red habilitada para Z-Wave.

Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. Aprovechando la red de malla Z-Wave, los comandos se pueden transmitir a su destino a través de productos Z-Wave intermediarios que "escuchan".

La Serie Mini-PIR-ZW incluye los siguientes modelos:

| **Nombre del modelo** | **Detección de movimiento** | **Luz y temperatura** |
| --------------------- | --------------------------- | --------------------- |
|                       |                             | **detección**         |
|                       |                             |                       |
| Mini-FUEGO-EN VIVO    | EN                          |                       |
|                       |                             |                       |
| Mini-FIRE-LT-LIVE     | EN                          | EN                    |
|                       |                             |                       |

**Identificación de piezas**

El PIR se compone de un cuerpo principal y una base. El cuerpo principal debe estar separado de la base para la instalación de la batería y la configuración de la red Z-Wave.

Para separar el cuerpo principal y la base, sostenga el PIR con ambas manos y gire la base hacia la derecha y el cuerpo principal hacia la izquierda para separarlos.

![](<.gitbook/assets/0 (58).png>)

**1. Lente IR con indicador LED**

El indicador LED está ubicado en el centro de la lente IR.

El indicador LED se enciende en las siguientes condiciones:

-   -   Parpadea una vez:

El PIR está transmitiendo código de aprendizaje/restablecimiento de fábrica.

-   -   Parpadea dos veces rápidamente:

El PIR se ha unido con éxito a la red Z-Wave.

-   -   Parpadea en modo de funcionamiento normal:

El PIR ha detectado un movimiento y actualmente se encuentra en condición de batería baja o apertura por manipulación.

1.  **Contraportada**

Retire la cubierta trasera para acceder al compartimiento de la batería y al botón de función.

1.  **Botón de función**
    -   Presione el botón una vez para enviar una señal de supervisión e ingresar al modo de prueba.
    -   Presione 3 veces en 1,5 segundos para transmitir un código de aprendizaje.
    -   Mantenga presionado el botón durante 10 segundos y luego suéltelo para restablecer los valores de fábrica.
2.  **Compartimiento de la batería**

The PIR is powered by one CR123A 3V Lithium battery.

1.  **Tornillo de ajuste del ángulo de la base**
2.  **Orificios de montaje en pared**

1

**Características**

-   _**Tiempo de dormir**_

El PIR tiene un “tiempo de inactividad” de aproximadamente 1 minuto para conservar energía. Después de transmitir un movimiento detectado, el PIR no retransmitirá durante 1 minuto. Cualquier movimiento adicional detectado durante este período de sueño extenderá el tiempo de sueño en otro minuto. De esta manera, el movimiento continuo frente a un PIR no agotará indebidamente la batería.

-   _**Señalización de parada de movimiento**_

Después de cada detección de movimiento, si pasan 30 segundos sin detección, el PIR transmitirá una señal de "detención de movimiento" al coordinador de la red Z-Wave.

-   _**Detección de batería y batería baja**_
    -   El PIR utiliza una batería de litio CR123A de 3 V como fuente de energía. El cuerpo principal del PIR debe retirarse de la base para acceder al compartimiento de la batería. El compartimiento de la batería tiene una tira que se debe presionar debajo de la batería cuando se inserta la batería. Al retirar la masa, simplemente levante la tira.
    -   El PIR cuenta con la función de detección de batería baja. Cuando el voltaje de la batería es bajo, el PIR transmitirá la señal de batería baja al coordinador en la red Z-Wave. Si se detecta movimiento bajo la condición de batería baja, el indicador LED parpadeará para indicarlo.
    -   El PIR informará su porcentaje de batería a la puerta de enlace/panel de control respectivamente al 100 %, 75 %, 50 % y 25 %. Si el voltaje de la batería es bajo (25%), se enviará una señal de Batería baja al Panel de control para notificar al usuario.
    -   Si la batería no se cambia después de la condición de batería baja y está agotada, el LED parpadeará cada 2 segundos y el PIR detendrá toda operación.
    -   Al cambiar la batería, después de quitar la batería vieja, presione el botón de función dos veces para descargarla completamente antes de insertar una batería nueva.
-   _**Protección contra manipulación**_

El PIR está protegido por un interruptor antisabotaje ubicado dentro del cuerpo principal del PIR. El interruptor de manipulación se activa cada vez que se retira el PIR de la base, y el PIR enviará una señal de apertura de manipulación para recordarle al usuario la condición. Si se detecta movimiento cuando el interruptor de manipulación está abierto, el PIR parpadeará para indicarlo.

-   _**Supervisión**_

Esta función utiliza la clase de comando Z-Wave Wake Up. La clase de comando de activación permite que el PIR alimentado por batería notifique al panel de control/puerta de enlace que está despierto y listo para recibir cualquier comando en cola. El período de tiempo para despertarse se programa automáticamente de acuerdo con la configuración del Panel de control cuando se incluye el PIR. La configuración recomendada para la hora de despertarse es de 60 minutos más.

-   _**Modo de prueba**_
    -   El modo de prueba le permite verificar el rango de detección del PIR.
    -   Presione el botón Función una vez para ingresar al modo de prueba durante 3 minutos.
    -   During Test Mode, you can trigger PIR sensor to check its detection coverage. If PIR is triggered, the LED will light up to indicate.
-   _**Detección de temperatura (solo modelo Mini-PIR-LT-ZW)**_
    -   El PIR con sensor de temperatura incorporado transmitirá señales de temperatura regularmente según la configuración. El intervalo predeterminado de fábrica es de 30 minutos.
    -   Cuando la temperatura cambia +/- 2°C, el PIR también transmitirá una señal.
    -   También puede presionar el botón de función una vez para transmitir una señal de temperatura manualmente.
    -   El rango de detección de temperatura es de aproximadamente -10 °C.~ 50°C ( 14°F ~122°F).
-   _**Monitoreo de luz (solo modelo Mini-PIR-LT-ZW)**_
    -   El PIR con sensor de luz ambiental incorporado mide la iluminancia y transmite periódicamente los datos medidos al coordinador de red Z-Wave. El intervalo predeterminado de fábrica es de 30 minutos.
    -   Cuando la iluminancia actual cambia en +/- 10%, el PIR también transmitirá una señal.
    -   También puede presionar el botón de función una vez para transmitir la lectura de lux actual manualmente.
-   _**Agregar dispositivo (inclusión)**_

Este producto se puede incluir y operar en cualquier red Z-Wave con otros dispositivos certificados Z-Wave de otros fabricantes y/u otras aplicaciones. Todos los nodos de la red que no funcionan con baterías actuarán como repetidores independientemente del proveedor para aumentar la confiabilidad de la red.

-   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de inclusión**(consulte el manual de la puerta de enlace Z-Wave o del panel de control).
-   En 1,5 segundos, presione el botón de función 3 veces.
-   Consulte el manual de funcionamiento de la puerta de enlace Z-Wave o del panel de control para completar el proceso de adición.
-   Si ya se ha agregado (incluido) PIR en otra puerta de enlace/panel de control Z-Wave, o si el dispositivo no se puede agregar a la puerta de enlace/panel de control Z-Wave actual, intente eliminarlo primero (consulte_**Quitar dispositivo**_).

2

-   _**Eliminación del dispositivo (exclusión)**_

El PIR debe eliminarse de la red Z-Wave existente antes de agregarlo a otra.

**Modo de exclusión**

-   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de exclusión**(consulte el manual de la puerta de enlace Z-Wave o del panel de control).
-   En 1,5 segundos, presione el botón de función 3 veces y el PIR se eliminará de la red Z-Wave.

**Restablecimiento de fábrica**

_(Utilice el restablecimiento de fábrica únicamente cuando falte el panel de control/puerta de enlace de la red o no esté operativo)._

-   Retire primero la batería del PIR.
-   Mantenga presionado el botón de función. Mientras mantiene presionado el botón de función, encienda el PIR reinsertando la batería, espere 10 segundos para restablecer los valores de fábrica.

_\\<NOTE>_

-   -   El restablecimiento de fábrica del PIR lo restaurará a la configuración predeterminada de fábrica (excluido de la red Z-Wave). La puerta de enlace o el panel de control Z-Wave seguirán manteniendo su configuración Z-Wave. Consulte el manual de la puerta de enlace o del panel de control sobre cómo eliminar la configuración de PIR Z-Wave.
-   _**Prueba de rango**_

Para probar si el PIR puede comunicarse con la puerta de enlace Z-Wave o el panel de control:

-   -   Coloque la puerta de enlace/panel en modo de prueba de alcance (Walk Test).
    -   Presione el botón de función en el PIR.
    -   La puerta de enlace/panel debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual de operación de la puerta de enlace/panel).
-   _**Modo de suspensión Z-Wave**_
    -   El PIR entrará en modo de suspensión Z-Wave (para conservar energía) después de despertarse por un corto período de tiempo (~10 segundos). Mientras está en el modo de suspensión Z-Wave, las puertas de enlace o paneles de control Z-Wave no pueden enviar comandos al PIR.
    -   Para programar el PIR utilizando el panel de control/puerta de enlace Z-Wave, envíe comandos al PIR dentro del período de activación.

**Instalación**

-   _**Altura de montaje y cobertura de detección PIR**_
    -   Hay dos formas de implementar el Mini-PIR: montaje en pared e implementación en superficie.
    -   El PIR tiene una cobertura de detección de un cono de 120∘ al frente. Cuando se despliega en una superficie plana a aproximadamente 1,2 metros sobre el suelo, o se monta en una pared a unos 2 metros de altura, el PIR tiene un alcance máximo de 10 metros.
    -   La dirección del PIR se puede cambiar aflojando el tornillo de ajuste del ángulo en la base para inclinar el PIR hacia arriba y hacia abajo.

![](<.gitbook/assets/1 (86).jpeg>)

3

-   _**Asamblea**_
    -   El PIR está compuesto por el cuerpo principal y la base. Consulte las instrucciones a continuación para fijar el cuerpo principal a la base o separar el cuerpo principal después de la instalación.
        1.  Conecte el cuerpo principal a la base. (Figura 1)
        2.  Incline el PIR hacia atrás hasta que su parte posterior toque la base. (Figura 2)

**Figura 1****Figura 2**

![](<.gitbook/assets/2 (81).png>)

1.  Sostenga el cuerpo principal del PIR con la mano izquierda y la base con la mano derecha. NO toque la lente IR o la lente podría dañarse durante el proceso. (Figura 3, 4)
2.  A**cerrar**Coloque el cuerpo principal en la base, gire el cuerpo principal con la mano izquierda hacia afuera y gire la base con la mano derecha hacia usted al mismo tiempo en dirección opuesta hasta que escuche un clic. (Figura 3)
3.  A**liberar**El cuerpo principal desde la base, gire el cuerpo principal con la mano izquierda hacia usted y presione hacia abajo con el pulgar de la mano derecha en dirección opuesta a usted al mismo tiempo hasta que escuche un clic. (Figura 4)

**figura 3****Figura 4**

![](<.gitbook/assets/3 (79).png>)

-   _**Instalación**_
    1.  Utilice los 2 orificios de montaje en la base PIR como plantilla y taladre orificios en la superficie.
    2.  Inserte los tacos si lo fija en yeso o ladrillo.
    3.  Atornille la base a los tacos de pared. (Figura 5)
    4.  Enganche el cuerpo principal del PIR en la base y gírelo para bloquearlo. (Figura 6, 7)
    5.  Afloje los tornillos de ajuste del ángulo y luego incline el PIR hasta que esté satisfecho con el ángulo de detección. Apriete los tornillos para fijar el PIR en el ángulo establecido. (Figura 8)

**Figura 5****Figura 6****Figura 7****Figura 8**

![](<.gitbook/assets/4 (60).jpeg>)

-   _**Guía de instalación**_
    -   **Se recomienda instalar el PIR en las siguientes ubicaciones.**
        -   En una posición tal que un intruso normalmente se movería a través del campo de visión del PIR de lado a lado.
        -   Donde su campo de visión no esté obstruido, p.e. por cortinas, adornos, etc.
    -   **Limitaciones**
        -   No instale el PIR en un lugar expuesto a la luz solar directa ni cerca de aparatos de calefacción/refrigeración ni de ventilación.
        -   No apunte el PIR hacia fuentes de calor como calentadores, radiadores y ventanas.
        -   No apunte el PIR a la ventana.
        -   Evite obstáculos grandes en el área de detección y evite objetos en movimiento como cortinas.

4

-   _**Información de onda Z**_

**Tipo de dispositivo:**Alarma de humo con notificación de sensor

**Tipo de rol:**Informar sobre esclavo durmiente (RSS)

**Grupo de asociación máximo:**6

**Soporte/Control de Clase de Comando**

**Soporte CC obligatorio:**

Z-Wave Plus Información CC

Versión CC, v2 o más reciente

CC específico del fabricante

Restablecimiento del dispositivo localmente CC

Nivel de potencia CC

CC de la batería

SensorMultinivel CC, V5

Notificación V4 CC

Asociación CC, v2 o más reciente

Información del grupo de asociación CC

Configuración CC

Actualización de firmware MD CC

-   _**Grupos de Z-Wave (clase de comando de asociación versión 2)**_

Grupo 1 para “LifeLine”:

Sensor multinivel CC,V5

Notificación CC,V4 (COMANDO_CLASE_Notificación)

Batería CC (COMANDO_CLASE_BÁSICO)

Restablecimiento del dispositivo localmente CC

Grupo 2 para “Conjunto PIR Básico”:

CC básico (COMANDO_CLASE_BÁSICO)

Cuando PIR está activo, el Grupo 2 enviará la Configuración básica (0xFF), la Restauración enviará (0x00)

Grupo 3 para “representante de notificación PIR”:

Notificación CC, V4 (COMANDO_CLASE_NOTIFICACIÓN)

Solo envía PIR Activo (07,08) y Restaurar (07,00,01,08)

Grupo 4 para “Informe de temperatura/luz” (solo modelo Mini-PIR-LT-ZW):

Sensor Multilevel CC, V5 (COMMAND_CLASE_SENSOR_MULTI NIVEL)

Solo envía temperatura/luz

Grupo 5 para “representante de notificaciones HD”:

Notificación CC,V4 (COMANDO_CLASE_NOTIFICACIÓN)

Cuando HD esté activo, el Grupo 5 enviará (04,02), Restaurar enviará (04,06)

Grupo 6 para “representante de manipulación”:

Notificación CC,V4 (COMANDO_CLASE_NOTIFICACIÓN)

Cuando se abre la manipulación, el grupo 6 enviará (07,03), la restauración enviará (07,00,01,03)

5
