# VESTA-382

&#x20;**IRAGS-35SL-F1-2W-868**

## **PIR Plus Glass Break Detector**

<figure><img src=".gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

### Introduction

IRAGS-35 integrates two sensors, the PIR motion sensor & glass break detector, into a single device, featuring the detections of movements within an assigned area and signals the Control Panel to activate the alarm if an intruder crosses its’ path of detection as well as breakage of glass windows.

The PIR is designed to give a typical detection range of 12 meters when mounted at a height of 2.5 meters above the ground and supports pet immunity function to avoid false alarm. The glass break detector is able to detect high-frequency sound emitted by glass breakage as well as low-frequency sound emitted by glass impact.

The detector consists of a cover and a base. The cover contains all the electronics and optics and the base provides a means of fixing.

## Parts Identification![](<.gitbook/assets/2 (141).png>)

<figure><img src=".gitbook/assets/0 (142).jpeg" alt=""><figcaption></figcaption></figure>

1. **Test Button / LED Indicator**
   * The Test Button is used for testing the radio performance and for learning purpose.
   * The LED indicator is used to indicate the status of system.
2. **Microphone**
3. **IR Sensor**
4. **Battery Compartment**
5. **Pet Immunity Enable/Disable Jumper Switch (JP3)**

*

    <figure><img src=".gitbook/assets/4 (81).jpeg" alt=""><figcaption></figcaption></figure>

**Jumper On,** The jumper link is inserted, connected to the two pins.

**Jumper Off,** The jumper link is removed  or “**parked**” on one pin.

![](<.gitbook/assets/5 (59).jpeg>)![](<.gitbook/assets/6 (106).png>)![](<.gitbook/assets/7 (71).jpeg>)

* When set as ON, Pet Immunity is disabled (Factory default).
* When set as OFF, Pet Immunity is enabled.

6. **Sensitivity Increaser Jumper Switch (JP4)**

* When set as ON, the PIR’s detection sensitivity is high.
* When set as OFF, the PIR’s detection sensitivity is in normal level (Factory default).

7. **Tamper Switch**
8. **Hook Holes**
9. **Mounting Bracket**

## Features

### LED Indicator

#### Red LED (for PIR)

In Normal operation mode, the LED Indicator will light up in the following situations:

* When movement is detected under low battery condition or under Test Mode
* When the cover is opened and the tamper switch is triggered
* When movement is detected if the tamper condition continues
* When the Test Button is pressed under the tamper condition or if PIR is low in battery

The LED will not flash if the PIR tamper and battery are normal and PIR is not under test mode.

If the LED flashes to indicate signal transmission, it will flash twice rapidly upon receiving acknowledgement from the Panel. The LED will slowly turn on and then turn off when Remote Setting from the Control Panel is successfully applied.

#### Orange LED (for Glass Break Detector)

* The Orange LED will light up when the Test Button is pressed.
* The Orange LED will slowly turn on and then turn off when Remote Setting from the Control Panel is successfully applied.
* The Orange LED will light up when glass break is detected under test mode.

(The Orange LED does not light up when glass break is detected during normal operation.)

#### Green LED (for Glass Break Detector)

* The Green LED will flash rapidly when glass striking is detected under test mode.
* The Green LED will flash per second in test mode.

### Battery and Low Battery Detection

The detector uses three CR123 3V Lithium batteries as its power source:

The detector features low-battery detection function. If low battery voltage is detected, a low-battery signal will be sent to the Control Panel along with the regular signal transmissions for the Control Panel to display the status accordingly.

{% hint style="warning" %}
Note:

When changing the batteries, press the Tamper Switch or Test Button a couple times after removing the old ones to fully drain the residual energy before inserting new ones.
{% endhint %}

### Tamper Protection

IRAGS-35 is protected by a tamper switch which is depressed when the detector is properly installed.

When IRAGS-35 is removed from the mounting surface, or when its cover is opened, the tamper switch will be activated and the detector will send a tamper-open signal to the control panel to remind the user of the condition. If any movement is detected when the tamper switch is open, the LED for PIR will light up.

### Supervision

When IRAGS-35 is in normal operation mode, it will conduct a self-test periodically by transmitting a supervisory signal once every 90 to 110 minutes.

If the Control Panel fails to receive the supervisory signals transmitted for a preset time, an “**Out-Of-Order**” fault message will be generated.

### Sleep Timer

* IRAGS-35 has a “**sleep time**” of approximately **1 minute** to conserve power.
* During the **1-minute sleep time**, the PIR will not transmit any signals; any further movement detected in this period will extend the sleep time by another minute. This way, continuous movement in front of the PIR will not unduly exhaust the battery.
* Depending on the Sleep Mode setting (Normal or Optimized), the PIR will enter **sleep time** for **1 minute** after transmitting a detected movement or 3 detected movements within 1 minute.

{% hint style="warning" %}
Note:

The sleep mode setting is remotely configurable. When sleep mode is set to Normal, the PIR will enter sleep time for 1 minute after transmitting a detected movement. When sleep mode is set to Optimized, the PIR will enter sleep time for 1 minute after transmitting 3 detected movements within 1 minute. Please refer to _**Remote Setting**_ section below for details.
{% endhint %}

### Test Mode

* By pressing the Test Button, the PIR and Glass Break Detector can be put into test mode for **3 minutes** to test the PIR’s signal transmission and to check the glass break detection range. In test mode, the Green LED will flash every second.
* In test mode, if a movement is detected, the Red LED indicator for PIR will light up.
* In test mode, if glass break is detected, the Green LED will flash rapidly and the Orange LED will light up.
* Pressing the Test Button again in test mode will extend the test mode duration to another **3 minutes**. Test Mode will time out after 3 minutes.

### _**Testing the Glass Break Detector**_

The glass break detector should be tested to ensure it is able to detect glass breakage successfully.

<figure><img src=".gitbook/assets/image (16) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

#### Testing Tool

Use FlexGuard FG-701 Glassbreak Simulator to create glass break sound.

1. Set the switches on FG-701 to “FLEX” and “TEST” mode. Press the red start button.
2. Put FG-701 at the desired testing location on the glass point the speaker at IRAGS-35. Close the window covering if it is present.

<figure><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

3. Strike the glass with a cushioned tool to create a glass striking sound. When FG-701 detects the glass striking sound, it will emit a glass break sound.

#### Testing the Glass Break Detector

Put the detector at the desired installation location. Make sure the sensitivity level is adjusted based on the detection range.

For optimal detection, IRAGS-35 should face windows to monitor glass breakage.

1. Press the Test Button once, and the device will enter test mode for 5 minutes. The Green LED will flash slowly.
2. Press the red start button on FG-701. Within 8 seconds after the button press, strike the glass with a cushioned tool to create a glass strike sound. FG-701 will produce a burst of glass break audio.
3. IRAGS-35 will be activated if both the glass striking and glass break sounds are properly received. The Green LED will flash quickly and the Orange LED will light up. A glass-break signal will be sent to the Control Panel.

{% hint style="warning" %}
Note:

After the red start button on the FG-701 is pressed, if there is no strike action performed within the 8 seconds, the simulator will automatically “click” off. You will need to press the red start button again to restart testing.
{% endhint %}

### Glass Thickness

Float Glass: 3 mm to 6.4 mm (1/8 to 1/4”)

Tempered Glass: 2.4 mm to 6.4 mm (3/32 to 1/4”)

Wired Glass: 3.2 mm to 6.4 mm (1/8 to 1/4”)

Laminated Glass: 3.2 mm to 6.4 mm (1/8 to 1/4”)

### PIR Pet Immunity Function

IRAGS-35 supports pet immunity feature and will not detect pets of up to 25 kg to minimize false alarm situation. The Pet Immunity function can be enabled or disabled by setting the position of Pet Immunity Jumper Switch (JP3). When the Jumper Switch (JP3) is set to ON, Pet Immunity is disabled (factory default). When the Jumper Switch (JP3) is set to OFF, Pet Immunity is enabled. The pet immunity function can also be adjusted by remote setting as described in the _**Remote Setting**_ section below.

### Sensitivity Setting

#### For PIR Motion Sensor

You can use the sensitivity increaser jumper switch (JP4) to increase the PIR’s detection sensitivity.

To increase detection sensitivity, set JP4 to ON. To maintain normal detection sensitivity, set JP4 to OFF (Factory default). The sensitivity for PIR can also be adjusted by remote setting as described in the _**Remote Setting**_ section below.

#### For Glass Break Detector

The sensitivity for Glass Break Detector can only be adjusted on Control Panel’s webpage. Please refer to the _**Remote Setting**_ section below.

Adjusting the sensitivity will change the detection range. The detector will send alarm signals to the Control Panel according to different sensitivity levels set in the Control Panel. The sensitivity levels include maximum, medium, low and minimum. The sensitivity is set to Maximum (high) by default.

<table data-header-hidden><thead><tr><th width="372"></th><th></th></tr></thead><tbody><tr><td><strong>Sensitivity</strong></td><td><strong>Detection Range</strong></td></tr><tr><td>Maximum (High)</td><td>8m</td></tr><tr><td>Medium (Med.)</td><td>5m</td></tr><tr><td>Low (Low)</td><td>3m</td></tr><tr><td>Minimum (Lower)</td><td>1.5m</td></tr></tbody></table>

### Flex & Audio Detection

* The Glass Break Detector features the detection of low-frequency sound for glass impact (flex) as well as high-frequency sound for glass breakage (audio).
* Normally the Glass Break Detector will trigger an alarm when it detects glass impact followed by glass breakage.
* If you disable the flex detection for glass impact, the Glass Break Detector will trigger an alarm once it detects a high-frequency sound.

{% hint style="warning" %}
Note:

Disabling the flex detection for glass impact will increase the possibility of false alarms due to environmental sounds.
{% endhint %}

* If both Flex and Audio Detection are disabled, the Glass Break Detector is essentially turned off.

### Remote Setting for Sensitivity

#### For PIR Motion Sensor

When the PIR is powered on, its pet immunity function and sensitivity are determined by adjusting the JP3 and JP4 settings or remotely change the pet immunity and sensitivity settings from the Control Panel. Remote setting will overwrite the jumper settings.

**Control Panel Webpage**

1. On the Panel’s local webpage, go to the Device Edit page by clicking “Edit” of the IR entry.
2. Press the Test Button once and then the Sensor Setting section will be shown. Enter the value for the desired settings and click OK to confirm.

<figure><img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Please refer to the table below for configuration details. For example, if you want to enable Pet Immunity, set Sensitivity level to “normal” and Sleep Mode to “optimized”, you can input 06.

<table data-header-hidden><thead><tr><th width="160"></th><th width="135"></th><th width="179"></th><th></th></tr></thead><tbody><tr><td><strong>IR Configuration</strong></td><td><strong>Pet Immunity</strong></td><td><strong>Sensitivity</strong></td><td><strong>Sleep Mode</strong></td></tr><tr><td>00</td><td>No</td><td>Normal</td><td>Normal (1 detection)</td></tr><tr><td>01</td><td>No</td><td>High</td><td>Normal (1 detection)</td></tr><tr><td>02</td><td>Yes</td><td>Normal</td><td>Normal (1 detection)</td></tr><tr><td>03</td><td>Yes</td><td>High</td><td>Normal (1 detection)</td></tr><tr><td>04</td><td>No</td><td>Normal</td><td>Optimized (3 detections)</td></tr><tr><td>05</td><td>No</td><td>High</td><td>Optimized (3 detections)</td></tr><tr><td>06</td><td>Yes</td><td>Normal</td><td>Optimized (3 detections)</td></tr><tr><td>07</td><td>Yes</td><td>High</td><td>Optimized (3 detections)</td></tr></tbody></table>

3. Press the Test Button once to send a signal to the Control Panel, and the new settings will be applied immediately. If the button is not pressed, the new settings will be applied upon next signal transmission, i.e., transmission of the supervisory signal or IR trigger signal.

The Red LED for PIR will slowly turn on and then turn off when the IR Configuration from the Control Panel is successfully set.

**Home Portal Server**

I. On Home Portal Server, go to the Device setting page, click the IR-35 device row and select “IR Configuration.”

&#x20;II. Select the desired setting for Pet Immunity (Enable/Disable), Sensitivity (High/Normal), and Sleep Mode (Normal/Optimized) from the drop-down lists, and click “Submit” to confirm the setting.

III. Press the Test button once to send a signal to the Control Panel, and the new settings will be applied immediately. If the button is not pressed, the new settings will be applied upon next signal transmission, i.e., transmission of the supervisory signal or IR trigger signal.

#### For Glass Break Detector

Functions for the Glass Break Detector can only be set on the Control Panel’s webpage. Functions configurable are audio (high-frequency detection for glass breakage sound), flex (low-frequency detection for glass impact sound) and sensitivity.

**Control Panel Webpage**

1. Click “Edit” of the Glass entry on the Control Panel’s webpage.
2. Press the Test Button once and then the Sensor Setting section will be shown.

<figure><img src=".gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

3. Fill in the configuration value according to the table below and click OK to confirm.

<table data-header-hidden><thead><tr><th></th><th></th><th width="178"></th><th></th></tr></thead><tbody><tr><td><strong>ACGS Configuration</strong></td><td><strong>Audio (Glass Breakage)</strong></td><td><strong>Flex (Glass Impact)</strong></td><td><strong>Sensitivity</strong></td></tr><tr><td>01xx</td><td>Disable (ACGS Detector turned off)</td><td></td><td></td></tr><tr><td>0000</td><td>Enable</td><td>Enable</td><td>Lower</td></tr><tr><td>0001</td><td>Enable</td><td>Enable</td><td>Low</td></tr><tr><td>0002</td><td>Enable</td><td>Enable</td><td>Medium</td></tr><tr><td>0003 (Default)</td><td>Enable</td><td>Enable</td><td>High</td></tr><tr><td>0008</td><td>Enable</td><td>Disable</td><td>Lower</td></tr><tr><td>0009</td><td>Enable</td><td>Disable</td><td>Low</td></tr><tr><td>000A</td><td>Enable</td><td>Disable</td><td>Medium</td></tr><tr><td>000B</td><td>Enable</td><td>Disable</td><td>High</td></tr></tbody></table>

{% hint style="warning" %}
Note:

&#x20;Disabling the flex detection for glass impact will increase the possibility of false alarms due to environmental sounds
{% endhint %}

4. Press the Test Button once to apply new setting of the sensitivity level set in the Control Panel immediately. If the button is not pressed, the new settings will be applied upon next signal transmission. The Orange LED will slowly turn brighter and then turn dark, indicating the programming command from the Control Panel is successfully set for the Glass Break Detector.

## Getting Started

* Place the batteries in correctly to power the device.
* The LED indicator will flash for 30 seconds (the PIR is warming up). During the warm-up period, the PIR will not be activated. After the warm-up period is over, the LED will turn off and the PIR will be ready for operation.
* Put the Control Panel into learning mode and learn the detector into the Panel (refer to Control Panel manual for details).
* Press the test button to send a learn code to the Control Panel.
* IRAGS-35 will be recognized as two separate devices (i.e., PIR & Glass Break Detector), occupying two zones after being learned into the Control Panel.
* After the detector is learnt-in, put the Control Panel into “**Walk Test**” mode; hold the detector in the desired location, and press the Test button to confirm that this location is within the signal range of the Control Panel (refer to Control Panel manual to complete the Walk Test).
* When you are satisfied that the detector works well in the chosen location, you can proceed with mounting.

<figure><img src=".gitbook/assets/image (4) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (5) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

## Installation

### Installation Guideline

* When the detector is mounted at a height of 2.3-2.5 meters above the ground, the PIR’s detection range is up to 12 meters.
* For optimal detection of glass break, the detector should face the window to monitor the glass breakage.
* When Pet-Immunity function is enabled, the PIR will not detect pets up to 25 kg when mounted at the height of 2.3-2.5 meters above the ground. If required, you can adjust the height of the PIR according to the size of your pet for optimal pet immunity performance. Higher installation location will provide larger pet-immune space, but will increase
* After the installation site is selected, press the Test Button to enter Test Mode. Walk around the protected area noting when the LED lights up and check that the detection coverage is adequate.
* When detection coverage is found to be satisfying, follow the steps described in _**Mounting Method**_ section below to mount the detector.

### Mounting Method

#### **Surface/Corner Mounting with the mounting bracket**

* The detector is designed to be mounted either on a flat surface or in a corner.
* The provided mounting bracket has two central screw holes for surface fixing and four side screw holes for corner fixing.
* To mount the Detector with the mounting bracket:
  1. Depending on whether you are mounting on a surface or in a corner, use the two central screw holes or the four side screw holes as a template, and drill holes into the mounting surface.
  2. (Optional) Insert the wall plugs if the detector is to be fixed onto plaster or bricks.
  3. Screw the mounting bracket onto the wall plugs with the two pointing sticks on top and facing you.
  4. Hook the detector onto the mounting bracket and push it downwards to lock it in place.

{% hint style="warning" %}
Note:

Please make sure the PIR Camera is properly hooked onto the mounting bracket, so that the tamper switch is fully depressed.
{% endhint %}

#### **Surface Mounting**

<figure><img src=".gitbook/assets/image (6) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

#### **Corner Mounting**

<figure><img src=".gitbook/assets/image (7) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

* **(Optional) Stabilizing Screw for the Mounting Bracket**

An extra screw is provided for stabilizing the base of the PIR Camera onto the mounting bracket.

To use the stabilizing screw, you will need to detach the PIR Camera’s front cover from the base. After hooking the base of the PIR Camera onto the mounting bracket, tighten the stabilizing screw from the base. Re-place the front cover and tighten the bottom fixing screw.

**Surface Mounting**

<figure><img src=".gitbook/assets/image (8) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

**Corner Mounting**

<figure><img src=".gitbook/assets/image (9) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

* **Surface Mounting without the mounting bracket**
  * The PIR Camera can also be mounted on a flat surface with the fixing screws and wall plugs without the mounting bracket.
  * The base has three knockouts, where the plastic is thinner and can be broken for mounting purpose.
  * To mount the Detector without the mounting bracket:
    1. Undo the bottom fixing screw and detach the front cover from the base.
    2. Break through the 3 knockouts from the inside of the base.
    3. Use the holes as a template and drill holes into the surface to be mounted.
    4. (Optional) Insert the wall plugs if the detector is to be fixed onto plaster or bricks.
    5. Screw base onto the wall plugs.
    6. Fit the upper part of the cover to the base, and then close the lower part.
    7. Tighten the bottom fixing screw to firmly attach the front cover to the base.

<figure><img src=".gitbook/assets/image (10) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

## _**Installation Recommendations**_

* **It is recommended to install the PIR & Glass Break Detector in the following locations:**
  * Face the window and mount at a height of 2.3-2.5 meters for best performance.
  * Avoid locations or stairways where animals cannot come to the detection area by climbing on furniture or other objects.
  * At a position such that an intruder would normally move across the PIR’s field of view from side to side.  In a corner to give the widest view.
  * At a position where its field of view will not be obstructed by e.g., curtains, ornaments etc.
  * Away from sound source such as speakers, air conditioners or motors.
  * As far from the windows or doors as possible to avoid external sound interference.
* **Limitations**

<figure><img src=".gitbook/assets/image (11) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (12) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>
