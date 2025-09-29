# VESTA-312

**PIR-ZW**

## **Mini-PIR-ZW Series**

<figure><img src=".gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

## **Introduction**

The Mini-PIR-ZW Series is a Z-Wave Passive Infrared Motion Sensor that is capable of sending wireless signals to the coordinator in the Z-Wave network upon movement detection. The PIR has optional built-in temperature/ambient light sensor which provides temperature/lux reading that will be transmitted via Z-Wave network in regular interval (Mini-PIR-LT-ZW model only).

The PIR can be configured using Z-Wave coordinator to function as either a security sensor which activate alarm when triggered, or an occupancy/vacancy sensor which controls home automation or lighting functions via Z-Wave coordinator.

The PIR is a Z-Wave enabled device and is fully compatible with any Z-Wave enabled network.

Z-Wave is a wireless communication protocol that uses a low-power RF radio. By taking advantage of the Z-Wave mesh network, commands can be transmitted to their destination via intermediary “listening” Z-Wave products.

The Mini-PIR-ZW Series includes the following models:

| **Model Name** | **Motion detection** | **Light & Temperature detection** |
| -------------- | -------------------- | --------------------------------- |
| Mini-PIR-ZW    | V                    |                                   |
| Mini-PIR-LT-ZW | V                    | V                                 |

## **Parts Identification**

The PIR is comprised of a main body and a base. The main body must be separated from the base for battery installation and Z-Wave network setup.

To separate the main body and base, hold the PIR in both hands, and turn the base to the right and the main body to the left to separate.

![](<.gitbook/assets/0 (71).png>)

**1. IR Lens w/ LED Indicator**

The LED Indicator is located at the center of the IR lens.

The LED indicator lights up in the following conditions:

* Flashes once: The PIR is transmitting learn code/factory reset.
* Flashes twice quickly: The PIR has successfully joined the Z-Wave network.
* Flashes under normal operation mode: The PIR has detected a movement and it is currently under Low Battery or Tamper open condition.

2. **Back Cover**

Remove the back cover to access battery compartment and function button.

3. **Function Button**

* Press the button once to send a supervision signal and enter Test Mode.
* Press for 3 times within 1.5 seconds to transmit a learn code.
* Press and hold the button for 10 seconds then release to Factory Reset.

4. **Battery Compartment**

The PIR is powered by one CR123A 3V Lithium battery.

5. **Base Angle Adjustment Screw**
6. **Wall Mounting Holes**

## **Features**

### _**Sleep Timer**_

The PIR has a “sleep time” of approximately 1 minute to conserve power. After transmitting a detected movement, the PIR will not retransmit for 1 minute. Any further movement detected during this sleep period will extend the sleep time by another minute. In this way continuous movement in front of a PIR will not unduly exhaust the battery.

### _**Motion Stop Signalling**_

After each movement detection, if 30 seconds pass without detection, the PIR will transmit a “motion stop” signal to Z-Wave network coordinator.

### _**Battery and Low Battery Detection**_

* The PIR uses one CR123A 3V Lithium battery as its power source. The PIR’s main body must be removed from base to access battery compartment. The battery compartment has a strip which should be pressed under the battery when battery is inserted. When removing batter, simply lift the strip.
* The PIR features Low Battery Detection function. When the battery voltage is low, the PIR will transmit Low Battery signal to the coordinator in Z-Wave network. If movement is detected under Low Battery condition, the LED Indicator will flash to indicate.
* The PIR will report its battery percentage to the Gateway/Control Panel respectively at 100%, 75%, 50% and 25%. If the battery voltage is low (25%), a Low Battery signal will be sent to the Control Panel to notify the user.
* If battery is not changed after Low Battery condition and is exhausted, the LED will flash every 2 seconds and the PIR will stop all operation.
* When changing battery, after removing the old battery, press the Function Button twice to fully discharge before inserting new battery

### _**Tamper Protection**_

The PIR is protected by a tamper switch which is located inside the PIR’s main body. The tamper switch is activated whenever the PIR is removed from the base, and the PIR will send a tamper open signal to remind the user of the condition. If movement is detected when the tamper switch is open, the PIR will flash to indicate.

### _**Supervision**_

This function uses the Z-Wave Wake Up Command Class. The Wake Up Command Class allows the battery-powered PIR to notify the Control Panel/Gateway that it is awake and ready to receive any queued commands. The wake up time period is programmed automatically according to Control Panel’s setting when The PIR is included. The recommended setting of the wake up time is 60 minutes above.

### _**Test Mode**_

* Test mode is for you to check the PIR’s detection range.
* Press the Function button once to enter Test mode for 3 minutes.
* During Test Mode, you can trigger PIR sensor to check its detection coverage. If PIR is triggered, the LED will light up to indicate.

### _**Temperature Detection (Mini-PIR-LT-ZW model only)**_

* PIR with built-in temperature sensor will transmit temperature signals regularly according to setting. The factory default interval is 30 minutes.
* When the temperature changes by +/- 2°C, the PIR will also transmit a signal.
* You can also press the Function Button once to transmit a temperature signal manually.
* The temperature detection range is about -10°C \~ 50°C ( 14°F \~ 122°F).

### _**Light Monitoring (Mini-PIR-LT-ZW model only)**_

* The PIR with built-in ambient light sensor measures illuminance and transmits measured data to Z-Wave network coordinator regularly. The factory default interval is 30 minutes.
* When the current illuminance changes by +/- 10%, the PIR will also transmit a signal.
* You can also press the Function Button once to transmit current lux reading manually.

## _**Adding Device (Inclusion)**_

This product can be included and operated in any Z-Wave network with other Z-Wave certified devices from other manufactures and/or other applications. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase reliability of the network.

* Put the Z-Wave gateway or control panel into **Inclusion mode** (please refer to the Z-Wave gateway or control panel manual).
* Within 1.5 seconds, press the Function Button 3 times.
* Refer to the operation manual of the Z-Wave gateway or control panel to complete the adding process.
* If PIR has already been added (included) into another Z-Wave Gateway/Control Panel, or if the device is unable to be added into the current Z-Wave Gateway/Control Panel, try removing it first (see _**Removing Device**_).

## _**Removing Device (Exclusion)**_

The PIR must be removed from existing Z-Wave network before being added into another.

**Exclusion Mode**

* Put the Z-Wave gateway or control panel into **Exclusion mode** (please refer to the Z-Wave gateway or control panel manual).
* Within 1.5 seconds, press the Function Button 3 times and the PIR will be removed from the Z-Wave network.

**Factory Reset**

_(Only use factory reset when network Control Panel/Gateway is missing or inoperable)._

* Remove the battery of the PIR first.
* Press and hold the Function Button. While holding the Function Button, power on the PIR by re-inserting the battery, wait for 10 seconds to factory reset.

{% hint style="warning" %}
Note:

Factory resetting the PIR will restore it to factory default settings (excluded from the Z-Wave network). The Z-Wave gateway or control panel will still keep its Z-Wave settings. Please refer to the gateway or control panel manual on how to remove the PIR Z-Wave settings.
{% endhint %}

## _**Range Test**_

To test whether the PIR is able to communicate with the Z-Wave gateway or control panel:

* Put the gateway / panel into range test mode (Walk Test).
* Press the Function Button on the PIR.
* The gateway / panel should display if the device is within the operation range (please refer to the operation manual of the gateway / panel).

## _**Z-Wave Sleep Mode**_

* The PIR will enter Z-Wave Sleep mode (to conserve power) after waking up for a short period of time (\~10 seconds). While in Z-Wave sleep mode, Z-Wave gateways or control panels are unable to send commands to the PIR.
* To program the PIR using the Z-Wave Gateway/Control Panel, please send command(s) to the PIR within the wake-up period.

## **Installation**

### _**Mounting Height and PIR Detection Coverage**_

* There are two ways to deploy the Mini-PIR: Wall Mounting and Surface Deployment.
* The PIR has detection coverage of a 120∘cone to the front. When deployed on a flat surface about 1.2 meters above ground, or mounted on the wall around 2 meters high, the PIR has maximum range of 10 meters.
* The PIR direction can be changed by loosening the angle adjustment screw on the base to tilt the PIR up and down.

![](<.gitbook/assets/1 (97).jpeg>)

## _**Assembly**_

* The PIR is composed of the main body and the base. See instruction below to fix the main body onto base or detach the main body after installation.
  1. Connect the main body to the base. (Figure 1)
  2. Tilt the PIR backward until its back touches the base. (Figure 2)

![Figure 1                                                                                                                      Figure 2](<.gitbook/assets/2 (92).png>)

3. Hold the PIR main body with your left hand and the base with your right hand. Do NOT touch the IR lens or the lens may be damaged during the process. (Figure 3, 4)
4. To **lock** the main body on to the base, turn the main body with your left hand away from yourself and turn the base with your right hand toward yourself at the same time in opposite direction until you hear a click. (Figure 3)
5. To **release** the main body from the base, turn the main body with your left hand toward yourself and press downward with your right hand thumb away from yourself at the same time in opposite direction until you hear a click. (Figure 4)



![Figure 3                                                                                                                     Figure 4](<.gitbook/assets/3 (89).png>)

## _**Installation**_

1. Use the 2 mounting holes on PIR base as template, drill holes in the surface.
2. Insert the wall plugs if fixing it into plaster or brick.
3. Screw the base into the wall plugs. (Figure 5)
4. Hook the PIR main body onto the base and turn to lock. (Figure 6, 7)
5. Loosen the angle adjustment screws then tilt the PIR until you are satisfied with the detection angle. Tighten the screws to fix the PIR at set angle. (Figure 8)



![Figure 5                                    Figure 6                                                           Figure 7                                               Figure 8](<.gitbook/assets/4 (62).jpeg>)

### _**Installation Guideline**_

* **It is recommended to install the PIR in the following locations.**
  * In a position such that an intruder would normally move across the PIR’s field of view from side to side.
  * Where its field of view will not be obstructed e.g. by curtains, ornaments etc.

### **Limitations**

* Do not install the PIR at location exposed direct sunlight, or close to heating/cooling appliance and vent
* Do not point the PIR at heat source such as heater, radiator and window.
* Do not point the PIR at window.
* Avoid large obstacles in the detection area, and avoid moving objects such as curtain.

## _**Z-Wave Information**_

**Device Type:** Sensor Notification Smoke Alarm

**Role Type:** Reporting Sleeping Slave (RSS)

**Max Association Group:** 6

**Command Class Support/Control**

**Mandatory CC Support:**

Z-Wave Plus Info CC

Version CC, v2 or newer

Manufacturer Specific CC

Device Reset Locally CC

Power Level CC

Battery CC

SensorMultilevel CC, V5

Notification V4 CC

Association CC, v2 or newer

Association Group Information CC

Configuration CC

Firmware Update Md CC

### _**Z-Wave’s Groups (Association Command Class Version 2)**_

Group 1 for “LifeLine”:

Sensor Multilevel CC,V5

Notification CC,V4 (COMMAND\_CLASS\_Notification)

Battery CC (COMMAND\_CLASS\_BASIC)

Device Reset Locally CC

Group 2 for “PIR Basic set”:

Basic CC (COMMAND\_CLASS\_BASIC)

When PIR Active, Group 2 will send Basic Set (0xFF), Restore will send (0x00)

Group 3 for “PIR notification rep”:

Notification CC, V4 (COMMAND\_CLASS\_NOTIFICATION)

Only send PIR Active (07,08) and Restore (07,00,01,08)

Group 4 for “Temp/Light Report”(Mini-PIR-LT-ZW model only):

Sensor Multilevel CC, V5 (COMMAND\_CLASS\_SENSOR\_MULTILEVEL)

Only send temperature/light

Group 5 for “HD notification rep”:

Notification CC,V4 (COMMAND\_CLASS\_NOTIFICATION)

When HD Active, Group 5 will send (04,02), Restore will send (04,06)

Group 6 for “Tamper rep”:

Notification CC,V4 (COMMAND\_CLASS\_NOTIFICATION)

When Tamper Open, Group 6 will send (07,03), Restore will send (07,00,01,03)
