# VESTA 211N

**Cámara con sensor de movimiento PIR (VST-892)**

**Introducción**

VST-892 es una cámara con sensor de movimiento infrarrojo pasivo (PIR). Es capaz de enviar señales inalámbricas e imágenes capturadas (calidad de imagen de hasta 640 x 480 píxeles) al Panel de control al detectar movimiento.

La cámara PIR está diseñada para ofrecer un rango de detección típico de 12 metros cuando se monta entre 2,3 y 2,5 metros sobre el suelo. Cuando la función de inmunidad a mascotas está habilitada, la cámara con sensor de movimiento no detectará mascotas de hasta 25 kg cuando se monte a entre 2,3 y 2,5 metros sobre el suelo. VST-892 también es compatible con el repetidor RP-29/enrutador RMB-29 de Climax, que puede ampliar aún más el rango de comunicación RF a áreas de difícil acceso.

VST-892 está diseñado con el detector de proximidad digital. La función antienmascaramiento permite detectar cualquier intento de cegar el detector colocando objetos en su campo de visión.

La configuración remota es compatible con la cámara PIR. Además de ajustar los interruptores de puente, los usuarios también pueden habilitar/deshabilitar la función de inmunidad a mascotas y ajustar la sensibilidad de la cámara PIR desde la página web del Panel de control o Home Portal Server.

La cámara PIR consta de un diseño de dos partes formada por una cubierta y una base. La cubierta contiene toda la electrónica y la óptica y la base proporciona un medio de fijación. La base tiene orificios ciegos para permitir el montaje en una superficie plana, o se proporciona un soporte de montaje para montaje en esquina y en superficie.

**La serie VST-892 incluye los siguientes modelos**:

VST-892 – Cámara con sensor de movimiento PIR y flash LED

VST-892-IL – Cámara con sensor de movimiento PIR y LED infrarrojo

**Identificación de piezas**

![](<.gitbook/assets/0 (86).jpeg>)

**1. LED de destello/LED infrarrojo**

El LED de flash (para VST-892) o el LED de infrarrojos (para VST-892-IL) proporciona suficiente luz para capturar imágenes en condiciones de poca iluminación.

**2. LED azul/botón de función**

**LED azul:**

(Por favor refiérase a\_**Indicador LED**\_descripción a continuación para más detalles)

**Uso del botón de función:**

*
  * Mantenga presionado el botón durante 3 segundos para enviar un código de aprendizaje, suéltelo cuando la luz LED azul se encienda.
  * Presione el botón una vez para ingresar al modo de prueba durante 3 minutos.
  * Presione el botón una vez para enviar un código de aprendizaje al repetidor/enrutador. (solo modelos P5)

1. **Detector de proximidad digital**

El detector de proximidad digital se utiliza para detectar cualquier intento de enmascaramiento (bloqueo) por parte de un intruso.

1. **Sensor de infrarrojos**
2. **Lente de cámara PIR**
3. **Compartimiento de la batería**
4. **Manibela de encendido**
5. **Interruptor de puente de activación/desactivación de inmunidad a mascotas (JP3)**

![](<.gitbook/assets/1 (75).jpeg>) ![](<.gitbook/assets/2 (67).png>)

**Puente encendido**

![](<.gitbook/assets/3 (64).jpeg>)

El enlace del puente se inserta conectando los dos pines.

**Puente apagado**

El enlace del puente se elimina o "**estacionado**”en un alfiler.

1

Cuando está activado, la inmunidad a mascotas está desactivada (valor predeterminado de fábrica).

Cuando se establece en APAGADO, la inmunidad a mascotas está habilitada.

\*\*9.\*\***Interruptor de puente aumentador de sensibilidad (JP4)**

Cuando se establece en ON, la sensibilidad de detección del PIR es alta.

Cuando se configura en APAGADO, la sensibilidad de detección del PIR está en el nivel normal (valor predeterminado de fábrica).

1. **Aislador de batería**
2. **Tapa del compartimento de la batería**
3. **Soporte de montaje**

**Características**

![](<.gitbook/assets/4 (71).png>)

* _**Indicador LED**_

En el modo de funcionamiento normal, el LED azul no se encenderá excepto en las siguientes situaciones:

* Cuando la cámara PIR tiene batería baja, cada vez que transmite un movimiento detectado, el LED azul parpadeará durante 2 segundos.
* Cuando se abre la cubierta y se viola el interruptor de manipulación, el LED azul parpadeará durante 2 segundos para indicar que está transmitiendo una señal de "sabotaje".
* Cuando la condición de Tamper persiste, cada vez que transmita un movimiento detectado, el LED Azul parpadeará durante 2 segundos.
* Cuando la cámara PIR ingresa al modo de prueba, el LED azul parpadeará durante 1 segundo. Durante el modo de prueba, el LED azul también parpadeará durante 2 segundos cada vez que se detecte un movimiento.
* Cuando la cámara PIR esté en el período de calentamiento de 30 segundos, el LED azul parpadeará lentamente.
* Cuando la cámara PIR transmite imágenes capturadas en condiciones de falla (batería baja, interruptor de manipulación activado), el LED azul parpadeará continuamente.

El LED no parpadeará si la manipulación de la cámara PIR y la batería son normales y no están en modo de prueba.

Si el LED parpadea para indicar transmisión de señal, parpadeará dos veces rápidamente al recibir el reconocimiento del panel.

![](<.gitbook/assets/5 (72).png>)

* _**Captura de imagen**_

Cuando el sistema de alarma está armado, la cámara PIR capturará 1, 3 o 6 imágenes de alarma en resoluciones de 640 x 480 o 320 x 240 (programables desde el panel de control) al detectar movimiento. También puede solicitar manualmente a la cámara PIR que tome una fotografía a través del Panel de control. Las imágenes capturadas se transferirán al Panel de control para que los usuarios las vean.

![](<.gitbook/assets/6 (52).png>)

_\\_

*
  * Si su cámara PIR está instalada en un lugar donde el campo de visión de la cámara es un entorno complejo con luz intensa o muchos colores, las imágenes capturadas tendrán un gran tamaño de archivo, lo que posiblemente provocará un truncamiento cuando las imágenes se transmitan al Panel de control. .
* _**Período de calentamiento**_

![](<.gitbook/assets/7 (48).png>)

Cuando el sistema del panel de control ingresa al modo armado, o cuando la cámara PIR se pone en modo de prueba, la cámara PIR se calentará durante 30 segundos. Durante el período de calentamiento de 30 segundos, la cámara PIR no se activará. El LED azul parpadeará lentamente durante el período de calentamiento solo cuando el PIR entre al modo de prueba.

![](<.gitbook/assets/8 (47).png>)

* _**Tiempo de dormir**_

La cámara PIR tiene un "**hora de dormir**”de aproximadamente 1 minuto para ahorrar energía. Después de transmitir un movimiento detectado, la cámara PIR no retransmitirá durante 1 minuto. Cualquier movimiento detectado durante este período restablecerá el tiempo de sueño a 1 minuto. Por lo tanto, el movimiento continuo delante de la cámara PIR no agotará la batería.

![](<.gitbook/assets/9 (32).jpeg>)

* _**Detección de batería y batería baja**_

La cámara PIR utiliza dos**Pilas alcalinas “AA” de 1,5 V**en conexión en serie como fuente de energía.

La cámara PIR cuenta con la función de detección de batería baja. Cuando el voltaje de la batería es bajo, la cámara PIR transmitirá la señal de batería baja al panel de control. Si se detecta movimiento bajo la condición de batería baja, el LED azul parpadeará durante 2 segundos.

Al cambiar la batería, después de retirar la batería vieja, presione el interruptor de manipulación o el botón de función dos veces para descargarla por completo antes de insertar baterías nuevas.

![](<.gitbook/assets/10 (45).png>)

* _**Protección contra manipulación**_

La cámara PIR está protegida por un interruptor de manipulación que se comprime cuando la cámara PIR está instalada correctamente. Cuando se retira la cámara PIR de la superficie montada o se abre su cubierta, se activará el interruptor de manipulación y la cámara PIR enviará una señal de apertura de manipulación al panel de control del sistema para recordarle al usuario la condición. Si se detecta movimiento cuando el interruptor de manipulación está abierto, el LED azul parpadeará durante 2 segundos.

![](<.gitbook/assets/11 (37).png>)

* _**Supervisión**_

La cámara PIR realizará una autoprueba periódicamente transmitiendo una señal de supervisión una vez cada 90 a 110 minutos.

2

* ![](<.gitbook/assets/12 (38).png>)_**Modo de prueba**_
  * El modo de prueba le permite verificar el rango de detección de la cámara PIR (no la cobertura de disparo).
  * Presione el botón Función una vez para ingresar al modo de prueba durante 3 minutos, el LED azul parpadeará durante 1 segundo.
  * La cámara PIR se calentará durante 30 segundos. No active la cámara durante este período de calentamiento.
  * Después del período de calentamiento, puede activar la cámara PIR para verificar el rango de detección de IR. Si se activa la cámara PIR, el LED azul parpadeará durante 2 segundos.
* _**Aprendiendo**_
  * Encienda la cámara PIR quitando el aislante de la batería.
  * Coloque el Panel de control en modo de aprendizaje; consulte el manual del Panel de control para obtener más detalles.
  * Mantenga presionado el botón de función durante 3 segundos, suelte el botón cuando el LED azul se encienda. (Para aprender a utilizar el panel que funciona con baterías, después de presionar y mantener presionado el botón de función durante 3 segundos, presione el botón de función nuevamente durante un segundo).
  * El LED azul se encenderá durante 25 segundos en modo de aprendizaje; agregue la cámara PIR al Panel de control durante este período (consulte su Panel de control para finalizar el proceso de aprendizaje). Si el PIR se agrega exitosamente al Panel de control, el LED azul parpadeará 6 veces para indicarlo. Si no se agrega PIR en 25 segundos, repita el aprendizaje

![](<.gitbook/assets/13 (28).jpeg>)

proceso.

![](<.gitbook/assets/14 (27).png>)

_\\_

*
  *
    *
      * Si la cámara PIR ya existe en un sistema de Panel de control, primero deberá eliminar la cámara PIR del Panel de control antes de poder aprenderla en un Panel de control diferente.
      * Al aprender la cámara PIR en un repetidor/enrutador, presione el botón de función una vez (en lugar de presionarlo y mantenerlo presionado durante 3 segundos) para enviar un código de aprendizaje. (solo modelos P5)
* _**Prueba de caminata**_
  * Una vez memorizada la cámara PIR, coloque el panel de control en "**Prueba de caminata**", sostenga la cámara PIR en la ubicación deseada y presione el botón de función para confirmar que esta ubicación está dentro del alcance de la señal del panel de control; consulte el manual del panel de control para completar la prueba de caminata.
  * Cuando esté satisfecho de que la cámara PIR funciona en la ubicación elegida, puede proceder al montaje.
* _**Editar área de operación de la cámara PIR**_
  * Siga las instrucciones a continuación para cambiar el área de la cámara PIR en el panel de control:
    1. Utilice la función Editar dispositivo del panel para cambiar la configuración del área de la cámara PIR.
    2. Mantenga presionado el botón de prueba durante 3 segundos en la cámara PIR para enviar una señal al panel y luego suelte el botón cuando el LED se encienda.
* _**Función de inmunidad a las mascotas**_

![](<.gitbook/assets/15 (21).jpeg>) ![](<.gitbook/assets/16 (29).png>) ![](<.gitbook/assets/17 (23).png>)

El sensor PIR admite la función de inmunidad a mascotas y no detectará mascotas de hasta 25 kg para minimizar la situación de falsas alarmas. La función de inmunidad a mascotas se puede habilitar/deshabilitar configurando la posición del interruptor de puente (JP3). Cuando el interruptor de puente (JP3) está en ON, la inmunidad a mascotas está desactivada (valor predeterminado de fábrica). Cuando el interruptor de puente (JP3) está en APAGADO, se habilita la inmunidad a mascotas. La función de inmunidad a mascotas también se puede ajustar mediante configuración remota como se describe a continuación.

![](<.gitbook/assets/18 (28).png>)

* _**Función de aumento de sensibilidad**_

Puede utilizar la función de aumento de sensibilidad para aumentar la sensibilidad de detección del PIR. Para aumentar la sensibilidad de detección, configure el interruptor de puente (JP4) en ON. Para mantener una sensibilidad de detección normal, configure el interruptor de puente (JP4) en APAGADO (valor predeterminado de fábrica). La función de aumento de sensibilidad también se puede ajustar mediante configuración remota como se describe a continuación.

![](<.gitbook/assets/19 (29).png>)

\_**Configuración remota**\_

 La cámara PIR admite la configuración remota de la inmunidad y sensibilidad de las mascotas.

 Cuando la cámara PIR está encendida, su función de inmunidad a mascotas y su sensibilidad están determinadas por los ajustes JP3 y JP4. Los usuarios pueden ajustar la configuración de los puentes o cambiar de forma remota la configuración de sensibilidad e inmunidad a las mascotas desde el Panel de control. La configuración remota sobrescribirá la configuración del puente.

**Página web del panel de control**:

1\)En la página web local del Panel, vaya a la página Editar dispositivo, ingrese la configuración de la cámara PIR en la sección Configuración del sensor. Haga clic en Aceptar para confirmar.

Consulte la siguiente tabla para obtener detalles de configuración. Por ejemplo, si desea habilitar la inmunidad a mascotas y establecer el nivel de sensibilidad en alto, puede ingresar 02.

| **Configuración de infrarrojos** | **Inmunidad a las mascotas** | **Sensibilidad** |
| -------------------------------- | ---------------------------- | ---------------- |
| 00                               | No                           | Alto             |
| 01                               | No                           | Normal           |
| 02                               | Sí                           | Alto             |
| 03                               | Sí                           | Normal           |

2\)Presione el botón de función una vez en la cámara PIR para enviar una señal al panel de control; las nuevas configuraciones se aplicarán inmediatamente. Si no se presiona el botón, se aplicarán nuevas configuraciones en la siguiente transmisión de señal, por ejemplo, la transmisión de la señal de supervisión o la señal de activación de IR.

3

**Servidor del portal de inicio**:

*
  *
    1. En Home Portal Server, vaya a la página de configuración del dispositivo, haga clic en la fila del dispositivo VST-892 y seleccione "Configuración de IR".
    2. Seleccione la función Inmunidad a mascotas (Activar/Desactivar) y Sensibilidad (Alta/Normal) de las listas desplegables, haga clic en "Enviar" para confirmar la configuración.
    3. Presione el botón de función una vez en la cámara PIR para enviar una señal al panel de control; las nuevas configuraciones se aplicarán inmediatamente. Si no se presiona el botón, se aplicarán nuevas configuraciones en la siguiente transmisión de señal, por ejemplo, la transmisión de la señal de supervisión o la señal de activación de IR.
* _**Detección de proximidad**_
  * La cámara PIR tiene un detector de proximidad digital que puede detectar cualquier intento de enmascaramiento (bloqueo) por parte de un intruso.
  * Cuando se detecta un evento de enmascaramiento y la condición de enmascaramiento dura 3 minutos, VST-892 enviará una señal de alarma de enmascaramiento al panel de control para notificar al usuario sobre la condición de enmascaramiento.
  * Después de eliminar el enmascaramiento/bloqueo durante 3 minutos, VST-892 enviará una señal de restauración al Panel de control.

![](<.gitbook/assets/20 (20).png>)

**Instalación**

* _**Guía de instalación**_
  *
    * La cámara PIR está diseñada para montarse en una superficie plana o en una esquina.
    * La base tiene orificios ciegos, donde el plástico es más delgado, para fines de montaje en superficie. Se puede utilizar un soporte de montaje para fijación en esquinas así como para fijación en superficies.
    * El rango de detección es de hasta 12 metros si la cámara PIR se monta a una altura de 2,3 a 2,5 metros sobre el suelo.
    * Cuando la función de inmunidad a mascotas está habilitada, no detectará mascotas de hasta 25 kg cuando se monte a una altura de 2,3 a 2,5 metros sobre el suelo. Si es necesario, puede ajustar la altura de la cámara PIR según el tamaño de su mascota para lograr un rendimiento inmunológico óptimo. Una ubicación de instalación más alta proporcionará un mayor espacio inmune a las mascotas, pero también aumentará el punto ciego debajo de la cámara PIR.
  * Cuando el VST-892 se monta con un soporte giratorio, no tendrá el área de detección normal (como en el diagrama) ni el rango inmune típico a las mascotas.

**Se recomienda instalar la cámara PIR en las siguientes ubicaciones:**

*
  * En una posición donde los animales no puedan llegar a la zona de detección trepando a muebles u otros objetos.
  * No apunte el detector hacia escaleras por las que puedan subir los animales.
  * En una posición tal que un intruso normalmente cruzaría el campo de visión del PIR.
  * A una altura entre 2,3 y 2,5 metros sobre el suelo para un mejor rendimiento.
  * En una esquina para dar la vista más amplia.
  * En una posición donde su campo de visión no quede obstruido, por ejemplo, por cortinas, adornos, etc.
* **Limitaciones**
* No instalar al aire libre.
* Evite grandes obstáculos en el área de detección.

4

* Evite objetos en movimiento, como cortinas, tapices, etc., en el área de detección.
* Evite la luz reflejada por superficies brillantes, p. espejos, ventanas, etc.

5

_\\_

*
  *
    * Los usuarios pueden cambiar fácilmente las baterías quitando la cámara PIR del soporte de montaje cuando la cámara PIR está montada con el soporte de montaje.
* Para montaje en superficie, se proporciona un soporte giratorio opcional para que los usuarios ajusten el rango de detección. Con el soporte giratorio, el VST-892 se puede girar 80 grados horizontalmente y 70 grados verticalmente para brindar una cobertura óptima.
  * **Montaje en superficie sin soporte de montaje:**
    *
      1. Retire la cubierta aflojando el tornillo de fijación inferior con un destornillador Phillips.
      2. Rompe los 2 orificios ciegos de la superficie en el centro de la base.
      3. Utilice los 2 agujeros como plantilla y taladre agujeros en la superficie a montar.
      4. Inserte los tacos de pared si la cámara PIR se va a fijar sobre yeso o ladrillos.
      5. Atornille la base a los tacos.
      6. Vuelva a colocar la cubierta en la base y apriete el tornillo de fijación inferior.
* **Montaje en superficie con el soporte de montaje:**
  1. Utilice los dos orificios centrales para tornillos en el soporte como plantilla y taladre orificios en la superficie a montar.
  2. Inserte los tacos de pared si la cámara PIR se va a fijar sobre yeso o ladrillos.
  3. Atornille el soporte de montaje a los tacos de pared con los dos punteros hacia arriba y hacia usted.
  4. Coloque la cámara PIR en los ganchos del soporte de montaje.

6

1. Inserte los tacos de pared si la cámara PIR se va a fijar sobre yeso o ladrillos.
2. Atornille el soporte de montaje a los tacos de pared con los dos punteros hacia arriba y hacia usted.
   1. Coloque la cámara PIR en los ganchos del soporte de montaje.

* **Montaje en superficie con soporte giratorio (artículo opcional, se vende por separado):**

El soporte giratorio se puede montar en la pared con los tornillos suministrados.

*
  1. Atornille el soporte giratorio a la pared.
  2. Coloque los 3 orificios para ganchos de la base en los ganchos del soporte giratorio en consecuencia.
  3. Gire el soporte para obtener el rango de detección adecuado y apriete el tornillo de fijación.

7
