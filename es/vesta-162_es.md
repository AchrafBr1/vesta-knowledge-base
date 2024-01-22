# VESTA 162

**PRM2-ZW-P5**

**Interruptor de relé de potencia Z-Wave con medidor**

**Introducción**

El interruptor de relé de alimentación es capaz de recibir señales inalámbricas del coordinador en la red Z-Wave para activar o desactivar los electrodomésticos que están conectados a él.

El interruptor de relé de alimentación es un dispositivo habilitado para Z-Wave y es totalmente compatible con cualquier red habilitada para Z-Wave.

Z-Wave es un protocolo de comunicación inalámbrica que utiliza una radio RF de baja potencia. Aprovechando la red de malla Z-Wave, los comandos se pueden transmitir a su destino a través de productos Z-Wave intermediarios que "escuchan".

PRM2-ZW-P5 tiene la característica adicional de realizar un seguimiento del consumo de energía con el medidor de energía incorporado y transmitir los datos al coordinador regularmente.

PRM2-ZW-P5 también sirve como enrutador en la red Z-Wave. Después de ser incluido en la red Z-Wave, permite que otros dispositivos Z-Wave se unan a la red a través del interruptor de encendido.

**Identificación de piezas**

![](<.gitbook/assets/0 (57).jpeg>)

**1. Indicador LED**

El indicador LED se utiliza para indicar el estado del interruptor del relé de alimentación:

*
  * En:

El interruptor del relé de alimentación está encendido.

*
  * Apagado:

El interruptor del relé de alimentación está apagado.

1. **Botón de función**

El botón de función se utiliza para controlar el interruptor del relé de alimentación:

**Uso del botón de función:**

*
  * Presione el botón para activar/desactivar el interruptor del relé de alimentación
  * Presione el botón 3 veces en 1,5 segundos para agregar o eliminar de la red Z-Wave.
  * Mantenga presionado el botón durante 10 segundos para restablecer los valores de fábrica.

1. **Terminal de interruptor externo 1**
2. **Terminal de interruptor externo 2**
3. **Entrada de alimentación de línea de CA**
4. **Entrada de energía neuronal de CA**
5. **Salida de carga de potencia neutra de CA**
6. **Salida de carga de alimentación de línea de CA**

**Operación**

* _**Diagrama de conexión de cables**_
  * Consulte el diagrama para conectar sus dispositivos al interruptor de relé de alimentación.
* _**Instalación**_

![](<.gitbook/assets/1 (51).jpeg>)

\*\*Paso 1:\*\*Apague el suministro de electricidad al cable de alimentación por seguridad y para garantizar que el cable no sufra un cortocircuito durante el proceso de instalación.

\*\*Paso 2:\*\*Conecte el cable de alimentación de entrada de CA al conector de entrada y el cable de alimentación de salida al conector de salida.

\*\*Paso 3:\*\*Para la conexión del interruptor externo, conecte el interruptor con el control del interruptor externo.

\*\*Etapa 4:\*\*Después de completar el cableado, restablezca el suministro eléctrico al cable de alimentación.

1

* _**Agregar dispositivo (inclusión)**_

Este producto se puede incluir y operar en cualquier red Z-Wave con otros dispositivos certificados Z-Wave de otros fabricantes y/u otras aplicaciones. Todos los nodos de la red que no funcionan con baterías actuarán como repetidores independientemente del proveedor para aumentar la confiabilidad de la red.

*
  * Conecte el interruptor del relé de alimentación al cable de alimentación.
  * Coloque la puerta de enlace Z-Wave o el panel de control en**Inclusión**o**Aprendiendo**modo (consulte el manual de la puerta de enlace Z-Wave o del panel de control).
  * En 1,5 segundos, presione el botón de función 3 veces.
  * Consulte el manual de funcionamiento de la puerta de enlace Z-Wave o del panel de control para completar el proceso de aprendizaje.
  * Si el sensor ya ha sido**incluido**(aprendido) en otra puerta de enlace/panel de control Z-Wave, o si el sensor no se puede aprender en la puerta de enlace/panel de control Z-Wave actual, exclúyalo primero (consulte\_**Exclusión**\_) antes de intentar**incluir**en el panel de control/puerta de enlace Z-Wave actual.
* _**Eliminación del dispositivo (exclusión)**_

El interruptor de relé de alimentación debe retirarse de la red Z-Wave existente antes de incluirlo en otra. Hay dos métodos disponibles para excluir un dispositivo.

**Modo de exclusión**

* Coloque la puerta de enlace Z-Wave o el panel de control en**Modo de exclusión**(consulte el manual de la puerta de enlace Z-Wave o del panel de control).
* En 1,5 segundos, presione el botón de función 3 veces y el interruptor del relé de alimentación se eliminará de la red Z-Wave.

**Restablecimiento de fábrica**

_(Utilice el restablecimiento de fábrica únicamente cuando falte el panel de control/puerta de enlace de la red o no esté operativo)._

*
  * Mantenga presionado el botón de función durante 10 segundos para restablecer los valores de fábrica.

_\\_

*
  *
    * El restablecimiento de fábrica del interruptor de relé de alimentación lo restaurará a la configuración predeterminada de fábrica (excluido de la red Z-Wave). La puerta de enlace o el panel de control Z-Wave seguirán manteniendo su configuración Z-Wave. Consulte el manual de la puerta de enlace o del panel de control sobre cómo eliminar la configuración Z-Wave del interruptor de relé de alimentación.
* _**Prueba de rango**_

Para probar si el dispositivo puede comunicarse con la puerta de enlace Z-Wave o el panel de control:

*
  *
    * Coloque la puerta de enlace/panel en modo de prueba de alcance (Walk Test).
    * Presione el botón de función en el dispositivo.
    * La puerta de enlace/panel debe mostrar si el dispositivo está dentro del rango de operación (consulte el manual de operación de la puerta de enlace/panel).
* _**Control de electrodomésticos**_
  * Después de que el interruptor de relé de alimentación se haya unido con éxito a una red Z-Wave, el coordinador puede encender/apagar el dispositivo de forma remota.
  * También puede presionar el botón en el interruptor del relé de alimentación para encender/apagar la luz.
  * Puede encender/apagar el interruptor del relé de alimentación con un interruptor externo.
  * Si ha vinculado un controlador con el interruptor de relé de alimentación, también puede utilizar el controlador para encender/apagar el interruptor de relé de alimentación.
  * Si la entrada de alimentación de CA se desconecta del interruptor del relé de alimentación, su estado anterior de encendido/apagado se restaurará dentro de 1 minuto después de volver a conectar la entrada de alimentación de CA al interruptor del relé de alimentación.
* _**Monitor de consumo de energía**_
  * El Power Relay Switch transmitirá una señal con sus datos de consumo de energía cada 1 minuto al coordinador de red Z-Wave.
  * Siempre que la salida de energía del interruptor de alimentación cambie en +/- 2 W, transmitirá automáticamente una señal con datos de consumo de energía al coordinador de red Z-Wave para su actualización.
  * El interruptor de encendido transmite una señal con datos de energía al coordinador cada vez que el uso de energía acumulada aumenta en 0,1 kW/h.
  * El medidor tiene una precisión de +/- 5%.
  * 2 métodos para borrar los datos de consumo de energía acumulados del interruptor de relé de potencia:
    *
      1. Utilice la clase de comando de reinicio del medidor.
      2. Ejecute el restablecimiento de fábrica. Mantenga presionado el botón de función durante 10 segundos.

_\\_

* Si ejecuta el restablecimiento de fábrica, el dispositivo se eliminará de la red Z-wave. Tienes que incluirlo nuevamente. Para obtener instrucciones de inclusión, consulte la sección de\_**Agregar dispositivo (inclusión)**.\_

2

* _**Carga máxima de operación**_
  * Para 110V: la carga máxima de operación es 1100W y 10A.
  * Para 230V: la carga máxima de funcionamiento es de 2300W y 10A.
  * Si el interruptor del relé de alimentación se sobrecalienta, cortará la energía automáticamente como medida de seguridad. El usuario debe desconectar y volver a conectar la alimentación de CA al interruptor de relé de alimentación después del corte para reanudar el funcionamiento normal.
* _**Información de onda Z**_

\*\*Tipo de dispositivo:\*\*Interruptor de encendido/apagado

\*\*Tipo de rol:\*\*Siempre en esclavo (AOS)

**Soporte/Control de Clase de Comando**

\*\*Soporte CC obligatorio:\*\*Asociación CC, v2 o más reciente

Información del grupo de asociación CC

Medidor CC, v2

CC básico

Interruptor binario CC

Restablecimiento del dispositivo localmente CC

CC específico del fabricante

Nivel de potencia CC

Versión CC, v2 o más reciente

Z-Wave Plus Información CC

\*\*Soporte CC recomendado:\*\*Metadatos de actualización de firmware CC

* _**Grupos de Z-Wave (clase de comando de asociación versión 2)**_

El Switch se puede configurar para enviar informes a dispositivos Z-Wave asociados. Admite un grupo de asociación con soporte de cinco nodos para el Grupo 1. Para el Grupo 1, el conmutador informará su último estado al panel/puerta de enlace Z-Wave.

El grupo 1 incluye:

Interruptor binario CC (INTERRUPTOR\_BINARIO\_INFORME)

Medidor CC, v2 (METRO\_INFORME\_DOMINIO)

Restablecimiento del dispositivo localmente CC (COMANDO\_CLASE\_DISPOSITIVO\_REINICIAR\_EN LA ZONA)

* Informe automático al Grupo 1 (Nodo máximo 5)
* Informe de evento activado/desactivado

Al alternar entre Encendido/Apagado, enviará un Informe de cambio binario a los nodos del Grupo 1.

3
