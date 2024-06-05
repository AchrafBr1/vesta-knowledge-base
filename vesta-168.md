# VESTA 168

**SCS-1-ZW Shutter Control Switch**

**Introduction**

SCS-1-ZW is a Z-Wave Three-Button Shutter Control Switch designed to control a group of pre-programmed home automation devices by simply pressing the scenario buttons under the same Z-Wave network.

The Shutter Control Switch is a Z-Wave enabled device and is fully compatible with any Z-Wave enabled network.

Z-Wave is a wireless communication protocol that uses a low-power RF radio. By taking advantage of the Z-Wave mesh network, commands can be routed to their destination via intermediary “listening” Z-Wave products.

![](<.gitbook/assets/0 (70).jpeg>)

**Device Introduction**

**1. Scenario LED**

When any of the 3 scenario buttons are pressed, the LED will light up briefly

**2. Scenario Buttons**

The Shutter Control Switch has 3 scenario buttons

1. **Battery Compartment**
2. **Function Button**
   * Press the button 3 times within 1.5 seconds to transmit a learn code.
   * Press and hold for 10 seconds to reset.
3. **LED (Red)**

Red LED lights up in the following situations:

*
  * Flashes once:

When the Sutter Control Switch is transmitting a signal.

*
  * Flashes twice:

The Shutter Control Switch has successfully added into a Z-Wave network.

1. **Function Button Hole**

**Features**

![](<.gitbook/assets/1 (65).jpeg>)

* _**Battery and Low Battery Detection**_

The Shutter Control Switch uses two 1.5V AA Alkaline batteries as its power source.

The Switch will report its battery percentage to the Control Panel respectively at 100%, 75%, 50%, 25%. If the battery voltage is low (25%), a Low Battery signal will be sent to the Control Panel to notify the user. The Shutter Control Switch features Low Battery Detection function. When the battery voltage is low, the Scenario Switch will transmit Low Battery signal to the Z-Wave coordinator.

![](<.gitbook/assets/2 (69).png>)

* _**Supervision**_

This function uses the Z-Wave Wake Up Command Class. The Wake Up Command Class allows the battery-powered Switch to notify the Control Panel/Gateway that it is awake and ready to receive any queued commands. The wake up interval time period is programmed automatically according to Control Panel’s setting when the Switch is included. The recommended setting of the interval time is between 30 to 60 minutes.

![](<.gitbook/assets/3 (68).png>)

* _**Scenario and Shutter Control**_

When a Scenario Button is pressed, the Shutter Control Switch will send a signal to the Control Panel to activate the correspondent scenario (see Control Panel for details). Set the scenario in the Control Panel to

1

control the open/close/stop function of the shutter to operate the shutter through the Scenario Control Switch.

The switch will emit a beep as indication when the button is pressed.

![](<.gitbook/assets/4 (68).png>)

* _**Adding Device (Inclusion)**_

This product can be included and operated in any Z-Wave network with other Z-Wave certified devices from other manufactures and/or other applications. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase reliability of the network.

*
  * Remove the cover by using a screwdriver.
  * Insert the battery then replace the cover.
  * Put the Z-Wave control panel into **Inclusion mode** (please refer to the Z-Wave control panel manual).
  * Within 1.5 seconds, press the Function Button 3 times.
  * Refer to the operation manual of the Z-Wave gateway or control panel to complete the adding process.
  * If the device has already been added (included) into another Z-Wave Gateway/Control Panel, or if the device is unable to be added into the current Z-Wave Gateway/Control Panel, try removing it first (see _**Removing Device**_).
* _**Removing Device (Exclusion)**_

![](<.gitbook/assets/5 (69).png>)

The device must be removed from existing Z-Wave network before being added into another. **Exclusion Mode**

* Put the Z-Wave gateway or control panel into **Exclusion mode** (please refer to the Z-Wave or control panel manual).
* Within 1.5 seconds, press the Function Button 3 times and the device will be removed from the Z-Wave network.

**Factory Reset**

Factory resetting the device will restore it to factory default settings (i.e. not included into any Z-Wave network). Please only use this procedure if the Z-Wave gateway or control panel is lost or otherwise inoperable.

*
  * Press and hold the Function Button of the device for 10 seconds to factory reset.
* _**Range Test**_

![](<.gitbook/assets/6 (49).png>)

To test whether the device is able to communicate with the Z-Wave gateway or control panel:

*
  * Put the gateway / panel into range test mode (Walk Test).
  * Press the Function Button on the device.
  * The gateway / panel should display if the device is within the operation range (please refer to the operation manual of the gateway / panel).
* _**Z-Wave Sleep Mode**_
  * The Shutter Control Switch will enter Z-Wave Sleep mode (to conserve power) after waking up for a short period of time (\~10 seconds). While in Z-Wave sleep mode, Z-Wave gateways or control panels are unable to send commands to the Shutter Control Switch.
  * To program the Shutter Control Switch using the Z-Wave Gateway/Control Panel, please send command(s) to the Shutter Control Switch within the wake-up period.

![](<.gitbook/assets/7 (43).png>) ![](<.gitbook/assets/8 (36).jpeg>)

**Installation**

* The Shutter Control Switch is designed to be mounted on a flat surface with fixing screws.
* The base has 3 knockouts, where the plastic is thinner, for mounting purpose.
  1. Remove the cover by using a screwdriver.
  2. Break through the appropriate knockouts on the base.
  3. Using the holes as a template, drill holes in the surface.
  4. Screw the base into the surface.
  5. Replace the cover back onto the base and secure it by tightening the fixing screw.

![](<.gitbook/assets/9 (22).jpeg>)

2

**Z-Wave Information**

**Device Type:** Sensor - Notification

**Role Type:** Reporting Sleeping Slave (RSS)

**Command Class Support/Control**

**Mandatory CC Support:** Association CC, v2

Association Group Information CC

Battery CC

Device Reset Locally CC

Manufacturer Specific CC, v2

Scene Activation CC

Version CC, v2

Wake UP CC, v2

Z-Wave Plus Info CC, v2

Power Level CC

Notification CC, v4

Firmware Update CC, v2

![](<.gitbook/assets/10 (42).png>)

* _**Z-Wave’s Groups (Association Command Class Version 2)**_

Group 1 for “LifeLine”:

Scene Activation CC

(COMMAND\_CLASS\_SCENE\_ACTIVATION)

Battery CC (COMMAND\_CLASS\_BASIC)

Device Reset Locally CC

3
