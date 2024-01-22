# VESTA 037

**Detector acústico de rotura de cristales (ACGS-23)**

El detector de rotura de vidrio detecta el sonido de alta frecuencia emitido por la rotura de vidrio y transmite una señal para notificar al panel de control del sistema de alarma cuando se activa.

![](<.gitbook/assets/0 (31).png>)

* _**Identificación de piezas**_
  *
    1. **Indicador LED verde (interior)**
    2. **Indicador rojo (interior)**
    3. **Micrófono**
    4. **Dip switch**
    5. **Compartimiento de la batería**
    6. **Botón Aprender/Probar**

\-Presione el botón una vez para enviar un código de aprendizaje.

*
  *
    1. **Manibela de encendido**

\-El interruptor de manipulación está comprimido contra la cubierta posterior y protege el detector contra la apertura de la cubierta o su extracción de la ubicación montada.

*
  *
    1. **Área de ruptura**

El área de separación tiene 2 orificios ciegos donde el plástico es más delgado para el montaje con tornillos. Cuando el detector se retira a la fuerza de la ubicación de montaje, el área de separación se separará y permitirá que se active el interruptor de manipulación.

* _**Indicador LED**_
  * Los indicadores LED están dentro de la cubierta frontal y solo son visibles cuando están activados.
  * LED rojo: El LED rojo se activa cuando:
    *
      * El interruptor de manipulación está activado.
      * Se presiona el botón Aprender/Probar.
      * Se detectó rotura de vidrio en modo de prueba, batería baja o condición de apertura por manipulación

![](<.gitbook/assets/1 (28).jpeg>)

(El LED rojo no se enciende cuando se detecta rotura de vidrio durante el funcionamiento normal)

*
  * LED verde

El LED verde se activa cuando se detecta rotura de vidrio en el modo de prueba.

* _**Empezando**_

![](<.gitbook/assets/2 (26).jpeg>) ![](<.gitbook/assets/3 (24).jpeg>)

*
  1. Inserte la batería para encender el dispositivo.
  2. Coloque el panel de control en modo de aprendizaje; consulte el manual del panel para obtener más detalles.
  3. Presione el botón Aprender/Probar una vez para transmitir el código de aprendizaje al panel.
  4. Consulte el manual del panel para completar el proceso de aprendizaje.
* _**Ajuste de sensibilidad**_

![](<.gitbook/assets/4 (37).png>) ![](<.gitbook/assets/5 (33).png>)

La sensibilidad del detector de rotura de vidrio se puede ajustar mediante los dos interruptores DIP. Ajuste la sensibilidad para cambiar el rango del detector.

1

| Sensibilidad | Interruptor DIP 1 | Interruptor DIP 2 | Rango de detección |
| ------------ | ----------------- | ----------------- | ------------------ |
|              |                   |                   |                    |
| Máximo       | APAGADO           | APAGADO           | Levantarse         |
|              |                   |                   |                    |
| Medio        | APAGADO           | EN                | 5 metros           |
|              |                   |                   |                    |
| Bajo         | EN                | APAGADO           | tío paterno        |
|              |                   |                   |                    |
| Mínimo       | EN                | EN                | 1,5 metros         |
|              |                   |                   |                    |

![](<.gitbook/assets/6 (22).jpeg>)

* _**Modo de prueba**_

El modo de prueba se utiliza para ayudar a verificar la distancia de detección del detector de rotura de vidrio. Cuando se presiona el botón Aprender/Probar, el detector de rotura de vidrio ingresará al modo de prueba durante 5 minutos. Al presionar el botón nuevamente durante el período de 5 minutos, se restablecerá el tiempo del modo de prueba a 5 minutos.

Durante el modo de prueba, los LED rojos se encenderán cuando se detecte una rotura de vidrio.

![](<.gitbook/assets/7 (20).jpeg>)

* _**Probando el detector**_

El detector debe probarse para garantizar que pueda detectar con éxito la rotura del vidrio.

![](<.gitbook/assets/8 (14).jpeg>)

**Herramienta de prueba**

Utilice el simulador de rotura de cristales FlexGuard FG-701 para crear un sonido de rotura de cristales.

1. Configure los interruptores FlexGuard FG-701 en modo “FLEX” y “TEST”. Presione el botón rojo de inicio.
2. Coloque el FG-701 en el lugar de prueba deseado sobre el vidrio y apunte el altavoz hacia el detector. Cierre la cubierta de la ventana si está presente.
3. Golpee el vidrio con una herramienta acolchada para crear un sonido de golpe. Cuando el FG-701 detecta el sonido de golpe del vidrio, reaccionará emitiendo un sonido de rotura del vidrio.

![](<.gitbook/assets/9 (10).jpeg>)

**Probando el detector**

Coloque el detector en la ubicación de instalación deseada y asegúrese de que el nivel de sensibilidad se ajuste según el rango de detección. Para una detección óptima, el ACGS-23 debe mirar hacia la ventana para controlar la rotura del vidrio.

2

1. Utilice un destornillador para aflojar el tornillo de fijación del ACGS-23 y quitar la tapa.
2. Presione el botón Aprender/Probar una vez, el detector de rotura de vidrio ingresará al modo de prueba durante 5 minutos. El LED verde parpadeará lentamente.
3. Presione el botón rojo de inicio del FG-701. En 8 segundos, golpee el vidrio con una herramienta acolchada para crear un sonido de golpe. El FG-701 responderá produciendo una ráfaga de audio de rotura de cristal.
4. ACGS-23 se activará si tanto el sonido de golpe como el de rotura de vidrio se reciben correctamente. El LED verde parpadeará rápidamente y el LED rojo se iluminará; la señal de rotura de cristal se transmitirá al panel de control.

![](<.gitbook/assets/10 (19).png>)

_\\_

*
  * Después de presionar el botón rojo de inicio del FG-701, si no hay acción durante 8 segundos, el simulador se apagará automáticamente. Deberá presionar el botón de inicio nuevamente para reiniciar la prueba.
* _**Función de supervisión**_

![](<.gitbook/assets/11 (15).jpeg>)

Cuando el detector de rotura de vidrio esté en funcionamiento normal, transmitirá una señal de supervisión regularmente cada 30\~50 minutos.

![](<.gitbook/assets/12 (10).jpeg>)

* _**Batería**_

El detector de rotura de cristales utiliza una batería de litio CR123A de 3 V.

El detector de rotura de cristales puede detectar un voltaje bajo de la batería. Cuando se detecta un voltaje de batería bajo, se enviará una señal de batería baja al Panel de control junto con transmisiones de señales regulares para que el Panel de control muestre el estado correspondiente.

Al cambiar la batería, presione el botón de aprendizaje/prueba un par de veces para descargarla después de retirar la batería antes de insertar una nueva.

![](<.gitbook/assets/13 (10).jpeg>)

* _**Espesor del vidrio**_

Vidrio flotado: 3 a 6,4 mm (1/8 a 1/4”)

Vidrio templado: 2,4 a 6,4 mm (3/32 a 1/4")

Vidrio cableado: 3,2 a 6,4 mm (1/8 a 1/4")

Vidrio laminado de 3,2 a 6,4 mm (1/8" a 1/4")

![](<.gitbook/assets/14 (11).jpeg>)

* _**Instalación**_

El detector de rotura de cristales debe montarse en el techo o en la pared. Para una detección óptima, el ACGS-23 debe mirar hacia la ventana para controlar la rotura del vidrio. No debe haber ningún obstáculo entre el Detector y la ventana protegida. La cubierta posterior del detector tiene orificios ciegos de montaje que se pueden romper para montarlos con tornillos. Alternativamente, también puede montar el detector con la cinta adhesiva de doble cara incluida.

**Ubicación de montaje:**

* Monte lejos de fuentes de sonido, como altavoces, aire acondicionado o motor.
* Monte lo más lejos posible de la ventana o puerta para evitar interferencias de sonido externo.

Montaje con tornillos

![](<.gitbook/assets/15 (13).png>)

1. Rompe los orificios ciegos en la cubierta posterior y úsalos como plantilla para marcar la posición en la pared/techo.
2. Taladre agujeros en el lugar marcado y atornille la cubierta posterior a la pared/techo; inserte el taco de pared si es necesario.
3. Vuelva a colocar el cuerpo principal del detector en la cubierta posterior. Asegúrese de que la tapa esté correctamente cerrada y que el dispositivo esté bien fijado a la pared.

![](<.gitbook/assets/16 (9).jpeg>)

Montaje de cinta adhesiva

Cuando utilice la cinta adhesiva de doble cara proporcionada, asegúrese de instalar el detector en una superficie plana. No lo instale en superficies irregulares o en lugares con pinturas agrietadas.

![](<.gitbook/assets/17 (8).jpeg>)

1. Limpie tanto la cubierta posterior del detector como la ubicación de montaje con un desengrasante adecuado.
2. Aplique la cinta adhesiva de doble cara a la cubierta posterior del detector y luego aplíquela en la ubicación de montaje._\\_
   * Al realizar el montaje con cinta adhesiva de doble cara, se desactivará la protección contra manipulaciones para retirar el lugar de montaje. La protección contra la apertura de la cubierta todavía está disponible.

![](<.gitbook/assets/18 (12).png>)

3
