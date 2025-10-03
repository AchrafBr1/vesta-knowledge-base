---
description: For all Radio (HSGW, ESGW) and hybrid VESTA panels
icon: screwdriver
---

# PANEL INSTALLER MANUAL

Welcome to the **VESTA Wireless and Hybrid Control Panels Knowledge Base**. Here, you'll find all the essential information for installing, configuring, and maintaining VESTA security control panels that operate via wireless communication and hybrid systems.

This manual is designed for technicians, integrators, and advanced users who need a detailed understanding of these control panels. It includes step-by-step guides, troubleshooting tips, device compatibility, and best practices to optimize system performance.



## QUICK GUIDE&#x20;

## 1. Panel Registration as Installer and User

### 1.1 Installer Registration

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Step 1:</strong> Log in as an installer in the <a href="../guia-de-usuario-smarthomesec.md">SmartHomeSec</a> APP</td><td><img src="../.gitbook/assets/image (9) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td></td></tr><tr><td><p><strong>Step 2:</strong> Select the + button</p><p>(Add panel)</p></td><td><img src="../.gitbook/assets/image (10) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td></td></tr><tr><td><strong>Step 3:</strong> Enter the panel's MAC address found on a label of panel</td><td><img src="../.gitbook/assets/image (11) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td></td></tr></tbody></table>

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

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Step 1:</strong> Access the panel as installers, the default code is [7982]</td><td><img src="../.gitbook/assets/Imagen de WhatsApp 2024-06-02 a las 15.19.19_5e1f9a7f.jpg" alt="" data-size="original"></td><td></td></tr><tr><td><strong>Step 2:</strong> Select the Main system menu section<img src="../.gitbook/assets/image (14) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""></td><td></td><td></td></tr><tr><td><strong>Step 3:</strong> Select account list</td><td></td><td><img src="../.gitbook/assets/image (15) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td></tr><tr><td><strong>Step 4:</strong> Select add</td><td></td><td><img src="../.gitbook/assets/image (17) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td></tr><tr><td><strong>Step 5:</strong> If it's a new user: Select create an account</td><td><img src="../.gitbook/assets/image (18) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td></td></tr><tr><td><p><strong>Step 6:</strong> Fill in the user data for APP access</p><p><img src="../.gitbook/assets/image (19) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></p></td><td></td><td></td></tr></tbody></table>

{% hint style="success" %}
User registration completed! For information on how to operate with the user APP, follow the SmartHomeSec user guide.
{% endhint %}

## 3. Add and Configure Devices

To add and configure VESTA RF devices, follow these steps:

### 3.1 Add Devices

Step 1: Access the panel configuration from the installer APP:

<figure><img src="../.gitbook/assets/image (20) (1) (1) (1) (1) (1) (1).png" alt="" width="192"><figcaption><p>Installer -> Settings</p></figcaption></figure>

Step 2: Select "Devices" in the menu.

<figure><img src="../.gitbook/assets/image (21) (1) (1) (1) (1) (1) (1).png" alt="" width="190"><figcaption><p>Installer -> Settings -> Devices</p></figcaption></figure>

Step 3: In the menu click "Add device".

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src="../.gitbook/assets/image (23) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td></td><td></td></tr><tr><td><img src="../.gitbook/assets/image (24) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td></td><td></td></tr></tbody></table>

Step 4: Select the device type you want to add, e.g., Motion Detector. Press and hold the pairing button on the device until the LED flashes (refer to the device's manual for specific instructions).

Step 5: Follow the on-screen instructions to complete the pairing process. The panel will confirm the successful addition of the device.

<figure><img src="../.gitbook/assets/image (27) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Botón learn de los dispositivos VESTA</p></figcaption></figure>

{% hint style="danger" %}
Important! In case of PIRCAMS and keyboards: The keystroke must be 3 or 4 seconds. While the rest of the devices with a short press is enough to add them.
{% endhint %}

Once added, the RF devices will be ready for use and can be managed from the same section, here is an example of sensor attribute configuration:

### 3.2 Zone configuration

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src="../.gitbook/assets/image (28) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td></td><td></td></tr><tr><td><img src="../.gitbook/assets/image (30) (1) (1) (1) (1).png" alt="" data-size="original"></td><td></td><td></td></tr><tr><td><img src="../.gitbook/assets/image (31) (1) (1) (1) (1).png" alt="" data-size="original"></td><td></td><td></td></tr></tbody></table>

{% hint style="info" %}
To configure the zones correctly, it is important to be familiar with the available attributes and their impact on the behavior of the alarm system.

For example: Interior is an instant zone and Entry is a delayed zone; we can assign these attributes in the section Response on arming which means "When the system is armed."
{% endhint %}

## 4. Panel configuration and reporting to ARC (Alarm Receiving Central Station)

### 4.1 Security configuration

This section details how to adjust the **siren duration** during an alarm and set the **input and output delays**. For ease of identification and adjustment, critical options are highlighted in \*\*color \*\*<mark style="color:red;">**red**</mark>.

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) ( (8).png" alt="" data-size="original"></td><td>Ajustes -> Panel</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Ajustes -> Panel -> Seguridad</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (4) (2).png" alt="" data-size="original"></td><td><ol><li>La <strong>siren duration</strong> en in case of alarm</li><li>Enabling this option delays the alarm reporting by 30 seconds. (<strong>Recommended to leave OFF</strong>)</li><li>Ajustar los <strong>entry and exit delays</strong></li></ol></td><td></td></tr></tbody></table>

### 4.2 Panel configuration

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) ( (8).png" alt="" data-size="original"></td><td>Settings -> Panel</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (10) (2).png" alt="" data-size="original"></td><td>Settings-> Panel -> Panel</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (7) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Polling --> test time to ARC </td><td></td></tr></tbody></table>

{% hint style="success" %}
## 🔧 **Configuration Parameters \[Panel --> Panel]**

**AC Failure Report**\
Wait time to detect and report power outage (AC = Alternating Current).

**AC Failure Suspension**\
If enabled, the system enters eco mode when power is cut (Panel will report every thing but app will be offline). "Disable" = panel will keep 100% online during AC failure.

**Interference Report**\
Detects and reports signal jamming attempts or radio frequency (RF: F1 and SF1) interference.

**ARC Polling**\
Interval at which a heartbeat signal (ping) is sent to the Central Monitoring Station (ARC), use every 3 minutes (Ask you ARC)

**Daily Auto Check-in**\
Time when the panel sends an automatic daily check.&#x20;

**GPRS/LTE Test Interval**\
Frequency for testing GPRS or LTE mobile connection.&#x20;

**ETHERNET Test Interval**\
Same as above but for wired network (Ethernet).&#x20;

**Disable Device Status Alerts**\
If enabled, panel will not report device status change in UI (Open/close) Often used to save mobile data in SIM-only panels.

**PD6662 Compliance**\
European standard for intrusion alarm systems.&#x20;

**PIRCAMS Resolution**\
Quality of images captured by PIR cameras.&#x20;

**Outdoor IR Camera in Grayscale**\
Allows or prevents use of black and white IR cameras, useful for outdoor applications.&#x20;

**Bypass Ethernet Failure**\
If enabled, ignores wired network outages. Off = detects them.

**Service Failure Report (Ethernet)**\
Reports if the panel loses connection to its server.&#x20;

**Power Supply Overcurrent Reset Time**\
If an overload is detected (Only in hybrid system), the panel waits x minutes before restarting.

**Wired Device Tolerance**\
Tolerance margin for wired devices before generating an alarm.&#x20;

**Mute Internal Siren**\
Prevents the panel's siren from sounding during an alarm. Off = will sound.

**DNS Update Period**\
Frequency of domain updates if using domain name instead of IP. Disabled = no updates.
{% endhint %}

### 4.3 Configure user codes

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src="../.gitbook/assets/image (20) (1) (1) (1) (1) (1) (1).png" alt="Instalador -> Ajustes" data-size="original"></td><td>Inslogging -> Settings</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (8) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Settings -> User PIN</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (9) (2).png" alt="" data-size="original"></td><td>Add the Name and code for each user, this code will allow the user to switch modes from the APP or keyboards see User Manual for more information.</td><td></td></tr></tbody></table>

### 4.4 Updating the panel

It is crucial to keep the control panel up to date to ensure optimal system performance and security. Updates may contain essential enhancements, bug fixes and security patches that protect against known vulnerabilities.

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) ( (8).png" alt="" data-size="original"></td><td>Ajustes -> Panel</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (11) (2).png" alt="" data-size="original"></td><td>Panel -> Actualización de FW</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (12) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Select from the list the firmware with the highest version (Highest number and highest letter).</td><td></td></tr></tbody></table>

{% hint style="info" %}
NOTE: The panel by 2G or low coverage may take 8 minutes to update.

If the panel communicates over 4G/LTE with good coverage the update may take 3-5 minutes
{% endhint %}

{% hint style="danger" %}
Once the panel is in upgrade mode <mark style="color:red;">**Do NOT turn off**</mark> or disconnect under any circumstances. The panel will restart automatically.

SWITCHING OFF THE PANEL DURING AN UPGRADE MAY RENDER IT COMPLETELY INOPERATIVE.
{% endhint %}



### 4.5 Reporting configuration to ARC (Alarm Receiving Center)

#### _**Event Report**_

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src="../.gitbook/assets/image (13) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Settings -> Report</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (14) (2).png" alt="" data-size="original"></td><td>In the report section we have report configuration for events and captured files for PIRCAMS photos.</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (15) (2).png" alt="" data-size="original"></td><td>In this section we configure the report URL of our ARC, and very important the GROUP 2 or higher since group 1 is used for the APP. APPENDIX 2 for examples</td><td></td></tr></tbody></table>

#### _APPENDIX 2_

{% hint style="success" %}
Examples of **EVENTS** reporting in different protocols:

:fire: **MANITOU (most used in Spain): ip://**<mark style="color:blue;">**ACCT**</mark>**@**<mark style="color:orange;">**IP**</mark>**:**<mark style="color:purple;">**PORT**</mark>**/MAN**

SIA: **ip://**<mark style="color:blue;">**ACCT**</mark>@<mark style="color:orange;">**IP**</mark>**:**<mark style="color:purple;">**PORT**</mark>/SIA2

CID: **ip://**<mark style="color:blue;">**ACCT**</mark>@<mark style="color:orange;">**IP**</mark>**:**<mark style="color:purple;">**PORT**</mark>/CID
{% endhint %}

In this section, you will find the **standard communication protocols** supported by VESTA panels for reporting events directly to the Alarm Receiving Center (ARC).\
These protocols allow the panel to send All EVENTS except photos without the need for additional converters or tools.

If your ARC uses **one of these standard protocols** (such as **MANITOU XML**, **SIA DC09**, or **Contact ID**), the panel can be configured to report directly using the appropriate format.

{% hint style="warning" %}
If your ARC **does not support any of the standard protocols**, please refer to the [**ALARMSPACE** ](panel-installer-manual.md#id-4.5.1-using-alarmspace-software-gateway-for-non-standard-arc-protocols)section below, which explains how to integrate non-standard systems using VESTA's translation software.
{% endhint %}

{% hint style="info" %}
## Extended examples: Reporting URL Configuration



### Overview

Reporting URLs are used by the installer to program report destinations for the security system.

### Supported URL Formats

#### 1. CID Protocol via TCP IP

**Format:** `ip://(Account Number)@(Server IP):(Port)/CID`\
**Example:** `ip://1234@54.183.182.247:8080/CID`

#### 2. SIA DC-09 Protocol via IP

**Format:** `ip://(Account Number)@(Server IP):(Port)/SIA2`\
**Example:** `ip://1234@54.183.182.247:8080/SIA2`

#### 3. SIA DC-09 Protocol via IP with AES Encryption

**Format:** `ip://(Account Number)@(Server IP):(Port)/SIA/KEY/(128, 192, or 256-bit Key)`\
**Example:** `ip://1234@54.183.182.247:8080/SIA/KEY/4A46321737F890F654D632103F86B4F3`

#### 4. SIA DC-09 Protocol Using CID Event Code via TCP IP (wrapped events)

**Format:** `ip://(Account Number)@(Server IP):(Port)/CID_SIA2`\
**Example:** `ip://1234@54.183.182.247:8080/CID_SIA2`

#### 5. SIA DC-09 Protocol Using CID Event Code via IP with HEX Encryption

**Format:** `ip://(Account Number)@(Server IP):(Port)/CID_SIA/KEY/(HEX Key)`\
**Example:** `ip://1234@54.183.182.247:8080/CID_SIA/KEY/4A46321737F890F654D632103F86B4F3`

#### 6. CSV Protocol via IP

**Format:** `ip://(Account Number)@(Server IP):(Port)/CSV`\
**Example:** `ip://1234@54.183.182.247:8080/CSV`

#### 7. CSV Protocol via IP with Authentication

**Format:** `ip://(Account Number)@(Server IP):(Port)/CSV/Username/Password`\
**Example:** `ip://1234@54.183.182.247:8080/CSV/abcd/1357`

#### 8. Email

**Format:** `mailto:user@example.com`\
**Example:** `mailto:john@gmail.com`

###

### Level Configuration

Select a reporting condition for each destination:

* **All Events:** The system will report all events to this destination
* **Alarm Events:** The system will only report alarm events to this destination
* **Status Events:** The system will only report status events (non-alarm events) to this destination

### Group Configuration

Select a group for your report destination. The system follows these reporting principles:

#### Priority Structure

Groups are reported in priority order: Group 1 → Group 2 → Group 3, etc.

#### Reporting Logic

1. **Within a Group:** If reporting to the first destination in a group fails, the system moves to the next destination in that group
2. **Group Success:** If any destination in a group receives the report successfully, the system considers that group successful and moves to the next group
3. **Group Failure:** If all destinations in a group fail, the system retries according to the retry settings below
4. **Cycle Completion:** After attempting all groups (Group 1 → Group 2 → ... → Group 5), if any Essential group failed to receive reports, the system restarts the reporting cycle

#### Essential vs. Optional Groups

**Essential Groups:**

* The system will report to all groups marked as Essential
* The system never stops trying until at least one destination in every Essential group successfully receives the report
* Group 1 is always Essential and cannot be changed

**Optional Groups:**

* The system only reports to Optional groups when the previous group fails
* Example: If Group 3 is set as Optional, the system will only report to Group 3 if reporting to Group 2 fails

#### Retry Settings

Choose from: 1, 3, 5, 10, or 99 retries

If reporting to all destinations in a group fails, the system will retry reporting to that group according to the retry count specified here.

### Important Notes

⚠️ **VESTA SmartHomeSec app report:**

* When the panel is registered with VESTA APP, URL1 will be automatically configured with Home Portal Server information
* **Do not modify** this information after registration is complete, or reporting to the Home Portal Server may fail
* If you need additional reporting destinations after registering with Home Portal Server, configure them in a **different group** than URL1 to ensure successful reporting
{% endhint %}

### 4.5.1 Using ALARMSPACE Software Gateway for Non-Standard ARC Protocols

In cases where the Alarm Receiving Center (ARC) does **not** support any of the standard reporting protocols listed above (e.g., MANITOU, XML, SIA DC09, CID, etc.), **VESTA provides a software gateway solution called ALARMSPACE**.

<figure><img src="../.gitbook/assets/image (312).png" alt=""><figcaption><p>ALARMSPACE</p></figcaption></figure>

**ALARMSPACE** acts as a translation layer between the VESTA panel and the ARC, converting VESTA events into the required format expected by the ARC’s monitoring system. This ensures full compatibility even when a proprietary or custom protocol is used by the ARC.

The ALARMSPACE software can be **installed on any Windows-based PC or virtual machine** within the ARC infrastructure.

{% hint style="success" %}
For installation, please **contact your VESTA representative**. Full support is provided for setup, configuration, and operational testing.
{% endhint %}

### _**4.6 Photo report**_.

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src="../.gitbook/assets/image (13) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>Settings -> Report</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (14) (2).png" alt="" data-size="original"></td><td>In the report section we have report configuration for events and captured files for PIRCAMS photos.</td><td></td></tr><tr><td><img src="../.gitbook/assets/image (16) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="original"></td><td>In this section we configure the report URL of our CRA for sending photos. APPENDIX 3 for examples</td><td></td></tr></tbody></table>

{% hint style="success" %}
Examples of **PHOTOS** reporting in different protocols:

:fire: **MANITOU**: <mark style="color:blue;">**ACCT**</mark>**@**<mark style="color:orange;">**IP**</mark>**:PORT**

**SMTP: Using email adress for ARC**&#x20;

**HTTP: Http post images in base64**
{% endhint %}



### 4.6.1 Photo report for SENTINEL software

{% hint style="info" %}
Step 1: Program SMTP information in settings -> Report&#x20;
{% endhint %}

<figure><img src="../.gitbook/assets/image (51) (1).png" alt=""><figcaption><p>Example</p></figcaption></figure>



{% hint style="info" %}
Step 2: Program the email provided by central monitoring station in "Captured files"
{% endhint %}

<figure><img src="../.gitbook/assets/image (52) (1).png" alt=""><figcaption></figcaption></figure>



{% hint style="warning" %}
**IMPORTANT:** If you use IP cameras integrated with VESTA, you have to lower the camera resolution to 2MP or lower for proper operation.
{% endhint %}

## Automation features

The panel has advanced automation functions that unlock a very high level of functionality designed to maximise the security of the system. These features allow, for example, the creation of rules where opening a door contact automatically captures an image or triggers a relay to open or close specific circuits. These capabilities not only improve system efficiency, but also provide a quick and appropriate response to security events.

{% hint style="success" %}
**Number of rules and scenes that can be created:**\


* Rules: 100
* Scenes: 50



Find out more: [Scenes and automatic rules of the VESTA Alarm System](https://vestasecurity.eu/en/scenes-and-automatic-rules-of-the-vesta-alarm-system/)
{% endhint %}

## COMPLETE INSTALATION MANUALS



<figure><img src="../.gitbook/assets/image (230).png" alt=""><figcaption><p>Hybrid Grade 3</p></figcaption></figure>

{% file src="../.gitbook/assets/Hybrid Panel-1_Installation Guide.pdf" %}





<figure><img src="../.gitbook/assets/image (231).png" alt=""><figcaption><p>Hybrid Lite</p></figcaption></figure>

{% file src="../.gitbook/assets/Hybrid Panel Lite 2G 4G _Installation Guide.pdf" %}



<figure><img src="../.gitbook/assets/image (232).png" alt=""><figcaption><p>Radio panels</p></figcaption></figure>

{% file src="../.gitbook/assets/HSGW-MAX8-DT18-SF1-DUAL 20220811.pdf" %}







