# VESTA 050

**Alarma de reconocimiento de voz (VRA)**

La alarma de reconocimiento de voz (VRA) reconoce comandos vocales o palabras clave preestablecidos y activa una alarma de ayuda. Además de la activación por voz, el VRA también cuenta con un botón grande para que los usuarios soliciten ayuda durante una emergencia.

* **Identificación de piezas**

**Vista frontalVista traseraVista lateral**

![](<.gitbook/assets/0 (39).jpeg>)

1. **Botón de ayuda (con retroiluminación azul)**
   1. Presione una vez para enviar un código de aprendizaje o activar una alarma de pánico
   2. Mantenga presionado el botón durante 8 segundos para enviar un Código de cancelación al Panel de control.
   3. La luz de fondo azul parpadeará cuando se transmita la señal al panel de control.
2. **Indicador LED (verde/ámbar)**

* LED verde encendido: cuando la fuente de alimentación externa está conectada.
* LED verde apagado: cuando se retira la fuente de alimentación externa.
* El LED ámbar parpadea tres veces: se detecta un estado de batería baja cuando se enciende.
* El LED ámbar parpadea una vez cada 5 segundos: se detectó un estado de batería baja durante el funcionamiento.
  1. **Micrófono para VR (Reconocimiento de Voz)**
  2. **Compartimiento de la batería**
  3. **Interruptores DIP**
  4. **Ojo de cerradura**
  5. **Conector CC (con función de bloqueo)**

Conecte un adaptador de corriente CC de 5 V y gírelo 90 grados en el sentido de las agujas del reloj hasta la posición de bloqueo. Para quitar el adaptador, gírelo 90 grados en sentido antihorario hasta la posición abierta original y retírelo.

* **Fuente de alimentación**
  *
    * El VRA se puede alimentar conectándolo a una fuente de alimentación de 5 V CC o dos baterías tipo C.
    * Cuando el VRA está conectado a una fuente de alimentación de 5 V CC, se encenderá el LED verde. Cuando se retira la fuente de alimentación de CC, el VRA pasará a utilizar baterías (si las baterías ya están instaladas y no están agotadas) y continuará funcionando; El LED verde se apagará.
    * Cuando se alimenta con baterías tipo C, el VRA transmitirá cualquier estado de batería baja detectado junto con

1

transmisiones periódicas de señales de estado al panel de control para su visualización correspondiente.

*
  * Al cambiar las baterías, retire la cubierta posterior desatornillando el tornillo de fijación inferior y luego insertando un destornillador de punta plana para levantar la cubierta posterior. Retire las baterías viejas y luego presione el botón Ayuda dos veces para descargarlas por completo antes de insertar baterías nuevas.
* **Señal de supervisión**
  * Después de aprender en el Panel de control, VRA transmitirá automáticamente señales de supervisión cada 30 a 50 minutos.
  * Si el panel de control no ha recibido la señal de supervisión de VRA durante un período de tiempo preestablecido, el panel de control indicará que la alarma de reconocimiento de voz está fuera del rango de señal o está fuera de servicio.
* **Sensibilidad**
  * La función de reconocimiento de voz tiene tres niveles de sensibilidad: alta, media y baja. Cuando el nivel de sensibilidad se establece en alto, VRA detectará más fácilmente la palabra clave/comando y activará la alarma.
  * Utilice una herramienta afilada para ajustar las posiciones del interruptor DIP para establecer el nivel de sensibilidad.

|   |                  |                  |             |                                      |             |   |
| - | ---------------- | ---------------- | ----------- | ------------------------------------ | ----------- | - |
|   |                  |                  |             |                                      |             |   |
|   |                  | **ADEREZO**      |             | **Búsqueda (nivel de sensibilidad)** |             |   |
|   |                  |                  |             |                                      |             |   |
|   | **Interruptor1** |                  |             |                                      |             |   |
|   |                  | **interruptor2** |             |                                      |             |   |
|   |                  |                  |             |                                      |             |   |
|   | APAGADO          |                  | APAGADO     |                                      | Bajo        |   |
|   |                  |                  |             |                                      |             |   |
|   | EN               |                  | APAGADO     |                                      | Medio       |   |
|   |                  |                  |             |                                      |             |   |
|   | APAGADO          |                  | EN          |                                      | Alto        |   |
|   |                  |                  |             |                                      |             |   |
|   |                  |                  |             |                                      |             |   |
|   |                  |                  | **ADEREZO** |                                      | **Función** |   |
|   |                  |                  |             |                                      |             |   |
|   | **interruptor3** |                  |             |                                      | Reservado   |   |
|   |                  | **interruptor4** |             |                                      |             |   |
|   |                  |                  |             |                                      |             |   |

![](<.gitbook/assets/1 (33).jpeg>) ![](<.gitbook/assets/2 (45).png>)

_\\_

*
  * Después de cambiar la configuración del interruptor DIP, desconecte la fuente de alimentación (se deben quitar tanto la fuente de alimentación externa como las baterías) y luego vuelva a conectar la alimentación al VRA. VRA lo hará

Trabaja con el nivel de sensibilidad recién establecido después de volver a encenderlo.

* **Empezando**
  * Retire la cubierta posterior desatornillando el tornillo de fijación inferior y luego insertando un destornillador de punta plana para levantar la cubierta posterior.
  * Según sus necesidades, configure el interruptor de sensibilidad como se muestra en la tabla de posiciones del interruptor DIP.
    * Encienda la alarma de reconocimiento de voz conectándola a una fuente de alimentación de 5 V CC o dos baterías tipo C.
    * Poner el Panel de Control en modo de aprendizaje
    * Presione el botón de la alarma de reconocimiento de voz para transmitir un código de aprendizaje.
    * Consulte el manual de funcionamiento de su panel de control para completar el proceso de aprendizaje.
    * Vuelva a colocar la cubierta trasera.
* **Prueba de caminata**
  *
    * Una vez que el VRA se haya aprendido correctamente, coloque el panel de control en el modo de prueba de caminata, luego presione el botón en el VRA para confirmar que esta ubicación está dentro del alcance de la señal del panel de control. Consulte el manual del panel de control para completar la prueba de caminata.
* **Operación**
  *
    * Después de que VRA se haya aprendido correctamente, al presionar el botón una vez se activará una alarma de ayuda. Cuando se presiona el botón, VRA emitirá un pitido.
    * El Usuario también puede pronunciar el comando vocal específico para activar una Alarma de Ayuda. Cuando se reconocen las palabras desencadenantes, el VRA emitirá un pitido largo.
    * Las palabras de activación pueden ser “Alarma SARA (alemán)” o “Ayúdame (inglés)”, según la versión del firmware. "SARA Alarm (alemán)” debe pronunciarse dos veces en 5 segundos para activar la alarma, mientras

2

“Ayúdame (inglés)” solo es necesario decir una vez para activar la alarma.

* Al presionar y mantener presionado el botón durante 8 segundos o más, se enviará un código de cancelación al panel de control para detener la alarma.

**Formas de buscar ayuda**

![](<.gitbook/assets/3 (45).png>)

O

\*\*Pronuncie la palabra clave desencadenante.\*\***Presione el botón Ayuda.**

![](<.gitbook/assets/4 (29).jpeg>)

_\\_

*
  * Para garantizar la precisión del reconocimiento de voz, evite instalar VRA en una habitación grande o ruidosa.
  * El entorno ideal para el reconocimiento de voz es el silencio o el silencio parcial. Si pronuncia el comando vocal con voz normal, hable a menos de 2 metros del VRA para garantizar que se active la alarma.
  * La función de reconocimiento de voz tiene tres niveles de sensibilidad. Puede probar con ellos y seleccionar el nivel que mejor se adapte a su ubicación de montaje.
* **Instalación**

Después de realizar la prueba de recorrido para confirmar que el VRA se encuentra dentro del alcance de la señal del panel de control y de estar satisfecho de que el nivel de sensibilidad seleccionado funciona en la ubicación elegida, puede continuar con la instalación. Hay dos formas de instalar VRA: montaje en pared e implementación en superficie.

* **Montaje en pared**

Asegúrese de que el VRA esté instalado aproximadamente a la altura del pecho (alrededor de 130 cm a 150 cm sobre el suelo), donde se pueda acceder y operar fácilmente el botón.

*
  1. Identifique el ojo de cerradura en la parte posterior del VRA, taladre un agujero en la pared y coloque el taco de pared provisto (Figura 1). Coloque el tornillo de fijación y deje la parte no roscada para colgar el VRA, como se muestra en la Figura 2.

Figura 1 Figura 2

![](<.gitbook/assets/5 (19).jpeg>) ![](<.gitbook/assets/6 (26).jpeg>)

3

1. Coloque la ranura en forma de cerradura del VRA sobre la cabeza del tornillo. Empuje suave y firmemente el VRA hacia abajo, como se muestra a continuación. (Figura 5,6)

Figura 5 Figura 6

![](<.gitbook/assets/7 (23).jpeg>) ![](<.gitbook/assets/8 (16).jpeg>)

* **Colocación en superficie**

VRA viene con una almohadilla antideslizante en la parte posterior. El dispositivo también se puede desplegar sobre una superficie plana sin instalarlo en una ubicación fija.

![](<.gitbook/assets/9 (23).png>)

4
