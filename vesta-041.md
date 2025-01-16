# VESTA-041

**RS-23-ZW Room Sensor** V:R3

**Introduction**

RS-23-ZW is a Z-Wave Room Sensor. It features both temperature and humidity detection function to monitor your home environments. The temperature and humidity information will be transmitted to the Z-Wave network and displayed on the Room Sensor’s LCD screen.

The Room Sensor is a Z-Wave enabled device and is fully compatible with any Z-Wave enabled network.

Z-Wave is a wireless communication protocol that uses a low-power RF radio. By taking advantage of the Z-Wave mesh network, commands can be transmitted to their destination via intermediary “listening” Z-Wave products.

The Z-Wave Room Sensor series includes the following models:

RS-23-ZW, RS-23-ZW-OTA

![](<.gitbook/assets/0 (46).png>)

## **Parts Identification**

**1. LCD Display**

The LCD displays the following information:

* Temperature in Farenheit / Celcius setting
* Humidity RH%.
* Z-Wave network connectivity (![](<.gitbook/assets/1 (41).jpeg>) icon).
* Low Battery status ( ![](<.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png>)icon).
* LCD Backlight on: when function button is pressed.

2. **Function Button**

* Press the button once to:

Send a supervision signal with temperature/humidity info Light up the LCD backlight for 10 seconds.

* Press the button 3 times within 1.5 seconds to transmit learning code.
* Press and hold the button for 10 seconds to factory reset. Refer to **Removing Device (Exclusion)** for details.

3. **Base Screw (Open/Close Cover)**

When the front cover is installed on the back cover, open the cover by loosen the base screw and close it likewise.

4. **Fahrenheit / Celcius Setting Jumper (JP1)**

* ![](<.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png>) If the jumper link is inserted between the top 2 pins, the LCD will display the temperature in Celsius. (**Factory Default**)
* ![](<.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png>) If the jumper link is inserted between the bottom 2 pins, the LCD will display the temperature in Fahrenheit.

5. **Battery Compartment**

The Room Sensor is powered by two AA 1.5 V Alkaline batteries

6. **Back Cover**
7. **Wall Mounting Knockouts**

## **Features**

### _**Temperature and Humidity Detection**_

* The Room Sensor will transmit temperature and humidity signals regularly according to setting. The factory default interval is 10 minutes.
* When the temperature changes by +/- 2°C, or humidity changes +/- 10%,the Room Sensor will also transmit a signal.
* You can also press the Function Button once to transmit a temperature and humidity signal manually.
* The temperature detection range is about -10°C \~ 50°C.( 14°F \~ 122°F)
* The humidity detection range is about 10% \~ 90% RH

## _**Battery and Low Battery Detection**_

* The Room Sensor uses two 1.5 V Alkaline batteries as its power source. The batteries are included in the package.
* The Room Sensor will report its battery percentage to the Z-Wave Control Panel respectively at 100%, 75%, 50%, 25%, 0%. If the battery voltage is low (25%), a Low Battery signal will be sent to the Z-Wave Control Panel to notify the user.
* The Room Sensor feature Low Battery Detection function. When the battery voltage is low, the Room Sensor will transmit Low Battery signal to notify the user and display low battery icon on LCD.
* When changing batteries, after removing the old batteries, press the Function Button twice to fully discharge before inserting new batteries.

## _**Supervision**_

* This function uses the Z-Wave Wake Up Command Class. The Wake Up Command Class allows the battery-powered Room Sensor to notify the Z-Wave Control Panel/Gateway that it is awake and ready to receive any queued commands. The wake up time is programmed automatically according to Z-Wave Control Panel’s setting when The Room Sensor is included. The recommended setting of the wake up time is 60 minutes above.

## _**Adding Device (Inclusion)**_

This product can be included and operated in any Z-Wave network with other Z-Wave certified devices from other manufactures and/or other applications. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase reliability of the network.

* Remove the cover by loosening the fixing screw.
* Insert the 2 alkaline batteries into the battery compartment connecting the correct polarity as shown on the battery compartment lid to power on the Room Sensor.
* Put the Z-Wave gateway or Z-Wave Control Panel into **Inclusion** or **Learning** mode (please refer to the Z-wave gateway or Z-Wave Control Panel manual).
* Within 1.5 seconds, press the Function Button 3 times.
* Refer to the operation manual of the Z-Wave gateway or Z-Wave Control Panel to complete the learn-in process.
* If the sensor has already been **included** (learnt) into another Z-Wave Gateway/Z-Wave Control Panel, or if the sensor is unable to be learnt into the current Z-Wave Gateway/Z-Wave Control Panel, please exclude it first (see _**Exclusion**_) before attempting to **include** it into the current Z-Wave Gateway/Z-Wave Control Panel.
* _**Removing Device (Exclusion)**_

The Room Sensor must be removed from existing Z-Wave network before being included into another. There are two methods available to exclude a device.

## **Exclusion Mode**

* Put the Z-Wave gateway or Z-Wave Control Panel into **Exclusion mode** (please refer to the Z-Wave gateway or Z-Wave Control Panel manual).
* Within 1.5 seconds, press the Function Button 3 times and the Room Sensor will be removed from the Z-Wave network.

## **Factory Reset**

_(Only use factory reset when network Z-Wave Control Panel/Gateway is missing or inoperable)._

* Remove the batteries of the Room Sensor first.
* Press and hold the Function Button. While holding the Function Button, power on the Room Sensor by re-inserting the batteries, wait for 10 seconds to factory reset.

_\<NOTE>_

* Factory resetting the Room Sensor will restore it to factory default settings (excluded from the Z-wave network). The Z-Wave gateway or Z-Wave Control Panel will still keep its Z-Wave settings. Please refer to the gateway or Z-Wave Control Panel manual on how to remove the Room Sensor’s Z-Wave settings.

## _**Range Test**_

To test whether the device is able to communicate with the Z-Wave gateway or Z-Wave Control Panel:

* Put the gateway / panel into range test mode (Walk Test).
* Press the Function Button on the device.
* The gateway / panel Control Panel should display if the device is within the operation range (please refer to the operation manual of the gateway / panel Control Panel).

## _**Z-Wave Sleep Mode**_

* The Room Sensor will enter Z-Wave Sleep mode (to conserve power) after waking up for a short period of time (\~10 seconds). While in Z-Wave sleep mode, Z-Wave gateways or Z-Wave Control Panels are unable to send commands to the Room Sensor.
* To program the Room Sensor, please send command(s) to the Room Sensor within the wake-up period.

## **Installation**

### _**Mounting the Room Sensor**_

For best LCD display quality, the Room Sensor should be mounted at location about 5∘above eye level height.

### Screw mounting

When mounting with screw, make sure to only use screws provided in the package by original manufacturer, as inappropriate screws may damage interior of the device.

1. Remove the front cover by using a screwdriver.
2. Break through the knockouts on the back cover.
3. Using the holes as a template, drill holes in the surface
4. Insert the wall plugs if fixing into plaster or brick
5. Screw the back cover into the wall plugs
6. Screw the front cover back on to the back cover

## _**Z-Wave Information**_

**Device Type:** Sensor - Notification

**Role Type:** Reporting Sleeping Slave (RSS)

**Command Class Support/Control**

**Mandatory CC Support:**&#x20;

Association CC, v2 or newer

Association Group Information CC

Battery CC

Device Reset Locally CC

Manufacturer Specific CC

Sensor Multilevel CC

Version CC, v2 or newer

Wake UP CC

Z-Wave Plus Info CC

Firmware Update CC, v2 (OTA version only)

### _**Z-Wave’s Groups (Association Command Class Version 2)**_

The Room Sensor can be set to send reports to associated Z-Wave devices. It supports 3 association groups.

Group 1 for “LifeLine”:

Sensor Multilevel CC,V5 (COMMAND\_CLASS\_SENSOR\_MULTILEVEL)

Battery CC (COMMAND\_CLASS\_USER\_BASIC)

Device Reset Locally CC

_(It supports 1 node)_

Group 2 for “Temperature Report”:

Sensor Multilevel CC, v5 (COMMAND\_CLASS\_SENSOR\_MULTILEVEL)

_(it supports 5 nodes)_

Group 3 for “Humidity Report”:

Sensor Multilevel CC,V5 (COMMAND\_CLASS\_SENSOR\_MULTILEVEL)

_(it supports 5 nodes)_

