# VESTA 040

Sensor de impacto, vibración y rotura de vidrio SVGS-5

SVGS-5 es un sensor de choque, vibración/rotura de vidrio. Es capaz de enviar señales inalámbricas al panel de control al detectar una rotura de vidrio o un golpe/vibración.

![](<.gitbook/assets/0 (9).jpeg>)Identificación de piezas

1.  **Botón Aprender/Probar**

(Presione el botón con una herramienta afilada, como un clip).

-   Presione el botón una vez para transmitir un código de aprendizaje/prueba.
-   Presione el botón una vez para ingresar al modo de prueba durante 3 minutos.
-   Presione el botón durante 5 segundos para ajustar la configuración de sensibilidad desde el panel de control.

1.  **Indicador LED**

-   **Se ilumina durante 1 segundo:**Cuando el sensor está encendido.
-   **Parpadea una vez:**Transmitiendo señal.
-   **Parpadea tres veces lentamente:**Batería baja detectada al encender.

**Características**

-   _Detección de batería y batería baja_
-   El sensor utiliza uno**P2477 ZV**Batería de litio como fuente de energía.
-   El sensor puede detectar un voltaje bajo de la batería. Cuando la batería está baja, se enviará una señal de batería baja al panel de control junto con una transmisión regular.
-   Al cambiar la batería, utilice una herramienta afilada para abrir la ranura de la batería y quitarla e insertarla.
-   Al insertar la batería, el**positivo(+)**El lado de la batería debe mirar hacia arriba.**NUNCA**Inserte la batería con el lado negativo (-) hacia arriba.

![](<.gitbook/assets/1 (6).jpeg>)

-   _**Supervisión**_

El sensor transmitirá una señal de supervisión para informar su condición periódicamente según la configuración del usuario. El intervalo predeterminado de fábrica es de 30 a 50 minutos.

-   _**Ajuste de sensibilidad**_

El sensor puede enviar una señal de alarma al panel de control según los diferentes niveles de sensibilidad establecidos en el panel de control. Los niveles de sensibilidad incluyen alto, medio y bajo (el valor predeterminado es medio si no se establece ningún nivel de sensibilidad en el Panel de control). Cuanto mayor sea la sensibilidad, más fácil será activar el sensor cuando se detecte una rotura de ventana/vidrio o una vibración de choque.

Después de agregar el sensor al Panel de control, puede configurar aún más su nivel de sensibilidad desde el Panel de control o Inicio

Página web del servidor Portal.

1.  Utilice una herramienta afilada, como un clip, para presionar el botón de prueba del sensor durante 5 segundos. El LED del sensor estará iluminado de forma fija.
2.  Consulte el manual de funcionamiento de su Panel de control para editar el dispositivo. Los usuarios podrán ajustar la configuración de sensibilidad en 10 segundos.
3.  Ir a**Tipo y sensibilidad**y seleccione la configuración deseada en el menú desplegable.
4.  Hacer clic**DE ACUERDO**para confirmar. El LED del sensor se atenuará para indicar una operación exitosa.

-   Para obtener detalles sobre el rango del modo de detección de golpes/vibraciones, consulte la sección Instalación en una sección posterior.
-   _**Modo de detección**_
-   La función de detección de golpes/vibraciones del dispositivo puede activarse según el modo diferente seleccionado en el Panel de control.
-   **Modo de descarga de pulso único**_**(modo predeterminado para SVGS-5 si no se establece ningún modo de detección en el Panel de control)**_

El dispositivo se activa cuando se detecta una única descarga que supera el umbral de detección.

-   **Modo multipulso/vibración acumulada**

El dispositivo se activa por cualquiera de las siguientes condiciones:

1.  Cuando**3**los conteos de pulso se detectan dentro**20****segundos**.
2.  Cuando se detecta una vibración menor acumulada con**2 minutos**excede el umbral de detección.

-   Para obtener detalles sobre el rango del modo de detección de golpes/vibraciones, consulte la sección**Instalación**en la sección posterior.
-   _**Test Mode**_

El sensor se puede poner en modo de prueba de 3 minutos presionando el botón de prueba:

-   Presione el botón Aprender/Probar una vez, el LED parpadeará para indicar que el sensor está en modo de prueba.
-   En el modo de prueba, cada vez que se activa el sensor, el LED parpadeará.
-   El sensor saldrá del modo de prueba después de 3 minutos.
-   _**Tiempo de dormir**_

El sensor entrará en un tiempo de suspensión de 2 minutos después de cada activación. El sensor no retransmitirá la señal de detección durante este período de 2 minutos. Cada activación de detección de descarga durante este período hará que el temporizador de apagado regrese a 2 minutos. El tiempo de sueño solo expirará si no se detecta ninguna descarga durante 2 minutos, luego el sensor volverá a su funcionamiento normal y transmitirá la siguiente señal de detección de descarga.

Aprendizaje e instalación

-   _**Aprendiendo**_

1.  Retire el aislante de la batería del sensor.
2.  Consulte el manual del Panel de control para poner el panel en modo de aprendizaje.
3.  Presione el botón Aprender/Probar una vez para transmitir un código de aprendizaje.
4.  Consulte el manual de funcionamiento de su panel de control para completar el proceso de aprendizaje.

-   _**Superficie y material de montaje**_

El sensor debe montarse directamente sobre una superficie de vidrio o madera contrachapada.

-   Espesor del vidrio: Vidrio chapado, templado y laminado: Mínimo 5 mm.
-   Espesor del contrachapado: Máximo 9 mm.
-   Grosor de la caja de seguridad: mínimo 3 mm.
-   _**Rango de sensibilidad y detección**_

La sensibilidad del sensor se ajusta a través del Panel de control. El rango de detección de diferente sensibilidad varía según los materiales de la superficie de montaje.

|                                         | Vaso                                      | Madera contrachapada                | Caja de seguridad          |   |
| --------------------------------------- | ----------------------------------------- | ----------------------------------- | -------------------------- | - |
| Material                                | Vidrio Chapado/Templado/Laminado/Cableado | Madera contrachapada                | Acero / Dióxido de Silicio |   |
| Espesor                                 | Mínimo 5 mm                               | Máximo 9 mm                         | mín.                       |   |
| Modo de detección de golpes/vibraciones | Modo de pulso único                       | Modo multipulso/vibración acumulada |                            |   |
| Sensitivity                             | Bajo                                      | 8000mm                              | 2000 mm                    | - |
| Medio                                   | 10000mm                                   | 2500mm                              | -                          |   |
| Alto                                    | 12000mm                                   | 3000 mm                             | 1400 mm                    |   |

-   _**Pasos y pautas de instalación**_

1.  Ajuste la sensibilidad del sensor como desee según el material de la superficie de montaje utilizando la tabla proporcionada en la sección anterior.

sección.

**Instalación de ventana/pared:**

Determine la ubicación de montaje en la ventana o la pared. El sensor puede montarse en el centro o en la esquina. Si un sensor no puede cubrir toda la superficie, utilice varios sensores.

\\<NOTE>

-   Cuando lo monte en una esquina, asegúrese de mantener al menos una distancia de 10 mm entre el sensor y el borde de la ventana o pared. Ajuste la dirección de la ranura de la batería (**No mires a la esquina**) para evitar dificultades al retirar la ranura de la batería.

**Instalación de caja de seguridad:**

Cuando lo monte en una caja de seguridad, monte el sensor a no más de 2 cm del pivote de la puerta.

1.  ![](<.gitbook/assets/5 (12).png>)Limpie y seque la ubicación de montaje. No lo instale en superficies sucias o web.
2.  Utilice la cinta adhesiva de doble cara proporcionada (Ø35 mm x 8 mm) para aplicarla a la cubierta posterior del SVGS y pegue el sensor en la ubicación de montaje.

\\<NOTE>

-   No aplique la cinta adhesiva de doble cara a la cubierta frontal donde se encuentran el botón de prueba y el indicador LED, y no aplique la cinta dos veces.

![](<.gitbook/assets/6 (7).png>)

-   _**Guía de instalación**_
-   Asegúrese siempre de probar el rango de detección después de la instalación para confirmar el rango de detección real.
-   La cinta adhesiva puede perder su adherencia con el tiempo. Asegúrese de revisar el sensor al menos una vez cada 6 meses.
-   Evite el montaje en un lugar propenso a fuertes vientos que podrían dislocar el sensor.
-   Evite el montaje en un lugar propenso a sacudidas o vibraciones, lo que provocará falsas alarmas.
-   Configure el sensor en sensibilidad baja cuando lo instale en ventanas móviles para evitar falsas alarmas.
-   Evite montarlo en un lugar donde el sensor pueda chocar fácilmente con un objeto.
-   Al montar sobre madera contrachapada:

1.  Utilice únicamente ajustes de alta sensibilidad.
2.  El montaje en la pared junto a muebles grandes puede afectar el rango de detección del sensor y el rango de transmisión de la señal. Asegúrese de probar el sensor si decide montarlo en dicha ubicación.

-   El rango de detección del sensor se ve afectado por el tamaño y el material de la cinta adhesiva. La tabla de rangos de sensibilidad proporcionada en este documento se prueba con cinta adhesiva proporcionada de fábrica. Si se utiliza una cinta adhesiva diferente, asegúrese de volver a probar el rango de detección.
