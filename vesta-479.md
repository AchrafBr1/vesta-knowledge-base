# VESTA-479

**VST-897EX-Solar Series**

## **Outdoor PIR Motion Sensor Camera**

<figure><img src=".gitbook/assets/image (1303).png" alt=""><figcaption></figcaption></figure>

The VST-897EX-Solar Series is an advanced outdoor passive infrared (PIR) motion sensor camera, designed to enhance security with high-definition image transmission (up to 1280 x 720 pixels) upon motion detection. It includes a rechargeable battery powered by solar charging, with two 1.5V L91 lithium batteries as backup.

The HaLow model, equipped with Sub-GHz Wi-Fi and an SF1 backup module, ensures rapid processing for faster visual alarm verification.

Built to withstand outdoor conditions, the VST-897EX-Solar features night illumination, UV-resistant housing, and IPX6 waterproofing, making it suitable for areas like backyards, gates, and outdoor corridors. The HDR model adds white balance with HDR support for clearer images in high-contrast lighting conditions.

With a typical detection range of **10 meters** when mounted at **2.3 meters** above ground, it offers pet immunity up to 20 kilos and three selectable sensitivity levels for different environments.

The camera incorporates anti-masking detectors an advanced anti-masking feature, capable of detecting attempts to obscure the lens using objects or coatings within 20cm. Infrared technology further enhances anti-masking through over-the-lens detection.

**The VST-897EX-Solar Series includes the following models:**

<figure><img src=".gitbook/assets/image (1304).png" alt=""><figcaption></figcaption></figure>

## Identifying the Parts

<figure><img src=".gitbook/assets/Unknown image (445)" alt=""><figcaption></figcaption></figure>

1. **Flash LED / Infrared LED**

&#x20;The Flash LED or Infrared LED delivers sufficient light for image capture under low lighting condition.

2. **IR Sensor**
3. **LED Indicator (Red)**

&#x20; For system status indication

4. **LED Indicator (Green)** **(for HaLow models only)**

* Lights up when searching for the HaLow-supported Control Panel
* Flashes rapidly for data transmission via Wi-Fi\*\*\*\*

5. **PIR Camera Lens**
6. **Charging Plates**
7. **Test & Learn Button**

* Press the button for 3 seconds to send a learn code, and then release the button when Red LED lights up.
* Press the button once to enter test mode for 10 minutes.
* Press the button once to send a learn code to the repeater / router.

8. **Hook Holes**
9. **Tamper Switch**
10. **Battery Compartment**
11. **Dip Switch Block**
12. **Battery Insulator**
13. **Rechargeable Battery**
14. **Solar Panel**
15. **Stabilizing Screw**
16. **Hooks**
17. **Corner Mounting Holes**
18. **Surface Mounting Holes**

## LED Indicator

When enabled, the LED Indicator will light up in the following conditions:

* When the Tamper Switch is triggered, the LED will flash for 2 seconds to indicate it is transmitting “**Tamper**” signal.
* When the PIR Camera is in fault conditions (tamper open or low battery condition persists), each time it transmits a detected movement, the LED will flash for 2 seconds.
* In Test mode, the LED will turn on for 2 seconds whenever a movement is detected.

The LED will not flash if the PIR Camera tamper and battery are normal and it is not under test mode.

If the LED flashes to indicate signal transmission, it will flash twice rapidly upon receiving acknowledgement from panel.

{% hint style="info" %}
Note: The LED indicator can be enabled by setting the DIP Switch 2 to ON position. Please refer to **DIP Switch Position Table** for details.
{% endhint %}

## Image Capture

When the alarm system is armed, the PIR Camera will capture alarm images in resolution 1280 x 720 pixels, 640 x 480 or 320 x 240 pixels (programmable from Control Panel) upon movement detection. You can also manually request the PIR Camera to take a picture through the Control Panel. The captured images will be transferred to the Control Panel for visual alarm verification.

{% hint style="info" %}
Note: If your PIR Camera is installed at a location where the camera’s field of view is a complex environment with intense light or lots of colors, the images captured will be great in file size, possibly leading to truncation when the images are transmitted to the Control Panel.
{% endhint %}

## Warm Up Period

When the PIR Camera is powered on, the PIR Camera will warm up for 30 seconds. During the 30-second warm-up period, the PIR Camera will not be activated.

## Test Mode

* Test Mode allows you to check the PIR Camera’s detection range (not shooting coverage).
* Press the Test / Learn Button once to enter Test mode for 10 minutes.
* During Test Mode, the sleep timer is disabled. You can trigger the PIR Camera to check the IR detection range. Each time the PIR Camera is triggered, the Red LED will turn on briefly (for 2 seconds).
* In Test Mode, the LED indicator must be enabled by setting the DIP Switch 2 to ON position, and the Double Knock function must be disabled by setting the DIP Switch 7 to OFF position, for the user to test the detection range.

## Double Knock Function

* The PIR Camera has a double knock function. If the double knock function is enabled, the PIR Camera will report an alarm to the control panel only if two movements are detected within 10 seconds. If the double knock function is disabled, the PIR Camera will report an alarm to the control panel when a movement is detected.

## DIP Switch Position Table

The function of each DIP Switch is listed in the table below. The DIP Switch is either ON or OFF.      ON The upper position indicates ON and the lower position indicates OFF.

![](<.gitbook/assets/Unknown image (446)>)

<figure><img src=".gitbook/assets/image (1305).png" alt=""><figcaption></figcaption></figure>

After changing Dip Switch settings, please re-power on the PIR Camera for it to operate with new Dip Switch Settings.

## Supervision Signal

* After installation, the PIR Camera will automatically transmit Supervisory signals periodically to the Control Panel at random intervals of 15 to 18 minutes.
* If the Control Panel has not received the signal from the PIR Camera for the preset period of time, the Control Panel will indicate on its display that the particular PIR Camera is experiencing an out-of-signal problem.

## Sleep Timer

* The PIR Camera has a “sleep time” of approximately 1 minute to conserve power. After transmitting a detected movement, the PIR Camera will not retransmit for 1 minute.
* Continuous movement in front of PIR Camera will not unduly exhaust the battery.

## Tamper Protection

* The PIR Camera is protected by an internal tamper switch which is compressed when the PIR Camera is hooked onto the mounting bracket. When the PIR Camera is removed from the mounting bracket, the tamper switch will be activated and the PIR Camera will send a tamper open signal to the control panel to remind the user of this condition.

## Anti-Masking

* The PIR Camera has a digital proximity detector that can detect any masking (blocking) attempt by an intruder.
* When a masking event is detected, and the masking condition lasts for 3 minutes, the PIR Camera will send a masking alarm signal to the Control Panel to notify user of the masking condition.
* After masking/blocking is removed for 3 minutes, the PIR Camera will send restore signal to the Control Panel.

## Battery

* The PIR Camera includes a 3.2V 600mAh LFP (Lithium Iron Phosphate) rechargeable battery by solar charging, and two 1.5V, L91 Lithium batteries as backup.
* The PIR Camera features low battery voltage detection. When low battery is detected (from 1.5V, L91 Lithium batteries), a low battery signal will be sent to the Control Panel along with regular signal transmissions for the Control Panel to display the status accordingly.
* **To change the batteries (1.5V, L91 Lithium batteries):**

**Step 1:** Remove the PIR Camera from mounting position.

**Step 2:** Loosen the back cover fixing screw and open the back cover.

Step 3: Remove the old batteries and press the test button twice to fully discharge the power.

**Step 4:** Insert two new AAL91 lithium batteries.

**Step 5:** Press the test button once. A battery normal signal will be sent to the Control Panel.

**Step 6:** Screw back the back cover.

**Step 7:** Mount back the PIR Camera to mounting location.

## Getting Started – Learning the PIR Camera into the Control Panel

* Loosen the bottom fixing screw, and open the back cover.
* Insert four AAL91 lithium batteries into the battery holder taking care to connect the polarity correctly.
* Put the Control Panel into learning mode, refer to Control Panel manual for details.
* Press and hold the Test button for 3 seconds to send a learn code, and then release the button when Red LED lights up. (To learn into battery-operated panel, after pressing and holding the Test button for 3 seconds, please press the Test button again for one second.) The LED will be on for 20 seconds, indicating the PIR Camera is in learning mode.
* If the Control Panel receives the signal from the PIR Camera, it will display the information accordingly. Within 20 seconds when the LED of the PIR Camera is on, select the PIR Camera on the Control Panel Webpage and click **“add”** to include it into the Panel. Refer to the Control Panel manual for details.
* When the PIR Camera receives acknowledgement from the Control Panel, the LED of the PIR Camera will flash 6 times and then turn off to indicate successful learning.
* After the PIR Camera is learnt-in, put the Control Panel into Walk Test mode. Hold the PIR Camera in the desired location, and press the Test Button to confirm this location is within the signal range of the Control Panel.
* For Wi-Fi HaLow models, when the Control Panel is put to Walk Test mode, pressing the Test Button also initiate a Wi-Fi Walk Test. The PIR Camera’s Green LED will light up as it begins searching for a HaLow-supported Control Panel.

If a connection is established, the Green LED will flash rapidly during data transmission via Wi-Fi, and the message “HALOW OK” will appear on the Panel’s webpage upon completing data transmission. If the connection fails, the Green LED will turn off.

![](<.gitbook/assets/Unknown image (447)>)

* When it is confirmed that the PIR Camera works in the chosen location, you can proceed to installation.

###

{% hint style="info" %}
Note:&#x20;

* After the Test button is held and pressed for 3 seconds, the LED of the PIR Camera will be on for 20 seconds. If the PIR Camera does not receive acknowledgement from the Control Panel within this 20-second period, the LED will turn off. The Test button needs to be pressed and held for 3 seconds again to resend a learning code.
* If the PIR Camera already exists in a Control Panel system, you will need to first remove the PIR Camera from the Control Panel before you can learn it into a different Control Panel.
* **Walk Test** should be conducted to confirm proper operation and coverage of the PIR Camera.**\_\_**
* When learning the PIR Camera into a repeater/router, please press the Test button once (instead of pressing and holding it for 3 seconds) to send a learn code.
{% endhint %}

## Edit PIR Camera Operation Area

Follow instruction below to change PIR Camera Area in the Control Panel.

1. Use the panel Edit Device function to change PIR Camera area setting.
2. Press and hold the Test button for 3 seconds on the PIR Camera to send a signal to the Panel, and then release the button when the LED lights up.

## Mounting & Installation Method

* The PIR Camera can be mounted on a flat surface or in a corner with the fixing screws, wall plugs, and the mounting bracket provided.
* The provided mounting bracket features two surface-mounting holes and four corner-mounting holes, accommodating various mounting needs.
* To mount the PIR Camera with the mounting bracket:
  1. Use the mounting bracket as a template and drill 2 (for mounting on a flat surface) or 4 (for mounting in the corner) holes into the wall.
  2. Push in the plugs and screw the mounting bracket onto the wall.
  3. Hook the PIR Camera onto the mounting bracket and then **push it downward**.

{% hint style="info" %}
Note: Please make sure the PIR Camera is properly hooked onto the mounting bracket, so that the tamper switch is fully compressed.
{% endhint %}

### Surface Mounting

![](<.gitbook/assets/Unknown image (448)>)

### Corner Mounting

![](<.gitbook/assets/Unknown image (449)>)

4. Apply the Stabilizing Screw to the top of the PIR Camera. The Stabilizing Screw has a foolproof mechanism for correct installation.

![](<.gitbook/assets/Unknown image (450)>)

## Installation Recommendations

**It is recommended to install the PIR Camera in the following locations:**

* At a height of 2.3 meters (measured from bottom of the camera) above the ground level for best performance.
* In a corner for the widest view.
* At a position where an intruder would normally move across the PIR Camera’s field of view.
* On a surface or in a corner where animals are inaccessible.
* The PIR Camera has a detection range of 10M when mounted at the height of 2.3 meters above the ground.



![VST-897EX-Solar Detection Range](<.gitbook/assets/Unknown image (451)>)

***

![Pet's Weight/Height: 20 kg](<.gitbook/assets/Unknown image (452)>)

**Limitations:**

* Do not expose the PIR Camera completely to direct sunlight.  Avoid large obstacles in the detection area.
* Do not face heat sources such as fires and boilers, or install above radiators.
* Never attempt to disassemble or modify the unit.
* Please install the PIR Camera straight up. Do not tilt it.

![](<.gitbook/assets/Unknown image (453)>)

* Do not install the motion sensor camera where objects moved by wind such as trees and laundry, which may block the motion sensor camera’s field of view.

![](<.gitbook/assets/Unknown image (454)>)

* Clear all light-reflecting surfaces from the detection area, as well as water puddles.

![](<.gitbook/assets/Unknown image (455)>)

* Avoid aiming at the path of outdoor unit’s intake or exhaust airflow.

<figure><img src=".gitbook/assets/Unknown image (456)" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
IMPORTANT  NOTE:

* Adjust the Dip Switches according to the installation location of the PIR Camera for ideal performance. If Dip Switch settings does not match with installation environment, the PIR Camera’s performance will be hindered and may cause either false alarm or inability to detect movement.
* The PIR Camera detects differences between the moving object and the background. If the object is idle (i.e. not moving), the PIR Camera is unable to detect it.
* The PIR Camera has a directional characteristic and is most effective at detecting intruder moving across field of detection. It is less sensitive for detecting motion directly towards the PIR Camera.
* For best performance, remember to adjust the mounting height of Motion Sensor Camera with respect to the height of the tallest pet in the house. Taller dogs require the Motion Sensor Camera to be mounted higher for pet friendliness.
* The PIR Camera has a blind spot of about 1 meter under the camera when mounted at a height of 2.3 meters. The blind spot area will enlarge if you mount the PIR Camera higher than 2.3 m, and reduce if lower than 2.3 m.
* Unless required, we suggest keeping the PIR Camera mounting location at the height of 2.3 meters for optimum performance. If you change the mounting height, please conduct detection test to make sure the PIR Camera can detect intruder normally at the chosen height.
{% endhint %}
