# VESTA 008 LED

**PIR Motion Sensor Camera**

**VST-862**

**Introduction**

VST-862 is a passive infrared (PIR) motion sensor camera. It is capable of sending wireless signals and captured images (picture quality of up to 640 x 480 pixels) to the Control Panel upon movement detection.

The PIR Camera is designed to give a typical detection range of 12 meters when mounted at 2 meters above ground. The pet-immune models support pet immunity up to 27 kg within 7 meters range to minimize false alarm situation. For models that are compatible with Climax’s Repeater RP-29/Router RMB-29 **(P5 models only)**, the RF communication range can be further extended into hard-to-reach areas.

The PIR Camera consists of a two-part design made up of a cover and a base. The cover contains all the electronics and optics and the base provides a means of fixing. The base has knockouts to allow mounting on either a flat surface or in a corner situation with a triangular bracket for corner mounting.

**The VST-862 Series includes the following models:**

| **Model Name**   | **Flash LED** | **Infrared LED** | **Pet Immune** | **Compatible with** |
| ---------------- | ------------- | ---------------- | -------------- | ------------------- |
|                  |               |                  |                | **Repeater**        |
| VST-862-(P5)     | V             |                  |                | P5 model only       |
|                  |               |                  |                |                     |
| VST-862-IL-(P5)  |               | V                |                | P5 model only       |
|                  |               |                  |                |                     |
| VST-862P-(P5)    | V             |                  | V              | P5 model only       |
|                  |               |                  |                |                     |
| VST-862P-IL-(P5) |               | V                | V              | P5 model only       |
|                  |               |                  |                |                     |

![](<.gitbook/assets/0 (30).jpeg>)

**Parts Identification**

**1.** **Flash LED / Infrared LED**

The Flash LED (For 862(P)) or Infrared LED (For 862(P)-IL) delivers sufficient light for image capture under low lighting condition.

**2. Blue LED/Function Button**

**Blue LED:**

(Please refer to _**LED Indicator**_ description below for details)

**Function Button Usage:**

*
  * Press and hold the button for 3 seconds to send a learn code, release when Blue LED light on. (For battery-operated panel, after pressing and holding the button for 3 seconds, please press the button **again** for one second to send a learn code.)
  * Press the button once to enter test mode for 3 minutes.
  * Press the button once to send a learn code to the repeater/router. (P5 models only)

1. **IR Sensor**
2. **PIR Camera Lens**
3. **Battery Compartment Cover**
4. **Tamper Switch**
5. **Battery Compartment**
6. **Sensitivity Adjustment Jumper Switch (JP3)**

![](<.gitbook/assets/1 (40).png>)

**Jumper On** **Jumper Off**

![](<.gitbook/assets/2 (17).jpeg>)

The jumper link is inserted connecting the two pins.

if the jumper link is removed

or “**parked**” on one pin.

*
  * Jumper On: the PIR’s sensitivity level is set to High.
  * Jumper Off: the PIR’s sensitivity level is set to Normal. (**Factory Default**)

1. **Sleep Timer Jumper Switch (JP2)**

![](<.gitbook/assets/3 (40).png>)

**Jumper On**

![](<.gitbook/assets/4 (15).jpeg>)

The jumper link is inserted connecting the two pins.

**Jumper Off**

if the jumper link is removed

or “**parked**” on one pin.

* Jumper On: After movement detection, the PIR Camera does not enter sleep mode and will transmit detection signal again immediately if triggered (**Factory Default**).
* Jumper Off: PIR Camera has a “**sleep time**” of approximately 1 minute after motion detection to conserve power.

1

**Features**

![](<.gitbook/assets/5 (35).png>)

* _**LED Indicator**_

In Normal operation mode, the Blue LED will not light except in the following situations:

*
  * When the PIR Camera is in low battery condition, every time it transmits a detected movement, the Blue LED will flash for 2 seconds.
  * When the cover is opened and the tamper switch is violated, the Blue LED will flash for 2 seconds, to indicate it is transmitting “Tamper” signal.
  * When the Tamper condition persists, every time it transmits a detected movement, the Blue LED will flash for 2 seconds.
  * When PIR Camera enters Test Mode, the Blue LED will flash for 1 second. During Test mode, the Blue LED will also flash for 2 seconds every time a movement is detected.
  * When the PIR Camera is in 30 seconds warm up period, the Blue LED will slow flash.
  * When the PIR Camera is transmitting captured images under fault conditions (low battery, tamper switch activated), the Blue LED will continuous flash.
* _**Image Capture**_

![](<.gitbook/assets/6 (24).png>)

When the alarm system is armed, the PIR Camera will capture 1, 3 or 6 alarm images in 640 x 480 or 320 x 240 resolutions (programmable from Control Panel) upon movement detection. You can also manually request the PIR Camera to take a picture through the Control Panel. The captured images will be transferred to the Control Panel for users to view.

![](<.gitbook/assets/7 (21).png>)

_\<NOTE>_

*
  * If your PIR Camera is installed at a location where the camera’s field of view is a complex environment with intense light or lots of colors, the images captured will be great in file size, possibly leading to truncation when the images are transmitted to the Control Panel.
* _**Warm Up Period**_

![](<.gitbook/assets/8 (23).png>)

When the Control Panel system enters arm mode, or when PIR Camera is put into Test Mode, the PIR Camera will warm up for 30 seconds. During the 30-second warm up period, the PIR Camera will not be activated. The Blue LED will slow flash during the warm up period only when PIR enters for Test Mode.

![](<.gitbook/assets/9 (27).png>)

* _**Sleep Timer**_

When **Jumper Switch 2** is set to Off, the PIR Camera has a “**sleep time**” of approximately 1 minute to conserve power. After transmitting for a detected movement, the PIR Camera will not retransmit for 1 minute. Any detected movement during this period will reset the sleep time to 1 minute. Continuous movement in front of the PIR Camera will therefore not exhaust the battery.

![](<.gitbook/assets/10 (5).jpeg>)

* _**Battery and Low Battery Detection**_

The PIR Camera uses two **1.5V “AA” Alkaline batteries** in series connection as its power source. Remove the Battery Compartment Cover and insert the batteries to activate the PIR Camera.

The PIR Camera features Low Battery Detection function. When the battery voltage is low, the PIR Camera will transmit Low Battery signal to the Control Panel. If movement is detected under Low Battery condition, the Blue LED will flash for 2 seconds.

When changing battery, after removing the old battery, press the Tamper Switch or the Function Button twice to fully discharge before inserting new batteries

![](<.gitbook/assets/11 (16).png>)

* _**Tamper Protection**_

The PIR Camera is protected by a tamper switch which is compressed when the PIR Camera is properly installed. When the PIR Camera is removed from mounted surface or its cover opened, the tamper switch will be activated and the PIR Camera will send a tamper open signal to the system control panel to remind the user of the condition. If movement is detected when the tamper switch is open, the Blue LED will flash for 2 seconds.

![](<.gitbook/assets/12 (18).png>)

* _**Supervision**_

The PIR Camera will conduct a Self-test Periodically by transmitting a supervisory signal once every 90 to 110 minutes.

![](<.gitbook/assets/13 (17).png>)

* _**Test Mode**_
  * Test mode is for you to check the PIR camera’s detection range (not shooting coverage).
  * Press the Function button once to enter Test mode for 3 minutes, the Blue LED will flash for 1 second.
  * The PIR camera will warm up for 30 seconds. Please do not trigger the Camera during this warming-up period.
  * After the warm-up period, you can trigger PIR camera to check IR detection range. If PIR camera is triggered, the Blue LED will flash for 2 seconds.
* _**Learning**_
  * Power on the PIR Camera by pulling out the battery insulator located at the battery compartment cover.
  * Put the Control Panel into learning mode, refer to Control Panel manual for details.
  * Press and hold the function button for 3 seconds, release the button when the Blue LED lights up. (For

![](<.gitbook/assets/14 (7).jpeg>)

2

battery-operated panel, after pressing and holding the function button for 3 seconds, please press the function button **again** for one second.)

* The Blue LED will light on for 25 seconds in learning mode, add PIR Camera into the Control Panel during this period (refer to your Control Panel to finish learn in process). If the PIR is successfully added into the Control Panel, the Blue LED will flash 6 times to indicate. If PIR is not added within 25 seconds, please repeat learning

process.

![](<.gitbook/assets/15 (15).png>)

_\<NOTE>_

*
  *
    *
      * If the PIR Camera already exists in a Control Panel system, you will need to first remove the PIR Camera from the Control Panel before you can learn it into a different Control Panel.
      * When learning the PIR Camera into a repeater/router, please press the function button once (instead of pressing and holding it for 3 seconds) to send a learn code. (P5 models only)
* _**Walk Test**_
  * After the PIR Camera is learnt-in, put the Control Panel into “**Walk Test**” mode, hold the PIR Camera in the desired location, and press the Function Button to confirm this location is within signal range of the Control Panel, refer to Control Panel manual to complete Walk Test.
  * When you are satisfied that the PIR Camera works in the chosen location, you can proceed to mounting.
* _**Edit PIR Camera Operation Area**_
  * Follow instructions below to change PIR Camera Area in the Control Panel
    1. Use the panel Edit Device function to change PIR Camera area setting.
    2. Press and hold the function button for 3 seconds on the PIR Camera to send a signal to the panel, and then release the button when the LED lights up. (For battery-operated panel, after pressing and holding the function button for 3 seconds, please press the function button **again** for one second to send a signal.)

![](<.gitbook/assets/16 (1).jpeg>) ![](<.gitbook/assets/17 (12).png>)

**Installation**

![](<.gitbook/assets/18 (1).jpeg>)

* _**Installation Guideline**_
  *
    * The PIR Camera is designed to be mounted on either a flat surface or in a corner situation with fixing screws and plugs provided.
    * The base has knockouts, where the plastic is thinner, for mounting purpose. Two knockouts are for surface fixing and a triangular mounting bracket is used for corner fixing.
    * The detection range is up to 12 meters if the PIR Camera is mounted 2 meters above ground.
    * The Pet-Immune models give a typical PET IMMUNE range of 7 meters when mounted at 1.9 to 2 meters above ground. If required, you can adjust the height of the PIR Camera according to the size of your pet for optimal pet immune performance. Higher installation location will provide larger pet-immune space, but also increases the blind spot under the PIR Camera.
  * When VST-862 is mounted with rotating bracket, it will not have the regular detection area (as in the diagram), or the typical pet immue range.

![](<.gitbook/assets/19 (1).jpeg>)

**It is recommended to install the PIR Camera in the following locations**

* Mount where the animals cannot come to the detection area by climbing on furniture or other objects.
* Don’t aim the detector at stairways the animals can climb on.
* In a position such that an intruder would normally move across the PIR’s field of view.
* Between 1.9 and 2m above ground for best performance.
* In a corner to give the widest view.
* Where its field of view will not be obstructed e.g. by curtains, ornaments etc.

3

* **Limitations**

|  | Do not install outdoors.                            |  | Avoid large obstacles in the detection area.     |
| - | --------------------------------------------------- | - | ------------------------------------------------ |
|   |                                                     |   |                                                  |
|  | Do not install the PIR completely exposed to        |  | Avoid vapor or high humidity that can cause      |
|   | direct sunlight.                                    |   | condensation.                                    |
|   |                                                     |   |                                                  |
|  | Avoid moving objects in the detection area i.e.     |  | Avoid reflected light from bright surfaces, e.g. |
|   | curtain, wall hanging etc.                          |   | mirror, window.                                  |
|   |                                                     |   |                                                  |
|  | Avoid installing the PIR in areas where devices     |  | Avoid reflecting surface in the detection area.  |
|   | may cause rapid change of temperature in the        |   | Reflected infrared signatures may lead to false  |
|   | detection area, i.e. air conditioner, heaters, etc. |   | alarm.                                           |
|   |                                                     |   |                                                  |

![](<.gitbook/assets/20 (11).png>)

* **Be sure to always remain the RSSI signal strength steady at “4”.**

4

* _**Mounting the PIR Camera**_
  * The PIR is designed to be mounted on either a flat surface or in a corner situation with fixing screws and plugs provided.
  * For corner mounting, a triangular bracket is provided to add Back Tamper Protection. The bracket also includes two knockouts to mount on the wall.
    * For surface mounting, an optional rotating bracket is provided for users to adjust the range of detection. With the rotating bracket, the VST-862 can be rotated 80 degrees horizontally and 70 degrees vertically to provide optimal coverage.
    * **Corner mounting:**
      1. Break through the two knockouts on the triangular bracket.
      2. Use the two holes as template to drill holes on the corner surface.
      3. Insert the wall plugs.
      4. Screw the triangular bracket into the wall plugs with the two pointing sticks on top facing you.
      5. Fit the PIR Camera onto the hooks of the triangular bracket.
    * **Surface mounting:**
      1. Open the cover by loosening the Cover Screw using a Philips screwdriver.
      2. Break through the 2 Surface knockouts at the center of base.
      3. Use the holes as template to drill holes on the surface.
      4. Insert the wall plugs if fixing it into plaster or brick.
      5. Screw the base into the wall plugs.
      6. Fit the cover onto the base and tighten.
  * **Surface mounting with rotating bracket (optional item, sold separately):**

The rotating bracket can be mounted on the wall with the provided screws.

*
  *
    *
      *
        1. Screw the rotating bracket into the wall.
        2. Fit the 3 hooks of the rotating bracket into the 3 holes of the base accordingly.
        3. Rotate the bracket for the proper range of detection and tighten the fixing screw.

5
