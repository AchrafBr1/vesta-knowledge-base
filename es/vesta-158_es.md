# VESTA 158

![](<.gitbook/assets/0 (47).png>)**Sensor de temperatura (TAS-9/TAS-9E)**

TAS-9E es un dispositivo sensor de temperatura inalámbrico. Transmite la condición de temperatura al panel de control cada 30 a 50 minutos y una señal de alarma cuando la temperatura excede o cae por debajo del rango de operación normal establecido por el interruptor DIP.

El Sensor de Temperatura incluye los siguientes modelos:**TAS-9:**Sensor de temperatura con sensor de temperatura incorporado.**Confianza:**Sensor de Temperatura con Sonda de Temperatura Externa.

![](<.gitbook/assets/1 (50).jpeg>)

-   _**Identificación de piezas**_

Retire la cubierta aflojando el tornillo de fijación inferior; el interior del sensor de temperatura quedará revelado como se muestra.

-   1.  **Bloque de terminales para sonda de temperatura externa (solo TAS-9E)**

Bloque de terminales opcional para conectar una sonda de temperatura externa.

-   1.  **Manibela de encendido**

Cuando el sensor de temperatura esté instalado correctamente, el interruptor de manipulación se comprimirá.

A**Cierre de manipulación**La señal se transmite cuando se comprime el Tamper.

A**manipulación abierta**La señal se transmite cuando se libera el sabotaje.

-   1.  **LED interno**

Parpadea rápidamente durante 2 segundos –

Interruptor antisabotaje cerrado/abierto, botón de aprendizaje/prueba presionado. Parpadea cada 4 segundos – Batería agotada

El LED parpadea una vez cada 4 segundos para indicar batería baja y se detienen todas las operaciones. Referirse a**Batería**para cambiar y restaurar la función del sensor de temperatura.

-   1.  **Bloque funcional del interruptor DIP**
    2.  **Botón Aprender/Probar**

Presione el botón una vez para enviar un código de aprendizaje junto con un código de estado para informar al panel de control el estado del sensor de temperatura.

-   1.  **Compartimiento de la batería**
    2.  **Conector de sonda de temperatura externa (solo TAS-9E)**
    3.  **Sonda de temperatura externa (solo TAS-9E)**
    4.  **Sonda de temperatura interna**
-   _**Batería**_

![](<.gitbook/assets/2 (47).jpeg>)![](<.gitbook/assets/3 (42).jpeg>)

El sensor de temperatura utiliza uno**CR123 - Batería de litio de 3V**. Reemplace siempre la batería con una del tamaño y voltaje correctos.

Cuando el sensor de temperatura tiene batería baja, se enviará una señal de batería baja al panel de control junto con transmisiones de señales regulares para que el panel de control muestre el estado correspondiente.

Cuando la batería se agota, el LED parpadea cada 4 segundos y el sensor de temperatura detendrá todas sus funciones.

-   **Cambio de batería**

1.  Retire la cubierta aflojando el tornillo de fijación inferior. Luego retire la batería vieja.

II. Presione el interruptor de manipulación o el botón de aprendizaje/prueba varias veces.

III. Coloque una batería nueva en el compartimiento de la batería. Oriente la batería según la polaridad correcta.

IV. Vuelva a colocar la cubierta.

1

-   ![](<.gitbook/assets/4 (42).jpeg>)_**Supervisión**_
    -   Se envía una señal de supervisión cada 30 a 50 minutos junto con la lectura de temperatura actual y el estado de la batería.
    -   El tiempo de supervisión se reinicia cada vez que se transmite una señal. (como**manipulación abierta**señal,**Cierre de manipulación**señal, etcétera).
-   _**Empezando**_
    -   Retire el tornillo de fijación y el conjunto de la cubierta.
    -   Inserte la batería en el soporte de la batería teniendo cuidado de conectar la polaridad correctamente.
    -   Ponga el Panel de control en modo de aprendizaje. Consulte el manual de usuario de su Panel de control.
    -   Presione el botón Aprender/Probar una vez para enviar un código de aprendizaje al Panel de control.
    -   Consulte el manual de usuario del Panel de control para completar el proceso de aprendizaje.
    -   Para verificar el alcance, coloque el panel de control en modo de prueba de caminata, coloque el dispositivo en la ubicación de montaje deseada y presione el botón Aprender/Probar para transmitir la señal para la prueba de ira.
    -   Cuando esté satisfecho de que el sensor de temperatura funciona en la ubicación elegida, puede continuar con la instalación.
-   _**Instalación**_

![](<.gitbook/assets/5 (26).jpeg>)![](<.gitbook/assets/6 (36).jpeg>)

Hay dos formas de montar el sensor de temperatura: montaje autoadhesivo o con tornillos.

-   **Montaje autoadhesivo**

1.  Limpiar la superficie con un desengrasante adecuado.
2.  Retire la cubierta protectora de un lado de la almohadilla adhesiva de doble cara y aplíquela firmemente en la parte posterior del dispositivo.

III. Luego retire la otra cubierta y presione firmemente el artículo en la ubicación deseada.

![](<.gitbook/assets/7 (31).png>)

_\\<NOTE>_

-   -   No utilice el método de instalación con almohadilla adhesiva sobre una superficie con pintura descascarada o agrietada, o sobre una superficie rugosa.
-   **Montaje con tornillos**

La base tiene dos orificios ciegos, donde el plástico es más delgado, para fines de montaje. Para montar el sensor de temperatura

1.  Retire la cubierta y rompa los agujeros ciegos en la base.

II. Usando los agujeros como plantilla, taladre agujeros en la superficie III. Inserte los tacos de pared si se fija en yeso o ladrillo.

IV. Atornille la base a los tacos de pared y luego vuelva a atornillar la cubierta a su base.

![](<.gitbook/assets/8 (28).jpeg>)

-   _**Operación y activación de alarma**_
    -   El sensor de temperatura se puede seleccionar para usar la sonda de temperatura interna o externa según la configuración del interruptor DIP.
    -   La configuración del interruptor DIP también determina cuatro rangos de temperatura para el funcionamiento normal y el umbral de activación de alarma.
    -   Se transmite una señal de activación de alarma si la temperatura supera el umbral de activación de alarma.**durante 10 minutos**.
    -   Se transmite una señal de restauración de alarma si la temperatura cae por debajo del umbral de restauración de alarma.**durante 4 minutos**.
    -   Consulte la siguiente tabla para obtener más detalles:

| ADEREZO   | ADEREZO    | Normal       | Alarma     | Alarma    | Sonda de detección |   |
| --------- | ---------- | ------------ | ---------- | --------- | ------------------ | - |
| Operación | Activación | Restauracion | (Interno o |           |                    |   |
| Cambiar 1 | Cambiar 2  |              |            |           |                    |   |
| Rango     | Límite     | Límite       | Externo)   |           |                    |   |
|           |            |              |            |           |                    |   |
| Apagado   | Apagado    | 7°C - 35°C   | &lt;7°C    | > 9°C     | Interno            |   |
| > 35°C    | &lt; 33°C  |              |            |           |                    |   |
|           |            |              |            |           |                    |   |
|           |            |              |            |           |                    |   |
| Apagado   | En         | &lt;-12°C    | > -12°C    | &lt;-14°C | Externo            |   |
| > 7ºC     | &lt;7°C    | > 9°C        |            |           |                    |   |
|           |            |              |            |           |                    |   |
|           |            |              |            |           |                    |   |
| En        | Apagado    | 7°C - 24°C   | &lt;7°C    | > 9°C     | Interno            |   |
| > 24°C    | &lt; 22°C  |              |            |           |                    |   |
|           |            |              |            |           |                    |   |
|           |            |              |            |           |                    |   |
| En        | En         | &lt;6°C      | > 6°C      | &lt; 4°C  | Externo            |   |
| > 7ºC     | &lt;7°C    | > 9°C        |            |           |                    |   |
|           |            |              |            |           |                    |   |
|           |            |              |            |           |                    |   |

-   Para cambiar entre modos, simplemente ajuste los interruptores DIP según la configuración deseada.

2
