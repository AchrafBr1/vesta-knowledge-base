# VESTA-357

**VST-892EX-BUS**

## **BUS Wired Outdoor PIR Motion Sensor Camera**&#x20;

<figure><img src=".gitbook/assets/image (14) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

VST-892EX-BUS is a wired outdoor passive infrared (PIR) motion sensor camera. It is capable of sending wired signals and captured images (picture quality of up to 640 x 480 pixels) over BUS to the Control Panel upon movement detection.

Featuring night illumination capability, with a UV resistant housing, and waterproof to IPX6 standard, VST-892EX-BUS is ideal for backyards, lawns, gates, outdoor corridors and hallways.

The outdoor PIR Camera is designed with a typical detection range of 10 meters when mounted at a height of 2.3 meters above the ground. It provides pet-immunity for pets of up to 60 kilos with three selectable sensitivity levels to adapt to different environments.

In addition, VST-892EX-BUS is designed with the digital proximity detector. The anti-masking feature allows for detection of any attempts to blind the detector by placing objects in its field of view.

Remote configuration is supported for the PIR motion sensor camera. Besides adjusting the DIP Switch, users can also enable/disable the double knock function and pet immunity, and adjust the sensitivity of the PIR Camera from the Control Panel webpage or Home Portal Server.

## _**Identifying the Parts**_

![](<.gitbook/assets/1 (2) (1) (1).jpeg>)

1. **Digital Proximity Detector**

The digital proximity detector is used to detect any masking (blocking) attempt by an intruder.

2. **LED Indicator (Red)**

The LED indicator is used to indicate the system status.

3. **Flash LED**

The Flash LED delivers sufficient light for image capture under low lighting condition.

4. **IR Sensor**

The sensor is intended to detect moving objects.

5. **PIR Camera Lens**
6. **Internal Tamper**
7. **Test & Learn Button**

\- Press the button once to enter test mode for 10 minutes.

8. **DIP Switch Block**

There are 8 DIP Switches for setting the function & detection sensitivity levels.

9. **Terminal Resistor Jumper Switch**

When the PIR motion sensor camera is connected as the furthest BUS device on a BUS line, please set the PIR motion sensor camera 's terminal resistor jumper and the first BUS device’s (usually the Hybrid Panel’s) Jumper Switch to ON to serve as terminating resistors. The connected BUS line’ communication ability will be enhanced.

**Jumper On:** The jumper link is inserted, connecting the two pins.

**Jumper Off:** The jumper link is removed or “**parked**” on one pin.

* If the jumper is OFF, the communication ability is in normal level.
* If the jumper is ON, the communication ability will be enhanced.

10. **BUS Terminal**
11. **BUS Wiring Hole**
12. **Mounting Bracket**
13. **Hooks**
14. **Mounting Holes**

## _**LED Indicator**_

When enabled, the LED Indicator will light up in the following conditions:

* When the PIR Camera is in fault conditions (tamper open or continuing masking conditions), every time it transmits a detected movement, the LED will flash once.
* After the test button is pressed once to enter Test Mode, the LED will flash for 60 seconds to indicate that the PIR motion sensor camera is warming up.
* In Test mode, the LED will flash once whenever a movement is detected.

The LED will not flash if the PIR Camera is normal and is not under test mode.

{% hint style="warning" %}
Note:

The LED indicator can be enabled by setting the DIP Switch 2 to ON position. Please refer to **DIP Switch Position Table** below for details.
{% endhint %}

* The LED indicator can be enabled by setting the DIP Switch 2 to ON position. Please refer to **DIP Switch Position Table** below for details.

## _**Image Capture**_

When the alarm system is armed, the PIR Camera will capture 1, 3 or 6 alarm images with resolution of 640 x 480 or 320 x 240 (programmable from the Control Panel) upon movement detection. You can also manually request the PIR Camera to take a picture through the Control Panel. The captured images will be transferred to the Control Panel for visual alarm verification.

{% hint style="warning" %}
Note:

If your PIR Camera is installed at a location where the camera’s field of view is a complex environment with intense light or lots of colors, the images captured will be great in file size, possibly leading to truncation when the images are transmitted to the Control Panel.
{% endhint %}

## _**Warm Up Period**_

The PIR Camera will warm up for 60 seconds when the PIR Camera is turned on by the Control Panel upon entering armed mode.

## _**Test Mode**_

* The PIR Camera can be put into Test mode for 10 minutes by pressing the test button once.
* In Test Mode, the image capture functions are disabled. The LED indicator will flash once whenever a movement is detected.
* The PIR Camera will automatically exit Test Mode after 10 minutes and return to normal mode.
* In Test Mode, the LED indicator must be enabled by setting the DIP Switch 2 to ON position, and the Double Knock function must be disabled by setting the DIP Switch 7 to OFF position, for the users to test the detection range.

## _**Double Knock Function**_

* The PIR Camera has a double knock function. If the double knock function is enabled, the PIR Camera will report an alarm to the control panel only if two movements are detected within 10 seconds. If the double knock function is disabled, the PIR Camera will report an alarm to the Control Panel when a movement is detected.

## _**DIP Switch Position Table**_

The function of each DIP Switch is listed in the table below. The DIP Switch is either ON or OFF. Top position indicates ON, and bottom position indicates OFF.

<figure><img src=".gitbook/assets/10 (93).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Note:

After changing the Dip Switch settings, please re-power on the PIR Camera to apply new Dip Switch settings.
{% endhint %}

## _**Remote Setting**_

* The PIR motion sensor camera supports remote setting of the double knock function, sensitivity and pet immunity.
* When the PIR camera is powered on, its double knock function is determined by DIP SW7 setting, sensitivity is determined by DIP SW5 & SW6, and pet immunity is determined by DIP SW8. Users can either adjust the DIP Switch settings or remotely change the double knock function, sensitivity and pet immunity settings in the Control Panel webpage or Home Portal Server. Remote setting will overwrite the DIP Switch settings.

### **Control Panel Webpage**:

1. On the Panel’s local webpage, go to the Edit Device page and input the PIR camera configuration in the Sensor Setting section. Click OK to confirm.

Please refer to the table below for configuration details. For example, if you want to disable double knock function and set Sensitivity level to Low, you can input 00.

| **IR Configuration** | **Double Knock** | **Sensitivity**       | **Pet Immunity** |
| -------------------- | ---------------- | --------------------- | ---------------- |
| 00                   | No               | Low                   | Yes              |
| 20                   | No               | Medium                | Yes              |
| 40                   | No               | High                  | Yes              |
| 60                   | No               | Pet immunity disabled | No               |
| 80                   | Yes              | Low                   | Yes              |
| A0                   | Yes              | Medium                | Yes              |
| C0                   | Yes              | High                  | Yes              |
| E0                   | Yes              | Pet immunity disabled | No               |

### **Home Portal Server**:

1. On Home Portal Server, go to the Device Setting page, click the VST-892EX device row and select “IR Configuration.”
2. Select the Double Knock function (Enable/Disable), Sensitivity (High/Medium/Low), and Pet immunity (Enable/Disable) from the drop-down menu, and click “Submit” to confirm the setting.

## _**Supervision Signal**_

* After installation, the PIR Camera will automatically transmit Supervisory signals periodically to the Control Panel at random intervals of 20-30 seconds.

## _**Tamper Protection**_

* The PIR Camera is protected by an internal tamper switch which is compressed when the PIR Camera is hooked onto the mounting bracket. When the PIR Camera is removed from the mounting bracket, the tamper switch will be activated and the PIR Camera will send a tamper open signal to the control panel to remind the user of this condition.

## _**Anti-Masking**_

* The PIR Camera has a digital proximity detector that can detect any masking (blocking) attempts by an intruder.
* When a masking event is detected, and the masking condition lasts for 3 minutes, VST-892EX-BUS will send a masking alarm signal to the Control Panel to notify user of the masking condition.
* After masking/blocking is removed for 3 minutes, VST-892EX-BUS will send a restore signal to the Control Panel.

## _**Power Supply**_

* When VST-892EX-BUS is hardwired to a Hybrid Panel, 13.5V power supply can be provided by the Hybrid Panel.

{% hint style="danger" %}
_**Caution**_&#x20;

* Wiring of the PIR camera should only be performed by certified technicians with proper knowledge and training in electric equipment.
* Before installation or any maintenance work, make sure the power supply has been disconnected.
{% endhint %}

## _**Outdoor PIR Camera Wiring**_

* Before connecting the PIR Camera to the system bus, please switch the power off.
* To assist with cable connections, the terminal blocks on each BUS system module are color-coded.

<figure><img src=".gitbook/assets/10 (90).png" alt=""><figcaption></figcaption></figure>

* Multiple BUS devices can be connected in series to the Hybrid Panel. For optimal communication of the connected BUS line devices, ensure the terminal resistor jumper switches of the first (usually the Hybrid Panel) and the furthest BUS devices on a BUS line are set to ON to serve as terminating resistors. Be sure to only enable the aforementioned 2 jumper switches, and do not set the jumper switches to ON for any other BUS devices in between.

{% hint style="warning" %}
Note:

The pluggable design of BUS terminal blocks improves upon installation efficiency. Before wiring, you can remove the terminal blocks from the PCB board for ease of use, and plug in again after wiring.

After unplugging the terminal, when re-installing the terminal back to the board, make sure to install the terminal in the same direction to avoid potential hazards
{% endhint %}

* Incorrect connections will result in failure or improper operation. Inspect wiring and ensure proper connections before applying power.

<figure><img src=".gitbook/assets/10 (6).png" alt=""><figcaption></figcaption></figure>

## _**Getting Started – Learning the PIR Camera into the Control Panel**_

Please follow the steps below to learn the device into the Hybrid Panel.

Step 1. Connect the device to the Panel. Then, power the Panel on.

Step 2. On the Panel’s webpage, click “**Learning**” to enter learn page.

Step 3. Click “**Start**” to enter learning mode.

Step 4. Click “**Add**” to include the device into the Panel.

Step 5. If the device is successfully learnt into the Panel, it will be displayed in the “Learned Device” section.

### _**Identification**_

The “**Identify**” function is used to localize a specific BUS device in the BUS wired system. This function is helpful in distinguishing which device is which especially in a large installation where numerous BUS devices are included.

To locate the PIR Camera in the BUS system:

**Step 1.** On Hybrid Panel’s webpage, click “Identify” under the device list after the IR Camera’s device column entry.

**Step 2.** If the PIR Camera receives the signal from the Hybrid Panel, the webpage will display a success message and PIR Camera’s LED indicator will flash 10 times to indicate where it is to the user.

{% hint style="warning" %}
Note:

If a timeout message is displayed on the webpage, it means the PIR Camera did not receive the signal from the Panel. Please check whether the PIR Camera is connected properly to the Panel within appropriate wiring distance.
{% endhint %}

### _**Walk Test**_

* To make sure the PIR Camera is able to communicate with the Panel after it is learned-in, place the Control Panel in Walk Test mode and press the test button on VST-892EX-BUS to transmit a test signal to the Panel.
* When the Panel receives the test signal, it will beep once and display the PIR Camera’s information accordingly on the top of the device list.

{% hint style="warning" %}
Note:

If there is no response from the Panel after the press of test button, it means the Panel did not receive the test signal from the device. Please check whether the PIR Camera is connected properly to the Panel within appropriate wiring distance.
{% endhint %}

## _**Mounting & Installation Method**_

* **Mounting with the mounting bracket:**
  * The PIR Camera can be mounted on a flat surface with the fixing screws, wall plugs, and the mounting bracket provided.
  * The provided mounting bracket has knockouts, where the plastic is thinner and can be broken for mounting purpose.

<figure><img src=".gitbook/assets/10 (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

*   To mount VST-892EX-BUS with the mounting bracket:

    1. Use the mounting bracket as a template and drill 2 holes on the wall for the wall plugs.
    2. Push in the wall plugs and fix the mounting bracket on the wall with the screws.
    3. Hook VST-892EX-BUS on the mounting bracket and then **push downwards until you hear a click sound**.


*

    <figure><img src=".gitbook/assets/11 (2).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Note:

Please make sure the PIR Camera is properly hooked onto the mounting bracket, so that the internal tamper switch is fully depressed.
{% endhint %}

* **Mounting with the mounting bracket and rotating holder:**

A rotating holder is provided as a user-friendly mounting option **(optional item, sold separately)**. It is comprised of a base to fix to a surface, and a swivel ball to fix the mounting bracket to the rotating holder.

With the rotating holder, the PIR Camera can be rotated horizontally to provide the optimal coverage.

<figure><img src=".gitbook/assets/10 (2) (1) (1).png" alt=""><figcaption></figcaption></figure>

A special screwdriver with a reversible double-sided bit and three star socket screws are provided for fixing the rotating holder to the wall. Please use the provided screwdriver to tighten/loosen the star socket screws.

<figure><img src=".gitbook/assets/10 (3) (1).png" alt=""><figcaption></figcaption></figure>

* To mount VST-892EX-BUS with the mounting bracket and rotating holder:

1. Fix the rotating holder to the wall with the provided screws.
2. Fix the mounting bracket on the swivel ball with the fixing screw secured through the foolproof design hole.
3. Hook VST-892EX-BUS onto the mounting bracket and then push downwards until you hear a click sound.
4. Rotate the swivel ball horizontally to adjust VST-892EX-BUS’s detecting angle. (When the angle adjusting screw is half loosen, the swivel ball can still be rotated.)
5. When VST-892EX-BUS is rotated to a position with desired detection coverage, you can lock the position by firmly tightening the angle adjusting screw.

<figure><img src=".gitbook/assets/10 (4) (1).png" alt=""><figcaption></figcaption></figure>

* _**Installation Recommendations**_

**It is recommended installing the PIR Camera in the following locations:**

* At a height of 2.3 meters (measured from the bottom of the camera) above the ground level for best performance
* In a corner for the widest view
* At a place where an intruder would normally move across the PIR Camera’s field of view
* On a surface or in a corner where animals are inaccessible
* The PIR Camera has a detection range of 10 meters when mounted at the height of 2.3 meters above the ground.

<figure><img src=".gitbook/assets/10 (5) (1).png" alt=""><figcaption></figcaption></figure>

**Limitations:**

* Do not expose the PIR Camera completely to direct sunlight.
* Avoid large obstacles in the detection area.
* Do not face heat sources such as fires and boilers, directly or install above radiators.
* Never attempt to disassemble or modify the device.
* Please install the PIR Camera straight up. Do not tilt it.

<figure><img src=".gitbook/assets/10 (6) (1).png" alt=""><figcaption></figcaption></figure>

* Do not install the motion sensor camera where objects are moved by the wind, such as trees and laundry, which may block the motion sensor camera’s field of view.

<figure><img src=".gitbook/assets/10 (7).png" alt=""><figcaption></figcaption></figure>

* Clear all light-reflecting surfaces from the detection area, as well as water puddles.

<figure><img src=".gitbook/assets/10 (8).png" alt=""><figcaption></figcaption></figure>

* Avoid aiming at the path of an outdoor unit’s intake or exhaust airflow.

<figure><img src=".gitbook/assets/10 (9).png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
_IMPORTANT NOTE_

* Adjust the Dip Switches according to the installation location of the PIR Camera for ideal performance. If the Dip Switch settings does not match with the installation environment, the PIR Camera’s performance will be hindered and may cause either false alarm or inability to detect movement.
* The PIR Camera detects differences between the moving object and the background. If the object is idle (i.e., not moving), the PIR Camera is unable to detect it.
* The PIR Camera has a directional characteristic and is most effective at detecting intruders moving across its field of detection. It is less sensitive for detecting motions directly in front of the PIR Camera.
* For best performance, remember to adjust the mounting height of the motion sensor camera with respect to the height of the tallest pet in the house. Taller dogs require the motion sensor camera to be mounted higher for pet friendliness.
* The PIR Camera has a blind spot of about 1 meter under the camera when mounted at a height of 2.3 meters. The blind spot area will enlarge if the PIR Camera is mounted higher than the height of 2.3 meters, and reduce if mounted lower than this height.
* Unless required, it is suggested keeping the PIR Camera’s mounting location at the height of 2.3 meters for optimum performance. If you change the mounting height, please conduct detection test to make sure the PIR Camera can normally detect intruders at the chosen height.
{% endhint %}



