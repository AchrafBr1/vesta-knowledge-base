# VESTA 194

![](<.gitbook/assets/0 (79).jpeg>)**Sensor de caída-3**

Este sensor de caídas está diseñado para activar el panel de control presionando un botón manualmente o con la detección automática de caídas para solicitar ayuda en condiciones de emergencia.

**A. Identificación de las piezas**

![](<.gitbook/assets/1 (59).png>)![](<.gitbook/assets/2 (64).jpeg>)

-   1.  **Bucle de cordón**
    2.  **LED verde/rojo**
        -   El LED verde PARPADEA durante 1 segundo: cuando está encendido.
        -   LED verde FLASH: Transmitiendo señal al Panel de Control.
        -   LED rojo PARPADEO: Transmitiendo señal al panel de control en condiciones de batería baja.
        -   El LED rojo PARPADEA 3 veces: Se detecta estado de batería baja cuando se enciende.
    3.  **Botón activo**
        -   -   Presione el botón Activo para activar el Panel de control.
            -   Mantenga presionado el botón durante 8 segundos para cancelar la alarma.
            -   Mantenga presionado el botón durante 8 segundos para recibir datos del nivel de sensibilidad del Panel de control.
    4.  **Tapa del compartimento de la batería**

1.  **Detección automática de batería baja**

![](<.gitbook/assets/3 (57).jpeg>)![](<.gitbook/assets/4 (64).png>)

El sensor de caída cuenta con detección automática de batería baja.

-   -   Después de insertar la batería, el sensor de caída verificará automáticamente el voltaje de la batería y transmitirá la señal del estado de la batería al panel de control cada 24 horas. Si se detecta batería baja 3 veces seguidas, el sensor de caída entrará en estado de batería baja y transmitirá una señal de batería baja cada 12 horas.

1.  **Sensor de aprendizaje en caída**

Paso 1. Coloque el panel de control en modo de aprendizaje (consulte el manual del panel de control para obtener más detalles). Paso 2. Presione el botón en el sensor de caída. Se transmitirá una señal de radio al panel de control.

Paso 3. Consulte el manual de operación de su Panel de control para completar el proceso de aprendizaje.

**D. Batería**

El sensor de caída utiliza una batería de litio CR2477 de 3 V como fuente de energía.

Si el voltaje de la batería es bajo, se enviará una señal de Batería baja al Panel de control para notificar al usuario. Además, cuando se activa en estado de batería baja, el LED rojo parpadeará para recordarle al usuario que reemplace la batería.

![](<.gitbook/assets/5 (66).png>)

_\\<NOTE>_

-   -   Está prohibido aprender el Sensor de Caída al Panel de Control cuando se encuentra en estado de batería baja.

1.  **Ajuste del nivel de sensibilidad**

La sensibilidad del sensor de caída es programable desde el panel de control. Hay cinco niveles de sensibilidad disponibles para seleccionar.

El nivel 1 se refiere al nivel de sensibilidad más bajo, mientras que el nivel 5 se refiere al nivel de sensibilidad más alto.

| Nivel de sensibilidad | Valores                |
| --------------------- | ---------------------- |
|                       |                        |
| Nivel 1               | 130ms                  |
|                       |                        |
| Nivel 2               | 110ms                  |
|                       |                        |
| Nivel 3               | 90 ms (predeterminado) |
|                       |                        |
| Nivel 4               | 70 ms                  |
|                       |                        |
| Nivel 5               | 50 ms                  |
|                       |                        |

![](<.gitbook/assets/6 (46).png>)

_\\<NOTE>_

-   Después de configurar el nivel de sensibilidad desde el panel de control, presione y mantenga presionado el botón en el sensor de caída durante 8

1

![](<.gitbook/assets/7 (41).png>)segundos para recibir los datos del nivel de sensibilidad del Panel de control. El LED (verde en modo normal; rojo en estado de batería baja) se iluminará al recibir datos del Panel de control.

**F. Detección de inactividad**

Si se detecta una caída, el sensor transmitirá una señal de alarma al Panel de Control. Si no se detecta ningún movimiento repentino dentro de los 10 segundos posteriores a la detección de la caída, el sensor de caída transmitirá otro código de inactividad al panel de control.

**G. Recomendación de uso**

-   La mejor manera de usar un sensor de caídas**(O)**
    1.  Déjelo colgar frente al pecho y ajuste la longitud del collar para que el sensor cuelgue en la parte inferior del esternón como se muestra en la imagen a continuación.
    2.  Use el colgante expuesto afuera y delante de cualquier ropa o chaqueta pesada/de plumas.

![](<.gitbook/assets/8 (37).jpeg>)

-   -   1.  Cuando se produce una caída, lo mejor es que el sensor de caída pueda tocar el suelo.
    -   Manera incorrecta de usar un sensor de caída**(X)**
        1.  Si el collar es demasiado corto (alrededor de la clavícula) o demasiado largo (debajo del esternón), es probable que se produzca un disparo falso o que no haya respuesta.
        2.  El uso del sensor de caída dentro de un bolsillo en el pecho provocará que la condición no se detecte.
    -   Coloque con cuidado el sensor de caídas sobre un escritorio cuando no lo esté utilizando para evitar que se active una falsa alarma.
    -   Debido a la naturaleza del mecanismo de detección de caídas, la detección de caídas no puede ser 100 % precisa. No se pudieron evitar por completo las falsas alarmas o los fallos de detección durante el uso diario. Utilice el botón activo para activar la alarma manualmente cuando sea necesario para garantizar la seguridad.

1.  **Modo de sueño**
    -   Si el sensor de caída permanece estacionario durante más de 3 horas, entrará en modo de suspensión. Si se detecta movimiento durante el modo de suspensión, el sensor de caída iniciará una cuenta atrás de 1 minuto para volver al modo de funcionamiento normal. La función de detección de caídas se desactiva durante el temporizador de 1 minuto y el usuario puede colocarse el sensor de caídas sin activar una falsa alarma. Cuando expire el temporizador de 1 minuto, el sensor de caída volverá a su funcionamiento normal.
2.  **Pruebas**

Durante la prueba, no active el sensor de caída dos veces en un intervalo de 10 segundos.

![](<.gitbook/assets/9 (38).png>)

_**Declaración de la FCC**_

_Este dispositivo cumple con la Parte 15 de las normas de la FCC. La operación está sujeta a las dos condiciones siguientes:_

1.  _Es posible que este dispositivo no cause interferencias dañinas y_
2.  _Este dispositivo debe aceptar cualquier interferencia recibida, incluidas las interferencias que puedan provocar un funcionamiento no deseado._

![](<.gitbook/assets/10 (21).jpeg>)

_**Precaución de la FCC:**_

_Para garantizar el cumplimiento continuo, cualquier cambio o modificación no aprobado expresamente por la parte responsable del cumplimiento puede anular la autoridad del usuario para operar este equipo. (Ejemplo: utilice únicamente cables de interfaz blindados cuando se conecte a una computadora o dispositivos periféricos)._

2
