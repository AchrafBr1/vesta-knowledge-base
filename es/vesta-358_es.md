# VESTA 358

**Sensor de movimiento PIR con cable (IR-35-BUS)**

**Introducción**

El PIR detecta firmas infrarrojas para detectar movimientos dentro de un área asignada y envía señales al panel de control a través de BUS para activar la alarma si un intruso cruza su camino de detección.

El PIR está diseñado para ofrecer un rango de detección típico de 12 metros cuando se monta a 2,5 metros sobre el suelo. El sensor PIR también admite la función de inmunidad a mascotas y no detectará mascotas de hasta 25 kg para minimizar la situación de falsas alarmas.

El PIR consta de un diseño de dos partes formado por una cubierta y una base. La cubierta contiene toda la electrónica y la óptica y la base proporciona un medio de fijación.

**Identificación de piezas**

![](<.gitbook/assets/0 (1) (1).jpeg>)

1. **Botón de prueba/indicador LED**
   * Presione el botón de prueba una vez para ingresar al modo de prueba durante 3 minutos.
   * El indicador LED se utiliza para indicar el estado del sistema.
2. **Sensor de infrarrojos**
3. **Interruptor de puente de resistencia terminal**

Cuando el sensor de movimiento PIR está conectado como el dispositivo BUS más lejano en una línea BUS, configure el puente de resistencia terminal del sensor de movimiento PIR y el interruptor de puente del primer dispositivo BUS (generalmente el panel híbrido) en ON para que sirvan como resistencias de terminación. Se mejorará la capacidad de comunicación de la línea BUS conectada.

*
  *
    * Si el puente está APAGADO (el enlace del puente está retirado o "estacionado" en un pin), la capacidad de comunicación está en nivel normal.
      * Si el puente está activado, se mejorará la capacidad de comunicación.

1. **Terminal de autobus**
2. **Interruptor de puente de activación/desactivación de inmunidad a mascotas (JP3)**
   * Cuando está activado, la inmunidad a mascotas está desactivada (valor predeterminado de fábrica).
   * Cuando se establece en APAGADO, la inmunidad a mascotas está habilitada.

![](<.gitbook/assets/1 (2).png>)

**Puente encendido**

![](<.gitbook/assets/2 (2).jpeg>)

Se inserta el enlace del puente, conectando los dos pines.

**Puente apagado**

![](<.gitbook/assets/3 (1).jpeg>)

El enlace del puente se elimina o "**estacionado**”en un alfiler.

**6. Interruptor de puente aumentador de sensibilidad (JP4)**

*
  * Cuando se establece en ON, la sensibilidad de detección del PIR es alta.
  * Cuando se configura en APAGADO, la sensibilidad de detección del PIR está en el nivel normal. (Predeterminado de fábrica)

1. **Manibela de encendido**
2. **Tornillo de fijación inferior**

1

**Características**

![](<.gitbook/assets/4 (2).jpeg>)

* _**Indicador LED**_

En el modo de funcionamiento normal, el indicador LED parpadeará 3 veces en las siguientes situaciones:

* Cuando se abre la cubierta y se activa el interruptor de manipulación.
* Cuando se detecta movimiento si la condición de manipulación persiste.
* Cuando se detecta movimiento en el modo de prueba
* Cuando se presiona el botón de prueba en condiciones de manipulación

El LED no parpadeará si la manipulación del PIR es normal y el PIR no está en modo de prueba.

![](<.gitbook/assets/5 (1).jpeg>)

* _**Protección contra manipulación**_

El PIR está protegido por un interruptor de manipulación que se comprime cuando el PIR está instalado correctamente. Cuando se retira el PIR de la superficie montada o del soporte de montaje, o se abre su cubierta, se activará el interruptor de manipulación y el PIR enviará una señal de apertura de manipulación al panel de control del sistema para recordarle al usuario la condición. Si se detecta movimiento cuando el interruptor de manipulación está abierto, el LED parpadeará 3 veces.

![](<.gitbook/assets/6 (2).jpeg>)

* _**Función de supervisión**_

Después de la instalación, el PIR transmitirá automáticamente señales de supervisión periódicamente al panel de control en intervalos aleatorios de 20 a 30 segundos.

![](<.gitbook/assets/7 (3).png>)

* _**Modo de prueba**_

El PIR se puede poner en modo de prueba presionando el botón de prueba. Cada vez que se presiona el botón de prueba, el PIR transmitirá una señal de prueba al panel de control para probar el alcance de la radio y entrará en el modo de prueba durante 3 minutos. El modo de prueba finalizará después de 3 minutos.

![](<.gitbook/assets/8 (4).png>)

* _**Función de inmunidad a las mascotas**_
  * El sensor PIR admite la función de inmunidad a mascotas y no detectará mascotas de hasta 25 kg para minimizar la situación de falsas alarmas.
  * La función de inmunidad a mascotas se puede habilitar/deshabilitar configurando la posición del interruptor de puente (JP3). Cuando el interruptor de puente (JP3) está en ON, la inmunidad a mascotas está desactivada (valor predeterminado de fábrica). Cuando el interruptor de puente (JP3) está en APAGADO, se habilita la inmunidad a mascotas.
  * La función de inmunidad a mascotas también se puede ajustar mediante configuración remota; consulte la\_**Configuración remota**\_sección siguiente.
* _**Función de aumento de sensibilidad**_
  * Puede utilizar la función de aumento de sensibilidad para aumentar la sensibilidad de detección del PIR.
  * Para aumentar la sensibilidad de detección, configure el interruptor de puente (JP4) en ON. Para mantener una sensibilidad de detección normal, configure el interruptor de puente (JP4) en APAGADO (valor predeterminado de fábrica).
  * La función de sensibilidad también se puede ajustar mediante configuración remota; consulte la\_**Configuración remota**\_sección siguiente.
* _**Configuración remota**_
  * El sensor de movimiento PIR admite la configuración remota de la inmunidad y sensibilidad de las mascotas.
  * Cuando el PIR está encendido, su función de inmunidad a mascotas y su sensibilidad están determinadas por las configuraciones JP3 y JP4. Los usuarios pueden ajustar la configuración de los puentes o cambiar de forma remota la configuración de sensibilidad e inmunidad a las mascotas desde el Panel de control. La configuración remota sobrescribirá la configuración del puente.

**Página web del panel de control**:

*
  *
    1. En la página web local del Panel, vaya a la página Editar dispositivo.
    2. Ingrese la configuración del sensor de movimiento PIR en la sección Configuración del sensor. Haga clic en Aceptar para confirmar.
    3. Consulte la siguiente tabla para obtener detalles de configuración. Por ejemplo, si desea habilitar la inmunidad a mascotas y establecer el nivel de sensibilidad en alto, puede ingresar 03.

![](<.gitbook/assets/9 (4).png>) ![](<.gitbook/assets/10 (4).png>)

| **Configuración de infrarrojos** | **Inmunidad a las mascotas** | **Sensibilidad** |
| -------------------------------- | ---------------------------- | ---------------- |
| 00                               | Desactivar                   | Normal           |
| 01                               | Desactivar                   | Alto             |
| 02                               | Permitir                     | Normal           |
| 03                               | Permitir                     | Alto             |

**Servidor del portal de inicio**:

*
  *
    *
      1. En Home Portal Server, vaya a la página de configuración del dispositivo, haga clic en la fila del dispositivo IR-35 y seleccione "Configuración de IR".
      2. Seleccione la función Inmunidad a mascotas (Activar/Desactivar) y Sensibilidad (Alta/Normal) de las listas desplegables, haga clic en "Enviar" para confirmar la configuración.
* _**Fuente de alimentación**_
  *
    * Cuando el IR-35-BUS está cableado a un panel híbrido, el panel híbrido puede proporcionar una fuente de alimentación de 13,5 V.
* _**Precaución**_
  * El cableado del sensor de movimiento PIR sólo debe realizarlo un técnico certificado con el conocimiento y la formación adecuados en equipos eléctricos.
  * Antes de la instalación o cualquier trabajo de mantenimiento, asegúrese de que la fuente de alimentación esté desconectada.

![](<.gitbook/assets/11 (1).jpeg>) ![](.gitbook/assets/12.jpeg) ![](<.gitbook/assets/13 (4).png>)

2

* ![](<.gitbook/assets/14 (3).png>)_**Cableado del sensor de movimiento PIR**_
  * Antes de conectar el sensor de movimiento PIR al bus del sistema, apague la alimentación.
  * Para ayudar con las conexiones de cables, los bloques de terminales de cada módulo del sistema BUS están codificados por colores.

![](<.gitbook/assets/15 (1).jpeg>)

| **Rojo**     | VDD    |
| ------------ | ------ |
| **Negro**    | Tierra |
| **Amarillo** | 485A   |
| **Verde**    | 485B   |

* Se pueden conectar varios dispositivos BUS en serie al panel híbrido. Para una comunicación óptima de los dispositivos de línea BUS conectados, asegúrese de que los interruptores de puente de resistencia terminal del primer dispositivo (generalmente el panel híbrido) y del último dispositivo BUS en una línea BUS estén configurados en ON para que sirvan como resistencias de terminación. Asegúrese de habilitar solo los 2 interruptores de puente antes mencionados y

no coloque los interruptores de puente en ON para ningún otro dispositivo BUS intermedio.

_\\_

*
  * El diseño enchufable de los bloques de terminales BUS mejora la eficiencia de la instalación. Antes de realizar el cableado, puede retirar los bloques de terminales de la placa PCB para facilitar su uso y enchufarlos nuevamente después del cableado.
  * Después de desconectar el terminal, al volver a instalarlo en la placa, asegúrese de instalar el terminal en la misma dirección para evitar posibles peligros.
* Las conexiones incorrectas provocarán fallas o un funcionamiento incorrecto. Inspeccione el cableado y asegúrese de que las conexiones sean adecuadas antes de aplicar energía.

![](<.gitbook/assets/16 (4).png>)

* _**Primeros pasos: aprendizaje del sensor de movimiento PIR en el panel de control**_

Siga los pasos a continuación para aprender el dispositivo en el panel híbrido.

Paso 1. Conecte el dispositivo al Panel. Luego, encienda el Panel.

Paso 2. En la página web del Panel, haga clic en “**Aprendiendo**”para ingresar a la página de aprendizaje.

Paso 3. Haga clic en "**Comenzar**”para ingresar al modo de aprendizaje.

Paso 4. Haga clic en "**Agregar**”para incluir el dispositivo en el Panel.

Paso 5. Si el dispositivo se reconoce correctamente en el Panel, se mostrará en la sección "Dispositivo aprendido".

![](<.gitbook/assets/17 (1).jpeg>)

* _**Identificación**_

El "**Identificar**La función ”se utiliza para localizar un dispositivo BUS específico en el sistema cableado BUS. Esta función es útil para distinguir qué dispositivo es cuál, especialmente en una instalación grande donde se incluyen numerosos dispositivos BUS.

Para ubicar el sensor de movimiento PIR en el sistema BUS:

\*\*Paso 1.\*\*En la página web del Panel híbrido, haga clic en "Identificar" debajo de la lista de dispositivos después de la entrada de la columna del dispositivo de la cámara IR.

\*\*Paso 2.\*\*Si el sensor de movimiento PIR recibe la señal del panel híbrido, la página web mostrará un mensaje de éxito y el indicador LED del sensor de movimiento PIR parpadeará 10 veces para indicarle al usuario dónde se encuentra.

![](<.gitbook/assets/18 (4).png>)

_\\_

* Si se muestra un mensaje de tiempo de espera en la página web, significa que el sensor de movimiento PIR no recibió la señal del Panel.

Verifique si la conexión por cable entre el panel y el sensor de movimiento PIR está conectada correctamente.

3

* ![](.gitbook/assets/19.jpeg)_**Prueba de caminata**_
  * Para asegurarse de que el sensor de movimiento PIR pueda comunicarse con el panel después de su aprendizaje, coloque el panel de control en modo de prueba de caminata y presione el botón de prueba en IR-35-BUS para transmitir una señal de prueba al panel de control.
  * Cuando el panel reciba la señal de prueba, emitirá un pitido y mostrará la información del sensor de movimiento PIR en consecuencia en la parte superior de la lista de dispositivos.

![](<.gitbook/assets/20 (3).png>)

_\\_

*
  * Si no hay respuesta del Panel después de presionar el botón de prueba, significa que el Panel no recibió la señal de prueba del dispositivo.

Verifique si el IR-35-BUS está conectado correctamente al panel dentro de la distancia de cableado adecuada.

* _**Restablecimiento de fábrica**_

El sensor de movimiento PIR se puede restablecer de fábrica a la inmunidad y sensibilidad predeterminadas para mascotas según las configuraciones JP3 y JP4. Siga los pasos a continuación para continuar.

Paso 1. Desconecte la fuente de alimentación del sensor de movimiento PIR.

Paso 2. Mantenga presionado el botón de prueba del sensor de movimiento PIR y luego encienda el dispositivo. Continúe presionando el botón de prueba durante 5 segundos. Suelte el botón de prueba después de que el LED parpadee 5 veces. El restablecimiento de fábrica está completo.

**Instalación**

* _**Guía de instalación**_
  * El PIR está diseñado para montarse en una superficie plana o en una esquina.
  * El rango de detección es de hasta 12 metros si el PIR se monta entre 2,3 y 2,5 metros por encima del
  * Cuando la función de inmunidad a mascotas está habilitada, el PIR no detectará mascotas de hasta 25 kg cuando se monte a entre 2,3 y 2,5 metros del suelo. Si es necesario, puede ajustar la altura del PIR según el tamaño de su mascota para un rendimiento óptimo de la inmunidad a las mascotas. Una ubicación de instalación más alta proporcionará un mayor espacio inmune a las mascotas, pero aumentará el punto ciego bajo el PIR.
  * Cuando el PIR se monta con el soporte giratorio, no tendrá el área de detección normal (como en el diagrama a continuación) ni el rango inmune típico a las mascotas.
  * Después de seleccionar el sitio de instalación, presione el botón de prueba para ingresar al modo de prueba. Camine por el área protegida observando cuando se enciende el LED y verifique que la cobertura de detección sea la adecuada.
  * Cuando la cobertura de detección sea satisfactoria, siga los pasos descritos en\_**Método de montaje**\_sección siguiente para montar el PIR.

**Rango de detección IR-35-BUS**

4

* _**Método de montaje**_
  * El PIR está diseñado para montarse en una superficie plana o en una esquina.
  * La base tiene dos orificios ciegos, donde el plástico es más delgado y se puede romper para montarlo en la superficie.
  * Un soporte de montaje incluye dos orificios para tornillos centrales para fijar el PIR en una superficie y cuatro orificios para tornillos laterales para fijar el PIR en una esquina.
  * Para montaje en superficie, se proporciona un soporte giratorio opcional para que los usuarios ajusten el rango de detección. Con el soporte giratorio, el IR-35-BUS se puede girar 80 grados horizontalmente y 70 grados verticalmente para proporcionar una cobertura óptima.
* **Montaje en superficie sin soporte de montaje:**
  1. Retire el tornillo de fijación inferior y el conjunto de la cubierta.
  2. Rompe los dos nocauts desde el interior de la base.
  3. Utilice los agujeros como plantilla y taladre agujeros en la superficie a montar.
  4. Inserte los tacos si el PIR se va a fijar sobre yeso o ladrillo.
  5. Atornille la base a los tacos.
  6. Atornille la tapa a la base.
* **Montaje en superficie con el soporte de montaje:**
  1. Utilice los dos orificios centrales para tornillos en el soporte como plantilla y taladre orificios en la superficie a montar.
  2. Inserte los tacos si el PIR se va a fijar sobre yeso o ladrillo.
  3. Atornille el soporte de montaje a los tacos de pared con los dos punteros hacia arriba y hacia usted.
  4. Coloque el PIR en los ganchos del soporte de montaje.

5

* Para montaje en superficie, se proporciona un soporte giratorio opcional para que los usuarios ajusten el rango de detección. Con el soporte giratorio, el IR-35-BUS se puede girar 80 grados horizontalmente y 70 grados verticalmente para proporcionar una cobertura óptima.
* El soporte giratorio se puede montar en la pared con los tornillos suministrados.
  1. Atornille el soporte giratorio a la pared.
  2. Coloque los 3 ganchos del soporte giratorio en los 3 orificios de la base en consecuencia.
  3. Gire el soporte para obtener el rango de detección adecuado y apriete el tornillo de fijación.

**Recomendaciones de instalación**

* **Se recomienda instalar el PIR en las siguientes ubicaciones:**
  * A una altura de 2,3 M-2,5 M para un mejor rendimiento:
  * En lugares donde los animales no puedan llegar al área de detección trepando a muebles u otros objetos.
  * No apunte el sensor hacia escaleras donde los animales puedan subir.
  * En una posición tal que un intruso normalmente se movería a través del campo de visión del PIR de lado a lado.
  * En una esquina para dar la vista más amplia.
  * En una posición donde su campo de visión no quede obstruido por, por ejemplo, cortinas, adornos, etc.
* **Limitaciones**

|  | No instalar al aire libre.                        |  | Evite grandes obstáculos en el área de detección.  |
| - | ------------------------------------------------- | - | -------------------------------------------------- |
|   |                                                   |   |                                                    |
|  | No exponga el PIR completamente a la luz directa. |  | Evite el vapor o la alta humedad que pueden causar |
|   | luz de sol.                                       |   | condensación.                                      |
|   |                                                   |   |                                                    |
|   |                                                   | 6 |                                                    |

|  | Evite objetos en movimiento, por ejemplo, cortinas, paredes |  | Evite la luz reflejada de superficies brillantes, por ejemplo, |
| - | ----------------------------------------------------------- | - | -------------------------------------------------------------- |
|   | tapices, etc., en el área de detección.                     |   | espejos, ventanas, etc.                                        |
|   |                                                             |   |                                                                |
|  | Evite instalar el PIR en áreas donde                        |  | Evite la superficie reflectante en el área de detección.       |
|   | Máquinas como aires acondicionados o calentadores.          |   | Las firmas infrarrojas reflejadas pueden dar lugar a falsas    |
|   | puede causar cambios rápidos de temperatura en el           |   | alarma.                                                        |
|   | zona de detección.                                          |   |                                                                |
|   |                                                             |   |                                                                |

7
