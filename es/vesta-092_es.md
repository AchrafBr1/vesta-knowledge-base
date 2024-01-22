# VESTA 092

**VRCP-DECT****Extensor de voz**

VRCP-DECT es un extensor de voz que permite a los usuarios solicitar ayuda de emergencia con un comando de reconocimiento de voz o presionando un solo botón. VRCP-DECT tiene reconocimiento de voz incorporado y puede activar una llamada de emergencia al CMS mediante comandos vocales o palabras clave preestablecidas. Es adecuado para atención médica y para personas mayores, casas de varios pisos y locales más grandes.

-   _**Identificando las partes:**_

![](<.gitbook/assets/0 (47).jpeg>)

1.  **Botón de alarma**
    -   -   Presione el botón para obtener ayuda y abrir la comunicación bidireccional.
        -   Mantenga presionado el botón durante 5 segundos durante la comunicación bidireccional para solicitar al panel de control que finalice la comunicación. El Panel de Control finalizará la comunicación o no dependiendo de la configuración del usuario.
2.  **LED rojo**
    -   Encendido: VRCP-DECT no se ha aprendido en el panel de control.
    -   Parpadea cada 5 segundos: Batería baja
    -   3 segundos encendido, 3 segundos apagado: Fallo de CA
    -   Parpadea dos veces: aprendizaje exitoso
3.  **LED verde**
    -   -   Encendido: VRCP-DECT se está aprendiendo en el panel de control. VRCP-DECT está en comunicación bidireccional.
4.  **Vocero**
5.  **Micrófono para VR (Reconocimiento de Voz)**
6.  **Micrófono para comunicación bidireccional.**
7.  **DC Jack**
    -   Conexión del adaptador de corriente DC 9V 1A SPS
8.  **Botón de prueba/aprendizaje**

1

-   -   Mantenga presionado el botón durante 3 segundos hasta que VRCP-DECT emita 1 pitido largo para indicar que ha ingresado al modo de aprendizaje.

1.  **interruptor de batería**
2.  **Interruptores DIP**
3.  **Orificios de montaje**
4.  **Marca de triángulo**
    -   La marca del triángulo debe apuntar hacia arriba cuando el soporte esté fijado en la pared.

-   _**Fuente de alimentación:**_

El extensor de voz puede funcionar con alimentación de CA o con batería.

**Alimentación de CA:**Se proporciona un adaptador de corriente DC 9V 1A SPS para la conexión de alimentación de CA.

-   Cuando se desconecta la alimentación de CA, el LED rojo se encenderá/apagará cada 3 segundos para indicar una falla de CA. DECT se apagará para ahorrar energía de la batería.
-   Después de que se restablezca la alimentación de CA, el LED rojo se apagará para indicar la restauración de la falla de CA. DECT se encenderá nuevamente y se volverá a conectar al Panel de control.

**Batería:**Cuando se desconecta la alimentación de CA, VRCP-DECT cambiará al uso de la batería recargable en el interior.

-   -   Cuando el voltaje de la batería es bajo, VRCP-DECT enviará una señal de batería baja al Panel de control para notificar la situación.
    -   La condición de batería baja se restablecerá 12 horas después de que se suministre alimentación de CA a VRCP-DECT. VRCP-DECT también enviará una señal de restauración de batería baja al panel de control.
    -   Si el interruptor de la batería está en APAGADO, la batería no se cargará cuando esté conectada la alimentación de CA y tampoco servirá como fuente de alimentación de respaldo cuando falte la alimentación de CA. Debe encender la batería para que se cargue cuando esté conectada la alimentación de CA y sirva como fuente de alimentación de respaldo cuando falte la alimentación de CA.
-   _**Señal de supervisión**_
    -   -   Después de la instalación, el VRCP-DECT transmitirá automáticamente la señal de supervisión al panel de control cada 24 horas.
-   _**Sensibilidad del reconocimiento de voz**_
-   La función de reconocimiento de voz tiene tres niveles de sensibilidad: alta, media y baja. Cuando el nivel de sensibilidad se establece en alto, VRCP-DECT detectará más fácilmente la palabra clave/comando y activará la alarma.
-   Utilice una herramienta afilada para ajustar las posiciones del interruptor DIP para establecer el nivel de sensibilidad.

![](<.gitbook/assets/1 (44).png>)

|   |                  | **ADEREZO**      |         |   | **Búsqueda (nivel de sensibilidad)** |   |   |   |
| - | ---------------- | ---------------- | ------- | - | ------------------------------------ | - | - | - |
|   |                  |                  |         |   |                                      |   |   |   |
|   |                  |                  |         |   |                                      |   |   |   |
|   | **Interruptor1** |                  |         |   |                                      |   |   |   |
|   |                  | **interruptor2** |         |   |                                      |   |   |   |
|   |                  |                  |         |   |                                      |   |   |   |
|   | APAGADO          |                  | OFF     |   | Bajo                                 |   |   |   |
|   |                  |                  |         |   |                                      |   |   |   |
|   | EN               |                  | APAGADO |   | Medio                                |   |   |   |
|   |                  |                  |         |   |                                      |   |   |   |
|   | OFF              |                  | EN      |   | Alto                                 |   |   |   |
|   |                  |                  |         |   |                                      |   |   |   |

![](<.gitbook/assets/2 (34).jpeg>)

_**\\<NOTE>**_

-   Después de cambiar la configuración del interruptor DIP, desconecte la fuente de alimentación (se deben quitar tanto la fuente de alimentación externa como las baterías) y luego vuelva a conectar la alimentación a VRCP-DECT. VRCP-DECT funcionará con una nueva configuración de sensibilidad después de volver a encenderlo.

2

-   _**Procedimientos de aprendizaje:**_

Paso 1. Abra la página web del Panel y comience con el modo de aprendizaje. Consulte el manual del Panel de control para obtener más detalles.

Paso 2. Mantenga presionado el botón de aprendizaje de VRCP-DECT durante 3 segundos hasta que escuche un pitido largo y suelte el botón. VRCP-DECT entrará en modo de aprendizaje durante 30 segundos. El LED verde estará encendido durante el modo de aprendizaje.

Paso 3. Cuando el panel de control reciba la señal de VRCP-DECT, mostrará la información correspondiente. Si el dispositivo que desea aprender ya existe en el sistema, la información del dispositivo se mostrará en la sección Dispositivo aprendido. De lo contrario, la información del dispositivo se mostrará en la sección Dispositivo detectado.

Paso 4.VRCP-DECT emitirá dos pitidos para indicar un aprendizaje exitoso al recibir el reconocimiento del Panel de control.

Paso 5. Haga clic en "Agregar" en la página web para incluir el dispositivo seleccionado en el panel.

_**\\<NOTE>**_

-   -   Si VRCP-DECT no recibe confirmación del panel de control durante el modo de aprendizaje de 30 segundos, emitirá un pitido de tono bajo para indicar que el aprendizaje falló y saldrá del modo de aprendizaje. El LED verde se apagará y el LED rojo se encenderá. Realice los pasos de aprendizaje nuevamente.
-   _**Operación:**_

**Informe de emergencia**

-   Cuando presionas el**ALARMA**o pronuncie el comando vocal específico, se enviará un informe de emergencia y se establecerá una comunicación bidireccional de acuerdo con la duración establecida en su Panel de control. El LED verde se iluminará durante la comunicación.
-   Las palabras de activación pueden ser “Alarma SARA (alemán)”, “Ayuda SARA (inglés)” o “Ayúdame (inglés)”, según la versión del firmware. "SARA Alarm (alemán)" debe pronunciarse dos veces en 5 segundos para activar la alarma, mientras que "SARA Help (inglés)" o "Help Me (English)" solo deben pronunciarse una vez para activar la alarma.

**Formas de buscar ayuda**

![](<.gitbook/assets/3 (50).png>)

**o**

-   VRCP-DECT finalizará la llamada cuando expire el tiempo. El LED verde se apagará.
-   Durante la comunicación bidireccional, puede presionar y mantener presionado el botón ALARMA durante 5 segundos para solicitar al Panel de control que finalice la comunicación. El Panel de control finalizará la comunicación bidireccional o no dependiendo de la configuración del usuario.

3

![](<.gitbook/assets/4 (46).png>)

_**\\<NOTE>**_

-   Cuando la opción Devolución de llamada está habilitada en el Panel de control, el LED verde permanecerá encendido después de que se haya finalizado la llamada. El LED verde se apagará cuando finalice el temporizador de devolución de llamada. Consulte el manual del Panel de control para obtener más detalles sobre la función de devolución de llamada.
-   Cuando la función de cancelación VRCP-DECT está habilitada en el panel de control, al presionar el botón en VRCP-DECT finalizará la comunicación bidireccional. Cuando la función de cancelación VRCP-DECT está desactivada, presionar el botón en VRCP-DECT no finalizará la comunicación bidireccional.
-   Para garantizar la precisión del reconocimiento de voz, evite instalar VRCP-DECT en una habitación grande o ruidosa.
-   El entorno ideal para el reconocimiento de voz es el silencio o el silencio parcial. Si pronuncia el comando vocal con voz normal, hable a menos de 2 metros de VRCP-DECT para garantizar que se active la alarma.
-   La función de reconocimiento de voz tiene tres niveles de sensibilidad. Puede probar con ellos y seleccionar el nivel que mejor se adapte a su ubicación de montaje.

**Informe de alarma activado por otros dispositivos**

-   Cuando un dispositivo detectado en el panel de control activa una alarma y se selecciona "808RV" para la función de encendido bidireccional en la página web de ese dispositivo, se iniciará automáticamente una comunicación bidireccional con VRCP-DECT sin presionar ningún botón.

_**\\<NOTE>**_

-   Esta función de contestar llamadas automáticamente y abrir comunicación bidireccional solo está disponible cuando la alimentación de CA está conectada a VRCP-DECT.
-   Si se desconecta la alimentación de CA de VRCP-DECT, DECT se apagará, VRCP-DECT no podrá atender llamadas y, en su lugar, se iniciará la comunicación bidireccional con GX.

![](<.gitbook/assets/5 (45).png>)

4

**Incoming Call**

-   -   Cuando haya una llamada entrante, al presionar el botón ALARMA en VRCP-DECT se contestará la llamada.
-   _**Montaje VRCP-DECT**_

Una vez que VRCP-DECT se haya aprendido correctamente y haya realizado una prueba de recorrido para confirmar que el dispositivo está dentro del alcance de la señal del panel de control, y también esté satisfecho de que el nivel de sensibilidad seleccionado funciona en la ubicación elegida, puede continuar con la instalación. . El VRCP-DECT se puede montar en la pared o desplegar sobre una superficie plana.

**Montaje en pared**

Asegúrese de que VRCP-DECT esté instalado aproximadamente a la altura del pecho, donde se pueda acceder y operar fácilmente el botón.

1.  Rompe los 2 orificios ciegos del soporte de montaje en pared.
2.  Use the 2 holes as a template to mark off the holes’ positions. Make sure that the triangle symbol on the bracket points straight up.
3.  Taladre 2 agujeros y atornille el soporte a la pared.
4.  Conecte un adaptador de corriente DC 9V 1A SPS al conector DC y mantenga el cable bien colocado

![](<.gitbook/assets/6 (31).jpeg>)

1.  Coloque VRCP-DECT en el soporte de montaje. Asegúrese de que la marca impresa en VRCP-DECT esté alineada con la marca superior en el soporte.
2.  Gire VRCP-DECT en el sentido de las agujas del reloj hasta la posición de bloqueo.

![](<.gitbook/assets/7 (27).jpeg>)

**Colocación en superficie**

El VRCP-DECT se puede implementar sobre una superficie plana sin instalarlo en una ubicación fija.

1.  Limpie la parte posterior de VRCP-DECT con desengrasante.
2.  Conecte el adaptador de corriente DC 9V 1A SPS al conector DC y mantenga el cable bien colocado hacia la derecha o hacia la izquierda. (**Foto 1**)
3.  Retire el respaldo de papel de la almohadilla antideslizante y aplíquelo en la parte posterior de VRCP-DECT. (**Imagen 2**)
4.  Coloque VRCP-DECT en la ubicación deseada. (**Imagen 3**)

5

**Foto 1****Picture 2****Imagen 3**

![](<.gitbook/assets/8 (29).png>)

6
