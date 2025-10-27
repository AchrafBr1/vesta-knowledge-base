# VESTA-460

VST 897EX IL Series

<figure><img src=".gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

The VST-897EX Series is an advanced outdoor passive infrared (PIR) motion sensor camera, designed to enhance security&#x20;with high-definition image transmission (up to 1280 x 720 pixels) upon motion detection. Equipped with Sub-GHz Wi-Fi and an&#x20;SF1 backup module, the **HALOW model** ensures rapid processing for faster visual alarm verification.\
Built to withstand outdoor conditions, the VST-897EX features night illumination, UV-resistant housing, and IPX5 waterproofing,&#x20;making it suitable for areas like backyards, gates, and outdoor corridors. The **HDR model** adds white balance with HDR support&#x20;for clearer images in high-contrast lighting conditions.\
With a typical detection range of **10 meters** when mounted at **2.3 meters** above the ground, it offers pet immunity for pets up to&#x20;20 kilograms.&#x20;The camera incorporates anti-masking detectors an advanced anti-masking feature, capable of detecting attempts to obscure&#x20;the lens using objects or coatings within 20 cm. Infrared technology further enhances anti-masking through over-the-lens\
detection.

<figure><img src=".gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

## Identifying the Parts

**\_\_**

<figure><img src=".gitbook/assets/Unknown image (246)" alt=""><figcaption></figcaption></figure>

1. **Flash LED / Infrared LED**

The Flash LED or Infrared LED delivers sufficient light for image capture under low lighting condition

2. **IR Sensor**
3. **LED Indicator (Red)** For system status indication
4. **LED Indicator (Green)** **(for HaLow models only)**

* Lights up when searching for the HaLow-supported Control Panel
* Flashes rapidly for data transmission via Wi-Fi

5. **PIR Camera Lens**
6. **Test\&Learn Button**

* Press the button for 3 seconds to send a learn code, and then release the button when Red LED lights up.
* Press the button once to enter test mode for 10 minutes.
* Press the button once to send a learn code to the repeater / router.

7. **Hook Holes**
8. **Battery Compartment**
9. **DIP Switch Block** There are 8 DIP Switches for setting various functions.\*\*\*\*
10. **Tamper Switch**
11. **Stabilizing Screw**
12. **Hooks**
13. **Corner Mounting Holes**
14. **Surface Mounting Holes**

## LED Indicator

When enabled, the LED Indicator will light up in the following conditions:

* When the Tamper Switch is triggered, the LED will flash to indicate it is transmitting “**Tamper**” signal.
* When the PIR Camera is in fault conditions (tamper open or low battery condition persists), each time it transmits a detected movement, the LED will flash.
* In Test mode, the LED will light up when a motion is detected.

The LED will not flash if the PIR Camera tamper and battery are normal and it is not under test mode.

If the LED flashes to indicate signal transmission, it will flash twice rapidly upon receiving acknowledgement from the Panel.

{% hint style="warning" %}
Note:

The LED indicator can be enabled by setting the DIP Switch 2 to ON position. Please refer to **DIP Switch Position Table** for details.
{% endhint %}

## Image Capture

When the alarm system is armed, the PIR Camera will capture alarm images in resolution of 1280 x 720 pixels, 640 x 480 or 320 x 240 pixels (programmable from Control Panel) upon movement detection. You can also manually request the PIR Camera to take a picture through the Control Panel. The captured images will be transferred to the Control Panel for visual alarm verification.

{% hint style="warning" %}
Note:

If your PIR Camera is installed at a location where the camera’s field of view is a complex environment with intense light or lots of colors, the images captured will be great in file size, possibly leading to truncation when the images are transmitted to the Control Panel.
{% endhint %}

## Supervision Signal

* After installation, the PIR Camera will automatically transmit Supervisory signals periodically to the Control Panel at random intervals of 15 to 18 minutes.
* If the Control Panel does not receive the signal from the PIR Camera during the preset period, the Control Panel will indicate that the particular PIR Camera is experiencing an out-of-signal problem.

## Warm-up Period

When the PIR Camera powers on, it will warm up for 60 seconds. During the 60-second warm-up period, the PIR Camera will not be activated.

## Test Mode

* The PIR Camera can be put into Test Mode for 10 minutes by pressing the Test Button once.

(The LED Indicator will begin flashing slowly if Disarm Response is set to No Response.)

* In Test Mode, the sleep timer and image capture functions are disabled. The LED indicator will light up when motion is detected.
* The PIR Camera will automatically exit Test Mode after 10 minute and return to normal mode.
* To test the detection range in Test Mode, the LED indicator must be enabled by setting DIP Switch 2 to ON, and the Double Knock function must be disabled by setting DIP Switch 7 to OFF.

## Double Knock Function

 The PIR Camera has a double knock function. If the double knock function is enabled, the PIR Camera will report an alarm to the control panel only if two movements are detected within 10 seconds. If the double knock function is disabled, the PIR Camera will report an alarm to the control panel when a movement is detected.

## Tamper Protection

 The PIR Camera is protected by an internal tamper switch which is compressed when the PIR Camera is hooked onto the mounting bracket. When the PIR Camera is removed from the mounting bracket, the tamper switch will be activated and the PIR Camera will send a tamper open signal to the control panel to remind the user of this condition.

## Sleep Timer

* The PIR Camera has a “**sleep time**” of approximately one minute to conserve power. After transmitting for a detected movement, it will not retransmit for 1 minute.
* Continuous movement in front of the PIR Camera will therefore not exhaust the battery.

## DIP Switch Position Table

The table below outlines the function of each Dip switch. Each switch has two positions: **ON** (upper position) and **OFF** (lower position).

<figure><img src=".gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
Note:

After changing Dip Switch settings, re-power on the PIR Camera to activate the changes.
{% endhint %}



## Anti-Masking

* The PIR Camera has two masking sensors that can detect any masking (blocking) attempt by an intruder.
* When a masking condition continues for 3 minutes after being detected, the PIR Camera will send a masking alarm signal to the Control Panel to report the masking condition.
* After masking/blocking has been removed for 3 minutes, the PIR Camera will send restore signal to the Control Panel.

## Remote Update

* The VST-897EX Series PIR Camera supports remote firmware updates.
* Users can initiate the update by enter a designated URL and selecting the appropriate firmware file, enabling a simple and convenient update process without the need for physical access to the device.

## Battery

* The PIR Camera uses four AAL91 lithium batteries as its power source.
* The PIR Camera reports its battery level every 24 hours to the Control Panel. It also sends a report whenever the battery level changes.
* The PIR Camera features low battery voltage detection. When low battery is detected, a low battery signal will be sent to the Control Panel along with regular signal transmissions for the Panel to display the status accordingly.
* **To change the batteries:**

<figure><img src=".gitbook/assets/Unknown image (2) (2)" alt="" width="188"><figcaption></figcaption></figure>

**Step 1** Detach the PIR Camera from mounting bracket.

**Step 2** Loosen the fixing screw and open the battery compartment cover.

**Step 3** Remove the old batteries and press the test button twice to fully discharge the residual power.

**Step 4** Insert four new AAL91 lithium batteries.

**Step 5** Press the Test Button once. A battery normal signal will be sent to the Control Panel.

**Step 6** Re-secure the battery compartment cover.

**Step 7**Re-attach the PIR Camera to the mounting bracket.

## Getting Started – Learning the PIR Camera into the Control Panel

* Detach the PIR Camera from the mounting bracket and open the battery compartment cover.
* Insert four AAL91 lithium batteries into the battery compartment according to the polarity.
* Put the Control Panel into learning mode; refer to Control Panel manual for details.
* Press and hold the Test Button for 3 seconds to send a learn code, and then release the button when Red LED lights up. (To learn into battery-operated panel, after pressing and holding the Test Button for 3 seconds, press the Test Button again for one second.) The LED will be on for 30 seconds, indicating the PIR Camera is in learning mode.
* If the Control Panel receives the signal from the PIR Camera, it will display the information accordingly. Within 30 seconds when the LED of the PIR Camera is on, select the PIR Camera on the Control Panel Webpage and click “**add**” to include it into the Panel. Refer to the Control Panel manual for details.
* When the PIR Camera receives acknowledgement from the Control Panel, the LED of the PIR Camera will flash 6 times and then turn off to indicate successful learning.

{% hint style="warning" %}
Note:

* After the Test Button is held for 3 seconds, the LED of the PIR Camera will be on for 30 seconds. If the PIR Camera does not receive acknowledgement from the Control Panel within this 30-second period, the LED will turn off. The Test button needs to be pressed and held for 3 seconds again to resend a learning code.
* If the PIR Camera already exists in a Control Panel system, you will need to first remove the PIR Camera from the Control Panel before you can learn it into a different Control Panel.
{% endhint %}

**Walk Test**

* After the PIR Camera is learnt-in, put the Control Panel into Walk Test mode. Hold the PIR Camera in the desired location, and press the Test Button to confirm this location is within the signal range of the Control Panel.

{% hint style="warning" %}
Note:

* **Walk Test** should be conducted to confirm proper operation and coverage of the PIR Camera.
* When learning the PIR Camera into a repeater/router, please press the Test button once (instead of pressing and holding it for 3 seconds) to send a learn signal.
{% endhint %}

**Wi-Fi Walk Test&#x20;**_**(For Wi-Fi HaLow models)**_

* When the Control Panel is put to Walk Test mode, pressing the Test Button also initiate a Wi-Fi Walk Test. The PIR Camera’s Green LED will light up as it begins searching for a HaLow-supported Control Panel.

<img src=".gitbook/assets/image (2) (1).png" alt="" data-size="line"> If a connection is established, the Green LED will flash rapidly during data transmission via Wi-Fi, and the message “HALOW OK” will appear on the Panel’s webpage upon completing data transmission.

<img src=".gitbook/assets/image (3) (1).png" alt="" data-size="line"> If the connection fails, the Green LED will turn off.

![](<.gitbook/assets/Unknown image (3) (2)>)

* When you are satisfied that the PIR Camera works in the chosen location, you can proceed to installation.

## Edit PIR Camera Operation Area

1. Use the panel Edit Device function to change PIR Camera area setting.
2. For devices communicating directly with the Panel, the setting is completed after clicking OK.

For devices using a Repeater, press the Test Button to transmit a learn code after changing the area setting.

## Mounting & Installation Method

* The PIR Camera can be mounted either on a flat surface or in a corner with the fixing screws, wall plugs, and the mounting bracket provided.
* The mounting bracket has two surface-mounting holes and four corner-mounting holes, accommodating various mounting needs.
* To mount the PIR Camera with the mounting bracket:
  1. Use the mounting bracket as a template and drill 2 (for mounting on a flat surface) or 4 (for mounting in the corner) screw holes into the wall.
  2. Push in the plugs and screw the mounting bracket onto the wall.
  3. Hook the PIR Camera onto the mounting bracket and then **push it downward**.

{% hint style="warning" %}
Note:

Please make sure the PIR Camera is properly hooked onto the mounting bracket, so that the tamper switch is fully depressed.
{% endhint %}

#### Surface Mounting

![](<.gitbook/assets/Unknown image (4) (2)>)

#### Corner Mounting

![](<.gitbook/assets/Unknown image (5) (2)>)

4. Apply the Stabilizing Screw to the top of the PIR Camera. The Stabilizing Screw has a foolproof mechanism for correct installation.

![](<.gitbook/assets/Unknown image (6) (2)>)

## Installation Recommendations

**It is recommended to install the PIR Camera in the following locations:**

* At a height of 2.3 meters (measured from bottom of the camera) above the ground level for best performance.
* In a corner for the widest view.
* At a position where an intruder would normally move across the PIR Camera’s field of view.
* On a surface or in a corner where animals are inaccessible.
* The PIR Camera has a detection range of 10 meters when mounted at the height of 2.3 meters above the ground.

![VST-897 EX Detection Range](<.gitbook/assets/Unknown image (7) (2)>)

![Pet Weight/Height: 20 kg](<.gitbook/assets/Unknown image (8) (2)>)



**Limitations:**

* Do not expose the PIR Camera completely to direct sunlight.
* Avoid large obstacles in the detection area.
* Do not face heat sources such as fires and boilers, or install above radiators.
* Never attempt to disassemble or modify the unit.
* Please install the PIR Camera straight up. Do not tilt it.

![](<.gitbook/assets/Unknown image (9) (2)>)

* Do not install the motion sensor camera where objects moved by wind such as trees and laundry, which may block the motion sensor camera’s field of view.

![](<.gitbook/assets/Unknown image (10) (2)>)

* Clear all light-reflecting surfaces from the detection area, as well as water puddles.

![](<.gitbook/assets/Unknown image (11) (2)>)

* Avoid aiming at the path of outdoor unit’s intake or exhaust airflow.

\_\_

<figure><img src=".gitbook/assets/Unknown image (12) (2)" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
IMPORTANT NOTE:

* Adjust the Dip Switches according to the installation location of the PIR Camera for ideal performance. If Dip Switch settings does not match with installation environment, the PIR Camera’s performance will be hindered and may cause either false alarm or inability to detect movement.
* The PIR Camera detects differences between the moving object and the background. If the object is idle (i.e. not moving), the PIR Camera is unable to detect it.
* The PIR Camera has a directional characteristic and is most effective at detecting intruder moving across field of detection. It is less sensitive for detecting motion directly towards the PIR Camera.
* For best performance, remember to adjust the mounting height of Motion Sensor Camera with respect to the height of the tallest pet in the house. Taller dogs require the Motion Sensor Camera to be mounted higher for pet friendliness.
* The PIR Camera has a blind spot of about 1 meter under the camera when mounted at a height of 2.3 meters. The blind spot area will enlarge if you mount the PIR Camera higher than 2.3 M, and reduce if lower than 2.3 M.
* Unless required, we suggest keeping the PIR Camera mounting location at the height of 2.3 meters for optimum performance. If you change the mounting height, please conduct detection test to make sure the PIR Camera can detect intruder normally at the chosen height.
{% endhint %}
