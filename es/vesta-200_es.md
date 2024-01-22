# VESTA 200

**Contacto de puerta (DC-15SL-2W-F1) Manual del usuario**

El contacto de puerta monitorea la apertura/cierre de dispositivos específicos (por ejemplo, puerta o ventana). El contacto de puerta se fija al marco del dispositivo monitoreado con un imán de accionamiento fijado al dispositivo. Cuando se abre la puerta o ventana, el imán se aleja del contacto de la puerta, activando un interruptor magnético interno que hace que el contacto de la puerta transmita una señal de alarma al panel central. El dispositivo también tiene la capacidad de comunicar problemas de señal junto con situaciones de batería baja.

El diseño Door Contact consta de una cubierta y una base. La cubierta contiene todos los componentes electrónicos y la base proporciona un medio para fijar el dispositivo. Un interruptor antisabotaje de PCB incluido proporciona protección contra manipulación contra la apertura y/o extracción no autorizada del dispositivo.

El contacto de puerta es un dispositivo de transmisión de señales de radio bidireccional. Cuando se activa el contacto de puerta pero no recibe confirmación del panel de control, el contacto de puerta reenviará la señal para garantizar que el panel reciba la notificación correctamente.

![](<.gitbook/assets/0 (81).jpeg>)

_**Identificación de piezas**_

1.  **Indicador LED/botón de prueba**

Presione el botón Prueba para transmitir el código de aprendizaje o ingrese al modo de prueba durante 3 minutos.

1.  **Orificios de montaje**

Se utiliza para fijar y atornillar el contacto de la puerta directamente al marco de la puerta o a la pared.

1.  **Aislador de batería**
2.  **Manibela de encendido**

Proporciona protección contra manipulación contra la apertura y/o extracción no autorizada del dispositivo de la superficie de montaje.

_**Interruptor interno y terminal**_

Afloje el tornillo de fijación inferior y retire la cubierta para revelar el terminal como se muestra.

1.  **Terminal de extensión**

Además del interruptor magnético incorporado, se proporciona un terminal de contacto seco de 2 pines adicional para un interruptor magnético de extensión o cualquier dispositivo con funcionalidad N.C. (normalmente cerrado).

![](<.gitbook/assets/1 (71).jpeg>)![](<.gitbook/assets/2 (66).jpeg>)

**Puente encendido** **Puente apagado**

El enlace del puente se inserta si se quita el enlace del puente o "**estacionado**”en un alfiler.

-   1.  **Interruptor de puente magnético interno (JP3)**
        -   Cuando el puente está configurado en ON, el interruptor magnético interno está desactivado. Sólo el dispositivo conectado al terminal de extensión activará el contacto de puerta.
        -   Cuando el puente está configurado en APAGADO, el interruptor magnético interno está habilitado.

**(Valor predeterminado de fábrica para todos los modelos)**

-   1.  **Imán**
        -   Monte el imán en el costado del contacto de la puerta donde tiene 2 marcas de nervaduras para indicar la posición del interruptor magnético interno. El contacto de la puerta debe instalarse en posición vertical o invertida para garantizar que el lado marcado con nervaduras mire hacia el imán.
    2.  **Imán Orificio para tornillo**
    3.  **Magnet Spacer**
-   _**Accesorios incluidos**_

![](<.gitbook/assets/3 (60).jpeg>)

-   -   1.  1 imán y espaciador de imán.
        2.  Gorras blancas
        3.  Tornillos
        4.  2 enchufes de pared
-   _**Indicador LED**_
    -   En el modo de funcionamiento normal, el LED no se encenderá cuando se active el contacto de la puerta.
    -   Cuando el voltaje de la batería del contacto de puerta es bajo, cada vez que se activa el contacto de puerta (dispositivo abierto/cerrado), el LED se encenderá durante 2 segundos.

1

-   -   Cuando se abre la cubierta o se activa el interruptor de manipulación, el LED se iluminará durante 2 segundos. Cuando persiste una condición de manipulación, el LED se encenderá durante 2 segundos cada vez que se active el contacto de la puerta.
    -   Cuando el contacto de puerta está en modo de prueba, el LED se iluminará cada vez que se active.
    -   Cuando la batería se agota, el contacto de la puerta detendrá todas sus funciones y el LED parpadeará cada 4 segundos.
-   _**Batería**_
    -   El contacto de puerta utiliza uno**CR2, batería de litio de 3V**como su fuente de energía. Tenga en cuenta:**SIEMPRE**reemplace la batería con una del tamaño y voltaje correctos.
    -   El contacto de puerta puede detectar una condición de batería baja. Cuando el voltaje de la batería es bajo, se enviará una señal de batería baja al panel de control para notificar la condición. El LED se iluminará cuando el contacto de puerta se active en estado de batería baja. Cuando la batería se agota, el contacto de la puerta detendrá todas sus funciones y el LED parpadeará cada 4 segundos.
    -   Al cambiar las baterías, después de quitar las baterías viejas, presione el interruptor de manipulación dos veces para descargarlas por completo antes de insertar baterías nuevas.
-   _**Señal de supervisión**_
    -   El contacto de puerta transmitirá automáticamente señales de supervisión periódicamente al panel de control en intervalos aleatorios de 90 a 110 minutos.
    -   Si el panel de control no ha recibido la señal del contacto de puerta durante un período de tiempo preestablecido, el panel de control indicará que el contacto de puerta en particular está experimentando un problema de falta de señal.
-   _**Modo de prueba**_
    -   En el modo normal, presione el botón de prueba para transmitir una señal de prueba y un código de aprendizaje al panel de control. El contacto de la puerta también entrará en el modo de prueba durante 3 minutos.
    -   En el modo de prueba, el LED se iluminará cada vez que se active el contacto de la puerta.
    -   Cada pulsación adicional del botón de prueba restablecerá el tiempo del modo de prueba a 3 minutos.
-   _**Empezando**_
    -   Saque el aislante de la batería para activar la batería.
    -   Coloque el panel de control en modo de aprendizaje (consulte el manual de operación del panel).
    -   Presione el botón de prueba de contacto de puerta.
    -   Consulte el manual de funcionamiento de su panel de control para completar el proceso de aprendizaje.
    -   Una vez aprendido el contacto de la puerta, coloque el panel de control en (**Prueba de caminata)**modo, mantenga el contacto de la puerta en la ubicación deseada y presione el botón de prueba para transmitir la señal de prueba al panel de control. Si el panel de control está dentro del rango de señal de contacto de puerta, el panel mostrará la información de contacto de puerta en consecuencia.
    -   Continúe con el montaje y la instalación una vez que esté satisfecho de que la ubicación del contacto de la puerta funciona correctamente.
-   _**Métodos de montaje e instalación**_

Se recomienda que el contacto de la puerta se coloque en el marco de la puerta/ventana y el imán en la puerta/ventana.

Paso 1: Encuentre una ubicación adecuada cerca de su puerta/ventana para instalar el contacto de puerta. Realice una prueba de recorrido para comprobar si la posición está dentro del alcance de la señal del panel de control.

Paso 2: El contacto de la puerta tiene 2 marcas de nervaduras en un lado (consulte la figura), que marcan la ubicación del interruptor magnético interno. El contacto de la puerta debe instalarse en posición vertical o invertida, para garantizar que el lado marcado con las nervaduras mire hacia el imán.

Paso 3: Para montar el contacto de puerta:

1.  Retire las tapas blancas que cubren los dos orificios de montaje.
2.  Utilice los 2 orificios de montaje como plantilla para la colocación adecuada de los orificios.
3.  Utilice los tacos de pared proporcionados para la instalación de yeso/ladrillo.
4.  Atornille el contacto de la puerta en los tacos de pared proporcionados con un destornillador Philips.
5.  Vuelva a colocar las tapas blancas para cubrir los dos orificios de montaje.
    -   _NOTA >_
        -   Asegúrese de que el resorte del interruptor antisabotaje esté colocado de manera que haga contacto con la superficie de montaje a través de la apertura del interruptor antisabotaje.

![](<.gitbook/assets/4 (56).jpeg>)

Paso 4: Para montar el imán:

(i) Utilice los 2 orificios para tornillos magnéticos como plantilla para la colocación adecuada de los orificios.

2

-   _NOTA >_
    -   El imán no debe estar a más de 15 mm del contacto de la puerta cuando la puerta está cerrada.
    -   El imán debe alinearse con el lado de la marca de la nervadura del contacto de la puerta. Si es necesario, aplique el espaciador del imán en la parte posterior del imán para alinear mejor el imán con las marcas de las nervaduras.

![](<.gitbook/assets/5 (37).jpeg>)

1.  Atornille el imán a la puerta.
2.  Inserte las dos tapas blancas en los orificios de los tornillos magnéticos para lograr integridad estética. Paso 5: La instalación ya está completa.

-   _**Uso del terminal de extensión**_

El contacto de puerta tiene un terminal de extensión para proporcionar mayor flexibilidad. El terminal de extensión forma un circuito cerrado con el dispositivo conectado a él. Cuando se activa el dispositivo, se abrirá el bucle; También se activará el contacto de puerta.

![](<.gitbook/assets/6 (46).jpeg>)

El terminal de extensión y el interruptor magnético interno pueden funcionar juntos para activar el contacto de puerta cuando cualquiera de ellos está activado; también puede optar por desactivar el interruptor magnético interno a través de la configuración del puente JP3.

Para conectar el dispositivo al terminal de extensión:

1.  Abra el contacto de la puerta aflojando el tornillo de fijación con un destornillador Philips.
2.  El extremo superior de la caja frontal tiene un orificio de plástico más delgado. Rompe el orificio ciego para crear un orificio para la conexión del cableado al terminal de extensión.
3.  Conecte el dispositivo al terminal de extensión.

El terminal de extensión puede resultar útil para la siguiente situación.

-   Si el contacto de puerta no se puede montar en el marco de la puerta, puede conectar un interruptor de extensión adicional al terminal de extensión para montar el contacto de puerta de forma remota.
-   Cualquier dispositivo de contacto seco con bucle N.C. (cierre normal) se puede conectar al terminal de extensión, lo que hace que el contacto de puerta sirva como un transmisor universal.
-   Se pueden conectar varios dispositivos de contacto seco junto con el contacto de puerta, como se muestra en el diagrama a continuación.

![](<.gitbook/assets/7 (43).jpeg>)![](<.gitbook/assets/8 (39).jpeg>)

_\\<NOTE>_

-   **Si tanto el interruptor magnético interno como el terminal de extensión funcionan juntos, entonces:**

Cuando se abre/cierra la puerta protegida**o**El dispositivo externo se activa, el contacto de puerta se activa y transmite una señal inmediatamente.

Sin embargo, el contacto de puerta sólo transmitirá una**Puerta cerrada**o**Restaurado**señal después de la puerta**y**el dispositivo externo se restaura durante 3 segundos.

3
