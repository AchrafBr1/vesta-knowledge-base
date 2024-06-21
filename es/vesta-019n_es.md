# VESTA 019N





## CONFIGURACIÓN DE JUMPERS

<figure><img src=".gitbook/assets/image (47).png" alt=""><figcaption><p>JUMPERS</p></figcaption></figure>

{% hint style="success" %}
**JP6**: Modo contacto de puerta o entrada externa&#x20;

* JP OFF: Modo contacto de puerta&#x20;
* JP ON: Modo de entrada externa&#x20;

**JP5**: Modo NO/NC&#x20;

* JP OFF: NO (Normalmente abierto)&#x20;
* JP ON: NC (Normalmente Cerrado)
{% endhint %}



**Manual del usuario del contacto de puerta (DC-23 / DC-23-R3)**

El contacto de puerta monitorea la apertura/cierre de dispositivos específicos (por ejemplo, puertas o ventanas). El contacto de puerta se fija al marco del dispositivo monitoreado con un imán de accionamiento fijado al dispositivo. Cuando se abre la puerta o ventana, el imán se aleja del contacto de la puerta, activando un interruptor magnético interno que hace que el contacto de la puerta transmita señales de alarma al panel de control. El dispositivo también tiene la capacidad de comunicar problemas de señal junto con situaciones de batería baja.

El diseño del Door Contact consta de una tapa y una base. La cubierta contiene todos los componentes electrónicos y la base proporciona un medio para fijar el contacto de la puerta. Un interruptor antisabotaje de PCB incluido proporciona protección contra manipulación contra la apertura y/o extracción no autorizada del dispositivo.

El contacto de puerta serie DC-23 incluye los siguientes modelos:

DC-23: La cubierta del Door Contact está asegurada mediante un tornillo de fijación inferior.

DC-23-R3: La cubierta de Door Contact está asegurada mediante dos pestillos en la parte superior e inferior.

![](<.gitbook/assets/0 (26).png>)

**Identificación de piezas**

1. **Indicador LED/botón de prueba**

Presione el botón Prueba para transmitir un código de aprendizaje o ingrese al modo de prueba durante 3 minutos.

1. **Orificios de montaje**

Se utiliza para fijar y atornillar el contacto de puerta directamente al marco de la puerta o a la pared.

1. **Manibela de encendido**

Cuando el contacto de puerta esté montado, el interruptor de manipulación se activará cuando se abra la cubierta o cuando se retire el contacto de puerta de la superficie de montaje.

1. **Aislador de batería**
2. **Interruptor de puente de supervisión (JP2) (**_**Sólo modelo 868WF**_**)**

![](<.gitbook/assets/1 (21).jpeg>)

**Puente encendido**

![](<.gitbook/assets/2 (20).jpeg>) ![](<.gitbook/assets/3 (19).jpeg>)

Se inserta el enlace del puente, conectando los dos pines.

**Puente apagado**

El enlace del puente se elimina o "**estacionado**”en un alfiler.

* Jumper ON: Supervisión deshabilitada
* Jumper OFF: Supervisión habilitada\*\*(Predeterminado de fábrica)\*\*.

**6. Interruptor de puente del interruptor de láminas (JP3)**

![](<.gitbook/assets/4 (18).jpeg>)

**Puente encendido**

![](<.gitbook/assets/5 (14).jpeg>) ![](<.gitbook/assets/6 (17).jpeg>)

Se inserta el enlace del puente, conectando los dos pines.

**Puente apagado**

El enlace del puente se elimina o "**estacionado**”en un alfiler.

*
  * Puente ON: Interruptor de láminas deshabilitado. Sólo el dispositivo conectado al terminal de extensión activará el contacto de puerta.
  * Puente APAGADO: Interruptor de láminas habilitado\*\*(Valor predeterminado de fábrica para todos los modelos)\*\*.

1. **Terminal de extensión**

Además del interruptor magnético incorporado, se proporciona un terminal de contacto seco de 2 pines adicional para un interruptor magnético de extensión o cualquier dispositivo con funcionalidad N.C. (normalmente cerrado).

1. **Compartimiento de la batería**
2. **Imán**
3. **Imán Orificio para tornillo**
4. **Espaciador magnético**

![](<.gitbook/assets/7 (16).jpeg>)

1

**Características**

![](<.gitbook/assets/8 (12).jpeg>)

* _**Indicador LED**_
  * En el modo de funcionamiento normal, el LED no se iluminará cuando se active el contacto de la puerta.
  * Cuando el voltaje de la batería del contacto de puerta es bajo, cada vez que se activa el contacto de puerta (dispositivo abierto/cerrado), el LED se iluminará durante 2 segundos.
  * Cuando se abre la cubierta o se activa el interruptor de manipulación, el LED se iluminará durante 2 segundos. Cuando la condición de manipulación continúa, el LED se iluminará durante 2 segundos cada vez que se active el contacto de la puerta.
  * Cuando el contacto de puerta está en modo de prueba, el LED se iluminará cada vez que se active.
  * Cuando la batería se agota, el contacto de puerta detendrá todas las funciones y el LED parpadeará cada 4 segundos.
* _**Terminal de extensión**_

![](<.gitbook/assets/9 (7).jpeg>)

El contacto de puerta tiene un terminal de extensión para proporcionar mayor flexibilidad. El terminal de extensión forma un circuito cerrado con el dispositivo conectado a él. Cuando el dispositivo se activa con el bucle abierto, también se activará el contacto de puerta. El terminal de extensión y el interruptor magnético interno pueden funcionar juntos para activar el contacto de puerta cuando cualquiera de ellos está activado; también puede optar por desactivar el interruptor magnético interno a través de la configuración del puente JP3.

Para conectar el dispositivo al terminal de extensión:

**Para el modelo DC-23:**

![](<.gitbook/assets/10 (8).jpeg>)

1. Abra la cubierta del contacto de puerta con un destornillador para aflojar el tornillo de fijación de la cubierta en la parte inferior de la cubierta del contacto de puerta (consulte la imagen de la vista superior a la derecha).
2. El extremo superior de la caja frontal tiene un orificio de plástico más delgado. Rompe el orificio ciego para crear un orificio para la conexión del cableado al terminal de extensión.
3. Conecte el dispositivo al terminal de extensión.

**Para el modelo DC-23-R3:**

1. Utilice el pulgar para presionar el pestillo y, mientras lo presiona, extraiga la cubierta de la base del contacto de la puerta (consulte la imagen de la vista superior a la derecha).
2. El extremo superior de la caja frontal tiene un orificio de plástico más delgado. Rompe el orificio ciego para crear un orificio para la conexión del cableado al terminal de extensión.
3. Conecte el dispositivo al terminal de extensión.

![](<.gitbook/assets/11 (12).jpeg>)

El terminal de extensión puede resultar útil para la siguiente situación.

* Si el contacto de puerta no se puede montar en el marco de la puerta, puede conectar un

interruptor magnético de extensión adicional al terminal de extensión para montar el contacto de puerta de forma remota.

* Cualquier dispositivo de contacto seco con un bucle N.C. (cierre normal) se puede conectar al terminal de extensión, lo que hace que el contacto de puerta sirva como un transmisor universal.
* Se pueden conectar varios dispositivos de contacto seco junto con Door Contact, como se muestra en la siguiente imagen.

![](<.gitbook/assets/12 (7).jpeg>)

*
  *
    * El terminal de extensión y el interruptor magnético interno pueden funcionar juntos para activar el contacto de puerta cuando cualquiera de ellos está activado; También puede optar por desactivar el interruptor magnético interno a través de la configuración del puente JP3. Si tanto el terminal de extensión como el interruptor magnético interno están en uso y cualquiera de ellos se activa (abre), se enviará una señal de activación al Panel de control. El contacto de puerta solo enviará una señal de cierre (restauración) de contacto de puerta cuando ambos estén cerrados.
* _**Batería**_
  * El contacto de puerta funciona con una batería de litio CR123 de 3 V. Tenga en cuenta:**SIEMPRE**reemplace la batería con una del tamaño y voltaje correctos.
  * El contacto de puerta puede detectar condiciones de batería baja. Cuando el voltaje de la batería es bajo, se enviará una señal de batería baja al panel de control para indicar la condición. El LED se iluminará cuando el contacto de la puerta se active en estado de batería baja. Cuando la batería se agota, el contacto de puerta detendrá todas las funciones y el LED parpadeará cada 4 segundos.

![](<.gitbook/assets/13 (6).jpeg>)

2

*
  * Al cambiar la batería, después de retirar la batería usada, presione el interruptor de manipulación dos veces para descargarla completamente antes de insertar una batería nueva.
* _**Protección contra manipulación**_
  * El contacto de puerta está protegido por un interruptor antisabotaje que se presiona contra la superficie de montaje cuando el contacto de puerta está montado en su lugar. Cada vez que se abre o retira la cubierta del contacto de la puerta de la superficie de montaje, se activará el interruptor de manipulación y el contacto de la puerta enviará una señal de apertura de manipulación para recordarle al usuario la condición.
* _**Señal de supervisión**_
  * La función de supervisión para el modelo 868WF se controla mediante la configuración del puente JP2. Para el modelo que no es 868WF, la función de supervisión siempre está habilitada.
  * Cuando está habilitado, el contacto de puerta transmitirá automáticamente señales de supervisión periódicamente al panel de control en intervalos aleatorios de 30 a 50 minutos.
  * Si el panel de control no ha recibido la señal del contacto de puerta durante un período de tiempo preestablecido, el panel de control indicará que el contacto de puerta en particular está experimentando un problema de falta de señal.
* _**Modo de prueba**_
  * En el modo normal, presione el botón de prueba para transmitir una señal de prueba y un código de aprendizaje al panel de control. El contacto de la puerta también entrará en el modo de prueba durante 3 minutos.
  * En el modo de prueba, el LED se iluminará cada vez que se active el contacto de la puerta.
  * Cada vez que presione el botón de prueba adicional, el período del modo de prueba se restablecerá a 3 minutos.
* _**Empezando**_
  * Abra la tapa del contacto de puerta e inserte la batería.
  * Coloque el panel de control en modo de aprendizaje (consulte el manual del usuario del panel).
  * Presione el botón de prueba del contacto de puerta.
  * Consulte el manual de usuario de su Panel de control para completar el proceso de aprendizaje.
  * Una vez aprendido el contacto de la puerta, coloque el panel de control en (\*\*Prueba de caminata)\*\*modo, mantenga el contacto de la puerta en la ubicación deseada y presione el botón de prueba para transmitir una señal de prueba al panel de control. Si el panel de control está dentro del rango de señal del contacto de la puerta, el panel mostrará la información del contacto de la puerta en consecuencia.
  * Continúe con el montaje y la instalación una vez que esté satisfecho de que el contacto de puerta funciona correctamente en la ubicación deseada.

![](<.gitbook/assets/14 (8).jpeg>) ![](<.gitbook/assets/15 (7).jpeg>) ![](<.gitbook/assets/16 (7).jpeg>) ![](<.gitbook/assets/17 (7).jpeg>)

**Instalación**

![](<.gitbook/assets/18 (7).jpeg>)

* _**Guía de instalación**_
  * El contacto de puerta debe instalarse en el marco de la puerta/ventana y el imán en la puerta/ventana.
  * La distancia entre el contacto de la puerta y el imán no debe ser superior a 15 mm cuando la puerta está cerrada.
  * Evite montar el contacto de puerta sobre superficies metálicas. Si se requiere el montaje en una superficie metálica, asegúrese de probar si el contacto de la puerta se puede activar cuando se abre la puerta.
  * Monte el contacto de la puerta lo más alto posible.
* _**Montaje del contacto de la puerta**_

![](<.gitbook/assets/19 (3).jpeg>)

1. Encuentre una ubicación adecuada cerca de su puerta/ventana para instalar el contacto de puerta.
2. El contacto de puerta tiene 2 marcas de nervaduras en un lado (consulte la imagen a continuación), que marcan la ubicación del interruptor magnético interno. El contacto de la puerta debe instalarse en posición vertical o invertida para garantizar que el lado marcado con nervaduras mire hacia el imán.
3. Para montar el contacto de puerta:
   1. Utilice los orificios de montaje de los contactos de 2 puertas como plantilla para la ubicación adecuada de los orificios.
   2. Utilice los tacos de pared proporcionados para la instalación de yeso/ladrillo.
   3. Atornille el contacto de la puerta en los tacos de pared proporcionados.
4. Para montar el imán:
5. Utilice los 2 orificios para tornillos magnéticos como plantilla para la colocación adecuada de los orificios.

_< NOTA >_

*
  *
    * El imán no debe estar a más de 15 mm del contacto de la puerta cuando la puerta está cerrada.
    * El imán debe alinearse con el lado de la marca de la nervadura del contacto de la puerta. Si es necesario, aplique el espaciador del imán en la parte posterior del imán para alinear mejor el imán con las marcas de las nervaduras.
  * Atornille el imán a la puerta.
  * Inserte las dos tapas blancas en los orificios de los tornillos magnéticos para lograr integridad estética.

![](<.gitbook/assets/20 (11).png>)

3

5.La instalación ya está completa.

Declaración de la FCC

Este dispositivo cumple con la Parte 15 de las normas de la FCC. La operación está sujeta a las dos condiciones siguientes:

1. Es posible que este dispositivo no cause interferencias dañinas y
2. Este dispositivo debe aceptar cualquier interferencia recibida, incluidas las interferencias que puedan provocar un funcionamiento no deseado.

Precaución de la FCC:

Para garantizar el cumplimiento continuo, cualquier cambio o modificación no aprobado expresamente por la parte responsable del cumplimiento puede anular la autoridad del usuario para operar este equipo. (Ejemplo: utilice únicamente cables de interfaz blindados cuando se conecte a una computadora o dispositivos periféricos).

4
