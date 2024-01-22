# VESTA 199

**Manual del usuario del contacto de puerta (DC-16SL)**

El contacto de puerta monitorea la apertura/cierre de dispositivos específicos (por ejemplo, puerta o ventana). El contacto de puerta se fija al marco del dispositivo monitoreado con un imán de accionamiento fijado al dispositivo. Cuando se abre la puerta o ventana, el imán se aleja del contacto de la puerta, activando un interruptor magnético interno que hace que el contacto de la puerta transmita una señal de alarma al panel de control. El dispositivo también tiene la capacidad de comunicar problemas de señal junto con situaciones de batería baja.

El diseño de Door Contact consta de una cubierta y una base. La cubierta contiene todos los componentes electrónicos y la base proporciona un medio para fijar el dispositivo. Un interruptor antisabotaje de PCB incluido proporciona protección contra manipulación contra la apertura y/o extracción no autorizada del dispositivo.

**El Contacto de Puerta incluye los siguientes modelos de frecuencia:**

**433 metros**

**433FM F1**

**868WF**

**868FM**

**868FM F1**

**869FM**

**869 F1**

![](<.gitbook/assets/0 (80).jpeg>)

* _**Identificando las partes**_

![](<.gitbook/assets/1 (60).png>)

1. **Indicador LED**
2. **Botón Aprender/Probar**

\-Presione el botón Prueba para transmitir un código de aprendizaje.

\-Presione el botón Prueba una vez para ingresar al modo de prueba durante 3 minutos.

1. **Interruptor de puente de supervisión (JP2)**

**Puente encendido**

![](<.gitbook/assets/2 (65).jpeg>)

**Puente apagado**

![](<.gitbook/assets/3 (59).jpeg>)

El enlace del puente se inserta si se quita el enlace del puente o "**estacionado**”en un alfiler.

\~\~-\~\~Cuando el jumper está configurado en ON, la Supervisión está deshabilitada.**(Valor predeterminado de fábrica para 433 a.m.)**

\-Cuando el jumper está configurado en OFF, la Supervisión está habilitada.**(Valor predeterminado de fábrica para los modelos 868WF, 868FM, 869FM)**

_**Los modelos 433FM-F1, 868FM-F1 y 869-F1 no tienen este puente instalado y la supervisión siempre está habilitada**_

1. **Batería**
2. **Orificio para tornillo de seguridad de la cubierta**
3. **nocauts**
4. **Manibela de encendido**
5. **Orificio aislante de batería**
6. **Marcas de costillas**
7. **Imán**

\-Monte el imán en el costado del contacto de la puerta donde tiene 2 marcas de nervaduras para indicar la posición del interruptor magnético interno. El contacto de puerta debe instalarse en posición vertical o invertida para garantizar que el lado marcado con nervaduras mire hacia el imán.

1

*
  1. **Imán Orificio para tornillo**
  2. **Espaciador magnético**
* _**Accesorios incluidos**_
  *
    1. 1 imán
    2. 2 tornillos
    3. 1 almohadilla adhesiva de doble cara
    4. 2 enchufes de pared
    5. 2 tornillos de montaje magnético
    6. 1 espaciador magnético.
    7. 2 gorras blancas
* _**Indicador LED**_

![](<.gitbook/assets/4 (55).jpeg>) ![](<.gitbook/assets/5 (36).jpeg>)

En el modo de funcionamiento normal, el indicador LED permanece apagado excepto en las siguientes situaciones:

*
  * Cuando se activa el interruptor de manipulación del contacto de puerta.
  * Cada vez que se activa el contacto de puerta con condición de manipulación o batería baja.
  * Cada vez que el contacto de puerta se activa y transmite la señal en el modo de prueba.
* _**Supervisión**_
  * Si está habilitado, el contacto de puerta transmitirá automáticamente señales de supervisión periódicamente al panel de control en intervalos aleatorios de 30 a 50 minutos en el modo de funcionamiento normal.
  * Si el panel de control no ha recibido la señal del contacto de puerta durante un período de tiempo preestablecido, el panel de control indicará que el contacto de puerta en particular está experimentando un problema de falta de señal.
* _**Manibela de encendido**_
  * Está diseñado para proteger contra la extracción no autorizada de la ubicación montada, la apertura de la cubierta o la instalación inestable. Cuando se activa la manipulación, el contacto de puerta emitirá una señal al panel de control para informar y el LED también se iluminará.
* _**Batería**_

![](<.gitbook/assets/6 (45).jpeg>) ![](<.gitbook/assets/7 (42).jpeg>) ![](<.gitbook/assets/8 (38).jpeg>)

El contacto de puerta utiliza uno**Batería de litio CR2 de 3V**como fuente de energía, también es capaz de detectar batería baja. Cuando la batería está baja, se enviará una señal de batería baja al panel de control junto con una transmisión regular. El LED se iluminará cuando el contacto de puerta se active en estado de batería baja. Cuando la batería se agota, el contacto de la puerta detendrá todas sus funciones y el LED parpadeará cada 4 segundos.

* **Cambio de batería:**

Después de retirar la batería, presione el botón Aprender/Probar 5 o 6 veces para descargarla por completo antes de insertar la batería nueva.

![](<.gitbook/assets/9 (39).png>)

_\\_

*
  * Debido a las características de la batería, después de insertar una batería nueva en el contacto de puerta, éste comprobará automáticamente si esta batería funciona correctamente o no dentro de los 16 minutos posteriores a la inserción.
* _**Modo de prueba**_

![](<.gitbook/assets/10 (22).jpeg>)

El contacto de la puerta se puede poner en modo de prueba durante 3 minutos presionando una vez el botón de prueba en la cubierta frontal. Durante el modo de prueba, el indicador LED se encenderá al activarse. Cada vez que presione el botón de prueba, el contacto de la puerta transmitirá una señal de prueba al panel de control para la prueba del alcance del radio y restablecerá el modo de prueba a la duración de 3 minutos. Saldrá del modo de prueba automáticamente después de 3 minutos y volverá al modo de funcionamiento normal.

![](<.gitbook/assets/11 (25).jpeg>)

* _**Empezando**_

Paso 1: saque el aislante de la batería de manera constante

Paso 2: Coloque el Panel de control en modo de aprendizaje; consulte el manual del Panel de control para obtener más detalles.

Paso 3: Presione el botón de prueba en el contacto de la puerta para enviar la señal al panel de control.

Paso 4: Si el Panel de control recibe exitosamente la señal, el Panel de control debería responder (por ejemplo, emitiendo pitidos). Consulte el manual de su Panel de control para completar el proceso de aprendizaje.

Paso 5: Después de aprender el contacto de la puerta, coloque el panel de control en "**Prueba de caminata**”, mantenga presionado el contacto de la puerta en

la ubicación deseada y presione el botón Probar para confirmar si esta ubicación está dentro del alcance de la señal del panel de control.

Paso 6: Cuando esté satisfecho con el contacto de puerta en la ubicación elegida, continúe con la instalación.

![](<.gitbook/assets/12 (21).jpeg>)

* _**Instalación**_

Paso 1: Monte el contacto de la puerta utilizando uno de los métodos siguientes.

Paso 2: Monte el imán en el objeto más móvil (como una puerta) utilizando los tornillos proporcionados.

Alinee el imán según la marca de la nervadura en el contacto de la puerta.

Cuando sea necesario, utilice el espaciador magnético para alinear mejor el imán con las marcas de las nervaduras.

![](<.gitbook/assets/13 (28).png>)

* _NOTA >_
  * El imán no debe medir más que**15mm**del detector cuando la puerta está cerrada.
  * Las dos tapas blancas proporcionadas se pueden insertar en los orificios de los tornillos magnéticos para lograr una integridad estética.

2

* ![](<.gitbook/assets/14 (21).jpeg>)_**Métodos de montaje**_

Hay dos formas de montar el contacto de puerta: montaje autoadhesivo o montaje con tornillos.

![](<.gitbook/assets/15 (19).jpeg>)

* **Montaje autoadhesivo**

I. La superficie de montaje debe estar limpia, seca y lisa. Limpia el

superficie de montaje con un desengrasante adecuado si es necesario.

1. Retire la cubierta protectora de un lado de la almohadilla adhesiva de doble cara. Aplicar en la parte posterior del dispositivo y presionar firmemente para

30 segundos para asegurar un buen contacto.

1. Retire la otra cubierta y presione firmemente el contacto de la puerta sobre

la ubicación deseada durante 30 segundos.

![](<.gitbook/assets/16 (27).png>)

_\\_

*
  * No utilice el método de instalación con almohadilla adhesiva sobre una superficie con pintura descascarada o agrietada, o sobre una superficie rugosa.
  * No vuelva a aplicar la cinta adhesiva 3M. No se puede reutilizar
  * Instale el contacto de puerta en el objeto más estacionario (como el marco de una puerta o ventana) y monte el imán en el objeto más móvil (como una puerta o ventana).
* **Montaje con tornillos**

La base tiene dos orificios ciegos, donde el plástico es más delgado, para fines de montaje. Para montar el contacto de puerta:

*
  *
    1. Retire la cubierta desatornillando el tornillo de seguridad de la cubierta con un destornillador Philips.

![](<.gitbook/assets/17 (18).jpeg>)

1. Rompe el nocaut en la base.
2. Usando los agujeros como plantilla, taladre ambos agujeros.

IV. Inserte tacos de pared si lo fija en yeso o ladrillo.

1. Atornille la base al taco de pared con un destornillador Philips.

VI. Fije la cubierta a la base y apriete el tornillo de seguridad de la cubierta.

3
