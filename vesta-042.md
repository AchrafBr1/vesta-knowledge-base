# VESTA-042

PSM-29ZW / PSS-29ZW

## Power Switch Series

## **Introduction**

The Power Switch series includes the following models:

**PSS-29ZW:** Z-Wave Power Switch with Router function

**PSM-29ZW:** Z-Wave Power Switch with Meter function and Router function

The Z-Wave-enabled Power Switches are capable of receiving wireless signals from the coordinator in the Z-Wave network to toggle On/Off of appliances that are attached to it. The Power Switch also serves as a router in the Z-Wave network. After being included in the Z-Wave network, it allows other Z-Wave device to join the network through the Power Switch.

The Power Switch with Meter function (PSM-29ZW) has the extra feature of keeping tracks of energy consumption with built-in power meter and transmitting the data to coordinator regularly.

Z-Wave is a wireless communication protocol that uses a low-power RF radio. By taking advantage of the Z-Wave mesh network, commands can be transmitted to their destination via intermediary “listening” Z-Wave products.

The Z-Wave Power Switches allow access to the “S2 Unauthenticated” class and support Z-Wave SmartStart inclusion as well as classic inclusion.

## **Parts Identification**

1\. Function Button aka LED indicator

The Function Button also doubles as the LED Indicator. The Function Button is used to control the Power Switch. The LED indicator is used to indicate Power Switch status.

### **LED Indication:**

The LED indicator lights up in the following conditions:

* On: power on
* Off: power off
* Red light flashes twice:

1\. The Power Switch has just been powered on.

2\. The Power Switch has just been factory reset.

## **Function Button Usage:**

* Press the Function Button to switch on/off the Power Switch.
* Press the Function Button 3 times within 1.5 seconds to transmit a learn code.
* Press and hold the Function Button for 10 seconds to factory reset.

<figure><img src=".gitbook/assets/vesta-042 1.png" alt=""><figcaption></figcaption></figure>

## _**Adding Device (Inclusion)**_

This product can be included and operated in any Z-Wave network with other Z-Wave certified devices from other manufactures and/or other applications. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase reliability of the network.

The device supports both classic inclusion process and SmartStart inclusion process.

### **Classic Inclusion**

* Plug the Power Switch into a power outlet.
* Put the Z-Wave Gateway or Control Panel into **Inclusion** **mode** (please refer to the Z-Wave Gateway or Control Panel manual).
* Within 1.5 seconds, press the Function Button 3 times.
* Refer to the operation manual of the Z-Wave Gateway or Control Panel to complete the adding process.
* If the device has already been added (included) into another Z-Wave Gateway/Control Panel, or if the device is unable to be added into the current Z-Wave Gateway/Control Panel, please exclude it first (see _**Removing Device**_) before attempting to **include** it into the current Z-Wave Gateway/Control Panel.

### **SmartStart Inclusion**

<figure><img src=".gitbook/assets/vesta-042 2.png" alt=""><figcaption></figcaption></figure>

Z-Wave SmartStart utilizes the DSK of the device to enhance and simplify the inclusion process. DSK is Device Specific Key used for authentication. The DSK information is stored in the QR code format that is printed on a sticker and attached to the device.

* Scan the QR Code sticker on the Power Switch to obtain DSK and transfer to the Z-Wave gateway.
* Plug the Power Switch into a power outlet, a SmartStart inclusion request will be automatically sent to the gateway.
* The gateway will automatically include the device upon recognition of the device by matching the inclusion request with the DSK obtained

< NOTE>

* The DSK of the device is used only during inclusion.
* The DSK can be read without the Power Switch powered ON, so it is possible to prepare the gateway to include the device prior to powering up the Power Switch.

## _**Removing Device (Exclusion)**_

The device must be removed from existing Z-Wave network before being included into another. There are two methods available to exclude a device.

### **Exclusion Mode**

* Put the Z-Wave Gateway or Control Panel into **Exclusion mode** (please refer to the Z-Wave Gateway or Control Panel manual).
* Within 1.5 seconds, press the Function Button 3 times and the device will be removed from the Z-Wave network.

## **Factory Reset**

_(Only use factory reset when network Control Panel/Gateway is missing or inoperable)._

* Press and hold the Function Button of the device for 10 seconds to factory reset.

\<NOTE>

* Factory resetting the device will restore it to factory default settings (excluded from the Z-Wave network). The Z-Wave Gateway or Control Panel will still keep its Z-Wave settings. Please refer to the Gateway or Control Panel manual on how to remove the device’s Z-Wave settings.
* Factory resetting the device will also clear all accumulated power data.
* Before you remove or factory reset the Power Switch, please ensure that the device DSK information has been removed or does not exist in the gateway. If you remove or factory reset the device, but its DSK still exists in the gateway, the gateway will automatically include the device again.

## _**Range Test**_

To test whether the device is able to communicate with the Z-Wave Gateway or Control Panel:

* Put the Gateway / Panel into range test mode (Walk Test).
* Press the Function Button on the device.
* The Gateway / Panel should display if the device is within the operation range (please refer to the operation manual of the Gateway / Panel).
* _Z-Wave Router Device Capacity_

The Power Switch allows other Z-Wave devices to join the Z-Wave Network through the Router. The maximum capacity of the devices to join the Z-Wave Network through the Power Switch is 255.

### Operation

* _**Appliance Control**_
* After being included into a Z-Wave Gateway or Control Panel, plug a home appliance into the Power Switch. This home appliance’s power and energy usage data will be transferred to the Control Panel.
* Users can remotely turn on/off the electric appliance through the Control Panel (please refer your Control Panel manual).
* Pressing the Function Button on the Power Switch can also toggle on/off the Power Switch.
* The Power Switch transmits a signal with power data to Z-Wave Gateway/Panel every 10 minutes starting from the last time a signal is transmitted.
* When the Power Switch is re-plugged after it has been removed from the power outlet, the previous on/off status of Power Switch will be resumed immediately.

## _**Energy Consumption Monitor (PSM-29ZW only)**_

* If the power output is below 1kW, PSM-29 will transmit a signal to Z-Wave Gateway/Panel when the power deviates by +/- 2W to update PSM-29’s power information.
* If the power output is above 1kW, PSM-29 will transmit a signal to Z-Wave Gateway/Panel when the power deviates by +/- 5W to update PSM-29’s power information.
* The Power Switch transmits a signal with power data to Z-Wave Gateway/Panel whenever power usage increases by 0.1kW/hr.
* When the power is below 20W, measurement error is more likely to occur.

## _**Power Specification**_

* For **110V:** the maximum operation load is 1760W and 16A. Warning: please do not exceed the maximum load.
* For **230V:** the maximum operation load is 3680W and 16A. Warning: please do not exceed the maximum load.
* If the Power Switch is overheating, it will cut off power automatically as a safety measure. The Power Switch must be un-plugged and re-plugged after cut off to resume normal operation.

## _**Z-Wave Information**_

**Device Type:** On/Off Power Switch

**Role Type:** Always On Slave (AOS)

**Command Class Support/Control**

**Mandatory CC Support:**&#x20;

Association CC, v2 or newer

Association Group Information CC

Meter CC, v2

Basic CC

Binary Switch CC

Device Reset Locally CC

Manufacturer Specific CC

Powerlevel CC

Version CC, v2 or newer

Z-Wave Plus Info CC

**Recommended CC Support:** Firmware Update Metadata CC

### _**Z-Wave’s Groups (Association Command Class Version 2)**_

The Switch can be set to send reports to associated Z-Wave devices. It supports one association group with five node support for Grouping 1. For grouping 1, the Switch will report its latest status to Z-Wave Gateway/Panel.

Grouping 1 includes:

Binary Switch CC (SWITCH\_BINARY\_REPORT)

Meter CC, v2 (METER\_REPORT\_COMMAND)

Device Reset Locally CC (COMMAND\_CLASS\_DEVICE\_RESET\_LOCALLY)

* Auto report to Grouping 1 (Maximum Node 5)
* On/Off Event Report

When toggling between On/Off, it will send Binary Switch Report to the nodes of Grouping 1.

* Factory Reset

When the Power Switch is reset to factory default, it will send Device Reset Locally to all nodes in Group 1.
