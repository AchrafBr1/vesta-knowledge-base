# VESTA-043

* WSS-4E-ZW Smart Scenario Switch
* **Introduction**

WSS-4E-ZW is a Z-Wave Four-Button Scenario Switch designed to control a group of pre-programmed home automation devices by simply pressing the scenario buttons under the same Z-Wave network.

The Scenario Switch is a Z-Wave enabled device and is fully compatible with any Z-Wave enabled network.

Z-Wave is a wireless communication protocol that uses a low-power RF radio. By taking advantage of the Z-Wave mesh network, commands can be routed to their destination via intermediary “listening” Z-Wave products.

![](<.gitbook/assets/0 (26).png>)

## Parts Identification

**1. Scenario LED**

There are four Scenario LED, the LED will light up according to the correspondent Scenario button pressed.

**2. Scenario Button**

The Scenario Switch has 4 scenario buttons:

<div align="left">

<figure><img src=".gitbook/assets/1 (18).jpeg" alt=""><figcaption></figcaption></figure>

</div>

Button 1

Button 2

Button 3

Button 4

**3. Battery Compartment**

**4. Function Button**

* Press the button 3 times within 1.5 seconds to transmit a learn code.
* Press and hold the button for 10 seconds to factory reset.

**5. LED (Red)**

Red LED lights up in the following situations:

* Flashes once:

When the Scenario Switch is transmitting a signal.

* Flashes twice:

The Scenario Switch has successfully added into a Z-Wave network.

**6. Function Button Hole**

* Features
* _Battery and Low Battery Detection_

The Scenario Switch uses two 1.5V AA Alkaline batteries as its power source.

The Switch will report its battery percentage to the Control Panel respectively at 100%, 75%, 50%, 25%. If the battery voltage is low (25%), a Low Battery signal will be sent to the Control Panel to notify the user.

The Scenario Switch features Low Battery Detection function. When the battery voltage is low, the Scenario Switch will transmit Low Battery signal to the Z-Wave coordinator.

## _**Supervision**_

This function uses the Z-Wave Wake Up Command Class. The Wake Up Command Class allows the battery-powered Light Switch to notify the Control Panel/Gateway that it is awake and ready to receive any queued commands. The wake up interval time period is programmed automatically according to Control Panel’s setting when The Light Switch is included. The recommended setting of the interval time is between 30 to 60 minutes.

## _**Scenario**_

When a Scenario Button is pressed, the Scenario Switch will send a signal to the Control Panel to activate the correspondent scenario (see Control Panel for details). The switch will also emit a beep as indication.

## _**Adding Device (Inclusion)**_

This product can be included and operated in any Z-Wave network with other Z-Wave certified devices from other manufactures and/or other applications. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase reliability of the network.

* Remove the cover by using a screwdriver.
* Insert the battery then replace the cover.
* Put the Z-Wave control panel into **Inclusion mode** (please refer to the Z-Wave control panel manual).
* Within 1.5 seconds, press the Function Button 3 times.
* Refer to the operation manual of the Z-Wave gateway or control panel to complete the adding process.
* If the device has already been added (included) into another Z-Wave Gateway/Control Panel, or if the device is unable to be added into the current Z-Wave Gateway/Control Panel, try removing it first (see _**Removing Device**_).

## _**Removing Device (Exclusion)**_

The device must be removed from existing Z-Wave network before being added into another.

### **Exclusion Mode**

* Put the Z-Wave gateway or control panel into **Exclusion mode** (please refer to the Z-Wave or control panel manual).
* Within 1.5 seconds, press the Function Button 3 times and the device will be removed from the Z-Wave network.

## **Factory Reset**

Factory resetting the device will restore it to factory default settings (i.e. not included into any Z-Wave network). Please only use this procedure if the Z-Wave gateway or control panel is lost or otherwise inoperable.

* Press and hold the Function Button of the device for 10 seconds to factory reset.

## _**Range Test**_

To test whether the device is able to communicate with the Z-Wave gateway or control panel:

* Put the gateway / panel into range test mode (Walk Test).
* Press the Function Button on the device.
* The gateway / panel should display if the device is within the operation range (please refer to the operation manual of the gateway / panel).

## _**Z-Wave Sleep Mode**_

* The Scenario Switch will enter Z-Wave Sleep mode (to conserve power) after waking up for a short period of time (\~10 seconds). While in Z-Wave sleep mode, Z-Wave gateways or control panels are unable to send commands to the Scenario Switch.
* To program the Scenario Switch using the Z-Wave Gateway/Control Panel, please send command(s) to the Scenario Switch within the wake-up period.
* Installation
* The Scenario Switch is designed to be mounted on a flat surface with fixing screws.
* The base has 3 knockouts, where the plastic is thinner, for mounting purpose.

1. Remove the cover by using a screwdriver.
2. Break through the appropriate knockouts on the base.
3. Using the holes as a template, drill holes in the surface.
4. Screw the base into the surface.
5. Replace the cover back onto the base and secure it by tightening the fixing screw.

![未命名-2](<.gitbook/assets/2 (13).jpeg>)

## **Z-Wave Information**

**Device Type:** Sensor - Notification

**Role Type:** Reporting Sleeping Slave (RSS)

**Command Class Support/Control**

**Mandatory CC Support:**&#x20;

Association CC, v2

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

### _**Z-Wave’s Groups (Association Command Class Version 2)**_

Group 1 for “LifeLine”:

Scene Activation CC

(COMMAND\_CLASS\_SCENE\_ACTIVATION)

Battery CC (COMMAND\_CLASS\_BASIC)

Device Reset Locally CC
