# VESTA 172

**Air Quality Sensor (AQS-2-ZW)**

The Air Quality Sensor AQS-2 is a Z-Wave™ indoor air quality sensor that aims to detect and monitor CO2 concentration. The Air Quality Sensor is compatible only with Z-Wave Gateway/Control Panel. Z-Wave is a wireless communication protocol that uses a low-power RF radio. By taking advantage of the Z-Wave mesh network, commands can be routed to their destination via intermediary “listening” Z-Wave products.

**Parts Identification**

![](<.gitbook/assets/0 (72).jpeg>)

**1. Function Button**

\-Press the button once to send CO2 concentration level signals.

\-Press the button 3 times within 1 second to transmit a learn code.

\-Press and hold the button for 10 seconds to perform factory reset.

**2.** **DC Jack**

Connects to a 12V 1A DC Adapter

**Features**

![](<.gitbook/assets/1 (65).png>)

* _**Power Supply**_

The Air Quality Sensor is powered by connecting with a DC 12V output and 1A adaptor. Be sure to only use an adapter with the appropriate AC voltage rating to prevent component damage, or only use the AC power adapter included with the Air Quality Sensor.

If an AC power failure is detected, the Air Quality Sensor will send an AC failure report to the Control Panel.

![](<.gitbook/assets/2 (70).png>)

* _**Carbon Dioxide Detection**_
  * The Air Quality Sensor measures CO2 concentration every 5 seconds, and reports data to the Control Panel every 30 minutes. If the CO2 concentration changes by +/- 100ppm for two consecutive times, the Air Quality sensor will report to the Control Panel.
  * If the detected CO2 concentration is above 1000ppm, the AQS-2 will send a CO2 alarm signal to the Control Panel. If the CO2 concentration drops below 1000ppm, the AQS-2 will send a CO2 restore signal to the Control Panel.
* _**Adding Device (Inclusion)**_

![](<.gitbook/assets/3 (70).png>)

This product can be included and operated in any Z-Wave network with other Z-Wave certified devices from other manufactures and/or other applications. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase reliability of the network.

*
  * Plug in the AC Power adapter; connect to the DC Jack on the Air Quality Sensor to power up.
  * Put the Z-Wave Gateway or Control Panel into **Inclusion** mode (please refer to the Z-Wave Gateway or Control Panel manual).
  * Within 1 second, press the Function Button 3 times.
  * Refer to the operation manual of the Z-Wave Gateway or Control Panel to complete the inclusion process.
  * If the sensor has already been **added** (included) into another Z-Wave Gateway/Control Panel, or if the sensor is unable to be added into the current Z-Wave Gateway/Control Panel, please exclude it first (see _**Removing Device**_) before attempting to **include** it into the current Z-Wave Gateway/Control Panel.
* _**Removing Device (Exclusion)**_

![](<.gitbook/assets/4 (70).png>)

The Air Quality Sensor must be removed from existing Z-Wave network before being included into another. There are two methods available to exclude a device.

**Exclusion Mode**

* Put the Z-Wave Gateway or Control Panel into **Exclusion mode** (please refer to the Z-Wave Gateway or Control Panel manual).
* Within 1 second, press the Function Button 3 times and the device will be removed from the Z-Wave network.

1

**Factory Reset**

_(Only use factory reset when network Control Panel/Gateway is missing or inoperable)._

* Press and hold the Function Button for 10 seconds to perform factory reset.

_\<NOTE>_

*
  * Factory resetting the device will restore it to factory default settings (excluded from the Z-Wave network). The Z-Wave Gateway or Control Panel will still keep its Z-Wave settings. Please refer to the Gateway or Control Panel manual on how to remove the device’s Z-Wave settings.

![](<.gitbook/assets/5 (72).png>)

**Installation**

![](<.gitbook/assets/6 (51).png>)

* _**Placing the Air Quality Sensor**_

The Air Quality Sensor should be placed on a flat surface with open area around it in the room you want to monitor.

The more open the location of placement is, the more accurate the air quality measurements will be.

**Z-Wave Information**

**Generic Type:** Switch Multilevel

**Specific Type:** Color Tunable Multilevel

**Product Type ID:** 0x0004

**Product ID:** 0x0020

**Role Type:** Always On Slave (AOS)

**Security:** S2 Unauthenticated

**Command Class Support/Control**

**Mandatory CC Support:** Z-Wave Plus Info CC, V2

Sensor Multilevel CC, V11 (security 2)

Association CC, V2 (security 2)

Multi Channel Association CC, V3 (security 2)

Association Group Information CC (security 2)

Manufacturer Specific CC, V2 (security 2)

Transport Service CC, V2

.Version CC, V3 (security 2)

.Device Reset Locally CC (security 2)

.Power level CC (security 2)

.Security CC

Security 2 CC

.Supervision CC

.Firmware Update MD CC, V4 (security 2)

![](<.gitbook/assets/7 (45).png>)

* _**Z-Wave’s Groups (Association Command Class Version 2)**_

The AQS can be set to send reports to associated Z-Wave devices. It supports 1 association group. Group 1 for “LifeLine”: (maximum node: 5)

Sensor Multilevel (COMMAND\_SWITCH\_MULTILEVEL, SWITCH\_MULTILEVEL\_REPORT)

Device Reset Locally

(COMMAND\_CLASS\_DEVICE\_RESET\_LOCALLY, DEVICE\_RESET\_LOCALLY\_NOTIFICATION)

**Sensor Multilevel:** As the CO2 levels detected changes; the AQS will transmit sensor multilevel command.

**Factory Reset:** When the AQS has been reset to factory default state, it will send Device Reset Locally to all nodes in Group 1.

![](<.gitbook/assets/8 (48).png>)

* _**Command Class Data Format**_
  * CO2 Report: \[COMMAND\_CLASS\_SENSOR\_MULTILEVEL] \[SENSOR\_MULTILEVEL\_REPORT]
    * If CO2 signal 11 02 06 99 is transmitted, 0699 can be viewed as 0x0699 in Hexadecimal number. You can convert hexadecimal to decimal to check the CO2 value.

0699=0x0699=1689ppm

2
