# VESTA 357

**Cámara con sensor de movimiento PIR para exteriores con cable (VST-892EX-BUS)**

VST-892EX-BUS es una cámara con sensor de movimiento infrarrojo pasivo (PIR) para exteriores con cable. Es capaz de enviar señales por cable e imágenes capturadas (calidad de imagen de hasta 640 x 480 píxeles) a través de BUS al panel de control al detectar movimiento.

Con capacidad de iluminación nocturna, una carcasa resistente a los rayos UV y resistente al agua según el estándar IPX6, el VST-892EX-BUS es ideal para patios traseros, céspedes, portones, pasillos y pasillos exteriores.

La cámara PIR para exteriores está diseñada con un rango de detección típico de 10 metros cuando se monta a una altura de 2,3 metros sobre el suelo. Proporciona inmunidad a las mascotas de hasta 60 kilos con tres niveles de sensibilidad seleccionables para adaptarse a diferentes entornos.

Además, VST-892EX-BUS está diseñado con un detector de proximidad digital. La función antienmascaramiento permite detectar cualquier intento de cegar el detector colocando objetos en su campo de visión.

La configuración remota es compatible con la cámara con sensor de movimiento PIR. Además de ajustar el interruptor DIP, los usuarios también pueden habilitar/deshabilitar la función de doble golpe y la inmunidad a mascotas, y ajustar la sensibilidad de la cámara PIR desde la página web del Panel de control o Home Portal Server.

![](<.gitbook/assets/0 (2).png>)

* _**Identificar las piezas**_

![](<.gitbook/assets/1 (1) (1).jpeg>)

1. **Detector de proximidad digital**

El detector de proximidad digital se utiliza para detectar cualquier intento de enmascaramiento (bloqueo) por parte de un intruso.

1. **Indicador LED (rojo)**

El indicador LED se utiliza para indicar el estado del sistema.

1. **LED intermitente**

El Flash LED proporciona suficiente luz para capturar imágenes en condiciones de poca iluminación.

1. **Sensor de infrarrojos**

El sensor está destinado a detectar objetos en movimiento.

*
  1. **Lente de cámara PIR**

1. **Sabotaje interno**
2. **Botón Probar y aprender**

\-Presione el botón una vez para ingresar al modo de prueba durante 10 minutos.

1. **Bloque de interruptores DIP**

Hay 8 interruptores DIP para configurar los niveles de sensibilidad de detección y función.

1. **Interruptor de puente de resistencia terminal**

Cuando la cámara con sensor de movimiento PIR está conectada como el dispositivo BUS más alejado en una línea BUS, configure el puente de resistencia terminal de la cámara con sensor de movimiento PIR y el interruptor de puente del primer dispositivo BUS (generalmente el panel híbrido) en ON para que sirva como resistencias de terminación. . Se mejorará la capacidad de comunicación de la línea BUS conectada.

![](<.gitbook/assets/2 (1) (1).jpeg>) ![](<.gitbook/assets/3 (3).png>)

**Puente encendido**

![](<.gitbook/assets/4 (1).jpeg>)

Se inserta el enlace del puente, conectando los dos pines.

**Puente apagado**

El enlace del puente se elimina o "**estacionado**”en un alfiler.

*
  * Si el puente está APAGADO, la capacidad de comunicación está en nivel normal.
  * Si el puente está activado, se mejorará la capacidad de comunicación.

1. **Terminal de autobus**

1

1. **Orificio de cableado del autobús**
2. **Soporte de montaje**
3. **Manos**
4. **Orificios de montaje**

![](<.gitbook/assets/5 (3).png>)

* _**Indicador LED**_

Cuando esté habilitado, el indicador LED se iluminará en las siguientes condiciones:

* Cuando la cámara PIR se encuentra en condiciones de falla (sabotaje abierto o condiciones de enmascaramiento continuo), cada vez que transmite un movimiento detectado, el LED parpadeará una vez.
* Después de presionar el botón de prueba una vez para ingresar al modo de prueba, el LED parpadeará durante 60 segundos para indicar que la cámara con sensor de movimiento PIR se está calentando.
* En el modo de prueba, el LED parpadeará una vez cada vez que se detecte un movimiento.

El LED no parpadeará si la cámara PIR está normal y no está en modo de prueba.

![](<.gitbook/assets/6 (1) (1).png>)

_\\_

*
  * El indicador LED se puede habilitar configurando el interruptor DIP 2 en la posición ON. Por favor refiérase a**Tabla de posiciones del interruptor DIP**a continuación para más detalles.
* _**Captura de imagen**_

![](<.gitbook/assets/7 (2).png>)

Cuando el sistema de alarma está armado, la cámara PIR capturará 1, 3 o 6 imágenes de alarma con una resolución de 640 x 480 o 320 x 240 (programable desde el panel de control) al detectar movimiento. También puede solicitar manualmente a la cámara PIR que tome una fotografía a través del Panel de control. Las imágenes capturadas se transferirán al Panel de control para la verificación visual de la alarma.

![](<.gitbook/assets/8 (3).png>)

_\\_

*
  * Si su cámara PIR está instalada en una ubicación donde el campo de visión de la cámara es un entorno complejo con luz intensa o muchos colores, las imágenes capturadas tendrán un gran tamaño de archivo, lo que posiblemente provocará un truncamiento cuando las imágenes se transmitan al Panel de control. .
* _**Período de calentamiento**_

![](<.gitbook/assets/9 (3).png>)

La cámara PIR se calentará durante 60 segundos cuando el panel de control la encienda al ingresar al modo armado.

![](<.gitbook/assets/10 (3).png>)

* _**Modo de prueba**_
  * La cámara PIR se puede poner en modo de prueba durante 10 minutos presionando el botón de prueba una vez.
  * En el modo de prueba, las funciones de captura de imágenes están deshabilitadas. El indicador LED parpadeará una vez cada vez que se detecte un movimiento.
  * La cámara PIR saldrá automáticamente del modo de prueba después de 10 minutos y volverá al modo normal.
  * En el modo de prueba, el indicador LED debe habilitarse configurando el interruptor DIP 2 en la posición ON, y la función de doble golpe debe desactivarse configurando el interruptor DIP 7 en la posición OFF, para que los usuarios prueben el rango de detección.
* _**Función de doble golpe**_
  * La cámara PIR tiene una función de doble golpe. Si la función de doble golpe está habilitada, la cámara PIR informará una alarma al panel de control solo si se detectan dos movimientos en 10 segundos. Si la función de doble golpe está desactivada, la cámara PIR informará una alarma al panel de control cuando se detecte un movimiento.
* _**Tabla de posiciones del interruptor DIP**_

![](<.gitbook/assets/11 (2).png>) ![](<.gitbook/assets/12 (3).png>)

La función de cada interruptor DIP se enumera en la siguiente tabla. El interruptor DIP está encendido o apagado. La posición superior indica ENCENDIDO y la posición inferior indica APAGADO.

![](<.gitbook/assets/13 (3).png>)

Posición de inmersión

Encender

1 APAGADO

Encender

2 APAGADO

Función

Modo de prueba

Modo normal (predeterminado)

Indicador LED habilitado (predeterminado)

Indicador LED desactivado

| ADEREZO   | Nivel de sensibilidad |                                       |         |   |
| --------- | --------------------- | ------------------------------------- | ------- | - |
| Cambiar 5 | Cambiar 6             |                                       |         |   |
| EN        | EN                    | Bajo; mascota de 60 kilos             | EN      |   |
| EN        | APAGADO               | Medio; Mascota de 35 kg (por defecto) |         |   |
| APAGADO   | EN                    | Alto; mascota de 20 kilos             | APAGADO |   |
|           |                       |                                       |         |   |

![](<.gitbook/assets/14 (2).png>)

Cambiar

3

EN

APAGADO

EN

Cámara PIR frente a una pared a menos de 10 m

Cámara PIR orientada hacia un espacio abierto (sin paredes a menos de 10 m) (predeterminado)

Cámara PIR frente a un césped

| APAGADO   | APAGADO       | Reservado                       |   |
| --------- | ------------- | ------------------------------- | - |
| ADEREZO   | Posición      | Función                         |   |
|           | EN            | Detección de doble golpe        |   |
| Cambiar 7 | (por defecto) |                                 |   |
|           |               |                                 |   |
|           | APAGADO       | Detección normal                |   |
| Cambiar 8 | EN            | Inmunidad a mascotas habilitada |   |
|           |               |                                 |   |

Cambiar

4 APAGADO

(por defecto)

Cámara PIR frente a un

suelo de hormigón/piedra

APAGADO Inmunidad a mascotas deshabilitada (predeterminado)

_\\_

* Después de cambiar la configuración del interruptor Dip, vuelva a encender la cámara PIR para aplicar la nueva configuración del interruptor Dip.

![](.gitbook/assets/15.jpeg)

2

* ![](<.gitbook/assets/16 (3).png>)_**Configuración remota**_
  * La cámara con sensor de movimiento PIR admite la configuración remota de la función de doble golpe, la sensibilidad y la inmunidad a las mascotas.
  * Cuando la cámara PIR está encendida, su función de doble golpe está determinada por la configuración DIP SW7, la sensibilidad está determinada por DIP SW5 y SW6, y la inmunidad a mascotas está determinada por DIP SW8. Los usuarios pueden ajustar la configuración del interruptor DIP o cambiar de forma remota la configuración de la función de doble golpe, la sensibilidad y la inmunidad a mascotas en la página web del Panel de control o en el Home Portal Server. La configuración remota sobrescribirá la configuración del interruptor DIP.

**Página web del panel de control**:

*
  *
    1. En la página web local del Panel, vaya a la página Editar dispositivo e ingrese la configuración de la cámara PIR en la sección Configuración del sensor. Haga clic en Aceptar para confirmar.

Consulte la siguiente tabla para obtener detalles de configuración. Por ejemplo, si desea desactivar la función de doble golpe y establecer el nivel de sensibilidad en Bajo, puede ingresar 00.

| **Configuración de infrarrojos** | **doble golpe** | **Sensibilidad**                   | **Inmunidad a las mascotas** |
| -------------------------------- | --------------- | ---------------------------------- | ---------------------------- |
| 00                               | No              | Bajo                               | Sí                           |
| 20                               | No              | Medio                              | Sí                           |
| 40                               | No              | Alto                               | Sí                           |
| 60                               | No              | Pet immunity disabled              | No                           |
| 80                               | Sí              | Bajo                               | Sí                           |
| A0                               | Sí              | Medio                              | Sí                           |
| C0                               | Sí              | Alto                               | Sí                           |
| E0                               | Sí              | Inmunidad a mascotas deshabilitada | No                           |

**Servidor del portal de inicio**:

*
  *
    *
      1. En Home Portal Server, vaya a la página Configuración del dispositivo, haga clic en la fila del dispositivo VST-892EX y seleccione "Configuración IR".
      2. Seleccione la función Doble golpe (Activar/Desactivar), Sensibilidad (Alta/Media/Baja) e Inmunidad a mascotas (Activar/Desactivar) en el menú desplegable y haga clic en "Enviar" para confirmar la configuración.
* _**Señal de supervisión**_
  *
    * Después de la instalación, la cámara PIR transmitirá automáticamente señales de supervisión periódicamente al panel de control en intervalos aleatorios de 20 a 30 segundos.
* _**Protección contra manipulación**_
  *
    * La cámara PIR está protegida por un interruptor de manipulación interno que se comprime cuando la cámara PIR se engancha al soporte de montaje. Cuando se retira la cámara PIR del soporte de montaje, el interruptor de manipulación se activará y la cámara PIR enviará una señal de apertura de manipulación al panel de control para recordarle al usuario esta condición.
* _**Antienmascaramiento**_
  *
    * La cámara PIR tiene un detector de proximidad digital que puede detectar cualquier intento de enmascaramiento (bloqueo) por parte de un intruso.
    * Cuando se detecta un evento de enmascaramiento y la condición de enmascaramiento dura 3 minutos, VST-892EX-BUS enviará una señal de alarma de enmascaramiento al panel de control para notificar al usuario sobre la condición de enmascaramiento.
    * Después de eliminar el enmascaramiento/bloqueo durante 3 minutos, VST-892EX-BUS enviará una señal de restauración al Panel de control.
* _**Fuente de alimentación**_
  *
    * Cuando el VST-892EX-BUS está cableado a un panel híbrido, el panel híbrido puede proporcionar una fuente de alimentación de 13,5 V.
* _**Precaución**_![](.gitbook/assets/17.jpeg)
  * El cableado de la cámara PIR sólo debe ser realizado por técnicos certificados con el conocimiento y la formación adecuados en equipos eléctricos.
  * Antes de la instalación o cualquier trabajo de mantenimiento, asegúrese de que la fuente de alimentación esté desconectada.
* _**Cableado de la cámara PIR exterior**_
  *
    * Antes de conectar la cámara PIR al bus del sistema, apague la alimentación.
    * Para ayudar con las conexiones de cables, los bloques de terminales de cada módulo del sistema BUS están codificados por colores.

![](<.gitbook/assets/18 (3).png>) ![](<.gitbook/assets/19 (3).png>) ![](<.gitbook/assets/20 (2).png>)

| **Rojo**     | VDD    |
| ------------ | ------ |
| **Negro**    | Tierra |
| **Amarillo** | 485A   |
| **Verde**    | 485B   |

* Se pueden conectar varios dispositivos BUS en serie al panel híbrido. Para una comunicación óptima de los dispositivos de línea BUS conectados, asegúrese de que los interruptores de puente de resistencia terminal del primer dispositivo (generalmente el panel híbrido) y del último dispositivo BUS en una línea BUS estén configurados en ON para que sirvan como resistencias de terminación. Asegúrese de habilitar solo los 2 interruptores de puente antes mencionados y no configurar los interruptores de puente en ON para ningún otro dispositivo BUS intermedio.

_\\_

* El diseño enchufable de los bloques de terminales BUS mejora la eficiencia de la instalación. Antes de realizar el cableado, puede retirar los bloques de terminales de la placa PCB para facilitar su uso y enchufarlos nuevamente después del cableado.

3

*
  * Después de desconectar el terminal, al volver a instalarlo en la placa, asegúrese de instalar el terminal en la misma dirección para evitar posibles peligros.
* Las conexiones incorrectas provocarán fallas o un funcionamiento incorrecto. Inspeccione el cableado y asegúrese de que las conexiones sean adecuadas antes de aplicar energía.
* _**Primeros pasos: aprender a utilizar la cámara PIR en el panel de control**_

Siga los pasos a continuación para aprender el dispositivo en el panel híbrido.

Paso 1. Conecte el dispositivo al Panel. Luego, encienda el Panel.

Paso 2. En la página web del Panel, haga clic en “**Aprendiendo**”para ingresar a la página de aprendizaje.

Paso 3. Haga clic en "**Comenzar**”para ingresar al modo de aprendizaje.

Paso 4. Haga clic en "**Agregar**”para incluir el dispositivo en el Panel.

Paso 5. Si el dispositivo se reconoce correctamente en el Panel, se mostrará en la sección "Dispositivo aprendido".

* _**Identificación**_

El "**Identificar**La función ”se utiliza para localizar un dispositivo BUS específico en el sistema cableado BUS. Esta función es útil para distinguir qué dispositivo es cuál, especialmente en una instalación grande donde se incluyen numerosos dispositivos BUS.

Para ubicar la Cámara PIR en el sistema BUS:

\*\*Paso 1.\*\*En la página web del Panel híbrido, haga clic en "Identificar" debajo de la lista de dispositivos después de la entrada de la columna del dispositivo de la cámara IR.

\*\*Paso 2.\*\*Si la cámara PIR recibe la señal del panel híbrido, la página web mostrará un mensaje de éxito y el indicador LED de la cámara PIR parpadeará 10 veces para indicarle al usuario dónde está.

_\\_

*
  *
    * Si se muestra un mensaje de tiempo de espera en la página web, significa que la cámara PIR no recibió la señal del panel.

Verifique si la cámara PIR está conectada correctamente al panel dentro de la distancia de cableado adecuada.

* _**Prueba de caminata**_
  * Para asegurarse de que la cámara PIR pueda comunicarse con el panel después de su aprendizaje, coloque el panel de control en modo de prueba de caminata y presione el botón de prueba en VST-892EX-BUS para transmitir una señal de prueba al panel.
  * Cuando el panel reciba la señal de prueba, emitirá un pitido y mostrará la información de la cámara PIR en consecuencia en la parte superior de la lista de dispositivos.

_\\_

*
  *
    * Si no hay respuesta del Panel después de presionar el botón de prueba, significa que el Panel no recibió la señal de prueba del dispositivo.

Verifique si la cámara PIR está conectada correctamente al panel dentro de la distancia de cableado adecuada.

* _**Método de montaje e instalación**_
  * **Montaje con el soporte de montaje:**
    *
      * La cámara PIR se puede montar sobre una superficie plana con los tornillos de fijación, los tacos de pared y el soporte de montaje proporcionados.
      * El soporte de montaje provisto tiene orificios ciegos, donde el plástico es más delgado y se puede romper para el montaje.

4

objetivo.

* Para montar VST-892EX-BUS con el soporte de montaje:
  1. Utilice el soporte de montaje como plantilla y taladre 2 orificios en la pared para los tacos.
  2. Introduzca los tacos y fije el soporte de montaje en la pared con los tornillos.
  3. Enganche el VST-892EX-BUS en el soporte de montaje y luego**Empuje hacia abajo hasta que escuche un clic.**.

_\\_

* Asegúrese de que la cámara PIR esté correctamente enganchada al soporte de montaje, de modo que el interruptor de manipulación interno esté completamente presionado.
* **Montaje con soporte de montaje y soporte giratorio:**

Se proporciona un soporte giratorio como opción de montaje fácil de usar.**(artículo opcional, se vende por separado)**. Se compone de una base para fijar a una superficie y una bola giratoria para fijar el soporte de montaje al soporte giratorio.

Con el soporte giratorio, la cámara PIR se puede girar horizontalmente para proporcionar una cobertura óptima.

Para fijar el soporte giratorio a la pared se suministra un destornillador especial con punta reversible de doble cara y tres tornillos con cabeza de estrella. Utilice el destornillador proporcionado para apretar/aflojar los tornillos de estrella.

5

*
  * Para montar VST-892EX-BUS con el soporte de montaje y el soporte giratorio:

1. Fije el soporte giratorio a la pared con los tornillos suministrados.
2. Fije el soporte de montaje en la bola giratoria con el tornillo de fijación asegurado a través del orificio de diseño infalible.
3. Enganche el VST-892EX-BUS en el soporte de montaje y luego empuje hacia abajo hasta que escuche un clic.
4. Gire la bola giratoria horizontalmente para ajustar el ángulo de detección del VST-892EX-BUS. (Cuando el tornillo de ajuste del ángulo está medio aflojado, la bola giratoria aún se puede girar).
5. Cuando se gira el VST-892EX-BUS a una posición con la cobertura de detección deseada, puede bloquear la posición apretando firmemente el tornillo de ajuste del ángulo.

* _**Recomendaciones de instalación**_

**Se recomienda instalar la cámara PIR en las siguientes ubicaciones:**

* A una altura de 2,3 metros (medida desde la parte inferior de la cámara) sobre el nivel del suelo para un mejor rendimiento
* En un rincón para la vista más amplia
* En un lugar donde un intruso normalmente cruzaría el campo de visión de la cámara PIR
* En una superficie o en un rincón donde los animales sean inaccesibles
* La cámara PIR tiene un alcance de detección de 10 metros cuando se monta a una altura de 2,3 metros sobre el suelo.

**Rango de detección del 892EX-BUS**

6

**Limitaciones:**

*
  * No exponga la cámara PIR completamente a la luz solar directa.
  * Evite grandes obstáculos en el área de detección.
  * No acerque fuentes de calor como incendios y calderas, directamente ni lo instale encima de los radiadores.
  * Nunca intente desmontar o modificar el dispositivo.
* Instale la cámara PIR hacia arriba. No lo incline.
* No instale la cámara con sensor de movimiento donde el viento mueva objetos, como árboles y ropa sucia, que puedan bloquear el campo de visión de la cámara con sensor de movimiento.

7

_\\_

* Ajuste los interruptores DIP según la ubicación de instalación de la cámara PIR para un rendimiento ideal. Si la configuración del interruptor DIP no coincide con el entorno de instalación, el rendimiento de la cámara PIR se verá afectado y puede causar falsas alarmas o incapacidad para detectar movimiento.
* La cámara PIR detecta diferencias entre el objeto en movimiento y el fondo. Si el objeto está inactivo (es decir, sin moverse), la cámara PIR no puede detectarlo.
* La cámara PIR tiene una característica direccional y es más efectiva para detectar intrusos que se mueven a través de su campo de detección. Es menos sensible para detectar movimientos directamente frente a la cámara PIR.
* Para obtener el mejor rendimiento, recuerde ajustar la altura de montaje de la cámara con sensor de movimiento con respecto a la altura de la mascota más alta de la casa. Los perros más altos requieren que la cámara con sensor de movimiento esté montada más arriba para que sean más amigables con las mascotas.
* La cámara PIR tiene un punto ciego de aproximadamente 1 metro debajo de la cámara cuando se monta a una altura de 2,3 metros. El área del punto ciego aumentará si la cámara PIR se monta a una altura superior a 2,3 metros y se reducirá si se monta a una altura inferior a esta altura.
* A menos que sea necesario, se sugiere mantener la ubicación de montaje de la cámara PIR a una altura de 2,3 metros para un rendimiento óptimo. Si cambia la altura de montaje, realice una prueba de detección para asegurarse de que la cámara PIR normalmente pueda detectar intrusos a la altura elegida.

8
