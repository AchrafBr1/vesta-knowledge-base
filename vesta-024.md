# VESTA-024

**VST-862EX**

## **Outdoor PIR Motion Sensor Camera**

<figure><img src=".gitbook/assets/image (20) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

VST-862EX is an outdoor passive infrared (PIR) motion sensor camera. It is capable of sending wireless signals and captured images (picture quality of up to 640 x 480 pixels) to the Control Panel upon movement detection.

Featuring night illumination capability, with UV resistant housing, and waterproof to IP45 standard, VST-862EX is ideal for backyards, lawns, gates, outdoor corridors and hallways.

The outdoor PIR Camera is designed to give a typical detection range of 10 meters when mounted at 2 meters above ground. It provides pet-immunity up to 60 kilos with two selectable sensitivity levels to accommodate different environments.

VST-862EX is also compatible with Climax’s Repeater RP-29/Router RMB-29, which can further extend the RF communication range into hard-to-reach areas.

**VST-862EX Series includes the following models**:

VST-862EX – PIR motion sensor camera with flash LED

VST-862EX-IL – PIR motion sensor camera with Infrared LED

## _**Identifying the Parts**_

**Front View** **Inside View**

![](<.gitbook/assets/1 (33).jpeg>)

1. **Flash LED / Infrared LED -** The Flash LED (For VST-862EX) or Infrared LED (For VST-862EX-IL) delivers sufficient light for image capture under low lighting conditions.
2. **LED Indicator (Red) -** The LED indicator is used to indicate the system status.
3. **IR Sensor -** The sensor is intended to detect moving objects.
4. **PIR Camera Lens**
5. **Test\&Learn Button**

&#x20;      -Press and hold the button for 3 seconds to send a learn code, and then release the button when Red LED lights up.

&#x20;       -Press the button once to enter test mode for 10 minutes.

&#x20;       -Press the button once to send a learn code to the repeater/router.

6. **Internal Tamper**
7. **DIP Switch Block-** There are 8 DIP Switches for setting the function & detection sensitivity levels.
8. **Battery Compartment**
9.  **Mounting Bracket**

    ![](<.gitbook/assets/0 (36).jpeg>)

## _**LED Indicator**_

When enabled, the LED Indicator will light up in the following conditions:

* When the Tamper Switch is triggered, the LED will flash for 6 times to indicate it is transmitting a “**Tamper**” signal.
* When the PIR Camera is in fault conditions (tamper open or low battery condition persists), each time it transmits a detected movement, the LED will flash for 6 times.
* After the Test button is pressed once to enter Test Mode, the LED will flash for 60 seconds to indicate that the PIR motion sensor camera is warming up.
* In Test mode, the LED will turn on for 2 seconds whenever a movement is detected.

{% hint style="warning" %}
Note:

The LED indicator can be enabled by setting the DIP Switch2 to ON position. Please refer to **DIP Switch Position Table** for details.
{% endhint %}

## _**Image Capture**_

When the alarm system is armed, the PIR Camera will capture 1, 3 or 6 alarm images in 640 x 480 or 320 x 240 resolutions (programmable from Control Panel) upon movement detection. You can also manually request the PIR Camera to take a picture through the Control Panel. The captured images will be transferred to the Control Panel for visual alarm verification.

{% hint style="warning" %}
Note:

If your PIR Camera is installed at a location where the camera’s field of view is a complex environment with intense light or lots of colors, the images captured will be great in file size, possibly leading to truncation when the images are transmitted to the Control Panel.
{% endhint %}

## _**Warm Up Period**_

The PIR Camera will warm up for 60 seconds in the following conditions:

* When the PIR Camera is turned on by the Control Panel system upon entering arm mode or entering arm mode with fault conditions.
* When the test button is pressed once to enter Test Mode.

The Red LED will flash slowly during warm up period. During the 60-second warm up period, the PIR Camera will not be activated.

## _**Test Mode**_

* The PIR Camera can be put into Test mode for 10 minutes by pressing the Test button once. In Test mode, the sleep timer and image capture functions are disabled. LED indicator is enabled to light up for two seconds whenever a movement is detected. The PIR Camera will automatically exit Test Mode after 10 minutes, and return to normal mode.
* To put the PIR Camera into constant Test mode, please adjust DIP switch1 to ON position (Please refer to **DIP Switch Position Table**).

## _**Supervision Signal**_

* After installation, the PIR Camera will automatically transmit Supervisory signals periodically to the Control Panel at random intervals of 30 to 50 minutes.
* If the Control Panel has not received the signal from the PIR Camera for the preset period of time, the Control Panel will indicate on its display that the particular PIR Camera is experiencing an out-of-signal problem.

## _**Sleep Timer**_

* The PIR Camera features an automatic “sleep time” of approximately one minute for power conservation. After transmitting a detected movement, the PIR Camera will not retransmit for one minute. Any further movement detected within this one-minute sleep period will extend the sleep time by another minute. This way, continuous movement in front of PIR Camera will not unduly exhaust the battery.

## _**Double Knock Function**_

* The PIR Camera has a double knock function. If the double knock function is enabled, the PIR Camera will report an alarm to the control panel only if two movements are detected within 10 seconds. If the double knock function is disabled, the PIR Camera will report an alarm to the control panel when a movement is detected.

## _**Tamper Protection**_

* The PIR Camera is protected by an internal tamper switch which is compressed when the PIR Camera is hooked onto the mounting bracket. When the PIR Camera is removed from the mounting bracket, the tamper switch will be activated and the PIR Camera will send a tamper open signal to the control panel to remind the user of this condition.

## _**DIP Switch Position Table**_

The function of each DIP Switch is listed in the table below. The DIP Switch is either ON or OFF. Top position indicates ON and bottom position indicates OFF.

<figure><img src=".gitbook/assets/3 (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Note:

After changing the Dip Switch settings, please re-power on the PIR Camera for it to operate with new Dip Switch Settings.
{% endhint %}

## _**Battery**_

* The PIR Camera uses four AAL91 lithium batteries as its power source.
* The PIR Camera features low battery voltage detection. When low battery is detected, a low battery signal will be sent to the Control Panel along with regular signal transmissions for the Control Panel to display the status accordingly.
* **To change the batteries:**

**Step 1:** Remove the PIR Camera from the mounting position and loosen the back cover fixing screw.

**Step 2:** Insert a flathead screwdriver into the caved-in area of the back cover and then carefully lift the back cover.

![](<.gitbook/assets/3 (44).png>)

**Step 3:** Remove the old batteries and press the test button twice to fully discharge.

**Step 4:** Insert four new AAL91 lithium batteries.

**Step 5:** Press the test button once. A battery normal signal will be sent to the Control Panel.

**Step 6:** Screw back the back cover.

**Step 7:** Mount back the PIR Camera to the mounting location.

## _**Getting Started – Learning the PIR Camera into the Control Panel**_

* Loosen the bottom fixing screw, and then insert a flat-head screwdriver to lift the back cover.
* Based on your needs, set Sensitivity Switch as shown in _DIP Switch Position Table_.
* Insert four AAL91 lithium batteries into the battery holder taking care to connect the polarity correctly.
* Put the Control Panel into learning mode, refer to Control Panel manual for details.
* Press and hold the Test button for 3 seconds to send a learn code, and then release the button when Red LED lights up. The LED will be on for 20 seconds, indicating that the PIR Camera is in learning mode.
* If the Control Panel receives the signal from the PIR Camera, it will display the information accordingly. Within 20 seconds when the LED of the PIR Camera is on, select the PIR Camera on the Control Panel Webpage and click **“add”** to include it into the Panel. Refer to the Control Panel manual for details.
* When the PIR Camera receives acknowledgement from the Control Panel, the LED of the PIR Camera will flash 6 times and then turn off to indicate successful learning.
* After the PIR Camera is learnt-in, put the Control Panel into Walk Test mode. Hold the PIR Camera in the desired location and press the Test button to confirm this location is within the signal range of the Control Panel.
* When you are satisfied that the PIR Camera works in the chosen location, you can proceed to installation.

{% hint style="warning" %}
Note:

After the Test button is held and pressed for 3 seconds, the LED of the PIR Camera will be on for 20 seconds. If the PIR Camera does not receive acknowledgement from the Control Panel within this 20-second period, the LED will turn off. The Test button needs to be pressed and held for 3 seconds again to resend a learning code.

If the PIR Camera already exists in a Control Panel system, you will need to first remove the PIR Camera from the Control Panel before you can learn it into a different Control Panel.

**Walk Test** should be conducted to confirm proper operation and coverage of the PIR.

When learning the PIR Camera into a repeater/router, please press the Test button once (instead of pressing and holding it for 3 seconds) to send a learn code.
{% endhint %}

## _**Edit PIR Camera Operation Area**_

Follow the instructions below to change the PIR Camera Area in the Control Panel

1. Use the panel Edit Device function to change PIR Camera area setting.
2. Press and hold the Test button for 3 seconds on the PIR Camera to send a signal to the panel, and then release the button when the LED lights up.

## _**Mounting & Installation Method**_

![](<.gitbook/assets/4 (21).jpeg>)

* **Mounting with mounting bracket:**
  * The PIR Camera can be mounted on either a flat surface or in a corner situation with fixing screws, plugs, and the mounting bracket provided.
  * The provided mounting plate has knockouts where the plastic is thinner and can be broken for mounting purposes. Two knockouts are for surface fixing, and four knockouts are for corner fixing, as shown in the picture.
  * To mount VST-862EX with mounting bracket:
    1. Use the mounting bracket as a template to drill holes on the wall for plugs.
    2. Push in the plugs and fix the mounting bracket on the wall with the screws.
    3. Mount the VST-862EX with the hooks of the mounting bracket latched on the back cover of the VST-862EX, and then push downwards until you hear a click sound.

{% hint style="warning" %}
Note:

Please make sure the PIR Camera is properly hooked onto the mounting bracket so that the internal tamper switch is fully compressed.
{% endhint %}



![](<.gitbook/assets/5 (40).png>)

{% hint style="warning" %}
Please avoid mounting the PIR Camera on uneven surfaces. If mounting in a corner situation on uneven surfaces is still necessary, you can attach the 4 adhesive foam spacers to the back of the mounting bracket to provide stress relaxation.
{% endhint %}



![](<.gitbook/assets/6 (29).png>)

* **Mounting with mounting bracket and rotating holder:**

A rotating holder is provided as a user-friendly mounting option **(optional item, sold separately)**. It is comprised of a base to fix to surface and a swivel ball to fix to the mounting bracket and VST-862EX.

With the rotating holder, the PIR Camera can be rotated horizontally to provide optimal coverage.

![](<.gitbook/assets/7 (26).jpeg>)

A special screwdriver with reversible double-sided bit, and three star socket screws are provided for fixing the rotating holder to the wall.

![](<.gitbook/assets/8 (27).png>)

Please use the provided screwdriver to tighten/loosen star socket screws.

![](<.gitbook/assets/9 (31).png>)

* To mount VST-862EX with mounting bracket and rotating holder:

1. Fix the rotating holder to the wall with provided screws.
2. Fix the mounting bracket on the swivel ball with the fixing screw secured through the foolproof design hole.
3. Mount VST-862EX with the hooks of the mounting bracket latched on the back cover of the VST-862EX, and then push downwards until you hear a click sound.

![](<.gitbook/assets/10 (23).png>)

4. Rotate the swivel ball horizontally to adjust VST-862EX’s detecting angle. (When the angle adjusting screw is half loosen, the swivel ball can still be rotated.)

![](<.gitbook/assets/11 (14).jpeg>)

5. When VST-862EX is rotated to a positon with desired detection coverage, you can lock the position by firmly tightening the angle adjusting screw.

## _**Installation Recommendations**_

**It is recommended to install the PIR Camera in the following locations:**

* At a height of 2 meters (measured from the bottom of the camera) above the ground level for best performance.
* In a corner for the widest view.
* Where an intruder would normally move across the PIR Camera’s field of view.
* A surface or corner where animals are inaccessible.
* The PIR Camera has a detection range of 10M when mounted at a height of 2 meters above the ground.

**VST-862EX Detection Range**

![](<.gitbook/assets/12 (10).jpeg>)

**Limitations:**

* Do not expose the PIR Camera completely to direct sunlight.
* Avoid large obstacles in the detection area.
* Do not face heat sources such as fires and boilers or install above radiators.
* Never attempt to disassemble or modify the unit.
* Please install the PIR Camera straight up. Do not tilt it.

![](<.gitbook/assets/13 (8).jpeg>)

* Do not install the motion sensor camera where objects moved by wind such as trees and laundry, which may block the motion sensor camera’s field of view.

![](<.gitbook/assets/14 (11).jpeg>)

* Clear all light-reflecting surfaces from the detection area, as well as water puddles.

![](<.gitbook/assets/15 (8).jpeg>)

* Avoid looking directly at the path of the outdoor unit’s intake or exhaust airflow.

![](<.gitbook/assets/16 (8).jpeg>)

{% hint style="warning" %}
IMPORTANT NOTE:

Adjust the Dip Switches according to the installation location of the PIR Camera for ideal performance. If Dip Switch settings do not match the installation environment, the PIR Camera’s performance will be hindered and may cause either a false alarm or an inability to detect movement.

The PIR Camera detects differences between the moving object and the background. If the object is stationary (i.e. not moving), the PIR Camera is unable to detect it.

The PIR Camera has a directional characteristic and is most effective at detecting intruders moving across the field of detection. It is less sensitive for detecting motion directly towards the PIR Camera.

The PIR Camera has a blind spot of about 1 meter under the camera when mounted at a height of 2 meters. The blind spot area will enlarge if you mount the PIR Camera higher than 2M, and reduce if lower than 2M.

Unless required, we suggest keeping the PIR Camera at the suggested height for optimum performance. If you change the mounting height, please conduct a detection test to make sure the PIR Camera can detect intruders normally at the desired height.
{% endhint %}
