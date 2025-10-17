# VESTA-008

VST-862-IL-F1-ALK

## White Flash Pircam&#x20;

<figure><img src=".gitbook/assets/image (3) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

## Introduction

VST-862 is a passive infrared (PIR) motion sensor camera. It is capable of sending wireless signals and captured images (picture quality of up to 640 x 480 pixels) to the Control Panel upon movement detection.

The PIR Camera is designed to give a typical detection range of 12 meters when mounted at 2 meters above ground. For pet-immune models, a pet-immune range of 7 meters is provided, your household pets will not trigger false alarms within this distance. For models that are compatible with Climax’s Repeater RP-29/Router RMB-29 **(P5 models only)**, the RF communication range can be further extended into hard-to-reach areas.

The PIR Camera consists of a two-part design made up of a cover and a base. The cover contains all the electronics and optics and the base provides a means of fixing. The base has knockouts to allow mounting on either a flat surface or in a corner situation with a triangular bracket for corner mounting.

**The VST-862 Series includes the following models:**

| **Model Name**   | **Flash LED** | **Infrared LED** | **Pet Immune** | **Compatible with Repeater** |
| ---------------- | ------------- | ---------------- | -------------- | ---------------------------- |
| VST-862-(P5)     | V             |                  |                | P5 model only                |
| VST-862-IL-(P5)  |               | V                |                | P5 model only                |
| VST-862P-(P5)    | V             |                  | V              | P5 model only                |
| VST-862P-IL-(P5) |               | V                | V              | P5 model only                |

## Parts Identification

<figure><img src=".gitbook/assets/10 (86).png" alt=""><figcaption></figcaption></figure>

#### **1. Flash LED / Infrared LED**

The Flash LED (For 862(P)) or Infrared LED (For 862(P)-IL) delivers sufficient light for image capture under low lighting conditions.

#### **2. Blue LED/Function Button**

&#x20;    **Blue LED:**

&#x20;     (Please refer to _**the LED Indicator**_ description below for details)

&#x20;     **Function Button Usage:**

* Press and hold the button for 3 seconds to send a learn code, and release when the Blue LED light is on. (For the battery-operated panel, after pressing and holding the button for 3 seconds, please press the button **again** for one second to send a learn code.)
* Press the button once to enter test mode for 3 minutes.
* Press the button once to send a learn code to the repeater/router. (P5 models only)

#### **3. IR Sensor**

#### **4. PIR Camera Lens**

#### **5. Battery Compartment Cover**

#### **6. Tamper Switch**

#### **7. Battery Compartment**

#### **8. Sensitivity Adjustment Jumper Switch (JP3)**

![jumper open](<.gitbook/assets/1 (14).png>)<img src=".gitbook/assets/2 (14).png" alt="jumper close" data-size="original">

**Jumper Off** if the jumper link is removed or “**parked**” on one pin.

**Jumper On t**he jumper link is inserted connecting the two pins.

* Jumper On: the PIR’s sensitivity level is set to High.
* Jumper Off: the PIR’s sensitivity level is set to Normal. (**Factory Default**)

#### **Sleep Timer Jumper Switch (JP2)**

![jumper open](<.gitbook/assets/3 (13).png>)![jumper close](<.gitbook/assets/4 (14).png>)

**Jumper Off** if the jumper link is removed or “**parked**” on one pin.

**Jumper On t**he jumper link is inserted connecting the two pins.

* Jumper On: After movement detection, the PIR Camera does not enter sleep mode and will transmit the detection signal again immediately if triggered (**Factory Default**).
* Jumper Off: PIR Camera has a “**sleep time**” of approximately 1 minute after motion detection to conserve power.

## Features

## _**LED Indicator**_

In Normal operation mode, the Blue LED will not light except in the following situations:

* When the PIR Camera is in low battery condition, every time it transmits a detected movement, the Blue LED will flash for 2 seconds.
* When the cover is opened and the tamper switch is violated, the Blue LED will flash for 2 seconds, to indicate it is transmitting a  “Tamper” signal.
* When the Tamper condition persists, every time it transmits a detected movement, the Blue LED will flash for 2 seconds.
* When PIR Camera enters Test Mode, the Blue LED will flash for 1 second. During Test mode, the Blue LED will also flash for 2 seconds every time a movement is detected.
* When the PIR Camera is in 30 seconds warm-up period, the Blue LED will slow flash.
* When the PIR Camera is transmitting captured images under fault conditions (low battery, tamper switch activated), the Blue LED will continuous flash.

## _**Image Capture**_

When the alarm system is armed, the PIR Camera will capture 1, 3 or 6 alarm images in 640 x 480 or 320 x 240 resolutions (programmable from Control Panel) upon movement detection. You can also manually request the PIR Camera to take a picture through the Control Panel. The captured images will be transferred to the Control Panel for users view.

{% hint style="info" %}
Note:&#x20;

If your PIR Camera is installed at a location where the camera’s field of view is a complex environment with intense light or lots of colours, the images captured will be great in file size, possibly leading to truncation when the images are transmitted to the Control Panel.
{% endhint %}

## _**Warm Up Period**_

When the Control Panel system enters arm mode, or when the PIR Camera is put into Test Mode, the PIR Camera will warm up for 30 seconds. During the 30-second warm-up period, the PIR Camera will not be activated. The Blue LED will slow flash during the warm-up period only when PIR enters for Test Mode.

## _**Sleep Timer**_

When **Jumper Switch 2** is set to Off, the PIR Camera has a “**sleep time**” of approximately 1 minute to conserve power. After transmitting for a detected movement, the PIR Camera will not retransmit for 1 minute. Any detected movement during this period will reset the sleep time to 1 minute. Continuous movement in front of the PIR Camera will therefore not exhaust the battery.

## _Battery and Low Battery Detection_

The PIR Camera uses three **CR123A 3V Lithium batteries** as its power source. Remove the Battery Compartment Cover and insert the batteries to activate the PIR Camera.

The PIR Camera features a Low Battery Detection function. When the battery voltage is low, the PIR Camera will transmit a Low Battery signal to the Control Panel. If movement is detected under Low Battery conditions, the Blue LED will flash for 2 seconds.

When changing the battery, after removing the old battery, press the Tamper Switch or the Function Button twice to fully discharge before inserting new batteries

## _**Tamper Protection**_

The PIR Camera is protected by a tamper switch which is compressed when the PIR Camera is properly installed. When the PIR Camera is removed from the mounted surface or its cover opened, the tamper switch will be activated and the PIR Camera will send a tamper open signal to the system control panel to remind the user of the condition. If movement is detected when the tamper switch is open, the Blue LED will flash for 2 seconds.

## _**Supervision**_

The PIR Camera will conduct a Self-test Periodically by transmitting a supervisory signal once every 30 to 50 minutes.

## _**Test Mode**_

* Test mode is for you to check the PIR camera’s detection range (not shooting coverage).
* Press the Function button once to enter Test mode for 3 minutes, the Blue LED will flash for 1 second.
* The PIR camera will warm up for 30 seconds. Please do not trigger the Camera during this warming-up period.
* After the warm-up period, you can trigger PIR camera to check IR detection range. If PIR camera is triggered, the Blue LED will flash for 2 seconds.
*
* For Test Mode to run smoothly, It is recommended to disable the sleep timer.

## _Learning_

* Remove the Battery Compartment Cover by loosening the Battery Compartment Screw.
* Insert the batteries. Orient the battery according to the polarity indication.
* Put the Control Panel into learning mode, refer to Control Panel manual for details.
* Press and hold the function button for 3 seconds, and release the button when the Blue LED lights up. (For the battery-operated panel, after pressing and holding the function button for 3 seconds, please press the function button **again** for one second.)
* The Blue LED will light on for 25 seconds in learning mode, add PIR Camera into the Control Panel during this period (refer to your Control Panel to finish the learning process). If the PIR is successfully added to the Control Panel, the Blue LED will flash 6 times to indicate. If PIR is not added within 25 seconds, please repeat the learning process.

{% hint style="info" %}
Note:

* If the PIR Camera already exists in a Control Panel system, you will need to first remove the PIR Camera from the Control Panel before you can learn it into a different Control Panel.
* When learning the PIR Camera into a repeater/router, please press the function button once (instead of pressing and holding it for 3 seconds) to send a learn code. (P5 models only)
{% endhint %}

## _Walk Test_

* After the PIR Camera is learnt-in, put the Control Panel into “**Walk Test**” mode, hold the PIR Camera in the desired location, and press the Function Button to confirm this location is within signal range of the Control Panel, refer to Control Panel manual to complete Walk Test.
* When you are satisfied that the PIR Camera works in the chosen location, you can proceed to mount.

## _**Edit PIR Camera Operation Area**_

* Follow the instructions below to change the PIR Camera Area in the Control Panel

1. Use the panel Edit Device function to change the PIR Camera area setting.
2. Press and hold the function button for 3 seconds on the PIR Camera to send a signal to the panel, and then release the button when the LED lights up. (For the battery-operated panel, after pressing and holding the function button for 3 seconds, please press the function button **again** for one second to send a signal.)

## Installation

### _Installation Guideline_

* The PIR Camera is designed to be mounted on either a flat surface or in a corner situation with fixing screws and plugs provided.
* The base has knockouts, where the plastic is thinner, for mounting purposes. Two knockouts are for surface fixing and a triangular mounting bracket is used for corner fixing.
* The detection range is up to 12 meters if the PIR Camera is mounted 2 meters above ground.
* The Pet-Immune models give a typical PET IMMUNE range of 7 meters when mounted at 1.9 to 2 meters above ground. If required, you can adjust the height of the PIR Camera according to the size of your pet for optimal pet immune performance. A higher installation location will provide a larger pet-immune space but also increase the blind spot under the PIR Camera.
* When VST-862 is mounted with a rotating bracket, it will not have the regular detection area (as in the diagram), or the typical pet immue range.

![](<.gitbook/assets/5 (15).png>)

**It is recommended to install the PIR Camera in the following locations**

* Mount where the animals cannot come to the detection area by climbing on furniture or other objects.
* Don’t aim the detector at stairways the animals can climb on.
* In a position such that an intruder would normally move across the PIR’s field of view.
* Between 1.9 and 2m above ground for best performance.
* In a corner to give the widest view.
* Where its field of view will not be obstructed e.g. by curtains, ornaments etc.
* **Limitations**
* Do not install the PIR Camera completely exposed to direct sunlight.
* Avoid installing the PIR Camera in areas where devices may cause rapid changes of temperature in the detection area, i.e. air conditioners, heaters, etc.
* Avoid large obstacles in the detection area.
* Not pointing directly at sources of heat e.g. Fires or boilers, and not above radiators.
* Avoid moving objects in the detection area i.e. curtain, wall hanging etc.
* **Be sure to always remain the RSSI signal strength steady at “4”.**



<figure><img src=".gitbook/assets/3 (111).png" alt=""><figcaption></figcaption></figure>

## _Mounting the PIR Camera_

* ![852 r3 knockouts](<.gitbook/assets/6 (11).jpeg>)
* The PIR is designed to be mounted on either a flat surface or in a corner situation with fixing screws and plugs provided.
* For corner mounting, a triangular bracket is provided to add Back Tamper Protection. The bracket also includes two knockouts to mount on the wall.
* For surface mounting, an optional rotating bracket is provided for users to adjust the range of detection. With the rotating bracket, the VST-862 can be rotated 80 degrees horizontally and 70 degrees vertically to provide optimal coverage.

### **Corner mounting:**

1. Break through the two knockouts on the triangular bracket.
2. Use the two holes as a template to drill holes on the corner surface.
3. Insert the wall plugs.
4. Screw the triangular bracket into the wall plugs with the two pointing sticks on top facing you.
5. Fit the PIR Camera onto the hooks of the triangular bracket.

### **Surface mounting:**

<figure><img src=".gitbook/assets/1 (112).png" alt=""><figcaption></figcaption></figure>

1. Open the cover by loosening the Cover Screw using a Philips screwdriver. Screw the rotating bracket into the wall.
2. Break through the 2 Surface knockouts at the centre of the base.
3. Use the holes as a template to drill holes on the surface.
4. Insert the wall plugs if fixing it into plaster or brick.
5. Screw the base into the wall plugs.
6. Fit the cover onto the base and tighten.

### **Surface mounting with rotating bracket (optional item, sold separately):**

{% hint style="success" %}
Rotating Bracket code: VESTA-212&#x20;
{% endhint %}

The rotating bracket can be mounted on the wall with provides screws.

1. Screw the rotating bracket into the wall
2. Fit the 3 hooks of the rotating bracket into the 3 holes of the base accordingly.
3. Rotate the bracket for the proper range of detection and tighten the fixing screw.

Note: Control error or error control is because a device normally PIRCAM or pir camera has not been added by pressing the learn button for 4 seconds.



<figure><img src=".gitbook/assets/2 (121).png" alt=""><figcaption></figcaption></figure>









