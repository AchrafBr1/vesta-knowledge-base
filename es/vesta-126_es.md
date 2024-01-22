# VESTA 126

Manual del usuario del contacto de puerta (DC-23 / DC-23-R3)

El contacto de puerta monitorea la apertura/cierre de dispositivos específicos (por ejemplo, puerta o ventana). El contacto de puerta se fija al marco del dispositivo monitoreado con un imán de accionamiento fijado al dispositivo. Cuando se abre la puerta o ventana, el imán se aleja del contacto de la puerta, activando un interruptor magnético interno que hace que el contacto de la puerta transmita una señal de alarma al panel central. El dispositivo también tiene la capacidad de comunicar problemas de señal junto con situaciones de batería baja.

El diseño Door Contact consta de una cubierta y una base. La cubierta contiene todos los componentes electrónicos y la base proporciona un medio para fijar el dispositivo. Un interruptor antisabotaje de PCB incluido proporciona protección contra manipulación contra la apertura y/o extracción no autorizada del dispositivo.

El contacto de puerta de la serie DC-23 incluye los siguientes modelos:

DC-23: La cubierta del contacto de la puerta está asegurada mediante un tornillo de fijación inferior.

DC-23-R3: La cubierta del contacto de la puerta está asegurada mediante dos pestillos en la parte superior e inferior

![](<.gitbook/assets/0 (15).jpeg>)

Identificación de piezas

1.  **Indicador LED/botón de prueba**

Presione el botón Prueba para transmitir el código de aprendizaje o ingrese al modo de prueba durante 3 minutos.

1.  **Orificios de montaje**

Se utiliza para fijar y atornillar el contacto de la puerta directamente al marco de la puerta o a la pared.

1.  **Manibela de encendido**

Cuando se monta el contacto de puerta, el interruptor de manipulación se activará cuando se abra la cubierta o cuando se retire el contacto de puerta de la superficie montada.

1.  **Aislador de batería**
2.  **Interruptor de puente de supervisión (JP2)**

**(**_**Sólo modelo 868WF**_**)**

**Puente apagado**

si se elimina el enlace del puente o "**estacionado**”en un alfiler.

**Puente encendido**

Se inserta el enlace del puente, conectando los dos pines.

![jumper close](<.gitbook/assets/1 (26).png>)![jumper open](<.gitbook/assets/2 (31).png>)

-   Jumper ON: Supervisión deshabilitada
-   Jumper OFF: Supervisión habilitada.**(Predeterminado de fábrica)**

1.  **Interruptor de puente de interruptor de láminas (JP3)**

![jumper close](<.gitbook/assets/3 (27).png>)![jumper open](<.gitbook/assets/4 (26).png>)

**Puente encendido**

Se inserta el enlace del puente, conectando los dos pines.

**Puente apagado**

si se elimina el enlace del puente o "**estacionado**”en un alfiler.

-   Puente ON: Interruptor de láminas deshabilitado. Sólo el dispositivo conectado al terminal de extensión activará el contacto de puerta.
-   Puente APAGADO: Interruptor de láminas habilitado.**(Valor predeterminado de fábrica para todos los modelos)**

1.  **Terminal de extensión**

Además del interruptor magnético incorporado, se proporciona un terminal de contacto seco de 2 pines adicional para un interruptor magnético de extensión o cualquier dispositivo con funcionalidad N.C. (normalmente cerrado).

1.  ![](<.gitbook/assets/5 (18).png>)**Compartimiento de la batería**
2.  **Imán**
3.  **Imán Orificio para tornillo**
4.  **Espaciador magnético**

Características

-   _**Indicador LED**_
-   En el modo de funcionamiento normal, el LED no se encenderá cuando se active el contacto de la puerta.
-   Cuando el voltaje de la batería del contacto de puerta es bajo, cada vez que se activa el contacto de puerta (dispositivo abierto/cerrado), el LED se encenderá durante 2 segundos.
-   Cuando se abre la cubierta o se activa el interruptor de manipulación, el LED se iluminará durante 2 segundos. Cuando persiste una condición de manipulación, el LED se encenderá durante 2 segundos cada vez que se active el contacto de la puerta.
-   Cuando el contacto de puerta está en modo de prueba, el LED se iluminará cada vez que se active.
-   Cuando la batería se agota, el contacto de la puerta detendrá todas sus funciones y el LED parpadeará cada 4 segundos.
-   _**Terminal de extensión**_

El contacto de puerta tiene un terminal de extensión para proporcionar mayor flexibilidad. El terminal de extensión forma un circuito cerrado con el dispositivo conectado a él. Cuando se activa el dispositivo, se abre el bucle y también se activará el contacto de puerta.

El terminal de extensión y el interruptor magnético interno pueden funcionar juntos para activar el contacto de puerta cuando cualquiera de ellos está activado; también puede optar por desactivar el interruptor magnético interno a través de la configuración del puente JP3.

Para conectar el dispositivo al terminal de extensión:

![](<.gitbook/assets/6 (10).jpeg>)**Para el modelo DC-23:**

1.  Abra la cubierta del contacto de puerta usando un destornillador para aflojar el tornillo de fijación de la cubierta en la parte inferior de la cubierta del contacto de puerta. (Vea la imagen debajo de la imagen desde el ángulo de visión superior).
2.  El extremo superior de la caja frontal tiene un orificio de plástico más delgado. Rompe el orificio ciego para crear un orificio para la conexión del cableado al terminal de extensión.
3.  Conecte el dispositivo al terminal de extensión.

**Para el modelo DC-23-R3:**

1.  ![](<.gitbook/assets/7 (9).jpeg>)Use su pulgar para presionar el pestillo, mientras lo presiona, extraiga la cubierta de la base del contacto de la puerta (vea la imagen a continuación desde el ángulo de vista superior).
2.  El extremo superior de la caja frontal tiene un orificio de plástico más delgado. Rompe el orificio ciego para crear un orificio para la conexión del cableado al terminal de extensión.
3.  Conecte el dispositivo al terminal de extensión.

El terminal de extensión puede resultar útil para la siguiente situación.

-   Si el contacto de puerta no se puede montar en el marco de la puerta, puede conectar un interruptor magnético de extensión adicional al terminal de extensión para montar el contacto de puerta de forma remota.
-   Cualquier dispositivo de contacto seco con bucle N.C. (cierre normal) se puede conectar al terminal de extensión, lo que hace que el contacto de puerta sirva como un transmisor universal.
-   Se pueden conectar varios dispositivos de contacto seco junto con el contacto de puerta, como se muestra en el diagrama a continuación.

![](<.gitbook/assets/8 (9).png>)

-   El terminal de extensión y el interruptor magnético interno pueden funcionar juntos para activar el contacto de puerta cuando cualquiera de ellos está activado; también puede optar por desactivar el interruptor magnético interno a través de la configuración del puente JP3. Si tanto el terminal de extensión como el interruptor magnético interno están en uso y cualquiera de ellos está activado (abierto). El contacto de puerta solo enviará una señal de cierre (restauración) del contacto de puerta cuando ambos estén cerrados.
-   _**Batería**_
-   El contacto de puerta funciona con una batería de litio CR123 de 3 V. Tenga en cuenta:**SIEMPRE**reemplace la batería con una del tamaño y voltaje correctos.
-   El contacto de puerta puede detectar una condición de batería baja. Cuando el voltaje de la batería es bajo, se enviará una señal de batería baja al panel de control para notificar la condición. El LED se iluminará cuando el contacto de puerta se active en estado de batería baja. Cuando la batería se agota, el contacto de la puerta detendrá todas sus funciones y el LED parpadeará cada 4 segundos.
-   Al cambiar la batería, después de retirar las baterías viejas, presione el interruptor de manipulación dos veces para descargarla completamente antes de insertar una batería nueva.
-   _**Protección contra manipulación**_
-   El contacto de puerta está protegido por un interruptor antisabotaje que se comprime contra la superficie de montaje cuando se monta el contacto de puerta. Siempre que se abre la cubierta del contacto de la puerta o se retira de la superficie montada, se activará el interruptor de manipulación y el contacto de la puerta enviará una señal de apertura de manipulación para recordarle al usuario la condición.
-   _**Señal de supervisión**_
-   La función de supervisión para el modelo 868WF se controla mediante la configuración del puente JP2. Para el modelo que no es 868WF, la función de supervisión siempre está habilitada.
-   Cuando está habilitado, el contacto de puerta transmitirá automáticamente señales de supervisión periódicamente al panel de control en intervalos aleatorios de 30 a 50 minutos.
-   Si el panel de control no ha recibido la señal del contacto de puerta durante un período de tiempo preestablecido, el panel de control indicará que el contacto de puerta en particular está experimentando un problema de falta de señal.
-   _**Modo de prueba**_
-   En el modo normal, presione el botón de prueba para transmitir una señal de prueba y un código de aprendizaje al panel de control. El contacto de la puerta también entrará en el modo de prueba durante 3 minutos.
-   En el modo de prueba, el LED se iluminará cada vez que se active el contacto de la puerta.
-   Cada pulsación adicional del botón de prueba restablecerá el tiempo del modo de prueba a 3 minutos.
-   _**Empezando**_
-   Abra la tapa del contacto de puerta e inserte la batería.
-   Coloque el panel de control en modo de aprendizaje (consulte el manual de operación del panel).
-   Presione el botón de prueba de contacto de puerta.
-   Consulte el manual de funcionamiento de su panel de control para completar el proceso de aprendizaje.
-   Una vez aprendido el contacto de la puerta, coloque el panel de control en (**Prueba de caminata)**modo, mantenga el contacto de la puerta en la ubicación deseada y presione el botón de prueba para transmitir la señal de prueba al panel de control. Si el panel de control está dentro del rango de señal de contacto de puerta, el panel mostrará la información de contacto de puerta en consecuencia.
-   Continúe con el montaje y la instalación una vez que esté satisfecho de que la ubicación del contacto de la puerta funciona correctamente.

Instalación

-   _Guía de instalación_
-   El contacto de puerta debe instalarse en el marco de la puerta/ventana y el imán en la puerta/ventana.
-   La distancia entre el contacto de la puerta y el imán no debe ser superior a 15 mm cuando la puerta está cerrada.
-   Evite montar el contacto de puerta sobre una superficie metálica. Si lo monta sobre una superficie metálica, asegúrese de probar si el contacto de la puerta se puede activar cuando se abre la puerta.
-   Monte el contacto de la puerta lo más alto posible.
-   _**Montaje del contacto de la puerta**_

1.  Encuentre una ubicación adecuada cerca de su puerta/ventana para instalar el contacto de puerta.
2.  El contacto de puerta tiene 2 marcas de nervaduras en un lado (consulte la figura), que marcan la ubicación del interruptor magnético interno. El contacto de la puerta debe instalarse en posición vertical o invertida para garantizar que el lado marcado con nervaduras mire hacia el imán.
3.  Para montar el contacto de puerta:
4.  Utilice los orificios de montaje de los contactos de 2 puertas como plantilla para la ubicación adecuada de los orificios.
5.  Utilice los tacos de pared proporcionados para la instalación de yeso/ladrillo.
6.  Atornille el contacto de la puerta en los tacos de pared proporcionados.
7.  Para montar el imán:
8.  Utilice los 2 orificios para tornillos magnéticos como plantilla para la colocación adecuada de los orificios.

&lt;Nota>

-   El imán no debe estar a más de 15 mm del contacto de la puerta cuando la puerta está cerrada.
-   El imán debe alinearse con el lado de la marca de la nervadura del contacto de la puerta. Si es necesario, aplique el espaciador del imán en la parte posterior del imán para alinear mejor el imán con las marcas de las nervaduras.

1.  Atornille el imán a la puerta.
2.  Inserte las dos tapas blancas en los orificios de los tornillos magnéticos para lograr integridad estética.
3.  La instalación ya está completa.

![](<.gitbook/assets/9 (9) (1).png>)

Declaración de la FCC

Este dispositivo cumple con la Parte 15 de las normas de la FCC. La operación está sujeta a las dos condiciones siguientes:

(1) Es posible que este dispositivo no cause interferencias dañinas y

(2) Este dispositivo debe aceptar cualquier interferencia recibida, incluidas las interferencias que puedan causar un funcionamiento no deseado.

Precaución de la FCC:

Para garantizar el cumplimiento continuo, cualquier cambio o modificación no aprobado expresamente por la parte responsable del cumplimiento puede anular la autoridad del usuario para operar este equipo. (Ejemplo: utilice únicamente cables de interfaz blindados cuando se conecte a una computadora o dispositivos periféricos).
