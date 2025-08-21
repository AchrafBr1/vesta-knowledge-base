---
description: Manual for VESTA BOGP-type panels (VESTA-068N and VESTA-067)
---

# VESTA-067

## Introduction: Manual for Autonomous BOGP Type Panels

<figure><img src=".gitbook/assets/image (19) (1) (1) (1).png" alt="" width="325"><figcaption><p>VESTA-068N/VESTA-067</p></figcaption></figure>

This manual is designed to guide you through the setup and configuration of autonomous BOGP-type panels, operated by batteries or an external battery. The content of the manual is organized as follows:

1. External battery and SIM connection
2. Panel registration as installer and Master
3. Add and configure devices
4. Complete system configurations and report to ARC

## 1. External Battery + SIM Connection and APN Configuration

{% hint style="info" %}
It is crucial to configure the APN so the panel can communicate with the SmartHomeSec cloud. Also, connecting the external battery is essential for the panel to maintain constant and effective communication with the cloud. If the panel only has internal batteries, it will not connect to the cloud unless XMPP is enabled in the panel settings.
{% endhint %}

### 1.1 SIM and External Battery Connection

<figure><img src=".gitbook/assets/image (4) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Insert SIM and External Battery</p></figcaption></figure>

#### Recommended external batteries:

{% hint style="success" %}
The panel with an external battery is 100% connected to the cloud. It will use BACKUP batteries if the external battery is exhausted.

**Very important** these batteries require ventilation so avoid any confined area without ventilation.
{% endhint %}

{% tabs %}
{% tab title="8 months duration" %}
[VESTA-436](https://bydemes.com/en/products/intrusion/vesta-alarm/battery/VESTA-436)

<figure><img src="https://bydemes.com/ByDemesFiles/images/VESTA-436_B.jpg" alt="" width="375"><figcaption><p>External Battery 7.5V /400Ah/3000W</p></figcaption></figure>
{% endtab %}

{% tab title="14 months duration" %}
[VESTA-435](https://bydemes.com/en/products/intrusion/vesta-alarm/battery/VESTA-435)

<figure><img src="https://bydemes.com/ByDemesFiles/images/450px/VESTA-435.jpg" alt=""><figcaption><p>External Battery 12V/500Ah, 6000W</p></figcaption></figure>
{% endtab %}
{% endtabs %}

### 1.2 APN Configuration

<figure><img src=".gitbook/assets/Multimedia1.gif" alt=""><figcaption><p>APN configuration on the panel</p></figcaption></figure>

{% hint style="info" %}
Note: We can also configure the APN with an SMS command, which we must send to the phone number of the SIM connected to the panel:

PROG 7982 GAPN:<mark style="color:orange;">internet</mark>,<mark style="color:purple;">user</mark>,<mark style="color:blue;">password</mark>

<mark style="color:orange;">Parameter 1</mark>: GPRS APN

<mark style="color:purple;">Parameter 2</mark>: GPRS username

<mark style="color:blue;">Parameter 3</mark>: GPRS password
{% endhint %}

{% hint style="warning" %}
Warning! For panels that DO NOT have an external battery, only internal batteries, enable the cloud using the keyboard and LCD screen of the panel as follows before proceeding:
{% endhint %}

<figure><img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Enable cloud when using the panel with batteries only</p></figcaption></figure>

## 2. Panel Registration as Installer and User

### 2.1 Installer Registration

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Step 1:</strong> Log in as an installer in the <a href="guia-de-usuario-smarthomesec.md">SmartHomeSec</a> APP</td><td><img src=".gitbook/assets/image (9) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td></td></tr><tr><td><p><strong>Step 2:</strong> Select the + button</p><p>(Add panel)</p></td><td><img src=".gitbook/assets/image (10) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td></td></tr><tr><td><strong>Step 3:</strong> Enter the panel's MAC address found on a label</td><td><img src=".gitbook/assets/image (11) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td></td></tr></tbody></table>

Once the panel is registered as an installer, it is ready ✨ for configuration.

{% hint style="danger" %}
The panel must be on and connected to the internet. We have 15 minutes after powering it up to register the panel.
{% endhint %}

{% hint style="success" %}
The MAC of the panel is always on one side of the panel physically. In the NAME field, we should place the subscriber or any identifier of the panel.
{% endhint %}

### 2.2 User Account Registration

The user account is used to control the system and is intended for the end user. From the SmartHomeSec APP, this account allows arming, disarming, and performing any operation. There are two types of user accounts: Master and Slave.

The first account we register is the Master. The main difference between the Master and Slave accounts is that the Master allows creating new users, while the Slave cannot create new accounts.

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Step 1:</strong> Access the panel as installers, the default code is [7982]</td><td><img src=".gitbook/assets/Imagen de WhatsApp 2024-06-02 a las 15.19.19_5e1f9a7f.jpg" alt="" data-size="original"></td><td></td></tr><tr><td><strong>Step 2:</strong> Select the Main system menu section<img src=".gitbook/assets/image (14) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""></td><td></td><td></td></tr><tr><td><strong>Step 3:</strong> Select account list</td><td></td><td><img src=".gitbook/assets/image (15) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td></tr><tr><td><strong>Step 4:</strong> Select add</td><td></td><td><img src=".gitbook/assets/image (17) (1) (1) (1) (1).png" alt="" data-size="original"></td></tr><tr><td><strong>Step 5:</strong> If it's a new user: Select create an account</td><td><img src=".gitbook/assets/image (18) (1) (1) (1) (1).png" alt="" data-size="original"></td><td></td></tr><tr><td><p><strong>Step 6:</strong> Fill in the user data for APP access</p><p><img src=".gitbook/assets/image (19) (1) (1) (1) (1).png" alt="" data-size="original"></p></td><td></td><td></td></tr></tbody></table>

{% hint style="success" %}
User registration completed! For information on how to operate with the user APP, follow the SmartHomeSec user guide.
{% endhint %}

## 3. Add and Configure Devices

To add and configure VESTA RF devices, follow these steps:

### 3.1 Add Devices

Step 1: Access the panel configuration from the installer APP:

<figure><img src=".gitbook/assets/image (20) (1) (1).png" alt="" width="192"><figcaption><p>Installer -> Settings</p></figcaption></figure>

Step 2: Select "Devices" in the menu.

<figure><img src=".gitbook/assets/image (21) (1) (1).png" alt="" width="190"><figcaption><p>Installer -> Settings -> Devices</p></figcaption></figure>

Step 3: In the menu click "Add device".

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (23) (1) (1).png" alt="" data-size="original"></td><td></td><td></td></tr><tr><td><img src=".gitbook/assets/image (24) (1) (1).png" alt="" data-size="original"></td><td></td><td></td></tr></tbody></table>

Step 4: Select the device type you want to add, e.g., Motion Detector. Press and hold the pairing button on the device until the LED flashes (refer to the device's manual for specific instructions).

Step 5: Follow the on-screen instructions to complete the pairing process. The panel will confirm the successful addition of the device.

<figure><img src=".gitbook/assets/image (27) (1) (1).png" alt=""><figcaption><p>Botón learn de los dispositivos VESTA</p></figcaption></figure>

{% hint style="danger" %}
Important! In case of PIRCAMS and keyboards: The keystroke must be 3 or 4 seconds. While the rest of the devices with a short press is enough to add them.
{% endhint %}

Once added, the RF devices will be ready for use and can be managed from the same section, here is an example of sensor attribute configuration:

### 3.2 Zone configuration

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (28) (1) (1).png" alt="" data-size="original"></td><td></td><td></td></tr><tr><td><img src=".gitbook/assets/image (30) (1) (1).png" alt="" data-size="original"></td><td></td><td></td></tr><tr><td><img src=".gitbook/assets/image (31) (1) (1).png" alt="" data-size="original"></td><td></td><td></td></tr></tbody></table>

{% hint style="info" %}
To configure the zones correctly, it is important to be familiar with the available attributes and their impact on the behavior of the alarm system.

For example: Interior is an instant zone and Entry is a delayed zone; we can assign these attributes in the section Response on arming which means "When the system is armed."
{% endhint %}

## 4. Panel configuration and reporting to ARC (Alarm Receiving Central Station)

### 4.1 Security configuration

This section details how to adjust the **siren duration** during an alarm and set the **input and output delays**. For ease of identification and adjustment, critical options are highlighted in \*\*color \*\*<mark style="color:red;">**red**</mark>.

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Ajustes -> Panel</td><td></td></tr><tr><td><img src=".gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Ajustes -> Panel -> Seguridad</td><td></td></tr><tr><td><img src=".gitbook/assets/image (4) (2).png" alt="" data-size="original"></td><td><ol><li>La <strong>siren duration</strong> en in case of alarm</li><li>Enabling this option delays the alarm reporting by 30 seconds. (<strong>Recommended to leave OFF</strong>)</li><li>Ajustar los <strong>entry and exit delays</strong></li></ol></td><td></td></tr></tbody></table>

### 4.2 Panel configuration

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Ajustes -> Panel</td><td></td></tr><tr><td><img src=".gitbook/assets/image (10) (2).png" alt="" data-size="original"></td><td>Ajustes -> Panel -> Panel</td><td></td></tr><tr><td><img src=".gitbook/assets/image (7) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>NOTAS ANEXO 1</td><td></td></tr></tbody></table>

_ANNEX 1_

{% hint style="info" %}
1. The **Polling with Alarm Receiving Centre** (Very important to configure according to the time provided by the ARC).
2. Connect Alarm: When the panel is only battery operated (<mark style="color:red;">**WITHOUT EXTERNAL BATTERY**</mark>) this option allows us to access the panel by **CLOUD during the ALARM**.
3.  **SAVINGS MODE ON:**

    1. **The panel when only operating by BATTERIES, will be OFFLINE, only connected in case of alarm** \2. **a. SAVING MODE&#x20;**<mark style="color:red;">**DISABLED**</mark>**: The panel will stay in CLOUD 100% on batteries \[Warning! Batteries will last 14 days]**.

    b. **SAVE MODE&#x20;**<mark style="color:green;">**ON**</mark>**: The panel will stay OFFLINE will report all events to both the APP and CRA \[Batteries will last 7 months approx.]**.
{% endhint %}

### 4.3 Configure user codes

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (20) (1) (1).png" alt="Instalador -> Ajustes" data-size="original"></td><td>Instalador -> Ajustes</td><td></td></tr><tr><td><img src=".gitbook/assets/image (8) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Ajustes -> PIN de usuario</td><td></td></tr><tr><td><img src=".gitbook/assets/image (9) (2).png" alt="" data-size="original"></td><td>Añadir el Nombre y código para cada usuario, este código permitirá al usuario cambiar de modo desde la APP o teclados consultar <a href="guia-de-usuario-smarthomesec.md">Manual de usuario</a> para más información</td><td></td></tr></tbody></table>

### 4.4 Updating the panel

It is crucial to keep the control panel up to date to ensure optimal system performance and security. Updates may contain essential enhancements, bug fixes and security patches that protect against known vulnerabilities.

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Ajustes -> Panel</td><td></td></tr><tr><td><img src=".gitbook/assets/image (11) (2).png" alt="" data-size="original"></td><td>Panel -> Actualización de FW</td><td></td></tr><tr><td><img src=".gitbook/assets/image (12) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Seleccionar del listado el firmware con versión más alta (Número más alto y letra más alta)</td><td></td></tr></tbody></table>

{% hint style="info" %}
NOTE: The panel by 2G or low coverage may take 8 minutes to update.

If the panel communicates over 4G/LTE with good coverage the update may take 3-5 minutes
{% endhint %}

{% hint style="danger" %}
Once the panel is in upgrade mode <mark style="color:red;">**Do NOT turn off**</mark> or disconnect under any circumstances. The panel will restart automatically.

SWITCHING OFF THE PANEL DURING AN UPGRADE MAY RENDER IT COMPLETELY INOPERATIVE.
{% endhint %}



### 4.5 Reporting configuration to ARC (Alarm Receiving Center)

_**Reporte Eventos**_

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (13) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Ajustes -> Reporte</td><td></td></tr><tr><td><img src=".gitbook/assets/image (14) (2).png" alt="" data-size="original"></td><td>En el apartado reporte disponemos de configuración de reporte para eventos y archivos capturados para fotos de PIRCAMS</td><td></td></tr><tr><td><img src=".gitbook/assets/image (15) (2).png" alt="" data-size="original"></td><td>En este apartado configuramos la URL de repote de nuestra CRA, y muy importante el <strong>GRUPO 2</strong> o superior ya que el gruopo 1 está empleado para la APP. ANEXO 2 para ejemplos</td><td></td></tr></tbody></table>

_APPENDIX 2_

{% hint style="success" %}
Examples of **EVENTS** reporting in different protocols:

:fire: **MANITOU (most used in Spain): ip://**<mark style="color:blue;">**ACCT**</mark>**@**<mark style="color:orange;">**IP**</mark>**:**<mark style="color:purple;">**PORT**</mark>**/MAN**

SIA: **ip://**<mark style="color:blue;">**ACCT**</mark>@<mark style="color:orange;">**IP**</mark>**:**<mark style="color:purple;">**PORT**</mark>/SIA2\*\*

CID: **ip://**<mark style="color:blue;">**ACCT**</mark>@<mark style="color:orange;">**IP**</mark>**:**<mark style="color:purple;">**PORT**</mark>/CID\*\*.
{% endhint %}

_**Photo report**_.

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (13) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Ajustes -> Reporte</td><td></td></tr><tr><td><img src=".gitbook/assets/image (14) (2).png" alt="" data-size="original"></td><td>En el apartado reporte disponemos de configuración de reporte para eventos y archivos capturados para fotos de PIRCAMS</td><td></td></tr><tr><td><img src=".gitbook/assets/image (16) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>En este apartado configuramos la URL de repote de nuestra CRA para el envío de fotos. ANEXO 3 para ejmplos</td><td></td></tr></tbody></table>

{% hint style="success" %}
Examples of **PHOTOS** reporting in different protocols:

:fire: **MANITOU**: <mark style="color:blue;">**ACCT**</mark>**@**<mark style="color:orange;">**IP**</mark>**:**<mark style="color:purple;">**PUERTO**</mark>
{% endhint %}



## Photo report for SENTINEL software

{% hint style="info" %}
Step 1: Program SMTP information in settings -> Report&#x20;
{% endhint %}

<figure><img src=".gitbook/assets/image (51).png" alt=""><figcaption><p>Example</p></figcaption></figure>



{% hint style="info" %}
Step 2: Program the email provided by central monitoring station in "Captured files"
{% endhint %}

<figure><img src=".gitbook/assets/image (52).png" alt=""><figcaption></figcaption></figure>



{% hint style="warning" %}
**IMPORTANT:** If you use IP cameras integrated with VESTA, you have to lower the camera resolution to 2MP or lower for proper operation.
{% endhint %}

## PANEL INSTALLER MANUAL

{% file src=".gitbook/assets/EN_VESTA-068N_manual_rev2.0.pdf" %}
