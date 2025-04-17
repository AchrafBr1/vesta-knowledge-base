# VESTA-163

**PRS5-P5-ZW**

## **Z-Wave Power Relay Switch**

## **Introduction**

The Power Relay Switch is capable of receiving wireless signals from the coordinator in the Z-Wave network to toggle On/Off of appliances that are attached to it.

The Power Relay Switch is a Z-Wave enabled device and is fully compatible with any Z-Wave enabled network.

Z-Wave is a wireless communication protocol that uses a low-power RF radio. By taking advantage of the Z-Wave mesh network, commands can be transmitted to their destination via intermediary “listening” Z-Wave products.

PRS5-P5-ZW also serves as a router in the Z-Wave network. After being included in the Z-Wave network, it allows other Z-Wave device to join the network through the Power Switch.

## **Parts Identification**

![](<.gitbook/assets/0 (67).jpeg>)

**1. LED indicator**

The LED indicator is used to indicate Power Relay Switch status:

* On: The Power Relay Switch is turned on.
* Off:  The Power Relay Switch is turned off.
* Flashes twice: The Power Relay Switch has successfully added into Z-Wave network.
* Flashes three times: The Power Relay Switch has successfully bound with a controller.
* Flashes five times: The Power Relay Switch was unable to bind with a controller.



2. **Function Button**

&#x20;      The function button is used to control the Power Relay Switch:

&#x20;     **Function Button Usage**

* Press the button to toggle on/off the Power Relay Switch
* Press the button 3 times within 1.5 seconds to send a learn code.
* Press and hold the button for 3 seconds then release to bind with a controller
* Press and hold the button for 10 seconds to factory reset.

3. **External Switch connection cable 1 (Red)**
4. **External Switch connection cable 2 (Orange)**
5. **AC Line Power Load Output (Yellow)**
6. **AC Neural Power Input/AC Neutral Power Load Output (Blue)**
7. **AC Line Power Input (Brown)**

### **Caution**

* All works on the device, including installation and maintenance, must be performed by a qualified and licensed electrician.
* Before installation or any maintenance work, make sure the power supply has been disconnected.
* Do not connect the device to loads exceeding supported load current.

## **Installation**

* _**Wiring with Splicing Connector**_
  * The Power Relay Switch comes with embedded cable for connecting to AC power, appliance, and external switch. Five Wago 221 Splicing Connectors are provided for connection.
  * The 2-wire/3-wire connectors accommodate solid and stranded wires from 0.2 to 4 mm² (24–12 AWG).
  * Before wiring, please make sure the power is off. To connect the wires:

1. Lift the lever and insert the brown wire. **(Picture 1, 2)**

![Picture1                                                                                                                                 Picture 2](<.gitbook/assets/1 (63).png>)



2. Push the lever back down. The transparent housing allows you to check if the wire is connected properly. Make sure the wire is held in place tightly and won't come off. **(Picture 3, 4)**

![Picture3                                                                                                                                                    Picture 4](<.gitbook/assets/2 (67).png>)

3\) In the same way as step 1 & 2, insert into another pole the wire for connecting to&#x20;AC Line Power Input. (Picture 5)

![Picture 5](<.gitbook/assets/3 (50).jpeg>)



4\) Repeat step 1 & 2 & 3 to connect the other wires with connectors.

Please be noted that the blue wire must be connected to a 3-wire connector and then connected to AC Neural Power Input and AC Neutral Power Load Output. **(Picture 6)**

![Picture 6](<.gitbook/assets/4 (67).png>)



## **Z-Wave Network Setup**

* _**Adding Device (Inclusion)**_

This product can be included and operated in any Z-Wave network with other Z-Wave certified devices from other manufactures and/or other applications. All non-battery operated nodes within the network will act as repeaters regardless of vendor to increase reliability of the network.

* Connect the Power Relay Switch to power cable.
* The Power Relay Switch will emit a 2-tone beep.
* Put the Z-Wave gateway or control panel into **Inclusion** or **Learning** mode (please refer to the Z-Wave gateway or control panel manual).
* Within 1.5 seconds, press the Function Button 3 times. The Power Relay Switch will emit a 2-tone beep.
* Refer to the operation manual of the Z-Wave gateway or control panel to complete the learn-in process.
* If the sensor has already been **included** (learnt) into another Z-Wave Gateway/Control Panel, or if the sensor is unable to be learnt into the current Z-Wave Gateway/Control Panel, please exclude it first (see _**Exclusion**_) before attempting to **include** it into the current Z-Wave Gateway/Control Panel.
* _**Removing Device (Exclusion)**_

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

* _**Range Test**_

To test whether the device is able to communicate with the Z-Wave gateway or control panel:

* Put the gateway / panel into range test mode (Walk Test).
* Press the Function Button on the device.
* The gateway / panel should display if the device is within the operation range (please refer to the operation manual of the gateway / panel).
* _**Z-Wave Sleep Mode**_
  * The Power Relay Switch will enter Z-Wave Sleep mode (to conserve power) after waking up for a short period of time (\~10 seconds). While in Z-Wave sleep mode, Z-Wave gateways or control panels are unable to send commands to the Power Relay Switch.
  * To program the Power Relay Switch, please send command(s) to the Power Relay Switch within the wake-up period.
* _**Binding with Controller**_

After joining the Z-Wave network, the Power Relay Switch can bind itself with a controller device which can be used to adjust the Power Relay Switch’s power output level. To bind the Power Relay Switch and the device:

1. Press and hold the Function Button for 3 seconds, then release the button. The Power Relay Switch will send binding request to the coordinator.
2. Refer to your controller manual to send binding request for the device within 16 seconds.
3. If binding is successful, the Power Relay Switch LED indicator will flash 3 times to confirm. You can now use the controller to adjust power output level for the Power Relay Switch.
4. If binding is unsuccessful, the Power Relay Switch LED indicator will flash 5 times. Please retry the binding process.

![](<.gitbook/assets/5 (34).jpeg>)

## **Operation**

* _**Wire Connection Diagram**_
  * Refer to the diagram to connect your home lighting to the Power Relay Switch.
* _**Installation**_
  * Connect the Power Relay Switch to power cable.
  * Connect the Power Relay Switch to your home lighting. The lighting must be in ON status.
  * You can connect an external switch to the Power Relay Switch according to the diagram to turn on/off the Power Relay Switch.

{% hint style="danger" %}
_**IMPORTANT NOTE**_**:**&#x20;

The Power Relay Switch does not have a backup battery and will be powered down when AC power fails. **DO NOT** use the Power Relay Switch as router for your security sensor or alarm control devices such as Door Contact, PIR Sensor…etc., otherwise the sensors will lose connection to Z-Wave network if the Power Relay Switch is disconnected from AC power. Plan the installation locations of these security sensors without using the Power Relay Switch and only use a router with backup battery for them. The router function of the Power Switch should **ONLY** be used to provide signal range extension for other Power Switches/Dimmer.
{% endhint %}

* _**Appliance Control**_
  * After the Power Relay Switch has successfully joined a Z-Wave network, the coordinator can remotely turn on/off the Appliance.
  * You can also press the button on the Power Relay Switch to toggle on/off the light.
  * You can turn on/off the Power Relay Switch with an external switch.
  * If you have bound a controller with the Power Relay Switch, you can also use the controller to turn on/off the Power Relay Switch.
  * If the AC Power input is disconnected from the Power Relay Switch, its previous on/off status will be restored within 1 minute after reconnecting the AC Power input to the Power Relay Switch.
* _**Maximum Operation Load**_
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

Power level CC

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
