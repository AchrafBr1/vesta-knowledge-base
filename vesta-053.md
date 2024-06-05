# VESTA 053

**LMHT-1ZW** **Ambient Light, Humidity and Temperature Sensor**

**Introduction**

LMHT-1ZW is a Z-Wave Ambient Light, Humidity and Temperature Sensor. It monitors your home environment and transmits measured Illuminance (lux), humidity and temperature to the coordinator in the Z-Wave network.

The Sensor is a Z-Wave enabled device and is fully compatible with any Z-Wave enabled network.

Z-Wave is a wireless communication protocol that uses a low-power RF radio. By taking advantage of the Z-Wave mesh network, commands can be transmitted to their destination via intermediary “listening” Z-Wave products.

The LMHT-1ZW series includes the following models.

LMHT-1ZW

LMHT-1ZW-OTA

**Parts Identification**

1. **Light Sensor / LED Indicator**
   * **Flashes once:** Transmitting Learning Code/Factory Reset
   * **Flashes twice:** After the sensor has successfully added into Z-Wave Gateway/Control Panel.
2. **Temperature Sensor**
3. **Battery Compartment**
4. **Function Button**
   * Press once to send a signal to the coordinator.
   * Press and hold for 10 seconds to factory reset.
   * Press for 3 times within 1.5 seconds to transmit learning code.

![](<.gitbook/assets/0 (50).jpeg>)

**Features**

* _**Lighting, Humidity and Temperature Monitoring**_
  * The sensor measures illuminance, humidity and temperature to transmit measured data to Z-Wave Control Panel/Gateway regularly.

The illuminance/Humidity and temperature reading signal is transmitted every 1 minute. The sensor will also transmit the signal automatically when:

*
  *
    * The temperature changes by +/- 2°C
    * The humidity changes by +/- 10%
    * The illuminance changes by 1500 lux compared to the previous illuminance
    * The current illuminance is greater than or equal to 300 lux and changes by 45% compared to the previous illuminance
    * The current illuminance is less than 300 lux and changes by more than 60 lux compared to the previous illuminance
    * Power on the Sensor by inserting the battery.
  * You can also press the Function Button once to transmit current reading signal manually.
* _**Battery and Low Battery Detection**_
  * The sensor uses one CR123A 3V Lithium battery as its power source.
  * The sensor features Low Battery Detection function. When the battery voltage is low, the sensor will transmit a low-battery signal to the Gateway/Control Panel.

1

*
  * The Sensor will report its battery percentage to the Gateway/Control Panel respectively at 100%, 75%, 50% and 25%. If the battery voltage is low (25%), the low-battery signal will be sent to the Control Panel to notify the user.
  * When changing the battery, after removing the old battery, press the Function Button twice to fully discharge before inserting a new battery.
* _**Supervision**_

This function uses the Z-Wave Wake Up Command Class. The Wake Up Command Class allows the battery-powered Sensor to notify the Control Panel/Gateway that it is awake and ready to receive any queued commands. The wake up time period is programmed automatically according to Control Panel’s setting when The Sensor is included. The recommended setting of the wake up time is 60 minutes above.

* _**Adding Device (Inclusion)**_

This product can be included and operated in any Z-Wave network with other Z-Wave certified devices from other manufactures and/or other applications. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase reliability of the network.

*
  * Put the Z-Wave gateway or control panel into **Inclusion mode** (please refer to the Z-Wave gateway or control panel manual).
  * Within 1.5 seconds, press the Function Button 3 times.
  * Refer to the operation manual of the Z-Wave gateway or control panel to complete the adding process.
  * If the Sensor has already been added (included) into another Z-Wave Gateway/Control Panel, or if the device is unable to be added into the current Z-Wave Gateway/Control Panel, try removing it first (see _**Removing Device**_).
* _**Removing Device (Exclusion)**_

The Sensor must be removed from the existing Z-Wave network before being added into another.

**Exclusion Mode**

* Put the Z-Wave gateway or control panel into **Exclusion mode** (please refer to the Z-Wave gateway or control panel manual).
* Within 1.5 seconds, press the Function Button 3 times and the Sensor will be removed from the Z-Wave network.

**Factory Reset**

_(Only use factory reset when network Control Panel/Gateway is missing or inoperable)._

* Remove the battery of the Sensor first.
* Press and hold the Function Button. While holding the Function Button, power on the Sensor by re-inserting the battery, wait for 10 seconds to factory reset.

_\<NOTE>_

*
  * Factory resetting the Sensor will restore it to factory default settings (excluded from the Z-Wave network). The Z-Wave gateway or control panel will still keep its Z-Wave settings. Please refer to the gateway or control panel manual on how to remove the Sensor Z-Wave settings.
* _**Range Test**_

To test whether the Sensor is able to communicate with the Z-Wave gateway or control panel:

*
  * Put the gateway / panel into range test mode (Walk Test).
  * Press the Function Button on the Sensor.
  * The gateway / panel should display if the device is within the operation range (please refer to the operation manual of the gateway / panel).
* _**Z-Wave Sleep Mode**_
  * The Sensor will enter Z-Wave Sleep mode (to conserve power) after waking up for a short period of time (\~10 seconds). While in Z-Wave sleep mode, Z-Wave gateways or control panels are unable to send commands to the Sensor.
  * To program the Sensor using the Z-Wave Gateway/Control Panel, please send command(s) to the Sensor within the wake-up period.

2

**Installation**

* _**Mounting the Sensor**_

The sensor can be mounted using two methods: Self-adhesive or Screw mounting.

**Self adhesive mounting**

1. Clean the surface with a suitable degreaser.
2. Remove the liner from one side of double-sided adhesive pad and firmly apply the adhesive pad to the back of the device.
3. Remove the other liner and firmly place/press the device at the desired location.

![](<.gitbook/assets/1 (46).jpeg>)

Do not use the self-adhesive mounting method on poorly painted and/or rough surfaces.

**Screw Mounting**

The base of the sensor has two screw knockouts, where the plastic is thinner for mounting purposes. To mount the sensor:

*
  1. Detach the Top Cover and Base assembly by loosening the Cover-Fixing Screw using a Phillips screwdriver.
  2. Break through the knockouts on the base.
  3. Use the holes as a template and drill two holes and insert the wall plugs.
  4. Screw the base onto the wall plugs.
  5. Re-place the top cover over the base by hooking the base onto the fixing hook and pushing the cover towards the base.
  6. Secure and screw the top cover back on to its base using a Phillips screwdriver.
* _**Z-Wave Information**_

**Device Type:** Sensor - Notification

**Role Type:** Reporting Sleeping Slave (RSS)

**Command Class Support/Control**

**Mandatory CC Support:**

Association CC, v2

Association Group Information CC

Battery CC

Device Reset Locally CC

Manufacturer Specific CC, v2

Sensor Multilevel CC, V5

Version CC, v2

Wake UP CC, v2

Z-Wave Plus Info CC, v2

Power Level CC

Notification CC, v4

Firmware Update CC,v2

* _**Z-Wave’s Groups (Association Command Class Version 2)**_

Group 1 for “LifeLine”:

Sensor Multilevel CC,V5 (COMMAND\_CLASS\_SENSOR\_MULTILEVEL)

Battery CC (COMMAND\_CLASS\_BASIC)

Device Reset Locally CC

Group 2 for “Temperature Report”:

Sensor Multilevel CC,V5 (COMMAND\_CLASS\_SENSOR\_MULTILEVEL)

Group 3 for “Humidity Report”:

Sensor Multilevel CC, V5 (COMMAND\_CLASS\_SENSOR\_MULTILEVEL)

Group 4 for “Luminance Report”:

Sensor Multilevel CC, V5 (COMMAND\_CLASS\_SENSOR\_MULTILEVEL)

3
