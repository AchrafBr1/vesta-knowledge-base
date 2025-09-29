# VESTA-211N

**VST-892**

## **PIR Motion Sensor Camera**

<figure><img src=".gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

## **Introduction**

VST-892 is a passive infrared (PIR) motion sensor camera. It is capable of sending wireless signals and captured images (picture quality of up to 640 x 480 pixels) to the Control Panel upon movement detection.

The PIR Camera is designed to give a typical detection range of 12 meters when mounted at 2.3-2.5 meters above ground. When Pet Immunity function is enabled, the motion sensor camera will not detect pets up to 25kg when mounted at 2.3-2.5 meters above ground. VST-892 is also compatible with Climax’s Repeater RP-29/Router RMB-29, which can further extend the RF communication range into hard-to-reach areas.

VST-892 is designed with the digital proximity detector. The anti-masking feature allows for detection of any attempts to blind the detector by placing objects in its field of view.

Remote configuration is supported for the PIR camera. Besides adjusting the Jumper Switches, users can also enable/disable pet immunity function and adjust the sensitivity of the PIR camera from the Control Panel webpage or Home Portal Server.

The PIR Camera consists of a two-part design made up of a cover and a base. The cover contains all the electronics and optics and the base provides a means of fixing. The base has knockouts to allow mounting on a flat surface, or a mounting bracket is provided for corner mounting and surface mounting.

**The VST-892 Series includes the following models**:

VST-892 – PIR motion sensor camera with flash LED

VST-892-IL – PIR motion sensor camera with Infrared LED

## **Parts Identification**

![](<.gitbook/assets/0 (95).jpeg>)

**1. Flash LED/Infrared LED**

The Flash LED (For VST-892) or Infrared LED (For VST-892-IL) delivers sufficient light for image capture under low lighting condition.

**2. Blue LED/Function Button**

&#x20;     **Blue LED:** (Please refer to _**LED Indicator**_ description below for details)

**Function Button Usage:**

* Press and hold the button for 3 seconds to send a learn code, release when Blue LED light on.
* Press the button once to enter test mode for 3 minutes.
* Press the button once to send a learn code to the repeater/router. (P5 models only)



3. **Digital Proximity Detector**

&#x20;       The digital proximity detector is used to detect any masking (blocking) attempt by an intruder.

4. **IR Sensor**
5. **PIR Camera Lens**
6. **Battery Compartment**
7. **Tamper Switch**
8. **Pet Immunity Enable/Disable Jumper Switch (JP3)**

**Jumper On:**  The jumper link is inserted connecting the two pins.

**Jumper Off:** The jumper link is removed or “**parked**” on one pin.

&#x20;      When set as ON, Pet Immunity is disabled (Factory default).

&#x20;      When set as OFF, Pet Immunity is enabled.

**9.** **Sensitivity Increaser Jumper Switch (JP4)**

&#x20;   When set as ON, the PIR’s detection sensitivity is high.

&#x20;    When set as OFF, the PIR’s detection sensitivity is in normal level (Factory default).

10. **Battery Insulator**
11. **Battery Compartment Cover**
12. **Mounting Bracket**

## **Features**

### _**LED Indicator**_

In Normal operation mode, the Blue LED will not light except in the following situations:

* When the PIR Camera is in low battery condition, every time it transmits a detected movement, the Blue LED will flash for 2 seconds.
* When the cover is opened and the tamper switch is violated, the Blue LED will flash for 2 seconds, to indicate it is transmitting “Tamper” signal.
* When the Tamper condition persists, every time it transmits a detected movement, the Blue LED will flash for 2 seconds.
* When PIR Camera enters Test Mode, the Blue LED will flash for 1 second. During Test mode, the Blue LED will also flash for 2 seconds every time a movement is detected.
* When the PIR Camera is in 30 seconds warm up period, the Blue LED will slow flash.
* When the PIR Camera is transmitting captured images under fault conditions (low battery, tamper switch activated), the Blue LED will continuous flash.

The LED will not flash if the PIR Camera tamper and battery are normal and is not under test mode,

If the LED flashes to indicate signal transmission, it will flash twice rapidly upon receiving acknowledgement from panel.

### _**Image Capture**_

When the alarm system is armed, the PIR Camera will capture 1, 3 or 6 alarm images in 640 x 480 or 320 x 240 resolutions (programmable from Control Panel) upon movement detection. You can also manually request the PIR Camera to take a picture through the Control Panel. The captured images will be transferred to the Control Panel for users to view.

{% hint style="warning" %}
Note:

f your PIR Camera is installed at a location where the camera’s field of view is a complex environment with intense light or lots of colors, the images captured will be great in file size, possibly leading to truncation when the images are transmitted to the Control Panel.
{% endhint %}



### _**Warm Up Period**_

When the Control Panel system enters arm mode, or when PIR Camera is put into Test Mode, the PIR Camera will warm up for 30 seconds. During the 30-second warm up period, the PIR Camera will not be activated. The Blue LED will slow flash during the warm up period only when PIR enters for Test Mode.

### _**Sleep Timer**_

The PIR Camera has a “**sleep time**” of approximately 1 minute to conserve power. After transmitting for a detected movement, the PIR Camera will not retransmit for 1 minute. Any detected movement during this period will reset the sleep time to 1 minute. Continuous movement in front of the PIR Camera will therefore not exhaust the battery.

### _**Battery and Low Battery Detection**_

The PIR Camera uses two **1.5V “AA” Alkaline batteries** in series connection as its power source.

The PIR Camera features Low Battery Detection function. When the battery voltage is low, the PIR Camera will transmit Low Battery signal to the Control Panel. If movement is detected under Low Battery condition, the Blue LED will flash for 2 seconds.

When changing battery, after removing the old battery, press the Tamper Switch or the Function Button twice to fully discharge before inserting new batteries.

### _**Tamper Protection**_

The PIR Camera is protected by a tamper switch which is compressed when the PIR Camera is properly installed. When the PIR Camera is removed from mounted surface or its cover opened, the tamper switch will be activated and the PIR Camera will send a tamper open signal to the system control panel to remind the user of the condition. If movement is detected when the tamper switch is open, the Blue LED will flash for 2 seconds.

### _**Supervision**_

The PIR Camera will conduct a self-test periodically by transmitting a supervisory signal once every 90 to 110 minutes.

### _**Test Mode**_

* Test mode is for you to check the PIR camera’s detection range (not shooting coverage).
* Press the Function button once to enter Test mode for 3 minutes, the Blue LED will flash for 1 second.
* The PIR camera will warm up for 30 seconds. Please do not trigger the Camera during this warming-up period.
* After the warm-up period, you can trigger PIR camera to check IR detection range. If PIR camera is triggered, the Blue LED will flash for 2 seconds.

### _**Learning**_

* Power on the PIR Camera by removing the battery insulator.
* Put the Control Panel into learning mode, refer to Control Panel manual for details.
* Press and hold the function button for 3 seconds, release the button when the Blue LED light on. (To learned into battery-operated panel, after pressing and holding the function button for 3 seconds, please press the function button again for one second.)
* The Blue LED will light on for 25 seconds in learning mode, add PIR Camera into the Control Panel during this period (refer to your Control Panel to finish learn in process). If the PIR is successfully added into the Control Panel, the Blue LED will flash 6 times to indicate. If PIR is not added within 25 seconds, please repeat learning process.

{% hint style="warning" %}
Note:

If the PIR Camera already exists in a Control Panel system, you will need to first remove the PIR Camera from the Control Panel before you can learn it into a different Control Panel.

When learning the PIR Camera into a repeater/router, please press the function button once (instead of pressing and holding it for 3 seconds) to send a learn code. (P5 models only)
{% endhint %}

### _**Walk Test**_

* After the PIR Camera is learnt-in, put the Control Panel into “**Walk Test**” mode, hold the PIR Camera in the desired location, and press the Function Button to confirm this location is within signal range of the Control Panel, refer to Control Panel manual to complete Walk Test.
* When you are satisfied that the PIR Camera works in the chosen location, you can proceed to mounting.

### _**Edit PIR Camera Operation Area**_

* Follow instruction below to change PIR Camera Area in the Control Panel:
  1. Use the panel Edit Device function to change PIR Camera area setting.
  2. Press and hold the Test button for 3 seconds on the PIR Camera to send a signal to the panel, and then release the button when the LED lights up.

### _**Pet Immunity Function**_

The PIR sensor supports pet immunity feature and will not detect pets up to 25 kg to minimize false alarm situation. The Pet Immunity function can be enabled/disabled by setting the Jumper Switch (JP3) position. When the Jumper Switch (JP3) is set to ON, Pet Immunity is disabled (factory default). When the Jumper Switch (JP3) is set to OFF, Pet Immunity is enabled. The pet immunity function can also be adjusted by remote setting as described below.

### _**Sensitivity Increaser Function**_

You can use the sensitivity increaser function to increase the PIR’s detection sensitivity. To increase detection sensitivity, set the Jumper Switch (JP4) to ON. To maintain normal detection sensitivity, set the the Jumper Switch (JP4) to OFF (Factory default). The sensitivity increaser function can also be adjusted by remote setting as described below.

### _**Remote Setting**_

The PIR camera supports remote setting of pet Immunity and sensitivity.

 When the PIR camera is powered on, its pet immunity function and sensitivity are determined by the JP3 and JP4 settings. Users can either adjust jumper settings or remotely change the pet immunity and sensitivity settings from the Control Panel. Remote setting will overwrite jumper settings.

#### **Control Panel Webpage**:

1\) On the Panel local webpage, go to the Edit Device page, input the PIR Camera configuration in the Sensor Setting section. Click OK to confirm.

Please refer to the table below for configuration details. For example, if you want to enable Pet Immunity and set Sensitivity level to high, you can input 02.

<figure><img src=".gitbook/assets/8 (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

2\) Press the function button once on the PIR Camera to send a signal to the Control Panel, new settings will be applied immediately. If the button is not pressed, new settings will be applied upon next signal transmission, e.g., transmission of the supervision signal or IR trigger signal.

**Home Portal Server**:

1. On Home Portal Server, go to the Device setting page, click the VST-892 device row and select “IR Configuration.”
2. Select the Pet Immunity function (Enable/Disable) and Sensitivity (High/Normal) from the drop-down lists, click “Submit” to confirm setting.
3. Press the function button once on the PIR Camera to send a signal to the Control Panel, new settings will be applied immediately. If the button is not pressed, new settings will be applied upon next signal transmission, e.g., transmission of the supervision signal or IR trigger signal.

### _**Proximity Detection**_

* The PIR Camera has a digital proximity detector that can detect any masking (blocking) attempt by an intruder.
* When a masking event is detected, and the masking condition lasts for 3 minutes, VST-892 will send a masking alarm signal to the Control Panel to notify user of the masking condition.
* After masking/blocking is removed for 3 minutes, VST-892 will send restore signal to the Control Panel.

<figure><img src=".gitbook/assets/3 (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

## **Installation**

### _**Installation Guideline**_

* The PIR Camera is designed to be mounted either on a flat surface or in a corner.
* The base has knockouts, where the plastic is thinner, for surface mounting purpose. A mounting bracket can be used for corner fixing as well as surface fixing.
* The detection range is up to 12 meters if the PIR Camera is mounted at a height of 2.3-2.5 meters above the ground.
* When Pet-Immunity function is enabled, it will not detect pets up to 25kg when mounted at a height of 2.3-2.5 meters above the ground. If required, you can adjust the height of the PIR Camera according to the size of your pet for optimal pet immune performance. Higher installation location will provide larger pet-immune space, but also increases the blind spot under the PIR Camera.
* When VST-892 is mounted with rotating bracket, it will not have the regular detection area (as in the diagram), or the typical pet immune range.

**It is recommended to install the PIR Camera in the following locations:**

* At a position where the animals cannot come to the detection area by climbing on furniture or other objects.
* Don’t aim the detector at stairways the animals can climb on.
* At a position such that an intruder would normally move across the PIR’s field of view.
* At a height between 2.3 and 2.5 meters above the ground for best performance.
* In a corner to give the widest view.
* At a position where its field of view will not be obstructed e.g., by curtains, ornaments etc.

**Limitations**

<figure><img src=".gitbook/assets/1 (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/2 (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

## Mounting the PIR Camera

The PIR Camera is designed to be mounted either on a flat surface or in a corner.

A mounting bracket is provided and includes two central screw holes for fixing the\
PIR Camera onto a flat surface and four side screw holes for fixing the PIR Camera\
onto a corner

{% hint style="warning" %}
Note:

Users can easily change the batteries by taking the PIR Camera off the mounting\
bracket when the PIR Camera is mounted with the mounting bracket.
{% endhint %}

* For surface mounting, an optional rotating bracket is provided for users to adjust the range of detection. With the rotating bracket, the VST-892 can be rotated 80 degrees horizontally and 70 degrees vertically to provide optimal coverage.

<figure><img src=".gitbook/assets/1 (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### **Surface mounting without the mounting bracket:**

1. Detach the cover by loosening the bottom fixing screw with a Phillips screwdriver.
2. Break through the 2 surface knockouts at the center of the base.
3. Use the 2 holes as a template and drill holes on the surface to be mounted.
4. Insert the wall plugs if the PIR Camera is to be fixed onto plaster or bricks.
5. Screw the base onto the wall plugs.
6. Re-place the cover onto the base and tighten the bottom fixing screw.

<figure><img src=".gitbook/assets/2 (2) (1).png" alt=""><figcaption></figcaption></figure>

### **Surface Mounting with the mounting bracket:**

1. Use the two central screw holes on the bracket as a template and drill holes into the surface to be mounted.
2. Insert the wall plugs if the PIR Camera is to be fixed onto plaster or bricks.
3. Screw the mounting bracket onto the wall plugs with the two pointing sticks on top and facing you.
4. Fit the PIR Camera onto the hooks of the mounting bracket.

<figure><img src=".gitbook/assets/3 (2) (1).png" alt=""><figcaption></figcaption></figure>

### &#x20;Corner mounting with the mounting bracket:

1. Insert the wall plugs if the PIR Camera is to be fixed onto plaster or bricks.
2. Screw the mounting bracket onto the wall plugs with the two pointing sticks on top and facing you.
3. Fit the PIR Camera onto the hooks of the mounting bracket.

<figure><img src=".gitbook/assets/1 (2).png" alt=""><figcaption></figcaption></figure>

* **Surface mounting with rotating bracket (optional item, sold separately):**

{% hint style="success" %}
Rotating Bracket code: VESTA-212&#x20;
{% endhint %}

The rotating bracket can be mounted on the wall with the screws provided.

1. Screw the rotating bracket onto the wall.
2. Fit the 3 hook holes on the base to the hooks of the rotating bracket accordingly.
3. Rotate the bracket for the proper range of detection and tighten the fixing screw.

<figure><img src=".gitbook/assets/2 (3).png" alt=""><figcaption></figcaption></figure>
