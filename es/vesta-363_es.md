# VESTA 363

**Extensor de rango aislado de BUS (ISL-1-BUS)**

**Introducción**

El ISL-1-BUS es un extensor de alcance aislado. Puede ampliar el rango de comunicación y amplificar la señal del sistema de seguridad cableado a largas distancias, al tiempo que protege los dispositivos conectados contra cortocircuitos. El aislador ha separado galvánicamente los terminales de entrada y salida. En caso de que haya un cortocircuito en la salida, todos los dispositivos conectados a la entrada del ISL-1-BUS continuarán funcionando sin interrupción. El ISL-1-BUS también puede aumentar el voltaje hasta 13,5 V para dispositivos BUS conectados a la salida.

**Identificar las piezas**

![](<.gitbook/assets/0 (5).png>)

1.  **Salida de cableado BUS para líneas de entrada**
2.  **Terminal de BUS enchufable para entrada**
3.  **LED para terminal BUS (entrada)**

El LED se enciende cuando el terminal A de salida del BUS está encendido.

1.  **Puente de resistencia terminal para entrada terminal**

![](<.gitbook/assets/1 (5).jpeg>)

Apague el puente quitando o “estacionando” el enlace del puente.

![](<.gitbook/assets/2 (4).jpeg>)

Encienda el puente apoyando el enlace del puente en ambos pines.

1.  **LED para terminal BUS (Salida A)**

El LED se enciende cuando el terminal A de salida del BUS está encendido.

1.  **Puente de resistencia terminal para terminal BUS (Salida A)**

![](<.gitbook/assets/3 (4).jpeg>)Apague el puente quitando o “estacionando” el enlace del puente.

![](<.gitbook/assets/4 (5).jpeg>)

Encienda el puente apoyando el enlace del puente en ambos pines.

1.  **Terminal BUS enchufable para salida A**

El LED se enciende cuando el terminal A de salida del BUS está encendido.

1.  **Salida de cableado BUS para líneas de salida**
2.  **Terminal de BUS enchufable Salida B**
3.  **LED para terminal BUS (Salida B)**

El LED se enciende cuando el terminal B de salida del BUS está encendido.

1

1.  **Puente de resistencia terminal para terminal BUS (Salida B)**

La misma función que el puente de resistencia terminal para la salida terminal A.

_**Tenga en cuenta:**_

-   _**Después de desconectar los terminales, al volver a instalarlos en la placa, asegúrese de instalarlos en la misma orientación para evitar posibles peligros.**_

**Fuente de alimentación**

El ISL-1-BUS está alimentado por el BUS del panel híbrido. Como amplificador, el ISL-1-BUS puede proporcionar alimentación de 13,5 V y 0,5 A en cada uno de sus terminales de salida A y B.

**Conexión de cableado**

Agregar el ISL-1-BUS al sistema BUS existente ampliará el rango del BUS y aumentará la potencia hasta 13,5 V, 0,5 A para cada uno de sus terminales de salida A y B.

Como el terminal de entrada y los dos terminales de salida independientes están separados galvánicamente, el ISL-1-BUS protege los dispositivos conectados contra cortocircuitos aguas abajo.

Al agregar el ISL-1-BUS al sistema BUS, el BUS se dividirá en 3 segmentos de BUS independientes (línea 1 de BUS, línea 2 de BUS y línea 3 de BUS).

-   Como se muestra en el siguiente diagrama, el panel híbrido, como primer dispositivo BUS en**Línea 1 de autobús**está conectado a la entrada ISL-1-BUS, que es el dispositivo más alejado en la línea 1 de BUS. Asegúrese de configurar los puentes de resistencia terminal del panel híbrido y la entrada ISL-1-BUS en ON para que sirvan como resistencia terminal.
-   Los dos terminales de salida individuales de ISL-1-BUS están conectados cada uno a dispositivos BUS separados a través de**Línea 2 de autobús**y**Línea 3 de autobús**. El terminal de salida A es el primer dispositivo en la línea 2 de BUS; El terminal de salida B es el primer dispositivo en la línea BUS 3. Asegúrese de configurar los puentes de resistencia terminal en ON para las dos salidas ISL-1-BUS, así como para los dispositivos BUS más alejados al final de cada línea BUS para que sirvan como resistencia terminal.
-   El número total de dispositivos BUS (denominados “nodos”; el panel híbrido se cuenta como un nodo) en cada línea BUS debe ser de 32 o menos. De lo contrario, pueden producirse anomalías en la señal del BUS. En el siguiente ejemplo, hay un total de 3 líneas de BUS:**Línea 1 de autobús**contiene 2 nodos (Panel híbrido e ISL-1-BUS),**Línea 2 de autobús**contiene 3 nodos (ISL-1-BUS y 2 dispositivos BUS),**Línea 3 de autobús**Tiene 3 nodos (ISL-1-BUS y 2 dispositivos BUS).

![](<.gitbook/assets/5 (2).jpeg>)

_**Tenga en cuenta también:**_

-   _**Como ISL-1-BUS proporciona hasta 0,5 A para cada uno de sus 2 terminales de salida, se recomienda conectar los dispositivos BUS al terminal de salida de ISL-1-BUS uno por uno para garantizar un funcionamiento óptimo del sistema. Intente evitar conectar todos los dispositivos al terminal de salida a la vez.**_
-   _**Dado que el panel de control suministra energía a ISL-1-BUS, la distancia máxima de cableado desde el panel de control a ISL-1-BUS es de 300 pies.**_
-   _**Se recomienda tener sólo un ISL-1-BUS en una única línea de BUS.**_

2
