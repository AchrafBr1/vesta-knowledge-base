# VESTA 104

-   Termostato (Serie TMST-15ZW)
-   Introducción

TMST-15ZW es un termostato que funciona con baterías. Está diseñado para incorporarse al sistema de calefacción y refrigeración del hogar para el control del ambiente del hogar. El termostato se puede operar manualmente usando la pantalla LCD y los botones, o se puede acceder de forma remota a través del coordinador Z-Wave. Cuenta con modos de refrigeración y calefacción con punto de ajuste de temperatura y programación automática para que pueda controlar fácilmente el entorno de su hogar.

-   ![](<.gitbook/assets/0 (14).jpeg>)Identificación de piezas

**1. Pantalla LCD**

La pantalla LCD muestra la siguiente información:

![](<.gitbook/assets/1 (21).png>)

1.  Icono de modo de calefacción: cuando se muestra, el termostato está en modo de calefacción.
2.  Icono de modo frío: cuando se muestra, el termostato está en modo frío.
3.  Icono de nivel de batería: solo se muestra cuando el nivel de batería está al 25 %, 50 % y 75 %. El icono desaparecerá cuando el nivel de la batería esté por debajo del 15%.
4.  Conectividad de red Z-Wave:

Cuando se muestra, indica que el termostato aún no se ha aprendido en ninguna puerta de enlace/panel, o cuando el dispositivo pierde la conexión a la red Z-Wave actual.

1.  Modo: selección de modo, modo remoto y compensación
2.  Horario: El termostato ejecutará la configuración del horario programado.
3.  Lectura de temperatura/punto de ajuste

**2. Botón Abajo (-).**

\-Presione el botón y la pantalla LCD mostrará el punto de ajuste actual, el modo y la configuración durante 5 segundos. Dentro de 5 segundos, presione el botón Abajo (-) para disminuir el punto de ajuste.

\-Mantenga presionado durante 3 segundos para ingresar al modo de programación.

**3. Botón arriba (+)**

\-Presione el botón y la pantalla LCD mostrará el punto de ajuste actual, el modo y la configuración durante 5 segundos. Dentro de 5 segundos, presione el botón ARRIBA (+) para aumentar el punto de ajuste.

\-Presione 3 veces en 1,5 segundos para transmitir el código de aprendizaje y se mostrará "Joi NET" en la pantalla LCD.

![](<.gitbook/assets/2 (25).png>)

**4. Orificio de montaje en pared**

**5. Compartimento de la batería**

Inserte 2 pilas alcalinas AA.

**6. Terminales del relé (retire la cubierta del relé para acceder)**

Terminales de relé 230V 5A NO/COM/NC.

Conéctelo al sistema de calefacción/refrigeración del hogar.

**Características**

-   _Detección de batería y batería baja_

El termostato utiliza 2 pilas alcalinas AA como fuente de energía. El sensor informará su porcentaje de batería a la puerta de enlace/panel de control respectivamente al 100 % (0x64), 75 % (0x4B), 50 % (0x32) y 25 % (0x19). Cuando el nivel de la batería está por debajo del 15%, el sensor enviará 0xFF a la puerta de enlace/panel de control.

-   _Control de relé_

El termostato controla el sistema de calefacción/refrigeración del hogar a través del control de relé. Abra y voltee la cubierta trasera, retire la cubierta interna del relé para revelar los terminales para el cableado. Al cablear el termostato, pase el cable a través de la abertura central en la cubierta trasera.

![](<.gitbook/assets/3 (4) (1).jpeg>)

-   _**Control de modo**_

El Termostato tiene dos modos de funcionamiento: Modo Local y Modo Programado.

-   **Modo local:**

El modo local permite ajustar la función Calor/Enfriamiento del termostato y los puntos de ajuste mediante los botones del termostato.

-   **Modo programado:**

El modo programado permite el modo termostato y el control del punto de ajuste a través de la puerta de enlace una vez completado el aprendizaje.

Para cambiar el modo de funcionamiento, consulte “_Modo de programación_”Sección para más detalles.

-   _**Control de calefacción/refrigeración y punto de ajuste**_

El termostato de calefacción/refrigeración y el punto de ajuste solo se pueden ajustar localmente cuando el termostato está configurado en modo local.

Cuando esté en modo local, presione el botón**ARRIBA**(**+**) o**Abajo (-)**Botón para ajustar el punto de ajuste.

Cuando esté en modo programado, use la puerta de enlace/panel de control para ajustar el punto de ajuste de forma remota.

Rango de punto de ajuste de calor: 9°C~30°C.

Rango de punto de ajuste frío: 11°C~32ºC

-   _**Control remoto**_

Después de que el termostato se una a una red Z-Wave, puede controlar el termostato a través del coordinador o puerta de enlace de la red Z-Wave. Consulte el manual de su coordinador/puerta de enlace Z-Wave para obtener más información.

Las siguientes funciones solo están disponibles para configurar a través del coordinador y la puerta de enlace Z-Wave:

-   **Cronograma:**

Solo puede programar la configuración del horario a través del coordinador/puerta de enlace de red Z-Wave.

Configuración de horarios: se pueden programar hasta 5 horarios para cada día de la semana con modo, punto de ajuste y hora de inicio.

Control de Horarios:

Normal: el termostato ejecutará la configuración del horario programado en consecuencia.

Mantener: el termostato omitirá el cronograma actual y realizará el siguiente cronograma cuando comience.

Sin horario: el termostato no ejecutará ningún horario establecido hasta que se establezca nuevamente en Normal.

-   _**Detección de temperatura**_
-   El termostato tiene sensores de temperatura incorporados y mostrará la lectura de temperatura en la pantalla LCD.
-   El termostato transmitirá señales de temperatura periódicamente según la configuración. El intervalo predeterminado de fábrica es de 5 minutos.
-   También puede presionar el botón de red Z-Wave una vez para transmitir una señal de temperatura manualmente.
-   _**Modo de suspensión Z-Wave**_
-   El termostato entrará en el modo de suspensión Z-Wave (para conservar energía) después de despertarse por un corto período de tiempo. Mientras está en el modo de suspensión Z-wave, las puertas de enlace o paneles de control Z-Wave no pueden enviar comandos al termostato
-   _**Modo de programación**_

**Paso 1.**Mantenga presionado el botón Abajo (-) durante 3 segundos para ingresar al modo de programación.

**Paso 2.**Hay 3 funciones disponibles para programación, incluidas funciones de termostato, control de relé remoto y punto de ajuste

Compensar. Puede presionar el botón ARRIBA (+) o Abajo (-) para cambiar de modo.

**Paso 3.**Después de finalizar la selección, espere unos segundos hasta que el termostato ingrese al modo seleccionado.

**Funciones del termostato (calefacción y refrigeración):**

En este modo, se mostrará "Pro Mod" en la pantalla LCD.

![](<.gitbook/assets/4 (22).png>)

Los modos de calefacción/refrigeración están disponibles para su selección. Presione el botón ARRIBA (+) para seleccionar Calefacción y el botón Abajo (-) para seleccionar Refrigeración.

Refrigeración calefacción

![](<.gitbook/assets/5 (15).png>)

Después de finalizar la selección, espere unos segundos hasta que el termostato salga del modo de configuración automáticamente. El termostato ingresará al último modo seleccionado.

**Control del relé remoto:**

En este modo, se mostrará “Pro RM” en la pantalla LCD.

El modo remoto le permite controlar el relé remoto a través del panel de control cuando la función está habilitada. El termostato no controlará el relé local en modo remoto.

![](<.gitbook/assets/6 (10).png>)

-   Si el modo remoto está desactivado, se mostrará "dS RM" en la pantalla LCD.
-   Si el modo remoto está habilitado, se mostrará “En RM” en la pantalla LCD.

![](<.gitbook/assets/7 (7) (1).png>)

**Compensación del punto de ajuste:**

En este modo, se mostrará “Pro OFS” en la pantalla LCD. La función de compensación del punto de ajuste le permite compensar la desviación. Para calcular la compensación del punto de ajuste, simplemente reste la temperatura ambiente a la temperatura del dispositivo. Cuando esté en modo local, presione y mantenga presionado el botón Abajo (-) durante 3 segundos para ingresar al modo de programación. Después de finalizar la selección, espere unos segundos hasta que el termostato ingrese al modo de selección.

![](<.gitbook/assets/8 (7) (1).png>)

Por ejemplo: si la temperatura del dispositivo es de 20 °C y la temperatura ambiente es de 18 °C, entonces la compensación del punto de ajuste = 18 – 20 = -2 °C.

Después de aplicar la compensación del punto de ajuste, el dispositivo funcionará de acuerdo con la temperatura ajustada.

Por ejemplo: si la lectura de temperatura del dispositivo es 20 °C, la compensación del punto de ajuste es -2 °C, el dispositivo funcionará utilizando 18 °C como referencia real.

-   _**Agregar dispositivo (inclusión)**_

Este producto se puede incluir y operar en cualquier red Z-Wave con otros dispositivos certificados Z-Wave de otros fabricantes y/u otras aplicaciones. Todos los nodos de la red que no funcionan con baterías actuarán como repetidores independientemente del proveedor para aumentar la confiabilidad de la red.

-   Cargue dos baterías alcalinas AA en el compartimiento de baterías.
-   Coloque el panel de control Z-Wave en modo de inclusión (consulte el manual del panel de control Z-Wave).
-   En 1,5 segundos, presione el botón Arriba (+) 3 veces para transmitir el código de aprendizaje y se mostrará "Joi NET" en la pantalla LCD. Si el termostato se une exitosamente a una red, el ícono de conexión Z-Wave desaparecerá en la pantalla LCD.
-   Consulte el manual de funcionamiento de la puerta de enlace Z-Wave o del panel de control para completar el proceso de adición.
-   Si el dispositivo ya se ha agregado (incluido) en otra puerta de enlace/panel de control Z-Wave, o si el dispositivo no se puede agregar a la puerta de enlace/panel de control Z-Wave actual, intente eliminarlo primero (consulte Extracción del dispositivo).
-   _**Eliminación del dispositivo (exclusión)**_

El dispositivo debe eliminarse de la red Z-Wave existente antes de agregarlo a otra.

**Modo de exclusión:**

-   Coloque la puerta de enlace Z-Wave o el panel de control en modo de exclusión (consulte el manual de Z-Wave o el panel de control).
-   En 1,5 segundos, presione el botón Arriba (+) 3 veces y el dispositivo se eliminará de la red Z-Wave. Si el termostato se elimina con éxito de la red, aparecerá el icono de conexión Z-Wave en la pantalla LCD.

**Restablecimiento de fábrica**

El restablecimiento de fábrica del dispositivo lo restaurará a la configuración predeterminada de fábrica (es decir, no estará incluido en ninguna red Z-Wave). Utilice este procedimiento únicamente si la puerta de enlace Z-Wave o el panel de control se pierden o no funcionan.

-   Mantenga presionado el botón Arriba (+) del dispositivo durante 10 segundos para restablecer los valores de fábrica.
-   _**Instalación**_

El termostato está diseñado para montarse en la pared utilizando los orificios de montaje de la cubierta posterior.

1.  Antes del montaje, asegúrese de completar primero el cableado del relé a través de la abertura de la cubierta trasera.
2.  Utilice los orificios de montaje de la cubierta posterior como plantilla para marcar la ubicación de montaje en la pared.
3.  Taladre agujeros en la pared e inserte el taco de pared si es necesario, atornille la cubierta posterior en la ubicación de montaje.
4.  Coloque el cuerpo principal del termostato en la cubierta posterior; la instalación estará completa.

**Información de onda Z**

**Tipo de dispositivo:**Termostato

**Tipo de rol:**Informar sobre esclavo durmiente (RSS)

**Soporte/Control de Clase de Comando**

**Soporte CC obligatorio:**Asociación CC, v2

Información del grupo de asociación CC

CC de la batería

Restablecimiento del dispositivo localmente CC

CC específico del fabricante, v2

Versión CC, v2

Nivel de potencia CC

Z-Wave Plus Información CC, v2

Asociación multicanal CC, v2

Despertar CC

CC de supervisión

Modo termostato CC, v3

Punto de ajuste del termostato CC, v3

Estado de funcionamiento del termostato CC

Sensor CC multinivel

Actualización de firmware CC, v2 (solo versión OTA)

_**Grupos Z-Wave (clase de comando de asociación versión 2)**_

Grupo 1 para “LifeLine”:

Batería CC (COMANDO_CLASE_BÁSICO)

Restablecimiento del dispositivo localmente CC

Modo termostato CC, V3

Punto de ajuste del termostato CC, V3

Estado de funcionamiento del termostato CC

Sensor CC multinivel

Grupo 2 para el estado de funcionamiento del termostato:

Estado de funcionamiento del termostato CC
