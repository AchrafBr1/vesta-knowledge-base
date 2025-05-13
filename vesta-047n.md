---
description: For all Radio (HSGW, ESGW) and hybrid VESTA panels
---

# VESTA-047N

Welcome to the **VESTA Wireless and Hybrid Control Panels Knowledge Base**. Here, you'll find all the essential information for installing, configuring, and maintaining VESTA security control panels that operate via wireless communication and hybrid systems.

This manual is designed for technicians, integrators, and advanced users who need a detailed understanding of these control panels. It includes step-by-step guides, troubleshooting tips, device compatibility, and best practices to optimize system performance.



## QUICK GUIDE&#x20;

## 1. Panel Registration as Installer and User

### 1.1 Installer Registration

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Step 1:</strong> Log in as an installer in the <a href="guia-de-usuario-smarthomesec.md">SmartHomeSec</a> APP</td><td><img src=".gitbook/assets/image (9) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td></td></tr><tr><td><p><strong>Step 2:</strong> Select the + button</p><p>(Add panel)</p></td><td><img src=".gitbook/assets/image (10) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td></td></tr><tr><td><strong>Step 3:</strong> Enter the panel's MAC address found on a label of panel</td><td><img src=".gitbook/assets/image (11) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td></td></tr></tbody></table>

Once the panel is registered as an installer, it is ready ✨ for configuration.

{% hint style="danger" %}
The panel must be on and connected to the internet. We have 15 minutes after powering it up to register the panel.
{% endhint %}

{% hint style="success" %}
The MAC of the panel is always on one side of the panel physically. In the NAME field, we should place the subscriber or any identifier of the panel.
{% endhint %}

### 2. User Account Registration

The user account is used to control the system and is intended for the end user. From the SmartHomeSec APP, this account allows arming, disarming, and performing any operation. There are two types of user accounts: Master and Slave.

The first account we register is the Master. The main difference between the Master and Slave accounts is that the Master allows creating new users, while the Slave cannot create new accounts.

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Step 1:</strong> Access the panel as installers, the default code is [7982]</td><td><img src=".gitbook/assets/Imagen de WhatsApp 2024-06-02 a las 15.19.19_5e1f9a7f.jpg" alt="" data-size="original"></td><td></td></tr><tr><td><strong>Step 2:</strong> Select the Main system menu section<img src=".gitbook/assets/image (14) (1) (1) (1) (1) (1).png" alt=""></td><td></td><td></td></tr><tr><td><strong>Step 3:</strong> Select account list</td><td></td><td><img src=".gitbook/assets/image (15) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td></tr><tr><td><strong>Step 4:</strong> Select add</td><td></td><td><img src=".gitbook/assets/image (17) (1) (1) (1).png" alt="" data-size="original"></td></tr><tr><td><strong>Step 5:</strong> If it's a new user: Select create an account</td><td><img src=".gitbook/assets/image (18) (1) (1) (1).png" alt="" data-size="original"></td><td></td></tr><tr><td><p><strong>Step 6:</strong> Fill in the user data for APP access</p><p><img src=".gitbook/assets/image (19) (1) (1) (1).png" alt="" data-size="original"></p></td><td></td><td></td></tr></tbody></table>

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

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Ajustes -> Panel</td><td></td></tr><tr><td><img src=".gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Ajustes -> Panel -> Seguridad</td><td></td></tr><tr><td><img src=".gitbook/assets/image (4) (2).png" alt="" data-size="original"></td><td><ol><li>La <strong>siren duration</strong> en in case of alarm</li><li>Enabling this option delays the alarm reporting by 30 seconds. (<strong>Recommended to leave OFF</strong>)</li><li>Ajustar los <strong>entry and exit delays</strong></li></ol></td><td></td></tr></tbody></table>

### 4.2 Panel configuration

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Settings -> Panel</td><td></td></tr><tr><td><img src=".gitbook/assets/image (10) (2).png" alt="" data-size="original"></td><td>Settings-> Panel -> Panel</td><td></td></tr><tr><td><img src=".gitbook/assets/image (7) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Polling --> test time to ARC </td><td></td></tr></tbody></table>



### 4.3 Configure user codes

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (20) (1) (1).png" alt="Instalador -> Ajustes" data-size="original"></td><td>Inslogging -> Settings</td><td></td></tr><tr><td><img src=".gitbook/assets/image (8) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Settings -> User PIN</td><td></td></tr><tr><td><img src=".gitbook/assets/image (9) (2).png" alt="" data-size="original"></td><td>Add the Name and code for each user, this code will allow the user to switch modes from the APP or keyboards see User Manual for more information.</td><td></td></tr></tbody></table>

### 4.4 Updating the panel

It is crucial to keep the control panel up to date to ensure optimal system performance and security. Updates may contain essential enhancements, bug fixes and security patches that protect against known vulnerabilities.

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Ajustes -> Panel</td><td></td></tr><tr><td><img src=".gitbook/assets/image (11) (2).png" alt="" data-size="original"></td><td>Panel -> Actualización de FW</td><td></td></tr><tr><td><img src=".gitbook/assets/image (12) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Select from the list the firmware with the highest version (Highest number and highest letter).</td><td></td></tr></tbody></table>

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

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (13) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Settings -> Report</td><td></td></tr><tr><td><img src=".gitbook/assets/image (14) (2).png" alt="" data-size="original"></td><td>In the report section we have report configuration for events and captured files for PIRCAMS photos.</td><td></td></tr><tr><td><img src=".gitbook/assets/image (15) (2).png" alt="" data-size="original"></td><td>In this section we configure the repote URL of our ARC, and very important the GROUP 2 or higher since group 1 is used for the APP. APPENDIX 2 for examples</td><td></td></tr></tbody></table>

_APPENDIX 2_

{% hint style="success" %}
Examples of **EVENTS** reporting in different protocols:

:fire: **MANITOU (most used in Spain): ip://**<mark style="color:blue;">**ACCT**</mark>**@**<mark style="color:orange;">**IP**</mark>**:**<mark style="color:purple;">**PORT**</mark>**/MAN**

SIA: **ip://**<mark style="color:blue;">**ACCT**</mark>@<mark style="color:orange;">**IP**</mark>**:**<mark style="color:purple;">**PORT**</mark>/SIA2

CID: **ip://**<mark style="color:blue;">**ACCT**</mark>@<mark style="color:orange;">**IP**</mark>**:**<mark style="color:purple;">**PORT**</mark>/CID
{% endhint %}

_**Photo report**_.

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src=".gitbook/assets/image (13) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Settings -> Report</td><td></td></tr><tr><td><img src=".gitbook/assets/image (14) (2).png" alt="" data-size="original"></td><td>In the report section we have report configuration for events and captured files for PIRCAMS photos.</td><td></td></tr><tr><td><img src=".gitbook/assets/image (16) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>In this section we configure the repote URL of our CRA for sending photos. APPENDIX 3 for examples</td><td></td></tr></tbody></table>

{% hint style="success" %}
Examples of **PHOTOS** reporting in different protocols:

:fire: **MANITOU**: <mark style="color:blue;">**ACCT**</mark>**@**<mark style="color:orange;">**IP**</mark>**:PORT**
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



## COMPLETE INSTALATION MANUALS



<figure><img src=".gitbook/assets/image (230).png" alt=""><figcaption><p>Hybrid Grade 3</p></figcaption></figure>

{% file src=".gitbook/assets/Hybrid Panel-1_Installation Guide.pdf" %}





<figure><img src=".gitbook/assets/image (231).png" alt=""><figcaption><p>Hybrid Lite</p></figcaption></figure>

{% file src=".gitbook/assets/Hybrid Panel Lite 2G 4G _Installation Guide.pdf" %}



<figure><img src=".gitbook/assets/image (232).png" alt=""><figcaption><p>Radio panels</p></figcaption></figure>

{% file src=".gitbook/assets/HSGW Installer Guide.pdf" %}







