---
icon: video
---

# VESTA ADVANCED IP CAMERA SERIES (With SmartHomeSec)

## ✨ Are you ready to discover the new VESTA ADVANCED SERIES cameras?

{% embed url="https://drive.google.com/file/d/1snvNV-L2JUDdsPN4qwz1_Xb32DzoiepE/view?usp=sharing" %}

### What does this VESTA integration allow?

<figure><img src="../.gitbook/assets/image (276).png" alt=""><figcaption></figcaption></figure>

### **Start-up with VESTA panels in 3 steps**

{% stepper %}
{% step %}
### Upgrade the IP cam ([Clic here for the QUICK VIDEO](vesta-advanced-ip-camera-series-with-smarthomesec.md#how-to-update-a-vesta-adv-camera-or-nvr-step-by-step))

To update the camera, follow these steps:

1.  **Download the Firmware**: Ensure you download the firmware that matches your camera model from the following list according to your model:\


    <table><thead><tr><th>Models</th><th width="114">Firmware</th></tr></thead><tbody><tr><td><ul><li>IPC-T38-ZAS-PV-B</li><li>IPC-T38-ZAS-PV</li><li>IPC-B38-ZAS-PV-B</li><li>IPC-B38-ZAS-PV</li></ul></td><td><a href="https://gofile.me/7yryF/u9fVnKEjg">Download</a></td></tr><tr><td><ul><li>IPC-T35-AS-PV-B</li><li>IPC-T35-AS-PV</li><li>IPC-B35-AS-PV-B</li><li>IPC-B35-AS-PV</li></ul></td><td><a href="https://gofile.me/7yryF/LJPMxKDbU">Download</a></td></tr><tr><td><ul><li>IPC-D24-ZAS-L-B</li><li>IPC-D24-ZAS-L</li></ul><ul><li>IPC-T24-L</li><li>IPC-B24-L</li></ul></td><td><a href="https://gofile.me/7yryF/HYczagZrp">Download</a></td></tr></tbody></table>


2. [**Access Local Interface**](vesta-advanced-ip-camera-series-with-smarthomesec.md#quick-login-to-local-portal): Navigate to the camera's local interface (Default IP: _192.168.1.86_).
3. **Navigate to Setup**: Go to 'Setup' in the menu.
4. **Select System**: Choose 'System' from the options.
5. **Choose Upgrade**: Proceed to 'Upgrade' to begin the firmware update process.

<figure><img src="../.gitbook/assets/image (275).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Panel and SmartHomeSec APP upgrade

{% hint style="info" %}
It is important to ensure that the **panel is at version 34F or higher** and that the **application is updated to version 3.6.0 or higher**. These updates include this integration. Check and update regularly to maintain compatibility and optimal performance of your devices.
{% endhint %}
{% endstep %}

{% step %}
### Adding the camera to the panel

1. **Network Verification:** Ensure that both the VESTA panel and the camera are connected to the same network.
2. **SmartHomeSec APP Setup:**
   * Open the app and log in using your **Master account** credentials.
   * Navigate to the "**Cameras**" section and select "**VESTA ADVANCED**."
3. **Camera Scanning:**
   * The system will begin **scanning for new cameras on the network automatically**.
4. **Camera Selection:**
   * Choose the camera from the list, and input the **username and password**. Use the same credentials you use for accessing the camera's web server locally.
{% endstep %}
{% endstepper %}

<figure><img src="../.gitbook/assets/ADV-settings.gif" alt=""><figcaption></figcaption></figure>



## Quick videos

### How to update a VESTA ADV camera or NVR – Step by step

{% embed url="https://www.youtube.com/watch?v=XrwbhkilqVs" %}

### How to program IVS rules in VESTA ADV&#x20;

**Intelligent Video Surveillance (IVS) Rules** are advanced video analysis algorithms used to enhance the functionality of your VESTA ADV camera or NVR. These rules allow the system to automatically detect and respond to specific events, improving security and reducing false alarms. Common IVS rules include:

1. **Intrusion Detection:** Alerts when an object/human enters a predefined zone.
2. **Tripwire:** Triggers when an object/human crosses a defined line.
3. **Cross region:** Triggers when an object/human crosses or appears in a defined area.

To program IVS rules in your VESTA ADV system follow this steps:&#x20;

{% embed url="https://youtu.be/2tznoM9PdzM" %}

### How to set up continuous recording on MicroSD of IP CAM:

**Enable Continuous Recording on MicroSD**

1. **Storage Configuration:**
   * Navigate to the **Storage** section.
   * Select **Destination** and ensure **Scheduled** is enabled.
   * In **Scheduled** make sure to enable 24h all days or needed days

<figure><img src="../.gitbook/assets/step-step-SD.gif" alt=""><figcaption></figcaption></figure>



### **Quick login to local portal:**&#x20;

{% hint style="success" %}
**Quick login to local portal:**&#x20;



**Step 1:** Open a browser, enter the device’s IP address in the address bar (the **default IP address is 192.168.1.86**), and press Enter.

**Step 2:** Enter the username and passwor&#x64;**; the default user name of the device is “admin”**.

![](<../.gitbook/assets/image (216).png>)

**Step 3:** When logging in to the device for the first time, the system will pop up a “Change Password” prompt. Please change the administrator password on time and safe-keep it.

![](<../.gitbook/assets/image (217).png>)



**Reset Password:** If the user forgets the password, click Reset Password to get a key. After the customer sends this key to our technician, our technician will generate a new decoding key for the user, and the password will be reset to **the default password “123456”.**
{% endhint %}





### VESTA advanced series complete manual guide&#x20;

{% file src="../.gitbook/assets/VESTA Advanced Series .doc" %}

### Quick Guide

{% file src="../.gitbook/assets/Quickly User Manual v25.pdf" %}

***

## **Camera Troubleshooting and Configuration Issues**

### **CGI Activation Issues:**

![](<../.gitbook/assets/image (4) (4).png>)\
\
If the panel prompts you to enable CGI on the camera (And CGI already activated), this may be due to changes in user settings. This can happen if:

* A client manually modified user settings on the camera (Changed admin rights).
* The camera was added to a third-party recorder, which initialized it in a way that altered user data.

**Solution:**\
Reset the camera to factory settings. After the reset, the camera will function correctly.\
&#xNAN;_(Note: This issue is typically related to modifications in the Users settings.)_

