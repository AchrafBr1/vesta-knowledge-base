# VESTA-259

**PSM-DIN2-ZW Series**

## **DIN-Rail Power Switch Meter**

<figure><img src=".gitbook/assets/image (19) (1).png" alt=""><figcaption></figcaption></figure>

The Power Switch is capable of receiving wireless signals from the coordinator in the Z-Wave network to toggle On/Off of appliances that are attached to it. The Power Switch also features keeping tracks of energy consumption with built-in power meter and transmit the data to the Z-Wave network regularly.

The Power Switch is a Z-Wave enabled device and is fully compatible with any Z-Wave enabled network.

Z-Wave is a wireless communication protocol that uses a low-power RF radio. By taking advantage of the Z-Wave mesh network, commands can be transmitted to their destination via intermediary “listening” Z-Wave products.

The PSM-DIN2-ZW series includes the following models:

PSM-DIN2-ZW

PSM-DIN2-ZW-OTA

## _**Identifying the Parts**_

<figure><img src=".gitbook/assets/11 (2) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

1. **Input Connector**
2. **Output Connector**
3. **External Antenna Port**
4. **LED Indicator**
5. **Function Button**

&#x20;      -Press the Function Button 3 times within 1.5 seconds to send a learn code.

&#x20;      -Press and hold for 10 seconds to factory reset.

## _**LED Indicator**_

* On: power on
* Off: power off
* Red light flashes twice:

&#x20;      1\. The Power Switch has just been powered on, _or_

&#x20;      2\. The Power Switch has just been factory reset.

## _**Caution**_

* All works on the device, including installation and maintenance, must be performed by a qualified and licensed electrician.
* Before installation or any maintenance work, make sure the power supply has been disconnected.
* Do not connect the device to loads exceeding supported load current.

## _**Wiring and Installation**_

**Before installation, make sure the power supply has been disconnected.**

![](<.gitbook/assets/7 (55).jpeg>)

* Connect L terminal of input connector to the L terminal of Power Supply, please use fuse for the wire. Connect N terminal of input connector to the N terminal of Power Supply.
* Connect N terminal of output connector to the N terminal of external device, and connect L terminal of output connector to the L terminal of external device.
* Connect the external antenna to the external antenna port.
* Mount the device inside the electrical enclosure using a DIN rail.

## _**Inclusion (Adding or Learning Device)**_

This product can be included and operated in any Z-Wave network with other Z-Wave certified devices from other manufactures and/or other applications. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase reliability of the network.

* Power on the device by turning on external power supply.
* Put the Z-Wave Gateway or Control Panel into **Inclusion** or **Learning** mode (please refer to the Z-Wave Gateway or Control Panel manual).
* Within 1.5 seconds, press the Function Button 3 times.
* Refer to the operation manual of the Z-Wave Gateway or Control panel to complete the adding process.
* If the device has already been added (included) into another Z-Wave Gateway/Control Panel, or if the device is unable to be added into the current Z-Wave Gateway/Control Panel, please exclude it first (see _**Exclusion**_) before attempting to include it into the current Z-Wave Gateway/Control Panel.

## _**Exclusion (Removing Device)**_

The device must be removed from existing Z-Wave network before being included into another. There are two methods available to exclude a device.

**Exclusion Mode**

* Put the Z-Wave Gateway or Control Panel into **Exclusion mode** (please refer to the Z-Wave Gateway or Control panel manual).
* Within 1.5 seconds, press the Function Button 3 times and the device will be removed from the Z-Wave network.

## **Factory Reset**

_(Only use factory reset when network Control Panel/Gateway is missing or inoperable)._

* Press and hold the Function Button of the device for 10 seconds to factory reset.

{% hint style="warning" %}
Note:

* Factory resetting the device will restore it to factory default settings (excluded from the Z-Wave network). The Z-Wave Gateway or Control Panel will still keep its Z-Wave settings. Please refer to the Gateway or Control Panel manual on how to remove the device’s Z-Wave settings.
* Factory resetting the device will also clear all accumulated power data.
{% endhint %}

## _**Range Test**_

To test whether the device is able to communicate with the Z-Wave Gateway or Control Panel:

* Put the Gateway / Panel into range test mode (Walk Test).
* Press the Function Button on the device.
* The Gateway / Panel should display if the device is within the operation range (please refer to the operation manual of the Gateway / Panel).

## _**Operation**_

* After being included into a Z-Wave Gateway or Control Panel, plug a home appliance into the Power Switch. This home appliance’s power and energy usage data will be transferred to the Control Panel.
* Pressing the switch button on the Power Switch can also toggle on/off the Power Switch.
* Remotely turn on/off the electric appliance through the Control Panel (please refer the manual of your Control Panel).
* If the power output is below 1kW, PSM-DIN2 will transmit a signal to Z-Wave Gateway/Panel when the power deviates by +/- 2W to update PSM-DIN2’s power information. If the power output is above 1kW, PSM-DIN2 will transmit a signal to Z-Wave Gateway/Panel when the power deviates by +/- 5W to update PSM-DIN2’s power information.
* PSM-DIN2 transmits a signal with power data to Z-Wave Gateway/Control Panel every 10 minutes starting from the last time a signal is transmitted.
* The Power Switch transmits a signal with power data to Z-Wave Gateway/Control Panel whenever power usage increases by 0.1kW/hr.
* If power of the Power Switch is reconnected from a previous disconnection, the previous on/off status of Power Switch will be resumed immediately.
* When the power is below 20W, measurement error is more likely to occur.

## _**Power Specification**_

* For **110V:** the maximum operation load is 1760W and 16A. Warning: please do not exceed the maximum load.
* For **230V:** the maximum operation load is 3680W and 16A. Warning: please do not exceed the maximum load.

## _**Z-Wave Information**_

**Device Type:** Generic Type Switch Binary

**Role Type:** Always On Slave (AOS)

**Product Type:** 0x0004

**Product ID:** 0x0003

**Command Class Support/Control**

**Mandatory CC Support:** Z-Wave Plus Info CC

Association CC ,(S2)

Multi Channel Association CC ,(S2)

Association Group Information CC ,(S2)

Transport Service CC

Version CC ,(S2)

Manufacturer Specific CC ,(S2)

Device Reset Locally CC ,(S2)

Power Level CC ,(S2)

Meter CC, v2

Switch Binary CC

Supervision CC ,(S2)

Firmware Update Md CC ,(S2)

## _**Z-Wave’s Groups (Association Command Class Version 2)**_

The Switch can be set to send reports to associated Z-Wave devices. It supports one association group with five node support for Grouping 1. For grouping 1, the Switch will report its latest status to Z-Wave Gateway/Panel. Group 1 for “LifeLine”: (max node : 5)

Switch Binary CC (COMMAND\_CLASS\_SWITCH\_BINARY)

Meter CC (COMMAND\_CLASS\_METER)

Device Reset Locally CC (COMMAND\_CLASS\_DEVICE\_RESET\_LOCALLY)

* Auto report to Grouping 1 (Maximum Node 5)
* On/Off Event Report

When toggling between On/Off, it will send Binary Switch Report to the nodes of Grouping 1.

* Factory Reset

When the Power Switch is reset to factory default, it will send Device Reset Locally to all nodes in Group 1.

* Meter Report:
  * If the power output is below 1kW, PSM-DIN2 will transmit a signal to Z-Wave Gateway/Panel when the power deviates by +/- 2W to update PSM-DIN2’s power information.
  * If the power output is above 1kW, PSM-DIN2 will transmit a signal to Z-Wave Gateway/Panel when the power deviates by +/- 5W to update PSM-DIN2’s power information.
  * PSM-DIN2 transmits a signal with power data to Z-Wave Gateway/Control Panel every 10 minutes starting from the last time a signal is transmitted.
  * The Power Switch transmits a signal with power data to Z-Wave Gateway/Control Panel whenever power usage increases by 0.1kW/hr.
  * Data format:

Example 1: **41 64 00 00 50 14** FF FF **00 00 00 00** kWh (00005014 = 20500 = 20.5)

* Present Value: **41 64 00 00 50 14**
* Previous Value: **00 00 00 00**

Example 2: **41 74 00 00 27 10** FF FF **00 00 00 00** W (00002710 = 10000 = 10W)

* Present Value: **41 74 00 00 27 10**
* Previous Value: **00 00 00 00**
