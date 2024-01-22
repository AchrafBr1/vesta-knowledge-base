# VESTA 103

**Control de obturador (SCM-8)**

**Introducción**

SCM-8 es un control de persianas enrollables que proporciona una operación conveniente, subir, bajar o detener de forma remota persianas enrollables motorizadas.

El control de persianas enrollables tiene dos salidas de motor para control automático y remoto y dos interruptores locales para control manual opcional. El usuario puede controlar el SCM-8 a través del Panel de Control a distancia o manualmente activando interruptores locales.

SCM-8 también está equipado con una abrazadera de alivio de tensión y una hebilla de cableado para la integridad eléctrica y mecánica, el rendimiento general y la seguridad.

**Identificación de piezas**

1.  **Botón de prueba**
    -   Presione una vez: transmite la señal de supervisión.
    -   Informar la posición actual al Panel de control.
    -   Mantenga presionado durante 3 segundos: envíe un código de aprendizaje.
    -   Mantenga presionado el botón mientras enciende el control del obturador, mantenga presionado el botón durante aproximadamente 4 segundos, luego suelte el botón cuando el LED

parpadea 3 veces para restablecer los valores de fábrica.

-   -   Mantenga presionado durante 10 segundos: ingrese al modo de calibración.

1.  **Indicador LED**

![](<.gitbook/assets/0 (48).jpeg>)

El indicador LED se utiliza para indicar el estado del control de persianas:

-   -   -   Parpadea una vez: cuando está encendido.
        -   Parpadea dos veces: cuando el aprendizaje es exitoso.
        -   Parpadea 3 veces: el control del obturador se ha restablecido a los valores de fábrica.
        -   Se enciende de forma fija: en modo aprendizaje.
        -   Parpadea continuamente: cuando está en modo de calibración.

1.  **Orificios de montaje**
2.  **Interruptor local S1 (dirección abierta)**
    -   Conecte un interruptor externo a este terminal. Active este interruptor para controlar que la persiana gire hacia la dirección "Abrir" activando la salida del motor O1.
    -   Activar este interruptor cuando la persiana está girando hacia la dirección "Cerrar" detendrá la persiana.
3.  **Interruptor local S2 (dirección de cierre)**
    -   Conecte un interruptor externo a este terminal. Activar

este interruptor controla la persiana para que gire hacia la dirección de "Cerrar" activando la salida del motor O2.

-   -   Activar este interruptor cuando la persiana está girando hacia la dirección "Abrir" detendrá la persiana.

1.  **Salida del motor O1 (dirección abierta)**

Conéctelo al terminal abierto del motor de la persiana.

**7. Salida del motor O2 (dirección de cierre)**

Connect to the Close terminal of the Shutter Motor.

1.  **Entrada de alimentación L (conductor activo)**
2.  **Entrada de alimentación N (conductor neutro)**
3.  **Abrazadera de alivio de tensión**

La abrazadera se utiliza para asegurar los cables y proporcionar alivio de tensión para proteger los cables del recorte de metal.

**11. Hebilla de cableado**

La hebilla de cableado se utiliza para gestionar los cables.

1

**Especificación**

-   Fuente de alimentación: 100 - 240 VCA, 50/60 Hz
-   Corriente de carga admitida: 1/2 HP (caballos de fuerza); 3,6Amperios para motores con factor de potencia compensado (cargas inductivas)

![](<.gitbook/assets/1 (40).jpeg>)

**Precaución**

-   Todos los trabajos en el dispositivo, incluida la instalación y el mantenimiento, deben ser realizados por un electricista calificado y autorizado.
-   Antes de la instalación o cualquier trabajo de mantenimiento, asegúrese de que la fuente de alimentación esté desconectada.
-   No conecte el dispositivo a cargas que excedan la corriente de carga admitida.
-   Conecte el dispositivo únicamente a un motor alimentado por CA.

**Alambrado**

-   SCM-8 debe conectarse de acuerdo con el siguiente diagrama:

![](<.gitbook/assets/2 (35).jpeg>)

-   -   Conecte el terminal N del SCM al terminal N de la fuente de alimentación.
    -   Conecte el terminal L del SCM al terminal L de la fuente de alimentación.
    -   Conecte el terminal O1 del SCM al terminal abierto del motor de la persiana.
    -   Conecte el terminal O2 del SCM al terminal de cierre del motor de la persiana.
    -   **(Conmutador local opcional)**Conecte los terminales S2 y S1 del SCM al terminal L de la fuente de alimentación.
-   Inserte cada cable en el terminal al que debe conectarse, apriete cada tornillo para cerrar las cortadoras y mantener los cables en su lugar.
-   Después de conectar los cables, utilice la hebilla de cableado para gestionar los cables y coloque la hebilla de cableado en la base con su espacio (abertura) colocado a la izquierda.

![](<.gitbook/assets/3 (32).jpeg>)

2

**Aprendiendo**

Paso 1: Conecte la fuente de alimentación al control de persiana de acuerdo con las instrucciones de instalación de la sección anterior y encienda el control de persiana.

Paso 2: ponga el Panel de control en modo de aprendizaje.

Paso 3: Mantenga presionado el botón Prueba en el control del obturador durante 3 segundos para enviar un código de aprendizaje.

Paso 4: El LED parpadeará una vez y luego se encenderá fijamente después de soltar el botón, lo que indica que el control del obturador está en modo de aprendizaje.

Paso 5: Si el panel de control recibe la señal del control del obturador, mostrará la información correspondiente. Consulte el manual del Panel de control para completar el proceso de aprendizaje.

Paso 6: Cuando el control del obturador recibe el código de aprendizaje del panel de control, el LED del control del obturador parpadeará dos veces y luego se apagará para indicar que el proceso de aprendizaje se ha completado.

_\\<NOTE>_

-   Después de ingresar al modo de aprendizaje, si el control del obturador no recibe confirmación del panel de control durante 1 minuto, saldrá automáticamente del modo de aprendizaje.
-   Si el control del obturador ya existe en un sistema de panel de control, primero deberá eliminar el control del obturador del panel de control antes de poder aprenderlo en un panel de control diferente.

**Prueba de caminata**

Para probar si el control del obturador puede comunicarse con el panel de control:

-   Coloque el panel de control en modo de prueba de recorrido.
-   Presione el botón de prueba en el control del obturador.
-   El panel de control debería mostrar si el control del obturador está dentro del rango de operación (consulte el manual de operación del panel de control).

**Montaje**

-   Una vez que haya finalizado la prueba de recorrido y esté satisfecho de que el dispositivo puede comunicarse con el panel de control en la ubicación elegida, continúe con el montaje.
-   Desconecte la fuente de alimentación principal.
-   Afloje el tornillo de fijación inferior y retire la cubierta superior del Control de Persiana.
-   Utilice los orificios de montaje de la base para marcar la ubicación de montaje en la pared.
-   Taladre agujeros en el lugar marcado e inserte tacos de pared si es necesario, atornille la base en el lugar de montaje.
-   Vuelva a colocar la cubierta superior y apriete el tornillo de fijación inferior.

**Supervisión**

-   Después de que el control del obturador se haya aprendido correctamente en el panel de control, el dispositivo transmitirá automáticamente una señal de supervisión junto con el informe de posición actual al panel de control en intervalos aleatorios de 30 a 50 minutos.
-   Si el panel de control no ha recibido la señal del control de la persiana durante el período de tiempo preestablecido, el panel de control indicará en su pantalla que el control de la persiana en particular está experimentando un problema de falta de señal.

**Operación**

-   _**Calibración**_
    -   El tiempo de activación predeterminado del control de persianas es**4**minutos. Cuando se presiona el botón Arriba/Abajo o el Panel de control envía una solicitud Arriba/Abajo, activará el motor de la persiana durante 4 minutos.
    -   For the Shutter Control to work properly, its activation time must be calibrated manually. Calibrate the activation time according to procedures below:
        1.  Antes de la calibración, los interruptores locales externos deben estar conectados al control de persianas.
        2.  Mantenga presionado el botón de prueba durante 10 segundos y luego suéltelo para ingresar al modo de calibración (el LED parpadeará dos veces). El control del obturador girará hacia la dirección "Abrir" durante 4 minutos después de ingresar al modo de calibración.
        3.  Espere 4 minutos hasta que el motor de la persiana deje de girar, luego presione el botón "Abajo" para bajar la persiana. (Si en menos de 4 minutos la persiana ya ha alcanzado la posición abierta, puede presionar el botón "Abajo" para detener el motor de la persiana. Luego presione el botón "Abajo" nuevamente para bajar la persiana).

3

1.  Presione el botón "Arriba" en el momento en que el obturador esté completamente cerrado. El control del obturador registrará el tiempo que tardó el obturador en abrirse y cerrarse como el nuevo "**hora de cierre**”.
2.  El control del obturador girará hacia la dirección de apertura después del paso 4 (cuando se presiona el botón "Arriba" en el momento en que el obturador esté completamente cerrado).
3.  Presione el botón "Abajo" en el momento en que el obturador esté completamente abierto. El control del obturador registrará el tiempo que tardó el obturador en pasar de cerrado a abierto como el nuevo "**tiempo abierto**”.
4.  Una vez completada la calibración, el control de la persiana enviará un informe de posición actual al panel de control y funcionará con un nuevo tiempo de cierre/apertura.

Ejemplo

Si el obturador tarda 30 segundos en pasar de Abierto a Cerrado y 40 segundos en pasar de Cerrado a Abierto, el nuevo**hora de cierre**será**30**segundos y nuevo**tiempo abierto**será**40**segundos.

Después de la calibración, siempre que el control del obturador reciba una solicitud de cierre, girará hacia la dirección de cierre durante 30 segundos. Cuando recibe una solicitud de apertura, avanzará hacia la apertura durante 40 segundos.

-   -   El tiempo de activación se restablecerá a**4**minutos cada vez que el control del obturador se restablece a los valores de fábrica.
-   _**Control de obturador**_

**Control remoto**

-   Una vez que el control de la persiana se aprende con éxito en el panel de control, el usuario puede controlar de forma remota la persiana para abrirla, cerrarla o detenerla a través de la página web del panel de control.
-   Cuando el control de la persiana recibe una solicitud de apertura/cierre del panel de control, se moverá hacia la dirección de apertura/cierre de acuerdo con el tiempo de activación calibrado para abrir/cerrar completamente la persiana.
-   El estado del obturador también se puede ajustar por porcentaje desde 0%, 10%, 20%... hasta 100% a través de la página web del Panel de control.
-   El porcentaje de apertura actual también se transmite al Panel de control.

![](<.gitbook/assets/4 (48).png>)

**Conmutador local**

-   Si se conecta un interruptor local opcional, los usuarios también pueden presionar el botón del interruptor para abrir/cerrar la persiana.
-   Presione y suelte el interruptor durante menos de 1 segundo para controlar que el obturador se abra o cierre completamente.
-   Al presionar el interruptor cuando la persiana se está moviendo en la dirección opuesta, se detendrá la persiana. Presione el interruptor nuevamente para abrir/cerrar la persiana.

Por ejemplo, presionar el interruptor hacia abajo cuando la persiana se está abriendo detendrá la persiana; presione el interruptor hacia abajo nuevamente para comenzar a cerrar la persiana.

**Restablecimiento de fábrica**

-   El restablecimiento de fábrica del control del obturador borrará su memoria y lo restaurará a la configuración predeterminada de fábrica.
-   Mantenga presionado el botón mientras enciende el control del obturador, mantenga presionado el botón durante aproximadamente 4 segundos, luego suelte el botón cuando el LED parpadee 3 veces para restablecer los valores de fábrica.

4
