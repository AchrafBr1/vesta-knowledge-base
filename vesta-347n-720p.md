# VESTA-347N-720P

**VST-892EX-HD-IL-SF1**

**Outdoor PIR Motion Sensor Camera**&#x20;

VST-892EX-HD is an outdoor passive infrared (PIR) motion sensor camera. It is capable of sending wireless signals and captured images (picture quality of up to 1280 x 720 pixels) to the Control Panel upon movement detection.

Featuring night illumination capability, with UV resistant housing, and waterproof to IPX6 standard, VST-892EX-HD is ideal for backyards, lawns, gates, outdoor corridors and hallways.

The outdoor PIR Camera is designed to give a typical detection range of 10 meters when mounted at 2.3 meters above ground.

It provides pet-immunity up to 60 kilos with three selectable sensitivity levels to accommodate different environments.

Besides, VST-892EX-HD is designed with the digital proximity detector. The anti-masking feature allows for detection of any attempts to blind the detector by placing objects in its field of view.

VST-892EX-HD is also compatible with Climax’s Repeater RP-29/Router RMB-29, which can further extend the RF communication range into hard-to-reach areas.

Remote configuration is supported for the PIR motion sensor camera. Besides adjusting the DIP Switch, users can also enable/disable double knock function and pet immunity, and adjust the sensitivity of the PIR Camera from the Control Panel webpage or Home Portal Server.

**The VST-892EX-HD Series includes the following models:**

VST-892EX-HD – PIR motion sensor camera with flash LED&#x20;

VST-892EX-HD-IL – PIR motion sensor camera with Infrared LED

## _**Identifying the Parts**_

![](<.gitbook/assets/0 (119).jpeg>)

1. **Digital Proximity Detector**

The digital proximity detector is used to detect any masking (blocking) attempt by an intruder.

2. **LED Indicator (Red)**

The LED indicator is used to indicate the system status.

3. **Flash LED/Infrared LED**

The Flash LED (for VST-892EX-HD) or Infrared LED (for VST-892EX-HD-IL) delivers sufficient light for image capture under low lighting condition.

4. **IR Sensor**

The sensor is intended to detect moving objects.

5. **PIR Camera Lens**
6. **Internal Tamper**
7. **Test\&Learn Button**

-Press and hold the button for 3 seconds to send a learn code, and then release the button when Red LED lights up.

-Press the button once to enter test mode for 10 minutes.

-Press the button once to send a learn code to the repeater/router.

8. **DIP Switch Block**

There are 8 DIP Switches for setting the function & detection sensitivity levels.

9. **Battery Compartment**
10. **Mounting Bracket**
11. **Hooks**
12. **Mounting Holes**

## _**LED Indicator**_

When enabled, the LED Indicator will light up in the following conditions:

* When the Tamper Switch is triggered, the LED will flash for 2 seconds to indicate it is transmitting “**Tamper**” signal.
* When the PIR Camera is in fault conditions (tamper open or low battery condition persists), each time it transmits a detected movement, the LED will flash for 2 seconds.
* After the Test button is pressed once to enter Test Mode, the LED will flash for 60 seconds to indicate that the PIR motion sensor camera is warming up.
* In Test mode, the LED will turn on for 2 seconds whenever a movement is detected.

The LED will not flash if the PIR Camera tamper and battery are normal and it is not under test mode.

If the LED flashes to indicate signal transmission, it will flash twice rapidly upon receiving acknowledgement from panel.

{% hint style="warning" %}
Note:

The LED indicator can be enabled by setting the DIP Switch2 to ON position. Please refer to **DIP Switch Position Table** for details.
{% endhint %}

## _**Image Capture**_

When the alarm system is armed, the PIR Camera will capture 1or 3 alarm images in 1280x720, or 1/3/6 alarm images in 640 x 480 or 320 x 240 resolutions (programmable from Control Panel) upon movement detection. You can also manually request the PIR Camera to take a picture through the Control Panel. The captured images will be transferred to the Control Panel for visual alarm verification.

{% hint style="warning" %}
Note:

If your PIR Camera is installed at a location where the camera’s field of view is a complex environment with intense light or lots of colors, the images captured will be great in file size, possibly leading to truncation when the images are transmitted to the Control Panel.
{% endhint %}

## _**Warm Up Period**_

The PIR Camera will warm up for 60 seconds in the following conditions:

* When the PIR Camera is turned on by the Control Panel system upon entering arm mode.
* When the test button is pressed once to enter Test Mode.

The Red LED will flash slowly during warm up period. During the 60-second warm up period, the PIR Camera will not be activated.

## _**Test Mode**_

* The PIR Camera can be put into Test mode for 10 minutes by pressing the Test button once.
* In Test mode, the sleep timer and image capture functions are disabled. LED indicator will light up for two seconds whenever a movement is detected.
* The PIR Camera will automatically exit Test Mode after 10 minutes, and return to normal mode.
* In Test Mode, the LED indicator must be enabled by setting the DIP Switch2 to ON position, and the Double Knock function must be disabled by setting the DIP Switch7 to OFF position, for the user to test the detection range.

## _**Double Knock Function**_

* The PIR Camera has a double knock function. If the double knock function is enabled, the PIR Camera will report an alarm to the control panel only if two movements are detected within 10 seconds. If the double knock function is disabled, the PIR Camera will report an alarm to the control panel when a movement is detected.

## _**DIP Switch Position Table**_

The function of each DIP Switch is listed in the table below. The DIP Switch is either ON or OFF. Top position indicates ON and bottom position indicates OFF.

<figure><img src=".gitbook/assets/10 (93).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Note:

After changing Dip Switch settings, please re-power on the PIR Camera for it to operate with new Dip Switch Settings.
{% endhint %}

## _**Remote Setting**_

* The PIR motion sensor camera supports remote setting of double knock function, sensitivity and pet immunity.
* When the PIR camera is powered on, its double knock function is determined by DIP SW7 setting, sensitivity is determined by DIP SW5 & SW6, and pet immunity is determined by DIP SW8. Users can either adjust DIP Switch settings or remotely change the double knock function, sensitivity and pet immunity settings in the Control Panel webpage or Home Portal Server. Remote setting will overwrite DIP Switch settings.

### **Control Panel Webpage**:

1. On the Panel local webpage, go to the Edit Device page, input the PIR camera configuration in the Sensor Setting section. Click OK to confirm.

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

2. Press the Test button on the PIR camera to send a signal to the panel, new settings will be applied immediately. If the button is not pressed, new settings will be applied upon next signal transmission, e.g. supervision signal or IR trigger signal.

### **Home Portal Server**:

1. On Home Portal Server, go to the Device setting page, click the VST-892EX-HD device row and select “IR Configuration.”
2. Select the Double Knock function (Enable/Disable), Sensitivity (High/Medium/Low), and Pet immunity (Enable/Disable) from the drop-down lists, click “Submit” to confirm setting.
3. Press the Test button on the PIR camera to send a signal to the panel, new settings will be applied immediately. If the button is not pressed, new settings will be applied upon next signal transmission, e.g. supervision signal or IR trigger signal.

## _**Supervision Signal**_

* After installation, the PIR Camera will automatically transmit Supervisory signals periodically to the Control Panel at random intervals of 90 to 110 minutes.
* If the Control Panel has not received the signal from the PIR Camera for the preset period of time, the Control Panel will indicate on its display that the particular PIR Camera is experiencing an out-of-signal problem.

## _**Sleep Timer**_

* The PIR Camera features an automatic “sleep time” of approximately one minute for power conservation. After transmitting a detected movement, the PIR Camera will not retransmit for one minute. Any further movement detected within this one-minute sleep period will extend the sleep time by another minute. This way, continuous movement in front of PIR Camera will not unduly exhaust the battery.

## _**Tamper Protection**_

* The PIR Camera is protected by an internal tamper switch which is compressed when the PIR Camera is hooked onto the mounting bracket. When the PIR Camera is removed from the mounting bracket, the tamper switch will be activated and the PIR Camera will send a tamper open signal to the control panel to remind the user of this condition.

## _**Anti-Masking**_

* The PIR Camera has a digital proximity detector that can detect any masking (blocking) attempt by an intruder.
* When a masking event is detected, and the masking condition lasts for 3 minutes, VST-892EX-HD will send a masking alarm signal to the Control Panel to notify user of the masking condition.
* After masking/blocking is removed for 3 minutes, VST-892EX-HD will send restore signal to the Control Panel.

## _**Battery**_

* The PIR Camera uses four AAL91 lithium batteries as its power source.
* The PIR Camera features low battery voltage detection. When low battery is detected, a low battery signal will be sent to the Control Panel along with regular signal transmissions for the Control Panel to display the status accordingly.
* **To change the batteries:**

**Step 1:** Remove the PIR Camera from mounting position.

**Step 2:** Loosen the back cover fixing screw and open the back cover.

**Step 3:** Remove the old batteries and press the test button twice to fully discharge.

**Step 4:** Insert four new AAL91 lithium batteries.

**Step 5:** Press the test button once. A battery normal signal will be sent to the Control Panel.

**Step 6:** Screw back the back cover.

**Step 7:** Mount back the PIR Camera to mounting location.

## _**Getting Started – Learning the PIR Camera into the Control Panel**_

* Loosen the bottom fixing screw, and open the back cover.
* Based on your needs, set Sensitivity Switch as shown in _DIP Switch Position Table_.
* Insert four AAL91 lithium batteries into the battery holder taking care to connect the polarity correctly.
* Put the Control Panel into learning mode, refer to Control Panel manual for details.
* Press and hold the Test button for 3 seconds to send a learn code, and then release the button when Red LED lights up. (To learn into battery-operated panel, after pressing and holding the Test button for 3 seconds, please press the Test button again for one second.) The LED will be on for 20 seconds, indicating the PIR Camera is in learning mode.
* If the Control Panel receives the signal from the PIR Camera, it will display the information accordingly. Within 20 seconds when the LED of the PIR Camera is on, select the PIR Camera on the Control Panel Webpage and click **“add”** to include it into the Panel. Refer to the Control Panel manual for details.
* When the PIR Camera receives acknowledgement from the Control Panel, the LED of the PIR Camera will flash 6 times and then turn off to indicate successful learning.
* After the PIR Camera is learnt-in, put the Control Panel into Walk Test mode. Hold the PIR Camera in the desired location, and press the Test button to confirm this location is within the signal range of the Control Panel.
* When you are satisfied that the PIR Camera works in the chosen location, you can proceed to installation.

{% hint style="warning" %}
Note:

* After the Test button is held and pressed for 3 seconds, the LED of the PIR Camera will be on for 20 seconds. If the PIR Camera does not receive acknowledgement from the Control Panel within this 20-second period, the LED will turn off. The Test button needs to be pressed and held for 3 seconds again to resend a learning code.
* If the PIR Camera already exists in a Control Panel system, you will need to first remove the PIR Camera from the Control Panel before you can learn it into a different Control Panel.
* **Walk Test** should be conducted to confirm proper operation and coverage of the PIR.
* When learning the PIR Camera into a repeater/router, please press the Test button once (instead of pressing and holding it for 3 seconds) to send a learn code.
{% endhint %}

## _**Edit PIR Camera Operation Area**_

Follow instruction below to change PIR Camera Area in the Control Panel.

1. Use the panel Edit Device function to change PIR Camera area setting.
2. Press and hold the Test button for 3 seconds on the PIR Camera to send a signal to the panel, and then release the button when the LED lights up.

## _**Mounting & Installation Method**_

### **Mounting with mounting bracket:**

* The PIR Camera can be mounted on a flat surface with fixing screws, plugs, and the mounting bracket provided.
* The provided mounting plate has knockouts, where the plastic is thinner and can be broken for mounting purpose.
* To mount VST-892EX-HD with mounting bracket:
  1. Use the mounting bracket as a template to drill 2 holes on the wall for plugs..
  2. Push in the plugs and fix the mounting bracket on the wall with the screws.
  3. Hook VST-892EX on the mounting bracket and then **push downwards until you hear a click sound**.

![](<.gitbook/assets/3 (79).jpeg>)

{% hint style="warning" %}
Note:

Please make sure the PIR Camera is properly hooked onto the mounting bracket, so that the internal tamper switch is fully compressed.
{% endhint %}

![](<.gitbook/assets/4 (99).png>)

### **Mounting with mounting bracket and rotating holder:**

A rotating holder is provided as a user friendly mounting option **(optional item, sold separately)**. It is comprised of a base to fix to a surface, and a swivel ball to fix the mounting bracket.

With the rotating holder, the PIR Camera can be rotated horizontally to provide optimal coverage.

![](<.gitbook/assets/5 (50).jpeg>)

A special screwdriver with reversible double-sided bit (as the left picture below), and three star socket screws are provided for fixing the rotating holder to the wall.

Please use the provided screwdriver to tighten/loosen star socket screws.

![](<.gitbook/assets/6 (80).png>)

* To mount VST-892EX with mounting bracket and rotating holder:

1. Fix the rotating holder to the wall with provided screws.
2. Fix the mounting bracket on the swivel ball with the fixing screw secured through the foolproof design hole.
3. Hook VST-892EX onto the mounting bracket and then push downwards until you hear a click sound.
4. Rotate the swivel ball horizontally to adjust VST-892EX’s detecting angle. (When the angle adjusting screw is half loosen, the swivel ball can still be rotated.)
5. When VST-892EX is rotated to a positon with desired detection coverage, you can lock the position by firmly tightening the angle adjusting screw.

![](<.gitbook/assets/7 (70).png>)

## _**Installation Recommendations**_

**It is recommended to install the PIR Camera in the following locations:**

* At a height of 2.3 meters (measured from bottom of the camera) above the ground level for best performance.
* In a corner for the widest view.
* At a position where an intruder would normally move across the PIR Camera’s field of view.
* On a surface or in a corner where animals are inaccessible.
* The PIR Camera has a detection range of 10M when mounted at the height of 2.3 meters above the ground.

![](<.gitbook/assets/8 (52).jpeg>)

**Limitations:**

* Do not expose the PIR Camera completely to direct sunlight.
* Avoid large obstacles in the detection area.
* Do not face heat sources such as fires and boilers, or install above radiators.
* Never attempt to disassemble or modify the unit.
* Please install the PIR Camera straight up. Do not tilt it.

![](<.gitbook/assets/9 (40).jpeg>)

* Do not install the motion sensor camera where objects moved by wind such as trees and laundry, which may block the motion sensor camera’s field of view.

![](<.gitbook/assets/10 (30).jpeg>)

* Clear all light-reflecting surfaces from the detection area, as well as water puddles.

![](<.gitbook/assets/11 (32).jpeg>)

* Avoid aiming at the path of outdoor unit’s intake or exhaust airflow.

![](<.gitbook/assets/12 (31).jpeg>)

{% hint style="danger" %}
_IMPORTANT NOTE_

* Adjust the Dip Switches according to the installation location of the PIR Camera for ideal performance. If Dip Switch settings does not match with installation environment, the PIR Camera’s performance will be hindered and may cause either false alarm or inability to detect movement.
* The PIR Camera detects differences between the moving object and the background. If the object is idle (i.e. not moving), the PIR Camera is unable to detect it.
* The PIR Camera has a directional characteristic and is most effective at detecting intruder moving across field of detection. It is less sensitive for detecting motion directly towards the PIR Camera.
* For best performance, remember to adjust the mounting height of Motion Sensor Camera with respect to the height of the tallest pet in the house. Taller dogs require the Motion Sensor Camera to be mounted higher for pet friendliness.
* The PIR Camera has a blind spot of about 1 meter under the camera when mounted at a height of 2.3 meters. The blind spot area will enlarge if the PIR Camera is mounted higher than the height of 2.3 meters, and reduce if mounted lower than this height.
* Unless required, we suggest keeping the PIR Camera mounting location at the height of 2.3 meters for optimum performance. If you change the mounting height, please conduct detection test to make sure the PIR Camera can detect intruder normally at the chosen height.
{% endhint %}
