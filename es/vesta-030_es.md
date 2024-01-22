# VESTA 030

**Repeater (RP-29)**

El Repetidor está diseñado para aumentar la eficacia y versatilidad del sistema de alarma. Es un dispositivo que hace que su sistema sea más potente al aumentar la distancia máxima posible entre la Unidad Principal (Panel de Control) y los Dispositivos.

-   **Identificar las piezas**

![C:\\Documents and Settings\\C0874.CLIMAX-TECH\\桌面\\done\\to be completed\\manual pictures\\RP-23 20140415.jpg](<.gitbook/assets/0 (5) (1).jpeg>)

1.  **LED de encendido (verde)**

**En**– Alimentado por un adaptador de corriente o batería recargable

**Destello**– Batería recargable con poca energía

1.  **LED de modo (amarillo)**

**En**– El Repetidor está en Modo Aprendizaje (Panel) o Modo Borrar

**Destello**(1 destello cada segundo): el repetidor está en modo de prueba de caminata.

**Parpadeo lento**(1 destello cada 2 segundos) – El Repetidor está en Modo de Aprendizaje (Dispositivo)

1.  **Transmisión: Recibir LED (Azul)**

El LED azul se enciende cuando el repetidor recibe una transmisión de señal

1.  **Transmisión: LED de transmisión (rojo)**

El LED rojo se enciende cuando el repetidor transmite una señal.

1.  **Bloque de interruptores funcionales**
2.  **Botón de prueba**
3.  **Interruptor de batería**
4.  **Funda extraíble**
5.  **Manibela de encendido**
6.  **Orificio de montaje**
7.  **Conector de alimentación CC**
8.  **Soporte de montaje**

-   **Fuente de alimentación**

Se requiere un adaptador de corriente para conectarlo a una toma de corriente de pared. Asegúrese de utilizar únicamente un adaptador con la clasificación de voltaje de CA adecuada para evitar daños a los componentes. Generalmente se utiliza un adaptador de corriente de salida CC de 12 V y 1 A para alimentar el repetidor.

**Aplicación del adaptador de corriente:**

Para conectar el adaptador de corriente:

1.  Localice el adaptador de corriente y conéctelo al conector de alimentación de CC.
2.  Conecte el adaptador de corriente a una toma de corriente de pared.
3.  El repetidor emitirá un pitido largo y el LED verde se iluminará.

**Fallo de CA/Restauración de CA:**

El repetidor enviará una señal de falla de CA al panel de control cuando el adaptador de corriente esté desconectado durante 30 a 60 segundos. Cuando el adaptador de corriente se vuelve a enchufar durante 30 a 60 segundos, el repetidor enviará una señal de restauración de CA al panel de control.

**Batería recargable:**

Además del adaptador, hay una batería recargable dentro del repetidor, que sirve como energía de respaldo en caso de un corte de energía.

Cuando el adaptador de corriente esté enchufado al conector de alimentación de CC, deslice el interruptor de la batería a la posición ON para que el adaptador de corriente suministre energía al repetidor y al mismo tiempo recargue la batería. Se necesitan aproximadamente 72 horas para cargar completamente la batería.

Cuando el adaptador de corriente esté desenchufado, el repetidor funcionará con la batería recargable.

El repetidor puede detectar el voltaje de la batería. Cuando el voltaje de la batería es bajo, el LED verde parpadeará para indicar el estado de la batería baja.

-   **Bloque de interruptores funcionales**

![C:\\Documents and Settings\\C0874.CLIMAX-TECH\\桌面\\done\\to be completed\\manual pictures\\RP-23 switch block.jpg](<.gitbook/assets/1 (2) (1).jpeg>)El bloque de interruptores funcionales determina en qué modo se encuentra el repetidor. Un interruptor en la posición superior indica el (**EN**) Modo. Asimismo, un interruptor en la posición hacia abajo indica el (**APAGADO**) Modo.

|                   | Función                                    | EN                                | APAGADO                  |
| ----------------- | ------------------------------------------ | --------------------------------- | ------------------------ |
| Interruptor DIP 1 | Aprender dispositivo                       | Modo de aprendizaje (Dispositivo) | Modo normal              |
| Interruptor DIP 2 | Prueba de alcance o caminata               | Modo de prueba de caminata        | Modo normal              |
| Interruptor DIP 3 | Restablecimiento de fábrica                | Modo claro                        | Modo normal              |
| Interruptor DIP 4 | Aprenda en el Panel de control             | Modo de aprendizaje (Panel)       | Modo normal              |
| Interruptor DIP 6 | Configuración unidireccional/bidireccional | bidireccional                     | De una sola mano         |
| Interruptor DIP 8 | Función de manipulación                    | Desactivar                        | Modo normal (habilitado) |

Los interruptores DIP 5 y 7 están reservados.

\\<Note>

-   Cambie la configuración del interruptor DIP 1-4 cuando el repetidor esté encendido, porque el cambio para el interruptor DIP 1-4 solo es válido cuando el repetidor está encendido. Por ejemplo, el interruptor DIP 3 se desliza a la posición de encendido cuando el repetidor está apagado. Cuando el repetidor esté encendido, NO ingresará al modo de borrado. Sin embargo, si primero se desliza el interruptor DIP 3 a la posición de apagado y luego se desliza a la posición de encendido cuando el repetidor está encendido, el repetidor ingresará al modo de borrado.
-   Configure la posición del interruptor DIP 6 para dispositivo unidireccional/bidireccional cuando el repetidor esté apagado. Una vez completada la configuración, encienda el repetidor y aprenda o vuelva a aprenderlo en el Panel para que la configuración surta efecto.
-   Para la configuración del interruptor DIP 8, apague el repetidor antes de cambiar la configuración del interruptor DIP. La nueva configuración del Dip Switch 8 entrará en vigor cuando se vuelva a encender el repetidor.
-   **Señal de supervisión**
-   Después de ser programado en el panel de control, el repetidor transmitirá automáticamente señales de supervisión cada 30 a 50 minutos cuando funcione como un dispositivo unidireccional. Si funciona como dispositivo bidireccional, el repetidor transmitirá automáticamente señales de supervisión cada 90 a 120 minutos.
-   Si el Panel de control no ha recibido la señal del Repetidor durante un período de tiempo preestablecido, el Panel de control lo indicará en su pantalla para mostrar que el Repetidor está experimentando un problema de falta de señal.
-   **Configuración unidireccional/bidireccional**
-   El repetidor puede funcionar como dispositivo unidireccional o bidireccional. Cuando se programa como un dispositivo bidireccional, el repetidor puede recibir confirmación del panel de control para garantizar una transmisión exitosa.
-   El repetidor funcionará como**bidireccional**dispositivo cuando el interruptor DIP 6 se desliza hacia la posición**EN**posición. Funcionará como un**Un camino**dispositivo cuando el interruptor DIP 6 se desliza hacia la posición**APAGADO**posición.
-   Configure la posición del interruptor DIP 6 para dispositivo unidireccional/bidireccional cuando el repetidor esté apagado. Una vez completada la configuración, encienda el repetidor y aprenda o vuelva a aprenderlo en el Panel para que la configuración surta efecto.
-   **Aprenda en el Panel de control**

1.  Para programar el repetidor en el panel de control, deslice el interruptor DIP 4 a la posición Encendido en Modo normal. El Repetidor emitirá 1 pitido largo y se encenderá el LED Amarillo.
2.  Coloque el Panel de control en modo de aprendizaje (consulte el manual del Panel de control).
3.  Presione el botón Prueba. El repetidor transmitirá un código de prueba al panel de control cuando el LED rojo se encienda y el repetidor emita 1 pitido.
4.  Si el repetidor recibe una señal de reconocimiento del panel de control dentro de 60 segundos, el aprendizaje es exitoso. El LED azul se iluminará durante 1 segundo mientras el repetidor emite 1 pitido largo.

Si el repetidor no recibe una señal de reconocimiento del panel de control dentro de 60 segundos, el aprendizaje ha fallado y se indica mediante el LED amarillo que parpadea 3 veces. Repita los pasos 3-4 nuevamente.

1.  Deslice el interruptor DIP 4 a la posición de apagado. El repetidor emitirá 1 pitido largo y el LED amarillo se apagará cuando el repetidor regrese al modo normal.

-   **Repetidor de aprendizaje en repetidor**

Si el Repetidor A está aprendiendo en el Repetidor B:

1.  Poner el Repetidor B en modo de aprendizaje: En Modo Normal, deslice el interruptor DIP 1 del Repetidor B a la posición Encendido. El repetidor B emitirá 1 pitido largo y el LED amarillo parpadeará lentamente (1 parpadeo cada 2 segundos).
2.  Presione el botón de prueba en el repetidor A para enviar un código de aprendizaje. El repetidor A emitirá 1 pitido y el LED rojo se encenderá.

Si el Repetidor B recibe el código de aprendizaje del Repetidor A, emitirá 1 pitido largo y el LED azul se iluminará durante 1 segundo para indicar un aprendizaje exitoso.

Si el Repetidor B recibe el código de aprendizaje del Repetidor A y el Repetidor A ya fue aprendido, el Repetidor B emitirá 2 pitidos y el LED azul se iluminará durante 1 segundo.

\\<Note>

-   No realice un aprendizaje cruzado de los repetidores, p. Aprender el Repetidor A en el Repetidor B y aprender el Repetidor B en el Repetidor A.
-   Todos los repetidores deberán aprenderse en el Panel de control.

1.  Cuando se complete el aprendizaje, deslice el interruptor DIP 1 del repetidor B a la posición de apagado. El repetidor B emitirá 1 pitido largo y el LED amarillo se apagará cuando el repetidor B regrese al modo normal.

-   **Dispositivo de aprendizaje en repetidor**

1.  En el modo normal, deslice el interruptor DIP 1 a la posición de encendido. El Repetidor emitirá 1 pitido largo y el LED Amarillo parpadeará lentamente (1 parpadeo cada 2 segundos).
2.  Consulte los manuales de los dispositivos sobre cómo enviar códigos de aprendizaje desde los dispositivos.

**Para la cámara PIR, presione el botón de prueba una vez para enviar un código de aprendizaje al repetidor.**

Si el repetidor recibe un código de aprendizaje de un nuevo dispositivo, emitirá 1 pitido largo y el LED azul se iluminará durante 1 segundo para indicar un aprendizaje exitoso.

Si el Repetidor recibe un código de aprendizaje de un dispositivo ya aprendido en el Repetidor, emitirá 2 pitidos y el LED azul se iluminará durante 1 segundo.

**Se puede programar un máximo de 60 dispositivos (incluidos repetidores) en el repetidor y se admiten hasta 8 cámaras PIR. Si el usuario intenta aprender en un dispositivo número 61, el repetidor emitirá 4 pitidos.**

\\<Note>

-   Si se utilizan varios repetidores, solo reconozca los dispositivos en los repetidores más cercanos a las áreas de operación de los dispositivos.
-   Todos los dispositivos aprendidos en el Repetidor también deben aprenderse en el Panel de Control.

1.  Cuando se complete el aprendizaje, deslice el interruptor DIP 1 a la posición de apagado. El Repetidor emitirá 1 pitido largo, el LED amarillo se apagará cuando el Repetidor regrese al Modo Normal.

-   **Modo de prueba de caminata**

El panel de control aprendido o los dispositivos aprendidos pueden verificar el alcance de su señal con el repetidor si el repetidor ingresa al modo de prueba de caminata.

1.  En el modo normal, deslice el interruptor DIP 2 a la posición de encendido. El Repetidor emitirá 1 pitido largo y el LED Amarillo parpadeará (1 parpadeo cada segundo).
2.  Cuando el Repetidor reciba señales del Panel de Control o de los dispositivos aprendidos, emitirá un pitido largo y el LED azul se iluminará durante 1 segundo. Luego, la señal se retransmite cuando el LED rojo se enciende durante 1 segundo.
3.  Para salir del modo de prueba de caminata, deslice el interruptor DIP 2 a la posición de apagado. El Repetidor emitirá 1 pitido largo y el LED Amarillo se apagará.

-   **Modo claro (restablecimiento de fábrica)**

Borre la memoria previamente programada y restablezca el repetidor a los valores predeterminados de fábrica.

1.  En el modo normal, deslice el interruptor DIP 3 a la posición de encendido. El Repetidor emitirá 1 pitido largo y se encenderá el LED Amarillo.
2.  Mantenga presionado el botón Prueba durante 5 segundos. El repetidor emitirá 1 pitido largo para indicar que todos los dispositivos aprendidos y el panel de control se borraron del repetidor.
3.  Para salir del modo de borrado, deslice el interruptor DIP 3 a la posición de apagado. El Repetidor emitirá 1 pitido largo y el LED Amarillo se apagará.

\\<Note>

-   Siempre que se retira el repetidor del Panel de control, también se debe restablecer a los valores de fábrica para borrar la memoria del Panel de control.
-   **Operación**

Si el Repetidor recibe una señal del Panel de Control (por ejemplo, un comando), la señal se retransmite al dispositivo correspondiente desde el Repetidor. Los LED de transmisión se iluminarán en consecuencia.

Si el Repetidor recibe una señal de un dispositivo (por ejemplo, una señal de alarma), la señal se retransmite al Panel de Control desde el Repetidor. Los LED de transmisión se iluminarán en consecuencia.

-   **Cómo montar el repetidor**

El Repetidor se puede colocar sobre la mesa, montar en la pared o donde se desee. Siga los pasos a continuación para montar el repetidor:

1.  Usando los orificios del soporte de montaje como plantilla, taladre orificios en la superficie de montaje.
2.  Inserte los tacos de pared si los fija en yeso o ladrillo. Atornille el soporte de montaje a la pared.

![](<.gitbook/assets/2 (17).png>)

1.  Enganche el repetidor en el soporte de montaje en pared (con los orificios de montaje del repetidor).

![](<.gitbook/assets/3 (16).png>)

1.  Sostenga el repetidor y empújelo suavemente hacia abajo como se muestra a continuación.

![](<.gitbook/assets/4 (15).png>)

-   **Protección contra manipulación**
-   El interruptor antisabotaje está en posición de funcionamiento normal (sabotaje cerrado) cuando el repetidor está enganchado al soporte de montaje en pared. La infracción de manipulación ocurre cuando se retira el repetidor del gancho donde se libera el interruptor de manipulación (sabotaje abierto).
-   La función de protección contra manipulaciones se puede**desactivado**cuando el interruptor DIP 8 se desliza a la posición ON. Es**activado**cuando el interruptor DIP 8 se desliza a la posición APAGADO. El cambio a la configuración del interruptor DIP 8 será válido cuando se vuelva a encender el repetidor.
-   **Recomendaciones**

Se recomienda encarecidamente mantener una distancia entre cada repetidor y/o Panel de Control Principal para evitar señales cruzadas.

Si un dispositivo en particular está dentro de un rango aceptable para que el Panel de control reciba su señal de transmisión, se recomienda encarecidamente programar el dispositivo en el Panel de control directamente en lugar de hacerlo en el Repetidor.

Al conectar repetidores en cascada para formar un relé de transmisión, se recomienda encarecidamente vincular no más de 2 capas de repetidores.

\\<Note>

-   Para dispositivos que son controlados directamente por el Panel para encender/apagar, p.e. interruptores de alimentación, interruptores de medidor de energía, controladores de válvulas, controles de persianas enrollables o interruptores de entrada y salida, vincule solo una capa de repetidores.
-   Para el teclado, también se recomienda vincular solo una capa de repetidores.

**Múltiples repetidores**

Si se utilizan varios repetidores, siga las pautas a continuación para obtener un rendimiento óptimo:

1.  Al vincular repetidores para formar una repetición de transmisión, se recomienda vincular no más de dos capas de repetidores.

Del siguiente ejemplo (Dispositivo a B, a A, al Panel de control), el Repetidor A, el Repetidor B y el Dispositivo deben aprenderse en el Panel de control.

El dispositivo debe aprenderse en su repetidor más cercano (Repetido B). El repetidor B debe aprenderse en el repetidor A. (No aprenda el repetidor A en el repetidor B).

Ejemplo:

![C:\\Documents and Settings\\C0874.CLIMAX-TECH\\桌面\\done\\to be completed\\manual pictures\\RP coverage device.jpg](<.gitbook/assets/5 (2) (1).jpeg>)

1.  Si un dispositivo está ubicado entre la cobertura de RF de múltiples repetidores y el Panel de Control:

Ejemplo 1:

![C:\\Documents and Settings\\C0874.CLIMAX-TECH\\桌面\\done\\to be completed\\manual pictures\\RP coverage eg1.jpg](<.gitbook/assets/6 (5) (1).jpeg>)

En el diagrama mostrado, el dispositivo está ubicado entre las áreas de cobertura de RF de los Repetidores B y C. Los usuarios pueden elegir programar el dispositivo solo en el Repetidor B, aprender solo en el Repetidor C o aprender en los Repetidores B y C.

Es**recomendado**para programar el dispositivo en el Repetidor B únicamente (y no en el Repetidor C) para reducir el tráfico de señal.

\\<Note>

-   Para el sistema anterior, el Repetidor C también se aprende en el Repetidor A o B o ambos, de modo que las señales del Repetidor C puedan transmitirse al Panel de control a través del Repetidor A o B, o cualquiera de ellos.

Ejemplo 2:

![C:\\Documents and Settings\\C0874.CLIMAX-TECH\\桌面\\done\\to be completed\\manual pictures\\RP coverage eg2.jpg](<.gitbook/assets/7 (4) (1).jpeg>)

En el diagrama mostrado, el dispositivo está ubicado entre las áreas de cobertura de RF de los Repetidores A, B y C. Los usuarios pueden elegir programar el dispositivo solo en el Repetidor A, aprender solo en el Repetidor B, aprender solo en el Repetidor C o aprender en Repetidores. A, B y C.

Es**recomendado** to learn the device into Repeater A only or Repeater B only (and not to Repeater C) to reduce signal traffic.

\\<Note>

-   Para el sistema anterior, el Repetidor C también se aprende en el Repetidor A o B o ambos, de modo que las señales del Repetidor C puedan transmitirse al Panel de control a través del Repetidor A o B, o cualquiera de ellos.

1.  Normalmente, la mayoría de los dispositivos permanecen en la misma área de cobertura de RF. Para excepciones como un controlador remoto, conecte el dispositivo a todos los repetidores (y al panel de control) del sistema.
