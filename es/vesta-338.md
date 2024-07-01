# 🏥 VESTA-338



## Puesta en marcha rápida Mobile Lite VESTA-338&#x20;



<figure><img src=".gitbook/assets/image (48).png" alt=""><figcaption><p><a href="https://bydemes.com/es/productos/intrusion/alarma-medica-vesta/sensores/VESTA-338">VESTA-338</a></p></figcaption></figure>







**PASO 1: Activación de SIM y configuración de APN:**

{% hint style="success" %}
El dispositivo **incluye** una tarjeta SIM de simalarm.eu el APN es: **internet.csliot.com**
{% endhint %}

1. **Activación de la SIM:**
   * Accede al plan de activación de SIM de simalarm en el siguiente enlace: [Plan de SIM](https://www.simalarm.eu/es/generic-5-mb-20-sms-5voice-general-clone-en/)**.**
   * Sigue las [instrucciones ](https://app.gitbook.com/s/ZJzpNocHhYVmD43GZobR/third-parties/simalarm)para activar la SIM que viene incrustada en el dispositivo Mobile Lite VESTA-338.
2. **Configuración del APN:**
   *   Si el dispositivo no tiene el APN preconfigurado, envía un SMS al dispositivo con el siguiente formato:

       ```
       APN:PROG,1111,apn,usuario,contraseña
       ```

       * `apn` = El APN de tu operadora.
       * `usuario` = El usuario (Si no tiene usuario, dejar en blanco).
       * `contraseña` = La contraseña (Si no tiene contraseña, dejar en blanco).
   *   En caso de no tener usuario y contraseña, utiliza:

       ```
       APN:PROG,1111,apn,,
       ```

**Ejemplos adicionales de configuración por SMS:**

1.  **Configuración de CRA:**

    ```
    RPT:PROG,1111,1,abonado@ip:puerto,1,21,0,255
    ```
2.  **Envío de ubicación por SMS:**

    ```
    RPT:PROG,1111,2,00351967641619,2,31,0,255
    ```
3.  **Llamada al cliente final:**

    ```
    RPT:PROG,1111,3,00351967641619,3,0,0,4
    ```

**PASO 2: Registro del dispositivo en MedAlert:**

* Después de configurar el APN, espera **5 minutos** para que el dispositivo se conecte con éxito al cloud.
* Procede al registro del dispositivo como instalador en MedAlert a través de la **WEB** o la **APP**.

<figure><img src=".gitbook/assets/image (49).png" alt=""><figcaption><p><a href="https://smarthomesec.bydemes.com/medalert/">https://smarthomesec.bydemes.com/medalert/</a></p></figcaption></figure>



1. Acceder como instalador y seleccionar el botón + para añadir el panel Mobile lite:&#x20;

<figure><img src=".gitbook/assets/image (50).png" alt=""><figcaption></figcaption></figure>

2. Seleccionar Mobile lite:&#x20;



<figure><img src=".gitbook/assets/image (51).png" alt=""><figcaption></figcaption></figure>

3. Rellenar la información para añadir el panel:&#x20;

<figure><img src=".gitbook/assets/image (52).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**IMEI**: La dirección IMEI del dispositivo (Viene en un lateral o en la parte posterior del Mobile lite)

**Nombre de Equipo**&#x20;

**Telefono móvil:** MUY IMPORTANTE! Debe ser el número de telefono de la SIM insertada en el mobile lite, en el caso de la SIM de SIMALARM viene en la tarjeta azul/blanca
{% endhint %}



Una vez registrado el dispositivo, se puede configurar desde MedAlert
