# VESTA 148

**EIRP-J1/EIRC-J2 Aprenda en las instrucciones**

El transmisor GEN-TX está instalado dentro de EIRP-J1 y EIRC-J2, lo que les permite enviar señales de RF inalámbricas al panel de control.

Las antenas de GEN-TX son diferentes según la frecuencia 433 y 868.

**PIRE-J1****EIRC-J2****Frecuencia 433****Frecuencia 868**

![](<.gitbook/assets/0 (43).png>)

-   _**Identificar las piezas**_

1.  **Botón Aprender/Probar**
2.  **Batería (CR2)**
3.  **Interruptor de puente de supervisión (JP2)**
4.  **Indicador LED (rojo)**

![](<.gitbook/assets/1 (49).png>)![](<.gitbook/assets/2 (54).png>)

-   _**Indicador LED**_

En el modo de funcionamiento normal, el indicador LED permanece apagado excepto:

-   -   Cuando el detector de movimiento tiene batería baja, cada vez que transmite un movimiento detectado, el LED parpadeará 6 veces.
    -   Cuando se activa el interruptor de manipulación, el LED parpadeará 6 veces para indicar que está transmitiendo "**Manosear**”señal.
    -   Cuando la condición de Tamper persiste, cada vez que transmite un movimiento detectado, el LED parpadeará 6 veces.
    -   Cuando la batería esté agotada, el LED parpadeará cada 4 segundos.
-   _**Aprendiendo**_
    -   Para EIRP-J1, primero separe la caja posterior y la placa de montaje. Para EIRC-J2, primero separe la base de montaje. (Consulte las Instrucciones de instalación de VXI-R y FTN-R-PT para obtener más detalles).
    -   Saque el aislante de la batería para activar la batería.
    -   Coloque el Panel de control en modo de aprendizaje; consulte el manual del Panel de control para obtener más detalles.
    -   Presione el botón Aprender.
    -   Consulte el manual del Panel de control para completar el proceso de aprendizaje.

![](<.gitbook/assets/3 (53).png>)

1

-   ![](<.gitbook/assets/4 (53).png>)_**Prueba de caminata**_
    -   Después de que el detector se haya memorizado, coloque el panel de control en "**Prueba de caminata**", sostenga el detector en la ubicación deseada y presione el botón Prueba para confirmar que esta ubicación está dentro del alcance de la señal del panel de control; consulte el manual del panel de control para completar la prueba de caminata.
    -   Cuando esté satisfecho de que el detector funciona en la ubicación elegida, puede proceder al montaje.
-   _**Batería**_
    -   The detector uses one “CR2”, 3V Lithium battery as its power source.
    -   Cuando se detecta batería baja, se enviará una señal de batería baja al Panel de control junto con transmisiones de señal regulares para que el Panel de control muestre el estado correspondiente.
    -   Cuando la batería se agota, el detector detendrá todas sus funciones y el LED parpadeará cada 4 segundos.
    -   Al cambiar la batería, después de quitar la batería vieja, presione el botón Aprender dos veces para descargarla completamente antes de insertar una batería nueva.
-   _**Supervisión**_
    -   Después de la instalación, el detector transmitirá automáticamente señales de supervisión periódicamente al panel de control en intervalos aleatorios de 30 a 50 minutos.
    -   Si el panel de control no ha recibido la señal del detector durante el período de tiempo preestablecido, el panel de control indicará en su pantalla que el detector en particular está experimentando un problema de falta de señal.

![](<.gitbook/assets/5 (52).png>)![](<.gitbook/assets/6 (34).png>)![](<.gitbook/assets/7 (32).jpeg>)

**Puente APAGADO (valor predeterminado de fábrica)**

\-Cuando el jumper (JP2) está configurado en OFF, la Supervisión está habilitada.

**Puente encendido**

![](<.gitbook/assets/8 (25).jpeg>)

-   Cuando el puente (JP2) está configurado en ON, la Supervisión está deshabilitada.

2
