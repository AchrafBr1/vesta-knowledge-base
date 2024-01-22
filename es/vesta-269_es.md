# VESTA 269

**Pinza amperimétrica (CLMT-1ZW)**

CL-Meter-ZW es una pinza amperimétrica Z-Wave que tiene como objetivo monitorear e informar la cantidad total de uso de electricidad en sus instalaciones conectando la pinza al cable de alimentación.

El medidor de energía es un dispositivo habilitado para Z-Wave y es totalmente compatible con cualquier red habilitada para Z-Wave.

Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. Al aprovechar la red de malla Z-Wave, los comandos se pueden enrutar a su destino a través de productos Z-Wave intermediarios que “escuchan”.

![](<.gitbook/assets/0 (100).jpeg>)

**Identificación de piezas**

**1. LED rojo**

Parpadea una vez:

Cuando la pinza amperimétrica está transmitiendo una señal.

Destella dos veces:

La pinza amperimétrica se ha unido con éxito a una red Z-Wave.

1. **Cable de entrada de CA**
2. **Cable de transformador de corriente (CT2)**
3. **Cable de transformador de corriente (CT1)**
4. **Botón de función**

\-Presione el botón una vez para informar el valor del medidor a la red Z-Wave.

\-Presione el botón 3 veces en 1,5 segundos para transmitir un código de aprendizaje.

\-Mantenga presionado el botón durante 10 segundos para restablecer la pinza amperimétrica a los valores de fábrica.

1. **Reservado**
2. **Orificio de montaje**
3. **Ganchos de montaje**
4. **Soporte de montaje**

**Instalación**

![](<.gitbook/assets/1 (69).png>)

* _**Alambrado**_

![](<.gitbook/assets/2 (76).png>)**ADVERTENCIA**

El cableado del dispositivo sólo debe realizarlo un electricista autorizado. El disyuntor principal de la caja de circuitos debe estar apagado para realizar la instalación.

La especificación del cable del orificio de inserción es AWG18 o Ø 1,02 (mm²).

La especificación de la abrazadera es 60A Ø 10 mm.

Asegúrese de que la alimentación principal de sus instalaciones también esté apagada antes de realizar la instalación. Siga los pasos a continuación:

1. Conecte el cable de entrada de CA a un enchufe cerca de la caja eléctrica para encender la pinza amperimétrica.
2. Open the clamp as indicated by below picture. The clamp should be applied onto an electric cable The arrow direction on the clamp need to point at the correct direction of the electricity current flows (**KL**). Si la flecha apunta en dirección inversa, la lectura mostrará un valor negativo (-), sin embargo, no influirá en las lecturas.

![](<.gitbook/assets/3 (74).png>)

**k**

**l**

1. Siga los esquemas a continuación como ejemplo; Sujete las abrazaderas de los cables de electricidad en el 2 cable de alimentación entrante conectado al disyuntor principal.

![](<.gitbook/assets/4 (79).png>)

* _**Montaje**_

La pinza amperimétrica tiene un soporte de montaje para fines de montaje.

1. Utilice el soporte de montaje como plantilla para marcar los dos orificios en la pared para instalar los tornillos.
2. Atornille el soporte de montaje a la pared según la ubicación marcada. Instale tacos de pared si es necesario.
3. Ubique los ganchos del soporte de montaje y alinee los ganchos con los orificios de montaje de la pinza amperimétrica. Coloque los ganchos en los orificios de montaje como se muestra en la siguiente imagen. La instalación ya está completa.

![](<.gitbook/assets/5 (79).png>)

* _**Agregar dispositivo (inclusión)**_

Este producto se puede incluir y operar en cualquier red Z-Wave con otros dispositivos certificados Z-Wave de otros fabricantes y/u otras aplicaciones. Todos los nodos de la red que no funcionan con baterías actuarán como repetidores independientemente del proveedor para aumentar la confiabilidad de la red.

*
  * Conecte el cable de entrada de CA al enchufe para encender la pinza amperimétrica.
  * Coloque el panel de control Z-Wave en**Modo de inclusión**(consulte el manual del panel de control Z-Wave).
  * En 1,5 segundos, presione el botón de función 3 veces.
  * Consulte el manual de funcionamiento de Z-Wave Gateway o Panel de control para completar el proceso de adición.
  * Si el dispositivo ya se ha agregado (incluido) en otra puerta de enlace/panel de control Z-Wave, o si el dispositivo no se puede agregar a la puerta de enlace/panel de control Z-Wave actual, intente eliminarlo primero (consulte\_**Quitar dispositivo**\_).
* _**Eliminación del dispositivo (exclusión)**_

![](<.gitbook/assets/6 (59).png>)

El dispositivo debe eliminarse de la red Z-Wave existente antes de agregarlo a otra.**Modo de exclusión**

* Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de exclusión**(consulte el manual del Z-Wave o del panel de control).
* En 1,5 segundos, presione el botón de función 3 veces y el dispositivo se eliminará de la red Z-Wave.

**Restablecimiento de fábrica**

El restablecimiento de fábrica del dispositivo lo restaurará a la configuración predeterminada de fábrica (es decir, no estará incluido en ninguna red Z-Wave). Utilice este procedimiento únicamente si la puerta de enlace Z-Wave o el panel de control se pierden o no funcionan.

*
  * Mantenga presionado el botón de función del dispositivo durante 10 segundos para restablecer los valores de fábrica.
* _**Prueba de rango**_

![](<.gitbook/assets/7 (54).png>)

Para probar si el dispositivo puede comunicarse con Z-Wave Gateway o Panel de control:

*
  * Coloque la puerta de enlace/panel de control en modo de prueba de alcance (Prueba de caminata).
  * Presione el botón de función en el dispositivo.
  * La puerta de enlace/panel de control debería mostrar si el dispositivo está dentro del rango de funcionamiento (consulte el manual de funcionamiento de la puerta de enlace/panel de control).
* _**Monitor de consumo de energía**_
  *
    * La pinza amperimétrica transmitirá una señal desde la propia pinza con sus datos de consumo de energía cada 10 minutos al coordinador de red Z-Wave.
      * La lectura de la abrazadera del cable del transformador de corriente CT-1 se informa al canal 1 del medidor
      * La lectura de la abrazadera del cable del transformador de corriente CT-2 se informa al canal 2 del medidor.
    * Siempre que la salida de energía de la pinza cambie en +/- 2 W, la pinza amperimétrica transmitirá automáticamente una señal con datos de consumo de energía al coordinador de red Z-Wave para su actualización.
    * La pinza amperimétrica transmite una señal con datos de potencia al coordinador cada vez que el uso de energía acumulada de la pinza aumenta en 0,1 kW/h.
    * La abrazadera tiene una precisión de +/- 5%.
    * Para borrar la pinza de sus datos de consumo de energía acumulado, siga los pasos a continuación:

![](<.gitbook/assets/8 (54).png>)

1. Desenchufe el cable de CA para apagar la pinza amperimétrica.
2. Mantenga presionado el botón de función, mientras mantiene presionado el botón, encienda la pinza amperimétrica volviendo a enchufar el cable de CA.
3. Suelte el botón de función cuando el LED rojo comience a parpadear rápidamente.
4. Desenchufe y vuelva a enchufar el cable de CA; la limpieza estará completa.

* ![](<.gitbook/assets/9 (50).png>)_**Carga máxima de operación**_
  * 110V: 6600W y 60A
  * 230V: 13800W y 60A.

**Información de onda Z**

\*\*Tipo de dispositivo:\*\*Medidor para todo el hogar: sencillo

\*\*Tipo de rol:\*\*Siempre en esclavo (AOS)

Soporte/Control de Clase de Comando

Soporte CC obligatorio: Asociación CC, v2

Información del grupo de asociación CC

Restablecimiento del dispositivo localmente CC

CC específico del fabricante, v2

Asociación multicanal CC, V3

CC multicanal, V4

Medidor CC, V2

CRC 16 ENCAP

Versión CC, v2

Z-Wave Plus Información CC, v2

nivel de potencia CC,

Actualización de firmware CC, v2

![](<.gitbook/assets/10 (52).png>)

* _**Grupos de Z-Wave (clase de comando de asociación versión 2)**_

El medidor se puede configurar para enviar informes a dispositivos Z-Wave asociados. Admite 3 grupos de asociación y cada grupo tiene un nodo compatible. Grupo 1\~MEDIDOR de soporte grupo 3\_INFORME\_DOMINIO\_Clase

Grupo 1 para “LifeLine”: (nodo máximo: 1)

Restablecimiento del dispositivo localmente CC, V2

Medidor CC, V2

Para el grupo 1, la pinza amperimétrica informará:

1. La suma del consumo de energía instantáneo (vatios) leído de CT1 y CT2
2. La suma del consumo de energía acumulado (KWh) leído de CT1 y CT2 Grupo 2 para el “medidor CT1” (nodo máximo: 1)

Medidor CC, V2

Para el grupo 2, el Switch informará:

1. Consumo de energía instantáneo (vatios) leído desde CT1
2. Consumo de energía acumulado (KWh) leído desde CT1 Grupo 3 para “medidor CT2”: (nodo máximo: 1)

Medidor CC, V2

Para el grupo 3, el Switch informará

*
  1. La suma del consumo de energía instantáneo (vatios) leído desde CT2
  2. La suma del consumo de energía acumulado (KWh) leído desde CT2
* _**Asociación multicanal de Z-Wave**_

![](<.gitbook/assets/11 (42).png>)

La clase de comando de asociación multicanal se utiliza para crear enlaces de aplicaciones a recursos de punto final multicanal, así como a dispositivos raíz. La clase de comando puede manejar nodos con y sin puntos finales.

Para Root, admite un máximo de 1 nodo y un máximo de 3 grupos de asociación.

| Raíz    | Perfil 2 bytes             | Clase de comando                              | Nombre del grupo                   |
| ------- | -------------------------- | --------------------------------------------- | ---------------------------------- |
|         |                            |                                               | (UTF-8)                            |
| Grupo 1 | General: línea de vida     | Restablecimiento del dispositivo localmente y | "Línea de vida"                    |
|         |                            | informe del medidor                           |                                    |
| Grupo 2 | Medidor: Medidor Eléctrico | informe del medidor                           | “Medidor CT 1”                     |
|         |                            |                                               | (espejo del punto final 1 grupo 2) |
| grupo 3 | Medidor: Medidor Eléctrico | informe del medidor                           | “Medidor CT 2”                     |
|         |                            |                                               | (espejo del punto final 2 grupo2)  |

Para el punto final 1, admite un máximo de 1 nodo y un máximo de 2 grupos de asociación.

| Punto final 1 | Perfil 2 bytes             | Clase de comando    | Nombre del grupo     |
| ------------- | -------------------------- | ------------------- | -------------------- |
|               |                            |                     | (UTF-8)              |
| Grupo 1       | General: línea de vida     | informe del medidor | “Línea de vida EP 1” |
| Grupo 2       | Medidor: Medidor Eléctrico | informe del medidor | “Medidor CT 1”       |

Para Endpoint 2, admite un máximo de 1 nodo y un máximo de 2 grupos de asociación.

| Punto final 2 | Perfil 2 bytes             | Clase de comando    |   | Nombre del grupo     |   |   |
| ------------- | -------------------------- | ------------------- | - | -------------------- | - | - |
|               |                            |                     |   | (UTF-8)              |   |   |
|               |                            |                     |   |                      |   |   |
| Grupo 1       | General: línea de vida     | informe del medidor |   | “Línea de vida EP 2” |   |   |
| Grupo 2       | Medidor: Medidor Eléctrico | informe del medidor |   | “Medidor CT 2”       |   |   |

* ![](<.gitbook/assets/12 (44).png>)_**Punto final seleccionado**_

Si el controlador puede usar Multi\_Clase de comando de canal para acceder al punto final de la pinza amperimétrica, puede configurar el valor del punto final para que reaccione a la clase de comando del medidor V2.

**Punto final 1 seleccionado: (para CT1 del primer canal)**

* Tipo de dispositivo: Medidor simple
* Clases de comandos admitidas Información Z-Wave Plus CC, V2 Asociación CC, V2 Información del grupo de asociación CC Asociación multicanal CC, V3 Medidor CC, V2
* Descripción:

Para el punto final 1, la pinza amperimétrica informará

*
  1. Consumo de energía instantáneo (vatios) leído desde CT1.
  2. Consumo de energía acumulado (KWh) leído desde CT1.

**Punto final 2 seleccionado: (para CT2 del segundo canal)**

* Tipo de dispositivo: Medidor simple
* Clases de comandos admitidas Información Z-Wave Plus CC, V2 Asociación CC, V2 Información del grupo de asociación CC Asociación multicanal CC, V3 Medidor CC, V2
* Descripción:

Para el punto final 2, la pinza amperimétrica informará

*
  1. Consumo instantáneo de energía (vatios) leído desde CT2.
  2. Consumo de energía acumulado (KWh) leído desde CT2
