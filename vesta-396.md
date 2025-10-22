---
icon: star-of-life
---

# VESTA-396

Quick Start Mobile Lite VESTA-338

<figure><img src="https://bydemes.com/ByDemesFiles/images/VESTA-396.jpg" alt="" width="375"><figcaption><p>VESTA-396</p></figcaption></figure>



**STEP 1: SIM activation and APN configuration:**

The device **includes** a SIM card from simalarm.eu the APN is: **internet.csliot.com**

1. **SIM activation:**
   * Access the simalarm SIM activation plan at the following link: [SIM Plan ](https://www.simalarm.eu/es/generic-5-mb-20-sms-5voice-general-clone-en/)**.**
   * Follow the [instructions](https://vesta-guide.gitbook.io/vesta-guide/third-parties/simalarm) to activate the SIM that comes embedded in the Mobile Lite VESTA-338 device.
2. **APN Settings:**
   *   If the device does not have the APN preconfigured, send an SMS to the device with the following format:

       Copy

       ```
       APN:PROG,1111,apn,usuario,contraseña
       ```

       * `apn`= Your operator's APN.
       * `usuario`= The user (If you do not have a user, leave blank).
       * `contraseña`= The password (If you do not have a password, leave it blank).
   *   If you do not have a username and password, use:

       Copy

       ```
       APN:PROG,1111,apn,,
       ```

**Additional SMS configuration examples:**

1.  **ARC Configuration:**



    ```
    RPT:PROG,1111,1,abonado@ip:puerto,1,21,0,255
    ```
2.  **Sending location via SMS:**



    ```
    RPT:PROG,1111,2,00351967641619,2,31,0,255
    ```
3.  **Call to the end customer:**



    ```
    RPT:PROG,1111,3,00351967641619,3,0,0,4
    ```

**STEP 2: Registering the device in MedAlert:**

* After setting the APN, please wait **5 minutes** for the device to successfully connect to the cloud.
* Proceed to register the device as an installer in MedAlert through the **WEB** or the **APP** .

<figure><img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F4073699981-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FnyRwTrjZZiTU2rxbXeIk%252Fuploads%252FNpmPo410FNF3Go3Vac2D%252Fimage.png%3Falt%3Dmedia%26token%3Dd003b23a-35ca-4d39-93c4-825a9064e81a&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=1e36a743&#x26;sv=2" alt=""><figcaption><p><a href="https://smarthomesec.bydemes.com/medalert/">https://smarthomesec.bydemes.com/medalert/</a></p></figcaption></figure>



1. Log in as an installer and select the + button to add the Mobile lite panel:

<figure><img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F4073699981-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FnyRwTrjZZiTU2rxbXeIk%252Fuploads%252FJhr3BrWiRQe3FWBStgta%252Fimage.png%3Falt%3Dmedia%26token%3D7bd4b4f6-1b8c-4715-9a20-88d95086bb13&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=72ff00a&#x26;sv=2" alt=""><figcaption></figcaption></figure>

1. Select Mobile lite:

<figure><img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F4073699981-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FnyRwTrjZZiTU2rxbXeIk%252Fuploads%252FUOj4E5QLbD7Ondk1hbrD%252Fimage.png%3Falt%3Dmedia%26token%3D527d080c-0ae9-4e33-8279-796fec03626b&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=e18363f7&#x26;sv=2" alt=""><figcaption></figcaption></figure>

1. Fill in the information to add the panel:

<figure><img src="https://vesta-guide.gitbook.io/~gitbook/image?url=https%3A%2F%2F4073699981-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FnyRwTrjZZiTU2rxbXeIk%252Fuploads%252F3WnFzLMxExsaRWK9WMbS%252Fimage.png%3Falt%3Dmedia%26token%3D89bee8b0-ba39-48bb-bf3a-1dbbdaedd692&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=2fa98716&#x26;sv=2" alt=""><figcaption></figcaption></figure>

**IMEI** : The IMEI address of the device (It comes on the side or back of the Mobile lite)

**Device name**

**Mobile phone:** VERY IMPORTANT! It must be the phone number of the SIM inserted in the mobile lite, in the case of the SIMALARM SIM it comes on the blue/white card

Once the device is registered, it can be configured from MedAlert



### **Estimated Battery Life Based on Configuration**

The following estimates provide a general guideline for battery life from a full charge (100%) to depletion (0%), based on different configurations:

* **Low Usage Configuration**: Up to 2 days
* **Moderate Usage Configuration**: Approximately 24h
* **High Usage Configuration**: About 8h

<figure><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Please note that these values are approximate and actual battery life can vary due to factors such as network strength, frequency of alerts, ambient temperature, and other environmental conditions.
