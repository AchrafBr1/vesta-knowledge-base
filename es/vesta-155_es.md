# VESTA 155

Módulo DI/DO (DIO-52-B)

Introducción

DIO-52-B es un módulo DI/DO que integra dispositivos cableados en redes inalámbricas para crear respuestas automatizadas y mejorar la seguridad y la conveniencia.

El módulo DI/DO tiene terminales de entrada digital y salida digital incorporados. Se puede conectar a un solo sensor, interruptor o dispositivo para recibir el comando de encendido/apagado desde el panel de control a través de DO y devolver el estado actual a través de DI al panel.

El DIO-52-B también se puede conectar a dispositivos separados. Con la regla de Domótica configurada en el Panel, el dispositivo conectado a su punto DI se puede convertir en el disparador de eventos, y su punto DO en el respondedor de eventos. Cuando se selecciona el “Modo de seguidor de entrada” en el Panel de control, el terminal DO se interconecta al terminal DI y el dispositivo terminal DO se activará mediante el disparador del dispositivo terminal DI.

**La cubierta superior****Base**

![](<.gitbook/assets/0 (21).png>)

**Identificación de piezas**

1.  **Botón de prueba**

Presione una vez para enviar un código de aprendizaje al Panel de control.

1.  **Indicador LED**

El indicador LED se enciende en las siguientes condiciones:

-   Parpadea 6 veces:

Cuando se activa el terminal de entrada o cuando el interruptor está transmitiendo una señal.

-   Parpadea 3 veces:

Cuando se activa el terminal de salida.

-   Parpadea una vez cada 4 segundos:

Las baterías están extremadamente bajas y es necesario reemplazarlas.

1.  **Compartimiento de la batería**
2.  **Terminal de alimentación**
3.  **Terminal de entrada digital (DI)**
4.  **Terminal de salida digital (DO)**

-   Al conectar el cable a cada terminal, utilice un destornillador Phillips mini para atornillar/desatornillar el terminal. Evite el uso de un destornillador de punta plana, que puede causar raspaduras.

1.  **Orificios de montaje**
2.  **Abrazaderas de alivio de tensión**

Las abrazaderas se utilizan para asegurar los cables y proporcionar alivio de tensión para proteger los cables del corte de metal.

1.  **Orificios de cableado**

Características

-   _**Fuente de alimentación**_

**Alimentación de CA y batería**

-   DIO-52-B puede funcionar con un adaptador de CC de 5-12 V de dos cables cuando se conecta al terminal de alimentación, o puede funcionar con tres baterías de litio CR123.
-   Cuando el terminal de alimentación y las baterías están en uso, DIO-52-B solo se alimentará a través del adaptador.

**Detección de batería baja**

-   DIO-52-B presenta la función de detección de batería baja. Cuando el voltaje de la batería es bajo, DIO-52-B transmitirá una señal de batería baja para notificar al usuario. Al cambiar las baterías, después de quitar las baterías viejas, presione el botón de prueba dos veces para descargarlas por completo antes de insertar baterías nuevas.
-   _**Supervisión**_

DIO-52-B transmitirá una señal de supervisión cada 30 a 50 minutos regularmente para informar su condición.

-   _Empezando_

1.  Inserte las baterías o conecte el adaptador de CC de 5-12 V de dos cables para encender el DIO-52-B.
2.  Coloque el Panel de control en modo de aprendizaje; consulte el manual del Panel de control para obtener más detalles.
3.  Presione el botón Prueba una vez, el LED parpadeará 6 veces.
4.  Si el Panel de control recibe la señal, mostrará la información correspondiente; consulte el manual del Panel de control para completar el proceso de aprendizaje.

\\<NOTE>

-   Cuando se aprende en el Panel de control, el DIO-52-B será reconocido como 2 dispositivos separados (DI y DO), ocupando 2 zonas en el Panel.
-   _**Prueba de caminata**_
-   Después de aprender el DIO-52-B, coloque el panel de control en (**Prueba de caminata**), mantenga presionado el módulo DI/DO en la ubicación deseada y presione el botón de prueba para transmitir la señal de prueba al panel de control. Si el panel de control está dentro del rango de señal DIO-52-B, el panel mostrará la información DI\\&DO correspondiente.
-   Continúe con el montaje y la instalación una vez que esté satisfecho de que el módulo DI/DO funciona correctamente en la ubicación deseada.
-   _**Modo de operación**_

El módulo DI/DO puede funcionar según los diferentes modos seleccionados en la página web del Panel de control o en el Home Portal Server (la función de selección de modo no está disponible en la aplicación Vesta Home 5). Por favor seleccione el modo en**Editar dispositivo**página.

| **Página web del panel de control**                                | **Servidor del portal de inicio**                                  |
| ------------------------------------------------------------------ | ------------------------------------------------------------------ |
| <img src=".gitbook/assets/1 (28).png" alt="" data-size="original"> | <img src=".gitbook/assets/2 (33).png" alt="" data-size="original"> |

-   **Control de electrodomésticos:**

Cuando se utiliza DIO-52-B para el control de aparatos, los terminales de entrada y salida están conectados al mismo dispositivo, p. una válvula de agua.

El terminal de salida se usa para recibir señal de encendido/apagado desde el Panel de control para apagar/encender el dispositivo conectado, mientras que el terminal de entrada se usa para transmitir el estado actual del dispositivo conectado al Panel.

Cuando se selecciona el modo "Control de electrodomésticos", puede encender/apagar remotamente el dispositivo conectado desde la página web del Panel de control, Home Portal Server o la aplicación Vesta Home 5, pero la configuración de salida y entrada en DO se desactivará. Puede programar reglas de Automatización del Hogar, Escenas en la página web del Panel o Home Portal Server para integrar el dispositivo conectado al DIO-52-B con otros dispositivos en el Panel de Control.

![](<.gitbook/assets/3 (29).png>)

Ejemplo de práctica DI/DO para el control de electrodomésticos:

![](<.gitbook/assets/4 (28).png>)

-   **Dispositivos separados:**

En este modo, los terminales de entrada y salida del DIO-52-B están conectados a dispositivos separados. El terminal de entrada se utiliza para monitorear la activación del dispositivo conectado y transmitir la señal de activación al Panel de control. El terminal de salida se utiliza para recibir la señal de encendido/apagado desde el panel de control para encender/apagar el dispositivo conectado.

Cuando DIO-52-B está funcionando en este modo, la configuración de entrada de seguimiento de salida en DO está desactivada. Los usuarios pueden programar reglas de automatización del hogar, escenas en la página web del panel o Home Portal Server para convertir el punto DI en disparador de eventos y el punto DO en respondedor de eventos.

Ejemplo de práctica DI/DO para dispositivos separados:

El terminal de entrada DI está conectado a un sensor de fuga de agua y la salida DO está conectada a una válvula de agua. Al establecer una regla de automatización del hogar en HPS, el panel cerrará automáticamente la válvula de agua cuando se active el sensor de fuga de agua.

| **Configuración DI**                                               | **configuración de HACER**                                         |
| ------------------------------------------------------------------ | ------------------------------------------------------------------ |
| <img src=".gitbook/assets/5 (20).png" alt="" data-size="original"> | <img src=".gitbook/assets/6 (12).png" alt="" data-size="original"> |

| **Regla de domótica**                                             |
| ----------------------------------------------------------------- |
| <img src=".gitbook/assets/7 (9).png" alt="" data-size="original"> |

![](<.gitbook/assets/8 (10).png>)

-   **Seguidor de entrada:**

En este modo, los terminales de entrada y salida del DIO-52-B están conectados a dispositivos separados. El dispositivo terminal de salida está interconectado con el dispositivo terminal de entrada.

Cuando se activa el dispositivo terminal de entrada, el dispositivo terminal de salida se activará de acuerdo con la configuración Salida siguiendo entrada. Consulte la siguiente sección_**Configuración DI y DO**_para detalles.

Después de seleccionar el modo “Seguidor de entrada”, se desactivará la función Regla de automatización del hogar y Aplicar escena en Home Portal Server. Necesitará programar el**Salida Seguir entrada**configuración en la página DO Device Edit, de modo que el dispositivo terminal de salida se active en consecuencia después de la activación del dispositivo terminal de entrada.

Ejemplo de práctica DI/DO para seguidor de entrada:

Después de seleccionar el modo "Seguidor de entrada" en la página de edición del dispositivo DO, seleccione "Latch" para la configuración de salida de seguimiento de entrada. El dispositivo terminal de salida se activará instantáneamente cuando se active el dispositivo terminal de entrada.

![](<.gitbook/assets/9 (10) (1).png>)

![](<.gitbook/assets/10 (4) (1).png>)

-   _**Configuración DI y DO**_
-   **Terminal de salida (DO):**

Programe los ajustes de DO en**Editar dispositivo**en la página web del Panel o en el servidor del Home Portal.

| **Página web del panel de control**                                    | **Servidor del portal de inicio**                                       |
| ---------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| <img src=".gitbook/assets/11 (3) (1).png" alt="" data-size="original"> | <img src=".gitbook/assets/12 (1) (1).jpeg" alt="" data-size="original"> |

Encendido a través de la aplicación:

-   **Hacer nada**– El dispositivo de salida Do no se puede encender a través de la aplicación.
-   **No apagues**- El dispositivo de salida Do no se apagará después de encenderlo a través de la APLICACIÓN.
-   **Apagar después de 1-240 seg/5-30 min**– Después de encenderse a través de la APP durante el tiempo seleccionado, el dispositivo de salida Do se apagará.

Estado para 0: Ingrese la descripción del Estado 0 para el terminal de salida.

Estado para 1: Ingrese la descripción del Estado 1 para el terminal de salida.

Invertir entrada: seleccione para cambiar el orden del Estado 0 y el Estado 1 para la entrada DI. Cuando se selecciona “Sí”, se cambiará el orden del Estado 0 y el Estado 1 para la entrada DI.

Invertir salida: seleccione para cambiar el orden del Estado 0 y el Estado 1 para la salida DO. Cuando se selecciona “Sí”, se cambiará el orden del Estado 0 y el Estado 1 para la salida DO.

Salida Seguir Entrada: Esta función está disponible sólo cuando se selecciona el Modo de Operación "Seguidor de 3 Entradas".

-   **No**- Cuando se activa el dispositivo terminal de entrada, el dispositivo terminal de salida no se activará.
-   **Pestillo**- El dispositivo terminal de salida se activará instantáneamente cuando se active el dispositivo terminal de entrada.
-   **Encendido durante 10-240 segundos/5-30 min**- Cuando se activa el dispositivo terminal de entrada, el dispositivo terminal de salida se activará durante un tiempo determinado.

Modo de operación: seleccione el modo de operación para DIO-52-B. Consulte la sección anterior para obtener más detalles.

-   **Entrada de terminal (DI):**

Programe la configuración DI en**Edición de dispositivo DI**en la página web del Panel o en el servidor del Home Portal.

| **Página web del panel de control**                                    | **Servidor del portal de inicio**                                      |
| ---------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| <img src=".gitbook/assets/13 (3) (1).png" alt="" data-size="original"> | <img src=".gitbook/assets/14 (2) (1).png" alt="" data-size="original"> |

Estado para 0: Ingrese la descripción del Estado 0 para el terminal de entrada.

Estado para 1: Ingrese la descripción del Estado 1 para el terminal de entrada.

Instalación

DIO-52-B se puede implementar sobre una superficie plana o montarse en la pared. Una vez que haya finalizado la prueba de recorrido y esté satisfecho de que el dispositivo puede comunicarse con el panel de control en la ubicación elegida, continúe con la instalación.

1.  Desconecte la fuente de alimentación principal.
2.  Afloje el tornillo de fijación inferior y retire la cubierta superior del DIO-52-B.
3.  Utilice los orificios de la base para marcar la ubicación de montaje en la pared.
4.  Taladre agujeros en el lugar marcado e inserte tacos de pared si es necesario, atornille la base en el lugar de montaje.
5.  Vuelva a colocar la cubierta superior y apriete el tornillo de fijación inferior.
