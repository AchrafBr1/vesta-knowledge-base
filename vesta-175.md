# VESTA-175

## **PRS5-ZBS(R)/PRM5-ZBS(R)**

## **Power Relay Switch Series**

## **Introduction**

The Power Relay Switch series include the following models:

**PRS5-ZBS:** ZigBee Relay Power Switch

**PRS5-ZBSR:** ZigBee Relay Power Switch with Router function

**PRM5-ZBS:** ZigBee Relay Power Switch with Meter

**PRM5-ZBSR:** ZigBee Relay Power Switch with Meter and Router function

The Power Switches are capable of receiving wireless signals from the coordinator in the Zigbee network to toggle On/Off of appliances that are attached to it.

The Power Relay Switch utilizes ZigBee technology for wireless signal transmission. ZigBee is a wireless communication protocol that is reliable, has low power consumption and has high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and coordinated for data exchange and signal transmission.

Models with Meter functions have the extra feature of keeping tracks of energy consumption with built-in power meter and transmit the data to coordinator regularly.

Models with router function also serve as a router in the ZigBee network. After being included in the ZigBee network, it allows other ZigBee device to join the network through the Power Switch.

Models with OTA function supports OTA firmware upgrade feature via ZigBee network, which can be initiated from the ZigBee network coordinator.

<figure><img src=".gitbook/assets/image (160).png" alt=""><figcaption></figcaption></figure>

**Parts Identification**

![](<.gitbook/assets/0 (75).jpeg>)

1. &#x20;**LED indicator**

The LED indicator is used to indicate Power Relay Switch status:

* On: The Power Relay Switch is turned on.
* Off: The Power Relay Switch is turned off.
* Flashes twice: The Power Relay Switch has successfully joined a ZigBee network.
* Flashes 5 times:The Power Relay Switch has successfully bound with a controller
* Flashes every 20 minutes: The Power Relay Switch has lost connection to its current ZigBee network

2.  **Function Button**

    **Function Button Usage:**

    1. Press the button to toggle on/off the Power Relay Switch
    2. Press and hold the button for 10 seconds then release to reset the Power Relay Switch.
    3. Press and hold the button for 3 seconds then release to bind with a controller
3. **External Switch connection cable 1**
4. **External Switch connection cable 2**
5. **AC Line Power Load Output**
6. **AC Neural Power Input/AC Neutral Power Load Output**
7. **AC Line Power Input**

## **ZigBee Network Setup**

### _**ZigBee Device Guideline**_

ZigBee is a wireless communication protocol that is reliable, has low power consumption and has high transmission efficiency. Based on the IEEE802.15.4 standard, ZigBee allows a large amount of devices to be included in a network and are coordinated for data exchange and signal transmission.

Due to the fundamental structure of ZigBee network, ZigBee device will actively seek and join network after powering on.

### _**Joining the ZigBee Network**_

As a ZigBee device, the Power Relay Switch needs to join a ZigBee network to receive commands and transmit energy consumption information. Please follow the steps bellow to join the Power Relay Switch into a ZigBee network.

1. Connect the Power Relay Switch to power cable.
2. Press and hold the Function button for 10 seconds, then release it to join the network. Please make sure the permit-to-join feature on the router or coordinator of your ZigBee network is enabled.
3. If the Power Relay Switch successfully joins a ZigBee network, the LED Indicator will flash twice to confirm.
4. After joining the ZigBee network, the Power Relay Switch will be registered in the network automatically. Please check the Zigbee network coordinator, system control panel or CIE (Control and Indicating Equipment) to confirm if joining and registration is successful.
5. If registration and joining to the network is unsuccessful, please check your ZigBee network coordinator, system control panel or CIE setting to ensure the permit-to-join function is available, and then use the Factory Reset function below to join the ZigBee network.

### _**Binding with Controller**_

After joining the ZigBee network, the Power Relay Switch can bind itself with a controller device which can be used to adjust the Power Relay Switch’s power output level. To bind the Power Relay Switch and the device:

1. Press and hold the Function Button for 3 seconds, then release the button. The Power Relay Switch will send binding request to the coordinator.
2. Refer to your controller manual to send binding request for the device within 16 seconds.
3. If binding is successful, the Power Relay Switch LED indicator will flash 5 times to confirm. You can now use the controller to adjust power output level for the Power Relay Switch.
4. If binding is unsuccessful, please retry the binding process.

### _**Removing Device from ZigBee Network (Factory Reset)**_

To remove the Power Switch from current ZigBee network, the Power Switch must be put to Factory Reset to complete device removal. Factory Reset function will clear the Power Switch of its stored setting and information and prompt the Power Switch to search for new ZigBee network.

**Before removing device, make sure the Power Switch is within current ZigBee network signal range**

1. Press and hold the function button for 10 seconds, then release the button to reset Power Switch.
2. Upon reset, the Power Switch will clear current ZigBee network setting and transmit signal to ZigBee coordinator to remove itself from current ZigBee network. It will then actively search for available ZigBee network again and join the network automatically.

### _**ZigBee Router Device Capacity (PRS5-ZBSR/PRM5-ZBSR Only)**_

The Power Switch models with Router function allow other ZigBee devices to join the ZigBee Network through the Router. The Power Switch Router has maximum capacity of 40 devices, including 10 routers; the Power Switch Meter Router has maximum capacity of 10 devices including 5 routers.

<figure><img src=".gitbook/assets/image (161).png" alt=""><figcaption></figcaption></figure>

### _**OTA Firmware Upgrade (For OTA version only)**_

The Power Relay Switch supports OTA firmware upgrade feature via ZigBee network, which can be initiated from the ZigBee network coordinator. Follow steps below to perform OTA firmware upgrade.

**Step 1.** You have to access your ZigBee Coordinator to perform the firmware upgrade on the air. **Step 2.** On the configuration webpage, select the device that you wish to upgrade and select the new

ZigBee firmware provided. Please refer to ZigBee Coordinator User Manual for details.

**Step 3.**&#x50;ress“OK”to start upgrading process, and the LED will keep flashing. During the OTA process,

please do not perform any other actions, or power down the panel.

**Step 4.**&#x54;he length of an upgrade will take approximately 20 to 30 minutes. Please note that the duration may vary based on file size or distance between your accessory and coordinator.

**Step 5.**&#x57;ait for firmware to complete update. When the progress reaches 100%, the Device will reset automatically. You can also refresh the webpage again to ensure that the Device firmware is successfully updated with the newest version displayed.

**Caution**

{% hint style="info" %}
* All works on the device, including installation and maintenance, must be performed by a qualified and licensed electrician.
* Before installation or any maintenance work, make sure the power supply has been disconnected.
* Do not connect the device to loads exceeding supported load current.
{% endhint %}

## **Installation**

### _**Wiring with Splicing Connector**_

* The Power Relay Switch comes with embedded cable for connecting to AC power, appliance, and external switch. Five Wago 221 Splicing Connectors are provided for connection.
* The 2-wire/3-wire connectors accommodate solid and stranded wires from 0.2 to 4 mm² (24–12 AWG).
* Before wiring, please make sure the power is off. To connect the wires:
  1. Lift the lever and insert the brown wire. **(Picture 1, 2)**

![Picture 1                                                                                                                                 Picture 2](<.gitbook/assets/1 (66).png>)

2. Push the lever back down. The transparent housing allows you to check if the wire is connected properly. Make sure the wire is held in place tightly and won't come off. **(Picture 3, 4)**

![Picture 3                                                                                                                                        Picture 4](<.gitbook/assets/2 (71).png>)

3. In the same way as step 1 & 2, insert into another pole the wire for connecting to AC Line Power Input. (Picture 5)

![Picture 5](<.gitbook/assets/3 (55).jpeg>)

4.  Repeat step 1 & 2 & 3 to connect the other wires with connectors.

    Please be noted that the blue wire must be connected to a 3-wire connector and then connected to AC Neural Power Input and AC Neutral Power Load Output. **(Picture 6)**

![Picture 6](<.gitbook/assets/4 (72).png>)

## **Operation**

### _**Wire Connection Diagram**_

Refer to the diagram to connect your home lighting to the Power Relay Switch.

![](<.gitbook/assets/5 (37).jpeg>)

### _**Installation**_

* Connect the Power Relay Switch to power cable.
* Connect the Power Relay Switch to your home lighting. The lighting must be in ON status.
* You can connect an external switch to the Power Relay Switch according to the diagram to turn on/off the Power Relay Switch
* _**IMPORTANT NOTE**_**:** The Power Relay Switch does not have a backup battery and will be powered down when AC power fails. **DO NOT** use the Power Relay Switch as router for your security sensor or alarm control devices such as Door Contact, PIR Sensor…etc., otherwise the sensors will lose connection to ZigBee network if the Power Relay Switch is disconnected from AC power. Plan the installation locations of these security sensors without using the Power Relay Switch and only use a router with backup battery for them. The router function of the Power Switch should **ONLY** be used to provide signal range extension for other Power Switches/Dimmer.

### _**Appliance Control**_

* After the Power Relay Switch has successfully joined a ZigBee network, the coordinator can remotely turn on/off the Appliance.
* You can also press the button on the Power Relay Switch to toggle on/off the light.
* You can turn on/off the Power Relay Switch with an external switch.
* If you have bound a controller with the Power Relay Switch, you can also use the controller to turn on/off the Power Relay Switch.
* If the AC Power input is disconnected from the Power Relay Switch, its previous on/off status will be restored within 1 minute after reconnecting the AC Power input to the Power Relay Switch.

### _**Energy Consumption Monitor (PRM5-ZBS/PRM5-ZBSR Only)**_

* The Power Relay Switch will transmit a signal with its power consumption data every two minutes to the ZigBee network coordinator.
* Whenever the Power Switch energy output changes by +/- 2W, it will automatically transmit a signal with power consumption data to the ZigBee network coordinator for update.
* The Power Switch transmits a signal with power data to coordinator whenever accumulated power usage increases by 0.1kW/hr.
* The Meter has an accuracy of +/- 5%.
* To clear the Power Switch of its accumulated power consumption data, follow steps below:
  1. Disconnect the Power Relay Switch from power outlet.
  2. Press and hold the function button and reconnect power when holding down the button.
  3. Keep holding the button and release after 3 seconds. The accumulated power consumption data will be cleared.

### _**Maximum Operation Load**_

* For 110V: the maximum operation load is 1100W and 10A.
* For 230V: the maximum operation load is 2300W and 10A.
* If the Power Relay Switch is overheating, it will cut off power automatically as a safety measure. The user must disconnect and reconnect AC power to the Power Relay Switch after cut off to resume normal operation.

## **Appendix (For developers only)**

### _**Power Relay Switch with Meter Cluster ID**_

<figure><img src=".gitbook/assets/image (162).png" alt=""><figcaption></figcaption></figure>

#### _**Attribute of Basic Cluster Information**_

<figure><img src=".gitbook/assets/image (163).png" alt=""><figcaption></figcaption></figure>

#### Attribute of Identify Cluster Information

<figure><img src=".gitbook/assets/image (164).png" alt=""><figcaption></figcaption></figure>

#### Attributes of the Groups cluster Information

<figure><img src=".gitbook/assets/image (165).png" alt=""><figcaption></figcaption></figure>

#### Attributes of the Scenes cluster Information

<figure><img src=".gitbook/assets/image (166).png" alt=""><figcaption></figcaption></figure>

#### _**Attribute of On/Off Cluster Information**_

<figure><img src=".gitbook/assets/image (167).png" alt=""><figcaption></figcaption></figure>

#### _**Attributes of the Metering cluster Information (Reading Information Attribute Set)**_

<figure><img src=".gitbook/assets/image (168).png" alt=""><figcaption></figcaption></figure>

#### _**Attributes of the Metering cluster Information (Formatting Attribute Set)**_

<figure><img src=".gitbook/assets/image (169).png" alt=""><figcaption></figcaption></figure>

_**Attributes of the Metering cluster Information (Historical Attribute Set)**_

<figure><img src=".gitbook/assets/image (170).png" alt=""><figcaption></figcaption></figure>
