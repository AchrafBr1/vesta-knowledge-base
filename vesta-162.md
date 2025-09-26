# VESTA-162

**PRM2-ZW-P5**

## **Z-Wave Power Relay Switch with Meter**

<figure><img src=".gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

## **Introduction**

The Power Relay Switch is capable of receiving wireless signals from the coordinator in the Z-Wave network to toggle On/Off of appliances that are attached to it.

The Power Relay Switch is a Z-Wave enabled device and is fully compatible with any Z-Wave enabled network.

Z-Wave is a wireless communication protocol that uses a low-power RF radio. By taking advantage of the Z-Wave mesh network, commands can be transmitted to their destination via intermediary “listening” Z-Wave products.

PRM2-ZW-P5 has the extra feature of keeping tracks of energy consumption with built-in power meter and transmitting the data to coordinator regularly.

PRM2-ZW-P5 also serves as a router in the Z-Wave network. After being included in the Z-Wave network, it allows other Z-Wave device to join the network through the Power Switch.

## **Parts Identification**

![](<.gitbook/assets/0 (66).jpeg>)

**1. LED indicator**

The LED indicator is used to indicate Power Relay Switch status:

* On:  The Power Relay Switch is turned on.
* Off:  The Power Relay Switch is turned off.



2. **Function Button**

The function button is used to control the Power Relay Switch:

&#x20;    **Function Button Usage:**

&#x20;    **-** Press the button to toggle on/off the Power Relay Switch

&#x20;    \- Press the button 3 times within 1.5 seconds to add in/remove from the Z-Wave network.

&#x20;    \- Press and hold the button for 10 seconds to factory reset.

3. **External Switch Terminal 1**
4. **External Switch Terminal 2**
5. **AC Line Power Input**
6. **AC Neural Power Input**
7. **AC Neutral Power Load Output**
8. **AC Line Power Load Output**

## **Operation**

### _**Wire Connection Diagram**_

* Refer to the diagram to connect your devices to Power Relay Switch.

### _**Installation**_

![](<.gitbook/assets/1 (62).jpeg>)

**Step 1:** Shut off the electricity supply to the power cable to for safety and to ensure that the wire would not short circuit during the installation process.

**Step 2:** Connect the AC input power cable to the input connector and the output power cable to the output connector.

**Step 3:** For external switch connection, connect the switch with the external switch control.

**Step 4:** After completing wiring, restore the electricity supply to the power cable.

## _**Adding Device (Inclusion)**_

This product can be included and operated in any Z-Wave network with other Z-Wave certified devices from other manufactures and/or other applications. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase reliability of the network.

*
  * Connect the Power Relay Switch to power cable.
  * Put the Z-Wave gateway or control panel into **Inclusion** or **Learning** mode (please refer to the Z-Wave gateway or control panel manual).
  * Within 1.5 seconds, press the Function Button 3 times.
  * Refer to the operation manual of the Z-Wave gateway or control panel to complete the learn-in process.
  * If the sensor has already been **included** (learnt) into another Z-Wave Gateway/Control Panel, or if the sensor is unable to be learnt into the current Z-Wave Gateway/Control Panel, please exclude it first (see _**Exclusion**_) before attempting to **include** it into the current Z-Wave Gateway/Control Panel.

## _**Removing Device (Exclusion)**_

The Power Relay Switch must be removed from existing Z-Wave network before being included into another. There are two methods available to exclude a device.

**Exclusion Mode**

* Put the Z-Wave gateway or control panel into **Exclusion mode** (please refer to the Z-Wave gateway or control panel manual).
* Within 1.5 seconds, press the Function Button 3 times and the Power Relay Switch will be removed from the Z-Wave network.

**Factory Reset**

_(Only use factory reset when network Control Panel/Gateway is missing or inoperable)._

* Press and hold the Function Button for 10 seconds to factory reset.

{% hint style="warning" %}
Note:

Factory resetting the Power Relay Switch will restore it to factory default settings (excluded from the Z-Wave network). The Z-Wave gateway or control panel will still keep its Z-Wave settings. Please refer to the gateway or control panel manual on how to remove the Power Relay Switch’s Z-Wave settings.
{% endhint %}

## _**Range Test**_

To test whether the device is able to communicate with the Z-Wave gateway or control panel:

* Put the gateway / panel into range test mode (Walk Test).
* Press the Function Button on the device.
* The gateway / panel should display if the device is within the operation range (please refer to the operation manual of the gateway / panel).

## _**Appliance Control**_

* After the Power Relay Switch has successfully joined a Z-Wave network, the coordinator can remotely turn on/off the Appliance.
* You can also press the button on the Power Relay Switch to toggle on/off the light.
* You can turn on/off the Power Relay Switch with an external switch.
* If you have bound a controller with the Power Relay Switch, you can also use the controller to turn on/off the Power Relay Switch.
* If the AC Power input is disconnected from the Power Relay Switch, its previous on/off status will be restored within 1 minute after reconnecting the AC Power input to the Power Relay Switch.

## _**Energy Consumption Monitor**_

* The Power Relay Switch will transmit a signal with its power consumption data every 1 minute to the Z-Wave network coordinator.
* Whenever the Power Switch energy output changes by +/- 2W, it will automatically transmit a signal with power consumption data to the Z-Wave network coordinator for update.
* The Power Switch transmits a signal with power data to coordinator whenever accumulated power usage increases by 0.1kW/hr.
* The Meter has an accuracy of +/- 5%.
* 2 methods to clear the Power Relay Switch of its accumulated power consumption data:
  1. Use Meter Reset Command Class.
  2. Execute Factory Reset. Press and hold the Function Button for 10 seconds.

{% hint style="warning" %}
Note:

If you execute Factory Reset, the device will be removed from Z-wave network. You have to include it again. For the instructions of Inclusion, please refer to the section of _**Adding Device (Inclusion)**._
{% endhint %}

## _**Maximum Operation Load**_

* For 110V: the maximum operation load is 1100W and 10A.
* For 230V: the maximum operation load is 2300W and 10A.
* If the Power Relay Switch is overheating, it will cut off power automatically as a safety measure. The user must disconnect and reconnect AC power to the Power Relay Switch after cut off to resume normal operation.

## _**Z-Wave Information**_

**Device Type:** On/Off Power Switch

**Role Type:** Always On Slave (AOS)

**Command Class Support/Control**

**Mandatory CC Support:** Association CC, v2 or newer

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

## _**Z-Wave’s Groups (Association Command Class Version 2)**_

The Switch can be set to send reports to associated Z-Wave devices. It supports one association group with five node support for Grouping 1. For grouping 1, the Switch will report its latest status to Z-Wave Gateway/Panel.

Grouping 1 includes:

Binary Switch CC (SWITCH\_BINARY\_REPORT)

Meter CC, v2 (METER\_REPORT\_COMMAND)

Device Reset Locally CC (COMMAND\_CLASS\_DEVICE\_RESET\_LOCALLY)

* Auto report to Grouping 1 (Maximum Node 5)
* On/Off Event Report

When toggling between On/Off, it will send Binary Switch Report to the nodes of Grouping 1.
