---
description: >-
  The VESTA Home series are a range of wireless security cameras designed for
  both indoor and outdoor use. They provide reliable video surveillance with
  easy installation.
icon: camera-cctv
---

# SETUP VESTA Home IP CAM

<figure><img src="../.gitbook/assets/image (379).png" alt=""><figcaption></figcaption></figure>



{% hint style="info" %}
We will show how to add the camera Vesta-292, but the steps to add the camera Vesta-291 or Vesta-293 are similar
{% endhint %}

## Camera 292

<figure><img src="../.gitbook/assets/1 (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

#### STEP 1:  Plug the power cable&#x20;

#### STEP 2: Wait for the LED to remain in solid <mark style="color:green;">GREEN</mark> colour for Ethernet connection or flashing  <mark style="color:green;">GREEN</mark> in case of Wi-Fi Setup

Use the SmartHomeSec app to initialise the camera and **add** it to the system

<figure><img src="../.gitbook/assets/100 (1).png" alt=""><figcaption><p>STEP 1                                                                STEP 2                                                           STEP 3</p></figcaption></figure>

### STEP 1: Login as User in the SmarthomeSec App

### STEP 2: Press Camera logo

### STEP 3: Press + Icon to add a camera

<figure><img src="../.gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>STEP 4                                                                                                             STEP 5 </p></figcaption></figure>

### STEP 4: Press the VESTA/Imou icon

### STEP 5: Scan the Camera QR code and press NEXT&#x20;

### STEP 6: Select how to add the camera:

* &#x20;Add to the equipment: The camera must be installed on the same panel LAN network. In this way, the camera will be fully supported in the panel and the user app.&#x20;

{% hint style="success" %}
Vantages to add to the equipment:

* The camera will be an intrusion zone in the panel, and it can generate alarms.
* SD-CARD video recording access
* Movement detection.
* PTZ control for the VESTA-292
{% endhint %}

<figure><img src="../.gitbook/assets/image (4) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>STEP 6</p></figcaption></figure>

* Add to the cloud: The camera will be installed using the cloud. The user will see the live video only from the user's app account.

{% hint style="success" %}
Vantages to add to the cloud:

* The camera can be installed on a different network (or at a different site).
* Users with panels connected with 4G communication only, can have cameras connected to their accounts.
{% endhint %}

### STEP 7: Choose the communication path of the camera (Ethernet or Wi-Fi)

{% hint style="warning" %}
The camera and the panel must be on the same network, please check before proceeding&#x20;
{% endhint %}

<figure><img src="../.gitbook/assets/102.png" alt=""><figcaption><p>STEP 7</p></figcaption></figure>

{% hint style="info" %}
In case of Ethernet communication, jump directly to STEP 12
{% endhint %}

### STEP 8: Wi-Fi connection

{% hint style="warning" %}
The mobile must be connected to the Wi-Fi network that you want to connect the camera
{% endhint %}

<figure><img src="../.gitbook/assets/102.2.png" alt=""><figcaption><p>STEP 8                                                                STEP 9                                                                 STEP 10</p></figcaption></figure>

{% hint style="info" %}
**If you're connecting your camera via Wi-Fi but it doesn't proceed to the IP search step, don't worry. This can happen if your mobile device temporarily lost internet connection while switching networks and didn’t reconnect properly.**

To continue:

* Check if the camera's <mark style="color:green;">**GREEN LED**</mark> is **solid ON** (not blinking).
* If it is, go back to the previous step and **select ETHERNET instead of Wi-Fi** — the setup should then work correctly.

![](<../.gitbook/assets/image (351).png>)
{% endhint %}

### STEP 9: Connect your mobile to the camera network by pressing join

### STEP 10: Select the network and press Next

<figure><img src="../.gitbook/assets/103.png" alt=""><figcaption><p> STEP 11                                                                STEP 12                                                                    STEP 13</p></figcaption></figure>

### STEP 11: Write the Wi-Fi password

### STEP 12: The app will show you the camera userID and password

<figure><img src="../.gitbook/assets/104.png" alt=""><figcaption><p>STEP 12                                                                                                                                                  </p></figcaption></figure>

{% hint style="warning" %}
Note:

If the password field is not automatically filled:&#x20;

UserID: admin

Password: (Safety code of the camera, label below)
{% endhint %}

<figure><img src="../.gitbook/assets/image (12) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Password</p></figcaption></figure>

SETUP COMPLETED

<figure><img src="../.gitbook/assets/21.jpg" alt="" width="185"><figcaption></figcaption></figure>

***

### **How to Enable Camera Notifications When the System is Disarmed**

The **VESTA HOME / ADV cameras** allow you to receive notifications even while the system is disarmed. This can be useful if you want to stay aware of movement in certain areas without arming the entire system.

#### Steps to Configure:

1. Go to the Settings --> Device -->  **Camera settings** in the app SmartHomeSec.
   1.

       <figure><img src="../.gitbook/assets/image (1) (1) (2).png" alt=""><figcaption></figcaption></figure>
2. Locate the option **Chime as Attribute during Disarm**:&#x20;
   1.

       <figure><img src="../.gitbook/assets/image (1) (1) (2) (1).png" alt=""><figcaption></figcaption></figure>
3. Enable this option on the camera.

#### What Happens Next:

* The system will stay in **alert mode** even when disarmed.
* If the camera detects activity, you will receive a **push notification**:
  * _Human Detected / Motion Detected_

⚠️ **Important:** In this mode, the camera **will not capture images**. You will only get the push notification. You can then open the live stream manually if you want to check what’s happening.



{% hint style="success" %}
**Note:**\
By default, **VESTA Home cameras** use a filtering system where a person must remain in the scene for **30 seconds** before an event is reported to the panel.

This behavior can be modified by adding the camera to the **SmartPSS software** and adjusting the motion detection "Anti-Dither" setting to **1 second**, allowing for almost immediate event reporting

The Anti-Dither option determines how long a movement must last in the scene to be considered as such.
{% endhint %}

<figure><img src="../.gitbook/assets/image (369).png" alt="The Anti-Dither option"><figcaption></figcaption></figure>

{% hint style="info" %}
Additionally, between detections the camera has a **sleep time of 3 minutes**, meaning that continuous motion will only trigger one event every 3 minutes.
{% endhint %}

{% hint style="success" %}
#### Coming Soon:

The platform will soon support a new attribute: **Notifications with Image**. Once available, you will not only get the notification but also a snapshot from the camera directly in the alert.
{% endhint %}

***

## TROUBLESHOOTING&#x20;

### **I cannot find the IP of the camera on the setup steps:**

1\.   Ensure that the VESTA central controller is connected to the same network as the camera.

2\.   Restart the switch or router where the VESTA panel and Camera are connected.

{% hint style="success" %}
### **IP Detection Issue During Camera Setup**

Sometimes, when you reach the **IP detection step**, the panel may not find any devices during the scan. If this happens, and you have already configured the camera via **Wi-Fi**, check the following:

#### Scenario

* You used **Wi-Fi setup** as the connection method.
* The camera shows a **solid green LED**, meaning it is already connected to the Wi-Fi network.
* However, when the panel scans for IP devices, nothing appears.

#### Solution

To avoid repeating the entire setup process, do the following:

1. Go back to the step where you select the **connection method**.
2. Scan the **QR code** again.
3. Instead of selecting _Wi-Fi_, choose **Ethernet**.

![](<../.gitbook/assets/image (2) (3).png>)

#### Why?

Even though the camera is connected via Wi-Fi, selecting **Ethernet** in this step allows the panel to correctly detect the camera on the network without forcing you to reconfigure everything.
{% endhint %}

***

### **I cannot complete the setup via WIFI**

1\.   Check that you have the latest firmware in the VESTA control unit.

2\.   Make sure to enable the location for the SmartHomeSec APP.

3\.   Make sure you give the APP permissions to connect to a WIFI network, and if it asks for connection permissions allow them.

***

### **The camera is not ready:**

1. Reset the camera to factory settings

To reset the VESTA camera:  Press the button RESET located on the back and hold for 10 seconds (The camera will make a BEEP and the LED will turn red) NOTES: In the VESTA-292 model, the button is located under the optics

<figure><img src="../.gitbook/assets/Immagine1.png" alt="" width="375"><figcaption></figcaption></figure>
