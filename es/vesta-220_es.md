# VESTA 220

**Control de puerta de garaje Z-Wave (GDC-3)**

**Introducción**

GDC-3 es un control de puerta de garaje Z-Wave que se conecta al abridor de puerta de garaje. Después de unirse a una red Z-Wave, el GDC-3 puede recibir comandos a través de la red Z-Wave para activar el abridor de puerta de garaje conectado, proporcionando una operación conveniente para abrir o cerrar la puerta de garaje de forma remota.

GDC-3 también incluye un sensor de inclinación de puerta de garaje (Tilt-GDC3) que se puede instalar en una puerta de garaje abatible o un contacto de puerta de garaje (DC-16SL-GDC3 / DC-32-EX-GDC3) que se puede instalar Se utiliza en una puerta de garaje que se abre horizontalmente para informar el estado de la puerta del garaje cuando está "abierta" o "cerrada".

Antes de que la puerta del garaje activada comience a moverse, los LED de advertencia del GDC-3 parpadearán y la sirena incorporada emitirá pitidos de alarma.

Z-Wave es un protocolo de comunicación inalámbrica que utiliza radio RF de baja potencia. El control de puerta de garaje Z-Wave permite el acceso a la clase "S2 no autenticado" y admite la inclusión Z-Wave SmartStart así como la inclusión clásica.

**Identificación de piezas**

**GDC-3 (Control de puerta de garaje)**

![](<.gitbook/assets/0 (90).jpeg>)

1. **Indicador LED verde**
   * **En**: Conectado a la fuente de alimentación.
   * \*\*Parpadea con LED rojo durante 5 segundos:\*\*Antes de que se mueva la puerta del garaje.
2. **Indicador LED rojo**
   * \*\*Parpadea una vez por segundo:\*\*En modo de aprendizaje para Tilt-GDC3.
   * \*\*Parpadea una vez cada 5 segundos:\*\*Tilt-GDC3 con batería baja
   * \*\*Parpadea con LED verde durante 5 segundos:\*\*Antes de que se mueva la puerta del garaje.
3. **Botón de función**
   * Presione el botón 3 veces en 1 segundo para incluir o excluir el dispositivo en/de la red Z-Wave.
   * Mantenga presionado el botón durante 10 segundos para restablecer los valores de fábrica.
   * Presione el botón una vez para abrir/cerrar la puerta del garaje.
4. **Terminales de conexión**

Conéctelo a los terminales de la consola de pared con botón pulsador en el abridor de puerta de garaje.

1. **Conector CC (con función de bloqueo)**

Conecte un adaptador de corriente DC 9V1A y gírelo 90 grados en el sentido de las agujas del reloj hasta la posición de bloqueo. Para quitar el adaptador, gírelo 90 grados en sentido antihorario hasta la posición abierta original y retírelo.

1. **Botón Aprender**

Utilice una herramienta puntiaguda para presionar el botón de aprendizaje una vez para ingresar al modo de aprendizaje para Tilt-GDC3.

1. **Orificios de montaje**
2. **Soporte de montaje**

1

**Tilt-GDC3 (Sensor de inclinación de puerta de garaje)**

![](<.gitbook/assets/1 (77).jpeg>)

**1. Botón de prueba/indicador LED**

**Botón de prueba:**

* Presione el botón Prueba para transmitir un código de aprendizaje al GDC-3.
* Presione el botón Prueba para informar la posición de la puerta del garaje e ingresar al modo de prueba durante 3 minutos. En el modo de prueba, el LED se iluminará cada vez que se active el sensor de inclinación de la puerta del garaje.

**Indicador LED:**

*
  * El LED parpadeará 3 veces cuando esté transmitiendo un código de aprendizaje.
  * El LED se iluminará cada vez que el dispositivo se active en el modo de prueba.
  * El LED se iluminará cada vez que se active el interruptor de manipulación.
  * (Puerta abierta) Cuando experimente una falla en el dispositivo o esté en modo de prueba, el LED parpadeará 6 veces.
  * (Puerta cerrada) Cuando experimente una falla en el dispositivo o esté en modo de prueba, el LED parpadeará 6 veces. Después de 10 segundos, el LED parpadeará 3 veces.
  * Cuando la batería se agota, el sensor de inclinación de la puerta del garaje detendrá todas sus funciones y el LED parpadeará cada 4 segundos.

1. **Orificios de montaje**

Se utiliza para fijar y atornillar el sensor de inclinación de la puerta del garaje directamente en la parte superior de la puerta del garaje.

**3. Interruptor de manipulación**

Cuando el sensor de inclinación de la puerta del garaje esté montado, el interruptor de manipulación quedará completamente presionado contra la puerta del garaje.

Cuando se abre la cubierta del dispositivo o cuando se retira de la superficie de montaje, se activará el interruptor de manipulación.

El LED parpadeará 6 veces y enviará una señal de apertura por manipulación para notificar a los usuarios de esta condición.

1. **Aislador de batería**
2. **Compartimiento de la batería**

El sensor de inclinación de la puerta del garaje funciona con una batería de litio CR123 de 3 V. Cuando el voltaje de la batería es bajo, se enviará una señal de batería baja al panel de control para notificar a los usuarios de esta condición.

**DC-16SL-GDC3 (Contacto de puerta de garaje)**

![](<.gitbook/assets/2 (71).jpeg>)

**1. Indicador LED**

En el modo de funcionamiento normal, el indicador LED permanece apagado excepto en las siguientes situaciones:

\-Cuando se activa el interruptor de manipulación del contacto de puerta.

2

*
  * Cada vez que se activa el contacto de puerta debido a una activación de manipulación o una condición de batería baja.
  * Cada vez que el contacto de puerta se activa y transmite la señal en el modo de prueba.

1. **Botón de prueba**
   * Presione el botón Prueba para transmitir un código de aprendizaje al GDC-3.
   * Presione el botón Prueba para informar la posición de la puerta del garaje e ingresar al modo de prueba durante 3 minutos. En el modo de prueba, el LED se iluminará cada vez que se active el contacto de la puerta.
2. **Compartimiento de la batería**

El contacto de puerta funciona con uno**Batería de litio CR2 de 3V**. Cuando el voltaje de la batería es bajo, se enviará una señal de batería baja al panel de control para notificar a los usuarios de esta condición.

1. **Orificio para tornillo de seguridad de la cubierta**
2. **nocauts**
3. **Manibela de encendido**

Está diseñado para proteger contra la extracción no autorizada del lugar de montaje, la apertura de la cubierta o la instalación inestable. Cuando se activa la manipulación, se informará una señal de manipulación al panel de control a través del GDC-3 y el LED también se iluminará.

1. **Orificio aislante de batería**
2. **Marcas de costillas**
3. **Imán**

Monte el imán en el costado del contacto de la puerta donde tiene 2 marcas de nervaduras para indicar la posición del interruptor magnético interno. El contacto de la puerta debe instalarse en posición vertical o invertida para garantizar que el lado marcado con nervaduras mire hacia el imán.

1. **Imán Orificio para tornillo**
2. **Espaciador magnético**

**DC-32-EX-GDC3 (Contacto de puerta de garaje exterior)**

![](<.gitbook/assets/3 (66).jpeg>)

1. **Cubierta protectora**
2. **Tapa de la batería**

3

\*\*3.\*\***Interruptor de manipulación frontal**

Cuando se retira la tapa de la batería, se activará el interruptor de manipulación frontal.

1. **Indicador LED**
2. **Botón Aprender/Probar**

Utilice una herramienta puntiaguda para presionar el botón para transmitir el código de aprendizaje o ingrese al modo de prueba durante 3 minutos.

Presione el botón Prueba para informar la posición de la puerta del garaje e ingresar al modo de prueba durante 3 minutos. En el modo de prueba, el LED se iluminará cada vez que se active el contacto de la puerta.

\*\*6.\*\***Compartimiento de la batería**

El contacto de puerta utiliza dos baterías de litio AA L91 como fuente de energía.

\*\*7.\*\***Interruptor de manipulación posterior**

Siempre que se retire el contacto de la puerta de la superficie de montaje, se activará el interruptor de manipulación posterior.

1. **Manos**
2. **Orificios para pestillos**
3. **nocauts**
4. **Área de ruptura**

**Empezando**

![](<.gitbook/assets/4 (75).png>)

* _**Aprenda Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 a GDC-3**_

Encienda el Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 y conecte el GDC-3 a la fuente de alimentación.

* Utilice una herramienta puntiaguda para presionar el botón de aprendizaje del GDC-3 una vez para ingresar al modo de aprendizaje. El GDC-3 emitirá un pitido y el LED rojo comenzará a parpadear.
* Presione el botón de prueba de Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 para enviar un código de aprendizaje a GDC3, el LED parpadeará 3 veces.
* Si el aprendizaje se realiza correctamente, el GDC-3 emitirá 2 pitidos para indicarlo. Si Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 ya se ha agregado al GDC-3, el GDC-3 emitirá un sonido Di-Do para alertar al usuario.
* Utilice una herramienta puntiaguda para presionar el botón de aprendizaje del GDC-3 una vez más para volver al modo normal; el LED rojo se apagará. Alternativamente, el GDC-3 saldrá del modo de aprendizaje automáticamente con 5 pitidos después de 1 minuto de inactividad.

![](<.gitbook/assets/5 (76).png>)

*
  * _NOTA >_
    * El control de puerta de garaje admite solo un sensor. Si se aprende un segundo sensor (ya sea sensor de inclinación o contacto de puerta) en GDC-3, el sensor antiguo será reemplazado por el sensor recién aprendido.
* _**Agregar GDC-3 al sistema (inclusión)**_

![](<.gitbook/assets/6 (55).png>)

El dispositivo admite tanto el proceso de inclusión clásico como el proceso de inclusión SmartStart.

**Inclusión clásica**

* Conecte el GDC-3 a la fuente de alimentación
* Coloque la puerta de enlace Z-wave o el panel de control en**Modo de inclusión**(consulte el manual de usuario de la puerta de enlace o panel de control Z-wave).
* En 1 segundo, presione el botón de función 3 veces.
* Consulte el manual del usuario de la puerta de enlace Z-wave o del panel de control para completar el proceso de adición.
* Si el control de puerta de garaje ya se ha agregado o incluido en otro panel de control/puerta de enlace Z-wave, o si no se puede agregar al panel de control/puerta de enlace Z-wave actual, intente quitarlo primero (consulte\_**Quitar dispositivo**\_).

**Inclusión SmartStart**

Los productos habilitados para SmartStart se pueden agregar a una red Z-Wave escaneando el código QR Z-Wave presente en el producto con un controlador que proporciona la inclusión de SmartStart. No es necesario realizar ninguna otra acción y el producto SmartStart se agregará automáticamente dentro de los 10 minutos posteriores a su encendido en las proximidades de la red. Z-Wave SmartStart utiliza la información DSK del dispositivo para mejorar y simplificar el proceso de inclusión.**DSK**significa Clave específica del dispositivo que se utiliza para autenticación y comunicación cifrada. La información DSK se almacena en formato de código QR que se imprime en una etiqueta y se adhiere a la parte frontal del dispositivo, como se muestra en el ejemplo de la derecha.

![](<.gitbook/assets/7 (45).jpeg>)

* Escanee el código QR en la parte posterior del GDC-3 para obtener el**DSK**información y transferencia a la puerta de enlace Z-Wave.
* Conecte el GDC-3 a la fuente de alimentación; se enviará automáticamente una solicitud de inclusión de SmartStart al portal.
* La puerta de enlace incluirá automáticamente el dispositivo al reconocer el

4

dispositivo haciendo coincidir la solicitud de inclusión con el DSK obtenido.

![](<.gitbook/assets/8 (51).png>)

*
  * _NOTA>_
    * El DSK del dispositivo se utiliza sólo durante la inclusión.
    * El DSK se puede leer sin que el GDC-3 esté encendido, por lo que es posible preparar la puerta de enlace para incluir el dispositivo antes de instalar y encender el control de puerta de garaje.
    * Si GDC-3 ya ha sido**incluido**(aprendido) en otra puerta de enlace/panel de control Z-Wave, exclúyalo primero (consulte\_**Exclusión**\_) antes de intentar**incluir**en el panel de control/puerta de enlace Z-Wave actual. GDC-3 no enviará una solicitud de inclusión de SmartStart si ya está en un panel de control/puerta de enlace Z-Wave.
* _**Eliminación de GDC-3 del sistema (exclusión)**_

![](<.gitbook/assets/9 (46).png>)

El control de puerta de garaje debe retirarse de la red Z-wave existente antes de agregarlo a otra.**Modo de exclusión**

*
  *
    *
      * Coloque la puerta de enlace Z-wave o el panel de control en**Modo de exclusión**(consulte el manual de usuario de la puerta de enlace o panel de control Z-wave).
      * En 1 segundo, presione el botón de función 3 veces y el dispositivo se eliminará de la red Z-wave.

**Restablecimiento de fábrica**

_(Utilice el restablecimiento de fábrica únicamente cuando falte el panel de control/puerta de enlace de la red o no esté operativo)._

El restablecimiento de fábrica del dispositivo lo restaurará a la configuración predeterminada de fábrica (es decir, no incluido en ninguna red Z-wave).

*
  *
    *
      * Mantenga presionado el botón de función del dispositivo durante 10 segundos para realizar el restablecimiento de fábrica.
  * _NOTA>_
    * Antes de eliminar o restablecer el GDC-3 de fábrica, asegúrese de que la información DSK del dispositivo se haya eliminado o no exista en la puerta de enlace. Si elimina o restablece el dispositivo a los valores de fábrica, pero su información DSK aún existe en la puerta de enlace, la puerta de enlace incluirá automáticamente el dispositivo nuevamente.
* _**Prueba de rango**_

![](<.gitbook/assets/10 (48).png>) ![](<.gitbook/assets/11 (40).png>)

Para probar si el control de la puerta del garaje puede comunicarse con la puerta de enlace Z-Wave o el panel de control:

* Coloque la puerta de enlace/panel en modo de prueba de alcance (Walk Test).
* Presione el botón de función en el dispositivo.
* La puerta de enlace/panel de control debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual del usuario de la puerta de enlace/panel de control).

**Instalación**

![](<.gitbook/assets/12 (25).jpeg>)

**Montaje del sensor de inclinación de la puerta del garaje (Tilt-GDC3)**

* El sensor de inclinación de puerta de garaje está diseñado para montarse en puertas de garaje basculantes o basculantes, no para usarse en puertas de garaje enrollables. Se utiliza para informar el estado de cuando la puerta del garaje está "abierta", "cerrada" o en movimiento.
* El dispositivo se montará verticalmente al suelo (no debe inclinarse más de +-5 grados cuando esté montado).
* Monte el dispositivo sobre una superficie seca y limpia. Asegúrese de que el dispositivo esté montado con el indicador LED en la parte superior.
* El sensor de inclinación de la puerta del garaje debe montarse en el panel superior de la puerta del garaje, como se muestra a continuación.

![](<.gitbook/assets/13 (31).jpeg>)

* Hay dos formas de montar el sensor de inclinación de la puerta del garaje. Montaje con tornillos:
  1. Encuentre una ubicación adecuada para instalar el sensor de inclinación de la puerta del garaje. La superficie de montaje debe estar limpia y seca. Limpie a fondo la superficie de montaje si es necesario.
  2. Utilice los dos orificios de montaje como plantilla para marcar y perforar los orificios de montaje.
  3. Utilice los tacos de pared proporcionados para la instalación de yeso/ladrillo. Atornille el sensor de inclinación de la puerta del garaje en los tacos de pared proporcionados. Asegúrese de que los tacos de pared estén al ras con la superficie de montaje.

![](<.gitbook/assets/14 (29).png>)

5

* ![](<.gitbook/assets/15 (29).png>)_NOTA>_
  * Utilice este tipo de método de montaje únicamente cuando las puertas del garaje sean más gruesas que la longitud de los tornillos.

![](<.gitbook/assets/16 (31).png>)

Montaje adhesivo:

1. Encuentre una ubicación adecuada para instalar el sensor de inclinación de la puerta del garaje. La superficie de montaje debe estar limpia y seca. Limpie a fondo la superficie de montaje si es necesario.
2. Retire un lado de los revestimientos de la almohadilla adhesiva de doble cara. Aplíquelo en la parte posterior del sensor de inclinación de la puerta del garaje y presione firmemente durante 30 segundos para garantizar un buen contacto.
3. Retire el revestimiento restante de la almohadilla adhesiva y presione firmemente el sensor de inclinación de la puerta del garaje en la ubicación deseada durante otros 30 segundos. Evite aplicar la almohadilla adhesiva sobre superficies irregulares o volver a aplicarla.

**Montaje del contacto de la puerta del garaje (DC-16SL-GDC3)**

* El contacto de puerta está diseñado para usarse en puertas de garaje que se abren horizontalmente para informar el estado de la puerta del garaje cuando está "abierta" o "cerrada".
* Instale el contacto de puerta en el objeto más estacionario (como el marco de la puerta) y monte el imán en el objeto más móvil (como la puerta del garaje).

![](<.gitbook/assets/17 (20).jpeg>)

* Monte el imán utilizando los tornillos proporcionados. Alinee el imán según la marca de la nervadura en el contacto de la puerta.
* Cuando sea necesario, utilice el espaciador magnético para alinear mejor el imán con las marcas de las nervaduras.
  *
    * _NOTA >_
      * El imán no debe estar a más de 15 mm del contacto de la puerta cuando la puerta está cerrada.
      * Las dos tapas blancas proporcionadas se pueden insertar en los orificios de los tornillos magnéticos para lograr una integridad estética.
* Hay dos formas de montar el contacto de puerta: montaje autoadhesivo o montaje con tornillos. Montaje autoadhesivo:
  1. La superficie de montaje debe estar limpia, seca y lisa. Limpie la superficie de montaje con un desengrasante adecuado si es necesario.
  2. Retire un lado de los revestimientos de la almohadilla adhesiva de doble cara. Aplique la almohadilla adhesiva en la parte posterior del dispositivo y presione firmemente durante 30 segundos para asegurar un buen contacto.
  3. Retire el revestimiento restante de la almohadilla adhesiva y presione firmemente el contacto de la puerta en la ubicación deseada durante 30 segundos.

_\\_

*
  *
    *
      * No utilice el método de instalación con almohadilla adhesiva sobre una superficie con pintura descascarada o agrietada, o sobre una superficie rugosa.
      * No vuelva a aplicar la almohadilla adhesiva 3M. No se puede reutilizar

![](<.gitbook/assets/18 (30).png>) ![](<.gitbook/assets/19 (31).png>) ![](<.gitbook/assets/20 (22).png>)

Montaje con tornillos:

La base tiene dos orificios ciegos, donde el plástico es más delgado, para fines de montaje.

Para montar el contacto de puerta:

1. Retire la cubierta desatornillando el tornillo de seguridad de la cubierta con un destornillador Phillips.
2. Rompe los nocauts en la base.
3. Utilice los agujeros como plantilla y taladre dos agujeros.
4. Inserte tacos de pared si lo fija en yeso o ladrillo.
5. Atornille la base al taco de pared con un destornillador Phillips.
6. Fije la cubierta a la base y apriete el tornillo de seguridad de la cubierta.

**Montaje del contacto de puerta de garaje exterior (DC-32-EX-GDC3)**

* El contacto de puerta a prueba de agua está diseñado para usarse en puertas de garaje que se abren horizontalmente para informar el estado de los 6

puerta del garaje cuando la puerta del garaje está “abierta” o “cerrada”.

* Se recomienda colocar el contacto de puerta en el marco fijo de la puerta del garaje y el imán en la puerta del garaje.
* Las marcas de las nervaduras en el imán y el contacto de la puerta deben alinearse (**HIGO. 1**).
* El imán no debe estar a más de 3 cm del lado marcado del contacto de la puerta cuando la puerta está cerrada.
* El contacto de la puerta tiene un interruptor de manipulación trasero en su cubierta trasera. Asegúrese de que el dispositivo esté colocado dentro del soporte de modo que el resorte del interruptor de manipulación quede presionado contra el área de separación que está conectada sin apretar al soporte.

Si el contacto de la puerta se retira a la fuerza de la pared, el área de separación se desprenderá del soporte y permanecerá unida a la superficie de montaje, activando el interruptor de manipulación.

**HIGO. 1**

* Para montar el contacto de puerta:
  *
    1. El soporte de montaje provisto tiene 3 orificios ciegos donde el plástico es más delgado y se puede romper para realizar el montaje. (**HIGO. 2**)
    2. Utilice el soporte de montaje como plantilla para perforar agujeros en la pared para los enchufes. (**HIGO. 3**)
    3. Introduzca los tacos y fije el soporte de montaje en la pared con los tornillos.
    4. Monte el contacto de puerta con los ganchos de la cubierta posterior del contacto de puerta asegurados en los orificios del pestillo del soporte de montaje y luego empuje hacia abajo para bloquear el gancho. (**HIGO. 4**)
  * _NOTA >_
    *
      * Asegúrese de que el interruptor de manipulación posterior del contacto de puerta esté presionado contra el área de separación en el soporte de montaje.

**HIGO. 2**

 Asegure los tornillos de fijación inferiores.

5\)Vuelva a colocar la cubierta protectora.

 Hay dos formas de montar el imán: montaje adhesivo y montaje con tornillos.

 Montaje con tornillos:

1. Atornille el soporte de montaje a la puerta con los dos tornillos suministrados.
2. Conecte el imán al soporte de montaje.

_\\_

* Se puede utilizar el espaciador magnético proporcionado haciendo que el lado con palabras negras toque el soporte de montaje.

entre el imán y la puerta para facilitar la alineación y la instalación.

7

* Montaje adhesivo:
  1. Como alternativa, utilice la cinta de doble cara proporcionada para fijar directamente el imán a la puerta.

_\\_

*
  *
    * Asegúrese de que la superficie de montaje esté limpia, seca y lisa antes de colocar el imán pegado con cinta de doble cara a la puerta y que el imán debe presionarse firmemente contra la puerta durante 30 segundos.
  * La instalación está completa.

**HIGO. 3**

**HIGO. 4**

**Montaje del control de puerta de garaje (GDC-3)**

* El control de la puerta del garaje generalmente se monta en el techo cerca del abridor de la puerta del garaje y del tomacorriente.

8

_**ADVERTENCIA :**_

*
  1. Antes de la instalación, asegúrese de desconectar la fuente de alimentación del abridor de puerta de garaje.
     1. El control de puerta de garaje GDC-3 debe instalarse a la vista de la puerta del garaje, donde las alarmas visuales y audibles puedan verse y oírse claramente.

1. Utilice el soporte de montaje como plantilla, marque los dos orificios de montaje, taladre orificios en la ubicación de montaje e inserte tacos de pared si es necesario.
2. Atornille el soporte de montaje en la ubicación marcada con los dos ganchos hacia afuera.
3. Enganche el control de la puerta del garaje en el soporte de montaje en pared (con los orificios de montaje del control de la puerta del garaje).
4. Empuje el control de la puerta del garaje (en la dirección que se indica en la imagen a continuación) para bloquearlo en el soporte de montaje.
5. Conecte los terminales GDC-3 a los terminales de la consola de pared con botón pulsador en el abridor de puerta de garaje. Cualquier cable se puede conectar a cualquiera de los terminales. (Los terminales de la consola de pared pueden denominarse “PWC”, “WC”, “PB”, “PUSHBUTTON” o “RED” y “WHITE”. Los nombres y ubicaciones de los terminales varían según el modelo).
6. Enchufe el adaptador de corriente de salida DC 9V 1A y conéctelo a la fuente de alimentación.
7. Restaure la energía al abridor de puerta de garaje.

9

**Operación**

* _**Funcionamiento de la puerta del garaje**_
  * Después de que GDC-3 se haya incluido en la red Z-Wave, la puerta de enlace Z-Wave puede abrir o cerrar la puerta del garaje de forma remota con Z-Wave

dominio\[DOMINIO\_CLASE\_BARRERA\_OPERADOR] y\[BARRERA\_OPERADOR\_SET], usando los siguientes parámetros:

*
  *
    * Abierto: Valor objetivo = 0xFF
    * Cerrar: Valor objetivo = 0x00
  * Los usuarios también pueden presionar el botón de función una vez para abrir/cerrar la puerta del garaje.
  * Antes de que la puerta del garaje activada comience a moverse, los indicadores LED de advertencia (verde y rojo) parpadearán y sonarán pitidos de alarma durante 5 segundos. Cuando la puerta del garaje comience a moverse, se informará su posición al portal Z-Wave.

\[DOMINIO\_CLASE\_BARRERA\_OPERADOR]\[BARRERA\_OPERADOR\_INFORME] estado:

|  | BARRERA\_OPERADOR\_CERRADO      | 0x00 |
| - | ------------------------------- | ---- |
|  | BARRERA\_OPERADOR\_CLAUSURA     | 0xFC |
|  | BARRERA\_OPERADOR\_INTERRUMPIDO | 0xFD |
|  | BARRERA\_OPERADOR\_APERTURA     | 0xFE |
|  | BARRERA\_OPERADOR\_ABIERTO      | 0xFF |

*
  * Una vez que GDC-3 inicia el movimiento de la puerta del garaje, deberá esperar 35 segundos para que la puerta del garaje se abra o cierre completamente antes de poder enviar un segundo comando de apertura/cierre o presionar el botón de función para abrir/cerrar. Si se envía un segundo comando o se presiona el botón de función dentro de los 35 segundos, GDC-3 enviará una señal de ocupado a la puerta de enlace Z-Wave.

\[DOMINIO\_CLASE\_SOLICITUD\_ESTADO]\[SOLICITUD\_OCUPADO]

*
  *
    *
      * Estado: 0x00
      * Tiempo de espera: 0x00
    * Cuando la puerta del garaje está abierta, el GDC-3 omitirá cualquier comando de apertura del portal Z-Wave. Cuando la puerta del garaje está cerrada, el GDC-3 omitirá cualquier comando de cierre de la puerta de enlace Z-Wave.
* _**Volumen del sonido de la alarma**_
  *
    * Antes de que la puerta del garaje activada comience a moverse, los indicadores LED de advertencia parpadearán y sonarán pitidos de alarma durante 5 segundos. Los usuarios pueden ajustar el volumen del sonido de la alarma enviando un comando desde la puerta de enlace Z-Wave con el comando Configuración CC, utilizando los siguientes parámetros:

10

* S: Talla
* D: Predeterminado

| No. | Nombre                    | S | mín. | máx. | D | Descripción   |
| --- | ------------------------- | - | ---- | ---- | - | ------------- |
|     |                           |   |      |      |   |               |
| 1   | Nivel de sonido de alarma | 1 | 0    | 2    | 2 | 0: silencioso |
|     |                           |   |      |      |   | 1: pequeño    |
|     |                           |   |      |      |   | 2: fuerte     |
|     |                           |   |      |      |   |               |

* _**Características del sensor de inclinación de puerta de garaje (Tilt-GDC3)/contacto de puerta (DC-16SL-GDC3)/contacto de puerta exterior (DC-32-EX-GDC3)**_
  * Detección de posición de puerta de garaje

Siempre que cambie la posición de la puerta del garaje, Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 informará la posición de la puerta a GDC-3, y GDC-3 informará a la puerta de enlace Z-Wave con Z -Comando de onda

\[DOMINIO\_CLASE\_BARRERA\_OPERADOR]\[BARRERA\_OPERADOR\_INFORME].

|  | BARRERA\_OPERADOR\_CERRADO      | 0x00                       |
| - | ------------------------------- | -------------------------- |
|  | BARRERA\_OPERADOR\_CLAUSURA     | 0xFC (solo para Tilt-GDC3) |
|  | BARRERA\_OPERADOR\_INTERRUMPIDO | 0xFD (solo para Tilt-GDC3) |
|  | BARRERA\_OPERADOR\_APERTURA     | 0xFE (solo para Tilt-GDC3) |
|  | BARRERA\_OPERADOR\_ABIERTO      | 0xFF                       |

* Protección contra manipulación

Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 está protegido por un interruptor de manipulación. Cuando se retira el dispositivo de la superficie de montaje o cuando se abre la cubierta del dispositivo, se activará su interruptor de manipulación. Luego, el dispositivo enviará una señal de apertura por manipulación al GDC-3, y el GDC-3 informará a la puerta de enlace Z-Wave con el comando Z-Wave.\[DOMINIO\_CLASE\_NOTIFICACIÓN]\[NOTIFICACIÓN\_INFORME].

*
  * Abierto: 00 00 00 FF 07 03 00 00
  * Cerrar: 00 00 00 FF 07 00 01 03
* Señal de supervisión

El Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 transmitirá una señal de supervisión junto con la posición de la puerta del garaje al GDC-3 cada 15 a 20 minutos. GDC-3 informará a la puerta de enlace Z-Wave utilizando\[BARRERA\_OPERADOR\_INFORME].

Si la puerta de enlace Z-Wave no recibe ninguna señal de supervisión del Tilt-GDC3 / DC-16SL-GDC / DC-32-EX-GDC durante un período de tiempo preestablecido, se mostrará un mensaje de error "Fuera de servicio". generado.

*
  * Error de supervisión: 00 00 00 FF 06 49 00
  * Restaurar: 00 00 00 FF 06 00 00 (Tanto el estado de la batería como la señal de supervisión deben volver a la normalidad)
* Batería baja

El Tilt-GDC3 / DC-16SL-GDC3 / DC-32-EX-GDC3 presenta la función de detección de batería baja. Cuando el voltaje de la batería es bajo, el sensor de inclinación/contacto de puerta transmitirá una señal de batería baja al GDC-3, y el GDC-3 informará a la puerta de enlace Z-Wave con el comando Z-Wave.\[DOMINIO\_CLASE\_NOTIFICACIÓN]\[NOTIFICACIÓN\_INFORME].

*
  * Batería baja: 00 00 00 FF 06 4A 00
  * Restaurar: 00 00 00 FF 06 00 00 (Tanto el estado de la batería como la señal de supervisión deben volver a la normalidad)

**Información de onda Z**

\*\*Tipo de dispositivo:\*\*GENÉRICO\_TIPO\_ENTRADA\_CONTROL

\*\*Tipo específico:\*\*ESPECÍFICO\_TIPO\_SEGURO\_BARRERA\_AÑADIR

\*\*Tipo de icono:\*\*ICONO\_TIPO\_GENÉRICO\_BARRERA

\*\*Tipo de rol:\*\*Siempre en esclavo (AOS)

\*\*Seguridad:\*\*Malo\_NO AUTENTICADO

\*\*Identificación del fabricante:\*\*0x018E

\*\*Identificación del tipo de producto:\*\*0x0004

\*\*ID del Producto:\*\*0x0127

* _**Clase de comando admitida**_

11

| **Clase de comando**                        | **Versión** | **Clase de seguridad requerida**     |
| ------------------------------------------- | ----------- | ------------------------------------ |
|                                             |             |                                      |
| Asociación                                  | 2           | Clase de seguridad más alta otorgada |
|                                             |             |                                      |
| Información del grupo de asociación         | 3           | Clase de seguridad más alta otorgada |
|                                             |             |                                      |
| Básico                                      | 2           | Clase de seguridad más alta otorgada |
|                                             |             |                                      |
| Restablecimiento del dispositivo localmente | 1           | Clase de seguridad más alta otorgada |
|                                             |             |                                      |
| Metadatos de actualización de firmware      | 5           | Clase de seguridad más alta otorgada |
|                                             |             |                                      |
| Específico de fabricación                   | 2           | Clase de seguridad más alta otorgada |
|                                             |             |                                      |
| Multicanal                                  | 4           | Clase de seguridad más alta otorgada |
|                                             |             |                                      |
| Asociación multicanal                       | 3           | Clase de seguridad más alta otorgada |
|                                             |             |                                      |
| Nivel de potencia                           | 1           | Clase de seguridad más alta otorgada |
|                                             |             |                                      |
| Configuración                               | 1           | Clase de seguridad más alta otorgada |
|                                             |             |                                      |
| Notificación                                | 8           | Clase de seguridad más alta otorgada |
|                                             |             |                                      |
| Operador de barrera                         | 1           | Clase de seguridad más alta otorgada |
|                                             |             |                                      |
| Estado de la aplicación                     | 1           | Clase de seguridad más alta otorgada |
|                                             |             |                                      |
| Versión                                     | 3           | Clase de seguridad más alta otorgada |
|                                             |             |                                      |
| Servicio de transporte                      | 2           | Ninguno                              |
|                                             |             |                                      |
| Información sobre Z-Wave Plus               | 2           | Ninguno                              |
|                                             |             |                                      |
| Seguridad 2                                 | 1           | Ninguno                              |
|                                             |             |                                      |
| Supervisión                                 | 1           | Ninguno                              |
|                                             |             |                                      |

* _**Grupos de asociación**_

| **IDENTIFICACIÓN** | **Nombre**    | **máx.** | **Descripción**                                                                                      |
| ------------------ | ------------- | -------- | ---------------------------------------------------------------------------------------------------- |
|                    |               | **Nodo** |                                                                                                      |
|                    |               |          |                                                                                                      |
| 1                  | Línea de vida | 5        | Admite las siguientes clases de comando:                                                             |
|                    |               |          |  Informe de notificación: activado por manipulación, batería baja, error de supervisión.            |
|                    |               |          |  Informe del Operador de Barrera: GDC abierto/cerrado.                                              |
|                    |               |          |  Informe de aplicación ocupada: activado desde el conjunto de operadores de barrera en 35 segundos. |
|                    |               |          |  Restablecimiento del dispositivo localmente: se activa al restablecer                              |
|                    |               |          |                                                                                                      |

12
