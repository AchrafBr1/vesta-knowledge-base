# VESTA 024

**Cámara con sensor de movimiento PIR para exteriores VST-862EX**

VST-862EX es una cámara con sensor de movimiento infrarrojo pasivo (PIR) para exteriores. Es capaz de enviar señales inalámbricas e imágenes capturadas (calidad de imagen de hasta 640 x 480 píxeles) al Panel de control al detectar movimiento.

Con capacidad de iluminación nocturna, carcasa resistente a los rayos UV y resistente al agua según el estándar IP45, el VST-862EX es ideal para patios traseros, céspedes, portones, pasillos y pasillos exteriores.

La cámara PIR para exteriores está diseñada para brindar un rango de detección típico de 10 metros cuando se monta a 2 metros sobre el suelo. Proporciona inmunidad a mascotas de hasta 60 kilos con dos niveles de sensibilidad seleccionables para adaptarse a diferentes entornos.

VST-862EX también es compatible con el repetidor RP-29/enrutador RMB-29 de Climax, que puede ampliar aún más el rango de comunicación RF a áreas de difícil acceso.

**La serie VST-862EX incluye los siguientes modelos**:

VST-862EX – Cámara con sensor de movimiento PIR y flash LED

VST-862EX-IL – Cámara con sensor de movimiento PIR y LED infrarrojo

-   _**Identificar las piezas**_

![](<.gitbook/assets/0 (27).jpeg>)

**Vista frontal****Vista interior**

![](<.gitbook/assets/1 (22).jpeg>)

1.  **LED de destello/LED infrarrojo**

El LED de flash (para VST-862EX) o el LED de infrarrojos (para VST-862EX-IL) proporciona suficiente luz para capturar imágenes en condiciones de poca iluminación.

1.  **Indicador LED (rojo)**

El indicador LED se utiliza para indicar el estado del sistema.

1.  **Sensor de infrarrojos**

El sensor está destinado a detectar objetos en movimiento.

1.  **Lente de cámara PIR**
2.  **Botón Probar\\y Aprender**

\-Mantenga presionado el botón durante 3 segundos para enviar un código de aprendizaje y luego suelte el botón cuando se encienda el LED rojo.

\-Presione el botón una vez para ingresar al modo de prueba durante 10 minutos.

\-Press the button once to send a learn code to the repeater/router.

1.  **Sabotaje interno**
2.  **Bloque de interruptores DIP**

Hay 8 interruptores DIP para configurar los niveles de sensibilidad de detección y función.

-   1.  **Battery Compartment**
    2.  **Soporte de montaje**
-   _**Indicador LED**_

Cuando esté habilitado, el indicador LED se iluminará en las siguientes condiciones:

-   Cuando se activa el interruptor de manipulación, el LED parpadeará 6 veces para indicar que está transmitiendo "**Manosear**”señal.

1

-   Cuando la cámara PIR está en condiciones de falla (sabotaje abierto o condición de batería baja persiste), cada vez que transmite un movimiento detectado, el LED parpadeará 6 veces.
-   Después de presionar el botón de prueba una vez para ingresar al modo de prueba, el LED parpadeará durante 60 segundos para indicar que la cámara con sensor de movimiento PIR se está calentando.
-   En el modo de prueba, el LED se encenderá durante 2 segundos cada vez que se detecte un movimiento.

_\\<NOTE>_

-   -   El indicador LED se puede habilitar configurando el interruptor DIP2 en la posición ON. Por favor refiérase a**Tabla de posiciones del interruptor DIP**para detalles.
-   _**Captura de imagen**_

Cuando el sistema de alarma está armado, la cámara PIR capturará 1, 3 o 6 imágenes de alarma en resoluciones de 640 x 480 o 320 x 240 (programables desde el panel de control) al detectar movimiento. También puede solicitar manualmente a la cámara PIR que tome una fotografía a través del Panel de control. Las imágenes capturadas se transferirán al Panel de control para la verificación visual de la alarma.

_\\<NOTE>_

-   -   Si su cámara PIR está instalada en una ubicación donde el campo de visión de la cámara es un entorno complejo con luz intensa o muchos colores, las imágenes capturadas tendrán un gran tamaño de archivo, lo que posiblemente provocará un truncamiento cuando las imágenes se transmitan al Panel de control. .
-   _**Período de calentamiento**_

La cámara PIR se calentará durante 60 segundos en las siguientes condiciones:

-   Cuando el sistema del panel de control enciende la cámara PIR al ingresar al modo armado o al ingresar al modo armado con condiciones de falla.
-   Cuando se presiona el botón de prueba una vez para ingresar al modo de prueba.

El LED rojo parpadeará lentamente durante el período de calentamiento. Durante el período de calentamiento de 60 segundos, la cámara PIR no se activará.

-   _**Modo de prueba**_
    -   La cámara PIR se puede poner en modo de prueba durante 10 minutos presionando el botón de prueba una vez. En el modo de prueba, las funciones de temporizador de apagado y captura de imágenes están desactivadas. El indicador LED está habilitado para iluminarse durante dos segundos cada vez que se detecta un movimiento. La cámara PIR saldrá automáticamente del modo de prueba después de 10 minutos y volverá al modo normal.
    -   Para poner la cámara PIR en modo de prueba constante, ajuste el interruptor DIP 1 a la posición ON (consulte**Tabla de posiciones del interruptor DIP**).
-   _**Señal de supervisión**_
    -   Después de la instalación, la cámara PIR transmitirá automáticamente señales de supervisión periódicamente al panel de control en intervalos aleatorios de 30 a 50 minutos.
    -   Si el panel de control no ha recibido la señal de la cámara PIR durante el período de tiempo preestablecido, el panel de control indicará en su pantalla que la cámara PIR en particular está experimentando un problema de falta de señal.
-   _**Tiempo de dormir**_
    -   La cámara PIR cuenta con un “tiempo de suspensión” automático de aproximadamente un minuto para conservar energía. Después de transmitir un movimiento detectado, la cámara PIR no retransmitirá durante un minuto. Cualquier movimiento adicional detectado dentro de este período de sueño de un minuto extenderá el tiempo de sueño en otro minuto. De esta manera, el movimiento continuo frente a la cámara PIR no agotará excesivamente la batería.
-   _**Función de doble golpe**_
    -   La cámara PIR tiene una función de doble golpe. Si la función de doble golpe está habilitada, la cámara PIR informará una alarma al panel de control solo si se detectan dos movimientos en 10 segundos. Si la función de doble golpe está desactivada, la cámara PIR informará una alarma al panel de control cuando se detecte un movimiento.
-   _**Protección contra manipulación**_
    -   La cámara PIR está protegida por un interruptor de manipulación interno que se comprime cuando la cámara PIR se engancha al soporte de montaje. Cuando se retira la cámara PIR del soporte de montaje, el interruptor de manipulación se activará y la cámara PIR enviará una señal de apertura de manipulación al panel de control para recordarle al usuario esta condición.
-   _**Tabla de posiciones del interruptor DIP**_

La función de cada interruptor DIP se enumera en la siguiente tabla. El interruptor DIP está encendido o apagado. La posición superior indica ENCENDIDO y la posición inferior indica APAGADO.

|   | ADEREZO      |   |         | Posición                 |                              |                                               | Función                                |   |              |              |                                 | ADEREZO   |              |                                         | Nivel de sensibilidad                                 |   |   |         |   |   |
| - | ------------ | - | ------- | ------------------------ | ---------------------------- | --------------------------------------------- | -------------------------------------- | - | ------------ | ------------ | ------------------------------- | --------- | ------------ | --------------------------------------- | ----------------------------------------------------- | - | - | ------- | - | - |
|   |              |   |         |                          |                              |                                               |                                        |   |              |              |                                 |           |              |                                         |                                                       |   |   |         |   |   |
|   | Interruptor1 |   |         | EN                       |                              | Modo de prueba                                |                                        |   |              | interruptor5 |                                 |           | interruptor6 |                                         |                                                       |   |   |         |   |   |
|   |              |   | APAGADO |                          | Modo normal (predeterminado) |                                               |                                        |   | EN           |              |                                 | EN        |              | Bajo; Mascota de 60 kg (predeterminado) | EN                                                    |   |   |         |   |   |
|   |              |   |         |                          |                              |                                               |                                        |   |              |              |                                 |           |              |                                         |                                                       |   |   |         |   |   |
|   |              |   |         | EN                       |                              | Activación del indicador LED (predeterminado) |                                        |   | EN           |              |                                 | APAGADO   |              | Alto; mascota de 35 kilos               |                                                       |   |   |         |   |   |
|   | interruptor2 |   |         |                          |                              |                                               | APAGADO                                |   |              | EN           |                                 | Reservado |              |                                         |                                                       |   |   |         |   |   |
|   |              |   |         |                          |                              |                                               |                                        |   |              |              |                                 |           |              |                                         |                                                       |   |   |         |   |   |
|   |              |   |         | APAGADO                  |                              | Indicador LED desactivado                     |                                        |   |              | APAGADO      |                                 |           | APAGADO      |                                         | Reservado                                             |   |   |         |   |   |
|   |              |   |         | EN                       |                              | Cámara PIR orientada hacia                    | una pared                              |   |              |              |                                 |           |              |                                         |                                                       |   |   | APAGADO |   |   |
|   |              |   |         |                          |                              |                                               | ADEREZO                                |   |              | Posición     |                                 |           | Función      |                                         |                                                       |   |   |         |   |   |
|   |              |   |         |                          |                              |                                               | Cámara PIR frente a un espacio abierto |   |              |              |                                 |           |              |                                         |                                                       |   |   |         |   |   |
|   | interruptor3 |   |         |                          |                              |                                               |                                        |   | interruptor7 |              |                                 | EN        |              | Habilitar doble golpe (predeterminado)  |                                                       |   |   |         |   |   |
|   |              |   | APAGADO |                          | espacio (sin pared dentro    | 10 metros)                                    |                                        |   |              |              |                                 |           |              |                                         |                                                       |   |   |         |   |   |
|   |              |   |         |                          |                              |                                               |                                        |   | APAGADO      |              | Deshabilitar doble golpe        |           |              |                                         |                                                       |   |   |         |   |   |
|   |              |   |         |                          |                              |                                               | (por defecto)                          |   |              |              |                                 |           |              |                                         |                                                       |   |   |         |   |   |
|   |              |   |         |                          |                              |                                               |                                        |   |              |              |                                 |           | EN           |                                         | Habilitación de inmunidad a mascotas (predeterminado) |   |   |         |   |   |
|   |              |   |         | EN                       |                              | Cámara PIR orientada hacia                    | un césped                              |   |              | interruptor8 |                                 |           |              |                                         |                                                       |   |   |         |   |   |
|   |              |   |         |                          |                              |                                               |                                        |   | APAGADO      |              | Desactivación inmune a mascotas |           |              |                                         |                                                       |   |   |         |   |   |
|   |              |   |         |                          | (por defecto)                |                                               |                                        |   |              |              |                                 |           |              |                                         |                                                       |   |   |         |   |   |
|   |              |   |         |                          |                              |                                               |                                        |   |              |              |                                 |           |              |                                         |                                                       |   |   |         |   |   |
|   | interruptor4 |   |         |                          |                              |                                               |                                        |   |              |              |                                 |           |              |                                         |                                                       |   |   |         |   |   |
|   |              |   | APAGADO |                          | Cámara PIR frente a un       |                                               |                                        |   |              |              |                                 |           |              |                                         |                                                       |   |   |         |   |   |
|   |              |   |         |                          |                              |                                               |                                        |   |              |              |                                 |           |              |                                         |                                                       |   |   |         |   |   |
|   |              |   |         | suelo de hormigón/piedra |                              |                                               |                                        |   | 2            |              |                                 |           |              |                                         |                                                       |   |   |         |   |   |
|   |              |   |         |                          |                              |                                               |                                        |   |              |              |                                 |           |              |                                         |                                                       |   |   |         |   |   |

![](<.gitbook/assets/2 (37).png>)

_**\\<NOTE>**_

 Después de cambiar la configuración del interruptor DIP, vuelva a encender la cámara PIR para que funcione con las nuevas configuraciones del interruptor DIP.

-   _**Batería**_
-   La cámara PIR utiliza cuatro baterías de litio AAL91 como fuente de energía.
-   La cámara PIR cuenta con detección de voltaje de batería baja. Cuando se detecta batería baja, se enviará una señal de batería baja al Panel de control junto con transmisiones de señal regulares para que el Panel de control muestre el estado correspondiente.
-   **Para cambiar las baterías:**

**Paso 1:**Retire la cámara PIR de la posición de montaje y afloje el tornillo de fijación de la cubierta posterior.

**Paso 2:**Inserte un destornillador de punta plana en el área hundida de la cubierta posterior y luego levante con cuidado la cubierta posterior.

![](<.gitbook/assets/3 (34).png>)

**Paso 3:**Retire las baterías viejas y presione el botón de prueba dos veces para descargarlas por completo.

**Etapa 4:**Inserte cuatro baterías de litio AAL91 nuevas.

**Paso 5:**Presione el botón de prueba una vez. Se enviará una señal de batería normal al panel de control.

**Paso 6:**Vuelva a atornillar la cubierta trasera.

**Paso 7:**Vuelva a montar la cámara PIR en la ubicación de montaje.

-   _**Primeros pasos: aprender a utilizar la cámara PIR en el panel de control**_
    -   Afloje el tornillo de fijación inferior y luego inserte un destornillador de punta plana para levantar la cubierta posterior.
    -   Según sus necesidades, configure el interruptor de sensibilidad como se muestra en_Tabla de posiciones del interruptor DIP_.
    -   Inserte cuatro baterías de litio AAL91 en el portapilas teniendo cuidado de conectar la polaridad correctamente.
    -   Coloque el Panel de control en modo de aprendizaje; consulte el manual del Panel de control para obtener más detalles.
    -   Mantenga presionado el botón de prueba durante 3 segundos para enviar un código de aprendizaje y luego suelte el botón cuando se encienda el LED rojo. El LED estará encendido durante 20 segundos, indicando que la cámara PIR está en modo de aprendizaje.
    -   Si el panel de control recibe la señal de la cámara PIR, mostrará la información correspondiente. Dentro de los 20 segundos cuando el LED de la cámara PIR esté encendido, seleccione la cámara PIR en la página web del Panel de control y haga clic en**"agregar"**incluirlo en el Panel. Consulte el manual del Panel de control para obtener más detalles.
    -   Cuando la cámara PIR reciba confirmación del panel de control, el LED de la cámara PIR parpadeará 6 veces y luego se apagará para indicar un aprendizaje exitoso.
    -   Una vez memorizada la cámara PIR, coloque el panel de control en modo de prueba de caminata. Sostenga la cámara PIR en la ubicación deseada y presione el botón Probar para confirmar que esta ubicación está dentro del alcance de la señal del panel de control.
    -   Cuando esté satisfecho de que la cámara PIR funciona en la ubicación elegida, puede continuar con la instalación.

_\\<NOTE>_









Después de mantener presionado el botón de prueba durante 3 segundos, el LED de la cámara PIR se encenderá durante 20 segundos. Si la cámara PIR no recibe confirmación del panel de control dentro de este período de 20 segundos, el LED se apagará. Es necesario presionar y mantener presionado el botón Prueba durante 3 segundos nuevamente para reenviar un código de aprendizaje.

Si la cámara PIR ya existe en un sistema de Panel de control, primero deberá eliminar la cámara PIR del Panel de control antes de poder acceder a ella en un Panel de control diferente.

**Prueba de caminata**Se debe realizar una prueba para confirmar el funcionamiento y la cobertura adecuados del PIR.

![](<.gitbook/assets/4 (19).jpeg>)

Al aprender la cámara PIR en un repetidor/enrutador, presione el botón Prueba una vez (en lugar de presionarlo y mantenerlo presionado durante 3 segundos) para enviar un código de aprendizaje.

-   _**Editar área de operación de la cámara PIR**_

Siga las instrucciones a continuación para cambiar el área de la cámara PIR en el panel de control

1.  Utilice la función Editar dispositivo del panel para cambiar la configuración del área de la cámara PIR.
2.  Mantenga presionado el botón de prueba durante 3 segundos en la cámara PIR para enviar una señal al panel y luego suelte el botón cuando el LED se encienda.

3

-   _**Método de montaje e instalación**_
    -   **Montaje con soporte de montaje:**
        -   La cámara PIR se puede montar en una superficie plana o en una esquina con tornillos de fijación, tapones y el soporte de montaje proporcionado.
        -   La placa de montaje proporcionada tiene orificios ciegos, donde el plástico es más delgado y se puede romper para realizar el montaje. Dos orificios ciegos son para fijación en superficie y cuatro orificios ciegos para fijación en esquina, como se muestra en la imagen.
        -   Para montar VST-862EX con soporte de montaje:
            1.  Utilice el soporte de montaje como plantilla para perforar agujeros en la pared para los enchufes.
            2.  Introduzca los tacos y fije el soporte de montaje en la pared con los tornillos.
            3.  Monte el VST-862EX con los ganchos del soporte de montaje asegurados en la cubierta posterior del VST-862EX y luego empuje hacia abajo hasta que escuche un clic.

_\\<NOTE>_

-   Please make sure the PIR Camera is properly hooked onto the mounting bracket, so that the internal tamper switch is fully compressed.

![](<.gitbook/assets/5 (27).png>)

-   Evite montar la cámara PIR en superficies irregulares. Si aún es necesario el montaje en una esquina sobre superficies irregulares, puede colocar los 4 espaciadores de espuma adhesiva en la parte posterior del soporte de montaje para aliviar el estrés.

![](<.gitbook/assets/6 (18).png>)

-   **Montaje con soporte de montaje y soporte giratorio:**

Se proporciona un soporte giratorio como opción de montaje fácil de usar.**(artículo opcional, se vende por separado)**. Se compone de una base para fijar a la superficie y una bola giratoria para fijar al soporte de montaje y al VST-862EX.

Con el soporte giratorio, la cámara PIR se puede girar horizontalmente para proporcionar una cobertura óptima.

![](<.gitbook/assets/7 (17).jpeg>)

4

Para fijar el soporte giratorio a la pared se suministra un destornillador especial con punta reversible de doble cara y tres tornillos con cabeza de estrella.

![](<.gitbook/assets/8 (16).png>)

Utilice el destornillador proporcionado para apretar o aflojar los tornillos con casquillo de estrella.

![](<.gitbook/assets/9 (17).png>)

-   -   Para montar el VST-862EX con soporte de montaje y soporte giratorio:

1.  Fije el soporte giratorio a la pared con los tornillos suministrados.
2.  Fije el soporte de montaje en la bola giratoria con el tornillo de fijación asegurado a través del orificio de diseño infalible.
3.  Monte el VST-862EX con los ganchos del soporte de montaje asegurados en la cubierta posterior del VST-862EX y luego empuje hacia abajo hasta que escuche un clic.

![](<.gitbook/assets/10 (15).png>)

5

1.  Gire la bola giratoria horizontalmente para ajustar el ángulo de detección del VST-862EX. (Cuando el tornillo de ajuste del ángulo está medio aflojado, la bola giratoria aún se puede girar).

![](<.gitbook/assets/11 (13).jpeg>)

-   1.  Cuando se gira el VST-862EX a una posición con la cobertura de detección deseada, puede bloquear la posición apretando firmemente el tornillo de ajuste del ángulo.
-   _**Recomendaciones de instalación**_

**Se recomienda instalar la cámara PIR en las siguientes ubicaciones:**

-   A una altura de 2 metros (medida desde la parte inferior de la cámara) sobre el nivel del suelo para un mejor rendimiento.
-   En una esquina para la vista más amplia.
-   Donde un intruso normalmente se movería a través del campo de visión de la cámara PIR.
-   Una superficie o rincón donde los animales son inaccesibles.
-   La cámara PIR tiene un rango de detección de 10 m cuando se monta a una altura de 2 metros sobre el suelo.

**Rango de detección VST-862EX**

![](<.gitbook/assets/12 (8).jpeg>)

**Limitaciones:**

-   No exponga la cámara PIR completamente a la luz solar directa.
-   Evite grandes obstáculos en el área de detección.
-   No lo acerque a fuentes de calor como incendios y calderas, ni lo instale encima de radiadores.
-   Nunca intente desmontar o modificar la unidad.
-   Instale la cámara PIR hacia arriba. No lo incline.

![](<.gitbook/assets/13 (7).jpeg>)

6

-   No instale la cámara con sensor de movimiento donde haya objetos movidos por el viento, como árboles y ropa sucia, que puedan bloquear el campo de visión de la cámara con sensor de movimiento.

![](<.gitbook/assets/14 (9).jpeg>)

-   Retire todas las superficies que reflejen la luz del área de detección, así como los charcos de agua.

![](<.gitbook/assets/15 (8).jpeg>)

-   Evite mirar directamente a la ruta del flujo de aire de entrada o salida de la unidad exterior.

![](<.gitbook/assets/16 (8).jpeg>)

_\\<IMPORTANT NOTE>_

-   Ajuste los interruptores DIP según la ubicación de instalación de la cámara PIR para un rendimiento ideal. Si la configuración del interruptor DIP no coincide con el entorno de instalación, el rendimiento de la cámara PIR se verá afectado y puede causar falsas alarmas o incapacidad para detectar movimiento.
-   La cámara PIR detecta diferencias entre el objeto en movimiento y el fondo. Si el objeto está estacionario (es decir, sin moverse), la cámara PIR no puede detectarlo.
-   La cámara PIR tiene una característica direccional y es más efectiva para detectar intrusos que se mueven a través del campo de detección. Es menos sensible para detectar movimiento directamente hacia la cámara PIR.
-   La cámara PIR tiene un punto ciego de aproximadamente 1 metro debajo de la cámara cuando se monta a una altura de 2 metros. El área del punto ciego aumentará si monta la cámara PIR a más de 2 M y se reducirá si monta a menos de 2 M.
-   A menos que sea necesario, sugerimos mantener la cámara PIR a la altura sugerida para un rendimiento óptimo. Si cambia la altura de montaje, realice una prueba de detección para asegurarse de que la cámara PIR pueda detectar intrusos normalmente a la altura deseada.

7
