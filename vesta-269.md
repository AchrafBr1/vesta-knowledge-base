# VESTA-269

**CLMT-1ZW**

## **Clamp Meter**&#x20;

CL-Meter-ZW is a Z-Wave Clamp Meter aim to monitor and report the total amount of electricity uses in your facility by connecting the clamp onto the power cable.

The Energy Meter is a Z-Wave enabled device and is fully compatible with any Z-Wave enabled network.

Z-Wave is a wireless communication protocol that uses a low-power RF radio. By taking advantage of the Z-Wave mesh network, commands can be routed to their destination via intermediary “listening” Z-Wave products.

![](<.gitbook/assets/0 (109).jpeg>)

## **Parts Identification**

**1. Red LED**

Flashes once: When Clamp Meter is transmitting a signal.

Flash Twice: The Clamp Meter has successfully joined a Z-Wave network.

2. **AC Input cable**
3. **Current Transformer Cable (CT2)**
4. **Current Transformer Cable (CT1)**
5. **Function Button**

-Press the button once to report the value of the meter to the Z-Wave network.

-Press the button 3 times within 1.5 seconds to transmit a learn code.

-Press and hold the button for 10 seconds to factory reset the Clamp Meter.

6. **Reserved**
7. **Mounting Hole**
8. **Mounting Hooks**
9. **Mounting Bracket**

## **Installation**

## _**Wiring**_

{% hint style="danger" %}
**WARNING**

Wiring of the device should only be performed by a licensed electrician. The circuit box’s main breaker should be turned off to perform installation.
{% endhint %}

The insertion hole wire specification is AWG18 or Ø 1.02 (mm²).

The Clamp specification is 60A Ø 10mm

Please make sure the main power in your facility is also off before installing. Follow the steps below:

1. Connect AC Input cable to a socket near the Electrical Box to power on the Clamp Meter.
2. Open the clamp as indicated by below picture. The clamp should be applied onto an electric cable The arrow direction on the clamp need to point at the correct direction of the electricity current flows (**KL**). If arrow is faced in reverse direction, the reading will display negative value (-) however it will not influence the readings.

![                                                                                                                                                                                             K                                          L](<.gitbook/assets/3 (84).png>)

3. Follow the schematics below as an example; clip the clamps on the electricity cables on the 2 the incoming power cable connected to the Main Circuit Breaker.

![](<.gitbook/assets/4 (90).png>)

## _**Mounting**_

The Clamp Meter has a mounting bracket for mounting purposes.

1. Use the mounting bracket as template to mark the two holes on the wall for installing screws.
2. Screw the mounting bracket onto the wall according to marked location. Install wall plugs if necessary.
3. Locate the hooks of the mounting bracket and line up the hooks with the mounting holes on the Clamp Meter. Fit the hooks into the mounting holes as picture below. Installation is now complete.

![](<.gitbook/assets/5 (92).png>)

## _**Adding Device (Inclusion)**_

This product can be included and operated in any Z-Wave network with other Z-Wave certified devices from other manufactures and/or other applications. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase reliability of the network.

* Plug in the AC Input cable into the socket to power on the Clamp Meter.
* Put the Z-Wave control panel into **Inclusion mode** (please refer to the Z-Wave control panel manual).
* Within 1.5 seconds, press the Function Button 3 times.
* Refer to the operation manual of the Z-Wave Gateway or Control Panel to complete the adding process.
* If the device has already been added (included) into another Z-Wave Gateway/Control Panel, or if the device is unable to be added into the current Z-Wave Gateway/Control Panel, try removing it first (see _**Removing Device**_).

## _**Removing Device (Exclusion)**_

The device must be removed from existing Z-Wave network before being added into another.&#x20;

### **Exclusion Mode**

* Put the Z-Wave Gateway or Control Panel into **Exclusion mode** (please refer to the Z-Wave or control panel manual).
* Within 1.5 seconds, press the Function Button 3 times and the device will be removed from the Z-Wave network.

### **Factory Reset**

Factory resetting the device will restore it to factory default settings (i.e. not included into any Z-Wave network). Please only use this procedure if the Z-Wave Gateway or Control Panel is lost or otherwise inoperable.

* Press and hold the Function Button of the device for 10 seconds to factory reset.

## _**Range Test**_

To test whether the device is able to communicate with the Z-Wave Gateway or Control Panel:

* Put the Gateway / Control Panel into range test mode (Walk Test).
* Press the Function Button on the device.
* The Gateway / Control Panel should display if the device is within the operation range (please refer to the operation manual of the Gateway / Control Panel).

## _**Energy Consumption Monitor**_

* The Clamp Meter will transmit a signal from the clamp itself with its power consumption data every 10 minutes to the Z-Wave network coordinator.
  * Reading from clamp on Current Transformer Cable CT-1 is reported to Meter Channel 1
  * Reading from clamp on Current Transformer Cable CT-2 is reported to Meter Channel 2.
* Whenever the Clamp’s energy output changes by +/- 2W, the Clamp Meter will automatically transmit a signal with power consumption data to the Z-Wave network coordinator for update.
* The Clamp Meter transmits a signal with power data to coordinator whenever accumulated power usage of the clamp increases by 0.1kW/hr.
* The Clamp has an accuracy of +/- 5%.
* To clear the clamp of its accumulated power consumption data, follow steps below:

1. Un-plug AC cable to power down Clamp Meter.
2. Press and hold the function button, while holding the button, power on the Clamp Meter by re-plug in the AC cable.
3. Release the function button when red LED starts to quickly flash.
4. Un-plug and re-plug AC cable again, clearing is complete.

## _**Maximum Operation Load**_

* 110V: 6600W and 60A
* 230V: 13800W and 60A.

## **Z-Wave Information**

**Device Type:** Whole Home Meter - Simple

**Role Type:** Always On Slave (AOS)

Command Class Support/Control

### Mandatory CC Support:&#x20;

Association CC, v2

Association Group Information CC

Device Reset Locally CC

Manufacturer Specific CC, v2

Multi Channel Association CC, V3

Multi Channel CC, V4

Meter CC, V2

CRC 16 ENCAP

Version CC, v2

Z-Wave Plus Info CC, v2

Power Level CC,

Firmware Update CC, v2

## _**Z-Wave’s Groups (Association Command Class Version 2)**_

The meter can be set to send reports to associated Z-Wave devices. It supports 3 association groups which every group has one node support. Group 1\~Group 3 support METER\_REPORT\_COMMAND\_V2

Group 1 for “LifeLine”: (maximum node:1)

Device Reset Locally CC, V2

Meter CC, V2

For group 1, the Clamp Meter will report:

1. The sum of instant Power Consumption (Watt) read from CT1 and CT2
2. The sum of accumulated Power Consumption (KWh) read from CT1 and CT2 Group 2 for “meter CT1” (maximum node: 1)

Meter CC, V2

For group 2, the Switch will report:

1. Instant Power Consumption (Watt) read from CT1
2. Accumulated Power Consumption (KWh) read from CT1 Group 3 for “meter CT2”: (maximum node: 1)

Meter CC, V2

For group 3, the Switch will report



1. The sum of instant Power Consumption (Watt) read from CT2
2. The sum of accumulated Power Consumption (KWh) read from CT2

## _**Z-Wave’s Multi Channel Association**_

The Multi Channel Association Command Class is used to create application bindings to Multi Channel End Point resources as well as to Root Devices. The command class can handle nodes with and without end points.

For Root, it supports maximum 1 node and maximum 3 association groups

<figure><img src=".gitbook/assets/11 (66).png" alt=""><figcaption></figcaption></figure>

For Endpoint 1, it supports maximum 1 node and maximum 2 association groups.

<figure><img src=".gitbook/assets/12 (71).png" alt=""><figcaption></figcaption></figure>

For Endpoint 2, it supports maximum 1 node and maximum 2 association groups.

<figure><img src=".gitbook/assets/13 (60).png" alt=""><figcaption></figcaption></figure>

## _**Selected Endpoint**_

If Controller can use Multi\_Channel command class to access the endpoint of Clamp Meter, you may configure the endpoint value to react the Meter Command Class V2

**Selected Endpoint 1: (for CT1 of the first channel)**

* Device Type: Simple Meter
* Supported Command Classes Z-Wave Plus Info CC, V2 Association CC, V2 Association Group Information CC Multi Channel Association CC, V3 Meter CC, V2
* Descirption: For Endpoint 1, the Clamp Meter will report

1. Instant Power Consumption (Watt) read from CT1.
2. Accumulated Power Consumption (KWh) read from CT1.

**Selected Endpoint 2: (for CT2 of the second channel)**

* Device Type: Simple Meter
* Supported Command Classes Z-Wave Plus info CC, V2 Association CC, V2 Association Group Information CC Multi Channel Association CC, V3 Meter CC, V2
* Description:  For Endpoint 2, the Clamp Meter will report

1. Instant Power Consumption (Watt) read from CT2.
2. Accumulated Power Consumption (KWh) read from CT2
