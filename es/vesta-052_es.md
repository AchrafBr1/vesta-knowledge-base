# VESTA 052

-   POVS-1-ZW
-   Sensor PIR de ocupación/vacancia
-   Introducción

POVS-1-ZW es un sensor de movimiento infrarrojo pasivo Z-Wave. Es capaz de enviar señales inalámbricas al coordinador en la red Z-Wave al detectar movimiento. Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. Los sensores de movimiento infrarrojos pasivos Z-Wave permiten el acceso a la clase "S2 no autenticado" y admiten la inclusión Z-Wave SmartStart así como la inclusión clásica.

-   Identificación de piezas
-   ![Mini-PIR B 2](<.gitbook/assets/0 (12).jpeg>)1. Lente IR con indicador LED

El indicador LED está ubicado en el centro de la lente IR.

El indicador LED se enciende en las siguientes condiciones:

-   Parpadea una vez después de presionar el botón de función:

El PIR entra en modo Inclusión/Exclusión o detecta un movimiento en modo Prueba.

**2. Compartimento de la batería**

El PIR funciona con una batería de litio CR123A de 3 V.

**3. Botón de función**

-   Press the button once within 30 seconds of inserting the battery to enter Inclusion or\\
    Exclusion mode.
-   Presione el botón una vez en funcionamiento normal para enviar un comando de notificación de activación\\
    e ingrese al modo de prueba.
-   Mantenga presionado el botón durante 10 segundos y luego suéltelo para restablecer el PIR de fábrica.

**4. Base magnética**

El PIR se despliega sobre la base magnética durante la instalación. El imán dentro del PIR y la base garantizará que el PIR permanezca unido a la base independientemente de la ubicación y el ángulo del PIR.

-   Características
-   _**Detección de ocupación/vacancia**_

Cuando el PIR detecta un movimiento, transmitirá una señal de activación. Luego, el PIR comienza la cuenta regresiva del temporizador de ocupación/vacancia. La duración del temporizador es ajustable desde**30 segundos**a**60 minutos**y debe ajustarse desde el coordinador/panel de control de la red Z-Wave.

Durante el temporizador, si el PIR detecta un movimiento, el temporizador se reiniciará.

Cuando el temporizador expire sin detección de movimiento, el PIR transmitirá una señal de restauración de detección de movimiento y volverá al funcionamiento normal.

Por favor refiérase a_**Configuración de clase de comando**_para obtener más detalles sobre la configuración.

-   _**Ajuste de sensibilidad**_

La sensibilidad PIR se puede ajustar para cumplir con diferentes requisitos, ya sea como sensor de seguridad o de ocupación/vacancia. Se pueden seleccionar hasta 5 niveles de sensibilidad a través del panel de control/coordinador de red Z-Wave. Siga los pasos a continuación para ajustar la sensibilidad:

1.  Presione el botón de función en el PIR una vez, el PIR se activará.
2.  En 10 segundos, configure la nueva sensibilidad PIR desde el Panel de control (consulte el manual de su Panel de control para obtener más detalles). El panel enviará una señal al PIR para completar la configuración.
3.  Si la configuración de sensibilidad no se completa dentro de este intervalo, reinicie desde el Paso 1.

Por favor refiérase a_**Configuración de clase de comando**_para obtener más detalles sobre la configuración.

-   _Detección de batería y batería baja_

El PIR utiliza una batería de litio CR123A de 3 V como fuente de energía. Se debe retirar el cuerpo principal de la base para acceder al compartimiento de la batería. El compartimiento de la batería tiene una tira que se debe presionar debajo de la batería cuando se inserta la batería. Al retirar la masa, simplemente levante la tira.

El PIR cuenta con la función de detección de batería baja. Cuando el voltaje de la batería es bajo, el PIR transmitirá la señal de batería baja al coordinador en la red Z-Wave.

Si la batería no se cambia después de Batería baja y se agota, el PIR detendrá toda operación.

Al cambiar la batería, después de quitar la batería vieja, presione el botón de función dos veces para descargarla completamente antes de insertar una batería nueva.

-   _**Despertar**_

Esta función utiliza la clase de comando Z-Wave Wake Up. La clase de comando de activación permite que el PIR alimentado por batería notifique al panel de control/puerta de enlace que está despierto y listo para recibir cualquier comando en cola. El período de tiempo del intervalo de despertador se programa automáticamente de acuerdo con la configuración del Panel de control cuando se incluye el PIR. El ajuste recomendado del intervalo de tiempo es de 60 minutos.

-   _**Modo de prueba**_
-   El modo de prueba le permite verificar el rango de detección del PIR.
-   Para ingresar al modo de prueba, presione el botón de función una vez que ingrese al modo de prueba durante 3 minutos.
-   Durante el modo de prueba, puede activar el sensor PIR para verificar su cobertura de detección. Si se activa PIR, el LED parpadeará una vez para indicarlo.
-   _**Agregar dispositivo (inclusión)**_

El dispositivo admite tanto el proceso de inclusión clásico como el proceso de inclusión SmartStart. Este producto se puede incluir y operar en cualquier red Z-Wave con otros dispositivos certificados Z-Wave de otros fabricantes y/u otras aplicaciones. Todos los nodos de la red que no funcionan con baterías actuarán como repetidores independientemente del proveedor para aumentar la confiabilidad de la red.

-   **Inclusión clásica**
-   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de inclusión**(consulte el manual de la puerta de enlace Z-Wave o del panel de control).
-   Inserte la batería y presione el botón una vez dentro de 30 segundos. Consulte el manual de funcionamiento de la puerta de enlace Z-Wave o del panel de control para completar el proceso de adición.
-   Si el dispositivo ya se ha agregado (incluido) en otra puerta de enlace/panel de control Z-Wave, o si el dispositivo no se puede agregar a la puerta de enlace/panel de control Z-Wave actual, intente eliminarlo primero (consulte_**Quitar dispositivo**_).

**Inclusión SmartStart**

![](<.gitbook/assets/1 (19).png>)![](<.gitbook/assets/2 (22).png>)

Los productos habilitados para SmartStart se pueden agregar a una red Z-Wave escaneando el código QR Z-Wave presentado en el producto con un controlador que proporciona la inclusión de SmartStart. No es necesario realizar ninguna otra acción y el producto SmartStart se agregará automáticamente dentro de los 10 minutos posteriores a su encendido en las proximidades de la red. Z-Wave SmartStart utiliza el DSK del dispositivo para mejorar y simplificar el proceso de inclusión.**DSK**es la clave específica del dispositivo que se utiliza para la autenticación. La información DSK se almacena en formato de código QR que se imprime en una etiqueta y se adhiere al exterior del dispositivo, como se muestra en el ejemplo del lado derecho.

-   Escanee el código QR en la base de POVS-1-ZW para obtener**DSK**y transfiera a la puerta de enlace Z-Wave.

**Sólo ejemplo**

-   Encienda POVS-1-ZW, se enviará automáticamente una solicitud de inclusión de SmartStart a la puerta de enlace.
-   La puerta de enlace incluirá automáticamente el dispositivo al reconocerlo haciendo coincidir la solicitud de inclusión con el DSK obtenido.

&lt;NOTA>

-   El DSK del dispositivo se utiliza sólo durante la inclusión.
-   El DSK se puede leer sin que el POVS esté encendido, por lo que es posible preparar la puerta de enlace para incluir el dispositivo antes de instalar y encender el POVS-1-ZW.
-   Si el POVS-1-ZW ya ha sido**incluido**(aprendido) en otra puerta de enlace/panel de control Z-Wave, exclúyalo primero (consulte_**Exclusión**_) antes de intentar**incluir**en el panel de control/puerta de enlace Z-Wave actual. El POVS-1-ZW no enviará una solicitud de inclusión de SmartStart si ya está en un panel de control/puerta de enlace Z-Wave.
-   _**Eliminación del dispositivo (exclusión)**_

El dispositivo debe eliminarse de la red Z-Wave existente antes de agregarlo a otra.

**Modo de exclusión**

-   Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de exclusión**(consulte el manual de la puerta de enlace Z-Wave o del panel de control).
-   Inserte la batería y presione el botón una vez dentro de 30 segundos. El dispositivo se eliminará de la red Z-Wave.

**Restablecimiento de fábrica**

_(Utilice el restablecimiento de fábrica únicamente cuando falte el panel de control/puerta de enlace de la red o no esté operativo)._

-   El restablecimiento de fábrica del dispositivo lo restaurará a la configuración predeterminada de fábrica (es decir, no estará incluido en ninguna red Z-Wave). Utilice este procedimiento únicamente si la puerta de enlace Z-Wave o el panel de control se pierden o no funcionan.
-   Mantenga presionado el botón de función del dispositivo durante 10 segundos para restablecer los valores de fábrica.

&lt;NOTA>

-   Antes de quitar o restablecer los valores de fábrica del POVS-1-ZW, asegúrese de que la información DSK del dispositivo se haya eliminado o no exista en la puerta de enlace. Si elimina o restablece el dispositivo a los valores de fábrica, pero su DSK aún existe en la puerta de enlace, la puerta de enlace incluirá automáticamente el dispositivo nuevamente.
-   _**Prueba de rango**_

Para probar si el dispositivo puede comunicarse con la puerta de enlace Z-Wave o el panel de control:

-   Coloque la puerta de enlace/panel en modo de prueba de alcance (Walk Test).
-   Presione el botón de función en el dispositivo.
-   La puerta de enlace/panel debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual de operación de la puerta de enlace/panel).
-   _**Modo de suspensión Z-Wave**_
-   El PIR entrará en modo de suspensión Z-Wave (para conservar energía) después de despertarse por un corto período de tiempo (~10 segundos). Mientras está en el modo de suspensión Z-Wave, las puertas de enlace o paneles de control Z-Wave no pueden enviar comandos al PIR.
-   Para programar el PIR utilizando el panel de control/puerta de enlace Z-Wave, envíe comandos al PIR dentro del período de activación.
-   Instalación
-   _Altura de montaje y cobertura de detección PIR_
-   El PIR tiene una cobertura de detección de un cono de 120∘ al frente. Cuando se monta a una altura de 1,2 ma 2,1 m y mirando hacia adelante, el PIR tiene un alcance máximo de 10 metros.
-   La dirección del PIR se puede cambiar simplemente girando el PIR en la base. Después de cambiar de dirección, asegúrese de probar la función de detección para confirmar la nueva cobertura de detección.
-   _Asamblea_
-   El PIR se compone de una cubierta frontal y una cubierta trasera. La cubierta trasera debe separarse para la instalación de la batería y la configuración de la red Z-Wave.
-   Para separar la cubierta posterior, sostenga el PIR con ambas manos y gírelo según la imagen a continuación para abrir el PIR.

![Mini-PIR B](<.gitbook/assets/3 (3).jpeg>)

-   _Instalación_
-   El cuerpo principal del PIR tiene un imán interno en la parte inferior y trasera, que une el cuerpo principal a la base del imán PIR cuando se coloca sobre la base. Las ubicaciones de los imanes se identifican mediante la marca circular en la carcasa.
-   La función de detección de movimiento del PIR es direccional. Es más sensible al movimiento lateral y menos sensible al movimiento vertical de arriba a abajo. Utilice la ubicación del imán inferior como referencia para determinar la dirección horizontal y vertical del PIR.
-   La base PIR tiene 2 orificios de montaje que se utilizan para la instalación en superficie con los tornillos y tapones de fijación incluidos. La base también tiene un imán en su interior. Un lado de la base tiene una abertura para marcar el lado frontal de la base. El cuerpo principal debe colocarse en la base con la lente mirando hacia la abertura frontal para garantizar que la base no obstruya la cobertura de detección del PIR.

![](<.gitbook/assets/4 (1).jpeg>)

1.  Utilice los 2 orificios de montaje en la base PIR como plantilla y taladre orificios en la superficie.
2.  Inserte los tacos si lo fija en yeso o ladrillo.
3.  Atornille la base a los tacos de pared.
4.  Coloque el PIR en la base. El imán dentro del PIR y la base garantizará que el PIR permanezca conectado a la base.
5.  Gire el PIR para ajustar la cobertura de detección según la ruta esperada del movimiento del intruso. Asegúrese de que el intruso se mueva a través de la cobertura de detección PIR de lado a lado.

-   _Guía de instalación_
-   **It is recommended to install the PIR in the following locations.**
-   En una posición en la que un intruso normalmente se movería a través del campo de visión del PIR de lado a lado, evite la instalación donde el intruso se mueva a través de la cobertura de detección del PIR de arriba a abajo.
-   Entre 1,9 y 2 m sobre el suelo para un mejor rendimiento mirando hacia adelante.
-   Donde su campo de visión no esté obstruido, p.e. por cortinas, adornos, etc.
-   **Limitaciones**
-   No instale el PIR en un lugar expuesto a la luz solar directa ni cerca de aparatos de calefacción/refrigeración ni de ventilación.
-   No apunte el PIR hacia fuentes de calor como calentadores, radiadores y ventanas.
-   No apunte el PIR a la ventana.
-   Evite obstáculos grandes en el área de detección y evite objetos en movimiento como cortinas.
-   Evite lugares donde la mascota pueda trepar y comprometer su inmunidad, como escaleras.
-   Información de onda Z

**Tipo de dispositivo:**Notificación de sensor de tipo genérico

**Tipo de rol:**Informes de esclavos dormidos (RSS)

**Identificación del fabricante:**0x018E

**Identificación del tipo de producto:**0x0001

**ID del Producto:**0x0104

**Clase de comando admitida:**

| **Clase de comando**                        | **Versión** | **Clase de seguridad requerida**     |
| ------------------------------------------- | ----------- | ------------------------------------ |
| Asociación                                  | 2           | Clase de seguridad más alta otorgada |
| Información del grupo de asociación         | 3           | Clase de seguridad más alta otorgada |
| Restablecimiento del dispositivo localmente | 1           | Clase de seguridad más alta otorgada |
| Metadatos de actualización de firmware      | 5           | Clase de seguridad más alta otorgada |
| Específico de fabricación                   | 2           | Clase de seguridad más alta otorgada |
| Multicanal                                  | 4           | Clase de seguridad más alta otorgada |
| Asociación multicanal                       | 3           | Clase de seguridad más alta otorgada |
| Nivel de potencia                           | 1           | Clase de seguridad más alta otorgada |
| Notificación                                | 8           | Clase de seguridad más alta otorgada |
| Batería                                     | 1           | Clase de seguridad más alta otorgada |
| Despertar                                   | 2           | Clase de seguridad más alta otorgada |
| Configuración                               | 1           | Clase de seguridad más alta otorgada |
| Versión                                     | 3           | Clase de seguridad más alta otorgada |
| Servicio de transporte                      | 2           | Ninguno                              |
| Información sobre Z-Wave Plus               | 2           | Ninguno                              |
| Seguridad 2                                 | 1           | Ninguno                              |
| Supervisión                                 | 1           | Ninguno                              |

**Association Groups :**

| **IDENTIFICACIÓN** | **Nombre**      | **Recuento de nodos** | **Descripción**                                                                                                                                                                                                                                           |
| ------------------ | --------------- | --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1                  | Línea de vida   | 5                     | <p>Admite las siguientes clases de comando:</p><ul><li>Restablecimiento del dispositivo localmente: se activa al restablecer</li><li>Informe de notificación: activado por PIR</li><li>Informe de batería: cuando cambia el nivel de la batería</li></ul> |
| 2                  | Conjunto básico | 5                     | <p>Cuando se activa PIR, el grupo 2 envía 0xFF.</p><p>Cuando se restaura PIR, el grupo 2 envía 0x00.</p>                                                                                                                                                  |

**Configuración de clase de comando:**

| **Número** | **Nombre**                            | **Tamaño** | **Mínimo** | **Máximo** | **Por defecto** | **Descripción**                                                                                                                                                                                                                                                       |
| ---------- | ------------------------------------- | ---------- | ---------- | ---------- | --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1          | Sensibilidad infrarroja               | 1          | 1          | 5          | 4               | <p>Ajuste del nivel de sensibilidad:</p><ul><li>1: el más bajo; 5: el más alto</li><li>Cuando el máximo es mayor que 5, 5 será el valor establecido; cuando el mínimo es menor que 1, 1 será el valor establecido.</li></ul>                                          |
| 2          | Tiempo de restauración de infrarrojos | 1          | 1          | 120        | 1               | <p>La duración del temporizador es ajustable de 30 segundos a 60 minutos:</p><ul><li>1:30 segundos; 120: 60 minutos</li><li>Cuando el máximo es mayor que 120, 120 será el valor establecido; cuando el mínimo es menor que 1, 1 será el valor establecido.</li></ul> |
