# VESTA-260

**PSM-DIN3-ZW**&#x20;

## **DIN-Rail Power Switch Meter**&#x20;

<figure><img src=".gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

The Power Switch is capable of receiving wireless signals from the coordinator in the Z-Wave network to toggle On/Off of appliances that are attached to it. The Power Switch also features keeping tracks of energy consumption with built-in power meter and transmit the data to the Z-Wave network regularly.

The Power Switch is a Z-Wave enabled device and is fully compatible with any Z-Wave enabled network.

Z-Wave is a wireless communication protocol that uses a low-power RF radio. By taking advantage of the Z-Wave mesh network, commands can be transmitted to their destination via intermediary “listening” Z-Wave products.

The PSM-DIN3-ZW series includes the following models:

PSM-DIN3-ZW

PSM-DIN3-ZW-OTA

![](<.gitbook/assets/0 (107).jpeg>)

## _**Identifying the Parts**_

1. **Input Connector**
2. **Output Connector**
3. **External Antenna Port**
4. **LED Indicator**
5. **Function Button**

Press the Function Button 3 times within 1.5 seconds to transmit a learn code

Press and hold for 10 seconds to factory reset Press once to toggle on/off the connected appliance

## _**LED Indicator**_

* On: power on
* Off: power off
*   Red light flashes twice: 1. The Power Switch has just been powered on, _or_

    &#x20;                                           2\. The Power Switch has just been factory reset.

## _**Caution**_

* All works on the device, including installation and maintenance, must be performed by a qualified and licensed electrician.
* Before installation or any maintenance work, make sure the power supply has been disconnected.
* Do not connect the device to loads exceeding supported load current.

## _**Wiring and Installation**_

**Before installation, make sure the power supply has been disconnected.**

* Connect L terminal of input connector to the L terminal of Power Supply, please use fuse for the wire. Connect N terminal of input connector to the N terminal of Power Supply.
* Connect N terminal of output connector to the N terminal of external device, and connect L terminal of output connector to the L terminal of external device.
* Connect the external antenna to the external antenna port.
* Mount the device inside the electrical enclosure using a DIN rail.

![](<.gitbook/assets/1 (93).jpeg>)

## _**Inclusion (Adding or Learning Device)**_

This product can be included and operated in any Z-Wave network with other Z-Wave certified devices from other manufactures and/or other applications. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase reliability of the network.

* Power on the device by turning on external power supply.
* Put the Z-wave gateway or control panel into **Inclusion** or **Learning** mode (please refer to the Z-wave gateway or control panel manual).
* Within 1.5 seconds, press the Function Button 3 times.
* Refer to the operation manual of the Z-wave gateway or control panel to complete the learn-in process.
* If the device has already been **included** (learnt) into another Z-wave Gateway/Control Panel, or if the device is unable to be learnt into the current Z-wave Gateway/Control Panel, please exclude it first (see _**Exclusion**_) before attempting to **include** it into the current Z-wave Gateway/Control Panel.

## _**Exclusion (Removing Device)**_

The device must be removed from existing Z-wave network before being included into another. There are two methods available to exclude a device.

### **Exclusion Mode**

* Put the Z-wave gateway or control panel into **Exclusion mode** (please refer to the Z-wave gateway or control panel manual).
* Within 1.5 seconds, press the Function Button 3 times and the device will be removed from the Z-wave network.

### **Factory Reset**

_(Only use factory reset when network Control Panel/Gateway is missing or inoperable)._

* Press and hold the Function Button of the device for 10 seconds to factory reset.

{% hint style="warning" %}
Note:

* Factory resetting the device will restore it to factory default settings (excluded from the Z-wave network). The Z-wave gateway or control panel will still keep its Z-wave settings. Please refer to the gateway or control panel manual on how to remove the device’s Z-wave settings.
* Factory resetting the device will also clear all accumulated power data.
{% endhint %}

## _**Range Test**_

To test whether the device is able to communicate with the Z-Wave Gateway or Control Panel:

* Put the Gateway / Panel into range test mode (Walk Test).
* Press the Function Button on the device.
* The Gateway / Panel should display if the device is within the operation range (please refer to the operation manual of the Gateway / Panel).

## _**Operation**_

* After being included into a Z-wave gateway or control panel, plug a home appliance into the Power Switch. This home appliance’s power and energy usage data will be transferred to the Gateway / Control Panel.
* Pressing the switch button on the Power Switch can also toggle on/off the Power Switch.
* Remotely turn on/off the electric appliance through the Control Panel (please refer the manual of your Control Panel).
* If the power output is below 1kW, PSM-DIN3 will transmit a signal to Z-wave gateway/panel when the power deviates by +/- 2W to update PSM-DIN3’s power information.

If the power output is above 1kW, PSM-DIN3 will transmit a signal to Z-wave gateway/panel when the power deviates by +/- 5W to update PSM-DIN3’s power information.

* PSM-DIN3 transmits a signal with power data to Z-wave gateway/panel every 10 minutes starting from the last time a signal is transmitted.
* The Power Switch transmits a signal with power data to Z-wave gateway/panel whenever power usage increases by 0.1kW/hr.
* If power of the Power Switch is reconnected from a previous disconnection, the previous on/off status of Power Switch will be resumed immediately.
* When the power is below 20W, measurement error is more likely to occur.

## _**Power Specification**_

* For **110V:** the maximum operation load is 3300W and 30A. Warning: please do not exceed the maximum load.
* For **230V:** the maximum operation load is 6900W and 30A. Warning: please do not exceed the maximum load.

## _**Overheat Protection**_

When the Power Switch is overheating, it will turn off automatically. When the temperature returns to normal, it will turn on automatically to resume normal operation.

## _**Z-Wave Information**_

**Device Type:** Generic Type Switch Binary

**Role Type:** Always On Slave (AOS)

**Product Type:** 0x0004

**Product ID:** 0x0013

## **Command Class Support/Control**

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

## Meter Report:

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
