# VESTA 008 LED

**Cámara con sensor de movimiento PIR**

**VST-862**

**Introducción**

VST-862 es una cámara con sensor de movimiento infrarrojo pasivo (PIR). Es capaz de enviar señales inalámbricas e imágenes capturadas (calidad de imagen de hasta 640 x 480 píxeles) al Panel de control al detectar movimiento.

La cámara PIR está diseñada para ofrecer un rango de detección típico de 12 metros cuando se monta a 2 metros sobre el suelo. Los modelos inmunes a mascotas admiten inmunidad a mascotas de hasta 27 kg dentro de un rango de 7 metros para minimizar situaciones de falsas alarmas. Para modelos compatibles con el repetidor RP-29/enrutador RMB-29 de Climax\*\*(solo modelos P5)\*\*, el alcance de la comunicación RF se puede ampliar aún más a zonas de difícil acceso.

La cámara PIR consta de un diseño de dos partes formada por una cubierta y una base. La cubierta contiene toda la electrónica y la óptica y la base proporciona un medio de fijación. La base tiene orificios ciegos para permitir el montaje en una superficie plana o en una esquina con un soporte triangular para montaje en esquina.

**La serie VST-862 incluye los siguientes modelos:**

| **Nombre del modelo** | **LED intermitente** | **LED infrarrojo** | **inmune a las mascotas** | **Compatible con**      |
| --------------------- | -------------------- | ------------------ | ------------------------- | ----------------------- |
|                       |                      |                    |                           | **Reloj de repetición** |
| VST-862-(P5)          | EN                   |                    |                           | Sólo modelo P5          |
|                       |                      |                    |                           |                         |
| VST-862-IL-(P5)       |                      | EN                 |                           | Sólo modelo P5          |
|                       |                      |                    |                           |                         |
| VST-862P-(P5)         | EN                   |                    | EN                        | Sólo modelo P5          |
|                       |                      |                    |                           |                         |
| VST-862P-IL-(P5)      |                      | EN                 | EN                        | Sólo modelo P5          |
|                       |                      |                    |                           |                         |

![](<.gitbook/assets/0 (21).jpeg>)

**Identificación de piezas**

\*\*1.\*\***LED de destello/LED infrarrojo**

El LED de flash (para 862(P)) o el LED de infrarrojos (para 862(P)-IL) proporciona suficiente luz para capturar imágenes en condiciones de poca iluminación.

**2. LED azul/botón de función**

**LED azul:**

(Por favor refiérase a\_**Indicador LED**\_descripción a continuación para más detalles)

**Uso del botón de función:**

*
  * Mantenga presionado el botón durante 3 segundos para enviar un código de aprendizaje, suéltelo cuando la luz LED azul se encienda. (Para el panel que funciona con baterías, después de presionar y mantener presionado el botón durante 3 segundos, presione el botón**de nuevo**durante un segundo para enviar un código de aprendizaje).
  * Presione el botón una vez para ingresar al modo de prueba durante 3 minutos.
  * Presione el botón una vez para enviar un código de aprendizaje al repetidor/enrutador. (solo modelos P5)

1. **Sensor de infrarrojos**
2. **Lente de cámara PIR**
3. **Tapa del compartimento de la batería**
4. **Manibela de encendido**
5. **Compartimiento de la batería**
6. **Interruptor de puente de ajuste de sensibilidad (JP3)**

![](<.gitbook/assets/1 (29).png>)

**Puente encendido\*\*\*\*Puente apagado**

![](<.gitbook/assets/2 (12).jpeg>)

El enlace del puente se inserta conectando los dos pines.

si se elimina el enlace del puente

o "**estacionado**”en un alfiler.

*
  * Puente activado: el nivel de sensibilidad del PIR está configurado en Alto.
  * Puente desactivado: el nivel de sensibilidad del PIR está configurado en Normal. (**Predeterminado de fábrica**)

1. **Interruptor de puente del temporizador de apagado (JP2)**

![](<.gitbook/assets/3 (30).png>)

**Puente encendido**

![](<.gitbook/assets/4 (13).jpeg>)

El enlace del puente se inserta conectando los dos pines.

**Puente apagado**

si se elimina el enlace del puente

o "**estacionado**”en un alfiler.

* Puente encendido: Después de la detección de movimiento, la cámara PIR no entra en modo de suspensión y transmitirá la señal de detección nuevamente inmediatamente si se activa (**Predeterminado de fábrica**).
* Puente apagado: la cámara PIR tiene un "**hora de dormir**”de aproximadamente 1 minuto después de la detección de movimiento para ahorrar energía.

1

**Características**

![](<.gitbook/assets/5 (22).png>)

* _**Indicador LED**_

En el modo de funcionamiento normal, el LED azul no se encenderá excepto en las siguientes situaciones:

*
  * Cuando la cámara PIR tiene batería baja, cada vez que transmite un movimiento detectado, el LED azul parpadeará durante 2 segundos.
  * Cuando se abre la cubierta y se viola el interruptor de manipulación, el LED azul parpadeará durante 2 segundos para indicar que está transmitiendo una señal de "sabotaje".
  * Cuando la condición de Tamper persiste, cada vez que transmita un movimiento detectado, el LED Azul parpadeará durante 2 segundos.
  * Cuando la cámara PIR ingresa al modo de prueba, el LED azul parpadeará durante 1 segundo. Durante el modo de prueba, el LED azul también parpadeará durante 2 segundos cada vez que se detecte un movimiento.
  * Cuando la cámara PIR esté en el período de calentamiento de 30 segundos, el LED azul parpadeará lentamente.
  * Cuando la cámara PIR transmite imágenes capturadas en condiciones de falla (batería baja, interruptor de manipulación activado), el LED azul parpadeará continuamente.
* _**Captura de imagen**_

![](<.gitbook/assets/6 (13).png>)

Cuando el sistema de alarma está armado, la cámara PIR capturará 1, 3 o 6 imágenes de alarma en resoluciones de 640 x 480 o 320 x 240 (programables desde el panel de control) al detectar movimiento. También puede solicitar manualmente a la cámara PIR que tome una fotografía a través del Panel de control. Las imágenes capturadas se transferirán al Panel de control para que los usuarios las vean.

![](<.gitbook/assets/7 (10).png>)

_\\_

*
  * Si su cámara PIR está instalada en una ubicación donde el campo de visión de la cámara es un entorno complejo con luz intensa o muchos colores, las imágenes capturadas tendrán un gran tamaño de archivo, lo que posiblemente provocará un truncamiento cuando las imágenes se transmitan al Panel de control. .
* _**Período de calentamiento**_

![](<.gitbook/assets/8 (12).png>)

Cuando el sistema del panel de control ingresa al modo armado, o cuando la cámara PIR se pone en modo de prueba, la cámara PIR se calentará durante 30 segundos. Durante el período de calentamiento de 30 segundos, la cámara PIR no se activará. El LED azul parpadeará lentamente durante el período de calentamiento solo cuando el PIR entre al modo de prueba.

![](<.gitbook/assets/9 (13).png>)

* _**Tiempo de dormir**_

Cuando**Interruptor de puente 2**está configurado en Apagado, la cámara PIR tiene un “**hora de dormir**”de aproximadamente 1 minuto para ahorrar energía. Después de transmitir un movimiento detectado, la cámara PIR no retransmitirá durante 1 minuto. Cualquier movimiento detectado durante este período restablecerá el tiempo de sueño a 1 minuto. Por lo tanto, el movimiento continuo delante de la cámara PIR no agotará la batería.

![](<.gitbook/assets/10 (3).jpeg>)

* _**Detección de batería y batería baja**_

La cámara PIR utiliza dos**Pilas alcalinas “AA” de 1,5 V**en conexión en serie como fuente de energía. Retire la tapa del compartimento de las baterías e inserte las baterías para activar la cámara PIR.

La cámara PIR cuenta con la función de detección de batería baja. Cuando el voltaje de la batería es bajo, la cámara PIR transmitirá la señal de batería baja al panel de control. Si se detecta movimiento bajo la condición de batería baja, el LED azul parpadeará durante 2 segundos.

Al cambiar la batería, después de retirar la batería vieja, presione el interruptor de manipulación o el botón de función dos veces para descargarla completamente antes de insertar baterías nuevas.

![](<.gitbook/assets/11 (8).png>)

* _**Protección contra manipulación**_

La cámara PIR está protegida por un interruptor de manipulación que se comprime cuando la cámara PIR está instalada correctamente. Cuando se retira la cámara PIR de la superficie montada o se abre su cubierta, se activará el interruptor de manipulación y la cámara PIR enviará una señal de apertura de manipulación al panel de control del sistema para recordarle al usuario la condición. Si se detecta movimiento cuando el interruptor de manipulación está abierto, el LED azul parpadeará durante 2 segundos.

![](<.gitbook/assets/12 (11).png>)

* _**Supervisión**_

La cámara PIR realizará una autoprueba periódicamente transmitiendo una señal de supervisión una vez cada 90 a 110 minutos.

![](<.gitbook/assets/13 (9).png>)

* _**Modo de prueba**_
  * El modo de prueba le permite verificar el rango de detección de la cámara PIR (no la cobertura de disparo).
  * Presione el botón Función una vez para ingresar al modo de prueba durante 3 minutos, el LED azul parpadeará durante 1 segundo.
  * La cámara PIR se calentará durante 30 segundos. No active la cámara durante este período de calentamiento.
  * Después del período de calentamiento, puede activar la cámara PIR para verificar el rango de detección de IR. Si se activa la cámara PIR, el LED azul parpadeará durante 2 segundos.
* _**Aprendiendo**_
  * Encienda la cámara PIR tirando del aislante de la batería ubicado en la tapa del compartimiento de la batería.
  * Coloque el Panel de control en modo de aprendizaje; consulte el manual del Panel de control para obtener más detalles.
  * Mantenga presionado el botón de función durante 3 segundos, suelte el botón cuando se encienda el LED azul. (Para

![](<.gitbook/assets/14 (5).jpeg>)

2

panel que funciona con baterías, después de presionar y mantener presionado el botón de función durante 3 segundos, presione el botón de función**de nuevo**por un segundo.)

* El LED azul se encenderá durante 25 segundos en modo de aprendizaje; agregue la cámara PIR al panel de control durante este período (consulte su panel de control para finalizar el proceso de aprendizaje). Si el PIR se agrega exitosamente al Panel de control, el LED azul parpadeará 6 veces para indicarlo. Si no se agrega PIR en 25 segundos, repita el aprendizaje

proceso.

![](<.gitbook/assets/15 (7).png>)

_\\_

*
  *
    *
      * Si la cámara PIR ya existe en un sistema de Panel de control, primero deberá eliminar la cámara PIR del Panel de control antes de poder acceder a ella en un Panel de control diferente.
      * Al aprender la cámara PIR en un repetidor/enrutador, presione el botón de función una vez (en lugar de presionarlo y mantenerlo presionado durante 3 segundos) para enviar un código de aprendizaje. (solo modelos P5)
* _**Prueba de caminata**_
  * Una vez memorizada la cámara PIR, coloque el panel de control en "**Prueba de caminata**", sostenga la cámara PIR en la ubicación deseada y presione el botón de función para confirmar que esta ubicación está dentro del alcance de la señal del panel de control; consulte el manual del panel de control para completar la prueba de caminata.
  * Cuando esté satisfecho de que la cámara PIR funciona en la ubicación elegida, puede proceder al montaje.
* _**Editar área de operación de la cámara PIR**_
  * Siga las instrucciones a continuación para cambiar el área de la cámara PIR en el panel de control
    1. Utilice la función Editar dispositivo del panel para cambiar la configuración del área de la cámara PIR.
    2. Mantenga presionado el botón de función durante 3 segundos en la cámara PIR para enviar una señal al panel y luego suelte el botón cuando el LED se encienda. (Para el panel que funciona con baterías, después de presionar y mantener presionado el botón de función durante 3 segundos, presione el botón de función**de nuevo**durante un segundo para enviar una señal.)

![](<.gitbook/assets/16 (1).jpeg>) ![](<.gitbook/assets/17 (7).png>)

**Instalación**

![](<.gitbook/assets/18 (1).jpeg>)

* _**Guía de instalación**_
  *
    * La cámara PIR está diseñada para montarse en una superficie plana o en una esquina con los tornillos y tapones de fijación incluidos.
    * La base tiene orificios ciegos, donde el plástico es más delgado, para fines de montaje. Dos orificios ciegos son para fijación en superficie y un soporte de montaje triangular se utiliza para fijación en esquina.
    * El rango de detección es de hasta 12 metros si la cámara PIR se monta a 2 metros del suelo.
    * Los modelos Pet-Immune ofrecen un alcance típico de PET IMMUNE de 7 metros cuando se montan entre 1,9 y 2 metros sobre el suelo. Si es necesario, puede ajustar la altura de la cámara PIR según el tamaño de su mascota para lograr un rendimiento inmunológico óptimo. Una ubicación de instalación más alta proporcionará un mayor espacio inmune a las mascotas, pero también aumentará el punto ciego debajo de la cámara PIR.
  * Cuando el VST-862 se monta con un soporte giratorio, no tendrá el área de detección normal (como en el diagrama) ni el rango inmune típico a las mascotas.

![](<.gitbook/assets/19 (1).jpeg>)

**Se recomienda instalar la cámara PIR en las siguientes ubicaciones**

* Monte donde los animales no puedan llegar a la zona de detección trepando a muebles u otros objetos.
* No apunte el detector hacia escaleras por las que puedan subir los animales.
* En una posición tal que un intruso normalmente cruzaría el campo de visión del PIR.
* Entre 1,9 y 2 m sobre el suelo para un mejor rendimiento.
* En una esquina para dar la vista más amplia.
* Donde su campo de visión no esté obstruido, p.e. por cortinas, adornos, etc.

3

* **Limitaciones**

|  | No instalar al aire libre.                                          |  | Evite grandes obstáculos en el área de detección.           |
| - | ------------------------------------------------------------------- | - | ----------------------------------------------------------- |
|   |                                                                     |   |                                                             |
|  | No instale el PIR completamente expuesto a                          |  | Evite el vapor o la alta humedad que pueden causar          |
|   | Luz solar directa.                                                  |   | condensación.                                               |
|   |                                                                     |   |                                                             |
|  | Evite mover objetos en el área de detección, es decir               |  | Evite la luz reflejada por superficies brillantes, p.       |
|   | cortina, tapiz, etc.                                                |   | espejo, ventana.                                            |
|   |                                                                     |   |                                                             |
|  | Evite instalar el PIR en áreas donde los dispositivos               |  | Evite la superficie reflectante en el área de detección.    |
|   | puede causar cambios rápidos de temperatura en el                   |   | Las firmas infrarrojas reflejadas pueden dar lugar a falsas |
|   | área de detección, es decir, aire acondicionado, calentadores, etc. |   | alarma.                                                     |
|   |                                                                     |   |                                                             |

![](<.gitbook/assets/20 (7).png>)

* **Asegúrese de mantener siempre la intensidad de la señal RSSI estable en "4".**

4

* _**Montaje de la cámara PIR**_
  * El PIR está diseñado para montarse en una superficie plana o en una esquina con los tornillos y tapones de fijación incluidos.
  * Para el montaje en esquina, se proporciona un soporte triangular para agregar protección contra manipulación trasera. El soporte también incluye dos orificios ciegos para montar en la pared.
    * Para montaje en superficie, se proporciona un soporte giratorio opcional para que los usuarios ajusten el rango de detección. Con el soporte giratorio, el VST-862 se puede girar 80 grados horizontalmente y 70 grados verticalmente para proporcionar una cobertura óptima.
    * **Montaje en esquina:**
      1. Rompe los dos orificios ciegos del soporte triangular.
      2. Utilice los dos agujeros como plantilla para perforar agujeros en la superficie de la esquina.
      3. Inserte los tacos de pared.
      4. Atornille el soporte triangular en los tacos de pared con los dos punteros de arriba hacia usted.
      5. Coloque la cámara PIR en los ganchos del soporte triangular.
    * **Superficie montanosa:**
      1. Abra la cubierta aflojando el tornillo de la cubierta con un destornillador Philips.
      2. Rompe los 2 nocauts de superficie en el centro de la base.
      3. Utilice los agujeros como plantilla para perforar agujeros en la superficie.
      4. Inserte los tacos si lo fija en yeso o ladrillo.
      5. Atornille la base a los tacos de pared.
      6. Coloque la cubierta en la base y apriete.
  * **Montaje en superficie con soporte giratorio (artículo opcional, se vende por separado):**

El soporte giratorio se puede montar en la pared con los tornillos suministrados.

*
  *
    *
      *
        1. Atornille el soporte giratorio a la pared.
        2. Coloque los 3 ganchos del soporte giratorio en los 3 orificios de la base en consecuencia.
        3. Gire el soporte para obtener el rango de detección adecuado y apriete el tornillo de fijación.

5
