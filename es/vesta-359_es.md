# VESTA 359

**Manual del usuario del contacto de puerta cableado (DC-23-BUS)**

DC-23-BUS es un contacto de puerta cableado que monitorea la apertura/cierre de dispositivos específicos (por ejemplo, puerta o ventana). El contacto de puerta cableado se fija al marco del dispositivo monitoreado con un imán de accionamiento fijado al dispositivo. Cuando se abre la puerta o ventana, el imán se aleja del contacto de puerta cableado, activando un interruptor magnético interno que hace que el contacto de puerta cableado transmita señales de alarma a través de BUS al panel de control.

Con un terminal de extensión incorporado, DC-23-BUS también se puede conectar a un dispositivo cableado para funcionar como un transmisor universal.

El diseño de Wired Door Contact consta de una cubierta y una base. La cubierta contiene todos los componentes electrónicos y la base proporciona un medio para fijar el dispositivo. Un interruptor antisabotaje de PCB incluido proporciona protección contra manipulación contra la apertura y/o extracción no autorizada del dispositivo.

**Identificación de piezas**

![](<.gitbook/assets/0 (2).jpeg>)

1.  **Indicador LED/botón de prueba**

Presione el botón Prueba para ingresar al modo de prueba durante 3 minutos.

1.  **Tornillo de fijación de la cubierta**
2.  **Interruptor de puente de entrada (JP2)**

![](<.gitbook/assets/1 (3).png>)

**Puente encendido****Puente apagado**

![](<.gitbook/assets/2 (3).jpeg>)![](<.gitbook/assets/3 (1) (1).jpeg>)

Se inserta el enlace del puente, conectando los dos. Se retira el enlace del puente o "**estacionado**" en uno

patas. alfiler.

-   -   Puente ON: Normalmente cerrado (N.C.) está configurado.
    -   Puente APAGADO: Normalmente abierto (N.A.) está configurado**(Predeterminado de fábrica)**.

1.  **Interruptor de puente de resistencia terminal**

Cuando el contacto de puerta está conectado como el dispositivo BUS más lejano en una línea BUS, configure el puente de resistencia terminal del contacto de puerta y el interruptor de puente del primer dispositivo BUS (generalmente el panel híbrido) en ON para que sirvan como resistencias de terminación. Se mejorará la capacidad de comunicación de la línea BUS conectada.

![](<.gitbook/assets/4 (2).png>)

**Puente encendido**

Se inserta el enlace del puente, conectando los dos pines.

**Puente apagado**

El enlace del puente se elimina o "**estacionado**”en un alfiler.

-   -   Si el puente está activado, se mejorará la capacidad de comunicación.
    -   Si el puente está APAGADO, la capacidad de comunicación está en nivel normal.

1.  **Terminal de autobus**
2.  **Terminal de extensión**

Además del interruptor magnético incorporado, se proporciona un terminal de contacto seco de 2 pines adicional para un interruptor magnético de extensión o cualquier dispositivo con conexión N.C. (normalmente cerrado) o N.A. (Normalmente abierto) funcionalidad.

1.  **Manibela de encendido**

Cuando se monta el contacto de puerta cableado, el interruptor de manipulación se activará cuando se abra la cubierta o cuando se retire el contacto de puerta cableado de la superficie de montaje.

1.  **Orificios de montaje**

Se utiliza para fijar y atornillar el contacto de puerta directamente al marco de la puerta o a la pared.

1

1.  **Área de separación para orificios de cableado (para terminal de autobuses)**
2.  **Imán**
3.  **Orificio para tornillo magnético**
4.  **Espaciador magnético**

**Características**

![](<.gitbook/assets/5 (4).png>)

-   _**Indicador LED**_
    -   En el modo de funcionamiento normal, el LED no se iluminará cuando se active el contacto de puerta cableado.
    -   Cuando se abre la cubierta del contacto de puerta cableado o se activa el interruptor de manipulación, el LED parpadeará 3 veces. Cuando la condición de manipulación continúa, el LED parpadeará 3 veces cada vez que se active el contacto de puerta cableado.
    -   Cuando el contacto de puerta cableado está en modo de prueba, el LED parpadeará 3 veces cada vez que se active.
-   _**Terminal de extensión**_

![](<.gitbook/assets/6 (2).png>)

DC-23-BUS tiene un terminal de extensión para proporcionar mayor flexibilidad. Según la configuración de JP2, el terminal de extensión forma un bucle cerrado (Normalmente cerrado (N.C.)) o abierto (Normalmente abierto (N.A.)) con el dispositivo conectado a él. Cuando se activa el dispositivo conectado al terminal de extensión, se activará el contacto de puerta cableado.

| Para conectar el dispositivo al terminal de extensión: | _**Vista superior del DC-23-BUS**_ |   |
| ------------------------------------------------------ | ---------------------------------- | - |
|                                                        |                                    |   |

![](<.gitbook/assets/7 (1).jpeg>)

1.  Abra la cubierta del contacto de puerta cableado con un destornillador aflojando el tornillo de fijación de la cubierta en la parte inferior del dispositivo.
2.  El extremo superior de la caja frontal tiene un orificio de plástico más delgado. Rompe el orificio ciego para crear un orificio para la conexión del cableado al terminal de extensión.
3.  Conecte el dispositivo al terminal de extensión.

![](<.gitbook/assets/8 (1).jpeg>)

El terminal de extensión puede resultar útil para las siguientes situaciones:

-   Si el contacto de puerta cableado no se puede montar en el marco de la puerta, puede conectar un interruptor magnético de extensión adicional al terminal de extensión para montar el contacto de puerta de forma remota.
-   Cualquier dispositivo de contacto seco con cierre N.C. (Normal Cerrado) o N.A. El bucle (normalmente abierto) se puede conectar al terminal de extensión haciendo que el contacto de puerta cableado sirva como un transmisor universal.
-   Se pueden conectar varios dispositivos de contacto seco junto con el contacto de puerta cableado, como se muestra en la siguiente imagen.

![](<.gitbook/assets/9 (5).png>)

-   _**Fuente de alimentación**_
    -   Cuando DC-23-BUS está cableado a un panel híbrido, el panel híbrido puede proporcionar una fuente de alimentación de 13,5 V.
-   _**Protección contra manipulación**_
    -   El contacto de puerta cableado está protegido por un interruptor antisabotaje que se comprime contra la superficie de montaje cuando el contacto de puerta cableado está montado en su lugar. Cada vez que se abre o retira la cubierta del contacto de puerta cableado de la superficie de montaje, se activará el interruptor de manipulación y el contacto de puerta cableado enviará una señal de apertura de manipulación para recordarle al usuario la condición.
-   _**Señal de supervisión**_
    -   El contacto de puerta cableado transmitirá automáticamente señales de supervisión periódicamente al panel de control en intervalos aleatorios de 20 a 30 segundos.
    -   Si el panel de control no ha recibido la señal del contacto de puerta cableado durante un período de tiempo preestablecido, el panel de control indicará que el contacto de puerta en particular está experimentando un problema de falta de señal.
-   _**Modo de prueba**_
    -   En el modo normal, presione el botón de prueba para transmitir una señal de prueba al panel de control. El contacto de puerta cableado entrará en modo de prueba durante 3 minutos.
    -   En el modo de prueba, el LED parpadeará 3 veces cada vez que se active el contacto de puerta cableado.
    -   Cada pulsación adicional del botón de prueba restablecerá el período del modo de prueba a 3 minutos.

![](<.gitbook/assets/10 (5).png>)![](<.gitbook/assets/11 (3).png>)![](<.gitbook/assets/12 (4).png>)

2

-   ![](<.gitbook/assets/13 (5).png>)_**Precaución**_
    -   El cableado del contacto de la puerta sólo debe ser realizado por técnicos certificados con el conocimiento y la formación adecuados en equipos eléctricos.
    -   Antes de la instalación o cualquier trabajo de mantenimiento, asegúrese de que la fuente de alimentación esté desconectada.
-   _**Cableado de contacto de puerta**_
    -   -   Antes de conectar el contacto de puerta cableado al BUS del sistema, apague la alimentación.
        -   Para ayudar con las conexiones de cables, los bloques de terminales de cada módulo del sistema BUS están codificados por colores.

![](<.gitbook/assets/14 (4).png>)![](<.gitbook/assets/15 (2).jpeg>)

| **Rojo**     | VDD    |
| ------------ | ------ |
| **Negro**    | Tierra |
| **Amarillo** | 485A   |
| **Verde**    | 485B   |

-   Se pueden conectar varios dispositivos BUS en serie al panel híbrido. Para una comunicación óptima de los dispositivos de la línea BUS conectados, asegúrese de que los interruptores de puente de resistencia terminal del primero (generalmente el panel híbrido) y del último dispositivo BUS en una línea BUS estén configurados. en ON para servir como resistencias terminales. Asegúrese de habilitar solo los 2 interruptores de puente antes mencionados y no configurar los interruptores de puente en ON para ningún otro dispositivo BUS intermedio.

_\\<NOTE>_

-   -   El diseño enchufable de los bloques de terminales BUS mejora la eficiencia de la instalación. Antes de realizar el cableado, puede retirar los bloques de terminales de la placa PCB para facilitar su uso y enchufarlos nuevamente después del cableado.
    -   Después de desconectar el terminal, al volver a instalarlo en la placa, asegúrese de instalar el terminal en la misma dirección para evitar posibles peligros.
-   Las conexiones incorrectas provocarán fallas o mal funcionamiento. Inspeccione el cableado y asegúrese de que las conexiones sean adecuadas antes de aplicar energía.

![](<.gitbook/assets/16 (5).png>)

-   _**Aprendiendo**_

Siga los pasos a continuación para aprender el dispositivo en el panel híbrido.

Paso 1: Conecte el dispositivo al Panel. Luego, encienda el Panel.

Paso 2: En la página web del Panel, haga clic en "**Aprendiendo**”para ingresar a la página de aprendizaje.

Paso 3: Haga clic en "**Comenzar**”para ingresar al modo de aprendizaje.

Paso 4: Haga clic en "**Agregar**”para incluir el dispositivo en el Panel.

Paso 5: Si el dispositivo se reconoce correctamente en el Panel, se mostrará en la sección "Dispositivo aprendido".

-   Cuando se aprende en el Panel, DC-23-BUS será reconocido como 2 dispositivos separados y ocupará 2 zonas en el Panel.

![](<.gitbook/assets/17 (3).png>)

3

![](<.gitbook/assets/18 (5).png>)

-   Para diferenciar los 2 dispositivos separados, se recomienda cambiar el nombre del dispositivo por

haciendo clic en "Editar" debajo de la lista de dispositivos después de la entrada de la columna del dispositivo.

Como se muestra en la página Editar dispositivo, el ID con los dos últimos dígitos de "**00**” representa el interruptor magnético interno.

![](<.gitbook/assets/19 (4).png>)

El DNI con los dos últimos dígitos de “**02**” representa el terminal de extensión.

![](<.gitbook/assets/20 (4).png>)

-   _**Identificación**_

La función "Identificar" se utiliza para localizar un dispositivo BUS específico en el sistema cableado BUS. Esta función es útil para distinguir qué dispositivo es cuál, especialmente en una instalación grande donde se incluyen numerosos dispositivos BUS.

Para ubicar el contacto de puerta cableado en el sistema BUS:

**Paso 1.**En la página web del Panel híbrido, haga clic en "Identificar" debajo de la lista de dispositivos después de la entrada de la columna de dispositivos del DC-23-BUS.

**Paso 2.**Si el contacto de puerta cableado recibe la señal del panel híbrido, la página web mostrará un mensaje de éxito y el indicador LED del contacto de puerta cableado parpadeará 10 veces para indicarle al usuario dónde está.

_\\<NOTE>_

-   -   -   Si se muestra un mensaje de tiempo de espera en la página web, significa que el contacto de puerta cableado no recibió la señal del panel.

Verifique si DC-23-BUS está conectado correctamente al panel dentro de la distancia de cableado adecuada.

-   _**Prueba de caminata**_
    -   Para asegurarse de que el contacto de puerta cableado pueda comunicarse con el panel después de su aprendizaje, coloque el panel de control en modo de prueba de recorrido y presione el botón de prueba en DC-23-BUS para transmitir una señal de prueba al panel de control.
    -   Cuando el panel reciba la señal de prueba, emitirá un pitido y mostrará la información del contacto de puerta cableado en la parte superior de la lista de dispositivos.

_\\<NOTE>_

-   Si no hay respuesta del Panel después de presionar el botón de prueba, significa que el Panel no recibió la señal de prueba del dispositivo.

Verifique si DC-23-BUS está conectado correctamente al panel dentro de la distancia de cableado adecuada.

**Instalación**

-   _**Guía de instalación**_
    -   El contacto de puerta cableado debe instalarse en el marco de la puerta/ventana y el imán en la puerta/ventana.
    -   La distancia entre el contacto de puerta cableado y el imán no debe ser superior a 15 mm cuando la puerta está cerrada.
    -   Evite montar el contacto de puerta cableado en superficies metálicas. Si se monta sobre superficies metálicas, asegúrese de probar si el contacto de puerta cableado se puede activar cuando se abre la puerta.
    -   Monte el contacto de puerta cableado lo más alto posible.
-   _**Montaje del contacto de puerta cableado**_

1.  Encuentre una ubicación adecuada cerca de su puerta/ventana para instalar el contacto de puerta cableado.
2.  El contacto de puerta cableado tiene 2 marcas de nervaduras en un lado (consulte la figura), que marcan la ubicación del interruptor magnético interno. El contacto de puerta cableado debe instalarse en posición vertical o invertida para garantizar que el lado marcado con nervaduras mire hacia el imán.
3.  Para montar el contacto de puerta cableado:
    -   1.  Utilice los 2 orificios de montaje como plantilla y taladre orificios en el marco que se va a montar.
        2.  Utilice los tacos de pared proporcionados para la instalación de yeso/ladrillo.
        3.  Atornille el contacto de la puerta en los tacos de pared proporcionados.
4.  Para montar el imán:
    1.  Utilice los 2 orificios para tornillos magnéticos como plantilla y taladre orificios en la puerta/ventana que se va a montar.

-   _NOTA >_
    -   El imán no debe estar a más de 15 mm del contacto cableado de la puerta cuando la puerta está cerrada.
    -   El imán debe alinearse con el lado de la marca de la nervadura del contacto de puerta cableado. Si es necesario, aplique el espaciador del imán en la parte posterior del imán para alinear mejor el imán con las marcas de las nervaduras.
    -   Atornille el imán a la puerta/ventana.
    -   Inserte las dos tapas blancas en los orificios de los tornillos magnéticos para lograr integridad estética.

1.  La instalación ya está completa.

4
