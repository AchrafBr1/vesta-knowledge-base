---
icon: puzzle-piece
---

# INTEGRATION WITH DAHUA IP CAMERAS

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" width="375"><figcaption></figcaption></figure>

{% hint style="success" %}
### 🎯 Introduction - Sync Real Snapshot with Alarm – Dahua Series 3 Cameras

VESTA can now display **the exact snapshot** taken by Dahua Series 3 cameras at the **very moment an IVS event is triggered** — such as line crossing or intrusion detection.

To make this work, a simple setup is required on the camera side. Once done, you’ll get **100% real-time visual confirmation** of the alarm cause, fully integrated into the VESTA ecosystem.

This guide explains how to configure your Dahua camera so that:

* 📷 It captures and stores real snapshots of IVS events.
* 🔄 VESTA receives those images automatically with each alarm.

Let’s get started. 👇
{% endhint %}

## Sync Real Snapshot with Alarm – Dahua Series 3 Cameras

To make sure VESTA receives **the real snapshot of the event** exactly when an IVS alarm is triggered (line crossing, region intrusion, etc.), follow these simple steps:

{% stepper %}
{% step %}
#### Step 1 – Update Camera Firmware

Make sure the Dahua camera has the latest firmware.

<a href="https://drive.google.com/file/d/1_E4gALQLkPwMRePfONcUMF9Gx5o7KanM/view?usp=drive_link" class="button primary" data-icon="down-to-bracket">Download Firmware update</a>
{% endstep %}

{% step %}
#### Step 2 – Insert a microSD Card

Insert a **microSD card** into the camera. (_This is where the real image will be stored._)
{% endstep %}

{% step %}
#### Step 3 – Enable Snapshots in IVS

* Go to the **IVS settings** of the camera.
* Edit each rule (Line Crossing, Intrusion, etc.).
* Enable **“Snapshot Capture”** for each rule.

This allows the camera to **save a real image** when an event is triggered.

<figure><img src="../.gitbook/assets/image (352).png" alt="Alarm Image in VESTA " width="375"><figcaption><p>Alarm first Image in VESTA system</p></figcaption></figure>
{% endstep %}
{% endstepper %}

***

### Compatible Models (Series 3)

* DAHUA-4670 - DH-IPC-HFW3449T1P-AS-PV-0280B-S5-Black
* DAHUA-4558 - DH-IPC-HDW3849HP-AS-PV-0280B-S5-B
* DAHUA-4297N - DH-IPC-HDW3449HP-AS-PV-0280B-S5-B
* DAHUA-4667 - DH-IPC-HFW3549T1P-AS-PV-0280B-S5
* DAHUA-4547 - DH-IPC-HFW3849T1P-AS-PV-0280B-S5-B
* DAHUA-4543 - DH-IPC-HDW3549HP-AS-PV-0280B-S5-BLACK
* DAHUA-4454 - DH-IPC-HDW3549HP-AS-PV-0280B-S5
* DAHUA-4436 - DH-IPC-HFW3849T1P-AS-PV-0280B-S5
* DAHUA-4401 - DH-IPC-HFW3449T1P-AS-PV-0280B-S5
* DAHUA-4400 - DH-IPC-HDW3849HP-AS-PV-0280B-S5
* DAHUA-4399 - DH-IPC-HDW3449HP-AS-PV-0280B-S5
* DAHUA-4602 - DH-IPC-HFW3449T1-ZAS-PV-27135-S5-B
* DAHUA-4606 - DH-IPC-HDBW3849R1P-ZAS-PV-27135-S5
* DAHUA-4588 - DH-IPC-HDBW3449R1P-ZAS-PV-27135-S5
* DAHUA-4457 - DH-IPC-HFW3849T1P-ZAS-PV-27135-S5
* DAHUA-4386 - DH-IPC-HDW3549HP-ZAS-PV-27135-S5
* DAHUA-4766-FO - DH-IPC-HDBW3549R1P-ZAS-PV-27135-S5
* DAHUA-4561 - DH-IPC-HDW3449HP-ZAS-PV-27135-S5-Black
* DAHUA-4560 - DH-IPC-HDW3849HP-ZAS-PV-27135-S5-Black
* DAHUA-4557 - DH-IPC-HFW3449T1P-ZAS-PV-27135-S5-BLACK
* DAHUA-4455 - DH-IPC-HFW3449T1P-ZAS-PV-27135-S5
* DAHUA-4453 - DH-IPC-HDW3449HP-ZAS-PV-27135-S5
* DAHUA-4116N - DH-IPC-HDW3849HP-ZAS-PV-27135-S5

> ℹ️ Firmware for series 2: [Download FIRMWARE](https://drive.google.com/drive/folders/1thS-QK6UmKX14amsHNiuCVVx--nTSaMI)



***

## Integration **DAHUA**:

_**If the camera has a disarm function**_

\- The Vesta panel will be able to control the arming and disarming of the IVS, therefore, functions such as lights and sound, for example, when crossing a line, will follow the arming and disarming of the panel.

\- Alarm activation and captures will function normally.

_**If the camera does not have a disarm function**_

\- In this case, control over the IVS is lost, so it will always be activated. Even if the Vesta panel is disarmed, the lights and sound will always activate, as the panel cannot control them.

\- The camera functions the same whether the panel is armed or disarmed.

_**Image capture time**_

The correct capture time is between 1 and 3 seconds. A capture time of about 5 seconds or more indicates a slowdown in the network.

A practical way to determine this time is by executing an HTTP command, where we request a photograph. This command is as follows: http://user:password@CAMERA\_IP/cgi-bin/snapshot.cgi?

Real example: http://admin:Admin1234@192.168.10.182/cgi-bin/snapshot.cgi?

_**DAHUA P2P Camera**_

With SmartHomeSec, you can add the camera to a zone using its serial number (P2P ID). This will allow the master or slave user with permission to view the live video from the app itself. Therefore, it is essential to first add the camera to the VESTA panel, and then, if video recording is required, integrate it via its IP address with a Dahua recorder. Image recording can also be done locally by inserting a micro SD card into the camera itself.

_**\<Note>**_

• The VESTA system works with photos, not videos, so the relevant settings must be made in the zone where the camera was added.

_**Time between alarms**_

For proper verification, allow 3 minutes between detections.
