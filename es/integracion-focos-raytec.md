# INTEGRACIÓN FOCOS RAYTEC

## Manual de Integración de Focos RAYTEC con Paneles VESTA

<figure><img src=".gitbook/assets/image (53).png" alt=""><figcaption><p><a href="https://bydemes.com/es/marcas/raytec">RAYTEC IP SERIES</a></p></figcaption></figure>



Este manual explica cómo integrar focos RAYTEC con los paneles de seguridad VESTA utilizando comandos HTTP GET. Estos comandos se configuran en las escenas y reglas automáticas de los paneles VESTA a través de la plataforma **SmartHomeSec**. A continuación, se proporcionan ejemplos detallados para apagar, encender y hacer parpadear un foco RAYTEC.

### **1. Preparativos Iniciales**

Antes de comenzar con la configuración, asegúrese de tener la siguiente información y elementos:

* **IP del Foco RAYTEC**: La dirección IP del dispositivo (por ejemplo, `192.168.1.63`).
* **Credenciales de Acceso**: Nombre de usuario (`admin`) y contraseña (`Admin1234`) del dispositivo RAYTEC.
* **Acceso al Panel VESTA**: Acceda al panel de seguridad VESTA mediante la interfaz de usuario de **SmartHomeSec**.

### **2. Comandos HTTP para Controlar el Foco RAYTEC**

Los comandos se enviarán mediante HTTP GET desde el panel VESTA para controlar los focos RAYTEC. A continuación, se muestran los ejemplos de comandos para distintas acciones:

*   **Apagar el foco:**

    ```url
    http://admin:Admin1234@192.168.1.63/power.cgi?Power=off&LightType=WL
    ```
*   **Encender el foco por 5 segundos:**

    ```url
    http://admin:Admin1234@192.168.1.63/power.cgi?LightType=WL&Power=on&Level=100&Time=5
    ```
*   **Hacer parpadear el foco por 5 segundos:**

    ```url
    http://admin:Admin1234@192.168.1.63/deter.cgi?Deter=on&Level=20&DeterFreq=fast&DeterPat=sos&Time=5
    ```

### **3. Configuración de Comandos en el Panel de Seguridad VESTA**

Para configurar estos comandos en el panel de seguridad VESTA, siga los siguientes pasos:

**Paso 1: Acceder a la Plataforma SmartHomeSec**

<figure><img src=".gitbook/assets/image (54).png" alt="" width="188"><figcaption><p>SmartHomeSec</p></figcaption></figure>

1. Inicie sesión en su cuenta de **SmartHomeSec** desde un navegador web o APP
2. Seleccione su panel VESTA correspondiente.

**Paso 2: Configurar Comandos en Escenas**

<figure><img src=".gitbook/assets/image (55).png" alt="" width="188"><figcaption><p>Escenas</p></figcaption></figure>

1. Diríjase a la sección de **Escenas**.
2. Cree una nueva escena o edite una existente.
3. Seleccione la opción para añadir una acción de **HTTP GET**.
4. Introduzca el comando HTTP deseado en el campo correspondiente:
   * Para apagar el foco, copie el comando proporcionado en el apartado de **Apagar**.
   * Para encender el foco por un tiempo específico, utilice el comando proporcionado en el apartado de **Encender**.
   * Para hacer parpadear el foco, use el comando del apartado de **Parpadear**.
5. Asigne un nombre descriptivo a la escena, como "Apagar Foco RAYTEC", "Encender Foco RAYTEC 5s", o "Parpadear Foco RAYTEC".
6. Guarde los cambios.

**Paso 3: Configurar Comandos en Reglas Automáticas**

<figure><img src=".gitbook/assets/image (56).png" alt="" width="188"><figcaption><p>Seleccionar Reglas</p></figcaption></figure>

1. Vaya a la sección de **Reglas**.
2. Cree una nueva regla o edite una existente.
3. Configure el disparador de la regla (por ejemplo, activación de alarma, detección de movimiento, etc.).
4. En las acciones, seleccione **Ejecutar Comando HTTP GET**.
5. Pegue el comando HTTP correspondiente a la acción deseada.
6. Guarde la regla con un nombre adecuado.

**4. Verificación y Pruebas**

Después de configurar los comandos:

1. **Ejecute las Escenas**: Desde la interfaz de SmartHomeSec, ejecute las escenas configuradas para verificar que el foco RAYTEC responde correctamente.
2. **Active las Reglas**: Pruebe las reglas automáticas generando los eventos que las disparen y observe si el foco RAYTEC se comporta según lo esperado.

**5. Solución de Problemas Comunes**

* **Error de autenticación:** Asegúrese de que las credenciales de acceso al dispositivo RAYTEC (`admin:Admin1234`) son correctas.
* **Conectividad de red:** Verifique que la dirección IP del foco RAYTEC es correcta y que ambos dispositivos (panel VESTA y foco RAYTEC) están en la misma red local.
* **Comandos no ejecutados:** Asegúrese de que los comandos HTTP están correctamente escritos y no contienen espacios o caracteres adicionales.

**6. Consideraciones de Seguridad**

* Cambie las credenciales predeterminadas del foco RAYTEC para evitar accesos no autorizados.
* Asegúrese de que la red local donde se encuentran los dispositivos esté protegida con una contraseña segura y cifrado adecuado.

**7. Conclusión**

Integrar focos RAYTEC con paneles VESTA mediante comandos HTTP GET es un proceso sencillo que permite automatizar la iluminación en función de las necesidades del usuario. Siguiendo estos pasos, podrá controlar de manera efectiva los focos RAYTEC desde el panel de seguridad VESTA.
